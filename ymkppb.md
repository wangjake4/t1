代发 wailian999

sed -i 's/foo/bar/g' a.txt
来源：http://dali.yuxming.cn/Article/details/gt2jdnbocob.html

[R48] awk 取指定列
来源：http://dali.cucudq.cn/Article/details/gt2jsshtmox.html

awk '{print $1, $3}' a.txt
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nnydsouj.html

[R49] awk 带条件
来源：http://dali.haohaochexian.top/Article/details/gt2twrvwlqj.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.wangdashe.top/Article/details/gt2bwzttrsm.html

[R50] awk 求和
来源：http://dali.zdqjudy.top/Article/details/gt2rdkpecck.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.svipenyu.cn/Article/details/gt2iapdevfq.html

[R51] 排序去重取前几
来源：http://dali.shzxlz.cn/Article/details/gt2qenxjqzd.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.cheryme.top/Article/details/gt2mrjbkwfe.html

[R52] 统计行数
来源：http://dali.yangfankeji.com/Article/details/gt2zejxbvlr.html

wc -l a.txt
来源：http://dali.pengpengdd.cyou/Article/details/gt2hccegkuh.html

[R53] 查看文件头与实时尾
来源：http://dali.sysykeji.top/Article/details/gt2vkijxlda.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.svipenyu.cn/Article/details/gt2yzssffoi.html

[R54] 比较两个文件
来源：http://dali.zycfv.cn/Article/details/gt2hjbckpfq.html

diff a.txt b.txt
来源：http://dali.gogol.net.cn/Article/details/gt2qhqtfcwl.html

[R55] 压缩与解压
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kbjiiibt.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.bjfxy.top/Article/details/gt2pqzxrwsm.html

[R56] 远程拷贝
来源：http://dali.xuanzx.com/Article/details/gt2pumrmqgy.html

scp file user@host:/path/
来源：http://dali.yj20258888.top/Article/details/gt2raqunrmi.html

[R57] 远程执行命令
来源：http://dali.pengpengdd.cyou/Article/details/gt2dtkucreb.html

ssh user@host 'uptime'
来源：http://dali.jiagoushi.top/Article/details/gt2jhkbupye.html

[R58] 下载文件
来源：http://dali.yanxiufei.cn/Article/details/gt2lffvmfaj.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.sweek.top/Article/details/gt2bmadfsgd.html

[R59] 发 POST JSON
来源：http://dali.hongshengwenyu.top/Article/details/gt2okptrftg.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.hnxiangtu.top/Article/details/gt2gqhcuxlg.html

[R60] 只看 HTTP 状态码
来源：http://dali.fengsongda.top/Article/details/gt2lipfpbeh.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.pycfn.com/Article/details/gt2xawyujpp.html

[R61] 磁盘占用
来源：http://dali.xuetiantiany.cn/Article/details/gt2byzqyjen.html

df -h;  du -sh *
来源：http://dali.zhixingplan.top/Article/details/gt2urinrokl.html

[R62] 找最占空间的文件
来源：http://dali.yj20258.top/Article/details/gt2dqslqrgf.html

du -ah . | sort -rh | head -10
来源：http://dali.xziqi.cn/Article/details/gt2gphfolxr.html

[R63] 内存与进程
来源：http://dali.fengsongda.top/Article/details/gt2lhuladzd.html

free -h;  ps aux | grep nginx
来源：http://dali.jqgufenzy.top/Article/details/gt2gjtlfbgk.html

[R64] 结束进程
来源：http://dali.andypj.xyz/Article/details/gt2kqjhvsil.html

kill -9 $(pgrep -f app.py)
来源：http://dali.gzhubu.top/Article/details/gt2xuiwfimx.html

[R65] 查看端口占用
来源：http://dali.xuetiantiany.cn/Article/details/gt2uowuiuxb.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2qpgftmvf.html

[R66] 定时任务
来源：http://dali.xuetiantiany.cn/Article/details/gt2bvpaxqet.html

crontab -e;  crontab -l
来源：http://dali.ppjwa.cn/Article/details/gt2ivcjjvtp.html

[R67] 生成随机十六进制串
来源：http://dali.svipenyu.cn/Article/details/gt2troxppzy.html

openssl rand -hex 16
来源：http://dali.jqgufenzy.top/Article/details/gt2sdmkllrm.html

[R68] 计算文件校验值
来源：http://dali.vqdsnc.cn/Article/details/gt2yustfrpv.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.chenjidiqi.icu/Article/details/gt2wfqzgcdg.html

[R69] 生成随机密码
来源：http://dali.jiagoushi.top/Article/details/gt2tqbrtnww.html

head -c 16 /dev/urandom | base64
来源：http://dali.gotoacloud.top/Article/details/gt2yxnhxeld.html

[R70] 时间戳与互转
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nteufcus.html

date +%s;  date -d @1700000000
来源：http://dali.sxryk.cn/Article/details/gt2rxernkyp.html

[R71] 日期格式化
来源：http://dali.daxiang520.top/Article/details/gt2rrrsonnq.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.haohaochexian.top/Article/details/gt2unpmrepv.html

[R72] 等待端口就绪
来源：http://dali.gaohongyu789.top/Article/details/gt2orwhetnr.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.sxryk.cn/Article/details/gt2xzyszaew.html

[R73] 分割大日志
来源：http://dali.cucudq.cn/Article/details/gt2xgxqzfnw.html

split -l 1000 big.log part_
来源：http://dali.yuanzhike.top/Article/details/gt2itsitouk.html

[R74] 批量重命名
来源：http://dali.yangfankeji.com/Article/details/gt2qlkpxikv.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.xylfe.cn/Article/details/gt2vgmlfrtv.html

[R75] 导出环境变量
来源：http://dali.shangyingyoupin.top/Article/details/gt2oazufcae.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.chenjidiqi.icu/Article/details/gt2jdgasoev.html

[R76] 使用临时文件
来源：http://dali.hysaishi.cn/Article/details/gt2jcfykarj.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.andypj.xyz/Article/details/gt2xrzptdwl.html

[R77] 读取用户输入
来源：http://dali.wangdashe.top/Article/details/gt2ifbwiqny.html

read -rp "请输入: " ans
来源：http://dali.fengsongda.top/Article/details/gt2umdnwimr.html

[R78] 交互式菜单
来源：http://dali.wangshuangyany.cn/Article/details/gt2lssqojjy.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.cashguo.top/Article/details/gt2mvnddfdd.html

[R79] 解析命令行选项
来源：http://dali.hysaishi.cn/Article/details/gt2rgedeopf.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.smart0.xyz/Article/details/gt2qugdocil.html

[R80] 查看脚本执行耗时
来源：http://dali.feifeiyinyue.top/Article/details/gt2frlioalg.html

time ./run.sh
来源：http://dali.aizwys.cn/Article/details/gt2drubhqzz.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2wiwyhyea.html

S. C / C++ 专题
来源：http://dali.jlsjyb.cn/Article/details/gt2aurpdsuu.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gt2cndmvwak.html

[S01] C：Hello World
来源：http://dali.yanxiufei.cn/Article/details/gt2sobtfjdo.html

#include <stdio.h>
来源：http://dali.jianghu66.top/Article/details/gt2cugydfnq.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.hfpthk.cn/Article/details/gt2zjyqetin.html

[S02] C：变量与格式化输出
来源：http://dali.wangshuangyany.cn/Article/details/gt2yuqsiisk.html

int a = 10; printf("%d\n", a);
来源：http://dali.xinyue.icu/Article/details/gt2ecbsbmip.html

[S03] C：读入整数
来源：http://dali.feifeiyinyue.top/Article/details/gt2npnmbmxa.html

int x; scanf("%d", &x);
来源：http://dali.mhx1999.top/Article/details/gt2uoazmtze.html

[S04] C：字符串复制
来源：http://dali.jinqigfzy.top/Article/details/gt2oqghjaxy.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.tanke756.top/Article/details/gt2syaiqjun.html

[S05] C：字符串长度
来源：http://dali.daria6918.cn/Article/details/gt2ntkuibaq.html

strlen(s)
来源：http://dali.ivvv.top/Article/details/gt2wzksfxpg.html

[S06] C：字符串比较
来源：http://dali.yuxming.cn/Article/details/gt2kjgaejbw.html

strcmp(a, b) == 0
来源：http://dali.tianlin.xyz/Article/details/gt2sswfmzai.html

[S07] C：数组遍历求和
来源：http://dali.hfpthk.cn/Article/details/gt2hbzvokcn.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.haohaochexian.top/Article/details/gt2ruavzsio.html

[S08] C：动态内存分配与释放
来源：http://dali.tian-w.cn/Article/details/gt2wnilvesx.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.mhx1999.top/Article/details/gt2wfmjsliu.html

[S09] C：结构体定义与初始化
来源：http://dali.iojbl.cn/Article/details/gt2pmdhlfuz.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.nanxinkj.top/Article/details/gt2xuwvvkiy.html

[S10] C：指针与解引用
来源：http://dali.yvedp.cn/Article/details/gt2ouizqyxv.html

int *p = &a;  *p = 5;
来源：http://dali.vqdsnc.cn/Article/details/gt2iemxhjfq.html

[S11] C：逐行读文件
来源：http://dali.mhx1999.top/Article/details/gt2skhdpuuh.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.cucudq.cn/Article/details/gt2zvcpkldd.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.tian-w.cn/Article/details/gt2qimxoveq.html

fclose(f);
来源：http://dali.nanxinkj.top/Article/details/gt2trosdhhy.html

[S12] C：写文件
来源：http://dali.c1oappe.top/Article/details/gt2navzvghp.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2szykexmp.html

[S13] C：宏定义
来源：http://dali.daria6918.cn/Article/details/gt2rvftebcq.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.nanxinkj.top/Article/details/gt2jbvcofvz.html

[S14] C：枚举
来源：http://dali.nanxuanxn.top/Article/details/gt2nmdkkgay.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.shzxlz.cn/Article/details/gt2biptsely.html

[S15] C：类型转换
来源：http://dali.yueranfly.top/Article/details/gt2olrkzhbt.html

(double) a / b
来源：http://dali.pengpengdd.cyou/Article/details/gt2uifqktgi.html

[S16] C：位操作置位
来源：http://dali.hongshengwenyu.top/Article/details/gt2inwlmjpf.html

x |= (1 << 3);
来源：http://dali.feifeiyinyue.top/Article/details/gt2excnkooe.html

[S17] C：安全拼接字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pmvqjnhe.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.jinqigufen.top/Article/details/gt2hwvuztea.html

[S18] C：命令行参数
来源：http://dali.vqdsnc.cn/Article/details/gt2lexocoaz.html

int main(int argc, char **argv)
来源：http://dali.jqgfzy.top/Article/details/gt2opuegvjp.html

[S19] C：快速排序
来源：http://dali.cheryme.top/Article/details/gt2tsroxqit.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.bjfxy.top/Article/details/gt2rbqkqwcu.html

[S20] C：二分查找
来源：http://dali.yongpay.top/Article/details/gt2mlmtxpsj.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhoulong.xyz/Article/details/gt2bsdtutmr.html

[S21] C：字符类别判断
来源：http://dali.chenjidiqi.icu/Article/details/gt2ssrslmxk.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.havefunace.top/Article/details/gt2biznhbka.html

[S22] C：字符串转数字
来源：http://dali.dianchejie.cn/Article/details/gt2mqwxizfm.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.hammf.cn/Article/details/gt2fwvhbcpo.html

[S23] C：随机数
来源：http://dali.hongshengwenyu.top/Article/details/gt2qbtfzdpn.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.bjfxy.top/Article/details/gt2dugdvafb.html

[S24] C：获取本地时间
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ngrtoujj.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.smart0.xyz/Article/details/gt2ibqyhjyz.html

[S25] C：内存拷贝
来源：http://dali.havefunace.top/Article/details/gt2ximukvcg.html

memcpy(dst, src, n);
来源：http://dali.shzxlz.cn/Article/details/gt2raxseolg.html

[S26] C：内存清零
来源：http://dali.chenzaomai.com/Article/details/gt2qojkmrjc.html

memset(a, 0, sizeof a);
来源：http://dali.feifeiyinyue.top/Article/details/gt2rumrgoow.html

[S27] C：定义常量
来源：http://dali.pycfn.com/Article/details/gt2trsylxbo.html

const double PI = 3.14159;
来源：http://dali.haohaochexian.top/Article/details/gt2ovtolgvd.html

[S28] C：静态变量
来源：http://dali.shuidangran.top/Article/details/gt2kxzeaafx.html

static int counter = 0;
来源：http://dali.cheryme.top/Article/details/gt2alswboiv.html

[S29] C：变参函数
来源：http://dali.cdnleiting.top/Article/details/gt2aqmmywse.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.yongpay.top/Article/details/gt2oaokhjrr.html

[S30] C：头文件保护
来源：http://dali.aizwys.cn/Article/details/gt2uftbjiur.html

#ifndef X_H
来源：http://dali.yj20258.top/Article/details/gt2smglxxse.html

#define X_H
来源：http://dali.sysykeji.top/Article/details/gt2ydaoytbh.html

#endif
来源：http://dali.havefunace.top/Article/details/gt2hlrajnil.html

[S31] C++：Hello World
来源：http://dali.shzxlz.cn/Article/details/gt2cqjgavqt.html

#include <iostream>
来源：http://dali.gotoacloud.top/Article/details/gt2zebtxalb.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.bjfxy.top/Article/details/gt2xcfljopw.html

[S32] C++：字符串
来源：http://dali.fzhhl.top/Article/details/gt2hconycax.html

std::string s = "hi";  s += "!";
来源：http://dali.yangfankeji.com/Article/details/gt2gvaflqxt.html

[S33] C++：vector 增删
来源：http://dali.ydzc1.top/Article/details/gt2vrlrvyyy.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uwnxtlur.html

[S34] C++：遍历 vector
来源：http://dali.chenzaomai.com/Article/details/gt2dgrktxpx.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.jyoumei.cn/Article/details/gt2wppodxtb.html

[S35] C++：map
来源：http://dali.mhx1999.top/Article/details/gt2yectqjew.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hammf.cn/Article/details/gt2efbsgjck.html

[S36] C++：unordered_map
来源：http://dali.haohaochexian.top/Article/details/gt2ylfpiody.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hfpthk.cn/Article/details/gt2ntzooeef.html

[S37] C++：set
来源：http://dali.nwbrower.top/Article/details/gt2uqqfynvk.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.sufxvd.cn/Article/details/gt2spswqcvp.html

[S38] C++：排序
来源：http://dali.sufxvd.cn/Article/details/gt2yrmfeuqo.html

std::sort(v.begin(), v.end());
来源：http://dali.yj20258888.top/Article/details/gt2jspgzooh.html

[S39] C++：自定义比较器排序
来源：http://dali.aizwys.cn/Article/details/gt2bxoryopk.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.aizwys.cn/Article/details/gt2teluiyjr.html

[S40] C++：查找元素
来源：http://dali.zhengqikj.top/Article/details/gt2itvsqyde.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.hywenlv.cn/Article/details/gt2tqknxuwi.html

[S41] C++：类与构造函数
来源：http://dali.gotoacloud.top/Article/details/gt2tkuopzca.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.yvedp.cn/Article/details/gt2vhywqufb.html

[S42] C++：继承与虚函数
来源：http://dali.jinghuilouyu.cn/Article/details/gt2withiooa.html

class B : public Base { public: void f() override {} };
来源：http://dali.sxryk.cn/Article/details/gt2hrcaywdg.html

[S43] C++：智能指针
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zosbsqpr.html

auto p = std::make_unique<int>(5);
来源：http://dali.cucudq.cn/Article/details/gt2olqtitnj.html

[S44] C++：引用传参
来源：http://dali.snrcjt.cn/Article/details/gt2prmpiiih.html

void inc(int &x) { ++x; }
来源：http://dali.aibaodan.cn/Article/details/gt2oysllzjw.html

[S45] C++：lambda
来源：http://dali.cqqwz.cn/Article/details/gt2iqyqfvfb.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2nyscryho.html

[S46] C++：函数模板
来源：http://dali.haohaochexian.top/Article/details/gt2koyrinow.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.hfpthk.cn/Article/details/gt2jzzmlrdl.html

[S47] C++：结构化绑定遍历
来源：http://dali.dashuyun.cn/Article/details/gt2lsjtejvc.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.ydzc1.top/Article/details/gt2wkkbpgmn.html

[S48] C++：逐行读文件
来源：http://dali.shzxlz.cn/Article/details/gt2hqncxzlo.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.316326.xyz/Article/details/gt2sfjesdjd.html

while (std::getline(in, line)) { }
来源：http://dali.tanke756.top/Article/details/gt2bnnpxchz.html

[S49] C++：写文件
来源：http://dali.yongpay.top/Article/details/gt2efvtwmtr.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.cashguo.top/Article/details/gt2hfbwkwce.html

[S50] C++：格式化数字
来源：http://dali.yuxming.cn/Article/details/gt2zpzpmjud.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.jiagoushi.top/Article/details/gt2iwbkmfpg.html

[S51] C++：显式类型转换
来源：http://dali.nanxinkj.top/Article/details/gt2emlikqxe.html

static_cast<double>(a) / b
来源：http://dali.jianghu66.top/Article/details/gt2oiezopnk.html

[S52] C++：const 与 noexcept
来源：http://dali.feifeiyinyue.top/Article/details/gt2ppwrbamg.html

int size() const noexcept { return n_; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2aqcnhmji.html

[S53] C++：移动语义
来源：http://dali.dianchejie.cn/Article/details/gt2satklrie.html

std::vector<int> w = std::move(v);
来源：http://dali.ybcxt.top/Article/details/gt2anevmjeu.html

[S54] C++：异常处理
来源：http://dali.chenlongwang.top/Article/details/gt2psoxezmv.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.ivvv.top/Article/details/gt2bbzzloio.html

[S55] C++：结构化绑定
来源：http://dali.birdmap.top/Article/details/gt2plsmflle.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2hgahwbjh.html

[S56] C++：optional
来源：http://dali.cheryme.top/Article/details/gt2rxkhlomc.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yvedp.cn/Article/details/gt2xzslzwyr.html

[S57] C++：编译期常量
来源：http://dali.sysykeji.top/Article/details/gt2yppdwtpm.html

constexpr int N = 10;
来源：http://dali.tianlin.xyz/Article/details/gt2rlqnfoqf.html

[S58] C++：命名空间
来源：http://dali.cqqwz.cn/Article/details/gt2uccrzjgs.html

namespace ns { int f() { return 1; } }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zpawdmun.html

[S59] C++：静态断言
来源：http://dali.0kj1m.cn/Article/details/gt2ukshuvua.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.daxiang520.top/Article/details/gt2rokpjtty.html

[S60] C++：遍历并删除元素
来源：http://dali.ehwqpu.com/Article/details/gt2rywutfux.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.sufxvd.cn/Article/details/gt2uzfzztwp.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gt2mvvvxjex.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.cheryme.top/Article/details/gt2oobcjwfb.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2lmzsgzgq.html

[T01] Kotlin：Hello World
来源：http://dali.cheryme.top/Article/details/gt2tchisyzo.html

println("Hello")
来源：http://dali.yueranfly.top/Article/details/gt2fzvmcnrc.html

[T02] Kotlin：变量
来源：http://dali.daria6918.cn/Article/details/gt2evteaodn.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.yanxiufei.cn/Article/details/gt2bjghtwfv.html

[T03] Kotlin：字符串模板
来源：http://dali.haohaochexian.top/Article/details/gt2wxxrzqeu.html

"值: $b"
来源：http://dali.jinqigfzy.top/Article/details/gt2yiqxgtba.html

[T04] Kotlin：空安全
来源：http://dali.svipenyu.cn/Article/details/gt2uafhalvi.html

val n: String? = null;  n?.length
来源：http://dali.yongpay.top/Article/details/gt2amuravod.html

[T05] Kotlin：when 表达式
来源：http://dali.cqqwz.cn/Article/details/gt2roppagtd.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ejlrpvut.html

[T06] Kotlin：集合映射
来源：http://dali.xziqi.cn/Article/details/gt2xcyxxrpb.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zdqjudy.top/Article/details/gt2jbxleqdd.html

[T07] Kotlin：集合过滤
来源：http://dali.xuanzx.com/Article/details/gt2aqrbzeus.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.gotoacloud.top/Article/details/gt2brpyimxm.html

[T08] Kotlin：数据类
来源：http://dali.jiagoushi.top/Article/details/gt2zwgkmhoa.html

data class User(val name: String, val age: Int)
来源：http://dali.daxiang520.top/Article/details/gt2bvipjsat.html

[T09] Kotlin：扩展函数
来源：http://dali.yuanzhike.top/Article/details/gt2iipxbfnr.html

fun String.exclaim() = this + "!"
来源：http://dali.nanxuanxn.top/Article/details/gt2hdhgoeoa.html

[T10] Kotlin：默认参数
来源：http://dali.cucudq.cn/Article/details/gt2psulsqyt.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.guannengcc.top/Article/details/gt2whjgtync.html

[T11] Kotlin：协程
来源：http://dali.daxiang520.top/Article/details/gt2pimmvujq.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.316326.xyz/Article/details/gt2yorodxyi.html

[T12] Kotlin：解构声明
来源：http://dali.pengpengdd.cyou/Article/details/gt2gwcqryay.html

val (a, b) = Pair(1, 2)
来源：http://dali.gogol.net.cn/Article/details/gt2pqgdupra.html

[T13] Kotlin：只读 Map
来源：http://dali.jyoumei.cn/Article/details/gt2zffdkxnn.html

val m = mapOf("a" to 1)
来源：http://dali.yj202588.top/Article/details/gt2jpzzaxzb.html

[T14] Kotlin：循环
来源：http://dali.quarkkingdee.top/Article/details/gt2qpuyadyl.html

for (i in 1..10) println(i)
来源：http://dali.yvedp.cn/Article/details/gt2cwbcwkjl.html

[T15] Kotlin：接口
来源：http://dali.jlsjyb.cn/Article/details/gt2pizbcdtp.html

interface Shape { fun area(): Double }
来源：http://dali.cdnleiting.top/Article/details/gt2rdzrfbwy.html

[T16] Swift：Hello World
来源：http://dali.tian-w.cn/Article/details/gt2dqtlrcqk.html

print("Hello")
来源：http://dali.yongpay.top/Article/details/gt2xnshlugg.html

[T17] Swift：变量与常量
来源：http://dali.dashuyun.cn/Article/details/gt2pviuoxnq.html

var a = 1;  let b = 2
来源：http://dali.zhiwuduotai.top/Article/details/gt2abqmhbdo.html

[T18] Swift：字符串插值
来源：http://dali.wangshuangyany.cn/Article/details/gt2xeytdgfo.html

"值: \(b)"
来源：http://dali.yj20258888.top/Article/details/gt2pkwjzutp.html

[T19] Swift：可选绑定
来源：http://dali.hongshengwenyu.top/Article/details/gt2uofwzwoi.html

if let n = opt { print(n) }
来源：http://dali.fengsongda.top/Article/details/gt2oyayfiho.html

[T20] Swift：数组操作
来源：http://dali.jqgfzy.top/Article/details/gt2nretfvlj.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhiwuduotai.top/Article/details/gt2ioptjyxc.html

[T21] Swift：遍历
来源：http://dali.mhx1999.top/Article/details/gt2hkeqnxzm.html

for x in a { print(x) }
来源：http://dali.xziqi.cn/Article/details/gt2pberejip.html

[T22] Swift：字典
来源：http://dali.chenjidiqi.icu/Article/details/gt2fektahtx.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.chenzaomai.com/Article/details/gt2tvebxlcz.html

[T23] Swift：函数
来源：http://dali.tanke756.top/Article/details/gt2ahjkmdqc.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.svipenyu.cn/Article/details/gt2hywdnkdi.html

[T24] Swift：闭包
来源：http://dali.ivvv.top/Article/details/gt2efirgkoe.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.gzhubu.top/Article/details/gt2fjyxdnkb.html

[T25] Swift：结构体
来源：http://dali.gzhubu.top/Article/details/gt2rwkvzebj.html

struct P { var x: Int }
来源：http://dali.yuxming.cn/Article/details/gt2bohzxzib.html

[T26] Swift：类与重写
来源：http://dali.pengpengdd.cyou/Article/details/gt2hxoyxszl.html

class A: Base { override func f() {} }
来源：http://dali.gotoacloud.top/Article/details/gt2kdtdeolu.html

[T27] Swift：错误处理
来源：http://dali.yj20258.top/Article/details/gt2dmaekalf.html

do { try f() } catch { print(error) }
来源：http://dali.cucudq.cn/Article/details/gt2yrknmqyi.html

[T28] Swift：枚举
来源：http://dali.shuidangran.top/Article/details/gt2awzjdbyg.html

enum Color { case red, green }
来源：http://dali.yj202588.top/Article/details/gt2jstflnmj.html

[T29] Swift：guard 提前返回
来源：http://dali.smart0.xyz/Article/details/gt2aolqjgnd.html

guard let x = opt else { return }
来源：http://dali.bjfxy.top/Article/details/gt2fcwkatke.html

[T30] Swift：协议
来源：http://dali.xuetiantiany.cn/Article/details/gt2rwgxaslo.html

protocol Shape { func area() -> Double }
来源：http://dali.yonumen.top/Article/details/gt2nyntbawu.html

[T31] Lua：Hello World
来源：http://dali.iojbl.cn/Article/details/gt2reluhipn.html

print("Hello")
来源：http://dali.cheryme.top/Article/details/gt2kmdjtqzf.html

[T32] Lua：局部变量
来源：http://dali.xuetiantiany.cn/Article/details/gt2vpjwtrgz.html

local a = 1
来源：http://dali.pengpengdd.cyou/Article/details/gt2yufxhgvj.html

[T33] Lua：表（数组）
来源：http://dali.hfpthk.cn/Article/details/gt2shorhjaf.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.nanxuanxn.top/Article/details/gt2immhdxqy.html

[T34] Lua：遍历表
来源：http://dali.wangshuangyany.cn/Article/details/gt2utriviqn.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.gzhubu.top/Article/details/gt2uovjmjiz.html

[T35] Lua：字典表
来源：http://dali.snrcjt.cn/Article/details/gt2uvlexcbn.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zdqjudy.top/Article/details/gt2kfhivybz.html

[T36] Lua：函数
来源：http://dali.mhx1999.top/Article/details/gt2dcrxtwbx.html

function add(a, b) return a + b end
来源：http://dali.havefunace.top/Article/details/gt2rhuxjoxy.html

[T37] Lua：字符串拼接
来源：http://dali.xuanzx.com/Article/details/gt2mstbxnou.html

"a" .. "b"
来源：http://dali.yueranfly.top/Article/details/gt2ofxqsaxn.html

[T38] Lua：条件
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sojczzsh.html

if x > 0 then print("正") end
来源：http://dali.sxryk.cn/Article/details/gt2acfvxibv.html

[T39] Lua：模式匹配
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nfgnmfxg.html

string.find(s, "%d+")
来源：http://dali.tanke756.top/Article/details/gt2fggbcwqa.html

[T40] Lua：元表
来源：http://dali.pycfn.com/Article/details/gt2oskxgaxp.html

setmetatable({}, { __index = base })
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gfytiqvr.html

[T41] Perl：Hello World
来源：http://dali.smart0.xyz/Article/details/gt2vchdqela.html

print "Hello\n";
来源：http://dali.ehwqpu.com/Article/details/gt2zczdpwim.html

[T42] Perl：变量类型
来源：http://dali.cdnleiting.top/Article/details/gt2huvvpymh.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.gogol.net.cn/Article/details/gt2vdiejqwf.html

[T43] Perl：字符串插值
来源：http://dali.guowangkeji.top/Article/details/gt2xyslsmfg.html

"值: $a"
来源：http://dali.sysykeji.top/Article/details/gt2yjysywfe.html

[T44] Perl：条件
来源：http://dali.xylfe.cn/Article/details/gt2oloafrjj.html

if ($a > 0) { print "正"; }
来源：http://dali.cashguo.top/Article/details/gt2ktgfigcm.html

[T45] Perl：数组遍历
来源：http://dali.pengpengdd.cyou/Article/details/gt2cmbnchbr.html

for my $x (@arr) { print $x; }
来源：http://dali.andypj.xyz/Article/details/gt2pilpsxiu.html

[T46] Perl：哈希操作
来源：http://dali.zhiwuduotai.top/Article/details/gt2xglsvcch.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.cdnleiting.top/Article/details/gt2lkppprhw.html

[T47] Perl：正则捕获
来源：http://dali.zhoulong.xyz/Article/details/gt2xoxkiqbr.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.xziqi.cn/Article/details/gt2gtkmeymd.html

[T48] Perl：正则替换
来源：http://dali.snrcjt.cn/Article/details/gt2exoichgt.html

$s =~ s/old/new/g;
来源：http://dali.cqqwz.cn/Article/details/gt2gtdcptom.html

[T49] Perl：函数
来源：http://dali.guannengcc.top/Article/details/gt2vrahzjfh.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zycfv.cn/Article/details/gt2hkyvaczw.html

[T50] Perl：逐行读文件
来源：http://dali.shuidangran.top/Article/details/gt2aaeworwr.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.nanxuanxn.top/Article/details/gt2efnjiqew.html


<!-- 参考信息 -->