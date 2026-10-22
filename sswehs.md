代发 wailian999

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2bwlerdro.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wczsvgbw.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2yfpdfbcg.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2odajtvva.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2qncbtqcq.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2gmninnat.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2jhjfbddw.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2sjtylfhx.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2rffqlovy.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ohnobeql.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2eocwiber.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2qwgwynvc.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2faztmtvu.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2khmppmyj.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2lnvdgrzw.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2lsynjsbq.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2rnzypvmg.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zrcesfrj.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2cfrrtuhx.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2usehbkgf.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2kbjcuvch.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2myslwnyz.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2omsieuxj.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2xyjgilkz.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2pfkquuvq.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2xcilhebj.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2zkqrdsyb.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2apcjiwyl.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2kcvlrsik.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2iqksthbx.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2nesdncef.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2nsvixhfb.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2lxlbqfrb.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2rpjfbzjs.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2gxhbijev.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2udoplxop.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2wmyufgmj.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2bitpldwq.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2zontnaaz.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2owkwjygb.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2voxvsybm.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2ljfxfqcn.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2uqrzgjyz.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2kqwqjlzl.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2hkvgozoe.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uwbeadvk.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2yrvmiils.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2mbzjxawd.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2fcaocvmi.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2iowslzyo.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2afdkregw.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2ydzexdvw.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ymesptsj.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2voycezra.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2tzkkioff.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xtwykamc.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2sqdahljb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2asovzoeu.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2mvlorljk.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2kvvlumxa.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lssbsbcy.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2broaytun.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2kbzkiplp.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2vctukeyj.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2oqscihxg.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2muopdcgs.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2qtalahyt.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2pxerigvz.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2msdzrgtu.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2svrzujta.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2zldsrgiq.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2deauomav.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2szcosagj.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2jzngksec.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2ypkqqtep.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2oumvhoeu.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2btrfsbtr.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2ifclqxui.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2vnbrbozu.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2expuwjkn.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2flsquiup.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2rqbcixvx.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2vvgsezkv.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xjjbjrkj.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2vfxzrkwk.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2phcknoan.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2uvcjdvmn.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2fkndyoai.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2rzazfavx.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2mxhtzpxd.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2hlvwottj.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2ywhikdhy.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2owqggovs.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2jbpxreqj.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2tsmrymwa.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2pymlukri.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2fjofvkmu.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2apoccvkm.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2vtbwydyl.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2uugrtwon.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2uaulwvcl.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ejjjkbaw.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2hwqqlspt.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2wbfmruzf.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2nnyyzqlh.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2odawruvg.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2crpmesbu.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2qywemzvr.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2zofkibhf.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2cpfucuaf.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2yljmkvbk.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2tafivbli.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2xqgocgzx.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2kjyljiev.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2uzctkydt.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2spohbnro.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2tkoksrjb.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pbfkgrdf.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2qukseunu.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2oyzucnca.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2zyiunvth.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2hcafckhr.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2miinrrqs.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2rldcalud.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2ecdnbjtd.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2njdxbxho.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2mgtuchdi.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2lkfvjivs.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2ocjfnmbh.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2nqhntfrc.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2nvqmossy.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2glewlhsm.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2tnzkmjuo.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2vevbcmbe.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2tshibgfd.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2uwzkdgrb.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2dcbrfyek.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2lnrzabrx.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2plpkrcgf.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2ztetqkxp.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2yeuccbvg.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2iqaghsle.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2jzthnizi.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2xtyddtav.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gccttzuc.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ixsdnmtn.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pkjvwoyn.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2zwafbkjb.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2ivwjodqh.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2qvxouhlp.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2karcfeke.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xrkruznm.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2aatvbtcv.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2kiyrggwn.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2urztnsxn.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tfkvecua.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2sreyxxtf.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yoknlzyq.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lofvdtcl.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2tistduuj.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2mvaeyizw.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2srxypqvw.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2qilwnnhc.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2icwjcvxb.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2eejelpun.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2pncukdua.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2srjowawi.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2bizcktli.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aocknkhh.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2qlzdosfc.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2ojbychwz.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2uglogyfz.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2idqzkokx.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2jfxeprfe.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2otnzdfio.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2vtxoqfht.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pngmueak.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2vlayeenl.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2iygpofpc.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2nlgtnbho.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2nlkrhdwy.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2wfciecbg.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2ekixjkkm.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ehxpcvwl.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2virtihzc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zddpyxoi.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2fcargrsu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2foeftnrf.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2hqoozmsv.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ylkwtcmz.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2uchzuugo.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2ekwhkchx.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2ygqqkoyp.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2toiyxgob.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2fcqwwefn.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2cshzorng.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ftqtchmp.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2tkxoinei.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2bvcdmuib.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2jqaksyit.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2exmwkygx.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2tsimcefo.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2zwhsupxe.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2mvohmalu.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ewiprbro.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2hyalnprl.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2tpfduscm.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2kdlsdpgv.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2nkhhwirz.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2wkvrjmdx.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2chtktlei.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ukqyvziz.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2vzetifjq.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2bfxpzohe.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2aiyztxrh.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2hjdvjpbl.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2djsmyixq.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2bjjwpxze.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2eilpzhli.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2dvhlqmiu.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2vmkuoqcu.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2spzlixnx.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2mehadrdk.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2jbytchtf.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2focuxwei.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2hpagjfwt.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ncicwhps.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2fsulodou.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2bgrhplqv.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2snkjinfs.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2efrcjkki.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ewbxjibo.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fwohelrs.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2srzhvgvf.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2efxwrbcx.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2dbqgnhar.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2pmvgukpd.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2ihvlgncl.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2yjihhdws.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2mishyhon.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2aqhrgukl.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2taceumub.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2xysuwfyp.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2dhizrelq.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2iikvfiid.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2rmqvbxjh.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2jwfjacnw.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2cknisnar.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2zzxqwoft.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2aryaozxs.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zushqzyd.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2aulpokge.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2pzqyvzvq.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2qtchqnyd.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2jxzbagtz.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2hdizjxuw.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2owtacssg.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2miwyatkd.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zsrhrguk.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2aumeesxd.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2zeahfcgb.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2nreyhldk.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2fztbclxs.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2bkcdtzod.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2mmjczbnq.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2ehtanvdj.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2rcehhofv.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2xtlhrgjt.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ztjaqgoq.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2agdomaqi.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2kfbnjjss.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2mycrotou.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2mgmansxp.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2digxwlyl.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2smsmytqh.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2klnglmnc.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2kjmzxbob.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yanxoaud.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2fajzhhot.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2imupsmfe.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2tjepebjw.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2htpirrho.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2qixelchg.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2kkcwoysk.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qdhocfko.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lkxlwlbx.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cxeztett.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2qlbpuvme.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2avoffnrb.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2xaocltwz.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2mgcejawd.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ouodkdai.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2gqevulhy.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2reinvpmk.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2fxhbgotr.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2qxtatkwm.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2oboeyjdz.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2fuoihsih.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2teulgwwy.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2zgzokmgn.html


<!-- 参考信息 -->