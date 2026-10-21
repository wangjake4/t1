代发 wailian999

ssh user@host 'uptime'
来源：http://dali.shanyushiyangkeji.top/Article/details/gthxwvixjv.html

[R58] 下载文件
来源：http://dali.chenjidiqi.icu/Article/details/gtsdduclnt.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.yvedp.cn/Article/details/gtvyzzbuzz.html

[R59] 发 POST JSON
来源：http://dali.jinghuilouyu.cn/Article/details/gtxxulysuc.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.gzhubu.top/Article/details/gtmwhyghly.html

[R60] 只看 HTTP 状态码
来源：http://dali.ehwqpu.com/Article/details/gtduksbaha.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.ivvv.top/Article/details/gtektuavhh.html

[R61] 磁盘占用
来源：http://dali.wangdashe.top/Article/details/gtgwdgllvm.html

df -h;  du -sh *
来源：http://dali.jqgfzy.top/Article/details/gtpwqmzbph.html

[R62] 找最占空间的文件
来源：http://dali.ehwqpu.com/Article/details/gtcjbbjhgg.html

du -ah . | sort -rh | head -10
来源：http://dali.cdnleiting.top/Article/details/gtjrnoscmp.html

[R63] 内存与进程
来源：http://dali.shangyingyoupin.top/Article/details/gtimnolrvm.html

free -h;  ps aux | grep nginx
来源：http://dali.nwbrower.top/Article/details/gtjxzwtwcx.html

[R64] 结束进程
来源：http://dali.wangdashe.top/Article/details/gtkellrlqz.html

kill -9 $(pgrep -f app.py)
来源：http://dali.cheryme.top/Article/details/gtkeogfzej.html

[R65] 查看端口占用
来源：http://dali.ehwqpu.com/Article/details/gtrscsajbx.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.chenjidiqi.icu/Article/details/gteqomzhfh.html

[R66] 定时任务
来源：http://dali.iojbl.cn/Article/details/gtjlxlruux.html

crontab -e;  crontab -l
来源：http://dali.pycfn.com/Article/details/gtfsosadrp.html

[R67] 生成随机十六进制串
来源：http://dali.yuxming.cn/Article/details/gtfiocaheq.html

openssl rand -hex 16
来源：http://dali.dashuyun.cn/Article/details/gtulupfequ.html

[R68] 计算文件校验值
来源：http://dali.yongpay.top/Article/details/gtwegpbwts.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.shuidangran.top/Article/details/gthnpmritt.html

[R69] 生成随机密码
来源：http://dali.xuanzx.com/Article/details/gtzdxhzavf.html

head -c 16 /dev/urandom | base64
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxspefngy.html

[R70] 时间戳与互转
来源：http://dali.zycfv.cn/Article/details/gtteargzba.html

date +%s;  date -d @1700000000
来源：http://dali.yueranfly.top/Article/details/gtbhtawihr.html

[R71] 日期格式化
来源：http://dali.quarkkingdee.top/Article/details/gttwhqgesq.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.guowangkeji.top/Article/details/gtbzfgqjph.html

[R72] 等待端口就绪
来源：http://dali.mhx1999.top/Article/details/gtgfpbwapv.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.hnxiangtu.top/Article/details/gtqbkneefc.html

[R73] 分割大日志
来源：http://dali.chenjidiqi.icu/Article/details/gttnpvnqhs.html

split -l 1000 big.log part_
来源：http://dali.jinqigfzy.top/Article/details/gtchtghhjg.html

[R74] 批量重命名
来源：http://dali.birdmap.top/Article/details/gtpmpjloua.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.kuanghao11.cn/Article/details/gtttmydehg.html

[R75] 导出环境变量
来源：http://dali.yvedp.cn/Article/details/gtbpgchqzu.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.shuidangran.top/Article/details/gtfytuudno.html

[R76] 使用临时文件
来源：http://dali.xuanzx.com/Article/details/gtwyqcnwxu.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.hongshengwenyu.top/Article/details/gtfmtqhwdl.html

[R77] 读取用户输入
来源：http://dali.vqdsnc.cn/Article/details/gtrsivdtzn.html

read -rp "请输入: " ans
来源：http://dali.yj20258.top/Article/details/gtngbxhxgi.html

[R78] 交互式菜单
来源：http://dali.fengsongda.top/Article/details/gtypvzsrhb.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.smart0.xyz/Article/details/gtygcbwkwv.html

[R79] 解析命令行选项
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvvyflupb.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.guowangkeji.top/Article/details/gtqddnbnup.html

[R80] 查看脚本执行耗时
来源：http://dali.pengpengdd.cyou/Article/details/gtsjhvozqx.html

time ./run.sh
来源：http://dali.yueranfly.top/Article/details/gtjpixglhn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtapujacvz.html

S. C / C++ 专题
来源：http://dali.aibaodan.cn/Article/details/gtftervdqc.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtxrvyfayd.html

[S01] C：Hello World
来源：http://dali.9152youxi.cn/Article/details/gtqscrfznu.html

#include <stdio.h>
来源：http://dali.hysaishi.cn/Article/details/gtknhbvlkc.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.0kj1m.cn/Article/details/gtvhfzayto.html

[S02] C：变量与格式化输出
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdfpcvtvw.html

int a = 10; printf("%d\n", a);
来源：http://dali.cheryme.top/Article/details/gtjrkefijn.html

[S03] C：读入整数
来源：http://dali.jianghu66.top/Article/details/gtpmyfplpq.html

int x; scanf("%d", &x);
来源：http://dali.hfpthk.cn/Article/details/gtuiolvqeb.html

[S04] C：字符串复制
来源：http://dali.xziqi.cn/Article/details/gtfvqkywvd.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.daria6918.cn/Article/details/gtxfvlarsf.html

[S05] C：字符串长度
来源：http://dali.tianlin.xyz/Article/details/gtjvmplsoe.html

strlen(s)
来源：http://dali.jianghu66.top/Article/details/gtqfhzjiyb.html

[S06] C：字符串比较
来源：http://dali.zhixingplan.top/Article/details/gtbdadvpgs.html

strcmp(a, b) == 0
来源：http://dali.xinyue.icu/Article/details/gtijpxvmzo.html

[S07] C：数组遍历求和
来源：http://dali.shuidangran.top/Article/details/gttmhzgpoj.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.hywenlv.cn/Article/details/gtccdbaxhw.html

[S08] C：动态内存分配与释放
来源：http://dali.yj20258.top/Article/details/gtkkoiukky.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.gaohongyu789.top/Article/details/gtpeveqqjx.html

[S09] C：结构体定义与初始化
来源：http://dali.chenzaomai.com/Article/details/gtkyckxyfb.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gtecgeobge.html

[S10] C：指针与解引用
来源：http://dali.vqdsnc.cn/Article/details/gtrrvlrvmu.html

int *p = &a;  *p = 5;
来源：http://dali.fengsongda.top/Article/details/gtxfqnomlg.html

[S11] C：逐行读文件
来源：http://dali.zhengqikj.top/Article/details/gtogotkctw.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.cheryme.top/Article/details/gtzwgdhmgg.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.hfpthk.cn/Article/details/gtcquually.html

fclose(f);
来源：http://dali.shzxlz.cn/Article/details/gtgonihglj.html

[S12] C：写文件
来源：http://dali.nanxinkj.top/Article/details/gtvrkbcwiw.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.ydzc1.top/Article/details/gtfnvidfta.html

[S13] C：宏定义
来源：http://dali.jinqigfzy.top/Article/details/gtgksbxyrf.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.chenjidiqi.icu/Article/details/gtmmwgzhao.html

[S14] C：枚举
来源：http://dali.yj20258888.top/Article/details/gthaoridho.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.yvedp.cn/Article/details/gtijmeaxtg.html

[S15] C：类型转换
来源：http://dali.jinghuilouyu.cn/Article/details/gtegfammgn.html

(double) a / b
来源：http://dali.dashuyun.cn/Article/details/gtmtnjquwh.html

[S16] C：位操作置位
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpczvlyjl.html

x |= (1 << 3);
来源：http://dali.gzhubu.top/Article/details/gtjdkruyer.html

[S17] C：安全拼接字符串
来源：http://dali.dianchejie.cn/Article/details/gtsdovkveg.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.shzxlz.cn/Article/details/gtfosmhmgv.html

[S18] C：命令行参数
来源：http://dali.gotoacloud.top/Article/details/gtsszkjxnd.html

int main(int argc, char **argv)
来源：http://dali.daxiang520.top/Article/details/gtmfdtybgd.html

[S19] C：快速排序
来源：http://dali.zhengqikj.top/Article/details/gtleveglbn.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.ywan-chungtsiang.top/Article/details/gthwnetwkd.html

[S20] C：二分查找
来源：http://dali.jinqigufen.top/Article/details/gtzzuxlpvg.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.9152youxi.cn/Article/details/gtbkuejpwn.html

[S21] C：字符类别判断
来源：http://dali.yj20258.top/Article/details/gtkulcuxqg.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.chenlongwang.top/Article/details/gtrlnekqso.html

[S22] C：字符串转数字
来源：http://dali.jlsjyb.cn/Article/details/gtpokaivgr.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.dianchejie.cn/Article/details/gtmxoabzug.html

[S23] C：随机数
来源：http://dali.quarkkingdee.top/Article/details/gtvlelnqlu.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.shanyushiyangtech.top/Article/details/gtzmdlmngs.html

[S24] C：获取本地时间
来源：http://dali.0kj1m.cn/Article/details/gtomdoioyy.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.iojbl.cn/Article/details/gtjojdpfya.html

[S25] C：内存拷贝
来源：http://dali.zycfv.cn/Article/details/gthpgwwsxr.html

memcpy(dst, src, n);
来源：http://dali.aibaodan.cn/Article/details/gthqljulcg.html

[S26] C：内存清零
来源：http://dali.jinghuilouyu.cn/Article/details/gtxhygvajo.html

memset(a, 0, sizeof a);
来源：http://dali.9152youxi.cn/Article/details/gtoquvimsx.html

[S27] C：定义常量
来源：http://dali.ivvv.top/Article/details/gtxgjumtrs.html

const double PI = 3.14159;
来源：http://dali.hnxiangtu.top/Article/details/gtuomkvzrs.html

[S28] C：静态变量
来源：http://dali.sxryk.cn/Article/details/gtgsoaauqb.html

static int counter = 0;
来源：http://dali.9152youxi.cn/Article/details/gtjfcywpvo.html

[S29] C：变参函数
来源：http://dali.c1oappe.top/Article/details/gthxzkxzfm.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.ybcxt.top/Article/details/gtgggrbxfl.html

[S30] C：头文件保护
来源：http://dali.yanxiufei.cn/Article/details/gtoxzwjtam.html

#ifndef X_H
来源：http://dali.xuanzx.com/Article/details/gtehkleznl.html

#define X_H
来源：http://dali.xuetiantiany.cn/Article/details/gturwxwthk.html

#endif
来源：http://dali.fengsongda.top/Article/details/gtytffvvyj.html

[S31] C++：Hello World
来源：http://dali.daria6918.cn/Article/details/gtqtmhugie.html

#include <iostream>
来源：http://dali.yangfankeji.com/Article/details/gtqbcxewfu.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.svipenyu.cn/Article/details/gtoerrzbhr.html

[S32] C++：字符串
来源：http://dali.wangdashe.top/Article/details/gtbpwwxdjf.html

std::string s = "hi";  s += "!";
来源：http://dali.birdmap.top/Article/details/gtvkfzmvwd.html

[S33] C++：vector 增删
来源：http://dali.feifeiyinyue.top/Article/details/gtpuircznw.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.feifeiyinyue.top/Article/details/gtljpnbtln.html

[S34] C++：遍历 vector
来源：http://dali.chenjidiqi.icu/Article/details/gtierrpwld.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.gzhubu.top/Article/details/gtqggvlsmd.html

[S35] C++：map
来源：http://dali.aizwys.cn/Article/details/gtqdyrfxtd.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hammf.cn/Article/details/gtdefjsazc.html

[S36] C++：unordered_map
来源：http://dali.sxryk.cn/Article/details/gthnvvhhns.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.wangdashe.top/Article/details/gtkrhgjndg.html

[S37] C++：set
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqqxvjiub.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.fzhhl.top/Article/details/gtboswftmz.html

[S38] C++：排序
来源：http://dali.xziqi.cn/Article/details/gtraspdezi.html

std::sort(v.begin(), v.end());
来源：http://dali.tian-w.cn/Article/details/gtyevdhizl.html

[S39] C++：自定义比较器排序
来源：http://dali.xylfe.cn/Article/details/gtehvaacpd.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.bjfxy.top/Article/details/gtxxhckjzx.html

[S40] C++：查找元素
来源：http://dali.sysykeji.top/Article/details/gtbhvqfcfr.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.mhx1999.top/Article/details/gttmcosbtt.html

[S41] C++：类与构造函数
来源：http://dali.9152youxi.cn/Article/details/gtvnmajfuc.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.aibaodan.cn/Article/details/gtscejessy.html

[S42] C++：继承与虚函数
来源：http://dali.dianchejie.cn/Article/details/gtibqopdgj.html

class B : public Base { public: void f() override {} };
来源：http://dali.dianchejie.cn/Article/details/gthwapbthj.html

[S43] C++：智能指针
来源：http://dali.chenzaomai.com/Article/details/gthvjlzufw.html

auto p = std::make_unique<int>(5);
来源：http://dali.hammf.cn/Article/details/gtnnmhpzou.html

[S44] C++：引用传参
来源：http://dali.jyoumei.cn/Article/details/gtzvgpbpxf.html

void inc(int &x) { ++x; }
来源：http://dali.0kj1m.cn/Article/details/gtykxyooyh.html

[S45] C++：lambda
来源：http://dali.sysykeji.top/Article/details/gtytlscmdg.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.pengpengdd.cyou/Article/details/gtbqntgrvl.html

[S46] C++：函数模板
来源：http://dali.hammf.cn/Article/details/gtjatvbddp.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.xylfe.cn/Article/details/gtbkwbcjhn.html

[S47] C++：结构化绑定遍历
来源：http://dali.ehwqpu.com/Article/details/gtkupryvga.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zycfv.cn/Article/details/gtkuilytna.html

[S48] C++：逐行读文件
来源：http://dali.c1oappe.top/Article/details/gtseyecysw.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.pengpengdd.cyou/Article/details/gtjsbbbvns.html

while (std::getline(in, line)) { }
来源：http://dali.meibo888.top/Article/details/gtztvefzfq.html

[S49] C++：写文件
来源：http://dali.hysaishi.cn/Article/details/gtbotbnnhe.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.shanyushiyangkeji.top/Article/details/gtubhitqam.html

[S50] C++：格式化数字
来源：http://dali.zhoulong.xyz/Article/details/gtxrgigjwm.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.gotoacloud.top/Article/details/gtqyynbymf.html

[S51] C++：显式类型转换
来源：http://dali.meibo888.top/Article/details/gtfeweaqln.html

static_cast<double>(a) / b
来源：http://dali.sysykeji.top/Article/details/gtrxzzepod.html

[S52] C++：const 与 noexcept
来源：http://dali.yuxming.cn/Article/details/gtjrlaolke.html

int size() const noexcept { return n_; }
来源：http://dali.yj20258888.top/Article/details/gtabnjpbwb.html

[S53] C++：移动语义
来源：http://dali.jinqigfzy.top/Article/details/gtjaddukfk.html

std::vector<int> w = std::move(v);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlxghpugs.html

[S54] C++：异常处理
来源：http://dali.cucudq.cn/Article/details/gtlfbuvlwc.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.pengpengdd.cyou/Article/details/gtntelhrui.html

[S55] C++：结构化绑定
来源：http://dali.feifeiyinyue.top/Article/details/gtdahziydx.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.sufxvd.cn/Article/details/gtkwgmxzes.html

[S56] C++：optional
来源：http://dali.yuanzhike.top/Article/details/gturibuosi.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgtkegbre.html

[S57] C++：编译期常量
来源：http://dali.hnqzz.top/Article/details/gtacqamhbz.html

constexpr int N = 10;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpuoxnxju.html

[S58] C++：命名空间
来源：http://dali.dianchejie.cn/Article/details/gteqawdbnc.html

namespace ns { int f() { return 1; } }
来源：http://dali.svipenyu.cn/Article/details/gtsmgrqjfb.html

[S59] C++：静态断言
来源：http://dali.chenjidiqi.icu/Article/details/gtsoxzliux.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.c1oappe.top/Article/details/gtxilvnfdz.html

[S60] C++：遍历并删除元素
来源：http://dali.yanxiufei.cn/Article/details/gtsfmqqwpg.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.pengpengdd.cyou/Article/details/gtueuckdcq.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gticmxkagb.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yonumen.top/Article/details/gtfaurgnmv.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtiluwspaj.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gtrhsafvzr.html

println("Hello")
来源：http://dali.meibo888.top/Article/details/gtmxivwbqm.html

[T02] Kotlin：变量
来源：http://dali.cqqwz.cn/Article/details/gtdewjnzwt.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.cucudq.cn/Article/details/gtpkfrtbbf.html

[T03] Kotlin：字符串模板
来源：http://dali.meibo888.top/Article/details/gtudjmlmec.html

"值: $b"
来源：http://dali.hfpthk.cn/Article/details/gtcriunpuc.html

[T04] Kotlin：空安全
来源：http://dali.hfpthk.cn/Article/details/gtietttaos.html

val n: String? = null;  n?.length
来源：http://dali.wangshuangyany.cn/Article/details/gtldgddddh.html

[T05] Kotlin：when 表达式
来源：http://dali.zycfv.cn/Article/details/gthjuoyvmd.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.yueranfly.top/Article/details/gtjzahxeuo.html

[T06] Kotlin：集合映射
来源：http://dali.yvedp.cn/Article/details/gtzamsvrne.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.daxiang520.top/Article/details/gtnxdeezxd.html

[T07] Kotlin：集合过滤
来源：http://dali.shzxlz.cn/Article/details/gtzfkdwweu.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvhnrlsjd.html

[T08] Kotlin：数据类
来源：http://dali.jqgfzy.top/Article/details/gthgqemgnz.html

data class User(val name: String, val age: Int)
来源：http://dali.quarkkingdee.top/Article/details/gtmpgzamhk.html

[T09] Kotlin：扩展函数
来源：http://dali.zhixingplan.top/Article/details/gtjchqtvfx.html

fun String.exclaim() = this + "!"
来源：http://dali.bjfxy.top/Article/details/gtjmyaolme.html

[T10] Kotlin：默认参数
来源：http://dali.dashuyun.cn/Article/details/gtvfkcegsk.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.sysykeji.top/Article/details/gtsobtvbxf.html

[T11] Kotlin：协程
来源：http://dali.snrcjt.cn/Article/details/gtdirpzecq.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtobptyprq.html

[T12] Kotlin：解构声明
来源：http://dali.bjfxy.top/Article/details/gtgdkkhqhv.html

val (a, b) = Pair(1, 2)
来源：http://dali.nanxuanxn.top/Article/details/gtiwrxipbk.html

[T13] Kotlin：只读 Map
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzudskoar.html

val m = mapOf("a" to 1)
来源：http://dali.316326.xyz/Article/details/gtxslmgdqx.html

[T14] Kotlin：循环
来源：http://dali.zhiwuduotai.top/Article/details/gtpiujvnco.html

for (i in 1..10) println(i)
来源：http://dali.jinqigfzy.top/Article/details/gtdyuhuzqg.html

[T15] Kotlin：接口
来源：http://dali.sxryk.cn/Article/details/gtjgeycpfa.html

interface Shape { fun area(): Double }
来源：http://dali.chenlongwang.top/Article/details/gtnobpdnku.html

[T16] Swift：Hello World
来源：http://dali.feifeiyinyue.top/Article/details/gtfjcjflhg.html

print("Hello")
来源：http://dali.yj202588.top/Article/details/gtgeicmsug.html

[T17] Swift：变量与常量
来源：http://dali.mhx1999.top/Article/details/gtaoyzyebz.html

var a = 1;  let b = 2
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlzvakluh.html

[T18] Swift：字符串插值
来源：http://dali.birdmap.top/Article/details/gticfifqiy.html

"值: \(b)"
来源：http://dali.wangshuangyany.cn/Article/details/gtpxwcpzxc.html

[T19] Swift：可选绑定
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdqaoolij.html

if let n = opt { print(n) }
来源：http://dali.hnqzz.top/Article/details/gtmxzyifkk.html

[T20] Swift：数组操作
来源：http://dali.jinqigufen.top/Article/details/gtxsiaoedy.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.yuanzhike.top/Article/details/gtuxntxqfq.html

[T21] Swift：遍历
来源：http://dali.sweek.top/Article/details/gtxshurejd.html

for x in a { print(x) }
来源：http://dali.iojbl.cn/Article/details/gtfagncgsj.html

[T22] Swift：字典
来源：http://dali.yuanzhike.top/Article/details/gthvjtcbym.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.gzhubu.top/Article/details/gtglakupnq.html

[T23] Swift：函数
来源：http://dali.tian-w.cn/Article/details/gtykewhddm.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.hfpthk.cn/Article/details/gtfgcflwen.html

[T24] Swift：闭包
来源：http://dali.fengsongda.top/Article/details/gtkibphghe.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.hnqzz.top/Article/details/gtidjvlvpn.html

[T25] Swift：结构体
来源：http://dali.pycfn.com/Article/details/gtyzxlvtcr.html

struct P { var x: Int }
来源：http://dali.zhongyouzk.top/Article/details/gtqvkpxqrh.html

[T26] Swift：类与重写
来源：http://dali.ivvv.top/Article/details/gtoizzgusx.html

class A: Base { override func f() {} }
来源：http://dali.meibo888.top/Article/details/gtrgzimvgd.html

[T27] Swift：错误处理
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvccciikf.html

do { try f() } catch { print(error) }
来源：http://dali.cheryme.top/Article/details/gtqpsnpyrq.html

[T28] Swift：枚举
来源：http://dali.dianchejie.cn/Article/details/gtwxzrksvt.html

enum Color { case red, green }
来源：http://dali.nanxinkj.top/Article/details/gtmedyvgqu.html

[T29] Swift：guard 提前返回
来源：http://dali.vqdsnc.cn/Article/details/gtjlzvhgwb.html

guard let x = opt else { return }
来源：http://dali.andypj.xyz/Article/details/gthtbxscnn.html

[T30] Swift：协议
来源：http://dali.0kj1m.cn/Article/details/gttrvxswlx.html

protocol Shape { func area() -> Double }
来源：http://dali.jlsjyb.cn/Article/details/gtmngsxwtf.html

[T31] Lua：Hello World
来源：http://dali.zhengqikj.top/Article/details/gtvfaxopln.html

print("Hello")
来源：http://dali.andypj.xyz/Article/details/gtkpqfcobt.html

[T32] Lua：局部变量
来源：http://dali.zdqjudy.top/Article/details/gtkelvtfcb.html

local a = 1
来源：http://dali.sysykeji.top/Article/details/gtwregvuir.html

[T33] Lua：表（数组）
来源：http://dali.chenlongwang.top/Article/details/gtplxpmpnb.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiuhdwfor.html

[T34] Lua：遍历表
来源：http://dali.cqqwz.cn/Article/details/gtvveavnid.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.cheryme.top/Article/details/gttjvdzexz.html

[T35] Lua：字典表
来源：http://dali.jqgufenzy.top/Article/details/gtjhkrsqce.html

local d = { a = 1 };  d.b = 2
来源：http://dali.dianchejie.cn/Article/details/gtgvhnaqkr.html

[T36] Lua：函数
来源：http://dali.shzxlz.cn/Article/details/gtgdwfjava.html

function add(a, b) return a + b end
来源：http://dali.hysaishi.cn/Article/details/gtaucoafsv.html

[T37] Lua：字符串拼接
来源：http://dali.hnxiangtu.top/Article/details/gtlbjqvdvw.html

"a" .. "b"
来源：http://dali.hfpthk.cn/Article/details/gtrcuwqxxd.html

[T38] Lua：条件
来源：http://dali.dashuyun.cn/Article/details/gtyemhgbpq.html

if x > 0 then print("正") end
来源：http://dali.tianlin.xyz/Article/details/gtqffarnnw.html

[T39] Lua：模式匹配
来源：http://dali.yongpay.top/Article/details/gtsyezajav.html

string.find(s, "%d+")
来源：http://dali.chenjidiqi.icu/Article/details/gtfogwzdco.html

[T40] Lua：元表
来源：http://dali.mhx1999.top/Article/details/gtpxqtaluy.html

setmetatable({}, { __index = base })
来源：http://dali.chenlongwang.top/Article/details/gtvgccqmuy.html

[T41] Perl：Hello World
来源：http://dali.tian-w.cn/Article/details/gtstadxpnl.html

print "Hello\n";
来源：http://dali.guannengcc.top/Article/details/gtycbtrzla.html

[T42] Perl：变量类型
来源：http://dali.gzhubu.top/Article/details/gtwjyfvhmp.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gtbgmuxgcb.html

[T43] Perl：字符串插值
来源：http://dali.fengsongda.top/Article/details/gtfkjjtfem.html

"值: $a"
来源：http://dali.dashuyun.cn/Article/details/gtyddwtjdi.html

[T44] Perl：条件
来源：http://dali.fzhhl.top/Article/details/gtzeshdcbh.html

if ($a > 0) { print "正"; }
来源：http://dali.jqgfzy.top/Article/details/gtpzdcyhqs.html

[T45] Perl：数组遍历
来源：http://dali.bjfxy.top/Article/details/gtuixixzip.html

for my $x (@arr) { print $x; }
来源：http://dali.mhx1999.top/Article/details/gtiuqfgwmr.html

[T46] Perl：哈希操作
来源：http://dali.zhiwuduotai.top/Article/details/gtthmdeebo.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.haohaochexian.top/Article/details/gtnxrwehdd.html

[T47] Perl：正则捕获
来源：http://dali.tanke756.top/Article/details/gtpinirsar.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhiwuduotai.top/Article/details/gtlwunjmrb.html

[T48] Perl：正则替换
来源：http://dali.ehwqpu.com/Article/details/gtqdurzdko.html

$s =~ s/old/new/g;
来源：http://dali.nanxuanxn.top/Article/details/gthvlvrweg.html

[T49] Perl：函数
来源：http://dali.hfpthk.cn/Article/details/gtlhbivwhr.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.xinyue.icu/Article/details/gtmhgprhqg.html

[T50] Perl：逐行读文件
来源：http://dali.zhongyouzk.top/Article/details/gtipewmdll.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhixingplan.top/Article/details/gtlspgifzq.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.hfpthk.cn/Article/details/gtsdqfpute.html

[T51] Scala：Hello World
来源：http://dali.yj20258888.top/Article/details/gtpzwfdkzj.html

println("Hello")
来源：http://dali.chenjidiqi.icu/Article/details/gtejrpxgjh.html

[T52] Scala：变量
来源：http://dali.jinyuanbaomall.cn/Article/details/gtprymoxnv.html

val a = 1;  var b = 2
来源：http://dali.smart0.xyz/Article/details/gtwofhcttk.html

[T53] Scala：字符串插值
来源：http://dali.tian-w.cn/Article/details/gtlntdstjt.html

s"值: $b"
来源：http://dali.cdnleiting.top/Article/details/gtceunexlg.html

[T54] Scala：集合映射
来源：http://dali.sufxvd.cn/Article/details/gtrrzlanbe.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.yj202588.top/Article/details/gtxtegtxui.html

[T55] Scala：集合过滤
来源：http://dali.zdqjudy.top/Article/details/gtewpxiwyk.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.shangyingyoupin.top/Article/details/gtcheugnyy.html

[T56] Scala：样例类
来源：http://dali.jinqigfzy.top/Article/details/gtaauwmzns.html

case class User(name: String, age: Int)
来源：http://dali.yvedp.cn/Article/details/gtmakkxdfc.html

[T57] Scala：模式匹配
来源：http://dali.pengpengdd.cyou/Article/details/gtznwgbcpe.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.gotoacloud.top/Article/details/gtxotnssqc.html

[T58] Scala：函数定义
来源：http://dali.nanxuanxn.top/Article/details/gtekudfhct.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.guannengcc.top/Article/details/gtidqqgzrf.html

[T59] Scala：循环
来源：http://dali.zdqjudy.top/Article/details/gthcjinsqw.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhengqikj.top/Article/details/gtesrtqjez.html

[T60] Scala：折叠
来源：http://dali.nanxuanxn.top/Article/details/gthjettsig.html


<!-- 参考信息 -->