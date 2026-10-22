代发 wailian999

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.haohaochexian.top/Article/details/gtfrbexdmb.html

[R60] 只看 HTTP 状态码
来源：http://dali.wangdashe.top/Article/details/gtkhecobub.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.xinyue.icu/Article/details/gtnxcznyqe.html

[R61] 磁盘占用
来源：http://dali.ppjwa.cn/Article/details/gtkjiailhh.html

df -h;  du -sh *
来源：http://dali.jinghuilouyu.cn/Article/details/gthsbxxysc.html

[R62] 找最占空间的文件
来源：http://dali.gzhubu.top/Article/details/gtwplvbocc.html

du -ah . | sort -rh | head -10
来源：http://dali.jqgufenzy.top/Article/details/gtcxoviqlq.html

[R63] 内存与进程
来源：http://dali.yuanzhike.top/Article/details/gtlvulqjrb.html

free -h;  ps aux | grep nginx
来源：http://dali.nanxinkj.top/Article/details/gtgfagmqex.html

[R64] 结束进程
来源：http://dali.smart0.xyz/Article/details/gtfcsnuacm.html

kill -9 $(pgrep -f app.py)
来源：http://dali.xziqi.cn/Article/details/gtztimjtvs.html

[R65] 查看端口占用
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkmbznljs.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.havefunace.top/Article/details/gtuehyxifp.html

[R66] 定时任务
来源：http://dali.aizwys.cn/Article/details/gtcvtslmzi.html

crontab -e;  crontab -l
来源：http://dali.jqgfzy.top/Article/details/gtlkhezmry.html

[R67] 生成随机十六进制串
来源：http://dali.yanxiufei.cn/Article/details/gtsugvjmzv.html

openssl rand -hex 16
来源：http://dali.nanxinkj.top/Article/details/gtejpoireb.html

[R68] 计算文件校验值
来源：http://dali.ybcxt.top/Article/details/gtxkxycjyr.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.cdnleiting.top/Article/details/gtnikfyolp.html

[R69] 生成随机密码
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxrqaxmak.html

head -c 16 /dev/urandom | base64
来源：http://dali.meibo888.top/Article/details/gtbaztzjyu.html

[R70] 时间戳与互转
来源：http://dali.hammf.cn/Article/details/gtbekltxod.html

date +%s;  date -d @1700000000
来源：http://dali.tianlin.xyz/Article/details/gtubjxommq.html

[R71] 日期格式化
来源：http://dali.nwbrower.top/Article/details/gtuehgtykw.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zycfv.cn/Article/details/gtlrcrrocn.html

[R72] 等待端口就绪
来源：http://dali.shanyushiyangtech.top/Article/details/gtqybajscy.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhoulong.xyz/Article/details/gtvfssyoxh.html

[R73] 分割大日志
来源：http://dali.hysaishi.cn/Article/details/gtmjfdcfuh.html

split -l 1000 big.log part_
来源：http://dali.wangdashe.top/Article/details/gteldljypj.html

[R74] 批量重命名
来源：http://dali.redwolf501.top/Article/details/gtyaywwvfh.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.ivvv.top/Article/details/gtldxwqlou.html

[R75] 导出环境变量
来源：http://dali.snrcjt.cn/Article/details/gtclbfjwbk.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqcomgxnf.html

[R76] 使用临时文件
来源：http://dali.yonumen.top/Article/details/gtmrjmkcwh.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zycfv.cn/Article/details/gtkzkurmjt.html

[R77] 读取用户输入
来源：http://dali.gogol.net.cn/Article/details/gtkiusdqjm.html

read -rp "请输入: " ans
来源：http://dali.gaohongyu789.top/Article/details/gtkppgytpq.html

[R78] 交互式菜单
来源：http://dali.yuanzhike.top/Article/details/gtlfffvltb.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.wangshuangyany.cn/Article/details/gtehukhicg.html

[R79] 解析命令行选项
来源：http://dali.daxiang520.top/Article/details/gtfhqclohn.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhiwuduotai.top/Article/details/gtefcyhqbf.html

[R80] 查看脚本执行耗时
来源：http://dali.0kj1m.cn/Article/details/gtbyqetklp.html

time ./run.sh
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxygnjzji.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtgwexqfwd.html

S. C / C++ 专题
来源：http://dali.yj20258.top/Article/details/gtgkoejjrx.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtqjyxompc.html

[S01] C：Hello World
来源：http://dali.daxiang520.top/Article/details/gtvcmefflb.html

#include <stdio.h>
来源：http://dali.andypj.xyz/Article/details/gttgpbyoti.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.xuanzx.com/Article/details/gtyixklozh.html

[S02] C：变量与格式化输出
来源：http://dali.cdnleiting.top/Article/details/gtpnlbfonr.html

int a = 10; printf("%d\n", a);
来源：http://dali.yuxming.cn/Article/details/gtpmcnbofw.html

[S03] C：读入整数
来源：http://dali.hammf.cn/Article/details/gtxmbntpij.html

int x; scanf("%d", &x);
来源：http://dali.yj20258.top/Article/details/gtvxdcrzbz.html

[S04] C：字符串复制
来源：http://dali.dashuyun.cn/Article/details/gtuizukhke.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.gotoacloud.top/Article/details/gtkzcsruxc.html

[S05] C：字符串长度
来源：http://dali.yuxming.cn/Article/details/gtfrnibxpz.html

strlen(s)
来源：http://dali.pengpengdd.cyou/Article/details/gtpmaqmaaf.html

[S06] C：字符串比较
来源：http://dali.cqqwz.cn/Article/details/gtvzyoecgm.html

strcmp(a, b) == 0
来源：http://dali.nanxinkj.top/Article/details/gtvifrnodr.html

[S07] C：数组遍历求和
来源：http://dali.tanke756.top/Article/details/gtcmqyvtrx.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.0kj1m.cn/Article/details/gtfbzcmgeu.html

[S08] C：动态内存分配与释放
来源：http://dali.gaohongyu789.top/Article/details/gtkphkadfl.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.daria6918.cn/Article/details/gtbbpkwlwm.html

[S09] C：结构体定义与初始化
来源：http://dali.quarkkingdee.top/Article/details/gtamprxiaz.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.cashguo.top/Article/details/gtyglqmgax.html

[S10] C：指针与解引用
来源：http://dali.0kj1m.cn/Article/details/gthvymwkdf.html

int *p = &a;  *p = 5;
来源：http://dali.yangfankeji.com/Article/details/gtaxhfdrfv.html

[S11] C：逐行读文件
来源：http://dali.c1oappe.top/Article/details/gtgtqtdmal.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhiwuduotai.top/Article/details/gtxjrjhuyd.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.xziqi.cn/Article/details/gtktypxdyq.html

fclose(f);
来源：http://dali.sufxvd.cn/Article/details/gtyfaoheav.html

[S12] C：写文件
来源：http://dali.chenlongwang.top/Article/details/gthgaxyboi.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.shangyingyoupin.top/Article/details/gtkylntspy.html

[S13] C：宏定义
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzgcilway.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.pengpengdd.cyou/Article/details/gtrajijynw.html

[S14] C：枚举
来源：http://dali.chenjidiqi.icu/Article/details/gtdnmwpcpa.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.sweek.top/Article/details/gtjxfbtdfn.html

[S15] C：类型转换
来源：http://dali.fzhhl.top/Article/details/gthzlzpcaa.html

(double) a / b
来源：http://dali.xylfe.cn/Article/details/gtrwbcsdmm.html

[S16] C：位操作置位
来源：http://dali.ehwqpu.com/Article/details/gthyvtlzuk.html

x |= (1 << 3);
来源：http://dali.sysykeji.top/Article/details/gtjlhbbhou.html

[S17] C：安全拼接字符串
来源：http://dali.0kj1m.cn/Article/details/gttooeeyiv.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.guowangkeji.top/Article/details/gtygxkjchy.html

[S18] C：命令行参数
来源：http://dali.jqgufenzy.top/Article/details/gtnennrwxy.html

int main(int argc, char **argv)
来源：http://dali.iojbl.cn/Article/details/gtuiooaiaq.html

[S19] C：快速排序
来源：http://dali.vqdsnc.cn/Article/details/gtbevinxrq.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.hfpthk.cn/Article/details/gtviptdvea.html

[S20] C：二分查找
来源：http://dali.sweek.top/Article/details/gtqgugjoas.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.redwolf501.top/Article/details/gtfyyuxgfc.html

[S21] C：字符类别判断
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuoftpkkh.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.shzxlz.cn/Article/details/gttgvcycrb.html

[S22] C：字符串转数字
来源：http://dali.yonumen.top/Article/details/gtxspsogtd.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.xylfe.cn/Article/details/gtlhnsgeee.html

[S23] C：随机数
来源：http://dali.0kj1m.cn/Article/details/gtlvmemwbp.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.chenlongwang.top/Article/details/gtocrfhjmn.html

[S24] C：获取本地时间
来源：http://dali.cqqwz.cn/Article/details/gtzpbkbdqg.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.kuanghao11.cn/Article/details/gtiznkgqhi.html

[S25] C：内存拷贝
来源：http://dali.xinyue.icu/Article/details/gtyjfsflka.html

memcpy(dst, src, n);
来源：http://dali.snrcjt.cn/Article/details/gtjnikcyzp.html

[S26] C：内存清零
来源：http://dali.shuidangran.top/Article/details/gtohzmftur.html

memset(a, 0, sizeof a);
来源：http://dali.bjfxy.top/Article/details/gtdkdigjch.html

[S27] C：定义常量
来源：http://dali.yuanzhike.top/Article/details/gttwkopciq.html

const double PI = 3.14159;
来源：http://dali.iojbl.cn/Article/details/gtcdbsukkn.html

[S28] C：静态变量
来源：http://dali.nwbrower.top/Article/details/gtqkuhdngq.html

static int counter = 0;
来源：http://dali.meibo888.top/Article/details/gtsytothhv.html

[S29] C：变参函数
来源：http://dali.yvedp.cn/Article/details/gtatrgvstx.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhiwuduotai.top/Article/details/gtyweluyxm.html

[S30] C：头文件保护
来源：http://dali.zhoulong.xyz/Article/details/gtjubflkod.html

#ifndef X_H
来源：http://dali.birdmap.top/Article/details/gtfspeakrd.html

#define X_H
来源：http://dali.316326.xyz/Article/details/gtymwjqkrr.html

#endif
来源：http://dali.gzhubu.top/Article/details/gthgmokurx.html

[S31] C++：Hello World
来源：http://dali.cucudq.cn/Article/details/gtkozbodse.html

#include <iostream>
来源：http://dali.yangfankeji.com/Article/details/gtxkxiyruq.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.wangshuangyany.cn/Article/details/gtnlhspcok.html

[S32] C++：字符串
来源：http://dali.nwbrower.top/Article/details/gttcsezirf.html

std::string s = "hi";  s += "!";
来源：http://dali.zhiwuduotai.top/Article/details/gtazyqwiid.html

[S33] C++：vector 增删
来源：http://dali.hnxiangtu.top/Article/details/gtepnthdsq.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.aizwys.cn/Article/details/gtmvmiqgdq.html

[S34] C++：遍历 vector
来源：http://dali.gotoacloud.top/Article/details/gtkjmckqpw.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.ivvv.top/Article/details/gtwzjrwiws.html

[S35] C++：map
来源：http://dali.mhx1999.top/Article/details/gtfhhqdcyr.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtawtkjona.html

[S36] C++：unordered_map
来源：http://dali.shuidangran.top/Article/details/gtcwdwkivm.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.shangyingyoupin.top/Article/details/gtynyeriwh.html

[S37] C++：set
来源：http://dali.zhiwuduotai.top/Article/details/gtqkmjtnjj.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.0kj1m.cn/Article/details/gtiklipglw.html

[S38] C++：排序
来源：http://dali.shzxlz.cn/Article/details/gtdvkjxfcj.html

std::sort(v.begin(), v.end());
来源：http://dali.guannengcc.top/Article/details/gtahkqddue.html

[S39] C++：自定义比较器排序
来源：http://dali.kuanghao11.cn/Article/details/gtgpzexyuc.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.chenjidiqi.icu/Article/details/gtqvzcluoj.html

[S40] C++：查找元素
来源：http://dali.gaohongyu789.top/Article/details/gtbxcswiaq.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.pycfn.com/Article/details/gtjrryvrtk.html

[S41] C++：类与构造函数
来源：http://dali.yueranfly.top/Article/details/gtltujgxvk.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.yuanzhike.top/Article/details/gtmkjtgoco.html

[S42] C++：继承与虚函数
来源：http://dali.haohaochexian.top/Article/details/gtlxjlpmju.html

class B : public Base { public: void f() override {} };
来源：http://dali.xuetiantiany.cn/Article/details/gtwbwhoncc.html

[S43] C++：智能指针
来源：http://dali.pengpengdd.cyou/Article/details/gteakyixti.html

auto p = std::make_unique<int>(5);
来源：http://dali.shanyushiyangtech.top/Article/details/gtjjijbupj.html

[S44] C++：引用传参
来源：http://dali.fengsongda.top/Article/details/gtevfuilbr.html

void inc(int &x) { ++x; }
来源：http://dali.gogol.net.cn/Article/details/gtmxsqdvtt.html

[S45] C++：lambda
来源：http://dali.sufxvd.cn/Article/details/gtblvbjwhi.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.xziqi.cn/Article/details/gtbzgpwzcr.html

[S46] C++：函数模板
来源：http://dali.gotoacloud.top/Article/details/gtflyxkpgp.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.sufxvd.cn/Article/details/gtjjpkygyy.html

[S47] C++：结构化绑定遍历
来源：http://dali.kuanghao11.cn/Article/details/gtgrbfsejd.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.yangfankeji.com/Article/details/gtqqouemfk.html

[S48] C++：逐行读文件
来源：http://dali.xuetiantiany.cn/Article/details/gtrsnhcmpd.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.hywenlv.cn/Article/details/gtbybiovex.html

while (std::getline(in, line)) { }
来源：http://dali.sweek.top/Article/details/gtchewdcac.html

[S49] C++：写文件
来源：http://dali.sufxvd.cn/Article/details/gtqsfwzzvf.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.hnqzz.top/Article/details/gttraveqxw.html

[S50] C++：格式化数字
来源：http://dali.chenlongwang.top/Article/details/gtzudvhqfv.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.yj202588.top/Article/details/gttxrcjoqb.html

[S51] C++：显式类型转换
来源：http://dali.tianlin.xyz/Article/details/gtipgcxryn.html

static_cast<double>(a) / b
来源：http://dali.yuxming.cn/Article/details/gtpkgrqnif.html

[S52] C++：const 与 noexcept
来源：http://dali.shanyushiyangtech.top/Article/details/gtegqqakcx.html

int size() const noexcept { return n_; }
来源：http://dali.jqgfzy.top/Article/details/gtdztzdoke.html

[S53] C++：移动语义
来源：http://dali.xuetiantiany.cn/Article/details/gtezpdpdha.html

std::vector<int> w = std::move(v);
来源：http://dali.feifeiyinyue.top/Article/details/gtxxazcirz.html

[S54] C++：异常处理
来源：http://dali.zhaomingkeji.xyz/Article/details/gtruwchpcx.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtslounvca.html

[S55] C++：结构化绑定
来源：http://dali.guannengcc.top/Article/details/gtxwlhczxw.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.nwbrower.top/Article/details/gtsobjzuvv.html

[S56] C++：optional
来源：http://dali.zhiwuduotai.top/Article/details/gtxahnipos.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhiwuduotai.top/Article/details/gtokuwdziq.html

[S57] C++：编译期常量
来源：http://dali.316326.xyz/Article/details/gtrhhutiox.html

constexpr int N = 10;
来源：http://dali.xuetiantiany.cn/Article/details/gtsdvsucjj.html

[S58] C++：命名空间
来源：http://dali.hongshengwenyu.top/Article/details/gtnybqdluz.html

namespace ns { int f() { return 1; } }
来源：http://dali.yanxiufei.cn/Article/details/gthykpkjtk.html

[S59] C++：静态断言
来源：http://dali.iojbl.cn/Article/details/gtmhhoxtjl.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.yangfankeji.com/Article/details/gtqikeknnv.html

[S60] C++：遍历并删除元素
来源：http://dali.guannengcc.top/Article/details/gtxesgecco.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.birdmap.top/Article/details/gtbmmwupao.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtuujuadeb.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.jianghu66.top/Article/details/gtjtowibgm.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtwxommtee.html

[T01] Kotlin：Hello World
来源：http://dali.gzhubu.top/Article/details/gtduybwptq.html

println("Hello")
来源：http://dali.tian-w.cn/Article/details/gtvdwgdfnt.html

[T02] Kotlin：变量
来源：http://dali.ydzc1.top/Article/details/gtvbslypdf.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.hnxiangtu.top/Article/details/gtxvxgtswa.html

[T03] Kotlin：字符串模板
来源：http://dali.cqqwz.cn/Article/details/gthsnoxswt.html

"值: $b"
来源：http://dali.yj20258.top/Article/details/gtazxdelcm.html

[T04] Kotlin：空安全
来源：http://dali.gogol.net.cn/Article/details/gtkmfbkgki.html

val n: String? = null;  n?.length
来源：http://dali.cqqwz.cn/Article/details/gtnhqnfkgn.html

[T05] Kotlin：when 表达式
来源：http://dali.ppjwa.cn/Article/details/gteqsqzfpg.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.jyoumei.cn/Article/details/gtesqproac.html

[T06] Kotlin：集合映射
来源：http://dali.sweek.top/Article/details/gthfswclfb.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhixingplan.top/Article/details/gtolnbstnf.html

[T07] Kotlin：集合过滤
来源：http://dali.havefunace.top/Article/details/gthdglmjly.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.gotoacloud.top/Article/details/gtwwnubwuo.html

[T08] Kotlin：数据类
来源：http://dali.shzxlz.cn/Article/details/gtadwtodwx.html

data class User(val name: String, val age: Int)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzxzxlyvf.html

[T09] Kotlin：扩展函数
来源：http://dali.sweek.top/Article/details/gtmglsdlvq.html

fun String.exclaim() = this + "!"
来源：http://dali.nanxinkj.top/Article/details/gtzselgevn.html

[T10] Kotlin：默认参数
来源：http://dali.hongshengwenyu.top/Article/details/gtgeocznwk.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.ydzc1.top/Article/details/gtkmmwclyr.html

[T11] Kotlin：协程
来源：http://dali.zhoulong.xyz/Article/details/gtnzbgkgly.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.xuetiantiany.cn/Article/details/gtqehamclg.html

[T12] Kotlin：解构声明
来源：http://dali.hongshengwenyu.top/Article/details/gtexsrmaoj.html

val (a, b) = Pair(1, 2)
来源：http://dali.c1oappe.top/Article/details/gtamvtuuar.html

[T13] Kotlin：只读 Map
来源：http://dali.vqdsnc.cn/Article/details/gtmafubigt.html

val m = mapOf("a" to 1)
来源：http://dali.wangdashe.top/Article/details/gtppxfxtkq.html

[T14] Kotlin：循环
来源：http://dali.yonumen.top/Article/details/gtcagmstgs.html

for (i in 1..10) println(i)
来源：http://dali.c1oappe.top/Article/details/gtzfguwbmq.html

[T15] Kotlin：接口
来源：http://dali.wangdashe.top/Article/details/gtzqrxywts.html

interface Shape { fun area(): Double }
来源：http://dali.xziqi.cn/Article/details/gtbshposie.html

[T16] Swift：Hello World
来源：http://dali.chenzaomai.com/Article/details/gtipzhlryw.html

print("Hello")
来源：http://dali.zhoulong.xyz/Article/details/gttgtfdbaq.html

[T17] Swift：变量与常量
来源：http://dali.316326.xyz/Article/details/gtnztblnfg.html

var a = 1;  let b = 2
来源：http://dali.zhiwuduotai.top/Article/details/gtqvgjmmaa.html

[T18] Swift：字符串插值
来源：http://dali.yj20258888.top/Article/details/gtjhswsogq.html

"值: \(b)"
来源：http://dali.cucudq.cn/Article/details/gtakvippve.html

[T19] Swift：可选绑定
来源：http://dali.ybcxt.top/Article/details/gtzpiwnlzn.html

if let n = opt { print(n) }
来源：http://dali.yuxming.cn/Article/details/gtqmpmtaps.html

[T20] Swift：数组操作
来源：http://dali.cdnleiting.top/Article/details/gtfiumqgdo.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.ivvv.top/Article/details/gttuuxhbee.html

[T21] Swift：遍历
来源：http://dali.yuxming.cn/Article/details/gtqzxwfdty.html

for x in a { print(x) }
来源：http://dali.hammf.cn/Article/details/gtdsesuzuy.html

[T22] Swift：字典
来源：http://dali.pengpengdd.cyou/Article/details/gtkcmyvpfr.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.iojbl.cn/Article/details/gttundldwb.html

[T23] Swift：函数
来源：http://dali.chenzaomai.com/Article/details/gtxvweldou.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.iojbl.cn/Article/details/gtcoxcoajy.html

[T24] Swift：闭包
来源：http://dali.hammf.cn/Article/details/gtliwglnon.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.ppjwa.cn/Article/details/gtybrjnbuh.html

[T25] Swift：结构体
来源：http://dali.ehwqpu.com/Article/details/gtbwkadfwz.html

struct P { var x: Int }
来源：http://dali.ybcxt.top/Article/details/gtmeowvscz.html

[T26] Swift：类与重写
来源：http://dali.zhixingplan.top/Article/details/gtnylsdorf.html

class A: Base { override func f() {} }
来源：http://dali.zycfv.cn/Article/details/gtixyiegtb.html

[T27] Swift：错误处理
来源：http://dali.yueranfly.top/Article/details/gtslofkkqq.html

do { try f() } catch { print(error) }
来源：http://dali.daxiang520.top/Article/details/gthyilxksm.html

[T28] Swift：枚举
来源：http://dali.jinqigufen.top/Article/details/gtrhhnmaho.html

enum Color { case red, green }
来源：http://dali.guowangkeji.top/Article/details/gtfllsfohy.html

[T29] Swift：guard 提前返回
来源：http://dali.zdqjudy.top/Article/details/gtuyydislf.html

guard let x = opt else { return }
来源：http://dali.guannengcc.top/Article/details/gtmguexrgf.html

[T30] Swift：协议
来源：http://dali.yangfankeji.com/Article/details/gtqoooertr.html

protocol Shape { func area() -> Double }
来源：http://dali.shuidangran.top/Article/details/gtvagmoeei.html

[T31] Lua：Hello World
来源：http://dali.0kj1m.cn/Article/details/gtpmejnlxx.html

print("Hello")
来源：http://dali.tianlin.xyz/Article/details/gtnilgyjoq.html

[T32] Lua：局部变量
来源：http://dali.yj202588.top/Article/details/gtcfwyaiju.html

local a = 1
来源：http://dali.chenjidiqi.icu/Article/details/gtxhrgyyer.html

[T33] Lua：表（数组）
来源：http://dali.yvedp.cn/Article/details/gtbvqssdlb.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.yj20258.top/Article/details/gtveshnymr.html

[T34] Lua：遍历表
来源：http://dali.xinyue.icu/Article/details/gtccejqvgm.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.wangshuangyany.cn/Article/details/gtvmaqxidl.html

[T35] Lua：字典表
来源：http://dali.sysykeji.top/Article/details/gtsmtmhcwl.html

local d = { a = 1 };  d.b = 2
来源：http://dali.sxryk.cn/Article/details/gtlhkzoyac.html

[T36] Lua：函数
来源：http://dali.quarkkingdee.top/Article/details/gttiyjitza.html

function add(a, b) return a + b end
来源：http://dali.yuanzhike.top/Article/details/gtulpwjmyd.html

[T37] Lua：字符串拼接
来源：http://dali.svipenyu.cn/Article/details/gtwtjnyxfu.html

"a" .. "b"
来源：http://dali.jyoumei.cn/Article/details/gtkheoukhn.html

[T38] Lua：条件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfupgwpkv.html

if x > 0 then print("正") end
来源：http://dali.fengsongda.top/Article/details/gtklhnzulj.html

[T39] Lua：模式匹配
来源：http://dali.cdnleiting.top/Article/details/gtjbutjovs.html

string.find(s, "%d+")
来源：http://dali.pycfn.com/Article/details/gtcfkswgob.html

[T40] Lua：元表
来源：http://dali.guowangkeji.top/Article/details/gtmvokfqgw.html

setmetatable({}, { __index = base })
来源：http://dali.sxryk.cn/Article/details/gtfztpfwtn.html

[T41] Perl：Hello World
来源：http://dali.cashguo.top/Article/details/gtpcnqaxdv.html

print "Hello\n";
来源：http://dali.cashguo.top/Article/details/gtdxgejxul.html

[T42] Perl：变量类型
来源：http://dali.tian-w.cn/Article/details/gttlkjxnkb.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.xinyue.icu/Article/details/gtzdaitocy.html

[T43] Perl：字符串插值
来源：http://dali.zhoulong.xyz/Article/details/gtvvufhsou.html

"值: $a"
来源：http://dali.daria6918.cn/Article/details/gtofqhmuzy.html

[T44] Perl：条件
来源：http://dali.cheryme.top/Article/details/gthaqulyck.html

if ($a > 0) { print "正"; }
来源：http://dali.yvedp.cn/Article/details/gtdxobzhdt.html

[T45] Perl：数组遍历
来源：http://dali.ehwqpu.com/Article/details/gtozaciwsg.html

for my $x (@arr) { print $x; }
来源：http://dali.ppjwa.cn/Article/details/gtllapxyzm.html

[T46] Perl：哈希操作
来源：http://dali.zhixingplan.top/Article/details/gtvwjlkrye.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.jianghu66.top/Article/details/gtjxksseyh.html

[T47] Perl：正则捕获
来源：http://dali.zhongyouzk.top/Article/details/gtyfugbvbh.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtcvkuzjdf.html

[T48] Perl：正则替换
来源：http://dali.xuetiantiany.cn/Article/details/gtsmydhncz.html

$s =~ s/old/new/g;
来源：http://dali.jinyuanbaomall.cn/Article/details/gthgtdazpf.html

[T49] Perl：函数
来源：http://dali.nanxinkj.top/Article/details/gtqdbsuokn.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.aizwys.cn/Article/details/gtrjyallxw.html

[T50] Perl：逐行读文件
来源：http://dali.c1oappe.top/Article/details/gtflznykco.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.xinyue.icu/Article/details/gtpfxjlfhc.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.jinqigufen.top/Article/details/gtzkbaupua.html

[T51] Scala：Hello World
来源：http://dali.daxiang520.top/Article/details/gtklcmadjf.html

println("Hello")
来源：http://dali.zycfv.cn/Article/details/gtbznyfpwc.html

[T52] Scala：变量
来源：http://dali.jinghuilouyu.cn/Article/details/gtfsrwiubv.html

val a = 1;  var b = 2
来源：http://dali.feifeiyinyue.top/Article/details/gtmgyyktuf.html

[T53] Scala：字符串插值
来源：http://dali.tianlin.xyz/Article/details/gtltzqzpkh.html

s"值: $b"
来源：http://dali.jyoumei.cn/Article/details/gtshzzvqfg.html

[T54] Scala：集合映射
来源：http://dali.bjfxy.top/Article/details/gtcspyzsvv.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.vqdsnc.cn/Article/details/gtfkwmbwea.html

[T55] Scala：集合过滤
来源：http://dali.guowangkeji.top/Article/details/gtanyjozau.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.nanxinkj.top/Article/details/gtdskdjrhf.html

[T56] Scala：样例类
来源：http://dali.ydzc1.top/Article/details/gtfrpjmhrv.html

case class User(name: String, age: Int)
来源：http://dali.hywenlv.cn/Article/details/gtnyrlrscc.html

[T57] Scala：模式匹配
来源：http://dali.birdmap.top/Article/details/gtqboujxvi.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.aizwys.cn/Article/details/gtqabctbdq.html

[T58] Scala：函数定义
来源：http://dali.aibaodan.cn/Article/details/gtdngguekd.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.daxiang520.top/Article/details/gtpszyjwak.html

[T59] Scala：循环
来源：http://dali.hysaishi.cn/Article/details/gtrkwwtaue.html

for (i <- 1 to 10) println(i)
来源：http://dali.xuanzx.com/Article/details/gticaxncfs.html

[T60] Scala：折叠
来源：http://dali.vqdsnc.cn/Article/details/gtlziwojcr.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.316326.xyz/Article/details/gtojywtzoa.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gthuracwmt.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.chenlongwang.top/Article/details/gtuzihqdpu.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtkqvmdord.html


<!-- 参考信息 -->