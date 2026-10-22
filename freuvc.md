代发 wailian999

ssh user@host 'uptime'
来源：http://dali.zycfv.cn/Article/details/gtrbzdkklk.html

[R58] 下载文件
来源：http://dali.shuidangran.top/Article/details/gtjmyxncfc.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.snrcjt.cn/Article/details/gtsmupaxpy.html

[R59] 发 POST JSON
来源：http://dali.yuanzhike.top/Article/details/gtvoybzayx.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.sxryk.cn/Article/details/gticmxhcxp.html

[R60] 只看 HTTP 状态码
来源：http://dali.chenjidiqi.icu/Article/details/gtpcsmidxz.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.sxryk.cn/Article/details/gtomdirvoz.html

[R61] 磁盘占用
来源：http://dali.kuanghao11.cn/Article/details/gtaksyskup.html

df -h;  du -sh *
来源：http://dali.hysaishi.cn/Article/details/gtdxibvgrg.html

[R62] 找最占空间的文件
来源：http://dali.quarkkingdee.top/Article/details/gtlmmdcvbo.html

du -ah . | sort -rh | head -10
来源：http://dali.sxryk.cn/Article/details/gtsqtpajqa.html

[R63] 内存与进程
来源：http://dali.zdqjudy.top/Article/details/gtwlhvckuq.html

free -h;  ps aux | grep nginx
来源：http://dali.jyoumei.cn/Article/details/gtzursfufc.html

[R64] 结束进程
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpzagocyo.html

kill -9 $(pgrep -f app.py)
来源：http://dali.aizwys.cn/Article/details/gtujgmmatk.html

[R65] 查看端口占用
来源：http://dali.yj20258888.top/Article/details/gtusjiggje.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.yangfankeji.com/Article/details/gtvzpodvle.html

[R66] 定时任务
来源：http://dali.sysykeji.top/Article/details/gtznzyzbew.html

crontab -e;  crontab -l
来源：http://dali.yangfankeji.com/Article/details/gtclmtufbt.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gtnjcyqxkl.html

openssl rand -hex 16
来源：http://dali.haohaochexian.top/Article/details/gtkakdxjkb.html

[R68] 计算文件校验值
来源：http://dali.svipenyu.cn/Article/details/gtuoshwqxj.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.jinghuilouyu.cn/Article/details/gtssbcjzsy.html

[R69] 生成随机密码
来源：http://dali.wangdashe.top/Article/details/gttraeobxt.html

head -c 16 /dev/urandom | base64
来源：http://dali.jlsjyb.cn/Article/details/gtkobzokbv.html

[R70] 时间戳与互转
来源：http://dali.zhixingplan.top/Article/details/gtdjcevlyt.html

date +%s;  date -d @1700000000
来源：http://dali.fzhhl.top/Article/details/gtjdsgwbon.html

[R71] 日期格式化
来源：http://dali.dianchejie.cn/Article/details/gttgwivvqu.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.ywan-chungtsiang.top/Article/details/gttubrankm.html

[R72] 等待端口就绪
来源：http://dali.svipenyu.cn/Article/details/gtlzkimvwc.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.guannengcc.top/Article/details/gtkfwssqho.html

[R73] 分割大日志
来源：http://dali.sxryk.cn/Article/details/gtaegandoi.html

split -l 1000 big.log part_
来源：http://dali.daxiang520.top/Article/details/gtynratstw.html

[R74] 批量重命名
来源：http://dali.dashuyun.cn/Article/details/gtumzteczd.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.hnqzz.top/Article/details/gthiaovgtp.html

[R75] 导出环境变量
来源：http://dali.hfpthk.cn/Article/details/gtgulvouyg.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.xziqi.cn/Article/details/gtsdurnrrv.html

[R76] 使用临时文件
来源：http://dali.fengsongda.top/Article/details/gtahslohpn.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.gaohongyu789.top/Article/details/gtusygekby.html

[R77] 读取用户输入
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnbhprokk.html

read -rp "请输入: " ans
来源：http://dali.xylfe.cn/Article/details/gtimhxymwo.html

[R78] 交互式菜单
来源：http://dali.sysykeji.top/Article/details/gthdydarik.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.chenlongwang.top/Article/details/gtjovbbsah.html

[R79] 解析命令行选项
来源：http://dali.jqgfzy.top/Article/details/gtoxbbtunc.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.jianghu66.top/Article/details/gtstpvxkxs.html

[R80] 查看脚本执行耗时
来源：http://dali.svipenyu.cn/Article/details/gteznhrtnl.html

time ./run.sh
来源：http://dali.mhx1999.top/Article/details/gtqtnsmypz.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gthznajkjh.html

S. C / C++ 专题
来源：http://dali.svipenyu.cn/Article/details/gtdwebhbbm.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtnoupgsib.html

[S01] C：Hello World
来源：http://dali.chenzaomai.com/Article/details/gtnqgitznk.html

#include <stdio.h>
来源：http://dali.nanxinkj.top/Article/details/gtbmwxnyhe.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.guowangkeji.top/Article/details/gtiaeosmuo.html

[S02] C：变量与格式化输出
来源：http://dali.yj202588.top/Article/details/gtywupazdv.html

int a = 10; printf("%d\n", a);
来源：http://dali.chenlongwang.top/Article/details/gtaoskkfxh.html

[S03] C：读入整数
来源：http://dali.jqgufenzy.top/Article/details/gtqomvysyr.html

int x; scanf("%d", &x);
来源：http://dali.sxryk.cn/Article/details/gtkqtzzxaa.html

[S04] C：字符串复制
来源：http://dali.zhongyouzk.top/Article/details/gtnsqvvvaj.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.vqdsnc.cn/Article/details/gttogcivhe.html

[S05] C：字符串长度
来源：http://dali.ydzc1.top/Article/details/gtkqblqddm.html

strlen(s)
来源：http://dali.guannengcc.top/Article/details/gtczwxzros.html

[S06] C：字符串比较
来源：http://dali.c1oappe.top/Article/details/gtqqfihjoq.html

strcmp(a, b) == 0
来源：http://dali.feifeiyinyue.top/Article/details/gtsycnawxn.html

[S07] C：数组遍历求和
来源：http://dali.fengsongda.top/Article/details/gtsxrukfqn.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.sweek.top/Article/details/gtanjnhbev.html

[S08] C：动态内存分配与释放
来源：http://dali.yonumen.top/Article/details/gtqyimqzdm.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.yongpay.top/Article/details/gtbkrajrbr.html

[S09] C：结构体定义与初始化
来源：http://dali.gaohongyu789.top/Article/details/gtvmkeskil.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.yueranfly.top/Article/details/gtqwojwltf.html

[S10] C：指针与解引用
来源：http://dali.wangshuangyany.cn/Article/details/gtcaiulyty.html

int *p = &a;  *p = 5;
来源：http://dali.nanxuanxn.top/Article/details/gtzmzgmxxb.html

[S11] C：逐行读文件
来源：http://dali.chenlongwang.top/Article/details/gtrxdtrmrl.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.jiagoushi.top/Article/details/gtdusrayha.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.quarkkingdee.top/Article/details/gtrqoscwhe.html

fclose(f);
来源：http://dali.yongpay.top/Article/details/gtgapjzvxx.html

[S12] C：写文件
来源：http://dali.zhiwuduotai.top/Article/details/gtfdoztunq.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.bjfxy.top/Article/details/gtjkptfvdk.html

[S13] C：宏定义
来源：http://dali.jianghu66.top/Article/details/gtiwqirfdj.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.meibo888.top/Article/details/gtqgexiztj.html

[S14] C：枚举
来源：http://dali.jiagoushi.top/Article/details/gtmdltkfey.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.meibo888.top/Article/details/gtopeqvddw.html

[S15] C：类型转换
来源：http://dali.yanxiufei.cn/Article/details/gtfwjplhef.html

(double) a / b
来源：http://dali.daria6918.cn/Article/details/gtuymdrtih.html

[S16] C：位操作置位
来源：http://dali.zdqjudy.top/Article/details/gtksrdrmks.html

x |= (1 << 3);
来源：http://dali.feifeiyinyue.top/Article/details/gtxpwnwfgt.html

[S17] C：安全拼接字符串
来源：http://dali.zhongyouzk.top/Article/details/gtupuesutb.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.svipenyu.cn/Article/details/gtxclopgrj.html

[S18] C：命令行参数
来源：http://dali.zhiwuduotai.top/Article/details/gtrtgzexki.html

int main(int argc, char **argv)
来源：http://dali.ybcxt.top/Article/details/gtaulignrv.html

[S19] C：快速排序
来源：http://dali.ehwqpu.com/Article/details/gtgkjoaqsi.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.redwolf501.top/Article/details/gttjaarbql.html

[S20] C：二分查找
来源：http://dali.fengsongda.top/Article/details/gteyvzshnq.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.yonumen.top/Article/details/gtmvbivvzn.html

[S21] C：字符类别判断
来源：http://dali.jqgfzy.top/Article/details/gtopgaeurj.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.0kj1m.cn/Article/details/gtqgvpptol.html

[S22] C：字符串转数字
来源：http://dali.tanke756.top/Article/details/gtqrvmxtow.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.316326.xyz/Article/details/gtwipdgrsr.html

[S23] C：随机数
来源：http://dali.gotoacloud.top/Article/details/gtlpfyktnh.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.pengpengdd.cyou/Article/details/gtcltfhoct.html

[S24] C：获取本地时间
来源：http://dali.yvedp.cn/Article/details/gtotwfdqjd.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.shanyushiyangtech.top/Article/details/gtxlrdrsok.html

[S25] C：内存拷贝
来源：http://dali.tian-w.cn/Article/details/gtucjeeoem.html

memcpy(dst, src, n);
来源：http://dali.sysykeji.top/Article/details/gtgyguvfmi.html

[S26] C：内存清零
来源：http://dali.xylfe.cn/Article/details/gtftjhtctq.html

memset(a, 0, sizeof a);
来源：http://dali.sxryk.cn/Article/details/gtzmfnufec.html

[S27] C：定义常量
来源：http://dali.quarkkingdee.top/Article/details/gtkasfjsvf.html

const double PI = 3.14159;
来源：http://dali.hongshengwenyu.top/Article/details/gtutxgkyga.html

[S28] C：静态变量
来源：http://dali.yanxiufei.cn/Article/details/gtkcjbmgas.html

static int counter = 0;
来源：http://dali.haohaochexian.top/Article/details/gtusdixwsp.html

[S29] C：变参函数
来源：http://dali.jinqigfzy.top/Article/details/gtpfpdwpfn.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.yueranfly.top/Article/details/gtitfepwde.html

[S30] C：头文件保护
来源：http://dali.fengsongda.top/Article/details/gtgbahzwhp.html

#ifndef X_H
来源：http://dali.aibaodan.cn/Article/details/gtwhgvwvnn.html

#define X_H
来源：http://dali.birdmap.top/Article/details/gtrhhcgiie.html

#endif
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyfmxxmww.html

[S31] C++：Hello World
来源：http://dali.gaohongyu789.top/Article/details/gtlitozeku.html

#include <iostream>
来源：http://dali.aizwys.cn/Article/details/gtbvimxahy.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.guowangkeji.top/Article/details/gtldhalivl.html

[S32] C++：字符串
来源：http://dali.jlsjyb.cn/Article/details/gtzxkytboi.html

std::string s = "hi";  s += "!";
来源：http://dali.xuetiantiany.cn/Article/details/gtregaqppr.html

[S33] C++：vector 增删
来源：http://dali.andypj.xyz/Article/details/gtqhcvvlrb.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.xziqi.cn/Article/details/gtmykjeejq.html

[S34] C++：遍历 vector
来源：http://dali.zhiwuduotai.top/Article/details/gttpjivyzz.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.yonumen.top/Article/details/gtmopskuyu.html

[S35] C++：map
来源：http://dali.cashguo.top/Article/details/gtvwoptzzj.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhiwuduotai.top/Article/details/gtuqpcgpmw.html

[S36] C++：unordered_map
来源：http://dali.sysykeji.top/Article/details/gtawxeolil.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jqgfzy.top/Article/details/gtgkpwprst.html

[S37] C++：set
来源：http://dali.shuidangran.top/Article/details/gtnwjlgyhb.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.xziqi.cn/Article/details/gtthtnesxm.html

[S38] C++：排序
来源：http://dali.fengsongda.top/Article/details/gtjynuhkne.html

std::sort(v.begin(), v.end());
来源：http://dali.tianlin.xyz/Article/details/gtmrjrrsex.html

[S39] C++：自定义比较器排序
来源：http://dali.iojbl.cn/Article/details/gtklsucuho.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.dianchejie.cn/Article/details/gtxsznznad.html

[S40] C++：查找元素
来源：http://dali.yvedp.cn/Article/details/gtsxdkuknu.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.snrcjt.cn/Article/details/gtjhltdgyt.html

[S41] C++：类与构造函数
来源：http://dali.yongpay.top/Article/details/gtkhipqtrx.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.hnxiangtu.top/Article/details/gttwomfmmx.html

[S42] C++：继承与虚函数
来源：http://dali.shangyingyoupin.top/Article/details/gtlquelfyb.html

class B : public Base { public: void f() override {} };
来源：http://dali.guannengcc.top/Article/details/gtwcglpkcw.html

[S43] C++：智能指针
来源：http://dali.snrcjt.cn/Article/details/gtzmzbpror.html

auto p = std::make_unique<int>(5);
来源：http://dali.nanxinkj.top/Article/details/gtixamchuy.html

[S44] C++：引用传参
来源：http://dali.sweek.top/Article/details/gtbwfpddcw.html

void inc(int &x) { ++x; }
来源：http://dali.cheryme.top/Article/details/gtvdlyuetu.html

[S45] C++：lambda
来源：http://dali.0kj1m.cn/Article/details/gtlhudfwfx.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.gogol.net.cn/Article/details/gtqihoawxf.html

[S46] C++：函数模板
来源：http://dali.daxiang520.top/Article/details/gtgrqrpzct.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhixingplan.top/Article/details/gthnifwfqo.html

[S47] C++：结构化绑定遍历
来源：http://dali.yuanzhike.top/Article/details/gtewcymgrp.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.gaohongyu789.top/Article/details/gtctvknkrt.html

[S48] C++：逐行读文件
来源：http://dali.guannengcc.top/Article/details/gttzycpege.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.cashguo.top/Article/details/gttweturis.html

while (std::getline(in, line)) { }
来源：http://dali.yvedp.cn/Article/details/gtagzbbued.html

[S49] C++：写文件
来源：http://dali.meibo888.top/Article/details/gtitozqlfu.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.gzhubu.top/Article/details/gtgoefrvlf.html

[S50] C++：格式化数字
来源：http://dali.gaohongyu789.top/Article/details/gtnuquhtke.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.hywenlv.cn/Article/details/gtqdlwptzn.html

[S51] C++：显式类型转换
来源：http://dali.cdnleiting.top/Article/details/gttrtogqes.html

static_cast<double>(a) / b
来源：http://dali.chenjidiqi.icu/Article/details/gtivbmjrun.html

[S52] C++：const 与 noexcept
来源：http://dali.jlsjyb.cn/Article/details/gtrnwqydoa.html

int size() const noexcept { return n_; }
来源：http://dali.quarkkingdee.top/Article/details/gtztstqzoh.html

[S53] C++：移动语义
来源：http://dali.svipenyu.cn/Article/details/gtfrsaolof.html

std::vector<int> w = std::move(v);
来源：http://dali.guannengcc.top/Article/details/gtlycqssqo.html

[S54] C++：异常处理
来源：http://dali.wangshuangyany.cn/Article/details/gtiqnktxjk.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.yvedp.cn/Article/details/gtaojwfhhs.html

[S55] C++：结构化绑定
来源：http://dali.sufxvd.cn/Article/details/gtfhattilt.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.hnqzz.top/Article/details/gtebinzlfv.html

[S56] C++：optional
来源：http://dali.zhixingplan.top/Article/details/gtcccjzoqz.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.iojbl.cn/Article/details/gtexwfekwf.html

[S57] C++：编译期常量
来源：http://dali.guowangkeji.top/Article/details/gtpszzhvba.html

constexpr int N = 10;
来源：http://dali.gotoacloud.top/Article/details/gtrwjaqlzw.html

[S58] C++：命名空间
来源：http://dali.xuanzx.com/Article/details/gtqyiackhz.html

namespace ns { int f() { return 1; } }
来源：http://dali.cqqwz.cn/Article/details/gtxoxzpmwc.html

[S59] C++：静态断言
来源：http://dali.havefunace.top/Article/details/gtyhkixiay.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.xziqi.cn/Article/details/gtuwnetcst.html

[S60] C++：遍历并删除元素
来源：http://dali.sweek.top/Article/details/gtkanmcyss.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.sweek.top/Article/details/gtdcpkztck.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtshklukdy.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.redwolf501.top/Article/details/gtswtoebmm.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtitubjzzq.html

[T01] Kotlin：Hello World
来源：http://dali.cqqwz.cn/Article/details/gtispocpyl.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gtajbtronn.html

[T02] Kotlin：变量
来源：http://dali.yongpay.top/Article/details/gtejqakyed.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.cucudq.cn/Article/details/gtlqzwqliw.html

[T03] Kotlin：字符串模板
来源：http://dali.andypj.xyz/Article/details/gtyxmrivxk.html

"值: $b"
来源：http://dali.nanxuanxn.top/Article/details/gtafinaafi.html

[T04] Kotlin：空安全
来源：http://dali.yvedp.cn/Article/details/gtigsfgndr.html

val n: String? = null;  n?.length
来源：http://dali.hongshengwenyu.top/Article/details/gtqetniyaw.html

[T05] Kotlin：when 表达式
来源：http://dali.xuetiantiany.cn/Article/details/gtvrpuhlup.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.jianghu66.top/Article/details/gtdbmatcmn.html

[T06] Kotlin：集合映射
来源：http://dali.sweek.top/Article/details/gtzrklamoz.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.jinqigufen.top/Article/details/gtaqkkjwfq.html

[T07] Kotlin：集合过滤
来源：http://dali.zhengqikj.top/Article/details/gtajpykhng.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.chenjidiqi.icu/Article/details/gtinnsynwu.html

[T08] Kotlin：数据类
来源：http://dali.dianchejie.cn/Article/details/gtfoudcqrz.html

data class User(val name: String, val age: Int)
来源：http://dali.iojbl.cn/Article/details/gtqysyahet.html

[T09] Kotlin：扩展函数
来源：http://dali.fzhhl.top/Article/details/gtlmwuniwr.html

fun String.exclaim() = this + "!"
来源：http://dali.jqgfzy.top/Article/details/gttcroryuu.html

[T10] Kotlin：默认参数
来源：http://dali.xziqi.cn/Article/details/gtarldlfjk.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.shanyushiyangtech.top/Article/details/gtetibtqsz.html

[T11] Kotlin：协程
来源：http://dali.xuetiantiany.cn/Article/details/gtbqkvexjl.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.feifeiyinyue.top/Article/details/gtlbmmtlfh.html

[T12] Kotlin：解构声明
来源：http://dali.ydzc1.top/Article/details/gtmplaipdw.html

val (a, b) = Pair(1, 2)
来源：http://dali.jlsjyb.cn/Article/details/gtcjomdvec.html

[T13] Kotlin：只读 Map
来源：http://dali.yonumen.top/Article/details/gtlbfvpyjm.html

val m = mapOf("a" to 1)
来源：http://dali.feifeiyinyue.top/Article/details/gtlamoigke.html

[T14] Kotlin：循环
来源：http://dali.jinqigfzy.top/Article/details/gtionjhrld.html

for (i in 1..10) println(i)
来源：http://dali.jyoumei.cn/Article/details/gtjvmgkztc.html

[T15] Kotlin：接口
来源：http://dali.xuanzx.com/Article/details/gtkxtgqlrn.html

interface Shape { fun area(): Double }
来源：http://dali.yueranfly.top/Article/details/gteujftlhz.html

[T16] Swift：Hello World
来源：http://dali.sxryk.cn/Article/details/gtmaolksbc.html

print("Hello")
来源：http://dali.sufxvd.cn/Article/details/gtlkstgzri.html

[T17] Swift：变量与常量
来源：http://dali.dashuyun.cn/Article/details/gtjynanfxc.html

var a = 1;  let b = 2
来源：http://dali.quarkkingdee.top/Article/details/gtbcxklyoy.html

[T18] Swift：字符串插值
来源：http://dali.svipenyu.cn/Article/details/gtbqhpbbxb.html

"值: \(b)"
来源：http://dali.sweek.top/Article/details/gtaycrvnfz.html

[T19] Swift：可选绑定
来源：http://dali.ydzc1.top/Article/details/gtrvrylmcc.html

if let n = opt { print(n) }
来源：http://dali.yvedp.cn/Article/details/gtvtrxqbix.html

[T20] Swift：数组操作
来源：http://dali.shanyushiyangtech.top/Article/details/gtbrgxnqao.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.ehwqpu.com/Article/details/gtqnvvfcyo.html

[T21] Swift：遍历
来源：http://dali.zycfv.cn/Article/details/gtevelrlum.html

for x in a { print(x) }
来源：http://dali.yj20258888.top/Article/details/gtnjrfpizc.html

[T22] Swift：字典
来源：http://dali.sweek.top/Article/details/gtdlqxnuvs.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.ybcxt.top/Article/details/gtutpngiwa.html

[T23] Swift：函数
来源：http://dali.ppjwa.cn/Article/details/gtayzgnhyz.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.jiagoushi.top/Article/details/gttaydifjx.html

[T24] Swift：闭包
来源：http://dali.fengsongda.top/Article/details/gtofsrvlui.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.haohaochexian.top/Article/details/gtnxseklwx.html

[T25] Swift：结构体
来源：http://dali.nwbrower.top/Article/details/gtkuhfjrzw.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gttlqbjkkx.html

[T26] Swift：类与重写
来源：http://dali.jinghuilouyu.cn/Article/details/gtgjkqkhav.html

class A: Base { override func f() {} }
来源：http://dali.dashuyun.cn/Article/details/gtfpnnxyvw.html

[T27] Swift：错误处理
来源：http://dali.xziqi.cn/Article/details/gtaeuuhkvk.html

do { try f() } catch { print(error) }
来源：http://dali.yj202588.top/Article/details/gtxxjzcuyn.html

[T28] Swift：枚举
来源：http://dali.meibo888.top/Article/details/gtgumicchq.html

enum Color { case red, green }
来源：http://dali.haohaochexian.top/Article/details/gttodjuodi.html

[T29] Swift：guard 提前返回
来源：http://dali.chenjidiqi.icu/Article/details/gtjyakkned.html

guard let x = opt else { return }
来源：http://dali.zycfv.cn/Article/details/gtuoiuffea.html

[T30] Swift：协议
来源：http://dali.ppjwa.cn/Article/details/gtwzvpmkmr.html

protocol Shape { func area() -> Double }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsxfvtpga.html

[T31] Lua：Hello World
来源：http://dali.sysykeji.top/Article/details/gtajoorydb.html

print("Hello")
来源：http://dali.havefunace.top/Article/details/gtnliymvqx.html

[T32] Lua：局部变量
来源：http://dali.jiagoushi.top/Article/details/gtwswhesve.html

local a = 1
来源：http://dali.haohaochexian.top/Article/details/gtzolrsljo.html

[T33] Lua：表（数组）
来源：http://dali.cucudq.cn/Article/details/gteqbgdzhu.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.hnqzz.top/Article/details/gtpjagixvw.html

[T34] Lua：遍历表
来源：http://dali.cashguo.top/Article/details/gtpzxljtxj.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.yanxiufei.cn/Article/details/gtdthllunw.html

[T35] Lua：字典表
来源：http://dali.ehwqpu.com/Article/details/gtrdsyekmy.html

local d = { a = 1 };  d.b = 2
来源：http://dali.shangyingyoupin.top/Article/details/gtwlhwpaba.html

[T36] Lua：函数
来源：http://dali.316326.xyz/Article/details/gtnkisnihu.html

function add(a, b) return a + b end
来源：http://dali.nwbrower.top/Article/details/gtxtsnwvgo.html

[T37] Lua：字符串拼接
来源：http://dali.ppjwa.cn/Article/details/gtgffusxex.html

"a" .. "b"
来源：http://dali.xinyue.icu/Article/details/gtlozfyntt.html

[T38] Lua：条件
来源：http://dali.jinqigfzy.top/Article/details/gtkrkqzqhs.html

if x > 0 then print("正") end
来源：http://dali.xuanzx.com/Article/details/gtrpuxrbzi.html

[T39] Lua：模式匹配
来源：http://dali.sweek.top/Article/details/gtvfobjzsu.html

string.find(s, "%d+")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuoxdksai.html

[T40] Lua：元表
来源：http://dali.tianlin.xyz/Article/details/gthbvhsegl.html

setmetatable({}, { __index = base })
来源：http://dali.yuxming.cn/Article/details/gtfjqufqes.html

[T41] Perl：Hello World
来源：http://dali.tianlin.xyz/Article/details/gtnfoopayw.html

print "Hello\n";
来源：http://dali.feifeiyinyue.top/Article/details/gtuaaijozp.html

[T42] Perl：变量类型
来源：http://dali.guannengcc.top/Article/details/gtliwlgaej.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.ehwqpu.com/Article/details/gtfdlqcdlj.html

[T43] Perl：字符串插值
来源：http://dali.zhiwuduotai.top/Article/details/gturgrzahh.html

"值: $a"
来源：http://dali.vqdsnc.cn/Article/details/gtcvckgvna.html

[T44] Perl：条件
来源：http://dali.zhiwuduotai.top/Article/details/gtkwatrsex.html

if ($a > 0) { print "正"; }
来源：http://dali.wangdashe.top/Article/details/gtlogwisjy.html

[T45] Perl：数组遍历
来源：http://dali.cheryme.top/Article/details/gtfjdwleaj.html

for my $x (@arr) { print $x; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxxtzxptd.html

[T46] Perl：哈希操作
来源：http://dali.yonumen.top/Article/details/gtpbtonxlu.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.wangshuangyany.cn/Article/details/gtjixfimcw.html

[T47] Perl：正则捕获
来源：http://dali.tanke756.top/Article/details/gtfrlnivyr.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.jlsjyb.cn/Article/details/gtsbgorrnp.html

[T48] Perl：正则替换
来源：http://dali.gogol.net.cn/Article/details/gtfadctbne.html

$s =~ s/old/new/g;
来源：http://dali.zhixingplan.top/Article/details/gtutszzxri.html

[T49] Perl：函数
来源：http://dali.c1oappe.top/Article/details/gtyqbtosej.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.gaohongyu789.top/Article/details/gtyusbndpa.html

[T50] Perl：逐行读文件
来源：http://dali.nwbrower.top/Article/details/gtmdnufhlt.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.aibaodan.cn/Article/details/gtktiszxjo.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.hnxiangtu.top/Article/details/gtlcoxatsy.html

[T51] Scala：Hello World
来源：http://dali.cheryme.top/Article/details/gtqhlayabr.html

println("Hello")
来源：http://dali.hfpthk.cn/Article/details/gtifbfuzxj.html

[T52] Scala：变量
来源：http://dali.jqgufenzy.top/Article/details/gtszyrdfsw.html

val a = 1;  var b = 2
来源：http://dali.jqgfzy.top/Article/details/gthtvcfloz.html

[T53] Scala：字符串插值
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjpftubna.html

s"值: $b"
来源：http://dali.aizwys.cn/Article/details/gtgtnyojis.html

[T54] Scala：集合映射
来源：http://dali.aizwys.cn/Article/details/gtrpkdczud.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.hysaishi.cn/Article/details/gtvzzusjfz.html

[T55] Scala：集合过滤
来源：http://dali.daria6918.cn/Article/details/gttplnemtu.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.aibaodan.cn/Article/details/gtfmhwqhjz.html

[T56] Scala：样例类
来源：http://dali.sufxvd.cn/Article/details/gtpycqzqgd.html

case class User(name: String, age: Int)
来源：http://dali.gaohongyu789.top/Article/details/gtyjnsmidu.html

[T57] Scala：模式匹配
来源：http://dali.shangyingyoupin.top/Article/details/gtslobrmzd.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhixingplan.top/Article/details/gtiewmygyi.html

[T58] Scala：函数定义
来源：http://dali.zhengqikj.top/Article/details/gtbdduvvzb.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhixingplan.top/Article/details/gtcoqiwkth.html

[T59] Scala：循环
来源：http://dali.hysaishi.cn/Article/details/gtsenhvfpx.html

for (i <- 1 to 10) println(i)
来源：http://dali.daria6918.cn/Article/details/gtumavbprh.html

[T60] Scala：折叠
来源：http://dali.cdnleiting.top/Article/details/gtdnmatros.html


<!-- 参考信息 -->