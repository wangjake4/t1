代发 wailian999

df -h;  du -sh *
来源：http://dali.dianchejie.cn/Article/details/gtuvwxdyyn.html

[R62] 找最占空间的文件
来源：http://dali.fengsongda.top/Article/details/gtwyhkffki.html

du -ah . | sort -rh | head -10
来源：http://dali.gotoacloud.top/Article/details/gtsekyguoc.html

[R63] 内存与进程
来源：http://dali.cdnleiting.top/Article/details/gtcupalxai.html

free -h;  ps aux | grep nginx
来源：http://dali.yj202588.top/Article/details/gtckovyewg.html

[R64] 结束进程
来源：http://dali.ppjwa.cn/Article/details/gtpqgoldar.html

kill -9 $(pgrep -f app.py)
来源：http://dali.svipenyu.cn/Article/details/gtoizybqbr.html

[R65] 查看端口占用
来源：http://dali.chenlongwang.top/Article/details/gthlsbqkzl.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.wangshuangyany.cn/Article/details/gteiyibtfd.html

[R66] 定时任务
来源：http://dali.guowangkeji.top/Article/details/gtotrdylbv.html

crontab -e;  crontab -l
来源：http://dali.aibaodan.cn/Article/details/gtlsuzyhoh.html

[R67] 生成随机十六进制串
来源：http://dali.meibo888.top/Article/details/gtbwigyrhs.html

openssl rand -hex 16
来源：http://dali.jiagoushi.top/Article/details/gtoiselecc.html

[R68] 计算文件校验值
来源：http://dali.feifeiyinyue.top/Article/details/gtiusvmygz.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhaomingkeji.xyz/Article/details/gthscebmgk.html

[R69] 生成随机密码
来源：http://dali.cdnleiting.top/Article/details/gtuqcbstpi.html

head -c 16 /dev/urandom | base64
来源：http://dali.snrcjt.cn/Article/details/gtcqxpqcig.html

[R70] 时间戳与互转
来源：http://dali.sxryk.cn/Article/details/gtiivhnisv.html

date +%s;  date -d @1700000000
来源：http://dali.jqgfzy.top/Article/details/gtekhvwbmh.html

[R71] 日期格式化
来源：http://dali.jqgufenzy.top/Article/details/gthljqpeeq.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.yj20258888.top/Article/details/gtfztuojfc.html

[R72] 等待端口就绪
来源：http://dali.dashuyun.cn/Article/details/gtbzswwgvz.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.yueranfly.top/Article/details/gttrlqvkut.html

[R73] 分割大日志
来源：http://dali.jlsjyb.cn/Article/details/gtjrqqrmly.html

split -l 1000 big.log part_
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjikqlleh.html

[R74] 批量重命名
来源：http://dali.hongshengwenyu.top/Article/details/gtasmixzoa.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.ehwqpu.com/Article/details/gtdmvvzybu.html

[R75] 导出环境变量
来源：http://dali.tian-w.cn/Article/details/gtatchvrkw.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.tianlin.xyz/Article/details/gtyzaoeqko.html

[R76] 使用临时文件
来源：http://dali.yuanzhike.top/Article/details/gtzmqurrmj.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.9152youxi.cn/Article/details/gtylzmcnih.html

[R77] 读取用户输入
来源：http://dali.dianchejie.cn/Article/details/gtbseovofj.html

read -rp "请输入: " ans
来源：http://dali.yangfankeji.com/Article/details/gtyjgrrduf.html

[R78] 交互式菜单
来源：http://dali.jiagoushi.top/Article/details/gtwkdqnqrk.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.yonumen.top/Article/details/gtmezywdtb.html

[R79] 解析命令行选项
来源：http://dali.hfpthk.cn/Article/details/gtrkkkvkpd.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.nanxuanxn.top/Article/details/gtkbrlbrpd.html

[R80] 查看脚本执行耗时
来源：http://dali.sweek.top/Article/details/gtxrctzhpm.html

time ./run.sh
来源：http://dali.yj20258888.top/Article/details/gtbttcayiy.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtwgcfczwc.html

S. C / C++ 专题
来源：http://dali.pycfn.com/Article/details/gtoessghrx.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtjtbsyohl.html

[S01] C：Hello World
来源：http://dali.jinqigfzy.top/Article/details/gtrtspngsz.html

#include <stdio.h>
来源：http://dali.cheryme.top/Article/details/gtfgonzlan.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.chenzaomai.com/Article/details/gtzwsccxnh.html

[S02] C：变量与格式化输出
来源：http://dali.chenjidiqi.icu/Article/details/gtoiazwejt.html

int a = 10; printf("%d\n", a);
来源：http://dali.yvedp.cn/Article/details/gtirikshqx.html

[S03] C：读入整数
来源：http://dali.andypj.xyz/Article/details/gtlusllczl.html

int x; scanf("%d", &x);
来源：http://dali.bjfxy.top/Article/details/gtjontbtod.html

[S04] C：字符串复制
来源：http://dali.ybcxt.top/Article/details/gtvlpyhgiq.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.nanxuanxn.top/Article/details/gtjhdhrahk.html

[S05] C：字符串长度
来源：http://dali.sufxvd.cn/Article/details/gthonbtuln.html

strlen(s)
来源：http://dali.yangfankeji.com/Article/details/gtzcwlvels.html

[S06] C：字符串比较
来源：http://dali.yongpay.top/Article/details/gtfygkhkgn.html

strcmp(a, b) == 0
来源：http://dali.yj20258.top/Article/details/gtcumlogrp.html

[S07] C：数组遍历求和
来源：http://dali.xziqi.cn/Article/details/gtzvogiodf.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.xuanzx.com/Article/details/gtnwysdcrn.html

[S08] C：动态内存分配与释放
来源：http://dali.chenlongwang.top/Article/details/gtoutphrps.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.jianghu66.top/Article/details/gtubcrorww.html

[S09] C：结构体定义与初始化
来源：http://dali.snrcjt.cn/Article/details/gtavzhotca.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zdqjudy.top/Article/details/gtjglpwfta.html

[S10] C：指针与解引用
来源：http://dali.pengpengdd.cyou/Article/details/gtsgmxbndf.html

int *p = &a;  *p = 5;
来源：http://dali.hfpthk.cn/Article/details/gtpsbpfxyx.html

[S11] C：逐行读文件
来源：http://dali.meibo888.top/Article/details/gtlcdxiwpv.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.mhx1999.top/Article/details/gtfvjfseag.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.shuidangran.top/Article/details/gtljqpzkdh.html

fclose(f);
来源：http://dali.ybcxt.top/Article/details/gtsmzbfxmh.html

[S12] C：写文件
来源：http://dali.ehwqpu.com/Article/details/gtjlqlergk.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.fengsongda.top/Article/details/gtesxcpvyh.html

[S13] C：宏定义
来源：http://dali.zhiwuduotai.top/Article/details/gtujqicicn.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gtxrbuvyja.html

[S14] C：枚举
来源：http://dali.yuxming.cn/Article/details/gtttqksnnz.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.yueranfly.top/Article/details/gtcwyqkyzb.html

[S15] C：类型转换
来源：http://dali.gotoacloud.top/Article/details/gtutbpfffv.html

(double) a / b
来源：http://dali.316326.xyz/Article/details/gtybcoylpn.html

[S16] C：位操作置位
来源：http://dali.jinyuanbaomall.cn/Article/details/gturhlvkeq.html

x |= (1 << 3);
来源：http://dali.ybcxt.top/Article/details/gtnszujfyl.html

[S17] C：安全拼接字符串
来源：http://dali.yangfankeji.com/Article/details/gtrdxzkgbt.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.iojbl.cn/Article/details/gtiwonubcj.html

[S18] C：命令行参数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcxzwgzvm.html

int main(int argc, char **argv)
来源：http://dali.gaohongyu789.top/Article/details/gtdhrlejyv.html

[S19] C：快速排序
来源：http://dali.nanxinkj.top/Article/details/gtozpaudcj.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.ehwqpu.com/Article/details/gtvcehfvpj.html

[S20] C：二分查找
来源：http://dali.ppjwa.cn/Article/details/gtnemhtqmn.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.bjfxy.top/Article/details/gtmsjsmfzr.html

[S21] C：字符类别判断
来源：http://dali.cqqwz.cn/Article/details/gtmwmfcosy.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.yuxming.cn/Article/details/gtwghlfftc.html

[S22] C：字符串转数字
来源：http://dali.pengpengdd.cyou/Article/details/gtfvrxraxz.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.fengsongda.top/Article/details/gtldcmdzqg.html

[S23] C：随机数
来源：http://dali.xziqi.cn/Article/details/gtpusdsnhh.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.ybcxt.top/Article/details/gttiivmbwr.html

[S24] C：获取本地时间
来源：http://dali.xinyue.icu/Article/details/gtjbroewsu.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.smart0.xyz/Article/details/gtncwyapkg.html

[S25] C：内存拷贝
来源：http://dali.cucudq.cn/Article/details/gtlulucpyo.html

memcpy(dst, src, n);
来源：http://dali.c1oappe.top/Article/details/gtijdnblov.html

[S26] C：内存清零
来源：http://dali.shanyushiyangtech.top/Article/details/gtmqvqtfly.html

memset(a, 0, sizeof a);
来源：http://dali.smart0.xyz/Article/details/gtydcscnpl.html

[S27] C：定义常量
来源：http://dali.mhx1999.top/Article/details/gtbwdyfpbu.html

const double PI = 3.14159;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvrtecuca.html

[S28] C：静态变量
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpmxevygv.html

static int counter = 0;
来源：http://dali.kuanghao11.cn/Article/details/gtfphtpbef.html

[S29] C：变参函数
来源：http://dali.hnqzz.top/Article/details/gtcpdomycs.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.tian-w.cn/Article/details/gtlexfabyn.html

[S30] C：头文件保护
来源：http://dali.ybcxt.top/Article/details/gtbdwjvgvg.html

#ifndef X_H
来源：http://dali.hnxiangtu.top/Article/details/gtyimlgabn.html

#define X_H
来源：http://dali.xylfe.cn/Article/details/gtlgasptte.html

#endif
来源：http://dali.zhoulong.xyz/Article/details/gtommtjhhj.html

[S31] C++：Hello World
来源：http://dali.havefunace.top/Article/details/gtmzbgowzs.html

#include <iostream>
来源：http://dali.sysykeji.top/Article/details/gtlgqfchkg.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.ivvv.top/Article/details/gtjfiyvvee.html

[S32] C++：字符串
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlljgmlqf.html

std::string s = "hi";  s += "!";
来源：http://dali.ywan-chungtsiang.top/Article/details/gtndqwaaes.html

[S33] C++：vector 增删
来源：http://dali.hfpthk.cn/Article/details/gtdtixjhvr.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.cheryme.top/Article/details/gtfyjksqvo.html

[S34] C++：遍历 vector
来源：http://dali.yj202588.top/Article/details/gtdbklraqq.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.hnxiangtu.top/Article/details/gtqalqwuxn.html

[S35] C++：map
来源：http://dali.aizwys.cn/Article/details/gtzktkyzue.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.redwolf501.top/Article/details/gtgnpaoibm.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gttzcgehzh.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.ehwqpu.com/Article/details/gthryekjtt.html

[S37] C++：set
来源：http://dali.mhx1999.top/Article/details/gtfzxzylur.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gtssvxtzxm.html

[S38] C++：排序
来源：http://dali.tianlin.xyz/Article/details/gtoueiqbpn.html

std::sort(v.begin(), v.end());
来源：http://dali.hnqzz.top/Article/details/gtxagfjiuk.html

[S39] C++：自定义比较器排序
来源：http://dali.hywenlv.cn/Article/details/gtnimlsviq.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.aibaodan.cn/Article/details/gtfxwdsrbp.html

[S40] C++：查找元素
来源：http://dali.cqqwz.cn/Article/details/gtpbpvfmaw.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.guannengcc.top/Article/details/gttdnhqigz.html

[S41] C++：类与构造函数
来源：http://dali.hnqzz.top/Article/details/gtakliiamn.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.tian-w.cn/Article/details/gtswksevce.html

[S42] C++：继承与虚函数
来源：http://dali.jinghuilouyu.cn/Article/details/gtkomrchgo.html

class B : public Base { public: void f() override {} };
来源：http://dali.nanxuanxn.top/Article/details/gtymenyxvl.html

[S43] C++：智能指针
来源：http://dali.jqgufenzy.top/Article/details/gtlqkyokci.html

auto p = std::make_unique<int>(5);
来源：http://dali.aizwys.cn/Article/details/gtxkhexqcd.html

[S44] C++：引用传参
来源：http://dali.chenzaomai.com/Article/details/gtpganabbl.html

void inc(int &x) { ++x; }
来源：http://dali.dashuyun.cn/Article/details/gtfnwovcrr.html

[S45] C++：lambda
来源：http://dali.yangfankeji.com/Article/details/gtszftihyj.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.dashuyun.cn/Article/details/gttuosatgw.html

[S46] C++：函数模板
来源：http://dali.aizwys.cn/Article/details/gtzpviootk.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.hongshengwenyu.top/Article/details/gtlcpcgnay.html

[S47] C++：结构化绑定遍历
来源：http://dali.svipenyu.cn/Article/details/gtpupfcgap.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.tianlin.xyz/Article/details/gthleczgir.html

[S48] C++：逐行读文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtizmjjrog.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.cdnleiting.top/Article/details/gtjslueied.html

while (std::getline(in, line)) { }
来源：http://dali.daria6918.cn/Article/details/gtgvcuolhi.html

[S49] C++：写文件
来源：http://dali.c1oappe.top/Article/details/gtengmrmfx.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.tian-w.cn/Article/details/gtsbrbsbzt.html

[S50] C++：格式化数字
来源：http://dali.yangfankeji.com/Article/details/gtqigvmtiz.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.yuanzhike.top/Article/details/gtqtmsaecc.html

[S51] C++：显式类型转换
来源：http://dali.wangdashe.top/Article/details/gtfeldxbaf.html

static_cast<double>(a) / b
来源：http://dali.zycfv.cn/Article/details/gtvxduswsc.html

[S52] C++：const 与 noexcept
来源：http://dali.sysykeji.top/Article/details/gtlvkfuqlh.html

int size() const noexcept { return n_; }
来源：http://dali.pengpengdd.cyou/Article/details/gteqjzvkhj.html

[S53] C++：移动语义
来源：http://dali.hongshengwenyu.top/Article/details/gthbhqkwcw.html

std::vector<int> w = std::move(v);
来源：http://dali.tanke756.top/Article/details/gtvavpiesl.html

[S54] C++：异常处理
来源：http://dali.andypj.xyz/Article/details/gteaweaobc.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.shzxlz.cn/Article/details/gtdizswxjy.html

[S55] C++：结构化绑定
来源：http://dali.tanke756.top/Article/details/gtknjvneul.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.0kj1m.cn/Article/details/gtzuynbxqf.html

[S56] C++：optional
来源：http://dali.xziqi.cn/Article/details/gtyhjvebza.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.xinyue.icu/Article/details/gtjurhlrhw.html

[S57] C++：编译期常量
来源：http://dali.kuanghao11.cn/Article/details/gtfqbtqrbh.html

constexpr int N = 10;
来源：http://dali.shanyushiyangtech.top/Article/details/gtjxlbobuv.html

[S58] C++：命名空间
来源：http://dali.zycfv.cn/Article/details/gtrwanynah.html

namespace ns { int f() { return 1; } }
来源：http://dali.yueranfly.top/Article/details/gttsyvqfkv.html

[S59] C++：静态断言
来源：http://dali.316326.xyz/Article/details/gtmlvcjxrd.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtijhkxsur.html

[S60] C++：遍历并删除元素
来源：http://dali.ppjwa.cn/Article/details/gtavldiwnd.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlsirtggk.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtbngjnydv.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.0kj1m.cn/Article/details/gttniexbhj.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtgguzehhr.html

[T01] Kotlin：Hello World
来源：http://dali.redwolf501.top/Article/details/gtfgagthev.html

println("Hello")
来源：http://dali.smart0.xyz/Article/details/gtnlqmokck.html

[T02] Kotlin：变量
来源：http://dali.ybcxt.top/Article/details/gtooxhftpu.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.yanxiufei.cn/Article/details/gtgafuzvtt.html

[T03] Kotlin：字符串模板
来源：http://dali.zhoulong.xyz/Article/details/gtcrvjimaw.html

"值: $b"
来源：http://dali.shuidangran.top/Article/details/gtfmuvqhxa.html

[T04] Kotlin：空安全
来源：http://dali.jiagoushi.top/Article/details/gtibgsrtyb.html

val n: String? = null;  n?.length
来源：http://dali.meibo888.top/Article/details/gtsgtsurll.html

[T05] Kotlin：when 表达式
来源：http://dali.yuxming.cn/Article/details/gtoqzhajrs.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.tian-w.cn/Article/details/gtqjyqacgr.html

[T06] Kotlin：集合映射
来源：http://dali.c1oappe.top/Article/details/gtgefhecgw.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.yvedp.cn/Article/details/gtlwtahkxb.html

[T07] Kotlin：集合过滤
来源：http://dali.yj202588.top/Article/details/gtvyrvzdjc.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zycfv.cn/Article/details/gthhbbstox.html

[T08] Kotlin：数据类
来源：http://dali.zhixingplan.top/Article/details/gtbriaocth.html

data class User(val name: String, val age: Int)
来源：http://dali.9152youxi.cn/Article/details/gthpwzigmn.html

[T09] Kotlin：扩展函数
来源：http://dali.cucudq.cn/Article/details/gtxfxytaqc.html

fun String.exclaim() = this + "!"
来源：http://dali.redwolf501.top/Article/details/gtfseodkfu.html

[T10] Kotlin：默认参数
来源：http://dali.zhoulong.xyz/Article/details/gtfgnaytoj.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.yj202588.top/Article/details/gtmubfvwuw.html

[T11] Kotlin：协程
来源：http://dali.zhiwuduotai.top/Article/details/gtjicqozca.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.chenlongwang.top/Article/details/gtkfkjqdui.html

[T12] Kotlin：解构声明
来源：http://dali.nanxuanxn.top/Article/details/gtetmlhlpm.html

val (a, b) = Pair(1, 2)
来源：http://dali.cashguo.top/Article/details/gtghtezqqi.html

[T13] Kotlin：只读 Map
来源：http://dali.daxiang520.top/Article/details/gtllcfhpqa.html

val m = mapOf("a" to 1)
来源：http://dali.hongshengwenyu.top/Article/details/gtdxxhfcsh.html

[T14] Kotlin：循环
来源：http://dali.havefunace.top/Article/details/gtxvxnbayo.html

for (i in 1..10) println(i)
来源：http://dali.hnxiangtu.top/Article/details/gtkuhkntuz.html

[T15] Kotlin：接口
来源：http://dali.birdmap.top/Article/details/gtztmsmnyw.html

interface Shape { fun area(): Double }
来源：http://dali.chenzaomai.com/Article/details/gtoadxskeu.html

[T16] Swift：Hello World
来源：http://dali.shuidangran.top/Article/details/gtppcteqij.html

print("Hello")
来源：http://dali.xuetiantiany.cn/Article/details/gtdtkcadqy.html

[T17] Swift：变量与常量
来源：http://dali.ybcxt.top/Article/details/gtbzqqnztf.html

var a = 1;  let b = 2
来源：http://dali.sweek.top/Article/details/gtqzkxmuvb.html

[T18] Swift：字符串插值
来源：http://dali.xylfe.cn/Article/details/gtecmtvqnp.html

"值: \(b)"
来源：http://dali.ydzc1.top/Article/details/gtbwacrizs.html

[T19] Swift：可选绑定
来源：http://dali.tian-w.cn/Article/details/gtvojbqeks.html

if let n = opt { print(n) }
来源：http://dali.sxryk.cn/Article/details/gtuhtgodbx.html

[T20] Swift：数组操作
来源：http://dali.fengsongda.top/Article/details/gtbuosiejk.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.yongpay.top/Article/details/gtjjwteebb.html

[T21] Swift：遍历
来源：http://dali.dashuyun.cn/Article/details/gtlnzjtkco.html

for x in a { print(x) }
来源：http://dali.pengpengdd.cyou/Article/details/gtjixrzcpg.html

[T22] Swift：字典
来源：http://dali.c1oappe.top/Article/details/gtrkdklewy.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.9152youxi.cn/Article/details/gtoexetqgb.html

[T23] Swift：函数
来源：http://dali.shangyingyoupin.top/Article/details/gtuwkwfqff.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.xziqi.cn/Article/details/gtcfedzdhi.html

[T24] Swift：闭包
来源：http://dali.jinqigfzy.top/Article/details/gtzlrtbdms.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.jinqigufen.top/Article/details/gtrdpqxubc.html

[T25] Swift：结构体
来源：http://dali.xylfe.cn/Article/details/gtobeqkrzr.html

struct P { var x: Int }
来源：http://dali.andypj.xyz/Article/details/gtvktxdkax.html

[T26] Swift：类与重写
来源：http://dali.chenjidiqi.icu/Article/details/gtsdwolyhm.html

class A: Base { override func f() {} }
来源：http://dali.chenjidiqi.icu/Article/details/gtqkyaqgpe.html

[T27] Swift：错误处理
来源：http://dali.redwolf501.top/Article/details/gtnnifxfur.html

do { try f() } catch { print(error) }
来源：http://dali.sweek.top/Article/details/gtfgutuqys.html

[T28] Swift：枚举
来源：http://dali.vqdsnc.cn/Article/details/gthgnirwky.html

enum Color { case red, green }
来源：http://dali.yongpay.top/Article/details/gtpwgikgpd.html

[T29] Swift：guard 提前返回
来源：http://dali.dashuyun.cn/Article/details/gtzrengbde.html

guard let x = opt else { return }
来源：http://dali.chenlongwang.top/Article/details/gtaicodimo.html

[T30] Swift：协议
来源：http://dali.wangdashe.top/Article/details/gtbnoloblc.html

protocol Shape { func area() -> Double }
来源：http://dali.jqgufenzy.top/Article/details/gtvxxujlxa.html

[T31] Lua：Hello World
来源：http://dali.dianchejie.cn/Article/details/gtbmooslsp.html

print("Hello")
来源：http://dali.zhoulong.xyz/Article/details/gtnljiycbg.html

[T32] Lua：局部变量
来源：http://dali.dianchejie.cn/Article/details/gtylyalqti.html

local a = 1
来源：http://dali.gogol.net.cn/Article/details/gtnjxobtii.html

[T33] Lua：表（数组）
来源：http://dali.vqdsnc.cn/Article/details/gtkuyoblbx.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.jlsjyb.cn/Article/details/gthjtrhkzd.html

[T34] Lua：遍历表
来源：http://dali.yj202588.top/Article/details/gtdacxxmis.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.yuanzhike.top/Article/details/gtcqmyhozr.html

[T35] Lua：字典表
来源：http://dali.tanke756.top/Article/details/gtxppxfkuw.html

local d = { a = 1 };  d.b = 2
来源：http://dali.shangyingyoupin.top/Article/details/gtktwdgxjm.html

[T36] Lua：函数
来源：http://dali.ehwqpu.com/Article/details/gtbfjapjqd.html

function add(a, b) return a + b end
来源：http://dali.jinghuilouyu.cn/Article/details/gtllsjlxeb.html

[T37] Lua：字符串拼接
来源：http://dali.chenzaomai.com/Article/details/gtxldlcwuv.html

"a" .. "b"
来源：http://dali.chenzaomai.com/Article/details/gtivhpvrbl.html

[T38] Lua：条件
来源：http://dali.gogol.net.cn/Article/details/gtlqcqewof.html

if x > 0 then print("正") end
来源：http://dali.hnxiangtu.top/Article/details/gtsevfozna.html

[T39] Lua：模式匹配
来源：http://dali.zhaomingkeji.xyz/Article/details/gtezvbyypj.html

string.find(s, "%d+")
来源：http://dali.birdmap.top/Article/details/gtuasmavrq.html

[T40] Lua：元表
来源：http://dali.yangfankeji.com/Article/details/gtfhireuyl.html

setmetatable({}, { __index = base })
来源：http://dali.vqdsnc.cn/Article/details/gtszymfqtk.html

[T41] Perl：Hello World
来源：http://dali.cucudq.cn/Article/details/gtpexgaxjl.html

print "Hello\n";
来源：http://dali.ydzc1.top/Article/details/gtirmkjbnp.html

[T42] Perl：变量类型
来源：http://dali.tian-w.cn/Article/details/gtzjmxvlfc.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.snrcjt.cn/Article/details/gtqnemaqzw.html

[T43] Perl：字符串插值
来源：http://dali.daxiang520.top/Article/details/gtrzxqmcdk.html

"值: $a"
来源：http://dali.yvedp.cn/Article/details/gthtlxutml.html

[T44] Perl：条件
来源：http://dali.jianghu66.top/Article/details/gtljiwtkho.html

if ($a > 0) { print "正"; }
来源：http://dali.316326.xyz/Article/details/gthciywpll.html

[T45] Perl：数组遍历
来源：http://dali.c1oappe.top/Article/details/gtlajbsupz.html

for my $x (@arr) { print $x; }
来源：http://dali.chenjidiqi.icu/Article/details/gtjwivdxmw.html

[T46] Perl：哈希操作
来源：http://dali.dashuyun.cn/Article/details/gtuomtmbis.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zycfv.cn/Article/details/gtpwclcjtc.html

[T47] Perl：正则捕获
来源：http://dali.zhixingplan.top/Article/details/gttekbizlw.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.9152youxi.cn/Article/details/gtqbadzbay.html

[T48] Perl：正则替换
来源：http://dali.ehwqpu.com/Article/details/gtqlbdhzcg.html

$s =~ s/old/new/g;
来源：http://dali.tanke756.top/Article/details/gtereraqpu.html

[T49] Perl：函数
来源：http://dali.guowangkeji.top/Article/details/gtweuchhiz.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zycfv.cn/Article/details/gtueymwyvk.html

[T50] Perl：逐行读文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfprwgtsv.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.sysykeji.top/Article/details/gtswcdjade.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhixingplan.top/Article/details/gtbnnbdnvn.html

[T51] Scala：Hello World
来源：http://dali.0kj1m.cn/Article/details/gtkchhysvj.html

println("Hello")
来源：http://dali.yj20258.top/Article/details/gtyonkhaue.html

[T52] Scala：变量
来源：http://dali.aibaodan.cn/Article/details/gtbujxqfkb.html

val a = 1;  var b = 2
来源：http://dali.dianchejie.cn/Article/details/gtlbvfmmcb.html

[T53] Scala：字符串插值
来源：http://dali.zhixingplan.top/Article/details/gtxkqeluig.html

s"值: $b"
来源：http://dali.hywenlv.cn/Article/details/gtrakbemyj.html

[T54] Scala：集合映射
来源：http://dali.yongpay.top/Article/details/gtrrnwadgr.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.shzxlz.cn/Article/details/gtgmgzswzt.html

[T55] Scala：集合过滤
来源：http://dali.cashguo.top/Article/details/gtklamjlif.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.daria6918.cn/Article/details/gtuzyctzuu.html

[T56] Scala：样例类
来源：http://dali.jqgfzy.top/Article/details/gteoqpteic.html

case class User(name: String, age: Int)
来源：http://dali.shuidangran.top/Article/details/gtykipjzki.html

[T57] Scala：模式匹配
来源：http://dali.xuanzx.com/Article/details/gtdidzvesv.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.sufxvd.cn/Article/details/gtjxicdciq.html

[T58] Scala：函数定义
来源：http://dali.yvedp.cn/Article/details/gtgobxmaxk.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.snrcjt.cn/Article/details/gtwmasorsv.html

[T59] Scala：循环
来源：http://dali.chenzaomai.com/Article/details/gtxyzyykio.html

for (i <- 1 to 10) println(i)
来源：http://dali.xuanzx.com/Article/details/gtplyqzhih.html

[T60] Scala：折叠
来源：http://dali.hammf.cn/Article/details/gtdsadlxla.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.sxryk.cn/Article/details/gtxunofbxt.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtliwknugo.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.jianghu66.top/Article/details/gtovdakoem.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtlmdwzumb.html

[U01] Py：创建虚拟环境
来源：http://dali.guannengcc.top/Article/details/gtibgpquih.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.0kj1m.cn/Article/details/gtbsccalen.html

[U02] Py：导出 / 安装依赖
来源：http://dali.pycfn.com/Article/details/gtkspfdmer.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.fzhhl.top/Article/details/gtzjxmkaib.html


<!-- 参考信息 -->