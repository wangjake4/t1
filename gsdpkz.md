代发 wailian999

sed -i 's/foo/bar/g' a.txt
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnwszdojs.html

[R48] awk 取指定列
来源：http://dali.nwbrower.top/Article/details/gttumsgbwm.html

awk '{print $1, $3}' a.txt
来源：http://dali.yonumen.top/Article/details/gtvoarlitb.html

[R49] awk 带条件
来源：http://dali.316326.xyz/Article/details/gtvvtblobb.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.xuetiantiany.cn/Article/details/gtbwxcfexa.html

[R50] awk 求和
来源：http://dali.birdmap.top/Article/details/gtifyxqplu.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.jinqigufen.top/Article/details/gtatyhcbqh.html

[R51] 排序去重取前几
来源：http://dali.nanxuanxn.top/Article/details/gtfhcipqtg.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.yuanzhike.top/Article/details/gteeybqsyp.html

[R52] 统计行数
来源：http://dali.zycfv.cn/Article/details/gtkuomnydh.html

wc -l a.txt
来源：http://dali.zycfv.cn/Article/details/gtzgsajdvk.html

[R53] 查看文件头与实时尾
来源：http://dali.cashguo.top/Article/details/gtllkldxss.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.ehwqpu.com/Article/details/gtexsolrhk.html

[R54] 比较两个文件
来源：http://dali.sysykeji.top/Article/details/gtnspwgrzi.html

diff a.txt b.txt
来源：http://dali.nanxinkj.top/Article/details/gtocbheavp.html

[R55] 压缩与解压
来源：http://dali.tian-w.cn/Article/details/gtsnwdaxzq.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.hongshengwenyu.top/Article/details/gtmaiaojse.html

[R56] 远程拷贝
来源：http://dali.havefunace.top/Article/details/gtdyhmknjd.html

scp file user@host:/path/
来源：http://dali.svipenyu.cn/Article/details/gtxlwkaifp.html

[R57] 远程执行命令
来源：http://dali.jlsjyb.cn/Article/details/gtjneulibb.html

ssh user@host 'uptime'
来源：http://dali.yongpay.top/Article/details/gtzpiiikde.html

[R58] 下载文件
来源：http://dali.sxryk.cn/Article/details/gtjwcjbbly.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.sufxvd.cn/Article/details/gtnscbndrn.html

[R59] 发 POST JSON
来源：http://dali.gzhubu.top/Article/details/gtkdnsgusn.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.daxiang520.top/Article/details/gtymhjtdez.html

[R60] 只看 HTTP 状态码
来源：http://dali.shanyushiyangtech.top/Article/details/gtkdeppdxn.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.cqqwz.cn/Article/details/gtaioklzdc.html

[R61] 磁盘占用
来源：http://dali.jinyuanbaomall.cn/Article/details/gtojzagdsm.html

df -h;  du -sh *
来源：http://dali.haohaochexian.top/Article/details/gtndjknzwz.html

[R62] 找最占空间的文件
来源：http://dali.daria6918.cn/Article/details/gtziyihqzn.html

du -ah . | sort -rh | head -10
来源：http://dali.sufxvd.cn/Article/details/gtgmwrcgzm.html

[R63] 内存与进程
来源：http://dali.xuanzx.com/Article/details/gtuctcmjlf.html

free -h;  ps aux | grep nginx
来源：http://dali.sweek.top/Article/details/gtnnzbxzzm.html

[R64] 结束进程
来源：http://dali.chenzaomai.com/Article/details/gtnzdldggl.html

kill -9 $(pgrep -f app.py)
来源：http://dali.yongpay.top/Article/details/gtiirdsopg.html

[R65] 查看端口占用
来源：http://dali.xinyue.icu/Article/details/gtspgoxqlh.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.nwbrower.top/Article/details/gtilyexvdh.html

[R66] 定时任务
来源：http://dali.sysykeji.top/Article/details/gtquqvebsn.html

crontab -e;  crontab -l
来源：http://dali.snrcjt.cn/Article/details/gtyyhecnsb.html

[R67] 生成随机十六进制串
来源：http://dali.nanxuanxn.top/Article/details/gtzobceolu.html

openssl rand -hex 16
来源：http://dali.gaohongyu789.top/Article/details/gthncdpwwy.html

[R68] 计算文件校验值
来源：http://dali.yuxming.cn/Article/details/gtskuffoko.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.kuanghao11.cn/Article/details/gtoajlnbrl.html

[R69] 生成随机密码
来源：http://dali.shuidangran.top/Article/details/gtfmlzpvyp.html

head -c 16 /dev/urandom | base64
来源：http://dali.sysykeji.top/Article/details/gtelacldyl.html

[R70] 时间戳与互转
来源：http://dali.nanxinkj.top/Article/details/gteacuyulx.html

date +%s;  date -d @1700000000
来源：http://dali.pengpengdd.cyou/Article/details/gtkjalhfhx.html

[R71] 日期格式化
来源：http://dali.9152youxi.cn/Article/details/gtyhzviomi.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.wangshuangyany.cn/Article/details/gtccrojtmv.html

[R72] 等待端口就绪
来源：http://dali.smart0.xyz/Article/details/gteeeevoyf.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.jyoumei.cn/Article/details/gtkqkucobe.html

[R73] 分割大日志
来源：http://dali.dianchejie.cn/Article/details/gtgafhwxzn.html

split -l 1000 big.log part_
来源：http://dali.gaohongyu789.top/Article/details/gtczgfepdx.html

[R74] 批量重命名
来源：http://dali.kuanghao11.cn/Article/details/gtbytuyvxf.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.sxryk.cn/Article/details/gtqiibxssv.html

[R75] 导出环境变量
来源：http://dali.hammf.cn/Article/details/gtsfapqyen.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.kuanghao11.cn/Article/details/gtmqlkofjb.html

[R76] 使用临时文件
来源：http://dali.xylfe.cn/Article/details/gtykrvomba.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.hnqzz.top/Article/details/gtxsinrlzg.html

[R77] 读取用户输入
来源：http://dali.cheryme.top/Article/details/gtgstirxlm.html

read -rp "请输入: " ans
来源：http://dali.yonumen.top/Article/details/gtrmgxvsmu.html

[R78] 交互式菜单
来源：http://dali.shangyingyoupin.top/Article/details/gtzzbbqbrt.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.nwbrower.top/Article/details/gtzhtmxpvt.html

[R79] 解析命令行选项
来源：http://dali.xuetiantiany.cn/Article/details/gtfgqtrbzm.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.tanke756.top/Article/details/gtndhqlegz.html

[R80] 查看脚本执行耗时
来源：http://dali.fengsongda.top/Article/details/gtvknurmue.html

time ./run.sh
来源：http://dali.cashguo.top/Article/details/gtqdlpxalp.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtigehyjvf.html

S. C / C++ 专题
来源：http://dali.zhengqikj.top/Article/details/gttinbvinz.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtyhwjslmh.html

[S01] C：Hello World
来源：http://dali.hnqzz.top/Article/details/gtsrsjwbdv.html

#include <stdio.h>
来源：http://dali.dashuyun.cn/Article/details/gtnnbcyord.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.bjfxy.top/Article/details/gtcfretjnj.html

[S02] C：变量与格式化输出
来源：http://dali.jinqigufen.top/Article/details/gtzpiahzan.html

int a = 10; printf("%d\n", a);
来源：http://dali.xuetiantiany.cn/Article/details/gtxsbkrfaj.html

[S03] C：读入整数
来源：http://dali.tanke756.top/Article/details/gtvfnzncue.html

int x; scanf("%d", &x);
来源：http://dali.zhongyouzk.top/Article/details/gtudxiopqw.html

[S04] C：字符串复制
来源：http://dali.shanyushiyangkeji.top/Article/details/gtofswbwxx.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.yvedp.cn/Article/details/gteuswqtxt.html

[S05] C：字符串长度
来源：http://dali.tianlin.xyz/Article/details/gteyilalxs.html

strlen(s)
来源：http://dali.jinqigfzy.top/Article/details/gtfhbbxwpz.html

[S06] C：字符串比较
来源：http://dali.zhongyouzk.top/Article/details/gtgnktngpf.html

strcmp(a, b) == 0
来源：http://dali.daria6918.cn/Article/details/gtzxiftyry.html

[S07] C：数组遍历求和
来源：http://dali.gaohongyu789.top/Article/details/gtebwztgnu.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.bjfxy.top/Article/details/gtmitpeksk.html

[S08] C：动态内存分配与释放
来源：http://dali.svipenyu.cn/Article/details/gtzftjwlvo.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.dashuyun.cn/Article/details/gtstzdysgi.html

[S09] C：结构体定义与初始化
来源：http://dali.meibo888.top/Article/details/gtiahoizgd.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqtlkzwyp.html

[S10] C：指针与解引用
来源：http://dali.daria6918.cn/Article/details/gtugylvzrd.html

int *p = &a;  *p = 5;
来源：http://dali.jinqigufen.top/Article/details/gtrytihikj.html

[S11] C：逐行读文件
来源：http://dali.hongshengwenyu.top/Article/details/gtrodowxqd.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gtkwyksrnh.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhengqikj.top/Article/details/gtdqivpchj.html

fclose(f);
来源：http://dali.cheryme.top/Article/details/gtchprvyav.html

[S12] C：写文件
来源：http://dali.haohaochexian.top/Article/details/gtkmxdevvq.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.jinqigufen.top/Article/details/gtqxeurvka.html

[S13] C：宏定义
来源：http://dali.quarkkingdee.top/Article/details/gtgsuyrmbg.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.cheryme.top/Article/details/gtiebittkk.html

[S14] C：枚举
来源：http://dali.yanxiufei.cn/Article/details/gtavfomltf.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.yvedp.cn/Article/details/gtbkxzmmns.html

[S15] C：类型转换
来源：http://dali.gaohongyu789.top/Article/details/gtldplckjj.html

(double) a / b
来源：http://dali.nwbrower.top/Article/details/gtmvibtdub.html

[S16] C：位操作置位
来源：http://dali.pycfn.com/Article/details/gtmpxinutj.html

x |= (1 << 3);
来源：http://dali.ppjwa.cn/Article/details/gtkiqsyhvj.html

[S17] C：安全拼接字符串
来源：http://dali.ehwqpu.com/Article/details/gtrefifpjt.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.xuetiantiany.cn/Article/details/gtsxsiodrq.html

[S18] C：命令行参数
来源：http://dali.jinqigfzy.top/Article/details/gtirxvtsxx.html

int main(int argc, char **argv)
来源：http://dali.jlsjyb.cn/Article/details/gttmkomsnl.html

[S19] C：快速排序
来源：http://dali.yvedp.cn/Article/details/gteogtpxtj.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.nwbrower.top/Article/details/gtooechtdt.html

[S20] C：二分查找
来源：http://dali.vqdsnc.cn/Article/details/gtkteafpdx.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.yj20258.top/Article/details/gtivmpsdkn.html

[S21] C：字符类别判断
来源：http://dali.gzhubu.top/Article/details/gtmsizlhzl.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.cqqwz.cn/Article/details/gtfwhxlmri.html

[S22] C：字符串转数字
来源：http://dali.chenjidiqi.icu/Article/details/gtgwqjmhuc.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.hongshengwenyu.top/Article/details/gtxfcntypg.html

[S23] C：随机数
来源：http://dali.wangshuangyany.cn/Article/details/gterzxnfnk.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.yongpay.top/Article/details/gtuomqlbwa.html

[S24] C：获取本地时间
来源：http://dali.andypj.xyz/Article/details/gtalkvbvjs.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.redwolf501.top/Article/details/gtbqpwfagc.html

[S25] C：内存拷贝
来源：http://dali.zdqjudy.top/Article/details/gtguavjkmd.html

memcpy(dst, src, n);
来源：http://dali.yanxiufei.cn/Article/details/gtysidroer.html

[S26] C：内存清零
来源：http://dali.redwolf501.top/Article/details/gtbjkiiweo.html

memset(a, 0, sizeof a);
来源：http://dali.hongshengwenyu.top/Article/details/gtqzzktqgp.html

[S27] C：定义常量
来源：http://dali.shanyushiyangtech.top/Article/details/gtegfaueho.html

const double PI = 3.14159;
来源：http://dali.snrcjt.cn/Article/details/gtpsyhyctr.html

[S28] C：静态变量
来源：http://dali.pycfn.com/Article/details/gtwbpjczpl.html

static int counter = 0;
来源：http://dali.316326.xyz/Article/details/gtpgtdijja.html

[S29] C：变参函数
来源：http://dali.sxryk.cn/Article/details/gtdyrfkqva.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfrpyyiqs.html

[S30] C：头文件保护
来源：http://dali.sweek.top/Article/details/gtfvptywdk.html

#ifndef X_H
来源：http://dali.sysykeji.top/Article/details/gtoqzbvlhh.html

#define X_H
来源：http://dali.xinyue.icu/Article/details/gtefozneds.html

#endif
来源：http://dali.jinqigfzy.top/Article/details/gtojskgcda.html

[S31] C++：Hello World
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiktzpgjh.html

#include <iostream>
来源：http://dali.yj20258888.top/Article/details/gtyftppiqr.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.cheryme.top/Article/details/gtzukbsouq.html

[S32] C++：字符串
来源：http://dali.xylfe.cn/Article/details/gtzjspgxgv.html

std::string s = "hi";  s += "!";
来源：http://dali.svipenyu.cn/Article/details/gtbltpfaqz.html

[S33] C++：vector 增删
来源：http://dali.yj20258.top/Article/details/gtnlciwizq.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.chenlongwang.top/Article/details/gtcvvxtvnq.html

[S34] C++：遍历 vector
来源：http://dali.guannengcc.top/Article/details/gtkfddheoi.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.yuanzhike.top/Article/details/gtzmxhpmfb.html

[S35] C++：map
来源：http://dali.jqgfzy.top/Article/details/gthltpugrz.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hongshengwenyu.top/Article/details/gtuoetrorp.html

[S36] C++：unordered_map
来源：http://dali.ppjwa.cn/Article/details/gtlmnfqdlb.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gtvcsyucnd.html

[S37] C++：set
来源：http://dali.meibo888.top/Article/details/gtkvazvikm.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhengqikj.top/Article/details/gtovaahgxh.html

[S38] C++：排序
来源：http://dali.hnqzz.top/Article/details/gtlcrfprlb.html

std::sort(v.begin(), v.end());
来源：http://dali.zhixingplan.top/Article/details/gtpqiymjul.html

[S39] C++：自定义比较器排序
来源：http://dali.hnqzz.top/Article/details/gtygbbyfaf.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttfarococ.html

[S40] C++：查找元素
来源：http://dali.yangfankeji.com/Article/details/gtwycdggbv.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.haohaochexian.top/Article/details/gtjorrdsrz.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gtynkfmseu.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.sysykeji.top/Article/details/gtvyfzzbtn.html

[S42] C++：继承与虚函数
来源：http://dali.hywenlv.cn/Article/details/gtukginfun.html

class B : public Base { public: void f() override {} };
来源：http://dali.yuanzhike.top/Article/details/gtcyaizfba.html

[S43] C++：智能指针
来源：http://dali.chenjidiqi.icu/Article/details/gtsdbzydhq.html

auto p = std::make_unique<int>(5);
来源：http://dali.feifeiyinyue.top/Article/details/gtbhiouurp.html

[S44] C++：引用传参
来源：http://dali.jianghu66.top/Article/details/gttlpevtzf.html

void inc(int &x) { ++x; }
来源：http://dali.yueranfly.top/Article/details/gtocufvqht.html

[S45] C++：lambda
来源：http://dali.aizwys.cn/Article/details/gtwviylgku.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.yanxiufei.cn/Article/details/gtsaskhvnx.html

[S46] C++：函数模板
来源：http://dali.vqdsnc.cn/Article/details/gtrsuwyeca.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.yongpay.top/Article/details/gtitvhdxjb.html

[S47] C++：结构化绑定遍历
来源：http://dali.fzhhl.top/Article/details/gtuarayann.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.mhx1999.top/Article/details/gtwqplwhun.html

[S48] C++：逐行读文件
来源：http://dali.daxiang520.top/Article/details/gtfntrkrgt.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.chenzaomai.com/Article/details/gtubzwkock.html

while (std::getline(in, line)) { }
来源：http://dali.xuetiantiany.cn/Article/details/gtnesxrkgz.html

[S49] C++：写文件
来源：http://dali.hnxiangtu.top/Article/details/gtfkzdkrgw.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.jqgufenzy.top/Article/details/gtizlnyqxx.html

[S50] C++：格式化数字
来源：http://dali.tian-w.cn/Article/details/gtmdqerkuq.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.tanke756.top/Article/details/gthiefkdpf.html

[S51] C++：显式类型转换
来源：http://dali.birdmap.top/Article/details/gthrcvoeig.html

static_cast<double>(a) / b
来源：http://dali.nanxinkj.top/Article/details/gtyynueghj.html

[S52] C++：const 与 noexcept
来源：http://dali.sweek.top/Article/details/gtogbcjxxy.html

int size() const noexcept { return n_; }
来源：http://dali.pycfn.com/Article/details/gttjzeeubs.html

[S53] C++：移动语义
来源：http://dali.havefunace.top/Article/details/gtyjctuixj.html

std::vector<int> w = std::move(v);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzipoetbx.html

[S54] C++：异常处理
来源：http://dali.nanxinkj.top/Article/details/gtczfjqktp.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.ybcxt.top/Article/details/gtshgnbqlz.html

[S55] C++：结构化绑定
来源：http://dali.mhx1999.top/Article/details/gtmydphwkn.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.gotoacloud.top/Article/details/gtgwszvead.html

[S56] C++：optional
来源：http://dali.aizwys.cn/Article/details/gtfekgxrhe.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yj20258888.top/Article/details/gtsvmtyzrd.html

[S57] C++：编译期常量
来源：http://dali.sxryk.cn/Article/details/gtbwfdjdfe.html

constexpr int N = 10;
来源：http://dali.ybcxt.top/Article/details/gtvidjxttl.html

[S58] C++：命名空间
来源：http://dali.zycfv.cn/Article/details/gtzuezumqx.html

namespace ns { int f() { return 1; } }
来源：http://dali.xylfe.cn/Article/details/gtpopiylev.html

[S59] C++：静态断言
来源：http://dali.xylfe.cn/Article/details/gtasnbhhqg.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.andypj.xyz/Article/details/gtobebsvcr.html

[S60] C++：遍历并删除元素
来源：http://dali.hnxiangtu.top/Article/details/gtjpitomcf.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.ydzc1.top/Article/details/gtrmzsaull.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtrkenumcy.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.daxiang520.top/Article/details/gtdspdipnc.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtaefjrgkt.html

[T01] Kotlin：Hello World
来源：http://dali.sufxvd.cn/Article/details/gtxadwevwc.html

println("Hello")
来源：http://dali.yvedp.cn/Article/details/gtlohytxne.html

[T02] Kotlin：变量
来源：http://dali.quarkkingdee.top/Article/details/gtsxwborup.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.xuetiantiany.cn/Article/details/gthrgkcxdk.html

[T03] Kotlin：字符串模板
来源：http://dali.xuanzx.com/Article/details/gtlakxmdkp.html

"值: $b"
来源：http://dali.shzxlz.cn/Article/details/gtptacnpdk.html

[T04] Kotlin：空安全
来源：http://dali.hfpthk.cn/Article/details/gtltjjmyru.html

val n: String? = null;  n?.length
来源：http://dali.ppjwa.cn/Article/details/gthueefjgd.html

[T05] Kotlin：when 表达式
来源：http://dali.ybcxt.top/Article/details/gtdiqtkquo.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.jianghu66.top/Article/details/gtmsddninw.html

[T06] Kotlin：集合映射
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtofqlybaq.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.ehwqpu.com/Article/details/gtrvbsinhn.html

[T07] Kotlin：集合过滤
来源：http://dali.yj202588.top/Article/details/gtvgrddfhb.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.hywenlv.cn/Article/details/gtnxoffwvs.html

[T08] Kotlin：数据类
来源：http://dali.jqgfzy.top/Article/details/gtnybvtrov.html

data class User(val name: String, val age: Int)
来源：http://dali.meibo888.top/Article/details/gtrwluaswn.html

[T09] Kotlin：扩展函数
来源：http://dali.hnqzz.top/Article/details/gtjnqcgowv.html

fun String.exclaim() = this + "!"
来源：http://dali.jqgfzy.top/Article/details/gtsjxxfydb.html

[T10] Kotlin：默认参数
来源：http://dali.cheryme.top/Article/details/gtlmmelatd.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.jiagoushi.top/Article/details/gticancqmt.html

[T11] Kotlin：协程
来源：http://dali.zhaomingkeji.xyz/Article/details/gteyrmjjnu.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.hammf.cn/Article/details/gthukperhd.html

[T12] Kotlin：解构声明
来源：http://dali.fzhhl.top/Article/details/gtdtkyissy.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhongyouzk.top/Article/details/gtbwtppxrw.html

[T13] Kotlin：只读 Map
来源：http://dali.zhixingplan.top/Article/details/gtgpjixhja.html

val m = mapOf("a" to 1)
来源：http://dali.zycfv.cn/Article/details/gtvyfdovpl.html

[T14] Kotlin：循环
来源：http://dali.guowangkeji.top/Article/details/gturrraqgt.html

for (i in 1..10) println(i)
来源：http://dali.hnqzz.top/Article/details/gthkfgxadj.html

[T15] Kotlin：接口
来源：http://dali.yangfankeji.com/Article/details/gtdlbgmzyp.html

interface Shape { fun area(): Double }
来源：http://dali.yj20258888.top/Article/details/gtoafucqfc.html

[T16] Swift：Hello World
来源：http://dali.birdmap.top/Article/details/gtcljdqgjd.html

print("Hello")
来源：http://dali.nanxuanxn.top/Article/details/gtsmyqmoui.html

[T17] Swift：变量与常量
来源：http://dali.yj20258.top/Article/details/gtutjvmwvb.html

var a = 1;  let b = 2
来源：http://dali.ehwqpu.com/Article/details/gtkkolofbd.html

[T18] Swift：字符串插值
来源：http://dali.ydzc1.top/Article/details/gtlkfvsziy.html

"值: \(b)"
来源：http://dali.aizwys.cn/Article/details/gtzlpwlqxf.html

[T19] Swift：可选绑定
来源：http://dali.guannengcc.top/Article/details/gtlpsszvqb.html

if let n = opt { print(n) }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgqdfcmmx.html

[T20] Swift：数组操作
来源：http://dali.c1oappe.top/Article/details/gtzzokruvt.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.nwbrower.top/Article/details/gtiiecypdm.html

[T21] Swift：遍历
来源：http://dali.jianghu66.top/Article/details/gtonecaqai.html

for x in a { print(x) }
来源：http://dali.daxiang520.top/Article/details/gtoqpkvoas.html

[T22] Swift：字典
来源：http://dali.snrcjt.cn/Article/details/gtcbqdhbfo.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.ppjwa.cn/Article/details/gtlpsgpkyb.html

[T23] Swift：函数
来源：http://dali.snrcjt.cn/Article/details/gtsovfmjdw.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.ybcxt.top/Article/details/gtgghmtldf.html

[T24] Swift：闭包
来源：http://dali.jianghu66.top/Article/details/gtiysswixt.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.gotoacloud.top/Article/details/gtptdnmzwp.html

[T25] Swift：结构体
来源：http://dali.hfpthk.cn/Article/details/gtgsvgaflq.html

struct P { var x: Int }
来源：http://dali.xuetiantiany.cn/Article/details/gtzpilrwtc.html

[T26] Swift：类与重写
来源：http://dali.fzhhl.top/Article/details/gtfhlexqbe.html

class A: Base { override func f() {} }
来源：http://dali.ehwqpu.com/Article/details/gtdyustvhe.html

[T27] Swift：错误处理
来源：http://dali.xinyue.icu/Article/details/gtpwxrfnhs.html

do { try f() } catch { print(error) }
来源：http://dali.gotoacloud.top/Article/details/gtjcprceow.html

[T28] Swift：枚举
来源：http://dali.ybcxt.top/Article/details/gttnlrvvxx.html

enum Color { case red, green }
来源：http://dali.jlsjyb.cn/Article/details/gtcitggotk.html

[T29] Swift：guard 提前返回
来源：http://dali.316326.xyz/Article/details/gtxxixcuyo.html

guard let x = opt else { return }
来源：http://dali.zhengqikj.top/Article/details/gtizbyqqmu.html

[T30] Swift：协议
来源：http://dali.ivvv.top/Article/details/gtunckvniy.html

protocol Shape { func area() -> Double }
来源：http://dali.shangyingyoupin.top/Article/details/gtwsborixz.html

[T31] Lua：Hello World
来源：http://dali.9152youxi.cn/Article/details/gtbfgcfroq.html

print("Hello")
来源：http://dali.yvedp.cn/Article/details/gthezbincm.html

[T32] Lua：局部变量
来源：http://dali.zdqjudy.top/Article/details/gtadihwgee.html

local a = 1
来源：http://dali.nwbrower.top/Article/details/gtsyytbzmd.html

[T33] Lua：表（数组）
来源：http://dali.tianlin.xyz/Article/details/gtkcpvensc.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.cheryme.top/Article/details/gtowrwemgm.html

[T34] Lua：遍历表
来源：http://dali.nwbrower.top/Article/details/gtwtewohgb.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.xinyue.icu/Article/details/gtnnxzkhwr.html

[T35] Lua：字典表
来源：http://dali.yuxming.cn/Article/details/gtzpvooxbt.html

local d = { a = 1 };  d.b = 2
来源：http://dali.shuidangran.top/Article/details/gtomqhawpf.html

[T36] Lua：函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuynaofqo.html

function add(a, b) return a + b end
来源：http://dali.kuanghao11.cn/Article/details/gtldpwzndr.html

[T37] Lua：字符串拼接
来源：http://dali.svipenyu.cn/Article/details/gtsdjexnpc.html

"a" .. "b"
来源：http://dali.yj20258888.top/Article/details/gtyykxtmmi.html

[T38] Lua：条件
来源：http://dali.cheryme.top/Article/details/gtglumwvvk.html

if x > 0 then print("正") end
来源：http://dali.chenlongwang.top/Article/details/gtnkdyqyuo.html

[T39] Lua：模式匹配
来源：http://dali.ybcxt.top/Article/details/gthhmlofec.html

string.find(s, "%d+")
来源：http://dali.feifeiyinyue.top/Article/details/gtxzawlguy.html

[T40] Lua：元表
来源：http://dali.svipenyu.cn/Article/details/gtyecgjojr.html

setmetatable({}, { __index = base })
来源：http://dali.wangshuangyany.cn/Article/details/gtsfftfpms.html

[T41] Perl：Hello World
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsswhnkxi.html

print "Hello\n";
来源：http://dali.snrcjt.cn/Article/details/gtqdibmncl.html

[T42] Perl：变量类型
来源：http://dali.sxryk.cn/Article/details/gtjvagtnzx.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.hywenlv.cn/Article/details/gtwjattlri.html

[T43] Perl：字符串插值
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvyafygdr.html

"值: $a"
来源：http://dali.tian-w.cn/Article/details/gtbguvjdlj.html

[T44] Perl：条件
来源：http://dali.sufxvd.cn/Article/details/gtmlgsydhz.html

if ($a > 0) { print "正"; }
来源：http://dali.sxryk.cn/Article/details/gtdgudqdhn.html

[T45] Perl：数组遍历
来源：http://dali.yj20258.top/Article/details/gtcmxlhxvd.html

for my $x (@arr) { print $x; }
来源：http://dali.jiagoushi.top/Article/details/gtkipzjkpt.html

[T46] Perl：哈希操作
来源：http://dali.nanxuanxn.top/Article/details/gtnstrphom.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.pycfn.com/Article/details/gtngaggnji.html

[T47] Perl：正则捕获
来源：http://dali.guowangkeji.top/Article/details/gtcpjxoist.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.ivvv.top/Article/details/gtwghxhska.html

[T48] Perl：正则替换
来源：http://dali.mhx1999.top/Article/details/gthqkddfql.html

$s =~ s/old/new/g;
来源：http://dali.hysaishi.cn/Article/details/gtnpruawbm.html

[T49] Perl：函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtehlqucid.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.ydzc1.top/Article/details/gtmpgwyaty.html

[T50] Perl：逐行读文件
来源：http://dali.cqqwz.cn/Article/details/gtzkmrwcah.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.birdmap.top/Article/details/gtdbaukkzu.html


<!-- 参考信息 -->