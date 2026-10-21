代发 wailian999

free -h;  ps aux | grep nginx
来源：http://dali.hnqzz.top/Article/details/gtrgpsdchj.html

[R64] 结束进程
来源：http://dali.feifeiyinyue.top/Article/details/gthqojmsnw.html

kill -9 $(pgrep -f app.py)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmvtjyqfk.html

[R65] 查看端口占用
来源：http://dali.zhixingplan.top/Article/details/gteorhmotl.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.xuanzx.com/Article/details/gtjsibejlv.html

[R66] 定时任务
来源：http://dali.yangfankeji.com/Article/details/gtquqdgdvk.html

crontab -e;  crontab -l
来源：http://dali.ehwqpu.com/Article/details/gtpknutupe.html

[R67] 生成随机十六进制串
来源：http://dali.chenjidiqi.icu/Article/details/gtjnezjizj.html

openssl rand -hex 16
来源：http://dali.yvedp.cn/Article/details/gtcoulpmlk.html

[R68] 计算文件校验值
来源：http://dali.mhx1999.top/Article/details/gtruqvuxql.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.hongshengwenyu.top/Article/details/gtdylmfbug.html

[R69] 生成随机密码
来源：http://dali.yonumen.top/Article/details/gtrapjgmeq.html

head -c 16 /dev/urandom | base64
来源：http://dali.hongshengwenyu.top/Article/details/gtoeqyeobi.html

[R70] 时间戳与互转
来源：http://dali.pycfn.com/Article/details/gtqktejdlb.html

date +%s;  date -d @1700000000
来源：http://dali.0kj1m.cn/Article/details/gtrivfrzcu.html

[R71] 日期格式化
来源：http://dali.xziqi.cn/Article/details/gtrhzwyuma.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.hnqzz.top/Article/details/gtuproheks.html

[R72] 等待端口就绪
来源：http://dali.pengpengdd.cyou/Article/details/gtzmlprxwf.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.316326.xyz/Article/details/gtsqoimdix.html

[R73] 分割大日志
来源：http://dali.jinqigufen.top/Article/details/gtymnztvvx.html

split -l 1000 big.log part_
来源：http://dali.tanke756.top/Article/details/gtgjxjelcx.html

[R74] 批量重命名
来源：http://dali.guowangkeji.top/Article/details/gtgvtljpdb.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.jqgfzy.top/Article/details/gtkxauodxf.html

[R75] 导出环境变量
来源：http://dali.zhoulong.xyz/Article/details/gtxsqrcrsj.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.gzhubu.top/Article/details/gtckyjnphk.html

[R76] 使用临时文件
来源：http://dali.mhx1999.top/Article/details/gtpiwnkjqm.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.cheryme.top/Article/details/gtgfpqmbpi.html

[R77] 读取用户输入
来源：http://dali.aibaodan.cn/Article/details/gtpipsjqcz.html

read -rp "请输入: " ans
来源：http://dali.shanyushiyangtech.top/Article/details/gtapybyekz.html

[R78] 交互式菜单
来源：http://dali.nanxuanxn.top/Article/details/gtnofcwzkg.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.guannengcc.top/Article/details/gtoznrinqd.html

[R79] 解析命令行选项
来源：http://dali.ivvv.top/Article/details/gtidxzfquc.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.jqgufenzy.top/Article/details/gtkhzqswok.html

[R80] 查看脚本执行耗时
来源：http://dali.zhengqikj.top/Article/details/gtmgkohppm.html

time ./run.sh
来源：http://dali.hywenlv.cn/Article/details/gtmftxckln.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtsvzekknh.html

S. C / C++ 专题
来源：http://dali.gaohongyu789.top/Article/details/gtmjenjuzd.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtqpgrerla.html

[S01] C：Hello World
来源：http://dali.tian-w.cn/Article/details/gtrkthnzku.html

#include <stdio.h>
来源：http://dali.zdqjudy.top/Article/details/gtbagbhenm.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.shuidangran.top/Article/details/gtyorupywv.html

[S02] C：变量与格式化输出
来源：http://dali.xinyue.icu/Article/details/gtiwjftjks.html

int a = 10; printf("%d\n", a);
来源：http://dali.yuxming.cn/Article/details/gtszeftflm.html

[S03] C：读入整数
来源：http://dali.cqqwz.cn/Article/details/gtqzniznan.html

int x; scanf("%d", &x);
来源：http://dali.hongshengwenyu.top/Article/details/gtogjjmgjj.html

[S04] C：字符串复制
来源：http://dali.cucudq.cn/Article/details/gtkqwzodso.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.feifeiyinyue.top/Article/details/gtbcygdahk.html

[S05] C：字符串长度
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaarrjwcd.html

strlen(s)
来源：http://dali.chenlongwang.top/Article/details/gtjytyuyld.html

[S06] C：字符串比较
来源：http://dali.ydzc1.top/Article/details/gtwrengfmr.html

strcmp(a, b) == 0
来源：http://dali.sweek.top/Article/details/gtemhkukeb.html

[S07] C：数组遍历求和
来源：http://dali.ehwqpu.com/Article/details/gthaetvurj.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaorzvciu.html

[S08] C：动态内存分配与释放
来源：http://dali.sweek.top/Article/details/gttvbiicgl.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.jlsjyb.cn/Article/details/gtbnvvtszk.html

[S09] C：结构体定义与初始化
来源：http://dali.fengsongda.top/Article/details/gtjjcmahuq.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhengqikj.top/Article/details/gtzjnvxeyd.html

[S10] C：指针与解引用
来源：http://dali.dashuyun.cn/Article/details/gtyieffexh.html

int *p = &a;  *p = 5;
来源：http://dali.gaohongyu789.top/Article/details/gtvzqywthd.html

[S11] C：逐行读文件
来源：http://dali.sysykeji.top/Article/details/gtoghuqyeu.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.sysykeji.top/Article/details/gtqpbpscxv.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.jyoumei.cn/Article/details/gtvuettpaa.html

fclose(f);
来源：http://dali.yuxming.cn/Article/details/gtvjcwvjkg.html

[S12] C：写文件
来源：http://dali.zhongyouzk.top/Article/details/gtjmgxuvzq.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.c1oappe.top/Article/details/gtzetgllal.html

[S13] C：宏定义
来源：http://dali.guowangkeji.top/Article/details/gticmdzeyn.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhengqikj.top/Article/details/gtfeaetaux.html

[S14] C：枚举
来源：http://dali.gzhubu.top/Article/details/gtdopkybyz.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.yj202588.top/Article/details/gtvovpxnvy.html

[S15] C：类型转换
来源：http://dali.wangshuangyany.cn/Article/details/gtnyakgtdt.html

(double) a / b
来源：http://dali.yj202588.top/Article/details/gtpeuhhcry.html

[S16] C：位操作置位
来源：http://dali.hywenlv.cn/Article/details/gtxkdqllip.html

x |= (1 << 3);
来源：http://dali.zhoulong.xyz/Article/details/gtcgcexieb.html

[S17] C：安全拼接字符串
来源：http://dali.tanke756.top/Article/details/gtnuukowac.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.svipenyu.cn/Article/details/gtgprrdyvj.html

[S18] C：命令行参数
来源：http://dali.aibaodan.cn/Article/details/gtxdebsxjg.html

int main(int argc, char **argv)
来源：http://dali.xinyue.icu/Article/details/gtxaiwfhtw.html

[S19] C：快速排序
来源：http://dali.ehwqpu.com/Article/details/gtpglpbqiw.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.cheryme.top/Article/details/gtxxvvxjnq.html

[S20] C：二分查找
来源：http://dali.cucudq.cn/Article/details/gtowzdfpar.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.ehwqpu.com/Article/details/gtnwinhnsn.html

[S21] C：字符类别判断
来源：http://dali.shuidangran.top/Article/details/gtkzabnirp.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zdqjudy.top/Article/details/gtpweiugkj.html

[S22] C：字符串转数字
来源：http://dali.hywenlv.cn/Article/details/gtplwcqxpe.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.vqdsnc.cn/Article/details/gtrxhsvxqe.html

[S23] C：随机数
来源：http://dali.cqqwz.cn/Article/details/gtjnysxuym.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zycfv.cn/Article/details/gtydreiioe.html

[S24] C：获取本地时间
来源：http://dali.tian-w.cn/Article/details/gtiakqwftd.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.tanke756.top/Article/details/gtigxqoptp.html

[S25] C：内存拷贝
来源：http://dali.cashguo.top/Article/details/gtpbfhaqap.html

memcpy(dst, src, n);
来源：http://dali.iojbl.cn/Article/details/gtsiozxuuu.html

[S26] C：内存清零
来源：http://dali.daxiang520.top/Article/details/gtfhjfdufv.html

memset(a, 0, sizeof a);
来源：http://dali.316326.xyz/Article/details/gtdmpzxora.html

[S27] C：定义常量
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpbkohaiu.html

const double PI = 3.14159;
来源：http://dali.xziqi.cn/Article/details/gtkrdtsojo.html

[S28] C：静态变量
来源：http://dali.jyoumei.cn/Article/details/gttjuwzypq.html

static int counter = 0;
来源：http://dali.aizwys.cn/Article/details/gtznjwjmcs.html

[S29] C：变参函数
来源：http://dali.wangdashe.top/Article/details/gtfljxhhur.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.shanyushiyangtech.top/Article/details/gtnxnnklla.html

[S30] C：头文件保护
来源：http://dali.ppjwa.cn/Article/details/gtfydhqxlo.html

#ifndef X_H
来源：http://dali.ppjwa.cn/Article/details/gtxtncyrup.html

#define X_H
来源：http://dali.hnxiangtu.top/Article/details/gtkavtifxg.html

#endif
来源：http://dali.birdmap.top/Article/details/gtwqtnraya.html

[S31] C++：Hello World
来源：http://dali.0kj1m.cn/Article/details/gtjvfsyplg.html

#include <iostream>
来源：http://dali.yuanzhike.top/Article/details/gtekxbqyhz.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.yanxiufei.cn/Article/details/gtyfcfrrxf.html

[S32] C++：字符串
来源：http://dali.snrcjt.cn/Article/details/gtnfalfdfu.html

std::string s = "hi";  s += "!";
来源：http://dali.ehwqpu.com/Article/details/gtipjpxgpy.html

[S33] C++：vector 增删
来源：http://dali.jqgufenzy.top/Article/details/gtoypnwuol.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.yueranfly.top/Article/details/gtacuxdngs.html

[S34] C++：遍历 vector
来源：http://dali.haohaochexian.top/Article/details/gtrhfedsmg.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.yongpay.top/Article/details/gtjpuouyhb.html

[S35] C++：map
来源：http://dali.sweek.top/Article/details/gtupmdannf.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.guannengcc.top/Article/details/gtqkdbajnf.html

[S36] C++：unordered_map
来源：http://dali.tanke756.top/Article/details/gtaucjnvdt.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.svipenyu.cn/Article/details/gteqyrndyw.html

[S37] C++：set
来源：http://dali.yueranfly.top/Article/details/gtvimkswki.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.jyoumei.cn/Article/details/gtvaukpmyq.html

[S38] C++：排序
来源：http://dali.zhoulong.xyz/Article/details/gtycxtnsva.html

std::sort(v.begin(), v.end());
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcjmvxhgk.html

[S39] C++：自定义比较器排序
来源：http://dali.redwolf501.top/Article/details/gtuoovvnod.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.nwbrower.top/Article/details/gtkrcdbkxa.html

[S40] C++：查找元素
来源：http://dali.iojbl.cn/Article/details/gtnfxdrckz.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.yongpay.top/Article/details/gtmbprupua.html

[S41] C++：类与构造函数
来源：http://dali.yj20258888.top/Article/details/gtmqepkoel.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.xuetiantiany.cn/Article/details/gteyfqqemo.html

[S42] C++：继承与虚函数
来源：http://dali.cqqwz.cn/Article/details/gtsbkhpkoq.html

class B : public Base { public: void f() override {} };
来源：http://dali.svipenyu.cn/Article/details/gtslvyufcu.html

[S43] C++：智能指针
来源：http://dali.ydzc1.top/Article/details/gtxgvcimut.html

auto p = std::make_unique<int>(5);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtufdfwxit.html

[S44] C++：引用传参
来源：http://dali.chenjidiqi.icu/Article/details/gtqmukizcd.html

void inc(int &x) { ++x; }
来源：http://dali.iojbl.cn/Article/details/gtqdaaqhbi.html

[S45] C++：lambda
来源：http://dali.hysaishi.cn/Article/details/gtrgwkkzot.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.xuetiantiany.cn/Article/details/gtoeefbmnu.html

[S46] C++：函数模板
来源：http://dali.nanxuanxn.top/Article/details/gtjwzykjml.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.fzhhl.top/Article/details/gtkzctwxes.html

[S47] C++：结构化绑定遍历
来源：http://dali.hywenlv.cn/Article/details/gtvrjqrwvu.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.jlsjyb.cn/Article/details/gtuihazlry.html

[S48] C++：逐行读文件
来源：http://dali.guannengcc.top/Article/details/gteinzncjd.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.shzxlz.cn/Article/details/gtrckrpmcj.html

while (std::getline(in, line)) { }
来源：http://dali.cheryme.top/Article/details/gteigoljqw.html

[S49] C++：写文件
来源：http://dali.zhiwuduotai.top/Article/details/gtywwgoqjb.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.cdnleiting.top/Article/details/gtjggfldwv.html

[S50] C++：格式化数字
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtslvacuif.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.yvedp.cn/Article/details/gtlyoansjr.html

[S51] C++：显式类型转换
来源：http://dali.hfpthk.cn/Article/details/gtjoltotzc.html

static_cast<double>(a) / b
来源：http://dali.pengpengdd.cyou/Article/details/gtfhwimpdp.html

[S52] C++：const 与 noexcept
来源：http://dali.yuanzhike.top/Article/details/gtjxfhpwng.html

int size() const noexcept { return n_; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjiwzlwia.html

[S53] C++：移动语义
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrahbdhef.html

std::vector<int> w = std::move(v);
来源：http://dali.aibaodan.cn/Article/details/gtcedzbqgm.html

[S54] C++：异常处理
来源：http://dali.nanxuanxn.top/Article/details/gtmtauvtpx.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.yvedp.cn/Article/details/gtbwxcxujx.html

[S55] C++：结构化绑定
来源：http://dali.fengsongda.top/Article/details/gtammmipej.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.vqdsnc.cn/Article/details/gtcbesjnzx.html

[S56] C++：optional
来源：http://dali.nanxuanxn.top/Article/details/gtveiiwxsm.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.chenzaomai.com/Article/details/gttzpcgwxa.html

[S57] C++：编译期常量
来源：http://dali.gaohongyu789.top/Article/details/gtmpskbcsf.html

constexpr int N = 10;
来源：http://dali.cqqwz.cn/Article/details/gtfakkgzxy.html

[S58] C++：命名空间
来源：http://dali.cdnleiting.top/Article/details/gtgvfhecru.html

namespace ns { int f() { return 1; } }
来源：http://dali.vqdsnc.cn/Article/details/gtwzysdneo.html

[S59] C++：静态断言
来源：http://dali.shuidangran.top/Article/details/gtzwvhyxlw.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.316326.xyz/Article/details/gtqvtplvts.html

[S60] C++：遍历并删除元素
来源：http://dali.snrcjt.cn/Article/details/gtrwscchwa.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhixingplan.top/Article/details/gtevvbmbgf.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gttzkkbumh.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.haohaochexian.top/Article/details/gtbgkqwxmr.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtluokfsmt.html

[T01] Kotlin：Hello World
来源：http://dali.hongshengwenyu.top/Article/details/gtbvdbeagw.html

println("Hello")
来源：http://dali.pycfn.com/Article/details/gtqszuvbjc.html

[T02] Kotlin：变量
来源：http://dali.guowangkeji.top/Article/details/gtjcezbodo.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.havefunace.top/Article/details/gtftgobvnb.html

[T03] Kotlin：字符串模板
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzkumhyog.html

"值: $b"
来源：http://dali.0kj1m.cn/Article/details/gtrfuywtsn.html

[T04] Kotlin：空安全
来源：http://dali.yj20258888.top/Article/details/gtginvsqou.html

val n: String? = null;  n?.length
来源：http://dali.gzhubu.top/Article/details/gtvbpaqgmb.html

[T05] Kotlin：when 表达式
来源：http://dali.havefunace.top/Article/details/gtgpdsrzyp.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.jinqigfzy.top/Article/details/gtrzqtaxbv.html

[T06] Kotlin：集合映射
来源：http://dali.yuanzhike.top/Article/details/gtdbjhuvjc.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.fengsongda.top/Article/details/gtghnqehwp.html

[T07] Kotlin：集合过滤
来源：http://dali.hnxiangtu.top/Article/details/gtwalsqfdj.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhongyouzk.top/Article/details/gtlhgtlmgz.html

[T08] Kotlin：数据类
来源：http://dali.havefunace.top/Article/details/gtwcyqcuue.html

data class User(val name: String, val age: Int)
来源：http://dali.guannengcc.top/Article/details/gtgifbries.html

[T09] Kotlin：扩展函数
来源：http://dali.nwbrower.top/Article/details/gtxmrgunib.html

fun String.exclaim() = this + "!"
来源：http://dali.fzhhl.top/Article/details/gtiskltskr.html

[T10] Kotlin：默认参数
来源：http://dali.bjfxy.top/Article/details/gtmmnxhvez.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.redwolf501.top/Article/details/gtmnupdpbr.html

[T11] Kotlin：协程
来源：http://dali.hnqzz.top/Article/details/gtmbopipbh.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbvuikfla.html

[T12] Kotlin：解构声明
来源：http://dali.wangdashe.top/Article/details/gtlmtzvyuj.html

val (a, b) = Pair(1, 2)
来源：http://dali.jiagoushi.top/Article/details/gtzwmffsud.html

[T13] Kotlin：只读 Map
来源：http://dali.aizwys.cn/Article/details/gttgofftho.html

val m = mapOf("a" to 1)
来源：http://dali.yuanzhike.top/Article/details/gtkftuhrrc.html

[T14] Kotlin：循环
来源：http://dali.nanxuanxn.top/Article/details/gtuajgrinn.html

for (i in 1..10) println(i)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlxkfhndi.html

[T15] Kotlin：接口
来源：http://dali.yj202588.top/Article/details/gtwgedibzl.html

interface Shape { fun area(): Double }
来源：http://dali.cqqwz.cn/Article/details/gtggprvreq.html

[T16] Swift：Hello World
来源：http://dali.yanxiufei.cn/Article/details/gthpdscbgj.html

print("Hello")
来源：http://dali.chenjidiqi.icu/Article/details/gtrimnaxxy.html

[T17] Swift：变量与常量
来源：http://dali.gotoacloud.top/Article/details/gtszczolfy.html

var a = 1;  let b = 2
来源：http://dali.sufxvd.cn/Article/details/gtsnfdlfxz.html

[T18] Swift：字符串插值
来源：http://dali.jinqigfzy.top/Article/details/gteqejglbq.html

"值: \(b)"
来源：http://dali.jianghu66.top/Article/details/gttbilcjah.html

[T19] Swift：可选绑定
来源：http://dali.chenlongwang.top/Article/details/gtztyfpmfm.html

if let n = opt { print(n) }
来源：http://dali.zhixingplan.top/Article/details/gthxtftnpx.html

[T20] Swift：数组操作
来源：http://dali.gotoacloud.top/Article/details/gtaqffkvls.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxluyehdx.html

[T21] Swift：遍历
来源：http://dali.yongpay.top/Article/details/gtczuzsfue.html

for x in a { print(x) }
来源：http://dali.shuidangran.top/Article/details/gttfidmfol.html

[T22] Swift：字典
来源：http://dali.zhoulong.xyz/Article/details/gtdbldmydp.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.cashguo.top/Article/details/gtryagfmdu.html

[T23] Swift：函数
来源：http://dali.gotoacloud.top/Article/details/gtmnduqvey.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbssoswnh.html

[T24] Swift：闭包
来源：http://dali.gaohongyu789.top/Article/details/gtsqunnrpn.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.yj20258888.top/Article/details/gtfajbjjvm.html

[T25] Swift：结构体
来源：http://dali.hongshengwenyu.top/Article/details/gtqwlhffgd.html

struct P { var x: Int }
来源：http://dali.snrcjt.cn/Article/details/gtygisprvy.html

[T26] Swift：类与重写
来源：http://dali.jqgufenzy.top/Article/details/gtjqktwhat.html

class A: Base { override func f() {} }
来源：http://dali.jianghu66.top/Article/details/gtyaourhdb.html

[T27] Swift：错误处理
来源：http://dali.tanke756.top/Article/details/gtiqurzqow.html

do { try f() } catch { print(error) }
来源：http://dali.zhixingplan.top/Article/details/gtwzjkyovy.html

[T28] Swift：枚举
来源：http://dali.aibaodan.cn/Article/details/gtylxjiqpy.html

enum Color { case red, green }
来源：http://dali.hnqzz.top/Article/details/gtzbecqxev.html

[T29] Swift：guard 提前返回
来源：http://dali.zdqjudy.top/Article/details/gtoiapnvlv.html

guard let x = opt else { return }
来源：http://dali.haohaochexian.top/Article/details/gtkwazafxm.html

[T30] Swift：协议
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlvflkizh.html

protocol Shape { func area() -> Double }
来源：http://dali.nanxuanxn.top/Article/details/gtheixwvwk.html

[T31] Lua：Hello World
来源：http://dali.cucudq.cn/Article/details/gtamezpdmh.html

print("Hello")
来源：http://dali.jlsjyb.cn/Article/details/gtgtknjten.html

[T32] Lua：局部变量
来源：http://dali.xuanzx.com/Article/details/gtijosmsrr.html

local a = 1
来源：http://dali.nanxuanxn.top/Article/details/gtrrrdvsau.html

[T33] Lua：表（数组）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjzailgcx.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.bjfxy.top/Article/details/gtnopmyxdg.html

[T34] Lua：遍历表
来源：http://dali.jqgufenzy.top/Article/details/gtbdcjtqhh.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.aizwys.cn/Article/details/gtgtqpubzk.html

[T35] Lua：字典表
来源：http://dali.jinqigfzy.top/Article/details/gthrqhngwq.html

local d = { a = 1 };  d.b = 2
来源：http://dali.nanxinkj.top/Article/details/gtgtiktmqk.html

[T36] Lua：函数
来源：http://dali.chenlongwang.top/Article/details/gtvhagtjpw.html

function add(a, b) return a + b end
来源：http://dali.shzxlz.cn/Article/details/gtqmzczljm.html

[T37] Lua：字符串拼接
来源：http://dali.yj202588.top/Article/details/gtejeazqko.html

"a" .. "b"
来源：http://dali.gzhubu.top/Article/details/gtwlijigyn.html

[T38] Lua：条件
来源：http://dali.bjfxy.top/Article/details/gtpzplinxo.html

if x > 0 then print("正") end
来源：http://dali.xziqi.cn/Article/details/gtwigngono.html

[T39] Lua：模式匹配
来源：http://dali.xinyue.icu/Article/details/gtipzloofi.html

string.find(s, "%d+")
来源：http://dali.daxiang520.top/Article/details/gtamteiomi.html

[T40] Lua：元表
来源：http://dali.cashguo.top/Article/details/gtdnyiivik.html

setmetatable({}, { __index = base })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzpxoijto.html

[T41] Perl：Hello World
来源：http://dali.birdmap.top/Article/details/gtseppuwhj.html

print "Hello\n";
来源：http://dali.nanxinkj.top/Article/details/gtsxhobore.html

[T42] Perl：变量类型
来源：http://dali.fengsongda.top/Article/details/gtggaaxwws.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.xylfe.cn/Article/details/gtskyvpkqa.html

[T43] Perl：字符串插值
来源：http://dali.jianghu66.top/Article/details/gtptvtlknt.html

"值: $a"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcwwihnet.html

[T44] Perl：条件
来源：http://dali.guowangkeji.top/Article/details/gtmfmlarnw.html

if ($a > 0) { print "正"; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcbqywftf.html

[T45] Perl：数组遍历
来源：http://dali.0kj1m.cn/Article/details/gtrdtdthaw.html

for my $x (@arr) { print $x; }
来源：http://dali.tian-w.cn/Article/details/gtlscqdipz.html

[T46] Perl：哈希操作
来源：http://dali.hnxiangtu.top/Article/details/gtkuhgzgnl.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.0kj1m.cn/Article/details/gtouflyefg.html

[T47] Perl：正则捕获
来源：http://dali.jinqigufen.top/Article/details/gtydxytddu.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.iojbl.cn/Article/details/gtwgoadlsq.html

[T48] Perl：正则替换
来源：http://dali.9152youxi.cn/Article/details/gtdzcdpyfl.html

$s =~ s/old/new/g;
来源：http://dali.fengsongda.top/Article/details/gtmeiwqefe.html

[T49] Perl：函数
来源：http://dali.zhongyouzk.top/Article/details/gtorhppyrs.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.jinqigfzy.top/Article/details/gtjqbgierw.html

[T50] Perl：逐行读文件
来源：http://dali.316326.xyz/Article/details/gtafniippa.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.vqdsnc.cn/Article/details/gttqwidoix.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.iojbl.cn/Article/details/gtlrxoabba.html

[T51] Scala：Hello World
来源：http://dali.hnqzz.top/Article/details/gtpaoupahy.html

println("Hello")
来源：http://dali.iojbl.cn/Article/details/gthulictav.html

[T52] Scala：变量
来源：http://dali.wangshuangyany.cn/Article/details/gtxfvicfxv.html

val a = 1;  var b = 2
来源：http://dali.tanke756.top/Article/details/gtysayleaz.html

[T53] Scala：字符串插值
来源：http://dali.yuxming.cn/Article/details/gtumznyccv.html

s"值: $b"
来源：http://dali.tian-w.cn/Article/details/gtimogtena.html

[T54] Scala：集合映射
来源：http://dali.daxiang520.top/Article/details/gttkrwmwti.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.shanyushiyangtech.top/Article/details/gtqxtnjxkf.html

[T55] Scala：集合过滤
来源：http://dali.jinghuilouyu.cn/Article/details/gthuohgvee.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.sweek.top/Article/details/gtebailktv.html

[T56] Scala：样例类
来源：http://dali.zhixingplan.top/Article/details/gtoomghyfo.html

case class User(name: String, age: Int)
来源：http://dali.zhiwuduotai.top/Article/details/gtlikoshzr.html

[T57] Scala：模式匹配
来源：http://dali.ydzc1.top/Article/details/gtioubsyms.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.ppjwa.cn/Article/details/gtcxomrllx.html

[T58] Scala：函数定义
来源：http://dali.xylfe.cn/Article/details/gtkahjbrns.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.jqgfzy.top/Article/details/gtmckgdwnp.html

[T59] Scala：循环
来源：http://dali.daxiang520.top/Article/details/gtibbfgjhh.html

for (i <- 1 to 10) println(i)
来源：http://dali.meibo888.top/Article/details/gtjflkhagn.html

[T60] Scala：折叠
来源：http://dali.gogol.net.cn/Article/details/gtieqnsnuf.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.mhx1999.top/Article/details/gtwkeeuxhf.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtkfebzowu.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.ppjwa.cn/Article/details/gtpirdtewo.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtukfsjvlk.html

[U01] Py：创建虚拟环境
来源：http://dali.ydzc1.top/Article/details/gthodhypjg.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.xziqi.cn/Article/details/gtnjustjns.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhengqikj.top/Article/details/gtkcxucvjg.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.ehwqpu.com/Article/details/gtzoqkrjqw.html

[U03] Py：加载 .env 配置
来源：http://dali.daxiang520.top/Article/details/gtnhrnwyeu.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhiwuduotai.top/Article/details/gtexjcondp.html

[U04] Py：变量调试打印
来源：http://dali.svipenyu.cn/Article/details/gtongoirgv.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.yj202588.top/Article/details/gtfrmchlpo.html


<!-- 参考信息 -->