代发 wailian999

FILE *f = fopen("a.txt", "r");
来源：http://dali.zycfv.cn/Article/details/gt2ndqkewvy.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.vqdsnc.cn/Article/details/gt2nrucfumq.html

fclose(f);
来源：http://dali.gzhubu.top/Article/details/gt2nnheuxvp.html

[S12] C：写文件
来源：http://dali.tanke756.top/Article/details/gt2ydpgekpc.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.smart0.xyz/Article/details/gt2gdzxqtsc.html

[S13] C：宏定义
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pvsadkwc.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.gogol.net.cn/Article/details/gt2amkqguwp.html

[S14] C：枚举
来源：http://dali.jinqigfzy.top/Article/details/gt2rscptohf.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.bjfxy.top/Article/details/gt2suodtgje.html

[S15] C：类型转换
来源：http://dali.havefunace.top/Article/details/gt2zmnvdczt.html

(double) a / b
来源：http://dali.chenjidiqi.icu/Article/details/gt2oheoyaqn.html

[S16] C：位操作置位
来源：http://dali.meibo888.top/Article/details/gt2apybquuu.html

x |= (1 << 3);
来源：http://dali.jianghu66.top/Article/details/gt2hdfjfgwt.html

[S17] C：安全拼接字符串
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lkhdqbvx.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.aibaodan.cn/Article/details/gt2bljxxvaw.html

[S18] C：命令行参数
来源：http://dali.zhengqikj.top/Article/details/gt2frqhhrwf.html

int main(int argc, char **argv)
来源：http://dali.jinqigfzy.top/Article/details/gt2pjxbgbkn.html

[S19] C：快速排序
来源：http://dali.meibo888.top/Article/details/gt2eereqgvu.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.dianchejie.cn/Article/details/gt2aedzgjxe.html

[S20] C：二分查找
来源：http://dali.gogol.net.cn/Article/details/gt2auacrrto.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.nanxinkj.top/Article/details/gt2fnowgble.html

[S21] C：字符类别判断
来源：http://dali.vqdsnc.cn/Article/details/gt2oicixfdx.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zycfv.cn/Article/details/gt2uwgsdpnl.html

[S22] C：字符串转数字
来源：http://dali.guowangkeji.top/Article/details/gt2wzbgrnml.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2yygovlak.html

[S23] C：随机数
来源：http://dali.sufxvd.cn/Article/details/gt2subfrtvk.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.ppjwa.cn/Article/details/gt2gtaqkenb.html

[S24] C：获取本地时间
来源：http://dali.hnqzz.top/Article/details/gt2plokqfsy.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.shzxlz.cn/Article/details/gt2iagkoeiv.html

[S25] C：内存拷贝
来源：http://dali.dianchejie.cn/Article/details/gt2crclnwxl.html

memcpy(dst, src, n);
来源：http://dali.hfpthk.cn/Article/details/gt2blylrbep.html

[S26] C：内存清零
来源：http://dali.jinqigufen.top/Article/details/gt2qxvxjyjb.html

memset(a, 0, sizeof a);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tuxmnjdy.html

[S27] C：定义常量
来源：http://dali.redwolf501.top/Article/details/gt2wxqzwagp.html

const double PI = 3.14159;
来源：http://dali.yuanzhike.top/Article/details/gt2qbpwzkjd.html

[S28] C：静态变量
来源：http://dali.sweek.top/Article/details/gt2luhdlqra.html

static int counter = 0;
来源：http://dali.nanxuanxn.top/Article/details/gt2igzxxnbf.html

[S29] C：变参函数
来源：http://dali.hysaishi.cn/Article/details/gt2ymdljozh.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.svipenyu.cn/Article/details/gt2mxewldyl.html

[S30] C：头文件保护
来源：http://dali.shuidangran.top/Article/details/gt2brvfxixw.html

#ifndef X_H
来源：http://dali.sufxvd.cn/Article/details/gt2wyrubile.html

#define X_H
来源：http://dali.ehwqpu.com/Article/details/gt2mryxesbk.html

#endif
来源：http://dali.xylfe.cn/Article/details/gt2ypgdbbvc.html

[S31] C++：Hello World
来源：http://dali.zhixingplan.top/Article/details/gt2vqoywnxk.html

#include <iostream>
来源：http://dali.daria6918.cn/Article/details/gt2junzmzjd.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.kuanghao11.cn/Article/details/gt2fmriutqq.html

[S32] C++：字符串
来源：http://dali.pycfn.com/Article/details/gt2ssnxftwt.html

std::string s = "hi";  s += "!";
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yjhwdwro.html

[S33] C++：vector 增删
来源：http://dali.ivvv.top/Article/details/gt2rxlfhnkc.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.jqgfzy.top/Article/details/gt2xejjaqix.html

[S34] C++：遍历 vector
来源：http://dali.cucudq.cn/Article/details/gt2bketbbcd.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.shuidangran.top/Article/details/gt2jifybywm.html

[S35] C++：map
来源：http://dali.guannengcc.top/Article/details/gt2bgefohak.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.cqqwz.cn/Article/details/gt2lnfkjsej.html

[S36] C++：unordered_map
来源：http://dali.nwbrower.top/Article/details/gt2vswuahie.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.wangshuangyany.cn/Article/details/gt2lvzpikfg.html

[S37] C++：set
来源：http://dali.jlsjyb.cn/Article/details/gt2ibtxmzvs.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.daria6918.cn/Article/details/gt2cgewzfqf.html

[S38] C++：排序
来源：http://dali.zhengqikj.top/Article/details/gt2mgzgzdng.html

std::sort(v.begin(), v.end());
来源：http://dali.tanke756.top/Article/details/gt2ktjhjrse.html

[S39] C++：自定义比较器排序
来源：http://dali.andypj.xyz/Article/details/gt2zuyfycmr.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.aizwys.cn/Article/details/gt2abqmblll.html

[S40] C++：查找元素
来源：http://dali.kuanghao11.cn/Article/details/gt2lhwtgocj.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.sysykeji.top/Article/details/gt2wezoctsv.html

[S41] C++：类与构造函数
来源：http://dali.xuanzx.com/Article/details/gt2yjojegqz.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zdqjudy.top/Article/details/gt2bdhhqmkt.html

[S42] C++：继承与虚函数
来源：http://dali.ydzc1.top/Article/details/gt2fykubkxh.html

class B : public Base { public: void f() override {} };
来源：http://dali.nanxinkj.top/Article/details/gt2crpbiocj.html

[S43] C++：智能指针
来源：http://dali.zycfv.cn/Article/details/gt2krrholju.html

auto p = std::make_unique<int>(5);
来源：http://dali.yuxming.cn/Article/details/gt2ugjvumno.html

[S44] C++：引用传参
来源：http://dali.kuanghao11.cn/Article/details/gt2qymivrka.html

void inc(int &x) { ++x; }
来源：http://dali.cashguo.top/Article/details/gt2bmlbejua.html

[S45] C++：lambda
来源：http://dali.wangshuangyany.cn/Article/details/gt2nathnleb.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2tacfcryi.html

[S46] C++：函数模板
来源：http://dali.fengsongda.top/Article/details/gt2pkgpzetg.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.tianlin.xyz/Article/details/gt2mjmpknsq.html

[S47] C++：结构化绑定遍历
来源：http://dali.haohaochexian.top/Article/details/gt2tzzprzhk.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.smart0.xyz/Article/details/gt2roseoqht.html

[S48] C++：逐行读文件
来源：http://dali.yangfankeji.com/Article/details/gt2csrkqnlw.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xezpczhf.html

while (std::getline(in, line)) { }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pjdzdbfe.html

[S49] C++：写文件
来源：http://dali.aibaodan.cn/Article/details/gt2wuyfrjgu.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.jianghu66.top/Article/details/gt2nlmgbelo.html

[S50] C++：格式化数字
来源：http://dali.hysaishi.cn/Article/details/gt2gfbaerdm.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.guowangkeji.top/Article/details/gt2nygrbfaw.html

[S51] C++：显式类型转换
来源：http://dali.guannengcc.top/Article/details/gt2xzbfhvqm.html

static_cast<double>(a) / b
来源：http://dali.shanyushiyangtech.top/Article/details/gt2alweondy.html

[S52] C++：const 与 noexcept
来源：http://dali.tanke756.top/Article/details/gt2bqnnnbgy.html

int size() const noexcept { return n_; }
来源：http://dali.gaohongyu789.top/Article/details/gt2mxiutozg.html

[S53] C++：移动语义
来源：http://dali.iojbl.cn/Article/details/gt2lekrjskb.html

std::vector<int> w = std::move(v);
来源：http://dali.sufxvd.cn/Article/details/gt2wryxciaf.html

[S54] C++：异常处理
来源：http://dali.yonumen.top/Article/details/gt2wrwrucea.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.cashguo.top/Article/details/gt2napmthwo.html

[S55] C++：结构化绑定
来源：http://dali.xziqi.cn/Article/details/gt2pppoqqcs.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.gaohongyu789.top/Article/details/gt2lerwgltf.html

[S56] C++：optional
来源：http://dali.cqqwz.cn/Article/details/gt2hxcbrwnf.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.fzhhl.top/Article/details/gt2zjqwffgm.html

[S57] C++：编译期常量
来源：http://dali.chenjidiqi.icu/Article/details/gt2bohpinau.html

constexpr int N = 10;
来源：http://dali.hfpthk.cn/Article/details/gt2xlvfgunv.html

[S58] C++：命名空间
来源：http://dali.yonumen.top/Article/details/gt2becjbdox.html

namespace ns { int f() { return 1; } }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tilfxqrb.html

[S59] C++：静态断言
来源：http://dali.xylfe.cn/Article/details/gt2cgbdimzw.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.jiagoushi.top/Article/details/gt2btueccrr.html

[S60] C++：遍历并删除元素
来源：http://dali.xinyue.icu/Article/details/gt2obwaeopi.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.hongshengwenyu.top/Article/details/gt2fdfgzsoa.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2plfosqoi.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fxlodvda.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2wutgrrou.html

[T01] Kotlin：Hello World
来源：http://dali.yj20258.top/Article/details/gt2lidooxyj.html

println("Hello")
来源：http://dali.guowangkeji.top/Article/details/gt2qjoqsezp.html

[T02] Kotlin：变量
来源：http://dali.yvedp.cn/Article/details/gt2pydjrsjn.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.birdmap.top/Article/details/gt2cjkewgnp.html

[T03] Kotlin：字符串模板
来源：http://dali.yj20258.top/Article/details/gt2ozmklkfj.html

"值: $b"
来源：http://dali.zhongyouzk.top/Article/details/gt2qkolvywq.html

[T04] Kotlin：空安全
来源：http://dali.yonumen.top/Article/details/gt2imqpmyvs.html

val n: String? = null;  n?.length
来源：http://dali.xuetiantiany.cn/Article/details/gt2gxttmsco.html

[T05] Kotlin：when 表达式
来源：http://dali.cdnleiting.top/Article/details/gt2lnjwsois.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhoulong.xyz/Article/details/gt2ukvswhca.html

[T06] Kotlin：集合映射
来源：http://dali.sysykeji.top/Article/details/gt2pejattzn.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.cqqwz.cn/Article/details/gt2euvmjupa.html

[T07] Kotlin：集合过滤
来源：http://dali.yanxiufei.cn/Article/details/gt2sguhgcbz.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.yj202588.top/Article/details/gt2knakzejc.html

[T08] Kotlin：数据类
来源：http://dali.hammf.cn/Article/details/gt2rpljivwy.html

data class User(val name: String, val age: Int)
来源：http://dali.hnxiangtu.top/Article/details/gt2odiwxeya.html

[T09] Kotlin：扩展函数
来源：http://dali.wangshuangyany.cn/Article/details/gt2kccybedh.html

fun String.exclaim() = this + "!"
来源：http://dali.zhiwuduotai.top/Article/details/gt2zbrhhkzp.html

[T10] Kotlin：默认参数
来源：http://dali.zhiwuduotai.top/Article/details/gt2kzshxhmu.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.daxiang520.top/Article/details/gt2tskaovwq.html

[T11] Kotlin：协程
来源：http://dali.zycfv.cn/Article/details/gt2izbtdvhv.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.daria6918.cn/Article/details/gt2uornnlth.html

[T12] Kotlin：解构声明
来源：http://dali.aizwys.cn/Article/details/gt2jjpiuupp.html

val (a, b) = Pair(1, 2)
来源：http://dali.hfpthk.cn/Article/details/gt2trtfupzw.html

[T13] Kotlin：只读 Map
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mbuzsyej.html

val m = mapOf("a" to 1)
来源：http://dali.svipenyu.cn/Article/details/gt2grztmnwu.html

[T14] Kotlin：循环
来源：http://dali.jlsjyb.cn/Article/details/gt2pgukoyif.html

for (i in 1..10) println(i)
来源：http://dali.ppjwa.cn/Article/details/gt2zlrhnwbq.html

[T15] Kotlin：接口
来源：http://dali.pengpengdd.cyou/Article/details/gt2wdjenfxg.html

interface Shape { fun area(): Double }
来源：http://dali.chenjidiqi.icu/Article/details/gt2wirgmcjv.html

[T16] Swift：Hello World
来源：http://dali.ydzc1.top/Article/details/gt2ngxrwjby.html

print("Hello")
来源：http://dali.cheryme.top/Article/details/gt2bltevvmc.html

[T17] Swift：变量与常量
来源：http://dali.chenzaomai.com/Article/details/gt2ilcsnasd.html

var a = 1;  let b = 2
来源：http://dali.gzhubu.top/Article/details/gt2fxgraqba.html

[T18] Swift：字符串插值
来源：http://dali.gotoacloud.top/Article/details/gt2pjpbjivp.html

"值: \(b)"
来源：http://dali.jlsjyb.cn/Article/details/gt2tfvaiklg.html

[T19] Swift：可选绑定
来源：http://dali.yvedp.cn/Article/details/gt2mwmgnhlj.html

if let n = opt { print(n) }
来源：http://dali.zycfv.cn/Article/details/gt2gymhroyt.html

[T20] Swift：数组操作
来源：http://dali.zhiwuduotai.top/Article/details/gt2mjczchlt.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.shzxlz.cn/Article/details/gt2pcxnqarg.html

[T21] Swift：遍历
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2buohokfi.html

for x in a { print(x) }
来源：http://dali.tian-w.cn/Article/details/gt2kqukftuk.html

[T22] Swift：字典
来源：http://dali.cheryme.top/Article/details/gt2upwztmmi.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.xuetiantiany.cn/Article/details/gt2czwoluoj.html

[T23] Swift：函数
来源：http://dali.zhiwuduotai.top/Article/details/gt2yuieqllb.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.wangshuangyany.cn/Article/details/gt2megbzfkb.html

[T24] Swift：闭包
来源：http://dali.ppjwa.cn/Article/details/gt2bedyywdp.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.yueranfly.top/Article/details/gt2dagcrjqp.html

[T25] Swift：结构体
来源：http://dali.yonumen.top/Article/details/gt2qzcwytyl.html

struct P { var x: Int }
来源：http://dali.aizwys.cn/Article/details/gt2zzggmnee.html

[T26] Swift：类与重写
来源：http://dali.ydzc1.top/Article/details/gt2haaccujj.html

class A: Base { override func f() {} }
来源：http://dali.havefunace.top/Article/details/gt2jeyzsmrw.html

[T27] Swift：错误处理
来源：http://dali.zhongyouzk.top/Article/details/gt2ctirxmos.html

do { try f() } catch { print(error) }
来源：http://dali.0kj1m.cn/Article/details/gt2xxosvrqc.html

[T28] Swift：枚举
来源：http://dali.cashguo.top/Article/details/gt2tnatlwqc.html

enum Color { case red, green }
来源：http://dali.jqgufenzy.top/Article/details/gt2cyjmgcpl.html

[T29] Swift：guard 提前返回
来源：http://dali.birdmap.top/Article/details/gt2pjbtksvo.html

guard let x = opt else { return }
来源：http://dali.tianlin.xyz/Article/details/gt2ioxfvsfw.html

[T30] Swift：协议
来源：http://dali.nanxuanxn.top/Article/details/gt2echjmnwj.html

protocol Shape { func area() -> Double }
来源：http://dali.feifeiyinyue.top/Article/details/gt2dzzcpjku.html

[T31] Lua：Hello World
来源：http://dali.quarkkingdee.top/Article/details/gt2nokqdfvv.html

print("Hello")
来源：http://dali.c1oappe.top/Article/details/gt2ktbiqquu.html

[T32] Lua：局部变量
来源：http://dali.dianchejie.cn/Article/details/gt2xnaslwxg.html

local a = 1
来源：http://dali.ppjwa.cn/Article/details/gt2zfggalnw.html

[T33] Lua：表（数组）
来源：http://dali.meibo888.top/Article/details/gt2pwjlwkmb.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.kuanghao11.cn/Article/details/gt2ofaxujdv.html

[T34] Lua：遍历表
来源：http://dali.hfpthk.cn/Article/details/gt2sdpuqptf.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.andypj.xyz/Article/details/gt2pntjsulq.html

[T35] Lua：字典表
来源：http://dali.mhx1999.top/Article/details/gt2skeazrey.html

local d = { a = 1 };  d.b = 2
来源：http://dali.dashuyun.cn/Article/details/gt2aonvgbnf.html

[T36] Lua：函数
来源：http://dali.redwolf501.top/Article/details/gt2gocrphjr.html

function add(a, b) return a + b end
来源：http://dali.wangshuangyany.cn/Article/details/gt2qvybcgkx.html

[T37] Lua：字符串拼接
来源：http://dali.jqgfzy.top/Article/details/gt2zmisfagq.html

"a" .. "b"
来源：http://dali.ivvv.top/Article/details/gt2ncnhleam.html

[T38] Lua：条件
来源：http://dali.zhengqikj.top/Article/details/gt2vyhbgfkm.html

if x > 0 then print("正") end
来源：http://dali.xylfe.cn/Article/details/gt2ptsuiysz.html

[T39] Lua：模式匹配
来源：http://dali.zhongyouzk.top/Article/details/gt2vhhndpzh.html

string.find(s, "%d+")
来源：http://dali.hywenlv.cn/Article/details/gt2xhqpnykm.html

[T40] Lua：元表
来源：http://dali.birdmap.top/Article/details/gt2wwyutyia.html

setmetatable({}, { __index = base })
来源：http://dali.ydzc1.top/Article/details/gt2ppgwjnon.html

[T41] Perl：Hello World
来源：http://dali.guowangkeji.top/Article/details/gt2blqxuqpz.html

print "Hello\n";
来源：http://dali.nanxinkj.top/Article/details/gt2mxefyqvd.html

[T42] Perl：变量类型
来源：http://dali.nwbrower.top/Article/details/gt2dveidopt.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.nanxuanxn.top/Article/details/gt2ihkxycau.html

[T43] Perl：字符串插值
来源：http://dali.jqgfzy.top/Article/details/gt2hdgyeqwf.html

"值: $a"
来源：http://dali.316326.xyz/Article/details/gt2yonyfbdr.html

[T44] Perl：条件
来源：http://dali.ppjwa.cn/Article/details/gt2ecnjnizy.html

if ($a > 0) { print "正"; }
来源：http://dali.yangfankeji.com/Article/details/gt2aqetgfau.html

[T45] Perl：数组遍历
来源：http://dali.tian-w.cn/Article/details/gt2fhloltqw.html

for my $x (@arr) { print $x; }
来源：http://dali.bjfxy.top/Article/details/gt2kurtpkym.html

[T46] Perl：哈希操作
来源：http://dali.cqqwz.cn/Article/details/gt2pvcenodm.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.shuidangran.top/Article/details/gt2yeyoecrt.html

[T47] Perl：正则捕获
来源：http://dali.nanxinkj.top/Article/details/gt2kyvgzljz.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.9152youxi.cn/Article/details/gt2dyasookh.html

[T48] Perl：正则替换
来源：http://dali.wangshuangyany.cn/Article/details/gt2ylgzqzcc.html

$s =~ s/old/new/g;
来源：http://dali.kuanghao11.cn/Article/details/gt2odqwughb.html

[T49] Perl：函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2frqyhxub.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.kuanghao11.cn/Article/details/gt2jzjmuayf.html

[T50] Perl：逐行读文件
来源：http://dali.hysaishi.cn/Article/details/gt2nninbere.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.hfpthk.cn/Article/details/gt2tnvhnzml.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.hfpthk.cn/Article/details/gt2dhdlaqcc.html

[T51] Scala：Hello World
来源：http://dali.yuxming.cn/Article/details/gt2odeaisch.html

println("Hello")
来源：http://dali.yvedp.cn/Article/details/gt2lylekyli.html

[T52] Scala：变量
来源：http://dali.haohaochexian.top/Article/details/gt2qkxswtrv.html

val a = 1;  var b = 2
来源：http://dali.sweek.top/Article/details/gt2amqrdofj.html

[T53] Scala：字符串插值
来源：http://dali.guowangkeji.top/Article/details/gt2pwyoyxou.html

s"值: $b"
来源：http://dali.zhixingplan.top/Article/details/gt2nutlzris.html

[T54] Scala：集合映射
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ymmznclk.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.iojbl.cn/Article/details/gt2qysgagci.html

[T55] Scala：集合过滤
来源：http://dali.sufxvd.cn/Article/details/gt2uiggtypt.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.nanxuanxn.top/Article/details/gt2cjyxbbru.html

[T56] Scala：样例类
来源：http://dali.cashguo.top/Article/details/gt2nrvdphcj.html

case class User(name: String, age: Int)
来源：http://dali.hfpthk.cn/Article/details/gt2wunomebd.html

[T57] Scala：模式匹配
来源：http://dali.cashguo.top/Article/details/gt2ixzukbsg.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.gotoacloud.top/Article/details/gt2hauqqldr.html

[T58] Scala：函数定义
来源：http://dali.ppjwa.cn/Article/details/gt2bcoistnc.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.meibo888.top/Article/details/gt2cywvrbdv.html

[T59] Scala：循环
来源：http://dali.smart0.xyz/Article/details/gt2mpzxccar.html

for (i <- 1 to 10) println(i)
来源：http://dali.aibaodan.cn/Article/details/gt2vngzjjoq.html

[T60] Scala：折叠
来源：http://dali.xinyue.icu/Article/details/gt2ibhggdpk.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.iojbl.cn/Article/details/gt2duljsyni.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2rdsieqmp.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.xziqi.cn/Article/details/gt2ifsvtinu.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gt2nagfesqy.html

[U01] Py：创建虚拟环境
来源：http://dali.yueranfly.top/Article/details/gt2nsfsfbjf.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.yanxiufei.cn/Article/details/gt2hntvtndg.html

[U02] Py：导出 / 安装依赖
来源：http://dali.sufxvd.cn/Article/details/gt2oxubdqae.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.jinqigufen.top/Article/details/gt2qxmlvyvd.html

[U03] Py：加载 .env 配置
来源：http://dali.jianghu66.top/Article/details/gt2rpddxmnu.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.tianlin.xyz/Article/details/gt2cejvzmjs.html

[U04] Py：变量调试打印
来源：http://dali.hywenlv.cn/Article/details/gt2fyelxlhn.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.ydzc1.top/Article/details/gt2kqdvnqgk.html

[U05] Py：列表去重且保序
来源：http://dali.svipenyu.cn/Article/details/gt2czbgbmog.html

list(dict.fromkeys(arr))
来源：http://dali.tian-w.cn/Article/details/gt2qqonucjv.html

[U06] Py：合并两个字典
来源：http://dali.ydzc1.top/Article/details/gt2dkdaifrc.html

{**a, **b}
来源：http://dali.sysykeji.top/Article/details/gt2jwjmabqi.html

[U07] Py：反转字典键值
来源：http://dali.cheryme.top/Article/details/gt2nmghcksh.html

{v: k for k, v in d.items()}
来源：http://dali.svipenyu.cn/Article/details/gt2tolimshe.html

[U08] Py：展平二维列表
来源：http://dali.andypj.xyz/Article/details/gt2nzezndbr.html

[y for x in nested for y in x]
来源：http://dali.c1oappe.top/Article/details/gt2rwnpiejd.html

[U09] Py：字典取最大值的键
来源：http://dali.sweek.top/Article/details/gt2xzqbzdnc.html

max(d, key=d.get)
来源：http://dali.jinqigfzy.top/Article/details/gt2vlgckzrt.html

[U10] Py：按值排序字典
来源：http://dali.yuxming.cn/Article/details/gt2hmeaanqr.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.hnxiangtu.top/Article/details/gt2pckpmfkl.html

[U11] Py：生成器表达式
来源：http://dali.pycfn.com/Article/details/gt2ipgrljvz.html

(x * 2 for x in arr)
来源：http://dali.hywenlv.cn/Article/details/gt2rmxwjhcy.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.jianghu66.top/Article/details/gt2fnihpewg.html

Counter(arr).most_common(3)
来源：http://dali.pengpengdd.cyou/Article/details/gt2xemijlfa.html

[U13] Py：固定长度队列
来源：http://dali.dashuyun.cn/Article/details/gt2qvnojkcz.html

deque(maxlen=10)
来源：http://dali.yj20258888.top/Article/details/gt2qmaeuejz.html

[U14] Py：分组收集到列表
来源：http://dali.zhongyouzk.top/Article/details/gt2wfssravk.html

defaultdict(list)
来源：http://dali.jiagoushi.top/Article/details/gt2klassxaz.html

[U15] Py：高精度计时
来源：http://dali.jqgufenzy.top/Article/details/gt2aktvlplf.html

t = time.perf_counter()
来源：http://dali.jqgfzy.top/Article/details/gt2ponxkycx.html

[U16] Py：命令行参数解析
来源：http://dali.yuanzhike.top/Article/details/gt2lwfvtkxv.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.daxiang520.top/Article/details/gt2gnkuafsu.html

[U17] Py：初始化日志
来源：http://dali.gogol.net.cn/Article/details/gt2lzpnawtn.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2haymvrhy.html

[U18] Py：预编译正则
来源：http://dali.aibaodan.cn/Article/details/gt2pdwedorh.html

pat = re.compile(r"\d+")
来源：http://dali.redwolf501.top/Article/details/gt2fawwbwny.html

[U19] Py：正则替换带回调
来源：http://dali.yueranfly.top/Article/details/gt2juixolpf.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.pengpengdd.cyou/Article/details/gt2fkryglqf.html

[U20] Py：缓存函数结果
来源：http://dali.yvedp.cn/Article/details/gt2ltpscfoq.html

@functools.lru_cache(maxsize=None)
来源：http://dali.gogol.net.cn/Article/details/gt2prcyucch.html

[U21] Py：自定义上下文管理器
来源：http://dali.snrcjt.cn/Article/details/gt2taoinwvy.html

@contextlib.contextmanager
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zmlyxfct.html

[U22] Py：矩阵转置
来源：http://dali.chenjidiqi.icu/Article/details/gt2xybzuaag.html

list(zip(*m))
来源：http://dali.chenzaomai.com/Article/details/gt2guerpslw.html

[U23] Py：分块读取大文件
来源：http://dali.sysykeji.top/Article/details/gt2vdwcydpa.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.9152youxi.cn/Article/details/gt2cmldgdif.html

[U24] Py：路径操作
来源：http://dali.tanke756.top/Article/details/gt2movufhkh.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.jinqigufen.top/Article/details/gt2utqnwnco.html

[U25] Py：CSV 按字典读
来源：http://dali.c1oappe.top/Article/details/gt2wexljexy.html

csv.DictReader(f)
来源：http://dali.ydzc1.top/Article/details/gt2maktqozm.html

[U26] Py：并发下载
来源：http://dali.shzxlz.cn/Article/details/gt2ntqrsews.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.ivvv.top/Article/details/gt2rjxtikwl.html

[U27] Py：异步 HTTP
来源：http://dali.haohaochexian.top/Article/details/gt2rzzkyidd.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.meibo888.top/Article/details/gt2fqaytdho.html

[U28] Py：类型别名
来源：http://dali.yj20258.top/Article/details/gt2nryzjidj.html

UserId = int
来源：http://dali.zhiwuduotai.top/Article/details/gt2juzmvayo.html

[U29] Py：属性校验
来源：http://dali.yueranfly.top/Article/details/gt2gjrogtxt.html

@property 与 @x.setter 配合
来源：http://dali.guowangkeji.top/Article/details/gt2sjhneggr.html

[U30] Py：数据类
来源：http://dali.yueranfly.top/Article/details/gt2cyqfjhmw.html

@dataclass(slots=True)
来源：http://dali.guowangkeji.top/Article/details/gt2ucwurpzb.html

[U31] Py：单测
来源：http://dali.iojbl.cn/Article/details/gt2lykoinrv.html

python -m pytest -q
来源：http://dali.daria6918.cn/Article/details/gt2vrwrovdj.html

[U32] Py：代码格式化
来源：http://dali.kuanghao11.cn/Article/details/gt2zbcijaol.html

ruff format . && ruff check --fix .
来源：http://dali.svipenyu.cn/Article/details/gt2ftwzoslk.html

[U33] Py：打包发布
来源：http://dali.tianlin.xyz/Article/details/gt2phtzfyve.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.nwbrower.top/Article/details/gt2fifdpefw.html

[U34] Py：判断编码
来源：http://dali.yonumen.top/Article/details/gt2vkwfajfy.html

chardet.detect(raw)
来源：http://dali.zhengqikj.top/Article/details/gt2jgedgdva.html


<!-- 参考信息 -->