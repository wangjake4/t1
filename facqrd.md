代发 wailian999

free -h;  ps aux | grep nginx
来源：http://dali.jiagoushi.top/Article/details/gt2bxialbdn.html

[R64] 结束进程
来源：http://dali.jinqigufen.top/Article/details/gt2coxuqdub.html

kill -9 $(pgrep -f app.py)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dpwebkxh.html

[R65] 查看端口占用
来源：http://dali.cdnleiting.top/Article/details/gt2ntwukeaj.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.shzxlz.cn/Article/details/gt2yovvsvrb.html

[R66] 定时任务
来源：http://dali.redwolf501.top/Article/details/gt2dgzhizyq.html

crontab -e;  crontab -l
来源：http://dali.nwbrower.top/Article/details/gt2bokafofd.html

[R67] 生成随机十六进制串
来源：http://dali.svipenyu.cn/Article/details/gt2uxplmdtp.html

openssl rand -hex 16
来源：http://dali.svipenyu.cn/Article/details/gt2sahfquxa.html

[R68] 计算文件校验值
来源：http://dali.yj20258888.top/Article/details/gt2ocfmozyd.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.gaohongyu789.top/Article/details/gt2rxrytxwq.html

[R69] 生成随机密码
来源：http://dali.snrcjt.cn/Article/details/gt2behslbfu.html

head -c 16 /dev/urandom | base64
来源：http://dali.ppjwa.cn/Article/details/gt2njvhecgj.html

[R70] 时间戳与互转
来源：http://dali.fengsongda.top/Article/details/gt2tqzlwoks.html

date +%s;  date -d @1700000000
来源：http://dali.zycfv.cn/Article/details/gt2anfhotzp.html

[R71] 日期格式化
来源：http://dali.9152youxi.cn/Article/details/gt2mpvwgzng.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.ppjwa.cn/Article/details/gt2daqhbnjc.html

[R72] 等待端口就绪
来源：http://dali.zhengqikj.top/Article/details/gt2gryjwpca.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.xylfe.cn/Article/details/gt2dniwmduf.html

[R73] 分割大日志
来源：http://dali.hfpthk.cn/Article/details/gt2yjqczegc.html

split -l 1000 big.log part_
来源：http://dali.hfpthk.cn/Article/details/gt2mvruoiym.html

[R74] 批量重命名
来源：http://dali.pycfn.com/Article/details/gt2sbwixphr.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.pengpengdd.cyou/Article/details/gt2toazukii.html

[R75] 导出环境变量
来源：http://dali.shuidangran.top/Article/details/gt2ibadszzk.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.jianghu66.top/Article/details/gt2idkojtdf.html

[R76] 使用临时文件
来源：http://dali.meibo888.top/Article/details/gt2saaafknv.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.yvedp.cn/Article/details/gt2govsltmj.html

[R77] 读取用户输入
来源：http://dali.jyoumei.cn/Article/details/gt2fahgfptq.html

read -rp "请输入: " ans
来源：http://dali.birdmap.top/Article/details/gt2qojawqlu.html

[R78] 交互式菜单
来源：http://dali.sufxvd.cn/Article/details/gt2monbwbbv.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.nwbrower.top/Article/details/gt2wfsebrit.html

[R79] 解析命令行选项
来源：http://dali.yangfankeji.com/Article/details/gt2raspkdqa.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.andypj.xyz/Article/details/gt2qsvktenr.html

[R80] 查看脚本执行耗时
来源：http://dali.kuanghao11.cn/Article/details/gt2qskzaqfq.html

time ./run.sh
来源：http://dali.cucudq.cn/Article/details/gt2weslkusq.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2brqjddno.html

S. C / C++ 专题
来源：http://dali.guannengcc.top/Article/details/gt2hdclyxne.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2volxhoea.html

[S01] C：Hello World
来源：http://dali.aizwys.cn/Article/details/gt2wrjxbywz.html

#include <stdio.h>
来源：http://dali.hammf.cn/Article/details/gt2fpjgmzyv.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.cashguo.top/Article/details/gt2xqtxytcq.html

[S02] C：变量与格式化输出
来源：http://dali.hnqzz.top/Article/details/gt2ajqfmpwk.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bkcmatkl.html

[S03] C：读入整数
来源：http://dali.yongpay.top/Article/details/gt2kqhljkbk.html

int x; scanf("%d", &x);
来源：http://dali.zhoulong.xyz/Article/details/gt2qziehdmq.html

[S04] C：字符串复制
来源：http://dali.meibo888.top/Article/details/gt2xautshro.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.hongshengwenyu.top/Article/details/gt2umvftaas.html

[S05] C：字符串长度
来源：http://dali.snrcjt.cn/Article/details/gt2kwoqvqhj.html

strlen(s)
来源：http://dali.bjfxy.top/Article/details/gt2ttyzzsvy.html

[S06] C：字符串比较
来源：http://dali.zhiwuduotai.top/Article/details/gt2pzmljjmz.html

strcmp(a, b) == 0
来源：http://dali.xylfe.cn/Article/details/gt2jvkajeug.html

[S07] C：数组遍历求和
来源：http://dali.wangdashe.top/Article/details/gt2aojhqzpm.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.aibaodan.cn/Article/details/gt2rdtdurmm.html

[S08] C：动态内存分配与释放
来源：http://dali.yuxming.cn/Article/details/gt2xbijdihl.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.yueranfly.top/Article/details/gt2hfryswnm.html

[S09] C：结构体定义与初始化
来源：http://dali.cdnleiting.top/Article/details/gt2ohzxcqpn.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.ydzc1.top/Article/details/gt2oqffbhrk.html

[S10] C：指针与解引用
来源：http://dali.aizwys.cn/Article/details/gt2ivhyjacg.html

int *p = &a;  *p = 5;
来源：http://dali.daria6918.cn/Article/details/gt2hhfajcmw.html

[S11] C：逐行读文件
来源：http://dali.dashuyun.cn/Article/details/gt2ielepwef.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.cheryme.top/Article/details/gt2khnkjgvp.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.dianchejie.cn/Article/details/gt2xmifjecc.html

fclose(f);
来源：http://dali.smart0.xyz/Article/details/gt2lehtdeyy.html

[S12] C：写文件
来源：http://dali.chenzaomai.com/Article/details/gt2qlchvnzy.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.wangshuangyany.cn/Article/details/gt2ctlvbuqu.html

[S13] C：宏定义
来源：http://dali.nwbrower.top/Article/details/gt2saanayej.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.fengsongda.top/Article/details/gt2xsptmbbt.html

[S14] C：枚举
来源：http://dali.pycfn.com/Article/details/gt2pgnoqrly.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhoulong.xyz/Article/details/gt2clvmfupi.html

[S15] C：类型转换
来源：http://dali.aizwys.cn/Article/details/gt2eaztetpd.html

(double) a / b
来源：http://dali.zhoulong.xyz/Article/details/gt2obvbxoro.html

[S16] C：位操作置位
来源：http://dali.nanxinkj.top/Article/details/gt2bxlxttvf.html

x |= (1 << 3);
来源：http://dali.yangfankeji.com/Article/details/gt2pdhlivba.html

[S17] C：安全拼接字符串
来源：http://dali.smart0.xyz/Article/details/gt2hvhblgvx.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.9152youxi.cn/Article/details/gt2rrofubqv.html

[S18] C：命令行参数
来源：http://dali.zhongyouzk.top/Article/details/gt2ljnltkbs.html

int main(int argc, char **argv)
来源：http://dali.hnxiangtu.top/Article/details/gt2ncmxtinf.html

[S19] C：快速排序
来源：http://dali.nwbrower.top/Article/details/gt2fjvwixrp.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.dianchejie.cn/Article/details/gt2oxtgiejt.html

[S20] C：二分查找
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yfnbwvxa.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.quarkkingdee.top/Article/details/gt2czcwxgqo.html

[S21] C：字符类别判断
来源：http://dali.xuetiantiany.cn/Article/details/gt2thvswhdu.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.nwbrower.top/Article/details/gt2pblhvnev.html

[S22] C：字符串转数字
来源：http://dali.gotoacloud.top/Article/details/gt2hriwignc.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.hywenlv.cn/Article/details/gt2lzuebzqo.html

[S23] C：随机数
来源：http://dali.meibo888.top/Article/details/gt2mvbzxgkr.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.cucudq.cn/Article/details/gt2obmrrnai.html

[S24] C：获取本地时间
来源：http://dali.yongpay.top/Article/details/gt2nznhkbou.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.tian-w.cn/Article/details/gt2repzljaw.html

[S25] C：内存拷贝
来源：http://dali.yj20258.top/Article/details/gt2mskksmai.html

memcpy(dst, src, n);
来源：http://dali.zhoulong.xyz/Article/details/gt2kghsluhk.html

[S26] C：内存清零
来源：http://dali.nanxinkj.top/Article/details/gt2krskgibl.html

memset(a, 0, sizeof a);
来源：http://dali.meibo888.top/Article/details/gt2cyeacjeu.html

[S27] C：定义常量
来源：http://dali.guowangkeji.top/Article/details/gt2uqlytmzt.html

const double PI = 3.14159;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pjkdfdud.html

[S28] C：静态变量
来源：http://dali.haohaochexian.top/Article/details/gt2ktexozdk.html

static int counter = 0;
来源：http://dali.hysaishi.cn/Article/details/gt2eggcnvfn.html

[S29] C：变参函数
来源：http://dali.cucudq.cn/Article/details/gt2eiqytjzj.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.birdmap.top/Article/details/gt2jlgnsmlk.html

[S30] C：头文件保护
来源：http://dali.zycfv.cn/Article/details/gt2frsbhddf.html

#ifndef X_H
来源：http://dali.jqgfzy.top/Article/details/gt2gclxrqkx.html

#define X_H
来源：http://dali.zhoulong.xyz/Article/details/gt2exkuwlzg.html

#endif
来源：http://dali.pycfn.com/Article/details/gt2gpqevqyq.html

[S31] C++：Hello World
来源：http://dali.hywenlv.cn/Article/details/gt2lrimbaxi.html

#include <iostream>
来源：http://dali.shzxlz.cn/Article/details/gt2acfyeyug.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.gogol.net.cn/Article/details/gt2vvolfxao.html

[S32] C++：字符串
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pxsabizv.html

std::string s = "hi";  s += "!";
来源：http://dali.chenzaomai.com/Article/details/gt2csfimiwd.html

[S33] C++：vector 增删
来源：http://dali.havefunace.top/Article/details/gt2ujxanquq.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.cqqwz.cn/Article/details/gt2xufpillo.html

[S34] C++：遍历 vector
来源：http://dali.sufxvd.cn/Article/details/gt2tqhvbbng.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.tanke756.top/Article/details/gt2wferrice.html

[S35] C++：map
来源：http://dali.gaohongyu789.top/Article/details/gt2wcocvets.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.xuanzx.com/Article/details/gt2iungpclx.html

[S36] C++：unordered_map
来源：http://dali.jyoumei.cn/Article/details/gt2sxbnsglz.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.cashguo.top/Article/details/gt2hohcsxmk.html

[S37] C++：set
来源：http://dali.sysykeji.top/Article/details/gt2dcknvghj.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.haohaochexian.top/Article/details/gt2sqccpfpg.html

[S38] C++：排序
来源：http://dali.zhixingplan.top/Article/details/gt2toxuqjpu.html

std::sort(v.begin(), v.end());
来源：http://dali.dashuyun.cn/Article/details/gt2saobqggw.html

[S39] C++：自定义比较器排序
来源：http://dali.gaohongyu789.top/Article/details/gt2heyyljzr.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.andypj.xyz/Article/details/gt2gbqwfatw.html

[S40] C++：查找元素
来源：http://dali.ydzc1.top/Article/details/gt2hfpqrebb.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhengqikj.top/Article/details/gt2ipsrttje.html

[S41] C++：类与构造函数
来源：http://dali.iojbl.cn/Article/details/gt2gpbvmlgw.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.shuidangran.top/Article/details/gt2wylkzlyf.html

[S42] C++：继承与虚函数
来源：http://dali.shangyingyoupin.top/Article/details/gt2xurmmfhf.html

class B : public Base { public: void f() override {} };
来源：http://dali.aibaodan.cn/Article/details/gt2bjqhqspg.html

[S43] C++：智能指针
来源：http://dali.yangfankeji.com/Article/details/gt2kkejzckd.html

auto p = std::make_unique<int>(5);
来源：http://dali.jyoumei.cn/Article/details/gt2vrxxtfyx.html

[S44] C++：引用传参
来源：http://dali.sysykeji.top/Article/details/gt2bnxqmisc.html

void inc(int &x) { ++x; }
来源：http://dali.gogol.net.cn/Article/details/gt2qxrqvpoa.html

[S45] C++：lambda
来源：http://dali.xuetiantiany.cn/Article/details/gt2mxmaslyv.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.chenlongwang.top/Article/details/gt2jqyidzmf.html

[S46] C++：函数模板
来源：http://dali.yj202588.top/Article/details/gt2zwzjbdis.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.dianchejie.cn/Article/details/gt2sasxlram.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhiwuduotai.top/Article/details/gt2icjxxflm.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhengqikj.top/Article/details/gt2ubjpshvg.html

[S48] C++：逐行读文件
来源：http://dali.haohaochexian.top/Article/details/gt2yxecrdxp.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.chenzaomai.com/Article/details/gt2kmlqovpl.html

while (std::getline(in, line)) { }
来源：http://dali.tian-w.cn/Article/details/gt2zzngxdgn.html

[S49] C++：写文件
来源：http://dali.xziqi.cn/Article/details/gt2uaskmfaq.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.hnqzz.top/Article/details/gt2yavqfywd.html

[S50] C++：格式化数字
来源：http://dali.jqgufenzy.top/Article/details/gt2iwevqvgb.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.havefunace.top/Article/details/gt2qnubfmdr.html

[S51] C++：显式类型转换
来源：http://dali.jqgfzy.top/Article/details/gt2qrhzluea.html

static_cast<double>(a) / b
来源：http://dali.yueranfly.top/Article/details/gt2pzkbvrpq.html

[S52] C++：const 与 noexcept
来源：http://dali.fzhhl.top/Article/details/gt2cllsucph.html

int size() const noexcept { return n_; }
来源：http://dali.tianlin.xyz/Article/details/gt2cljbniia.html

[S53] C++：移动语义
来源：http://dali.yuanzhike.top/Article/details/gt2eibwboij.html

std::vector<int> w = std::move(v);
来源：http://dali.yuanzhike.top/Article/details/gt2wjxhmoeh.html

[S54] C++：异常处理
来源：http://dali.havefunace.top/Article/details/gt2mbbdosej.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.sufxvd.cn/Article/details/gt2pnrluryc.html

[S55] C++：结构化绑定
来源：http://dali.redwolf501.top/Article/details/gt2ualziffw.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2awdntfzh.html

[S56] C++：optional
来源：http://dali.yj20258888.top/Article/details/gt2rruyilwh.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.shuidangran.top/Article/details/gt2ufjzqjiz.html

[S57] C++：编译期常量
来源：http://dali.bjfxy.top/Article/details/gt2pebzakeg.html

constexpr int N = 10;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qpkutyst.html

[S58] C++：命名空间
来源：http://dali.quarkkingdee.top/Article/details/gt2xdqyqlrz.html

namespace ns { int f() { return 1; } }
来源：http://dali.xziqi.cn/Article/details/gt2tqyevkkh.html

[S59] C++：静态断言
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uzdzkfjr.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.gzhubu.top/Article/details/gt2hbyobumu.html

[S60] C++：遍历并删除元素
来源：http://dali.gaohongyu789.top/Article/details/gt2ryzkzvtv.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.pycfn.com/Article/details/gt2yabersba.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gt2asuxylbj.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.chenzaomai.com/Article/details/gt2ngbshmel.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2jevvgytt.html

[T01] Kotlin：Hello World
来源：http://dali.aizwys.cn/Article/details/gt2rljixyvd.html

println("Hello")
来源：http://dali.jiagoushi.top/Article/details/gt2pqkhoorm.html

[T02] Kotlin：变量
来源：http://dali.iojbl.cn/Article/details/gt2sgbmxfqu.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zdqjudy.top/Article/details/gt2hlpzdsrn.html

[T03] Kotlin：字符串模板
来源：http://dali.pengpengdd.cyou/Article/details/gt2rnzxqntv.html

"值: $b"
来源：http://dali.hywenlv.cn/Article/details/gt2dddfktfh.html

[T04] Kotlin：空安全
来源：http://dali.sysykeji.top/Article/details/gt2anqzgmqs.html

val n: String? = null;  n?.length
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jbjjxkom.html

[T05] Kotlin：when 表达式
来源：http://dali.pengpengdd.cyou/Article/details/gt2kdrwlyge.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lvldulxh.html

[T06] Kotlin：集合映射
来源：http://dali.fengsongda.top/Article/details/gt2svfoekmw.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.pycfn.com/Article/details/gt2urtsoeel.html

[T07] Kotlin：集合过滤
来源：http://dali.jiagoushi.top/Article/details/gt2kxlwmxgo.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.wangshuangyany.cn/Article/details/gt2mldzkoli.html

[T08] Kotlin：数据类
来源：http://dali.jlsjyb.cn/Article/details/gt2mssqyvgb.html

data class User(val name: String, val age: Int)
来源：http://dali.chenzaomai.com/Article/details/gt2bpeqmbtb.html

[T09] Kotlin：扩展函数
来源：http://dali.jianghu66.top/Article/details/gt2daketnil.html

fun String.exclaim() = this + "!"
来源：http://dali.jinqigufen.top/Article/details/gt2edoeuyvc.html

[T10] Kotlin：默认参数
来源：http://dali.hnqzz.top/Article/details/gt2ethobfck.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.yongpay.top/Article/details/gt2udojvjsr.html

[T11] Kotlin：协程
来源：http://dali.yueranfly.top/Article/details/gt2stfuectb.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vgiyxnub.html

[T12] Kotlin：解构声明
来源：http://dali.smart0.xyz/Article/details/gt2hgyiojpd.html

val (a, b) = Pair(1, 2)
来源：http://dali.cheryme.top/Article/details/gt2odclysgh.html

[T13] Kotlin：只读 Map
来源：http://dali.ivvv.top/Article/details/gt2mdasltzc.html

val m = mapOf("a" to 1)
来源：http://dali.nanxuanxn.top/Article/details/gt2pgfseclh.html

[T14] Kotlin：循环
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wrurfsyu.html

for (i in 1..10) println(i)
来源：http://dali.aibaodan.cn/Article/details/gt2zjynfapv.html

[T15] Kotlin：接口
来源：http://dali.yangfankeji.com/Article/details/gt2wsvophyj.html

interface Shape { fun area(): Double }
来源：http://dali.dashuyun.cn/Article/details/gt2giiqxcwq.html

[T16] Swift：Hello World
来源：http://dali.hysaishi.cn/Article/details/gt2wkmbnonj.html

print("Hello")
来源：http://dali.yuxming.cn/Article/details/gt2fevgeocc.html

[T17] Swift：变量与常量
来源：http://dali.jqgufenzy.top/Article/details/gt2flnthvvz.html

var a = 1;  let b = 2
来源：http://dali.feifeiyinyue.top/Article/details/gt2vskbgmar.html

[T18] Swift：字符串插值
来源：http://dali.zhongyouzk.top/Article/details/gt2wkrzveee.html

"值: \(b)"
来源：http://dali.nanxinkj.top/Article/details/gt2pybbmxum.html

[T19] Swift：可选绑定
来源：http://dali.shuidangran.top/Article/details/gt2juvhghss.html

if let n = opt { print(n) }
来源：http://dali.0kj1m.cn/Article/details/gt2ifmyzsdd.html

[T20] Swift：数组操作
来源：http://dali.vqdsnc.cn/Article/details/gt2izazhtvh.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.bjfxy.top/Article/details/gt2wkkujshl.html

[T21] Swift：遍历
来源：http://dali.hfpthk.cn/Article/details/gt2oqdnfhcq.html

for x in a { print(x) }
来源：http://dali.pengpengdd.cyou/Article/details/gt2cwwagyhy.html

[T22] Swift：字典
来源：http://dali.ybcxt.top/Article/details/gt2tuxwvdwf.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.shangyingyoupin.top/Article/details/gt2moyhhcue.html

[T23] Swift：函数
来源：http://dali.ppjwa.cn/Article/details/gt2hareoppk.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.bjfxy.top/Article/details/gt2shqxniib.html

[T24] Swift：闭包
来源：http://dali.zycfv.cn/Article/details/gt2mbkifieg.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.jqgfzy.top/Article/details/gt2ncevtzbq.html

[T25] Swift：结构体
来源：http://dali.hywenlv.cn/Article/details/gt2bwdsyeha.html

struct P { var x: Int }
来源：http://dali.zhiwuduotai.top/Article/details/gt2yylvmlth.html

[T26] Swift：类与重写
来源：http://dali.kuanghao11.cn/Article/details/gt2yonszspr.html

class A: Base { override func f() {} }
来源：http://dali.ppjwa.cn/Article/details/gt2vwdrahhx.html

[T27] Swift：错误处理
来源：http://dali.zdqjudy.top/Article/details/gt2amuyqlvf.html

do { try f() } catch { print(error) }
来源：http://dali.havefunace.top/Article/details/gt2puargtbd.html

[T28] Swift：枚举
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yrapifjj.html

enum Color { case red, green }
来源：http://dali.jlsjyb.cn/Article/details/gt2yhqtbuew.html

[T29] Swift：guard 提前返回
来源：http://dali.xinyue.icu/Article/details/gt2hdeuavkk.html

guard let x = opt else { return }
来源：http://dali.hnxiangtu.top/Article/details/gt2xnrygjea.html

[T30] Swift：协议
来源：http://dali.jqgfzy.top/Article/details/gt2foarfrjb.html

protocol Shape { func area() -> Double }
来源：http://dali.svipenyu.cn/Article/details/gt2bnnbkwga.html

[T31] Lua：Hello World
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jaqwomkp.html

print("Hello")
来源：http://dali.jinqigufen.top/Article/details/gt2qycacjcf.html

[T32] Lua：局部变量
来源：http://dali.hongshengwenyu.top/Article/details/gt2mtcvuxmh.html

local a = 1
来源：http://dali.dianchejie.cn/Article/details/gt2vbkjejov.html

[T33] Lua：表（数组）
来源：http://dali.xinyue.icu/Article/details/gt2gvyvntsr.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.jinqigufen.top/Article/details/gt2pjwmiabb.html

[T34] Lua：遍历表
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yyaobxgc.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.aizwys.cn/Article/details/gt2onogrnby.html

[T35] Lua：字典表
来源：http://dali.cucudq.cn/Article/details/gt2ibkkzwvq.html

local d = { a = 1 };  d.b = 2
来源：http://dali.sufxvd.cn/Article/details/gt2qopmruqz.html

[T36] Lua：函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2iwckchmf.html

function add(a, b) return a + b end
来源：http://dali.cashguo.top/Article/details/gt2vuupejza.html

[T37] Lua：字符串拼接
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2oqajyvqz.html

"a" .. "b"
来源：http://dali.xinyue.icu/Article/details/gt2pfpjfuls.html

[T38] Lua：条件
来源：http://dali.mhx1999.top/Article/details/gt2iqjfklyb.html

if x > 0 then print("正") end
来源：http://dali.fzhhl.top/Article/details/gt2vydvtfsm.html

[T39] Lua：模式匹配
来源：http://dali.jiagoushi.top/Article/details/gt2ztkawimd.html

string.find(s, "%d+")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xmizdyiy.html

[T40] Lua：元表
来源：http://dali.zhiwuduotai.top/Article/details/gt2qzwexmsh.html

setmetatable({}, { __index = base })
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nflqgmnc.html

[T41] Perl：Hello World
来源：http://dali.ppjwa.cn/Article/details/gt2garkseij.html

print "Hello\n";
来源：http://dali.zhixingplan.top/Article/details/gt2tqtnwbov.html

[T42] Perl：变量类型
来源：http://dali.yj20258888.top/Article/details/gt2prjccabk.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2roxglcku.html

[T43] Perl：字符串插值
来源：http://dali.zhongyouzk.top/Article/details/gt2mkuccwhz.html

"值: $a"
来源：http://dali.vqdsnc.cn/Article/details/gt2jpbyzhus.html

[T44] Perl：条件
来源：http://dali.chenlongwang.top/Article/details/gt2xeanrqij.html

if ($a > 0) { print "正"; }
来源：http://dali.xziqi.cn/Article/details/gt2sjcvvsgr.html

[T45] Perl：数组遍历
来源：http://dali.yj20258.top/Article/details/gt2xxvgtlcu.html

for my $x (@arr) { print $x; }
来源：http://dali.c1oappe.top/Article/details/gt2pbadnhqr.html

[T46] Perl：哈希操作
来源：http://dali.zhiwuduotai.top/Article/details/gt2xdzkfdli.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.ybcxt.top/Article/details/gt2gmwwqubp.html

[T47] Perl：正则捕获
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sjhsdtvh.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.dianchejie.cn/Article/details/gt2pusjykkh.html

[T48] Perl：正则替换
来源：http://dali.meibo888.top/Article/details/gt2neptynxq.html

$s =~ s/old/new/g;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dpwzgyzo.html

[T49] Perl：函数
来源：http://dali.chenjidiqi.icu/Article/details/gt2oyczzgfa.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.tianlin.xyz/Article/details/gt2pfaslakf.html

[T50] Perl：逐行读文件
来源：http://dali.guannengcc.top/Article/details/gt2lhyqutai.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.jlsjyb.cn/Article/details/gt2yzoqmkgi.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.chenlongwang.top/Article/details/gt2iezzgxfe.html

[T51] Scala：Hello World
来源：http://dali.ivvv.top/Article/details/gt2zsiujemr.html

println("Hello")
来源：http://dali.hnxiangtu.top/Article/details/gt2eakorete.html

[T52] Scala：变量
来源：http://dali.yongpay.top/Article/details/gt2rllvouiq.html

val a = 1;  var b = 2
来源：http://dali.snrcjt.cn/Article/details/gt2cqkfpsun.html

[T53] Scala：字符串插值
来源：http://dali.hysaishi.cn/Article/details/gt2jtswmwgf.html

s"值: $b"
来源：http://dali.fzhhl.top/Article/details/gt2xxfvdssr.html

[T54] Scala：集合映射
来源：http://dali.0kj1m.cn/Article/details/gt2aptiwzgc.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.fengsongda.top/Article/details/gt2efgmpdlh.html

[T55] Scala：集合过滤
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2slhgzpre.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.pengpengdd.cyou/Article/details/gt2ewkkkuxt.html

[T56] Scala：样例类
来源：http://dali.snrcjt.cn/Article/details/gt2auugxuci.html

case class User(name: String, age: Int)
来源：http://dali.yueranfly.top/Article/details/gt2gsftjixh.html

[T57] Scala：模式匹配
来源：http://dali.cqqwz.cn/Article/details/gt2yuakaikq.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhengqikj.top/Article/details/gt2qfitxxak.html

[T58] Scala：函数定义
来源：http://dali.haohaochexian.top/Article/details/gt2ilavzprs.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.yongpay.top/Article/details/gt2taabfati.html

[T59] Scala：循环
来源：http://dali.ppjwa.cn/Article/details/gt2ahkotnnt.html

for (i <- 1 to 10) println(i)
来源：http://dali.gzhubu.top/Article/details/gt2toiptikj.html

[T60] Scala：折叠
来源：http://dali.mhx1999.top/Article/details/gt2nlcbpkfg.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.hysaishi.cn/Article/details/gt2tlgdjohi.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gt2nnqjbwxc.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.nwbrower.top/Article/details/gt2tslozrny.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gt2skjaysqm.html

[U01] Py：创建虚拟环境
来源：http://dali.sufxvd.cn/Article/details/gt2rmaefrok.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.ybcxt.top/Article/details/gt2zperjesp.html

[U02] Py：导出 / 安装依赖
来源：http://dali.jqgfzy.top/Article/details/gt2rmthycqx.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.aibaodan.cn/Article/details/gt2rxrzpyhk.html

[U03] Py：加载 .env 配置
来源：http://dali.xuanzx.com/Article/details/gt2gqoiwhus.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.iojbl.cn/Article/details/gt2jdamtppj.html

[U04] Py：变量调试打印
来源：http://dali.tian-w.cn/Article/details/gt2tachadmp.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.dianchejie.cn/Article/details/gt2wykejpec.html


<!-- 参考信息 -->