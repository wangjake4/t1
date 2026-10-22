代发 wailian999

openssl rand -hex 16
来源：http://dali.zycfv.cn/Article/details/gt2xophhzbr.html

[R68] 计算文件校验值
来源：http://dali.9152youxi.cn/Article/details/gt2pcdeclcd.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.jlsjyb.cn/Article/details/gt2nuesekol.html

[R69] 生成随机密码
来源：http://dali.vqdsnc.cn/Article/details/gt2jpogrzhi.html

head -c 16 /dev/urandom | base64
来源：http://dali.chenjidiqi.icu/Article/details/gt2vnvzexwe.html

[R70] 时间戳与互转
来源：http://dali.hongshengwenyu.top/Article/details/gt2midyvmai.html

date +%s;  date -d @1700000000
来源：http://dali.mhx1999.top/Article/details/gt2nrepppin.html

[R71] 日期格式化
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qmbvykab.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.yonumen.top/Article/details/gt2aiwmkqwj.html

[R72] 等待端口就绪
来源：http://dali.sxryk.cn/Article/details/gt2mpbpxbzg.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.snrcjt.cn/Article/details/gt2yapsgknp.html

[R73] 分割大日志
来源：http://dali.shuidangran.top/Article/details/gt2cxzhtitt.html

split -l 1000 big.log part_
来源：http://dali.pengpengdd.cyou/Article/details/gt2feoaqhtu.html

[R74] 批量重命名
来源：http://dali.shanyushiyangtech.top/Article/details/gt2beusndpz.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.shangyingyoupin.top/Article/details/gt2ywraafcl.html

[R75] 导出环境变量
来源：http://dali.chenlongwang.top/Article/details/gt2tpzfhcer.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.aizwys.cn/Article/details/gt2vowhwots.html

[R76] 使用临时文件
来源：http://dali.316326.xyz/Article/details/gt2tropgfgd.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pwjzscpy.html

[R77] 读取用户输入
来源：http://dali.ehwqpu.com/Article/details/gt2kcxieslf.html

read -rp "请输入: " ans
来源：http://dali.cdnleiting.top/Article/details/gt2erinnsdo.html

[R78] 交互式菜单
来源：http://dali.xylfe.cn/Article/details/gt2qixoodmc.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.wangshuangyany.cn/Article/details/gt2mawtipqc.html

[R79] 解析命令行选项
来源：http://dali.vqdsnc.cn/Article/details/gt2ofwbwnpz.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.daxiang520.top/Article/details/gt2xhirgawt.html

[R80] 查看脚本执行耗时
来源：http://dali.redwolf501.top/Article/details/gt2zbizrjhh.html

time ./run.sh
来源：http://dali.pengpengdd.cyou/Article/details/gt2nankogtq.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kycdmirr.html

S. C / C++ 专题
来源：http://dali.wangshuangyany.cn/Article/details/gt2stjzkbek.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gt2ixbqrhjd.html

[S01] C：Hello World
来源：http://dali.yonumen.top/Article/details/gt2kmnoyxbq.html

#include <stdio.h>
来源：http://dali.wangdashe.top/Article/details/gt2oyvjspug.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.hywenlv.cn/Article/details/gt2hssyttos.html

[S02] C：变量与格式化输出
来源：http://dali.zycfv.cn/Article/details/gt2hsxbuixq.html

int a = 10; printf("%d\n", a);
来源：http://dali.sxryk.cn/Article/details/gt2fhdpsgvx.html

[S03] C：读入整数
来源：http://dali.gogol.net.cn/Article/details/gt2gmxnddgm.html

int x; scanf("%d", &x);
来源：http://dali.hywenlv.cn/Article/details/gt2royqsqqc.html

[S04] C：字符串复制
来源：http://dali.hywenlv.cn/Article/details/gt2ublfkova.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.yj20258888.top/Article/details/gt2sylrdhly.html

[S05] C：字符串长度
来源：http://dali.hongshengwenyu.top/Article/details/gt2nsmsgavx.html

strlen(s)
来源：http://dali.yj202588.top/Article/details/gt2bfnsbplh.html

[S06] C：字符串比较
来源：http://dali.zycfv.cn/Article/details/gt2qlbzeodo.html

strcmp(a, b) == 0
来源：http://dali.sxryk.cn/Article/details/gt2sijbczgj.html

[S07] C：数组遍历求和
来源：http://dali.ehwqpu.com/Article/details/gt2oqvjfhhq.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zycfv.cn/Article/details/gt2uaaikydl.html

[S08] C：动态内存分配与释放
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2naxrfnwg.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.fzhhl.top/Article/details/gt2fuwdkhjb.html

[S09] C：结构体定义与初始化
来源：http://dali.bjfxy.top/Article/details/gt2fhetjggw.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.c1oappe.top/Article/details/gt2vshdqafv.html

[S10] C：指针与解引用
来源：http://dali.ydzc1.top/Article/details/gt2digeglar.html

int *p = &a;  *p = 5;
来源：http://dali.shzxlz.cn/Article/details/gt2pcspunzc.html

[S11] C：逐行读文件
来源：http://dali.smart0.xyz/Article/details/gt2jvwhwheg.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.ppjwa.cn/Article/details/gt2bstfokhp.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.shuidangran.top/Article/details/gt2eljohgvy.html

fclose(f);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dqmziglo.html

[S12] C：写文件
来源：http://dali.yonumen.top/Article/details/gt2mfuscwkb.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.vqdsnc.cn/Article/details/gt2pdkupfet.html

[S13] C：宏定义
来源：http://dali.shangyingyoupin.top/Article/details/gt2qlsgqloh.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.316326.xyz/Article/details/gt2tvkllldl.html

[S14] C：枚举
来源：http://dali.yj20258.top/Article/details/gt2khmsnlap.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.sxryk.cn/Article/details/gt2ptsblguh.html

[S15] C：类型转换
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mwzymqli.html

(double) a / b
来源：http://dali.ydzc1.top/Article/details/gt2izrvotwu.html

[S16] C：位操作置位
来源：http://dali.andypj.xyz/Article/details/gt2isgadoel.html

x |= (1 << 3);
来源：http://dali.cdnleiting.top/Article/details/gt2jvhokelm.html

[S17] C：安全拼接字符串
来源：http://dali.kuanghao11.cn/Article/details/gt2fbluinoi.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.hfpthk.cn/Article/details/gt2igdqzohy.html

[S18] C：命令行参数
来源：http://dali.snrcjt.cn/Article/details/gt2ueldlmyv.html

int main(int argc, char **argv)
来源：http://dali.gzhubu.top/Article/details/gt2gwtlkzxa.html

[S19] C：快速排序
来源：http://dali.iojbl.cn/Article/details/gt2hnzahtfg.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.hnqzz.top/Article/details/gt2pmbwkhdu.html

[S20] C：二分查找
来源：http://dali.xylfe.cn/Article/details/gt2leqzocbq.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zycfv.cn/Article/details/gt2qitomvph.html

[S21] C：字符类别判断
来源：http://dali.quarkkingdee.top/Article/details/gt2ngtsjslb.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.ehwqpu.com/Article/details/gt2thqzgyvl.html

[S22] C：字符串转数字
来源：http://dali.yuxming.cn/Article/details/gt2pkknfdsl.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.hnqzz.top/Article/details/gt2zbqvdyzu.html

[S23] C：随机数
来源：http://dali.jianghu66.top/Article/details/gt2dkpdjeuq.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.aibaodan.cn/Article/details/gt2cakzizvm.html

[S24] C：获取本地时间
来源：http://dali.snrcjt.cn/Article/details/gt2lcikrusn.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhiwuduotai.top/Article/details/gt2gnwpyixt.html

[S25] C：内存拷贝
来源：http://dali.hysaishi.cn/Article/details/gt2zjqzajne.html

memcpy(dst, src, n);
来源：http://dali.jqgufenzy.top/Article/details/gt2jgwheteb.html

[S26] C：内存清零
来源：http://dali.hongshengwenyu.top/Article/details/gt2rrwcihal.html

memset(a, 0, sizeof a);
来源：http://dali.jqgufenzy.top/Article/details/gt2lcrhwnse.html

[S27] C：定义常量
来源：http://dali.svipenyu.cn/Article/details/gt2tqlychiu.html

const double PI = 3.14159;
来源：http://dali.yueranfly.top/Article/details/gt2xibtxvdn.html

[S28] C：静态变量
来源：http://dali.iojbl.cn/Article/details/gt2vssgkhrn.html

static int counter = 0;
来源：http://dali.wangdashe.top/Article/details/gt2tfwulhdt.html

[S29] C：变参函数
来源：http://dali.hywenlv.cn/Article/details/gt2ggxzbujp.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yeykwash.html

[S30] C：头文件保护
来源：http://dali.fzhhl.top/Article/details/gt2fofsvuuw.html

#ifndef X_H
来源：http://dali.birdmap.top/Article/details/gt2imxcitia.html

#define X_H
来源：http://dali.sufxvd.cn/Article/details/gt2uwuclkax.html

#endif
来源：http://dali.ppjwa.cn/Article/details/gt2srntylgm.html

[S31] C++：Hello World
来源：http://dali.xuetiantiany.cn/Article/details/gt2ryzftwtj.html

#include <iostream>
来源：http://dali.ydzc1.top/Article/details/gt2bdcdgakx.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2hppdopbv.html

[S32] C++：字符串
来源：http://dali.xziqi.cn/Article/details/gt2qqgnmiue.html

std::string s = "hi";  s += "!";
来源：http://dali.cashguo.top/Article/details/gt2niskttvq.html

[S33] C++：vector 增删
来源：http://dali.gzhubu.top/Article/details/gt2mqwgzwud.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.yvedp.cn/Article/details/gt2edqzayds.html

[S34] C++：遍历 vector
来源：http://dali.daria6918.cn/Article/details/gt2fqggbski.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhixingplan.top/Article/details/gt2yxnnoojy.html

[S35] C++：map
来源：http://dali.cqqwz.cn/Article/details/gt2ubpbzvzp.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.gaohongyu789.top/Article/details/gt2knnioini.html

[S36] C++：unordered_map
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zpkwfigv.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.chenjidiqi.icu/Article/details/gt2zwlkaieu.html

[S37] C++：set
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2asazhogi.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.cqqwz.cn/Article/details/gt2pwcluglr.html

[S38] C++：排序
来源：http://dali.ivvv.top/Article/details/gt2zxsgbhsq.html

std::sort(v.begin(), v.end());
来源：http://dali.dashuyun.cn/Article/details/gt2zhoixhdh.html

[S39] C++：自定义比较器排序
来源：http://dali.pengpengdd.cyou/Article/details/gt2pslnrwfo.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.hammf.cn/Article/details/gt2cvlcjygk.html

[S40] C++：查找元素
来源：http://dali.yangfankeji.com/Article/details/gt2rumlevun.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zycfv.cn/Article/details/gt2gyrtakqk.html

[S41] C++：类与构造函数
来源：http://dali.shuidangran.top/Article/details/gt2yxijfmzv.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.pengpengdd.cyou/Article/details/gt2qzyxnhiw.html

[S42] C++：继承与虚函数
来源：http://dali.guowangkeji.top/Article/details/gt2jmebdauy.html

class B : public Base { public: void f() override {} };
来源：http://dali.sufxvd.cn/Article/details/gt2fdlbmmgx.html

[S43] C++：智能指针
来源：http://dali.tanke756.top/Article/details/gt2srlxkktw.html

auto p = std::make_unique<int>(5);
来源：http://dali.andypj.xyz/Article/details/gt2fffqqsax.html

[S44] C++：引用传参
来源：http://dali.xinyue.icu/Article/details/gt2crwrdaqr.html

void inc(int &x) { ++x; }
来源：http://dali.zhoulong.xyz/Article/details/gt2dcmexolx.html

[S45] C++：lambda
来源：http://dali.iojbl.cn/Article/details/gt2fgeuygaa.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.yj202588.top/Article/details/gt2mwwhteol.html

[S46] C++：函数模板
来源：http://dali.smart0.xyz/Article/details/gt2jaljvqns.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.c1oappe.top/Article/details/gt2uahsaruh.html

[S47] C++：结构化绑定遍历
来源：http://dali.sufxvd.cn/Article/details/gt2yzmnfdhx.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.jqgufenzy.top/Article/details/gt2bvfdfhlt.html

[S48] C++：逐行读文件
来源：http://dali.yuanzhike.top/Article/details/gt2erdlojoo.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.cucudq.cn/Article/details/gt2jytjhbhu.html

while (std::getline(in, line)) { }
来源：http://dali.gotoacloud.top/Article/details/gt2ujoghlin.html

[S49] C++：写文件
来源：http://dali.bjfxy.top/Article/details/gt2pxdlohzr.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.redwolf501.top/Article/details/gt2lvrncghh.html

[S50] C++：格式化数字
来源：http://dali.pengpengdd.cyou/Article/details/gt2zxqatntg.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.xuanzx.com/Article/details/gt2jiotwbtf.html

[S51] C++：显式类型转换
来源：http://dali.jiagoushi.top/Article/details/gt2zlnyyrje.html

static_cast<double>(a) / b
来源：http://dali.zhengqikj.top/Article/details/gt2ghrpwdhf.html

[S52] C++：const 与 noexcept
来源：http://dali.sufxvd.cn/Article/details/gt2gcxyhbto.html

int size() const noexcept { return n_; }
来源：http://dali.yj202588.top/Article/details/gt2coavooxm.html

[S53] C++：移动语义
来源：http://dali.ydzc1.top/Article/details/gt2rloldqkz.html

std::vector<int> w = std::move(v);
来源：http://dali.tian-w.cn/Article/details/gt2poclrxuw.html

[S54] C++：异常处理
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2renyqvmd.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.jqgfzy.top/Article/details/gt2qfhtjvzo.html

[S55] C++：结构化绑定
来源：http://dali.chenjidiqi.icu/Article/details/gt2vmjiwwak.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.yonumen.top/Article/details/gt2acolnhug.html

[S56] C++：optional
来源：http://dali.hysaishi.cn/Article/details/gt2clrvgrkn.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.birdmap.top/Article/details/gt2gjqiqzsq.html

[S57] C++：编译期常量
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nqmatuew.html

constexpr int N = 10;
来源：http://dali.havefunace.top/Article/details/gt2tcogvfjj.html

[S58] C++：命名空间
来源：http://dali.gogol.net.cn/Article/details/gt2roxgaeef.html

namespace ns { int f() { return 1; } }
来源：http://dali.fengsongda.top/Article/details/gt2sfifmkgj.html

[S59] C++：静态断言
来源：http://dali.316326.xyz/Article/details/gt2xksswqpt.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.chenzaomai.com/Article/details/gt2cufmemff.html

[S60] C++：遍历并删除元素
来源：http://dali.aibaodan.cn/Article/details/gt2qrnykpen.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.ivvv.top/Article/details/gt2fcgbggly.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2oiqqpqaj.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.hysaishi.cn/Article/details/gt2cyvcwzou.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gt2fngccyni.html

[T01] Kotlin：Hello World
来源：http://dali.yonumen.top/Article/details/gt2zsrukvdn.html

println("Hello")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ygvsntth.html

[T02] Kotlin：变量
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ihidhhbg.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.dianchejie.cn/Article/details/gt2jtyjglsj.html

[T03] Kotlin：字符串模板
来源：http://dali.aibaodan.cn/Article/details/gt2bzztkuyb.html

"值: $b"
来源：http://dali.tianlin.xyz/Article/details/gt2upsgzmfy.html

[T04] Kotlin：空安全
来源：http://dali.fzhhl.top/Article/details/gt2ltxwkcoz.html

val n: String? = null;  n?.length
来源：http://dali.hfpthk.cn/Article/details/gt2fgtnqzkt.html

[T05] Kotlin：when 表达式
来源：http://dali.andypj.xyz/Article/details/gt2rnlqhowz.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.kuanghao11.cn/Article/details/gt2nrgvdnfh.html

[T06] Kotlin：集合映射
来源：http://dali.jqgfzy.top/Article/details/gt2dahjimrv.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.jinqigfzy.top/Article/details/gt2mjquhaaq.html

[T07] Kotlin：集合过滤
来源：http://dali.cashguo.top/Article/details/gt2xumrkvbe.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zdqjudy.top/Article/details/gt2auryaaqt.html

[T08] Kotlin：数据类
来源：http://dali.andypj.xyz/Article/details/gt2tdgkqxyn.html

data class User(val name: String, val age: Int)
来源：http://dali.cheryme.top/Article/details/gt2kwcdadvd.html

[T09] Kotlin：扩展函数
来源：http://dali.xziqi.cn/Article/details/gt2jimdynmo.html

fun String.exclaim() = this + "!"
来源：http://dali.zhengqikj.top/Article/details/gt2uymnmkcw.html

[T10] Kotlin：默认参数
来源：http://dali.daxiang520.top/Article/details/gt2lafztixe.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.yonumen.top/Article/details/gt2jkvdcxru.html

[T11] Kotlin：协程
来源：http://dali.ivvv.top/Article/details/gt2blosomjj.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.ppjwa.cn/Article/details/gt2yvvgwhgp.html

[T12] Kotlin：解构声明
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mitbxnyk.html

val (a, b) = Pair(1, 2)
来源：http://dali.yongpay.top/Article/details/gt2wmglsazx.html

[T13] Kotlin：只读 Map
来源：http://dali.chenlongwang.top/Article/details/gt2xthxmkzi.html

val m = mapOf("a" to 1)
来源：http://dali.yueranfly.top/Article/details/gt2bqwhhkmv.html

[T14] Kotlin：循环
来源：http://dali.ppjwa.cn/Article/details/gt2xsbrnmtq.html

for (i in 1..10) println(i)
来源：http://dali.jinqigufen.top/Article/details/gt2adfxitoi.html

[T15] Kotlin：接口
来源：http://dali.svipenyu.cn/Article/details/gt2ualyxefh.html

interface Shape { fun area(): Double }
来源：http://dali.guannengcc.top/Article/details/gt2jdouuzre.html

[T16] Swift：Hello World
来源：http://dali.ivvv.top/Article/details/gt2nvburnhj.html

print("Hello")
来源：http://dali.jqgfzy.top/Article/details/gt2yknywpex.html

[T17] Swift：变量与常量
来源：http://dali.birdmap.top/Article/details/gt2sruhhutb.html

var a = 1;  let b = 2
来源：http://dali.zhongyouzk.top/Article/details/gt2oqdooiva.html

[T18] Swift：字符串插值
来源：http://dali.jiagoushi.top/Article/details/gt2msjxdhko.html

"值: \(b)"
来源：http://dali.feifeiyinyue.top/Article/details/gt2zaglario.html

[T19] Swift：可选绑定
来源：http://dali.yueranfly.top/Article/details/gt2vqxtvhum.html

if let n = opt { print(n) }
来源：http://dali.jiagoushi.top/Article/details/gt2fxadathw.html

[T20] Swift：数组操作
来源：http://dali.hysaishi.cn/Article/details/gt2bifzcqvy.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.jiagoushi.top/Article/details/gt2poiuitxj.html

[T21] Swift：遍历
来源：http://dali.316326.xyz/Article/details/gt2gdnknjfc.html

for x in a { print(x) }
来源：http://dali.pycfn.com/Article/details/gt2pvnlknmm.html

[T22] Swift：字典
来源：http://dali.aizwys.cn/Article/details/gt2rbolbfei.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.chenlongwang.top/Article/details/gt2pfaklnkf.html

[T23] Swift：函数
来源：http://dali.hysaishi.cn/Article/details/gt2ewptzivg.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.9152youxi.cn/Article/details/gt2pbstlrmc.html

[T24] Swift：闭包
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zdivyycm.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.shzxlz.cn/Article/details/gt2beelecxi.html

[T25] Swift：结构体
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xjpvxhrs.html

struct P { var x: Int }
来源：http://dali.hysaishi.cn/Article/details/gt2ukgnheoy.html

[T26] Swift：类与重写
来源：http://dali.xuetiantiany.cn/Article/details/gt2bozackfk.html

class A: Base { override func f() {} }
来源：http://dali.xinyue.icu/Article/details/gt2hplrsbkn.html

[T27] Swift：错误处理
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ppbcbjrp.html

do { try f() } catch { print(error) }
来源：http://dali.haohaochexian.top/Article/details/gt2tinhonto.html

[T28] Swift：枚举
来源：http://dali.yvedp.cn/Article/details/gt2qkvuxopb.html

enum Color { case red, green }
来源：http://dali.redwolf501.top/Article/details/gt2ipbchqvk.html

[T29] Swift：guard 提前返回
来源：http://dali.yj20258888.top/Article/details/gt2owhzbacr.html

guard let x = opt else { return }
来源：http://dali.jinqigfzy.top/Article/details/gt2pwqsacfl.html

[T30] Swift：协议
来源：http://dali.jianghu66.top/Article/details/gt2pyzoirng.html

protocol Shape { func area() -> Double }
来源：http://dali.snrcjt.cn/Article/details/gt2kmgxchrb.html

[T31] Lua：Hello World
来源：http://dali.yongpay.top/Article/details/gt2uuoemhkn.html

print("Hello")
来源：http://dali.gaohongyu789.top/Article/details/gt2scpxbkuh.html

[T32] Lua：局部变量
来源：http://dali.xziqi.cn/Article/details/gt2tsgbiwch.html

local a = 1
来源：http://dali.mhx1999.top/Article/details/gt2wbzbywjo.html

[T33] Lua：表（数组）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vjwbwjhj.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.snrcjt.cn/Article/details/gt2vlvuzeck.html

[T34] Lua：遍历表
来源：http://dali.yangfankeji.com/Article/details/gt2ajpdlela.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.snrcjt.cn/Article/details/gt2edffwwva.html

[T35] Lua：字典表
来源：http://dali.shangyingyoupin.top/Article/details/gt2oruzqmwv.html

local d = { a = 1 };  d.b = 2
来源：http://dali.hywenlv.cn/Article/details/gt2unkancxj.html

[T36] Lua：函数
来源：http://dali.nanxinkj.top/Article/details/gt2aytfxxjv.html

function add(a, b) return a + b end
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wkeqfetr.html

[T37] Lua：字符串拼接
来源：http://dali.jqgfzy.top/Article/details/gt2iimivwrp.html

"a" .. "b"
来源：http://dali.xuanzx.com/Article/details/gt2qirwrpkm.html

[T38] Lua：条件
来源：http://dali.aizwys.cn/Article/details/gt2igmfrimh.html

if x > 0 then print("正") end
来源：http://dali.jlsjyb.cn/Article/details/gt2adrtqrag.html

[T39] Lua：模式匹配
来源：http://dali.hongshengwenyu.top/Article/details/gt2zsiryjdz.html

string.find(s, "%d+")
来源：http://dali.fzhhl.top/Article/details/gt2kndmslyl.html

[T40] Lua：元表
来源：http://dali.jianghu66.top/Article/details/gt2xolhopgo.html

setmetatable({}, { __index = base })
来源：http://dali.meibo888.top/Article/details/gt2hzzvvgln.html

[T41] Perl：Hello World
来源：http://dali.shuidangran.top/Article/details/gt2skixakve.html

print "Hello\n";
来源：http://dali.sweek.top/Article/details/gt2imyamfnw.html

[T42] Perl：变量类型
来源：http://dali.smart0.xyz/Article/details/gt2sgjxzkvw.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.pengpengdd.cyou/Article/details/gt2iajakzrv.html

[T43] Perl：字符串插值
来源：http://dali.xylfe.cn/Article/details/gt2mufylghe.html

"值: $a"
来源：http://dali.aibaodan.cn/Article/details/gt2bjzpoioc.html

[T44] Perl：条件
来源：http://dali.wangshuangyany.cn/Article/details/gt2lntwbfkk.html

if ($a > 0) { print "正"; }
来源：http://dali.cdnleiting.top/Article/details/gt2shnlpopl.html

[T45] Perl：数组遍历
来源：http://dali.hnxiangtu.top/Article/details/gt2luhqitkr.html

for my $x (@arr) { print $x; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2eyurboov.html

[T46] Perl：哈希操作
来源：http://dali.gotoacloud.top/Article/details/gt2kslvmqec.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.shuidangran.top/Article/details/gt2hvhnwiof.html

[T47] Perl：正则捕获
来源：http://dali.ppjwa.cn/Article/details/gt2knudjsec.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.birdmap.top/Article/details/gt2tlwxjgkd.html

[T48] Perl：正则替换
来源：http://dali.havefunace.top/Article/details/gt2rdarrvii.html

$s =~ s/old/new/g;
来源：http://dali.jinqigufen.top/Article/details/gt2yhvepqxr.html

[T49] Perl：函数
来源：http://dali.jqgufenzy.top/Article/details/gt2qhcrlbyf.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.havefunace.top/Article/details/gt2fvuqidku.html

[T50] Perl：逐行读文件
来源：http://dali.svipenyu.cn/Article/details/gt2zgxlivom.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.tanke756.top/Article/details/gt2wopgsowy.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2xpxyntgi.html

[T51] Scala：Hello World
来源：http://dali.zhoulong.xyz/Article/details/gt2qduveigf.html

println("Hello")
来源：http://dali.mhx1999.top/Article/details/gt2fjvqifbd.html

[T52] Scala：变量
来源：http://dali.c1oappe.top/Article/details/gt2bjwcaxtp.html

val a = 1;  var b = 2
来源：http://dali.c1oappe.top/Article/details/gt2asedbhmh.html

[T53] Scala：字符串插值
来源：http://dali.yuxming.cn/Article/details/gt2glwtipaq.html

s"值: $b"
来源：http://dali.hywenlv.cn/Article/details/gt2ilievsyb.html

[T54] Scala：集合映射
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zmovdrkl.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.cashguo.top/Article/details/gt2nhuwrcpr.html

[T55] Scala：集合过滤
来源：http://dali.aibaodan.cn/Article/details/gt2izuaqjzu.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.jqgfzy.top/Article/details/gt2vzueteof.html

[T56] Scala：样例类
来源：http://dali.zdqjudy.top/Article/details/gt2faglylya.html

case class User(name: String, age: Int)
来源：http://dali.guannengcc.top/Article/details/gt2owlbblcu.html

[T57] Scala：模式匹配
来源：http://dali.wangdashe.top/Article/details/gt2adlaynmo.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhongyouzk.top/Article/details/gt2ypboahsd.html

[T58] Scala：函数定义
来源：http://dali.ehwqpu.com/Article/details/gt2qearmzul.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.fengsongda.top/Article/details/gt2lwglqrfi.html

[T59] Scala：循环
来源：http://dali.sysykeji.top/Article/details/gt2eqrslgko.html

for (i <- 1 to 10) println(i)
来源：http://dali.ehwqpu.com/Article/details/gt2ndhlsnsr.html

[T60] Scala：折叠
来源：http://dali.yj20258.top/Article/details/gt2rgsxukmj.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.mhx1999.top/Article/details/gt2ihozyybi.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2ouyqezpy.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.chenlongwang.top/Article/details/gt2sydtersv.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2ztqxmohx.html

[U01] Py：创建虚拟环境
来源：http://dali.yangfankeji.com/Article/details/gt2duqyknjn.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.hysaishi.cn/Article/details/gt2jsiodrfv.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhengqikj.top/Article/details/gt2qjewutvh.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tidxpaxi.html

[U03] Py：加载 .env 配置
来源：http://dali.tian-w.cn/Article/details/gt2mzdjbryn.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhiwuduotai.top/Article/details/gt2ylssmixe.html

[U04] Py：变量调试打印
来源：http://dali.wangshuangyany.cn/Article/details/gt2cfqlgmko.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.nwbrower.top/Article/details/gt2kkrdihsg.html

[U05] Py：列表去重且保序
来源：http://dali.xziqi.cn/Article/details/gt2jbixzanz.html

list(dict.fromkeys(arr))
来源：http://dali.aibaodan.cn/Article/details/gt2zyuqsjoh.html

[U06] Py：合并两个字典
来源：http://dali.sweek.top/Article/details/gt2fnezofjo.html

{**a, **b}
来源：http://dali.xinyue.icu/Article/details/gt2sqcvmjar.html

[U07] Py：反转字典键值
来源：http://dali.yj20258.top/Article/details/gt2butwauit.html

{v: k for k, v in d.items()}
来源：http://dali.chenzaomai.com/Article/details/gt2npmbmexo.html

[U08] Py：展平二维列表
来源：http://dali.yonumen.top/Article/details/gt2qmbmhjls.html

[y for x in nested for y in x]
来源：http://dali.hongshengwenyu.top/Article/details/gt2ufsaiptc.html


<!-- 参考信息 -->