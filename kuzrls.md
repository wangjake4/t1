代发 wailian999

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gtdoecbtnw.html

[R48] awk 取指定列
来源：http://dali.pycfn.com/Article/details/gtpjfrihnm.html

awk '{print $1, $3}' a.txt
来源：http://dali.quarkkingdee.top/Article/details/gtfunddupy.html

[R49] awk 带条件
来源：http://dali.cucudq.cn/Article/details/gtcaeqieqj.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.feifeiyinyue.top/Article/details/gtazjizoqv.html

[R50] awk 求和
来源：http://dali.sufxvd.cn/Article/details/gthrtadgkm.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.chenlongwang.top/Article/details/gtwrsbtvbr.html

[R51] 排序去重取前几
来源：http://dali.fengsongda.top/Article/details/gthusmhxwq.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.mhx1999.top/Article/details/gteubxhmsl.html

[R52] 统计行数
来源：http://dali.yuxming.cn/Article/details/gtgncmpfff.html

wc -l a.txt
来源：http://dali.aizwys.cn/Article/details/gtttuafanu.html

[R53] 查看文件头与实时尾
来源：http://dali.hysaishi.cn/Article/details/gtabwjitev.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.jinqigufen.top/Article/details/gtddrwqjxb.html

[R54] 比较两个文件
来源：http://dali.shzxlz.cn/Article/details/gtmiwfpywl.html

diff a.txt b.txt
来源：http://dali.yvedp.cn/Article/details/gtlmtppvgy.html

[R55] 压缩与解压
来源：http://dali.snrcjt.cn/Article/details/gtefgsovzr.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.guowangkeji.top/Article/details/gtfgvgodzd.html

[R56] 远程拷贝
来源：http://dali.cashguo.top/Article/details/gttvksbsyb.html

scp file user@host:/path/
来源：http://dali.chenjidiqi.icu/Article/details/gtgaqxchkc.html

[R57] 远程执行命令
来源：http://dali.yvedp.cn/Article/details/gtbjbgmjst.html

ssh user@host 'uptime'
来源：http://dali.zdqjudy.top/Article/details/gtiywrpfip.html

[R58] 下载文件
来源：http://dali.pengpengdd.cyou/Article/details/gtvobztwtr.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.feifeiyinyue.top/Article/details/gtwvwfihss.html

[R59] 发 POST JSON
来源：http://dali.jinqigufen.top/Article/details/gtopdgkike.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.xinyue.icu/Article/details/gtmexmuxzr.html

[R60] 只看 HTTP 状态码
来源：http://dali.chenzaomai.com/Article/details/gtwqectjei.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.hysaishi.cn/Article/details/gtgnrqoxnk.html

[R61] 磁盘占用
来源：http://dali.shuidangran.top/Article/details/gtmylxcpcd.html

df -h;  du -sh *
来源：http://dali.fengsongda.top/Article/details/gtzuljbuxx.html

[R62] 找最占空间的文件
来源：http://dali.yonumen.top/Article/details/gtlppxxjcs.html

du -ah . | sort -rh | head -10
来源：http://dali.sxryk.cn/Article/details/gtvlqbhdmi.html

[R63] 内存与进程
来源：http://dali.0kj1m.cn/Article/details/gtvczogzdn.html

free -h;  ps aux | grep nginx
来源：http://dali.shangyingyoupin.top/Article/details/gtcrvhsroy.html

[R64] 结束进程
来源：http://dali.ivvv.top/Article/details/gtbbynrckn.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhengqikj.top/Article/details/gtqlbhvpmy.html

[R65] 查看端口占用
来源：http://dali.yj20258888.top/Article/details/gtocpjkhaj.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.havefunace.top/Article/details/gtervlfbjf.html

[R66] 定时任务
来源：http://dali.ppjwa.cn/Article/details/gtlqyjzkcp.html

crontab -e;  crontab -l
来源：http://dali.shangyingyoupin.top/Article/details/gtxhkftfxy.html

[R67] 生成随机十六进制串
来源：http://dali.pycfn.com/Article/details/gtsezfmrek.html

openssl rand -hex 16
来源：http://dali.jqgufenzy.top/Article/details/gtrayrsyxk.html

[R68] 计算文件校验值
来源：http://dali.dianchejie.cn/Article/details/gtodhybpjg.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.hongshengwenyu.top/Article/details/gtejfcubqa.html

[R69] 生成随机密码
来源：http://dali.tian-w.cn/Article/details/gtgvypdohv.html

head -c 16 /dev/urandom | base64
来源：http://dali.pycfn.com/Article/details/gtlelvezhb.html

[R70] 时间戳与互转
来源：http://dali.jinghuilouyu.cn/Article/details/gtzkwjrxur.html

date +%s;  date -d @1700000000
来源：http://dali.zhoulong.xyz/Article/details/gtswbqcnnc.html

[R71] 日期格式化
来源：http://dali.cqqwz.cn/Article/details/gtrybtiqvj.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.yangfankeji.com/Article/details/gtqcozunhj.html

[R72] 等待端口就绪
来源：http://dali.jinghuilouyu.cn/Article/details/gtfwegetso.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.9152youxi.cn/Article/details/gtivlbjfse.html

[R73] 分割大日志
来源：http://dali.yj20258888.top/Article/details/gttcjzvpgd.html

split -l 1000 big.log part_
来源：http://dali.vqdsnc.cn/Article/details/gtqsayfvuk.html

[R74] 批量重命名
来源：http://dali.svipenyu.cn/Article/details/gtyemvxnse.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.yueranfly.top/Article/details/gtnpsbrggv.html

[R75] 导出环境变量
来源：http://dali.ivvv.top/Article/details/gtliacvreh.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlfhkbfav.html

[R76] 使用临时文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcgjfzyco.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.haohaochexian.top/Article/details/gtpnhwzrrs.html

[R77] 读取用户输入
来源：http://dali.cheryme.top/Article/details/gtbxlglcvg.html

read -rp "请输入: " ans
来源：http://dali.hfpthk.cn/Article/details/gtabxlppdc.html

[R78] 交互式菜单
来源：http://dali.cdnleiting.top/Article/details/gthnqhfevk.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhongyouzk.top/Article/details/gtdyszzfxg.html

[R79] 解析命令行选项
来源：http://dali.c1oappe.top/Article/details/gtcwvfykzt.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.snrcjt.cn/Article/details/gtdayptybi.html

[R80] 查看脚本执行耗时
来源：http://dali.sxryk.cn/Article/details/gtvrrhwaap.html

time ./run.sh
来源：http://dali.yangfankeji.com/Article/details/gtectutbxa.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtjzjxqaqc.html

S. C / C++ 专题
来源：http://dali.cqqwz.cn/Article/details/gtpuortmxg.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtcuoeaurm.html

[S01] C：Hello World
来源：http://dali.shzxlz.cn/Article/details/gtonklrrdk.html

#include <stdio.h>
来源：http://dali.hfpthk.cn/Article/details/gtksereemw.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.fzhhl.top/Article/details/gtefwbzglw.html

[S02] C：变量与格式化输出
来源：http://dali.zdqjudy.top/Article/details/gtptlwytbe.html

int a = 10; printf("%d\n", a);
来源：http://dali.nanxuanxn.top/Article/details/gtmtioykfi.html

[S03] C：读入整数
来源：http://dali.jqgfzy.top/Article/details/gtzvkgefbj.html

int x; scanf("%d", &x);
来源：http://dali.daria6918.cn/Article/details/gtgrbznvrz.html

[S04] C：字符串复制
来源：http://dali.zhoulong.xyz/Article/details/gtptojtnee.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.sysykeji.top/Article/details/gtamrorteb.html

[S05] C：字符串长度
来源：http://dali.shanyushiyangkeji.top/Article/details/gtihlgwqej.html

strlen(s)
来源：http://dali.ehwqpu.com/Article/details/gtebfcmhhm.html

[S06] C：字符串比较
来源：http://dali.fzhhl.top/Article/details/gtnyshxype.html

strcmp(a, b) == 0
来源：http://dali.ppjwa.cn/Article/details/gtqoqkamcy.html

[S07] C：数组遍历求和
来源：http://dali.hfpthk.cn/Article/details/gtmdbsifop.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.tian-w.cn/Article/details/gtwyrgnrqf.html

[S08] C：动态内存分配与释放
来源：http://dali.jyoumei.cn/Article/details/gtbafvnzlh.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.316326.xyz/Article/details/gtsbutamcr.html

[S09] C：结构体定义与初始化
来源：http://dali.cashguo.top/Article/details/gtyzwwadfr.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.xuanzx.com/Article/details/gtxyrxflmd.html

[S10] C：指针与解引用
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoudchzcv.html

int *p = &a;  *p = 5;
来源：http://dali.jianghu66.top/Article/details/gtegzogegt.html

[S11] C：逐行读文件
来源：http://dali.yvedp.cn/Article/details/gtujpzbxox.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.xylfe.cn/Article/details/gtgavjmfup.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.gzhubu.top/Article/details/gtkrwdhxvj.html

fclose(f);
来源：http://dali.xylfe.cn/Article/details/gtybkhmlul.html

[S12] C：写文件
来源：http://dali.yj202588.top/Article/details/gtxrxhvzhl.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.jianghu66.top/Article/details/gttaaheqoq.html

[S13] C：宏定义
来源：http://dali.fengsongda.top/Article/details/gtwmsxpwrk.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.birdmap.top/Article/details/gtblrbcqqy.html

[S14] C：枚举
来源：http://dali.zhixingplan.top/Article/details/gtauzthjfj.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.hywenlv.cn/Article/details/gtayysmbbu.html

[S15] C：类型转换
来源：http://dali.zhongyouzk.top/Article/details/gtkthjqvrq.html

(double) a / b
来源：http://dali.hnqzz.top/Article/details/gtaekdqzzt.html

[S16] C：位操作置位
来源：http://dali.iojbl.cn/Article/details/gtttczawku.html

x |= (1 << 3);
来源：http://dali.gogol.net.cn/Article/details/gtcchygmad.html

[S17] C：安全拼接字符串
来源：http://dali.shzxlz.cn/Article/details/gtshwypiay.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.ppjwa.cn/Article/details/gtzfltubjt.html

[S18] C：命令行参数
来源：http://dali.pengpengdd.cyou/Article/details/gtsuwpqkrc.html

int main(int argc, char **argv)
来源：http://dali.zhiwuduotai.top/Article/details/gtddhxchsm.html

[S19] C：快速排序
来源：http://dali.tianlin.xyz/Article/details/gtgvigujnm.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.tianlin.xyz/Article/details/gtgnvyaylm.html

[S20] C：二分查找
来源：http://dali.0kj1m.cn/Article/details/gtnimmzonf.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.xziqi.cn/Article/details/gtgjcvfshd.html

[S21] C：字符类别判断
来源：http://dali.zhixingplan.top/Article/details/gtmtycemkb.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.sufxvd.cn/Article/details/gtpyzzcjxw.html

[S22] C：字符串转数字
来源：http://dali.nanxinkj.top/Article/details/gtkvfwiana.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.shuidangran.top/Article/details/gthztbkqtd.html

[S23] C：随机数
来源：http://dali.jinghuilouyu.cn/Article/details/gtcrgwumxc.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhiwuduotai.top/Article/details/gtzawtsovi.html

[S24] C：获取本地时间
来源：http://dali.gaohongyu789.top/Article/details/gtvrezyiwm.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.yuxming.cn/Article/details/gtinkgdpno.html

[S25] C：内存拷贝
来源：http://dali.yj202588.top/Article/details/gtbzjfmopt.html

memcpy(dst, src, n);
来源：http://dali.jianghu66.top/Article/details/gtofzomebh.html

[S26] C：内存清零
来源：http://dali.jqgufenzy.top/Article/details/gtsszepmtw.html

memset(a, 0, sizeof a);
来源：http://dali.chenzaomai.com/Article/details/gtuwzrsmuo.html

[S27] C：定义常量
来源：http://dali.cdnleiting.top/Article/details/gtjbckvepo.html

const double PI = 3.14159;
来源：http://dali.yj20258888.top/Article/details/gtaxasdjav.html

[S28] C：静态变量
来源：http://dali.nwbrower.top/Article/details/gtwsdujsku.html

static int counter = 0;
来源：http://dali.ybcxt.top/Article/details/gtixyompum.html

[S29] C：变参函数
来源：http://dali.yj20258888.top/Article/details/gtwkvapgqz.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.tian-w.cn/Article/details/gtyvsfqegb.html

[S30] C：头文件保护
来源：http://dali.zhengqikj.top/Article/details/gtczrqxybv.html

#ifndef X_H
来源：http://dali.xuanzx.com/Article/details/gtbqoahzvv.html

#define X_H
来源：http://dali.zdqjudy.top/Article/details/gtwimnqtex.html

#endif
来源：http://dali.sweek.top/Article/details/gtiulyuabd.html

[S31] C++：Hello World
来源：http://dali.ehwqpu.com/Article/details/gtfdrltrdt.html

#include <iostream>
来源：http://dali.zycfv.cn/Article/details/gtyuaidudu.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.ehwqpu.com/Article/details/gtoovgohzr.html

[S32] C++：字符串
来源：http://dali.gzhubu.top/Article/details/gtadcoevxe.html

std::string s = "hi";  s += "!";
来源：http://dali.hnxiangtu.top/Article/details/gthfrwicgd.html

[S33] C++：vector 增删
来源：http://dali.wangdashe.top/Article/details/gtblocqzya.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.yongpay.top/Article/details/gtrrbofqen.html

[S34] C++：遍历 vector
来源：http://dali.sweek.top/Article/details/gtcetjlxfg.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.jiagoushi.top/Article/details/gtuaqxdvnc.html

[S35] C++：map
来源：http://dali.hammf.cn/Article/details/gtfabodaxx.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.gzhubu.top/Article/details/gtrqvrtqkw.html

[S36] C++：unordered_map
来源：http://dali.hongshengwenyu.top/Article/details/gticeabxms.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jianghu66.top/Article/details/gtcnmmovby.html

[S37] C++：set
来源：http://dali.pycfn.com/Article/details/gtnaqonqha.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.aibaodan.cn/Article/details/gtkcgztlxu.html

[S38] C++：排序
来源：http://dali.xuanzx.com/Article/details/gtylnjinib.html

std::sort(v.begin(), v.end());
来源：http://dali.quarkkingdee.top/Article/details/gtpjaxjbnk.html

[S39] C++：自定义比较器排序
来源：http://dali.sufxvd.cn/Article/details/gtydsntroj.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gtpvzailxg.html

[S40] C++：查找元素
来源：http://dali.guowangkeji.top/Article/details/gtbqrvjezq.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.iojbl.cn/Article/details/gtvczhdrne.html

[S41] C++：类与构造函数
来源：http://dali.kuanghao11.cn/Article/details/gtvwqudxfy.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.dashuyun.cn/Article/details/gtwtbjvdwb.html

[S42] C++：继承与虚函数
来源：http://dali.xinyue.icu/Article/details/gttidjsbcp.html

class B : public Base { public: void f() override {} };
来源：http://dali.ybcxt.top/Article/details/gtafthrgyw.html

[S43] C++：智能指针
来源：http://dali.nanxuanxn.top/Article/details/gtgkmkcfjx.html

auto p = std::make_unique<int>(5);
来源：http://dali.snrcjt.cn/Article/details/gtyfhdgkbw.html

[S44] C++：引用传参
来源：http://dali.bjfxy.top/Article/details/gtolnxrknd.html

void inc(int &x) { ++x; }
来源：http://dali.shangyingyoupin.top/Article/details/gtjiiaklui.html

[S45] C++：lambda
来源：http://dali.birdmap.top/Article/details/gtujxfgdcq.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.tianlin.xyz/Article/details/gtgfzavmys.html

[S46] C++：函数模板
来源：http://dali.ydzc1.top/Article/details/gtpvdqcaew.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.ybcxt.top/Article/details/gtmjptfmus.html

[S47] C++：结构化绑定遍历
来源：http://dali.dashuyun.cn/Article/details/gtpmkzwnbf.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.shzxlz.cn/Article/details/gtiplclflb.html

[S48] C++：逐行读文件
来源：http://dali.jianghu66.top/Article/details/gtvowwxybm.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.shanyushiyangtech.top/Article/details/gtvtjrxncs.html

while (std::getline(in, line)) { }
来源：http://dali.yj20258.top/Article/details/gthrutuuug.html

[S49] C++：写文件
来源：http://dali.xuetiantiany.cn/Article/details/gtwbigiyui.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.pengpengdd.cyou/Article/details/gtmhnxquyi.html

[S50] C++：格式化数字
来源：http://dali.guowangkeji.top/Article/details/gtcbiijgvq.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrsbxfuuj.html

[S51] C++：显式类型转换
来源：http://dali.jqgfzy.top/Article/details/gthfcltoai.html

static_cast<double>(a) / b
来源：http://dali.havefunace.top/Article/details/gtcgypdrrl.html

[S52] C++：const 与 noexcept
来源：http://dali.316326.xyz/Article/details/gtnqulsmcp.html

int size() const noexcept { return n_; }
来源：http://dali.daria6918.cn/Article/details/gtcavguogl.html

[S53] C++：移动语义
来源：http://dali.yvedp.cn/Article/details/gtbrrsdhje.html

std::vector<int> w = std::move(v);
来源：http://dali.0kj1m.cn/Article/details/gtwjhatgka.html

[S54] C++：异常处理
来源：http://dali.cashguo.top/Article/details/gtuujrupbr.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.9152youxi.cn/Article/details/gtnpvohvda.html

[S55] C++：结构化绑定
来源：http://dali.wangdashe.top/Article/details/gtcouymwgf.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.xuetiantiany.cn/Article/details/gtotpdbybv.html

[S56] C++：optional
来源：http://dali.chenlongwang.top/Article/details/gtnxzaeciy.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.hywenlv.cn/Article/details/gtvgwnhazu.html

[S57] C++：编译期常量
来源：http://dali.yueranfly.top/Article/details/gtuprposqb.html

constexpr int N = 10;
来源：http://dali.yueranfly.top/Article/details/gtjihywioi.html

[S58] C++：命名空间
来源：http://dali.xuetiantiany.cn/Article/details/gtcueisqyc.html

namespace ns { int f() { return 1; } }
来源：http://dali.jianghu66.top/Article/details/gtuabyhund.html

[S59] C++：静态断言
来源：http://dali.sysykeji.top/Article/details/gtabfsquvq.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.xuanzx.com/Article/details/gtmebyilxl.html

[S60] C++：遍历并删除元素
来源：http://dali.cucudq.cn/Article/details/gthfxzbqvw.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.tanke756.top/Article/details/gtdntptffh.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtqtpgzatt.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.xuanzx.com/Article/details/gtitunwkif.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtmziwokus.html

[T01] Kotlin：Hello World
来源：http://dali.shzxlz.cn/Article/details/gtnmbsmslp.html

println("Hello")
来源：http://dali.yj20258888.top/Article/details/gtfgqkbyue.html

[T02] Kotlin：变量
来源：http://dali.yueranfly.top/Article/details/gtjgsglrdr.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gtyakrjzcs.html

[T03] Kotlin：字符串模板
来源：http://dali.cqqwz.cn/Article/details/gttzlppkgl.html

"值: $b"
来源：http://dali.cucudq.cn/Article/details/gtymubxffu.html

[T04] Kotlin：空安全
来源：http://dali.sweek.top/Article/details/gtwiamjctc.html

val n: String? = null;  n?.length
来源：http://dali.sxryk.cn/Article/details/gthchtwvxg.html

[T05] Kotlin：when 表达式
来源：http://dali.9152youxi.cn/Article/details/gtjgkyykgy.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhiwuduotai.top/Article/details/gtwdfovjtg.html

[T06] Kotlin：集合映射
来源：http://dali.cucudq.cn/Article/details/gtfyivwuyy.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.andypj.xyz/Article/details/gtjrggzuoq.html

[T07] Kotlin：集合过滤
来源：http://dali.hammf.cn/Article/details/gtsvidkbjz.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.hfpthk.cn/Article/details/gtuqksoqqt.html

[T08] Kotlin：数据类
来源：http://dali.tanke756.top/Article/details/gttkfqejbv.html

data class User(val name: String, val age: Int)
来源：http://dali.gotoacloud.top/Article/details/gtltijddaw.html

[T09] Kotlin：扩展函数
来源：http://dali.aibaodan.cn/Article/details/gthleqtmsn.html

fun String.exclaim() = this + "!"
来源：http://dali.svipenyu.cn/Article/details/gtvwmvslka.html

[T10] Kotlin：默认参数
来源：http://dali.yanxiufei.cn/Article/details/gtknyjolgx.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.gotoacloud.top/Article/details/gttqtcmvkj.html

[T11] Kotlin：协程
来源：http://dali.aizwys.cn/Article/details/gtkonrluqz.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.tianlin.xyz/Article/details/gtbegwfsza.html

[T12] Kotlin：解构声明
来源：http://dali.yvedp.cn/Article/details/gtqkyzpvbb.html

val (a, b) = Pair(1, 2)
来源：http://dali.fengsongda.top/Article/details/gtkqotpuic.html

[T13] Kotlin：只读 Map
来源：http://dali.cqqwz.cn/Article/details/gtvszypxxt.html

val m = mapOf("a" to 1)
来源：http://dali.nwbrower.top/Article/details/gtudtzcvmb.html

[T14] Kotlin：循环
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmeglgxya.html

for (i in 1..10) println(i)
来源：http://dali.fengsongda.top/Article/details/gtpxmyqkjm.html

[T15] Kotlin：接口
来源：http://dali.quarkkingdee.top/Article/details/gtxlltftun.html

interface Shape { fun area(): Double }
来源：http://dali.sxryk.cn/Article/details/gteoyxwevp.html

[T16] Swift：Hello World
来源：http://dali.smart0.xyz/Article/details/gtbpugiocl.html

print("Hello")
来源：http://dali.feifeiyinyue.top/Article/details/gtzbyeqbaa.html

[T17] Swift：变量与常量
来源：http://dali.wangshuangyany.cn/Article/details/gtiynlayyf.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gtdlxrodmw.html

[T18] Swift：字符串插值
来源：http://dali.zhoulong.xyz/Article/details/gtykmtsckl.html

"值: \(b)"
来源：http://dali.jqgfzy.top/Article/details/gtnhplqrds.html

[T19] Swift：可选绑定
来源：http://dali.chenlongwang.top/Article/details/gtopglijkm.html

if let n = opt { print(n) }
来源：http://dali.zhengqikj.top/Article/details/gtuvsyyorc.html

[T20] Swift：数组操作
来源：http://dali.wangshuangyany.cn/Article/details/gtpxioqtxi.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkqndlqlt.html

[T21] Swift：遍历
来源：http://dali.nanxinkj.top/Article/details/gtvpiokzzr.html

for x in a { print(x) }
来源：http://dali.xylfe.cn/Article/details/gtsjbuwamg.html

[T22] Swift：字典
来源：http://dali.shanyushiyangtech.top/Article/details/gtinnhnhqg.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.daria6918.cn/Article/details/gttkfesmgo.html

[T23] Swift：函数
来源：http://dali.sysykeji.top/Article/details/gtdzozrlkt.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.shuidangran.top/Article/details/gtiazacvyt.html

[T24] Swift：闭包
来源：http://dali.birdmap.top/Article/details/gtfuzltbnd.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.yangfankeji.com/Article/details/gtsefsersz.html

[T25] Swift：结构体
来源：http://dali.hywenlv.cn/Article/details/gtvdgujkkb.html

struct P { var x: Int }
来源：http://dali.yangfankeji.com/Article/details/gtwadysqeo.html

[T26] Swift：类与重写
来源：http://dali.zhixingplan.top/Article/details/gtttwbimvj.html

class A: Base { override func f() {} }
来源：http://dali.ydzc1.top/Article/details/gtibhmthch.html

[T27] Swift：错误处理
来源：http://dali.jinqigufen.top/Article/details/gtlysgdrhg.html

do { try f() } catch { print(error) }
来源：http://dali.gotoacloud.top/Article/details/gtklabpqwk.html

[T28] Swift：枚举
来源：http://dali.vqdsnc.cn/Article/details/gtbtklgnbg.html

enum Color { case red, green }
来源：http://dali.ybcxt.top/Article/details/gtkrxophkb.html

[T29] Swift：guard 提前返回
来源：http://dali.jinqigufen.top/Article/details/gtlxpaypun.html

guard let x = opt else { return }
来源：http://dali.smart0.xyz/Article/details/gtpkvhxqsh.html

[T30] Swift：协议
来源：http://dali.daria6918.cn/Article/details/gtpdalhfxn.html

protocol Shape { func area() -> Double }
来源：http://dali.jinqigfzy.top/Article/details/gtcebupvrz.html

[T31] Lua：Hello World
来源：http://dali.jyoumei.cn/Article/details/gtszglwbxn.html

print("Hello")
来源：http://dali.tian-w.cn/Article/details/gtkeaatvfi.html

[T32] Lua：局部变量
来源：http://dali.yj202588.top/Article/details/gtjqegkihj.html

local a = 1
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbdhjspfo.html

[T33] Lua：表（数组）
来源：http://dali.yj20258888.top/Article/details/gthbjdgzdk.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zdqjudy.top/Article/details/gtrhwzobua.html

[T34] Lua：遍历表
来源：http://dali.zhiwuduotai.top/Article/details/gtemgpngyi.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.yanxiufei.cn/Article/details/gtxditllia.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gtsenpebnc.html

local d = { a = 1 };  d.b = 2
来源：http://dali.yj202588.top/Article/details/gtqainpcxq.html

[T36] Lua：函数
来源：http://dali.hammf.cn/Article/details/gtogtaamnh.html

function add(a, b) return a + b end
来源：http://dali.yonumen.top/Article/details/gtffztlrnx.html

[T37] Lua：字符串拼接
来源：http://dali.smart0.xyz/Article/details/gtyvhpbtge.html

"a" .. "b"
来源：http://dali.316326.xyz/Article/details/gtqrzsphvd.html

[T38] Lua：条件
来源：http://dali.xuanzx.com/Article/details/gtgrszmamv.html

if x > 0 then print("正") end
来源：http://dali.yanxiufei.cn/Article/details/gtcimdpgst.html

[T39] Lua：模式匹配
来源：http://dali.aibaodan.cn/Article/details/gtaiafdvhe.html

string.find(s, "%d+")
来源：http://dali.yuanzhike.top/Article/details/gtybeftrju.html

[T40] Lua：元表
来源：http://dali.iojbl.cn/Article/details/gtkuvaeyok.html

setmetatable({}, { __index = base })
来源：http://dali.cheryme.top/Article/details/gtmiyowoew.html

[T41] Perl：Hello World
来源：http://dali.ydzc1.top/Article/details/gtqdzrlarb.html

print "Hello\n";
来源：http://dali.9152youxi.cn/Article/details/gtrddanuma.html

[T42] Perl：变量类型
来源：http://dali.pycfn.com/Article/details/gtojvuiuno.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhixingplan.top/Article/details/gtxxapocgl.html

[T43] Perl：字符串插值
来源：http://dali.sweek.top/Article/details/gtojcoqvqx.html

"值: $a"
来源：http://dali.dashuyun.cn/Article/details/gttqxkdzdm.html

[T44] Perl：条件
来源：http://dali.sweek.top/Article/details/gtzbnulncq.html

if ($a > 0) { print "正"; }
来源：http://dali.cqqwz.cn/Article/details/gtxtrgrpnw.html

[T45] Perl：数组遍历
来源：http://dali.yuanzhike.top/Article/details/gtnuphrilc.html

for my $x (@arr) { print $x; }
来源：http://dali.havefunace.top/Article/details/gtxhyuikea.html

[T46] Perl：哈希操作
来源：http://dali.birdmap.top/Article/details/gtaprlxjqn.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.chenjidiqi.icu/Article/details/gtzcivmuby.html

[T47] Perl：正则捕获
来源：http://dali.hongshengwenyu.top/Article/details/gtohrfjtyv.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.dianchejie.cn/Article/details/gtvsurmwqf.html

[T48] Perl：正则替换
来源：http://dali.hnqzz.top/Article/details/gtmfdqskuo.html

$s =~ s/old/new/g;
来源：http://dali.ppjwa.cn/Article/details/gtvgqcplff.html

[T49] Perl：函数
来源：http://dali.fengsongda.top/Article/details/gtyexhtuti.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.ehwqpu.com/Article/details/gttqikcfee.html

[T50] Perl：逐行读文件
来源：http://dali.guowangkeji.top/Article/details/gtzsoihmhk.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.cashguo.top/Article/details/gtbtjtzctb.html


<!-- 参考信息 -->