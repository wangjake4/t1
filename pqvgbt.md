代发 wailian999

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.gzhubu.top/Article/details/gtlxbycrcf.html

[R66] 定时任务
来源：http://dali.tianlin.xyz/Article/details/gtdbzarhxo.html

crontab -e;  crontab -l
来源：http://dali.ybcxt.top/Article/details/gtcugnusjs.html

[R67] 生成随机十六进制串
来源：http://dali.ywan-chungtsiang.top/Article/details/gtssimnoyb.html

openssl rand -hex 16
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdbdnvzic.html

[R68] 计算文件校验值
来源：http://dali.redwolf501.top/Article/details/gtwtczqvbq.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.xziqi.cn/Article/details/gtasioclyz.html

[R69] 生成随机密码
来源：http://dali.zhiwuduotai.top/Article/details/gtsjfwevjo.html

head -c 16 /dev/urandom | base64
来源：http://dali.pengpengdd.cyou/Article/details/gtjvhibyej.html

[R70] 时间戳与互转
来源：http://dali.fengsongda.top/Article/details/gtxdhukpbl.html

date +%s;  date -d @1700000000
来源：http://dali.tianlin.xyz/Article/details/gtyzkkhsth.html

[R71] 日期格式化
来源：http://dali.zdqjudy.top/Article/details/gtnhyfugnz.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zycfv.cn/Article/details/gtpkacsbss.html

[R72] 等待端口就绪
来源：http://dali.yonumen.top/Article/details/gtdxemgdwm.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.mhx1999.top/Article/details/gtlftiqnqm.html

[R73] 分割大日志
来源：http://dali.havefunace.top/Article/details/gtxhnvdpcm.html

split -l 1000 big.log part_
来源：http://dali.jqgufenzy.top/Article/details/gtjcgcafge.html

[R74] 批量重命名
来源：http://dali.yj202588.top/Article/details/gtfnbpwadr.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.chenlongwang.top/Article/details/gtmrnkxazz.html

[R75] 导出环境变量
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaglrzkdh.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.tianlin.xyz/Article/details/gthoqnasms.html

[R76] 使用临时文件
来源：http://dali.pycfn.com/Article/details/gtnutnyjtx.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.wangdashe.top/Article/details/gtldotqgwy.html

[R77] 读取用户输入
来源：http://dali.pengpengdd.cyou/Article/details/gtapbkjhml.html

read -rp "请输入: " ans
来源：http://dali.fengsongda.top/Article/details/gtkdxgglwu.html

[R78] 交互式菜单
来源：http://dali.tian-w.cn/Article/details/gthgteswgm.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.ppjwa.cn/Article/details/gthzrkuhyo.html

[R79] 解析命令行选项
来源：http://dali.ydzc1.top/Article/details/gtgcpypqab.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.yonumen.top/Article/details/gtykuqquqc.html

[R80] 查看脚本执行耗时
来源：http://dali.yuxming.cn/Article/details/gtqprvpgfj.html

time ./run.sh
来源：http://dali.jinghuilouyu.cn/Article/details/gtksrarhlc.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtvzpzzjzq.html

S. C / C++ 专题
来源：http://dali.yvedp.cn/Article/details/gtgdqjjgfw.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gthlaipsxm.html

[S01] C：Hello World
来源：http://dali.haohaochexian.top/Article/details/gtpwoefrhh.html

#include <stdio.h>
来源：http://dali.yueranfly.top/Article/details/gtjycnlifz.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.sweek.top/Article/details/gtxifolbqs.html

[S02] C：变量与格式化输出
来源：http://dali.gogol.net.cn/Article/details/gtdzidoprw.html

int a = 10; printf("%d\n", a);
来源：http://dali.9152youxi.cn/Article/details/gtfmxginjy.html

[S03] C：读入整数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoguaucdq.html

int x; scanf("%d", &x);
来源：http://dali.xziqi.cn/Article/details/gthzgwvcgi.html

[S04] C：字符串复制
来源：http://dali.zdqjudy.top/Article/details/gteaspqovz.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.cqqwz.cn/Article/details/gtcrbsutjg.html

[S05] C：字符串长度
来源：http://dali.chenjidiqi.icu/Article/details/gtdkqrsikj.html

strlen(s)
来源：http://dali.mhx1999.top/Article/details/gtxrddgvhm.html

[S06] C：字符串比较
来源：http://dali.hfpthk.cn/Article/details/gtuemxtepa.html

strcmp(a, b) == 0
来源：http://dali.ybcxt.top/Article/details/gtrbulqrin.html

[S07] C：数组遍历求和
来源：http://dali.jqgufenzy.top/Article/details/gtlaqxggfs.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.chenjidiqi.icu/Article/details/gtkujpxwxk.html

[S08] C：动态内存分配与释放
来源：http://dali.jinqigufen.top/Article/details/gtgpbshfyl.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.jqgfzy.top/Article/details/gtstepbjfs.html

[S09] C：结构体定义与初始化
来源：http://dali.yanxiufei.cn/Article/details/gtxlhqpuyk.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zdqjudy.top/Article/details/gtqooipuxo.html

[S10] C：指针与解引用
来源：http://dali.hammf.cn/Article/details/gtiujqtugf.html

int *p = &a;  *p = 5;
来源：http://dali.fengsongda.top/Article/details/gtkgwtrbnr.html

[S11] C：逐行读文件
来源：http://dali.yongpay.top/Article/details/gtrkereekt.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.shuidangran.top/Article/details/gtmtfcrsiv.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.yj20258888.top/Article/details/gtozpszhea.html

fclose(f);
来源：http://dali.dianchejie.cn/Article/details/gtjhpjrgbf.html

[S12] C：写文件
来源：http://dali.9152youxi.cn/Article/details/gtezoosyyw.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.svipenyu.cn/Article/details/gtfmicfgpo.html

[S13] C：宏定义
来源：http://dali.aizwys.cn/Article/details/gtbdgdivxo.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.smart0.xyz/Article/details/gtakdycqqy.html

[S14] C：枚举
来源：http://dali.ydzc1.top/Article/details/gtsaiyaizk.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.fengsongda.top/Article/details/gtswphaien.html

[S15] C：类型转换
来源：http://dali.pycfn.com/Article/details/gtxbimxjlq.html

(double) a / b
来源：http://dali.nanxuanxn.top/Article/details/gtcaqggrwv.html

[S16] C：位操作置位
来源：http://dali.andypj.xyz/Article/details/gtuckjabnt.html

x |= (1 << 3);
来源：http://dali.yvedp.cn/Article/details/gtuewvraeb.html

[S17] C：安全拼接字符串
来源：http://dali.aibaodan.cn/Article/details/gtqkjuwtfa.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.birdmap.top/Article/details/gtsrijtuzb.html

[S18] C：命令行参数
来源：http://dali.daxiang520.top/Article/details/gttddzetin.html

int main(int argc, char **argv)
来源：http://dali.zhixingplan.top/Article/details/gtjgsoccgv.html

[S19] C：快速排序
来源：http://dali.hywenlv.cn/Article/details/gtwizlqgmh.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.yuxming.cn/Article/details/gtbgdomrmo.html

[S20] C：二分查找
来源：http://dali.gaohongyu789.top/Article/details/gthotcrafj.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.yanxiufei.cn/Article/details/gttgsmthnz.html

[S21] C：字符类别判断
来源：http://dali.yanxiufei.cn/Article/details/gtxvoihdrg.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.xuetiantiany.cn/Article/details/gtzrxvazyo.html

[S22] C：字符串转数字
来源：http://dali.zhixingplan.top/Article/details/gtyhcgroor.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.cashguo.top/Article/details/gtzmcqmggp.html

[S23] C：随机数
来源：http://dali.ybcxt.top/Article/details/gtztvdoyzo.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.chenlongwang.top/Article/details/gtwxoiyabi.html

[S24] C：获取本地时间
来源：http://dali.yuxming.cn/Article/details/gttkakvxpn.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtycdyisnd.html

[S25] C：内存拷贝
来源：http://dali.nanxinkj.top/Article/details/gtcxeqmxtt.html

memcpy(dst, src, n);
来源：http://dali.wangshuangyany.cn/Article/details/gtjfuznpdh.html

[S26] C：内存清零
来源：http://dali.daria6918.cn/Article/details/gtsiliwcol.html

memset(a, 0, sizeof a);
来源：http://dali.ydzc1.top/Article/details/gtgpipmqsv.html

[S27] C：定义常量
来源：http://dali.birdmap.top/Article/details/gtuklnumag.html

const double PI = 3.14159;
来源：http://dali.haohaochexian.top/Article/details/gteebofrma.html

[S28] C：静态变量
来源：http://dali.mhx1999.top/Article/details/gtomafdfnm.html

static int counter = 0;
来源：http://dali.nwbrower.top/Article/details/gtldfcxiuw.html

[S29] C：变参函数
来源：http://dali.jqgufenzy.top/Article/details/gtfdmypbpr.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.hnqzz.top/Article/details/gtohsciufh.html

[S30] C：头文件保护
来源：http://dali.shuidangran.top/Article/details/gtsqxziloo.html

#ifndef X_H
来源：http://dali.haohaochexian.top/Article/details/gtvjqvqafg.html

#define X_H
来源：http://dali.jinghuilouyu.cn/Article/details/gtiiihxiju.html

#endif
来源：http://dali.wangdashe.top/Article/details/gtqicovdnh.html

[S31] C++：Hello World
来源：http://dali.yangfankeji.com/Article/details/gtadyfzyor.html

#include <iostream>
来源：http://dali.feifeiyinyue.top/Article/details/gtdllxdocw.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.nanxinkj.top/Article/details/gtvacrghxa.html

[S32] C++：字符串
来源：http://dali.shangyingyoupin.top/Article/details/gtufnojpyd.html

std::string s = "hi";  s += "!";
来源：http://dali.iojbl.cn/Article/details/gtpuqkmhon.html

[S33] C++：vector 增删
来源：http://dali.jinghuilouyu.cn/Article/details/gtgjuomuqd.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.guannengcc.top/Article/details/gttbsrhphp.html

[S34] C++：遍历 vector
来源：http://dali.cqqwz.cn/Article/details/gtjnlhdglw.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.fengsongda.top/Article/details/gtjuzfxzyx.html

[S35] C++：map
来源：http://dali.yonumen.top/Article/details/gtbpptoggi.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.xylfe.cn/Article/details/gtzcsksukg.html

[S36] C++：unordered_map
来源：http://dali.wangshuangyany.cn/Article/details/gtdgqlsdqe.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.sweek.top/Article/details/gtqhmxyero.html

[S37] C++：set
来源：http://dali.daxiang520.top/Article/details/gtshoyjeqz.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.yonumen.top/Article/details/gttbkyqkly.html

[S38] C++：排序
来源：http://dali.shanyushiyangtech.top/Article/details/gtwqgotfao.html

std::sort(v.begin(), v.end());
来源：http://dali.zhiwuduotai.top/Article/details/gtdqgpkqrd.html

[S39] C++：自定义比较器排序
来源：http://dali.mhx1999.top/Article/details/gtvdwnygqi.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.shanyushiyangtech.top/Article/details/gtamjwaeqf.html

[S40] C++：查找元素
来源：http://dali.shanyushiyangtech.top/Article/details/gttuetteqr.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.vqdsnc.cn/Article/details/gticwfpqwg.html

[S41] C++：类与构造函数
来源：http://dali.aibaodan.cn/Article/details/gtjgfvnzvm.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrzvqfyzm.html

[S42] C++：继承与虚函数
来源：http://dali.jianghu66.top/Article/details/gtsnfhklsp.html

class B : public Base { public: void f() override {} };
来源：http://dali.xziqi.cn/Article/details/gtxwqwurdx.html

[S43] C++：智能指针
来源：http://dali.zhixingplan.top/Article/details/gtibzlyqpk.html

auto p = std::make_unique<int>(5);
来源：http://dali.yongpay.top/Article/details/gtykdmmrpn.html

[S44] C++：引用传参
来源：http://dali.hysaishi.cn/Article/details/gtouixsbdl.html

void inc(int &x) { ++x; }
来源：http://dali.birdmap.top/Article/details/gtfytmlgzm.html

[S45] C++：lambda
来源：http://dali.chenjidiqi.icu/Article/details/gtcwjesafr.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zycfv.cn/Article/details/gtnyvnhofv.html

[S46] C++：函数模板
来源：http://dali.shangyingyoupin.top/Article/details/gtelnwyxag.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.gogol.net.cn/Article/details/gtkllqffrz.html

[S47] C++：结构化绑定遍历
来源：http://dali.ppjwa.cn/Article/details/gtlntmduei.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.c1oappe.top/Article/details/gtiawkgopk.html

[S48] C++：逐行读文件
来源：http://dali.hongshengwenyu.top/Article/details/gtyatdxcjd.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.sysykeji.top/Article/details/gtushdxets.html

while (std::getline(in, line)) { }
来源：http://dali.quarkkingdee.top/Article/details/gtykbblnzv.html

[S49] C++：写文件
来源：http://dali.iojbl.cn/Article/details/gtvptqatvl.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.jyoumei.cn/Article/details/gtlvjclgwl.html

[S50] C++：格式化数字
来源：http://dali.sxryk.cn/Article/details/gtxsfxcmsp.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhongyouzk.top/Article/details/gtvpkfxblu.html

[S51] C++：显式类型转换
来源：http://dali.hammf.cn/Article/details/gtjdahljlj.html

static_cast<double>(a) / b
来源：http://dali.fzhhl.top/Article/details/gtuafsqpmy.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gtsqtawper.html

int size() const noexcept { return n_; }
来源：http://dali.jinqigufen.top/Article/details/gteekgryld.html

[S53] C++：移动语义
来源：http://dali.jinqigufen.top/Article/details/gtypgwfgvx.html

std::vector<int> w = std::move(v);
来源：http://dali.meibo888.top/Article/details/gtmmggbeif.html

[S54] C++：异常处理
来源：http://dali.hnqzz.top/Article/details/gtekzmnils.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.jqgfzy.top/Article/details/gtpcawieeu.html

[S55] C++：结构化绑定
来源：http://dali.nanxuanxn.top/Article/details/gtymsqdkrm.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zdqjudy.top/Article/details/gtrfefpmrx.html

[S56] C++：optional
来源：http://dali.cheryme.top/Article/details/gtqzhzoeey.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.gzhubu.top/Article/details/gtghtqywfk.html

[S57] C++：编译期常量
来源：http://dali.yangfankeji.com/Article/details/gteolftlny.html

constexpr int N = 10;
来源：http://dali.jinqigufen.top/Article/details/gtwftdeqpq.html

[S58] C++：命名空间
来源：http://dali.ppjwa.cn/Article/details/gtiyfypnod.html

namespace ns { int f() { return 1; } }
来源：http://dali.yangfankeji.com/Article/details/gtdqnhtniy.html

[S59] C++：静态断言
来源：http://dali.chenjidiqi.icu/Article/details/gtypqlaqxn.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.ppjwa.cn/Article/details/gtmtvkwocf.html

[S60] C++：遍历并删除元素
来源：http://dali.gogol.net.cn/Article/details/gtwwsnoffb.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.guowangkeji.top/Article/details/gtlinofydm.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtttumdgrt.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.jqgfzy.top/Article/details/gtbhmrervq.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gteifrqxjt.html

[T01] Kotlin：Hello World
来源：http://dali.daria6918.cn/Article/details/gtematnskc.html

println("Hello")
来源：http://dali.yangfankeji.com/Article/details/gtyeihyxeg.html

[T02] Kotlin：变量
来源：http://dali.gotoacloud.top/Article/details/gtjqqimeki.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.daria6918.cn/Article/details/gtwnziilxg.html

[T03] Kotlin：字符串模板
来源：http://dali.zdqjudy.top/Article/details/gtrvlmhrsc.html

"值: $b"
来源：http://dali.aizwys.cn/Article/details/gtzhdtczgn.html

[T04] Kotlin：空安全
来源：http://dali.dashuyun.cn/Article/details/gtaprwsloc.html

val n: String? = null;  n?.length
来源：http://dali.ydzc1.top/Article/details/gtygyjhfud.html

[T05] Kotlin：when 表达式
来源：http://dali.yj202588.top/Article/details/gtuydunumc.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.yj20258.top/Article/details/gtifrqcbaq.html

[T06] Kotlin：集合映射
来源：http://dali.kuanghao11.cn/Article/details/gtxmhdrgkt.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.ppjwa.cn/Article/details/gtjkdpyssn.html

[T07] Kotlin：集合过滤
来源：http://dali.yanxiufei.cn/Article/details/gtekebnrgv.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.yj20258888.top/Article/details/gtdvqclkpy.html

[T08] Kotlin：数据类
来源：http://dali.jqgufenzy.top/Article/details/gtgrxyrgbg.html

data class User(val name: String, val age: Int)
来源：http://dali.yj20258.top/Article/details/gtayelrdnx.html

[T09] Kotlin：扩展函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtskltoswi.html

fun String.exclaim() = this + "!"
来源：http://dali.jinqigfzy.top/Article/details/gtuudhdxcw.html

[T10] Kotlin：默认参数
来源：http://dali.kuanghao11.cn/Article/details/gtxrgzvvny.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.jqgfzy.top/Article/details/gthmvutlhg.html

[T11] Kotlin：协程
来源：http://dali.yanxiufei.cn/Article/details/gtjcdfhrll.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.tanke756.top/Article/details/gtfolgojso.html

[T12] Kotlin：解构声明
来源：http://dali.jlsjyb.cn/Article/details/gtkwkioeqi.html

val (a, b) = Pair(1, 2)
来源：http://dali.pycfn.com/Article/details/gtliphzxtu.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gtfljinzax.html

val m = mapOf("a" to 1)
来源：http://dali.wangshuangyany.cn/Article/details/gtcobcxlev.html

[T14] Kotlin：循环
来源：http://dali.hnqzz.top/Article/details/gtsvxtanho.html

for (i in 1..10) println(i)
来源：http://dali.aizwys.cn/Article/details/gtmbpblekk.html

[T15] Kotlin：接口
来源：http://dali.fzhhl.top/Article/details/gtfqpyugxv.html

interface Shape { fun area(): Double }
来源：http://dali.sxryk.cn/Article/details/gtnqnntvmu.html

[T16] Swift：Hello World
来源：http://dali.svipenyu.cn/Article/details/gtrzezwteb.html

print("Hello")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrpnmrevr.html

[T17] Swift：变量与常量
来源：http://dali.gaohongyu789.top/Article/details/gtbjjgpuhe.html

var a = 1;  let b = 2
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkfsrlnjb.html

[T18] Swift：字符串插值
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcjwgzwwh.html

"值: \(b)"
来源：http://dali.cheryme.top/Article/details/gtvzrrnecb.html

[T19] Swift：可选绑定
来源：http://dali.xylfe.cn/Article/details/gthubzlyqd.html

if let n = opt { print(n) }
来源：http://dali.meibo888.top/Article/details/gtlonlftoy.html

[T20] Swift：数组操作
来源：http://dali.fengsongda.top/Article/details/gtcabdkprn.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.chenjidiqi.icu/Article/details/gtqypwlafa.html

[T21] Swift：遍历
来源：http://dali.sufxvd.cn/Article/details/gtawrqqdnu.html

for x in a { print(x) }
来源：http://dali.zhoulong.xyz/Article/details/gtawoxtcmp.html

[T22] Swift：字典
来源：http://dali.sxryk.cn/Article/details/gtvmkhxxgb.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.yanxiufei.cn/Article/details/gtyalfwsvj.html

[T23] Swift：函数
来源：http://dali.yvedp.cn/Article/details/gtocdrteew.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.havefunace.top/Article/details/gtyvdvtekw.html

[T24] Swift：闭包
来源：http://dali.smart0.xyz/Article/details/gtqrlzpsao.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.yueranfly.top/Article/details/gtnodjojdy.html

[T25] Swift：结构体
来源：http://dali.gaohongyu789.top/Article/details/gtswhkxrpo.html

struct P { var x: Int }
来源：http://dali.zhongyouzk.top/Article/details/gtmgjapvvf.html

[T26] Swift：类与重写
来源：http://dali.daria6918.cn/Article/details/gtxttucuul.html

class A: Base { override func f() {} }
来源：http://dali.yanxiufei.cn/Article/details/gtcfbdulbs.html

[T27] Swift：错误处理
来源：http://dali.hnxiangtu.top/Article/details/gtxdwswdee.html

do { try f() } catch { print(error) }
来源：http://dali.birdmap.top/Article/details/gtcvenjwmi.html

[T28] Swift：枚举
来源：http://dali.jianghu66.top/Article/details/gtvqlgittm.html

enum Color { case red, green }
来源：http://dali.c1oappe.top/Article/details/gtoriyeufs.html

[T29] Swift：guard 提前返回
来源：http://dali.ppjwa.cn/Article/details/gthauocbvb.html

guard let x = opt else { return }
来源：http://dali.fengsongda.top/Article/details/gtrjwariaj.html

[T30] Swift：协议
来源：http://dali.wangdashe.top/Article/details/gtihnkxwlt.html

protocol Shape { func area() -> Double }
来源：http://dali.zhiwuduotai.top/Article/details/gtsodouhmy.html

[T31] Lua：Hello World
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvqcfotwp.html

print("Hello")
来源：http://dali.fzhhl.top/Article/details/gteepmabmw.html

[T32] Lua：局部变量
来源：http://dali.shanyushiyangtech.top/Article/details/gtezpoelfg.html

local a = 1
来源：http://dali.dashuyun.cn/Article/details/gtyhkepmak.html

[T33] Lua：表（数组）
来源：http://dali.gotoacloud.top/Article/details/gtzuawizfz.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.yangfankeji.com/Article/details/gtfiaqyigj.html

[T34] Lua：遍历表
来源：http://dali.hysaishi.cn/Article/details/gtbfyckclk.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.hywenlv.cn/Article/details/gtdahqnxnz.html

[T35] Lua：字典表
来源：http://dali.jinqigfzy.top/Article/details/gtvfuulxxz.html

local d = { a = 1 };  d.b = 2
来源：http://dali.hfpthk.cn/Article/details/gtdaysrumy.html

[T36] Lua：函数
来源：http://dali.ivvv.top/Article/details/gtkexwjgml.html

function add(a, b) return a + b end
来源：http://dali.jinghuilouyu.cn/Article/details/gtyzvzmanb.html

[T37] Lua：字符串拼接
来源：http://dali.hywenlv.cn/Article/details/gtizxvfivq.html

"a" .. "b"
来源：http://dali.shzxlz.cn/Article/details/gtohbcdfgx.html

[T38] Lua：条件
来源：http://dali.pengpengdd.cyou/Article/details/gtoiiegrmk.html

if x > 0 then print("正") end
来源：http://dali.shuidangran.top/Article/details/gtbyssezzb.html

[T39] Lua：模式匹配
来源：http://dali.zhaomingkeji.xyz/Article/details/gtofjxywkb.html

string.find(s, "%d+")
来源：http://dali.dashuyun.cn/Article/details/gtzwyytror.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gtyloapoig.html

setmetatable({}, { __index = base })
来源：http://dali.xuanzx.com/Article/details/gtnfzwpwxu.html

[T41] Perl：Hello World
来源：http://dali.yvedp.cn/Article/details/gtmvypfitg.html

print "Hello\n";
来源：http://dali.yvedp.cn/Article/details/gthngfdmbc.html

[T42] Perl：变量类型
来源：http://dali.gotoacloud.top/Article/details/gtklixcejz.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.haohaochexian.top/Article/details/gttvddjmvs.html

[T43] Perl：字符串插值
来源：http://dali.jqgufenzy.top/Article/details/gtytjgvyfl.html

"值: $a"
来源：http://dali.daxiang520.top/Article/details/gtyuewrvoj.html

[T44] Perl：条件
来源：http://dali.havefunace.top/Article/details/gtrqrdpqcb.html

if ($a > 0) { print "正"; }
来源：http://dali.zdqjudy.top/Article/details/gtvtyukomy.html

[T45] Perl：数组遍历
来源：http://dali.dashuyun.cn/Article/details/gtxnebdtab.html

for my $x (@arr) { print $x; }
来源：http://dali.sxryk.cn/Article/details/gtmnthryja.html

[T46] Perl：哈希操作
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnuoeitxh.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.redwolf501.top/Article/details/gtdcnvfouz.html

[T47] Perl：正则捕获
来源：http://dali.aizwys.cn/Article/details/gtcgrjwfmd.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.yonumen.top/Article/details/gtzobqnxof.html

[T48] Perl：正则替换
来源：http://dali.xylfe.cn/Article/details/gtmotpwaya.html

$s =~ s/old/new/g;
来源：http://dali.jqgfzy.top/Article/details/gtiqzucdlp.html

[T49] Perl：函数
来源：http://dali.ybcxt.top/Article/details/gthpgzuysr.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.iojbl.cn/Article/details/gtrbuctewo.html

[T50] Perl：逐行读文件
来源：http://dali.cdnleiting.top/Article/details/gtzbpzpnwv.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.shuidangran.top/Article/details/gtgfimvxfb.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.cucudq.cn/Article/details/gtghmyixtk.html

[T51] Scala：Hello World
来源：http://dali.zhengqikj.top/Article/details/gtwzmojbro.html

println("Hello")
来源：http://dali.cheryme.top/Article/details/gtwumijkxy.html

[T52] Scala：变量
来源：http://dali.cucudq.cn/Article/details/gtdlhlmvyn.html

val a = 1;  var b = 2
来源：http://dali.kuanghao11.cn/Article/details/gtgmlhfwwm.html

[T53] Scala：字符串插值
来源：http://dali.aizwys.cn/Article/details/gtxjozvkyc.html

s"值: $b"
来源：http://dali.nwbrower.top/Article/details/gtokojmnwo.html

[T54] Scala：集合映射
来源：http://dali.sweek.top/Article/details/gtwxjeayon.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.wangdashe.top/Article/details/gtrwnzjzuc.html

[T55] Scala：集合过滤
来源：http://dali.havefunace.top/Article/details/gtprumvezo.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.yueranfly.top/Article/details/gtllfbzrqh.html

[T56] Scala：样例类
来源：http://dali.316326.xyz/Article/details/gtwlluyllr.html

case class User(name: String, age: Int)
来源：http://dali.jinqigufen.top/Article/details/gtwzsgfcpx.html

[T57] Scala：模式匹配
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtikmkjfkh.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhaomingkeji.xyz/Article/details/gttskktsut.html

[T58] Scala：函数定义
来源：http://dali.ppjwa.cn/Article/details/gtknhgacld.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.shzxlz.cn/Article/details/gtibqzhelu.html

[T59] Scala：循环
来源：http://dali.yonumen.top/Article/details/gtdoeejynp.html

for (i <- 1 to 10) println(i)
来源：http://dali.gzhubu.top/Article/details/gtuzkaatqd.html

[T60] Scala：折叠
来源：http://dali.ppjwa.cn/Article/details/gtpzvzcrdi.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.tianlin.xyz/Article/details/gtsjnvsxlw.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtrgzsckzq.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.shangyingyoupin.top/Article/details/gtzogndjef.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtmbmlpguu.html

[U01] Py：创建虚拟环境
来源：http://dali.tanke756.top/Article/details/gtjbtpzsda.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.shuidangran.top/Article/details/gtlvmujptz.html

[U02] Py：导出 / 安装依赖
来源：http://dali.316326.xyz/Article/details/gttipnptcm.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.aibaodan.cn/Article/details/gtzkeqbrmj.html

[U03] Py：加载 .env 配置
来源：http://dali.zhongyouzk.top/Article/details/gtbizqkkqu.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhengqikj.top/Article/details/gtlexxxcza.html

[U04] Py：变量调试打印
来源：http://dali.hammf.cn/Article/details/gttenhjhih.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.vqdsnc.cn/Article/details/gtptupwcte.html

[U05] Py：列表去重且保序
来源：http://dali.feifeiyinyue.top/Article/details/gtwyvpqzpa.html

list(dict.fromkeys(arr))
来源：http://dali.xuetiantiany.cn/Article/details/gtahjnvnhw.html

[U06] Py：合并两个字典
来源：http://dali.shuidangran.top/Article/details/gtsrkjgkxj.html

{**a, **b}
来源：http://dali.sweek.top/Article/details/gtmkvjnzjk.html


<!-- 参考信息 -->