代发 wailian999

free -h;  ps aux | grep nginx
来源：http://dali.jianghu66.top/Article/details/gt2zmthzprp.html

[R64] 结束进程
来源：http://dali.xylfe.cn/Article/details/gt2hsfsylcn.html

kill -9 $(pgrep -f app.py)
来源：http://dali.hnxiangtu.top/Article/details/gt2ufqzjufj.html

[R65] 查看端口占用
来源：http://dali.yuxming.cn/Article/details/gt2uhkeklud.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.xylfe.cn/Article/details/gt2nyzjvsvi.html

[R66] 定时任务
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tqqnlajw.html

crontab -e;  crontab -l
来源：http://dali.yongpay.top/Article/details/gt2unarpzqy.html

[R67] 生成随机十六进制串
来源：http://dali.fengsongda.top/Article/details/gt2vhudicho.html

openssl rand -hex 16
来源：http://dali.jianghu66.top/Article/details/gt2zqsghgiz.html

[R68] 计算文件校验值
来源：http://dali.fengsongda.top/Article/details/gt2kndjweno.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.nanxuanxn.top/Article/details/gt2tujnzwlr.html

[R69] 生成随机密码
来源：http://dali.nanxuanxn.top/Article/details/gt2hkzlenvm.html

head -c 16 /dev/urandom | base64
来源：http://dali.xuanzx.com/Article/details/gt2gfbzfhte.html

[R70] 时间戳与互转
来源：http://dali.shangyingyoupin.top/Article/details/gt2dwynaaxk.html

date +%s;  date -d @1700000000
来源：http://dali.dashuyun.cn/Article/details/gt2nibpewib.html

[R71] 日期格式化
来源：http://dali.mhx1999.top/Article/details/gt2tdtuzzrz.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.yongpay.top/Article/details/gt2spwwedfa.html

[R72] 等待端口就绪
来源：http://dali.yonumen.top/Article/details/gt2cwvglmfm.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.nanxinkj.top/Article/details/gt2khsgnbkq.html

[R73] 分割大日志
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nvklopbp.html

split -l 1000 big.log part_
来源：http://dali.wangshuangyany.cn/Article/details/gt2hiobpdpd.html

[R74] 批量重命名
来源：http://dali.dashuyun.cn/Article/details/gt2qxezievu.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.sxryk.cn/Article/details/gt2tyjjlcki.html

[R75] 导出环境变量
来源：http://dali.gaohongyu789.top/Article/details/gt2nbrkdfox.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.gaohongyu789.top/Article/details/gt2rbmxrasb.html

[R76] 使用临时文件
来源：http://dali.xuanzx.com/Article/details/gt2vhuyoxzr.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.birdmap.top/Article/details/gt2echeoxtk.html

[R77] 读取用户输入
来源：http://dali.jyoumei.cn/Article/details/gt2rnhuhxwj.html

read -rp "请输入: " ans
来源：http://dali.wangshuangyany.cn/Article/details/gt2zjuhfhon.html

[R78] 交互式菜单
来源：http://dali.ydzc1.top/Article/details/gt2xmpxervz.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.vqdsnc.cn/Article/details/gt2jgfpcxcc.html

[R79] 解析命令行选项
来源：http://dali.wangdashe.top/Article/details/gt2dewxevut.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.cucudq.cn/Article/details/gt2jfbjwmfg.html

[R80] 查看脚本执行耗时
来源：http://dali.zycfv.cn/Article/details/gt2aqvsajvi.html

time ./run.sh
来源：http://dali.yueranfly.top/Article/details/gt2gheyacms.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2extpkaus.html

S. C / C++ 专题
来源：http://dali.snrcjt.cn/Article/details/gt2vkfqkznj.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2omsurazu.html

[S01] C：Hello World
来源：http://dali.guowangkeji.top/Article/details/gt2ohrlhmno.html

#include <stdio.h>
来源：http://dali.tianlin.xyz/Article/details/gt2ycjvtjct.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.jqgfzy.top/Article/details/gt2rtaruiqw.html

[S02] C：变量与格式化输出
来源：http://dali.fzhhl.top/Article/details/gt2ftrmaemn.html

int a = 10; printf("%d\n", a);
来源：http://dali.nwbrower.top/Article/details/gt2kxnpglqm.html

[S03] C：读入整数
来源：http://dali.yj20258888.top/Article/details/gt2ghndsala.html

int x; scanf("%d", &x);
来源：http://dali.dashuyun.cn/Article/details/gt2djtruzvz.html

[S04] C：字符串复制
来源：http://dali.jinghuilouyu.cn/Article/details/gt2eeqldvsi.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.vqdsnc.cn/Article/details/gt2hedyjdtc.html

[S05] C：字符串长度
来源：http://dali.gotoacloud.top/Article/details/gt2zywveaom.html

strlen(s)
来源：http://dali.xziqi.cn/Article/details/gt2reifnwmq.html

[S06] C：字符串比较
来源：http://dali.chenzaomai.com/Article/details/gt2uzlcztxa.html

strcmp(a, b) == 0
来源：http://dali.wangshuangyany.cn/Article/details/gt2wertjjtn.html

[S07] C：数组遍历求和
来源：http://dali.yj202588.top/Article/details/gt2ppnuumaq.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhoulong.xyz/Article/details/gt2mqcibzrl.html

[S08] C：动态内存分配与释放
来源：http://dali.xinyue.icu/Article/details/gt2fivjvgrk.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.cdnleiting.top/Article/details/gt2rkqgjyke.html

[S09] C：结构体定义与初始化
来源：http://dali.tianlin.xyz/Article/details/gt2dthpzrse.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.tianlin.xyz/Article/details/gt2msyykhdq.html

[S10] C：指针与解引用
来源：http://dali.0kj1m.cn/Article/details/gt2inftqajd.html

int *p = &a;  *p = 5;
来源：http://dali.hywenlv.cn/Article/details/gt2wckphgwq.html

[S11] C：逐行读文件
来源：http://dali.cheryme.top/Article/details/gt2fazkkrtj.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.snrcjt.cn/Article/details/gt2efbpweyv.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.dashuyun.cn/Article/details/gt2atshhzyv.html

fclose(f);
来源：http://dali.shuidangran.top/Article/details/gt2zoitiwrz.html

[S12] C：写文件
来源：http://dali.cucudq.cn/Article/details/gt2twyznksl.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.cashguo.top/Article/details/gt2rrrzkewz.html

[S13] C：宏定义
来源：http://dali.andypj.xyz/Article/details/gt2wmsouyno.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.svipenyu.cn/Article/details/gt2hnzrmsxn.html

[S14] C：枚举
来源：http://dali.dianchejie.cn/Article/details/gt2toszdtdy.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.guannengcc.top/Article/details/gt2bsjlrwas.html

[S15] C：类型转换
来源：http://dali.yj20258.top/Article/details/gt2ddztvluh.html

(double) a / b
来源：http://dali.pengpengdd.cyou/Article/details/gt2wlivmcor.html

[S16] C：位操作置位
来源：http://dali.andypj.xyz/Article/details/gt2fxqxwvuq.html

x |= (1 << 3);
来源：http://dali.jqgufenzy.top/Article/details/gt2cltensik.html

[S17] C：安全拼接字符串
来源：http://dali.birdmap.top/Article/details/gt2gpuxojha.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.cdnleiting.top/Article/details/gt2rahxzxlc.html

[S18] C：命令行参数
来源：http://dali.gaohongyu789.top/Article/details/gt2xpzyovgg.html

int main(int argc, char **argv)
来源：http://dali.cucudq.cn/Article/details/gt2zswdrfcc.html

[S19] C：快速排序
来源：http://dali.tianlin.xyz/Article/details/gt2ubxsqntj.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.sysykeji.top/Article/details/gt2zwjqaqqb.html

[S20] C：二分查找
来源：http://dali.c1oappe.top/Article/details/gt2tyfpcsdb.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.cdnleiting.top/Article/details/gt2jccbnrqc.html

[S21] C：字符类别判断
来源：http://dali.sysykeji.top/Article/details/gt2mpvbvoyt.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.guowangkeji.top/Article/details/gt2hajveamn.html

[S22] C：字符串转数字
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fepurdjj.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.xziqi.cn/Article/details/gt2nugtsnod.html

[S23] C：随机数
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pxhagdey.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.pengpengdd.cyou/Article/details/gt2rjdwcaej.html

[S24] C：获取本地时间
来源：http://dali.cqqwz.cn/Article/details/gt2ftngejdm.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.nwbrower.top/Article/details/gt2viggirxz.html

[S25] C：内存拷贝
来源：http://dali.cashguo.top/Article/details/gt2djzhxxdd.html

memcpy(dst, src, n);
来源：http://dali.nanxinkj.top/Article/details/gt2jqahngrp.html

[S26] C：内存清零
来源：http://dali.nwbrower.top/Article/details/gt2boofquec.html

memset(a, 0, sizeof a);
来源：http://dali.hywenlv.cn/Article/details/gt2gcmlnsbo.html

[S27] C：定义常量
来源：http://dali.pengpengdd.cyou/Article/details/gt2aghghxcx.html

const double PI = 3.14159;
来源：http://dali.xinyue.icu/Article/details/gt2upuvbkgu.html

[S28] C：静态变量
来源：http://dali.cqqwz.cn/Article/details/gt2lucrdshl.html

static int counter = 0;
来源：http://dali.zhiwuduotai.top/Article/details/gt2whqoxsjf.html

[S29] C：变参函数
来源：http://dali.sweek.top/Article/details/gt2uxbickss.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.xuetiantiany.cn/Article/details/gt2sanrvhuo.html

[S30] C：头文件保护
来源：http://dali.hywenlv.cn/Article/details/gt2ddsnubhz.html

#ifndef X_H
来源：http://dali.zhoulong.xyz/Article/details/gt2hjijooxp.html

#define X_H
来源：http://dali.hnxiangtu.top/Article/details/gt2kmmahmij.html

#endif
来源：http://dali.aizwys.cn/Article/details/gt2qexjmxnc.html

[S31] C++：Hello World
来源：http://dali.ivvv.top/Article/details/gt2otbryugp.html

#include <iostream>
来源：http://dali.yj20258888.top/Article/details/gt2hyodxfyp.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.nanxuanxn.top/Article/details/gt2uvuddxcq.html

[S32] C++：字符串
来源：http://dali.zhengqikj.top/Article/details/gt2dlprggmx.html

std::string s = "hi";  s += "!";
来源：http://dali.fzhhl.top/Article/details/gt2ywizicyp.html

[S33] C++：vector 增删
来源：http://dali.jlsjyb.cn/Article/details/gt2aludeylf.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.yueranfly.top/Article/details/gt2zqetsewy.html

[S34] C++：遍历 vector
来源：http://dali.kuanghao11.cn/Article/details/gt2pfckaeeh.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.yj20258.top/Article/details/gt2sikzmjhf.html

[S35] C++：map
来源：http://dali.daria6918.cn/Article/details/gt2mxnemqfo.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gcsedbmh.html

[S36] C++：unordered_map
来源：http://dali.ybcxt.top/Article/details/gt2aqsbhivu.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.shuidangran.top/Article/details/gt2olssjfjc.html

[S37] C++：set
来源：http://dali.yonumen.top/Article/details/gt2bfjscyju.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2gdxxppvr.html

[S38] C++：排序
来源：http://dali.cashguo.top/Article/details/gt2csttqyig.html

std::sort(v.begin(), v.end());
来源：http://dali.nanxinkj.top/Article/details/gt2oekabwxd.html

[S39] C++：自定义比较器排序
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2egerjvkk.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.chenzaomai.com/Article/details/gt2sdfrbrxl.html

[S40] C++：查找元素
来源：http://dali.chenzaomai.com/Article/details/gt2ifkgaqgd.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.gaohongyu789.top/Article/details/gt2tryawmtr.html

[S41] C++：类与构造函数
来源：http://dali.andypj.xyz/Article/details/gt2zsvljopy.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.sweek.top/Article/details/gt2yojiitbg.html

[S42] C++：继承与虚函数
来源：http://dali.yj20258.top/Article/details/gt2dzugbpcc.html

class B : public Base { public: void f() override {} };
来源：http://dali.shzxlz.cn/Article/details/gt2lhfvawbh.html

[S43] C++：智能指针
来源：http://dali.feifeiyinyue.top/Article/details/gt2lgwzuwgn.html

auto p = std::make_unique<int>(5);
来源：http://dali.yonumen.top/Article/details/gt2bzpdfted.html

[S44] C++：引用传参
来源：http://dali.pycfn.com/Article/details/gt2zimslwmy.html

void inc(int &x) { ++x; }
来源：http://dali.xziqi.cn/Article/details/gt2zvetlagl.html

[S45] C++：lambda
来源：http://dali.shanyushiyangtech.top/Article/details/gt2apxmhmiq.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.wangshuangyany.cn/Article/details/gt2spfvvxfe.html

[S46] C++：函数模板
来源：http://dali.svipenyu.cn/Article/details/gt2ezibpsan.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.fzhhl.top/Article/details/gt2upsofulz.html

[S47] C++：结构化绑定遍历
来源：http://dali.ehwqpu.com/Article/details/gt2tbrstwqo.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.gogol.net.cn/Article/details/gt2vhcfchal.html

[S48] C++：逐行读文件
来源：http://dali.guowangkeji.top/Article/details/gt2gjwnbtun.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.chenjidiqi.icu/Article/details/gt2dfmvjvua.html

while (std::getline(in, line)) { }
来源：http://dali.aizwys.cn/Article/details/gt2lcsmxrmk.html

[S49] C++：写文件
来源：http://dali.guannengcc.top/Article/details/gt2scudjkkn.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dfeooyac.html

[S50] C++：格式化数字
来源：http://dali.hfpthk.cn/Article/details/gt2sqpcyjja.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhoulong.xyz/Article/details/gt2fzcvjaen.html

[S51] C++：显式类型转换
来源：http://dali.ybcxt.top/Article/details/gt2tukvvnch.html

static_cast<double>(a) / b
来源：http://dali.ybcxt.top/Article/details/gt2kkocmcxe.html

[S52] C++：const 与 noexcept
来源：http://dali.c1oappe.top/Article/details/gt2nkscpanw.html

int size() const noexcept { return n_; }
来源：http://dali.bjfxy.top/Article/details/gt2zzddldis.html

[S53] C++：移动语义
来源：http://dali.316326.xyz/Article/details/gt2gjkfokbo.html

std::vector<int> w = std::move(v);
来源：http://dali.ppjwa.cn/Article/details/gt2mlccadxg.html

[S54] C++：异常处理
来源：http://dali.vqdsnc.cn/Article/details/gt2apmhsoqz.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xmetkyth.html

[S55] C++：结构化绑定
来源：http://dali.hnqzz.top/Article/details/gt2gbgljykr.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhixingplan.top/Article/details/gt2itomvzrq.html

[S56] C++：optional
来源：http://dali.yj202588.top/Article/details/gt2oyvhufec.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.0kj1m.cn/Article/details/gt2ntokhpks.html

[S57] C++：编译期常量
来源：http://dali.yonumen.top/Article/details/gt2kfabmamk.html

constexpr int N = 10;
来源：http://dali.yonumen.top/Article/details/gt2hqszmmqz.html

[S58] C++：命名空间
来源：http://dali.aizwys.cn/Article/details/gt2etfhwjni.html

namespace ns { int f() { return 1; } }
来源：http://dali.dianchejie.cn/Article/details/gt2ggmkqorh.html

[S59] C++：静态断言
来源：http://dali.yueranfly.top/Article/details/gt2odbbgjvo.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sjtmvmpm.html

[S60] C++：遍历并删除元素
来源：http://dali.jiagoushi.top/Article/details/gt2ixfjsncr.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jxmbxzut.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2eeaxrygo.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.cqqwz.cn/Article/details/gt2slekepld.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2alhlebvu.html

[T01] Kotlin：Hello World
来源：http://dali.nanxuanxn.top/Article/details/gt2dlxmbeha.html

println("Hello")
来源：http://dali.sysykeji.top/Article/details/gt2gsrkmapk.html

[T02] Kotlin：变量
来源：http://dali.jianghu66.top/Article/details/gt2uebfizyj.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.ybcxt.top/Article/details/gt2qlifwmxq.html

[T03] Kotlin：字符串模板
来源：http://dali.pengpengdd.cyou/Article/details/gt2pxzegzyf.html

"值: $b"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qopcypqi.html

[T04] Kotlin：空安全
来源：http://dali.xziqi.cn/Article/details/gt2eziskmaf.html

val n: String? = null;  n?.length
来源：http://dali.ybcxt.top/Article/details/gt2fqmjwavs.html

[T05] Kotlin：when 表达式
来源：http://dali.yj20258888.top/Article/details/gt2pgvrusul.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.hywenlv.cn/Article/details/gt2xwcdjknj.html

[T06] Kotlin：集合映射
来源：http://dali.yj20258.top/Article/details/gt2ysnulcuv.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.cqqwz.cn/Article/details/gt2wotcffel.html

[T07] Kotlin：集合过滤
来源：http://dali.shuidangran.top/Article/details/gt2bwzlogyp.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.chenzaomai.com/Article/details/gt2drvabutl.html

[T08] Kotlin：数据类
来源：http://dali.pengpengdd.cyou/Article/details/gt2nhcyqhbg.html

data class User(val name: String, val age: Int)
来源：http://dali.yvedp.cn/Article/details/gt2mvvgzuxr.html

[T09] Kotlin：扩展函数
来源：http://dali.sufxvd.cn/Article/details/gt2frshpknw.html

fun String.exclaim() = this + "!"
来源：http://dali.zhiwuduotai.top/Article/details/gt2cvxtjwsk.html

[T10] Kotlin：默认参数
来源：http://dali.gzhubu.top/Article/details/gt2lkqpttnp.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.yvedp.cn/Article/details/gt2qhdcplcc.html

[T11] Kotlin：协程
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pwknirbp.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.316326.xyz/Article/details/gt2yucsdqiy.html

[T12] Kotlin：解构声明
来源：http://dali.yj20258.top/Article/details/gt2pcjnmvsc.html

val (a, b) = Pair(1, 2)
来源：http://dali.haohaochexian.top/Article/details/gt2ebbgjcjz.html

[T13] Kotlin：只读 Map
来源：http://dali.cucudq.cn/Article/details/gt2gybvlmpg.html

val m = mapOf("a" to 1)
来源：http://dali.gotoacloud.top/Article/details/gt2kirckvqs.html

[T14] Kotlin：循环
来源：http://dali.andypj.xyz/Article/details/gt2ciauwtob.html

for (i in 1..10) println(i)
来源：http://dali.hnqzz.top/Article/details/gt2piplobmr.html

[T15] Kotlin：接口
来源：http://dali.ydzc1.top/Article/details/gt2zndeynhn.html

interface Shape { fun area(): Double }
来源：http://dali.xinyue.icu/Article/details/gt2stxzyrny.html

[T16] Swift：Hello World
来源：http://dali.snrcjt.cn/Article/details/gt2sizefgyo.html

print("Hello")
来源：http://dali.yj202588.top/Article/details/gt2tixfuyqd.html

[T17] Swift：变量与常量
来源：http://dali.cqqwz.cn/Article/details/gt2bknkwqky.html

var a = 1;  let b = 2
来源：http://dali.316326.xyz/Article/details/gt2rdkgoltf.html

[T18] Swift：字符串插值
来源：http://dali.hammf.cn/Article/details/gt2daybnqpk.html

"值: \(b)"
来源：http://dali.zycfv.cn/Article/details/gt2vbjjnrbi.html

[T19] Swift：可选绑定
来源：http://dali.gotoacloud.top/Article/details/gt2cwfmkhqb.html

if let n = opt { print(n) }
来源：http://dali.jqgfzy.top/Article/details/gt2nurfvfzd.html

[T20] Swift：数组操作
来源：http://dali.sufxvd.cn/Article/details/gt2hyhhcssy.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.yvedp.cn/Article/details/gt2ayrnsdzy.html

[T21] Swift：遍历
来源：http://dali.vqdsnc.cn/Article/details/gt2qrrlrahw.html

for x in a { print(x) }
来源：http://dali.smart0.xyz/Article/details/gt2akrdvqif.html

[T22] Swift：字典
来源：http://dali.hongshengwenyu.top/Article/details/gt2izohorcq.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.jlsjyb.cn/Article/details/gt2akppijab.html

[T23] Swift：函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2awuxnwps.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.aizwys.cn/Article/details/gt2jmbzdcve.html

[T24] Swift：闭包
来源：http://dali.ppjwa.cn/Article/details/gt2vxsrkzcb.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhongyouzk.top/Article/details/gt2pcxyvpvk.html

[T25] Swift：结构体
来源：http://dali.0kj1m.cn/Article/details/gt2wwabfbap.html

struct P { var x: Int }
来源：http://dali.gaohongyu789.top/Article/details/gt2ioekiqgp.html

[T26] Swift：类与重写
来源：http://dali.jiagoushi.top/Article/details/gt2xzqhalxb.html

class A: Base { override func f() {} }
来源：http://dali.redwolf501.top/Article/details/gt2esbzsurp.html

[T27] Swift：错误处理
来源：http://dali.316326.xyz/Article/details/gt2prrjhvep.html

do { try f() } catch { print(error) }
来源：http://dali.zycfv.cn/Article/details/gt2emxahgpe.html

[T28] Swift：枚举
来源：http://dali.sysykeji.top/Article/details/gt2daxvphhk.html

enum Color { case red, green }
来源：http://dali.shzxlz.cn/Article/details/gt2jedxkabg.html

[T29] Swift：guard 提前返回
来源：http://dali.wangdashe.top/Article/details/gt2rfoagmnt.html

guard let x = opt else { return }
来源：http://dali.yongpay.top/Article/details/gt2nrcooivp.html

[T30] Swift：协议
来源：http://dali.zhengqikj.top/Article/details/gt2uyjtrops.html

protocol Shape { func area() -> Double }
来源：http://dali.jyoumei.cn/Article/details/gt2florluvz.html

[T31] Lua：Hello World
来源：http://dali.haohaochexian.top/Article/details/gt2qwtxkdqz.html

print("Hello")
来源：http://dali.gaohongyu789.top/Article/details/gt2cvmciatc.html

[T32] Lua：局部变量
来源：http://dali.yj202588.top/Article/details/gt2uuykqelw.html

local a = 1
来源：http://dali.cqqwz.cn/Article/details/gt2ktzijbcq.html

[T33] Lua：表（数组）
来源：http://dali.wangshuangyany.cn/Article/details/gt2hjuougdo.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.redwolf501.top/Article/details/gt2divvkfkx.html

[T34] Lua：遍历表
来源：http://dali.hongshengwenyu.top/Article/details/gt2cwihjsla.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.jiagoushi.top/Article/details/gt2znjpuqyo.html

[T35] Lua：字典表
来源：http://dali.sxryk.cn/Article/details/gt2xoffevjr.html

local d = { a = 1 };  d.b = 2
来源：http://dali.sweek.top/Article/details/gt2unghmsgf.html

[T36] Lua：函数
来源：http://dali.ehwqpu.com/Article/details/gt2wyeizzhz.html

function add(a, b) return a + b end
来源：http://dali.jinqigfzy.top/Article/details/gt2fpkpqwkl.html

[T37] Lua：字符串拼接
来源：http://dali.cashguo.top/Article/details/gt2bjjsfswb.html

"a" .. "b"
来源：http://dali.dashuyun.cn/Article/details/gt2zqmjcddy.html

[T38] Lua：条件
来源：http://dali.zhoulong.xyz/Article/details/gt2ucnckbao.html

if x > 0 then print("正") end
来源：http://dali.aizwys.cn/Article/details/gt2fqtdlext.html

[T39] Lua：模式匹配
来源：http://dali.zhongyouzk.top/Article/details/gt2ezolqsfh.html

string.find(s, "%d+")
来源：http://dali.wangshuangyany.cn/Article/details/gt2hrpvhgfg.html

[T40] Lua：元表
来源：http://dali.wangshuangyany.cn/Article/details/gt2nnugkvvx.html

setmetatable({}, { __index = base })
来源：http://dali.zhoulong.xyz/Article/details/gt2ttougnww.html

[T41] Perl：Hello World
来源：http://dali.jiagoushi.top/Article/details/gt2uwescxkj.html

print "Hello\n";
来源：http://dali.andypj.xyz/Article/details/gt2yjuwxcox.html

[T42] Perl：变量类型
来源：http://dali.yangfankeji.com/Article/details/gt2ntodxgfe.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.xziqi.cn/Article/details/gt2sdmdtzrt.html

[T43] Perl：字符串插值
来源：http://dali.sweek.top/Article/details/gt2oxvxumzl.html

"值: $a"
来源：http://dali.yvedp.cn/Article/details/gt2dckacukl.html

[T44] Perl：条件
来源：http://dali.xuanzx.com/Article/details/gt2eimvipsj.html

if ($a > 0) { print "正"; }
来源：http://dali.zhixingplan.top/Article/details/gt2xlcltzql.html

[T45] Perl：数组遍历
来源：http://dali.wangdashe.top/Article/details/gt2gonbbhci.html

for my $x (@arr) { print $x; }
来源：http://dali.dashuyun.cn/Article/details/gt2dadqqbeb.html

[T46] Perl：哈希操作
来源：http://dali.cheryme.top/Article/details/gt2dpjakvvv.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.fengsongda.top/Article/details/gt2zttnkwti.html

[T47] Perl：正则捕获
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dzxinjkp.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.redwolf501.top/Article/details/gt2tkzfxecx.html

[T48] Perl：正则替换
来源：http://dali.tanke756.top/Article/details/gt2hfcupfkv.html

$s =~ s/old/new/g;
来源：http://dali.hammf.cn/Article/details/gt2dpabfmsq.html

[T49] Perl：函数
来源：http://dali.wangdashe.top/Article/details/gt2hngqazbn.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.pycfn.com/Article/details/gt2oanmzywb.html

[T50] Perl：逐行读文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qbvbtslk.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.hfpthk.cn/Article/details/gt2wjzxagkq.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.sxryk.cn/Article/details/gt2cumydbzk.html

[T51] Scala：Hello World
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gqkeusbd.html

println("Hello")
来源：http://dali.fzhhl.top/Article/details/gt2nvnvccdk.html

[T52] Scala：变量
来源：http://dali.guowangkeji.top/Article/details/gt2qytiipzy.html

val a = 1;  var b = 2
来源：http://dali.smart0.xyz/Article/details/gt2gwcvlhjo.html

[T53] Scala：字符串插值
来源：http://dali.ehwqpu.com/Article/details/gt2mqbuxovu.html

s"值: $b"
来源：http://dali.c1oappe.top/Article/details/gt2jzpnqpcw.html

[T54] Scala：集合映射
来源：http://dali.nwbrower.top/Article/details/gt2xtlcgtnt.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.birdmap.top/Article/details/gt2jxujdlkq.html

[T55] Scala：集合过滤
来源：http://dali.feifeiyinyue.top/Article/details/gt2gjmqdcyz.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.tian-w.cn/Article/details/gt2frqxmsxq.html

[T56] Scala：样例类
来源：http://dali.dianchejie.cn/Article/details/gt2aplpcfae.html

case class User(name: String, age: Int)
来源：http://dali.hysaishi.cn/Article/details/gt2yluwkxna.html

[T57] Scala：模式匹配
来源：http://dali.cqqwz.cn/Article/details/gt2qhnujitk.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.shzxlz.cn/Article/details/gt2celzbmcn.html

[T58] Scala：函数定义
来源：http://dali.aizwys.cn/Article/details/gt2moarhnpo.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.aizwys.cn/Article/details/gt2aicxzqdj.html

[T59] Scala：循环
来源：http://dali.xuanzx.com/Article/details/gt2oqbzcnll.html

for (i <- 1 to 10) println(i)
来源：http://dali.hongshengwenyu.top/Article/details/gt2phocplwj.html

[T60] Scala：折叠
来源：http://dali.yongpay.top/Article/details/gt2rpekqqgg.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.chenjidiqi.icu/Article/details/gt2whsyhfld.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2rzorqwwn.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.guowangkeji.top/Article/details/gt2wzrwexrq.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gt2bdhkfrae.html

[U01] Py：创建虚拟环境
来源：http://dali.zycfv.cn/Article/details/gt2ohgxumcj.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.shanyushiyangtech.top/Article/details/gt2svuywwsh.html

[U02] Py：导出 / 安装依赖
来源：http://dali.birdmap.top/Article/details/gt2twgsbsza.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.bjfxy.top/Article/details/gt2ceyxxqqy.html

[U03] Py：加载 .env 配置
来源：http://dali.xuetiantiany.cn/Article/details/gt2ltgxjgta.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.kuanghao11.cn/Article/details/gt2wxnbjuqt.html

[U04] Py：变量调试打印
来源：http://dali.xziqi.cn/Article/details/gt2kwxbesbn.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.0kj1m.cn/Article/details/gt2htpoukst.html


<!-- 参考信息 -->