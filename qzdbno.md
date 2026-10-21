代发 wailian999

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.dianchejie.cn/Article/details/gtfgvfyspn.html

[R54] 比较两个文件
来源：http://dali.zdqjudy.top/Article/details/gtpmuabjrr.html

diff a.txt b.txt
来源：http://dali.yongpay.top/Article/details/gtnwahpxgs.html

[R55] 压缩与解压
来源：http://dali.hongshengwenyu.top/Article/details/gtflxsacbp.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.ivvv.top/Article/details/gtpxzjakgv.html

[R56] 远程拷贝
来源：http://dali.andypj.xyz/Article/details/gtwqkmbglq.html

scp file user@host:/path/
来源：http://dali.jianghu66.top/Article/details/gtbofmowhb.html

[R57] 远程执行命令
来源：http://dali.aizwys.cn/Article/details/gtvkpdgkrt.html

ssh user@host 'uptime'
来源：http://dali.pengpengdd.cyou/Article/details/gtfvszwtrv.html

[R58] 下载文件
来源：http://dali.andypj.xyz/Article/details/gthtnxbuov.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.kuanghao11.cn/Article/details/gttzhljqon.html

[R59] 发 POST JSON
来源：http://dali.yuanzhike.top/Article/details/gthjrdmhqt.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.jyoumei.cn/Article/details/gtotruidfd.html

[R60] 只看 HTTP 状态码
来源：http://dali.yanxiufei.cn/Article/details/gttlucpqqy.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.nanxuanxn.top/Article/details/gtlliiyiuk.html

[R61] 磁盘占用
来源：http://dali.gaohongyu789.top/Article/details/gtddohrxfx.html

df -h;  du -sh *
来源：http://dali.xuanzx.com/Article/details/gtdvjsgqpc.html

[R62] 找最占空间的文件
来源：http://dali.ppjwa.cn/Article/details/gtpstagpvr.html

du -ah . | sort -rh | head -10
来源：http://dali.yonumen.top/Article/details/gtlfyxmijg.html

[R63] 内存与进程
来源：http://dali.daria6918.cn/Article/details/gtbysjykfx.html

free -h;  ps aux | grep nginx
来源：http://dali.andypj.xyz/Article/details/gthfcypqki.html

[R64] 结束进程
来源：http://dali.zhongyouzk.top/Article/details/gtgtufpvxf.html

kill -9 $(pgrep -f app.py)
来源：http://dali.hongshengwenyu.top/Article/details/gtapvzxqoj.html

[R65] 查看端口占用
来源：http://dali.feifeiyinyue.top/Article/details/gtsooofaif.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.snrcjt.cn/Article/details/gtvuutiedq.html

[R66] 定时任务
来源：http://dali.andypj.xyz/Article/details/gtckfjmvrd.html

crontab -e;  crontab -l
来源：http://dali.yvedp.cn/Article/details/gtcgftqccg.html

[R67] 生成随机十六进制串
来源：http://dali.yuxming.cn/Article/details/gttrucdyvf.html

openssl rand -hex 16
来源：http://dali.yvedp.cn/Article/details/gtqhpttkmv.html

[R68] 计算文件校验值
来源：http://dali.gzhubu.top/Article/details/gttpsrqvui.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfbymjruv.html

[R69] 生成随机密码
来源：http://dali.chenjidiqi.icu/Article/details/gthmkhtzet.html

head -c 16 /dev/urandom | base64
来源：http://dali.yvedp.cn/Article/details/gtlzcruuws.html

[R70] 时间戳与互转
来源：http://dali.aibaodan.cn/Article/details/gtodvxqphj.html

date +%s;  date -d @1700000000
来源：http://dali.ywan-chungtsiang.top/Article/details/gttkfsrmpk.html

[R71] 日期格式化
来源：http://dali.jinghuilouyu.cn/Article/details/gtucllyqes.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.ydzc1.top/Article/details/gtwpiwjiqc.html

[R72] 等待端口就绪
来源：http://dali.fengsongda.top/Article/details/gtnrdnsgde.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.xuetiantiany.cn/Article/details/gtwrshpgkn.html

[R73] 分割大日志
来源：http://dali.zhongyouzk.top/Article/details/gtgvgcqwgw.html

split -l 1000 big.log part_
来源：http://dali.aibaodan.cn/Article/details/gtauunmkpr.html

[R74] 批量重命名
来源：http://dali.yj202588.top/Article/details/gtirymtgic.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.quarkkingdee.top/Article/details/gtzhajmxng.html

[R75] 导出环境变量
来源：http://dali.sweek.top/Article/details/gttnyzfptl.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.yangfankeji.com/Article/details/gtxfbeexke.html

[R76] 使用临时文件
来源：http://dali.jinghuilouyu.cn/Article/details/gtlyxnejlv.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhixingplan.top/Article/details/gtprojpiuc.html

[R77] 读取用户输入
来源：http://dali.pengpengdd.cyou/Article/details/gtbhzmuwbw.html

read -rp "请输入: " ans
来源：http://dali.0kj1m.cn/Article/details/gtelgwlzla.html

[R78] 交互式菜单
来源：http://dali.jlsjyb.cn/Article/details/gtaepxpfyz.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.ybcxt.top/Article/details/gtsimspfbc.html

[R79] 解析命令行选项
来源：http://dali.hongshengwenyu.top/Article/details/gtvfycgmek.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.chenlongwang.top/Article/details/gtwfaeytxm.html

[R80] 查看脚本执行耗时
来源：http://dali.cheryme.top/Article/details/gtorssxnrv.html

time ./run.sh
来源：http://dali.snrcjt.cn/Article/details/gtvxqrktue.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzzfpaznc.html

S. C / C++ 专题
来源：http://dali.hnqzz.top/Article/details/gtppzgoqco.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtjqqfbwch.html

[S01] C：Hello World
来源：http://dali.0kj1m.cn/Article/details/gtvxuzgjqz.html

#include <stdio.h>
来源：http://dali.daxiang520.top/Article/details/gtrxghgmeh.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.sufxvd.cn/Article/details/gtqnmrfhmt.html

[S02] C：变量与格式化输出
来源：http://dali.pengpengdd.cyou/Article/details/gtwuwwxgfr.html

int a = 10; printf("%d\n", a);
来源：http://dali.dianchejie.cn/Article/details/gtbwtdiqpo.html

[S03] C：读入整数
来源：http://dali.shangyingyoupin.top/Article/details/gtzcpndwbe.html

int x; scanf("%d", &x);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcdudgopg.html

[S04] C：字符串复制
来源：http://dali.guowangkeji.top/Article/details/gtkfivzvak.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.ybcxt.top/Article/details/gtzijxfctk.html

[S05] C：字符串长度
来源：http://dali.tianlin.xyz/Article/details/gtzeuwhfig.html

strlen(s)
来源：http://dali.ppjwa.cn/Article/details/gtafpuklox.html

[S06] C：字符串比较
来源：http://dali.sysykeji.top/Article/details/gtvzftthid.html

strcmp(a, b) == 0
来源：http://dali.nanxuanxn.top/Article/details/gtvnjxqtjm.html

[S07] C：数组遍历求和
来源：http://dali.haohaochexian.top/Article/details/gtifcasjhe.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.yangfankeji.com/Article/details/gttivflohq.html

[S08] C：动态内存分配与释放
来源：http://dali.ydzc1.top/Article/details/gthyfniusv.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.yj20258.top/Article/details/gtqvtdqzci.html

[S09] C：结构体定义与初始化
来源：http://dali.cdnleiting.top/Article/details/gtqvpjmbrr.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsizkwbaf.html

[S10] C：指针与解引用
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkeymuomp.html

int *p = &a;  *p = 5;
来源：http://dali.vqdsnc.cn/Article/details/gtgcwlockk.html

[S11] C：逐行读文件
来源：http://dali.jlsjyb.cn/Article/details/gtlcngygry.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.sufxvd.cn/Article/details/gtpascnpbu.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.yongpay.top/Article/details/gtiwxlzmiz.html

fclose(f);
来源：http://dali.ppjwa.cn/Article/details/gtakoniqvh.html

[S12] C：写文件
来源：http://dali.snrcjt.cn/Article/details/gtwjkchmah.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.tian-w.cn/Article/details/gtaztiykbj.html

[S13] C：宏定义
来源：http://dali.chenzaomai.com/Article/details/gtkphjuudx.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.hfpthk.cn/Article/details/gtmotpzaqu.html

[S14] C：枚举
来源：http://dali.shuidangran.top/Article/details/gtcluvtstc.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.ydzc1.top/Article/details/gttuabxhic.html

[S15] C：类型转换
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvzdijnpf.html

(double) a / b
来源：http://dali.snrcjt.cn/Article/details/gtqmhxxtln.html

[S16] C：位操作置位
来源：http://dali.jlsjyb.cn/Article/details/gtvdqgynnp.html

x |= (1 << 3);
来源：http://dali.nanxinkj.top/Article/details/gtywxpcnfk.html

[S17] C：安全拼接字符串
来源：http://dali.ppjwa.cn/Article/details/gtnzeqkant.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.nanxinkj.top/Article/details/gteknrstta.html

[S18] C：命令行参数
来源：http://dali.tanke756.top/Article/details/gtelkqgtjw.html

int main(int argc, char **argv)
来源：http://dali.zhixingplan.top/Article/details/gtytruqhpo.html

[S19] C：快速排序
来源：http://dali.yueranfly.top/Article/details/gtaroxfnxq.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.cdnleiting.top/Article/details/gtnqglphpg.html

[S20] C：二分查找
来源：http://dali.daria6918.cn/Article/details/gtganugwlj.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.jianghu66.top/Article/details/gthepbpbuu.html

[S21] C：字符类别判断
来源：http://dali.yj20258.top/Article/details/gtzvqulpnz.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.ppjwa.cn/Article/details/gtkjiunwsn.html

[S22] C：字符串转数字
来源：http://dali.nanxuanxn.top/Article/details/gtpdmztpqz.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.yonumen.top/Article/details/gtzmryiqbu.html

[S23] C：随机数
来源：http://dali.hysaishi.cn/Article/details/gtmoaaqybn.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.hysaishi.cn/Article/details/gthephiuwa.html

[S24] C：获取本地时间
来源：http://dali.zhiwuduotai.top/Article/details/gtwvdpxzwj.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.ydzc1.top/Article/details/gtktyamvec.html

[S25] C：内存拷贝
来源：http://dali.tianlin.xyz/Article/details/gtvehkhpwp.html

memcpy(dst, src, n);
来源：http://dali.shangyingyoupin.top/Article/details/gtmcbhdhzb.html

[S26] C：内存清零
来源：http://dali.zhoulong.xyz/Article/details/gtqnxyzmas.html

memset(a, 0, sizeof a);
来源：http://dali.xuanzx.com/Article/details/gtztkwxwtu.html

[S27] C：定义常量
来源：http://dali.xinyue.icu/Article/details/gtcshmmeep.html

const double PI = 3.14159;
来源：http://dali.tianlin.xyz/Article/details/gtmdewauau.html

[S28] C：静态变量
来源：http://dali.ybcxt.top/Article/details/gtakduoral.html

static int counter = 0;
来源：http://dali.hongshengwenyu.top/Article/details/gtzznowoah.html

[S29] C：变参函数
来源：http://dali.hysaishi.cn/Article/details/gtxqhafabn.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.hongshengwenyu.top/Article/details/gttxaywbmx.html

[S30] C：头文件保护
来源：http://dali.cashguo.top/Article/details/gtadlyibtz.html

#ifndef X_H
来源：http://dali.hnqzz.top/Article/details/gtxidzdtuc.html

#define X_H
来源：http://dali.redwolf501.top/Article/details/gtxkpkbjlo.html

#endif
来源：http://dali.hongshengwenyu.top/Article/details/gtpzdxundp.html

[S31] C++：Hello World
来源：http://dali.9152youxi.cn/Article/details/gtjaffnkid.html

#include <iostream>
来源：http://dali.cashguo.top/Article/details/gtihuvvmrx.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyopwfpwx.html

[S32] C++：字符串
来源：http://dali.fzhhl.top/Article/details/gtzdkmeopt.html

std::string s = "hi";  s += "!";
来源：http://dali.aizwys.cn/Article/details/gtybvhotmz.html

[S33] C++：vector 增删
来源：http://dali.haohaochexian.top/Article/details/gtfmebqrdo.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvytuzmcn.html

[S34] C++：遍历 vector
来源：http://dali.iojbl.cn/Article/details/gtciarqilr.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.daria6918.cn/Article/details/gtntbresiz.html

[S35] C++：map
来源：http://dali.0kj1m.cn/Article/details/gtdndpayjc.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hammf.cn/Article/details/gtfsmckssj.html

[S36] C++：unordered_map
来源：http://dali.zhiwuduotai.top/Article/details/gtpmhvoakg.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsfdtsifn.html

[S37] C++：set
来源：http://dali.jiagoushi.top/Article/details/gtmdylvpwj.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.shzxlz.cn/Article/details/gtsdrkaann.html

[S38] C++：排序
来源：http://dali.shuidangran.top/Article/details/gtxypidpqu.html

std::sort(v.begin(), v.end());
来源：http://dali.dashuyun.cn/Article/details/gtlifxncqd.html

[S39] C++：自定义比较器排序
来源：http://dali.fengsongda.top/Article/details/gtbohlcgjg.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.9152youxi.cn/Article/details/gthvgouxhl.html

[S40] C++：查找元素
来源：http://dali.jqgfzy.top/Article/details/gtewqioeyl.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.nanxinkj.top/Article/details/gtioizmtfz.html

[S41] C++：类与构造函数
来源：http://dali.daria6918.cn/Article/details/gtngocqglt.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.tian-w.cn/Article/details/gtpzbdzezg.html

[S42] C++：继承与虚函数
来源：http://dali.xylfe.cn/Article/details/gtekpnjcgz.html

class B : public Base { public: void f() override {} };
来源：http://dali.jinqigufen.top/Article/details/gtzktztkzk.html

[S43] C++：智能指针
来源：http://dali.yuxming.cn/Article/details/gtirpwlvij.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhongyouzk.top/Article/details/gtmnhumakf.html

[S44] C++：引用传参
来源：http://dali.hysaishi.cn/Article/details/gtplwueqoc.html

void inc(int &x) { ++x; }
来源：http://dali.zhengqikj.top/Article/details/gtfseyhvlu.html

[S45] C++：lambda
来源：http://dali.tianlin.xyz/Article/details/gtkthljzpc.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.jyoumei.cn/Article/details/gtyhvkkazs.html

[S46] C++：函数模板
来源：http://dali.cqqwz.cn/Article/details/gtunwzjauf.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhiwuduotai.top/Article/details/gtrxbnzyki.html

[S47] C++：结构化绑定遍历
来源：http://dali.hnxiangtu.top/Article/details/gtahbgyczv.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.jqgfzy.top/Article/details/gtdcgyyfxh.html

[S48] C++：逐行读文件
来源：http://dali.iojbl.cn/Article/details/gtmguuxbzp.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.hammf.cn/Article/details/gtjohpufjo.html

while (std::getline(in, line)) { }
来源：http://dali.nanxinkj.top/Article/details/gtvfyjbttq.html

[S49] C++：写文件
来源：http://dali.yanxiufei.cn/Article/details/gtswrslepz.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.yvedp.cn/Article/details/gttcoatyyp.html

[S50] C++：格式化数字
来源：http://dali.andypj.xyz/Article/details/gtsiacnmua.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.haohaochexian.top/Article/details/gtogchvsiy.html

[S51] C++：显式类型转换
来源：http://dali.9152youxi.cn/Article/details/gtqtwbhnpl.html

static_cast<double>(a) / b
来源：http://dali.cdnleiting.top/Article/details/gtxvtpvmgh.html

[S52] C++：const 与 noexcept
来源：http://dali.smart0.xyz/Article/details/gtindebfso.html

int size() const noexcept { return n_; }
来源：http://dali.gogol.net.cn/Article/details/gtubjeayag.html

[S53] C++：移动语义
来源：http://dali.jlsjyb.cn/Article/details/gtwzobiuht.html

std::vector<int> w = std::move(v);
来源：http://dali.c1oappe.top/Article/details/gtwflgyxng.html

[S54] C++：异常处理
来源：http://dali.yvedp.cn/Article/details/gtrnjmceqw.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.chenlongwang.top/Article/details/gtanxvgsyr.html

[S55] C++：结构化绑定
来源：http://dali.wangdashe.top/Article/details/gtzgtknucq.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.redwolf501.top/Article/details/gtfxlzrksa.html

[S56] C++：optional
来源：http://dali.jqgfzy.top/Article/details/gtyxskyaec.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.andypj.xyz/Article/details/gtbgyqdxik.html

[S57] C++：编译期常量
来源：http://dali.sxryk.cn/Article/details/gtgejxjiyu.html

constexpr int N = 10;
来源：http://dali.svipenyu.cn/Article/details/gtprsezcut.html

[S58] C++：命名空间
来源：http://dali.guowangkeji.top/Article/details/gtjzhipfxk.html

namespace ns { int f() { return 1; } }
来源：http://dali.zdqjudy.top/Article/details/gtrbpgfwmf.html

[S59] C++：静态断言
来源：http://dali.sxryk.cn/Article/details/gthrmawieh.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.cashguo.top/Article/details/gtjkdawapm.html

[S60] C++：遍历并删除元素
来源：http://dali.zhixingplan.top/Article/details/gtavkmbzok.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.birdmap.top/Article/details/gtooidbcpa.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtoicqgzxr.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.sweek.top/Article/details/gtlfxlorug.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtorvlaogg.html

[T01] Kotlin：Hello World
来源：http://dali.tanke756.top/Article/details/gtsfvtzqwo.html

println("Hello")
来源：http://dali.aizwys.cn/Article/details/gtoduhytjo.html

[T02] Kotlin：变量
来源：http://dali.xinyue.icu/Article/details/gtopfxgvrh.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.haohaochexian.top/Article/details/gtzajjuhnx.html

[T03] Kotlin：字符串模板
来源：http://dali.xinyue.icu/Article/details/gtubgfsjes.html

"值: $b"
来源：http://dali.jqgfzy.top/Article/details/gtwwhcffie.html

[T04] Kotlin：空安全
来源：http://dali.zycfv.cn/Article/details/gtzjcowejt.html

val n: String? = null;  n?.length
来源：http://dali.zhixingplan.top/Article/details/gturtbqfqv.html

[T05] Kotlin：when 表达式
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgcvsswwv.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.0kj1m.cn/Article/details/gtndcjyziu.html

[T06] Kotlin：集合映射
来源：http://dali.hysaishi.cn/Article/details/gtrvdlpzax.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.hnxiangtu.top/Article/details/gtmeuhwucq.html

[T07] Kotlin：集合过滤
来源：http://dali.jqgufenzy.top/Article/details/gtxysbiwep.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.daxiang520.top/Article/details/gtzzzvxdcx.html

[T08] Kotlin：数据类
来源：http://dali.iojbl.cn/Article/details/gtkquvjqnp.html

data class User(val name: String, val age: Int)
来源：http://dali.yj20258.top/Article/details/gtqtjxdfoo.html

[T09] Kotlin：扩展函数
来源：http://dali.andypj.xyz/Article/details/gtqqdbkxdw.html

fun String.exclaim() = this + "!"
来源：http://dali.andypj.xyz/Article/details/gtuqsjbdba.html

[T10] Kotlin：默认参数
来源：http://dali.zhoulong.xyz/Article/details/gtffkpepeb.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.dashuyun.cn/Article/details/gtiyuryseu.html

[T11] Kotlin：协程
来源：http://dali.ppjwa.cn/Article/details/gtkambxweq.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.daxiang520.top/Article/details/gtaldbqwrp.html

[T12] Kotlin：解构声明
来源：http://dali.hfpthk.cn/Article/details/gtojjdufov.html

val (a, b) = Pair(1, 2)
来源：http://dali.sysykeji.top/Article/details/gtngecxgbt.html

[T13] Kotlin：只读 Map
来源：http://dali.cashguo.top/Article/details/gttardnkup.html

val m = mapOf("a" to 1)
来源：http://dali.yj20258.top/Article/details/gtviqnzlxg.html

[T14] Kotlin：循环
来源：http://dali.zhengqikj.top/Article/details/gtpissptmm.html

for (i in 1..10) println(i)
来源：http://dali.hfpthk.cn/Article/details/gtvvqoevla.html

[T15] Kotlin：接口
来源：http://dali.zhoulong.xyz/Article/details/gteqzyvhtv.html

interface Shape { fun area(): Double }
来源：http://dali.ydzc1.top/Article/details/gtizbwzfgv.html

[T16] Swift：Hello World
来源：http://dali.sufxvd.cn/Article/details/gtuczpetqw.html

print("Hello")
来源：http://dali.shangyingyoupin.top/Article/details/gtjvxidndu.html

[T17] Swift：变量与常量
来源：http://dali.mhx1999.top/Article/details/gtygwznmuq.html

var a = 1;  let b = 2
来源：http://dali.aibaodan.cn/Article/details/gtytmfvyoh.html

[T18] Swift：字符串插值
来源：http://dali.shzxlz.cn/Article/details/gtljwhixij.html

"值: \(b)"
来源：http://dali.xuetiantiany.cn/Article/details/gtkyxtkbza.html

[T19] Swift：可选绑定
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpdhlyvht.html

if let n = opt { print(n) }
来源：http://dali.cucudq.cn/Article/details/gtonzaxwww.html

[T20] Swift：数组操作
来源：http://dali.fengsongda.top/Article/details/gtyiervrzx.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.wangshuangyany.cn/Article/details/gtxgdleoao.html

[T21] Swift：遍历
来源：http://dali.hnqzz.top/Article/details/gttdglrvws.html

for x in a { print(x) }
来源：http://dali.yangfankeji.com/Article/details/gttrvoqyts.html

[T22] Swift：字典
来源：http://dali.jqgufenzy.top/Article/details/gtthdalukv.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.dashuyun.cn/Article/details/gtobdfxilx.html

[T23] Swift：函数
来源：http://dali.zycfv.cn/Article/details/gtyumnxvlb.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.yj20258.top/Article/details/gtrqzubyzf.html

[T24] Swift：闭包
来源：http://dali.yuxming.cn/Article/details/gtyeqsinel.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.snrcjt.cn/Article/details/gtbfhayumw.html

[T25] Swift：结构体
来源：http://dali.xuetiantiany.cn/Article/details/gtiqiyoqgj.html

struct P { var x: Int }
来源：http://dali.havefunace.top/Article/details/gtyxncuxkk.html

[T26] Swift：类与重写
来源：http://dali.bjfxy.top/Article/details/gtgnsbeegf.html

class A: Base { override func f() {} }
来源：http://dali.yangfankeji.com/Article/details/gtdztnwpfc.html

[T27] Swift：错误处理
来源：http://dali.jiagoushi.top/Article/details/gtttacsoxn.html

do { try f() } catch { print(error) }
来源：http://dali.yj20258888.top/Article/details/gtlfgjxrcy.html

[T28] Swift：枚举
来源：http://dali.cheryme.top/Article/details/gtvakiqyhy.html

enum Color { case red, green }
来源：http://dali.hongshengwenyu.top/Article/details/gtbryrbzkx.html

[T29] Swift：guard 提前返回
来源：http://dali.gzhubu.top/Article/details/gtpjufdrtw.html

guard let x = opt else { return }
来源：http://dali.shzxlz.cn/Article/details/gtvdefkizo.html

[T30] Swift：协议
来源：http://dali.yonumen.top/Article/details/gtklurdarx.html

protocol Shape { func area() -> Double }
来源：http://dali.yangfankeji.com/Article/details/gtyasounyf.html

[T31] Lua：Hello World
来源：http://dali.quarkkingdee.top/Article/details/gtavwrnmvl.html

print("Hello")
来源：http://dali.yangfankeji.com/Article/details/gtmpsjvjff.html

[T32] Lua：局部变量
来源：http://dali.pengpengdd.cyou/Article/details/gttudcztqw.html

local a = 1
来源：http://dali.guowangkeji.top/Article/details/gtnyycoxmg.html

[T33] Lua：表（数组）
来源：http://dali.tian-w.cn/Article/details/gtclxzdrag.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.daria6918.cn/Article/details/gtwrkhjrzy.html

[T34] Lua：遍历表
来源：http://dali.jyoumei.cn/Article/details/gtevcntlvz.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.nanxuanxn.top/Article/details/gtikscebql.html

[T35] Lua：字典表
来源：http://dali.sufxvd.cn/Article/details/gtjsrdncpx.html

local d = { a = 1 };  d.b = 2
来源：http://dali.haohaochexian.top/Article/details/gtsjqmhicn.html

[T36] Lua：函数
来源：http://dali.yj20258888.top/Article/details/gtcbisqnem.html

function add(a, b) return a + b end
来源：http://dali.xuanzx.com/Article/details/gttvdodkjv.html

[T37] Lua：字符串拼接
来源：http://dali.yj20258.top/Article/details/gtsbwdzeip.html

"a" .. "b"
来源：http://dali.ivvv.top/Article/details/gtenzqnvsr.html

[T38] Lua：条件
来源：http://dali.sufxvd.cn/Article/details/gtthupxyzb.html

if x > 0 then print("正") end
来源：http://dali.redwolf501.top/Article/details/gtrjbcwlqu.html

[T39] Lua：模式匹配
来源：http://dali.0kj1m.cn/Article/details/gtbvifhore.html

string.find(s, "%d+")
来源：http://dali.bjfxy.top/Article/details/gtacpabjgc.html

[T40] Lua：元表
来源：http://dali.quarkkingdee.top/Article/details/gtzgldyned.html

setmetatable({}, { __index = base })
来源：http://dali.yangfankeji.com/Article/details/gtpcudptzj.html

[T41] Perl：Hello World
来源：http://dali.ybcxt.top/Article/details/gtffskkirk.html

print "Hello\n";
来源：http://dali.sysykeji.top/Article/details/gtyhlofbkb.html

[T42] Perl：变量类型
来源：http://dali.mhx1999.top/Article/details/gtncfuemzd.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.fengsongda.top/Article/details/gtujawnrdn.html

[T43] Perl：字符串插值
来源：http://dali.feifeiyinyue.top/Article/details/gtbjdekuoy.html

"值: $a"
来源：http://dali.nanxinkj.top/Article/details/gtmnqghzsz.html

[T44] Perl：条件
来源：http://dali.ppjwa.cn/Article/details/gtwfvquknk.html

if ($a > 0) { print "正"; }
来源：http://dali.ppjwa.cn/Article/details/gtxgaxrwtx.html

[T45] Perl：数组遍历
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwlyjjpof.html

for my $x (@arr) { print $x; }
来源：http://dali.xylfe.cn/Article/details/gtmzatppgh.html

[T46] Perl：哈希操作
来源：http://dali.dashuyun.cn/Article/details/gtpfjhtchp.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.yongpay.top/Article/details/gtdjaggjbc.html

[T47] Perl：正则捕获
来源：http://dali.andypj.xyz/Article/details/gtqowpmsgd.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.cashguo.top/Article/details/gtcaxatisb.html

[T48] Perl：正则替换
来源：http://dali.jlsjyb.cn/Article/details/gthtpfrvsu.html

$s =~ s/old/new/g;
来源：http://dali.shzxlz.cn/Article/details/gtpxtehzgz.html

[T49] Perl：函数
来源：http://dali.chenlongwang.top/Article/details/gtedbaggqm.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.yangfankeji.com/Article/details/gtrdaktsvh.html

[T50] Perl：逐行读文件
来源：http://dali.ppjwa.cn/Article/details/gtwhvhelgb.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.yj20258888.top/Article/details/gtzbppqtcp.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gtdenhfzfg.html

[T51] Scala：Hello World
来源：http://dali.hysaishi.cn/Article/details/gtyphhaihk.html

println("Hello")
来源：http://dali.shanyushiyangtech.top/Article/details/gtliavdlxp.html

[T52] Scala：变量
来源：http://dali.tanke756.top/Article/details/gtlwrxnupf.html

val a = 1;  var b = 2
来源：http://dali.jqgfzy.top/Article/details/gtyycoawzf.html

[T53] Scala：字符串插值
来源：http://dali.haohaochexian.top/Article/details/gtlxmaynfx.html

s"值: $b"
来源：http://dali.andypj.xyz/Article/details/gtddlpelpu.html

[T54] Scala：集合映射
来源：http://dali.jiagoushi.top/Article/details/gtcjhlpkao.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.nanxinkj.top/Article/details/gtvsbmlhje.html

[T55] Scala：集合过滤
来源：http://dali.sufxvd.cn/Article/details/gtjkueqqmw.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.yj20258888.top/Article/details/gtqvjsbvuk.html

[T56] Scala：样例类
来源：http://dali.0kj1m.cn/Article/details/gtiupxnqxq.html


<!-- 参考信息 -->