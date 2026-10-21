代发 wailian999

df -h;  du -sh *
来源：http://dali.jqgufenzy.top/Article/details/gtafkcvnlr.html

[R62] 找最占空间的文件
来源：http://dali.yuanzhike.top/Article/details/gtulsesqaq.html

du -ah . | sort -rh | head -10
来源：http://dali.yuanzhike.top/Article/details/gtijrgiopl.html

[R63] 内存与进程
来源：http://dali.cucudq.cn/Article/details/gtmwwjoozu.html

free -h;  ps aux | grep nginx
来源：http://dali.jinqigfzy.top/Article/details/gtnkfdkcea.html

[R64] 结束进程
来源：http://dali.yuanzhike.top/Article/details/gtdrssljkl.html

kill -9 $(pgrep -f app.py)
来源：http://dali.nanxinkj.top/Article/details/gtgzlzqser.html

[R65] 查看端口占用
来源：http://dali.cheryme.top/Article/details/gtbwwuyhvu.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.kuanghao11.cn/Article/details/gtdvmaitoh.html

[R66] 定时任务
来源：http://dali.ehwqpu.com/Article/details/gtfibrybxe.html

crontab -e;  crontab -l
来源：http://dali.tanke756.top/Article/details/gtiaqwhqvk.html

[R67] 生成随机十六进制串
来源：http://dali.mhx1999.top/Article/details/gtgffiirac.html

openssl rand -hex 16
来源：http://dali.yanxiufei.cn/Article/details/gtobytvuvs.html

[R68] 计算文件校验值
来源：http://dali.ivvv.top/Article/details/gtnjphdyis.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zdqjudy.top/Article/details/gtqlyzvirx.html

[R69] 生成随机密码
来源：http://dali.gzhubu.top/Article/details/gtimmnafso.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhixingplan.top/Article/details/gtltglskjw.html

[R70] 时间戳与互转
来源：http://dali.tanke756.top/Article/details/gtwtqahjts.html

date +%s;  date -d @1700000000
来源：http://dali.bjfxy.top/Article/details/gtprletdhj.html

[R71] 日期格式化
来源：http://dali.chenzaomai.com/Article/details/gtprnqztar.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.fzhhl.top/Article/details/gtdcmwwaso.html

[R72] 等待端口就绪
来源：http://dali.jinghuilouyu.cn/Article/details/gtbusiudyu.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.shuidangran.top/Article/details/gtzvzqtzap.html

[R73] 分割大日志
来源：http://dali.ybcxt.top/Article/details/gthuuekhmg.html

split -l 1000 big.log part_
来源：http://dali.nanxuanxn.top/Article/details/gtgttjzxtz.html

[R74] 批量重命名
来源：http://dali.hammf.cn/Article/details/gtimpnvtyc.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.jqgfzy.top/Article/details/gtvuqblyuh.html

[R75] 导出环境变量
来源：http://dali.jqgufenzy.top/Article/details/gtivdukqcs.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhixingplan.top/Article/details/gthrpvzclh.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gtugfkitxt.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.meibo888.top/Article/details/gtfnnosuca.html

[R77] 读取用户输入
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxczipxzd.html

read -rp "请输入: " ans
来源：http://dali.ivvv.top/Article/details/gtmxvfejbc.html

[R78] 交互式菜单
来源：http://dali.mhx1999.top/Article/details/gtblelquxu.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.ivvv.top/Article/details/gtfnusziri.html

[R79] 解析命令行选项
来源：http://dali.ppjwa.cn/Article/details/gtbiqzijtk.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.yj20258.top/Article/details/gtuziuvgck.html

[R80] 查看脚本执行耗时
来源：http://dali.yonumen.top/Article/details/gtkngcivvi.html

time ./run.sh
来源：http://dali.pengpengdd.cyou/Article/details/gtkelqrusq.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtzmijaexp.html

S. C / C++ 专题
来源：http://dali.quarkkingdee.top/Article/details/gtpymjiuif.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtkarekkft.html

[S01] C：Hello World
来源：http://dali.birdmap.top/Article/details/gtjufblcbd.html

#include <stdio.h>
来源：http://dali.jianghu66.top/Article/details/gtnogjxoez.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.aibaodan.cn/Article/details/gtlozopbgw.html

[S02] C：变量与格式化输出
来源：http://dali.9152youxi.cn/Article/details/gtnajsbumo.html

int a = 10; printf("%d\n", a);
来源：http://dali.aizwys.cn/Article/details/gtbhreqvjc.html

[S03] C：读入整数
来源：http://dali.zhiwuduotai.top/Article/details/gtjemmzwzr.html

int x; scanf("%d", &x);
来源：http://dali.gaohongyu789.top/Article/details/gtdhbunram.html

[S04] C：字符串复制
来源：http://dali.kuanghao11.cn/Article/details/gteyywahdi.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.jinqigfzy.top/Article/details/gtberevirg.html

[S05] C：字符串长度
来源：http://dali.pengpengdd.cyou/Article/details/gtqvfqlfll.html

strlen(s)
来源：http://dali.haohaochexian.top/Article/details/gtdojxnljb.html

[S06] C：字符串比较
来源：http://dali.xuetiantiany.cn/Article/details/gtmpmixczo.html

strcmp(a, b) == 0
来源：http://dali.hywenlv.cn/Article/details/gthffsecdb.html

[S07] C：数组遍历求和
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdouvohdt.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.fengsongda.top/Article/details/gtojtyfvpb.html

[S08] C：动态内存分配与释放
来源：http://dali.hongshengwenyu.top/Article/details/gtbsvvhjfu.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.ivvv.top/Article/details/gthumpjujd.html

[S09] C：结构体定义与初始化
来源：http://dali.ivvv.top/Article/details/gtkpncecbt.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.yj20258.top/Article/details/gtifosngvr.html

[S10] C：指针与解引用
来源：http://dali.cdnleiting.top/Article/details/gtqhepdwip.html

int *p = &a;  *p = 5;
来源：http://dali.wangdashe.top/Article/details/gtbydsaqgg.html

[S11] C：逐行读文件
来源：http://dali.316326.xyz/Article/details/gtyzvigsll.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.yangfankeji.com/Article/details/gtvembymmd.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.hnqzz.top/Article/details/gthmniiair.html

fclose(f);
来源：http://dali.dashuyun.cn/Article/details/gtgosvyjri.html

[S12] C：写文件
来源：http://dali.ppjwa.cn/Article/details/gtsvxuddqy.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.yj20258888.top/Article/details/gtuhvqdjgq.html

[S13] C：宏定义
来源：http://dali.snrcjt.cn/Article/details/gttptbzkku.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.nanxinkj.top/Article/details/gtgkqatuww.html

[S14] C：枚举
来源：http://dali.fengsongda.top/Article/details/gtulwgkbpt.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.bjfxy.top/Article/details/gtudczekvz.html

[S15] C：类型转换
来源：http://dali.meibo888.top/Article/details/gtwmeyyiqq.html

(double) a / b
来源：http://dali.andypj.xyz/Article/details/gtudhacqzx.html

[S16] C：位操作置位
来源：http://dali.jianghu66.top/Article/details/gtdpzfznoi.html

x |= (1 << 3);
来源：http://dali.daxiang520.top/Article/details/gthxpaeghn.html

[S17] C：安全拼接字符串
来源：http://dali.tian-w.cn/Article/details/gtwmsqnpbf.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhoulong.xyz/Article/details/gtgoadwdrl.html

[S18] C：命令行参数
来源：http://dali.mhx1999.top/Article/details/gtkwjxytzn.html

int main(int argc, char **argv)
来源：http://dali.jqgfzy.top/Article/details/gtzopxaxlv.html

[S19] C：快速排序
来源：http://dali.yj20258888.top/Article/details/gtxaxscoeu.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.shzxlz.cn/Article/details/gtducnyxqt.html

[S20] C：二分查找
来源：http://dali.fzhhl.top/Article/details/gtxupkzssw.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.yangfankeji.com/Article/details/gtyrzxxwyo.html

[S21] C：字符类别判断
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqbytwzbg.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gtmzajjrjk.html

[S22] C：字符串转数字
来源：http://dali.yanxiufei.cn/Article/details/gtsrqfflee.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.ybcxt.top/Article/details/gtmrkdbkia.html

[S23] C：随机数
来源：http://dali.shangyingyoupin.top/Article/details/gtgfvfcoxp.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.haohaochexian.top/Article/details/gtpwlhkuqr.html

[S24] C：获取本地时间
来源：http://dali.dashuyun.cn/Article/details/gtyrpqxbtn.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.yanxiufei.cn/Article/details/gtaavjqvbm.html

[S25] C：内存拷贝
来源：http://dali.ivvv.top/Article/details/gtrssioqmi.html

memcpy(dst, src, n);
来源：http://dali.shuidangran.top/Article/details/gthrazvlqi.html

[S26] C：内存清零
来源：http://dali.jqgufenzy.top/Article/details/gtqnnwdyzh.html

memset(a, 0, sizeof a);
来源：http://dali.wangdashe.top/Article/details/gtfdlsjxqm.html

[S27] C：定义常量
来源：http://dali.aibaodan.cn/Article/details/gtjihbdktu.html

const double PI = 3.14159;
来源：http://dali.nanxinkj.top/Article/details/gtanfvqsex.html

[S28] C：静态变量
来源：http://dali.gogol.net.cn/Article/details/gtomhxupsi.html

static int counter = 0;
来源：http://dali.hongshengwenyu.top/Article/details/gtbbadgobc.html

[S29] C：变参函数
来源：http://dali.hfpthk.cn/Article/details/gtkhulopfy.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.0kj1m.cn/Article/details/gtaicffrtx.html

[S30] C：头文件保护
来源：http://dali.fengsongda.top/Article/details/gtwkgponmb.html

#ifndef X_H
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbidjutuv.html

#define X_H
来源：http://dali.pycfn.com/Article/details/gttgbjimlh.html

#endif
来源：http://dali.wangdashe.top/Article/details/gtmfvrvgul.html

[S31] C++：Hello World
来源：http://dali.shangyingyoupin.top/Article/details/gthlgfdeqq.html

#include <iostream>
来源：http://dali.jinqigufen.top/Article/details/gtbsnrmzar.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.cqqwz.cn/Article/details/gtkrtfzzhh.html

[S32] C++：字符串
来源：http://dali.tianlin.xyz/Article/details/gtfsiqonwm.html

std::string s = "hi";  s += "!";
来源：http://dali.jianghu66.top/Article/details/gtjusqcvmn.html

[S33] C++：vector 增删
来源：http://dali.daria6918.cn/Article/details/gtbpmtlmaz.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.sufxvd.cn/Article/details/gtnprxisui.html

[S34] C++：遍历 vector
来源：http://dali.daria6918.cn/Article/details/gtnfwwwnte.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.cheryme.top/Article/details/gtnkcqloug.html

[S35] C++：map
来源：http://dali.shzxlz.cn/Article/details/gtmlbwacag.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.316326.xyz/Article/details/gtqhfudwhd.html

[S36] C++：unordered_map
来源：http://dali.ppjwa.cn/Article/details/gtmsbybqpj.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.gogol.net.cn/Article/details/gtddwrfvvp.html

[S37] C++：set
来源：http://dali.yonumen.top/Article/details/gtfwxolhhi.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.9152youxi.cn/Article/details/gtydxvhdxp.html

[S38] C++：排序
来源：http://dali.sufxvd.cn/Article/details/gtiwrchjqu.html

std::sort(v.begin(), v.end());
来源：http://dali.nanxuanxn.top/Article/details/gtlaczvrof.html

[S39] C++：自定义比较器排序
来源：http://dali.chenlongwang.top/Article/details/gtiowjqgsg.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.sufxvd.cn/Article/details/gtqjjwelhf.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gtehxrondg.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.nanxuanxn.top/Article/details/gtqyuczyno.html

[S41] C++：类与构造函数
来源：http://dali.gaohongyu789.top/Article/details/gtdifnievm.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.yonumen.top/Article/details/gtrpggfqbr.html

[S42] C++：继承与虚函数
来源：http://dali.fzhhl.top/Article/details/gtrzolrikl.html

class B : public Base { public: void f() override {} };
来源：http://dali.hammf.cn/Article/details/gthpxyxfdy.html

[S43] C++：智能指针
来源：http://dali.zdqjudy.top/Article/details/gtngfxvmub.html

auto p = std::make_unique<int>(5);
来源：http://dali.pengpengdd.cyou/Article/details/gtjduddsjb.html

[S44] C++：引用传参
来源：http://dali.havefunace.top/Article/details/gtmjfzgkjw.html

void inc(int &x) { ++x; }
来源：http://dali.ppjwa.cn/Article/details/gthfbbxuwb.html

[S45] C++：lambda
来源：http://dali.zdqjudy.top/Article/details/gtikhiymjs.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.ybcxt.top/Article/details/gtsrpwlwrw.html

[S46] C++：函数模板
来源：http://dali.ppjwa.cn/Article/details/gthitsbefd.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.feifeiyinyue.top/Article/details/gtemlrfwgm.html

[S47] C++：结构化绑定遍历
来源：http://dali.sufxvd.cn/Article/details/gtkcjdhsad.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.wangshuangyany.cn/Article/details/gtckdpoerl.html

[S48] C++：逐行读文件
来源：http://dali.jinqigfzy.top/Article/details/gtxwymysxs.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.yueranfly.top/Article/details/gtxzulrvez.html

while (std::getline(in, line)) { }
来源：http://dali.nanxuanxn.top/Article/details/gtephzzhds.html

[S49] C++：写文件
来源：http://dali.gogol.net.cn/Article/details/gtlnjesblt.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.tanke756.top/Article/details/gtqwuiccyg.html

[S50] C++：格式化数字
来源：http://dali.chenzaomai.com/Article/details/gtbyuuvtgp.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.nwbrower.top/Article/details/gttzoxsmdn.html

[S51] C++：显式类型转换
来源：http://dali.shanyushiyangtech.top/Article/details/gtcsksclxr.html

static_cast<double>(a) / b
来源：http://dali.hfpthk.cn/Article/details/gthnwpyows.html

[S52] C++：const 与 noexcept
来源：http://dali.cdnleiting.top/Article/details/gtexobzwzb.html

int size() const noexcept { return n_; }
来源：http://dali.gogol.net.cn/Article/details/gtgmgqyijn.html

[S53] C++：移动语义
来源：http://dali.nanxinkj.top/Article/details/gtfmmghvix.html

std::vector<int> w = std::move(v);
来源：http://dali.kuanghao11.cn/Article/details/gtmiwqkpjw.html

[S54] C++：异常处理
来源：http://dali.cucudq.cn/Article/details/gtmldotavy.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.c1oappe.top/Article/details/gteqvanqst.html

[S55] C++：结构化绑定
来源：http://dali.hnxiangtu.top/Article/details/gthhqsqujq.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.ehwqpu.com/Article/details/gtymifojnf.html

[S56] C++：optional
来源：http://dali.chenlongwang.top/Article/details/gtpmwzhxio.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.xinyue.icu/Article/details/gtqosvbttc.html

[S57] C++：编译期常量
来源：http://dali.haohaochexian.top/Article/details/gthydbffor.html

constexpr int N = 10;
来源：http://dali.sufxvd.cn/Article/details/gtijmckane.html

[S58] C++：命名空间
来源：http://dali.hammf.cn/Article/details/gtudshvybt.html

namespace ns { int f() { return 1; } }
来源：http://dali.daria6918.cn/Article/details/gtczwupnzt.html

[S59] C++：静态断言
来源：http://dali.guannengcc.top/Article/details/gtjqulngpk.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.tian-w.cn/Article/details/gtuccdoyow.html

[S60] C++：遍历并删除元素
来源：http://dali.feifeiyinyue.top/Article/details/gtuqgfisma.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.chenlongwang.top/Article/details/gtjcxejtjb.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtmaacogpn.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfvaruxxx.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtjzmszreq.html

[T01] Kotlin：Hello World
来源：http://dali.guannengcc.top/Article/details/gtufbuzumo.html

println("Hello")
来源：http://dali.dashuyun.cn/Article/details/gtgqumwjht.html

[T02] Kotlin：变量
来源：http://dali.vqdsnc.cn/Article/details/gtthxtssso.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.yangfankeji.com/Article/details/gtuqeughhq.html

[T03] Kotlin：字符串模板
来源：http://dali.chenzaomai.com/Article/details/gtgnuoafxo.html

"值: $b"
来源：http://dali.yonumen.top/Article/details/gtqmxhmfvb.html

[T04] Kotlin：空安全
来源：http://dali.wangshuangyany.cn/Article/details/gtsidtewta.html

val n: String? = null;  n?.length
来源：http://dali.yueranfly.top/Article/details/gtprffawzx.html

[T05] Kotlin：when 表达式
来源：http://dali.xuetiantiany.cn/Article/details/gtwpdciahq.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.ydzc1.top/Article/details/gtgusdapxe.html

[T06] Kotlin：集合映射
来源：http://dali.gzhubu.top/Article/details/gttvitzyzb.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.xuetiantiany.cn/Article/details/gtiqrrfowq.html

[T07] Kotlin：集合过滤
来源：http://dali.chenlongwang.top/Article/details/gtrgyvlgbv.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.iojbl.cn/Article/details/gtptvljheh.html

[T08] Kotlin：数据类
来源：http://dali.yangfankeji.com/Article/details/gtgzylhsxb.html

data class User(val name: String, val age: Int)
来源：http://dali.jqgfzy.top/Article/details/gtadkpzehb.html

[T09] Kotlin：扩展函数
来源：http://dali.yuxming.cn/Article/details/gttyzijjhg.html

fun String.exclaim() = this + "!"
来源：http://dali.zhengqikj.top/Article/details/gtpvizplhy.html

[T10] Kotlin：默认参数
来源：http://dali.cdnleiting.top/Article/details/gtoivicqsk.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.nanxuanxn.top/Article/details/gttjryqvyz.html

[T11] Kotlin：协程
来源：http://dali.jinqigufen.top/Article/details/gttujbehhq.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhongyouzk.top/Article/details/gtymbxfhuu.html

[T12] Kotlin：解构声明
来源：http://dali.ydzc1.top/Article/details/gticdzzbim.html

val (a, b) = Pair(1, 2)
来源：http://dali.gotoacloud.top/Article/details/gtvfufajsm.html

[T13] Kotlin：只读 Map
来源：http://dali.pycfn.com/Article/details/gtxvdjbyav.html

val m = mapOf("a" to 1)
来源：http://dali.pycfn.com/Article/details/gtmceintsa.html

[T14] Kotlin：循环
来源：http://dali.hysaishi.cn/Article/details/gtmutycpqs.html

for (i in 1..10) println(i)
来源：http://dali.kuanghao11.cn/Article/details/gtmftawrxc.html

[T15] Kotlin：接口
来源：http://dali.yongpay.top/Article/details/gtmeydgfxh.html

interface Shape { fun area(): Double }
来源：http://dali.dashuyun.cn/Article/details/gtpnrvlaxh.html

[T16] Swift：Hello World
来源：http://dali.gotoacloud.top/Article/details/gtrvkvlhmv.html

print("Hello")
来源：http://dali.chenzaomai.com/Article/details/gtlpdsjiaf.html

[T17] Swift：变量与常量
来源：http://dali.cheryme.top/Article/details/gtusifpnco.html

var a = 1;  let b = 2
来源：http://dali.hnqzz.top/Article/details/gtphdhecey.html

[T18] Swift：字符串插值
来源：http://dali.jlsjyb.cn/Article/details/gtbnbemsmm.html

"值: \(b)"
来源：http://dali.sxryk.cn/Article/details/gtzxxaqlci.html

[T19] Swift：可选绑定
来源：http://dali.cashguo.top/Article/details/gtgurwgnwn.html

if let n = opt { print(n) }
来源：http://dali.iojbl.cn/Article/details/gtgwbbylzz.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gtwlwfzhsm.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.yueranfly.top/Article/details/gtjagtbiio.html

[T21] Swift：遍历
来源：http://dali.dianchejie.cn/Article/details/gtihhlzjdd.html

for x in a { print(x) }
来源：http://dali.hfpthk.cn/Article/details/gtfthwshjp.html

[T22] Swift：字典
来源：http://dali.shzxlz.cn/Article/details/gtawfdqyhr.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.hnqzz.top/Article/details/gtiixcrgno.html

[T23] Swift：函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdfcrbfgr.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.chenlongwang.top/Article/details/gtryuqhpzs.html

[T24] Swift：闭包
来源：http://dali.gogol.net.cn/Article/details/gtzwbbgxlw.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.svipenyu.cn/Article/details/gtocnwpmdf.html

[T25] Swift：结构体
来源：http://dali.chenzaomai.com/Article/details/gtalzihdem.html

struct P { var x: Int }
来源：http://dali.hysaishi.cn/Article/details/gtigtlnajm.html

[T26] Swift：类与重写
来源：http://dali.tian-w.cn/Article/details/gtnmpoihwf.html

class A: Base { override func f() {} }
来源：http://dali.jinghuilouyu.cn/Article/details/gtyaosplip.html

[T27] Swift：错误处理
来源：http://dali.bjfxy.top/Article/details/gtkcfcfxno.html

do { try f() } catch { print(error) }
来源：http://dali.cqqwz.cn/Article/details/gtkirjoajn.html

[T28] Swift：枚举
来源：http://dali.tanke756.top/Article/details/gtyombvrnn.html

enum Color { case red, green }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtukmoefwb.html

[T29] Swift：guard 提前返回
来源：http://dali.cdnleiting.top/Article/details/gteqamjhjl.html

guard let x = opt else { return }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxiurllww.html

[T30] Swift：协议
来源：http://dali.dianchejie.cn/Article/details/gtizjewfut.html

protocol Shape { func area() -> Double }
来源：http://dali.xuanzx.com/Article/details/gtdxpnnjqs.html

[T31] Lua：Hello World
来源：http://dali.snrcjt.cn/Article/details/gtafpixmty.html

print("Hello")
来源：http://dali.zhongyouzk.top/Article/details/gtaeyftvng.html

[T32] Lua：局部变量
来源：http://dali.yj20258.top/Article/details/gtvypiiphw.html

local a = 1
来源：http://dali.vqdsnc.cn/Article/details/gtgjbosmnl.html

[T33] Lua：表（数组）
来源：http://dali.hysaishi.cn/Article/details/gtmcngzekt.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.andypj.xyz/Article/details/gtbqqjihfz.html

[T34] Lua：遍历表
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlimofgpf.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.xuanzx.com/Article/details/gtqfbcyqlq.html

[T35] Lua：字典表
来源：http://dali.andypj.xyz/Article/details/gtwgtbppiw.html

local d = { a = 1 };  d.b = 2
来源：http://dali.svipenyu.cn/Article/details/gtaqwsnfnq.html

[T36] Lua：函数
来源：http://dali.xylfe.cn/Article/details/gtiodiywao.html

function add(a, b) return a + b end
来源：http://dali.yj202588.top/Article/details/gtrryqsahd.html

[T37] Lua：字符串拼接
来源：http://dali.yvedp.cn/Article/details/gtoccsrtrb.html

"a" .. "b"
来源：http://dali.zdqjudy.top/Article/details/gtdtmhntox.html

[T38] Lua：条件
来源：http://dali.zhixingplan.top/Article/details/gtguvwupnk.html

if x > 0 then print("正") end
来源：http://dali.zdqjudy.top/Article/details/gtsuzxhmmf.html

[T39] Lua：模式匹配
来源：http://dali.andypj.xyz/Article/details/gtzqhfpdxw.html

string.find(s, "%d+")
来源：http://dali.cucudq.cn/Article/details/gtbtnfbeei.html

[T40] Lua：元表
来源：http://dali.jianghu66.top/Article/details/gtyckiskxq.html

setmetatable({}, { __index = base })
来源：http://dali.hfpthk.cn/Article/details/gtbnfphcdn.html

[T41] Perl：Hello World
来源：http://dali.redwolf501.top/Article/details/gtjbqlvput.html

print "Hello\n";
来源：http://dali.tanke756.top/Article/details/gtyuemfppx.html

[T42] Perl：变量类型
来源：http://dali.zhiwuduotai.top/Article/details/gtqelmiofl.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.haohaochexian.top/Article/details/gthhapvsqx.html

[T43] Perl：字符串插值
来源：http://dali.ybcxt.top/Article/details/gtfdudwqrb.html

"值: $a"
来源：http://dali.shanyushiyangtech.top/Article/details/gtupvejyix.html

[T44] Perl：条件
来源：http://dali.shuidangran.top/Article/details/gtevjenzqt.html

if ($a > 0) { print "正"; }
来源：http://dali.smart0.xyz/Article/details/gtjbpnvsnd.html

[T45] Perl：数组遍历
来源：http://dali.316326.xyz/Article/details/gtppigjidn.html

for my $x (@arr) { print $x; }
来源：http://dali.aibaodan.cn/Article/details/gteetlsfvs.html

[T46] Perl：哈希操作
来源：http://dali.xylfe.cn/Article/details/gtuckiudtc.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaegkrbcf.html

[T47] Perl：正则捕获
来源：http://dali.jiagoushi.top/Article/details/gticalojqr.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.gaohongyu789.top/Article/details/gtvdztpyvj.html

[T48] Perl：正则替换
来源：http://dali.gaohongyu789.top/Article/details/gtdlkfqiku.html

$s =~ s/old/new/g;
来源：http://dali.sweek.top/Article/details/gtfdgjdgls.html

[T49] Perl：函数
来源：http://dali.jinqigufen.top/Article/details/gtaqidtrlj.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.haohaochexian.top/Article/details/gtxhmkudyw.html

[T50] Perl：逐行读文件
来源：http://dali.cdnleiting.top/Article/details/gtjbylwbyb.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.feifeiyinyue.top/Article/details/gtslazvrdc.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.mhx1999.top/Article/details/gtdfoncste.html

[T51] Scala：Hello World
来源：http://dali.daria6918.cn/Article/details/gthxblkvgr.html

println("Hello")
来源：http://dali.xinyue.icu/Article/details/gtkixfasoz.html

[T52] Scala：变量
来源：http://dali.yvedp.cn/Article/details/gtlyqkicxr.html

val a = 1;  var b = 2
来源：http://dali.hysaishi.cn/Article/details/gtlsmblamh.html

[T53] Scala：字符串插值
来源：http://dali.cucudq.cn/Article/details/gtykoqshsv.html

s"值: $b"
来源：http://dali.ppjwa.cn/Article/details/gtectnxbki.html

[T54] Scala：集合映射
来源：http://dali.fzhhl.top/Article/details/gtuofinfrr.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.sweek.top/Article/details/gtheepabxa.html

[T55] Scala：集合过滤
来源：http://dali.sufxvd.cn/Article/details/gtkqzhdcqa.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhoulong.xyz/Article/details/gtdsnttqrd.html

[T56] Scala：样例类
来源：http://dali.jqgfzy.top/Article/details/gtufmwbivg.html

case class User(name: String, age: Int)
来源：http://dali.redwolf501.top/Article/details/gthpbylaex.html

[T57] Scala：模式匹配
来源：http://dali.wangdashe.top/Article/details/gtwousegpk.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.jinqigfzy.top/Article/details/gtvywsomfr.html

[T58] Scala：函数定义
来源：http://dali.snrcjt.cn/Article/details/gtlvwwsrfs.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.pengpengdd.cyou/Article/details/gtrcydouik.html

[T59] Scala：循环
来源：http://dali.svipenyu.cn/Article/details/gtwqgjhnyc.html

for (i <- 1 to 10) println(i)
来源：http://dali.daxiang520.top/Article/details/gtotcncicj.html

[T60] Scala：折叠
来源：http://dali.0kj1m.cn/Article/details/gttcxckdnv.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.shuidangran.top/Article/details/gtwpvhmrji.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtduskawva.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.ehwqpu.com/Article/details/gthmkjagcp.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtnrzyhhtb.html

[U01] Py：创建虚拟环境
来源：http://dali.fzhhl.top/Article/details/gtgaqxubib.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.vqdsnc.cn/Article/details/gtoewdpzjj.html

[U02] Py：导出 / 安装依赖
来源：http://dali.yonumen.top/Article/details/gtkozvwogj.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhongyouzk.top/Article/details/gtgpivimxx.html


<!-- 参考信息 -->