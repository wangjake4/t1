代发 wailian999

FILE *f = fopen("a.txt", "r");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bvirzzuq.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rsuscggi.html

fclose(f);
来源：http://dali.sxryk.cn/Article/details/gt2pmskmfrt.html

[S12] C：写文件
来源：http://dali.ivvv.top/Article/details/gt2bezbuuze.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.chenlongwang.top/Article/details/gt2tllkfalx.html

[S13] C：宏定义
来源：http://dali.birdmap.top/Article/details/gt2lmmwsaop.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhiwuduotai.top/Article/details/gt2brwrcbxr.html

[S14] C：枚举
来源：http://dali.haohaochexian.top/Article/details/gt2kvcrldqp.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.tianlin.xyz/Article/details/gt2nvcnmuwu.html

[S15] C：类型转换
来源：http://dali.nanxinkj.top/Article/details/gt2qkilyhsk.html

(double) a / b
来源：http://dali.yvedp.cn/Article/details/gt2jbuyvssf.html

[S16] C：位操作置位
来源：http://dali.iojbl.cn/Article/details/gt2esdesgot.html

x |= (1 << 3);
来源：http://dali.316326.xyz/Article/details/gt2lgmsqjqt.html

[S17] C：安全拼接字符串
来源：http://dali.zhoulong.xyz/Article/details/gt2zomfvcct.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.aizwys.cn/Article/details/gt2lnldunui.html

[S18] C：命令行参数
来源：http://dali.gzhubu.top/Article/details/gt2uurkhawn.html

int main(int argc, char **argv)
来源：http://dali.birdmap.top/Article/details/gt2ryrcrscf.html

[S19] C：快速排序
来源：http://dali.guowangkeji.top/Article/details/gt2fhcizkwu.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.yanxiufei.cn/Article/details/gt2nmhcgebe.html

[S20] C：二分查找
来源：http://dali.yueranfly.top/Article/details/gt2qvskbirs.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.yuxming.cn/Article/details/gt2vtulijxk.html

[S21] C：字符类别判断
来源：http://dali.gogol.net.cn/Article/details/gt2gvjdyglw.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.snrcjt.cn/Article/details/gt2ogxqfcws.html

[S22] C：字符串转数字
来源：http://dali.gaohongyu789.top/Article/details/gt2eposifwx.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.andypj.xyz/Article/details/gt2kcyphvop.html

[S23] C：随机数
来源：http://dali.yuanzhike.top/Article/details/gt2zmsywbau.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhongyouzk.top/Article/details/gt2xtcitaru.html

[S24] C：获取本地时间
来源：http://dali.meibo888.top/Article/details/gt2utfdxmyn.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.pycfn.com/Article/details/gt2gqzpacwb.html

[S25] C：内存拷贝
来源：http://dali.yj20258.top/Article/details/gt2nesxalbo.html

memcpy(dst, src, n);
来源：http://dali.mhx1999.top/Article/details/gt2ektbnhsx.html

[S26] C：内存清零
来源：http://dali.guannengcc.top/Article/details/gt2mlsumzln.html

memset(a, 0, sizeof a);
来源：http://dali.aibaodan.cn/Article/details/gt2kvoyozqb.html

[S27] C：定义常量
来源：http://dali.yuxming.cn/Article/details/gt2jcrnqxww.html

const double PI = 3.14159;
来源：http://dali.nanxinkj.top/Article/details/gt2uirgthls.html

[S28] C：静态变量
来源：http://dali.wangshuangyany.cn/Article/details/gt2kjkggugw.html

static int counter = 0;
来源：http://dali.nanxinkj.top/Article/details/gt2ydpptsay.html

[S29] C：变参函数
来源：http://dali.guowangkeji.top/Article/details/gt2zvqdeple.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.svipenyu.cn/Article/details/gt2ohjxezal.html

[S30] C：头文件保护
来源：http://dali.dashuyun.cn/Article/details/gt2tsyoygfd.html

#ifndef X_H
来源：http://dali.yanxiufei.cn/Article/details/gt2tphvlphk.html

#define X_H
来源：http://dali.hongshengwenyu.top/Article/details/gt2nkkromcp.html

#endif
来源：http://dali.hywenlv.cn/Article/details/gt2jgfotwvo.html

[S31] C++：Hello World
来源：http://dali.ydzc1.top/Article/details/gt2edlwptrv.html

#include <iostream>
来源：http://dali.svipenyu.cn/Article/details/gt2wivvxrgz.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.shuidangran.top/Article/details/gt2jiedsuhk.html

[S32] C++：字符串
来源：http://dali.tanke756.top/Article/details/gt2pqxydgxe.html

std::string s = "hi";  s += "!";
来源：http://dali.cashguo.top/Article/details/gt2lsutorcu.html

[S33] C++：vector 增删
来源：http://dali.dianchejie.cn/Article/details/gt2vbhijjir.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.xylfe.cn/Article/details/gt2qdtbgeof.html

[S34] C++：遍历 vector
来源：http://dali.c1oappe.top/Article/details/gt2lsnlcvoj.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hafktdnd.html

[S35] C++：map
来源：http://dali.jinqigufen.top/Article/details/gt2nebolwmz.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.andypj.xyz/Article/details/gt2naazjpqu.html

[S36] C++：unordered_map
来源：http://dali.nwbrower.top/Article/details/gt2dfktizck.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.smart0.xyz/Article/details/gt2adomhxey.html

[S37] C++：set
来源：http://dali.ybcxt.top/Article/details/gt2sflshdho.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.yuxming.cn/Article/details/gt2azfpayts.html

[S38] C++：排序
来源：http://dali.gzhubu.top/Article/details/gt2cvpelhuq.html

std::sort(v.begin(), v.end());
来源：http://dali.gaohongyu789.top/Article/details/gt2rddcqkzg.html

[S39] C++：自定义比较器排序
来源：http://dali.gzhubu.top/Article/details/gt2aixohyrc.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.snrcjt.cn/Article/details/gt2sacpgdrn.html

[S40] C++：查找元素
来源：http://dali.zhengqikj.top/Article/details/gt2ozkqetky.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.jqgufenzy.top/Article/details/gt2khnbugqo.html

[S41] C++：类与构造函数
来源：http://dali.fzhhl.top/Article/details/gt2citohuhf.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhoulong.xyz/Article/details/gt2gcuhtuka.html

[S42] C++：继承与虚函数
来源：http://dali.cqqwz.cn/Article/details/gt2lcyxmocs.html

class B : public Base { public: void f() override {} };
来源：http://dali.c1oappe.top/Article/details/gt2akiftvbr.html

[S43] C++：智能指针
来源：http://dali.kuanghao11.cn/Article/details/gt2aiclcadz.html

auto p = std::make_unique<int>(5);
来源：http://dali.yueranfly.top/Article/details/gt2ggjkozhu.html

[S44] C++：引用传参
来源：http://dali.yj20258.top/Article/details/gt2mqozgxus.html

void inc(int &x) { ++x; }
来源：http://dali.cashguo.top/Article/details/gt2lfwhxnmt.html

[S45] C++：lambda
来源：http://dali.dashuyun.cn/Article/details/gt2rvkyjwvf.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.yj20258888.top/Article/details/gt2xflxiiux.html

[S46] C++：函数模板
来源：http://dali.sweek.top/Article/details/gt2wqpwxlvk.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.jqgufenzy.top/Article/details/gt2iuesnaau.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2pnpkizgw.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.guannengcc.top/Article/details/gt2scnqvcql.html

[S48] C++：逐行读文件
来源：http://dali.chenjidiqi.icu/Article/details/gt2cybwhlju.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.yonumen.top/Article/details/gt2sttaqgbq.html

while (std::getline(in, line)) { }
来源：http://dali.shuidangran.top/Article/details/gt2sgxblevj.html

[S49] C++：写文件
来源：http://dali.zhengqikj.top/Article/details/gt2evrjrnrj.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zdqjudy.top/Article/details/gt2giftehwn.html

[S50] C++：格式化数字
来源：http://dali.hysaishi.cn/Article/details/gt2umqzuziy.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.gaohongyu789.top/Article/details/gt2dzhmzaym.html

[S51] C++：显式类型转换
来源：http://dali.yj20258888.top/Article/details/gt2fpyadfux.html

static_cast<double>(a) / b
来源：http://dali.guannengcc.top/Article/details/gt2ramdlmna.html

[S52] C++：const 与 noexcept
来源：http://dali.hammf.cn/Article/details/gt2trnaachw.html

int size() const noexcept { return n_; }
来源：http://dali.jinqigfzy.top/Article/details/gt2huvcexak.html

[S53] C++：移动语义
来源：http://dali.gaohongyu789.top/Article/details/gt2awtycuph.html

std::vector<int> w = std::move(v);
来源：http://dali.nanxuanxn.top/Article/details/gt2vocbirsb.html

[S54] C++：异常处理
来源：http://dali.yongpay.top/Article/details/gt2vcjrasao.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.316326.xyz/Article/details/gt2gdiltwvw.html

[S55] C++：结构化绑定
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ieyqixcu.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.xuanzx.com/Article/details/gt2giyznysd.html

[S56] C++：optional
来源：http://dali.jyoumei.cn/Article/details/gt2yoblygdp.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.kuanghao11.cn/Article/details/gt2svfxccik.html

[S57] C++：编译期常量
来源：http://dali.jqgufenzy.top/Article/details/gt2snsbgeyh.html

constexpr int N = 10;
来源：http://dali.hywenlv.cn/Article/details/gt2axqywixp.html

[S58] C++：命名空间
来源：http://dali.shangyingyoupin.top/Article/details/gt2qfzbrpcc.html

namespace ns { int f() { return 1; } }
来源：http://dali.xuanzx.com/Article/details/gt2rxvjrunl.html

[S59] C++：静态断言
来源：http://dali.meibo888.top/Article/details/gt2htgsuhzo.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.ydzc1.top/Article/details/gt2llnzxdnb.html

[S60] C++：遍历并删除元素
来源：http://dali.nanxuanxn.top/Article/details/gt2rowqybpb.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.tanke756.top/Article/details/gt2ngttshmi.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2qppytadn.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.birdmap.top/Article/details/gt2onwsowko.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2svfexwvl.html

[T01] Kotlin：Hello World
来源：http://dali.c1oappe.top/Article/details/gt2vvxlbzep.html

println("Hello")
来源：http://dali.gogol.net.cn/Article/details/gt2wzdaohln.html

[T02] Kotlin：变量
来源：http://dali.yuxming.cn/Article/details/gt2ajjqhxds.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.yueranfly.top/Article/details/gt2zkhtmgjz.html

[T03] Kotlin：字符串模板
来源：http://dali.yanxiufei.cn/Article/details/gt2bmenvlxt.html

"值: $b"
来源：http://dali.zycfv.cn/Article/details/gt2mmovbylz.html

[T04] Kotlin：空安全
来源：http://dali.andypj.xyz/Article/details/gt2bzoaghqe.html

val n: String? = null;  n?.length
来源：http://dali.xziqi.cn/Article/details/gt2itdzfidf.html

[T05] Kotlin：when 表达式
来源：http://dali.jiagoushi.top/Article/details/gt2ncruzkav.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.aibaodan.cn/Article/details/gt2tlzotami.html

[T06] Kotlin：集合映射
来源：http://dali.zhixingplan.top/Article/details/gt2sweecgrq.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.9152youxi.cn/Article/details/gt2fxzrxtzf.html

[T07] Kotlin：集合过滤
来源：http://dali.yj202588.top/Article/details/gt2lvfccswi.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.guowangkeji.top/Article/details/gt2hzfpouwk.html

[T08] Kotlin：数据类
来源：http://dali.0kj1m.cn/Article/details/gt2hcvxpize.html

data class User(val name: String, val age: Int)
来源：http://dali.hywenlv.cn/Article/details/gt2sovmphjh.html

[T09] Kotlin：扩展函数
来源：http://dali.quarkkingdee.top/Article/details/gt2tbfrkfcu.html

fun String.exclaim() = this + "!"
来源：http://dali.c1oappe.top/Article/details/gt2tavshyiu.html

[T10] Kotlin：默认参数
来源：http://dali.jlsjyb.cn/Article/details/gt2jnscnibi.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.jiagoushi.top/Article/details/gt2kwfkyopg.html

[T11] Kotlin：协程
来源：http://dali.wangdashe.top/Article/details/gt2dlapwzrs.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.dianchejie.cn/Article/details/gt2fgobbkqt.html

[T12] Kotlin：解构声明
来源：http://dali.daria6918.cn/Article/details/gt2snlxeinq.html

val (a, b) = Pair(1, 2)
来源：http://dali.cucudq.cn/Article/details/gt2vcfebqwc.html

[T13] Kotlin：只读 Map
来源：http://dali.zhoulong.xyz/Article/details/gt2whqrnxwr.html

val m = mapOf("a" to 1)
来源：http://dali.ehwqpu.com/Article/details/gt2nfronxrd.html

[T14] Kotlin：循环
来源：http://dali.ybcxt.top/Article/details/gt2khcqjfpn.html

for (i in 1..10) println(i)
来源：http://dali.cheryme.top/Article/details/gt2mcsqjgbn.html

[T15] Kotlin：接口
来源：http://dali.9152youxi.cn/Article/details/gt2lbosxxwh.html

interface Shape { fun area(): Double }
来源：http://dali.shzxlz.cn/Article/details/gt2mkvnmcvt.html

[T16] Swift：Hello World
来源：http://dali.tian-w.cn/Article/details/gt2zsryggta.html

print("Hello")
来源：http://dali.yongpay.top/Article/details/gt2txvzxhsj.html

[T17] Swift：变量与常量
来源：http://dali.zhixingplan.top/Article/details/gt2vvyrfqos.html

var a = 1;  let b = 2
来源：http://dali.hysaishi.cn/Article/details/gt2rhkgmajm.html

[T18] Swift：字符串插值
来源：http://dali.yj20258888.top/Article/details/gt2uevldnla.html

"值: \(b)"
来源：http://dali.cashguo.top/Article/details/gt2beixdump.html

[T19] Swift：可选绑定
来源：http://dali.bjfxy.top/Article/details/gt2qykqngdk.html

if let n = opt { print(n) }
来源：http://dali.nanxinkj.top/Article/details/gt2wlzfowje.html

[T20] Swift：数组操作
来源：http://dali.nanxuanxn.top/Article/details/gt2xyxnzjtw.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.iojbl.cn/Article/details/gt2gphtwdxg.html

[T21] Swift：遍历
来源：http://dali.yj202588.top/Article/details/gt2pzwwqdrz.html

for x in a { print(x) }
来源：http://dali.wangshuangyany.cn/Article/details/gt2ebhwjfmx.html

[T22] Swift：字典
来源：http://dali.jyoumei.cn/Article/details/gt2aqlilcpk.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.shangyingyoupin.top/Article/details/gt2alylvpdq.html

[T23] Swift：函数
来源：http://dali.9152youxi.cn/Article/details/gt2ygltutam.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rgbpumgl.html

[T24] Swift：闭包
来源：http://dali.meibo888.top/Article/details/gt2jwwbrwjs.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.gogol.net.cn/Article/details/gt2oidprvos.html

[T25] Swift：结构体
来源：http://dali.hnxiangtu.top/Article/details/gt2gbjcdydc.html

struct P { var x: Int }
来源：http://dali.ppjwa.cn/Article/details/gt2bmuwqeak.html

[T26] Swift：类与重写
来源：http://dali.yueranfly.top/Article/details/gt2mdqklhka.html

class A: Base { override func f() {} }
来源：http://dali.fengsongda.top/Article/details/gt2vmqjkbzg.html

[T27] Swift：错误处理
来源：http://dali.ydzc1.top/Article/details/gt2xdlkshev.html

do { try f() } catch { print(error) }
来源：http://dali.xziqi.cn/Article/details/gt2jzxblqtf.html

[T28] Swift：枚举
来源：http://dali.feifeiyinyue.top/Article/details/gt2uvqpbqjl.html

enum Color { case red, green }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jjyixhlo.html

[T29] Swift：guard 提前返回
来源：http://dali.zhiwuduotai.top/Article/details/gt2hivoqfgs.html

guard let x = opt else { return }
来源：http://dali.xuetiantiany.cn/Article/details/gt2volxmneb.html

[T30] Swift：协议
来源：http://dali.xinyue.icu/Article/details/gt2fkunxtsj.html

protocol Shape { func area() -> Double }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2klrlqiya.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2yjicpczn.html

print("Hello")
来源：http://dali.gogol.net.cn/Article/details/gt2zhxpwjgi.html

[T32] Lua：局部变量
来源：http://dali.dashuyun.cn/Article/details/gt2wwvmasdk.html

local a = 1
来源：http://dali.guowangkeji.top/Article/details/gt2lifiuejd.html

[T33] Lua：表（数组）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rbulogom.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.yj20258.top/Article/details/gt2ciqneztu.html

[T34] Lua：遍历表
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tpzsiqdw.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.tian-w.cn/Article/details/gt2elhdxgfn.html

[T35] Lua：字典表
来源：http://dali.nwbrower.top/Article/details/gt2tssrxsjk.html

local d = { a = 1 };  d.b = 2
来源：http://dali.iojbl.cn/Article/details/gt2jnglysqz.html

[T36] Lua：函数
来源：http://dali.dianchejie.cn/Article/details/gt2tazlgjcm.html

function add(a, b) return a + b end
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hhhazwbq.html

[T37] Lua：字符串拼接
来源：http://dali.xylfe.cn/Article/details/gt2degrkens.html

"a" .. "b"
来源：http://dali.chenzaomai.com/Article/details/gt2cnrrobik.html

[T38] Lua：条件
来源：http://dali.jqgufenzy.top/Article/details/gt2fsbxgzan.html

if x > 0 then print("正") end
来源：http://dali.sxryk.cn/Article/details/gt2uflqvaiz.html

[T39] Lua：模式匹配
来源：http://dali.xziqi.cn/Article/details/gt2gzdkmtmh.html

string.find(s, "%d+")
来源：http://dali.xylfe.cn/Article/details/gt2ldjnwktl.html

[T40] Lua：元表
来源：http://dali.fengsongda.top/Article/details/gt2fcqoalrz.html

setmetatable({}, { __index = base })
来源：http://dali.yj202588.top/Article/details/gt2uhrsponk.html

[T41] Perl：Hello World
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gmiimngv.html

print "Hello\n";
来源：http://dali.cucudq.cn/Article/details/gt2lunrbrfi.html

[T42] Perl：变量类型
来源：http://dali.gaohongyu789.top/Article/details/gt2gacbtymv.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.jianghu66.top/Article/details/gt2dcwiyrbg.html

[T43] Perl：字符串插值
来源：http://dali.yj20258888.top/Article/details/gt2odrtftbj.html

"值: $a"
来源：http://dali.xylfe.cn/Article/details/gt2ujxwoiaz.html

[T44] Perl：条件
来源：http://dali.hammf.cn/Article/details/gt2euupmvod.html

if ($a > 0) { print "正"; }
来源：http://dali.hnqzz.top/Article/details/gt2lzxgyssj.html

[T45] Perl：数组遍历
来源：http://dali.jyoumei.cn/Article/details/gt2gcimmewc.html

for my $x (@arr) { print $x; }
来源：http://dali.fengsongda.top/Article/details/gt2wzyfdefa.html

[T46] Perl：哈希操作
来源：http://dali.9152youxi.cn/Article/details/gt2bmudvlvl.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.chenlongwang.top/Article/details/gt2adzvxmty.html

[T47] Perl：正则捕获
来源：http://dali.ivvv.top/Article/details/gt2gnbfxvlb.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.daxiang520.top/Article/details/gt2hcrthgds.html

[T48] Perl：正则替换
来源：http://dali.wangshuangyany.cn/Article/details/gt2xggcfequ.html

$s =~ s/old/new/g;
来源：http://dali.svipenyu.cn/Article/details/gt2srgdntgx.html

[T49] Perl：函数
来源：http://dali.cdnleiting.top/Article/details/gt2vruyxjtq.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.chenlongwang.top/Article/details/gt2docqnosi.html

[T50] Perl：逐行读文件
来源：http://dali.yueranfly.top/Article/details/gt2zzzecjth.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.chenjidiqi.icu/Article/details/gt2gmoxzrys.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zycfv.cn/Article/details/gt2vyjyfiaw.html

[T51] Scala：Hello World
来源：http://dali.andypj.xyz/Article/details/gt2olwyqsqs.html

println("Hello")
来源：http://dali.daxiang520.top/Article/details/gt2lvriqfoy.html

[T52] Scala：变量
来源：http://dali.ivvv.top/Article/details/gt2wdewsvbm.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2cbosettr.html

[T53] Scala：字符串插值
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kjtuzvvo.html

s"值: $b"
来源：http://dali.wangdashe.top/Article/details/gt2uxvxyfum.html

[T54] Scala：集合映射
来源：http://dali.guannengcc.top/Article/details/gt2ezjjwoop.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.c1oappe.top/Article/details/gt2xweqewqw.html

[T55] Scala：集合过滤
来源：http://dali.hongshengwenyu.top/Article/details/gt2rxbxyozg.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uotqldzo.html

[T56] Scala：样例类
来源：http://dali.cqqwz.cn/Article/details/gt2mkyistog.html

case class User(name: String, age: Int)
来源：http://dali.iojbl.cn/Article/details/gt2cfvospvh.html

[T57] Scala：模式匹配
来源：http://dali.zdqjudy.top/Article/details/gt2erqglkpz.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.yj20258888.top/Article/details/gt2kvpaqrev.html

[T58] Scala：函数定义
来源：http://dali.jinqigfzy.top/Article/details/gt2qftplhca.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.yuanzhike.top/Article/details/gt2pqdrybqk.html

[T59] Scala：循环
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ptbtxjrs.html

for (i <- 1 to 10) println(i)
来源：http://dali.sufxvd.cn/Article/details/gt2jpwbotrg.html

[T60] Scala：折叠
来源：http://dali.xziqi.cn/Article/details/gt2kgrqkqey.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.haohaochexian.top/Article/details/gt2mmxnbtqj.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2rczavuuv.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.nanxinkj.top/Article/details/gt2grgtrlje.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2nfmkfsxa.html

[U01] Py：创建虚拟环境
来源：http://dali.yj202588.top/Article/details/gt2hsuzsdrc.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2isnmtdpx.html

[U02] Py：导出 / 安装依赖
来源：http://dali.jqgufenzy.top/Article/details/gt2zpsjwscs.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.jlsjyb.cn/Article/details/gt2zinrltyf.html

[U03] Py：加载 .env 配置
来源：http://dali.vqdsnc.cn/Article/details/gt2hkawnbfr.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.0kj1m.cn/Article/details/gt2mebfmsak.html

[U04] Py：变量调试打印
来源：http://dali.ehwqpu.com/Article/details/gt2vxospuzj.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.daxiang520.top/Article/details/gt2cmmivdku.html

[U05] Py：列表去重且保序
来源：http://dali.smart0.xyz/Article/details/gt2mpewuoqs.html

list(dict.fromkeys(arr))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ynupzjts.html

[U06] Py：合并两个字典
来源：http://dali.xuetiantiany.cn/Article/details/gt2xxybmpyj.html

{**a, **b}
来源：http://dali.guannengcc.top/Article/details/gt2uqvqbqte.html

[U07] Py：反转字典键值
来源：http://dali.quarkkingdee.top/Article/details/gt2vdodmcau.html

{v: k for k, v in d.items()}
来源：http://dali.bjfxy.top/Article/details/gt2ttglruvu.html

[U08] Py：展平二维列表
来源：http://dali.hnqzz.top/Article/details/gt2ikzoekad.html

[y for x in nested for y in x]
来源：http://dali.zhengqikj.top/Article/details/gt2mdhtiwjt.html

[U09] Py：字典取最大值的键
来源：http://dali.kuanghao11.cn/Article/details/gt2lncuzouu.html

max(d, key=d.get)
来源：http://dali.redwolf501.top/Article/details/gt2qfmgnlut.html

[U10] Py：按值排序字典
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pfccozyl.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.hnqzz.top/Article/details/gt2urentuor.html

[U11] Py：生成器表达式
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2milacylu.html

(x * 2 for x in arr)
来源：http://dali.cdnleiting.top/Article/details/gt2jgwzbpcf.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.meibo888.top/Article/details/gt2uzpuxfxq.html

Counter(arr).most_common(3)
来源：http://dali.andypj.xyz/Article/details/gt2ikraoezg.html

[U13] Py：固定长度队列
来源：http://dali.ppjwa.cn/Article/details/gt2qwmzfvie.html

deque(maxlen=10)
来源：http://dali.tian-w.cn/Article/details/gt2dwqglyhg.html

[U14] Py：分组收集到列表
来源：http://dali.hammf.cn/Article/details/gt2cblborzp.html

defaultdict(list)
来源：http://dali.hywenlv.cn/Article/details/gt2skvdbxsy.html

[U15] Py：高精度计时
来源：http://dali.zhengqikj.top/Article/details/gt2acwbnlzx.html

t = time.perf_counter()
来源：http://dali.guannengcc.top/Article/details/gt2qdqrsxqm.html

[U16] Py：命令行参数解析
来源：http://dali.pycfn.com/Article/details/gt2fqwjvtdc.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.hammf.cn/Article/details/gt2jfltjkld.html

[U17] Py：初始化日志
来源：http://dali.zhiwuduotai.top/Article/details/gt2nhvxjuqy.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ncombckp.html

[U18] Py：预编译正则
来源：http://dali.jinqigfzy.top/Article/details/gt2zwdqhuwn.html

pat = re.compile(r"\d+")
来源：http://dali.guowangkeji.top/Article/details/gt2guxziqpd.html

[U19] Py：正则替换带回调
来源：http://dali.meibo888.top/Article/details/gt2jecfsrtc.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.hammf.cn/Article/details/gt2xjcgdxmf.html

[U20] Py：缓存函数结果
来源：http://dali.zhoulong.xyz/Article/details/gt2ejdblclw.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhengqikj.top/Article/details/gt2rdzvqtod.html

[U21] Py：自定义上下文管理器
来源：http://dali.ehwqpu.com/Article/details/gt2ncnenhsp.html

@contextlib.contextmanager
来源：http://dali.0kj1m.cn/Article/details/gt2xrhkaxwl.html

[U22] Py：矩阵转置
来源：http://dali.jianghu66.top/Article/details/gt2xzxjlpsp.html

list(zip(*m))
来源：http://dali.feifeiyinyue.top/Article/details/gt2daldazba.html

[U23] Py：分块读取大文件
来源：http://dali.iojbl.cn/Article/details/gt2nfgajaxg.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.jlsjyb.cn/Article/details/gt2vohbdlvl.html

[U24] Py：路径操作
来源：http://dali.svipenyu.cn/Article/details/gt2rdfeudkw.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.gzhubu.top/Article/details/gt2vmfdcjul.html

[U25] Py：CSV 按字典读
来源：http://dali.hywenlv.cn/Article/details/gt2ldbtgsde.html

csv.DictReader(f)
来源：http://dali.jiagoushi.top/Article/details/gt2ymmfabbw.html

[U26] Py：并发下载
来源：http://dali.mhx1999.top/Article/details/gt2cplgxihl.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.cdnleiting.top/Article/details/gt2mvbzqbxw.html

[U27] Py：异步 HTTP
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ulavmtir.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2aogkfams.html

[U28] Py：类型别名
来源：http://dali.snrcjt.cn/Article/details/gt2vckklfeb.html

UserId = int
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2owfxnssk.html

[U29] Py：属性校验
来源：http://dali.kuanghao11.cn/Article/details/gt2cdxdgwfj.html

@property 与 @x.setter 配合
来源：http://dali.0kj1m.cn/Article/details/gt2xnrlnrzc.html

[U30] Py：数据类
来源：http://dali.kuanghao11.cn/Article/details/gt2vwgiqmeq.html

@dataclass(slots=True)
来源：http://dali.iojbl.cn/Article/details/gt2qlqyfgdl.html

[U31] Py：单测
来源：http://dali.sweek.top/Article/details/gt2pjaiamyu.html

python -m pytest -q
来源：http://dali.tianlin.xyz/Article/details/gt2iuommcyr.html

[U32] Py：代码格式化
来源：http://dali.yj20258.top/Article/details/gt2wtwgvslr.html

ruff format . && ruff check --fix .
来源：http://dali.ydzc1.top/Article/details/gt2goclpgpc.html

[U33] Py：打包发布
来源：http://dali.tian-w.cn/Article/details/gt2qjqsndxd.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.sysykeji.top/Article/details/gt2qtyjalxu.html

[U34] Py：判断编码
来源：http://dali.aibaodan.cn/Article/details/gt2csqrsmji.html

chardet.detect(raw)
来源：http://dali.hnxiangtu.top/Article/details/gt2tzoqplbq.html


<!-- 参考信息 -->