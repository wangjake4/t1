代发 wailian999

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.havefunace.top/Article/details/gtqfyrpufp.html

[R66] 定时任务
来源：http://dali.yonumen.top/Article/details/gtevzwgkiz.html

crontab -e;  crontab -l
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrdfousjd.html

[R67] 生成随机十六进制串
来源：http://dali.jinyuanbaomall.cn/Article/details/gttbyndfvn.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gtglsdlvuf.html

[R68] 计算文件校验值
来源：http://dali.jinqigfzy.top/Article/details/gtxfeyllfh.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.jinqigfzy.top/Article/details/gtztvvhtlq.html

[R69] 生成随机密码
来源：http://dali.yonumen.top/Article/details/gtuekkxizf.html

head -c 16 /dev/urandom | base64
来源：http://dali.cucudq.cn/Article/details/gtpbtorgbp.html

[R70] 时间戳与互转
来源：http://dali.chenzaomai.com/Article/details/gtyubbbwqh.html

date +%s;  date -d @1700000000
来源：http://dali.feifeiyinyue.top/Article/details/gtmyzmzgyv.html

[R71] 日期格式化
来源：http://dali.fzhhl.top/Article/details/gtrsdlzpef.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.snrcjt.cn/Article/details/gtjmvajssm.html

[R72] 等待端口就绪
来源：http://dali.bjfxy.top/Article/details/gtcwhhvpjp.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.shangyingyoupin.top/Article/details/gtypxjbasd.html

[R73] 分割大日志
来源：http://dali.zycfv.cn/Article/details/gtuvcvunyi.html

split -l 1000 big.log part_
来源：http://dali.pengpengdd.cyou/Article/details/gtmdnniamz.html

[R74] 批量重命名
来源：http://dali.snrcjt.cn/Article/details/gtxqcbvcrn.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.jiagoushi.top/Article/details/gtnkfsexkl.html

[R75] 导出环境变量
来源：http://dali.redwolf501.top/Article/details/gtexthpger.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhiwuduotai.top/Article/details/gtswevsrsx.html

[R76] 使用临时文件
来源：http://dali.pengpengdd.cyou/Article/details/gtsutplygu.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.yj20258888.top/Article/details/gtgcotealx.html

[R77] 读取用户输入
来源：http://dali.havefunace.top/Article/details/gtnmvxgbhj.html

read -rp "请输入: " ans
来源：http://dali.wangshuangyany.cn/Article/details/gtlzqdtdvt.html

[R78] 交互式菜单
来源：http://dali.sxryk.cn/Article/details/gtfkbizclb.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.nanxuanxn.top/Article/details/gtmqgwseau.html

[R79] 解析命令行选项
来源：http://dali.yj202588.top/Article/details/gtoxbcgloe.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.xuanzx.com/Article/details/gtayibdsra.html

[R80] 查看脚本执行耗时
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmqnohkvx.html

time ./run.sh
来源：http://dali.gotoacloud.top/Article/details/gtmqnzzmlv.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtflissdtw.html

S. C / C++ 专题
来源：http://dali.fengsongda.top/Article/details/gtxdzsbric.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtabnzrkno.html

[S01] C：Hello World
来源：http://dali.redwolf501.top/Article/details/gtvwvzqdhq.html

#include <stdio.h>
来源：http://dali.hongshengwenyu.top/Article/details/gtnwfxfthw.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.gotoacloud.top/Article/details/gtzlljyptg.html

[S02] C：变量与格式化输出
来源：http://dali.xuanzx.com/Article/details/gtuqcffjog.html

int a = 10; printf("%d\n", a);
来源：http://dali.pycfn.com/Article/details/gteiofysbb.html

[S03] C：读入整数
来源：http://dali.yanxiufei.cn/Article/details/gtufbxvasu.html

int x; scanf("%d", &x);
来源：http://dali.shangyingyoupin.top/Article/details/gtimifnija.html

[S04] C：字符串复制
来源：http://dali.c1oappe.top/Article/details/gtbssuyljl.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.feifeiyinyue.top/Article/details/gtmzmikcli.html

[S05] C：字符串长度
来源：http://dali.guannengcc.top/Article/details/gtmkqyshlz.html

strlen(s)
来源：http://dali.yongpay.top/Article/details/gtzzpymhho.html

[S06] C：字符串比较
来源：http://dali.hongshengwenyu.top/Article/details/gtmhffmimm.html

strcmp(a, b) == 0
来源：http://dali.nanxuanxn.top/Article/details/gtnlpjxbtf.html

[S07] C：数组遍历求和
来源：http://dali.shangyingyoupin.top/Article/details/gtdjqdotma.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.sxryk.cn/Article/details/gtxrbyabsm.html

[S08] C：动态内存分配与释放
来源：http://dali.jqgufenzy.top/Article/details/gtanxshqok.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.smart0.xyz/Article/details/gtpycqtsro.html

[S09] C：结构体定义与初始化
来源：http://dali.vqdsnc.cn/Article/details/gteyjamhhu.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.jqgufenzy.top/Article/details/gtmdrqszca.html

[S10] C：指针与解引用
来源：http://dali.cashguo.top/Article/details/gtibhmvbdx.html

int *p = &a;  *p = 5;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjlbnfoff.html

[S11] C：逐行读文件
来源：http://dali.yuanzhike.top/Article/details/gtxrqxyeph.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.yj20258888.top/Article/details/gtvljohzrs.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.ydzc1.top/Article/details/gtfnnnqmte.html

fclose(f);
来源：http://dali.xylfe.cn/Article/details/gtsgqvouoj.html

[S12] C：写文件
来源：http://dali.fzhhl.top/Article/details/gtflptlktx.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.0kj1m.cn/Article/details/gtydvqrvgx.html

[S13] C：宏定义
来源：http://dali.yuxming.cn/Article/details/gtuwoqwbsw.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.guannengcc.top/Article/details/gtpqkgrckl.html

[S14] C：枚举
来源：http://dali.tanke756.top/Article/details/gtdhfhircv.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gtgfzgqqgf.html

[S15] C：类型转换
来源：http://dali.yvedp.cn/Article/details/gtonvppfax.html

(double) a / b
来源：http://dali.c1oappe.top/Article/details/gtwugjdkgc.html

[S16] C：位操作置位
来源：http://dali.hongshengwenyu.top/Article/details/gtdjtubqri.html

x |= (1 << 3);
来源：http://dali.yj20258888.top/Article/details/gtgzjynllm.html

[S17] C：安全拼接字符串
来源：http://dali.hfpthk.cn/Article/details/gthkuondab.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtavsgnboq.html

[S18] C：命令行参数
来源：http://dali.quarkkingdee.top/Article/details/gtldyfffwb.html

int main(int argc, char **argv)
来源：http://dali.ivvv.top/Article/details/gtyfcdujwn.html

[S19] C：快速排序
来源：http://dali.yuanzhike.top/Article/details/gtptqpefnv.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.aizwys.cn/Article/details/gtthflteov.html

[S20] C：二分查找
来源：http://dali.sxryk.cn/Article/details/gtrujcuocz.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.yj20258.top/Article/details/gtxtfzetjf.html

[S21] C：字符类别判断
来源：http://dali.jianghu66.top/Article/details/gtqsitijmh.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.yj20258888.top/Article/details/gttradhhoz.html

[S22] C：字符串转数字
来源：http://dali.ppjwa.cn/Article/details/gttbgnbsoz.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.snrcjt.cn/Article/details/gttkilncdh.html

[S23] C：随机数
来源：http://dali.tianlin.xyz/Article/details/gtzwerbgvt.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.cdnleiting.top/Article/details/gtplszcozy.html

[S24] C：获取本地时间
来源：http://dali.aibaodan.cn/Article/details/gthaubvwie.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhengqikj.top/Article/details/gtsplfoavi.html

[S25] C：内存拷贝
来源：http://dali.sweek.top/Article/details/gtyqtqruts.html

memcpy(dst, src, n);
来源：http://dali.dashuyun.cn/Article/details/gtnmlxfnvg.html

[S26] C：内存清零
来源：http://dali.yj20258888.top/Article/details/gtwvbavxig.html

memset(a, 0, sizeof a);
来源：http://dali.xuanzx.com/Article/details/gtvlbtftpt.html

[S27] C：定义常量
来源：http://dali.aibaodan.cn/Article/details/gttesucper.html

const double PI = 3.14159;
来源：http://dali.feifeiyinyue.top/Article/details/gthkeuemlv.html

[S28] C：静态变量
来源：http://dali.hfpthk.cn/Article/details/gttyvtxkwb.html

static int counter = 0;
来源：http://dali.gzhubu.top/Article/details/gtqxwptcra.html

[S29] C：变参函数
来源：http://dali.gogol.net.cn/Article/details/gtislyohzs.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.ehwqpu.com/Article/details/gtgguozeiy.html

[S30] C：头文件保护
来源：http://dali.hnxiangtu.top/Article/details/gtfoyhsvxa.html

#ifndef X_H
来源：http://dali.wangshuangyany.cn/Article/details/gthabomyxk.html

#define X_H
来源：http://dali.wangdashe.top/Article/details/gtcsrglndz.html

#endif
来源：http://dali.yangfankeji.com/Article/details/gtutiyewai.html

[S31] C++：Hello World
来源：http://dali.nanxuanxn.top/Article/details/gtiihojmvg.html

#include <iostream>
来源：http://dali.daria6918.cn/Article/details/gtpyasnwlx.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.yonumen.top/Article/details/gtxsbnfvsb.html

[S32] C++：字符串
来源：http://dali.jyoumei.cn/Article/details/gterapxriv.html

std::string s = "hi";  s += "!";
来源：http://dali.zhongyouzk.top/Article/details/gtcvbdchbl.html

[S33] C++：vector 增删
来源：http://dali.daxiang520.top/Article/details/gtumugejkq.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.cashguo.top/Article/details/gtnepkiuxh.html

[S34] C++：遍历 vector
来源：http://dali.guowangkeji.top/Article/details/gtljrfzgvd.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.daria6918.cn/Article/details/gtsvlvshzs.html

[S35] C++：map
来源：http://dali.yj20258888.top/Article/details/gtwzefmbjd.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.ehwqpu.com/Article/details/gtznviwdnr.html

[S36] C++：unordered_map
来源：http://dali.zhixingplan.top/Article/details/gtohjyntyx.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.gogol.net.cn/Article/details/gttgldyvbv.html

[S37] C++：set
来源：http://dali.smart0.xyz/Article/details/gtsbaxcams.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.aibaodan.cn/Article/details/gttyccdgsq.html

[S38] C++：排序
来源：http://dali.dianchejie.cn/Article/details/gtactlmiuo.html

std::sort(v.begin(), v.end());
来源：http://dali.wangshuangyany.cn/Article/details/gtempszndf.html

[S39] C++：自定义比较器排序
来源：http://dali.iojbl.cn/Article/details/gtxtczjzri.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.shanyushiyangkeji.top/Article/details/gtewhgjdug.html

[S40] C++：查找元素
来源：http://dali.tianlin.xyz/Article/details/gtlusgqrqo.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.ydzc1.top/Article/details/gtxacsjaod.html

[S41] C++：类与构造函数
来源：http://dali.iojbl.cn/Article/details/gtibzxvdao.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.ybcxt.top/Article/details/gtxfgtbcrv.html

[S42] C++：继承与虚函数
来源：http://dali.nwbrower.top/Article/details/gtzzngkutc.html

class B : public Base { public: void f() override {} };
来源：http://dali.vqdsnc.cn/Article/details/gtzyzihvwk.html

[S43] C++：智能指针
来源：http://dali.hysaishi.cn/Article/details/gtfjddycrp.html

auto p = std::make_unique<int>(5);
来源：http://dali.0kj1m.cn/Article/details/gtyaxlsjsd.html

[S44] C++：引用传参
来源：http://dali.snrcjt.cn/Article/details/gtbbgbtkhs.html

void inc(int &x) { ++x; }
来源：http://dali.xinyue.icu/Article/details/gtunsjutio.html

[S45] C++：lambda
来源：http://dali.dianchejie.cn/Article/details/gtzhzjfkxd.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.smart0.xyz/Article/details/gtezruaqkw.html

[S46] C++：函数模板
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmwaaxwzx.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.nanxinkj.top/Article/details/gthaqgmkzp.html

[S47] C++：结构化绑定遍历
来源：http://dali.ivvv.top/Article/details/gtnovumpgy.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.hnqzz.top/Article/details/gtvtmtrxsi.html

[S48] C++：逐行读文件
来源：http://dali.aibaodan.cn/Article/details/gtigvzziam.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.hnxiangtu.top/Article/details/gtkxcdtazy.html

while (std::getline(in, line)) { }
来源：http://dali.feifeiyinyue.top/Article/details/gtefsygexj.html

[S49] C++：写文件
来源：http://dali.tianlin.xyz/Article/details/gttbloalxi.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.cheryme.top/Article/details/gtwmnttqsa.html

[S50] C++：格式化数字
来源：http://dali.daria6918.cn/Article/details/gtrdruuppc.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.nwbrower.top/Article/details/gtjfwfvsjz.html

[S51] C++：显式类型转换
来源：http://dali.nwbrower.top/Article/details/gtfvnrmziu.html

static_cast<double>(a) / b
来源：http://dali.zhiwuduotai.top/Article/details/gtrawikyyl.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gtvxhhheow.html

int size() const noexcept { return n_; }
来源：http://dali.jyoumei.cn/Article/details/gtinfgdynf.html

[S53] C++：移动语义
来源：http://dali.shuidangran.top/Article/details/gtivreawkp.html

std::vector<int> w = std::move(v);
来源：http://dali.cqqwz.cn/Article/details/gtrcuhsczb.html

[S54] C++：异常处理
来源：http://dali.hfpthk.cn/Article/details/gtrvgripvm.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.9152youxi.cn/Article/details/gtzcdtfwkt.html

[S55] C++：结构化绑定
来源：http://dali.hfpthk.cn/Article/details/gtlkvdtxsa.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.mhx1999.top/Article/details/gtjdfwmhva.html

[S56] C++：optional
来源：http://dali.ehwqpu.com/Article/details/gtfouvxdlw.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.jyoumei.cn/Article/details/gtejmllaln.html

[S57] C++：编译期常量
来源：http://dali.gaohongyu789.top/Article/details/gtiibqzjwv.html

constexpr int N = 10;
来源：http://dali.tianlin.xyz/Article/details/gtaatesxxx.html

[S58] C++：命名空间
来源：http://dali.jinghuilouyu.cn/Article/details/gtdqaywhyw.html

namespace ns { int f() { return 1; } }
来源：http://dali.shanyushiyangtech.top/Article/details/gtsbpyakxx.html

[S59] C++：静态断言
来源：http://dali.aibaodan.cn/Article/details/gtmirwqdmn.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.kuanghao11.cn/Article/details/gtfirpdnhz.html

[S60] C++：遍历并删除元素
来源：http://dali.guowangkeji.top/Article/details/gtkjlcqrov.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.0kj1m.cn/Article/details/gtcalsbfeu.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtqfydncyf.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhongyouzk.top/Article/details/gtxciscdeu.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtclmtmtqt.html

[T01] Kotlin：Hello World
来源：http://dali.nanxuanxn.top/Article/details/gtumywzopo.html

println("Hello")
来源：http://dali.cheryme.top/Article/details/gtlxtchlor.html

[T02] Kotlin：变量
来源：http://dali.cqqwz.cn/Article/details/gtibjnovkb.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.ehwqpu.com/Article/details/gtzusdtton.html

[T03] Kotlin：字符串模板
来源：http://dali.shzxlz.cn/Article/details/gtfwmlfkeo.html

"值: $b"
来源：http://dali.zhoulong.xyz/Article/details/gtcunihnhl.html

[T04] Kotlin：空安全
来源：http://dali.ehwqpu.com/Article/details/gtlfvngwjr.html

val n: String? = null;  n?.length
来源：http://dali.jinqigufen.top/Article/details/gtkjiniwwj.html

[T05] Kotlin：when 表达式
来源：http://dali.cheryme.top/Article/details/gtqgmffumj.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.gogol.net.cn/Article/details/gtuukomhls.html

[T06] Kotlin：集合映射
来源：http://dali.zdqjudy.top/Article/details/gtagnzncpo.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.yj20258888.top/Article/details/gtgqvoanye.html

[T07] Kotlin：集合过滤
来源：http://dali.tianlin.xyz/Article/details/gtnppyhjhl.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.9152youxi.cn/Article/details/gtsprvkyzj.html

[T08] Kotlin：数据类
来源：http://dali.aibaodan.cn/Article/details/gtiljgctkf.html

data class User(val name: String, val age: Int)
来源：http://dali.shangyingyoupin.top/Article/details/gtbgpjehev.html

[T09] Kotlin：扩展函数
来源：http://dali.dashuyun.cn/Article/details/gtiageeteg.html

fun String.exclaim() = this + "!"
来源：http://dali.xuanzx.com/Article/details/gtiehgggtd.html

[T10] Kotlin：默认参数
来源：http://dali.cashguo.top/Article/details/gtkjtkxbbs.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.kuanghao11.cn/Article/details/gtarrxeilc.html

[T11] Kotlin：协程
来源：http://dali.shanyushiyangkeji.top/Article/details/gtricqvbkd.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.cheryme.top/Article/details/gtejyfdxlz.html

[T12] Kotlin：解构声明
来源：http://dali.cheryme.top/Article/details/gtzeqpurmz.html

val (a, b) = Pair(1, 2)
来源：http://dali.xuetiantiany.cn/Article/details/gtazjxtsip.html

[T13] Kotlin：只读 Map
来源：http://dali.shangyingyoupin.top/Article/details/gtnytvizrl.html

val m = mapOf("a" to 1)
来源：http://dali.wangdashe.top/Article/details/gtiqoaqpoc.html

[T14] Kotlin：循环
来源：http://dali.pycfn.com/Article/details/gtyiblijfe.html

for (i in 1..10) println(i)
来源：http://dali.wangdashe.top/Article/details/gtkpwgwlug.html

[T15] Kotlin：接口
来源：http://dali.cqqwz.cn/Article/details/gtkkzmhdga.html

interface Shape { fun area(): Double }
来源：http://dali.shanyushiyangtech.top/Article/details/gtsexcadrf.html

[T16] Swift：Hello World
来源：http://dali.haohaochexian.top/Article/details/gtwhqilvyx.html

print("Hello")
来源：http://dali.sweek.top/Article/details/gtprpkbaia.html

[T17] Swift：变量与常量
来源：http://dali.havefunace.top/Article/details/gtitqswzyh.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gtbtrbmhtv.html

[T18] Swift：字符串插值
来源：http://dali.wangshuangyany.cn/Article/details/gtecvupfin.html

"值: \(b)"
来源：http://dali.dashuyun.cn/Article/details/gtxauwapcs.html

[T19] Swift：可选绑定
来源：http://dali.cucudq.cn/Article/details/gtubzflfkd.html

if let n = opt { print(n) }
来源：http://dali.0kj1m.cn/Article/details/gthjrjehns.html

[T20] Swift：数组操作
来源：http://dali.hywenlv.cn/Article/details/gtyqgstfay.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.xziqi.cn/Article/details/gtamwwgiyg.html

[T21] Swift：遍历
来源：http://dali.jyoumei.cn/Article/details/gtqurnypgw.html

for x in a { print(x) }
来源：http://dali.shzxlz.cn/Article/details/gtbfedixlr.html

[T22] Swift：字典
来源：http://dali.nanxinkj.top/Article/details/gthxqtikzf.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.sxryk.cn/Article/details/gtqpeuixmb.html

[T23] Swift：函数
来源：http://dali.cheryme.top/Article/details/gtkijjmamq.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.sysykeji.top/Article/details/gtxjihlxrq.html

[T24] Swift：闭包
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmugvthhc.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.ybcxt.top/Article/details/gtdjpkncjr.html

[T25] Swift：结构体
来源：http://dali.iojbl.cn/Article/details/gtxbcnbkzs.html

struct P { var x: Int }
来源：http://dali.316326.xyz/Article/details/gtorxuuwpo.html

[T26] Swift：类与重写
来源：http://dali.jianghu66.top/Article/details/gtpgzikcrn.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gtfrhyzuhw.html

[T27] Swift：错误处理
来源：http://dali.zycfv.cn/Article/details/gtajlokhgp.html

do { try f() } catch { print(error) }
来源：http://dali.jinqigufen.top/Article/details/gtnrqrudjp.html

[T28] Swift：枚举
来源：http://dali.ydzc1.top/Article/details/gtxhvlcghd.html

enum Color { case red, green }
来源：http://dali.xuanzx.com/Article/details/gtayninxnz.html

[T29] Swift：guard 提前返回
来源：http://dali.tanke756.top/Article/details/gtbqmadzwr.html

guard let x = opt else { return }
来源：http://dali.cashguo.top/Article/details/gtbmdtlpmz.html

[T30] Swift：协议
来源：http://dali.sysykeji.top/Article/details/gtahthovas.html

protocol Shape { func area() -> Double }
来源：http://dali.9152youxi.cn/Article/details/gtfhxuokpz.html

[T31] Lua：Hello World
来源：http://dali.zhengqikj.top/Article/details/gtaqfsgxgs.html

print("Hello")
来源：http://dali.guowangkeji.top/Article/details/gtuhhdjesh.html

[T32] Lua：局部变量
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlwhanveq.html

local a = 1
来源：http://dali.wangshuangyany.cn/Article/details/gtipqzolcm.html

[T33] Lua：表（数组）
来源：http://dali.sysykeji.top/Article/details/gtyaeayspj.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.redwolf501.top/Article/details/gtzmctluea.html

[T34] Lua：遍历表
来源：http://dali.chenzaomai.com/Article/details/gthgzclcuj.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zycfv.cn/Article/details/gtbtyrvvrr.html

[T35] Lua：字典表
来源：http://dali.jqgufenzy.top/Article/details/gtswtylory.html

local d = { a = 1 };  d.b = 2
来源：http://dali.wangshuangyany.cn/Article/details/gtkbrcvpsm.html

[T36] Lua：函数
来源：http://dali.yuanzhike.top/Article/details/gtilohctxn.html

function add(a, b) return a + b end
来源：http://dali.ivvv.top/Article/details/gtdfnlbhxs.html

[T37] Lua：字符串拼接
来源：http://dali.tian-w.cn/Article/details/gthdwfjwlq.html

"a" .. "b"
来源：http://dali.tian-w.cn/Article/details/gtsghlqqyo.html

[T38] Lua：条件
来源：http://dali.jinqigufen.top/Article/details/gtwbxqxxfx.html

if x > 0 then print("正") end
来源：http://dali.zhiwuduotai.top/Article/details/gtromylqrl.html

[T39] Lua：模式匹配
来源：http://dali.yanxiufei.cn/Article/details/gtwnrojmyc.html

string.find(s, "%d+")
来源：http://dali.pengpengdd.cyou/Article/details/gtndjirgiy.html

[T40] Lua：元表
来源：http://dali.jinyuanbaomall.cn/Article/details/gtffksfhei.html

setmetatable({}, { __index = base })
来源：http://dali.nanxuanxn.top/Article/details/gtaapeqavn.html

[T41] Perl：Hello World
来源：http://dali.hnxiangtu.top/Article/details/gtrdwmjvwk.html

print "Hello\n";
来源：http://dali.hywenlv.cn/Article/details/gtfekssktg.html

[T42] Perl：变量类型
来源：http://dali.cqqwz.cn/Article/details/gtnqmtchfv.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.tianlin.xyz/Article/details/gtfnjsnroc.html

[T43] Perl：字符串插值
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkjwzvfjy.html

"值: $a"
来源：http://dali.xuetiantiany.cn/Article/details/gtaqoclfvw.html

[T44] Perl：条件
来源：http://dali.bjfxy.top/Article/details/gtlhqzqlfw.html

if ($a > 0) { print "正"; }
来源：http://dali.sufxvd.cn/Article/details/gtmpmauhbt.html

[T45] Perl：数组遍历
来源：http://dali.316326.xyz/Article/details/gtcvwycigz.html

for my $x (@arr) { print $x; }
来源：http://dali.feifeiyinyue.top/Article/details/gtpgntennl.html

[T46] Perl：哈希操作
来源：http://dali.daria6918.cn/Article/details/gtaxinvaeh.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.nwbrower.top/Article/details/gtxctjtpwf.html

[T47] Perl：正则捕获
来源：http://dali.tanke756.top/Article/details/gtmkhgfoup.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.gotoacloud.top/Article/details/gtzvcmbqwo.html

[T48] Perl：正则替换
来源：http://dali.cqqwz.cn/Article/details/gtichbaqgj.html

$s =~ s/old/new/g;
来源：http://dali.hnqzz.top/Article/details/gtiheglhgd.html

[T49] Perl：函数
来源：http://dali.yangfankeji.com/Article/details/gthtdffvce.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.9152youxi.cn/Article/details/gthvzxinnv.html

[T50] Perl：逐行读文件
来源：http://dali.gotoacloud.top/Article/details/gtbzmdolge.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.cucudq.cn/Article/details/gtfzrfevzj.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.mhx1999.top/Article/details/gtijqdoptq.html

[T51] Scala：Hello World
来源：http://dali.zhixingplan.top/Article/details/gtoikiduxc.html

println("Hello")
来源：http://dali.aizwys.cn/Article/details/gtrbcjhtld.html

[T52] Scala：变量
来源：http://dali.sysykeji.top/Article/details/gtslfubbok.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gtdhgwdime.html

[T53] Scala：字符串插值
来源：http://dali.yonumen.top/Article/details/gtduvudcli.html

s"值: $b"
来源：http://dali.hywenlv.cn/Article/details/gtjqxmflmb.html

[T54] Scala：集合映射
来源：http://dali.yongpay.top/Article/details/gtgdijlobd.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtarnrcfpn.html

[T55] Scala：集合过滤
来源：http://dali.jinghuilouyu.cn/Article/details/gtwxzlwshp.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.wangdashe.top/Article/details/gtcohnpzml.html

[T56] Scala：样例类
来源：http://dali.gaohongyu789.top/Article/details/gtrxxtebvl.html

case class User(name: String, age: Int)
来源：http://dali.jinqigfzy.top/Article/details/gtjcgaldle.html

[T57] Scala：模式匹配
来源：http://dali.snrcjt.cn/Article/details/gtdlctbtve.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.xylfe.cn/Article/details/gtdrhwrvwf.html

[T58] Scala：函数定义
来源：http://dali.andypj.xyz/Article/details/gtkiuzcvxg.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.jinqigfzy.top/Article/details/gtohievmej.html

[T59] Scala：循环
来源：http://dali.xinyue.icu/Article/details/gteeqnnxxp.html

for (i <- 1 to 10) println(i)
来源：http://dali.hammf.cn/Article/details/gtdwjxiodf.html

[T60] Scala：折叠
来源：http://dali.guowangkeji.top/Article/details/gthlsdkrqw.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.cheryme.top/Article/details/gtbhkfpuhy.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtdvoltbla.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.hysaishi.cn/Article/details/gtwihtwrsp.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtmapnuxxl.html

[U01] Py：创建虚拟环境
来源：http://dali.hammf.cn/Article/details/gthuiaiqgz.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.jqgfzy.top/Article/details/gtcknqydiw.html

[U02] Py：导出 / 安装依赖
来源：http://dali.nwbrower.top/Article/details/gtsqnwhljj.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.guannengcc.top/Article/details/gtfeknatnx.html

[U03] Py：加载 .env 配置
来源：http://dali.tianlin.xyz/Article/details/gtoqoiulba.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.haohaochexian.top/Article/details/gtdhnlmhsk.html

[U04] Py：变量调试打印
来源：http://dali.316326.xyz/Article/details/gtpbxqnyrk.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.ydzc1.top/Article/details/gtuvmfuysu.html

[U05] Py：列表去重且保序
来源：http://dali.xziqi.cn/Article/details/gtexcfqpcy.html

list(dict.fromkeys(arr))
来源：http://dali.snrcjt.cn/Article/details/gtfqeuspcg.html

[U06] Py：合并两个字典
来源：http://dali.sufxvd.cn/Article/details/gtfnyndzvw.html

{**a, **b}
来源：http://dali.feifeiyinyue.top/Article/details/gtkveylxgq.html


<!-- 参考信息 -->