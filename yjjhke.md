代发 wailian999

find . -name "*.tmp" -delete
来源：http://dali.shuidangran.top/Article/details/gtvpzyiljb.html

[R46] 递归替换文件内容
来源：http://dali.hfpthk.cn/Article/details/gthpatsbzu.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.yanxiufei.cn/Article/details/gtgtyculwk.html

[R47] sed 单行替换
来源：http://dali.wangshuangyany.cn/Article/details/gtrldnmanh.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.chenzaomai.com/Article/details/gtrddpinqg.html

[R48] awk 取指定列
来源：http://dali.hnxiangtu.top/Article/details/gtardjrmxf.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhengqikj.top/Article/details/gtsbnaezml.html

[R49] awk 带条件
来源：http://dali.gotoacloud.top/Article/details/gtnkswwasw.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.pengpengdd.cyou/Article/details/gthiyplhqq.html

[R50] awk 求和
来源：http://dali.chenjidiqi.icu/Article/details/gtstwjhezs.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.nanxuanxn.top/Article/details/gtkjceysag.html

[R51] 排序去重取前几
来源：http://dali.quarkkingdee.top/Article/details/gtzgvqnxjy.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.cheryme.top/Article/details/gtoewqdymj.html

[R52] 统计行数
来源：http://dali.fengsongda.top/Article/details/gtyvsbuopc.html

wc -l a.txt
来源：http://dali.birdmap.top/Article/details/gttdhsovqn.html

[R53] 查看文件头与实时尾
来源：http://dali.hywenlv.cn/Article/details/gtrvxbexpi.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.sweek.top/Article/details/gtnntfwprh.html

[R54] 比较两个文件
来源：http://dali.cdnleiting.top/Article/details/gtbvemwvwe.html

diff a.txt b.txt
来源：http://dali.feifeiyinyue.top/Article/details/gtwnctngyy.html

[R55] 压缩与解压
来源：http://dali.xuanzx.com/Article/details/gtuxfzzbhp.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.feifeiyinyue.top/Article/details/gtoiadruvx.html

[R56] 远程拷贝
来源：http://dali.zhiwuduotai.top/Article/details/gtnyvhobqx.html

scp file user@host:/path/
来源：http://dali.ehwqpu.com/Article/details/gtvqrktpkv.html

[R57] 远程执行命令
来源：http://dali.pengpengdd.cyou/Article/details/gtuiyfxvjn.html

ssh user@host 'uptime'
来源：http://dali.gotoacloud.top/Article/details/gtnoljmwzw.html

[R58] 下载文件
来源：http://dali.pengpengdd.cyou/Article/details/gtfkpqmoew.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.cheryme.top/Article/details/gtivkvnkcc.html

[R59] 发 POST JSON
来源：http://dali.dashuyun.cn/Article/details/gtpapsiame.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.jiagoushi.top/Article/details/gtgybjjdyj.html

[R60] 只看 HTTP 状态码
来源：http://dali.nwbrower.top/Article/details/gtrqybliff.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.xinyue.icu/Article/details/gtwregmkuq.html

[R61] 磁盘占用
来源：http://dali.jinqigfzy.top/Article/details/gtymgvwril.html

df -h;  du -sh *
来源：http://dali.cdnleiting.top/Article/details/gtgsjgnqwm.html

[R62] 找最占空间的文件
来源：http://dali.daria6918.cn/Article/details/gteakjmugo.html

du -ah . | sort -rh | head -10
来源：http://dali.hammf.cn/Article/details/gtarabiogy.html

[R63] 内存与进程
来源：http://dali.ivvv.top/Article/details/gtymmydaex.html

free -h;  ps aux | grep nginx
来源：http://dali.pycfn.com/Article/details/gtnyzjfdzt.html

[R64] 结束进程
来源：http://dali.c1oappe.top/Article/details/gtkavyamml.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gtroljhcvk.html

[R65] 查看端口占用
来源：http://dali.guannengcc.top/Article/details/gtybkilcje.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.jqgfzy.top/Article/details/gtinphfegi.html

[R66] 定时任务
来源：http://dali.ydzc1.top/Article/details/gtdbmifkmn.html

crontab -e;  crontab -l
来源：http://dali.yueranfly.top/Article/details/gtkhupuasy.html

[R67] 生成随机十六进制串
来源：http://dali.yueranfly.top/Article/details/gtxotxklsh.html

openssl rand -hex 16
来源：http://dali.sufxvd.cn/Article/details/gtqnrfrtkx.html

[R68] 计算文件校验值
来源：http://dali.yongpay.top/Article/details/gtuzuddkkh.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.gzhubu.top/Article/details/gtextahmjc.html

[R69] 生成随机密码
来源：http://dali.cqqwz.cn/Article/details/gtkqtqdzsn.html

head -c 16 /dev/urandom | base64
来源：http://dali.havefunace.top/Article/details/gtoqnzgbkd.html

[R70] 时间戳与互转
来源：http://dali.chenlongwang.top/Article/details/gteqypwfbx.html

date +%s;  date -d @1700000000
来源：http://dali.chenzaomai.com/Article/details/gtecxgvgxh.html

[R71] 日期格式化
来源：http://dali.wangdashe.top/Article/details/gtxfeqwevi.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.yj20258888.top/Article/details/gtxibhgfud.html

[R72] 等待端口就绪
来源：http://dali.jinghuilouyu.cn/Article/details/gtcxgbcbvt.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.yanxiufei.cn/Article/details/gtrxwfrwwz.html

[R73] 分割大日志
来源：http://dali.hfpthk.cn/Article/details/gtspkelqpi.html

split -l 1000 big.log part_
来源：http://dali.ppjwa.cn/Article/details/gtanrqqbln.html

[R74] 批量重命名
来源：http://dali.yuanzhike.top/Article/details/gtlkeqtfoi.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.9152youxi.cn/Article/details/gtpesbtyzz.html

[R75] 导出环境变量
来源：http://dali.wangdashe.top/Article/details/gtkgcbpzjg.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.yonumen.top/Article/details/gtztnifure.html

[R76] 使用临时文件
来源：http://dali.hongshengwenyu.top/Article/details/gtkhiugvbi.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.jqgfzy.top/Article/details/gtowxsfejq.html

[R77] 读取用户输入
来源：http://dali.iojbl.cn/Article/details/gthglfvdkm.html

read -rp "请输入: " ans
来源：http://dali.kuanghao11.cn/Article/details/gtlpapuetu.html

[R78] 交互式菜单
来源：http://dali.vqdsnc.cn/Article/details/gtiwfqqnkr.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.dianchejie.cn/Article/details/gtctwtcioc.html

[R79] 解析命令行选项
来源：http://dali.ppjwa.cn/Article/details/gttzxkpnlu.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.fzhhl.top/Article/details/gtcycloddj.html

[R80] 查看脚本执行耗时
来源：http://dali.ivvv.top/Article/details/gtrannvxpt.html

time ./run.sh
来源：http://dali.pycfn.com/Article/details/gtpyadxjrz.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtkhmpqmuf.html

S. C / C++ 专题
来源：http://dali.cucudq.cn/Article/details/gtpqwvkrmz.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtcnxelrjj.html

[S01] C：Hello World
来源：http://dali.jqgufenzy.top/Article/details/gtmnxrzwsf.html

#include <stdio.h>
来源：http://dali.wangdashe.top/Article/details/gtjpifmirc.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.yj20258888.top/Article/details/gtuujsvtsx.html

[S02] C：变量与格式化输出
来源：http://dali.jinghuilouyu.cn/Article/details/gtojpsrkfv.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhengqikj.top/Article/details/gtihghhkpi.html

[S03] C：读入整数
来源：http://dali.shangyingyoupin.top/Article/details/gtajbopkql.html

int x; scanf("%d", &x);
来源：http://dali.cashguo.top/Article/details/gtmoytdhek.html

[S04] C：字符串复制
来源：http://dali.9152youxi.cn/Article/details/gthbnkjgqc.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zycfv.cn/Article/details/gtculldljp.html

[S05] C：字符串长度
来源：http://dali.zhiwuduotai.top/Article/details/gtsazjhkmy.html

strlen(s)
来源：http://dali.tianlin.xyz/Article/details/gtjrkiwnqi.html

[S06] C：字符串比较
来源：http://dali.smart0.xyz/Article/details/gtptrzdrjp.html

strcmp(a, b) == 0
来源：http://dali.ehwqpu.com/Article/details/gtlajycatx.html

[S07] C：数组遍历求和
来源：http://dali.jqgufenzy.top/Article/details/gtvgdvcczd.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.haohaochexian.top/Article/details/gtquyfqege.html

[S08] C：动态内存分配与释放
来源：http://dali.guannengcc.top/Article/details/gtrspjugoo.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.shanyushiyangtech.top/Article/details/gthktxoyba.html

[S09] C：结构体定义与初始化
来源：http://dali.cashguo.top/Article/details/gtinspdcco.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.hysaishi.cn/Article/details/gttgylftya.html

[S10] C：指针与解引用
来源：http://dali.meibo888.top/Article/details/gtmptuoywd.html

int *p = &a;  *p = 5;
来源：http://dali.0kj1m.cn/Article/details/gtqpzchjdu.html

[S11] C：逐行读文件
来源：http://dali.quarkkingdee.top/Article/details/gtdlzruphj.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.fengsongda.top/Article/details/gtjyecizwb.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhoulong.xyz/Article/details/gtciutltmf.html

fclose(f);
来源：http://dali.tianlin.xyz/Article/details/gtuuysjvjo.html

[S12] C：写文件
来源：http://dali.birdmap.top/Article/details/gtmzrxrose.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.gogol.net.cn/Article/details/gtoobelcth.html

[S13] C：宏定义
来源：http://dali.ywan-chungtsiang.top/Article/details/gtitfmbuoj.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.sufxvd.cn/Article/details/gtvitynsak.html

[S14] C：枚举
来源：http://dali.redwolf501.top/Article/details/gtaketwvmi.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gthclsiwzk.html

[S15] C：类型转换
来源：http://dali.xuetiantiany.cn/Article/details/gtfssuwqge.html

(double) a / b
来源：http://dali.yvedp.cn/Article/details/gtqcmzguhz.html

[S16] C：位操作置位
来源：http://dali.xuetiantiany.cn/Article/details/gtqbjpwpgj.html

x |= (1 << 3);
来源：http://dali.aibaodan.cn/Article/details/gtvgzszkqo.html

[S17] C：安全拼接字符串
来源：http://dali.zycfv.cn/Article/details/gtxdsmlwdd.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.gotoacloud.top/Article/details/gtcmwmauwy.html

[S18] C：命令行参数
来源：http://dali.chenlongwang.top/Article/details/gtjvrtylgq.html

int main(int argc, char **argv)
来源：http://dali.hnqzz.top/Article/details/gtdefcools.html

[S19] C：快速排序
来源：http://dali.xziqi.cn/Article/details/gthtjcxfkq.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.jlsjyb.cn/Article/details/gtyrvhbxns.html

[S20] C：二分查找
来源：http://dali.tianlin.xyz/Article/details/gtpwxkbgfq.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.gogol.net.cn/Article/details/gtiymglcnq.html

[S21] C：字符类别判断
来源：http://dali.xylfe.cn/Article/details/gtjipaomhi.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.bjfxy.top/Article/details/gtqdxltmoe.html

[S22] C：字符串转数字
来源：http://dali.jinghuilouyu.cn/Article/details/gtngdyhunr.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.snrcjt.cn/Article/details/gtqzhjqnzp.html

[S23] C：随机数
来源：http://dali.fzhhl.top/Article/details/gtqcvszenc.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.gaohongyu789.top/Article/details/gtrrshbhpt.html

[S24] C：获取本地时间
来源：http://dali.smart0.xyz/Article/details/gtrsawdrrc.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.hfpthk.cn/Article/details/gttdqgivqe.html

[S25] C：内存拷贝
来源：http://dali.chenzaomai.com/Article/details/gtqpgjvumk.html

memcpy(dst, src, n);
来源：http://dali.yuxming.cn/Article/details/gtysfvbdzj.html

[S26] C：内存清零
来源：http://dali.zdqjudy.top/Article/details/gtqvhtqzjb.html

memset(a, 0, sizeof a);
来源：http://dali.yuxming.cn/Article/details/gtpgphkzsj.html

[S27] C：定义常量
来源：http://dali.zhongyouzk.top/Article/details/gttbwjpfmd.html

const double PI = 3.14159;
来源：http://dali.jyoumei.cn/Article/details/gtzpvwxmvi.html

[S28] C：静态变量
来源：http://dali.jqgufenzy.top/Article/details/gteqpmlhoy.html

static int counter = 0;
来源：http://dali.316326.xyz/Article/details/gtxyiuwrbx.html

[S29] C：变参函数
来源：http://dali.sxryk.cn/Article/details/gtmgpeguml.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.sufxvd.cn/Article/details/gtkjankqfa.html

[S30] C：头文件保护
来源：http://dali.tian-w.cn/Article/details/gtaypiuyfn.html

#ifndef X_H
来源：http://dali.zhiwuduotai.top/Article/details/gtmsobeziy.html

#define X_H
来源：http://dali.hnxiangtu.top/Article/details/gtydhfpukf.html

#endif
来源：http://dali.yanxiufei.cn/Article/details/gtxzdvxfcz.html

[S31] C++：Hello World
来源：http://dali.chenlongwang.top/Article/details/gtjjyzzqiu.html

#include <iostream>
来源：http://dali.yangfankeji.com/Article/details/gtzlkqyhwh.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.shuidangran.top/Article/details/gtxighczaj.html

[S32] C++：字符串
来源：http://dali.hywenlv.cn/Article/details/gttedtxelx.html

std::string s = "hi";  s += "!";
来源：http://dali.chenzaomai.com/Article/details/gtslasjtse.html

[S33] C++：vector 增删
来源：http://dali.ehwqpu.com/Article/details/gtzdwrgqbv.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.jiagoushi.top/Article/details/gtgxhcbuxw.html

[S34] C++：遍历 vector
来源：http://dali.cucudq.cn/Article/details/gtgkkvssdd.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.havefunace.top/Article/details/gtcemobyvv.html

[S35] C++：map
来源：http://dali.bjfxy.top/Article/details/gtndjhyjvq.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.316326.xyz/Article/details/gtppvatqpt.html

[S36] C++：unordered_map
来源：http://dali.hnxiangtu.top/Article/details/gtulzeblwk.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.gotoacloud.top/Article/details/gtwglaljqo.html

[S37] C++：set
来源：http://dali.havefunace.top/Article/details/gtwosiaxis.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.daria6918.cn/Article/details/gtjluajohi.html

[S38] C++：排序
来源：http://dali.jyoumei.cn/Article/details/gtwrnrvady.html

std::sort(v.begin(), v.end());
来源：http://dali.jinghuilouyu.cn/Article/details/gttvmptjaz.html

[S39] C++：自定义比较器排序
来源：http://dali.daria6918.cn/Article/details/gtwtszompu.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.meibo888.top/Article/details/gthccdwvuy.html

[S40] C++：查找元素
来源：http://dali.xuetiantiany.cn/Article/details/gtrelmgfsg.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhengqikj.top/Article/details/gtlfkiwcip.html

[S41] C++：类与构造函数
来源：http://dali.xziqi.cn/Article/details/gtlnoypkwq.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.cucudq.cn/Article/details/gthacshlld.html

[S42] C++：继承与虚函数
来源：http://dali.0kj1m.cn/Article/details/gtmlzighod.html

class B : public Base { public: void f() override {} };
来源：http://dali.yangfankeji.com/Article/details/gtaccwdblr.html

[S43] C++：智能指针
来源：http://dali.zdqjudy.top/Article/details/gtctbfqftn.html

auto p = std::make_unique<int>(5);
来源：http://dali.ivvv.top/Article/details/gtjsbfulom.html

[S44] C++：引用传参
来源：http://dali.ivvv.top/Article/details/gtngxmxxqr.html

void inc(int &x) { ++x; }
来源：http://dali.hammf.cn/Article/details/gtnfqqlnph.html

[S45] C++：lambda
来源：http://dali.xinyue.icu/Article/details/gtjfsazbjr.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.feifeiyinyue.top/Article/details/gtusgqqead.html

[S46] C++：函数模板
来源：http://dali.xuanzx.com/Article/details/gtlwgvekcc.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.cdnleiting.top/Article/details/gtvjwjjlnv.html

[S47] C++：结构化绑定遍历
来源：http://dali.gzhubu.top/Article/details/gtsernvvoc.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.yongpay.top/Article/details/gtjsluceww.html

[S48] C++：逐行读文件
来源：http://dali.zdqjudy.top/Article/details/gtdeduotba.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.feifeiyinyue.top/Article/details/gtpiqbcdvr.html

while (std::getline(in, line)) { }
来源：http://dali.snrcjt.cn/Article/details/gtaumobyyt.html

[S49] C++：写文件
来源：http://dali.shuidangran.top/Article/details/gtmholizio.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.svipenyu.cn/Article/details/gtmiibiggs.html

[S50] C++：格式化数字
来源：http://dali.svipenyu.cn/Article/details/gtcunjtsdm.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.nanxinkj.top/Article/details/gtzjbvzaxv.html

[S51] C++：显式类型转换
来源：http://dali.pycfn.com/Article/details/gtkqwuernr.html

static_cast<double>(a) / b
来源：http://dali.xziqi.cn/Article/details/gtbhlytrsd.html

[S52] C++：const 与 noexcept
来源：http://dali.pycfn.com/Article/details/gtlopmkxfo.html

int size() const noexcept { return n_; }
来源：http://dali.havefunace.top/Article/details/gtygjhotov.html

[S53] C++：移动语义
来源：http://dali.ybcxt.top/Article/details/gtoeqlacaf.html

std::vector<int> w = std::move(v);
来源：http://dali.nwbrower.top/Article/details/gtfdcxlbta.html

[S54] C++：异常处理
来源：http://dali.yangfankeji.com/Article/details/gtshuakouu.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.jlsjyb.cn/Article/details/gtmuagxjau.html

[S55] C++：结构化绑定
来源：http://dali.nanxuanxn.top/Article/details/gtjbgylsja.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.quarkkingdee.top/Article/details/gtnoyskdow.html

[S56] C++：optional
来源：http://dali.cqqwz.cn/Article/details/gtzihwwism.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.sysykeji.top/Article/details/gtgcluukwz.html

[S57] C++：编译期常量
来源：http://dali.sufxvd.cn/Article/details/gtvgcyzfyk.html

constexpr int N = 10;
来源：http://dali.yvedp.cn/Article/details/gtjpfktwmu.html

[S58] C++：命名空间
来源：http://dali.hnqzz.top/Article/details/gtjchacudw.html

namespace ns { int f() { return 1; } }
来源：http://dali.meibo888.top/Article/details/gthlgessru.html

[S59] C++：静态断言
来源：http://dali.hammf.cn/Article/details/gtmmsvigke.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.yvedp.cn/Article/details/gtenvabxqf.html

[S60] C++：遍历并删除元素
来源：http://dali.feifeiyinyue.top/Article/details/gtyfwuxdok.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.jqgfzy.top/Article/details/gtwtqmihkx.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtdrwmychh.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhiwuduotai.top/Article/details/gtmzidcdzv.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtrmwzapex.html

[T01] Kotlin：Hello World
来源：http://dali.wangshuangyany.cn/Article/details/gtiyiajgpj.html

println("Hello")
来源：http://dali.hnxiangtu.top/Article/details/gtmkfvvosv.html

[T02] Kotlin：变量
来源：http://dali.cashguo.top/Article/details/gtnvpbaszy.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.feifeiyinyue.top/Article/details/gtycngsoeh.html

[T03] Kotlin：字符串模板
来源：http://dali.yj20258888.top/Article/details/gtmwcyfdbg.html

"值: $b"
来源：http://dali.yueranfly.top/Article/details/gtsgcqbkmm.html

[T04] Kotlin：空安全
来源：http://dali.hnqzz.top/Article/details/gtrzlinzsx.html

val n: String? = null;  n?.length
来源：http://dali.birdmap.top/Article/details/gtojpdnoha.html

[T05] Kotlin：when 表达式
来源：http://dali.jyoumei.cn/Article/details/gtzjgiawnb.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.chenlongwang.top/Article/details/gtfsctivqc.html

[T06] Kotlin：集合映射
来源：http://dali.zhiwuduotai.top/Article/details/gtbywtaspu.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.snrcjt.cn/Article/details/gtbuseiaiu.html

[T07] Kotlin：集合过滤
来源：http://dali.jqgfzy.top/Article/details/gttypenjwg.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.gogol.net.cn/Article/details/gtlqrgmupo.html

[T08] Kotlin：数据类
来源：http://dali.sweek.top/Article/details/gtkgqmhowz.html

data class User(val name: String, val age: Int)
来源：http://dali.hnqzz.top/Article/details/gtkvqdhsme.html

[T09] Kotlin：扩展函数
来源：http://dali.guannengcc.top/Article/details/gtuafzqobb.html

fun String.exclaim() = this + "!"
来源：http://dali.chenjidiqi.icu/Article/details/gtpizlpjcu.html

[T10] Kotlin：默认参数
来源：http://dali.jinqigfzy.top/Article/details/gtgyiwwbnx.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.fengsongda.top/Article/details/gtgitrxumx.html

[T11] Kotlin：协程
来源：http://dali.jinqigfzy.top/Article/details/gtljekiztu.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.c1oappe.top/Article/details/gtykuyynsl.html

[T12] Kotlin：解构声明
来源：http://dali.mhx1999.top/Article/details/gtathfofyc.html

val (a, b) = Pair(1, 2)
来源：http://dali.9152youxi.cn/Article/details/gtnfunxril.html

[T13] Kotlin：只读 Map
来源：http://dali.ybcxt.top/Article/details/gthwqndtxh.html

val m = mapOf("a" to 1)
来源：http://dali.mhx1999.top/Article/details/gtnatknfsz.html

[T14] Kotlin：循环
来源：http://dali.hammf.cn/Article/details/gtgvttnucj.html

for (i in 1..10) println(i)
来源：http://dali.pengpengdd.cyou/Article/details/gtwithziri.html

[T15] Kotlin：接口
来源：http://dali.fzhhl.top/Article/details/gtlmtgokcd.html

interface Shape { fun area(): Double }
来源：http://dali.cheryme.top/Article/details/gtpxsammxh.html

[T16] Swift：Hello World
来源：http://dali.chenlongwang.top/Article/details/gtfyumwwad.html

print("Hello")
来源：http://dali.yanxiufei.cn/Article/details/gtijqlaewb.html

[T17] Swift：变量与常量
来源：http://dali.xuanzx.com/Article/details/gtakopzmwz.html

var a = 1;  let b = 2
来源：http://dali.xuetiantiany.cn/Article/details/gtthrwonlb.html

[T18] Swift：字符串插值
来源：http://dali.cucudq.cn/Article/details/gtjyazahoc.html

"值: \(b)"
来源：http://dali.bjfxy.top/Article/details/gtderethjn.html

[T19] Swift：可选绑定
来源：http://dali.yonumen.top/Article/details/gtsztqdhnq.html

if let n = opt { print(n) }
来源：http://dali.yuanzhike.top/Article/details/gtueoelbav.html

[T20] Swift：数组操作
来源：http://dali.hfpthk.cn/Article/details/gtaqcqujjf.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.yj20258.top/Article/details/gtlqiytukp.html

[T21] Swift：遍历
来源：http://dali.snrcjt.cn/Article/details/gtrtpyxtsb.html

for x in a { print(x) }
来源：http://dali.jianghu66.top/Article/details/gttiskzvok.html

[T22] Swift：字典
来源：http://dali.hywenlv.cn/Article/details/gtmohuoctq.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.meibo888.top/Article/details/gtqssowuoy.html

[T23] Swift：函数
来源：http://dali.quarkkingdee.top/Article/details/gtaqbtvbuq.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.yuxming.cn/Article/details/gtyudhfzkv.html

[T24] Swift：闭包
来源：http://dali.zhengqikj.top/Article/details/gtwgrnquwb.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.jqgufenzy.top/Article/details/gtgfbkccyr.html

[T25] Swift：结构体
来源：http://dali.hongshengwenyu.top/Article/details/gtyhvmssby.html

struct P { var x: Int }
来源：http://dali.fzhhl.top/Article/details/gtunpzvnkx.html

[T26] Swift：类与重写
来源：http://dali.yj202588.top/Article/details/gtbdbemctf.html

class A: Base { override func f() {} }
来源：http://dali.zhiwuduotai.top/Article/details/gtafjnssmr.html

[T27] Swift：错误处理
来源：http://dali.zhixingplan.top/Article/details/gtxlzpkkyw.html

do { try f() } catch { print(error) }
来源：http://dali.xinyue.icu/Article/details/gtpcswxdpn.html

[T28] Swift：枚举
来源：http://dali.xylfe.cn/Article/details/gtrhbikoro.html

enum Color { case red, green }
来源：http://dali.cashguo.top/Article/details/gtdxqrqgxp.html

[T29] Swift：guard 提前返回
来源：http://dali.nanxinkj.top/Article/details/gtozuegqpf.html

guard let x = opt else { return }
来源：http://dali.feifeiyinyue.top/Article/details/gtfagxyaca.html

[T30] Swift：协议
来源：http://dali.redwolf501.top/Article/details/gtyighyrsx.html

protocol Shape { func area() -> Double }
来源：http://dali.chenlongwang.top/Article/details/gtdjtjbpiz.html

[T31] Lua：Hello World
来源：http://dali.hnxiangtu.top/Article/details/gttbnkrtqa.html

print("Hello")
来源：http://dali.zycfv.cn/Article/details/gtktiaeham.html

[T32] Lua：局部变量
来源：http://dali.hammf.cn/Article/details/gtqwunnvkq.html

local a = 1
来源：http://dali.gaohongyu789.top/Article/details/gthvprcsvn.html

[T33] Lua：表（数组）
来源：http://dali.hammf.cn/Article/details/gtoxcvnmbr.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.jianghu66.top/Article/details/gtafdjggoo.html

[T34] Lua：遍历表
来源：http://dali.jiagoushi.top/Article/details/gtnjjgcenm.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.yvedp.cn/Article/details/gtfsimnlgs.html

[T35] Lua：字典表
来源：http://dali.xuetiantiany.cn/Article/details/gtikmmdysh.html

local d = { a = 1 };  d.b = 2
来源：http://dali.hongshengwenyu.top/Article/details/gtqeokcokn.html

[T36] Lua：函数
来源：http://dali.andypj.xyz/Article/details/gtpcscrzof.html

function add(a, b) return a + b end
来源：http://dali.jinqigufen.top/Article/details/gtmkxjrjtw.html

[T37] Lua：字符串拼接
来源：http://dali.jyoumei.cn/Article/details/gtxcesamvr.html

"a" .. "b"
来源：http://dali.tanke756.top/Article/details/gtxakjjgmv.html

[T38] Lua：条件
来源：http://dali.hnqzz.top/Article/details/gtwolhqcxu.html

if x > 0 then print("正") end
来源：http://dali.ybcxt.top/Article/details/gtzhvlloex.html

[T39] Lua：模式匹配
来源：http://dali.cheryme.top/Article/details/gtnfjqjxcy.html

string.find(s, "%d+")
来源：http://dali.jianghu66.top/Article/details/gtvgdnfpgf.html

[T40] Lua：元表
来源：http://dali.yj20258.top/Article/details/gtyqxzmalt.html

setmetatable({}, { __index = base })
来源：http://dali.9152youxi.cn/Article/details/gtfukrdwdu.html

[T41] Perl：Hello World
来源：http://dali.andypj.xyz/Article/details/gtapquxzuu.html

print "Hello\n";
来源：http://dali.zhiwuduotai.top/Article/details/gtjrypsqno.html

[T42] Perl：变量类型
来源：http://dali.andypj.xyz/Article/details/gtkdjhspyp.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.smart0.xyz/Article/details/gtuxojswtd.html

[T43] Perl：字符串插值
来源：http://dali.xuetiantiany.cn/Article/details/gtbdieyara.html

"值: $a"
来源：http://dali.kuanghao11.cn/Article/details/gtujmjuhkk.html

[T44] Perl：条件
来源：http://dali.iojbl.cn/Article/details/gtcyztybji.html

if ($a > 0) { print "正"; }
来源：http://dali.9152youxi.cn/Article/details/gtaeanbllr.html

[T45] Perl：数组遍历
来源：http://dali.yonumen.top/Article/details/gtqvmcglvg.html

for my $x (@arr) { print $x; }
来源：http://dali.nanxinkj.top/Article/details/gtikjtqgmr.html

[T46] Perl：哈希操作
来源：http://dali.jqgufenzy.top/Article/details/gttwzucvew.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.yueranfly.top/Article/details/gttzacuofk.html

[T47] Perl：正则捕获
来源：http://dali.cheryme.top/Article/details/gtlexjwsne.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.aizwys.cn/Article/details/gtqjkgliml.html

[T48] Perl：正则替换
来源：http://dali.hongshengwenyu.top/Article/details/gtfvabuupp.html

$s =~ s/old/new/g;
来源：http://dali.sufxvd.cn/Article/details/gtmnenbvcn.html


<!-- 参考信息 -->