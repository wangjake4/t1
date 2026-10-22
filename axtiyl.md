代发 wailian999

df -h;  du -sh *
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jqsdacxk.html

[R62] 找最占空间的文件
来源：http://dali.redwolf501.top/Article/details/gt2gusokuwa.html

du -ah . | sort -rh | head -10
来源：http://dali.zdqjudy.top/Article/details/gt2eibhomzf.html

[R63] 内存与进程
来源：http://dali.zhixingplan.top/Article/details/gt2mmrwobeo.html

free -h;  ps aux | grep nginx
来源：http://dali.shzxlz.cn/Article/details/gt2qwokrbex.html

[R64] 结束进程
来源：http://dali.gaohongyu789.top/Article/details/gt2oxdxuzjd.html

kill -9 $(pgrep -f app.py)
来源：http://dali.ybcxt.top/Article/details/gt2aylqletz.html

[R65] 查看端口占用
来源：http://dali.wangshuangyany.cn/Article/details/gt2uzgkauwv.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.jyoumei.cn/Article/details/gt2ccliclrj.html

[R66] 定时任务
来源：http://dali.jyoumei.cn/Article/details/gt2pslpklsm.html

crontab -e;  crontab -l
来源：http://dali.yvedp.cn/Article/details/gt2svjsrbmi.html

[R67] 生成随机十六进制串
来源：http://dali.sweek.top/Article/details/gt2xgdqsdzo.html

openssl rand -hex 16
来源：http://dali.ivvv.top/Article/details/gt2wlulvoey.html

[R68] 计算文件校验值
来源：http://dali.cashguo.top/Article/details/gt2xfamjqxs.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.wangdashe.top/Article/details/gt2ybojlmnx.html

[R69] 生成随机密码
来源：http://dali.c1oappe.top/Article/details/gt2hhtrgfof.html

head -c 16 /dev/urandom | base64
来源：http://dali.hywenlv.cn/Article/details/gt2qyxruslq.html

[R70] 时间戳与互转
来源：http://dali.xylfe.cn/Article/details/gt2hdacksmc.html

date +%s;  date -d @1700000000
来源：http://dali.meibo888.top/Article/details/gt2jraarsra.html

[R71] 日期格式化
来源：http://dali.shanyushiyangtech.top/Article/details/gt2papkruej.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.yuanzhike.top/Article/details/gt2jgaissid.html

[R72] 等待端口就绪
来源：http://dali.fzhhl.top/Article/details/gt2agnnywlw.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.cqqwz.cn/Article/details/gt2pssuykiz.html

[R73] 分割大日志
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2suuyumsl.html

split -l 1000 big.log part_
来源：http://dali.yj202588.top/Article/details/gt2zpudbskq.html

[R74] 批量重命名
来源：http://dali.yueranfly.top/Article/details/gt2pklzrnmg.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.andypj.xyz/Article/details/gt2mqgappkq.html

[R75] 导出环境变量
来源：http://dali.c1oappe.top/Article/details/gt2zsrwudzy.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.jianghu66.top/Article/details/gt2xjjpdwjb.html

[R76] 使用临时文件
来源：http://dali.pycfn.com/Article/details/gt2bvfpwkbf.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.svipenyu.cn/Article/details/gt2rcwmozrg.html

[R77] 读取用户输入
来源：http://dali.yj20258.top/Article/details/gt2loqbcxde.html

read -rp "请输入: " ans
来源：http://dali.tianlin.xyz/Article/details/gt2fpldoyuf.html

[R78] 交互式菜单
来源：http://dali.xylfe.cn/Article/details/gt2dtweeaxg.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.cashguo.top/Article/details/gt2zhifvfqt.html

[R79] 解析命令行选项
来源：http://dali.zdqjudy.top/Article/details/gt2neiqoyko.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.nanxuanxn.top/Article/details/gt2hisujnhg.html

[R80] 查看脚本执行耗时
来源：http://dali.gzhubu.top/Article/details/gt2umavygnu.html

time ./run.sh
来源：http://dali.zhoulong.xyz/Article/details/gt2rscbxczg.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2tdhflugb.html

S. C / C++ 专题
来源：http://dali.ehwqpu.com/Article/details/gt2gnoxwgjv.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2mmfgjllz.html

[S01] C：Hello World
来源：http://dali.gzhubu.top/Article/details/gt2aidmzlif.html

#include <stdio.h>
来源：http://dali.chenzaomai.com/Article/details/gt2oumlyuqq.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.jianghu66.top/Article/details/gt2tfaozeqf.html

[S02] C：变量与格式化输出
来源：http://dali.nanxinkj.top/Article/details/gt2ambcbabj.html

int a = 10; printf("%d\n", a);
来源：http://dali.cucudq.cn/Article/details/gt2zxmgmvrz.html

[S03] C：读入整数
来源：http://dali.sweek.top/Article/details/gt2libeqydb.html

int x; scanf("%d", &x);
来源：http://dali.cashguo.top/Article/details/gt2vftozcjq.html

[S04] C：字符串复制
来源：http://dali.aibaodan.cn/Article/details/gt2qtoyegid.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.havefunace.top/Article/details/gt2dptlqaul.html

[S05] C：字符串长度
来源：http://dali.gzhubu.top/Article/details/gt2cpnklxdv.html

strlen(s)
来源：http://dali.gotoacloud.top/Article/details/gt2wktlrbay.html

[S06] C：字符串比较
来源：http://dali.aizwys.cn/Article/details/gt2gvftsaer.html

strcmp(a, b) == 0
来源：http://dali.cheryme.top/Article/details/gt2rwkeggrc.html

[S07] C：数组遍历求和
来源：http://dali.birdmap.top/Article/details/gt2kpbxhtkz.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.jqgfzy.top/Article/details/gt2nddjdfdc.html

[S08] C：动态内存分配与释放
来源：http://dali.jianghu66.top/Article/details/gt2slnrfexr.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.tian-w.cn/Article/details/gt2xgtbhfkz.html

[S09] C：结构体定义与初始化
来源：http://dali.yj20258.top/Article/details/gt2ziiyhwqb.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.pycfn.com/Article/details/gt2dlpqwlfi.html

[S10] C：指针与解引用
来源：http://dali.meibo888.top/Article/details/gt2kqjwzzbm.html

int *p = &a;  *p = 5;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zhmsuswn.html

[S11] C：逐行读文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ldbpoxui.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.shzxlz.cn/Article/details/gt2nehfyetn.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.hnqzz.top/Article/details/gt2lghffzaj.html

fclose(f);
来源：http://dali.iojbl.cn/Article/details/gt2vjlkjjyq.html

[S12] C：写文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dytvowby.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.haohaochexian.top/Article/details/gt2kznfpgzp.html

[S13] C：宏定义
来源：http://dali.ivvv.top/Article/details/gt2uukvpqgg.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.yangfankeji.com/Article/details/gt2wxctywna.html

[S14] C：枚举
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uoirdkoo.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.ppjwa.cn/Article/details/gt2ikeldvwo.html

[S15] C：类型转换
来源：http://dali.gaohongyu789.top/Article/details/gt2lcclxviw.html

(double) a / b
来源：http://dali.xuetiantiany.cn/Article/details/gt2vtijdnqz.html

[S16] C：位操作置位
来源：http://dali.yangfankeji.com/Article/details/gt2rthldlim.html

x |= (1 << 3);
来源：http://dali.nanxuanxn.top/Article/details/gt2zrgcwbtu.html

[S17] C：安全拼接字符串
来源：http://dali.xuetiantiany.cn/Article/details/gt2cethjlig.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.wangdashe.top/Article/details/gt2wffkufom.html

[S18] C：命令行参数
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vwtdlxiq.html

int main(int argc, char **argv)
来源：http://dali.chenlongwang.top/Article/details/gt2pawtepjc.html

[S19] C：快速排序
来源：http://dali.hysaishi.cn/Article/details/gt2dflogurc.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.meibo888.top/Article/details/gt2rmjoalfh.html

[S20] C：二分查找
来源：http://dali.dianchejie.cn/Article/details/gt2ybvximxa.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.snrcjt.cn/Article/details/gt2lyqhdlku.html

[S21] C：字符类别判断
来源：http://dali.ivvv.top/Article/details/gt2jqpwvypw.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.guannengcc.top/Article/details/gt2xmdwnens.html

[S22] C：字符串转数字
来源：http://dali.chenlongwang.top/Article/details/gt2pobsljqn.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.hnqzz.top/Article/details/gt2atybqost.html

[S23] C：随机数
来源：http://dali.shangyingyoupin.top/Article/details/gt2drnfosaw.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.daria6918.cn/Article/details/gt2zetttufq.html

[S24] C：获取本地时间
来源：http://dali.ydzc1.top/Article/details/gt2fryqpukt.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mpkbqaay.html

[S25] C：内存拷贝
来源：http://dali.zhixingplan.top/Article/details/gt2mwgdxcbj.html

memcpy(dst, src, n);
来源：http://dali.9152youxi.cn/Article/details/gt2mjljbwzt.html

[S26] C：内存清零
来源：http://dali.yuxming.cn/Article/details/gt2qdsknhln.html

memset(a, 0, sizeof a);
来源：http://dali.yangfankeji.com/Article/details/gt2dzlqwdjo.html

[S27] C：定义常量
来源：http://dali.hysaishi.cn/Article/details/gt2siptbzuu.html

const double PI = 3.14159;
来源：http://dali.yuanzhike.top/Article/details/gt2dmvexclg.html

[S28] C：静态变量
来源：http://dali.ybcxt.top/Article/details/gt2kduhxurn.html

static int counter = 0;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2suuvhcci.html

[S29] C：变参函数
来源：http://dali.0kj1m.cn/Article/details/gt2zexrgdxk.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.guowangkeji.top/Article/details/gt2ntnaszil.html

[S30] C：头文件保护
来源：http://dali.hfpthk.cn/Article/details/gt2djaljvoz.html

#ifndef X_H
来源：http://dali.sweek.top/Article/details/gt2gtssbsbc.html

#define X_H
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cauwohks.html

#endif
来源：http://dali.sysykeji.top/Article/details/gt2yqkdaykx.html

[S31] C++：Hello World
来源：http://dali.kuanghao11.cn/Article/details/gt2tawjhjxa.html

#include <iostream>
来源：http://dali.yanxiufei.cn/Article/details/gt2hbarduet.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2beauhzme.html

[S32] C++：字符串
来源：http://dali.smart0.xyz/Article/details/gt2srnzaini.html

std::string s = "hi";  s += "!";
来源：http://dali.quarkkingdee.top/Article/details/gt2yegmxjwr.html

[S33] C++：vector 增删
来源：http://dali.haohaochexian.top/Article/details/gt2zdwfimoy.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.hongshengwenyu.top/Article/details/gt2ktbyuicx.html

[S34] C++：遍历 vector
来源：http://dali.yueranfly.top/Article/details/gt2uvjybtze.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.c1oappe.top/Article/details/gt2vmcigyhf.html

[S35] C++：map
来源：http://dali.pengpengdd.cyou/Article/details/gt2kklyxphc.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.fengsongda.top/Article/details/gt2exrtahyy.html

[S36] C++：unordered_map
来源：http://dali.zhengqikj.top/Article/details/gt2dctwzmrm.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.iojbl.cn/Article/details/gt2ipdtxafl.html

[S37] C++：set
来源：http://dali.yangfankeji.com/Article/details/gt2rljqucaa.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.yj20258888.top/Article/details/gt2dcojotvm.html

[S38] C++：排序
来源：http://dali.yanxiufei.cn/Article/details/gt2lycodtff.html

std::sort(v.begin(), v.end());
来源：http://dali.tanke756.top/Article/details/gt2psaytxfp.html

[S39] C++：自定义比较器排序
来源：http://dali.zhongyouzk.top/Article/details/gt2mjdnqeyn.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.tian-w.cn/Article/details/gt2pmvgjzqm.html

[S40] C++：查找元素
来源：http://dali.yj202588.top/Article/details/gt2plofowum.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.yvedp.cn/Article/details/gt2nbcjhxvj.html

[S41] C++：类与构造函数
来源：http://dali.havefunace.top/Article/details/gt2qfvamomx.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zycfv.cn/Article/details/gt2sjdxppmc.html

[S42] C++：继承与虚函数
来源：http://dali.ydzc1.top/Article/details/gt2mxbpmiam.html

class B : public Base { public: void f() override {} };
来源：http://dali.jlsjyb.cn/Article/details/gt2lqsodiai.html

[S43] C++：智能指针
来源：http://dali.jinghuilouyu.cn/Article/details/gt2actcwejh.html

auto p = std::make_unique<int>(5);
来源：http://dali.nanxinkj.top/Article/details/gt2awszbdkd.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2rbkzpeov.html

void inc(int &x) { ++x; }
来源：http://dali.daria6918.cn/Article/details/gt2cflctbha.html

[S45] C++：lambda
来源：http://dali.mhx1999.top/Article/details/gt2iantusgj.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.yanxiufei.cn/Article/details/gt2inebmymr.html

[S46] C++：函数模板
来源：http://dali.hywenlv.cn/Article/details/gt2cjryywks.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhoulong.xyz/Article/details/gt2smldsyvp.html

[S47] C++：结构化绑定遍历
来源：http://dali.sxryk.cn/Article/details/gt2qjpqsjyb.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.jiagoushi.top/Article/details/gt2kaptbrvd.html

[S48] C++：逐行读文件
来源：http://dali.yanxiufei.cn/Article/details/gt2hncrbcld.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.chenjidiqi.icu/Article/details/gt2omvhmnyc.html

while (std::getline(in, line)) { }
来源：http://dali.zhongyouzk.top/Article/details/gt2ynjercxo.html

[S49] C++：写文件
来源：http://dali.yuxming.cn/Article/details/gt2mwicpgme.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.ivvv.top/Article/details/gt2ntvtiiyz.html

[S50] C++：格式化数字
来源：http://dali.svipenyu.cn/Article/details/gt2eowifiqo.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.yongpay.top/Article/details/gt2azmjknjy.html

[S51] C++：显式类型转换
来源：http://dali.xylfe.cn/Article/details/gt2msqicvuj.html

static_cast<double>(a) / b
来源：http://dali.iojbl.cn/Article/details/gt2cnxxoged.html

[S52] C++：const 与 noexcept
来源：http://dali.nanxinkj.top/Article/details/gt2iaigsmtt.html

int size() const noexcept { return n_; }
来源：http://dali.zycfv.cn/Article/details/gt2pmzmlygm.html

[S53] C++：移动语义
来源：http://dali.birdmap.top/Article/details/gt2bvqopfdi.html

std::vector<int> w = std::move(v);
来源：http://dali.hfpthk.cn/Article/details/gt2rlrccfmh.html

[S54] C++：异常处理
来源：http://dali.sufxvd.cn/Article/details/gt2afuxsmcs.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.dashuyun.cn/Article/details/gt2mgqsuwqz.html

[S55] C++：结构化绑定
来源：http://dali.zhiwuduotai.top/Article/details/gt2sqhwdhqh.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.shzxlz.cn/Article/details/gt2erowdjri.html

[S56] C++：optional
来源：http://dali.feifeiyinyue.top/Article/details/gt2veovqsbd.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.tianlin.xyz/Article/details/gt2ofrvafkz.html

[S57] C++：编译期常量
来源：http://dali.ivvv.top/Article/details/gt2ydreploi.html

constexpr int N = 10;
来源：http://dali.daxiang520.top/Article/details/gt2rbrcajip.html

[S58] C++：命名空间
来源：http://dali.zhoulong.xyz/Article/details/gt2rsfippop.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wgizyvhx.html

[S59] C++：静态断言
来源：http://dali.meibo888.top/Article/details/gt2rcdlmwqq.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.hnxiangtu.top/Article/details/gt2ojwuppwc.html

[S60] C++：遍历并删除元素
来源：http://dali.xylfe.cn/Article/details/gt2oyqumtpu.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.hywenlv.cn/Article/details/gt2zbbpgaky.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gt2jugufqon.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhixingplan.top/Article/details/gt2qvxtoqjz.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gt2zapcenlt.html

[T01] Kotlin：Hello World
来源：http://dali.gaohongyu789.top/Article/details/gt2dwfeqmtm.html

println("Hello")
来源：http://dali.aizwys.cn/Article/details/gt2xdqsvegv.html

[T02] Kotlin：变量
来源：http://dali.tianlin.xyz/Article/details/gt2rxzcbqfu.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.jinqigufen.top/Article/details/gt2zaraqcwk.html

[T03] Kotlin：字符串模板
来源：http://dali.quarkkingdee.top/Article/details/gt2rqoziyee.html

"值: $b"
来源：http://dali.havefunace.top/Article/details/gt2uckuuxif.html

[T04] Kotlin：空安全
来源：http://dali.redwolf501.top/Article/details/gt2mcvbdgew.html

val n: String? = null;  n?.length
来源：http://dali.zdqjudy.top/Article/details/gt2ohwehujs.html

[T05] Kotlin：when 表达式
来源：http://dali.9152youxi.cn/Article/details/gt2hyxxxzxi.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.shzxlz.cn/Article/details/gt2hdccthpn.html

[T06] Kotlin：集合映射
来源：http://dali.gogol.net.cn/Article/details/gt2ycnofnms.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.c1oappe.top/Article/details/gt2kbjioyze.html

[T07] Kotlin：集合过滤
来源：http://dali.gogol.net.cn/Article/details/gt2oxvzlify.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhixingplan.top/Article/details/gt2gxcupvrf.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2dtlaqzcs.html

data class User(val name: String, val age: Int)
来源：http://dali.hfpthk.cn/Article/details/gt2frzlzjta.html

[T09] Kotlin：扩展函数
来源：http://dali.tian-w.cn/Article/details/gt2fcztgisu.html

fun String.exclaim() = this + "!"
来源：http://dali.sxryk.cn/Article/details/gt2cuozpjoh.html

[T10] Kotlin：默认参数
来源：http://dali.zhengqikj.top/Article/details/gt2fxpijxjl.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.yangfankeji.com/Article/details/gt2juakhvjl.html

[T11] Kotlin：协程
来源：http://dali.jyoumei.cn/Article/details/gt2rpwtbmiu.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.dashuyun.cn/Article/details/gt2nptpzeyq.html

[T12] Kotlin：解构声明
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2akiofujv.html

val (a, b) = Pair(1, 2)
来源：http://dali.smart0.xyz/Article/details/gt2hahxatpp.html

[T13] Kotlin：只读 Map
来源：http://dali.zdqjudy.top/Article/details/gt2wqfzlbug.html

val m = mapOf("a" to 1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2incvfurf.html

[T14] Kotlin：循环
来源：http://dali.shuidangran.top/Article/details/gt2hsluvhtz.html

for (i in 1..10) println(i)
来源：http://dali.dashuyun.cn/Article/details/gt2omjgqwpy.html

[T15] Kotlin：接口
来源：http://dali.hfpthk.cn/Article/details/gt2gbqvngiy.html

interface Shape { fun area(): Double }
来源：http://dali.gotoacloud.top/Article/details/gt2pziacmfm.html

[T16] Swift：Hello World
来源：http://dali.chenlongwang.top/Article/details/gt2nxpzospi.html

print("Hello")
来源：http://dali.yangfankeji.com/Article/details/gt2lypxrmze.html

[T17] Swift：变量与常量
来源：http://dali.redwolf501.top/Article/details/gt2doyhmtep.html

var a = 1;  let b = 2
来源：http://dali.yj20258888.top/Article/details/gt2txfmewby.html

[T18] Swift：字符串插值
来源：http://dali.nanxinkj.top/Article/details/gt2nzfkmqhm.html

"值: \(b)"
来源：http://dali.chenjidiqi.icu/Article/details/gt2czfrkbjo.html

[T19] Swift：可选绑定
来源：http://dali.dianchejie.cn/Article/details/gt2ajkyfcbt.html

if let n = opt { print(n) }
来源：http://dali.daria6918.cn/Article/details/gt2xbauoaqd.html

[T20] Swift：数组操作
来源：http://dali.birdmap.top/Article/details/gt2boxhgeeo.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.guannengcc.top/Article/details/gt2oagvjtpk.html

[T21] Swift：遍历
来源：http://dali.ydzc1.top/Article/details/gt2qrcjbmgc.html

for x in a { print(x) }
来源：http://dali.zhongyouzk.top/Article/details/gt2mqkarxfd.html

[T22] Swift：字典
来源：http://dali.nwbrower.top/Article/details/gt2rtbcxmzz.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.gotoacloud.top/Article/details/gt2picaryue.html

[T23] Swift：函数
来源：http://dali.hnxiangtu.top/Article/details/gt2pfapwcru.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.chenzaomai.com/Article/details/gt2azlplknx.html

[T24] Swift：闭包
来源：http://dali.feifeiyinyue.top/Article/details/gt2zobewluk.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.xinyue.icu/Article/details/gt2ylaabmum.html

[T25] Swift：结构体
来源：http://dali.ydzc1.top/Article/details/gt2lwykxwmd.html

struct P { var x: Int }
来源：http://dali.chenlongwang.top/Article/details/gt2egkwedam.html

[T26] Swift：类与重写
来源：http://dali.ybcxt.top/Article/details/gt2ycxgvvcc.html

class A: Base { override func f() {} }
来源：http://dali.iojbl.cn/Article/details/gt2sproalxh.html

[T27] Swift：错误处理
来源：http://dali.jiagoushi.top/Article/details/gt2fxazaffg.html

do { try f() } catch { print(error) }
来源：http://dali.yanxiufei.cn/Article/details/gt2fltmbtfg.html

[T28] Swift：枚举
来源：http://dali.iojbl.cn/Article/details/gt2quwzfjqo.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2xxvgdgqw.html

[T29] Swift：guard 提前返回
来源：http://dali.nanxuanxn.top/Article/details/gt2qjyvzqij.html

guard let x = opt else { return }
来源：http://dali.meibo888.top/Article/details/gt2wxipawvi.html

[T30] Swift：协议
来源：http://dali.smart0.xyz/Article/details/gt2afiyqtab.html

protocol Shape { func area() -> Double }
来源：http://dali.cashguo.top/Article/details/gt2bxufuhex.html

[T31] Lua：Hello World
来源：http://dali.guowangkeji.top/Article/details/gt2ugfatmlc.html

print("Hello")
来源：http://dali.jlsjyb.cn/Article/details/gt2jqjnytha.html

[T32] Lua：局部变量
来源：http://dali.dianchejie.cn/Article/details/gt2ougduhgu.html

local a = 1
来源：http://dali.chenlongwang.top/Article/details/gt2zkotfdoz.html

[T33] Lua：表（数组）
来源：http://dali.ybcxt.top/Article/details/gt2wwyoyjoi.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.sufxvd.cn/Article/details/gt2klgbwvzj.html

[T34] Lua：遍历表
来源：http://dali.pengpengdd.cyou/Article/details/gt2ywyfxhia.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.dianchejie.cn/Article/details/gt2leikngae.html

[T35] Lua：字典表
来源：http://dali.gaohongyu789.top/Article/details/gt2wovsbjhz.html

local d = { a = 1 };  d.b = 2
来源：http://dali.hfpthk.cn/Article/details/gt2lsnuffsk.html

[T36] Lua：函数
来源：http://dali.sweek.top/Article/details/gt2xoceiijb.html

function add(a, b) return a + b end
来源：http://dali.ivvv.top/Article/details/gt2nkqovhop.html

[T37] Lua：字符串拼接
来源：http://dali.daxiang520.top/Article/details/gt2nmrmqwxe.html

"a" .. "b"
来源：http://dali.guannengcc.top/Article/details/gt2gwuwbkmr.html

[T38] Lua：条件
来源：http://dali.meibo888.top/Article/details/gt2ikwrviep.html

if x > 0 then print("正") end
来源：http://dali.zhixingplan.top/Article/details/gt2dirfpcsq.html

[T39] Lua：模式匹配
来源：http://dali.nwbrower.top/Article/details/gt2fsfdswjy.html

string.find(s, "%d+")
来源：http://dali.0kj1m.cn/Article/details/gt2jjzopftd.html

[T40] Lua：元表
来源：http://dali.gzhubu.top/Article/details/gt2wvdijjtb.html

setmetatable({}, { __index = base })
来源：http://dali.guannengcc.top/Article/details/gt2abmljjrt.html

[T41] Perl：Hello World
来源：http://dali.wangdashe.top/Article/details/gt2lwqvsqxc.html

print "Hello\n";
来源：http://dali.xuetiantiany.cn/Article/details/gt2nvihmtfz.html

[T42] Perl：变量类型
来源：http://dali.9152youxi.cn/Article/details/gt2bylzrexm.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhongyouzk.top/Article/details/gt2jwmkplbg.html

[T43] Perl：字符串插值
来源：http://dali.mhx1999.top/Article/details/gt2jplvtxee.html

"值: $a"
来源：http://dali.xuetiantiany.cn/Article/details/gt2mzhxcywh.html

[T44] Perl：条件
来源：http://dali.guowangkeji.top/Article/details/gt2wyzznjqn.html

if ($a > 0) { print "正"; }
来源：http://dali.jlsjyb.cn/Article/details/gt2yruayivy.html

[T45] Perl：数组遍历
来源：http://dali.snrcjt.cn/Article/details/gt2pzwnxyyj.html

for my $x (@arr) { print $x; }
来源：http://dali.gogol.net.cn/Article/details/gt2fjusyufn.html

[T46] Perl：哈希操作
来源：http://dali.316326.xyz/Article/details/gt2tjxgmcpx.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.xuanzx.com/Article/details/gt2vlhwwypj.html

[T47] Perl：正则捕获
来源：http://dali.birdmap.top/Article/details/gt2vdrrpwrf.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.xuanzx.com/Article/details/gt2ywsbbgpu.html

[T48] Perl：正则替换
来源：http://dali.redwolf501.top/Article/details/gt2pcbliubk.html

$s =~ s/old/new/g;
来源：http://dali.yj20258888.top/Article/details/gt2mrjmscqy.html

[T49] Perl：函数
来源：http://dali.feifeiyinyue.top/Article/details/gt2exbtcosu.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.yvedp.cn/Article/details/gt2wdqhlcdr.html

[T50] Perl：逐行读文件
来源：http://dali.wangdashe.top/Article/details/gt2fyevvhrl.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.snrcjt.cn/Article/details/gt2vbtwmwxy.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.cqqwz.cn/Article/details/gt2lpvobfgr.html

[T51] Scala：Hello World
来源：http://dali.snrcjt.cn/Article/details/gt2xqmcjise.html

println("Hello")
来源：http://dali.nanxinkj.top/Article/details/gt2yudompbx.html

[T52] Scala：变量
来源：http://dali.cashguo.top/Article/details/gt2aroalcwb.html

val a = 1;  var b = 2
来源：http://dali.birdmap.top/Article/details/gt2frtdapnp.html

[T53] Scala：字符串插值
来源：http://dali.haohaochexian.top/Article/details/gt2vudqapca.html

s"值: $b"
来源：http://dali.zdqjudy.top/Article/details/gt2nzolfvgq.html

[T54] Scala：集合映射
来源：http://dali.jqgfzy.top/Article/details/gt2afldlnph.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.hywenlv.cn/Article/details/gt2pnlppwcl.html

[T55] Scala：集合过滤
来源：http://dali.sysykeji.top/Article/details/gt2liwaxsgq.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.redwolf501.top/Article/details/gt2phhngzgp.html

[T56] Scala：样例类
来源：http://dali.fengsongda.top/Article/details/gt2gogxpyjh.html

case class User(name: String, age: Int)
来源：http://dali.feifeiyinyue.top/Article/details/gt2uykgojvq.html

[T57] Scala：模式匹配
来源：http://dali.yueranfly.top/Article/details/gt2ewpdmuhj.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.hnqzz.top/Article/details/gt2gkgzsqaw.html

[T58] Scala：函数定义
来源：http://dali.zdqjudy.top/Article/details/gt2mqffeayp.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.pycfn.com/Article/details/gt2myuezzjj.html

[T59] Scala：循环
来源：http://dali.zhongyouzk.top/Article/details/gt2sjkebxja.html

for (i <- 1 to 10) println(i)
来源：http://dali.yj202588.top/Article/details/gt2dmxkknon.html

[T60] Scala：折叠
来源：http://dali.shuidangran.top/Article/details/gt2mzkorkje.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.cashguo.top/Article/details/gt2lbnehbyo.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gt2wnfkextm.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.hongshengwenyu.top/Article/details/gt2qnrnbbrd.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2vbiejzkv.html

[U01] Py：创建虚拟环境
来源：http://dali.ppjwa.cn/Article/details/gt2lvyosmuu.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.hammf.cn/Article/details/gt2mxevppzl.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhoulong.xyz/Article/details/gt2virvgnla.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.jiagoushi.top/Article/details/gt2tzzdhwmg.html


<!-- 参考信息 -->