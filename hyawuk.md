代发 wailian999

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2klmxriuj.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2ypryketk.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2wovbbqtn.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2zegazwxb.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2fncpccwc.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lvrtwbxt.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2beomagqz.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2nxwgldig.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2hlkyepaa.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2uqvxxygq.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2mucgnknr.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2fxvkpres.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2mcmitivz.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2seyirwbj.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2bqgnaczm.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2mhgflluq.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2smrtcpkz.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2nsaotdtf.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2eqptpoin.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2scrtaiku.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2etagfrxr.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2idxobljv.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2mbqsxfwp.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2zzehrzkh.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2zicqjmwt.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2bdslzkth.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2kylaidqx.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2kmerpnsz.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2yntgnlof.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2bkuyfaxk.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2cvjzwevr.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2llkwomzd.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2dxlotfgv.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mtkpykqf.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2vfbgazcm.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2wslditeb.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2rnzhljji.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2fcexdpyh.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2gswhifnp.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2hfhpbwvd.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vfsyuwvz.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2mmmrytwi.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2oyogmlqt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tgmdphlz.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2rsfdneaz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nbxgxqlm.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2rcaocwvk.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2ftterfzh.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pgpkqawp.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2nwvverpt.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2gioijmpa.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2sbqasvgk.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2geptdvmw.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2gzrryxic.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2jycycgfy.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2rjcubkce.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2bwuiioha.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ysagcemj.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2lgcyljun.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ftaafnvc.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2ttoexiov.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2ghtfoukc.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2ehezorla.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2uyvsseoz.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2vdzgycwz.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2uayqdher.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2bmbtwwpc.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xaxrxzhp.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2oapacljl.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2rydqnjpw.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2njwcnanf.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jugpgibs.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2jqwszpnn.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2rmouaeia.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2tcreyqeg.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2eoglzwax.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2ktvcksga.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2wziolfas.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2fgorobft.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2jzlodwft.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2wtdfmkvo.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2nyaxgspl.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2lgnjtxbz.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2kuipdmbt.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2quiscjja.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2jfovykif.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2idcnbfdw.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2ydaoymzf.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2jgmmxrde.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2fpywbbrb.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2mjlpzqtd.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2lhsewkxg.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2kumlokta.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2slocaavu.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2mybilspw.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2kqrpvnes.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2newcozqq.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2sujwkgpe.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2pmcjphgi.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2jhlxuqnh.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2fqjaacko.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2avqhspdd.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2icfwogrd.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2eywcrxiq.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2wikrhzes.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2aynybgqa.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2swpmdgkc.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2lfozagre.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2mmeequdv.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2gvmxyppy.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2gtchcyke.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2xshkknyo.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2ltezhxvh.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hyottytn.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2zrusduha.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2jndekwwb.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2wtqqiphd.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2hzzgiwkm.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2fapucwjz.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qgijongc.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2vbbayqiv.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2oqudmaop.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2alawkgnp.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2cqimakdp.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2xonhssdj.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2bvxqsnuw.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2vnudqumf.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2hzduylnp.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2pnousafx.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2tfjabwfx.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2zqwiegoe.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2qnimhnzn.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wblupxck.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2nzyvsnfv.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zzmsiumh.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2qedhgjox.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2vcdksffs.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2bbbxvcje.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2xeljonvf.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kklpnazw.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2skdatncj.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2sowfxgso.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2tzhrftou.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xathlgae.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2wxzvfims.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2slhalkaf.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2miikvlkc.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2hzrsdhec.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2qxzynqfs.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yrohuuhe.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2ducrmzpb.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2wriuipyu.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2livzqxao.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ashhtjcg.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2nrtanksf.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2ecjyhdit.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kfehebtg.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2xmoriasz.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2vfszmwbw.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2rkntnavo.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2okcpiqcx.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2pkgzqqdq.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2hksnjzrm.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2jwltsphl.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hwxcspen.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2cqpfudei.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2gthjqats.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2fqtxtuiw.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2idrqeipv.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2tvubtfuj.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2ryisxvyl.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2yqxpsvaw.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2ganmyzdu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lcyqnuju.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2fcbglejb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ljbcaznh.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ymmvymde.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2mphpfkwp.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xzwsauwd.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2yevbbgba.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2nwwxtzrj.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2lzxjtyyp.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2ahermotm.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2hrrdywxv.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2tuazclay.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2ftrlkzfq.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2blitrwxt.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2lbhijqhs.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2fqgdecxv.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2zoygxsgl.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2fvolueiz.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2hpjvbkhr.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ewqipreb.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2sseizbck.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2kzqiqrfz.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2hjrnfnuz.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2zwmwvqcc.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2tksaptcp.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2lsssmhhj.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2tfhpmxnd.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2vzqzubir.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2smlrjbdi.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2yqbcccbi.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2mgerzmgs.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2ztpbnvlk.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2nmtzymps.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2cbjxbiac.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2sytnergw.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2jpchcnlr.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2poybaqzp.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2mcutzfbz.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2ligobztc.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2fmjhuixd.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2yjczvkwl.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2wxozlroe.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2uuruwtij.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2lsgyecdv.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ectcgjqu.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2cvckgipm.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2qayxumfz.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hqgucgeq.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2tkofrzme.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2iqcdrzza.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2xmjvuqha.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2hngvhqdv.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2mvtfbyki.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2lzqucbhv.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2enkgrqsz.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2iswxrvff.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2cfolafez.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2bvmpdezj.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2ofuyupjk.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2wqawvqab.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2jceqpnhj.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2wcvdadno.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2nqlqbaxy.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2mrrnrjyc.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2aiqruzsi.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2byxcbowq.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2kjtasmxc.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2mwvculus.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2uuzrwirm.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2fmzmyafs.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2fnphxtyc.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2gvgckkdl.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xdvyyrwi.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hmjuhhht.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2yglnjpmt.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2bhcwnmhz.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2teqdfypw.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2nxjruwiv.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2zesycaxa.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2deynlndo.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2bqvtyazh.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2rviibqic.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2naiisalb.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2gwmfxtzz.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2jjkqrjbz.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jawyvcjo.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2kmmgtgkt.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2gubkluan.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2mboshlas.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2dtpfdgpp.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rsluxiiw.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ajxnhrln.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2envulxqi.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2hfhcuoyl.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ybnaxqoi.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2sqeirkvu.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vpyytqsg.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2mdjuaivm.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2perukica.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xvfhfven.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sunwdftc.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tzkkirmf.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2xzhosysu.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2efnhsgsv.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2vlkoecci.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2akvdxmft.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2brozrxum.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ntyhuvuj.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2bcncbfeq.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2yllpvaug.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2oyjxgwdm.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2meufyula.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2dbirbhln.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jxdedimi.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2eumjizdd.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2nfqefaay.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2odzrpwno.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2diidhgyf.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2jlbsmrkh.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2gwyyikhj.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2cayoqexm.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2nilxsypl.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2zdwaqfwz.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2hnycprgp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2aavqtmdw.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ddeuyfix.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uarnoizo.html


<!-- 参考信息 -->