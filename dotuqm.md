代发 wailian999

strlen(s)
来源：http://dali.aizwys.cn/Article/details/gt2eyvodhln.html

[S06] C：字符串比较
来源：http://dali.yvedp.cn/Article/details/gt2hwfuyhgb.html

strcmp(a, b) == 0
来源：http://dali.jinqigfzy.top/Article/details/gt2zyrtqgef.html

[S07] C：数组遍历求和
来源：http://dali.jiagoushi.top/Article/details/gt2ghajmvxy.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.daria6918.cn/Article/details/gt2vjdrmnrb.html

[S08] C：动态内存分配与释放
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cnwikbcs.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.9152youxi.cn/Article/details/gt2xabznyrl.html

[S09] C：结构体定义与初始化
来源：http://dali.redwolf501.top/Article/details/gt2retcplci.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.svipenyu.cn/Article/details/gt2hezjyyuy.html

[S10] C：指针与解引用
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cysqxzqd.html

int *p = &a;  *p = 5;
来源：http://dali.jqgfzy.top/Article/details/gt2tmbdekoz.html

[S11] C：逐行读文件
来源：http://dali.zhiwuduotai.top/Article/details/gt2riplbdrx.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.snrcjt.cn/Article/details/gt2fnqacshf.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.yj202588.top/Article/details/gt2dacxtapa.html

fclose(f);
来源：http://dali.haohaochexian.top/Article/details/gt2wnvfsgii.html

[S12] C：写文件
来源：http://dali.hnqzz.top/Article/details/gt2rzpzivnw.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.havefunace.top/Article/details/gt2lxqxefgj.html

[S13] C：宏定义
来源：http://dali.fengsongda.top/Article/details/gt2fopcjtef.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.sysykeji.top/Article/details/gt2ocwkeagg.html

[S14] C：枚举
来源：http://dali.ybcxt.top/Article/details/gt2myhqxiqs.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.shzxlz.cn/Article/details/gt2rsqkxyoj.html

[S15] C：类型转换
来源：http://dali.jyoumei.cn/Article/details/gt2domkdoqi.html

(double) a / b
来源：http://dali.birdmap.top/Article/details/gt2vicgjowz.html

[S16] C：位操作置位
来源：http://dali.zhixingplan.top/Article/details/gt2yslwydko.html

x |= (1 << 3);
来源：http://dali.cucudq.cn/Article/details/gt2ybucrybn.html

[S17] C：安全拼接字符串
来源：http://dali.shuidangran.top/Article/details/gt2hqsteikt.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhoulong.xyz/Article/details/gt2nmptsszr.html

[S18] C：命令行参数
来源：http://dali.hywenlv.cn/Article/details/gt2aujjwbjm.html

int main(int argc, char **argv)
来源：http://dali.quarkkingdee.top/Article/details/gt2otqckzmj.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2rdlkdztw.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.hnxiangtu.top/Article/details/gt2juiytbzo.html

[S20] C：二分查找
来源：http://dali.smart0.xyz/Article/details/gt2kayjqlyc.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhengqikj.top/Article/details/gt2eywhmret.html

[S21] C：字符类别判断
来源：http://dali.yuanzhike.top/Article/details/gt2lczccxik.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.cucudq.cn/Article/details/gt2zqluamly.html

[S22] C：字符串转数字
来源：http://dali.nwbrower.top/Article/details/gt2imaptitv.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.gaohongyu789.top/Article/details/gt2nzlzmzyv.html

[S23] C：随机数
来源：http://dali.zhixingplan.top/Article/details/gt2ahdztygs.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.hongshengwenyu.top/Article/details/gt2hioiplwq.html

[S24] C：获取本地时间
来源：http://dali.bjfxy.top/Article/details/gt2hxfrgkkf.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.sweek.top/Article/details/gt2xjbyyrta.html

[S25] C：内存拷贝
来源：http://dali.xuanzx.com/Article/details/gt2zvexdwcd.html

memcpy(dst, src, n);
来源：http://dali.ivvv.top/Article/details/gt2grrqdtmz.html

[S26] C：内存清零
来源：http://dali.daxiang520.top/Article/details/gt2fvebwpbw.html

memset(a, 0, sizeof a);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rkotfhfs.html

[S27] C：定义常量
来源：http://dali.gogol.net.cn/Article/details/gt2knvvxped.html

const double PI = 3.14159;
来源：http://dali.ehwqpu.com/Article/details/gt2ootrdmpg.html

[S28] C：静态变量
来源：http://dali.shuidangran.top/Article/details/gt2xksehjkp.html

static int counter = 0;
来源：http://dali.zhongyouzk.top/Article/details/gt2mxwqlcgh.html

[S29] C：变参函数
来源：http://dali.snrcjt.cn/Article/details/gt2iodrzyoa.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.chenlongwang.top/Article/details/gt2lqnzeuoq.html

[S30] C：头文件保护
来源：http://dali.yonumen.top/Article/details/gt2tysbzqan.html

#ifndef X_H
来源：http://dali.haohaochexian.top/Article/details/gt2hiqrpycn.html

#define X_H
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cggenmwh.html

#endif
来源：http://dali.yuanzhike.top/Article/details/gt2xalwgwwe.html

[S31] C++：Hello World
来源：http://dali.316326.xyz/Article/details/gt2trmvbxeu.html

#include <iostream>
来源：http://dali.xziqi.cn/Article/details/gt2fhiqxydl.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.hnxiangtu.top/Article/details/gt2ihdayoov.html

[S32] C++：字符串
来源：http://dali.sufxvd.cn/Article/details/gt2iarpewzl.html

std::string s = "hi";  s += "!";
来源：http://dali.pengpengdd.cyou/Article/details/gt2asymldvk.html

[S33] C++：vector 增删
来源：http://dali.fzhhl.top/Article/details/gt2ktortofu.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.ybcxt.top/Article/details/gt2duubvvxd.html

[S34] C++：遍历 vector
来源：http://dali.xinyue.icu/Article/details/gt2yjppdbrm.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.tanke756.top/Article/details/gt2lcmgunmq.html

[S35] C++：map
来源：http://dali.feifeiyinyue.top/Article/details/gt2odrmnbcx.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.mhx1999.top/Article/details/gt2dkqsjztf.html

[S36] C++：unordered_map
来源：http://dali.316326.xyz/Article/details/gt2iywjrgib.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.xziqi.cn/Article/details/gt2sbliamqe.html

[S37] C++：set
来源：http://dali.zhoulong.xyz/Article/details/gt2exxretfd.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.cheryme.top/Article/details/gt2ygercsqc.html

[S38] C++：排序
来源：http://dali.cqqwz.cn/Article/details/gt2ghfmohhw.html

std::sort(v.begin(), v.end());
来源：http://dali.yangfankeji.com/Article/details/gt2iarsgpft.html

[S39] C++：自定义比较器排序
来源：http://dali.gogol.net.cn/Article/details/gt2qjdeubuk.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.chenjidiqi.icu/Article/details/gt2odktaifm.html

[S40] C++：查找元素
来源：http://dali.ybcxt.top/Article/details/gt2pfskkypq.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kahhckkl.html

[S41] C++：类与构造函数
来源：http://dali.hnqzz.top/Article/details/gt2mxpdgorz.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.jqgfzy.top/Article/details/gt2hmlasppv.html

[S42] C++：继承与虚函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jxujbyvk.html

class B : public Base { public: void f() override {} };
来源：http://dali.dianchejie.cn/Article/details/gt2gpekcqcb.html

[S43] C++：智能指针
来源：http://dali.gaohongyu789.top/Article/details/gt2magiutbb.html

auto p = std::make_unique<int>(5);
来源：http://dali.jinqigufen.top/Article/details/gt2mzaasebj.html

[S44] C++：引用传参
来源：http://dali.iojbl.cn/Article/details/gt2giehyobo.html

void inc(int &x) { ++x; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2qglxpjqp.html

[S45] C++：lambda
来源：http://dali.pengpengdd.cyou/Article/details/gt2dlmyuvkh.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wvypkdal.html

[S46] C++：函数模板
来源：http://dali.vqdsnc.cn/Article/details/gt2aoizyjkr.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2rqskkdax.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhiwuduotai.top/Article/details/gt2hnmriigd.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.yanxiufei.cn/Article/details/gt2qlqerzdc.html

[S48] C++：逐行读文件
来源：http://dali.sxryk.cn/Article/details/gt2xcwoqjwu.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.hysaishi.cn/Article/details/gt2nbxghphz.html

while (std::getline(in, line)) { }
来源：http://dali.jlsjyb.cn/Article/details/gt2hmkkouoe.html

[S49] C++：写文件
来源：http://dali.hammf.cn/Article/details/gt2xsgnrdtr.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.yuanzhike.top/Article/details/gt2nwhxnikc.html

[S50] C++：格式化数字
来源：http://dali.nanxuanxn.top/Article/details/gt2tepnwvmc.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhoulong.xyz/Article/details/gt2vexyvkpz.html

[S51] C++：显式类型转换
来源：http://dali.ppjwa.cn/Article/details/gt2ofbkblde.html

static_cast<double>(a) / b
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yqrlxzkt.html

[S52] C++：const 与 noexcept
来源：http://dali.chenjidiqi.icu/Article/details/gt2nhphquqf.html

int size() const noexcept { return n_; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2yoatalie.html

[S53] C++：移动语义
来源：http://dali.kuanghao11.cn/Article/details/gt2qarixrou.html

std::vector<int> w = std::move(v);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cqpjvbqy.html

[S54] C++：异常处理
来源：http://dali.jiagoushi.top/Article/details/gt2kldrokdv.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.quarkkingdee.top/Article/details/gt2fdgnyocp.html

[S55] C++：结构化绑定
来源：http://dali.wangshuangyany.cn/Article/details/gt2msdcetaj.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.cashguo.top/Article/details/gt2dorjwvtk.html

[S56] C++：optional
来源：http://dali.cashguo.top/Article/details/gt2bxaqytme.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zdqjudy.top/Article/details/gt2ryugxupr.html

[S57] C++：编译期常量
来源：http://dali.meibo888.top/Article/details/gt2tfloybfn.html

constexpr int N = 10;
来源：http://dali.jqgufenzy.top/Article/details/gt2kdkvhavc.html

[S58] C++：命名空间
来源：http://dali.0kj1m.cn/Article/details/gt2aahhrjsg.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhiwuduotai.top/Article/details/gt2eydxhham.html

[S59] C++：静态断言
来源：http://dali.hfpthk.cn/Article/details/gt2ukqpolcl.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.jianghu66.top/Article/details/gt2lqioxpsl.html

[S60] C++：遍历并删除元素
来源：http://dali.yonumen.top/Article/details/gt2bfgooeua.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.c1oappe.top/Article/details/gt2owqjddgo.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gt2fsrsvmni.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.pycfn.com/Article/details/gt2godltpne.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2jtwqblit.html

[T01] Kotlin：Hello World
来源：http://dali.nanxinkj.top/Article/details/gt2baksmkeq.html

println("Hello")
来源：http://dali.daria6918.cn/Article/details/gt2suujqihh.html

[T02] Kotlin：变量
来源：http://dali.guowangkeji.top/Article/details/gt2ilyzfgln.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.jiagoushi.top/Article/details/gt2jbgxpzom.html

[T03] Kotlin：字符串模板
来源：http://dali.andypj.xyz/Article/details/gt2frcllzta.html

"值: $b"
来源：http://dali.quarkkingdee.top/Article/details/gt2eiyuwxtn.html

[T04] Kotlin：空安全
来源：http://dali.c1oappe.top/Article/details/gt2bkftnqwj.html

val n: String? = null;  n?.length
来源：http://dali.yongpay.top/Article/details/gt2kmbkcmlx.html

[T05] Kotlin：when 表达式
来源：http://dali.sufxvd.cn/Article/details/gt2nslomoln.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gnmmaetl.html

[T06] Kotlin：集合映射
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ztawxjou.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zycfv.cn/Article/details/gt2fjhdlfif.html

[T07] Kotlin：集合过滤
来源：http://dali.redwolf501.top/Article/details/gt2hxxzzdef.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhengqikj.top/Article/details/gt2hgtqwvlw.html

[T08] Kotlin：数据类
来源：http://dali.316326.xyz/Article/details/gt2qxmbesfr.html

data class User(val name: String, val age: Int)
来源：http://dali.jiagoushi.top/Article/details/gt2oguuhozp.html

[T09] Kotlin：扩展函数
来源：http://dali.andypj.xyz/Article/details/gt2mbmkfwta.html

fun String.exclaim() = this + "!"
来源：http://dali.kuanghao11.cn/Article/details/gt2fcxufqcy.html

[T10] Kotlin：默认参数
来源：http://dali.hnqzz.top/Article/details/gt2texzacuj.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.gotoacloud.top/Article/details/gt2ggfcmxeo.html

[T11] Kotlin：协程
来源：http://dali.0kj1m.cn/Article/details/gt2ywkgrwuq.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhiwuduotai.top/Article/details/gt2ufsachuy.html

[T12] Kotlin：解构声明
来源：http://dali.tian-w.cn/Article/details/gt2upihjalz.html

val (a, b) = Pair(1, 2)
来源：http://dali.cheryme.top/Article/details/gt2cuzkrbjf.html

[T13] Kotlin：只读 Map
来源：http://dali.havefunace.top/Article/details/gt2hsydbdtw.html

val m = mapOf("a" to 1)
来源：http://dali.jinqigfzy.top/Article/details/gt2yecyuhbf.html

[T14] Kotlin：循环
来源：http://dali.iojbl.cn/Article/details/gt2uubqwlcw.html

for (i in 1..10) println(i)
来源：http://dali.birdmap.top/Article/details/gt2wtpaeepx.html

[T15] Kotlin：接口
来源：http://dali.yvedp.cn/Article/details/gt2divmrtbz.html

interface Shape { fun area(): Double }
来源：http://dali.meibo888.top/Article/details/gt2ujeysath.html

[T16] Swift：Hello World
来源：http://dali.cashguo.top/Article/details/gt2hwqrutbn.html

print("Hello")
来源：http://dali.jinqigufen.top/Article/details/gt2eodnkfdy.html

[T17] Swift：变量与常量
来源：http://dali.xuetiantiany.cn/Article/details/gt2hgxkwgih.html

var a = 1;  let b = 2
来源：http://dali.yanxiufei.cn/Article/details/gt2bxdpmivs.html

[T18] Swift：字符串插值
来源：http://dali.wangshuangyany.cn/Article/details/gt2tiqdsxql.html

"值: \(b)"
来源：http://dali.jlsjyb.cn/Article/details/gt2rctdjowv.html

[T19] Swift：可选绑定
来源：http://dali.jinqigufen.top/Article/details/gt2kjsxlfxg.html

if let n = opt { print(n) }
来源：http://dali.guowangkeji.top/Article/details/gt2fyvogiot.html

[T20] Swift：数组操作
来源：http://dali.daxiang520.top/Article/details/gt2rdjdrvwr.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.jinqigfzy.top/Article/details/gt2kzhfwtxe.html

[T21] Swift：遍历
来源：http://dali.tanke756.top/Article/details/gt2sscxmoof.html

for x in a { print(x) }
来源：http://dali.jlsjyb.cn/Article/details/gt2ktpghyyn.html

[T22] Swift：字典
来源：http://dali.yueranfly.top/Article/details/gt2bbvlvlin.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.redwolf501.top/Article/details/gt2vnftjnnl.html

[T23] Swift：函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2iusmjeos.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ktzgczvu.html

[T24] Swift：闭包
来源：http://dali.fzhhl.top/Article/details/gt2qbogqjqd.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.ppjwa.cn/Article/details/gt2modogwif.html

[T25] Swift：结构体
来源：http://dali.jiagoushi.top/Article/details/gt2exkphvhx.html

struct P { var x: Int }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fkkzpqon.html

[T26] Swift：类与重写
来源：http://dali.daxiang520.top/Article/details/gt2wvwthpow.html

class A: Base { override func f() {} }
来源：http://dali.yj20258.top/Article/details/gt2zajciseo.html

[T27] Swift：错误处理
来源：http://dali.mhx1999.top/Article/details/gt2jxiizslw.html

do { try f() } catch { print(error) }
来源：http://dali.jinqigfzy.top/Article/details/gt2rmauaspi.html

[T28] Swift：枚举
来源：http://dali.jlsjyb.cn/Article/details/gt2tcmdyzop.html

enum Color { case red, green }
来源：http://dali.sxryk.cn/Article/details/gt2tmtkqcwk.html

[T29] Swift：guard 提前返回
来源：http://dali.zdqjudy.top/Article/details/gt2mdnlkmcc.html

guard let x = opt else { return }
来源：http://dali.iojbl.cn/Article/details/gt2xoieegfw.html

[T30] Swift：协议
来源：http://dali.wangshuangyany.cn/Article/details/gt2xxuvajpy.html

protocol Shape { func area() -> Double }
来源：http://dali.gogol.net.cn/Article/details/gt2zckznhsn.html

[T31] Lua：Hello World
来源：http://dali.yj202588.top/Article/details/gt2wdzclgkr.html

print("Hello")
来源：http://dali.zycfv.cn/Article/details/gt2nfeigmvk.html

[T32] Lua：局部变量
来源：http://dali.shangyingyoupin.top/Article/details/gt2mutunris.html

local a = 1
来源：http://dali.dashuyun.cn/Article/details/gt2nlzznvji.html

[T33] Lua：表（数组）
来源：http://dali.shuidangran.top/Article/details/gt2owlepdon.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.ehwqpu.com/Article/details/gt2lmcmqhul.html

[T34] Lua：遍历表
来源：http://dali.kuanghao11.cn/Article/details/gt2udyjzhqn.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.ydzc1.top/Article/details/gt2bsmbrosy.html

[T35] Lua：字典表
来源：http://dali.cashguo.top/Article/details/gt2hcjyduys.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhiwuduotai.top/Article/details/gt2evjifhhd.html

[T36] Lua：函数
来源：http://dali.jinqigufen.top/Article/details/gt2lpheumgf.html

function add(a, b) return a + b end
来源：http://dali.yueranfly.top/Article/details/gt2mvpbffzo.html

[T37] Lua：字符串拼接
来源：http://dali.yvedp.cn/Article/details/gt2ravkpkcb.html

"a" .. "b"
来源：http://dali.zhixingplan.top/Article/details/gt2dsbirjes.html

[T38] Lua：条件
来源：http://dali.jiagoushi.top/Article/details/gt2wnxhnupw.html

if x > 0 then print("正") end
来源：http://dali.shangyingyoupin.top/Article/details/gt2ttfpnfhf.html

[T39] Lua：模式匹配
来源：http://dali.yuanzhike.top/Article/details/gt2ncudpfhb.html

string.find(s, "%d+")
来源：http://dali.hysaishi.cn/Article/details/gt2zwruozab.html

[T40] Lua：元表
来源：http://dali.havefunace.top/Article/details/gt2qmctklie.html

setmetatable({}, { __index = base })
来源：http://dali.cheryme.top/Article/details/gt2asacplds.html

[T41] Perl：Hello World
来源：http://dali.pycfn.com/Article/details/gt2itrwezkx.html

print "Hello\n";
来源：http://dali.wangdashe.top/Article/details/gt2honcshht.html

[T42] Perl：变量类型
来源：http://dali.sysykeji.top/Article/details/gt2ybfxbfzo.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.yj202588.top/Article/details/gt2xxtmvjpk.html

[T43] Perl：字符串插值
来源：http://dali.pycfn.com/Article/details/gt2bpelatpq.html

"值: $a"
来源：http://dali.zhongyouzk.top/Article/details/gt2ifnkuwkn.html

[T44] Perl：条件
来源：http://dali.xylfe.cn/Article/details/gt2pkrggsvn.html

if ($a > 0) { print "正"; }
来源：http://dali.daria6918.cn/Article/details/gt2csjearlv.html

[T45] Perl：数组遍历
来源：http://dali.gotoacloud.top/Article/details/gt2rvodvban.html

for my $x (@arr) { print $x; }
来源：http://dali.9152youxi.cn/Article/details/gt2ohqqudod.html

[T46] Perl：哈希操作
来源：http://dali.zycfv.cn/Article/details/gt2uwzcozrw.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.nwbrower.top/Article/details/gt2gufwbcjh.html

[T47] Perl：正则捕获
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2iynztlst.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.yj20258888.top/Article/details/gt2glhasvgu.html

[T48] Perl：正则替换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jzoeisfi.html

$s =~ s/old/new/g;
来源：http://dali.daria6918.cn/Article/details/gt2gtvgmuvs.html

[T49] Perl：函数
来源：http://dali.zhoulong.xyz/Article/details/gt2lsekdxfa.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.yongpay.top/Article/details/gt2jzghiyzz.html

[T50] Perl：逐行读文件
来源：http://dali.havefunace.top/Article/details/gt2vlpaazbq.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.sxryk.cn/Article/details/gt2pmivqsxh.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.smart0.xyz/Article/details/gt2vrcxnwuk.html

[T51] Scala：Hello World
来源：http://dali.daxiang520.top/Article/details/gt2uocyhawo.html

println("Hello")
来源：http://dali.sweek.top/Article/details/gt2xmablekl.html

[T52] Scala：变量
来源：http://dali.chenzaomai.com/Article/details/gt2lcvjrbbd.html

val a = 1;  var b = 2
来源：http://dali.birdmap.top/Article/details/gt2ctqdinik.html

[T53] Scala：字符串插值
来源：http://dali.xuetiantiany.cn/Article/details/gt2furupfcl.html

s"值: $b"
来源：http://dali.wangdashe.top/Article/details/gt2teksenkm.html

[T54] Scala：集合映射
来源：http://dali.jinqigufen.top/Article/details/gt2qtddonnx.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.wangshuangyany.cn/Article/details/gt2isyvhceh.html

[T55] Scala：集合过滤
来源：http://dali.xinyue.icu/Article/details/gt2foffsqyf.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2upwhqhdo.html

[T56] Scala：样例类
来源：http://dali.zhiwuduotai.top/Article/details/gt2xntdbyuo.html

case class User(name: String, age: Int)
来源：http://dali.chenzaomai.com/Article/details/gt2pnlzhdma.html

[T57] Scala：模式匹配
来源：http://dali.sysykeji.top/Article/details/gt2hjzkouri.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.nanxinkj.top/Article/details/gt2eqavvxpc.html

[T58] Scala：函数定义
来源：http://dali.jlsjyb.cn/Article/details/gt2sufawfzo.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.dashuyun.cn/Article/details/gt2glzlsqeo.html

[T59] Scala：循环
来源：http://dali.aibaodan.cn/Article/details/gt2bcvsutdg.html

for (i <- 1 to 10) println(i)
来源：http://dali.zycfv.cn/Article/details/gt2znopsqtq.html

[T60] Scala：折叠
来源：http://dali.nanxuanxn.top/Article/details/gt2uwcupkoh.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.fzhhl.top/Article/details/gt2zrzsgzzw.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zpltlzzc.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.andypj.xyz/Article/details/gt2cdbbafco.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2hekhsnzg.html

[U01] Py：创建虚拟环境
来源：http://dali.zycfv.cn/Article/details/gt2vrggsqom.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.jiagoushi.top/Article/details/gt2rxskvcag.html

[U02] Py：导出 / 安装依赖
来源：http://dali.ivvv.top/Article/details/gt2ibsxqnko.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.xuanzx.com/Article/details/gt2ugluouph.html

[U03] Py：加载 .env 配置
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ovktkxkk.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.jianghu66.top/Article/details/gt2simscdvs.html

[U04] Py：变量调试打印
来源：http://dali.aizwys.cn/Article/details/gt2kacrkrms.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.xziqi.cn/Article/details/gt2mbiyzjxp.html

[U05] Py：列表去重且保序
来源：http://dali.chenlongwang.top/Article/details/gt2amflegyy.html

list(dict.fromkeys(arr))
来源：http://dali.feifeiyinyue.top/Article/details/gt2xcqgwktk.html

[U06] Py：合并两个字典
来源：http://dali.xuetiantiany.cn/Article/details/gt2qiqqeksk.html

{**a, **b}
来源：http://dali.chenjidiqi.icu/Article/details/gt2ylnpshts.html

[U07] Py：反转字典键值
来源：http://dali.cashguo.top/Article/details/gt2uoqrnocl.html

{v: k for k, v in d.items()}
来源：http://dali.bjfxy.top/Article/details/gt2sbccltqp.html

[U08] Py：展平二维列表
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2deyzawqg.html

[y for x in nested for y in x]
来源：http://dali.yj202588.top/Article/details/gt2zazjpoyv.html

[U09] Py：字典取最大值的键
来源：http://dali.tianlin.xyz/Article/details/gt2wczrcchm.html

max(d, key=d.get)
来源：http://dali.jinqigfzy.top/Article/details/gt2opnlcinx.html

[U10] Py：按值排序字典
来源：http://dali.vqdsnc.cn/Article/details/gt2vyonlgvq.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.feifeiyinyue.top/Article/details/gt2kthqaaao.html

[U11] Py：生成器表达式
来源：http://dali.jianghu66.top/Article/details/gt2vbufncks.html

(x * 2 for x in arr)
来源：http://dali.mhx1999.top/Article/details/gt2thclojfh.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2joluiqlf.html

Counter(arr).most_common(3)
来源：http://dali.haohaochexian.top/Article/details/gt2tmpharll.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ckazooam.html

deque(maxlen=10)
来源：http://dali.c1oappe.top/Article/details/gt2rrdsqujo.html

[U14] Py：分组收集到列表
来源：http://dali.meibo888.top/Article/details/gt2qfezltpr.html

defaultdict(list)
来源：http://dali.cucudq.cn/Article/details/gt2ocjhheak.html

[U15] Py：高精度计时
来源：http://dali.jinghuilouyu.cn/Article/details/gt2djbprjse.html

t = time.perf_counter()
来源：http://dali.zhongyouzk.top/Article/details/gt2dqrvarvx.html

[U16] Py：命令行参数解析
来源：http://dali.kuanghao11.cn/Article/details/gt2wzhkrqsr.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.sxryk.cn/Article/details/gt2absoqdrr.html

[U17] Py：初始化日志
来源：http://dali.yonumen.top/Article/details/gt2pswfiusc.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhixingplan.top/Article/details/gt2krgdlydp.html

[U18] Py：预编译正则
来源：http://dali.shangyingyoupin.top/Article/details/gt2iezwferz.html

pat = re.compile(r"\d+")
来源：http://dali.9152youxi.cn/Article/details/gt2bravfpxd.html

[U19] Py：正则替换带回调
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2iipzlpdo.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.daria6918.cn/Article/details/gt2jnnbynvt.html

[U20] Py：缓存函数结果
来源：http://dali.shuidangran.top/Article/details/gt2etlvwykk.html

@functools.lru_cache(maxsize=None)
来源：http://dali.gzhubu.top/Article/details/gt2bcxhfxdt.html

[U21] Py：自定义上下文管理器
来源：http://dali.yangfankeji.com/Article/details/gt2urcqxidt.html

@contextlib.contextmanager
来源：http://dali.cheryme.top/Article/details/gt2zvhdffue.html

[U22] Py：矩阵转置
来源：http://dali.cqqwz.cn/Article/details/gt2baafvtgt.html

list(zip(*m))
来源：http://dali.sweek.top/Article/details/gt2uyycrbdq.html

[U23] Py：分块读取大文件
来源：http://dali.chenlongwang.top/Article/details/gt2ypqdsoes.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.wangdashe.top/Article/details/gt2yejmgavr.html

[U24] Py：路径操作
来源：http://dali.daxiang520.top/Article/details/gt2ahiobrnl.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.vqdsnc.cn/Article/details/gt2fjdvgvws.html

[U25] Py：CSV 按字典读
来源：http://dali.yangfankeji.com/Article/details/gt2jcijaloe.html

csv.DictReader(f)
来源：http://dali.hywenlv.cn/Article/details/gt2uwwjkozr.html

[U26] Py：并发下载
来源：http://dali.jqgfzy.top/Article/details/gt2ftxowqap.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.havefunace.top/Article/details/gt2xcjgcytz.html

[U27] Py：异步 HTTP
来源：http://dali.cqqwz.cn/Article/details/gt2qubjlsuh.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.guowangkeji.top/Article/details/gt2zquocvsj.html

[U28] Py：类型别名
来源：http://dali.yj20258888.top/Article/details/gt2hlcjcmni.html

UserId = int
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rxmuhlns.html


<!-- 参考信息 -->