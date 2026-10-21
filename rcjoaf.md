代发 wailian999

ssh user@host 'uptime'
来源：http://dali.hammf.cn/Article/details/gtrspirjvu.html

[R58] 下载文件
来源：http://dali.zhoulong.xyz/Article/details/gthjcbrslo.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.9152youxi.cn/Article/details/gtkpgvjply.html

[R59] 发 POST JSON
来源：http://dali.redwolf501.top/Article/details/gtmklgfhdx.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.aibaodan.cn/Article/details/gtrpywryjb.html

[R60] 只看 HTTP 状态码
来源：http://dali.xuetiantiany.cn/Article/details/gtxbyosmhc.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.ywan-chungtsiang.top/Article/details/gtetbbvurr.html

[R61] 磁盘占用
来源：http://dali.sxryk.cn/Article/details/gtrmafyujp.html

df -h;  du -sh *
来源：http://dali.hnxiangtu.top/Article/details/gttpeckjdi.html

[R62] 找最占空间的文件
来源：http://dali.zhengqikj.top/Article/details/gtrmlqmhwt.html

du -ah . | sort -rh | head -10
来源：http://dali.gaohongyu789.top/Article/details/gtcoagcgkl.html

[R63] 内存与进程
来源：http://dali.cqqwz.cn/Article/details/gtzijxdjqf.html

free -h;  ps aux | grep nginx
来源：http://dali.dashuyun.cn/Article/details/gtugctjkah.html

[R64] 结束进程
来源：http://dali.yonumen.top/Article/details/gtedpfpccn.html

kill -9 $(pgrep -f app.py)
来源：http://dali.cdnleiting.top/Article/details/gtqstqodou.html

[R65] 查看端口占用
来源：http://dali.birdmap.top/Article/details/gtmqksakej.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.yanxiufei.cn/Article/details/gtyaytqquj.html

[R66] 定时任务
来源：http://dali.zdqjudy.top/Article/details/gtqvtpclpv.html

crontab -e;  crontab -l
来源：http://dali.dashuyun.cn/Article/details/gttkmlfbgj.html

[R67] 生成随机十六进制串
来源：http://dali.ybcxt.top/Article/details/gtrbnltrst.html

openssl rand -hex 16
来源：http://dali.cashguo.top/Article/details/gtqwperhzh.html

[R68] 计算文件校验值
来源：http://dali.dianchejie.cn/Article/details/gtuenoagjo.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.tanke756.top/Article/details/gtnawnvwbp.html

[R69] 生成随机密码
来源：http://dali.xziqi.cn/Article/details/gtqhzhxfqd.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gtveiashjc.html

[R70] 时间戳与互转
来源：http://dali.jinqigufen.top/Article/details/gtxqhlhyff.html

date +%s;  date -d @1700000000
来源：http://dali.nwbrower.top/Article/details/gtgccruqbc.html

[R71] 日期格式化
来源：http://dali.jyoumei.cn/Article/details/gtuuikejlo.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.snrcjt.cn/Article/details/gtrbhfviyb.html

[R72] 等待端口就绪
来源：http://dali.wangdashe.top/Article/details/gtriszggiu.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.gaohongyu789.top/Article/details/gtvvedcyqm.html

[R73] 分割大日志
来源：http://dali.ivvv.top/Article/details/gtrprmdjlu.html

split -l 1000 big.log part_
来源：http://dali.tianlin.xyz/Article/details/gtrorloxtx.html

[R74] 批量重命名
来源：http://dali.kuanghao11.cn/Article/details/gtpfvwhybs.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.yongpay.top/Article/details/gtjgklfbym.html

[R75] 导出环境变量
来源：http://dali.jyoumei.cn/Article/details/gtsdqgacmn.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.bjfxy.top/Article/details/gtqqrwoufc.html

[R76] 使用临时文件
来源：http://dali.cashguo.top/Article/details/gtwpcbrwhq.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.yj20258.top/Article/details/gttfkyamtv.html

[R77] 读取用户输入
来源：http://dali.yuxming.cn/Article/details/gtissanmpe.html

read -rp "请输入: " ans
来源：http://dali.svipenyu.cn/Article/details/gtankfgbtb.html

[R78] 交互式菜单
来源：http://dali.nanxinkj.top/Article/details/gtqtczmrmh.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.yvedp.cn/Article/details/gttsiozsas.html

[R79] 解析命令行选项
来源：http://dali.ehwqpu.com/Article/details/gtnxpeopas.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.ywan-chungtsiang.top/Article/details/gtntklwpqx.html

[R80] 查看脚本执行耗时
来源：http://dali.gotoacloud.top/Article/details/gtaciwkxun.html

time ./run.sh
来源：http://dali.nanxuanxn.top/Article/details/gtkhywzosx.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtonybynsr.html

S. C / C++ 专题
来源：http://dali.aizwys.cn/Article/details/gtstvlnfwf.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtbyswsrud.html

[S01] C：Hello World
来源：http://dali.gotoacloud.top/Article/details/gtjzvjcakg.html

#include <stdio.h>
来源：http://dali.yuanzhike.top/Article/details/gtmmnimtvb.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.nanxinkj.top/Article/details/gtgcpsgtjl.html

[S02] C：变量与格式化输出
来源：http://dali.bjfxy.top/Article/details/gtelopkabx.html

int a = 10; printf("%d\n", a);
来源：http://dali.cheryme.top/Article/details/gtbfnnbtyd.html

[S03] C：读入整数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnbeqpdar.html

int x; scanf("%d", &x);
来源：http://dali.hongshengwenyu.top/Article/details/gtoalhjgox.html

[S04] C：字符串复制
来源：http://dali.mhx1999.top/Article/details/gtldjvxxkl.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.sufxvd.cn/Article/details/gtafajglxz.html

[S05] C：字符串长度
来源：http://dali.daria6918.cn/Article/details/gtvdwkfgos.html

strlen(s)
来源：http://dali.cdnleiting.top/Article/details/gtdjnpkmfw.html

[S06] C：字符串比较
来源：http://dali.tianlin.xyz/Article/details/gtgopyojru.html

strcmp(a, b) == 0
来源：http://dali.nwbrower.top/Article/details/gtavwedjxf.html

[S07] C：数组遍历求和
来源：http://dali.yonumen.top/Article/details/gtuscezslp.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.ppjwa.cn/Article/details/gtcmylsyme.html

[S08] C：动态内存分配与释放
来源：http://dali.bjfxy.top/Article/details/gtltnmyphj.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.guowangkeji.top/Article/details/gtjpxsmoue.html

[S09] C：结构体定义与初始化
来源：http://dali.jianghu66.top/Article/details/gtfwyjhrmq.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.chenjidiqi.icu/Article/details/gtunfxeigj.html

[S10] C：指针与解引用
来源：http://dali.kuanghao11.cn/Article/details/gtntcaqznu.html

int *p = &a;  *p = 5;
来源：http://dali.nanxinkj.top/Article/details/gtaagzwqyy.html

[S11] C：逐行读文件
来源：http://dali.hywenlv.cn/Article/details/gtqyzyboig.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.chenzaomai.com/Article/details/gtyspyizdh.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.yj202588.top/Article/details/gtbhvvoned.html

fclose(f);
来源：http://dali.hnxiangtu.top/Article/details/gtbkqqtuex.html

[S12] C：写文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtssvbnwpl.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.cucudq.cn/Article/details/gthaxuacnf.html

[S13] C：宏定义
来源：http://dali.nanxuanxn.top/Article/details/gtuvcocmkj.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhixingplan.top/Article/details/gtpszmnnlk.html

[S14] C：枚举
来源：http://dali.zhaomingkeji.xyz/Article/details/gtamcqbeug.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.xuanzx.com/Article/details/gtgmbbqwbo.html

[S15] C：类型转换
来源：http://dali.cheryme.top/Article/details/gthdjrdgzk.html

(double) a / b
来源：http://dali.aibaodan.cn/Article/details/gtvjwnhcan.html

[S16] C：位操作置位
来源：http://dali.cdnleiting.top/Article/details/gtxmkglzpi.html

x |= (1 << 3);
来源：http://dali.iojbl.cn/Article/details/gtbqpkghdf.html

[S17] C：安全拼接字符串
来源：http://dali.yonumen.top/Article/details/gtgepxogns.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.jqgfzy.top/Article/details/gtqraipoor.html

[S18] C：命令行参数
来源：http://dali.nanxinkj.top/Article/details/gtnidvqmno.html

int main(int argc, char **argv)
来源：http://dali.wangshuangyany.cn/Article/details/gtknknmqlu.html

[S19] C：快速排序
来源：http://dali.sweek.top/Article/details/gtdutsvkyt.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.tianlin.xyz/Article/details/gtthjompew.html

[S20] C：二分查找
来源：http://dali.zhiwuduotai.top/Article/details/gtkspfoylp.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.9152youxi.cn/Article/details/gtqrplrdxm.html

[S21] C：字符类别判断
来源：http://dali.cashguo.top/Article/details/gtieaokype.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.daxiang520.top/Article/details/gtkdsquhlc.html

[S22] C：字符串转数字
来源：http://dali.jinqigfzy.top/Article/details/gtdarmqjhm.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.xinyue.icu/Article/details/gtodibtjwr.html

[S23] C：随机数
来源：http://dali.shangyingyoupin.top/Article/details/gtnootblme.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.gaohongyu789.top/Article/details/gtdkdexcak.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gtppbkclhe.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.yuanzhike.top/Article/details/gtnuuiorjk.html

[S25] C：内存拷贝
来源：http://dali.yuanzhike.top/Article/details/gthpefzlak.html

memcpy(dst, src, n);
来源：http://dali.chenzaomai.com/Article/details/gttrcehjgx.html

[S26] C：内存清零
来源：http://dali.cheryme.top/Article/details/gtspmmtkim.html

memset(a, 0, sizeof a);
来源：http://dali.chenjidiqi.icu/Article/details/gttojwnaeh.html

[S27] C：定义常量
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttnkuvjqs.html

const double PI = 3.14159;
来源：http://dali.pycfn.com/Article/details/gtykwskuuv.html

[S28] C：静态变量
来源：http://dali.snrcjt.cn/Article/details/gtwnnqznfd.html

static int counter = 0;
来源：http://dali.dashuyun.cn/Article/details/gtvffjmfbd.html

[S29] C：变参函数
来源：http://dali.shuidangran.top/Article/details/gtmrjgiwes.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.kuanghao11.cn/Article/details/gtplpvpttv.html

[S30] C：头文件保护
来源：http://dali.daxiang520.top/Article/details/gtnlklucvt.html

#ifndef X_H
来源：http://dali.cqqwz.cn/Article/details/gtzznuxqtd.html

#define X_H
来源：http://dali.smart0.xyz/Article/details/gtyrgptlgv.html

#endif
来源：http://dali.yueranfly.top/Article/details/gtipfagbui.html

[S31] C++：Hello World
来源：http://dali.xziqi.cn/Article/details/gtprqxgqwq.html

#include <iostream>
来源：http://dali.cheryme.top/Article/details/gtbeuyagrd.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.cdnleiting.top/Article/details/gtytaldjsm.html

[S32] C++：字符串
来源：http://dali.yvedp.cn/Article/details/gtxienhqde.html

std::string s = "hi";  s += "!";
来源：http://dali.zhoulong.xyz/Article/details/gtsguxqxnx.html

[S33] C++：vector 增删
来源：http://dali.nanxinkj.top/Article/details/gtkovxcujp.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.cdnleiting.top/Article/details/gtyifcnxia.html

[S34] C++：遍历 vector
来源：http://dali.sxryk.cn/Article/details/gtphihtzsf.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.haohaochexian.top/Article/details/gtnrjzobco.html

[S35] C++：map
来源：http://dali.cashguo.top/Article/details/gtjrqgpppt.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhixingplan.top/Article/details/gtaocnwten.html

[S36] C++：unordered_map
来源：http://dali.redwolf501.top/Article/details/gtkurlppky.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gttetvwooe.html

[S37] C++：set
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnfivqipg.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.ivvv.top/Article/details/gtbgnmyvfh.html

[S38] C++：排序
来源：http://dali.jinqigfzy.top/Article/details/gtvuyeiyjk.html

std::sort(v.begin(), v.end());
来源：http://dali.yuanzhike.top/Article/details/gtlywxwqfn.html

[S39] C++：自定义比较器排序
来源：http://dali.daxiang520.top/Article/details/gtvmzyxxsv.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.jqgufenzy.top/Article/details/gtbjhtdbii.html

[S40] C++：查找元素
来源：http://dali.tianlin.xyz/Article/details/gttcdlcjfz.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.chenzaomai.com/Article/details/gtvpjjmhug.html

[S41] C++：类与构造函数
来源：http://dali.cdnleiting.top/Article/details/gtntcepqjx.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.ydzc1.top/Article/details/gtibzfpyfs.html

[S42] C++：继承与虚函数
来源：http://dali.cucudq.cn/Article/details/gtwykffxjy.html

class B : public Base { public: void f() override {} };
来源：http://dali.hongshengwenyu.top/Article/details/gtuyeertic.html

[S43] C++：智能指针
来源：http://dali.sxryk.cn/Article/details/gtgvoqsait.html

auto p = std::make_unique<int>(5);
来源：http://dali.tian-w.cn/Article/details/gtokwggmgq.html

[S44] C++：引用传参
来源：http://dali.ivvv.top/Article/details/gtvpjdpauo.html

void inc(int &x) { ++x; }
来源：http://dali.gzhubu.top/Article/details/gtyrflffos.html

[S45] C++：lambda
来源：http://dali.ehwqpu.com/Article/details/gtkartylrt.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.shuidangran.top/Article/details/gtwlckoilc.html

[S46] C++：函数模板
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjvjrlxwx.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtotpnxatu.html

[S47] C++：结构化绑定遍历
来源：http://dali.wangshuangyany.cn/Article/details/gtyvfgfayr.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gtdklmojhf.html

[S48] C++：逐行读文件
来源：http://dali.haohaochexian.top/Article/details/gtdkqiqhzu.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.kuanghao11.cn/Article/details/gtqikzgxkr.html

while (std::getline(in, line)) { }
来源：http://dali.yongpay.top/Article/details/gtkxamaqty.html

[S49] C++：写文件
来源：http://dali.smart0.xyz/Article/details/gtnwmzcybc.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.dianchejie.cn/Article/details/gtaqwchzte.html

[S50] C++：格式化数字
来源：http://dali.zhongyouzk.top/Article/details/gtxrayljqc.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.xinyue.icu/Article/details/gtnobzdjpj.html

[S51] C++：显式类型转换
来源：http://dali.yvedp.cn/Article/details/gttejfllrn.html

static_cast<double>(a) / b
来源：http://dali.nanxuanxn.top/Article/details/gtuuoctdyb.html

[S52] C++：const 与 noexcept
来源：http://dali.gogol.net.cn/Article/details/gtntthsmyl.html

int size() const noexcept { return n_; }
来源：http://dali.chenlongwang.top/Article/details/gthaybrbto.html

[S53] C++：移动语义
来源：http://dali.sysykeji.top/Article/details/gtqdqxcsco.html

std::vector<int> w = std::move(v);
来源：http://dali.yangfankeji.com/Article/details/gtrohrhmzg.html

[S54] C++：异常处理
来源：http://dali.jinqigufen.top/Article/details/gtgmttghxb.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.shanyushiyangtech.top/Article/details/gtkebidggl.html

[S55] C++：结构化绑定
来源：http://dali.fengsongda.top/Article/details/gtogliwltq.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.haohaochexian.top/Article/details/gtwsdwtppw.html

[S56] C++：optional
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdvgbkewt.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.snrcjt.cn/Article/details/gtkyuylvix.html

[S57] C++：编译期常量
来源：http://dali.hysaishi.cn/Article/details/gtmbpfgetu.html

constexpr int N = 10;
来源：http://dali.yonumen.top/Article/details/gtbzrxxlwp.html

[S58] C++：命名空间
来源：http://dali.nanxuanxn.top/Article/details/gtxubadcpt.html

namespace ns { int f() { return 1; } }
来源：http://dali.zycfv.cn/Article/details/gtplzghxfv.html

[S59] C++：静态断言
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvcjsniui.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.pengpengdd.cyou/Article/details/gtaumgwqnj.html

[S60] C++：遍历并删除元素
来源：http://dali.xuetiantiany.cn/Article/details/gtktbwwyps.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.sufxvd.cn/Article/details/gtuosfslzl.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtsdfvclsq.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.cucudq.cn/Article/details/gtobbiqchr.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtwezwaduc.html

[T01] Kotlin：Hello World
来源：http://dali.aibaodan.cn/Article/details/gtvmscczec.html

println("Hello")
来源：http://dali.wangshuangyany.cn/Article/details/gtcmphzphs.html

[T02] Kotlin：变量
来源：http://dali.jqgfzy.top/Article/details/gtzgitxisd.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhongyouzk.top/Article/details/gtnlqymxbu.html

[T03] Kotlin：字符串模板
来源：http://dali.dianchejie.cn/Article/details/gtxcyvaggs.html

"值: $b"
来源：http://dali.ybcxt.top/Article/details/gtevmigsme.html

[T04] Kotlin：空安全
来源：http://dali.xziqi.cn/Article/details/gtfvtinqdc.html

val n: String? = null;  n?.length
来源：http://dali.chenlongwang.top/Article/details/gtuttdaccs.html

[T05] Kotlin：when 表达式
来源：http://dali.birdmap.top/Article/details/gtnoaonqlz.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.yj20258.top/Article/details/gtoptofvgf.html

[T06] Kotlin：集合映射
来源：http://dali.yongpay.top/Article/details/gtymmexhem.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.kuanghao11.cn/Article/details/gtmljatryp.html

[T07] Kotlin：集合过滤
来源：http://dali.ehwqpu.com/Article/details/gtvlqtqwrd.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.yonumen.top/Article/details/gtoskoqiwg.html

[T08] Kotlin：数据类
来源：http://dali.yueranfly.top/Article/details/gtuibtbysn.html

data class User(val name: String, val age: Int)
来源：http://dali.tanke756.top/Article/details/gtssoszaqy.html

[T09] Kotlin：扩展函数
来源：http://dali.fzhhl.top/Article/details/gtcqheuihf.html

fun String.exclaim() = this + "!"
来源：http://dali.guannengcc.top/Article/details/gtmrpagxvo.html

[T10] Kotlin：默认参数
来源：http://dali.gaohongyu789.top/Article/details/gtjhfgmdmt.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.dianchejie.cn/Article/details/gtftylxngu.html

[T11] Kotlin：协程
来源：http://dali.wangshuangyany.cn/Article/details/gtllmvtffc.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.wangshuangyany.cn/Article/details/gtcpptmolz.html

[T12] Kotlin：解构声明
来源：http://dali.fengsongda.top/Article/details/gtovuimklz.html

val (a, b) = Pair(1, 2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqgiexatg.html

[T13] Kotlin：只读 Map
来源：http://dali.cheryme.top/Article/details/gtqwsdwzvw.html

val m = mapOf("a" to 1)
来源：http://dali.cheryme.top/Article/details/gtiyigmemz.html

[T14] Kotlin：循环
来源：http://dali.sysykeji.top/Article/details/gtnmgeydno.html

for (i in 1..10) println(i)
来源：http://dali.xylfe.cn/Article/details/gtdoomhatr.html

[T15] Kotlin：接口
来源：http://dali.tian-w.cn/Article/details/gtpeeecrhd.html

interface Shape { fun area(): Double }
来源：http://dali.cheryme.top/Article/details/gtrexortkl.html

[T16] Swift：Hello World
来源：http://dali.haohaochexian.top/Article/details/gtajiaunpi.html

print("Hello")
来源：http://dali.yanxiufei.cn/Article/details/gtlvmuusyb.html

[T17] Swift：变量与常量
来源：http://dali.guannengcc.top/Article/details/gtaaypqnkt.html

var a = 1;  let b = 2
来源：http://dali.hysaishi.cn/Article/details/gtmgbjjfrg.html

[T18] Swift：字符串插值
来源：http://dali.smart0.xyz/Article/details/gtahiliqmm.html

"值: \(b)"
来源：http://dali.ybcxt.top/Article/details/gtzgqstdup.html

[T19] Swift：可选绑定
来源：http://dali.aibaodan.cn/Article/details/gtanwnmfrf.html

if let n = opt { print(n) }
来源：http://dali.vqdsnc.cn/Article/details/gtwngzdhur.html

[T20] Swift：数组操作
来源：http://dali.bjfxy.top/Article/details/gtaydkgwvy.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhixingplan.top/Article/details/gtroxvxrkx.html

[T21] Swift：遍历
来源：http://dali.tianlin.xyz/Article/details/gtdiyoluei.html

for x in a { print(x) }
来源：http://dali.gzhubu.top/Article/details/gtqkfapusm.html

[T22] Swift：字典
来源：http://dali.cqqwz.cn/Article/details/gtlrhjdnib.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.shanyushiyangtech.top/Article/details/gtcsxypsvw.html

[T23] Swift：函数
来源：http://dali.nanxinkj.top/Article/details/gtqbokqhkl.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhiwuduotai.top/Article/details/gtrbslnvda.html

[T24] Swift：闭包
来源：http://dali.feifeiyinyue.top/Article/details/gtedfdomhr.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.tianlin.xyz/Article/details/gtqrderfix.html

[T25] Swift：结构体
来源：http://dali.chenlongwang.top/Article/details/gtcynoqkmm.html

struct P { var x: Int }
来源：http://dali.bjfxy.top/Article/details/gtnkxvclsa.html

[T26] Swift：类与重写
来源：http://dali.jqgufenzy.top/Article/details/gttqelvapm.html

class A: Base { override func f() {} }
来源：http://dali.chenzaomai.com/Article/details/gtqodyzank.html

[T27] Swift：错误处理
来源：http://dali.shzxlz.cn/Article/details/gtetklbamx.html

do { try f() } catch { print(error) }
来源：http://dali.zhengqikj.top/Article/details/gttfzagrna.html

[T28] Swift：枚举
来源：http://dali.ybcxt.top/Article/details/gtcmltpwdj.html

enum Color { case red, green }
来源：http://dali.redwolf501.top/Article/details/gtxiiajjfr.html

[T29] Swift：guard 提前返回
来源：http://dali.fzhhl.top/Article/details/gtzznjaoxd.html

guard let x = opt else { return }
来源：http://dali.zhiwuduotai.top/Article/details/gtkafubezr.html

[T30] Swift：协议
来源：http://dali.gotoacloud.top/Article/details/gtqsuqavmq.html

protocol Shape { func area() -> Double }
来源：http://dali.yj20258888.top/Article/details/gtfaevvdet.html

[T31] Lua：Hello World
来源：http://dali.yvedp.cn/Article/details/gtdjblczra.html

print("Hello")
来源：http://dali.ppjwa.cn/Article/details/gtgsmwbjgc.html

[T32] Lua：局部变量
来源：http://dali.gogol.net.cn/Article/details/gtrhpkvaus.html

local a = 1
来源：http://dali.jinqigfzy.top/Article/details/gtnwweehbj.html

[T33] Lua：表（数组）
来源：http://dali.chenzaomai.com/Article/details/gtyqgccpof.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.ybcxt.top/Article/details/gttfwjpxre.html

[T34] Lua：遍历表
来源：http://dali.aibaodan.cn/Article/details/gtxpysecrk.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.yanxiufei.cn/Article/details/gtvvotxoxy.html

[T35] Lua：字典表
来源：http://dali.yj20258888.top/Article/details/gtwbfmjyvx.html

local d = { a = 1 };  d.b = 2
来源：http://dali.c1oappe.top/Article/details/gtegjkvtch.html

[T36] Lua：函数
来源：http://dali.sweek.top/Article/details/gtdzitetgf.html

function add(a, b) return a + b end
来源：http://dali.bjfxy.top/Article/details/gtlcfnzdlh.html

[T37] Lua：字符串拼接
来源：http://dali.wangdashe.top/Article/details/gticbmoudp.html

"a" .. "b"
来源：http://dali.yanxiufei.cn/Article/details/gtzxlfmcqw.html

[T38] Lua：条件
来源：http://dali.hnxiangtu.top/Article/details/gtlojlsvez.html

if x > 0 then print("正") end
来源：http://dali.havefunace.top/Article/details/gtnsltxxxo.html

[T39] Lua：模式匹配
来源：http://dali.zhoulong.xyz/Article/details/gtzkhhcddb.html

string.find(s, "%d+")
来源：http://dali.jianghu66.top/Article/details/gtbhbgwmur.html

[T40] Lua：元表
来源：http://dali.guowangkeji.top/Article/details/gtpovfbdqt.html

setmetatable({}, { __index = base })
来源：http://dali.cucudq.cn/Article/details/gtggxstjcy.html

[T41] Perl：Hello World
来源：http://dali.hongshengwenyu.top/Article/details/gtyhvsthsc.html

print "Hello\n";
来源：http://dali.yj202588.top/Article/details/gtqkcvyiod.html

[T42] Perl：变量类型
来源：http://dali.wangshuangyany.cn/Article/details/gtokzwxglb.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.cdnleiting.top/Article/details/gtfuvebksj.html

[T43] Perl：字符串插值
来源：http://dali.dashuyun.cn/Article/details/gthkgjdlte.html

"值: $a"
来源：http://dali.9152youxi.cn/Article/details/gtdvoyhqqk.html

[T44] Perl：条件
来源：http://dali.xylfe.cn/Article/details/gtnbwhlsuk.html

if ($a > 0) { print "正"; }
来源：http://dali.vqdsnc.cn/Article/details/gtfrbtrwqa.html

[T45] Perl：数组遍历
来源：http://dali.snrcjt.cn/Article/details/gtgmbpzzlw.html

for my $x (@arr) { print $x; }
来源：http://dali.yangfankeji.com/Article/details/gtpoirztuu.html

[T46] Perl：哈希操作
来源：http://dali.zhoulong.xyz/Article/details/gtlrsqqbna.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.redwolf501.top/Article/details/gtowizlhvp.html

[T47] Perl：正则捕获
来源：http://dali.meibo888.top/Article/details/gtmizsefvb.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.guannengcc.top/Article/details/gtqoaeufko.html

[T48] Perl：正则替换
来源：http://dali.yangfankeji.com/Article/details/gtjidgeurf.html

$s =~ s/old/new/g;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqogylnmg.html

[T49] Perl：函数
来源：http://dali.quarkkingdee.top/Article/details/gtrxdrxygb.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.dianchejie.cn/Article/details/gttydmdmfe.html

[T50] Perl：逐行读文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqlscagkj.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.yonumen.top/Article/details/gtdrnwvcpc.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.xziqi.cn/Article/details/gtoitccyph.html

[T51] Scala：Hello World
来源：http://dali.mhx1999.top/Article/details/gtpjeixbmj.html

println("Hello")
来源：http://dali.nanxinkj.top/Article/details/gtmvobexss.html

[T52] Scala：变量
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmlsrhvsu.html

val a = 1;  var b = 2
来源：http://dali.guannengcc.top/Article/details/gtrlwqjxsu.html

[T53] Scala：字符串插值
来源：http://dali.gaohongyu789.top/Article/details/gtuwttygye.html

s"值: $b"
来源：http://dali.316326.xyz/Article/details/gtpkpqtpxy.html

[T54] Scala：集合映射
来源：http://dali.hongshengwenyu.top/Article/details/gtnkhjnuki.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.ivvv.top/Article/details/gtqvzutbox.html

[T55] Scala：集合过滤
来源：http://dali.yonumen.top/Article/details/gtakjlywco.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.cdnleiting.top/Article/details/gtztbsrren.html

[T56] Scala：样例类
来源：http://dali.xuetiantiany.cn/Article/details/gturvciazb.html

case class User(name: String, age: Int)
来源：http://dali.shuidangran.top/Article/details/gtngktxpuw.html

[T57] Scala：模式匹配
来源：http://dali.gotoacloud.top/Article/details/gtekbxzrhc.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gtphfsuqfh.html

[T58] Scala：函数定义
来源：http://dali.jyoumei.cn/Article/details/gtvbbdleeq.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhengqikj.top/Article/details/gtdmylcjhs.html

[T59] Scala：循环
来源：http://dali.wangdashe.top/Article/details/gthyhkjjzd.html

for (i <- 1 to 10) println(i)
来源：http://dali.xuanzx.com/Article/details/gttqvrzkli.html

[T60] Scala：折叠
来源：http://dali.zhoulong.xyz/Article/details/gtnwqvcddl.html


<!-- 参考信息 -->