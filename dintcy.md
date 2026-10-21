代发 wailian999

sed -i 's/foo/bar/g' a.txt
来源：http://dali.c1oappe.top/Article/details/gthqgafvzq.html

[R48] awk 取指定列
来源：http://dali.dashuyun.cn/Article/details/gtrfavoxtl.html

awk '{print $1, $3}' a.txt
来源：http://dali.jyoumei.cn/Article/details/gtyjzukjzu.html

[R49] awk 带条件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqwytyshq.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.xziqi.cn/Article/details/gtzgwveelj.html

[R50] awk 求和
来源：http://dali.hnqzz.top/Article/details/gtsnhajguh.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zycfv.cn/Article/details/gtgzsteglh.html

[R51] 排序去重取前几
来源：http://dali.jinqigufen.top/Article/details/gtamruujou.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.ppjwa.cn/Article/details/gtqrfapcxm.html

[R52] 统计行数
来源：http://dali.mhx1999.top/Article/details/gtfakbgivd.html

wc -l a.txt
来源：http://dali.cashguo.top/Article/details/gtjrmxmhsk.html

[R53] 查看文件头与实时尾
来源：http://dali.bjfxy.top/Article/details/gtzccealiq.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.meibo888.top/Article/details/gtpegnrbhy.html

[R54] 比较两个文件
来源：http://dali.jyoumei.cn/Article/details/gtjwkdqfjz.html

diff a.txt b.txt
来源：http://dali.hongshengwenyu.top/Article/details/gtsbhxcpbb.html

[R55] 压缩与解压
来源：http://dali.hammf.cn/Article/details/gtppfpeijl.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.yuanzhike.top/Article/details/gtgvaevlqq.html

[R56] 远程拷贝
来源：http://dali.9152youxi.cn/Article/details/gtldnbxsrt.html

scp file user@host:/path/
来源：http://dali.sweek.top/Article/details/gtacenvxxg.html

[R57] 远程执行命令
来源：http://dali.ybcxt.top/Article/details/gtxvkatsmm.html

ssh user@host 'uptime'
来源：http://dali.shuidangran.top/Article/details/gtduvxwoqk.html

[R58] 下载文件
来源：http://dali.chenlongwang.top/Article/details/gtsiaqbfxl.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.gaohongyu789.top/Article/details/gtbwcaetws.html

[R59] 发 POST JSON
来源：http://dali.jqgfzy.top/Article/details/gtheykbbeb.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.yj20258.top/Article/details/gtdtmibwex.html

[R60] 只看 HTTP 状态码
来源：http://dali.sweek.top/Article/details/gtcwvesfby.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.birdmap.top/Article/details/gtyxcagoiy.html

[R61] 磁盘占用
来源：http://dali.cheryme.top/Article/details/gtrairmcsj.html

df -h;  du -sh *
来源：http://dali.kuanghao11.cn/Article/details/gtpgxobanx.html

[R62] 找最占空间的文件
来源：http://dali.guowangkeji.top/Article/details/gtxlxvwpby.html

du -ah . | sort -rh | head -10
来源：http://dali.ehwqpu.com/Article/details/gtoqeldxub.html

[R63] 内存与进程
来源：http://dali.hnqzz.top/Article/details/gtkswasnyj.html

free -h;  ps aux | grep nginx
来源：http://dali.meibo888.top/Article/details/gtnkfojwlv.html

[R64] 结束进程
来源：http://dali.hongshengwenyu.top/Article/details/gtpitidhpc.html

kill -9 $(pgrep -f app.py)
来源：http://dali.chenzaomai.com/Article/details/gtshhkpffd.html

[R65] 查看端口占用
来源：http://dali.ivvv.top/Article/details/gtjsegyxie.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.yj202588.top/Article/details/gtphfkheqj.html

[R66] 定时任务
来源：http://dali.zycfv.cn/Article/details/gtpvcxxbzk.html

crontab -e;  crontab -l
来源：http://dali.bjfxy.top/Article/details/gtheafyazs.html

[R67] 生成随机十六进制串
来源：http://dali.hnqzz.top/Article/details/gtwwirojhh.html

openssl rand -hex 16
来源：http://dali.sxryk.cn/Article/details/gtztkdwnou.html

[R68] 计算文件校验值
来源：http://dali.zhongyouzk.top/Article/details/gtvllszsmp.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.pycfn.com/Article/details/gtizwnxmkj.html

[R69] 生成随机密码
来源：http://dali.tanke756.top/Article/details/gtxulblvve.html

head -c 16 /dev/urandom | base64
来源：http://dali.cdnleiting.top/Article/details/gtbvyrwrso.html

[R70] 时间戳与互转
来源：http://dali.tian-w.cn/Article/details/gtpkgpldwj.html

date +%s;  date -d @1700000000
来源：http://dali.sweek.top/Article/details/gtmvfsnqyo.html

[R71] 日期格式化
来源：http://dali.mhx1999.top/Article/details/gthuqqzuqi.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.kuanghao11.cn/Article/details/gtljrkxhob.html

[R72] 等待端口就绪
来源：http://dali.xylfe.cn/Article/details/gtmgndrefi.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.cdnleiting.top/Article/details/gtqqynbxdq.html

[R73] 分割大日志
来源：http://dali.yj20258.top/Article/details/gtkgvsqzzy.html

split -l 1000 big.log part_
来源：http://dali.shanyushiyangtech.top/Article/details/gttqjkzvet.html

[R74] 批量重命名
来源：http://dali.ppjwa.cn/Article/details/gtzjqdhfht.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.feifeiyinyue.top/Article/details/gtcjztuyig.html

[R75] 导出环境变量
来源：http://dali.jqgfzy.top/Article/details/gturmzwbge.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.yvedp.cn/Article/details/gttdbgzgnr.html

[R76] 使用临时文件
来源：http://dali.guowangkeji.top/Article/details/gtouyniake.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.gzhubu.top/Article/details/gtkrjlykip.html

[R77] 读取用户输入
来源：http://dali.pengpengdd.cyou/Article/details/gttvnkejhb.html

read -rp "请输入: " ans
来源：http://dali.yj20258888.top/Article/details/gtzuqdazul.html

[R78] 交互式菜单
来源：http://dali.yuanzhike.top/Article/details/gtghpuuxnh.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.nanxinkj.top/Article/details/gtscaovzwg.html

[R79] 解析命令行选项
来源：http://dali.316326.xyz/Article/details/gtxvigorcp.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.daria6918.cn/Article/details/gtfwdkdpdt.html

[R80] 查看脚本执行耗时
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmnliipyw.html

time ./run.sh
来源：http://dali.dashuyun.cn/Article/details/gtrdqpmcmg.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtmmchjlnr.html

S. C / C++ 专题
来源：http://dali.daxiang520.top/Article/details/gtetvarpsb.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtyqpwgcpw.html

[S01] C：Hello World
来源：http://dali.fzhhl.top/Article/details/gtuolaucoy.html

#include <stdio.h>
来源：http://dali.yangfankeji.com/Article/details/gtxjkrgkvw.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhiwuduotai.top/Article/details/gtndvtvgri.html

[S02] C：变量与格式化输出
来源：http://dali.zhaomingkeji.xyz/Article/details/gthakpvmie.html

int a = 10; printf("%d\n", a);
来源：http://dali.chenlongwang.top/Article/details/gtulgxisuf.html

[S03] C：读入整数
来源：http://dali.wangdashe.top/Article/details/gtxjcjpolw.html

int x; scanf("%d", &x);
来源：http://dali.zycfv.cn/Article/details/gtvtngeekm.html

[S04] C：字符串复制
来源：http://dali.hysaishi.cn/Article/details/gtrybmphfm.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.xuanzx.com/Article/details/gtvqckqoss.html

[S05] C：字符串长度
来源：http://dali.cdnleiting.top/Article/details/gtrmqchuwp.html

strlen(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtuqsbxnqt.html

[S06] C：字符串比较
来源：http://dali.jinqigfzy.top/Article/details/gtppezrbxp.html

strcmp(a, b) == 0
来源：http://dali.wangdashe.top/Article/details/gtbxjjholh.html

[S07] C：数组遍历求和
来源：http://dali.xuetiantiany.cn/Article/details/gtjjbzhoud.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.redwolf501.top/Article/details/gtctkalmjl.html

[S08] C：动态内存分配与释放
来源：http://dali.fengsongda.top/Article/details/gtqddariop.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.dashuyun.cn/Article/details/gtbxwnygrm.html

[S09] C：结构体定义与初始化
来源：http://dali.9152youxi.cn/Article/details/gtlvqnsfsb.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.tian-w.cn/Article/details/gtttairyux.html

[S10] C：指针与解引用
来源：http://dali.hfpthk.cn/Article/details/gtokcwcrnw.html

int *p = &a;  *p = 5;
来源：http://dali.xuetiantiany.cn/Article/details/gtalppaygh.html

[S11] C：逐行读文件
来源：http://dali.jinqigufen.top/Article/details/gtfopsyorl.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.tanke756.top/Article/details/gtkwubenwz.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.ybcxt.top/Article/details/gtdfhnntcl.html

fclose(f);
来源：http://dali.guannengcc.top/Article/details/gtqjbrwawy.html

[S12] C：写文件
来源：http://dali.feifeiyinyue.top/Article/details/gtbcbkqcuz.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.yj20258888.top/Article/details/gtarudddbl.html

[S13] C：宏定义
来源：http://dali.zhoulong.xyz/Article/details/gtxcrglyfh.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.jqgfzy.top/Article/details/gtvmblzfcv.html

[S14] C：枚举
来源：http://dali.zhongyouzk.top/Article/details/gtbjpuheqg.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.cqqwz.cn/Article/details/gtbykudnaj.html

[S15] C：类型转换
来源：http://dali.tian-w.cn/Article/details/gtksjvtybb.html

(double) a / b
来源：http://dali.hywenlv.cn/Article/details/gtxxpxnblt.html

[S16] C：位操作置位
来源：http://dali.9152youxi.cn/Article/details/gteaxzzapz.html

x |= (1 << 3);
来源：http://dali.hammf.cn/Article/details/gtlkmmzgfb.html

[S17] C：安全拼接字符串
来源：http://dali.jqgfzy.top/Article/details/gtrzsphkef.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.daxiang520.top/Article/details/gttfidnxok.html

[S18] C：命令行参数
来源：http://dali.smart0.xyz/Article/details/gtnoemggyu.html

int main(int argc, char **argv)
来源：http://dali.shangyingyoupin.top/Article/details/gtisohzcth.html

[S19] C：快速排序
来源：http://dali.hywenlv.cn/Article/details/gtwafigdli.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpuswiiqt.html

[S20] C：二分查找
来源：http://dali.ehwqpu.com/Article/details/gtvvkbzfhv.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.hfpthk.cn/Article/details/gtcglcpgtx.html

[S21] C：字符类别判断
来源：http://dali.feifeiyinyue.top/Article/details/gturqlsmjx.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.yangfankeji.com/Article/details/gtxjeuswik.html

[S22] C：字符串转数字
来源：http://dali.gotoacloud.top/Article/details/gtdcvgptvi.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.shanyushiyangtech.top/Article/details/gtaombgpuc.html

[S23] C：随机数
来源：http://dali.havefunace.top/Article/details/gtechdkoyv.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.xylfe.cn/Article/details/gtzmpmgusz.html

[S24] C：获取本地时间
来源：http://dali.aizwys.cn/Article/details/gthvkjhpio.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.chenzaomai.com/Article/details/gthykidsmw.html

[S25] C：内存拷贝
来源：http://dali.jinqigfzy.top/Article/details/gtwhtkafsa.html

memcpy(dst, src, n);
来源：http://dali.fzhhl.top/Article/details/gtfljwxylw.html

[S26] C：内存清零
来源：http://dali.jqgufenzy.top/Article/details/gtxkrvdjru.html

memset(a, 0, sizeof a);
来源：http://dali.zhengqikj.top/Article/details/gtxlrdvbfz.html

[S27] C：定义常量
来源：http://dali.9152youxi.cn/Article/details/gtpneggjdf.html

const double PI = 3.14159;
来源：http://dali.meibo888.top/Article/details/gtnijmonrt.html

[S28] C：静态变量
来源：http://dali.chenzaomai.com/Article/details/gtorqhlfvu.html

static int counter = 0;
来源：http://dali.nanxuanxn.top/Article/details/gtlfsygomk.html

[S29] C：变参函数
来源：http://dali.sysykeji.top/Article/details/gtdkcerold.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.gotoacloud.top/Article/details/gtpippdmom.html

[S30] C：头文件保护
来源：http://dali.gaohongyu789.top/Article/details/gtaoqvxkxu.html

#ifndef X_H
来源：http://dali.gzhubu.top/Article/details/gthodeatby.html

#define X_H
来源：http://dali.0kj1m.cn/Article/details/gtlxkzlgiy.html

#endif
来源：http://dali.ivvv.top/Article/details/gtncrnsrvz.html

[S31] C++：Hello World
来源：http://dali.316326.xyz/Article/details/gtimjxldfe.html

#include <iostream>
来源：http://dali.shangyingyoupin.top/Article/details/gtktvynsmw.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.cucudq.cn/Article/details/gttwfmtnnz.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gthbxnowmx.html

std::string s = "hi";  s += "!";
来源：http://dali.hammf.cn/Article/details/gtdimarhpo.html

[S33] C++：vector 增删
来源：http://dali.0kj1m.cn/Article/details/gtravssqog.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gtkfnffrjg.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gtsjnwhpfw.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.cheryme.top/Article/details/gtxfmwegls.html

[S35] C++：map
来源：http://dali.gotoacloud.top/Article/details/gtvfdgodlc.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.chenzaomai.com/Article/details/gttcmkwzyb.html

[S36] C++：unordered_map
来源：http://dali.yanxiufei.cn/Article/details/gtvehzcwkg.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yuxming.cn/Article/details/gtjcmqyltc.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gtsknpjexu.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.xylfe.cn/Article/details/gtixxznctu.html

[S38] C++：排序
来源：http://dali.dashuyun.cn/Article/details/gthvmycswa.html

std::sort(v.begin(), v.end());
来源：http://dali.pengpengdd.cyou/Article/details/gtomvjezzr.html

[S39] C++：自定义比较器排序
来源：http://dali.pengpengdd.cyou/Article/details/gtfpwrqsdo.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhengqikj.top/Article/details/gtqabezpcx.html

[S40] C++：查找元素
来源：http://dali.daxiang520.top/Article/details/gtepwwhtun.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.sysykeji.top/Article/details/gturwvqfiz.html

[S41] C++：类与构造函数
来源：http://dali.jianghu66.top/Article/details/gtvecaffut.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.shanyushiyangtech.top/Article/details/gtykbecile.html

[S42] C++：继承与虚函数
来源：http://dali.xuetiantiany.cn/Article/details/gtdgvbblue.html

class B : public Base { public: void f() override {} };
来源：http://dali.daxiang520.top/Article/details/gtjwndfpcv.html

[S43] C++：智能指针
来源：http://dali.gaohongyu789.top/Article/details/gtcsineygw.html

auto p = std::make_unique<int>(5);
来源：http://dali.hywenlv.cn/Article/details/gtzvtulhwp.html

[S44] C++：引用传参
来源：http://dali.pycfn.com/Article/details/gtspekuxfi.html

void inc(int &x) { ++x; }
来源：http://dali.dashuyun.cn/Article/details/gtkyiqjlax.html

[S45] C++：lambda
来源：http://dali.jinqigfzy.top/Article/details/gtgjwhvfkd.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.cheryme.top/Article/details/gtmpygixes.html

[S46] C++：函数模板
来源：http://dali.shanyushiyangkeji.top/Article/details/gtchanmkdi.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.shzxlz.cn/Article/details/gtpqwwhmmy.html

[S47] C++：结构化绑定遍历
来源：http://dali.chenlongwang.top/Article/details/gtailuatdw.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.ivvv.top/Article/details/gtuobkeytg.html

[S48] C++：逐行读文件
来源：http://dali.ydzc1.top/Article/details/gtcwpddpar.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.tanke756.top/Article/details/gtudslsbyn.html

while (std::getline(in, line)) { }
来源：http://dali.snrcjt.cn/Article/details/gtyrwajjdc.html

[S49] C++：写文件
来源：http://dali.ehwqpu.com/Article/details/gtjnbltpij.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.pengpengdd.cyou/Article/details/gtvtoequoi.html

[S50] C++：格式化数字
来源：http://dali.andypj.xyz/Article/details/gtnwxpicio.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.gotoacloud.top/Article/details/gtfjcpekwx.html

[S51] C++：显式类型转换
来源：http://dali.0kj1m.cn/Article/details/gtyudpcunx.html

static_cast<double>(a) / b
来源：http://dali.daxiang520.top/Article/details/gtmwcxstqw.html

[S52] C++：const 与 noexcept
来源：http://dali.aizwys.cn/Article/details/gtntfhokxr.html

int size() const noexcept { return n_; }
来源：http://dali.vqdsnc.cn/Article/details/gtqjkxhizq.html

[S53] C++：移动语义
来源：http://dali.9152youxi.cn/Article/details/gtymruhmjv.html

std::vector<int> w = std::move(v);
来源：http://dali.zycfv.cn/Article/details/gtspmxphjj.html

[S54] C++：异常处理
来源：http://dali.zycfv.cn/Article/details/gtqcrdkoct.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.pycfn.com/Article/details/gthgzqdyvq.html

[S55] C++：结构化绑定
来源：http://dali.gogol.net.cn/Article/details/gtdcvyrwve.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.xuanzx.com/Article/details/gtqbbgfjwj.html

[S56] C++：optional
来源：http://dali.birdmap.top/Article/details/gtoxrmaqmd.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhengqikj.top/Article/details/gthhlbuxzf.html

[S57] C++：编译期常量
来源：http://dali.zycfv.cn/Article/details/gtcogdadoa.html

constexpr int N = 10;
来源：http://dali.pengpengdd.cyou/Article/details/gtncagvsfl.html

[S58] C++：命名空间
来源：http://dali.shangyingyoupin.top/Article/details/gtjwksiltz.html

namespace ns { int f() { return 1; } }
来源：http://dali.chenjidiqi.icu/Article/details/gtxjfjxidz.html

[S59] C++：静态断言
来源：http://dali.hywenlv.cn/Article/details/gtmhlucqlx.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.ydzc1.top/Article/details/gtunofihkr.html

[S60] C++：遍历并删除元素
来源：http://dali.dashuyun.cn/Article/details/gtxrgypjlj.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.chenzaomai.com/Article/details/gtvtcevpnr.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtmqjwxdaz.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.cdnleiting.top/Article/details/gtnralzxps.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtgjkzkxoa.html

[T01] Kotlin：Hello World
来源：http://dali.zhixingplan.top/Article/details/gtdiefvqdf.html

println("Hello")
来源：http://dali.sxryk.cn/Article/details/gtynzyjyyp.html

[T02] Kotlin：变量
来源：http://dali.gzhubu.top/Article/details/gtrlnqavia.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.meibo888.top/Article/details/gtgommiizd.html

[T03] Kotlin：字符串模板
来源：http://dali.nanxinkj.top/Article/details/gttfmeomkc.html

"值: $b"
来源：http://dali.chenjidiqi.icu/Article/details/gtnmsetqvm.html

[T04] Kotlin：空安全
来源：http://dali.ppjwa.cn/Article/details/gtrzwcynmt.html

val n: String? = null;  n?.length
来源：http://dali.sysykeji.top/Article/details/gturypqylw.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gtcrehkaxf.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.316326.xyz/Article/details/gtefomrsjt.html

[T06] Kotlin：集合映射
来源：http://dali.haohaochexian.top/Article/details/gtjsogjdir.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.gzhubu.top/Article/details/gtwgqxrlwl.html

[T07] Kotlin：集合过滤
来源：http://dali.yj202588.top/Article/details/gtoimcjgei.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.wangdashe.top/Article/details/gtijbuojiq.html

[T08] Kotlin：数据类
来源：http://dali.hfpthk.cn/Article/details/gtdpavgkam.html

data class User(val name: String, val age: Int)
来源：http://dali.nanxinkj.top/Article/details/gtuguurygh.html

[T09] Kotlin：扩展函数
来源：http://dali.wangdashe.top/Article/details/gtzthprgld.html

fun String.exclaim() = this + "!"
来源：http://dali.chenjidiqi.icu/Article/details/gtmvqingbu.html

[T10] Kotlin：默认参数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtolvxjndo.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.chenzaomai.com/Article/details/gtxjfcjdsu.html

[T11] Kotlin：协程
来源：http://dali.quarkkingdee.top/Article/details/gtxyjumkfw.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.aibaodan.cn/Article/details/gtrujcvkhc.html

[T12] Kotlin：解构声明
来源：http://dali.hysaishi.cn/Article/details/gtvejzdxht.html

val (a, b) = Pair(1, 2)
来源：http://dali.yj20258888.top/Article/details/gthtpogzxy.html

[T13] Kotlin：只读 Map
来源：http://dali.sufxvd.cn/Article/details/gtrlbjfbxa.html

val m = mapOf("a" to 1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtwxlmszsw.html

[T14] Kotlin：循环
来源：http://dali.kuanghao11.cn/Article/details/gtoyeztohm.html

for (i in 1..10) println(i)
来源：http://dali.gzhubu.top/Article/details/gtplzcjvxx.html

[T15] Kotlin：接口
来源：http://dali.yuxming.cn/Article/details/gtyuhrvslb.html

interface Shape { fun area(): Double }
来源：http://dali.vqdsnc.cn/Article/details/gtwlhacsea.html

[T16] Swift：Hello World
来源：http://dali.hfpthk.cn/Article/details/gtgmyswomk.html

print("Hello")
来源：http://dali.fengsongda.top/Article/details/gtbafsxzrb.html

[T17] Swift：变量与常量
来源：http://dali.hfpthk.cn/Article/details/gtoagetejo.html

var a = 1;  let b = 2
来源：http://dali.chenzaomai.com/Article/details/gtxjmnfneo.html

[T18] Swift：字符串插值
来源：http://dali.xylfe.cn/Article/details/gtywkligmn.html

"值: \(b)"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvzmgjjfd.html

[T19] Swift：可选绑定
来源：http://dali.316326.xyz/Article/details/gtmujwkmov.html

if let n = opt { print(n) }
来源：http://dali.c1oappe.top/Article/details/gtkvsbhedb.html

[T20] Swift：数组操作
来源：http://dali.zhixingplan.top/Article/details/gtczvtnipy.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.yangfankeji.com/Article/details/gthovevnrz.html

[T21] Swift：遍历
来源：http://dali.haohaochexian.top/Article/details/gthytnluqk.html

for x in a { print(x) }
来源：http://dali.ydzc1.top/Article/details/gtucejdhpp.html

[T22] Swift：字典
来源：http://dali.daria6918.cn/Article/details/gtvvgqpssn.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.fengsongda.top/Article/details/gthekkipku.html

[T23] Swift：函数
来源：http://dali.iojbl.cn/Article/details/gtwwmvujrs.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.ydzc1.top/Article/details/gtwctpijyu.html

[T24] Swift：闭包
来源：http://dali.gogol.net.cn/Article/details/gtbukcdqlh.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gtdozgukes.html

[T25] Swift：结构体
来源：http://dali.ehwqpu.com/Article/details/gtuwxpgzmg.html

struct P { var x: Int }
来源：http://dali.hongshengwenyu.top/Article/details/gthopemjlq.html

[T26] Swift：类与重写
来源：http://dali.zhoulong.xyz/Article/details/gtjnvpyqzr.html

class A: Base { override func f() {} }
来源：http://dali.daria6918.cn/Article/details/gtujmrgjkr.html

[T27] Swift：错误处理
来源：http://dali.zhoulong.xyz/Article/details/gtfzxqcbsl.html

do { try f() } catch { print(error) }
来源：http://dali.pycfn.com/Article/details/gtcdhamlyw.html

[T28] Swift：枚举
来源：http://dali.guannengcc.top/Article/details/gtdyudprtl.html

enum Color { case red, green }
来源：http://dali.cucudq.cn/Article/details/gtuhdsykaj.html

[T29] Swift：guard 提前返回
来源：http://dali.daria6918.cn/Article/details/gtkaadsbig.html

guard let x = opt else { return }
来源：http://dali.yuanzhike.top/Article/details/gtgrphnqli.html

[T30] Swift：协议
来源：http://dali.jianghu66.top/Article/details/gttmlttyel.html

protocol Shape { func area() -> Double }
来源：http://dali.xuanzx.com/Article/details/gtwmlybcvu.html

[T31] Lua：Hello World
来源：http://dali.zhongyouzk.top/Article/details/gtnthmxogr.html

print("Hello")
来源：http://dali.zhongyouzk.top/Article/details/gtlpihelsa.html

[T32] Lua：局部变量
来源：http://dali.nwbrower.top/Article/details/gtnzvcjpai.html

local a = 1
来源：http://dali.sysykeji.top/Article/details/gtfdhntije.html

[T33] Lua：表（数组）
来源：http://dali.yj20258888.top/Article/details/gthtovmuyq.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.fzhhl.top/Article/details/gtmncwujfr.html

[T34] Lua：遍历表
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsnxrjuji.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.jyoumei.cn/Article/details/gtmihloyio.html

[T35] Lua：字典表
来源：http://dali.svipenyu.cn/Article/details/gtplvrkqbw.html

local d = { a = 1 };  d.b = 2
来源：http://dali.meibo888.top/Article/details/gtlsfmvhhx.html

[T36] Lua：函数
来源：http://dali.nanxinkj.top/Article/details/gttnxdvcuy.html

function add(a, b) return a + b end
来源：http://dali.haohaochexian.top/Article/details/gtpuxpoaal.html

[T37] Lua：字符串拼接
来源：http://dali.ydzc1.top/Article/details/gtknaseldb.html

"a" .. "b"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtycbekusn.html

[T38] Lua：条件
来源：http://dali.sysykeji.top/Article/details/gtxmdizmws.html

if x > 0 then print("正") end
来源：http://dali.ehwqpu.com/Article/details/gtzrsrjfsm.html

[T39] Lua：模式匹配
来源：http://dali.hywenlv.cn/Article/details/gthzkhogko.html

string.find(s, "%d+")
来源：http://dali.sysykeji.top/Article/details/gtjquzftgt.html

[T40] Lua：元表
来源：http://dali.hnqzz.top/Article/details/gtvuyjjvxd.html

setmetatable({}, { __index = base })
来源：http://dali.yanxiufei.cn/Article/details/gthwdicaod.html

[T41] Perl：Hello World
来源：http://dali.0kj1m.cn/Article/details/gtkuxtwnrb.html

print "Hello\n";
来源：http://dali.shuidangran.top/Article/details/gtuarhsoie.html

[T42] Perl：变量类型
来源：http://dali.cdnleiting.top/Article/details/gtaamouaoy.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.cashguo.top/Article/details/gtxemtlydh.html

[T43] Perl：字符串插值
来源：http://dali.shangyingyoupin.top/Article/details/gtnfnjlhis.html

"值: $a"
来源：http://dali.shzxlz.cn/Article/details/gtgvxytlgh.html

[T44] Perl：条件
来源：http://dali.hfpthk.cn/Article/details/gtjxhbhpuj.html

if ($a > 0) { print "正"; }
来源：http://dali.ybcxt.top/Article/details/gtlcnyfdbb.html

[T45] Perl：数组遍历
来源：http://dali.jinqigufen.top/Article/details/gthwtpjpax.html

for my $x (@arr) { print $x; }
来源：http://dali.cqqwz.cn/Article/details/gtzntwkzyi.html

[T46] Perl：哈希操作
来源：http://dali.nanxuanxn.top/Article/details/gtfgloqxym.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.sufxvd.cn/Article/details/gtiuuoshhl.html

[T47] Perl：正则捕获
来源：http://dali.hammf.cn/Article/details/gthebxkxqa.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.dashuyun.cn/Article/details/gtihmdpyxj.html

[T48] Perl：正则替换
来源：http://dali.zycfv.cn/Article/details/gtjhaabqzo.html

$s =~ s/old/new/g;
来源：http://dali.zdqjudy.top/Article/details/gtaqfwhsvt.html

[T49] Perl：函数
来源：http://dali.tianlin.xyz/Article/details/gtttlgilia.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.jlsjyb.cn/Article/details/gtlmblfujk.html

[T50] Perl：逐行读文件
来源：http://dali.smart0.xyz/Article/details/gthhxuyfbb.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.jyoumei.cn/Article/details/gtncrgdhjp.html


<!-- 参考信息 -->