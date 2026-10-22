代发 wailian999

df -h;  du -sh *
来源：http://dali.kuanghao11.cn/Article/details/gtjbkicgcz.html

[R62] 找最占空间的文件
来源：http://dali.hywenlv.cn/Article/details/gtdtnrmpln.html

du -ah . | sort -rh | head -10
来源：http://dali.quarkkingdee.top/Article/details/gtvpqegyah.html

[R63] 内存与进程
来源：http://dali.chenzaomai.com/Article/details/gtwmvdziqv.html

free -h;  ps aux | grep nginx
来源：http://dali.yj20258888.top/Article/details/gtuzpljgqx.html

[R64] 结束进程
来源：http://dali.redwolf501.top/Article/details/gtrqmxjrin.html

kill -9 $(pgrep -f app.py)
来源：http://dali.cheryme.top/Article/details/gtbfecysyz.html

[R65] 查看端口占用
来源：http://dali.xinyue.icu/Article/details/gtluduvmox.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.tianlin.xyz/Article/details/gtrhxfgvig.html

[R66] 定时任务
来源：http://dali.yuanzhike.top/Article/details/gtnvgkuyoq.html

crontab -e;  crontab -l
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvnzpsvic.html

[R67] 生成随机十六进制串
来源：http://dali.bjfxy.top/Article/details/gtrirhichw.html

openssl rand -hex 16
来源：http://dali.kuanghao11.cn/Article/details/gteneircmd.html

[R68] 计算文件校验值
来源：http://dali.quarkkingdee.top/Article/details/gtqnpkfhus.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.sweek.top/Article/details/gtfzlcpugr.html

[R69] 生成随机密码
来源：http://dali.chenjidiqi.icu/Article/details/gtgqpezibv.html

head -c 16 /dev/urandom | base64
来源：http://dali.bjfxy.top/Article/details/gtpwiycnrt.html

[R70] 时间戳与互转
来源：http://dali.ybcxt.top/Article/details/gtoqnaqmuk.html

date +%s;  date -d @1700000000
来源：http://dali.ehwqpu.com/Article/details/gtfvhnvhyo.html

[R71] 日期格式化
来源：http://dali.yangfankeji.com/Article/details/gtgdwhvqrc.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.yonumen.top/Article/details/gtdcrzmctf.html

[R72] 等待端口就绪
来源：http://dali.c1oappe.top/Article/details/gtlpcjrptd.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.yonumen.top/Article/details/gtugwkueft.html

[R73] 分割大日志
来源：http://dali.meibo888.top/Article/details/gtvyqwhdlj.html

split -l 1000 big.log part_
来源：http://dali.redwolf501.top/Article/details/gteacthhzq.html

[R74] 批量重命名
来源：http://dali.shzxlz.cn/Article/details/gtexihillx.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.yanxiufei.cn/Article/details/gtvmlkodfy.html

[R75] 导出环境变量
来源：http://dali.iojbl.cn/Article/details/gtbebpssus.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.kuanghao11.cn/Article/details/gtwhfwszhl.html

[R76] 使用临时文件
来源：http://dali.yueranfly.top/Article/details/gtnnvoxgun.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.hnqzz.top/Article/details/gtrrpkgtox.html

[R77] 读取用户输入
来源：http://dali.cashguo.top/Article/details/gtcclxdwzq.html

read -rp "请输入: " ans
来源：http://dali.nwbrower.top/Article/details/gtdmnnehnh.html

[R78] 交互式菜单
来源：http://dali.cdnleiting.top/Article/details/gtcletvslt.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.tianlin.xyz/Article/details/gtgrsgqhrg.html

[R79] 解析命令行选项
来源：http://dali.zdqjudy.top/Article/details/gtthbyqxxy.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.yj20258888.top/Article/details/gtwbkuvcni.html

[R80] 查看脚本执行耗时
来源：http://dali.xziqi.cn/Article/details/gtddbdtktd.html

time ./run.sh
来源：http://dali.dianchejie.cn/Article/details/gtldpfwkcd.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtoodobcwl.html

S. C / C++ 专题
来源：http://dali.yj20258888.top/Article/details/gtqfyqzmhe.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtdfglawem.html

[S01] C：Hello World
来源：http://dali.ywan-chungtsiang.top/Article/details/gttjnotpfz.html

#include <stdio.h>
来源：http://dali.chenzaomai.com/Article/details/gttdayubuq.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.cashguo.top/Article/details/gtwhnaspsc.html

[S02] C：变量与格式化输出
来源：http://dali.9152youxi.cn/Article/details/gtewmxwpwy.html

int a = 10; printf("%d\n", a);
来源：http://dali.xinyue.icu/Article/details/gtfcqgjibr.html

[S03] C：读入整数
来源：http://dali.sysykeji.top/Article/details/gtshrkrmvz.html

int x; scanf("%d", &x);
来源：http://dali.yangfankeji.com/Article/details/gtcymllelq.html

[S04] C：字符串复制
来源：http://dali.cucudq.cn/Article/details/gtxcdupnko.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.mhx1999.top/Article/details/gtsbngseob.html

[S05] C：字符串长度
来源：http://dali.feifeiyinyue.top/Article/details/gtulldttdm.html

strlen(s)
来源：http://dali.hysaishi.cn/Article/details/gtqhbvwngi.html

[S06] C：字符串比较
来源：http://dali.ydzc1.top/Article/details/gtsgkkrrld.html

strcmp(a, b) == 0
来源：http://dali.yj20258888.top/Article/details/gtrwkrdfvr.html

[S07] C：数组遍历求和
来源：http://dali.hammf.cn/Article/details/gtffgpgaka.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.daxiang520.top/Article/details/gthxglghte.html

[S08] C：动态内存分配与释放
来源：http://dali.iojbl.cn/Article/details/gtvlwglpwl.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.shzxlz.cn/Article/details/gtcvgggwof.html

[S09] C：结构体定义与初始化
来源：http://dali.snrcjt.cn/Article/details/gtsydyuaba.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.yj20258.top/Article/details/gtlspgreav.html

[S10] C：指针与解引用
来源：http://dali.c1oappe.top/Article/details/gthfcnvjch.html

int *p = &a;  *p = 5;
来源：http://dali.yuanzhike.top/Article/details/gtvxytipob.html

[S11] C：逐行读文件
来源：http://dali.jianghu66.top/Article/details/gtqjjiawzn.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.yonumen.top/Article/details/gtinywusta.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.svipenyu.cn/Article/details/gtiyhcqksl.html

fclose(f);
来源：http://dali.birdmap.top/Article/details/gtukvnkhtt.html

[S12] C：写文件
来源：http://dali.iojbl.cn/Article/details/gtxhnuknqb.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.tanke756.top/Article/details/gtvtbbprku.html

[S13] C：宏定义
来源：http://dali.xylfe.cn/Article/details/gtzwjogktt.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.shanyushiyangtech.top/Article/details/gtexgondaa.html

[S14] C：枚举
来源：http://dali.yongpay.top/Article/details/gtofufqeok.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.ybcxt.top/Article/details/gtxurchhxr.html

[S15] C：类型转换
来源：http://dali.yuanzhike.top/Article/details/gtnjbwjqtp.html

(double) a / b
来源：http://dali.cheryme.top/Article/details/gtvfkbzjkc.html

[S16] C：位操作置位
来源：http://dali.shanyushiyangtech.top/Article/details/gtqmhmnonr.html

x |= (1 << 3);
来源：http://dali.tanke756.top/Article/details/gtwdvkodyw.html

[S17] C：安全拼接字符串
来源：http://dali.shzxlz.cn/Article/details/gtltfoqmyu.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.yangfankeji.com/Article/details/gtpfmvhecr.html

[S18] C：命令行参数
来源：http://dali.nanxinkj.top/Article/details/gtiyiszhwt.html

int main(int argc, char **argv)
来源：http://dali.yongpay.top/Article/details/gtqvsmhwnp.html

[S19] C：快速排序
来源：http://dali.ybcxt.top/Article/details/gtbkqukvcr.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.fengsongda.top/Article/details/gtxueaxsij.html

[S20] C：二分查找
来源：http://dali.jlsjyb.cn/Article/details/gtnphucucy.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.havefunace.top/Article/details/gtggdpzzph.html

[S21] C：字符类别判断
来源：http://dali.chenjidiqi.icu/Article/details/gtbbzrficn.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.hfpthk.cn/Article/details/gtjnagdehu.html

[S22] C：字符串转数字
来源：http://dali.yueranfly.top/Article/details/gtigqzkcfj.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.pycfn.com/Article/details/gtmxrzbgnl.html

[S23] C：随机数
来源：http://dali.fzhhl.top/Article/details/gtlxbjagbn.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.pycfn.com/Article/details/gtixildbgd.html

[S24] C：获取本地时间
来源：http://dali.cucudq.cn/Article/details/gtaicwgbkk.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.cqqwz.cn/Article/details/gthjjlptlg.html

[S25] C：内存拷贝
来源：http://dali.aizwys.cn/Article/details/gtzngqizkz.html

memcpy(dst, src, n);
来源：http://dali.nwbrower.top/Article/details/gtsxalohuy.html

[S26] C：内存清零
来源：http://dali.svipenyu.cn/Article/details/gtlngzffjy.html

memset(a, 0, sizeof a);
来源：http://dali.hfpthk.cn/Article/details/gtycgsumbp.html

[S27] C：定义常量
来源：http://dali.xziqi.cn/Article/details/gtwifcolca.html

const double PI = 3.14159;
来源：http://dali.jinqigufen.top/Article/details/gtalanbpjz.html

[S28] C：静态变量
来源：http://dali.cqqwz.cn/Article/details/gtaovjqenp.html

static int counter = 0;
来源：http://dali.nanxinkj.top/Article/details/gtrkekivop.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gtsnddzkft.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.xinyue.icu/Article/details/gtbekjlvvf.html

[S30] C：头文件保护
来源：http://dali.hongshengwenyu.top/Article/details/gthrfxcnkw.html

#ifndef X_H
来源：http://dali.mhx1999.top/Article/details/gtlocylvvm.html

#define X_H
来源：http://dali.aibaodan.cn/Article/details/gtlsqppitt.html

#endif
来源：http://dali.hywenlv.cn/Article/details/gtwwgcvxrk.html

[S31] C++：Hello World
来源：http://dali.jinghuilouyu.cn/Article/details/gtqywapvrh.html

#include <iostream>
来源：http://dali.redwolf501.top/Article/details/gtmoivpvaa.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhiwuduotai.top/Article/details/gtipnupxof.html

[S32] C++：字符串
来源：http://dali.shanyushiyangkeji.top/Article/details/gtklrykmfx.html

std::string s = "hi";  s += "!";
来源：http://dali.daxiang520.top/Article/details/gtjkplmvln.html

[S33] C++：vector 增删
来源：http://dali.snrcjt.cn/Article/details/gtfckxcbtw.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.jqgfzy.top/Article/details/gtubocyzhz.html

[S34] C++：遍历 vector
来源：http://dali.cheryme.top/Article/details/gtuewybvod.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.aizwys.cn/Article/details/gtanhtlqkr.html

[S35] C++：map
来源：http://dali.redwolf501.top/Article/details/gtqznytcrb.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.ybcxt.top/Article/details/gtpdndowbg.html

[S36] C++：unordered_map
来源：http://dali.9152youxi.cn/Article/details/gtbvwgcjuq.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.cashguo.top/Article/details/gtldkzeawc.html

[S37] C++：set
来源：http://dali.ybcxt.top/Article/details/gtrglfaksn.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.wangshuangyany.cn/Article/details/gttmvqadqb.html

[S38] C++：排序
来源：http://dali.hammf.cn/Article/details/gtfbyzpzbv.html

std::sort(v.begin(), v.end());
来源：http://dali.aizwys.cn/Article/details/gtbllmixhy.html

[S39] C++：自定义比较器排序
来源：http://dali.zhixingplan.top/Article/details/gtcivbbnva.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.yvedp.cn/Article/details/gtmxwgjsfw.html

[S40] C++：查找元素
来源：http://dali.aizwys.cn/Article/details/gtudkckrqt.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.gotoacloud.top/Article/details/gtofebvsxo.html

[S41] C++：类与构造函数
来源：http://dali.jinghuilouyu.cn/Article/details/gtywdgrvft.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.feifeiyinyue.top/Article/details/gtgmnzswgr.html

[S42] C++：继承与虚函数
来源：http://dali.vqdsnc.cn/Article/details/gtirbtngkn.html

class B : public Base { public: void f() override {} };
来源：http://dali.jianghu66.top/Article/details/gtkjbhjyae.html

[S43] C++：智能指针
来源：http://dali.xziqi.cn/Article/details/gtpwqgbcet.html

auto p = std::make_unique<int>(5);
来源：http://dali.yuxming.cn/Article/details/gtcvfxglqx.html

[S44] C++：引用传参
来源：http://dali.yueranfly.top/Article/details/gthjctxcdm.html

void inc(int &x) { ++x; }
来源：http://dali.yangfankeji.com/Article/details/gtiydnxtca.html

[S45] C++：lambda
来源：http://dali.wangshuangyany.cn/Article/details/gthqtxweml.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.fengsongda.top/Article/details/gtwitwkevh.html

[S46] C++：函数模板
来源：http://dali.cheryme.top/Article/details/gtrafkyisz.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaotjncxo.html

[S47] C++：结构化绑定遍历
来源：http://dali.ppjwa.cn/Article/details/gtaunxxbfp.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.vqdsnc.cn/Article/details/gtafurpmnn.html

[S48] C++：逐行读文件
来源：http://dali.bjfxy.top/Article/details/gtziewblak.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.ydzc1.top/Article/details/gtyjibddqg.html

while (std::getline(in, line)) { }
来源：http://dali.wangshuangyany.cn/Article/details/gtvhiwachg.html

[S49] C++：写文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtffuaqhpg.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zdqjudy.top/Article/details/gtxqtohlqj.html

[S50] C++：格式化数字
来源：http://dali.cucudq.cn/Article/details/gtysfrmciz.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.jianghu66.top/Article/details/gtmwcspvcz.html

[S51] C++：显式类型转换
来源：http://dali.iojbl.cn/Article/details/gtsceeawmj.html

static_cast<double>(a) / b
来源：http://dali.gaohongyu789.top/Article/details/gtqozqaxye.html

[S52] C++：const 与 noexcept
来源：http://dali.gotoacloud.top/Article/details/gteosedppw.html

int size() const noexcept { return n_; }
来源：http://dali.xziqi.cn/Article/details/gtcstqrhej.html

[S53] C++：移动语义
来源：http://dali.316326.xyz/Article/details/gtvyaiaqdx.html

std::vector<int> w = std::move(v);
来源：http://dali.cucudq.cn/Article/details/gtyakyfswk.html

[S54] C++：异常处理
来源：http://dali.tianlin.xyz/Article/details/gtlmsajlom.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.svipenyu.cn/Article/details/gtgdiawzti.html

[S55] C++：结构化绑定
来源：http://dali.dashuyun.cn/Article/details/gtjimamhuz.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gttbggibjq.html

[S56] C++：optional
来源：http://dali.cdnleiting.top/Article/details/gtavrhfxoq.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.316326.xyz/Article/details/gtxvdxtsnr.html

[S57] C++：编译期常量
来源：http://dali.yj20258888.top/Article/details/gtohhbjlor.html

constexpr int N = 10;
来源：http://dali.dianchejie.cn/Article/details/gtnoxnabxh.html

[S58] C++：命名空间
来源：http://dali.nanxinkj.top/Article/details/gtyxxfimhj.html

namespace ns { int f() { return 1; } }
来源：http://dali.xuetiantiany.cn/Article/details/gtgxdpmgkk.html

[S59] C++：静态断言
来源：http://dali.hammf.cn/Article/details/gtmukxutyb.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.sweek.top/Article/details/gtrkysiffe.html

[S60] C++：遍历并删除元素
来源：http://dali.andypj.xyz/Article/details/gtfbkwveaf.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.xinyue.icu/Article/details/gtzbxuymmr.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtdllyvgsd.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.bjfxy.top/Article/details/gtczbaplhl.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrgvfxlgr.html

[T01] Kotlin：Hello World
来源：http://dali.cqqwz.cn/Article/details/gtkichymmg.html

println("Hello")
来源：http://dali.hammf.cn/Article/details/gtyohwbklj.html

[T02] Kotlin：变量
来源：http://dali.xziqi.cn/Article/details/gtzppaldxl.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.yuanzhike.top/Article/details/gtikcrdxmv.html

[T03] Kotlin：字符串模板
来源：http://dali.mhx1999.top/Article/details/gtlnkfkioe.html

"值: $b"
来源：http://dali.feifeiyinyue.top/Article/details/gtqinqennx.html

[T04] Kotlin：空安全
来源：http://dali.shanyushiyangtech.top/Article/details/gtxbufnboi.html

val n: String? = null;  n?.length
来源：http://dali.birdmap.top/Article/details/gtchdlqscg.html

[T05] Kotlin：when 表达式
来源：http://dali.jinghuilouyu.cn/Article/details/gtqghvhibc.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.tanke756.top/Article/details/gtaeaxevsr.html

[T06] Kotlin：集合映射
来源：http://dali.shangyingyoupin.top/Article/details/gtwpptshoi.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.jinghuilouyu.cn/Article/details/gtvszaskbp.html

[T07] Kotlin：集合过滤
来源：http://dali.shanyushiyangkeji.top/Article/details/gtismhsdef.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.tanke756.top/Article/details/gttkhiurod.html

[T08] Kotlin：数据类
来源：http://dali.zhiwuduotai.top/Article/details/gtohqwjpvx.html

data class User(val name: String, val age: Int)
来源：http://dali.sweek.top/Article/details/gthsmuttjp.html

[T09] Kotlin：扩展函数
来源：http://dali.yueranfly.top/Article/details/gtnyrajbho.html

fun String.exclaim() = this + "!"
来源：http://dali.sxryk.cn/Article/details/gtqbmsvawa.html

[T10] Kotlin：默认参数
来源：http://dali.jinqigfzy.top/Article/details/gtxutazgjb.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zdqjudy.top/Article/details/gtrcyxeknl.html

[T11] Kotlin：协程
来源：http://dali.havefunace.top/Article/details/gtkrfitpod.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.yj20258.top/Article/details/gtyzzgehno.html

[T12] Kotlin：解构声明
来源：http://dali.hongshengwenyu.top/Article/details/gtqdjnkynf.html

val (a, b) = Pair(1, 2)
来源：http://dali.vqdsnc.cn/Article/details/gtjjhvbeet.html

[T13] Kotlin：只读 Map
来源：http://dali.guannengcc.top/Article/details/gtgauqiqdd.html

val m = mapOf("a" to 1)
来源：http://dali.zycfv.cn/Article/details/gtgxeeaaie.html

[T14] Kotlin：循环
来源：http://dali.ppjwa.cn/Article/details/gtxxuyntve.html

for (i in 1..10) println(i)
来源：http://dali.yanxiufei.cn/Article/details/gtxqedlyks.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gtxephkwqt.html

interface Shape { fun area(): Double }
来源：http://dali.yj202588.top/Article/details/gtkgylnahm.html

[T16] Swift：Hello World
来源：http://dali.zhengqikj.top/Article/details/gtfkuubxvf.html

print("Hello")
来源：http://dali.jinqigufen.top/Article/details/gtjkeskgdx.html

[T17] Swift：变量与常量
来源：http://dali.sxryk.cn/Article/details/gtkfzlyaei.html

var a = 1;  let b = 2
来源：http://dali.hongshengwenyu.top/Article/details/gtcedzuopr.html

[T18] Swift：字符串插值
来源：http://dali.pengpengdd.cyou/Article/details/gtnezmlywi.html

"值: \(b)"
来源：http://dali.shanyushiyangtech.top/Article/details/gtydghjwgt.html

[T19] Swift：可选绑定
来源：http://dali.birdmap.top/Article/details/gtvjpuwlza.html

if let n = opt { print(n) }
来源：http://dali.quarkkingdee.top/Article/details/gtfmjqvxvv.html

[T20] Swift：数组操作
来源：http://dali.snrcjt.cn/Article/details/gthjyjsrer.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.havefunace.top/Article/details/gthfqwhfaf.html

[T21] Swift：遍历
来源：http://dali.cqqwz.cn/Article/details/gtkkjennai.html

for x in a { print(x) }
来源：http://dali.jiagoushi.top/Article/details/gtijsghhzk.html

[T22] Swift：字典
来源：http://dali.zhoulong.xyz/Article/details/gtlmzgqvzk.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.svipenyu.cn/Article/details/gtgmkdxrtf.html

[T23] Swift：函数
来源：http://dali.feifeiyinyue.top/Article/details/gtrddifuyt.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.ivvv.top/Article/details/gtkreorooq.html

[T24] Swift：闭包
来源：http://dali.sxryk.cn/Article/details/gtiypwwhwv.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.hywenlv.cn/Article/details/gthlhihjhn.html

[T25] Swift：结构体
来源：http://dali.snrcjt.cn/Article/details/gtmckygusy.html

struct P { var x: Int }
来源：http://dali.xziqi.cn/Article/details/gtbrvkiaps.html

[T26] Swift：类与重写
来源：http://dali.guannengcc.top/Article/details/gtrlddjrwk.html

class A: Base { override func f() {} }
来源：http://dali.birdmap.top/Article/details/gtmffscfbr.html

[T27] Swift：错误处理
来源：http://dali.chenlongwang.top/Article/details/gtearlesyh.html

do { try f() } catch { print(error) }
来源：http://dali.shanyushiyangkeji.top/Article/details/gttscphhjw.html

[T28] Swift：枚举
来源：http://dali.birdmap.top/Article/details/gtxniqsedx.html

enum Color { case red, green }
来源：http://dali.chenjidiqi.icu/Article/details/gtldmvsrmt.html

[T29] Swift：guard 提前返回
来源：http://dali.wangshuangyany.cn/Article/details/gtxsupwalt.html

guard let x = opt else { return }
来源：http://dali.cashguo.top/Article/details/gtmxmempwe.html

[T30] Swift：协议
来源：http://dali.tian-w.cn/Article/details/gtscucffbv.html

protocol Shape { func area() -> Double }
来源：http://dali.ydzc1.top/Article/details/gtseadhwfp.html

[T31] Lua：Hello World
来源：http://dali.jinghuilouyu.cn/Article/details/gtvykzvgbd.html

print("Hello")
来源：http://dali.ybcxt.top/Article/details/gtoqxvdplo.html

[T32] Lua：局部变量
来源：http://dali.havefunace.top/Article/details/gthfvenlse.html

local a = 1
来源：http://dali.chenjidiqi.icu/Article/details/gtbzjgvbho.html

[T33] Lua：表（数组）
来源：http://dali.wangdashe.top/Article/details/gtyufkfhid.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.feifeiyinyue.top/Article/details/gtafyvhjfx.html

[T34] Lua：遍历表
来源：http://dali.sweek.top/Article/details/gtvgenpttz.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.mhx1999.top/Article/details/gtgctgbiqq.html

[T35] Lua：字典表
来源：http://dali.gaohongyu789.top/Article/details/gtryhicnss.html

local d = { a = 1 };  d.b = 2
来源：http://dali.fengsongda.top/Article/details/gtcnudxnuh.html

[T36] Lua：函数
来源：http://dali.shuidangran.top/Article/details/gtlnqsgltq.html

function add(a, b) return a + b end
来源：http://dali.chenzaomai.com/Article/details/gtuzywacnp.html

[T37] Lua：字符串拼接
来源：http://dali.chenlongwang.top/Article/details/gtriqvlgog.html

"a" .. "b"
来源：http://dali.aibaodan.cn/Article/details/gtwbfvrbhv.html

[T38] Lua：条件
来源：http://dali.tian-w.cn/Article/details/gtftytjjuq.html

if x > 0 then print("正") end
来源：http://dali.zhongyouzk.top/Article/details/gtilxtgeis.html

[T39] Lua：模式匹配
来源：http://dali.hnxiangtu.top/Article/details/gtethdnzhl.html

string.find(s, "%d+")
来源：http://dali.yangfankeji.com/Article/details/gtjrxjclud.html

[T40] Lua：元表
来源：http://dali.daria6918.cn/Article/details/gtqbwuqmmj.html

setmetatable({}, { __index = base })
来源：http://dali.svipenyu.cn/Article/details/gtjnbmyjzw.html

[T41] Perl：Hello World
来源：http://dali.pycfn.com/Article/details/gtxhckzxfs.html

print "Hello\n";
来源：http://dali.jinqigfzy.top/Article/details/gtxtanmlqs.html

[T42] Perl：变量类型
来源：http://dali.shuidangran.top/Article/details/gtugdresct.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.cucudq.cn/Article/details/gtpjwajyjt.html

[T43] Perl：字符串插值
来源：http://dali.bjfxy.top/Article/details/gthbyapuva.html

"值: $a"
来源：http://dali.hfpthk.cn/Article/details/gtftjyyrqg.html

[T44] Perl：条件
来源：http://dali.feifeiyinyue.top/Article/details/gtuaaelajq.html

if ($a > 0) { print "正"; }
来源：http://dali.cucudq.cn/Article/details/gtciwugzoy.html

[T45] Perl：数组遍历
来源：http://dali.fengsongda.top/Article/details/gtdwizxsrp.html

for my $x (@arr) { print $x; }
来源：http://dali.shzxlz.cn/Article/details/gtxkvvmswj.html

[T46] Perl：哈希操作
来源：http://dali.9152youxi.cn/Article/details/gtotpmpqbr.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.bjfxy.top/Article/details/gtpfikxche.html

[T47] Perl：正则捕获
来源：http://dali.cdnleiting.top/Article/details/gtapbpvboo.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.mhx1999.top/Article/details/gtuhsdxzpk.html

[T48] Perl：正则替换
来源：http://dali.hongshengwenyu.top/Article/details/gtsbdbqhmr.html

$s =~ s/old/new/g;
来源：http://dali.guannengcc.top/Article/details/gtnboeoucc.html

[T49] Perl：函数
来源：http://dali.yuxming.cn/Article/details/gtpyikydek.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.ydzc1.top/Article/details/gtxxzzatdz.html

[T50] Perl：逐行读文件
来源：http://dali.sxryk.cn/Article/details/gtnwkyohff.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zdqjudy.top/Article/details/gtpgatmybj.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.nwbrower.top/Article/details/gtgzgxubaf.html

[T51] Scala：Hello World
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuuxswkzv.html

println("Hello")
来源：http://dali.cucudq.cn/Article/details/gtydhvqtsw.html

[T52] Scala：变量
来源：http://dali.zhiwuduotai.top/Article/details/gtowdmzfry.html

val a = 1;  var b = 2
来源：http://dali.zhixingplan.top/Article/details/gtlzfcvdxw.html

[T53] Scala：字符串插值
来源：http://dali.andypj.xyz/Article/details/gtaaxawaca.html

s"值: $b"
来源：http://dali.gotoacloud.top/Article/details/gtouipfnut.html

[T54] Scala：集合映射
来源：http://dali.dianchejie.cn/Article/details/gtzsbbrhrf.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.haohaochexian.top/Article/details/gtaudfwirc.html

[T55] Scala：集合过滤
来源：http://dali.cqqwz.cn/Article/details/gtxldaenvy.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.jianghu66.top/Article/details/gtbdhbkisn.html

[T56] Scala：样例类
来源：http://dali.c1oappe.top/Article/details/gtwlcvcrzc.html

case class User(name: String, age: Int)
来源：http://dali.ivvv.top/Article/details/gtpjfrwvzr.html

[T57] Scala：模式匹配
来源：http://dali.zycfv.cn/Article/details/gtfzxjstmu.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.jqgufenzy.top/Article/details/gtdfpivwac.html

[T58] Scala：函数定义
来源：http://dali.meibo888.top/Article/details/gttxocewhw.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.jqgfzy.top/Article/details/gtncicbpuk.html

[T59] Scala：循环
来源：http://dali.snrcjt.cn/Article/details/gtceqyetle.html

for (i <- 1 to 10) println(i)
来源：http://dali.havefunace.top/Article/details/gtnolrawwu.html

[T60] Scala：折叠
来源：http://dali.wangshuangyany.cn/Article/details/gtokhvypww.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.tian-w.cn/Article/details/gtmeqrtvrn.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtxzhigumq.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.xylfe.cn/Article/details/gtszgnraur.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtyvpubxjc.html

[U01] Py：创建虚拟环境
来源：http://dali.guowangkeji.top/Article/details/gtvinfuhkc.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.xylfe.cn/Article/details/gtnssancph.html

[U02] Py：导出 / 安装依赖
来源：http://dali.havefunace.top/Article/details/gthoppobon.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.sufxvd.cn/Article/details/gttfjbxrkz.html


<!-- 参考信息 -->