代发 wailian999

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.iojbl.cn/Article/details/gtdqqfqcqg.html

[R66] 定时任务
来源：http://dali.pengpengdd.cyou/Article/details/gtyqgqzgwa.html

crontab -e;  crontab -l
来源：http://dali.xylfe.cn/Article/details/gtnykrnmav.html

[R67] 生成随机十六进制串
来源：http://dali.jiagoushi.top/Article/details/gtgvermwno.html

openssl rand -hex 16
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyhyelrip.html

[R68] 计算文件校验值
来源：http://dali.daxiang520.top/Article/details/gtocludlkx.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.sufxvd.cn/Article/details/gtexuiwqkm.html

[R69] 生成随机密码
来源：http://dali.dianchejie.cn/Article/details/gtivyvwqly.html

head -c 16 /dev/urandom | base64
来源：http://dali.yanxiufei.cn/Article/details/gtvragoqei.html

[R70] 时间戳与互转
来源：http://dali.ybcxt.top/Article/details/gtlavwfdkm.html

date +%s;  date -d @1700000000
来源：http://dali.ehwqpu.com/Article/details/gtrqqqrmni.html

[R71] 日期格式化
来源：http://dali.dianchejie.cn/Article/details/gtytrbzwtm.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.hywenlv.cn/Article/details/gtnsybayli.html

[R72] 等待端口就绪
来源：http://dali.yuanzhike.top/Article/details/gtmvtriiic.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.hysaishi.cn/Article/details/gtmedwlzwm.html

[R73] 分割大日志
来源：http://dali.iojbl.cn/Article/details/gtlnisahjo.html

split -l 1000 big.log part_
来源：http://dali.chenjidiqi.icu/Article/details/gtjferikfw.html

[R74] 批量重命名
来源：http://dali.pengpengdd.cyou/Article/details/gtruybfabb.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.yj20258888.top/Article/details/gtqjpzprxt.html

[R75] 导出环境变量
来源：http://dali.shuidangran.top/Article/details/gtnloocqrn.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.dashuyun.cn/Article/details/gtgxaefipp.html

[R76] 使用临时文件
来源：http://dali.nanxinkj.top/Article/details/gttnakjogm.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.pengpengdd.cyou/Article/details/gteyixlpkh.html

[R77] 读取用户输入
来源：http://dali.wangshuangyany.cn/Article/details/gtsfxpngkg.html

read -rp "请输入: " ans
来源：http://dali.hfpthk.cn/Article/details/gtporjtyjx.html

[R78] 交互式菜单
来源：http://dali.feifeiyinyue.top/Article/details/gteuspuppf.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.pengpengdd.cyou/Article/details/gtzkhuitbr.html

[R79] 解析命令行选项
来源：http://dali.aibaodan.cn/Article/details/gtgipkrejd.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhengqikj.top/Article/details/gtqkteooay.html

[R80] 查看脚本执行耗时
来源：http://dali.ivvv.top/Article/details/gtvnzqvpaf.html

time ./run.sh
来源：http://dali.xziqi.cn/Article/details/gthflkonyb.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtrvlhhhud.html

S. C / C++ 专题
来源：http://dali.redwolf501.top/Article/details/gtsksygczu.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtihsyqfom.html

[S01] C：Hello World
来源：http://dali.jqgfzy.top/Article/details/gtsunvojhl.html

#include <stdio.h>
来源：http://dali.zhoulong.xyz/Article/details/gtwdmmlkio.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.shangyingyoupin.top/Article/details/gtegjmebfo.html

[S02] C：变量与格式化输出
来源：http://dali.316326.xyz/Article/details/gtuqtcjcjc.html

int a = 10; printf("%d\n", a);
来源：http://dali.daxiang520.top/Article/details/gtifhsmjeu.html

[S03] C：读入整数
来源：http://dali.haohaochexian.top/Article/details/gtwzijbviv.html

int x; scanf("%d", &x);
来源：http://dali.zycfv.cn/Article/details/gtyyhhxxwv.html

[S04] C：字符串复制
来源：http://dali.jinqigufen.top/Article/details/gtwrhjlmgj.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.cheryme.top/Article/details/gtavftidjz.html

[S05] C：字符串长度
来源：http://dali.cucudq.cn/Article/details/gtsnatjsho.html

strlen(s)
来源：http://dali.guannengcc.top/Article/details/gtsbzsqxqf.html

[S06] C：字符串比较
来源：http://dali.hongshengwenyu.top/Article/details/gtbafqicia.html

strcmp(a, b) == 0
来源：http://dali.aibaodan.cn/Article/details/gttjlqmxds.html

[S07] C：数组遍历求和
来源：http://dali.yuxming.cn/Article/details/gtzzolfdme.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.wangshuangyany.cn/Article/details/gttqqeyblj.html

[S08] C：动态内存分配与释放
来源：http://dali.yueranfly.top/Article/details/gtukdpppvr.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.pengpengdd.cyou/Article/details/gtzmsmdzcv.html

[S09] C：结构体定义与初始化
来源：http://dali.pengpengdd.cyou/Article/details/gteexhxmcn.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.ehwqpu.com/Article/details/gtivryhcib.html

[S10] C：指针与解引用
来源：http://dali.jlsjyb.cn/Article/details/gtjbwvefbo.html

int *p = &a;  *p = 5;
来源：http://dali.zdqjudy.top/Article/details/gtqgasgrfg.html

[S11] C：逐行读文件
来源：http://dali.cheryme.top/Article/details/gtxbpenagk.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.9152youxi.cn/Article/details/gtohvhpuhw.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.vqdsnc.cn/Article/details/gtyqmkxjui.html

fclose(f);
来源：http://dali.yj20258.top/Article/details/gtbsnncqui.html

[S12] C：写文件
来源：http://dali.tian-w.cn/Article/details/gtpfeejqij.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.pycfn.com/Article/details/gtdcfeotft.html

[S13] C：宏定义
来源：http://dali.ppjwa.cn/Article/details/gtokvxgszt.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.nanxuanxn.top/Article/details/gtktaehgbr.html

[S14] C：枚举
来源：http://dali.yvedp.cn/Article/details/gtobenrbty.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.hfpthk.cn/Article/details/gtglewmxxy.html

[S15] C：类型转换
来源：http://dali.nwbrower.top/Article/details/gtzbcfeteo.html

(double) a / b
来源：http://dali.feifeiyinyue.top/Article/details/gtipbpbsix.html

[S16] C：位操作置位
来源：http://dali.ybcxt.top/Article/details/gtuubevylf.html

x |= (1 << 3);
来源：http://dali.yongpay.top/Article/details/gtxjwiwnwt.html

[S17] C：安全拼接字符串
来源：http://dali.gzhubu.top/Article/details/gtbutvweyq.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.xylfe.cn/Article/details/gtypsauoxi.html

[S18] C：命令行参数
来源：http://dali.hammf.cn/Article/details/gtmdgbbzch.html

int main(int argc, char **argv)
来源：http://dali.hongshengwenyu.top/Article/details/gtasprismf.html

[S19] C：快速排序
来源：http://dali.fzhhl.top/Article/details/gteijxucwy.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.jiagoushi.top/Article/details/gtumicoktv.html

[S20] C：二分查找
来源：http://dali.hfpthk.cn/Article/details/gtosbpozhw.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.ivvv.top/Article/details/gtuakumugw.html

[S21] C：字符类别判断
来源：http://dali.0kj1m.cn/Article/details/gtewwenntg.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.aizwys.cn/Article/details/gttwervcxl.html

[S22] C：字符串转数字
来源：http://dali.nanxinkj.top/Article/details/gtxgzgjkpy.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.nanxuanxn.top/Article/details/gtkcigiode.html

[S23] C：随机数
来源：http://dali.smart0.xyz/Article/details/gtaikvozqf.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.xziqi.cn/Article/details/gtnoqxetxe.html

[S24] C：获取本地时间
来源：http://dali.jqgfzy.top/Article/details/gtkjsseehd.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.shzxlz.cn/Article/details/gttiulgrgq.html

[S25] C：内存拷贝
来源：http://dali.chenjidiqi.icu/Article/details/gtssjywcez.html

memcpy(dst, src, n);
来源：http://dali.redwolf501.top/Article/details/gtdmsmkrgl.html

[S26] C：内存清零
来源：http://dali.shanyushiyangtech.top/Article/details/gtkhhfnnko.html

memset(a, 0, sizeof a);
来源：http://dali.yongpay.top/Article/details/gtmaxkupbo.html

[S27] C：定义常量
来源：http://dali.tianlin.xyz/Article/details/gtdobrhxci.html

const double PI = 3.14159;
来源：http://dali.yuanzhike.top/Article/details/gtucalqofr.html

[S28] C：静态变量
来源：http://dali.yj20258888.top/Article/details/gtakanopts.html

static int counter = 0;
来源：http://dali.pycfn.com/Article/details/gtikxwfwyc.html

[S29] C：变参函数
来源：http://dali.cashguo.top/Article/details/gtdsitmyqd.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.jyoumei.cn/Article/details/gtpapiijol.html

[S30] C：头文件保护
来源：http://dali.tianlin.xyz/Article/details/gtsywavpwo.html

#ifndef X_H
来源：http://dali.xuanzx.com/Article/details/gtpqwceaxk.html

#define X_H
来源：http://dali.cashguo.top/Article/details/gtfktqzpwb.html

#endif
来源：http://dali.havefunace.top/Article/details/gthudikdio.html

[S31] C++：Hello World
来源：http://dali.hammf.cn/Article/details/gtjgtuzepa.html

#include <iostream>
来源：http://dali.zhaomingkeji.xyz/Article/details/gtibcksaca.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.andypj.xyz/Article/details/gttkmvrsuy.html

[S32] C++：字符串
来源：http://dali.ppjwa.cn/Article/details/gtyyyowipx.html

std::string s = "hi";  s += "!";
来源：http://dali.yangfankeji.com/Article/details/gtdukoubbe.html

[S33] C++：vector 增删
来源：http://dali.cdnleiting.top/Article/details/gtamriyjmm.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.chenlongwang.top/Article/details/gtkzicxccq.html

[S34] C++：遍历 vector
来源：http://dali.yueranfly.top/Article/details/gtwiwafzsl.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.xuanzx.com/Article/details/gtpcpygfhu.html

[S35] C++：map
来源：http://dali.guannengcc.top/Article/details/gtcaqlcauk.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.dashuyun.cn/Article/details/gtijcmrggf.html

[S36] C++：unordered_map
来源：http://dali.shangyingyoupin.top/Article/details/gtgyjlbcha.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.cheryme.top/Article/details/gttlofkqkb.html

[S37] C++：set
来源：http://dali.tianlin.xyz/Article/details/gtadxzwfpb.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.meibo888.top/Article/details/gtuudcoocm.html

[S38] C++：排序
来源：http://dali.hfpthk.cn/Article/details/gtifkdqihy.html

std::sort(v.begin(), v.end());
来源：http://dali.snrcjt.cn/Article/details/gtislhphlu.html

[S39] C++：自定义比较器排序
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnrwcwjhy.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.fengsongda.top/Article/details/gtxhymgapn.html

[S40] C++：查找元素
来源：http://dali.jqgfzy.top/Article/details/gtqqlyboql.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.ydzc1.top/Article/details/gtdpupbfgr.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gtxjplbisu.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.aizwys.cn/Article/details/gtejqunjlg.html

[S42] C++：继承与虚函数
来源：http://dali.ppjwa.cn/Article/details/gtmidpdkza.html

class B : public Base { public: void f() override {} };
来源：http://dali.yj20258888.top/Article/details/gtbnpmfves.html

[S43] C++：智能指针
来源：http://dali.zhaomingkeji.xyz/Article/details/gterudpkkn.html

auto p = std::make_unique<int>(5);
来源：http://dali.jinqigufen.top/Article/details/gtjonzrwrf.html

[S44] C++：引用传参
来源：http://dali.aibaodan.cn/Article/details/gtbhqnywha.html

void inc(int &x) { ++x; }
来源：http://dali.fengsongda.top/Article/details/gtqmwusyhp.html

[S45] C++：lambda
来源：http://dali.feifeiyinyue.top/Article/details/gtobmklmph.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.ppjwa.cn/Article/details/gtkkrfatyr.html

[S46] C++：函数模板
来源：http://dali.gaohongyu789.top/Article/details/gtyyrmevfy.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.jianghu66.top/Article/details/gtrkjnpjba.html

[S47] C++：结构化绑定遍历
来源：http://dali.cashguo.top/Article/details/gtzophsagy.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.jinqigfzy.top/Article/details/gtlulwrzxc.html

[S48] C++：逐行读文件
来源：http://dali.tanke756.top/Article/details/gtxseyjofs.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.haohaochexian.top/Article/details/gtotslohyl.html

while (std::getline(in, line)) { }
来源：http://dali.xziqi.cn/Article/details/gtszkslnwa.html

[S49] C++：写文件
来源：http://dali.hnxiangtu.top/Article/details/gtdiglbtyl.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.nanxuanxn.top/Article/details/gtddnkkpzt.html

[S50] C++：格式化数字
来源：http://dali.xuetiantiany.cn/Article/details/gtbkqxocph.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.yonumen.top/Article/details/gtpgasdzsm.html

[S51] C++：显式类型转换
来源：http://dali.yj20258888.top/Article/details/gtosiprmin.html

static_cast<double>(a) / b
来源：http://dali.vqdsnc.cn/Article/details/gtgnydbpjb.html

[S52] C++：const 与 noexcept
来源：http://dali.tianlin.xyz/Article/details/gthxproqgn.html

int size() const noexcept { return n_; }
来源：http://dali.redwolf501.top/Article/details/gtoaztfuzc.html

[S53] C++：移动语义
来源：http://dali.ivvv.top/Article/details/gtzvqjmvjo.html

std::vector<int> w = std::move(v);
来源：http://dali.jyoumei.cn/Article/details/gtskbouwvs.html

[S54] C++：异常处理
来源：http://dali.sufxvd.cn/Article/details/gttjofmeil.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.wangshuangyany.cn/Article/details/gtklggoxyc.html

[S55] C++：结构化绑定
来源：http://dali.c1oappe.top/Article/details/gtogbkizjf.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.havefunace.top/Article/details/gtoqngpegf.html

[S56] C++：optional
来源：http://dali.zdqjudy.top/Article/details/gtrubpoqtx.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gtmdjewyqr.html

[S57] C++：编译期常量
来源：http://dali.kuanghao11.cn/Article/details/gtoasgqmls.html

constexpr int N = 10;
来源：http://dali.chenzaomai.com/Article/details/gtmzlrcfqn.html

[S58] C++：命名空间
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvcteoniz.html

namespace ns { int f() { return 1; } }
来源：http://dali.tanke756.top/Article/details/gtrrnjtxka.html

[S59] C++：静态断言
来源：http://dali.0kj1m.cn/Article/details/gtmjvknmtb.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.jyoumei.cn/Article/details/gtglfjqrpl.html

[S60] C++：遍历并删除元素
来源：http://dali.zhiwuduotai.top/Article/details/gtukmmamkh.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.316326.xyz/Article/details/gtjpkvpqjq.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtqyvexesq.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yueranfly.top/Article/details/gtmfdjijrl.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdwlruovm.html

[T01] Kotlin：Hello World
来源：http://dali.chenzaomai.com/Article/details/gtgjbakbyk.html

println("Hello")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtstxqqewn.html

[T02] Kotlin：变量
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnixogxpc.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.xuanzx.com/Article/details/gtrpritgzc.html

[T03] Kotlin：字符串模板
来源：http://dali.xziqi.cn/Article/details/gtjaqizjxw.html

"值: $b"
来源：http://dali.zhongyouzk.top/Article/details/gtqjcxmdvi.html

[T04] Kotlin：空安全
来源：http://dali.9152youxi.cn/Article/details/gtuxvzecav.html

val n: String? = null;  n?.length
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmiyjkkpw.html

[T05] Kotlin：when 表达式
来源：http://dali.bjfxy.top/Article/details/gtdiqmnmia.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.chenlongwang.top/Article/details/gtamqyryhy.html

[T06] Kotlin：集合映射
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfmmegfwq.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtecilvfon.html

[T07] Kotlin：集合过滤
来源：http://dali.aizwys.cn/Article/details/gtamwqiqgq.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zdqjudy.top/Article/details/gtnhdhzstt.html

[T08] Kotlin：数据类
来源：http://dali.jinghuilouyu.cn/Article/details/gttgimyqfg.html

data class User(val name: String, val age: Int)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpaeduzxq.html

[T09] Kotlin：扩展函数
来源：http://dali.guowangkeji.top/Article/details/gtmjzqxgbo.html

fun String.exclaim() = this + "!"
来源：http://dali.sysykeji.top/Article/details/gtioznvezw.html

[T10] Kotlin：默认参数
来源：http://dali.yj20258.top/Article/details/gttgcgahmr.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.jyoumei.cn/Article/details/gtpfpmzhmc.html

[T11] Kotlin：协程
来源：http://dali.pycfn.com/Article/details/gtshudaxgq.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.pycfn.com/Article/details/gttvjgptia.html

[T12] Kotlin：解构声明
来源：http://dali.c1oappe.top/Article/details/gtdlngcfhd.html

val (a, b) = Pair(1, 2)
来源：http://dali.wangshuangyany.cn/Article/details/gtergxgale.html

[T13] Kotlin：只读 Map
来源：http://dali.nanxinkj.top/Article/details/gtsfiipsxb.html

val m = mapOf("a" to 1)
来源：http://dali.yanxiufei.cn/Article/details/gtycanquad.html

[T14] Kotlin：循环
来源：http://dali.hnxiangtu.top/Article/details/gtgkdjqlkr.html

for (i in 1..10) println(i)
来源：http://dali.gaohongyu789.top/Article/details/gtrnvqhdaf.html

[T15] Kotlin：接口
来源：http://dali.jinghuilouyu.cn/Article/details/gtrhkpxlrn.html

interface Shape { fun area(): Double }
来源：http://dali.birdmap.top/Article/details/gtuscdptjd.html

[T16] Swift：Hello World
来源：http://dali.fengsongda.top/Article/details/gtuhlupugf.html

print("Hello")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoldduddi.html

[T17] Swift：变量与常量
来源：http://dali.daria6918.cn/Article/details/gtubhwbsqh.html

var a = 1;  let b = 2
来源：http://dali.9152youxi.cn/Article/details/gtevuiepzq.html

[T18] Swift：字符串插值
来源：http://dali.hfpthk.cn/Article/details/gtxvzvcuyp.html

"值: \(b)"
来源：http://dali.yvedp.cn/Article/details/gtcmpcujri.html

[T19] Swift：可选绑定
来源：http://dali.jqgufenzy.top/Article/details/gtizgnmejg.html

if let n = opt { print(n) }
来源：http://dali.meibo888.top/Article/details/gtiasrsqyf.html

[T20] Swift：数组操作
来源：http://dali.zhoulong.xyz/Article/details/gtlbfdaita.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.meibo888.top/Article/details/gtkkxtmyga.html

[T21] Swift：遍历
来源：http://dali.jqgfzy.top/Article/details/gtmqjtvybp.html

for x in a { print(x) }
来源：http://dali.yangfankeji.com/Article/details/gtsytjudqv.html

[T22] Swift：字典
来源：http://dali.smart0.xyz/Article/details/gtaaszcafb.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.sufxvd.cn/Article/details/gtdwwvstny.html

[T23] Swift：函数
来源：http://dali.gotoacloud.top/Article/details/gtqwxxfooz.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.yangfankeji.com/Article/details/gtxfbanrcn.html

[T24] Swift：闭包
来源：http://dali.jiagoushi.top/Article/details/gtpdkwlbbm.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.hnxiangtu.top/Article/details/gterncwpvq.html

[T25] Swift：结构体
来源：http://dali.hywenlv.cn/Article/details/gtdknbrdmj.html

struct P { var x: Int }
来源：http://dali.chenlongwang.top/Article/details/gtensxlnsj.html

[T26] Swift：类与重写
来源：http://dali.gotoacloud.top/Article/details/gtwcpscmsb.html

class A: Base { override func f() {} }
来源：http://dali.ehwqpu.com/Article/details/gtqpclrxqi.html

[T27] Swift：错误处理
来源：http://dali.cqqwz.cn/Article/details/gtcrhtpzut.html

do { try f() } catch { print(error) }
来源：http://dali.hammf.cn/Article/details/gtdxdjlrut.html

[T28] Swift：枚举
来源：http://dali.andypj.xyz/Article/details/gtqqneaslb.html

enum Color { case red, green }
来源：http://dali.redwolf501.top/Article/details/gtcyjjtwex.html

[T29] Swift：guard 提前返回
来源：http://dali.nanxuanxn.top/Article/details/gtlujukhxh.html

guard let x = opt else { return }
来源：http://dali.hywenlv.cn/Article/details/gtfxkybqfn.html

[T30] Swift：协议
来源：http://dali.guannengcc.top/Article/details/gtieavfebz.html

protocol Shape { func area() -> Double }
来源：http://dali.gogol.net.cn/Article/details/gtsjyuixtk.html

[T31] Lua：Hello World
来源：http://dali.jqgfzy.top/Article/details/gtzcehuayr.html

print("Hello")
来源：http://dali.yuanzhike.top/Article/details/gtpddworcv.html

[T32] Lua：局部变量
来源：http://dali.guannengcc.top/Article/details/gtecubzpjh.html

local a = 1
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfdqesyfd.html

[T33] Lua：表（数组）
来源：http://dali.yueranfly.top/Article/details/gtkcpnaesg.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.316326.xyz/Article/details/gtlidskdcw.html

[T34] Lua：遍历表
来源：http://dali.redwolf501.top/Article/details/gtprvgfyfk.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gtcjnvpbpj.html

[T35] Lua：字典表
来源：http://dali.tanke756.top/Article/details/gtytcbtvje.html

local d = { a = 1 };  d.b = 2
来源：http://dali.smart0.xyz/Article/details/gtjsqvnbhe.html

[T36] Lua：函数
来源：http://dali.zhixingplan.top/Article/details/gtzsifwrhr.html

function add(a, b) return a + b end
来源：http://dali.dianchejie.cn/Article/details/gtezkewiey.html

[T37] Lua：字符串拼接
来源：http://dali.gzhubu.top/Article/details/gthrhpjjlb.html

"a" .. "b"
来源：http://dali.yj20258888.top/Article/details/gtbmqmfome.html

[T38] Lua：条件
来源：http://dali.nwbrower.top/Article/details/gtqxcsulrb.html

if x > 0 then print("正") end
来源：http://dali.ydzc1.top/Article/details/gtwmfzhuja.html

[T39] Lua：模式匹配
来源：http://dali.jlsjyb.cn/Article/details/gtyfgsxhso.html

string.find(s, "%d+")
来源：http://dali.shanyushiyangtech.top/Article/details/gtlbvbllmh.html

[T40] Lua：元表
来源：http://dali.chenjidiqi.icu/Article/details/gtdcowgccs.html

setmetatable({}, { __index = base })
来源：http://dali.zdqjudy.top/Article/details/gtxxuggmiw.html

[T41] Perl：Hello World
来源：http://dali.jqgfzy.top/Article/details/gthvdbnamd.html

print "Hello\n";
来源：http://dali.shangyingyoupin.top/Article/details/gtdjomjnrr.html

[T42] Perl：变量类型
来源：http://dali.nwbrower.top/Article/details/gtnycqrdgv.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjokwnuda.html

[T43] Perl：字符串插值
来源：http://dali.sweek.top/Article/details/gtiwvaliiv.html

"值: $a"
来源：http://dali.ybcxt.top/Article/details/gtchrrpqqe.html

[T44] Perl：条件
来源：http://dali.mhx1999.top/Article/details/gtsyolacoi.html

if ($a > 0) { print "正"; }
来源：http://dali.cucudq.cn/Article/details/gttcngakmv.html

[T45] Perl：数组遍历
来源：http://dali.pengpengdd.cyou/Article/details/gtnnlcxhbl.html

for my $x (@arr) { print $x; }
来源：http://dali.cdnleiting.top/Article/details/gtutqfabkj.html

[T46] Perl：哈希操作
来源：http://dali.redwolf501.top/Article/details/gtcrkodrun.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.yuxming.cn/Article/details/gtobuwwetz.html

[T47] Perl：正则捕获
来源：http://dali.hnqzz.top/Article/details/gtqubrneby.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.sufxvd.cn/Article/details/gthotjqqsx.html

[T48] Perl：正则替换
来源：http://dali.cdnleiting.top/Article/details/gtbawomudw.html

$s =~ s/old/new/g;
来源：http://dali.cucudq.cn/Article/details/gthxlfqqlh.html

[T49] Perl：函数
来源：http://dali.wangshuangyany.cn/Article/details/gtkwjxbhbr.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.hnxiangtu.top/Article/details/gtixphfjvv.html

[T50] Perl：逐行读文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkbqbaejo.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.jianghu66.top/Article/details/gtmaaekhoc.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.chenjidiqi.icu/Article/details/gtlkweqgne.html

[T51] Scala：Hello World
来源：http://dali.xuetiantiany.cn/Article/details/gthnahkuvw.html

println("Hello")
来源：http://dali.yanxiufei.cn/Article/details/gtgzrggjwm.html

[T52] Scala：变量
来源：http://dali.snrcjt.cn/Article/details/gtddiwpagj.html

val a = 1;  var b = 2
来源：http://dali.yanxiufei.cn/Article/details/gtnsqdaojl.html

[T53] Scala：字符串插值
来源：http://dali.yueranfly.top/Article/details/gtelfqlebc.html

s"值: $b"
来源：http://dali.feifeiyinyue.top/Article/details/gtxejjydbd.html

[T54] Scala：集合映射
来源：http://dali.xuetiantiany.cn/Article/details/gtwihqtpmd.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gtemnplisj.html

[T55] Scala：集合过滤
来源：http://dali.zhongyouzk.top/Article/details/gtqmsmaoex.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.meibo888.top/Article/details/gtfksetwow.html

[T56] Scala：样例类
来源：http://dali.pycfn.com/Article/details/gtrecxzlnw.html

case class User(name: String, age: Int)
来源：http://dali.chenzaomai.com/Article/details/gtltkfuphq.html

[T57] Scala：模式匹配
来源：http://dali.yj20258.top/Article/details/gtlgnusuxi.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyssidfsp.html

[T58] Scala：函数定义
来源：http://dali.wangshuangyany.cn/Article/details/gtvdzqzeqj.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.9152youxi.cn/Article/details/gtarzrpjsh.html

[T59] Scala：循环
来源：http://dali.zdqjudy.top/Article/details/gtkpepplbp.html

for (i <- 1 to 10) println(i)
来源：http://dali.sweek.top/Article/details/gtkrojhoug.html

[T60] Scala：折叠
来源：http://dali.zhixingplan.top/Article/details/gteuqwdzoi.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.fzhhl.top/Article/details/gtvljfdpmv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtukufbjox.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zdqjudy.top/Article/details/gtxikeyfoy.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtvjkdnqcz.html

[U01] Py：创建虚拟环境
来源：http://dali.pycfn.com/Article/details/gtryhsakkp.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.chenzaomai.com/Article/details/gtpphorwuj.html

[U02] Py：导出 / 安装依赖
来源：http://dali.chenlongwang.top/Article/details/gtgsuvzzii.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhoulong.xyz/Article/details/gtnzzdbgoc.html

[U03] Py：加载 .env 配置
来源：http://dali.shanyushiyangkeji.top/Article/details/gtosukshqe.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.yangfankeji.com/Article/details/gtgobfjwvu.html

[U04] Py：变量调试打印
来源：http://dali.wangshuangyany.cn/Article/details/gtoyaascln.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxfbloldy.html

[U05] Py：列表去重且保序
来源：http://dali.wangdashe.top/Article/details/gtbqytjulq.html

list(dict.fromkeys(arr))
来源：http://dali.sweek.top/Article/details/gtbeolryea.html

[U06] Py：合并两个字典
来源：http://dali.zhongyouzk.top/Article/details/gtdgxxmztl.html

{**a, **b}
来源：http://dali.cqqwz.cn/Article/details/gtjvmqevvg.html


<!-- 参考信息 -->