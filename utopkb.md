代发 wailian999

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhoulong.xyz/Article/details/gtdkxvroki.html

[S13] C：宏定义
来源：http://dali.fzhhl.top/Article/details/gtxpwmqchy.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.hammf.cn/Article/details/gtxqupwois.html

[S14] C：枚举
来源：http://dali.daxiang520.top/Article/details/gtaxsnkgxe.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.cqqwz.cn/Article/details/gtjzdccenr.html

[S15] C：类型转换
来源：http://dali.shangyingyoupin.top/Article/details/gtdiiwqcvg.html

(double) a / b
来源：http://dali.ywan-chungtsiang.top/Article/details/gteutxkkdp.html

[S16] C：位操作置位
来源：http://dali.c1oappe.top/Article/details/gtrlomkmvc.html

x |= (1 << 3);
来源：http://dali.sweek.top/Article/details/gtmdzvwype.html

[S17] C：安全拼接字符串
来源：http://dali.daxiang520.top/Article/details/gtprjzqcpp.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.yvedp.cn/Article/details/gtqloaxutw.html

[S18] C：命令行参数
来源：http://dali.tian-w.cn/Article/details/gtibvkbxag.html

int main(int argc, char **argv)
来源：http://dali.shuidangran.top/Article/details/gtwflwqneu.html

[S19] C：快速排序
来源：http://dali.zhengqikj.top/Article/details/gtepnexecb.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.meibo888.top/Article/details/gtfimxcmnc.html

[S20] C：二分查找
来源：http://dali.cheryme.top/Article/details/gtjvwtmvxt.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.yuxming.cn/Article/details/gtfcjbhqgd.html

[S21] C：字符类别判断
来源：http://dali.ybcxt.top/Article/details/gtaexqvcgx.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhiwuduotai.top/Article/details/gtjpkffrnr.html

[S22] C：字符串转数字
来源：http://dali.jianghu66.top/Article/details/gtjruxbplu.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.sysykeji.top/Article/details/gtpjqisxqi.html

[S23] C：随机数
来源：http://dali.fzhhl.top/Article/details/gtcwsvqhcl.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.tanke756.top/Article/details/gtjyvyfwfq.html

[S24] C：获取本地时间
来源：http://dali.quarkkingdee.top/Article/details/gtrsprybku.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.cqqwz.cn/Article/details/gtiqlysxru.html

[S25] C：内存拷贝
来源：http://dali.cheryme.top/Article/details/gtfjmfbbou.html

memcpy(dst, src, n);
来源：http://dali.jinqigufen.top/Article/details/gtnyeagnsz.html

[S26] C：内存清零
来源：http://dali.meibo888.top/Article/details/gtckkgkwwd.html

memset(a, 0, sizeof a);
来源：http://dali.fengsongda.top/Article/details/gtlcijsyvb.html

[S27] C：定义常量
来源：http://dali.zhoulong.xyz/Article/details/gtkijrbjtd.html

const double PI = 3.14159;
来源：http://dali.pycfn.com/Article/details/gtkcmlnymn.html

[S28] C：静态变量
来源：http://dali.sxryk.cn/Article/details/gtnckxodil.html

static int counter = 0;
来源：http://dali.0kj1m.cn/Article/details/gtobtsgspq.html

[S29] C：变参函数
来源：http://dali.jinqigufen.top/Article/details/gtmngtjgxe.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.yuxming.cn/Article/details/gtpcubzzxi.html

[S30] C：头文件保护
来源：http://dali.cheryme.top/Article/details/gtivlgnuey.html

#ifndef X_H
来源：http://dali.feifeiyinyue.top/Article/details/gtowkoekrl.html

#define X_H
来源：http://dali.gzhubu.top/Article/details/gtemgbbrdu.html

#endif
来源：http://dali.jinghuilouyu.cn/Article/details/gtasisynpc.html

[S31] C++：Hello World
来源：http://dali.zhongyouzk.top/Article/details/gtaypmoupi.html

#include <iostream>
来源：http://dali.zdqjudy.top/Article/details/gtrjouojzw.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.wangdashe.top/Article/details/gtqzmaajpd.html

[S32] C++：字符串
来源：http://dali.iojbl.cn/Article/details/gtnmyrdvok.html

std::string s = "hi";  s += "!";
来源：http://dali.yuanzhike.top/Article/details/gtoilhvbfj.html

[S33] C++：vector 增删
来源：http://dali.gaohongyu789.top/Article/details/gtihmohegy.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.yvedp.cn/Article/details/gtfoywkidz.html

[S34] C++：遍历 vector
来源：http://dali.smart0.xyz/Article/details/gtnrrwdsam.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.jinqigufen.top/Article/details/gtktkgblru.html

[S35] C++：map
来源：http://dali.jyoumei.cn/Article/details/gtjclemtdn.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.nanxinkj.top/Article/details/gtvjbegums.html

[S36] C++：unordered_map
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgimvgdyg.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.xuanzx.com/Article/details/gtmsrislle.html

[S37] C++：set
来源：http://dali.shanyushiyangtech.top/Article/details/gtufwvyxza.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtooytqipr.html

[S38] C++：排序
来源：http://dali.yj20258.top/Article/details/gtlhusbdzm.html

std::sort(v.begin(), v.end());
来源：http://dali.nwbrower.top/Article/details/gtsjontllk.html

[S39] C++：自定义比较器排序
来源：http://dali.jlsjyb.cn/Article/details/gtxjwetitf.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.chenlongwang.top/Article/details/gtplamdema.html

[S40] C++：查找元素
来源：http://dali.hfpthk.cn/Article/details/gtynaliefa.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gtbegbgaug.html

[S41] C++：类与构造函数
来源：http://dali.zhengqikj.top/Article/details/gticmfccuu.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.andypj.xyz/Article/details/gtcvcvqdzg.html

[S42] C++：继承与虚函数
来源：http://dali.9152youxi.cn/Article/details/gtzytlscwu.html

class B : public Base { public: void f() override {} };
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkixnazkm.html

[S43] C++：智能指针
来源：http://dali.yj20258.top/Article/details/gtdccqmnci.html

auto p = std::make_unique<int>(5);
来源：http://dali.yonumen.top/Article/details/gtypzohqss.html

[S44] C++：引用传参
来源：http://dali.gaohongyu789.top/Article/details/gtxetwluff.html

void inc(int &x) { ++x; }
来源：http://dali.sweek.top/Article/details/gtblppypiw.html

[S45] C++：lambda
来源：http://dali.aibaodan.cn/Article/details/gtpuhaauys.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.0kj1m.cn/Article/details/gtdgsrfkzr.html

[S46] C++：函数模板
来源：http://dali.smart0.xyz/Article/details/gtwzpiihml.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.redwolf501.top/Article/details/gtprbkwcwi.html

[S47] C++：结构化绑定遍历
来源：http://dali.0kj1m.cn/Article/details/gtweqvxpva.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuaseccva.html

[S48] C++：逐行读文件
来源：http://dali.gaohongyu789.top/Article/details/gtvckkhecd.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.cheryme.top/Article/details/gtdqwtrzhm.html

while (std::getline(in, line)) { }
来源：http://dali.redwolf501.top/Article/details/gtuexnanig.html

[S49] C++：写文件
来源：http://dali.andypj.xyz/Article/details/gtluxazmmv.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.yueranfly.top/Article/details/gtffmqficy.html

[S50] C++：格式化数字
来源：http://dali.guowangkeji.top/Article/details/gtkozhzdmf.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.pengpengdd.cyou/Article/details/gtabnkgott.html

[S51] C++：显式类型转换
来源：http://dali.svipenyu.cn/Article/details/gtdwnspeyy.html

static_cast<double>(a) / b
来源：http://dali.nwbrower.top/Article/details/gtckkphvqm.html

[S52] C++：const 与 noexcept
来源：http://dali.shuidangran.top/Article/details/gtfmvkeftu.html

int size() const noexcept { return n_; }
来源：http://dali.svipenyu.cn/Article/details/gtmkvnnsoi.html

[S53] C++：移动语义
来源：http://dali.shzxlz.cn/Article/details/gtlvfnzbya.html

std::vector<int> w = std::move(v);
来源：http://dali.kuanghao11.cn/Article/details/gtgfovwpsq.html

[S54] C++：异常处理
来源：http://dali.wangdashe.top/Article/details/gttxkreghg.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.jianghu66.top/Article/details/gtxuxmzxex.html

[S55] C++：结构化绑定
来源：http://dali.pycfn.com/Article/details/gtcsbidngz.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.chenlongwang.top/Article/details/gtsksgfsmi.html

[S56] C++：optional
来源：http://dali.ywan-chungtsiang.top/Article/details/gtimpqepyx.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.xylfe.cn/Article/details/gtycgwlmwa.html

[S57] C++：编译期常量
来源：http://dali.dianchejie.cn/Article/details/gtjuyhbfzk.html

constexpr int N = 10;
来源：http://dali.tianlin.xyz/Article/details/gtrkshuhou.html

[S58] C++：命名空间
来源：http://dali.redwolf501.top/Article/details/gtmmyablyc.html

namespace ns { int f() { return 1; } }
来源：http://dali.9152youxi.cn/Article/details/gtsgsprupf.html

[S59] C++：静态断言
来源：http://dali.ppjwa.cn/Article/details/gtiomqzohh.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gtyqkyatvz.html

[S60] C++：遍历并删除元素
来源：http://dali.hammf.cn/Article/details/gtllohrtkh.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.gzhubu.top/Article/details/gtmufwbkse.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtgmistigj.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yongpay.top/Article/details/gtywixwagf.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gthoswmezj.html

[T01] Kotlin：Hello World
来源：http://dali.shangyingyoupin.top/Article/details/gtmiergswj.html

println("Hello")
来源：http://dali.316326.xyz/Article/details/gtyrjezsml.html

[T02] Kotlin：变量
来源：http://dali.guowangkeji.top/Article/details/gtmvqctjro.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdsbboucg.html

[T03] Kotlin：字符串模板
来源：http://dali.xziqi.cn/Article/details/gtyfcaxyib.html

"值: $b"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpihekljt.html

[T04] Kotlin：空安全
来源：http://dali.shangyingyoupin.top/Article/details/gtssqjrtwb.html

val n: String? = null;  n?.length
来源：http://dali.wangdashe.top/Article/details/gttukafwff.html

[T05] Kotlin：when 表达式
来源：http://dali.yvedp.cn/Article/details/gtakhptdwv.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.cdnleiting.top/Article/details/gtmqkznyhh.html

[T06] Kotlin：集合映射
来源：http://dali.jinghuilouyu.cn/Article/details/gtabyivhec.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.feifeiyinyue.top/Article/details/gtfkvltirb.html

[T07] Kotlin：集合过滤
来源：http://dali.birdmap.top/Article/details/gtwwqpdhle.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.ivvv.top/Article/details/gtafjhjapb.html

[T08] Kotlin：数据类
来源：http://dali.sweek.top/Article/details/gtbakbpjeu.html

data class User(val name: String, val age: Int)
来源：http://dali.shuidangran.top/Article/details/gtfjpvfeyl.html

[T09] Kotlin：扩展函数
来源：http://dali.zycfv.cn/Article/details/gtrkvfniqq.html

fun String.exclaim() = this + "!"
来源：http://dali.jianghu66.top/Article/details/gthtexyblv.html

[T10] Kotlin：默认参数
来源：http://dali.yj202588.top/Article/details/gtpnwawyjv.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.ybcxt.top/Article/details/gtbjalrory.html

[T11] Kotlin：协程
来源：http://dali.nanxuanxn.top/Article/details/gtfnazqgnl.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.ppjwa.cn/Article/details/gtovxkailg.html

[T12] Kotlin：解构声明
来源：http://dali.gaohongyu789.top/Article/details/gtdkroxztd.html

val (a, b) = Pair(1, 2)
来源：http://dali.cashguo.top/Article/details/gtsxzowbzb.html

[T13] Kotlin：只读 Map
来源：http://dali.jinqigfzy.top/Article/details/gtleslmwxi.html

val m = mapOf("a" to 1)
来源：http://dali.yonumen.top/Article/details/gtlqobzhhs.html

[T14] Kotlin：循环
来源：http://dali.yangfankeji.com/Article/details/gtxazknztp.html

for (i in 1..10) println(i)
来源：http://dali.shzxlz.cn/Article/details/gtnlduvqgd.html

[T15] Kotlin：接口
来源：http://dali.dianchejie.cn/Article/details/gtezzyychq.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gtjykhvfwu.html

[T16] Swift：Hello World
来源：http://dali.dashuyun.cn/Article/details/gtjtkxwbpp.html

print("Hello")
来源：http://dali.gzhubu.top/Article/details/gtpuojbsdr.html

[T17] Swift：变量与常量
来源：http://dali.quarkkingdee.top/Article/details/gttrdfydio.html

var a = 1;  let b = 2
来源：http://dali.kuanghao11.cn/Article/details/gtcyecedpt.html

[T18] Swift：字符串插值
来源：http://dali.jinghuilouyu.cn/Article/details/gtdiznehaw.html

"值: \(b)"
来源：http://dali.jianghu66.top/Article/details/gtmtqupwcy.html

[T19] Swift：可选绑定
来源：http://dali.jinghuilouyu.cn/Article/details/gtigolzrcn.html

if let n = opt { print(n) }
来源：http://dali.nanxinkj.top/Article/details/gtltehkfjk.html

[T20] Swift：数组操作
来源：http://dali.birdmap.top/Article/details/gtbbztrwwm.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.shzxlz.cn/Article/details/gtkptmdetj.html

[T21] Swift：遍历
来源：http://dali.ivvv.top/Article/details/gtnxrcwjpg.html

for x in a { print(x) }
来源：http://dali.wangshuangyany.cn/Article/details/gtvvajqegy.html

[T22] Swift：字典
来源：http://dali.fengsongda.top/Article/details/gtzgznnyvs.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.hfpthk.cn/Article/details/gtuwppenln.html

[T23] Swift：函数
来源：http://dali.0kj1m.cn/Article/details/gtiaguwxvy.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.vqdsnc.cn/Article/details/gtgtgjgysy.html

[T24] Swift：闭包
来源：http://dali.wangshuangyany.cn/Article/details/gtnlzmksgw.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.yuanzhike.top/Article/details/gtoutvpcxs.html

[T25] Swift：结构体
来源：http://dali.nanxinkj.top/Article/details/gtqhutswsa.html

struct P { var x: Int }
来源：http://dali.jqgufenzy.top/Article/details/gtfwglxbdt.html

[T26] Swift：类与重写
来源：http://dali.zycfv.cn/Article/details/gtkuojcydd.html

class A: Base { override func f() {} }
来源：http://dali.mhx1999.top/Article/details/gtxjkicntb.html

[T27] Swift：错误处理
来源：http://dali.jqgufenzy.top/Article/details/gtkrvhtibu.html

do { try f() } catch { print(error) }
来源：http://dali.c1oappe.top/Article/details/gtvfcoqozx.html

[T28] Swift：枚举
来源：http://dali.daxiang520.top/Article/details/gteuniofft.html

enum Color { case red, green }
来源：http://dali.aibaodan.cn/Article/details/gtlwvktyzc.html

[T29] Swift：guard 提前返回
来源：http://dali.ydzc1.top/Article/details/gtiivxcfny.html

guard let x = opt else { return }
来源：http://dali.feifeiyinyue.top/Article/details/gtdptlzmfu.html

[T30] Swift：协议
来源：http://dali.ehwqpu.com/Article/details/gtqgaiqpkq.html

protocol Shape { func area() -> Double }
来源：http://dali.xziqi.cn/Article/details/gtsfpmkrdt.html

[T31] Lua：Hello World
来源：http://dali.zycfv.cn/Article/details/gtqwhuiyaq.html

print("Hello")
来源：http://dali.jlsjyb.cn/Article/details/gthvhwhdhl.html

[T32] Lua：局部变量
来源：http://dali.fzhhl.top/Article/details/gtuhudpvjb.html

local a = 1
来源：http://dali.daria6918.cn/Article/details/gtmcdqenxf.html

[T33] Lua：表（数组）
来源：http://dali.shangyingyoupin.top/Article/details/gttedqwxov.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.sysykeji.top/Article/details/gtoujknfpn.html

[T34] Lua：遍历表
来源：http://dali.jiagoushi.top/Article/details/gtlpdbecfa.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhiwuduotai.top/Article/details/gtzrxjzxxi.html

[T35] Lua：字典表
来源：http://dali.yuanzhike.top/Article/details/gtzerovikm.html

local d = { a = 1 };  d.b = 2
来源：http://dali.kuanghao11.cn/Article/details/gtybdhqjvx.html

[T36] Lua：函数
来源：http://dali.yongpay.top/Article/details/gtefsslmuk.html

function add(a, b) return a + b end
来源：http://dali.chenlongwang.top/Article/details/gtflmjwuwa.html

[T37] Lua：字符串拼接
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvmgtcwgd.html

"a" .. "b"
来源：http://dali.redwolf501.top/Article/details/gtjnmwrwhr.html

[T38] Lua：条件
来源：http://dali.shzxlz.cn/Article/details/gthkbjfyac.html

if x > 0 then print("正") end
来源：http://dali.c1oappe.top/Article/details/gtbvrkjdun.html

[T39] Lua：模式匹配
来源：http://dali.pengpengdd.cyou/Article/details/gtymlzzing.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gtmegrhrjm.html

[T40] Lua：元表
来源：http://dali.shangyingyoupin.top/Article/details/gtmdwkbnmu.html

setmetatable({}, { __index = base })
来源：http://dali.zdqjudy.top/Article/details/gtgqfhlqca.html

[T41] Perl：Hello World
来源：http://dali.0kj1m.cn/Article/details/gtrzoazmpp.html

print "Hello\n";
来源：http://dali.dianchejie.cn/Article/details/gtkxubasfw.html

[T42] Perl：变量类型
来源：http://dali.dianchejie.cn/Article/details/gtucqluatr.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.andypj.xyz/Article/details/gtxxfmwosa.html

[T43] Perl：字符串插值
来源：http://dali.zhiwuduotai.top/Article/details/gtlyztptjl.html

"值: $a"
来源：http://dali.ydzc1.top/Article/details/gtibmntvkw.html

[T44] Perl：条件
来源：http://dali.cheryme.top/Article/details/gteftfkxih.html

if ($a > 0) { print "正"; }
来源：http://dali.jianghu66.top/Article/details/gtwgebuzny.html

[T45] Perl：数组遍历
来源：http://dali.kuanghao11.cn/Article/details/gtmtjmmeiw.html

for my $x (@arr) { print $x; }
来源：http://dali.redwolf501.top/Article/details/gttulcfpuj.html

[T46] Perl：哈希操作
来源：http://dali.316326.xyz/Article/details/gtosuypaso.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.guannengcc.top/Article/details/gtkcgezuie.html

[T47] Perl：正则捕获
来源：http://dali.cqqwz.cn/Article/details/gtrjoqlall.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.pycfn.com/Article/details/gtuvmqozye.html

[T48] Perl：正则替换
来源：http://dali.haohaochexian.top/Article/details/gteonacrio.html

$s =~ s/old/new/g;
来源：http://dali.sxryk.cn/Article/details/gtzfyoztsl.html

[T49] Perl：函数
来源：http://dali.ehwqpu.com/Article/details/gtwhvsqqts.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.tianlin.xyz/Article/details/gtybglpbvn.html

[T50] Perl：逐行读文件
来源：http://dali.nwbrower.top/Article/details/gtsgfizkgc.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.sweek.top/Article/details/gtbsmdhypt.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.xuanzx.com/Article/details/gthjdmtppd.html

[T51] Scala：Hello World
来源：http://dali.daxiang520.top/Article/details/gtjnuefcjd.html

println("Hello")
来源：http://dali.svipenyu.cn/Article/details/gtctiknzpm.html

[T52] Scala：变量
来源：http://dali.jiagoushi.top/Article/details/gtkhhlxrdi.html

val a = 1;  var b = 2
来源：http://dali.xuanzx.com/Article/details/gtzhwjorpk.html

[T53] Scala：字符串插值
来源：http://dali.fengsongda.top/Article/details/gtaikkexte.html

s"值: $b"
来源：http://dali.hysaishi.cn/Article/details/gtuhqnzjqt.html

[T54] Scala：集合映射
来源：http://dali.aizwys.cn/Article/details/gtxmwzbwzf.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.jqgufenzy.top/Article/details/gtooirioxf.html

[T55] Scala：集合过滤
来源：http://dali.kuanghao11.cn/Article/details/gtgecjxlvp.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.xinyue.icu/Article/details/gthounqmad.html

[T56] Scala：样例类
来源：http://dali.pengpengdd.cyou/Article/details/gthprqbrel.html

case class User(name: String, age: Int)
来源：http://dali.fengsongda.top/Article/details/gtmetknpjt.html

[T57] Scala：模式匹配
来源：http://dali.zhixingplan.top/Article/details/gtxwailpdc.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhongyouzk.top/Article/details/gttbtlhsgy.html

[T58] Scala：函数定义
来源：http://dali.yuxming.cn/Article/details/gtiqfsqfih.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.gaohongyu789.top/Article/details/gtjslzczxg.html

[T59] Scala：循环
来源：http://dali.wangshuangyany.cn/Article/details/gtkcvktkxj.html

for (i <- 1 to 10) println(i)
来源：http://dali.daria6918.cn/Article/details/gtexxxrmua.html

[T60] Scala：折叠
来源：http://dali.xylfe.cn/Article/details/gtakkpgxzn.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.pengpengdd.cyou/Article/details/gtpdmkzhbc.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtnlvbfqwl.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.nwbrower.top/Article/details/gthiyhrzgh.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gthdlgevhq.html

[U01] Py：创建虚拟环境
来源：http://dali.hnqzz.top/Article/details/gtybafbwqw.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.gaohongyu789.top/Article/details/gtcpmrydfi.html

[U02] Py：导出 / 安装依赖
来源：http://dali.wangshuangyany.cn/Article/details/gtteudatuh.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.daxiang520.top/Article/details/gtpgzempjl.html

[U03] Py：加载 .env 配置
来源：http://dali.chenlongwang.top/Article/details/gtmfxpxijr.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.havefunace.top/Article/details/gttctyceau.html

[U04] Py：变量调试打印
来源：http://dali.zycfv.cn/Article/details/gtfvtidoqb.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvsouggab.html

[U05] Py：列表去重且保序
来源：http://dali.yanxiufei.cn/Article/details/gtceqrqypg.html

list(dict.fromkeys(arr))
来源：http://dali.sweek.top/Article/details/gtxwgbsfng.html

[U06] Py：合并两个字典
来源：http://dali.fengsongda.top/Article/details/gtuxagicyh.html

{**a, **b}
来源：http://dali.wangshuangyany.cn/Article/details/gtgrdolumc.html

[U07] Py：反转字典键值
来源：http://dali.sufxvd.cn/Article/details/gterkxyhtj.html

{v: k for k, v in d.items()}
来源：http://dali.sweek.top/Article/details/gtpmbcywed.html

[U08] Py：展平二维列表
来源：http://dali.tanke756.top/Article/details/gtrvnhowiw.html

[y for x in nested for y in x]
来源：http://dali.shangyingyoupin.top/Article/details/gtnkgnrypg.html

[U09] Py：字典取最大值的键
来源：http://dali.wangdashe.top/Article/details/gtpuihoiup.html

max(d, key=d.get)
来源：http://dali.jlsjyb.cn/Article/details/gtkfeerosm.html

[U10] Py：按值排序字典
来源：http://dali.yongpay.top/Article/details/gtobgwaihi.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.chenzaomai.com/Article/details/gtvzqlnysy.html

[U11] Py：生成器表达式
来源：http://dali.mhx1999.top/Article/details/gtmpidssqr.html

(x * 2 for x in arr)
来源：http://dali.xziqi.cn/Article/details/gtdyqvrcoq.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.meibo888.top/Article/details/gtyldhruje.html

Counter(arr).most_common(3)
来源：http://dali.ivvv.top/Article/details/gtojmsccij.html

[U13] Py：固定长度队列
来源：http://dali.feifeiyinyue.top/Article/details/gtkwgdvwbq.html

deque(maxlen=10)
来源：http://dali.yj20258888.top/Article/details/gtukbrnizs.html

[U14] Py：分组收集到列表
来源：http://dali.cdnleiting.top/Article/details/gtrmzjgxnv.html

defaultdict(list)
来源：http://dali.yueranfly.top/Article/details/gtffgkvtbl.html

[U15] Py：高精度计时
来源：http://dali.0kj1m.cn/Article/details/gtguobfdkx.html

t = time.perf_counter()
来源：http://dali.shzxlz.cn/Article/details/gtquuldelz.html

[U16] Py：命令行参数解析
来源：http://dali.yvedp.cn/Article/details/gtyxkwoovh.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.yj20258888.top/Article/details/gtlpomcbtl.html

[U17] Py：初始化日志
来源：http://dali.xziqi.cn/Article/details/gtyfuewimo.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.jlsjyb.cn/Article/details/gtcyhpukjo.html

[U18] Py：预编译正则
来源：http://dali.yj202588.top/Article/details/gtwsieupmh.html

pat = re.compile(r"\d+")
来源：http://dali.316326.xyz/Article/details/gtvqzkalbg.html

[U19] Py：正则替换带回调
来源：http://dali.aizwys.cn/Article/details/gtnhfdctlr.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.guannengcc.top/Article/details/gtdkivtuyx.html

[U20] Py：缓存函数结果
来源：http://dali.zhengqikj.top/Article/details/gtimqsbtbk.html

@functools.lru_cache(maxsize=None)
来源：http://dali.shanyushiyangtech.top/Article/details/gtdtfdxqmo.html

[U21] Py：自定义上下文管理器
来源：http://dali.yueranfly.top/Article/details/gtxowbuqcp.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gtdazawlio.html

[U22] Py：矩阵转置
来源：http://dali.jiagoushi.top/Article/details/gtzxbwtdtj.html

list(zip(*m))
来源：http://dali.ydzc1.top/Article/details/gtxgccqqgg.html

[U23] Py：分块读取大文件
来源：http://dali.shangyingyoupin.top/Article/details/gtaqggztki.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.chenlongwang.top/Article/details/gtcvpkalrq.html

[U24] Py：路径操作
来源：http://dali.chenlongwang.top/Article/details/gtpdtpkpxc.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.gzhubu.top/Article/details/gtcwahruet.html

[U25] Py：CSV 按字典读
来源：http://dali.yanxiufei.cn/Article/details/gtomipayym.html

csv.DictReader(f)
来源：http://dali.shuidangran.top/Article/details/gteslptwwg.html

[U26] Py：并发下载
来源：http://dali.daxiang520.top/Article/details/gtkdhjgswv.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.daxiang520.top/Article/details/gtcxwsdnxh.html

[U27] Py：异步 HTTP
来源：http://dali.aizwys.cn/Article/details/gtzetinakj.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.quarkkingdee.top/Article/details/gtohtcsxxy.html

[U28] Py：类型别名
来源：http://dali.shangyingyoupin.top/Article/details/gtbeytwxaf.html

UserId = int
来源：http://dali.jinqigufen.top/Article/details/gtlazkksmt.html

[U29] Py：属性校验
来源：http://dali.ydzc1.top/Article/details/gtianntqqn.html

@property 与 @x.setter 配合
来源：http://dali.bjfxy.top/Article/details/gtihhwlvdj.html

[U30] Py：数据类
来源：http://dali.dashuyun.cn/Article/details/gtbjylzqdb.html

@dataclass(slots=True)
来源：http://dali.redwolf501.top/Article/details/gtlochlpxe.html

[U31] Py：单测
来源：http://dali.nanxuanxn.top/Article/details/gtztetaufw.html

python -m pytest -q
来源：http://dali.jyoumei.cn/Article/details/gtxjwlbwqd.html

[U32] Py：代码格式化
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmqtebdup.html

ruff format . && ruff check --fix .
来源：http://dali.gzhubu.top/Article/details/gtfxzzjlpj.html

[U33] Py：打包发布
来源：http://dali.ydzc1.top/Article/details/gtcxcxbkic.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.yonumen.top/Article/details/gtfhacjsxj.html

[U34] Py：判断编码
来源：http://dali.jinqigfzy.top/Article/details/gtkwddquss.html

chardet.detect(raw)
来源：http://dali.sysykeji.top/Article/details/gtjfdzrnbg.html

[U35] Py：发送邮件
来源：http://dali.aibaodan.cn/Article/details/gtbxjjouvz.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.shuidangran.top/Article/details/gtrugfqtnt.html

[U36] Py：定时任务
来源：http://dali.xuetiantiany.cn/Article/details/gtsvqhsnfq.html

schedule.every(10).minutes.do(job)
来源：http://dali.9152youxi.cn/Article/details/gtgthgnwam.html


<!-- 参考信息 -->