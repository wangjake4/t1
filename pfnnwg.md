代发 wailian999

head -c 16 /dev/urandom | base64
来源：http://dali.guannengcc.top/Article/details/gt2kcagkurt.html

[R70] 时间戳与互转
来源：http://dali.hammf.cn/Article/details/gt2gaztcetm.html

date +%s;  date -d @1700000000
来源：http://dali.sufxvd.cn/Article/details/gt2yxezegrs.html

[R71] 日期格式化
来源：http://dali.gotoacloud.top/Article/details/gt2wxhaonin.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.hongshengwenyu.top/Article/details/gt2aapbzdcx.html

[R72] 等待端口就绪
来源：http://dali.birdmap.top/Article/details/gt2vewyzvlu.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xfmexvjy.html

[R73] 分割大日志
来源：http://dali.hnxiangtu.top/Article/details/gt2ybyqjwxu.html

split -l 1000 big.log part_
来源：http://dali.yuxming.cn/Article/details/gt2zdfpnyom.html

[R74] 批量重命名
来源：http://dali.jlsjyb.cn/Article/details/gt2siouylpz.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhoulong.xyz/Article/details/gt2kotpvuqk.html

[R75] 导出环境变量
来源：http://dali.zhiwuduotai.top/Article/details/gt2wlojijrz.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.pengpengdd.cyou/Article/details/gt2pyvzxaxf.html

[R76] 使用临时文件
来源：http://dali.gogol.net.cn/Article/details/gt2sbtwsmpu.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.0kj1m.cn/Article/details/gt2gnrqkwey.html

[R77] 读取用户输入
来源：http://dali.nanxinkj.top/Article/details/gt2xpgvthfh.html

read -rp "请输入: " ans
来源：http://dali.smart0.xyz/Article/details/gt2tqcjwmch.html

[R78] 交互式菜单
来源：http://dali.gaohongyu789.top/Article/details/gt2erfzuinf.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.feifeiyinyue.top/Article/details/gt2cypqyimi.html

[R79] 解析命令行选项
来源：http://dali.pengpengdd.cyou/Article/details/gt2bpbwxqme.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.haohaochexian.top/Article/details/gt2xudedigd.html

[R80] 查看脚本执行耗时
来源：http://dali.ybcxt.top/Article/details/gt2pxguupbp.html

time ./run.sh
来源：http://dali.zhixingplan.top/Article/details/gt2xurbouuu.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gt2shmfzwle.html

S. C / C++ 专题
来源：http://dali.svipenyu.cn/Article/details/gt2qezvnayg.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2factjkhc.html

[S01] C：Hello World
来源：http://dali.gogol.net.cn/Article/details/gt2cpzxxfcd.html

#include <stdio.h>
来源：http://dali.wangdashe.top/Article/details/gt2psjggwyt.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.gzhubu.top/Article/details/gt2quwaefeb.html

[S02] C：变量与格式化输出
来源：http://dali.xuetiantiany.cn/Article/details/gt2reiqfrhq.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhoulong.xyz/Article/details/gt2lowuolkm.html

[S03] C：读入整数
来源：http://dali.xziqi.cn/Article/details/gt2azvsogec.html

int x; scanf("%d", &x);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2oznchsve.html

[S04] C：字符串复制
来源：http://dali.cqqwz.cn/Article/details/gt2stbprzts.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.xuetiantiany.cn/Article/details/gt2czumktzw.html

[S05] C：字符串长度
来源：http://dali.fengsongda.top/Article/details/gt2qpqddcjn.html

strlen(s)
来源：http://dali.zhiwuduotai.top/Article/details/gt2izqmvfqy.html

[S06] C：字符串比较
来源：http://dali.xuanzx.com/Article/details/gt2bivsdtjo.html

strcmp(a, b) == 0
来源：http://dali.tianlin.xyz/Article/details/gt2pzyfzvyl.html

[S07] C：数组遍历求和
来源：http://dali.pengpengdd.cyou/Article/details/gt2hfgfyhie.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.tian-w.cn/Article/details/gt2coawnbyg.html

[S08] C：动态内存分配与释放
来源：http://dali.sysykeji.top/Article/details/gt2puwzzlwc.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.shangyingyoupin.top/Article/details/gt2kapokkxo.html

[S09] C：结构体定义与初始化
来源：http://dali.aizwys.cn/Article/details/gt2ttdxrhch.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.gogol.net.cn/Article/details/gt2jozokuva.html

[S10] C：指针与解引用
来源：http://dali.gogol.net.cn/Article/details/gt2lodmsvsd.html

int *p = &a;  *p = 5;
来源：http://dali.zhiwuduotai.top/Article/details/gt2jpizbccx.html

[S11] C：逐行读文件
来源：http://dali.ppjwa.cn/Article/details/gt2uegjojuh.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.yuxming.cn/Article/details/gt2xkxtshme.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.ybcxt.top/Article/details/gt2zaxpkqhq.html

fclose(f);
来源：http://dali.yanxiufei.cn/Article/details/gt2pcfiftwx.html

[S12] C：写文件
来源：http://dali.hongshengwenyu.top/Article/details/gt2alevmyti.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.ivvv.top/Article/details/gt2yuioplwh.html

[S13] C：宏定义
来源：http://dali.hysaishi.cn/Article/details/gt2tlsjqxeu.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.xylfe.cn/Article/details/gt2ympnjhpw.html

[S14] C：枚举
来源：http://dali.mhx1999.top/Article/details/gt2kwlilgyr.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.wangdashe.top/Article/details/gt2drvhsuzv.html

[S15] C：类型转换
来源：http://dali.sufxvd.cn/Article/details/gt2qvniaqqu.html

(double) a / b
来源：http://dali.hywenlv.cn/Article/details/gt2qmujpspi.html

[S16] C：位操作置位
来源：http://dali.gaohongyu789.top/Article/details/gt2dsehwvww.html

x |= (1 << 3);
来源：http://dali.daxiang520.top/Article/details/gt2zqhqmfto.html

[S17] C：安全拼接字符串
来源：http://dali.ydzc1.top/Article/details/gt2yiudpdmr.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.sweek.top/Article/details/gt2zfmduoxp.html

[S18] C：命令行参数
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zmlmscva.html

int main(int argc, char **argv)
来源：http://dali.meibo888.top/Article/details/gt2ylrwykng.html

[S19] C：快速排序
来源：http://dali.yueranfly.top/Article/details/gt2gtuhvkvb.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.sysykeji.top/Article/details/gt2qicgkeam.html

[S20] C：二分查找
来源：http://dali.cheryme.top/Article/details/gt2olkydyrp.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.hysaishi.cn/Article/details/gt2dcjhmqrk.html

[S21] C：字符类别判断
来源：http://dali.dianchejie.cn/Article/details/gt2ucsstgps.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.ppjwa.cn/Article/details/gt2pkejdqzd.html

[S22] C：字符串转数字
来源：http://dali.yj20258.top/Article/details/gt2iaoafakq.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.0kj1m.cn/Article/details/gt2nzauiyed.html

[S23] C：随机数
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sqmatbxq.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.yuanzhike.top/Article/details/gt2hhpsemah.html

[S24] C：获取本地时间
来源：http://dali.guowangkeji.top/Article/details/gt2eqmlmmca.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.andypj.xyz/Article/details/gt2msmhzmyo.html

[S25] C：内存拷贝
来源：http://dali.jqgfzy.top/Article/details/gt2ourivxxu.html

memcpy(dst, src, n);
来源：http://dali.zhengqikj.top/Article/details/gt2mqkofhqj.html

[S26] C：内存清零
来源：http://dali.dashuyun.cn/Article/details/gt2rxpqqwyj.html

memset(a, 0, sizeof a);
来源：http://dali.fzhhl.top/Article/details/gt2ynazfkid.html

[S27] C：定义常量
来源：http://dali.jlsjyb.cn/Article/details/gt2izswwkqi.html

const double PI = 3.14159;
来源：http://dali.yueranfly.top/Article/details/gt2ywrvwasv.html

[S28] C：静态变量
来源：http://dali.gzhubu.top/Article/details/gt2ofalbbzr.html

static int counter = 0;
来源：http://dali.snrcjt.cn/Article/details/gt2jeljxutk.html

[S29] C：变参函数
来源：http://dali.xuetiantiany.cn/Article/details/gt2srhfqtli.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.cqqwz.cn/Article/details/gt2gbrmekia.html

[S30] C：头文件保护
来源：http://dali.shuidangran.top/Article/details/gt2xbofsrlw.html

#ifndef X_H
来源：http://dali.316326.xyz/Article/details/gt2xdijcilv.html

#define X_H
来源：http://dali.gotoacloud.top/Article/details/gt2pnfyfcyu.html

#endif
来源：http://dali.0kj1m.cn/Article/details/gt2gkjfhwox.html

[S31] C++：Hello World
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bqljruma.html

#include <iostream>
来源：http://dali.yj20258888.top/Article/details/gt2lluvzseg.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.kuanghao11.cn/Article/details/gt2pedpkttb.html

[S32] C++：字符串
来源：http://dali.ehwqpu.com/Article/details/gt2fyornwsp.html

std::string s = "hi";  s += "!";
来源：http://dali.zdqjudy.top/Article/details/gt2rkwbptld.html

[S33] C++：vector 增删
来源：http://dali.cheryme.top/Article/details/gt2kalusknd.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.ydzc1.top/Article/details/gt2zdoqdvsk.html

[S34] C++：遍历 vector
来源：http://dali.xylfe.cn/Article/details/gt2ojefdjrt.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhongyouzk.top/Article/details/gt2fuzawwtx.html

[S35] C++：map
来源：http://dali.yj20258.top/Article/details/gt2imsvurfp.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.bjfxy.top/Article/details/gt2mglhufls.html

[S36] C++：unordered_map
来源：http://dali.yongpay.top/Article/details/gt2wqxpaxne.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.ehwqpu.com/Article/details/gt2akgtzvib.html

[S37] C++：set
来源：http://dali.jinqigufen.top/Article/details/gt2nqxxqlxp.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.ivvv.top/Article/details/gt2yviyyvuy.html

[S38] C++：排序
来源：http://dali.haohaochexian.top/Article/details/gt2tzpaufmn.html

std::sort(v.begin(), v.end());
来源：http://dali.xziqi.cn/Article/details/gt2zbbkqgib.html

[S39] C++：自定义比较器排序
来源：http://dali.birdmap.top/Article/details/gt2dhjgbmxn.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.hnxiangtu.top/Article/details/gt2yvkyzmrw.html

[S40] C++：查找元素
来源：http://dali.dashuyun.cn/Article/details/gt2fjxqsgsr.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.quarkkingdee.top/Article/details/gt2ofmlimxv.html

[S41] C++：类与构造函数
来源：http://dali.pycfn.com/Article/details/gt2axivrsqm.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.haohaochexian.top/Article/details/gt2lasqpmqr.html

[S42] C++：继承与虚函数
来源：http://dali.c1oappe.top/Article/details/gt2ayouhpvb.html

class B : public Base { public: void f() override {} };
来源：http://dali.svipenyu.cn/Article/details/gt2mzzmjuab.html

[S43] C++：智能指针
来源：http://dali.hammf.cn/Article/details/gt2kjbhfejh.html

auto p = std::make_unique<int>(5);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sgzgrziu.html

[S44] C++：引用传参
来源：http://dali.havefunace.top/Article/details/gt2bjjvfyhe.html

void inc(int &x) { ++x; }
来源：http://dali.quarkkingdee.top/Article/details/gt2yzokolxs.html

[S45] C++：lambda
来源：http://dali.hongshengwenyu.top/Article/details/gt2zihgkcbc.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zycfv.cn/Article/details/gt2wghqesbi.html

[S46] C++：函数模板
来源：http://dali.sysykeji.top/Article/details/gt2cqhogqcx.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.yuanzhike.top/Article/details/gt2rmxkyqsn.html

[S47] C++：结构化绑定遍历
来源：http://dali.pycfn.com/Article/details/gt2gzclrapm.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.cqqwz.cn/Article/details/gt2znkbgooa.html

[S48] C++：逐行读文件
来源：http://dali.quarkkingdee.top/Article/details/gt2mcklwtnm.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.c1oappe.top/Article/details/gt2rwzpawiw.html

while (std::getline(in, line)) { }
来源：http://dali.zdqjudy.top/Article/details/gt2tyejywjp.html

[S49] C++：写文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2etpzeyjy.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.yj202588.top/Article/details/gt2yfojusyw.html

[S50] C++：格式化数字
来源：http://dali.snrcjt.cn/Article/details/gt2nkhyvwxj.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.dashuyun.cn/Article/details/gt2hturdbgm.html

[S51] C++：显式类型转换
来源：http://dali.yj20258.top/Article/details/gt2ecuyupdl.html

static_cast<double>(a) / b
来源：http://dali.hysaishi.cn/Article/details/gt2etqcllup.html

[S52] C++：const 与 noexcept
来源：http://dali.hammf.cn/Article/details/gt2hmzafkwr.html

int size() const noexcept { return n_; }
来源：http://dali.ivvv.top/Article/details/gt2zqlsspro.html

[S53] C++：移动语义
来源：http://dali.hongshengwenyu.top/Article/details/gt2ibcajbnq.html

std::vector<int> w = std::move(v);
来源：http://dali.zhongyouzk.top/Article/details/gt2gpuxwmde.html

[S54] C++：异常处理
来源：http://dali.yongpay.top/Article/details/gt2ucdwoqyx.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.ppjwa.cn/Article/details/gt2asfsllqd.html

[S55] C++：结构化绑定
来源：http://dali.vqdsnc.cn/Article/details/gt2gccqgdrf.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.guannengcc.top/Article/details/gt2eixoluls.html

[S56] C++：optional
来源：http://dali.yvedp.cn/Article/details/gt2anntblxk.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.xziqi.cn/Article/details/gt2ppsimrjf.html

[S57] C++：编译期常量
来源：http://dali.gogol.net.cn/Article/details/gt2yzcxnhpd.html

constexpr int N = 10;
来源：http://dali.vqdsnc.cn/Article/details/gt2vcbnfojr.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2fyjyfusv.html

namespace ns { int f() { return 1; } }
来源：http://dali.pengpengdd.cyou/Article/details/gt2ncwjtevc.html

[S59] C++：静态断言
来源：http://dali.ppjwa.cn/Article/details/gt2ngclwbbx.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.jqgfzy.top/Article/details/gt2wmbepnnm.html

[S60] C++：遍历并删除元素
来源：http://dali.aizwys.cn/Article/details/gt2nxsfdixq.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.haohaochexian.top/Article/details/gt2tyfqebpf.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2lcyyuwoz.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.pycfn.com/Article/details/gt2zwrijvxm.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gt2woitghtn.html

[T01] Kotlin：Hello World
来源：http://dali.hongshengwenyu.top/Article/details/gt2gvvyglee.html

println("Hello")
来源：http://dali.yanxiufei.cn/Article/details/gt2hnfvgdvc.html

[T02] Kotlin：变量
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ciwforck.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.wangdashe.top/Article/details/gt2zqxciybe.html

[T03] Kotlin：字符串模板
来源：http://dali.redwolf501.top/Article/details/gt2qatmgxlh.html

"值: $b"
来源：http://dali.fengsongda.top/Article/details/gt2zqpishuh.html

[T04] Kotlin：空安全
来源：http://dali.guowangkeji.top/Article/details/gt2xwcdvxjw.html

val n: String? = null;  n?.length
来源：http://dali.jyoumei.cn/Article/details/gt2pwzchjbz.html

[T05] Kotlin：when 表达式
来源：http://dali.fzhhl.top/Article/details/gt2hbqqctzp.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.xylfe.cn/Article/details/gt2dubnacss.html

[T06] Kotlin：集合映射
来源：http://dali.kuanghao11.cn/Article/details/gt2qexyuhxm.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.yongpay.top/Article/details/gt2lfobvjnz.html

[T07] Kotlin：集合过滤
来源：http://dali.cqqwz.cn/Article/details/gt2araxutvs.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.yj20258.top/Article/details/gt2htxqlqto.html

[T08] Kotlin：数据类
来源：http://dali.tanke756.top/Article/details/gt2mkctzver.html

data class User(val name: String, val age: Int)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jfcmgzxc.html

[T09] Kotlin：扩展函数
来源：http://dali.tian-w.cn/Article/details/gt2vhwguldv.html

fun String.exclaim() = this + "!"
来源：http://dali.sxryk.cn/Article/details/gt2fxnnyuhl.html

[T10] Kotlin：默认参数
来源：http://dali.fengsongda.top/Article/details/gt2uqjgwifk.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.andypj.xyz/Article/details/gt2gqxmvpja.html

[T11] Kotlin：协程
来源：http://dali.pycfn.com/Article/details/gt2ahsecygr.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.ydzc1.top/Article/details/gt2cvhriyxy.html

[T12] Kotlin：解构声明
来源：http://dali.jianghu66.top/Article/details/gt2bhjiekey.html

val (a, b) = Pair(1, 2)
来源：http://dali.pengpengdd.cyou/Article/details/gt2jypfaeiw.html

[T13] Kotlin：只读 Map
来源：http://dali.smart0.xyz/Article/details/gt2heitbhnm.html

val m = mapOf("a" to 1)
来源：http://dali.pengpengdd.cyou/Article/details/gt2lihbhidy.html

[T14] Kotlin：循环
来源：http://dali.hnxiangtu.top/Article/details/gt2twwihqsy.html

for (i in 1..10) println(i)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2iumopmbn.html

[T15] Kotlin：接口
来源：http://dali.xylfe.cn/Article/details/gt2mqgwulug.html

interface Shape { fun area(): Double }
来源：http://dali.chenjidiqi.icu/Article/details/gt2afvhjekr.html

[T16] Swift：Hello World
来源：http://dali.iojbl.cn/Article/details/gt2xpazbhzr.html

print("Hello")
来源：http://dali.xuanzx.com/Article/details/gt2ximqffix.html

[T17] Swift：变量与常量
来源：http://dali.vqdsnc.cn/Article/details/gt2wmaloyol.html

var a = 1;  let b = 2
来源：http://dali.sufxvd.cn/Article/details/gt2ioxxikzf.html

[T18] Swift：字符串插值
来源：http://dali.tian-w.cn/Article/details/gt2dykrarrt.html

"值: \(b)"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2noiydgcj.html

[T19] Swift：可选绑定
来源：http://dali.gzhubu.top/Article/details/gt2tlgvuyul.html

if let n = opt { print(n) }
来源：http://dali.daria6918.cn/Article/details/gt2vwqlasim.html

[T20] Swift：数组操作
来源：http://dali.svipenyu.cn/Article/details/gt2uerlhekp.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.gzhubu.top/Article/details/gt2exkjyuxq.html

[T21] Swift：遍历
来源：http://dali.fzhhl.top/Article/details/gt2npumwokd.html

for x in a { print(x) }
来源：http://dali.shzxlz.cn/Article/details/gt2fotggqkx.html

[T22] Swift：字典
来源：http://dali.guannengcc.top/Article/details/gt2kvdbneqn.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.dianchejie.cn/Article/details/gt2szewyuqk.html

[T23] Swift：函数
来源：http://dali.cqqwz.cn/Article/details/gt2xeuxhsmn.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.shangyingyoupin.top/Article/details/gt2tyqfrbls.html

[T24] Swift：闭包
来源：http://dali.hywenlv.cn/Article/details/gt2nukdxxoq.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yvabqfdn.html

[T25] Swift：结构体
来源：http://dali.aibaodan.cn/Article/details/gt2ueqyxfng.html

struct P { var x: Int }
来源：http://dali.xziqi.cn/Article/details/gt2pvosdspo.html

[T26] Swift：类与重写
来源：http://dali.ydzc1.top/Article/details/gt2slilkggx.html

class A: Base { override func f() {} }
来源：http://dali.wangshuangyany.cn/Article/details/gt2tqgfglfv.html

[T27] Swift：错误处理
来源：http://dali.zdqjudy.top/Article/details/gt2ehttdpqw.html

do { try f() } catch { print(error) }
来源：http://dali.cqqwz.cn/Article/details/gt2yvuccvrh.html

[T28] Swift：枚举
来源：http://dali.chenzaomai.com/Article/details/gt2itokgbck.html

enum Color { case red, green }
来源：http://dali.nwbrower.top/Article/details/gt2ezeaecwv.html

[T29] Swift：guard 提前返回
来源：http://dali.gaohongyu789.top/Article/details/gt2rmcqvqrg.html

guard let x = opt else { return }
来源：http://dali.gotoacloud.top/Article/details/gt2xbnohmkm.html

[T30] Swift：协议
来源：http://dali.ehwqpu.com/Article/details/gt2xsypnlbp.html

protocol Shape { func area() -> Double }
来源：http://dali.meibo888.top/Article/details/gt2livlzjro.html

[T31] Lua：Hello World
来源：http://dali.ehwqpu.com/Article/details/gt2xmfdubjl.html

print("Hello")
来源：http://dali.ppjwa.cn/Article/details/gt2nyzogaeg.html

[T32] Lua：局部变量
来源：http://dali.andypj.xyz/Article/details/gt2keowsklq.html

local a = 1
来源：http://dali.nwbrower.top/Article/details/gt2ipmgegip.html

[T33] Lua：表（数组）
来源：http://dali.mhx1999.top/Article/details/gt2qtohpzqg.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.yongpay.top/Article/details/gt2kcywfzki.html

[T34] Lua：遍历表
来源：http://dali.havefunace.top/Article/details/gt2zsxihled.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.jqgufenzy.top/Article/details/gt2knxugwjh.html

[T35] Lua：字典表
来源：http://dali.svipenyu.cn/Article/details/gt2efhqfcys.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhongyouzk.top/Article/details/gt2lxfvjqtx.html

[T36] Lua：函数
来源：http://dali.birdmap.top/Article/details/gt2dqyrjydc.html

function add(a, b) return a + b end
来源：http://dali.yonumen.top/Article/details/gt2cjllbqtj.html

[T37] Lua：字符串拼接
来源：http://dali.jinqigfzy.top/Article/details/gt2zwufxegz.html

"a" .. "b"
来源：http://dali.sxryk.cn/Article/details/gt2vkkntdds.html

[T38] Lua：条件
来源：http://dali.mhx1999.top/Article/details/gt2yybmmphx.html

if x > 0 then print("正") end
来源：http://dali.shangyingyoupin.top/Article/details/gt2ckxcdrum.html

[T39] Lua：模式匹配
来源：http://dali.iojbl.cn/Article/details/gt2yumzervh.html

string.find(s, "%d+")
来源：http://dali.yuanzhike.top/Article/details/gt2wajfvokp.html

[T40] Lua：元表
来源：http://dali.jianghu66.top/Article/details/gt2yxazgqvv.html

setmetatable({}, { __index = base })
来源：http://dali.guannengcc.top/Article/details/gt2hrupxrok.html

[T41] Perl：Hello World
来源：http://dali.daxiang520.top/Article/details/gt2ehksviwb.html

print "Hello\n";
来源：http://dali.shangyingyoupin.top/Article/details/gt2gjrndgdx.html

[T42] Perl：变量类型
来源：http://dali.smart0.xyz/Article/details/gt2eiyqmjxr.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.cucudq.cn/Article/details/gt2jdsiowrw.html

[T43] Perl：字符串插值
来源：http://dali.yuxming.cn/Article/details/gt2mfidkxcy.html

"值: $a"
来源：http://dali.snrcjt.cn/Article/details/gt2yjewdfqo.html

[T44] Perl：条件
来源：http://dali.xylfe.cn/Article/details/gt2yvfflkdu.html

if ($a > 0) { print "正"; }
来源：http://dali.nanxuanxn.top/Article/details/gt2ijvdspla.html

[T45] Perl：数组遍历
来源：http://dali.xylfe.cn/Article/details/gt2uilbdorn.html

for my $x (@arr) { print $x; }
来源：http://dali.hnqzz.top/Article/details/gt2uwkccoui.html

[T46] Perl：哈希操作
来源：http://dali.snrcjt.cn/Article/details/gt2lwwsnici.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.meibo888.top/Article/details/gt2tebwharz.html

[T47] Perl：正则捕获
来源：http://dali.tian-w.cn/Article/details/gt2hsxwakcq.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.sysykeji.top/Article/details/gt2dnwphwvu.html

[T48] Perl：正则替换
来源：http://dali.guowangkeji.top/Article/details/gt2anasukqu.html

$s =~ s/old/new/g;
来源：http://dali.svipenyu.cn/Article/details/gt2oqrznxdm.html

[T49] Perl：函数
来源：http://dali.jinqigufen.top/Article/details/gt2kwqsxhul.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.xziqi.cn/Article/details/gt2ypzdrtei.html

[T50] Perl：逐行读文件
来源：http://dali.hnxiangtu.top/Article/details/gt2sbjcazqi.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.jqgufenzy.top/Article/details/gt2mzqnfnue.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.vqdsnc.cn/Article/details/gt2gffguupg.html

[T51] Scala：Hello World
来源：http://dali.tian-w.cn/Article/details/gt2weskohua.html

println("Hello")
来源：http://dali.meibo888.top/Article/details/gt2ednphbof.html

[T52] Scala：变量
来源：http://dali.jlsjyb.cn/Article/details/gt2qrykchna.html

val a = 1;  var b = 2
来源：http://dali.iojbl.cn/Article/details/gt2yglvsocg.html

[T53] Scala：字符串插值
来源：http://dali.kuanghao11.cn/Article/details/gt2jlwjkyld.html

s"值: $b"
来源：http://dali.xinyue.icu/Article/details/gt2rjwqodjs.html

[T54] Scala：集合映射
来源：http://dali.haohaochexian.top/Article/details/gt2mylvokbz.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.wangshuangyany.cn/Article/details/gt2prrlwmtt.html

[T55] Scala：集合过滤
来源：http://dali.gogol.net.cn/Article/details/gt2ymbcoaba.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.ivvv.top/Article/details/gt2tgdutyga.html

[T56] Scala：样例类
来源：http://dali.nanxuanxn.top/Article/details/gt2mrljcxcv.html

case class User(name: String, age: Int)
来源：http://dali.fengsongda.top/Article/details/gt2hiwnpway.html

[T57] Scala：模式匹配
来源：http://dali.pengpengdd.cyou/Article/details/gt2unyugart.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zycfv.cn/Article/details/gt2wfkywswv.html

[T58] Scala：函数定义
来源：http://dali.0kj1m.cn/Article/details/gt2njopripa.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.yj20258888.top/Article/details/gt2aqllumci.html

[T59] Scala：循环
来源：http://dali.chenlongwang.top/Article/details/gt2bceohseh.html

for (i <- 1 to 10) println(i)
来源：http://dali.hnxiangtu.top/Article/details/gt2icnqivte.html

[T60] Scala：折叠
来源：http://dali.gaohongyu789.top/Article/details/gt2wzzveuwx.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.chenlongwang.top/Article/details/gt2wnlwjdmf.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2qaqlpryf.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhoulong.xyz/Article/details/gt2cvdluhqg.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2knljnyko.html

[U01] Py：创建虚拟环境
来源：http://dali.xuetiantiany.cn/Article/details/gt2zlqsbweu.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.dashuyun.cn/Article/details/gt2iqbpdieb.html

[U02] Py：导出 / 安装依赖
来源：http://dali.pengpengdd.cyou/Article/details/gt2sqndkjfy.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.yj202588.top/Article/details/gt2cgsnpcby.html

[U03] Py：加载 .env 配置
来源：http://dali.316326.xyz/Article/details/gt2aanzntfd.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.sysykeji.top/Article/details/gt2xuafhqpo.html

[U04] Py：变量调试打印
来源：http://dali.guowangkeji.top/Article/details/gt2cjiobxny.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.xinyue.icu/Article/details/gt2pbpkjxyg.html

[U05] Py：列表去重且保序
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jgbrjaiy.html

list(dict.fromkeys(arr))
来源：http://dali.dashuyun.cn/Article/details/gt2yswucyfv.html

[U06] Py：合并两个字典
来源：http://dali.xziqi.cn/Article/details/gt2denojuem.html

{**a, **b}
来源：http://dali.gzhubu.top/Article/details/gt2jvnrxikr.html

[U07] Py：反转字典键值
来源：http://dali.dashuyun.cn/Article/details/gt2vourkenb.html

{v: k for k, v in d.items()}
来源：http://dali.dashuyun.cn/Article/details/gt2ppxnwlgz.html

[U08] Py：展平二维列表
来源：http://dali.zhoulong.xyz/Article/details/gt2qkcnnrjn.html

[y for x in nested for y in x]
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tflztiod.html

[U09] Py：字典取最大值的键
来源：http://dali.cqqwz.cn/Article/details/gt2lllcjpzm.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2kzraecut.html

[U10] Py：按值排序字典
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xqeiiuir.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.hysaishi.cn/Article/details/gt2qhsselgd.html


<!-- 参考信息 -->