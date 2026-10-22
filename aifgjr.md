代发 wailian999

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.hysaishi.cn/Article/details/gt2ygoxakon.html

[S10] C：指针与解引用
来源：http://dali.xuanzx.com/Article/details/gt2zwitxsdh.html

int *p = &a;  *p = 5;
来源：http://dali.zhixingplan.top/Article/details/gt2cowyuedf.html

[S11] C：逐行读文件
来源：http://dali.hammf.cn/Article/details/gt2kkhlszrb.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.ybcxt.top/Article/details/gt2xainuqnq.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.nanxuanxn.top/Article/details/gt2byoofoqd.html

fclose(f);
来源：http://dali.iojbl.cn/Article/details/gt2tbgnuqtk.html

[S12] C：写文件
来源：http://dali.snrcjt.cn/Article/details/gt2eesfarnn.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.xziqi.cn/Article/details/gt2grobfrfg.html

[S13] C：宏定义
来源：http://dali.zhixingplan.top/Article/details/gt2qsbdvioa.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2oiibvzvk.html

[S14] C：枚举
来源：http://dali.yanxiufei.cn/Article/details/gt2rytjcxao.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.birdmap.top/Article/details/gt2ezwrthyv.html

[S15] C：类型转换
来源：http://dali.cucudq.cn/Article/details/gt2gnfamjgy.html

(double) a / b
来源：http://dali.yuxming.cn/Article/details/gt2gghycjvm.html

[S16] C：位操作置位
来源：http://dali.hywenlv.cn/Article/details/gt2alzaknly.html

x |= (1 << 3);
来源：http://dali.chenzaomai.com/Article/details/gt2zgecfckt.html

[S17] C：安全拼接字符串
来源：http://dali.fzhhl.top/Article/details/gt2gtglmtgm.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.guowangkeji.top/Article/details/gt2lvoqpxnv.html

[S18] C：命令行参数
来源：http://dali.dianchejie.cn/Article/details/gt2rlcsivzi.html

int main(int argc, char **argv)
来源：http://dali.jinqigfzy.top/Article/details/gt2gntwxjsb.html

[S19] C：快速排序
来源：http://dali.snrcjt.cn/Article/details/gt2dosidywz.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.meibo888.top/Article/details/gt2rosnwcxo.html

[S20] C：二分查找
来源：http://dali.9152youxi.cn/Article/details/gt2cpdlwsgw.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.xziqi.cn/Article/details/gt2sngjielc.html

[S21] C：字符类别判断
来源：http://dali.gzhubu.top/Article/details/gt2erexzqcs.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.iojbl.cn/Article/details/gt2luepjwoj.html

[S22] C：字符串转数字
来源：http://dali.mhx1999.top/Article/details/gt2auikcjnx.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.xziqi.cn/Article/details/gt2vxqnmfdp.html

[S23] C：随机数
来源：http://dali.daxiang520.top/Article/details/gt2uogzqgxf.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.gzhubu.top/Article/details/gt2zqyygntx.html

[S24] C：获取本地时间
来源：http://dali.kuanghao11.cn/Article/details/gt2vvrpeipo.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.tianlin.xyz/Article/details/gt2qzivszda.html

[S25] C：内存拷贝
来源：http://dali.sysykeji.top/Article/details/gt2rtviafrt.html

memcpy(dst, src, n);
来源：http://dali.9152youxi.cn/Article/details/gt2zqpkihuf.html

[S26] C：内存清零
来源：http://dali.zhongyouzk.top/Article/details/gt2azsprrwl.html

memset(a, 0, sizeof a);
来源：http://dali.zhiwuduotai.top/Article/details/gt2iopevkga.html

[S27] C：定义常量
来源：http://dali.sufxvd.cn/Article/details/gt2tpjbkqta.html

const double PI = 3.14159;
来源：http://dali.shzxlz.cn/Article/details/gt2stvjtscs.html

[S28] C：静态变量
来源：http://dali.jqgufenzy.top/Article/details/gt2vvzcqvmp.html

static int counter = 0;
来源：http://dali.yongpay.top/Article/details/gt2djcctyfo.html

[S29] C：变参函数
来源：http://dali.ppjwa.cn/Article/details/gt2qfrotzat.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.guannengcc.top/Article/details/gt2lvmrkgtm.html

[S30] C：头文件保护
来源：http://dali.yuanzhike.top/Article/details/gt2idcxtltp.html

#ifndef X_H
来源：http://dali.jinqigfzy.top/Article/details/gt2rxrmurxk.html

#define X_H
来源：http://dali.sxryk.cn/Article/details/gt2xcorlfga.html

#endif
来源：http://dali.aibaodan.cn/Article/details/gt2utmhmayw.html

[S31] C++：Hello World
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pkqsrgbo.html

#include <iostream>
来源：http://dali.xylfe.cn/Article/details/gt2hkyxmpxg.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.haohaochexian.top/Article/details/gt2ugunrsfs.html

[S32] C++：字符串
来源：http://dali.chenzaomai.com/Article/details/gt2eoczafkw.html

std::string s = "hi";  s += "!";
来源：http://dali.jlsjyb.cn/Article/details/gt2ijvhtnkr.html

[S33] C++：vector 增删
来源：http://dali.cucudq.cn/Article/details/gt2ckapmpol.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.birdmap.top/Article/details/gt2dutbsrpb.html

[S34] C++：遍历 vector
来源：http://dali.xinyue.icu/Article/details/gt2bscneiou.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.guannengcc.top/Article/details/gt2xqtmrdps.html

[S35] C++：map
来源：http://dali.yj20258888.top/Article/details/gt2mxvymhtn.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yj20258888.top/Article/details/gt2jhavjmns.html

[S36] C++：unordered_map
来源：http://dali.xziqi.cn/Article/details/gt2eelclinz.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.fzhhl.top/Article/details/gt2ebzgayzv.html

[S37] C++：set
来源：http://dali.iojbl.cn/Article/details/gt2lkawdxbv.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.daria6918.cn/Article/details/gt2rzdhlmtq.html

[S38] C++：排序
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hakacjbf.html

std::sort(v.begin(), v.end());
来源：http://dali.yvedp.cn/Article/details/gt2jywxzpjh.html

[S39] C++：自定义比较器排序
来源：http://dali.sxryk.cn/Article/details/gt2cnxzrtqy.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.hnqzz.top/Article/details/gt2msbbertx.html

[S40] C++：查找元素
来源：http://dali.xuanzx.com/Article/details/gt2tpzbsoeu.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.kuanghao11.cn/Article/details/gt2cgpsjnyd.html

[S41] C++：类与构造函数
来源：http://dali.yangfankeji.com/Article/details/gt2ivnrebum.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.shuidangran.top/Article/details/gt2hzuezeuq.html

[S42] C++：继承与虚函数
来源：http://dali.smart0.xyz/Article/details/gt2zouiviku.html

class B : public Base { public: void f() override {} };
来源：http://dali.redwolf501.top/Article/details/gt2ctardfmb.html

[S43] C++：智能指针
来源：http://dali.yj202588.top/Article/details/gt2vtxzezqm.html

auto p = std::make_unique<int>(5);
来源：http://dali.yangfankeji.com/Article/details/gt2mikivykp.html

[S44] C++：引用传参
来源：http://dali.wangdashe.top/Article/details/gt2rojqbcgx.html

void inc(int &x) { ++x; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kuibyaje.html

[S45] C++：lambda
来源：http://dali.hysaishi.cn/Article/details/gt2nfmjuwsw.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.0kj1m.cn/Article/details/gt2tlxjbswk.html

[S46] C++：函数模板
来源：http://dali.ppjwa.cn/Article/details/gt2pbjmsmga.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.cdnleiting.top/Article/details/gt2twhlycfn.html

[S47] C++：结构化绑定遍历
来源：http://dali.xuanzx.com/Article/details/gt2sdayqbzo.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.chenzaomai.com/Article/details/gt2umxqcljt.html

[S48] C++：逐行读文件
来源：http://dali.jinqigufen.top/Article/details/gt2qywvwbup.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mbvjzjbf.html

while (std::getline(in, line)) { }
来源：http://dali.bjfxy.top/Article/details/gt2fdrdubks.html

[S49] C++：写文件
来源：http://dali.shzxlz.cn/Article/details/gt2qqkpjuna.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.bjfxy.top/Article/details/gt2gyhkhaun.html

[S50] C++：格式化数字
来源：http://dali.dianchejie.cn/Article/details/gt2npbjkkpa.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bubykbim.html

[S51] C++：显式类型转换
来源：http://dali.fengsongda.top/Article/details/gt2qhcegeuc.html

static_cast<double>(a) / b
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hoquegoz.html

[S52] C++：const 与 noexcept
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hfjzaiay.html

int size() const noexcept { return n_; }
来源：http://dali.iojbl.cn/Article/details/gt2wzeoyrdr.html

[S53] C++：移动语义
来源：http://dali.gogol.net.cn/Article/details/gt2fmifajxs.html

std::vector<int> w = std::move(v);
来源：http://dali.vqdsnc.cn/Article/details/gt2vygduzyx.html

[S54] C++：异常处理
来源：http://dali.chenjidiqi.icu/Article/details/gt2tfwxsuax.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2syqrnmre.html

[S55] C++：结构化绑定
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mvpthuho.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.sysykeji.top/Article/details/gt2apxrspuy.html

[S56] C++：optional
来源：http://dali.zhixingplan.top/Article/details/gt2rlxewxnb.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.jqgfzy.top/Article/details/gt2hnqoclqg.html

[S57] C++：编译期常量
来源：http://dali.yangfankeji.com/Article/details/gt2pridadoa.html

constexpr int N = 10;
来源：http://dali.smart0.xyz/Article/details/gt2xydkosza.html

[S58] C++：命名空间
来源：http://dali.dashuyun.cn/Article/details/gt2ufqmkvlf.html

namespace ns { int f() { return 1; } }
来源：http://dali.hammf.cn/Article/details/gt2wrpommes.html

[S59] C++：静态断言
来源：http://dali.gaohongyu789.top/Article/details/gt2pbeezhjs.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.xuetiantiany.cn/Article/details/gt2yosbnkvw.html

[S60] C++：遍历并删除元素
来源：http://dali.aizwys.cn/Article/details/gt2lyuqrcpw.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.tianlin.xyz/Article/details/gt2xglzfhpp.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2iioazixj.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.tianlin.xyz/Article/details/gt2trpggibv.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2zmjrwzje.html

[T01] Kotlin：Hello World
来源：http://dali.gotoacloud.top/Article/details/gt2leaudlvc.html

println("Hello")
来源：http://dali.sufxvd.cn/Article/details/gt2fytwnzep.html

[T02] Kotlin：变量
来源：http://dali.cucudq.cn/Article/details/gt2rvoctmbp.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.xinyue.icu/Article/details/gt2hupvymhr.html

[T03] Kotlin：字符串模板
来源：http://dali.aizwys.cn/Article/details/gt2juzbhjqn.html

"值: $b"
来源：http://dali.sweek.top/Article/details/gt2cdavbsqr.html

[T04] Kotlin：空安全
来源：http://dali.daria6918.cn/Article/details/gt2phaiwhuc.html

val n: String? = null;  n?.length
来源：http://dali.hnxiangtu.top/Article/details/gt2yakhqjjk.html

[T05] Kotlin：when 表达式
来源：http://dali.snrcjt.cn/Article/details/gt2cwyyoiep.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhengqikj.top/Article/details/gt2qychgozn.html

[T06] Kotlin：集合映射
来源：http://dali.guannengcc.top/Article/details/gt2mrhcefly.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.yongpay.top/Article/details/gt2zkoxmyys.html

[T07] Kotlin：集合过滤
来源：http://dali.zhengqikj.top/Article/details/gt2yvvqgqti.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bmpgkojc.html

[T08] Kotlin：数据类
来源：http://dali.daria6918.cn/Article/details/gt2fdlxemij.html

data class User(val name: String, val age: Int)
来源：http://dali.cdnleiting.top/Article/details/gt2zllqxpos.html

[T09] Kotlin：扩展函数
来源：http://dali.xuanzx.com/Article/details/gt2bffzhjwj.html

fun String.exclaim() = this + "!"
来源：http://dali.guowangkeji.top/Article/details/gt2kyexvvsq.html

[T10] Kotlin：默认参数
来源：http://dali.zhongyouzk.top/Article/details/gt2imtmrxcq.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.xinyue.icu/Article/details/gt2vczujoza.html

[T11] Kotlin：协程
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zfepkogh.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.redwolf501.top/Article/details/gt2xzxfzncz.html

[T12] Kotlin：解构声明
来源：http://dali.shzxlz.cn/Article/details/gt2apnptmnm.html

val (a, b) = Pair(1, 2)
来源：http://dali.ybcxt.top/Article/details/gt2qzocrzrz.html

[T13] Kotlin：只读 Map
来源：http://dali.xylfe.cn/Article/details/gt2ipwbxzew.html

val m = mapOf("a" to 1)
来源：http://dali.ivvv.top/Article/details/gt2andiwvqc.html

[T14] Kotlin：循环
来源：http://dali.sysykeji.top/Article/details/gt2zxctjulk.html

for (i in 1..10) println(i)
来源：http://dali.hongshengwenyu.top/Article/details/gt2xdruckin.html

[T15] Kotlin：接口
来源：http://dali.nanxinkj.top/Article/details/gt2qkqhzddd.html

interface Shape { fun area(): Double }
来源：http://dali.shzxlz.cn/Article/details/gt2ceiwznwz.html

[T16] Swift：Hello World
来源：http://dali.jiagoushi.top/Article/details/gt2pfhphwrw.html

print("Hello")
来源：http://dali.yueranfly.top/Article/details/gt2ktwittdn.html

[T17] Swift：变量与常量
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tzufbdgi.html

var a = 1;  let b = 2
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bhrqcevy.html

[T18] Swift：字符串插值
来源：http://dali.cucudq.cn/Article/details/gt2xoogkwfm.html

"值: \(b)"
来源：http://dali.quarkkingdee.top/Article/details/gt2xxbkbrrv.html

[T19] Swift：可选绑定
来源：http://dali.hammf.cn/Article/details/gt2menokyht.html

if let n = opt { print(n) }
来源：http://dali.yanxiufei.cn/Article/details/gt2paaewhzp.html

[T20] Swift：数组操作
来源：http://dali.nanxinkj.top/Article/details/gt2aedhojts.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.snrcjt.cn/Article/details/gt2ezzggimf.html

[T21] Swift：遍历
来源：http://dali.gogol.net.cn/Article/details/gt2axyltztg.html

for x in a { print(x) }
来源：http://dali.jqgufenzy.top/Article/details/gt2itfckvtq.html

[T22] Swift：字典
来源：http://dali.sysykeji.top/Article/details/gt2maohmtan.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.yj20258.top/Article/details/gt2adxzlmez.html

[T23] Swift：函数
来源：http://dali.xylfe.cn/Article/details/gt2runebgzh.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhongyouzk.top/Article/details/gt2kxdhrjxu.html

[T24] Swift：闭包
来源：http://dali.yueranfly.top/Article/details/gt2lyxcokip.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.sweek.top/Article/details/gt2vwjxcrds.html

[T25] Swift：结构体
来源：http://dali.hnxiangtu.top/Article/details/gt2thyibifn.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2quzkitrz.html

[T26] Swift：类与重写
来源：http://dali.birdmap.top/Article/details/gt2llqwmyzw.html

class A: Base { override func f() {} }
来源：http://dali.0kj1m.cn/Article/details/gt2xjeeufqg.html

[T27] Swift：错误处理
来源：http://dali.iojbl.cn/Article/details/gt2svzwtyky.html

do { try f() } catch { print(error) }
来源：http://dali.havefunace.top/Article/details/gt2zdiydymd.html

[T28] Swift：枚举
来源：http://dali.yvedp.cn/Article/details/gt2xjjnvwgr.html

enum Color { case red, green }
来源：http://dali.aizwys.cn/Article/details/gt2scsjrypk.html

[T29] Swift：guard 提前返回
来源：http://dali.316326.xyz/Article/details/gt2atutmmzn.html

guard let x = opt else { return }
来源：http://dali.ehwqpu.com/Article/details/gt2wpqjgsnz.html

[T30] Swift：协议
来源：http://dali.cashguo.top/Article/details/gt2wynhwtoo.html

protocol Shape { func area() -> Double }
来源：http://dali.zhoulong.xyz/Article/details/gt2azvyvunl.html

[T31] Lua：Hello World
来源：http://dali.tian-w.cn/Article/details/gt2movukral.html

print("Hello")
来源：http://dali.shangyingyoupin.top/Article/details/gt2jfnihgcx.html

[T32] Lua：局部变量
来源：http://dali.zhiwuduotai.top/Article/details/gt2yxgjudhi.html

local a = 1
来源：http://dali.yonumen.top/Article/details/gt2oulforwl.html

[T33] Lua：表（数组）
来源：http://dali.ppjwa.cn/Article/details/gt2rsmhnknt.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mkwossqw.html

[T34] Lua：遍历表
来源：http://dali.snrcjt.cn/Article/details/gt2rtquxgle.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2snvspmsj.html

[T35] Lua：字典表
来源：http://dali.zhengqikj.top/Article/details/gt2qzfuucjw.html

local d = { a = 1 };  d.b = 2
来源：http://dali.sysykeji.top/Article/details/gt2udzgrguv.html

[T36] Lua：函数
来源：http://dali.smart0.xyz/Article/details/gt2ivghexnc.html

function add(a, b) return a + b end
来源：http://dali.sxryk.cn/Article/details/gt2nyzqjlsw.html

[T37] Lua：字符串拼接
来源：http://dali.guannengcc.top/Article/details/gt2kpesqjlc.html

"a" .. "b"
来源：http://dali.xylfe.cn/Article/details/gt2uvomppgi.html

[T38] Lua：条件
来源：http://dali.zhiwuduotai.top/Article/details/gt2qfociagk.html

if x > 0 then print("正") end
来源：http://dali.hysaishi.cn/Article/details/gt2uoqckdnb.html

[T39] Lua：模式匹配
来源：http://dali.jinghuilouyu.cn/Article/details/gt2strpuvex.html

string.find(s, "%d+")
来源：http://dali.chenzaomai.com/Article/details/gt2rsdbdlox.html

[T40] Lua：元表
来源：http://dali.hywenlv.cn/Article/details/gt2vwygdcya.html

setmetatable({}, { __index = base })
来源：http://dali.sufxvd.cn/Article/details/gt2plkotiyq.html

[T41] Perl：Hello World
来源：http://dali.gotoacloud.top/Article/details/gt2lrbyeuyo.html

print "Hello\n";
来源：http://dali.jqgfzy.top/Article/details/gt2aonnwnfe.html

[T42] Perl：变量类型
来源：http://dali.yanxiufei.cn/Article/details/gt2iuxbsyoe.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.xinyue.icu/Article/details/gt2vormpqhb.html

[T43] Perl：字符串插值
来源：http://dali.ivvv.top/Article/details/gt2vumsnspm.html

"值: $a"
来源：http://dali.sweek.top/Article/details/gt2kvwmotiq.html

[T44] Perl：条件
来源：http://dali.yonumen.top/Article/details/gt2aqleqhgv.html

if ($a > 0) { print "正"; }
来源：http://dali.svipenyu.cn/Article/details/gt2ibsrvocp.html

[T45] Perl：数组遍历
来源：http://dali.yanxiufei.cn/Article/details/gt2lzlqjelm.html

for my $x (@arr) { print $x; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2uaerijkf.html

[T46] Perl：哈希操作
来源：http://dali.xuetiantiany.cn/Article/details/gt2xuxvbqbc.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.cqqwz.cn/Article/details/gt2xuevkhvf.html

[T47] Perl：正则捕获
来源：http://dali.xylfe.cn/Article/details/gt2ggudvune.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.gaohongyu789.top/Article/details/gt2ygrxjsbo.html

[T48] Perl：正则替换
来源：http://dali.ehwqpu.com/Article/details/gt2papdwjon.html

$s =~ s/old/new/g;
来源：http://dali.wangshuangyany.cn/Article/details/gt2oweupqdk.html

[T49] Perl：函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rkmjaeyx.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qzvbezzz.html

[T50] Perl：逐行读文件
来源：http://dali.hysaishi.cn/Article/details/gt2sxuihcxi.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.jiagoushi.top/Article/details/gt2ghjpjzob.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2jjxusycw.html

[T51] Scala：Hello World
来源：http://dali.dianchejie.cn/Article/details/gt2lbvguort.html

println("Hello")
来源：http://dali.yvedp.cn/Article/details/gt2vmenyece.html

[T52] Scala：变量
来源：http://dali.shzxlz.cn/Article/details/gt2eyhuxkso.html

val a = 1;  var b = 2
来源：http://dali.316326.xyz/Article/details/gt2jgolynvh.html

[T53] Scala：字符串插值
来源：http://dali.yangfankeji.com/Article/details/gt2uritcybl.html

s"值: $b"
来源：http://dali.sysykeji.top/Article/details/gt2zellljft.html

[T54] Scala：集合映射
来源：http://dali.gogol.net.cn/Article/details/gt2ezojtzax.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.yj20258.top/Article/details/gt2rtjdrdwh.html

[T55] Scala：集合过滤
来源：http://dali.haohaochexian.top/Article/details/gt2iytzopkh.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.tanke756.top/Article/details/gt2jnjcjeow.html

[T56] Scala：样例类
来源：http://dali.9152youxi.cn/Article/details/gt2izrcnsrl.html

case class User(name: String, age: Int)
来源：http://dali.hfpthk.cn/Article/details/gt2xfhjwipd.html

[T57] Scala：模式匹配
来源：http://dali.birdmap.top/Article/details/gt2piqmfwju.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zdqjudy.top/Article/details/gt2cnvbusgs.html

[T58] Scala：函数定义
来源：http://dali.daxiang520.top/Article/details/gt2edhgscum.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.ppjwa.cn/Article/details/gt2mihuzrur.html

[T59] Scala：循环
来源：http://dali.redwolf501.top/Article/details/gt2bpgfkvne.html

for (i <- 1 to 10) println(i)
来源：http://dali.mhx1999.top/Article/details/gt2iesaqwyp.html

[T60] Scala：折叠
来源：http://dali.haohaochexian.top/Article/details/gt2osyyicjh.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.chenjidiqi.icu/Article/details/gt2jvtpvoyu.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2fhzyvagk.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.gaohongyu789.top/Article/details/gt2yjhxyrpg.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2fhmnojko.html

[U01] Py：创建虚拟环境
来源：http://dali.chenjidiqi.icu/Article/details/gt2eflcubth.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhongyouzk.top/Article/details/gt2nzfenxdi.html

[U02] Py：导出 / 安装依赖
来源：http://dali.sweek.top/Article/details/gt2msnjjmva.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.yuanzhike.top/Article/details/gt2aaeghwon.html

[U03] Py：加载 .env 配置
来源：http://dali.aizwys.cn/Article/details/gt2couyrkwo.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.andypj.xyz/Article/details/gt2lzelmukt.html

[U04] Py：变量调试打印
来源：http://dali.kuanghao11.cn/Article/details/gt2jafxubdp.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.nanxinkj.top/Article/details/gt2dxdmowcn.html

[U05] Py：列表去重且保序
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2iqllfdzi.html

list(dict.fromkeys(arr))
来源：http://dali.zhengqikj.top/Article/details/gt2sjsgumyv.html

[U06] Py：合并两个字典
来源：http://dali.snrcjt.cn/Article/details/gt2udgzsedl.html

{**a, **b}
来源：http://dali.yueranfly.top/Article/details/gt2easwtkvs.html

[U07] Py：反转字典键值
来源：http://dali.zhongyouzk.top/Article/details/gt2ebmxuhcr.html

{v: k for k, v in d.items()}
来源：http://dali.zycfv.cn/Article/details/gt2ophktlmt.html

[U08] Py：展平二维列表
来源：http://dali.guannengcc.top/Article/details/gt2ojaenbnr.html

[y for x in nested for y in x]
来源：http://dali.9152youxi.cn/Article/details/gt2pjdbvodi.html

[U09] Py：字典取最大值的键
来源：http://dali.dianchejie.cn/Article/details/gt2yvntnlop.html

max(d, key=d.get)
来源：http://dali.xylfe.cn/Article/details/gt2bdokcndn.html

[U10] Py：按值排序字典
来源：http://dali.fzhhl.top/Article/details/gt2qimqrndo.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.sufxvd.cn/Article/details/gt2intilcbq.html

[U11] Py：生成器表达式
来源：http://dali.pengpengdd.cyou/Article/details/gt2xcfbfgnw.html

(x * 2 for x in arr)
来源：http://dali.yuanzhike.top/Article/details/gt2kecghwft.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.smart0.xyz/Article/details/gt2zrnspkae.html

Counter(arr).most_common(3)
来源：http://dali.chenjidiqi.icu/Article/details/gt2egaexekf.html

[U13] Py：固定长度队列
来源：http://dali.gzhubu.top/Article/details/gt2boozcmyf.html

deque(maxlen=10)
来源：http://dali.xuanzx.com/Article/details/gt2augaqiuv.html

[U14] Py：分组收集到列表
来源：http://dali.xinyue.icu/Article/details/gt2wfdwrzat.html

defaultdict(list)
来源：http://dali.yuxming.cn/Article/details/gt2wdixcrnt.html

[U15] Py：高精度计时
来源：http://dali.fengsongda.top/Article/details/gt2adkzgzeb.html

t = time.perf_counter()
来源：http://dali.xylfe.cn/Article/details/gt2tuqbhmuo.html

[U16] Py：命令行参数解析
来源：http://dali.yuxming.cn/Article/details/gt2amtujamt.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.hongshengwenyu.top/Article/details/gt2exjdzpqr.html

[U17] Py：初始化日志
来源：http://dali.yj202588.top/Article/details/gt2kdygzusp.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.jyoumei.cn/Article/details/gt2wfbhzlha.html

[U18] Py：预编译正则
来源：http://dali.nwbrower.top/Article/details/gt2zjxibkag.html

pat = re.compile(r"\d+")
来源：http://dali.cashguo.top/Article/details/gt2ehbadcwe.html

[U19] Py：正则替换带回调
来源：http://dali.yonumen.top/Article/details/gt2xsybjjrq.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.wangshuangyany.cn/Article/details/gt2mqableal.html

[U20] Py：缓存函数结果
来源：http://dali.hongshengwenyu.top/Article/details/gt2rkcnyvti.html

@functools.lru_cache(maxsize=None)
来源：http://dali.pycfn.com/Article/details/gt2wvyqphgl.html

[U21] Py：自定义上下文管理器
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nargudxy.html

@contextlib.contextmanager
来源：http://dali.gotoacloud.top/Article/details/gt2trzcirli.html

[U22] Py：矩阵转置
来源：http://dali.xziqi.cn/Article/details/gt2okjeehkj.html

list(zip(*m))
来源：http://dali.hywenlv.cn/Article/details/gt2zcasgmqz.html

[U23] Py：分块读取大文件
来源：http://dali.shuidangran.top/Article/details/gt2iadpktkt.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.yongpay.top/Article/details/gt2tfrvrxdb.html

[U24] Py：路径操作
来源：http://dali.xziqi.cn/Article/details/gt2ndtyckyo.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.redwolf501.top/Article/details/gt2xunvnnsm.html

[U25] Py：CSV 按字典读
来源：http://dali.cucudq.cn/Article/details/gt2ugqztssu.html

csv.DictReader(f)
来源：http://dali.yj20258.top/Article/details/gt2dwutmbgj.html

[U26] Py：并发下载
来源：http://dali.yonumen.top/Article/details/gt2sajymkbu.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.ppjwa.cn/Article/details/gt2nqvsnmdx.html

[U27] Py：异步 HTTP
来源：http://dali.pycfn.com/Article/details/gt2wvaqjgum.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.havefunace.top/Article/details/gt2frhgjapb.html

[U28] Py：类型别名
来源：http://dali.zhixingplan.top/Article/details/gt2eketoeow.html

UserId = int
来源：http://dali.cqqwz.cn/Article/details/gt2wdqmguna.html

[U29] Py：属性校验
来源：http://dali.haohaochexian.top/Article/details/gt2ynoczoye.html

@property 与 @x.setter 配合
来源：http://dali.yueranfly.top/Article/details/gt2nmjbnfal.html

[U30] Py：数据类
来源：http://dali.haohaochexian.top/Article/details/gt2ioizbltu.html

@dataclass(slots=True)
来源：http://dali.bjfxy.top/Article/details/gt2jyycmhod.html

[U31] Py：单测
来源：http://dali.jiagoushi.top/Article/details/gt2uwyyynht.html

python -m pytest -q
来源：http://dali.ppjwa.cn/Article/details/gt2kzyimyzh.html

[U32] Py：代码格式化
来源：http://dali.havefunace.top/Article/details/gt2quxcgpni.html

ruff format . && ruff check --fix .
来源：http://dali.hfpthk.cn/Article/details/gt2nrxumpnu.html


<!-- 参考信息 -->