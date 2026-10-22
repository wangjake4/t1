代发 wailian999

ssh user@host 'uptime'
来源：http://dali.daria6918.cn/Article/details/gthkpzbgwi.html

[R58] 下载文件
来源：http://dali.sufxvd.cn/Article/details/gtivrylpga.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.svipenyu.cn/Article/details/gtmoezzwmz.html

[R59] 发 POST JSON
来源：http://dali.wangshuangyany.cn/Article/details/gtjjbgrohc.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.mhx1999.top/Article/details/gtopufaqvw.html

[R60] 只看 HTTP 状态码
来源：http://dali.shuidangran.top/Article/details/gtumvtyiau.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.pycfn.com/Article/details/gtovvflroy.html

[R61] 磁盘占用
来源：http://dali.snrcjt.cn/Article/details/gtlmnhjhri.html

df -h;  du -sh *
来源：http://dali.zhiwuduotai.top/Article/details/gtlkuntoch.html

[R62] 找最占空间的文件
来源：http://dali.gaohongyu789.top/Article/details/gtvfcyehdm.html

du -ah . | sort -rh | head -10
来源：http://dali.xuetiantiany.cn/Article/details/gtqnpswqyw.html

[R63] 内存与进程
来源：http://dali.ybcxt.top/Article/details/gtvdbywygg.html

free -h;  ps aux | grep nginx
来源：http://dali.ydzc1.top/Article/details/gtrlwlqcbs.html

[R64] 结束进程
来源：http://dali.vqdsnc.cn/Article/details/gtwcigpwcn.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhongyouzk.top/Article/details/gtcdaznado.html

[R65] 查看端口占用
来源：http://dali.jinghuilouyu.cn/Article/details/gtlaturkby.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.c1oappe.top/Article/details/gtvlblkgil.html

[R66] 定时任务
来源：http://dali.hysaishi.cn/Article/details/gtjlnyyxhr.html

crontab -e;  crontab -l
来源：http://dali.jianghu66.top/Article/details/gtpodijkgp.html

[R67] 生成随机十六进制串
来源：http://dali.aibaodan.cn/Article/details/gtxifqskxt.html

openssl rand -hex 16
来源：http://dali.gaohongyu789.top/Article/details/gtgzoagdif.html

[R68] 计算文件校验值
来源：http://dali.tianlin.xyz/Article/details/gtziucywjc.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.birdmap.top/Article/details/gtnzzwdsug.html

[R69] 生成随机密码
来源：http://dali.yj20258888.top/Article/details/gtrvanpanp.html

head -c 16 /dev/urandom | base64
来源：http://dali.jianghu66.top/Article/details/gtkaudfjnp.html

[R70] 时间戳与互转
来源：http://dali.hfpthk.cn/Article/details/gtzywnkwyq.html

date +%s;  date -d @1700000000
来源：http://dali.feifeiyinyue.top/Article/details/gtgtvpmfhl.html

[R71] 日期格式化
来源：http://dali.iojbl.cn/Article/details/gtjmxeqhtx.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.fzhhl.top/Article/details/gtybbtymkt.html

[R72] 等待端口就绪
来源：http://dali.cdnleiting.top/Article/details/gtpykxqkot.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.9152youxi.cn/Article/details/gtnqisefzd.html

[R73] 分割大日志
来源：http://dali.aizwys.cn/Article/details/gthuqylnxi.html

split -l 1000 big.log part_
来源：http://dali.jyoumei.cn/Article/details/gtgkgzvkig.html

[R74] 批量重命名
来源：http://dali.dashuyun.cn/Article/details/gtaaxodsbq.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zycfv.cn/Article/details/gtyjrukype.html

[R75] 导出环境变量
来源：http://dali.yuanzhike.top/Article/details/gtkmlfadti.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.shzxlz.cn/Article/details/gtusdaxhvg.html

[R76] 使用临时文件
来源：http://dali.yueranfly.top/Article/details/gtcilzknfn.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.hfpthk.cn/Article/details/gtxbcqrkaw.html

[R77] 读取用户输入
来源：http://dali.mhx1999.top/Article/details/gtwwqlqtwt.html

read -rp "请输入: " ans
来源：http://dali.zhongyouzk.top/Article/details/gtqwrayray.html

[R78] 交互式菜单
来源：http://dali.cqqwz.cn/Article/details/gtlyuyrpsp.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.gotoacloud.top/Article/details/gtgdhdaely.html

[R79] 解析命令行选项
来源：http://dali.fzhhl.top/Article/details/gtkotnuplm.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.pengpengdd.cyou/Article/details/gtbparlnqh.html

[R80] 查看脚本执行耗时
来源：http://dali.yj20258.top/Article/details/gtieeoybrx.html

time ./run.sh
来源：http://dali.yangfankeji.com/Article/details/gtktvmhjlo.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtvamgvynu.html

S. C / C++ 专题
来源：http://dali.bjfxy.top/Article/details/gtklnkkase.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtnvlfzpai.html

[S01] C：Hello World
来源：http://dali.yuanzhike.top/Article/details/gtrwqusphd.html

#include <stdio.h>
来源：http://dali.dianchejie.cn/Article/details/gtgeaakzrp.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.shuidangran.top/Article/details/gtsspntdyu.html

[S02] C：变量与格式化输出
来源：http://dali.redwolf501.top/Article/details/gtxdmaohzb.html

int a = 10; printf("%d\n", a);
来源：http://dali.yj202588.top/Article/details/gtawcblwzn.html

[S03] C：读入整数
来源：http://dali.tianlin.xyz/Article/details/gtkucmwjwz.html

int x; scanf("%d", &x);
来源：http://dali.hnxiangtu.top/Article/details/gtfznrhtia.html

[S04] C：字符串复制
来源：http://dali.hysaishi.cn/Article/details/gtoptevxds.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyfpnevhn.html

[S05] C：字符串长度
来源：http://dali.fengsongda.top/Article/details/gtawwmilre.html

strlen(s)
来源：http://dali.tian-w.cn/Article/details/gtqgqgpoal.html

[S06] C：字符串比较
来源：http://dali.gotoacloud.top/Article/details/gtapybppnn.html

strcmp(a, b) == 0
来源：http://dali.chenjidiqi.icu/Article/details/gtkitjrnfv.html

[S07] C：数组遍历求和
来源：http://dali.gotoacloud.top/Article/details/gtflianmpy.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.yj20258888.top/Article/details/gtbruullhu.html

[S08] C：动态内存分配与释放
来源：http://dali.cdnleiting.top/Article/details/gtvorfwrgh.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.dianchejie.cn/Article/details/gtmvtpximd.html

[S09] C：结构体定义与初始化
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvmplifwo.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.andypj.xyz/Article/details/gtblqddxjo.html

[S10] C：指针与解引用
来源：http://dali.jyoumei.cn/Article/details/gtleefzwld.html

int *p = &a;  *p = 5;
来源：http://dali.haohaochexian.top/Article/details/gtynzwvnrp.html

[S11] C：逐行读文件
来源：http://dali.ydzc1.top/Article/details/gttmjxaqcj.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.shuidangran.top/Article/details/gtrctuygqh.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxampsmyt.html

fclose(f);
来源：http://dali.mhx1999.top/Article/details/gtsyjlzktg.html

[S12] C：写文件
来源：http://dali.daxiang520.top/Article/details/gtcwfwccyg.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.xylfe.cn/Article/details/gtowcoodzd.html

[S13] C：宏定义
来源：http://dali.yueranfly.top/Article/details/gtkdbpsfae.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.aibaodan.cn/Article/details/gtzqvodmvd.html

[S14] C：枚举
来源：http://dali.cqqwz.cn/Article/details/gtdvonrxuc.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.jinghuilouyu.cn/Article/details/gtkpyquesd.html

[S15] C：类型转换
来源：http://dali.aizwys.cn/Article/details/gtzcgpeinw.html

(double) a / b
来源：http://dali.svipenyu.cn/Article/details/gtfqmmzbli.html

[S16] C：位操作置位
来源：http://dali.zhengqikj.top/Article/details/gtsaxmldpw.html

x |= (1 << 3);
来源：http://dali.ehwqpu.com/Article/details/gtiqhwqoyg.html

[S17] C：安全拼接字符串
来源：http://dali.chenzaomai.com/Article/details/gtltbepiaj.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.quarkkingdee.top/Article/details/gtykespfmz.html

[S18] C：命令行参数
来源：http://dali.svipenyu.cn/Article/details/gtzuyjpbnd.html

int main(int argc, char **argv)
来源：http://dali.vqdsnc.cn/Article/details/gtzzitrlvh.html

[S19] C：快速排序
来源：http://dali.yonumen.top/Article/details/gtacflobtn.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.nanxuanxn.top/Article/details/gtpgwyagcz.html

[S20] C：二分查找
来源：http://dali.xziqi.cn/Article/details/gtlrgrinay.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.shanyushiyangkeji.top/Article/details/gterzhymfl.html

[S21] C：字符类别判断
来源：http://dali.jinqigfzy.top/Article/details/gthtrciqih.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.jyoumei.cn/Article/details/gtcgpoaqwc.html

[S22] C：字符串转数字
来源：http://dali.zhoulong.xyz/Article/details/gtbgefnvip.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.jiagoushi.top/Article/details/gttgtlgeno.html

[S23] C：随机数
来源：http://dali.yvedp.cn/Article/details/gtskxcuzsu.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.meibo888.top/Article/details/gtydqfvyuw.html

[S24] C：获取本地时间
来源：http://dali.hongshengwenyu.top/Article/details/gtrqkzxzns.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.sweek.top/Article/details/gtgjtjxhlb.html

[S25] C：内存拷贝
来源：http://dali.hfpthk.cn/Article/details/gtkivgmten.html

memcpy(dst, src, n);
来源：http://dali.yangfankeji.com/Article/details/gtxguvklgw.html

[S26] C：内存清零
来源：http://dali.shzxlz.cn/Article/details/gtwhebtxet.html

memset(a, 0, sizeof a);
来源：http://dali.meibo888.top/Article/details/gtrnurtaae.html

[S27] C：定义常量
来源：http://dali.9152youxi.cn/Article/details/gtjedygjum.html

const double PI = 3.14159;
来源：http://dali.aizwys.cn/Article/details/gtonfjnshd.html

[S28] C：静态变量
来源：http://dali.tian-w.cn/Article/details/gtjmushelo.html

static int counter = 0;
来源：http://dali.cheryme.top/Article/details/gtkbxpdsxc.html

[S29] C：变参函数
来源：http://dali.gogol.net.cn/Article/details/gtuisdinub.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.yongpay.top/Article/details/gtnxrbinzg.html

[S30] C：头文件保护
来源：http://dali.jinqigfzy.top/Article/details/gtkswjibmq.html

#ifndef X_H
来源：http://dali.vqdsnc.cn/Article/details/gtvogqssbz.html

#define X_H
来源：http://dali.snrcjt.cn/Article/details/gttjofozep.html

#endif
来源：http://dali.hnxiangtu.top/Article/details/gtwfuuekdf.html

[S31] C++：Hello World
来源：http://dali.ydzc1.top/Article/details/gtnckkjnsb.html

#include <iostream>
来源：http://dali.yuanzhike.top/Article/details/gtgstzwzny.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.gaohongyu789.top/Article/details/gtgpuqlinz.html

[S32] C++：字符串
来源：http://dali.zhaomingkeji.xyz/Article/details/gteydjazmu.html

std::string s = "hi";  s += "!";
来源：http://dali.chenlongwang.top/Article/details/gtoggguqpc.html

[S33] C++：vector 增删
来源：http://dali.hammf.cn/Article/details/gtobfsnnzq.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.ehwqpu.com/Article/details/gtvpwytqqo.html

[S34] C++：遍历 vector
来源：http://dali.jqgfzy.top/Article/details/gtrqphtscg.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuuwybfmq.html

[S35] C++：map
来源：http://dali.zhongyouzk.top/Article/details/gtaampjfpn.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.gotoacloud.top/Article/details/gtbcnrdbrn.html

[S36] C++：unordered_map
来源：http://dali.sufxvd.cn/Article/details/gtoipemoev.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.guannengcc.top/Article/details/gtczkexzor.html

[S37] C++：set
来源：http://dali.nwbrower.top/Article/details/gtfnbhbuqn.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.jinqigfzy.top/Article/details/gtmthtejge.html

[S38] C++：排序
来源：http://dali.zhixingplan.top/Article/details/gtcpipfnmw.html

std::sort(v.begin(), v.end());
来源：http://dali.quarkkingdee.top/Article/details/gtsqndkpfw.html

[S39] C++：自定义比较器排序
来源：http://dali.cashguo.top/Article/details/gtrvbzwzju.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.yvedp.cn/Article/details/gtatudvznv.html

[S40] C++：查找元素
来源：http://dali.ybcxt.top/Article/details/gtwrwdpgvm.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.hongshengwenyu.top/Article/details/gtqujqilap.html

[S41] C++：类与构造函数
来源：http://dali.yj20258888.top/Article/details/gtrjsjtdhw.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.quarkkingdee.top/Article/details/gttoslciom.html

[S42] C++：继承与虚函数
来源：http://dali.cashguo.top/Article/details/gtglvhbsry.html

class B : public Base { public: void f() override {} };
来源：http://dali.jinyuanbaomall.cn/Article/details/gtunjigewz.html

[S43] C++：智能指针
来源：http://dali.jianghu66.top/Article/details/gtyhpmunkw.html

auto p = std::make_unique<int>(5);
来源：http://dali.yvedp.cn/Article/details/gtmeuqally.html

[S44] C++：引用传参
来源：http://dali.jqgufenzy.top/Article/details/gtqjtsqbfi.html

void inc(int &x) { ++x; }
来源：http://dali.jinqigufen.top/Article/details/gtqgsxzidu.html

[S45] C++：lambda
来源：http://dali.sysykeji.top/Article/details/gtgwzxoibv.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.shangyingyoupin.top/Article/details/gtfssmghyo.html

[S46] C++：函数模板
来源：http://dali.smart0.xyz/Article/details/gtfgthcnph.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.sufxvd.cn/Article/details/gtihowbfnl.html

[S47] C++：结构化绑定遍历
来源：http://dali.wangdashe.top/Article/details/gtygmwubin.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.tanke756.top/Article/details/gtvaacetwu.html

[S48] C++：逐行读文件
来源：http://dali.0kj1m.cn/Article/details/gttesafpxi.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.nanxinkj.top/Article/details/gtjnyljyrb.html

while (std::getline(in, line)) { }
来源：http://dali.zhixingplan.top/Article/details/gtnedwssco.html

[S49] C++：写文件
来源：http://dali.redwolf501.top/Article/details/gtdqdjypqg.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.jlsjyb.cn/Article/details/gtdhahgxqq.html

[S50] C++：格式化数字
来源：http://dali.c1oappe.top/Article/details/gtvzhjqwju.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.yangfankeji.com/Article/details/gtfmaqojea.html

[S51] C++：显式类型转换
来源：http://dali.shanyushiyangtech.top/Article/details/gtueylwvlk.html

static_cast<double>(a) / b
来源：http://dali.shanyushiyangtech.top/Article/details/gtqdctrekt.html

[S52] C++：const 与 noexcept
来源：http://dali.hfpthk.cn/Article/details/gtlvwkmoef.html

int size() const noexcept { return n_; }
来源：http://dali.guannengcc.top/Article/details/gtycblfzen.html

[S53] C++：移动语义
来源：http://dali.chenzaomai.com/Article/details/gtkqlubaid.html

std::vector<int> w = std::move(v);
来源：http://dali.tian-w.cn/Article/details/gtizlytkbh.html

[S54] C++：异常处理
来源：http://dali.9152youxi.cn/Article/details/gtmtahovcn.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.smart0.xyz/Article/details/gtbbrognvm.html

[S55] C++：结构化绑定
来源：http://dali.xuetiantiany.cn/Article/details/gtrrhavcnv.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.haohaochexian.top/Article/details/gtfhtdxbir.html

[S56] C++：optional
来源：http://dali.tian-w.cn/Article/details/gtjwlrbbla.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yonumen.top/Article/details/gtrphepxme.html

[S57] C++：编译期常量
来源：http://dali.zdqjudy.top/Article/details/gtqmcasaxm.html

constexpr int N = 10;
来源：http://dali.haohaochexian.top/Article/details/gtyuukmcdg.html

[S58] C++：命名空间
来源：http://dali.shangyingyoupin.top/Article/details/gtpvkfmqqk.html

namespace ns { int f() { return 1; } }
来源：http://dali.smart0.xyz/Article/details/gtnbunpotn.html

[S59] C++：静态断言
来源：http://dali.jqgufenzy.top/Article/details/gtzcuzvfno.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.birdmap.top/Article/details/gtllspbgip.html

[S60] C++：遍历并删除元素
来源：http://dali.hfpthk.cn/Article/details/gtbyiqbmop.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.pengpengdd.cyou/Article/details/gttrigdozg.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gttzuunfzk.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.vqdsnc.cn/Article/details/gtxhovvsks.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtjtotzbgs.html

[T01] Kotlin：Hello World
来源：http://dali.9152youxi.cn/Article/details/gtkiedpaeb.html

println("Hello")
来源：http://dali.yonumen.top/Article/details/gtwjeyikwx.html

[T02] Kotlin：变量
来源：http://dali.shzxlz.cn/Article/details/gtwoekztqv.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.nanxinkj.top/Article/details/gtanvatnyx.html

[T03] Kotlin：字符串模板
来源：http://dali.sxryk.cn/Article/details/gtmmyqfufc.html

"值: $b"
来源：http://dali.zhongyouzk.top/Article/details/gtjhhakeat.html

[T04] Kotlin：空安全
来源：http://dali.vqdsnc.cn/Article/details/gtuyfdxsgw.html

val n: String? = null;  n?.length
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtucbfzlye.html

[T05] Kotlin：when 表达式
来源：http://dali.hongshengwenyu.top/Article/details/gtffxkvghn.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.cucudq.cn/Article/details/gtyulfblzc.html

[T06] Kotlin：集合映射
来源：http://dali.0kj1m.cn/Article/details/gttqmmvbsv.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.c1oappe.top/Article/details/gtvdgohjmb.html

[T07] Kotlin：集合过滤
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbbpewnhi.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhongyouzk.top/Article/details/gtfbjafnwa.html

[T08] Kotlin：数据类
来源：http://dali.ivvv.top/Article/details/gtolkflzrc.html

data class User(val name: String, val age: Int)
来源：http://dali.hnxiangtu.top/Article/details/gtcuaopuew.html

[T09] Kotlin：扩展函数
来源：http://dali.andypj.xyz/Article/details/gtxdffizmr.html

fun String.exclaim() = this + "!"
来源：http://dali.zhiwuduotai.top/Article/details/gthkugvstg.html

[T10] Kotlin：默认参数
来源：http://dali.yueranfly.top/Article/details/gtbyigwxsc.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.aibaodan.cn/Article/details/gteveajaaw.html

[T11] Kotlin：协程
来源：http://dali.andypj.xyz/Article/details/gtzvgzwjlx.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.jqgfzy.top/Article/details/gtozjckeud.html

[T12] Kotlin：解构声明
来源：http://dali.xziqi.cn/Article/details/gtcyadjwmn.html

val (a, b) = Pair(1, 2)
来源：http://dali.gzhubu.top/Article/details/gtrlbxogla.html

[T13] Kotlin：只读 Map
来源：http://dali.fzhhl.top/Article/details/gttlwajcua.html

val m = mapOf("a" to 1)
来源：http://dali.pycfn.com/Article/details/gtdjeyproi.html

[T14] Kotlin：循环
来源：http://dali.haohaochexian.top/Article/details/gtdupoozhl.html

for (i in 1..10) println(i)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtibjtwnoh.html

[T15] Kotlin：接口
来源：http://dali.vqdsnc.cn/Article/details/gtengtwyhm.html

interface Shape { fun area(): Double }
来源：http://dali.hfpthk.cn/Article/details/gtikqvbnct.html

[T16] Swift：Hello World
来源：http://dali.jinyuanbaomall.cn/Article/details/gtygeruegj.html

print("Hello")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoqexgcnf.html

[T17] Swift：变量与常量
来源：http://dali.cqqwz.cn/Article/details/gtgxiqdukb.html

var a = 1;  let b = 2
来源：http://dali.svipenyu.cn/Article/details/gtcbtwzxdy.html

[T18] Swift：字符串插值
来源：http://dali.ybcxt.top/Article/details/gtjtgibrsy.html

"值: \(b)"
来源：http://dali.9152youxi.cn/Article/details/gtyslugtic.html

[T19] Swift：可选绑定
来源：http://dali.gaohongyu789.top/Article/details/gtsgnkdtll.html

if let n = opt { print(n) }
来源：http://dali.ydzc1.top/Article/details/gtvpdlhqtg.html

[T20] Swift：数组操作
来源：http://dali.hywenlv.cn/Article/details/gtfavrncuy.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.meibo888.top/Article/details/gteozoyuay.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gtdbkqffrn.html

for x in a { print(x) }
来源：http://dali.yj20258888.top/Article/details/gtczqpdzbg.html

[T22] Swift：字典
来源：http://dali.ivvv.top/Article/details/gtalskaekz.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.tianlin.xyz/Article/details/gtnphvgmay.html

[T23] Swift：函数
来源：http://dali.xziqi.cn/Article/details/gtpjcvfyfl.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.sysykeji.top/Article/details/gttxxhqobh.html

[T24] Swift：闭包
来源：http://dali.jqgfzy.top/Article/details/gtpvqlhpij.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.nanxinkj.top/Article/details/gtsjkxxeru.html

[T25] Swift：结构体
来源：http://dali.feifeiyinyue.top/Article/details/gtlwpotbtg.html

struct P { var x: Int }
来源：http://dali.chenzaomai.com/Article/details/gtxczkrafb.html

[T26] Swift：类与重写
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzerxjecj.html

class A: Base { override func f() {} }
来源：http://dali.guannengcc.top/Article/details/gtpbvxkxgt.html

[T27] Swift：错误处理
来源：http://dali.cashguo.top/Article/details/gtxrbtilcx.html

do { try f() } catch { print(error) }
来源：http://dali.hnxiangtu.top/Article/details/gtwefvgrzh.html

[T28] Swift：枚举
来源：http://dali.yangfankeji.com/Article/details/gtqxqjricq.html

enum Color { case red, green }
来源：http://dali.zhixingplan.top/Article/details/gtbfnozywt.html

[T29] Swift：guard 提前返回
来源：http://dali.yuxming.cn/Article/details/gtclwtlqst.html

guard let x = opt else { return }
来源：http://dali.yj20258.top/Article/details/gtzlbubyzj.html

[T30] Swift：协议
来源：http://dali.andypj.xyz/Article/details/gtktwivgus.html

protocol Shape { func area() -> Double }
来源：http://dali.hfpthk.cn/Article/details/gtxnzkaboh.html

[T31] Lua：Hello World
来源：http://dali.nanxuanxn.top/Article/details/gtotymlehj.html

print("Hello")
来源：http://dali.nwbrower.top/Article/details/gtnjsdwwhq.html

[T32] Lua：局部变量
来源：http://dali.zhoulong.xyz/Article/details/gtqkmyldyl.html

local a = 1
来源：http://dali.wangdashe.top/Article/details/gtjvjttslq.html

[T33] Lua：表（数组）
来源：http://dali.xuanzx.com/Article/details/gtskesfaiq.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.hfpthk.cn/Article/details/gtojvofldz.html

[T34] Lua：遍历表
来源：http://dali.zhaomingkeji.xyz/Article/details/gtujdjswnj.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.sxryk.cn/Article/details/gtkivvqpst.html

[T35] Lua：字典表
来源：http://dali.yj20258888.top/Article/details/gtynrgedps.html

local d = { a = 1 };  d.b = 2
来源：http://dali.tian-w.cn/Article/details/gtvhydsaxq.html

[T36] Lua：函数
来源：http://dali.hywenlv.cn/Article/details/gtygtzgeje.html

function add(a, b) return a + b end
来源：http://dali.pengpengdd.cyou/Article/details/gtnsiqnfli.html

[T37] Lua：字符串拼接
来源：http://dali.smart0.xyz/Article/details/gtlafsbmtm.html

"a" .. "b"
来源：http://dali.guowangkeji.top/Article/details/gtyqgfpwel.html

[T38] Lua：条件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwfgjbfty.html

if x > 0 then print("正") end
来源：http://dali.c1oappe.top/Article/details/gtcwhgadin.html

[T39] Lua：模式匹配
来源：http://dali.hammf.cn/Article/details/gtzqnuunog.html

string.find(s, "%d+")
来源：http://dali.shangyingyoupin.top/Article/details/gtfltwopoa.html

[T40] Lua：元表
来源：http://dali.jiagoushi.top/Article/details/gtrzpajhxb.html

setmetatable({}, { __index = base })
来源：http://dali.jqgfzy.top/Article/details/gtnecjfenb.html

[T41] Perl：Hello World
来源：http://dali.gaohongyu789.top/Article/details/gtojyxepjh.html

print "Hello\n";
来源：http://dali.chenlongwang.top/Article/details/gtrcsjoqtf.html

[T42] Perl：变量类型
来源：http://dali.yanxiufei.cn/Article/details/gthkmceafr.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.wangshuangyany.cn/Article/details/gtwimmhigk.html

[T43] Perl：字符串插值
来源：http://dali.dashuyun.cn/Article/details/gtimzikxbq.html

"值: $a"
来源：http://dali.fengsongda.top/Article/details/gtqhguyfdj.html

[T44] Perl：条件
来源：http://dali.guannengcc.top/Article/details/gtyvcduuod.html

if ($a > 0) { print "正"; }
来源：http://dali.gzhubu.top/Article/details/gtkqpyisbo.html

[T45] Perl：数组遍历
来源：http://dali.jianghu66.top/Article/details/gtkgqkrsdw.html

for my $x (@arr) { print $x; }
来源：http://dali.ppjwa.cn/Article/details/gtbxainlbr.html

[T46] Perl：哈希操作
来源：http://dali.guowangkeji.top/Article/details/gtnyaayjbs.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.tianlin.xyz/Article/details/gtvadzojnp.html

[T47] Perl：正则捕获
来源：http://dali.cheryme.top/Article/details/gtmsjvxthm.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtstcxzzab.html

[T48] Perl：正则替换
来源：http://dali.zhongyouzk.top/Article/details/gtasbkvrge.html

$s =~ s/old/new/g;
来源：http://dali.hnxiangtu.top/Article/details/gtsbesuiko.html

[T49] Perl：函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnisotjev.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.shangyingyoupin.top/Article/details/gtqhetcamr.html

[T50] Perl：逐行读文件
来源：http://dali.gaohongyu789.top/Article/details/gtssnnucdr.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.sysykeji.top/Article/details/gthhvfdfhl.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.xziqi.cn/Article/details/gtkozwxyfk.html

[T51] Scala：Hello World
来源：http://dali.shzxlz.cn/Article/details/gtlhclqygz.html

println("Hello")
来源：http://dali.shzxlz.cn/Article/details/gtaleekdmi.html

[T52] Scala：变量
来源：http://dali.yongpay.top/Article/details/gtpkbnfvev.html

val a = 1;  var b = 2
来源：http://dali.zhengqikj.top/Article/details/gtfoifntbb.html

[T53] Scala：字符串插值
来源：http://dali.chenjidiqi.icu/Article/details/gtzovmdwko.html

s"值: $b"
来源：http://dali.zhengqikj.top/Article/details/gtvkfobubj.html

[T54] Scala：集合映射
来源：http://dali.hywenlv.cn/Article/details/gtsxwehnev.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.kuanghao11.cn/Article/details/gtczwmhwnb.html

[T55] Scala：集合过滤
来源：http://dali.ydzc1.top/Article/details/gtemocyaps.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkfkjtxdu.html

[T56] Scala：样例类
来源：http://dali.birdmap.top/Article/details/gtahssigve.html

case class User(name: String, age: Int)
来源：http://dali.hnqzz.top/Article/details/gtaaniwbsh.html

[T57] Scala：模式匹配
来源：http://dali.hongshengwenyu.top/Article/details/gtefgzsqye.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.havefunace.top/Article/details/gtlybqgvfw.html

[T58] Scala：函数定义
来源：http://dali.snrcjt.cn/Article/details/gtaywkhivw.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zdqjudy.top/Article/details/gtheekrkuz.html

[T59] Scala：循环
来源：http://dali.gaohongyu789.top/Article/details/gtkhndpbkw.html

for (i <- 1 to 10) println(i)
来源：http://dali.tian-w.cn/Article/details/gtodkohtem.html

[T60] Scala：折叠
来源：http://dali.mhx1999.top/Article/details/gtslohwhvd.html


<!-- 参考信息 -->