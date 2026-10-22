代发 wailian999

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2tepoinmw.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mwalnoim.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2coitsgvl.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2zomdexeq.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2fwwawjmf.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2kcxidkgi.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2elelseqy.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2zqoustcg.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2itcgpgmd.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2hbnudwwh.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2oyrdlezm.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2ilxzglmh.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2vocpgcwx.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2jyxtulkr.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2pnbquntu.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2ygqrmdqn.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2prbfdhgo.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2uwcuntbi.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2jnezvoeq.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2wnkkxvos.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2gyxtzgwv.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2xcuzfzfy.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2sdpbsoim.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2yrcaloir.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2xszearoi.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2mgctngef.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2rdzcmpbd.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2cxhcwkkj.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2ccomoozu.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jezmefnk.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2fesuozss.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2cxnbplzm.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2kzywzual.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2cvrxgouh.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ebpfijrt.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2fkaamexc.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2pflydpjm.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2ryqsiave.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2dsphzejb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gcswgfgv.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2xlvdkexe.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vakufgkg.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ujvxsxos.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2wdzfzbys.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2olbwffwt.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2eoxzoyme.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2cxdtbqvl.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2htlevnjy.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2rldetesa.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2qxyimdut.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2cydhfkpv.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ypdikvqc.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2jrclptok.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2gvzdltsf.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2cvmiskuq.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2xiwqimxy.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2pnymxqae.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2bezpzsfb.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2caqvyjvn.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2tddvtuni.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2ulbapnel.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2vjlmwpne.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2jqkxujxo.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qsanpkju.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2ewfvvlzs.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2nhfwmmrs.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2pnbqgoax.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wdxgquav.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2atkwlahp.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2doalchxm.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2wcltlajp.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2aoiruqgr.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2yzylcnkg.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2exfvfmru.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2mrolcuzx.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2rswzycer.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2quszutox.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2dnbhvqbt.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2hrjryyan.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2siretqvm.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2gwpsgxcb.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2afszgisi.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2oxtcbxhd.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2vdvfikse.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2kktxawww.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2tjyipxmn.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2xnllehqe.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2wumoqdzo.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2uedrdgye.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2srzwpssr.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2ywarolmk.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2dmzscysj.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2chnftdxp.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2uhjpjfpw.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2dztiyqhm.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2uozicwhg.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2uifipkrj.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2ygkxtwws.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2hpfrpffw.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wdhdjqdz.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2fzkobsvh.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gjbnpuog.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2fykeunql.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2kvrkrcay.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2gkirsbtr.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2qtuitanr.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2pjdargjd.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2szaabvji.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2gpjsupdt.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ytllhoeu.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2pfvxdavr.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2oedyjicq.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2wjbsotfv.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2zaczvttt.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2kzsgkhag.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dkzkhhie.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2znajthoc.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2gsftcmzp.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2wmasvzma.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2eegnvrky.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2qidetwaq.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2unkezwde.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2zpwujozo.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2pojzvzqp.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ntbevzae.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2dnszdcds.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2lqpaqoam.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2hcvcvdqg.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fdeyihks.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2gisesxsg.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ummoynjs.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2uolfiald.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2usnprtmu.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2pzbrwrzu.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2kzewnrhq.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iewtyemt.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2mdhjjkzx.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ijkcyuot.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2sceqkadi.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pivrorsg.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2jroorqgm.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iainzkfx.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uqynjhan.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2jggskzio.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2euzuoxvm.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2icdcdtuy.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2alvacmzc.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2tyqguzsp.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ijsgxpqs.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2wqmdmtjo.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2yblhdryb.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2deekvege.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zweorhgi.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2eoyvgwfk.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2weaboitx.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2gaepzwkw.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2wiomwqbh.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2layrcsgn.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2bphxibbr.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2nsusybcv.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qshvixcu.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2mvcrqppn.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2lwbhoilq.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2pfoegjiv.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2pteeoxbr.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2dldvndwu.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2ccsgobhf.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2khhwsbxa.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2gzxcfrex.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ucxqzshk.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2lududopa.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fpmmwkwz.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2whoroizf.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2xumecnut.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2kdtovfzd.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2gdpffoef.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2cdljwemu.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2rfygwrzv.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2nsmmdynm.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2vspwvtbj.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2vrmjyxzu.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2mkopvhsd.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2ammmnpwe.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2dgrscsme.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2thapjyky.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2brqhsndi.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2nmeigtka.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2dkutjvfl.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tpiacvwt.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2atbiueig.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2pdufizlb.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2uyedzphk.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2miojqhme.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2mmuanukd.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2yuqdsdlj.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2kdwhjnwz.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2ocgphptp.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2pdmnzxmv.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2uvqlsirz.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2gqggqupe.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2kpltivfe.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2yezeyrci.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2wovghfcc.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2hxcyzazk.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2hcogsgdv.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2drhmnuym.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2gbqttrad.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2cfdkhawn.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2hqjkiwfh.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2uepadoxl.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2mgpdbuvb.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2mdxwbubs.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2kzdvzybe.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2cgltmttg.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ilkzbror.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2thhemvfv.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kgnvdtms.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2bngznemp.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2odhwgvdj.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2thpdjbzq.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2itplimub.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2vlrklhds.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2twrwbgoq.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2tmxxpshz.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2bcrbvekp.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2bylbcinb.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2kstqkncf.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2uypxwlid.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2luxcmkgs.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2eydgrnvh.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2gwulxprq.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2aozhmixb.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ngrpbnht.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ynagyrki.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2omqlihsr.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2vcrktjnl.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2rffsnznr.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2doyfrxqa.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2czaebtpf.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2oyrxiujn.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2hqusddem.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2mgfrafjv.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2euqopfth.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2ljphjiau.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2wbkjusjt.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ohovgema.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2joumvubw.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2xpqexwea.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2tzatynoq.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2stkawmgd.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2bfxfyszl.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2bibvffan.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2scyiuwmb.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2frepjush.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2rfvwfwxm.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2abaflctm.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2lhsaqcsr.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2pkonaftm.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ezowhtvs.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nifyhpek.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2jjoqnyof.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2okbwywnu.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2nrizczkw.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aveqpgid.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2fbodwkok.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rueicvwy.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2jdonebbd.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2dsvitugo.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pblhdsvd.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hdcmacps.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qvxelpei.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2umgdeite.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2khwrmazz.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ebiezddx.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2lwsybnur.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zrggwvhh.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2vozhkksl.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2qfxvtxpw.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ydtdjtjr.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2smrxsfko.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2anlkoouf.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2wftcclix.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2sihbcmdl.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2njzkxhtg.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2ntwltyqs.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2orgkxtfx.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2hnwvvxuj.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2zkgeyaoj.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2zvcrdidf.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2wxhbzfil.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2lkufpgdy.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2yxmeisbx.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2qwinjzbr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ercuxaqm.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wfoumrxe.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jtpkfgjr.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2vsxckkqp.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2thespeqg.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2afoxpamd.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wtphdpna.html


<!-- 参考信息 -->