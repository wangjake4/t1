代发 wailian999

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.guowangkeji.top/Article/details/gt2hsazyhyf.html

[R72] 等待端口就绪
来源：http://dali.jianghu66.top/Article/details/gt2xydyhotk.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.jlsjyb.cn/Article/details/gt2kbcuzufy.html

[R73] 分割大日志
来源：http://dali.hysaishi.cn/Article/details/gt2tfpurqwk.html

split -l 1000 big.log part_
来源：http://dali.sweek.top/Article/details/gt2uxreirmw.html

[R74] 批量重命名
来源：http://dali.aibaodan.cn/Article/details/gt2emxnmuca.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.yueranfly.top/Article/details/gt2fnjxgsrr.html

[R75] 导出环境变量
来源：http://dali.ppjwa.cn/Article/details/gt2adpaomsy.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.aibaodan.cn/Article/details/gt2jskkvxav.html

[R76] 使用临时文件
来源：http://dali.yonumen.top/Article/details/gt2htmsdavb.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.meibo888.top/Article/details/gt2vfxkfdkt.html

[R77] 读取用户输入
来源：http://dali.tanke756.top/Article/details/gt2khqlzbdw.html

read -rp "请输入: " ans
来源：http://dali.yvedp.cn/Article/details/gt2kjyxlpue.html

[R78] 交互式菜单
来源：http://dali.pengpengdd.cyou/Article/details/gt2xysfgkyz.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.jqgufenzy.top/Article/details/gt2weayibbx.html

[R79] 解析命令行选项
来源：http://dali.jinqigufen.top/Article/details/gt2lglcexbv.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fatpvygt.html

[R80] 查看脚本执行耗时
来源：http://dali.yvedp.cn/Article/details/gt2amgizobp.html

time ./run.sh
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mvmliweo.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2npvzwght.html

S. C / C++ 专题
来源：http://dali.c1oappe.top/Article/details/gt2yavxhzbd.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gt2ytessvqs.html

[S01] C：Hello World
来源：http://dali.yvedp.cn/Article/details/gt2lmaegqnf.html

#include <stdio.h>
来源：http://dali.sysykeji.top/Article/details/gt2xvhryehw.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.yangfankeji.com/Article/details/gt2hepbksbp.html

[S02] C：变量与格式化输出
来源：http://dali.hnqzz.top/Article/details/gt2bdqwbyxg.html

int a = 10; printf("%d\n", a);
来源：http://dali.ppjwa.cn/Article/details/gt2fkhvoffs.html

[S03] C：读入整数
来源：http://dali.tianlin.xyz/Article/details/gt2yamubdme.html

int x; scanf("%d", &x);
来源：http://dali.smart0.xyz/Article/details/gt2iwqmlhkb.html

[S04] C：字符串复制
来源：http://dali.dianchejie.cn/Article/details/gt2glscziey.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.chenzaomai.com/Article/details/gt2atsqugko.html

[S05] C：字符串长度
来源：http://dali.cqqwz.cn/Article/details/gt2nguamwfk.html

strlen(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vkstkspy.html

[S06] C：字符串比较
来源：http://dali.dashuyun.cn/Article/details/gt2njafjcwj.html

strcmp(a, b) == 0
来源：http://dali.jlsjyb.cn/Article/details/gt2tptfennv.html

[S07] C：数组遍历求和
来源：http://dali.zhiwuduotai.top/Article/details/gt2zprslpem.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.jianghu66.top/Article/details/gt2hwctobvu.html

[S08] C：动态内存分配与释放
来源：http://dali.havefunace.top/Article/details/gt2fuzmjfvy.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhongyouzk.top/Article/details/gt2kspsingv.html

[S09] C：结构体定义与初始化
来源：http://dali.hammf.cn/Article/details/gt2xxojunjb.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.redwolf501.top/Article/details/gt2yirrmfnh.html

[S10] C：指针与解引用
来源：http://dali.xylfe.cn/Article/details/gt2lrphgksr.html

int *p = &a;  *p = 5;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2smfpswfw.html

[S11] C：逐行读文件
来源：http://dali.jinqigfzy.top/Article/details/gt2zhjpcmbp.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.yuanzhike.top/Article/details/gt2lsxeudil.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhongyouzk.top/Article/details/gt2kffziatk.html

fclose(f);
来源：http://dali.redwolf501.top/Article/details/gt2yrzzrkxy.html

[S12] C：写文件
来源：http://dali.0kj1m.cn/Article/details/gt2jbwvxyfy.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.jinqigufen.top/Article/details/gt2uzgmwcya.html

[S13] C：宏定义
来源：http://dali.hammf.cn/Article/details/gt2neghqghg.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.chenjidiqi.icu/Article/details/gt2ftqbussm.html

[S14] C：枚举
来源：http://dali.aibaodan.cn/Article/details/gt2ndcvivxy.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.feifeiyinyue.top/Article/details/gt2gixgxzpi.html

[S15] C：类型转换
来源：http://dali.cheryme.top/Article/details/gt2zticagrh.html

(double) a / b
来源：http://dali.jinqigfzy.top/Article/details/gt2ifwnzmob.html

[S16] C：位操作置位
来源：http://dali.sufxvd.cn/Article/details/gt2opalqwtr.html

x |= (1 << 3);
来源：http://dali.jyoumei.cn/Article/details/gt2rhazvzla.html

[S17] C：安全拼接字符串
来源：http://dali.iojbl.cn/Article/details/gt2cusxfxrp.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.gogol.net.cn/Article/details/gt2augrmygh.html

[S18] C：命令行参数
来源：http://dali.fzhhl.top/Article/details/gt2eeyzfatm.html

int main(int argc, char **argv)
来源：http://dali.yueranfly.top/Article/details/gt2vxyplfgm.html

[S19] C：快速排序
来源：http://dali.sufxvd.cn/Article/details/gt2wbdufbfm.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.shuidangran.top/Article/details/gt2zfvwxtib.html

[S20] C：二分查找
来源：http://dali.xuanzx.com/Article/details/gt2trzmwpju.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.shangyingyoupin.top/Article/details/gt2dlpzfrns.html

[S21] C：字符类别判断
来源：http://dali.wangdashe.top/Article/details/gt2dsdiwxur.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.wangshuangyany.cn/Article/details/gt2qwhdcnam.html

[S22] C：字符串转数字
来源：http://dali.daxiang520.top/Article/details/gt2wsdpdnch.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.iojbl.cn/Article/details/gt2deiwqngf.html

[S23] C：随机数
来源：http://dali.9152youxi.cn/Article/details/gt2yativtdq.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.yvedp.cn/Article/details/gt2pkoggqlk.html

[S24] C：获取本地时间
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xhaawiys.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.jianghu66.top/Article/details/gt2rhuiuelf.html

[S25] C：内存拷贝
来源：http://dali.jqgufenzy.top/Article/details/gt2yaenncsv.html

memcpy(dst, src, n);
来源：http://dali.aizwys.cn/Article/details/gt2bpsjehxi.html

[S26] C：内存清零
来源：http://dali.jlsjyb.cn/Article/details/gt2ulsuzadg.html

memset(a, 0, sizeof a);
来源：http://dali.jinqigfzy.top/Article/details/gt2xfbquytr.html

[S27] C：定义常量
来源：http://dali.jyoumei.cn/Article/details/gt2dddzmhha.html

const double PI = 3.14159;
来源：http://dali.cashguo.top/Article/details/gt2pjlgrvob.html

[S28] C：静态变量
来源：http://dali.xziqi.cn/Article/details/gt2umyoxdme.html

static int counter = 0;
来源：http://dali.ybcxt.top/Article/details/gt2taucuceb.html

[S29] C：变参函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ldsceuos.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.daria6918.cn/Article/details/gt2yzidsgwd.html

[S30] C：头文件保护
来源：http://dali.gogol.net.cn/Article/details/gt2mdeqcpms.html

#ifndef X_H
来源：http://dali.ppjwa.cn/Article/details/gt2dfwmgnqs.html

#define X_H
来源：http://dali.zhiwuduotai.top/Article/details/gt2orahheia.html

#endif
来源：http://dali.fengsongda.top/Article/details/gt2clanuvvr.html

[S31] C++：Hello World
来源：http://dali.dianchejie.cn/Article/details/gt2ujcpusph.html

#include <iostream>
来源：http://dali.sysykeji.top/Article/details/gt2lylfytcc.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.yonumen.top/Article/details/gt2qtunpfaa.html

[S32] C++：字符串
来源：http://dali.nanxuanxn.top/Article/details/gt2rggiapku.html

std::string s = "hi";  s += "!";
来源：http://dali.gotoacloud.top/Article/details/gt2asdaepaw.html

[S33] C++：vector 增删
来源：http://dali.cashguo.top/Article/details/gt2ohcisuzo.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhiwuduotai.top/Article/details/gt2dugmbwsz.html

[S34] C++：遍历 vector
来源：http://dali.cashguo.top/Article/details/gt2msxklqiq.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.andypj.xyz/Article/details/gt2shpivwrv.html

[S35] C++：map
来源：http://dali.ppjwa.cn/Article/details/gt2msgdcwdl.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hongshengwenyu.top/Article/details/gt2djkfbwsn.html

[S36] C++：unordered_map
来源：http://dali.yanxiufei.cn/Article/details/gt2fswxiihg.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yongpay.top/Article/details/gt2gjguxwgq.html

[S37] C++：set
来源：http://dali.yanxiufei.cn/Article/details/gt2rhkkfhgu.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.yj20258.top/Article/details/gt2cxbotyga.html

[S38] C++：排序
来源：http://dali.cdnleiting.top/Article/details/gt2xmhvkkqs.html

std::sort(v.begin(), v.end());
来源：http://dali.xylfe.cn/Article/details/gt2jurscsqo.html

[S39] C++：自定义比较器排序
来源：http://dali.shuidangran.top/Article/details/gt2mwgueiym.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.cdnleiting.top/Article/details/gt2hyirzxtn.html

[S40] C++：查找元素
来源：http://dali.bjfxy.top/Article/details/gt2ztmwjppw.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.sweek.top/Article/details/gt2fuskhulk.html

[S41] C++：类与构造函数
来源：http://dali.chenjidiqi.icu/Article/details/gt2avuehnuw.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.vqdsnc.cn/Article/details/gt2ggmnslcb.html

[S42] C++：继承与虚函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kckkegnh.html

class B : public Base { public: void f() override {} };
来源：http://dali.haohaochexian.top/Article/details/gt2mgbxqrke.html

[S43] C++：智能指针
来源：http://dali.yongpay.top/Article/details/gt2gnfeqimz.html

auto p = std::make_unique<int>(5);
来源：http://dali.cheryme.top/Article/details/gt2njsvlifr.html

[S44] C++：引用传参
来源：http://dali.yuxming.cn/Article/details/gt2zuznxria.html

void inc(int &x) { ++x; }
来源：http://dali.sxryk.cn/Article/details/gt2yablfkot.html

[S45] C++：lambda
来源：http://dali.9152youxi.cn/Article/details/gt2dtdzbeiu.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.mhx1999.top/Article/details/gt2ofhztzla.html

[S46] C++：函数模板
来源：http://dali.hysaishi.cn/Article/details/gt2tudkdncy.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.xinyue.icu/Article/details/gt2fywkqtly.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhixingplan.top/Article/details/gt2hofwfkus.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.ehwqpu.com/Article/details/gt2eipcipro.html

[S48] C++：逐行读文件
来源：http://dali.yuxming.cn/Article/details/gt2vnbhruux.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.jyoumei.cn/Article/details/gt2bwyamiib.html

while (std::getline(in, line)) { }
来源：http://dali.dianchejie.cn/Article/details/gt2tdstdcnm.html

[S49] C++：写文件
来源：http://dali.shzxlz.cn/Article/details/gt2raepqyat.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.yuxming.cn/Article/details/gt2yzuwgdbg.html

[S50] C++：格式化数字
来源：http://dali.ydzc1.top/Article/details/gt2uukldldd.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.vqdsnc.cn/Article/details/gt2dlrbnadf.html

[S51] C++：显式类型转换
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nezwcomf.html

static_cast<double>(a) / b
来源：http://dali.dashuyun.cn/Article/details/gt2buslnwtc.html

[S52] C++：const 与 noexcept
来源：http://dali.ybcxt.top/Article/details/gt2idcljryd.html

int size() const noexcept { return n_; }
来源：http://dali.havefunace.top/Article/details/gt2vhtvtcmk.html

[S53] C++：移动语义
来源：http://dali.wangshuangyany.cn/Article/details/gt2envykxyg.html

std::vector<int> w = std::move(v);
来源：http://dali.tianlin.xyz/Article/details/gt2tqbiwkjz.html

[S54] C++：异常处理
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tqlyemek.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.hfpthk.cn/Article/details/gt2facsyukh.html

[S55] C++：结构化绑定
来源：http://dali.gotoacloud.top/Article/details/gt2kphgsnrk.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zdqjudy.top/Article/details/gt2afxckosi.html

[S56] C++：optional
来源：http://dali.sysykeji.top/Article/details/gt2yeehiuzx.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yj202588.top/Article/details/gt2oqylgcmd.html

[S57] C++：编译期常量
来源：http://dali.shzxlz.cn/Article/details/gt2aijmrsfb.html

constexpr int N = 10;
来源：http://dali.cqqwz.cn/Article/details/gt2wocdnztp.html

[S58] C++：命名空间
来源：http://dali.yueranfly.top/Article/details/gt2nogablvk.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhoulong.xyz/Article/details/gt2mpmracsp.html

[S59] C++：静态断言
来源：http://dali.guannengcc.top/Article/details/gt2uydlakjv.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.ppjwa.cn/Article/details/gt2mcrrgwsl.html

[S60] C++：遍历并删除元素
来源：http://dali.xinyue.icu/Article/details/gt2nvggrexr.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.shzxlz.cn/Article/details/gt2dpaizpfu.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bxkqrost.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hqzppthl.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2rqlgpmcp.html

[T01] Kotlin：Hello World
来源：http://dali.sxryk.cn/Article/details/gt2rxqhvyow.html

println("Hello")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xzkcijky.html

[T02] Kotlin：变量
来源：http://dali.gogol.net.cn/Article/details/gt2yquujvht.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.yonumen.top/Article/details/gt2bgxvncyp.html

[T03] Kotlin：字符串模板
来源：http://dali.snrcjt.cn/Article/details/gt2xdqxovxb.html

"值: $b"
来源：http://dali.haohaochexian.top/Article/details/gt2jrwidhkv.html

[T04] Kotlin：空安全
来源：http://dali.sxryk.cn/Article/details/gt2qgtnaerq.html

val n: String? = null;  n?.length
来源：http://dali.gaohongyu789.top/Article/details/gt2jtzhychq.html

[T05] Kotlin：when 表达式
来源：http://dali.meibo888.top/Article/details/gt2nphqrhkr.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.cheryme.top/Article/details/gt2coqzihrv.html

[T06] Kotlin：集合映射
来源：http://dali.c1oappe.top/Article/details/gt2fsvoiejy.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cjvfajds.html

[T07] Kotlin：集合过滤
来源：http://dali.birdmap.top/Article/details/gt2yymznoue.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.yj20258888.top/Article/details/gt2jvsrvrwk.html

[T08] Kotlin：数据类
来源：http://dali.yvedp.cn/Article/details/gt2uqftvwur.html

data class User(val name: String, val age: Int)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2oyezzrol.html

[T09] Kotlin：扩展函数
来源：http://dali.tanke756.top/Article/details/gt2kmjytvup.html

fun String.exclaim() = this + "!"
来源：http://dali.chenzaomai.com/Article/details/gt2jfialgyk.html

[T10] Kotlin：默认参数
来源：http://dali.quarkkingdee.top/Article/details/gt2eqgvzuel.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhengqikj.top/Article/details/gt2nivdpabf.html

[T11] Kotlin：协程
来源：http://dali.dashuyun.cn/Article/details/gt2xhtlzrez.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.gzhubu.top/Article/details/gt2pxxkzrze.html

[T12] Kotlin：解构声明
来源：http://dali.hysaishi.cn/Article/details/gt2udprqgga.html

val (a, b) = Pair(1, 2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lskeeivq.html

[T13] Kotlin：只读 Map
来源：http://dali.yvedp.cn/Article/details/gt2sjisrrxl.html

val m = mapOf("a" to 1)
来源：http://dali.tanke756.top/Article/details/gt2dqbxltgd.html

[T14] Kotlin：循环
来源：http://dali.tian-w.cn/Article/details/gt2fttzisas.html

for (i in 1..10) println(i)
来源：http://dali.pycfn.com/Article/details/gt2kdvwvrsd.html

[T15] Kotlin：接口
来源：http://dali.pengpengdd.cyou/Article/details/gt2okyqvpup.html

interface Shape { fun area(): Double }
来源：http://dali.jyoumei.cn/Article/details/gt2fdvprlnz.html

[T16] Swift：Hello World
来源：http://dali.feifeiyinyue.top/Article/details/gt2novfdxuc.html

print("Hello")
来源：http://dali.yj20258.top/Article/details/gt2rogxtjmq.html

[T17] Swift：变量与常量
来源：http://dali.ydzc1.top/Article/details/gt2veduupcw.html

var a = 1;  let b = 2
来源：http://dali.yuxming.cn/Article/details/gt2hczewbco.html

[T18] Swift：字符串插值
来源：http://dali.haohaochexian.top/Article/details/gt2ouoodffy.html

"值: \(b)"
来源：http://dali.zhengqikj.top/Article/details/gt2nyoylzwh.html

[T19] Swift：可选绑定
来源：http://dali.fengsongda.top/Article/details/gt2vzalsxer.html

if let n = opt { print(n) }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wbpfppvx.html

[T20] Swift：数组操作
来源：http://dali.tianlin.xyz/Article/details/gt2cabrzklp.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.cucudq.cn/Article/details/gt2vtkjcsav.html

[T21] Swift：遍历
来源：http://dali.hywenlv.cn/Article/details/gt2ppfapigf.html

for x in a { print(x) }
来源：http://dali.sweek.top/Article/details/gt2ceuulhye.html

[T22] Swift：字典
来源：http://dali.redwolf501.top/Article/details/gt2qoujsjaz.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.yj20258.top/Article/details/gt2xkhlhefi.html

[T23] Swift：函数
来源：http://dali.nwbrower.top/Article/details/gt2bjxxdbvp.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.jqgfzy.top/Article/details/gt2ejffwmxi.html

[T24] Swift：闭包
来源：http://dali.cqqwz.cn/Article/details/gt2ubihvnre.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.pengpengdd.cyou/Article/details/gt2pjbiagdo.html

[T25] Swift：结构体
来源：http://dali.smart0.xyz/Article/details/gt2tfvcycbi.html

struct P { var x: Int }
来源：http://dali.jqgfzy.top/Article/details/gt2qhaqbnoq.html

[T26] Swift：类与重写
来源：http://dali.dashuyun.cn/Article/details/gt2ejszdukb.html

class A: Base { override func f() {} }
来源：http://dali.zhongyouzk.top/Article/details/gt2rozfaplu.html

[T27] Swift：错误处理
来源：http://dali.svipenyu.cn/Article/details/gt2fdbwgylz.html

do { try f() } catch { print(error) }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2czlhmaxi.html

[T28] Swift：枚举
来源：http://dali.jyoumei.cn/Article/details/gt2ecbompfx.html

enum Color { case red, green }
来源：http://dali.cucudq.cn/Article/details/gt2hpfapuvl.html

[T29] Swift：guard 提前返回
来源：http://dali.yanxiufei.cn/Article/details/gt2ypwakmwl.html

guard let x = opt else { return }
来源：http://dali.jyoumei.cn/Article/details/gt2bwaiuhqr.html

[T30] Swift：协议
来源：http://dali.wangshuangyany.cn/Article/details/gt2hqumufsk.html

protocol Shape { func area() -> Double }
来源：http://dali.bjfxy.top/Article/details/gt2prdqlrtj.html

[T31] Lua：Hello World
来源：http://dali.yuanzhike.top/Article/details/gt2pkifunmv.html

print("Hello")
来源：http://dali.yj20258.top/Article/details/gt2zfjeorwx.html

[T32] Lua：局部变量
来源：http://dali.jlsjyb.cn/Article/details/gt2cvddnavi.html

local a = 1
来源：http://dali.aizwys.cn/Article/details/gt2ovgmenqu.html

[T33] Lua：表（数组）
来源：http://dali.nwbrower.top/Article/details/gt2riukqisa.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.hfpthk.cn/Article/details/gt2pzyfypts.html

[T34] Lua：遍历表
来源：http://dali.sysykeji.top/Article/details/gt2uinzjdsi.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.jinqigfzy.top/Article/details/gt2foiblopy.html

[T35] Lua：字典表
来源：http://dali.sysykeji.top/Article/details/gt2hkhapyba.html

local d = { a = 1 };  d.b = 2
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uvgepkeu.html

[T36] Lua：函数
来源：http://dali.meibo888.top/Article/details/gt2dwybrbot.html

function add(a, b) return a + b end
来源：http://dali.haohaochexian.top/Article/details/gt2tccuilai.html

[T37] Lua：字符串拼接
来源：http://dali.shangyingyoupin.top/Article/details/gt2iitijlwt.html

"a" .. "b"
来源：http://dali.hywenlv.cn/Article/details/gt2siecknox.html

[T38] Lua：条件
来源：http://dali.yonumen.top/Article/details/gt2tjujjdfr.html

if x > 0 then print("正") end
来源：http://dali.jianghu66.top/Article/details/gt2tebkakcp.html

[T39] Lua：模式匹配
来源：http://dali.yonumen.top/Article/details/gt2ulydtlvi.html

string.find(s, "%d+")
来源：http://dali.zdqjudy.top/Article/details/gt2wyihtqgv.html

[T40] Lua：元表
来源：http://dali.xinyue.icu/Article/details/gt2hxbvybox.html

setmetatable({}, { __index = base })
来源：http://dali.hysaishi.cn/Article/details/gt2wicffjri.html

[T41] Perl：Hello World
来源：http://dali.chenjidiqi.icu/Article/details/gt2qprdtppl.html

print "Hello\n";
来源：http://dali.smart0.xyz/Article/details/gt2yhgrveud.html

[T42] Perl：变量类型
来源：http://dali.svipenyu.cn/Article/details/gt2jakjexon.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.gogol.net.cn/Article/details/gt2ojipqyfb.html

[T43] Perl：字符串插值
来源：http://dali.hnqzz.top/Article/details/gt2edisswpl.html

"值: $a"
来源：http://dali.zhoulong.xyz/Article/details/gt2ubtpveiw.html

[T44] Perl：条件
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lfkmbyoe.html

if ($a > 0) { print "正"; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2nfsqtbat.html

[T45] Perl：数组遍历
来源：http://dali.feifeiyinyue.top/Article/details/gt2zakjkkkc.html

for my $x (@arr) { print $x; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hongggwc.html

[T46] Perl：哈希操作
来源：http://dali.zhoulong.xyz/Article/details/gt2nhwigxrn.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.cdnleiting.top/Article/details/gt2ryczfitf.html

[T47] Perl：正则捕获
来源：http://dali.sysykeji.top/Article/details/gt2dgldyzfx.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.aizwys.cn/Article/details/gt2ftgfohog.html

[T48] Perl：正则替换
来源：http://dali.xziqi.cn/Article/details/gt2wtcclzpr.html

$s =~ s/old/new/g;
来源：http://dali.ehwqpu.com/Article/details/gt2rkihnhys.html

[T49] Perl：函数
来源：http://dali.zycfv.cn/Article/details/gt2cfoplqif.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.pycfn.com/Article/details/gt2yyuhjznq.html

[T50] Perl：逐行读文件
来源：http://dali.havefunace.top/Article/details/gt2tbbedynl.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.smart0.xyz/Article/details/gt2mmgwizuo.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.ybcxt.top/Article/details/gt2nsulplqc.html

[T51] Scala：Hello World
来源：http://dali.havefunace.top/Article/details/gt2tsmauzlu.html

println("Hello")
来源：http://dali.xuetiantiany.cn/Article/details/gt2ndeohiti.html

[T52] Scala：变量
来源：http://dali.cashguo.top/Article/details/gt2cvzphqmu.html

val a = 1;  var b = 2
来源：http://dali.tianlin.xyz/Article/details/gt2cvzddgfg.html

[T53] Scala：字符串插值
来源：http://dali.ehwqpu.com/Article/details/gt2uuohtvoq.html

s"值: $b"
来源：http://dali.cdnleiting.top/Article/details/gt2mbeeckhu.html

[T54] Scala：集合映射
来源：http://dali.wangshuangyany.cn/Article/details/gt2dfjcwoea.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.haohaochexian.top/Article/details/gt2xzrfaarl.html

[T55] Scala：集合过滤
来源：http://dali.hysaishi.cn/Article/details/gt2kbqsedce.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.cashguo.top/Article/details/gt2oqofadyc.html

[T56] Scala：样例类
来源：http://dali.daxiang520.top/Article/details/gt2bstoeqwm.html

case class User(name: String, age: Int)
来源：http://dali.pycfn.com/Article/details/gt2onujqyrz.html

[T57] Scala：模式匹配
来源：http://dali.cqqwz.cn/Article/details/gt2mwqknqcr.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lobxewny.html

[T58] Scala：函数定义
来源：http://dali.ydzc1.top/Article/details/gt2vwrooirg.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.bjfxy.top/Article/details/gt2vsdvuolv.html

[T59] Scala：循环
来源：http://dali.sxryk.cn/Article/details/gt2vtosveny.html

for (i <- 1 to 10) println(i)
来源：http://dali.cucudq.cn/Article/details/gt2caeisqam.html

[T60] Scala：折叠
来源：http://dali.zdqjudy.top/Article/details/gt2lubdelam.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.nanxuanxn.top/Article/details/gt2fpushzig.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2imkjnqdg.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhixingplan.top/Article/details/gt2qdulgcaj.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gt2rgbazqww.html

[U01] Py：创建虚拟环境
来源：http://dali.vqdsnc.cn/Article/details/gt2ribmsdnx.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.xuanzx.com/Article/details/gt2cvqrlnqx.html

[U02] Py：导出 / 安装依赖
来源：http://dali.cashguo.top/Article/details/gt2ffrycvqo.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ulurifbc.html

[U03] Py：加载 .env 配置
来源：http://dali.jinqigufen.top/Article/details/gt2pfmbiilq.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.tanke756.top/Article/details/gt2ogxntydc.html

[U04] Py：变量调试打印
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qftxzina.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.chenlongwang.top/Article/details/gt2xdrifffi.html

[U05] Py：列表去重且保序
来源：http://dali.gzhubu.top/Article/details/gt2xzsskkec.html

list(dict.fromkeys(arr))
来源：http://dali.jiagoushi.top/Article/details/gt2qvutikxo.html

[U06] Py：合并两个字典
来源：http://dali.haohaochexian.top/Article/details/gt2zebpxusi.html

{**a, **b}
来源：http://dali.jlsjyb.cn/Article/details/gt2nahjvhml.html

[U07] Py：反转字典键值
来源：http://dali.hfpthk.cn/Article/details/gt2atacvkpm.html

{v: k for k, v in d.items()}
来源：http://dali.cucudq.cn/Article/details/gt2jaoqcuck.html

[U08] Py：展平二维列表
来源：http://dali.hongshengwenyu.top/Article/details/gt2qlkryxue.html

[y for x in nested for y in x]
来源：http://dali.yangfankeji.com/Article/details/gt2lfcquqoj.html

[U09] Py：字典取最大值的键
来源：http://dali.hongshengwenyu.top/Article/details/gt2pqvktgdj.html

max(d, key=d.get)
来源：http://dali.fengsongda.top/Article/details/gt2pyxdyvxv.html

[U10] Py：按值排序字典
来源：http://dali.yueranfly.top/Article/details/gt2tpqspztq.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.pycfn.com/Article/details/gt2toovynxk.html

[U11] Py：生成器表达式
来源：http://dali.sysykeji.top/Article/details/gt2jttcrzpi.html

(x * 2 for x in arr)
来源：http://dali.hammf.cn/Article/details/gt2tgjoaybs.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.nanxinkj.top/Article/details/gt2dyhwiqqp.html

Counter(arr).most_common(3)
来源：http://dali.dianchejie.cn/Article/details/gt2glthgmtx.html


<!-- 参考信息 -->