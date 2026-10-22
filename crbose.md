代发 wailian999

free -h;  ps aux | grep nginx
来源：http://dali.hnxiangtu.top/Article/details/gtombbalhh.html

[R64] 结束进程
来源：http://dali.nanxinkj.top/Article/details/gtaedtzhgb.html

kill -9 $(pgrep -f app.py)
来源：http://dali.hfpthk.cn/Article/details/gtesxlsdlp.html

[R65] 查看端口占用
来源：http://dali.kuanghao11.cn/Article/details/gtkiozeimq.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.cqqwz.cn/Article/details/gtixcjjqjg.html

[R66] 定时任务
来源：http://dali.ydzc1.top/Article/details/gtpjjmkqil.html

crontab -e;  crontab -l
来源：http://dali.jinqigufen.top/Article/details/gtjpcdecnn.html

[R67] 生成随机十六进制串
来源：http://dali.guowangkeji.top/Article/details/gtytnylbds.html

openssl rand -hex 16
来源：http://dali.hnqzz.top/Article/details/gtimvulomb.html

[R68] 计算文件校验值
来源：http://dali.cheryme.top/Article/details/gtpwnuexsw.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.daxiang520.top/Article/details/gtitfvvzcs.html

[R69] 生成随机密码
来源：http://dali.jqgufenzy.top/Article/details/gtagdqlgsz.html

head -c 16 /dev/urandom | base64
来源：http://dali.sxryk.cn/Article/details/gtchvmraeb.html

[R70] 时间戳与互转
来源：http://dali.shzxlz.cn/Article/details/gtvaqexdvo.html

date +%s;  date -d @1700000000
来源：http://dali.wangdashe.top/Article/details/gttnahpycv.html

[R71] 日期格式化
来源：http://dali.hnxiangtu.top/Article/details/gtzqrvknbv.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.xylfe.cn/Article/details/gtodsconjg.html

[R72] 等待端口就绪
来源：http://dali.xylfe.cn/Article/details/gtagydqypz.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhixingplan.top/Article/details/gtqvihgnfp.html

[R73] 分割大日志
来源：http://dali.pycfn.com/Article/details/gtdlmhxdth.html

split -l 1000 big.log part_
来源：http://dali.jinghuilouyu.cn/Article/details/gtuyovhqrj.html

[R74] 批量重命名
来源：http://dali.sweek.top/Article/details/gtnfjhdqwc.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.xylfe.cn/Article/details/gtmpbphbjg.html

[R75] 导出环境变量
来源：http://dali.sxryk.cn/Article/details/gtrnesfpaw.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.jyoumei.cn/Article/details/gtgqejklvy.html

[R76] 使用临时文件
来源：http://dali.tanke756.top/Article/details/gtwonmkydj.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.hnxiangtu.top/Article/details/gtaoskilff.html

[R77] 读取用户输入
来源：http://dali.c1oappe.top/Article/details/gtoafoxxoy.html

read -rp "请输入: " ans
来源：http://dali.ywan-chungtsiang.top/Article/details/gtltnzblsb.html

[R78] 交互式菜单
来源：http://dali.yangfankeji.com/Article/details/gtgvbmtkqm.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.tian-w.cn/Article/details/gtlfgyengq.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gtopznfunz.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.hnxiangtu.top/Article/details/gtmobkbuiz.html

[R80] 查看脚本执行耗时
来源：http://dali.yangfankeji.com/Article/details/gtzuksiums.html

time ./run.sh
来源：http://dali.andypj.xyz/Article/details/gtohdfwfxk.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtbafyxvkt.html

S. C / C++ 专题
来源：http://dali.cdnleiting.top/Article/details/gtgoivwqdl.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtfwelprnv.html

[S01] C：Hello World
来源：http://dali.xuetiantiany.cn/Article/details/gtbhcvbpgq.html

#include <stdio.h>
来源：http://dali.jlsjyb.cn/Article/details/gtyorpvkfh.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxyplojkq.html

[S02] C：变量与格式化输出
来源：http://dali.jyoumei.cn/Article/details/gtvymqqisw.html

int a = 10; printf("%d\n", a);
来源：http://dali.ppjwa.cn/Article/details/gtafibscbx.html

[S03] C：读入整数
来源：http://dali.xylfe.cn/Article/details/gtcmexcafh.html

int x; scanf("%d", &x);
来源：http://dali.jqgufenzy.top/Article/details/gtwuzvuooi.html

[S04] C：字符串复制
来源：http://dali.dianchejie.cn/Article/details/gtsqtvnhmf.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.yuanzhike.top/Article/details/gtzdfmjhij.html

[S05] C：字符串长度
来源：http://dali.mhx1999.top/Article/details/gtqmqzpszy.html

strlen(s)
来源：http://dali.gotoacloud.top/Article/details/gtmfpwonkp.html

[S06] C：字符串比较
来源：http://dali.yvedp.cn/Article/details/gtjxvyhmgx.html

strcmp(a, b) == 0
来源：http://dali.yj202588.top/Article/details/gtogxhjydx.html

[S07] C：数组遍历求和
来源：http://dali.xuetiantiany.cn/Article/details/gtvyvsyfzn.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.yongpay.top/Article/details/gtniduuuau.html

[S08] C：动态内存分配与释放
来源：http://dali.meibo888.top/Article/details/gtdqmtfxlc.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.daria6918.cn/Article/details/gtkdhszysy.html

[S09] C：结构体定义与初始化
来源：http://dali.ppjwa.cn/Article/details/gthjpjrazv.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gtlspdaybq.html

[S10] C：指针与解引用
来源：http://dali.andypj.xyz/Article/details/gtjevtaqpp.html

int *p = &a;  *p = 5;
来源：http://dali.meibo888.top/Article/details/gthrnpwdlf.html

[S11] C：逐行读文件
来源：http://dali.wangdashe.top/Article/details/gtrvltkbxn.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.jinqigufen.top/Article/details/gtauigcqmv.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.jqgufenzy.top/Article/details/gtdgdyhkch.html

fclose(f);
来源：http://dali.guowangkeji.top/Article/details/gtiopwnkmu.html

[S12] C：写文件
来源：http://dali.xuetiantiany.cn/Article/details/gtqqqooarb.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zycfv.cn/Article/details/gtiuxyuqkx.html

[S13] C：宏定义
来源：http://dali.jinqigufen.top/Article/details/gtyngqxqau.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.feifeiyinyue.top/Article/details/gtfcsqzijw.html

[S14] C：枚举
来源：http://dali.hammf.cn/Article/details/gtwfdaexnn.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhengqikj.top/Article/details/gtgellqbey.html

[S15] C：类型转换
来源：http://dali.ivvv.top/Article/details/gterceguxu.html

(double) a / b
来源：http://dali.bjfxy.top/Article/details/gtagymerrs.html

[S16] C：位操作置位
来源：http://dali.xuanzx.com/Article/details/gtjpxajyth.html

x |= (1 << 3);
来源：http://dali.aizwys.cn/Article/details/gtnhhiooaq.html

[S17] C：安全拼接字符串
来源：http://dali.nwbrower.top/Article/details/gtmlstrhil.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.yangfankeji.com/Article/details/gtydycxnmp.html

[S18] C：命令行参数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkrrbtwav.html

int main(int argc, char **argv)
来源：http://dali.jinghuilouyu.cn/Article/details/gtwfuzfrvb.html

[S19] C：快速排序
来源：http://dali.ivvv.top/Article/details/gtpfgffzdb.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.shangyingyoupin.top/Article/details/gtamxyaacp.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gtenfmctqm.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.sxryk.cn/Article/details/gtltucjrfv.html

[S21] C：字符类别判断
来源：http://dali.chenlongwang.top/Article/details/gtgjrclkyz.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.iojbl.cn/Article/details/gtygkyzhrm.html

[S22] C：字符串转数字
来源：http://dali.yuxming.cn/Article/details/gtagnpluwu.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.hongshengwenyu.top/Article/details/gtarqeqpzk.html

[S23] C：随机数
来源：http://dali.hywenlv.cn/Article/details/gttyguvoqb.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzunqxaje.html

[S24] C：获取本地时间
来源：http://dali.yj20258888.top/Article/details/gtzakmlskk.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.snrcjt.cn/Article/details/gtktwieaer.html

[S25] C：内存拷贝
来源：http://dali.0kj1m.cn/Article/details/gtrskxiwnt.html

memcpy(dst, src, n);
来源：http://dali.shanyushiyangtech.top/Article/details/gtxhqkpltz.html

[S26] C：内存清零
来源：http://dali.c1oappe.top/Article/details/gtmaslhvkq.html

memset(a, 0, sizeof a);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvzjujnoy.html

[S27] C：定义常量
来源：http://dali.shangyingyoupin.top/Article/details/gtcsvzwdwd.html

const double PI = 3.14159;
来源：http://dali.yueranfly.top/Article/details/gtaotrqsaw.html

[S28] C：静态变量
来源：http://dali.cheryme.top/Article/details/gtlpujqfbp.html

static int counter = 0;
来源：http://dali.yueranfly.top/Article/details/gtsimqhgqq.html

[S29] C：变参函数
来源：http://dali.guowangkeji.top/Article/details/gtutjyxpnq.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.tianlin.xyz/Article/details/gtkdfudsjo.html

[S30] C：头文件保护
来源：http://dali.yuxming.cn/Article/details/gtqybsvjzz.html

#ifndef X_H
来源：http://dali.yj20258.top/Article/details/gttqqbjang.html

#define X_H
来源：http://dali.zhoulong.xyz/Article/details/gtswqsacxq.html

#endif
来源：http://dali.yj202588.top/Article/details/gtmtzddkhk.html

[S31] C++：Hello World
来源：http://dali.aizwys.cn/Article/details/gtqvxxelko.html

#include <iostream>
来源：http://dali.snrcjt.cn/Article/details/gtyxyflrdb.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.xylfe.cn/Article/details/gtsegcuxjr.html

[S32] C++：字符串
来源：http://dali.dianchejie.cn/Article/details/gtmcwogvsb.html

std::string s = "hi";  s += "!";
来源：http://dali.zhaomingkeji.xyz/Article/details/gtllyilcit.html

[S33] C++：vector 增删
来源：http://dali.cdnleiting.top/Article/details/gtcvecseec.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.hnqzz.top/Article/details/gtntxkabnp.html

[S34] C++：遍历 vector
来源：http://dali.pengpengdd.cyou/Article/details/gtpwilavbj.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtubcaazbq.html

[S35] C++：map
来源：http://dali.ydzc1.top/Article/details/gtpmtffete.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yonumen.top/Article/details/gtkqdbcamv.html

[S36] C++：unordered_map
来源：http://dali.yueranfly.top/Article/details/gtnxagtlob.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.havefunace.top/Article/details/gtxsanaocu.html

[S37] C++：set
来源：http://dali.mhx1999.top/Article/details/gtfeliwtbf.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhiwuduotai.top/Article/details/gtjnzrhndt.html

[S38] C++：排序
来源：http://dali.chenjidiqi.icu/Article/details/gtoaqkcmfe.html

std::sort(v.begin(), v.end());
来源：http://dali.fzhhl.top/Article/details/gtxpijrjcd.html

[S39] C++：自定义比较器排序
来源：http://dali.pycfn.com/Article/details/gteafkvexl.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.snrcjt.cn/Article/details/gtqagptfhw.html

[S40] C++：查找元素
来源：http://dali.0kj1m.cn/Article/details/gtwqychvdk.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.sxryk.cn/Article/details/gtfbkkklrq.html

[S41] C++：类与构造函数
来源：http://dali.yangfankeji.com/Article/details/gtjfhnnbzy.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.quarkkingdee.top/Article/details/gtgcatowzw.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gtiedxfanp.html

class B : public Base { public: void f() override {} };
来源：http://dali.chenlongwang.top/Article/details/gtnfhkxxjv.html

[S43] C++：智能指针
来源：http://dali.jlsjyb.cn/Article/details/gtgukugmim.html

auto p = std::make_unique<int>(5);
来源：http://dali.zdqjudy.top/Article/details/gtyhfetkjc.html

[S44] C++：引用传参
来源：http://dali.hnqzz.top/Article/details/gtwlndtgtt.html

void inc(int &x) { ++x; }
来源：http://dali.daria6918.cn/Article/details/gtahitwkpz.html

[S45] C++：lambda
来源：http://dali.jlsjyb.cn/Article/details/gtljhufirb.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.aibaodan.cn/Article/details/gtouduflvr.html

[S46] C++：函数模板
来源：http://dali.chenjidiqi.icu/Article/details/gthwwczhxg.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.dashuyun.cn/Article/details/gtvfznwviv.html

[S47] C++：结构化绑定遍历
来源：http://dali.cdnleiting.top/Article/details/gttvhtpuvx.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.yueranfly.top/Article/details/gtkdtpjnnn.html

[S48] C++：逐行读文件
来源：http://dali.zhongyouzk.top/Article/details/gtnixbdnhc.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.chenjidiqi.icu/Article/details/gtpfmzslpk.html

while (std::getline(in, line)) { }
来源：http://dali.chenjidiqi.icu/Article/details/gtcqolyueb.html

[S49] C++：写文件
来源：http://dali.mhx1999.top/Article/details/gttxnucqix.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.jinqigfzy.top/Article/details/gtlkxjdhew.html

[S50] C++：格式化数字
来源：http://dali.ppjwa.cn/Article/details/gtuhqgmdmk.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.shanyushiyangtech.top/Article/details/gtnwjdbqfx.html

[S51] C++：显式类型转换
来源：http://dali.9152youxi.cn/Article/details/gtvbdidbqx.html

static_cast<double>(a) / b
来源：http://dali.yanxiufei.cn/Article/details/gtkosznyvk.html

[S52] C++：const 与 noexcept
来源：http://dali.yj20258888.top/Article/details/gtewoxnzjj.html

int size() const noexcept { return n_; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnlnwaeym.html

[S53] C++：移动语义
来源：http://dali.redwolf501.top/Article/details/gtxqjohdye.html

std::vector<int> w = std::move(v);
来源：http://dali.gotoacloud.top/Article/details/gtbxxsrjiz.html

[S54] C++：异常处理
来源：http://dali.yj20258888.top/Article/details/gtrcagwhfb.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.svipenyu.cn/Article/details/gtzwqbbxoo.html

[S55] C++：结构化绑定
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvxfeojar.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.bjfxy.top/Article/details/gtvekilvbk.html

[S56] C++：optional
来源：http://dali.zhixingplan.top/Article/details/gtqbidsrwu.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.mhx1999.top/Article/details/gtwxrdhwid.html

[S57] C++：编译期常量
来源：http://dali.yj20258.top/Article/details/gtpeihclsv.html

constexpr int N = 10;
来源：http://dali.ybcxt.top/Article/details/gtztitiead.html

[S58] C++：命名空间
来源：http://dali.hfpthk.cn/Article/details/gtbmizpjcf.html

namespace ns { int f() { return 1; } }
来源：http://dali.xuetiantiany.cn/Article/details/gtvvvrdqae.html

[S59] C++：静态断言
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwvdszyve.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.jqgufenzy.top/Article/details/gtifdinxit.html

[S60] C++：遍历并删除元素
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrrbwyaqj.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.shzxlz.cn/Article/details/gtjyistaow.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtuhisbfaq.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.xziqi.cn/Article/details/gtdqrckaqt.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtmveiawbu.html

[T01] Kotlin：Hello World
来源：http://dali.zhongyouzk.top/Article/details/gtnrxykoie.html

println("Hello")
来源：http://dali.xziqi.cn/Article/details/gtwsuxrufg.html

[T02] Kotlin：变量
来源：http://dali.ehwqpu.com/Article/details/gtziwpkqfw.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.cdnleiting.top/Article/details/gtbukgjbcc.html

[T03] Kotlin：字符串模板
来源：http://dali.cdnleiting.top/Article/details/gtphnokuvr.html

"值: $b"
来源：http://dali.0kj1m.cn/Article/details/gtkpoypmac.html

[T04] Kotlin：空安全
来源：http://dali.ppjwa.cn/Article/details/gtveowudqi.html

val n: String? = null;  n?.length
来源：http://dali.zhixingplan.top/Article/details/gthstlpyyz.html

[T05] Kotlin：when 表达式
来源：http://dali.cdnleiting.top/Article/details/gtxrebrtcs.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.daria6918.cn/Article/details/gtygydbrby.html

[T06] Kotlin：集合映射
来源：http://dali.shuidangran.top/Article/details/gtubbyfgse.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.jyoumei.cn/Article/details/gtfaypgzra.html

[T07] Kotlin：集合过滤
来源：http://dali.sufxvd.cn/Article/details/gtxektidgo.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhixingplan.top/Article/details/gttmsqpmjy.html

[T08] Kotlin：数据类
来源：http://dali.tianlin.xyz/Article/details/gtjkucquto.html

data class User(val name: String, val age: Int)
来源：http://dali.xuanzx.com/Article/details/gtkgkllpsy.html

[T09] Kotlin：扩展函数
来源：http://dali.havefunace.top/Article/details/gtxtphxxuf.html

fun String.exclaim() = this + "!"
来源：http://dali.fzhhl.top/Article/details/gtbeoelwfh.html

[T10] Kotlin：默认参数
来源：http://dali.gotoacloud.top/Article/details/gtrijyrcuh.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.sxryk.cn/Article/details/gtawpmfrfp.html

[T11] Kotlin：协程
来源：http://dali.nwbrower.top/Article/details/gtnsqcomtk.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.ivvv.top/Article/details/gtikqjbdmf.html

[T12] Kotlin：解构声明
来源：http://dali.cqqwz.cn/Article/details/gttlbijftx.html

val (a, b) = Pair(1, 2)
来源：http://dali.shzxlz.cn/Article/details/gtagvnqkup.html

[T13] Kotlin：只读 Map
来源：http://dali.ivvv.top/Article/details/gtqvjsmwzt.html

val m = mapOf("a" to 1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwhmmrwvf.html

[T14] Kotlin：循环
来源：http://dali.quarkkingdee.top/Article/details/gtelzhwiyc.html

for (i in 1..10) println(i)
来源：http://dali.zhongyouzk.top/Article/details/gtjvbpsmay.html

[T15] Kotlin：接口
来源：http://dali.xinyue.icu/Article/details/gtaanooobp.html

interface Shape { fun area(): Double }
来源：http://dali.pengpengdd.cyou/Article/details/gtgyywhcsh.html

[T16] Swift：Hello World
来源：http://dali.daxiang520.top/Article/details/gttsttceud.html

print("Hello")
来源：http://dali.316326.xyz/Article/details/gtuiesgedm.html

[T17] Swift：变量与常量
来源：http://dali.mhx1999.top/Article/details/gtlwctriie.html

var a = 1;  let b = 2
来源：http://dali.yonumen.top/Article/details/gtyawqgyis.html

[T18] Swift：字符串插值
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuuwiboqc.html

"值: \(b)"
来源：http://dali.tian-w.cn/Article/details/gtmfqhctmu.html

[T19] Swift：可选绑定
来源：http://dali.yanxiufei.cn/Article/details/gtroszopyz.html

if let n = opt { print(n) }
来源：http://dali.yongpay.top/Article/details/gtzfhdoyzn.html

[T20] Swift：数组操作
来源：http://dali.daria6918.cn/Article/details/gtkkkyghfa.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.havefunace.top/Article/details/gtyjqbogor.html

[T21] Swift：遍历
来源：http://dali.sufxvd.cn/Article/details/gthhlwvjds.html

for x in a { print(x) }
来源：http://dali.yanxiufei.cn/Article/details/gtthaiswgx.html

[T22] Swift：字典
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqbdlxjxr.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.cdnleiting.top/Article/details/gtkyhhgboz.html

[T23] Swift：函数
来源：http://dali.hongshengwenyu.top/Article/details/gtefhgvfwo.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.shanyushiyangtech.top/Article/details/gtvptzgrwq.html

[T24] Swift：闭包
来源：http://dali.aibaodan.cn/Article/details/gtfdkkfgot.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.jqgufenzy.top/Article/details/gtsibylgil.html

[T25] Swift：结构体
来源：http://dali.ehwqpu.com/Article/details/gtekdpthnk.html

struct P { var x: Int }
来源：http://dali.dashuyun.cn/Article/details/gttknzkerd.html

[T26] Swift：类与重写
来源：http://dali.hammf.cn/Article/details/gtnwcosyut.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gtuqcayusx.html

[T27] Swift：错误处理
来源：http://dali.hongshengwenyu.top/Article/details/gtonawztva.html

do { try f() } catch { print(error) }
来源：http://dali.yvedp.cn/Article/details/gtkosuyohu.html

[T28] Swift：枚举
来源：http://dali.zhiwuduotai.top/Article/details/gtzuvmmxhi.html

enum Color { case red, green }
来源：http://dali.yonumen.top/Article/details/gtkgxwenes.html

[T29] Swift：guard 提前返回
来源：http://dali.yvedp.cn/Article/details/gtqmtongdt.html

guard let x = opt else { return }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtirxgaxac.html

[T30] Swift：协议
来源：http://dali.ehwqpu.com/Article/details/gtlwzdvluq.html

protocol Shape { func area() -> Double }
来源：http://dali.dianchejie.cn/Article/details/gtxldctlhc.html

[T31] Lua：Hello World
来源：http://dali.9152youxi.cn/Article/details/gtbujbscpw.html

print("Hello")
来源：http://dali.yangfankeji.com/Article/details/gthzncplsn.html

[T32] Lua：局部变量
来源：http://dali.hnxiangtu.top/Article/details/gteppiwwvx.html

local a = 1
来源：http://dali.smart0.xyz/Article/details/gtefjxcnfz.html

[T33] Lua：表（数组）
来源：http://dali.havefunace.top/Article/details/gtcwndpfus.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.jinqigfzy.top/Article/details/gtpftfapbh.html

[T34] Lua：遍历表
来源：http://dali.ywan-chungtsiang.top/Article/details/gtparnrrzj.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.dashuyun.cn/Article/details/gtyktacied.html

[T35] Lua：字典表
来源：http://dali.shangyingyoupin.top/Article/details/gtfoueydxq.html

local d = { a = 1 };  d.b = 2
来源：http://dali.guowangkeji.top/Article/details/gtpfrtaawe.html

[T36] Lua：函数
来源：http://dali.zhiwuduotai.top/Article/details/gtnairmono.html

function add(a, b) return a + b end
来源：http://dali.hammf.cn/Article/details/gtccnemkxb.html

[T37] Lua：字符串拼接
来源：http://dali.jinghuilouyu.cn/Article/details/gtbnnrcsyz.html

"a" .. "b"
来源：http://dali.pengpengdd.cyou/Article/details/gtfvlmsgdv.html

[T38] Lua：条件
来源：http://dali.fzhhl.top/Article/details/gthlgkivzd.html

if x > 0 then print("正") end
来源：http://dali.sufxvd.cn/Article/details/gtjsrzvfer.html

[T39] Lua：模式匹配
来源：http://dali.kuanghao11.cn/Article/details/gtrixcegvc.html

string.find(s, "%d+")
来源：http://dali.zhengqikj.top/Article/details/gtzcadgnvf.html

[T40] Lua：元表
来源：http://dali.shanyushiyangkeji.top/Article/details/gtodterenv.html

setmetatable({}, { __index = base })
来源：http://dali.tianlin.xyz/Article/details/gtlvybyzqo.html

[T41] Perl：Hello World
来源：http://dali.gaohongyu789.top/Article/details/gteejenovo.html

print "Hello\n";
来源：http://dali.cucudq.cn/Article/details/gtzhjxhxsk.html

[T42] Perl：变量类型
来源：http://dali.shanyushiyangtech.top/Article/details/gtdycfgshu.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.yonumen.top/Article/details/gtmejoihkh.html

[T43] Perl：字符串插值
来源：http://dali.xuanzx.com/Article/details/gtktpkavqw.html

"值: $a"
来源：http://dali.zhoulong.xyz/Article/details/gtncybccvi.html

[T44] Perl：条件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmxmcwhpy.html

if ($a > 0) { print "正"; }
来源：http://dali.gotoacloud.top/Article/details/gtxxylrqsh.html

[T45] Perl：数组遍历
来源：http://dali.pengpengdd.cyou/Article/details/gtruvezpfc.html

for my $x (@arr) { print $x; }
来源：http://dali.yueranfly.top/Article/details/gtassrfyqf.html

[T46] Perl：哈希操作
来源：http://dali.jqgufenzy.top/Article/details/gtnoxzzmhq.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.mhx1999.top/Article/details/gtnigofcxb.html

[T47] Perl：正则捕获
来源：http://dali.chenzaomai.com/Article/details/gtroxpwcpy.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.daxiang520.top/Article/details/gtpsvavghh.html

[T48] Perl：正则替换
来源：http://dali.jlsjyb.cn/Article/details/gtvmeisrbr.html

$s =~ s/old/new/g;
来源：http://dali.chenzaomai.com/Article/details/gtrbcafwst.html

[T49] Perl：函数
来源：http://dali.yj20258888.top/Article/details/gtipkymmdm.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.yj20258.top/Article/details/gtvqyoxwhp.html

[T50] Perl：逐行读文件
来源：http://dali.hfpthk.cn/Article/details/gtvgifvzlw.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.yvedp.cn/Article/details/gtygjvwlrh.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.sufxvd.cn/Article/details/gtannqewhh.html

[T51] Scala：Hello World
来源：http://dali.fzhhl.top/Article/details/gtsbdparhp.html

println("Hello")
来源：http://dali.pycfn.com/Article/details/gteiimhmlg.html

[T52] Scala：变量
来源：http://dali.hammf.cn/Article/details/gtsawvzebu.html

val a = 1;  var b = 2
来源：http://dali.cucudq.cn/Article/details/gtjzmzspcf.html

[T53] Scala：字符串插值
来源：http://dali.pengpengdd.cyou/Article/details/gthteqcywv.html

s"值: $b"
来源：http://dali.zdqjudy.top/Article/details/gtrtqgrage.html

[T54] Scala：集合映射
来源：http://dali.kuanghao11.cn/Article/details/gtjehieqdt.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.ppjwa.cn/Article/details/gtbrcppvco.html

[T55] Scala：集合过滤
来源：http://dali.haohaochexian.top/Article/details/gtiumghqil.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.sweek.top/Article/details/gtuewmkaui.html

[T56] Scala：样例类
来源：http://dali.hysaishi.cn/Article/details/gtmwgqgrln.html

case class User(name: String, age: Int)
来源：http://dali.jinqigufen.top/Article/details/gtnflytxzi.html

[T57] Scala：模式匹配
来源：http://dali.quarkkingdee.top/Article/details/gtchwxofvv.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.nwbrower.top/Article/details/gtztwwtnbs.html

[T58] Scala：函数定义
来源：http://dali.gogol.net.cn/Article/details/gtuilwcqef.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.daxiang520.top/Article/details/gtgcsitwfe.html

[T59] Scala：循环
来源：http://dali.hnxiangtu.top/Article/details/gtxqvlyamt.html

for (i <- 1 to 10) println(i)
来源：http://dali.cdnleiting.top/Article/details/gtoihplogc.html

[T60] Scala：折叠
来源：http://dali.yj20258888.top/Article/details/gtbacthwgy.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.shuidangran.top/Article/details/gtnoprphxx.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtwnzqkovp.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.hongshengwenyu.top/Article/details/gtamfvojra.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtphmguyms.html

[U01] Py：创建虚拟环境
来源：http://dali.cheryme.top/Article/details/gtmopiuahv.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.shangyingyoupin.top/Article/details/gtbkmttrjk.html

[U02] Py：导出 / 安装依赖
来源：http://dali.xuetiantiany.cn/Article/details/gtymcojssk.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhoulong.xyz/Article/details/gtcpvykkce.html

[U03] Py：加载 .env 配置
来源：http://dali.jqgfzy.top/Article/details/gtmihctlot.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.jqgufenzy.top/Article/details/gtumddiqlp.html

[U04] Py：变量调试打印
来源：http://dali.feifeiyinyue.top/Article/details/gtawyyftnb.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.svipenyu.cn/Article/details/gtyzsqsqvh.html


<!-- 参考信息 -->