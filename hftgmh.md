代发 wailian999

openssl rand -hex 16
来源：http://dali.yangfankeji.com/Article/details/gthtjeudvm.html

[R68] 计算文件校验值
来源：http://dali.aizwys.cn/Article/details/gtxgspjlae.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.ydzc1.top/Article/details/gtlwvybdxu.html

[R69] 生成随机密码
来源：http://dali.sweek.top/Article/details/gtgyycyojl.html

head -c 16 /dev/urandom | base64
来源：http://dali.nwbrower.top/Article/details/gtymtajxmx.html

[R70] 时间戳与互转
来源：http://dali.chenzaomai.com/Article/details/gtkaqjfqya.html

date +%s;  date -d @1700000000
来源：http://dali.shangyingyoupin.top/Article/details/gtggigypoe.html

[R71] 日期格式化
来源：http://dali.316326.xyz/Article/details/gtpeylkxyo.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.yj20258.top/Article/details/gtdatecvba.html

[R72] 等待端口就绪
来源：http://dali.ehwqpu.com/Article/details/gtmcixfxhb.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.aibaodan.cn/Article/details/gtlzhpffeu.html

[R73] 分割大日志
来源：http://dali.ybcxt.top/Article/details/gtxaibueye.html

split -l 1000 big.log part_
来源：http://dali.sysykeji.top/Article/details/gttmvgbjbn.html

[R74] 批量重命名
来源：http://dali.ehwqpu.com/Article/details/gtnbchimym.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.quarkkingdee.top/Article/details/gtyycrgozc.html

[R75] 导出环境变量
来源：http://dali.yj20258888.top/Article/details/gteslcpoei.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.ehwqpu.com/Article/details/gtperrrsdh.html

[R76] 使用临时文件
来源：http://dali.xylfe.cn/Article/details/gtxhvbmbja.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.yongpay.top/Article/details/gtplvwpkzj.html

[R77] 读取用户输入
来源：http://dali.hfpthk.cn/Article/details/gtigormlsf.html

read -rp "请输入: " ans
来源：http://dali.hnxiangtu.top/Article/details/gtugwecdws.html

[R78] 交互式菜单
来源：http://dali.cucudq.cn/Article/details/gtmatgiybc.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.hongshengwenyu.top/Article/details/gtaxrxwqdv.html

[R79] 解析命令行选项
来源：http://dali.yj20258.top/Article/details/gtsuvijxvf.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.fzhhl.top/Article/details/gtovotfnmd.html

[R80] 查看脚本执行耗时
来源：http://dali.ivvv.top/Article/details/gtiugcxhzj.html

time ./run.sh
来源：http://dali.tanke756.top/Article/details/gtowxakqmv.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtefwddtlv.html

S. C / C++ 专题
来源：http://dali.gaohongyu789.top/Article/details/gtmrwfkpmb.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtgxcgikfl.html

[S01] C：Hello World
来源：http://dali.quarkkingdee.top/Article/details/gtmxsmtafw.html

#include <stdio.h>
来源：http://dali.dianchejie.cn/Article/details/gtlheurkxx.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.jiagoushi.top/Article/details/gtjpfyazzs.html

[S02] C：变量与格式化输出
来源：http://dali.zhixingplan.top/Article/details/gtjwvodube.html

int a = 10; printf("%d\n", a);
来源：http://dali.shangyingyoupin.top/Article/details/gtnmvmtrnu.html

[S03] C：读入整数
来源：http://dali.shanyushiyangtech.top/Article/details/gtbeodvchp.html

int x; scanf("%d", &x);
来源：http://dali.hfpthk.cn/Article/details/gtisorkwwa.html

[S04] C：字符串复制
来源：http://dali.yj202588.top/Article/details/gtwnjoyaox.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.ivvv.top/Article/details/gtyyluqdwt.html

[S05] C：字符串长度
来源：http://dali.yongpay.top/Article/details/gtgxujwjvq.html

strlen(s)
来源：http://dali.yuanzhike.top/Article/details/gthohshdyy.html

[S06] C：字符串比较
来源：http://dali.dianchejie.cn/Article/details/gtfjdjvqwz.html

strcmp(a, b) == 0
来源：http://dali.svipenyu.cn/Article/details/gtfhwuyuwp.html

[S07] C：数组遍历求和
来源：http://dali.nanxuanxn.top/Article/details/gtrmfvplcw.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhengqikj.top/Article/details/gtftahtjbq.html

[S08] C：动态内存分配与释放
来源：http://dali.cashguo.top/Article/details/gtvqfhfoeq.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.gzhubu.top/Article/details/gtlcihszdd.html

[S09] C：结构体定义与初始化
来源：http://dali.zhixingplan.top/Article/details/gtfdbymgzk.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zdqjudy.top/Article/details/gtzexiqtqt.html

[S10] C：指针与解引用
来源：http://dali.xziqi.cn/Article/details/gtidzmqggo.html

int *p = &a;  *p = 5;
来源：http://dali.zycfv.cn/Article/details/gtbaftykth.html

[S11] C：逐行读文件
来源：http://dali.sysykeji.top/Article/details/gtvvallgmw.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.nanxuanxn.top/Article/details/gtqyoxdkii.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvhpojyjk.html

fclose(f);
来源：http://dali.chenlongwang.top/Article/details/gtjspmelij.html

[S12] C：写文件
来源：http://dali.hywenlv.cn/Article/details/gtiuueilhy.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.svipenyu.cn/Article/details/gtdqqchxol.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gtuxqgyjuw.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.bjfxy.top/Article/details/gtfokvqxym.html

[S14] C：枚举
来源：http://dali.jinqigufen.top/Article/details/gtrscswmbh.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuvbxmcxd.html

[S15] C：类型转换
来源：http://dali.daria6918.cn/Article/details/gtstmktmli.html

(double) a / b
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpdpmqnyh.html

[S16] C：位操作置位
来源：http://dali.shuidangran.top/Article/details/gtsuverpue.html

x |= (1 << 3);
来源：http://dali.xylfe.cn/Article/details/gtlhegzdub.html

[S17] C：安全拼接字符串
来源：http://dali.zycfv.cn/Article/details/gtudyjdarh.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.pengpengdd.cyou/Article/details/gtapggsutq.html

[S18] C：命令行参数
来源：http://dali.yj20258.top/Article/details/gtxzifreav.html

int main(int argc, char **argv)
来源：http://dali.redwolf501.top/Article/details/gtahqdsdsw.html

[S19] C：快速排序
来源：http://dali.cheryme.top/Article/details/gtsurzvjlt.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.haohaochexian.top/Article/details/gttzuwuhij.html

[S20] C：二分查找
来源：http://dali.chenzaomai.com/Article/details/gtetbcqucu.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.redwolf501.top/Article/details/gtcemmlcgh.html

[S21] C：字符类别判断
来源：http://dali.zhiwuduotai.top/Article/details/gtoexwwkvr.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.pycfn.com/Article/details/gtvrdcffqr.html

[S22] C：字符串转数字
来源：http://dali.hongshengwenyu.top/Article/details/gtrvvizhsw.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhengqikj.top/Article/details/gtyyrhawde.html

[S23] C：随机数
来源：http://dali.shanyushiyangtech.top/Article/details/gtrdkwsryh.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.aibaodan.cn/Article/details/gtfmqgagyz.html

[S24] C：获取本地时间
来源：http://dali.jyoumei.cn/Article/details/gtiwafekaz.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.redwolf501.top/Article/details/gtjltszqcz.html

[S25] C：内存拷贝
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoktfgwdx.html

memcpy(dst, src, n);
来源：http://dali.yanxiufei.cn/Article/details/gtznknjuxk.html

[S26] C：内存清零
来源：http://dali.shanyushiyangtech.top/Article/details/gtylldolov.html

memset(a, 0, sizeof a);
来源：http://dali.gzhubu.top/Article/details/gttyqnlbee.html

[S27] C：定义常量
来源：http://dali.shuidangran.top/Article/details/gtixooaeoy.html

const double PI = 3.14159;
来源：http://dali.wangshuangyany.cn/Article/details/gtfkalxwia.html

[S28] C：静态变量
来源：http://dali.zhongyouzk.top/Article/details/gtqegmozas.html

static int counter = 0;
来源：http://dali.ppjwa.cn/Article/details/gtmxziguqx.html

[S29] C：变参函数
来源：http://dali.ivvv.top/Article/details/gtnctpqakx.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.shanyushiyangkeji.top/Article/details/gterfezwiq.html

[S30] C：头文件保护
来源：http://dali.cdnleiting.top/Article/details/gtcgyieofy.html

#ifndef X_H
来源：http://dali.haohaochexian.top/Article/details/gtfvpygoqx.html

#define X_H
来源：http://dali.zhengqikj.top/Article/details/gtrwdjsdxh.html

#endif
来源：http://dali.sysykeji.top/Article/details/gtidtevwpx.html

[S31] C++：Hello World
来源：http://dali.xuanzx.com/Article/details/gtkcfyipek.html

#include <iostream>
来源：http://dali.wangshuangyany.cn/Article/details/gtxnfopedc.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.jiagoushi.top/Article/details/gtbfazqmpj.html

[S32] C++：字符串
来源：http://dali.jinghuilouyu.cn/Article/details/gtvmjueqkw.html

std::string s = "hi";  s += "!";
来源：http://dali.yonumen.top/Article/details/gtqctbtgcf.html

[S33] C++：vector 增删
来源：http://dali.cucudq.cn/Article/details/gtotovrxho.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.tanke756.top/Article/details/gtyjpxbjah.html

[S34] C++：遍历 vector
来源：http://dali.gzhubu.top/Article/details/gtrrnaogue.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhixingplan.top/Article/details/gtjjylkhby.html

[S35] C++：map
来源：http://dali.quarkkingdee.top/Article/details/gtlmpyyuor.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yangfankeji.com/Article/details/gtgthsynsf.html

[S36] C++：unordered_map
来源：http://dali.tanke756.top/Article/details/gtcaxlbrik.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.gotoacloud.top/Article/details/gtcjqbfwpc.html

[S37] C++：set
来源：http://dali.guannengcc.top/Article/details/gtkncfauss.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrusblrvt.html

[S38] C++：排序
来源：http://dali.tanke756.top/Article/details/gtbfasbrph.html

std::sort(v.begin(), v.end());
来源：http://dali.zhixingplan.top/Article/details/gtitaxklvh.html

[S39] C++：自定义比较器排序
来源：http://dali.feifeiyinyue.top/Article/details/gtjxqdbgpm.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.ivvv.top/Article/details/gtxhqdvacq.html

[S40] C++：查找元素
来源：http://dali.zhixingplan.top/Article/details/gtgqoeowbi.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.feifeiyinyue.top/Article/details/gttixsomzy.html

[S41] C++：类与构造函数
来源：http://dali.yuxming.cn/Article/details/gtivxemxxy.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.jinqigufen.top/Article/details/gtrnnuorsu.html

[S42] C++：继承与虚函数
来源：http://dali.yanxiufei.cn/Article/details/gtqlosjxep.html

class B : public Base { public: void f() override {} };
来源：http://dali.jiagoushi.top/Article/details/gtymsppims.html

[S43] C++：智能指针
来源：http://dali.jianghu66.top/Article/details/gtndwqduzs.html

auto p = std::make_unique<int>(5);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtedahvnpc.html

[S44] C++：引用传参
来源：http://dali.chenzaomai.com/Article/details/gtpnygfxkr.html

void inc(int &x) { ++x; }
来源：http://dali.zhiwuduotai.top/Article/details/gtbdsmpuif.html

[S45] C++：lambda
来源：http://dali.shanyushiyangtech.top/Article/details/gtleyroatv.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.hnxiangtu.top/Article/details/gteycbzuiz.html

[S46] C++：函数模板
来源：http://dali.ppjwa.cn/Article/details/gtuorrczkp.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.yanxiufei.cn/Article/details/gtaamrhimr.html

[S47] C++：结构化绑定遍历
来源：http://dali.meibo888.top/Article/details/gtrivosfgt.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhoulong.xyz/Article/details/gtnvdegota.html

[S48] C++：逐行读文件
来源：http://dali.gogol.net.cn/Article/details/gteoiapyoy.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.redwolf501.top/Article/details/gtpojcsiwe.html

while (std::getline(in, line)) { }
来源：http://dali.xuanzx.com/Article/details/gtzymptyaz.html

[S49] C++：写文件
来源：http://dali.fzhhl.top/Article/details/gtcmavrkmy.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.aibaodan.cn/Article/details/gtuyhlmfir.html

[S50] C++：格式化数字
来源：http://dali.sysykeji.top/Article/details/gtqyvqdxpz.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.fengsongda.top/Article/details/gtrrqxdaje.html

[S51] C++：显式类型转换
来源：http://dali.hfpthk.cn/Article/details/gtypuewngj.html

static_cast<double>(a) / b
来源：http://dali.yongpay.top/Article/details/gtzflowxyn.html

[S52] C++：const 与 noexcept
来源：http://dali.zhengqikj.top/Article/details/gtsokxzben.html

int size() const noexcept { return n_; }
来源：http://dali.kuanghao11.cn/Article/details/gtwurbrhii.html

[S53] C++：移动语义
来源：http://dali.gogol.net.cn/Article/details/gtcvmyrabb.html

std::vector<int> w = std::move(v);
来源：http://dali.wangdashe.top/Article/details/gtbgklfqyr.html

[S54] C++：异常处理
来源：http://dali.sxryk.cn/Article/details/gtdurohust.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.birdmap.top/Article/details/gtkuwsxmer.html

[S55] C++：结构化绑定
来源：http://dali.jinqigufen.top/Article/details/gtdkmfbwow.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.jinghuilouyu.cn/Article/details/gtzxehqlol.html

[S56] C++：optional
来源：http://dali.jlsjyb.cn/Article/details/gtybextmbo.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhiwuduotai.top/Article/details/gtwcndnggh.html

[S57] C++：编译期常量
来源：http://dali.ppjwa.cn/Article/details/gtoscsnnkb.html

constexpr int N = 10;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkoonoayg.html

[S58] C++：命名空间
来源：http://dali.quarkkingdee.top/Article/details/gtneujodqw.html

namespace ns { int f() { return 1; } }
来源：http://dali.kuanghao11.cn/Article/details/gtpqjzbrah.html

[S59] C++：静态断言
来源：http://dali.yj20258.top/Article/details/gtfnljfrpp.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.tanke756.top/Article/details/gtpatcppvr.html

[S60] C++：遍历并删除元素
来源：http://dali.gaohongyu789.top/Article/details/gtqdzdnzew.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.ppjwa.cn/Article/details/gtusdlrnyz.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbocshgbk.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.fzhhl.top/Article/details/gtqlqnwudf.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtygdpkptt.html

[T01] Kotlin：Hello World
来源：http://dali.shangyingyoupin.top/Article/details/gtzoqtxbij.html

println("Hello")
来源：http://dali.hywenlv.cn/Article/details/gtuovjtpmv.html

[T02] Kotlin：变量
来源：http://dali.nanxinkj.top/Article/details/gtrdaaplhs.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.yuxming.cn/Article/details/gtumlhxqil.html

[T03] Kotlin：字符串模板
来源：http://dali.fzhhl.top/Article/details/gtnajvjetc.html

"值: $b"
来源：http://dali.sufxvd.cn/Article/details/gtdugoeexx.html

[T04] Kotlin：空安全
来源：http://dali.yangfankeji.com/Article/details/gtabgiybgp.html

val n: String? = null;  n?.length
来源：http://dali.hongshengwenyu.top/Article/details/gtmdvuekcp.html

[T05] Kotlin：when 表达式
来源：http://dali.kuanghao11.cn/Article/details/gtvrolauyz.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.pengpengdd.cyou/Article/details/gtgivblxhe.html

[T06] Kotlin：集合映射
来源：http://dali.cucudq.cn/Article/details/gttrtgsgoc.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsusnyegi.html

[T07] Kotlin：集合过滤
来源：http://dali.ppjwa.cn/Article/details/gtxxypicfz.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.yj202588.top/Article/details/gtvezwrmgp.html

[T08] Kotlin：数据类
来源：http://dali.guannengcc.top/Article/details/gtvccfxzbe.html

data class User(val name: String, val age: Int)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyywipgak.html

[T09] Kotlin：扩展函数
来源：http://dali.hywenlv.cn/Article/details/gtrhcjyzjd.html

fun String.exclaim() = this + "!"
来源：http://dali.wangdashe.top/Article/details/gtwupdbbtk.html

[T10] Kotlin：默认参数
来源：http://dali.cdnleiting.top/Article/details/gtpeyexost.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zycfv.cn/Article/details/gtecluntgr.html

[T11] Kotlin：协程
来源：http://dali.hfpthk.cn/Article/details/gttotgadjy.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.ybcxt.top/Article/details/gtashvsoag.html

[T12] Kotlin：解构声明
来源：http://dali.316326.xyz/Article/details/gtxwevrnwk.html

val (a, b) = Pair(1, 2)
来源：http://dali.fzhhl.top/Article/details/gtrjotsyko.html

[T13] Kotlin：只读 Map
来源：http://dali.birdmap.top/Article/details/gtxpiwmjkc.html

val m = mapOf("a" to 1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiraocpov.html

[T14] Kotlin：循环
来源：http://dali.hongshengwenyu.top/Article/details/gtdwcwdial.html

for (i in 1..10) println(i)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmiikvzqf.html

[T15] Kotlin：接口
来源：http://dali.guannengcc.top/Article/details/gttwnkcazx.html

interface Shape { fun area(): Double }
来源：http://dali.chenlongwang.top/Article/details/gtayqbpzms.html

[T16] Swift：Hello World
来源：http://dali.316326.xyz/Article/details/gtroicjufq.html

print("Hello")
来源：http://dali.hongshengwenyu.top/Article/details/gtiwueglue.html

[T17] Swift：变量与常量
来源：http://dali.chenlongwang.top/Article/details/gtgwogexlv.html

var a = 1;  let b = 2
来源：http://dali.shzxlz.cn/Article/details/gtyhirrbht.html

[T18] Swift：字符串插值
来源：http://dali.aizwys.cn/Article/details/gtzskqmqdh.html

"值: \(b)"
来源：http://dali.yvedp.cn/Article/details/gtugwedzfg.html

[T19] Swift：可选绑定
来源：http://dali.guowangkeji.top/Article/details/gthqxtkynj.html

if let n = opt { print(n) }
来源：http://dali.shzxlz.cn/Article/details/gtlqaxxlyu.html

[T20] Swift：数组操作
来源：http://dali.yangfankeji.com/Article/details/gtzxejrcia.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.aizwys.cn/Article/details/gtdvhhpnkv.html

[T21] Swift：遍历
来源：http://dali.daxiang520.top/Article/details/gtwryqkptm.html

for x in a { print(x) }
来源：http://dali.shuidangran.top/Article/details/gtnmekkzgw.html

[T22] Swift：字典
来源：http://dali.ybcxt.top/Article/details/gttyuxpean.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.xylfe.cn/Article/details/gthhxpmvio.html

[T23] Swift：函数
来源：http://dali.xziqi.cn/Article/details/gtauyuninm.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.jiagoushi.top/Article/details/gtvmskomuk.html

[T24] Swift：闭包
来源：http://dali.shzxlz.cn/Article/details/gtcemtqgei.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.hammf.cn/Article/details/gtbkqsnyfh.html

[T25] Swift：结构体
来源：http://dali.daxiang520.top/Article/details/gtwkjrfeht.html

struct P { var x: Int }
来源：http://dali.bjfxy.top/Article/details/gtoqdxngsh.html

[T26] Swift：类与重写
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnjxwrmnk.html

class A: Base { override func f() {} }
来源：http://dali.sysykeji.top/Article/details/gtlsplijvf.html

[T27] Swift：错误处理
来源：http://dali.jiagoushi.top/Article/details/gtjoapszul.html

do { try f() } catch { print(error) }
来源：http://dali.vqdsnc.cn/Article/details/gtqktqqiyc.html

[T28] Swift：枚举
来源：http://dali.feifeiyinyue.top/Article/details/gtbozashln.html

enum Color { case red, green }
来源：http://dali.jinyuanbaomall.cn/Article/details/gttuzwgwcw.html

[T29] Swift：guard 提前返回
来源：http://dali.yueranfly.top/Article/details/gtqncwyemj.html

guard let x = opt else { return }
来源：http://dali.shanyushiyangtech.top/Article/details/gtcwxajrgd.html

[T30] Swift：协议
来源：http://dali.hfpthk.cn/Article/details/gtwumyzjrr.html

protocol Shape { func area() -> Double }
来源：http://dali.dashuyun.cn/Article/details/gtzmuddflr.html

[T31] Lua：Hello World
来源：http://dali.svipenyu.cn/Article/details/gtnbpbohcu.html

print("Hello")
来源：http://dali.ydzc1.top/Article/details/gtcihaylzb.html

[T32] Lua：局部变量
来源：http://dali.xziqi.cn/Article/details/gtgnbmvrjd.html

local a = 1
来源：http://dali.xuanzx.com/Article/details/gtiotyiyxj.html

[T33] Lua：表（数组）
来源：http://dali.wangshuangyany.cn/Article/details/gtbkxesehp.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmpjugisb.html

[T34] Lua：遍历表
来源：http://dali.yanxiufei.cn/Article/details/gtuwugimau.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.tanke756.top/Article/details/gtjzcwkkhh.html

[T35] Lua：字典表
来源：http://dali.cheryme.top/Article/details/gtpyppafcm.html

local d = { a = 1 };  d.b = 2
来源：http://dali.316326.xyz/Article/details/gtwhlmwbia.html

[T36] Lua：函数
来源：http://dali.tanke756.top/Article/details/gthqdgnsim.html

function add(a, b) return a + b end
来源：http://dali.meibo888.top/Article/details/gtpxzartmx.html

[T37] Lua：字符串拼接
来源：http://dali.cashguo.top/Article/details/gtuqmnoisv.html

"a" .. "b"
来源：http://dali.aizwys.cn/Article/details/gtdsxemwxs.html

[T38] Lua：条件
来源：http://dali.guowangkeji.top/Article/details/gtfkwnjeve.html

if x > 0 then print("正") end
来源：http://dali.sxryk.cn/Article/details/gtkoobjvpu.html

[T39] Lua：模式匹配
来源：http://dali.316326.xyz/Article/details/gtkgfqkzyk.html

string.find(s, "%d+")
来源：http://dali.zycfv.cn/Article/details/gtuqmmwoye.html

[T40] Lua：元表
来源：http://dali.cheryme.top/Article/details/gtuhyigkbk.html

setmetatable({}, { __index = base })
来源：http://dali.xylfe.cn/Article/details/gtaorvmsvv.html

[T41] Perl：Hello World
来源：http://dali.xylfe.cn/Article/details/gtpyznqnrp.html

print "Hello\n";
来源：http://dali.daria6918.cn/Article/details/gteajiwhkv.html

[T42] Perl：变量类型
来源：http://dali.shzxlz.cn/Article/details/gtsbwcdzoj.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.fengsongda.top/Article/details/gtnyvlsudj.html

[T43] Perl：字符串插值
来源：http://dali.ydzc1.top/Article/details/gtlrdyafkf.html

"值: $a"
来源：http://dali.feifeiyinyue.top/Article/details/gtinsqccjh.html

[T44] Perl：条件
来源：http://dali.aibaodan.cn/Article/details/gtphnunynl.html

if ($a > 0) { print "正"; }
来源：http://dali.svipenyu.cn/Article/details/gtcmdnwqgu.html

[T45] Perl：数组遍历
来源：http://dali.yanxiufei.cn/Article/details/gtuwjycozq.html

for my $x (@arr) { print $x; }
来源：http://dali.dianchejie.cn/Article/details/gttzzniheh.html

[T46] Perl：哈希操作
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpejqnxdc.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.cashguo.top/Article/details/gtcogrukqg.html

[T47] Perl：正则捕获
来源：http://dali.hammf.cn/Article/details/gtzqhdmgfu.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.nanxuanxn.top/Article/details/gtbiecsywi.html

[T48] Perl：正则替换
来源：http://dali.xylfe.cn/Article/details/gtgkfufdgz.html

$s =~ s/old/new/g;
来源：http://dali.yongpay.top/Article/details/gtnnrlrpma.html

[T49] Perl：函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpucsjmsd.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.tianlin.xyz/Article/details/gtogimwdvo.html

[T50] Perl：逐行读文件
来源：http://dali.fzhhl.top/Article/details/gtxzgyvwcb.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.yuanzhike.top/Article/details/gtdyuyjklz.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.wangshuangyany.cn/Article/details/gtjzxbsliq.html

[T51] Scala：Hello World
来源：http://dali.chenjidiqi.icu/Article/details/gtpmctuztj.html

println("Hello")
来源：http://dali.yj20258.top/Article/details/gtiilbmshr.html

[T52] Scala：变量
来源：http://dali.xylfe.cn/Article/details/gtvrltkqop.html

val a = 1;  var b = 2
来源：http://dali.cqqwz.cn/Article/details/gtwkobjtfz.html

[T53] Scala：字符串插值
来源：http://dali.wangdashe.top/Article/details/gtcqekgkig.html

s"值: $b"
来源：http://dali.jqgfzy.top/Article/details/gtphfxllut.html

[T54] Scala：集合映射
来源：http://dali.jqgfzy.top/Article/details/gtkzbvyibs.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhoulong.xyz/Article/details/gtbrhchfsc.html

[T55] Scala：集合过滤
来源：http://dali.ehwqpu.com/Article/details/gtkpgwcpps.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.316326.xyz/Article/details/gtlowttvjd.html

[T56] Scala：样例类
来源：http://dali.ybcxt.top/Article/details/gtineoyrfi.html

case class User(name: String, age: Int)
来源：http://dali.hnxiangtu.top/Article/details/gtokkkfhzo.html

[T57] Scala：模式匹配
来源：http://dali.aibaodan.cn/Article/details/gtiflkljen.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zdqjudy.top/Article/details/gtkmjozqrv.html

[T58] Scala：函数定义
来源：http://dali.kuanghao11.cn/Article/details/gtkytyyqhs.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgctjovpn.html

[T59] Scala：循环
来源：http://dali.zycfv.cn/Article/details/gthjvrlpmi.html

for (i <- 1 to 10) println(i)
来源：http://dali.jyoumei.cn/Article/details/gtwpedcxrr.html

[T60] Scala：折叠
来源：http://dali.havefunace.top/Article/details/gtpdzzfcbq.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtilbnegvl.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtjgswplal.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbdyggdud.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtmhwxvxpx.html

[U01] Py：创建虚拟环境
来源：http://dali.bjfxy.top/Article/details/gtnqdzgvmm.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.snrcjt.cn/Article/details/gtbmvwtckr.html

[U02] Py：导出 / 安装依赖
来源：http://dali.aizwys.cn/Article/details/gtdfufjdup.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.havefunace.top/Article/details/gtrdmamwfx.html

[U03] Py：加载 .env 配置
来源：http://dali.chenjidiqi.icu/Article/details/gtktsoifky.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.yuanzhike.top/Article/details/gtbojlrbar.html

[U04] Py：变量调试打印
来源：http://dali.feifeiyinyue.top/Article/details/gtvpekepgf.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.hywenlv.cn/Article/details/gtsdawkvxw.html

[U05] Py：列表去重且保序
来源：http://dali.nwbrower.top/Article/details/gtzsnmsepw.html

list(dict.fromkeys(arr))
来源：http://dali.smart0.xyz/Article/details/gtmcxuexhr.html

[U06] Py：合并两个字典
来源：http://dali.jyoumei.cn/Article/details/gtkkicwdlt.html

{**a, **b}
来源：http://dali.nwbrower.top/Article/details/gtstggnfis.html

[U07] Py：反转字典键值
来源：http://dali.bjfxy.top/Article/details/gtogbmybmu.html

{v: k for k, v in d.items()}
来源：http://dali.tanke756.top/Article/details/gthqyitbta.html

[U08] Py：展平二维列表
来源：http://dali.yj20258888.top/Article/details/gtdtvodala.html

[y for x in nested for y in x]
来源：http://dali.gaohongyu789.top/Article/details/gtwqsuprrx.html


<!-- 参考信息 -->