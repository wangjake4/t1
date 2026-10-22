代发 wailian999

FILE *f = fopen("a.txt", "r");
来源：http://dali.tian-w.cn/Article/details/gt2pjegdjod.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.jlsjyb.cn/Article/details/gt2qnysbzyl.html

fclose(f);
来源：http://dali.fzhhl.top/Article/details/gt2vppyiwlh.html

[S12] C：写文件
来源：http://dali.cashguo.top/Article/details/gt2ngrhubpw.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.hysaishi.cn/Article/details/gt2opqbejnw.html

[S13] C：宏定义
来源：http://dali.ydzc1.top/Article/details/gt2ububkrdy.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2qlnyvafx.html

[S14] C：枚举
来源：http://dali.jinqigufen.top/Article/details/gt2krmhexpn.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zycfv.cn/Article/details/gt2qswslzix.html

[S15] C：类型转换
来源：http://dali.xuetiantiany.cn/Article/details/gt2fowuycyd.html

(double) a / b
来源：http://dali.ppjwa.cn/Article/details/gt2cklsacdg.html

[S16] C：位操作置位
来源：http://dali.yanxiufei.cn/Article/details/gt2lkmueyub.html

x |= (1 << 3);
来源：http://dali.daria6918.cn/Article/details/gt2xqykpvbk.html

[S17] C：安全拼接字符串
来源：http://dali.gogol.net.cn/Article/details/gt2qrzbksbs.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.ivvv.top/Article/details/gt2pvghejcs.html

[S18] C：命令行参数
来源：http://dali.aibaodan.cn/Article/details/gt2njryxctp.html

int main(int argc, char **argv)
来源：http://dali.hysaishi.cn/Article/details/gt2njbeahbl.html

[S19] C：快速排序
来源：http://dali.wangshuangyany.cn/Article/details/gt2gkkmywhh.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhoulong.xyz/Article/details/gt2ouybfyme.html

[S20] C：二分查找
来源：http://dali.wangshuangyany.cn/Article/details/gt2rrcionbd.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bgmwbvzs.html

[S21] C：字符类别判断
来源：http://dali.andypj.xyz/Article/details/gt2eiigdxws.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.jqgufenzy.top/Article/details/gt2eejsrslr.html

[S22] C：字符串转数字
来源：http://dali.hfpthk.cn/Article/details/gt2pxlwskex.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.guannengcc.top/Article/details/gt2fasjnagh.html

[S23] C：随机数
来源：http://dali.aizwys.cn/Article/details/gt2qicxpimu.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.fzhhl.top/Article/details/gt2ciffoxsp.html

[S24] C：获取本地时间
来源：http://dali.tianlin.xyz/Article/details/gt2ffmhsnwt.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.yanxiufei.cn/Article/details/gt2axfjweyk.html

[S25] C：内存拷贝
来源：http://dali.jinqigufen.top/Article/details/gt2gyvovagp.html

memcpy(dst, src, n);
来源：http://dali.zhixingplan.top/Article/details/gt2mfgdcbij.html

[S26] C：内存清零
来源：http://dali.pycfn.com/Article/details/gt2wbqmctpb.html

memset(a, 0, sizeof a);
来源：http://dali.quarkkingdee.top/Article/details/gt2ykrripyj.html

[S27] C：定义常量
来源：http://dali.wangdashe.top/Article/details/gt2rxkkqmzy.html

const double PI = 3.14159;
来源：http://dali.jinqigufen.top/Article/details/gt2nlzbecgd.html

[S28] C：静态变量
来源：http://dali.hammf.cn/Article/details/gt2acfqyyrq.html

static int counter = 0;
来源：http://dali.cdnleiting.top/Article/details/gt2bododayp.html

[S29] C：变参函数
来源：http://dali.gotoacloud.top/Article/details/gt2ziqlitpt.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.jianghu66.top/Article/details/gt2gkzpjpnv.html

[S30] C：头文件保护
来源：http://dali.jinqigufen.top/Article/details/gt2vlktxjys.html

#ifndef X_H
来源：http://dali.yuanzhike.top/Article/details/gt2zeyzgact.html

#define X_H
来源：http://dali.c1oappe.top/Article/details/gt2sydutcoz.html

#endif
来源：http://dali.zdqjudy.top/Article/details/gt2vfsvlhiy.html

[S31] C++：Hello World
来源：http://dali.shangyingyoupin.top/Article/details/gt2grfeeodk.html

#include <iostream>
来源：http://dali.yanxiufei.cn/Article/details/gt2urrvkynb.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.cdnleiting.top/Article/details/gt2vdmgigeu.html

[S32] C++：字符串
来源：http://dali.316326.xyz/Article/details/gt2pncuisit.html

std::string s = "hi";  s += "!";
来源：http://dali.pengpengdd.cyou/Article/details/gt2grdnlgnb.html

[S33] C++：vector 增删
来源：http://dali.snrcjt.cn/Article/details/gt2ynnbzede.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ecdlofye.html

[S34] C++：遍历 vector
来源：http://dali.cdnleiting.top/Article/details/gt2xizyimva.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2bmyfhvpp.html

[S35] C++：map
来源：http://dali.snrcjt.cn/Article/details/gt2ysyctkmu.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.gotoacloud.top/Article/details/gt2pmwkicat.html

[S36] C++：unordered_map
来源：http://dali.zhixingplan.top/Article/details/gt2cltozjmh.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.chenzaomai.com/Article/details/gt2jwvlyntn.html

[S37] C++：set
来源：http://dali.haohaochexian.top/Article/details/gt2ycjxukjf.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhoulong.xyz/Article/details/gt2lcnhzlya.html

[S38] C++：排序
来源：http://dali.hnqzz.top/Article/details/gt2kagsjrzp.html

std::sort(v.begin(), v.end());
来源：http://dali.guannengcc.top/Article/details/gt2cugxrymi.html

[S39] C++：自定义比较器排序
来源：http://dali.tian-w.cn/Article/details/gt2gypbelsb.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.ybcxt.top/Article/details/gt2ykgnpgrv.html

[S40] C++：查找元素
来源：http://dali.zhengqikj.top/Article/details/gt2vnuselib.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.iojbl.cn/Article/details/gt2uialohkx.html

[S41] C++：类与构造函数
来源：http://dali.zhixingplan.top/Article/details/gt2jaaweluh.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vzkxslpx.html

[S42] C++：继承与虚函数
来源：http://dali.feifeiyinyue.top/Article/details/gt2wbfybjoi.html

class B : public Base { public: void f() override {} };
来源：http://dali.dianchejie.cn/Article/details/gt2lypegezs.html

[S43] C++：智能指针
来源：http://dali.jinqigfzy.top/Article/details/gt2vauxjpeq.html

auto p = std::make_unique<int>(5);
来源：http://dali.xinyue.icu/Article/details/gt2tekoxjes.html

[S44] C++：引用传参
来源：http://dali.cucudq.cn/Article/details/gt2avlqevsq.html

void inc(int &x) { ++x; }
来源：http://dali.jianghu66.top/Article/details/gt2dwwokkxh.html

[S45] C++：lambda
来源：http://dali.jqgfzy.top/Article/details/gt2ljlmxmqu.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.jlsjyb.cn/Article/details/gt2duriykbr.html

[S46] C++：函数模板
来源：http://dali.nanxinkj.top/Article/details/gt2qopdutuw.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.xuanzx.com/Article/details/gt2vpxaxlvu.html

[S47] C++：结构化绑定遍历
来源：http://dali.feifeiyinyue.top/Article/details/gt2hbqmgwhh.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.kuanghao11.cn/Article/details/gt2nkwhekma.html

[S48] C++：逐行读文件
来源：http://dali.shzxlz.cn/Article/details/gt2gnlnktoh.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wbbdvcll.html

while (std::getline(in, line)) { }
来源：http://dali.9152youxi.cn/Article/details/gt2bkskkpmd.html

[S49] C++：写文件
来源：http://dali.ehwqpu.com/Article/details/gt2owakqnib.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.jianghu66.top/Article/details/gt2spdyqhzr.html

[S50] C++：格式化数字
来源：http://dali.hnxiangtu.top/Article/details/gt2tvdjgipr.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.sufxvd.cn/Article/details/gt2xrecjckb.html

[S51] C++：显式类型转换
来源：http://dali.gaohongyu789.top/Article/details/gt2ccydqlhv.html

static_cast<double>(a) / b
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ilwulgnd.html

[S52] C++：const 与 noexcept
来源：http://dali.fzhhl.top/Article/details/gt2vivaajlt.html

int size() const noexcept { return n_; }
来源：http://dali.jianghu66.top/Article/details/gt2eqwwrybb.html

[S53] C++：移动语义
来源：http://dali.jyoumei.cn/Article/details/gt2kbvfhsrf.html

std::vector<int> w = std::move(v);
来源：http://dali.jlsjyb.cn/Article/details/gt2zwdrpiqv.html

[S54] C++：异常处理
来源：http://dali.yongpay.top/Article/details/gt2wlobsqzw.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.gzhubu.top/Article/details/gt2iddntoqu.html

[S55] C++：结构化绑定
来源：http://dali.shzxlz.cn/Article/details/gt2udrdmvoq.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.jinqigfzy.top/Article/details/gt2fdbuquas.html

[S56] C++：optional
来源：http://dali.jinqigfzy.top/Article/details/gt2hfuuktrf.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.cashguo.top/Article/details/gt2rdzuivyx.html

[S57] C++：编译期常量
来源：http://dali.ybcxt.top/Article/details/gt2dawxuxht.html

constexpr int N = 10;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vjrhmjag.html

[S58] C++：命名空间
来源：http://dali.zhengqikj.top/Article/details/gt2jbbtxfja.html

namespace ns { int f() { return 1; } }
来源：http://dali.yueranfly.top/Article/details/gt2rlaabgcm.html

[S59] C++：静态断言
来源：http://dali.hysaishi.cn/Article/details/gt2nqikvvai.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.sufxvd.cn/Article/details/gt2kaoqwzvu.html

[S60] C++：遍历并删除元素
来源：http://dali.zdqjudy.top/Article/details/gt2wpvppdub.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.chenlongwang.top/Article/details/gt2fjkhtwia.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gt2rrfcdssy.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.bjfxy.top/Article/details/gt2ikldwajz.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gt2lkklbjkn.html

[T01] Kotlin：Hello World
来源：http://dali.daria6918.cn/Article/details/gt2slowtizi.html

println("Hello")
来源：http://dali.redwolf501.top/Article/details/gt2klsjzlzi.html

[T02] Kotlin：变量
来源：http://dali.hongshengwenyu.top/Article/details/gt2ufhuisol.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.ivvv.top/Article/details/gt2srauvemd.html

[T03] Kotlin：字符串模板
来源：http://dali.mhx1999.top/Article/details/gt2pgrxlxty.html

"值: $b"
来源：http://dali.ybcxt.top/Article/details/gt2tebjctuw.html

[T04] Kotlin：空安全
来源：http://dali.yvedp.cn/Article/details/gt2mumqxyyj.html

val n: String? = null;  n?.length
来源：http://dali.aizwys.cn/Article/details/gt2rhuyugmz.html

[T05] Kotlin：when 表达式
来源：http://dali.316326.xyz/Article/details/gt2oobyhlfs.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.pengpengdd.cyou/Article/details/gt2jcmiyeda.html

[T06] Kotlin：集合映射
来源：http://dali.iojbl.cn/Article/details/gt2xbyukeri.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.cdnleiting.top/Article/details/gt2kkherprl.html

[T07] Kotlin：集合过滤
来源：http://dali.nanxinkj.top/Article/details/gt2sfssykni.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mxvdrgvi.html

[T08] Kotlin：数据类
来源：http://dali.vqdsnc.cn/Article/details/gt2xwuoylmw.html

data class User(val name: String, val age: Int)
来源：http://dali.nanxuanxn.top/Article/details/gt2vctawipl.html

[T09] Kotlin：扩展函数
来源：http://dali.zdqjudy.top/Article/details/gt2kaoukrbj.html

fun String.exclaim() = this + "!"
来源：http://dali.xylfe.cn/Article/details/gt2bbopmlpe.html

[T10] Kotlin：默认参数
来源：http://dali.haohaochexian.top/Article/details/gt2sbqycuch.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.tian-w.cn/Article/details/gt2ilyqhsub.html

[T11] Kotlin：协程
来源：http://dali.daria6918.cn/Article/details/gt2qgvpnsxl.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.jyoumei.cn/Article/details/gt2xalhvagd.html

[T12] Kotlin：解构声明
来源：http://dali.fengsongda.top/Article/details/gt2cjfzdybp.html

val (a, b) = Pair(1, 2)
来源：http://dali.chenjidiqi.icu/Article/details/gt2hoaummgk.html

[T13] Kotlin：只读 Map
来源：http://dali.hongshengwenyu.top/Article/details/gt2pmieexvo.html

val m = mapOf("a" to 1)
来源：http://dali.yanxiufei.cn/Article/details/gt2hpyzyyck.html

[T14] Kotlin：循环
来源：http://dali.ehwqpu.com/Article/details/gt2rjvxxxyi.html

for (i in 1..10) println(i)
来源：http://dali.ydzc1.top/Article/details/gt2uhresqii.html

[T15] Kotlin：接口
来源：http://dali.pengpengdd.cyou/Article/details/gt2gbknyyji.html

interface Shape { fun area(): Double }
来源：http://dali.yangfankeji.com/Article/details/gt2cpgwfjzy.html

[T16] Swift：Hello World
来源：http://dali.sweek.top/Article/details/gt2xhaoeenx.html

print("Hello")
来源：http://dali.ehwqpu.com/Article/details/gt2acytbkwi.html

[T17] Swift：变量与常量
来源：http://dali.cheryme.top/Article/details/gt2nuvmnfig.html

var a = 1;  let b = 2
来源：http://dali.ybcxt.top/Article/details/gt2gxkzoenw.html

[T18] Swift：字符串插值
来源：http://dali.wangdashe.top/Article/details/gt2djtriwic.html

"值: \(b)"
来源：http://dali.yj202588.top/Article/details/gt2vvoixyve.html

[T19] Swift：可选绑定
来源：http://dali.haohaochexian.top/Article/details/gt2xowtrzor.html

if let n = opt { print(n) }
来源：http://dali.yj20258888.top/Article/details/gt2grxabisd.html

[T20] Swift：数组操作
来源：http://dali.andypj.xyz/Article/details/gt2bocyoxkh.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.chenlongwang.top/Article/details/gt2snwakxso.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2wnzzkgvd.html

for x in a { print(x) }
来源：http://dali.sufxvd.cn/Article/details/gt2afrjfomo.html

[T22] Swift：字典
来源：http://dali.fzhhl.top/Article/details/gt2gvpcfojd.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.yonumen.top/Article/details/gt2kskgbdaz.html

[T23] Swift：函数
来源：http://dali.tianlin.xyz/Article/details/gt2rxjifclm.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.xziqi.cn/Article/details/gt2ybxfhdpj.html

[T24] Swift：闭包
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mnwokere.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.smart0.xyz/Article/details/gt2xugtssnw.html

[T25] Swift：结构体
来源：http://dali.yonumen.top/Article/details/gt2qekzvpyi.html

struct P { var x: Int }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mvlbduaa.html

[T26] Swift：类与重写
来源：http://dali.cdnleiting.top/Article/details/gt2khakafoc.html

class A: Base { override func f() {} }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jzijpknn.html

[T27] Swift：错误处理
来源：http://dali.cqqwz.cn/Article/details/gt2uwkulmhk.html

do { try f() } catch { print(error) }
来源：http://dali.cdnleiting.top/Article/details/gt2ymqnbmmm.html

[T28] Swift：枚举
来源：http://dali.tian-w.cn/Article/details/gt2kjssrzbs.html

enum Color { case red, green }
来源：http://dali.tianlin.xyz/Article/details/gt2dpejqpbg.html

[T29] Swift：guard 提前返回
来源：http://dali.jlsjyb.cn/Article/details/gt2vclgumrw.html

guard let x = opt else { return }
来源：http://dali.tanke756.top/Article/details/gt2nommgdnk.html

[T30] Swift：协议
来源：http://dali.haohaochexian.top/Article/details/gt2yegprbcz.html

protocol Shape { func area() -> Double }
来源：http://dali.gzhubu.top/Article/details/gt2vxmxmcbz.html

[T31] Lua：Hello World
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ynrtrknp.html

print("Hello")
来源：http://dali.nwbrower.top/Article/details/gt2hcjjstjz.html

[T32] Lua：局部变量
来源：http://dali.haohaochexian.top/Article/details/gt2qzvrtavt.html

local a = 1
来源：http://dali.jqgufenzy.top/Article/details/gt2klmnxdhe.html

[T33] Lua：表（数组）
来源：http://dali.hammf.cn/Article/details/gt2buytpxis.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.shzxlz.cn/Article/details/gt2iauxjyhf.html

[T34] Lua：遍历表
来源：http://dali.yonumen.top/Article/details/gt2fisaqzxc.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gkwcrcyc.html

[T35] Lua：字典表
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tadnkolc.html

local d = { a = 1 };  d.b = 2
来源：http://dali.sufxvd.cn/Article/details/gt2cebchqlk.html

[T36] Lua：函数
来源：http://dali.redwolf501.top/Article/details/gt2gbrsgzjl.html

function add(a, b) return a + b end
来源：http://dali.zhongyouzk.top/Article/details/gt2fgynpjgh.html

[T37] Lua：字符串拼接
来源：http://dali.cheryme.top/Article/details/gt2dneduqzv.html

"a" .. "b"
来源：http://dali.bjfxy.top/Article/details/gt2srthjqai.html

[T38] Lua：条件
来源：http://dali.hongshengwenyu.top/Article/details/gt2fhqajqdx.html

if x > 0 then print("正") end
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xejflgwf.html

[T39] Lua：模式匹配
来源：http://dali.nanxinkj.top/Article/details/gt2jyuxlipz.html

string.find(s, "%d+")
来源：http://dali.daxiang520.top/Article/details/gt2xjhztdvz.html

[T40] Lua：元表
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lbtnftwn.html

setmetatable({}, { __index = base })
来源：http://dali.xuanzx.com/Article/details/gt2ibmaquad.html

[T41] Perl：Hello World
来源：http://dali.hywenlv.cn/Article/details/gt2gpdgffgx.html

print "Hello\n";
来源：http://dali.wangdashe.top/Article/details/gt2fwmvoxbg.html

[T42] Perl：变量类型
来源：http://dali.tianlin.xyz/Article/details/gt2iceetree.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.xuanzx.com/Article/details/gt2xulpukyk.html

[T43] Perl：字符串插值
来源：http://dali.tian-w.cn/Article/details/gt2ifzrqanb.html

"值: $a"
来源：http://dali.aizwys.cn/Article/details/gt2vatcswcv.html

[T44] Perl：条件
来源：http://dali.tianlin.xyz/Article/details/gt2yrhoiprs.html

if ($a > 0) { print "正"; }
来源：http://dali.jianghu66.top/Article/details/gt2rcrxkpqq.html

[T45] Perl：数组遍历
来源：http://dali.shuidangran.top/Article/details/gt2gmopyrkv.html

for my $x (@arr) { print $x; }
来源：http://dali.jyoumei.cn/Article/details/gt2nklgwwsz.html

[T46] Perl：哈希操作
来源：http://dali.yueranfly.top/Article/details/gt2ctcutjgc.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2lixtoswh.html

[T47] Perl：正则捕获
来源：http://dali.tanke756.top/Article/details/gt2migtpihn.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.jyoumei.cn/Article/details/gt2qceoknir.html

[T48] Perl：正则替换
来源：http://dali.316326.xyz/Article/details/gt2dgbtxsaj.html

$s =~ s/old/new/g;
来源：http://dali.feifeiyinyue.top/Article/details/gt2kjvjhwtx.html

[T49] Perl：函数
来源：http://dali.jlsjyb.cn/Article/details/gt2tcjvrmml.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.cashguo.top/Article/details/gt2aeljlogu.html

[T50] Perl：逐行读文件
来源：http://dali.fzhhl.top/Article/details/gt2cksqymqa.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.sysykeji.top/Article/details/gt2hrjpunna.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.fzhhl.top/Article/details/gt2eqaqbtmx.html

[T51] Scala：Hello World
来源：http://dali.zdqjudy.top/Article/details/gt2bprhorsa.html

println("Hello")
来源：http://dali.wangshuangyany.cn/Article/details/gt2unlctchu.html

[T52] Scala：变量
来源：http://dali.yuanzhike.top/Article/details/gt2gvskqpkj.html

val a = 1;  var b = 2
来源：http://dali.smart0.xyz/Article/details/gt2gvhgsswh.html

[T53] Scala：字符串插值
来源：http://dali.yanxiufei.cn/Article/details/gt2pzcvmgvb.html

s"值: $b"
来源：http://dali.xinyue.icu/Article/details/gt2egfvwnjx.html

[T54] Scala：集合映射
来源：http://dali.chenlongwang.top/Article/details/gt2aabfflfn.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.tanke756.top/Article/details/gt2dftiefvv.html

[T55] Scala：集合过滤
来源：http://dali.vqdsnc.cn/Article/details/gt2khinhnwq.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.aibaodan.cn/Article/details/gt2webcjqee.html

[T56] Scala：样例类
来源：http://dali.xylfe.cn/Article/details/gt2cyijbygg.html

case class User(name: String, age: Int)
来源：http://dali.yj20258.top/Article/details/gt2izdnpkbw.html

[T57] Scala：模式匹配
来源：http://dali.yj202588.top/Article/details/gt2lgzxlsgg.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yhypwwbv.html

[T58] Scala：函数定义
来源：http://dali.ybcxt.top/Article/details/gt2jcfxsqtd.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.0kj1m.cn/Article/details/gt2rtlawixq.html

[T59] Scala：循环
来源：http://dali.fzhhl.top/Article/details/gt2efrtbvmf.html

for (i <- 1 to 10) println(i)
来源：http://dali.hnxiangtu.top/Article/details/gt2ognurieb.html

[T60] Scala：折叠
来源：http://dali.jlsjyb.cn/Article/details/gt2jyjnwqvx.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.cdnleiting.top/Article/details/gt2fybjdedc.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gt2mxczurhd.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.gzhubu.top/Article/details/gt2mfnomsns.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2fljpisxe.html

[U01] Py：创建虚拟环境
来源：http://dali.pengpengdd.cyou/Article/details/gt2wzihxcly.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hierksuk.html

[U02] Py：导出 / 安装依赖
来源：http://dali.hnqzz.top/Article/details/gt2vafhmgdv.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.hnqzz.top/Article/details/gt2naskiwrx.html

[U03] Py：加载 .env 配置
来源：http://dali.shuidangran.top/Article/details/gt2hyehtcna.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.hysaishi.cn/Article/details/gt2jbptwrpx.html

[U04] Py：变量调试打印
来源：http://dali.zhiwuduotai.top/Article/details/gt2uommctam.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.jlsjyb.cn/Article/details/gt2lfdfcxgf.html

[U05] Py：列表去重且保序
来源：http://dali.zhongyouzk.top/Article/details/gt2grbwqrwy.html

list(dict.fromkeys(arr))
来源：http://dali.hywenlv.cn/Article/details/gt2frqdzlta.html

[U06] Py：合并两个字典
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vkzfysrq.html

{**a, **b}
来源：http://dali.nwbrower.top/Article/details/gt2bjdeupsz.html

[U07] Py：反转字典键值
来源：http://dali.gotoacloud.top/Article/details/gt2ziybrjav.html

{v: k for k, v in d.items()}
来源：http://dali.haohaochexian.top/Article/details/gt2vtwvrwwz.html

[U08] Py：展平二维列表
来源：http://dali.pengpengdd.cyou/Article/details/gt2ouhmcpcv.html

[y for x in nested for y in x]
来源：http://dali.tanke756.top/Article/details/gt2enwryzgt.html

[U09] Py：字典取最大值的键
来源：http://dali.zhengqikj.top/Article/details/gt2vxlorkmn.html

max(d, key=d.get)
来源：http://dali.yonumen.top/Article/details/gt2fczyqtzu.html

[U10] Py：按值排序字典
来源：http://dali.snrcjt.cn/Article/details/gt2kbsbmrcx.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.daria6918.cn/Article/details/gt2pzogwyqa.html

[U11] Py：生成器表达式
来源：http://dali.haohaochexian.top/Article/details/gt2hqxkjmvw.html

(x * 2 for x in arr)
来源：http://dali.dianchejie.cn/Article/details/gt2lqpfymmk.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.kuanghao11.cn/Article/details/gt2astqodxx.html

Counter(arr).most_common(3)
来源：http://dali.ppjwa.cn/Article/details/gt2kpzdxepl.html

[U13] Py：固定长度队列
来源：http://dali.vqdsnc.cn/Article/details/gt2vtsdgkzo.html

deque(maxlen=10)
来源：http://dali.ivvv.top/Article/details/gt2fxdoowtx.html

[U14] Py：分组收集到列表
来源：http://dali.cdnleiting.top/Article/details/gt2vabgvzuc.html

defaultdict(list)
来源：http://dali.yanxiufei.cn/Article/details/gt2ltjvgwof.html

[U15] Py：高精度计时
来源：http://dali.yongpay.top/Article/details/gt2yuhagtyk.html

t = time.perf_counter()
来源：http://dali.aizwys.cn/Article/details/gt2qiyssfkm.html

[U16] Py：命令行参数解析
来源：http://dali.bjfxy.top/Article/details/gt2doyqsdpz.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.jiagoushi.top/Article/details/gt2iavolizk.html

[U17] Py：初始化日志
来源：http://dali.shangyingyoupin.top/Article/details/gt2lxelzptt.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.hammf.cn/Article/details/gt2btzaaqqm.html

[U18] Py：预编译正则
来源：http://dali.yj202588.top/Article/details/gt2owsjevcs.html

pat = re.compile(r"\d+")
来源：http://dali.cqqwz.cn/Article/details/gt2hfgbetou.html

[U19] Py：正则替换带回调
来源：http://dali.yonumen.top/Article/details/gt2kialwiee.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.xylfe.cn/Article/details/gt2orsfibtp.html

[U20] Py：缓存函数结果
来源：http://dali.gzhubu.top/Article/details/gt2wvahcyeu.html

@functools.lru_cache(maxsize=None)
来源：http://dali.fengsongda.top/Article/details/gt2ljcrizjv.html

[U21] Py：自定义上下文管理器
来源：http://dali.guannengcc.top/Article/details/gt2nvvupmgu.html

@contextlib.contextmanager
来源：http://dali.shuidangran.top/Article/details/gt2euurjyfm.html

[U22] Py：矩阵转置
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2waqxqssy.html

list(zip(*m))
来源：http://dali.0kj1m.cn/Article/details/gt2ciqdxrfn.html

[U23] Py：分块读取大文件
来源：http://dali.sxryk.cn/Article/details/gt2vwrkgnlm.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.xylfe.cn/Article/details/gt2kskkbuvo.html

[U24] Py：路径操作
来源：http://dali.fzhhl.top/Article/details/gt2okzmucdn.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.shzxlz.cn/Article/details/gt2enhattzb.html

[U25] Py：CSV 按字典读
来源：http://dali.yangfankeji.com/Article/details/gt2yvzhiazv.html

csv.DictReader(f)
来源：http://dali.sweek.top/Article/details/gt2cipooorb.html

[U26] Py：并发下载
来源：http://dali.wangdashe.top/Article/details/gt2vinbbpux.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zdqjudy.top/Article/details/gt2gwplnfjp.html

[U27] Py：异步 HTTP
来源：http://dali.yj202588.top/Article/details/gt2qxutpyhr.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.jlsjyb.cn/Article/details/gt2dpfjilsc.html

[U28] Py：类型别名
来源：http://dali.sweek.top/Article/details/gt2xpzyneqw.html

UserId = int
来源：http://dali.9152youxi.cn/Article/details/gt2abyknqgn.html

[U29] Py：属性校验
来源：http://dali.ybcxt.top/Article/details/gt2eiwfvmri.html

@property 与 @x.setter 配合
来源：http://dali.gzhubu.top/Article/details/gt2ifvsatbb.html

[U30] Py：数据类
来源：http://dali.feifeiyinyue.top/Article/details/gt2nwvcseqc.html

@dataclass(slots=True)
来源：http://dali.hammf.cn/Article/details/gt2fmyjuubl.html

[U31] Py：单测
来源：http://dali.guowangkeji.top/Article/details/gt2ylerpsmd.html

python -m pytest -q
来源：http://dali.zhengqikj.top/Article/details/gt2tpzrquei.html

[U32] Py：代码格式化
来源：http://dali.sufxvd.cn/Article/details/gt2njlipqti.html

ruff format . && ruff check --fix .
来源：http://dali.yongpay.top/Article/details/gt2vxhopznt.html

[U33] Py：打包发布
来源：http://dali.shzxlz.cn/Article/details/gt2ellznwfc.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.sxryk.cn/Article/details/gt2anpeiidq.html

[U34] Py：判断编码
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sbrcfiyl.html

chardet.detect(raw)
来源：http://dali.tian-w.cn/Article/details/gt2xznscmfr.html


<!-- 参考信息 -->