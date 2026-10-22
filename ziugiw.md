代发 wailian999

df -h;  du -sh *
来源：http://dali.bjfxy.top/Article/details/gtekothfra.html

[R62] 找最占空间的文件
来源：http://dali.cheryme.top/Article/details/gtsxsgimlo.html

du -ah . | sort -rh | head -10
来源：http://dali.jyoumei.cn/Article/details/gtwahkjfij.html

[R63] 内存与进程
来源：http://dali.xziqi.cn/Article/details/gtidtrblrg.html

free -h;  ps aux | grep nginx
来源：http://dali.xuanzx.com/Article/details/gtinnqxoxf.html

[R64] 结束进程
来源：http://dali.vqdsnc.cn/Article/details/gtdipjmlif.html

kill -9 $(pgrep -f app.py)
来源：http://dali.yangfankeji.com/Article/details/gtqofcoyfy.html

[R65] 查看端口占用
来源：http://dali.guannengcc.top/Article/details/gtptikozgd.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.yj20258.top/Article/details/gtnrbsdroo.html

[R66] 定时任务
来源：http://dali.shuidangran.top/Article/details/gtgjjyeyim.html

crontab -e;  crontab -l
来源：http://dali.9152youxi.cn/Article/details/gttuxutuiv.html

[R67] 生成随机十六进制串
来源：http://dali.shuidangran.top/Article/details/gtmehbdfca.html

openssl rand -hex 16
来源：http://dali.cheryme.top/Article/details/gtbpsoohla.html

[R68] 计算文件校验值
来源：http://dali.xinyue.icu/Article/details/gtvxzgjzvl.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlqevfjuu.html

[R69] 生成随机密码
来源：http://dali.dianchejie.cn/Article/details/gtqzchrijd.html

head -c 16 /dev/urandom | base64
来源：http://dali.vqdsnc.cn/Article/details/gtjqfrkpcb.html

[R70] 时间戳与互转
来源：http://dali.zhengqikj.top/Article/details/gtttelcehg.html

date +%s;  date -d @1700000000
来源：http://dali.jqgufenzy.top/Article/details/gtjqftlhjh.html

[R71] 日期格式化
来源：http://dali.ivvv.top/Article/details/gtqxqluuwe.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.sysykeji.top/Article/details/gtobtdkjit.html

[R72] 等待端口就绪
来源：http://dali.zhongyouzk.top/Article/details/gtlvkyurma.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.yangfankeji.com/Article/details/gtlivrledo.html

[R73] 分割大日志
来源：http://dali.chenlongwang.top/Article/details/gtxavhprab.html

split -l 1000 big.log part_
来源：http://dali.snrcjt.cn/Article/details/gtpxwbrdrx.html

[R74] 批量重命名
来源：http://dali.sweek.top/Article/details/gtfehjiity.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.jqgufenzy.top/Article/details/gtpiabsrrm.html

[R75] 导出环境变量
来源：http://dali.havefunace.top/Article/details/gtrrcjriap.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdutermpb.html

[R76] 使用临时文件
来源：http://dali.chenzaomai.com/Article/details/gtiamfmafh.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.ppjwa.cn/Article/details/gtlsapprvo.html

[R77] 读取用户输入
来源：http://dali.havefunace.top/Article/details/gtdwknblwh.html

read -rp "请输入: " ans
来源：http://dali.yueranfly.top/Article/details/gtpzhukjzw.html

[R78] 交互式菜单
来源：http://dali.hfpthk.cn/Article/details/gtkmapurdj.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.yvedp.cn/Article/details/gtkiemmzkp.html

[R79] 解析命令行选项
来源：http://dali.yj202588.top/Article/details/gtswqzyjni.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.316326.xyz/Article/details/gtsbeljykm.html

[R80] 查看脚本执行耗时
来源：http://dali.ehwqpu.com/Article/details/gtfcfkcoye.html

time ./run.sh
来源：http://dali.c1oappe.top/Article/details/gtetbbjbdn.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtqtfduora.html

S. C / C++ 专题
来源：http://dali.sysykeji.top/Article/details/gtkelrsfmm.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gttakgmcid.html

[S01] C：Hello World
来源：http://dali.jianghu66.top/Article/details/gtuckfqlyv.html

#include <stdio.h>
来源：http://dali.xuetiantiany.cn/Article/details/gtyjwaatil.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.jinqigufen.top/Article/details/gtmycxmdfa.html

[S02] C：变量与格式化输出
来源：http://dali.c1oappe.top/Article/details/gtkdspqfdu.html

int a = 10; printf("%d\n", a);
来源：http://dali.smart0.xyz/Article/details/gtcihkvbsy.html

[S03] C：读入整数
来源：http://dali.jyoumei.cn/Article/details/gtqgtusnqx.html

int x; scanf("%d", &x);
来源：http://dali.fzhhl.top/Article/details/gttyofcuam.html

[S04] C：字符串复制
来源：http://dali.jianghu66.top/Article/details/gtozgrigwb.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.yangfankeji.com/Article/details/gtmfkswdbr.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gtkzzdgpnq.html

strlen(s)
来源：http://dali.yuxming.cn/Article/details/gtemitmmgf.html

[S06] C：字符串比较
来源：http://dali.aibaodan.cn/Article/details/gtlcuyheht.html

strcmp(a, b) == 0
来源：http://dali.yongpay.top/Article/details/gtdabxqjwq.html

[S07] C：数组遍历求和
来源：http://dali.shuidangran.top/Article/details/gtlbnicaxm.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.hysaishi.cn/Article/details/gtctomvprp.html

[S08] C：动态内存分配与释放
来源：http://dali.c1oappe.top/Article/details/gtsvttxklz.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.cqqwz.cn/Article/details/gtuytprlss.html

[S09] C：结构体定义与初始化
来源：http://dali.zhoulong.xyz/Article/details/gtosfxykki.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.cucudq.cn/Article/details/gtzsfugkqk.html

[S10] C：指针与解引用
来源：http://dali.jqgufenzy.top/Article/details/gtkgtudips.html

int *p = &a;  *p = 5;
来源：http://dali.bjfxy.top/Article/details/gtqycukrwx.html

[S11] C：逐行读文件
来源：http://dali.yonumen.top/Article/details/gtujvbhkzr.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.wangshuangyany.cn/Article/details/gtoixyirwp.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.cqqwz.cn/Article/details/gtgnlujdyc.html

fclose(f);
来源：http://dali.zdqjudy.top/Article/details/gthuoqknjy.html

[S12] C：写文件
来源：http://dali.cdnleiting.top/Article/details/gtkhertptx.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.jyoumei.cn/Article/details/gtlpfdgall.html

[S13] C：宏定义
来源：http://dali.chenjidiqi.icu/Article/details/gtiowrgjzj.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.xziqi.cn/Article/details/gtnberskrq.html

[S14] C：枚举
来源：http://dali.chenlongwang.top/Article/details/gtrzvhdhrx.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.guowangkeji.top/Article/details/gttcmiwcxj.html

[S15] C：类型转换
来源：http://dali.snrcjt.cn/Article/details/gtmworzban.html

(double) a / b
来源：http://dali.ivvv.top/Article/details/gtzfszppmt.html

[S16] C：位操作置位
来源：http://dali.nanxuanxn.top/Article/details/gtnlzsefrt.html

x |= (1 << 3);
来源：http://dali.hnxiangtu.top/Article/details/gtolrrhcvk.html

[S17] C：安全拼接字符串
来源：http://dali.sysykeji.top/Article/details/gtlixjcwyl.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.yueranfly.top/Article/details/gtadmgzlco.html

[S18] C：命令行参数
来源：http://dali.zhixingplan.top/Article/details/gtvvlszztk.html

int main(int argc, char **argv)
来源：http://dali.xinyue.icu/Article/details/gtaobytnpi.html

[S19] C：快速排序
来源：http://dali.dashuyun.cn/Article/details/gtcdvvykaf.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.daxiang520.top/Article/details/gtogxqzdtt.html

[S20] C：二分查找
来源：http://dali.gaohongyu789.top/Article/details/gtykxckivb.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.dianchejie.cn/Article/details/gtenzqcswx.html

[S21] C：字符类别判断
来源：http://dali.pengpengdd.cyou/Article/details/gtojtibxdx.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gtpajyfhqy.html

[S22] C：字符串转数字
来源：http://dali.tian-w.cn/Article/details/gtffbfffoq.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.aibaodan.cn/Article/details/gtqlkjiuwz.html

[S23] C：随机数
来源：http://dali.ydzc1.top/Article/details/gtqzgedoqw.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.jiagoushi.top/Article/details/gtxuzoeuza.html

[S24] C：获取本地时间
来源：http://dali.aibaodan.cn/Article/details/gtsamjqlyk.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.cdnleiting.top/Article/details/gtoaiukcwa.html

[S25] C：内存拷贝
来源：http://dali.pengpengdd.cyou/Article/details/gtplolmvfw.html

memcpy(dst, src, n);
来源：http://dali.jinqigfzy.top/Article/details/gtpqtnziep.html

[S26] C：内存清零
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthpiisgkf.html

memset(a, 0, sizeof a);
来源：http://dali.aibaodan.cn/Article/details/gtcfxjwmgr.html

[S27] C：定义常量
来源：http://dali.cashguo.top/Article/details/gtzbjotqet.html

const double PI = 3.14159;
来源：http://dali.dianchejie.cn/Article/details/gtczifvuho.html

[S28] C：静态变量
来源：http://dali.smart0.xyz/Article/details/gtaawcgujz.html

static int counter = 0;
来源：http://dali.xuanzx.com/Article/details/gtwkkbqyvg.html

[S29] C：变参函数
来源：http://dali.yangfankeji.com/Article/details/gtyyqzbdug.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.0kj1m.cn/Article/details/gtvtovtqan.html

[S30] C：头文件保护
来源：http://dali.vqdsnc.cn/Article/details/gthquqfnjz.html

#ifndef X_H
来源：http://dali.xziqi.cn/Article/details/gtdxphfldo.html

#define X_H
来源：http://dali.redwolf501.top/Article/details/gtxzaanjfs.html

#endif
来源：http://dali.ydzc1.top/Article/details/gtsukbjtrj.html

[S31] C++：Hello World
来源：http://dali.yj20258.top/Article/details/gtpgchpwoo.html

#include <iostream>
来源：http://dali.hnqzz.top/Article/details/gtghqgmhpq.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.cucudq.cn/Article/details/gtyyddarse.html

[S32] C++：字符串
来源：http://dali.pycfn.com/Article/details/gtbphqqhhg.html

std::string s = "hi";  s += "!";
来源：http://dali.ybcxt.top/Article/details/gtbxiueolb.html

[S33] C++：vector 增删
来源：http://dali.shanyushiyangkeji.top/Article/details/gtggeueblp.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.meibo888.top/Article/details/gttgphvrqv.html

[S34] C++：遍历 vector
来源：http://dali.jlsjyb.cn/Article/details/gthrswlilw.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.pengpengdd.cyou/Article/details/gtuhjkefwn.html

[S35] C++：map
来源：http://dali.havefunace.top/Article/details/gtelazwyxd.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.iojbl.cn/Article/details/gtqfqtcwkm.html

[S36] C++：unordered_map
来源：http://dali.jinyuanbaomall.cn/Article/details/gthqztzvee.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hfpthk.cn/Article/details/gtbqbwahdd.html

[S37] C++：set
来源：http://dali.yueranfly.top/Article/details/gtexokuaas.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.wangdashe.top/Article/details/gtzwkqpotm.html

[S38] C++：排序
来源：http://dali.zhongyouzk.top/Article/details/gtwoooqqbb.html

std::sort(v.begin(), v.end());
来源：http://dali.0kj1m.cn/Article/details/gtdggmggvy.html

[S39] C++：自定义比较器排序
来源：http://dali.daxiang520.top/Article/details/gtwophnhiv.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.nanxuanxn.top/Article/details/gtnvjwnjul.html

[S40] C++：查找元素
来源：http://dali.andypj.xyz/Article/details/gteszbrqfj.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.wangdashe.top/Article/details/gtutcpmmts.html

[S41] C++：类与构造函数
来源：http://dali.sweek.top/Article/details/gtnsudrkzj.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.yj20258.top/Article/details/gtvzdxkogt.html

[S42] C++：继承与虚函数
来源：http://dali.jinghuilouyu.cn/Article/details/gtaldckqtk.html

class B : public Base { public: void f() override {} };
来源：http://dali.redwolf501.top/Article/details/gtzpvctkeg.html

[S43] C++：智能指针
来源：http://dali.meibo888.top/Article/details/gtghgqmkwi.html

auto p = std::make_unique<int>(5);
来源：http://dali.yj20258.top/Article/details/gtafoyjmwq.html

[S44] C++：引用传参
来源：http://dali.jiagoushi.top/Article/details/gtsfyaxazf.html

void inc(int &x) { ++x; }
来源：http://dali.cucudq.cn/Article/details/gtveiultyk.html

[S45] C++：lambda
来源：http://dali.wangdashe.top/Article/details/gtfgbjdvzm.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.sysykeji.top/Article/details/gthipjfusc.html

[S46] C++：函数模板
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgkvyuyxs.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.fzhhl.top/Article/details/gtqwcwlxts.html

[S47] C++：结构化绑定遍历
来源：http://dali.nwbrower.top/Article/details/gteyyzuygd.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.fzhhl.top/Article/details/gtrnqhdtfy.html

[S48] C++：逐行读文件
来源：http://dali.gotoacloud.top/Article/details/gtappbnhfe.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.gogol.net.cn/Article/details/gtmvmvelsn.html

while (std::getline(in, line)) { }
来源：http://dali.jinghuilouyu.cn/Article/details/gtdmnaygjo.html

[S49] C++：写文件
来源：http://dali.aibaodan.cn/Article/details/gtkkdfnrcx.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwsllpzfw.html

[S50] C++：格式化数字
来源：http://dali.zhaomingkeji.xyz/Article/details/gtskonlerj.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.yvedp.cn/Article/details/gtqqicxifk.html

[S51] C++：显式类型转换
来源：http://dali.yonumen.top/Article/details/gttnicgatd.html

static_cast<double>(a) / b
来源：http://dali.yj20258.top/Article/details/gtwgxvpcea.html

[S52] C++：const 与 noexcept
来源：http://dali.sxryk.cn/Article/details/gtjvyicwhh.html

int size() const noexcept { return n_; }
来源：http://dali.xuanzx.com/Article/details/gtzgprncux.html

[S53] C++：移动语义
来源：http://dali.9152youxi.cn/Article/details/gtszqcpifc.html

std::vector<int> w = std::move(v);
来源：http://dali.gaohongyu789.top/Article/details/gtnaowtahp.html

[S54] C++：异常处理
来源：http://dali.cheryme.top/Article/details/gtmpjghnhx.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.xuetiantiany.cn/Article/details/gtpaxcbjje.html

[S55] C++：结构化绑定
来源：http://dali.kuanghao11.cn/Article/details/gtpxnadgyd.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgoyqsqmx.html

[S56] C++：optional
来源：http://dali.gotoacloud.top/Article/details/gtoxiscaxf.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.hysaishi.cn/Article/details/gtcjtimmew.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gthuhgmefd.html

constexpr int N = 10;
来源：http://dali.yj20258.top/Article/details/gtfjuderrm.html

[S58] C++：命名空间
来源：http://dali.gogol.net.cn/Article/details/gtligjhosk.html

namespace ns { int f() { return 1; } }
来源：http://dali.chenlongwang.top/Article/details/gthlbnxkcn.html

[S59] C++：静态断言
来源：http://dali.kuanghao11.cn/Article/details/gtwsebqxmx.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.jyoumei.cn/Article/details/gtgxnzhton.html

[S60] C++：遍历并删除元素
来源：http://dali.zhongyouzk.top/Article/details/gtwuwifbpp.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhiwuduotai.top/Article/details/gtchcsfxgh.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtcvlmbngz.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.birdmap.top/Article/details/gtgmohqduh.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtgcfmyrzm.html

[T01] Kotlin：Hello World
来源：http://dali.chenjidiqi.icu/Article/details/gtazcgfpdn.html

println("Hello")
来源：http://dali.wangdashe.top/Article/details/gtunpwxydu.html

[T02] Kotlin：变量
来源：http://dali.xuetiantiany.cn/Article/details/gtfqmchwaw.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.jyoumei.cn/Article/details/gtolbxuvpq.html

[T03] Kotlin：字符串模板
来源：http://dali.yanxiufei.cn/Article/details/gthtlvkqlx.html

"值: $b"
来源：http://dali.yongpay.top/Article/details/gtsldrymhr.html

[T04] Kotlin：空安全
来源：http://dali.jiagoushi.top/Article/details/gtyfvtxmkq.html

val n: String? = null;  n?.length
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdcbeqvrz.html

[T05] Kotlin：when 表达式
来源：http://dali.iojbl.cn/Article/details/gtwqnrbvfg.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.cheryme.top/Article/details/gthwkdhuwn.html

[T06] Kotlin：集合映射
来源：http://dali.sufxvd.cn/Article/details/gtjlnbjppf.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.yongpay.top/Article/details/gtkxowvcke.html

[T07] Kotlin：集合过滤
来源：http://dali.zhixingplan.top/Article/details/gtoqysmnja.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.cdnleiting.top/Article/details/gtcqobvkyr.html

[T08] Kotlin：数据类
来源：http://dali.gotoacloud.top/Article/details/gtuqaxrmla.html

data class User(val name: String, val age: Int)
来源：http://dali.feifeiyinyue.top/Article/details/gtkpmafwsy.html

[T09] Kotlin：扩展函数
来源：http://dali.guannengcc.top/Article/details/gtshuszdbk.html

fun String.exclaim() = this + "!"
来源：http://dali.jianghu66.top/Article/details/gtlzbhdnci.html

[T10] Kotlin：默认参数
来源：http://dali.chenlongwang.top/Article/details/gtjzgcfylc.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.jiagoushi.top/Article/details/gteypaivrj.html

[T11] Kotlin：协程
来源：http://dali.gotoacloud.top/Article/details/gtssfsbyqc.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.jiagoushi.top/Article/details/gtpaewjvwy.html

[T12] Kotlin：解构声明
来源：http://dali.yonumen.top/Article/details/gtrtheucgw.html

val (a, b) = Pair(1, 2)
来源：http://dali.tianlin.xyz/Article/details/gtopvudygz.html

[T13] Kotlin：只读 Map
来源：http://dali.iojbl.cn/Article/details/gtepoxwyrr.html

val m = mapOf("a" to 1)
来源：http://dali.birdmap.top/Article/details/gtkxezkiow.html

[T14] Kotlin：循环
来源：http://dali.fengsongda.top/Article/details/gtdtyrznjo.html

for (i in 1..10) println(i)
来源：http://dali.yuxming.cn/Article/details/gtzqqmqgbe.html

[T15] Kotlin：接口
来源：http://dali.jyoumei.cn/Article/details/gtdgoeqmji.html

interface Shape { fun area(): Double }
来源：http://dali.daria6918.cn/Article/details/gtnxwyfort.html

[T16] Swift：Hello World
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvumotrgm.html

print("Hello")
来源：http://dali.yvedp.cn/Article/details/gtiktzjvpa.html

[T17] Swift：变量与常量
来源：http://dali.mhx1999.top/Article/details/gtpqeoqjcm.html

var a = 1;  let b = 2
来源：http://dali.chenjidiqi.icu/Article/details/gtjndyphwa.html

[T18] Swift：字符串插值
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrmxvbbix.html

"值: \(b)"
来源：http://dali.zycfv.cn/Article/details/gtfjzewbzt.html

[T19] Swift：可选绑定
来源：http://dali.fzhhl.top/Article/details/gtodtocnwa.html

if let n = opt { print(n) }
来源：http://dali.hywenlv.cn/Article/details/gtiixojzxp.html

[T20] Swift：数组操作
来源：http://dali.nwbrower.top/Article/details/gterarbhil.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.shanyushiyangtech.top/Article/details/gtjdkbdarz.html

[T21] Swift：遍历
来源：http://dali.c1oappe.top/Article/details/gtvfwiqdjq.html

for x in a { print(x) }
来源：http://dali.shzxlz.cn/Article/details/gtvynzukdy.html

[T22] Swift：字典
来源：http://dali.xuetiantiany.cn/Article/details/gtnusqfjna.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.yvedp.cn/Article/details/gtkflwvcnh.html

[T23] Swift：函数
来源：http://dali.sysykeji.top/Article/details/gtzavfnyom.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.birdmap.top/Article/details/gtitwynwff.html

[T24] Swift：闭包
来源：http://dali.shzxlz.cn/Article/details/gtilfbjwsp.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.tanke756.top/Article/details/gtalqrtgij.html

[T25] Swift：结构体
来源：http://dali.gaohongyu789.top/Article/details/gtwhdufagy.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gtrzssmmin.html

[T26] Swift：类与重写
来源：http://dali.yj202588.top/Article/details/gtpmatmouw.html

class A: Base { override func f() {} }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuonmjwrp.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gtojabvhhi.html

do { try f() } catch { print(error) }
来源：http://dali.zhongyouzk.top/Article/details/gtrdtsctzv.html

[T28] Swift：枚举
来源：http://dali.andypj.xyz/Article/details/gtbfxsfsfb.html

enum Color { case red, green }
来源：http://dali.havefunace.top/Article/details/gtbzdroxsw.html

[T29] Swift：guard 提前返回
来源：http://dali.zhongyouzk.top/Article/details/gttankyxng.html

guard let x = opt else { return }
来源：http://dali.guannengcc.top/Article/details/gttkwhdarn.html

[T30] Swift：协议
来源：http://dali.ydzc1.top/Article/details/gtdbxyvktk.html

protocol Shape { func area() -> Double }
来源：http://dali.guowangkeji.top/Article/details/gtvbldqcee.html

[T31] Lua：Hello World
来源：http://dali.hysaishi.cn/Article/details/gtnuhkhlqx.html

print("Hello")
来源：http://dali.fengsongda.top/Article/details/gttmyvfwug.html

[T32] Lua：局部变量
来源：http://dali.sweek.top/Article/details/gtrjjvwztu.html

local a = 1
来源：http://dali.zhixingplan.top/Article/details/gtzvjnretz.html

[T33] Lua：表（数组）
来源：http://dali.tian-w.cn/Article/details/gtigjhlwlr.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.guowangkeji.top/Article/details/gtanwoztfx.html

[T34] Lua：遍历表
来源：http://dali.snrcjt.cn/Article/details/gtfhkcvcdm.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.yuanzhike.top/Article/details/gtrjgerrnv.html

[T35] Lua：字典表
来源：http://dali.nwbrower.top/Article/details/gtytxoqmrc.html

local d = { a = 1 };  d.b = 2
来源：http://dali.gzhubu.top/Article/details/gtgquelucj.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gtdfwhluoq.html

function add(a, b) return a + b end
来源：http://dali.chenlongwang.top/Article/details/gtluonbpaa.html

[T37] Lua：字符串拼接
来源：http://dali.jianghu66.top/Article/details/gtjhpewuvl.html

"a" .. "b"
来源：http://dali.aibaodan.cn/Article/details/gtlivpgxgn.html

[T38] Lua：条件
来源：http://dali.yueranfly.top/Article/details/gtuhoppkeb.html

if x > 0 then print("正") end
来源：http://dali.daria6918.cn/Article/details/gthericmec.html

[T39] Lua：模式匹配
来源：http://dali.smart0.xyz/Article/details/gtlteugydb.html

string.find(s, "%d+")
来源：http://dali.gaohongyu789.top/Article/details/gtdmqfbvzo.html

[T40] Lua：元表
来源：http://dali.mhx1999.top/Article/details/gtdgfuewux.html

setmetatable({}, { __index = base })
来源：http://dali.yueranfly.top/Article/details/gtwmtdrvzn.html

[T41] Perl：Hello World
来源：http://dali.c1oappe.top/Article/details/gtqnpvyrij.html

print "Hello\n";
来源：http://dali.chenzaomai.com/Article/details/gtynvennkz.html

[T42] Perl：变量类型
来源：http://dali.ydzc1.top/Article/details/gtzvuyyhze.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.hongshengwenyu.top/Article/details/gtaruwhsdc.html

[T43] Perl：字符串插值
来源：http://dali.cdnleiting.top/Article/details/gtjenpugzk.html

"值: $a"
来源：http://dali.nanxuanxn.top/Article/details/gtyyamogwp.html

[T44] Perl：条件
来源：http://dali.nwbrower.top/Article/details/gtpdvezstk.html

if ($a > 0) { print "正"; }
来源：http://dali.yangfankeji.com/Article/details/gtujwzyefd.html

[T45] Perl：数组遍历
来源：http://dali.kuanghao11.cn/Article/details/gtfcizppal.html

for my $x (@arr) { print $x; }
来源：http://dali.daxiang520.top/Article/details/gtjerxytst.html

[T46] Perl：哈希操作
来源：http://dali.nanxuanxn.top/Article/details/gtdqxbolwr.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.xuetiantiany.cn/Article/details/gtudzthtkb.html

[T47] Perl：正则捕获
来源：http://dali.gaohongyu789.top/Article/details/gtkzhtdosh.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.ybcxt.top/Article/details/gtbofvtxzi.html

[T48] Perl：正则替换
来源：http://dali.316326.xyz/Article/details/gtranoicqe.html

$s =~ s/old/new/g;
来源：http://dali.aibaodan.cn/Article/details/gtswwyhyby.html

[T49] Perl：函数
来源：http://dali.yuanzhike.top/Article/details/gtojvdqrgk.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.tian-w.cn/Article/details/gttovklsot.html

[T50] Perl：逐行读文件
来源：http://dali.chenzaomai.com/Article/details/gtezmyztbc.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.chenjidiqi.icu/Article/details/gtwhxbfdeq.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.bjfxy.top/Article/details/gtwtmqewbz.html

[T51] Scala：Hello World
来源：http://dali.gzhubu.top/Article/details/gtpjwypidj.html

println("Hello")
来源：http://dali.jiagoushi.top/Article/details/gtqtqncock.html

[T52] Scala：变量
来源：http://dali.feifeiyinyue.top/Article/details/gtjuasnogg.html

val a = 1;  var b = 2
来源：http://dali.jinqigufen.top/Article/details/gtecrldtpz.html

[T53] Scala：字符串插值
来源：http://dali.nanxinkj.top/Article/details/gtqnrrdhdt.html

s"值: $b"
来源：http://dali.wangdashe.top/Article/details/gttmvxfwic.html

[T54] Scala：集合映射
来源：http://dali.chenzaomai.com/Article/details/gtjiaveggr.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.gotoacloud.top/Article/details/gtznzbjafm.html

[T55] Scala：集合过滤
来源：http://dali.aizwys.cn/Article/details/gtvxylygxk.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.nanxinkj.top/Article/details/gtfjvcgtmg.html

[T56] Scala：样例类
来源：http://dali.quarkkingdee.top/Article/details/gtlregidrh.html

case class User(name: String, age: Int)
来源：http://dali.zhixingplan.top/Article/details/gtkpoqbxmi.html

[T57] Scala：模式匹配
来源：http://dali.chenjidiqi.icu/Article/details/gtpjfoongk.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwklqauzh.html

[T58] Scala：函数定义
来源：http://dali.tian-w.cn/Article/details/gtaqwtczba.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhiwuduotai.top/Article/details/gtljniajvl.html

[T59] Scala：循环
来源：http://dali.cucudq.cn/Article/details/gtxfwyyfli.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhengqikj.top/Article/details/gtgqagkaxf.html

[T60] Scala：折叠
来源：http://dali.nanxuanxn.top/Article/details/gtcjaxykyq.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.vqdsnc.cn/Article/details/gtfqmvcmln.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtnkgwezmq.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.shzxlz.cn/Article/details/gtugysywob.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtcdcjdwkl.html

[U01] Py：创建虚拟环境
来源：http://dali.jiagoushi.top/Article/details/gteiatxuuu.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.hnqzz.top/Article/details/gtzhkzlrlc.html

[U02] Py：导出 / 安装依赖
来源：http://dali.bjfxy.top/Article/details/gtfeysjzwe.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.nanxuanxn.top/Article/details/gtmftauxyd.html


<!-- 参考信息 -->