代发 wailian999

ssh user@host 'uptime'
来源：http://dali.hfpthk.cn/Article/details/gtbxsbmbqd.html

[R58] 下载文件
来源：http://dali.iojbl.cn/Article/details/gtolzpogea.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.cdnleiting.top/Article/details/gtmksybdal.html

[R59] 发 POST JSON
来源：http://dali.0kj1m.cn/Article/details/gtcwdctsvq.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.dianchejie.cn/Article/details/gtdjxjjizp.html

[R60] 只看 HTTP 状态码
来源：http://dali.mhx1999.top/Article/details/gtrpxgvhjy.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.yangfankeji.com/Article/details/gtutalqjlv.html

[R61] 磁盘占用
来源：http://dali.yuxming.cn/Article/details/gtdissvjdn.html

df -h;  du -sh *
来源：http://dali.hywenlv.cn/Article/details/gtdtpsgqyl.html

[R62] 找最占空间的文件
来源：http://dali.nwbrower.top/Article/details/gtyvwmejwb.html

du -ah . | sort -rh | head -10
来源：http://dali.0kj1m.cn/Article/details/gtwjeqivzt.html

[R63] 内存与进程
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtirldhxil.html

free -h;  ps aux | grep nginx
来源：http://dali.pycfn.com/Article/details/gtxasjzmxh.html

[R64] 结束进程
来源：http://dali.guannengcc.top/Article/details/gthnuwvyem.html

kill -9 $(pgrep -f app.py)
来源：http://dali.gogol.net.cn/Article/details/gtichxqzag.html

[R65] 查看端口占用
来源：http://dali.0kj1m.cn/Article/details/gtplphytzn.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.gzhubu.top/Article/details/gtequcjvst.html

[R66] 定时任务
来源：http://dali.aibaodan.cn/Article/details/gtkkjaycvy.html

crontab -e;  crontab -l
来源：http://dali.smart0.xyz/Article/details/gtyyzhpcja.html

[R67] 生成随机十六进制串
来源：http://dali.hongshengwenyu.top/Article/details/gtyycwpggl.html

openssl rand -hex 16
来源：http://dali.gotoacloud.top/Article/details/gtinkjryme.html

[R68] 计算文件校验值
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnejircxz.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhoulong.xyz/Article/details/gtxaittlsj.html

[R69] 生成随机密码
来源：http://dali.aizwys.cn/Article/details/gthkbejtpt.html

head -c 16 /dev/urandom | base64
来源：http://dali.fzhhl.top/Article/details/gtmqlefmqj.html

[R70] 时间戳与互转
来源：http://dali.jlsjyb.cn/Article/details/gtfskddaee.html

date +%s;  date -d @1700000000
来源：http://dali.zhoulong.xyz/Article/details/gtzdipumxd.html

[R71] 日期格式化
来源：http://dali.tanke756.top/Article/details/gtgizanfdm.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjddnlojh.html

[R72] 等待端口就绪
来源：http://dali.cucudq.cn/Article/details/gtpoxvsovo.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.jyoumei.cn/Article/details/gtazgmabar.html

[R73] 分割大日志
来源：http://dali.zdqjudy.top/Article/details/gtskqtdkjd.html

split -l 1000 big.log part_
来源：http://dali.cheryme.top/Article/details/gtogkonkde.html

[R74] 批量重命名
来源：http://dali.jianghu66.top/Article/details/gtwvvxvbml.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.wangdashe.top/Article/details/gtphffnzpj.html

[R75] 导出环境变量
来源：http://dali.yueranfly.top/Article/details/gtevexixtk.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.wangdashe.top/Article/details/gtwagtpbyk.html

[R76] 使用临时文件
来源：http://dali.jqgfzy.top/Article/details/gtgjfundrl.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.aizwys.cn/Article/details/gtslvdxpow.html

[R77] 读取用户输入
来源：http://dali.0kj1m.cn/Article/details/gtdyfudxfd.html

read -rp "请输入: " ans
来源：http://dali.jianghu66.top/Article/details/gtojotauyd.html

[R78] 交互式菜单
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyhydybjf.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.ehwqpu.com/Article/details/gtizauyovy.html

[R79] 解析命令行选项
来源：http://dali.daria6918.cn/Article/details/gtyeybhjqm.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.xziqi.cn/Article/details/gttqjinlzd.html

[R80] 查看脚本执行耗时
来源：http://dali.chenlongwang.top/Article/details/gtwxgvqpqc.html

time ./run.sh
来源：http://dali.xuanzx.com/Article/details/gtjodgbafc.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtvfzbpnmd.html

S. C / C++ 专题
来源：http://dali.hywenlv.cn/Article/details/gtsezixktd.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtttyrqkzt.html

[S01] C：Hello World
来源：http://dali.jqgfzy.top/Article/details/gtbulmlbcu.html

#include <stdio.h>
来源：http://dali.dashuyun.cn/Article/details/gthcgxwskl.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhongyouzk.top/Article/details/gtebhhnfcm.html

[S02] C：变量与格式化输出
来源：http://dali.316326.xyz/Article/details/gtckufmuut.html

int a = 10; printf("%d\n", a);
来源：http://dali.hfpthk.cn/Article/details/gtbjmfdncq.html

[S03] C：读入整数
来源：http://dali.chenjidiqi.icu/Article/details/gtmycyvqmm.html

int x; scanf("%d", &x);
来源：http://dali.yj20258.top/Article/details/gtxfuqygfg.html

[S04] C：字符串复制
来源：http://dali.ppjwa.cn/Article/details/gtfldajjpe.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.cqqwz.cn/Article/details/gtogpdhzvz.html

[S05] C：字符串长度
来源：http://dali.jianghu66.top/Article/details/gthkdxhaje.html

strlen(s)
来源：http://dali.yj20258888.top/Article/details/gtmpgspjhy.html

[S06] C：字符串比较
来源：http://dali.hfpthk.cn/Article/details/gtudbgzpfj.html

strcmp(a, b) == 0
来源：http://dali.316326.xyz/Article/details/gthyeqmdzg.html

[S07] C：数组遍历求和
来源：http://dali.yonumen.top/Article/details/gtxobjivcq.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.xinyue.icu/Article/details/gtxdfypuzi.html

[S08] C：动态内存分配与释放
来源：http://dali.zycfv.cn/Article/details/gtovbyztce.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.birdmap.top/Article/details/gthouyexjh.html

[S09] C：结构体定义与初始化
来源：http://dali.cdnleiting.top/Article/details/gtmosztriy.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.nanxinkj.top/Article/details/gtamyntfxk.html

[S10] C：指针与解引用
来源：http://dali.aibaodan.cn/Article/details/gtrqsfhwwi.html

int *p = &a;  *p = 5;
来源：http://dali.ivvv.top/Article/details/gtbwlveiiz.html

[S11] C：逐行读文件
来源：http://dali.hysaishi.cn/Article/details/gtwtbrgmqo.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.jqgufenzy.top/Article/details/gtkqqaecti.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.hammf.cn/Article/details/gtblfhoiky.html

fclose(f);
来源：http://dali.dianchejie.cn/Article/details/gtizefluti.html

[S12] C：写文件
来源：http://dali.hongshengwenyu.top/Article/details/gtyxuznaov.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.cashguo.top/Article/details/gtasvliiin.html

[S13] C：宏定义
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvqkbzcfj.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.fzhhl.top/Article/details/gtxvabwyan.html

[S14] C：枚举
来源：http://dali.yuxming.cn/Article/details/gtocfdswxe.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.hongshengwenyu.top/Article/details/gttcbuqtuf.html

[S15] C：类型转换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvoykjlqj.html

(double) a / b
来源：http://dali.jinghuilouyu.cn/Article/details/gthdtfgnse.html

[S16] C：位操作置位
来源：http://dali.dianchejie.cn/Article/details/gtqrehhlcc.html

x |= (1 << 3);
来源：http://dali.xuetiantiany.cn/Article/details/gtfcwbgfez.html

[S17] C：安全拼接字符串
来源：http://dali.feifeiyinyue.top/Article/details/gtnlcahkza.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.jiagoushi.top/Article/details/gtoakoljnp.html

[S18] C：命令行参数
来源：http://dali.meibo888.top/Article/details/gtrootuoqi.html

int main(int argc, char **argv)
来源：http://dali.yongpay.top/Article/details/gtvtfepmzb.html

[S19] C：快速排序
来源：http://dali.zhaomingkeji.xyz/Article/details/gttexzodhb.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.svipenyu.cn/Article/details/gtoipvmomh.html

[S20] C：二分查找
来源：http://dali.gogol.net.cn/Article/details/gtotsgnpdk.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.jinqigfzy.top/Article/details/gtwzcbfrji.html

[S21] C：字符类别判断
来源：http://dali.xuanzx.com/Article/details/gtgyqouhne.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhongyouzk.top/Article/details/gtbymjwddh.html

[S22] C：字符串转数字
来源：http://dali.guannengcc.top/Article/details/gtvkchjbnv.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.yongpay.top/Article/details/gtrioqwrbv.html

[S23] C：随机数
来源：http://dali.cheryme.top/Article/details/gtgmegwhvg.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.andypj.xyz/Article/details/gtiqfwyeuo.html

[S24] C：获取本地时间
来源：http://dali.ybcxt.top/Article/details/gtaswgeark.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.chenlongwang.top/Article/details/gthejyynlt.html

[S25] C：内存拷贝
来源：http://dali.tianlin.xyz/Article/details/gtbruacnlz.html

memcpy(dst, src, n);
来源：http://dali.cdnleiting.top/Article/details/gteqvlwrkh.html

[S26] C：内存清零
来源：http://dali.yj20258888.top/Article/details/gtvzeovree.html

memset(a, 0, sizeof a);
来源：http://dali.yvedp.cn/Article/details/gtqusuigbo.html

[S27] C：定义常量
来源：http://dali.snrcjt.cn/Article/details/gtnxmpipva.html

const double PI = 3.14159;
来源：http://dali.sweek.top/Article/details/gtpnnxicmj.html

[S28] C：静态变量
来源：http://dali.wangdashe.top/Article/details/gtfpvcuaeb.html

static int counter = 0;
来源：http://dali.jqgufenzy.top/Article/details/gtrddqdasd.html

[S29] C：变参函数
来源：http://dali.andypj.xyz/Article/details/gtgbdgsmxe.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhongyouzk.top/Article/details/gtccqddpjz.html

[S30] C：头文件保护
来源：http://dali.zhengqikj.top/Article/details/gtprxbiunr.html

#ifndef X_H
来源：http://dali.cqqwz.cn/Article/details/gtdoobiith.html

#define X_H
来源：http://dali.guannengcc.top/Article/details/gtlzcczphw.html

#endif
来源：http://dali.sweek.top/Article/details/gtjdokujky.html

[S31] C++：Hello World
来源：http://dali.ybcxt.top/Article/details/gtleuaivyi.html

#include <iostream>
来源：http://dali.cqqwz.cn/Article/details/gtjoyurhdl.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtawfjgzcw.html

[S32] C++：字符串
来源：http://dali.c1oappe.top/Article/details/gtwvmphcqr.html

std::string s = "hi";  s += "!";
来源：http://dali.0kj1m.cn/Article/details/gtypbszbqf.html

[S33] C++：vector 增删
来源：http://dali.shanyushiyangkeji.top/Article/details/gthaybrnzk.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.xylfe.cn/Article/details/gtzqowjyjn.html

[S34] C++：遍历 vector
来源：http://dali.hnxiangtu.top/Article/details/gtnfylgszf.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.cdnleiting.top/Article/details/gtyihdevak.html

[S35] C++：map
来源：http://dali.ppjwa.cn/Article/details/gtdawvmies.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.birdmap.top/Article/details/gtehenirbh.html

[S36] C++：unordered_map
来源：http://dali.yangfankeji.com/Article/details/gthoekzbqw.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.iojbl.cn/Article/details/gtepvgolit.html

[S37] C++：set
来源：http://dali.nanxuanxn.top/Article/details/gtwbwummqk.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.yangfankeji.com/Article/details/gtaitzaozl.html

[S38] C++：排序
来源：http://dali.zycfv.cn/Article/details/gtnxpadtvw.html

std::sort(v.begin(), v.end());
来源：http://dali.tian-w.cn/Article/details/gtuhldhmnu.html

[S39] C++：自定义比较器排序
来源：http://dali.ybcxt.top/Article/details/gtxmwgdybl.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.yueranfly.top/Article/details/gtwmvxynst.html

[S40] C++：查找元素
来源：http://dali.cqqwz.cn/Article/details/gtyuphwqiy.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.aibaodan.cn/Article/details/gtjewavvmp.html

[S41] C++：类与构造函数
来源：http://dali.yonumen.top/Article/details/gtndrbuizq.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.birdmap.top/Article/details/gtivgsukkl.html

[S42] C++：继承与虚函数
来源：http://dali.guannengcc.top/Article/details/gtlqbygnry.html

class B : public Base { public: void f() override {} };
来源：http://dali.feifeiyinyue.top/Article/details/gtbulddune.html

[S43] C++：智能指针
来源：http://dali.quarkkingdee.top/Article/details/gtoqaqvnal.html

auto p = std::make_unique<int>(5);
来源：http://dali.andypj.xyz/Article/details/gtuwnhyyru.html

[S44] C++：引用传参
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjnarjkba.html

void inc(int &x) { ++x; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtvirezvfl.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gtgxqpamok.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.jinqigufen.top/Article/details/gtdcuopdgp.html

[S46] C++：函数模板
来源：http://dali.ywan-chungtsiang.top/Article/details/gtehufjozp.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.xinyue.icu/Article/details/gtmryehhff.html

[S47] C++：结构化绑定遍历
来源：http://dali.redwolf501.top/Article/details/gtazyluxuu.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.iojbl.cn/Article/details/gtwbvfuded.html

[S48] C++：逐行读文件
来源：http://dali.gogol.net.cn/Article/details/gtagzudjrv.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.jiagoushi.top/Article/details/gtbabyxglx.html

while (std::getline(in, line)) { }
来源：http://dali.gzhubu.top/Article/details/gtukcztxty.html

[S49] C++：写文件
来源：http://dali.bjfxy.top/Article/details/gtaxvxdefl.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.smart0.xyz/Article/details/gtrcxjlrjw.html

[S50] C++：格式化数字
来源：http://dali.yongpay.top/Article/details/gtoxzgdzcy.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.tianlin.xyz/Article/details/gtrjsgdgbv.html

[S51] C++：显式类型转换
来源：http://dali.cucudq.cn/Article/details/gtzqkikqwz.html

static_cast<double>(a) / b
来源：http://dali.yj20258888.top/Article/details/gtkgdynhtc.html

[S52] C++：const 与 noexcept
来源：http://dali.zhaomingkeji.xyz/Article/details/gtarhwygay.html

int size() const noexcept { return n_; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtzdjhebtw.html

[S53] C++：移动语义
来源：http://dali.ppjwa.cn/Article/details/gtqycgrphk.html

std::vector<int> w = std::move(v);
来源：http://dali.redwolf501.top/Article/details/gtzttsswri.html

[S54] C++：异常处理
来源：http://dali.zhoulong.xyz/Article/details/gtlckhfdvw.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.cashguo.top/Article/details/gtlsutvghq.html

[S55] C++：结构化绑定
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtancptqfx.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.cheryme.top/Article/details/gthwwidlle.html

[S56] C++：optional
来源：http://dali.yonumen.top/Article/details/gtobnmalxi.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.tanke756.top/Article/details/gteevusfiu.html

[S57] C++：编译期常量
来源：http://dali.birdmap.top/Article/details/gtjhotouuh.html

constexpr int N = 10;
来源：http://dali.ybcxt.top/Article/details/gtlcgjtyqv.html

[S58] C++：命名空间
来源：http://dali.fzhhl.top/Article/details/gtulnilprt.html

namespace ns { int f() { return 1; } }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyaxyxouz.html

[S59] C++：静态断言
来源：http://dali.xuanzx.com/Article/details/gtnvgdcsbg.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.yangfankeji.com/Article/details/gthgmzurbk.html

[S60] C++：遍历并删除元素
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzuniuaqz.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.shuidangran.top/Article/details/gtxlghbsgn.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlveuusfu.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zycfv.cn/Article/details/gtgypiplai.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtffwzldbj.html

[T01] Kotlin：Hello World
来源：http://dali.meibo888.top/Article/details/gtibmfnjhy.html

println("Hello")
来源：http://dali.chenzaomai.com/Article/details/gtnmfgyeof.html

[T02] Kotlin：变量
来源：http://dali.daxiang520.top/Article/details/gthcjwlyao.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.xziqi.cn/Article/details/gtxbmyhhup.html

[T03] Kotlin：字符串模板
来源：http://dali.chenjidiqi.icu/Article/details/gtsxatsyuu.html

"值: $b"
来源：http://dali.9152youxi.cn/Article/details/gtxmxwtnrr.html

[T04] Kotlin：空安全
来源：http://dali.sweek.top/Article/details/gtwcudgpui.html

val n: String? = null;  n?.length
来源：http://dali.zhixingplan.top/Article/details/gtclnwcres.html

[T05] Kotlin：when 表达式
来源：http://dali.guowangkeji.top/Article/details/gtqhllbohg.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.fengsongda.top/Article/details/gtgulszuzi.html

[T06] Kotlin：集合映射
来源：http://dali.hammf.cn/Article/details/gtuxjfazjp.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.shuidangran.top/Article/details/gthfkpooqn.html

[T07] Kotlin：集合过滤
来源：http://dali.kuanghao11.cn/Article/details/gtptcvsdyi.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.quarkkingdee.top/Article/details/gtvymqcgjs.html

[T08] Kotlin：数据类
来源：http://dali.yvedp.cn/Article/details/gtjppgxjzl.html

data class User(val name: String, val age: Int)
来源：http://dali.hnqzz.top/Article/details/gtxfaqsdsz.html

[T09] Kotlin：扩展函数
来源：http://dali.xylfe.cn/Article/details/gtkexztqhi.html

fun String.exclaim() = this + "!"
来源：http://dali.gaohongyu789.top/Article/details/gtxsegxbrc.html

[T10] Kotlin：默认参数
来源：http://dali.haohaochexian.top/Article/details/gtnvgrzrgu.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.jiagoushi.top/Article/details/gtzwseocyc.html

[T11] Kotlin：协程
来源：http://dali.havefunace.top/Article/details/gtfrdkhfrg.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvyacjnkb.html

[T12] Kotlin：解构声明
来源：http://dali.gogol.net.cn/Article/details/gtgzvmqlyk.html

val (a, b) = Pair(1, 2)
来源：http://dali.nanxuanxn.top/Article/details/gtljhemmnn.html

[T13] Kotlin：只读 Map
来源：http://dali.cheryme.top/Article/details/gtawldplkr.html

val m = mapOf("a" to 1)
来源：http://dali.nwbrower.top/Article/details/gtsqwuihfj.html

[T14] Kotlin：循环
来源：http://dali.daxiang520.top/Article/details/gtbjycxkba.html

for (i in 1..10) println(i)
来源：http://dali.pengpengdd.cyou/Article/details/gtaeiblguh.html

[T15] Kotlin：接口
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnmragotd.html

interface Shape { fun area(): Double }
来源：http://dali.sysykeji.top/Article/details/gtwljtmsef.html

[T16] Swift：Hello World
来源：http://dali.guannengcc.top/Article/details/gtxrflrdwf.html

print("Hello")
来源：http://dali.shangyingyoupin.top/Article/details/gtoirpruap.html

[T17] Swift：变量与常量
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqligmdtx.html

var a = 1;  let b = 2
来源：http://dali.yanxiufei.cn/Article/details/gtroyxbadf.html

[T18] Swift：字符串插值
来源：http://dali.sxryk.cn/Article/details/gtljoprari.html

"值: \(b)"
来源：http://dali.gaohongyu789.top/Article/details/gthpikoype.html

[T19] Swift：可选绑定
来源：http://dali.vqdsnc.cn/Article/details/gtmjrpnqoa.html

if let n = opt { print(n) }
来源：http://dali.hfpthk.cn/Article/details/gtxjoeezei.html

[T20] Swift：数组操作
来源：http://dali.0kj1m.cn/Article/details/gtijioxuty.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.nwbrower.top/Article/details/gtqyghaiid.html

[T21] Swift：遍历
来源：http://dali.gaohongyu789.top/Article/details/gthmhfyofu.html

for x in a { print(x) }
来源：http://dali.yanxiufei.cn/Article/details/gtwzpbjnes.html

[T22] Swift：字典
来源：http://dali.zhoulong.xyz/Article/details/gtbgrstoyw.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.ehwqpu.com/Article/details/gtyakkmmxz.html

[T23] Swift：函数
来源：http://dali.tian-w.cn/Article/details/gtxpphxkxr.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.sweek.top/Article/details/gtrzcxomsp.html

[T24] Swift：闭包
来源：http://dali.sxryk.cn/Article/details/gtjblawmfl.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.gogol.net.cn/Article/details/gtpbffwaqz.html

[T25] Swift：结构体
来源：http://dali.jqgufenzy.top/Article/details/gtfxqjvnem.html

struct P { var x: Int }
来源：http://dali.yj20258888.top/Article/details/gtwuedramt.html

[T26] Swift：类与重写
来源：http://dali.cdnleiting.top/Article/details/gtrnlpklhr.html

class A: Base { override func f() {} }
来源：http://dali.daxiang520.top/Article/details/gtmszfslqk.html

[T27] Swift：错误处理
来源：http://dali.sysykeji.top/Article/details/gtobruegwr.html

do { try f() } catch { print(error) }
来源：http://dali.jinqigfzy.top/Article/details/gtydhylyrc.html

[T28] Swift：枚举
来源：http://dali.yueranfly.top/Article/details/gtelvitxjs.html

enum Color { case red, green }
来源：http://dali.cashguo.top/Article/details/gthnamjegm.html

[T29] Swift：guard 提前返回
来源：http://dali.jqgufenzy.top/Article/details/gtckkhfxja.html

guard let x = opt else { return }
来源：http://dali.meibo888.top/Article/details/gtxxqhqfvj.html

[T30] Swift：协议
来源：http://dali.316326.xyz/Article/details/gtgdvmdire.html

protocol Shape { func area() -> Double }
来源：http://dali.yonumen.top/Article/details/gtszbvnuxa.html

[T31] Lua：Hello World
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtarotwihm.html

print("Hello")
来源：http://dali.hnxiangtu.top/Article/details/gtcrahsmne.html

[T32] Lua：局部变量
来源：http://dali.cashguo.top/Article/details/gttdunpxid.html

local a = 1
来源：http://dali.hammf.cn/Article/details/gtlbomejkw.html

[T33] Lua：表（数组）
来源：http://dali.shangyingyoupin.top/Article/details/gtddirblds.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.ybcxt.top/Article/details/gtxxwmrvye.html

[T34] Lua：遍历表
来源：http://dali.bjfxy.top/Article/details/gtofybnqpd.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.guannengcc.top/Article/details/gtomtdjjzz.html

[T35] Lua：字典表
来源：http://dali.yvedp.cn/Article/details/gtuljgdqyl.html

local d = { a = 1 };  d.b = 2
来源：http://dali.hongshengwenyu.top/Article/details/gtwuboxynz.html

[T36] Lua：函数
来源：http://dali.shangyingyoupin.top/Article/details/gtdoijdial.html

function add(a, b) return a + b end
来源：http://dali.shuidangran.top/Article/details/gthknvqnrm.html

[T37] Lua：字符串拼接
来源：http://dali.zhoulong.xyz/Article/details/gtxkbiwjtm.html

"a" .. "b"
来源：http://dali.gogol.net.cn/Article/details/gtjdwltqig.html

[T38] Lua：条件
来源：http://dali.hammf.cn/Article/details/gtziwkxeuv.html

if x > 0 then print("正") end
来源：http://dali.birdmap.top/Article/details/gtixohyltq.html

[T39] Lua：模式匹配
来源：http://dali.gogol.net.cn/Article/details/gtqlaodlqv.html

string.find(s, "%d+")
来源：http://dali.sysykeji.top/Article/details/gtoijainxb.html

[T40] Lua：元表
来源：http://dali.hnxiangtu.top/Article/details/gtosrwtxkh.html

setmetatable({}, { __index = base })
来源：http://dali.gzhubu.top/Article/details/gtwycrjznh.html

[T41] Perl：Hello World
来源：http://dali.sxryk.cn/Article/details/gtndybmppv.html

print "Hello\n";
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuypbjhue.html

[T42] Perl：变量类型
来源：http://dali.daxiang520.top/Article/details/gtqbufosru.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.ydzc1.top/Article/details/gtczqavkxv.html

[T43] Perl：字符串插值
来源：http://dali.yanxiufei.cn/Article/details/gtvflhfpbu.html

"值: $a"
来源：http://dali.tianlin.xyz/Article/details/gtbpatwxfd.html

[T44] Perl：条件
来源：http://dali.ppjwa.cn/Article/details/gtelryimuo.html

if ($a > 0) { print "正"; }
来源：http://dali.9152youxi.cn/Article/details/gtcrllosfy.html

[T45] Perl：数组遍历
来源：http://dali.ydzc1.top/Article/details/gtiqqkylcv.html

for my $x (@arr) { print $x; }
来源：http://dali.smart0.xyz/Article/details/gtivneaste.html

[T46] Perl：哈希操作
来源：http://dali.hfpthk.cn/Article/details/gttmytjavo.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.cqqwz.cn/Article/details/gtloghswnc.html

[T47] Perl：正则捕获
来源：http://dali.cdnleiting.top/Article/details/gteojgnopw.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.shuidangran.top/Article/details/gtmexpwxwn.html

[T48] Perl：正则替换
来源：http://dali.jyoumei.cn/Article/details/gtvfrvlryn.html

$s =~ s/old/new/g;
来源：http://dali.pengpengdd.cyou/Article/details/gtjhazfbxu.html

[T49] Perl：函数
来源：http://dali.svipenyu.cn/Article/details/gtryflrnxi.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhengqikj.top/Article/details/gtlebnipkq.html

[T50] Perl：逐行读文件
来源：http://dali.haohaochexian.top/Article/details/gturxcfptw.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.hywenlv.cn/Article/details/gtnikmjvha.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.cashguo.top/Article/details/gtudoahgrs.html

[T51] Scala：Hello World
来源：http://dali.xuetiantiany.cn/Article/details/gtpwvwpihl.html

println("Hello")
来源：http://dali.chenjidiqi.icu/Article/details/gtdtmckrxc.html

[T52] Scala：变量
来源：http://dali.yj20258888.top/Article/details/gtixroszmd.html

val a = 1;  var b = 2
来源：http://dali.gogol.net.cn/Article/details/gtydxdequo.html

[T53] Scala：字符串插值
来源：http://dali.cucudq.cn/Article/details/gthvtzzlpj.html

s"值: $b"
来源：http://dali.haohaochexian.top/Article/details/gtsedcgicm.html

[T54] Scala：集合映射
来源：http://dali.yueranfly.top/Article/details/gtzmgmpzpt.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.hywenlv.cn/Article/details/gtnapneupa.html

[T55] Scala：集合过滤
来源：http://dali.svipenyu.cn/Article/details/gtmftpsdds.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhoulong.xyz/Article/details/gtspmeqnqs.html

[T56] Scala：样例类
来源：http://dali.nanxinkj.top/Article/details/gtousdkslq.html

case class User(name: String, age: Int)
来源：http://dali.yuanzhike.top/Article/details/gtysjsyboq.html

[T57] Scala：模式匹配
来源：http://dali.jqgufenzy.top/Article/details/gtmhugobpc.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.gotoacloud.top/Article/details/gtmoguwcno.html

[T58] Scala：函数定义
来源：http://dali.hnxiangtu.top/Article/details/gtaxvexlvg.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.fzhhl.top/Article/details/gtseszotwr.html

[T59] Scala：循环
来源：http://dali.tanke756.top/Article/details/gtriaykbdl.html

for (i <- 1 to 10) println(i)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjuxsnnzk.html

[T60] Scala：折叠
来源：http://dali.gaohongyu789.top/Article/details/gtaszmfdyi.html


<!-- 参考信息 -->