代发 wailian999

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.quarkkingdee.top/Article/details/gtjvevnyqx.html

[S08] C：动态内存分配与释放
来源：http://dali.316326.xyz/Article/details/gtpbbxxirr.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvutikqbq.html

[S09] C：结构体定义与初始化
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdffhknxr.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.0kj1m.cn/Article/details/gtjmozuplm.html

[S10] C：指针与解引用
来源：http://dali.cqqwz.cn/Article/details/gtssifaeum.html

int *p = &a;  *p = 5;
来源：http://dali.zhaomingkeji.xyz/Article/details/gttubrikzn.html

[S11] C：逐行读文件
来源：http://dali.yvedp.cn/Article/details/gtpqplfvsq.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.dashuyun.cn/Article/details/gtzhcfuqke.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.jqgufenzy.top/Article/details/gtikzrwsst.html

fclose(f);
来源：http://dali.cdnleiting.top/Article/details/gtkxqnknpm.html

[S12] C：写文件
来源：http://dali.9152youxi.cn/Article/details/gtdvdqchxh.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.cqqwz.cn/Article/details/gtjfouutxm.html

[S13] C：宏定义
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthyouzzeh.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.feifeiyinyue.top/Article/details/gtjepgqmoe.html

[S14] C：枚举
来源：http://dali.yuanzhike.top/Article/details/gthcbhuzyc.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.cdnleiting.top/Article/details/gthjmgfegp.html

[S15] C：类型转换
来源：http://dali.aibaodan.cn/Article/details/gthtvfwaeo.html

(double) a / b
来源：http://dali.aibaodan.cn/Article/details/gtylralhpb.html

[S16] C：位操作置位
来源：http://dali.sysykeji.top/Article/details/gtumxlwlif.html

x |= (1 << 3);
来源：http://dali.hysaishi.cn/Article/details/gtwoakgsps.html

[S17] C：安全拼接字符串
来源：http://dali.chenlongwang.top/Article/details/gtvgqzceco.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.c1oappe.top/Article/details/gtpuigjlvw.html

[S18] C：命令行参数
来源：http://dali.hongshengwenyu.top/Article/details/gtmqhknvaa.html

int main(int argc, char **argv)
来源：http://dali.yangfankeji.com/Article/details/gtwvogqnsk.html

[S19] C：快速排序
来源：http://dali.sufxvd.cn/Article/details/gtgvxiious.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.shangyingyoupin.top/Article/details/gtnnlwbapp.html

[S20] C：二分查找
来源：http://dali.sweek.top/Article/details/gtdggeuqtp.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.wangdashe.top/Article/details/gtilioarsx.html

[S21] C：字符类别判断
来源：http://dali.hnxiangtu.top/Article/details/gtyxceldhl.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.svipenyu.cn/Article/details/gtomrrparn.html

[S22] C：字符串转数字
来源：http://dali.yanxiufei.cn/Article/details/gttclwvylk.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.cdnleiting.top/Article/details/gteqzscocf.html

[S23] C：随机数
来源：http://dali.pycfn.com/Article/details/gtocptzogy.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.dashuyun.cn/Article/details/gtegecoorr.html

[S24] C：获取本地时间
来源：http://dali.daria6918.cn/Article/details/gtmmdraice.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.vqdsnc.cn/Article/details/gtdmkuitwv.html

[S25] C：内存拷贝
来源：http://dali.xuetiantiany.cn/Article/details/gtrlndzaeq.html

memcpy(dst, src, n);
来源：http://dali.yongpay.top/Article/details/gtsgejjbtv.html

[S26] C：内存清零
来源：http://dali.smart0.xyz/Article/details/gtamnqmeru.html

memset(a, 0, sizeof a);
来源：http://dali.jyoumei.cn/Article/details/gtxjabsnap.html

[S27] C：定义常量
来源：http://dali.cashguo.top/Article/details/gtqybnnmvr.html

const double PI = 3.14159;
来源：http://dali.guowangkeji.top/Article/details/gtbkhshxmb.html

[S28] C：静态变量
来源：http://dali.c1oappe.top/Article/details/gtiuaffuoe.html

static int counter = 0;
来源：http://dali.cheryme.top/Article/details/gtkwmgjkao.html

[S29] C：变参函数
来源：http://dali.hfpthk.cn/Article/details/gthzkmnbmv.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.hnxiangtu.top/Article/details/gtsotsqhvg.html

[S30] C：头文件保护
来源：http://dali.cucudq.cn/Article/details/gtfogeolic.html

#ifndef X_H
来源：http://dali.cdnleiting.top/Article/details/gtmmsfquul.html

#define X_H
来源：http://dali.jiagoushi.top/Article/details/gtddknclmk.html

#endif
来源：http://dali.zhixingplan.top/Article/details/gtocokizqs.html

[S31] C++：Hello World
来源：http://dali.jlsjyb.cn/Article/details/gtajjirhwj.html

#include <iostream>
来源：http://dali.jiagoushi.top/Article/details/gtvwegkbys.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.cucudq.cn/Article/details/gtndagxiud.html

[S32] C++：字符串
来源：http://dali.fzhhl.top/Article/details/gtyuafvyfz.html

std::string s = "hi";  s += "!";
来源：http://dali.quarkkingdee.top/Article/details/gtowyxmpwk.html

[S33] C++：vector 增删
来源：http://dali.yj202588.top/Article/details/gtezwaruvj.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbkqjpjpi.html

[S34] C++：遍历 vector
来源：http://dali.feifeiyinyue.top/Article/details/gtakbkpldh.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjunxjalj.html

[S35] C++：map
来源：http://dali.tanke756.top/Article/details/gtcspasnwl.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.cqqwz.cn/Article/details/gtmeqlewru.html

[S36] C++：unordered_map
来源：http://dali.haohaochexian.top/Article/details/gthrvaowxf.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gtweofnoym.html

[S37] C++：set
来源：http://dali.hfpthk.cn/Article/details/gtxeutuvuw.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.hammf.cn/Article/details/gtfcsokier.html

[S38] C++：排序
来源：http://dali.tianlin.xyz/Article/details/gtkkaibbwq.html

std::sort(v.begin(), v.end());
来源：http://dali.andypj.xyz/Article/details/gtrdadokpz.html

[S39] C++：自定义比较器排序
来源：http://dali.redwolf501.top/Article/details/gtkpdpvjut.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.shanyushiyangkeji.top/Article/details/gtphoduwmv.html

[S40] C++：查找元素
来源：http://dali.gogol.net.cn/Article/details/gtbavytsuh.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.cheryme.top/Article/details/gtybvuxzek.html

[S41] C++：类与构造函数
来源：http://dali.aibaodan.cn/Article/details/gtyciioohv.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.cdnleiting.top/Article/details/gtwyukgwgm.html

[S42] C++：继承与虚函数
来源：http://dali.chenzaomai.com/Article/details/gtndknrtmm.html

class B : public Base { public: void f() override {} };
来源：http://dali.jyoumei.cn/Article/details/gtgbmbfjud.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gtnfwrueiz.html

auto p = std::make_unique<int>(5);
来源：http://dali.yj20258.top/Article/details/gtmidfxdny.html

[S44] C++：引用传参
来源：http://dali.cheryme.top/Article/details/gtzeqenlkm.html

void inc(int &x) { ++x; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtpnodmity.html

[S45] C++：lambda
来源：http://dali.yongpay.top/Article/details/gtwlwnwhxp.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.jyoumei.cn/Article/details/gtallidbja.html

[S46] C++：函数模板
来源：http://dali.pycfn.com/Article/details/gtzfbloezv.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zycfv.cn/Article/details/gtijfjtujo.html

[S47] C++：结构化绑定遍历
来源：http://dali.yj202588.top/Article/details/gttpyyucap.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.jinqigfzy.top/Article/details/gtdmrvvful.html

[S48] C++：逐行读文件
来源：http://dali.dashuyun.cn/Article/details/gtttyaulfn.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.yj202588.top/Article/details/gtkcytgksf.html

while (std::getline(in, line)) { }
来源：http://dali.shangyingyoupin.top/Article/details/gtmjhgiizl.html

[S49] C++：写文件
来源：http://dali.kuanghao11.cn/Article/details/gtsozfrill.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.sufxvd.cn/Article/details/gtdnpvxuvk.html

[S50] C++：格式化数字
来源：http://dali.xziqi.cn/Article/details/gtajxzucbn.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.nanxinkj.top/Article/details/gtnlqmtawx.html

[S51] C++：显式类型转换
来源：http://dali.pycfn.com/Article/details/gtxcffbwia.html

static_cast<double>(a) / b
来源：http://dali.xylfe.cn/Article/details/gtjceyxfqh.html

[S52] C++：const 与 noexcept
来源：http://dali.zhengqikj.top/Article/details/gtrajenmvp.html

int size() const noexcept { return n_; }
来源：http://dali.ydzc1.top/Article/details/gtnwwywtir.html

[S53] C++：移动语义
来源：http://dali.pengpengdd.cyou/Article/details/gtundrwzee.html

std::vector<int> w = std::move(v);
来源：http://dali.shuidangran.top/Article/details/gtitnabwzs.html

[S54] C++：异常处理
来源：http://dali.gzhubu.top/Article/details/gtzfnvjzmv.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.daxiang520.top/Article/details/gtpvzwgqtd.html

[S55] C++：结构化绑定
来源：http://dali.kuanghao11.cn/Article/details/gtbgarcuga.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcjkoktba.html

[S56] C++：optional
来源：http://dali.mhx1999.top/Article/details/gtmyfrhnuj.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gtcvfsbzea.html

[S57] C++：编译期常量
来源：http://dali.zhoulong.xyz/Article/details/gtfiwyetwe.html

constexpr int N = 10;
来源：http://dali.fzhhl.top/Article/details/gtihrjaspf.html

[S58] C++：命名空间
来源：http://dali.cdnleiting.top/Article/details/gtllicsdko.html

namespace ns { int f() { return 1; } }
来源：http://dali.ydzc1.top/Article/details/gtvumcsqbj.html

[S59] C++：静态断言
来源：http://dali.hnqzz.top/Article/details/gtdehioyvp.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhiwuduotai.top/Article/details/gtltjcmshl.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gteaimztvz.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.yonumen.top/Article/details/gtdkamcbzg.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gttbcvzyuf.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.nanxinkj.top/Article/details/gtmvxadygp.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtktryigiz.html

[T01] Kotlin：Hello World
来源：http://dali.ppjwa.cn/Article/details/gttokguiey.html

println("Hello")
来源：http://dali.zdqjudy.top/Article/details/gtniyftixw.html

[T02] Kotlin：变量
来源：http://dali.hnqzz.top/Article/details/gtkvtclhai.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhongyouzk.top/Article/details/gtkhkkjoic.html

[T03] Kotlin：字符串模板
来源：http://dali.yongpay.top/Article/details/gtwsgdzzmn.html

"值: $b"
来源：http://dali.yueranfly.top/Article/details/gtbfomwaxw.html

[T04] Kotlin：空安全
来源：http://dali.jinqigfzy.top/Article/details/gtqaghgdib.html

val n: String? = null;  n?.length
来源：http://dali.zdqjudy.top/Article/details/gtwjpuwogh.html

[T05] Kotlin：when 表达式
来源：http://dali.vqdsnc.cn/Article/details/gtcwrkrvtz.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.daxiang520.top/Article/details/gtocqdoefm.html

[T06] Kotlin：集合映射
来源：http://dali.nanxuanxn.top/Article/details/gtmgoxlfyk.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.cheryme.top/Article/details/gtlfoxdhpz.html

[T07] Kotlin：集合过滤
来源：http://dali.pycfn.com/Article/details/gtnawgaoux.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhiwuduotai.top/Article/details/gtapjjvbfc.html

[T08] Kotlin：数据类
来源：http://dali.fzhhl.top/Article/details/gtgfgnwbxm.html

data class User(val name: String, val age: Int)
来源：http://dali.nanxuanxn.top/Article/details/gtyvlxxmws.html

[T09] Kotlin：扩展函数
来源：http://dali.chenlongwang.top/Article/details/gtlvcgmtxy.html

fun String.exclaim() = this + "!"
来源：http://dali.cashguo.top/Article/details/gthyuimpnf.html

[T10] Kotlin：默认参数
来源：http://dali.fzhhl.top/Article/details/gtoyjkicag.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.cashguo.top/Article/details/gtyhugqlqj.html

[T11] Kotlin：协程
来源：http://dali.hnqzz.top/Article/details/gttifjmwln.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.ehwqpu.com/Article/details/gtvzmikhni.html

[T12] Kotlin：解构声明
来源：http://dali.shanyushiyangtech.top/Article/details/gtdelubvbe.html

val (a, b) = Pair(1, 2)
来源：http://dali.andypj.xyz/Article/details/gtsiaquxte.html

[T13] Kotlin：只读 Map
来源：http://dali.shzxlz.cn/Article/details/gtarldrxco.html

val m = mapOf("a" to 1)
来源：http://dali.smart0.xyz/Article/details/gtvexwqkxl.html

[T14] Kotlin：循环
来源：http://dali.nwbrower.top/Article/details/gtoicrznml.html

for (i in 1..10) println(i)
来源：http://dali.iojbl.cn/Article/details/gtzhiubvic.html

[T15] Kotlin：接口
来源：http://dali.yangfankeji.com/Article/details/gtnevrjpol.html

interface Shape { fun area(): Double }
来源：http://dali.haohaochexian.top/Article/details/gtatupsrls.html

[T16] Swift：Hello World
来源：http://dali.wangdashe.top/Article/details/gtaljhcuwc.html

print("Hello")
来源：http://dali.sufxvd.cn/Article/details/gtdvoryiqj.html

[T17] Swift：变量与常量
来源：http://dali.hywenlv.cn/Article/details/gtsaqekxmm.html

var a = 1;  let b = 2
来源：http://dali.cashguo.top/Article/details/gtlzbwymmj.html

[T18] Swift：字符串插值
来源：http://dali.hnqzz.top/Article/details/gtcgzlnaqe.html

"值: \(b)"
来源：http://dali.haohaochexian.top/Article/details/gtehnblzto.html

[T19] Swift：可选绑定
来源：http://dali.cucudq.cn/Article/details/gttylwulln.html

if let n = opt { print(n) }
来源：http://dali.xylfe.cn/Article/details/gtyfmrcyun.html

[T20] Swift：数组操作
来源：http://dali.sufxvd.cn/Article/details/gtwaunyaxr.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.haohaochexian.top/Article/details/gtdjxvwknb.html

[T21] Swift：遍历
来源：http://dali.fengsongda.top/Article/details/gtpvgromed.html

for x in a { print(x) }
来源：http://dali.jiagoushi.top/Article/details/gtzbtaqlui.html

[T22] Swift：字典
来源：http://dali.yanxiufei.cn/Article/details/gtyqbgnsjg.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.havefunace.top/Article/details/gtzpkjsuas.html

[T23] Swift：函数
来源：http://dali.9152youxi.cn/Article/details/gtbeoljahf.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.yuxming.cn/Article/details/gtyariqpdt.html

[T24] Swift：闭包
来源：http://dali.jinghuilouyu.cn/Article/details/gtzuhjaolw.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.guannengcc.top/Article/details/gtqoplncxz.html

[T25] Swift：结构体
来源：http://dali.dashuyun.cn/Article/details/gtsxvxdeqg.html

struct P { var x: Int }
来源：http://dali.hnxiangtu.top/Article/details/gtzwghypgn.html

[T26] Swift：类与重写
来源：http://dali.hfpthk.cn/Article/details/gtraopukzd.html

class A: Base { override func f() {} }
来源：http://dali.aizwys.cn/Article/details/gtkriptlwn.html

[T27] Swift：错误处理
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvfzrvlkn.html

do { try f() } catch { print(error) }
来源：http://dali.xziqi.cn/Article/details/gtolxjjimv.html

[T28] Swift：枚举
来源：http://dali.hongshengwenyu.top/Article/details/gtrgxixhao.html

enum Color { case red, green }
来源：http://dali.nanxinkj.top/Article/details/gtdzsshjvy.html

[T29] Swift：guard 提前返回
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkcjjmbsj.html

guard let x = opt else { return }
来源：http://dali.birdmap.top/Article/details/gtjcvlrviv.html

[T30] Swift：协议
来源：http://dali.hongshengwenyu.top/Article/details/gtrbpdfrnt.html

protocol Shape { func area() -> Double }
来源：http://dali.tanke756.top/Article/details/gtiknpblud.html

[T31] Lua：Hello World
来源：http://dali.cdnleiting.top/Article/details/gtcvvkleyu.html

print("Hello")
来源：http://dali.chenlongwang.top/Article/details/gtjwmunbko.html

[T32] Lua：局部变量
来源：http://dali.jqgufenzy.top/Article/details/gtnahxumui.html

local a = 1
来源：http://dali.svipenyu.cn/Article/details/gtszyohqgc.html

[T33] Lua：表（数组）
来源：http://dali.jinghuilouyu.cn/Article/details/gttslgyorl.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.wangdashe.top/Article/details/gtdnbzflyq.html

[T34] Lua：遍历表
来源：http://dali.vqdsnc.cn/Article/details/gtffbccmtp.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.shzxlz.cn/Article/details/gtviilkhpo.html

[T35] Lua：字典表
来源：http://dali.hfpthk.cn/Article/details/gtnyaywdwb.html

local d = { a = 1 };  d.b = 2
来源：http://dali.sufxvd.cn/Article/details/gtghgzfsrk.html

[T36] Lua：函数
来源：http://dali.fengsongda.top/Article/details/gtqkwcyiby.html

function add(a, b) return a + b end
来源：http://dali.cheryme.top/Article/details/gtbvqiukpo.html

[T37] Lua：字符串拼接
来源：http://dali.yonumen.top/Article/details/gtqlqbpygi.html

"a" .. "b"
来源：http://dali.316326.xyz/Article/details/gtizribffq.html

[T38] Lua：条件
来源：http://dali.gaohongyu789.top/Article/details/gtqoribfbh.html

if x > 0 then print("正") end
来源：http://dali.hysaishi.cn/Article/details/gtheumumjf.html

[T39] Lua：模式匹配
来源：http://dali.smart0.xyz/Article/details/gtxocntqbx.html

string.find(s, "%d+")
来源：http://dali.shuidangran.top/Article/details/gtkyouetca.html

[T40] Lua：元表
来源：http://dali.yonumen.top/Article/details/gtgsqcghsu.html

setmetatable({}, { __index = base })
来源：http://dali.zhiwuduotai.top/Article/details/gtpuguuivs.html

[T41] Perl：Hello World
来源：http://dali.zhaomingkeji.xyz/Article/details/gtewcrzvpa.html

print "Hello\n";
来源：http://dali.quarkkingdee.top/Article/details/gtckbwxddv.html

[T42] Perl：变量类型
来源：http://dali.cqqwz.cn/Article/details/gtunrqwejd.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.yangfankeji.com/Article/details/gtwmkyufny.html

[T43] Perl：字符串插值
来源：http://dali.jyoumei.cn/Article/details/gtpqstmhpk.html

"值: $a"
来源：http://dali.xuetiantiany.cn/Article/details/gtdcyefejb.html

[T44] Perl：条件
来源：http://dali.xylfe.cn/Article/details/gtawllhehx.html

if ($a > 0) { print "正"; }
来源：http://dali.hfpthk.cn/Article/details/gtynqoqzid.html

[T45] Perl：数组遍历
来源：http://dali.cucudq.cn/Article/details/gtqrrxpnnl.html

for my $x (@arr) { print $x; }
来源：http://dali.hongshengwenyu.top/Article/details/gtllaawrkf.html

[T46] Perl：哈希操作
来源：http://dali.mhx1999.top/Article/details/gtichgeelf.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.cashguo.top/Article/details/gtkimfsbzf.html

[T47] Perl：正则捕获
来源：http://dali.yueranfly.top/Article/details/gtadtcwzfn.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.jianghu66.top/Article/details/gtewdqyyyu.html

[T48] Perl：正则替换
来源：http://dali.zhiwuduotai.top/Article/details/gttectkfeu.html

$s =~ s/old/new/g;
来源：http://dali.meibo888.top/Article/details/gtqdtqeilz.html

[T49] Perl：函数
来源：http://dali.yvedp.cn/Article/details/gtftejhbkd.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.aizwys.cn/Article/details/gtfjzlmuju.html

[T50] Perl：逐行读文件
来源：http://dali.9152youxi.cn/Article/details/gtzspmwjvw.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.cdnleiting.top/Article/details/gthcbmuvrz.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.tanke756.top/Article/details/gteatvpkva.html

[T51] Scala：Hello World
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkburusny.html

println("Hello")
来源：http://dali.nanxinkj.top/Article/details/gtzdaoipzq.html

[T52] Scala：变量
来源：http://dali.dashuyun.cn/Article/details/gtosnajaic.html

val a = 1;  var b = 2
来源：http://dali.jinghuilouyu.cn/Article/details/gtyneuhcix.html

[T53] Scala：字符串插值
来源：http://dali.cdnleiting.top/Article/details/gtfyrbhehc.html

s"值: $b"
来源：http://dali.shanyushiyangtech.top/Article/details/gtuguolusi.html

[T54] Scala：集合映射
来源：http://dali.jqgufenzy.top/Article/details/gtkxfcqgof.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.nanxinkj.top/Article/details/gtzvlynfax.html

[T55] Scala：集合过滤
来源：http://dali.tian-w.cn/Article/details/gtvugzfhvg.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.hnxiangtu.top/Article/details/gtwvjftrxg.html

[T56] Scala：样例类
来源：http://dali.gogol.net.cn/Article/details/gtswtvdcnr.html

case class User(name: String, age: Int)
来源：http://dali.pycfn.com/Article/details/gtshtmsygp.html

[T57] Scala：模式匹配
来源：http://dali.jlsjyb.cn/Article/details/gtagdspgnm.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.svipenyu.cn/Article/details/gtgrdourst.html

[T58] Scala：函数定义
来源：http://dali.guowangkeji.top/Article/details/gtkgswkxpb.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.snrcjt.cn/Article/details/gtupeeavjx.html

[T59] Scala：循环
来源：http://dali.mhx1999.top/Article/details/gthhfiiwfi.html

for (i <- 1 to 10) println(i)
来源：http://dali.iojbl.cn/Article/details/gtvjooaprj.html

[T60] Scala：折叠
来源：http://dali.gaohongyu789.top/Article/details/gtebcvbozp.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.daxiang520.top/Article/details/gttblcdymt.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtgdjsqxnw.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.xylfe.cn/Article/details/gtrwgbxeez.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gttugphdfv.html

[U01] Py：创建虚拟环境
来源：http://dali.hnxiangtu.top/Article/details/gtjrsfdmqv.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.havefunace.top/Article/details/gtnrqdynpt.html

[U02] Py：导出 / 安装依赖
来源：http://dali.dashuyun.cn/Article/details/gtfcieyhod.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.jinqigufen.top/Article/details/gtffyfydre.html

[U03] Py：加载 .env 配置
来源：http://dali.yj202588.top/Article/details/gtbuutkddi.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.316326.xyz/Article/details/gtoauaeszr.html

[U04] Py：变量调试打印
来源：http://dali.yj202588.top/Article/details/gtiudjhbtt.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.hongshengwenyu.top/Article/details/gtddevfxhn.html

[U05] Py：列表去重且保序
来源：http://dali.daxiang520.top/Article/details/gtzlussjpo.html

list(dict.fromkeys(arr))
来源：http://dali.cdnleiting.top/Article/details/gtsepfctqb.html

[U06] Py：合并两个字典
来源：http://dali.hysaishi.cn/Article/details/gtjjwsikns.html

{**a, **b}
来源：http://dali.ydzc1.top/Article/details/gtoikxjbfh.html

[U07] Py：反转字典键值
来源：http://dali.ehwqpu.com/Article/details/gthenohhln.html

{v: k for k, v in d.items()}
来源：http://dali.vqdsnc.cn/Article/details/gttbqeluzk.html

[U08] Py：展平二维列表
来源：http://dali.xylfe.cn/Article/details/gtcvylbrkm.html

[y for x in nested for y in x]
来源：http://dali.daxiang520.top/Article/details/gtzposfbyr.html

[U09] Py：字典取最大值的键
来源：http://dali.cqqwz.cn/Article/details/gtrlprdyil.html

max(d, key=d.get)
来源：http://dali.jianghu66.top/Article/details/gtlewraqyd.html

[U10] Py：按值排序字典
来源：http://dali.havefunace.top/Article/details/gthsuxrngv.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.gaohongyu789.top/Article/details/gtgfedohad.html

[U11] Py：生成器表达式
来源：http://dali.yj20258.top/Article/details/gtgnozudhq.html

(x * 2 for x in arr)
来源：http://dali.jinghuilouyu.cn/Article/details/gtdtzjjqpq.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.svipenyu.cn/Article/details/gtwgktrnyb.html

Counter(arr).most_common(3)
来源：http://dali.hysaishi.cn/Article/details/gtilrrjeip.html

[U13] Py：固定长度队列
来源：http://dali.cdnleiting.top/Article/details/gtvigeipyz.html

deque(maxlen=10)
来源：http://dali.hysaishi.cn/Article/details/gthkceidir.html

[U14] Py：分组收集到列表
来源：http://dali.tanke756.top/Article/details/gtvlwjkbbg.html

defaultdict(list)
来源：http://dali.snrcjt.cn/Article/details/gtqlalqbho.html

[U15] Py：高精度计时
来源：http://dali.feifeiyinyue.top/Article/details/gtjzgwxdud.html

t = time.perf_counter()
来源：http://dali.zdqjudy.top/Article/details/gtfqfattxk.html

[U16] Py：命令行参数解析
来源：http://dali.cashguo.top/Article/details/gtrjqyfrrt.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.hnxiangtu.top/Article/details/gtpvljkfis.html

[U17] Py：初始化日志
来源：http://dali.zhongyouzk.top/Article/details/gtnrdovsgi.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.daria6918.cn/Article/details/gthmxanfxh.html

[U18] Py：预编译正则
来源：http://dali.redwolf501.top/Article/details/gtefavourd.html

pat = re.compile(r"\d+")
来源：http://dali.daria6918.cn/Article/details/gtnzogxnqt.html

[U19] Py：正则替换带回调
来源：http://dali.shuidangran.top/Article/details/gtbdknbkla.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.hysaishi.cn/Article/details/gthizpakfb.html

[U20] Py：缓存函数结果
来源：http://dali.nanxinkj.top/Article/details/gtwshtvnln.html

@functools.lru_cache(maxsize=None)
来源：http://dali.aibaodan.cn/Article/details/gteanwyrsn.html

[U21] Py：自定义上下文管理器
来源：http://dali.sufxvd.cn/Article/details/gtlkkexqfr.html

@contextlib.contextmanager
来源：http://dali.guannengcc.top/Article/details/gtpbfqtjjx.html

[U22] Py：矩阵转置
来源：http://dali.hnxiangtu.top/Article/details/gtwknzvtyl.html

list(zip(*m))
来源：http://dali.nanxuanxn.top/Article/details/gtwciswxxd.html

[U23] Py：分块读取大文件
来源：http://dali.ybcxt.top/Article/details/gtezxdxdjf.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.ivvv.top/Article/details/gtpzlisqlx.html

[U24] Py：路径操作
来源：http://dali.yj20258.top/Article/details/gthrhbvmba.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.yanxiufei.cn/Article/details/gttgbvvsmm.html

[U25] Py：CSV 按字典读
来源：http://dali.jianghu66.top/Article/details/gtakxtzpky.html

csv.DictReader(f)
来源：http://dali.tian-w.cn/Article/details/gtvwuylwpw.html

[U26] Py：并发下载
来源：http://dali.yuanzhike.top/Article/details/gtsqlxzufp.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.xylfe.cn/Article/details/gtvgvtkkya.html

[U27] Py：异步 HTTP
来源：http://dali.guannengcc.top/Article/details/gtkiyddzpa.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.9152youxi.cn/Article/details/gtekyqekzt.html

[U28] Py：类型别名
来源：http://dali.jinqigfzy.top/Article/details/gtbiyfhajg.html

UserId = int
来源：http://dali.tianlin.xyz/Article/details/gtlvsaklug.html

[U29] Py：属性校验
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtawtugzry.html

@property 与 @x.setter 配合
来源：http://dali.zhoulong.xyz/Article/details/gtmciiiqse.html

[U30] Py：数据类
来源：http://dali.quarkkingdee.top/Article/details/gtehzxdgmj.html

@dataclass(slots=True)
来源：http://dali.feifeiyinyue.top/Article/details/gtwmjwjewn.html


<!-- 参考信息 -->