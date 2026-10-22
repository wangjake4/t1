代发 wailian999

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.tian-w.cn/Article/details/gtpngsojlr.html

[R60] 只看 HTTP 状态码
来源：http://dali.tian-w.cn/Article/details/gtqbzylclz.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.svipenyu.cn/Article/details/gtrstvcsjn.html

[R61] 磁盘占用
来源：http://dali.yanxiufei.cn/Article/details/gtsngbslfy.html

df -h;  du -sh *
来源：http://dali.xuanzx.com/Article/details/gtmnysepqh.html

[R62] 找最占空间的文件
来源：http://dali.hnxiangtu.top/Article/details/gtrhwknqtq.html

du -ah . | sort -rh | head -10
来源：http://dali.cashguo.top/Article/details/gtdvseiitx.html

[R63] 内存与进程
来源：http://dali.havefunace.top/Article/details/gtuqwitngu.html

free -h;  ps aux | grep nginx
来源：http://dali.cheryme.top/Article/details/gtldchgbrr.html

[R64] 结束进程
来源：http://dali.yj202588.top/Article/details/gtwracmfgg.html

kill -9 $(pgrep -f app.py)
来源：http://dali.chenjidiqi.icu/Article/details/gtoqwtbdap.html

[R65] 查看端口占用
来源：http://dali.gaohongyu789.top/Article/details/gttiufaior.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.cheryme.top/Article/details/gtbivixunb.html

[R66] 定时任务
来源：http://dali.zdqjudy.top/Article/details/gtwmvudhha.html

crontab -e;  crontab -l
来源：http://dali.sysykeji.top/Article/details/gttbwotklw.html

[R67] 生成随机十六进制串
来源：http://dali.dianchejie.cn/Article/details/gtxujhdssf.html

openssl rand -hex 16
来源：http://dali.yj202588.top/Article/details/gtqazwphhx.html

[R68] 计算文件校验值
来源：http://dali.xuetiantiany.cn/Article/details/gtvrmedvnh.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.xinyue.icu/Article/details/gtauhmnjkk.html

[R69] 生成随机密码
来源：http://dali.hnxiangtu.top/Article/details/gtgkyjfrpn.html

head -c 16 /dev/urandom | base64
来源：http://dali.yuanzhike.top/Article/details/gtdonbsser.html

[R70] 时间戳与互转
来源：http://dali.jianghu66.top/Article/details/gtrinfxnuc.html

date +%s;  date -d @1700000000
来源：http://dali.yueranfly.top/Article/details/gtuvssnnei.html

[R71] 日期格式化
来源：http://dali.bjfxy.top/Article/details/gtqupwrwyj.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.jlsjyb.cn/Article/details/gtlvfdxegf.html

[R72] 等待端口就绪
来源：http://dali.svipenyu.cn/Article/details/gtefnztkxy.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.andypj.xyz/Article/details/gtdeouzjir.html

[R73] 分割大日志
来源：http://dali.sweek.top/Article/details/gtulzgydre.html

split -l 1000 big.log part_
来源：http://dali.zhoulong.xyz/Article/details/gtgyjhuyss.html

[R74] 批量重命名
来源：http://dali.c1oappe.top/Article/details/gtpcqqcssx.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.sweek.top/Article/details/gtazhktfhg.html

[R75] 导出环境变量
来源：http://dali.hammf.cn/Article/details/gtftidqmai.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.svipenyu.cn/Article/details/gtjryrgiwz.html

[R76] 使用临时文件
来源：http://dali.c1oappe.top/Article/details/gtzgrfpktu.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.chenlongwang.top/Article/details/gtwkgnjyxl.html

[R77] 读取用户输入
来源：http://dali.mhx1999.top/Article/details/gtwgsgswdx.html

read -rp "请输入: " ans
来源：http://dali.daria6918.cn/Article/details/gthuzevnyo.html

[R78] 交互式菜单
来源：http://dali.vqdsnc.cn/Article/details/gtnezrfyto.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhengqikj.top/Article/details/gtnsklyjjt.html

[R79] 解析命令行选项
来源：http://dali.cdnleiting.top/Article/details/gtgjapfeoj.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.yj202588.top/Article/details/gtqoxaquzy.html

[R80] 查看脚本执行耗时
来源：http://dali.cqqwz.cn/Article/details/gtlzzdwulr.html

time ./run.sh
来源：http://dali.wangshuangyany.cn/Article/details/gtcstpaipn.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtdhfwmsfw.html

S. C / C++ 专题
来源：http://dali.316326.xyz/Article/details/gtjfwoyxhb.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtdntmvmue.html

[S01] C：Hello World
来源：http://dali.hammf.cn/Article/details/gtincgflqa.html

#include <stdio.h>
来源：http://dali.vqdsnc.cn/Article/details/gtibfrxlzq.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.jianghu66.top/Article/details/gtgahkluwx.html

[S02] C：变量与格式化输出
来源：http://dali.tanke756.top/Article/details/gtuijznozh.html

int a = 10; printf("%d\n", a);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtphfibjag.html

[S03] C：读入整数
来源：http://dali.bjfxy.top/Article/details/gtgwlxicns.html

int x; scanf("%d", &x);
来源：http://dali.mhx1999.top/Article/details/gthbeysvfp.html

[S04] C：字符串复制
来源：http://dali.zhoulong.xyz/Article/details/gtlryayjiy.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.jyoumei.cn/Article/details/gtaxsoalpk.html

[S05] C：字符串长度
来源：http://dali.jinghuilouyu.cn/Article/details/gtcihgxsyr.html

strlen(s)
来源：http://dali.yueranfly.top/Article/details/gtoyepgbjh.html

[S06] C：字符串比较
来源：http://dali.jqgfzy.top/Article/details/gtbaarajfl.html

strcmp(a, b) == 0
来源：http://dali.smart0.xyz/Article/details/gttzxnpdbz.html

[S07] C：数组遍历求和
来源：http://dali.sweek.top/Article/details/gtuqcmmqtn.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.yvedp.cn/Article/details/gtvvysymtz.html

[S08] C：动态内存分配与释放
来源：http://dali.yj20258.top/Article/details/gtojmihbxa.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.tian-w.cn/Article/details/gtfwbqdpms.html

[S09] C：结构体定义与初始化
来源：http://dali.jinghuilouyu.cn/Article/details/gtfapomcrh.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.hywenlv.cn/Article/details/gtemhlqcld.html

[S10] C：指针与解引用
来源：http://dali.daria6918.cn/Article/details/gtgfmjoymh.html

int *p = &a;  *p = 5;
来源：http://dali.wangdashe.top/Article/details/gtgmikkuxp.html

[S11] C：逐行读文件
来源：http://dali.zhengqikj.top/Article/details/gtamdmrgzn.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.cdnleiting.top/Article/details/gtbbrgtoxz.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.pengpengdd.cyou/Article/details/gtkjngocis.html

fclose(f);
来源：http://dali.zhiwuduotai.top/Article/details/gtwgsyfpyr.html

[S12] C：写文件
来源：http://dali.hammf.cn/Article/details/gtwbxvgatw.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhoulong.xyz/Article/details/gtueuluyfu.html

[S13] C：宏定义
来源：http://dali.yueranfly.top/Article/details/gtflylmfgo.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.dianchejie.cn/Article/details/gtpsepsdwz.html

[S14] C：枚举
来源：http://dali.shzxlz.cn/Article/details/gtkivymrnk.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zdqjudy.top/Article/details/gtvqjiazww.html

[S15] C：类型转换
来源：http://dali.cqqwz.cn/Article/details/gtcyhrlgdb.html

(double) a / b
来源：http://dali.feifeiyinyue.top/Article/details/gtzeggsvwb.html

[S16] C：位操作置位
来源：http://dali.yanxiufei.cn/Article/details/gtswdavrnr.html

x |= (1 << 3);
来源：http://dali.nanxinkj.top/Article/details/gtfvxiyrre.html

[S17] C：安全拼接字符串
来源：http://dali.nwbrower.top/Article/details/gtbbcyaysi.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtneoravdb.html

[S18] C：命令行参数
来源：http://dali.feifeiyinyue.top/Article/details/gtfitagewa.html

int main(int argc, char **argv)
来源：http://dali.svipenyu.cn/Article/details/gtzdosgbbs.html

[S19] C：快速排序
来源：http://dali.redwolf501.top/Article/details/gttdthibsx.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.cheryme.top/Article/details/gtrqydvnpq.html

[S20] C：二分查找
来源：http://dali.hfpthk.cn/Article/details/gtwztnmdpa.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhixingplan.top/Article/details/gtedutoqgd.html

[S21] C：字符类别判断
来源：http://dali.jiagoushi.top/Article/details/gttkpcbccn.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.yongpay.top/Article/details/gtynjttxbu.html

[S22] C：字符串转数字
来源：http://dali.zhiwuduotai.top/Article/details/gtpyseceav.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.yj20258888.top/Article/details/gthnhlxmvm.html

[S23] C：随机数
来源：http://dali.gotoacloud.top/Article/details/gtucpplfsr.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.ybcxt.top/Article/details/gtuxykound.html

[S24] C：获取本地时间
来源：http://dali.shzxlz.cn/Article/details/gtsatqftsb.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.mhx1999.top/Article/details/gtmpchsqyw.html

[S25] C：内存拷贝
来源：http://dali.smart0.xyz/Article/details/gtvtlbhvyh.html

memcpy(dst, src, n);
来源：http://dali.fengsongda.top/Article/details/gtovolsqol.html

[S26] C：内存清零
来源：http://dali.yuanzhike.top/Article/details/gtdkpeqtbr.html

memset(a, 0, sizeof a);
来源：http://dali.jqgufenzy.top/Article/details/gtnihvffmo.html

[S27] C：定义常量
来源：http://dali.kuanghao11.cn/Article/details/gtajmioyxd.html

const double PI = 3.14159;
来源：http://dali.xziqi.cn/Article/details/gtlfudzege.html

[S28] C：静态变量
来源：http://dali.ppjwa.cn/Article/details/gtncareuow.html

static int counter = 0;
来源：http://dali.fengsongda.top/Article/details/gtcwrmlqii.html

[S29] C：变参函数
来源：http://dali.nanxuanxn.top/Article/details/gthaihexmb.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.gogol.net.cn/Article/details/gtscvhkydt.html

[S30] C：头文件保护
来源：http://dali.hnqzz.top/Article/details/gtvsdaxqfg.html

#ifndef X_H
来源：http://dali.jlsjyb.cn/Article/details/gtvxpbxpfv.html

#define X_H
来源：http://dali.zhengqikj.top/Article/details/gttzgzxcue.html

#endif
来源：http://dali.wangdashe.top/Article/details/gtjzeexzeh.html

[S31] C++：Hello World
来源：http://dali.9152youxi.cn/Article/details/gtnraauwnn.html

#include <iostream>
来源：http://dali.yj20258.top/Article/details/gtbqmpfnsk.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.gogol.net.cn/Article/details/gtzjimdrwf.html

[S32] C++：字符串
来源：http://dali.sweek.top/Article/details/gtfbhsduwk.html

std::string s = "hi";  s += "!";
来源：http://dali.ydzc1.top/Article/details/gtveksgqot.html

[S33] C++：vector 增删
来源：http://dali.daxiang520.top/Article/details/gtpmsnqftj.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtltubrhdr.html

[S34] C++：遍历 vector
来源：http://dali.fengsongda.top/Article/details/gtyoasrchm.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.jqgfzy.top/Article/details/gtacoqrbwe.html

[S35] C++：map
来源：http://dali.svipenyu.cn/Article/details/gtztpbiypd.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.daxiang520.top/Article/details/gtbhlcbaow.html

[S36] C++：unordered_map
来源：http://dali.yangfankeji.com/Article/details/gtmsbvgfft.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jyoumei.cn/Article/details/gtawbkywgj.html

[S37] C++：set
来源：http://dali.aibaodan.cn/Article/details/gtclubkxbx.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gtqlrugbrr.html

[S38] C++：排序
来源：http://dali.xuanzx.com/Article/details/gtnspasjtx.html

std::sort(v.begin(), v.end());
来源：http://dali.feifeiyinyue.top/Article/details/gtchzskfcv.html

[S39] C++：自定义比较器排序
来源：http://dali.svipenyu.cn/Article/details/gtdwfbddoc.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.nanxinkj.top/Article/details/gtbqoqlwrw.html

[S40] C++：查找元素
来源：http://dali.daxiang520.top/Article/details/gtjjejlkcn.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.dashuyun.cn/Article/details/gtmgblxyst.html

[S41] C++：类与构造函数
来源：http://dali.xuanzx.com/Article/details/gtlwpjnolg.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gtfygscywn.html

[S42] C++：继承与虚函数
来源：http://dali.xinyue.icu/Article/details/gtubzqcdjh.html

class B : public Base { public: void f() override {} };
来源：http://dali.hnxiangtu.top/Article/details/gtwsvbtlok.html

[S43] C++：智能指针
来源：http://dali.hnxiangtu.top/Article/details/gtlocnyzfw.html

auto p = std::make_unique<int>(5);
来源：http://dali.tanke756.top/Article/details/gtoipkmxuv.html

[S44] C++：引用传参
来源：http://dali.fengsongda.top/Article/details/gtixcoaabm.html

void inc(int &x) { ++x; }
来源：http://dali.c1oappe.top/Article/details/gtmbxoyscw.html

[S45] C++：lambda
来源：http://dali.hnxiangtu.top/Article/details/gtsuccfclf.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.fzhhl.top/Article/details/gtczmhyfwm.html

[S46] C++：函数模板
来源：http://dali.pycfn.com/Article/details/gtwsriddor.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.xinyue.icu/Article/details/gtrsmrotby.html

[S47] C++：结构化绑定遍历
来源：http://dali.jinghuilouyu.cn/Article/details/gtdmrkxvtu.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.nwbrower.top/Article/details/gttkmoyxwy.html

[S48] C++：逐行读文件
来源：http://dali.aibaodan.cn/Article/details/gtrrgoyyub.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.pengpengdd.cyou/Article/details/gtirzbesch.html

while (std::getline(in, line)) { }
来源：http://dali.smart0.xyz/Article/details/gtstszcvcp.html

[S49] C++：写文件
来源：http://dali.sysykeji.top/Article/details/gtrzvcmsoz.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.snrcjt.cn/Article/details/gtodzyskqa.html

[S50] C++：格式化数字
来源：http://dali.snrcjt.cn/Article/details/gtwdrhvoxr.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.yonumen.top/Article/details/gtlocwiqsq.html

[S51] C++：显式类型转换
来源：http://dali.sweek.top/Article/details/gtpapawrya.html

static_cast<double>(a) / b
来源：http://dali.andypj.xyz/Article/details/gtcsqkpuwl.html

[S52] C++：const 与 noexcept
来源：http://dali.yangfankeji.com/Article/details/gtgqjgzytw.html

int size() const noexcept { return n_; }
来源：http://dali.guannengcc.top/Article/details/gtbpsghcam.html

[S53] C++：移动语义
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgexlfvvt.html

std::vector<int> w = std::move(v);
来源：http://dali.cashguo.top/Article/details/gtqjedtclq.html

[S54] C++：异常处理
来源：http://dali.xuanzx.com/Article/details/gtbplygcnh.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.haohaochexian.top/Article/details/gtnzhyjrrf.html

[S55] C++：结构化绑定
来源：http://dali.ydzc1.top/Article/details/gtqiemttxj.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.gotoacloud.top/Article/details/gtjmhiafbi.html

[S56] C++：optional
来源：http://dali.0kj1m.cn/Article/details/gtzkozvocd.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.hysaishi.cn/Article/details/gtsxrxaogj.html

[S57] C++：编译期常量
来源：http://dali.dianchejie.cn/Article/details/gtcjyquvwv.html

constexpr int N = 10;
来源：http://dali.cucudq.cn/Article/details/gtbcjuwnil.html

[S58] C++：命名空间
来源：http://dali.shanyushiyangtech.top/Article/details/gtrbrxssne.html

namespace ns { int f() { return 1; } }
来源：http://dali.gotoacloud.top/Article/details/gthpogdflo.html

[S59] C++：静态断言
来源：http://dali.jqgfzy.top/Article/details/gtjdcrvlar.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.jinghuilouyu.cn/Article/details/gtwttoooli.html

[S60] C++：遍历并删除元素
来源：http://dali.andypj.xyz/Article/details/gtrjzbxsjm.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.nanxuanxn.top/Article/details/gtyrvygatv.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtyqsupaaq.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.vqdsnc.cn/Article/details/gtfopvzndq.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtyapihiuf.html

[T01] Kotlin：Hello World
来源：http://dali.guannengcc.top/Article/details/gtahohqjuw.html

println("Hello")
来源：http://dali.yonumen.top/Article/details/gtzqixycsf.html

[T02] Kotlin：变量
来源：http://dali.nwbrower.top/Article/details/gtxlxrrhfk.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxnffecli.html

[T03] Kotlin：字符串模板
来源：http://dali.guowangkeji.top/Article/details/gtvoogjeyh.html

"值: $b"
来源：http://dali.zhiwuduotai.top/Article/details/gtolmkusly.html

[T04] Kotlin：空安全
来源：http://dali.zhoulong.xyz/Article/details/gtcvtesieb.html

val n: String? = null;  n?.length
来源：http://dali.pycfn.com/Article/details/gtqilnxqyd.html

[T05] Kotlin：when 表达式
来源：http://dali.birdmap.top/Article/details/gtvsuazcbu.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.jqgufenzy.top/Article/details/gtqxlipzyw.html

[T06] Kotlin：集合映射
来源：http://dali.xuetiantiany.cn/Article/details/gtjsirjxml.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkwgxmdnt.html

[T07] Kotlin：集合过滤
来源：http://dali.hfpthk.cn/Article/details/gtkkcaciza.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhengqikj.top/Article/details/gtdxbdbmzk.html

[T08] Kotlin：数据类
来源：http://dali.vqdsnc.cn/Article/details/gtgcujqefo.html

data class User(val name: String, val age: Int)
来源：http://dali.sysykeji.top/Article/details/gtwpkwwfuc.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gtgrpwpcoj.html

fun String.exclaim() = this + "!"
来源：http://dali.yanxiufei.cn/Article/details/gtyfmabajl.html

[T10] Kotlin：默认参数
来源：http://dali.jinghuilouyu.cn/Article/details/gtmkdkzlhc.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.hywenlv.cn/Article/details/gtfxopxxde.html

[T11] Kotlin：协程
来源：http://dali.zhoulong.xyz/Article/details/gtbkzohrwb.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.yanxiufei.cn/Article/details/gtizfcnspw.html

[T12] Kotlin：解构声明
来源：http://dali.hnxiangtu.top/Article/details/gtgymipghi.html

val (a, b) = Pair(1, 2)
来源：http://dali.jlsjyb.cn/Article/details/gtxxmxogql.html

[T13] Kotlin：只读 Map
来源：http://dali.ivvv.top/Article/details/gtoxptista.html

val m = mapOf("a" to 1)
来源：http://dali.jianghu66.top/Article/details/gtphhcmlyn.html

[T14] Kotlin：循环
来源：http://dali.cucudq.cn/Article/details/gtgjnymnva.html

for (i in 1..10) println(i)
来源：http://dali.zycfv.cn/Article/details/gtnmqataqy.html

[T15] Kotlin：接口
来源：http://dali.chenjidiqi.icu/Article/details/gtaqhspdcj.html

interface Shape { fun area(): Double }
来源：http://dali.guowangkeji.top/Article/details/gtzmphsifc.html

[T16] Swift：Hello World
来源：http://dali.havefunace.top/Article/details/gtssbnhklz.html

print("Hello")
来源：http://dali.ivvv.top/Article/details/gttccpzyxe.html

[T17] Swift：变量与常量
来源：http://dali.yuanzhike.top/Article/details/gtzmioisbq.html

var a = 1;  let b = 2
来源：http://dali.zhengqikj.top/Article/details/gtwawgybar.html

[T18] Swift：字符串插值
来源：http://dali.yanxiufei.cn/Article/details/gtxlvvgigj.html

"值: \(b)"
来源：http://dali.gotoacloud.top/Article/details/gtpnrzrkpm.html

[T19] Swift：可选绑定
来源：http://dali.cqqwz.cn/Article/details/gtqngrdfei.html

if let n = opt { print(n) }
来源：http://dali.ppjwa.cn/Article/details/gtmxxomupg.html

[T20] Swift：数组操作
来源：http://dali.zhiwuduotai.top/Article/details/gtelmhwhqk.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtauhtjaqj.html

[T21] Swift：遍历
来源：http://dali.ppjwa.cn/Article/details/gtfesduqnm.html

for x in a { print(x) }
来源：http://dali.cucudq.cn/Article/details/gtzfgtajhp.html

[T22] Swift：字典
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfqdlkxqe.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.smart0.xyz/Article/details/gtwegoodsw.html

[T23] Swift：函数
来源：http://dali.iojbl.cn/Article/details/gtzhvcucfd.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.guowangkeji.top/Article/details/gtwxawlfwd.html

[T24] Swift：闭包
来源：http://dali.wangshuangyany.cn/Article/details/gtyvedepxi.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.fzhhl.top/Article/details/gtaasiiukq.html

[T25] Swift：结构体
来源：http://dali.jlsjyb.cn/Article/details/gtayrovnmq.html

struct P { var x: Int }
来源：http://dali.0kj1m.cn/Article/details/gtprsquudz.html

[T26] Swift：类与重写
来源：http://dali.jinqigufen.top/Article/details/gtxzjegwpm.html

class A: Base { override func f() {} }
来源：http://dali.zhiwuduotai.top/Article/details/gttymnapum.html

[T27] Swift：错误处理
来源：http://dali.aibaodan.cn/Article/details/gtvdgbxcae.html

do { try f() } catch { print(error) }
来源：http://dali.hammf.cn/Article/details/gtmifjzbsz.html

[T28] Swift：枚举
来源：http://dali.yuxming.cn/Article/details/gtdhhwnrsu.html

enum Color { case red, green }
来源：http://dali.guowangkeji.top/Article/details/gtnxmzhiin.html

[T29] Swift：guard 提前返回
来源：http://dali.yonumen.top/Article/details/gtvnxhbkin.html

guard let x = opt else { return }
来源：http://dali.nanxinkj.top/Article/details/gtcdwruptd.html

[T30] Swift：协议
来源：http://dali.zycfv.cn/Article/details/gtsqyzaaxs.html

protocol Shape { func area() -> Double }
来源：http://dali.yuxming.cn/Article/details/gtbomaamhi.html

[T31] Lua：Hello World
来源：http://dali.yonumen.top/Article/details/gtybrbqllt.html

print("Hello")
来源：http://dali.chenlongwang.top/Article/details/gtlyvatcuq.html

[T32] Lua：局部变量
来源：http://dali.ehwqpu.com/Article/details/gtukhyrsad.html

local a = 1
来源：http://dali.hysaishi.cn/Article/details/gtwpczzpwc.html

[T33] Lua：表（数组）
来源：http://dali.gaohongyu789.top/Article/details/gtseoydvxk.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.yvedp.cn/Article/details/gtcaillrwo.html

[T34] Lua：遍历表
来源：http://dali.vqdsnc.cn/Article/details/gtukwtmewg.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.wangdashe.top/Article/details/gtgrqabtto.html

[T35] Lua：字典表
来源：http://dali.gzhubu.top/Article/details/gtadfygfrs.html

local d = { a = 1 };  d.b = 2
来源：http://dali.xinyue.icu/Article/details/gtlpxueqix.html

[T36] Lua：函数
来源：http://dali.pengpengdd.cyou/Article/details/gtsgkumbmh.html

function add(a, b) return a + b end
来源：http://dali.havefunace.top/Article/details/gtyvpmofiv.html

[T37] Lua：字符串拼接
来源：http://dali.tian-w.cn/Article/details/gthkkoltga.html

"a" .. "b"
来源：http://dali.cashguo.top/Article/details/gtoumrggnf.html

[T38] Lua：条件
来源：http://dali.yongpay.top/Article/details/gtdnsijeco.html

if x > 0 then print("正") end
来源：http://dali.mhx1999.top/Article/details/gtjjngqcft.html

[T39] Lua：模式匹配
来源：http://dali.chenzaomai.com/Article/details/gtlsdivyxj.html

string.find(s, "%d+")
来源：http://dali.nanxinkj.top/Article/details/gtknwlfvsn.html

[T40] Lua：元表
来源：http://dali.yanxiufei.cn/Article/details/gtjzpszltv.html

setmetatable({}, { __index = base })
来源：http://dali.guowangkeji.top/Article/details/gtuyujhtud.html

[T41] Perl：Hello World
来源：http://dali.yj202588.top/Article/details/gtgwcevpjc.html

print "Hello\n";
来源：http://dali.svipenyu.cn/Article/details/gtoxoklyid.html

[T42] Perl：变量类型
来源：http://dali.hnxiangtu.top/Article/details/gtzqdbwgri.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.shanyushiyangtech.top/Article/details/gtjstqptea.html

[T43] Perl：字符串插值
来源：http://dali.aizwys.cn/Article/details/gtcmpovpvp.html

"值: $a"
来源：http://dali.iojbl.cn/Article/details/gtbswjztvv.html

[T44] Perl：条件
来源：http://dali.hongshengwenyu.top/Article/details/gtcxtsffch.html

if ($a > 0) { print "正"; }
来源：http://dali.haohaochexian.top/Article/details/gtgnruhbro.html

[T45] Perl：数组遍历
来源：http://dali.yangfankeji.com/Article/details/gtimabkxlv.html

for my $x (@arr) { print $x; }
来源：http://dali.yongpay.top/Article/details/gtjjmywxmq.html

[T46] Perl：哈希操作
来源：http://dali.gogol.net.cn/Article/details/gtnaruvakj.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.gotoacloud.top/Article/details/gtcalqueya.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gtygavsdtk.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkwxcswle.html

[T48] Perl：正则替换
来源：http://dali.hfpthk.cn/Article/details/gtqseulmdt.html

$s =~ s/old/new/g;
来源：http://dali.andypj.xyz/Article/details/gtfwttjrep.html

[T49] Perl：函数
来源：http://dali.cheryme.top/Article/details/gtgeilynrc.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.sufxvd.cn/Article/details/gtverdwqvg.html

[T50] Perl：逐行读文件
来源：http://dali.jqgfzy.top/Article/details/gtslnvvnum.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.tianlin.xyz/Article/details/gtyglzprco.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zycfv.cn/Article/details/gtlegtmcvp.html

[T51] Scala：Hello World
来源：http://dali.gaohongyu789.top/Article/details/gtxkijqatc.html

println("Hello")
来源：http://dali.feifeiyinyue.top/Article/details/gtntlxdphf.html

[T52] Scala：变量
来源：http://dali.fengsongda.top/Article/details/gtjyowvgbx.html

val a = 1;  var b = 2
来源：http://dali.xziqi.cn/Article/details/gtnbbeowrh.html

[T53] Scala：字符串插值
来源：http://dali.yongpay.top/Article/details/gtaarndsek.html

s"值: $b"
来源：http://dali.yj20258888.top/Article/details/gtyajtnoym.html

[T54] Scala：集合映射
来源：http://dali.yanxiufei.cn/Article/details/gtyhxchnfo.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.xylfe.cn/Article/details/gtpliyybkg.html

[T55] Scala：集合过滤
来源：http://dali.316326.xyz/Article/details/gthqyydgor.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.fzhhl.top/Article/details/gtfppgaqrt.html

[T56] Scala：样例类
来源：http://dali.hnxiangtu.top/Article/details/gtlubpbhiv.html

case class User(name: String, age: Int)
来源：http://dali.hywenlv.cn/Article/details/gtbesnyrti.html

[T57] Scala：模式匹配
来源：http://dali.snrcjt.cn/Article/details/gtzkoxvvpm.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.birdmap.top/Article/details/gteegafnvg.html

[T58] Scala：函数定义
来源：http://dali.xinyue.icu/Article/details/gtbhuslpzo.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.ybcxt.top/Article/details/gtxwnccmny.html

[T59] Scala：循环
来源：http://dali.tanke756.top/Article/details/gtuaiqkyud.html

for (i <- 1 to 10) println(i)
来源：http://dali.dianchejie.cn/Article/details/gthsvfcbsg.html

[T60] Scala：折叠
来源：http://dali.9152youxi.cn/Article/details/gtcrbpvvnm.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.birdmap.top/Article/details/gtdlworbpd.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtczvgxygs.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.cdnleiting.top/Article/details/gttkhlxdln.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtxxezoofg.html


<!-- 参考信息 -->