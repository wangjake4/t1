代发 wailian999

openssl rand -hex 16
来源：http://dali.kuanghao11.cn/Article/details/gt2ggnxoyky.html

[R68] 计算文件校验值
来源：http://dali.zdqjudy.top/Article/details/gt2newdcofg.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.smart0.xyz/Article/details/gt2rhswvmwb.html

[R69] 生成随机密码
来源：http://dali.cheryme.top/Article/details/gt2bvcrfrsi.html

head -c 16 /dev/urandom | base64
来源：http://dali.daria6918.cn/Article/details/gt2uytvpjde.html

[R70] 时间戳与互转
来源：http://dali.gotoacloud.top/Article/details/gt2fydletxh.html

date +%s;  date -d @1700000000
来源：http://dali.vqdsnc.cn/Article/details/gt2dbbkfian.html

[R71] 日期格式化
来源：http://dali.snrcjt.cn/Article/details/gt2wowbhwnv.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhiwuduotai.top/Article/details/gt2uiiiuzen.html

[R72] 等待端口就绪
来源：http://dali.zhengqikj.top/Article/details/gt2dbmkjoah.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.hongshengwenyu.top/Article/details/gt2xeiqkncu.html

[R73] 分割大日志
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xowksluz.html

split -l 1000 big.log part_
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bynexafc.html

[R74] 批量重命名
来源：http://dali.c1oappe.top/Article/details/gt2rvgurxur.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.yuanzhike.top/Article/details/gt2ifmsilfd.html

[R75] 导出环境变量
来源：http://dali.yanxiufei.cn/Article/details/gt2czkpkack.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.hongshengwenyu.top/Article/details/gt2ryhdjblb.html

[R76] 使用临时文件
来源：http://dali.yj20258.top/Article/details/gt2pyernlqm.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.nwbrower.top/Article/details/gt2vrlpbxbw.html

[R77] 读取用户输入
来源：http://dali.vqdsnc.cn/Article/details/gt2nfogzagb.html

read -rp "请输入: " ans
来源：http://dali.zhongyouzk.top/Article/details/gt2wmxjmmhs.html

[R78] 交互式菜单
来源：http://dali.jinqigufen.top/Article/details/gt2gnydyfza.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.wangdashe.top/Article/details/gt2svzgdfmz.html

[R79] 解析命令行选项
来源：http://dali.sufxvd.cn/Article/details/gt2joxisgfx.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.jqgfzy.top/Article/details/gt2spuhespl.html

[R80] 查看脚本执行耗时
来源：http://dali.feifeiyinyue.top/Article/details/gt2nptjxnwt.html

time ./run.sh
来源：http://dali.zhoulong.xyz/Article/details/gt2temimhsu.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2krrsebuh.html

S. C / C++ 专题
来源：http://dali.haohaochexian.top/Article/details/gt2rhdbpysf.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2svmbmmuu.html

[S01] C：Hello World
来源：http://dali.wangdashe.top/Article/details/gt2gwzzifie.html

#include <stdio.h>
来源：http://dali.316326.xyz/Article/details/gt2iyyllzqc.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.meibo888.top/Article/details/gt2hgiqygso.html

[S02] C：变量与格式化输出
来源：http://dali.cucudq.cn/Article/details/gt2amalhoot.html

int a = 10; printf("%d\n", a);
来源：http://dali.hnxiangtu.top/Article/details/gt2eihkdrcx.html

[S03] C：读入整数
来源：http://dali.cheryme.top/Article/details/gt2zkcardoc.html

int x; scanf("%d", &x);
来源：http://dali.dashuyun.cn/Article/details/gt2piapsnll.html

[S04] C：字符串复制
来源：http://dali.sweek.top/Article/details/gt2hucmcekg.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.tianlin.xyz/Article/details/gt2jlohwmgm.html

[S05] C：字符串长度
来源：http://dali.gogol.net.cn/Article/details/gt2zdrrlgbs.html

strlen(s)
来源：http://dali.jianghu66.top/Article/details/gt2hdbaczfy.html

[S06] C：字符串比较
来源：http://dali.cashguo.top/Article/details/gt2tdspnwav.html

strcmp(a, b) == 0
来源：http://dali.xuanzx.com/Article/details/gt2vszogilj.html

[S07] C：数组遍历求和
来源：http://dali.gzhubu.top/Article/details/gt2nqjzight.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.jyoumei.cn/Article/details/gt2syydhrbu.html

[S08] C：动态内存分配与释放
来源：http://dali.cucudq.cn/Article/details/gt2timmfqsd.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.haohaochexian.top/Article/details/gt2kriupfde.html

[S09] C：结构体定义与初始化
来源：http://dali.daxiang520.top/Article/details/gt2iezmqjzs.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.xziqi.cn/Article/details/gt2zvodvffr.html

[S10] C：指针与解引用
来源：http://dali.xylfe.cn/Article/details/gt2gypeptmg.html

int *p = &a;  *p = 5;
来源：http://dali.sysykeji.top/Article/details/gt2drvdtkxb.html

[S11] C：逐行读文件
来源：http://dali.hnxiangtu.top/Article/details/gt2cngnpvof.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.daria6918.cn/Article/details/gt2gtpvyhtd.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.nanxinkj.top/Article/details/gt2bmyhoepq.html

fclose(f);
来源：http://dali.fzhhl.top/Article/details/gt2bfzjxteu.html

[S12] C：写文件
来源：http://dali.hywenlv.cn/Article/details/gt2fbhnmegp.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2fekdtjfr.html

[S13] C：宏定义
来源：http://dali.daxiang520.top/Article/details/gt2sgzuocwu.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.sxryk.cn/Article/details/gt2fwkdjfjg.html

[S14] C：枚举
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ukwnengt.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.mhx1999.top/Article/details/gt2tzubxvbn.html

[S15] C：类型转换
来源：http://dali.iojbl.cn/Article/details/gt2hjafrppd.html

(double) a / b
来源：http://dali.chenlongwang.top/Article/details/gt2mpqxcdjq.html

[S16] C：位操作置位
来源：http://dali.fzhhl.top/Article/details/gt2meoizfhm.html

x |= (1 << 3);
来源：http://dali.redwolf501.top/Article/details/gt2lafcjzzp.html

[S17] C：安全拼接字符串
来源：http://dali.chenzaomai.com/Article/details/gt2rgusbmke.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.aibaodan.cn/Article/details/gt2nwahfxmh.html

[S18] C：命令行参数
来源：http://dali.hywenlv.cn/Article/details/gt2ucsnqrvw.html

int main(int argc, char **argv)
来源：http://dali.chenjidiqi.icu/Article/details/gt2fbafdbbw.html

[S19] C：快速排序
来源：http://dali.0kj1m.cn/Article/details/gt2brdnopsq.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.yj20258888.top/Article/details/gt2nqrdapjc.html

[S20] C：二分查找
来源：http://dali.jlsjyb.cn/Article/details/gt2ydvgshhy.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xvhmvszv.html

[S21] C：字符类别判断
来源：http://dali.gogol.net.cn/Article/details/gt2bikbcalf.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.quarkkingdee.top/Article/details/gt2ctcnjnrv.html

[S22] C：字符串转数字
来源：http://dali.yangfankeji.com/Article/details/gt2iemjyxxf.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.xziqi.cn/Article/details/gt2unpgqbcu.html

[S23] C：随机数
来源：http://dali.pycfn.com/Article/details/gt2wksnevby.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.jinqigfzy.top/Article/details/gt2fcfuvqip.html

[S24] C：获取本地时间
来源：http://dali.wangshuangyany.cn/Article/details/gt2jkxlxvkg.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.vqdsnc.cn/Article/details/gt2gsqfmpga.html

[S25] C：内存拷贝
来源：http://dali.yuxming.cn/Article/details/gt2hpjijlej.html

memcpy(dst, src, n);
来源：http://dali.jinqigufen.top/Article/details/gt2mlufeqtj.html

[S26] C：内存清零
来源：http://dali.nanxinkj.top/Article/details/gt2ayufsvnt.html

memset(a, 0, sizeof a);
来源：http://dali.vqdsnc.cn/Article/details/gt2nkeksiky.html

[S27] C：定义常量
来源：http://dali.xylfe.cn/Article/details/gt2ozvmsbvr.html

const double PI = 3.14159;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hsrxouap.html

[S28] C：静态变量
来源：http://dali.nwbrower.top/Article/details/gt2lznkluyy.html

static int counter = 0;
来源：http://dali.ydzc1.top/Article/details/gt2dglwxwor.html

[S29] C：变参函数
来源：http://dali.quarkkingdee.top/Article/details/gt2bqrqjvot.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.jqgfzy.top/Article/details/gt2tljbivlx.html

[S30] C：头文件保护
来源：http://dali.jiagoushi.top/Article/details/gt2hgtuoubp.html

#ifndef X_H
来源：http://dali.tianlin.xyz/Article/details/gt2cgykcngt.html

#define X_H
来源：http://dali.hysaishi.cn/Article/details/gt2okuaqhsu.html

#endif
来源：http://dali.hongshengwenyu.top/Article/details/gt2vtbrlraw.html

[S31] C++：Hello World
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2skixxmsu.html

#include <iostream>
来源：http://dali.nwbrower.top/Article/details/gt2jjhntnwy.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.nanxinkj.top/Article/details/gt2ygnkirpb.html

[S32] C++：字符串
来源：http://dali.hnqzz.top/Article/details/gt2gvaehdzu.html

std::string s = "hi";  s += "!";
来源：http://dali.gzhubu.top/Article/details/gt2mzldgivq.html

[S33] C++：vector 增删
来源：http://dali.shangyingyoupin.top/Article/details/gt2tnkpnrte.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.xuetiantiany.cn/Article/details/gt2gsseujwd.html

[S34] C++：遍历 vector
来源：http://dali.sweek.top/Article/details/gt2vageyrrs.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.jqgufenzy.top/Article/details/gt2ilqshnhb.html

[S35] C++：map
来源：http://dali.redwolf501.top/Article/details/gt2xsortbad.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.aibaodan.cn/Article/details/gt2srxcfgqc.html

[S36] C++：unordered_map
来源：http://dali.andypj.xyz/Article/details/gt2boghqwfz.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.fengsongda.top/Article/details/gt2dqpqjmtk.html

[S37] C++：set
来源：http://dali.9152youxi.cn/Article/details/gt2hvwrmjtc.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pcykfxon.html

[S38] C++：排序
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vcwxqfyk.html

std::sort(v.begin(), v.end());
来源：http://dali.birdmap.top/Article/details/gt2calssieo.html

[S39] C++：自定义比较器排序
来源：http://dali.zycfv.cn/Article/details/gt2hcgklzbh.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.tian-w.cn/Article/details/gt2udtftkze.html

[S40] C++：查找元素
来源：http://dali.jianghu66.top/Article/details/gt2ypmrvoas.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.smart0.xyz/Article/details/gt2vdxsqnwx.html

[S41] C++：类与构造函数
来源：http://dali.316326.xyz/Article/details/gt2bfgqaasy.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.xylfe.cn/Article/details/gt2nytniqln.html

[S42] C++：继承与虚函数
来源：http://dali.havefunace.top/Article/details/gt2mmrblwto.html

class B : public Base { public: void f() override {} };
来源：http://dali.smart0.xyz/Article/details/gt2khulzzrk.html

[S43] C++：智能指针
来源：http://dali.birdmap.top/Article/details/gt2ygochfpn.html

auto p = std::make_unique<int>(5);
来源：http://dali.chenlongwang.top/Article/details/gt2ywwfmgrx.html

[S44] C++：引用传参
来源：http://dali.zhoulong.xyz/Article/details/gt2dxgcnnog.html

void inc(int &x) { ++x; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wfqussfs.html

[S45] C++：lambda
来源：http://dali.yongpay.top/Article/details/gt2ufxzboei.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.shuidangran.top/Article/details/gt2ynwfhktj.html

[S46] C++：函数模板
来源：http://dali.ehwqpu.com/Article/details/gt2nrdaxmgm.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.ivvv.top/Article/details/gt2lmnbckgu.html

[S47] C++：结构化绑定遍历
来源：http://dali.hfpthk.cn/Article/details/gt2qycdxelp.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.fzhhl.top/Article/details/gt2gszqsmxj.html

[S48] C++：逐行读文件
来源：http://dali.aibaodan.cn/Article/details/gt2aokdptby.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.sxryk.cn/Article/details/gt2twabnwbx.html

while (std::getline(in, line)) { }
来源：http://dali.tian-w.cn/Article/details/gt2brvofzmc.html

[S49] C++：写文件
来源：http://dali.yonumen.top/Article/details/gt2clxqfuat.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.cucudq.cn/Article/details/gt2qjotcyub.html

[S50] C++：格式化数字
来源：http://dali.zhoulong.xyz/Article/details/gt2hqwcvlgs.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.xylfe.cn/Article/details/gt2ptdhrfye.html

[S51] C++：显式类型转换
来源：http://dali.shzxlz.cn/Article/details/gt2cclnrzvc.html

static_cast<double>(a) / b
来源：http://dali.c1oappe.top/Article/details/gt2nxezqsoc.html

[S52] C++：const 与 noexcept
来源：http://dali.gaohongyu789.top/Article/details/gt2duikshyt.html

int size() const noexcept { return n_; }
来源：http://dali.chenlongwang.top/Article/details/gt2hpnznhjc.html

[S53] C++：移动语义
来源：http://dali.aizwys.cn/Article/details/gt2shtdzgfq.html

std::vector<int> w = std::move(v);
来源：http://dali.zhengqikj.top/Article/details/gt2qsvsnnhc.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2sxqqsxkb.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.nwbrower.top/Article/details/gt2ichoqfzt.html

[S55] C++：结构化绑定
来源：http://dali.pycfn.com/Article/details/gt2mfoktycu.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.0kj1m.cn/Article/details/gt2wbjdbcdf.html

[S56] C++：optional
来源：http://dali.nanxuanxn.top/Article/details/gt2ueducqzm.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.guannengcc.top/Article/details/gt2bttxjuxg.html

[S57] C++：编译期常量
来源：http://dali.bjfxy.top/Article/details/gt2gzwxbsso.html

constexpr int N = 10;
来源：http://dali.shuidangran.top/Article/details/gt2cffzngvd.html

[S58] C++：命名空间
来源：http://dali.cdnleiting.top/Article/details/gt2yprupahc.html

namespace ns { int f() { return 1; } }
来源：http://dali.cheryme.top/Article/details/gt2rsfoxxwr.html

[S59] C++：静态断言
来源：http://dali.fengsongda.top/Article/details/gt2yuhqsmwq.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.shangyingyoupin.top/Article/details/gt2aajxbmjo.html

[S60] C++：遍历并删除元素
来源：http://dali.nanxinkj.top/Article/details/gt2frqcbgmi.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.hammf.cn/Article/details/gt2yfvhbglf.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2ylrvioxw.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.nanxinkj.top/Article/details/gt2njfecnlq.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2abbjkmqw.html

[T01] Kotlin：Hello World
来源：http://dali.pengpengdd.cyou/Article/details/gt2zsdrhlnd.html

println("Hello")
来源：http://dali.nwbrower.top/Article/details/gt2gwchjgkh.html

[T02] Kotlin：变量
来源：http://dali.ppjwa.cn/Article/details/gt2cfpqfibh.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.yongpay.top/Article/details/gt2svpaansa.html

[T03] Kotlin：字符串模板
来源：http://dali.mhx1999.top/Article/details/gt2zfxdjshx.html

"值: $b"
来源：http://dali.zhoulong.xyz/Article/details/gt2fyzyspay.html

[T04] Kotlin：空安全
来源：http://dali.gotoacloud.top/Article/details/gt2kqostbvo.html

val n: String? = null;  n?.length
来源：http://dali.zhengqikj.top/Article/details/gt2rokdwpwa.html

[T05] Kotlin：when 表达式
来源：http://dali.gogol.net.cn/Article/details/gt2oacfiszn.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.dashuyun.cn/Article/details/gt2onkubqem.html

[T06] Kotlin：集合映射
来源：http://dali.ehwqpu.com/Article/details/gt2skzysurl.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.chenzaomai.com/Article/details/gt2lusyfbai.html

[T07] Kotlin：集合过滤
来源：http://dali.chenzaomai.com/Article/details/gt2hennfasv.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.nanxuanxn.top/Article/details/gt2ntkbtjyz.html

[T08] Kotlin：数据类
来源：http://dali.yj202588.top/Article/details/gt2epuwyugj.html

data class User(val name: String, val age: Int)
来源：http://dali.mhx1999.top/Article/details/gt2zzzsbzsb.html

[T09] Kotlin：扩展函数
来源：http://dali.ydzc1.top/Article/details/gt2vzfahxtq.html

fun String.exclaim() = this + "!"
来源：http://dali.gogol.net.cn/Article/details/gt2aftggotl.html

[T10] Kotlin：默认参数
来源：http://dali.quarkkingdee.top/Article/details/gt2abztpqcz.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.cucudq.cn/Article/details/gt2uvpfjhlt.html

[T11] Kotlin：协程
来源：http://dali.0kj1m.cn/Article/details/gt2phqhvixn.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2jxwliqri.html

[T12] Kotlin：解构声明
来源：http://dali.birdmap.top/Article/details/gt2yzuptiuk.html

val (a, b) = Pair(1, 2)
来源：http://dali.hongshengwenyu.top/Article/details/gt2xhkwtcgy.html

[T13] Kotlin：只读 Map
来源：http://dali.hnxiangtu.top/Article/details/gt2xdlpxuvy.html

val m = mapOf("a" to 1)
来源：http://dali.svipenyu.cn/Article/details/gt2lixxcprq.html

[T14] Kotlin：循环
来源：http://dali.cdnleiting.top/Article/details/gt2cferjilm.html

for (i in 1..10) println(i)
来源：http://dali.ehwqpu.com/Article/details/gt2hijuremq.html

[T15] Kotlin：接口
来源：http://dali.sweek.top/Article/details/gt2nbrpkaql.html

interface Shape { fun area(): Double }
来源：http://dali.daxiang520.top/Article/details/gt2cllawhuu.html

[T16] Swift：Hello World
来源：http://dali.shuidangran.top/Article/details/gt2xwiiivuv.html

print("Hello")
来源：http://dali.sysykeji.top/Article/details/gt2jqekpcmc.html

[T17] Swift：变量与常量
来源：http://dali.hongshengwenyu.top/Article/details/gt2ouwqwwyb.html

var a = 1;  let b = 2
来源：http://dali.xylfe.cn/Article/details/gt2obuoxyrc.html

[T18] Swift：字符串插值
来源：http://dali.tianlin.xyz/Article/details/gt2dnsutndb.html

"值: \(b)"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2idharqmf.html

[T19] Swift：可选绑定
来源：http://dali.0kj1m.cn/Article/details/gt2qprdnrfs.html

if let n = opt { print(n) }
来源：http://dali.tian-w.cn/Article/details/gt2ntykesig.html

[T20] Swift：数组操作
来源：http://dali.dashuyun.cn/Article/details/gt2pzaloeol.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.jlsjyb.cn/Article/details/gt2gynpzxlf.html

[T21] Swift：遍历
来源：http://dali.sxryk.cn/Article/details/gt2ydqstlck.html

for x in a { print(x) }
来源：http://dali.cucudq.cn/Article/details/gt2knsztisc.html

[T22] Swift：字典
来源：http://dali.zycfv.cn/Article/details/gt2rszreftd.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.hfpthk.cn/Article/details/gt2xsbspctb.html

[T23] Swift：函数
来源：http://dali.iojbl.cn/Article/details/gt2gxbyyhge.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.yj20258888.top/Article/details/gt2zfsdzsuh.html

[T24] Swift：闭包
来源：http://dali.sysykeji.top/Article/details/gt2ldwyaisi.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.haohaochexian.top/Article/details/gt2fjmysrwx.html

[T25] Swift：结构体
来源：http://dali.vqdsnc.cn/Article/details/gt2fyfectwx.html

struct P { var x: Int }
来源：http://dali.chenjidiqi.icu/Article/details/gt2ehufyrdr.html

[T26] Swift：类与重写
来源：http://dali.redwolf501.top/Article/details/gt2khjytfzb.html

class A: Base { override func f() {} }
来源：http://dali.hnqzz.top/Article/details/gt2vplqlrdi.html

[T27] Swift：错误处理
来源：http://dali.jyoumei.cn/Article/details/gt2ltqaouoj.html

do { try f() } catch { print(error) }
来源：http://dali.vqdsnc.cn/Article/details/gt2sxlqkcwh.html

[T28] Swift：枚举
来源：http://dali.shzxlz.cn/Article/details/gt2myveygql.html

enum Color { case red, green }
来源：http://dali.dashuyun.cn/Article/details/gt2ptxvavqp.html

[T29] Swift：guard 提前返回
来源：http://dali.zhoulong.xyz/Article/details/gt2ilcnnqkc.html

guard let x = opt else { return }
来源：http://dali.hongshengwenyu.top/Article/details/gt2tmlswdic.html

[T30] Swift：协议
来源：http://dali.hysaishi.cn/Article/details/gt2lvakscdb.html

protocol Shape { func area() -> Double }
来源：http://dali.meibo888.top/Article/details/gt2wuaaczhr.html

[T31] Lua：Hello World
来源：http://dali.zhoulong.xyz/Article/details/gt2shzinzhr.html

print("Hello")
来源：http://dali.xylfe.cn/Article/details/gt2ixijcgds.html

[T32] Lua：局部变量
来源：http://dali.jqgufenzy.top/Article/details/gt2cahinlac.html

local a = 1
来源：http://dali.xuanzx.com/Article/details/gt2pxsgfdlj.html

[T33] Lua：表（数组）
来源：http://dali.yvedp.cn/Article/details/gt2kypzymif.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.kuanghao11.cn/Article/details/gt2qnptiwtj.html

[T34] Lua：遍历表
来源：http://dali.yueranfly.top/Article/details/gt2effkiiyy.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.pengpengdd.cyou/Article/details/gt2wlknrqdr.html

[T35] Lua：字典表
来源：http://dali.cheryme.top/Article/details/gt2qkxmtuzs.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhengqikj.top/Article/details/gt2lzpgldkw.html

[T36] Lua：函数
来源：http://dali.yonumen.top/Article/details/gt2swsctvau.html

function add(a, b) return a + b end
来源：http://dali.yj20258888.top/Article/details/gt2npmlowhh.html

[T37] Lua：字符串拼接
来源：http://dali.jinqigfzy.top/Article/details/gt2bdmoqxpx.html

"a" .. "b"
来源：http://dali.meibo888.top/Article/details/gt2ajtusuai.html

[T38] Lua：条件
来源：http://dali.sxryk.cn/Article/details/gt2zgzviqwn.html

if x > 0 then print("正") end
来源：http://dali.yj20258.top/Article/details/gt2mpqxxfzx.html

[T39] Lua：模式匹配
来源：http://dali.ehwqpu.com/Article/details/gt2pjnhwkmn.html

string.find(s, "%d+")
来源：http://dali.shangyingyoupin.top/Article/details/gt2ejsnhoea.html

[T40] Lua：元表
来源：http://dali.shangyingyoupin.top/Article/details/gt2noxzjayu.html

setmetatable({}, { __index = base })
来源：http://dali.zycfv.cn/Article/details/gt2knznjqkk.html

[T41] Perl：Hello World
来源：http://dali.jinqigfzy.top/Article/details/gt2zymfbejn.html

print "Hello\n";
来源：http://dali.smart0.xyz/Article/details/gt2rudqeaok.html

[T42] Perl：变量类型
来源：http://dali.xuetiantiany.cn/Article/details/gt2hhvjupjz.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.dashuyun.cn/Article/details/gt2bjngzhgg.html

[T43] Perl：字符串插值
来源：http://dali.redwolf501.top/Article/details/gt2mrdqnpaz.html

"值: $a"
来源：http://dali.sweek.top/Article/details/gt2ykvtsjei.html

[T44] Perl：条件
来源：http://dali.pengpengdd.cyou/Article/details/gt2dnxlskxb.html

if ($a > 0) { print "正"; }
来源：http://dali.haohaochexian.top/Article/details/gt2qgsoqlhi.html

[T45] Perl：数组遍历
来源：http://dali.smart0.xyz/Article/details/gt2sosvruyj.html

for my $x (@arr) { print $x; }
来源：http://dali.zdqjudy.top/Article/details/gt2ksyqkapd.html

[T46] Perl：哈希操作
来源：http://dali.0kj1m.cn/Article/details/gt2vbejqode.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.fzhhl.top/Article/details/gt2lwmrldsr.html

[T47] Perl：正则捕获
来源：http://dali.guowangkeji.top/Article/details/gt2moehodmr.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gtsvktoz.html

[T48] Perl：正则替换
来源：http://dali.zhixingplan.top/Article/details/gt2wzbcjnve.html

$s =~ s/old/new/g;
来源：http://dali.zhongyouzk.top/Article/details/gt2mivrhmxj.html

[T49] Perl：函数
来源：http://dali.hammf.cn/Article/details/gt2elkrgvbr.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.meibo888.top/Article/details/gt2fvtvrlxc.html

[T50] Perl：逐行读文件
来源：http://dali.zhiwuduotai.top/Article/details/gt2mxyhceek.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.yuanzhike.top/Article/details/gt2ufykkovk.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.jiagoushi.top/Article/details/gt2ohexeexl.html

[T51] Scala：Hello World
来源：http://dali.feifeiyinyue.top/Article/details/gt2ihihpyqd.html

println("Hello")
来源：http://dali.zhengqikj.top/Article/details/gt2ecefqmkp.html

[T52] Scala：变量
来源：http://dali.yj20258.top/Article/details/gt2lsuzzxrz.html

val a = 1;  var b = 2
来源：http://dali.c1oappe.top/Article/details/gt2yreqbrgz.html

[T53] Scala：字符串插值
来源：http://dali.shangyingyoupin.top/Article/details/gt2ozbdujgz.html

s"值: $b"
来源：http://dali.shangyingyoupin.top/Article/details/gt2ipwbqyww.html

[T54] Scala：集合映射
来源：http://dali.yueranfly.top/Article/details/gt2mdtlrzat.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.jyoumei.cn/Article/details/gt2ditlbfvf.html

[T55] Scala：集合过滤
来源：http://dali.hysaishi.cn/Article/details/gt2wenefoub.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.jinqigfzy.top/Article/details/gt2subcfhuy.html

[T56] Scala：样例类
来源：http://dali.yonumen.top/Article/details/gt2onfadvmi.html

case class User(name: String, age: Int)
来源：http://dali.hongshengwenyu.top/Article/details/gt2tdxymhev.html

[T57] Scala：模式匹配
来源：http://dali.tian-w.cn/Article/details/gt2uknnlwxs.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.hfpthk.cn/Article/details/gt2otjfbbwz.html

[T58] Scala：函数定义
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uwhyiilx.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.svipenyu.cn/Article/details/gt2kcudfczn.html

[T59] Scala：循环
来源：http://dali.jqgfzy.top/Article/details/gt2pdeklljh.html

for (i <- 1 to 10) println(i)
来源：http://dali.yj20258.top/Article/details/gt2mglbocse.html

[T60] Scala：折叠
来源：http://dali.yanxiufei.cn/Article/details/gt2yapthcvi.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhiwuduotai.top/Article/details/gt2tcbfferk.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2wihesuac.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhengqikj.top/Article/details/gt2vhrwmuei.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2gflwkqir.html

[U01] Py：创建虚拟环境
来源：http://dali.xuetiantiany.cn/Article/details/gt2agfainil.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.havefunace.top/Article/details/gt2hzufxrkr.html

[U02] Py：导出 / 安装依赖
来源：http://dali.shuidangran.top/Article/details/gt2poghoulc.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.chenlongwang.top/Article/details/gt2spifrkfc.html

[U03] Py：加载 .env 配置
来源：http://dali.ydzc1.top/Article/details/gt2xpzldswf.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.pengpengdd.cyou/Article/details/gt2xakthfje.html

[U04] Py：变量调试打印
来源：http://dali.cheryme.top/Article/details/gt2podljtno.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.hongshengwenyu.top/Article/details/gt2gofzgktv.html

[U05] Py：列表去重且保序
来源：http://dali.zhoulong.xyz/Article/details/gt2kirdmfpa.html

list(dict.fromkeys(arr))
来源：http://dali.sweek.top/Article/details/gt2hpncnxuq.html

[U06] Py：合并两个字典
来源：http://dali.ehwqpu.com/Article/details/gt2blsvzzfp.html

{**a, **b}
来源：http://dali.sufxvd.cn/Article/details/gt2indvqkrg.html

[U07] Py：反转字典键值
来源：http://dali.havefunace.top/Article/details/gt2eydtvkgq.html

{v: k for k, v in d.items()}
来源：http://dali.jyoumei.cn/Article/details/gt2tzmntpjp.html

[U08] Py：展平二维列表
来源：http://dali.yj20258888.top/Article/details/gt2wpkjojtf.html

[y for x in nested for y in x]
来源：http://dali.wangshuangyany.cn/Article/details/gt2ztjqbnyp.html


<!-- 参考信息 -->