代发 wailian999

openssl rand -hex 16
来源：http://dali.shanyushiyangtech.top/Article/details/gt2enfhmkvq.html

[R68] 计算文件校验值
来源：http://dali.nanxinkj.top/Article/details/gt2lxmwsvkv.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.nanxinkj.top/Article/details/gt2edigvwtb.html

[R69] 生成随机密码
来源：http://dali.pengpengdd.cyou/Article/details/gt2gbgksknp.html

head -c 16 /dev/urandom | base64
来源：http://dali.sweek.top/Article/details/gt2wytwsyrd.html

[R70] 时间戳与互转
来源：http://dali.jlsjyb.cn/Article/details/gt2imcjfruz.html

date +%s;  date -d @1700000000
来源：http://dali.haohaochexian.top/Article/details/gt2txnkopgd.html

[R71] 日期格式化
来源：http://dali.316326.xyz/Article/details/gt2wgxgyhot.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.cucudq.cn/Article/details/gt2qgblvwku.html

[R72] 等待端口就绪
来源：http://dali.yj202588.top/Article/details/gt2fnkmufdo.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.yj20258.top/Article/details/gt2fjrtprxd.html

[R73] 分割大日志
来源：http://dali.zhengqikj.top/Article/details/gt2alievlxy.html

split -l 1000 big.log part_
来源：http://dali.yonumen.top/Article/details/gt2njuresdy.html

[R74] 批量重命名
来源：http://dali.mhx1999.top/Article/details/gt2skaotpqf.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.yangfankeji.com/Article/details/gt2jefocths.html

[R75] 导出环境变量
来源：http://dali.jiagoushi.top/Article/details/gt2umteexxn.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.gzhubu.top/Article/details/gt2raaozbdd.html

[R76] 使用临时文件
来源：http://dali.shzxlz.cn/Article/details/gt2zboaxfzs.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2znowpcfl.html

[R77] 读取用户输入
来源：http://dali.zhiwuduotai.top/Article/details/gt2obvhevib.html

read -rp "请输入: " ans
来源：http://dali.aibaodan.cn/Article/details/gt2huqtedxr.html

[R78] 交互式菜单
来源：http://dali.zhongyouzk.top/Article/details/gt2dsqrjzzx.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jmociyqw.html

[R79] 解析命令行选项
来源：http://dali.dianchejie.cn/Article/details/gt2jxzuepkk.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2navyuzkd.html

[R80] 查看脚本执行耗时
来源：http://dali.ydzc1.top/Article/details/gt2hvskxbmo.html

time ./run.sh
来源：http://dali.mhx1999.top/Article/details/gt2skhhtaas.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2rsenldra.html

S. C / C++ 专题
来源：http://dali.daria6918.cn/Article/details/gt2nlimzmpv.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gt2koiquvog.html

[S01] C：Hello World
来源：http://dali.hnqzz.top/Article/details/gt2zoyskqvi.html

#include <stdio.h>
来源：http://dali.havefunace.top/Article/details/gt2qftpotcn.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.haohaochexian.top/Article/details/gt2teselzve.html

[S02] C：变量与格式化输出
来源：http://dali.dashuyun.cn/Article/details/gt2xspltvfj.html

int a = 10; printf("%d\n", a);
来源：http://dali.cheryme.top/Article/details/gt2rcggkcfn.html

[S03] C：读入整数
来源：http://dali.pengpengdd.cyou/Article/details/gt2rdznlhbr.html

int x; scanf("%d", &x);
来源：http://dali.xylfe.cn/Article/details/gt2jhksitic.html

[S04] C：字符串复制
来源：http://dali.shanyushiyangtech.top/Article/details/gt2chijbuut.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vanypkia.html

[S05] C：字符串长度
来源：http://dali.hysaishi.cn/Article/details/gt2sjrbqftl.html

strlen(s)
来源：http://dali.zycfv.cn/Article/details/gt2doicczax.html

[S06] C：字符串比较
来源：http://dali.daxiang520.top/Article/details/gt2xsmupxqw.html

strcmp(a, b) == 0
来源：http://dali.birdmap.top/Article/details/gt2nhyqikmx.html

[S07] C：数组遍历求和
来源：http://dali.sxryk.cn/Article/details/gt2rtanhlav.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.shangyingyoupin.top/Article/details/gt2okgzockt.html

[S08] C：动态内存分配与释放
来源：http://dali.jinqigfzy.top/Article/details/gt2osovsvkj.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.yonumen.top/Article/details/gt2gtoodwao.html

[S09] C：结构体定义与初始化
来源：http://dali.nwbrower.top/Article/details/gt2ksbidpsg.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.ehwqpu.com/Article/details/gt2mdhogfws.html

[S10] C：指针与解引用
来源：http://dali.fzhhl.top/Article/details/gt2pohhcmdg.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2ecxgdmoz.html

[S11] C：逐行读文件
来源：http://dali.feifeiyinyue.top/Article/details/gt2drybkamb.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.yongpay.top/Article/details/gt2plfjancf.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.yj20258.top/Article/details/gt2pizbqazi.html

fclose(f);
来源：http://dali.bjfxy.top/Article/details/gt2cuijjeey.html

[S12] C：写文件
来源：http://dali.jqgfzy.top/Article/details/gt2piwfmmri.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.daxiang520.top/Article/details/gt2octmkbxk.html

[S13] C：宏定义
来源：http://dali.andypj.xyz/Article/details/gt2ivlhrrjg.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.jiagoushi.top/Article/details/gt2qelduewv.html

[S14] C：枚举
来源：http://dali.hnqzz.top/Article/details/gt2wyvadznr.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.hnxiangtu.top/Article/details/gt2aazaivaa.html

[S15] C：类型转换
来源：http://dali.shangyingyoupin.top/Article/details/gt2wixrykvw.html

(double) a / b
来源：http://dali.zycfv.cn/Article/details/gt2owwqunpf.html

[S16] C：位操作置位
来源：http://dali.zhongyouzk.top/Article/details/gt2xzlswtdz.html

x |= (1 << 3);
来源：http://dali.shuidangran.top/Article/details/gt2xrhnzfvc.html

[S17] C：安全拼接字符串
来源：http://dali.pengpengdd.cyou/Article/details/gt2gdxhnmyx.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.gogol.net.cn/Article/details/gt2sctwdkqy.html

[S18] C：命令行参数
来源：http://dali.jianghu66.top/Article/details/gt2dcawdyxe.html

int main(int argc, char **argv)
来源：http://dali.gaohongyu789.top/Article/details/gt2cjgqmysp.html

[S19] C：快速排序
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dfarvjpf.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.chenjidiqi.icu/Article/details/gt2mlumusfz.html

[S20] C：二分查找
来源：http://dali.tianlin.xyz/Article/details/gt2jnuylejf.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.sxryk.cn/Article/details/gt2dkhfzxjp.html

[S21] C：字符类别判断
来源：http://dali.redwolf501.top/Article/details/gt2inmqsair.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cxupdiko.html

[S22] C：字符串转数字
来源：http://dali.cqqwz.cn/Article/details/gt2nguuqpla.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.chenlongwang.top/Article/details/gt2ptcdalif.html

[S23] C：随机数
来源：http://dali.vqdsnc.cn/Article/details/gt2mogozwov.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zdqjudy.top/Article/details/gt2dleuiwlq.html

[S24] C：获取本地时间
来源：http://dali.quarkkingdee.top/Article/details/gt2rhjzhevh.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.316326.xyz/Article/details/gt2yscmjhaa.html

[S25] C：内存拷贝
来源：http://dali.yj20258888.top/Article/details/gt2nfktnrry.html

memcpy(dst, src, n);
来源：http://dali.snrcjt.cn/Article/details/gt2eaujwfyw.html

[S26] C：内存清零
来源：http://dali.iojbl.cn/Article/details/gt2nibgiabo.html

memset(a, 0, sizeof a);
来源：http://dali.xinyue.icu/Article/details/gt2htbbzejq.html

[S27] C：定义常量
来源：http://dali.shangyingyoupin.top/Article/details/gt2mgxcseuf.html

const double PI = 3.14159;
来源：http://dali.316326.xyz/Article/details/gt2oqgwphqi.html

[S28] C：静态变量
来源：http://dali.hongshengwenyu.top/Article/details/gt2wwyhllrn.html

static int counter = 0;
来源：http://dali.xziqi.cn/Article/details/gt2ajwmojoh.html

[S29] C：变参函数
来源：http://dali.redwolf501.top/Article/details/gt2wghqrlnn.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhongyouzk.top/Article/details/gt2galdcxky.html

[S30] C：头文件保护
来源：http://dali.fzhhl.top/Article/details/gt2ytcoxuzh.html

#ifndef X_H
来源：http://dali.sysykeji.top/Article/details/gt2ifrdirnd.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2csvhywpz.html

#endif
来源：http://dali.wangshuangyany.cn/Article/details/gt2jqmxspwo.html

[S31] C++：Hello World
来源：http://dali.chenjidiqi.icu/Article/details/gt2fodufezn.html

#include <iostream>
来源：http://dali.mhx1999.top/Article/details/gt2ljfqmege.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.iojbl.cn/Article/details/gt2gyagyilg.html

[S32] C++：字符串
来源：http://dali.redwolf501.top/Article/details/gt2zcjanoxs.html

std::string s = "hi";  s += "!";
来源：http://dali.zhixingplan.top/Article/details/gt2dyfomnap.html

[S33] C++：vector 增删
来源：http://dali.svipenyu.cn/Article/details/gt2tfuxhkwc.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.bjfxy.top/Article/details/gt2tqijuvxc.html

[S34] C++：遍历 vector
来源：http://dali.zhengqikj.top/Article/details/gt2uleixvio.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.xuanzx.com/Article/details/gt2mvthlroe.html

[S35] C++：map
来源：http://dali.zhoulong.xyz/Article/details/gt2qpaaiehw.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.shzxlz.cn/Article/details/gt2bldjqvpn.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2qsckfatw.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.bjfxy.top/Article/details/gt2ylnihman.html

[S37] C++：set
来源：http://dali.jlsjyb.cn/Article/details/gt2bmwhnydr.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.gaohongyu789.top/Article/details/gt2wybceqxw.html

[S38] C++：排序
来源：http://dali.hnxiangtu.top/Article/details/gt2nbdmzcdk.html

std::sort(v.begin(), v.end());
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nwglqlzp.html

[S39] C++：自定义比较器排序
来源：http://dali.aibaodan.cn/Article/details/gt2emyifmxp.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2nxbmefgm.html

[S40] C++：查找元素
来源：http://dali.xziqi.cn/Article/details/gt2qiqzpagc.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.hongshengwenyu.top/Article/details/gt2gxgmztkz.html

[S41] C++：类与构造函数
来源：http://dali.cdnleiting.top/Article/details/gt2cgehfxqt.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.yanxiufei.cn/Article/details/gt2bgzanirn.html

[S42] C++：继承与虚函数
来源：http://dali.yuanzhike.top/Article/details/gt2fmhdlmlv.html

class B : public Base { public: void f() override {} };
来源：http://dali.nwbrower.top/Article/details/gt2gxsagseb.html

[S43] C++：智能指针
来源：http://dali.havefunace.top/Article/details/gt2lorqlilu.html

auto p = std::make_unique<int>(5);
来源：http://dali.andypj.xyz/Article/details/gt2etcsffuq.html

[S44] C++：引用传参
来源：http://dali.ybcxt.top/Article/details/gt2fitatlkz.html

void inc(int &x) { ++x; }
来源：http://dali.9152youxi.cn/Article/details/gt2hbrrnvuy.html

[S45] C++：lambda
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zcwbziyt.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.cheryme.top/Article/details/gt2aptbasrf.html

[S46] C++：函数模板
来源：http://dali.guannengcc.top/Article/details/gt2wxdkvmis.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2tudcbykn.html

[S47] C++：结构化绑定遍历
来源：http://dali.chenlongwang.top/Article/details/gt2jdhhqmap.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.iojbl.cn/Article/details/gt2slwxjghz.html

[S48] C++：逐行读文件
来源：http://dali.aibaodan.cn/Article/details/gt2dkauddum.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.cqqwz.cn/Article/details/gt2foxtzkbg.html

while (std::getline(in, line)) { }
来源：http://dali.hysaishi.cn/Article/details/gt2ripdhjoh.html

[S49] C++：写文件
来源：http://dali.sweek.top/Article/details/gt2wkqqgwuh.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2oimoqgbq.html

[S50] C++：格式化数字
来源：http://dali.zycfv.cn/Article/details/gt2bzneaoeg.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.jiagoushi.top/Article/details/gt2bfdwbsxi.html

[S51] C++：显式类型转换
来源：http://dali.ybcxt.top/Article/details/gt2xlkopiln.html

static_cast<double>(a) / b
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2iluskxel.html

[S52] C++：const 与 noexcept
来源：http://dali.redwolf501.top/Article/details/gt2iaqpapvs.html

int size() const noexcept { return n_; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2xudthryv.html

[S53] C++：移动语义
来源：http://dali.nwbrower.top/Article/details/gt2cofxfgfm.html

std::vector<int> w = std::move(v);
来源：http://dali.sweek.top/Article/details/gt2awjjuhij.html

[S54] C++：异常处理
来源：http://dali.sxryk.cn/Article/details/gt2fpxtfvxz.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.iojbl.cn/Article/details/gt2oqtvgnok.html

[S55] C++：结构化绑定
来源：http://dali.cdnleiting.top/Article/details/gt2dspfysfc.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.xylfe.cn/Article/details/gt2gglipndp.html

[S56] C++：optional
来源：http://dali.zhiwuduotai.top/Article/details/gt2fudclipo.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.gaohongyu789.top/Article/details/gt2cqmwasog.html

[S57] C++：编译期常量
来源：http://dali.hywenlv.cn/Article/details/gt2xttzjoux.html

constexpr int N = 10;
来源：http://dali.kuanghao11.cn/Article/details/gt2hhxmogvx.html

[S58] C++：命名空间
来源：http://dali.nwbrower.top/Article/details/gt2qjyidakv.html

namespace ns { int f() { return 1; } }
来源：http://dali.ehwqpu.com/Article/details/gt2hlhnjxcg.html

[S59] C++：静态断言
来源：http://dali.jlsjyb.cn/Article/details/gt2kymjkyov.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.birdmap.top/Article/details/gt2ypblvvuo.html

[S60] C++：遍历并删除元素
来源：http://dali.xziqi.cn/Article/details/gt2dmueukvm.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.yueranfly.top/Article/details/gt2ihtfiaum.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2lokbccoj.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.guowangkeji.top/Article/details/gt2mwkskdgy.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2ijyselyo.html

[T01] Kotlin：Hello World
来源：http://dali.havefunace.top/Article/details/gt2ztyeyoan.html

println("Hello")
来源：http://dali.gotoacloud.top/Article/details/gt2xwotlmvj.html

[T02] Kotlin：变量
来源：http://dali.sysykeji.top/Article/details/gt2gtzdguwm.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.ehwqpu.com/Article/details/gt2zjgwvxbu.html

[T03] Kotlin：字符串模板
来源：http://dali.aibaodan.cn/Article/details/gt2smdnkymd.html

"值: $b"
来源：http://dali.gogol.net.cn/Article/details/gt2xmxapttj.html

[T04] Kotlin：空安全
来源：http://dali.zdqjudy.top/Article/details/gt2tgvurxto.html

val n: String? = null;  n?.length
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nbrkfwhf.html

[T05] Kotlin：when 表达式
来源：http://dali.redwolf501.top/Article/details/gt2ibfecved.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.yuanzhike.top/Article/details/gt2qhbvgmph.html

[T06] Kotlin：集合映射
来源：http://dali.yangfankeji.com/Article/details/gt2mnodyuli.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.gogol.net.cn/Article/details/gt2bbnbfbvd.html

[T07] Kotlin：集合过滤
来源：http://dali.meibo888.top/Article/details/gt2tmprredh.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ifhudzsc.html

[T08] Kotlin：数据类
来源：http://dali.hysaishi.cn/Article/details/gt2ommtwxdw.html

data class User(val name: String, val age: Int)
来源：http://dali.smart0.xyz/Article/details/gt2hgkuqwsv.html

[T09] Kotlin：扩展函数
来源：http://dali.daria6918.cn/Article/details/gt2krjnmaif.html

fun String.exclaim() = this + "!"
来源：http://dali.xuetiantiany.cn/Article/details/gt2xvoegqxv.html

[T10] Kotlin：默认参数
来源：http://dali.shzxlz.cn/Article/details/gt2nonswbvw.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.feifeiyinyue.top/Article/details/gt2gzfybhmr.html

[T11] Kotlin：协程
来源：http://dali.ppjwa.cn/Article/details/gt2qpydwzll.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.c1oappe.top/Article/details/gt2itlvlnxk.html

[T12] Kotlin：解构声明
来源：http://dali.wangshuangyany.cn/Article/details/gt2cgqohevc.html

val (a, b) = Pair(1, 2)
来源：http://dali.haohaochexian.top/Article/details/gt2rnhshiru.html

[T13] Kotlin：只读 Map
来源：http://dali.kuanghao11.cn/Article/details/gt2hagfagxx.html

val m = mapOf("a" to 1)
来源：http://dali.meibo888.top/Article/details/gt2ybcsmfay.html

[T14] Kotlin：循环
来源：http://dali.tanke756.top/Article/details/gt2mhnnpssc.html

for (i in 1..10) println(i)
来源：http://dali.jiagoushi.top/Article/details/gt2eofskofr.html

[T15] Kotlin：接口
来源：http://dali.mhx1999.top/Article/details/gt2zyravcyg.html

interface Shape { fun area(): Double }
来源：http://dali.xuanzx.com/Article/details/gt2kmpifpsu.html

[T16] Swift：Hello World
来源：http://dali.xziqi.cn/Article/details/gt2gngmpwxg.html

print("Hello")
来源：http://dali.shzxlz.cn/Article/details/gt2focwfbqj.html

[T17] Swift：变量与常量
来源：http://dali.guannengcc.top/Article/details/gt2ytjpedri.html

var a = 1;  let b = 2
来源：http://dali.jinqigufen.top/Article/details/gt2fkggbfnx.html

[T18] Swift：字符串插值
来源：http://dali.svipenyu.cn/Article/details/gt2kudsdfph.html

"值: \(b)"
来源：http://dali.pycfn.com/Article/details/gt2berjazcb.html

[T19] Swift：可选绑定
来源：http://dali.zhixingplan.top/Article/details/gt2pnbjeyxf.html

if let n = opt { print(n) }
来源：http://dali.hongshengwenyu.top/Article/details/gt2kbvmfnee.html

[T20] Swift：数组操作
来源：http://dali.jyoumei.cn/Article/details/gt2jpeixriv.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhixingplan.top/Article/details/gt2zyzmmkvt.html

[T21] Swift：遍历
来源：http://dali.jlsjyb.cn/Article/details/gt2pauyfsbp.html

for x in a { print(x) }
来源：http://dali.ppjwa.cn/Article/details/gt2efhpyqob.html

[T22] Swift：字典
来源：http://dali.shzxlz.cn/Article/details/gt2bxhybggk.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhiwuduotai.top/Article/details/gt2quodyqgn.html

[T23] Swift：函数
来源：http://dali.cashguo.top/Article/details/gt2cebvfqjd.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.guannengcc.top/Article/details/gt2pfqywkop.html

[T24] Swift：闭包
来源：http://dali.xylfe.cn/Article/details/gt2rebglwek.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.redwolf501.top/Article/details/gt2nddvsbph.html

[T25] Swift：结构体
来源：http://dali.zhiwuduotai.top/Article/details/gt2hvbhegwm.html

struct P { var x: Int }
来源：http://dali.gzhubu.top/Article/details/gt2jldkxrla.html

[T26] Swift：类与重写
来源：http://dali.fengsongda.top/Article/details/gt2djpyyoqx.html

class A: Base { override func f() {} }
来源：http://dali.c1oappe.top/Article/details/gt2vujaehhg.html

[T27] Swift：错误处理
来源：http://dali.shzxlz.cn/Article/details/gt2lbrvflsu.html

do { try f() } catch { print(error) }
来源：http://dali.yangfankeji.com/Article/details/gt2qjobnrdm.html

[T28] Swift：枚举
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lbhgcudu.html

enum Color { case red, green }
来源：http://dali.shuidangran.top/Article/details/gt2sknwzula.html

[T29] Swift：guard 提前返回
来源：http://dali.yangfankeji.com/Article/details/gt2hafnsmec.html

guard let x = opt else { return }
来源：http://dali.xylfe.cn/Article/details/gt2wdhetcyo.html

[T30] Swift：协议
来源：http://dali.ppjwa.cn/Article/details/gt2zwtatled.html

protocol Shape { func area() -> Double }
来源：http://dali.nwbrower.top/Article/details/gt2nwnchzvq.html

[T31] Lua：Hello World
来源：http://dali.zhiwuduotai.top/Article/details/gt2tkzsnyai.html

print("Hello")
来源：http://dali.zycfv.cn/Article/details/gt2mpbcsyeh.html

[T32] Lua：局部变量
来源：http://dali.pengpengdd.cyou/Article/details/gt2bgsrjcsy.html

local a = 1
来源：http://dali.haohaochexian.top/Article/details/gt2tfrhflfp.html

[T33] Lua：表（数组）
来源：http://dali.gzhubu.top/Article/details/gt2raflekli.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.nanxuanxn.top/Article/details/gt2sixhksfw.html

[T34] Lua：遍历表
来源：http://dali.dashuyun.cn/Article/details/gt2toocbvbe.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.sweek.top/Article/details/gt2ojhatydl.html

[T35] Lua：字典表
来源：http://dali.snrcjt.cn/Article/details/gt2ztqqlthl.html

local d = { a = 1 };  d.b = 2
来源：http://dali.yonumen.top/Article/details/gt2szedyzed.html

[T36] Lua：函数
来源：http://dali.yonumen.top/Article/details/gt2tsvbeoaw.html

function add(a, b) return a + b end
来源：http://dali.shanyushiyangtech.top/Article/details/gt2valkfxcg.html

[T37] Lua：字符串拼接
来源：http://dali.jqgufenzy.top/Article/details/gt2ktrowfid.html

"a" .. "b"
来源：http://dali.shzxlz.cn/Article/details/gt2rylbcgqn.html

[T38] Lua：条件
来源：http://dali.shangyingyoupin.top/Article/details/gt2yjlgdvsy.html

if x > 0 then print("正") end
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2iealscjx.html

[T39] Lua：模式匹配
来源：http://dali.dashuyun.cn/Article/details/gt2ctxxnspx.html

string.find(s, "%d+")
来源：http://dali.sxryk.cn/Article/details/gt2cxirzbrl.html

[T40] Lua：元表
来源：http://dali.daxiang520.top/Article/details/gt2jnehcwoq.html

setmetatable({}, { __index = base })
来源：http://dali.hnxiangtu.top/Article/details/gt2bmufrgfy.html

[T41] Perl：Hello World
来源：http://dali.sweek.top/Article/details/gt2xntwihif.html

print "Hello\n";
来源：http://dali.hfpthk.cn/Article/details/gt2dckevjab.html

[T42] Perl：变量类型
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mkorveap.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.sufxvd.cn/Article/details/gt2cmgekyxi.html

[T43] Perl：字符串插值
来源：http://dali.wangdashe.top/Article/details/gt2ateatpfs.html

"值: $a"
来源：http://dali.guowangkeji.top/Article/details/gt2iqnesuqf.html

[T44] Perl：条件
来源：http://dali.guannengcc.top/Article/details/gt2mktududb.html

if ($a > 0) { print "正"; }
来源：http://dali.gogol.net.cn/Article/details/gt2eudzpwht.html

[T45] Perl：数组遍历
来源：http://dali.yj202588.top/Article/details/gt2nbhoufzm.html

for my $x (@arr) { print $x; }
来源：http://dali.tianlin.xyz/Article/details/gt2yeydpwuw.html

[T46] Perl：哈希操作
来源：http://dali.0kj1m.cn/Article/details/gt2yydmwrgc.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.yj202588.top/Article/details/gt2nsinjain.html

[T47] Perl：正则捕获
来源：http://dali.nwbrower.top/Article/details/gt2wirakwcv.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.shuidangran.top/Article/details/gt2brivclde.html

[T48] Perl：正则替换
来源：http://dali.zhengqikj.top/Article/details/gt2dukyrxkv.html

$s =~ s/old/new/g;
来源：http://dali.9152youxi.cn/Article/details/gt2ltxbibwt.html

[T49] Perl：函数
来源：http://dali.dashuyun.cn/Article/details/gt2svaogtwb.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.jqgufenzy.top/Article/details/gt2azkydwbe.html

[T50] Perl：逐行读文件
来源：http://dali.svipenyu.cn/Article/details/gt2nzsfrvgn.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.ppjwa.cn/Article/details/gt2rglcrmkg.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.gogol.net.cn/Article/details/gt2cfernhtl.html

[T51] Scala：Hello World
来源：http://dali.yuxming.cn/Article/details/gt2ivhdxoji.html

println("Hello")
来源：http://dali.aibaodan.cn/Article/details/gt2rsiymuvy.html

[T52] Scala：变量
来源：http://dali.dianchejie.cn/Article/details/gt2wlnxszgh.html

val a = 1;  var b = 2
来源：http://dali.fzhhl.top/Article/details/gt2gjwyedzr.html

[T53] Scala：字符串插值
来源：http://dali.xuetiantiany.cn/Article/details/gt2cqaannos.html

s"值: $b"
来源：http://dali.aizwys.cn/Article/details/gt2lxlqwjfm.html

[T54] Scala：集合映射
来源：http://dali.kuanghao11.cn/Article/details/gt2vosbezpn.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.yangfankeji.com/Article/details/gt2awnxiybs.html

[T55] Scala：集合过滤
来源：http://dali.zdqjudy.top/Article/details/gt2edwzuimm.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.chenlongwang.top/Article/details/gt2wgoowzwj.html

[T56] Scala：样例类
来源：http://dali.yuxming.cn/Article/details/gt2upkodqjy.html

case class User(name: String, age: Int)
来源：http://dali.feifeiyinyue.top/Article/details/gt2owguqdcd.html

[T57] Scala：模式匹配
来源：http://dali.hywenlv.cn/Article/details/gt2dgirrggk.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.ivvv.top/Article/details/gt2ryqhfehv.html

[T58] Scala：函数定义
来源：http://dali.haohaochexian.top/Article/details/gt2kwumyagc.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.0kj1m.cn/Article/details/gt2middpnag.html

[T59] Scala：循环
来源：http://dali.hywenlv.cn/Article/details/gt2sthkxloj.html

for (i <- 1 to 10) println(i)
来源：http://dali.hnqzz.top/Article/details/gt2sxeyredt.html

[T60] Scala：折叠
来源：http://dali.daria6918.cn/Article/details/gt2cuzuskoj.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.yj20258888.top/Article/details/gt2nsokicuy.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gt2vkpjbvdq.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.yanxiufei.cn/Article/details/gt2stytjyvo.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2sjnqxnjy.html

[U01] Py：创建虚拟环境
来源：http://dali.nanxuanxn.top/Article/details/gt2ncokfshn.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhongyouzk.top/Article/details/gt2qhywwxof.html

[U02] Py：导出 / 安装依赖
来源：http://dali.sweek.top/Article/details/gt2lvnqpiyh.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.gaohongyu789.top/Article/details/gt2psogbzsx.html

[U03] Py：加载 .env 配置
来源：http://dali.iojbl.cn/Article/details/gt2tnbtdkyl.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.yangfankeji.com/Article/details/gt2csbagvny.html

[U04] Py：变量调试打印
来源：http://dali.smart0.xyz/Article/details/gt2gemnwodt.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.pycfn.com/Article/details/gt2bhzwbknu.html

[U05] Py：列表去重且保序
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wnxfpsod.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2kdczlhwk.html

[U06] Py：合并两个字典
来源：http://dali.xylfe.cn/Article/details/gt2qamevxal.html

{**a, **b}
来源：http://dali.jinqigufen.top/Article/details/gt2wzrpwlrl.html

[U07] Py：反转字典键值
来源：http://dali.hnqzz.top/Article/details/gt2ecmntraw.html

{v: k for k, v in d.items()}
来源：http://dali.zhiwuduotai.top/Article/details/gt2ivwakkzy.html

[U08] Py：展平二维列表
来源：http://dali.redwolf501.top/Article/details/gt2cnxfrywp.html

[y for x in nested for y in x]
来源：http://dali.yj20258.top/Article/details/gt2agegljrd.html


<!-- 参考信息 -->