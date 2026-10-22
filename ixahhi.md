代发 wailian999

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zycfv.cn/Article/details/gt2pewadzba.html

[S02] C：变量与格式化输出
来源：http://dali.hongshengwenyu.top/Article/details/gt2gcpdihwb.html

int a = 10; printf("%d\n", a);
来源：http://dali.chenlongwang.top/Article/details/gt2gjxrryin.html

[S03] C：读入整数
来源：http://dali.fengsongda.top/Article/details/gt2vtcmhssa.html

int x; scanf("%d", &x);
来源：http://dali.yuanzhike.top/Article/details/gt2xjpjbqhp.html

[S04] C：字符串复制
来源：http://dali.yuanzhike.top/Article/details/gt2iwidylzx.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.hongshengwenyu.top/Article/details/gt2rlixjtkn.html

[S05] C：字符串长度
来源：http://dali.316326.xyz/Article/details/gt2eejoatnm.html

strlen(s)
来源：http://dali.sweek.top/Article/details/gt2zijrwxky.html

[S06] C：字符串比较
来源：http://dali.jinqigufen.top/Article/details/gt2vxvhrupq.html

strcmp(a, b) == 0
来源：http://dali.jiagoushi.top/Article/details/gt2xreqdadr.html

[S07] C：数组遍历求和
来源：http://dali.daxiang520.top/Article/details/gt2hggklsyr.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dbcymekp.html

[S08] C：动态内存分配与释放
来源：http://dali.yj20258888.top/Article/details/gt2tbttccbg.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.fzhhl.top/Article/details/gt2lczqusgq.html

[S09] C：结构体定义与初始化
来源：http://dali.316326.xyz/Article/details/gt2srxnrygi.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.yj20258.top/Article/details/gt2fxzlmqnt.html

[S10] C：指针与解引用
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yhepibmv.html

int *p = &a;  *p = 5;
来源：http://dali.xylfe.cn/Article/details/gt2kvpwsxpl.html

[S11] C：逐行读文件
来源：http://dali.andypj.xyz/Article/details/gt2jqikotvv.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.tian-w.cn/Article/details/gt2qvhzqmwi.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.aibaodan.cn/Article/details/gt2pkfgwuno.html

fclose(f);
来源：http://dali.yj20258.top/Article/details/gt2ipmeokcv.html

[S12] C：写文件
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zgqhbeob.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.chenzaomai.com/Article/details/gt2gphmetbl.html

[S13] C：宏定义
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jzrrhkfu.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.redwolf501.top/Article/details/gt2xwpznbgk.html

[S14] C：枚举
来源：http://dali.gaohongyu789.top/Article/details/gt2ytqfoesf.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jpoocdsz.html

[S15] C：类型转换
来源：http://dali.meibo888.top/Article/details/gt2eilqdwox.html

(double) a / b
来源：http://dali.sweek.top/Article/details/gt2qcpynkct.html

[S16] C：位操作置位
来源：http://dali.quarkkingdee.top/Article/details/gt2ylebfbay.html

x |= (1 << 3);
来源：http://dali.fengsongda.top/Article/details/gt2qjfjgwqr.html

[S17] C：安全拼接字符串
来源：http://dali.yj20258.top/Article/details/gt2rwcxrxuw.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.yangfankeji.com/Article/details/gt2aoiepqir.html

[S18] C：命令行参数
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2shvlhwag.html

int main(int argc, char **argv)
来源：http://dali.zhongyouzk.top/Article/details/gt2udfeqvgc.html

[S19] C：快速排序
来源：http://dali.gzhubu.top/Article/details/gt2fdzmvnue.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wlsoccxz.html

[S20] C：二分查找
来源：http://dali.9152youxi.cn/Article/details/gt2aeginucm.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.dashuyun.cn/Article/details/gt2cllbddil.html

[S21] C：字符类别判断
来源：http://dali.dianchejie.cn/Article/details/gt2jucthemz.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.yongpay.top/Article/details/gt2nxlnpcao.html

[S22] C：字符串转数字
来源：http://dali.zhengqikj.top/Article/details/gt2tgultosz.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.aibaodan.cn/Article/details/gt2ldiflqid.html

[S23] C：随机数
来源：http://dali.dianchejie.cn/Article/details/gt2fnywccxw.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cmhouxek.html

[S24] C：获取本地时间
来源：http://dali.zhengqikj.top/Article/details/gt2tpybtmwz.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhongyouzk.top/Article/details/gt2oesphgbs.html

[S25] C：内存拷贝
来源：http://dali.316326.xyz/Article/details/gt2njskmubs.html

memcpy(dst, src, n);
来源：http://dali.yj20258.top/Article/details/gt2ukyxmawg.html

[S26] C：内存清零
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yckhnxln.html

memset(a, 0, sizeof a);
来源：http://dali.wangdashe.top/Article/details/gt2ctzrclhd.html

[S27] C：定义常量
来源：http://dali.sweek.top/Article/details/gt2akmydjbt.html

const double PI = 3.14159;
来源：http://dali.meibo888.top/Article/details/gt2mprrqkse.html

[S28] C：静态变量
来源：http://dali.chenjidiqi.icu/Article/details/gt2tdnptsky.html

static int counter = 0;
来源：http://dali.dashuyun.cn/Article/details/gt2wxlizmke.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zrdzsldm.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.iojbl.cn/Article/details/gt2mrllfvgl.html

[S30] C：头文件保护
来源：http://dali.guannengcc.top/Article/details/gt2ezdzphdd.html

#ifndef X_H
来源：http://dali.yj20258.top/Article/details/gt2iimkngcn.html

#define X_H
来源：http://dali.cqqwz.cn/Article/details/gt2kfcpdjdv.html

#endif
来源：http://dali.jianghu66.top/Article/details/gt2szprhyie.html

[S31] C++：Hello World
来源：http://dali.nanxinkj.top/Article/details/gt2nofegnor.html

#include <iostream>
来源：http://dali.hfpthk.cn/Article/details/gt2uygtiyhn.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.yongpay.top/Article/details/gt2mxrzcejg.html

[S32] C++：字符串
来源：http://dali.gaohongyu789.top/Article/details/gt2fmyfbypj.html

std::string s = "hi";  s += "!";
来源：http://dali.xuanzx.com/Article/details/gt2awyjiguk.html

[S33] C++：vector 增删
来源：http://dali.gotoacloud.top/Article/details/gt2klvejmjv.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.aibaodan.cn/Article/details/gt2muhbhcug.html

[S34] C++：遍历 vector
来源：http://dali.hfpthk.cn/Article/details/gt2pvpcoruk.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.smart0.xyz/Article/details/gt2qpsmnpkp.html

[S35] C++：map
来源：http://dali.vqdsnc.cn/Article/details/gt2bhkzcsvt.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.chenlongwang.top/Article/details/gt2flcnulkh.html

[S36] C++：unordered_map
来源：http://dali.yuanzhike.top/Article/details/gt2tagbwpsi.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.cqqwz.cn/Article/details/gt2eddrykug.html

[S37] C++：set
来源：http://dali.guowangkeji.top/Article/details/gt2oddczbky.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.aibaodan.cn/Article/details/gt2ufjydztu.html

[S38] C++：排序
来源：http://dali.fzhhl.top/Article/details/gt2yvdqjggt.html

std::sort(v.begin(), v.end());
来源：http://dali.yj20258888.top/Article/details/gt2hygxrwrv.html

[S39] C++：自定义比较器排序
来源：http://dali.daria6918.cn/Article/details/gt2njposhqx.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.xylfe.cn/Article/details/gt2pmtzrtva.html

[S40] C++：查找元素
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2brnfmodl.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ubbptund.html

[S41] C++：类与构造函数
来源：http://dali.ydzc1.top/Article/details/gt2dfhbnrzk.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2nruibhpi.html

[S42] C++：继承与虚函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mlkmapwh.html

class B : public Base { public: void f() override {} };
来源：http://dali.mhx1999.top/Article/details/gt2mstvppiz.html

[S43] C++：智能指针
来源：http://dali.hywenlv.cn/Article/details/gt2iugxykpk.html

auto p = std::make_unique<int>(5);
来源：http://dali.zycfv.cn/Article/details/gt2bjkscgda.html

[S44] C++：引用传参
来源：http://dali.sysykeji.top/Article/details/gt2sqokfnxp.html

void inc(int &x) { ++x; }
来源：http://dali.yj20258888.top/Article/details/gt2spifnlzm.html

[S45] C++：lambda
来源：http://dali.yanxiufei.cn/Article/details/gt2vmwysqdw.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.pengpengdd.cyou/Article/details/gt2pdloewdb.html

[S46] C++：函数模板
来源：http://dali.shzxlz.cn/Article/details/gt2fkagtrtp.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.ybcxt.top/Article/details/gt2kzubenrj.html

[S47] C++：结构化绑定遍历
来源：http://dali.nanxinkj.top/Article/details/gt2agrbdozi.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.hnqzz.top/Article/details/gt2isuhpoek.html

[S48] C++：逐行读文件
来源：http://dali.aibaodan.cn/Article/details/gt2gfjmychd.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.wangdashe.top/Article/details/gt2hukljfdt.html

while (std::getline(in, line)) { }
来源：http://dali.zycfv.cn/Article/details/gt2bocnlpxu.html

[S49] C++：写文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xdqlgjgh.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.jianghu66.top/Article/details/gt2vurdqcbh.html

[S50] C++：格式化数字
来源：http://dali.shzxlz.cn/Article/details/gt2wlwrguvy.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.dianchejie.cn/Article/details/gt2dzaillzm.html

[S51] C++：显式类型转换
来源：http://dali.mhx1999.top/Article/details/gt2mgsoxnhc.html

static_cast<double>(a) / b
来源：http://dali.dashuyun.cn/Article/details/gt2clcrwnxi.html

[S52] C++：const 与 noexcept
来源：http://dali.gaohongyu789.top/Article/details/gt2stthpxmz.html

int size() const noexcept { return n_; }
来源：http://dali.xziqi.cn/Article/details/gt2oroxjiia.html

[S53] C++：移动语义
来源：http://dali.sweek.top/Article/details/gt2grmnllzh.html

std::vector<int> w = std::move(v);
来源：http://dali.haohaochexian.top/Article/details/gt2pofulvmj.html

[S54] C++：异常处理
来源：http://dali.guowangkeji.top/Article/details/gt2isliktgb.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.gaohongyu789.top/Article/details/gt2sttrqhmx.html

[S55] C++：结构化绑定
来源：http://dali.ydzc1.top/Article/details/gt2kahpkown.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.nanxuanxn.top/Article/details/gt2lhlbtcoy.html

[S56] C++：optional
来源：http://dali.sufxvd.cn/Article/details/gt2yjjdtmzf.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.mhx1999.top/Article/details/gt2gcwqqfpu.html

[S57] C++：编译期常量
来源：http://dali.jyoumei.cn/Article/details/gt2sylvbwkd.html

constexpr int N = 10;
来源：http://dali.hnqzz.top/Article/details/gt2gfbmsepe.html

[S58] C++：命名空间
来源：http://dali.ybcxt.top/Article/details/gt2sumqzrvx.html

namespace ns { int f() { return 1; } }
来源：http://dali.0kj1m.cn/Article/details/gt2jzsuegqc.html

[S59] C++：静态断言
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ggviczxe.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.birdmap.top/Article/details/gt2ishnybvm.html

[S60] C++：遍历并删除元素
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kzlvkppf.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.yj20258888.top/Article/details/gt2dvgttoog.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ejaqztdg.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.shuidangran.top/Article/details/gt2liknokfv.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gt2njptvdgo.html

[T01] Kotlin：Hello World
来源：http://dali.c1oappe.top/Article/details/gt2zjogymig.html

println("Hello")
来源：http://dali.snrcjt.cn/Article/details/gt2wixlshoc.html

[T02] Kotlin：变量
来源：http://dali.xuetiantiany.cn/Article/details/gt2hjzqaaik.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.kuanghao11.cn/Article/details/gt2zmrxsskv.html

[T03] Kotlin：字符串模板
来源：http://dali.gaohongyu789.top/Article/details/gt2hkjxohrg.html

"值: $b"
来源：http://dali.daxiang520.top/Article/details/gt2nqbxeiqp.html

[T04] Kotlin：空安全
来源：http://dali.yuxming.cn/Article/details/gt2axwxdwqd.html

val n: String? = null;  n?.length
来源：http://dali.jiagoushi.top/Article/details/gt2gbsckgch.html

[T05] Kotlin：when 表达式
来源：http://dali.ivvv.top/Article/details/gt2jutsmkul.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2xbfzgvwl.html

[T06] Kotlin：集合映射
来源：http://dali.shzxlz.cn/Article/details/gt2zmooobew.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.sufxvd.cn/Article/details/gt2gsbwsvso.html

[T07] Kotlin：集合过滤
来源：http://dali.snrcjt.cn/Article/details/gt2tfcrtbth.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.316326.xyz/Article/details/gt2nswdwrad.html

[T08] Kotlin：数据类
来源：http://dali.xuetiantiany.cn/Article/details/gt2ffbnclpn.html

data class User(val name: String, val age: Int)
来源：http://dali.0kj1m.cn/Article/details/gt2trjxzeem.html

[T09] Kotlin：扩展函数
来源：http://dali.haohaochexian.top/Article/details/gt2dbphvbki.html

fun String.exclaim() = this + "!"
来源：http://dali.cqqwz.cn/Article/details/gt2wmzkuzgx.html

[T10] Kotlin：默认参数
来源：http://dali.ydzc1.top/Article/details/gt2glempeko.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.tian-w.cn/Article/details/gt2lvxdmrvh.html

[T11] Kotlin：协程
来源：http://dali.ppjwa.cn/Article/details/gt2tzaeabvq.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.cqqwz.cn/Article/details/gt2timvgahp.html

[T12] Kotlin：解构声明
来源：http://dali.cqqwz.cn/Article/details/gt2edzjkoxa.html

val (a, b) = Pair(1, 2)
来源：http://dali.jqgufenzy.top/Article/details/gt2hpkoujjx.html

[T13] Kotlin：只读 Map
来源：http://dali.ehwqpu.com/Article/details/gt2dcmntlxg.html

val m = mapOf("a" to 1)
来源：http://dali.daxiang520.top/Article/details/gt2giohefbb.html

[T14] Kotlin：循环
来源：http://dali.yueranfly.top/Article/details/gt2minqxgdq.html

for (i in 1..10) println(i)
来源：http://dali.feifeiyinyue.top/Article/details/gt2eqoluaos.html

[T15] Kotlin：接口
来源：http://dali.guowangkeji.top/Article/details/gt2pgetrqix.html

interface Shape { fun area(): Double }
来源：http://dali.daria6918.cn/Article/details/gt2gdftjjsb.html

[T16] Swift：Hello World
来源：http://dali.pycfn.com/Article/details/gt2imtsqear.html

print("Hello")
来源：http://dali.cdnleiting.top/Article/details/gt2jnjgruqy.html

[T17] Swift：变量与常量
来源：http://dali.wangdashe.top/Article/details/gt2nbyatinu.html

var a = 1;  let b = 2
来源：http://dali.hfpthk.cn/Article/details/gt2dftkveaa.html

[T18] Swift：字符串插值
来源：http://dali.gotoacloud.top/Article/details/gt2qhebxcwb.html

"值: \(b)"
来源：http://dali.yonumen.top/Article/details/gt2ejgtxplr.html

[T19] Swift：可选绑定
来源：http://dali.yvedp.cn/Article/details/gt2uaiwvreq.html

if let n = opt { print(n) }
来源：http://dali.daria6918.cn/Article/details/gt2ordavcso.html

[T20] Swift：数组操作
来源：http://dali.tian-w.cn/Article/details/gt2wbglrjvq.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.jiagoushi.top/Article/details/gt2xhithrhy.html

[T21] Swift：遍历
来源：http://dali.iojbl.cn/Article/details/gt2uwkxxdis.html

for x in a { print(x) }
来源：http://dali.wangdashe.top/Article/details/gt2nlaikfzh.html

[T22] Swift：字典
来源：http://dali.aibaodan.cn/Article/details/gt2vhvkvrfb.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.jlsjyb.cn/Article/details/gt2wcfulbyb.html

[T23] Swift：函数
来源：http://dali.haohaochexian.top/Article/details/gt2xggvtelg.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhixingplan.top/Article/details/gt2ldanlfjv.html

[T24] Swift：闭包
来源：http://dali.gogol.net.cn/Article/details/gt2apwhzqcd.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.birdmap.top/Article/details/gt2rksttamn.html

[T25] Swift：结构体
来源：http://dali.jinqigufen.top/Article/details/gt2obvynipb.html

struct P { var x: Int }
来源：http://dali.nwbrower.top/Article/details/gt2jstigqpp.html

[T26] Swift：类与重写
来源：http://dali.shuidangran.top/Article/details/gt2dtdftetv.html

class A: Base { override func f() {} }
来源：http://dali.dianchejie.cn/Article/details/gt2hqosnhwf.html

[T27] Swift：错误处理
来源：http://dali.ppjwa.cn/Article/details/gt2vcvapfqd.html

do { try f() } catch { print(error) }
来源：http://dali.yangfankeji.com/Article/details/gt2bnnhhhos.html

[T28] Swift：枚举
来源：http://dali.nanxinkj.top/Article/details/gt2xvpjpijw.html

enum Color { case red, green }
来源：http://dali.fzhhl.top/Article/details/gt2dbvekgkc.html

[T29] Swift：guard 提前返回
来源：http://dali.quarkkingdee.top/Article/details/gt2vrzlmbqq.html

guard let x = opt else { return }
来源：http://dali.chenjidiqi.icu/Article/details/gt2brximaoz.html

[T30] Swift：协议
来源：http://dali.dianchejie.cn/Article/details/gt2vhojqrtp.html

protocol Shape { func area() -> Double }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jggwjtvo.html

[T31] Lua：Hello World
来源：http://dali.c1oappe.top/Article/details/gt2wxxjqwiv.html

print("Hello")
来源：http://dali.shangyingyoupin.top/Article/details/gt2cyqzcvlu.html

[T32] Lua：局部变量
来源：http://dali.fengsongda.top/Article/details/gt2hbzyvaui.html

local a = 1
来源：http://dali.sweek.top/Article/details/gt2csfornmi.html

[T33] Lua：表（数组）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2beyxnoox.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.tian-w.cn/Article/details/gt2utuycbtg.html

[T34] Lua：遍历表
来源：http://dali.bjfxy.top/Article/details/gt2ctrxrrqk.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.ydzc1.top/Article/details/gt2iqttwzrc.html

[T35] Lua：字典表
来源：http://dali.ybcxt.top/Article/details/gt2hximlyww.html

local d = { a = 1 };  d.b = 2
来源：http://dali.aibaodan.cn/Article/details/gt2gedmwqqc.html

[T36] Lua：函数
来源：http://dali.c1oappe.top/Article/details/gt2qibilpkq.html

function add(a, b) return a + b end
来源：http://dali.gaohongyu789.top/Article/details/gt2xiqdgstg.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2cviujixt.html

"a" .. "b"
来源：http://dali.yj20258888.top/Article/details/gt2gaarowqu.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2cwnqyxii.html

if x > 0 then print("正") end
来源：http://dali.daria6918.cn/Article/details/gt2qhlnqgtn.html

[T39] Lua：模式匹配
来源：http://dali.dashuyun.cn/Article/details/gt2oobjhgkj.html

string.find(s, "%d+")
来源：http://dali.yuanzhike.top/Article/details/gt2setxemlk.html

[T40] Lua：元表
来源：http://dali.xziqi.cn/Article/details/gt2suyayphd.html

setmetatable({}, { __index = base })
来源：http://dali.yanxiufei.cn/Article/details/gt2mjynjgiq.html

[T41] Perl：Hello World
来源：http://dali.quarkkingdee.top/Article/details/gt2tpcgkhvc.html

print "Hello\n";
来源：http://dali.hnqzz.top/Article/details/gt2vzvshpnu.html

[T42] Perl：变量类型
来源：http://dali.tian-w.cn/Article/details/gt2chxtibsd.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.ppjwa.cn/Article/details/gt2cdsrioix.html

[T43] Perl：字符串插值
来源：http://dali.gzhubu.top/Article/details/gt2aaqcsafm.html

"值: $a"
来源：http://dali.aizwys.cn/Article/details/gt2cynidhmj.html

[T44] Perl：条件
来源：http://dali.xuetiantiany.cn/Article/details/gt2cuapctfm.html

if ($a > 0) { print "正"; }
来源：http://dali.mhx1999.top/Article/details/gt2tashzrei.html

[T45] Perl：数组遍历
来源：http://dali.xinyue.icu/Article/details/gt2azdykuvy.html

for my $x (@arr) { print $x; }
来源：http://dali.chenlongwang.top/Article/details/gt2pucbjdnl.html

[T46] Perl：哈希操作
来源：http://dali.cdnleiting.top/Article/details/gt2meqgnojz.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.iojbl.cn/Article/details/gt2gakgurlf.html

[T47] Perl：正则捕获
来源：http://dali.dashuyun.cn/Article/details/gt2kqpwhups.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.yongpay.top/Article/details/gt2piqgygde.html

[T48] Perl：正则替换
来源：http://dali.yvedp.cn/Article/details/gt2jmabouzu.html

$s =~ s/old/new/g;
来源：http://dali.hfpthk.cn/Article/details/gt2dvqkrwzj.html

[T49] Perl：函数
来源：http://dali.cdnleiting.top/Article/details/gt2hhdjcixq.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.chenlongwang.top/Article/details/gt2kdkirqlw.html

[T50] Perl：逐行读文件
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qfaeqcut.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.yj20258.top/Article/details/gt2bdqmfgpz.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.jiagoushi.top/Article/details/gt2sdfjlljx.html

[T51] Scala：Hello World
来源：http://dali.gzhubu.top/Article/details/gt2bgelemow.html

println("Hello")
来源：http://dali.guannengcc.top/Article/details/gt2ddynrdmt.html

[T52] Scala：变量
来源：http://dali.nwbrower.top/Article/details/gt2ndkyobmi.html

val a = 1;  var b = 2
来源：http://dali.havefunace.top/Article/details/gt2alhdpyxf.html

[T53] Scala：字符串插值
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hwlqgbxp.html

s"值: $b"
来源：http://dali.dashuyun.cn/Article/details/gt2clixwnqj.html

[T54] Scala：集合映射
来源：http://dali.pengpengdd.cyou/Article/details/gt2mzdasvfm.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.yuxming.cn/Article/details/gt2fpijcrho.html

[T55] Scala：集合过滤
来源：http://dali.gotoacloud.top/Article/details/gt2zrrzmwnn.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.tanke756.top/Article/details/gt2wwxljfaa.html

[T56] Scala：样例类
来源：http://dali.ydzc1.top/Article/details/gt2fmtxxxpm.html

case class User(name: String, age: Int)
来源：http://dali.tian-w.cn/Article/details/gt2haqphwgg.html

[T57] Scala：模式匹配
来源：http://dali.gogol.net.cn/Article/details/gt2jeziugel.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.xylfe.cn/Article/details/gt2mlbnxsph.html

[T58] Scala：函数定义
来源：http://dali.xinyue.icu/Article/details/gt2nfxoezck.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.gaohongyu789.top/Article/details/gt2udyuargi.html

[T59] Scala：循环
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yksvwrfg.html

for (i <- 1 to 10) println(i)
来源：http://dali.fzhhl.top/Article/details/gt2bihpzenl.html

[T60] Scala：折叠
来源：http://dali.shangyingyoupin.top/Article/details/gt2axkomokc.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.nanxinkj.top/Article/details/gt2mgalhdlm.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gt2skjtmzfn.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.c1oappe.top/Article/details/gt2hlzcxuyz.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gt2vlofblgb.html

[U01] Py：创建虚拟环境
来源：http://dali.hywenlv.cn/Article/details/gt2xjsvrpvc.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2smlnaksn.html

[U02] Py：导出 / 安装依赖
来源：http://dali.gzhubu.top/Article/details/gt2tmssrrid.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.bjfxy.top/Article/details/gt2padbngjz.html

[U03] Py：加载 .env 配置
来源：http://dali.yanxiufei.cn/Article/details/gt2lcgusjmo.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.snrcjt.cn/Article/details/gt2xvgnyjqj.html

[U04] Py：变量调试打印
来源：http://dali.shzxlz.cn/Article/details/gt2mwzhqwve.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.hnxiangtu.top/Article/details/gt2mcrvtiug.html

[U05] Py：列表去重且保序
来源：http://dali.jiagoushi.top/Article/details/gt2evehapuv.html

list(dict.fromkeys(arr))
来源：http://dali.zhixingplan.top/Article/details/gt2oqnrhqot.html

[U06] Py：合并两个字典
来源：http://dali.wangshuangyany.cn/Article/details/gt2tavrngjm.html

{**a, **b}
来源：http://dali.guowangkeji.top/Article/details/gt2lsikkqci.html

[U07] Py：反转字典键值
来源：http://dali.zhoulong.xyz/Article/details/gt2ctqxxxed.html

{v: k for k, v in d.items()}
来源：http://dali.jqgufenzy.top/Article/details/gt2qzcaabpv.html

[U08] Py：展平二维列表
来源：http://dali.zhiwuduotai.top/Article/details/gt2fskbbagc.html

[y for x in nested for y in x]
来源：http://dali.zhongyouzk.top/Article/details/gt2swazzcuo.html

[U09] Py：字典取最大值的键
来源：http://dali.hfpthk.cn/Article/details/gt2dpdbsudg.html

max(d, key=d.get)
来源：http://dali.bjfxy.top/Article/details/gt2kftbjhdx.html

[U10] Py：按值排序字典
来源：http://dali.hfpthk.cn/Article/details/gt2xelymvbu.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.fzhhl.top/Article/details/gt2pqrahpyy.html

[U11] Py：生成器表达式
来源：http://dali.gaohongyu789.top/Article/details/gt2zzoeanvh.html

(x * 2 for x in arr)
来源：http://dali.birdmap.top/Article/details/gt2paurgicz.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.gzhubu.top/Article/details/gt2tzelvjzi.html

Counter(arr).most_common(3)
来源：http://dali.fengsongda.top/Article/details/gt2cukilvmu.html

[U13] Py：固定长度队列
来源：http://dali.nanxuanxn.top/Article/details/gt2jfpwjqjb.html

deque(maxlen=10)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xiryvbqc.html

[U14] Py：分组收集到列表
来源：http://dali.yonumen.top/Article/details/gt2zaajfqdm.html

defaultdict(list)
来源：http://dali.haohaochexian.top/Article/details/gt2ptdlfinc.html

[U15] Py：高精度计时
来源：http://dali.jinghuilouyu.cn/Article/details/gt2thbjcywu.html

t = time.perf_counter()
来源：http://dali.iojbl.cn/Article/details/gt2alqavckd.html

[U16] Py：命令行参数解析
来源：http://dali.svipenyu.cn/Article/details/gt2pvxvahfb.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.feifeiyinyue.top/Article/details/gt2lvrwmztb.html

[U17] Py：初始化日志
来源：http://dali.shuidangran.top/Article/details/gt2ueguqpkx.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.mhx1999.top/Article/details/gt2xsqbdfoz.html

[U18] Py：预编译正则
来源：http://dali.jiagoushi.top/Article/details/gt2ftnaycgq.html

pat = re.compile(r"\d+")
来源：http://dali.tian-w.cn/Article/details/gt2qidqgotf.html

[U19] Py：正则替换带回调
来源：http://dali.zhongyouzk.top/Article/details/gt2tdioetyx.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.jlsjyb.cn/Article/details/gt2hhfngwrt.html

[U20] Py：缓存函数结果
来源：http://dali.yanxiufei.cn/Article/details/gt2yehvluiu.html

@functools.lru_cache(maxsize=None)
来源：http://dali.ehwqpu.com/Article/details/gt2dyzevewh.html

[U21] Py：自定义上下文管理器
来源：http://dali.hfpthk.cn/Article/details/gt2vnphlshp.html

@contextlib.contextmanager
来源：http://dali.vqdsnc.cn/Article/details/gt2lrcuewjc.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2dwhbigpz.html

list(zip(*m))
来源：http://dali.snrcjt.cn/Article/details/gt2vwfhhpax.html

[U23] Py：分块读取大文件
来源：http://dali.zhengqikj.top/Article/details/gt2uzhytbmh.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.yuanzhike.top/Article/details/gt2amycximb.html

[U24] Py：路径操作
来源：http://dali.hysaishi.cn/Article/details/gt2gzllxpcm.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ktnubyjj.html


<!-- 参考信息 -->