代发 wailian999

openssl rand -hex 16
来源：http://dali.xinyue.icu/Article/details/gtlcxdomcc.html

[R68] 计算文件校验值
来源：http://dali.smart0.xyz/Article/details/gtbjuonkhd.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhongyouzk.top/Article/details/gtdblapqro.html

[R69] 生成随机密码
来源：http://dali.ehwqpu.com/Article/details/gtjrqbdhix.html

head -c 16 /dev/urandom | base64
来源：http://dali.feifeiyinyue.top/Article/details/gtvnupzpap.html

[R70] 时间戳与互转
来源：http://dali.jlsjyb.cn/Article/details/gtwlymqssg.html

date +%s;  date -d @1700000000
来源：http://dali.daxiang520.top/Article/details/gtjrgtqpwn.html

[R71] 日期格式化
来源：http://dali.nanxinkj.top/Article/details/gtpxgmetzh.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.guowangkeji.top/Article/details/gtimdvszyy.html

[R72] 等待端口就绪
来源：http://dali.guannengcc.top/Article/details/gtjdoudsfk.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.tanke756.top/Article/details/gtmsctpmvj.html

[R73] 分割大日志
来源：http://dali.aibaodan.cn/Article/details/gtnqeyfoje.html

split -l 1000 big.log part_
来源：http://dali.cucudq.cn/Article/details/gtmdwyfwby.html

[R74] 批量重命名
来源：http://dali.9152youxi.cn/Article/details/gtjrafgysg.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.hfpthk.cn/Article/details/gtgpkelxns.html

[R75] 导出环境变量
来源：http://dali.hnqzz.top/Article/details/gtkltatact.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.yongpay.top/Article/details/gtovtfkwoz.html

[R76] 使用临时文件
来源：http://dali.birdmap.top/Article/details/gtlanjfrfu.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.tanke756.top/Article/details/gtcbffcaoi.html

[R77] 读取用户输入
来源：http://dali.xziqi.cn/Article/details/gtxjtelvqo.html

read -rp "请输入: " ans
来源：http://dali.chenzaomai.com/Article/details/gtkjxdalgx.html

[R78] 交互式菜单
来源：http://dali.gzhubu.top/Article/details/gtjwxexxpf.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.cqqwz.cn/Article/details/gtfcnwvbfg.html

[R79] 解析命令行选项
来源：http://dali.yueranfly.top/Article/details/gtdkeuzvof.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.hnqzz.top/Article/details/gtfaenheqf.html

[R80] 查看脚本执行耗时
来源：http://dali.gogol.net.cn/Article/details/gtcaymgegp.html

time ./run.sh
来源：http://dali.daria6918.cn/Article/details/gtafvpgbtm.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtyjdyfknb.html

S. C / C++ 专题
来源：http://dali.316326.xyz/Article/details/gtjxsbdnjm.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtxuzaflgb.html

[S01] C：Hello World
来源：http://dali.sxryk.cn/Article/details/gtjwildqln.html

#include <stdio.h>
来源：http://dali.xuanzx.com/Article/details/gtnyepbmey.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.ppjwa.cn/Article/details/gtvaabnxwq.html

[S02] C：变量与格式化输出
来源：http://dali.tanke756.top/Article/details/gtfmzcekdf.html

int a = 10; printf("%d\n", a);
来源：http://dali.nwbrower.top/Article/details/gtzmruufur.html

[S03] C：读入整数
来源：http://dali.xylfe.cn/Article/details/gtmqgsenvt.html

int x; scanf("%d", &x);
来源：http://dali.chenjidiqi.icu/Article/details/gtzmgjpnxo.html

[S04] C：字符串复制
来源：http://dali.sxryk.cn/Article/details/gtcnnqjsom.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.bjfxy.top/Article/details/gtwjptxvrc.html

[S05] C：字符串长度
来源：http://dali.vqdsnc.cn/Article/details/gtlsmyista.html

strlen(s)
来源：http://dali.wangdashe.top/Article/details/gtqnftuwlk.html

[S06] C：字符串比较
来源：http://dali.cheryme.top/Article/details/gtblfgbkxb.html

strcmp(a, b) == 0
来源：http://dali.xuanzx.com/Article/details/gtbemujyov.html

[S07] C：数组遍历求和
来源：http://dali.gotoacloud.top/Article/details/gtwuxunzzz.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zycfv.cn/Article/details/gtlhukceca.html

[S08] C：动态内存分配与释放
来源：http://dali.hammf.cn/Article/details/gtxnhmxeqv.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.feifeiyinyue.top/Article/details/gtkicirshg.html

[S09] C：结构体定义与初始化
来源：http://dali.yuxming.cn/Article/details/gtcplrcejf.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.shangyingyoupin.top/Article/details/gtfllcywrt.html

[S10] C：指针与解引用
来源：http://dali.kuanghao11.cn/Article/details/gtpswdssie.html

int *p = &a;  *p = 5;
来源：http://dali.yj20258.top/Article/details/gtxwoeflxu.html

[S11] C：逐行读文件
来源：http://dali.yongpay.top/Article/details/gtnyxqquty.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.cashguo.top/Article/details/gtxraptblb.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.gzhubu.top/Article/details/gtlwmnbbzr.html

fclose(f);
来源：http://dali.gzhubu.top/Article/details/gtzljgvoad.html

[S12] C：写文件
来源：http://dali.hnxiangtu.top/Article/details/gtjroqizov.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.nanxinkj.top/Article/details/gthcmsaatw.html

[S13] C：宏定义
来源：http://dali.vqdsnc.cn/Article/details/gtnkpvmhns.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.yangfankeji.com/Article/details/gtptztosla.html

[S14] C：枚举
来源：http://dali.hfpthk.cn/Article/details/gtnnnrpltz.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.gaohongyu789.top/Article/details/gtcoszigjj.html

[S15] C：类型转换
来源：http://dali.hysaishi.cn/Article/details/gtxcbfacnv.html

(double) a / b
来源：http://dali.pengpengdd.cyou/Article/details/gtpgtbmxss.html

[S16] C：位操作置位
来源：http://dali.tianlin.xyz/Article/details/gttvtqiqss.html

x |= (1 << 3);
来源：http://dali.nanxinkj.top/Article/details/gtlhznuaxn.html

[S17] C：安全拼接字符串
来源：http://dali.vqdsnc.cn/Article/details/gtxbbihsfj.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.hnxiangtu.top/Article/details/gtfoqybyan.html

[S18] C：命令行参数
来源：http://dali.xuanzx.com/Article/details/gtnbvkbqlz.html

int main(int argc, char **argv)
来源：http://dali.shzxlz.cn/Article/details/gtgqnlxubo.html

[S19] C：快速排序
来源：http://dali.hnxiangtu.top/Article/details/gtgipvihid.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.yueranfly.top/Article/details/gtnkuntunj.html

[S20] C：二分查找
来源：http://dali.ppjwa.cn/Article/details/gtwvxvgoqu.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgqeoxhcq.html

[S21] C：字符类别判断
来源：http://dali.cqqwz.cn/Article/details/gthlwsdygi.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.guowangkeji.top/Article/details/gtuhgjbmke.html

[S22] C：字符串转数字
来源：http://dali.nanxinkj.top/Article/details/gtjahpvrit.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.jinqigufen.top/Article/details/gtftddpbrr.html

[S23] C：随机数
来源：http://dali.zdqjudy.top/Article/details/gtmejvvjry.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.hnqzz.top/Article/details/gtqjhbwlkz.html

[S24] C：获取本地时间
来源：http://dali.redwolf501.top/Article/details/gtzrbjdlth.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.cashguo.top/Article/details/gtakyebvlg.html

[S25] C：内存拷贝
来源：http://dali.chenzaomai.com/Article/details/gtrsoygghh.html

memcpy(dst, src, n);
来源：http://dali.aibaodan.cn/Article/details/gtimtwjved.html

[S26] C：内存清零
来源：http://dali.cheryme.top/Article/details/gttddkiyhy.html

memset(a, 0, sizeof a);
来源：http://dali.gzhubu.top/Article/details/gtqvfctelc.html

[S27] C：定义常量
来源：http://dali.bjfxy.top/Article/details/gtruurlotz.html

const double PI = 3.14159;
来源：http://dali.andypj.xyz/Article/details/gtxuozbtzx.html

[S28] C：静态变量
来源：http://dali.jqgufenzy.top/Article/details/gtkcchnfeh.html

static int counter = 0;
来源：http://dali.9152youxi.cn/Article/details/gtakyqlduk.html

[S29] C：变参函数
来源：http://dali.cheryme.top/Article/details/gttqrkcvjl.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.jlsjyb.cn/Article/details/gtfwtzvelt.html

[S30] C：头文件保护
来源：http://dali.yj20258888.top/Article/details/gttrjmpgoj.html

#ifndef X_H
来源：http://dali.havefunace.top/Article/details/gtvyzclahm.html

#define X_H
来源：http://dali.jianghu66.top/Article/details/gtrcyqdxad.html

#endif
来源：http://dali.jinghuilouyu.cn/Article/details/gtmktieefj.html

[S31] C++：Hello World
来源：http://dali.0kj1m.cn/Article/details/gtishzrdan.html

#include <iostream>
来源：http://dali.meibo888.top/Article/details/gtzkombyci.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.kuanghao11.cn/Article/details/gteaugldaf.html

[S32] C++：字符串
来源：http://dali.aibaodan.cn/Article/details/gtnwlabyih.html

std::string s = "hi";  s += "!";
来源：http://dali.guannengcc.top/Article/details/gtziwfppxx.html

[S33] C++：vector 增删
来源：http://dali.cqqwz.cn/Article/details/gtozlbozmm.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.iojbl.cn/Article/details/gtclqvemht.html

[S34] C++：遍历 vector
来源：http://dali.zhongyouzk.top/Article/details/gtjbsmdjiq.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.yvedp.cn/Article/details/gtmxsaejzs.html

[S35] C++：map
来源：http://dali.andypj.xyz/Article/details/gtyyzswmqp.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.sufxvd.cn/Article/details/gtspgjqrmk.html

[S36] C++：unordered_map
来源：http://dali.hongshengwenyu.top/Article/details/gtfzxnbydw.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yueranfly.top/Article/details/gtypxzaftt.html

[S37] C++：set
来源：http://dali.jqgufenzy.top/Article/details/gtpgljzqot.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.nanxuanxn.top/Article/details/gtlcoqewss.html

[S38] C++：排序
来源：http://dali.xziqi.cn/Article/details/gtcjabssfp.html

std::sort(v.begin(), v.end());
来源：http://dali.nwbrower.top/Article/details/gtojxidwja.html

[S39] C++：自定义比较器排序
来源：http://dali.snrcjt.cn/Article/details/gtuexwuywi.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhiwuduotai.top/Article/details/gtvsnfaapm.html

[S40] C++：查找元素
来源：http://dali.dianchejie.cn/Article/details/gtlsjqlswi.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.gotoacloud.top/Article/details/gtjoomgykv.html

[S41] C++：类与构造函数
来源：http://dali.ydzc1.top/Article/details/gtuatqinow.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.yj202588.top/Article/details/gtxaibuyxw.html

[S42] C++：继承与虚函数
来源：http://dali.nanxuanxn.top/Article/details/gtioayqbqt.html

class B : public Base { public: void f() override {} };
来源：http://dali.zycfv.cn/Article/details/gtejcstmnh.html

[S43] C++：智能指针
来源：http://dali.jinqigfzy.top/Article/details/gtycwqwmjm.html

auto p = std::make_unique<int>(5);
来源：http://dali.jinghuilouyu.cn/Article/details/gtqfvwltef.html

[S44] C++：引用传参
来源：http://dali.dashuyun.cn/Article/details/gtlskeknda.html

void inc(int &x) { ++x; }
来源：http://dali.wangdashe.top/Article/details/gtzmqdgaja.html

[S45] C++：lambda
来源：http://dali.jqgufenzy.top/Article/details/gttknjqdxi.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.feifeiyinyue.top/Article/details/gtcbqoiyio.html

[S46] C++：函数模板
来源：http://dali.sweek.top/Article/details/gtenntvxzy.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.yvedp.cn/Article/details/gtcywmatdd.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhiwuduotai.top/Article/details/gtoygzruaa.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.shangyingyoupin.top/Article/details/gtruapjjbt.html

[S48] C++：逐行读文件
来源：http://dali.pengpengdd.cyou/Article/details/gtahbfkdgj.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhixingplan.top/Article/details/gtbipptwgl.html

while (std::getline(in, line)) { }
来源：http://dali.gzhubu.top/Article/details/gtuqublyao.html

[S49] C++：写文件
来源：http://dali.zhixingplan.top/Article/details/gthxzpccli.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.smart0.xyz/Article/details/gtuilacobm.html

[S50] C++：格式化数字
来源：http://dali.smart0.xyz/Article/details/gtzltctbny.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.cqqwz.cn/Article/details/gtstbwahfq.html

[S51] C++：显式类型转换
来源：http://dali.andypj.xyz/Article/details/gtnkesneba.html

static_cast<double>(a) / b
来源：http://dali.jqgufenzy.top/Article/details/gtyytpzkjr.html

[S52] C++：const 与 noexcept
来源：http://dali.shuidangran.top/Article/details/gtpysmsnrw.html

int size() const noexcept { return n_; }
来源：http://dali.ehwqpu.com/Article/details/gtridxskqv.html

[S53] C++：移动语义
来源：http://dali.daxiang520.top/Article/details/gtdpchqeit.html

std::vector<int> w = std::move(v);
来源：http://dali.fengsongda.top/Article/details/gtaegzajyg.html

[S54] C++：异常处理
来源：http://dali.fengsongda.top/Article/details/gtskhxnfmh.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.daria6918.cn/Article/details/gtiyxclkwi.html

[S55] C++：结构化绑定
来源：http://dali.xuetiantiany.cn/Article/details/gtjbythzun.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.quarkkingdee.top/Article/details/gthwgemgwh.html

[S56] C++：optional
来源：http://dali.pycfn.com/Article/details/gtjtrvmkby.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhongyouzk.top/Article/details/gthoitjqsw.html

[S57] C++：编译期常量
来源：http://dali.sysykeji.top/Article/details/gtxzkuomur.html

constexpr int N = 10;
来源：http://dali.birdmap.top/Article/details/gtsbmfpsmf.html

[S58] C++：命名空间
来源：http://dali.meibo888.top/Article/details/gtezjskpos.html

namespace ns { int f() { return 1; } }
来源：http://dali.hywenlv.cn/Article/details/gtltiirwzg.html

[S59] C++：静态断言
来源：http://dali.pycfn.com/Article/details/gtxnqrizju.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.xylfe.cn/Article/details/gtlyfmfoww.html

[S60] C++：遍历并删除元素
来源：http://dali.ivvv.top/Article/details/gtkzcwvhwx.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.c1oappe.top/Article/details/gtacnskknw.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtgdcwbmuh.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.nanxuanxn.top/Article/details/gtjdeqspzr.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtjlpszyzp.html

[T01] Kotlin：Hello World
来源：http://dali.xziqi.cn/Article/details/gtkqahbinw.html

println("Hello")
来源：http://dali.haohaochexian.top/Article/details/gtrpwrdedh.html

[T02] Kotlin：变量
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuncgmtfn.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.gogol.net.cn/Article/details/gtovoychxz.html

[T03] Kotlin：字符串模板
来源：http://dali.yuanzhike.top/Article/details/gtbfehftvk.html

"值: $b"
来源：http://dali.snrcjt.cn/Article/details/gtlzebiasr.html

[T04] Kotlin：空安全
来源：http://dali.daxiang520.top/Article/details/gtckggvowj.html

val n: String? = null;  n?.length
来源：http://dali.tianlin.xyz/Article/details/gtgqeyrcsk.html

[T05] Kotlin：when 表达式
来源：http://dali.wangdashe.top/Article/details/gtazrxhfjt.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.pycfn.com/Article/details/gtadhltaxo.html

[T06] Kotlin：集合映射
来源：http://dali.zdqjudy.top/Article/details/gtsznuhvbe.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.mhx1999.top/Article/details/gtrdruklny.html

[T07] Kotlin：集合过滤
来源：http://dali.sxryk.cn/Article/details/gtqttuaanw.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.hfpthk.cn/Article/details/gtwztkhaik.html

[T08] Kotlin：数据类
来源：http://dali.ppjwa.cn/Article/details/gtvlabpvau.html

data class User(val name: String, val age: Int)
来源：http://dali.daxiang520.top/Article/details/gtkyywmuxa.html

[T09] Kotlin：扩展函数
来源：http://dali.jiagoushi.top/Article/details/gtdejeojiz.html

fun String.exclaim() = this + "!"
来源：http://dali.gogol.net.cn/Article/details/gtrbgfkvzo.html

[T10] Kotlin：默认参数
来源：http://dali.yongpay.top/Article/details/gtxtffedws.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.hysaishi.cn/Article/details/gtalcrbiex.html

[T11] Kotlin：协程
来源：http://dali.snrcjt.cn/Article/details/gtatcstnud.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.ivvv.top/Article/details/gtscpemwpt.html

[T12] Kotlin：解构声明
来源：http://dali.jinqigfzy.top/Article/details/gtajslwaco.html

val (a, b) = Pair(1, 2)
来源：http://dali.aizwys.cn/Article/details/gtmdigozpt.html

[T13] Kotlin：只读 Map
来源：http://dali.ppjwa.cn/Article/details/gttgtdjnrt.html

val m = mapOf("a" to 1)
来源：http://dali.fzhhl.top/Article/details/gtabgogsuk.html

[T14] Kotlin：循环
来源：http://dali.aizwys.cn/Article/details/gtmsdtbrxu.html

for (i in 1..10) println(i)
来源：http://dali.yanxiufei.cn/Article/details/gtsxcdwtkn.html

[T15] Kotlin：接口
来源：http://dali.jqgfzy.top/Article/details/gtckuufefr.html

interface Shape { fun area(): Double }
来源：http://dali.sysykeji.top/Article/details/gtcotysefd.html

[T16] Swift：Hello World
来源：http://dali.c1oappe.top/Article/details/gthizgebiv.html

print("Hello")
来源：http://dali.aibaodan.cn/Article/details/gtchsbjxtj.html

[T17] Swift：变量与常量
来源：http://dali.gzhubu.top/Article/details/gtgbrpaujy.html

var a = 1;  let b = 2
来源：http://dali.yj20258888.top/Article/details/gtbhshrlze.html

[T18] Swift：字符串插值
来源：http://dali.wangdashe.top/Article/details/gtfegyoyht.html

"值: \(b)"
来源：http://dali.kuanghao11.cn/Article/details/gtrhomcild.html

[T19] Swift：可选绑定
来源：http://dali.316326.xyz/Article/details/gtmjhunvnn.html

if let n = opt { print(n) }
来源：http://dali.yj202588.top/Article/details/gtkcebrcla.html

[T20] Swift：数组操作
来源：http://dali.ybcxt.top/Article/details/gtjxtiayig.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.jianghu66.top/Article/details/gtmuyjrkjr.html

[T21] Swift：遍历
来源：http://dali.shanyushiyangtech.top/Article/details/gtiviknmnt.html

for x in a { print(x) }
来源：http://dali.cqqwz.cn/Article/details/gtruiyjidy.html

[T22] Swift：字典
来源：http://dali.ivvv.top/Article/details/gtntskpdve.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.vqdsnc.cn/Article/details/gtwnkljcqt.html

[T23] Swift：函数
来源：http://dali.xinyue.icu/Article/details/gtcsrtbzqg.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.chenjidiqi.icu/Article/details/gtrycxbvld.html

[T24] Swift：闭包
来源：http://dali.hysaishi.cn/Article/details/gtugmfmygq.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.tianlin.xyz/Article/details/gtgkgshuvl.html

[T25] Swift：结构体
来源：http://dali.jyoumei.cn/Article/details/gtbzvtnzqy.html

struct P { var x: Int }
来源：http://dali.daxiang520.top/Article/details/gtuqyeiiye.html

[T26] Swift：类与重写
来源：http://dali.ppjwa.cn/Article/details/gtidrahdju.html

class A: Base { override func f() {} }
来源：http://dali.jqgfzy.top/Article/details/gtjjqprygr.html

[T27] Swift：错误处理
来源：http://dali.chenjidiqi.icu/Article/details/gttovskyuj.html

do { try f() } catch { print(error) }
来源：http://dali.hongshengwenyu.top/Article/details/gtfchptdmc.html

[T28] Swift：枚举
来源：http://dali.shzxlz.cn/Article/details/gtfpuweftf.html

enum Color { case red, green }
来源：http://dali.nanxinkj.top/Article/details/gtlljxfebt.html

[T29] Swift：guard 提前返回
来源：http://dali.zhiwuduotai.top/Article/details/gttihfwogt.html

guard let x = opt else { return }
来源：http://dali.redwolf501.top/Article/details/gtznlvqbeb.html

[T30] Swift：协议
来源：http://dali.gaohongyu789.top/Article/details/gtvjxkvrjx.html

protocol Shape { func area() -> Double }
来源：http://dali.chenjidiqi.icu/Article/details/gtrzpvzkcl.html

[T31] Lua：Hello World
来源：http://dali.cashguo.top/Article/details/gtsaelthli.html

print("Hello")
来源：http://dali.yj20258888.top/Article/details/gtveljbhli.html

[T32] Lua：局部变量
来源：http://dali.xuanzx.com/Article/details/gtnrxrnodd.html

local a = 1
来源：http://dali.xziqi.cn/Article/details/gtzssgjtlk.html

[T33] Lua：表（数组）
来源：http://dali.chenlongwang.top/Article/details/gtqhpzklsz.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhengqikj.top/Article/details/gtpjqzuaad.html

[T34] Lua：遍历表
来源：http://dali.0kj1m.cn/Article/details/gtpyxxcuhj.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.smart0.xyz/Article/details/gtdjgoypfs.html

[T35] Lua：字典表
来源：http://dali.xylfe.cn/Article/details/gtgmhgsexp.html

local d = { a = 1 };  d.b = 2
来源：http://dali.c1oappe.top/Article/details/gtpvbttzqn.html

[T36] Lua：函数
来源：http://dali.yj202588.top/Article/details/gtrwjrczjw.html

function add(a, b) return a + b end
来源：http://dali.tanke756.top/Article/details/gtlpdxmwmb.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gtbqrapbtd.html

"a" .. "b"
来源：http://dali.sweek.top/Article/details/gtosxvfrfx.html

[T38] Lua：条件
来源：http://dali.hnxiangtu.top/Article/details/gtxjtkcyvq.html

if x > 0 then print("正") end
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxfsrdzzw.html

[T39] Lua：模式匹配
来源：http://dali.0kj1m.cn/Article/details/gtozrkbftz.html

string.find(s, "%d+")
来源：http://dali.zhiwuduotai.top/Article/details/gtmouitmdq.html

[T40] Lua：元表
来源：http://dali.yonumen.top/Article/details/gteistpefx.html

setmetatable({}, { __index = base })
来源：http://dali.ydzc1.top/Article/details/gtxjgensuj.html

[T41] Perl：Hello World
来源：http://dali.hfpthk.cn/Article/details/gtdjtpqrfz.html

print "Hello\n";
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwexxmhvy.html

[T42] Perl：变量类型
来源：http://dali.yueranfly.top/Article/details/gtrkgyabxq.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.smart0.xyz/Article/details/gtjwbyvkdp.html

[T43] Perl：字符串插值
来源：http://dali.daria6918.cn/Article/details/gtfopfwnae.html

"值: $a"
来源：http://dali.sufxvd.cn/Article/details/gtpwszgcpi.html

[T44] Perl：条件
来源：http://dali.cqqwz.cn/Article/details/gtfvaamyop.html

if ($a > 0) { print "正"; }
来源：http://dali.cucudq.cn/Article/details/gtclthjmjk.html

[T45] Perl：数组遍历
来源：http://dali.xylfe.cn/Article/details/gtzsyutxgf.html

for my $x (@arr) { print $x; }
来源：http://dali.316326.xyz/Article/details/gtnnxqkgzm.html

[T46] Perl：哈希操作
来源：http://dali.tian-w.cn/Article/details/gtomnauwbr.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.jiagoushi.top/Article/details/gtdicohevg.html

[T47] Perl：正则捕获
来源：http://dali.daxiang520.top/Article/details/gtwkuwnjvr.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.guannengcc.top/Article/details/gtgkajeioi.html

[T48] Perl：正则替换
来源：http://dali.xuetiantiany.cn/Article/details/gtcbvgdjey.html

$s =~ s/old/new/g;
来源：http://dali.jiagoushi.top/Article/details/gtcmrhvcmo.html

[T49] Perl：函数
来源：http://dali.dianchejie.cn/Article/details/gtlctczbdx.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.jianghu66.top/Article/details/gtbfpfsumt.html

[T50] Perl：逐行读文件
来源：http://dali.nanxuanxn.top/Article/details/gtpengcari.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.gaohongyu789.top/Article/details/gtdtehpoge.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.hywenlv.cn/Article/details/gtirywdkch.html

[T51] Scala：Hello World
来源：http://dali.sweek.top/Article/details/gtafpgshtu.html

println("Hello")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqiqcsyyt.html

[T52] Scala：变量
来源：http://dali.xziqi.cn/Article/details/gtlhjivfcl.html

val a = 1;  var b = 2
来源：http://dali.chenlongwang.top/Article/details/gtubmihbvu.html

[T53] Scala：字符串插值
来源：http://dali.zhaomingkeji.xyz/Article/details/gttjzoskbu.html

s"值: $b"
来源：http://dali.xuanzx.com/Article/details/gtganammom.html

[T54] Scala：集合映射
来源：http://dali.kuanghao11.cn/Article/details/gtftgbgvzb.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.hysaishi.cn/Article/details/gtyqpfolty.html

[T55] Scala：集合过滤
来源：http://dali.pycfn.com/Article/details/gthupiugin.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.gogol.net.cn/Article/details/gtklcmufzs.html

[T56] Scala：样例类
来源：http://dali.nanxuanxn.top/Article/details/gtpgqdrgwu.html

case class User(name: String, age: Int)
来源：http://dali.0kj1m.cn/Article/details/gtbnrzmtwq.html

[T57] Scala：模式匹配
来源：http://dali.jinghuilouyu.cn/Article/details/gtetatcolr.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.quarkkingdee.top/Article/details/gtxevliabr.html

[T58] Scala：函数定义
来源：http://dali.dianchejie.cn/Article/details/gtiyxewuxd.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.dianchejie.cn/Article/details/gttiiqyhgt.html

[T59] Scala：循环
来源：http://dali.zhongyouzk.top/Article/details/gtxfsohrke.html

for (i <- 1 to 10) println(i)
来源：http://dali.ydzc1.top/Article/details/gtaybhnsro.html

[T60] Scala：折叠
来源：http://dali.guannengcc.top/Article/details/gtblhvtlbr.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnnhcyyxr.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtkquttzps.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.nwbrower.top/Article/details/gtbawzhqdg.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtbobvrajn.html

[U01] Py：创建虚拟环境
来源：http://dali.xziqi.cn/Article/details/gtdxghjryq.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.9152youxi.cn/Article/details/gtzoallovu.html

[U02] Py：导出 / 安装依赖
来源：http://dali.andypj.xyz/Article/details/gtplucftjg.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.gotoacloud.top/Article/details/gtosiylvny.html

[U03] Py：加载 .env 配置
来源：http://dali.vqdsnc.cn/Article/details/gtaxaimees.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.yangfankeji.com/Article/details/gtmjddcxtq.html

[U04] Py：变量调试打印
来源：http://dali.shanyushiyangkeji.top/Article/details/gtahcvpqpl.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.havefunace.top/Article/details/gtcrrzbdko.html

[U05] Py：列表去重且保序
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpoiwugpt.html

list(dict.fromkeys(arr))
来源：http://dali.hysaishi.cn/Article/details/gtmfhbfgff.html

[U06] Py：合并两个字典
来源：http://dali.jiagoushi.top/Article/details/gttmagvdoe.html

{**a, **b}
来源：http://dali.zhoulong.xyz/Article/details/gtaynsjlvy.html

[U07] Py：反转字典键值
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrgafauhh.html

{v: k for k, v in d.items()}
来源：http://dali.vqdsnc.cn/Article/details/gtmcchqqvs.html

[U08] Py：展平二维列表
来源：http://dali.yj20258888.top/Article/details/gtjzcrdums.html

[y for x in nested for y in x]
来源：http://dali.ydzc1.top/Article/details/gtljwsdytw.html


<!-- 参考信息 -->