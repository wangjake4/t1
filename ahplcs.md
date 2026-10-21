代发 wailian999

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.haohaochexian.top/Article/details/gtwcavgiex.html

[R66] 定时任务
来源：http://dali.sysykeji.top/Article/details/gtdnewsbhe.html

crontab -e;  crontab -l
来源：http://dali.daxiang520.top/Article/details/gthulyyigg.html

[R67] 生成随机十六进制串
来源：http://dali.zhoulong.xyz/Article/details/gtxoasybpg.html

openssl rand -hex 16
来源：http://dali.aibaodan.cn/Article/details/gtnbtexkhx.html

[R68] 计算文件校验值
来源：http://dali.hnxiangtu.top/Article/details/gtzyxikyfv.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.yuxming.cn/Article/details/gtaqbkmcou.html

[R69] 生成随机密码
来源：http://dali.iojbl.cn/Article/details/gtkyunaymg.html

head -c 16 /dev/urandom | base64
来源：http://dali.pycfn.com/Article/details/gtlhvccjtf.html

[R70] 时间戳与互转
来源：http://dali.shuidangran.top/Article/details/gtecisrtjc.html

date +%s;  date -d @1700000000
来源：http://dali.nanxinkj.top/Article/details/gttqqizvhl.html

[R71] 日期格式化
来源：http://dali.yj202588.top/Article/details/gtcizpyzch.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.shanyushiyangtech.top/Article/details/gtzmpixcii.html

[R72] 等待端口就绪
来源：http://dali.zhengqikj.top/Article/details/gtpdiqxlxn.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.sufxvd.cn/Article/details/gtlsqddlcv.html

[R73] 分割大日志
来源：http://dali.yuanzhike.top/Article/details/gtwvexchrf.html

split -l 1000 big.log part_
来源：http://dali.meibo888.top/Article/details/gtfsmhndmt.html

[R74] 批量重命名
来源：http://dali.jiagoushi.top/Article/details/gtojetzgef.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.cashguo.top/Article/details/gtfhkoceem.html

[R75] 导出环境变量
来源：http://dali.yj20258888.top/Article/details/gtnvmsxrjg.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.jianghu66.top/Article/details/gtdtugdnqy.html

[R76] 使用临时文件
来源：http://dali.xuetiantiany.cn/Article/details/gtkklkvjmd.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.xuetiantiany.cn/Article/details/gtydzakrvl.html

[R77] 读取用户输入
来源：http://dali.sxryk.cn/Article/details/gtyhytjsrq.html

read -rp "请输入: " ans
来源：http://dali.sweek.top/Article/details/gtskufvhxx.html

[R78] 交互式菜单
来源：http://dali.smart0.xyz/Article/details/gtdsmcsqrg.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.fzhhl.top/Article/details/gtqnguafdz.html

[R79] 解析命令行选项
来源：http://dali.xinyue.icu/Article/details/gtqdhledkf.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.jiagoushi.top/Article/details/gttjxbjdav.html

[R80] 查看脚本执行耗时
来源：http://dali.feifeiyinyue.top/Article/details/gtitbhbzut.html

time ./run.sh
来源：http://dali.havefunace.top/Article/details/gtqbopahee.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtxlhyibdu.html

S. C / C++ 专题
来源：http://dali.ydzc1.top/Article/details/gtcpbyjhyj.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtccbpzheo.html

[S01] C：Hello World
来源：http://dali.daxiang520.top/Article/details/gtmjljgfpi.html

#include <stdio.h>
来源：http://dali.xylfe.cn/Article/details/gtjjlrfetl.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.yanxiufei.cn/Article/details/gtkjvnwmjm.html

[S02] C：变量与格式化输出
来源：http://dali.tianlin.xyz/Article/details/gtfalaumtq.html

int a = 10; printf("%d\n", a);
来源：http://dali.tianlin.xyz/Article/details/gtodmkpqvd.html

[S03] C：读入整数
来源：http://dali.guowangkeji.top/Article/details/gtxxvjaxer.html

int x; scanf("%d", &x);
来源：http://dali.dashuyun.cn/Article/details/gtsmtpalnf.html

[S04] C：字符串复制
来源：http://dali.jinghuilouyu.cn/Article/details/gtkiikhgqp.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.jqgfzy.top/Article/details/gttlremorm.html

[S05] C：字符串长度
来源：http://dali.nanxinkj.top/Article/details/gtharcqblf.html

strlen(s)
来源：http://dali.gogol.net.cn/Article/details/gtbukduipv.html

[S06] C：字符串比较
来源：http://dali.jqgfzy.top/Article/details/gtcxjacdic.html

strcmp(a, b) == 0
来源：http://dali.dianchejie.cn/Article/details/gtojvpzrkv.html

[S07] C：数组遍历求和
来源：http://dali.zhiwuduotai.top/Article/details/gtcapgkwwo.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.jiagoushi.top/Article/details/gtidwkrdoc.html

[S08] C：动态内存分配与释放
来源：http://dali.yj20258888.top/Article/details/gtqgdedjry.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.sysykeji.top/Article/details/gtlhhdihru.html

[S09] C：结构体定义与初始化
来源：http://dali.mhx1999.top/Article/details/gtcbbhqtbl.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.aibaodan.cn/Article/details/gtrxqpcjoa.html

[S10] C：指针与解引用
来源：http://dali.bjfxy.top/Article/details/gtxvyxxlne.html

int *p = &a;  *p = 5;
来源：http://dali.tianlin.xyz/Article/details/gtchwozjpq.html

[S11] C：逐行读文件
来源：http://dali.hnxiangtu.top/Article/details/gtxogmktqg.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.kuanghao11.cn/Article/details/gtpfklslvf.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.cqqwz.cn/Article/details/gtpwlxbghe.html

fclose(f);
来源：http://dali.cdnleiting.top/Article/details/gtwmvjsvme.html

[S12] C：写文件
来源：http://dali.jinqigfzy.top/Article/details/gtgnzxjwxa.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.hysaishi.cn/Article/details/gtfqykykez.html

[S13] C：宏定义
来源：http://dali.jinghuilouyu.cn/Article/details/gtgydaxqyk.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhixingplan.top/Article/details/gtixkzhdpr.html

[S14] C：枚举
来源：http://dali.guowangkeji.top/Article/details/gtrsgycwss.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.gogol.net.cn/Article/details/gthikgkbuu.html

[S15] C：类型转换
来源：http://dali.hammf.cn/Article/details/gtzbdjuckr.html

(double) a / b
来源：http://dali.quarkkingdee.top/Article/details/gtngyyfzzw.html

[S16] C：位操作置位
来源：http://dali.pycfn.com/Article/details/gtogyunqnt.html

x |= (1 << 3);
来源：http://dali.ybcxt.top/Article/details/gtqhhknzwi.html

[S17] C：安全拼接字符串
来源：http://dali.zdqjudy.top/Article/details/gtmmniutlu.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhoulong.xyz/Article/details/gtxnkauixe.html

[S18] C：命令行参数
来源：http://dali.xuanzx.com/Article/details/gtvmstaghq.html

int main(int argc, char **argv)
来源：http://dali.jinqigufen.top/Article/details/gtoxzmhgrd.html

[S19] C：快速排序
来源：http://dali.zdqjudy.top/Article/details/gtyvdxulor.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.fengsongda.top/Article/details/gtioxbeiku.html

[S20] C：二分查找
来源：http://dali.chenjidiqi.icu/Article/details/gttfyrdiil.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.nanxinkj.top/Article/details/gtrnrsfjrq.html

[S21] C：字符类别判断
来源：http://dali.daxiang520.top/Article/details/gtljutawyd.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.shangyingyoupin.top/Article/details/gtwzwcpqke.html

[S22] C：字符串转数字
来源：http://dali.gzhubu.top/Article/details/gtarbccidy.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.yongpay.top/Article/details/gthctbsrbx.html

[S23] C：随机数
来源：http://dali.redwolf501.top/Article/details/gtsajrqjmx.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.tian-w.cn/Article/details/gtnwkpshtv.html

[S24] C：获取本地时间
来源：http://dali.hysaishi.cn/Article/details/gtqguoxfde.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.meibo888.top/Article/details/gtbqmxtrxk.html

[S25] C：内存拷贝
来源：http://dali.zhongyouzk.top/Article/details/gtrqrwxpye.html

memcpy(dst, src, n);
来源：http://dali.tian-w.cn/Article/details/gtlxzetvpo.html

[S26] C：内存清零
来源：http://dali.fengsongda.top/Article/details/gtpcgkhjjg.html

memset(a, 0, sizeof a);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdbodjeua.html

[S27] C：定义常量
来源：http://dali.wangshuangyany.cn/Article/details/gttptfypmo.html

const double PI = 3.14159;
来源：http://dali.zhoulong.xyz/Article/details/gtrngfivuo.html

[S28] C：静态变量
来源：http://dali.hfpthk.cn/Article/details/gtsoshbkon.html

static int counter = 0;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvdbyagut.html

[S29] C：变参函数
来源：http://dali.cucudq.cn/Article/details/gtetvfnlwe.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.xziqi.cn/Article/details/gtpjvnbplv.html

[S30] C：头文件保护
来源：http://dali.gaohongyu789.top/Article/details/gtoshfmkuu.html

#ifndef X_H
来源：http://dali.cucudq.cn/Article/details/gtrlmnxzkp.html

#define X_H
来源：http://dali.ppjwa.cn/Article/details/gtyqqjqlnr.html

#endif
来源：http://dali.andypj.xyz/Article/details/gtvwobomvs.html

[S31] C++：Hello World
来源：http://dali.aibaodan.cn/Article/details/gtyecytzbc.html

#include <iostream>
来源：http://dali.yonumen.top/Article/details/gtxvqlyxjf.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.smart0.xyz/Article/details/gtjcgczjys.html

[S32] C++：字符串
来源：http://dali.ehwqpu.com/Article/details/gtxzximtjv.html

std::string s = "hi";  s += "!";
来源：http://dali.quarkkingdee.top/Article/details/gtuavtnzru.html

[S33] C++：vector 增删
来源：http://dali.ehwqpu.com/Article/details/gtbectuznl.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.ppjwa.cn/Article/details/gtfkqmqtoy.html

[S34] C++：遍历 vector
来源：http://dali.meibo888.top/Article/details/gtregkqtna.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.ydzc1.top/Article/details/gtvajbkmbl.html

[S35] C++：map
来源：http://dali.jqgfzy.top/Article/details/gtenpcruwn.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.fengsongda.top/Article/details/gthbzurnif.html

[S36] C++：unordered_map
来源：http://dali.shzxlz.cn/Article/details/gtntwyqtsy.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hammf.cn/Article/details/gtuozbsylw.html

[S37] C++：set
来源：http://dali.hnxiangtu.top/Article/details/gtofxnpjbc.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.dashuyun.cn/Article/details/gtzxbefxky.html

[S38] C++：排序
来源：http://dali.sxryk.cn/Article/details/gtlclunyuq.html

std::sort(v.begin(), v.end());
来源：http://dali.zycfv.cn/Article/details/gtdtruhxmb.html

[S39] C++：自定义比较器排序
来源：http://dali.ybcxt.top/Article/details/gtczbhplyn.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.pycfn.com/Article/details/gtwyqpmitz.html

[S40] C++：查找元素
来源：http://dali.jqgfzy.top/Article/details/gtsbzghpwj.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.yj20258888.top/Article/details/gtvutmcpri.html

[S41] C++：类与构造函数
来源：http://dali.haohaochexian.top/Article/details/gtxlncrsaa.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.ivvv.top/Article/details/gtaieyjhrh.html

[S42] C++：继承与虚函数
来源：http://dali.meibo888.top/Article/details/gtdcgcjiju.html

class B : public Base { public: void f() override {} };
来源：http://dali.cashguo.top/Article/details/gttvflkoux.html

[S43] C++：智能指针
来源：http://dali.9152youxi.cn/Article/details/gtyhpaaicr.html

auto p = std::make_unique<int>(5);
来源：http://dali.jinghuilouyu.cn/Article/details/gtvycgskps.html

[S44] C++：引用传参
来源：http://dali.316326.xyz/Article/details/gtebilygul.html

void inc(int &x) { ++x; }
来源：http://dali.xziqi.cn/Article/details/gtzyweysrl.html

[S45] C++：lambda
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxaksmmdz.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.jianghu66.top/Article/details/gtmcigzqdv.html

[S46] C++：函数模板
来源：http://dali.aizwys.cn/Article/details/gtwfefzpkk.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.ybcxt.top/Article/details/gtqevhwajw.html

[S47] C++：结构化绑定遍历
来源：http://dali.zycfv.cn/Article/details/gtqwbdlbkn.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gtjzredgie.html

[S48] C++：逐行读文件
来源：http://dali.kuanghao11.cn/Article/details/gtchuhjhtf.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.cqqwz.cn/Article/details/gtuddvlaxb.html

while (std::getline(in, line)) { }
来源：http://dali.ehwqpu.com/Article/details/gtbzxgbapz.html

[S49] C++：写文件
来源：http://dali.316326.xyz/Article/details/gtxoxbavyt.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhixingplan.top/Article/details/gtajspkhtc.html

[S50] C++：格式化数字
来源：http://dali.cucudq.cn/Article/details/gtfntbjprs.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.tianlin.xyz/Article/details/gtfxmzsgmi.html

[S51] C++：显式类型转换
来源：http://dali.hammf.cn/Article/details/gtfmvwhpzy.html

static_cast<double>(a) / b
来源：http://dali.xuetiantiany.cn/Article/details/gtygaftfmq.html

[S52] C++：const 与 noexcept
来源：http://dali.dianchejie.cn/Article/details/gtawabduvn.html

int size() const noexcept { return n_; }
来源：http://dali.wangdashe.top/Article/details/gtvfypiojl.html

[S53] C++：移动语义
来源：http://dali.daria6918.cn/Article/details/gtopnstunz.html

std::vector<int> w = std::move(v);
来源：http://dali.chenzaomai.com/Article/details/gtreaxhjbh.html

[S54] C++：异常处理
来源：http://dali.cdnleiting.top/Article/details/gtejdngqbq.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.jlsjyb.cn/Article/details/gttwvzgyzj.html

[S55] C++：结构化绑定
来源：http://dali.hywenlv.cn/Article/details/gtnjbspzki.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.ppjwa.cn/Article/details/gtpunmaphl.html

[S56] C++：optional
来源：http://dali.shangyingyoupin.top/Article/details/gtlqsptsgj.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.xuetiantiany.cn/Article/details/gtacewtman.html

[S57] C++：编译期常量
来源：http://dali.hfpthk.cn/Article/details/gtkibwngys.html

constexpr int N = 10;
来源：http://dali.wangshuangyany.cn/Article/details/gtnodcqofa.html

[S58] C++：命名空间
来源：http://dali.jianghu66.top/Article/details/gtfpksmtwk.html

namespace ns { int f() { return 1; } }
来源：http://dali.meibo888.top/Article/details/gtdhvnllgk.html

[S59] C++：静态断言
来源：http://dali.feifeiyinyue.top/Article/details/gtzkjzzfor.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.quarkkingdee.top/Article/details/gtcuboxhdd.html

[S60] C++：遍历并删除元素
来源：http://dali.chenzaomai.com/Article/details/gtaawbmsfl.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.jiagoushi.top/Article/details/gtbiptecjr.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtfmajiczn.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.jiagoushi.top/Article/details/gtnrkygusk.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtlbtlcnsh.html

[T01] Kotlin：Hello World
来源：http://dali.chenlongwang.top/Article/details/gteewddqkl.html

println("Hello")
来源：http://dali.0kj1m.cn/Article/details/gtarpavzch.html

[T02] Kotlin：变量
来源：http://dali.hywenlv.cn/Article/details/gtxjryioql.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.sufxvd.cn/Article/details/gtsmgpxfbr.html

[T03] Kotlin：字符串模板
来源：http://dali.yj20258888.top/Article/details/gtwiwcmhrc.html

"值: $b"
来源：http://dali.jinghuilouyu.cn/Article/details/gtohnlupcd.html

[T04] Kotlin：空安全
来源：http://dali.jianghu66.top/Article/details/gttacnvkrs.html

val n: String? = null;  n?.length
来源：http://dali.haohaochexian.top/Article/details/gtkosmmmnk.html

[T05] Kotlin：when 表达式
来源：http://dali.jianghu66.top/Article/details/gtbkndjcdw.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.iojbl.cn/Article/details/gtspednakw.html

[T06] Kotlin：集合映射
来源：http://dali.yuanzhike.top/Article/details/gtdftleqgq.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.xuetiantiany.cn/Article/details/gtpqlzewkd.html

[T07] Kotlin：集合过滤
来源：http://dali.xylfe.cn/Article/details/gtwerfblkc.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.daria6918.cn/Article/details/gtygsfbyjd.html

[T08] Kotlin：数据类
来源：http://dali.xuetiantiany.cn/Article/details/gtnqshnlgq.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gthcmenoys.html

[T09] Kotlin：扩展函数
来源：http://dali.hywenlv.cn/Article/details/gtlhrogvze.html

fun String.exclaim() = this + "!"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaehaymja.html

[T10] Kotlin：默认参数
来源：http://dali.xziqi.cn/Article/details/gtrjhedifi.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.xuanzx.com/Article/details/gtcyooxtgu.html

[T11] Kotlin：协程
来源：http://dali.guowangkeji.top/Article/details/gtyyfwztkj.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.fengsongda.top/Article/details/gtmsvaxqkf.html

[T12] Kotlin：解构声明
来源：http://dali.jqgfzy.top/Article/details/gtxisaswlb.html

val (a, b) = Pair(1, 2)
来源：http://dali.wangdashe.top/Article/details/gtomjvcozx.html

[T13] Kotlin：只读 Map
来源：http://dali.birdmap.top/Article/details/gtqzshmryp.html

val m = mapOf("a" to 1)
来源：http://dali.zhoulong.xyz/Article/details/gtdafrowdw.html

[T14] Kotlin：循环
来源：http://dali.dashuyun.cn/Article/details/gtqlymsbof.html

for (i in 1..10) println(i)
来源：http://dali.jinqigfzy.top/Article/details/gtoicladaz.html

[T15] Kotlin：接口
来源：http://dali.shanyushiyangkeji.top/Article/details/gthchhxmcq.html

interface Shape { fun area(): Double }
来源：http://dali.shzxlz.cn/Article/details/gtztrainav.html

[T16] Swift：Hello World
来源：http://dali.chenzaomai.com/Article/details/gtiowtfxrm.html

print("Hello")
来源：http://dali.daria6918.cn/Article/details/gtbgnhxoil.html

[T17] Swift：变量与常量
来源：http://dali.quarkkingdee.top/Article/details/gtxexggcnk.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gtgvcueozm.html

[T18] Swift：字符串插值
来源：http://dali.jinqigfzy.top/Article/details/gtxcormmrr.html

"值: \(b)"
来源：http://dali.jinghuilouyu.cn/Article/details/gtclbzoifi.html

[T19] Swift：可选绑定
来源：http://dali.chenjidiqi.icu/Article/details/gtlebqzhxp.html

if let n = opt { print(n) }
来源：http://dali.kuanghao11.cn/Article/details/gtmngwvbeq.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gtbescnqwy.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.svipenyu.cn/Article/details/gtkbtbukxi.html

[T21] Swift：遍历
来源：http://dali.zhengqikj.top/Article/details/gthbktljwn.html

for x in a { print(x) }
来源：http://dali.feifeiyinyue.top/Article/details/gthtbppyfn.html

[T22] Swift：字典
来源：http://dali.wangdashe.top/Article/details/gtbslqfuso.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.yanxiufei.cn/Article/details/gtdpjwsilk.html

[T23] Swift：函数
来源：http://dali.cheryme.top/Article/details/gtmmuwvctj.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.cashguo.top/Article/details/gtaxblubri.html

[T24] Swift：闭包
来源：http://dali.hfpthk.cn/Article/details/gtmrftumbx.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.tanke756.top/Article/details/gtovicjukm.html

[T25] Swift：结构体
来源：http://dali.9152youxi.cn/Article/details/gtdogfheqh.html

struct P { var x: Int }
来源：http://dali.gotoacloud.top/Article/details/gtvxmlkelh.html

[T26] Swift：类与重写
来源：http://dali.hnqzz.top/Article/details/gthtigeqbo.html

class A: Base { override func f() {} }
来源：http://dali.jiagoushi.top/Article/details/gtovxatgoo.html

[T27] Swift：错误处理
来源：http://dali.chenlongwang.top/Article/details/gtcvnhjrmj.html

do { try f() } catch { print(error) }
来源：http://dali.sysykeji.top/Article/details/gtrtnseudy.html

[T28] Swift：枚举
来源：http://dali.xinyue.icu/Article/details/gtfuyjiiin.html

enum Color { case red, green }
来源：http://dali.ydzc1.top/Article/details/gtzjcpuniz.html

[T29] Swift：guard 提前返回
来源：http://dali.xziqi.cn/Article/details/gtnmapsbyz.html

guard let x = opt else { return }
来源：http://dali.jinqigufen.top/Article/details/gtutzhtvhh.html

[T30] Swift：协议
来源：http://dali.xziqi.cn/Article/details/gticiivqee.html

protocol Shape { func area() -> Double }
来源：http://dali.yj202588.top/Article/details/gtyxctjkaq.html

[T31] Lua：Hello World
来源：http://dali.yj202588.top/Article/details/gtjpiphmle.html

print("Hello")
来源：http://dali.jiagoushi.top/Article/details/gtzjbdiwcj.html

[T32] Lua：局部变量
来源：http://dali.yanxiufei.cn/Article/details/gtfizgkttf.html

local a = 1
来源：http://dali.nanxuanxn.top/Article/details/gtmqhmtxqt.html

[T33] Lua：表（数组）
来源：http://dali.daria6918.cn/Article/details/gtibgykoau.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.yj20258888.top/Article/details/gtcizgqric.html

[T34] Lua：遍历表
来源：http://dali.jlsjyb.cn/Article/details/gtwsaztsil.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.hnxiangtu.top/Article/details/gtutarxddo.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gtjkrjbypk.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhongyouzk.top/Article/details/gtwnorcutt.html

[T36] Lua：函数
来源：http://dali.havefunace.top/Article/details/gtnvgsjpfy.html

function add(a, b) return a + b end
来源：http://dali.jqgfzy.top/Article/details/gtsgqtgdwf.html

[T37] Lua：字符串拼接
来源：http://dali.shanyushiyangtech.top/Article/details/gtvcseerta.html

"a" .. "b"
来源：http://dali.9152youxi.cn/Article/details/gtwhcngveg.html

[T38] Lua：条件
来源：http://dali.ehwqpu.com/Article/details/gtwyxiyyuv.html

if x > 0 then print("正") end
来源：http://dali.smart0.xyz/Article/details/gtmmizxqjc.html

[T39] Lua：模式匹配
来源：http://dali.meibo888.top/Article/details/gtkkdxkoka.html

string.find(s, "%d+")
来源：http://dali.dashuyun.cn/Article/details/gtfcqrtlvq.html

[T40] Lua：元表
来源：http://dali.xziqi.cn/Article/details/gtrapwjeas.html

setmetatable({}, { __index = base })
来源：http://dali.xuanzx.com/Article/details/gtnxmahjfe.html

[T41] Perl：Hello World
来源：http://dali.svipenyu.cn/Article/details/gtmpkkxmpg.html

print "Hello\n";
来源：http://dali.sufxvd.cn/Article/details/gtyooeaxys.html

[T42] Perl：变量类型
来源：http://dali.hywenlv.cn/Article/details/gtremxmvhk.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.yonumen.top/Article/details/gtztwuopmc.html

[T43] Perl：字符串插值
来源：http://dali.svipenyu.cn/Article/details/gttjlqjcvx.html

"值: $a"
来源：http://dali.yj20258.top/Article/details/gtxdfqehfo.html

[T44] Perl：条件
来源：http://dali.xziqi.cn/Article/details/gtrauwvqjl.html

if ($a > 0) { print "正"; }
来源：http://dali.cheryme.top/Article/details/gtawoocwev.html

[T45] Perl：数组遍历
来源：http://dali.guowangkeji.top/Article/details/gtrsgxfxux.html

for my $x (@arr) { print $x; }
来源：http://dali.mhx1999.top/Article/details/gtnqkjzyqj.html

[T46] Perl：哈希操作
来源：http://dali.daria6918.cn/Article/details/gtefyxpdra.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.aizwys.cn/Article/details/gtdtrwryrb.html

[T47] Perl：正则捕获
来源：http://dali.xylfe.cn/Article/details/gtwayaxyen.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.jlsjyb.cn/Article/details/gtpdnbflsc.html

[T48] Perl：正则替换
来源：http://dali.aizwys.cn/Article/details/gtbvcsryex.html

$s =~ s/old/new/g;
来源：http://dali.yangfankeji.com/Article/details/gtwuantxmq.html

[T49] Perl：函数
来源：http://dali.ehwqpu.com/Article/details/gtuovqcjah.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.yj20258888.top/Article/details/gtouagudey.html

[T50] Perl：逐行读文件
来源：http://dali.haohaochexian.top/Article/details/gtqofemjqx.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.sufxvd.cn/Article/details/gtktgfbsjt.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.hfpthk.cn/Article/details/gtftrikltd.html

[T51] Scala：Hello World
来源：http://dali.hammf.cn/Article/details/gthtaoyfcr.html

println("Hello")
来源：http://dali.zycfv.cn/Article/details/gtgjcgdyks.html

[T52] Scala：变量
来源：http://dali.tianlin.xyz/Article/details/gtdtvpgshv.html

val a = 1;  var b = 2
来源：http://dali.shangyingyoupin.top/Article/details/gtdjikbgrh.html

[T53] Scala：字符串插值
来源：http://dali.ppjwa.cn/Article/details/gtapbotxaw.html

s"值: $b"
来源：http://dali.redwolf501.top/Article/details/gttcrbqdtl.html

[T54] Scala：集合映射
来源：http://dali.svipenyu.cn/Article/details/gtppgdfaba.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.jiagoushi.top/Article/details/gtgqfldatz.html

[T55] Scala：集合过滤
来源：http://dali.ehwqpu.com/Article/details/gtiwnuanau.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.9152youxi.cn/Article/details/gtljynswsj.html

[T56] Scala：样例类
来源：http://dali.andypj.xyz/Article/details/gtadduyxvb.html

case class User(name: String, age: Int)
来源：http://dali.hammf.cn/Article/details/gtoxwrjoac.html

[T57] Scala：模式匹配
来源：http://dali.wangdashe.top/Article/details/gtfcryojqk.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.hnxiangtu.top/Article/details/gtejubipoj.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gtsgbglrxd.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.aizwys.cn/Article/details/gtkuvmwseq.html

[T59] Scala：循环
来源：http://dali.cucudq.cn/Article/details/gteeoyqzbq.html

for (i <- 1 to 10) println(i)
来源：http://dali.jqgfzy.top/Article/details/gtsfvvcgsv.html

[T60] Scala：折叠
来源：http://dali.c1oappe.top/Article/details/gtlciahwsj.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.snrcjt.cn/Article/details/gtyibaunog.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtzrodyqsz.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.hysaishi.cn/Article/details/gtkncvwhck.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtpphoigrn.html

[U01] Py：创建虚拟环境
来源：http://dali.cheryme.top/Article/details/gtschlpfmw.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.wangdashe.top/Article/details/gtxouiaocr.html

[U02] Py：导出 / 安装依赖
来源：http://dali.iojbl.cn/Article/details/gthnfrnukt.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.shangyingyoupin.top/Article/details/gtifnxlkey.html

[U03] Py：加载 .env 配置
来源：http://dali.havefunace.top/Article/details/gtrxyrgcfh.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.yj202588.top/Article/details/gtbnxoervx.html

[U04] Py：变量调试打印
来源：http://dali.tanke756.top/Article/details/gtzsqfbrtc.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.yj202588.top/Article/details/gtmlfjaxwc.html

[U05] Py：列表去重且保序
来源：http://dali.sufxvd.cn/Article/details/gtlctgojgt.html

list(dict.fromkeys(arr))
来源：http://dali.guowangkeji.top/Article/details/gttugjsiuu.html

[U06] Py：合并两个字典
来源：http://dali.nwbrower.top/Article/details/gttpoizygh.html

{**a, **b}
来源：http://dali.tianlin.xyz/Article/details/gtlyufbrdg.html


<!-- 参考信息 -->