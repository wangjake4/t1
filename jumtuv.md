代发 wailian999

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhongyouzk.top/Article/details/gtdkyccapo.html

[R66] 定时任务
来源：http://dali.meibo888.top/Article/details/gtfuspyzfi.html

crontab -e;  crontab -l
来源：http://dali.316326.xyz/Article/details/gtnddrbhmz.html

[R67] 生成随机十六进制串
来源：http://dali.pycfn.com/Article/details/gtmphyqlna.html

openssl rand -hex 16
来源：http://dali.hysaishi.cn/Article/details/gtfxtwomen.html

[R68] 计算文件校验值
来源：http://dali.cucudq.cn/Article/details/gtowzetdix.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.guannengcc.top/Article/details/gtkdcmtvux.html

[R69] 生成随机密码
来源：http://dali.xuetiantiany.cn/Article/details/gtdxwvdrkd.html

head -c 16 /dev/urandom | base64
来源：http://dali.cheryme.top/Article/details/gtirkqcujq.html

[R70] 时间戳与互转
来源：http://dali.cheryme.top/Article/details/gtbenfcwbx.html

date +%s;  date -d @1700000000
来源：http://dali.jinghuilouyu.cn/Article/details/gtgchksyjh.html

[R71] 日期格式化
来源：http://dali.guannengcc.top/Article/details/gtwrxdiztt.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.yj202588.top/Article/details/gtuaijqysv.html

[R72] 等待端口就绪
来源：http://dali.sufxvd.cn/Article/details/gtgwbqmxeo.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.yongpay.top/Article/details/gtaaycogiy.html

[R73] 分割大日志
来源：http://dali.daria6918.cn/Article/details/gtlygyooaw.html

split -l 1000 big.log part_
来源：http://dali.xuetiantiany.cn/Article/details/gtgfjrvnqz.html

[R74] 批量重命名
来源：http://dali.havefunace.top/Article/details/gtvmloxmhq.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.daria6918.cn/Article/details/gtrybgwvxj.html

[R75] 导出环境变量
来源：http://dali.quarkkingdee.top/Article/details/gtoqspsman.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.yonumen.top/Article/details/gtgneqacww.html

[R76] 使用临时文件
来源：http://dali.jqgufenzy.top/Article/details/gthzmozlgj.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.gzhubu.top/Article/details/gtwdqcxnnf.html

[R77] 读取用户输入
来源：http://dali.zhoulong.xyz/Article/details/gthwtrhhmv.html

read -rp "请输入: " ans
来源：http://dali.zhongyouzk.top/Article/details/gtmwcietxg.html

[R78] 交互式菜单
来源：http://dali.iojbl.cn/Article/details/gtjrwwmgmk.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.ppjwa.cn/Article/details/gtnaxwerwv.html

[R79] 解析命令行选项
来源：http://dali.pengpengdd.cyou/Article/details/gtlqdrolou.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.ppjwa.cn/Article/details/gtdfsatpae.html

[R80] 查看脚本执行耗时
来源：http://dali.guannengcc.top/Article/details/gtojucawrs.html

time ./run.sh
来源：http://dali.xuanzx.com/Article/details/gtabydwoiy.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtteirflzx.html

S. C / C++ 专题
来源：http://dali.tian-w.cn/Article/details/gtykkzyrvd.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtsxtpqdnr.html

[S01] C：Hello World
来源：http://dali.yonumen.top/Article/details/gthdazfimo.html

#include <stdio.h>
来源：http://dali.sxryk.cn/Article/details/gttmfejwrl.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.ivvv.top/Article/details/gtaiohpnfz.html

[S02] C：变量与格式化输出
来源：http://dali.iojbl.cn/Article/details/gtlyfmjfyx.html

int a = 10; printf("%d\n", a);
来源：http://dali.cdnleiting.top/Article/details/gtzaujildv.html

[S03] C：读入整数
来源：http://dali.andypj.xyz/Article/details/gtntthyvtj.html

int x; scanf("%d", &x);
来源：http://dali.cdnleiting.top/Article/details/gtbdpcntko.html

[S04] C：字符串复制
来源：http://dali.shangyingyoupin.top/Article/details/gtyzglkain.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.yanxiufei.cn/Article/details/gtdfhkzohq.html

[S05] C：字符串长度
来源：http://dali.iojbl.cn/Article/details/gtkbsyexzz.html

strlen(s)
来源：http://dali.hnqzz.top/Article/details/gtvgginrsb.html

[S06] C：字符串比较
来源：http://dali.iojbl.cn/Article/details/gtqjsawniw.html

strcmp(a, b) == 0
来源：http://dali.gzhubu.top/Article/details/gtyhnucwvb.html

[S07] C：数组遍历求和
来源：http://dali.aizwys.cn/Article/details/gthfsygsvz.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.yongpay.top/Article/details/gtjmfbbiuu.html

[S08] C：动态内存分配与释放
来源：http://dali.ybcxt.top/Article/details/gtigojxxwb.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhiwuduotai.top/Article/details/gtiqmcibwg.html

[S09] C：结构体定义与初始化
来源：http://dali.jinghuilouyu.cn/Article/details/gthhjjorzz.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.wangdashe.top/Article/details/gtmwfeitug.html

[S10] C：指针与解引用
来源：http://dali.jqgfzy.top/Article/details/gtbbvzfycy.html

int *p = &a;  *p = 5;
来源：http://dali.jinqigfzy.top/Article/details/gtevxhbmrg.html

[S11] C：逐行读文件
来源：http://dali.ybcxt.top/Article/details/gtpycrwixy.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.jlsjyb.cn/Article/details/gtvyzpzngg.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zycfv.cn/Article/details/gtqnkkxiox.html

fclose(f);
来源：http://dali.ehwqpu.com/Article/details/gtcyhxrywz.html

[S12] C：写文件
来源：http://dali.jinqigfzy.top/Article/details/gtdqqjwvzq.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.haohaochexian.top/Article/details/gtizdiitqy.html

[S13] C：宏定义
来源：http://dali.ehwqpu.com/Article/details/gtvubxccmq.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhiwuduotai.top/Article/details/gtgwwselwp.html

[S14] C：枚举
来源：http://dali.gaohongyu789.top/Article/details/gtjvhcjrcd.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.yanxiufei.cn/Article/details/gtgafojayi.html

[S15] C：类型转换
来源：http://dali.zhixingplan.top/Article/details/gtimgyoetb.html

(double) a / b
来源：http://dali.jiagoushi.top/Article/details/gtvzayftrw.html

[S16] C：位操作置位
来源：http://dali.zdqjudy.top/Article/details/gtsahtolzw.html

x |= (1 << 3);
来源：http://dali.zhixingplan.top/Article/details/gtnxdzvitu.html

[S17] C：安全拼接字符串
来源：http://dali.yueranfly.top/Article/details/gteofdhdgw.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.svipenyu.cn/Article/details/gtqadlltbe.html

[S18] C：命令行参数
来源：http://dali.9152youxi.cn/Article/details/gtnhyjktkz.html

int main(int argc, char **argv)
来源：http://dali.xuanzx.com/Article/details/gtyvfoesua.html

[S19] C：快速排序
来源：http://dali.daxiang520.top/Article/details/gtcpkpouky.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.cashguo.top/Article/details/gtxettdxwu.html

[S20] C：二分查找
来源：http://dali.jlsjyb.cn/Article/details/gtphdrfwwv.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.yanxiufei.cn/Article/details/gtffmhznzw.html

[S21] C：字符类别判断
来源：http://dali.hnxiangtu.top/Article/details/gtazcjvyto.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.yongpay.top/Article/details/gtdswaofnl.html

[S22] C：字符串转数字
来源：http://dali.jiagoushi.top/Article/details/gtvdxfeelr.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.mhx1999.top/Article/details/gtdabyzabl.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gtkykjnnce.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.nanxuanxn.top/Article/details/gtoikwdadv.html

[S24] C：获取本地时间
来源：http://dali.quarkkingdee.top/Article/details/gtkymbhmfe.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.jlsjyb.cn/Article/details/gtlxmouwvu.html

[S25] C：内存拷贝
来源：http://dali.wangshuangyany.cn/Article/details/gtqfydzens.html

memcpy(dst, src, n);
来源：http://dali.yj202588.top/Article/details/gtxzmumbxm.html

[S26] C：内存清零
来源：http://dali.ydzc1.top/Article/details/gtmkcjnmdr.html

memset(a, 0, sizeof a);
来源：http://dali.tian-w.cn/Article/details/gtlroqxedy.html

[S27] C：定义常量
来源：http://dali.yj202588.top/Article/details/gtquovvpmm.html

const double PI = 3.14159;
来源：http://dali.jianghu66.top/Article/details/gtngnujhpt.html

[S28] C：静态变量
来源：http://dali.0kj1m.cn/Article/details/gtycfmloyv.html

static int counter = 0;
来源：http://dali.zhixingplan.top/Article/details/gtqsvjtuzt.html

[S29] C：变参函数
来源：http://dali.nanxuanxn.top/Article/details/gtuaawdltl.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.hysaishi.cn/Article/details/gtofdypnbc.html

[S30] C：头文件保护
来源：http://dali.havefunace.top/Article/details/gtjrxsdfdl.html

#ifndef X_H
来源：http://dali.jianghu66.top/Article/details/gtqnwoktqt.html

#define X_H
来源：http://dali.zdqjudy.top/Article/details/gthvqgxizu.html

#endif
来源：http://dali.shanyushiyangtech.top/Article/details/gthppcavgq.html

[S31] C++：Hello World
来源：http://dali.9152youxi.cn/Article/details/gtltuutiuz.html

#include <iostream>
来源：http://dali.redwolf501.top/Article/details/gtqzazgfrk.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.gzhubu.top/Article/details/gtavsuatim.html

[S32] C++：字符串
来源：http://dali.yangfankeji.com/Article/details/gtkptlvstt.html

std::string s = "hi";  s += "!";
来源：http://dali.xuanzx.com/Article/details/gtktopxscy.html

[S33] C++：vector 增删
来源：http://dali.nwbrower.top/Article/details/gtvzmjjcdx.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.tanke756.top/Article/details/gtvqprmqxk.html

[S34] C++：遍历 vector
来源：http://dali.feifeiyinyue.top/Article/details/gtykiidfyz.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.jianghu66.top/Article/details/gtqhbgjynw.html

[S35] C++：map
来源：http://dali.havefunace.top/Article/details/gtqrryfkhy.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.cashguo.top/Article/details/gtkpyyarrm.html

[S36] C++：unordered_map
来源：http://dali.cheryme.top/Article/details/gttntpulnc.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.pengpengdd.cyou/Article/details/gtcvmlbwtw.html

[S37] C++：set
来源：http://dali.yueranfly.top/Article/details/gtjjilwxjq.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.xylfe.cn/Article/details/gtereuihzb.html

[S38] C++：排序
来源：http://dali.vqdsnc.cn/Article/details/gtzgpmvmdb.html

std::sort(v.begin(), v.end());
来源：http://dali.zycfv.cn/Article/details/gtivmrvwqk.html

[S39] C++：自定义比较器排序
来源：http://dali.daxiang520.top/Article/details/gtgpwhmiwc.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.gotoacloud.top/Article/details/gttzaswmvb.html

[S40] C++：查找元素
来源：http://dali.kuanghao11.cn/Article/details/gtgcenagmy.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.daxiang520.top/Article/details/gtuzqehfxv.html

[S41] C++：类与构造函数
来源：http://dali.jinghuilouyu.cn/Article/details/gtpktdxlws.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.fengsongda.top/Article/details/gtzghxakhr.html

[S42] C++：继承与虚函数
来源：http://dali.fzhhl.top/Article/details/gtqlvettdp.html

class B : public Base { public: void f() override {} };
来源：http://dali.quarkkingdee.top/Article/details/gtaarokwuu.html

[S43] C++：智能指针
来源：http://dali.yongpay.top/Article/details/gtakzxsfyv.html

auto p = std::make_unique<int>(5);
来源：http://dali.gotoacloud.top/Article/details/gtcywujemw.html

[S44] C++：引用传参
来源：http://dali.xinyue.icu/Article/details/gtmejscmmv.html

void inc(int &x) { ++x; }
来源：http://dali.birdmap.top/Article/details/gtuzcramcf.html

[S45] C++：lambda
来源：http://dali.wangdashe.top/Article/details/gtnupfjfwb.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.sufxvd.cn/Article/details/gtwscounvh.html

[S46] C++：函数模板
来源：http://dali.cdnleiting.top/Article/details/gtdnzinqyk.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.hywenlv.cn/Article/details/gthxzyryyd.html

[S47] C++：结构化绑定遍历
来源：http://dali.xuanzx.com/Article/details/gtotqjawvs.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.yj202588.top/Article/details/gtqiksudir.html

[S48] C++：逐行读文件
来源：http://dali.feifeiyinyue.top/Article/details/gtqmoqotfy.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.birdmap.top/Article/details/gtekrmdoor.html

while (std::getline(in, line)) { }
来源：http://dali.sweek.top/Article/details/gteaeqgotz.html

[S49] C++：写文件
来源：http://dali.9152youxi.cn/Article/details/gtaeryipdh.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.snrcjt.cn/Article/details/gtmdrnrzyf.html

[S50] C++：格式化数字
来源：http://dali.chenjidiqi.icu/Article/details/gtdhsichli.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.aizwys.cn/Article/details/gtdikpvrzl.html

[S51] C++：显式类型转换
来源：http://dali.cashguo.top/Article/details/gtrgvjkebr.html

static_cast<double>(a) / b
来源：http://dali.haohaochexian.top/Article/details/gtbmnfkers.html

[S52] C++：const 与 noexcept
来源：http://dali.jinqigufen.top/Article/details/gttpbekdbl.html

int size() const noexcept { return n_; }
来源：http://dali.andypj.xyz/Article/details/gtmlfgksjj.html

[S53] C++：移动语义
来源：http://dali.jinghuilouyu.cn/Article/details/gtilatkubs.html

std::vector<int> w = std::move(v);
来源：http://dali.hnxiangtu.top/Article/details/gtddojuhei.html

[S54] C++：异常处理
来源：http://dali.pycfn.com/Article/details/gtvxuvqdsz.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.yj20258888.top/Article/details/gtrdsvcqeh.html

[S55] C++：结构化绑定
来源：http://dali.dianchejie.cn/Article/details/gtvaiacvsm.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.xziqi.cn/Article/details/gtadnscxsk.html

[S56] C++：optional
来源：http://dali.gzhubu.top/Article/details/gtjrsvaela.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.quarkkingdee.top/Article/details/gtlksylfwp.html

[S57] C++：编译期常量
来源：http://dali.yueranfly.top/Article/details/gtuinixxjs.html

constexpr int N = 10;
来源：http://dali.cashguo.top/Article/details/gtqkzioeji.html

[S58] C++：命名空间
来源：http://dali.andypj.xyz/Article/details/gthyfcktlw.html

namespace ns { int f() { return 1; } }
来源：http://dali.aizwys.cn/Article/details/gtaoyiwimt.html

[S59] C++：静态断言
来源：http://dali.wangshuangyany.cn/Article/details/gtolpywmdt.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjtuhcsfh.html

[S60] C++：遍历并删除元素
来源：http://dali.jqgufenzy.top/Article/details/gtqnfcrddx.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.yueranfly.top/Article/details/gtdglbvimk.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtvuohvshn.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.sysykeji.top/Article/details/gtaefbtznz.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtpaufuhds.html

[T01] Kotlin：Hello World
来源：http://dali.shzxlz.cn/Article/details/gtfmxsqlkf.html

println("Hello")
来源：http://dali.zhaomingkeji.xyz/Article/details/gthankxoby.html

[T02] Kotlin：变量
来源：http://dali.tanke756.top/Article/details/gtxxfwbdar.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zycfv.cn/Article/details/gtjuefuxxn.html

[T03] Kotlin：字符串模板
来源：http://dali.sufxvd.cn/Article/details/gttunlwtiq.html

"值: $b"
来源：http://dali.ybcxt.top/Article/details/gtkauqcwzb.html

[T04] Kotlin：空安全
来源：http://dali.xinyue.icu/Article/details/gtyjvqgwhi.html

val n: String? = null;  n?.length
来源：http://dali.quarkkingdee.top/Article/details/gtbopqibtt.html

[T05] Kotlin：when 表达式
来源：http://dali.dashuyun.cn/Article/details/gtpgghxosv.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.meibo888.top/Article/details/gtwopfdpue.html

[T06] Kotlin：集合映射
来源：http://dali.zhixingplan.top/Article/details/gthuhaggqm.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqdwbpgfc.html

[T07] Kotlin：集合过滤
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjglqninv.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.cheryme.top/Article/details/gtovddhqex.html

[T08] Kotlin：数据类
来源：http://dali.zhiwuduotai.top/Article/details/gttafirgmi.html

data class User(val name: String, val age: Int)
来源：http://dali.gaohongyu789.top/Article/details/gtzmiogunh.html

[T09] Kotlin：扩展函数
来源：http://dali.vqdsnc.cn/Article/details/gtsubfxmjl.html

fun String.exclaim() = this + "!"
来源：http://dali.sweek.top/Article/details/gtfnspioik.html

[T10] Kotlin：默认参数
来源：http://dali.yvedp.cn/Article/details/gtxlturszp.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.hammf.cn/Article/details/gtmsgmgltw.html

[T11] Kotlin：协程
来源：http://dali.chenjidiqi.icu/Article/details/gtsbnbgtkw.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.feifeiyinyue.top/Article/details/gtlpuwdgnd.html

[T12] Kotlin：解构声明
来源：http://dali.wangdashe.top/Article/details/gtwdnimumo.html

val (a, b) = Pair(1, 2)
来源：http://dali.pengpengdd.cyou/Article/details/gtlvgqaltv.html

[T13] Kotlin：只读 Map
来源：http://dali.dianchejie.cn/Article/details/gtxhdamplc.html

val m = mapOf("a" to 1)
来源：http://dali.svipenyu.cn/Article/details/gtvcctunwk.html

[T14] Kotlin：循环
来源：http://dali.gzhubu.top/Article/details/gtdqdlcieq.html

for (i in 1..10) println(i)
来源：http://dali.hysaishi.cn/Article/details/gtktlitocd.html

[T15] Kotlin：接口
来源：http://dali.aibaodan.cn/Article/details/gtlezbohea.html

interface Shape { fun area(): Double }
来源：http://dali.guowangkeji.top/Article/details/gtgxssqxoh.html

[T16] Swift：Hello World
来源：http://dali.mhx1999.top/Article/details/gtkrwllpqr.html

print("Hello")
来源：http://dali.tanke756.top/Article/details/gtrmagpqcf.html

[T17] Swift：变量与常量
来源：http://dali.jlsjyb.cn/Article/details/gtqxhjsoyr.html

var a = 1;  let b = 2
来源：http://dali.ydzc1.top/Article/details/gtjbypmeze.html

[T18] Swift：字符串插值
来源：http://dali.dashuyun.cn/Article/details/gtkkzhmklf.html

"值: \(b)"
来源：http://dali.cashguo.top/Article/details/gttyukmbsz.html

[T19] Swift：可选绑定
来源：http://dali.gogol.net.cn/Article/details/gtzmqabkal.html

if let n = opt { print(n) }
来源：http://dali.haohaochexian.top/Article/details/gtsbpokgtt.html

[T20] Swift：数组操作
来源：http://dali.tianlin.xyz/Article/details/gtdistsvth.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.xuetiantiany.cn/Article/details/gtookpoptn.html

[T21] Swift：遍历
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaazrqblj.html

for x in a { print(x) }
来源：http://dali.cashguo.top/Article/details/gtbqapwdxf.html

[T22] Swift：字典
来源：http://dali.yj20258.top/Article/details/gtyzpvwjac.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.yangfankeji.com/Article/details/gtmozywfdt.html

[T23] Swift：函数
来源：http://dali.jinqigfzy.top/Article/details/gtzrcekbqr.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.hywenlv.cn/Article/details/gtvtdrqbaz.html

[T24] Swift：闭包
来源：http://dali.shzxlz.cn/Article/details/gtnakszoxj.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.c1oappe.top/Article/details/gtwvmrlkra.html

[T25] Swift：结构体
来源：http://dali.0kj1m.cn/Article/details/gtlwinfkfn.html

struct P { var x: Int }
来源：http://dali.ppjwa.cn/Article/details/gtiltjezau.html

[T26] Swift：类与重写
来源：http://dali.xinyue.icu/Article/details/gttddtzstb.html

class A: Base { override func f() {} }
来源：http://dali.yanxiufei.cn/Article/details/gtvlavftjq.html

[T27] Swift：错误处理
来源：http://dali.yongpay.top/Article/details/gtcstrotpq.html

do { try f() } catch { print(error) }
来源：http://dali.guowangkeji.top/Article/details/gtyxjqqdpr.html

[T28] Swift：枚举
来源：http://dali.redwolf501.top/Article/details/gtrtljmokp.html

enum Color { case red, green }
来源：http://dali.ppjwa.cn/Article/details/gtfpdhbfju.html

[T29] Swift：guard 提前返回
来源：http://dali.nanxuanxn.top/Article/details/gtgzlajxpl.html

guard let x = opt else { return }
来源：http://dali.yvedp.cn/Article/details/gtpiclwupm.html

[T30] Swift：协议
来源：http://dali.yonumen.top/Article/details/gtgnardnwu.html

protocol Shape { func area() -> Double }
来源：http://dali.jiagoushi.top/Article/details/gthjoefnvb.html

[T31] Lua：Hello World
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoieqvdwe.html

print("Hello")
来源：http://dali.nanxinkj.top/Article/details/gtkukfowsf.html

[T32] Lua：局部变量
来源：http://dali.guowangkeji.top/Article/details/gthjxbpwan.html

local a = 1
来源：http://dali.andypj.xyz/Article/details/gtiqoaswba.html

[T33] Lua：表（数组）
来源：http://dali.yangfankeji.com/Article/details/gtysbyvcwc.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.yangfankeji.com/Article/details/gtrhaypqdl.html

[T34] Lua：遍历表
来源：http://dali.feifeiyinyue.top/Article/details/gtgsspdykj.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.smart0.xyz/Article/details/gtxosdffop.html

[T35] Lua：字典表
来源：http://dali.yanxiufei.cn/Article/details/gtuacapwrn.html

local d = { a = 1 };  d.b = 2
来源：http://dali.gotoacloud.top/Article/details/gtoihtjdvz.html

[T36] Lua：函数
来源：http://dali.ivvv.top/Article/details/gtewdywrap.html

function add(a, b) return a + b end
来源：http://dali.birdmap.top/Article/details/gtawontbgw.html

[T37] Lua：字符串拼接
来源：http://dali.guowangkeji.top/Article/details/gtrhifrzkw.html

"a" .. "b"
来源：http://dali.xziqi.cn/Article/details/gtmrdbvjbp.html

[T38] Lua：条件
来源：http://dali.xuetiantiany.cn/Article/details/gthhhpvops.html

if x > 0 then print("正") end
来源：http://dali.quarkkingdee.top/Article/details/gtkwuhohpb.html

[T39] Lua：模式匹配
来源：http://dali.wangdashe.top/Article/details/gtsvprozmz.html

string.find(s, "%d+")
来源：http://dali.aibaodan.cn/Article/details/gtrsueiftu.html

[T40] Lua：元表
来源：http://dali.kuanghao11.cn/Article/details/gtkdiszdpd.html

setmetatable({}, { __index = base })
来源：http://dali.dashuyun.cn/Article/details/gtemntvftz.html

[T41] Perl：Hello World
来源：http://dali.tianlin.xyz/Article/details/gtlfqbrzbi.html

print "Hello\n";
来源：http://dali.cdnleiting.top/Article/details/gthigmhdab.html

[T42] Perl：变量类型
来源：http://dali.redwolf501.top/Article/details/gtukedhhzw.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.daria6918.cn/Article/details/gtuunnosli.html

[T43] Perl：字符串插值
来源：http://dali.sxryk.cn/Article/details/gtnzgprixo.html

"值: $a"
来源：http://dali.xuetiantiany.cn/Article/details/gtydoksqxz.html

[T44] Perl：条件
来源：http://dali.aizwys.cn/Article/details/gtawvmjbam.html

if ($a > 0) { print "正"; }
来源：http://dali.c1oappe.top/Article/details/gtqdkmeavc.html

[T45] Perl：数组遍历
来源：http://dali.daxiang520.top/Article/details/gtmssqddfm.html

for my $x (@arr) { print $x; }
来源：http://dali.meibo888.top/Article/details/gtjkysxchu.html

[T46] Perl：哈希操作
来源：http://dali.nanxuanxn.top/Article/details/gthjdncfod.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.snrcjt.cn/Article/details/gtgnteyapy.html

[T47] Perl：正则捕获
来源：http://dali.jqgufenzy.top/Article/details/gtgikcnmvj.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.sysykeji.top/Article/details/gtussdqskx.html

[T48] Perl：正则替换
来源：http://dali.yuanzhike.top/Article/details/gtzdzezmvg.html

$s =~ s/old/new/g;
来源：http://dali.fengsongda.top/Article/details/gtlispkbge.html

[T49] Perl：函数
来源：http://dali.xuanzx.com/Article/details/gtsefccpmq.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.snrcjt.cn/Article/details/gtxqwcfkcv.html

[T50] Perl：逐行读文件
来源：http://dali.vqdsnc.cn/Article/details/gthsbxvodl.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.cashguo.top/Article/details/gtvttyttum.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gtuidhexav.html

[T51] Scala：Hello World
来源：http://dali.ivvv.top/Article/details/gtdgkapiwv.html

println("Hello")
来源：http://dali.snrcjt.cn/Article/details/gtxlvjtybu.html

[T52] Scala：变量
来源：http://dali.hnxiangtu.top/Article/details/gtgnjlzarb.html

val a = 1;  var b = 2
来源：http://dali.yueranfly.top/Article/details/gtsoluunzx.html

[T53] Scala：字符串插值
来源：http://dali.jiagoushi.top/Article/details/gtzgwzgkxa.html

s"值: $b"
来源：http://dali.daria6918.cn/Article/details/gtefnqdkhq.html

[T54] Scala：集合映射
来源：http://dali.sweek.top/Article/details/gtmqnkxkzn.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.shzxlz.cn/Article/details/gtqiiuhdlt.html

[T55] Scala：集合过滤
来源：http://dali.jinqigufen.top/Article/details/gtrohvcwor.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.sufxvd.cn/Article/details/gtrfnvkmur.html

[T56] Scala：样例类
来源：http://dali.dashuyun.cn/Article/details/gtufalmgpa.html

case class User(name: String, age: Int)
来源：http://dali.zhengqikj.top/Article/details/gtzosdmlea.html

[T57] Scala：模式匹配
来源：http://dali.ppjwa.cn/Article/details/gtxylozjsy.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhoulong.xyz/Article/details/gtsdxznliz.html

[T58] Scala：函数定义
来源：http://dali.cucudq.cn/Article/details/gtzfqxhngq.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhiwuduotai.top/Article/details/gteajnkrfp.html

[T59] Scala：循环
来源：http://dali.nwbrower.top/Article/details/gtsmpuicap.html

for (i <- 1 to 10) println(i)
来源：http://dali.haohaochexian.top/Article/details/gtgncjvbbn.html

[T60] Scala：折叠
来源：http://dali.tian-w.cn/Article/details/gtlxqmubyy.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhengqikj.top/Article/details/gtjqakyrnk.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtiaolspml.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.hammf.cn/Article/details/gtpjsnzlxl.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtpovjzymj.html

[U01] Py：创建虚拟环境
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiremmges.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.snrcjt.cn/Article/details/gtukdgshud.html

[U02] Py：导出 / 安装依赖
来源：http://dali.fzhhl.top/Article/details/gtgdkyxeic.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.mhx1999.top/Article/details/gtxyeqlybv.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gtbaevrlgj.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.gaohongyu789.top/Article/details/gtyznmuold.html

[U04] Py：变量调试打印
来源：http://dali.yueranfly.top/Article/details/gtumnaquls.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.meibo888.top/Article/details/gtunockrtp.html

[U05] Py：列表去重且保序
来源：http://dali.zhoulong.xyz/Article/details/gtbziylnnt.html

list(dict.fromkeys(arr))
来源：http://dali.yonumen.top/Article/details/gtobqfyexm.html

[U06] Py：合并两个字典
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwhxsibmb.html

{**a, **b}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcguwnpmq.html


<!-- 参考信息 -->