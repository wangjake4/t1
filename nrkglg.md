代发 wailian999

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.nwbrower.top/Article/details/gt2rcpdlugj.html

[S13] C：宏定义
来源：http://dali.sweek.top/Article/details/gt2mzlouadk.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ibfbtlpj.html

[S14] C：枚举
来源：http://dali.quarkkingdee.top/Article/details/gt2yoglfuwr.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhiwuduotai.top/Article/details/gt2oerrgrba.html

[S15] C：类型转换
来源：http://dali.mhx1999.top/Article/details/gt2rvqwhlti.html

(double) a / b
来源：http://dali.9152youxi.cn/Article/details/gt2drounrea.html

[S16] C：位操作置位
来源：http://dali.birdmap.top/Article/details/gt2snsemtyf.html

x |= (1 << 3);
来源：http://dali.jlsjyb.cn/Article/details/gt2fdtfksbv.html

[S17] C：安全拼接字符串
来源：http://dali.meibo888.top/Article/details/gt2cfwgdyik.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.aizwys.cn/Article/details/gt2nxnoycpi.html

[S18] C：命令行参数
来源：http://dali.redwolf501.top/Article/details/gt2uorlxgsl.html

int main(int argc, char **argv)
来源：http://dali.hnqzz.top/Article/details/gt2outjvfot.html

[S19] C：快速排序
来源：http://dali.hnxiangtu.top/Article/details/gt2gtvaqyjn.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.birdmap.top/Article/details/gt2ekgrskid.html

[S20] C：二分查找
来源：http://dali.tanke756.top/Article/details/gt2qgppiyaq.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.haohaochexian.top/Article/details/gt2qmzfhbgm.html

[S21] C：字符类别判断
来源：http://dali.ppjwa.cn/Article/details/gt2tomnkkoe.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.aibaodan.cn/Article/details/gt2rvdjzkga.html

[S22] C：字符串转数字
来源：http://dali.xylfe.cn/Article/details/gt2mzyrjfua.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.pycfn.com/Article/details/gt2rpyrmqlh.html

[S23] C：随机数
来源：http://dali.xinyue.icu/Article/details/gt2bjperwxw.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.wangdashe.top/Article/details/gt2inhfaesf.html

[S24] C：获取本地时间
来源：http://dali.fengsongda.top/Article/details/gt2reepdltm.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.yj20258.top/Article/details/gt2rvlubsom.html

[S25] C：内存拷贝
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cvhtxjnf.html

memcpy(dst, src, n);
来源：http://dali.ppjwa.cn/Article/details/gt2jhtunqvg.html

[S26] C：内存清零
来源：http://dali.wangdashe.top/Article/details/gt2onkiqeob.html

memset(a, 0, sizeof a);
来源：http://dali.quarkkingdee.top/Article/details/gt2ogbjredl.html

[S27] C：定义常量
来源：http://dali.ehwqpu.com/Article/details/gt2zwgfchsb.html

const double PI = 3.14159;
来源：http://dali.smart0.xyz/Article/details/gt2ktdyyewb.html

[S28] C：静态变量
来源：http://dali.shangyingyoupin.top/Article/details/gt2orqopzvh.html

static int counter = 0;
来源：http://dali.jlsjyb.cn/Article/details/gt2aydhcbek.html

[S29] C：变参函数
来源：http://dali.wangdashe.top/Article/details/gt2coknfkzf.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.yongpay.top/Article/details/gt2hlntgedx.html

[S30] C：头文件保护
来源：http://dali.yvedp.cn/Article/details/gt2jbdieyzb.html

#ifndef X_H
来源：http://dali.nanxuanxn.top/Article/details/gt2othmryaa.html

#define X_H
来源：http://dali.zhengqikj.top/Article/details/gt2cduxdjtg.html

#endif
来源：http://dali.feifeiyinyue.top/Article/details/gt2vzqhkekn.html

[S31] C++：Hello World
来源：http://dali.316326.xyz/Article/details/gt2xiiglvde.html

#include <iostream>
来源：http://dali.shuidangran.top/Article/details/gt2vpanwaes.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.yonumen.top/Article/details/gt2ahfrnsdm.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2udtmgprf.html

std::string s = "hi";  s += "!";
来源：http://dali.jlsjyb.cn/Article/details/gt2mtickhdz.html

[S33] C++：vector 增删
来源：http://dali.nanxuanxn.top/Article/details/gt2nkaapscv.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.yuxming.cn/Article/details/gt2datfrwyy.html

[S34] C++：遍历 vector
来源：http://dali.hywenlv.cn/Article/details/gt2ainaknqh.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.yvedp.cn/Article/details/gt2gynhsshu.html

[S35] C++：map
来源：http://dali.chenzaomai.com/Article/details/gt2omitmdcu.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jvxmrdpo.html

[S36] C++：unordered_map
来源：http://dali.jinghuilouyu.cn/Article/details/gt2becktzzl.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.sysykeji.top/Article/details/gt2ttorvirf.html

[S37] C++：set
来源：http://dali.haohaochexian.top/Article/details/gt2hmasgoxh.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.yuanzhike.top/Article/details/gt2fddsbdti.html

[S38] C++：排序
来源：http://dali.yonumen.top/Article/details/gt2nrxvrmfa.html

std::sort(v.begin(), v.end());
来源：http://dali.ehwqpu.com/Article/details/gt2vekvkixg.html

[S39] C++：自定义比较器排序
来源：http://dali.jyoumei.cn/Article/details/gt2evspeddz.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.jlsjyb.cn/Article/details/gt2xyezpled.html

[S40] C++：查找元素
来源：http://dali.cdnleiting.top/Article/details/gt2ewawtsfl.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.sxryk.cn/Article/details/gt2lvbvbdxh.html

[S41] C++：类与构造函数
来源：http://dali.zhixingplan.top/Article/details/gt2landwibd.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhongyouzk.top/Article/details/gt2vemlqekt.html

[S42] C++：继承与虚函数
来源：http://dali.aizwys.cn/Article/details/gt2hxyctybf.html

class B : public Base { public: void f() override {} };
来源：http://dali.aizwys.cn/Article/details/gt2pcyepmcs.html

[S43] C++：智能指针
来源：http://dali.quarkkingdee.top/Article/details/gt2axnzztnd.html

auto p = std::make_unique<int>(5);
来源：http://dali.cheryme.top/Article/details/gt2vlobchod.html

[S44] C++：引用传参
来源：http://dali.wangshuangyany.cn/Article/details/gt2zziquqnn.html

void inc(int &x) { ++x; }
来源：http://dali.nanxinkj.top/Article/details/gt2xhhotwiy.html

[S45] C++：lambda
来源：http://dali.ppjwa.cn/Article/details/gt2ucifjulb.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.jlsjyb.cn/Article/details/gt2ziypydji.html

[S46] C++：函数模板
来源：http://dali.kuanghao11.cn/Article/details/gt2muvhsrwj.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhengqikj.top/Article/details/gt2ejhnnuxh.html

[S47] C++：结构化绑定遍历
来源：http://dali.mhx1999.top/Article/details/gt2uhlibqes.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2udviside.html

[S48] C++：逐行读文件
来源：http://dali.dianchejie.cn/Article/details/gt2wwuguhdg.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.yangfankeji.com/Article/details/gt2ziqflorj.html

while (std::getline(in, line)) { }
来源：http://dali.pycfn.com/Article/details/gt2riaafchk.html

[S49] C++：写文件
来源：http://dali.tanke756.top/Article/details/gt2lhglraqc.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.guowangkeji.top/Article/details/gt2mzzpuiqp.html

[S50] C++：格式化数字
来源：http://dali.vqdsnc.cn/Article/details/gt2nxdzesuj.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.gzhubu.top/Article/details/gt2nocssyid.html

[S51] C++：显式类型转换
来源：http://dali.xinyue.icu/Article/details/gt2xawqqqio.html

static_cast<double>(a) / b
来源：http://dali.cashguo.top/Article/details/gt2olmegdan.html

[S52] C++：const 与 noexcept
来源：http://dali.hywenlv.cn/Article/details/gt2venfmjen.html

int size() const noexcept { return n_; }
来源：http://dali.tianlin.xyz/Article/details/gt2dghjsvyo.html

[S53] C++：移动语义
来源：http://dali.bjfxy.top/Article/details/gt2bcixtnzh.html

std::vector<int> w = std::move(v);
来源：http://dali.shuidangran.top/Article/details/gt2ohvqzcce.html

[S54] C++：异常处理
来源：http://dali.aibaodan.cn/Article/details/gt2maschewb.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.xuetiantiany.cn/Article/details/gt2mqxkdbsm.html

[S55] C++：结构化绑定
来源：http://dali.nanxinkj.top/Article/details/gt2emvyqrjk.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.jqgfzy.top/Article/details/gt2sixdpink.html

[S56] C++：optional
来源：http://dali.zycfv.cn/Article/details/gt2pwqcbein.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.jinqigufen.top/Article/details/gt2xzaxrgxj.html

[S57] C++：编译期常量
来源：http://dali.nwbrower.top/Article/details/gt2imeahkoa.html

constexpr int N = 10;
来源：http://dali.bjfxy.top/Article/details/gt2ecwhjyoe.html

[S58] C++：命名空间
来源：http://dali.yongpay.top/Article/details/gt2rbmmxcme.html

namespace ns { int f() { return 1; } }
来源：http://dali.dianchejie.cn/Article/details/gt2inkwnwsx.html

[S59] C++：静态断言
来源：http://dali.redwolf501.top/Article/details/gt2knwfexhz.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.yj20258888.top/Article/details/gt2vlfqqvyh.html

[S60] C++：遍历并删除元素
来源：http://dali.gzhubu.top/Article/details/gt2qcfvyhvf.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.316326.xyz/Article/details/gt2yngbvlpl.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2cdphhmvf.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.xziqi.cn/Article/details/gt2bkhjukqc.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2aavetukr.html

[T01] Kotlin：Hello World
来源：http://dali.jlsjyb.cn/Article/details/gt2mcsohweu.html

println("Hello")
来源：http://dali.cashguo.top/Article/details/gt2dhrvtqka.html

[T02] Kotlin：变量
来源：http://dali.fengsongda.top/Article/details/gt2qaltjlrx.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.aibaodan.cn/Article/details/gt2bqpvfgqg.html

[T03] Kotlin：字符串模板
来源：http://dali.zdqjudy.top/Article/details/gt2newzmbno.html

"值: $b"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lageveij.html

[T04] Kotlin：空安全
来源：http://dali.xziqi.cn/Article/details/gt2dwbpmixk.html

val n: String? = null;  n?.length
来源：http://dali.yuxming.cn/Article/details/gt2jtklfysf.html

[T05] Kotlin：when 表达式
来源：http://dali.jqgufenzy.top/Article/details/gt2vdknupck.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhixingplan.top/Article/details/gt2hksrytpx.html

[T06] Kotlin：集合映射
来源：http://dali.yonumen.top/Article/details/gt2wdukqswz.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.fzhhl.top/Article/details/gt2rilbortl.html

[T07] Kotlin：集合过滤
来源：http://dali.yangfankeji.com/Article/details/gt2ilxgcgxa.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.iojbl.cn/Article/details/gt2ugbyrctp.html

[T08] Kotlin：数据类
来源：http://dali.ehwqpu.com/Article/details/gt2usuhurqz.html

data class User(val name: String, val age: Int)
来源：http://dali.guowangkeji.top/Article/details/gt2nluefzvn.html

[T09] Kotlin：扩展函数
来源：http://dali.0kj1m.cn/Article/details/gt2fmipxfbj.html

fun String.exclaim() = this + "!"
来源：http://dali.zhixingplan.top/Article/details/gt2iqzdaity.html

[T10] Kotlin：默认参数
来源：http://dali.iojbl.cn/Article/details/gt2zaaqxikj.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gzwappim.html

[T11] Kotlin：协程
来源：http://dali.dianchejie.cn/Article/details/gt2xubbdrgo.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.yvedp.cn/Article/details/gt2zqnkalda.html

[T12] Kotlin：解构声明
来源：http://dali.jyoumei.cn/Article/details/gt2abgxfulv.html

val (a, b) = Pair(1, 2)
来源：http://dali.hongshengwenyu.top/Article/details/gt2snitimsg.html

[T13] Kotlin：只读 Map
来源：http://dali.xylfe.cn/Article/details/gt2gqtedzqu.html

val m = mapOf("a" to 1)
来源：http://dali.fzhhl.top/Article/details/gt2xtmfwyuk.html

[T14] Kotlin：循环
来源：http://dali.fengsongda.top/Article/details/gt2yrxhrjfo.html

for (i in 1..10) println(i)
来源：http://dali.cashguo.top/Article/details/gt2wxzgyknn.html

[T15] Kotlin：接口
来源：http://dali.nanxuanxn.top/Article/details/gt2oycnveeh.html

interface Shape { fun area(): Double }
来源：http://dali.hongshengwenyu.top/Article/details/gt2tjiovify.html

[T16] Swift：Hello World
来源：http://dali.hnxiangtu.top/Article/details/gt2qpvsaive.html

print("Hello")
来源：http://dali.chenlongwang.top/Article/details/gt2fvrbuojo.html

[T17] Swift：变量与常量
来源：http://dali.shuidangran.top/Article/details/gt2qdibitbi.html

var a = 1;  let b = 2
来源：http://dali.chenlongwang.top/Article/details/gt2qqigxztn.html

[T18] Swift：字符串插值
来源：http://dali.gotoacloud.top/Article/details/gt2vravrzlk.html

"值: \(b)"
来源：http://dali.ydzc1.top/Article/details/gt2voqlnxyt.html

[T19] Swift：可选绑定
来源：http://dali.gaohongyu789.top/Article/details/gt2dngwkeku.html

if let n = opt { print(n) }
来源：http://dali.chenjidiqi.icu/Article/details/gt2yaynymah.html

[T20] Swift：数组操作
来源：http://dali.cdnleiting.top/Article/details/gt2twyqxron.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.xinyue.icu/Article/details/gt2xjsxbduk.html

[T21] Swift：遍历
来源：http://dali.yj20258.top/Article/details/gt2uurxeuaz.html

for x in a { print(x) }
来源：http://dali.jinqigfzy.top/Article/details/gt2wiwuvoug.html

[T22] Swift：字典
来源：http://dali.yj202588.top/Article/details/gt2raydoodp.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.9152youxi.cn/Article/details/gt2oslkejsz.html

[T23] Swift：函数
来源：http://dali.nanxuanxn.top/Article/details/gt2ccchjkbt.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.jianghu66.top/Article/details/gt2mkoldejh.html

[T24] Swift：闭包
来源：http://dali.cqqwz.cn/Article/details/gt2bollfyki.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.xuanzx.com/Article/details/gt2sezdehgn.html

[T25] Swift：结构体
来源：http://dali.yj20258.top/Article/details/gt2ftqbflcj.html

struct P { var x: Int }
来源：http://dali.yj202588.top/Article/details/gt2hqfmonrc.html

[T26] Swift：类与重写
来源：http://dali.c1oappe.top/Article/details/gt2hewamxfx.html

class A: Base { override func f() {} }
来源：http://dali.hongshengwenyu.top/Article/details/gt2byvwwjys.html

[T27] Swift：错误处理
来源：http://dali.haohaochexian.top/Article/details/gt2jfqkawua.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ebvfgqoq.html

[T28] Swift：枚举
来源：http://dali.tanke756.top/Article/details/gt2hxnxdzdo.html

enum Color { case red, green }
来源：http://dali.nanxuanxn.top/Article/details/gt2ozuinwof.html

[T29] Swift：guard 提前返回
来源：http://dali.zhiwuduotai.top/Article/details/gt2ypyshrut.html

guard let x = opt else { return }
来源：http://dali.jqgfzy.top/Article/details/gt2bmsvybvk.html

[T30] Swift：协议
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mabymail.html

protocol Shape { func area() -> Double }
来源：http://dali.birdmap.top/Article/details/gt2jjsbnasj.html

[T31] Lua：Hello World
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lxufdbnj.html

print("Hello")
来源：http://dali.yongpay.top/Article/details/gt2epafenom.html

[T32] Lua：局部变量
来源：http://dali.daria6918.cn/Article/details/gt2ishgavqx.html

local a = 1
来源：http://dali.andypj.xyz/Article/details/gt2varetjnt.html

[T33] Lua：表（数组）
来源：http://dali.quarkkingdee.top/Article/details/gt2iskgdoct.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.haohaochexian.top/Article/details/gt2jyurwpcz.html

[T34] Lua：遍历表
来源：http://dali.gotoacloud.top/Article/details/gt2xzgqupwq.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.hnqzz.top/Article/details/gt2flygxhgz.html

[T35] Lua：字典表
来源：http://dali.snrcjt.cn/Article/details/gt2ulsuxogr.html

local d = { a = 1 };  d.b = 2
来源：http://dali.smart0.xyz/Article/details/gt2jxdsrnzs.html

[T36] Lua：函数
来源：http://dali.hammf.cn/Article/details/gt2ubepusgk.html

function add(a, b) return a + b end
来源：http://dali.ydzc1.top/Article/details/gt2wbetbjyo.html

[T37] Lua：字符串拼接
来源：http://dali.smart0.xyz/Article/details/gt2pzfrekrk.html

"a" .. "b"
来源：http://dali.xziqi.cn/Article/details/gt2sjvxbkbj.html

[T38] Lua：条件
来源：http://dali.smart0.xyz/Article/details/gt2oakoffcl.html

if x > 0 then print("正") end
来源：http://dali.cucudq.cn/Article/details/gt2bggbwtqf.html

[T39] Lua：模式匹配
来源：http://dali.yanxiufei.cn/Article/details/gt2tjslrogw.html

string.find(s, "%d+")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yimhtzvw.html

[T40] Lua：元表
来源：http://dali.yanxiufei.cn/Article/details/gt2qjqcyvxx.html

setmetatable({}, { __index = base })
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hmsiedbt.html

[T41] Perl：Hello World
来源：http://dali.smart0.xyz/Article/details/gt2hugqpzss.html

print "Hello\n";
来源：http://dali.316326.xyz/Article/details/gt2xxsjpplf.html

[T42] Perl：变量类型
来源：http://dali.hfpthk.cn/Article/details/gt2rluygwdk.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.andypj.xyz/Article/details/gt2iclsluep.html

[T43] Perl：字符串插值
来源：http://dali.zhiwuduotai.top/Article/details/gt2kraocxtc.html

"值: $a"
来源：http://dali.yueranfly.top/Article/details/gt2jukbiwpr.html

[T44] Perl：条件
来源：http://dali.yanxiufei.cn/Article/details/gt2nrcpyfpa.html

if ($a > 0) { print "正"; }
来源：http://dali.ehwqpu.com/Article/details/gt2nqfmutlg.html

[T45] Perl：数组遍历
来源：http://dali.zhiwuduotai.top/Article/details/gt2hvlqtaoh.html

for my $x (@arr) { print $x; }
来源：http://dali.birdmap.top/Article/details/gt2aianguoa.html

[T46] Perl：哈希操作
来源：http://dali.daxiang520.top/Article/details/gt2dgsjeaae.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.havefunace.top/Article/details/gt2qeptoqkk.html

[T47] Perl：正则捕获
来源：http://dali.mhx1999.top/Article/details/gt2rjrchzkm.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.xylfe.cn/Article/details/gt2tfrdhahx.html

[T48] Perl：正则替换
来源：http://dali.nanxuanxn.top/Article/details/gt2fbmhhmqk.html

$s =~ s/old/new/g;
来源：http://dali.cheryme.top/Article/details/gt2uesttbtm.html

[T49] Perl：函数
来源：http://dali.vqdsnc.cn/Article/details/gt2puucbsci.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2qxuslpwd.html

[T50] Perl：逐行读文件
来源：http://dali.zhiwuduotai.top/Article/details/gt2zsucwzdp.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.wangdashe.top/Article/details/gt2sppmaewm.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.aizwys.cn/Article/details/gt2aollakcj.html

[T51] Scala：Hello World
来源：http://dali.cheryme.top/Article/details/gt2boijdkbj.html

println("Hello")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2upbwnkzf.html

[T52] Scala：变量
来源：http://dali.yueranfly.top/Article/details/gt2xworgmjn.html

val a = 1;  var b = 2
来源：http://dali.yj202588.top/Article/details/gt2iqiizgqb.html

[T53] Scala：字符串插值
来源：http://dali.yj20258888.top/Article/details/gt2mzqcvsri.html

s"值: $b"
来源：http://dali.ybcxt.top/Article/details/gt2rrdtjbyu.html

[T54] Scala：集合映射
来源：http://dali.cashguo.top/Article/details/gt2qyakwozr.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.hnqzz.top/Article/details/gt2xpudjxam.html

[T55] Scala：集合过滤
来源：http://dali.zhiwuduotai.top/Article/details/gt2pwbfrwln.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.smart0.xyz/Article/details/gt2vctbbsxq.html

[T56] Scala：样例类
来源：http://dali.yongpay.top/Article/details/gt2ebprwciv.html

case class User(name: String, age: Int)
来源：http://dali.fzhhl.top/Article/details/gt2nwtuodje.html

[T57] Scala：模式匹配
来源：http://dali.gotoacloud.top/Article/details/gt2xgfnukbb.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.hammf.cn/Article/details/gt2pcuoacln.html

[T58] Scala：函数定义
来源：http://dali.yuxming.cn/Article/details/gt2xdhopnpl.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.hammf.cn/Article/details/gt2btinjmtw.html

[T59] Scala：循环
来源：http://dali.hnxiangtu.top/Article/details/gt2wrbvjkwu.html

for (i <- 1 to 10) println(i)
来源：http://dali.shangyingyoupin.top/Article/details/gt2ywlhiola.html

[T60] Scala：折叠
来源：http://dali.jianghu66.top/Article/details/gt2aiegasiv.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.chenlongwang.top/Article/details/gt2ogjhefdn.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2hqpfrowx.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.snrcjt.cn/Article/details/gt2bxvxzggh.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2zgknoves.html

[U01] Py：创建虚拟环境
来源：http://dali.xuanzx.com/Article/details/gt2zssmntjf.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhixingplan.top/Article/details/gt2ntdlspnp.html

[U02] Py：导出 / 安装依赖
来源：http://dali.fzhhl.top/Article/details/gt2bpkiikkd.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.gzhubu.top/Article/details/gt2zdojdnhw.html

[U03] Py：加载 .env 配置
来源：http://dali.jianghu66.top/Article/details/gt2wegbopmm.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.yuxming.cn/Article/details/gt2kmhkcswy.html

[U04] Py：变量调试打印
来源：http://dali.yonumen.top/Article/details/gt2tdsbglha.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.yj202588.top/Article/details/gt2tdqkiagk.html

[U05] Py：列表去重且保序
来源：http://dali.jianghu66.top/Article/details/gt2hwkqeptf.html

list(dict.fromkeys(arr))
来源：http://dali.haohaochexian.top/Article/details/gt2rzifaesw.html

[U06] Py：合并两个字典
来源：http://dali.quarkkingdee.top/Article/details/gt2woohkcjm.html

{**a, **b}
来源：http://dali.yonumen.top/Article/details/gt2lhzrcrtp.html

[U07] Py：反转字典键值
来源：http://dali.yuxming.cn/Article/details/gt2jemqmklx.html

{v: k for k, v in d.items()}
来源：http://dali.vqdsnc.cn/Article/details/gt2ezqurrsc.html

[U08] Py：展平二维列表
来源：http://dali.jinqigfzy.top/Article/details/gt2fdjlpeww.html

[y for x in nested for y in x]
来源：http://dali.jinqigufen.top/Article/details/gt2vunoqqzz.html

[U09] Py：字典取最大值的键
来源：http://dali.cheryme.top/Article/details/gt2jjkweruh.html

max(d, key=d.get)
来源：http://dali.havefunace.top/Article/details/gt2rvpezpab.html

[U10] Py：按值排序字典
来源：http://dali.hywenlv.cn/Article/details/gt2ecmuimxf.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.chenlongwang.top/Article/details/gt2gbsxmoqs.html

[U11] Py：生成器表达式
来源：http://dali.birdmap.top/Article/details/gt2oasjsycy.html

(x * 2 for x in arr)
来源：http://dali.zycfv.cn/Article/details/gt2elikmmnd.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhoulong.xyz/Article/details/gt2akveeixt.html

Counter(arr).most_common(3)
来源：http://dali.shuidangran.top/Article/details/gt2iydmwpga.html

[U13] Py：固定长度队列
来源：http://dali.vqdsnc.cn/Article/details/gt2zlhmsnyb.html

deque(maxlen=10)
来源：http://dali.xuetiantiany.cn/Article/details/gt2rvqibdcj.html

[U14] Py：分组收集到列表
来源：http://dali.yj20258.top/Article/details/gt2qwlbowah.html

defaultdict(list)
来源：http://dali.dianchejie.cn/Article/details/gt2vczibfnq.html

[U15] Py：高精度计时
来源：http://dali.nwbrower.top/Article/details/gt2bfcgplwt.html

t = time.perf_counter()
来源：http://dali.ehwqpu.com/Article/details/gt2zeralwjq.html

[U16] Py：命令行参数解析
来源：http://dali.hnqzz.top/Article/details/gt2abgwrxph.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.dianchejie.cn/Article/details/gt2pxoczlcy.html

[U17] Py：初始化日志
来源：http://dali.wangdashe.top/Article/details/gt2mqpfinkf.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.feifeiyinyue.top/Article/details/gt2hoywylwu.html

[U18] Py：预编译正则
来源：http://dali.fzhhl.top/Article/details/gt2upiodotc.html

pat = re.compile(r"\d+")
来源：http://dali.tian-w.cn/Article/details/gt2gbjbbrru.html

[U19] Py：正则替换带回调
来源：http://dali.zhengqikj.top/Article/details/gt2rfhtagpt.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.gaohongyu789.top/Article/details/gt2wgskdrib.html

[U20] Py：缓存函数结果
来源：http://dali.sweek.top/Article/details/gt2zsehnoqz.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhongyouzk.top/Article/details/gt2milnshti.html

[U21] Py：自定义上下文管理器
来源：http://dali.pengpengdd.cyou/Article/details/gt2imzghazh.html

@contextlib.contextmanager
来源：http://dali.gaohongyu789.top/Article/details/gt2fgarpqge.html

[U22] Py：矩阵转置
来源：http://dali.smart0.xyz/Article/details/gt2zyggvmag.html

list(zip(*m))
来源：http://dali.sufxvd.cn/Article/details/gt2nrfhavcp.html

[U23] Py：分块读取大文件
来源：http://dali.zhiwuduotai.top/Article/details/gt2ziugodqi.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.feifeiyinyue.top/Article/details/gt2hacbdgie.html

[U24] Py：路径操作
来源：http://dali.yanxiufei.cn/Article/details/gt2njjdawic.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.cucudq.cn/Article/details/gt2huctebav.html

[U25] Py：CSV 按字典读
来源：http://dali.dashuyun.cn/Article/details/gt2rsofrpxg.html

csv.DictReader(f)
来源：http://dali.guannengcc.top/Article/details/gt2pcjjgbtt.html

[U26] Py：并发下载
来源：http://dali.mhx1999.top/Article/details/gt2gkjdpirz.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.sufxvd.cn/Article/details/gt2viubvmuh.html

[U27] Py：异步 HTTP
来源：http://dali.yj20258888.top/Article/details/gt2lkxjejat.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.yuxming.cn/Article/details/gt2fbybhetm.html

[U28] Py：类型别名
来源：http://dali.redwolf501.top/Article/details/gt2zfobyyxm.html

UserId = int
来源：http://dali.ydzc1.top/Article/details/gt2fgrcgnnx.html

[U29] Py：属性校验
来源：http://dali.jqgufenzy.top/Article/details/gt2cnywrino.html

@property 与 @x.setter 配合
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yidskrch.html

[U30] Py：数据类
来源：http://dali.gaohongyu789.top/Article/details/gt2twwzridr.html

@dataclass(slots=True)
来源：http://dali.jqgfzy.top/Article/details/gt2atimtgul.html

[U31] Py：单测
来源：http://dali.yvedp.cn/Article/details/gt2gfroetha.html

python -m pytest -q
来源：http://dali.hammf.cn/Article/details/gt2rfpucctg.html

[U32] Py：代码格式化
来源：http://dali.c1oappe.top/Article/details/gt2ndlzskvn.html

ruff format . && ruff check --fix .
来源：http://dali.sxryk.cn/Article/details/gt2lcnnzgbd.html

[U33] Py：打包发布
来源：http://dali.gotoacloud.top/Article/details/gt2xgrfvmdk.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wxkwixsz.html

[U34] Py：判断编码
来源：http://dali.yj202588.top/Article/details/gt2fkrdircw.html

chardet.detect(raw)
来源：http://dali.yj202588.top/Article/details/gt2rkdaqiei.html

[U35] Py：发送邮件
来源：http://dali.nwbrower.top/Article/details/gt2dxokhlzw.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.yangfankeji.com/Article/details/gt2lupwohes.html

[U36] Py：定时任务
来源：http://dali.nanxuanxn.top/Article/details/gt2rbxnvwvw.html

schedule.every(10).minutes.do(job)
来源：http://dali.jlsjyb.cn/Article/details/gt2fpknmciw.html


<!-- 参考信息 -->