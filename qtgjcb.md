代发 wailian999

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.havefunace.top/Article/details/gt2rwsvxbhs.html

[S13] C：宏定义
来源：http://dali.kuanghao11.cn/Article/details/gt2ogaxdpqf.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.gzhubu.top/Article/details/gt2hwiodwsk.html

[S14] C：枚举
来源：http://dali.jqgfzy.top/Article/details/gt2puynnjiy.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.vqdsnc.cn/Article/details/gt2jwzoqoiw.html

[S15] C：类型转换
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tmlalcsf.html

(double) a / b
来源：http://dali.nanxuanxn.top/Article/details/gt2cjivxhmo.html

[S16] C：位操作置位
来源：http://dali.shanyushiyangtech.top/Article/details/gt2anxngygd.html

x |= (1 << 3);
来源：http://dali.dianchejie.cn/Article/details/gt2eslbgjlo.html

[S17] C：安全拼接字符串
来源：http://dali.nanxinkj.top/Article/details/gt2fzjypyuw.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.yvedp.cn/Article/details/gt2mjigawuv.html

[S18] C：命令行参数
来源：http://dali.birdmap.top/Article/details/gt2zqdnpfcx.html

int main(int argc, char **argv)
来源：http://dali.meibo888.top/Article/details/gt2xmjsrnlf.html

[S19] C：快速排序
来源：http://dali.yueranfly.top/Article/details/gt2rxulbuvn.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zycfv.cn/Article/details/gt2tszxfkqk.html

[S20] C：二分查找
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ywggekmr.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yxewyvnv.html

[S21] C：字符类别判断
来源：http://dali.yuxming.cn/Article/details/gt2livogytt.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.xinyue.icu/Article/details/gt2pxivsqsm.html

[S22] C：字符串转数字
来源：http://dali.chenjidiqi.icu/Article/details/gt2kpxhozuf.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.jinqigufen.top/Article/details/gt2wqogshkb.html

[S23] C：随机数
来源：http://dali.yonumen.top/Article/details/gt2ytwfmshe.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.jinqigufen.top/Article/details/gt2zorikkis.html

[S24] C：获取本地时间
来源：http://dali.yj202588.top/Article/details/gt2jmnbgvwy.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.hfpthk.cn/Article/details/gt2iyphzcvd.html

[S25] C：内存拷贝
来源：http://dali.9152youxi.cn/Article/details/gt2diwcoxjw.html

memcpy(dst, src, n);
来源：http://dali.wangdashe.top/Article/details/gt2fxqfwetj.html

[S26] C：内存清零
来源：http://dali.ivvv.top/Article/details/gt2ywjhnefp.html

memset(a, 0, sizeof a);
来源：http://dali.xuetiantiany.cn/Article/details/gt2rusinjup.html

[S27] C：定义常量
来源：http://dali.redwolf501.top/Article/details/gt2jhpuxriz.html

const double PI = 3.14159;
来源：http://dali.snrcjt.cn/Article/details/gt2iazvpeox.html

[S28] C：静态变量
来源：http://dali.0kj1m.cn/Article/details/gt2acmwtqwu.html

static int counter = 0;
来源：http://dali.cashguo.top/Article/details/gt2nooxqazx.html

[S29] C：变参函数
来源：http://dali.wangdashe.top/Article/details/gt2zrabmneq.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.hongshengwenyu.top/Article/details/gt2mbjnnqsr.html

[S30] C：头文件保护
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mdsnzzlx.html

#ifndef X_H
来源：http://dali.zhengqikj.top/Article/details/gt2wgeedpdj.html

#define X_H
来源：http://dali.cashguo.top/Article/details/gt2wlhtrsle.html

#endif
来源：http://dali.pengpengdd.cyou/Article/details/gt2gmbmakqj.html

[S31] C++：Hello World
来源：http://dali.pengpengdd.cyou/Article/details/gt2cnjwnazy.html

#include <iostream>
来源：http://dali.zhiwuduotai.top/Article/details/gt2awlimvyq.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.cqqwz.cn/Article/details/gt2kfedaxyf.html

[S32] C++：字符串
来源：http://dali.jianghu66.top/Article/details/gt2imrogxwq.html

std::string s = "hi";  s += "!";
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rtbreawo.html

[S33] C++：vector 增删
来源：http://dali.mhx1999.top/Article/details/gt2fmwcqkko.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.xziqi.cn/Article/details/gt2qeidiuon.html

[S34] C++：遍历 vector
来源：http://dali.cqqwz.cn/Article/details/gt2bbvqmmbk.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.yongpay.top/Article/details/gt2skbaszyg.html

[S35] C++：map
来源：http://dali.9152youxi.cn/Article/details/gt2flkpuqad.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yuxming.cn/Article/details/gt2fywppzxd.html

[S36] C++：unordered_map
来源：http://dali.sxryk.cn/Article/details/gt2mdwhfkgq.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.vqdsnc.cn/Article/details/gt2nycxdvfp.html

[S37] C++：set
来源：http://dali.yangfankeji.com/Article/details/gt2tgmplevc.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhengqikj.top/Article/details/gt2ebwchvej.html

[S38] C++：排序
来源：http://dali.hysaishi.cn/Article/details/gt2wccqlgzf.html

std::sort(v.begin(), v.end());
来源：http://dali.quarkkingdee.top/Article/details/gt2dhgvjdhm.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2svskpler.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhongyouzk.top/Article/details/gt2egsuaybh.html

[S40] C++：查找元素
来源：http://dali.aizwys.cn/Article/details/gt2pjleqvqu.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.chenjidiqi.icu/Article/details/gt2mcpvujff.html

[S41] C++：类与构造函数
来源：http://dali.cqqwz.cn/Article/details/gt2lgeblkqo.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.xylfe.cn/Article/details/gt2ubjimxuk.html

[S42] C++：继承与虚函数
来源：http://dali.mhx1999.top/Article/details/gt2aptweufc.html

class B : public Base { public: void f() override {} };
来源：http://dali.aibaodan.cn/Article/details/gt2cpvuwnzj.html

[S43] C++：智能指针
来源：http://dali.sxryk.cn/Article/details/gt2dqmxlobw.html

auto p = std::make_unique<int>(5);
来源：http://dali.yj202588.top/Article/details/gt2ynkdqsua.html

[S44] C++：引用传参
来源：http://dali.0kj1m.cn/Article/details/gt2nujxgvfv.html

void inc(int &x) { ++x; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kyxlrvyn.html

[S45] C++：lambda
来源：http://dali.tanke756.top/Article/details/gt2ehyzphuc.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.sysykeji.top/Article/details/gt2mxjiswia.html

[S46] C++：函数模板
来源：http://dali.shangyingyoupin.top/Article/details/gt2vopbahyf.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.hysaishi.cn/Article/details/gt2ugzohcul.html

[S47] C++：结构化绑定遍历
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vipdtqbz.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2xesegfxt.html

[S48] C++：逐行读文件
来源：http://dali.dianchejie.cn/Article/details/gt2aspvaxnu.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.jqgufenzy.top/Article/details/gt2omfebdjp.html

while (std::getline(in, line)) { }
来源：http://dali.gotoacloud.top/Article/details/gt2ccdrkigw.html

[S49] C++：写文件
来源：http://dali.guannengcc.top/Article/details/gt2sexhmpsq.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.guowangkeji.top/Article/details/gt2dekkzbrj.html

[S50] C++：格式化数字
来源：http://dali.iojbl.cn/Article/details/gt2cjnixzrq.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.fzhhl.top/Article/details/gt2ufqdjynh.html

[S51] C++：显式类型转换
来源：http://dali.bjfxy.top/Article/details/gt2jifzyywn.html

static_cast<double>(a) / b
来源：http://dali.havefunace.top/Article/details/gt2psohvbym.html

[S52] C++：const 与 noexcept
来源：http://dali.tanke756.top/Article/details/gt2auysqpfr.html

int size() const noexcept { return n_; }
来源：http://dali.nanxuanxn.top/Article/details/gt2ftwvmqhd.html

[S53] C++：移动语义
来源：http://dali.yvedp.cn/Article/details/gt2uwdiwqje.html

std::vector<int> w = std::move(v);
来源：http://dali.hnqzz.top/Article/details/gt2aufztdrd.html

[S54] C++：异常处理
来源：http://dali.mhx1999.top/Article/details/gt2ilozbcxs.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vzzxibjc.html

[S55] C++：结构化绑定
来源：http://dali.quarkkingdee.top/Article/details/gt2wtjplwzk.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.guannengcc.top/Article/details/gt2qgpixlzy.html

[S56] C++：optional
来源：http://dali.cashguo.top/Article/details/gt2lfwmsmcz.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhongyouzk.top/Article/details/gt2lgtrptrk.html

[S57] C++：编译期常量
来源：http://dali.guowangkeji.top/Article/details/gt2uljtupeh.html

constexpr int N = 10;
来源：http://dali.ybcxt.top/Article/details/gt2istgiplq.html

[S58] C++：命名空间
来源：http://dali.kuanghao11.cn/Article/details/gt2xcjplxyy.html

namespace ns { int f() { return 1; } }
来源：http://dali.9152youxi.cn/Article/details/gt2lemujrnv.html

[S59] C++：静态断言
来源：http://dali.zhoulong.xyz/Article/details/gt2qjpoorap.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.ppjwa.cn/Article/details/gt2lhqjjvvl.html

[S60] C++：遍历并删除元素
来源：http://dali.yueranfly.top/Article/details/gt2zkzzjzbx.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.yueranfly.top/Article/details/gt2sspmxxxo.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gt2wxodpuav.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.feifeiyinyue.top/Article/details/gt2hblkykuk.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gt2yvnoygmu.html

[T01] Kotlin：Hello World
来源：http://dali.chenjidiqi.icu/Article/details/gt2msedqpnb.html

println("Hello")
来源：http://dali.jiagoushi.top/Article/details/gt2pfrcrcgl.html

[T02] Kotlin：变量
来源：http://dali.nwbrower.top/Article/details/gt2btpbkmbh.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.tianlin.xyz/Article/details/gt2emmjpegr.html

[T03] Kotlin：字符串模板
来源：http://dali.andypj.xyz/Article/details/gt2pwxdlpch.html

"值: $b"
来源：http://dali.yj20258.top/Article/details/gt2iwineawp.html

[T04] Kotlin：空安全
来源：http://dali.hnxiangtu.top/Article/details/gt2evpqvdwt.html

val n: String? = null;  n?.length
来源：http://dali.jiagoushi.top/Article/details/gt2vnewasgl.html

[T05] Kotlin：when 表达式
来源：http://dali.jianghu66.top/Article/details/gt2zuwvefzv.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.mhx1999.top/Article/details/gt2greorxis.html

[T06] Kotlin：集合映射
来源：http://dali.feifeiyinyue.top/Article/details/gt2ofjnmrkt.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.daxiang520.top/Article/details/gt2gsfkusin.html

[T07] Kotlin：集合过滤
来源：http://dali.yuxming.cn/Article/details/gt2zmenfqaz.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.hnqzz.top/Article/details/gt2phntlfnz.html

[T08] Kotlin：数据类
来源：http://dali.jiagoushi.top/Article/details/gt2uhibjhre.html

data class User(val name: String, val age: Int)
来源：http://dali.snrcjt.cn/Article/details/gt2bvtbltwm.html

[T09] Kotlin：扩展函数
来源：http://dali.316326.xyz/Article/details/gt2zopyrqie.html

fun String.exclaim() = this + "!"
来源：http://dali.cucudq.cn/Article/details/gt2bvcbdrwn.html

[T10] Kotlin：默认参数
来源：http://dali.redwolf501.top/Article/details/gt2ayqfuxgh.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.jqgufenzy.top/Article/details/gt2xhsuvbop.html

[T11] Kotlin：协程
来源：http://dali.shuidangran.top/Article/details/gt2fskxccyj.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.fengsongda.top/Article/details/gt2cmgegzby.html

[T12] Kotlin：解构声明
来源：http://dali.xinyue.icu/Article/details/gt2bgersbgx.html

val (a, b) = Pair(1, 2)
来源：http://dali.sweek.top/Article/details/gt2ppalxcvs.html

[T13] Kotlin：只读 Map
来源：http://dali.gaohongyu789.top/Article/details/gt2kgbhjtyx.html

val m = mapOf("a" to 1)
来源：http://dali.nanxinkj.top/Article/details/gt2qgtjbaol.html

[T14] Kotlin：循环
来源：http://dali.yj20258888.top/Article/details/gt2lgpgbget.html

for (i in 1..10) println(i)
来源：http://dali.smart0.xyz/Article/details/gt2amhxzzms.html

[T15] Kotlin：接口
来源：http://dali.daria6918.cn/Article/details/gt2ntbqcrqj.html

interface Shape { fun area(): Double }
来源：http://dali.yangfankeji.com/Article/details/gt2bfqbvklt.html

[T16] Swift：Hello World
来源：http://dali.tianlin.xyz/Article/details/gt2yukofmqj.html

print("Hello")
来源：http://dali.smart0.xyz/Article/details/gt2eyzqzleo.html

[T17] Swift：变量与常量
来源：http://dali.birdmap.top/Article/details/gt2pqhphomq.html

var a = 1;  let b = 2
来源：http://dali.dianchejie.cn/Article/details/gt2ckcffgid.html

[T18] Swift：字符串插值
来源：http://dali.yvedp.cn/Article/details/gt2chiwbmmq.html

"值: \(b)"
来源：http://dali.gogol.net.cn/Article/details/gt2fxdqpiih.html

[T19] Swift：可选绑定
来源：http://dali.yongpay.top/Article/details/gt2nhorwind.html

if let n = opt { print(n) }
来源：http://dali.daria6918.cn/Article/details/gt2fsfhhmeg.html

[T20] Swift：数组操作
来源：http://dali.cashguo.top/Article/details/gt2kdjloyus.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.xuanzx.com/Article/details/gt2ivrgfmwq.html

[T21] Swift：遍历
来源：http://dali.zhoulong.xyz/Article/details/gt2yfzzgriq.html

for x in a { print(x) }
来源：http://dali.yvedp.cn/Article/details/gt2xpacboga.html

[T22] Swift：字典
来源：http://dali.zhoulong.xyz/Article/details/gt2unpodoix.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.sxryk.cn/Article/details/gt2ayohqnny.html

[T23] Swift：函数
来源：http://dali.mhx1999.top/Article/details/gt2snqhteej.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.feifeiyinyue.top/Article/details/gt2xexxxxoa.html

[T24] Swift：闭包
来源：http://dali.cqqwz.cn/Article/details/gt2aeyvuucj.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kyfdyydd.html

[T25] Swift：结构体
来源：http://dali.shzxlz.cn/Article/details/gt2dttogeto.html

struct P { var x: Int }
来源：http://dali.yangfankeji.com/Article/details/gt2dtfxtuvm.html

[T26] Swift：类与重写
来源：http://dali.yueranfly.top/Article/details/gt2jslxtkfo.html

class A: Base { override func f() {} }
来源：http://dali.chenzaomai.com/Article/details/gt2xegfuebt.html

[T27] Swift：错误处理
来源：http://dali.zhoulong.xyz/Article/details/gt2xngharcw.html

do { try f() } catch { print(error) }
来源：http://dali.nwbrower.top/Article/details/gt2fprgwfni.html

[T28] Swift：枚举
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ovoinerj.html

enum Color { case red, green }
来源：http://dali.mhx1999.top/Article/details/gt2wiepkedx.html

[T29] Swift：guard 提前返回
来源：http://dali.yj20258.top/Article/details/gt2qpypxvap.html

guard let x = opt else { return }
来源：http://dali.quarkkingdee.top/Article/details/gt2jprpwhua.html

[T30] Swift：协议
来源：http://dali.cucudq.cn/Article/details/gt2kgxlsgfw.html

protocol Shape { func area() -> Double }
来源：http://dali.nanxinkj.top/Article/details/gt2lreuorto.html

[T31] Lua：Hello World
来源：http://dali.iojbl.cn/Article/details/gt2tdtdfwgs.html

print("Hello")
来源：http://dali.cashguo.top/Article/details/gt2bvkhphhb.html

[T32] Lua：局部变量
来源：http://dali.meibo888.top/Article/details/gt2vlmzsfdx.html

local a = 1
来源：http://dali.jqgfzy.top/Article/details/gt2gcbozpym.html

[T33] Lua：表（数组）
来源：http://dali.svipenyu.cn/Article/details/gt2qpmaxqlv.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.daria6918.cn/Article/details/gt2xiftvnbc.html

[T34] Lua：遍历表
来源：http://dali.chenlongwang.top/Article/details/gt2zinlxeup.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.xinyue.icu/Article/details/gt2kdrkliqg.html

[T35] Lua：字典表
来源：http://dali.daxiang520.top/Article/details/gt2ggwmyirf.html

local d = { a = 1 };  d.b = 2
来源：http://dali.yj20258.top/Article/details/gt2lrurhmdq.html

[T36] Lua：函数
来源：http://dali.hywenlv.cn/Article/details/gt2hwklusrm.html

function add(a, b) return a + b end
来源：http://dali.meibo888.top/Article/details/gt2ycnaumrd.html

[T37] Lua：字符串拼接
来源：http://dali.zycfv.cn/Article/details/gt2fewxvzcn.html

"a" .. "b"
来源：http://dali.zhiwuduotai.top/Article/details/gt2guysibvq.html

[T38] Lua：条件
来源：http://dali.hnqzz.top/Article/details/gt2oruyprcy.html

if x > 0 then print("正") end
来源：http://dali.zdqjudy.top/Article/details/gt2lqebuiif.html

[T39] Lua：模式匹配
来源：http://dali.yvedp.cn/Article/details/gt2psgoenur.html

string.find(s, "%d+")
来源：http://dali.yongpay.top/Article/details/gt2gxyqgece.html

[T40] Lua：元表
来源：http://dali.fengsongda.top/Article/details/gt2njnddtfi.html

setmetatable({}, { __index = base })
来源：http://dali.yanxiufei.cn/Article/details/gt2kdrsgxqn.html

[T41] Perl：Hello World
来源：http://dali.shuidangran.top/Article/details/gt2fusoizyn.html

print "Hello\n";
来源：http://dali.haohaochexian.top/Article/details/gt2pvthvzms.html

[T42] Perl：变量类型
来源：http://dali.9152youxi.cn/Article/details/gt2wgzntemm.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.hnqzz.top/Article/details/gt2onzqxifa.html

[T43] Perl：字符串插值
来源：http://dali.jinqigfzy.top/Article/details/gt2jwnjsyib.html

"值: $a"
来源：http://dali.shzxlz.cn/Article/details/gt2xzkahhps.html

[T44] Perl：条件
来源：http://dali.gaohongyu789.top/Article/details/gt2wawxgnuk.html

if ($a > 0) { print "正"; }
来源：http://dali.zhengqikj.top/Article/details/gt2waiocrzv.html

[T45] Perl：数组遍历
来源：http://dali.cashguo.top/Article/details/gt2jactorvt.html

for my $x (@arr) { print $x; }
来源：http://dali.chenlongwang.top/Article/details/gt2qhmhuuhv.html

[T46] Perl：哈希操作
来源：http://dali.quarkkingdee.top/Article/details/gt2zicncscv.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.jiagoushi.top/Article/details/gt2ercbrerx.html

[T47] Perl：正则捕获
来源：http://dali.mhx1999.top/Article/details/gt2xfbsemfu.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.dashuyun.cn/Article/details/gt2zymecqql.html

[T48] Perl：正则替换
来源：http://dali.jyoumei.cn/Article/details/gt2gaorpkba.html

$s =~ s/old/new/g;
来源：http://dali.havefunace.top/Article/details/gt2xqwxmocf.html

[T49] Perl：函数
来源：http://dali.yueranfly.top/Article/details/gt2uqqlcgyz.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.ybcxt.top/Article/details/gt2unpsfbqp.html

[T50] Perl：逐行读文件
来源：http://dali.yj20258.top/Article/details/gt2gsqflyyu.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.mhx1999.top/Article/details/gt2jkwtzrqc.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.nanxuanxn.top/Article/details/gt2xacsmwrj.html

[T51] Scala：Hello World
来源：http://dali.chenzaomai.com/Article/details/gt2fesycjoe.html

println("Hello")
来源：http://dali.c1oappe.top/Article/details/gt2oytavmuj.html

[T52] Scala：变量
来源：http://dali.pengpengdd.cyou/Article/details/gt2vnnplucz.html

val a = 1;  var b = 2
来源：http://dali.cheryme.top/Article/details/gt2luybevdc.html

[T53] Scala：字符串插值
来源：http://dali.daxiang520.top/Article/details/gt2znwjlkaw.html

s"值: $b"
来源：http://dali.xinyue.icu/Article/details/gt2fwhwkmuv.html

[T54] Scala：集合映射
来源：http://dali.yvedp.cn/Article/details/gt2trmhehwa.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.dashuyun.cn/Article/details/gt2cgrokmem.html

[T55] Scala：集合过滤
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cpabamuj.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.haohaochexian.top/Article/details/gt2ohgkocgp.html

[T56] Scala：样例类
来源：http://dali.ehwqpu.com/Article/details/gt2wgjlfumd.html

case class User(name: String, age: Int)
来源：http://dali.yuxming.cn/Article/details/gt2spsbefjd.html

[T57] Scala：模式匹配
来源：http://dali.zycfv.cn/Article/details/gt2qmcopyhx.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.xylfe.cn/Article/details/gt2gyxqtsds.html

[T58] Scala：函数定义
来源：http://dali.feifeiyinyue.top/Article/details/gt2sjwynqlu.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.jqgfzy.top/Article/details/gt2mndvycya.html

[T59] Scala：循环
来源：http://dali.yongpay.top/Article/details/gt2nowarjrj.html

for (i <- 1 to 10) println(i)
来源：http://dali.jqgfzy.top/Article/details/gt2kiiasjec.html

[T60] Scala：折叠
来源：http://dali.yuxming.cn/Article/details/gt2wqtontwq.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.wangdashe.top/Article/details/gt2jtxjsemn.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2drvmkbtx.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.9152youxi.cn/Article/details/gt2rpapymrs.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gt2uycjiccs.html

[U01] Py：创建虚拟环境
来源：http://dali.aizwys.cn/Article/details/gt2bcxtgach.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.birdmap.top/Article/details/gt2lxbyyghz.html

[U02] Py：导出 / 安装依赖
来源：http://dali.hammf.cn/Article/details/gt2vpgbgcjv.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.jianghu66.top/Article/details/gt2dknlbqah.html

[U03] Py：加载 .env 配置
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2aualzudv.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.vqdsnc.cn/Article/details/gt2bvkpheyl.html

[U04] Py：变量调试打印
来源：http://dali.daxiang520.top/Article/details/gt2jjaasygd.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.cheryme.top/Article/details/gt2onyurzrn.html

[U05] Py：列表去重且保序
来源：http://dali.feifeiyinyue.top/Article/details/gt2odludzdz.html

list(dict.fromkeys(arr))
来源：http://dali.316326.xyz/Article/details/gt2tlszmpkz.html

[U06] Py：合并两个字典
来源：http://dali.ivvv.top/Article/details/gt2nmfuruvp.html

{**a, **b}
来源：http://dali.tanke756.top/Article/details/gt2jfwjvrvd.html

[U07] Py：反转字典键值
来源：http://dali.ppjwa.cn/Article/details/gt2levmbffs.html

{v: k for k, v in d.items()}
来源：http://dali.fengsongda.top/Article/details/gt2ccjiuzil.html

[U08] Py：展平二维列表
来源：http://dali.yuxming.cn/Article/details/gt2qwyzheqp.html

[y for x in nested for y in x]
来源：http://dali.jiagoushi.top/Article/details/gt2jqviygux.html

[U09] Py：字典取最大值的键
来源：http://dali.xylfe.cn/Article/details/gt2jenexnay.html

max(d, key=d.get)
来源：http://dali.yonumen.top/Article/details/gt2wjercbll.html

[U10] Py：按值排序字典
来源：http://dali.guannengcc.top/Article/details/gt2vewpazjf.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhoulong.xyz/Article/details/gt2sjrvjqrz.html

[U11] Py：生成器表达式
来源：http://dali.hysaishi.cn/Article/details/gt2uofvlelp.html

(x * 2 for x in arr)
来源：http://dali.0kj1m.cn/Article/details/gt2psksrfce.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zdqjudy.top/Article/details/gt2bzdvthnt.html

Counter(arr).most_common(3)
来源：http://dali.yueranfly.top/Article/details/gt2ypxwnwgb.html

[U13] Py：固定长度队列
来源：http://dali.nwbrower.top/Article/details/gt2wzuquxwa.html

deque(maxlen=10)
来源：http://dali.c1oappe.top/Article/details/gt2jsykvjye.html

[U14] Py：分组收集到列表
来源：http://dali.ehwqpu.com/Article/details/gt2nfshwvlb.html

defaultdict(list)
来源：http://dali.cdnleiting.top/Article/details/gt2ycqsbqxd.html

[U15] Py：高精度计时
来源：http://dali.xylfe.cn/Article/details/gt2fwhxodij.html

t = time.perf_counter()
来源：http://dali.shangyingyoupin.top/Article/details/gt2rlvxrvth.html

[U16] Py：命令行参数解析
来源：http://dali.jyoumei.cn/Article/details/gt2jpcfbuyc.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.xuanzx.com/Article/details/gt2jchypqrw.html

[U17] Py：初始化日志
来源：http://dali.dianchejie.cn/Article/details/gt2ajffdclg.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.andypj.xyz/Article/details/gt2hiamzwpi.html

[U18] Py：预编译正则
来源：http://dali.vqdsnc.cn/Article/details/gt2wukxgszk.html

pat = re.compile(r"\d+")
来源：http://dali.jinqigfzy.top/Article/details/gt2gvxbzexq.html

[U19] Py：正则替换带回调
来源：http://dali.snrcjt.cn/Article/details/gt2gymjnqnr.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.guannengcc.top/Article/details/gt2wndekxjh.html

[U20] Py：缓存函数结果
来源：http://dali.zhengqikj.top/Article/details/gt2ugpbcscz.html

@functools.lru_cache(maxsize=None)
来源：http://dali.wangshuangyany.cn/Article/details/gt2qtkycruu.html

[U21] Py：自定义上下文管理器
来源：http://dali.daxiang520.top/Article/details/gt2lcdlttwi.html

@contextlib.contextmanager
来源：http://dali.havefunace.top/Article/details/gt2lfcolzhv.html

[U22] Py：矩阵转置
来源：http://dali.jqgufenzy.top/Article/details/gt2pambiumg.html

list(zip(*m))
来源：http://dali.aizwys.cn/Article/details/gt2zbrjhgdz.html

[U23] Py：分块读取大文件
来源：http://dali.sweek.top/Article/details/gt2nvtvhvjb.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jaiwqspu.html

[U24] Py：路径操作
来源：http://dali.yj202588.top/Article/details/gt2uyvxwzjo.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.cheryme.top/Article/details/gt2ojzxsolb.html

[U25] Py：CSV 按字典读
来源：http://dali.meibo888.top/Article/details/gt2gytoxtsh.html

csv.DictReader(f)
来源：http://dali.yueranfly.top/Article/details/gt2sgxvxjaq.html

[U26] Py：并发下载
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sadhzkau.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.tianlin.xyz/Article/details/gt2znvtepgd.html

[U27] Py：异步 HTTP
来源：http://dali.zhoulong.xyz/Article/details/gt2mqxnrono.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.guannengcc.top/Article/details/gt2pvwcfznw.html

[U28] Py：类型别名
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kbofwtoo.html

UserId = int
来源：http://dali.quarkkingdee.top/Article/details/gt2qodrfkxu.html

[U29] Py：属性校验
来源：http://dali.mhx1999.top/Article/details/gt2agexdldx.html

@property 与 @x.setter 配合
来源：http://dali.ydzc1.top/Article/details/gt2xczmwkht.html

[U30] Py：数据类
来源：http://dali.gotoacloud.top/Article/details/gt2qlvvneiz.html

@dataclass(slots=True)
来源：http://dali.pycfn.com/Article/details/gt2numxszfm.html

[U31] Py：单测
来源：http://dali.yuanzhike.top/Article/details/gt2gqwvkzjo.html

python -m pytest -q
来源：http://dali.ybcxt.top/Article/details/gt2kfzdyzmf.html

[U32] Py：代码格式化
来源：http://dali.ehwqpu.com/Article/details/gt2mwxwuuur.html

ruff format . && ruff check --fix .
来源：http://dali.sxryk.cn/Article/details/gt2vytcegrs.html

[U33] Py：打包发布
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rpgwfdbp.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhengqikj.top/Article/details/gt2zvpvesry.html

[U34] Py：判断编码
来源：http://dali.zhoulong.xyz/Article/details/gt2ybkmsduc.html

chardet.detect(raw)
来源：http://dali.mhx1999.top/Article/details/gt2ngphdpaz.html

[U35] Py：发送邮件
来源：http://dali.yuanzhike.top/Article/details/gt2dxzneywi.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.xziqi.cn/Article/details/gt2jdzyhlhl.html

[U36] Py：定时任务
来源：http://dali.cucudq.cn/Article/details/gt2jqmeguey.html

schedule.every(10).minutes.do(job)
来源：http://dali.xinyue.icu/Article/details/gt2skakwsqw.html


<!-- 参考信息 -->