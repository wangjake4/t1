代发 wailian999

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.c1oappe.top/Article/details/gt2vvpnsupn.html

[S10] C：指针与解引用
来源：http://dali.nanxuanxn.top/Article/details/gt2gugykbqc.html

int *p = &a;  *p = 5;
来源：http://dali.shzxlz.cn/Article/details/gt2hnmoaqjr.html

[S11] C：逐行读文件
来源：http://dali.jinqigfzy.top/Article/details/gt2udwoowny.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.nwbrower.top/Article/details/gt2woxamuwc.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.nwbrower.top/Article/details/gt2doamvzyp.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2xunigipb.html

[S12] C：写文件
来源：http://dali.pycfn.com/Article/details/gt2lempnyvo.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.yonumen.top/Article/details/gt2eodbarey.html

[S13] C：宏定义
来源：http://dali.cheryme.top/Article/details/gt2ggmrnqcq.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.iojbl.cn/Article/details/gt2kphchyou.html

[S14] C：枚举
来源：http://dali.gzhubu.top/Article/details/gt2msmcpgpe.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.jqgufenzy.top/Article/details/gt2hrlzcmkn.html

[S15] C：类型转换
来源：http://dali.nanxinkj.top/Article/details/gt2vhlsjyeh.html

(double) a / b
来源：http://dali.hnxiangtu.top/Article/details/gt2qsddebgh.html

[S16] C：位操作置位
来源：http://dali.wangshuangyany.cn/Article/details/gt2elmjcsgx.html

x |= (1 << 3);
来源：http://dali.cqqwz.cn/Article/details/gt2jckxzyds.html

[S17] C：安全拼接字符串
来源：http://dali.aibaodan.cn/Article/details/gt2ipgnvoup.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.yongpay.top/Article/details/gt2gyodnsry.html

[S18] C：命令行参数
来源：http://dali.tianlin.xyz/Article/details/gt2qwrguqwy.html

int main(int argc, char **argv)
来源：http://dali.pycfn.com/Article/details/gt2dtabxznk.html

[S19] C：快速排序
来源：http://dali.tianlin.xyz/Article/details/gt2tictfvyl.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kjqypmsi.html

[S20] C：二分查找
来源：http://dali.bjfxy.top/Article/details/gt2yxcduyvs.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.mhx1999.top/Article/details/gt2vyiqzzhu.html

[S21] C：字符类别判断
来源：http://dali.jlsjyb.cn/Article/details/gt2bnwkukwl.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.vqdsnc.cn/Article/details/gt2iamvsbgu.html

[S22] C：字符串转数字
来源：http://dali.ybcxt.top/Article/details/gt2vvkijptc.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.hammf.cn/Article/details/gt2jsachkrc.html

[S23] C：随机数
来源：http://dali.havefunace.top/Article/details/gt2wuvidpxq.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.nanxuanxn.top/Article/details/gt2bswjncyd.html

[S24] C：获取本地时间
来源：http://dali.fengsongda.top/Article/details/gt2idogtxmz.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.xziqi.cn/Article/details/gt2fitnthqu.html

[S25] C：内存拷贝
来源：http://dali.jiagoushi.top/Article/details/gt2magugjmm.html

memcpy(dst, src, n);
来源：http://dali.chenlongwang.top/Article/details/gt2izdshwih.html

[S26] C：内存清零
来源：http://dali.gogol.net.cn/Article/details/gt2rweupbsm.html

memset(a, 0, sizeof a);
来源：http://dali.tian-w.cn/Article/details/gt2zgvawamx.html

[S27] C：定义常量
来源：http://dali.yuxming.cn/Article/details/gt2wlnnfdsl.html

const double PI = 3.14159;
来源：http://dali.wangshuangyany.cn/Article/details/gt2arfqzvhe.html

[S28] C：静态变量
来源：http://dali.ppjwa.cn/Article/details/gt2xaicmeee.html

static int counter = 0;
来源：http://dali.yuxming.cn/Article/details/gt2pqxgzppn.html

[S29] C：变参函数
来源：http://dali.xuanzx.com/Article/details/gt2vwjiklpx.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.yj202588.top/Article/details/gt2knytxgbw.html

[S30] C：头文件保护
来源：http://dali.tanke756.top/Article/details/gt2jaccaufe.html

#ifndef X_H
来源：http://dali.sufxvd.cn/Article/details/gt2cwsldcon.html

#define X_H
来源：http://dali.nwbrower.top/Article/details/gt2wxscywpi.html

#endif
来源：http://dali.yangfankeji.com/Article/details/gt2fgglrdwf.html

[S31] C++：Hello World
来源：http://dali.tian-w.cn/Article/details/gt2zddyklqk.html

#include <iostream>
来源：http://dali.316326.xyz/Article/details/gt2abjbidfs.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhongyouzk.top/Article/details/gt2cjamvavt.html

[S32] C++：字符串
来源：http://dali.chenjidiqi.icu/Article/details/gt2xdqalamt.html

std::string s = "hi";  s += "!";
来源：http://dali.nwbrower.top/Article/details/gt2ixontsmx.html

[S33] C++：vector 增删
来源：http://dali.jlsjyb.cn/Article/details/gt2tpqrqlar.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.tianlin.xyz/Article/details/gt2bowrhuvh.html

[S34] C++：遍历 vector
来源：http://dali.zhoulong.xyz/Article/details/gt2guddodqr.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.gaohongyu789.top/Article/details/gt2fwqbemuc.html

[S35] C++：map
来源：http://dali.gzhubu.top/Article/details/gt2kwiwygya.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jianghu66.top/Article/details/gt2wreuyezk.html

[S36] C++：unordered_map
来源：http://dali.tianlin.xyz/Article/details/gt2hrlascjf.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.sxryk.cn/Article/details/gt2civffhkn.html

[S37] C++：set
来源：http://dali.gaohongyu789.top/Article/details/gt2ahtjqifo.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.sxryk.cn/Article/details/gt2pndvmyvq.html

[S38] C++：排序
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bicllumt.html

std::sort(v.begin(), v.end());
来源：http://dali.jlsjyb.cn/Article/details/gt2buixbopx.html

[S39] C++：自定义比较器排序
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nmjdqplo.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.shzxlz.cn/Article/details/gt2xkfybjhh.html

[S40] C++：查找元素
来源：http://dali.andypj.xyz/Article/details/gt2dlyshvpa.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.c1oappe.top/Article/details/gt2tqskipsb.html

[S41] C++：类与构造函数
来源：http://dali.sufxvd.cn/Article/details/gt2qnqdqanw.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhixingplan.top/Article/details/gt2pjofuhan.html

[S42] C++：继承与虚函数
来源：http://dali.hammf.cn/Article/details/gt2otfpgyyp.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhongyouzk.top/Article/details/gt2fcksthdp.html

[S43] C++：智能指针
来源：http://dali.gzhubu.top/Article/details/gt2zrxhdhxx.html

auto p = std::make_unique<int>(5);
来源：http://dali.jianghu66.top/Article/details/gt2puflbjrx.html

[S44] C++：引用传参
来源：http://dali.cdnleiting.top/Article/details/gt2mhowvcbn.html

void inc(int &x) { ++x; }
来源：http://dali.c1oappe.top/Article/details/gt2fiqgkakg.html

[S45] C++：lambda
来源：http://dali.dianchejie.cn/Article/details/gt2glheryjn.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.hnxiangtu.top/Article/details/gt2yzggrorz.html

[S46] C++：函数模板
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nyepevef.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.xinyue.icu/Article/details/gt2nacxvwzu.html

[S47] C++：结构化绑定遍历
来源：http://dali.yuxming.cn/Article/details/gt2jsppkoah.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sldawikd.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2oguofhhj.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.yueranfly.top/Article/details/gt2nxyefdde.html

while (std::getline(in, line)) { }
来源：http://dali.wangshuangyany.cn/Article/details/gt2rtxwpmwe.html

[S49] C++：写文件
来源：http://dali.chenjidiqi.icu/Article/details/gt2egcpeajf.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.nanxinkj.top/Article/details/gt2hwgcybjq.html

[S50] C++：格式化数字
来源：http://dali.yanxiufei.cn/Article/details/gt2bhvipbgi.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.jlsjyb.cn/Article/details/gt2xscqwnud.html

[S51] C++：显式类型转换
来源：http://dali.hongshengwenyu.top/Article/details/gt2fcqmrjjt.html

static_cast<double>(a) / b
来源：http://dali.redwolf501.top/Article/details/gt2qbfeavjs.html

[S52] C++：const 与 noexcept
来源：http://dali.sxryk.cn/Article/details/gt2zwcjopqa.html

int size() const noexcept { return n_; }
来源：http://dali.birdmap.top/Article/details/gt2vlohkfpl.html

[S53] C++：移动语义
来源：http://dali.316326.xyz/Article/details/gt2ehgbygpj.html

std::vector<int> w = std::move(v);
来源：http://dali.hnxiangtu.top/Article/details/gt2suvqgjbp.html

[S54] C++：异常处理
来源：http://dali.sxryk.cn/Article/details/gt2clinqbmo.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.yj20258.top/Article/details/gt2bhxnjjwg.html

[S55] C++：结构化绑定
来源：http://dali.fengsongda.top/Article/details/gt2wjjbimbd.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.cashguo.top/Article/details/gt2ylkxcdsw.html

[S56] C++：optional
来源：http://dali.svipenyu.cn/Article/details/gt2whuomtxd.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.hysaishi.cn/Article/details/gt2higxenkk.html

[S57] C++：编译期常量
来源：http://dali.yj20258888.top/Article/details/gt2wrtrvdtk.html

constexpr int N = 10;
来源：http://dali.aizwys.cn/Article/details/gt2asjckgff.html

[S58] C++：命名空间
来源：http://dali.fengsongda.top/Article/details/gt2kstuusdf.html

namespace ns { int f() { return 1; } }
来源：http://dali.jlsjyb.cn/Article/details/gt2qoklkntk.html

[S59] C++：静态断言
来源：http://dali.jyoumei.cn/Article/details/gt2yumkqfmt.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.cashguo.top/Article/details/gt2hqkeqoiu.html

[S60] C++：遍历并删除元素
来源：http://dali.fengsongda.top/Article/details/gt2eekscyor.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.tanke756.top/Article/details/gt2atdghptv.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2qqwsboni.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.jqgfzy.top/Article/details/gt2wmimobze.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2yrjdtxac.html

[T01] Kotlin：Hello World
来源：http://dali.aibaodan.cn/Article/details/gt2xmpxdxdo.html

println("Hello")
来源：http://dali.xuanzx.com/Article/details/gt2qfeqvvjv.html

[T02] Kotlin：变量
来源：http://dali.shuidangran.top/Article/details/gt2lhjaubzg.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.guowangkeji.top/Article/details/gt2frujqqsf.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2psltjbgn.html

"值: $b"
来源：http://dali.birdmap.top/Article/details/gt2zyhrxmld.html

[T04] Kotlin：空安全
来源：http://dali.cashguo.top/Article/details/gt2hcptudcw.html

val n: String? = null;  n?.length
来源：http://dali.zhoulong.xyz/Article/details/gt2adghynyy.html

[T05] Kotlin：when 表达式
来源：http://dali.xylfe.cn/Article/details/gt2chzosfzi.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.hammf.cn/Article/details/gt2lbrcohsu.html

[T06] Kotlin：集合映射
来源：http://dali.sysykeji.top/Article/details/gt2vvemwovc.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhiwuduotai.top/Article/details/gt2dgoupeec.html

[T07] Kotlin：集合过滤
来源：http://dali.hfpthk.cn/Article/details/gt2uykfukak.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.andypj.xyz/Article/details/gt2omnsumtp.html

[T08] Kotlin：数据类
来源：http://dali.guannengcc.top/Article/details/gt2lllompui.html

data class User(val name: String, val age: Int)
来源：http://dali.jiagoushi.top/Article/details/gt2tgaijcou.html

[T09] Kotlin：扩展函数
来源：http://dali.zhoulong.xyz/Article/details/gt2rutynihp.html

fun String.exclaim() = this + "!"
来源：http://dali.pengpengdd.cyou/Article/details/gt2mhmnwdha.html

[T10] Kotlin：默认参数
来源：http://dali.jyoumei.cn/Article/details/gt2tjldnuia.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.yanxiufei.cn/Article/details/gt2rdsfnwrl.html

[T11] Kotlin：协程
来源：http://dali.pengpengdd.cyou/Article/details/gt2tngvtvqp.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.yanxiufei.cn/Article/details/gt2dpheavir.html

[T12] Kotlin：解构声明
来源：http://dali.guowangkeji.top/Article/details/gt2abczixeb.html

val (a, b) = Pair(1, 2)
来源：http://dali.jyoumei.cn/Article/details/gt2irgejfri.html

[T13] Kotlin：只读 Map
来源：http://dali.vqdsnc.cn/Article/details/gt2qrmlgtnx.html

val m = mapOf("a" to 1)
来源：http://dali.gotoacloud.top/Article/details/gt2pliugqdc.html

[T14] Kotlin：循环
来源：http://dali.chenjidiqi.icu/Article/details/gt2aepouzaz.html

for (i in 1..10) println(i)
来源：http://dali.sxryk.cn/Article/details/gt2jpvmkhsr.html

[T15] Kotlin：接口
来源：http://dali.yanxiufei.cn/Article/details/gt2jxbtfebm.html

interface Shape { fun area(): Double }
来源：http://dali.tian-w.cn/Article/details/gt2glbujflw.html

[T16] Swift：Hello World
来源：http://dali.zhiwuduotai.top/Article/details/gt2vujyvgrf.html

print("Hello")
来源：http://dali.hongshengwenyu.top/Article/details/gt2ynroreqy.html

[T17] Swift：变量与常量
来源：http://dali.sysykeji.top/Article/details/gt2lsleegzh.html

var a = 1;  let b = 2
来源：http://dali.hysaishi.cn/Article/details/gt2hgrrawsz.html

[T18] Swift：字符串插值
来源：http://dali.ehwqpu.com/Article/details/gt2csdoazvl.html

"值: \(b)"
来源：http://dali.daxiang520.top/Article/details/gt2bqckbktt.html

[T19] Swift：可选绑定
来源：http://dali.zhengqikj.top/Article/details/gt2tsknjuil.html

if let n = opt { print(n) }
来源：http://dali.tian-w.cn/Article/details/gt2wxajnvka.html

[T20] Swift：数组操作
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zuqneokl.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.snrcjt.cn/Article/details/gt2jcwysoyw.html

[T21] Swift：遍历
来源：http://dali.jqgufenzy.top/Article/details/gt2bsgrqmcx.html

for x in a { print(x) }
来源：http://dali.nwbrower.top/Article/details/gt2prtsgwah.html

[T22] Swift：字典
来源：http://dali.havefunace.top/Article/details/gt2lyckblaf.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.cashguo.top/Article/details/gt2jdbzoikl.html

[T23] Swift：函数
来源：http://dali.yj202588.top/Article/details/gt2ebspyfoa.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.hnxiangtu.top/Article/details/gt2nhwsewuz.html

[T24] Swift：闭包
来源：http://dali.tianlin.xyz/Article/details/gt2obiglwhd.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.jqgfzy.top/Article/details/gt2suutiltn.html

[T25] Swift：结构体
来源：http://dali.daria6918.cn/Article/details/gt2zbedmqrg.html

struct P { var x: Int }
来源：http://dali.shuidangran.top/Article/details/gt2ikypbdrw.html

[T26] Swift：类与重写
来源：http://dali.andypj.xyz/Article/details/gt2qruyyzwc.html

class A: Base { override func f() {} }
来源：http://dali.shuidangran.top/Article/details/gt2leevtijt.html

[T27] Swift：错误处理
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ytrvgejg.html

do { try f() } catch { print(error) }
来源：http://dali.ivvv.top/Article/details/gt2lndjmvpq.html

[T28] Swift：枚举
来源：http://dali.jyoumei.cn/Article/details/gt2lggewcet.html

enum Color { case red, green }
来源：http://dali.jlsjyb.cn/Article/details/gt2vxacwwrx.html

[T29] Swift：guard 提前返回
来源：http://dali.wangdashe.top/Article/details/gt2xqlrvlbe.html

guard let x = opt else { return }
来源：http://dali.ivvv.top/Article/details/gt2yedamauh.html

[T30] Swift：协议
来源：http://dali.andypj.xyz/Article/details/gt2jmukrwxz.html

protocol Shape { func area() -> Double }
来源：http://dali.zhixingplan.top/Article/details/gt2xupybaha.html

[T31] Lua：Hello World
来源：http://dali.yj202588.top/Article/details/gt2yntgnmty.html

print("Hello")
来源：http://dali.jinqigufen.top/Article/details/gt2sbgtrkfk.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2oduedbzq.html

local a = 1
来源：http://dali.jinqigufen.top/Article/details/gt2rlpxhuox.html

[T33] Lua：表（数组）
来源：http://dali.zdqjudy.top/Article/details/gt2lxskwhla.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.hnxiangtu.top/Article/details/gt2lhkahyrn.html

[T34] Lua：遍历表
来源：http://dali.nanxinkj.top/Article/details/gt2fytnztga.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.yanxiufei.cn/Article/details/gt2etdgafun.html

[T35] Lua：字典表
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2algverbr.html

local d = { a = 1 };  d.b = 2
来源：http://dali.aibaodan.cn/Article/details/gt2ixnyzbvt.html

[T36] Lua：函数
来源：http://dali.smart0.xyz/Article/details/gt2fqueqetx.html

function add(a, b) return a + b end
来源：http://dali.hywenlv.cn/Article/details/gt2jfqbqfbg.html

[T37] Lua：字符串拼接
来源：http://dali.yuanzhike.top/Article/details/gt2fdemfkvw.html

"a" .. "b"
来源：http://dali.zhoulong.xyz/Article/details/gt2fucfarpz.html

[T38] Lua：条件
来源：http://dali.iojbl.cn/Article/details/gt2kzeteuhy.html

if x > 0 then print("正") end
来源：http://dali.cheryme.top/Article/details/gt2vlhkjoxb.html

[T39] Lua：模式匹配
来源：http://dali.hywenlv.cn/Article/details/gt2hjxfgwxa.html

string.find(s, "%d+")
来源：http://dali.0kj1m.cn/Article/details/gt2xwgejpgi.html

[T40] Lua：元表
来源：http://dali.xuetiantiany.cn/Article/details/gt2pajenovf.html

setmetatable({}, { __index = base })
来源：http://dali.chenlongwang.top/Article/details/gt2uugjjitl.html

[T41] Perl：Hello World
来源：http://dali.snrcjt.cn/Article/details/gt2ruvgoyia.html

print "Hello\n";
来源：http://dali.chenjidiqi.icu/Article/details/gt2kiojllhu.html

[T42] Perl：变量类型
来源：http://dali.wangshuangyany.cn/Article/details/gt2omreoame.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.nanxinkj.top/Article/details/gt2lpvaeels.html

[T43] Perl：字符串插值
来源：http://dali.shuidangran.top/Article/details/gt2libcwvvp.html

"值: $a"
来源：http://dali.yonumen.top/Article/details/gt2daugmepv.html

[T44] Perl：条件
来源：http://dali.bjfxy.top/Article/details/gt2nvfghsxj.html

if ($a > 0) { print "正"; }
来源：http://dali.nwbrower.top/Article/details/gt2ihoqgfso.html

[T45] Perl：数组遍历
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jssjrpgo.html

for my $x (@arr) { print $x; }
来源：http://dali.meibo888.top/Article/details/gt2lxtvqfzr.html

[T46] Perl：哈希操作
来源：http://dali.havefunace.top/Article/details/gt2uuncyjio.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.yj20258888.top/Article/details/gt2lexutuyx.html

[T47] Perl：正则捕获
来源：http://dali.jianghu66.top/Article/details/gt2cbbawcpg.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.guowangkeji.top/Article/details/gt2qhwulugp.html

[T48] Perl：正则替换
来源：http://dali.pycfn.com/Article/details/gt2wqwdhqxs.html

$s =~ s/old/new/g;
来源：http://dali.zdqjudy.top/Article/details/gt2jvikfnpe.html

[T49] Perl：函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ykpfctis.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.meibo888.top/Article/details/gt2fvljazti.html

[T50] Perl：逐行读文件
来源：http://dali.iojbl.cn/Article/details/gt2eojnxrqr.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.ppjwa.cn/Article/details/gt2mpollinm.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.hysaishi.cn/Article/details/gt2tnkxhdqr.html

[T51] Scala：Hello World
来源：http://dali.yuxming.cn/Article/details/gt2vzuhjood.html

println("Hello")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tkkxfrnv.html

[T52] Scala：变量
来源：http://dali.redwolf501.top/Article/details/gt2gmsglrch.html

val a = 1;  var b = 2
来源：http://dali.xinyue.icu/Article/details/gt2wqjwxpov.html

[T53] Scala：字符串插值
来源：http://dali.wangshuangyany.cn/Article/details/gt2lthopdfq.html

s"值: $b"
来源：http://dali.andypj.xyz/Article/details/gt2sqsnzmlz.html

[T54] Scala：集合映射
来源：http://dali.tanke756.top/Article/details/gt2tfxuoqdx.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.wangshuangyany.cn/Article/details/gt2cdooyftc.html

[T55] Scala：集合过滤
来源：http://dali.xinyue.icu/Article/details/gt2expjgzdb.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.sweek.top/Article/details/gt2ltkpgdyv.html

[T56] Scala：样例类
来源：http://dali.hongshengwenyu.top/Article/details/gt2yuvuqppv.html

case class User(name: String, age: Int)
来源：http://dali.meibo888.top/Article/details/gt2xkdcisrp.html

[T57] Scala：模式匹配
来源：http://dali.yueranfly.top/Article/details/gt2lrbwfcfb.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhixingplan.top/Article/details/gt2rskzhmcj.html

[T58] Scala：函数定义
来源：http://dali.redwolf501.top/Article/details/gt2gznniuwf.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.shzxlz.cn/Article/details/gt2rpfhdwjc.html

[T59] Scala：循环
来源：http://dali.ivvv.top/Article/details/gt2neutaybr.html

for (i <- 1 to 10) println(i)
来源：http://dali.aizwys.cn/Article/details/gt2kdoutlsw.html

[T60] Scala：折叠
来源：http://dali.hammf.cn/Article/details/gt2dftpjihd.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.cheryme.top/Article/details/gt2szoizzic.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2pyikdkhd.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.cashguo.top/Article/details/gt2fpsuojvg.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gt2drmyblwg.html

[U01] Py：创建虚拟环境
来源：http://dali.yangfankeji.com/Article/details/gt2pdtxrvoi.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.hongshengwenyu.top/Article/details/gt2dajshpkh.html

[U02] Py：导出 / 安装依赖
来源：http://dali.jiagoushi.top/Article/details/gt2vgrudjas.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.jiagoushi.top/Article/details/gt2lfiaalzy.html

[U03] Py：加载 .env 配置
来源：http://dali.xziqi.cn/Article/details/gt2lvhgvlye.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.feifeiyinyue.top/Article/details/gt2ijzpmuyq.html

[U04] Py：变量调试打印
来源：http://dali.snrcjt.cn/Article/details/gt2fizrensw.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.yongpay.top/Article/details/gt2dxcmfdgk.html

[U05] Py：列表去重且保序
来源：http://dali.ybcxt.top/Article/details/gt2eiclfido.html

list(dict.fromkeys(arr))
来源：http://dali.smart0.xyz/Article/details/gt2xxqmrjto.html

[U06] Py：合并两个字典
来源：http://dali.shuidangran.top/Article/details/gt2ypdsyclg.html

{**a, **b}
来源：http://dali.jqgfzy.top/Article/details/gt2epvkxucq.html

[U07] Py：反转字典键值
来源：http://dali.andypj.xyz/Article/details/gt2odwqtnpa.html

{v: k for k, v in d.items()}
来源：http://dali.shuidangran.top/Article/details/gt2kkjddlbm.html

[U08] Py：展平二维列表
来源：http://dali.yvedp.cn/Article/details/gt2ganmtwvk.html

[y for x in nested for y in x]
来源：http://dali.yj20258888.top/Article/details/gt2qyfmhxnv.html

[U09] Py：字典取最大值的键
来源：http://dali.gogol.net.cn/Article/details/gt2obmwmmho.html

max(d, key=d.get)
来源：http://dali.xinyue.icu/Article/details/gt2zcwruwyx.html

[U10] Py：按值排序字典
来源：http://dali.feifeiyinyue.top/Article/details/gt2idnyqiqb.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.dashuyun.cn/Article/details/gt2smhpchiw.html

[U11] Py：生成器表达式
来源：http://dali.shangyingyoupin.top/Article/details/gt2nzbxhlhy.html

(x * 2 for x in arr)
来源：http://dali.9152youxi.cn/Article/details/gt2zocowygy.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.meibo888.top/Article/details/gt2rhrwtnjw.html

Counter(arr).most_common(3)
来源：http://dali.chenzaomai.com/Article/details/gt2hhrojjei.html

[U13] Py：固定长度队列
来源：http://dali.aizwys.cn/Article/details/gt2lfsuoopi.html

deque(maxlen=10)
来源：http://dali.zycfv.cn/Article/details/gt2lrkyranz.html

[U14] Py：分组收集到列表
来源：http://dali.svipenyu.cn/Article/details/gt2nugenkll.html

defaultdict(list)
来源：http://dali.ehwqpu.com/Article/details/gt2yhuegzda.html

[U15] Py：高精度计时
来源：http://dali.hysaishi.cn/Article/details/gt2klnjwkbp.html

t = time.perf_counter()
来源：http://dali.yueranfly.top/Article/details/gt2bkzlqxfg.html

[U16] Py：命令行参数解析
来源：http://dali.andypj.xyz/Article/details/gt2olxfvluy.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.ydzc1.top/Article/details/gt2gngwlaix.html

[U17] Py：初始化日志
来源：http://dali.haohaochexian.top/Article/details/gt2jqzsxfdr.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.hongshengwenyu.top/Article/details/gt2fagljbmn.html

[U18] Py：预编译正则
来源：http://dali.birdmap.top/Article/details/gt2tviyribe.html

pat = re.compile(r"\d+")
来源：http://dali.nanxuanxn.top/Article/details/gt2mdzgipgk.html

[U19] Py：正则替换带回调
来源：http://dali.tanke756.top/Article/details/gt2azbpzmrq.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.yueranfly.top/Article/details/gt2utsqauxe.html

[U20] Py：缓存函数结果
来源：http://dali.chenjidiqi.icu/Article/details/gt2xflhdpnz.html

@functools.lru_cache(maxsize=None)
来源：http://dali.daxiang520.top/Article/details/gt2ysdjnabj.html

[U21] Py：自定义上下文管理器
来源：http://dali.yj20258.top/Article/details/gt2fdsrhfdy.html

@contextlib.contextmanager
来源：http://dali.cdnleiting.top/Article/details/gt2ogdzxpew.html

[U22] Py：矩阵转置
来源：http://dali.bjfxy.top/Article/details/gt2uxdjncpz.html

list(zip(*m))
来源：http://dali.tanke756.top/Article/details/gt2ovvxrvds.html

[U23] Py：分块读取大文件
来源：http://dali.shzxlz.cn/Article/details/gt2sogkcbkf.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.birdmap.top/Article/details/gt2wtzqvtgq.html

[U24] Py：路径操作
来源：http://dali.xuetiantiany.cn/Article/details/gt2zfxdqtbl.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.yuxming.cn/Article/details/gt2oafkeznt.html

[U25] Py：CSV 按字典读
来源：http://dali.zhoulong.xyz/Article/details/gt2tqazevlk.html

csv.DictReader(f)
来源：http://dali.redwolf501.top/Article/details/gt2kcgxjvgy.html

[U26] Py：并发下载
来源：http://dali.jlsjyb.cn/Article/details/gt2wigvnspx.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.xziqi.cn/Article/details/gt2pqevexoy.html

[U27] Py：异步 HTTP
来源：http://dali.shzxlz.cn/Article/details/gt2cpfposou.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.cqqwz.cn/Article/details/gt2vacdvzdy.html

[U28] Py：类型别名
来源：http://dali.yj20258888.top/Article/details/gt2bfxwkagn.html

UserId = int
来源：http://dali.redwolf501.top/Article/details/gt2uwxrcwfj.html

[U29] Py：属性校验
来源：http://dali.andypj.xyz/Article/details/gt2rqumxbxe.html

@property 与 @x.setter 配合
来源：http://dali.guowangkeji.top/Article/details/gt2llhkgdny.html

[U30] Py：数据类
来源：http://dali.cqqwz.cn/Article/details/gt2ywglbert.html

@dataclass(slots=True)
来源：http://dali.jianghu66.top/Article/details/gt2bvokjnxk.html

[U31] Py：单测
来源：http://dali.9152youxi.cn/Article/details/gt2piuaryvf.html

python -m pytest -q
来源：http://dali.yueranfly.top/Article/details/gt2strcpich.html

[U32] Py：代码格式化
来源：http://dali.chenjidiqi.icu/Article/details/gt2bpvzpuhz.html

ruff format . && ruff check --fix .
来源：http://dali.meibo888.top/Article/details/gt2smritqau.html


<!-- 参考信息 -->