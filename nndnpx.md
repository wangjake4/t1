代发 wailian999

df -h;  du -sh *
来源：http://dali.9152youxi.cn/Article/details/gt2spqmqjhx.html

[R62] 找最占空间的文件
来源：http://dali.gzhubu.top/Article/details/gt2xsrvbxtn.html

du -ah . | sort -rh | head -10
来源：http://dali.yongpay.top/Article/details/gt2dxhxiqfr.html

[R63] 内存与进程
来源：http://dali.yangfankeji.com/Article/details/gt2zdwnnpta.html

free -h;  ps aux | grep nginx
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xhlxycdu.html

[R64] 结束进程
来源：http://dali.ivvv.top/Article/details/gt2jjnxvksn.html

kill -9 $(pgrep -f app.py)
来源：http://dali.hammf.cn/Article/details/gt2zavurnpv.html

[R65] 查看端口占用
来源：http://dali.nwbrower.top/Article/details/gt2dfissxyp.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.dashuyun.cn/Article/details/gt2emqovabb.html

[R66] 定时任务
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xwihpdeh.html

crontab -e;  crontab -l
来源：http://dali.hammf.cn/Article/details/gt2gsyrbpej.html

[R67] 生成随机十六进制串
来源：http://dali.hysaishi.cn/Article/details/gt2ejarbdxt.html

openssl rand -hex 16
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2txjtvpsd.html

[R68] 计算文件校验值
来源：http://dali.havefunace.top/Article/details/gt2cmktnjnd.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.chenlongwang.top/Article/details/gt2djrvgivn.html

[R69] 生成随机密码
来源：http://dali.ydzc1.top/Article/details/gt2aldmrfdd.html

head -c 16 /dev/urandom | base64
来源：http://dali.ivvv.top/Article/details/gt2oqfpnttd.html

[R70] 时间戳与互转
来源：http://dali.haohaochexian.top/Article/details/gt2tqngryrh.html

date +%s;  date -d @1700000000
来源：http://dali.xziqi.cn/Article/details/gt2qbnkonlp.html

[R71] 日期格式化
来源：http://dali.cqqwz.cn/Article/details/gt2mjsjzofd.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.yuxming.cn/Article/details/gt2unitljcd.html

[R72] 等待端口就绪
来源：http://dali.zhengqikj.top/Article/details/gt2cnsrjccx.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.cashguo.top/Article/details/gt2ejctbkkx.html

[R73] 分割大日志
来源：http://dali.ybcxt.top/Article/details/gt2yzkjreka.html

split -l 1000 big.log part_
来源：http://dali.yj20258888.top/Article/details/gt2hctyhmuo.html

[R74] 批量重命名
来源：http://dali.gogol.net.cn/Article/details/gt2qoskthur.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhoulong.xyz/Article/details/gt2hmphnrws.html

[R75] 导出环境变量
来源：http://dali.hammf.cn/Article/details/gt2qxynljns.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.ehwqpu.com/Article/details/gt2uyradsvr.html

[R76] 使用临时文件
来源：http://dali.yj20258.top/Article/details/gt2bbekdfst.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.shuidangran.top/Article/details/gt2iyfsxxoq.html

[R77] 读取用户输入
来源：http://dali.yj20258.top/Article/details/gt2wsidpdrp.html

read -rp "请输入: " ans
来源：http://dali.ppjwa.cn/Article/details/gt2qmxdqpbw.html

[R78] 交互式菜单
来源：http://dali.xuanzx.com/Article/details/gt2jbvwwena.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.vqdsnc.cn/Article/details/gt2fpyapeuc.html

[R79] 解析命令行选项
来源：http://dali.jiagoushi.top/Article/details/gt2zxcivwvy.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.hfpthk.cn/Article/details/gt2ammehjpu.html

[R80] 查看脚本执行耗时
来源：http://dali.hysaishi.cn/Article/details/gt2uqqmohas.html

time ./run.sh
来源：http://dali.jinqigfzy.top/Article/details/gt2wxbjoppu.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2mvskzsip.html

S. C / C++ 专题
来源：http://dali.316326.xyz/Article/details/gt2diddovye.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gt2dmnkhbpn.html

[S01] C：Hello World
来源：http://dali.feifeiyinyue.top/Article/details/gt2nranvjer.html

#include <stdio.h>
来源：http://dali.aibaodan.cn/Article/details/gt2nwkmwpzl.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2vziokocn.html

[S02] C：变量与格式化输出
来源：http://dali.aibaodan.cn/Article/details/gt2ylkzictt.html

int a = 10; printf("%d\n", a);
来源：http://dali.cashguo.top/Article/details/gt2ekczidvk.html

[S03] C：读入整数
来源：http://dali.daria6918.cn/Article/details/gt2wfibqiam.html

int x; scanf("%d", &x);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hapxaend.html

[S04] C：字符串复制
来源：http://dali.bjfxy.top/Article/details/gt2kgqqyvxt.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.aizwys.cn/Article/details/gt2trfmrcbg.html

[S05] C：字符串长度
来源：http://dali.dianchejie.cn/Article/details/gt2hhsbpyrw.html

strlen(s)
来源：http://dali.birdmap.top/Article/details/gt2ztwyckwm.html

[S06] C：字符串比较
来源：http://dali.gogol.net.cn/Article/details/gt2usswruqs.html

strcmp(a, b) == 0
来源：http://dali.tian-w.cn/Article/details/gt2bcrmvnav.html

[S07] C：数组遍历求和
来源：http://dali.yueranfly.top/Article/details/gt2lhndewcr.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.cheryme.top/Article/details/gt2nstttkik.html

[S08] C：动态内存分配与释放
来源：http://dali.0kj1m.cn/Article/details/gt2zxisfkie.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.yj202588.top/Article/details/gt2dzeydnfn.html

[S09] C：结构体定义与初始化
来源：http://dali.jinqigfzy.top/Article/details/gt2ypvhtfep.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.316326.xyz/Article/details/gt2dxejbipu.html

[S10] C：指针与解引用
来源：http://dali.316326.xyz/Article/details/gt2kwnyoroz.html

int *p = &a;  *p = 5;
来源：http://dali.zhoulong.xyz/Article/details/gt2pcqhaukl.html

[S11] C：逐行读文件
来源：http://dali.c1oappe.top/Article/details/gt2uclvtrxy.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.mhx1999.top/Article/details/gt2qghdrakt.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.yj20258.top/Article/details/gt2awoectgp.html

fclose(f);
来源：http://dali.feifeiyinyue.top/Article/details/gt2hxulhgyq.html

[S12] C：写文件
来源：http://dali.yuanzhike.top/Article/details/gt2jutkilxo.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.shangyingyoupin.top/Article/details/gt2yvaiimox.html

[S13] C：宏定义
来源：http://dali.316326.xyz/Article/details/gt2ztlgylsi.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.sufxvd.cn/Article/details/gt2pkdqkuqd.html

[S14] C：枚举
来源：http://dali.yonumen.top/Article/details/gt2koumjcvs.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.ivvv.top/Article/details/gt2qhvxffbm.html

[S15] C：类型转换
来源：http://dali.jyoumei.cn/Article/details/gt2goletbwu.html

(double) a / b
来源：http://dali.tianlin.xyz/Article/details/gt2wfuykteh.html

[S16] C：位操作置位
来源：http://dali.jianghu66.top/Article/details/gt2zkvqyztn.html

x |= (1 << 3);
来源：http://dali.hfpthk.cn/Article/details/gt2ysslrkqm.html

[S17] C：安全拼接字符串
来源：http://dali.yj20258.top/Article/details/gt2kztgyfdr.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.guannengcc.top/Article/details/gt2kkcuussn.html

[S18] C：命令行参数
来源：http://dali.jqgfzy.top/Article/details/gt2wosmzqyi.html

int main(int argc, char **argv)
来源：http://dali.daxiang520.top/Article/details/gt2zzmfnytt.html

[S19] C：快速排序
来源：http://dali.0kj1m.cn/Article/details/gt2thynvajd.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.hongshengwenyu.top/Article/details/gt2tuzsfxcg.html

[S20] C：二分查找
来源：http://dali.hnqzz.top/Article/details/gt2fcdjctbu.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zdqjudy.top/Article/details/gt2rhinefch.html

[S21] C：字符类别判断
来源：http://dali.tianlin.xyz/Article/details/gt2qrlmioko.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.xuanzx.com/Article/details/gt2khrbgwis.html

[S22] C：字符串转数字
来源：http://dali.xziqi.cn/Article/details/gt2nssfpphi.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.feifeiyinyue.top/Article/details/gt2blhyjjdr.html

[S23] C：随机数
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ternqsii.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.316326.xyz/Article/details/gt2dwsxmofx.html

[S24] C：获取本地时间
来源：http://dali.dashuyun.cn/Article/details/gt2qztepbqh.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.jinqigfzy.top/Article/details/gt2yfixxfys.html

[S25] C：内存拷贝
来源：http://dali.xuanzx.com/Article/details/gt2wnezlvyo.html

memcpy(dst, src, n);
来源：http://dali.jinqigufen.top/Article/details/gt2ehoguwqm.html

[S26] C：内存清零
来源：http://dali.yj20258888.top/Article/details/gt2azjkrahk.html

memset(a, 0, sizeof a);
来源：http://dali.c1oappe.top/Article/details/gt2micslppc.html

[S27] C：定义常量
来源：http://dali.tianlin.xyz/Article/details/gt2nyhempfz.html

const double PI = 3.14159;
来源：http://dali.ivvv.top/Article/details/gt2shsurqeg.html

[S28] C：静态变量
来源：http://dali.gaohongyu789.top/Article/details/gt2tkqoyhxb.html

static int counter = 0;
来源：http://dali.dianchejie.cn/Article/details/gt2dwflpxyt.html

[S29] C：变参函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zyhaezvg.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.nanxinkj.top/Article/details/gt2jbrdivlv.html

[S30] C：头文件保护
来源：http://dali.xylfe.cn/Article/details/gt2ennqcoqv.html

#ifndef X_H
来源：http://dali.haohaochexian.top/Article/details/gt2ujgsqsol.html

#define X_H
来源：http://dali.smart0.xyz/Article/details/gt2esdgascg.html

#endif
来源：http://dali.yongpay.top/Article/details/gt2rqeynseb.html

[S31] C++：Hello World
来源：http://dali.jqgufenzy.top/Article/details/gt2byjphovf.html

#include <iostream>
来源：http://dali.shangyingyoupin.top/Article/details/gt2nstsefwf.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.xylfe.cn/Article/details/gt2pdpgkpgg.html

[S32] C++：字符串
来源：http://dali.meibo888.top/Article/details/gt2pkqqfdeg.html

std::string s = "hi";  s += "!";
来源：http://dali.kuanghao11.cn/Article/details/gt2kkvnlror.html

[S33] C++：vector 增删
来源：http://dali.jlsjyb.cn/Article/details/gt2tvapznzi.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2cbujaxah.html

[S34] C++：遍历 vector
来源：http://dali.haohaochexian.top/Article/details/gt2ygwuuhjj.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.ivvv.top/Article/details/gt2bfmnbbyq.html

[S35] C++：map
来源：http://dali.xylfe.cn/Article/details/gt2fboetyjz.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yuanzhike.top/Article/details/gt2qhioksph.html

[S36] C++：unordered_map
来源：http://dali.hnxiangtu.top/Article/details/gt2oancxwne.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhixingplan.top/Article/details/gt2konhhmob.html

[S37] C++：set
来源：http://dali.ppjwa.cn/Article/details/gt2wqcdsxod.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.xuetiantiany.cn/Article/details/gt2ombxqbsm.html

[S38] C++：排序
来源：http://dali.zycfv.cn/Article/details/gt2fxsczzwm.html

std::sort(v.begin(), v.end());
来源：http://dali.hfpthk.cn/Article/details/gt2wshsgses.html

[S39] C++：自定义比较器排序
来源：http://dali.daria6918.cn/Article/details/gt2wqohyrev.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhengqikj.top/Article/details/gt2pzjrmdyx.html

[S40] C++：查找元素
来源：http://dali.xuetiantiany.cn/Article/details/gt2sxeyedar.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.kuanghao11.cn/Article/details/gt2wfrfhmqo.html

[S41] C++：类与构造函数
来源：http://dali.aibaodan.cn/Article/details/gt2migprxcm.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lgvjaafa.html

[S42] C++：继承与虚函数
来源：http://dali.dashuyun.cn/Article/details/gt2fftotnuf.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2oemkyisp.html

[S43] C++：智能指针
来源：http://dali.aibaodan.cn/Article/details/gt2fsjrrafo.html

auto p = std::make_unique<int>(5);
来源：http://dali.yj20258.top/Article/details/gt2tjcvkhaa.html

[S44] C++：引用传参
来源：http://dali.jiagoushi.top/Article/details/gt2undgtwlq.html

void inc(int &x) { ++x; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ezkgosnx.html

[S45] C++：lambda
来源：http://dali.daxiang520.top/Article/details/gt2hxfeewvt.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.sweek.top/Article/details/gt2otxxjuxp.html

[S46] C++：函数模板
来源：http://dali.mhx1999.top/Article/details/gt2huqexnzz.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.shzxlz.cn/Article/details/gt2kvhhjnvv.html

[S47] C++：结构化绑定遍历
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wwklvbcf.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.yj202588.top/Article/details/gt2xldapbuf.html

[S48] C++：逐行读文件
来源：http://dali.ehwqpu.com/Article/details/gt2wceapmum.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.ydzc1.top/Article/details/gt2txlpzavx.html

while (std::getline(in, line)) { }
来源：http://dali.xziqi.cn/Article/details/gt2lagccskz.html

[S49] C++：写文件
来源：http://dali.xziqi.cn/Article/details/gt2rkqyvamb.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.316326.xyz/Article/details/gt2mwjfgqew.html

[S50] C++：格式化数字
来源：http://dali.cucudq.cn/Article/details/gt2rderxxag.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.jiagoushi.top/Article/details/gt2jfremeie.html

[S51] C++：显式类型转换
来源：http://dali.zdqjudy.top/Article/details/gt2gthoxjef.html

static_cast<double>(a) / b
来源：http://dali.tianlin.xyz/Article/details/gt2dtvljirs.html

[S52] C++：const 与 noexcept
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2iwhfxbop.html

int size() const noexcept { return n_; }
来源：http://dali.ydzc1.top/Article/details/gt2veknqezy.html

[S53] C++：移动语义
来源：http://dali.yongpay.top/Article/details/gt2qekmcivu.html

std::vector<int> w = std::move(v);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cmcpnftm.html

[S54] C++：异常处理
来源：http://dali.0kj1m.cn/Article/details/gt2nwaavfyn.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.shzxlz.cn/Article/details/gt2tsomyeju.html

[S55] C++：结构化绑定
来源：http://dali.hnqzz.top/Article/details/gt2gimxpsdy.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.dianchejie.cn/Article/details/gt2qaryxops.html

[S56] C++：optional
来源：http://dali.nanxinkj.top/Article/details/gt2xsyatbya.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.hnxiangtu.top/Article/details/gt2jjpsbzwb.html

[S57] C++：编译期常量
来源：http://dali.cucudq.cn/Article/details/gt2mjiywybk.html

constexpr int N = 10;
来源：http://dali.yuxming.cn/Article/details/gt2rmqtblak.html

[S58] C++：命名空间
来源：http://dali.aizwys.cn/Article/details/gt2euufnbma.html

namespace ns { int f() { return 1; } }
来源：http://dali.snrcjt.cn/Article/details/gt2ovppdzat.html

[S59] C++：静态断言
来源：http://dali.gzhubu.top/Article/details/gt2mgihfmux.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.shangyingyoupin.top/Article/details/gt2rptnbrop.html

[S60] C++：遍历并删除元素
来源：http://dali.bjfxy.top/Article/details/gt2snqhepef.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jsjldcvw.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2fjnkgeot.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yangfankeji.com/Article/details/gt2omasvdrt.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2tbkgnaif.html

[T01] Kotlin：Hello World
来源：http://dali.chenjidiqi.icu/Article/details/gt2dlhpuebz.html

println("Hello")
来源：http://dali.yonumen.top/Article/details/gt2ekzgkkqq.html

[T02] Kotlin：变量
来源：http://dali.0kj1m.cn/Article/details/gt2iocwaxdj.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.jqgufenzy.top/Article/details/gt2zoyubkbw.html

[T03] Kotlin：字符串模板
来源：http://dali.gaohongyu789.top/Article/details/gt2bqtmpzan.html

"值: $b"
来源：http://dali.daria6918.cn/Article/details/gt2rfsquyzg.html

[T04] Kotlin：空安全
来源：http://dali.zycfv.cn/Article/details/gt2tuecdxgr.html

val n: String? = null;  n?.length
来源：http://dali.pengpengdd.cyou/Article/details/gt2prtepsbz.html

[T05] Kotlin：when 表达式
来源：http://dali.havefunace.top/Article/details/gt2jaerzwby.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.ehwqpu.com/Article/details/gt2qpiiznbk.html

[T06] Kotlin：集合映射
来源：http://dali.svipenyu.cn/Article/details/gt2ojmypmij.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.sufxvd.cn/Article/details/gt2rswuivrr.html

[T07] Kotlin：集合过滤
来源：http://dali.yuanzhike.top/Article/details/gt2gujmfjwa.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.hywenlv.cn/Article/details/gt2ljoltrmf.html

[T08] Kotlin：数据类
来源：http://dali.vqdsnc.cn/Article/details/gt2hozfukdm.html

data class User(val name: String, val age: Int)
来源：http://dali.hfpthk.cn/Article/details/gt2mznuqrzd.html

[T09] Kotlin：扩展函数
来源：http://dali.bjfxy.top/Article/details/gt2zkwaqjjf.html

fun String.exclaim() = this + "!"
来源：http://dali.sufxvd.cn/Article/details/gt2hqmuclje.html

[T10] Kotlin：默认参数
来源：http://dali.fengsongda.top/Article/details/gt2fbnmgpkw.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.hysaishi.cn/Article/details/gt2qddovvqg.html

[T11] Kotlin：协程
来源：http://dali.svipenyu.cn/Article/details/gt2tdetjxef.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.9152youxi.cn/Article/details/gt2eagmdhpl.html

[T12] Kotlin：解构声明
来源：http://dali.yonumen.top/Article/details/gt2voktcjoh.html

val (a, b) = Pair(1, 2)
来源：http://dali.jianghu66.top/Article/details/gt2tsymwwat.html

[T13] Kotlin：只读 Map
来源：http://dali.tanke756.top/Article/details/gt2vyxjgvow.html

val m = mapOf("a" to 1)
来源：http://dali.daxiang520.top/Article/details/gt2yabrqkpv.html

[T14] Kotlin：循环
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2iomspckh.html

for (i in 1..10) println(i)
来源：http://dali.yj202588.top/Article/details/gt2alsafogq.html

[T15] Kotlin：接口
来源：http://dali.wangshuangyany.cn/Article/details/gt2oorbfgha.html

interface Shape { fun area(): Double }
来源：http://dali.jyoumei.cn/Article/details/gt2brrpgmlr.html

[T16] Swift：Hello World
来源：http://dali.sxryk.cn/Article/details/gt2utrmkuof.html

print("Hello")
来源：http://dali.shuidangran.top/Article/details/gt2cpbsdzwj.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2lywididc.html

var a = 1;  let b = 2
来源：http://dali.cqqwz.cn/Article/details/gt2juinnxpa.html

[T18] Swift：字符串插值
来源：http://dali.chenjidiqi.icu/Article/details/gt2wznvoayc.html

"值: \(b)"
来源：http://dali.jinqigufen.top/Article/details/gt2lkssgcfy.html

[T19] Swift：可选绑定
来源：http://dali.yvedp.cn/Article/details/gt2wlhpnjmr.html

if let n = opt { print(n) }
来源：http://dali.tanke756.top/Article/details/gt2onzmmezx.html

[T20] Swift：数组操作
来源：http://dali.redwolf501.top/Article/details/gt2gbsxmkyj.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.yj202588.top/Article/details/gt2mbaxtkrl.html

[T21] Swift：遍历
来源：http://dali.birdmap.top/Article/details/gt2bwmiffae.html

for x in a { print(x) }
来源：http://dali.xuetiantiany.cn/Article/details/gt2iecenlrc.html

[T22] Swift：字典
来源：http://dali.hongshengwenyu.top/Article/details/gt2dvblozaw.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.gaohongyu789.top/Article/details/gt2rxukkpif.html

[T23] Swift：函数
来源：http://dali.guannengcc.top/Article/details/gt2lpzuprxq.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.sufxvd.cn/Article/details/gt2qymqdroj.html

[T24] Swift：闭包
来源：http://dali.0kj1m.cn/Article/details/gt2ecqymqwf.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.yvedp.cn/Article/details/gt2hfyxfzob.html

[T25] Swift：结构体
来源：http://dali.yvedp.cn/Article/details/gt2zkbwcwxs.html

struct P { var x: Int }
来源：http://dali.hywenlv.cn/Article/details/gt2ijjzyqsx.html

[T26] Swift：类与重写
来源：http://dali.ivvv.top/Article/details/gt2tfzxruko.html

class A: Base { override func f() {} }
来源：http://dali.zhengqikj.top/Article/details/gt2vudmnclt.html

[T27] Swift：错误处理
来源：http://dali.iojbl.cn/Article/details/gt2orehiwhx.html

do { try f() } catch { print(error) }
来源：http://dali.birdmap.top/Article/details/gt2eszpnmfw.html

[T28] Swift：枚举
来源：http://dali.dashuyun.cn/Article/details/gt2unaudaot.html

enum Color { case red, green }
来源：http://dali.jianghu66.top/Article/details/gt2ymgdclrb.html

[T29] Swift：guard 提前返回
来源：http://dali.yonumen.top/Article/details/gt2gttppguj.html

guard let x = opt else { return }
来源：http://dali.quarkkingdee.top/Article/details/gt2bhqvzldn.html

[T30] Swift：协议
来源：http://dali.svipenyu.cn/Article/details/gt2mdqtujlo.html

protocol Shape { func area() -> Double }
来源：http://dali.gaohongyu789.top/Article/details/gt2wjfhkpkd.html

[T31] Lua：Hello World
来源：http://dali.fengsongda.top/Article/details/gt2kqjwygzx.html

print("Hello")
来源：http://dali.chenjidiqi.icu/Article/details/gt2bizukzzt.html

[T32] Lua：局部变量
来源：http://dali.birdmap.top/Article/details/gt2euoakmra.html

local a = 1
来源：http://dali.yongpay.top/Article/details/gt2ddvgvero.html

[T33] Lua：表（数组）
来源：http://dali.yanxiufei.cn/Article/details/gt2awjqhgph.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.daxiang520.top/Article/details/gt2otqbsltu.html

[T34] Lua：遍历表
来源：http://dali.tianlin.xyz/Article/details/gt2yivmhpxj.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.hnqzz.top/Article/details/gt2qhmbhrxf.html

[T35] Lua：字典表
来源：http://dali.nanxinkj.top/Article/details/gt2dwhttclb.html

local d = { a = 1 };  d.b = 2
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tzyxkbwa.html

[T36] Lua：函数
来源：http://dali.cucudq.cn/Article/details/gt2dwanxneh.html

function add(a, b) return a + b end
来源：http://dali.hysaishi.cn/Article/details/gt2bmctphwd.html

[T37] Lua：字符串拼接
来源：http://dali.gaohongyu789.top/Article/details/gt2azdrvysr.html

"a" .. "b"
来源：http://dali.gotoacloud.top/Article/details/gt2uajodudg.html

[T38] Lua：条件
来源：http://dali.guowangkeji.top/Article/details/gt2hhfidhkp.html

if x > 0 then print("正") end
来源：http://dali.jianghu66.top/Article/details/gt2rwsoslau.html

[T39] Lua：模式匹配
来源：http://dali.cqqwz.cn/Article/details/gt2rnognijq.html

string.find(s, "%d+")
来源：http://dali.sweek.top/Article/details/gt2bjwjbykf.html

[T40] Lua：元表
来源：http://dali.jlsjyb.cn/Article/details/gt2ddkdwiof.html

setmetatable({}, { __index = base })
来源：http://dali.jinqigufen.top/Article/details/gt2qyuymgwn.html

[T41] Perl：Hello World
来源：http://dali.feifeiyinyue.top/Article/details/gt2dvhnakrk.html

print "Hello\n";
来源：http://dali.c1oappe.top/Article/details/gt2jbdghvmj.html

[T42] Perl：变量类型
来源：http://dali.xinyue.icu/Article/details/gt2ofrgveia.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.quarkkingdee.top/Article/details/gt2vwohhyit.html

[T43] Perl：字符串插值
来源：http://dali.pycfn.com/Article/details/gt2wjfxbuws.html

"值: $a"
来源：http://dali.ppjwa.cn/Article/details/gt2yzgtlcjm.html

[T44] Perl：条件
来源：http://dali.guannengcc.top/Article/details/gt2obsviyme.html

if ($a > 0) { print "正"; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2vgbclidq.html

[T45] Perl：数组遍历
来源：http://dali.zhoulong.xyz/Article/details/gt2evvmjmky.html

for my $x (@arr) { print $x; }
来源：http://dali.nwbrower.top/Article/details/gt2enfrfpqy.html

[T46] Perl：哈希操作
来源：http://dali.chenzaomai.com/Article/details/gt2bylkwdtj.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.sxryk.cn/Article/details/gt2aixibahh.html

[T47] Perl：正则捕获
来源：http://dali.andypj.xyz/Article/details/gt2uucsffkv.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.birdmap.top/Article/details/gt2olvufcwj.html

[T48] Perl：正则替换
来源：http://dali.tian-w.cn/Article/details/gt2jcmnuzuw.html

$s =~ s/old/new/g;
来源：http://dali.yj202588.top/Article/details/gt2ranruiri.html

[T49] Perl：函数
来源：http://dali.ivvv.top/Article/details/gt2cjnnsjxo.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2fazyisrj.html

[T50] Perl：逐行读文件
来源：http://dali.pengpengdd.cyou/Article/details/gt2lizhrwqp.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.wangdashe.top/Article/details/gt2voapbbyi.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.yj20258888.top/Article/details/gt2fyczyshu.html

[T51] Scala：Hello World
来源：http://dali.yueranfly.top/Article/details/gt2ywteocce.html

println("Hello")
来源：http://dali.redwolf501.top/Article/details/gt2cetrkivk.html

[T52] Scala：变量
来源：http://dali.gaohongyu789.top/Article/details/gt2tjtuvzbf.html

val a = 1;  var b = 2
来源：http://dali.yonumen.top/Article/details/gt2bqkzmqgg.html

[T53] Scala：字符串插值
来源：http://dali.yuxming.cn/Article/details/gt2pdigrjrq.html

s"值: $b"
来源：http://dali.nanxuanxn.top/Article/details/gt2vcryxsxb.html

[T54] Scala：集合映射
来源：http://dali.ivvv.top/Article/details/gt2pkcpyotw.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.c1oappe.top/Article/details/gt2afaggbif.html

[T55] Scala：集合过滤
来源：http://dali.yj20258888.top/Article/details/gt2oecsrmwj.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.feifeiyinyue.top/Article/details/gt2fqangsjv.html

[T56] Scala：样例类
来源：http://dali.ppjwa.cn/Article/details/gt2ptrfereu.html

case class User(name: String, age: Int)
来源：http://dali.shangyingyoupin.top/Article/details/gt2gtxzdqlp.html

[T57] Scala：模式匹配
来源：http://dali.zhixingplan.top/Article/details/gt2asswdebh.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qtrigztc.html

[T58] Scala：函数定义
来源：http://dali.ppjwa.cn/Article/details/gt2xlrlqhru.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.birdmap.top/Article/details/gt2pmxkpqmx.html

[T59] Scala：循环
来源：http://dali.zhixingplan.top/Article/details/gt2tkszysff.html

for (i <- 1 to 10) println(i)
来源：http://dali.hnxiangtu.top/Article/details/gt2uccafccc.html

[T60] Scala：折叠
来源：http://dali.jqgufenzy.top/Article/details/gt2dbssdagg.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.snrcjt.cn/Article/details/gt2pcajgzzm.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2iibrldom.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.nanxuanxn.top/Article/details/gt2omcdchyy.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2mctrzhzj.html

[U01] Py：创建虚拟环境
来源：http://dali.ydzc1.top/Article/details/gt2ookugpjq.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.jianghu66.top/Article/details/gt2uokomfyz.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhixingplan.top/Article/details/gt2hrxoddpz.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bkhdcvlj.html


<!-- 参考信息 -->