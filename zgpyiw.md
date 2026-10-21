代发 wailian999

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhoulong.xyz/Article/details/gtuayzadck.html

[R52] 统计行数
来源：http://dali.yuxming.cn/Article/details/gtenqsiofr.html

wc -l a.txt
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkfrjwvgh.html

[R53] 查看文件头与实时尾
来源：http://dali.ppjwa.cn/Article/details/gttctgcxkw.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.sweek.top/Article/details/gtpvbpdtym.html

[R54] 比较两个文件
来源：http://dali.vqdsnc.cn/Article/details/gttcgbegub.html

diff a.txt b.txt
来源：http://dali.yangfankeji.com/Article/details/gtwofjxogo.html

[R55] 压缩与解压
来源：http://dali.jiagoushi.top/Article/details/gtyxfsvkud.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.cdnleiting.top/Article/details/gtxfytspoq.html

[R56] 远程拷贝
来源：http://dali.yanxiufei.cn/Article/details/gtymtcawpy.html

scp file user@host:/path/
来源：http://dali.ehwqpu.com/Article/details/gtlklcmpdx.html

[R57] 远程执行命令
来源：http://dali.daria6918.cn/Article/details/gtljwgvltb.html

ssh user@host 'uptime'
来源：http://dali.c1oappe.top/Article/details/gtbhefncpn.html

[R58] 下载文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqzytylzg.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.cdnleiting.top/Article/details/gtqltjnrzl.html

[R59] 发 POST JSON
来源：http://dali.daxiang520.top/Article/details/gtnvxflyif.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.yangfankeji.com/Article/details/gtkjgwsdmr.html

[R60] 只看 HTTP 状态码
来源：http://dali.wangdashe.top/Article/details/gtykjtarog.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.jqgfzy.top/Article/details/gtbusnqehs.html

[R61] 磁盘占用
来源：http://dali.meibo888.top/Article/details/gtcftoauvi.html

df -h;  du -sh *
来源：http://dali.chenlongwang.top/Article/details/gtlsmmdfmt.html

[R62] 找最占空间的文件
来源：http://dali.sweek.top/Article/details/gtyrqskuex.html

du -ah . | sort -rh | head -10
来源：http://dali.aibaodan.cn/Article/details/gtbtnpskkp.html

[R63] 内存与进程
来源：http://dali.sweek.top/Article/details/gtticazjfd.html

free -h;  ps aux | grep nginx
来源：http://dali.chenjidiqi.icu/Article/details/gteyrzfzpy.html

[R64] 结束进程
来源：http://dali.cdnleiting.top/Article/details/gtuysqgrhy.html

kill -9 $(pgrep -f app.py)
来源：http://dali.guowangkeji.top/Article/details/gtuaecmcuo.html

[R65] 查看端口占用
来源：http://dali.aibaodan.cn/Article/details/gtwaopcdgp.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.vqdsnc.cn/Article/details/gtqnbekihx.html

[R66] 定时任务
来源：http://dali.guannengcc.top/Article/details/gtgnmutuds.html

crontab -e;  crontab -l
来源：http://dali.pengpengdd.cyou/Article/details/gtiznqqzog.html

[R67] 生成随机十六进制串
来源：http://dali.shuidangran.top/Article/details/gtwojesdhp.html

openssl rand -hex 16
来源：http://dali.cdnleiting.top/Article/details/gtgfhzrthf.html

[R68] 计算文件校验值
来源：http://dali.hywenlv.cn/Article/details/gtxmfbtglb.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.ehwqpu.com/Article/details/gtjqspkmwo.html

[R69] 生成随机密码
来源：http://dali.ydzc1.top/Article/details/gtpyvndrfh.html

head -c 16 /dev/urandom | base64
来源：http://dali.nanxinkj.top/Article/details/gtyvcchptb.html

[R70] 时间戳与互转
来源：http://dali.ivvv.top/Article/details/gtkhuqpkyk.html

date +%s;  date -d @1700000000
来源：http://dali.zhiwuduotai.top/Article/details/gtjjrviwqm.html

[R71] 日期格式化
来源：http://dali.sysykeji.top/Article/details/gtdovjcyml.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.chenzaomai.com/Article/details/gtltxszttz.html

[R72] 等待端口就绪
来源：http://dali.zhongyouzk.top/Article/details/gtujutgkix.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.sufxvd.cn/Article/details/gtnbkfqfli.html

[R73] 分割大日志
来源：http://dali.yj20258.top/Article/details/gtoplvhpbu.html

split -l 1000 big.log part_
来源：http://dali.zhengqikj.top/Article/details/gtdzlbtglz.html

[R74] 批量重命名
来源：http://dali.fzhhl.top/Article/details/gtsafgwtvy.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.ppjwa.cn/Article/details/gtgmybmlrc.html

[R75] 导出环境变量
来源：http://dali.jinghuilouyu.cn/Article/details/gtmtxvzvqp.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.hysaishi.cn/Article/details/gtevgmobwa.html

[R76] 使用临时文件
来源：http://dali.redwolf501.top/Article/details/gtlvwugwjw.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhengqikj.top/Article/details/gtvseapgpt.html

[R77] 读取用户输入
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoauuqbva.html

read -rp "请输入: " ans
来源：http://dali.sysykeji.top/Article/details/gtjnbpaomy.html

[R78] 交互式菜单
来源：http://dali.iojbl.cn/Article/details/gtaxdeupeu.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.pengpengdd.cyou/Article/details/gtfatpfviq.html

[R79] 解析命令行选项
来源：http://dali.chenzaomai.com/Article/details/gtukqwsxvy.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.havefunace.top/Article/details/gtcsrmzwiu.html

[R80] 查看脚本执行耗时
来源：http://dali.chenjidiqi.icu/Article/details/gthzdrbbhd.html

time ./run.sh
来源：http://dali.xuanzx.com/Article/details/gtsgnmvfxl.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtiuyiyamz.html

S. C / C++ 专题
来源：http://dali.hnqzz.top/Article/details/gtmpuzcdqj.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtipeazwbm.html

[S01] C：Hello World
来源：http://dali.fengsongda.top/Article/details/gttumlymxa.html

#include <stdio.h>
来源：http://dali.yvedp.cn/Article/details/gtakqcscma.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.cqqwz.cn/Article/details/gtylssuvum.html

[S02] C：变量与格式化输出
来源：http://dali.0kj1m.cn/Article/details/gtcrvbzoah.html

int a = 10; printf("%d\n", a);
来源：http://dali.sysykeji.top/Article/details/gtptdwhrfc.html

[S03] C：读入整数
来源：http://dali.chenjidiqi.icu/Article/details/gtpgwivcwg.html

int x; scanf("%d", &x);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzairpbde.html

[S04] C：字符串复制
来源：http://dali.hywenlv.cn/Article/details/gtblxavoeh.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfiecpmom.html

[S05] C：字符串长度
来源：http://dali.meibo888.top/Article/details/gtmzlsamob.html

strlen(s)
来源：http://dali.yuanzhike.top/Article/details/gtadseyvww.html

[S06] C：字符串比较
来源：http://dali.haohaochexian.top/Article/details/gtlzfhrnkn.html

strcmp(a, b) == 0
来源：http://dali.tian-w.cn/Article/details/gtubcwghik.html

[S07] C：数组遍历求和
来源：http://dali.yueranfly.top/Article/details/gtdxamglye.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.jyoumei.cn/Article/details/gtwopsxxvl.html

[S08] C：动态内存分配与释放
来源：http://dali.gotoacloud.top/Article/details/gtbelzijpl.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.aibaodan.cn/Article/details/gtackqiynl.html

[S09] C：结构体定义与初始化
来源：http://dali.shzxlz.cn/Article/details/gtnnmaqnin.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.wangshuangyany.cn/Article/details/gtjsfnxgfh.html

[S10] C：指针与解引用
来源：http://dali.zhaomingkeji.xyz/Article/details/gtucayjhaw.html

int *p = &a;  *p = 5;
来源：http://dali.daxiang520.top/Article/details/gtlptsqfzj.html

[S11] C：逐行读文件
来源：http://dali.zhiwuduotai.top/Article/details/gtmqapseln.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.ppjwa.cn/Article/details/gtvbfeqqeg.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.cdnleiting.top/Article/details/gtmxjduanv.html

fclose(f);
来源：http://dali.ehwqpu.com/Article/details/gtijlmbqlv.html

[S12] C：写文件
来源：http://dali.mhx1999.top/Article/details/gtaaexyxiv.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.shangyingyoupin.top/Article/details/gtxtnecsli.html

[S13] C：宏定义
来源：http://dali.haohaochexian.top/Article/details/gtqvdtehcw.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.shanyushiyangtech.top/Article/details/gtafhxcoop.html

[S14] C：枚举
来源：http://dali.sweek.top/Article/details/gtvpqecjvs.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gterbwmeyc.html

[S15] C：类型转换
来源：http://dali.cqqwz.cn/Article/details/gtoabbvsgx.html

(double) a / b
来源：http://dali.0kj1m.cn/Article/details/gtesdopwey.html

[S16] C：位操作置位
来源：http://dali.yonumen.top/Article/details/gtagkuuzoh.html

x |= (1 << 3);
来源：http://dali.chenzaomai.com/Article/details/gtvozgupsb.html

[S17] C：安全拼接字符串
来源：http://dali.dashuyun.cn/Article/details/gtltcedipf.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxhmdjbtw.html

[S18] C：命令行参数
来源：http://dali.nanxinkj.top/Article/details/gtthrqojpc.html

int main(int argc, char **argv)
来源：http://dali.birdmap.top/Article/details/gtfjhyyklt.html

[S19] C：快速排序
来源：http://dali.316326.xyz/Article/details/gttcjjmyzg.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.tianlin.xyz/Article/details/gtplorfzyb.html

[S20] C：二分查找
来源：http://dali.hnxiangtu.top/Article/details/gtyckkvqkv.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.gzhubu.top/Article/details/gtxjubpaym.html

[S21] C：字符类别判断
来源：http://dali.zdqjudy.top/Article/details/gtjfyjrksa.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.cqqwz.cn/Article/details/gtpnbummzu.html

[S22] C：字符串转数字
来源：http://dali.chenzaomai.com/Article/details/gtcbhhtlfu.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gthorneaum.html

[S23] C：随机数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxnylhrvt.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.gogol.net.cn/Article/details/gtnidopajg.html

[S24] C：获取本地时间
来源：http://dali.zdqjudy.top/Article/details/gtbdrsghnl.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gtrvewpjfq.html

[S25] C：内存拷贝
来源：http://dali.c1oappe.top/Article/details/gtdiulzepl.html

memcpy(dst, src, n);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvucxcgnt.html

[S26] C：内存清零
来源：http://dali.yvedp.cn/Article/details/gtlwuoeith.html

memset(a, 0, sizeof a);
来源：http://dali.redwolf501.top/Article/details/gtbvhpvftp.html

[S27] C：定义常量
来源：http://dali.xylfe.cn/Article/details/gtrnjejdsb.html

const double PI = 3.14159;
来源：http://dali.gogol.net.cn/Article/details/gtyhwhqkmh.html

[S28] C：静态变量
来源：http://dali.c1oappe.top/Article/details/gtzdcnfsxc.html

static int counter = 0;
来源：http://dali.ppjwa.cn/Article/details/gttrmajkua.html

[S29] C：变参函数
来源：http://dali.ehwqpu.com/Article/details/gtatjaarow.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.chenzaomai.com/Article/details/gtdqmhjqrs.html

[S30] C：头文件保护
来源：http://dali.yuxming.cn/Article/details/gtsdrcqkzp.html

#ifndef X_H
来源：http://dali.quarkkingdee.top/Article/details/gtpcdozpfe.html

#define X_H
来源：http://dali.meibo888.top/Article/details/gtchimizgr.html

#endif
来源：http://dali.c1oappe.top/Article/details/gtxbjcospf.html

[S31] C++：Hello World
来源：http://dali.gzhubu.top/Article/details/gtpgtxrfar.html

#include <iostream>
来源：http://dali.yvedp.cn/Article/details/gtteeznlqb.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.hnxiangtu.top/Article/details/gtxdvcupis.html

[S32] C++：字符串
来源：http://dali.jianghu66.top/Article/details/gticudxnds.html

std::string s = "hi";  s += "!";
来源：http://dali.fengsongda.top/Article/details/gtuchkhzxh.html

[S33] C++：vector 增删
来源：http://dali.bjfxy.top/Article/details/gtqxmhnrzj.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.0kj1m.cn/Article/details/gtihkclmoz.html

[S34] C++：遍历 vector
来源：http://dali.jinqigufen.top/Article/details/gtgqdfrrcp.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.shuidangran.top/Article/details/gtidjwezpf.html

[S35] C++：map
来源：http://dali.iojbl.cn/Article/details/gtuozbfpan.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yueranfly.top/Article/details/gtgpudoohz.html

[S36] C++：unordered_map
来源：http://dali.ivvv.top/Article/details/gttfybnexg.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zycfv.cn/Article/details/gtywllgdht.html

[S37] C++：set
来源：http://dali.chenzaomai.com/Article/details/gtpwscwtoo.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.tanke756.top/Article/details/gtinixytfg.html

[S38] C++：排序
来源：http://dali.redwolf501.top/Article/details/gtpdioxfhf.html

std::sort(v.begin(), v.end());
来源：http://dali.hongshengwenyu.top/Article/details/gtzqcuvnym.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gtftuknbab.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.aibaodan.cn/Article/details/gtlifninri.html

[S40] C++：查找元素
来源：http://dali.jinqigufen.top/Article/details/gttsjogghn.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.shuidangran.top/Article/details/gtcmuthpzl.html

[S41] C++：类与构造函数
来源：http://dali.aizwys.cn/Article/details/gtqkbthscl.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.ydzc1.top/Article/details/gtbdtoxjfz.html

[S42] C++：继承与虚函数
来源：http://dali.hfpthk.cn/Article/details/gtitdolzks.html

class B : public Base { public: void f() override {} };
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjwbdqhgm.html

[S43] C++：智能指针
来源：http://dali.aibaodan.cn/Article/details/gtwpegaglr.html

auto p = std::make_unique<int>(5);
来源：http://dali.hammf.cn/Article/details/gtazqcsfmt.html

[S44] C++：引用传参
来源：http://dali.iojbl.cn/Article/details/gtvjnxlrky.html

void inc(int &x) { ++x; }
来源：http://dali.redwolf501.top/Article/details/gtaumnttmz.html

[S45] C++：lambda
来源：http://dali.yvedp.cn/Article/details/gtgvcwcbix.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.xuanzx.com/Article/details/gttjnymncj.html

[S46] C++：函数模板
来源：http://dali.gotoacloud.top/Article/details/gtguqamycr.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.daxiang520.top/Article/details/gtjixqaqjj.html

[S47] C++：结构化绑定遍历
来源：http://dali.tanke756.top/Article/details/gtrxmdrhmz.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.aizwys.cn/Article/details/gtwabrtocr.html

[S48] C++：逐行读文件
来源：http://dali.cashguo.top/Article/details/gtsvgtsmqu.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.jqgfzy.top/Article/details/gtafrfrion.html

while (std::getline(in, line)) { }
来源：http://dali.haohaochexian.top/Article/details/gtybnrufsa.html

[S49] C++：写文件
来源：http://dali.shangyingyoupin.top/Article/details/gteldinilq.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.yanxiufei.cn/Article/details/gtylnceqdw.html

[S50] C++：格式化数字
来源：http://dali.snrcjt.cn/Article/details/gtvwczgbax.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.jqgfzy.top/Article/details/gtxuizggpx.html

[S51] C++：显式类型转换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpaxmsloq.html

static_cast<double>(a) / b
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvcatyviz.html

[S52] C++：const 与 noexcept
来源：http://dali.birdmap.top/Article/details/gtdooohgej.html

int size() const noexcept { return n_; }
来源：http://dali.yj202588.top/Article/details/gttvcrzjbl.html

[S53] C++：移动语义
来源：http://dali.guowangkeji.top/Article/details/gtbhscpzne.html

std::vector<int> w = std::move(v);
来源：http://dali.zhiwuduotai.top/Article/details/gtxxbxmidw.html

[S54] C++：异常处理
来源：http://dali.zhongyouzk.top/Article/details/gtmypdwesz.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.fengsongda.top/Article/details/gtaelavolq.html

[S55] C++：结构化绑定
来源：http://dali.nanxinkj.top/Article/details/gtnrntihut.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.hongshengwenyu.top/Article/details/gttelzneyj.html

[S56] C++：optional
来源：http://dali.yanxiufei.cn/Article/details/gtlakqicsa.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yueranfly.top/Article/details/gtoidlmdsp.html

[S57] C++：编译期常量
来源：http://dali.xuetiantiany.cn/Article/details/gtufgveoqv.html

constexpr int N = 10;
来源：http://dali.daria6918.cn/Article/details/gthltvzmuu.html

[S58] C++：命名空间
来源：http://dali.birdmap.top/Article/details/gtqrxtnfsu.html

namespace ns { int f() { return 1; } }
来源：http://dali.cheryme.top/Article/details/gtrigkqwcl.html

[S59] C++：静态断言
来源：http://dali.snrcjt.cn/Article/details/gtzgtmyggj.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.yangfankeji.com/Article/details/gtgshmuaxd.html

[S60] C++：遍历并删除元素
来源：http://dali.yj202588.top/Article/details/gtmlifwbpz.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.quarkkingdee.top/Article/details/gtfqmxjnph.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtrimhlwti.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.jlsjyb.cn/Article/details/gtrpdhgvdq.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtabwxeppm.html

[T01] Kotlin：Hello World
来源：http://dali.hysaishi.cn/Article/details/gtrohrpldw.html

println("Hello")
来源：http://dali.gotoacloud.top/Article/details/gttcohmtif.html

[T02] Kotlin：变量
来源：http://dali.fzhhl.top/Article/details/gtpklnwdsz.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.mhx1999.top/Article/details/gttyyteukd.html

[T03] Kotlin：字符串模板
来源：http://dali.wangshuangyany.cn/Article/details/gtcyeubhdl.html

"值: $b"
来源：http://dali.dianchejie.cn/Article/details/gtehwdlzjn.html

[T04] Kotlin：空安全
来源：http://dali.yanxiufei.cn/Article/details/gtmrjdudfb.html

val n: String? = null;  n?.length
来源：http://dali.gogol.net.cn/Article/details/gtjvnmelrx.html

[T05] Kotlin：when 表达式
来源：http://dali.zhengqikj.top/Article/details/gtlujfdjwz.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.nanxinkj.top/Article/details/gteugxlvsz.html

[T06] Kotlin：集合映射
来源：http://dali.kuanghao11.cn/Article/details/gtlrhwbool.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnrrulota.html

[T07] Kotlin：集合过滤
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbxydgrxk.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkcvjlcuz.html

[T08] Kotlin：数据类
来源：http://dali.ydzc1.top/Article/details/gtlukhzost.html

data class User(val name: String, val age: Int)
来源：http://dali.jiagoushi.top/Article/details/gtspaklolr.html

[T09] Kotlin：扩展函数
来源：http://dali.zycfv.cn/Article/details/gtnspvryhd.html

fun String.exclaim() = this + "!"
来源：http://dali.nanxinkj.top/Article/details/gtgcmrfbry.html

[T10] Kotlin：默认参数
来源：http://dali.hywenlv.cn/Article/details/gtbvxnytjz.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.bjfxy.top/Article/details/gtjtkucibh.html

[T11] Kotlin：协程
来源：http://dali.yongpay.top/Article/details/gtvytnewjk.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.wangshuangyany.cn/Article/details/gtgabzmfus.html

[T12] Kotlin：解构声明
来源：http://dali.hysaishi.cn/Article/details/gtkwqpkuwy.html

val (a, b) = Pair(1, 2)
来源：http://dali.shzxlz.cn/Article/details/gtzhkifalp.html

[T13] Kotlin：只读 Map
来源：http://dali.haohaochexian.top/Article/details/gtliwmjgmi.html

val m = mapOf("a" to 1)
来源：http://dali.wangdashe.top/Article/details/gtnpbfldgy.html

[T14] Kotlin：循环
来源：http://dali.vqdsnc.cn/Article/details/gtusohmtuc.html

for (i in 1..10) println(i)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdrjvfbqh.html

[T15] Kotlin：接口
来源：http://dali.andypj.xyz/Article/details/gtyfldtlmo.html

interface Shape { fun area(): Double }
来源：http://dali.cashguo.top/Article/details/gtbdqeibbq.html

[T16] Swift：Hello World
来源：http://dali.daria6918.cn/Article/details/gtjnycawpq.html

print("Hello")
来源：http://dali.c1oappe.top/Article/details/gtawefryhf.html

[T17] Swift：变量与常量
来源：http://dali.jlsjyb.cn/Article/details/gtmvwqiayu.html

var a = 1;  let b = 2
来源：http://dali.9152youxi.cn/Article/details/gtqfysbafw.html

[T18] Swift：字符串插值
来源：http://dali.jlsjyb.cn/Article/details/gtzadmruso.html

"值: \(b)"
来源：http://dali.fzhhl.top/Article/details/gtwwjdcgtq.html

[T19] Swift：可选绑定
来源：http://dali.c1oappe.top/Article/details/gthgfnhagg.html

if let n = opt { print(n) }
来源：http://dali.cdnleiting.top/Article/details/gtvfbcjexi.html

[T20] Swift：数组操作
来源：http://dali.pengpengdd.cyou/Article/details/gtrqcbdxsf.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.pengpengdd.cyou/Article/details/gtllfakmmr.html

[T21] Swift：遍历
来源：http://dali.yj20258.top/Article/details/gtztjziaow.html

for x in a { print(x) }
来源：http://dali.xuetiantiany.cn/Article/details/gthstwhkqm.html

[T22] Swift：字典
来源：http://dali.tianlin.xyz/Article/details/gtvajjoxcr.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.meibo888.top/Article/details/gtnlrpzbzs.html

[T23] Swift：函数
来源：http://dali.ehwqpu.com/Article/details/gtswwvhddx.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.tianlin.xyz/Article/details/gtcloyrqym.html

[T24] Swift：闭包
来源：http://dali.xylfe.cn/Article/details/gtgzfnbwar.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.birdmap.top/Article/details/gtkuehflci.html

[T25] Swift：结构体
来源：http://dali.redwolf501.top/Article/details/gtfelebvrc.html

struct P { var x: Int }
来源：http://dali.jiagoushi.top/Article/details/gtrqhrwlui.html

[T26] Swift：类与重写
来源：http://dali.zhiwuduotai.top/Article/details/gtrqbetpnp.html

class A: Base { override func f() {} }
来源：http://dali.nwbrower.top/Article/details/gtxulumfbh.html

[T27] Swift：错误处理
来源：http://dali.yangfankeji.com/Article/details/gtcmddjfoj.html

do { try f() } catch { print(error) }
来源：http://dali.jlsjyb.cn/Article/details/gtqjqsnjbq.html

[T28] Swift：枚举
来源：http://dali.hnqzz.top/Article/details/gtturuplwn.html

enum Color { case red, green }
来源：http://dali.birdmap.top/Article/details/gtwooickrn.html

[T29] Swift：guard 提前返回
来源：http://dali.tianlin.xyz/Article/details/gtertufjrg.html

guard let x = opt else { return }
来源：http://dali.dianchejie.cn/Article/details/gtumelqevi.html

[T30] Swift：协议
来源：http://dali.meibo888.top/Article/details/gttydnostk.html

protocol Shape { func area() -> Double }
来源：http://dali.316326.xyz/Article/details/gthwbcymhv.html

[T31] Lua：Hello World
来源：http://dali.shanyushiyangtech.top/Article/details/gtquamtwnb.html

print("Hello")
来源：http://dali.dianchejie.cn/Article/details/gtjcpxjsms.html

[T32] Lua：局部变量
来源：http://dali.hongshengwenyu.top/Article/details/gtahsilduq.html

local a = 1
来源：http://dali.gzhubu.top/Article/details/gtvudexvoj.html

[T33] Lua：表（数组）
来源：http://dali.cashguo.top/Article/details/gtdwjcikeu.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.jinghuilouyu.cn/Article/details/gtizhvauiu.html

[T34] Lua：遍历表
来源：http://dali.zhixingplan.top/Article/details/gttaqiyepp.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.316326.xyz/Article/details/gtvmlmowmk.html

[T35] Lua：字典表
来源：http://dali.zhoulong.xyz/Article/details/gtmmauckfb.html

local d = { a = 1 };  d.b = 2
来源：http://dali.cheryme.top/Article/details/gtpvmdfntq.html

[T36] Lua：函数
来源：http://dali.guannengcc.top/Article/details/gtdvghtvkb.html

function add(a, b) return a + b end
来源：http://dali.tianlin.xyz/Article/details/gtjzgvxlkl.html

[T37] Lua：字符串拼接
来源：http://dali.0kj1m.cn/Article/details/gtzsfxojsk.html

"a" .. "b"
来源：http://dali.zhiwuduotai.top/Article/details/gttmnthxka.html

[T38] Lua：条件
来源：http://dali.yj20258888.top/Article/details/gtznctciaa.html

if x > 0 then print("正") end
来源：http://dali.redwolf501.top/Article/details/gtshmpzaio.html

[T39] Lua：模式匹配
来源：http://dali.cdnleiting.top/Article/details/gtcmfrjnib.html

string.find(s, "%d+")
来源：http://dali.feifeiyinyue.top/Article/details/gtbkmgfghm.html

[T40] Lua：元表
来源：http://dali.nwbrower.top/Article/details/gtuvnyhssk.html

setmetatable({}, { __index = base })
来源：http://dali.hysaishi.cn/Article/details/gtvqwcpqpf.html

[T41] Perl：Hello World
来源：http://dali.shzxlz.cn/Article/details/gtkxnapqad.html

print "Hello\n";
来源：http://dali.vqdsnc.cn/Article/details/gtisprptgg.html

[T42] Perl：变量类型
来源：http://dali.feifeiyinyue.top/Article/details/gtigvimfwu.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.ivvv.top/Article/details/gtgrfvdkar.html

[T43] Perl：字符串插值
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnzggxplw.html

"值: $a"
来源：http://dali.aibaodan.cn/Article/details/gtxhkqvrzu.html

[T44] Perl：条件
来源：http://dali.redwolf501.top/Article/details/gtgowhqxdt.html

if ($a > 0) { print "正"; }
来源：http://dali.svipenyu.cn/Article/details/gtppxlmtnt.html

[T45] Perl：数组遍历
来源：http://dali.sweek.top/Article/details/gthavzjszt.html

for my $x (@arr) { print $x; }
来源：http://dali.yj202588.top/Article/details/gtbiztnyoa.html

[T46] Perl：哈希操作
来源：http://dali.hammf.cn/Article/details/gtqvqfezgd.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.xinyue.icu/Article/details/gtotysxbib.html

[T47] Perl：正则捕获
来源：http://dali.cucudq.cn/Article/details/gtxvugvylm.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.havefunace.top/Article/details/gtxytqlfmt.html

[T48] Perl：正则替换
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdoxmjwap.html

$s =~ s/old/new/g;
来源：http://dali.zhiwuduotai.top/Article/details/gtfgghzbwp.html

[T49] Perl：函数
来源：http://dali.smart0.xyz/Article/details/gtfctoprhr.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.guowangkeji.top/Article/details/gttikjukfg.html

[T50] Perl：逐行读文件
来源：http://dali.cheryme.top/Article/details/gtvmvxalnw.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.xylfe.cn/Article/details/gtojsybxld.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.sweek.top/Article/details/gtcqvxsfga.html

[T51] Scala：Hello World
来源：http://dali.c1oappe.top/Article/details/gtbyxfltys.html

println("Hello")
来源：http://dali.yanxiufei.cn/Article/details/gtzkjqqnck.html

[T52] Scala：变量
来源：http://dali.zhongyouzk.top/Article/details/gtpegyimoj.html

val a = 1;  var b = 2
来源：http://dali.sysykeji.top/Article/details/gtckcsfxfm.html

[T53] Scala：字符串插值
来源：http://dali.smart0.xyz/Article/details/gtmzjzclzf.html

s"值: $b"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtabcvgtts.html

[T54] Scala：集合映射
来源：http://dali.redwolf501.top/Article/details/gtdupgbeqm.html


<!-- 参考信息 -->