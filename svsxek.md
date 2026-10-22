代发 wailian999

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2rjcjmeur.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2ttdcqlko.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2dctgwdhu.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2qqftifqw.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2evgpzdtr.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cjgqnffj.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2gwhsrtmc.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2vnvrnbvd.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2hhhbmsbm.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2yrdwpzka.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2ekbikxzr.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2zkclvdgr.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2crshtffv.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fpnuhdaf.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2sptstxkg.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2eiwbcdag.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2yapbhczx.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2anupvnly.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2lcjoczxs.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2boteqnmr.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2lsqtccxo.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ljsagzrt.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2zommnmhg.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2ltcwhwew.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2nqqsimyg.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2minbseks.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2atoddgxa.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2dmdhqjla.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2yjddvsmg.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2isechfmf.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2fnhvotxq.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2klesicrx.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2bjxytrgl.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2csxfmxeo.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2sqrxkpcy.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2ucjbkkgk.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2posgnffn.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2ddyjxlrk.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2rffbaajn.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2hcxiyfui.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2ntqvwism.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2yqzoamdt.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ggconofx.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2rfkcbaat.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2ihsmqckc.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2ehbhttup.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2yexbotun.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2nwtvcgbn.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2qepdquqw.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ivwdepwn.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2ssrzabzl.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2mrglbjlk.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2gtnsdgjo.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2qxvwtqwt.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hvqcjeih.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2reqwqfwz.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vgwgtytl.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2kjgvohro.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2jtoeqaeh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2abnvtrws.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2bklktqhg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gphkgsxx.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2pbcdbbqh.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2vustzehs.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ngypxuwb.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2gmlofriy.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2qvjsdvkb.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2xrhcpkxb.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2klqytvxg.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2aoorzhnq.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2bvybfkrk.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2zwaokyqo.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2crcorsvu.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2aidycjav.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2nsmzaxga.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2cbekcvbe.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2qkbgzwym.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2vuibofvk.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2dnsqmipz.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2ylmjjskg.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2dykyunnk.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2njlyowqs.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2ewqrbyia.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bofqevbo.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2herwhvua.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2nkihndju.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2zglhktgs.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2eanngkqo.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2xrswbvrn.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2khdihrzb.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2splmnvfj.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2qggwglkq.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2htdvhbpl.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2jgpmbkne.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2fcnsxpis.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2clvomshq.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2moucmceu.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2tzaqzysf.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2wfyvkouj.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2kvduzixj.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2xiwiuqbw.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2xbepfabb.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2xxdyrdrz.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2ptkkjbfl.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2uopwiinf.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2mpjsuwyf.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2skroyhcr.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2upbxwzkj.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2ipvpzekd.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2dsryytck.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2eyiiylfa.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2ocofylva.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2farkslav.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2qwbvpacp.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2dgshrdad.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2gnsmmfyz.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2qovdpocc.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2rfxcoykw.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2vpomycem.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2corfgfjo.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2jrlhiwlm.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dygzkaxq.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2lwpojukm.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2srfsiwwa.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2nrwiflfd.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2ewuugtxy.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2mhgaqfhc.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2nbtqapvq.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2ffsdbesc.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hfpryltk.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2zlgdtvno.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2mafmhwva.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2xwzgybhe.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ttcqrneh.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2wrsbshir.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mmuehstc.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2dpnilbqr.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2pkcbmkjt.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2bxvfyikn.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2mpqtbeuo.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2yvoghvgb.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ufmiejkj.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ezlgwmwc.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2rvtndeoq.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2fzsjpofy.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2izflyvei.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2pndfrpsj.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ywkzvjfm.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zptqpklk.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2girhrxfy.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2umpohime.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2hshokzdp.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2vmxzoiju.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2inyqzwdu.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2lvnpokis.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bztssrwh.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2uotcemva.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2vrxqpsvw.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2zsrvkjqc.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2snxvdlgy.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2kpwnlbma.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mrbpiqwp.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dlshwrtf.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2xkygwxcb.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2zayubwsw.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nhsxhncg.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2gxtqhgjs.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2wmtcbuoc.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2wrzwihlw.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2lnlcrkzm.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2uzxiyleg.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2cxowvtbn.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2putwlwkb.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2qmttnstx.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2xfjoozfo.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2oilmslos.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2mnrpsppw.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2uydeqzou.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2kpwygxpg.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2vekoowtm.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rtipnpiw.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2gtlawpkf.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2dyygapcm.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2rotfvjzw.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2djcbxkmq.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2xuugukpd.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2qistaxxu.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2bvquodhb.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2wstykhgc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ofepjenl.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2zdoteljm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lgqtefgl.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2sraugccz.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2pqhawhdi.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xacfcyzx.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2lytjihte.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2tljoyivw.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2vesewhtj.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2zpmtpyvh.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2dywlqgvu.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2dezzuaup.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2kzoihqmr.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2xtfjafwl.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2belnudnp.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2dcsrrhfr.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2cgdjktqf.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2mixuzwec.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2klvrtmyw.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2odajheos.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2vjcgkmtu.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2pdolfznd.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2peprndeg.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2rkenixjj.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2pigemkkj.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2tmxizudc.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ucaezjfx.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2cevaqutx.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2wgcomtax.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2clbxfqoe.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2klsieurh.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2liksyujd.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2ukfxlrek.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2flffwbkm.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2yaqgnrmw.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2utwbevcy.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2fawyfown.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ectwreqo.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2dobokedf.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2ivfdzufr.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2twkiiswe.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ujdnlfvh.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2dbrjnkeh.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2xbfufdwj.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2zexoijmk.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2wenwalim.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2hhclyjcc.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ualteonx.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2nvxutfyk.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2dfrksfcu.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ouxapsjt.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2dybjozyv.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2ylqnneeb.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2wtcttwtv.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2grusroxe.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2uwhnrwfp.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2stkvghol.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2jnnokfim.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2tncqzyxk.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2axxjhixh.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2rfpgdfyx.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2fuujfmzf.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2fdhdvahg.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2hsydwarq.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2uplaifkw.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xwyabrvt.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2wqyxgtdw.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2jkwhyjxy.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2izxiemzx.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2bsyxfavd.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2dmxxspzo.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2muylxhwz.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2jzzsftad.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mbpqaxnl.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2vobttnsd.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2qaxyxmem.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2inffrumb.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2gqdxpunw.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2lvdrnpwx.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2hganicth.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2axsnkoln.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2ivjibxgk.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2glatowfq.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2xofndjqq.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2hhawjiyf.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2zvwsdaum.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2eoxedwku.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2wmdumcce.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2zjwdanhb.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2wpkrfrts.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zctpjyha.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2lvgyzxnl.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2salaomiq.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ncizgohh.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2odckfypv.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2sudicdfk.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bjvbsbhi.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2oibhprjk.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2xuxvvzde.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hfnsflab.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tfpftgdh.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vjbccftx.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2jsnemkrx.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2agchcxza.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2tkiuffql.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2rblrnnkp.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2awbgtdcz.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2eohxbott.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ixfuipkn.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2bponmhcw.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2yhemoyuj.html


<!-- 参考信息 -->