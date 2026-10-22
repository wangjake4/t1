代发 wailian999

split -l 1000 big.log part_
来源：http://dali.tanke756.top/Article/details/gt2dpukhynw.html

[R74] 批量重命名
来源：http://dali.yueranfly.top/Article/details/gt2vupqipgn.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2iokyessw.html

[R75] 导出环境变量
来源：http://dali.chenlongwang.top/Article/details/gt2ahfzjwzx.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.smart0.xyz/Article/details/gt2kgxtkcpt.html

[R76] 使用临时文件
来源：http://dali.yanxiufei.cn/Article/details/gt2asjhrlvp.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.guowangkeji.top/Article/details/gt2lyaelyiu.html

[R77] 读取用户输入
来源：http://dali.fengsongda.top/Article/details/gt2lwizumrp.html

read -rp "请输入: " ans
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2awmxayad.html

[R78] 交互式菜单
来源：http://dali.quarkkingdee.top/Article/details/gt2gamjlinb.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.fzhhl.top/Article/details/gt2inmywzkt.html

[R79] 解析命令行选项
来源：http://dali.gzhubu.top/Article/details/gt2mkxqjpal.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.c1oappe.top/Article/details/gt2ttidhmdh.html

[R80] 查看脚本执行耗时
来源：http://dali.aibaodan.cn/Article/details/gt2nbpdxpzs.html

time ./run.sh
来源：http://dali.quarkkingdee.top/Article/details/gt2izcnpzwr.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2rrruyljs.html

S. C / C++ 专题
来源：http://dali.xinyue.icu/Article/details/gt2iajjfxox.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2ctbolrlm.html

[S01] C：Hello World
来源：http://dali.316326.xyz/Article/details/gt2chmviujk.html

#include <stdio.h>
来源：http://dali.ppjwa.cn/Article/details/gt2iuguckcb.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.tian-w.cn/Article/details/gt2nkskbfxs.html

[S02] C：变量与格式化输出
来源：http://dali.sysykeji.top/Article/details/gt2slcwacvh.html

int a = 10; printf("%d\n", a);
来源：http://dali.nwbrower.top/Article/details/gt2iymzxbui.html

[S03] C：读入整数
来源：http://dali.yonumen.top/Article/details/gt2tymalzuw.html

int x; scanf("%d", &x);
来源：http://dali.aibaodan.cn/Article/details/gt2tzllvdrx.html

[S04] C：字符串复制
来源：http://dali.wangdashe.top/Article/details/gt2zbutacst.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uylgpnmf.html

[S05] C：字符串长度
来源：http://dali.haohaochexian.top/Article/details/gt2dqynpgrk.html

strlen(s)
来源：http://dali.zhoulong.xyz/Article/details/gt2vpcrzsvj.html

[S06] C：字符串比较
来源：http://dali.hywenlv.cn/Article/details/gt2tjnnjsbb.html

strcmp(a, b) == 0
来源：http://dali.xziqi.cn/Article/details/gt2iopgnyal.html

[S07] C：数组遍历求和
来源：http://dali.tanke756.top/Article/details/gt2zjjbznis.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.cqqwz.cn/Article/details/gt2lnmbxmje.html

[S08] C：动态内存分配与释放
来源：http://dali.gzhubu.top/Article/details/gt2jnrjjlgx.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.sufxvd.cn/Article/details/gt2ixqccsun.html

[S09] C：结构体定义与初始化
来源：http://dali.cheryme.top/Article/details/gt2fpekrcci.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.quarkkingdee.top/Article/details/gt2khhwnvrt.html

[S10] C：指针与解引用
来源：http://dali.ybcxt.top/Article/details/gt2xvimjzgo.html

int *p = &a;  *p = 5;
来源：http://dali.hammf.cn/Article/details/gt2zupnhtjt.html

[S11] C：逐行读文件
来源：http://dali.gogol.net.cn/Article/details/gt2aobguvdb.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.fengsongda.top/Article/details/gt2inuldazi.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.ehwqpu.com/Article/details/gt2myhfyfth.html

fclose(f);
来源：http://dali.mhx1999.top/Article/details/gt2cepsmvll.html

[S12] C：写文件
来源：http://dali.jinqigfzy.top/Article/details/gt2ikygovyc.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cvfizzkx.html

[S13] C：宏定义
来源：http://dali.yueranfly.top/Article/details/gt2uwncfzxh.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mpnwlwmg.html

[S14] C：枚举
来源：http://dali.havefunace.top/Article/details/gt2qnjrkcsh.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.yangfankeji.com/Article/details/gt2gajgnmna.html

[S15] C：类型转换
来源：http://dali.vqdsnc.cn/Article/details/gt2ouxwubbu.html

(double) a / b
来源：http://dali.cheryme.top/Article/details/gt2njeqzppw.html

[S16] C：位操作置位
来源：http://dali.9152youxi.cn/Article/details/gt2zmfytmlw.html

x |= (1 << 3);
来源：http://dali.dianchejie.cn/Article/details/gt2ukbasros.html

[S17] C：安全拼接字符串
来源：http://dali.hammf.cn/Article/details/gt2ouvebxdg.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhiwuduotai.top/Article/details/gt2gbcdjisa.html

[S18] C：命令行参数
来源：http://dali.meibo888.top/Article/details/gt2nnzmpwok.html

int main(int argc, char **argv)
来源：http://dali.tanke756.top/Article/details/gt2zfpyziph.html

[S19] C：快速排序
来源：http://dali.shangyingyoupin.top/Article/details/gt2mizjrqni.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.yongpay.top/Article/details/gt2acekbyht.html

[S20] C：二分查找
来源：http://dali.9152youxi.cn/Article/details/gt2pzqayzvp.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.jinqigufen.top/Article/details/gt2gzbgltat.html

[S21] C：字符类别判断
来源：http://dali.cheryme.top/Article/details/gt2xuxniqwc.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.cheryme.top/Article/details/gt2tlkwzqju.html

[S22] C：字符串转数字
来源：http://dali.fzhhl.top/Article/details/gt2zhfvkxsy.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.dashuyun.cn/Article/details/gt2uqdtfhcg.html

[S23] C：随机数
来源：http://dali.yj202588.top/Article/details/gt2gxrguowk.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.nanxuanxn.top/Article/details/gt2cepfdsiz.html

[S24] C：获取本地时间
来源：http://dali.jianghu66.top/Article/details/gt2rouapugr.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zycfv.cn/Article/details/gt2sxxtdzfm.html

[S25] C：内存拷贝
来源：http://dali.svipenyu.cn/Article/details/gt2zaudmjbr.html

memcpy(dst, src, n);
来源：http://dali.haohaochexian.top/Article/details/gt2ivbnmtbv.html

[S26] C：内存清零
来源：http://dali.yonumen.top/Article/details/gt2mooildqw.html

memset(a, 0, sizeof a);
来源：http://dali.ydzc1.top/Article/details/gt2ubzygrzg.html

[S27] C：定义常量
来源：http://dali.jinqigfzy.top/Article/details/gt2dyrwkgdr.html

const double PI = 3.14159;
来源：http://dali.svipenyu.cn/Article/details/gt2fkdhjsib.html

[S28] C：静态变量
来源：http://dali.yuxming.cn/Article/details/gt2zpefizuy.html

static int counter = 0;
来源：http://dali.chenlongwang.top/Article/details/gt2keqwepvv.html

[S29] C：变参函数
来源：http://dali.c1oappe.top/Article/details/gt2xujklzgm.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.yonumen.top/Article/details/gt2qfucyxjc.html

[S30] C：头文件保护
来源：http://dali.dianchejie.cn/Article/details/gt2jvtqkdui.html

#ifndef X_H
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zybwcfku.html

#define X_H
来源：http://dali.tian-w.cn/Article/details/gt2eczxejku.html

#endif
来源：http://dali.daria6918.cn/Article/details/gt2dmdlmkyw.html

[S31] C++：Hello World
来源：http://dali.birdmap.top/Article/details/gt2szuryxmc.html

#include <iostream>
来源：http://dali.gaohongyu789.top/Article/details/gt2zgtubsku.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.yj202588.top/Article/details/gt2nyyavooa.html

[S32] C++：字符串
来源：http://dali.quarkkingdee.top/Article/details/gt2mizabjat.html

std::string s = "hi";  s += "!";
来源：http://dali.sysykeji.top/Article/details/gt2uhbnqdsr.html

[S33] C++：vector 增删
来源：http://dali.wangdashe.top/Article/details/gt2mwbctryq.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.aibaodan.cn/Article/details/gt2nxpshlwl.html

[S34] C++：遍历 vector
来源：http://dali.yonumen.top/Article/details/gt2rqqtdlpx.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.9152youxi.cn/Article/details/gt2rzsbqbir.html

[S35] C++：map
来源：http://dali.shangyingyoupin.top/Article/details/gt2elkwgxgz.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.ehwqpu.com/Article/details/gt2pkwygpoi.html

[S36] C++：unordered_map
来源：http://dali.jqgfzy.top/Article/details/gt2ffnoseql.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.aibaodan.cn/Article/details/gt2cpvgtxlu.html

[S37] C++：set
来源：http://dali.sweek.top/Article/details/gt2jujgkfis.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.0kj1m.cn/Article/details/gt2rilyofky.html

[S38] C++：排序
来源：http://dali.jianghu66.top/Article/details/gt2dbnxawbw.html

std::sort(v.begin(), v.end());
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2axmvzqpu.html

[S39] C++：自定义比较器排序
来源：http://dali.dashuyun.cn/Article/details/gt2lygruwoy.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kpgucntp.html

[S40] C++：查找元素
来源：http://dali.jinqigfzy.top/Article/details/gt2pcqyplvp.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.xuetiantiany.cn/Article/details/gt2pdfujqqg.html

[S41] C++：类与构造函数
来源：http://dali.jinqigfzy.top/Article/details/gt2almbyuaj.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.tanke756.top/Article/details/gt2rljdfyzp.html

[S42] C++：继承与虚函数
来源：http://dali.snrcjt.cn/Article/details/gt2tulgzrbc.html

class B : public Base { public: void f() override {} };
来源：http://dali.zdqjudy.top/Article/details/gt2cbnlrcsh.html

[S43] C++：智能指针
来源：http://dali.cdnleiting.top/Article/details/gt2ifvojfno.html

auto p = std::make_unique<int>(5);
来源：http://dali.yueranfly.top/Article/details/gt2kuhjcybc.html

[S44] C++：引用传参
来源：http://dali.cdnleiting.top/Article/details/gt2ygkvamtr.html

void inc(int &x) { ++x; }
来源：http://dali.xinyue.icu/Article/details/gt2hivmtqgy.html

[S45] C++：lambda
来源：http://dali.chenjidiqi.icu/Article/details/gt2poejzwgz.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.yonumen.top/Article/details/gt2kcbanmbf.html

[S46] C++：函数模板
来源：http://dali.sufxvd.cn/Article/details/gt2dslduibf.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2xparnkip.html

[S47] C++：结构化绑定遍历
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2myzpvyfo.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.yuxming.cn/Article/details/gt2gpczmchk.html

[S48] C++：逐行读文件
来源：http://dali.mhx1999.top/Article/details/gt2uaweoyiq.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.cqqwz.cn/Article/details/gt2vasgqsoh.html

while (std::getline(in, line)) { }
来源：http://dali.shzxlz.cn/Article/details/gt2ebvzxsni.html

[S49] C++：写文件
来源：http://dali.jinqigfzy.top/Article/details/gt2qzzsqtgf.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.vqdsnc.cn/Article/details/gt2bayfmfyt.html

[S50] C++：格式化数字
来源：http://dali.jqgufenzy.top/Article/details/gt2ytxssnqz.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.quarkkingdee.top/Article/details/gt2vjwaztgz.html

[S51] C++：显式类型转换
来源：http://dali.shzxlz.cn/Article/details/gt2uvbiffzz.html

static_cast<double>(a) / b
来源：http://dali.snrcjt.cn/Article/details/gt2imuymcbh.html

[S52] C++：const 与 noexcept
来源：http://dali.wangdashe.top/Article/details/gt2nkxhkjrd.html

int size() const noexcept { return n_; }
来源：http://dali.cqqwz.cn/Article/details/gt2xmpiawfd.html

[S53] C++：移动语义
来源：http://dali.nanxuanxn.top/Article/details/gt2sbfwrtit.html

std::vector<int> w = std::move(v);
来源：http://dali.iojbl.cn/Article/details/gt2ngyktjdx.html

[S54] C++：异常处理
来源：http://dali.cheryme.top/Article/details/gt2fjlvlzpv.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.jinqigfzy.top/Article/details/gt2mgmypmxk.html

[S55] C++：结构化绑定
来源：http://dali.yj20258888.top/Article/details/gt2tkmnhyuf.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.jianghu66.top/Article/details/gt2ieoguscb.html

[S56] C++：optional
来源：http://dali.hongshengwenyu.top/Article/details/gt2kpymmwdp.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2tgdrruhu.html

[S57] C++：编译期常量
来源：http://dali.jlsjyb.cn/Article/details/gt2ikcldrbe.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2jtjwgiqt.html

[S58] C++：命名空间
来源：http://dali.ybcxt.top/Article/details/gt2breiyddu.html

namespace ns { int f() { return 1; } }
来源：http://dali.havefunace.top/Article/details/gt2spjmbwxu.html

[S59] C++：静态断言
来源：http://dali.hfpthk.cn/Article/details/gt2wqmdrvwg.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.jianghu66.top/Article/details/gt2ltdqpafw.html

[S60] C++：遍历并删除元素
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hhwvyekr.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.tian-w.cn/Article/details/gt2wmwtzgvs.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2wslwjfuu.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.wangdashe.top/Article/details/gt2mdlmeiru.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gt2opsstesr.html

[T01] Kotlin：Hello World
来源：http://dali.gotoacloud.top/Article/details/gt2fwybetjc.html

println("Hello")
来源：http://dali.ydzc1.top/Article/details/gt2szwddxsd.html

[T02] Kotlin：变量
来源：http://dali.9152youxi.cn/Article/details/gt2iwamqlsu.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.cheryme.top/Article/details/gt2qvqnxnqz.html

[T03] Kotlin：字符串模板
来源：http://dali.ehwqpu.com/Article/details/gt2kqebhnry.html

"值: $b"
来源：http://dali.tanke756.top/Article/details/gt2xfslidlw.html

[T04] Kotlin：空安全
来源：http://dali.dianchejie.cn/Article/details/gt2kfpytmki.html

val n: String? = null;  n?.length
来源：http://dali.daxiang520.top/Article/details/gt2dztkdrvs.html

[T05] Kotlin：when 表达式
来源：http://dali.tianlin.xyz/Article/details/gt2ilszssed.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.jyoumei.cn/Article/details/gt2tbmazehw.html

[T06] Kotlin：集合映射
来源：http://dali.jianghu66.top/Article/details/gt2ijglipqp.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.ydzc1.top/Article/details/gt2qoyaifkr.html

[T07] Kotlin：集合过滤
来源：http://dali.yuanzhike.top/Article/details/gt2qxjonjsb.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.sysykeji.top/Article/details/gt2lztxyqrh.html

[T08] Kotlin：数据类
来源：http://dali.jinghuilouyu.cn/Article/details/gt2awuabplx.html

data class User(val name: String, val age: Int)
来源：http://dali.zhongyouzk.top/Article/details/gt2ngudnfxg.html

[T09] Kotlin：扩展函数
来源：http://dali.wangdashe.top/Article/details/gt2kdfozlfk.html

fun String.exclaim() = this + "!"
来源：http://dali.hnqzz.top/Article/details/gt2rkpwvvlk.html

[T10] Kotlin：默认参数
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mfqbaskv.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.9152youxi.cn/Article/details/gt2emgqfnoy.html

[T11] Kotlin：协程
来源：http://dali.guowangkeji.top/Article/details/gt2fydovlhw.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.hywenlv.cn/Article/details/gt2hngfaesl.html

[T12] Kotlin：解构声明
来源：http://dali.9152youxi.cn/Article/details/gt2ytqfaeaj.html

val (a, b) = Pair(1, 2)
来源：http://dali.wangdashe.top/Article/details/gt2okpjfonm.html

[T13] Kotlin：只读 Map
来源：http://dali.shzxlz.cn/Article/details/gt2hpunwwxq.html

val m = mapOf("a" to 1)
来源：http://dali.snrcjt.cn/Article/details/gt2pharenlc.html

[T14] Kotlin：循环
来源：http://dali.jqgfzy.top/Article/details/gt2jzyslgef.html

for (i in 1..10) println(i)
来源：http://dali.shzxlz.cn/Article/details/gt2pysbzimr.html

[T15] Kotlin：接口
来源：http://dali.snrcjt.cn/Article/details/gt2hikcfmzw.html

interface Shape { fun area(): Double }
来源：http://dali.guowangkeji.top/Article/details/gt2dfrdhijz.html

[T16] Swift：Hello World
来源：http://dali.shuidangran.top/Article/details/gt2gdswpquv.html

print("Hello")
来源：http://dali.sysykeji.top/Article/details/gt2cfgvhtix.html

[T17] Swift：变量与常量
来源：http://dali.aizwys.cn/Article/details/gt2vvwvwubk.html

var a = 1;  let b = 2
来源：http://dali.cashguo.top/Article/details/gt2jmcpdkia.html

[T18] Swift：字符串插值
来源：http://dali.ydzc1.top/Article/details/gt2mdezrspg.html

"值: \(b)"
来源：http://dali.birdmap.top/Article/details/gt2cfmqaepc.html

[T19] Swift：可选绑定
来源：http://dali.snrcjt.cn/Article/details/gt2opmnlfbj.html

if let n = opt { print(n) }
来源：http://dali.guowangkeji.top/Article/details/gt2dpybyysa.html

[T20] Swift：数组操作
来源：http://dali.sxryk.cn/Article/details/gt2ksympqfm.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhoulong.xyz/Article/details/gt2fgminjhz.html

[T21] Swift：遍历
来源：http://dali.cucudq.cn/Article/details/gt2okucojjb.html

for x in a { print(x) }
来源：http://dali.zhongyouzk.top/Article/details/gt2tscuekfm.html

[T22] Swift：字典
来源：http://dali.gotoacloud.top/Article/details/gt2wfopxhcl.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.daria6918.cn/Article/details/gt2qgwxxdyh.html

[T23] Swift：函数
来源：http://dali.shzxlz.cn/Article/details/gt2ncbanthr.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.cdnleiting.top/Article/details/gt2yrpeyqrd.html

[T24] Swift：闭包
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nuamhsnw.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.snrcjt.cn/Article/details/gt2yfndkdmd.html

[T25] Swift：结构体
来源：http://dali.svipenyu.cn/Article/details/gt2gqbmmsxo.html

struct P { var x: Int }
来源：http://dali.nanxinkj.top/Article/details/gt2hhyolntg.html

[T26] Swift：类与重写
来源：http://dali.jqgfzy.top/Article/details/gt2qnhowrnx.html

class A: Base { override func f() {} }
来源：http://dali.ehwqpu.com/Article/details/gt2pojonsxu.html

[T27] Swift：错误处理
来源：http://dali.jinqigfzy.top/Article/details/gt2arlmztun.html

do { try f() } catch { print(error) }
来源：http://dali.cdnleiting.top/Article/details/gt2haljlobc.html

[T28] Swift：枚举
来源：http://dali.jqgufenzy.top/Article/details/gt2blljkogs.html

enum Color { case red, green }
来源：http://dali.jlsjyb.cn/Article/details/gt2gpwnvfxl.html

[T29] Swift：guard 提前返回
来源：http://dali.yangfankeji.com/Article/details/gt2klzjtlrh.html

guard let x = opt else { return }
来源：http://dali.nanxuanxn.top/Article/details/gt2qaasdyny.html

[T30] Swift：协议
来源：http://dali.hnqzz.top/Article/details/gt2aqkjvkmq.html

protocol Shape { func area() -> Double }
来源：http://dali.haohaochexian.top/Article/details/gt2krhrvmrf.html

[T31] Lua：Hello World
来源：http://dali.gogol.net.cn/Article/details/gt2gidgrnqa.html

print("Hello")
来源：http://dali.feifeiyinyue.top/Article/details/gt2ujgfislf.html

[T32] Lua：局部变量
来源：http://dali.hammf.cn/Article/details/gt2dejziens.html

local a = 1
来源：http://dali.svipenyu.cn/Article/details/gt2quyzfmwy.html

[T33] Lua：表（数组）
来源：http://dali.hnqzz.top/Article/details/gt2xfctngoj.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.dianchejie.cn/Article/details/gt2aadlbavd.html

[T34] Lua：遍历表
来源：http://dali.cucudq.cn/Article/details/gt2kqxdoejx.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.xziqi.cn/Article/details/gt2pspwyvnb.html

[T35] Lua：字典表
来源：http://dali.jiagoushi.top/Article/details/gt2lcyluitw.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhongyouzk.top/Article/details/gt2xgctsigw.html

[T36] Lua：函数
来源：http://dali.yvedp.cn/Article/details/gt2oizmpcmn.html

function add(a, b) return a + b end
来源：http://dali.xylfe.cn/Article/details/gt2hpqdkndi.html

[T37] Lua：字符串拼接
来源：http://dali.birdmap.top/Article/details/gt2mmfenjod.html

"a" .. "b"
来源：http://dali.bjfxy.top/Article/details/gt2njpbigij.html

[T38] Lua：条件
来源：http://dali.yj20258.top/Article/details/gt2ujtgmpix.html

if x > 0 then print("正") end
来源：http://dali.cqqwz.cn/Article/details/gt2lydeixef.html

[T39] Lua：模式匹配
来源：http://dali.dianchejie.cn/Article/details/gt2xcuaysrx.html

string.find(s, "%d+")
来源：http://dali.sufxvd.cn/Article/details/gt2dbjgcfyr.html

[T40] Lua：元表
来源：http://dali.nanxinkj.top/Article/details/gt2ffaxgglz.html

setmetatable({}, { __index = base })
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dxgqrwhd.html

[T41] Perl：Hello World
来源：http://dali.xinyue.icu/Article/details/gt2kjmlchep.html

print "Hello\n";
来源：http://dali.hammf.cn/Article/details/gt2amuufsly.html

[T42] Perl：变量类型
来源：http://dali.316326.xyz/Article/details/gt2zrrvqdbm.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.jyoumei.cn/Article/details/gt2bqaxsdtu.html

[T43] Perl：字符串插值
来源：http://dali.wangshuangyany.cn/Article/details/gt2aosrojbo.html

"值: $a"
来源：http://dali.zhengqikj.top/Article/details/gt2oweoqboc.html

[T44] Perl：条件
来源：http://dali.fzhhl.top/Article/details/gt2ybrarzrr.html

if ($a > 0) { print "正"; }
来源：http://dali.yj20258.top/Article/details/gt2zisynmmg.html

[T45] Perl：数组遍历
来源：http://dali.ybcxt.top/Article/details/gt2suqvloge.html

for my $x (@arr) { print $x; }
来源：http://dali.guowangkeji.top/Article/details/gt2zlisvcmv.html

[T46] Perl：哈希操作
来源：http://dali.nanxuanxn.top/Article/details/gt2hhewndij.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vxkevebm.html

[T47] Perl：正则捕获
来源：http://dali.cdnleiting.top/Article/details/gt2zumqmjqx.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2scubbvkz.html

[T48] Perl：正则替换
来源：http://dali.shuidangran.top/Article/details/gt2mdlljpvg.html

$s =~ s/old/new/g;
来源：http://dali.wangshuangyany.cn/Article/details/gt2rumofbbo.html

[T49] Perl：函数
来源：http://dali.cashguo.top/Article/details/gt2bdkshhza.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.hywenlv.cn/Article/details/gt2rygzdzxe.html

[T50] Perl：逐行读文件
来源：http://dali.chenlongwang.top/Article/details/gt2mbieuzyp.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.hnqzz.top/Article/details/gt2swoqbsap.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.hnxiangtu.top/Article/details/gt2lecieege.html

[T51] Scala：Hello World
来源：http://dali.bjfxy.top/Article/details/gt2tyoshkwi.html

println("Hello")
来源：http://dali.sxryk.cn/Article/details/gt2wkcwqcpg.html

[T52] Scala：变量
来源：http://dali.ivvv.top/Article/details/gt2pmrjudlx.html

val a = 1;  var b = 2
来源：http://dali.quarkkingdee.top/Article/details/gt2xrryhfhz.html

[T53] Scala：字符串插值
来源：http://dali.zhixingplan.top/Article/details/gt2thqdiilt.html

s"值: $b"
来源：http://dali.ivvv.top/Article/details/gt2mksbhmmh.html

[T54] Scala：集合映射
来源：http://dali.shuidangran.top/Article/details/gt2vaxgklbm.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.0kj1m.cn/Article/details/gt2rnfnelky.html

[T55] Scala：集合过滤
来源：http://dali.hfpthk.cn/Article/details/gt2hhlgsexb.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.ehwqpu.com/Article/details/gt2wkcssryp.html

[T56] Scala：样例类
来源：http://dali.chenzaomai.com/Article/details/gt2bowsmkvm.html

case class User(name: String, age: Int)
来源：http://dali.haohaochexian.top/Article/details/gt2mauzdtty.html

[T57] Scala：模式匹配
来源：http://dali.hfpthk.cn/Article/details/gt2qqmcqqpq.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.mhx1999.top/Article/details/gt2jnsqmyek.html

[T58] Scala：函数定义
来源：http://dali.bjfxy.top/Article/details/gt2bevwdfbl.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.sysykeji.top/Article/details/gt2lutjuhkp.html

[T59] Scala：循环
来源：http://dali.0kj1m.cn/Article/details/gt2jexrvhhy.html

for (i <- 1 to 10) println(i)
来源：http://dali.cqqwz.cn/Article/details/gt2ljokyeqp.html

[T60] Scala：折叠
来源：http://dali.cqqwz.cn/Article/details/gt2hwbmwkrz.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.c1oappe.top/Article/details/gt2yxynlbmx.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2jhttllvp.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhixingplan.top/Article/details/gt2wbhhqwmg.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gt2tvbugmda.html

[U01] Py：创建虚拟环境
来源：http://dali.xuetiantiany.cn/Article/details/gt2zzhodxxu.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.yuanzhike.top/Article/details/gt2uwgaltsg.html

[U02] Py：导出 / 安装依赖
来源：http://dali.fengsongda.top/Article/details/gt2qzggqlvx.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.xziqi.cn/Article/details/gt2xitbpdnl.html

[U03] Py：加载 .env 配置
来源：http://dali.yangfankeji.com/Article/details/gt2axowiegh.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.sweek.top/Article/details/gt2nzmujvxl.html

[U04] Py：变量调试打印
来源：http://dali.pengpengdd.cyou/Article/details/gt2ulohpaxc.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhiwuduotai.top/Article/details/gt2ilvtmjdl.html

[U05] Py：列表去重且保序
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gchyqyou.html

list(dict.fromkeys(arr))
来源：http://dali.pycfn.com/Article/details/gt2zwlmvmaa.html

[U06] Py：合并两个字典
来源：http://dali.yj20258.top/Article/details/gt2msyxfmrw.html

{**a, **b}
来源：http://dali.zhixingplan.top/Article/details/gt2jvfuqpld.html

[U07] Py：反转字典键值
来源：http://dali.dianchejie.cn/Article/details/gt2vefcnlrq.html

{v: k for k, v in d.items()}
来源：http://dali.zhixingplan.top/Article/details/gt2mjeanokp.html

[U08] Py：展平二维列表
来源：http://dali.chenlongwang.top/Article/details/gt2tcndfkmz.html

[y for x in nested for y in x]
来源：http://dali.yj202588.top/Article/details/gt2skyxxukd.html

[U09] Py：字典取最大值的键
来源：http://dali.yanxiufei.cn/Article/details/gt2dafluuiv.html

max(d, key=d.get)
来源：http://dali.aibaodan.cn/Article/details/gt2whmifdkq.html

[U10] Py：按值排序字典
来源：http://dali.yongpay.top/Article/details/gt2jvofjsft.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.shzxlz.cn/Article/details/gt2orlhpeso.html

[U11] Py：生成器表达式
来源：http://dali.jqgufenzy.top/Article/details/gt2slqptfun.html

(x * 2 for x in arr)
来源：http://dali.yanxiufei.cn/Article/details/gt2rfbjeviw.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.guannengcc.top/Article/details/gt2xftfqjpx.html

Counter(arr).most_common(3)
来源：http://dali.ybcxt.top/Article/details/gt2rilfbozm.html

[U13] Py：固定长度队列
来源：http://dali.hnxiangtu.top/Article/details/gt2fckscfou.html

deque(maxlen=10)
来源：http://dali.gogol.net.cn/Article/details/gt2pgnhedov.html

[U14] Py：分组收集到列表
来源：http://dali.cheryme.top/Article/details/gt2odgfrebi.html

defaultdict(list)
来源：http://dali.daxiang520.top/Article/details/gt2jzqyuwml.html


<!-- 参考信息 -->