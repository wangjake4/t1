代发 wailian999

openssl rand -hex 16
来源：http://dali.chenlongwang.top/Article/details/gt2ktdxmxyg.html

[R68] 计算文件校验值
来源：http://dali.hnqzz.top/Article/details/gt2lnelgvpb.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.gogol.net.cn/Article/details/gt2duhtzuin.html

[R69] 生成随机密码
来源：http://dali.zhixingplan.top/Article/details/gt2mpcuptdx.html

head -c 16 /dev/urandom | base64
来源：http://dali.feifeiyinyue.top/Article/details/gt2vrkawzsi.html

[R70] 时间戳与互转
来源：http://dali.zhoulong.xyz/Article/details/gt2labhpcdk.html

date +%s;  date -d @1700000000
来源：http://dali.yangfankeji.com/Article/details/gt2opsmqfyx.html

[R71] 日期格式化
来源：http://dali.mhx1999.top/Article/details/gt2brinmwob.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.yj20258888.top/Article/details/gt2zgndlhbi.html

[R72] 等待端口就绪
来源：http://dali.tian-w.cn/Article/details/gt2hxmgbbtn.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.redwolf501.top/Article/details/gt2ascutqfy.html

[R73] 分割大日志
来源：http://dali.jinqigufen.top/Article/details/gt2htrtjvdm.html

split -l 1000 big.log part_
来源：http://dali.ydzc1.top/Article/details/gt2adlznfbm.html

[R74] 批量重命名
来源：http://dali.hysaishi.cn/Article/details/gt2wqzhgcpr.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.shangyingyoupin.top/Article/details/gt2dgiwgwko.html

[R75] 导出环境变量
来源：http://dali.yj202588.top/Article/details/gt2rkehigsl.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.cashguo.top/Article/details/gt2ktspzzjs.html

[R76] 使用临时文件
来源：http://dali.yonumen.top/Article/details/gt2wxeqtywr.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhongyouzk.top/Article/details/gt2ebzgtola.html

[R77] 读取用户输入
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qpicbzdc.html

read -rp "请输入: " ans
来源：http://dali.zhoulong.xyz/Article/details/gt2rgvxinhm.html

[R78] 交互式菜单
来源：http://dali.gogol.net.cn/Article/details/gt2jjgqrvds.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.yanxiufei.cn/Article/details/gt2upyipzsv.html

[R79] 解析命令行选项
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mzdxddhu.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.wangdashe.top/Article/details/gt2isqlokkt.html

[R80] 查看脚本执行耗时
来源：http://dali.yj20258888.top/Article/details/gt2abyhmhsb.html

time ./run.sh
来源：http://dali.hongshengwenyu.top/Article/details/gt2iqiarasb.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2zsljbiut.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2tdizbpbn.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2ikhraoml.html

[S01] C：Hello World
来源：http://dali.fengsongda.top/Article/details/gt2enpcdbvr.html

#include <stdio.h>
来源：http://dali.gotoacloud.top/Article/details/gt2khvknqds.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.c1oappe.top/Article/details/gt2rmfogehv.html

[S02] C：变量与格式化输出
来源：http://dali.ybcxt.top/Article/details/gt2cqojjady.html

int a = 10; printf("%d\n", a);
来源：http://dali.cqqwz.cn/Article/details/gt2cdvotqvq.html

[S03] C：读入整数
来源：http://dali.shangyingyoupin.top/Article/details/gt2zgiwwccq.html

int x; scanf("%d", &x);
来源：http://dali.gaohongyu789.top/Article/details/gt2xliawepj.html

[S04] C：字符串复制
来源：http://dali.birdmap.top/Article/details/gt2nfrjkcni.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.cdnleiting.top/Article/details/gt2tvxtcdmz.html

[S05] C：字符串长度
来源：http://dali.nwbrower.top/Article/details/gt2slscfgdm.html

strlen(s)
来源：http://dali.xylfe.cn/Article/details/gt2cfnghxrc.html

[S06] C：字符串比较
来源：http://dali.vqdsnc.cn/Article/details/gt2ixazpbhn.html

strcmp(a, b) == 0
来源：http://dali.yj20258888.top/Article/details/gt2zvbwnrcn.html

[S07] C：数组遍历求和
来源：http://dali.meibo888.top/Article/details/gt2gqgglakg.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mdrapviq.html

[S08] C：动态内存分配与释放
来源：http://dali.chenlongwang.top/Article/details/gt2zsebmqea.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pfvnwpoi.html

[S09] C：结构体定义与初始化
来源：http://dali.chenlongwang.top/Article/details/gt2gnbhnnkq.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.hfpthk.cn/Article/details/gt2qdaiytbz.html

[S10] C：指针与解引用
来源：http://dali.9152youxi.cn/Article/details/gt2fsrzncmt.html

int *p = &a;  *p = 5;
来源：http://dali.guowangkeji.top/Article/details/gt2yujndvpr.html

[S11] C：逐行读文件
来源：http://dali.zhiwuduotai.top/Article/details/gt2vladjrbv.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.yuanzhike.top/Article/details/gt2trppimsh.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.bjfxy.top/Article/details/gt2vbbaghlw.html

fclose(f);
来源：http://dali.ppjwa.cn/Article/details/gt2iahnykeh.html

[S12] C：写文件
来源：http://dali.shzxlz.cn/Article/details/gt2qkyahnpm.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.havefunace.top/Article/details/gt2qggqpdhu.html

[S13] C：宏定义
来源：http://dali.jinqigufen.top/Article/details/gt2wqrvdppu.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.vqdsnc.cn/Article/details/gt2toihbsfa.html

[S14] C：枚举
来源：http://dali.wangshuangyany.cn/Article/details/gt2ablsddrj.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.cqqwz.cn/Article/details/gt2flgxitcn.html

[S15] C：类型转换
来源：http://dali.dianchejie.cn/Article/details/gt2hgnpjlat.html

(double) a / b
来源：http://dali.cqqwz.cn/Article/details/gt2nxdkepfs.html

[S16] C：位操作置位
来源：http://dali.ppjwa.cn/Article/details/gt2dwajasnu.html

x |= (1 << 3);
来源：http://dali.xziqi.cn/Article/details/gt2kntfvwcu.html

[S17] C：安全拼接字符串
来源：http://dali.meibo888.top/Article/details/gt2ypdkbppe.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.chenzaomai.com/Article/details/gt2vsxwjhjn.html

[S18] C：命令行参数
来源：http://dali.hywenlv.cn/Article/details/gt2pkkditha.html

int main(int argc, char **argv)
来源：http://dali.yuanzhike.top/Article/details/gt2qglkuzkl.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2cxohckwh.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.jinqigufen.top/Article/details/gt2wtbqttaq.html

[S20] C：二分查找
来源：http://dali.xylfe.cn/Article/details/gt2hwfeyffe.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.9152youxi.cn/Article/details/gt2yatixevh.html

[S21] C：字符类别判断
来源：http://dali.aibaodan.cn/Article/details/gt2mpscrclp.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zdqjudy.top/Article/details/gt2vnfprufx.html

[S22] C：字符串转数字
来源：http://dali.havefunace.top/Article/details/gt2cdalwsks.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhixingplan.top/Article/details/gt2deydpyuc.html

[S23] C：随机数
来源：http://dali.jqgufenzy.top/Article/details/gt2waolzdmq.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.snrcjt.cn/Article/details/gt2ejsszwce.html

[S24] C：获取本地时间
来源：http://dali.tianlin.xyz/Article/details/gt2esjbpqhe.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.chenjidiqi.icu/Article/details/gt2obdtprxz.html

[S25] C：内存拷贝
来源：http://dali.pengpengdd.cyou/Article/details/gt2ngwgvslc.html

memcpy(dst, src, n);
来源：http://dali.xinyue.icu/Article/details/gt2zvexxprt.html

[S26] C：内存清零
来源：http://dali.cucudq.cn/Article/details/gt2vfmtrljh.html

memset(a, 0, sizeof a);
来源：http://dali.dianchejie.cn/Article/details/gt2rxvbhxue.html

[S27] C：定义常量
来源：http://dali.zhengqikj.top/Article/details/gt2wozaqdon.html

const double PI = 3.14159;
来源：http://dali.c1oappe.top/Article/details/gt2kefrrmym.html

[S28] C：静态变量
来源：http://dali.yanxiufei.cn/Article/details/gt2wyqbsevn.html

static int counter = 0;
来源：http://dali.jyoumei.cn/Article/details/gt2ckvhxljv.html

[S29] C：变参函数
来源：http://dali.wangshuangyany.cn/Article/details/gt2yhzconkh.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.shangyingyoupin.top/Article/details/gt2dbzxopuu.html

[S30] C：头文件保护
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xjmvcspy.html

#ifndef X_H
来源：http://dali.zhongyouzk.top/Article/details/gt2uvkikdoz.html

#define X_H
来源：http://dali.yj20258.top/Article/details/gt2kdfqpjgk.html

#endif
来源：http://dali.nwbrower.top/Article/details/gt2gmgzaxcf.html

[S31] C++：Hello World
来源：http://dali.nanxinkj.top/Article/details/gt2qqqatupo.html

#include <iostream>
来源：http://dali.haohaochexian.top/Article/details/gt2vdpovfdv.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zdqjudy.top/Article/details/gt2ljamlvbr.html

[S32] C++：字符串
来源：http://dali.pycfn.com/Article/details/gt2hrhbxsyq.html

std::string s = "hi";  s += "!";
来源：http://dali.dianchejie.cn/Article/details/gt2ihouurio.html

[S33] C++：vector 增删
来源：http://dali.hammf.cn/Article/details/gt2vzeosfje.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.kuanghao11.cn/Article/details/gt2xvbsrkjv.html

[S34] C++：遍历 vector
来源：http://dali.sweek.top/Article/details/gt2mrnxtkqv.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.jianghu66.top/Article/details/gt2bfjrrpva.html

[S35] C++：map
来源：http://dali.yongpay.top/Article/details/gt2htvsjytn.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.kuanghao11.cn/Article/details/gt2zuwpsfxn.html

[S36] C++：unordered_map
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2aqdhlcsk.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hongshengwenyu.top/Article/details/gt2yxmwzkmc.html

[S37] C++：set
来源：http://dali.svipenyu.cn/Article/details/gt2qvaajixq.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.yueranfly.top/Article/details/gt2wszpjsmw.html

[S38] C++：排序
来源：http://dali.guannengcc.top/Article/details/gt2jzdldjuc.html

std::sort(v.begin(), v.end());
来源：http://dali.daria6918.cn/Article/details/gt2zuzelsbj.html

[S39] C++：自定义比较器排序
来源：http://dali.ybcxt.top/Article/details/gt2hcjcvrjo.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.cdnleiting.top/Article/details/gt2walmzqcx.html

[S40] C++：查找元素
来源：http://dali.hysaishi.cn/Article/details/gt2ivryazas.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.nanxinkj.top/Article/details/gt2tvxdrgkf.html

[S41] C++：类与构造函数
来源：http://dali.dianchejie.cn/Article/details/gt2zheclgpc.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.dianchejie.cn/Article/details/gt2uymxqdpi.html

[S42] C++：继承与虚函数
来源：http://dali.aibaodan.cn/Article/details/gt2svxrtymo.html

class B : public Base { public: void f() override {} };
来源：http://dali.shuidangran.top/Article/details/gt2tgjnguuu.html

[S43] C++：智能指针
来源：http://dali.nwbrower.top/Article/details/gt2eoxndjdd.html

auto p = std::make_unique<int>(5);
来源：http://dali.yj20258888.top/Article/details/gt2dyzzqbtl.html

[S44] C++：引用传参
来源：http://dali.jianghu66.top/Article/details/gt2cltnznnt.html

void inc(int &x) { ++x; }
来源：http://dali.hywenlv.cn/Article/details/gt2nywggelr.html

[S45] C++：lambda
来源：http://dali.chenjidiqi.icu/Article/details/gt2ozpicknx.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.gaohongyu789.top/Article/details/gt2rhnzxotf.html

[S46] C++：函数模板
来源：http://dali.guannengcc.top/Article/details/gt2ngyxfprq.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.cqqwz.cn/Article/details/gt2svmlwepa.html

[S47] C++：结构化绑定遍历
来源：http://dali.zycfv.cn/Article/details/gt2benhvjgz.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2rkxknyrk.html

[S48] C++：逐行读文件
来源：http://dali.gzhubu.top/Article/details/gt2fkriiqeo.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.tanke756.top/Article/details/gt2eznnebgl.html

while (std::getline(in, line)) { }
来源：http://dali.316326.xyz/Article/details/gt2tihtcuol.html

[S49] C++：写文件
来源：http://dali.jinqigfzy.top/Article/details/gt2jzujqfjr.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.snrcjt.cn/Article/details/gt2fndsgxrf.html

[S50] C++：格式化数字
来源：http://dali.shzxlz.cn/Article/details/gt2cvwdfnqh.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.chenjidiqi.icu/Article/details/gt2kcwtoypi.html

[S51] C++：显式类型转换
来源：http://dali.yueranfly.top/Article/details/gt2lifmqhor.html

static_cast<double>(a) / b
来源：http://dali.aizwys.cn/Article/details/gt2znpvyzfr.html

[S52] C++：const 与 noexcept
来源：http://dali.pycfn.com/Article/details/gt2kycqgoam.html

int size() const noexcept { return n_; }
来源：http://dali.zhengqikj.top/Article/details/gt2mlkyxagk.html

[S53] C++：移动语义
来源：http://dali.hongshengwenyu.top/Article/details/gt2azyjxreu.html

std::vector<int> w = std::move(v);
来源：http://dali.yj202588.top/Article/details/gt2wdvnmrqv.html

[S54] C++：异常处理
来源：http://dali.fzhhl.top/Article/details/gt2ztrwkeyf.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.pengpengdd.cyou/Article/details/gt2frgbxobe.html

[S55] C++：结构化绑定
来源：http://dali.kuanghao11.cn/Article/details/gt2lsavsgog.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.xylfe.cn/Article/details/gt2anxqzzfv.html

[S56] C++：optional
来源：http://dali.dianchejie.cn/Article/details/gt2brjcywlo.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yuxming.cn/Article/details/gt2knnrrcpv.html

[S57] C++：编译期常量
来源：http://dali.yuxming.cn/Article/details/gt2dtftgwos.html

constexpr int N = 10;
来源：http://dali.dashuyun.cn/Article/details/gt2yhxmsbkk.html

[S58] C++：命名空间
来源：http://dali.hnqzz.top/Article/details/gt2zgboqank.html

namespace ns { int f() { return 1; } }
来源：http://dali.tianlin.xyz/Article/details/gt2tjwqwdmy.html

[S59] C++：静态断言
来源：http://dali.yongpay.top/Article/details/gt2podbgvcm.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.ydzc1.top/Article/details/gt2txoooizt.html

[S60] C++：遍历并删除元素
来源：http://dali.zdqjudy.top/Article/details/gt2qtdhwkpl.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.vqdsnc.cn/Article/details/gt2bvnyadwt.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2sqodzluu.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.quarkkingdee.top/Article/details/gt2wbamjylx.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2igxbjobz.html

[T01] Kotlin：Hello World
来源：http://dali.meibo888.top/Article/details/gt2ymfmdhvz.html

println("Hello")
来源：http://dali.gotoacloud.top/Article/details/gt2pzsxpxpm.html

[T02] Kotlin：变量
来源：http://dali.chenjidiqi.icu/Article/details/gt2bmkpfymv.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.cheryme.top/Article/details/gt2iyalkptm.html

[T03] Kotlin：字符串模板
来源：http://dali.smart0.xyz/Article/details/gt2uznbqsuc.html

"值: $b"
来源：http://dali.xziqi.cn/Article/details/gt2knxvomyd.html

[T04] Kotlin：空安全
来源：http://dali.316326.xyz/Article/details/gt2hokixxby.html

val n: String? = null;  n?.length
来源：http://dali.cheryme.top/Article/details/gt2wnbzkdzv.html

[T05] Kotlin：when 表达式
来源：http://dali.hammf.cn/Article/details/gt2iktikatl.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.guowangkeji.top/Article/details/gt2xfuobwhp.html

[T06] Kotlin：集合映射
来源：http://dali.kuanghao11.cn/Article/details/gt2ryzlngqi.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.hywenlv.cn/Article/details/gt2pzagmyqa.html

[T07] Kotlin：集合过滤
来源：http://dali.fengsongda.top/Article/details/gt2jopdsvhu.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.nanxinkj.top/Article/details/gt2sfzdxrnt.html

[T08] Kotlin：数据类
来源：http://dali.jqgfzy.top/Article/details/gt2zucixzpu.html

data class User(val name: String, val age: Int)
来源：http://dali.xuetiantiany.cn/Article/details/gt2eeebvtgy.html

[T09] Kotlin：扩展函数
来源：http://dali.9152youxi.cn/Article/details/gt2lfcvdynq.html

fun String.exclaim() = this + "!"
来源：http://dali.nanxinkj.top/Article/details/gt2swzybmxz.html

[T10] Kotlin：默认参数
来源：http://dali.nanxuanxn.top/Article/details/gt2cutoignm.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.hnxiangtu.top/Article/details/gt2vjijzyht.html

[T11] Kotlin：协程
来源：http://dali.chenzaomai.com/Article/details/gt2lnduiqbd.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.0kj1m.cn/Article/details/gt2hbdzxjdf.html

[T12] Kotlin：解构声明
来源：http://dali.bjfxy.top/Article/details/gt2eziuayig.html

val (a, b) = Pair(1, 2)
来源：http://dali.fzhhl.top/Article/details/gt2ykyoxygk.html

[T13] Kotlin：只读 Map
来源：http://dali.jinqigfzy.top/Article/details/gt2ptxadzvr.html

val m = mapOf("a" to 1)
来源：http://dali.kuanghao11.cn/Article/details/gt2ekvmfxkk.html

[T14] Kotlin：循环
来源：http://dali.nanxinkj.top/Article/details/gt2hntxjpnv.html

for (i in 1..10) println(i)
来源：http://dali.nwbrower.top/Article/details/gt2hpcunmxu.html

[T15] Kotlin：接口
来源：http://dali.svipenyu.cn/Article/details/gt2zqihhnij.html

interface Shape { fun area(): Double }
来源：http://dali.cucudq.cn/Article/details/gt2lcgwsufe.html

[T16] Swift：Hello World
来源：http://dali.meibo888.top/Article/details/gt2frzwwvhq.html

print("Hello")
来源：http://dali.daria6918.cn/Article/details/gt2xaopbymm.html

[T17] Swift：变量与常量
来源：http://dali.bjfxy.top/Article/details/gt2gkngjljj.html

var a = 1;  let b = 2
来源：http://dali.cheryme.top/Article/details/gt2zqbytiwo.html

[T18] Swift：字符串插值
来源：http://dali.shanyushiyangtech.top/Article/details/gt2iurmdmke.html

"值: \(b)"
来源：http://dali.hysaishi.cn/Article/details/gt2rixebfgb.html

[T19] Swift：可选绑定
来源：http://dali.birdmap.top/Article/details/gt2vedjbjsp.html

if let n = opt { print(n) }
来源：http://dali.hywenlv.cn/Article/details/gt2ggbcczap.html

[T20] Swift：数组操作
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mhadrtee.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.snrcjt.cn/Article/details/gt2scbkqkrp.html

[T21] Swift：遍历
来源：http://dali.aizwys.cn/Article/details/gt2amxqljgi.html

for x in a { print(x) }
来源：http://dali.yuxming.cn/Article/details/gt2jldxrrvh.html

[T22] Swift：字典
来源：http://dali.hnqzz.top/Article/details/gt2qkeaexfl.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.yangfankeji.com/Article/details/gt2ongiqfgw.html

[T23] Swift：函数
来源：http://dali.svipenyu.cn/Article/details/gt2xjdvdqik.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.xinyue.icu/Article/details/gt2khbxqowl.html

[T24] Swift：闭包
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tpcvlred.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.hongshengwenyu.top/Article/details/gt2skqaouqf.html

[T25] Swift：结构体
来源：http://dali.cucudq.cn/Article/details/gt2xupppifa.html

struct P { var x: Int }
来源：http://dali.aibaodan.cn/Article/details/gt2phupwyjd.html

[T26] Swift：类与重写
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hsdtwlbh.html

class A: Base { override func f() {} }
来源：http://dali.hfpthk.cn/Article/details/gt2opevicas.html

[T27] Swift：错误处理
来源：http://dali.quarkkingdee.top/Article/details/gt2upcwgovc.html

do { try f() } catch { print(error) }
来源：http://dali.redwolf501.top/Article/details/gt2hmfkyykb.html

[T28] Swift：枚举
来源：http://dali.mhx1999.top/Article/details/gt2nsfekywo.html

enum Color { case red, green }
来源：http://dali.yj202588.top/Article/details/gt2bccnisju.html

[T29] Swift：guard 提前返回
来源：http://dali.feifeiyinyue.top/Article/details/gt2qjpapwfk.html

guard let x = opt else { return }
来源：http://dali.hfpthk.cn/Article/details/gt2udqwpjiq.html

[T30] Swift：协议
来源：http://dali.quarkkingdee.top/Article/details/gt2peafqent.html

protocol Shape { func area() -> Double }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lqjioqgb.html

[T31] Lua：Hello World
来源：http://dali.hnqzz.top/Article/details/gt2szreyanu.html

print("Hello")
来源：http://dali.snrcjt.cn/Article/details/gt2cpppmbhh.html

[T32] Lua：局部变量
来源：http://dali.wangdashe.top/Article/details/gt2kxflwokh.html

local a = 1
来源：http://dali.ehwqpu.com/Article/details/gt2zvhcrmau.html

[T33] Lua：表（数组）
来源：http://dali.nanxinkj.top/Article/details/gt2ivwvyvku.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.meibo888.top/Article/details/gt2guirgnbq.html

[T34] Lua：遍历表
来源：http://dali.feifeiyinyue.top/Article/details/gt2xkqtdbkt.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.cucudq.cn/Article/details/gt2yynvpife.html

[T35] Lua：字典表
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2iycjnvya.html

local d = { a = 1 };  d.b = 2
来源：http://dali.chenjidiqi.icu/Article/details/gt2lmlsxied.html

[T36] Lua：函数
来源：http://dali.kuanghao11.cn/Article/details/gt2mrtrvmgz.html

function add(a, b) return a + b end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hdpwobnx.html

[T37] Lua：字符串拼接
来源：http://dali.gaohongyu789.top/Article/details/gt2zmvijqmn.html

"a" .. "b"
来源：http://dali.yonumen.top/Article/details/gt2oacrgvfm.html

[T38] Lua：条件
来源：http://dali.nanxinkj.top/Article/details/gt2vyyddfxw.html

if x > 0 then print("正") end
来源：http://dali.zhoulong.xyz/Article/details/gt2wvpzdenv.html

[T39] Lua：模式匹配
来源：http://dali.tian-w.cn/Article/details/gt2axjvzdlm.html

string.find(s, "%d+")
来源：http://dali.meibo888.top/Article/details/gt2thncmeay.html

[T40] Lua：元表
来源：http://dali.cheryme.top/Article/details/gt2bxkkfjjo.html

setmetatable({}, { __index = base })
来源：http://dali.gzhubu.top/Article/details/gt2ajgitrlu.html

[T41] Perl：Hello World
来源：http://dali.yongpay.top/Article/details/gt2pwkdkcth.html

print "Hello\n";
来源：http://dali.jinqigfzy.top/Article/details/gt2dwnwaufm.html

[T42] Perl：变量类型
来源：http://dali.meibo888.top/Article/details/gt2puymojgf.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.sxryk.cn/Article/details/gt2hcpweuhv.html

[T43] Perl：字符串插值
来源：http://dali.xylfe.cn/Article/details/gt2wnxasgyh.html

"值: $a"
来源：http://dali.nanxuanxn.top/Article/details/gt2zglrdflk.html

[T44] Perl：条件
来源：http://dali.jinqigfzy.top/Article/details/gt2xprutxab.html

if ($a > 0) { print "正"; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xxbvjeiu.html

[T45] Perl：数组遍历
来源：http://dali.0kj1m.cn/Article/details/gt2azpzpzty.html

for my $x (@arr) { print $x; }
来源：http://dali.iojbl.cn/Article/details/gt2sbrpwqoj.html

[T46] Perl：哈希操作
来源：http://dali.hnqzz.top/Article/details/gt2mjxmbgnt.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.c1oappe.top/Article/details/gt2opgelufu.html

[T47] Perl：正则捕获
来源：http://dali.hywenlv.cn/Article/details/gt2hmvcnuwd.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.cashguo.top/Article/details/gt2uhvregcv.html

[T48] Perl：正则替换
来源：http://dali.zhiwuduotai.top/Article/details/gt2grhbvhpm.html

$s =~ s/old/new/g;
来源：http://dali.cashguo.top/Article/details/gt2ruoorhfc.html

[T49] Perl：函数
来源：http://dali.nanxuanxn.top/Article/details/gt2sblwkpzy.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.cheryme.top/Article/details/gt2fhzzoroj.html

[T50] Perl：逐行读文件
来源：http://dali.jianghu66.top/Article/details/gt2rfwpoeaz.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2urupxdri.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.nanxuanxn.top/Article/details/gt2msdppqca.html

[T51] Scala：Hello World
来源：http://dali.iojbl.cn/Article/details/gt2qqbbcclr.html

println("Hello")
来源：http://dali.gotoacloud.top/Article/details/gt2zfsojedr.html

[T52] Scala：变量
来源：http://dali.zhengqikj.top/Article/details/gt2hkqmjllp.html

val a = 1;  var b = 2
来源：http://dali.tian-w.cn/Article/details/gt2xakmzooo.html

[T53] Scala：字符串插值
来源：http://dali.feifeiyinyue.top/Article/details/gt2ywoocrpr.html

s"值: $b"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dtynjfku.html

[T54] Scala：集合映射
来源：http://dali.yonumen.top/Article/details/gt2kaujikgz.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.andypj.xyz/Article/details/gt2ajlaipef.html

[T55] Scala：集合过滤
来源：http://dali.gaohongyu789.top/Article/details/gt2ahchdwrg.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.fzhhl.top/Article/details/gt2bkotgfkp.html

[T56] Scala：样例类
来源：http://dali.sxryk.cn/Article/details/gt2gclwnsjm.html

case class User(name: String, age: Int)
来源：http://dali.fengsongda.top/Article/details/gt2ftpyizvz.html

[T57] Scala：模式匹配
来源：http://dali.hfpthk.cn/Article/details/gt2ctdyqqbq.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.havefunace.top/Article/details/gt2xzkenqzk.html

[T58] Scala：函数定义
来源：http://dali.xylfe.cn/Article/details/gt2mhndsnjp.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qnrugcqf.html

[T59] Scala：循环
来源：http://dali.sweek.top/Article/details/gt2zhhsiyzt.html

for (i <- 1 to 10) println(i)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2awpziuet.html

[T60] Scala：折叠
来源：http://dali.xuetiantiany.cn/Article/details/gt2guntjfmy.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.sweek.top/Article/details/gt2qxonrguv.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2jrfrhsgc.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.quarkkingdee.top/Article/details/gt2untcqpwe.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2inqorttx.html

[U01] Py：创建虚拟环境
来源：http://dali.tian-w.cn/Article/details/gt2wawyelln.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.fzhhl.top/Article/details/gt2hexfpinr.html

[U02] Py：导出 / 安装依赖
来源：http://dali.shuidangran.top/Article/details/gt2wmtyjtji.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.shzxlz.cn/Article/details/gt2ltdppiea.html

[U03] Py：加载 .env 配置
来源：http://dali.jinghuilouyu.cn/Article/details/gt2stxzgbfl.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.quarkkingdee.top/Article/details/gt2cnaixlzi.html

[U04] Py：变量调试打印
来源：http://dali.jiagoushi.top/Article/details/gt2ecewphfy.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.bjfxy.top/Article/details/gt2buvatadb.html

[U05] Py：列表去重且保序
来源：http://dali.xuanzx.com/Article/details/gt2trifryew.html

list(dict.fromkeys(arr))
来源：http://dali.hysaishi.cn/Article/details/gt2namxjhtl.html

[U06] Py：合并两个字典
来源：http://dali.tianlin.xyz/Article/details/gt2xyvhkxop.html

{**a, **b}
来源：http://dali.xinyue.icu/Article/details/gt2jjzhajjp.html

[U07] Py：反转字典键值
来源：http://dali.c1oappe.top/Article/details/gt2cfggcrpl.html

{v: k for k, v in d.items()}
来源：http://dali.haohaochexian.top/Article/details/gt2ppbejilh.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2xglodlrj.html

[y for x in nested for y in x]
来源：http://dali.gotoacloud.top/Article/details/gt2hmuvvfxo.html


<!-- 参考信息 -->