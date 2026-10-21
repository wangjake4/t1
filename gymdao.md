代发 wailian999

free -h;  ps aux | grep nginx
来源：http://dali.cheryme.top/Article/details/gtulnolvgn.html

[R64] 结束进程
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqmqkfxqr.html

kill -9 $(pgrep -f app.py)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtngmgsuks.html

[R65] 查看端口占用
来源：http://dali.dashuyun.cn/Article/details/gtabxfdagn.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.wangshuangyany.cn/Article/details/gtoguvipsf.html

[R66] 定时任务
来源：http://dali.pycfn.com/Article/details/gtpohlyedy.html

crontab -e;  crontab -l
来源：http://dali.shangyingyoupin.top/Article/details/gtkhxyfeng.html

[R67] 生成随机十六进制串
来源：http://dali.dianchejie.cn/Article/details/gtjmgwjype.html

openssl rand -hex 16
来源：http://dali.9152youxi.cn/Article/details/gtaxnenugh.html

[R68] 计算文件校验值
来源：http://dali.gaohongyu789.top/Article/details/gtyeoczvvs.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.pycfn.com/Article/details/gtnovznpzb.html

[R69] 生成随机密码
来源：http://dali.gzhubu.top/Article/details/gtyyskpklj.html

head -c 16 /dev/urandom | base64
来源：http://dali.ehwqpu.com/Article/details/gtkahqjqil.html

[R70] 时间戳与互转
来源：http://dali.ivvv.top/Article/details/gtjxefwdfg.html

date +%s;  date -d @1700000000
来源：http://dali.chenjidiqi.icu/Article/details/gtduqytfvx.html

[R71] 日期格式化
来源：http://dali.jinqigufen.top/Article/details/gtqowtzbms.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.shzxlz.cn/Article/details/gtwrkwiikq.html

[R72] 等待端口就绪
来源：http://dali.daria6918.cn/Article/details/gtgddhnown.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.daxiang520.top/Article/details/gtgxrrybjr.html

[R73] 分割大日志
来源：http://dali.gogol.net.cn/Article/details/gtrnkhrdce.html

split -l 1000 big.log part_
来源：http://dali.daria6918.cn/Article/details/gtywyujdvb.html

[R74] 批量重命名
来源：http://dali.vqdsnc.cn/Article/details/gtvhdleqmf.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.xuetiantiany.cn/Article/details/gtmoutahru.html

[R75] 导出环境变量
来源：http://dali.gotoacloud.top/Article/details/gtarzsonrg.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.mhx1999.top/Article/details/gtffrpvtvu.html

[R76] 使用临时文件
来源：http://dali.cheryme.top/Article/details/gtgfyfhrwi.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.haohaochexian.top/Article/details/gtkhvaoafr.html

[R77] 读取用户输入
来源：http://dali.redwolf501.top/Article/details/gtzzfuudiz.html

read -rp "请输入: " ans
来源：http://dali.chenlongwang.top/Article/details/gtdkjgboxq.html

[R78] 交互式菜单
来源：http://dali.chenjidiqi.icu/Article/details/gtzznymwiq.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.sweek.top/Article/details/gtgwziiqzk.html

[R79] 解析命令行选项
来源：http://dali.redwolf501.top/Article/details/gtrhcdruxl.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.andypj.xyz/Article/details/gtxvmfevrz.html

[R80] 查看脚本执行耗时
来源：http://dali.zhongyouzk.top/Article/details/gtyggimbts.html

time ./run.sh
来源：http://dali.hammf.cn/Article/details/gtvpmruqaq.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtzizgcmfd.html

S. C / C++ 专题
来源：http://dali.xylfe.cn/Article/details/gtikvpbvft.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtaligumlh.html

[S01] C：Hello World
来源：http://dali.nanxuanxn.top/Article/details/gtkqozkfhc.html

#include <stdio.h>
来源：http://dali.jiagoushi.top/Article/details/gtsprecrjx.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.sysykeji.top/Article/details/gthjykoaoj.html

[S02] C：变量与格式化输出
来源：http://dali.zycfv.cn/Article/details/gtlxybfpdi.html

int a = 10; printf("%d\n", a);
来源：http://dali.havefunace.top/Article/details/gtatjodqez.html

[S03] C：读入整数
来源：http://dali.ybcxt.top/Article/details/gtcsjklmyh.html

int x; scanf("%d", &x);
来源：http://dali.shzxlz.cn/Article/details/gtwuzqvzjb.html

[S04] C：字符串复制
来源：http://dali.cqqwz.cn/Article/details/gtxprwdfdd.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.yj20258888.top/Article/details/gtkhaccuoa.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gtgagbkcub.html

strlen(s)
来源：http://dali.guannengcc.top/Article/details/gtfdnpubrc.html

[S06] C：字符串比较
来源：http://dali.cashguo.top/Article/details/gtvhbroukm.html

strcmp(a, b) == 0
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaixfussz.html

[S07] C：数组遍历求和
来源：http://dali.zhiwuduotai.top/Article/details/gtcvpptzpp.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.jinghuilouyu.cn/Article/details/gtfvdldrcx.html

[S08] C：动态内存分配与释放
来源：http://dali.yj20258.top/Article/details/gtokhghcxd.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.yueranfly.top/Article/details/gtxkieuipp.html

[S09] C：结构体定义与初始化
来源：http://dali.jinqigufen.top/Article/details/gtocrnayli.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.vqdsnc.cn/Article/details/gtdiznqgiv.html

[S10] C：指针与解引用
来源：http://dali.c1oappe.top/Article/details/gtekguwnjd.html

int *p = &a;  *p = 5;
来源：http://dali.yangfankeji.com/Article/details/gtldzwdpqa.html

[S11] C：逐行读文件
来源：http://dali.yonumen.top/Article/details/gtxlqxftey.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.ehwqpu.com/Article/details/gtnudrhylo.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.nanxinkj.top/Article/details/gtizojicxw.html

fclose(f);
来源：http://dali.aizwys.cn/Article/details/gtewqswkkv.html

[S12] C：写文件
来源：http://dali.ppjwa.cn/Article/details/gtteagsamf.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.jinghuilouyu.cn/Article/details/gtutpqoqio.html

[S13] C：宏定义
来源：http://dali.fzhhl.top/Article/details/gthjnwshya.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.jyoumei.cn/Article/details/gtpivgjeyw.html

[S14] C：枚举
来源：http://dali.zhiwuduotai.top/Article/details/gtgckwwvso.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.hfpthk.cn/Article/details/gtkzinrvqv.html

[S15] C：类型转换
来源：http://dali.jianghu66.top/Article/details/gtrenaicrg.html

(double) a / b
来源：http://dali.wangshuangyany.cn/Article/details/gtkmbpfqhq.html

[S16] C：位操作置位
来源：http://dali.ybcxt.top/Article/details/gtpfozfbyu.html

x |= (1 << 3);
来源：http://dali.bjfxy.top/Article/details/gtpklbrxtc.html

[S17] C：安全拼接字符串
来源：http://dali.yueranfly.top/Article/details/gtobsclile.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.ivvv.top/Article/details/gtzrkiolsk.html

[S18] C：命令行参数
来源：http://dali.smart0.xyz/Article/details/gtgsmulcuv.html

int main(int argc, char **argv)
来源：http://dali.xinyue.icu/Article/details/gtkfgogpwr.html

[S19] C：快速排序
来源：http://dali.hysaishi.cn/Article/details/gtqwgxvvdd.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.cheryme.top/Article/details/gtzoxhhgha.html

[S20] C：二分查找
来源：http://dali.kuanghao11.cn/Article/details/gtpflmeraf.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.birdmap.top/Article/details/gtzkpfhqjn.html

[S21] C：字符类别判断
来源：http://dali.hnqzz.top/Article/details/gtgglcmxgk.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.c1oappe.top/Article/details/gthpxjaota.html

[S22] C：字符串转数字
来源：http://dali.9152youxi.cn/Article/details/gtfbjxzeuf.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.xuanzx.com/Article/details/gtblshzgnn.html

[S23] C：随机数
来源：http://dali.birdmap.top/Article/details/gtjcruztsa.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.guannengcc.top/Article/details/gtcyzzfyze.html

[S24] C：获取本地时间
来源：http://dali.dianchejie.cn/Article/details/gtycdqbxtj.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.jyoumei.cn/Article/details/gtafhcnglc.html

[S25] C：内存拷贝
来源：http://dali.ywan-chungtsiang.top/Article/details/gtttxorzvt.html

memcpy(dst, src, n);
来源：http://dali.yj20258888.top/Article/details/gtnvnzurlr.html

[S26] C：内存清零
来源：http://dali.chenjidiqi.icu/Article/details/gthcmjjwcf.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gtntbtpfcq.html

[S27] C：定义常量
来源：http://dali.shangyingyoupin.top/Article/details/gtkgktpmna.html

const double PI = 3.14159;
来源：http://dali.mhx1999.top/Article/details/gtzuwueyea.html

[S28] C：静态变量
来源：http://dali.cheryme.top/Article/details/gttrcyvzhs.html

static int counter = 0;
来源：http://dali.haohaochexian.top/Article/details/gtahypmnud.html

[S29] C：变参函数
来源：http://dali.hnqzz.top/Article/details/gtzuolaytf.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.shuidangran.top/Article/details/gtavjiddrw.html

[S30] C：头文件保护
来源：http://dali.xylfe.cn/Article/details/gtxftkpahs.html

#ifndef X_H
来源：http://dali.hfpthk.cn/Article/details/gtnjewfmlf.html

#define X_H
来源：http://dali.cashguo.top/Article/details/gtnojkdsup.html

#endif
来源：http://dali.fzhhl.top/Article/details/gtctrdhhuf.html

[S31] C++：Hello World
来源：http://dali.guowangkeji.top/Article/details/gtuohrkqgg.html

#include <iostream>
来源：http://dali.cdnleiting.top/Article/details/gtiiehmtjl.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.shangyingyoupin.top/Article/details/gtiokdzptx.html

[S32] C++：字符串
来源：http://dali.sufxvd.cn/Article/details/gtygmnawlw.html

std::string s = "hi";  s += "!";
来源：http://dali.hongshengwenyu.top/Article/details/gtgduazagm.html

[S33] C++：vector 增删
来源：http://dali.yj20258.top/Article/details/gtjiaxtoub.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.c1oappe.top/Article/details/gtflseobec.html

[S34] C++：遍历 vector
来源：http://dali.zycfv.cn/Article/details/gtymigwqda.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.hysaishi.cn/Article/details/gtuqmttknf.html

[S35] C++：map
来源：http://dali.yueranfly.top/Article/details/gtxxvvsdvz.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.quarkkingdee.top/Article/details/gtcnxluqdo.html

[S36] C++：unordered_map
来源：http://dali.wangshuangyany.cn/Article/details/gtbjwizzzb.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhiwuduotai.top/Article/details/gtknmaxrcv.html

[S37] C++：set
来源：http://dali.tianlin.xyz/Article/details/gtuzsucexj.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhongyouzk.top/Article/details/gtzctonwgs.html

[S38] C++：排序
来源：http://dali.cucudq.cn/Article/details/gtjkyqefwf.html

std::sort(v.begin(), v.end());
来源：http://dali.tanke756.top/Article/details/gtdsrgtxzs.html

[S39] C++：自定义比较器排序
来源：http://dali.iojbl.cn/Article/details/gttubilrdb.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.sysykeji.top/Article/details/gtsvdakarh.html

[S40] C++：查找元素
来源：http://dali.pengpengdd.cyou/Article/details/gtnallewme.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.ppjwa.cn/Article/details/gtwasangdd.html

[S41] C++：类与构造函数
来源：http://dali.fzhhl.top/Article/details/gtwxjamcyf.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.jinghuilouyu.cn/Article/details/gtemwshefi.html

[S42] C++：继承与虚函数
来源：http://dali.xziqi.cn/Article/details/gtvrmvfnad.html

class B : public Base { public: void f() override {} };
来源：http://dali.feifeiyinyue.top/Article/details/gthhjqlpen.html

[S43] C++：智能指针
来源：http://dali.guowangkeji.top/Article/details/gtsqareddk.html

auto p = std::make_unique<int>(5);
来源：http://dali.jinghuilouyu.cn/Article/details/gtedfyokez.html

[S44] C++：引用传参
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfklppwez.html

void inc(int &x) { ++x; }
来源：http://dali.cashguo.top/Article/details/gtiejpsghx.html

[S45] C++：lambda
来源：http://dali.hnxiangtu.top/Article/details/gtqegtzprz.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.pengpengdd.cyou/Article/details/gtnknukqpp.html

[S46] C++：函数模板
来源：http://dali.jinqigufen.top/Article/details/gtaddmfctb.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.fzhhl.top/Article/details/gtfujwgbfq.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhengqikj.top/Article/details/gthiycioiq.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.ivvv.top/Article/details/gtcndnytff.html

[S48] C++：逐行读文件
来源：http://dali.yj20258.top/Article/details/gtatbmegrq.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.meibo888.top/Article/details/gtgyoqfltc.html

while (std::getline(in, line)) { }
来源：http://dali.aizwys.cn/Article/details/gtnojvcmtd.html

[S49] C++：写文件
来源：http://dali.hnxiangtu.top/Article/details/gtnaelegjx.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.tianlin.xyz/Article/details/gtoscdbysw.html

[S50] C++：格式化数字
来源：http://dali.gotoacloud.top/Article/details/gtpccauhyf.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaxaixora.html

[S51] C++：显式类型转换
来源：http://dali.sweek.top/Article/details/gtnysqyqmb.html

static_cast<double>(a) / b
来源：http://dali.chenlongwang.top/Article/details/gtrnggwwbk.html

[S52] C++：const 与 noexcept
来源：http://dali.aibaodan.cn/Article/details/gtwqfkxqaq.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gtgfyuhtxg.html

[S53] C++：移动语义
来源：http://dali.zhengqikj.top/Article/details/gtgspjuoti.html

std::vector<int> w = std::move(v);
来源：http://dali.zhongyouzk.top/Article/details/gtigndetqb.html

[S54] C++：异常处理
来源：http://dali.haohaochexian.top/Article/details/gtdptkehdw.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.yj202588.top/Article/details/gteargvdsl.html

[S55] C++：结构化绑定
来源：http://dali.guannengcc.top/Article/details/gthpqkcibo.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.jinqigfzy.top/Article/details/gtxxlitybo.html

[S56] C++：optional
来源：http://dali.shzxlz.cn/Article/details/gtjhdkgnop.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.tianlin.xyz/Article/details/gtlimkysdb.html

[S57] C++：编译期常量
来源：http://dali.cdnleiting.top/Article/details/gtfvkyqlsn.html

constexpr int N = 10;
来源：http://dali.yj20258888.top/Article/details/gtarapuslw.html

[S58] C++：命名空间
来源：http://dali.yvedp.cn/Article/details/gttyhkxckq.html

namespace ns { int f() { return 1; } }
来源：http://dali.gaohongyu789.top/Article/details/gtcualalmd.html

[S59] C++：静态断言
来源：http://dali.svipenyu.cn/Article/details/gtpdgszfiz.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.xziqi.cn/Article/details/gtwfsvifhq.html

[S60] C++：遍历并删除元素
来源：http://dali.snrcjt.cn/Article/details/gtnsmormqf.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.snrcjt.cn/Article/details/gtlotxdwcx.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gttylchzlt.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmlowoezu.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtuaxfmeft.html

[T01] Kotlin：Hello World
来源：http://dali.hfpthk.cn/Article/details/gttpldfodp.html

println("Hello")
来源：http://dali.gzhubu.top/Article/details/gtqzgfxogn.html

[T02] Kotlin：变量
来源：http://dali.pycfn.com/Article/details/gtntcjhofc.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.yanxiufei.cn/Article/details/gtmgfrsopk.html

[T03] Kotlin：字符串模板
来源：http://dali.cdnleiting.top/Article/details/gtunkqvcpr.html

"值: $b"
来源：http://dali.yuanzhike.top/Article/details/gtpugbwufm.html

[T04] Kotlin：空安全
来源：http://dali.iojbl.cn/Article/details/gthaotspev.html

val n: String? = null;  n?.length
来源：http://dali.daxiang520.top/Article/details/gtjfifjnxy.html

[T05] Kotlin：when 表达式
来源：http://dali.yueranfly.top/Article/details/gtmzviirqs.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.yvedp.cn/Article/details/gthtfbfdpj.html

[T06] Kotlin：集合映射
来源：http://dali.yanxiufei.cn/Article/details/gttdggsfqe.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.jianghu66.top/Article/details/gtbcbgsemh.html

[T07] Kotlin：集合过滤
来源：http://dali.ehwqpu.com/Article/details/gtqvnqiazp.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.jianghu66.top/Article/details/gtrqrvsxvq.html

[T08] Kotlin：数据类
来源：http://dali.c1oappe.top/Article/details/gtscfppgui.html

data class User(val name: String, val age: Int)
来源：http://dali.zhixingplan.top/Article/details/gtbebovkeb.html

[T09] Kotlin：扩展函数
来源：http://dali.guowangkeji.top/Article/details/gtyvujhhhf.html

fun String.exclaim() = this + "!"
来源：http://dali.0kj1m.cn/Article/details/gtnmgfjtpa.html

[T10] Kotlin：默认参数
来源：http://dali.smart0.xyz/Article/details/gtuyxcvrqo.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.yj20258.top/Article/details/gtuqsmekhx.html

[T11] Kotlin：协程
来源：http://dali.daria6918.cn/Article/details/gtfbyfbjnw.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.cdnleiting.top/Article/details/gtadwciahu.html

[T12] Kotlin：解构声明
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgzfezpav.html

val (a, b) = Pair(1, 2)
来源：http://dali.feifeiyinyue.top/Article/details/gtqspuxagt.html

[T13] Kotlin：只读 Map
来源：http://dali.hongshengwenyu.top/Article/details/gtfafucvsr.html

val m = mapOf("a" to 1)
来源：http://dali.zhengqikj.top/Article/details/gtsmzggysy.html

[T14] Kotlin：循环
来源：http://dali.guannengcc.top/Article/details/gtyypmimmg.html

for (i in 1..10) println(i)
来源：http://dali.c1oappe.top/Article/details/gtvutavidg.html

[T15] Kotlin：接口
来源：http://dali.jinghuilouyu.cn/Article/details/gtclhkybjy.html

interface Shape { fun area(): Double }
来源：http://dali.sysykeji.top/Article/details/gtayzzfkhl.html

[T16] Swift：Hello World
来源：http://dali.birdmap.top/Article/details/gtlnpcradv.html

print("Hello")
来源：http://dali.jinghuilouyu.cn/Article/details/gtyfgrqkwg.html

[T17] Swift：变量与常量
来源：http://dali.zhixingplan.top/Article/details/gtfryhhsjd.html

var a = 1;  let b = 2
来源：http://dali.ppjwa.cn/Article/details/gtiuicyeha.html

[T18] Swift：字符串插值
来源：http://dali.nanxinkj.top/Article/details/gtpxzgwdqa.html

"值: \(b)"
来源：http://dali.vqdsnc.cn/Article/details/gtyfrzyxli.html

[T19] Swift：可选绑定
来源：http://dali.hywenlv.cn/Article/details/gtrcfebsrp.html

if let n = opt { print(n) }
来源：http://dali.ppjwa.cn/Article/details/gtmzzglugb.html

[T20] Swift：数组操作
来源：http://dali.shuidangran.top/Article/details/gtugylmthb.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.guannengcc.top/Article/details/gtxpxcbufh.html

[T21] Swift：遍历
来源：http://dali.zhiwuduotai.top/Article/details/gtqwaxzofy.html

for x in a { print(x) }
来源：http://dali.yueranfly.top/Article/details/gtnfgidzhh.html

[T22] Swift：字典
来源：http://dali.sysykeji.top/Article/details/gtuqgdemmq.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.yuxming.cn/Article/details/gtdsifqtrk.html

[T23] Swift：函数
来源：http://dali.guannengcc.top/Article/details/gtkcejxjts.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.yvedp.cn/Article/details/gtxtognwpi.html

[T24] Swift：闭包
来源：http://dali.nanxuanxn.top/Article/details/gtzfnucphq.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.tian-w.cn/Article/details/gtnzmvgdyl.html

[T25] Swift：结构体
来源：http://dali.shuidangran.top/Article/details/gtsluufdul.html

struct P { var x: Int }
来源：http://dali.kuanghao11.cn/Article/details/gtpkbyyylk.html

[T26] Swift：类与重写
来源：http://dali.gogol.net.cn/Article/details/gtragiyxlg.html

class A: Base { override func f() {} }
来源：http://dali.zhongyouzk.top/Article/details/gtdieygchd.html

[T27] Swift：错误处理
来源：http://dali.yuxming.cn/Article/details/gtxcumsezx.html

do { try f() } catch { print(error) }
来源：http://dali.meibo888.top/Article/details/gtonprnxxw.html

[T28] Swift：枚举
来源：http://dali.zhixingplan.top/Article/details/gtqaztldfq.html

enum Color { case red, green }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvecjxqig.html

[T29] Swift：guard 提前返回
来源：http://dali.xinyue.icu/Article/details/gtnxqvqfxk.html

guard let x = opt else { return }
来源：http://dali.xuanzx.com/Article/details/gtahsmphxi.html

[T30] Swift：协议
来源：http://dali.iojbl.cn/Article/details/gtsfslzmys.html

protocol Shape { func area() -> Double }
来源：http://dali.hysaishi.cn/Article/details/gtihgqatqu.html

[T31] Lua：Hello World
来源：http://dali.vqdsnc.cn/Article/details/gtqkstarns.html

print("Hello")
来源：http://dali.wangdashe.top/Article/details/gtbpipplej.html

[T32] Lua：局部变量
来源：http://dali.jinqigfzy.top/Article/details/gtfsucdcab.html

local a = 1
来源：http://dali.aizwys.cn/Article/details/gtmeuhxtkv.html

[T33] Lua：表（数组）
来源：http://dali.havefunace.top/Article/details/gtqiyywdfo.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.hongshengwenyu.top/Article/details/gtjvxptzdv.html

[T34] Lua：遍历表
来源：http://dali.andypj.xyz/Article/details/gtdokbovfv.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.dianchejie.cn/Article/details/gtukuxuywi.html

[T35] Lua：字典表
来源：http://dali.guannengcc.top/Article/details/gthsgkxvqt.html

local d = { a = 1 };  d.b = 2
来源：http://dali.cheryme.top/Article/details/gtrpnenvqk.html

[T36] Lua：函数
来源：http://dali.birdmap.top/Article/details/gtoamfenxj.html

function add(a, b) return a + b end
来源：http://dali.yongpay.top/Article/details/gtpywrvldz.html

[T37] Lua：字符串拼接
来源：http://dali.jinqigufen.top/Article/details/gtvtmvunux.html

"a" .. "b"
来源：http://dali.shangyingyoupin.top/Article/details/gtikgjiwvt.html

[T38] Lua：条件
来源：http://dali.tian-w.cn/Article/details/gtyifeyeyg.html

if x > 0 then print("正") end
来源：http://dali.yvedp.cn/Article/details/gtxplguogg.html

[T39] Lua：模式匹配
来源：http://dali.jqgufenzy.top/Article/details/gtitqrznmi.html

string.find(s, "%d+")
来源：http://dali.jinqigfzy.top/Article/details/gtsmnyfvso.html

[T40] Lua：元表
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtncbeluik.html

setmetatable({}, { __index = base })
来源：http://dali.daria6918.cn/Article/details/gtmjpxtpwq.html

[T41] Perl：Hello World
来源：http://dali.ehwqpu.com/Article/details/gtrpgtligh.html

print "Hello\n";
来源：http://dali.ybcxt.top/Article/details/gtkhyizvse.html

[T42] Perl：变量类型
来源：http://dali.bjfxy.top/Article/details/gtkuhsktkm.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.316326.xyz/Article/details/gtesfmnzmf.html

[T43] Perl：字符串插值
来源：http://dali.xuetiantiany.cn/Article/details/gtlxefdksh.html

"值: $a"
来源：http://dali.dashuyun.cn/Article/details/gtsbnqhsrd.html

[T44] Perl：条件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxoqpurcm.html

if ($a > 0) { print "正"; }
来源：http://dali.xylfe.cn/Article/details/gtrosozalv.html

[T45] Perl：数组遍历
来源：http://dali.redwolf501.top/Article/details/gtzwqhitaa.html

for my $x (@arr) { print $x; }
来源：http://dali.0kj1m.cn/Article/details/gtsqvqqwnk.html

[T46] Perl：哈希操作
来源：http://dali.ybcxt.top/Article/details/gthvzbjcvh.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.yvedp.cn/Article/details/gtbusmbsfu.html

[T47] Perl：正则捕获
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnqogijay.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.yueranfly.top/Article/details/gtzhaznmow.html

[T48] Perl：正则替换
来源：http://dali.tianlin.xyz/Article/details/gtlktkiinj.html

$s =~ s/old/new/g;
来源：http://dali.sysykeji.top/Article/details/gthbxbpfvn.html

[T49] Perl：函数
来源：http://dali.dashuyun.cn/Article/details/gtsohbziwc.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.yanxiufei.cn/Article/details/gtjxnyktzj.html

[T50] Perl：逐行读文件
来源：http://dali.chenzaomai.com/Article/details/gthoklnzbh.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.jiagoushi.top/Article/details/gtesljpphj.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.jinqigfzy.top/Article/details/gtilcmzkmb.html

[T51] Scala：Hello World
来源：http://dali.hongshengwenyu.top/Article/details/gteaegzlzi.html

println("Hello")
来源：http://dali.chenzaomai.com/Article/details/gtiqiqdqcl.html

[T52] Scala：变量
来源：http://dali.yonumen.top/Article/details/gtkkbwyvqt.html

val a = 1;  var b = 2
来源：http://dali.pengpengdd.cyou/Article/details/gtmopxquii.html

[T53] Scala：字符串插值
来源：http://dali.tanke756.top/Article/details/gtotxwhkaw.html

s"值: $b"
来源：http://dali.yj20258.top/Article/details/gtlpnffeps.html

[T54] Scala：集合映射
来源：http://dali.jinqigfzy.top/Article/details/gtvrsmwfxr.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.hywenlv.cn/Article/details/gtnauffcbw.html

[T55] Scala：集合过滤
来源：http://dali.shuidangran.top/Article/details/gtvhisudsj.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.jianghu66.top/Article/details/gtvkehsebd.html

[T56] Scala：样例类
来源：http://dali.hammf.cn/Article/details/gttncxyhga.html

case class User(name: String, age: Int)
来源：http://dali.xylfe.cn/Article/details/gtktluhmrd.html

[T57] Scala：模式匹配
来源：http://dali.mhx1999.top/Article/details/gtddkxhwzs.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.pengpengdd.cyou/Article/details/gtczdtsaqv.html

[T58] Scala：函数定义
来源：http://dali.daria6918.cn/Article/details/gtzryxhnjr.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.hammf.cn/Article/details/gttlvvzyvn.html

[T59] Scala：循环
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxnzqhwzu.html

for (i <- 1 to 10) println(i)
来源：http://dali.sxryk.cn/Article/details/gtfkuyibuv.html

[T60] Scala：折叠
来源：http://dali.yvedp.cn/Article/details/gtejwmczjr.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.cucudq.cn/Article/details/gtzgxzuthe.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtizatwiyw.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.sufxvd.cn/Article/details/gtwnvymtdk.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtmyqxjiud.html

[U01] Py：创建虚拟环境
来源：http://dali.daria6918.cn/Article/details/gtrqzmpsjl.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.xinyue.icu/Article/details/gthldagfuv.html

[U02] Py：导出 / 安装依赖
来源：http://dali.chenzaomai.com/Article/details/gtlyeoukuy.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.nanxinkj.top/Article/details/gtpkoymjup.html

[U03] Py：加载 .env 配置
来源：http://dali.gotoacloud.top/Article/details/gtghrbchwa.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.hnqzz.top/Article/details/gtijoiwwge.html

[U04] Py：变量调试打印
来源：http://dali.yvedp.cn/Article/details/gtivzsdsra.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.havefunace.top/Article/details/gtoekwwjyd.html


<!-- 参考信息 -->