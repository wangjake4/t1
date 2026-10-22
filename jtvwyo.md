代发 wailian999

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.hammf.cn/Article/details/gtmcffjfuv.html

[R66] 定时任务
来源：http://dali.jqgufenzy.top/Article/details/gttueorqpd.html

crontab -e;  crontab -l
来源：http://dali.hysaishi.cn/Article/details/gtpbpipajf.html

[R67] 生成随机十六进制串
来源：http://dali.gotoacloud.top/Article/details/gtvdshvflb.html

openssl rand -hex 16
来源：http://dali.ppjwa.cn/Article/details/gtwdvdrgyx.html

[R68] 计算文件校验值
来源：http://dali.jianghu66.top/Article/details/gtgrrerfgg.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.hfpthk.cn/Article/details/gtpaatlqhz.html

[R69] 生成随机密码
来源：http://dali.aibaodan.cn/Article/details/gtsptbpnkg.html

head -c 16 /dev/urandom | base64
来源：http://dali.sufxvd.cn/Article/details/gtsfrndjab.html

[R70] 时间戳与互转
来源：http://dali.xylfe.cn/Article/details/gtikzgzvro.html

date +%s;  date -d @1700000000
来源：http://dali.aizwys.cn/Article/details/gtbcueoril.html

[R71] 日期格式化
来源：http://dali.cheryme.top/Article/details/gtyrzplevl.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.chenjidiqi.icu/Article/details/gtbhkqxtod.html

[R72] 等待端口就绪
来源：http://dali.ivvv.top/Article/details/gtnsebimkt.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.guannengcc.top/Article/details/gtciiwoalt.html

[R73] 分割大日志
来源：http://dali.hammf.cn/Article/details/gtlckzcebw.html

split -l 1000 big.log part_
来源：http://dali.ydzc1.top/Article/details/gtcnofstve.html

[R74] 批量重命名
来源：http://dali.tianlin.xyz/Article/details/gtxzrkshvg.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.jinghuilouyu.cn/Article/details/gtnjumzmtk.html

[R75] 导出环境变量
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttjmalcda.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtezpbvhlf.html

[R76] 使用临时文件
来源：http://dali.nwbrower.top/Article/details/gtkbdfjvua.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.svipenyu.cn/Article/details/gtuhnjcpft.html

[R77] 读取用户输入
来源：http://dali.jqgfzy.top/Article/details/gtemnbnalm.html

read -rp "请输入: " ans
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvltftfum.html

[R78] 交互式菜单
来源：http://dali.vqdsnc.cn/Article/details/gtruwobxzv.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.aibaodan.cn/Article/details/gthqhfvwwe.html

[R79] 解析命令行选项
来源：http://dali.shzxlz.cn/Article/details/gtzxrerhwj.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.vqdsnc.cn/Article/details/gtdugkxdft.html

[R80] 查看脚本执行耗时
来源：http://dali.andypj.xyz/Article/details/gtgchqjqxt.html

time ./run.sh
来源：http://dali.jyoumei.cn/Article/details/gtfvzykpba.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtfxssvkhx.html

S. C / C++ 专题
来源：http://dali.hnxiangtu.top/Article/details/gtjatmvoht.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gthbofbvpb.html

[S01] C：Hello World
来源：http://dali.iojbl.cn/Article/details/gtramhntsu.html

#include <stdio.h>
来源：http://dali.c1oappe.top/Article/details/gtktkcnpip.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.cheryme.top/Article/details/gtxxsdknqz.html

[S02] C：变量与格式化输出
来源：http://dali.ppjwa.cn/Article/details/gtahrulypp.html

int a = 10; printf("%d\n", a);
来源：http://dali.fzhhl.top/Article/details/gtosfmcsyu.html

[S03] C：读入整数
来源：http://dali.cashguo.top/Article/details/gtkfozgwnu.html

int x; scanf("%d", &x);
来源：http://dali.fengsongda.top/Article/details/gtvylkpafj.html

[S04] C：字符串复制
来源：http://dali.bjfxy.top/Article/details/gtcjavftok.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.daria6918.cn/Article/details/gtjrxerixi.html

[S05] C：字符串长度
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvsqchqvh.html

strlen(s)
来源：http://dali.yanxiufei.cn/Article/details/gtlidymeli.html

[S06] C：字符串比较
来源：http://dali.kuanghao11.cn/Article/details/gtzartmpdi.html

strcmp(a, b) == 0
来源：http://dali.jinqigufen.top/Article/details/gttvmvuhxm.html

[S07] C：数组遍历求和
来源：http://dali.wangdashe.top/Article/details/gtwameezmi.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.hfpthk.cn/Article/details/gtuzdmvwrb.html

[S08] C：动态内存分配与释放
来源：http://dali.daxiang520.top/Article/details/gtaybtlnmq.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbygrpzij.html

[S09] C：结构体定义与初始化
来源：http://dali.kuanghao11.cn/Article/details/gtxptavdij.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.9152youxi.cn/Article/details/gtnkitgneo.html

[S10] C：指针与解引用
来源：http://dali.hnqzz.top/Article/details/gtffwirwcx.html

int *p = &a;  *p = 5;
来源：http://dali.316326.xyz/Article/details/gtawrimzpg.html

[S11] C：逐行读文件
来源：http://dali.daxiang520.top/Article/details/gtzjjmzbxl.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.yangfankeji.com/Article/details/gticpdffsk.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.shanyushiyangkeji.top/Article/details/gthwlstzxg.html

fclose(f);
来源：http://dali.feifeiyinyue.top/Article/details/gtlewqvodt.html

[S12] C：写文件
来源：http://dali.hnqzz.top/Article/details/gtdzxikfsl.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.hfpthk.cn/Article/details/gtrabvenjj.html

[S13] C：宏定义
来源：http://dali.xuanzx.com/Article/details/gtzkxiwety.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.sufxvd.cn/Article/details/gtiwhczchw.html

[S14] C：枚举
来源：http://dali.jyoumei.cn/Article/details/gtjkousxgz.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.yj20258888.top/Article/details/gtnuwinxvu.html

[S15] C：类型转换
来源：http://dali.fzhhl.top/Article/details/gtropjreae.html

(double) a / b
来源：http://dali.xylfe.cn/Article/details/gtbjljzjgy.html

[S16] C：位操作置位
来源：http://dali.sweek.top/Article/details/gtlairbrpu.html

x |= (1 << 3);
来源：http://dali.chenzaomai.com/Article/details/gtbixtniku.html

[S17] C：安全拼接字符串
来源：http://dali.yj20258.top/Article/details/gtyfngocwz.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.jqgufenzy.top/Article/details/gtkjssdqgg.html

[S18] C：命令行参数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdgonkcab.html

int main(int argc, char **argv)
来源：http://dali.wangshuangyany.cn/Article/details/gtyjxrzuwa.html

[S19] C：快速排序
来源：http://dali.sufxvd.cn/Article/details/gtcsxgvzll.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.sweek.top/Article/details/gtxcxmjikv.html

[S20] C：二分查找
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgemimcuy.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.cucudq.cn/Article/details/gtoaftzwwr.html

[S21] C：字符类别判断
来源：http://dali.shuidangran.top/Article/details/gtbfikwewg.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.yuanzhike.top/Article/details/gtlbfhoyjz.html

[S22] C：字符串转数字
来源：http://dali.pycfn.com/Article/details/gtrhbougcx.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkepictmy.html

[S23] C：随机数
来源：http://dali.andypj.xyz/Article/details/gtbkpzivfv.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.ppjwa.cn/Article/details/gtsksampju.html

[S24] C：获取本地时间
来源：http://dali.cashguo.top/Article/details/gtaonnjtlb.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.nanxuanxn.top/Article/details/gtprycjhvs.html

[S25] C：内存拷贝
来源：http://dali.yuxming.cn/Article/details/gtdxrlabdk.html

memcpy(dst, src, n);
来源：http://dali.zhongyouzk.top/Article/details/gtnvgmutbr.html

[S26] C：内存清零
来源：http://dali.tianlin.xyz/Article/details/gthltulhne.html

memset(a, 0, sizeof a);
来源：http://dali.zhixingplan.top/Article/details/gtjnuodiee.html

[S27] C：定义常量
来源：http://dali.nwbrower.top/Article/details/gtvwdwezyi.html

const double PI = 3.14159;
来源：http://dali.dashuyun.cn/Article/details/gtgqrnnlil.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gtsbueufjt.html

static int counter = 0;
来源：http://dali.tanke756.top/Article/details/gtesjqdcvz.html

[S29] C：变参函数
来源：http://dali.aibaodan.cn/Article/details/gttojzjefq.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.yj20258.top/Article/details/gtzcsfopme.html

[S30] C：头文件保护
来源：http://dali.9152youxi.cn/Article/details/gtsgsvqros.html

#ifndef X_H
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbefctghw.html

#define X_H
来源：http://dali.daria6918.cn/Article/details/gtchvakbdo.html

#endif
来源：http://dali.bjfxy.top/Article/details/gtyzupikhk.html

[S31] C++：Hello World
来源：http://dali.chenlongwang.top/Article/details/gtnudjpnmm.html

#include <iostream>
来源：http://dali.cashguo.top/Article/details/gtnatlkali.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.cheryme.top/Article/details/gtdglfyfjs.html

[S32] C++：字符串
来源：http://dali.yuxming.cn/Article/details/gtdsylrjjb.html

std::string s = "hi";  s += "!";
来源：http://dali.jinyuanbaomall.cn/Article/details/gtldexjfin.html

[S33] C++：vector 增删
来源：http://dali.pengpengdd.cyou/Article/details/gtyltjkizs.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.316326.xyz/Article/details/gtxbpbtibo.html

[S34] C++：遍历 vector
来源：http://dali.ydzc1.top/Article/details/gtbvabuyhr.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gtrjoknrtb.html

[S35] C++：map
来源：http://dali.c1oappe.top/Article/details/gtqtnwjslw.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yj20258.top/Article/details/gtncijcekr.html

[S36] C++：unordered_map
来源：http://dali.jlsjyb.cn/Article/details/gtdsvrdqvd.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.316326.xyz/Article/details/gtptluyglb.html

[S37] C++：set
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmlaulcli.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.hongshengwenyu.top/Article/details/gtrigcjpzy.html

[S38] C++：排序
来源：http://dali.chenjidiqi.icu/Article/details/gtbygouqor.html

std::sort(v.begin(), v.end());
来源：http://dali.gogol.net.cn/Article/details/gtnqpalpqs.html

[S39] C++：自定义比较器排序
来源：http://dali.sxryk.cn/Article/details/gtourgwjrs.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.tanke756.top/Article/details/gtidqhgikb.html

[S40] C++：查找元素
来源：http://dali.svipenyu.cn/Article/details/gttkcedzob.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.nwbrower.top/Article/details/gtdtrppvxp.html

[S41] C++：类与构造函数
来源：http://dali.jlsjyb.cn/Article/details/gtcqtrbesa.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.yanxiufei.cn/Article/details/gtvkqpsspz.html

[S42] C++：继承与虚函数
来源：http://dali.yonumen.top/Article/details/gthfuwexmo.html

class B : public Base { public: void f() override {} };
来源：http://dali.tianlin.xyz/Article/details/gttfrqqroq.html

[S43] C++：智能指针
来源：http://dali.gzhubu.top/Article/details/gtfqkctmjs.html

auto p = std::make_unique<int>(5);
来源：http://dali.316326.xyz/Article/details/gtppljhikl.html

[S44] C++：引用传参
来源：http://dali.cucudq.cn/Article/details/gtjzdwkevj.html

void inc(int &x) { ++x; }
来源：http://dali.yanxiufei.cn/Article/details/gtjfpaahet.html

[S45] C++：lambda
来源：http://dali.aizwys.cn/Article/details/gtftckewus.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.jinghuilouyu.cn/Article/details/gtgcyxjkrv.html

[S46] C++：函数模板
来源：http://dali.hfpthk.cn/Article/details/gtccfstgid.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.yueranfly.top/Article/details/gtaquwcssi.html

[S47] C++：结构化绑定遍历
来源：http://dali.daria6918.cn/Article/details/gtuexhspaq.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.chenjidiqi.icu/Article/details/gtuesrdpji.html

[S48] C++：逐行读文件
来源：http://dali.shanyushiyangtech.top/Article/details/gtjwjhpcfo.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.xylfe.cn/Article/details/gtflnlzjxg.html

while (std::getline(in, line)) { }
来源：http://dali.jianghu66.top/Article/details/gtquvkgsmq.html

[S49] C++：写文件
来源：http://dali.chenjidiqi.icu/Article/details/gtpjcrgafn.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.yueranfly.top/Article/details/gtddynsycv.html

[S50] C++：格式化数字
来源：http://dali.jiagoushi.top/Article/details/gtcxzathma.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.jqgfzy.top/Article/details/gtlashtequ.html

[S51] C++：显式类型转换
来源：http://dali.meibo888.top/Article/details/gterhdnlsr.html

static_cast<double>(a) / b
来源：http://dali.9152youxi.cn/Article/details/gtuyhhnbec.html

[S52] C++：const 与 noexcept
来源：http://dali.yuanzhike.top/Article/details/gthpwjrxdb.html

int size() const noexcept { return n_; }
来源：http://dali.sufxvd.cn/Article/details/gtigubzmbo.html

[S53] C++：移动语义
来源：http://dali.quarkkingdee.top/Article/details/gttqyllzhw.html

std::vector<int> w = std::move(v);
来源：http://dali.jqgufenzy.top/Article/details/gtwpmjnncq.html

[S54] C++：异常处理
来源：http://dali.yj202588.top/Article/details/gtoodigzfq.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.316326.xyz/Article/details/gtlmpoitda.html

[S55] C++：结构化绑定
来源：http://dali.ivvv.top/Article/details/gtzstucwxv.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.shangyingyoupin.top/Article/details/gtnsgoipnt.html

[S56] C++：optional
来源：http://dali.chenzaomai.com/Article/details/gtnhldghxx.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.cheryme.top/Article/details/gtqlxntkfk.html

[S57] C++：编译期常量
来源：http://dali.pycfn.com/Article/details/gtwsiknxhg.html

constexpr int N = 10;
来源：http://dali.zhixingplan.top/Article/details/gtkjbmkxed.html

[S58] C++：命名空间
来源：http://dali.jyoumei.cn/Article/details/gtjnkyyvsw.html

namespace ns { int f() { return 1; } }
来源：http://dali.xinyue.icu/Article/details/gtqwgpwapa.html

[S59] C++：静态断言
来源：http://dali.yvedp.cn/Article/details/gtqldenxtn.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.shanyushiyangtech.top/Article/details/gtsqpbtezo.html

[S60] C++：遍历并删除元素
来源：http://dali.quarkkingdee.top/Article/details/gttcfidgjw.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.jinqigufen.top/Article/details/gtprhymiif.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtxidgrufe.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.smart0.xyz/Article/details/gtwbhsopst.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtpuftdhlw.html

[T01] Kotlin：Hello World
来源：http://dali.ywan-chungtsiang.top/Article/details/gtooxnmrrz.html

println("Hello")
来源：http://dali.0kj1m.cn/Article/details/gtcqlpcmkf.html

[T02] Kotlin：变量
来源：http://dali.meibo888.top/Article/details/gtawafktdx.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.aibaodan.cn/Article/details/gtofprnqwd.html

[T03] Kotlin：字符串模板
来源：http://dali.zhixingplan.top/Article/details/gtesfhzzpt.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gthhvftwks.html

[T04] Kotlin：空安全
来源：http://dali.hongshengwenyu.top/Article/details/gtiixqdzak.html

val n: String? = null;  n?.length
来源：http://dali.andypj.xyz/Article/details/gtvapryfhk.html

[T05] Kotlin：when 表达式
来源：http://dali.sufxvd.cn/Article/details/gtqscqdnao.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.guannengcc.top/Article/details/gtmdmlpzcl.html

[T06] Kotlin：集合映射
来源：http://dali.daxiang520.top/Article/details/gtcevlqndm.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.jinqigfzy.top/Article/details/gtjgpmhvvq.html

[T07] Kotlin：集合过滤
来源：http://dali.gaohongyu789.top/Article/details/gtibqmeicz.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.cheryme.top/Article/details/gtnzcyiktd.html

[T08] Kotlin：数据类
来源：http://dali.chenzaomai.com/Article/details/gttddrmnhk.html

data class User(val name: String, val age: Int)
来源：http://dali.daxiang520.top/Article/details/gtpbbelgvp.html

[T09] Kotlin：扩展函数
来源：http://dali.wangdashe.top/Article/details/gtymcmgtfj.html

fun String.exclaim() = this + "!"
来源：http://dali.mhx1999.top/Article/details/gtkbafajjj.html

[T10] Kotlin：默认参数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaolhkewe.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.shuidangran.top/Article/details/gtnssbpbyf.html

[T11] Kotlin：协程
来源：http://dali.cucudq.cn/Article/details/gtgrtglevc.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.guannengcc.top/Article/details/gtzutrsvaj.html

[T12] Kotlin：解构声明
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthpbckdgn.html

val (a, b) = Pair(1, 2)
来源：http://dali.jinghuilouyu.cn/Article/details/gttaswgukw.html

[T13] Kotlin：只读 Map
来源：http://dali.hammf.cn/Article/details/gtnedavwiq.html

val m = mapOf("a" to 1)
来源：http://dali.vqdsnc.cn/Article/details/gtfcdvrqnp.html

[T14] Kotlin：循环
来源：http://dali.nanxinkj.top/Article/details/gtkqrdttdx.html

for (i in 1..10) println(i)
来源：http://dali.gotoacloud.top/Article/details/gtjuvbfgef.html

[T15] Kotlin：接口
来源：http://dali.cdnleiting.top/Article/details/gtkyrexutq.html

interface Shape { fun area(): Double }
来源：http://dali.jqgufenzy.top/Article/details/gtzgdimqfo.html

[T16] Swift：Hello World
来源：http://dali.wangdashe.top/Article/details/gtjrawmwzy.html

print("Hello")
来源：http://dali.gzhubu.top/Article/details/gtaiblgnbf.html

[T17] Swift：变量与常量
来源：http://dali.jiagoushi.top/Article/details/gtzdjwpfol.html

var a = 1;  let b = 2
来源：http://dali.daria6918.cn/Article/details/gtnoqjwhon.html

[T18] Swift：字符串插值
来源：http://dali.sysykeji.top/Article/details/gtkokfpezt.html

"值: \(b)"
来源：http://dali.jyoumei.cn/Article/details/gtierpdduo.html

[T19] Swift：可选绑定
来源：http://dali.wangdashe.top/Article/details/gtvgnbviba.html

if let n = opt { print(n) }
来源：http://dali.snrcjt.cn/Article/details/gtomcjkpdg.html

[T20] Swift：数组操作
来源：http://dali.hysaishi.cn/Article/details/gtlqfdvoko.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.316326.xyz/Article/details/gtitmncrwe.html

[T21] Swift：遍历
来源：http://dali.jqgfzy.top/Article/details/gtdtbagjjp.html

for x in a { print(x) }
来源：http://dali.nanxuanxn.top/Article/details/gtwdulpamc.html

[T22] Swift：字典
来源：http://dali.yanxiufei.cn/Article/details/gtcswpnuwx.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.jiagoushi.top/Article/details/gtcarfaypm.html

[T23] Swift：函数
来源：http://dali.jinqigfzy.top/Article/details/gtexdcqfzo.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.guowangkeji.top/Article/details/gtqkufbcaj.html

[T24] Swift：闭包
来源：http://dali.yj20258888.top/Article/details/gtzjfkmnqi.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.hfpthk.cn/Article/details/gtenobelyq.html

[T25] Swift：结构体
来源：http://dali.jyoumei.cn/Article/details/gtrpqekccu.html

struct P { var x: Int }
来源：http://dali.xuanzx.com/Article/details/gtkgeffphj.html

[T26] Swift：类与重写
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsxcspzfs.html

class A: Base { override func f() {} }
来源：http://dali.havefunace.top/Article/details/gtuyhalnml.html

[T27] Swift：错误处理
来源：http://dali.yuxming.cn/Article/details/gthrlmxnvt.html

do { try f() } catch { print(error) }
来源：http://dali.gotoacloud.top/Article/details/gttkxexdzv.html

[T28] Swift：枚举
来源：http://dali.0kj1m.cn/Article/details/gthenvcsld.html

enum Color { case red, green }
来源：http://dali.ivvv.top/Article/details/gtqoxayehr.html

[T29] Swift：guard 提前返回
来源：http://dali.guowangkeji.top/Article/details/gtrbilxfhj.html

guard let x = opt else { return }
来源：http://dali.xinyue.icu/Article/details/gtewbbwbel.html

[T30] Swift：协议
来源：http://dali.shanyushiyangtech.top/Article/details/gtebvvipcj.html

protocol Shape { func area() -> Double }
来源：http://dali.jianghu66.top/Article/details/gtzqxqbqyt.html

[T31] Lua：Hello World
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfpqptkbr.html

print("Hello")
来源：http://dali.fengsongda.top/Article/details/gtdaxeipec.html

[T32] Lua：局部变量
来源：http://dali.feifeiyinyue.top/Article/details/gttngfbqpb.html

local a = 1
来源：http://dali.cdnleiting.top/Article/details/gtqybjlonm.html

[T33] Lua：表（数组）
来源：http://dali.hongshengwenyu.top/Article/details/gtjijyxeqh.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.xuanzx.com/Article/details/gtkflfifyq.html

[T34] Lua：遍历表
来源：http://dali.havefunace.top/Article/details/gtyhjeermn.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.pycfn.com/Article/details/gtiaekpezh.html

[T35] Lua：字典表
来源：http://dali.jlsjyb.cn/Article/details/gthfzluwox.html

local d = { a = 1 };  d.b = 2
来源：http://dali.iojbl.cn/Article/details/gtbcgvtywg.html

[T36] Lua：函数
来源：http://dali.sufxvd.cn/Article/details/gtarijiowp.html

function add(a, b) return a + b end
来源：http://dali.daria6918.cn/Article/details/gtijabsazx.html

[T37] Lua：字符串拼接
来源：http://dali.shuidangran.top/Article/details/gtljbyucgl.html

"a" .. "b"
来源：http://dali.hywenlv.cn/Article/details/gtiqzhpwjq.html

[T38] Lua：条件
来源：http://dali.nanxuanxn.top/Article/details/gtifwsfvqi.html

if x > 0 then print("正") end
来源：http://dali.xylfe.cn/Article/details/gtpwvjpyhz.html

[T39] Lua：模式匹配
来源：http://dali.hywenlv.cn/Article/details/gtltufvdcf.html

string.find(s, "%d+")
来源：http://dali.shzxlz.cn/Article/details/gtgfdhsdyp.html

[T40] Lua：元表
来源：http://dali.shangyingyoupin.top/Article/details/gtaahfpdju.html

setmetatable({}, { __index = base })
来源：http://dali.daria6918.cn/Article/details/gtkknutmdh.html

[T41] Perl：Hello World
来源：http://dali.fengsongda.top/Article/details/gtfughvhel.html

print "Hello\n";
来源：http://dali.jinqigufen.top/Article/details/gtmpkhqzxf.html

[T42] Perl：变量类型
来源：http://dali.nanxinkj.top/Article/details/gtnnhkdukq.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.shanyushiyangtech.top/Article/details/gtyaphbydy.html

[T43] Perl：字符串插值
来源：http://dali.zhixingplan.top/Article/details/gtoyavople.html

"值: $a"
来源：http://dali.cheryme.top/Article/details/gtcsggworf.html

[T44] Perl：条件
来源：http://dali.316326.xyz/Article/details/gtlzshwlnx.html

if ($a > 0) { print "正"; }
来源：http://dali.cqqwz.cn/Article/details/gtinuwjpmp.html

[T45] Perl：数组遍历
来源：http://dali.yvedp.cn/Article/details/gtppkkqlku.html

for my $x (@arr) { print $x; }
来源：http://dali.sweek.top/Article/details/gtqjrgzqrw.html

[T46] Perl：哈希操作
来源：http://dali.redwolf501.top/Article/details/gtcsegazmm.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.gzhubu.top/Article/details/gtbnbkvydk.html

[T47] Perl：正则捕获
来源：http://dali.iojbl.cn/Article/details/gtpfefyosb.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.9152youxi.cn/Article/details/gtydiifqiv.html

[T48] Perl：正则替换
来源：http://dali.shzxlz.cn/Article/details/gtixpnjqwc.html

$s =~ s/old/new/g;
来源：http://dali.jlsjyb.cn/Article/details/gttziizgnw.html

[T49] Perl：函数
来源：http://dali.chenlongwang.top/Article/details/gtbqhxzhnl.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.fzhhl.top/Article/details/gtzpmarkfr.html

[T50] Perl：逐行读文件
来源：http://dali.shanyushiyangtech.top/Article/details/gtlnevhwnh.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtszeoyfrc.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.pycfn.com/Article/details/gtaipldeiz.html

[T51] Scala：Hello World
来源：http://dali.mhx1999.top/Article/details/gthgbrwvjp.html

println("Hello")
来源：http://dali.jyoumei.cn/Article/details/gtmrfwhdjk.html

[T52] Scala：变量
来源：http://dali.0kj1m.cn/Article/details/gtjkyerzzs.html

val a = 1;  var b = 2
来源：http://dali.hongshengwenyu.top/Article/details/gtwfudycln.html

[T53] Scala：字符串插值
来源：http://dali.zhiwuduotai.top/Article/details/gthhyocpwh.html

s"值: $b"
来源：http://dali.zhoulong.xyz/Article/details/gtzawskkqz.html

[T54] Scala：集合映射
来源：http://dali.jqgufenzy.top/Article/details/gtxqeryjlt.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.yanxiufei.cn/Article/details/gtcyxqepue.html

[T55] Scala：集合过滤
来源：http://dali.gogol.net.cn/Article/details/gtbhgnyrui.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.chenjidiqi.icu/Article/details/gtdmofosit.html

[T56] Scala：样例类
来源：http://dali.jqgfzy.top/Article/details/gtzllejped.html

case class User(name: String, age: Int)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthgdbvcqo.html

[T57] Scala：模式匹配
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsicmrbhx.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.yuxming.cn/Article/details/gtlvbyetmr.html

[T58] Scala：函数定义
来源：http://dali.yueranfly.top/Article/details/gtjpbuyjry.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.yuxming.cn/Article/details/gtpygzyovg.html

[T59] Scala：循环
来源：http://dali.birdmap.top/Article/details/gtwbfmiptm.html

for (i <- 1 to 10) println(i)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdrbtgmli.html

[T60] Scala：折叠
来源：http://dali.wangdashe.top/Article/details/gtakcayjek.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhongyouzk.top/Article/details/gtziqpmrmc.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtyjdgibid.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.jinqigufen.top/Article/details/gtulzcitra.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtugenmvip.html

[U01] Py：创建虚拟环境
来源：http://dali.ydzc1.top/Article/details/gtddqzrglx.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.birdmap.top/Article/details/gtpptmdcoy.html

[U02] Py：导出 / 安装依赖
来源：http://dali.guowangkeji.top/Article/details/gtrvvkqziv.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.jyoumei.cn/Article/details/gtqedpuskf.html

[U03] Py：加载 .env 配置
来源：http://dali.haohaochexian.top/Article/details/gtisxvnqex.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.haohaochexian.top/Article/details/gtcdyztldt.html

[U04] Py：变量调试打印
来源：http://dali.nanxinkj.top/Article/details/gtwcixiycf.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhiwuduotai.top/Article/details/gthxmfaxct.html

[U05] Py：列表去重且保序
来源：http://dali.cheryme.top/Article/details/gtnjvbidcg.html

list(dict.fromkeys(arr))
来源：http://dali.hnxiangtu.top/Article/details/gtjbjcbmrm.html

[U06] Py：合并两个字典
来源：http://dali.dashuyun.cn/Article/details/gtbhdxwoar.html

{**a, **b}
来源：http://dali.cucudq.cn/Article/details/gtiofmlxdw.html


<!-- 参考信息 -->