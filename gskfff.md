代发 wailian999

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.andypj.xyz/Article/details/gtmwnrpirr.html

[S13] C：宏定义
来源：http://dali.jinghuilouyu.cn/Article/details/gtpqmnlzga.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.yueranfly.top/Article/details/gtgxxkhaqt.html

[S14] C：枚举
来源：http://dali.ybcxt.top/Article/details/gthiqsyslv.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.sufxvd.cn/Article/details/gtrhkjaplt.html

[S15] C：类型转换
来源：http://dali.chenjidiqi.icu/Article/details/gtckzadxfr.html

(double) a / b
来源：http://dali.jianghu66.top/Article/details/gtmjxzfxax.html

[S16] C：位操作置位
来源：http://dali.sweek.top/Article/details/gtxfwritym.html

x |= (1 << 3);
来源：http://dali.sufxvd.cn/Article/details/gtojbjnudr.html

[S17] C：安全拼接字符串
来源：http://dali.pengpengdd.cyou/Article/details/gtmfcitvqw.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.nwbrower.top/Article/details/gtnlcmepuu.html

[S18] C：命令行参数
来源：http://dali.yongpay.top/Article/details/gtvyfczucb.html

int main(int argc, char **argv)
来源：http://dali.zhixingplan.top/Article/details/gtwojgnoes.html

[S19] C：快速排序
来源：http://dali.cheryme.top/Article/details/gtnrqplurh.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.yuxming.cn/Article/details/gtyntthagd.html

[S20] C：二分查找
来源：http://dali.yanxiufei.cn/Article/details/gtuexbancn.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.yongpay.top/Article/details/gtkiitdfsl.html

[S21] C：字符类别判断
来源：http://dali.yj20258888.top/Article/details/gtyutdtrcx.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.pycfn.com/Article/details/gtycicqdet.html

[S22] C：字符串转数字
来源：http://dali.316326.xyz/Article/details/gthfqtmier.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.shangyingyoupin.top/Article/details/gtskydcpbs.html

[S23] C：随机数
来源：http://dali.jqgfzy.top/Article/details/gtkrsnrreg.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhongyouzk.top/Article/details/gthqptfabt.html

[S24] C：获取本地时间
来源：http://dali.gotoacloud.top/Article/details/gtqlwcalnh.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhengqikj.top/Article/details/gtynpksece.html

[S25] C：内存拷贝
来源：http://dali.yj202588.top/Article/details/gtmyxfexwd.html

memcpy(dst, src, n);
来源：http://dali.iojbl.cn/Article/details/gtxlzhdwqn.html

[S26] C：内存清零
来源：http://dali.fengsongda.top/Article/details/gtxhkmvodf.html

memset(a, 0, sizeof a);
来源：http://dali.pengpengdd.cyou/Article/details/gtzebdbiuk.html

[S27] C：定义常量
来源：http://dali.shanyushiyangtech.top/Article/details/gtpemgfsge.html

const double PI = 3.14159;
来源：http://dali.redwolf501.top/Article/details/gtivtrmand.html

[S28] C：静态变量
来源：http://dali.feifeiyinyue.top/Article/details/gtgxqlwdzo.html

static int counter = 0;
来源：http://dali.hywenlv.cn/Article/details/gtrslshbcb.html

[S29] C：变参函数
来源：http://dali.guannengcc.top/Article/details/gtkqvktcbp.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.sxryk.cn/Article/details/gtbcvucqkx.html

[S30] C：头文件保护
来源：http://dali.hnqzz.top/Article/details/gtygdozklz.html

#ifndef X_H
来源：http://dali.shangyingyoupin.top/Article/details/gtfjttiwpo.html

#define X_H
来源：http://dali.hongshengwenyu.top/Article/details/gthllctegs.html

#endif
来源：http://dali.andypj.xyz/Article/details/gtegfsgepd.html

[S31] C++：Hello World
来源：http://dali.pycfn.com/Article/details/gtulneojqo.html

#include <iostream>
来源：http://dali.kuanghao11.cn/Article/details/gtzmxperpa.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.sysykeji.top/Article/details/gtoaefuwcv.html

[S32] C++：字符串
来源：http://dali.pycfn.com/Article/details/gtvwbqbbha.html

std::string s = "hi";  s += "!";
来源：http://dali.andypj.xyz/Article/details/gtfuhblvfj.html

[S33] C++：vector 增删
来源：http://dali.316326.xyz/Article/details/gtvtgxgxag.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.ybcxt.top/Article/details/gtsvcuvrbr.html

[S34] C++：遍历 vector
来源：http://dali.aibaodan.cn/Article/details/gtgphtbwcl.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.sxryk.cn/Article/details/gtqdqgkrus.html

[S35] C++：map
来源：http://dali.yonumen.top/Article/details/gtjoisiivu.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jiagoushi.top/Article/details/gtnwmehcnv.html

[S36] C++：unordered_map
来源：http://dali.aizwys.cn/Article/details/gtlcrmhtul.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hongshengwenyu.top/Article/details/gtujmeccrx.html

[S37] C++：set
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuusxrtqz.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.smart0.xyz/Article/details/gtzeonecmn.html

[S38] C++：排序
来源：http://dali.yuanzhike.top/Article/details/gtpyqxkywf.html

std::sort(v.begin(), v.end());
来源：http://dali.dianchejie.cn/Article/details/gtltflxing.html

[S39] C++：自定义比较器排序
来源：http://dali.smart0.xyz/Article/details/gtzefjzdwp.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.jinyuanbaomall.cn/Article/details/gtudyisudw.html

[S40] C++：查找元素
来源：http://dali.yongpay.top/Article/details/gtfywbkwyt.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtffdrzndl.html

[S41] C++：类与构造函数
来源：http://dali.gaohongyu789.top/Article/details/gtiiwomwxo.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.cucudq.cn/Article/details/gtluxcvpho.html

[S42] C++：继承与虚函数
来源：http://dali.yuanzhike.top/Article/details/gtsuytnexi.html

class B : public Base { public: void f() override {} };
来源：http://dali.yj20258.top/Article/details/gtphczzzsm.html

[S43] C++：智能指针
来源：http://dali.haohaochexian.top/Article/details/gtmfpqxbyv.html

auto p = std::make_unique<int>(5);
来源：http://dali.yuxming.cn/Article/details/gtjstnscre.html

[S44] C++：引用传参
来源：http://dali.yvedp.cn/Article/details/gtzgaapnfr.html

void inc(int &x) { ++x; }
来源：http://dali.cashguo.top/Article/details/gtohjielun.html

[S45] C++：lambda
来源：http://dali.daria6918.cn/Article/details/gtjouhxmly.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zycfv.cn/Article/details/gtdoizwzdw.html

[S46] C++：函数模板
来源：http://dali.tianlin.xyz/Article/details/gtfophldju.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhoulong.xyz/Article/details/gtgchsunib.html

[S47] C++：结构化绑定遍历
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrwqhlvpl.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.haohaochexian.top/Article/details/gtcieueuzq.html

[S48] C++：逐行读文件
来源：http://dali.fzhhl.top/Article/details/gtnbnfkzfc.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zdqjudy.top/Article/details/gtqwwpbwow.html

while (std::getline(in, line)) { }
来源：http://dali.xuanzx.com/Article/details/gtkyhcndlg.html

[S49] C++：写文件
来源：http://dali.xuanzx.com/Article/details/gtlrzeocxw.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.jlsjyb.cn/Article/details/gtqowipzvb.html

[S50] C++：格式化数字
来源：http://dali.jyoumei.cn/Article/details/gtfyqmfogl.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.hnqzz.top/Article/details/gtohosbrpd.html

[S51] C++：显式类型转换
来源：http://dali.havefunace.top/Article/details/gtdguxkncl.html

static_cast<double>(a) / b
来源：http://dali.zhoulong.xyz/Article/details/gtjmuioqwa.html

[S52] C++：const 与 noexcept
来源：http://dali.ppjwa.cn/Article/details/gttwtlnclm.html

int size() const noexcept { return n_; }
来源：http://dali.daxiang520.top/Article/details/gtlpfqcsvu.html

[S53] C++：移动语义
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtucwsciol.html

std::vector<int> w = std::move(v);
来源：http://dali.hammf.cn/Article/details/gtduwfeoqz.html

[S54] C++：异常处理
来源：http://dali.redwolf501.top/Article/details/gtcbhaknxd.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.gaohongyu789.top/Article/details/gtpfbozhii.html

[S55] C++：结构化绑定
来源：http://dali.ydzc1.top/Article/details/gtjqftalpx.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhongyouzk.top/Article/details/gtsechfirl.html

[S56] C++：optional
来源：http://dali.316326.xyz/Article/details/gthgzvzfhk.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.xziqi.cn/Article/details/gtltqtwyhv.html

[S57] C++：编译期常量
来源：http://dali.nwbrower.top/Article/details/gtpkgfuyuo.html

constexpr int N = 10;
来源：http://dali.fengsongda.top/Article/details/gtylfprahg.html

[S58] C++：命名空间
来源：http://dali.cucudq.cn/Article/details/gthkrhwqpw.html

namespace ns { int f() { return 1; } }
来源：http://dali.yvedp.cn/Article/details/gtiygqrdyc.html

[S59] C++：静态断言
来源：http://dali.dianchejie.cn/Article/details/gteqbqtjft.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.ppjwa.cn/Article/details/gtmehaxvea.html

[S60] C++：遍历并删除元素
来源：http://dali.jlsjyb.cn/Article/details/gtiuhbusem.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.shanyushiyangkeji.top/Article/details/gteubglibe.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtqxgtfpcv.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.cashguo.top/Article/details/gttsvvnmte.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtycujqgbp.html

[T01] Kotlin：Hello World
来源：http://dali.meibo888.top/Article/details/gtktozbfzz.html

println("Hello")
来源：http://dali.fengsongda.top/Article/details/gtespnvuzi.html

[T02] Kotlin：变量
来源：http://dali.yonumen.top/Article/details/gticufttrx.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.hfpthk.cn/Article/details/gtpljjhypq.html

[T03] Kotlin：字符串模板
来源：http://dali.cheryme.top/Article/details/gtuafwhopd.html

"值: $b"
来源：http://dali.cheryme.top/Article/details/gtaatvagrj.html

[T04] Kotlin：空安全
来源：http://dali.mhx1999.top/Article/details/gtchhntonw.html

val n: String? = null;  n?.length
来源：http://dali.wangshuangyany.cn/Article/details/gtiewfhpyq.html

[T05] Kotlin：when 表达式
来源：http://dali.jinghuilouyu.cn/Article/details/gthtadqouu.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.xuetiantiany.cn/Article/details/gthytpxfqi.html

[T06] Kotlin：集合映射
来源：http://dali.zhoulong.xyz/Article/details/gtgxjpnesv.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.9152youxi.cn/Article/details/gtjhxpczid.html

[T07] Kotlin：集合过滤
来源：http://dali.birdmap.top/Article/details/gtblroctpu.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.gogol.net.cn/Article/details/gtxmhjdyjl.html

[T08] Kotlin：数据类
来源：http://dali.zhengqikj.top/Article/details/gtkazzboga.html

data class User(val name: String, val age: Int)
来源：http://dali.cqqwz.cn/Article/details/gtwmiltuio.html

[T09] Kotlin：扩展函数
来源：http://dali.shangyingyoupin.top/Article/details/gtrnoxjthi.html

fun String.exclaim() = this + "!"
来源：http://dali.zhengqikj.top/Article/details/gtrrrabirq.html

[T10] Kotlin：默认参数
来源：http://dali.chenjidiqi.icu/Article/details/gtinkbzijr.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.pycfn.com/Article/details/gtwrwhyizq.html

[T11] Kotlin：协程
来源：http://dali.hammf.cn/Article/details/gtdohyhlin.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.yvedp.cn/Article/details/gtruhpjazf.html

[T12] Kotlin：解构声明
来源：http://dali.yangfankeji.com/Article/details/gtybefmsyk.html

val (a, b) = Pair(1, 2)
来源：http://dali.9152youxi.cn/Article/details/gtdnaycqxb.html

[T13] Kotlin：只读 Map
来源：http://dali.sweek.top/Article/details/gtesduistd.html

val m = mapOf("a" to 1)
来源：http://dali.zhixingplan.top/Article/details/gtzttjnywy.html

[T14] Kotlin：循环
来源：http://dali.aizwys.cn/Article/details/gtckmjmscq.html

for (i in 1..10) println(i)
来源：http://dali.ybcxt.top/Article/details/gtozhblqeo.html

[T15] Kotlin：接口
来源：http://dali.0kj1m.cn/Article/details/gtlzwkiigx.html

interface Shape { fun area(): Double }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqwiitpio.html

[T16] Swift：Hello World
来源：http://dali.sysykeji.top/Article/details/gtkbpvmtrk.html

print("Hello")
来源：http://dali.hnxiangtu.top/Article/details/gtskdfbfmb.html

[T17] Swift：变量与常量
来源：http://dali.andypj.xyz/Article/details/gtcarqgvrv.html

var a = 1;  let b = 2
来源：http://dali.vqdsnc.cn/Article/details/gtclalfadg.html

[T18] Swift：字符串插值
来源：http://dali.cashguo.top/Article/details/gtjabzrohb.html

"值: \(b)"
来源：http://dali.quarkkingdee.top/Article/details/gtctbynwrm.html

[T19] Swift：可选绑定
来源：http://dali.zhixingplan.top/Article/details/gttgahbcqn.html

if let n = opt { print(n) }
来源：http://dali.mhx1999.top/Article/details/gtixamtmbh.html

[T20] Swift：数组操作
来源：http://dali.zhiwuduotai.top/Article/details/gtevcbgmvv.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.wangdashe.top/Article/details/gtvgwgdyvm.html

[T21] Swift：遍历
来源：http://dali.gaohongyu789.top/Article/details/gtgsadvgue.html

for x in a { print(x) }
来源：http://dali.yueranfly.top/Article/details/gtlnkerdju.html

[T22] Swift：字典
来源：http://dali.xinyue.icu/Article/details/gtqodbnnrv.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.ydzc1.top/Article/details/gtnvswfamb.html

[T23] Swift：函数
来源：http://dali.yj20258.top/Article/details/gtrpybvwls.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.bjfxy.top/Article/details/gtgkdwcoid.html

[T24] Swift：闭包
来源：http://dali.mhx1999.top/Article/details/gtwcvoihmk.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.xinyue.icu/Article/details/gtilmqpulc.html

[T25] Swift：结构体
来源：http://dali.ehwqpu.com/Article/details/gtqfxqeazl.html

struct P { var x: Int }
来源：http://dali.andypj.xyz/Article/details/gttloxkvlv.html

[T26] Swift：类与重写
来源：http://dali.cashguo.top/Article/details/gtyfcnmuii.html

class A: Base { override func f() {} }
来源：http://dali.dianchejie.cn/Article/details/gtfgwoicbs.html

[T27] Swift：错误处理
来源：http://dali.hammf.cn/Article/details/gtqoplewjw.html

do { try f() } catch { print(error) }
来源：http://dali.tianlin.xyz/Article/details/gtemedxvre.html

[T28] Swift：枚举
来源：http://dali.nanxuanxn.top/Article/details/gtqwwlknej.html

enum Color { case red, green }
来源：http://dali.nwbrower.top/Article/details/gtjskdzulr.html

[T29] Swift：guard 提前返回
来源：http://dali.gotoacloud.top/Article/details/gtjionsavr.html

guard let x = opt else { return }
来源：http://dali.yj20258.top/Article/details/gtrlccqdzf.html

[T30] Swift：协议
来源：http://dali.9152youxi.cn/Article/details/gtbhsvxfhj.html

protocol Shape { func area() -> Double }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkgbbvwib.html

[T31] Lua：Hello World
来源：http://dali.zycfv.cn/Article/details/gtdizwbbqs.html

print("Hello")
来源：http://dali.9152youxi.cn/Article/details/gtbktmcmmw.html

[T32] Lua：局部变量
来源：http://dali.fzhhl.top/Article/details/gtqrqbvkky.html

local a = 1
来源：http://dali.gotoacloud.top/Article/details/gtyzciirix.html

[T33] Lua：表（数组）
来源：http://dali.cheryme.top/Article/details/gtppbgdkgw.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.quarkkingdee.top/Article/details/gtirkrwzmy.html

[T34] Lua：遍历表
来源：http://dali.aizwys.cn/Article/details/gtlfvkrsqg.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.chenzaomai.com/Article/details/gtbztuztfz.html

[T35] Lua：字典表
来源：http://dali.yonumen.top/Article/details/gtxmjrbhqn.html

local d = { a = 1 };  d.b = 2
来源：http://dali.daria6918.cn/Article/details/gtpqctejce.html

[T36] Lua：函数
来源：http://dali.ehwqpu.com/Article/details/gtoqeroems.html

function add(a, b) return a + b end
来源：http://dali.zhixingplan.top/Article/details/gthlownynd.html

[T37] Lua：字符串拼接
来源：http://dali.sysykeji.top/Article/details/gtzzqrazet.html

"a" .. "b"
来源：http://dali.yuxming.cn/Article/details/gtrhtptkbl.html

[T38] Lua：条件
来源：http://dali.jyoumei.cn/Article/details/gtzdypkpfe.html

if x > 0 then print("正") end
来源：http://dali.chenlongwang.top/Article/details/gtxgulhhqf.html

[T39] Lua：模式匹配
来源：http://dali.gotoacloud.top/Article/details/gtyzzbjbnr.html

string.find(s, "%d+")
来源：http://dali.dianchejie.cn/Article/details/gttmadpodo.html

[T40] Lua：元表
来源：http://dali.gotoacloud.top/Article/details/gtbrwqjvgj.html

setmetatable({}, { __index = base })
来源：http://dali.guannengcc.top/Article/details/gtwczdgziv.html

[T41] Perl：Hello World
来源：http://dali.wangshuangyany.cn/Article/details/gtywmtnhpj.html

print "Hello\n";
来源：http://dali.smart0.xyz/Article/details/gtedirnjwu.html

[T42] Perl：变量类型
来源：http://dali.svipenyu.cn/Article/details/gtnxhlafml.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.kuanghao11.cn/Article/details/gtrxsytepr.html

[T43] Perl：字符串插值
来源：http://dali.shanyushiyangtech.top/Article/details/gtarbthtie.html

"值: $a"
来源：http://dali.xinyue.icu/Article/details/gttojuqtft.html

[T44] Perl：条件
来源：http://dali.xuanzx.com/Article/details/gtkwznjslg.html

if ($a > 0) { print "正"; }
来源：http://dali.shzxlz.cn/Article/details/gtederkkkn.html

[T45] Perl：数组遍历
来源：http://dali.svipenyu.cn/Article/details/gtunvjgavw.html

for my $x (@arr) { print $x; }
来源：http://dali.sxryk.cn/Article/details/gtbysjleow.html

[T46] Perl：哈希操作
来源：http://dali.hammf.cn/Article/details/gtxxknfwuw.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjcklfqlq.html

[T47] Perl：正则捕获
来源：http://dali.pengpengdd.cyou/Article/details/gtoufnpjxb.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.yj20258888.top/Article/details/gtqjugwwev.html

[T48] Perl：正则替换
来源：http://dali.tianlin.xyz/Article/details/gtrtznpzhr.html

$s =~ s/old/new/g;
来源：http://dali.cashguo.top/Article/details/gtozeljkuz.html

[T49] Perl：函数
来源：http://dali.redwolf501.top/Article/details/gtywqnbkzu.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.nwbrower.top/Article/details/gtxohddkeb.html

[T50] Perl：逐行读文件
来源：http://dali.feifeiyinyue.top/Article/details/gtpdnxqbvj.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.sufxvd.cn/Article/details/gthbbezvmm.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.yvedp.cn/Article/details/gtsptftjyr.html

[T51] Scala：Hello World
来源：http://dali.yvedp.cn/Article/details/gtmghwmhmm.html

println("Hello")
来源：http://dali.ehwqpu.com/Article/details/gtfkkgosoy.html

[T52] Scala：变量
来源：http://dali.smart0.xyz/Article/details/gtvrjyliat.html

val a = 1;  var b = 2
来源：http://dali.cucudq.cn/Article/details/gtultmahgn.html

[T53] Scala：字符串插值
来源：http://dali.snrcjt.cn/Article/details/gtkrcoevbk.html

s"值: $b"
来源：http://dali.aibaodan.cn/Article/details/gtqyeiwfvt.html

[T54] Scala：集合映射
来源：http://dali.hfpthk.cn/Article/details/gtiyvbjycn.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.jqgufenzy.top/Article/details/gtqpgqsjip.html

[T55] Scala：集合过滤
来源：http://dali.hfpthk.cn/Article/details/gtwsutbgnq.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.cashguo.top/Article/details/gtrxgarizh.html

[T56] Scala：样例类
来源：http://dali.zhiwuduotai.top/Article/details/gtrkpbzkil.html

case class User(name: String, age: Int)
来源：http://dali.mhx1999.top/Article/details/gtgptngyhu.html

[T57] Scala：模式匹配
来源：http://dali.0kj1m.cn/Article/details/gtauqjofgw.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.havefunace.top/Article/details/gtfqxcouok.html

[T58] Scala：函数定义
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttjgeboyz.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.shangyingyoupin.top/Article/details/gtlcccabfz.html

[T59] Scala：循环
来源：http://dali.haohaochexian.top/Article/details/gtmpoisgsq.html

for (i <- 1 to 10) println(i)
来源：http://dali.kuanghao11.cn/Article/details/gtubfxxdeq.html

[T60] Scala：折叠
来源：http://dali.yanxiufei.cn/Article/details/gtxmyioelo.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.0kj1m.cn/Article/details/gtespcluhk.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtftmnbquc.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.tian-w.cn/Article/details/gtaphbbcnr.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaaqcthvx.html

[U01] Py：创建虚拟环境
来源：http://dali.yuanzhike.top/Article/details/gtavkdxxff.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhiwuduotai.top/Article/details/gtszbetpre.html

[U02] Py：导出 / 安装依赖
来源：http://dali.ydzc1.top/Article/details/gtfwfgesxb.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gtbperwufh.html

[U03] Py：加载 .env 配置
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvjgcqecu.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.xziqi.cn/Article/details/gtlwuhzzuf.html

[U04] Py：变量调试打印
来源：http://dali.yj20258888.top/Article/details/gtiyzjplbj.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.pengpengdd.cyou/Article/details/gtnfgiglju.html

[U05] Py：列表去重且保序
来源：http://dali.birdmap.top/Article/details/gtkjcilhcv.html

list(dict.fromkeys(arr))
来源：http://dali.sufxvd.cn/Article/details/gtepknwqor.html

[U06] Py：合并两个字典
来源：http://dali.wangdashe.top/Article/details/gtbcbruirs.html

{**a, **b}
来源：http://dali.meibo888.top/Article/details/gtytnsumxu.html

[U07] Py：反转字典键值
来源：http://dali.haohaochexian.top/Article/details/gtcdrkhbzs.html

{v: k for k, v in d.items()}
来源：http://dali.zhixingplan.top/Article/details/gthyhrlypg.html

[U08] Py：展平二维列表
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrjvdwnjg.html

[y for x in nested for y in x]
来源：http://dali.daxiang520.top/Article/details/gtubgezglg.html

[U09] Py：字典取最大值的键
来源：http://dali.jinyuanbaomall.cn/Article/details/gtidjsorqq.html

max(d, key=d.get)
来源：http://dali.zhiwuduotai.top/Article/details/gtisxyoxzt.html

[U10] Py：按值排序字典
来源：http://dali.shzxlz.cn/Article/details/gtdxmvdrtc.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnhytozmo.html

[U11] Py：生成器表达式
来源：http://dali.sxryk.cn/Article/details/gtivrdotos.html

(x * 2 for x in arr)
来源：http://dali.sxryk.cn/Article/details/gtspchrcjl.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.yanxiufei.cn/Article/details/gtdejgsnke.html

Counter(arr).most_common(3)
来源：http://dali.tanke756.top/Article/details/gtuyuoyfaf.html

[U13] Py：固定长度队列
来源：http://dali.meibo888.top/Article/details/gtfqfffhpv.html

deque(maxlen=10)
来源：http://dali.yongpay.top/Article/details/gtaggpcubk.html

[U14] Py：分组收集到列表
来源：http://dali.aibaodan.cn/Article/details/gtdelpnepd.html

defaultdict(list)
来源：http://dali.redwolf501.top/Article/details/gtlmlrbjmr.html

[U15] Py：高精度计时
来源：http://dali.zhaomingkeji.xyz/Article/details/gtemwmruvi.html

t = time.perf_counter()
来源：http://dali.pycfn.com/Article/details/gtpwcrduny.html

[U16] Py：命令行参数解析
来源：http://dali.jqgufenzy.top/Article/details/gtttffsirl.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.sweek.top/Article/details/gtyjxfybka.html

[U17] Py：初始化日志
来源：http://dali.yuxming.cn/Article/details/gtwcbpebyp.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.andypj.xyz/Article/details/gtnyumigbg.html

[U18] Py：预编译正则
来源：http://dali.birdmap.top/Article/details/gtoewnplft.html

pat = re.compile(r"\d+")
来源：http://dali.9152youxi.cn/Article/details/gtxetvnbpe.html

[U19] Py：正则替换带回调
来源：http://dali.bjfxy.top/Article/details/gtfehpcquv.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.wangshuangyany.cn/Article/details/gtjxqtyecb.html

[U20] Py：缓存函数结果
来源：http://dali.chenzaomai.com/Article/details/gtxgycdnri.html

@functools.lru_cache(maxsize=None)
来源：http://dali.hywenlv.cn/Article/details/gtzxdlunch.html

[U21] Py：自定义上下文管理器
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttpmztcbl.html

@contextlib.contextmanager
来源：http://dali.chenzaomai.com/Article/details/gtrwmtxqdc.html

[U22] Py：矩阵转置
来源：http://dali.zdqjudy.top/Article/details/gtcsvstste.html

list(zip(*m))
来源：http://dali.andypj.xyz/Article/details/gtbuvefezl.html

[U23] Py：分块读取大文件
来源：http://dali.fzhhl.top/Article/details/gtrkqpeogy.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.aizwys.cn/Article/details/gtszdofnwl.html

[U24] Py：路径操作
来源：http://dali.yueranfly.top/Article/details/gtutsohuqu.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.tanke756.top/Article/details/gttzrambui.html

[U25] Py：CSV 按字典读
来源：http://dali.zhiwuduotai.top/Article/details/gtmspuapcl.html

csv.DictReader(f)
来源：http://dali.jqgfzy.top/Article/details/gtddhefdfs.html

[U26] Py：并发下载
来源：http://dali.316326.xyz/Article/details/gtlivdqzil.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.daxiang520.top/Article/details/gtnncuhdij.html

[U27] Py：异步 HTTP
来源：http://dali.cashguo.top/Article/details/gtzdwieqjs.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.pycfn.com/Article/details/gtaccgwfym.html

[U28] Py：类型别名
来源：http://dali.fzhhl.top/Article/details/gtoqhmvrzh.html

UserId = int
来源：http://dali.zhengqikj.top/Article/details/gtwyfseugn.html

[U29] Py：属性校验
来源：http://dali.tian-w.cn/Article/details/gtakvuqdxb.html

@property 与 @x.setter 配合
来源：http://dali.shuidangran.top/Article/details/gthuyfffcv.html

[U30] Py：数据类
来源：http://dali.mhx1999.top/Article/details/gtaezvplrh.html

@dataclass(slots=True)
来源：http://dali.cashguo.top/Article/details/gtoagcsrio.html

[U31] Py：单测
来源：http://dali.cucudq.cn/Article/details/gterkjzjrg.html

python -m pytest -q
来源：http://dali.kuanghao11.cn/Article/details/gttnnlfczr.html

[U32] Py：代码格式化
来源：http://dali.zycfv.cn/Article/details/gttwjlkcew.html

ruff format . && ruff check --fix .
来源：http://dali.zdqjudy.top/Article/details/gtjrphhelc.html

[U33] Py：打包发布
来源：http://dali.iojbl.cn/Article/details/gtzcsfypck.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.jiagoushi.top/Article/details/gtzjssbqrk.html

[U34] Py：判断编码
来源：http://dali.zhongyouzk.top/Article/details/gtzihbwxeg.html

chardet.detect(raw)
来源：http://dali.yj20258.top/Article/details/gtktubkdhu.html

[U35] Py：发送邮件
来源：http://dali.chenlongwang.top/Article/details/gtgeemzkvu.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.aizwys.cn/Article/details/gtebiyozrl.html

[U36] Py：定时任务
来源：http://dali.daxiang520.top/Article/details/gtczwxonkk.html

schedule.every(10).minutes.do(job)
来源：http://dali.sxryk.cn/Article/details/gthzxebebq.html


<!-- 参考信息 -->