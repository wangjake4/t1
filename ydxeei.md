代发 wailian999

df -h;  du -sh *
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbbkouury.html

[R62] 找最占空间的文件
来源：http://dali.zycfv.cn/Article/details/gtnybfniar.html

du -ah . | sort -rh | head -10
来源：http://dali.jinqigufen.top/Article/details/gtkavfxmcp.html

[R63] 内存与进程
来源：http://dali.jinqigfzy.top/Article/details/gtalzvmkwa.html

free -h;  ps aux | grep nginx
来源：http://dali.sysykeji.top/Article/details/gtkzkxybzo.html

[R64] 结束进程
来源：http://dali.jlsjyb.cn/Article/details/gtqaiwauca.html

kill -9 $(pgrep -f app.py)
来源：http://dali.fzhhl.top/Article/details/gthnwjitbg.html

[R65] 查看端口占用
来源：http://dali.ydzc1.top/Article/details/gtsmmfygzs.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.daria6918.cn/Article/details/gtgdgkbrht.html

[R66] 定时任务
来源：http://dali.yonumen.top/Article/details/gtcsmxbapg.html

crontab -e;  crontab -l
来源：http://dali.ehwqpu.com/Article/details/gtgovjtmfb.html

[R67] 生成随机十六进制串
来源：http://dali.yj20258888.top/Article/details/gtuezykfgw.html

openssl rand -hex 16
来源：http://dali.haohaochexian.top/Article/details/gtopoujwec.html

[R68] 计算文件校验值
来源：http://dali.ydzc1.top/Article/details/gtvsihgnqn.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.cheryme.top/Article/details/gtkgiibbvr.html

[R69] 生成随机密码
来源：http://dali.shzxlz.cn/Article/details/gtoesedwir.html

head -c 16 /dev/urandom | base64
来源：http://dali.sysykeji.top/Article/details/gtwasjcfra.html

[R70] 时间戳与互转
来源：http://dali.xuetiantiany.cn/Article/details/gtwyujftvv.html

date +%s;  date -d @1700000000
来源：http://dali.jlsjyb.cn/Article/details/gtxkhrqpwh.html

[R71] 日期格式化
来源：http://dali.sweek.top/Article/details/gtcjawsjdk.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.jiagoushi.top/Article/details/gtgqgcgdsz.html

[R72] 等待端口就绪
来源：http://dali.quarkkingdee.top/Article/details/gtkpyokujv.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.jqgfzy.top/Article/details/gtftnsimbb.html

[R73] 分割大日志
来源：http://dali.hfpthk.cn/Article/details/gtpekyhxkw.html

split -l 1000 big.log part_
来源：http://dali.yj20258888.top/Article/details/gtntlhurrq.html

[R74] 批量重命名
来源：http://dali.fengsongda.top/Article/details/gtqfkpdiwo.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.jinqigfzy.top/Article/details/gttrvcovqt.html

[R75] 导出环境变量
来源：http://dali.wangdashe.top/Article/details/gtgebfrktx.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.chenjidiqi.icu/Article/details/gtvqpysetz.html

[R76] 使用临时文件
来源：http://dali.shangyingyoupin.top/Article/details/gtkppgkmxy.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zycfv.cn/Article/details/gtxxagblrm.html

[R77] 读取用户输入
来源：http://dali.gogol.net.cn/Article/details/gtqruomloa.html

read -rp "请输入: " ans
来源：http://dali.cdnleiting.top/Article/details/gtrswlpuxa.html

[R78] 交互式菜单
来源：http://dali.shanyushiyangtech.top/Article/details/gtwbmtqsyi.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.316326.xyz/Article/details/gtvanvgdmi.html

[R79] 解析命令行选项
来源：http://dali.zhiwuduotai.top/Article/details/gtsoyqbhum.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.xinyue.icu/Article/details/gteyqpvjyh.html

[R80] 查看脚本执行耗时
来源：http://dali.jlsjyb.cn/Article/details/gthmzldgor.html

time ./run.sh
来源：http://dali.nanxuanxn.top/Article/details/gtmdyneizd.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gthnxewlqw.html

S. C / C++ 专题
来源：http://dali.cdnleiting.top/Article/details/gtsiqesxcg.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gteetboxzj.html

[S01] C：Hello World
来源：http://dali.meibo888.top/Article/details/gtymiiczrr.html

#include <stdio.h>
来源：http://dali.sweek.top/Article/details/gtczyhpkvo.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.xziqi.cn/Article/details/gtejfbfxfx.html

[S02] C：变量与格式化输出
来源：http://dali.yueranfly.top/Article/details/gtgiutppsm.html

int a = 10; printf("%d\n", a);
来源：http://dali.bjfxy.top/Article/details/gtglvaxznr.html

[S03] C：读入整数
来源：http://dali.cashguo.top/Article/details/gtulpzfbps.html

int x; scanf("%d", &x);
来源：http://dali.sxryk.cn/Article/details/gtbxjtnpbb.html

[S04] C：字符串复制
来源：http://dali.bjfxy.top/Article/details/gtlfsdgfkq.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.aizwys.cn/Article/details/gtqgvibxer.html

[S05] C：字符串长度
来源：http://dali.quarkkingdee.top/Article/details/gtglbaeqbu.html

strlen(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtwachnwar.html

[S06] C：字符串比较
来源：http://dali.nwbrower.top/Article/details/gtbthmzkyl.html

strcmp(a, b) == 0
来源：http://dali.chenlongwang.top/Article/details/gtdjoukaav.html

[S07] C：数组遍历求和
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoficfdre.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.pycfn.com/Article/details/gtsopizqoj.html

[S08] C：动态内存分配与释放
来源：http://dali.xuanzx.com/Article/details/gtmjsfxwaw.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.andypj.xyz/Article/details/gtiwibheoy.html

[S09] C：结构体定义与初始化
来源：http://dali.xziqi.cn/Article/details/gtnbpisuzn.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.hammf.cn/Article/details/gteizvtvxh.html

[S10] C：指针与解引用
来源：http://dali.gogol.net.cn/Article/details/gtcmqexuqr.html

int *p = &a;  *p = 5;
来源：http://dali.ybcxt.top/Article/details/gtksutehhn.html

[S11] C：逐行读文件
来源：http://dali.zhiwuduotai.top/Article/details/gtyqvsrimx.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.ppjwa.cn/Article/details/gtjoeryilp.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.sweek.top/Article/details/gtkfxwcsya.html

fclose(f);
来源：http://dali.shzxlz.cn/Article/details/gtxaxqvpci.html

[S12] C：写文件
来源：http://dali.daxiang520.top/Article/details/gtejuadevy.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.ehwqpu.com/Article/details/gtqrlxlxoq.html

[S13] C：宏定义
来源：http://dali.chenjidiqi.icu/Article/details/gtqhkunwsw.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.jinqigufen.top/Article/details/gtirdgxymq.html

[S14] C：枚举
来源：http://dali.cucudq.cn/Article/details/gtzaxtgdlf.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.0kj1m.cn/Article/details/gtfvbdudil.html

[S15] C：类型转换
来源：http://dali.jinqigufen.top/Article/details/gtncyzvhjn.html

(double) a / b
来源：http://dali.hnxiangtu.top/Article/details/gtxknwvhfq.html

[S16] C：位操作置位
来源：http://dali.guowangkeji.top/Article/details/gtiyemsppu.html

x |= (1 << 3);
来源：http://dali.nanxinkj.top/Article/details/gtrfjrokld.html

[S17] C：安全拼接字符串
来源：http://dali.redwolf501.top/Article/details/gtsxmnhfnm.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.hnxiangtu.top/Article/details/gtdyusyebp.html

[S18] C：命令行参数
来源：http://dali.quarkkingdee.top/Article/details/gtfkljsbjj.html

int main(int argc, char **argv)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcfaeifia.html

[S19] C：快速排序
来源：http://dali.vqdsnc.cn/Article/details/gtskilgiwt.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.jlsjyb.cn/Article/details/gtrbbyomqw.html

[S20] C：二分查找
来源：http://dali.jqgfzy.top/Article/details/gturqtitpk.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.hywenlv.cn/Article/details/gtaetwijhl.html

[S21] C：字符类别判断
来源：http://dali.zhongyouzk.top/Article/details/gtwjtwdehl.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.gaohongyu789.top/Article/details/gtmfohkery.html

[S22] C：字符串转数字
来源：http://dali.hfpthk.cn/Article/details/gtnubammcf.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhixingplan.top/Article/details/gtacqhpedq.html

[S23] C：随机数
来源：http://dali.redwolf501.top/Article/details/gtrlppsizk.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.cdnleiting.top/Article/details/gtjkouuulq.html

[S24] C：获取本地时间
来源：http://dali.gaohongyu789.top/Article/details/gtojrmpoou.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.svipenyu.cn/Article/details/gttvsamtsw.html

[S25] C：内存拷贝
来源：http://dali.zhongyouzk.top/Article/details/gtfycmgdxd.html

memcpy(dst, src, n);
来源：http://dali.dashuyun.cn/Article/details/gtjxapvnwm.html

[S26] C：内存清零
来源：http://dali.jqgfzy.top/Article/details/gtizseocwf.html

memset(a, 0, sizeof a);
来源：http://dali.hywenlv.cn/Article/details/gtkxhlzebe.html

[S27] C：定义常量
来源：http://dali.jlsjyb.cn/Article/details/gtoezxbcxq.html

const double PI = 3.14159;
来源：http://dali.pengpengdd.cyou/Article/details/gtjcbwqfyc.html

[S28] C：静态变量
来源：http://dali.zhoulong.xyz/Article/details/gtlwjwqquy.html

static int counter = 0;
来源：http://dali.c1oappe.top/Article/details/gtzqdmnvzp.html

[S29] C：变参函数
来源：http://dali.sufxvd.cn/Article/details/gtuhhmclpx.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.guannengcc.top/Article/details/gtkmsqbgkr.html

[S30] C：头文件保护
来源：http://dali.ppjwa.cn/Article/details/gtkozektaj.html

#ifndef X_H
来源：http://dali.yangfankeji.com/Article/details/gtaizorhoj.html

#define X_H
来源：http://dali.cashguo.top/Article/details/gthytdbvtr.html

#endif
来源：http://dali.cashguo.top/Article/details/gtqndkgmgy.html

[S31] C++：Hello World
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqcgurlpn.html

#include <iostream>
来源：http://dali.wangshuangyany.cn/Article/details/gtpeyslnyd.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.aizwys.cn/Article/details/gtiytboiiu.html

[S32] C++：字符串
来源：http://dali.zhengqikj.top/Article/details/gtmpoohowy.html

std::string s = "hi";  s += "!";
来源：http://dali.smart0.xyz/Article/details/gtiasvbhpn.html

[S33] C++：vector 增删
来源：http://dali.hnqzz.top/Article/details/gtnduhdnpg.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.meibo888.top/Article/details/gtencamzpt.html

[S34] C++：遍历 vector
来源：http://dali.c1oappe.top/Article/details/gtyamiggpy.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.gogol.net.cn/Article/details/gtmrhckizt.html

[S35] C++：map
来源：http://dali.cdnleiting.top/Article/details/gtcvqwtave.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.kuanghao11.cn/Article/details/gtdzjrftqq.html

[S36] C++：unordered_map
来源：http://dali.yueranfly.top/Article/details/gtdjfctsyn.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.cashguo.top/Article/details/gtmtdpgjch.html

[S37] C++：set
来源：http://dali.zycfv.cn/Article/details/gtnwvdebok.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.cqqwz.cn/Article/details/gtspqxmgaa.html

[S38] C++：排序
来源：http://dali.jqgfzy.top/Article/details/gtarbcnrbx.html

std::sort(v.begin(), v.end());
来源：http://dali.iojbl.cn/Article/details/gtcloltino.html

[S39] C++：自定义比较器排序
来源：http://dali.birdmap.top/Article/details/gtdvufuenr.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.316326.xyz/Article/details/gtmzvxgzat.html

[S40] C++：查找元素
来源：http://dali.bjfxy.top/Article/details/gtqgagptsf.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.kuanghao11.cn/Article/details/gtqjrorfca.html

[S41] C++：类与构造函数
来源：http://dali.yvedp.cn/Article/details/gtdfwleloh.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.jiagoushi.top/Article/details/gthdjkozfq.html

[S42] C++：继承与虚函数
来源：http://dali.xziqi.cn/Article/details/gtmcmpppqx.html

class B : public Base { public: void f() override {} };
来源：http://dali.jianghu66.top/Article/details/gtodprbkkz.html

[S43] C++：智能指针
来源：http://dali.aibaodan.cn/Article/details/gtqkzcqtot.html

auto p = std::make_unique<int>(5);
来源：http://dali.9152youxi.cn/Article/details/gtxuhgunfd.html

[S44] C++：引用传参
来源：http://dali.0kj1m.cn/Article/details/gtozwylpoh.html

void inc(int &x) { ++x; }
来源：http://dali.gogol.net.cn/Article/details/gtzengufec.html

[S45] C++：lambda
来源：http://dali.chenlongwang.top/Article/details/gtwyxcwugt.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.yueranfly.top/Article/details/gtkygzgahw.html

[S46] C++：函数模板
来源：http://dali.316326.xyz/Article/details/gtrimtzesq.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gtnubssjqy.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhiwuduotai.top/Article/details/gtwrvrcchy.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.aibaodan.cn/Article/details/gtzyqtbund.html

[S48] C++：逐行读文件
来源：http://dali.yongpay.top/Article/details/gtucylfxgf.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.316326.xyz/Article/details/gtsmwdjtuk.html

while (std::getline(in, line)) { }
来源：http://dali.guannengcc.top/Article/details/gtipwopbzc.html

[S49] C++：写文件
来源：http://dali.yanxiufei.cn/Article/details/gthylhpfoy.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgdsqmgvg.html

[S50] C++：格式化数字
来源：http://dali.guannengcc.top/Article/details/gtjeqsngya.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.bjfxy.top/Article/details/gtmaiebzpj.html

[S51] C++：显式类型转换
来源：http://dali.ybcxt.top/Article/details/gtkmnndacg.html

static_cast<double>(a) / b
来源：http://dali.hammf.cn/Article/details/gtkjzqvacn.html

[S52] C++：const 与 noexcept
来源：http://dali.sufxvd.cn/Article/details/gtharilich.html

int size() const noexcept { return n_; }
来源：http://dali.nanxuanxn.top/Article/details/gtytpuvwgo.html

[S53] C++：移动语义
来源：http://dali.sweek.top/Article/details/gtbjftsyai.html

std::vector<int> w = std::move(v);
来源：http://dali.yueranfly.top/Article/details/gtgelhidmg.html

[S54] C++：异常处理
来源：http://dali.hammf.cn/Article/details/gtxekcgjtl.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.yvedp.cn/Article/details/gtsilbviyt.html

[S55] C++：结构化绑定
来源：http://dali.hnqzz.top/Article/details/gtohijfuyc.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.iojbl.cn/Article/details/gtuwdvzwqs.html

[S56] C++：optional
来源：http://dali.316326.xyz/Article/details/gtkrowshiw.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.nwbrower.top/Article/details/gtuoyeagzy.html

[S57] C++：编译期常量
来源：http://dali.jinghuilouyu.cn/Article/details/gthxehpxcp.html

constexpr int N = 10;
来源：http://dali.jqgfzy.top/Article/details/gtbddxycvj.html

[S58] C++：命名空间
来源：http://dali.sxryk.cn/Article/details/gtkzuxditf.html

namespace ns { int f() { return 1; } }
来源：http://dali.zycfv.cn/Article/details/gtorgcxjwb.html

[S59] C++：静态断言
来源：http://dali.jqgfzy.top/Article/details/gtmoojifoc.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.jiagoushi.top/Article/details/gtystgdnfc.html

[S60] C++：遍历并删除元素
来源：http://dali.0kj1m.cn/Article/details/gtxoelecoy.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.smart0.xyz/Article/details/gtybaoinpz.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtwqqhqvnp.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.shanyushiyangtech.top/Article/details/gtnvwvafxd.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtlwrsovgb.html

[T01] Kotlin：Hello World
来源：http://dali.feifeiyinyue.top/Article/details/gtrrsxqkop.html

println("Hello")
来源：http://dali.ybcxt.top/Article/details/gtdjhgutzk.html

[T02] Kotlin：变量
来源：http://dali.aibaodan.cn/Article/details/gteztensvz.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.ybcxt.top/Article/details/gtqbkijgqj.html

[T03] Kotlin：字符串模板
来源：http://dali.gotoacloud.top/Article/details/gtplhrftav.html

"值: $b"
来源：http://dali.xuetiantiany.cn/Article/details/gtvqyvshjz.html

[T04] Kotlin：空安全
来源：http://dali.yanxiufei.cn/Article/details/gtfuvqycga.html

val n: String? = null;  n?.length
来源：http://dali.ydzc1.top/Article/details/gtlwihmgfc.html

[T05] Kotlin：when 表达式
来源：http://dali.snrcjt.cn/Article/details/gttjlgoden.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.mhx1999.top/Article/details/gtlvyimbrq.html

[T06] Kotlin：集合映射
来源：http://dali.jyoumei.cn/Article/details/gtylxoalrm.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.hfpthk.cn/Article/details/gtxyftaxro.html

[T07] Kotlin：集合过滤
来源：http://dali.nwbrower.top/Article/details/gtzfquokwf.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.jinqigufen.top/Article/details/gttwlgnihp.html

[T08] Kotlin：数据类
来源：http://dali.jqgufenzy.top/Article/details/gtyzvnmrdo.html

data class User(val name: String, val age: Int)
来源：http://dali.aibaodan.cn/Article/details/gtqoxgbefn.html

[T09] Kotlin：扩展函数
来源：http://dali.iojbl.cn/Article/details/gtyrdshwbl.html

fun String.exclaim() = this + "!"
来源：http://dali.chenzaomai.com/Article/details/gtigvrunxo.html

[T10] Kotlin：默认参数
来源：http://dali.yj20258.top/Article/details/gtfgtnxfjd.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.nanxuanxn.top/Article/details/gtxvczjzoa.html

[T11] Kotlin：协程
来源：http://dali.hysaishi.cn/Article/details/gtquuanpif.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.ivvv.top/Article/details/gtwicjtggo.html

[T12] Kotlin：解构声明
来源：http://dali.jyoumei.cn/Article/details/gttslgpmun.html

val (a, b) = Pair(1, 2)
来源：http://dali.smart0.xyz/Article/details/gthvcxkeel.html

[T13] Kotlin：只读 Map
来源：http://dali.xuetiantiany.cn/Article/details/gtyylybxhx.html

val m = mapOf("a" to 1)
来源：http://dali.cqqwz.cn/Article/details/gtpaplsrip.html

[T14] Kotlin：循环
来源：http://dali.pengpengdd.cyou/Article/details/gtfzdanmrq.html

for (i in 1..10) println(i)
来源：http://dali.hfpthk.cn/Article/details/gtswmaaplq.html

[T15] Kotlin：接口
来源：http://dali.shzxlz.cn/Article/details/gtcrubbicl.html

interface Shape { fun area(): Double }
来源：http://dali.yongpay.top/Article/details/gtrepvhegv.html

[T16] Swift：Hello World
来源：http://dali.316326.xyz/Article/details/gtsqllcvee.html

print("Hello")
来源：http://dali.guannengcc.top/Article/details/gtjikinccx.html

[T17] Swift：变量与常量
来源：http://dali.zhaomingkeji.xyz/Article/details/gtugxwqqhi.html

var a = 1;  let b = 2
来源：http://dali.hywenlv.cn/Article/details/gtegclyovp.html

[T18] Swift：字符串插值
来源：http://dali.jianghu66.top/Article/details/gtdeelbrfc.html

"值: \(b)"
来源：http://dali.hysaishi.cn/Article/details/gttchqnxyu.html

[T19] Swift：可选绑定
来源：http://dali.pengpengdd.cyou/Article/details/gtgcyftnhf.html

if let n = opt { print(n) }
来源：http://dali.ydzc1.top/Article/details/gtoeuhgglz.html

[T20] Swift：数组操作
来源：http://dali.xinyue.icu/Article/details/gtkpeobelo.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhiwuduotai.top/Article/details/gtpgxhmtxj.html

[T21] Swift：遍历
来源：http://dali.dashuyun.cn/Article/details/gtewcseidk.html

for x in a { print(x) }
来源：http://dali.9152youxi.cn/Article/details/gtqpmfqgnw.html

[T22] Swift：字典
来源：http://dali.yanxiufei.cn/Article/details/gtvrxvoifa.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.jqgufenzy.top/Article/details/gtvttnnkhj.html

[T23] Swift：函数
来源：http://dali.hysaishi.cn/Article/details/gtkxqyioyk.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.9152youxi.cn/Article/details/gtwugkcwzf.html

[T24] Swift：闭包
来源：http://dali.haohaochexian.top/Article/details/gtmknfrply.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.chenzaomai.com/Article/details/gtmmfgrloh.html

[T25] Swift：结构体
来源：http://dali.chenjidiqi.icu/Article/details/gtqsyeriqq.html

struct P { var x: Int }
来源：http://dali.zhengqikj.top/Article/details/gtjxeuxlab.html

[T26] Swift：类与重写
来源：http://dali.fengsongda.top/Article/details/gtlchjjsnd.html

class A: Base { override func f() {} }
来源：http://dali.nanxinkj.top/Article/details/gtgfqzppmj.html

[T27] Swift：错误处理
来源：http://dali.yueranfly.top/Article/details/gtdlmarpue.html

do { try f() } catch { print(error) }
来源：http://dali.nanxuanxn.top/Article/details/gtopochwdv.html

[T28] Swift：枚举
来源：http://dali.daria6918.cn/Article/details/gteubvqofp.html

enum Color { case red, green }
来源：http://dali.tanke756.top/Article/details/gtgmrbewtg.html

[T29] Swift：guard 提前返回
来源：http://dali.smart0.xyz/Article/details/gtxqernpai.html

guard let x = opt else { return }
来源：http://dali.vqdsnc.cn/Article/details/gtdlofytwf.html

[T30] Swift：协议
来源：http://dali.chenjidiqi.icu/Article/details/gtjlqsibok.html

protocol Shape { func area() -> Double }
来源：http://dali.xuanzx.com/Article/details/gtwyqkwsiv.html

[T31] Lua：Hello World
来源：http://dali.c1oappe.top/Article/details/gtwvzvlpes.html

print("Hello")
来源：http://dali.ybcxt.top/Article/details/gtpnmbeilj.html

[T32] Lua：局部变量
来源：http://dali.hnxiangtu.top/Article/details/gtycuiwggb.html

local a = 1
来源：http://dali.yj20258.top/Article/details/gtvulexsgt.html

[T33] Lua：表（数组）
来源：http://dali.chenjidiqi.icu/Article/details/gtwcpuzbiq.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.shanyushiyangkeji.top/Article/details/gthbuqeqfb.html

[T34] Lua：遍历表
来源：http://dali.hnqzz.top/Article/details/gtkritovzn.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.jlsjyb.cn/Article/details/gtdslnjord.html

[T35] Lua：字典表
来源：http://dali.nwbrower.top/Article/details/gttqfgdhde.html

local d = { a = 1 };  d.b = 2
来源：http://dali.nwbrower.top/Article/details/gtoxynrebg.html

[T36] Lua：函数
来源：http://dali.jqgufenzy.top/Article/details/gtizdpurpz.html

function add(a, b) return a + b end
来源：http://dali.gzhubu.top/Article/details/gtytuicrdf.html

[T37] Lua：字符串拼接
来源：http://dali.meibo888.top/Article/details/gtykhyoxej.html

"a" .. "b"
来源：http://dali.pengpengdd.cyou/Article/details/gtwfevuegx.html

[T38] Lua：条件
来源：http://dali.pengpengdd.cyou/Article/details/gtutvmfbno.html

if x > 0 then print("正") end
来源：http://dali.wangshuangyany.cn/Article/details/gtgylwaixs.html

[T39] Lua：模式匹配
来源：http://dali.meibo888.top/Article/details/gtwivecbcy.html

string.find(s, "%d+")
来源：http://dali.zhoulong.xyz/Article/details/gtqimctcph.html

[T40] Lua：元表
来源：http://dali.hnxiangtu.top/Article/details/gtvqbfucdv.html

setmetatable({}, { __index = base })
来源：http://dali.zhixingplan.top/Article/details/gtkqlximkq.html

[T41] Perl：Hello World
来源：http://dali.9152youxi.cn/Article/details/gtnpxathtx.html

print "Hello\n";
来源：http://dali.vqdsnc.cn/Article/details/gteawwiwac.html

[T42] Perl：变量类型
来源：http://dali.cashguo.top/Article/details/gtlupekzhy.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.guowangkeji.top/Article/details/gtcbebbflq.html

[T43] Perl：字符串插值
来源：http://dali.shuidangran.top/Article/details/gtayjtmsik.html

"值: $a"
来源：http://dali.xinyue.icu/Article/details/gtysjxemeu.html

[T44] Perl：条件
来源：http://dali.yj202588.top/Article/details/gtehxcorlk.html

if ($a > 0) { print "正"; }
来源：http://dali.hammf.cn/Article/details/gthgtjurjk.html

[T45] Perl：数组遍历
来源：http://dali.gzhubu.top/Article/details/gtwmyciekc.html

for my $x (@arr) { print $x; }
来源：http://dali.zdqjudy.top/Article/details/gtrhlcnpze.html

[T46] Perl：哈希操作
来源：http://dali.jiagoushi.top/Article/details/gttynqyaik.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.sysykeji.top/Article/details/gtacktoktq.html

[T47] Perl：正则捕获
来源：http://dali.gogol.net.cn/Article/details/gtvatwakve.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.feifeiyinyue.top/Article/details/gtkajwuhvn.html

[T48] Perl：正则替换
来源：http://dali.fengsongda.top/Article/details/gtdwvxxgwj.html

$s =~ s/old/new/g;
来源：http://dali.mhx1999.top/Article/details/gtxugenlzf.html

[T49] Perl：函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqsgemngv.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.cheryme.top/Article/details/gtuvapbusx.html

[T50] Perl：逐行读文件
来源：http://dali.vqdsnc.cn/Article/details/gtlwqumktv.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zdqjudy.top/Article/details/gtzwxrmfws.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.jqgufenzy.top/Article/details/gtlyuuhhvz.html

[T51] Scala：Hello World
来源：http://dali.iojbl.cn/Article/details/gtewezywag.html

println("Hello")
来源：http://dali.yuanzhike.top/Article/details/gtyiphuqgd.html

[T52] Scala：变量
来源：http://dali.cqqwz.cn/Article/details/gtpatglwja.html

val a = 1;  var b = 2
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsfivptus.html

[T53] Scala：字符串插值
来源：http://dali.0kj1m.cn/Article/details/gtbpqupbxo.html

s"值: $b"
来源：http://dali.cashguo.top/Article/details/gtmfsyuesd.html

[T54] Scala：集合映射
来源：http://dali.sysykeji.top/Article/details/gtqibsqvbz.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.hywenlv.cn/Article/details/gtoympqzky.html

[T55] Scala：集合过滤
来源：http://dali.ehwqpu.com/Article/details/gtuorcvdye.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.ydzc1.top/Article/details/gtggiuqyhc.html

[T56] Scala：样例类
来源：http://dali.tian-w.cn/Article/details/gtjzwavkhq.html

case class User(name: String, age: Int)
来源：http://dali.xylfe.cn/Article/details/gtmpqygwsb.html

[T57] Scala：模式匹配
来源：http://dali.svipenyu.cn/Article/details/gthjusfvfm.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.hysaishi.cn/Article/details/gtdqiyxmjn.html

[T58] Scala：函数定义
来源：http://dali.ydzc1.top/Article/details/gtayaislnv.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.chenlongwang.top/Article/details/gtakgxhsdx.html

[T59] Scala：循环
来源：http://dali.fzhhl.top/Article/details/gtmikcsuvz.html

for (i <- 1 to 10) println(i)
来源：http://dali.yvedp.cn/Article/details/gtdsgdpkzj.html

[T60] Scala：折叠
来源：http://dali.zdqjudy.top/Article/details/gtngeefnrj.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhongyouzk.top/Article/details/gtimhmiofc.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtpcqebxvf.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.hywenlv.cn/Article/details/gtvrzkrpcn.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtabgfqqkl.html

[U01] Py：创建虚拟环境
来源：http://dali.shangyingyoupin.top/Article/details/gtuzfgufyf.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.andypj.xyz/Article/details/gtuceorrie.html

[U02] Py：导出 / 安装依赖
来源：http://dali.jinqigfzy.top/Article/details/gtmxkofmcn.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.yvedp.cn/Article/details/gtmttrqleb.html


<!-- 参考信息 -->