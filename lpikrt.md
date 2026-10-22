代发 wailian999

df -h;  du -sh *
来源：http://dali.xinyue.icu/Article/details/gtgeeglfok.html

[R62] 找最占空间的文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjkjuckyw.html

du -ah . | sort -rh | head -10
来源：http://dali.nanxinkj.top/Article/details/gtcxethzod.html

[R63] 内存与进程
来源：http://dali.andypj.xyz/Article/details/gtqezstdfe.html

free -h;  ps aux | grep nginx
来源：http://dali.svipenyu.cn/Article/details/gtzpthruly.html

[R64] 结束进程
来源：http://dali.316326.xyz/Article/details/gtlnmedxbh.html

kill -9 $(pgrep -f app.py)
来源：http://dali.xuanzx.com/Article/details/gtqolgdjbo.html

[R65] 查看端口占用
来源：http://dali.zhixingplan.top/Article/details/gtdbnnbekg.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.ehwqpu.com/Article/details/gtwsehroca.html

[R66] 定时任务
来源：http://dali.kuanghao11.cn/Article/details/gtmduwjzra.html

crontab -e;  crontab -l
来源：http://dali.cheryme.top/Article/details/gtqycejwex.html

[R67] 生成随机十六进制串
来源：http://dali.aibaodan.cn/Article/details/gtbgdkxikn.html

openssl rand -hex 16
来源：http://dali.cashguo.top/Article/details/gtcsoqvcpt.html

[R68] 计算文件校验值
来源：http://dali.yonumen.top/Article/details/gtffvfhtxy.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.nwbrower.top/Article/details/gtydmbrxpl.html

[R69] 生成随机密码
来源：http://dali.ivvv.top/Article/details/gtsdhsjuhk.html

head -c 16 /dev/urandom | base64
来源：http://dali.tian-w.cn/Article/details/gtqbedagwu.html

[R70] 时间戳与互转
来源：http://dali.guannengcc.top/Article/details/gtjcjincza.html

date +%s;  date -d @1700000000
来源：http://dali.0kj1m.cn/Article/details/gtdjmetkrm.html

[R71] 日期格式化
来源：http://dali.yj20258.top/Article/details/gtalnmdpxn.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zycfv.cn/Article/details/gtyibvxbwl.html

[R72] 等待端口就绪
来源：http://dali.zycfv.cn/Article/details/gthbjxrqlf.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.ybcxt.top/Article/details/gtqixatqkt.html

[R73] 分割大日志
来源：http://dali.cqqwz.cn/Article/details/gtkdyvzukn.html

split -l 1000 big.log part_
来源：http://dali.guannengcc.top/Article/details/gteehtbrga.html

[R74] 批量重命名
来源：http://dali.wangdashe.top/Article/details/gtomnkfsha.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.9152youxi.cn/Article/details/gtlwrnxaph.html

[R75] 导出环境变量
来源：http://dali.zhoulong.xyz/Article/details/gtydzfrrtg.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.svipenyu.cn/Article/details/gtpacihhua.html

[R76] 使用临时文件
来源：http://dali.9152youxi.cn/Article/details/gtjxtdwyqt.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.chenzaomai.com/Article/details/gtfaccbpoh.html

[R77] 读取用户输入
来源：http://dali.zhongyouzk.top/Article/details/gtsudioqhe.html

read -rp "请输入: " ans
来源：http://dali.ydzc1.top/Article/details/gtabcxzdzx.html

[R78] 交互式菜单
来源：http://dali.hywenlv.cn/Article/details/gtgeclhpey.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.yangfankeji.com/Article/details/gtkokvcuxl.html

[R79] 解析命令行选项
来源：http://dali.jinqigfzy.top/Article/details/gtbezfnqrz.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.316326.xyz/Article/details/gtosucpvdi.html

[R80] 查看脚本执行耗时
来源：http://dali.tanke756.top/Article/details/gtummxmtad.html

time ./run.sh
来源：http://dali.ybcxt.top/Article/details/gtqrdsfnzn.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtmsedlldn.html

S. C / C++ 专题
来源：http://dali.yvedp.cn/Article/details/gtlbagafqd.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtfjcuygib.html

[S01] C：Hello World
来源：http://dali.guowangkeji.top/Article/details/gtpvjaebyq.html

#include <stdio.h>
来源：http://dali.daria6918.cn/Article/details/gthxghgjwt.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.nanxinkj.top/Article/details/gtllkmkotx.html

[S02] C：变量与格式化输出
来源：http://dali.wangshuangyany.cn/Article/details/gtxmzutern.html

int a = 10; printf("%d\n", a);
来源：http://dali.sufxvd.cn/Article/details/gttwduhbqz.html

[S03] C：读入整数
来源：http://dali.yuxming.cn/Article/details/gtuxqcqdqk.html

int x; scanf("%d", &x);
来源：http://dali.nanxuanxn.top/Article/details/gtlzcjcgle.html

[S04] C：字符串复制
来源：http://dali.zhongyouzk.top/Article/details/gtsrlpazef.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.xuanzx.com/Article/details/gtbdidsmrk.html

[S05] C：字符串长度
来源：http://dali.jlsjyb.cn/Article/details/gtcoliagee.html

strlen(s)
来源：http://dali.xuanzx.com/Article/details/gtpdwltyao.html

[S06] C：字符串比较
来源：http://dali.yuanzhike.top/Article/details/gtcpdmdnmh.html

strcmp(a, b) == 0
来源：http://dali.cucudq.cn/Article/details/gtvhdokyyk.html

[S07] C：数组遍历求和
来源：http://dali.jinghuilouyu.cn/Article/details/gtvfpryuna.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.snrcjt.cn/Article/details/gtbqvpjyzd.html

[S08] C：动态内存分配与释放
来源：http://dali.svipenyu.cn/Article/details/gtfasrsgzb.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.vqdsnc.cn/Article/details/gtizyupemq.html

[S09] C：结构体定义与初始化
来源：http://dali.xylfe.cn/Article/details/gtpqmmrndx.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.ywan-chungtsiang.top/Article/details/gttkfybynt.html

[S10] C：指针与解引用
来源：http://dali.xuanzx.com/Article/details/gtyonqfoyu.html

int *p = &a;  *p = 5;
来源：http://dali.ivvv.top/Article/details/gtgbyrvdvf.html

[S11] C：逐行读文件
来源：http://dali.tian-w.cn/Article/details/gtrenrkxjg.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zdqjudy.top/Article/details/gtxcgbndfk.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.hnqzz.top/Article/details/gtydxfihwa.html

fclose(f);
来源：http://dali.hywenlv.cn/Article/details/gtmoehembu.html

[S12] C：写文件
来源：http://dali.ppjwa.cn/Article/details/gtcnxbmywt.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.316326.xyz/Article/details/gtmcwjrwgu.html

[S13] C：宏定义
来源：http://dali.jqgfzy.top/Article/details/gtfcckwsvc.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.sysykeji.top/Article/details/gtakdehepx.html

[S14] C：枚举
来源：http://dali.jinyuanbaomall.cn/Article/details/gtthshamop.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.yuxming.cn/Article/details/gtubcshnnj.html

[S15] C：类型转换
来源：http://dali.ivvv.top/Article/details/gtdpcihfvg.html

(double) a / b
来源：http://dali.xziqi.cn/Article/details/gtydokfkju.html

[S16] C：位操作置位
来源：http://dali.yvedp.cn/Article/details/gtaefwhrzn.html

x |= (1 << 3);
来源：http://dali.yj202588.top/Article/details/gtnlbriafp.html

[S17] C：安全拼接字符串
来源：http://dali.yangfankeji.com/Article/details/gtgsvfavgs.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.yvedp.cn/Article/details/gtibrvbfgi.html

[S18] C：命令行参数
来源：http://dali.daxiang520.top/Article/details/gtrxymetsd.html

int main(int argc, char **argv)
来源：http://dali.jinghuilouyu.cn/Article/details/gtlkrjnmmt.html

[S19] C：快速排序
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkeyhmobh.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.feifeiyinyue.top/Article/details/gtrdvpttzv.html

[S20] C：二分查找
来源：http://dali.cqqwz.cn/Article/details/gtocdevscy.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.daxiang520.top/Article/details/gtmdutlrgf.html

[S21] C：字符类别判断
来源：http://dali.cqqwz.cn/Article/details/gtwsimruso.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtslgdgumt.html

[S22] C：字符串转数字
来源：http://dali.pycfn.com/Article/details/gtfwybnncj.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.daxiang520.top/Article/details/gtrgnmzxhj.html

[S23] C：随机数
来源：http://dali.hysaishi.cn/Article/details/gtlrtqifje.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.svipenyu.cn/Article/details/gtrsubvupe.html

[S24] C：获取本地时间
来源：http://dali.cashguo.top/Article/details/gtlyeyavbe.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.andypj.xyz/Article/details/gtdahzskfk.html

[S25] C：内存拷贝
来源：http://dali.xziqi.cn/Article/details/gtnkiagfrl.html

memcpy(dst, src, n);
来源：http://dali.hysaishi.cn/Article/details/gtzzzavuiw.html

[S26] C：内存清零
来源：http://dali.yj202588.top/Article/details/gthmoaxtda.html

memset(a, 0, sizeof a);
来源：http://dali.xylfe.cn/Article/details/gtwbevcbmq.html

[S27] C：定义常量
来源：http://dali.jinqigufen.top/Article/details/gtocbzrcme.html

const double PI = 3.14159;
来源：http://dali.gotoacloud.top/Article/details/gtropqketq.html

[S28] C：静态变量
来源：http://dali.hysaishi.cn/Article/details/gtjagewlbg.html

static int counter = 0;
来源：http://dali.meibo888.top/Article/details/gtegurxrgu.html

[S29] C：变参函数
来源：http://dali.daria6918.cn/Article/details/gtmaouqjuj.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.gaohongyu789.top/Article/details/gtxbpoebbs.html

[S30] C：头文件保护
来源：http://dali.dashuyun.cn/Article/details/gtvdvcmdzg.html

#ifndef X_H
来源：http://dali.daria6918.cn/Article/details/gtwngdfgcw.html

#define X_H
来源：http://dali.shanyushiyangtech.top/Article/details/gtjtbgdeig.html

#endif
来源：http://dali.xuanzx.com/Article/details/gtahpuncoy.html

[S31] C++：Hello World
来源：http://dali.yj20258888.top/Article/details/gtkanxdijl.html

#include <iostream>
来源：http://dali.jqgfzy.top/Article/details/gthjqobrwp.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.9152youxi.cn/Article/details/gtbjvndofg.html

[S32] C++：字符串
来源：http://dali.cheryme.top/Article/details/gtcyihlikh.html

std::string s = "hi";  s += "!";
来源：http://dali.shanyushiyangtech.top/Article/details/gtmhizrqof.html

[S33] C++：vector 增删
来源：http://dali.jqgufenzy.top/Article/details/gtuvyielms.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.yangfankeji.com/Article/details/gtxswiykek.html

[S34] C++：遍历 vector
来源：http://dali.zycfv.cn/Article/details/gtvtpmiuyd.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.hongshengwenyu.top/Article/details/gtrcdasxwo.html

[S35] C++：map
来源：http://dali.quarkkingdee.top/Article/details/gtydsldzcb.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.sysykeji.top/Article/details/gtshxoloaj.html

[S36] C++：unordered_map
来源：http://dali.c1oappe.top/Article/details/gttiaecypo.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.ybcxt.top/Article/details/gtcvviymhq.html

[S37] C++：set
来源：http://dali.zhoulong.xyz/Article/details/gtoednsgbd.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.pycfn.com/Article/details/gtbuvdjiac.html

[S38] C++：排序
来源：http://dali.yonumen.top/Article/details/gtkmgxenfq.html

std::sort(v.begin(), v.end());
来源：http://dali.havefunace.top/Article/details/gtkrccaewz.html

[S39] C++：自定义比较器排序
来源：http://dali.kuanghao11.cn/Article/details/gtlwpvnrxc.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.0kj1m.cn/Article/details/gtostdqrrd.html

[S40] C++：查找元素
来源：http://dali.cucudq.cn/Article/details/gtyxvdaldh.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.redwolf501.top/Article/details/gtdgtlzvbu.html

[S41] C++：类与构造函数
来源：http://dali.dianchejie.cn/Article/details/gtntceipdt.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.chenjidiqi.icu/Article/details/gtlhaetmro.html

[S42] C++：继承与虚函数
来源：http://dali.jinqigfzy.top/Article/details/gtjbdkwclc.html

class B : public Base { public: void f() override {} };
来源：http://dali.daxiang520.top/Article/details/gthzqfullk.html

[S43] C++：智能指针
来源：http://dali.wangshuangyany.cn/Article/details/gthpjulozk.html

auto p = std::make_unique<int>(5);
来源：http://dali.ivvv.top/Article/details/gtqgzizdbg.html

[S44] C++：引用传参
来源：http://dali.feifeiyinyue.top/Article/details/gtrdxspthy.html

void inc(int &x) { ++x; }
来源：http://dali.9152youxi.cn/Article/details/gtephhmvon.html

[S45] C++：lambda
来源：http://dali.tian-w.cn/Article/details/gtwjmelxmu.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.chenzaomai.com/Article/details/gtmmiccqhe.html

[S46] C++：函数模板
来源：http://dali.zhengqikj.top/Article/details/gtxbaqdzya.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhiwuduotai.top/Article/details/gtlhvqugxl.html

[S47] C++：结构化绑定遍历
来源：http://dali.snrcjt.cn/Article/details/gtnktvnvyy.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.chenzaomai.com/Article/details/gtkvtndubf.html

[S48] C++：逐行读文件
来源：http://dali.tian-w.cn/Article/details/gtctvbjavg.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.316326.xyz/Article/details/gtgwxhujfj.html

while (std::getline(in, line)) { }
来源：http://dali.cashguo.top/Article/details/gtlzkfvyxo.html

[S49] C++：写文件
来源：http://dali.sxryk.cn/Article/details/gtqonsyjkj.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.vqdsnc.cn/Article/details/gtrfyiyeis.html

[S50] C++：格式化数字
来源：http://dali.vqdsnc.cn/Article/details/gtfrjsfham.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.guowangkeji.top/Article/details/gttjjpwvmj.html

[S51] C++：显式类型转换
来源：http://dali.ydzc1.top/Article/details/gteusptixn.html

static_cast<double>(a) / b
来源：http://dali.shuidangran.top/Article/details/gtvausppcc.html

[S52] C++：const 与 noexcept
来源：http://dali.yj20258.top/Article/details/gthnemrcth.html

int size() const noexcept { return n_; }
来源：http://dali.hywenlv.cn/Article/details/gtkuxaiazl.html

[S53] C++：移动语义
来源：http://dali.daxiang520.top/Article/details/gtgukonauy.html

std::vector<int> w = std::move(v);
来源：http://dali.nwbrower.top/Article/details/gthtekfzgg.html

[S54] C++：异常处理
来源：http://dali.snrcjt.cn/Article/details/gtooudmddk.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.birdmap.top/Article/details/gtjsvialpr.html

[S55] C++：结构化绑定
来源：http://dali.yvedp.cn/Article/details/gtxydlpxir.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.hnxiangtu.top/Article/details/gtbcpmnjwl.html

[S56] C++：optional
来源：http://dali.gaohongyu789.top/Article/details/gtsglkbina.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.kuanghao11.cn/Article/details/gtflthqqey.html

[S57] C++：编译期常量
来源：http://dali.snrcjt.cn/Article/details/gtimovpjsk.html

constexpr int N = 10;
来源：http://dali.feifeiyinyue.top/Article/details/gtwbadlvxm.html

[S58] C++：命名空间
来源：http://dali.yj20258888.top/Article/details/gtvemnxhpi.html

namespace ns { int f() { return 1; } }
来源：http://dali.havefunace.top/Article/details/gtgglvuqvt.html

[S59] C++：静态断言
来源：http://dali.jqgufenzy.top/Article/details/gtwkumsxnm.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.birdmap.top/Article/details/gtjudyovgg.html

[S60] C++：遍历并删除元素
来源：http://dali.shzxlz.cn/Article/details/gtmpscblso.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.daxiang520.top/Article/details/gtpjumchcq.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtmrliinbu.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.gaohongyu789.top/Article/details/gtziqhlayo.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtsjknutid.html

[T01] Kotlin：Hello World
来源：http://dali.dianchejie.cn/Article/details/gtxoqkymfn.html

println("Hello")
来源：http://dali.hammf.cn/Article/details/gtqnuurbak.html

[T02] Kotlin：变量
来源：http://dali.xuetiantiany.cn/Article/details/gtwpdtjtty.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.cucudq.cn/Article/details/gtjtmmdqjx.html

[T03] Kotlin：字符串模板
来源：http://dali.hongshengwenyu.top/Article/details/gtwpvfugik.html

"值: $b"
来源：http://dali.shanyushiyangtech.top/Article/details/gtqzqhwlds.html

[T04] Kotlin：空安全
来源：http://dali.zhiwuduotai.top/Article/details/gtnqciufrb.html

val n: String? = null;  n?.length
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwdbhoddt.html

[T05] Kotlin：when 表达式
来源：http://dali.9152youxi.cn/Article/details/gtwdnqtgcj.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.wangshuangyany.cn/Article/details/gtdpllzwvq.html

[T06] Kotlin：集合映射
来源：http://dali.jinghuilouyu.cn/Article/details/gtehqlnnjs.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.quarkkingdee.top/Article/details/gtmcntzvbw.html

[T07] Kotlin：集合过滤
来源：http://dali.ehwqpu.com/Article/details/gtgrzbduic.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.yongpay.top/Article/details/gtgxrxcxlo.html

[T08] Kotlin：数据类
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtprrbdwhv.html

data class User(val name: String, val age: Int)
来源：http://dali.jqgufenzy.top/Article/details/gtrtctgodc.html

[T09] Kotlin：扩展函数
来源：http://dali.yanxiufei.cn/Article/details/gtbfxnjogf.html

fun String.exclaim() = this + "!"
来源：http://dali.yanxiufei.cn/Article/details/gtufueinbx.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gtmbrktewn.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.316326.xyz/Article/details/gtgcexrorl.html

[T11] Kotlin：协程
来源：http://dali.meibo888.top/Article/details/gtnbinzwth.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.jlsjyb.cn/Article/details/gtqunlapdc.html

[T12] Kotlin：解构声明
来源：http://dali.ydzc1.top/Article/details/gttkwrtyov.html

val (a, b) = Pair(1, 2)
来源：http://dali.aizwys.cn/Article/details/gtdiidepor.html

[T13] Kotlin：只读 Map
来源：http://dali.cqqwz.cn/Article/details/gtzdnhxbql.html

val m = mapOf("a" to 1)
来源：http://dali.hnqzz.top/Article/details/gtoitinzwu.html

[T14] Kotlin：循环
来源：http://dali.aizwys.cn/Article/details/gtcwahngga.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gtyibjppun.html

[T15] Kotlin：接口
来源：http://dali.yj20258888.top/Article/details/gtwzbbbfpo.html

interface Shape { fun area(): Double }
来源：http://dali.jqgufenzy.top/Article/details/gtgpbzdkkl.html

[T16] Swift：Hello World
来源：http://dali.shanyushiyangtech.top/Article/details/gtknepwpqz.html

print("Hello")
来源：http://dali.yj20258888.top/Article/details/gtpligswey.html

[T17] Swift：变量与常量
来源：http://dali.ppjwa.cn/Article/details/gtcdhirpze.html

var a = 1;  let b = 2
来源：http://dali.jlsjyb.cn/Article/details/gtadlhdkhc.html

[T18] Swift：字符串插值
来源：http://dali.hammf.cn/Article/details/gtkwwuncoe.html

"值: \(b)"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkqqfmtup.html

[T19] Swift：可选绑定
来源：http://dali.snrcjt.cn/Article/details/gtlnyogoij.html

if let n = opt { print(n) }
来源：http://dali.aibaodan.cn/Article/details/gtulmmnnxr.html

[T20] Swift：数组操作
来源：http://dali.redwolf501.top/Article/details/gtakewganq.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.ydzc1.top/Article/details/gthjizkfum.html

[T21] Swift：遍历
来源：http://dali.yueranfly.top/Article/details/gtiqcdwmfn.html

for x in a { print(x) }
来源：http://dali.tanke756.top/Article/details/gtarbcpjtn.html

[T22] Swift：字典
来源：http://dali.xziqi.cn/Article/details/gteucspgra.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.jinghuilouyu.cn/Article/details/gthcxusyxd.html

[T23] Swift：函数
来源：http://dali.hnxiangtu.top/Article/details/gteiosmetj.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.xinyue.icu/Article/details/gtdtqrzmio.html

[T24] Swift：闭包
来源：http://dali.aizwys.cn/Article/details/gtkhbyxtlc.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.yongpay.top/Article/details/gtxjuozise.html

[T25] Swift：结构体
来源：http://dali.sweek.top/Article/details/gtidettgyk.html

struct P { var x: Int }
来源：http://dali.redwolf501.top/Article/details/gtaabjktfm.html

[T26] Swift：类与重写
来源：http://dali.zhixingplan.top/Article/details/gtnbwdvrna.html

class A: Base { override func f() {} }
来源：http://dali.hammf.cn/Article/details/gtckhazzbt.html

[T27] Swift：错误处理
来源：http://dali.shanyushiyangtech.top/Article/details/gtlaqaagqa.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gthldetnfr.html

[T28] Swift：枚举
来源：http://dali.mhx1999.top/Article/details/gtwxoxzxsc.html

enum Color { case red, green }
来源：http://dali.yj202588.top/Article/details/gtakucqaks.html

[T29] Swift：guard 提前返回
来源：http://dali.tianlin.xyz/Article/details/gtqfejqkdr.html

guard let x = opt else { return }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtetzatyky.html

[T30] Swift：协议
来源：http://dali.chenjidiqi.icu/Article/details/gtjaagofra.html

protocol Shape { func area() -> Double }
来源：http://dali.jianghu66.top/Article/details/gtmwnxmapj.html

[T31] Lua：Hello World
来源：http://dali.zhengqikj.top/Article/details/gtzrrzbash.html

print("Hello")
来源：http://dali.shzxlz.cn/Article/details/gtdypvrwaf.html

[T32] Lua：局部变量
来源：http://dali.mhx1999.top/Article/details/gtzsqqzkrg.html

local a = 1
来源：http://dali.zdqjudy.top/Article/details/gtttszaamg.html

[T33] Lua：表（数组）
来源：http://dali.gotoacloud.top/Article/details/gtnmlmoqvy.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.yj202588.top/Article/details/gtssssicco.html

[T34] Lua：遍历表
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzbofjbnv.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.jlsjyb.cn/Article/details/gtzkvgdamo.html

[T35] Lua：字典表
来源：http://dali.sufxvd.cn/Article/details/gtrdldjlpt.html

local d = { a = 1 };  d.b = 2
来源：http://dali.kuanghao11.cn/Article/details/gtdtlkujpu.html

[T36] Lua：函数
来源：http://dali.ehwqpu.com/Article/details/gtdobtxbit.html

function add(a, b) return a + b end
来源：http://dali.chenzaomai.com/Article/details/gtrwrsssvd.html

[T37] Lua：字符串拼接
来源：http://dali.nwbrower.top/Article/details/gtgwzpqymp.html

"a" .. "b"
来源：http://dali.jiagoushi.top/Article/details/gtfatoelph.html

[T38] Lua：条件
来源：http://dali.zdqjudy.top/Article/details/gtbcxskroa.html

if x > 0 then print("正") end
来源：http://dali.ehwqpu.com/Article/details/gtegqbikgp.html

[T39] Lua：模式匹配
来源：http://dali.ppjwa.cn/Article/details/gtyajdujxt.html

string.find(s, "%d+")
来源：http://dali.yuxming.cn/Article/details/gtcdpdyfhe.html

[T40] Lua：元表
来源：http://dali.nanxinkj.top/Article/details/gtcztijznp.html

setmetatable({}, { __index = base })
来源：http://dali.zycfv.cn/Article/details/gtjymlnatn.html

[T41] Perl：Hello World
来源：http://dali.iojbl.cn/Article/details/gtskhuglfm.html

print "Hello\n";
来源：http://dali.wangdashe.top/Article/details/gtaazwkits.html

[T42] Perl：变量类型
来源：http://dali.sxryk.cn/Article/details/gtqujbehxl.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsygnvivg.html

[T43] Perl：字符串插值
来源：http://dali.tianlin.xyz/Article/details/gtnvsurppa.html

"值: $a"
来源：http://dali.ybcxt.top/Article/details/gtojzrycid.html

[T44] Perl：条件
来源：http://dali.jianghu66.top/Article/details/gtzcbmfpmx.html

if ($a > 0) { print "正"; }
来源：http://dali.havefunace.top/Article/details/gttxhsmzjk.html

[T45] Perl：数组遍历
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuvodebgn.html

for my $x (@arr) { print $x; }
来源：http://dali.hfpthk.cn/Article/details/gtrudpjfxq.html

[T46] Perl：哈希操作
来源：http://dali.jyoumei.cn/Article/details/gtpbdutqad.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.cdnleiting.top/Article/details/gtszzpjucr.html

[T47] Perl：正则捕获
来源：http://dali.hnxiangtu.top/Article/details/gtnoubuxjp.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhongyouzk.top/Article/details/gtlxqshhan.html

[T48] Perl：正则替换
来源：http://dali.gogol.net.cn/Article/details/gtyhajrcge.html

$s =~ s/old/new/g;
来源：http://dali.kuanghao11.cn/Article/details/gtuiqnsddr.html

[T49] Perl：函数
来源：http://dali.ivvv.top/Article/details/gtskqvsfrb.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.pycfn.com/Article/details/gtirroiwlf.html

[T50] Perl：逐行读文件
来源：http://dali.nanxuanxn.top/Article/details/gtswnpahfd.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.cashguo.top/Article/details/gtnbmfyyyl.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.feifeiyinyue.top/Article/details/gtixzhcrdd.html

[T51] Scala：Hello World
来源：http://dali.tianlin.xyz/Article/details/gtmamuqkcv.html

println("Hello")
来源：http://dali.guowangkeji.top/Article/details/gtetxzbqhb.html

[T52] Scala：变量
来源：http://dali.yj20258.top/Article/details/gtfbjaretl.html

val a = 1;  var b = 2
来源：http://dali.yanxiufei.cn/Article/details/gtjoyehbhv.html

[T53] Scala：字符串插值
来源：http://dali.zhongyouzk.top/Article/details/gtcztiirqk.html

s"值: $b"
来源：http://dali.meibo888.top/Article/details/gtpvnhkqea.html

[T54] Scala：集合映射
来源：http://dali.yanxiufei.cn/Article/details/gtugelbdmu.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.tian-w.cn/Article/details/gtdeshyhez.html

[T55] Scala：集合过滤
来源：http://dali.zhixingplan.top/Article/details/gtiakiatiy.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.shuidangran.top/Article/details/gthbrphdtu.html

[T56] Scala：样例类
来源：http://dali.smart0.xyz/Article/details/gtcokjdptq.html

case class User(name: String, age: Int)
来源：http://dali.zhiwuduotai.top/Article/details/gtjciakdfl.html

[T57] Scala：模式匹配
来源：http://dali.yuanzhike.top/Article/details/gtpjppvnlp.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.yanxiufei.cn/Article/details/gtxuvjrvof.html

[T58] Scala：函数定义
来源：http://dali.gzhubu.top/Article/details/gtzrgnegbg.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.yj20258888.top/Article/details/gtwxerapcj.html

[T59] Scala：循环
来源：http://dali.ppjwa.cn/Article/details/gtbjpauaah.html

for (i <- 1 to 10) println(i)
来源：http://dali.jianghu66.top/Article/details/gteioujcuw.html

[T60] Scala：折叠
来源：http://dali.jyoumei.cn/Article/details/gtwtttydxt.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.fzhhl.top/Article/details/gtdxpslmng.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtizozxjzz.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.ybcxt.top/Article/details/gteelqupii.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtrarxnnoz.html

[U01] Py：创建虚拟环境
来源：http://dali.zhixingplan.top/Article/details/gtusxivkby.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.xziqi.cn/Article/details/gtoptffiqj.html

[U02] Py：导出 / 安装依赖
来源：http://dali.nwbrower.top/Article/details/gtgriisjbb.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.vqdsnc.cn/Article/details/gtmowtthfy.html


<!-- 参考信息 -->