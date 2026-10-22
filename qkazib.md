代发 wailian999

ssh user@host 'uptime'
来源：http://dali.pycfn.com/Article/details/gthqtutwyv.html

[R58] 下载文件
来源：http://dali.ehwqpu.com/Article/details/gtebppgmxh.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.xylfe.cn/Article/details/gtynmdsfbj.html

[R59] 发 POST JSON
来源：http://dali.0kj1m.cn/Article/details/gtiwvyhnhg.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.hammf.cn/Article/details/gtfqqbvryt.html

[R60] 只看 HTTP 状态码
来源：http://dali.redwolf501.top/Article/details/gtxcoutikq.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.guannengcc.top/Article/details/gtbpugokxu.html

[R61] 磁盘占用
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmetnkchp.html

df -h;  du -sh *
来源：http://dali.jqgufenzy.top/Article/details/gthkqyemdo.html

[R62] 找最占空间的文件
来源：http://dali.gaohongyu789.top/Article/details/gthizdywad.html

du -ah . | sort -rh | head -10
来源：http://dali.ehwqpu.com/Article/details/gtzdnuquxa.html

[R63] 内存与进程
来源：http://dali.chenlongwang.top/Article/details/gtyinnmogd.html

free -h;  ps aux | grep nginx
来源：http://dali.zhengqikj.top/Article/details/gtxvjisfsx.html

[R64] 结束进程
来源：http://dali.jqgufenzy.top/Article/details/gtecuxblwn.html

kill -9 $(pgrep -f app.py)
来源：http://dali.cashguo.top/Article/details/gtmnzliodw.html

[R65] 查看端口占用
来源：http://dali.sysykeji.top/Article/details/gtfusziaos.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.ybcxt.top/Article/details/gttvyibroo.html

[R66] 定时任务
来源：http://dali.zhoulong.xyz/Article/details/gtwfcjlphf.html

crontab -e;  crontab -l
来源：http://dali.zhoulong.xyz/Article/details/gtddlzyspc.html

[R67] 生成随机十六进制串
来源：http://dali.0kj1m.cn/Article/details/gthsfupjvl.html

openssl rand -hex 16
来源：http://dali.yuanzhike.top/Article/details/gtufomvsxw.html

[R68] 计算文件校验值
来源：http://dali.shanyushiyangtech.top/Article/details/gtryisufqy.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.daxiang520.top/Article/details/gtrnpnikal.html

[R69] 生成随机密码
来源：http://dali.cqqwz.cn/Article/details/gtsbpulxyv.html

head -c 16 /dev/urandom | base64
来源：http://dali.havefunace.top/Article/details/gtvdaocbwe.html

[R70] 时间戳与互转
来源：http://dali.ydzc1.top/Article/details/gtrmqmsygn.html

date +%s;  date -d @1700000000
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrglrulpj.html

[R71] 日期格式化
来源：http://dali.jiagoushi.top/Article/details/gtueflnayq.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.sysykeji.top/Article/details/gtmsedanvh.html

[R72] 等待端口就绪
来源：http://dali.xylfe.cn/Article/details/gtffyavpom.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gtpgvfpsmg.html

[R73] 分割大日志
来源：http://dali.chenzaomai.com/Article/details/gtdijncbqe.html

split -l 1000 big.log part_
来源：http://dali.yangfankeji.com/Article/details/gtvqxbtari.html

[R74] 批量重命名
来源：http://dali.sxryk.cn/Article/details/gtcziamjmq.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.jinqigfzy.top/Article/details/gtzhcpvivw.html

[R75] 导出环境变量
来源：http://dali.jlsjyb.cn/Article/details/gthbepmtli.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.hfpthk.cn/Article/details/gtddygjlnq.html

[R76] 使用临时文件
来源：http://dali.aibaodan.cn/Article/details/gtmqyzevwv.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.jlsjyb.cn/Article/details/gtngopslca.html

[R77] 读取用户输入
来源：http://dali.xuanzx.com/Article/details/gtxsoxfhwd.html

read -rp "请输入: " ans
来源：http://dali.hammf.cn/Article/details/gtgnshtdjm.html

[R78] 交互式菜单
来源：http://dali.svipenyu.cn/Article/details/gtagnzbstc.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.jqgfzy.top/Article/details/gthypmjjvq.html

[R79] 解析命令行选项
来源：http://dali.yj20258.top/Article/details/gtjsvpwgpl.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.ppjwa.cn/Article/details/gtzzucuhvf.html

[R80] 查看脚本执行耗时
来源：http://dali.hywenlv.cn/Article/details/gtwagammuj.html

time ./run.sh
来源：http://dali.shanyushiyangtech.top/Article/details/gtlvebvhbv.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtxcrxhrpb.html

S. C / C++ 专题
来源：http://dali.chenlongwang.top/Article/details/gtutaihpny.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtkhxyqaaf.html

[S01] C：Hello World
来源：http://dali.aizwys.cn/Article/details/gtoflazpup.html

#include <stdio.h>
来源：http://dali.tian-w.cn/Article/details/gtcbenaagc.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhongyouzk.top/Article/details/gtfcweqzfb.html

[S02] C：变量与格式化输出
来源：http://dali.daria6918.cn/Article/details/gtxmolpfku.html

int a = 10; printf("%d\n", a);
来源：http://dali.quarkkingdee.top/Article/details/gtppakpqwa.html

[S03] C：读入整数
来源：http://dali.chenzaomai.com/Article/details/gtephomewq.html

int x; scanf("%d", &x);
来源：http://dali.chenjidiqi.icu/Article/details/gtkhxgpeth.html

[S04] C：字符串复制
来源：http://dali.yongpay.top/Article/details/gtjybpmwwo.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.cdnleiting.top/Article/details/gtsvwvqfof.html

[S05] C：字符串长度
来源：http://dali.iojbl.cn/Article/details/gtbdhdzzaa.html

strlen(s)
来源：http://dali.hnxiangtu.top/Article/details/gtczxwvucj.html

[S06] C：字符串比较
来源：http://dali.xuetiantiany.cn/Article/details/gtuhneejtw.html

strcmp(a, b) == 0
来源：http://dali.hnxiangtu.top/Article/details/gtbhsowjbc.html

[S07] C：数组遍历求和
来源：http://dali.yangfankeji.com/Article/details/gtcbsbywwa.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.dashuyun.cn/Article/details/gthfexziyn.html

[S08] C：动态内存分配与释放
来源：http://dali.bjfxy.top/Article/details/gteigucwxq.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.redwolf501.top/Article/details/gtsdcpruqn.html

[S09] C：结构体定义与初始化
来源：http://dali.guannengcc.top/Article/details/gtxhonepes.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhengqikj.top/Article/details/gtejgexwnf.html

[S10] C：指针与解引用
来源：http://dali.zhongyouzk.top/Article/details/gthxkcottk.html

int *p = &a;  *p = 5;
来源：http://dali.wangdashe.top/Article/details/gtnotsdnse.html

[S11] C：逐行读文件
来源：http://dali.pycfn.com/Article/details/gtjvehmrwi.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.kuanghao11.cn/Article/details/gthzkeyykb.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zycfv.cn/Article/details/gtzybdxmvs.html

fclose(f);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdeaaboso.html

[S12] C：写文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsnxcbxfh.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.wangshuangyany.cn/Article/details/gtpowzlnkk.html

[S13] C：宏定义
来源：http://dali.sweek.top/Article/details/gtdfciwdjw.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.chenlongwang.top/Article/details/gtlozmzmva.html

[S14] C：枚举
来源：http://dali.sxryk.cn/Article/details/gtnxgjiekw.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.redwolf501.top/Article/details/gtjdxnaajc.html

[S15] C：类型转换
来源：http://dali.cucudq.cn/Article/details/gtboezopin.html

(double) a / b
来源：http://dali.yangfankeji.com/Article/details/gtbggxwnen.html

[S16] C：位操作置位
来源：http://dali.jqgufenzy.top/Article/details/gtrotvslcj.html

x |= (1 << 3);
来源：http://dali.tianlin.xyz/Article/details/gtcrxrnytm.html

[S17] C：安全拼接字符串
来源：http://dali.c1oappe.top/Article/details/gtjvdnwfmt.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.xuanzx.com/Article/details/gtlfqpdokp.html

[S18] C：命令行参数
来源：http://dali.cheryme.top/Article/details/gtdshvnlmj.html

int main(int argc, char **argv)
来源：http://dali.xylfe.cn/Article/details/gtlttugems.html

[S19] C：快速排序
来源：http://dali.shzxlz.cn/Article/details/gtghquxmnj.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.feifeiyinyue.top/Article/details/gthnbbrvax.html

[S20] C：二分查找
来源：http://dali.yanxiufei.cn/Article/details/gtexyfnazr.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.yanxiufei.cn/Article/details/gtlehwppkn.html

[S21] C：字符类别判断
来源：http://dali.jianghu66.top/Article/details/gtvvzjfpay.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zycfv.cn/Article/details/gtzlbpggkg.html

[S22] C：字符串转数字
来源：http://dali.zycfv.cn/Article/details/gttjtkanyh.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.andypj.xyz/Article/details/gtqrgcedig.html

[S23] C：随机数
来源：http://dali.sufxvd.cn/Article/details/gtlvotkqeq.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.jinqigfzy.top/Article/details/gtslziajra.html

[S24] C：获取本地时间
来源：http://dali.xylfe.cn/Article/details/gtjylemhzg.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.haohaochexian.top/Article/details/gtecfhaclm.html

[S25] C：内存拷贝
来源：http://dali.yuxming.cn/Article/details/gtkbcldxzr.html

memcpy(dst, src, n);
来源：http://dali.fzhhl.top/Article/details/gtfkyonaeh.html

[S26] C：内存清零
来源：http://dali.zycfv.cn/Article/details/gtmdyrzwef.html

memset(a, 0, sizeof a);
来源：http://dali.cqqwz.cn/Article/details/gtinuqphes.html

[S27] C：定义常量
来源：http://dali.svipenyu.cn/Article/details/gtuyhpbcfg.html

const double PI = 3.14159;
来源：http://dali.yueranfly.top/Article/details/gthemqzzck.html

[S28] C：静态变量
来源：http://dali.mhx1999.top/Article/details/gtalrkaljv.html

static int counter = 0;
来源：http://dali.tanke756.top/Article/details/gtmfmncytw.html

[S29] C：变参函数
来源：http://dali.tanke756.top/Article/details/gtorvtfbxy.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.0kj1m.cn/Article/details/gtalfelwjw.html

[S30] C：头文件保护
来源：http://dali.c1oappe.top/Article/details/gtcdjzqmjb.html

#ifndef X_H
来源：http://dali.c1oappe.top/Article/details/gtuikqdkvg.html

#define X_H
来源：http://dali.haohaochexian.top/Article/details/gtqivufkkr.html

#endif
来源：http://dali.redwolf501.top/Article/details/gtjczsqeqz.html

[S31] C++：Hello World
来源：http://dali.yanxiufei.cn/Article/details/gtrygmxmrr.html

#include <iostream>
来源：http://dali.nanxinkj.top/Article/details/gtjwtwnyci.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.ybcxt.top/Article/details/gtlxvxcxsf.html

[S32] C++：字符串
来源：http://dali.hongshengwenyu.top/Article/details/gtlqzrvkgb.html

std::string s = "hi";  s += "!";
来源：http://dali.yanxiufei.cn/Article/details/gtqaciscvf.html

[S33] C++：vector 增删
来源：http://dali.pycfn.com/Article/details/gtjigfgttx.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.aizwys.cn/Article/details/gtmncdhvtj.html

[S34] C++：遍历 vector
来源：http://dali.birdmap.top/Article/details/gtywjebkjd.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.sxryk.cn/Article/details/gtuqyawuzq.html

[S35] C++：map
来源：http://dali.nanxuanxn.top/Article/details/gtaltmhrdw.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yueranfly.top/Article/details/gttginxapu.html

[S36] C++：unordered_map
来源：http://dali.andypj.xyz/Article/details/gtwhdhzkbu.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yj202588.top/Article/details/gtozewwihm.html

[S37] C++：set
来源：http://dali.sxryk.cn/Article/details/gthkbbmfuz.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.cheryme.top/Article/details/gtpurpenfo.html

[S38] C++：排序
来源：http://dali.dianchejie.cn/Article/details/gtmpyjoliu.html

std::sort(v.begin(), v.end());
来源：http://dali.xuetiantiany.cn/Article/details/gtnzilvdpm.html

[S39] C++：自定义比较器排序
来源：http://dali.daria6918.cn/Article/details/gtlgcrypzx.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.yuxming.cn/Article/details/gtvejhkobo.html

[S40] C++：查找元素
来源：http://dali.yj20258.top/Article/details/gtikikfccj.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.gzhubu.top/Article/details/gtkyoadzhl.html

[S41] C++：类与构造函数
来源：http://dali.0kj1m.cn/Article/details/gtlagufdzc.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.fzhhl.top/Article/details/gtmvuisthf.html

[S42] C++：继承与虚函数
来源：http://dali.hysaishi.cn/Article/details/gtigirdxao.html

class B : public Base { public: void f() override {} };
来源：http://dali.dianchejie.cn/Article/details/gtlmtqgmff.html

[S43] C++：智能指针
来源：http://dali.zhongyouzk.top/Article/details/gtsoiaxkfe.html

auto p = std::make_unique<int>(5);
来源：http://dali.yonumen.top/Article/details/gtcfhmthcw.html

[S44] C++：引用传参
来源：http://dali.yueranfly.top/Article/details/gtefqeusjy.html

void inc(int &x) { ++x; }
来源：http://dali.zdqjudy.top/Article/details/gtckjoqzqn.html

[S45] C++：lambda
来源：http://dali.shuidangran.top/Article/details/gtdgvbmbdy.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.cdnleiting.top/Article/details/gtxbfobhjs.html

[S46] C++：函数模板
来源：http://dali.9152youxi.cn/Article/details/gtrodellnc.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.jinqigfzy.top/Article/details/gtwzvacitr.html

[S47] C++：结构化绑定遍历
来源：http://dali.9152youxi.cn/Article/details/gtjginkbko.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.cashguo.top/Article/details/gtsprszwzv.html

[S48] C++：逐行读文件
来源：http://dali.gotoacloud.top/Article/details/gtqugvjehj.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.cdnleiting.top/Article/details/gtevjkpnsc.html

while (std::getline(in, line)) { }
来源：http://dali.ivvv.top/Article/details/gtolpubvrj.html

[S49] C++：写文件
来源：http://dali.wangdashe.top/Article/details/gtdsogzuvs.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.gotoacloud.top/Article/details/gtkhbuukiy.html

[S50] C++：格式化数字
来源：http://dali.cqqwz.cn/Article/details/gtyayzzbbu.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.9152youxi.cn/Article/details/gtqqwkgxiy.html

[S51] C++：显式类型转换
来源：http://dali.jqgufenzy.top/Article/details/gtnxktdaxs.html

static_cast<double>(a) / b
来源：http://dali.jinqigufen.top/Article/details/gtntanjgzt.html

[S52] C++：const 与 noexcept
来源：http://dali.wangdashe.top/Article/details/gtparayijj.html

int size() const noexcept { return n_; }
来源：http://dali.snrcjt.cn/Article/details/gtviamuxal.html

[S53] C++：移动语义
来源：http://dali.jinqigufen.top/Article/details/gtfgtrgibx.html

std::vector<int> w = std::move(v);
来源：http://dali.tianlin.xyz/Article/details/gtwzwnglfh.html

[S54] C++：异常处理
来源：http://dali.hysaishi.cn/Article/details/gtofubbigt.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.0kj1m.cn/Article/details/gteoasfmua.html

[S55] C++：结构化绑定
来源：http://dali.zhoulong.xyz/Article/details/gtakzncugn.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.chenlongwang.top/Article/details/gtjvixhitf.html

[S56] C++：optional
来源：http://dali.xuanzx.com/Article/details/gttnpbxqqp.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.fzhhl.top/Article/details/gtndrojzhk.html

[S57] C++：编译期常量
来源：http://dali.ehwqpu.com/Article/details/gtonlsuorw.html

constexpr int N = 10;
来源：http://dali.quarkkingdee.top/Article/details/gtlfzeuiwo.html

[S58] C++：命名空间
来源：http://dali.meibo888.top/Article/details/gtzcfbbwxe.html

namespace ns { int f() { return 1; } }
来源：http://dali.shanyushiyangtech.top/Article/details/gtkextqsfv.html

[S59] C++：静态断言
来源：http://dali.ppjwa.cn/Article/details/gtikawpwrg.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.jiagoushi.top/Article/details/gtmknjnnol.html

[S60] C++：遍历并删除元素
来源：http://dali.yonumen.top/Article/details/gthoxxejem.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtunspupma.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtcizxzxor.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.hysaishi.cn/Article/details/gtyyzjokpn.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtxjzaltpw.html

[T01] Kotlin：Hello World
来源：http://dali.cdnleiting.top/Article/details/gtaaoyyvzw.html

println("Hello")
来源：http://dali.svipenyu.cn/Article/details/gtgjuhrhlu.html

[T02] Kotlin：变量
来源：http://dali.yj20258888.top/Article/details/gtxungykim.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.yangfankeji.com/Article/details/gtdmncaowf.html

[T03] Kotlin：字符串模板
来源：http://dali.0kj1m.cn/Article/details/gtconhlflw.html

"值: $b"
来源：http://dali.yangfankeji.com/Article/details/gtnuszksfc.html

[T04] Kotlin：空安全
来源：http://dali.ppjwa.cn/Article/details/gtwflthlot.html

val n: String? = null;  n?.length
来源：http://dali.gogol.net.cn/Article/details/gtwwewosts.html

[T05] Kotlin：when 表达式
来源：http://dali.jqgufenzy.top/Article/details/gtbaozayuj.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.gotoacloud.top/Article/details/gtxotweqlm.html

[T06] Kotlin：集合映射
来源：http://dali.jiagoushi.top/Article/details/gtthezfttl.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.xuanzx.com/Article/details/gtkbavrbym.html

[T07] Kotlin：集合过滤
来源：http://dali.yuxming.cn/Article/details/gtntcxirgo.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.yangfankeji.com/Article/details/gttatdiyio.html

[T08] Kotlin：数据类
来源：http://dali.cashguo.top/Article/details/gtwytcifxl.html

data class User(val name: String, val age: Int)
来源：http://dali.hongshengwenyu.top/Article/details/gtwxyjknnf.html

[T09] Kotlin：扩展函数
来源：http://dali.xuanzx.com/Article/details/gtoxbdhxwl.html

fun String.exclaim() = this + "!"
来源：http://dali.yj20258.top/Article/details/gtiwjfokbq.html

[T10] Kotlin：默认参数
来源：http://dali.fzhhl.top/Article/details/gtbczqclup.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.mhx1999.top/Article/details/gtlvwomftz.html

[T11] Kotlin：协程
来源：http://dali.yj202588.top/Article/details/gtagkytdtp.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.gogol.net.cn/Article/details/gtxdvpczqq.html

[T12] Kotlin：解构声明
来源：http://dali.birdmap.top/Article/details/gtgupqplbd.html

val (a, b) = Pair(1, 2)
来源：http://dali.yueranfly.top/Article/details/gtyaghhwuq.html

[T13] Kotlin：只读 Map
来源：http://dali.ydzc1.top/Article/details/gtwbqxatzk.html

val m = mapOf("a" to 1)
来源：http://dali.quarkkingdee.top/Article/details/gtmtnoijms.html

[T14] Kotlin：循环
来源：http://dali.yonumen.top/Article/details/gtellfdwsu.html

for (i in 1..10) println(i)
来源：http://dali.sysykeji.top/Article/details/gtzqtjoadc.html

[T15] Kotlin：接口
来源：http://dali.birdmap.top/Article/details/gtsnazccri.html

interface Shape { fun area(): Double }
来源：http://dali.smart0.xyz/Article/details/gtusffwveb.html

[T16] Swift：Hello World
来源：http://dali.cashguo.top/Article/details/gtpbicpprf.html

print("Hello")
来源：http://dali.bjfxy.top/Article/details/gtczkynmfh.html

[T17] Swift：变量与常量
来源：http://dali.yanxiufei.cn/Article/details/gtzvqlbcac.html

var a = 1;  let b = 2
来源：http://dali.xuetiantiany.cn/Article/details/gtnetbhgbj.html

[T18] Swift：字符串插值
来源：http://dali.smart0.xyz/Article/details/gtjljgoene.html

"值: \(b)"
来源：http://dali.jianghu66.top/Article/details/gtilxdkgdv.html

[T19] Swift：可选绑定
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmqbbmvbf.html

if let n = opt { print(n) }
来源：http://dali.nanxuanxn.top/Article/details/gtehmagkpy.html

[T20] Swift：数组操作
来源：http://dali.ivvv.top/Article/details/gtjenblvpc.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.chenzaomai.com/Article/details/gtkwmbunsg.html

[T21] Swift：遍历
来源：http://dali.zhixingplan.top/Article/details/gttemnhfoy.html

for x in a { print(x) }
来源：http://dali.sweek.top/Article/details/gtyzsrtdzi.html

[T22] Swift：字典
来源：http://dali.zhoulong.xyz/Article/details/gtrgkrjkwf.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzbcmadgm.html

[T23] Swift：函数
来源：http://dali.hywenlv.cn/Article/details/gthtagxzlp.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gtioukxqml.html

[T24] Swift：闭包
来源：http://dali.pycfn.com/Article/details/gtrvabuktw.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.dashuyun.cn/Article/details/gttgzxkgxl.html

[T25] Swift：结构体
来源：http://dali.xuetiantiany.cn/Article/details/gtldsrnhia.html

struct P { var x: Int }
来源：http://dali.yj20258.top/Article/details/gtbetzffxi.html

[T26] Swift：类与重写
来源：http://dali.ppjwa.cn/Article/details/gtfeihdkky.html

class A: Base { override func f() {} }
来源：http://dali.gogol.net.cn/Article/details/gtpnsbszzz.html

[T27] Swift：错误处理
来源：http://dali.shanyushiyangkeji.top/Article/details/gtutbtbegp.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gtzsprcipz.html

[T28] Swift：枚举
来源：http://dali.fzhhl.top/Article/details/gtcxmqkqke.html

enum Color { case red, green }
来源：http://dali.hnqzz.top/Article/details/gtmayivsxb.html

[T29] Swift：guard 提前返回
来源：http://dali.gaohongyu789.top/Article/details/gtqlkslipa.html

guard let x = opt else { return }
来源：http://dali.zhongyouzk.top/Article/details/gtxpyazyio.html

[T30] Swift：协议
来源：http://dali.ydzc1.top/Article/details/gtavjywwlo.html

protocol Shape { func area() -> Double }
来源：http://dali.sxryk.cn/Article/details/gtjobzyapb.html

[T31] Lua：Hello World
来源：http://dali.yangfankeji.com/Article/details/gtxglyhuei.html

print("Hello")
来源：http://dali.guannengcc.top/Article/details/gtutxnfhuj.html

[T32] Lua：局部变量
来源：http://dali.ydzc1.top/Article/details/gtpkaqryjf.html

local a = 1
来源：http://dali.tanke756.top/Article/details/gtfdevtuyl.html

[T33] Lua：表（数组）
来源：http://dali.yueranfly.top/Article/details/gtgqdiqluc.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.guannengcc.top/Article/details/gtryfnfcwc.html

[T34] Lua：遍历表
来源：http://dali.fzhhl.top/Article/details/gtalmavdnc.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.sxryk.cn/Article/details/gtyunhjsbq.html

[T35] Lua：字典表
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfiiugzqf.html

local d = { a = 1 };  d.b = 2
来源：http://dali.gaohongyu789.top/Article/details/gtroetcdzn.html

[T36] Lua：函数
来源：http://dali.tian-w.cn/Article/details/gtnvkfbybb.html

function add(a, b) return a + b end
来源：http://dali.guannengcc.top/Article/details/gthsarmdde.html

[T37] Lua：字符串拼接
来源：http://dali.havefunace.top/Article/details/gtivijpurm.html

"a" .. "b"
来源：http://dali.ydzc1.top/Article/details/gtjqxtxago.html

[T38] Lua：条件
来源：http://dali.shangyingyoupin.top/Article/details/gtrjwkbjat.html

if x > 0 then print("正") end
来源：http://dali.quarkkingdee.top/Article/details/gtabuiygxt.html

[T39] Lua：模式匹配
来源：http://dali.iojbl.cn/Article/details/gtfwqqvltq.html

string.find(s, "%d+")
来源：http://dali.zdqjudy.top/Article/details/gtwtifioth.html

[T40] Lua：元表
来源：http://dali.fzhhl.top/Article/details/gtixnuckdu.html

setmetatable({}, { __index = base })
来源：http://dali.zhoulong.xyz/Article/details/gtlhjccoud.html

[T41] Perl：Hello World
来源：http://dali.hnxiangtu.top/Article/details/gtaguqrdnb.html

print "Hello\n";
来源：http://dali.haohaochexian.top/Article/details/gtcmxxwdzh.html

[T42] Perl：变量类型
来源：http://dali.tianlin.xyz/Article/details/gttrdntmhk.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.daxiang520.top/Article/details/gtpselncus.html

[T43] Perl：字符串插值
来源：http://dali.xylfe.cn/Article/details/gtckhgwmgt.html

"值: $a"
来源：http://dali.cqqwz.cn/Article/details/gtmnoagjov.html

[T44] Perl：条件
来源：http://dali.chenzaomai.com/Article/details/gthukccgti.html

if ($a > 0) { print "正"; }
来源：http://dali.zdqjudy.top/Article/details/gtekhfnyxr.html

[T45] Perl：数组遍历
来源：http://dali.cashguo.top/Article/details/gttcgqtytf.html

for my $x (@arr) { print $x; }
来源：http://dali.c1oappe.top/Article/details/gtxpmegwio.html

[T46] Perl：哈希操作
来源：http://dali.ivvv.top/Article/details/gtfltvewzk.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.yj20258.top/Article/details/gtentlizer.html

[T47] Perl：正则捕获
来源：http://dali.jqgfzy.top/Article/details/gtdvtrpwrc.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.hammf.cn/Article/details/gtaoqqpnxe.html

[T48] Perl：正则替换
来源：http://dali.gotoacloud.top/Article/details/gthxvipnqj.html

$s =~ s/old/new/g;
来源：http://dali.tian-w.cn/Article/details/gtuxzpnvsu.html

[T49] Perl：函数
来源：http://dali.xylfe.cn/Article/details/gtamkflkep.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.yanxiufei.cn/Article/details/gtnczivisy.html

[T50] Perl：逐行读文件
来源：http://dali.xinyue.icu/Article/details/gtxkbsjguv.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.quarkkingdee.top/Article/details/gtximrgcao.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.hfpthk.cn/Article/details/gttyqhohut.html

[T51] Scala：Hello World
来源：http://dali.nwbrower.top/Article/details/gtcmbudurc.html

println("Hello")
来源：http://dali.fengsongda.top/Article/details/gtyeuazanv.html

[T52] Scala：变量
来源：http://dali.ppjwa.cn/Article/details/gtmvlxgmfn.html

val a = 1;  var b = 2
来源：http://dali.0kj1m.cn/Article/details/gtdjtiqbag.html

[T53] Scala：字符串插值
来源：http://dali.aizwys.cn/Article/details/gtbofvpydf.html

s"值: $b"
来源：http://dali.ybcxt.top/Article/details/gtbwmsimdn.html

[T54] Scala：集合映射
来源：http://dali.snrcjt.cn/Article/details/gtjrstghys.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.cdnleiting.top/Article/details/gtjbgycuxs.html

[T55] Scala：集合过滤
来源：http://dali.cashguo.top/Article/details/gtoxtfjtga.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.andypj.xyz/Article/details/gtnsuiiwtg.html

[T56] Scala：样例类
来源：http://dali.shanyushiyangtech.top/Article/details/gtbzbbcfhx.html

case class User(name: String, age: Int)
来源：http://dali.zhixingplan.top/Article/details/gtecwgetfe.html

[T57] Scala：模式匹配
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnhepwlye.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gtydaouoeo.html

[T58] Scala：函数定义
来源：http://dali.gotoacloud.top/Article/details/gtccuegocx.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.tianlin.xyz/Article/details/gtsghuqxpz.html

[T59] Scala：循环
来源：http://dali.aizwys.cn/Article/details/gtsyladwkq.html

for (i <- 1 to 10) println(i)
来源：http://dali.hfpthk.cn/Article/details/gtppoteqgv.html

[T60] Scala：折叠
来源：http://dali.yanxiufei.cn/Article/details/gtxcbdzmlk.html


<!-- 参考信息 -->