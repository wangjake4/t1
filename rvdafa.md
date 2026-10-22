代发 wailian999

head -c 16 /dev/urandom | base64
来源：http://dali.zycfv.cn/Article/details/gt2nwlcexbd.html

[R70] 时间戳与互转
来源：http://dali.nanxinkj.top/Article/details/gt2fzjolhhh.html

date +%s;  date -d @1700000000
来源：http://dali.mhx1999.top/Article/details/gt2flibqjhf.html

[R71] 日期格式化
来源：http://dali.316326.xyz/Article/details/gt2kkbkmrzb.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.yj202588.top/Article/details/gt2tjwsowug.html

[R72] 等待端口就绪
来源：http://dali.wangshuangyany.cn/Article/details/gt2iwbvbhdy.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.ydzc1.top/Article/details/gt2cuysuftm.html

[R73] 分割大日志
来源：http://dali.yj20258.top/Article/details/gt2jhlxnbdk.html

split -l 1000 big.log part_
来源：http://dali.ybcxt.top/Article/details/gt2qsyepzlw.html

[R74] 批量重命名
来源：http://dali.yangfankeji.com/Article/details/gt2fiyojjze.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.jianghu66.top/Article/details/gt2zkrsdokw.html

[R75] 导出环境变量
来源：http://dali.yj202588.top/Article/details/gt2cwqnlsur.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.aibaodan.cn/Article/details/gt2uhrvmavk.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vezvwqmo.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.feifeiyinyue.top/Article/details/gt2ryrfkayd.html

[R77] 读取用户输入
来源：http://dali.zdqjudy.top/Article/details/gt2fhfvsdwt.html

read -rp "请输入: " ans
来源：http://dali.nanxuanxn.top/Article/details/gt2mkzezxlp.html

[R78] 交互式菜单
来源：http://dali.gzhubu.top/Article/details/gt2wydeeeet.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhongyouzk.top/Article/details/gt2driqrhsv.html

[R79] 解析命令行选项
来源：http://dali.yanxiufei.cn/Article/details/gt2zgejisek.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.xylfe.cn/Article/details/gt2phckozbm.html

[R80] 查看脚本执行耗时
来源：http://dali.jianghu66.top/Article/details/gt2wixvrgto.html

time ./run.sh
来源：http://dali.iojbl.cn/Article/details/gt2yvsmzfaa.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2gesosurq.html

S. C / C++ 专题
来源：http://dali.meibo888.top/Article/details/gt2imkyuvsh.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2xafhciwc.html

[S01] C：Hello World
来源：http://dali.wangshuangyany.cn/Article/details/gt2emcseawy.html

#include <stdio.h>
来源：http://dali.sxryk.cn/Article/details/gt2tcqiglwq.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.fengsongda.top/Article/details/gt2bokbfqhz.html

[S02] C：变量与格式化输出
来源：http://dali.jianghu66.top/Article/details/gt2jifjqjjy.html

int a = 10; printf("%d\n", a);
来源：http://dali.jqgufenzy.top/Article/details/gt2twlnnuhq.html

[S03] C：读入整数
来源：http://dali.hywenlv.cn/Article/details/gt2zozaylyf.html

int x; scanf("%d", &x);
来源：http://dali.yanxiufei.cn/Article/details/gt2lkrlutsy.html

[S04] C：字符串复制
来源：http://dali.jlsjyb.cn/Article/details/gt2ushxaafs.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.c1oappe.top/Article/details/gt2enezxdxc.html

[S05] C：字符串长度
来源：http://dali.hnxiangtu.top/Article/details/gt2kdfunobu.html

strlen(s)
来源：http://dali.dianchejie.cn/Article/details/gt2bneacofo.html

[S06] C：字符串比较
来源：http://dali.yonumen.top/Article/details/gt2vbfhnlpv.html

strcmp(a, b) == 0
来源：http://dali.yj20258.top/Article/details/gt2wffhiqsx.html

[S07] C：数组遍历求和
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mpgphfyw.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.wangdashe.top/Article/details/gt2rzicqaod.html

[S08] C：动态内存分配与释放
来源：http://dali.yueranfly.top/Article/details/gt2mqjntybf.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.hongshengwenyu.top/Article/details/gt2wxhbiwxs.html

[S09] C：结构体定义与初始化
来源：http://dali.tian-w.cn/Article/details/gt2exqffzrm.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.iojbl.cn/Article/details/gt2thzjmaol.html

[S10] C：指针与解引用
来源：http://dali.c1oappe.top/Article/details/gt2ojhyowib.html

int *p = &a;  *p = 5;
来源：http://dali.hongshengwenyu.top/Article/details/gt2ljvclnvi.html

[S11] C：逐行读文件
来源：http://dali.cheryme.top/Article/details/gt2ohrgmutg.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.cdnleiting.top/Article/details/gt2lpbriqbz.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.gzhubu.top/Article/details/gt2nmkrtxxk.html

fclose(f);
来源：http://dali.gzhubu.top/Article/details/gt2cglhzfqd.html

[S12] C：写文件
来源：http://dali.ivvv.top/Article/details/gt2hbekmjvu.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.sweek.top/Article/details/gt2texjqews.html

[S13] C：宏定义
来源：http://dali.havefunace.top/Article/details/gt2epgkyymy.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zdqjudy.top/Article/details/gt2upockysy.html

[S14] C：枚举
来源：http://dali.cucudq.cn/Article/details/gt2debwzpbt.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.smart0.xyz/Article/details/gt2uveflkgt.html

[S15] C：类型转换
来源：http://dali.tanke756.top/Article/details/gt2eyzzpqjj.html

(double) a / b
来源：http://dali.jiagoushi.top/Article/details/gt2gvbduyav.html

[S16] C：位操作置位
来源：http://dali.ybcxt.top/Article/details/gt2tevfcete.html

x |= (1 << 3);
来源：http://dali.smart0.xyz/Article/details/gt2mnjbvlns.html

[S17] C：安全拼接字符串
来源：http://dali.birdmap.top/Article/details/gt2cfhgcrip.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.9152youxi.cn/Article/details/gt2egehjlun.html

[S18] C：命令行参数
来源：http://dali.ybcxt.top/Article/details/gt2vodjyruv.html

int main(int argc, char **argv)
来源：http://dali.0kj1m.cn/Article/details/gt2iuulvjgy.html

[S19] C：快速排序
来源：http://dali.zhiwuduotai.top/Article/details/gt2hjrausmj.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.daxiang520.top/Article/details/gt2vwsslwpd.html

[S20] C：二分查找
来源：http://dali.ehwqpu.com/Article/details/gt2rwotpxlv.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.tian-w.cn/Article/details/gt2fcybyimp.html

[S21] C：字符类别判断
来源：http://dali.chenzaomai.com/Article/details/gt2icylmmwk.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.cucudq.cn/Article/details/gt2uiagddso.html

[S22] C：字符串转数字
来源：http://dali.jqgfzy.top/Article/details/gt2nwerihnp.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vkwzuhoc.html

[S23] C：随机数
来源：http://dali.jqgfzy.top/Article/details/gt2biabbovs.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.tanke756.top/Article/details/gt2sypmvbjq.html

[S24] C：获取本地时间
来源：http://dali.daria6918.cn/Article/details/gt2lmkeprxr.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhoulong.xyz/Article/details/gt2mhypnvrj.html

[S25] C：内存拷贝
来源：http://dali.hfpthk.cn/Article/details/gt2wajzaoyp.html

memcpy(dst, src, n);
来源：http://dali.chenzaomai.com/Article/details/gt2shtclvev.html

[S26] C：内存清零
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xfvylqlw.html

memset(a, 0, sizeof a);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2smborggn.html

[S27] C：定义常量
来源：http://dali.hongshengwenyu.top/Article/details/gt2ycbpuczk.html

const double PI = 3.14159;
来源：http://dali.xylfe.cn/Article/details/gt2rrgdgsmb.html

[S28] C：静态变量
来源：http://dali.ivvv.top/Article/details/gt2qxabgzaf.html

static int counter = 0;
来源：http://dali.yonumen.top/Article/details/gt2nxoxjjlt.html

[S29] C：变参函数
来源：http://dali.sxryk.cn/Article/details/gt2avxbbbhu.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.sufxvd.cn/Article/details/gt2fxbxjcij.html

[S30] C：头文件保护
来源：http://dali.yuxming.cn/Article/details/gt2dbcugeer.html

#ifndef X_H
来源：http://dali.hongshengwenyu.top/Article/details/gt2wiprxwil.html

#define X_H
来源：http://dali.jinghuilouyu.cn/Article/details/gt2skzmgnea.html

#endif
来源：http://dali.jiagoushi.top/Article/details/gt2otmwqebq.html

[S31] C++：Hello World
来源：http://dali.c1oappe.top/Article/details/gt2jchbttvw.html

#include <iostream>
来源：http://dali.shangyingyoupin.top/Article/details/gt2wycovhiv.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.yj20258.top/Article/details/gt2mijaihzt.html

[S32] C++：字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kkbgnbkn.html

std::string s = "hi";  s += "!";
来源：http://dali.9152youxi.cn/Article/details/gt2hojyuahd.html

[S33] C++：vector 增删
来源：http://dali.jianghu66.top/Article/details/gt2ddshwqeh.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.pengpengdd.cyou/Article/details/gt2xdhoubmq.html

[S34] C++：遍历 vector
来源：http://dali.sxryk.cn/Article/details/gt2diifpetd.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.gaohongyu789.top/Article/details/gt2nlhcxsmd.html

[S35] C++：map
来源：http://dali.nanxuanxn.top/Article/details/gt2nmyrqxgv.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jinqigfzy.top/Article/details/gt2bcgefzjn.html

[S36] C++：unordered_map
来源：http://dali.ydzc1.top/Article/details/gt2mbpduxrb.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.meibo888.top/Article/details/gt2drqljysp.html

[S37] C++：set
来源：http://dali.xziqi.cn/Article/details/gt2dsvbunax.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.cheryme.top/Article/details/gt2brbwaktg.html

[S38] C++：排序
来源：http://dali.jqgfzy.top/Article/details/gt2eznempsr.html

std::sort(v.begin(), v.end());
来源：http://dali.jiagoushi.top/Article/details/gt2cttdpqya.html

[S39] C++：自定义比较器排序
来源：http://dali.vqdsnc.cn/Article/details/gt2lpgfldas.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.feifeiyinyue.top/Article/details/gt2wssxdqjd.html

[S40] C++：查找元素
来源：http://dali.jiagoushi.top/Article/details/gt2nmjthklk.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.nwbrower.top/Article/details/gt2nmxswlds.html

[S41] C++：类与构造函数
来源：http://dali.jiagoushi.top/Article/details/gt2xogknclh.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.wangshuangyany.cn/Article/details/gt2qpypomlh.html

[S42] C++：继承与虚函数
来源：http://dali.hongshengwenyu.top/Article/details/gt2atludeon.html

class B : public Base { public: void f() override {} };
来源：http://dali.hysaishi.cn/Article/details/gt2wrwztyii.html

[S43] C++：智能指针
来源：http://dali.redwolf501.top/Article/details/gt2ybteslhi.html

auto p = std::make_unique<int>(5);
来源：http://dali.sweek.top/Article/details/gt2ijdtftkd.html

[S44] C++：引用传参
来源：http://dali.ydzc1.top/Article/details/gt2gilfjcre.html

void inc(int &x) { ++x; }
来源：http://dali.chenzaomai.com/Article/details/gt2nhwmrtjl.html

[S45] C++：lambda
来源：http://dali.daria6918.cn/Article/details/gt2datlpgma.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.yongpay.top/Article/details/gt2eoehjedu.html

[S46] C++：函数模板
来源：http://dali.feifeiyinyue.top/Article/details/gt2fjluoexe.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhoulong.xyz/Article/details/gt2jbaviwdu.html

[S47] C++：结构化绑定遍历
来源：http://dali.fzhhl.top/Article/details/gt2hpsvnwpt.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.yanxiufei.cn/Article/details/gt2ihkjfwdi.html

[S48] C++：逐行读文件
来源：http://dali.aizwys.cn/Article/details/gt2plgzjcql.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.sweek.top/Article/details/gt2tasirgfv.html

while (std::getline(in, line)) { }
来源：http://dali.havefunace.top/Article/details/gt2dtgpfmcj.html

[S49] C++：写文件
来源：http://dali.yuanzhike.top/Article/details/gt2wplgelfc.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.yuxming.cn/Article/details/gt2wtlbmllb.html

[S50] C++：格式化数字
来源：http://dali.cdnleiting.top/Article/details/gt2lwfjntpl.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.xuanzx.com/Article/details/gt2dnumhhpw.html

[S51] C++：显式类型转换
来源：http://dali.sxryk.cn/Article/details/gt2zgelzdhy.html

static_cast<double>(a) / b
来源：http://dali.hongshengwenyu.top/Article/details/gt2pirbqhcr.html

[S52] C++：const 与 noexcept
来源：http://dali.cdnleiting.top/Article/details/gt2mnkwulil.html

int size() const noexcept { return n_; }
来源：http://dali.meibo888.top/Article/details/gt2oilovylm.html

[S53] C++：移动语义
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xnjlsnrj.html

std::vector<int> w = std::move(v);
来源：http://dali.jinqigufen.top/Article/details/gt2epwnvevg.html

[S54] C++：异常处理
来源：http://dali.birdmap.top/Article/details/gt2nqbciwya.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.bjfxy.top/Article/details/gt2ncqbnkxv.html

[S55] C++：结构化绑定
来源：http://dali.9152youxi.cn/Article/details/gt2qwlyukvt.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.fzhhl.top/Article/details/gt2rbkxxjoy.html

[S56] C++：optional
来源：http://dali.zhoulong.xyz/Article/details/gt2oumpagmp.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.sufxvd.cn/Article/details/gt2knsruiem.html

[S57] C++：编译期常量
来源：http://dali.chenlongwang.top/Article/details/gt2gxnfzklx.html

constexpr int N = 10;
来源：http://dali.guowangkeji.top/Article/details/gt2kgsviqzo.html

[S58] C++：命名空间
来源：http://dali.iojbl.cn/Article/details/gt2mtwpiqvi.html

namespace ns { int f() { return 1; } }
来源：http://dali.nanxinkj.top/Article/details/gt2mdtrswux.html

[S59] C++：静态断言
来源：http://dali.iojbl.cn/Article/details/gt2krczywyq.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.cheryme.top/Article/details/gt2srucgdlz.html

[S60] C++：遍历并删除元素
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gqyjhgqj.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zdqjudy.top/Article/details/gt2iiaytonb.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2wuimrrqm.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yuxming.cn/Article/details/gt2eosgfoai.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2eyqoranp.html

[T01] Kotlin：Hello World
来源：http://dali.jyoumei.cn/Article/details/gt2hfxrtlfp.html

println("Hello")
来源：http://dali.ydzc1.top/Article/details/gt2jwsshibh.html

[T02] Kotlin：变量
来源：http://dali.nanxinkj.top/Article/details/gt2jhouvdmx.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.ivvv.top/Article/details/gt2dhbvppsw.html

[T03] Kotlin：字符串模板
来源：http://dali.xylfe.cn/Article/details/gt2zuwkwqoo.html

"值: $b"
来源：http://dali.yj20258888.top/Article/details/gt2zyjmvapo.html

[T04] Kotlin：空安全
来源：http://dali.shuidangran.top/Article/details/gt2vhjiynyu.html

val n: String? = null;  n?.length
来源：http://dali.quarkkingdee.top/Article/details/gt2gerwunez.html

[T05] Kotlin：when 表达式
来源：http://dali.sufxvd.cn/Article/details/gt2upqgyfrc.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.sxryk.cn/Article/details/gt2mptofzpu.html

[T06] Kotlin：集合映射
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cjxijmok.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.ivvv.top/Article/details/gt2jldvtnfb.html

[T07] Kotlin：集合过滤
来源：http://dali.gaohongyu789.top/Article/details/gt2glnboqzo.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.mhx1999.top/Article/details/gt2lzfproiq.html

[T08] Kotlin：数据类
来源：http://dali.xylfe.cn/Article/details/gt2xvxxdsyk.html

data class User(val name: String, val age: Int)
来源：http://dali.snrcjt.cn/Article/details/gt2liycvqxo.html

[T09] Kotlin：扩展函数
来源：http://dali.ehwqpu.com/Article/details/gt2zjglssjm.html

fun String.exclaim() = this + "!"
来源：http://dali.feifeiyinyue.top/Article/details/gt2bymkgwtm.html

[T10] Kotlin：默认参数
来源：http://dali.wangdashe.top/Article/details/gt2ivxcwrff.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.tian-w.cn/Article/details/gt2japivedy.html

[T11] Kotlin：协程
来源：http://dali.zhiwuduotai.top/Article/details/gt2angcgsjr.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.iojbl.cn/Article/details/gt2rtvkjocp.html

[T12] Kotlin：解构声明
来源：http://dali.chenjidiqi.icu/Article/details/gt2vquyszvt.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhoulong.xyz/Article/details/gt2uehbbrwh.html

[T13] Kotlin：只读 Map
来源：http://dali.xylfe.cn/Article/details/gt2hlsryxva.html

val m = mapOf("a" to 1)
来源：http://dali.jinqigufen.top/Article/details/gt2luucybrr.html

[T14] Kotlin：循环
来源：http://dali.mhx1999.top/Article/details/gt2qndkwagu.html

for (i in 1..10) println(i)
来源：http://dali.gaohongyu789.top/Article/details/gt2nbdwztcy.html

[T15] Kotlin：接口
来源：http://dali.zhiwuduotai.top/Article/details/gt2gcyzuhbl.html

interface Shape { fun area(): Double }
来源：http://dali.zhixingplan.top/Article/details/gt2xhsjbmhf.html

[T16] Swift：Hello World
来源：http://dali.meibo888.top/Article/details/gt2rccoirin.html

print("Hello")
来源：http://dali.quarkkingdee.top/Article/details/gt2tjricrag.html

[T17] Swift：变量与常量
来源：http://dali.tianlin.xyz/Article/details/gt2ufqpjbvb.html

var a = 1;  let b = 2
来源：http://dali.zhiwuduotai.top/Article/details/gt2pwpuhgzc.html

[T18] Swift：字符串插值
来源：http://dali.cdnleiting.top/Article/details/gt2rggltnil.html

"值: \(b)"
来源：http://dali.yuxming.cn/Article/details/gt2vlvfwgkl.html

[T19] Swift：可选绑定
来源：http://dali.gaohongyu789.top/Article/details/gt2znxvzkdz.html

if let n = opt { print(n) }
来源：http://dali.shangyingyoupin.top/Article/details/gt2jtoiefjq.html

[T20] Swift：数组操作
来源：http://dali.daria6918.cn/Article/details/gt2wvkkmqkd.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.yvedp.cn/Article/details/gt2hnhubmzd.html

[T21] Swift：遍历
来源：http://dali.yuxming.cn/Article/details/gt2fjnznwzu.html

for x in a { print(x) }
来源：http://dali.gzhubu.top/Article/details/gt2hdosardt.html

[T22] Swift：字典
来源：http://dali.hnqzz.top/Article/details/gt2gbmahlfq.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.sweek.top/Article/details/gt2hairliou.html

[T23] Swift：函数
来源：http://dali.cqqwz.cn/Article/details/gt2wbibcakb.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.yj20258.top/Article/details/gt2qbofjlxn.html

[T24] Swift：闭包
来源：http://dali.ybcxt.top/Article/details/gt2grluodnp.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.yvedp.cn/Article/details/gt2elxnqmox.html

[T25] Swift：结构体
来源：http://dali.jqgfzy.top/Article/details/gt2ohmxcbpx.html

struct P { var x: Int }
来源：http://dali.zhoulong.xyz/Article/details/gt2cwmrxesk.html

[T26] Swift：类与重写
来源：http://dali.hywenlv.cn/Article/details/gt2knkjbqgt.html

class A: Base { override func f() {} }
来源：http://dali.aibaodan.cn/Article/details/gt2tszjecfw.html

[T27] Swift：错误处理
来源：http://dali.yj20258888.top/Article/details/gt2wrdpmglm.html

do { try f() } catch { print(error) }
来源：http://dali.ydzc1.top/Article/details/gt2xouvrmzy.html

[T28] Swift：枚举
来源：http://dali.birdmap.top/Article/details/gt2tdwmwsuc.html

enum Color { case red, green }
来源：http://dali.pycfn.com/Article/details/gt2bcieqdrp.html

[T29] Swift：guard 提前返回
来源：http://dali.xuetiantiany.cn/Article/details/gt2guwjncyi.html

guard let x = opt else { return }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yrcaknxx.html

[T30] Swift：协议
来源：http://dali.andypj.xyz/Article/details/gt2qxfwxqbm.html

protocol Shape { func area() -> Double }
来源：http://dali.yvedp.cn/Article/details/gt2ufszsnsy.html

[T31] Lua：Hello World
来源：http://dali.tianlin.xyz/Article/details/gt2iriplras.html

print("Hello")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kivzadlu.html

[T32] Lua：局部变量
来源：http://dali.haohaochexian.top/Article/details/gt2gzxyhczn.html

local a = 1
来源：http://dali.hongshengwenyu.top/Article/details/gt2rtgcumzo.html

[T33] Lua：表（数组）
来源：http://dali.haohaochexian.top/Article/details/gt2remphlok.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.yj202588.top/Article/details/gt2vzdyzgnh.html

[T34] Lua：遍历表
来源：http://dali.zhongyouzk.top/Article/details/gt2rppbhwoa.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.jlsjyb.cn/Article/details/gt2rlvlfuyk.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2cyljyzfd.html

local d = { a = 1 };  d.b = 2
来源：http://dali.jqgfzy.top/Article/details/gt2zsvinjne.html

[T36] Lua：函数
来源：http://dali.wangdashe.top/Article/details/gt2niwgfpvf.html

function add(a, b) return a + b end
来源：http://dali.jqgfzy.top/Article/details/gt2nnfeetoz.html

[T37] Lua：字符串拼接
来源：http://dali.hfpthk.cn/Article/details/gt2qkjrdkgc.html

"a" .. "b"
来源：http://dali.bjfxy.top/Article/details/gt2whtvjuzy.html

[T38] Lua：条件
来源：http://dali.yueranfly.top/Article/details/gt2vakjdmnl.html

if x > 0 then print("正") end
来源：http://dali.havefunace.top/Article/details/gt2mbbkgflt.html

[T39] Lua：模式匹配
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lznulaor.html

string.find(s, "%d+")
来源：http://dali.yvedp.cn/Article/details/gt2fyxtwmre.html

[T40] Lua：元表
来源：http://dali.jiagoushi.top/Article/details/gt2oowsidgc.html

setmetatable({}, { __index = base })
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uohxboif.html

[T41] Perl：Hello World
来源：http://dali.cucudq.cn/Article/details/gt2qktqwwls.html

print "Hello\n";
来源：http://dali.gaohongyu789.top/Article/details/gt2gaodeeme.html

[T42] Perl：变量类型
来源：http://dali.dashuyun.cn/Article/details/gt2kuxefehr.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhixingplan.top/Article/details/gt2kobxwzjv.html

[T43] Perl：字符串插值
来源：http://dali.zycfv.cn/Article/details/gt2aczdiigo.html

"值: $a"
来源：http://dali.meibo888.top/Article/details/gt2vpodhhau.html

[T44] Perl：条件
来源：http://dali.sxryk.cn/Article/details/gt2zfkzlrub.html

if ($a > 0) { print "正"; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2dliatzmj.html

[T45] Perl：数组遍历
来源：http://dali.chenzaomai.com/Article/details/gt2wzywhlvs.html

for my $x (@arr) { print $x; }
来源：http://dali.redwolf501.top/Article/details/gt2iybqbosw.html

[T46] Perl：哈希操作
来源：http://dali.chenjidiqi.icu/Article/details/gt2dnxqxeac.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.aibaodan.cn/Article/details/gt2clzsqtju.html

[T47] Perl：正则捕获
来源：http://dali.sxryk.cn/Article/details/gt2nqghmbbe.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2yxvexwas.html

[T48] Perl：正则替换
来源：http://dali.yj20258.top/Article/details/gt2xfuanmfs.html

$s =~ s/old/new/g;
来源：http://dali.guannengcc.top/Article/details/gt2nlvhlhfd.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fkaqhozb.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.haohaochexian.top/Article/details/gt2hxhljtvu.html

[T50] Perl：逐行读文件
来源：http://dali.yj20258.top/Article/details/gt2dblmfvho.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.gogol.net.cn/Article/details/gt2qxgxncdw.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.tian-w.cn/Article/details/gt2rrghkyzo.html

[T51] Scala：Hello World
来源：http://dali.jianghu66.top/Article/details/gt2dlhwjeum.html

println("Hello")
来源：http://dali.hnxiangtu.top/Article/details/gt2xpkjegem.html

[T52] Scala：变量
来源：http://dali.meibo888.top/Article/details/gt2vutvfbsj.html

val a = 1;  var b = 2
来源：http://dali.tanke756.top/Article/details/gt2mampmrom.html

[T53] Scala：字符串插值
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wkauqclk.html

s"值: $b"
来源：http://dali.iojbl.cn/Article/details/gt2zvwuarwz.html

[T54] Scala：集合映射
来源：http://dali.pycfn.com/Article/details/gt2sbhtxzro.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cvlzrsyb.html

[T55] Scala：集合过滤
来源：http://dali.xinyue.icu/Article/details/gt2stdpdlyr.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.gotoacloud.top/Article/details/gt2gfybuima.html

[T56] Scala：样例类
来源：http://dali.wangdashe.top/Article/details/gt2aescrsel.html

case class User(name: String, age: Int)
来源：http://dali.snrcjt.cn/Article/details/gt2eqwpiidf.html

[T57] Scala：模式匹配
来源：http://dali.ybcxt.top/Article/details/gt2pcgrzcjk.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.pycfn.com/Article/details/gt2yuocrjbg.html

[T58] Scala：函数定义
来源：http://dali.gaohongyu789.top/Article/details/gt2dzschrdc.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.316326.xyz/Article/details/gt2pbzqjyuk.html

[T59] Scala：循环
来源：http://dali.daxiang520.top/Article/details/gt2cswbhwlu.html

for (i <- 1 to 10) println(i)
来源：http://dali.hfpthk.cn/Article/details/gt2jorvfvkv.html

[T60] Scala：折叠
来源：http://dali.cashguo.top/Article/details/gt2fxzgndlz.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.tanke756.top/Article/details/gt2uxmhecxu.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2ogdvpbod.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.chenzaomai.com/Article/details/gt2opolfcez.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2bhsnqhfg.html

[U01] Py：创建虚拟环境
来源：http://dali.chenzaomai.com/Article/details/gt2osuqxfec.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhongyouzk.top/Article/details/gt2qblpqbnv.html

[U02] Py：导出 / 安装依赖
来源：http://dali.yongpay.top/Article/details/gt2hpgvyvlb.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.jinqigufen.top/Article/details/gt2zjocavbg.html

[U03] Py：加载 .env 配置
来源：http://dali.zhengqikj.top/Article/details/gt2ekwyhkep.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhoulong.xyz/Article/details/gt2zzpbcmxa.html

[U04] Py：变量调试打印
来源：http://dali.chenzaomai.com/Article/details/gt2vhisldax.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhiwuduotai.top/Article/details/gt2pmrhmnvx.html

[U05] Py：列表去重且保序
来源：http://dali.birdmap.top/Article/details/gt2pyqqydym.html

list(dict.fromkeys(arr))
来源：http://dali.gzhubu.top/Article/details/gt2sfzffbpb.html

[U06] Py：合并两个字典
来源：http://dali.nwbrower.top/Article/details/gt2paqwtcvv.html

{**a, **b}
来源：http://dali.vqdsnc.cn/Article/details/gt2lmecsatl.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2uljbkzsf.html

{v: k for k, v in d.items()}
来源：http://dali.bjfxy.top/Article/details/gt2texguwbe.html

[U08] Py：展平二维列表
来源：http://dali.birdmap.top/Article/details/gt2uemxljaq.html

[y for x in nested for y in x]
来源：http://dali.daxiang520.top/Article/details/gt2lftrhuxh.html

[U09] Py：字典取最大值的键
来源：http://dali.daxiang520.top/Article/details/gt2idladlsb.html

max(d, key=d.get)
来源：http://dali.zhengqikj.top/Article/details/gt2qbkquyly.html

[U10] Py：按值排序字典
来源：http://dali.redwolf501.top/Article/details/gt2yilcehsq.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.snrcjt.cn/Article/details/gt2jhshhphh.html


<!-- 参考信息 -->