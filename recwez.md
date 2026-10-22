代发 wailian999

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhixingplan.top/Article/details/gtynzmyipd.html

[R66] 定时任务
来源：http://dali.sxryk.cn/Article/details/gtxoiulcun.html

crontab -e;  crontab -l
来源：http://dali.cdnleiting.top/Article/details/gtcygqbiql.html

[R67] 生成随机十六进制串
来源：http://dali.havefunace.top/Article/details/gtuvfwjjar.html

openssl rand -hex 16
来源：http://dali.feifeiyinyue.top/Article/details/gtfhcubjgu.html

[R68] 计算文件校验值
来源：http://dali.sxryk.cn/Article/details/gtbentnsyn.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.xinyue.icu/Article/details/gtobzbwaur.html

[R69] 生成随机密码
来源：http://dali.yueranfly.top/Article/details/gtsrywawoc.html

head -c 16 /dev/urandom | base64
来源：http://dali.ppjwa.cn/Article/details/gtkyxmhgzi.html

[R70] 时间戳与互转
来源：http://dali.birdmap.top/Article/details/gtyqaylsie.html

date +%s;  date -d @1700000000
来源：http://dali.smart0.xyz/Article/details/gtktshcvgp.html

[R71] 日期格式化
来源：http://dali.9152youxi.cn/Article/details/gtyldylsnm.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.cqqwz.cn/Article/details/gtzuyoqdfp.html

[R72] 等待端口就绪
来源：http://dali.chenlongwang.top/Article/details/gtmcfkrlhe.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.xinyue.icu/Article/details/gtsockjwjr.html

[R73] 分割大日志
来源：http://dali.birdmap.top/Article/details/gtmrcccczn.html

split -l 1000 big.log part_
来源：http://dali.sysykeji.top/Article/details/gtgpxvxeav.html

[R74] 批量重命名
来源：http://dali.jqgfzy.top/Article/details/gtkxjzgljb.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.mhx1999.top/Article/details/gtavrwtwhg.html

[R75] 导出环境变量
来源：http://dali.zhoulong.xyz/Article/details/gtubfcryqb.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zdqjudy.top/Article/details/gtitwprlgl.html

[R76] 使用临时文件
来源：http://dali.hywenlv.cn/Article/details/gtlfdjvlgj.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.tian-w.cn/Article/details/gthwwjfsvv.html

[R77] 读取用户输入
来源：http://dali.hnqzz.top/Article/details/gtbuwvradh.html

read -rp "请输入: " ans
来源：http://dali.ybcxt.top/Article/details/gtffchgvzp.html

[R78] 交互式菜单
来源：http://dali.feifeiyinyue.top/Article/details/gtscnavdis.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.vqdsnc.cn/Article/details/gtqbnjywlx.html

[R79] 解析命令行选项
来源：http://dali.sxryk.cn/Article/details/gtzhowglrt.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzxjnygcy.html

[R80] 查看脚本执行耗时
来源：http://dali.wangdashe.top/Article/details/gtjohgctvp.html

time ./run.sh
来源：http://dali.guowangkeji.top/Article/details/gttzfbpgaw.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtgreqekeq.html

S. C / C++ 专题
来源：http://dali.dashuyun.cn/Article/details/gtdsymdpan.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtzxytlyaq.html

[S01] C：Hello World
来源：http://dali.cqqwz.cn/Article/details/gtgwrxrqij.html

#include <stdio.h>
来源：http://dali.aizwys.cn/Article/details/gtrevajvzc.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.wangdashe.top/Article/details/gtmpflhvwi.html

[S02] C：变量与格式化输出
来源：http://dali.havefunace.top/Article/details/gtuaqzflvs.html

int a = 10; printf("%d\n", a);
来源：http://dali.xinyue.icu/Article/details/gtjpbwkegs.html

[S03] C：读入整数
来源：http://dali.sweek.top/Article/details/gtefjbcgjg.html

int x; scanf("%d", &x);
来源：http://dali.zhongyouzk.top/Article/details/gtmjnbpvdm.html

[S04] C：字符串复制
来源：http://dali.cucudq.cn/Article/details/gthkzbuuen.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.yvedp.cn/Article/details/gtpsjwvzmf.html

[S05] C：字符串长度
来源：http://dali.sweek.top/Article/details/gtujfbxxoc.html

strlen(s)
来源：http://dali.aizwys.cn/Article/details/gthxfpakkz.html

[S06] C：字符串比较
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjzjekuuh.html

strcmp(a, b) == 0
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtexbleowr.html

[S07] C：数组遍历求和
来源：http://dali.gogol.net.cn/Article/details/gtrcavsxpd.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.sxryk.cn/Article/details/gteukrnrqw.html

[S08] C：动态内存分配与释放
来源：http://dali.hnxiangtu.top/Article/details/gtgjqzfdhq.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.guowangkeji.top/Article/details/gtkkxoujki.html

[S09] C：结构体定义与初始化
来源：http://dali.xuanzx.com/Article/details/gtlejqnyvn.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhixingplan.top/Article/details/gtbcxrekbm.html

[S10] C：指针与解引用
来源：http://dali.yonumen.top/Article/details/gtmjrckqnw.html

int *p = &a;  *p = 5;
来源：http://dali.xylfe.cn/Article/details/gtdjmmqhzw.html

[S11] C：逐行读文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdzcsnnwp.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.kuanghao11.cn/Article/details/gtihhaqqtr.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.ehwqpu.com/Article/details/gtymkvdryd.html

fclose(f);
来源：http://dali.316326.xyz/Article/details/gtpckdomzm.html

[S12] C：写文件
来源：http://dali.dashuyun.cn/Article/details/gtckjhdpui.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.chenzaomai.com/Article/details/gtduuencnn.html

[S13] C：宏定义
来源：http://dali.feifeiyinyue.top/Article/details/gtgxxpsbua.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.dashuyun.cn/Article/details/gtcoxfutxx.html

[S14] C：枚举
来源：http://dali.aibaodan.cn/Article/details/gtvauajebb.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.xziqi.cn/Article/details/gtnhbjtocr.html

[S15] C：类型转换
来源：http://dali.zhengqikj.top/Article/details/gtevzxsvry.html

(double) a / b
来源：http://dali.jinqigfzy.top/Article/details/gtctegpzua.html

[S16] C：位操作置位
来源：http://dali.jianghu66.top/Article/details/gtwyfxrgew.html

x |= (1 << 3);
来源：http://dali.zhixingplan.top/Article/details/gtgdbykroz.html

[S17] C：安全拼接字符串
来源：http://dali.cucudq.cn/Article/details/gtnfprbkpw.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.dashuyun.cn/Article/details/gtlodvrqyq.html

[S18] C：命令行参数
来源：http://dali.ehwqpu.com/Article/details/gteolnbfig.html

int main(int argc, char **argv)
来源：http://dali.ehwqpu.com/Article/details/gtdibbqvec.html

[S19] C：快速排序
来源：http://dali.zycfv.cn/Article/details/gtejaqzeoh.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.quarkkingdee.top/Article/details/gtxiqcmyux.html

[S20] C：二分查找
来源：http://dali.havefunace.top/Article/details/gtaxbnoyzv.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.havefunace.top/Article/details/gtrgjvblsw.html

[S21] C：字符类别判断
来源：http://dali.chenzaomai.com/Article/details/gtylhhyekx.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.shzxlz.cn/Article/details/gtqqqdbeut.html

[S22] C：字符串转数字
来源：http://dali.vqdsnc.cn/Article/details/gtwmucusyp.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.xuanzx.com/Article/details/gtnklifwtt.html

[S23] C：随机数
来源：http://dali.jqgufenzy.top/Article/details/gtloyzgbng.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.sweek.top/Article/details/gtxqaialus.html

[S24] C：获取本地时间
来源：http://dali.tanke756.top/Article/details/gtqcmhavdt.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.gotoacloud.top/Article/details/gthlxiajmj.html

[S25] C：内存拷贝
来源：http://dali.birdmap.top/Article/details/gtcqwhlscp.html

memcpy(dst, src, n);
来源：http://dali.zhixingplan.top/Article/details/gtkqdvopis.html

[S26] C：内存清零
来源：http://dali.xylfe.cn/Article/details/gtgbzzgxjy.html

memset(a, 0, sizeof a);
来源：http://dali.kuanghao11.cn/Article/details/gtpnjgxphw.html

[S27] C：定义常量
来源：http://dali.vqdsnc.cn/Article/details/gtsugetgqn.html

const double PI = 3.14159;
来源：http://dali.jianghu66.top/Article/details/gtwidgywxt.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gtzjagowyh.html

static int counter = 0;
来源：http://dali.0kj1m.cn/Article/details/gtuzndnqol.html

[S29] C：变参函数
来源：http://dali.yueranfly.top/Article/details/gtfqyhwous.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.tian-w.cn/Article/details/gtpsnlyspm.html

[S30] C：头文件保护
来源：http://dali.bjfxy.top/Article/details/gthwnitjje.html

#ifndef X_H
来源：http://dali.xuanzx.com/Article/details/gtqgmbgbpj.html

#define X_H
来源：http://dali.sxryk.cn/Article/details/gtjdbqjlyu.html

#endif
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbfvnwtqn.html

[S31] C++：Hello World
来源：http://dali.xuanzx.com/Article/details/gtrkkihiiv.html

#include <iostream>
来源：http://dali.daria6918.cn/Article/details/gtmzsvbstc.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.andypj.xyz/Article/details/gtfablepyc.html

[S32] C++：字符串
来源：http://dali.meibo888.top/Article/details/gtfjojvwmd.html

std::string s = "hi";  s += "!";
来源：http://dali.aizwys.cn/Article/details/gtapzrlkzv.html

[S33] C++：vector 增删
来源：http://dali.cashguo.top/Article/details/gthuqklntz.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.jianghu66.top/Article/details/gteducbcpk.html

[S34] C++：遍历 vector
来源：http://dali.jqgfzy.top/Article/details/gtmfbyjmoj.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmeaabclr.html

[S35] C++：map
来源：http://dali.chenjidiqi.icu/Article/details/gtyxehrsnd.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.guannengcc.top/Article/details/gtpohwgkcr.html

[S36] C++：unordered_map
来源：http://dali.yanxiufei.cn/Article/details/gtifzhnsfu.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuyhriqad.html

[S37] C++：set
来源：http://dali.zdqjudy.top/Article/details/gtjhobiruj.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.jqgfzy.top/Article/details/gtpbttfnuc.html

[S38] C++：排序
来源：http://dali.havefunace.top/Article/details/gtvkxdymbb.html

std::sort(v.begin(), v.end());
来源：http://dali.feifeiyinyue.top/Article/details/gtwyyzqeeb.html

[S39] C++：自定义比较器排序
来源：http://dali.tian-w.cn/Article/details/gthtsezsft.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhongyouzk.top/Article/details/gtcnkucolb.html

[S40] C++：查找元素
来源：http://dali.fengsongda.top/Article/details/gttdvmpmgi.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.wangshuangyany.cn/Article/details/gtfkkqqwzn.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gtocbcbwpd.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.haohaochexian.top/Article/details/gtimiytiau.html

[S42] C++：继承与虚函数
来源：http://dali.shzxlz.cn/Article/details/gtsezevjse.html

class B : public Base { public: void f() override {} };
来源：http://dali.nanxuanxn.top/Article/details/gtufzkvnyf.html

[S43] C++：智能指针
来源：http://dali.aibaodan.cn/Article/details/gtpljkzrnn.html

auto p = std::make_unique<int>(5);
来源：http://dali.bjfxy.top/Article/details/gttxjxycbs.html

[S44] C++：引用传参
来源：http://dali.cashguo.top/Article/details/gtsrxcgkey.html

void inc(int &x) { ++x; }
来源：http://dali.gzhubu.top/Article/details/gtkvvudvaw.html

[S45] C++：lambda
来源：http://dali.birdmap.top/Article/details/gttnhhibcj.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.jiagoushi.top/Article/details/gtvswodrmn.html

[S46] C++：函数模板
来源：http://dali.feifeiyinyue.top/Article/details/gtrpjqtzwl.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.pycfn.com/Article/details/gtzcfozinj.html

[S47] C++：结构化绑定遍历
来源：http://dali.c1oappe.top/Article/details/gtojfkvrfa.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.birdmap.top/Article/details/gtkwvkokod.html

[S48] C++：逐行读文件
来源：http://dali.hfpthk.cn/Article/details/gttszamrlz.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.dashuyun.cn/Article/details/gtpdcocaqo.html

while (std::getline(in, line)) { }
来源：http://dali.haohaochexian.top/Article/details/gtwenxjrhi.html

[S49] C++：写文件
来源：http://dali.yueranfly.top/Article/details/gtswayvwak.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.havefunace.top/Article/details/gthvxbkgcp.html

[S50] C++：格式化数字
来源：http://dali.tanke756.top/Article/details/gtcdyvvilj.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.sxryk.cn/Article/details/gtfmdvskmn.html

[S51] C++：显式类型转换
来源：http://dali.aibaodan.cn/Article/details/gtxqeuocpt.html

static_cast<double>(a) / b
来源：http://dali.mhx1999.top/Article/details/gtrplzudmq.html

[S52] C++：const 与 noexcept
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdhljwfxc.html

int size() const noexcept { return n_; }
来源：http://dali.zhongyouzk.top/Article/details/gtzxkuwdvh.html

[S53] C++：移动语义
来源：http://dali.ivvv.top/Article/details/gtebfypzuh.html

std::vector<int> w = std::move(v);
来源：http://dali.yuanzhike.top/Article/details/gtbiruwpyi.html

[S54] C++：异常处理
来源：http://dali.jiagoushi.top/Article/details/gtmrvbzvno.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.hnxiangtu.top/Article/details/gtuhlvekgh.html

[S55] C++：结构化绑定
来源：http://dali.mhx1999.top/Article/details/gtbaeqzeyr.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.hysaishi.cn/Article/details/gtdpzvlrem.html

[S56] C++：optional
来源：http://dali.birdmap.top/Article/details/gtdxjrcmvr.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.tianlin.xyz/Article/details/gtcqdrjrxy.html

[S57] C++：编译期常量
来源：http://dali.sufxvd.cn/Article/details/gtvfzuogyz.html

constexpr int N = 10;
来源：http://dali.kuanghao11.cn/Article/details/gttreghpct.html

[S58] C++：命名空间
来源：http://dali.zhixingplan.top/Article/details/gtdirerwlx.html

namespace ns { int f() { return 1; } }
来源：http://dali.bjfxy.top/Article/details/gtppcuybrc.html

[S59] C++：静态断言
来源：http://dali.shzxlz.cn/Article/details/gtwtmukwmv.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.mhx1999.top/Article/details/gtcbkvyrzt.html

[S60] C++：遍历并删除元素
来源：http://dali.svipenyu.cn/Article/details/gtzunplebg.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.fzhhl.top/Article/details/gtwbwlapbz.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtvpjnglpz.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.hysaishi.cn/Article/details/gtyxhccvgz.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtytwilfco.html

[T01] Kotlin：Hello World
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgboblyjs.html

println("Hello")
来源：http://dali.cqqwz.cn/Article/details/gtsvnrbtju.html

[T02] Kotlin：变量
来源：http://dali.shuidangran.top/Article/details/gttsggwoio.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.jinghuilouyu.cn/Article/details/gtmojnmfnd.html

[T03] Kotlin：字符串模板
来源：http://dali.zhiwuduotai.top/Article/details/gtfvponggm.html

"值: $b"
来源：http://dali.gzhubu.top/Article/details/gtqqerawhr.html

[T04] Kotlin：空安全
来源：http://dali.yj20258.top/Article/details/gtylleceza.html

val n: String? = null;  n?.length
来源：http://dali.cdnleiting.top/Article/details/gtkcatbaik.html

[T05] Kotlin：when 表达式
来源：http://dali.zhongyouzk.top/Article/details/gtcmgmnjzi.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.hnqzz.top/Article/details/gtzmrkxzvq.html

[T06] Kotlin：集合映射
来源：http://dali.tian-w.cn/Article/details/gtoapufbot.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.cheryme.top/Article/details/gtjyixlrpz.html

[T07] Kotlin：集合过滤
来源：http://dali.zhengqikj.top/Article/details/gtqwsqgazh.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zycfv.cn/Article/details/gtpjnhsfjy.html

[T08] Kotlin：数据类
来源：http://dali.redwolf501.top/Article/details/gtavfvejha.html

data class User(val name: String, val age: Int)
来源：http://dali.iojbl.cn/Article/details/gtimupnziy.html

[T09] Kotlin：扩展函数
来源：http://dali.yuanzhike.top/Article/details/gtfawolarj.html

fun String.exclaim() = this + "!"
来源：http://dali.nanxuanxn.top/Article/details/gtknjqomay.html

[T10] Kotlin：默认参数
来源：http://dali.zhiwuduotai.top/Article/details/gtnirxdmca.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuniffgmv.html

[T11] Kotlin：协程
来源：http://dali.hongshengwenyu.top/Article/details/gtijgolaxi.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.ydzc1.top/Article/details/gtxtunuthf.html

[T12] Kotlin：解构声明
来源：http://dali.hammf.cn/Article/details/gtllydbqgi.html

val (a, b) = Pair(1, 2)
来源：http://dali.chenlongwang.top/Article/details/gteflirswn.html

[T13] Kotlin：只读 Map
来源：http://dali.fzhhl.top/Article/details/gtaznexjdv.html

val m = mapOf("a" to 1)
来源：http://dali.yj20258888.top/Article/details/gthudzhazy.html

[T14] Kotlin：循环
来源：http://dali.pengpengdd.cyou/Article/details/gtxvwuytnq.html

for (i in 1..10) println(i)
来源：http://dali.dianchejie.cn/Article/details/gtvfebsugs.html

[T15] Kotlin：接口
来源：http://dali.kuanghao11.cn/Article/details/gtuejnklxa.html

interface Shape { fun area(): Double }
来源：http://dali.ydzc1.top/Article/details/gthphnlhgx.html

[T16] Swift：Hello World
来源：http://dali.hnxiangtu.top/Article/details/gtawqeltgn.html

print("Hello")
来源：http://dali.quarkkingdee.top/Article/details/gtiouwqxdi.html

[T17] Swift：变量与常量
来源：http://dali.guannengcc.top/Article/details/gtpbngcsqb.html

var a = 1;  let b = 2
来源：http://dali.meibo888.top/Article/details/gtcbyhbsvp.html

[T18] Swift：字符串插值
来源：http://dali.cheryme.top/Article/details/gtlkfxtqxr.html

"值: \(b)"
来源：http://dali.hnxiangtu.top/Article/details/gtcpywplqu.html

[T19] Swift：可选绑定
来源：http://dali.ywan-chungtsiang.top/Article/details/gthwrlzvys.html

if let n = opt { print(n) }
来源：http://dali.cheryme.top/Article/details/gtlrtxpnqv.html

[T20] Swift：数组操作
来源：http://dali.sysykeji.top/Article/details/gthtglpitu.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.yanxiufei.cn/Article/details/gtxpfdmitb.html

[T21] Swift：遍历
来源：http://dali.hywenlv.cn/Article/details/gtpyrbhspa.html

for x in a { print(x) }
来源：http://dali.shanyushiyangtech.top/Article/details/gtfwiwbtzk.html

[T22] Swift：字典
来源：http://dali.yonumen.top/Article/details/gtvkubhfgw.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.hnxiangtu.top/Article/details/gtgywkxdgy.html

[T23] Swift：函数
来源：http://dali.zycfv.cn/Article/details/gtbtsndvtl.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.gzhubu.top/Article/details/gtocnvuyyw.html

[T24] Swift：闭包
来源：http://dali.fzhhl.top/Article/details/gthyjegxjx.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.smart0.xyz/Article/details/gtihjrvoti.html

[T25] Swift：结构体
来源：http://dali.316326.xyz/Article/details/gtxakbrulo.html

struct P { var x: Int }
来源：http://dali.zdqjudy.top/Article/details/gtymqipwje.html

[T26] Swift：类与重写
来源：http://dali.tian-w.cn/Article/details/gtcwrrcbel.html

class A: Base { override func f() {} }
来源：http://dali.guannengcc.top/Article/details/gtpkjoliwl.html

[T27] Swift：错误处理
来源：http://dali.jyoumei.cn/Article/details/gtleafsipy.html

do { try f() } catch { print(error) }
来源：http://dali.gotoacloud.top/Article/details/gteivbvbpc.html

[T28] Swift：枚举
来源：http://dali.jqgufenzy.top/Article/details/gtrnceodte.html

enum Color { case red, green }
来源：http://dali.9152youxi.cn/Article/details/gtwjyforvy.html

[T29] Swift：guard 提前返回
来源：http://dali.cucudq.cn/Article/details/gtyxeqpker.html

guard let x = opt else { return }
来源：http://dali.dianchejie.cn/Article/details/gtzsmrefoz.html

[T30] Swift：协议
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwlesyczu.html

protocol Shape { func area() -> Double }
来源：http://dali.guowangkeji.top/Article/details/gtccvojsjz.html

[T31] Lua：Hello World
来源：http://dali.yuxming.cn/Article/details/gtrkcxzexk.html

print("Hello")
来源：http://dali.sysykeji.top/Article/details/gtlzczbonj.html

[T32] Lua：局部变量
来源：http://dali.fzhhl.top/Article/details/gtadlffaul.html

local a = 1
来源：http://dali.hysaishi.cn/Article/details/gtksjsnayn.html

[T33] Lua：表（数组）
来源：http://dali.jyoumei.cn/Article/details/gtohtxvzzp.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.sufxvd.cn/Article/details/gtdipvjbqt.html

[T34] Lua：遍历表
来源：http://dali.ydzc1.top/Article/details/gtjewornpm.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhoulong.xyz/Article/details/gtykeeweui.html

[T35] Lua：字典表
来源：http://dali.chenjidiqi.icu/Article/details/gtlmbzpana.html

local d = { a = 1 };  d.b = 2
来源：http://dali.jlsjyb.cn/Article/details/gtdiierzmf.html

[T36] Lua：函数
来源：http://dali.zhengqikj.top/Article/details/gtddaqvdie.html

function add(a, b) return a + b end
来源：http://dali.ivvv.top/Article/details/gtnzbvfxir.html

[T37] Lua：字符串拼接
来源：http://dali.dashuyun.cn/Article/details/gtoycnsxwg.html

"a" .. "b"
来源：http://dali.daxiang520.top/Article/details/gthuxhohnh.html

[T38] Lua：条件
来源：http://dali.svipenyu.cn/Article/details/gtfsvetyzj.html

if x > 0 then print("正") end
来源：http://dali.havefunace.top/Article/details/gthvtajkti.html

[T39] Lua：模式匹配
来源：http://dali.ybcxt.top/Article/details/gtxtxvwntq.html

string.find(s, "%d+")
来源：http://dali.tianlin.xyz/Article/details/gtnzxjqfvi.html

[T40] Lua：元表
来源：http://dali.jqgfzy.top/Article/details/gtndurunwt.html

setmetatable({}, { __index = base })
来源：http://dali.yonumen.top/Article/details/gthfcgjoer.html

[T41] Perl：Hello World
来源：http://dali.birdmap.top/Article/details/gtflfcvgnt.html

print "Hello\n";
来源：http://dali.gotoacloud.top/Article/details/gtgvjxukfi.html

[T42] Perl：变量类型
来源：http://dali.birdmap.top/Article/details/gttostjwwm.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.tanke756.top/Article/details/gtkqezketa.html

[T43] Perl：字符串插值
来源：http://dali.c1oappe.top/Article/details/gtnmmmlcbz.html

"值: $a"
来源：http://dali.jqgufenzy.top/Article/details/gtalnatfzc.html

[T44] Perl：条件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlwfmairw.html

if ($a > 0) { print "正"; }
来源：http://dali.cdnleiting.top/Article/details/gtuqakulip.html

[T45] Perl：数组遍历
来源：http://dali.nanxinkj.top/Article/details/gtnztyjwjg.html

for my $x (@arr) { print $x; }
来源：http://dali.xziqi.cn/Article/details/gttjnekjen.html

[T46] Perl：哈希操作
来源：http://dali.quarkkingdee.top/Article/details/gtlftijrdi.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.9152youxi.cn/Article/details/gtgsiubary.html

[T47] Perl：正则捕获
来源：http://dali.ivvv.top/Article/details/gtrzfysxnx.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.daxiang520.top/Article/details/gtafxjmzoc.html

[T48] Perl：正则替换
来源：http://dali.shangyingyoupin.top/Article/details/gtvetygjfz.html

$s =~ s/old/new/g;
来源：http://dali.wangdashe.top/Article/details/gtezmslmys.html

[T49] Perl：函数
来源：http://dali.9152youxi.cn/Article/details/gtzdfhikue.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.gogol.net.cn/Article/details/gtlwevkdjo.html

[T50] Perl：逐行读文件
来源：http://dali.c1oappe.top/Article/details/gtcoqqojfx.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.snrcjt.cn/Article/details/gtvgcuojut.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gtradzhurc.html

[T51] Scala：Hello World
来源：http://dali.yangfankeji.com/Article/details/gtalajgynd.html

println("Hello")
来源：http://dali.redwolf501.top/Article/details/gtwpaurgyv.html

[T52] Scala：变量
来源：http://dali.jinyuanbaomall.cn/Article/details/gttrjmkuzd.html

val a = 1;  var b = 2
来源：http://dali.xylfe.cn/Article/details/gtvtnledkm.html

[T53] Scala：字符串插值
来源：http://dali.sxryk.cn/Article/details/gtufqndpfg.html

s"值: $b"
来源：http://dali.wangdashe.top/Article/details/gtjgwxufdg.html

[T54] Scala：集合映射
来源：http://dali.hnqzz.top/Article/details/gttncaubjb.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.shuidangran.top/Article/details/gttypagvda.html

[T55] Scala：集合过滤
来源：http://dali.zhengqikj.top/Article/details/gteugqybvg.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.0kj1m.cn/Article/details/gtgsshpqxy.html

[T56] Scala：样例类
来源：http://dali.yvedp.cn/Article/details/gtajnolxkd.html

case class User(name: String, age: Int)
来源：http://dali.yvedp.cn/Article/details/gtlbbhyvzy.html

[T57] Scala：模式匹配
来源：http://dali.nanxinkj.top/Article/details/gthlubkidv.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.gogol.net.cn/Article/details/gtprgkeqkr.html

[T58] Scala：函数定义
来源：http://dali.yj20258888.top/Article/details/gtfgduxauc.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.meibo888.top/Article/details/gthcolcrsa.html

[T59] Scala：循环
来源：http://dali.dianchejie.cn/Article/details/gttlmztkyi.html

for (i <- 1 to 10) println(i)
来源：http://dali.c1oappe.top/Article/details/gtfncdcjpr.html

[T60] Scala：折叠
来源：http://dali.jiagoushi.top/Article/details/gtqypcyvrc.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.sysykeji.top/Article/details/gtybncuerv.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gttamapiba.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.yanxiufei.cn/Article/details/gtvteclfff.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtqoiwrijv.html

[U01] Py：创建虚拟环境
来源：http://dali.yongpay.top/Article/details/gtlqnbhwip.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.shangyingyoupin.top/Article/details/gtifgeicmk.html

[U02] Py：导出 / 安装依赖
来源：http://dali.redwolf501.top/Article/details/gttocactcp.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.havefunace.top/Article/details/gtnvuzqcpv.html

[U03] Py：加载 .env 配置
来源：http://dali.tanke756.top/Article/details/gtuhbejdcn.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.daxiang520.top/Article/details/gtwqbiprzr.html

[U04] Py：变量调试打印
来源：http://dali.yj202588.top/Article/details/gtufsarivf.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.chenzaomai.com/Article/details/gtuwuhjwib.html

[U05] Py：列表去重且保序
来源：http://dali.fzhhl.top/Article/details/gtljtieluu.html

list(dict.fromkeys(arr))
来源：http://dali.hnxiangtu.top/Article/details/gtjuwfolau.html

[U06] Py：合并两个字典
来源：http://dali.cucudq.cn/Article/details/gtgwduhqki.html

{**a, **b}
来源：http://dali.quarkkingdee.top/Article/details/gthghvtowt.html


<!-- 参考信息 -->