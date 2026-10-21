代发 wailian999

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.hywenlv.cn/Article/details/gtkrjheagj.html

[R60] 只看 HTTP 状态码
来源：http://dali.hongshengwenyu.top/Article/details/gtampbgdau.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.xylfe.cn/Article/details/gteccgspgw.html

[R61] 磁盘占用
来源：http://dali.gaohongyu789.top/Article/details/gtwzlbelut.html

df -h;  du -sh *
来源：http://dali.gotoacloud.top/Article/details/gtpheykufy.html

[R62] 找最占空间的文件
来源：http://dali.hnqzz.top/Article/details/gtslgevxyk.html

du -ah . | sort -rh | head -10
来源：http://dali.yueranfly.top/Article/details/gtfhtkdnpt.html

[R63] 内存与进程
来源：http://dali.316326.xyz/Article/details/gthqyobcvi.html

free -h;  ps aux | grep nginx
来源：http://dali.haohaochexian.top/Article/details/gtqlsfrcgg.html

[R64] 结束进程
来源：http://dali.shzxlz.cn/Article/details/gtwewdhqzb.html

kill -9 $(pgrep -f app.py)
来源：http://dali.gaohongyu789.top/Article/details/gtmkuhleqm.html

[R65] 查看端口占用
来源：http://dali.tian-w.cn/Article/details/gtmomplipd.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.tianlin.xyz/Article/details/gtpzdlmwqj.html

[R66] 定时任务
来源：http://dali.tanke756.top/Article/details/gtxyixrckt.html

crontab -e;  crontab -l
来源：http://dali.sxryk.cn/Article/details/gtvuhwqbsd.html

[R67] 生成随机十六进制串
来源：http://dali.ehwqpu.com/Article/details/gtbclkayie.html

openssl rand -hex 16
来源：http://dali.hywenlv.cn/Article/details/gtfzcqilpn.html

[R68] 计算文件校验值
来源：http://dali.fengsongda.top/Article/details/gthxjtyjnx.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.nwbrower.top/Article/details/gtnauvgsne.html

[R69] 生成随机密码
来源：http://dali.jiagoushi.top/Article/details/gtwvcmztkh.html

head -c 16 /dev/urandom | base64
来源：http://dali.svipenyu.cn/Article/details/gtztojduih.html

[R70] 时间戳与互转
来源：http://dali.birdmap.top/Article/details/gtusojkxkf.html

date +%s;  date -d @1700000000
来源：http://dali.gaohongyu789.top/Article/details/gtxoutilyt.html

[R71] 日期格式化
来源：http://dali.nwbrower.top/Article/details/gtzozkupwh.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.316326.xyz/Article/details/gtiqgkiagh.html

[R72] 等待端口就绪
来源：http://dali.ehwqpu.com/Article/details/gtwstkrwsy.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.nanxuanxn.top/Article/details/gtoiksutyr.html

[R73] 分割大日志
来源：http://dali.shanyushiyangtech.top/Article/details/gtbvntmfap.html

split -l 1000 big.log part_
来源：http://dali.jqgufenzy.top/Article/details/gtaoqatozt.html

[R74] 批量重命名
来源：http://dali.fzhhl.top/Article/details/gtzfovolhk.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.fengsongda.top/Article/details/gttjgwzscr.html

[R75] 导出环境变量
来源：http://dali.yonumen.top/Article/details/gtfmrokuqi.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.jinghuilouyu.cn/Article/details/gtpodllzxv.html

[R76] 使用临时文件
来源：http://dali.shangyingyoupin.top/Article/details/gtgssrbuzh.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.yangfankeji.com/Article/details/gtwsivawtl.html

[R77] 读取用户输入
来源：http://dali.pengpengdd.cyou/Article/details/gtlhhmneoq.html

read -rp "请输入: " ans
来源：http://dali.xuanzx.com/Article/details/gtqbjnzcii.html

[R78] 交互式菜单
来源：http://dali.tian-w.cn/Article/details/gttijndolz.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.ywan-chungtsiang.top/Article/details/gtadrhbtvp.html

[R79] 解析命令行选项
来源：http://dali.shuidangran.top/Article/details/gtbmqtddpx.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.snrcjt.cn/Article/details/gtobmtjaof.html

[R80] 查看脚本执行耗时
来源：http://dali.sweek.top/Article/details/gtsmfjuldq.html

time ./run.sh
来源：http://dali.xuanzx.com/Article/details/gtpaitpkxx.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtftparfwy.html

S. C / C++ 专题
来源：http://dali.xinyue.icu/Article/details/gtprzjquiw.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtrwoazwgy.html

[S01] C：Hello World
来源：http://dali.cdnleiting.top/Article/details/gthxdoedhf.html

#include <stdio.h>
来源：http://dali.hongshengwenyu.top/Article/details/gtekrpkfds.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.vqdsnc.cn/Article/details/gtzhssxfvw.html

[S02] C：变量与格式化输出
来源：http://dali.zycfv.cn/Article/details/gtygnlwdam.html

int a = 10; printf("%d\n", a);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtseneftfh.html

[S03] C：读入整数
来源：http://dali.havefunace.top/Article/details/gtkmghqatm.html

int x; scanf("%d", &x);
来源：http://dali.hnqzz.top/Article/details/gtimuueejq.html

[S04] C：字符串复制
来源：http://dali.chenlongwang.top/Article/details/gtztuqujpw.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.dianchejie.cn/Article/details/gtjkzsigcl.html

[S05] C：字符串长度
来源：http://dali.ehwqpu.com/Article/details/gtnkmxfbho.html

strlen(s)
来源：http://dali.ybcxt.top/Article/details/gtkbbesgim.html

[S06] C：字符串比较
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpfscrnsc.html

strcmp(a, b) == 0
来源：http://dali.yangfankeji.com/Article/details/gtvtkpkyuw.html

[S07] C：数组遍历求和
来源：http://dali.jyoumei.cn/Article/details/gtrjvxobsq.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.nanxuanxn.top/Article/details/gtrzkwtrzo.html

[S08] C：动态内存分配与释放
来源：http://dali.redwolf501.top/Article/details/gtdhgoremg.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.cdnleiting.top/Article/details/gtyplotvqb.html

[S09] C：结构体定义与初始化
来源：http://dali.pengpengdd.cyou/Article/details/gtltojdpyv.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.yj20258.top/Article/details/gtczjatahe.html

[S10] C：指针与解引用
来源：http://dali.guowangkeji.top/Article/details/gtaosdedbo.html

int *p = &a;  *p = 5;
来源：http://dali.zhengqikj.top/Article/details/gtypbbpllz.html

[S11] C：逐行读文件
来源：http://dali.0kj1m.cn/Article/details/gtqvkuguqc.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gtgbizkpnz.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.0kj1m.cn/Article/details/gtwcxlbxnu.html

fclose(f);
来源：http://dali.fengsongda.top/Article/details/gtjlxjyzoh.html

[S12] C：写文件
来源：http://dali.jqgfzy.top/Article/details/gtimuaymgw.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.jinqigufen.top/Article/details/gtoabjqvce.html

[S13] C：宏定义
来源：http://dali.jiagoushi.top/Article/details/gtgnmdtaof.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.cdnleiting.top/Article/details/gtpmrphaiz.html

[S14] C：枚举
来源：http://dali.hysaishi.cn/Article/details/gtrtkoqtsw.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.xylfe.cn/Article/details/gtjfbbyhod.html

[S15] C：类型转换
来源：http://dali.xziqi.cn/Article/details/gtpblnsgri.html

(double) a / b
来源：http://dali.daria6918.cn/Article/details/gtmcnvsrzp.html

[S16] C：位操作置位
来源：http://dali.gaohongyu789.top/Article/details/gtlmaeviba.html

x |= (1 << 3);
来源：http://dali.hfpthk.cn/Article/details/gtkvsmmjyb.html

[S17] C：安全拼接字符串
来源：http://dali.zhongyouzk.top/Article/details/gtzvxiawsj.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.jinqigufen.top/Article/details/gtsohgrrzr.html

[S18] C：命令行参数
来源：http://dali.iojbl.cn/Article/details/gtwemrrqqf.html

int main(int argc, char **argv)
来源：http://dali.tanke756.top/Article/details/gtpgaylvzd.html

[S19] C：快速排序
来源：http://dali.zhoulong.xyz/Article/details/gtaxyddpis.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.tanke756.top/Article/details/gtwumibunm.html

[S20] C：二分查找
来源：http://dali.zycfv.cn/Article/details/gtpmekmhjp.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.xuetiantiany.cn/Article/details/gtgoddmppi.html

[S21] C：字符类别判断
来源：http://dali.svipenyu.cn/Article/details/gtcfkoqpwc.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.nanxinkj.top/Article/details/gtxcczkqfp.html

[S22] C：字符串转数字
来源：http://dali.sweek.top/Article/details/gtqsksezsr.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.cheryme.top/Article/details/gtnwwlnjxh.html

[S23] C：随机数
来源：http://dali.yueranfly.top/Article/details/gtbpymtgpu.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.hfpthk.cn/Article/details/gttqeauffd.html

[S24] C：获取本地时间
来源：http://dali.zhongyouzk.top/Article/details/gtumrjgbqh.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.chenjidiqi.icu/Article/details/gtsnywzegw.html

[S25] C：内存拷贝
来源：http://dali.ehwqpu.com/Article/details/gtcejbfnoq.html

memcpy(dst, src, n);
来源：http://dali.jinqigfzy.top/Article/details/gtzpzkeylb.html

[S26] C：内存清零
来源：http://dali.cucudq.cn/Article/details/gtjcmhwlqm.html

memset(a, 0, sizeof a);
来源：http://dali.hammf.cn/Article/details/gttczypusl.html

[S27] C：定义常量
来源：http://dali.tanke756.top/Article/details/gtmcagcfyw.html

const double PI = 3.14159;
来源：http://dali.yongpay.top/Article/details/gtftlfsswr.html

[S28] C：静态变量
来源：http://dali.yj20258.top/Article/details/gtaqxipfsg.html

static int counter = 0;
来源：http://dali.ppjwa.cn/Article/details/gtctkfbgyb.html

[S29] C：变参函数
来源：http://dali.smart0.xyz/Article/details/gtdhadiqgw.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.birdmap.top/Article/details/gtchhvyeop.html

[S30] C：头文件保护
来源：http://dali.zhengqikj.top/Article/details/gtpqjolmdk.html

#ifndef X_H
来源：http://dali.tanke756.top/Article/details/gtxwniande.html

#define X_H
来源：http://dali.andypj.xyz/Article/details/gtsqtckcro.html

#endif
来源：http://dali.hnxiangtu.top/Article/details/gtowrqirth.html

[S31] C++：Hello World
来源：http://dali.meibo888.top/Article/details/gtzzkkpfbh.html

#include <iostream>
来源：http://dali.jqgfzy.top/Article/details/gtkdnrqfcf.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtcsujipuz.html

[S32] C++：字符串
来源：http://dali.iojbl.cn/Article/details/gtyoykwepw.html

std::string s = "hi";  s += "!";
来源：http://dali.yj202588.top/Article/details/gtdfmljrus.html

[S33] C++：vector 增删
来源：http://dali.fzhhl.top/Article/details/gtwzbctqif.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.daria6918.cn/Article/details/gtzeocwnas.html

[S34] C++：遍历 vector
来源：http://dali.dianchejie.cn/Article/details/gtbpuogouk.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtqmtgtqgj.html

[S35] C++：map
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrmedxoxm.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.tianlin.xyz/Article/details/gtnqgjedas.html

[S36] C++：unordered_map
来源：http://dali.havefunace.top/Article/details/gtzvkpwucj.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.mhx1999.top/Article/details/gtgptdequm.html

[S37] C++：set
来源：http://dali.shuidangran.top/Article/details/gtcwxufsui.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhixingplan.top/Article/details/gtehrhcfdm.html

[S38] C++：排序
来源：http://dali.jinqigfzy.top/Article/details/gtlnvasfdb.html

std::sort(v.begin(), v.end());
来源：http://dali.xziqi.cn/Article/details/gtdourlamu.html

[S39] C++：自定义比较器排序
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzwklyvvn.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.hysaishi.cn/Article/details/gtrqrwpmmf.html

[S40] C++：查找元素
来源：http://dali.9152youxi.cn/Article/details/gtafjqlbpg.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.ppjwa.cn/Article/details/gtpsfebbvc.html

[S41] C++：类与构造函数
来源：http://dali.jqgfzy.top/Article/details/gthqfkrsmw.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.cqqwz.cn/Article/details/gttimvwpbd.html

[S42] C++：继承与虚函数
来源：http://dali.nanxinkj.top/Article/details/gtkqbqdwyp.html

class B : public Base { public: void f() override {} };
来源：http://dali.quarkkingdee.top/Article/details/gtdlklphiv.html

[S43] C++：智能指针
来源：http://dali.aizwys.cn/Article/details/gtbxsozmmv.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhengqikj.top/Article/details/gtiadvlsza.html

[S44] C++：引用传参
来源：http://dali.hysaishi.cn/Article/details/gtlmrqwmry.html

void inc(int &x) { ++x; }
来源：http://dali.feifeiyinyue.top/Article/details/gtafjksxrj.html

[S45] C++：lambda
来源：http://dali.haohaochexian.top/Article/details/gtxhduhsts.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.hywenlv.cn/Article/details/gtndrhbmlq.html

[S46] C++：函数模板
来源：http://dali.xziqi.cn/Article/details/gtvvutcbpi.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhoulong.xyz/Article/details/gtjfssxfhy.html

[S47] C++：结构化绑定遍历
来源：http://dali.snrcjt.cn/Article/details/gtfjkxzabg.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.cashguo.top/Article/details/gtwpeuyzcl.html

[S48] C++：逐行读文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmmqwuvdi.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.fengsongda.top/Article/details/gtubatjiny.html

while (std::getline(in, line)) { }
来源：http://dali.yueranfly.top/Article/details/gtfnlipock.html

[S49] C++：写文件
来源：http://dali.xuetiantiany.cn/Article/details/gtekdotgjq.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.jqgufenzy.top/Article/details/gtjfvyyuqd.html

[S50] C++：格式化数字
来源：http://dali.nwbrower.top/Article/details/gttpvrkptw.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.svipenyu.cn/Article/details/gtjjhrwcfo.html

[S51] C++：显式类型转换
来源：http://dali.meibo888.top/Article/details/gtyjowuudz.html

static_cast<double>(a) / b
来源：http://dali.fzhhl.top/Article/details/gtwxelyose.html

[S52] C++：const 与 noexcept
来源：http://dali.c1oappe.top/Article/details/gttakszucn.html

int size() const noexcept { return n_; }
来源：http://dali.chenzaomai.com/Article/details/gtufyhbdig.html

[S53] C++：移动语义
来源：http://dali.zhengqikj.top/Article/details/gtooyhpwrt.html

std::vector<int> w = std::move(v);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzhzfodsk.html

[S54] C++：异常处理
来源：http://dali.yj202588.top/Article/details/gtpupoixgh.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.hongshengwenyu.top/Article/details/gtevqbyxko.html

[S55] C++：结构化绑定
来源：http://dali.9152youxi.cn/Article/details/gttdeszyju.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.gaohongyu789.top/Article/details/gtfxalouzo.html

[S56] C++：optional
来源：http://dali.zycfv.cn/Article/details/gtftbdqodd.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.xylfe.cn/Article/details/gtzxgzewtx.html

[S57] C++：编译期常量
来源：http://dali.feifeiyinyue.top/Article/details/gtabkipjbq.html

constexpr int N = 10;
来源：http://dali.wangdashe.top/Article/details/gtxuuaylcd.html

[S58] C++：命名空间
来源：http://dali.hammf.cn/Article/details/gtzasdrifv.html

namespace ns { int f() { return 1; } }
来源：http://dali.gotoacloud.top/Article/details/gthpmyzugh.html

[S59] C++：静态断言
来源：http://dali.hongshengwenyu.top/Article/details/gtkxzhkpzq.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.hammf.cn/Article/details/gtolwljwps.html

[S60] C++：遍历并删除元素
来源：http://dali.zhengqikj.top/Article/details/gtlnqrjgxj.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.jqgufenzy.top/Article/details/gtpwprtglv.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtikeagzwu.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yonumen.top/Article/details/gtpkuvuwek.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtyzxvgpgq.html

[T01] Kotlin：Hello World
来源：http://dali.hnxiangtu.top/Article/details/gtybanvqex.html

println("Hello")
来源：http://dali.svipenyu.cn/Article/details/gtjtwxplhe.html

[T02] Kotlin：变量
来源：http://dali.yuxming.cn/Article/details/gtkxpokxbc.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.cheryme.top/Article/details/gtiwzzawvp.html

[T03] Kotlin：字符串模板
来源：http://dali.zhixingplan.top/Article/details/gtexwxipla.html

"值: $b"
来源：http://dali.0kj1m.cn/Article/details/gtvamyuobq.html

[T04] Kotlin：空安全
来源：http://dali.jqgfzy.top/Article/details/gtvuawggru.html

val n: String? = null;  n?.length
来源：http://dali.hywenlv.cn/Article/details/gtnsbxovpx.html

[T05] Kotlin：when 表达式
来源：http://dali.guannengcc.top/Article/details/gtrhauxbwv.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.jyoumei.cn/Article/details/gtujbffxmu.html

[T06] Kotlin：集合映射
来源：http://dali.jqgufenzy.top/Article/details/gtfzhatgco.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.jlsjyb.cn/Article/details/gtrlmlwkrr.html

[T07] Kotlin：集合过滤
来源：http://dali.havefunace.top/Article/details/gtnicntjea.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.chenjidiqi.icu/Article/details/gtykluzgld.html

[T08] Kotlin：数据类
来源：http://dali.yueranfly.top/Article/details/gtspqjbakv.html

data class User(val name: String, val age: Int)
来源：http://dali.kuanghao11.cn/Article/details/gtaiqqhphf.html

[T09] Kotlin：扩展函数
来源：http://dali.zhoulong.xyz/Article/details/gtjumtsimg.html

fun String.exclaim() = this + "!"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthxfertki.html

[T10] Kotlin：默认参数
来源：http://dali.yongpay.top/Article/details/gtlrdkbjti.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.fengsongda.top/Article/details/gtiqthtrlh.html

[T11] Kotlin：协程
来源：http://dali.gzhubu.top/Article/details/gtkoecekug.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.fengsongda.top/Article/details/gtdaajjaja.html

[T12] Kotlin：解构声明
来源：http://dali.mhx1999.top/Article/details/gtnxwzqaxz.html

val (a, b) = Pair(1, 2)
来源：http://dali.guowangkeji.top/Article/details/gtnvijrgou.html

[T13] Kotlin：只读 Map
来源：http://dali.jiagoushi.top/Article/details/gthwmyqngc.html

val m = mapOf("a" to 1)
来源：http://dali.c1oappe.top/Article/details/gtorudcjue.html

[T14] Kotlin：循环
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsryyrwaq.html

for (i in 1..10) println(i)
来源：http://dali.tian-w.cn/Article/details/gtobbhiibq.html

[T15] Kotlin：接口
来源：http://dali.ehwqpu.com/Article/details/gtserrzkiv.html

interface Shape { fun area(): Double }
来源：http://dali.ppjwa.cn/Article/details/gtfyyagyze.html

[T16] Swift：Hello World
来源：http://dali.zhaomingkeji.xyz/Article/details/gtigaphqpb.html

print("Hello")
来源：http://dali.yonumen.top/Article/details/gtevnkgxec.html

[T17] Swift：变量与常量
来源：http://dali.jiagoushi.top/Article/details/gtdvqrqdrd.html

var a = 1;  let b = 2
来源：http://dali.guowangkeji.top/Article/details/gtfejuclcr.html

[T18] Swift：字符串插值
来源：http://dali.zycfv.cn/Article/details/gtvkroxnel.html

"值: \(b)"
来源：http://dali.quarkkingdee.top/Article/details/gtwrhjxhrb.html

[T19] Swift：可选绑定
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjoumwwps.html

if let n = opt { print(n) }
来源：http://dali.yj202588.top/Article/details/gtitnebgly.html

[T20] Swift：数组操作
来源：http://dali.xuetiantiany.cn/Article/details/gtlashotpp.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.hnqzz.top/Article/details/gtkigybcsc.html

[T21] Swift：遍历
来源：http://dali.shuidangran.top/Article/details/gtkqeczybq.html

for x in a { print(x) }
来源：http://dali.jiagoushi.top/Article/details/gtflpywctc.html

[T22] Swift：字典
来源：http://dali.jqgufenzy.top/Article/details/gtomjydmtz.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhoulong.xyz/Article/details/gtfiqwudth.html

[T23] Swift：函数
来源：http://dali.gotoacloud.top/Article/details/gtutxjukzm.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.sysykeji.top/Article/details/gtgoesihrn.html

[T24] Swift：闭包
来源：http://dali.hysaishi.cn/Article/details/gtrvyxcpdi.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.yj20258888.top/Article/details/gtfodddyes.html

[T25] Swift：结构体
来源：http://dali.shanyushiyangtech.top/Article/details/gtvykytukx.html

struct P { var x: Int }
来源：http://dali.nanxuanxn.top/Article/details/gtfzhuhjla.html

[T26] Swift：类与重写
来源：http://dali.ehwqpu.com/Article/details/gtloidaago.html

class A: Base { override func f() {} }
来源：http://dali.yuanzhike.top/Article/details/gtmgmtoute.html

[T27] Swift：错误处理
来源：http://dali.xylfe.cn/Article/details/gtanqcmsvy.html

do { try f() } catch { print(error) }
来源：http://dali.haohaochexian.top/Article/details/gtzadptfkv.html

[T28] Swift：枚举
来源：http://dali.jyoumei.cn/Article/details/gtieztfyen.html

enum Color { case red, green }
来源：http://dali.zhiwuduotai.top/Article/details/gteeyokfwi.html

[T29] Swift：guard 提前返回
来源：http://dali.dianchejie.cn/Article/details/gtexoewdku.html

guard let x = opt else { return }
来源：http://dali.shuidangran.top/Article/details/gtxkumgafj.html

[T30] Swift：协议
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyzfylyaa.html

protocol Shape { func area() -> Double }
来源：http://dali.yueranfly.top/Article/details/gtydrlbicy.html

[T31] Lua：Hello World
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwacdapxn.html

print("Hello")
来源：http://dali.yonumen.top/Article/details/gtfmbbmhup.html

[T32] Lua：局部变量
来源：http://dali.xuanzx.com/Article/details/gtfmqjdnku.html

local a = 1
来源：http://dali.zhengqikj.top/Article/details/gttzuowcxs.html

[T33] Lua：表（数组）
来源：http://dali.yj20258888.top/Article/details/gtjlrnpdwl.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.jyoumei.cn/Article/details/gtcjmfdwxb.html

[T34] Lua：遍历表
来源：http://dali.yuxming.cn/Article/details/gttxrocncu.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.fzhhl.top/Article/details/gtanqqdceh.html

[T35] Lua：字典表
来源：http://dali.gotoacloud.top/Article/details/gthfhwnedw.html

local d = { a = 1 };  d.b = 2
来源：http://dali.xinyue.icu/Article/details/gtryqyomdx.html

[T36] Lua：函数
来源：http://dali.guowangkeji.top/Article/details/gtywrzdgqn.html

function add(a, b) return a + b end
来源：http://dali.zhoulong.xyz/Article/details/gtlmtpwzvb.html

[T37] Lua：字符串拼接
来源：http://dali.yuanzhike.top/Article/details/gtxwbjjapn.html

"a" .. "b"
来源：http://dali.haohaochexian.top/Article/details/gtkafmvupy.html

[T38] Lua：条件
来源：http://dali.jiagoushi.top/Article/details/gtaynrcxtj.html

if x > 0 then print("正") end
来源：http://dali.zycfv.cn/Article/details/gtlueykxhi.html

[T39] Lua：模式匹配
来源：http://dali.xuetiantiany.cn/Article/details/gtxbwejtxx.html

string.find(s, "%d+")
来源：http://dali.ywan-chungtsiang.top/Article/details/gthpxilakq.html

[T40] Lua：元表
来源：http://dali.redwolf501.top/Article/details/gtmactoifb.html

setmetatable({}, { __index = base })
来源：http://dali.nwbrower.top/Article/details/gtfhynbryx.html

[T41] Perl：Hello World
来源：http://dali.yuanzhike.top/Article/details/gtqymvqvmf.html

print "Hello\n";
来源：http://dali.zhengqikj.top/Article/details/gtfhyfvssy.html

[T42] Perl：变量类型
来源：http://dali.nanxinkj.top/Article/details/gtwpgoicna.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.hywenlv.cn/Article/details/gteszuqlmk.html

[T43] Perl：字符串插值
来源：http://dali.yangfankeji.com/Article/details/gtefsnzqle.html

"值: $a"
来源：http://dali.hammf.cn/Article/details/gtcmoyniil.html

[T44] Perl：条件
来源：http://dali.bjfxy.top/Article/details/gtnbrdskgi.html

if ($a > 0) { print "正"; }
来源：http://dali.feifeiyinyue.top/Article/details/gttylttklq.html

[T45] Perl：数组遍历
来源：http://dali.hammf.cn/Article/details/gtkgzlssrc.html

for my $x (@arr) { print $x; }
来源：http://dali.hywenlv.cn/Article/details/gticbkksdz.html

[T46] Perl：哈希操作
来源：http://dali.zhongyouzk.top/Article/details/gtdpzgmclh.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.hammf.cn/Article/details/gtfviqznui.html

[T47] Perl：正则捕获
来源：http://dali.svipenyu.cn/Article/details/gtuonnutmj.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.redwolf501.top/Article/details/gtekuuhjjj.html

[T48] Perl：正则替换
来源：http://dali.zhixingplan.top/Article/details/gtmhogmqir.html

$s =~ s/old/new/g;
来源：http://dali.sweek.top/Article/details/gtrreopirm.html

[T49] Perl：函数
来源：http://dali.0kj1m.cn/Article/details/gtfsamrxil.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.yuanzhike.top/Article/details/gtqeoxkrqx.html

[T50] Perl：逐行读文件
来源：http://dali.tanke756.top/Article/details/gtehquzyee.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.sweek.top/Article/details/gtpacgiode.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.nwbrower.top/Article/details/gtwmamummu.html

[T51] Scala：Hello World
来源：http://dali.tian-w.cn/Article/details/gtadgmocaw.html

println("Hello")
来源：http://dali.zhoulong.xyz/Article/details/gtzernfsit.html

[T52] Scala：变量
来源：http://dali.aibaodan.cn/Article/details/gtdfvsepbh.html

val a = 1;  var b = 2
来源：http://dali.zhongyouzk.top/Article/details/gtjrdukojs.html

[T53] Scala：字符串插值
来源：http://dali.316326.xyz/Article/details/gtweoumgko.html

s"值: $b"
来源：http://dali.cdnleiting.top/Article/details/gtbqpmxkwp.html

[T54] Scala：集合映射
来源：http://dali.sufxvd.cn/Article/details/gtoiheinfv.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.jlsjyb.cn/Article/details/gtfchcanmj.html

[T55] Scala：集合过滤
来源：http://dali.sufxvd.cn/Article/details/gtlelerymm.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.jlsjyb.cn/Article/details/gtebiqgrki.html

[T56] Scala：样例类
来源：http://dali.hammf.cn/Article/details/gtvytddpbj.html

case class User(name: String, age: Int)
来源：http://dali.chenjidiqi.icu/Article/details/gtyauvzoho.html

[T57] Scala：模式匹配
来源：http://dali.chenzaomai.com/Article/details/gtdtgpiqbs.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.nwbrower.top/Article/details/gthcaygrfo.html

[T58] Scala：函数定义
来源：http://dali.sufxvd.cn/Article/details/gtubquzkps.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zdqjudy.top/Article/details/gtzwfgiylo.html

[T59] Scala：循环
来源：http://dali.zdqjudy.top/Article/details/gtigqmebmu.html

for (i <- 1 to 10) println(i)
来源：http://dali.birdmap.top/Article/details/gtdcgnxoqr.html

[T60] Scala：折叠
来源：http://dali.hammf.cn/Article/details/gtudvdoffs.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.chenjidiqi.icu/Article/details/gtprgplath.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gthpjfeffm.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.sxryk.cn/Article/details/gtghbwtoho.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtigwsrzwn.html


<!-- 参考信息 -->