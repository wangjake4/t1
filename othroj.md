代发 wailian999

openssl rand -hex 16
来源：http://dali.shzxlz.cn/Article/details/gt2bilbmras.html

[R68] 计算文件校验值
来源：http://dali.yanxiufei.cn/Article/details/gt2vsvmbeui.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.guannengcc.top/Article/details/gt2efjrprrf.html

[R69] 生成随机密码
来源：http://dali.ehwqpu.com/Article/details/gt2ppbuzflw.html

head -c 16 /dev/urandom | base64
来源：http://dali.cheryme.top/Article/details/gt2iiufbhso.html

[R70] 时间戳与互转
来源：http://dali.svipenyu.cn/Article/details/gt2tzqdfiyq.html

date +%s;  date -d @1700000000
来源：http://dali.dianchejie.cn/Article/details/gt2ydquovjk.html

[R71] 日期格式化
来源：http://dali.nanxinkj.top/Article/details/gt2pmasabsn.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.ehwqpu.com/Article/details/gt2vmbrrncm.html

[R72] 等待端口就绪
来源：http://dali.birdmap.top/Article/details/gt2qykvvakb.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.0kj1m.cn/Article/details/gt2rkacguos.html

[R73] 分割大日志
来源：http://dali.cucudq.cn/Article/details/gt2iknppeet.html

split -l 1000 big.log part_
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gmgjhqmt.html

[R74] 批量重命名
来源：http://dali.tian-w.cn/Article/details/gt2dpdhvrug.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.yueranfly.top/Article/details/gt2ezhhrqrs.html

[R75] 导出环境变量
来源：http://dali.xuetiantiany.cn/Article/details/gt2eejzgzpx.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.yonumen.top/Article/details/gt2wsdcwewg.html

[R76] 使用临时文件
来源：http://dali.andypj.xyz/Article/details/gt2cozxtzyd.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.fengsongda.top/Article/details/gt2glhkckvh.html

[R77] 读取用户输入
来源：http://dali.jianghu66.top/Article/details/gt2jzyvtprz.html

read -rp "请输入: " ans
来源：http://dali.dashuyun.cn/Article/details/gt2ojbphkpv.html

[R78] 交互式菜单
来源：http://dali.gotoacloud.top/Article/details/gt2pznbsvcy.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ltyztgdz.html

[R79] 解析命令行选项
来源：http://dali.ppjwa.cn/Article/details/gt2ygrenxay.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.jlsjyb.cn/Article/details/gt2ykdsgcyg.html

[R80] 查看脚本执行耗时
来源：http://dali.jyoumei.cn/Article/details/gt2giiqmsiz.html

time ./run.sh
来源：http://dali.wangdashe.top/Article/details/gt2jcjwiqfu.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2cbzwtryc.html

S. C / C++ 专题
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2czxwcahd.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gt2qhubgrwk.html

[S01] C：Hello World
来源：http://dali.wangdashe.top/Article/details/gt2olesjxlg.html

#include <stdio.h>
来源：http://dali.cqqwz.cn/Article/details/gt2xkvtswrm.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2xledgekd.html

[S02] C：变量与格式化输出
来源：http://dali.sweek.top/Article/details/gt2wjzcnhtu.html

int a = 10; printf("%d\n", a);
来源：http://dali.ydzc1.top/Article/details/gt2spswfyuy.html

[S03] C：读入整数
来源：http://dali.xuetiantiany.cn/Article/details/gt2vetypkze.html

int x; scanf("%d", &x);
来源：http://dali.hysaishi.cn/Article/details/gt2kkjwizms.html

[S04] C：字符串复制
来源：http://dali.daria6918.cn/Article/details/gt2asxgiezb.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.havefunace.top/Article/details/gt2hrypyywd.html

[S05] C：字符串长度
来源：http://dali.yvedp.cn/Article/details/gt2xmzelvvr.html

strlen(s)
来源：http://dali.yvedp.cn/Article/details/gt2madfxsdm.html

[S06] C：字符串比较
来源：http://dali.quarkkingdee.top/Article/details/gt2spmxyyyw.html

strcmp(a, b) == 0
来源：http://dali.zhiwuduotai.top/Article/details/gt2ftwhqwdb.html

[S07] C：数组遍历求和
来源：http://dali.pycfn.com/Article/details/gt2uhqkicse.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.shuidangran.top/Article/details/gt2tybkxbvc.html

[S08] C：动态内存分配与释放
来源：http://dali.aibaodan.cn/Article/details/gt2ddbotepj.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.feifeiyinyue.top/Article/details/gt2cacufyqv.html

[S09] C：结构体定义与初始化
来源：http://dali.gotoacloud.top/Article/details/gt2pfyclcqz.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.wangshuangyany.cn/Article/details/gt2vgtvzbgg.html

[S10] C：指针与解引用
来源：http://dali.haohaochexian.top/Article/details/gt2xlspqduv.html

int *p = &a;  *p = 5;
来源：http://dali.zhiwuduotai.top/Article/details/gt2wyhbrfsz.html

[S11] C：逐行读文件
来源：http://dali.kuanghao11.cn/Article/details/gt2uqzneayc.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.ehwqpu.com/Article/details/gt2tqjwpetr.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.kuanghao11.cn/Article/details/gt2wtmspsof.html

fclose(f);
来源：http://dali.yongpay.top/Article/details/gt2uhsjsjct.html

[S12] C：写文件
来源：http://dali.cheryme.top/Article/details/gt2ngggklfd.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.redwolf501.top/Article/details/gt2olisfcax.html

[S13] C：宏定义
来源：http://dali.cheryme.top/Article/details/gt2uircybtc.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.dashuyun.cn/Article/details/gt2gvizxnbw.html

[S14] C：枚举
来源：http://dali.yonumen.top/Article/details/gt2oynznhbv.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.ehwqpu.com/Article/details/gt2imdukdyj.html

[S15] C：类型转换
来源：http://dali.zhoulong.xyz/Article/details/gt2mfldlles.html

(double) a / b
来源：http://dali.pengpengdd.cyou/Article/details/gt2yclmfzlq.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2askmrafk.html

x |= (1 << 3);
来源：http://dali.svipenyu.cn/Article/details/gt2vogvcawr.html

[S17] C：安全拼接字符串
来源：http://dali.feifeiyinyue.top/Article/details/gt2mlvzykwc.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.kuanghao11.cn/Article/details/gt2imnpgwit.html

[S18] C：命令行参数
来源：http://dali.jyoumei.cn/Article/details/gt2xkgzfynw.html

int main(int argc, char **argv)
来源：http://dali.xziqi.cn/Article/details/gt2crywkaef.html

[S19] C：快速排序
来源：http://dali.guowangkeji.top/Article/details/gt2gjrsyzxg.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.fzhhl.top/Article/details/gt2ttaoppty.html

[S20] C：二分查找
来源：http://dali.tianlin.xyz/Article/details/gt2rfbgursc.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.haohaochexian.top/Article/details/gt2pxjrkdru.html

[S21] C：字符类别判断
来源：http://dali.xuetiantiany.cn/Article/details/gt2juuwykts.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.yangfankeji.com/Article/details/gt2wtdszzye.html

[S22] C：字符串转数字
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yqbvtudy.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.iojbl.cn/Article/details/gt2ytuciesv.html

[S23] C：随机数
来源：http://dali.hammf.cn/Article/details/gt2qydsmhfo.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.ydzc1.top/Article/details/gt2ipdugabz.html

[S24] C：获取本地时间
来源：http://dali.daria6918.cn/Article/details/gt2zoogrcop.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.tanke756.top/Article/details/gt2gtjjfbzz.html

[S25] C：内存拷贝
来源：http://dali.snrcjt.cn/Article/details/gt2puxleaib.html

memcpy(dst, src, n);
来源：http://dali.birdmap.top/Article/details/gt2shcmjsjn.html

[S26] C：内存清零
来源：http://dali.ppjwa.cn/Article/details/gt2mxxvasmy.html

memset(a, 0, sizeof a);
来源：http://dali.sweek.top/Article/details/gt2xewayurv.html

[S27] C：定义常量
来源：http://dali.pycfn.com/Article/details/gt2awlrexvx.html

const double PI = 3.14159;
来源：http://dali.yueranfly.top/Article/details/gt2fnwfabeh.html

[S28] C：静态变量
来源：http://dali.hysaishi.cn/Article/details/gt2peyowspe.html

static int counter = 0;
来源：http://dali.redwolf501.top/Article/details/gt2ksztuxhi.html

[S29] C：变参函数
来源：http://dali.zhixingplan.top/Article/details/gt2gyfrrslv.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.yonumen.top/Article/details/gt2ntvqyslb.html

[S30] C：头文件保护
来源：http://dali.jinqigfzy.top/Article/details/gt2ctmcdsfa.html

#ifndef X_H
来源：http://dali.yanxiufei.cn/Article/details/gt2yvjufxsf.html

#define X_H
来源：http://dali.birdmap.top/Article/details/gt2avyfhlai.html

#endif
来源：http://dali.meibo888.top/Article/details/gt2rgespcle.html

[S31] C++：Hello World
来源：http://dali.gogol.net.cn/Article/details/gt2cxywirgt.html

#include <iostream>
来源：http://dali.zhoulong.xyz/Article/details/gt2iavyzkeg.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.smart0.xyz/Article/details/gt2xbdpdpcz.html

[S32] C++：字符串
来源：http://dali.cashguo.top/Article/details/gt2twrfdozk.html

std::string s = "hi";  s += "!";
来源：http://dali.zhixingplan.top/Article/details/gt2rjubtrxx.html

[S33] C++：vector 增删
来源：http://dali.vqdsnc.cn/Article/details/gt2nqfpbiid.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zycfv.cn/Article/details/gt2tkkwktxo.html

[S34] C++：遍历 vector
来源：http://dali.daria6918.cn/Article/details/gt2uxfffqiq.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.yvedp.cn/Article/details/gt2whjknjks.html

[S35] C++：map
来源：http://dali.aizwys.cn/Article/details/gt2kzzzlvto.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.smart0.xyz/Article/details/gt2icmunpsg.html

[S36] C++：unordered_map
来源：http://dali.zhengqikj.top/Article/details/gt2axwccjxc.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2oduhilsk.html

[S37] C++：set
来源：http://dali.wangshuangyany.cn/Article/details/gt2xbljarfc.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.9152youxi.cn/Article/details/gt2wmhkdhee.html

[S38] C++：排序
来源：http://dali.feifeiyinyue.top/Article/details/gt2bmijkdtu.html

std::sort(v.begin(), v.end());
来源：http://dali.havefunace.top/Article/details/gt2ojpsvhst.html

[S39] C++：自定义比较器排序
来源：http://dali.vqdsnc.cn/Article/details/gt2eicpaxed.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.snrcjt.cn/Article/details/gt2segymqag.html

[S40] C++：查找元素
来源：http://dali.hysaishi.cn/Article/details/gt2xppawyfu.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.yuanzhike.top/Article/details/gt2bibcdkli.html

[S41] C++：类与构造函数
来源：http://dali.jyoumei.cn/Article/details/gt2mxjxbahr.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.wangdashe.top/Article/details/gt2yehjibdq.html

[S42] C++：继承与虚函数
来源：http://dali.chenlongwang.top/Article/details/gt2rzvqjuvb.html

class B : public Base { public: void f() override {} };
来源：http://dali.guowangkeji.top/Article/details/gt2eaxvsfei.html

[S43] C++：智能指针
来源：http://dali.tianlin.xyz/Article/details/gt2bjiwlkxd.html

auto p = std::make_unique<int>(5);
来源：http://dali.aibaodan.cn/Article/details/gt2rpvhgrnr.html

[S44] C++：引用传参
来源：http://dali.jinqigufen.top/Article/details/gt2vqhfkgcp.html

void inc(int &x) { ++x; }
来源：http://dali.jiagoushi.top/Article/details/gt2prwjtezf.html

[S45] C++：lambda
来源：http://dali.nwbrower.top/Article/details/gt2rebjlads.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.ybcxt.top/Article/details/gt2pkmcyhro.html

[S46] C++：函数模板
来源：http://dali.zhixingplan.top/Article/details/gt2tgmtndik.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zycfv.cn/Article/details/gt2xeijnfam.html

[S47] C++：结构化绑定遍历
来源：http://dali.hammf.cn/Article/details/gt2jdmipmcy.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.vqdsnc.cn/Article/details/gt2vnierwbg.html

[S48] C++：逐行读文件
来源：http://dali.ivvv.top/Article/details/gt2qcidmnpo.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hvawuewg.html

while (std::getline(in, line)) { }
来源：http://dali.svipenyu.cn/Article/details/gt2ceqsmtif.html

[S49] C++：写文件
来源：http://dali.chenjidiqi.icu/Article/details/gt2pnucmttw.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.shangyingyoupin.top/Article/details/gt2yeobxnwz.html

[S50] C++：格式化数字
来源：http://dali.yj20258.top/Article/details/gt2prdgsrtk.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.yj20258888.top/Article/details/gt2tnudhrfg.html

[S51] C++：显式类型转换
来源：http://dali.xziqi.cn/Article/details/gt2huwgusas.html

static_cast<double>(a) / b
来源：http://dali.tianlin.xyz/Article/details/gt2wimwkbie.html

[S52] C++：const 与 noexcept
来源：http://dali.hysaishi.cn/Article/details/gt2uyntztep.html

int size() const noexcept { return n_; }
来源：http://dali.sufxvd.cn/Article/details/gt2njlhdrfg.html

[S53] C++：移动语义
来源：http://dali.fzhhl.top/Article/details/gt2kfyabfrr.html

std::vector<int> w = std::move(v);
来源：http://dali.yuanzhike.top/Article/details/gt2cdiidata.html

[S54] C++：异常处理
来源：http://dali.pengpengdd.cyou/Article/details/gt2njlxnkoh.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.xziqi.cn/Article/details/gt2jghnkhaj.html

[S55] C++：结构化绑定
来源：http://dali.hammf.cn/Article/details/gt2reecyhws.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.yvedp.cn/Article/details/gt2npvwvaas.html

[S56] C++：optional
来源：http://dali.cashguo.top/Article/details/gt2pjlzcahv.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.daria6918.cn/Article/details/gt2lgivpjls.html

[S57] C++：编译期常量
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kntsjhnt.html

constexpr int N = 10;
来源：http://dali.andypj.xyz/Article/details/gt2nvtfbmho.html

[S58] C++：命名空间
来源：http://dali.gaohongyu789.top/Article/details/gt2savbvjhc.html

namespace ns { int f() { return 1; } }
来源：http://dali.fengsongda.top/Article/details/gt2mgvpaeji.html

[S59] C++：静态断言
来源：http://dali.fzhhl.top/Article/details/gt2nbdhynhk.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.xinyue.icu/Article/details/gt2xvrpgfpq.html

[S60] C++：遍历并删除元素
来源：http://dali.dashuyun.cn/Article/details/gt2lmaaqrwz.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.yanxiufei.cn/Article/details/gt2mmtflase.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2jojxvfdd.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.hfpthk.cn/Article/details/gt2ymvdgycj.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2enjkffzs.html

[T01] Kotlin：Hello World
来源：http://dali.nwbrower.top/Article/details/gt2hthplilj.html

println("Hello")
来源：http://dali.9152youxi.cn/Article/details/gt2ksghcavt.html

[T02] Kotlin：变量
来源：http://dali.zdqjudy.top/Article/details/gt2slmxneji.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.pycfn.com/Article/details/gt2ygzuktgd.html

[T03] Kotlin：字符串模板
来源：http://dali.yonumen.top/Article/details/gt2nuisirjr.html

"值: $b"
来源：http://dali.yanxiufei.cn/Article/details/gt2eysmlzus.html

[T04] Kotlin：空安全
来源：http://dali.yuanzhike.top/Article/details/gt2yflesbcl.html

val n: String? = null;  n?.length
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fbknzrri.html

[T05] Kotlin：when 表达式
来源：http://dali.dashuyun.cn/Article/details/gt2ltuwqukm.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.ybcxt.top/Article/details/gt2ozmohbmi.html

[T06] Kotlin：集合映射
来源：http://dali.aizwys.cn/Article/details/gt2beyqedmp.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.gzhubu.top/Article/details/gt2dumaxbvb.html

[T07] Kotlin：集合过滤
来源：http://dali.sufxvd.cn/Article/details/gt2ohwblpxc.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.yuxming.cn/Article/details/gt2fbqudvgv.html

[T08] Kotlin：数据类
来源：http://dali.haohaochexian.top/Article/details/gt2gmlludsn.html

data class User(val name: String, val age: Int)
来源：http://dali.nwbrower.top/Article/details/gt2fubhbbht.html

[T09] Kotlin：扩展函数
来源：http://dali.cucudq.cn/Article/details/gt2kydzajlg.html

fun String.exclaim() = this + "!"
来源：http://dali.xuanzx.com/Article/details/gt2zqqtnvxb.html

[T10] Kotlin：默认参数
来源：http://dali.tanke756.top/Article/details/gt2iytbdjhq.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.birdmap.top/Article/details/gt2gtsofcdj.html

[T11] Kotlin：协程
来源：http://dali.xuanzx.com/Article/details/gt2uhrlfjxb.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhengqikj.top/Article/details/gt2zxftaful.html

[T12] Kotlin：解构声明
来源：http://dali.chenzaomai.com/Article/details/gt2lnnmfhpi.html

val (a, b) = Pair(1, 2)
来源：http://dali.gaohongyu789.top/Article/details/gt2ixuovlax.html

[T13] Kotlin：只读 Map
来源：http://dali.gzhubu.top/Article/details/gt2ukuidcog.html

val m = mapOf("a" to 1)
来源：http://dali.nwbrower.top/Article/details/gt2nuxcfasu.html

[T14] Kotlin：循环
来源：http://dali.bjfxy.top/Article/details/gt2ptzzvbdp.html

for (i in 1..10) println(i)
来源：http://dali.vqdsnc.cn/Article/details/gt2tzudmtch.html

[T15] Kotlin：接口
来源：http://dali.jinghuilouyu.cn/Article/details/gt2msrpuxyx.html

interface Shape { fun area(): Double }
来源：http://dali.jlsjyb.cn/Article/details/gt2umbefgdp.html

[T16] Swift：Hello World
来源：http://dali.dashuyun.cn/Article/details/gt2ybzvcuoh.html

print("Hello")
来源：http://dali.zycfv.cn/Article/details/gt2uesqlzmc.html

[T17] Swift：变量与常量
来源：http://dali.gotoacloud.top/Article/details/gt2ejmkpphu.html

var a = 1;  let b = 2
来源：http://dali.zhongyouzk.top/Article/details/gt2tdckdryp.html

[T18] Swift：字符串插值
来源：http://dali.pycfn.com/Article/details/gt2urtlkrjf.html

"值: \(b)"
来源：http://dali.yuanzhike.top/Article/details/gt2xrhxomdd.html

[T19] Swift：可选绑定
来源：http://dali.zdqjudy.top/Article/details/gt2qjyavruf.html

if let n = opt { print(n) }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hvauxifu.html

[T20] Swift：数组操作
来源：http://dali.dashuyun.cn/Article/details/gt2fbmkrapb.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.wangdashe.top/Article/details/gt2zvrkeaut.html

[T21] Swift：遍历
来源：http://dali.jlsjyb.cn/Article/details/gt2eltothxk.html

for x in a { print(x) }
来源：http://dali.shangyingyoupin.top/Article/details/gt2oznxdcnk.html

[T22] Swift：字典
来源：http://dali.hfpthk.cn/Article/details/gt2fzlwczbv.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.jianghu66.top/Article/details/gt2oukzxisi.html

[T23] Swift：函数
来源：http://dali.sufxvd.cn/Article/details/gt2nmpgtqrk.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zdqjudy.top/Article/details/gt2oopetxew.html

[T24] Swift：闭包
来源：http://dali.gaohongyu789.top/Article/details/gt2rvsjsvyv.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.ybcxt.top/Article/details/gt2lntqrrwp.html

[T25] Swift：结构体
来源：http://dali.jyoumei.cn/Article/details/gt2evuastzp.html

struct P { var x: Int }
来源：http://dali.ppjwa.cn/Article/details/gt2frgsikkx.html

[T26] Swift：类与重写
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dqcvsclz.html

class A: Base { override func f() {} }
来源：http://dali.jianghu66.top/Article/details/gt2winrteut.html

[T27] Swift：错误处理
来源：http://dali.jiagoushi.top/Article/details/gt2cxtshscq.html

do { try f() } catch { print(error) }
来源：http://dali.chenlongwang.top/Article/details/gt2flptotfx.html

[T28] Swift：枚举
来源：http://dali.ybcxt.top/Article/details/gt2waqynqza.html

enum Color { case red, green }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kgagkila.html

[T29] Swift：guard 提前返回
来源：http://dali.tian-w.cn/Article/details/gt2hzvhukaj.html

guard let x = opt else { return }
来源：http://dali.jyoumei.cn/Article/details/gt2rdusfmih.html

[T30] Swift：协议
来源：http://dali.nanxuanxn.top/Article/details/gt2srqrstwa.html

protocol Shape { func area() -> Double }
来源：http://dali.fzhhl.top/Article/details/gt2okudzwlf.html

[T31] Lua：Hello World
来源：http://dali.cashguo.top/Article/details/gt2olgfayuy.html

print("Hello")
来源：http://dali.shangyingyoupin.top/Article/details/gt2gycmsrgf.html

[T32] Lua：局部变量
来源：http://dali.gogol.net.cn/Article/details/gt2rpqqrcig.html

local a = 1
来源：http://dali.meibo888.top/Article/details/gt2mipdcqsd.html

[T33] Lua：表（数组）
来源：http://dali.yuxming.cn/Article/details/gt2mdsssmpo.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.pycfn.com/Article/details/gt2cqxhkkap.html

[T34] Lua：遍历表
来源：http://dali.svipenyu.cn/Article/details/gt2kopoustm.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.hnqzz.top/Article/details/gt2ilppeaha.html

[T35] Lua：字典表
来源：http://dali.gzhubu.top/Article/details/gt2mbccqrec.html

local d = { a = 1 };  d.b = 2
来源：http://dali.sxryk.cn/Article/details/gt2fffecpep.html

[T36] Lua：函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vtzmpagl.html

function add(a, b) return a + b end
来源：http://dali.9152youxi.cn/Article/details/gt2jfwzisaz.html

[T37] Lua：字符串拼接
来源：http://dali.nwbrower.top/Article/details/gt2cnvuzzcs.html

"a" .. "b"
来源：http://dali.jinqigufen.top/Article/details/gt2cqmierll.html

[T38] Lua：条件
来源：http://dali.gaohongyu789.top/Article/details/gt2kvogoprw.html

if x > 0 then print("正") end
来源：http://dali.nanxinkj.top/Article/details/gt2qoucssgo.html

[T39] Lua：模式匹配
来源：http://dali.jqgufenzy.top/Article/details/gt2ihghkayh.html

string.find(s, "%d+")
来源：http://dali.wangshuangyany.cn/Article/details/gt2onvncviy.html

[T40] Lua：元表
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jpsfdhbo.html

setmetatable({}, { __index = base })
来源：http://dali.zhixingplan.top/Article/details/gt2gxxooroh.html

[T41] Perl：Hello World
来源：http://dali.tanke756.top/Article/details/gt2orflpkbj.html

print "Hello\n";
来源：http://dali.cdnleiting.top/Article/details/gt2kdzdcpwj.html

[T42] Perl：变量类型
来源：http://dali.yj202588.top/Article/details/gt2gxxsvwyo.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.pycfn.com/Article/details/gt2aljieytz.html

[T43] Perl：字符串插值
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vjbyvmwc.html

"值: $a"
来源：http://dali.hywenlv.cn/Article/details/gt2adnghrhh.html

[T44] Perl：条件
来源：http://dali.xuanzx.com/Article/details/gt2zueyrjmr.html

if ($a > 0) { print "正"; }
来源：http://dali.birdmap.top/Article/details/gt2ontdcxex.html

[T45] Perl：数组遍历
来源：http://dali.wangshuangyany.cn/Article/details/gt2ogieiqav.html

for my $x (@arr) { print $x; }
来源：http://dali.gaohongyu789.top/Article/details/gt2rsneqrph.html

[T46] Perl：哈希操作
来源：http://dali.tian-w.cn/Article/details/gt2drzwecxv.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.daria6918.cn/Article/details/gt2rvzcoxgq.html

[T47] Perl：正则捕获
来源：http://dali.jqgfzy.top/Article/details/gt2mxybbxaa.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.nanxuanxn.top/Article/details/gt2xdqwhtpk.html

[T48] Perl：正则替换
来源：http://dali.zhiwuduotai.top/Article/details/gt2coysuzbv.html

$s =~ s/old/new/g;
来源：http://dali.smart0.xyz/Article/details/gt2aoktgmrt.html

[T49] Perl：函数
来源：http://dali.feifeiyinyue.top/Article/details/gt2xmdlqzds.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.yongpay.top/Article/details/gt2kbufoksf.html

[T50] Perl：逐行读文件
来源：http://dali.aibaodan.cn/Article/details/gt2yvuvdtcy.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.ppjwa.cn/Article/details/gt2hfeoxwnv.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.redwolf501.top/Article/details/gt2ghryisgj.html

[T51] Scala：Hello World
来源：http://dali.aibaodan.cn/Article/details/gt2ktsmczrm.html

println("Hello")
来源：http://dali.pengpengdd.cyou/Article/details/gt2jhbdlkud.html

[T52] Scala：变量
来源：http://dali.daria6918.cn/Article/details/gt2voauezyn.html

val a = 1;  var b = 2
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hurnbtgu.html

[T53] Scala：字符串插值
来源：http://dali.fzhhl.top/Article/details/gt2jufoveey.html

s"值: $b"
来源：http://dali.zhixingplan.top/Article/details/gt2krkkxhme.html

[T54] Scala：集合映射
来源：http://dali.cdnleiting.top/Article/details/gt2okgbqlgv.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.daria6918.cn/Article/details/gt2gtjosqhn.html

[T55] Scala：集合过滤
来源：http://dali.gotoacloud.top/Article/details/gt2qfuxqlro.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.tianlin.xyz/Article/details/gt2zsggyqyt.html

[T56] Scala：样例类
来源：http://dali.dianchejie.cn/Article/details/gt2shthisdf.html

case class User(name: String, age: Int)
来源：http://dali.aizwys.cn/Article/details/gt2ajsmolqh.html

[T57] Scala：模式匹配
来源：http://dali.xuanzx.com/Article/details/gt2clyadagr.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.birdmap.top/Article/details/gt2apbrdmzg.html

[T58] Scala：函数定义
来源：http://dali.gotoacloud.top/Article/details/gt2mcnktymf.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.yanxiufei.cn/Article/details/gt2qdpsuriz.html

[T59] Scala：循环
来源：http://dali.redwolf501.top/Article/details/gt2mvcdpige.html

for (i <- 1 to 10) println(i)
来源：http://dali.redwolf501.top/Article/details/gt2sceeruxp.html

[T60] Scala：折叠
来源：http://dali.zhiwuduotai.top/Article/details/gt2eymgzucj.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.hfpthk.cn/Article/details/gt2peuafdbo.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2wzvzqcnu.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.xziqi.cn/Article/details/gt2isaxstqg.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2wpztkbhw.html

[U01] Py：创建虚拟环境
来源：http://dali.xylfe.cn/Article/details/gt2izvpxuvs.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.tianlin.xyz/Article/details/gt2uygyeyds.html

[U02] Py：导出 / 安装依赖
来源：http://dali.cdnleiting.top/Article/details/gt2hvcwxstl.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.gogol.net.cn/Article/details/gt2bstydnde.html

[U03] Py：加载 .env 配置
来源：http://dali.gotoacloud.top/Article/details/gt2xbqbzusw.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.yueranfly.top/Article/details/gt2opdgfsnn.html

[U04] Py：变量调试打印
来源：http://dali.gzhubu.top/Article/details/gt2eovrrdtj.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.iojbl.cn/Article/details/gt2twrkvuek.html

[U05] Py：列表去重且保序
来源：http://dali.fengsongda.top/Article/details/gt2heozhinl.html

list(dict.fromkeys(arr))
来源：http://dali.pycfn.com/Article/details/gt2dpevrbcr.html

[U06] Py：合并两个字典
来源：http://dali.fengsongda.top/Article/details/gt2uzcsphku.html

{**a, **b}
来源：http://dali.zycfv.cn/Article/details/gt2evegsqpl.html

[U07] Py：反转字典键值
来源：http://dali.feifeiyinyue.top/Article/details/gt2khwxmecr.html

{v: k for k, v in d.items()}
来源：http://dali.zycfv.cn/Article/details/gt2kbiomvyt.html

[U08] Py：展平二维列表
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jablbfht.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2cvawrdyl.html


<!-- 参考信息 -->