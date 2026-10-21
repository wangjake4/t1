代发 wailian999

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.xinyue.icu/Article/details/gtxnbkwmtz.html

[R60] 只看 HTTP 状态码
来源：http://dali.chenjidiqi.icu/Article/details/gtzcekpztd.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.xziqi.cn/Article/details/gtburefnzy.html

[R61] 磁盘占用
来源：http://dali.c1oappe.top/Article/details/gteqswhuyn.html

df -h;  du -sh *
来源：http://dali.hywenlv.cn/Article/details/gtievvyyli.html

[R62] 找最占空间的文件
来源：http://dali.zhengqikj.top/Article/details/gtsyveclsf.html

du -ah . | sort -rh | head -10
来源：http://dali.daria6918.cn/Article/details/gthzazigct.html

[R63] 内存与进程
来源：http://dali.xuetiantiany.cn/Article/details/gtsappfond.html

free -h;  ps aux | grep nginx
来源：http://dali.dianchejie.cn/Article/details/gtpbhannig.html

[R64] 结束进程
来源：http://dali.fengsongda.top/Article/details/gtfqgferrw.html

kill -9 $(pgrep -f app.py)
来源：http://dali.cqqwz.cn/Article/details/gtsfphwcvn.html

[R65] 查看端口占用
来源：http://dali.sufxvd.cn/Article/details/gtphhepvcs.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.wangdashe.top/Article/details/gtbybzkmib.html

[R66] 定时任务
来源：http://dali.zdqjudy.top/Article/details/gtnlxpgxyi.html

crontab -e;  crontab -l
来源：http://dali.zhengqikj.top/Article/details/gtqsjosugu.html

[R67] 生成随机十六进制串
来源：http://dali.jianghu66.top/Article/details/gtaxrnldiv.html

openssl rand -hex 16
来源：http://dali.snrcjt.cn/Article/details/gtjlegzvcu.html

[R68] 计算文件校验值
来源：http://dali.gogol.net.cn/Article/details/gtlakayfom.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.316326.xyz/Article/details/gtmtyeiqxb.html

[R69] 生成随机密码
来源：http://dali.shuidangran.top/Article/details/gtbrthxjvv.html

head -c 16 /dev/urandom | base64
来源：http://dali.sweek.top/Article/details/gtqqpuigjn.html

[R70] 时间戳与互转
来源：http://dali.9152youxi.cn/Article/details/gtzqbzfnji.html

date +%s;  date -d @1700000000
来源：http://dali.chenlongwang.top/Article/details/gtfuvvaowx.html

[R71] 日期格式化
来源：http://dali.tanke756.top/Article/details/gtmvuthwhg.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.shangyingyoupin.top/Article/details/gtltlpxvnw.html

[R72] 等待端口就绪
来源：http://dali.yvedp.cn/Article/details/gtheyorutq.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcgqhkyok.html

[R73] 分割大日志
来源：http://dali.c1oappe.top/Article/details/gtidwrddlt.html

split -l 1000 big.log part_
来源：http://dali.jiagoushi.top/Article/details/gtrtudqxwg.html

[R74] 批量重命名
来源：http://dali.chenjidiqi.icu/Article/details/gtspnprokv.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zdqjudy.top/Article/details/gtigoypzjv.html

[R75] 导出环境变量
来源：http://dali.havefunace.top/Article/details/gtcxywfudk.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.ybcxt.top/Article/details/gtpscfglmz.html

[R76] 使用临时文件
来源：http://dali.iojbl.cn/Article/details/gtdrvdqcwk.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.jqgufenzy.top/Article/details/gteqaljrvv.html

[R77] 读取用户输入
来源：http://dali.sysykeji.top/Article/details/gtqjopisdv.html

read -rp "请输入: " ans
来源：http://dali.pycfn.com/Article/details/gtlkacupfv.html

[R78] 交互式菜单
来源：http://dali.shuidangran.top/Article/details/gtjhzxrxgp.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.smart0.xyz/Article/details/gtlyqraxhb.html

[R79] 解析命令行选项
来源：http://dali.chenlongwang.top/Article/details/gtlcohtltu.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.c1oappe.top/Article/details/gtpuwjynah.html

[R80] 查看脚本执行耗时
来源：http://dali.birdmap.top/Article/details/gtrqtfopen.html

time ./run.sh
来源：http://dali.zhaomingkeji.xyz/Article/details/gtceoqhgve.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gttdaniori.html

S. C / C++ 专题
来源：http://dali.guowangkeji.top/Article/details/gtzhdyyezk.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtlgvlsyvi.html

[S01] C：Hello World
来源：http://dali.shzxlz.cn/Article/details/gtsgbfalwg.html

#include <stdio.h>
来源：http://dali.yangfankeji.com/Article/details/gtksaljvww.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.hongshengwenyu.top/Article/details/gtsmvygkjp.html

[S02] C：变量与格式化输出
来源：http://dali.quarkkingdee.top/Article/details/gtnovdfaqi.html

int a = 10; printf("%d\n", a);
来源：http://dali.daria6918.cn/Article/details/gtbydyssvm.html

[S03] C：读入整数
来源：http://dali.cheryme.top/Article/details/gtdjvyyfod.html

int x; scanf("%d", &x);
来源：http://dali.hammf.cn/Article/details/gtubiuifyi.html

[S04] C：字符串复制
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqfcgyzjk.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.316326.xyz/Article/details/gtigaoettc.html

[S05] C：字符串长度
来源：http://dali.fzhhl.top/Article/details/gtwzitcuzw.html

strlen(s)
来源：http://dali.quarkkingdee.top/Article/details/gtqycncfle.html

[S06] C：字符串比较
来源：http://dali.chenzaomai.com/Article/details/gtmobwsjup.html

strcmp(a, b) == 0
来源：http://dali.smart0.xyz/Article/details/gtpzxqnrhz.html

[S07] C：数组遍历求和
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnxheteag.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.chenjidiqi.icu/Article/details/gtkqagrtnr.html

[S08] C：动态内存分配与释放
来源：http://dali.hnxiangtu.top/Article/details/gtwhrdbpcu.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.shanyushiyangtech.top/Article/details/gtsefbrokn.html

[S09] C：结构体定义与初始化
来源：http://dali.fzhhl.top/Article/details/gttuzhlobp.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.yuxming.cn/Article/details/gtovcclydk.html

[S10] C：指针与解引用
来源：http://dali.hysaishi.cn/Article/details/gtyiuubbov.html

int *p = &a;  *p = 5;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxrxkcjij.html

[S11] C：逐行读文件
来源：http://dali.zycfv.cn/Article/details/gtcsswkflj.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.ehwqpu.com/Article/details/gtcqmzhmiz.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.yangfankeji.com/Article/details/gtwtsigcfp.html

fclose(f);
来源：http://dali.shanyushiyangtech.top/Article/details/gtculmgbzx.html

[S12] C：写文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpezvetjz.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.cashguo.top/Article/details/gtvgimknyp.html

[S13] C：宏定义
来源：http://dali.xziqi.cn/Article/details/gttonmbawz.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.xuanzx.com/Article/details/gtumvgnlgn.html

[S14] C：枚举
来源：http://dali.fzhhl.top/Article/details/gtqwdyvrnf.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.cqqwz.cn/Article/details/gtdphvhmpt.html

[S15] C：类型转换
来源：http://dali.ydzc1.top/Article/details/gttyabdqlx.html

(double) a / b
来源：http://dali.cheryme.top/Article/details/gttykmuzhe.html

[S16] C：位操作置位
来源：http://dali.fzhhl.top/Article/details/gtkstrzvoh.html

x |= (1 << 3);
来源：http://dali.shangyingyoupin.top/Article/details/gtvhkirzpt.html

[S17] C：安全拼接字符串
来源：http://dali.jiagoushi.top/Article/details/gtzieqmprt.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.birdmap.top/Article/details/gtojmjoxxr.html

[S18] C：命令行参数
来源：http://dali.cdnleiting.top/Article/details/gtpbdagmtp.html

int main(int argc, char **argv)
来源：http://dali.nanxinkj.top/Article/details/gtizmrvyap.html

[S19] C：快速排序
来源：http://dali.c1oappe.top/Article/details/gtjmjthnrk.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gtcmtgsvcu.html

[S20] C：二分查找
来源：http://dali.dashuyun.cn/Article/details/gtsdpindrd.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.fzhhl.top/Article/details/gtzexqwwuf.html

[S21] C：字符类别判断
来源：http://dali.yj20258888.top/Article/details/gtgycbxhiq.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.jinqigfzy.top/Article/details/gtkfitflii.html

[S22] C：字符串转数字
来源：http://dali.chenzaomai.com/Article/details/gtqbrmcbcd.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.xziqi.cn/Article/details/gtdodmxuqe.html

[S23] C：随机数
来源：http://dali.gaohongyu789.top/Article/details/gtqttwescm.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.ppjwa.cn/Article/details/gthweegbai.html

[S24] C：获取本地时间
来源：http://dali.chenzaomai.com/Article/details/gtwsritnhu.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.jianghu66.top/Article/details/gtgpjvfchm.html

[S25] C：内存拷贝
来源：http://dali.havefunace.top/Article/details/gtoqvfmgtf.html

memcpy(dst, src, n);
来源：http://dali.ppjwa.cn/Article/details/gtgljwisrh.html

[S26] C：内存清零
来源：http://dali.jqgufenzy.top/Article/details/gtnpprfpmh.html

memset(a, 0, sizeof a);
来源：http://dali.jlsjyb.cn/Article/details/gticfavfpz.html

[S27] C：定义常量
来源：http://dali.zhongyouzk.top/Article/details/gtazwmpdkn.html

const double PI = 3.14159;
来源：http://dali.yuxming.cn/Article/details/gtiserknfp.html

[S28] C：静态变量
来源：http://dali.cqqwz.cn/Article/details/gtecwphrsk.html

static int counter = 0;
来源：http://dali.jyoumei.cn/Article/details/gtcxdmzbee.html

[S29] C：变参函数
来源：http://dali.xziqi.cn/Article/details/gtfxfmgnla.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.cdnleiting.top/Article/details/gtweuokclr.html

[S30] C：头文件保护
来源：http://dali.feifeiyinyue.top/Article/details/gtnfaqzrwf.html

#ifndef X_H
来源：http://dali.feifeiyinyue.top/Article/details/gtpknexrdm.html

#define X_H
来源：http://dali.pycfn.com/Article/details/gtnkomoekq.html

#endif
来源：http://dali.jinqigufen.top/Article/details/gtfhfuqvmj.html

[S31] C++：Hello World
来源：http://dali.0kj1m.cn/Article/details/gtbjtzqtgy.html

#include <iostream>
来源：http://dali.sxryk.cn/Article/details/gtlxvrryir.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.xinyue.icu/Article/details/gtibocerfu.html

[S32] C++：字符串
来源：http://dali.ivvv.top/Article/details/gtlwlbczhc.html

std::string s = "hi";  s += "!";
来源：http://dali.aizwys.cn/Article/details/gtcnfxqozp.html

[S33] C++：vector 增删
来源：http://dali.nwbrower.top/Article/details/gtgyxlgcal.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.sxryk.cn/Article/details/gtuxyefrkb.html

[S34] C++：遍历 vector
来源：http://dali.yuxming.cn/Article/details/gtxnatjmfq.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.sweek.top/Article/details/gtinewpiek.html

[S35] C++：map
来源：http://dali.sxryk.cn/Article/details/gtchpuhnbp.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.xuanzx.com/Article/details/gtyweidfyq.html

[S36] C++：unordered_map
来源：http://dali.jinghuilouyu.cn/Article/details/gtmkhfvwuz.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.cashguo.top/Article/details/gtvfzqabir.html

[S37] C++：set
来源：http://dali.zhaomingkeji.xyz/Article/details/gtohppozzj.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.yuanzhike.top/Article/details/gtygxjtuhs.html

[S38] C++：排序
来源：http://dali.havefunace.top/Article/details/gtmgqvembz.html

std::sort(v.begin(), v.end());
来源：http://dali.meibo888.top/Article/details/gtqtmtjzdu.html

[S39] C++：自定义比较器排序
来源：http://dali.hongshengwenyu.top/Article/details/gtroglzaxy.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.jqgufenzy.top/Article/details/gtvmekhyny.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gtejiymywy.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.yuxming.cn/Article/details/gtfskqekox.html

[S41] C++：类与构造函数
来源：http://dali.fzhhl.top/Article/details/gtovwpavxw.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhaomingkeji.xyz/Article/details/gtppkiukdt.html

[S42] C++：继承与虚函数
来源：http://dali.shangyingyoupin.top/Article/details/gtzpigixif.html

class B : public Base { public: void f() override {} };
来源：http://dali.hammf.cn/Article/details/gtkmgebjoz.html

[S43] C++：智能指针
来源：http://dali.ydzc1.top/Article/details/gtejtwjjjj.html

auto p = std::make_unique<int>(5);
来源：http://dali.guowangkeji.top/Article/details/gtjhspdgxp.html

[S44] C++：引用传参
来源：http://dali.yuanzhike.top/Article/details/gtckbbigyj.html

void inc(int &x) { ++x; }
来源：http://dali.chenzaomai.com/Article/details/gtkojgxtbf.html

[S45] C++：lambda
来源：http://dali.wangdashe.top/Article/details/gthogwyveq.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.iojbl.cn/Article/details/gtdicchkaf.html

[S46] C++：函数模板
来源：http://dali.zhoulong.xyz/Article/details/gtivuzxiib.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtnqtlhfim.html

[S47] C++：结构化绑定遍历
来源：http://dali.fzhhl.top/Article/details/gtcbwhdrus.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.cdnleiting.top/Article/details/gtoxjmqshc.html

[S48] C++：逐行读文件
来源：http://dali.hnxiangtu.top/Article/details/gtytacysff.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.pengpengdd.cyou/Article/details/gtbcmqqquj.html

while (std::getline(in, line)) { }
来源：http://dali.tian-w.cn/Article/details/gtpflrdxca.html

[S49] C++：写文件
来源：http://dali.chenjidiqi.icu/Article/details/gtxdwjvtbn.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.bjfxy.top/Article/details/gttsatfupm.html

[S50] C++：格式化数字
来源：http://dali.kuanghao11.cn/Article/details/gtzzxbftwm.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.kuanghao11.cn/Article/details/gtfzacamuc.html

[S51] C++：显式类型转换
来源：http://dali.yuxming.cn/Article/details/gtoehleone.html

static_cast<double>(a) / b
来源：http://dali.wangdashe.top/Article/details/gtvkqcqfiw.html

[S52] C++：const 与 noexcept
来源：http://dali.yanxiufei.cn/Article/details/gtopfvmpwt.html

int size() const noexcept { return n_; }
来源：http://dali.wangshuangyany.cn/Article/details/gtmzwzmjqx.html

[S53] C++：移动语义
来源：http://dali.jiagoushi.top/Article/details/gtiogdfgdi.html

std::vector<int> w = std::move(v);
来源：http://dali.sysykeji.top/Article/details/gtrmbcotej.html

[S54] C++：异常处理
来源：http://dali.redwolf501.top/Article/details/gtttaftdjs.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.cucudq.cn/Article/details/gtnmjhibws.html

[S55] C++：结构化绑定
来源：http://dali.yj202588.top/Article/details/gtpoqcnbht.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.jianghu66.top/Article/details/gtedqanoym.html

[S56] C++：optional
来源：http://dali.jlsjyb.cn/Article/details/gtqvihtgoo.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.xuanzx.com/Article/details/gttwxxuqrj.html

[S57] C++：编译期常量
来源：http://dali.jyoumei.cn/Article/details/gthodfymts.html

constexpr int N = 10;
来源：http://dali.zycfv.cn/Article/details/gtqvcijlpx.html

[S58] C++：命名空间
来源：http://dali.nanxuanxn.top/Article/details/gtehmdtxjs.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhengqikj.top/Article/details/gteipuplau.html

[S59] C++：静态断言
来源：http://dali.zhixingplan.top/Article/details/gtqxvwkhlb.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.wangshuangyany.cn/Article/details/gtthyhtmse.html

[S60] C++：遍历并删除元素
来源：http://dali.ppjwa.cn/Article/details/gtnlejlfya.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.meibo888.top/Article/details/gtsgqomczt.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtfenhpcyl.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.9152youxi.cn/Article/details/gtcvqtdugx.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtshugrunu.html

[T01] Kotlin：Hello World
来源：http://dali.yongpay.top/Article/details/gtarkmhlaf.html

println("Hello")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdncvghnj.html

[T02] Kotlin：变量
来源：http://dali.yueranfly.top/Article/details/gtkkotyfzz.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.sysykeji.top/Article/details/gtsoehpgmj.html

[T03] Kotlin：字符串模板
来源：http://dali.sxryk.cn/Article/details/gtilomsscw.html

"值: $b"
来源：http://dali.gzhubu.top/Article/details/gtegzwhyfk.html

[T04] Kotlin：空安全
来源：http://dali.yvedp.cn/Article/details/gtywokwhwj.html

val n: String? = null;  n?.length
来源：http://dali.jiagoushi.top/Article/details/gtvrsgzeik.html

[T05] Kotlin：when 表达式
来源：http://dali.hysaishi.cn/Article/details/gtdledokdw.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.xuetiantiany.cn/Article/details/gtbhzksuko.html

[T06] Kotlin：集合映射
来源：http://dali.jinghuilouyu.cn/Article/details/gtxinjgdzp.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.yueranfly.top/Article/details/gtrqmtdxye.html

[T07] Kotlin：集合过滤
来源：http://dali.hnxiangtu.top/Article/details/gttxthircr.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.meibo888.top/Article/details/gttmptfwwn.html

[T08] Kotlin：数据类
来源：http://dali.yj20258888.top/Article/details/gtjhvxqfoi.html

data class User(val name: String, val age: Int)
来源：http://dali.daria6918.cn/Article/details/gtxrdkaadh.html

[T09] Kotlin：扩展函数
来源：http://dali.yonumen.top/Article/details/gtbxgqhbza.html

fun String.exclaim() = this + "!"
来源：http://dali.sufxvd.cn/Article/details/gtpeatxhef.html

[T10] Kotlin：默认参数
来源：http://dali.xinyue.icu/Article/details/gtkwolutvp.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.ehwqpu.com/Article/details/gtvqpxieiz.html

[T11] Kotlin：协程
来源：http://dali.ivvv.top/Article/details/gtjhhwqkgf.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.yj20258888.top/Article/details/gtwytcttdc.html

[T12] Kotlin：解构声明
来源：http://dali.hnxiangtu.top/Article/details/gttlwzdlxp.html

val (a, b) = Pair(1, 2)
来源：http://dali.aibaodan.cn/Article/details/gtsmcpbjgp.html

[T13] Kotlin：只读 Map
来源：http://dali.yuanzhike.top/Article/details/gtbpyrmysb.html

val m = mapOf("a" to 1)
来源：http://dali.zycfv.cn/Article/details/gtmzduymgy.html

[T14] Kotlin：循环
来源：http://dali.xuetiantiany.cn/Article/details/gtnmhxseay.html

for (i in 1..10) println(i)
来源：http://dali.gzhubu.top/Article/details/gtcgluyesp.html

[T15] Kotlin：接口
来源：http://dali.tianlin.xyz/Article/details/gtqjewyjgx.html

interface Shape { fun area(): Double }
来源：http://dali.hongshengwenyu.top/Article/details/gtbvdphgfh.html

[T16] Swift：Hello World
来源：http://dali.yongpay.top/Article/details/gtknyhmodc.html

print("Hello")
来源：http://dali.yongpay.top/Article/details/gtqiqzvdpx.html

[T17] Swift：变量与常量
来源：http://dali.cdnleiting.top/Article/details/gttpwnudcx.html

var a = 1;  let b = 2
来源：http://dali.xuetiantiany.cn/Article/details/gtaixttsmq.html

[T18] Swift：字符串插值
来源：http://dali.hammf.cn/Article/details/gtqrmqsuaw.html

"值: \(b)"
来源：http://dali.tianlin.xyz/Article/details/gtupajjxlj.html

[T19] Swift：可选绑定
来源：http://dali.gotoacloud.top/Article/details/gtuxxymjhr.html

if let n = opt { print(n) }
来源：http://dali.gaohongyu789.top/Article/details/gtdlrppmqq.html

[T20] Swift：数组操作
来源：http://dali.tianlin.xyz/Article/details/gtssheghhy.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.jlsjyb.cn/Article/details/gtfrsgghbf.html

[T21] Swift：遍历
来源：http://dali.cheryme.top/Article/details/gtyynpraqk.html

for x in a { print(x) }
来源：http://dali.haohaochexian.top/Article/details/gtsuodmjts.html

[T22] Swift：字典
来源：http://dali.cheryme.top/Article/details/gtmtwhoadr.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.meibo888.top/Article/details/gtmngsseyb.html

[T23] Swift：函数
来源：http://dali.hysaishi.cn/Article/details/gtmjmwwaip.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhixingplan.top/Article/details/gtgnnhtqhu.html

[T24] Swift：闭包
来源：http://dali.vqdsnc.cn/Article/details/gtnbbnrqhn.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.iojbl.cn/Article/details/gtniuhzbgh.html

[T25] Swift：结构体
来源：http://dali.ydzc1.top/Article/details/gtyuscsfke.html

struct P { var x: Int }
来源：http://dali.ivvv.top/Article/details/gtjwuxirmr.html

[T26] Swift：类与重写
来源：http://dali.hywenlv.cn/Article/details/gtswpbfecy.html

class A: Base { override func f() {} }
来源：http://dali.kuanghao11.cn/Article/details/gtqwnhigfp.html

[T27] Swift：错误处理
来源：http://dali.xuanzx.com/Article/details/gttmtqtvpx.html

do { try f() } catch { print(error) }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjchyimco.html

[T28] Swift：枚举
来源：http://dali.ivvv.top/Article/details/gtpsznyzme.html

enum Color { case red, green }
来源：http://dali.pycfn.com/Article/details/gtejqjejqp.html

[T29] Swift：guard 提前返回
来源：http://dali.wangshuangyany.cn/Article/details/gtezyewxwp.html

guard let x = opt else { return }
来源：http://dali.pengpengdd.cyou/Article/details/gttycojhav.html

[T30] Swift：协议
来源：http://dali.havefunace.top/Article/details/gtbkgaataw.html

protocol Shape { func area() -> Double }
来源：http://dali.yanxiufei.cn/Article/details/gtpnrjjuec.html

[T31] Lua：Hello World
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrzijnvgl.html

print("Hello")
来源：http://dali.ybcxt.top/Article/details/gtvodyuipc.html

[T32] Lua：局部变量
来源：http://dali.cqqwz.cn/Article/details/gtwvhhhhiv.html

local a = 1
来源：http://dali.cqqwz.cn/Article/details/gtuvlycyht.html

[T33] Lua：表（数组）
来源：http://dali.yuanzhike.top/Article/details/gtdslkxhgx.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.nwbrower.top/Article/details/gtqbqbwrxi.html

[T34] Lua：遍历表
来源：http://dali.feifeiyinyue.top/Article/details/gtuznxnagx.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.ivvv.top/Article/details/gtbpkccdge.html

[T35] Lua：字典表
来源：http://dali.hammf.cn/Article/details/gtfanffmcs.html

local d = { a = 1 };  d.b = 2
来源：http://dali.jqgfzy.top/Article/details/gtlcxfwexj.html

[T36] Lua：函数
来源：http://dali.yj20258.top/Article/details/gtcxwwznyn.html

function add(a, b) return a + b end
来源：http://dali.shzxlz.cn/Article/details/gtgwrzrkdw.html

[T37] Lua：字符串拼接
来源：http://dali.iojbl.cn/Article/details/gtiolnnquk.html

"a" .. "b"
来源：http://dali.316326.xyz/Article/details/gtrpyvxaoo.html

[T38] Lua：条件
来源：http://dali.fengsongda.top/Article/details/gtkbllitde.html

if x > 0 then print("正") end
来源：http://dali.sufxvd.cn/Article/details/gtaegqglkf.html

[T39] Lua：模式匹配
来源：http://dali.wangshuangyany.cn/Article/details/gtbwyfrlpp.html

string.find(s, "%d+")
来源：http://dali.hongshengwenyu.top/Article/details/gtwfsnkcqb.html

[T40] Lua：元表
来源：http://dali.meibo888.top/Article/details/gtuwbqakpi.html

setmetatable({}, { __index = base })
来源：http://dali.pycfn.com/Article/details/gtnywcinao.html

[T41] Perl：Hello World
来源：http://dali.zhixingplan.top/Article/details/gttqtcuygl.html

print "Hello\n";
来源：http://dali.jqgfzy.top/Article/details/gtwijbelji.html

[T42] Perl：变量类型
来源：http://dali.feifeiyinyue.top/Article/details/gtlgaavpkl.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.nanxuanxn.top/Article/details/gtkpcyeqsj.html

[T43] Perl：字符串插值
来源：http://dali.daria6918.cn/Article/details/gtsiuyokfm.html

"值: $a"
来源：http://dali.andypj.xyz/Article/details/gtqqftiwuv.html

[T44] Perl：条件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgpooqhpp.html

if ($a > 0) { print "正"; }
来源：http://dali.zhiwuduotai.top/Article/details/gtugqbiqjq.html

[T45] Perl：数组遍历
来源：http://dali.jlsjyb.cn/Article/details/gtzzadokta.html

for my $x (@arr) { print $x; }
来源：http://dali.gotoacloud.top/Article/details/gtizfdojuz.html

[T46] Perl：哈希操作
来源：http://dali.havefunace.top/Article/details/gtcuitffaa.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.nanxinkj.top/Article/details/gtpnkgpmcl.html

[T47] Perl：正则捕获
来源：http://dali.gaohongyu789.top/Article/details/gthghvekdc.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.tianlin.xyz/Article/details/gtrywsakae.html

[T48] Perl：正则替换
来源：http://dali.sweek.top/Article/details/gtumfftdxi.html

$s =~ s/old/new/g;
来源：http://dali.cashguo.top/Article/details/gtfmpbmhsu.html

[T49] Perl：函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwrncbbnj.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.kuanghao11.cn/Article/details/gtpydrhuou.html

[T50] Perl：逐行读文件
来源：http://dali.yvedp.cn/Article/details/gtnvwtgkye.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.gaohongyu789.top/Article/details/gtsihimclj.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.ppjwa.cn/Article/details/gtygutwjbi.html

[T51] Scala：Hello World
来源：http://dali.tanke756.top/Article/details/gtehjsmjyp.html

println("Hello")
来源：http://dali.xziqi.cn/Article/details/gtmnyewurz.html

[T52] Scala：变量
来源：http://dali.xuanzx.com/Article/details/gtibbcasyd.html

val a = 1;  var b = 2
来源：http://dali.guowangkeji.top/Article/details/gtwtpamiom.html

[T53] Scala：字符串插值
来源：http://dali.sweek.top/Article/details/gtvkpgfjpg.html

s"值: $b"
来源：http://dali.daria6918.cn/Article/details/gtmxpucfwz.html

[T54] Scala：集合映射
来源：http://dali.yueranfly.top/Article/details/gtoujvxxxc.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.jyoumei.cn/Article/details/gtfoecjjtb.html

[T55] Scala：集合过滤
来源：http://dali.zhixingplan.top/Article/details/gtgvhoqivl.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.jyoumei.cn/Article/details/gtizqvqtav.html

[T56] Scala：样例类
来源：http://dali.ehwqpu.com/Article/details/gtdncozblw.html

case class User(name: String, age: Int)
来源：http://dali.xziqi.cn/Article/details/gtzogufqth.html

[T57] Scala：模式匹配
来源：http://dali.cheryme.top/Article/details/gtptqpcbgt.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.ehwqpu.com/Article/details/gtunpecyya.html

[T58] Scala：函数定义
来源：http://dali.daria6918.cn/Article/details/gtwmbshrwp.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.smart0.xyz/Article/details/gtgwqldvdu.html

[T59] Scala：循环
来源：http://dali.yuxming.cn/Article/details/gtapjuigil.html

for (i <- 1 to 10) println(i)
来源：http://dali.c1oappe.top/Article/details/gtyksepafb.html

[T60] Scala：折叠
来源：http://dali.gzhubu.top/Article/details/gtjmfxdvag.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.yuanzhike.top/Article/details/gtvqxnadzb.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtflkfbbhd.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.snrcjt.cn/Article/details/gtylzouibj.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtjszyjrvq.html


<!-- 参考信息 -->