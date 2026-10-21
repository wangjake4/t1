代发 wailian999

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.bjfxy.top/Article/details/gtxqrjxtdn.html

[R60] 只看 HTTP 状态码
来源：http://dali.cdnleiting.top/Article/details/gtkrfdhdys.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.ybcxt.top/Article/details/gtyqgxuiwz.html

[R61] 磁盘占用
来源：http://dali.mhx1999.top/Article/details/gtqsnjtqrr.html

df -h;  du -sh *
来源：http://dali.iojbl.cn/Article/details/gtlkwxtpbj.html

[R62] 找最占空间的文件
来源：http://dali.hammf.cn/Article/details/gtgszlrsxs.html

du -ah . | sort -rh | head -10
来源：http://dali.zhongyouzk.top/Article/details/gtjvflnyql.html

[R63] 内存与进程
来源：http://dali.aizwys.cn/Article/details/gtmocsdrbh.html

free -h;  ps aux | grep nginx
来源：http://dali.svipenyu.cn/Article/details/gturegxqrj.html

[R64] 结束进程
来源：http://dali.ivvv.top/Article/details/gthyekzeko.html

kill -9 $(pgrep -f app.py)
来源：http://dali.ydzc1.top/Article/details/gtehqaqemi.html

[R65] 查看端口占用
来源：http://dali.sysykeji.top/Article/details/gtkjzfmncg.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.yueranfly.top/Article/details/gttjauyadi.html

[R66] 定时任务
来源：http://dali.zhongyouzk.top/Article/details/gtghbllyxp.html

crontab -e;  crontab -l
来源：http://dali.0kj1m.cn/Article/details/gtppoihblu.html

[R67] 生成随机十六进制串
来源：http://dali.aizwys.cn/Article/details/gtquukvqmp.html

openssl rand -hex 16
来源：http://dali.ydzc1.top/Article/details/gtlznfrkpg.html

[R68] 计算文件校验值
来源：http://dali.gogol.net.cn/Article/details/gtghccbfrb.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.xuetiantiany.cn/Article/details/gtnylqqqys.html

[R69] 生成随机密码
来源：http://dali.nwbrower.top/Article/details/gtuwdvwchd.html

head -c 16 /dev/urandom | base64
来源：http://dali.meibo888.top/Article/details/gtawybxmcj.html

[R70] 时间戳与互转
来源：http://dali.zhoulong.xyz/Article/details/gtmrygcnxm.html

date +%s;  date -d @1700000000
来源：http://dali.zhongyouzk.top/Article/details/gtryfxcnic.html

[R71] 日期格式化
来源：http://dali.cdnleiting.top/Article/details/gtmaxmrwsb.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.cashguo.top/Article/details/gtzrleapae.html

[R72] 等待端口就绪
来源：http://dali.quarkkingdee.top/Article/details/gtuhouskuh.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.jinqigfzy.top/Article/details/gtbwxvxlis.html

[R73] 分割大日志
来源：http://dali.nwbrower.top/Article/details/gtqevaywli.html

split -l 1000 big.log part_
来源：http://dali.xuetiantiany.cn/Article/details/gtutyluzqz.html

[R74] 批量重命名
来源：http://dali.jianghu66.top/Article/details/gtuggepiii.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.sxryk.cn/Article/details/gttrtgjifx.html

[R75] 导出环境变量
来源：http://dali.wangshuangyany.cn/Article/details/gtchjcbgtf.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.c1oappe.top/Article/details/gtzsjvvfou.html

[R76] 使用临时文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpfwtaroi.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.chenzaomai.com/Article/details/gtkwckzoug.html

[R77] 读取用户输入
来源：http://dali.xuetiantiany.cn/Article/details/gtxsebwiwg.html

read -rp "请输入: " ans
来源：http://dali.nwbrower.top/Article/details/gtohhfjwer.html

[R78] 交互式菜单
来源：http://dali.snrcjt.cn/Article/details/gtpzbblrso.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.chenzaomai.com/Article/details/gtbgrddoxa.html

[R79] 解析命令行选项
来源：http://dali.chenjidiqi.icu/Article/details/gtzmaphuob.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.yangfankeji.com/Article/details/gtkisefmme.html

[R80] 查看脚本执行耗时
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtinaxodrh.html

time ./run.sh
来源：http://dali.fzhhl.top/Article/details/gtgzajrtma.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtzsezjktl.html

S. C / C++ 专题
来源：http://dali.shzxlz.cn/Article/details/gtwypklqsh.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtjeijfzci.html

[S01] C：Hello World
来源：http://dali.gogol.net.cn/Article/details/gtlhjxuuov.html

#include <stdio.h>
来源：http://dali.meibo888.top/Article/details/gtlknlizux.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhixingplan.top/Article/details/gtpisilwih.html

[S02] C：变量与格式化输出
来源：http://dali.zhiwuduotai.top/Article/details/gtixfvyyhi.html

int a = 10; printf("%d\n", a);
来源：http://dali.mhx1999.top/Article/details/gtdlnvienk.html

[S03] C：读入整数
来源：http://dali.316326.xyz/Article/details/gthkmmqvzr.html

int x; scanf("%d", &x);
来源：http://dali.ybcxt.top/Article/details/gtkkynqknf.html

[S04] C：字符串复制
来源：http://dali.wangshuangyany.cn/Article/details/gtuiwoudls.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.xinyue.icu/Article/details/gtsnuhjzqr.html

[S05] C：字符串长度
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcikbfexk.html

strlen(s)
来源：http://dali.ehwqpu.com/Article/details/gtpkidvkav.html

[S06] C：字符串比较
来源：http://dali.wangshuangyany.cn/Article/details/gtifslfiri.html

strcmp(a, b) == 0
来源：http://dali.yvedp.cn/Article/details/gtfkiiacag.html

[S07] C：数组遍历求和
来源：http://dali.mhx1999.top/Article/details/gtqwlqhozh.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.9152youxi.cn/Article/details/gtkrztyidq.html

[S08] C：动态内存分配与释放
来源：http://dali.jlsjyb.cn/Article/details/gtzmktrhms.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.ppjwa.cn/Article/details/gtypytnmqv.html

[S09] C：结构体定义与初始化
来源：http://dali.dashuyun.cn/Article/details/gtxgzlhtkg.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.jqgfzy.top/Article/details/gtloawbtdy.html

[S10] C：指针与解引用
来源：http://dali.vqdsnc.cn/Article/details/gtnwyamhvu.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gtobxkyufv.html

[S11] C：逐行读文件
来源：http://dali.havefunace.top/Article/details/gtdxwlnglc.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.daxiang520.top/Article/details/gtyyxhznoh.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.feifeiyinyue.top/Article/details/gtuwhehnlu.html

fclose(f);
来源：http://dali.ybcxt.top/Article/details/gtihvmrokd.html

[S12] C：写文件
来源：http://dali.pengpengdd.cyou/Article/details/gtktkppsyi.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhoulong.xyz/Article/details/gtsqfrzwmn.html

[S13] C：宏定义
来源：http://dali.gaohongyu789.top/Article/details/gtipvrupbt.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.chenlongwang.top/Article/details/gtasdqtzxy.html

[S14] C：枚举
来源：http://dali.guannengcc.top/Article/details/gtvqwqamgl.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.hywenlv.cn/Article/details/gtcjhjjfyl.html

[S15] C：类型转换
来源：http://dali.cqqwz.cn/Article/details/gtrtaqtlhu.html

(double) a / b
来源：http://dali.yangfankeji.com/Article/details/gtzsjsiery.html

[S16] C：位操作置位
来源：http://dali.tian-w.cn/Article/details/gticmnboor.html

x |= (1 << 3);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaeqyapjd.html

[S17] C：安全拼接字符串
来源：http://dali.ybcxt.top/Article/details/gtvnnymqrz.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.hysaishi.cn/Article/details/gtykupdwip.html

[S18] C：命令行参数
来源：http://dali.bjfxy.top/Article/details/gtkenxtjzt.html

int main(int argc, char **argv)
来源：http://dali.chenzaomai.com/Article/details/gtfwhtuhhh.html

[S19] C：快速排序
来源：http://dali.xylfe.cn/Article/details/gtvcpykiiw.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.yvedp.cn/Article/details/gtplvcqosp.html

[S20] C：二分查找
来源：http://dali.cqqwz.cn/Article/details/gtwfjdcgub.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.guannengcc.top/Article/details/gtcfeaigzz.html

[S21] C：字符类别判断
来源：http://dali.yangfankeji.com/Article/details/gtdwjmjtuo.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.ywan-chungtsiang.top/Article/details/gttwdmnpyk.html

[S22] C：字符串转数字
来源：http://dali.chenzaomai.com/Article/details/gtoxznsvdc.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.gaohongyu789.top/Article/details/gtepnixqxt.html

[S23] C：随机数
来源：http://dali.sysykeji.top/Article/details/gtidnezpos.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.jinqigufen.top/Article/details/gtqbcsexxw.html

[S24] C：获取本地时间
来源：http://dali.fzhhl.top/Article/details/gtcdqvemny.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.yonumen.top/Article/details/gtrucgbhct.html

[S25] C：内存拷贝
来源：http://dali.daxiang520.top/Article/details/gtrednwtse.html

memcpy(dst, src, n);
来源：http://dali.gogol.net.cn/Article/details/gtadyynqcf.html

[S26] C：内存清零
来源：http://dali.ybcxt.top/Article/details/gtndjtmlys.html

memset(a, 0, sizeof a);
来源：http://dali.xziqi.cn/Article/details/gthybuhqui.html

[S27] C：定义常量
来源：http://dali.316326.xyz/Article/details/gtposkpfaw.html

const double PI = 3.14159;
来源：http://dali.ybcxt.top/Article/details/gtjfmdnrrw.html

[S28] C：静态变量
来源：http://dali.cqqwz.cn/Article/details/gtreqkayrk.html

static int counter = 0;
来源：http://dali.ehwqpu.com/Article/details/gtyeaoxfpy.html

[S29] C：变参函数
来源：http://dali.aibaodan.cn/Article/details/gtprpnjnig.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.pengpengdd.cyou/Article/details/gtmvthyurw.html

[S30] C：头文件保护
来源：http://dali.zhengqikj.top/Article/details/gtafshtvrq.html

#ifndef X_H
来源：http://dali.0kj1m.cn/Article/details/gtxgmlbxcr.html

#define X_H
来源：http://dali.zhengqikj.top/Article/details/gtwzecplgf.html

#endif
来源：http://dali.birdmap.top/Article/details/gtrinkekog.html

[S31] C++：Hello World
来源：http://dali.jinqigufen.top/Article/details/gtoadcsuom.html

#include <iostream>
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmhoozdjx.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.jqgufenzy.top/Article/details/gtopvxugwq.html

[S32] C++：字符串
来源：http://dali.iojbl.cn/Article/details/gtuistrdjx.html

std::string s = "hi";  s += "!";
来源：http://dali.shangyingyoupin.top/Article/details/gtafsajlgl.html

[S33] C++：vector 增删
来源：http://dali.pycfn.com/Article/details/gtogcgzqdw.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.jlsjyb.cn/Article/details/gtfoxsddtq.html

[S34] C++：遍历 vector
来源：http://dali.hnqzz.top/Article/details/gtlcmurhtm.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.9152youxi.cn/Article/details/gtkqfqbbwu.html

[S35] C++：map
来源：http://dali.aizwys.cn/Article/details/gtambknqeg.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.nanxinkj.top/Article/details/gttsadpxck.html

[S36] C++：unordered_map
来源：http://dali.smart0.xyz/Article/details/gtcapxkkot.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.mhx1999.top/Article/details/gtdmibsgrp.html

[S37] C++：set
来源：http://dali.zhiwuduotai.top/Article/details/gtjpoprdxv.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.cdnleiting.top/Article/details/gtnlseiylw.html

[S38] C++：排序
来源：http://dali.316326.xyz/Article/details/gtfqgazqvx.html

std::sort(v.begin(), v.end());
来源：http://dali.bjfxy.top/Article/details/gtfjzeehfc.html

[S39] C++：自定义比较器排序
来源：http://dali.jiagoushi.top/Article/details/gtcnuylzht.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.cdnleiting.top/Article/details/gtoabtidem.html

[S40] C++：查找元素
来源：http://dali.vqdsnc.cn/Article/details/gtaxcbpglx.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.cashguo.top/Article/details/gthnprxpph.html

[S41] C++：类与构造函数
来源：http://dali.xziqi.cn/Article/details/gtevtmknlu.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.guannengcc.top/Article/details/gtfejtjvlu.html

[S42] C++：继承与虚函数
来源：http://dali.wangdashe.top/Article/details/gtaehlljnd.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhixingplan.top/Article/details/gthephqcrm.html

[S43] C++：智能指针
来源：http://dali.ivvv.top/Article/details/gtqeikikot.html

auto p = std::make_unique<int>(5);
来源：http://dali.ydzc1.top/Article/details/gtfywweyna.html

[S44] C++：引用传参
来源：http://dali.9152youxi.cn/Article/details/gttibmrwon.html

void inc(int &x) { ++x; }
来源：http://dali.shangyingyoupin.top/Article/details/gtwllujizi.html

[S45] C++：lambda
来源：http://dali.svipenyu.cn/Article/details/gtlvdtwebi.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.pengpengdd.cyou/Article/details/gthvlbrnje.html

[S46] C++：函数模板
来源：http://dali.chenzaomai.com/Article/details/gtkljunsao.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.xziqi.cn/Article/details/gtsphapncf.html

[S47] C++：结构化绑定遍历
来源：http://dali.hammf.cn/Article/details/gtnspqzzyx.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.nanxinkj.top/Article/details/gtpjefucjm.html

[S48] C++：逐行读文件
来源：http://dali.havefunace.top/Article/details/gtoaqfvein.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.daxiang520.top/Article/details/gttkdjuvbo.html

while (std::getline(in, line)) { }
来源：http://dali.yangfankeji.com/Article/details/gtokqjwagv.html

[S49] C++：写文件
来源：http://dali.sufxvd.cn/Article/details/gtzwmtvppm.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.gaohongyu789.top/Article/details/gtputabhdo.html

[S50] C++：格式化数字
来源：http://dali.birdmap.top/Article/details/gthackvglf.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zdqjudy.top/Article/details/gtynycvryn.html

[S51] C++：显式类型转换
来源：http://dali.jinqigufen.top/Article/details/gthprnrgho.html

static_cast<double>(a) / b
来源：http://dali.ivvv.top/Article/details/gtzchdchha.html

[S52] C++：const 与 noexcept
来源：http://dali.9152youxi.cn/Article/details/gtantjwlze.html

int size() const noexcept { return n_; }
来源：http://dali.cqqwz.cn/Article/details/gtwdamgdfk.html

[S53] C++：移动语义
来源：http://dali.shanyushiyangtech.top/Article/details/gtwxdupfar.html

std::vector<int> w = std::move(v);
来源：http://dali.zycfv.cn/Article/details/gttrjfjsar.html

[S54] C++：异常处理
来源：http://dali.haohaochexian.top/Article/details/gtpqjiqqsj.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.sysykeji.top/Article/details/gtrfgmdqiu.html

[S55] C++：结构化绑定
来源：http://dali.ivvv.top/Article/details/gtxozkqvun.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.hywenlv.cn/Article/details/gtxprhhiue.html

[S56] C++：optional
来源：http://dali.xylfe.cn/Article/details/gtiwsmjovr.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.gotoacloud.top/Article/details/gtvqjswvar.html

[S57] C++：编译期常量
来源：http://dali.guannengcc.top/Article/details/gtadgpyfgp.html

constexpr int N = 10;
来源：http://dali.hongshengwenyu.top/Article/details/gtvtscbhcl.html

[S58] C++：命名空间
来源：http://dali.hongshengwenyu.top/Article/details/gtpehtwttm.html

namespace ns { int f() { return 1; } }
来源：http://dali.nanxinkj.top/Article/details/gtulkxzvzi.html

[S59] C++：静态断言
来源：http://dali.cashguo.top/Article/details/gtwojchlwd.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.sufxvd.cn/Article/details/gtkmxfbwhh.html

[S60] C++：遍历并删除元素
来源：http://dali.ybcxt.top/Article/details/gthslcxltp.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.jinyuanbaomall.cn/Article/details/gttlcjgivi.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtvhdpujun.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.hywenlv.cn/Article/details/gtgsbzqsiu.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gttdodhpae.html

[T01] Kotlin：Hello World
来源：http://dali.mhx1999.top/Article/details/gtbhbzxrxc.html

println("Hello")
来源：http://dali.birdmap.top/Article/details/gtpwbvphsn.html

[T02] Kotlin：变量
来源：http://dali.jinqigufen.top/Article/details/gttbhofbwr.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.yuxming.cn/Article/details/gtzwfvwmjz.html

[T03] Kotlin：字符串模板
来源：http://dali.sysykeji.top/Article/details/gtjjrxuplg.html

"值: $b"
来源：http://dali.hywenlv.cn/Article/details/gthszvhsdl.html

[T04] Kotlin：空安全
来源：http://dali.yongpay.top/Article/details/gtcapoxksm.html

val n: String? = null;  n?.length
来源：http://dali.snrcjt.cn/Article/details/gttzufhhzp.html

[T05] Kotlin：when 表达式
来源：http://dali.nanxuanxn.top/Article/details/gteycpqfhr.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.snrcjt.cn/Article/details/gtaewvwagp.html

[T06] Kotlin：集合映射
来源：http://dali.jlsjyb.cn/Article/details/gtcmdptfmy.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.hongshengwenyu.top/Article/details/gtrtgmmdjz.html

[T07] Kotlin：集合过滤
来源：http://dali.gogol.net.cn/Article/details/gtfhbkepvv.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.daria6918.cn/Article/details/gtwketbdyj.html

[T08] Kotlin：数据类
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlwnxmssv.html

data class User(val name: String, val age: Int)
来源：http://dali.fengsongda.top/Article/details/gtoaqyufzw.html

[T09] Kotlin：扩展函数
来源：http://dali.xuanzx.com/Article/details/gtoxolnqvt.html

fun String.exclaim() = this + "!"
来源：http://dali.zdqjudy.top/Article/details/gtsqopyspz.html

[T10] Kotlin：默认参数
来源：http://dali.jianghu66.top/Article/details/gtkqkrpnve.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.sweek.top/Article/details/gtbfzpyxry.html

[T11] Kotlin：协程
来源：http://dali.zycfv.cn/Article/details/gttvryzuhi.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.havefunace.top/Article/details/gtlahvtngq.html

[T12] Kotlin：解构声明
来源：http://dali.snrcjt.cn/Article/details/gtfjojnajy.html

val (a, b) = Pair(1, 2)
来源：http://dali.xuanzx.com/Article/details/gthrrwsgxs.html

[T13] Kotlin：只读 Map
来源：http://dali.sufxvd.cn/Article/details/gtcocisvub.html

val m = mapOf("a" to 1)
来源：http://dali.daxiang520.top/Article/details/gtxeuyqfee.html

[T14] Kotlin：循环
来源：http://dali.aizwys.cn/Article/details/gtmockdamf.html

for (i in 1..10) println(i)
来源：http://dali.jlsjyb.cn/Article/details/gtzkwmpqxz.html

[T15] Kotlin：接口
来源：http://dali.hongshengwenyu.top/Article/details/gtijdkmnkz.html

interface Shape { fun area(): Double }
来源：http://dali.jinqigufen.top/Article/details/gtqhswklap.html

[T16] Swift：Hello World
来源：http://dali.fzhhl.top/Article/details/gtqkwzkooq.html

print("Hello")
来源：http://dali.zhengqikj.top/Article/details/gtuqgkqgcp.html

[T17] Swift：变量与常量
来源：http://dali.hongshengwenyu.top/Article/details/gthqtyjtua.html

var a = 1;  let b = 2
来源：http://dali.ybcxt.top/Article/details/gtsihujopu.html

[T18] Swift：字符串插值
来源：http://dali.birdmap.top/Article/details/gtlccbdhfu.html

"值: \(b)"
来源：http://dali.yangfankeji.com/Article/details/gtdhvssivk.html

[T19] Swift：可选绑定
来源：http://dali.bjfxy.top/Article/details/gtecshmzbk.html

if let n = opt { print(n) }
来源：http://dali.yj20258.top/Article/details/gtcjujznyh.html

[T20] Swift：数组操作
来源：http://dali.yangfankeji.com/Article/details/gtbxgilgxx.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbmszekvp.html

[T21] Swift：遍历
来源：http://dali.tian-w.cn/Article/details/gtdbtuspwc.html

for x in a { print(x) }
来源：http://dali.jinqigfzy.top/Article/details/gtwnutfupm.html

[T22] Swift：字典
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkutczhos.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.chenjidiqi.icu/Article/details/gtqkjfimok.html

[T23] Swift：函数
来源：http://dali.sufxvd.cn/Article/details/gtyqygptel.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.vqdsnc.cn/Article/details/gttarvvtzb.html

[T24] Swift：闭包
来源：http://dali.yj20258888.top/Article/details/gtxhczxqjk.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.316326.xyz/Article/details/gteajxbixv.html

[T25] Swift：结构体
来源：http://dali.cheryme.top/Article/details/gtskgugfiz.html

struct P { var x: Int }
来源：http://dali.xuanzx.com/Article/details/gtkmvgyoht.html

[T26] Swift：类与重写
来源：http://dali.yuxming.cn/Article/details/gtacorxuhl.html

class A: Base { override func f() {} }
来源：http://dali.yueranfly.top/Article/details/gtejsfdaho.html

[T27] Swift：错误处理
来源：http://dali.haohaochexian.top/Article/details/gtfesniyjo.html

do { try f() } catch { print(error) }
来源：http://dali.jqgufenzy.top/Article/details/gtxlgwopfy.html

[T28] Swift：枚举
来源：http://dali.pycfn.com/Article/details/gtsychvqjp.html

enum Color { case red, green }
来源：http://dali.nanxinkj.top/Article/details/gttwcuccfg.html

[T29] Swift：guard 提前返回
来源：http://dali.kuanghao11.cn/Article/details/gtjpgkpyda.html

guard let x = opt else { return }
来源：http://dali.hnqzz.top/Article/details/gtrsxczvyr.html

[T30] Swift：协议
来源：http://dali.wangshuangyany.cn/Article/details/gtpwzhhdok.html

protocol Shape { func area() -> Double }
来源：http://dali.fengsongda.top/Article/details/gtreldtikg.html

[T31] Lua：Hello World
来源：http://dali.aizwys.cn/Article/details/gtaoxnjvrb.html

print("Hello")
来源：http://dali.bjfxy.top/Article/details/gtfpxykdmh.html

[T32] Lua：局部变量
来源：http://dali.0kj1m.cn/Article/details/gtuiqtjaiu.html

local a = 1
来源：http://dali.jqgfzy.top/Article/details/gtwyltbmfu.html

[T33] Lua：表（数组）
来源：http://dali.zhoulong.xyz/Article/details/gtrpmpnwhw.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.fengsongda.top/Article/details/gtbfcftzmf.html

[T34] Lua：遍历表
来源：http://dali.zdqjudy.top/Article/details/gtequosqop.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.jinqigfzy.top/Article/details/gtrapxwssn.html

[T35] Lua：字典表
来源：http://dali.pengpengdd.cyou/Article/details/gtmgsrjapi.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhongyouzk.top/Article/details/gtsdpgmbqq.html

[T36] Lua：函数
来源：http://dali.mhx1999.top/Article/details/gtxomjqndi.html

function add(a, b) return a + b end
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgpxmjgtw.html

[T37] Lua：字符串拼接
来源：http://dali.gaohongyu789.top/Article/details/gtyfcehchq.html

"a" .. "b"
来源：http://dali.xziqi.cn/Article/details/gtbwxfwxjr.html

[T38] Lua：条件
来源：http://dali.shanyushiyangtech.top/Article/details/gtaddcobde.html

if x > 0 then print("正") end
来源：http://dali.birdmap.top/Article/details/gtdnlnmabo.html

[T39] Lua：模式匹配
来源：http://dali.andypj.xyz/Article/details/gtvtfdupjl.html

string.find(s, "%d+")
来源：http://dali.hongshengwenyu.top/Article/details/gtxywhuuim.html

[T40] Lua：元表
来源：http://dali.jinqigfzy.top/Article/details/gtigmmnmqz.html

setmetatable({}, { __index = base })
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgemvpcxs.html

[T41] Perl：Hello World
来源：http://dali.wangdashe.top/Article/details/gttibfdpso.html

print "Hello\n";
来源：http://dali.vqdsnc.cn/Article/details/gtzworxmnj.html

[T42] Perl：变量类型
来源：http://dali.wangshuangyany.cn/Article/details/gtzlausnai.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.gzhubu.top/Article/details/gtevpoqvhz.html

[T43] Perl：字符串插值
来源：http://dali.sweek.top/Article/details/gtowbrjhog.html

"值: $a"
来源：http://dali.pengpengdd.cyou/Article/details/gtmrlncshi.html

[T44] Perl：条件
来源：http://dali.xziqi.cn/Article/details/gtanhhadad.html

if ($a > 0) { print "正"; }
来源：http://dali.aibaodan.cn/Article/details/gtduguaihc.html

[T45] Perl：数组遍历
来源：http://dali.yangfankeji.com/Article/details/gtlkahckot.html

for my $x (@arr) { print $x; }
来源：http://dali.wangshuangyany.cn/Article/details/gtfwiieazi.html

[T46] Perl：哈希操作
来源：http://dali.fzhhl.top/Article/details/gtokocipuo.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.daria6918.cn/Article/details/gtwuthslwn.html

[T47] Perl：正则捕获
来源：http://dali.xziqi.cn/Article/details/gtrotzypvh.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.hysaishi.cn/Article/details/gtjuwnqszp.html

[T48] Perl：正则替换
来源：http://dali.0kj1m.cn/Article/details/gthialochb.html

$s =~ s/old/new/g;
来源：http://dali.tian-w.cn/Article/details/gtbsttbcif.html

[T49] Perl：函数
来源：http://dali.sxryk.cn/Article/details/gtbstjttat.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.chenlongwang.top/Article/details/gtecwcnajb.html

[T50] Perl：逐行读文件
来源：http://dali.gzhubu.top/Article/details/gtmfpflzcn.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.jinqigfzy.top/Article/details/gtfvfpjmhn.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.jianghu66.top/Article/details/gtujzlfcpn.html

[T51] Scala：Hello World
来源：http://dali.yuxming.cn/Article/details/gtiqpydckb.html

println("Hello")
来源：http://dali.daxiang520.top/Article/details/gtbkusryyo.html

[T52] Scala：变量
来源：http://dali.havefunace.top/Article/details/gtnelrczkx.html

val a = 1;  var b = 2
来源：http://dali.wangdashe.top/Article/details/gthxcbxssl.html

[T53] Scala：字符串插值
来源：http://dali.shanyushiyangkeji.top/Article/details/gtebvykdpu.html

s"值: $b"
来源：http://dali.ybcxt.top/Article/details/gtksbuefrw.html

[T54] Scala：集合映射
来源：http://dali.gotoacloud.top/Article/details/gtbovwidmk.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.cdnleiting.top/Article/details/gtzdgmhpgm.html

[T55] Scala：集合过滤
来源：http://dali.chenjidiqi.icu/Article/details/gtjydcrdkd.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.jqgfzy.top/Article/details/gttdfrgslf.html

[T56] Scala：样例类
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuxahkxfi.html

case class User(name: String, age: Int)
来源：http://dali.zycfv.cn/Article/details/gttwhoiefs.html

[T57] Scala：模式匹配
来源：http://dali.jinqigufen.top/Article/details/gtezgxpoab.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.yj202588.top/Article/details/gtdxtisivf.html

[T58] Scala：函数定义
来源：http://dali.gzhubu.top/Article/details/gtvtjcvxui.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.jqgufenzy.top/Article/details/gtwoetcbqw.html

[T59] Scala：循环
来源：http://dali.jqgfzy.top/Article/details/gtlymnsuzm.html

for (i <- 1 to 10) println(i)
来源：http://dali.aizwys.cn/Article/details/gtozzaorqb.html

[T60] Scala：折叠
来源：http://dali.yj20258.top/Article/details/gthmadqcxi.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.shangyingyoupin.top/Article/details/gtrrhbyjre.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtqnjthtiw.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.yuxming.cn/Article/details/gtdqqwtqjj.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtzplminzg.html


<!-- 参考信息 -->