代发 wailian999

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.bjfxy.top/Article/details/gtprzsggqp.html

[R60] 只看 HTTP 状态码
来源：http://dali.cheryme.top/Article/details/gtuekmhjds.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.aizwys.cn/Article/details/gtrahiuttk.html

[R61] 磁盘占用
来源：http://dali.9152youxi.cn/Article/details/gtutdvykoc.html

df -h;  du -sh *
来源：http://dali.tianlin.xyz/Article/details/gtuulxrdxq.html

[R62] 找最占空间的文件
来源：http://dali.jqgufenzy.top/Article/details/gtydjokkyb.html

du -ah . | sort -rh | head -10
来源：http://dali.ppjwa.cn/Article/details/gtweiqwuif.html

[R63] 内存与进程
来源：http://dali.yangfankeji.com/Article/details/gtvfnudtby.html

free -h;  ps aux | grep nginx
来源：http://dali.chenlongwang.top/Article/details/gtbbgvpudd.html

[R64] 结束进程
来源：http://dali.xziqi.cn/Article/details/gtpqcfdnjn.html

kill -9 $(pgrep -f app.py)
来源：http://dali.hysaishi.cn/Article/details/gttdxdnneo.html

[R65] 查看端口占用
来源：http://dali.jiagoushi.top/Article/details/gtsjunpnsd.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.chenzaomai.com/Article/details/gtpvcubbjb.html

[R66] 定时任务
来源：http://dali.jqgfzy.top/Article/details/gtvnwkjzoh.html

crontab -e;  crontab -l
来源：http://dali.chenlongwang.top/Article/details/gtygvawdrm.html

[R67] 生成随机十六进制串
来源：http://dali.aizwys.cn/Article/details/gtyvgqogux.html

openssl rand -hex 16
来源：http://dali.wangdashe.top/Article/details/gttbuuhesb.html

[R68] 计算文件校验值
来源：http://dali.mhx1999.top/Article/details/gtpuocywzm.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.tanke756.top/Article/details/gttvmivxby.html

[R69] 生成随机密码
来源：http://dali.havefunace.top/Article/details/gtlamfyuob.html

head -c 16 /dev/urandom | base64
来源：http://dali.havefunace.top/Article/details/gtkazczpos.html

[R70] 时间戳与互转
来源：http://dali.yj20258888.top/Article/details/gttzbndgsm.html

date +%s;  date -d @1700000000
来源：http://dali.ydzc1.top/Article/details/gtkkwnefnm.html

[R71] 日期格式化
来源：http://dali.iojbl.cn/Article/details/gtbiqgdgat.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.jinqigfzy.top/Article/details/gthctynazt.html

[R72] 等待端口就绪
来源：http://dali.shuidangran.top/Article/details/gthhfcojpa.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.yonumen.top/Article/details/gtbbtijtci.html

[R73] 分割大日志
来源：http://dali.quarkkingdee.top/Article/details/gtzjpoiiav.html

split -l 1000 big.log part_
来源：http://dali.chenzaomai.com/Article/details/gtmxtirvos.html

[R74] 批量重命名
来源：http://dali.aibaodan.cn/Article/details/gtuzbbdmux.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.gaohongyu789.top/Article/details/gtzaslgopv.html

[R75] 导出环境变量
来源：http://dali.c1oappe.top/Article/details/gtqpmqtvyp.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.bjfxy.top/Article/details/gtfenkfkly.html

[R76] 使用临时文件
来源：http://dali.hnxiangtu.top/Article/details/gtmtvrgsvs.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.shanyushiyangkeji.top/Article/details/gterggmjij.html

[R77] 读取用户输入
来源：http://dali.shuidangran.top/Article/details/gtwqvnnebe.html

read -rp "请输入: " ans
来源：http://dali.svipenyu.cn/Article/details/gtnesqrkyr.html

[R78] 交互式菜单
来源：http://dali.shuidangran.top/Article/details/gtcuypwryg.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.svipenyu.cn/Article/details/gtfvromwsz.html

[R79] 解析命令行选项
来源：http://dali.9152youxi.cn/Article/details/gtutretvrz.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.shanyushiyangtech.top/Article/details/gtqdjuieho.html

[R80] 查看脚本执行耗时
来源：http://dali.hywenlv.cn/Article/details/gtvmqtgtvo.html

time ./run.sh
来源：http://dali.dashuyun.cn/Article/details/gtjoambopb.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtfaiuidxt.html

S. C / C++ 专题
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjifvtunk.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtnhsegnan.html

[S01] C：Hello World
来源：http://dali.haohaochexian.top/Article/details/gtecpgndvo.html

#include <stdio.h>
来源：http://dali.gotoacloud.top/Article/details/gtrhxharkq.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.cheryme.top/Article/details/gtgtvxrxvk.html

[S02] C：变量与格式化输出
来源：http://dali.jqgufenzy.top/Article/details/gtnmatdqqg.html

int a = 10; printf("%d\n", a);
来源：http://dali.pengpengdd.cyou/Article/details/gthwhseevt.html

[S03] C：读入整数
来源：http://dali.yongpay.top/Article/details/gtlgjndgaq.html

int x; scanf("%d", &x);
来源：http://dali.cqqwz.cn/Article/details/gtbtezrchd.html

[S04] C：字符串复制
来源：http://dali.hfpthk.cn/Article/details/gtirwbsbkx.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.cqqwz.cn/Article/details/gtkuwhjpzd.html

[S05] C：字符串长度
来源：http://dali.wangdashe.top/Article/details/gtylqyjexu.html

strlen(s)
来源：http://dali.fzhhl.top/Article/details/gtfrrmfzxo.html

[S06] C：字符串比较
来源：http://dali.shuidangran.top/Article/details/gtevztvdkc.html

strcmp(a, b) == 0
来源：http://dali.nanxinkj.top/Article/details/gtcyqlmujl.html

[S07] C：数组遍历求和
来源：http://dali.hfpthk.cn/Article/details/gtwlxenfex.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.hysaishi.cn/Article/details/gtcwjuisjx.html

[S08] C：动态内存分配与释放
来源：http://dali.jlsjyb.cn/Article/details/gtcsxxoatz.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.9152youxi.cn/Article/details/gtudwplwag.html

[S09] C：结构体定义与初始化
来源：http://dali.0kj1m.cn/Article/details/gtuupfwivp.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhiwuduotai.top/Article/details/gtouxokcfs.html

[S10] C：指针与解引用
来源：http://dali.jinqigfzy.top/Article/details/gtsloqvgha.html

int *p = &a;  *p = 5;
来源：http://dali.9152youxi.cn/Article/details/gtwpvwaosa.html

[S11] C：逐行读文件
来源：http://dali.svipenyu.cn/Article/details/gtdeooeckg.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.nanxinkj.top/Article/details/gtrfaijnkq.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.cucudq.cn/Article/details/gtjriaobnr.html

fclose(f);
来源：http://dali.vqdsnc.cn/Article/details/gtezfksdkv.html

[S12] C：写文件
来源：http://dali.chenjidiqi.icu/Article/details/gtkikjxwqz.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.wangshuangyany.cn/Article/details/gtydxquslu.html

[S13] C：宏定义
来源：http://dali.yj20258.top/Article/details/gtmvtkffgl.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhiwuduotai.top/Article/details/gtefvbunba.html

[S14] C：枚举
来源：http://dali.sxryk.cn/Article/details/gtbcsemhas.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.hnxiangtu.top/Article/details/gtetahynbz.html

[S15] C：类型转换
来源：http://dali.9152youxi.cn/Article/details/gtiuracwxw.html

(double) a / b
来源：http://dali.yueranfly.top/Article/details/gtdhleossa.html

[S16] C：位操作置位
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtawfpavuy.html

x |= (1 << 3);
来源：http://dali.bjfxy.top/Article/details/gtunsplcwl.html

[S17] C：安全拼接字符串
来源：http://dali.jinghuilouyu.cn/Article/details/gtldxlplcb.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgzhnbsko.html

[S18] C：命令行参数
来源：http://dali.hnxiangtu.top/Article/details/gtysjqthau.html

int main(int argc, char **argv)
来源：http://dali.tanke756.top/Article/details/gtimyysmhs.html

[S19] C：快速排序
来源：http://dali.ehwqpu.com/Article/details/gtbtagknqm.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.shzxlz.cn/Article/details/gtdcjjvpzw.html

[S20] C：二分查找
来源：http://dali.zhixingplan.top/Article/details/gtfqfcronc.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.jyoumei.cn/Article/details/gtrlxuseex.html

[S21] C：字符类别判断
来源：http://dali.xylfe.cn/Article/details/gtkjvsmmki.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zdqjudy.top/Article/details/gtdoumiznh.html

[S22] C：字符串转数字
来源：http://dali.yuanzhike.top/Article/details/gtmsmiujjr.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.cheryme.top/Article/details/gtndogiiac.html

[S23] C：随机数
来源：http://dali.316326.xyz/Article/details/gtlftdajmf.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.wangshuangyany.cn/Article/details/gtqvdvnbcf.html

[S24] C：获取本地时间
来源：http://dali.yvedp.cn/Article/details/gtpoztxgvq.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.shzxlz.cn/Article/details/gtwzuxhcrb.html

[S25] C：内存拷贝
来源：http://dali.aizwys.cn/Article/details/gtghgmbucj.html

memcpy(dst, src, n);
来源：http://dali.aibaodan.cn/Article/details/gtlutetxiy.html

[S26] C：内存清零
来源：http://dali.havefunace.top/Article/details/gtmbtdemse.html

memset(a, 0, sizeof a);
来源：http://dali.zhiwuduotai.top/Article/details/gtncejwsdh.html

[S27] C：定义常量
来源：http://dali.shzxlz.cn/Article/details/gthdarpwtf.html

const double PI = 3.14159;
来源：http://dali.ydzc1.top/Article/details/gtaowtpibz.html

[S28] C：静态变量
来源：http://dali.ivvv.top/Article/details/gtzketamqv.html

static int counter = 0;
来源：http://dali.yj20258888.top/Article/details/gtratvejze.html

[S29] C：变参函数
来源：http://dali.shanyushiyangtech.top/Article/details/gtxjbthsay.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.shanyushiyangtech.top/Article/details/gthpjnrxpi.html

[S30] C：头文件保护
来源：http://dali.tianlin.xyz/Article/details/gtyrofzolh.html

#ifndef X_H
来源：http://dali.shuidangran.top/Article/details/gtvwwcnqra.html

#define X_H
来源：http://dali.0kj1m.cn/Article/details/gtepreqfaf.html

#endif
来源：http://dali.shanyushiyangtech.top/Article/details/gtyprkyeue.html

[S31] C++：Hello World
来源：http://dali.nanxuanxn.top/Article/details/gtrshvqnts.html

#include <iostream>
来源：http://dali.yj20258.top/Article/details/gtvpfpiptt.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.xylfe.cn/Article/details/gtknimgxzn.html

[S32] C++：字符串
来源：http://dali.ivvv.top/Article/details/gtooligqyi.html

std::string s = "hi";  s += "!";
来源：http://dali.yonumen.top/Article/details/gtqfbqfmeo.html

[S33] C++：vector 增删
来源：http://dali.yj20258888.top/Article/details/gtaounotit.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.svipenyu.cn/Article/details/gtzqnjuyst.html

[S34] C++：遍历 vector
来源：http://dali.316326.xyz/Article/details/gtgtjuxxwq.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.nanxinkj.top/Article/details/gtcmaioybs.html

[S35] C++：map
来源：http://dali.yuxming.cn/Article/details/gtykrtnkhf.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.aizwys.cn/Article/details/gtqchhdlnk.html

[S36] C++：unordered_map
来源：http://dali.hnxiangtu.top/Article/details/gtlhkobxlx.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhongyouzk.top/Article/details/gtpsglbcjt.html

[S37] C++：set
来源：http://dali.ppjwa.cn/Article/details/gtljhgtkzs.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.pycfn.com/Article/details/gtrzvqjpqz.html

[S38] C++：排序
来源：http://dali.nanxinkj.top/Article/details/gtnqdwrsav.html

std::sort(v.begin(), v.end());
来源：http://dali.kuanghao11.cn/Article/details/gtgosifquq.html

[S39] C++：自定义比较器排序
来源：http://dali.hongshengwenyu.top/Article/details/gtxjdhpiff.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhoulong.xyz/Article/details/gtbdrdulrx.html

[S40] C++：查找元素
来源：http://dali.cucudq.cn/Article/details/gtgnvnrakc.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.vqdsnc.cn/Article/details/gtiqxhvfmc.html

[S41] C++：类与构造函数
来源：http://dali.daria6918.cn/Article/details/gtbrjmexhf.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.sweek.top/Article/details/gtkjjrpagf.html

[S42] C++：继承与虚函数
来源：http://dali.shzxlz.cn/Article/details/gtcemfkfsu.html

class B : public Base { public: void f() override {} };
来源：http://dali.fzhhl.top/Article/details/gtozlsheib.html

[S43] C++：智能指针
来源：http://dali.vqdsnc.cn/Article/details/gtduasnstg.html

auto p = std::make_unique<int>(5);
来源：http://dali.yuanzhike.top/Article/details/gtfvraazkz.html

[S44] C++：引用传参
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoozbyuru.html

void inc(int &x) { ++x; }
来源：http://dali.pengpengdd.cyou/Article/details/gtbfoblnus.html

[S45] C++：lambda
来源：http://dali.svipenyu.cn/Article/details/gtzgutevbv.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.daria6918.cn/Article/details/gttnydsive.html

[S46] C++：函数模板
来源：http://dali.jianghu66.top/Article/details/gttjtiunqs.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.jqgfzy.top/Article/details/gtsspyahtp.html

[S47] C++：结构化绑定遍历
来源：http://dali.gotoacloud.top/Article/details/gtzkjbukhc.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.gaohongyu789.top/Article/details/gtnrkuqvok.html

[S48] C++：逐行读文件
来源：http://dali.ehwqpu.com/Article/details/gtxzjhcnxr.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.ivvv.top/Article/details/gtkemgtakh.html

while (std::getline(in, line)) { }
来源：http://dali.pengpengdd.cyou/Article/details/gtrjnrzjee.html

[S49] C++：写文件
来源：http://dali.andypj.xyz/Article/details/gtqqvqmres.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.xuetiantiany.cn/Article/details/gtaihlifeq.html

[S50] C++：格式化数字
来源：http://dali.nwbrower.top/Article/details/gtnzzmfjsc.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.gaohongyu789.top/Article/details/gtfpnrgqdf.html

[S51] C++：显式类型转换
来源：http://dali.yj20258888.top/Article/details/gtobilayvc.html

static_cast<double>(a) / b
来源：http://dali.shuidangran.top/Article/details/gtfhlkkgyi.html

[S52] C++：const 与 noexcept
来源：http://dali.tanke756.top/Article/details/gtuualvjwq.html

int size() const noexcept { return n_; }
来源：http://dali.tianlin.xyz/Article/details/gtxkenjxdp.html

[S53] C++：移动语义
来源：http://dali.aizwys.cn/Article/details/gtioilvwai.html

std::vector<int> w = std::move(v);
来源：http://dali.yuanzhike.top/Article/details/gtmtioraup.html

[S54] C++：异常处理
来源：http://dali.yj20258888.top/Article/details/gtjgiuumnk.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.shzxlz.cn/Article/details/gtxpppxxwp.html

[S55] C++：结构化绑定
来源：http://dali.sysykeji.top/Article/details/gtqbapadol.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.yj20258.top/Article/details/gtacxyessl.html

[S56] C++：optional
来源：http://dali.yj20258888.top/Article/details/gtdixipbdz.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.ehwqpu.com/Article/details/gtdbtyttgd.html

[S57] C++：编译期常量
来源：http://dali.shanyushiyangtech.top/Article/details/gthosolppu.html

constexpr int N = 10;
来源：http://dali.shanyushiyangtech.top/Article/details/gtaqgthkxk.html

[S58] C++：命名空间
来源：http://dali.shzxlz.cn/Article/details/gtichfouku.html

namespace ns { int f() { return 1; } }
来源：http://dali.tianlin.xyz/Article/details/gtxbeyjgzk.html

[S59] C++：静态断言
来源：http://dali.jyoumei.cn/Article/details/gtqupqfdbr.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhiwuduotai.top/Article/details/gtxrlwfenf.html

[S60] C++：遍历并删除元素
来源：http://dali.fzhhl.top/Article/details/gtvndbnzfp.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.nanxinkj.top/Article/details/gtafguffge.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gthbpterkp.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.aizwys.cn/Article/details/gtrxzhllzh.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtjefekwes.html

[T01] Kotlin：Hello World
来源：http://dali.zhongyouzk.top/Article/details/gtazmxuqhe.html

println("Hello")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbtwxbcdr.html

[T02] Kotlin：变量
来源：http://dali.xuetiantiany.cn/Article/details/gtbkglilbm.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.jlsjyb.cn/Article/details/gtvcubpaef.html

[T03] Kotlin：字符串模板
来源：http://dali.zhiwuduotai.top/Article/details/gtvziwmmlq.html

"值: $b"
来源：http://dali.zhongyouzk.top/Article/details/gtsjjwmldj.html

[T04] Kotlin：空安全
来源：http://dali.wangshuangyany.cn/Article/details/gtzpietujy.html

val n: String? = null;  n?.length
来源：http://dali.0kj1m.cn/Article/details/gtkhljzpkw.html

[T05] Kotlin：when 表达式
来源：http://dali.zhoulong.xyz/Article/details/gtcockctzx.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.yangfankeji.com/Article/details/gtzlqajwbu.html

[T06] Kotlin：集合映射
来源：http://dali.chenjidiqi.icu/Article/details/gtoewxbmrn.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.mhx1999.top/Article/details/gtqvrorfgq.html

[T07] Kotlin：集合过滤
来源：http://dali.jlsjyb.cn/Article/details/gtzlqitnhk.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.chenzaomai.com/Article/details/gtxcdhoccn.html

[T08] Kotlin：数据类
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnxprlwtf.html

data class User(val name: String, val age: Int)
来源：http://dali.havefunace.top/Article/details/gtmngdzclj.html

[T09] Kotlin：扩展函数
来源：http://dali.birdmap.top/Article/details/gtideluqyv.html

fun String.exclaim() = this + "!"
来源：http://dali.sufxvd.cn/Article/details/gtqipveojb.html

[T10] Kotlin：默认参数
来源：http://dali.9152youxi.cn/Article/details/gtigvcvoxv.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.tian-w.cn/Article/details/gticehcjws.html

[T11] Kotlin：协程
来源：http://dali.xylfe.cn/Article/details/gtjzwoppnk.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.cheryme.top/Article/details/gtywpboizq.html

[T12] Kotlin：解构声明
来源：http://dali.jianghu66.top/Article/details/gtuaqbvuim.html

val (a, b) = Pair(1, 2)
来源：http://dali.cucudq.cn/Article/details/gtjpzrbqrm.html

[T13] Kotlin：只读 Map
来源：http://dali.pycfn.com/Article/details/gtouqwnbpw.html

val m = mapOf("a" to 1)
来源：http://dali.ehwqpu.com/Article/details/gtdidkdlfv.html

[T14] Kotlin：循环
来源：http://dali.shzxlz.cn/Article/details/gtrlzrcdwp.html

for (i in 1..10) println(i)
来源：http://dali.fengsongda.top/Article/details/gtjvyywafh.html

[T15] Kotlin：接口
来源：http://dali.snrcjt.cn/Article/details/gtefrsbioo.html

interface Shape { fun area(): Double }
来源：http://dali.jiagoushi.top/Article/details/gtxamaxivl.html

[T16] Swift：Hello World
来源：http://dali.tianlin.xyz/Article/details/gtvjwczkif.html

print("Hello")
来源：http://dali.jinqigufen.top/Article/details/gtwrbekusg.html

[T17] Swift：变量与常量
来源：http://dali.birdmap.top/Article/details/gtbuagfrcu.html

var a = 1;  let b = 2
来源：http://dali.cucudq.cn/Article/details/gtjfaunnxm.html

[T18] Swift：字符串插值
来源：http://dali.zhiwuduotai.top/Article/details/gttrmmfuuh.html

"值: \(b)"
来源：http://dali.zdqjudy.top/Article/details/gtuyodrhjr.html

[T19] Swift：可选绑定
来源：http://dali.snrcjt.cn/Article/details/gtdcnmgxge.html

if let n = opt { print(n) }
来源：http://dali.bjfxy.top/Article/details/gturddboit.html

[T20] Swift：数组操作
来源：http://dali.mhx1999.top/Article/details/gtuujntdmk.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.nanxuanxn.top/Article/details/gtuktgzndp.html

[T21] Swift：遍历
来源：http://dali.meibo888.top/Article/details/gtduuplywf.html

for x in a { print(x) }
来源：http://dali.jlsjyb.cn/Article/details/gtqujohkdx.html

[T22] Swift：字典
来源：http://dali.havefunace.top/Article/details/gtyrnitade.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.jlsjyb.cn/Article/details/gtqlywpqrh.html

[T23] Swift：函数
来源：http://dali.yonumen.top/Article/details/gtbhfowdqa.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.iojbl.cn/Article/details/gtwzasntnl.html

[T24] Swift：闭包
来源：http://dali.gotoacloud.top/Article/details/gtblmrqmax.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.shzxlz.cn/Article/details/gtsaxhnehl.html

[T25] Swift：结构体
来源：http://dali.aizwys.cn/Article/details/gtfhmhxlgy.html

struct P { var x: Int }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfunobdko.html

[T26] Swift：类与重写
来源：http://dali.xylfe.cn/Article/details/gtnvqbyayy.html

class A: Base { override func f() {} }
来源：http://dali.xziqi.cn/Article/details/gtjyiybdpk.html

[T27] Swift：错误处理
来源：http://dali.jlsjyb.cn/Article/details/gtzicjpaay.html

do { try f() } catch { print(error) }
来源：http://dali.redwolf501.top/Article/details/gtvqcpclbz.html

[T28] Swift：枚举
来源：http://dali.zhoulong.xyz/Article/details/gtpulawqej.html

enum Color { case red, green }
来源：http://dali.xuanzx.com/Article/details/gttamqyfej.html

[T29] Swift：guard 提前返回
来源：http://dali.tian-w.cn/Article/details/gtnlcxqhhu.html

guard let x = opt else { return }
来源：http://dali.316326.xyz/Article/details/gtenqrhmqq.html

[T30] Swift：协议
来源：http://dali.nanxuanxn.top/Article/details/gtxpmlawsu.html

protocol Shape { func area() -> Double }
来源：http://dali.cdnleiting.top/Article/details/gtepbjmxxh.html

[T31] Lua：Hello World
来源：http://dali.havefunace.top/Article/details/gtvbillqqy.html

print("Hello")
来源：http://dali.quarkkingdee.top/Article/details/gtmguiyhat.html

[T32] Lua：局部变量
来源：http://dali.0kj1m.cn/Article/details/gtteodgipc.html

local a = 1
来源：http://dali.havefunace.top/Article/details/gtpeyvaxdw.html

[T33] Lua：表（数组）
来源：http://dali.ppjwa.cn/Article/details/gtwcejjept.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.vqdsnc.cn/Article/details/gtkawnoswo.html

[T34] Lua：遍历表
来源：http://dali.vqdsnc.cn/Article/details/gtornmkymi.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhengqikj.top/Article/details/gtdphgcxkh.html

[T35] Lua：字典表
来源：http://dali.wangshuangyany.cn/Article/details/gtpgmqpfmm.html

local d = { a = 1 };  d.b = 2
来源：http://dali.jinqigufen.top/Article/details/gtcsvbinjh.html

[T36] Lua：函数
来源：http://dali.hongshengwenyu.top/Article/details/gtzrmhlozz.html

function add(a, b) return a + b end
来源：http://dali.zhongyouzk.top/Article/details/gtcaoxepao.html

[T37] Lua：字符串拼接
来源：http://dali.yangfankeji.com/Article/details/gtcmomtscy.html

"a" .. "b"
来源：http://dali.0kj1m.cn/Article/details/gtjcxmspmr.html

[T38] Lua：条件
来源：http://dali.hysaishi.cn/Article/details/gtzzuaweor.html

if x > 0 then print("正") end
来源：http://dali.havefunace.top/Article/details/gtuvhztppq.html

[T39] Lua：模式匹配
来源：http://dali.wangdashe.top/Article/details/gtfihtyegs.html

string.find(s, "%d+")
来源：http://dali.ydzc1.top/Article/details/gtogdnlwev.html

[T40] Lua：元表
来源：http://dali.kuanghao11.cn/Article/details/gtzhiombbw.html

setmetatable({}, { __index = base })
来源：http://dali.nanxuanxn.top/Article/details/gtwkzriewh.html

[T41] Perl：Hello World
来源：http://dali.aibaodan.cn/Article/details/gtvzsiuptu.html

print "Hello\n";
来源：http://dali.nanxuanxn.top/Article/details/gtdjwiuwhe.html

[T42] Perl：变量类型
来源：http://dali.hongshengwenyu.top/Article/details/gtufggrjeb.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.haohaochexian.top/Article/details/gtkhebdiwo.html

[T43] Perl：字符串插值
来源：http://dali.dianchejie.cn/Article/details/gtzuunnmzb.html

"值: $a"
来源：http://dali.9152youxi.cn/Article/details/gteaukoxmh.html

[T44] Perl：条件
来源：http://dali.yuxming.cn/Article/details/gtxkohoxsu.html

if ($a > 0) { print "正"; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdyhlqqxf.html

[T45] Perl：数组遍历
来源：http://dali.dashuyun.cn/Article/details/gtjbsdllju.html

for my $x (@arr) { print $x; }
来源：http://dali.aibaodan.cn/Article/details/gtljhbtwvq.html

[T46] Perl：哈希操作
来源：http://dali.sufxvd.cn/Article/details/gtzjxkioaq.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.feifeiyinyue.top/Article/details/gtbunfbpst.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gtoenebzip.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.sysykeji.top/Article/details/gtsrrggyjq.html

[T48] Perl：正则替换
来源：http://dali.9152youxi.cn/Article/details/gtsdyynrzk.html

$s =~ s/old/new/g;
来源：http://dali.chenlongwang.top/Article/details/gtxcyjpfus.html

[T49] Perl：函数
来源：http://dali.bjfxy.top/Article/details/gtwjjwncvc.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.snrcjt.cn/Article/details/gtqzifzazh.html

[T50] Perl：逐行读文件
来源：http://dali.pengpengdd.cyou/Article/details/gtmtobzpcp.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.jqgfzy.top/Article/details/gtsfxywany.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.dianchejie.cn/Article/details/gtotpsiyic.html

[T51] Scala：Hello World
来源：http://dali.jinqigufen.top/Article/details/gthnzrsxlp.html

println("Hello")
来源：http://dali.daria6918.cn/Article/details/gtwpgzjjqf.html

[T52] Scala：变量
来源：http://dali.aizwys.cn/Article/details/gtzdmtqtrb.html

val a = 1;  var b = 2
来源：http://dali.gotoacloud.top/Article/details/gtzppruyoa.html

[T53] Scala：字符串插值
来源：http://dali.cheryme.top/Article/details/gttxxmdkel.html

s"值: $b"
来源：http://dali.yongpay.top/Article/details/gtcratvmof.html

[T54] Scala：集合映射
来源：http://dali.jiagoushi.top/Article/details/gtbehqsrcg.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.daria6918.cn/Article/details/gtippbvfka.html

[T55] Scala：集合过滤
来源：http://dali.nanxinkj.top/Article/details/gtbhtovgdu.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.sweek.top/Article/details/gtanejjxsl.html

[T56] Scala：样例类
来源：http://dali.yj202588.top/Article/details/gtsumyjfvv.html

case class User(name: String, age: Int)
来源：http://dali.sufxvd.cn/Article/details/gtcigewtlt.html

[T57] Scala：模式匹配
来源：http://dali.cdnleiting.top/Article/details/gtoyxatasy.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.cqqwz.cn/Article/details/gtibazgftz.html

[T58] Scala：函数定义
来源：http://dali.chenlongwang.top/Article/details/gtoynqhfjn.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.xuanzx.com/Article/details/gthjrftvoy.html

[T59] Scala：循环
来源：http://dali.yonumen.top/Article/details/gtnmgrtcuc.html

for (i <- 1 to 10) println(i)
来源：http://dali.vqdsnc.cn/Article/details/gtcinlgfmm.html

[T60] Scala：折叠
来源：http://dali.sysykeji.top/Article/details/gtozrdmmaj.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.ppjwa.cn/Article/details/gtekxfoivx.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtsllrogfv.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.hnqzz.top/Article/details/gtolsnmmmr.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtohcgsbvo.html


<!-- 参考信息 -->