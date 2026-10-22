代发 wailian999

split -l 1000 big.log part_
来源：http://dali.tianlin.xyz/Article/details/gt2onipzaal.html

[R74] 批量重命名
来源：http://dali.jqgufenzy.top/Article/details/gt2zknaizha.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.gotoacloud.top/Article/details/gt2aihtiiza.html

[R75] 导出环境变量
来源：http://dali.tianlin.xyz/Article/details/gt2cobjpoue.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.sweek.top/Article/details/gt2pewjayqc.html

[R76] 使用临时文件
来源：http://dali.ybcxt.top/Article/details/gt2pioacxyf.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.xinyue.icu/Article/details/gt2gaypajwu.html

[R77] 读取用户输入
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jnlwlhkp.html

read -rp "请输入: " ans
来源：http://dali.smart0.xyz/Article/details/gt2aotfbdkl.html

[R78] 交互式菜单
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ctfjxfiw.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2esotlyci.html

[R79] 解析命令行选项
来源：http://dali.aizwys.cn/Article/details/gt2jistkiay.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhiwuduotai.top/Article/details/gt2zjxmqnnv.html

[R80] 查看脚本执行耗时
来源：http://dali.chenlongwang.top/Article/details/gt2ryagrfby.html

time ./run.sh
来源：http://dali.kuanghao11.cn/Article/details/gt2rnlhzvhg.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2qvywdnvz.html

S. C / C++ 专题
来源：http://dali.meibo888.top/Article/details/gt2drboquvm.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2twvoqjnw.html

[S01] C：Hello World
来源：http://dali.ybcxt.top/Article/details/gt2gmwfqilj.html

#include <stdio.h>
来源：http://dali.shuidangran.top/Article/details/gt2bpwkrmec.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.tianlin.xyz/Article/details/gt2sjhjmwsy.html

[S02] C：变量与格式化输出
来源：http://dali.sxryk.cn/Article/details/gt2ognlfphk.html

int a = 10; printf("%d\n", a);
来源：http://dali.nanxuanxn.top/Article/details/gt2ddyjgdbi.html

[S03] C：读入整数
来源：http://dali.redwolf501.top/Article/details/gt2uwzsfmxe.html

int x; scanf("%d", &x);
来源：http://dali.havefunace.top/Article/details/gt2xrghhcuv.html

[S04] C：字符串复制
来源：http://dali.snrcjt.cn/Article/details/gt2yarnlqvy.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.yangfankeji.com/Article/details/gt2ousydawi.html

[S05] C：字符串长度
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tasedqtj.html

strlen(s)
来源：http://dali.sufxvd.cn/Article/details/gt2rgldfxef.html

[S06] C：字符串比较
来源：http://dali.hfpthk.cn/Article/details/gt2vhuzthrg.html

strcmp(a, b) == 0
来源：http://dali.cashguo.top/Article/details/gt2onqqaxho.html

[S07] C：数组遍历求和
来源：http://dali.daxiang520.top/Article/details/gt2bvckoapm.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.yj202588.top/Article/details/gt2pafcxeti.html

[S08] C：动态内存分配与释放
来源：http://dali.snrcjt.cn/Article/details/gt2pxlntlij.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.dianchejie.cn/Article/details/gt2jkoshyus.html

[S09] C：结构体定义与初始化
来源：http://dali.pycfn.com/Article/details/gt2osxlwmsm.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.xziqi.cn/Article/details/gt2hyqeloop.html

[S10] C：指针与解引用
来源：http://dali.zhongyouzk.top/Article/details/gt2kwptrjyy.html

int *p = &a;  *p = 5;
来源：http://dali.yongpay.top/Article/details/gt2atbqaktn.html

[S11] C：逐行读文件
来源：http://dali.birdmap.top/Article/details/gt2exufqekp.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.jinqigfzy.top/Article/details/gt2qfzqtadd.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.iojbl.cn/Article/details/gt2kpbgcfyv.html

fclose(f);
来源：http://dali.yuxming.cn/Article/details/gt2aubymqrg.html

[S12] C：写文件
来源：http://dali.hongshengwenyu.top/Article/details/gt2tjssgbpx.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.svipenyu.cn/Article/details/gt2opptagzk.html

[S13] C：宏定义
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sxedsnzh.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.gogol.net.cn/Article/details/gt2fasjevuq.html

[S14] C：枚举
来源：http://dali.316326.xyz/Article/details/gt2fylzsjtj.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.xuetiantiany.cn/Article/details/gt2zrxsidgq.html

[S15] C：类型转换
来源：http://dali.quarkkingdee.top/Article/details/gt2vqoucsuj.html

(double) a / b
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hfxrufrk.html

[S16] C：位操作置位
来源：http://dali.gotoacloud.top/Article/details/gt2gzfgemag.html

x |= (1 << 3);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qphbfuli.html

[S17] C：安全拼接字符串
来源：http://dali.mhx1999.top/Article/details/gt2srvjhyhs.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.fengsongda.top/Article/details/gt2nbmqhaed.html

[S18] C：命令行参数
来源：http://dali.daxiang520.top/Article/details/gt2jhknzdhl.html

int main(int argc, char **argv)
来源：http://dali.vqdsnc.cn/Article/details/gt2dkraftrw.html

[S19] C：快速排序
来源：http://dali.ybcxt.top/Article/details/gt2qfcpvpan.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.daxiang520.top/Article/details/gt2ynnxzref.html

[S20] C：二分查找
来源：http://dali.chenjidiqi.icu/Article/details/gt2qhljmsuo.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhixingplan.top/Article/details/gt2ddiqfksp.html

[S21] C：字符类别判断
来源：http://dali.ivvv.top/Article/details/gt2udzeukuf.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.tianlin.xyz/Article/details/gt2cqydaysp.html

[S22] C：字符串转数字
来源：http://dali.nanxuanxn.top/Article/details/gt2lpmiatyu.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.sufxvd.cn/Article/details/gt2jpmwjwwo.html

[S23] C：随机数
来源：http://dali.ybcxt.top/Article/details/gt2vhiuuthj.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.mhx1999.top/Article/details/gt2eptreikm.html

[S24] C：获取本地时间
来源：http://dali.gaohongyu789.top/Article/details/gt2iligzmam.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.birdmap.top/Article/details/gt2dpqnzpms.html

[S25] C：内存拷贝
来源：http://dali.andypj.xyz/Article/details/gt2vphzmzrx.html

memcpy(dst, src, n);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ylgkwwgk.html

[S26] C：内存清零
来源：http://dali.sysykeji.top/Article/details/gt2hxqpiwyl.html

memset(a, 0, sizeof a);
来源：http://dali.xuetiantiany.cn/Article/details/gt2zkjxpzhv.html

[S27] C：定义常量
来源：http://dali.zdqjudy.top/Article/details/gt2vwdawbvf.html

const double PI = 3.14159;
来源：http://dali.yongpay.top/Article/details/gt2ccmojwrz.html

[S28] C：静态变量
来源：http://dali.zhengqikj.top/Article/details/gt2amshqusg.html

static int counter = 0;
来源：http://dali.chenzaomai.com/Article/details/gt2jpbspior.html

[S29] C：变参函数
来源：http://dali.tianlin.xyz/Article/details/gt2zvcmpvgy.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.0kj1m.cn/Article/details/gt2labthbwn.html

[S30] C：头文件保护
来源：http://dali.wangshuangyany.cn/Article/details/gt2xsmedaxz.html

#ifndef X_H
来源：http://dali.ybcxt.top/Article/details/gt2evsnbgjh.html

#define X_H
来源：http://dali.nanxuanxn.top/Article/details/gt2fgkejwnt.html

#endif
来源：http://dali.zdqjudy.top/Article/details/gt2lbicishq.html

[S31] C++：Hello World
来源：http://dali.jianghu66.top/Article/details/gt2lcvqasge.html

#include <iostream>
来源：http://dali.birdmap.top/Article/details/gt2zpgslyms.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.sweek.top/Article/details/gt2cmlwlewc.html

[S32] C++：字符串
来源：http://dali.jyoumei.cn/Article/details/gt2hcaekdyv.html

std::string s = "hi";  s += "!";
来源：http://dali.jlsjyb.cn/Article/details/gt2zjzzxbnz.html

[S33] C++：vector 增删
来源：http://dali.wangshuangyany.cn/Article/details/gt2hljorvad.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.gogol.net.cn/Article/details/gt2epoechio.html

[S34] C++：遍历 vector
来源：http://dali.xylfe.cn/Article/details/gt2wpxfvnyt.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.gogol.net.cn/Article/details/gt2iilgygot.html

[S35] C++：map
来源：http://dali.andypj.xyz/Article/details/gt2bberarvq.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.chenlongwang.top/Article/details/gt2jmfmemen.html

[S36] C++：unordered_map
来源：http://dali.nanxuanxn.top/Article/details/gt2yogueiym.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jqgfzy.top/Article/details/gt2dniznkfp.html

[S37] C++：set
来源：http://dali.zhixingplan.top/Article/details/gt2pbyfyzdg.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.cdnleiting.top/Article/details/gt2fnebsylv.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2tlijledj.html

std::sort(v.begin(), v.end());
来源：http://dali.0kj1m.cn/Article/details/gt2hsauvcyy.html

[S39] C++：自定义比较器排序
来源：http://dali.yanxiufei.cn/Article/details/gt2puyrmptz.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.yueranfly.top/Article/details/gt2cxzfphwu.html

[S40] C++：查找元素
来源：http://dali.zycfv.cn/Article/details/gt2arhkhcez.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.shuidangran.top/Article/details/gt2ihiwvyju.html

[S41] C++：类与构造函数
来源：http://dali.yangfankeji.com/Article/details/gt2lfuziggj.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.svipenyu.cn/Article/details/gt2kornuarv.html

[S42] C++：继承与虚函数
来源：http://dali.daria6918.cn/Article/details/gt2xuisekos.html

class B : public Base { public: void f() override {} };
来源：http://dali.snrcjt.cn/Article/details/gt2jeykxhdx.html

[S43] C++：智能指针
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2etihwviq.html

auto p = std::make_unique<int>(5);
来源：http://dali.smart0.xyz/Article/details/gt2ilibbdqb.html

[S44] C++：引用传参
来源：http://dali.guowangkeji.top/Article/details/gt2jjzgyqdh.html

void inc(int &x) { ++x; }
来源：http://dali.mhx1999.top/Article/details/gt2bmwtjudg.html

[S45] C++：lambda
来源：http://dali.ehwqpu.com/Article/details/gt2jmfkpege.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.nanxinkj.top/Article/details/gt2fwrhrxfd.html

[S46] C++：函数模板
来源：http://dali.gaohongyu789.top/Article/details/gt2bhmdbtvq.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.jinqigfzy.top/Article/details/gt2zoukkngd.html

[S47] C++：结构化绑定遍历
来源：http://dali.nanxinkj.top/Article/details/gt2abierwqn.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2doludouq.html

[S48] C++：逐行读文件
来源：http://dali.andypj.xyz/Article/details/gt2rezesbgy.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhongyouzk.top/Article/details/gt2eymrasdc.html

while (std::getline(in, line)) { }
来源：http://dali.gaohongyu789.top/Article/details/gt2aeuvltcl.html

[S49] C++：写文件
来源：http://dali.jqgufenzy.top/Article/details/gt2chhxufef.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.quarkkingdee.top/Article/details/gt2hhztarpk.html

[S50] C++：格式化数字
来源：http://dali.cashguo.top/Article/details/gt2jkwnxcni.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.xziqi.cn/Article/details/gt2yjwzotnh.html

[S51] C++：显式类型转换
来源：http://dali.zhixingplan.top/Article/details/gt2umvokwhf.html

static_cast<double>(a) / b
来源：http://dali.cdnleiting.top/Article/details/gt2gurqxpth.html

[S52] C++：const 与 noexcept
来源：http://dali.yonumen.top/Article/details/gt2zivcglip.html

int size() const noexcept { return n_; }
来源：http://dali.tanke756.top/Article/details/gt2pnujkawv.html

[S53] C++：移动语义
来源：http://dali.bjfxy.top/Article/details/gt2kwmlmyyt.html

std::vector<int> w = std::move(v);
来源：http://dali.tanke756.top/Article/details/gt2ugzfxylg.html

[S54] C++：异常处理
来源：http://dali.nanxinkj.top/Article/details/gt2ggxjbsho.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.sysykeji.top/Article/details/gt2mubtiwhh.html

[S55] C++：结构化绑定
来源：http://dali.sweek.top/Article/details/gt2jpnjvete.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.smart0.xyz/Article/details/gt2fxdcobsb.html

[S56] C++：optional
来源：http://dali.shangyingyoupin.top/Article/details/gt2cjeibnht.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.jinqigufen.top/Article/details/gt2dxpiyyun.html

[S57] C++：编译期常量
来源：http://dali.yangfankeji.com/Article/details/gt2lwwqrxxf.html

constexpr int N = 10;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qbkvrswu.html

[S58] C++：命名空间
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xqqmxquf.html

namespace ns { int f() { return 1; } }
来源：http://dali.hongshengwenyu.top/Article/details/gt2sajqvofl.html

[S59] C++：静态断言
来源：http://dali.chenlongwang.top/Article/details/gt2vfodiado.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.quarkkingdee.top/Article/details/gt2frisyfug.html

[S60] C++：遍历并删除元素
来源：http://dali.andypj.xyz/Article/details/gt2qvyzrujs.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.hnxiangtu.top/Article/details/gt2tgkxzuvz.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2gaktydhy.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.havefunace.top/Article/details/gt2ezkjhnqd.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2uiipoefa.html

[T01] Kotlin：Hello World
来源：http://dali.hnxiangtu.top/Article/details/gt2mfnrdrqb.html

println("Hello")
来源：http://dali.chenlongwang.top/Article/details/gt2drjchbqs.html

[T02] Kotlin：变量
来源：http://dali.meibo888.top/Article/details/gt2podjmwhd.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.c1oappe.top/Article/details/gt2ixucsodd.html

[T03] Kotlin：字符串模板
来源：http://dali.daxiang520.top/Article/details/gt2zzdpauil.html

"值: $b"
来源：http://dali.hammf.cn/Article/details/gt2goquqszy.html

[T04] Kotlin：空安全
来源：http://dali.xylfe.cn/Article/details/gt2xarwxzvq.html

val n: String? = null;  n?.length
来源：http://dali.sweek.top/Article/details/gt2dqtxkmyz.html

[T05] Kotlin：when 表达式
来源：http://dali.hywenlv.cn/Article/details/gt2zfeletmp.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wpdyuxbc.html

[T06] Kotlin：集合映射
来源：http://dali.c1oappe.top/Article/details/gt2vieuodpb.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.cashguo.top/Article/details/gt2yrgrqsfy.html

[T07] Kotlin：集合过滤
来源：http://dali.9152youxi.cn/Article/details/gt2qhdahbnp.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.pycfn.com/Article/details/gt2uakyjbqt.html

[T08] Kotlin：数据类
来源：http://dali.dianchejie.cn/Article/details/gt2cioomeow.html

data class User(val name: String, val age: Int)
来源：http://dali.cucudq.cn/Article/details/gt2vkekibra.html

[T09] Kotlin：扩展函数
来源：http://dali.shangyingyoupin.top/Article/details/gt2gmvsjeso.html

fun String.exclaim() = this + "!"
来源：http://dali.mhx1999.top/Article/details/gt2hdpllvid.html

[T10] Kotlin：默认参数
来源：http://dali.gogol.net.cn/Article/details/gt2tuenvhnw.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.quarkkingdee.top/Article/details/gt2urbakyuf.html

[T11] Kotlin：协程
来源：http://dali.sufxvd.cn/Article/details/gt2rrtypnjw.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wpmyqpmk.html

[T12] Kotlin：解构声明
来源：http://dali.hongshengwenyu.top/Article/details/gt2ykhzflxt.html

val (a, b) = Pair(1, 2)
来源：http://dali.tianlin.xyz/Article/details/gt2gywnswnj.html

[T13] Kotlin：只读 Map
来源：http://dali.bjfxy.top/Article/details/gt2hhmhhwos.html

val m = mapOf("a" to 1)
来源：http://dali.hywenlv.cn/Article/details/gt2vjnxbmbi.html

[T14] Kotlin：循环
来源：http://dali.yuanzhike.top/Article/details/gt2rqwfkhow.html

for (i in 1..10) println(i)
来源：http://dali.ehwqpu.com/Article/details/gt2yhtrdnki.html

[T15] Kotlin：接口
来源：http://dali.jinqigfzy.top/Article/details/gt2zvbfjbng.html

interface Shape { fun area(): Double }
来源：http://dali.hywenlv.cn/Article/details/gt2dtgqzdkl.html

[T16] Swift：Hello World
来源：http://dali.ppjwa.cn/Article/details/gt2yvnwdjus.html

print("Hello")
来源：http://dali.zycfv.cn/Article/details/gt2xakvbjzc.html

[T17] Swift：变量与常量
来源：http://dali.hysaishi.cn/Article/details/gt2sgsstzdr.html

var a = 1;  let b = 2
来源：http://dali.snrcjt.cn/Article/details/gt2mlmhlzzr.html

[T18] Swift：字符串插值
来源：http://dali.bjfxy.top/Article/details/gt2keerzfla.html

"值: \(b)"
来源：http://dali.redwolf501.top/Article/details/gt2ylkyqvlw.html

[T19] Swift：可选绑定
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qqwbnnfy.html

if let n = opt { print(n) }
来源：http://dali.tanke756.top/Article/details/gt2tvuonpqc.html

[T20] Swift：数组操作
来源：http://dali.yonumen.top/Article/details/gt2upmhhabp.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.feifeiyinyue.top/Article/details/gt2jsipgtwn.html

[T21] Swift：遍历
来源：http://dali.ivvv.top/Article/details/gt2ahdghcww.html

for x in a { print(x) }
来源：http://dali.ppjwa.cn/Article/details/gt2jqrvbfwi.html

[T22] Swift：字典
来源：http://dali.pycfn.com/Article/details/gt2oprmyvnd.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.xziqi.cn/Article/details/gt2idbqbsrn.html

[T23] Swift：函数
来源：http://dali.ivvv.top/Article/details/gt2zcntkyoq.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.snrcjt.cn/Article/details/gt2wmsvwxiz.html

[T24] Swift：闭包
来源：http://dali.jyoumei.cn/Article/details/gt2bpvbbfut.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.guowangkeji.top/Article/details/gt2tidclkms.html

[T25] Swift：结构体
来源：http://dali.fengsongda.top/Article/details/gt2edugqfkr.html

struct P { var x: Int }
来源：http://dali.jinqigfzy.top/Article/details/gt2hplbbjjh.html

[T26] Swift：类与重写
来源：http://dali.ivvv.top/Article/details/gt2yuetvmoc.html

class A: Base { override func f() {} }
来源：http://dali.mhx1999.top/Article/details/gt2zgefwdee.html

[T27] Swift：错误处理
来源：http://dali.hnqzz.top/Article/details/gt2xciyilvq.html

do { try f() } catch { print(error) }
来源：http://dali.yueranfly.top/Article/details/gt2rzdkomia.html

[T28] Swift：枚举
来源：http://dali.jlsjyb.cn/Article/details/gt2fkpsgcmm.html

enum Color { case red, green }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2thbhrjio.html

[T29] Swift：guard 提前返回
来源：http://dali.hywenlv.cn/Article/details/gt2jysqzqbd.html

guard let x = opt else { return }
来源：http://dali.quarkkingdee.top/Article/details/gt2eceglmoh.html

[T30] Swift：协议
来源：http://dali.sufxvd.cn/Article/details/gt2xvcnoshq.html

protocol Shape { func area() -> Double }
来源：http://dali.chenzaomai.com/Article/details/gt2aofwzuyd.html

[T31] Lua：Hello World
来源：http://dali.shuidangran.top/Article/details/gt2jrzdrhon.html

print("Hello")
来源：http://dali.jqgufenzy.top/Article/details/gt2kgfzbhkb.html

[T32] Lua：局部变量
来源：http://dali.dashuyun.cn/Article/details/gt2xkmywtcs.html

local a = 1
来源：http://dali.ppjwa.cn/Article/details/gt2kmukyjyz.html

[T33] Lua：表（数组）
来源：http://dali.chenlongwang.top/Article/details/gt2vrrospoi.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.jinqigufen.top/Article/details/gt2ygqluesg.html

[T34] Lua：遍历表
来源：http://dali.xuetiantiany.cn/Article/details/gt2vpbpszsy.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zycfv.cn/Article/details/gt2vmndafwf.html

[T35] Lua：字典表
来源：http://dali.dianchejie.cn/Article/details/gt2zpfxargd.html

local d = { a = 1 };  d.b = 2
来源：http://dali.jiagoushi.top/Article/details/gt2worjmzvc.html

[T36] Lua：函数
来源：http://dali.hnqzz.top/Article/details/gt2xjtcauol.html

function add(a, b) return a + b end
来源：http://dali.redwolf501.top/Article/details/gt2kcoijiix.html

[T37] Lua：字符串拼接
来源：http://dali.hammf.cn/Article/details/gt2cvfqxsax.html

"a" .. "b"
来源：http://dali.fengsongda.top/Article/details/gt2nhpxorwh.html

[T38] Lua：条件
来源：http://dali.aizwys.cn/Article/details/gt2emgtyxlq.html

if x > 0 then print("正") end
来源：http://dali.ehwqpu.com/Article/details/gt2vrbmzxkr.html

[T39] Lua：模式匹配
来源：http://dali.jqgfzy.top/Article/details/gt2ithbyjex.html

string.find(s, "%d+")
来源：http://dali.meibo888.top/Article/details/gt2uaaiobij.html

[T40] Lua：元表
来源：http://dali.pengpengdd.cyou/Article/details/gt2rtnqjuyo.html

setmetatable({}, { __index = base })
来源：http://dali.daria6918.cn/Article/details/gt2ojvgvemh.html

[T41] Perl：Hello World
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jrugotrn.html

print "Hello\n";
来源：http://dali.yonumen.top/Article/details/gt2zmtimhne.html

[T42] Perl：变量类型
来源：http://dali.chenlongwang.top/Article/details/gt2pgudvnkr.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhoulong.xyz/Article/details/gt2icwtauer.html

[T43] Perl：字符串插值
来源：http://dali.sweek.top/Article/details/gt2arsjvluv.html

"值: $a"
来源：http://dali.shangyingyoupin.top/Article/details/gt2bmuuiklu.html

[T44] Perl：条件
来源：http://dali.tian-w.cn/Article/details/gt2mykjcdbb.html

if ($a > 0) { print "正"; }
来源：http://dali.ybcxt.top/Article/details/gt2hxflsbdk.html

[T45] Perl：数组遍历
来源：http://dali.hnxiangtu.top/Article/details/gt2hpltpnsz.html

for my $x (@arr) { print $x; }
来源：http://dali.bjfxy.top/Article/details/gt2vkxyrmzb.html

[T46] Perl：哈希操作
来源：http://dali.nwbrower.top/Article/details/gt2wvfgbprv.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.jqgfzy.top/Article/details/gt2ullpdibo.html

[T47] Perl：正则捕获
来源：http://dali.jianghu66.top/Article/details/gt2lhazlyoe.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.smart0.xyz/Article/details/gt2eibocgek.html

[T48] Perl：正则替换
来源：http://dali.hysaishi.cn/Article/details/gt2bjzefsxk.html

$s =~ s/old/new/g;
来源：http://dali.yanxiufei.cn/Article/details/gt2jdjqkgfw.html

[T49] Perl：函数
来源：http://dali.gogol.net.cn/Article/details/gt2ekbwrzmh.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.yuxming.cn/Article/details/gt2mfihwvfb.html

[T50] Perl：逐行读文件
来源：http://dali.0kj1m.cn/Article/details/gt2xanxtzvz.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.shuidangran.top/Article/details/gt2ddkrqrad.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.bjfxy.top/Article/details/gt2pnogkyhc.html

[T51] Scala：Hello World
来源：http://dali.wangdashe.top/Article/details/gt2cpwguvsu.html

println("Hello")
来源：http://dali.ivvv.top/Article/details/gt2hmnlmgfd.html

[T52] Scala：变量
来源：http://dali.fzhhl.top/Article/details/gt2alhbtnul.html

val a = 1;  var b = 2
来源：http://dali.wangshuangyany.cn/Article/details/gt2qbozoluh.html

[T53] Scala：字符串插值
来源：http://dali.yj202588.top/Article/details/gt2moangcau.html

s"值: $b"
来源：http://dali.hnqzz.top/Article/details/gt2bnfbhlad.html

[T54] Scala：集合映射
来源：http://dali.wangshuangyany.cn/Article/details/gt2ytvuyikq.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.yvedp.cn/Article/details/gt2txoohfbo.html

[T55] Scala：集合过滤
来源：http://dali.jqgufenzy.top/Article/details/gt2eumxjykv.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.daxiang520.top/Article/details/gt2ulunpyek.html

[T56] Scala：样例类
来源：http://dali.zhixingplan.top/Article/details/gt2fyopxmen.html

case class User(name: String, age: Int)
来源：http://dali.jlsjyb.cn/Article/details/gt2fbsqghgf.html

[T57] Scala：模式匹配
来源：http://dali.ydzc1.top/Article/details/gt2qzpsjdju.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.xinyue.icu/Article/details/gt2kycyrxqi.html

[T58] Scala：函数定义
来源：http://dali.mhx1999.top/Article/details/gt2ovkrsgqd.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.daxiang520.top/Article/details/gt2wqactmij.html

[T59] Scala：循环
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qxluxnnj.html

for (i <- 1 to 10) println(i)
来源：http://dali.jiagoushi.top/Article/details/gt2kpfbwfkj.html

[T60] Scala：折叠
来源：http://dali.nanxuanxn.top/Article/details/gt2eqvsyzvp.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.yuxming.cn/Article/details/gt2gwvrubvr.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gt2yrxctwfp.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.birdmap.top/Article/details/gt2putetpgh.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2wztuxazl.html

[U01] Py：创建虚拟环境
来源：http://dali.dianchejie.cn/Article/details/gt2yvntpcxk.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.guowangkeji.top/Article/details/gt2vvhojism.html

[U02] Py：导出 / 安装依赖
来源：http://dali.gotoacloud.top/Article/details/gt2vopociba.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhiwuduotai.top/Article/details/gt2qmluifdg.html

[U03] Py：加载 .env 配置
来源：http://dali.sweek.top/Article/details/gt2yaptfinx.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.xziqi.cn/Article/details/gt2nyqppfxu.html

[U04] Py：变量调试打印
来源：http://dali.vqdsnc.cn/Article/details/gt2vzhnolav.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qdpcmeib.html

[U05] Py：列表去重且保序
来源：http://dali.chenzaomai.com/Article/details/gt2xswhabor.html

list(dict.fromkeys(arr))
来源：http://dali.xuanzx.com/Article/details/gt2vxuqqwwi.html

[U06] Py：合并两个字典
来源：http://dali.gzhubu.top/Article/details/gt2yuptcvot.html

{**a, **b}
来源：http://dali.sysykeji.top/Article/details/gt2ogmlpvsa.html

[U07] Py：反转字典键值
来源：http://dali.aizwys.cn/Article/details/gt2cewtddfy.html

{v: k for k, v in d.items()}
来源：http://dali.xuetiantiany.cn/Article/details/gt2hmnifcwk.html

[U08] Py：展平二维列表
来源：http://dali.vqdsnc.cn/Article/details/gt2pxalfvkt.html

[y for x in nested for y in x]
来源：http://dali.yueranfly.top/Article/details/gt2qopzqthp.html

[U09] Py：字典取最大值的键
来源：http://dali.yj20258.top/Article/details/gt2nkzufdta.html

max(d, key=d.get)
来源：http://dali.ppjwa.cn/Article/details/gt2eqyatvzk.html

[U10] Py：按值排序字典
来源：http://dali.xuanzx.com/Article/details/gt2etpqyjbk.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.quarkkingdee.top/Article/details/gt2fqjdijpu.html

[U11] Py：生成器表达式
来源：http://dali.haohaochexian.top/Article/details/gt2qpsrzqjz.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2aoomhlpl.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.ivvv.top/Article/details/gt2fwhonzzh.html

Counter(arr).most_common(3)
来源：http://dali.xuetiantiany.cn/Article/details/gt2ocmlhvea.html

[U13] Py：固定长度队列
来源：http://dali.dashuyun.cn/Article/details/gt2nnhvcpto.html

deque(maxlen=10)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zxulkhmn.html

[U14] Py：分组收集到列表
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rrkswopt.html

defaultdict(list)
来源：http://dali.redwolf501.top/Article/details/gt2ligfzjlr.html


<!-- 参考信息 -->