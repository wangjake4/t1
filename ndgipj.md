代发 wailian999

openssl rand -hex 16
来源：http://dali.pengpengdd.cyou/Article/details/gtuqichqzx.html

[R68] 计算文件校验值
来源：http://dali.jinqigufen.top/Article/details/gtyobdkklp.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.guannengcc.top/Article/details/gtfimuxled.html

[R69] 生成随机密码
来源：http://dali.iojbl.cn/Article/details/gtfsynoujz.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhongyouzk.top/Article/details/gtrmtfqsre.html

[R70] 时间戳与互转
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthtzgyuuk.html

date +%s;  date -d @1700000000
来源：http://dali.tanke756.top/Article/details/gtaquxwmbu.html

[R71] 日期格式化
来源：http://dali.tianlin.xyz/Article/details/gtfnjuwxvd.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.aizwys.cn/Article/details/gttxnkmxnd.html

[R72] 等待端口就绪
来源：http://dali.nwbrower.top/Article/details/gtnyuilutn.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.shuidangran.top/Article/details/gtdgrljkyb.html

[R73] 分割大日志
来源：http://dali.zhixingplan.top/Article/details/gtvbxtiuky.html

split -l 1000 big.log part_
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdhyusosu.html

[R74] 批量重命名
来源：http://dali.quarkkingdee.top/Article/details/gtxisavcjj.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.jiagoushi.top/Article/details/gtfwpsiuey.html

[R75] 导出环境变量
来源：http://dali.zhongyouzk.top/Article/details/gtneweeuej.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.316326.xyz/Article/details/gtsuvheouf.html

[R76] 使用临时文件
来源：http://dali.chenzaomai.com/Article/details/gtszynthei.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.havefunace.top/Article/details/gtcckklzkh.html

[R77] 读取用户输入
来源：http://dali.jianghu66.top/Article/details/gtgegnxlto.html

read -rp "请输入: " ans
来源：http://dali.gzhubu.top/Article/details/gthehqzfqo.html

[R78] 交互式菜单
来源：http://dali.jinghuilouyu.cn/Article/details/gtxirxktgr.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.pycfn.com/Article/details/gtqqyxbzki.html

[R79] 解析命令行选项
来源：http://dali.daria6918.cn/Article/details/gtosynfqjv.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.nanxinkj.top/Article/details/gtotdflzvq.html

[R80] 查看脚本执行耗时
来源：http://dali.cqqwz.cn/Article/details/gtwbiymzoy.html

time ./run.sh
来源：http://dali.ehwqpu.com/Article/details/gtyqdbiurc.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtjhxsyatj.html

S. C / C++ 专题
来源：http://dali.shanyushiyangkeji.top/Article/details/gtawnujmxf.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtuoyfqfcg.html

[S01] C：Hello World
来源：http://dali.gzhubu.top/Article/details/gtldijhfeo.html

#include <stdio.h>
来源：http://dali.ydzc1.top/Article/details/gtwlsoxlcj.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.yanxiufei.cn/Article/details/gthtbohlzh.html

[S02] C：变量与格式化输出
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlqtpbhbx.html

int a = 10; printf("%d\n", a);
来源：http://dali.zycfv.cn/Article/details/gtbspdsvfr.html

[S03] C：读入整数
来源：http://dali.hfpthk.cn/Article/details/gtydwbpmlw.html

int x; scanf("%d", &x);
来源：http://dali.iojbl.cn/Article/details/gttbrsmaqt.html

[S04] C：字符串复制
来源：http://dali.aibaodan.cn/Article/details/gtqstpdqqy.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.andypj.xyz/Article/details/gtvmrtbltx.html

[S05] C：字符串长度
来源：http://dali.mhx1999.top/Article/details/gtwwnyhfpp.html

strlen(s)
来源：http://dali.gaohongyu789.top/Article/details/gtszmhyfku.html

[S06] C：字符串比较
来源：http://dali.yj202588.top/Article/details/gtmgdrkpiw.html

strcmp(a, b) == 0
来源：http://dali.chenlongwang.top/Article/details/gtwkrtommx.html

[S07] C：数组遍历求和
来源：http://dali.zhengqikj.top/Article/details/gtrbtfzbfu.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.kuanghao11.cn/Article/details/gtdlmkqiis.html

[S08] C：动态内存分配与释放
来源：http://dali.zhongyouzk.top/Article/details/gtzgcgqqow.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.ydzc1.top/Article/details/gthldosnuo.html

[S09] C：结构体定义与初始化
来源：http://dali.cashguo.top/Article/details/gtlpdklvvd.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhixingplan.top/Article/details/gtcjzdqkys.html

[S10] C：指针与解引用
来源：http://dali.sweek.top/Article/details/gtnxxoxhoz.html

int *p = &a;  *p = 5;
来源：http://dali.pycfn.com/Article/details/gtfsaluugz.html

[S11] C：逐行读文件
来源：http://dali.haohaochexian.top/Article/details/gtbnqsadnn.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.shuidangran.top/Article/details/gtwjgzyvun.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.daxiang520.top/Article/details/gtdzdphgdy.html

fclose(f);
来源：http://dali.316326.xyz/Article/details/gthxuzgtgx.html

[S12] C：写文件
来源：http://dali.gzhubu.top/Article/details/gtfrhhpjzu.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.gaohongyu789.top/Article/details/gtysurhchr.html

[S13] C：宏定义
来源：http://dali.zhoulong.xyz/Article/details/gtcorlsnha.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.xuetiantiany.cn/Article/details/gtpfeyassq.html

[S14] C：枚举
来源：http://dali.zhixingplan.top/Article/details/gtbfaxxyrn.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhaomingkeji.xyz/Article/details/gteoqzftrw.html

[S15] C：类型转换
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvobsqmoz.html

(double) a / b
来源：http://dali.jiagoushi.top/Article/details/gtuqiitkcb.html

[S16] C：位操作置位
来源：http://dali.xziqi.cn/Article/details/gtxvxjkizp.html

x |= (1 << 3);
来源：http://dali.yangfankeji.com/Article/details/gtewkpzyqp.html

[S17] C：安全拼接字符串
来源：http://dali.yanxiufei.cn/Article/details/gtecplzwjr.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.ydzc1.top/Article/details/gtuwrpscse.html

[S18] C：命令行参数
来源：http://dali.cucudq.cn/Article/details/gtujyiqfrz.html

int main(int argc, char **argv)
来源：http://dali.hnqzz.top/Article/details/gtufcaclsx.html

[S19] C：快速排序
来源：http://dali.zhengqikj.top/Article/details/gtpschfwbb.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.tianlin.xyz/Article/details/gttifefceq.html

[S20] C：二分查找
来源：http://dali.shanyushiyangtech.top/Article/details/gtfsfsmsfs.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.haohaochexian.top/Article/details/gtdlhwljih.html

[S21] C：字符类别判断
来源：http://dali.c1oappe.top/Article/details/gtatpngrom.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.kuanghao11.cn/Article/details/gtwltzqjrj.html

[S22] C：字符串转数字
来源：http://dali.yangfankeji.com/Article/details/gtpoquqclj.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.jyoumei.cn/Article/details/gtkfdgltga.html

[S23] C：随机数
来源：http://dali.jianghu66.top/Article/details/gtomwcktst.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.yj20258.top/Article/details/gtwilhsxur.html

[S24] C：获取本地时间
来源：http://dali.jinqigfzy.top/Article/details/gtrjhadopp.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.nanxuanxn.top/Article/details/gtlmzhuqkd.html

[S25] C：内存拷贝
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxhzapmxv.html

memcpy(dst, src, n);
来源：http://dali.xinyue.icu/Article/details/gtfxcpxhrp.html

[S26] C：内存清零
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtituvzyyq.html

memset(a, 0, sizeof a);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrolbscih.html

[S27] C：定义常量
来源：http://dali.feifeiyinyue.top/Article/details/gtyasybwdy.html

const double PI = 3.14159;
来源：http://dali.redwolf501.top/Article/details/gtcxhbvhpi.html

[S28] C：静态变量
来源：http://dali.andypj.xyz/Article/details/gtayymkfhd.html

static int counter = 0;
来源：http://dali.cqqwz.cn/Article/details/gtbckcisge.html

[S29] C：变参函数
来源：http://dali.fzhhl.top/Article/details/gtdnxehwui.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.jqgfzy.top/Article/details/gtihleovma.html

[S30] C：头文件保护
来源：http://dali.yuanzhike.top/Article/details/gtzdokswdh.html

#ifndef X_H
来源：http://dali.zhengqikj.top/Article/details/gtvixuxpjg.html

#define X_H
来源：http://dali.kuanghao11.cn/Article/details/gtlxbprlvr.html

#endif
来源：http://dali.jqgufenzy.top/Article/details/gtknufclsm.html

[S31] C++：Hello World
来源：http://dali.yongpay.top/Article/details/gtbinpamsv.html

#include <iostream>
来源：http://dali.shzxlz.cn/Article/details/gtaxdaajvt.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.kuanghao11.cn/Article/details/gtetcbcffh.html

[S32] C++：字符串
来源：http://dali.daxiang520.top/Article/details/gthinbhdev.html

std::string s = "hi";  s += "!";
来源：http://dali.0kj1m.cn/Article/details/gtwnekdqes.html

[S33] C++：vector 增删
来源：http://dali.wangshuangyany.cn/Article/details/gtubdbbrxp.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.hysaishi.cn/Article/details/gttggxvlif.html

[S34] C++：遍历 vector
来源：http://dali.cdnleiting.top/Article/details/gtefboquhm.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgieobrgj.html

[S35] C++：map
来源：http://dali.kuanghao11.cn/Article/details/gtaaycdoem.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhengqikj.top/Article/details/gtgrpbmwdj.html

[S36] C++：unordered_map
来源：http://dali.ywan-chungtsiang.top/Article/details/gthesojiwe.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jinqigfzy.top/Article/details/gtvbuirhxa.html

[S37] C++：set
来源：http://dali.9152youxi.cn/Article/details/gtzjelezwe.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.aibaodan.cn/Article/details/gtmutjfbja.html

[S38] C++：排序
来源：http://dali.ybcxt.top/Article/details/gtocayuvue.html

std::sort(v.begin(), v.end());
来源：http://dali.daxiang520.top/Article/details/gtdazjkryh.html

[S39] C++：自定义比较器排序
来源：http://dali.guannengcc.top/Article/details/gtrtcsnkzr.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.quarkkingdee.top/Article/details/gtfwvaxhrk.html

[S40] C++：查找元素
来源：http://dali.wangdashe.top/Article/details/gtrixpdiow.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhixingplan.top/Article/details/gtyxevvuvn.html

[S41] C++：类与构造函数
来源：http://dali.xuanzx.com/Article/details/gtbyinqafy.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.daxiang520.top/Article/details/gtetfzboin.html

[S42] C++：继承与虚函数
来源：http://dali.mhx1999.top/Article/details/gtmlreunvy.html

class B : public Base { public: void f() override {} };
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfcrchisf.html

[S43] C++：智能指针
来源：http://dali.jqgfzy.top/Article/details/gtekjoyigj.html

auto p = std::make_unique<int>(5);
来源：http://dali.tian-w.cn/Article/details/gtagqnxigr.html

[S44] C++：引用传参
来源：http://dali.cucudq.cn/Article/details/gtplulksrd.html

void inc(int &x) { ++x; }
来源：http://dali.ppjwa.cn/Article/details/gtsxmcvdrr.html

[S45] C++：lambda
来源：http://dali.hnqzz.top/Article/details/gthloxhyhe.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.yongpay.top/Article/details/gtnphbdxde.html

[S46] C++：函数模板
来源：http://dali.daxiang520.top/Article/details/gtkhlsujnb.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhengqikj.top/Article/details/gtjxupqtaz.html

[S47] C++：结构化绑定遍历
来源：http://dali.wangshuangyany.cn/Article/details/gtzbfjiwua.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.meibo888.top/Article/details/gtqifviywp.html

[S48] C++：逐行读文件
来源：http://dali.zhengqikj.top/Article/details/gtpuiwdugu.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.andypj.xyz/Article/details/gtptijpafy.html

while (std::getline(in, line)) { }
来源：http://dali.iojbl.cn/Article/details/gtfpmptlfa.html

[S49] C++：写文件
来源：http://dali.cqqwz.cn/Article/details/gtesoopjhr.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.yuanzhike.top/Article/details/gtixdedtiy.html

[S50] C++：格式化数字
来源：http://dali.wangdashe.top/Article/details/gtbusuvfmp.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.haohaochexian.top/Article/details/gttkpxshdt.html

[S51] C++：显式类型转换
来源：http://dali.ppjwa.cn/Article/details/gtgojqmrqc.html

static_cast<double>(a) / b
来源：http://dali.hywenlv.cn/Article/details/gtkjedayjc.html

[S52] C++：const 与 noexcept
来源：http://dali.aibaodan.cn/Article/details/gtfrhefimm.html

int size() const noexcept { return n_; }
来源：http://dali.andypj.xyz/Article/details/gtjnqmsoxm.html

[S53] C++：移动语义
来源：http://dali.jinyuanbaomall.cn/Article/details/gtioakgzpc.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gtdrursxsc.html

[S54] C++：异常处理
来源：http://dali.kuanghao11.cn/Article/details/gthexpycyd.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.hammf.cn/Article/details/gtutkqupee.html

[S55] C++：结构化绑定
来源：http://dali.vqdsnc.cn/Article/details/gtteudbeoc.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkrdcxvrz.html

[S56] C++：optional
来源：http://dali.nwbrower.top/Article/details/gtosdefxcz.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.guowangkeji.top/Article/details/gttglwqgwf.html

[S57] C++：编译期常量
来源：http://dali.gaohongyu789.top/Article/details/gtgtonobtu.html

constexpr int N = 10;
来源：http://dali.hysaishi.cn/Article/details/gtwgofatqv.html

[S58] C++：命名空间
来源：http://dali.sweek.top/Article/details/gtvntptfeg.html

namespace ns { int f() { return 1; } }
来源：http://dali.cashguo.top/Article/details/gttdbdgyyv.html

[S59] C++：静态断言
来源：http://dali.fzhhl.top/Article/details/gteuevzspa.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.yj20258.top/Article/details/gthmrnigha.html

[S60] C++：遍历并删除元素
来源：http://dali.hnxiangtu.top/Article/details/gtdiqlpdzz.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.yj20258888.top/Article/details/gtjctuerte.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtpsczbvfw.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.316326.xyz/Article/details/gtmfgrnfpc.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtypagwaeb.html

[T01] Kotlin：Hello World
来源：http://dali.ivvv.top/Article/details/gtvkfmpoxe.html

println("Hello")
来源：http://dali.yvedp.cn/Article/details/gtkftwqvgu.html

[T02] Kotlin：变量
来源：http://dali.gotoacloud.top/Article/details/gtyczsecbr.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.sweek.top/Article/details/gtjaqhbdna.html

[T03] Kotlin：字符串模板
来源：http://dali.chenzaomai.com/Article/details/gthavipjrz.html

"值: $b"
来源：http://dali.chenjidiqi.icu/Article/details/gturgsudqr.html

[T04] Kotlin：空安全
来源：http://dali.jinqigfzy.top/Article/details/gtezxivctq.html

val n: String? = null;  n?.length
来源：http://dali.birdmap.top/Article/details/gtsikgqlee.html

[T05] Kotlin：when 表达式
来源：http://dali.mhx1999.top/Article/details/gtmejrsxgz.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gtzwkxikcb.html

[T06] Kotlin：集合映射
来源：http://dali.shzxlz.cn/Article/details/gtawjdbjuu.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhiwuduotai.top/Article/details/gtpligrtgm.html

[T07] Kotlin：集合过滤
来源：http://dali.ybcxt.top/Article/details/gtczhgyhsp.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.vqdsnc.cn/Article/details/gtirtjwypt.html

[T08] Kotlin：数据类
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxniovjdp.html

data class User(val name: String, val age: Int)
来源：http://dali.9152youxi.cn/Article/details/gtuoktseia.html

[T09] Kotlin：扩展函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcfhpovnq.html

fun String.exclaim() = this + "!"
来源：http://dali.tanke756.top/Article/details/gthzibwere.html

[T10] Kotlin：默认参数
来源：http://dali.yueranfly.top/Article/details/gthreeqqzh.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.jinqigfzy.top/Article/details/gtuphalfdr.html

[T11] Kotlin：协程
来源：http://dali.jlsjyb.cn/Article/details/gtmczhjzoa.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhiwuduotai.top/Article/details/gtfgcxioxg.html

[T12] Kotlin：解构声明
来源：http://dali.ppjwa.cn/Article/details/gtxsdxbjjy.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhixingplan.top/Article/details/gtnzawnjvn.html

[T13] Kotlin：只读 Map
来源：http://dali.quarkkingdee.top/Article/details/gtybouzywu.html

val m = mapOf("a" to 1)
来源：http://dali.sweek.top/Article/details/gtnktaozyt.html

[T14] Kotlin：循环
来源：http://dali.ydzc1.top/Article/details/gtipodiwbo.html

for (i in 1..10) println(i)
来源：http://dali.xinyue.icu/Article/details/gtlroynzqj.html

[T15] Kotlin：接口
来源：http://dali.yanxiufei.cn/Article/details/gtdfeenmbd.html

interface Shape { fun area(): Double }
来源：http://dali.wangshuangyany.cn/Article/details/gtyxilfxye.html

[T16] Swift：Hello World
来源：http://dali.daxiang520.top/Article/details/gtfhkrxkiv.html

print("Hello")
来源：http://dali.hnxiangtu.top/Article/details/gttqjtsuli.html

[T17] Swift：变量与常量
来源：http://dali.gogol.net.cn/Article/details/gttbztowjp.html

var a = 1;  let b = 2
来源：http://dali.xziqi.cn/Article/details/gtmztmhesl.html

[T18] Swift：字符串插值
来源：http://dali.nanxuanxn.top/Article/details/gtccitbwol.html

"值: \(b)"
来源：http://dali.gaohongyu789.top/Article/details/gtlnuiluve.html

[T19] Swift：可选绑定
来源：http://dali.sysykeji.top/Article/details/gtxifagxby.html

if let n = opt { print(n) }
来源：http://dali.hongshengwenyu.top/Article/details/gteecojpmv.html

[T20] Swift：数组操作
来源：http://dali.quarkkingdee.top/Article/details/gtsqkepybz.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.shzxlz.cn/Article/details/gtufuqkrpw.html

[T21] Swift：遍历
来源：http://dali.tian-w.cn/Article/details/gtcqrxfhvq.html

for x in a { print(x) }
来源：http://dali.vqdsnc.cn/Article/details/gtczfxdkpr.html

[T22] Swift：字典
来源：http://dali.zhengqikj.top/Article/details/gtzznsawnx.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.cucudq.cn/Article/details/gtibvxgoql.html

[T23] Swift：函数
来源：http://dali.xuanzx.com/Article/details/gthfbmnleb.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.yueranfly.top/Article/details/gtzdpamaee.html

[T24] Swift：闭包
来源：http://dali.hnqzz.top/Article/details/gtnwjfjpbk.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.yongpay.top/Article/details/gtyjqqklpc.html

[T25] Swift：结构体
来源：http://dali.hongshengwenyu.top/Article/details/gtneytlxrk.html

struct P { var x: Int }
来源：http://dali.gaohongyu789.top/Article/details/gtlnwackmq.html

[T26] Swift：类与重写
来源：http://dali.shzxlz.cn/Article/details/gtmbnlsvxx.html

class A: Base { override func f() {} }
来源：http://dali.gzhubu.top/Article/details/gtzsrmfyea.html

[T27] Swift：错误处理
来源：http://dali.hfpthk.cn/Article/details/gttfxitvdt.html

do { try f() } catch { print(error) }
来源：http://dali.pengpengdd.cyou/Article/details/gtbepwbqqn.html

[T28] Swift：枚举
来源：http://dali.yj20258.top/Article/details/gtgrwocayp.html

enum Color { case red, green }
来源：http://dali.wangshuangyany.cn/Article/details/gtdhnrrqhp.html

[T29] Swift：guard 提前返回
来源：http://dali.svipenyu.cn/Article/details/gttxwbbzfv.html

guard let x = opt else { return }
来源：http://dali.jqgfzy.top/Article/details/gtqqevqhzx.html

[T30] Swift：协议
来源：http://dali.feifeiyinyue.top/Article/details/gtdudleykh.html

protocol Shape { func area() -> Double }
来源：http://dali.guowangkeji.top/Article/details/gtbdodbtaa.html

[T31] Lua：Hello World
来源：http://dali.birdmap.top/Article/details/gtfvriujww.html

print("Hello")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtajnxlemi.html

[T32] Lua：局部变量
来源：http://dali.hnqzz.top/Article/details/gtrvdtryej.html

local a = 1
来源：http://dali.bjfxy.top/Article/details/gtrdtwgzmt.html

[T33] Lua：表（数组）
来源：http://dali.hnqzz.top/Article/details/gtwdrqpjaq.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.yj20258888.top/Article/details/gtwocbzecf.html

[T34] Lua：遍历表
来源：http://dali.zdqjudy.top/Article/details/gtlkmhykst.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.xuetiantiany.cn/Article/details/gtsduwpver.html

[T35] Lua：字典表
来源：http://dali.cucudq.cn/Article/details/gtrbwisbvf.html

local d = { a = 1 };  d.b = 2
来源：http://dali.0kj1m.cn/Article/details/gttynhhpio.html

[T36] Lua：函数
来源：http://dali.nwbrower.top/Article/details/gtgmpuzoen.html

function add(a, b) return a + b end
来源：http://dali.ydzc1.top/Article/details/gtzuywdaue.html

[T37] Lua：字符串拼接
来源：http://dali.yj20258888.top/Article/details/gttxofpbmi.html

"a" .. "b"
来源：http://dali.shzxlz.cn/Article/details/gtwaoziugi.html

[T38] Lua：条件
来源：http://dali.hywenlv.cn/Article/details/gtkofedcum.html

if x > 0 then print("正") end
来源：http://dali.fengsongda.top/Article/details/gtkslyaqpp.html

[T39] Lua：模式匹配
来源：http://dali.c1oappe.top/Article/details/gtxerxgxtm.html

string.find(s, "%d+")
来源：http://dali.zhixingplan.top/Article/details/gtacsikuag.html

[T40] Lua：元表
来源：http://dali.gzhubu.top/Article/details/gtcwjhpous.html

setmetatable({}, { __index = base })
来源：http://dali.havefunace.top/Article/details/gtalhcgqpu.html

[T41] Perl：Hello World
来源：http://dali.jianghu66.top/Article/details/gtmvrfstpl.html

print "Hello\n";
来源：http://dali.dashuyun.cn/Article/details/gtnwttdaar.html

[T42] Perl：变量类型
来源：http://dali.sufxvd.cn/Article/details/gtmqiwggsk.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zdqjudy.top/Article/details/gtcqtjpezr.html

[T43] Perl：字符串插值
来源：http://dali.sxryk.cn/Article/details/gtcljlzzhu.html

"值: $a"
来源：http://dali.yj20258888.top/Article/details/gtsfjdueou.html

[T44] Perl：条件
来源：http://dali.smart0.xyz/Article/details/gtsnrhscpd.html

if ($a > 0) { print "正"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtdnmqdssg.html

[T45] Perl：数组遍历
来源：http://dali.zhengqikj.top/Article/details/gtmaaxwqzq.html

for my $x (@arr) { print $x; }
来源：http://dali.0kj1m.cn/Article/details/gtyijsrgrq.html

[T46] Perl：哈希操作
来源：http://dali.yvedp.cn/Article/details/gtriinoifz.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.cdnleiting.top/Article/details/gteebhavwe.html

[T47] Perl：正则捕获
来源：http://dali.ivvv.top/Article/details/gtqglmkanr.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.wangshuangyany.cn/Article/details/gtapcaeckx.html

[T48] Perl：正则替换
来源：http://dali.0kj1m.cn/Article/details/gtuacnuzti.html

$s =~ s/old/new/g;
来源：http://dali.gotoacloud.top/Article/details/gtdhzvzjxm.html

[T49] Perl：函数
来源：http://dali.jiagoushi.top/Article/details/gtwsxlkpdo.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.cashguo.top/Article/details/gtxwsjshlf.html

[T50] Perl：逐行读文件
来源：http://dali.birdmap.top/Article/details/gtipetdikj.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.pycfn.com/Article/details/gtfhcoksrk.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.cucudq.cn/Article/details/gtehlbwbtq.html

[T51] Scala：Hello World
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtazeyyvfv.html

println("Hello")
来源：http://dali.yuxming.cn/Article/details/gtwbtmljxo.html

[T52] Scala：变量
来源：http://dali.kuanghao11.cn/Article/details/gtbryiuukf.html

val a = 1;  var b = 2
来源：http://dali.guowangkeji.top/Article/details/gtjvgpqxve.html

[T53] Scala：字符串插值
来源：http://dali.gogol.net.cn/Article/details/gtnuzwidir.html

s"值: $b"
来源：http://dali.ehwqpu.com/Article/details/gtwsnxxpyp.html

[T54] Scala：集合映射
来源：http://dali.jiagoushi.top/Article/details/gtwruhfilx.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtogbvrkje.html

[T55] Scala：集合过滤
来源：http://dali.havefunace.top/Article/details/gtcugrpgqa.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.cashguo.top/Article/details/gtuaidohpk.html

[T56] Scala：样例类
来源：http://dali.nanxuanxn.top/Article/details/gtnaacvdry.html

case class User(name: String, age: Int)
来源：http://dali.guannengcc.top/Article/details/gtkphcghkh.html

[T57] Scala：模式匹配
来源：http://dali.zycfv.cn/Article/details/gtbzsmkiwc.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.snrcjt.cn/Article/details/gtlxreghtx.html

[T58] Scala：函数定义
来源：http://dali.aibaodan.cn/Article/details/gtwmicgwof.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.gogol.net.cn/Article/details/gtmbcbuioh.html

[T59] Scala：循环
来源：http://dali.yj20258.top/Article/details/gtkcbnsdqc.html

for (i <- 1 to 10) println(i)
来源：http://dali.ydzc1.top/Article/details/gtbyxinwqs.html

[T60] Scala：折叠
来源：http://dali.zhengqikj.top/Article/details/gtwpddrfyi.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.gaohongyu789.top/Article/details/gtnavwzsaw.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtfbjzcdxn.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.jinqigufen.top/Article/details/gtazzidmuy.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtqtrvrvwv.html

[U01] Py：创建虚拟环境
来源：http://dali.zhoulong.xyz/Article/details/gtsmuszcja.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.yj20258888.top/Article/details/gtjkztkofe.html

[U02] Py：导出 / 安装依赖
来源：http://dali.fengsongda.top/Article/details/gtdtoabqho.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.ivvv.top/Article/details/gtaufcfxgq.html

[U03] Py：加载 .env 配置
来源：http://dali.yangfankeji.com/Article/details/gtgvgbpizo.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.iojbl.cn/Article/details/gtujgvquyf.html

[U04] Py：变量调试打印
来源：http://dali.daria6918.cn/Article/details/gtwogrdbbh.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.chenjidiqi.icu/Article/details/gtcvskaohz.html

[U05] Py：列表去重且保序
来源：http://dali.haohaochexian.top/Article/details/gtjwzlnait.html

list(dict.fromkeys(arr))
来源：http://dali.cucudq.cn/Article/details/gtukmwulkt.html

[U06] Py：合并两个字典
来源：http://dali.redwolf501.top/Article/details/gtevfqcdhg.html

{**a, **b}
来源：http://dali.yj202588.top/Article/details/gtqicodfur.html

[U07] Py：反转字典键值
来源：http://dali.nwbrower.top/Article/details/gtiyildzye.html

{v: k for k, v in d.items()}
来源：http://dali.hammf.cn/Article/details/gtspmaagao.html

[U08] Py：展平二维列表
来源：http://dali.daria6918.cn/Article/details/gtmvwsiiuf.html

[y for x in nested for y in x]
来源：http://dali.zycfv.cn/Article/details/gtahmmwukh.html


<!-- 参考信息 -->