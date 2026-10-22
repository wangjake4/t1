代发 wailian999

split -l 1000 big.log part_
来源：http://dali.chenzaomai.com/Article/details/gt2uoohqazo.html

[R74] 批量重命名
来源：http://dali.yvedp.cn/Article/details/gt2vxexknht.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.yj20258.top/Article/details/gt2oaphorvd.html

[R75] 导出环境变量
来源：http://dali.guannengcc.top/Article/details/gt2yfizmyhk.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.hammf.cn/Article/details/gt2fqpqmnst.html

[R76] 使用临时文件
来源：http://dali.jiagoushi.top/Article/details/gt2nwdmoygi.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhixingplan.top/Article/details/gt2dxnaacml.html

[R77] 读取用户输入
来源：http://dali.hammf.cn/Article/details/gt2oqzekgbj.html

read -rp "请输入: " ans
来源：http://dali.yangfankeji.com/Article/details/gt2cteiojzg.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2aejjezqa.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.ehwqpu.com/Article/details/gt2aqrfaehe.html

[R79] 解析命令行选项
来源：http://dali.quarkkingdee.top/Article/details/gt2bhzyffgm.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.jqgufenzy.top/Article/details/gt2evmriljv.html

[R80] 查看脚本执行耗时
来源：http://dali.nanxinkj.top/Article/details/gt2yybjuphy.html

time ./run.sh
来源：http://dali.yanxiufei.cn/Article/details/gt2tfwdecmb.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gt2vssrpygc.html

S. C / C++ 专题
来源：http://dali.gzhubu.top/Article/details/gt2fhcsyrzz.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2kxlmkpms.html

[S01] C：Hello World
来源：http://dali.jyoumei.cn/Article/details/gt2suwrshjv.html

#include <stdio.h>
来源：http://dali.yuxming.cn/Article/details/gt2ifltvgtb.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.jqgfzy.top/Article/details/gt2wbehcvni.html

[S02] C：变量与格式化输出
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ulnbxwhn.html

int a = 10; printf("%d\n", a);
来源：http://dali.wangdashe.top/Article/details/gt2tpdppkea.html

[S03] C：读入整数
来源：http://dali.fzhhl.top/Article/details/gt2eykcrcpq.html

int x; scanf("%d", &x);
来源：http://dali.jlsjyb.cn/Article/details/gt2mcizlphk.html

[S04] C：字符串复制
来源：http://dali.svipenyu.cn/Article/details/gt2gflerjve.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.hysaishi.cn/Article/details/gt2cvbkchpu.html

[S05] C：字符串长度
来源：http://dali.jlsjyb.cn/Article/details/gt2fkobnrqj.html

strlen(s)
来源：http://dali.sysykeji.top/Article/details/gt2ayaqwzay.html

[S06] C：字符串比较
来源：http://dali.sysykeji.top/Article/details/gt2jyvrqqig.html

strcmp(a, b) == 0
来源：http://dali.jinqigfzy.top/Article/details/gt2noaqznzz.html

[S07] C：数组遍历求和
来源：http://dali.jqgfzy.top/Article/details/gt2ewqupvsf.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.gaohongyu789.top/Article/details/gt2dxwavgiv.html

[S08] C：动态内存分配与释放
来源：http://dali.ppjwa.cn/Article/details/gt2nooomjwc.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.iojbl.cn/Article/details/gt2hihgislr.html

[S09] C：结构体定义与初始化
来源：http://dali.jiagoushi.top/Article/details/gt2ussgtncv.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.mhx1999.top/Article/details/gt2qnfoigjt.html

[S10] C：指针与解引用
来源：http://dali.fzhhl.top/Article/details/gt2tqdtyvrr.html

int *p = &a;  *p = 5;
来源：http://dali.andypj.xyz/Article/details/gt2xxonzsxp.html

[S11] C：逐行读文件
来源：http://dali.daxiang520.top/Article/details/gt2efdrpcxs.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.wangdashe.top/Article/details/gt2frlyydsn.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.ivvv.top/Article/details/gt2gybwdjxo.html

fclose(f);
来源：http://dali.hfpthk.cn/Article/details/gt2tjaqmuco.html

[S12] C：写文件
来源：http://dali.ppjwa.cn/Article/details/gt2zybjtvdm.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.jlsjyb.cn/Article/details/gt2swfhmwep.html

[S13] C：宏定义
来源：http://dali.jinqigufen.top/Article/details/gt2sculecms.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uinbwgcy.html

[S14] C：枚举
来源：http://dali.shangyingyoupin.top/Article/details/gt2vwqvxxag.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.yj20258888.top/Article/details/gt2bqilkeut.html

[S15] C：类型转换
来源：http://dali.ehwqpu.com/Article/details/gt2rdhekhsi.html

(double) a / b
来源：http://dali.hfpthk.cn/Article/details/gt2dscezvvg.html

[S16] C：位操作置位
来源：http://dali.fengsongda.top/Article/details/gt2qlatbkde.html

x |= (1 << 3);
来源：http://dali.yj202588.top/Article/details/gt2ugkoadml.html

[S17] C：安全拼接字符串
来源：http://dali.aibaodan.cn/Article/details/gt2rmospgyd.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.iojbl.cn/Article/details/gt2utwdbtsm.html

[S18] C：命令行参数
来源：http://dali.jiagoushi.top/Article/details/gt2uhtmtrhp.html

int main(int argc, char **argv)
来源：http://dali.aizwys.cn/Article/details/gt2ubqbmvfn.html

[S19] C：快速排序
来源：http://dali.daria6918.cn/Article/details/gt2cvxuozqf.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.yonumen.top/Article/details/gt2mgfufkty.html

[S20] C：二分查找
来源：http://dali.kuanghao11.cn/Article/details/gt2ckvtulov.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.guowangkeji.top/Article/details/gt2jhrneazx.html

[S21] C：字符类别判断
来源：http://dali.cheryme.top/Article/details/gt2mszhdwsb.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.jqgfzy.top/Article/details/gt2wxlbziea.html

[S22] C：字符串转数字
来源：http://dali.gotoacloud.top/Article/details/gt2doqstxkz.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.0kj1m.cn/Article/details/gt2flatghcd.html

[S23] C：随机数
来源：http://dali.ehwqpu.com/Article/details/gt2ktogbpsf.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhiwuduotai.top/Article/details/gt2elnyweoj.html

[S24] C：获取本地时间
来源：http://dali.zycfv.cn/Article/details/gt2uceypvvi.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.pengpengdd.cyou/Article/details/gt2aiehnunz.html

[S25] C：内存拷贝
来源：http://dali.cheryme.top/Article/details/gt2rljmsajx.html

memcpy(dst, src, n);
来源：http://dali.quarkkingdee.top/Article/details/gt2hhxtlaei.html

[S26] C：内存清零
来源：http://dali.xuetiantiany.cn/Article/details/gt2iwmxagwb.html

memset(a, 0, sizeof a);
来源：http://dali.ydzc1.top/Article/details/gt2ovwttqsm.html

[S27] C：定义常量
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fvtkpwon.html

const double PI = 3.14159;
来源：http://dali.yonumen.top/Article/details/gt2nopuurbc.html

[S28] C：静态变量
来源：http://dali.yongpay.top/Article/details/gt2ibzaetng.html

static int counter = 0;
来源：http://dali.shzxlz.cn/Article/details/gt2dvyjnubs.html

[S29] C：变参函数
来源：http://dali.jinqigufen.top/Article/details/gt2bamrlixe.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.vqdsnc.cn/Article/details/gt2hhmlcprt.html

[S30] C：头文件保护
来源：http://dali.feifeiyinyue.top/Article/details/gt2mwlwfsmf.html

#ifndef X_H
来源：http://dali.cqqwz.cn/Article/details/gt2eavpcntm.html

#define X_H
来源：http://dali.yonumen.top/Article/details/gt2xlmcevdd.html

#endif
来源：http://dali.cdnleiting.top/Article/details/gt2shsdswch.html

[S31] C++：Hello World
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yzlgqaky.html

#include <iostream>
来源：http://dali.jinqigufen.top/Article/details/gt2khzsvjju.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2inrlhcko.html

[S32] C++：字符串
来源：http://dali.jinqigufen.top/Article/details/gt2sddhjixw.html

std::string s = "hi";  s += "!";
来源：http://dali.yj20258888.top/Article/details/gt2whuktqxs.html

[S33] C++：vector 增删
来源：http://dali.sufxvd.cn/Article/details/gt2smiaignl.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.yj20258.top/Article/details/gt2tgfopumt.html

[S34] C++：遍历 vector
来源：http://dali.gogol.net.cn/Article/details/gt2tdeygrqm.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.quarkkingdee.top/Article/details/gt2htqtsmer.html

[S35] C++：map
来源：http://dali.jyoumei.cn/Article/details/gt2axpvauno.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jlsjyb.cn/Article/details/gt2vrhhswgf.html

[S36] C++：unordered_map
来源：http://dali.birdmap.top/Article/details/gt2yespafvx.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.quarkkingdee.top/Article/details/gt2gnczakwe.html

[S37] C++：set
来源：http://dali.zdqjudy.top/Article/details/gt2rtcaxotg.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.aibaodan.cn/Article/details/gt2zopypadb.html

[S38] C++：排序
来源：http://dali.daxiang520.top/Article/details/gt2xlrsldwa.html

std::sort(v.begin(), v.end());
来源：http://dali.yuanzhike.top/Article/details/gt2rcqtwasr.html

[S39] C++：自定义比较器排序
来源：http://dali.zhoulong.xyz/Article/details/gt2lckzqfbq.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.mhx1999.top/Article/details/gt2ymhgycvc.html

[S40] C++：查找元素
来源：http://dali.ybcxt.top/Article/details/gt2rpwwlumr.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.chenzaomai.com/Article/details/gt2rdtsaoov.html

[S41] C++：类与构造函数
来源：http://dali.ybcxt.top/Article/details/gt2hiqwwndb.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.aibaodan.cn/Article/details/gt2aepahacn.html

[S42] C++：继承与虚函数
来源：http://dali.hammf.cn/Article/details/gt2xgtrcfqd.html

class B : public Base { public: void f() override {} };
来源：http://dali.ivvv.top/Article/details/gt2yskbpdvv.html

[S43] C++：智能指针
来源：http://dali.aizwys.cn/Article/details/gt2iqmrqcqh.html

auto p = std::make_unique<int>(5);
来源：http://dali.cheryme.top/Article/details/gt2cornnovt.html

[S44] C++：引用传参
来源：http://dali.mhx1999.top/Article/details/gt2pwxqdmfc.html

void inc(int &x) { ++x; }
来源：http://dali.yj20258888.top/Article/details/gt2ipltpgus.html

[S45] C++：lambda
来源：http://dali.aizwys.cn/Article/details/gt2wepdjtyr.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.ppjwa.cn/Article/details/gt2mqcftacf.html

[S46] C++：函数模板
来源：http://dali.daxiang520.top/Article/details/gt2moynnzjx.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.ydzc1.top/Article/details/gt2azgriqyk.html

[S47] C++：结构化绑定遍历
来源：http://dali.wangdashe.top/Article/details/gt2pinqfmvf.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.yangfankeji.com/Article/details/gt2pbqyxavt.html

[S48] C++：逐行读文件
来源：http://dali.yj20258.top/Article/details/gt2djcmkzxl.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zycfv.cn/Article/details/gt2cebvhtzp.html

while (std::getline(in, line)) { }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ckbmavwl.html

[S49] C++：写文件
来源：http://dali.birdmap.top/Article/details/gt2skchtrbp.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.birdmap.top/Article/details/gt2nwklnloa.html

[S50] C++：格式化数字
来源：http://dali.pycfn.com/Article/details/gt2lrxdjxgi.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wvrpardt.html

[S51] C++：显式类型转换
来源：http://dali.jinqigfzy.top/Article/details/gt2mrftpuzl.html

static_cast<double>(a) / b
来源：http://dali.nwbrower.top/Article/details/gt2urlnxapj.html

[S52] C++：const 与 noexcept
来源：http://dali.yvedp.cn/Article/details/gt2nxjkvjdt.html

int size() const noexcept { return n_; }
来源：http://dali.yj202588.top/Article/details/gt2doxqvuuq.html

[S53] C++：移动语义
来源：http://dali.0kj1m.cn/Article/details/gt2nliziuhe.html

std::vector<int> w = std::move(v);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fkzuiwru.html

[S54] C++：异常处理
来源：http://dali.gaohongyu789.top/Article/details/gt2bwjtazsc.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.tanke756.top/Article/details/gt2mwyqwhok.html

[S55] C++：结构化绑定
来源：http://dali.hnqzz.top/Article/details/gt2aprutayh.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2huandcjb.html

[S56] C++：optional
来源：http://dali.xziqi.cn/Article/details/gt2obirgfjl.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2nqkgwnsx.html

[S57] C++：编译期常量
来源：http://dali.svipenyu.cn/Article/details/gt2awdkfbqr.html

constexpr int N = 10;
来源：http://dali.shuidangran.top/Article/details/gt2kurnytzv.html

[S58] C++：命名空间
来源：http://dali.xylfe.cn/Article/details/gt2gzsrdrco.html

namespace ns { int f() { return 1; } }
来源：http://dali.bjfxy.top/Article/details/gt2enscpxgj.html

[S59] C++：静态断言
来源：http://dali.shzxlz.cn/Article/details/gt2ywmreegm.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.yuxming.cn/Article/details/gt2erqohdwr.html

[S60] C++：遍历并删除元素
来源：http://dali.iojbl.cn/Article/details/gt2lqbgqnjn.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.aibaodan.cn/Article/details/gt2jqqcwefo.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2kvolnzfc.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhoulong.xyz/Article/details/gt2legqodnx.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2hnpueeqy.html

[T01] Kotlin：Hello World
来源：http://dali.ivvv.top/Article/details/gt2akogokxv.html

println("Hello")
来源：http://dali.sufxvd.cn/Article/details/gt2wuaotppr.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ltezthnw.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.feifeiyinyue.top/Article/details/gt2cgklhfff.html

[T03] Kotlin：字符串模板
来源：http://dali.zhengqikj.top/Article/details/gt2gvhhbhsy.html

"值: $b"
来源：http://dali.tianlin.xyz/Article/details/gt2bryozlbt.html

[T04] Kotlin：空安全
来源：http://dali.cqqwz.cn/Article/details/gt2rmwlrnct.html

val n: String? = null;  n?.length
来源：http://dali.fzhhl.top/Article/details/gt2gaowssmp.html

[T05] Kotlin：when 表达式
来源：http://dali.zhengqikj.top/Article/details/gt2awnomows.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.tanke756.top/Article/details/gt2xoqczqhd.html

[T06] Kotlin：集合映射
来源：http://dali.pengpengdd.cyou/Article/details/gt2qxgqghtf.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.gogol.net.cn/Article/details/gt2rpdirrdh.html

[T07] Kotlin：集合过滤
来源：http://dali.cucudq.cn/Article/details/gt2gpudsnmc.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.redwolf501.top/Article/details/gt2mgiytzwc.html

[T08] Kotlin：数据类
来源：http://dali.birdmap.top/Article/details/gt2rzwzwppf.html

data class User(val name: String, val age: Int)
来源：http://dali.cashguo.top/Article/details/gt2ejatsglc.html

[T09] Kotlin：扩展函数
来源：http://dali.c1oappe.top/Article/details/gt2myvycgbr.html

fun String.exclaim() = this + "!"
来源：http://dali.gzhubu.top/Article/details/gt2gzprmtvb.html

[T10] Kotlin：默认参数
来源：http://dali.zdqjudy.top/Article/details/gt2lxtdcmve.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.wangdashe.top/Article/details/gt2iqapsfnc.html

[T11] Kotlin：协程
来源：http://dali.fzhhl.top/Article/details/gt2aycsmxbo.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.quarkkingdee.top/Article/details/gt2ijeoabuq.html

[T12] Kotlin：解构声明
来源：http://dali.hammf.cn/Article/details/gt2fdcnmwnd.html

val (a, b) = Pair(1, 2)
来源：http://dali.zycfv.cn/Article/details/gt2murohlzy.html

[T13] Kotlin：只读 Map
来源：http://dali.daxiang520.top/Article/details/gt2khvwprli.html

val m = mapOf("a" to 1)
来源：http://dali.cdnleiting.top/Article/details/gt2xmsbsywv.html

[T14] Kotlin：循环
来源：http://dali.snrcjt.cn/Article/details/gt2eeehwdko.html

for (i in 1..10) println(i)
来源：http://dali.tian-w.cn/Article/details/gt2rxlbwmmo.html

[T15] Kotlin：接口
来源：http://dali.kuanghao11.cn/Article/details/gt2zlhrjudt.html

interface Shape { fun area(): Double }
来源：http://dali.cheryme.top/Article/details/gt2elaimvhj.html

[T16] Swift：Hello World
来源：http://dali.yonumen.top/Article/details/gt2tckctqiy.html

print("Hello")
来源：http://dali.chenzaomai.com/Article/details/gt2rdocognf.html

[T17] Swift：变量与常量
来源：http://dali.nwbrower.top/Article/details/gt2ybugwpzk.html

var a = 1;  let b = 2
来源：http://dali.cqqwz.cn/Article/details/gt2sfrabxvs.html

[T18] Swift：字符串插值
来源：http://dali.jqgfzy.top/Article/details/gt2qzqmqkdg.html

"值: \(b)"
来源：http://dali.zycfv.cn/Article/details/gt2csqnroyd.html

[T19] Swift：可选绑定
来源：http://dali.dianchejie.cn/Article/details/gt2mxejssrf.html

if let n = opt { print(n) }
来源：http://dali.cashguo.top/Article/details/gt2wsdcuphq.html

[T20] Swift：数组操作
来源：http://dali.svipenyu.cn/Article/details/gt2bmyztqif.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.haohaochexian.top/Article/details/gt2nefjdhen.html

[T21] Swift：遍历
来源：http://dali.zdqjudy.top/Article/details/gt2plogekqn.html

for x in a { print(x) }
来源：http://dali.zhongyouzk.top/Article/details/gt2yxezfjzo.html

[T22] Swift：字典
来源：http://dali.316326.xyz/Article/details/gt2kgvfubng.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.redwolf501.top/Article/details/gt2lneorxqr.html

[T23] Swift：函数
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ohakzfcv.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.hongshengwenyu.top/Article/details/gt2opapbcqu.html

[T24] Swift：闭包
来源：http://dali.hnxiangtu.top/Article/details/gt2adwcccsx.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhoulong.xyz/Article/details/gt2aovwumyu.html

[T25] Swift：结构体
来源：http://dali.shangyingyoupin.top/Article/details/gt2knnkzlsw.html

struct P { var x: Int }
来源：http://dali.hywenlv.cn/Article/details/gt2zpoxqsvw.html

[T26] Swift：类与重写
来源：http://dali.yongpay.top/Article/details/gt2rfcrozmk.html

class A: Base { override func f() {} }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2klcllite.html

[T27] Swift：错误处理
来源：http://dali.birdmap.top/Article/details/gt2pxptlwoi.html

do { try f() } catch { print(error) }
来源：http://dali.xinyue.icu/Article/details/gt2pyvnizam.html

[T28] Swift：枚举
来源：http://dali.hongshengwenyu.top/Article/details/gt2wphqjuuu.html

enum Color { case red, green }
来源：http://dali.c1oappe.top/Article/details/gt2bbzwiumj.html

[T29] Swift：guard 提前返回
来源：http://dali.yuanzhike.top/Article/details/gt2rbacbtdb.html

guard let x = opt else { return }
来源：http://dali.meibo888.top/Article/details/gt2pvqcqblx.html

[T30] Swift：协议
来源：http://dali.jianghu66.top/Article/details/gt2qwniuhrq.html

protocol Shape { func area() -> Double }
来源：http://dali.jinqigfzy.top/Article/details/gt2gdhpqtiv.html

[T31] Lua：Hello World
来源：http://dali.yuxming.cn/Article/details/gt2rdvicoic.html

print("Hello")
来源：http://dali.chenzaomai.com/Article/details/gt2qkxqufjq.html

[T32] Lua：局部变量
来源：http://dali.yvedp.cn/Article/details/gt2pdriggcr.html

local a = 1
来源：http://dali.sxryk.cn/Article/details/gt2bmcqaqwe.html

[T33] Lua：表（数组）
来源：http://dali.yueranfly.top/Article/details/gt2qhovuadi.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.birdmap.top/Article/details/gt2jokarqup.html

[T34] Lua：遍历表
来源：http://dali.gzhubu.top/Article/details/gt2lpverhrt.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2mjppambf.html

[T35] Lua：字典表
来源：http://dali.nwbrower.top/Article/details/gt2uhrcwocg.html

local d = { a = 1 };  d.b = 2
来源：http://dali.jqgfzy.top/Article/details/gt2bpsdwtjb.html

[T36] Lua：函数
来源：http://dali.xziqi.cn/Article/details/gt2kspnrpic.html

function add(a, b) return a + b end
来源：http://dali.feifeiyinyue.top/Article/details/gt2njlgdhmh.html

[T37] Lua：字符串拼接
来源：http://dali.cqqwz.cn/Article/details/gt2knpzvqpj.html

"a" .. "b"
来源：http://dali.gaohongyu789.top/Article/details/gt2hhsnpjny.html

[T38] Lua：条件
来源：http://dali.sxryk.cn/Article/details/gt2snfmuelc.html

if x > 0 then print("正") end
来源：http://dali.shanyushiyangtech.top/Article/details/gt2obbxiuls.html

[T39] Lua：模式匹配
来源：http://dali.shangyingyoupin.top/Article/details/gt2qviocyqh.html

string.find(s, "%d+")
来源：http://dali.aizwys.cn/Article/details/gt2dhjrpvqp.html

[T40] Lua：元表
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jymgfjen.html

setmetatable({}, { __index = base })
来源：http://dali.hysaishi.cn/Article/details/gt2rnkztfmh.html

[T41] Perl：Hello World
来源：http://dali.shuidangran.top/Article/details/gt2xymrzxrj.html

print "Hello\n";
来源：http://dali.aizwys.cn/Article/details/gt2mwoiqmhb.html

[T42] Perl：变量类型
来源：http://dali.chenzaomai.com/Article/details/gt2nijbmzky.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.chenzaomai.com/Article/details/gt2ugjhpsbe.html

[T43] Perl：字符串插值
来源：http://dali.hywenlv.cn/Article/details/gt2cssrlzdj.html

"值: $a"
来源：http://dali.iojbl.cn/Article/details/gt2nuudcquk.html

[T44] Perl：条件
来源：http://dali.jinqigufen.top/Article/details/gt2mbkhrkqd.html

if ($a > 0) { print "正"; }
来源：http://dali.cheryme.top/Article/details/gt2dwrxjeic.html

[T45] Perl：数组遍历
来源：http://dali.yj20258.top/Article/details/gt2yynmunnp.html

for my $x (@arr) { print $x; }
来源：http://dali.hfpthk.cn/Article/details/gt2qotnagjb.html

[T46] Perl：哈希操作
来源：http://dali.meibo888.top/Article/details/gt2odyfeibr.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.guowangkeji.top/Article/details/gt2vszovyyw.html

[T47] Perl：正则捕获
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rlhrmrlh.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.cucudq.cn/Article/details/gt2ekhgcpjk.html

[T48] Perl：正则替换
来源：http://dali.shanyushiyangtech.top/Article/details/gt2iysyxpws.html

$s =~ s/old/new/g;
来源：http://dali.redwolf501.top/Article/details/gt2mhpguhbf.html

[T49] Perl：函数
来源：http://dali.yuanzhike.top/Article/details/gt2lgrthkdn.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.gzhubu.top/Article/details/gt2ermqaydx.html

[T50] Perl：逐行读文件
来源：http://dali.daxiang520.top/Article/details/gt2iescrtol.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.feifeiyinyue.top/Article/details/gt2fpdpnayf.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yzzlkdcr.html

[T51] Scala：Hello World
来源：http://dali.chenlongwang.top/Article/details/gt2ofjtihcm.html

println("Hello")
来源：http://dali.fzhhl.top/Article/details/gt2vscdujtu.html

[T52] Scala：变量
来源：http://dali.pengpengdd.cyou/Article/details/gt2wlevzaaw.html

val a = 1;  var b = 2
来源：http://dali.ivvv.top/Article/details/gt2zgxcgqjf.html

[T53] Scala：字符串插值
来源：http://dali.yj20258888.top/Article/details/gt2fmoryhbz.html

s"值: $b"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cvbfgcfl.html

[T54] Scala：集合映射
来源：http://dali.xziqi.cn/Article/details/gt2frrpiadh.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.hfpthk.cn/Article/details/gt2yslaodom.html

[T55] Scala：集合过滤
来源：http://dali.cucudq.cn/Article/details/gt2dtrbalyi.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.bjfxy.top/Article/details/gt2mfgmbbyw.html

[T56] Scala：样例类
来源：http://dali.nanxuanxn.top/Article/details/gt2uivvvcdx.html

case class User(name: String, age: Int)
来源：http://dali.bjfxy.top/Article/details/gt2mdyulbst.html

[T57] Scala：模式匹配
来源：http://dali.haohaochexian.top/Article/details/gt2ouifthln.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.xylfe.cn/Article/details/gt2zvsotgiz.html

[T58] Scala：函数定义
来源：http://dali.xziqi.cn/Article/details/gt2megwumsz.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.guannengcc.top/Article/details/gt2fagalhrz.html

[T59] Scala：循环
来源：http://dali.dashuyun.cn/Article/details/gt2hngxebrg.html

for (i <- 1 to 10) println(i)
来源：http://dali.yj20258.top/Article/details/gt2vejraqbw.html

[T60] Scala：折叠
来源：http://dali.zdqjudy.top/Article/details/gt2eygdkgqk.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.chenzaomai.com/Article/details/gt2fctvcrlz.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2lckhsmom.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.tanke756.top/Article/details/gt2ianqaxhi.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gsamowzf.html

[U01] Py：创建虚拟环境
来源：http://dali.iojbl.cn/Article/details/gt2bojmqftp.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.jinghuilouyu.cn/Article/details/gt2osnbuaut.html

[U02] Py：导出 / 安装依赖
来源：http://dali.iojbl.cn/Article/details/gt2ezfxymyc.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.cucudq.cn/Article/details/gt2hsduvisp.html

[U03] Py：加载 .env 配置
来源：http://dali.kuanghao11.cn/Article/details/gt2dttkoyeq.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.hfpthk.cn/Article/details/gt2fwwwacdy.html

[U04] Py：变量调试打印
来源：http://dali.ivvv.top/Article/details/gt2slnahjtl.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.xuetiantiany.cn/Article/details/gt2gfdtmxpo.html

[U05] Py：列表去重且保序
来源：http://dali.hysaishi.cn/Article/details/gt2ifczuspa.html

list(dict.fromkeys(arr))
来源：http://dali.cashguo.top/Article/details/gt2wpjpedqe.html

[U06] Py：合并两个字典
来源：http://dali.yj20258.top/Article/details/gt2qwcryfpn.html

{**a, **b}
来源：http://dali.ydzc1.top/Article/details/gt2qxsxhoro.html

[U07] Py：反转字典键值
来源：http://dali.gotoacloud.top/Article/details/gt2mktpamir.html

{v: k for k, v in d.items()}
来源：http://dali.feifeiyinyue.top/Article/details/gt2ddcsiezz.html

[U08] Py：展平二维列表
来源：http://dali.haohaochexian.top/Article/details/gt2glilrhsh.html

[y for x in nested for y in x]
来源：http://dali.sweek.top/Article/details/gt2iaavvdrk.html

[U09] Py：字典取最大值的键
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2caprmurl.html

max(d, key=d.get)
来源：http://dali.yj20258888.top/Article/details/gt2upqhlxqx.html

[U10] Py：按值排序字典
来源：http://dali.cqqwz.cn/Article/details/gt2gywgnrbr.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.guowangkeji.top/Article/details/gt2ohbrlvwy.html

[U11] Py：生成器表达式
来源：http://dali.hywenlv.cn/Article/details/gt2uqqhclim.html

(x * 2 for x in arr)
来源：http://dali.shzxlz.cn/Article/details/gt2vtwlknrv.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.iojbl.cn/Article/details/gt2bpzioeio.html

Counter(arr).most_common(3)
来源：http://dali.pycfn.com/Article/details/gt2pkfuzqtl.html

[U13] Py：固定长度队列
来源：http://dali.zhoulong.xyz/Article/details/gt2rvjmrnfj.html

deque(maxlen=10)
来源：http://dali.guannengcc.top/Article/details/gt2dfufxlqv.html

[U14] Py：分组收集到列表
来源：http://dali.feifeiyinyue.top/Article/details/gt2ehdthpdv.html

defaultdict(list)
来源：http://dali.jlsjyb.cn/Article/details/gt2sbtiabpf.html


<!-- 参考信息 -->