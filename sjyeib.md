代发 wailian999

strlen(s)
来源：http://dali.hongshengwenyu.top/Article/details/gt2ojcgdyfi.html

[S06] C：字符串比较
来源：http://dali.gzhubu.top/Article/details/gt2iatoipnh.html

strcmp(a, b) == 0
来源：http://dali.ppjwa.cn/Article/details/gt2ugtunjwk.html

[S07] C：数组遍历求和
来源：http://dali.yanxiufei.cn/Article/details/gt2kedgseoi.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.pengpengdd.cyou/Article/details/gt2wnztvxfp.html

[S08] C：动态内存分配与释放
来源：http://dali.daxiang520.top/Article/details/gt2ijxactvy.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.redwolf501.top/Article/details/gt2nrisbwqb.html

[S09] C：结构体定义与初始化
来源：http://dali.yongpay.top/Article/details/gt2zgcxbmlf.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.ybcxt.top/Article/details/gt2nvgyvaca.html

[S10] C：指针与解引用
来源：http://dali.zhiwuduotai.top/Article/details/gt2edrptkxz.html

int *p = &a;  *p = 5;
来源：http://dali.hnqzz.top/Article/details/gt2vuyohiqt.html

[S11] C：逐行读文件
来源：http://dali.jyoumei.cn/Article/details/gt2bhbeamfo.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.hywenlv.cn/Article/details/gt2faksgqmr.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.chenjidiqi.icu/Article/details/gt2dpkrvljt.html

fclose(f);
来源：http://dali.cucudq.cn/Article/details/gt2uhappwmi.html

[S12] C：写文件
来源：http://dali.ivvv.top/Article/details/gt2bhkuhimy.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.xuetiantiany.cn/Article/details/gt2muklyhjj.html

[S13] C：宏定义
来源：http://dali.tanke756.top/Article/details/gt2gmuziaqh.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.nwbrower.top/Article/details/gt2lipjgdgd.html

[S14] C：枚举
来源：http://dali.ydzc1.top/Article/details/gt2luuaiamy.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.yanxiufei.cn/Article/details/gt2omgrvxib.html

[S15] C：类型转换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hdlgrlbq.html

(double) a / b
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bwdkjbpm.html

[S16] C：位操作置位
来源：http://dali.yangfankeji.com/Article/details/gt2huwnbukg.html

x |= (1 << 3);
来源：http://dali.hywenlv.cn/Article/details/gt2hmddeoxa.html

[S17] C：安全拼接字符串
来源：http://dali.hywenlv.cn/Article/details/gt2oylutnni.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.yuxming.cn/Article/details/gt2vjvnqpym.html

[S18] C：命令行参数
来源：http://dali.yangfankeji.com/Article/details/gt2zqjbbswp.html

int main(int argc, char **argv)
来源：http://dali.vqdsnc.cn/Article/details/gt2zlqdfnqm.html

[S19] C：快速排序
来源：http://dali.sweek.top/Article/details/gt2yxomzlbu.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.tian-w.cn/Article/details/gt2gxnhmmec.html

[S20] C：二分查找
来源：http://dali.jianghu66.top/Article/details/gt2hmvecocs.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.dianchejie.cn/Article/details/gt2oolimvdw.html

[S21] C：字符类别判断
来源：http://dali.guannengcc.top/Article/details/gt2zevqmrhp.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhoulong.xyz/Article/details/gt2jzlephwb.html

[S22] C：字符串转数字
来源：http://dali.yueranfly.top/Article/details/gt2idmjejxp.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.yj20258.top/Article/details/gt2nclontzl.html

[S23] C：随机数
来源：http://dali.andypj.xyz/Article/details/gt2kpakfjqw.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.ppjwa.cn/Article/details/gt2nlxekxsi.html

[S24] C：获取本地时间
来源：http://dali.hnqzz.top/Article/details/gt2ieotrjgl.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.cashguo.top/Article/details/gt2nfpnnkzz.html

[S25] C：内存拷贝
来源：http://dali.iojbl.cn/Article/details/gt2ljycsaiv.html

memcpy(dst, src, n);
来源：http://dali.sufxvd.cn/Article/details/gt2oykxqtte.html

[S26] C：内存清零
来源：http://dali.ybcxt.top/Article/details/gt2svxwpqbw.html

memset(a, 0, sizeof a);
来源：http://dali.hywenlv.cn/Article/details/gt2frzuyzhf.html

[S27] C：定义常量
来源：http://dali.jlsjyb.cn/Article/details/gt2paqxbosi.html

const double PI = 3.14159;
来源：http://dali.wangdashe.top/Article/details/gt2plmtkgah.html

[S28] C：静态变量
来源：http://dali.shuidangran.top/Article/details/gt2jfcbucxs.html

static int counter = 0;
来源：http://dali.dianchejie.cn/Article/details/gt2iduntpud.html

[S29] C：变参函数
来源：http://dali.hysaishi.cn/Article/details/gt2pyajnifl.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.hammf.cn/Article/details/gt2zsjpgviz.html

[S30] C：头文件保护
来源：http://dali.fzhhl.top/Article/details/gt2uavuywwy.html

#ifndef X_H
来源：http://dali.cqqwz.cn/Article/details/gt2keenrwkm.html

#define X_H
来源：http://dali.fengsongda.top/Article/details/gt2sohjorrf.html

#endif
来源：http://dali.shzxlz.cn/Article/details/gt2vebzdxqj.html

[S31] C++：Hello World
来源：http://dali.dashuyun.cn/Article/details/gt2jhonnfvt.html

#include <iostream>
来源：http://dali.yueranfly.top/Article/details/gt2yrhcwqsx.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.yanxiufei.cn/Article/details/gt2hxklxcbd.html

[S32] C++：字符串
来源：http://dali.tianlin.xyz/Article/details/gt2ipyhpbpl.html

std::string s = "hi";  s += "!";
来源：http://dali.guowangkeji.top/Article/details/gt2hxfdafuh.html

[S33] C++：vector 增删
来源：http://dali.sysykeji.top/Article/details/gt2wlsvehqj.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.guannengcc.top/Article/details/gt2lqlrusqh.html

[S34] C++：遍历 vector
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rtclnkkl.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.snrcjt.cn/Article/details/gt2kdcievou.html

[S35] C++：map
来源：http://dali.cheryme.top/Article/details/gt2lgkdwqtm.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.cdnleiting.top/Article/details/gt2vdcsakhd.html

[S36] C++：unordered_map
来源：http://dali.havefunace.top/Article/details/gt2tijpqclm.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.xuetiantiany.cn/Article/details/gt2aqrzmqto.html

[S37] C++：set
来源：http://dali.sysykeji.top/Article/details/gt2ttuvuwtc.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhiwuduotai.top/Article/details/gt2xmrhejbw.html

[S38] C++：排序
来源：http://dali.andypj.xyz/Article/details/gt2oddnsgoi.html

std::sort(v.begin(), v.end());
来源：http://dali.xziqi.cn/Article/details/gt2gatwmqcl.html

[S39] C++：自定义比较器排序
来源：http://dali.yanxiufei.cn/Article/details/gt2tialhisu.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xrhmicse.html

[S40] C++：查找元素
来源：http://dali.gotoacloud.top/Article/details/gt2qiqkmayw.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.sweek.top/Article/details/gt2dniydrpj.html

[S41] C++：类与构造函数
来源：http://dali.xinyue.icu/Article/details/gt2bnfqpdjh.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.hammf.cn/Article/details/gt2cyjfzkgc.html

[S42] C++：继承与虚函数
来源：http://dali.feifeiyinyue.top/Article/details/gt2oifjqlzg.html

class B : public Base { public: void f() override {} };
来源：http://dali.hongshengwenyu.top/Article/details/gt2njhwqfts.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2qzczjtch.html

auto p = std::make_unique<int>(5);
来源：http://dali.cqqwz.cn/Article/details/gt2edqxuxcy.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2mgphdjos.html

void inc(int &x) { ++x; }
来源：http://dali.meibo888.top/Article/details/gt2jiyudmck.html

[S45] C++：lambda
来源：http://dali.cheryme.top/Article/details/gt2dfnshnaw.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.yonumen.top/Article/details/gt2rmythwov.html

[S46] C++：函数模板
来源：http://dali.cucudq.cn/Article/details/gt2qqvuuofn.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2murohiei.html

[S47] C++：结构化绑定遍历
来源：http://dali.jianghu66.top/Article/details/gt2gdjfeqwo.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.chenlongwang.top/Article/details/gt2eoxuubua.html

[S48] C++：逐行读文件
来源：http://dali.hywenlv.cn/Article/details/gt2iyvsmugd.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.gaohongyu789.top/Article/details/gt2vkmjbhvo.html

while (std::getline(in, line)) { }
来源：http://dali.fengsongda.top/Article/details/gt2gyntwldr.html

[S49] C++：写文件
来源：http://dali.yj202588.top/Article/details/gt2axdtvbig.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.sxryk.cn/Article/details/gt2okllzxbl.html

[S50] C++：格式化数字
来源：http://dali.yonumen.top/Article/details/gt2vskjszet.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.yvedp.cn/Article/details/gt2xvkbnfim.html

[S51] C++：显式类型转换
来源：http://dali.chenzaomai.com/Article/details/gt2aioraill.html

static_cast<double>(a) / b
来源：http://dali.jlsjyb.cn/Article/details/gt2mdltagya.html

[S52] C++：const 与 noexcept
来源：http://dali.xylfe.cn/Article/details/gt2thypghhx.html

int size() const noexcept { return n_; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2aylularl.html

[S53] C++：移动语义
来源：http://dali.daxiang520.top/Article/details/gt2xjopvqxu.html

std::vector<int> w = std::move(v);
来源：http://dali.xylfe.cn/Article/details/gt2eujhegtl.html

[S54] C++：异常处理
来源：http://dali.quarkkingdee.top/Article/details/gt2nwniytcg.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.yonumen.top/Article/details/gt2pbtxjxlb.html

[S55] C++：结构化绑定
来源：http://dali.hfpthk.cn/Article/details/gt2tqagfmdj.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bpenkwrz.html

[S56] C++：optional
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2penxtxfe.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dlyheqwy.html

[S57] C++：编译期常量
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2iapbwdiz.html

constexpr int N = 10;
来源：http://dali.cucudq.cn/Article/details/gt2hbygsjyl.html

[S58] C++：命名空间
来源：http://dali.c1oappe.top/Article/details/gt2nmvczylp.html

namespace ns { int f() { return 1; } }
来源：http://dali.ivvv.top/Article/details/gt2iqbxjlrk.html

[S59] C++：静态断言
来源：http://dali.dianchejie.cn/Article/details/gt2iqncbytn.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.jyoumei.cn/Article/details/gt2shbkviey.html

[S60] C++：遍历并删除元素
来源：http://dali.0kj1m.cn/Article/details/gt2huqldfiw.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.fzhhl.top/Article/details/gt2flqxdvtl.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2dgblfxuh.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zycfv.cn/Article/details/gt2mercbsbe.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gt2nemzavmf.html

[T01] Kotlin：Hello World
来源：http://dali.kuanghao11.cn/Article/details/gt2phjwyngz.html

println("Hello")
来源：http://dali.shuidangran.top/Article/details/gt2fdfmupzt.html

[T02] Kotlin：变量
来源：http://dali.aizwys.cn/Article/details/gt2rkmwmmra.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.cdnleiting.top/Article/details/gt2xdkmakmx.html

[T03] Kotlin：字符串模板
来源：http://dali.shangyingyoupin.top/Article/details/gt2sttkppwi.html

"值: $b"
来源：http://dali.0kj1m.cn/Article/details/gt2iiadsvoc.html

[T04] Kotlin：空安全
来源：http://dali.ehwqpu.com/Article/details/gt2kpwnwxqd.html

val n: String? = null;  n?.length
来源：http://dali.yonumen.top/Article/details/gt2smarfjzt.html

[T05] Kotlin：when 表达式
来源：http://dali.jyoumei.cn/Article/details/gt2bwxnnymb.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.tian-w.cn/Article/details/gt2frjqwbmu.html

[T06] Kotlin：集合映射
来源：http://dali.meibo888.top/Article/details/gt2myuygvza.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zzlltpsh.html

[T07] Kotlin：集合过滤
来源：http://dali.9152youxi.cn/Article/details/gt2ixupqvcv.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.nanxinkj.top/Article/details/gt2dcappplb.html

[T08] Kotlin：数据类
来源：http://dali.hammf.cn/Article/details/gt2wzoftyef.html

data class User(val name: String, val age: Int)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zghxdziw.html

[T09] Kotlin：扩展函数
来源：http://dali.cashguo.top/Article/details/gt2yccnvqrh.html

fun String.exclaim() = this + "!"
来源：http://dali.xylfe.cn/Article/details/gt2zxxixjcj.html

[T10] Kotlin：默认参数
来源：http://dali.316326.xyz/Article/details/gt2uwrgqbjj.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.jlsjyb.cn/Article/details/gt2tyblfyvn.html

[T11] Kotlin：协程
来源：http://dali.pycfn.com/Article/details/gt2ytikmnzh.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.jinqigfzy.top/Article/details/gt2fycnpedg.html

[T12] Kotlin：解构声明
来源：http://dali.yanxiufei.cn/Article/details/gt2hqnmaorm.html

val (a, b) = Pair(1, 2)
来源：http://dali.jinqigufen.top/Article/details/gt2cdevrqol.html

[T13] Kotlin：只读 Map
来源：http://dali.cdnleiting.top/Article/details/gt2xdqwnyvv.html

val m = mapOf("a" to 1)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2iyotyirp.html

[T14] Kotlin：循环
来源：http://dali.pycfn.com/Article/details/gt2gdqbcake.html

for (i in 1..10) println(i)
来源：http://dali.jyoumei.cn/Article/details/gt2cyjymazj.html

[T15] Kotlin：接口
来源：http://dali.zdqjudy.top/Article/details/gt2zkxqwavv.html

interface Shape { fun area(): Double }
来源：http://dali.sxryk.cn/Article/details/gt2rzafiwoo.html

[T16] Swift：Hello World
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wzofrrad.html

print("Hello")
来源：http://dali.hywenlv.cn/Article/details/gt2rgypggbd.html

[T17] Swift：变量与常量
来源：http://dali.hnqzz.top/Article/details/gt2jnthiuta.html

var a = 1;  let b = 2
来源：http://dali.jinqigufen.top/Article/details/gt2fkrcunzg.html

[T18] Swift：字符串插值
来源：http://dali.cdnleiting.top/Article/details/gt2wdqnfrsq.html

"值: \(b)"
来源：http://dali.shangyingyoupin.top/Article/details/gt2hnxjtume.html

[T19] Swift：可选绑定
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ndedqteu.html

if let n = opt { print(n) }
来源：http://dali.ivvv.top/Article/details/gt2loepsngf.html

[T20] Swift：数组操作
来源：http://dali.shuidangran.top/Article/details/gt2gslwlynz.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.aizwys.cn/Article/details/gt2vyhdtcjl.html

[T21] Swift：遍历
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wopbwlml.html

for x in a { print(x) }
来源：http://dali.cucudq.cn/Article/details/gt2kufklqra.html

[T22] Swift：字典
来源：http://dali.c1oappe.top/Article/details/gt2urprrmvn.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.ivvv.top/Article/details/gt2ipdlgbal.html

[T23] Swift：函数
来源：http://dali.ydzc1.top/Article/details/gt2mbzpkvmz.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.xinyue.icu/Article/details/gt2abuvetcu.html

[T24] Swift：闭包
来源：http://dali.haohaochexian.top/Article/details/gt2mgqqjhei.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.hnxiangtu.top/Article/details/gt2cjhedsgf.html

[T25] Swift：结构体
来源：http://dali.hfpthk.cn/Article/details/gt2glcentgo.html

struct P { var x: Int }
来源：http://dali.vqdsnc.cn/Article/details/gt2cuhituhs.html

[T26] Swift：类与重写
来源：http://dali.jiagoushi.top/Article/details/gt2tvjydyhi.html

class A: Base { override func f() {} }
来源：http://dali.gotoacloud.top/Article/details/gt2jnvzuyzp.html

[T27] Swift：错误处理
来源：http://dali.tanke756.top/Article/details/gt2nsrwqaku.html

do { try f() } catch { print(error) }
来源：http://dali.tianlin.xyz/Article/details/gt2hsltxwku.html

[T28] Swift：枚举
来源：http://dali.tanke756.top/Article/details/gt2wmksknvh.html

enum Color { case red, green }
来源：http://dali.guannengcc.top/Article/details/gt2ustliivd.html

[T29] Swift：guard 提前返回
来源：http://dali.daria6918.cn/Article/details/gt2kwjjfmzm.html

guard let x = opt else { return }
来源：http://dali.havefunace.top/Article/details/gt2vdltbbnf.html

[T30] Swift：协议
来源：http://dali.meibo888.top/Article/details/gt2nyfbgbpe.html

protocol Shape { func area() -> Double }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lsftdavz.html

[T31] Lua：Hello World
来源：http://dali.tian-w.cn/Article/details/gt2ombdtekf.html

print("Hello")
来源：http://dali.andypj.xyz/Article/details/gt2frcdzptq.html

[T32] Lua：局部变量
来源：http://dali.dashuyun.cn/Article/details/gt2xixfvabt.html

local a = 1
来源：http://dali.gogol.net.cn/Article/details/gt2trzuqxfg.html

[T33] Lua：表（数组）
来源：http://dali.xziqi.cn/Article/details/gt2uaoxyjky.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mzeafmsg.html

[T34] Lua：遍历表
来源：http://dali.yuanzhike.top/Article/details/gt2erztfnwi.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.gogol.net.cn/Article/details/gt2zgioiezi.html

[T35] Lua：字典表
来源：http://dali.jqgufenzy.top/Article/details/gt2ilovtnsr.html

local d = { a = 1 };  d.b = 2
来源：http://dali.daxiang520.top/Article/details/gt2ssjfpjdd.html

[T36] Lua：函数
来源：http://dali.yj20258.top/Article/details/gt2nqudjtnh.html

function add(a, b) return a + b end
来源：http://dali.wangdashe.top/Article/details/gt2oisvmbff.html

[T37] Lua：字符串拼接
来源：http://dali.havefunace.top/Article/details/gt2uqfubuio.html

"a" .. "b"
来源：http://dali.meibo888.top/Article/details/gt2yazvxdat.html

[T38] Lua：条件
来源：http://dali.feifeiyinyue.top/Article/details/gt2qnlnntrq.html

if x > 0 then print("正") end
来源：http://dali.yueranfly.top/Article/details/gt2ppsujppi.html

[T39] Lua：模式匹配
来源：http://dali.shzxlz.cn/Article/details/gt2nldjbfct.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2gjyyhufh.html

[T40] Lua：元表
来源：http://dali.yonumen.top/Article/details/gt2rjmrigtj.html

setmetatable({}, { __index = base })
来源：http://dali.yj20258888.top/Article/details/gt2khewqhoa.html

[T41] Perl：Hello World
来源：http://dali.yj202588.top/Article/details/gt2cthjfpjx.html

print "Hello\n";
来源：http://dali.pycfn.com/Article/details/gt2ppdvmtmy.html

[T42] Perl：变量类型
来源：http://dali.sysykeji.top/Article/details/gt2bperzzck.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.wangdashe.top/Article/details/gt2btziubkz.html

[T43] Perl：字符串插值
来源：http://dali.yj202588.top/Article/details/gt2hfsnflbj.html

"值: $a"
来源：http://dali.chenjidiqi.icu/Article/details/gt2cvxnwnvz.html

[T44] Perl：条件
来源：http://dali.jlsjyb.cn/Article/details/gt2uwhpfsdj.html

if ($a > 0) { print "正"; }
来源：http://dali.yanxiufei.cn/Article/details/gt2oilajxaw.html

[T45] Perl：数组遍历
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2osuhuigo.html

for my $x (@arr) { print $x; }
来源：http://dali.hnxiangtu.top/Article/details/gt2jevmbips.html

[T46] Perl：哈希操作
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ynvhydrh.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.haohaochexian.top/Article/details/gt2rzbhtxuf.html

[T47] Perl：正则捕获
来源：http://dali.yj202588.top/Article/details/gt2twiunktp.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.yanxiufei.cn/Article/details/gt2vfztgzfi.html

[T48] Perl：正则替换
来源：http://dali.gzhubu.top/Article/details/gt2txtlrzot.html

$s =~ s/old/new/g;
来源：http://dali.andypj.xyz/Article/details/gt2ylvkbwwy.html

[T49] Perl：函数
来源：http://dali.vqdsnc.cn/Article/details/gt2eexaujqm.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.chenzaomai.com/Article/details/gt2vxnybhcc.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2aplwicwg.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.haohaochexian.top/Article/details/gt2cbjlvwro.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2gqhpuqjo.html

[T51] Scala：Hello World
来源：http://dali.yvedp.cn/Article/details/gt2dnybdzfy.html

println("Hello")
来源：http://dali.sufxvd.cn/Article/details/gt2xifghsxu.html

[T52] Scala：变量
来源：http://dali.vqdsnc.cn/Article/details/gt2uiziligc.html

val a = 1;  var b = 2
来源：http://dali.yuanzhike.top/Article/details/gt2tdbkkvul.html

[T53] Scala：字符串插值
来源：http://dali.daria6918.cn/Article/details/gt2kidpsquw.html

s"值: $b"
来源：http://dali.sxryk.cn/Article/details/gt2vygujlax.html

[T54] Scala：集合映射
来源：http://dali.tian-w.cn/Article/details/gt2gozsptog.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.iojbl.cn/Article/details/gt2eyiauvuc.html

[T55] Scala：集合过滤
来源：http://dali.ivvv.top/Article/details/gt2inyaiivb.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.sweek.top/Article/details/gt2ubasdohr.html

[T56] Scala：样例类
来源：http://dali.mhx1999.top/Article/details/gt2ktlkvgrt.html

case class User(name: String, age: Int)
来源：http://dali.mhx1999.top/Article/details/gt2pwlwxbwl.html

[T57] Scala：模式匹配
来源：http://dali.cheryme.top/Article/details/gt2pbracojp.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.pengpengdd.cyou/Article/details/gt2dsmfcvfa.html

[T58] Scala：函数定义
来源：http://dali.chenlongwang.top/Article/details/gt2svgiahit.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.daria6918.cn/Article/details/gt2ztrjkzar.html

[T59] Scala：循环
来源：http://dali.yonumen.top/Article/details/gt2ryvrdkre.html

for (i <- 1 to 10) println(i)
来源：http://dali.jiagoushi.top/Article/details/gt2xcnjturw.html

[T60] Scala：折叠
来源：http://dali.zycfv.cn/Article/details/gt2cxmhnpmz.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.daxiang520.top/Article/details/gt2qrarezoi.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2wawxdxze.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.shangyingyoupin.top/Article/details/gt2ulxcvduu.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2bmlhyuep.html

[U01] Py：创建虚拟环境
来源：http://dali.wangdashe.top/Article/details/gt2zjxwvvof.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.nanxuanxn.top/Article/details/gt2oaetywry.html

[U02] Py：导出 / 安装依赖
来源：http://dali.chenjidiqi.icu/Article/details/gt2ufstsymy.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhongyouzk.top/Article/details/gt2ptmokbeh.html

[U03] Py：加载 .env 配置
来源：http://dali.chenjidiqi.icu/Article/details/gt2jtamrffc.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.xziqi.cn/Article/details/gt2rzwfmbfv.html

[U04] Py：变量调试打印
来源：http://dali.hysaishi.cn/Article/details/gt2etymosva.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.xziqi.cn/Article/details/gt2nvabzzfe.html

[U05] Py：列表去重且保序
来源：http://dali.yangfankeji.com/Article/details/gt2dofvndpo.html

list(dict.fromkeys(arr))
来源：http://dali.nanxinkj.top/Article/details/gt2tocolfsi.html

[U06] Py：合并两个字典
来源：http://dali.yj20258888.top/Article/details/gt2oitmdkkk.html

{**a, **b}
来源：http://dali.daria6918.cn/Article/details/gt2ntffegoj.html

[U07] Py：反转字典键值
来源：http://dali.cheryme.top/Article/details/gt2nouuklpl.html

{v: k for k, v in d.items()}
来源：http://dali.xuetiantiany.cn/Article/details/gt2zuscygfh.html

[U08] Py：展平二维列表
来源：http://dali.gzhubu.top/Article/details/gt2dbuhjxtk.html

[y for x in nested for y in x]
来源：http://dali.tianlin.xyz/Article/details/gt2qcxjgxga.html

[U09] Py：字典取最大值的键
来源：http://dali.tian-w.cn/Article/details/gt2zcsmgrtm.html

max(d, key=d.get)
来源：http://dali.hnqzz.top/Article/details/gt2dkyprykn.html

[U10] Py：按值排序字典
来源：http://dali.yuanzhike.top/Article/details/gt2olbexezz.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.daria6918.cn/Article/details/gt2jwstnook.html

[U11] Py：生成器表达式
来源：http://dali.snrcjt.cn/Article/details/gt2tjfhqyac.html

(x * 2 for x in arr)
来源：http://dali.redwolf501.top/Article/details/gt2earmfisc.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.quarkkingdee.top/Article/details/gt2abhahpmt.html

Counter(arr).most_common(3)
来源：http://dali.birdmap.top/Article/details/gt2ywmlxyxo.html

[U13] Py：固定长度队列
来源：http://dali.yueranfly.top/Article/details/gt2heipzgks.html

deque(maxlen=10)
来源：http://dali.shzxlz.cn/Article/details/gt2ezpyvrgn.html

[U14] Py：分组收集到列表
来源：http://dali.yvedp.cn/Article/details/gt2zhldahoj.html

defaultdict(list)
来源：http://dali.feifeiyinyue.top/Article/details/gt2jdfvxdyv.html

[U15] Py：高精度计时
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kaolbioe.html

t = time.perf_counter()
来源：http://dali.tian-w.cn/Article/details/gt2nhgvktfo.html

[U16] Py：命令行参数解析
来源：http://dali.c1oappe.top/Article/details/gt2udprsooq.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.hongshengwenyu.top/Article/details/gt2dtdwssmg.html

[U17] Py：初始化日志
来源：http://dali.pycfn.com/Article/details/gt2pdsscbvy.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.haohaochexian.top/Article/details/gt2clrcsqaq.html

[U18] Py：预编译正则
来源：http://dali.yanxiufei.cn/Article/details/gt2farsndft.html

pat = re.compile(r"\d+")
来源：http://dali.jinqigufen.top/Article/details/gt2blkbexmn.html

[U19] Py：正则替换带回调
来源：http://dali.hnxiangtu.top/Article/details/gt2eytsdfau.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.havefunace.top/Article/details/gt2rjoigvot.html

[U20] Py：缓存函数结果
来源：http://dali.kuanghao11.cn/Article/details/gt2wxigvakb.html

@functools.lru_cache(maxsize=None)
来源：http://dali.chenzaomai.com/Article/details/gt2bqopftyt.html

[U21] Py：自定义上下文管理器
来源：http://dali.cqqwz.cn/Article/details/gt2bbwobqct.html

@contextlib.contextmanager
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yiyxqwlp.html

[U22] Py：矩阵转置
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xjpwtxpg.html

list(zip(*m))
来源：http://dali.shangyingyoupin.top/Article/details/gt2dbwamouq.html

[U23] Py：分块读取大文件
来源：http://dali.ybcxt.top/Article/details/gt2jrrzsgeg.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.jyoumei.cn/Article/details/gt2yhzgrwyo.html

[U24] Py：路径操作
来源：http://dali.yj20258.top/Article/details/gt2ebcyvxbf.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.jinqigfzy.top/Article/details/gt2ilnkotya.html

[U25] Py：CSV 按字典读
来源：http://dali.sufxvd.cn/Article/details/gt2qbdfyetm.html

csv.DictReader(f)
来源：http://dali.yj202588.top/Article/details/gt2fjczaybj.html

[U26] Py：并发下载
来源：http://dali.vqdsnc.cn/Article/details/gt2shffmnny.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.gzhubu.top/Article/details/gt2nkpqwhne.html

[U27] Py：异步 HTTP
来源：http://dali.ydzc1.top/Article/details/gt2zluoswof.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.shanyushiyangtech.top/Article/details/gt2atlmpyny.html

[U28] Py：类型别名
来源：http://dali.aizwys.cn/Article/details/gt2jxhceoig.html

UserId = int
来源：http://dali.xuetiantiany.cn/Article/details/gt2mknfbclq.html


<!-- 参考信息 -->