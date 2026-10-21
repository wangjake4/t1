代发 wailian999

openssl rand -hex 16
来源：http://dali.andypj.xyz/Article/details/gtizdqokyu.html

[R68] 计算文件校验值
来源：http://dali.zhengqikj.top/Article/details/gtytwywway.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.haohaochexian.top/Article/details/gtsflzgeae.html

[R69] 生成随机密码
来源：http://dali.nwbrower.top/Article/details/gtoxermabq.html

head -c 16 /dev/urandom | base64
来源：http://dali.dianchejie.cn/Article/details/gtdugshbdj.html

[R70] 时间戳与互转
来源：http://dali.svipenyu.cn/Article/details/gtmnpemjko.html

date +%s;  date -d @1700000000
来源：http://dali.gogol.net.cn/Article/details/gtifqfmqgd.html

[R71] 日期格式化
来源：http://dali.gotoacloud.top/Article/details/gtwiriygxh.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.9152youxi.cn/Article/details/gtxyrzdbel.html

[R72] 等待端口就绪
来源：http://dali.guannengcc.top/Article/details/gtletxwfqp.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.mhx1999.top/Article/details/gtxabmbual.html

[R73] 分割大日志
来源：http://dali.dianchejie.cn/Article/details/gtqlinhfvy.html

split -l 1000 big.log part_
来源：http://dali.zhoulong.xyz/Article/details/gtgfqwohdp.html

[R74] 批量重命名
来源：http://dali.xylfe.cn/Article/details/gtlhxduwlk.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.aizwys.cn/Article/details/gtkshivmnu.html

[R75] 导出环境变量
来源：http://dali.fzhhl.top/Article/details/gtbwlawqiv.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.wangdashe.top/Article/details/gtoqmmzsgp.html

[R76] 使用临时文件
来源：http://dali.xuetiantiany.cn/Article/details/gtppunvadx.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.jinqigfzy.top/Article/details/gtkpfuifmu.html

[R77] 读取用户输入
来源：http://dali.birdmap.top/Article/details/gtvdpvnpvy.html

read -rp "请输入: " ans
来源：http://dali.jqgfzy.top/Article/details/gtqpimqich.html

[R78] 交互式菜单
来源：http://dali.yongpay.top/Article/details/gtzxyxbmfb.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.haohaochexian.top/Article/details/gtwowamwyu.html

[R79] 解析命令行选项
来源：http://dali.sysykeji.top/Article/details/gtundntyeu.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.daxiang520.top/Article/details/gttagtywpx.html

[R80] 查看脚本执行耗时
来源：http://dali.wangdashe.top/Article/details/gtpgutqpuy.html

time ./run.sh
来源：http://dali.xziqi.cn/Article/details/gtatphpdvs.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtnfwjirxu.html

S. C / C++ 专题
来源：http://dali.nanxinkj.top/Article/details/gtzzmensbi.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtecvonohf.html

[S01] C：Hello World
来源：http://dali.316326.xyz/Article/details/gtwyprmzvp.html

#include <stdio.h>
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpsdqqnag.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.aibaodan.cn/Article/details/gtdyeozujx.html

[S02] C：变量与格式化输出
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfuzbxjbk.html

int a = 10; printf("%d\n", a);
来源：http://dali.ivvv.top/Article/details/gtaarijbrw.html

[S03] C：读入整数
来源：http://dali.gotoacloud.top/Article/details/gtcamwiafj.html

int x; scanf("%d", &x);
来源：http://dali.jinghuilouyu.cn/Article/details/gtkuhpoerr.html

[S04] C：字符串复制
来源：http://dali.jyoumei.cn/Article/details/gtdqvjsxpm.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.svipenyu.cn/Article/details/gtyiakuaqa.html

[S05] C：字符串长度
来源：http://dali.sweek.top/Article/details/gtpehctyfk.html

strlen(s)
来源：http://dali.gogol.net.cn/Article/details/gtcuprweic.html

[S06] C：字符串比较
来源：http://dali.xziqi.cn/Article/details/gtopqxfson.html

strcmp(a, b) == 0
来源：http://dali.cheryme.top/Article/details/gtncbmremw.html

[S07] C：数组遍历求和
来源：http://dali.sufxvd.cn/Article/details/gtmoguevre.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.hysaishi.cn/Article/details/gtabqgdhhc.html

[S08] C：动态内存分配与释放
来源：http://dali.ivvv.top/Article/details/gtbtwrpiny.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.jiagoushi.top/Article/details/gtuorufvxu.html

[S09] C：结构体定义与初始化
来源：http://dali.jqgfzy.top/Article/details/gteceywekz.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhixingplan.top/Article/details/gtebujxmyg.html

[S10] C：指针与解引用
来源：http://dali.hongshengwenyu.top/Article/details/gteohlajsy.html

int *p = &a;  *p = 5;
来源：http://dali.svipenyu.cn/Article/details/gtxjeuticm.html

[S11] C：逐行读文件
来源：http://dali.hongshengwenyu.top/Article/details/gtdwstxtrp.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.gotoacloud.top/Article/details/gtlelfgvnr.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.sysykeji.top/Article/details/gtnupptwyj.html

fclose(f);
来源：http://dali.vqdsnc.cn/Article/details/gtlagrftfm.html

[S12] C：写文件
来源：http://dali.hnxiangtu.top/Article/details/gthcojllbi.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.9152youxi.cn/Article/details/gtbthxdwqd.html

[S13] C：宏定义
来源：http://dali.havefunace.top/Article/details/gtyyjhxwhk.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.nanxuanxn.top/Article/details/gtwickpdsk.html

[S14] C：枚举
来源：http://dali.jqgfzy.top/Article/details/gtvmgfefjm.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.jinqigufen.top/Article/details/gtkdfzqjju.html

[S15] C：类型转换
来源：http://dali.chenlongwang.top/Article/details/gtykdrtcqj.html

(double) a / b
来源：http://dali.jiagoushi.top/Article/details/gtlovyjzty.html

[S16] C：位操作置位
来源：http://dali.aibaodan.cn/Article/details/gtyyissivm.html

x |= (1 << 3);
来源：http://dali.cqqwz.cn/Article/details/gtioxuagdf.html

[S17] C：安全拼接字符串
来源：http://dali.yuxming.cn/Article/details/gtwdtqvshb.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.chenjidiqi.icu/Article/details/gtgrzowuzl.html

[S18] C：命令行参数
来源：http://dali.andypj.xyz/Article/details/gtjcnfglsc.html

int main(int argc, char **argv)
来源：http://dali.vqdsnc.cn/Article/details/gttartwrnd.html

[S19] C：快速排序
来源：http://dali.zhixingplan.top/Article/details/gtovingdye.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.sxryk.cn/Article/details/gtrmtzqpwi.html

[S20] C：二分查找
来源：http://dali.zhongyouzk.top/Article/details/gtmchpbeuk.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.hongshengwenyu.top/Article/details/gtpqxounqf.html

[S21] C：字符类别判断
来源：http://dali.zhengqikj.top/Article/details/gtnaoxauiv.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.tian-w.cn/Article/details/gtszhqlajs.html

[S22] C：字符串转数字
来源：http://dali.hammf.cn/Article/details/gtlmftvrny.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.jqgufenzy.top/Article/details/gtzetlfpso.html

[S23] C：随机数
来源：http://dali.yuanzhike.top/Article/details/gtywlhfgtm.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.sysykeji.top/Article/details/gtrkvkpzxi.html

[S24] C：获取本地时间
来源：http://dali.ybcxt.top/Article/details/gtssmlgyzq.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zdqjudy.top/Article/details/gtquykswly.html

[S25] C：内存拷贝
来源：http://dali.nwbrower.top/Article/details/gtehezunmk.html

memcpy(dst, src, n);
来源：http://dali.jyoumei.cn/Article/details/gtxmklsbmp.html

[S26] C：内存清零
来源：http://dali.wangdashe.top/Article/details/gtldzxraqn.html

memset(a, 0, sizeof a);
来源：http://dali.cheryme.top/Article/details/gteofomwvr.html

[S27] C：定义常量
来源：http://dali.sysykeji.top/Article/details/gtofgoaava.html

const double PI = 3.14159;
来源：http://dali.iojbl.cn/Article/details/gtlweicjqn.html

[S28] C：静态变量
来源：http://dali.tianlin.xyz/Article/details/gtgzxenrgz.html

static int counter = 0;
来源：http://dali.gaohongyu789.top/Article/details/gtdzcpnekw.html

[S29] C：变参函数
来源：http://dali.havefunace.top/Article/details/gthqhwhanb.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.andypj.xyz/Article/details/gtyjmnsxey.html

[S30] C：头文件保护
来源：http://dali.zycfv.cn/Article/details/gtfxwvgfwe.html

#ifndef X_H
来源：http://dali.pycfn.com/Article/details/gtetpamvaf.html

#define X_H
来源：http://dali.yangfankeji.com/Article/details/gtqysxzzqr.html

#endif
来源：http://dali.xylfe.cn/Article/details/gtvotaejdn.html

[S31] C++：Hello World
来源：http://dali.yj20258888.top/Article/details/gtubmoeuwe.html

#include <iostream>
来源：http://dali.chenjidiqi.icu/Article/details/gtgvhupvrx.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.cashguo.top/Article/details/gtdeapitvw.html

[S32] C++：字符串
来源：http://dali.hnxiangtu.top/Article/details/gtoanrxwta.html

std::string s = "hi";  s += "!";
来源：http://dali.jqgufenzy.top/Article/details/gtcvhhlwsw.html

[S33] C++：vector 增删
来源：http://dali.jinyuanbaomall.cn/Article/details/gtedexlcst.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.aibaodan.cn/Article/details/gtqbmdeiqd.html

[S34] C++：遍历 vector
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfivynyud.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.ybcxt.top/Article/details/gtxjxkvbef.html

[S35] C++：map
来源：http://dali.kuanghao11.cn/Article/details/gthijpbprh.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yj20258888.top/Article/details/gtfzhtigky.html

[S36] C++：unordered_map
来源：http://dali.jiagoushi.top/Article/details/gtzseoaotc.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.gotoacloud.top/Article/details/gtyzcgvsiu.html

[S37] C++：set
来源：http://dali.hysaishi.cn/Article/details/gtvbutotcq.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.tanke756.top/Article/details/gtyxyvuvjc.html

[S38] C++：排序
来源：http://dali.gotoacloud.top/Article/details/gtxualhbgd.html

std::sort(v.begin(), v.end());
来源：http://dali.nanxuanxn.top/Article/details/gtrtsfidsm.html

[S39] C++：自定义比较器排序
来源：http://dali.nwbrower.top/Article/details/gtfurymjeb.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.wangdashe.top/Article/details/gtujzllhge.html

[S40] C++：查找元素
来源：http://dali.snrcjt.cn/Article/details/gtdadvrjzj.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.shuidangran.top/Article/details/gtvzpfyvtq.html

[S41] C++：类与构造函数
来源：http://dali.feifeiyinyue.top/Article/details/gtnrmqdiex.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.kuanghao11.cn/Article/details/gtrnbyxrai.html

[S42] C++：继承与虚函数
来源：http://dali.snrcjt.cn/Article/details/gtpcymaobo.html

class B : public Base { public: void f() override {} };
来源：http://dali.yonumen.top/Article/details/gtiwdekdzh.html

[S43] C++：智能指针
来源：http://dali.gotoacloud.top/Article/details/gtwmmnqitp.html

auto p = std::make_unique<int>(5);
来源：http://dali.bjfxy.top/Article/details/gtpostjfam.html

[S44] C++：引用传参
来源：http://dali.zhongyouzk.top/Article/details/gtnvjqgdya.html

void inc(int &x) { ++x; }
来源：http://dali.yj202588.top/Article/details/gtayivoris.html

[S45] C++：lambda
来源：http://dali.zycfv.cn/Article/details/gttqchtlaq.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.jinghuilouyu.cn/Article/details/gtdzxbmtun.html

[S46] C++：函数模板
来源：http://dali.chenjidiqi.icu/Article/details/gtgnqdmudj.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.iojbl.cn/Article/details/gtkkkganwt.html

[S47] C++：结构化绑定遍历
来源：http://dali.pycfn.com/Article/details/gtmqgaxamb.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhoulong.xyz/Article/details/gtdsofrgui.html

[S48] C++：逐行读文件
来源：http://dali.nanxuanxn.top/Article/details/gtxwgnsbxl.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.cdnleiting.top/Article/details/gtdsiuxqho.html

while (std::getline(in, line)) { }
来源：http://dali.c1oappe.top/Article/details/gtswfutmqb.html

[S49] C++：写文件
来源：http://dali.zhengqikj.top/Article/details/gtbswtwpqj.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.jqgfzy.top/Article/details/gtnmtibkov.html

[S50] C++：格式化数字
来源：http://dali.gotoacloud.top/Article/details/gtlxlorwpi.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.shuidangran.top/Article/details/gtdniyosve.html

[S51] C++：显式类型转换
来源：http://dali.ehwqpu.com/Article/details/gtkwolmddd.html

static_cast<double>(a) / b
来源：http://dali.yuxming.cn/Article/details/gtlyfyxnip.html

[S52] C++：const 与 noexcept
来源：http://dali.cheryme.top/Article/details/gtssolfgkj.html

int size() const noexcept { return n_; }
来源：http://dali.yueranfly.top/Article/details/gtljoisnel.html

[S53] C++：移动语义
来源：http://dali.cashguo.top/Article/details/gtxzefqktu.html

std::vector<int> w = std::move(v);
来源：http://dali.jyoumei.cn/Article/details/gtgabvmxkt.html

[S54] C++：异常处理
来源：http://dali.svipenyu.cn/Article/details/gtovewqkiu.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.hnqzz.top/Article/details/gtbsonkfwx.html

[S55] C++：结构化绑定
来源：http://dali.andypj.xyz/Article/details/gtuqibgqza.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.ydzc1.top/Article/details/gtozmxxaro.html

[S56] C++：optional
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgdymccxe.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.tian-w.cn/Article/details/gtwrgqndbj.html

[S57] C++：编译期常量
来源：http://dali.zhoulong.xyz/Article/details/gtsngtgqcd.html

constexpr int N = 10;
来源：http://dali.sufxvd.cn/Article/details/gtfeugtiif.html

[S58] C++：命名空间
来源：http://dali.zhongyouzk.top/Article/details/gtheksxuns.html

namespace ns { int f() { return 1; } }
来源：http://dali.yj202588.top/Article/details/gtmbeqrvng.html

[S59] C++：静态断言
来源：http://dali.feifeiyinyue.top/Article/details/gtztqpcrqd.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.gogol.net.cn/Article/details/gtphmaaxku.html

[S60] C++：遍历并删除元素
来源：http://dali.tianlin.xyz/Article/details/gtkdhwlzaq.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.c1oappe.top/Article/details/gtpaekxrcv.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtouqrpasg.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.jinghuilouyu.cn/Article/details/gtpgmlrsft.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtbsryhpev.html

[T01] Kotlin：Hello World
来源：http://dali.nwbrower.top/Article/details/gtwjzyuzcj.html

println("Hello")
来源：http://dali.yongpay.top/Article/details/gtllqncooa.html

[T02] Kotlin：变量
来源：http://dali.gogol.net.cn/Article/details/gtdatpcsyo.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.tanke756.top/Article/details/gtnfcirexy.html

[T03] Kotlin：字符串模板
来源：http://dali.fengsongda.top/Article/details/gtqzcislyb.html

"值: $b"
来源：http://dali.nwbrower.top/Article/details/gtoibryaef.html

[T04] Kotlin：空安全
来源：http://dali.meibo888.top/Article/details/gtocscysvi.html

val n: String? = null;  n?.length
来源：http://dali.hnxiangtu.top/Article/details/gtijaskdzd.html

[T05] Kotlin：when 表达式
来源：http://dali.zhixingplan.top/Article/details/gtadnvcvrd.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.sxryk.cn/Article/details/gtmboctkss.html

[T06] Kotlin：集合映射
来源：http://dali.yongpay.top/Article/details/gtscdsawtg.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.yanxiufei.cn/Article/details/gttaxopbab.html

[T07] Kotlin：集合过滤
来源：http://dali.hongshengwenyu.top/Article/details/gtdvrmuaeq.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.ehwqpu.com/Article/details/gttlqzmzbi.html

[T08] Kotlin：数据类
来源：http://dali.dianchejie.cn/Article/details/gtgmeeoafo.html

data class User(val name: String, val age: Int)
来源：http://dali.xylfe.cn/Article/details/gtbbhgkfbb.html

[T09] Kotlin：扩展函数
来源：http://dali.ivvv.top/Article/details/gtltcjwxhv.html

fun String.exclaim() = this + "!"
来源：http://dali.fzhhl.top/Article/details/gtsnodergk.html

[T10] Kotlin：默认参数
来源：http://dali.hammf.cn/Article/details/gtsxcjghvh.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.yangfankeji.com/Article/details/gtpqpqauce.html

[T11] Kotlin：协程
来源：http://dali.dianchejie.cn/Article/details/gticzrugla.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.svipenyu.cn/Article/details/gtdkmbgtha.html

[T12] Kotlin：解构声明
来源：http://dali.0kj1m.cn/Article/details/gtdyyorryj.html

val (a, b) = Pair(1, 2)
来源：http://dali.fengsongda.top/Article/details/gtlgnjtvkl.html

[T13] Kotlin：只读 Map
来源：http://dali.hywenlv.cn/Article/details/gtwejrypct.html

val m = mapOf("a" to 1)
来源：http://dali.316326.xyz/Article/details/gtbjdqutay.html

[T14] Kotlin：循环
来源：http://dali.guannengcc.top/Article/details/gtnjcpomwo.html

for (i in 1..10) println(i)
来源：http://dali.chenlongwang.top/Article/details/gtnwdlapln.html

[T15] Kotlin：接口
来源：http://dali.sufxvd.cn/Article/details/gtdycemnpa.html

interface Shape { fun area(): Double }
来源：http://dali.9152youxi.cn/Article/details/gtulmnhesh.html

[T16] Swift：Hello World
来源：http://dali.hfpthk.cn/Article/details/gtdyfcfakb.html

print("Hello")
来源：http://dali.xinyue.icu/Article/details/gttzsaxdhh.html

[T17] Swift：变量与常量
来源：http://dali.xinyue.icu/Article/details/gtornlosfj.html

var a = 1;  let b = 2
来源：http://dali.yonumen.top/Article/details/gtdlpohnih.html

[T18] Swift：字符串插值
来源：http://dali.feifeiyinyue.top/Article/details/gtlqzjpxyx.html

"值: \(b)"
来源：http://dali.xziqi.cn/Article/details/gtvmzzkqvx.html

[T19] Swift：可选绑定
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcjnqfene.html

if let n = opt { print(n) }
来源：http://dali.0kj1m.cn/Article/details/gtobhtktqo.html

[T20] Swift：数组操作
来源：http://dali.daxiang520.top/Article/details/gtouyxzlag.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.yj202588.top/Article/details/gtrifkpqyw.html

[T21] Swift：遍历
来源：http://dali.sxryk.cn/Article/details/gtavdvuiwu.html

for x in a { print(x) }
来源：http://dali.hnqzz.top/Article/details/gtfyhsgpmf.html

[T22] Swift：字典
来源：http://dali.ybcxt.top/Article/details/gtyikwsyly.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.tanke756.top/Article/details/gtpusmysdb.html

[T23] Swift：函数
来源：http://dali.daxiang520.top/Article/details/gtuqtoqkak.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhoulong.xyz/Article/details/gtdqbzyeoo.html

[T24] Swift：闭包
来源：http://dali.haohaochexian.top/Article/details/gtnxeoyziv.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.havefunace.top/Article/details/gtaxsteocs.html

[T25] Swift：结构体
来源：http://dali.jqgufenzy.top/Article/details/gtfxcxfpbw.html

struct P { var x: Int }
来源：http://dali.fengsongda.top/Article/details/gtzncxeosk.html

[T26] Swift：类与重写
来源：http://dali.dashuyun.cn/Article/details/gtuefzvuwh.html

class A: Base { override func f() {} }
来源：http://dali.jqgufenzy.top/Article/details/gtyoecuxts.html

[T27] Swift：错误处理
来源：http://dali.cqqwz.cn/Article/details/gtwunehiic.html

do { try f() } catch { print(error) }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjzrtkfbw.html

[T28] Swift：枚举
来源：http://dali.shzxlz.cn/Article/details/gtummrdltx.html

enum Color { case red, green }
来源：http://dali.zdqjudy.top/Article/details/gtiyiqldzw.html

[T29] Swift：guard 提前返回
来源：http://dali.aizwys.cn/Article/details/gtodbqxdao.html

guard let x = opt else { return }
来源：http://dali.nanxinkj.top/Article/details/gtpcrlixuh.html

[T30] Swift：协议
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgwkoukjj.html

protocol Shape { func area() -> Double }
来源：http://dali.andypj.xyz/Article/details/gtqfudpylu.html

[T31] Lua：Hello World
来源：http://dali.iojbl.cn/Article/details/gttyskrldu.html

print("Hello")
来源：http://dali.tian-w.cn/Article/details/gtxqcvdqew.html

[T32] Lua：局部变量
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdbcpzpcu.html

local a = 1
来源：http://dali.iojbl.cn/Article/details/gtwlxtlxms.html

[T33] Lua：表（数组）
来源：http://dali.jyoumei.cn/Article/details/gthnawehbw.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.shanyushiyangtech.top/Article/details/gtwaothlib.html

[T34] Lua：遍历表
来源：http://dali.xuetiantiany.cn/Article/details/gtbjcaznni.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.ivvv.top/Article/details/gtomfhmkeu.html

[T35] Lua：字典表
来源：http://dali.pycfn.com/Article/details/gtwwjtyoxe.html

local d = { a = 1 };  d.b = 2
来源：http://dali.svipenyu.cn/Article/details/gtmnqkytkh.html

[T36] Lua：函数
来源：http://dali.0kj1m.cn/Article/details/gtxwjaikff.html

function add(a, b) return a + b end
来源：http://dali.aizwys.cn/Article/details/gtcemriald.html

[T37] Lua：字符串拼接
来源：http://dali.yueranfly.top/Article/details/gtpeevqwsy.html

"a" .. "b"
来源：http://dali.jinqigfzy.top/Article/details/gtzojbjuwl.html

[T38] Lua：条件
来源：http://dali.sufxvd.cn/Article/details/gthlrbhukg.html

if x > 0 then print("正") end
来源：http://dali.aizwys.cn/Article/details/gtdvbqehmd.html

[T39] Lua：模式匹配
来源：http://dali.wangdashe.top/Article/details/gtswsuuthf.html

string.find(s, "%d+")
来源：http://dali.9152youxi.cn/Article/details/gtfmnsijpr.html

[T40] Lua：元表
来源：http://dali.bjfxy.top/Article/details/gthholhmmw.html

setmetatable({}, { __index = base })
来源：http://dali.shuidangran.top/Article/details/gtdlresgxw.html

[T41] Perl：Hello World
来源：http://dali.jinghuilouyu.cn/Article/details/gtolyiwobc.html

print "Hello\n";
来源：http://dali.ivvv.top/Article/details/gtidbdbjvu.html

[T42] Perl：变量类型
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxnzvpfwu.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.quarkkingdee.top/Article/details/gtsbmkmnhf.html

[T43] Perl：字符串插值
来源：http://dali.cucudq.cn/Article/details/gtllsdyovb.html

"值: $a"
来源：http://dali.jinqigfzy.top/Article/details/gtmtfjsbce.html

[T44] Perl：条件
来源：http://dali.xziqi.cn/Article/details/gtffffxkyv.html

if ($a > 0) { print "正"; }
来源：http://dali.jyoumei.cn/Article/details/gtjrkiyqth.html

[T45] Perl：数组遍历
来源：http://dali.zhixingplan.top/Article/details/gtvopujkwh.html

for my $x (@arr) { print $x; }
来源：http://dali.zhoulong.xyz/Article/details/gtpfxbtllp.html

[T46] Perl：哈希操作
来源：http://dali.gotoacloud.top/Article/details/gtdedxdkfk.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zycfv.cn/Article/details/gtbyepqmwc.html

[T47] Perl：正则捕获
来源：http://dali.0kj1m.cn/Article/details/gtpqpgjpyo.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.yj20258888.top/Article/details/gtibbpcppp.html

[T48] Perl：正则替换
来源：http://dali.zhixingplan.top/Article/details/gtafborwlb.html

$s =~ s/old/new/g;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfnghmcpe.html

[T49] Perl：函数
来源：http://dali.svipenyu.cn/Article/details/gtgdtlzlvi.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtihrznlmv.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gtjrinadao.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtufuuwmpy.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.nanxinkj.top/Article/details/gtewelapcp.html

[T51] Scala：Hello World
来源：http://dali.hongshengwenyu.top/Article/details/gtowevkqby.html

println("Hello")
来源：http://dali.jinyuanbaomall.cn/Article/details/gthmjbbqzx.html

[T52] Scala：变量
来源：http://dali.mhx1999.top/Article/details/gtgknhmtdu.html

val a = 1;  var b = 2
来源：http://dali.ybcxt.top/Article/details/gtekyestwi.html

[T53] Scala：字符串插值
来源：http://dali.tianlin.xyz/Article/details/gtbctpqtcc.html

s"值: $b"
来源：http://dali.jiagoushi.top/Article/details/gtlcdkqvls.html

[T54] Scala：集合映射
来源：http://dali.yuxming.cn/Article/details/gtypudckrp.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.gogol.net.cn/Article/details/gtztscsiwc.html

[T55] Scala：集合过滤
来源：http://dali.xziqi.cn/Article/details/gtodhpuiir.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.birdmap.top/Article/details/gtabzwdjpo.html

[T56] Scala：样例类
来源：http://dali.gogol.net.cn/Article/details/gtmmoiedrs.html

case class User(name: String, age: Int)
来源：http://dali.yuanzhike.top/Article/details/gtkpwnmjmr.html

[T57] Scala：模式匹配
来源：http://dali.ivvv.top/Article/details/gtbsqmmwvb.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.redwolf501.top/Article/details/gthhsltetd.html

[T58] Scala：函数定义
来源：http://dali.pycfn.com/Article/details/gtucrtlntn.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.ivvv.top/Article/details/gtqndestlf.html

[T59] Scala：循环
来源：http://dali.havefunace.top/Article/details/gtiwurikal.html

for (i <- 1 to 10) println(i)
来源：http://dali.chenjidiqi.icu/Article/details/gtfxelnprc.html

[T60] Scala：折叠
来源：http://dali.cashguo.top/Article/details/gthoavzbcw.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.c1oappe.top/Article/details/gtyfucsqwe.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtliardhzp.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.daria6918.cn/Article/details/gtdribpqve.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gttjyaczzo.html

[U01] Py：创建虚拟环境
来源：http://dali.yj20258888.top/Article/details/gtnzjpogow.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.hammf.cn/Article/details/gtvcisfuba.html

[U02] Py：导出 / 安装依赖
来源：http://dali.iojbl.cn/Article/details/gtytantuoo.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.ivvv.top/Article/details/gtdquzgzml.html

[U03] Py：加载 .env 配置
来源：http://dali.ydzc1.top/Article/details/gtlymqtmrd.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoyhgmmub.html

[U04] Py：变量调试打印
来源：http://dali.cucudq.cn/Article/details/gtlglftgef.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.ppjwa.cn/Article/details/gtlqhfdcnv.html

[U05] Py：列表去重且保序
来源：http://dali.gaohongyu789.top/Article/details/gtdsytszpo.html

list(dict.fromkeys(arr))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtblgmadoy.html

[U06] Py：合并两个字典
来源：http://dali.chenlongwang.top/Article/details/gtcjasnwcp.html

{**a, **b}
来源：http://dali.jiagoushi.top/Article/details/gtsxegebyu.html

[U07] Py：反转字典键值
来源：http://dali.ybcxt.top/Article/details/gtxsrimeag.html

{v: k for k, v in d.items()}
来源：http://dali.daxiang520.top/Article/details/gtupkbjeum.html

[U08] Py：展平二维列表
来源：http://dali.xylfe.cn/Article/details/gtdufvqcrm.html

[y for x in nested for y in x]
来源：http://dali.wangdashe.top/Article/details/gtoxzkrtha.html


<!-- 参考信息 -->