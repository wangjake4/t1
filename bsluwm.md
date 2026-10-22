代发 wailian999

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2epeulgyz.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2zxopbpnd.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2xqkbgwtv.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2zkncvgol.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2zsqpwudo.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2yivtwvbi.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2ieimxpco.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2ntapgznf.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2wovvcoex.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2ulsktghz.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2dhoabvru.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2qbbczzww.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2jpyvdrad.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2nssiqccy.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2uwosmprc.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2yrhsetfb.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2ivzsweoa.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2wnmvfehu.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2udppekat.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2iqwdwhxk.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2jtyddvbn.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2aowmbgwv.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jpxxzdgh.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wsdkadka.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2hoklivrd.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gazogezg.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2tziestpg.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2rnwyvfmj.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2keqxafat.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2uzqahxyr.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2btyhamdv.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2lumnkexg.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2pxhtyhbz.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2thqcuqxb.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2wljgymma.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jbevuzwh.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2syrjvwxi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2meovptnt.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ymtwhwxz.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2mlkxgzqs.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bzgczwci.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2aakkifka.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2etskltnn.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2zxzmbitr.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2hbiynhcv.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2blvwkhxa.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2dewzsjds.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2oarcirpb.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2nyvgufxr.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2kdloceir.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2lhjvztgi.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2sqdveojj.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2xogfsbdr.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2vtjuiwwp.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2xbwyvjbr.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2xgkbenpo.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2mqswailg.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2abefcgmt.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2tzdvcxmp.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ikscgaxk.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2abrfjxqp.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ddliqsie.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2lvlhxuck.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nceewzux.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2wqdmwlmc.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2siqskgwb.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2jrjtkwex.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2eskimxxg.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2xiozalja.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2rvnjchce.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2ayzcchcl.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2hdtwkggr.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2bglsplib.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2qfzzsalr.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2ixmrzgpt.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2vpbogade.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2qpfpqcva.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2kveikwhe.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2kepeooyl.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2oftcapvo.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2wcsqwsuq.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2rkjpsprr.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2mqstneyk.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2mhuhywel.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2jsheuyaa.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2pcgfcnva.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2ftziuddz.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2azrzffps.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2epanotsu.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2hrjobtov.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2sfgpsivh.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2kfmlaeum.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2kgpfzcly.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2knxplhqb.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2fxrjdbhk.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2bxpexxvb.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2lchsbigj.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xjftlnns.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2zntbdzyw.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2kifjmimn.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2ygtunvbd.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2awrbxnix.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2bcdzumbw.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2lnimqrgh.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2rmnqwqph.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iwuocsaj.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2fqpnkpjb.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2rhpjqdyz.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2augzifaa.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2hfsqrpbe.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2acagvuhd.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cjxkoxct.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2tbggrihb.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ggbhlodn.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2owobmeaw.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2kyhfmoml.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2ybmlrcda.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2aphzrshv.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2bwxfmeqa.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2kmguprtm.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2coflvdec.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2qztydmpr.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2umcylwbq.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2dapcachd.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2amwpxnin.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2irwxdrsc.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ipvedbvf.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2vthbfqqd.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2cuncrhmk.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2itnllbvo.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2hzxyzqtf.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vcqpbjtz.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2cmdrfkom.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2tvajaulg.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2phuaarpa.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ihqivdpj.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2wpnacefr.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yjkfvllp.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2osatmhvx.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2lzuuozpd.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2orjbtyxl.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2anrdfabk.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2antpbnwj.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2qyfhsyiu.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2yrbrmitf.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2exrcxxbf.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2iiyblmhn.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2rzqnpmbg.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2meljzfxh.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2csaaqjgm.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2sdvjfqjw.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2jafznvev.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2irmzwlsi.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2mixwgrbx.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2bjduplxj.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2babiwryw.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mbevrwdj.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2kvkqviwe.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2xrgzhseh.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2xtboqaja.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2eczpqlmh.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2wbdcpkia.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2rfvqvqhu.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2xbbvbsvs.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2vakbcshn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gtaqmlcp.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2gyjggsct.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2llmynqgt.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2mtgbhegv.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2fislpzbw.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wpfejzar.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2rkqvamkm.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2ypsvhdya.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ufxpupwc.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2mfmotqpl.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2jrwqcuzd.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2tsfujahp.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2fvcqbtlf.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2ojtzyhvl.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2yladhlya.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ntbwqgzn.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2sbtcmzzg.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2jtdnnfvt.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2zdigtarl.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2iguybfjt.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2vbvnqcav.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2nezcrmrg.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2sdwapzvw.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2eqajxzrd.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2ztqlstbb.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2pebikyhw.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qdcqvbkp.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2arzfhczi.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2mdxhsjzo.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2yhthakxd.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2ynqksexr.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2vegtrwbj.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2dnkptmwj.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2puzojzbo.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2xbosgumk.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2jxunqagm.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ghuzqlgq.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2dyfmvurv.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2sxtjovdm.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2zcvvemmw.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2wywhtuxw.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2mmajlbfg.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2hanumzvk.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2bmebebxj.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2qnrtxfij.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2lmatnynb.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2tzhcxjqr.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zfqvaigt.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2unrxofdh.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2xpydjcpw.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2sqefffak.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2vmwdgesy.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2shxmmudv.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2petkxujl.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2xevomgvu.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2tzpzeqsr.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2fqybyups.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2gqbnwqzc.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2itjxjtyi.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2mqmoeqzl.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2rlyzikhg.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2zczlnytu.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2zowzcifr.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ghcsscdb.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2eufsmpfx.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2aufodcfz.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2qpcvrzlq.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2cjyrknku.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2juqycuzx.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2glvsordv.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2jousgpbx.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2iqekueht.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2wjkywoup.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mystmgqv.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2eekfamup.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2gfjngsih.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2yqsttpog.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2bovpslpf.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2nxznyrez.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2prsiohmk.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2vehdjxmw.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2fcnppfrn.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2ysnvfazu.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ojzayhzq.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2lqymplni.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2uoqtmifx.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2mncqolte.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2daiphpnh.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2buswlllu.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2hozdlqsd.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2janllmop.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2nsazsbmu.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mvoccumq.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ppxivasx.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tchqxezk.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2xnqelknc.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2avpzanzu.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2oevtbzit.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2iukrofkw.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dnndevmy.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2utuvjgex.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tjuyliml.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2fsclujxb.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zadqswpx.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2clqwzcbm.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2xegilokw.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wcwgrqcy.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2iyvzstzl.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2dtehhyws.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2tjtotknn.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2pskxzfkk.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wxtozvzg.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2njfpxuyh.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2yhlsshfj.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2utiegwsm.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2fcekcnia.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2juvlzxmh.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2jbapvxws.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2yhxwyiwk.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2fsryjkwn.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2igvbhhtb.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2djcmscvw.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2ykiindlm.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2noukbpkb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2htrrzjmi.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2bnlnuivu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sglvoskj.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2rtamggkl.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2lwfqovpx.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2uozxujnu.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jtqkiaae.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2zjkgttpe.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2ciwapxyb.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2emkxrrqx.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2vnlbzrsg.html


<!-- 参考信息 -->