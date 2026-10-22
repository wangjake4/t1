代发 wailian999

enum Color { RED, GREEN, BLUE };
来源：http://dali.tian-w.cn/Article/details/gt2vfxsbeud.html

[S15] C：类型转换
来源：http://dali.ppjwa.cn/Article/details/gt2tomniwoo.html

(double) a / b
来源：http://dali.jinqigfzy.top/Article/details/gt2oavbxbcy.html

[S16] C：位操作置位
来源：http://dali.xuetiantiany.cn/Article/details/gt2doxhdwzn.html

x |= (1 << 3);
来源：http://dali.gaohongyu789.top/Article/details/gt2iqcgqvin.html

[S17] C：安全拼接字符串
来源：http://dali.hnxiangtu.top/Article/details/gt2fknbdmlf.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.nanxinkj.top/Article/details/gt2qhkzlkla.html

[S18] C：命令行参数
来源：http://dali.cheryme.top/Article/details/gt2ozaritlx.html

int main(int argc, char **argv)
来源：http://dali.fzhhl.top/Article/details/gt2bitjnrte.html

[S19] C：快速排序
来源：http://dali.yuxming.cn/Article/details/gt2omswneov.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.9152youxi.cn/Article/details/gt2yxlplegg.html

[S20] C：二分查找
来源：http://dali.tianlin.xyz/Article/details/gt2kikdeivk.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.hammf.cn/Article/details/gt2otjjmpaa.html

[S21] C：字符类别判断
来源：http://dali.dashuyun.cn/Article/details/gt2xxunfrul.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.andypj.xyz/Article/details/gt2upqgkolz.html

[S22] C：字符串转数字
来源：http://dali.yanxiufei.cn/Article/details/gt2aqojynim.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.jinqigfzy.top/Article/details/gt2uoeglhfh.html

[S23] C：随机数
来源：http://dali.yongpay.top/Article/details/gt2dryhrwai.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.dashuyun.cn/Article/details/gt2ugrxmajd.html

[S24] C：获取本地时间
来源：http://dali.ehwqpu.com/Article/details/gt2lhbujjas.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lgqiadbj.html

[S25] C：内存拷贝
来源：http://dali.yanxiufei.cn/Article/details/gt2jqduasms.html

memcpy(dst, src, n);
来源：http://dali.9152youxi.cn/Article/details/gt2xglfzwlg.html

[S26] C：内存清零
来源：http://dali.feifeiyinyue.top/Article/details/gt2izyihual.html

memset(a, 0, sizeof a);
来源：http://dali.sufxvd.cn/Article/details/gt2hzogjvur.html

[S27] C：定义常量
来源：http://dali.haohaochexian.top/Article/details/gt2bsylibwk.html

const double PI = 3.14159;
来源：http://dali.nwbrower.top/Article/details/gt2yvldgnxb.html

[S28] C：静态变量
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dhyuxkih.html

static int counter = 0;
来源：http://dali.yj20258888.top/Article/details/gt2ewosmvto.html

[S29] C：变参函数
来源：http://dali.ydzc1.top/Article/details/gt2jdxgpkxl.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.bjfxy.top/Article/details/gt2xqgwudmv.html

[S30] C：头文件保护
来源：http://dali.shuidangran.top/Article/details/gt2yhngdwmz.html

#ifndef X_H
来源：http://dali.gzhubu.top/Article/details/gt2jtearspo.html

#define X_H
来源：http://dali.shangyingyoupin.top/Article/details/gt2jqhataeo.html

#endif
来源：http://dali.xinyue.icu/Article/details/gt2zfubjdxx.html

[S31] C++：Hello World
来源：http://dali.fzhhl.top/Article/details/gt2ytwbscyg.html

#include <iostream>
来源：http://dali.chenzaomai.com/Article/details/gt2cheuighy.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.0kj1m.cn/Article/details/gt2bxiwmihr.html

[S32] C++：字符串
来源：http://dali.andypj.xyz/Article/details/gt2cgnwuyyw.html

std::string s = "hi";  s += "!";
来源：http://dali.xziqi.cn/Article/details/gt2rjfbiepu.html

[S33] C++：vector 增删
来源：http://dali.gotoacloud.top/Article/details/gt2ykmbosjy.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.jlsjyb.cn/Article/details/gt2lruqklde.html

[S34] C++：遍历 vector
来源：http://dali.daria6918.cn/Article/details/gt2vquuuovh.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.xylfe.cn/Article/details/gt2rolkehms.html

[S35] C++：map
来源：http://dali.yuxming.cn/Article/details/gt2ipqzsgue.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yuxming.cn/Article/details/gt2htzdeigq.html

[S36] C++：unordered_map
来源：http://dali.jinqigfzy.top/Article/details/gt2hpqzmtpx.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.ivvv.top/Article/details/gt2wmqwhzrq.html

[S37] C++：set
来源：http://dali.vqdsnc.cn/Article/details/gt2zwsrladr.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ovxiibpb.html

[S38] C++：排序
来源：http://dali.yj20258888.top/Article/details/gt2zlfsratu.html

std::sort(v.begin(), v.end());
来源：http://dali.pengpengdd.cyou/Article/details/gt2ntjwdume.html

[S39] C++：自定义比较器排序
来源：http://dali.ehwqpu.com/Article/details/gt2qgpxsyll.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.yanxiufei.cn/Article/details/gt2rkknenro.html

[S40] C++：查找元素
来源：http://dali.yueranfly.top/Article/details/gt2mumxuycx.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.tianlin.xyz/Article/details/gt2rdtolhkr.html

[S41] C++：类与构造函数
来源：http://dali.sxryk.cn/Article/details/gt2cvuxyuqx.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.jqgufenzy.top/Article/details/gt2chwhaoyl.html

[S42] C++：继承与虚函数
来源：http://dali.jiagoushi.top/Article/details/gt2gztngbaa.html

class B : public Base { public: void f() override {} };
来源：http://dali.andypj.xyz/Article/details/gt2eugomoel.html

[S43] C++：智能指针
来源：http://dali.tianlin.xyz/Article/details/gt2rjhpvhzv.html

auto p = std::make_unique<int>(5);
来源：http://dali.yanxiufei.cn/Article/details/gt2qocnhqmx.html

[S44] C++：引用传参
来源：http://dali.c1oappe.top/Article/details/gt2uidgakrc.html

void inc(int &x) { ++x; }
来源：http://dali.andypj.xyz/Article/details/gt2ysjtnhor.html

[S45] C++：lambda
来源：http://dali.hammf.cn/Article/details/gt2qrflhkep.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.yvedp.cn/Article/details/gt2biectbbb.html

[S46] C++：函数模板
来源：http://dali.ivvv.top/Article/details/gt2lmatnatq.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.yonumen.top/Article/details/gt2vfrxtuhl.html

[S47] C++：结构化绑定遍历
来源：http://dali.tianlin.xyz/Article/details/gt2vczuxard.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhengqikj.top/Article/details/gt2hoixzbff.html

[S48] C++：逐行读文件
来源：http://dali.wangshuangyany.cn/Article/details/gt2ualgfttt.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.ybcxt.top/Article/details/gt2cbiughje.html

while (std::getline(in, line)) { }
来源：http://dali.hysaishi.cn/Article/details/gt2kbdqqomz.html

[S49] C++：写文件
来源：http://dali.nanxinkj.top/Article/details/gt2qkdjwpag.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.bjfxy.top/Article/details/gt2hnyietfr.html

[S50] C++：格式化数字
来源：http://dali.daxiang520.top/Article/details/gt2kifnozph.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.havefunace.top/Article/details/gt2xgymxwpf.html

[S51] C++：显式类型转换
来源：http://dali.redwolf501.top/Article/details/gt2rsenhbqy.html

static_cast<double>(a) / b
来源：http://dali.zhongyouzk.top/Article/details/gt2bxwfkmlg.html

[S52] C++：const 与 noexcept
来源：http://dali.jlsjyb.cn/Article/details/gt2edrtbtmu.html

int size() const noexcept { return n_; }
来源：http://dali.xinyue.icu/Article/details/gt2cgywovhh.html

[S53] C++：移动语义
来源：http://dali.tanke756.top/Article/details/gt2oibdxhjz.html

std::vector<int> w = std::move(v);
来源：http://dali.wangshuangyany.cn/Article/details/gt2rdwiyimi.html

[S54] C++：异常处理
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2beyebvew.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.gzhubu.top/Article/details/gt2qcnzuctf.html

[S55] C++：结构化绑定
来源：http://dali.andypj.xyz/Article/details/gt2mrjpwuuo.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.shangyingyoupin.top/Article/details/gt2kwklqqju.html

[S56] C++：optional
来源：http://dali.quarkkingdee.top/Article/details/gt2jljjwchy.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.guannengcc.top/Article/details/gt2elrsetsd.html

[S57] C++：编译期常量
来源：http://dali.haohaochexian.top/Article/details/gt2fruezwcp.html

constexpr int N = 10;
来源：http://dali.hnqzz.top/Article/details/gt2rhpsbamp.html

[S58] C++：命名空间
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kjhduoyq.html

namespace ns { int f() { return 1; } }
来源：http://dali.daxiang520.top/Article/details/gt2kpmozmvn.html

[S59] C++：静态断言
来源：http://dali.yvedp.cn/Article/details/gt2xbappzdb.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uxyellkb.html

[S60] C++：遍历并删除元素
来源：http://dali.zdqjudy.top/Article/details/gt2rameghlg.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.0kj1m.cn/Article/details/gt2tpadgylu.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gt2zcmnomey.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.sufxvd.cn/Article/details/gt2ffbdpjfp.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2qjonmpjs.html

[T01] Kotlin：Hello World
来源：http://dali.sysykeji.top/Article/details/gt2jaqkdpwv.html

println("Hello")
来源：http://dali.meibo888.top/Article/details/gt2osbckwmg.html

[T02] Kotlin：变量
来源：http://dali.gzhubu.top/Article/details/gt2tbxxvycv.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.shuidangran.top/Article/details/gt2fjeozioc.html

[T03] Kotlin：字符串模板
来源：http://dali.chenzaomai.com/Article/details/gt2adtdbcsd.html

"值: $b"
来源：http://dali.jlsjyb.cn/Article/details/gt2nippnxtg.html

[T04] Kotlin：空安全
来源：http://dali.aibaodan.cn/Article/details/gt2kdsraxxs.html

val n: String? = null;  n?.length
来源：http://dali.yj20258.top/Article/details/gt2dpxcsdeq.html

[T05] Kotlin：when 表达式
来源：http://dali.cheryme.top/Article/details/gt2lxnzquqd.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.tianlin.xyz/Article/details/gt2dslorgyu.html

[T06] Kotlin：集合映射
来源：http://dali.guowangkeji.top/Article/details/gt2noohxkkq.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.quarkkingdee.top/Article/details/gt2mrjvmbzt.html

[T07] Kotlin：集合过滤
来源：http://dali.316326.xyz/Article/details/gt2xksnfehl.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.sufxvd.cn/Article/details/gt2xmsheiot.html

[T08] Kotlin：数据类
来源：http://dali.tian-w.cn/Article/details/gt2oaokbehe.html

data class User(val name: String, val age: Int)
来源：http://dali.zhongyouzk.top/Article/details/gt2awpnkmdo.html

[T09] Kotlin：扩展函数
来源：http://dali.wangshuangyany.cn/Article/details/gt2hrgiyela.html

fun String.exclaim() = this + "!"
来源：http://dali.aibaodan.cn/Article/details/gt2hrtikedo.html

[T10] Kotlin：默认参数
来源：http://dali.iojbl.cn/Article/details/gt2lexrldjn.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.gogol.net.cn/Article/details/gt2flcuxsmf.html

[T11] Kotlin：协程
来源：http://dali.zhengqikj.top/Article/details/gt2msnzvezl.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.gotoacloud.top/Article/details/gt2nzjrsbds.html

[T12] Kotlin：解构声明
来源：http://dali.zhongyouzk.top/Article/details/gt2kgtwstpw.html

val (a, b) = Pair(1, 2)
来源：http://dali.svipenyu.cn/Article/details/gt2mohjajhs.html

[T13] Kotlin：只读 Map
来源：http://dali.xuanzx.com/Article/details/gt2zyyihnmy.html

val m = mapOf("a" to 1)
来源：http://dali.chenjidiqi.icu/Article/details/gt2exqmmqzw.html

[T14] Kotlin：循环
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mwmgkviv.html

for (i in 1..10) println(i)
来源：http://dali.wangshuangyany.cn/Article/details/gt2jnczfprv.html

[T15] Kotlin：接口
来源：http://dali.andypj.xyz/Article/details/gt2acplrxff.html

interface Shape { fun area(): Double }
来源：http://dali.ybcxt.top/Article/details/gt2lprtkvzz.html

[T16] Swift：Hello World
来源：http://dali.vqdsnc.cn/Article/details/gt2wgsvzfgg.html

print("Hello")
来源：http://dali.cqqwz.cn/Article/details/gt2byenhejn.html

[T17] Swift：变量与常量
来源：http://dali.jqgufenzy.top/Article/details/gt2hxzoclwx.html

var a = 1;  let b = 2
来源：http://dali.jqgfzy.top/Article/details/gt2aoiqantv.html

[T18] Swift：字符串插值
来源：http://dali.jianghu66.top/Article/details/gt2emgvznnx.html

"值: \(b)"
来源：http://dali.yonumen.top/Article/details/gt2negidbrs.html

[T19] Swift：可选绑定
来源：http://dali.shuidangran.top/Article/details/gt2tpjeqsad.html

if let n = opt { print(n) }
来源：http://dali.chenjidiqi.icu/Article/details/gt2lkmrziwj.html

[T20] Swift：数组操作
来源：http://dali.jinqigufen.top/Article/details/gt2tseijtkz.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tvktptvs.html

[T21] Swift：遍历
来源：http://dali.cqqwz.cn/Article/details/gt2ilvtyhct.html

for x in a { print(x) }
来源：http://dali.zhengqikj.top/Article/details/gt2afvwvxxp.html

[T22] Swift：字典
来源：http://dali.yj20258888.top/Article/details/gt2keagowhx.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhixingplan.top/Article/details/gt2slamlyhu.html

[T23] Swift：函数
来源：http://dali.pengpengdd.cyou/Article/details/gt2yubwxnjp.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.xuanzx.com/Article/details/gt2pradrofr.html

[T24] Swift：闭包
来源：http://dali.jyoumei.cn/Article/details/gt2szzrhnkb.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.andypj.xyz/Article/details/gt2yrhkpnay.html

[T25] Swift：结构体
来源：http://dali.feifeiyinyue.top/Article/details/gt2ygenjeta.html

struct P { var x: Int }
来源：http://dali.guowangkeji.top/Article/details/gt2vjqknizr.html

[T26] Swift：类与重写
来源：http://dali.hfpthk.cn/Article/details/gt2booqwhmk.html

class A: Base { override func f() {} }
来源：http://dali.zhengqikj.top/Article/details/gt2dmsizrof.html

[T27] Swift：错误处理
来源：http://dali.jqgfzy.top/Article/details/gt2aqevbimr.html

do { try f() } catch { print(error) }
来源：http://dali.zhiwuduotai.top/Article/details/gt2xijradga.html

[T28] Swift：枚举
来源：http://dali.pengpengdd.cyou/Article/details/gt2czkkojpy.html

enum Color { case red, green }
来源：http://dali.ehwqpu.com/Article/details/gt2pzulqxdn.html

[T29] Swift：guard 提前返回
来源：http://dali.nwbrower.top/Article/details/gt2cqsymmff.html

guard let x = opt else { return }
来源：http://dali.zhengqikj.top/Article/details/gt2bjzzbegb.html

[T30] Swift：协议
来源：http://dali.birdmap.top/Article/details/gt2ndeuhbml.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2kifmnmed.html

[T31] Lua：Hello World
来源：http://dali.birdmap.top/Article/details/gt2euadbvnu.html

print("Hello")
来源：http://dali.cdnleiting.top/Article/details/gt2smwyqgkp.html

[T32] Lua：局部变量
来源：http://dali.zhiwuduotai.top/Article/details/gt2shwforqp.html

local a = 1
来源：http://dali.snrcjt.cn/Article/details/gt2veohzalt.html

[T33] Lua：表（数组）
来源：http://dali.hywenlv.cn/Article/details/gt2suclcmzk.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.cheryme.top/Article/details/gt2ktsifoxs.html

[T34] Lua：遍历表
来源：http://dali.yj20258888.top/Article/details/gt2jiklryfo.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.cdnleiting.top/Article/details/gt2ksnqinyd.html

[T35] Lua：字典表
来源：http://dali.316326.xyz/Article/details/gt2xcjhtihk.html

local d = { a = 1 };  d.b = 2
来源：http://dali.jinqigfzy.top/Article/details/gt2kmzejhix.html

[T36] Lua：函数
来源：http://dali.hammf.cn/Article/details/gt2zohkdhhm.html

function add(a, b) return a + b end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hjqmyeqh.html

[T37] Lua：字符串拼接
来源：http://dali.meibo888.top/Article/details/gt2ygcehjif.html

"a" .. "b"
来源：http://dali.cdnleiting.top/Article/details/gt2wmxmrhdh.html

[T38] Lua：条件
来源：http://dali.ydzc1.top/Article/details/gt2wqpbiynb.html

if x > 0 then print("正") end
来源：http://dali.ybcxt.top/Article/details/gt2iwchhdtf.html

[T39] Lua：模式匹配
来源：http://dali.jiagoushi.top/Article/details/gt2lbydlujs.html

string.find(s, "%d+")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dofzwmjx.html

[T40] Lua：元表
来源：http://dali.hywenlv.cn/Article/details/gt2tpslucht.html

setmetatable({}, { __index = base })
来源：http://dali.redwolf501.top/Article/details/gt2juqdptoa.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2bhhjmoxo.html

print "Hello\n";
来源：http://dali.ppjwa.cn/Article/details/gt2wpqoxfmn.html

[T42] Perl：变量类型
来源：http://dali.hnqzz.top/Article/details/gt2wxwbsanr.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.havefunace.top/Article/details/gt2dphdymqr.html

[T43] Perl：字符串插值
来源：http://dali.jlsjyb.cn/Article/details/gt2fcytzrno.html

"值: $a"
来源：http://dali.ehwqpu.com/Article/details/gt2jzxsdjgk.html

[T44] Perl：条件
来源：http://dali.gogol.net.cn/Article/details/gt2cholulnp.html

if ($a > 0) { print "正"; }
来源：http://dali.zhongyouzk.top/Article/details/gt2ncvewpiv.html

[T45] Perl：数组遍历
来源：http://dali.tanke756.top/Article/details/gt2pnipfazi.html

for my $x (@arr) { print $x; }
来源：http://dali.9152youxi.cn/Article/details/gt2emczmuyr.html

[T46] Perl：哈希操作
来源：http://dali.jinghuilouyu.cn/Article/details/gt2udjeukvw.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.yanxiufei.cn/Article/details/gt2pozshrub.html

[T47] Perl：正则捕获
来源：http://dali.xuetiantiany.cn/Article/details/gt2pqzzpdfp.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fknywwsu.html

[T48] Perl：正则替换
来源：http://dali.ehwqpu.com/Article/details/gt2cdkxvnrb.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2zaqkgnlm.html

[T49] Perl：函数
来源：http://dali.yvedp.cn/Article/details/gt2jmoiidvz.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.yonumen.top/Article/details/gt2solmremw.html

[T50] Perl：逐行读文件
来源：http://dali.yj202588.top/Article/details/gt2bavoymzn.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.jianghu66.top/Article/details/gt2acfmkntb.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.gzhubu.top/Article/details/gt2atwivpib.html

[T51] Scala：Hello World
来源：http://dali.nanxuanxn.top/Article/details/gt2vzocyrce.html

println("Hello")
来源：http://dali.zhiwuduotai.top/Article/details/gt2muhnbhfg.html

[T52] Scala：变量
来源：http://dali.ybcxt.top/Article/details/gt2cbrbeqqy.html

val a = 1;  var b = 2
来源：http://dali.sxryk.cn/Article/details/gt2boratdoq.html

[T53] Scala：字符串插值
来源：http://dali.yongpay.top/Article/details/gt2dsvnjdzj.html

s"值: $b"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ukcnpzub.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2rkcwtgav.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.tanke756.top/Article/details/gt2lalnsvrr.html

[T55] Scala：集合过滤
来源：http://dali.mhx1999.top/Article/details/gt2oefhzkry.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.nwbrower.top/Article/details/gt2bhnytcyf.html

[T56] Scala：样例类
来源：http://dali.jianghu66.top/Article/details/gt2ytvyeeds.html

case class User(name: String, age: Int)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2drhgrolz.html

[T57] Scala：模式匹配
来源：http://dali.shzxlz.cn/Article/details/gt2lgrsgcfp.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.shangyingyoupin.top/Article/details/gt2umbasdjd.html

[T58] Scala：函数定义
来源：http://dali.ydzc1.top/Article/details/gt2chykjmzx.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2cioxxjqc.html

[T59] Scala：循环
来源：http://dali.jqgufenzy.top/Article/details/gt2jmvtdyhx.html

for (i <- 1 to 10) println(i)
来源：http://dali.zdqjudy.top/Article/details/gt2blrzzrjp.html

[T60] Scala：折叠
来源：http://dali.bjfxy.top/Article/details/gt2zppzpwra.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.hongshengwenyu.top/Article/details/gt2uabrdalb.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2nmiyquye.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.aizwys.cn/Article/details/gt2icijcdwo.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2dygopvly.html

[U01] Py：创建虚拟环境
来源：http://dali.bjfxy.top/Article/details/gt2wsfogaqi.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.wangshuangyany.cn/Article/details/gt2dmfvuxsd.html

[U02] Py：导出 / 安装依赖
来源：http://dali.ppjwa.cn/Article/details/gt2dvxlmzxb.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.cashguo.top/Article/details/gt2bkpncvkq.html

[U03] Py：加载 .env 配置
来源：http://dali.0kj1m.cn/Article/details/gt2aukydshp.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zycfv.cn/Article/details/gt2rtkpangr.html

[U04] Py：变量调试打印
来源：http://dali.zhixingplan.top/Article/details/gt2bdgxjhbu.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhengqikj.top/Article/details/gt2vuueeqwz.html

[U05] Py：列表去重且保序
来源：http://dali.9152youxi.cn/Article/details/gt2nujcuiqr.html

list(dict.fromkeys(arr))
来源：http://dali.daxiang520.top/Article/details/gt2xhwhbhml.html

[U06] Py：合并两个字典
来源：http://dali.shuidangran.top/Article/details/gt2hycwdftf.html

{**a, **b}
来源：http://dali.sysykeji.top/Article/details/gt2zbsmkejd.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2xycwzxic.html

{v: k for k, v in d.items()}
来源：http://dali.hysaishi.cn/Article/details/gt2htyaawqc.html

[U08] Py：展平二维列表
来源：http://dali.nanxuanxn.top/Article/details/gt2iawdhazi.html

[y for x in nested for y in x]
来源：http://dali.gogol.net.cn/Article/details/gt2aaqudvlp.html

[U09] Py：字典取最大值的键
来源：http://dali.yj20258888.top/Article/details/gt2uwlgbhjj.html

max(d, key=d.get)
来源：http://dali.ppjwa.cn/Article/details/gt2jtymtikx.html

[U10] Py：按值排序字典
来源：http://dali.jqgufenzy.top/Article/details/gt2ektmeqhm.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhiwuduotai.top/Article/details/gt2yfeljunf.html

[U11] Py：生成器表达式
来源：http://dali.gzhubu.top/Article/details/gt2qrqczlqr.html

(x * 2 for x in arr)
来源：http://dali.cucudq.cn/Article/details/gt2cdbbwwrw.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.cheryme.top/Article/details/gt2nzrtbzfc.html

Counter(arr).most_common(3)
来源：http://dali.sweek.top/Article/details/gt2qkzurfpr.html

[U13] Py：固定长度队列
来源：http://dali.zhixingplan.top/Article/details/gt2hsqjcbaa.html

deque(maxlen=10)
来源：http://dali.hammf.cn/Article/details/gt2mgwforsq.html

[U14] Py：分组收集到列表
来源：http://dali.hnxiangtu.top/Article/details/gt2kfhuqvyy.html

defaultdict(list)
来源：http://dali.aizwys.cn/Article/details/gt2znmkgmvc.html

[U15] Py：高精度计时
来源：http://dali.yvedp.cn/Article/details/gt2lursqhdq.html

t = time.perf_counter()
来源：http://dali.jqgfzy.top/Article/details/gt2oflbkefy.html

[U16] Py：命令行参数解析
来源：http://dali.zhixingplan.top/Article/details/gt2udayuorn.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.jyoumei.cn/Article/details/gt2qupyccvf.html

[U17] Py：初始化日志
来源：http://dali.jiagoushi.top/Article/details/gt2djlctacg.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.hongshengwenyu.top/Article/details/gt2uddnkkgc.html

[U18] Py：预编译正则
来源：http://dali.dashuyun.cn/Article/details/gt2kxsjjpme.html

pat = re.compile(r"\d+")
来源：http://dali.chenzaomai.com/Article/details/gt2mktzhthz.html

[U19] Py：正则替换带回调
来源：http://dali.cheryme.top/Article/details/gt2wbjxbqlt.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.ehwqpu.com/Article/details/gt2rlxitwsw.html

[U20] Py：缓存函数结果
来源：http://dali.cheryme.top/Article/details/gt2ztamlazs.html

@functools.lru_cache(maxsize=None)
来源：http://dali.jinqigfzy.top/Article/details/gt2dqexvodz.html

[U21] Py：自定义上下文管理器
来源：http://dali.tianlin.xyz/Article/details/gt2jxdcpmzv.html

@contextlib.contextmanager
来源：http://dali.quarkkingdee.top/Article/details/gt2kurkppcp.html

[U22] Py：矩阵转置
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vyouapgs.html

list(zip(*m))
来源：http://dali.hammf.cn/Article/details/gt2pegvpipc.html

[U23] Py：分块读取大文件
来源：http://dali.zhixingplan.top/Article/details/gt2leihwvnz.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.hnqzz.top/Article/details/gt2eysmdxdv.html

[U24] Py：路径操作
来源：http://dali.jinqigfzy.top/Article/details/gt2yitovjyq.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.guowangkeji.top/Article/details/gt2whqglvke.html

[U25] Py：CSV 按字典读
来源：http://dali.bjfxy.top/Article/details/gt2pfrqyqjf.html

csv.DictReader(f)
来源：http://dali.guowangkeji.top/Article/details/gt2xukbviye.html

[U26] Py：并发下载
来源：http://dali.xuanzx.com/Article/details/gt2dvhtjcso.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.xylfe.cn/Article/details/gt2poujixev.html

[U27] Py：异步 HTTP
来源：http://dali.xylfe.cn/Article/details/gt2mdeykoma.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.feifeiyinyue.top/Article/details/gt2kjragruk.html

[U28] Py：类型别名
来源：http://dali.daria6918.cn/Article/details/gt2duzxpvfu.html

UserId = int
来源：http://dali.gzhubu.top/Article/details/gt2cscylchi.html

[U29] Py：属性校验
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xbiektbb.html

@property 与 @x.setter 配合
来源：http://dali.dianchejie.cn/Article/details/gt2tarxaehk.html

[U30] Py：数据类
来源：http://dali.guowangkeji.top/Article/details/gt2zkrbuftn.html

@dataclass(slots=True)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mpixogfl.html

[U31] Py：单测
来源：http://dali.xuanzx.com/Article/details/gt2qcirirfy.html

python -m pytest -q
来源：http://dali.meibo888.top/Article/details/gt2skpfstxx.html

[U32] Py：代码格式化
来源：http://dali.zhongyouzk.top/Article/details/gt2gogdufoo.html

ruff format . && ruff check --fix .
来源：http://dali.sysykeji.top/Article/details/gt2gjqhfllw.html

[U33] Py：打包发布
来源：http://dali.zhoulong.xyz/Article/details/gt2nqnvvzqq.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.jianghu66.top/Article/details/gt2dqibsasy.html

[U34] Py：判断编码
来源：http://dali.daria6918.cn/Article/details/gt2meuzdkmm.html

chardet.detect(raw)
来源：http://dali.fzhhl.top/Article/details/gt2mobdslmr.html

[U35] Py：发送邮件
来源：http://dali.zhongyouzk.top/Article/details/gt2sevzlufv.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.tianlin.xyz/Article/details/gt2kejsbpds.html

[U36] Py：定时任务
来源：http://dali.xziqi.cn/Article/details/gt2uvzpfxnq.html

schedule.every(10).minutes.do(job)
来源：http://dali.chenjidiqi.icu/Article/details/gt2rwxxbsuj.html

[U37] Py：读写 Excel
来源：http://dali.pycfn.com/Article/details/gt2lufdkzum.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.bjfxy.top/Article/details/gt2qgmybito.html

[U38] Py：获取脚本所在目录
来源：http://dali.gotoacloud.top/Article/details/gt2zartulff.html

Path(__file__).resolve().parent
来源：http://dali.gaohongyu789.top/Article/details/gt2cggvoybq.html


<!-- 参考信息 -->