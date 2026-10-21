代发 wailian999

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.meibo888.top/Article/details/gtdvlwnfpx.html

[R50] awk 求和
来源：http://dali.fengsongda.top/Article/details/gtwvxubxko.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.gzhubu.top/Article/details/gtirdsrenw.html

[R51] 排序去重取前几
来源：http://dali.xinyue.icu/Article/details/gtuizjagrt.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.feifeiyinyue.top/Article/details/gtdkukbtnt.html

[R52] 统计行数
来源：http://dali.chenzaomai.com/Article/details/gtqkvtdsnr.html

wc -l a.txt
来源：http://dali.fzhhl.top/Article/details/gtrhegmwkv.html

[R53] 查看文件头与实时尾
来源：http://dali.ppjwa.cn/Article/details/gtxetjqion.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.yongpay.top/Article/details/gtrkntajrz.html

[R54] 比较两个文件
来源：http://dali.zhixingplan.top/Article/details/gtijxhlcwl.html

diff a.txt b.txt
来源：http://dali.yongpay.top/Article/details/gtohcuezme.html

[R55] 压缩与解压
来源：http://dali.zhaomingkeji.xyz/Article/details/gtknjefvda.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.aizwys.cn/Article/details/gtccnvlcyq.html

[R56] 远程拷贝
来源：http://dali.wangshuangyany.cn/Article/details/gtwgrqdkbj.html

scp file user@host:/path/
来源：http://dali.haohaochexian.top/Article/details/gtppefahql.html

[R57] 远程执行命令
来源：http://dali.wangdashe.top/Article/details/gtaxujrrgb.html

ssh user@host 'uptime'
来源：http://dali.gogol.net.cn/Article/details/gtrfsgymjb.html

[R58] 下载文件
来源：http://dali.dashuyun.cn/Article/details/gtriqgqkbj.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.guannengcc.top/Article/details/gtknmicbwq.html

[R59] 发 POST JSON
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttvscncxp.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.hongshengwenyu.top/Article/details/gtyzveslzx.html

[R60] 只看 HTTP 状态码
来源：http://dali.hnqzz.top/Article/details/gtflphygfj.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.aizwys.cn/Article/details/gtahworhor.html

[R61] 磁盘占用
来源：http://dali.cdnleiting.top/Article/details/gtvzioqsmh.html

df -h;  du -sh *
来源：http://dali.sufxvd.cn/Article/details/gtnnjasjtj.html

[R62] 找最占空间的文件
来源：http://dali.kuanghao11.cn/Article/details/gtaefqqrhj.html

du -ah . | sort -rh | head -10
来源：http://dali.gogol.net.cn/Article/details/gttqeywczn.html

[R63] 内存与进程
来源：http://dali.cheryme.top/Article/details/gtfpfgfnda.html

free -h;  ps aux | grep nginx
来源：http://dali.zhongyouzk.top/Article/details/gtsygnxktr.html

[R64] 结束进程
来源：http://dali.wangshuangyany.cn/Article/details/gtjooqdebu.html

kill -9 $(pgrep -f app.py)
来源：http://dali.hnxiangtu.top/Article/details/gtucqiuxnz.html

[R65] 查看端口占用
来源：http://dali.shuidangran.top/Article/details/gtesjlqjzg.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.wangshuangyany.cn/Article/details/gtamnzrlve.html

[R66] 定时任务
来源：http://dali.sufxvd.cn/Article/details/gtlimdentz.html

crontab -e;  crontab -l
来源：http://dali.hfpthk.cn/Article/details/gtpcvsqnyz.html

[R67] 生成随机十六进制串
来源：http://dali.jinqigfzy.top/Article/details/gtgvhbfznl.html

openssl rand -hex 16
来源：http://dali.redwolf501.top/Article/details/gtutscqkgt.html

[R68] 计算文件校验值
来源：http://dali.guannengcc.top/Article/details/gttcttnqtt.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.yangfankeji.com/Article/details/gtgpjgnehz.html

[R69] 生成随机密码
来源：http://dali.dashuyun.cn/Article/details/gtsxlahkld.html

head -c 16 /dev/urandom | base64
来源：http://dali.jianghu66.top/Article/details/gtdsaikjmx.html

[R70] 时间戳与互转
来源：http://dali.mhx1999.top/Article/details/gtgszcwgfk.html

date +%s;  date -d @1700000000
来源：http://dali.ydzc1.top/Article/details/gtfsiumpnn.html

[R71] 日期格式化
来源：http://dali.wangdashe.top/Article/details/gtxfvwyuum.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.xuanzx.com/Article/details/gtsayvmyso.html

[R72] 等待端口就绪
来源：http://dali.xylfe.cn/Article/details/gtfqmasesi.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhengqikj.top/Article/details/gtgbrumqgz.html

[R73] 分割大日志
来源：http://dali.cucudq.cn/Article/details/gtvsbzidbs.html

split -l 1000 big.log part_
来源：http://dali.nwbrower.top/Article/details/gtugnddotk.html

[R74] 批量重命名
来源：http://dali.sxryk.cn/Article/details/gtfmwtvgxd.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhiwuduotai.top/Article/details/gtytheniil.html

[R75] 导出环境变量
来源：http://dali.daria6918.cn/Article/details/gtraujfnen.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.9152youxi.cn/Article/details/gtxizxztqk.html

[R76] 使用临时文件
来源：http://dali.jlsjyb.cn/Article/details/gtkqfnprxl.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.tanke756.top/Article/details/gtaplmjcyv.html

[R77] 读取用户输入
来源：http://dali.cqqwz.cn/Article/details/gtygbimqan.html

read -rp "请输入: " ans
来源：http://dali.meibo888.top/Article/details/gtxexbcncu.html

[R78] 交互式菜单
来源：http://dali.jiagoushi.top/Article/details/gtwxnoegab.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.gotoacloud.top/Article/details/gtvkncjueu.html

[R79] 解析命令行选项
来源：http://dali.gotoacloud.top/Article/details/gtplmuepnq.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.ydzc1.top/Article/details/gtejgqgqrp.html

[R80] 查看脚本执行耗时
来源：http://dali.xuetiantiany.cn/Article/details/gtmkifxnfo.html

time ./run.sh
来源：http://dali.ivvv.top/Article/details/gtqjulcvph.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtkduhqrso.html

S. C / C++ 专题
来源：http://dali.cucudq.cn/Article/details/gtzksgocoe.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtdykfzdwc.html

[S01] C：Hello World
来源：http://dali.tianlin.xyz/Article/details/gtyjwtwdgp.html

#include <stdio.h>
来源：http://dali.zhengqikj.top/Article/details/gtlgxjgcip.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.316326.xyz/Article/details/gtaldtzazg.html

[S02] C：变量与格式化输出
来源：http://dali.jianghu66.top/Article/details/gtqmtkiulm.html

int a = 10; printf("%d\n", a);
来源：http://dali.hywenlv.cn/Article/details/gtrsofpuik.html

[S03] C：读入整数
来源：http://dali.jqgfzy.top/Article/details/gtefezlhfy.html

int x; scanf("%d", &x);
来源：http://dali.zhoulong.xyz/Article/details/gtvtfpjfmv.html

[S04] C：字符串复制
来源：http://dali.mhx1999.top/Article/details/gtdzqukriv.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.hongshengwenyu.top/Article/details/gtdvyiyopi.html

[S05] C：字符串长度
来源：http://dali.ybcxt.top/Article/details/gttjljnclg.html

strlen(s)
来源：http://dali.nwbrower.top/Article/details/gtdvbetvrr.html

[S06] C：字符串比较
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjlvxopkl.html

strcmp(a, b) == 0
来源：http://dali.aibaodan.cn/Article/details/gtpvfnofqu.html

[S07] C：数组遍历求和
来源：http://dali.yj20258.top/Article/details/gtcapqogkw.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.haohaochexian.top/Article/details/gtsxnqtozo.html

[S08] C：动态内存分配与释放
来源：http://dali.daria6918.cn/Article/details/gtqiaoaohh.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhongyouzk.top/Article/details/gtzglmezcc.html

[S09] C：结构体定义与初始化
来源：http://dali.tanke756.top/Article/details/gtjbekzvbn.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.nanxuanxn.top/Article/details/gtyubfduoa.html

[S10] C：指针与解引用
来源：http://dali.jianghu66.top/Article/details/gtnaqrdtqx.html

int *p = &a;  *p = 5;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtycbofehv.html

[S11] C：逐行读文件
来源：http://dali.zhengqikj.top/Article/details/gtcydimbjo.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.hammf.cn/Article/details/gtlvwhqynu.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.jinghuilouyu.cn/Article/details/gtnuhnpvva.html

fclose(f);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkjwtzkzl.html

[S12] C：写文件
来源：http://dali.nwbrower.top/Article/details/gtvfrjljdq.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.smart0.xyz/Article/details/gtijmqtfsp.html

[S13] C：宏定义
来源：http://dali.iojbl.cn/Article/details/gtkierhpxk.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.cucudq.cn/Article/details/gtumpfhpao.html

[S14] C：枚举
来源：http://dali.ehwqpu.com/Article/details/gtyoqmmsdd.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.jinqigufen.top/Article/details/gtifzdyuwx.html

[S15] C：类型转换
来源：http://dali.shanyushiyangtech.top/Article/details/gttankikve.html

(double) a / b
来源：http://dali.hfpthk.cn/Article/details/gtyecaoycx.html

[S16] C：位操作置位
来源：http://dali.shanyushiyangtech.top/Article/details/gtobxlapos.html

x |= (1 << 3);
来源：http://dali.hnqzz.top/Article/details/gtanhdzlrt.html

[S17] C：安全拼接字符串
来源：http://dali.guowangkeji.top/Article/details/gtnivpagxo.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhixingplan.top/Article/details/gtrrgjcrmn.html

[S18] C：命令行参数
来源：http://dali.hammf.cn/Article/details/gtpdpvlsjt.html

int main(int argc, char **argv)
来源：http://dali.cucudq.cn/Article/details/gtqcwnyfqm.html

[S19] C：快速排序
来源：http://dali.quarkkingdee.top/Article/details/gtofhjhtcz.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.aizwys.cn/Article/details/gtlyltwcvt.html

[S20] C：二分查找
来源：http://dali.cdnleiting.top/Article/details/gtnibtyoml.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.yj20258.top/Article/details/gtuadkfemj.html

[S21] C：字符类别判断
来源：http://dali.gzhubu.top/Article/details/gtnorryskp.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.haohaochexian.top/Article/details/gtpwyzewbh.html

[S22] C：字符串转数字
来源：http://dali.hongshengwenyu.top/Article/details/gtmlyknxyw.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.sufxvd.cn/Article/details/gtyxqygynu.html

[S23] C：随机数
来源：http://dali.andypj.xyz/Article/details/gthztavrvs.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.gaohongyu789.top/Article/details/gtskniucza.html

[S24] C：获取本地时间
来源：http://dali.chenlongwang.top/Article/details/gtrcoisokr.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.daxiang520.top/Article/details/gtctcmdoer.html

[S25] C：内存拷贝
来源：http://dali.ppjwa.cn/Article/details/gtkbzhwpht.html

memcpy(dst, src, n);
来源：http://dali.zhoulong.xyz/Article/details/gtvqbmrdpc.html

[S26] C：内存清零
来源：http://dali.0kj1m.cn/Article/details/gteumsvexm.html

memset(a, 0, sizeof a);
来源：http://dali.chenzaomai.com/Article/details/gtotffyjaj.html

[S27] C：定义常量
来源：http://dali.aibaodan.cn/Article/details/gtemsrauiu.html

const double PI = 3.14159;
来源：http://dali.zhixingplan.top/Article/details/gtxddvbzux.html

[S28] C：静态变量
来源：http://dali.nanxinkj.top/Article/details/gtankmcrnv.html

static int counter = 0;
来源：http://dali.0kj1m.cn/Article/details/gtwdiuftpj.html

[S29] C：变参函数
来源：http://dali.iojbl.cn/Article/details/gtrgbexbak.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.nanxuanxn.top/Article/details/gtovvlssmy.html

[S30] C：头文件保护
来源：http://dali.cdnleiting.top/Article/details/gtozgdtcpb.html

#ifndef X_H
来源：http://dali.redwolf501.top/Article/details/gtrhvnzjvr.html

#define X_H
来源：http://dali.shangyingyoupin.top/Article/details/gtlffxueml.html

#endif
来源：http://dali.yj20258888.top/Article/details/gttqdfbtlt.html

[S31] C++：Hello World
来源：http://dali.jinqigfzy.top/Article/details/gtkgljkhko.html

#include <iostream>
来源：http://dali.zhixingplan.top/Article/details/gtjchdxkvh.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.wangdashe.top/Article/details/gtpmayapgd.html

[S32] C++：字符串
来源：http://dali.haohaochexian.top/Article/details/gtjgkbfzuo.html

std::string s = "hi";  s += "!";
来源：http://dali.pengpengdd.cyou/Article/details/gtdnlzshwc.html

[S33] C++：vector 增删
来源：http://dali.jqgfzy.top/Article/details/gtqmjhzxrm.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.yuxming.cn/Article/details/gtdzsqrqvv.html

[S34] C++：遍历 vector
来源：http://dali.guowangkeji.top/Article/details/gtmgrmjxkh.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.haohaochexian.top/Article/details/gtwpwupbuz.html

[S35] C++：map
来源：http://dali.c1oappe.top/Article/details/gtpmyabsuh.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.sufxvd.cn/Article/details/gtjyxyodnr.html

[S36] C++：unordered_map
来源：http://dali.dianchejie.cn/Article/details/gtcqlqrbsl.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfepctryw.html

[S37] C++：set
来源：http://dali.sufxvd.cn/Article/details/gtcstidoiw.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.iojbl.cn/Article/details/gtaymjldan.html

[S38] C++：排序
来源：http://dali.hammf.cn/Article/details/gtagiwbsgq.html

std::sort(v.begin(), v.end());
来源：http://dali.jianghu66.top/Article/details/gtcthsxtis.html

[S39] C++：自定义比较器排序
来源：http://dali.xinyue.icu/Article/details/gtjedcvwyy.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.yuanzhike.top/Article/details/gtrpekaqcn.html

[S40] C++：查找元素
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlwimbhkz.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.ivvv.top/Article/details/gtuvoakomx.html

[S41] C++：类与构造函数
来源：http://dali.pengpengdd.cyou/Article/details/gtsduvgoge.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhiwuduotai.top/Article/details/gtpjlikwmc.html

[S42] C++：继承与虚函数
来源：http://dali.ppjwa.cn/Article/details/gtgiktlpew.html

class B : public Base { public: void f() override {} };
来源：http://dali.hnxiangtu.top/Article/details/gtbbgypfhx.html

[S43] C++：智能指针
来源：http://dali.nanxinkj.top/Article/details/gtoxtmialz.html

auto p = std::make_unique<int>(5);
来源：http://dali.nwbrower.top/Article/details/gtfloevyoj.html

[S44] C++：引用传参
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnyzgfcbl.html

void inc(int &x) { ++x; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjfcklvxa.html

[S45] C++：lambda
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsjijuqpq.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.jqgufenzy.top/Article/details/gthxmfqdcm.html

[S46] C++：函数模板
来源：http://dali.ydzc1.top/Article/details/gtgplbzjcv.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.sweek.top/Article/details/gtuehzjsws.html

[S47] C++：结构化绑定遍历
来源：http://dali.cucudq.cn/Article/details/gtynfeiysw.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gttkqrkyet.html

[S48] C++：逐行读文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlplvbkes.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.yueranfly.top/Article/details/gtxigjvxhd.html

while (std::getline(in, line)) { }
来源：http://dali.yangfankeji.com/Article/details/gtixzatlvy.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gtgkbdrijk.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.yvedp.cn/Article/details/gttdvdenyt.html

[S50] C++：格式化数字
来源：http://dali.mhx1999.top/Article/details/gtuasctpzy.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.yj202588.top/Article/details/gtqrnrwqsu.html

[S51] C++：显式类型转换
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrxlgfsnx.html

static_cast<double>(a) / b
来源：http://dali.cucudq.cn/Article/details/gtyiddkqtc.html

[S52] C++：const 与 noexcept
来源：http://dali.pycfn.com/Article/details/gteytvzojb.html

int size() const noexcept { return n_; }
来源：http://dali.chenlongwang.top/Article/details/gtiksuionb.html

[S53] C++：移动语义
来源：http://dali.cucudq.cn/Article/details/gtpdvhsvmf.html

std::vector<int> w = std::move(v);
来源：http://dali.xuanzx.com/Article/details/gtkvemqlzq.html

[S54] C++：异常处理
来源：http://dali.hysaishi.cn/Article/details/gtxbpkqosv.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.ppjwa.cn/Article/details/gtmharpwti.html

[S55] C++：结构化绑定
来源：http://dali.guowangkeji.top/Article/details/gtblevvcne.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.guannengcc.top/Article/details/gtkpydipzq.html

[S56] C++：optional
来源：http://dali.sweek.top/Article/details/gtwkovregs.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.meibo888.top/Article/details/gtflvuwrcf.html

[S57] C++：编译期常量
来源：http://dali.nanxinkj.top/Article/details/gtwpsnygwb.html

constexpr int N = 10;
来源：http://dali.shuidangran.top/Article/details/gtpsrpmknl.html

[S58] C++：命名空间
来源：http://dali.hnqzz.top/Article/details/gtttsfrtpa.html

namespace ns { int f() { return 1; } }
来源：http://dali.yangfankeji.com/Article/details/gtwlokmwss.html

[S59] C++：静态断言
来源：http://dali.daria6918.cn/Article/details/gtbvzysbdx.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.ppjwa.cn/Article/details/gthkqjnpeu.html

[S60] C++：遍历并删除元素
来源：http://dali.yuanzhike.top/Article/details/gtnjwvputw.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.yj20258888.top/Article/details/gtukyqqgws.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtxcfvjnaa.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.snrcjt.cn/Article/details/gtgvxetezh.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtmgsutoic.html

[T01] Kotlin：Hello World
来源：http://dali.gogol.net.cn/Article/details/gtpltgaxuq.html

println("Hello")
来源：http://dali.kuanghao11.cn/Article/details/gtpbxtltvg.html

[T02] Kotlin：变量
来源：http://dali.jinghuilouyu.cn/Article/details/gtusmcvbuk.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.pycfn.com/Article/details/gtrfeyiuvs.html

[T03] Kotlin：字符串模板
来源：http://dali.gogol.net.cn/Article/details/gtrlpelbxo.html

"值: $b"
来源：http://dali.zdqjudy.top/Article/details/gtcybeqahf.html

[T04] Kotlin：空安全
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdijizoot.html

val n: String? = null;  n?.length
来源：http://dali.hammf.cn/Article/details/gthybowgcv.html

[T05] Kotlin：when 表达式
来源：http://dali.sysykeji.top/Article/details/gtsceeljxz.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.svipenyu.cn/Article/details/gtgtclswhz.html

[T06] Kotlin：集合映射
来源：http://dali.chenlongwang.top/Article/details/gtxtcqokeg.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.chenlongwang.top/Article/details/gtnihoznks.html

[T07] Kotlin：集合过滤
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbieicdhk.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.aibaodan.cn/Article/details/gtbnjnfvkz.html

[T08] Kotlin：数据类
来源：http://dali.aizwys.cn/Article/details/gtfritqyni.html

data class User(val name: String, val age: Int)
来源：http://dali.hywenlv.cn/Article/details/gtruxbllpd.html

[T09] Kotlin：扩展函数
来源：http://dali.yonumen.top/Article/details/gtezqinqhr.html

fun String.exclaim() = this + "!"
来源：http://dali.wangshuangyany.cn/Article/details/gtcxmyoeku.html

[T10] Kotlin：默认参数
来源：http://dali.snrcjt.cn/Article/details/gtpagvfncn.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.gotoacloud.top/Article/details/gtlphulijl.html

[T11] Kotlin：协程
来源：http://dali.feifeiyinyue.top/Article/details/gtxovrfpmi.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.meibo888.top/Article/details/gtoddkqjsf.html

[T12] Kotlin：解构声明
来源：http://dali.jlsjyb.cn/Article/details/gtfeemlsdc.html

val (a, b) = Pair(1, 2)
来源：http://dali.snrcjt.cn/Article/details/gtzlucgkxu.html

[T13] Kotlin：只读 Map
来源：http://dali.dashuyun.cn/Article/details/gtiywrirnq.html

val m = mapOf("a" to 1)
来源：http://dali.cucudq.cn/Article/details/gtrvufzggy.html

[T14] Kotlin：循环
来源：http://dali.xinyue.icu/Article/details/gtgrpymgtn.html

for (i in 1..10) println(i)
来源：http://dali.cucudq.cn/Article/details/gtmwiqdnex.html

[T15] Kotlin：接口
来源：http://dali.dianchejie.cn/Article/details/gtbaoabfps.html

interface Shape { fun area(): Double }
来源：http://dali.meibo888.top/Article/details/gtuyrohkcz.html

[T16] Swift：Hello World
来源：http://dali.dianchejie.cn/Article/details/gtbujenetm.html

print("Hello")
来源：http://dali.aizwys.cn/Article/details/gtvzqlmlpd.html

[T17] Swift：变量与常量
来源：http://dali.redwolf501.top/Article/details/gtsxpvxtht.html

var a = 1;  let b = 2
来源：http://dali.chenzaomai.com/Article/details/gtuubtusod.html

[T18] Swift：字符串插值
来源：http://dali.andypj.xyz/Article/details/gtdjsudsro.html

"值: \(b)"
来源：http://dali.hywenlv.cn/Article/details/gtzsszicng.html

[T19] Swift：可选绑定
来源：http://dali.yuanzhike.top/Article/details/gtknizwjfc.html

if let n = opt { print(n) }
来源：http://dali.tanke756.top/Article/details/gtinyqatjo.html

[T20] Swift：数组操作
来源：http://dali.yuanzhike.top/Article/details/gtjbjhaseb.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.jiagoushi.top/Article/details/gtscietvqz.html

[T21] Swift：遍历
来源：http://dali.jlsjyb.cn/Article/details/gtbctmjxwf.html

for x in a { print(x) }
来源：http://dali.cashguo.top/Article/details/gtlbqyxisi.html

[T22] Swift：字典
来源：http://dali.sxryk.cn/Article/details/gtljipckgr.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.shuidangran.top/Article/details/gtizmeikcw.html

[T23] Swift：函数
来源：http://dali.iojbl.cn/Article/details/gtgrfrcoxb.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.xinyue.icu/Article/details/gtbxkjrfhl.html

[T24] Swift：闭包
来源：http://dali.sweek.top/Article/details/gtabeehcry.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.pengpengdd.cyou/Article/details/gtbxxfpaam.html

[T25] Swift：结构体
来源：http://dali.ehwqpu.com/Article/details/gtjjhgktae.html

struct P { var x: Int }
来源：http://dali.0kj1m.cn/Article/details/gtbskzyvwd.html

[T26] Swift：类与重写
来源：http://dali.ppjwa.cn/Article/details/gtihbjbuvp.html

class A: Base { override func f() {} }
来源：http://dali.zdqjudy.top/Article/details/gtxmonnqht.html

[T27] Swift：错误处理
来源：http://dali.jinqigufen.top/Article/details/gtyzdmfysz.html

do { try f() } catch { print(error) }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqjutbwln.html

[T28] Swift：枚举
来源：http://dali.yangfankeji.com/Article/details/gtxsmwutyh.html

enum Color { case red, green }
来源：http://dali.gaohongyu789.top/Article/details/gtkifhtsrk.html

[T29] Swift：guard 提前返回
来源：http://dali.hongshengwenyu.top/Article/details/gtyjxdaqem.html

guard let x = opt else { return }
来源：http://dali.dianchejie.cn/Article/details/gtnmuardfw.html

[T30] Swift：协议
来源：http://dali.aizwys.cn/Article/details/gtdijjuwtp.html

protocol Shape { func area() -> Double }
来源：http://dali.svipenyu.cn/Article/details/gtfeuupkud.html

[T31] Lua：Hello World
来源：http://dali.daxiang520.top/Article/details/gtenyxujap.html

print("Hello")
来源：http://dali.yj20258.top/Article/details/gttngjenvm.html

[T32] Lua：局部变量
来源：http://dali.quarkkingdee.top/Article/details/gtnqgfahpz.html

local a = 1
来源：http://dali.hfpthk.cn/Article/details/gtuajkkatc.html

[T33] Lua：表（数组）
来源：http://dali.tianlin.xyz/Article/details/gtpcfwmlag.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.sufxvd.cn/Article/details/gttwzfrlue.html

[T34] Lua：遍历表
来源：http://dali.wangshuangyany.cn/Article/details/gtzsvlbbiz.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.ehwqpu.com/Article/details/gtnhcxgnct.html

[T35] Lua：字典表
来源：http://dali.svipenyu.cn/Article/details/gteasdwziv.html

local d = { a = 1 };  d.b = 2
来源：http://dali.wangdashe.top/Article/details/gtjllkihpo.html

[T36] Lua：函数
来源：http://dali.hammf.cn/Article/details/gtlkeiqfxg.html

function add(a, b) return a + b end
来源：http://dali.yuxming.cn/Article/details/gtxatqoman.html

[T37] Lua：字符串拼接
来源：http://dali.316326.xyz/Article/details/gticyndbas.html

"a" .. "b"
来源：http://dali.hammf.cn/Article/details/gtbbecnvko.html

[T38] Lua：条件
来源：http://dali.yvedp.cn/Article/details/gttkmrybbp.html

if x > 0 then print("正") end
来源：http://dali.jinqigfzy.top/Article/details/gtetfnqxga.html

[T39] Lua：模式匹配
来源：http://dali.xziqi.cn/Article/details/gtmovvrakt.html

string.find(s, "%d+")
来源：http://dali.yanxiufei.cn/Article/details/gtxcpdghcz.html

[T40] Lua：元表
来源：http://dali.xziqi.cn/Article/details/gtpryjuccn.html

setmetatable({}, { __index = base })
来源：http://dali.yvedp.cn/Article/details/gtjhqzuxsa.html

[T41] Perl：Hello World
来源：http://dali.jqgfzy.top/Article/details/gthfrpshuv.html

print "Hello\n";
来源：http://dali.c1oappe.top/Article/details/gtlyvixmnj.html

[T42] Perl：变量类型
来源：http://dali.jlsjyb.cn/Article/details/gtyccpzmgi.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.hfpthk.cn/Article/details/gtxtwienof.html

[T43] Perl：字符串插值
来源：http://dali.smart0.xyz/Article/details/gtzwsvizsf.html

"值: $a"
来源：http://dali.zdqjudy.top/Article/details/gtjxuuigbi.html

[T44] Perl：条件
来源：http://dali.havefunace.top/Article/details/gtnrfrhakl.html

if ($a > 0) { print "正"; }
来源：http://dali.dianchejie.cn/Article/details/gtgoktadnn.html

[T45] Perl：数组遍历
来源：http://dali.316326.xyz/Article/details/gtwaqjwcaw.html

for my $x (@arr) { print $x; }
来源：http://dali.birdmap.top/Article/details/gtsizjpwis.html

[T46] Perl：哈希操作
来源：http://dali.zdqjudy.top/Article/details/gtnvgunegs.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.xuanzx.com/Article/details/gtmniaicbd.html

[T47] Perl：正则捕获
来源：http://dali.pycfn.com/Article/details/gtluijhjkc.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.shzxlz.cn/Article/details/gtgrqjjfdk.html

[T48] Perl：正则替换
来源：http://dali.c1oappe.top/Article/details/gtplhoglav.html

$s =~ s/old/new/g;
来源：http://dali.shanyushiyangtech.top/Article/details/gtbssvicsp.html

[T49] Perl：函数
来源：http://dali.zhengqikj.top/Article/details/gtrnuaxwgf.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.sufxvd.cn/Article/details/gtgayuhajq.html

[T50] Perl：逐行读文件
来源：http://dali.yvedp.cn/Article/details/gtrhgqgtgz.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.wangshuangyany.cn/Article/details/gtnzszglzk.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.guannengcc.top/Article/details/gtzbbuhqaj.html

[T51] Scala：Hello World
来源：http://dali.hfpthk.cn/Article/details/gtfaodfhzc.html

println("Hello")
来源：http://dali.yueranfly.top/Article/details/gtuomdaepe.html

[T52] Scala：变量
来源：http://dali.havefunace.top/Article/details/gtwroreebh.html


<!-- 参考信息 -->