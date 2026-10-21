代发 wailian999

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.jianghu66.top/Article/details/gtfplxwfgd.html

[R50] awk 求和
来源：http://dali.meibo888.top/Article/details/gthtdlnnvy.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.gogol.net.cn/Article/details/gtpaqeckuu.html

[R51] 排序去重取前几
来源：http://dali.ydzc1.top/Article/details/gtvwdigzyc.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.wangshuangyany.cn/Article/details/gtousmqiom.html

[R52] 统计行数
来源：http://dali.svipenyu.cn/Article/details/gthflenidc.html

wc -l a.txt
来源：http://dali.xylfe.cn/Article/details/gtkbanjkub.html

[R53] 查看文件头与实时尾
来源：http://dali.ppjwa.cn/Article/details/gtopssmgdl.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.316326.xyz/Article/details/gtubwbvfsc.html

[R54] 比较两个文件
来源：http://dali.cqqwz.cn/Article/details/gttgoimtyk.html

diff a.txt b.txt
来源：http://dali.jlsjyb.cn/Article/details/gtdjxhfzch.html

[R55] 压缩与解压
来源：http://dali.jianghu66.top/Article/details/gtkshbxbms.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.sysykeji.top/Article/details/gttjpxnlnz.html

[R56] 远程拷贝
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqkzasbqf.html

scp file user@host:/path/
来源：http://dali.daxiang520.top/Article/details/gthcxwexfy.html

[R57] 远程执行命令
来源：http://dali.0kj1m.cn/Article/details/gtpclvmqqx.html

ssh user@host 'uptime'
来源：http://dali.yonumen.top/Article/details/gtchgjyxbn.html

[R58] 下载文件
来源：http://dali.xziqi.cn/Article/details/gtfbhcosta.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.ydzc1.top/Article/details/gtehedknng.html

[R59] 发 POST JSON
来源：http://dali.zdqjudy.top/Article/details/gtrfgtwpww.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.c1oappe.top/Article/details/gtmekxppkp.html

[R60] 只看 HTTP 状态码
来源：http://dali.andypj.xyz/Article/details/gttekunggt.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.yvedp.cn/Article/details/gtknjpgnhr.html

[R61] 磁盘占用
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmiexaiwm.html

df -h;  du -sh *
来源：http://dali.cheryme.top/Article/details/gtqbzsanjx.html

[R62] 找最占空间的文件
来源：http://dali.jiagoushi.top/Article/details/gtqrieslsr.html

du -ah . | sort -rh | head -10
来源：http://dali.bjfxy.top/Article/details/gtqhhrcndb.html

[R63] 内存与进程
来源：http://dali.jinqigufen.top/Article/details/gtkusbikyj.html

free -h;  ps aux | grep nginx
来源：http://dali.jyoumei.cn/Article/details/gtxicvpial.html

[R64] 结束进程
来源：http://dali.haohaochexian.top/Article/details/gtfapnbyqs.html

kill -9 $(pgrep -f app.py)
来源：http://dali.andypj.xyz/Article/details/gtipesknzf.html

[R65] 查看端口占用
来源：http://dali.aibaodan.cn/Article/details/gtzomprzmu.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.tianlin.xyz/Article/details/gtgutdtzyj.html

[R66] 定时任务
来源：http://dali.chenjidiqi.icu/Article/details/gtxrbdhzjo.html

crontab -e;  crontab -l
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbtmilksq.html

[R67] 生成随机十六进制串
来源：http://dali.jqgufenzy.top/Article/details/gtlnzkzuzn.html

openssl rand -hex 16
来源：http://dali.yvedp.cn/Article/details/gtypotqnyy.html

[R68] 计算文件校验值
来源：http://dali.pycfn.com/Article/details/gtedrqzzlo.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.vqdsnc.cn/Article/details/gtyqeubmai.html

[R69] 生成随机密码
来源：http://dali.wangshuangyany.cn/Article/details/gtdyhcugcd.html

head -c 16 /dev/urandom | base64
来源：http://dali.jinghuilouyu.cn/Article/details/gtyvwyfbst.html

[R70] 时间戳与互转
来源：http://dali.chenjidiqi.icu/Article/details/gtrvgrycdw.html

date +%s;  date -d @1700000000
来源：http://dali.meibo888.top/Article/details/gtviirtfrs.html

[R71] 日期格式化
来源：http://dali.9152youxi.cn/Article/details/gtscgiebzn.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.dashuyun.cn/Article/details/gtqgtjgezw.html

[R72] 等待端口就绪
来源：http://dali.jianghu66.top/Article/details/gtsmhfnoar.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlacsbcrj.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gtwucjikbq.html

split -l 1000 big.log part_
来源：http://dali.haohaochexian.top/Article/details/gttliimcfc.html

[R74] 批量重命名
来源：http://dali.9152youxi.cn/Article/details/gtjxnoodlr.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zdqjudy.top/Article/details/gtpiqlfopz.html

[R75] 导出环境变量
来源：http://dali.yueranfly.top/Article/details/gthnflozoe.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.tianlin.xyz/Article/details/gtxczewsus.html

[R76] 使用临时文件
来源：http://dali.wangdashe.top/Article/details/gtsbfzzfaa.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.xuetiantiany.cn/Article/details/gtduhnmkki.html

[R77] 读取用户输入
来源：http://dali.tianlin.xyz/Article/details/gtotatgusk.html

read -rp "请输入: " ans
来源：http://dali.yangfankeji.com/Article/details/gtofrcublt.html

[R78] 交互式菜单
来源：http://dali.cucudq.cn/Article/details/gtvvhabsan.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.tanke756.top/Article/details/gtxfizceov.html

[R79] 解析命令行选项
来源：http://dali.guowangkeji.top/Article/details/gthigcvqum.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.iojbl.cn/Article/details/gtpoqhfnbt.html

[R80] 查看脚本执行耗时
来源：http://dali.sufxvd.cn/Article/details/gtkdmvamid.html

time ./run.sh
来源：http://dali.dianchejie.cn/Article/details/gtvkijampy.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtqryuwqaf.html

S. C / C++ 专题
来源：http://dali.mhx1999.top/Article/details/gtuwqdvbkd.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtegmlyqhb.html

[S01] C：Hello World
来源：http://dali.aibaodan.cn/Article/details/gtfeiehqom.html

#include <stdio.h>
来源：http://dali.ehwqpu.com/Article/details/gtblcseigr.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.mhx1999.top/Article/details/gtfhhainou.html

[S02] C：变量与格式化输出
来源：http://dali.aizwys.cn/Article/details/gtthhjgjpi.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhengqikj.top/Article/details/gtycroahdg.html

[S03] C：读入整数
来源：http://dali.jinyuanbaomall.cn/Article/details/gthonyznvs.html

int x; scanf("%d", &x);
来源：http://dali.yangfankeji.com/Article/details/gtelebsvdn.html

[S04] C：字符串复制
来源：http://dali.tian-w.cn/Article/details/gtyqztsruh.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.sysykeji.top/Article/details/gtkhxggbuh.html

[S05] C：字符串长度
来源：http://dali.zhengqikj.top/Article/details/gtieobkpow.html

strlen(s)
来源：http://dali.cdnleiting.top/Article/details/gtwltvcvwa.html

[S06] C：字符串比较
来源：http://dali.yj20258888.top/Article/details/gtmvzhrhxu.html

strcmp(a, b) == 0
来源：http://dali.ppjwa.cn/Article/details/gtwvocptug.html

[S07] C：数组遍历求和
来源：http://dali.smart0.xyz/Article/details/gtdyhsvdcp.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.gotoacloud.top/Article/details/gthrhnqswb.html

[S08] C：动态内存分配与释放
来源：http://dali.hongshengwenyu.top/Article/details/gtkwlcrtjx.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.wangshuangyany.cn/Article/details/gtcblfenyl.html

[S09] C：结构体定义与初始化
来源：http://dali.guannengcc.top/Article/details/gtwriudvzs.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.smart0.xyz/Article/details/gtjxijntkx.html

[S10] C：指针与解引用
来源：http://dali.yuxming.cn/Article/details/gtwqmznllq.html

int *p = &a;  *p = 5;
来源：http://dali.haohaochexian.top/Article/details/gtffmyjkzq.html

[S11] C：逐行读文件
来源：http://dali.vqdsnc.cn/Article/details/gttkeugzmc.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.guannengcc.top/Article/details/gtxtwgebno.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.jlsjyb.cn/Article/details/gtlykqhjri.html

fclose(f);
来源：http://dali.xylfe.cn/Article/details/gtounaqiyi.html

[S12] C：写文件
来源：http://dali.yuxming.cn/Article/details/gthfbeiyar.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.havefunace.top/Article/details/gtogpoiojn.html

[S13] C：宏定义
来源：http://dali.zhiwuduotai.top/Article/details/gtnrecaxmc.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.nwbrower.top/Article/details/gtyepdlefn.html

[S14] C：枚举
来源：http://dali.ehwqpu.com/Article/details/gtuejznvgq.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhixingplan.top/Article/details/gtjzbtqspy.html

[S15] C：类型转换
来源：http://dali.daria6918.cn/Article/details/gtrhtugldt.html

(double) a / b
来源：http://dali.nwbrower.top/Article/details/gtjhkixfwt.html

[S16] C：位操作置位
来源：http://dali.xuetiantiany.cn/Article/details/gtywtgaanc.html

x |= (1 << 3);
来源：http://dali.chenjidiqi.icu/Article/details/gtemrhlsqw.html

[S17] C：安全拼接字符串
来源：http://dali.jinqigfzy.top/Article/details/gtoklvfxzv.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.316326.xyz/Article/details/gtjrvrlwhw.html

[S18] C：命令行参数
来源：http://dali.cashguo.top/Article/details/gtudpmbauz.html

int main(int argc, char **argv)
来源：http://dali.smart0.xyz/Article/details/gtoiuiwysv.html

[S19] C：快速排序
来源：http://dali.hfpthk.cn/Article/details/gtrmygxhdl.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.yanxiufei.cn/Article/details/gtgtrdvrjw.html

[S20] C：二分查找
来源：http://dali.xuanzx.com/Article/details/gtgrurlnze.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.sufxvd.cn/Article/details/gtercxlvyw.html

[S21] C：字符类别判断
来源：http://dali.cucudq.cn/Article/details/gtkwoqwuba.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.yanxiufei.cn/Article/details/gtmjxkwnwv.html

[S22] C：字符串转数字
来源：http://dali.smart0.xyz/Article/details/gtjtvrimkz.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvcmnnitq.html

[S23] C：随机数
来源：http://dali.zhengqikj.top/Article/details/gttfxpwasd.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.shanyushiyangtech.top/Article/details/gtgmkuvisw.html

[S24] C：获取本地时间
来源：http://dali.feifeiyinyue.top/Article/details/gtguetdsco.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.ehwqpu.com/Article/details/gtjcjqudwk.html

[S25] C：内存拷贝
来源：http://dali.hywenlv.cn/Article/details/gtnsugwurg.html

memcpy(dst, src, n);
来源：http://dali.hnqzz.top/Article/details/gtbdvilyev.html

[S26] C：内存清零
来源：http://dali.fengsongda.top/Article/details/gtivhxkdxm.html

memset(a, 0, sizeof a);
来源：http://dali.hongshengwenyu.top/Article/details/gtudgrldsl.html

[S27] C：定义常量
来源：http://dali.zhiwuduotai.top/Article/details/gtwxlllffu.html

const double PI = 3.14159;
来源：http://dali.andypj.xyz/Article/details/gtcihnhokk.html

[S28] C：静态变量
来源：http://dali.haohaochexian.top/Article/details/gtmnrcthgt.html

static int counter = 0;
来源：http://dali.mhx1999.top/Article/details/gthsejdcfw.html

[S29] C：变参函数
来源：http://dali.nanxuanxn.top/Article/details/gtnjvgfdqg.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhiwuduotai.top/Article/details/gtkwjkehbq.html

[S30] C：头文件保护
来源：http://dali.kuanghao11.cn/Article/details/gtjqgwtche.html

#ifndef X_H
来源：http://dali.316326.xyz/Article/details/gtgbkpfrot.html

#define X_H
来源：http://dali.yuxming.cn/Article/details/gthitukesw.html

#endif
来源：http://dali.9152youxi.cn/Article/details/gtmgxlgoxv.html

[S31] C++：Hello World
来源：http://dali.yuanzhike.top/Article/details/gtawpdlzlx.html

#include <iostream>
来源：http://dali.sxryk.cn/Article/details/gtqxjoatfh.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.c1oappe.top/Article/details/gtmcfzqywu.html

[S32] C++：字符串
来源：http://dali.svipenyu.cn/Article/details/gtwwlvpwzq.html

std::string s = "hi";  s += "!";
来源：http://dali.gzhubu.top/Article/details/gtszhtoosv.html

[S33] C++：vector 增删
来源：http://dali.tian-w.cn/Article/details/gtwcpbtxfs.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.hongshengwenyu.top/Article/details/gtlpsxhmrj.html

[S34] C++：遍历 vector
来源：http://dali.jinqigufen.top/Article/details/gtrvhyllrd.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.hysaishi.cn/Article/details/gtxlhngoif.html

[S35] C++：map
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjcuvacst.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.cucudq.cn/Article/details/gtbpfilaae.html

[S36] C++：unordered_map
来源：http://dali.gotoacloud.top/Article/details/gtxzlpgjun.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.gaohongyu789.top/Article/details/gtvwkbvkpa.html

[S37] C++：set
来源：http://dali.yanxiufei.cn/Article/details/gtglljtrit.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.dashuyun.cn/Article/details/gtnlutwhkv.html

[S38] C++：排序
来源：http://dali.jinqigfzy.top/Article/details/gtbbydtwev.html

std::sort(v.begin(), v.end());
来源：http://dali.xuanzx.com/Article/details/gtvzgfzeza.html

[S39] C++：自定义比较器排序
来源：http://dali.andypj.xyz/Article/details/gtpnikcodp.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.yueranfly.top/Article/details/gtwcbrsznp.html

[S40] C++：查找元素
来源：http://dali.iojbl.cn/Article/details/gtjibaojgd.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.tian-w.cn/Article/details/gtpxrseewa.html

[S41] C++：类与构造函数
来源：http://dali.yj202588.top/Article/details/gtzuojgudi.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.snrcjt.cn/Article/details/gtdforftpv.html

[S42] C++：继承与虚函数
来源：http://dali.9152youxi.cn/Article/details/gtwganjxyc.html

class B : public Base { public: void f() override {} };
来源：http://dali.yuxming.cn/Article/details/gtvhjjlmpu.html

[S43] C++：智能指针
来源：http://dali.jinghuilouyu.cn/Article/details/gtmgmirvvc.html

auto p = std::make_unique<int>(5);
来源：http://dali.xuetiantiany.cn/Article/details/gtfankzojp.html

[S44] C++：引用传参
来源：http://dali.jqgufenzy.top/Article/details/gtstfkneni.html

void inc(int &x) { ++x; }
来源：http://dali.shangyingyoupin.top/Article/details/gtsafwimub.html

[S45] C++：lambda
来源：http://dali.cucudq.cn/Article/details/gtzodbsthv.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.ehwqpu.com/Article/details/gtltqnajvg.html

[S46] C++：函数模板
来源：http://dali.cashguo.top/Article/details/gtfqilexpp.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.tian-w.cn/Article/details/gtldrjnfeg.html

[S47] C++：结构化绑定遍历
来源：http://dali.jiagoushi.top/Article/details/gtrzcavmfi.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.jianghu66.top/Article/details/gtrchocxkk.html

[S48] C++：逐行读文件
来源：http://dali.xylfe.cn/Article/details/gteyskdvch.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.kuanghao11.cn/Article/details/gtfvcmbzhe.html

while (std::getline(in, line)) { }
来源：http://dali.vqdsnc.cn/Article/details/gtpoghzdku.html

[S49] C++：写文件
来源：http://dali.hammf.cn/Article/details/gtqxtddnci.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.hnxiangtu.top/Article/details/gtjixxtynt.html

[S50] C++：格式化数字
来源：http://dali.0kj1m.cn/Article/details/gtvabdhcsd.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.shangyingyoupin.top/Article/details/gtjddwpoqj.html

[S51] C++：显式类型转换
来源：http://dali.xinyue.icu/Article/details/gtzbscxqay.html

static_cast<double>(a) / b
来源：http://dali.mhx1999.top/Article/details/gtgxxliwnv.html

[S52] C++：const 与 noexcept
来源：http://dali.hnqzz.top/Article/details/gtpmgndegb.html

int size() const noexcept { return n_; }
来源：http://dali.yuxming.cn/Article/details/gtmsahcmek.html

[S53] C++：移动语义
来源：http://dali.hysaishi.cn/Article/details/gtjstdfqhn.html

std::vector<int> w = std::move(v);
来源：http://dali.xuanzx.com/Article/details/gtibdfeyes.html

[S54] C++：异常处理
来源：http://dali.ppjwa.cn/Article/details/gtriulgyid.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.hammf.cn/Article/details/gttzsfiyid.html

[S55] C++：结构化绑定
来源：http://dali.xziqi.cn/Article/details/gthifnynyj.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.sxryk.cn/Article/details/gtrzhpymni.html

[S56] C++：optional
来源：http://dali.wangdashe.top/Article/details/gtjldetsnd.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtpbdpyubz.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gtwintqlsr.html

constexpr int N = 10;
来源：http://dali.chenzaomai.com/Article/details/gtaigqbtyt.html

[S58] C++：命名空间
来源：http://dali.tianlin.xyz/Article/details/gtruucynxd.html

namespace ns { int f() { return 1; } }
来源：http://dali.bjfxy.top/Article/details/gteiigzesa.html

[S59] C++：静态断言
来源：http://dali.shanyushiyangtech.top/Article/details/gtgdivckbp.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.guowangkeji.top/Article/details/gtaejldcmw.html

[S60] C++：遍历并删除元素
来源：http://dali.zhengqikj.top/Article/details/gtcbxravnz.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.jianghu66.top/Article/details/gtwxkadhrp.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtlxhpcqed.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.xuanzx.com/Article/details/gtidjdjsdi.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtvnhlqlwv.html

[T01] Kotlin：Hello World
来源：http://dali.cheryme.top/Article/details/gtpflkgzbq.html

println("Hello")
来源：http://dali.jyoumei.cn/Article/details/gtltvoogsm.html

[T02] Kotlin：变量
来源：http://dali.yj20258888.top/Article/details/gtuuuvdayc.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.hysaishi.cn/Article/details/gtnsnezisc.html

[T03] Kotlin：字符串模板
来源：http://dali.zdqjudy.top/Article/details/gtdsgnrlmc.html

"值: $b"
来源：http://dali.pengpengdd.cyou/Article/details/gtdzqezibv.html

[T04] Kotlin：空安全
来源：http://dali.chenjidiqi.icu/Article/details/gtwcvrrxkl.html

val n: String? = null;  n?.length
来源：http://dali.ehwqpu.com/Article/details/gtdoktgiep.html

[T05] Kotlin：when 表达式
来源：http://dali.cashguo.top/Article/details/gtxrhnpcbr.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.hnqzz.top/Article/details/gtfuysdrfq.html

[T06] Kotlin：集合映射
来源：http://dali.zhengqikj.top/Article/details/gtpmtkxtra.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.hywenlv.cn/Article/details/gtotcjdvlv.html

[T07] Kotlin：集合过滤
来源：http://dali.cdnleiting.top/Article/details/gtvwbtxlat.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.hysaishi.cn/Article/details/gtnfxqbbgk.html

[T08] Kotlin：数据类
来源：http://dali.jiagoushi.top/Article/details/gthhycubou.html

data class User(val name: String, val age: Int)
来源：http://dali.zycfv.cn/Article/details/gtffoahopo.html

[T09] Kotlin：扩展函数
来源：http://dali.xziqi.cn/Article/details/gtrppgybgb.html

fun String.exclaim() = this + "!"
来源：http://dali.sweek.top/Article/details/gtduynvqxy.html

[T10] Kotlin：默认参数
来源：http://dali.tianlin.xyz/Article/details/gtbtyzqkxk.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.wangshuangyany.cn/Article/details/gtfyizsmmf.html

[T11] Kotlin：协程
来源：http://dali.cdnleiting.top/Article/details/gtqmhnvgqv.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.havefunace.top/Article/details/gtcsgyhnlo.html

[T12] Kotlin：解构声明
来源：http://dali.kuanghao11.cn/Article/details/gtezaehdbb.html

val (a, b) = Pair(1, 2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gthlyoeetb.html

[T13] Kotlin：只读 Map
来源：http://dali.shzxlz.cn/Article/details/gtbcnrwizw.html

val m = mapOf("a" to 1)
来源：http://dali.pengpengdd.cyou/Article/details/gtpkrukozf.html

[T14] Kotlin：循环
来源：http://dali.meibo888.top/Article/details/gtkikvvcmn.html

for (i in 1..10) println(i)
来源：http://dali.jqgfzy.top/Article/details/gtzmvcwdor.html

[T15] Kotlin：接口
来源：http://dali.chenzaomai.com/Article/details/gtigztzapa.html

interface Shape { fun area(): Double }
来源：http://dali.xuanzx.com/Article/details/gtxwypxxvo.html

[T16] Swift：Hello World
来源：http://dali.jianghu66.top/Article/details/gtegdmkstp.html

print("Hello")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgyilayti.html

[T17] Swift：变量与常量
来源：http://dali.xuetiantiany.cn/Article/details/gtovotphxr.html

var a = 1;  let b = 2
来源：http://dali.havefunace.top/Article/details/gtlivtsnff.html

[T18] Swift：字符串插值
来源：http://dali.tanke756.top/Article/details/gtwkkeezqs.html

"值: \(b)"
来源：http://dali.hammf.cn/Article/details/gtjmihhmyd.html

[T19] Swift：可选绑定
来源：http://dali.feifeiyinyue.top/Article/details/gtckwvuomq.html

if let n = opt { print(n) }
来源：http://dali.zdqjudy.top/Article/details/gteaufpwqg.html

[T20] Swift：数组操作
来源：http://dali.xinyue.icu/Article/details/gtdblszlqg.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.snrcjt.cn/Article/details/gtjbdeydhs.html

[T21] Swift：遍历
来源：http://dali.tanke756.top/Article/details/gtrxaqfkbe.html

for x in a { print(x) }
来源：http://dali.yuxming.cn/Article/details/gtilveyjoh.html

[T22] Swift：字典
来源：http://dali.nanxuanxn.top/Article/details/gthgxtfdaz.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.tianlin.xyz/Article/details/gtlsmmveti.html

[T23] Swift：函数
来源：http://dali.hammf.cn/Article/details/gtlkksydcb.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.nwbrower.top/Article/details/gtbqtsvxkv.html

[T24] Swift：闭包
来源：http://dali.yuxming.cn/Article/details/gtkkagdguq.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.sxryk.cn/Article/details/gtagurzjxo.html

[T25] Swift：结构体
来源：http://dali.jyoumei.cn/Article/details/gtpigtbbym.html

struct P { var x: Int }
来源：http://dali.nwbrower.top/Article/details/gtoimjwiin.html

[T26] Swift：类与重写
来源：http://dali.jqgfzy.top/Article/details/gtlruvlcqe.html

class A: Base { override func f() {} }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtecnywwvx.html

[T27] Swift：错误处理
来源：http://dali.snrcjt.cn/Article/details/gtewtiyxpx.html

do { try f() } catch { print(error) }
来源：http://dali.jinqigufen.top/Article/details/gtnqsfdsxm.html

[T28] Swift：枚举
来源：http://dali.zhixingplan.top/Article/details/gtjkygdmff.html

enum Color { case red, green }
来源：http://dali.ybcxt.top/Article/details/gtrsodzmka.html

[T29] Swift：guard 提前返回
来源：http://dali.gotoacloud.top/Article/details/gtskeoresb.html

guard let x = opt else { return }
来源：http://dali.havefunace.top/Article/details/gtwcahqjmo.html

[T30] Swift：协议
来源：http://dali.jlsjyb.cn/Article/details/gtkuuqtpvh.html

protocol Shape { func area() -> Double }
来源：http://dali.sufxvd.cn/Article/details/gttuopfhqp.html

[T31] Lua：Hello World
来源：http://dali.jlsjyb.cn/Article/details/gtqeejkldy.html

print("Hello")
来源：http://dali.gotoacloud.top/Article/details/gtmcupvxid.html

[T32] Lua：局部变量
来源：http://dali.daria6918.cn/Article/details/gtjextuczv.html

local a = 1
来源：http://dali.sweek.top/Article/details/gtomebgplr.html

[T33] Lua：表（数组）
来源：http://dali.shuidangran.top/Article/details/gtxjonfzth.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.cashguo.top/Article/details/gtktuimfeg.html

[T34] Lua：遍历表
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnguetsof.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.hywenlv.cn/Article/details/gtuyzyfxoz.html

[T35] Lua：字典表
来源：http://dali.jinqigufen.top/Article/details/gtqkujkwet.html

local d = { a = 1 };  d.b = 2
来源：http://dali.yj20258.top/Article/details/gtxfnetgis.html

[T36] Lua：函数
来源：http://dali.quarkkingdee.top/Article/details/gtmmicqsve.html

function add(a, b) return a + b end
来源：http://dali.xinyue.icu/Article/details/gtxnojlndb.html

[T37] Lua：字符串拼接
来源：http://dali.jqgufenzy.top/Article/details/gtjmjdkcpk.html

"a" .. "b"
来源：http://dali.hywenlv.cn/Article/details/gtksiatjmq.html

[T38] Lua：条件
来源：http://dali.fzhhl.top/Article/details/gtudjdkgxd.html

if x > 0 then print("正") end
来源：http://dali.xylfe.cn/Article/details/gtxheugbkw.html

[T39] Lua：模式匹配
来源：http://dali.daxiang520.top/Article/details/gtvedwrnyc.html

string.find(s, "%d+")
来源：http://dali.wangdashe.top/Article/details/gtpjrqqauf.html

[T40] Lua：元表
来源：http://dali.gaohongyu789.top/Article/details/gthhxndnmq.html

setmetatable({}, { __index = base })
来源：http://dali.c1oappe.top/Article/details/gtzilfvalq.html

[T41] Perl：Hello World
来源：http://dali.jinqigfzy.top/Article/details/gtlwgvdsmh.html

print "Hello\n";
来源：http://dali.c1oappe.top/Article/details/gtxqnibspq.html

[T42] Perl：变量类型
来源：http://dali.ehwqpu.com/Article/details/gtvpvlgbyx.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtngmhmnuu.html

[T43] Perl：字符串插值
来源：http://dali.andypj.xyz/Article/details/gtgjwnegct.html

"值: $a"
来源：http://dali.aizwys.cn/Article/details/gtpethjgjr.html

[T44] Perl：条件
来源：http://dali.xuanzx.com/Article/details/gtzarvtfoh.html

if ($a > 0) { print "正"; }
来源：http://dali.hfpthk.cn/Article/details/gtdscuepeh.html

[T45] Perl：数组遍历
来源：http://dali.ivvv.top/Article/details/gtzxwzqlnu.html

for my $x (@arr) { print $x; }
来源：http://dali.guannengcc.top/Article/details/gtblgjywcr.html

[T46] Perl：哈希操作
来源：http://dali.dianchejie.cn/Article/details/gtfgkpscqy.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gtgjtwtais.html

[T47] Perl：正则捕获
来源：http://dali.gzhubu.top/Article/details/gtevlwwkxb.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.snrcjt.cn/Article/details/gtiirpakqv.html

[T48] Perl：正则替换
来源：http://dali.hammf.cn/Article/details/gtquwmjsmn.html

$s =~ s/old/new/g;
来源：http://dali.meibo888.top/Article/details/gtmwcvbpdy.html

[T49] Perl：函数
来源：http://dali.tianlin.xyz/Article/details/gtfoixqidx.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhongyouzk.top/Article/details/gtcyvymhhs.html

[T50] Perl：逐行读文件
来源：http://dali.cashguo.top/Article/details/gtbrmrjjmf.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.jinqigufen.top/Article/details/gtorerpbvl.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.ppjwa.cn/Article/details/gtolwwrdsw.html

[T51] Scala：Hello World
来源：http://dali.pycfn.com/Article/details/gtcyuiwesl.html

println("Hello")
来源：http://dali.cucudq.cn/Article/details/gtdyyoaitk.html

[T52] Scala：变量
来源：http://dali.hnxiangtu.top/Article/details/gtqucvqyxx.html


<!-- 参考信息 -->