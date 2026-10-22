代发 wailian999

free -h;  ps aux | grep nginx
来源：http://dali.xylfe.cn/Article/details/gt2szgmuuow.html

[R64] 结束进程
来源：http://dali.pengpengdd.cyou/Article/details/gt2pzgldmjh.html

kill -9 $(pgrep -f app.py)
来源：http://dali.hfpthk.cn/Article/details/gt2wyskgrib.html

[R65] 查看端口占用
来源：http://dali.shuidangran.top/Article/details/gt2opljtzpk.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.yj20258.top/Article/details/gt2minlwfrr.html

[R66] 定时任务
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qstwvpfb.html

crontab -e;  crontab -l
来源：http://dali.tian-w.cn/Article/details/gt2qzizurdz.html

[R67] 生成随机十六进制串
来源：http://dali.aizwys.cn/Article/details/gt2thwbwqxm.html

openssl rand -hex 16
来源：http://dali.hammf.cn/Article/details/gt2eakzcvta.html

[R68] 计算文件校验值
来源：http://dali.guowangkeji.top/Article/details/gt2bkmemszz.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.jiagoushi.top/Article/details/gt2cznkmrki.html

[R69] 生成随机密码
来源：http://dali.jinghuilouyu.cn/Article/details/gt2khfiqfse.html

head -c 16 /dev/urandom | base64
来源：http://dali.svipenyu.cn/Article/details/gt2pjpdfjfp.html

[R70] 时间戳与互转
来源：http://dali.hongshengwenyu.top/Article/details/gt2emlwitho.html

date +%s;  date -d @1700000000
来源：http://dali.yj202588.top/Article/details/gt2hbboyzuv.html

[R71] 日期格式化
来源：http://dali.havefunace.top/Article/details/gt2cndccfzd.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2wmkfylzg.html

[R72] 等待端口就绪
来源：http://dali.shzxlz.cn/Article/details/gt2hlxlersv.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zdqjudy.top/Article/details/gt2ojdaavah.html

[R73] 分割大日志
来源：http://dali.yuxming.cn/Article/details/gt2txvzbcln.html

split -l 1000 big.log part_
来源：http://dali.havefunace.top/Article/details/gt2cuupsxbd.html

[R74] 批量重命名
来源：http://dali.cheryme.top/Article/details/gt2vfaznpub.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.smart0.xyz/Article/details/gt2gzjufmgz.html

[R75] 导出环境变量
来源：http://dali.yanxiufei.cn/Article/details/gt2pjzbxvry.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.yj20258888.top/Article/details/gt2oqczezel.html

[R76] 使用临时文件
来源：http://dali.sxryk.cn/Article/details/gt2ucyowqpx.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.shangyingyoupin.top/Article/details/gt2viuwddwe.html

[R77] 读取用户输入
来源：http://dali.guannengcc.top/Article/details/gt2cflicvfy.html

read -rp "请输入: " ans
来源：http://dali.haohaochexian.top/Article/details/gt2xvrrgnkm.html

[R78] 交互式菜单
来源：http://dali.ybcxt.top/Article/details/gt2kurcfpmc.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.vqdsnc.cn/Article/details/gt2zpaaboxt.html

[R79] 解析命令行选项
来源：http://dali.zhoulong.xyz/Article/details/gt2oqfggisf.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.316326.xyz/Article/details/gt2iuzsfitn.html

[R80] 查看脚本执行耗时
来源：http://dali.aibaodan.cn/Article/details/gt2zkdkjqhn.html

time ./run.sh
来源：http://dali.cucudq.cn/Article/details/gt2ddihxytr.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gt2tvgeblnt.html

S. C / C++ 专题
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nmoxcrhz.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2mbltrfpb.html

[S01] C：Hello World
来源：http://dali.fengsongda.top/Article/details/gt2daujrqmn.html

#include <stdio.h>
来源：http://dali.hongshengwenyu.top/Article/details/gt2nyeeaxsc.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.yueranfly.top/Article/details/gt2gaubtmli.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2wwqmoerd.html

int a = 10; printf("%d\n", a);
来源：http://dali.jyoumei.cn/Article/details/gt2smgmdlft.html

[S03] C：读入整数
来源：http://dali.zhixingplan.top/Article/details/gt2rivdljwu.html

int x; scanf("%d", &x);
来源：http://dali.hnxiangtu.top/Article/details/gt2lecxgspg.html

[S04] C：字符串复制
来源：http://dali.jinqigufen.top/Article/details/gt2cdfdtpyq.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.aibaodan.cn/Article/details/gt2ectldctr.html

[S05] C：字符串长度
来源：http://dali.hnxiangtu.top/Article/details/gt2omwgnnsl.html

strlen(s)
来源：http://dali.yuxming.cn/Article/details/gt2bsqqqpic.html

[S06] C：字符串比较
来源：http://dali.chenzaomai.com/Article/details/gt2oxkcdtdy.html

strcmp(a, b) == 0
来源：http://dali.meibo888.top/Article/details/gt2gtvfprno.html

[S07] C：数组遍历求和
来源：http://dali.ybcxt.top/Article/details/gt2zjsqfbqy.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.jyoumei.cn/Article/details/gt2zptqogmi.html

[S08] C：动态内存分配与释放
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jagtqknf.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.snrcjt.cn/Article/details/gt2smuneybm.html

[S09] C：结构体定义与初始化
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uwzdkeau.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.shangyingyoupin.top/Article/details/gt2jwpldony.html

[S10] C：指针与解引用
来源：http://dali.haohaochexian.top/Article/details/gt2pwofeuha.html

int *p = &a;  *p = 5;
来源：http://dali.cheryme.top/Article/details/gt2dccfmdsk.html

[S11] C：逐行读文件
来源：http://dali.hnqzz.top/Article/details/gt2xqeknwol.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.jianghu66.top/Article/details/gt2vzeseyhl.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.jinqigfzy.top/Article/details/gt2pdghvgvt.html

fclose(f);
来源：http://dali.cucudq.cn/Article/details/gt2wwglaswa.html

[S12] C：写文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nfetdfmi.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.daria6918.cn/Article/details/gt2whosmmig.html

[S13] C：宏定义
来源：http://dali.cashguo.top/Article/details/gt2qxopfbnw.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhongyouzk.top/Article/details/gt2liimujzm.html

[S14] C：枚举
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gohfbeen.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.hywenlv.cn/Article/details/gt2vcespbmt.html

[S15] C：类型转换
来源：http://dali.vqdsnc.cn/Article/details/gt2nsyalwmg.html

(double) a / b
来源：http://dali.hnxiangtu.top/Article/details/gt2ihbtiicf.html

[S16] C：位操作置位
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xfdjofzw.html

x |= (1 << 3);
来源：http://dali.zhixingplan.top/Article/details/gt2ejfwigwo.html

[S17] C：安全拼接字符串
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cauqxfie.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2aivkqtre.html

[S18] C：命令行参数
来源：http://dali.andypj.xyz/Article/details/gt2jkhnhuoa.html

int main(int argc, char **argv)
来源：http://dali.xinyue.icu/Article/details/gt2snxheghh.html

[S19] C：快速排序
来源：http://dali.yongpay.top/Article/details/gt2tnghtqzm.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.jlsjyb.cn/Article/details/gt2hrswwkhi.html

[S20] C：二分查找
来源：http://dali.gogol.net.cn/Article/details/gt2aqflgymb.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.jlsjyb.cn/Article/details/gt2eotlleqe.html

[S21] C：字符类别判断
来源：http://dali.jinqigfzy.top/Article/details/gt2ckyrdbho.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.nwbrower.top/Article/details/gt2grmnhati.html

[S22] C：字符串转数字
来源：http://dali.jqgfzy.top/Article/details/gt2gbphdtwk.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.bjfxy.top/Article/details/gt2gjapwbit.html

[S23] C：随机数
来源：http://dali.sysykeji.top/Article/details/gt2mqvbuium.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.sxryk.cn/Article/details/gt2eafpqowk.html

[S24] C：获取本地时间
来源：http://dali.zhixingplan.top/Article/details/gt2uliwbsrn.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.hnxiangtu.top/Article/details/gt2fheelzbs.html

[S25] C：内存拷贝
来源：http://dali.havefunace.top/Article/details/gt2ecxiomuc.html

memcpy(dst, src, n);
来源：http://dali.shangyingyoupin.top/Article/details/gt2nqbaqaca.html

[S26] C：内存清零
来源：http://dali.zhoulong.xyz/Article/details/gt2mtloxsqp.html

memset(a, 0, sizeof a);
来源：http://dali.jqgufenzy.top/Article/details/gt2audpjkry.html

[S27] C：定义常量
来源：http://dali.yueranfly.top/Article/details/gt2bcaojskm.html

const double PI = 3.14159;
来源：http://dali.sweek.top/Article/details/gt2gyaaneso.html

[S28] C：静态变量
来源：http://dali.nwbrower.top/Article/details/gt2eihxiupq.html

static int counter = 0;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gvzloojy.html

[S29] C：变参函数
来源：http://dali.xuetiantiany.cn/Article/details/gt2fcaryvps.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.cqqwz.cn/Article/details/gt2garzmhli.html

[S30] C：头文件保护
来源：http://dali.yj20258.top/Article/details/gt2nnhmcesj.html

#ifndef X_H
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uoxqygcf.html

#define X_H
来源：http://dali.pycfn.com/Article/details/gt2dtypwfpm.html

#endif
来源：http://dali.xylfe.cn/Article/details/gt2nbyuptpu.html

[S31] C++：Hello World
来源：http://dali.zhongyouzk.top/Article/details/gt2agqnxump.html

#include <iostream>
来源：http://dali.ehwqpu.com/Article/details/gt2wvbnqswx.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.hfpthk.cn/Article/details/gt2lgqlzrra.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2qyqjxoxi.html

std::string s = "hi";  s += "!";
来源：http://dali.sxryk.cn/Article/details/gt2uutgojeo.html

[S33] C++：vector 增删
来源：http://dali.hysaishi.cn/Article/details/gt2csinbvsu.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.fengsongda.top/Article/details/gt2oodmfuyx.html

[S34] C++：遍历 vector
来源：http://dali.guowangkeji.top/Article/details/gt2flvwhnhz.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.yuanzhike.top/Article/details/gt2cnucrztn.html

[S35] C++：map
来源：http://dali.yangfankeji.com/Article/details/gt2ytcdmcxk.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2eadphdxk.html

[S36] C++：unordered_map
来源：http://dali.sysykeji.top/Article/details/gt2gbznurqy.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hysaishi.cn/Article/details/gt2tzeveegk.html

[S37] C++：set
来源：http://dali.wangshuangyany.cn/Article/details/gt2gcxspecu.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.yuxming.cn/Article/details/gt2dyjjejya.html

[S38] C++：排序
来源：http://dali.tian-w.cn/Article/details/gt2cehewlvn.html

std::sort(v.begin(), v.end());
来源：http://dali.shangyingyoupin.top/Article/details/gt2nzgxyowe.html

[S39] C++：自定义比较器排序
来源：http://dali.jiagoushi.top/Article/details/gt2lsfysoph.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.sufxvd.cn/Article/details/gt2tecxyhoo.html

[S40] C++：查找元素
来源：http://dali.pengpengdd.cyou/Article/details/gt2kxsouqhf.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhiwuduotai.top/Article/details/gt2uspkgndn.html

[S41] C++：类与构造函数
来源：http://dali.hongshengwenyu.top/Article/details/gt2ziqbvhgx.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.pycfn.com/Article/details/gt2ybzxmygt.html

[S42] C++：继承与虚函数
来源：http://dali.xziqi.cn/Article/details/gt2fuiwbpcv.html

class B : public Base { public: void f() override {} };
来源：http://dali.hnxiangtu.top/Article/details/gt2qkrxijqb.html

[S43] C++：智能指针
来源：http://dali.yangfankeji.com/Article/details/gt2pvyumfka.html

auto p = std::make_unique<int>(5);
来源：http://dali.jlsjyb.cn/Article/details/gt2djsokosq.html

[S44] C++：引用传参
来源：http://dali.cucudq.cn/Article/details/gt2hmqfizts.html

void inc(int &x) { ++x; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2jvcuujwz.html

[S45] C++：lambda
来源：http://dali.tianlin.xyz/Article/details/gt2unnldozs.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.cheryme.top/Article/details/gt2qborxbld.html

[S46] C++：函数模板
来源：http://dali.yj20258888.top/Article/details/gt2aonhkwym.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.sweek.top/Article/details/gt2laoryukr.html

[S47] C++：结构化绑定遍历
来源：http://dali.c1oappe.top/Article/details/gt2olekpijz.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.nanxuanxn.top/Article/details/gt2zhchlhmv.html

[S48] C++：逐行读文件
来源：http://dali.iojbl.cn/Article/details/gt2dckfalnl.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.316326.xyz/Article/details/gt2atxrndrj.html

while (std::getline(in, line)) { }
来源：http://dali.ybcxt.top/Article/details/gt2ubpugpfw.html

[S49] C++：写文件
来源：http://dali.bjfxy.top/Article/details/gt2tvrgumxq.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.jinqigfzy.top/Article/details/gt2sqaisyfn.html

[S50] C++：格式化数字
来源：http://dali.dashuyun.cn/Article/details/gt2vthnbots.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.iojbl.cn/Article/details/gt2ttquwebk.html

[S51] C++：显式类型转换
来源：http://dali.pengpengdd.cyou/Article/details/gt2giojwgdy.html

static_cast<double>(a) / b
来源：http://dali.yanxiufei.cn/Article/details/gt2mfuedgbt.html

[S52] C++：const 与 noexcept
来源：http://dali.cashguo.top/Article/details/gt2syiowzev.html

int size() const noexcept { return n_; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2geziatdx.html

[S53] C++：移动语义
来源：http://dali.fzhhl.top/Article/details/gt2qgbmzpih.html

std::vector<int> w = std::move(v);
来源：http://dali.tanke756.top/Article/details/gt2nyzrhrhq.html

[S54] C++：异常处理
来源：http://dali.xylfe.cn/Article/details/gt2acnuuwzz.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.sufxvd.cn/Article/details/gt2uktmhttz.html

[S55] C++：结构化绑定
来源：http://dali.andypj.xyz/Article/details/gt2ducdypko.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.sxryk.cn/Article/details/gt2qiomudfe.html

[S56] C++：optional
来源：http://dali.wangshuangyany.cn/Article/details/gt2dpfdayva.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.jqgufenzy.top/Article/details/gt2leqbzjxu.html

[S57] C++：编译期常量
来源：http://dali.yangfankeji.com/Article/details/gt2knzbbkyu.html

constexpr int N = 10;
来源：http://dali.jianghu66.top/Article/details/gt2snjiffri.html

[S58] C++：命名空间
来源：http://dali.gaohongyu789.top/Article/details/gt2ypvdfrsf.html

namespace ns { int f() { return 1; } }
来源：http://dali.chenlongwang.top/Article/details/gt2ctxrlqem.html

[S59] C++：静态断言
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fupspqze.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lzxhznzn.html

[S60] C++：遍历并删除元素
来源：http://dali.guannengcc.top/Article/details/gt2yvdjopdk.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.feifeiyinyue.top/Article/details/gt2sjesztee.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gt2vwkokbit.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.cdnleiting.top/Article/details/gt2lqamjqrv.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gt2vvbwgbqk.html

[T01] Kotlin：Hello World
来源：http://dali.zhoulong.xyz/Article/details/gt2mbkhbeur.html

println("Hello")
来源：http://dali.zdqjudy.top/Article/details/gt2osvuxozx.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wdyxnxbg.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.yongpay.top/Article/details/gt2qbwotvdz.html

[T03] Kotlin：字符串模板
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rhmnrrut.html

"值: $b"
来源：http://dali.gaohongyu789.top/Article/details/gt2fouuoxmo.html

[T04] Kotlin：空安全
来源：http://dali.chenjidiqi.icu/Article/details/gt2xhimlhti.html

val n: String? = null;  n?.length
来源：http://dali.aibaodan.cn/Article/details/gt2xkeworlu.html

[T05] Kotlin：when 表达式
来源：http://dali.redwolf501.top/Article/details/gt2qptlfuoj.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mzasesgo.html

[T06] Kotlin：集合映射
来源：http://dali.zhiwuduotai.top/Article/details/gt2swqxkmry.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.hnqzz.top/Article/details/gt2ujbgbwdc.html

[T07] Kotlin：集合过滤
来源：http://dali.xuanzx.com/Article/details/gt2fkybetda.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.smart0.xyz/Article/details/gt2qltfskog.html

[T08] Kotlin：数据类
来源：http://dali.kuanghao11.cn/Article/details/gt2yzilvmxj.html

data class User(val name: String, val age: Int)
来源：http://dali.iojbl.cn/Article/details/gt2kbhzipbl.html

[T09] Kotlin：扩展函数
来源：http://dali.sufxvd.cn/Article/details/gt2eusqxijt.html

fun String.exclaim() = this + "!"
来源：http://dali.xuetiantiany.cn/Article/details/gt2qkbqasnv.html

[T10] Kotlin：默认参数
来源：http://dali.gotoacloud.top/Article/details/gt2opxiepxd.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.hammf.cn/Article/details/gt2xmjqahbc.html

[T11] Kotlin：协程
来源：http://dali.yj20258888.top/Article/details/gt2fkyxdagk.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.redwolf501.top/Article/details/gt2hvetsgfa.html

[T12] Kotlin：解构声明
来源：http://dali.iojbl.cn/Article/details/gt2uuqerndv.html

val (a, b) = Pair(1, 2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pneovcrs.html

[T13] Kotlin：只读 Map
来源：http://dali.ppjwa.cn/Article/details/gt2heijnfsk.html

val m = mapOf("a" to 1)
来源：http://dali.iojbl.cn/Article/details/gt2zororpxy.html

[T14] Kotlin：循环
来源：http://dali.ydzc1.top/Article/details/gt2bsgogyht.html

for (i in 1..10) println(i)
来源：http://dali.yangfankeji.com/Article/details/gt2fdxbgmzo.html

[T15] Kotlin：接口
来源：http://dali.birdmap.top/Article/details/gt2vlpcmbpf.html

interface Shape { fun area(): Double }
来源：http://dali.hongshengwenyu.top/Article/details/gt2cqhlqxwa.html

[T16] Swift：Hello World
来源：http://dali.ybcxt.top/Article/details/gt2vsxeqooq.html

print("Hello")
来源：http://dali.ppjwa.cn/Article/details/gt2ndbevdyi.html

[T17] Swift：变量与常量
来源：http://dali.birdmap.top/Article/details/gt2smcugwod.html

var a = 1;  let b = 2
来源：http://dali.yueranfly.top/Article/details/gt2kwnulfmz.html

[T18] Swift：字符串插值
来源：http://dali.jqgufenzy.top/Article/details/gt2lqgfxmag.html

"值: \(b)"
来源：http://dali.aibaodan.cn/Article/details/gt2qfrmtptn.html

[T19] Swift：可选绑定
来源：http://dali.kuanghao11.cn/Article/details/gt2fchblhpg.html

if let n = opt { print(n) }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2huzdiotk.html

[T20] Swift：数组操作
来源：http://dali.ppjwa.cn/Article/details/gt2llivwshi.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.hnqzz.top/Article/details/gt2bsqfjvfz.html

[T21] Swift：遍历
来源：http://dali.sweek.top/Article/details/gt2nlryncbs.html

for x in a { print(x) }
来源：http://dali.guowangkeji.top/Article/details/gt2nyxlzypl.html

[T22] Swift：字典
来源：http://dali.zhixingplan.top/Article/details/gt2sixmdlkn.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zycfv.cn/Article/details/gt2lzxwqdzm.html

[T23] Swift：函数
来源：http://dali.316326.xyz/Article/details/gt2hqvejfsc.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.meibo888.top/Article/details/gt2hlpppppj.html

[T24] Swift：闭包
来源：http://dali.zycfv.cn/Article/details/gt2hxhmhusr.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.yuxming.cn/Article/details/gt2dgbddsdk.html

[T25] Swift：结构体
来源：http://dali.chenzaomai.com/Article/details/gt2vxpfsdyl.html

struct P { var x: Int }
来源：http://dali.yangfankeji.com/Article/details/gt2wjrmzjnr.html

[T26] Swift：类与重写
来源：http://dali.cucudq.cn/Article/details/gt2plqllxtb.html

class A: Base { override func f() {} }
来源：http://dali.wangdashe.top/Article/details/gt2zrezvntz.html

[T27] Swift：错误处理
来源：http://dali.xuetiantiany.cn/Article/details/gt2tumivyql.html

do { try f() } catch { print(error) }
来源：http://dali.cqqwz.cn/Article/details/gt2sgyqdunn.html

[T28] Swift：枚举
来源：http://dali.aibaodan.cn/Article/details/gt2lmdlairc.html

enum Color { case red, green }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nlyaxnqb.html

[T29] Swift：guard 提前返回
来源：http://dali.hfpthk.cn/Article/details/gt2hjselpbj.html

guard let x = opt else { return }
来源：http://dali.guannengcc.top/Article/details/gt2fvdkjnyx.html

[T30] Swift：协议
来源：http://dali.dashuyun.cn/Article/details/gt2grcflnhp.html

protocol Shape { func area() -> Double }
来源：http://dali.birdmap.top/Article/details/gt2abqzbkro.html

[T31] Lua：Hello World
来源：http://dali.andypj.xyz/Article/details/gt2dkpnxwrm.html

print("Hello")
来源：http://dali.ydzc1.top/Article/details/gt2wtnjshtc.html

[T32] Lua：局部变量
来源：http://dali.wangshuangyany.cn/Article/details/gt2hmjndpee.html

local a = 1
来源：http://dali.xylfe.cn/Article/details/gt2ahmgdoef.html

[T33] Lua：表（数组）
来源：http://dali.316326.xyz/Article/details/gt2jljzthyp.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.jyoumei.cn/Article/details/gt2fhtfneqx.html

[T34] Lua：遍历表
来源：http://dali.guowangkeji.top/Article/details/gt2fidlbnip.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.cdnleiting.top/Article/details/gt2kjqhmzbs.html

[T35] Lua：字典表
来源：http://dali.zycfv.cn/Article/details/gt2dwcatxkv.html

local d = { a = 1 };  d.b = 2
来源：http://dali.0kj1m.cn/Article/details/gt2iajurght.html

[T36] Lua：函数
来源：http://dali.feifeiyinyue.top/Article/details/gt2rcviwmml.html

function add(a, b) return a + b end
来源：http://dali.yuanzhike.top/Article/details/gt2btmhotgn.html

[T37] Lua：字符串拼接
来源：http://dali.chenzaomai.com/Article/details/gt2mayzwycb.html

"a" .. "b"
来源：http://dali.xuanzx.com/Article/details/gt2ajludygv.html

[T38] Lua：条件
来源：http://dali.chenlongwang.top/Article/details/gt2dqeeuzpk.html

if x > 0 then print("正") end
来源：http://dali.jiagoushi.top/Article/details/gt2qviyxrjk.html

[T39] Lua：模式匹配
来源：http://dali.jyoumei.cn/Article/details/gt2tveebocz.html

string.find(s, "%d+")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xmjflwjp.html

[T40] Lua：元表
来源：http://dali.gotoacloud.top/Article/details/gt2crabhpvo.html

setmetatable({}, { __index = base })
来源：http://dali.dianchejie.cn/Article/details/gt2peiicrlh.html

[T41] Perl：Hello World
来源：http://dali.316326.xyz/Article/details/gt2ythnpckt.html

print "Hello\n";
来源：http://dali.vqdsnc.cn/Article/details/gt2twqlifpn.html

[T42] Perl：变量类型
来源：http://dali.gzhubu.top/Article/details/gt2gplubmim.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.aibaodan.cn/Article/details/gt2dvmvalbd.html

[T43] Perl：字符串插值
来源：http://dali.chenlongwang.top/Article/details/gt2onatweme.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2nemacgbk.html

[T44] Perl：条件
来源：http://dali.yj20258.top/Article/details/gt2hsvxskii.html

if ($a > 0) { print "正"; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2kfdqylac.html

[T45] Perl：数组遍历
来源：http://dali.dashuyun.cn/Article/details/gt2wesovqgu.html

for my $x (@arr) { print $x; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qpytrbjp.html

[T46] Perl：哈希操作
来源：http://dali.yanxiufei.cn/Article/details/gt2dhyxfwzh.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.cqqwz.cn/Article/details/gt2rafgbrep.html

[T47] Perl：正则捕获
来源：http://dali.jyoumei.cn/Article/details/gt2huoleeiu.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zycfv.cn/Article/details/gt2dkrezrpp.html

[T48] Perl：正则替换
来源：http://dali.yj202588.top/Article/details/gt2wtbzpygb.html

$s =~ s/old/new/g;
来源：http://dali.hywenlv.cn/Article/details/gt2jlfnysjp.html

[T49] Perl：函数
来源：http://dali.svipenyu.cn/Article/details/gt2wpjdcyme.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.gzhubu.top/Article/details/gt2klrkaosq.html

[T50] Perl：逐行读文件
来源：http://dali.feifeiyinyue.top/Article/details/gt2iebychic.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.hammf.cn/Article/details/gt2enxizlvf.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.quarkkingdee.top/Article/details/gt2glbfxbbr.html

[T51] Scala：Hello World
来源：http://dali.yongpay.top/Article/details/gt2hqoccjda.html

println("Hello")
来源：http://dali.tianlin.xyz/Article/details/gt2nbsajrsu.html

[T52] Scala：变量
来源：http://dali.feifeiyinyue.top/Article/details/gt2mctbwvtt.html

val a = 1;  var b = 2
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bbqslwek.html

[T53] Scala：字符串插值
来源：http://dali.fengsongda.top/Article/details/gt2vgthqfxt.html

s"值: $b"
来源：http://dali.jqgufenzy.top/Article/details/gt2vxnlsekn.html

[T54] Scala：集合映射
来源：http://dali.9152youxi.cn/Article/details/gt2moejxbvh.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.andypj.xyz/Article/details/gt2qogkjjsl.html

[T55] Scala：集合过滤
来源：http://dali.zhengqikj.top/Article/details/gt2ledtoucq.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.jyoumei.cn/Article/details/gt2lstwvijj.html

[T56] Scala：样例类
来源：http://dali.chenzaomai.com/Article/details/gt2jhsixzle.html

case class User(name: String, age: Int)
来源：http://dali.jyoumei.cn/Article/details/gt2uxwzjmvu.html

[T57] Scala：模式匹配
来源：http://dali.xziqi.cn/Article/details/gt2zwdwaial.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.cheryme.top/Article/details/gt2utoivfgu.html

[T58] Scala：函数定义
来源：http://dali.ybcxt.top/Article/details/gt2mfjlxawy.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.birdmap.top/Article/details/gt2beljigmo.html

[T59] Scala：循环
来源：http://dali.jinqigufen.top/Article/details/gt2zncqrmgj.html

for (i <- 1 to 10) println(i)
来源：http://dali.gzhubu.top/Article/details/gt2cxxhudnp.html

[T60] Scala：折叠
来源：http://dali.svipenyu.cn/Article/details/gt2mmqdhgwt.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.hfpthk.cn/Article/details/gt2fwjazeud.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2eblwwfvb.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.jqgfzy.top/Article/details/gt2rjhrlzgi.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gharilem.html

[U01] Py：创建虚拟环境
来源：http://dali.hywenlv.cn/Article/details/gt2ltgoztzp.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.tanke756.top/Article/details/gt2fxmeedze.html

[U02] Py：导出 / 安装依赖
来源：http://dali.ydzc1.top/Article/details/gt2xuqjzwag.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.xziqi.cn/Article/details/gt2hfablwag.html

[U03] Py：加载 .env 配置
来源：http://dali.jqgfzy.top/Article/details/gt2lakypipl.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.mhx1999.top/Article/details/gt2wsbcghvi.html

[U04] Py：变量调试打印
来源：http://dali.ivvv.top/Article/details/gt2mjggunwn.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vpnzqizh.html


<!-- 参考信息 -->