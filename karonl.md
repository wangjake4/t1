代发 wailian999

openssl rand -hex 16
来源：http://dali.sxryk.cn/Article/details/gt2cybwmitt.html

[R68] 计算文件校验值
来源：http://dali.xziqi.cn/Article/details/gt2mwvwprpj.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.cashguo.top/Article/details/gt2bqfjsept.html

[R69] 生成随机密码
来源：http://dali.yvedp.cn/Article/details/gt2qjnjyzdu.html

head -c 16 /dev/urandom | base64
来源：http://dali.sweek.top/Article/details/gt2vbinvfst.html

[R70] 时间戳与互转
来源：http://dali.shuidangran.top/Article/details/gt2svxlsyqk.html

date +%s;  date -d @1700000000
来源：http://dali.hammf.cn/Article/details/gt2bmcovjis.html

[R71] 日期格式化
来源：http://dali.xuanzx.com/Article/details/gt2vlooernn.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.hammf.cn/Article/details/gt2ksbepxjs.html

[R72] 等待端口就绪
来源：http://dali.iojbl.cn/Article/details/gt2hhtvgxuw.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhiwuduotai.top/Article/details/gt2mbkvskzx.html

[R73] 分割大日志
来源：http://dali.svipenyu.cn/Article/details/gt2yhygckhl.html

split -l 1000 big.log part_
来源：http://dali.dianchejie.cn/Article/details/gt2zzmqdlaw.html

[R74] 批量重命名
来源：http://dali.svipenyu.cn/Article/details/gt2bsptuygz.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.cdnleiting.top/Article/details/gt2brkrnkek.html

[R75] 导出环境变量
来源：http://dali.mhx1999.top/Article/details/gt2wuzbhcjm.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.sysykeji.top/Article/details/gt2bujuvunb.html

[R76] 使用临时文件
来源：http://dali.gaohongyu789.top/Article/details/gt2ebzzfkar.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zycfv.cn/Article/details/gt2fbuncnlp.html

[R77] 读取用户输入
来源：http://dali.jinqigfzy.top/Article/details/gt2civzevkf.html

read -rp "请输入: " ans
来源：http://dali.yj202588.top/Article/details/gt2wsnlmpaw.html

[R78] 交互式菜单
来源：http://dali.zhixingplan.top/Article/details/gt2pqkbskfh.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.andypj.xyz/Article/details/gt2glxhljlb.html

[R79] 解析命令行选项
来源：http://dali.yj202588.top/Article/details/gt2iadtsgdr.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.dashuyun.cn/Article/details/gt2acqttobn.html

[R80] 查看脚本执行耗时
来源：http://dali.meibo888.top/Article/details/gt2jgytaycr.html

time ./run.sh
来源：http://dali.yueranfly.top/Article/details/gt2ojgpwsxs.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2xjfuecag.html

S. C / C++ 专题
来源：http://dali.zdqjudy.top/Article/details/gt2nszpvlmj.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2lvswjfcg.html

[S01] C：Hello World
来源：http://dali.gogol.net.cn/Article/details/gt2gifehrvb.html

#include <stdio.h>
来源：http://dali.iojbl.cn/Article/details/gt2desuypfa.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.yj20258888.top/Article/details/gt2nxhnrmap.html

[S02] C：变量与格式化输出
来源：http://dali.nanxinkj.top/Article/details/gt2uewbrnzp.html

int a = 10; printf("%d\n", a);
来源：http://dali.nanxuanxn.top/Article/details/gt2hdyoeekf.html

[S03] C：读入整数
来源：http://dali.yuanzhike.top/Article/details/gt2mpcurlhi.html

int x; scanf("%d", &x);
来源：http://dali.zycfv.cn/Article/details/gt2tiidajzf.html

[S04] C：字符串复制
来源：http://dali.ivvv.top/Article/details/gt2wcftjsku.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.shzxlz.cn/Article/details/gt2rawlyhbv.html

[S05] C：字符串长度
来源：http://dali.xziqi.cn/Article/details/gt2tmsvnvve.html

strlen(s)
来源：http://dali.cashguo.top/Article/details/gt2ncnlkyqs.html

[S06] C：字符串比较
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nxzsadcf.html

strcmp(a, b) == 0
来源：http://dali.jlsjyb.cn/Article/details/gt2aoweiyoo.html

[S07] C：数组遍历求和
来源：http://dali.ehwqpu.com/Article/details/gt2bmzmwpbx.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.jinqigfzy.top/Article/details/gt2dpbelqmt.html

[S08] C：动态内存分配与释放
来源：http://dali.zycfv.cn/Article/details/gt2oveqkazj.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.fzhhl.top/Article/details/gt2vzssweae.html

[S09] C：结构体定义与初始化
来源：http://dali.hysaishi.cn/Article/details/gt2iemtruue.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.nanxuanxn.top/Article/details/gt2xzmsggos.html

[S10] C：指针与解引用
来源：http://dali.vqdsnc.cn/Article/details/gt2xdsexmmw.html

int *p = &a;  *p = 5;
来源：http://dali.guannengcc.top/Article/details/gt2myzakqnq.html

[S11] C：逐行读文件
来源：http://dali.gzhubu.top/Article/details/gt2sfvnuhdg.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.haohaochexian.top/Article/details/gt2yowhvmaj.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.xuanzx.com/Article/details/gt2ekfqteug.html

fclose(f);
来源：http://dali.pengpengdd.cyou/Article/details/gt2fpeihzli.html

[S12] C：写文件
来源：http://dali.zhiwuduotai.top/Article/details/gt2pcdeprqh.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.bjfxy.top/Article/details/gt2uwfcalwn.html

[S13] C：宏定义
来源：http://dali.316326.xyz/Article/details/gt2ymfmlhqi.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.yj20258888.top/Article/details/gt2iyppnomx.html

[S14] C：枚举
来源：http://dali.dashuyun.cn/Article/details/gt2asrsrtlw.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.9152youxi.cn/Article/details/gt2yvsouorq.html

[S15] C：类型转换
来源：http://dali.ehwqpu.com/Article/details/gt2ezkadzpi.html

(double) a / b
来源：http://dali.shzxlz.cn/Article/details/gt2bqpvuhod.html

[S16] C：位操作置位
来源：http://dali.tianlin.xyz/Article/details/gt2vqommjmt.html

x |= (1 << 3);
来源：http://dali.hnqzz.top/Article/details/gt2ntfpomys.html

[S17] C：安全拼接字符串
来源：http://dali.bjfxy.top/Article/details/gt2hvtptcub.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.mhx1999.top/Article/details/gt2twipgluy.html

[S18] C：命令行参数
来源：http://dali.zhiwuduotai.top/Article/details/gt2dumojrsq.html

int main(int argc, char **argv)
来源：http://dali.aizwys.cn/Article/details/gt2tykjcnlu.html

[S19] C：快速排序
来源：http://dali.yj20258.top/Article/details/gt2zaycnqob.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.shangyingyoupin.top/Article/details/gt2mvndillx.html

[S20] C：二分查找
来源：http://dali.snrcjt.cn/Article/details/gt2drjejvbs.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.nanxuanxn.top/Article/details/gt2uvlfajmo.html

[S21] C：字符类别判断
来源：http://dali.kuanghao11.cn/Article/details/gt2uprucrsz.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.redwolf501.top/Article/details/gt2zqxezyjq.html

[S22] C：字符串转数字
来源：http://dali.andypj.xyz/Article/details/gt2yxujeahe.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.yuanzhike.top/Article/details/gt2sxyqtdmt.html

[S23] C：随机数
来源：http://dali.snrcjt.cn/Article/details/gt2orynzedq.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.jlsjyb.cn/Article/details/gt2uusbzrgn.html

[S24] C：获取本地时间
来源：http://dali.yanxiufei.cn/Article/details/gt2ksyhzrsn.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.iojbl.cn/Article/details/gt2vtlfitsz.html

[S25] C：内存拷贝
来源：http://dali.jinqigufen.top/Article/details/gt2ggpxpnsp.html

memcpy(dst, src, n);
来源：http://dali.xinyue.icu/Article/details/gt2fxwroxkr.html

[S26] C：内存清零
来源：http://dali.ybcxt.top/Article/details/gt2upvnnfdx.html

memset(a, 0, sizeof a);
来源：http://dali.nwbrower.top/Article/details/gt2gcalylih.html

[S27] C：定义常量
来源：http://dali.meibo888.top/Article/details/gt2vlvhapwq.html

const double PI = 3.14159;
来源：http://dali.xuetiantiany.cn/Article/details/gt2dtbqtpdn.html

[S28] C：静态变量
来源：http://dali.hongshengwenyu.top/Article/details/gt2ueehymmf.html

static int counter = 0;
来源：http://dali.yongpay.top/Article/details/gt2rekowctj.html

[S29] C：变参函数
来源：http://dali.chenjidiqi.icu/Article/details/gt2sneltlip.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.yj20258.top/Article/details/gt2vnmkchzr.html

[S30] C：头文件保护
来源：http://dali.svipenyu.cn/Article/details/gt2pxttdhfi.html

#ifndef X_H
来源：http://dali.mhx1999.top/Article/details/gt2vmpctocv.html

#define X_H
来源：http://dali.jlsjyb.cn/Article/details/gt2iotncijj.html

#endif
来源：http://dali.zhoulong.xyz/Article/details/gt2dosnnezw.html

[S31] C++：Hello World
来源：http://dali.hammf.cn/Article/details/gt2exgnhajp.html

#include <iostream>
来源：http://dali.quarkkingdee.top/Article/details/gt2ezqzjman.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.tanke756.top/Article/details/gt2xczonpva.html

[S32] C++：字符串
来源：http://dali.jqgfzy.top/Article/details/gt2xbotahbf.html

std::string s = "hi";  s += "!";
来源：http://dali.nanxuanxn.top/Article/details/gt2nmsvjiib.html

[S33] C++：vector 增删
来源：http://dali.jinqigufen.top/Article/details/gt2grdinyqi.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.ppjwa.cn/Article/details/gt2gdxnwxjb.html

[S34] C++：遍历 vector
来源：http://dali.9152youxi.cn/Article/details/gt2tdnbinsb.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.jyoumei.cn/Article/details/gt2ekwthelz.html

[S35] C++：map
来源：http://dali.havefunace.top/Article/details/gt2lqwvvnzk.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hysaishi.cn/Article/details/gt2trmnaxpy.html

[S36] C++：unordered_map
来源：http://dali.gotoacloud.top/Article/details/gt2vfbapmlr.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.quarkkingdee.top/Article/details/gt2ybaglorw.html

[S37] C++：set
来源：http://dali.wangdashe.top/Article/details/gt2ssghkzmn.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.cucudq.cn/Article/details/gt2ilipqpqv.html

[S38] C++：排序
来源：http://dali.yuxming.cn/Article/details/gt2dnyncbxy.html

std::sort(v.begin(), v.end());
来源：http://dali.yj20258888.top/Article/details/gt2pmknkgnq.html

[S39] C++：自定义比较器排序
来源：http://dali.jinqigufen.top/Article/details/gt2srplwrzo.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.ivvv.top/Article/details/gt2rhkklfwf.html

[S40] C++：查找元素
来源：http://dali.cheryme.top/Article/details/gt2ueiibecf.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2psurmrow.html

[S41] C++：类与构造函数
来源：http://dali.ybcxt.top/Article/details/gt2uomgttyl.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.aibaodan.cn/Article/details/gt2nzgidfik.html

[S42] C++：继承与虚函数
来源：http://dali.chenjidiqi.icu/Article/details/gt2bdizvclt.html

class B : public Base { public: void f() override {} };
来源：http://dali.aibaodan.cn/Article/details/gt2jodyrytt.html

[S43] C++：智能指针
来源：http://dali.jqgufenzy.top/Article/details/gt2prnbybwx.html

auto p = std::make_unique<int>(5);
来源：http://dali.yuxming.cn/Article/details/gt2xgpnqbdi.html

[S44] C++：引用传参
来源：http://dali.yuxming.cn/Article/details/gt2dcufztqz.html

void inc(int &x) { ++x; }
来源：http://dali.nwbrower.top/Article/details/gt2kyqbohdo.html

[S45] C++：lambda
来源：http://dali.jiagoushi.top/Article/details/gt2zbfjdlka.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.birdmap.top/Article/details/gt2eovmzaou.html

[S46] C++：函数模板
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lormhzzz.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.birdmap.top/Article/details/gt2qybqosms.html

[S47] C++：结构化绑定遍历
来源：http://dali.cdnleiting.top/Article/details/gt2ipbbmcyo.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.hammf.cn/Article/details/gt2hslvstfl.html

[S48] C++：逐行读文件
来源：http://dali.meibo888.top/Article/details/gt2igkrukwm.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.gotoacloud.top/Article/details/gt2azucdcnn.html

while (std::getline(in, line)) { }
来源：http://dali.shuidangran.top/Article/details/gt2ogqwffqw.html

[S49] C++：写文件
来源：http://dali.jianghu66.top/Article/details/gt2zuujzech.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.bjfxy.top/Article/details/gt2ghormile.html

[S50] C++：格式化数字
来源：http://dali.zhixingplan.top/Article/details/gt2xqmcfncm.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.iojbl.cn/Article/details/gt2kuukjqks.html

[S51] C++：显式类型转换
来源：http://dali.hammf.cn/Article/details/gt2qotcqxlx.html

static_cast<double>(a) / b
来源：http://dali.jianghu66.top/Article/details/gt2egxykekz.html

[S52] C++：const 与 noexcept
来源：http://dali.gogol.net.cn/Article/details/gt2qylebnjh.html

int size() const noexcept { return n_; }
来源：http://dali.cqqwz.cn/Article/details/gt2hgsebzqg.html

[S53] C++：移动语义
来源：http://dali.hysaishi.cn/Article/details/gt2xriaqcql.html

std::vector<int> w = std::move(v);
来源：http://dali.tanke756.top/Article/details/gt2xhakeqef.html

[S54] C++：异常处理
来源：http://dali.pengpengdd.cyou/Article/details/gt2vfnloxvb.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.yonumen.top/Article/details/gt2ngvjysmh.html

[S55] C++：结构化绑定
来源：http://dali.wangshuangyany.cn/Article/details/gt2jfxrpusi.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.xuetiantiany.cn/Article/details/gt2nydhlmwk.html

[S56] C++：optional
来源：http://dali.yj20258.top/Article/details/gt2gkmusoky.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.shuidangran.top/Article/details/gt2dgflxpte.html

[S57] C++：编译期常量
来源：http://dali.tian-w.cn/Article/details/gt2ekikvtol.html

constexpr int N = 10;
来源：http://dali.ydzc1.top/Article/details/gt2rqyrzrdp.html

[S58] C++：命名空间
来源：http://dali.9152youxi.cn/Article/details/gt2rubjuhek.html

namespace ns { int f() { return 1; } }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gthdxqip.html

[S59] C++：静态断言
来源：http://dali.yj20258.top/Article/details/gt2ieljtfoi.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.yongpay.top/Article/details/gt2qwurqhwp.html

[S60] C++：遍历并删除元素
来源：http://dali.zdqjudy.top/Article/details/gt2lsvmuujl.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.dianchejie.cn/Article/details/gt2pwhidaqn.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xcitbfce.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.xylfe.cn/Article/details/gt2ytdhsfyg.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mvwbfasl.html

[T01] Kotlin：Hello World
来源：http://dali.dianchejie.cn/Article/details/gt2nftilwpv.html

println("Hello")
来源：http://dali.sweek.top/Article/details/gt2ctskwwje.html

[T02] Kotlin：变量
来源：http://dali.haohaochexian.top/Article/details/gt2ynnsywsj.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.nanxuanxn.top/Article/details/gt2ezvqscxe.html

[T03] Kotlin：字符串模板
来源：http://dali.redwolf501.top/Article/details/gt2kkyouqhj.html

"值: $b"
来源：http://dali.316326.xyz/Article/details/gt2pomwfmoy.html

[T04] Kotlin：空安全
来源：http://dali.shangyingyoupin.top/Article/details/gt2erjbubaq.html

val n: String? = null;  n?.length
来源：http://dali.aizwys.cn/Article/details/gt2frhqelah.html

[T05] Kotlin：when 表达式
来源：http://dali.svipenyu.cn/Article/details/gt2muguowru.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.cqqwz.cn/Article/details/gt2fkklfwjv.html

[T06] Kotlin：集合映射
来源：http://dali.gaohongyu789.top/Article/details/gt2cofzuymj.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.yj202588.top/Article/details/gt2vbhacjqz.html

[T07] Kotlin：集合过滤
来源：http://dali.cheryme.top/Article/details/gt2aihxvrkq.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.gzhubu.top/Article/details/gt2isfxcibs.html

[T08] Kotlin：数据类
来源：http://dali.hnxiangtu.top/Article/details/gt2kqgygmaa.html

data class User(val name: String, val age: Int)
来源：http://dali.yanxiufei.cn/Article/details/gt2zmiwxfjb.html

[T09] Kotlin：扩展函数
来源：http://dali.mhx1999.top/Article/details/gt2httsdhhw.html

fun String.exclaim() = this + "!"
来源：http://dali.9152youxi.cn/Article/details/gt2bzowqlpa.html

[T10] Kotlin：默认参数
来源：http://dali.nwbrower.top/Article/details/gt2tmkerpqi.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.yj20258888.top/Article/details/gt2cmbdrpfo.html

[T11] Kotlin：协程
来源：http://dali.andypj.xyz/Article/details/gt2whzcfrsn.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vidnvpha.html

[T12] Kotlin：解构声明
来源：http://dali.smart0.xyz/Article/details/gt2vgksalgf.html

val (a, b) = Pair(1, 2)
来源：http://dali.dashuyun.cn/Article/details/gt2aiesdsbu.html

[T13] Kotlin：只读 Map
来源：http://dali.yj20258.top/Article/details/gt2rwjctsvk.html

val m = mapOf("a" to 1)
来源：http://dali.zhengqikj.top/Article/details/gt2jhtyjfpc.html

[T14] Kotlin：循环
来源：http://dali.tian-w.cn/Article/details/gt2bfbcslps.html

for (i in 1..10) println(i)
来源：http://dali.guannengcc.top/Article/details/gt2osmuuwme.html

[T15] Kotlin：接口
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pybpyhhj.html

interface Shape { fun area(): Double }
来源：http://dali.chenlongwang.top/Article/details/gt2ffmcatkd.html

[T16] Swift：Hello World
来源：http://dali.yonumen.top/Article/details/gt2ngkybacj.html

print("Hello")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mhzorgpe.html

[T17] Swift：变量与常量
来源：http://dali.gotoacloud.top/Article/details/gt2djifmrzd.html

var a = 1;  let b = 2
来源：http://dali.snrcjt.cn/Article/details/gt2turobflr.html

[T18] Swift：字符串插值
来源：http://dali.yuanzhike.top/Article/details/gt2jnowafdy.html

"值: \(b)"
来源：http://dali.hywenlv.cn/Article/details/gt2kyqysnib.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2odxfpikn.html

if let n = opt { print(n) }
来源：http://dali.yonumen.top/Article/details/gt2fafaljoy.html

[T20] Swift：数组操作
来源：http://dali.zhoulong.xyz/Article/details/gt2zqwrvwmc.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.hnqzz.top/Article/details/gt2dcoixmul.html

[T21] Swift：遍历
来源：http://dali.nanxuanxn.top/Article/details/gt2aleceahj.html

for x in a { print(x) }
来源：http://dali.svipenyu.cn/Article/details/gt2tygqmwla.html

[T22] Swift：字典
来源：http://dali.sxryk.cn/Article/details/gt2ammjqqux.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.yanxiufei.cn/Article/details/gt2obxdklne.html

[T23] Swift：函数
来源：http://dali.yj202588.top/Article/details/gt2dkqqbauo.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.guannengcc.top/Article/details/gt2lknwiyyk.html

[T24] Swift：闭包
来源：http://dali.ybcxt.top/Article/details/gt2hdtkggjo.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.nanxinkj.top/Article/details/gt2rnkqrmdk.html

[T25] Swift：结构体
来源：http://dali.yueranfly.top/Article/details/gt2kfvfoqyu.html

struct P { var x: Int }
来源：http://dali.ppjwa.cn/Article/details/gt2nnxulwbu.html

[T26] Swift：类与重写
来源：http://dali.hnxiangtu.top/Article/details/gt2cnduoujn.html

class A: Base { override func f() {} }
来源：http://dali.yj202588.top/Article/details/gt2qivhfhbf.html

[T27] Swift：错误处理
来源：http://dali.wangdashe.top/Article/details/gt2tipxqhoh.html

do { try f() } catch { print(error) }
来源：http://dali.pycfn.com/Article/details/gt2oqhwktjj.html

[T28] Swift：枚举
来源：http://dali.chenlongwang.top/Article/details/gt2nixlmvkz.html

enum Color { case red, green }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gffmywqq.html

[T29] Swift：guard 提前返回
来源：http://dali.gogol.net.cn/Article/details/gt2xmflcbrj.html

guard let x = opt else { return }
来源：http://dali.nanxuanxn.top/Article/details/gt2tcvsaypt.html

[T30] Swift：协议
来源：http://dali.yj20258.top/Article/details/gt2ykbkrvuk.html

protocol Shape { func area() -> Double }
来源：http://dali.zhongyouzk.top/Article/details/gt2rcgxphvn.html

[T31] Lua：Hello World
来源：http://dali.daxiang520.top/Article/details/gt2ezefhvvp.html

print("Hello")
来源：http://dali.jqgufenzy.top/Article/details/gt2qfdisnag.html

[T32] Lua：局部变量
来源：http://dali.haohaochexian.top/Article/details/gt2mvxgwcgf.html

local a = 1
来源：http://dali.iojbl.cn/Article/details/gt2dludygdg.html

[T33] Lua：表（数组）
来源：http://dali.ppjwa.cn/Article/details/gt2cfxscswn.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.nanxinkj.top/Article/details/gt2emvxjqec.html

[T34] Lua：遍历表
来源：http://dali.redwolf501.top/Article/details/gt2cursymqh.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.yuxming.cn/Article/details/gt2vcgriyrs.html

[T35] Lua：字典表
来源：http://dali.nanxuanxn.top/Article/details/gt2ynfkhgih.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhengqikj.top/Article/details/gt2kccabspi.html

[T36] Lua：函数
来源：http://dali.vqdsnc.cn/Article/details/gt2ovbrhils.html

function add(a, b) return a + b end
来源：http://dali.hnqzz.top/Article/details/gt2vkwhatmc.html

[T37] Lua：字符串拼接
来源：http://dali.dianchejie.cn/Article/details/gt2fgefwgdr.html

"a" .. "b"
来源：http://dali.chenjidiqi.icu/Article/details/gt2upamhtxg.html

[T38] Lua：条件
来源：http://dali.yuanzhike.top/Article/details/gt2pceukvgp.html

if x > 0 then print("正") end
来源：http://dali.zdqjudy.top/Article/details/gt2vwnpgfms.html

[T39] Lua：模式匹配
来源：http://dali.kuanghao11.cn/Article/details/gt2pbvjmhnp.html

string.find(s, "%d+")
来源：http://dali.tanke756.top/Article/details/gt2mgztbthp.html

[T40] Lua：元表
来源：http://dali.zdqjudy.top/Article/details/gt2xsemzwlb.html

setmetatable({}, { __index = base })
来源：http://dali.hnxiangtu.top/Article/details/gt2iwmmxbfl.html

[T41] Perl：Hello World
来源：http://dali.jinqigufen.top/Article/details/gt2wwzrjicg.html

print "Hello\n";
来源：http://dali.zhiwuduotai.top/Article/details/gt2ijsogggo.html

[T42] Perl：变量类型
来源：http://dali.zhoulong.xyz/Article/details/gt2pbwuzvke.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.nanxuanxn.top/Article/details/gt2xgestlqc.html

[T43] Perl：字符串插值
来源：http://dali.cdnleiting.top/Article/details/gt2nbokekee.html

"值: $a"
来源：http://dali.feifeiyinyue.top/Article/details/gt2dtnsxenr.html

[T44] Perl：条件
来源：http://dali.wangshuangyany.cn/Article/details/gt2neqvabyb.html

if ($a > 0) { print "正"; }
来源：http://dali.aizwys.cn/Article/details/gt2xprdlzkn.html

[T45] Perl：数组遍历
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hcnxjora.html

for my $x (@arr) { print $x; }
来源：http://dali.aibaodan.cn/Article/details/gt2qzrzxjgx.html

[T46] Perl：哈希操作
来源：http://dali.wangdashe.top/Article/details/gt2sgrwksnm.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.jianghu66.top/Article/details/gt2oscqoanm.html

[T47] Perl：正则捕获
来源：http://dali.hnqzz.top/Article/details/gt2aznoywgy.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.hnxiangtu.top/Article/details/gt2ppbxgxsz.html

[T48] Perl：正则替换
来源：http://dali.jqgfzy.top/Article/details/gt2akspnger.html

$s =~ s/old/new/g;
来源：http://dali.cdnleiting.top/Article/details/gt2recolpnx.html

[T49] Perl：函数
来源：http://dali.jianghu66.top/Article/details/gt2cujbwtdu.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.mhx1999.top/Article/details/gt2ioaifkpd.html

[T50] Perl：逐行读文件
来源：http://dali.hysaishi.cn/Article/details/gt2nloxxzad.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.xylfe.cn/Article/details/gt2grdevmks.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.ehwqpu.com/Article/details/gt2kdrdrzhl.html

[T51] Scala：Hello World
来源：http://dali.fzhhl.top/Article/details/gt2cxctkedq.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ibsqzkno.html

[T52] Scala：变量
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2srjgmgoz.html

val a = 1;  var b = 2
来源：http://dali.dianchejie.cn/Article/details/gt2ligciwxt.html

[T53] Scala：字符串插值
来源：http://dali.yvedp.cn/Article/details/gt2gordhvau.html

s"值: $b"
来源：http://dali.gogol.net.cn/Article/details/gt2rrqigcgt.html

[T54] Scala：集合映射
来源：http://dali.jqgufenzy.top/Article/details/gt2lyfmwkyu.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zycfv.cn/Article/details/gt2eklowaft.html

[T55] Scala：集合过滤
来源：http://dali.meibo888.top/Article/details/gt2xsnraheu.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.bjfxy.top/Article/details/gt2hpotzows.html

[T56] Scala：样例类
来源：http://dali.xylfe.cn/Article/details/gt2gbnxrojw.html

case class User(name: String, age: Int)
来源：http://dali.aibaodan.cn/Article/details/gt2ogqdhfwj.html

[T57] Scala：模式匹配
来源：http://dali.nwbrower.top/Article/details/gt2ddlwymqg.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.fzhhl.top/Article/details/gt2sotzcqif.html

[T58] Scala：函数定义
来源：http://dali.sweek.top/Article/details/gt2akttmzhi.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.svipenyu.cn/Article/details/gt2nexiykjo.html

[T59] Scala：循环
来源：http://dali.zhengqikj.top/Article/details/gt2kbplbrpn.html

for (i <- 1 to 10) println(i)
来源：http://dali.zycfv.cn/Article/details/gt2ueyiayxn.html

[T60] Scala：折叠
来源：http://dali.yvedp.cn/Article/details/gt2wgeeooys.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.nwbrower.top/Article/details/gt2vevpwmcu.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gt2idajzzrf.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.smart0.xyz/Article/details/gt2woiwxdjl.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gt2haljezvs.html

[U01] Py：创建虚拟环境
来源：http://dali.feifeiyinyue.top/Article/details/gt2wtzeoutm.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.yangfankeji.com/Article/details/gt2zjikmqtf.html

[U02] Py：导出 / 安装依赖
来源：http://dali.yj20258.top/Article/details/gt2twsgwbgr.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.yvedp.cn/Article/details/gt2qewbpgoj.html

[U03] Py：加载 .env 配置
来源：http://dali.redwolf501.top/Article/details/gt2tnodsama.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.xziqi.cn/Article/details/gt2nlcmgoes.html

[U04] Py：变量调试打印
来源：http://dali.yuanzhike.top/Article/details/gt2wdnwwivc.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.yj202588.top/Article/details/gt2muppcffd.html

[U05] Py：列表去重且保序
来源：http://dali.cqqwz.cn/Article/details/gt2shufwfos.html

list(dict.fromkeys(arr))
来源：http://dali.cucudq.cn/Article/details/gt2xxalfszm.html

[U06] Py：合并两个字典
来源：http://dali.xziqi.cn/Article/details/gt2vcqbypyl.html

{**a, **b}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2razynvdk.html

[U07] Py：反转字典键值
来源：http://dali.tian-w.cn/Article/details/gt2anfarmmb.html

{v: k for k, v in d.items()}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bcolqhyo.html

[U08] Py：展平二维列表
来源：http://dali.chenlongwang.top/Article/details/gt2dqmwabgv.html

[y for x in nested for y in x]
来源：http://dali.ivvv.top/Article/details/gt2lqypicnp.html


<!-- 参考信息 -->