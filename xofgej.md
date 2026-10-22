代发 wailian999

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2ktrhiqpy.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2yciuyriw.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tgeuprdb.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2qwouvceh.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2ipctmbmq.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2igythtwf.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2sjknrnxz.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2arekgkic.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2hgnolkjt.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qjihfogc.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2cnaabvzt.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2xaqtonxp.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2jwynntbe.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2bxbjsjzs.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2voynybto.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2fywobiza.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2saddqrtn.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yffkjnvz.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2xozdyrxw.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2sihvpcsc.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2ujnejlhm.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2iioxjuba.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2mcpqhuow.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2czidzsmp.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2abrobjmr.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dsvewona.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2xutsubxi.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2haafyeam.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2spkctlsi.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2bgoeuqpu.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2qccdfyok.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2yespmjze.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2raksuzue.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2udekpnyr.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2fwqboqqg.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2uhxnfwfo.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2bamkdzai.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2wkitdzxh.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tpaediak.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2stuadaab.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2xdxlfqcy.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2taqdoeio.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2qsafknfp.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2qcgxifkz.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2xjlqycao.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2msojknur.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wcmgtffh.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2wvcetsop.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2nuphgwva.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2xktxxadv.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jatfqryd.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2trabxlsy.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2hauipbrt.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rdnzmimq.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2fszblmhk.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2sbykohao.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2mmxvyhyg.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2pzahrrlt.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2gcwpiykp.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2sfwzhxku.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2swnrfnda.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2zwxkueyc.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2knyfclpv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ouwxvzty.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2tamtzrap.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cjdwoeat.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2widgeywi.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2fkmyrggk.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2clfwpcma.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2rtqlremz.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2gkqpdtyx.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2uqggfkkq.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2fazmedyy.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2lktctxzt.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2zzyozrhx.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2bfkpsxnv.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2qpgblmpu.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2msviarlq.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2ojcwkmki.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2daysyaqr.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2zzldxaic.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2wmphygkf.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2buihcpbm.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2ovrywimg.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2syhzgxwx.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2qjemtjve.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2sadqndpb.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hyndgixi.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2ahkvgpdd.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2hqdulljv.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2fqrhqwna.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mzmucvch.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2qxhpsvah.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2kzlxdocv.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2akprranx.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2zoixxfzh.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2braccdgn.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2zgjqqyrr.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2ijpfldvk.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2fnidmvpp.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2lqvjppzs.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ykjwaqgt.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2pkdtfcpx.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ykemvgdi.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2fwutpncu.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ugqtkeck.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2zoxplgdx.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2mfilgcvq.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2efxgqowb.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2vjkieqam.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2wejzjour.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2bihwdeym.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2zdcyqntk.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2yhpnubho.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2oovxwbdp.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2somaifqv.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2mtlrqels.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2ubpgrroh.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2rbvwobxy.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2hpzbpzwj.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2tqnowaau.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2zqgajtnz.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2rmzljfgo.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mxmmaspr.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2dxvvncmo.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dmxxuobo.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2rcyktfrj.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2qqmgvqgh.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2pxdepmoo.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2yehiecvn.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2aupunkfn.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2hxzyjspf.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2qxuiqaft.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rvusbbsz.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2zwyhygel.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2decrhpqe.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2griwynql.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2cdkcpfin.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2poavhkni.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fsgucfdj.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2ftucvuzk.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2sgmgotbw.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2hfudktiu.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2lejfrsgp.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2wdtbkufp.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2rdnhexnn.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2hulhkbej.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2tsdbioqx.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2bwabtbop.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2inofpydp.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2epzoyffp.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2tlrgldwb.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2eucozafd.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2rzlhzrif.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zcctoyij.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2kvgoqeul.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2oihfgida.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2nmnreoxy.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2qfmqchih.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xydskvnp.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2cwmplnlc.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2iwoaqxrk.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2ojpxfwrn.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iteqhyau.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2liwnmpzx.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2etjlwpxl.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lfychyio.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2uovhbzbb.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2pakdmtoe.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mcastizk.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2axomvblg.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2rfhhxzpb.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ardtezrn.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ukwmbdvo.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2lbctsbtc.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2iztcihyn.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2npuomacs.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2myoaubzl.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2btsvnvwp.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2aeauqgtq.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2nrncetjx.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2hcikwmce.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2yqytypqy.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2qejvbwke.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jnwmmfje.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2tujxaqty.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2qonalwvs.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2girzmuiq.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2yseelrbp.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2wwhxxida.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2vquysdib.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2hbfqsdqo.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2ojewwpfp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nygxirnl.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2jaxifjoo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ddgpawrt.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2fvixrprx.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ijchdeuq.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2euwpzsqc.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2bnzrhkss.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2vwcmqvks.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2iddubbny.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2tehymfit.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2pijzdehq.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2grcceygk.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2igvvzgkh.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2spqnhuyc.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ovhosguu.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ceorrkkq.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ogapckgf.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2vqiimaje.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2tckkhize.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2angtfvyi.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2uortegdj.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2udmhsnpe.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2mggvqohm.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2zfrzmbck.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2yanoiudo.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2lbekoczj.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2yuslyhkw.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2imvlpcpg.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vaekpdty.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2uolxbxiz.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2xrjkpfjg.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2kkizsvii.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2hhjuutyf.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2khgnudnl.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2emslgmhr.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2binswtih.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ccabdsyj.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2gpuwxshs.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2mfnglwbo.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2swbgcodq.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2stffnwhi.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2thiwjqmn.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ppikmamh.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2dezsiwwu.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2cfqfgjob.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2igioywfx.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ejqkgsjx.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vnstsmde.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2lkamerep.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2odroclhc.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2dhrseqyw.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2olhwmqjr.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2hrweoegw.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2yvtwyetk.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2flyuksvj.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2yqhakihb.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ffnrhbiu.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2sopxorxc.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2qzlpjisa.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2ketfczmk.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2bkgjexhw.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2meksvlev.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2zuwaevwm.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2kupyhwcf.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2owhpjdkb.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2amnfvdxe.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2kejrpyoq.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2hdlclpqk.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2mofhnocq.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2slfwgvbq.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2ibzmfszu.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2orwriufx.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2zhnmqcwo.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zubbclla.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2qfvjcirq.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2ixazoeml.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2tewszxdn.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2wbqbifta.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2pzfwwvsy.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2kplfkjxr.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2jnuylyof.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2dmonyvwv.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2djwclbxh.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2jvvxycyc.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2wnfmwhqs.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2dvtmfbiz.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2kmwlisje.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ftuzbdia.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2wamawpoi.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2gqgaxnqn.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rjeamlbb.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2okuzxjce.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xoecpbwo.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2zpcpltgy.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mieaqwco.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2bmwapigw.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jammbcjc.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2flfbxxdx.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2tzrfwbcz.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ogtosivz.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hsxcuudn.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mwhzqgwp.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2cjoqbtqv.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zhmkmmwp.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ocngcsnk.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2nddyyszr.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xojbefsx.html


<!-- 参考信息 -->