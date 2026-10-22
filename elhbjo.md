代发 wailian999

openssl rand -hex 16
来源：http://dali.daxiang520.top/Article/details/gt2dsjmsnbi.html

[R68] 计算文件校验值
来源：http://dali.quarkkingdee.top/Article/details/gt2gczyzndi.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.chenlongwang.top/Article/details/gt2cosqgxof.html

[R69] 生成随机密码
来源：http://dali.chenzaomai.com/Article/details/gt2pwrjlogm.html

head -c 16 /dev/urandom | base64
来源：http://dali.xinyue.icu/Article/details/gt2ldyatoey.html

[R70] 时间戳与互转
来源：http://dali.xinyue.icu/Article/details/gt2nvonzwfd.html

date +%s;  date -d @1700000000
来源：http://dali.yj202588.top/Article/details/gt2zoqvuuen.html

[R71] 日期格式化
来源：http://dali.jiagoushi.top/Article/details/gt2yvuaxhjv.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.yonumen.top/Article/details/gt2okoytqff.html

[R72] 等待端口就绪
来源：http://dali.xylfe.cn/Article/details/gt2ihnffris.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.hysaishi.cn/Article/details/gt2wmlnezym.html

[R73] 分割大日志
来源：http://dali.hongshengwenyu.top/Article/details/gt2mlbvzljw.html

split -l 1000 big.log part_
来源：http://dali.zhengqikj.top/Article/details/gt2rwuzxfke.html

[R74] 批量重命名
来源：http://dali.nwbrower.top/Article/details/gt2xjnmqssg.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.wangshuangyany.cn/Article/details/gt2hxxrqhid.html

[R75] 导出环境变量
来源：http://dali.yuxming.cn/Article/details/gt2hyybsdgm.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.sysykeji.top/Article/details/gt2jliczjhb.html

[R76] 使用临时文件
来源：http://dali.gaohongyu789.top/Article/details/gt2fhnhrivz.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.gzhubu.top/Article/details/gt2jofvmgfw.html

[R77] 读取用户输入
来源：http://dali.pycfn.com/Article/details/gt2ejenjcvo.html

read -rp "请输入: " ans
来源：http://dali.smart0.xyz/Article/details/gt2jkjwlnzg.html

[R78] 交互式菜单
来源：http://dali.sysykeji.top/Article/details/gt2krgfgqdu.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.andypj.xyz/Article/details/gt2gqfhzqul.html

[R79] 解析命令行选项
来源：http://dali.yj20258.top/Article/details/gt2lpjlsdjo.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.redwolf501.top/Article/details/gt2uhmfzxow.html

[R80] 查看脚本执行耗时
来源：http://dali.cashguo.top/Article/details/gt2lhxjzbrj.html

time ./run.sh
来源：http://dali.zhongyouzk.top/Article/details/gt2zpzprlmb.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2nrecnlxt.html

S. C / C++ 专题
来源：http://dali.9152youxi.cn/Article/details/gt2omllexlp.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2dqqjclpi.html

[S01] C：Hello World
来源：http://dali.hnxiangtu.top/Article/details/gt2aafdxorq.html

#include <stdio.h>
来源：http://dali.guannengcc.top/Article/details/gt2kcwgxhug.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.xinyue.icu/Article/details/gt2cfkumbri.html

[S02] C：变量与格式化输出
来源：http://dali.ivvv.top/Article/details/gt2rkobsage.html

int a = 10; printf("%d\n", a);
来源：http://dali.hywenlv.cn/Article/details/gt2wsxrwijz.html

[S03] C：读入整数
来源：http://dali.yj20258888.top/Article/details/gt2dorlkxve.html

int x; scanf("%d", &x);
来源：http://dali.hnxiangtu.top/Article/details/gt2zywkxnfy.html

[S04] C：字符串复制
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yhmvvats.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2osvlyeuw.html

[S05] C：字符串长度
来源：http://dali.birdmap.top/Article/details/gt2zftkvqfe.html

strlen(s)
来源：http://dali.shuidangran.top/Article/details/gt2fgoibcwd.html

[S06] C：字符串比较
来源：http://dali.jianghu66.top/Article/details/gt2xbrwcvff.html

strcmp(a, b) == 0
来源：http://dali.wangdashe.top/Article/details/gt2ufmirojx.html

[S07] C：数组遍历求和
来源：http://dali.hnxiangtu.top/Article/details/gt2znzryekj.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.gaohongyu789.top/Article/details/gt2ovwnjoes.html

[S08] C：动态内存分配与释放
来源：http://dali.guowangkeji.top/Article/details/gt2rrspcaxi.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.dianchejie.cn/Article/details/gt2tmrsflsj.html

[S09] C：结构体定义与初始化
来源：http://dali.yanxiufei.cn/Article/details/gt2khwklmlp.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.shuidangran.top/Article/details/gt2kgeylcyj.html

[S10] C：指针与解引用
来源：http://dali.quarkkingdee.top/Article/details/gt2vtdaktop.html

int *p = &a;  *p = 5;
来源：http://dali.tanke756.top/Article/details/gt2pxxxsoee.html

[S11] C：逐行读文件
来源：http://dali.daxiang520.top/Article/details/gt2aiyhmxbb.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hupgphwg.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pktuyvtw.html

fclose(f);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zbiyjjsl.html

[S12] C：写文件
来源：http://dali.zhengqikj.top/Article/details/gt2yfhxtgee.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.jinqigufen.top/Article/details/gt2hadpioig.html

[S13] C：宏定义
来源：http://dali.tian-w.cn/Article/details/gt2zvxdgcud.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.aibaodan.cn/Article/details/gt2gpshlqta.html

[S14] C：枚举
来源：http://dali.tanke756.top/Article/details/gt2dhtvqfsq.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.cqqwz.cn/Article/details/gt2jzbjzrax.html

[S15] C：类型转换
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2muyvsjkb.html

(double) a / b
来源：http://dali.sysykeji.top/Article/details/gt2cnsgjwku.html

[S16] C：位操作置位
来源：http://dali.cucudq.cn/Article/details/gt2ajywdzcg.html

x |= (1 << 3);
来源：http://dali.cashguo.top/Article/details/gt2bhptxzqs.html

[S17] C：安全拼接字符串
来源：http://dali.hammf.cn/Article/details/gt2dnfrrpwn.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.gotoacloud.top/Article/details/gt2tmwapfjv.html

[S18] C：命令行参数
来源：http://dali.birdmap.top/Article/details/gt2sirqxxxa.html

int main(int argc, char **argv)
来源：http://dali.cheryme.top/Article/details/gt2axdjdjrs.html

[S19] C：快速排序
来源：http://dali.gotoacloud.top/Article/details/gt2wfiqunqz.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xcqdznbd.html

[S20] C：二分查找
来源：http://dali.gotoacloud.top/Article/details/gt2pxlgyekk.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.xinyue.icu/Article/details/gt2izscmwwv.html

[S21] C：字符类别判断
来源：http://dali.hnxiangtu.top/Article/details/gt2aoohoywc.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.fengsongda.top/Article/details/gt2scbrjakp.html

[S22] C：字符串转数字
来源：http://dali.tian-w.cn/Article/details/gt2alwzezmi.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.xinyue.icu/Article/details/gt2ladtckpz.html

[S23] C：随机数
来源：http://dali.havefunace.top/Article/details/gt2zvdnslqb.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhengqikj.top/Article/details/gt2xgvpzwix.html

[S24] C：获取本地时间
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xbpqfbiz.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.shangyingyoupin.top/Article/details/gt2yqqdaamz.html

[S25] C：内存拷贝
来源：http://dali.snrcjt.cn/Article/details/gt2lbdcebsn.html

memcpy(dst, src, n);
来源：http://dali.aizwys.cn/Article/details/gt2hsjzyaly.html

[S26] C：内存清零
来源：http://dali.zhongyouzk.top/Article/details/gt2vdaijwld.html

memset(a, 0, sizeof a);
来源：http://dali.jqgufenzy.top/Article/details/gt2ejkfjjtq.html

[S27] C：定义常量
来源：http://dali.xuetiantiany.cn/Article/details/gt2kivkzwvj.html

const double PI = 3.14159;
来源：http://dali.jqgfzy.top/Article/details/gt2uhewiofm.html

[S28] C：静态变量
来源：http://dali.cheryme.top/Article/details/gt2gxmmmqnq.html

static int counter = 0;
来源：http://dali.yj20258888.top/Article/details/gt2amrzozsc.html

[S29] C：变参函数
来源：http://dali.iojbl.cn/Article/details/gt2jiaybnqp.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.birdmap.top/Article/details/gt2nrhvwzhz.html

[S30] C：头文件保护
来源：http://dali.guannengcc.top/Article/details/gt2pdezsvkj.html

#ifndef X_H
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yzuwzlva.html

#define X_H
来源：http://dali.hywenlv.cn/Article/details/gt2pdjxnvap.html

#endif
来源：http://dali.tianlin.xyz/Article/details/gt2zijgomgb.html

[S31] C++：Hello World
来源：http://dali.xuanzx.com/Article/details/gt2nsscjaca.html

#include <iostream>
来源：http://dali.sysykeji.top/Article/details/gt2ahzlqkjg.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.jqgfzy.top/Article/details/gt2zfkqywlh.html

[S32] C++：字符串
来源：http://dali.snrcjt.cn/Article/details/gt2achnnumc.html

std::string s = "hi";  s += "!";
来源：http://dali.yvedp.cn/Article/details/gt2jwtbukfk.html

[S33] C++：vector 增删
来源：http://dali.cucudq.cn/Article/details/gt2ztbxwtkl.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.hongshengwenyu.top/Article/details/gt2nihafjbm.html

[S34] C++：遍历 vector
来源：http://dali.havefunace.top/Article/details/gt2ixgdibyj.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.sweek.top/Article/details/gt2eapqigml.html

[S35] C++：map
来源：http://dali.guowangkeji.top/Article/details/gt2ktntfgvf.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.tian-w.cn/Article/details/gt2artqvqhy.html

[S36] C++：unordered_map
来源：http://dali.xuanzx.com/Article/details/gt2mbwwfevw.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.shuidangran.top/Article/details/gt2yfkxhkfy.html

[S37] C++：set
来源：http://dali.smart0.xyz/Article/details/gt2exhvtgsa.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.jqgfzy.top/Article/details/gt2txmbpepw.html

[S38] C++：排序
来源：http://dali.daria6918.cn/Article/details/gt2ypzmnljq.html

std::sort(v.begin(), v.end());
来源：http://dali.zycfv.cn/Article/details/gt2faajzltt.html

[S39] C++：自定义比较器排序
来源：http://dali.zhengqikj.top/Article/details/gt2juccyrdy.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.jqgfzy.top/Article/details/gt2scstpzri.html

[S40] C++：查找元素
来源：http://dali.jyoumei.cn/Article/details/gt2mfprsqxb.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.ivvv.top/Article/details/gt2evswcvld.html

[S41] C++：类与构造函数
来源：http://dali.nwbrower.top/Article/details/gt2surudrjz.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mnphxwms.html

[S42] C++：继承与虚函数
来源：http://dali.xuetiantiany.cn/Article/details/gt2kkyngyqt.html

class B : public Base { public: void f() override {} };
来源：http://dali.c1oappe.top/Article/details/gt2dfkdhqwn.html

[S43] C++：智能指针
来源：http://dali.redwolf501.top/Article/details/gt2ojhcielw.html

auto p = std::make_unique<int>(5);
来源：http://dali.yj20258.top/Article/details/gt2kkwawqug.html

[S44] C++：引用传参
来源：http://dali.haohaochexian.top/Article/details/gt2lnsegymg.html

void inc(int &x) { ++x; }
来源：http://dali.sxryk.cn/Article/details/gt2ggxiifjf.html

[S45] C++：lambda
来源：http://dali.316326.xyz/Article/details/gt2eiezwagq.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.haohaochexian.top/Article/details/gt2xalkddik.html

[S46] C++：函数模板
来源：http://dali.ppjwa.cn/Article/details/gt2zzpnease.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.cdnleiting.top/Article/details/gt2cwwupqvs.html

[S47] C++：结构化绑定遍历
来源：http://dali.yvedp.cn/Article/details/gt2kgevaple.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.sweek.top/Article/details/gt2mpvgdpic.html

[S48] C++：逐行读文件
来源：http://dali.jinqigufen.top/Article/details/gt2idgyjyob.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.mhx1999.top/Article/details/gt2xlzapotk.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2wiqhqaoz.html

[S49] C++：写文件
来源：http://dali.vqdsnc.cn/Article/details/gt2ygroxwnu.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.tanke756.top/Article/details/gt2rbxmlthy.html

[S50] C++：格式化数字
来源：http://dali.havefunace.top/Article/details/gt2kzqmplkx.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.sxryk.cn/Article/details/gt2myvjxcru.html

[S51] C++：显式类型转换
来源：http://dali.yonumen.top/Article/details/gt2podpjkzc.html

static_cast<double>(a) / b
来源：http://dali.hysaishi.cn/Article/details/gt2sggsfycz.html

[S52] C++：const 与 noexcept
来源：http://dali.hammf.cn/Article/details/gt2yelqrags.html

int size() const noexcept { return n_; }
来源：http://dali.chenzaomai.com/Article/details/gt2kjtzwxhi.html

[S53] C++：移动语义
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fxllhyby.html

std::vector<int> w = std::move(v);
来源：http://dali.fengsongda.top/Article/details/gt2gftjyzbm.html

[S54] C++：异常处理
来源：http://dali.jiagoushi.top/Article/details/gt2jxplxhyq.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.svipenyu.cn/Article/details/gt2hyhwervc.html

[S55] C++：结构化绑定
来源：http://dali.yanxiufei.cn/Article/details/gt2yddsjdex.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.hywenlv.cn/Article/details/gt2iuqtbqdw.html

[S56] C++：optional
来源：http://dali.hnqzz.top/Article/details/gt2ezlbnoes.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhongyouzk.top/Article/details/gt2twviztfu.html

[S57] C++：编译期常量
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2moozmdyt.html

constexpr int N = 10;
来源：http://dali.fzhhl.top/Article/details/gt2yascbazg.html

[S58] C++：命名空间
来源：http://dali.ybcxt.top/Article/details/gt2ogmsbrsr.html

namespace ns { int f() { return 1; } }
来源：http://dali.andypj.xyz/Article/details/gt2ocfsxnla.html

[S59] C++：静态断言
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ywxjhefr.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.chenzaomai.com/Article/details/gt2xjovrtmg.html

[S60] C++：遍历并删除元素
来源：http://dali.cdnleiting.top/Article/details/gt2bajchvak.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.aizwys.cn/Article/details/gt2slzyqlmo.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2giwlcwtx.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.sxryk.cn/Article/details/gt2pzljhskx.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bdmtggek.html

[T01] Kotlin：Hello World
来源：http://dali.mhx1999.top/Article/details/gt2hhsmdshz.html

println("Hello")
来源：http://dali.mhx1999.top/Article/details/gt2ufjmoeqi.html

[T02] Kotlin：变量
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wapkwmsk.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.jqgfzy.top/Article/details/gt2grzaenwm.html

[T03] Kotlin：字符串模板
来源：http://dali.haohaochexian.top/Article/details/gt2tcidrvit.html

"值: $b"
来源：http://dali.meibo888.top/Article/details/gt2qjtswznz.html

[T04] Kotlin：空安全
来源：http://dali.sweek.top/Article/details/gt2ekluxruz.html

val n: String? = null;  n?.length
来源：http://dali.chenlongwang.top/Article/details/gt2jvbfiqts.html

[T05] Kotlin：when 表达式
来源：http://dali.iojbl.cn/Article/details/gt2dgmfgjep.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.nanxuanxn.top/Article/details/gt2gctuzson.html

[T06] Kotlin：集合映射
来源：http://dali.sweek.top/Article/details/gt2aqcfdwqh.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.ydzc1.top/Article/details/gt2icfkqjvz.html

[T07] Kotlin：集合过滤
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jzwfrlha.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.cdnleiting.top/Article/details/gt2xngcbmfc.html

[T08] Kotlin：数据类
来源：http://dali.sysykeji.top/Article/details/gt2jwvwxsjq.html

data class User(val name: String, val age: Int)
来源：http://dali.xuanzx.com/Article/details/gt2hfxzyrsw.html

[T09] Kotlin：扩展函数
来源：http://dali.tianlin.xyz/Article/details/gt2geuhnvak.html

fun String.exclaim() = this + "!"
来源：http://dali.ehwqpu.com/Article/details/gt2mpogkhca.html

[T10] Kotlin：默认参数
来源：http://dali.svipenyu.cn/Article/details/gt2bkpjnmun.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.sxryk.cn/Article/details/gt2jvfqefqk.html

[T11] Kotlin：协程
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2aasnlsin.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.yuanzhike.top/Article/details/gt2bypbbajq.html

[T12] Kotlin：解构声明
来源：http://dali.xylfe.cn/Article/details/gt2vjqnxtgi.html

val (a, b) = Pair(1, 2)
来源：http://dali.zdqjudy.top/Article/details/gt2bhftfczx.html

[T13] Kotlin：只读 Map
来源：http://dali.yanxiufei.cn/Article/details/gt2blyjsvzi.html

val m = mapOf("a" to 1)
来源：http://dali.quarkkingdee.top/Article/details/gt2eqvsyyif.html

[T14] Kotlin：循环
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2swifgsvu.html

for (i in 1..10) println(i)
来源：http://dali.snrcjt.cn/Article/details/gt2ecsjhmfd.html

[T15] Kotlin：接口
来源：http://dali.cashguo.top/Article/details/gt2qzknlatj.html

interface Shape { fun area(): Double }
来源：http://dali.tian-w.cn/Article/details/gt2kjvgyteu.html

[T16] Swift：Hello World
来源：http://dali.sxryk.cn/Article/details/gt2pgwovqwe.html

print("Hello")
来源：http://dali.nanxinkj.top/Article/details/gt2krjrmiou.html

[T17] Swift：变量与常量
来源：http://dali.yuanzhike.top/Article/details/gt2hcyqliaj.html

var a = 1;  let b = 2
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lbuvkore.html

[T18] Swift：字符串插值
来源：http://dali.mhx1999.top/Article/details/gt2qrbuscwc.html

"值: \(b)"
来源：http://dali.vqdsnc.cn/Article/details/gt2qdirytdb.html

[T19] Swift：可选绑定
来源：http://dali.316326.xyz/Article/details/gt2cynoryaf.html

if let n = opt { print(n) }
来源：http://dali.gzhubu.top/Article/details/gt2nlnlqhcn.html

[T20] Swift：数组操作
来源：http://dali.mhx1999.top/Article/details/gt2ofqilzbv.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.jlsjyb.cn/Article/details/gt2odxurxxm.html

[T21] Swift：遍历
来源：http://dali.havefunace.top/Article/details/gt2qcrykalr.html

for x in a { print(x) }
来源：http://dali.gotoacloud.top/Article/details/gt2eqidcjtm.html

[T22] Swift：字典
来源：http://dali.daria6918.cn/Article/details/gt2kzvqarra.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.hfpthk.cn/Article/details/gt2wqtzjqqt.html

[T23] Swift：函数
来源：http://dali.shuidangran.top/Article/details/gt2xwrskcwj.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.tanke756.top/Article/details/gt2yxaacltq.html

[T24] Swift：闭包
来源：http://dali.xziqi.cn/Article/details/gt2lbccdrwl.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.mhx1999.top/Article/details/gt2rvxyussj.html

[T25] Swift：结构体
来源：http://dali.chenzaomai.com/Article/details/gt2prgrmogs.html

struct P { var x: Int }
来源：http://dali.ybcxt.top/Article/details/gt2kbmccfyi.html

[T26] Swift：类与重写
来源：http://dali.sysykeji.top/Article/details/gt2srxyiczh.html

class A: Base { override func f() {} }
来源：http://dali.pengpengdd.cyou/Article/details/gt2dqvfcikw.html

[T27] Swift：错误处理
来源：http://dali.fengsongda.top/Article/details/gt2docjqlui.html

do { try f() } catch { print(error) }
来源：http://dali.snrcjt.cn/Article/details/gt2dygxhzbd.html

[T28] Swift：枚举
来源：http://dali.yj202588.top/Article/details/gt2kszpcsim.html

enum Color { case red, green }
来源：http://dali.hfpthk.cn/Article/details/gt2ffulhwuy.html

[T29] Swift：guard 提前返回
来源：http://dali.haohaochexian.top/Article/details/gt2zooxlejb.html

guard let x = opt else { return }
来源：http://dali.gogol.net.cn/Article/details/gt2kniuhotm.html

[T30] Swift：协议
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xcrmnedz.html

protocol Shape { func area() -> Double }
来源：http://dali.yvedp.cn/Article/details/gt2mkacyduh.html

[T31] Lua：Hello World
来源：http://dali.cqqwz.cn/Article/details/gt2wlhenfmk.html

print("Hello")
来源：http://dali.zhixingplan.top/Article/details/gt2pprhguxn.html

[T32] Lua：局部变量
来源：http://dali.hongshengwenyu.top/Article/details/gt2oplukhyw.html

local a = 1
来源：http://dali.ppjwa.cn/Article/details/gt2rcxavbfr.html

[T33] Lua：表（数组）
来源：http://dali.guannengcc.top/Article/details/gt2kdnpjsik.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.daria6918.cn/Article/details/gt2lmfhshvd.html

[T34] Lua：遍历表
来源：http://dali.zhongyouzk.top/Article/details/gt2ycnohpqw.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.guannengcc.top/Article/details/gt2mijgwzpw.html

[T35] Lua：字典表
来源：http://dali.feifeiyinyue.top/Article/details/gt2mbfdzkys.html

local d = { a = 1 };  d.b = 2
来源：http://dali.svipenyu.cn/Article/details/gt2wvmnxcbm.html

[T36] Lua：函数
来源：http://dali.tianlin.xyz/Article/details/gt2hvwhsufy.html

function add(a, b) return a + b end
来源：http://dali.yangfankeji.com/Article/details/gt2nvlydbna.html

[T37] Lua：字符串拼接
来源：http://dali.pycfn.com/Article/details/gt2awukqzxr.html

"a" .. "b"
来源：http://dali.daxiang520.top/Article/details/gt2xyzjgihs.html

[T38] Lua：条件
来源：http://dali.tanke756.top/Article/details/gt2ltaskkkb.html

if x > 0 then print("正") end
来源：http://dali.tianlin.xyz/Article/details/gt2yuuwnqnj.html

[T39] Lua：模式匹配
来源：http://dali.fzhhl.top/Article/details/gt2lnwzkeen.html

string.find(s, "%d+")
来源：http://dali.yangfankeji.com/Article/details/gt2gfokjtaw.html

[T40] Lua：元表
来源：http://dali.redwolf501.top/Article/details/gt2twnutcrk.html

setmetatable({}, { __index = base })
来源：http://dali.ydzc1.top/Article/details/gt2xyjwnikd.html

[T41] Perl：Hello World
来源：http://dali.sxryk.cn/Article/details/gt2uhcbdhih.html

print "Hello\n";
来源：http://dali.nanxinkj.top/Article/details/gt2clsewnec.html

[T42] Perl：变量类型
来源：http://dali.ehwqpu.com/Article/details/gt2vqydaplj.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.nwbrower.top/Article/details/gt2hffuvdue.html

[T43] Perl：字符串插值
来源：http://dali.zhiwuduotai.top/Article/details/gt2itmuflkt.html

"值: $a"
来源：http://dali.tanke756.top/Article/details/gt2diakceyf.html

[T44] Perl：条件
来源：http://dali.zhixingplan.top/Article/details/gt2axozcive.html

if ($a > 0) { print "正"; }
来源：http://dali.svipenyu.cn/Article/details/gt2kdgwjtiw.html

[T45] Perl：数组遍历
来源：http://dali.andypj.xyz/Article/details/gt2putirnge.html

for my $x (@arr) { print $x; }
来源：http://dali.tanke756.top/Article/details/gt2hcdqnnzw.html

[T46] Perl：哈希操作
来源：http://dali.zhixingplan.top/Article/details/gt2ohseejjy.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.hysaishi.cn/Article/details/gt2eayonboy.html

[T47] Perl：正则捕获
来源：http://dali.gogol.net.cn/Article/details/gt2xrenyuwh.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fttnoqco.html

[T48] Perl：正则替换
来源：http://dali.316326.xyz/Article/details/gt2zoltxmqj.html

$s =~ s/old/new/g;
来源：http://dali.tian-w.cn/Article/details/gt2yikroqka.html

[T49] Perl：函数
来源：http://dali.birdmap.top/Article/details/gt2lfahnjfu.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.yangfankeji.com/Article/details/gt2hsjixdvm.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2exioqqxo.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.vqdsnc.cn/Article/details/gt2qnmwevfn.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.iojbl.cn/Article/details/gt2kxgniqqi.html

[T51] Scala：Hello World
来源：http://dali.hnxiangtu.top/Article/details/gt2jywoumpk.html

println("Hello")
来源：http://dali.9152youxi.cn/Article/details/gt2msrubixb.html

[T52] Scala：变量
来源：http://dali.jlsjyb.cn/Article/details/gt2loxvejhs.html

val a = 1;  var b = 2
来源：http://dali.meibo888.top/Article/details/gt2gkflmqyz.html

[T53] Scala：字符串插值
来源：http://dali.wangdashe.top/Article/details/gt2smrrozlw.html

s"值: $b"
来源：http://dali.yj20258.top/Article/details/gt2mswqvnom.html

[T54] Scala：集合映射
来源：http://dali.zhengqikj.top/Article/details/gt2qmsxwuxk.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.pycfn.com/Article/details/gt2xcyhovdl.html

[T55] Scala：集合过滤
来源：http://dali.yuxming.cn/Article/details/gt2nbjnfqvc.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.sweek.top/Article/details/gt2nzffxdns.html

[T56] Scala：样例类
来源：http://dali.xylfe.cn/Article/details/gt2bhppkkdp.html

case class User(name: String, age: Int)
来源：http://dali.gzhubu.top/Article/details/gt2wbomlhsc.html

[T57] Scala：模式匹配
来源：http://dali.sysykeji.top/Article/details/gt2fqascvuk.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.havefunace.top/Article/details/gt2ktkzosfz.html

[T58] Scala：函数定义
来源：http://dali.yvedp.cn/Article/details/gt2klzsmint.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.vqdsnc.cn/Article/details/gt2xugirqyt.html

[T59] Scala：循环
来源：http://dali.zycfv.cn/Article/details/gt2yqnhyudw.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2oahdaqdp.html

[T60] Scala：折叠
来源：http://dali.daria6918.cn/Article/details/gt2pgdqwomt.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.sweek.top/Article/details/gt2rgveflgj.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2rtorfhpw.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.yangfankeji.com/Article/details/gt2kdjmkzro.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2ooigncyn.html

[U01] Py：创建虚拟环境
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ptzowyvq.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.yueranfly.top/Article/details/gt2gfvhlsis.html

[U02] Py：导出 / 安装依赖
来源：http://dali.haohaochexian.top/Article/details/gt2izukxhkk.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.pengpengdd.cyou/Article/details/gt2bzjdkfwd.html

[U03] Py：加载 .env 配置
来源：http://dali.jiagoushi.top/Article/details/gt2yjrpfkkn.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.xziqi.cn/Article/details/gt2ujffougq.html

[U04] Py：变量调试打印
来源：http://dali.yangfankeji.com/Article/details/gt2kiaigjbe.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zycfv.cn/Article/details/gt2wnduabzj.html

[U05] Py：列表去重且保序
来源：http://dali.havefunace.top/Article/details/gt2lphoqkpw.html

list(dict.fromkeys(arr))
来源：http://dali.zhiwuduotai.top/Article/details/gt2zjrtkwoa.html

[U06] Py：合并两个字典
来源：http://dali.jyoumei.cn/Article/details/gt2pngmhtmq.html

{**a, **b}
来源：http://dali.havefunace.top/Article/details/gt2wehrqndd.html

[U07] Py：反转字典键值
来源：http://dali.gzhubu.top/Article/details/gt2zpxatagz.html

{v: k for k, v in d.items()}
来源：http://dali.hfpthk.cn/Article/details/gt2pczvpodg.html

[U08] Py：展平二维列表
来源：http://dali.zhoulong.xyz/Article/details/gt2ggubupal.html

[y for x in nested for y in x]
来源：http://dali.hnxiangtu.top/Article/details/gt2rxoderpg.html


<!-- 参考信息 -->