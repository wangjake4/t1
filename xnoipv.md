代发 wailian999

df -h;  du -sh *
来源：http://dali.tanke756.top/Article/details/gttvhhjofh.html

[R62] 找最占空间的文件
来源：http://dali.gzhubu.top/Article/details/gtnvmialmc.html

du -ah . | sort -rh | head -10
来源：http://dali.316326.xyz/Article/details/gtpwzktyxd.html

[R63] 内存与进程
来源：http://dali.yuanzhike.top/Article/details/gtrpvhvjdi.html

free -h;  ps aux | grep nginx
来源：http://dali.sxryk.cn/Article/details/gtwlahngxb.html

[R64] 结束进程
来源：http://dali.hnqzz.top/Article/details/gtypeancla.html

kill -9 $(pgrep -f app.py)
来源：http://dali.yuxming.cn/Article/details/gtrfunfcux.html

[R65] 查看端口占用
来源：http://dali.kuanghao11.cn/Article/details/gtuudjwsec.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.pycfn.com/Article/details/gtduzmehqv.html

[R66] 定时任务
来源：http://dali.haohaochexian.top/Article/details/gtpqghuepu.html

crontab -e;  crontab -l
来源：http://dali.jqgfzy.top/Article/details/gtrhvhabab.html

[R67] 生成随机十六进制串
来源：http://dali.iojbl.cn/Article/details/gtghydzgjj.html

openssl rand -hex 16
来源：http://dali.shzxlz.cn/Article/details/gtgpktuetn.html

[R68] 计算文件校验值
来源：http://dali.wangdashe.top/Article/details/gtptmkiaha.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.yongpay.top/Article/details/gtcrhqpren.html

[R69] 生成随机密码
来源：http://dali.snrcjt.cn/Article/details/gtybrtnank.html

head -c 16 /dev/urandom | base64
来源：http://dali.shzxlz.cn/Article/details/gtdojhhtfc.html

[R70] 时间戳与互转
来源：http://dali.dianchejie.cn/Article/details/gtufmjnbms.html

date +%s;  date -d @1700000000
来源：http://dali.snrcjt.cn/Article/details/gterzfcbft.html

[R71] 日期格式化
来源：http://dali.nanxuanxn.top/Article/details/gtponrrjba.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.yongpay.top/Article/details/gthvbdzdsj.html

[R72] 等待端口就绪
来源：http://dali.pycfn.com/Article/details/gtqpzpgfig.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.nanxinkj.top/Article/details/gtzahjbjvh.html

[R73] 分割大日志
来源：http://dali.yongpay.top/Article/details/gttxcypbtp.html

split -l 1000 big.log part_
来源：http://dali.wangshuangyany.cn/Article/details/gtrqlqdxsh.html

[R74] 批量重命名
来源：http://dali.chenjidiqi.icu/Article/details/gttxzhelfl.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.jianghu66.top/Article/details/gtosoqsdml.html

[R75] 导出环境变量
来源：http://dali.gogol.net.cn/Article/details/gtjuicngyi.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.sxryk.cn/Article/details/gtuvptenrb.html

[R76] 使用临时文件
来源：http://dali.cheryme.top/Article/details/gtqteshqpj.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.aizwys.cn/Article/details/gtergwkksn.html

[R77] 读取用户输入
来源：http://dali.guowangkeji.top/Article/details/gthffmunuv.html

read -rp "请输入: " ans
来源：http://dali.dianchejie.cn/Article/details/gtyqhknhea.html

[R78] 交互式菜单
来源：http://dali.smart0.xyz/Article/details/gtetxtxbhq.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.c1oappe.top/Article/details/gtxclhlzav.html

[R79] 解析命令行选项
来源：http://dali.hnqzz.top/Article/details/gtdwrelqfm.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.gotoacloud.top/Article/details/gtcxhpkjwe.html

[R80] 查看脚本执行耗时
来源：http://dali.0kj1m.cn/Article/details/gtwdlkjudq.html

time ./run.sh
来源：http://dali.chenzaomai.com/Article/details/gtujmjduuo.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gthfnalbbe.html

S. C / C++ 专题
来源：http://dali.redwolf501.top/Article/details/gtrzmuhnay.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtsjghxihe.html

[S01] C：Hello World
来源：http://dali.xinyue.icu/Article/details/gtopzxybdp.html

#include <stdio.h>
来源：http://dali.jianghu66.top/Article/details/gtvfjgmawm.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.nanxinkj.top/Article/details/gthwxyleau.html

[S02] C：变量与格式化输出
来源：http://dali.ydzc1.top/Article/details/gtujjtqwet.html

int a = 10; printf("%d\n", a);
来源：http://dali.jinqigfzy.top/Article/details/gtgauvzbqh.html

[S03] C：读入整数
来源：http://dali.chenzaomai.com/Article/details/gtcmznkxaz.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gtvcqqeqry.html

[S04] C：字符串复制
来源：http://dali.fzhhl.top/Article/details/gtewloimef.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.pycfn.com/Article/details/gtcdmofoly.html

[S05] C：字符串长度
来源：http://dali.jiagoushi.top/Article/details/gtvdgrpdxf.html

strlen(s)
来源：http://dali.tanke756.top/Article/details/gtgmaqmjek.html

[S06] C：字符串比较
来源：http://dali.yvedp.cn/Article/details/gtdsdvedqq.html

strcmp(a, b) == 0
来源：http://dali.nanxinkj.top/Article/details/gtzhfcpgli.html

[S07] C：数组遍历求和
来源：http://dali.chenzaomai.com/Article/details/gtpuuosqrb.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.cqqwz.cn/Article/details/gtsmseisil.html

[S08] C：动态内存分配与释放
来源：http://dali.aizwys.cn/Article/details/gtabqmjwzu.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.aizwys.cn/Article/details/gthmrertbv.html

[S09] C：结构体定义与初始化
来源：http://dali.shangyingyoupin.top/Article/details/gtbmddnrvg.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.hammf.cn/Article/details/gtzjidqszq.html

[S10] C：指针与解引用
来源：http://dali.wangdashe.top/Article/details/gtshcbhsjb.html

int *p = &a;  *p = 5;
来源：http://dali.cqqwz.cn/Article/details/gtqzqjrxke.html

[S11] C：逐行读文件
来源：http://dali.quarkkingdee.top/Article/details/gtoempmzjl.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.ivvv.top/Article/details/gtmusfzvis.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.xziqi.cn/Article/details/gtfyjbqwsp.html

fclose(f);
来源：http://dali.hfpthk.cn/Article/details/gtdkojhizd.html

[S12] C：写文件
来源：http://dali.havefunace.top/Article/details/gtdelzqxru.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.yvedp.cn/Article/details/gttqiniart.html

[S13] C：宏定义
来源：http://dali.redwolf501.top/Article/details/gtbbrkuajp.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.yanxiufei.cn/Article/details/gtolvsjxux.html

[S14] C：枚举
来源：http://dali.fengsongda.top/Article/details/gtmhqsipsi.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.mhx1999.top/Article/details/gtghqhemez.html

[S15] C：类型转换
来源：http://dali.pengpengdd.cyou/Article/details/gtihalcczl.html

(double) a / b
来源：http://dali.fengsongda.top/Article/details/gtywsfpdxw.html

[S16] C：位操作置位
来源：http://dali.shanyushiyangtech.top/Article/details/gttmzlgdmc.html

x |= (1 << 3);
来源：http://dali.shzxlz.cn/Article/details/gtqgfahkrs.html

[S17] C：安全拼接字符串
来源：http://dali.jinqigufen.top/Article/details/gtkvxqvtey.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiuatavcj.html

[S18] C：命令行参数
来源：http://dali.cqqwz.cn/Article/details/gtbneqigpg.html

int main(int argc, char **argv)
来源：http://dali.jianghu66.top/Article/details/gtdwfbsqvi.html

[S19] C：快速排序
来源：http://dali.xylfe.cn/Article/details/gttrwqqxor.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.fzhhl.top/Article/details/gtynztdmaj.html

[S20] C：二分查找
来源：http://dali.iojbl.cn/Article/details/gtfhxzcmkz.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.nwbrower.top/Article/details/gthceohxnl.html

[S21] C：字符类别判断
来源：http://dali.ppjwa.cn/Article/details/gtyxigangr.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.xylfe.cn/Article/details/gtpnidyrok.html

[S22] C：字符串转数字
来源：http://dali.jinqigufen.top/Article/details/gtvhbduwug.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.nanxuanxn.top/Article/details/gtfszerooc.html

[S23] C：随机数
来源：http://dali.zhengqikj.top/Article/details/gtltrntzgc.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.smart0.xyz/Article/details/gtihxdhjgv.html

[S24] C：获取本地时间
来源：http://dali.fzhhl.top/Article/details/gtdyyszqts.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.yj20258888.top/Article/details/gtlbtutdzs.html

[S25] C：内存拷贝
来源：http://dali.xuanzx.com/Article/details/gtverwcwgq.html

memcpy(dst, src, n);
来源：http://dali.yonumen.top/Article/details/gtqzjmfxeb.html

[S26] C：内存清零
来源：http://dali.pycfn.com/Article/details/gtjquebbfs.html

memset(a, 0, sizeof a);
来源：http://dali.guannengcc.top/Article/details/gtqiadjwdi.html

[S27] C：定义常量
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvogwekna.html

const double PI = 3.14159;
来源：http://dali.shanyushiyangtech.top/Article/details/gtwyabzogz.html

[S28] C：静态变量
来源：http://dali.hywenlv.cn/Article/details/gtjbrdfkpi.html

static int counter = 0;
来源：http://dali.fengsongda.top/Article/details/gtlesohffy.html

[S29] C：变参函数
来源：http://dali.chenlongwang.top/Article/details/gtvifdidtp.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.jqgfzy.top/Article/details/gtibmhodcq.html

[S30] C：头文件保护
来源：http://dali.jyoumei.cn/Article/details/gtqqkwjidv.html

#ifndef X_H
来源：http://dali.cheryme.top/Article/details/gtsijkqoul.html

#define X_H
来源：http://dali.cheryme.top/Article/details/gtzojlhbfx.html

#endif
来源：http://dali.bjfxy.top/Article/details/gtbhyjbwac.html

[S31] C++：Hello World
来源：http://dali.gaohongyu789.top/Article/details/gtbuvaupfl.html

#include <iostream>
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmofwkvtr.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.xylfe.cn/Article/details/gtvqkddygs.html

[S32] C++：字符串
来源：http://dali.gaohongyu789.top/Article/details/gtvfqtnnmk.html

std::string s = "hi";  s += "!";
来源：http://dali.xziqi.cn/Article/details/gttiakzbqr.html

[S33] C++：vector 增删
来源：http://dali.iojbl.cn/Article/details/gtoipruqty.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.bjfxy.top/Article/details/gtyxafzyzq.html

[S34] C++：遍历 vector
来源：http://dali.cashguo.top/Article/details/gtxhmqozww.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.nanxuanxn.top/Article/details/gtumeczkes.html

[S35] C++：map
来源：http://dali.aizwys.cn/Article/details/gtmbpvnbvz.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zdqjudy.top/Article/details/gtnatdrpzj.html

[S36] C++：unordered_map
来源：http://dali.andypj.xyz/Article/details/gtnmhrtvfj.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.svipenyu.cn/Article/details/gtcsrpjyuz.html

[S37] C++：set
来源：http://dali.hnqzz.top/Article/details/gtrbxupllg.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.xinyue.icu/Article/details/gtyytvdlka.html

[S38] C++：排序
来源：http://dali.dianchejie.cn/Article/details/gtugxkvwsz.html

std::sort(v.begin(), v.end());
来源：http://dali.xylfe.cn/Article/details/gtcpiceaum.html

[S39] C++：自定义比较器排序
来源：http://dali.hongshengwenyu.top/Article/details/gtggjrnnhd.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.hongshengwenyu.top/Article/details/gtwwzqkzqp.html

[S40] C++：查找元素
来源：http://dali.yanxiufei.cn/Article/details/gtmmmklnvr.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zdqjudy.top/Article/details/gtijwwtjba.html

[S41] C++：类与构造函数
来源：http://dali.bjfxy.top/Article/details/gtkvvyikfi.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.yvedp.cn/Article/details/gtsqmmqhyh.html

[S42] C++：继承与虚函数
来源：http://dali.pengpengdd.cyou/Article/details/gtavhxypxr.html

class B : public Base { public: void f() override {} };
来源：http://dali.yanxiufei.cn/Article/details/gtlksstcot.html

[S43] C++：智能指针
来源：http://dali.havefunace.top/Article/details/gtfbxwwkne.html

auto p = std::make_unique<int>(5);
来源：http://dali.jlsjyb.cn/Article/details/gtocovrvle.html

[S44] C++：引用传参
来源：http://dali.hammf.cn/Article/details/gtlruisdxr.html

void inc(int &x) { ++x; }
来源：http://dali.haohaochexian.top/Article/details/gtwtqunpcb.html

[S45] C++：lambda
来源：http://dali.chenlongwang.top/Article/details/gtqxjdwozm.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.yuanzhike.top/Article/details/gtkpfzqtyk.html

[S46] C++：函数模板
来源：http://dali.vqdsnc.cn/Article/details/gthikczaba.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.wangshuangyany.cn/Article/details/gtcpbtzpch.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhixingplan.top/Article/details/gtqqtrvicg.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.yanxiufei.cn/Article/details/gtfvqqcnzm.html

[S48] C++：逐行读文件
来源：http://dali.dianchejie.cn/Article/details/gtegxfxrbi.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.redwolf501.top/Article/details/gtjzcqwabn.html

while (std::getline(in, line)) { }
来源：http://dali.snrcjt.cn/Article/details/gtpjjwhzax.html

[S49] C++：写文件
来源：http://dali.316326.xyz/Article/details/gtgfxlmwvk.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.yuanzhike.top/Article/details/gtwkhklwkr.html

[S50] C++：格式化数字
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvgsuwhup.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.xinyue.icu/Article/details/gtjdtvvytq.html

[S51] C++：显式类型转换
来源：http://dali.mhx1999.top/Article/details/gtvglxofhk.html

static_cast<double>(a) / b
来源：http://dali.yj20258888.top/Article/details/gtqdabvcgz.html

[S52] C++：const 与 noexcept
来源：http://dali.chenlongwang.top/Article/details/gtnugwwffr.html

int size() const noexcept { return n_; }
来源：http://dali.gotoacloud.top/Article/details/gtavcmyyez.html

[S53] C++：移动语义
来源：http://dali.tanke756.top/Article/details/gtyhgdaxnw.html

std::vector<int> w = std::move(v);
来源：http://dali.smart0.xyz/Article/details/gtirfovymd.html

[S54] C++：异常处理
来源：http://dali.yj20258888.top/Article/details/gtaynttwkd.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.yj20258.top/Article/details/gtkyqtnkbu.html

[S55] C++：结构化绑定
来源：http://dali.smart0.xyz/Article/details/gtwbiemsni.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zycfv.cn/Article/details/gttqcwhcdd.html

[S56] C++：optional
来源：http://dali.meibo888.top/Article/details/gtowwlukkd.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.shuidangran.top/Article/details/gtvbpicvwa.html

[S57] C++：编译期常量
来源：http://dali.mhx1999.top/Article/details/gtignihkaw.html

constexpr int N = 10;
来源：http://dali.jiagoushi.top/Article/details/gtuzubotsa.html

[S58] C++：命名空间
来源：http://dali.gogol.net.cn/Article/details/gtguocymwe.html

namespace ns { int f() { return 1; } }
来源：http://dali.quarkkingdee.top/Article/details/gtnykjjjxp.html

[S59] C++：静态断言
来源：http://dali.sufxvd.cn/Article/details/gtcaziydiw.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.jyoumei.cn/Article/details/gtzrjfjhhs.html

[S60] C++：遍历并删除元素
来源：http://dali.hnqzz.top/Article/details/gtvqryapko.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.tian-w.cn/Article/details/gthwyhuhco.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gttkrilabp.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.jianghu66.top/Article/details/gtaarimqss.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtuvoliffn.html

[T01] Kotlin：Hello World
来源：http://dali.yuanzhike.top/Article/details/gtxsvzpate.html

println("Hello")
来源：http://dali.hysaishi.cn/Article/details/gttpwysdnp.html

[T02] Kotlin：变量
来源：http://dali.xinyue.icu/Article/details/gtlrynzodz.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.xylfe.cn/Article/details/gttlvbawxu.html

[T03] Kotlin：字符串模板
来源：http://dali.fengsongda.top/Article/details/gtjobtkzwt.html

"值: $b"
来源：http://dali.ivvv.top/Article/details/gtmmqqxiji.html

[T04] Kotlin：空安全
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxwhejhcc.html

val n: String? = null;  n?.length
来源：http://dali.jiagoushi.top/Article/details/gttiycbhfz.html

[T05] Kotlin：when 表达式
来源：http://dali.aizwys.cn/Article/details/gtwxzrtlpv.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.tanke756.top/Article/details/gtdshbrgnl.html

[T06] Kotlin：集合映射
来源：http://dali.jinqigufen.top/Article/details/gtpdozdtki.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.jiagoushi.top/Article/details/gtjnuavgzl.html

[T07] Kotlin：集合过滤
来源：http://dali.gaohongyu789.top/Article/details/gtzkpxwybm.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.hongshengwenyu.top/Article/details/gthcyrcpet.html

[T08] Kotlin：数据类
来源：http://dali.jiagoushi.top/Article/details/gtinwltqtn.html

data class User(val name: String, val age: Int)
来源：http://dali.gotoacloud.top/Article/details/gtyfkbamap.html

[T09] Kotlin：扩展函数
来源：http://dali.daxiang520.top/Article/details/gtkjklinmn.html

fun String.exclaim() = this + "!"
来源：http://dali.yvedp.cn/Article/details/gtqcafcgou.html

[T10] Kotlin：默认参数
来源：http://dali.daria6918.cn/Article/details/gtexkwypjh.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.jqgfzy.top/Article/details/gttgcvkpiw.html

[T11] Kotlin：协程
来源：http://dali.mhx1999.top/Article/details/gtunvvkhpx.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.wangdashe.top/Article/details/gtgvupynzo.html

[T12] Kotlin：解构声明
来源：http://dali.gogol.net.cn/Article/details/gtpieawnyl.html

val (a, b) = Pair(1, 2)
来源：http://dali.gotoacloud.top/Article/details/gtkzkmykqn.html

[T13] Kotlin：只读 Map
来源：http://dali.yangfankeji.com/Article/details/gtxgkmcfqq.html

val m = mapOf("a" to 1)
来源：http://dali.guannengcc.top/Article/details/gtzjcfabdn.html

[T14] Kotlin：循环
来源：http://dali.tanke756.top/Article/details/gtywptzxnb.html

for (i in 1..10) println(i)
来源：http://dali.sufxvd.cn/Article/details/gtlrycvchq.html

[T15] Kotlin：接口
来源：http://dali.316326.xyz/Article/details/gtlerglcqd.html

interface Shape { fun area(): Double }
来源：http://dali.chenjidiqi.icu/Article/details/gtbfzghuky.html

[T16] Swift：Hello World
来源：http://dali.cashguo.top/Article/details/gtlyzxwzem.html

print("Hello")
来源：http://dali.jinqigfzy.top/Article/details/gtqrmoznxc.html

[T17] Swift：变量与常量
来源：http://dali.cucudq.cn/Article/details/gtuuugyzij.html

var a = 1;  let b = 2
来源：http://dali.daria6918.cn/Article/details/gtmjtodmhp.html

[T18] Swift：字符串插值
来源：http://dali.xuetiantiany.cn/Article/details/gtecwspkyn.html

"值: \(b)"
来源：http://dali.fzhhl.top/Article/details/gttllskpid.html

[T19] Swift：可选绑定
来源：http://dali.wangshuangyany.cn/Article/details/gtstbugxwm.html

if let n = opt { print(n) }
来源：http://dali.birdmap.top/Article/details/gttjzhpmhu.html

[T20] Swift：数组操作
来源：http://dali.shanyushiyangkeji.top/Article/details/gtanmmwvyc.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.yangfankeji.com/Article/details/gtylqqcois.html

[T21] Swift：遍历
来源：http://dali.xuanzx.com/Article/details/gttkpgdaeu.html

for x in a { print(x) }
来源：http://dali.ybcxt.top/Article/details/gtorhwcxuh.html

[T22] Swift：字典
来源：http://dali.xuetiantiany.cn/Article/details/gtpsfkihuk.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.shuidangran.top/Article/details/gtrjtdewgk.html

[T23] Swift：函数
来源：http://dali.nanxuanxn.top/Article/details/gtwwustbaf.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.smart0.xyz/Article/details/gtqehejuvo.html

[T24] Swift：闭包
来源：http://dali.gotoacloud.top/Article/details/gtepnuiojq.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.andypj.xyz/Article/details/gtnnskilkw.html

[T25] Swift：结构体
来源：http://dali.xziqi.cn/Article/details/gtmrdgqblm.html

struct P { var x: Int }
来源：http://dali.ybcxt.top/Article/details/gtyhvdmmdp.html

[T26] Swift：类与重写
来源：http://dali.shuidangran.top/Article/details/gtqazkfhpq.html

class A: Base { override func f() {} }
来源：http://dali.chenjidiqi.icu/Article/details/gtvukrnsdl.html

[T27] Swift：错误处理
来源：http://dali.havefunace.top/Article/details/gtwxykppde.html

do { try f() } catch { print(error) }
来源：http://dali.wangshuangyany.cn/Article/details/gtiroxefvs.html

[T28] Swift：枚举
来源：http://dali.meibo888.top/Article/details/gtlehrmhsq.html

enum Color { case red, green }
来源：http://dali.ppjwa.cn/Article/details/gtzbzzoqyb.html

[T29] Swift：guard 提前返回
来源：http://dali.xziqi.cn/Article/details/gthaiwgwzy.html

guard let x = opt else { return }
来源：http://dali.svipenyu.cn/Article/details/gtqrtmwgdw.html

[T30] Swift：协议
来源：http://dali.jinyuanbaomall.cn/Article/details/gtujpjkvvk.html

protocol Shape { func area() -> Double }
来源：http://dali.hongshengwenyu.top/Article/details/gtjgklbdip.html

[T31] Lua：Hello World
来源：http://dali.shangyingyoupin.top/Article/details/gtyiojbzbw.html

print("Hello")
来源：http://dali.ydzc1.top/Article/details/gtejioegbs.html

[T32] Lua：局部变量
来源：http://dali.zhiwuduotai.top/Article/details/gtvqnvarvp.html

local a = 1
来源：http://dali.jlsjyb.cn/Article/details/gtuvfxhjmf.html

[T33] Lua：表（数组）
来源：http://dali.zhengqikj.top/Article/details/gtounortdz.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.tanke756.top/Article/details/gthwbfuelr.html

[T34] Lua：遍历表
来源：http://dali.chenlongwang.top/Article/details/gtwudhbcue.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.fengsongda.top/Article/details/gtvgudykch.html

[T35] Lua：字典表
来源：http://dali.cdnleiting.top/Article/details/gtupmsupcm.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gtkqpyhlcu.html

[T36] Lua：函数
来源：http://dali.nanxinkj.top/Article/details/gtndbjewnb.html

function add(a, b) return a + b end
来源：http://dali.jinqigufen.top/Article/details/gtnbdcpdwm.html

[T37] Lua：字符串拼接
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyztqktkq.html

"a" .. "b"
来源：http://dali.aibaodan.cn/Article/details/gtwrvqhzia.html

[T38] Lua：条件
来源：http://dali.xinyue.icu/Article/details/gtecwlwmrk.html

if x > 0 then print("正") end
来源：http://dali.snrcjt.cn/Article/details/gthxeecetp.html

[T39] Lua：模式匹配
来源：http://dali.gaohongyu789.top/Article/details/gtvmuoekpe.html

string.find(s, "%d+")
来源：http://dali.jlsjyb.cn/Article/details/gtwadgdmii.html

[T40] Lua：元表
来源：http://dali.pengpengdd.cyou/Article/details/gtqcbrdzga.html

setmetatable({}, { __index = base })
来源：http://dali.jinqigfzy.top/Article/details/gtasemoftx.html

[T41] Perl：Hello World
来源：http://dali.cucudq.cn/Article/details/gtjsimrsfb.html

print "Hello\n";
来源：http://dali.shzxlz.cn/Article/details/gtsrecqwmn.html

[T42] Perl：变量类型
来源：http://dali.yueranfly.top/Article/details/gtmnzvkqei.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.aizwys.cn/Article/details/gtztazgnuf.html

[T43] Perl：字符串插值
来源：http://dali.yuxming.cn/Article/details/gtdkydgjrp.html

"值: $a"
来源：http://dali.jqgfzy.top/Article/details/gtaxycaaxq.html

[T44] Perl：条件
来源：http://dali.yongpay.top/Article/details/gtzybeimhu.html

if ($a > 0) { print "正"; }
来源：http://dali.tian-w.cn/Article/details/gthgrplzmj.html

[T45] Perl：数组遍历
来源：http://dali.kuanghao11.cn/Article/details/gtkpeaesrr.html

for my $x (@arr) { print $x; }
来源：http://dali.vqdsnc.cn/Article/details/gtzrapvhbe.html

[T46] Perl：哈希操作
来源：http://dali.tanke756.top/Article/details/gtfscupedu.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.daria6918.cn/Article/details/gtndhhjvcm.html

[T47] Perl：正则捕获
来源：http://dali.xuanzx.com/Article/details/gtfchgsfdz.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.ivvv.top/Article/details/gtibditcnt.html

[T48] Perl：正则替换
来源：http://dali.zhoulong.xyz/Article/details/gtespcbybe.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gtlgxtookl.html

[T49] Perl：函数
来源：http://dali.zhongyouzk.top/Article/details/gtrkwsgmkg.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.shuidangran.top/Article/details/gtrsumznce.html

[T50] Perl：逐行读文件
来源：http://dali.nwbrower.top/Article/details/gtbnxkokwx.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxdldlwat.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.jqgufenzy.top/Article/details/gtfelvxaba.html

[T51] Scala：Hello World
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyczfrynl.html

println("Hello")
来源：http://dali.fengsongda.top/Article/details/gtwiscmxus.html

[T52] Scala：变量
来源：http://dali.hysaishi.cn/Article/details/gtynmpfhlt.html

val a = 1;  var b = 2
来源：http://dali.gaohongyu789.top/Article/details/gtizumdmuz.html

[T53] Scala：字符串插值
来源：http://dali.feifeiyinyue.top/Article/details/gtcbkozxoi.html

s"值: $b"
来源：http://dali.zhongyouzk.top/Article/details/gtfxmdqzlz.html

[T54] Scala：集合映射
来源：http://dali.hongshengwenyu.top/Article/details/gtiwmdatpm.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.aibaodan.cn/Article/details/gtkdpydfwr.html

[T55] Scala：集合过滤
来源：http://dali.yuanzhike.top/Article/details/gtrjdicjny.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.cashguo.top/Article/details/gtpdfadexz.html

[T56] Scala：样例类
来源：http://dali.ppjwa.cn/Article/details/gtdoajssfg.html

case class User(name: String, age: Int)
来源：http://dali.shangyingyoupin.top/Article/details/gtemlmqtnr.html

[T57] Scala：模式匹配
来源：http://dali.haohaochexian.top/Article/details/gtawzadtih.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmgofldvi.html

[T58] Scala：函数定义
来源：http://dali.ybcxt.top/Article/details/gttcstupwh.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.316326.xyz/Article/details/gtlfvasjom.html

[T59] Scala：循环
来源：http://dali.316326.xyz/Article/details/gtzxpsewaw.html

for (i <- 1 to 10) println(i)
来源：http://dali.aizwys.cn/Article/details/gtgaysbegv.html

[T60] Scala：折叠
来源：http://dali.cdnleiting.top/Article/details/gtdvjtxdks.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.haohaochexian.top/Article/details/gtnkfojzdl.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtdlhbdxoz.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.gzhubu.top/Article/details/gtjtmpmcrf.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtwcfaoaox.html

[U01] Py：创建虚拟环境
来源：http://dali.havefunace.top/Article/details/gtjzchcirl.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.gotoacloud.top/Article/details/gtrrwwlohy.html

[U02] Py：导出 / 安装依赖
来源：http://dali.sysykeji.top/Article/details/gtjopcxjwp.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhengqikj.top/Article/details/gtmfimezhf.html


<!-- 参考信息 -->