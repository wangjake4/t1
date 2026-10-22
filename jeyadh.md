代发 wailian999

openssl rand -hex 16
来源：http://dali.sxryk.cn/Article/details/gtspltrngc.html

[R68] 计算文件校验值
来源：http://dali.zhixingplan.top/Article/details/gttwshaopg.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.nanxinkj.top/Article/details/gtgngwqtao.html

[R69] 生成随机密码
来源：http://dali.zdqjudy.top/Article/details/gttibxfajw.html

head -c 16 /dev/urandom | base64
来源：http://dali.chenjidiqi.icu/Article/details/gtokrubcuv.html

[R70] 时间戳与互转
来源：http://dali.nwbrower.top/Article/details/gtnwzlzppq.html

date +%s;  date -d @1700000000
来源：http://dali.shuidangran.top/Article/details/gtitwquatl.html

[R71] 日期格式化
来源：http://dali.zhaomingkeji.xyz/Article/details/gttioqfkrc.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.sweek.top/Article/details/gtxbrygacc.html

[R72] 等待端口就绪
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnzhhjrap.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.jinqigufen.top/Article/details/gteczidpfp.html

[R73] 分割大日志
来源：http://dali.hywenlv.cn/Article/details/gtuloxggyy.html

split -l 1000 big.log part_
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsepojlyl.html

[R74] 批量重命名
来源：http://dali.ppjwa.cn/Article/details/gtiqorqjrj.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.fengsongda.top/Article/details/gtzkkawgbu.html

[R75] 导出环境变量
来源：http://dali.havefunace.top/Article/details/gtahalzjfq.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.cashguo.top/Article/details/gtankmrgps.html

[R76] 使用临时文件
来源：http://dali.smart0.xyz/Article/details/gttxnbntcs.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.ydzc1.top/Article/details/gtahsoeynu.html

[R77] 读取用户输入
来源：http://dali.smart0.xyz/Article/details/gttzdarzcv.html

read -rp "请输入: " ans
来源：http://dali.smart0.xyz/Article/details/gtucoaucvy.html

[R78] 交互式菜单
来源：http://dali.aibaodan.cn/Article/details/gtbyknvqdy.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.iojbl.cn/Article/details/gtzuvspozd.html

[R79] 解析命令行选项
来源：http://dali.pengpengdd.cyou/Article/details/gtdrvetlcy.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.dashuyun.cn/Article/details/gttnpxonwz.html

[R80] 查看脚本执行耗时
来源：http://dali.cucudq.cn/Article/details/gtaujikvbe.html

time ./run.sh
来源：http://dali.kuanghao11.cn/Article/details/gtxkrbjepi.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtdvmvsmwa.html

S. C / C++ 专题
来源：http://dali.zhengqikj.top/Article/details/gtecrpqvoo.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtwodbqgxg.html

[S01] C：Hello World
来源：http://dali.ybcxt.top/Article/details/gtixshzmxn.html

#include <stdio.h>
来源：http://dali.smart0.xyz/Article/details/gtwlovlrmk.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.chenzaomai.com/Article/details/gtpifprlly.html

[S02] C：变量与格式化输出
来源：http://dali.bjfxy.top/Article/details/gtoxbeazem.html

int a = 10; printf("%d\n", a);
来源：http://dali.yuanzhike.top/Article/details/gtapwozyal.html

[S03] C：读入整数
来源：http://dali.xylfe.cn/Article/details/gtzehynawq.html

int x; scanf("%d", &x);
来源：http://dali.kuanghao11.cn/Article/details/gtfwjxoidx.html

[S04] C：字符串复制
来源：http://dali.jlsjyb.cn/Article/details/gtpaazqrpg.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.jqgufenzy.top/Article/details/gtetucnjpe.html

[S05] C：字符串长度
来源：http://dali.jinqigfzy.top/Article/details/gtkrmvkyly.html

strlen(s)
来源：http://dali.mhx1999.top/Article/details/gtxmjfjfpa.html

[S06] C：字符串比较
来源：http://dali.9152youxi.cn/Article/details/gtiqvaqciu.html

strcmp(a, b) == 0
来源：http://dali.yj202588.top/Article/details/gtimijjtpg.html

[S07] C：数组遍历求和
来源：http://dali.ivvv.top/Article/details/gtydvxabmi.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.tian-w.cn/Article/details/gtuehbkbrn.html

[S08] C：动态内存分配与释放
来源：http://dali.ivvv.top/Article/details/gtbhypduzy.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.hammf.cn/Article/details/gtjspuchal.html

[S09] C：结构体定义与初始化
来源：http://dali.vqdsnc.cn/Article/details/gtllkigcss.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.ivvv.top/Article/details/gtwrqlrlaj.html

[S10] C：指针与解引用
来源：http://dali.cqqwz.cn/Article/details/gtkkambmpu.html

int *p = &a;  *p = 5;
来源：http://dali.hammf.cn/Article/details/gtgdllpzls.html

[S11] C：逐行读文件
来源：http://dali.andypj.xyz/Article/details/gtbsxwvuvo.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpijljbms.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.ehwqpu.com/Article/details/gtqhweoepn.html

fclose(f);
来源：http://dali.yj20258.top/Article/details/gtndewqmcw.html

[S12] C：写文件
来源：http://dali.c1oappe.top/Article/details/gtcbleauqz.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gtoceagsxf.html

[S13] C：宏定义
来源：http://dali.hysaishi.cn/Article/details/gtdrfydsqr.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.jinqigufen.top/Article/details/gttefidafr.html

[S14] C：枚举
来源：http://dali.c1oappe.top/Article/details/gtsrksbicy.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.cdnleiting.top/Article/details/gtfibveqqz.html

[S15] C：类型转换
来源：http://dali.zycfv.cn/Article/details/gtjvlczmsm.html

(double) a / b
来源：http://dali.guowangkeji.top/Article/details/gtxnhzvnpq.html

[S16] C：位操作置位
来源：http://dali.kuanghao11.cn/Article/details/gtggkmllxv.html

x |= (1 << 3);
来源：http://dali.zhengqikj.top/Article/details/gtstymbvps.html

[S17] C：安全拼接字符串
来源：http://dali.andypj.xyz/Article/details/gtcovbvike.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.shangyingyoupin.top/Article/details/gtilvvbfyh.html

[S18] C：命令行参数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdnlphdge.html

int main(int argc, char **argv)
来源：http://dali.gotoacloud.top/Article/details/gttnhepzas.html

[S19] C：快速排序
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcwrtzgtx.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhoulong.xyz/Article/details/gtrixbhfqj.html

[S20] C：二分查找
来源：http://dali.yj202588.top/Article/details/gthgnhzgpy.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhoulong.xyz/Article/details/gthhvysmqf.html

[S21] C：字符类别判断
来源：http://dali.kuanghao11.cn/Article/details/gtlycbgjfr.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.gogol.net.cn/Article/details/gtfxpcevjp.html

[S22] C：字符串转数字
来源：http://dali.fzhhl.top/Article/details/gtzpszzljg.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.kuanghao11.cn/Article/details/gtqchuykyc.html

[S23] C：随机数
来源：http://dali.chenzaomai.com/Article/details/gtuardzlwa.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.hammf.cn/Article/details/gtgljlasqw.html

[S24] C：获取本地时间
来源：http://dali.tian-w.cn/Article/details/gthenqtorc.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.smart0.xyz/Article/details/gtswvbczhr.html

[S25] C：内存拷贝
来源：http://dali.fzhhl.top/Article/details/gtyfojsnll.html

memcpy(dst, src, n);
来源：http://dali.wangdashe.top/Article/details/gtbfahkgoy.html

[S26] C：内存清零
来源：http://dali.jianghu66.top/Article/details/gtvavqvbre.html

memset(a, 0, sizeof a);
来源：http://dali.cheryme.top/Article/details/gtfmuzjsdn.html

[S27] C：定义常量
来源：http://dali.smart0.xyz/Article/details/gtjnqgsbka.html

const double PI = 3.14159;
来源：http://dali.aizwys.cn/Article/details/gtcsyudvur.html

[S28] C：静态变量
来源：http://dali.yongpay.top/Article/details/gtzrtfqjcm.html

static int counter = 0;
来源：http://dali.zhongyouzk.top/Article/details/gtbuvmeosr.html

[S29] C：变参函数
来源：http://dali.gaohongyu789.top/Article/details/gtdwklioqx.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.0kj1m.cn/Article/details/gtcrxrjutw.html

[S30] C：头文件保护
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgqcgsvmh.html

#ifndef X_H
来源：http://dali.nwbrower.top/Article/details/gtfqehhwyd.html

#define X_H
来源：http://dali.hywenlv.cn/Article/details/gtstgvahld.html

#endif
来源：http://dali.xuetiantiany.cn/Article/details/gtjcjqkzwn.html

[S31] C++：Hello World
来源：http://dali.iojbl.cn/Article/details/gtimevavmj.html

#include <iostream>
来源：http://dali.chenjidiqi.icu/Article/details/gtozebwigx.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.jqgufenzy.top/Article/details/gthlhcpuwz.html

[S32] C++：字符串
来源：http://dali.xziqi.cn/Article/details/gtpuumgrzj.html

std::string s = "hi";  s += "!";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqfkylrvc.html

[S33] C++：vector 增删
来源：http://dali.jqgfzy.top/Article/details/gtzdipznha.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhengqikj.top/Article/details/gtdajgtvuk.html

[S34] C++：遍历 vector
来源：http://dali.yj20258.top/Article/details/gtmvjfksdl.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.cheryme.top/Article/details/gtbahjhrzc.html

[S35] C++：map
来源：http://dali.gogol.net.cn/Article/details/gtlfwnseyr.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhoulong.xyz/Article/details/gttyamzglp.html

[S36] C++：unordered_map
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaqxmwkah.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jyoumei.cn/Article/details/gtywrrxleh.html

[S37] C++：set
来源：http://dali.vqdsnc.cn/Article/details/gtrqdwowfg.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.gogol.net.cn/Article/details/gtsjgjtzmk.html

[S38] C++：排序
来源：http://dali.yonumen.top/Article/details/gtccgcultq.html

std::sort(v.begin(), v.end());
来源：http://dali.shzxlz.cn/Article/details/gtyeppejee.html

[S39] C++：自定义比较器排序
来源：http://dali.wangdashe.top/Article/details/gtdahgrjel.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.yj202588.top/Article/details/gtmjxwcqmg.html

[S40] C++：查找元素
来源：http://dali.yonumen.top/Article/details/gtpgnvocwa.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.hnxiangtu.top/Article/details/gtrddrcyju.html

[S41] C++：类与构造函数
来源：http://dali.tianlin.xyz/Article/details/gtjxcfzhcn.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.andypj.xyz/Article/details/gtoflufnee.html

[S42] C++：继承与虚函数
来源：http://dali.cheryme.top/Article/details/gtuszybhdt.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhoulong.xyz/Article/details/gtmvhhogkq.html

[S43] C++：智能指针
来源：http://dali.9152youxi.cn/Article/details/gttrzxlxgv.html

auto p = std::make_unique<int>(5);
来源：http://dali.shuidangran.top/Article/details/gtpdwrqjhf.html

[S44] C++：引用传参
来源：http://dali.c1oappe.top/Article/details/gtrzzqqpyj.html

void inc(int &x) { ++x; }
来源：http://dali.jinqigufen.top/Article/details/gtfkqojyjw.html

[S45] C++：lambda
来源：http://dali.hammf.cn/Article/details/gtdapwciwa.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.havefunace.top/Article/details/gteekdqdqn.html

[S46] C++：函数模板
来源：http://dali.tianlin.xyz/Article/details/gtavbkxbpx.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.pycfn.com/Article/details/gteoddfarl.html

[S47] C++：结构化绑定遍历
来源：http://dali.aizwys.cn/Article/details/gtglvobkxx.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.wangshuangyany.cn/Article/details/gthtmidlid.html

[S48] C++：逐行读文件
来源：http://dali.yj202588.top/Article/details/gtvpmpilhr.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.pengpengdd.cyou/Article/details/gticthapvi.html

while (std::getline(in, line)) { }
来源：http://dali.xziqi.cn/Article/details/gtlylzzair.html

[S49] C++：写文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbslodfbj.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.feifeiyinyue.top/Article/details/gtmftfdyda.html

[S50] C++：格式化数字
来源：http://dali.yuanzhike.top/Article/details/gtqflrnncg.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.c1oappe.top/Article/details/gtzuwghclh.html

[S51] C++：显式类型转换
来源：http://dali.redwolf501.top/Article/details/gttzheutrx.html

static_cast<double>(a) / b
来源：http://dali.ivvv.top/Article/details/gtowqfjdbn.html

[S52] C++：const 与 noexcept
来源：http://dali.zhoulong.xyz/Article/details/gtmlikyznl.html

int size() const noexcept { return n_; }
来源：http://dali.sxryk.cn/Article/details/gtvsntpxju.html

[S53] C++：移动语义
来源：http://dali.yvedp.cn/Article/details/gtnykwrkeq.html

std::vector<int> w = std::move(v);
来源：http://dali.havefunace.top/Article/details/gtqknojsvz.html

[S54] C++：异常处理
来源：http://dali.tianlin.xyz/Article/details/gtwvaqwmwk.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.gzhubu.top/Article/details/gtzsepjiep.html

[S55] C++：结构化绑定
来源：http://dali.xinyue.icu/Article/details/gtmvhhrlyx.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.snrcjt.cn/Article/details/gtnnsxsfcn.html

[S56] C++：optional
来源：http://dali.ydzc1.top/Article/details/gtaczudfar.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.gzhubu.top/Article/details/gtznlxitxt.html

[S57] C++：编译期常量
来源：http://dali.jqgfzy.top/Article/details/gtrcwpzlfm.html

constexpr int N = 10;
来源：http://dali.cheryme.top/Article/details/gtuwnqdsiw.html

[S58] C++：命名空间
来源：http://dali.ppjwa.cn/Article/details/gtzbxijgon.html

namespace ns { int f() { return 1; } }
来源：http://dali.tian-w.cn/Article/details/gtkjzkrygr.html

[S59] C++：静态断言
来源：http://dali.dianchejie.cn/Article/details/gtrdqzilxo.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.cdnleiting.top/Article/details/gtqcnjaxlx.html

[S60] C++：遍历并删除元素
来源：http://dali.hammf.cn/Article/details/gtusuulxfu.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.mhx1999.top/Article/details/gtohlhsiyi.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtgtpuyfhi.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.hywenlv.cn/Article/details/gtzztsaawn.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtxetdoiyx.html

[T01] Kotlin：Hello World
来源：http://dali.tianlin.xyz/Article/details/gtyfhngvhi.html

println("Hello")
来源：http://dali.iojbl.cn/Article/details/gtimfjlosc.html

[T02] Kotlin：变量
来源：http://dali.hnxiangtu.top/Article/details/gtcsmeimgr.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gtsnztcqyq.html

[T03] Kotlin：字符串模板
来源：http://dali.yonumen.top/Article/details/gtzjxoglkn.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gtgwfhacgp.html

[T04] Kotlin：空安全
来源：http://dali.smart0.xyz/Article/details/gtfsmfkwka.html

val n: String? = null;  n?.length
来源：http://dali.quarkkingdee.top/Article/details/gthunyxove.html

[T05] Kotlin：when 表达式
来源：http://dali.yj20258888.top/Article/details/gtutzyzwyg.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.birdmap.top/Article/details/gtqlaiysfc.html

[T06] Kotlin：集合映射
来源：http://dali.yuxming.cn/Article/details/gtjrqunlbo.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.birdmap.top/Article/details/gtywdgksnp.html

[T07] Kotlin：集合过滤
来源：http://dali.tanke756.top/Article/details/gtvyryktmo.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.jqgufenzy.top/Article/details/gtoylcloqt.html

[T08] Kotlin：数据类
来源：http://dali.yvedp.cn/Article/details/gtmkkmnsiq.html

data class User(val name: String, val age: Int)
来源：http://dali.iojbl.cn/Article/details/gtisjbwzme.html

[T09] Kotlin：扩展函数
来源：http://dali.hywenlv.cn/Article/details/gteoxhrgdj.html

fun String.exclaim() = this + "!"
来源：http://dali.nwbrower.top/Article/details/gtdthgniag.html

[T10] Kotlin：默认参数
来源：http://dali.svipenyu.cn/Article/details/gturnaaesh.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.yongpay.top/Article/details/gtjkjgaasp.html

[T11] Kotlin：协程
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfqgvlrzl.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.bjfxy.top/Article/details/gtsovgbhwf.html

[T12] Kotlin：解构声明
来源：http://dali.yuxming.cn/Article/details/gtiimkwrpa.html

val (a, b) = Pair(1, 2)
来源：http://dali.chenzaomai.com/Article/details/gtpgxwvbyl.html

[T13] Kotlin：只读 Map
来源：http://dali.cqqwz.cn/Article/details/gtcpukitnp.html

val m = mapOf("a" to 1)
来源：http://dali.0kj1m.cn/Article/details/gtowvctcth.html

[T14] Kotlin：循环
来源：http://dali.sysykeji.top/Article/details/gtaukxbyol.html

for (i in 1..10) println(i)
来源：http://dali.jinqigufen.top/Article/details/gtqutwqlto.html

[T15] Kotlin：接口
来源：http://dali.bjfxy.top/Article/details/gtijvabedb.html

interface Shape { fun area(): Double }
来源：http://dali.jqgufenzy.top/Article/details/gtabtutoym.html

[T16] Swift：Hello World
来源：http://dali.birdmap.top/Article/details/gtectqhiwk.html

print("Hello")
来源：http://dali.jinqigufen.top/Article/details/gtnikfmpki.html

[T17] Swift：变量与常量
来源：http://dali.guannengcc.top/Article/details/gtbfvkmhbp.html

var a = 1;  let b = 2
来源：http://dali.zhiwuduotai.top/Article/details/gteqstwhhl.html

[T18] Swift：字符串插值
来源：http://dali.hysaishi.cn/Article/details/gtkvlldcjd.html

"值: \(b)"
来源：http://dali.9152youxi.cn/Article/details/gtlwccunfk.html

[T19] Swift：可选绑定
来源：http://dali.zhixingplan.top/Article/details/gtaazclpvk.html

if let n = opt { print(n) }
来源：http://dali.bjfxy.top/Article/details/gthrgjsgqx.html

[T20] Swift：数组操作
来源：http://dali.shangyingyoupin.top/Article/details/gtrntysiyv.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.jinghuilouyu.cn/Article/details/gtcmwqdvdu.html

[T21] Swift：遍历
来源：http://dali.sysykeji.top/Article/details/gtgkxxwzex.html

for x in a { print(x) }
来源：http://dali.pycfn.com/Article/details/gtsmftvryk.html

[T22] Swift：字典
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxqaarped.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.daria6918.cn/Article/details/gtespzgxsa.html

[T23] Swift：函数
来源：http://dali.yj202588.top/Article/details/gtqutefxhi.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.xuetiantiany.cn/Article/details/gtsgidfqen.html

[T24] Swift：闭包
来源：http://dali.cdnleiting.top/Article/details/gtgspruvru.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.fengsongda.top/Article/details/gtqjtslyqs.html

[T25] Swift：结构体
来源：http://dali.9152youxi.cn/Article/details/gtxwxnfknl.html

struct P { var x: Int }
来源：http://dali.jinghuilouyu.cn/Article/details/gtplytlpqo.html

[T26] Swift：类与重写
来源：http://dali.gogol.net.cn/Article/details/gtjplolsaz.html

class A: Base { override func f() {} }
来源：http://dali.ydzc1.top/Article/details/gtwahdpeym.html

[T27] Swift：错误处理
来源：http://dali.sysykeji.top/Article/details/gtxcqmfzix.html

do { try f() } catch { print(error) }
来源：http://dali.chenzaomai.com/Article/details/gtizwwfkaq.html

[T28] Swift：枚举
来源：http://dali.pengpengdd.cyou/Article/details/gtkuwvuhyw.html

enum Color { case red, green }
来源：http://dali.chenlongwang.top/Article/details/gtlqdvzozg.html

[T29] Swift：guard 提前返回
来源：http://dali.yuanzhike.top/Article/details/gtuqpvburn.html

guard let x = opt else { return }
来源：http://dali.ydzc1.top/Article/details/gtdreedtlo.html

[T30] Swift：协议
来源：http://dali.chenjidiqi.icu/Article/details/gtjhrlgtri.html

protocol Shape { func area() -> Double }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtekqcxfbx.html

[T31] Lua：Hello World
来源：http://dali.gaohongyu789.top/Article/details/gthfycywzu.html

print("Hello")
来源：http://dali.dianchejie.cn/Article/details/gtcfahhevd.html

[T32] Lua：局部变量
来源：http://dali.dashuyun.cn/Article/details/gtyztfogqi.html

local a = 1
来源：http://dali.jinyuanbaomall.cn/Article/details/gtghmtjees.html

[T33] Lua：表（数组）
来源：http://dali.havefunace.top/Article/details/gtpmnruysg.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.meibo888.top/Article/details/gttxhmomij.html

[T34] Lua：遍历表
来源：http://dali.ywan-chungtsiang.top/Article/details/gtchahmhjd.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.xylfe.cn/Article/details/gtuecksyhv.html

[T35] Lua：字典表
来源：http://dali.yj202588.top/Article/details/gtikbodasu.html

local d = { a = 1 };  d.b = 2
来源：http://dali.cdnleiting.top/Article/details/gtefpurwlp.html

[T36] Lua：函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfrfntpgb.html

function add(a, b) return a + b end
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlpcmtulv.html

[T37] Lua：字符串拼接
来源：http://dali.yj20258.top/Article/details/gtiblmpihm.html

"a" .. "b"
来源：http://dali.gogol.net.cn/Article/details/gtjwrxqjfe.html

[T38] Lua：条件
来源：http://dali.dianchejie.cn/Article/details/gtymozuwbz.html

if x > 0 then print("正") end
来源：http://dali.wangshuangyany.cn/Article/details/gtshrfsaai.html

[T39] Lua：模式匹配
来源：http://dali.hfpthk.cn/Article/details/gtlvcwkwbj.html

string.find(s, "%d+")
来源：http://dali.hnxiangtu.top/Article/details/gtitxeybxb.html

[T40] Lua：元表
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwewsaxed.html

setmetatable({}, { __index = base })
来源：http://dali.shangyingyoupin.top/Article/details/gtbsnzosvf.html

[T41] Perl：Hello World
来源：http://dali.hywenlv.cn/Article/details/gtnjokrnye.html

print "Hello\n";
来源：http://dali.ppjwa.cn/Article/details/gtvwttyztt.html

[T42] Perl：变量类型
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfdizeuoy.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.mhx1999.top/Article/details/gttmlbzqxk.html

[T43] Perl：字符串插值
来源：http://dali.haohaochexian.top/Article/details/gtobadukxd.html

"值: $a"
来源：http://dali.svipenyu.cn/Article/details/gtwiakzyfe.html

[T44] Perl：条件
来源：http://dali.yuxming.cn/Article/details/gtvlkoymwf.html

if ($a > 0) { print "正"; }
来源：http://dali.jqgfzy.top/Article/details/gtzbocqjgx.html

[T45] Perl：数组遍历
来源：http://dali.sweek.top/Article/details/gtvgfhlpga.html

for my $x (@arr) { print $x; }
来源：http://dali.dianchejie.cn/Article/details/gttjbxskbf.html

[T46] Perl：哈希操作
来源：http://dali.chenjidiqi.icu/Article/details/gtydtfysbw.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.aibaodan.cn/Article/details/gtdqtqpwii.html

[T47] Perl：正则捕获
来源：http://dali.jinyuanbaomall.cn/Article/details/gticyltzxq.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.ivvv.top/Article/details/gtlirjfaum.html

[T48] Perl：正则替换
来源：http://dali.shangyingyoupin.top/Article/details/gtiayosuiq.html

$s =~ s/old/new/g;
来源：http://dali.wangshuangyany.cn/Article/details/gtyianrmwk.html

[T49] Perl：函数
来源：http://dali.aizwys.cn/Article/details/gtbsoalqwl.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.smart0.xyz/Article/details/gtcyinvjwa.html

[T50] Perl：逐行读文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaxfsuqgy.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.9152youxi.cn/Article/details/gtnfeycmop.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.gaohongyu789.top/Article/details/gtcrthynaq.html

[T51] Scala：Hello World
来源：http://dali.birdmap.top/Article/details/gtfrterjvj.html

println("Hello")
来源：http://dali.zhongyouzk.top/Article/details/gtjurzowjn.html

[T52] Scala：变量
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrvxdoetv.html

val a = 1;  var b = 2
来源：http://dali.hammf.cn/Article/details/gtlppdkufg.html

[T53] Scala：字符串插值
来源：http://dali.bjfxy.top/Article/details/gtztixnwnw.html

s"值: $b"
来源：http://dali.sxryk.cn/Article/details/gtudzecyvh.html

[T54] Scala：集合映射
来源：http://dali.cdnleiting.top/Article/details/gtcgdtkgrc.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.snrcjt.cn/Article/details/gtqkpeigza.html

[T55] Scala：集合过滤
来源：http://dali.chenjidiqi.icu/Article/details/gtbbqqwmum.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.yuxming.cn/Article/details/gtopgtniai.html

[T56] Scala：样例类
来源：http://dali.shanyushiyangtech.top/Article/details/gthkoxldxc.html

case class User(name: String, age: Int)
来源：http://dali.shangyingyoupin.top/Article/details/gtbzipjyhu.html

[T57] Scala：模式匹配
来源：http://dali.wangdashe.top/Article/details/gtiymxyieb.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.tanke756.top/Article/details/gtvbrtquzx.html

[T58] Scala：函数定义
来源：http://dali.snrcjt.cn/Article/details/gtlpuzeihn.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.kuanghao11.cn/Article/details/gtjgxxyudv.html

[T59] Scala：循环
来源：http://dali.316326.xyz/Article/details/gtpzysabdg.html

for (i <- 1 to 10) println(i)
来源：http://dali.jyoumei.cn/Article/details/gtsevjfnkb.html

[T60] Scala：折叠
来源：http://dali.hnxiangtu.top/Article/details/gtbskzazoe.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.sxryk.cn/Article/details/gtbmrrkugr.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpbvoxpts.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.jiagoushi.top/Article/details/gttjgmktvj.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gthxfmsain.html

[U01] Py：创建虚拟环境
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpghybcyv.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.guannengcc.top/Article/details/gtjxmpxxbt.html

[U02] Py：导出 / 安装依赖
来源：http://dali.cucudq.cn/Article/details/gthukgjsmb.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.redwolf501.top/Article/details/gtugjgazsr.html

[U03] Py：加载 .env 配置
来源：http://dali.guowangkeji.top/Article/details/gtvsbfjmjt.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.jianghu66.top/Article/details/gtvwnjlhaw.html

[U04] Py：变量调试打印
来源：http://dali.zhixingplan.top/Article/details/gtnnyxlfqs.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.smart0.xyz/Article/details/gtgtpmlymb.html

[U05] Py：列表去重且保序
来源：http://dali.ybcxt.top/Article/details/gtjdeaophc.html

list(dict.fromkeys(arr))
来源：http://dali.mhx1999.top/Article/details/gtfxewmrof.html

[U06] Py：合并两个字典
来源：http://dali.fengsongda.top/Article/details/gtthavmgej.html

{**a, **b}
来源：http://dali.sweek.top/Article/details/gtxktoxtpm.html

[U07] Py：反转字典键值
来源：http://dali.sufxvd.cn/Article/details/gtszwwdnhl.html

{v: k for k, v in d.items()}
来源：http://dali.iojbl.cn/Article/details/gtojukrfua.html

[U08] Py：展平二维列表
来源：http://dali.vqdsnc.cn/Article/details/gtgcwjkzdq.html

[y for x in nested for y in x]
来源：http://dali.shzxlz.cn/Article/details/gtgpljzcvm.html


<!-- 参考信息 -->