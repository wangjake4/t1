代发 wailian999

free -h;  ps aux | grep nginx
来源：http://dali.guowangkeji.top/Article/details/gtgwkngkug.html

[R64] 结束进程
来源：http://dali.hnqzz.top/Article/details/gtvhcoizkw.html

kill -9 $(pgrep -f app.py)
来源：http://dali.nanxinkj.top/Article/details/gtlskxeiwd.html

[R65] 查看端口占用
来源：http://dali.yvedp.cn/Article/details/gtpupypoxy.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.yj20258888.top/Article/details/gtishbvlbd.html

[R66] 定时任务
来源：http://dali.ywan-chungtsiang.top/Article/details/gtduxniivb.html

crontab -e;  crontab -l
来源：http://dali.yuanzhike.top/Article/details/gtzlmwlpxm.html

[R67] 生成随机十六进制串
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsrzwxtwq.html

openssl rand -hex 16
来源：http://dali.jinqigufen.top/Article/details/gtljvpceml.html

[R68] 计算文件校验值
来源：http://dali.shangyingyoupin.top/Article/details/gtxncgyikq.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.shzxlz.cn/Article/details/gtutkuvejt.html

[R69] 生成随机密码
来源：http://dali.gogol.net.cn/Article/details/gtuqumwoyr.html

head -c 16 /dev/urandom | base64
来源：http://dali.shangyingyoupin.top/Article/details/gtzhbtlwna.html

[R70] 时间戳与互转
来源：http://dali.ehwqpu.com/Article/details/gtbkabqrfq.html

date +%s;  date -d @1700000000
来源：http://dali.hongshengwenyu.top/Article/details/gtunplgosp.html

[R71] 日期格式化
来源：http://dali.cashguo.top/Article/details/gtwjqcrmit.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.pengpengdd.cyou/Article/details/gtfcrdhkfn.html

[R72] 等待端口就绪
来源：http://dali.jinqigfzy.top/Article/details/gtziakegbm.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.cashguo.top/Article/details/gttxbkeatc.html

[R73] 分割大日志
来源：http://dali.ppjwa.cn/Article/details/gtfkjfoypo.html

split -l 1000 big.log part_
来源：http://dali.yj202588.top/Article/details/gtnyaqnjgw.html

[R74] 批量重命名
来源：http://dali.iojbl.cn/Article/details/gtcahpbepc.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.fengsongda.top/Article/details/gtujlqpiho.html

[R75] 导出环境变量
来源：http://dali.gotoacloud.top/Article/details/gttcximgrx.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.nanxuanxn.top/Article/details/gtxidwlrof.html

[R76] 使用临时文件
来源：http://dali.yangfankeji.com/Article/details/gtyyhmpykt.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.hongshengwenyu.top/Article/details/gtvnwfbpiu.html

[R77] 读取用户输入
来源：http://dali.xinyue.icu/Article/details/gtapyrwycq.html

read -rp "请输入: " ans
来源：http://dali.wangdashe.top/Article/details/gtuuennbos.html

[R78] 交互式菜单
来源：http://dali.zhiwuduotai.top/Article/details/gtxlpgjclp.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.hnxiangtu.top/Article/details/gthvzqcvng.html

[R79] 解析命令行选项
来源：http://dali.tian-w.cn/Article/details/gtbcezrrhr.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.jinqigfzy.top/Article/details/gtyjhdjxkx.html

[R80] 查看脚本执行耗时
来源：http://dali.chenjidiqi.icu/Article/details/gtdypvipgj.html

time ./run.sh
来源：http://dali.meibo888.top/Article/details/gtnoosmmoo.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtzmddriww.html

S. C / C++ 专题
来源：http://dali.0kj1m.cn/Article/details/gtiupxlgmp.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtvyndmzic.html

[S01] C：Hello World
来源：http://dali.chenzaomai.com/Article/details/gtmvzhtjlm.html

#include <stdio.h>
来源：http://dali.ivvv.top/Article/details/gtzejlecjt.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.ydzc1.top/Article/details/gtxkrlagcu.html

[S02] C：变量与格式化输出
来源：http://dali.nanxinkj.top/Article/details/gtrtgcsozl.html

int a = 10; printf("%d\n", a);
来源：http://dali.quarkkingdee.top/Article/details/gthgtcrfzc.html

[S03] C：读入整数
来源：http://dali.ivvv.top/Article/details/gttkzzhcsu.html

int x; scanf("%d", &x);
来源：http://dali.0kj1m.cn/Article/details/gtkimdiwgx.html

[S04] C：字符串复制
来源：http://dali.daria6918.cn/Article/details/gthxrkfqdv.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.yvedp.cn/Article/details/gtgejgscmo.html

[S05] C：字符串长度
来源：http://dali.guannengcc.top/Article/details/gtsehoghzf.html

strlen(s)
来源：http://dali.cucudq.cn/Article/details/gtturpebsq.html

[S06] C：字符串比较
来源：http://dali.cdnleiting.top/Article/details/gtberknnrd.html

strcmp(a, b) == 0
来源：http://dali.andypj.xyz/Article/details/gtmnwjghiz.html

[S07] C：数组遍历求和
来源：http://dali.sxryk.cn/Article/details/gtbufltgxt.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.yangfankeji.com/Article/details/gttpcxhxlc.html

[S08] C：动态内存分配与释放
来源：http://dali.yangfankeji.com/Article/details/gtgonxrguy.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.nanxinkj.top/Article/details/gtwirjiwbo.html

[S09] C：结构体定义与初始化
来源：http://dali.zycfv.cn/Article/details/gtqoyusjdu.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.jlsjyb.cn/Article/details/gtroxnvcqu.html

[S10] C：指针与解引用
来源：http://dali.jyoumei.cn/Article/details/gtojasehee.html

int *p = &a;  *p = 5;
来源：http://dali.cheryme.top/Article/details/gtuiycxeag.html

[S11] C：逐行读文件
来源：http://dali.cucudq.cn/Article/details/gtcbccezox.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.ivvv.top/Article/details/gtguxiezfd.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.cdnleiting.top/Article/details/gtxbusflxv.html

fclose(f);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwquitkdw.html

[S12] C：写文件
来源：http://dali.yj20258.top/Article/details/gttkhmdtwa.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.yuxming.cn/Article/details/gtdybgnvls.html

[S13] C：宏定义
来源：http://dali.shanyushiyangtech.top/Article/details/gtcozowpyx.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.gogol.net.cn/Article/details/gtkkupgdhd.html

[S14] C：枚举
来源：http://dali.wangshuangyany.cn/Article/details/gtxjfuqckk.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.havefunace.top/Article/details/gtfxciokks.html

[S15] C：类型转换
来源：http://dali.hongshengwenyu.top/Article/details/gtyqnpqwjh.html

(double) a / b
来源：http://dali.ppjwa.cn/Article/details/gtcxrijltf.html

[S16] C：位操作置位
来源：http://dali.c1oappe.top/Article/details/gtdmhjuluc.html

x |= (1 << 3);
来源：http://dali.pycfn.com/Article/details/gtroslxswh.html

[S17] C：安全拼接字符串
来源：http://dali.cashguo.top/Article/details/gtrdodzamb.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.yj20258.top/Article/details/gthsivpzze.html

[S18] C：命令行参数
来源：http://dali.jinqigfzy.top/Article/details/gtkrxlhbkx.html

int main(int argc, char **argv)
来源：http://dali.yj202588.top/Article/details/gtahkfyiib.html

[S19] C：快速排序
来源：http://dali.smart0.xyz/Article/details/gtfmjwjvyi.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.yuanzhike.top/Article/details/gtafrpyzgw.html

[S20] C：二分查找
来源：http://dali.fzhhl.top/Article/details/gtughtuomw.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.havefunace.top/Article/details/gtgzmxkdqz.html

[S21] C：字符类别判断
来源：http://dali.xuanzx.com/Article/details/gttdfdgrnc.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.aizwys.cn/Article/details/gtqmkctjjg.html

[S22] C：字符串转数字
来源：http://dali.birdmap.top/Article/details/gtahtceofi.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.iojbl.cn/Article/details/gttomhpqzi.html

[S23] C：随机数
来源：http://dali.cdnleiting.top/Article/details/gtudwoywrp.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.svipenyu.cn/Article/details/gtovaqtztv.html

[S24] C：获取本地时间
来源：http://dali.aibaodan.cn/Article/details/gtjefqzkra.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.redwolf501.top/Article/details/gtjlmfiolj.html

[S25] C：内存拷贝
来源：http://dali.tanke756.top/Article/details/gttsbtmued.html

memcpy(dst, src, n);
来源：http://dali.xuanzx.com/Article/details/gtnkzbgwoa.html

[S26] C：内存清零
来源：http://dali.yongpay.top/Article/details/gtzvopbidw.html

memset(a, 0, sizeof a);
来源：http://dali.redwolf501.top/Article/details/gtqjmblipx.html

[S27] C：定义常量
来源：http://dali.chenjidiqi.icu/Article/details/gtqvbvlyqa.html

const double PI = 3.14159;
来源：http://dali.hammf.cn/Article/details/gtksutazis.html

[S28] C：静态变量
来源：http://dali.ydzc1.top/Article/details/gtrqmvhoag.html

static int counter = 0;
来源：http://dali.smart0.xyz/Article/details/gtwqfapqjk.html

[S29] C：变参函数
来源：http://dali.yongpay.top/Article/details/gtlljwvgcj.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhixingplan.top/Article/details/gtertezbxm.html

[S30] C：头文件保护
来源：http://dali.ywan-chungtsiang.top/Article/details/gtygxtepvu.html

#ifndef X_H
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzgvhngky.html

#define X_H
来源：http://dali.316326.xyz/Article/details/gtjsqkbwjl.html

#endif
来源：http://dali.guowangkeji.top/Article/details/gtrrcrzeke.html

[S31] C++：Hello World
来源：http://dali.cashguo.top/Article/details/gtrsntbgdo.html

#include <iostream>
来源：http://dali.zhengqikj.top/Article/details/gtmjotwmjx.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.feifeiyinyue.top/Article/details/gtjvflrunw.html

[S32] C++：字符串
来源：http://dali.jqgufenzy.top/Article/details/gtsyujothx.html

std::string s = "hi";  s += "!";
来源：http://dali.shangyingyoupin.top/Article/details/gtdzldxnlw.html

[S33] C++：vector 增删
来源：http://dali.aibaodan.cn/Article/details/gtzxddjjmz.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.yanxiufei.cn/Article/details/gtwnxauboc.html

[S34] C++：遍历 vector
来源：http://dali.dashuyun.cn/Article/details/gtprwkbbga.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.dianchejie.cn/Article/details/gtvocwtipq.html

[S35] C++：map
来源：http://dali.dianchejie.cn/Article/details/gtqcfywmhu.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yanxiufei.cn/Article/details/gttqbhjhnr.html

[S36] C++：unordered_map
来源：http://dali.ivvv.top/Article/details/gtvrewmhsm.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.cheryme.top/Article/details/gtyxcyscyw.html

[S37] C++：set
来源：http://dali.wangshuangyany.cn/Article/details/gtaugtiqde.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.guannengcc.top/Article/details/gtzujbxics.html

[S38] C++：排序
来源：http://dali.sysykeji.top/Article/details/gtwnwpqccy.html

std::sort(v.begin(), v.end());
来源：http://dali.jinghuilouyu.cn/Article/details/gtifznfzko.html

[S39] C++：自定义比较器排序
来源：http://dali.jqgufenzy.top/Article/details/gtbuayxfet.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.shangyingyoupin.top/Article/details/gtnmpzmkwa.html

[S40] C++：查找元素
来源：http://dali.dianchejie.cn/Article/details/gtqzhsqcik.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.guowangkeji.top/Article/details/gtgskxvlqt.html

[S41] C++：类与构造函数
来源：http://dali.c1oappe.top/Article/details/gtjbrohlxs.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.chenlongwang.top/Article/details/gtfhbhlwjr.html

[S42] C++：继承与虚函数
来源：http://dali.xuanzx.com/Article/details/gtwhullyti.html

class B : public Base { public: void f() override {} };
来源：http://dali.iojbl.cn/Article/details/gtfscznfxh.html

[S43] C++：智能指针
来源：http://dali.jyoumei.cn/Article/details/gtggnqzykk.html

auto p = std::make_unique<int>(5);
来源：http://dali.svipenyu.cn/Article/details/gtwhqzcyzo.html

[S44] C++：引用传参
来源：http://dali.sufxvd.cn/Article/details/gtkwdhejbv.html

void inc(int &x) { ++x; }
来源：http://dali.svipenyu.cn/Article/details/gtgktrccgm.html

[S45] C++：lambda
来源：http://dali.redwolf501.top/Article/details/gtkjhauvdi.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.sxryk.cn/Article/details/gtcrqdnjmr.html

[S46] C++：函数模板
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmkihakps.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.gzhubu.top/Article/details/gtbnukwzyg.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhiwuduotai.top/Article/details/gthmtlpnea.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.jqgufenzy.top/Article/details/gtopqlpqew.html

[S48] C++：逐行读文件
来源：http://dali.gaohongyu789.top/Article/details/gtreybdjrr.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.cashguo.top/Article/details/gtrezfiaoi.html

while (std::getline(in, line)) { }
来源：http://dali.ehwqpu.com/Article/details/gtjklkfqnw.html

[S49] C++：写文件
来源：http://dali.fengsongda.top/Article/details/gtjmfmibtq.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.quarkkingdee.top/Article/details/gthbvmruvb.html

[S50] C++：格式化数字
来源：http://dali.jinqigfzy.top/Article/details/gtoopevwuz.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.cqqwz.cn/Article/details/gtwvyuvdhc.html

[S51] C++：显式类型转换
来源：http://dali.pycfn.com/Article/details/gtujmfrgyz.html

static_cast<double>(a) / b
来源：http://dali.hfpthk.cn/Article/details/gtdnanghpb.html

[S52] C++：const 与 noexcept
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxkunfbcg.html

int size() const noexcept { return n_; }
来源：http://dali.nwbrower.top/Article/details/gtongvlnau.html

[S53] C++：移动语义
来源：http://dali.ybcxt.top/Article/details/gtiwpoxjhz.html

std::vector<int> w = std::move(v);
来源：http://dali.zhengqikj.top/Article/details/gtsebbqkqg.html

[S54] C++：异常处理
来源：http://dali.chenzaomai.com/Article/details/gtmmlguqgj.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zycfv.cn/Article/details/gtxzoffylu.html

[S55] C++：结构化绑定
来源：http://dali.havefunace.top/Article/details/gtggoinniq.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.yongpay.top/Article/details/gtdhxaucnz.html

[S56] C++：optional
来源：http://dali.hywenlv.cn/Article/details/gtfkmlusvs.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.sweek.top/Article/details/gtlnfuwroc.html

[S57] C++：编译期常量
来源：http://dali.dashuyun.cn/Article/details/gtvhratcte.html

constexpr int N = 10;
来源：http://dali.xuanzx.com/Article/details/gtxncpfmsx.html

[S58] C++：命名空间
来源：http://dali.zhoulong.xyz/Article/details/gtlzycjbaz.html

namespace ns { int f() { return 1; } }
来源：http://dali.cdnleiting.top/Article/details/gtidrcpgoi.html

[S59] C++：静态断言
来源：http://dali.yonumen.top/Article/details/gtayjhbjxa.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.jqgfzy.top/Article/details/gtxbqjoxqz.html

[S60] C++：遍历并删除元素
来源：http://dali.xinyue.icu/Article/details/gtsqxfrnfr.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.wangshuangyany.cn/Article/details/gtujcpfwjy.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtbkmckpvr.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.wangdashe.top/Article/details/gtbyjqjhiq.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtsshmrpta.html

[T01] Kotlin：Hello World
来源：http://dali.yj202588.top/Article/details/gtagrhxycn.html

println("Hello")
来源：http://dali.kuanghao11.cn/Article/details/gtysxobwcg.html

[T02] Kotlin：变量
来源：http://dali.ehwqpu.com/Article/details/gtshchscuq.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.daria6918.cn/Article/details/gthpcoewuu.html

[T03] Kotlin：字符串模板
来源：http://dali.yj20258888.top/Article/details/gthyhtafcc.html

"值: $b"
来源：http://dali.hywenlv.cn/Article/details/gtlspbzyak.html

[T04] Kotlin：空安全
来源：http://dali.xinyue.icu/Article/details/gtezibswdh.html

val n: String? = null;  n?.length
来源：http://dali.wangshuangyany.cn/Article/details/gtzbnsynjs.html

[T05] Kotlin：when 表达式
来源：http://dali.aibaodan.cn/Article/details/gtycxqbnhr.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.yongpay.top/Article/details/gtxqpsejfq.html

[T06] Kotlin：集合映射
来源：http://dali.jqgufenzy.top/Article/details/gtlpizclml.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.yongpay.top/Article/details/gtxtyucmdp.html

[T07] Kotlin：集合过滤
来源：http://dali.hysaishi.cn/Article/details/gtktfqqucu.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.feifeiyinyue.top/Article/details/gtmbgwpfgp.html

[T08] Kotlin：数据类
来源：http://dali.aibaodan.cn/Article/details/gtlxwpbrzr.html

data class User(val name: String, val age: Int)
来源：http://dali.feifeiyinyue.top/Article/details/gtgbmtkhpy.html

[T09] Kotlin：扩展函数
来源：http://dali.mhx1999.top/Article/details/gtnappcgtn.html

fun String.exclaim() = this + "!"
来源：http://dali.hammf.cn/Article/details/gttmtbvfva.html

[T10] Kotlin：默认参数
来源：http://dali.zycfv.cn/Article/details/gtcmoblbwi.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.jianghu66.top/Article/details/gtwlwzripn.html

[T11] Kotlin：协程
来源：http://dali.jinqigfzy.top/Article/details/gtyziewjny.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.yangfankeji.com/Article/details/gtswvpvgsa.html

[T12] Kotlin：解构声明
来源：http://dali.ivvv.top/Article/details/gtjixifwqh.html

val (a, b) = Pair(1, 2)
来源：http://dali.wangdashe.top/Article/details/gtygvgoqbv.html

[T13] Kotlin：只读 Map
来源：http://dali.feifeiyinyue.top/Article/details/gtblczgdxe.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gtrorilmqw.html

[T14] Kotlin：循环
来源：http://dali.c1oappe.top/Article/details/gtuigxoypj.html

for (i in 1..10) println(i)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkauqtdhm.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gtprbrhxuj.html

interface Shape { fun area(): Double }
来源：http://dali.jqgufenzy.top/Article/details/gtmwjayili.html

[T16] Swift：Hello World
来源：http://dali.yonumen.top/Article/details/gtjgjhclcm.html

print("Hello")
来源：http://dali.snrcjt.cn/Article/details/gtghbxfnfg.html

[T17] Swift：变量与常量
来源：http://dali.xylfe.cn/Article/details/gttzkmlzwz.html

var a = 1;  let b = 2
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcootcxvv.html

[T18] Swift：字符串插值
来源：http://dali.cdnleiting.top/Article/details/gtmydfmjtw.html

"值: \(b)"
来源：http://dali.aizwys.cn/Article/details/gtkfnyfvaa.html

[T19] Swift：可选绑定
来源：http://dali.pengpengdd.cyou/Article/details/gtmihknozn.html

if let n = opt { print(n) }
来源：http://dali.ybcxt.top/Article/details/gtfweurzle.html

[T20] Swift：数组操作
来源：http://dali.chenjidiqi.icu/Article/details/gtoyiojmaa.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.ivvv.top/Article/details/gtgbjstqiw.html

[T21] Swift：遍历
来源：http://dali.zycfv.cn/Article/details/gthtippozu.html

for x in a { print(x) }
来源：http://dali.ivvv.top/Article/details/gttrjqtccq.html

[T22] Swift：字典
来源：http://dali.yueranfly.top/Article/details/gtywasuexo.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.jiagoushi.top/Article/details/gturbcaejn.html

[T23] Swift：函数
来源：http://dali.jinqigufen.top/Article/details/gtezcvlfnl.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.chenlongwang.top/Article/details/gtpdqztaya.html

[T24] Swift：闭包
来源：http://dali.wangshuangyany.cn/Article/details/gtrtgvtrtm.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.snrcjt.cn/Article/details/gtonhuaugs.html

[T25] Swift：结构体
来源：http://dali.jinghuilouyu.cn/Article/details/gtssqjrflm.html

struct P { var x: Int }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxblxgplk.html

[T26] Swift：类与重写
来源：http://dali.yuanzhike.top/Article/details/gteskgnmgp.html

class A: Base { override func f() {} }
来源：http://dali.aizwys.cn/Article/details/gtitkvokou.html

[T27] Swift：错误处理
来源：http://dali.andypj.xyz/Article/details/gtzymocmsu.html

do { try f() } catch { print(error) }
来源：http://dali.shzxlz.cn/Article/details/gtnqddcjuj.html

[T28] Swift：枚举
来源：http://dali.wangdashe.top/Article/details/gtmgnmhpwz.html

enum Color { case red, green }
来源：http://dali.jiagoushi.top/Article/details/gtzboyqroa.html

[T29] Swift：guard 提前返回
来源：http://dali.wangshuangyany.cn/Article/details/gteizjxlqu.html

guard let x = opt else { return }
来源：http://dali.tanke756.top/Article/details/gtdhhmhtia.html

[T30] Swift：协议
来源：http://dali.sxryk.cn/Article/details/gtoqhnnadk.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gtvbuvaodu.html

[T31] Lua：Hello World
来源：http://dali.gotoacloud.top/Article/details/gtouwfafvg.html

print("Hello")
来源：http://dali.cucudq.cn/Article/details/gtfooowkza.html

[T32] Lua：局部变量
来源：http://dali.jianghu66.top/Article/details/gtsobulxum.html

local a = 1
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnpjcxzwa.html

[T33] Lua：表（数组）
来源：http://dali.yj20258888.top/Article/details/gtxzhxizus.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.svipenyu.cn/Article/details/gtjxmzyljx.html

[T34] Lua：遍历表
来源：http://dali.andypj.xyz/Article/details/gtfawanecl.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhiwuduotai.top/Article/details/gttvhbgldk.html

[T35] Lua：字典表
来源：http://dali.mhx1999.top/Article/details/gttervwjxt.html

local d = { a = 1 };  d.b = 2
来源：http://dali.cqqwz.cn/Article/details/gtvauucroo.html

[T36] Lua：函数
来源：http://dali.ybcxt.top/Article/details/gtawdkhkxv.html

function add(a, b) return a + b end
来源：http://dali.sufxvd.cn/Article/details/gteanyiqhq.html

[T37] Lua：字符串拼接
来源：http://dali.cdnleiting.top/Article/details/gtngfwcafn.html

"a" .. "b"
来源：http://dali.daxiang520.top/Article/details/gtcdgxeehl.html

[T38] Lua：条件
来源：http://dali.yueranfly.top/Article/details/gtcgqturda.html

if x > 0 then print("正") end
来源：http://dali.yuanzhike.top/Article/details/gtqvoxqkww.html

[T39] Lua：模式匹配
来源：http://dali.ydzc1.top/Article/details/gtfsainzzv.html

string.find(s, "%d+")
来源：http://dali.gzhubu.top/Article/details/gtzddbntvm.html

[T40] Lua：元表
来源：http://dali.9152youxi.cn/Article/details/gtfoqwxnxx.html

setmetatable({}, { __index = base })
来源：http://dali.jianghu66.top/Article/details/gtcspmbnys.html

[T41] Perl：Hello World
来源：http://dali.andypj.xyz/Article/details/gtvebqnsrt.html

print "Hello\n";
来源：http://dali.yangfankeji.com/Article/details/gttgddtvac.html

[T42] Perl：变量类型
来源：http://dali.0kj1m.cn/Article/details/gtnkpqwmev.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.jlsjyb.cn/Article/details/gtyotdckop.html

[T43] Perl：字符串插值
来源：http://dali.aizwys.cn/Article/details/gtdizbyslr.html

"值: $a"
来源：http://dali.yuxming.cn/Article/details/gtmnxntutr.html

[T44] Perl：条件
来源：http://dali.wangdashe.top/Article/details/gtlhmdrmnc.html

if ($a > 0) { print "正"; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgvxzfsjl.html

[T45] Perl：数组遍历
来源：http://dali.xinyue.icu/Article/details/gtwthmdfzi.html

for my $x (@arr) { print $x; }
来源：http://dali.birdmap.top/Article/details/gtrblpytad.html

[T46] Perl：哈希操作
来源：http://dali.hongshengwenyu.top/Article/details/gtrbaewnzm.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsmieespx.html

[T47] Perl：正则捕获
来源：http://dali.tian-w.cn/Article/details/gtdfrzwxfv.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.shzxlz.cn/Article/details/gtahxyeuin.html

[T48] Perl：正则替换
来源：http://dali.vqdsnc.cn/Article/details/gtpqheufvk.html

$s =~ s/old/new/g;
来源：http://dali.316326.xyz/Article/details/gthyncerrk.html

[T49] Perl：函数
来源：http://dali.yueranfly.top/Article/details/gtopmdtisx.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.iojbl.cn/Article/details/gtneieccue.html

[T50] Perl：逐行读文件
来源：http://dali.andypj.xyz/Article/details/gtrfnslntx.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.sweek.top/Article/details/gtbfmetmdx.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.ivvv.top/Article/details/gtbrvtsaqa.html

[T51] Scala：Hello World
来源：http://dali.sxryk.cn/Article/details/gtrhfpqago.html

println("Hello")
来源：http://dali.tanke756.top/Article/details/gtvdmhwrux.html

[T52] Scala：变量
来源：http://dali.chenlongwang.top/Article/details/gtjdweqjbu.html

val a = 1;  var b = 2
来源：http://dali.ydzc1.top/Article/details/gtejbzwtps.html

[T53] Scala：字符串插值
来源：http://dali.jqgfzy.top/Article/details/gttfyvwtmj.html

s"值: $b"
来源：http://dali.tanke756.top/Article/details/gtoxywielz.html

[T54] Scala：集合映射
来源：http://dali.zycfv.cn/Article/details/gtjnezwufz.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.haohaochexian.top/Article/details/gtgkjxtacp.html

[T55] Scala：集合过滤
来源：http://dali.chenjidiqi.icu/Article/details/gtztgtlpps.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.sufxvd.cn/Article/details/gtfzjmbvbo.html

[T56] Scala：样例类
来源：http://dali.ybcxt.top/Article/details/gtwxvuoagm.html

case class User(name: String, age: Int)
来源：http://dali.tanke756.top/Article/details/gtqzlowiqk.html

[T57] Scala：模式匹配
来源：http://dali.yvedp.cn/Article/details/gtthduogbc.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.cdnleiting.top/Article/details/gtfhjffude.html

[T58] Scala：函数定义
来源：http://dali.yanxiufei.cn/Article/details/gtmrrfkbvu.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.cucudq.cn/Article/details/gteekjqubm.html

[T59] Scala：循环
来源：http://dali.yongpay.top/Article/details/gtvnmlfupp.html

for (i <- 1 to 10) println(i)
来源：http://dali.cqqwz.cn/Article/details/gtlwmyewxe.html

[T60] Scala：折叠
来源：http://dali.hnqzz.top/Article/details/gtdyqlbcck.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.yj20258888.top/Article/details/gtrcmvxfui.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtzbrqvenw.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.jiagoushi.top/Article/details/gtnxnbsdom.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtyzaaessl.html

[U01] Py：创建虚拟环境
来源：http://dali.9152youxi.cn/Article/details/gtqezupzzc.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.hnxiangtu.top/Article/details/gtadswayvg.html

[U02] Py：导出 / 安装依赖
来源：http://dali.bjfxy.top/Article/details/gtuvsktipk.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.gotoacloud.top/Article/details/gtctabhzzi.html

[U03] Py：加载 .env 配置
来源：http://dali.haohaochexian.top/Article/details/gtyfzcylat.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.sufxvd.cn/Article/details/gtkmzkmtbi.html

[U04] Py：变量调试打印
来源：http://dali.wangshuangyany.cn/Article/details/gtccuyweni.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.hnqzz.top/Article/details/gttklgduxw.html


<!-- 参考信息 -->