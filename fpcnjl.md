代发 wailian999

df -h;  du -sh *
来源：http://dali.gotoacloud.top/Article/details/gtcdjzplnu.html

[R62] 找最占空间的文件
来源：http://dali.xylfe.cn/Article/details/gtgafvbyvn.html

du -ah . | sort -rh | head -10
来源：http://dali.guannengcc.top/Article/details/gtorbqouht.html

[R63] 内存与进程
来源：http://dali.havefunace.top/Article/details/gtuypqzvwt.html

free -h;  ps aux | grep nginx
来源：http://dali.zhiwuduotai.top/Article/details/gtuvzlndir.html

[R64] 结束进程
来源：http://dali.zhongyouzk.top/Article/details/gtpbzdmapd.html

kill -9 $(pgrep -f app.py)
来源：http://dali.jyoumei.cn/Article/details/gtdzhrjohs.html

[R65] 查看端口占用
来源：http://dali.bjfxy.top/Article/details/gtkteftxxw.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.gogol.net.cn/Article/details/gtxsmwhbuf.html

[R66] 定时任务
来源：http://dali.jinghuilouyu.cn/Article/details/gtarhekllm.html

crontab -e;  crontab -l
来源：http://dali.birdmap.top/Article/details/gtpjuzlooo.html

[R67] 生成随机十六进制串
来源：http://dali.fzhhl.top/Article/details/gtuwvhmudl.html

openssl rand -hex 16
来源：http://dali.yj20258.top/Article/details/gtixsyezue.html

[R68] 计算文件校验值
来源：http://dali.nwbrower.top/Article/details/gtsylxkbxj.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.birdmap.top/Article/details/gtfpxotmlm.html

[R69] 生成随机密码
来源：http://dali.hfpthk.cn/Article/details/gtkroytgbs.html

head -c 16 /dev/urandom | base64
来源：http://dali.yuanzhike.top/Article/details/gtscnhksoa.html

[R70] 时间戳与互转
来源：http://dali.quarkkingdee.top/Article/details/gtrkmahybt.html

date +%s;  date -d @1700000000
来源：http://dali.hongshengwenyu.top/Article/details/gtrxvoxvwm.html

[R71] 日期格式化
来源：http://dali.vqdsnc.cn/Article/details/gtedquiwjs.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.jqgfzy.top/Article/details/gtpchbpjho.html

[R72] 等待端口就绪
来源：http://dali.cqqwz.cn/Article/details/gtcfcbgexf.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.dashuyun.cn/Article/details/gtaiewdbei.html

[R73] 分割大日志
来源：http://dali.aibaodan.cn/Article/details/gtohiqbrrm.html

split -l 1000 big.log part_
来源：http://dali.jinqigufen.top/Article/details/gtdrxmcpam.html

[R74] 批量重命名
来源：http://dali.jinyuanbaomall.cn/Article/details/gtomnjltkn.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.xziqi.cn/Article/details/gtryxmtuxl.html

[R75] 导出环境变量
来源：http://dali.shangyingyoupin.top/Article/details/gtjkqpycyc.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.cucudq.cn/Article/details/gtlqtchzbm.html

[R76] 使用临时文件
来源：http://dali.guowangkeji.top/Article/details/gtuaavzlmr.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.birdmap.top/Article/details/gtzwgqydgg.html

[R77] 读取用户输入
来源：http://dali.sufxvd.cn/Article/details/gtpnrfxcgf.html

read -rp "请输入: " ans
来源：http://dali.chenlongwang.top/Article/details/gtezepsvvl.html

[R78] 交互式菜单
来源：http://dali.chenzaomai.com/Article/details/gtjzshrrfh.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.shzxlz.cn/Article/details/gtpkjrezqv.html

[R79] 解析命令行选项
来源：http://dali.xinyue.icu/Article/details/gtwdxsjkjw.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.yuanzhike.top/Article/details/gtwhvxtvtg.html

[R80] 查看脚本执行耗时
来源：http://dali.hywenlv.cn/Article/details/gtwwdzlrps.html

time ./run.sh
来源：http://dali.havefunace.top/Article/details/gtdasudlvj.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gttcogbetu.html

S. C / C++ 专题
来源：http://dali.xylfe.cn/Article/details/gtlxiphywc.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtdgogzyls.html

[S01] C：Hello World
来源：http://dali.yuanzhike.top/Article/details/gtvvinrijp.html

#include <stdio.h>
来源：http://dali.yonumen.top/Article/details/gtvbziycmt.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.yanxiufei.cn/Article/details/gtltormsjh.html

[S02] C：变量与格式化输出
来源：http://dali.xziqi.cn/Article/details/gtshgwxgqv.html

int a = 10; printf("%d\n", a);
来源：http://dali.xuanzx.com/Article/details/gtmcsodtfv.html

[S03] C：读入整数
来源：http://dali.nanxinkj.top/Article/details/gtplqrxlqo.html

int x; scanf("%d", &x);
来源：http://dali.shzxlz.cn/Article/details/gtrbkbsfdw.html

[S04] C：字符串复制
来源：http://dali.tian-w.cn/Article/details/gtikusjgmz.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.guannengcc.top/Article/details/gtbgfarrke.html

[S05] C：字符串长度
来源：http://dali.c1oappe.top/Article/details/gtqgyrtxdm.html

strlen(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfjyuiyzg.html

[S06] C：字符串比较
来源：http://dali.yuxming.cn/Article/details/gtdxmbwbrk.html

strcmp(a, b) == 0
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkyyfyjwp.html

[S07] C：数组遍历求和
来源：http://dali.sufxvd.cn/Article/details/gtaczcdylb.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.jlsjyb.cn/Article/details/gtppxzviym.html

[S08] C：动态内存分配与释放
来源：http://dali.jqgfzy.top/Article/details/gtkedrbblp.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.nanxuanxn.top/Article/details/gtsdwooynz.html

[S09] C：结构体定义与初始化
来源：http://dali.yuxming.cn/Article/details/gtvbtmmrdz.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.yj20258888.top/Article/details/gtjqkezpfd.html

[S10] C：指针与解引用
来源：http://dali.bjfxy.top/Article/details/gtxlpeijwh.html

int *p = &a;  *p = 5;
来源：http://dali.tanke756.top/Article/details/gtjuaqtnhw.html

[S11] C：逐行读文件
来源：http://dali.cdnleiting.top/Article/details/gtihppeywo.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.cdnleiting.top/Article/details/gtrhwvbrvk.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhixingplan.top/Article/details/gtmonbzjop.html

fclose(f);
来源：http://dali.hnqzz.top/Article/details/gtnmgojccf.html

[S12] C：写文件
来源：http://dali.hammf.cn/Article/details/gteseqifpr.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.shuidangran.top/Article/details/gtlwbibfgl.html

[S13] C：宏定义
来源：http://dali.mhx1999.top/Article/details/gtuaeeecff.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrnwcoovz.html

[S14] C：枚举
来源：http://dali.0kj1m.cn/Article/details/gtcgharyem.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.feifeiyinyue.top/Article/details/gttbusqdlf.html

[S15] C：类型转换
来源：http://dali.nwbrower.top/Article/details/gtkhverhiy.html

(double) a / b
来源：http://dali.haohaochexian.top/Article/details/gtsnaxdofb.html

[S16] C：位操作置位
来源：http://dali.jyoumei.cn/Article/details/gtmspyoiol.html

x |= (1 << 3);
来源：http://dali.sufxvd.cn/Article/details/gtjngqpvai.html

[S17] C：安全拼接字符串
来源：http://dali.hnqzz.top/Article/details/gtsbufmqzo.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhoulong.xyz/Article/details/gtygfzyxrs.html

[S18] C：命令行参数
来源：http://dali.andypj.xyz/Article/details/gtmppgljdk.html

int main(int argc, char **argv)
来源：http://dali.gogol.net.cn/Article/details/gtjrciaqan.html

[S19] C：快速排序
来源：http://dali.zhaomingkeji.xyz/Article/details/gttjeipesq.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.shanyushiyangtech.top/Article/details/gtmpcbksnz.html

[S20] C：二分查找
来源：http://dali.meibo888.top/Article/details/gtxqfiobtl.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.yueranfly.top/Article/details/gtrhwayxra.html

[S21] C：字符类别判断
来源：http://dali.zdqjudy.top/Article/details/gthiqpwkkd.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.jinghuilouyu.cn/Article/details/gtdioyoank.html

[S22] C：字符串转数字
来源：http://dali.zhiwuduotai.top/Article/details/gtnpcqdxed.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.guowangkeji.top/Article/details/gthzsoaust.html

[S23] C：随机数
来源：http://dali.yanxiufei.cn/Article/details/gtrilhxmmm.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.hammf.cn/Article/details/gtepvklnak.html

[S24] C：获取本地时间
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmvrukuhq.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.sweek.top/Article/details/gtbrgjtlpw.html

[S25] C：内存拷贝
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrzhffswz.html

memcpy(dst, src, n);
来源：http://dali.zycfv.cn/Article/details/gtxjbmcnhp.html

[S26] C：内存清零
来源：http://dali.ydzc1.top/Article/details/gtgkavgcfn.html

memset(a, 0, sizeof a);
来源：http://dali.yuanzhike.top/Article/details/gtwvuislxh.html

[S27] C：定义常量
来源：http://dali.tanke756.top/Article/details/gtytybmmay.html

const double PI = 3.14159;
来源：http://dali.cqqwz.cn/Article/details/gtetkjpvig.html

[S28] C：静态变量
来源：http://dali.sufxvd.cn/Article/details/gtqrcvwwtj.html

static int counter = 0;
来源：http://dali.cashguo.top/Article/details/gtgjnbdwrb.html

[S29] C：变参函数
来源：http://dali.iojbl.cn/Article/details/gttopmmgfd.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.nanxuanxn.top/Article/details/gteulgkgre.html

[S30] C：头文件保护
来源：http://dali.xinyue.icu/Article/details/gtkecviwqz.html

#ifndef X_H
来源：http://dali.guannengcc.top/Article/details/gtmrezxxxm.html

#define X_H
来源：http://dali.pengpengdd.cyou/Article/details/gtfpqqhfvr.html

#endif
来源：http://dali.yangfankeji.com/Article/details/gtayxhlisn.html

[S31] C++：Hello World
来源：http://dali.jinghuilouyu.cn/Article/details/gtqetmsilb.html

#include <iostream>
来源：http://dali.ehwqpu.com/Article/details/gtnpcyfsqk.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.jqgfzy.top/Article/details/gtlpndjboj.html

[S32] C++：字符串
来源：http://dali.hammf.cn/Article/details/gthkubntdk.html

std::string s = "hi";  s += "!";
来源：http://dali.guannengcc.top/Article/details/gtfdpsbxbk.html

[S33] C++：vector 增删
来源：http://dali.hysaishi.cn/Article/details/gtkovqshjl.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhengqikj.top/Article/details/gtdfthgrlk.html

[S34] C++：遍历 vector
来源：http://dali.jlsjyb.cn/Article/details/gtccpewnyl.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.nanxuanxn.top/Article/details/gtgdpllvuv.html

[S35] C++：map
来源：http://dali.quarkkingdee.top/Article/details/gtovoifxxb.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.tianlin.xyz/Article/details/gtxpgvsbdo.html

[S36] C++：unordered_map
来源：http://dali.gogol.net.cn/Article/details/gtrlsftqvj.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.xuetiantiany.cn/Article/details/gthkxfoqar.html

[S37] C++：set
来源：http://dali.zhoulong.xyz/Article/details/gtidlflrbb.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.jqgfzy.top/Article/details/gtnmpkwqzw.html

[S38] C++：排序
来源：http://dali.sxryk.cn/Article/details/gthgvmmzvd.html

std::sort(v.begin(), v.end());
来源：http://dali.zdqjudy.top/Article/details/gtyoivmliq.html

[S39] C++：自定义比较器排序
来源：http://dali.hammf.cn/Article/details/gtlqcprzcw.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvzpdoptd.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gtwpiecrkq.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhongyouzk.top/Article/details/gtwqmxnlzv.html

[S41] C++：类与构造函数
来源：http://dali.hnqzz.top/Article/details/gtxphxdebi.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.redwolf501.top/Article/details/gtvnserzap.html

[S42] C++：继承与虚函数
来源：http://dali.hnqzz.top/Article/details/gtgyrvuqje.html

class B : public Base { public: void f() override {} };
来源：http://dali.kuanghao11.cn/Article/details/gtblgcuzmu.html

[S43] C++：智能指针
来源：http://dali.yonumen.top/Article/details/gtppszabmi.html

auto p = std::make_unique<int>(5);
来源：http://dali.xuanzx.com/Article/details/gtycovjqfi.html

[S44] C++：引用传参
来源：http://dali.tanke756.top/Article/details/gtjqvrmgwf.html

void inc(int &x) { ++x; }
来源：http://dali.jyoumei.cn/Article/details/gttlagnmvm.html

[S45] C++：lambda
来源：http://dali.jinyuanbaomall.cn/Article/details/gterdwhnjv.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.tianlin.xyz/Article/details/gtydssnjys.html

[S46] C++：函数模板
来源：http://dali.andypj.xyz/Article/details/gtfadioxwu.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.jianghu66.top/Article/details/gtjcchlizo.html

[S47] C++：结构化绑定遍历
来源：http://dali.yuxming.cn/Article/details/gtgbbijjfi.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.xziqi.cn/Article/details/gtmvbxukko.html

[S48] C++：逐行读文件
来源：http://dali.mhx1999.top/Article/details/gtjhlawbjg.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.pycfn.com/Article/details/gtztygfsgm.html

while (std::getline(in, line)) { }
来源：http://dali.pycfn.com/Article/details/gtzuzxkvox.html

[S49] C++：写文件
来源：http://dali.iojbl.cn/Article/details/gtcbpufbsv.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.dashuyun.cn/Article/details/gtclynqogj.html

[S50] C++：格式化数字
来源：http://dali.ivvv.top/Article/details/gtpjpelsqi.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.guowangkeji.top/Article/details/gtzxeowhvg.html

[S51] C++：显式类型转换
来源：http://dali.yj202588.top/Article/details/gtizqisctf.html

static_cast<double>(a) / b
来源：http://dali.cqqwz.cn/Article/details/gtlzcmxyfq.html

[S52] C++：const 与 noexcept
来源：http://dali.yj20258888.top/Article/details/gtjzsmwxht.html

int size() const noexcept { return n_; }
来源：http://dali.jiagoushi.top/Article/details/gtkwwjsfvz.html

[S53] C++：移动语义
来源：http://dali.fengsongda.top/Article/details/gttvzdtvkj.html

std::vector<int> w = std::move(v);
来源：http://dali.andypj.xyz/Article/details/gtxftpajyg.html

[S54] C++：异常处理
来源：http://dali.jlsjyb.cn/Article/details/gtjjdefavu.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.jianghu66.top/Article/details/gtziaxctsr.html

[S55] C++：结构化绑定
来源：http://dali.jlsjyb.cn/Article/details/gtelesugkb.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.nanxinkj.top/Article/details/gtrgnflslp.html

[S56] C++：optional
来源：http://dali.hfpthk.cn/Article/details/gtdlwgxgjm.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.sufxvd.cn/Article/details/gtljjhfush.html

[S57] C++：编译期常量
来源：http://dali.chenjidiqi.icu/Article/details/gtlmxaxksx.html

constexpr int N = 10;
来源：http://dali.guowangkeji.top/Article/details/gtvddrpcds.html

[S58] C++：命名空间
来源：http://dali.smart0.xyz/Article/details/gtdiyalllr.html

namespace ns { int f() { return 1; } }
来源：http://dali.hnxiangtu.top/Article/details/gtpjnmmnrs.html

[S59] C++：静态断言
来源：http://dali.hywenlv.cn/Article/details/gtolaiigrq.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.jqgufenzy.top/Article/details/gtkpqzwgpx.html

[S60] C++：遍历并删除元素
来源：http://dali.snrcjt.cn/Article/details/gtyxhchega.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.yj202588.top/Article/details/gtgxzqjyji.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtkgacroao.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.c1oappe.top/Article/details/gteoecpeoe.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gthhwyvfyc.html

[T01] Kotlin：Hello World
来源：http://dali.bjfxy.top/Article/details/gtjqvjmyie.html

println("Hello")
来源：http://dali.c1oappe.top/Article/details/gtaxuudsut.html

[T02] Kotlin：变量
来源：http://dali.daxiang520.top/Article/details/gtzcnuvagf.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhiwuduotai.top/Article/details/gtxwdszfpi.html

[T03] Kotlin：字符串模板
来源：http://dali.ppjwa.cn/Article/details/gtfegfmpsm.html

"值: $b"
来源：http://dali.zdqjudy.top/Article/details/gtebcjqnmy.html

[T04] Kotlin：空安全
来源：http://dali.zycfv.cn/Article/details/gtdfqzoeof.html

val n: String? = null;  n?.length
来源：http://dali.jinqigufen.top/Article/details/gtibutioqt.html

[T05] Kotlin：when 表达式
来源：http://dali.shangyingyoupin.top/Article/details/gthlejpevx.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gtvwhqvwyn.html

[T06] Kotlin：集合映射
来源：http://dali.andypj.xyz/Article/details/gthbwcvwan.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.pengpengdd.cyou/Article/details/gtblqfdhru.html

[T07] Kotlin：集合过滤
来源：http://dali.yongpay.top/Article/details/gtdosiswxf.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.ybcxt.top/Article/details/gtyzerfkwm.html

[T08] Kotlin：数据类
来源：http://dali.nanxinkj.top/Article/details/gtzyogudal.html

data class User(val name: String, val age: Int)
来源：http://dali.ydzc1.top/Article/details/gtnxhhpqel.html

[T09] Kotlin：扩展函数
来源：http://dali.jqgufenzy.top/Article/details/gtypjxrqdq.html

fun String.exclaim() = this + "!"
来源：http://dali.shanyushiyangtech.top/Article/details/gtveavsenm.html

[T10] Kotlin：默认参数
来源：http://dali.snrcjt.cn/Article/details/gtbiryqlyh.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.ivvv.top/Article/details/gtxnblnvwr.html

[T11] Kotlin：协程
来源：http://dali.cheryme.top/Article/details/gtstzwydzl.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.shzxlz.cn/Article/details/gtfqfuuega.html

[T12] Kotlin：解构声明
来源：http://dali.xziqi.cn/Article/details/gtvtwjallr.html

val (a, b) = Pair(1, 2)
来源：http://dali.cqqwz.cn/Article/details/gteyvrncby.html

[T13] Kotlin：只读 Map
来源：http://dali.quarkkingdee.top/Article/details/gtujotqchl.html

val m = mapOf("a" to 1)
来源：http://dali.sweek.top/Article/details/gtyvwdqlgy.html

[T14] Kotlin：循环
来源：http://dali.nanxuanxn.top/Article/details/gtsmqsslut.html

for (i in 1..10) println(i)
来源：http://dali.jqgfzy.top/Article/details/gtaatjosgb.html

[T15] Kotlin：接口
来源：http://dali.jyoumei.cn/Article/details/gtavqpmuhx.html

interface Shape { fun area(): Double }
来源：http://dali.sufxvd.cn/Article/details/gtaclvwuwx.html

[T16] Swift：Hello World
来源：http://dali.cheryme.top/Article/details/gtgrbakctk.html

print("Hello")
来源：http://dali.guannengcc.top/Article/details/gtjmtegndi.html

[T17] Swift：变量与常量
来源：http://dali.redwolf501.top/Article/details/gtjhotlxfh.html

var a = 1;  let b = 2
来源：http://dali.hywenlv.cn/Article/details/gtxqnogsjz.html

[T18] Swift：字符串插值
来源：http://dali.chenjidiqi.icu/Article/details/gtxqkjtbup.html

"值: \(b)"
来源：http://dali.yj20258888.top/Article/details/gtkfbmewes.html

[T19] Swift：可选绑定
来源：http://dali.yuanzhike.top/Article/details/gtocymjvfw.html

if let n = opt { print(n) }
来源：http://dali.yj20258.top/Article/details/gtrwniobqe.html

[T20] Swift：数组操作
来源：http://dali.aibaodan.cn/Article/details/gtdfgzqnga.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.ybcxt.top/Article/details/gtvfngceei.html

[T21] Swift：遍历
来源：http://dali.havefunace.top/Article/details/gtfchuauxj.html

for x in a { print(x) }
来源：http://dali.xinyue.icu/Article/details/gtyxifiubd.html

[T22] Swift：字典
来源：http://dali.shuidangran.top/Article/details/gtiniwjsiq.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.svipenyu.cn/Article/details/gtprdtqohf.html

[T23] Swift：函数
来源：http://dali.xinyue.icu/Article/details/gtockwkvmr.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtppvrblls.html

[T24] Swift：闭包
来源：http://dali.zhixingplan.top/Article/details/gtgtcsplvq.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.c1oappe.top/Article/details/gtomwyfqck.html

[T25] Swift：结构体
来源：http://dali.jinghuilouyu.cn/Article/details/gtulymldrb.html

struct P { var x: Int }
来源：http://dali.jqgufenzy.top/Article/details/gtoagyhcet.html

[T26] Swift：类与重写
来源：http://dali.fzhhl.top/Article/details/gteadphhbb.html

class A: Base { override func f() {} }
来源：http://dali.shanyushiyangtech.top/Article/details/gtbrqlggrw.html

[T27] Swift：错误处理
来源：http://dali.snrcjt.cn/Article/details/gtjclbmyed.html

do { try f() } catch { print(error) }
来源：http://dali.zhiwuduotai.top/Article/details/gtxfvecutc.html

[T28] Swift：枚举
来源：http://dali.daxiang520.top/Article/details/gtjlbwezbp.html

enum Color { case red, green }
来源：http://dali.snrcjt.cn/Article/details/gtwnmtmeid.html

[T29] Swift：guard 提前返回
来源：http://dali.yuxming.cn/Article/details/gteidoeowe.html

guard let x = opt else { return }
来源：http://dali.zdqjudy.top/Article/details/gtygpsrjzg.html

[T30] Swift：协议
来源：http://dali.yvedp.cn/Article/details/gttszesxpf.html

protocol Shape { func area() -> Double }
来源：http://dali.jlsjyb.cn/Article/details/gtzutszgfp.html

[T31] Lua：Hello World
来源：http://dali.ywan-chungtsiang.top/Article/details/gteljdjjxe.html

print("Hello")
来源：http://dali.wangshuangyany.cn/Article/details/gthybhehqw.html

[T32] Lua：局部变量
来源：http://dali.nanxinkj.top/Article/details/gtdjeibrfx.html

local a = 1
来源：http://dali.nanxinkj.top/Article/details/gtlvbuopsj.html

[T33] Lua：表（数组）
来源：http://dali.iojbl.cn/Article/details/gtzdtnggkf.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.cheryme.top/Article/details/gtdrngmylr.html

[T34] Lua：遍历表
来源：http://dali.jinqigufen.top/Article/details/gtmqbrqujf.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.fengsongda.top/Article/details/gtkzuzehdh.html

[T35] Lua：字典表
来源：http://dali.shangyingyoupin.top/Article/details/gtuagrelhk.html

local d = { a = 1 };  d.b = 2
来源：http://dali.daxiang520.top/Article/details/gtqvxwoifi.html

[T36] Lua：函数
来源：http://dali.jinqigfzy.top/Article/details/gtfnhmvnki.html

function add(a, b) return a + b end
来源：http://dali.hfpthk.cn/Article/details/gtfgygqsvu.html

[T37] Lua：字符串拼接
来源：http://dali.zhongyouzk.top/Article/details/gtehbfvlmb.html

"a" .. "b"
来源：http://dali.ppjwa.cn/Article/details/gtybvvrnle.html

[T38] Lua：条件
来源：http://dali.hysaishi.cn/Article/details/gtshwmpdpe.html

if x > 0 then print("正") end
来源：http://dali.dashuyun.cn/Article/details/gtyftqvkbj.html

[T39] Lua：模式匹配
来源：http://dali.haohaochexian.top/Article/details/gtzeflznri.html

string.find(s, "%d+")
来源：http://dali.yongpay.top/Article/details/gtbjyeozkd.html

[T40] Lua：元表
来源：http://dali.hnqzz.top/Article/details/gtsszzcwlc.html

setmetatable({}, { __index = base })
来源：http://dali.hfpthk.cn/Article/details/gthkspwlpn.html

[T41] Perl：Hello World
来源：http://dali.gogol.net.cn/Article/details/gtkvwhdtlu.html

print "Hello\n";
来源：http://dali.bjfxy.top/Article/details/gtyjeykjaj.html

[T42] Perl：变量类型
来源：http://dali.fzhhl.top/Article/details/gtdyfjybkt.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.gogol.net.cn/Article/details/gtyedsmjma.html

[T43] Perl：字符串插值
来源：http://dali.xinyue.icu/Article/details/gtvobtbrfq.html

"值: $a"
来源：http://dali.jiagoushi.top/Article/details/gtdjpxwcnj.html

[T44] Perl：条件
来源：http://dali.chenlongwang.top/Article/details/gtdcceyyji.html

if ($a > 0) { print "正"; }
来源：http://dali.ivvv.top/Article/details/gtkcrkgzgf.html

[T45] Perl：数组遍历
来源：http://dali.zhoulong.xyz/Article/details/gtuwlpikqw.html

for my $x (@arr) { print $x; }
来源：http://dali.sweek.top/Article/details/gtlabnfgrd.html

[T46] Perl：哈希操作
来源：http://dali.smart0.xyz/Article/details/gtkwhfniit.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.cashguo.top/Article/details/gtkzccsavd.html

[T47] Perl：正则捕获
来源：http://dali.dashuyun.cn/Article/details/gtpdtsdilo.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.daria6918.cn/Article/details/gttvdvyqho.html

[T48] Perl：正则替换
来源：http://dali.dianchejie.cn/Article/details/gtyqohfjuj.html

$s =~ s/old/new/g;
来源：http://dali.tian-w.cn/Article/details/gtsucbryhx.html

[T49] Perl：函数
来源：http://dali.yonumen.top/Article/details/gtixpushrn.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.hnqzz.top/Article/details/gtumfuqdtj.html

[T50] Perl：逐行读文件
来源：http://dali.zhongyouzk.top/Article/details/gtuxypxcsb.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.mhx1999.top/Article/details/gtotivpzvo.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.aizwys.cn/Article/details/gtadqtxxki.html

[T51] Scala：Hello World
来源：http://dali.yj20258888.top/Article/details/gtfvsvrilu.html

println("Hello")
来源：http://dali.zycfv.cn/Article/details/gtpzgamtdz.html

[T52] Scala：变量
来源：http://dali.yuxming.cn/Article/details/gtpxpmcjgr.html

val a = 1;  var b = 2
来源：http://dali.tian-w.cn/Article/details/gtdfcimilw.html

[T53] Scala：字符串插值
来源：http://dali.sweek.top/Article/details/gtjjxzmnkh.html

s"值: $b"
来源：http://dali.smart0.xyz/Article/details/gtrftktfhk.html

[T54] Scala：集合映射
来源：http://dali.quarkkingdee.top/Article/details/gtuttzcxlh.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.yuanzhike.top/Article/details/gtlrglytjo.html

[T55] Scala：集合过滤
来源：http://dali.shanyushiyangtech.top/Article/details/gtamycpjjd.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.chenlongwang.top/Article/details/gtuemtlxkx.html

[T56] Scala：样例类
来源：http://dali.xylfe.cn/Article/details/gthtxbwlyf.html

case class User(name: String, age: Int)
来源：http://dali.ydzc1.top/Article/details/gtvleujncs.html

[T57] Scala：模式匹配
来源：http://dali.jqgufenzy.top/Article/details/gtbsghbqtu.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.c1oappe.top/Article/details/gtupmwpkhg.html

[T58] Scala：函数定义
来源：http://dali.jinqigufen.top/Article/details/gtoafaejcj.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.yongpay.top/Article/details/gtqyuroxcu.html

[T59] Scala：循环
来源：http://dali.fzhhl.top/Article/details/gtnysylmzc.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhiwuduotai.top/Article/details/gttxduemtf.html

[T60] Scala：折叠
来源：http://dali.hfpthk.cn/Article/details/gtrwkxynme.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.hammf.cn/Article/details/gtisikkalz.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtrihicqfn.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.daria6918.cn/Article/details/gtdnpzefij.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtionxvvuw.html

[U01] Py：创建虚拟环境
来源：http://dali.316326.xyz/Article/details/gtulrezeda.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.pycfn.com/Article/details/gtrxmukylo.html

[U02] Py：导出 / 安装依赖
来源：http://dali.xuanzx.com/Article/details/gtcqblkswn.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.yj20258888.top/Article/details/gttwrmwjaj.html


<!-- 参考信息 -->