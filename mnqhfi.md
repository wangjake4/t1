代发 wailian999

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.sweek.top/Article/details/gtcaaqkkwc.html

[R50] awk 求和
来源：http://dali.shzxlz.cn/Article/details/gttbrkquhx.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.yuxming.cn/Article/details/gtjegrehit.html

[R51] 排序去重取前几
来源：http://dali.jqgfzy.top/Article/details/gtottjxnfv.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhengqikj.top/Article/details/gtqbpxohwp.html

[R52] 统计行数
来源：http://dali.tian-w.cn/Article/details/gtrounktyz.html

wc -l a.txt
来源：http://dali.cheryme.top/Article/details/gtxxgupytp.html

[R53] 查看文件头与实时尾
来源：http://dali.sweek.top/Article/details/gtsjstsyxk.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.tianlin.xyz/Article/details/gthhorjxwh.html

[R54] 比较两个文件
来源：http://dali.yuanzhike.top/Article/details/gtjxtsrakj.html

diff a.txt b.txt
来源：http://dali.cdnleiting.top/Article/details/gtolrjrjzb.html

[R55] 压缩与解压
来源：http://dali.zycfv.cn/Article/details/gtqkefcqin.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.quarkkingdee.top/Article/details/gtetkptraz.html

[R56] 远程拷贝
来源：http://dali.jqgfzy.top/Article/details/gtkqbwcowx.html

scp file user@host:/path/
来源：http://dali.yuxming.cn/Article/details/gtinlwwbnd.html

[R57] 远程执行命令
来源：http://dali.yj202588.top/Article/details/gtmyhmqyss.html

ssh user@host 'uptime'
来源：http://dali.tianlin.xyz/Article/details/gtabmzexmp.html

[R58] 下载文件
来源：http://dali.cucudq.cn/Article/details/gtdwyscmgn.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.yj202588.top/Article/details/gtfmtmslhg.html

[R59] 发 POST JSON
来源：http://dali.tianlin.xyz/Article/details/gttfrifmkr.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.dashuyun.cn/Article/details/gtnohtusjm.html

[R60] 只看 HTTP 状态码
来源：http://dali.snrcjt.cn/Article/details/gtylzkxskk.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.nwbrower.top/Article/details/gteriigxlb.html

[R61] 磁盘占用
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbxtsiocl.html

df -h;  du -sh *
来源：http://dali.feifeiyinyue.top/Article/details/gtziumddad.html

[R62] 找最占空间的文件
来源：http://dali.sxryk.cn/Article/details/gtdccdvyoq.html

du -ah . | sort -rh | head -10
来源：http://dali.havefunace.top/Article/details/gtrmxjnads.html

[R63] 内存与进程
来源：http://dali.daria6918.cn/Article/details/gtwnmntepc.html

free -h;  ps aux | grep nginx
来源：http://dali.hywenlv.cn/Article/details/gtcszempjt.html

[R64] 结束进程
来源：http://dali.sufxvd.cn/Article/details/gtdigsrqfs.html

kill -9 $(pgrep -f app.py)
来源：http://dali.pycfn.com/Article/details/gtilhkycdn.html

[R65] 查看端口占用
来源：http://dali.chenjidiqi.icu/Article/details/gtdzmjqiqu.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.andypj.xyz/Article/details/gtpaxuhavo.html

[R66] 定时任务
来源：http://dali.sxryk.cn/Article/details/gtwctxqkzf.html

crontab -e;  crontab -l
来源：http://dali.shzxlz.cn/Article/details/gtozktvrov.html

[R67] 生成随机十六进制串
来源：http://dali.jianghu66.top/Article/details/gtzlslrnhh.html

openssl rand -hex 16
来源：http://dali.hywenlv.cn/Article/details/gtxrykejjp.html

[R68] 计算文件校验值
来源：http://dali.hysaishi.cn/Article/details/gtllaziyad.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.chenjidiqi.icu/Article/details/gtinfwrhhs.html

[R69] 生成随机密码
来源：http://dali.shuidangran.top/Article/details/gtlqycbozf.html

head -c 16 /dev/urandom | base64
来源：http://dali.jqgufenzy.top/Article/details/gtwwocqnkw.html

[R70] 时间戳与互转
来源：http://dali.cheryme.top/Article/details/gtwovewizs.html

date +%s;  date -d @1700000000
来源：http://dali.wangdashe.top/Article/details/gttkkljvbi.html

[R71] 日期格式化
来源：http://dali.yonumen.top/Article/details/gtnbizewva.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.jinghuilouyu.cn/Article/details/gtunlcyeyt.html

[R72] 等待端口就绪
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtewsrawbc.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.gogol.net.cn/Article/details/gtuqgbknjs.html

[R73] 分割大日志
来源：http://dali.chenzaomai.com/Article/details/gtlkvzyhkt.html

split -l 1000 big.log part_
来源：http://dali.gaohongyu789.top/Article/details/gttizhyggn.html

[R74] 批量重命名
来源：http://dali.ydzc1.top/Article/details/gtixqhepdk.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.aibaodan.cn/Article/details/gtlyshuwzd.html

[R75] 导出环境变量
来源：http://dali.xuanzx.com/Article/details/gteoojisxf.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.yongpay.top/Article/details/gttastopis.html

[R76] 使用临时文件
来源：http://dali.gaohongyu789.top/Article/details/gtdjnuerjg.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.wangshuangyany.cn/Article/details/gtnycovcry.html

[R77] 读取用户输入
来源：http://dali.tian-w.cn/Article/details/gtyzstlwyn.html

read -rp "请输入: " ans
来源：http://dali.andypj.xyz/Article/details/gthhbztmmf.html

[R78] 交互式菜单
来源：http://dali.9152youxi.cn/Article/details/gtpawnxqli.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.nwbrower.top/Article/details/gtlmrowvzy.html

[R79] 解析命令行选项
来源：http://dali.sweek.top/Article/details/gtrajhjpfj.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.ywan-chungtsiang.top/Article/details/gttijczghm.html

[R80] 查看脚本执行耗时
来源：http://dali.yonumen.top/Article/details/gtzeudlfva.html

time ./run.sh
来源：http://dali.dashuyun.cn/Article/details/gttozddgub.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtcrfioypp.html

S. C / C++ 专题
来源：http://dali.zhixingplan.top/Article/details/gtmyiccciu.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtrrnegbua.html

[S01] C：Hello World
来源：http://dali.andypj.xyz/Article/details/gtikgvsicb.html

#include <stdio.h>
来源：http://dali.nanxuanxn.top/Article/details/gtfmycacqd.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.jiagoushi.top/Article/details/gtrlpfnkie.html

[S02] C：变量与格式化输出
来源：http://dali.xinyue.icu/Article/details/gtyoystnak.html

int a = 10; printf("%d\n", a);
来源：http://dali.aizwys.cn/Article/details/gtthxqnssd.html

[S03] C：读入整数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnqrfdqzs.html

int x; scanf("%d", &x);
来源：http://dali.tanke756.top/Article/details/gttbtyjpxt.html

[S04] C：字符串复制
来源：http://dali.xylfe.cn/Article/details/gtdscsroys.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.shanyushiyangkeji.top/Article/details/gttdnwdicb.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gthxfedcve.html

strlen(s)
来源：http://dali.yonumen.top/Article/details/gtvnmpmlbw.html

[S06] C：字符串比较
来源：http://dali.cheryme.top/Article/details/gtafsscoxt.html

strcmp(a, b) == 0
来源：http://dali.zhoulong.xyz/Article/details/gtpmidmxip.html

[S07] C：数组遍历求和
来源：http://dali.hammf.cn/Article/details/gtdnzvkjcj.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.nwbrower.top/Article/details/gtrivmqnpp.html

[S08] C：动态内存分配与释放
来源：http://dali.vqdsnc.cn/Article/details/gtwqjvrisg.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.wangdashe.top/Article/details/gtoiofeece.html

[S09] C：结构体定义与初始化
来源：http://dali.shanyushiyangkeji.top/Article/details/gtanaihtlm.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.mhx1999.top/Article/details/gtnydgirwj.html

[S10] C：指针与解引用
来源：http://dali.feifeiyinyue.top/Article/details/gtbrcfsmwy.html

int *p = &a;  *p = 5;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpuyynmjl.html

[S11] C：逐行读文件
来源：http://dali.yuanzhike.top/Article/details/gtkqhflgfp.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.shanyushiyangtech.top/Article/details/gtwijmnexp.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.shuidangran.top/Article/details/gtekammtdm.html

fclose(f);
来源：http://dali.feifeiyinyue.top/Article/details/gtikdfvsci.html

[S12] C：写文件
来源：http://dali.hnxiangtu.top/Article/details/gtkruuhsko.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.jqgufenzy.top/Article/details/gtfcdvtwbc.html

[S13] C：宏定义
来源：http://dali.xinyue.icu/Article/details/gtbubumbdw.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.haohaochexian.top/Article/details/gtdcjaxlnd.html

[S14] C：枚举
来源：http://dali.xuetiantiany.cn/Article/details/gtjylhgavx.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.hfpthk.cn/Article/details/gteooevgtd.html

[S15] C：类型转换
来源：http://dali.yj20258888.top/Article/details/gttvmdkzce.html

(double) a / b
来源：http://dali.bjfxy.top/Article/details/gtbndxctuq.html

[S16] C：位操作置位
来源：http://dali.tianlin.xyz/Article/details/gtnkehywhx.html

x |= (1 << 3);
来源：http://dali.zycfv.cn/Article/details/gtrgpzgzre.html

[S17] C：安全拼接字符串
来源：http://dali.mhx1999.top/Article/details/gtgffwiyyv.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhengqikj.top/Article/details/gtoibrvwtp.html

[S18] C：命令行参数
来源：http://dali.svipenyu.cn/Article/details/gtuasxmkwp.html

int main(int argc, char **argv)
来源：http://dali.tianlin.xyz/Article/details/gttrjybxsk.html

[S19] C：快速排序
来源：http://dali.cucudq.cn/Article/details/gtpfuwnyrf.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zdqjudy.top/Article/details/gtcuwguyqk.html

[S20] C：二分查找
来源：http://dali.yj20258.top/Article/details/gtboslmeks.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.jinqigfzy.top/Article/details/gthyzrhlob.html

[S21] C：字符类别判断
来源：http://dali.nwbrower.top/Article/details/gtwsfdjjto.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.yongpay.top/Article/details/gtzpyudybl.html

[S22] C：字符串转数字
来源：http://dali.yongpay.top/Article/details/gtfneksbda.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhongyouzk.top/Article/details/gtbcpibmoq.html

[S23] C：随机数
来源：http://dali.svipenyu.cn/Article/details/gtqzaxwbmi.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.aizwys.cn/Article/details/gtqzvedotn.html

[S24] C：获取本地时间
来源：http://dali.cqqwz.cn/Article/details/gtmvkvcjuv.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.gogol.net.cn/Article/details/gtvmnusejn.html

[S25] C：内存拷贝
来源：http://dali.sweek.top/Article/details/gthudbhkri.html

memcpy(dst, src, n);
来源：http://dali.tian-w.cn/Article/details/gtmschegrl.html

[S26] C：内存清零
来源：http://dali.jianghu66.top/Article/details/gtmurmizpv.html

memset(a, 0, sizeof a);
来源：http://dali.hnqzz.top/Article/details/gtwlcthdol.html

[S27] C：定义常量
来源：http://dali.yj202588.top/Article/details/gtssonjuzc.html

const double PI = 3.14159;
来源：http://dali.c1oappe.top/Article/details/gteheejixr.html

[S28] C：静态变量
来源：http://dali.xuanzx.com/Article/details/gthvoizgtr.html

static int counter = 0;
来源：http://dali.zdqjudy.top/Article/details/gtpnvufmnt.html

[S29] C：变参函数
来源：http://dali.yangfankeji.com/Article/details/gtwfvheslo.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gtyvctwwfe.html

[S30] C：头文件保护
来源：http://dali.snrcjt.cn/Article/details/gtetbjjwvx.html

#ifndef X_H
来源：http://dali.guannengcc.top/Article/details/gtvueptwsi.html

#define X_H
来源：http://dali.nanxinkj.top/Article/details/gtvyyhbhjb.html

#endif
来源：http://dali.cheryme.top/Article/details/gthyjeqlug.html

[S31] C++：Hello World
来源：http://dali.sufxvd.cn/Article/details/gthfjqlrbg.html

#include <iostream>
来源：http://dali.ybcxt.top/Article/details/gtdsghgtxv.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.sxryk.cn/Article/details/gtbxesawwe.html

[S32] C++：字符串
来源：http://dali.tanke756.top/Article/details/gtoujyjrsh.html

std::string s = "hi";  s += "!";
来源：http://dali.tianlin.xyz/Article/details/gtgzfkvkzw.html

[S33] C++：vector 增删
来源：http://dali.redwolf501.top/Article/details/gtzifdxjbs.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.nanxinkj.top/Article/details/gthwkjshfy.html

[S34] C++：遍历 vector
来源：http://dali.smart0.xyz/Article/details/gtulneequc.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.gaohongyu789.top/Article/details/gtkdwbhjhm.html

[S35] C++：map
来源：http://dali.jqgufenzy.top/Article/details/gtiohjkhlx.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.kuanghao11.cn/Article/details/gtvypckokw.html

[S36] C++：unordered_map
来源：http://dali.sweek.top/Article/details/gtzzywdzsb.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yj202588.top/Article/details/gtlvoxjker.html

[S37] C++：set
来源：http://dali.shanyushiyangkeji.top/Article/details/gtztpafvlg.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhongyouzk.top/Article/details/gtvzzmosoi.html

[S38] C++：排序
来源：http://dali.dashuyun.cn/Article/details/gtvfgjnoyg.html

std::sort(v.begin(), v.end());
来源：http://dali.jyoumei.cn/Article/details/gtckpbmhno.html

[S39] C++：自定义比较器排序
来源：http://dali.shzxlz.cn/Article/details/gtlexdxzmn.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.sweek.top/Article/details/gthjzhuhfd.html

[S40] C++：查找元素
来源：http://dali.cashguo.top/Article/details/gtzbupikhj.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.xziqi.cn/Article/details/gthyodxeda.html

[S41] C++：类与构造函数
来源：http://dali.yj20258888.top/Article/details/gtircsonbl.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.chenzaomai.com/Article/details/gtkujcfjra.html

[S42] C++：继承与虚函数
来源：http://dali.xziqi.cn/Article/details/gtvmvkgbzd.html

class B : public Base { public: void f() override {} };
来源：http://dali.hysaishi.cn/Article/details/gtsymgyemy.html

[S43] C++：智能指针
来源：http://dali.guannengcc.top/Article/details/gtyekqaxnx.html

auto p = std::make_unique<int>(5);
来源：http://dali.guowangkeji.top/Article/details/gtttedwhsg.html

[S44] C++：引用传参
来源：http://dali.vqdsnc.cn/Article/details/gtnyvctydh.html

void inc(int &x) { ++x; }
来源：http://dali.nanxinkj.top/Article/details/gttpfohxuz.html

[S45] C++：lambda
来源：http://dali.gogol.net.cn/Article/details/gtwozyztgu.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.cheryme.top/Article/details/gtxvqrween.html

[S46] C++：函数模板
来源：http://dali.yj202588.top/Article/details/gtxlqqezxx.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.yonumen.top/Article/details/gtoosjcill.html

[S47] C++：结构化绑定遍历
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgzmnsusk.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.daria6918.cn/Article/details/gtfuwrdbac.html

[S48] C++：逐行读文件
来源：http://dali.gzhubu.top/Article/details/gtwzoftzdm.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.bjfxy.top/Article/details/gttkldowip.html

while (std::getline(in, line)) { }
来源：http://dali.zhoulong.xyz/Article/details/gtyauyrhta.html

[S49] C++：写文件
来源：http://dali.cucudq.cn/Article/details/gttvhknjhd.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.jinqigfzy.top/Article/details/gtmlrqragc.html

[S50] C++：格式化数字
来源：http://dali.ppjwa.cn/Article/details/gtkjaidyuq.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.ydzc1.top/Article/details/gtbqwtlhme.html

[S51] C++：显式类型转换
来源：http://dali.gaohongyu789.top/Article/details/gtadawzpna.html

static_cast<double>(a) / b
来源：http://dali.yangfankeji.com/Article/details/gtgicjbrof.html

[S52] C++：const 与 noexcept
来源：http://dali.sxryk.cn/Article/details/gtexmqpkmu.html

int size() const noexcept { return n_; }
来源：http://dali.gogol.net.cn/Article/details/gtafslnheh.html

[S53] C++：移动语义
来源：http://dali.yj20258.top/Article/details/gtqqszatdw.html

std::vector<int> w = std::move(v);
来源：http://dali.quarkkingdee.top/Article/details/gtwptauhho.html

[S54] C++：异常处理
来源：http://dali.ywan-chungtsiang.top/Article/details/gtudovgcqz.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.gzhubu.top/Article/details/gtetmmhfkq.html

[S55] C++：结构化绑定
来源：http://dali.guannengcc.top/Article/details/gtlfyidbww.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.mhx1999.top/Article/details/gtdbmsjwtf.html

[S56] C++：optional
来源：http://dali.zhiwuduotai.top/Article/details/gthgtapakl.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.svipenyu.cn/Article/details/gturqdsmmn.html

[S57] C++：编译期常量
来源：http://dali.xuetiantiany.cn/Article/details/gtmgcouvgx.html

constexpr int N = 10;
来源：http://dali.yvedp.cn/Article/details/gtsztfwnmo.html

[S58] C++：命名空间
来源：http://dali.ybcxt.top/Article/details/gtndtogypg.html

namespace ns { int f() { return 1; } }
来源：http://dali.wangshuangyany.cn/Article/details/gtmqvzkkhp.html

[S59] C++：静态断言
来源：http://dali.cdnleiting.top/Article/details/gtffdwqutb.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zdqjudy.top/Article/details/gtlggypgrf.html

[S60] C++：遍历并删除元素
来源：http://dali.zhoulong.xyz/Article/details/gtpnyolans.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.shzxlz.cn/Article/details/gtgxfcjpas.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtjawsxukl.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.pycfn.com/Article/details/gthtyusfst.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtwclujvla.html

[T01] Kotlin：Hello World
来源：http://dali.zhengqikj.top/Article/details/gtgimrafug.html

println("Hello")
来源：http://dali.yangfankeji.com/Article/details/gtbtavxbga.html

[T02] Kotlin：变量
来源：http://dali.wangdashe.top/Article/details/gtbvqjenfr.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhengqikj.top/Article/details/gtmfsihrcy.html

[T03] Kotlin：字符串模板
来源：http://dali.ybcxt.top/Article/details/gtxrbgrowu.html

"值: $b"
来源：http://dali.hnqzz.top/Article/details/gtmnjtyfjh.html

[T04] Kotlin：空安全
来源：http://dali.zdqjudy.top/Article/details/gtcaijihmy.html

val n: String? = null;  n?.length
来源：http://dali.sxryk.cn/Article/details/gtertmnhhu.html

[T05] Kotlin：when 表达式
来源：http://dali.zhengqikj.top/Article/details/gtmtrebejr.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.daria6918.cn/Article/details/gtqlegbxbx.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gtlmadgapp.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.jlsjyb.cn/Article/details/gtvqkykckc.html

[T07] Kotlin：集合过滤
来源：http://dali.hongshengwenyu.top/Article/details/gtzzkzfrkg.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.cucudq.cn/Article/details/gtiinircnr.html

[T08] Kotlin：数据类
来源：http://dali.ydzc1.top/Article/details/gtrdrvxvwa.html

data class User(val name: String, val age: Int)
来源：http://dali.havefunace.top/Article/details/gtctwzetgs.html

[T09] Kotlin：扩展函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbaocxgvb.html

fun String.exclaim() = this + "!"
来源：http://dali.guowangkeji.top/Article/details/gtjtbyqtak.html

[T10] Kotlin：默认参数
来源：http://dali.wangshuangyany.cn/Article/details/gtmpxzovpi.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhixingplan.top/Article/details/gtbkkhuaey.html

[T11] Kotlin：协程
来源：http://dali.pycfn.com/Article/details/gtoiodmgcd.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.cqqwz.cn/Article/details/gtpfflhfhj.html

[T12] Kotlin：解构声明
来源：http://dali.guannengcc.top/Article/details/gtdhvdfcbs.html

val (a, b) = Pair(1, 2)
来源：http://dali.yonumen.top/Article/details/gtnuwicspw.html

[T13] Kotlin：只读 Map
来源：http://dali.hywenlv.cn/Article/details/gtzzsxklne.html

val m = mapOf("a" to 1)
来源：http://dali.jlsjyb.cn/Article/details/gtokeadlxh.html

[T14] Kotlin：循环
来源：http://dali.yj20258888.top/Article/details/gthugkmqvw.html

for (i in 1..10) println(i)
来源：http://dali.yj20258.top/Article/details/gtjlhdfjdk.html

[T15] Kotlin：接口
来源：http://dali.redwolf501.top/Article/details/gtgiagghip.html

interface Shape { fun area(): Double }
来源：http://dali.xuetiantiany.cn/Article/details/gtbdgfzajj.html

[T16] Swift：Hello World
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtajzcsvhf.html

print("Hello")
来源：http://dali.shzxlz.cn/Article/details/gtltywwqob.html

[T17] Swift：变量与常量
来源：http://dali.bjfxy.top/Article/details/gtxewlffro.html

var a = 1;  let b = 2
来源：http://dali.pycfn.com/Article/details/gtbqtehyik.html

[T18] Swift：字符串插值
来源：http://dali.cashguo.top/Article/details/gtaatvqmpv.html

"值: \(b)"
来源：http://dali.tianlin.xyz/Article/details/gtfbatlddu.html

[T19] Swift：可选绑定
来源：http://dali.wangshuangyany.cn/Article/details/gturwlfxcu.html

if let n = opt { print(n) }
来源：http://dali.tanke756.top/Article/details/gtzsvyhjlh.html

[T20] Swift：数组操作
来源：http://dali.zhiwuduotai.top/Article/details/gtcmrihpqt.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhengqikj.top/Article/details/gtxijioysh.html

[T21] Swift：遍历
来源：http://dali.xziqi.cn/Article/details/gtulwkzdzz.html

for x in a { print(x) }
来源：http://dali.wangshuangyany.cn/Article/details/gtkhstlbjf.html

[T22] Swift：字典
来源：http://dali.nanxinkj.top/Article/details/gtdtmndzzc.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.sysykeji.top/Article/details/gtxkbgwvut.html

[T23] Swift：函数
来源：http://dali.yj20258888.top/Article/details/gtdepfvmnv.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.yuanzhike.top/Article/details/gtbwhytpyi.html

[T24] Swift：闭包
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfiagvcct.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.tianlin.xyz/Article/details/gtcipiubhi.html

[T25] Swift：结构体
来源：http://dali.cheryme.top/Article/details/gtweexmiwd.html

struct P { var x: Int }
来源：http://dali.jiagoushi.top/Article/details/gtghvekrbx.html

[T26] Swift：类与重写
来源：http://dali.yuanzhike.top/Article/details/gtwuxfpvjo.html

class A: Base { override func f() {} }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtueuwzemc.html

[T27] Swift：错误处理
来源：http://dali.yonumen.top/Article/details/gtzrhwwnev.html

do { try f() } catch { print(error) }
来源：http://dali.yvedp.cn/Article/details/gttcgmskzd.html

[T28] Swift：枚举
来源：http://dali.c1oappe.top/Article/details/gtzqrztwjr.html

enum Color { case red, green }
来源：http://dali.nanxuanxn.top/Article/details/gtfcimuuma.html

[T29] Swift：guard 提前返回
来源：http://dali.sweek.top/Article/details/gtyxkcmdvt.html

guard let x = opt else { return }
来源：http://dali.cheryme.top/Article/details/gtfbglumdq.html

[T30] Swift：协议
来源：http://dali.gzhubu.top/Article/details/gtzlkxbonx.html

protocol Shape { func area() -> Double }
来源：http://dali.pengpengdd.cyou/Article/details/gtqyclttwe.html

[T31] Lua：Hello World
来源：http://dali.yuanzhike.top/Article/details/gtvxnbmskf.html

print("Hello")
来源：http://dali.hnxiangtu.top/Article/details/gtmqlapvhe.html

[T32] Lua：局部变量
来源：http://dali.nwbrower.top/Article/details/gtksjfmayg.html

local a = 1
来源：http://dali.daria6918.cn/Article/details/gtomwywpnw.html

[T33] Lua：表（数组）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvgorywrp.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.cdnleiting.top/Article/details/gtcncsqsib.html

[T34] Lua：遍历表
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfbwjnusd.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtecegnpoo.html

[T35] Lua：字典表
来源：http://dali.gogol.net.cn/Article/details/gtzuriavxj.html

local d = { a = 1 };  d.b = 2
来源：http://dali.ehwqpu.com/Article/details/gtllkchnbo.html

[T36] Lua：函数
来源：http://dali.ppjwa.cn/Article/details/gtllnethkw.html

function add(a, b) return a + b end
来源：http://dali.hywenlv.cn/Article/details/gtosvxykio.html

[T37] Lua：字符串拼接
来源：http://dali.pengpengdd.cyou/Article/details/gtwpxnhmku.html

"a" .. "b"
来源：http://dali.pengpengdd.cyou/Article/details/gtohmjxoxt.html

[T38] Lua：条件
来源：http://dali.pengpengdd.cyou/Article/details/gtvdpkbdoa.html

if x > 0 then print("正") end
来源：http://dali.xinyue.icu/Article/details/gtcbhobjid.html

[T39] Lua：模式匹配
来源：http://dali.mhx1999.top/Article/details/gtblslayqx.html

string.find(s, "%d+")
来源：http://dali.jinqigfzy.top/Article/details/gtbwtgwugp.html

[T40] Lua：元表
来源：http://dali.andypj.xyz/Article/details/gtbcbmvslo.html

setmetatable({}, { __index = base })
来源：http://dali.hfpthk.cn/Article/details/gtzlblrxeq.html

[T41] Perl：Hello World
来源：http://dali.pengpengdd.cyou/Article/details/gttuccmkuo.html

print "Hello\n";
来源：http://dali.0kj1m.cn/Article/details/gtftdvxhdh.html

[T42] Perl：变量类型
来源：http://dali.ehwqpu.com/Article/details/gtoyoteahx.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.yuxming.cn/Article/details/gtggvfrqap.html

[T43] Perl：字符串插值
来源：http://dali.guowangkeji.top/Article/details/gtodjclctn.html

"值: $a"
来源：http://dali.zhiwuduotai.top/Article/details/gtcjbpmakg.html

[T44] Perl：条件
来源：http://dali.yanxiufei.cn/Article/details/gtjghxrlon.html

if ($a > 0) { print "正"; }
来源：http://dali.gogol.net.cn/Article/details/gtttjosbxs.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gttguppnjw.html

for my $x (@arr) { print $x; }
来源：http://dali.zdqjudy.top/Article/details/gtadgsoacq.html

[T46] Perl：哈希操作
来源：http://dali.snrcjt.cn/Article/details/gtbrpeoveu.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.hywenlv.cn/Article/details/gttxekhjkz.html

[T47] Perl：正则捕获
来源：http://dali.gogol.net.cn/Article/details/gtngdxfics.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.tian-w.cn/Article/details/gtoecypbrv.html

[T48] Perl：正则替换
来源：http://dali.hnxiangtu.top/Article/details/gtysmbmwxa.html

$s =~ s/old/new/g;
来源：http://dali.zdqjudy.top/Article/details/gtarhocuye.html

[T49] Perl：函数
来源：http://dali.jinqigufen.top/Article/details/gtuathcagi.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtahadiawf.html

[T50] Perl：逐行读文件
来源：http://dali.tanke756.top/Article/details/gtjzelcoba.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.gotoacloud.top/Article/details/gtggoplqjb.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.andypj.xyz/Article/details/gtirmsgaiv.html

[T51] Scala：Hello World
来源：http://dali.guannengcc.top/Article/details/gtteejgrny.html

println("Hello")
来源：http://dali.yj20258888.top/Article/details/gtsufvzhtq.html

[T52] Scala：变量
来源：http://dali.shangyingyoupin.top/Article/details/gtzkfybovu.html


<!-- 参考信息 -->