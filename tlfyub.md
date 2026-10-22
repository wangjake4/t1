代发 wailian999

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2rwdytqiw.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2flzwimpj.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2fpfzrbcn.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2nmwutddq.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2llgsohvy.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2ynmjdrkt.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2ttgksuij.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2jdmsmzgw.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2gqihpiun.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2nzzrehij.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2hjsmjjbd.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2nsyamney.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2saidfwyj.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2tmymqefv.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2lkvrwhnf.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2dkkmugyz.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2crkelvxr.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2zzxbasyq.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2atytbyzl.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2cxgmmtob.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2vnwtnfai.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2toihgacd.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ueqeqiot.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2syqtkgnx.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2gwmylumo.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2fdosobyy.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2sxlraztl.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jbrnogzc.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2lqwhylru.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ggfeaycr.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2qaszlmpx.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2zirhkntf.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2xfeuwmqm.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2uhpzmkxq.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ukizilgt.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2bftusgkd.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ibyhjima.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2pxzzxbqt.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2uhwzwjee.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2trugzagj.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2caharhns.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cjnibdmu.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2xbvvmpik.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2yezciphi.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qxplklbj.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2ckwceibc.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2bcmyfpod.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2puqejjil.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2kkpqqxxc.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2bbeyoyil.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2oafghcxo.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2kwszlqnk.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2muxkwdtf.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2yqqwfwvy.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2mmkxiqte.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2jqlftxwh.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2xcztkcwo.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2xjafcicj.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2esgvpxku.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2cppgtxzo.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2rcfvocdr.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2blqzpwxd.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2vlbubmpe.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2clyonfku.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2zawufpxw.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2weztwshs.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2hemmtozl.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2krpxcuxo.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2lqwmclyv.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2gvwslneo.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2ereqpsxg.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2auriulcx.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2inmdptmj.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2yyulnbhe.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2sdpxmiuo.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2ykxfibzq.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2apconmcg.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2pinjhqyc.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2qncvahdn.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2dddjzvws.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2wfxbbkmr.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2vklusnzv.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2udzuhvvu.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2mnyvjgho.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2peixuqkd.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2jpaupfdl.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2cotuejjs.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2bzduekpk.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2bpwumsdg.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2cfoiukqg.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2qdxxdjob.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2nuddhyme.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2iiloqyvo.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2jlqzgeje.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2xkwgdksq.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2aotuktro.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2vcbimtam.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2stvtxudg.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2vpqxykxu.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2drcdtsfm.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2jcvrwqfq.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mfamqqkf.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2cesbwnpw.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2bldjpbyq.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2lkqpihci.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2jspyenyt.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2wnuifsgr.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2fkgmmjxn.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2dlropzcv.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2twhlverk.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2jqypsqzb.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2uebmvlwg.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2kcdbppmq.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2trpyfegv.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2mqdvgdmj.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kdozowoq.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2udybjmhf.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2gdjzzsxg.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2hffxbwih.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wyprvueh.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2rfzptsad.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2hhbcemmr.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2tlfgibug.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2unjdmujb.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2plbiercy.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2qwsduvng.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2xgabhtfa.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2hjeapgja.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2iwyjbzjk.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2inryyzhp.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2uckyrcma.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2kcbmkids.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2axlcfbys.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2wjsaqfrq.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2qitjvflm.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2evxxpfqw.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2vkznddmq.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2zjxzgdri.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2yadqabbf.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zcxtipuw.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2pzmadltz.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zyhvpgxd.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ixyalseo.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2gxpowjof.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ybymdfru.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qperkjnn.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2bunuhgnm.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2srcrvvcl.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2lecrvpdu.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2alskeqvr.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2ngptcaso.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2ratkghao.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ebqmhnge.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2tfiwkkiy.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2pupgnefg.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2nwfqpxbs.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2dbtoodyd.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2wqsqezvj.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2csaecslm.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2fslhmzsq.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fxluknet.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2bslarzjs.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2nliipgrd.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2mqbxoqwp.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2knylgobm.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2taiaezdg.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2nwqbpcyb.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2jbsgbfba.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2pxylsjzi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2isbowgva.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2hwbuwyte.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pvupxpzw.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2zejfhbzx.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2toytpglg.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2depiqtwe.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2etdgmyfy.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2ejuwzccs.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2gpojumws.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2ubvmdasy.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2jrpphaox.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2wasjtxmq.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2cogxauwr.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2ncemwilf.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2nyjpqzoj.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2xvfogssj.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2yxhpjqtp.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2pgbbfwca.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2idlcqlxk.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xyfhguep.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2zjaxdkrk.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2emmtmtmp.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2oqfpfrev.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2wkzxdimn.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2pcveneip.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2fquccpfu.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2rizykhue.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2nnmvtyqm.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2bpsacoge.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2zlhbifrr.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2cwmjlmni.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2tzkmqcdv.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2sorlally.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ixnvrpug.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2rfrwqgsp.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2qyfemjvz.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2jhezrtwt.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2hppnnclq.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2redwrjft.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2dfvvzybx.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2vmyxafeh.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2itplktpd.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2tfldqmcl.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2klejujca.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2noiqccjl.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2cwnhsbnf.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2pjhatanw.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jquvxatx.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2zjkylzuy.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2krmbuaml.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2htkoitgo.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2qvpxqhtz.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2uwimovgu.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2fztattny.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2ftrvpbat.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2cxqerord.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2vkmawhpn.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2bxprfcwc.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2zbyoldvr.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2mxkkdsbg.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2fhjmolgf.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2iyxvccta.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2zwzsdepu.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2cmwwmyif.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2uttwegrd.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ippdpjph.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2dnmkwcoh.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2lwslbdch.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2tnhkwcbl.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2usbdzncq.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2ssjyknse.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2mxjmrrvz.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ljbxmgus.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fgxztxod.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2ryyfccaj.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2cvirmotn.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2tnlssjzu.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2vtsbcjpz.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2feholsbl.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2cgsxzugp.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2gialmfbc.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2wicpcalp.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2zihxapyt.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2qrpapire.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2otwnteco.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wexadmkm.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2owkttjvd.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2jgrvxtcg.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2ckwowmii.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2vccudsft.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ppafrbct.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2yhknqibr.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qjimhvke.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2bkdjutse.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uchjkgxx.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2oqjnwqxr.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2utjrnikj.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2nizwiyhq.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2ereepdbe.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xiuwowyx.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iqwxevug.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yvmolnal.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2cjbkixof.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2umhtrqch.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ypjlbmvm.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2qofvnsis.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rrnsgyht.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2eyqjznlh.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2wuusgkox.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2mrdjosrc.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2kpwlsivz.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2usjxuccg.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2okpzvvnz.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2zwhggunb.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2qfpifkxv.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2phnreyos.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2fgxvjrds.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2gjoojrqi.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2spgsfqhl.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2ynfoognt.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2topkpxsi.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2yndsudhg.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2dtrbmpjy.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2vrzhmegg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xfrgiodu.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rnqpyywr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dtcqzkpx.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2wciodmls.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2rgpcfkgg.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2dxecwhwi.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2khfcgmyq.html


<!-- 参考信息 -->