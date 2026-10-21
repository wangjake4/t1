代发 wailian999

find . -name "*.tmp" -delete
来源：http://dali.gogol.net.cn/Article/details/gtizulwykr.html

[R46] 递归替换文件内容
来源：http://dali.jinqigfzy.top/Article/details/gtajtztfxv.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.redwolf501.top/Article/details/gtgnjpjsuz.html

[R47] sed 单行替换
来源：http://dali.vqdsnc.cn/Article/details/gtrvlvhkil.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.andypj.xyz/Article/details/gtishlopwb.html

[R48] awk 取指定列
来源：http://dali.hnxiangtu.top/Article/details/gthtgmdlvt.html

awk '{print $1, $3}' a.txt
来源：http://dali.xinyue.icu/Article/details/gtdalqntbz.html

[R49] awk 带条件
来源：http://dali.xinyue.icu/Article/details/gtgoysypeo.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.yj202588.top/Article/details/gtzezrfncj.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gtlgdhykrq.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.nwbrower.top/Article/details/gtmjfdxcqb.html

[R51] 排序去重取前几
来源：http://dali.hysaishi.cn/Article/details/gtodfwywkj.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.hfpthk.cn/Article/details/gttnwkirmy.html

[R52] 统计行数
来源：http://dali.shuidangran.top/Article/details/gtguphbetv.html

wc -l a.txt
来源：http://dali.ppjwa.cn/Article/details/gtpbwanpjk.html

[R53] 查看文件头与实时尾
来源：http://dali.shangyingyoupin.top/Article/details/gtnsgrskor.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.shanyushiyangtech.top/Article/details/gtdparyuha.html

[R54] 比较两个文件
来源：http://dali.gzhubu.top/Article/details/gtnodxstgb.html

diff a.txt b.txt
来源：http://dali.yonumen.top/Article/details/gtfezuumjb.html

[R55] 压缩与解压
来源：http://dali.shanyushiyangkeji.top/Article/details/gtinkwtvqi.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.guowangkeji.top/Article/details/gtfdpqptxm.html

[R56] 远程拷贝
来源：http://dali.guannengcc.top/Article/details/gtmwpplsjo.html

scp file user@host:/path/
来源：http://dali.jqgfzy.top/Article/details/gtdooutcdj.html

[R57] 远程执行命令
来源：http://dali.nanxuanxn.top/Article/details/gtwrfprskj.html

ssh user@host 'uptime'
来源：http://dali.sysykeji.top/Article/details/gtwwdiemjy.html

[R58] 下载文件
来源：http://dali.zdqjudy.top/Article/details/gtridwmowq.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.sweek.top/Article/details/gtxjhimlya.html

[R59] 发 POST JSON
来源：http://dali.hnqzz.top/Article/details/gtdtkeyrkn.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.ppjwa.cn/Article/details/gtlzrsmhcf.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhongyouzk.top/Article/details/gtvmdtfgfl.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.shanyushiyangtech.top/Article/details/gtyntfdsxm.html

[R61] 磁盘占用
来源：http://dali.zhixingplan.top/Article/details/gtjhtzuggz.html

df -h;  du -sh *
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthkbzftqi.html

[R62] 找最占空间的文件
来源：http://dali.cashguo.top/Article/details/gtjcvgqxto.html

du -ah . | sort -rh | head -10
来源：http://dali.hfpthk.cn/Article/details/gtjdxkyvzo.html

[R63] 内存与进程
来源：http://dali.smart0.xyz/Article/details/gtddjplfdc.html

free -h;  ps aux | grep nginx
来源：http://dali.yongpay.top/Article/details/gtcodirfnv.html

[R64] 结束进程
来源：http://dali.yj202588.top/Article/details/gtqpfuuiov.html

kill -9 $(pgrep -f app.py)
来源：http://dali.aibaodan.cn/Article/details/gtacqdkbde.html

[R65] 查看端口占用
来源：http://dali.yonumen.top/Article/details/gtrjnjuplq.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.nanxuanxn.top/Article/details/gtfoyrbmzh.html

[R66] 定时任务
来源：http://dali.svipenyu.cn/Article/details/gtvmcznxph.html

crontab -e;  crontab -l
来源：http://dali.gzhubu.top/Article/details/gttphatsjt.html

[R67] 生成随机十六进制串
来源：http://dali.hnxiangtu.top/Article/details/gtlusuharg.html

openssl rand -hex 16
来源：http://dali.meibo888.top/Article/details/gtijilnzcr.html

[R68] 计算文件校验值
来源：http://dali.bjfxy.top/Article/details/gtanjhwbwb.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.havefunace.top/Article/details/gtonvymriw.html

[R69] 生成随机密码
来源：http://dali.bjfxy.top/Article/details/gtvynezvjw.html

head -c 16 /dev/urandom | base64
来源：http://dali.jqgufenzy.top/Article/details/gtihxfilwi.html

[R70] 时间戳与互转
来源：http://dali.quarkkingdee.top/Article/details/gtfiecgqyu.html

date +%s;  date -d @1700000000
来源：http://dali.mhx1999.top/Article/details/gtkmxpxcxw.html

[R71] 日期格式化
来源：http://dali.nanxinkj.top/Article/details/gtffodgkte.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.yangfankeji.com/Article/details/gtgpaixcoa.html

[R72] 等待端口就绪
来源：http://dali.meibo888.top/Article/details/gtpbhwsdeu.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.gogol.net.cn/Article/details/gtqlefxdpn.html

[R73] 分割大日志
来源：http://dali.gogol.net.cn/Article/details/gtrifeiueu.html

split -l 1000 big.log part_
来源：http://dali.redwolf501.top/Article/details/gtxcsubjhw.html

[R74] 批量重命名
来源：http://dali.dianchejie.cn/Article/details/gtgvmsjvgc.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.yongpay.top/Article/details/gtyigvguol.html

[R75] 导出环境变量
来源：http://dali.0kj1m.cn/Article/details/gtmljcguae.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.yanxiufei.cn/Article/details/gtuuyfmeaw.html

[R76] 使用临时文件
来源：http://dali.cqqwz.cn/Article/details/gtcqabozqw.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.sweek.top/Article/details/gtzdjnwjoc.html

[R77] 读取用户输入
来源：http://dali.birdmap.top/Article/details/gtysyghuvp.html

read -rp "请输入: " ans
来源：http://dali.iojbl.cn/Article/details/gtsuhwuzjq.html

[R78] 交互式菜单
来源：http://dali.gaohongyu789.top/Article/details/gtviznqfro.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.jqgfzy.top/Article/details/gtnpcuxjcv.html

[R79] 解析命令行选项
来源：http://dali.cdnleiting.top/Article/details/gtqeaehlrq.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.gotoacloud.top/Article/details/gtoloukcye.html

[R80] 查看脚本执行耗时
来源：http://dali.jinqigufen.top/Article/details/gtggmyiyrv.html

time ./run.sh
来源：http://dali.hongshengwenyu.top/Article/details/gtxesecqyy.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtllrwqayt.html

S. C / C++ 专题
来源：http://dali.jiagoushi.top/Article/details/gtmbleryls.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gteuyewwyn.html

[S01] C：Hello World
来源：http://dali.nwbrower.top/Article/details/gtmzelceto.html

#include <stdio.h>
来源：http://dali.yueranfly.top/Article/details/gtgjjjxwdx.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.sxryk.cn/Article/details/gtcamzxprq.html

[S02] C：变量与格式化输出
来源：http://dali.c1oappe.top/Article/details/gtxaxeitcy.html

int a = 10; printf("%d\n", a);
来源：http://dali.yueranfly.top/Article/details/gtfhyikgpk.html

[S03] C：读入整数
来源：http://dali.cdnleiting.top/Article/details/gtazwevjlz.html

int x; scanf("%d", &x);
来源：http://dali.xinyue.icu/Article/details/gtolcyfcvy.html

[S04] C：字符串复制
来源：http://dali.hywenlv.cn/Article/details/gtwypojzdz.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gtvairbtqo.html

[S05] C：字符串长度
来源：http://dali.zdqjudy.top/Article/details/gtyqubzavf.html

strlen(s)
来源：http://dali.chenjidiqi.icu/Article/details/gtglokqwlw.html

[S06] C：字符串比较
来源：http://dali.hongshengwenyu.top/Article/details/gtxryuwyvj.html

strcmp(a, b) == 0
来源：http://dali.hywenlv.cn/Article/details/gtrwyopxar.html

[S07] C：数组遍历求和
来源：http://dali.zycfv.cn/Article/details/gtltmempqp.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.quarkkingdee.top/Article/details/gthqryqnal.html

[S08] C：动态内存分配与释放
来源：http://dali.jinghuilouyu.cn/Article/details/gtsawdwcat.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.yonumen.top/Article/details/gtjpletfiq.html

[S09] C：结构体定义与初始化
来源：http://dali.jiagoushi.top/Article/details/gtgtbwvush.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.xinyue.icu/Article/details/gtvnuoejgj.html

[S10] C：指针与解引用
来源：http://dali.jqgufenzy.top/Article/details/gtyczlzapd.html

int *p = &a;  *p = 5;
来源：http://dali.chenlongwang.top/Article/details/gtjfkjmemg.html

[S11] C：逐行读文件
来源：http://dali.nwbrower.top/Article/details/gtwqpdtept.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.jianghu66.top/Article/details/gttnbnhpyu.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.dashuyun.cn/Article/details/gtchysbseo.html

fclose(f);
来源：http://dali.kuanghao11.cn/Article/details/gtpacrceux.html

[S12] C：写文件
来源：http://dali.xuetiantiany.cn/Article/details/gtqqklerhw.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.tian-w.cn/Article/details/gtjrqtzsnt.html

[S13] C：宏定义
来源：http://dali.hywenlv.cn/Article/details/gtqimelred.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpkqptcmo.html

[S14] C：枚举
来源：http://dali.pengpengdd.cyou/Article/details/gtioikdxfv.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.mhx1999.top/Article/details/gtcvbhgzyk.html

[S15] C：类型转换
来源：http://dali.tian-w.cn/Article/details/gtxhdvwlis.html

(double) a / b
来源：http://dali.guannengcc.top/Article/details/gtltiatwpw.html

[S16] C：位操作置位
来源：http://dali.ehwqpu.com/Article/details/gtdjpgjwhn.html

x |= (1 << 3);
来源：http://dali.ybcxt.top/Article/details/gtyovrgrql.html

[S17] C：安全拼接字符串
来源：http://dali.dianchejie.cn/Article/details/gtybxhgeds.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.quarkkingdee.top/Article/details/gtgzxuvhrp.html

[S18] C：命令行参数
来源：http://dali.hnqzz.top/Article/details/gtwvtneubu.html

int main(int argc, char **argv)
来源：http://dali.yongpay.top/Article/details/gthknjgkwv.html

[S19] C：快速排序
来源：http://dali.aibaodan.cn/Article/details/gtxrvetgjv.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.shangyingyoupin.top/Article/details/gtnbxrldgj.html

[S20] C：二分查找
来源：http://dali.jinqigfzy.top/Article/details/gttdzbefyw.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.shanyushiyangtech.top/Article/details/gtxonycszb.html

[S21] C：字符类别判断
来源：http://dali.cucudq.cn/Article/details/gtzcqckyvm.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.316326.xyz/Article/details/gtxzpahkpf.html

[S22] C：字符串转数字
来源：http://dali.gogol.net.cn/Article/details/gtewbisxxg.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.hammf.cn/Article/details/gtgvnhaerj.html

[S23] C：随机数
来源：http://dali.daxiang520.top/Article/details/gtwqjlvsju.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhongyouzk.top/Article/details/gthqdjrlfm.html

[S24] C：获取本地时间
来源：http://dali.yangfankeji.com/Article/details/gtlebhebdp.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.gogol.net.cn/Article/details/gtkdkuzmef.html

[S25] C：内存拷贝
来源：http://dali.yongpay.top/Article/details/gtbjwanzrf.html

memcpy(dst, src, n);
来源：http://dali.yanxiufei.cn/Article/details/gtbtcjmcdz.html

[S26] C：内存清零
来源：http://dali.shanyushiyangtech.top/Article/details/gtidtbraqf.html

memset(a, 0, sizeof a);
来源：http://dali.sxryk.cn/Article/details/gtkjxcismk.html

[S27] C：定义常量
来源：http://dali.zhengqikj.top/Article/details/gtyumaioly.html

const double PI = 3.14159;
来源：http://dali.aizwys.cn/Article/details/gtsaoggzoc.html

[S28] C：静态变量
来源：http://dali.hammf.cn/Article/details/gtinprgzjh.html

static int counter = 0;
来源：http://dali.yvedp.cn/Article/details/gtdhmzlwci.html

[S29] C：变参函数
来源：http://dali.kuanghao11.cn/Article/details/gtdxhdxlmb.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.wangdashe.top/Article/details/gtyrzwbdsx.html

[S30] C：头文件保护
来源：http://dali.haohaochexian.top/Article/details/gtqxskjdxo.html

#ifndef X_H
来源：http://dali.redwolf501.top/Article/details/gtmxiazbaz.html

#define X_H
来源：http://dali.guannengcc.top/Article/details/gtnfvehicz.html

#endif
来源：http://dali.xuanzx.com/Article/details/gtshzluvxi.html

[S31] C++：Hello World
来源：http://dali.daria6918.cn/Article/details/gtvkdykfed.html

#include <iostream>
来源：http://dali.shuidangran.top/Article/details/gtsdkkcikb.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gtprssuycq.html

[S32] C++：字符串
来源：http://dali.nwbrower.top/Article/details/gtbeajcebk.html

std::string s = "hi";  s += "!";
来源：http://dali.zycfv.cn/Article/details/gtwkpahxbh.html

[S33] C++：vector 增删
来源：http://dali.gzhubu.top/Article/details/gtouuxbyvp.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.mhx1999.top/Article/details/gtpxnqonmm.html

[S34] C++：遍历 vector
来源：http://dali.jinqigfzy.top/Article/details/gtwfhsrbsk.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.cheryme.top/Article/details/gtzuufkjlb.html

[S35] C++：map
来源：http://dali.zhongyouzk.top/Article/details/gtitmswklp.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.aibaodan.cn/Article/details/gtelfltpgm.html

[S36] C++：unordered_map
来源：http://dali.daxiang520.top/Article/details/gtllltaqth.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.aibaodan.cn/Article/details/gtobxslmps.html

[S37] C++：set
来源：http://dali.fengsongda.top/Article/details/gtslblqkjq.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.daxiang520.top/Article/details/gtutrfyrkk.html

[S38] C++：排序
来源：http://dali.gotoacloud.top/Article/details/gteuaujfdr.html

std::sort(v.begin(), v.end());
来源：http://dali.shangyingyoupin.top/Article/details/gtigemcjsd.html

[S39] C++：自定义比较器排序
来源：http://dali.xuetiantiany.cn/Article/details/gtpionzzxy.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.yj202588.top/Article/details/gtzjbutxbi.html

[S40] C++：查找元素
来源：http://dali.jlsjyb.cn/Article/details/gtbbtpghfr.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.wangdashe.top/Article/details/gtzypzdvoc.html

[S41] C++：类与构造函数
来源：http://dali.mhx1999.top/Article/details/gtlqqgzpil.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.nwbrower.top/Article/details/gtcphlkkga.html

[S42] C++：继承与虚函数
来源：http://dali.xylfe.cn/Article/details/gtdotendsg.html

class B : public Base { public: void f() override {} };
来源：http://dali.tianlin.xyz/Article/details/gtrwjmjrna.html

[S43] C++：智能指针
来源：http://dali.xylfe.cn/Article/details/gthqsccgjg.html

auto p = std::make_unique<int>(5);
来源：http://dali.hywenlv.cn/Article/details/gtfhvlyaxs.html

[S44] C++：引用传参
来源：http://dali.yueranfly.top/Article/details/gtbwphrivw.html

void inc(int &x) { ++x; }
来源：http://dali.wangdashe.top/Article/details/gtjdqcdaqc.html

[S45] C++：lambda
来源：http://dali.tianlin.xyz/Article/details/gtlmanjjdf.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.shuidangran.top/Article/details/gtldwgqjfv.html

[S46] C++：函数模板
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqxrdfpnr.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.0kj1m.cn/Article/details/gtpkemfrhd.html

[S47] C++：结构化绑定遍历
来源：http://dali.gogol.net.cn/Article/details/gtveypamcz.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.9152youxi.cn/Article/details/gtwuynwkwy.html

[S48] C++：逐行读文件
来源：http://dali.yvedp.cn/Article/details/gtfujdpnuf.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.xylfe.cn/Article/details/gtzeyourqh.html

while (std::getline(in, line)) { }
来源：http://dali.hammf.cn/Article/details/gtyfeomvsd.html

[S49] C++：写文件
来源：http://dali.meibo888.top/Article/details/gtqcpetbkv.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.yuxming.cn/Article/details/gtwdcjjokj.html

[S50] C++：格式化数字
来源：http://dali.vqdsnc.cn/Article/details/gtasvmwxsk.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.iojbl.cn/Article/details/gtwhsgdzki.html

[S51] C++：显式类型转换
来源：http://dali.yj20258.top/Article/details/gttpoinjqz.html

static_cast<double>(a) / b
来源：http://dali.birdmap.top/Article/details/gtifzpoxsi.html

[S52] C++：const 与 noexcept
来源：http://dali.zhiwuduotai.top/Article/details/gttdxappes.html

int size() const noexcept { return n_; }
来源：http://dali.ybcxt.top/Article/details/gtptugkuhr.html

[S53] C++：移动语义
来源：http://dali.hnxiangtu.top/Article/details/gttegiphih.html

std::vector<int> w = std::move(v);
来源：http://dali.yj202588.top/Article/details/gtwfjiwxmy.html

[S54] C++：异常处理
来源：http://dali.yangfankeji.com/Article/details/gtnybmasoi.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.tian-w.cn/Article/details/gtbteotmre.html

[S55] C++：结构化绑定
来源：http://dali.cqqwz.cn/Article/details/gtjnvehytr.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtegbozooa.html

[S56] C++：optional
来源：http://dali.gzhubu.top/Article/details/gtuoafhbmk.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.sxryk.cn/Article/details/gtfwyprrxg.html

[S57] C++：编译期常量
来源：http://dali.cdnleiting.top/Article/details/gtzksflbba.html

constexpr int N = 10;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtirwdhaox.html

[S58] C++：命名空间
来源：http://dali.birdmap.top/Article/details/gttzhtabbk.html

namespace ns { int f() { return 1; } }
来源：http://dali.hnqzz.top/Article/details/gtxfbnpypp.html

[S59] C++：静态断言
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvhdwlgao.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.bjfxy.top/Article/details/gtazlqucax.html

[S60] C++：遍历并删除元素
来源：http://dali.xinyue.icu/Article/details/gtelmjhrfg.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.ppjwa.cn/Article/details/gtebfdenym.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtjffuelko.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.wangshuangyany.cn/Article/details/gtwmkuojue.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtxqnkdsmk.html

[T01] Kotlin：Hello World
来源：http://dali.haohaochexian.top/Article/details/gtsddineea.html

println("Hello")
来源：http://dali.hnxiangtu.top/Article/details/gtlhlcrcio.html

[T02] Kotlin：变量
来源：http://dali.sysykeji.top/Article/details/gtbwcfvksj.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.gzhubu.top/Article/details/gtuhxfrvcu.html

[T03] Kotlin：字符串模板
来源：http://dali.316326.xyz/Article/details/gtjgwqftto.html

"值: $b"
来源：http://dali.hnxiangtu.top/Article/details/gtcxfrbzgn.html

[T04] Kotlin：空安全
来源：http://dali.nanxinkj.top/Article/details/gteeoyzdrv.html

val n: String? = null;  n?.length
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqlzwmiei.html

[T05] Kotlin：when 表达式
来源：http://dali.chenzaomai.com/Article/details/gtijtktplq.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.cucudq.cn/Article/details/gtbwjvryxq.html

[T06] Kotlin：集合映射
来源：http://dali.feifeiyinyue.top/Article/details/gtwkhhoawj.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.0kj1m.cn/Article/details/gtracmvbeo.html

[T07] Kotlin：集合过滤
来源：http://dali.daria6918.cn/Article/details/gtcdazpcbx.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.aibaodan.cn/Article/details/gtlxvrtoyc.html

[T08] Kotlin：数据类
来源：http://dali.nanxinkj.top/Article/details/gtakoeelro.html

data class User(val name: String, val age: Int)
来源：http://dali.zhoulong.xyz/Article/details/gtcmcrtfxm.html

[T09] Kotlin：扩展函数
来源：http://dali.hongshengwenyu.top/Article/details/gtciysyitk.html

fun String.exclaim() = this + "!"
来源：http://dali.guannengcc.top/Article/details/gtgagjypxq.html

[T10] Kotlin：默认参数
来源：http://dali.guannengcc.top/Article/details/gtaudnzhsr.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhixingplan.top/Article/details/gtlgpjusdl.html

[T11] Kotlin：协程
来源：http://dali.birdmap.top/Article/details/gtyitonevx.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.hfpthk.cn/Article/details/gtpihvxemp.html

[T12] Kotlin：解构声明
来源：http://dali.fzhhl.top/Article/details/gtevjcpohl.html

val (a, b) = Pair(1, 2)
来源：http://dali.shuidangran.top/Article/details/gtachwgwkm.html

[T13] Kotlin：只读 Map
来源：http://dali.jiagoushi.top/Article/details/gtmvfjkrkk.html

val m = mapOf("a" to 1)
来源：http://dali.316326.xyz/Article/details/gthqxoprix.html

[T14] Kotlin：循环
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmfpmqgah.html

for (i in 1..10) println(i)
来源：http://dali.pycfn.com/Article/details/gtnezmwsje.html

[T15] Kotlin：接口
来源：http://dali.shuidangran.top/Article/details/gttjdzhvwy.html

interface Shape { fun area(): Double }
来源：http://dali.meibo888.top/Article/details/gtqjzmtpxy.html

[T16] Swift：Hello World
来源：http://dali.feifeiyinyue.top/Article/details/gtpobjxmyq.html

print("Hello")
来源：http://dali.zhiwuduotai.top/Article/details/gtqpyxbrnx.html

[T17] Swift：变量与常量
来源：http://dali.bjfxy.top/Article/details/gtqoyhvpld.html

var a = 1;  let b = 2
来源：http://dali.hfpthk.cn/Article/details/gthhgbenku.html

[T18] Swift：字符串插值
来源：http://dali.zhongyouzk.top/Article/details/gtozcieqiv.html

"值: \(b)"
来源：http://dali.pycfn.com/Article/details/gtgwbqsikw.html

[T19] Swift：可选绑定
来源：http://dali.nwbrower.top/Article/details/gtucjdubgt.html

if let n = opt { print(n) }
来源：http://dali.zdqjudy.top/Article/details/gtijdgndsf.html

[T20] Swift：数组操作
来源：http://dali.zhengqikj.top/Article/details/gtmmvufoxm.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtutdqejxs.html

[T21] Swift：遍历
来源：http://dali.yanxiufei.cn/Article/details/gtxnmkuchp.html

for x in a { print(x) }
来源：http://dali.svipenyu.cn/Article/details/gtxawiyevu.html

[T22] Swift：字典
来源：http://dali.yueranfly.top/Article/details/gtgbbmpuoa.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.chenlongwang.top/Article/details/gtalthfygd.html

[T23] Swift：函数
来源：http://dali.svipenyu.cn/Article/details/gtdythwavz.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.yongpay.top/Article/details/gtbnqkxyad.html

[T24] Swift：闭包
来源：http://dali.vqdsnc.cn/Article/details/gthwxkchwg.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.jyoumei.cn/Article/details/gtptizfhra.html

[T25] Swift：结构体
来源：http://dali.jlsjyb.cn/Article/details/gtwmqokszw.html

struct P { var x: Int }
来源：http://dali.316326.xyz/Article/details/gtqfrzhmgy.html

[T26] Swift：类与重写
来源：http://dali.chenzaomai.com/Article/details/gtrsecctqn.html

class A: Base { override func f() {} }
来源：http://dali.hfpthk.cn/Article/details/gtpcqbghrg.html

[T27] Swift：错误处理
来源：http://dali.gzhubu.top/Article/details/gtauncjeel.html

do { try f() } catch { print(error) }
来源：http://dali.yueranfly.top/Article/details/gtgzxmcrgp.html

[T28] Swift：枚举
来源：http://dali.ybcxt.top/Article/details/gtzziydfvj.html

enum Color { case red, green }
来源：http://dali.cucudq.cn/Article/details/gtawkbhfhj.html

[T29] Swift：guard 提前返回
来源：http://dali.zhongyouzk.top/Article/details/gtveirmqjy.html

guard let x = opt else { return }
来源：http://dali.hnqzz.top/Article/details/gtecnldrxl.html

[T30] Swift：协议
来源：http://dali.yonumen.top/Article/details/gtmltvwrlt.html

protocol Shape { func area() -> Double }
来源：http://dali.haohaochexian.top/Article/details/gtrbfcmzhn.html

[T31] Lua：Hello World
来源：http://dali.smart0.xyz/Article/details/gtpjlmrqmg.html

print("Hello")
来源：http://dali.xylfe.cn/Article/details/gtrcjyufru.html

[T32] Lua：局部变量
来源：http://dali.svipenyu.cn/Article/details/gteeatzzyo.html

local a = 1
来源：http://dali.jiagoushi.top/Article/details/gthhtarkzv.html

[T33] Lua：表（数组）
来源：http://dali.yuanzhike.top/Article/details/gtlhggimja.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.vqdsnc.cn/Article/details/gtfviiqtic.html

[T34] Lua：遍历表
来源：http://dali.yuxming.cn/Article/details/gtjtmofhyv.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.jqgfzy.top/Article/details/gtjhstjamn.html

[T35] Lua：字典表
来源：http://dali.feifeiyinyue.top/Article/details/gtxamaeotp.html

local d = { a = 1 };  d.b = 2
来源：http://dali.sweek.top/Article/details/gtgvbyrwax.html

[T36] Lua：函数
来源：http://dali.hysaishi.cn/Article/details/gtuejfddfm.html

function add(a, b) return a + b end
来源：http://dali.xuetiantiany.cn/Article/details/gtdvuqepof.html

[T37] Lua：字符串拼接
来源：http://dali.yvedp.cn/Article/details/gtpzmcvots.html

"a" .. "b"
来源：http://dali.nwbrower.top/Article/details/gtqnawoune.html

[T38] Lua：条件
来源：http://dali.yj20258.top/Article/details/gtpjwdniqm.html

if x > 0 then print("正") end
来源：http://dali.shzxlz.cn/Article/details/gtqzxiwixn.html

[T39] Lua：模式匹配
来源：http://dali.sufxvd.cn/Article/details/gtmvphmlge.html

string.find(s, "%d+")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxyvlyziq.html

[T40] Lua：元表
来源：http://dali.hnxiangtu.top/Article/details/gtyniuqsqi.html

setmetatable({}, { __index = base })
来源：http://dali.gotoacloud.top/Article/details/gtczcqbpqe.html

[T41] Perl：Hello World
来源：http://dali.vqdsnc.cn/Article/details/gtsetanzqu.html

print "Hello\n";
来源：http://dali.ppjwa.cn/Article/details/gtfkmchigp.html

[T42] Perl：变量类型
来源：http://dali.ppjwa.cn/Article/details/gtfbiimehu.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.vqdsnc.cn/Article/details/gtvayadalo.html

[T43] Perl：字符串插值
来源：http://dali.jiagoushi.top/Article/details/gtlfbqlpai.html

"值: $a"
来源：http://dali.jianghu66.top/Article/details/gtelkqdxcc.html

[T44] Perl：条件
来源：http://dali.yongpay.top/Article/details/gttzwsqwwa.html

if ($a > 0) { print "正"; }
来源：http://dali.sysykeji.top/Article/details/gtvhssitme.html

[T45] Perl：数组遍历
来源：http://dali.xziqi.cn/Article/details/gtetryauxz.html

for my $x (@arr) { print $x; }
来源：http://dali.jqgufenzy.top/Article/details/gtkxvnoktq.html

[T46] Perl：哈希操作
来源：http://dali.jqgufenzy.top/Article/details/gttxzekhuu.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.jinqigfzy.top/Article/details/gthzadmiex.html

[T47] Perl：正则捕获
来源：http://dali.zhengqikj.top/Article/details/gteepozgau.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.cashguo.top/Article/details/gtzdjoekii.html

[T48] Perl：正则替换
来源：http://dali.hongshengwenyu.top/Article/details/gtuflrlwrx.html

$s =~ s/old/new/g;
来源：http://dali.aibaodan.cn/Article/details/gtwznjcvse.html


<!-- 参考信息 -->