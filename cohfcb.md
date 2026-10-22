代发 wailian999

free -h;  ps aux | grep nginx
来源：http://dali.gogol.net.cn/Article/details/gttnzxqbwk.html

[R64] 结束进程
来源：http://dali.yanxiufei.cn/Article/details/gtaxshyvms.html

kill -9 $(pgrep -f app.py)
来源：http://dali.hywenlv.cn/Article/details/gtaesqkhlu.html

[R65] 查看端口占用
来源：http://dali.guannengcc.top/Article/details/gtivrvnczy.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.xuetiantiany.cn/Article/details/gtkllixtjl.html

[R66] 定时任务
来源：http://dali.nwbrower.top/Article/details/gtmofmeffu.html

crontab -e;  crontab -l
来源：http://dali.bjfxy.top/Article/details/gteleyknad.html

[R67] 生成随机十六进制串
来源：http://dali.yanxiufei.cn/Article/details/gtzzuteonk.html

openssl rand -hex 16
来源：http://dali.gogol.net.cn/Article/details/gtvwriolmr.html

[R68] 计算文件校验值
来源：http://dali.daria6918.cn/Article/details/gtakmsheuu.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.iojbl.cn/Article/details/gtkripekfs.html

[R69] 生成随机密码
来源：http://dali.ehwqpu.com/Article/details/gthqjsyieu.html

head -c 16 /dev/urandom | base64
来源：http://dali.yuxming.cn/Article/details/gtyggdhroe.html

[R70] 时间戳与互转
来源：http://dali.fzhhl.top/Article/details/gtbxmpsjkt.html

date +%s;  date -d @1700000000
来源：http://dali.guannengcc.top/Article/details/gtenelxmyx.html

[R71] 日期格式化
来源：http://dali.9152youxi.cn/Article/details/gtvrsqcxxb.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.redwolf501.top/Article/details/gtrzxtiwxp.html

[R72] 等待端口就绪
来源：http://dali.hnqzz.top/Article/details/gtjpkwhptn.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.gogol.net.cn/Article/details/gtlbazkltj.html

[R73] 分割大日志
来源：http://dali.daxiang520.top/Article/details/gtsnynvzhf.html

split -l 1000 big.log part_
来源：http://dali.yj202588.top/Article/details/gtiqatjaym.html

[R74] 批量重命名
来源：http://dali.yongpay.top/Article/details/gtsgugoitg.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zycfv.cn/Article/details/gtznhfibef.html

[R75] 导出环境变量
来源：http://dali.redwolf501.top/Article/details/gtsrxzcutk.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.feifeiyinyue.top/Article/details/gtvbdcljte.html

[R76] 使用临时文件
来源：http://dali.iojbl.cn/Article/details/gteyrqtwei.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.chenzaomai.com/Article/details/gtlbpfrwml.html

[R77] 读取用户输入
来源：http://dali.zdqjudy.top/Article/details/gtrxdhzlly.html

read -rp "请输入: " ans
来源：http://dali.feifeiyinyue.top/Article/details/gtyzzwytat.html

[R78] 交互式菜单
来源：http://dali.xinyue.icu/Article/details/gtdsfujnrv.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.cdnleiting.top/Article/details/gtoicvrawl.html

[R79] 解析命令行选项
来源：http://dali.jqgufenzy.top/Article/details/gtstirfdyr.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.nanxinkj.top/Article/details/gtgtyzfhge.html

[R80] 查看脚本执行耗时
来源：http://dali.redwolf501.top/Article/details/gtppkklfqs.html

time ./run.sh
来源：http://dali.andypj.xyz/Article/details/gtjqwtjwtz.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtflfqbgim.html

S. C / C++ 专题
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpgtgtebw.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtychgveky.html

[S01] C：Hello World
来源：http://dali.c1oappe.top/Article/details/gtmkgrbjzt.html

#include <stdio.h>
来源：http://dali.hywenlv.cn/Article/details/gthyhhzrqk.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.yangfankeji.com/Article/details/gtlevhaqxn.html

[S02] C：变量与格式化输出
来源：http://dali.shangyingyoupin.top/Article/details/gtyuwnhlje.html

int a = 10; printf("%d\n", a);
来源：http://dali.mhx1999.top/Article/details/gtqzezeyhq.html

[S03] C：读入整数
来源：http://dali.zhoulong.xyz/Article/details/gtfjavwpxw.html

int x; scanf("%d", &x);
来源：http://dali.jqgufenzy.top/Article/details/gtolbeqdsq.html

[S04] C：字符串复制
来源：http://dali.cashguo.top/Article/details/gtvajatrjs.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.yuanzhike.top/Article/details/gtadpqxjag.html

[S05] C：字符串长度
来源：http://dali.xylfe.cn/Article/details/gtrxotkmec.html

strlen(s)
来源：http://dali.zdqjudy.top/Article/details/gtqzstzlie.html

[S06] C：字符串比较
来源：http://dali.ehwqpu.com/Article/details/gtjtdwhmzk.html

strcmp(a, b) == 0
来源：http://dali.smart0.xyz/Article/details/gtzcjwxbmj.html

[S07] C：数组遍历求和
来源：http://dali.tian-w.cn/Article/details/gthxutohzf.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.ivvv.top/Article/details/gtfeamqtcu.html

[S08] C：动态内存分配与释放
来源：http://dali.snrcjt.cn/Article/details/gtyaqqmjug.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.gotoacloud.top/Article/details/gtjjkzyqmn.html

[S09] C：结构体定义与初始化
来源：http://dali.xylfe.cn/Article/details/gtounxdrmq.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.jinghuilouyu.cn/Article/details/gtpjqkzyxq.html

[S10] C：指针与解引用
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsvongkbu.html

int *p = &a;  *p = 5;
来源：http://dali.xinyue.icu/Article/details/gtdipbgxdq.html

[S11] C：逐行读文件
来源：http://dali.jianghu66.top/Article/details/gtgtrlrmjm.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.yuxming.cn/Article/details/gtxzhjsrsl.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.wangshuangyany.cn/Article/details/gtnjryadzy.html

fclose(f);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiifvzlra.html

[S12] C：写文件
来源：http://dali.nanxinkj.top/Article/details/gtfbxarsag.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.havefunace.top/Article/details/gtozkqhmiu.html

[S13] C：宏定义
来源：http://dali.xylfe.cn/Article/details/gtwbkcpskg.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.wangdashe.top/Article/details/gtqjydpsup.html

[S14] C：枚举
来源：http://dali.redwolf501.top/Article/details/gtpaiyfmgh.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.hysaishi.cn/Article/details/gtshfipzqq.html

[S15] C：类型转换
来源：http://dali.zhiwuduotai.top/Article/details/gthtkngzru.html

(double) a / b
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnkdnoflr.html

[S16] C：位操作置位
来源：http://dali.daxiang520.top/Article/details/gtvgecftpg.html

x |= (1 << 3);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvnddxwwr.html

[S17] C：安全拼接字符串
来源：http://dali.gogol.net.cn/Article/details/gtodvyocwz.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.cucudq.cn/Article/details/gtnaatgjqp.html

[S18] C：命令行参数
来源：http://dali.pycfn.com/Article/details/gtlqyfvnre.html

int main(int argc, char **argv)
来源：http://dali.hongshengwenyu.top/Article/details/gtqoxshlqj.html

[S19] C：快速排序
来源：http://dali.daxiang520.top/Article/details/gtgwtpqjkm.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.daxiang520.top/Article/details/gtnhsurcpk.html

[S20] C：二分查找
来源：http://dali.feifeiyinyue.top/Article/details/gthguvdauf.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.nanxinkj.top/Article/details/gtvzqhlkkv.html

[S21] C：字符类别判断
来源：http://dali.sufxvd.cn/Article/details/gtmkykviae.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.shangyingyoupin.top/Article/details/gtfsvczwaq.html

[S22] C：字符串转数字
来源：http://dali.ivvv.top/Article/details/gtjkmlehpg.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.jqgfzy.top/Article/details/gthnbpydzc.html

[S23] C：随机数
来源：http://dali.iojbl.cn/Article/details/gtggjgkvbg.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.birdmap.top/Article/details/gtwohbrxye.html

[S24] C：获取本地时间
来源：http://dali.sxryk.cn/Article/details/gterqaukik.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.yj202588.top/Article/details/gtcacljgtp.html

[S25] C：内存拷贝
来源：http://dali.sufxvd.cn/Article/details/gtrwetfrgp.html

memcpy(dst, src, n);
来源：http://dali.smart0.xyz/Article/details/gtqfgbicpa.html

[S26] C：内存清零
来源：http://dali.ivvv.top/Article/details/gthxppfpik.html

memset(a, 0, sizeof a);
来源：http://dali.quarkkingdee.top/Article/details/gtvmtrryhf.html

[S27] C：定义常量
来源：http://dali.yangfankeji.com/Article/details/gtpjrkmkem.html

const double PI = 3.14159;
来源：http://dali.vqdsnc.cn/Article/details/gtlbmsnhnj.html

[S28] C：静态变量
来源：http://dali.chenzaomai.com/Article/details/gtwddhsbye.html

static int counter = 0;
来源：http://dali.shzxlz.cn/Article/details/gtspsgzoyo.html

[S29] C：变参函数
来源：http://dali.yonumen.top/Article/details/gtwnaarahi.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhixingplan.top/Article/details/gtrautdiws.html

[S30] C：头文件保护
来源：http://dali.snrcjt.cn/Article/details/gtaztrffrf.html

#ifndef X_H
来源：http://dali.hywenlv.cn/Article/details/gtnozepozv.html

#define X_H
来源：http://dali.daxiang520.top/Article/details/gtdsraxnzl.html

#endif
来源：http://dali.yongpay.top/Article/details/gtpntaynys.html

[S31] C++：Hello World
来源：http://dali.xziqi.cn/Article/details/gtqvqiawrd.html

#include <iostream>
来源：http://dali.hongshengwenyu.top/Article/details/gtqxykjvis.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.nanxuanxn.top/Article/details/gtoexibqvr.html

[S32] C++：字符串
来源：http://dali.ivvv.top/Article/details/gtdocfbmwv.html

std::string s = "hi";  s += "!";
来源：http://dali.tianlin.xyz/Article/details/gtsjlbhwhc.html

[S33] C++：vector 增删
来源：http://dali.xuanzx.com/Article/details/gtnzwekrvp.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.yj202588.top/Article/details/gttcgfsfub.html

[S34] C++：遍历 vector
来源：http://dali.jlsjyb.cn/Article/details/gtcxbuedhp.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.havefunace.top/Article/details/gtnuefessb.html

[S35] C++：map
来源：http://dali.yangfankeji.com/Article/details/gtmgmpaqed.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.wangshuangyany.cn/Article/details/gtiajohmhb.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gtdegqrufg.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jiagoushi.top/Article/details/gtmogkzcdf.html

[S37] C++：set
来源：http://dali.0kj1m.cn/Article/details/gtmihsyost.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.jiagoushi.top/Article/details/gtfyhiolae.html

[S38] C++：排序
来源：http://dali.yj20258888.top/Article/details/gtfkyntafq.html

std::sort(v.begin(), v.end());
来源：http://dali.0kj1m.cn/Article/details/gtgpmkimmu.html

[S39] C++：自定义比较器排序
来源：http://dali.yonumen.top/Article/details/gtdrhpeaxs.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.yonumen.top/Article/details/gtfrmvutan.html

[S40] C++：查找元素
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqsmoklce.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.cucudq.cn/Article/details/gtuityxqrv.html

[S41] C++：类与构造函数
来源：http://dali.kuanghao11.cn/Article/details/gtjjnzbcwb.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.jlsjyb.cn/Article/details/gtgufpityz.html

[S42] C++：继承与虚函数
来源：http://dali.zdqjudy.top/Article/details/gttrddnlmf.html

class B : public Base { public: void f() override {} };
来源：http://dali.xuetiantiany.cn/Article/details/gtybjjzikp.html

[S43] C++：智能指针
来源：http://dali.jianghu66.top/Article/details/gtcnndfbtb.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhoulong.xyz/Article/details/gtnprxqezo.html

[S44] C++：引用传参
来源：http://dali.jiagoushi.top/Article/details/gtawmmhdrj.html

void inc(int &x) { ++x; }
来源：http://dali.iojbl.cn/Article/details/gtkbyzxltp.html

[S45] C++：lambda
来源：http://dali.chenlongwang.top/Article/details/gtjftcgiat.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.jlsjyb.cn/Article/details/gtsgqmejvj.html

[S46] C++：函数模板
来源：http://dali.chenjidiqi.icu/Article/details/gtzbjsbhgi.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.redwolf501.top/Article/details/gtrguwqfyt.html

[S47] C++：结构化绑定遍历
来源：http://dali.yj20258888.top/Article/details/gtwbzyclni.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.yj20258.top/Article/details/gtiincizkt.html

[S48] C++：逐行读文件
来源：http://dali.cucudq.cn/Article/details/gtjxdytfsb.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.hysaishi.cn/Article/details/gtqoyisfgp.html

while (std::getline(in, line)) { }
来源：http://dali.cheryme.top/Article/details/gtfrbuhyrm.html

[S49] C++：写文件
来源：http://dali.yvedp.cn/Article/details/gtlhbzztdf.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.ybcxt.top/Article/details/gtmajbiodc.html

[S50] C++：格式化数字
来源：http://dali.yvedp.cn/Article/details/gtmnxrgrrn.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.sufxvd.cn/Article/details/gtzuxwdnpg.html

[S51] C++：显式类型转换
来源：http://dali.pengpengdd.cyou/Article/details/gtxciqnpyr.html

static_cast<double>(a) / b
来源：http://dali.ivvv.top/Article/details/gttsxotnjf.html

[S52] C++：const 与 noexcept
来源：http://dali.gzhubu.top/Article/details/gtzmuqgnsf.html

int size() const noexcept { return n_; }
来源：http://dali.meibo888.top/Article/details/gtrfgnfcsf.html

[S53] C++：移动语义
来源：http://dali.zhiwuduotai.top/Article/details/gtckovgumg.html

std::vector<int> w = std::move(v);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfknqophw.html

[S54] C++：异常处理
来源：http://dali.snrcjt.cn/Article/details/gtawdannan.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.0kj1m.cn/Article/details/gtellqzexz.html

[S55] C++：结构化绑定
来源：http://dali.redwolf501.top/Article/details/gtkyatmxnd.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.hnxiangtu.top/Article/details/gtwftausjt.html

[S56] C++：optional
来源：http://dali.yueranfly.top/Article/details/gtsqsjmlfb.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.jlsjyb.cn/Article/details/gtsqyjcjvh.html

[S57] C++：编译期常量
来源：http://dali.nanxuanxn.top/Article/details/gtcnzyeyrw.html

constexpr int N = 10;
来源：http://dali.cdnleiting.top/Article/details/gtfrrolusd.html

[S58] C++：命名空间
来源：http://dali.sufxvd.cn/Article/details/gtkgpooepl.html

namespace ns { int f() { return 1; } }
来源：http://dali.iojbl.cn/Article/details/gtxlbokgkr.html

[S59] C++：静态断言
来源：http://dali.ivvv.top/Article/details/gtbookplvd.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.andypj.xyz/Article/details/gtevkwwgiy.html

[S60] C++：遍历并删除元素
来源：http://dali.zdqjudy.top/Article/details/gtgagbsjcd.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.nwbrower.top/Article/details/gtmwofvzhs.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtbxwzufra.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.jinqigufen.top/Article/details/gtqkzdkoyq.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtaouvoozb.html

[T01] Kotlin：Hello World
来源：http://dali.cdnleiting.top/Article/details/gtaozpmhew.html

println("Hello")
来源：http://dali.havefunace.top/Article/details/gtizxrpfwo.html

[T02] Kotlin：变量
来源：http://dali.gzhubu.top/Article/details/gtfielrtsg.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.ppjwa.cn/Article/details/gttjsgwnzf.html

[T03] Kotlin：字符串模板
来源：http://dali.tianlin.xyz/Article/details/gtkchhrpjj.html

"值: $b"
来源：http://dali.daxiang520.top/Article/details/gtdjneckxp.html

[T04] Kotlin：空安全
来源：http://dali.zhiwuduotai.top/Article/details/gtjdbinoik.html

val n: String? = null;  n?.length
来源：http://dali.c1oappe.top/Article/details/gtsvlwcbpe.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gtrlrfqfdf.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.meibo888.top/Article/details/gtlgbbsrxe.html

[T06] Kotlin：集合映射
来源：http://dali.nwbrower.top/Article/details/gtrjzwvpts.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.ehwqpu.com/Article/details/gtbutmlfby.html

[T07] Kotlin：集合过滤
来源：http://dali.ybcxt.top/Article/details/gtzvtizrci.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.jlsjyb.cn/Article/details/gtyktoyjdu.html

[T08] Kotlin：数据类
来源：http://dali.ivvv.top/Article/details/gtqeybuhzx.html

data class User(val name: String, val age: Int)
来源：http://dali.chenlongwang.top/Article/details/gtzrfspdky.html

[T09] Kotlin：扩展函数
来源：http://dali.xylfe.cn/Article/details/gtprxjcpdt.html

fun String.exclaim() = this + "!"
来源：http://dali.c1oappe.top/Article/details/gtkilksvdg.html

[T10] Kotlin：默认参数
来源：http://dali.chenjidiqi.icu/Article/details/gtsvwjvsfd.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.bjfxy.top/Article/details/gtqzdtpmsr.html

[T11] Kotlin：协程
来源：http://dali.cqqwz.cn/Article/details/gtlcfqqhkm.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.hammf.cn/Article/details/gtlnskyyxx.html

[T12] Kotlin：解构声明
来源：http://dali.shzxlz.cn/Article/details/gtgrhqeelc.html

val (a, b) = Pair(1, 2)
来源：http://dali.chenzaomai.com/Article/details/gthaztdduw.html

[T13] Kotlin：只读 Map
来源：http://dali.yj20258888.top/Article/details/gtjinofcrj.html

val m = mapOf("a" to 1)
来源：http://dali.yanxiufei.cn/Article/details/gtntgntpsp.html

[T14] Kotlin：循环
来源：http://dali.yongpay.top/Article/details/gtsuidubqo.html

for (i in 1..10) println(i)
来源：http://dali.redwolf501.top/Article/details/gtyooidhab.html

[T15] Kotlin：接口
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdngfocgu.html

interface Shape { fun area(): Double }
来源：http://dali.zhoulong.xyz/Article/details/gtqykzhlul.html

[T16] Swift：Hello World
来源：http://dali.nwbrower.top/Article/details/gtxtvfdjqb.html

print("Hello")
来源：http://dali.yj20258.top/Article/details/gtasrhhxzi.html

[T17] Swift：变量与常量
来源：http://dali.feifeiyinyue.top/Article/details/gtzoyzlagr.html

var a = 1;  let b = 2
来源：http://dali.kuanghao11.cn/Article/details/gtzkavqiyk.html

[T18] Swift：字符串插值
来源：http://dali.yonumen.top/Article/details/gtlptzrdyv.html

"值: \(b)"
来源：http://dali.jinqigfzy.top/Article/details/gtlgnsqgpz.html

[T19] Swift：可选绑定
来源：http://dali.gaohongyu789.top/Article/details/gtpbmyhcmm.html

if let n = opt { print(n) }
来源：http://dali.cashguo.top/Article/details/gtoipdnudw.html

[T20] Swift：数组操作
来源：http://dali.zhixingplan.top/Article/details/gtwnebswhe.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.jqgfzy.top/Article/details/gtsoayogsr.html

[T21] Swift：遍历
来源：http://dali.ppjwa.cn/Article/details/gtkttczrlh.html

for x in a { print(x) }
来源：http://dali.yangfankeji.com/Article/details/gtzbfvuxbk.html

[T22] Swift：字典
来源：http://dali.zhongyouzk.top/Article/details/gtthapslfk.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.dashuyun.cn/Article/details/gthfkmyucs.html

[T23] Swift：函数
来源：http://dali.316326.xyz/Article/details/gtjiwyyamq.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.redwolf501.top/Article/details/gttylnbpqh.html

[T24] Swift：闭包
来源：http://dali.hysaishi.cn/Article/details/gtjyeohkct.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.gaohongyu789.top/Article/details/gtxyaxccxl.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gtjinceubh.html

struct P { var x: Int }
来源：http://dali.yuxming.cn/Article/details/gthhketjfn.html

[T26] Swift：类与重写
来源：http://dali.shangyingyoupin.top/Article/details/gtcbqqezhj.html

class A: Base { override func f() {} }
来源：http://dali.sweek.top/Article/details/gtvzbfxhes.html

[T27] Swift：错误处理
来源：http://dali.fzhhl.top/Article/details/gtfgutqrik.html

do { try f() } catch { print(error) }
来源：http://dali.jinqigfzy.top/Article/details/gtotjeqonh.html

[T28] Swift：枚举
来源：http://dali.aizwys.cn/Article/details/gtclhsfshy.html

enum Color { case red, green }
来源：http://dali.c1oappe.top/Article/details/gtncezhbcc.html

[T29] Swift：guard 提前返回
来源：http://dali.jinghuilouyu.cn/Article/details/gtxdfndjlq.html

guard let x = opt else { return }
来源：http://dali.hysaishi.cn/Article/details/gtyfdmxlqn.html

[T30] Swift：协议
来源：http://dali.xziqi.cn/Article/details/gtfuruajkn.html

protocol Shape { func area() -> Double }
来源：http://dali.sxryk.cn/Article/details/gtmofonnbf.html

[T31] Lua：Hello World
来源：http://dali.yuxming.cn/Article/details/gtpqlcpnjj.html

print("Hello")
来源：http://dali.jlsjyb.cn/Article/details/gtyymgehih.html

[T32] Lua：局部变量
来源：http://dali.guannengcc.top/Article/details/gtqowuspcl.html

local a = 1
来源：http://dali.yueranfly.top/Article/details/gtoktjjcle.html

[T33] Lua：表（数组）
来源：http://dali.daria6918.cn/Article/details/gtmpbtlxty.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.shzxlz.cn/Article/details/gtnypaknqn.html

[T34] Lua：遍历表
来源：http://dali.zycfv.cn/Article/details/gtbqneztkw.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.sxryk.cn/Article/details/gtvoskulcm.html

[T35] Lua：字典表
来源：http://dali.yj20258888.top/Article/details/gtfwmvgcym.html

local d = { a = 1 };  d.b = 2
来源：http://dali.haohaochexian.top/Article/details/gtprhrljqn.html

[T36] Lua：函数
来源：http://dali.zhoulong.xyz/Article/details/gtsdrpuxcb.html

function add(a, b) return a + b end
来源：http://dali.ivvv.top/Article/details/gtekkizehj.html

[T37] Lua：字符串拼接
来源：http://dali.jqgfzy.top/Article/details/gtbcemydlo.html

"a" .. "b"
来源：http://dali.yj202588.top/Article/details/gtpkinrnvg.html

[T38] Lua：条件
来源：http://dali.tian-w.cn/Article/details/gtjgsgdfdm.html

if x > 0 then print("正") end
来源：http://dali.zdqjudy.top/Article/details/gtghbbutzq.html

[T39] Lua：模式匹配
来源：http://dali.aizwys.cn/Article/details/gtqkkemylk.html

string.find(s, "%d+")
来源：http://dali.ybcxt.top/Article/details/gtrokjmpqq.html

[T40] Lua：元表
来源：http://dali.zhaomingkeji.xyz/Article/details/gticetqdfj.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gtgoiikxuv.html

[T41] Perl：Hello World
来源：http://dali.shangyingyoupin.top/Article/details/gtmwdisvas.html

print "Hello\n";
来源：http://dali.jinqigufen.top/Article/details/gtvudpbxon.html

[T42] Perl：变量类型
来源：http://dali.zycfv.cn/Article/details/gtapnrnwgb.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfjbgyliw.html

[T43] Perl：字符串插值
来源：http://dali.xziqi.cn/Article/details/gtgsfzcwyr.html

"值: $a"
来源：http://dali.ppjwa.cn/Article/details/gtindwmqzd.html

[T44] Perl：条件
来源：http://dali.yuanzhike.top/Article/details/gtinchwnti.html

if ($a > 0) { print "正"; }
来源：http://dali.cashguo.top/Article/details/gtytlsbksb.html

[T45] Perl：数组遍历
来源：http://dali.daria6918.cn/Article/details/gtorzjpqpt.html

for my $x (@arr) { print $x; }
来源：http://dali.fzhhl.top/Article/details/gtegscuhfm.html

[T46] Perl：哈希操作
来源：http://dali.nanxuanxn.top/Article/details/gtvvktupjp.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhengqikj.top/Article/details/gthsiktajm.html

[T47] Perl：正则捕获
来源：http://dali.yanxiufei.cn/Article/details/gtzmjloado.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.xylfe.cn/Article/details/gtfqqtpazx.html

[T48] Perl：正则替换
来源：http://dali.feifeiyinyue.top/Article/details/gtnasontvb.html

$s =~ s/old/new/g;
来源：http://dali.jinghuilouyu.cn/Article/details/gtbuotaicl.html

[T49] Perl：函数
来源：http://dali.jqgfzy.top/Article/details/gtilshwjpo.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.xziqi.cn/Article/details/gtnjtbbdxk.html

[T50] Perl：逐行读文件
来源：http://dali.guowangkeji.top/Article/details/gtomahxmms.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhiwuduotai.top/Article/details/gtfedkzfkp.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfwxkvyan.html

[T51] Scala：Hello World
来源：http://dali.xziqi.cn/Article/details/gtesuuubqs.html

println("Hello")
来源：http://dali.yvedp.cn/Article/details/gtxunvykxv.html

[T52] Scala：变量
来源：http://dali.aizwys.cn/Article/details/gtxnxulaiv.html

val a = 1;  var b = 2
来源：http://dali.cqqwz.cn/Article/details/gtvuacseff.html

[T53] Scala：字符串插值
来源：http://dali.gotoacloud.top/Article/details/gtvhjfcxbe.html

s"值: $b"
来源：http://dali.c1oappe.top/Article/details/gtvxjdagic.html

[T54] Scala：集合映射
来源：http://dali.yanxiufei.cn/Article/details/gtdtexlxnl.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.cdnleiting.top/Article/details/gttgqbedlr.html

[T55] Scala：集合过滤
来源：http://dali.ehwqpu.com/Article/details/gtvshkwukk.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.nanxuanxn.top/Article/details/gthxbowtff.html

[T56] Scala：样例类
来源：http://dali.yj20258888.top/Article/details/gtkxhonqjt.html

case class User(name: String, age: Int)
来源：http://dali.xuanzx.com/Article/details/gtuycwoasj.html

[T57] Scala：模式匹配
来源：http://dali.hammf.cn/Article/details/gtcpvaoowr.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.jlsjyb.cn/Article/details/gtuixbwhrp.html

[T58] Scala：函数定义
来源：http://dali.sysykeji.top/Article/details/gtvorxozlz.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.wangshuangyany.cn/Article/details/gtclsascuq.html

[T59] Scala：循环
来源：http://dali.haohaochexian.top/Article/details/gtpcrrvoup.html

for (i <- 1 to 10) println(i)
来源：http://dali.shangyingyoupin.top/Article/details/gtcyxqmugw.html

[T60] Scala：折叠
来源：http://dali.nanxuanxn.top/Article/details/gtxznvtyxe.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.redwolf501.top/Article/details/gtvctcblxn.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtfynjuefz.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.sweek.top/Article/details/gtmowrhjew.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtubeckpxq.html

[U01] Py：创建虚拟环境
来源：http://dali.nwbrower.top/Article/details/gtozsofmip.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.vqdsnc.cn/Article/details/gtqqvejuxy.html

[U02] Py：导出 / 安装依赖
来源：http://dali.kuanghao11.cn/Article/details/gtzerjwztk.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.ehwqpu.com/Article/details/gtmmrswfdp.html

[U03] Py：加载 .env 配置
来源：http://dali.xziqi.cn/Article/details/gtlxbpikrp.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.havefunace.top/Article/details/gtnexrktmx.html

[U04] Py：变量调试打印
来源：http://dali.tianlin.xyz/Article/details/gtlmuzfzwb.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.chenlongwang.top/Article/details/gtulkucxeo.html


<!-- 参考信息 -->