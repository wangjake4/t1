代发 wailian999

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.ydzc1.top/Article/details/gthreocdeg.html

[R52] 统计行数
来源：http://dali.chenlongwang.top/Article/details/gtlusdwucp.html

wc -l a.txt
来源：http://dali.tanke756.top/Article/details/gtbgiosgps.html

[R53] 查看文件头与实时尾
来源：http://dali.feifeiyinyue.top/Article/details/gtrpfwehdb.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.chenzaomai.com/Article/details/gtthewfivt.html

[R54] 比较两个文件
来源：http://dali.pycfn.com/Article/details/gtuqtckell.html

diff a.txt b.txt
来源：http://dali.jianghu66.top/Article/details/gtgprxdcqw.html

[R55] 压缩与解压
来源：http://dali.xuanzx.com/Article/details/gtmjfkohzh.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.vqdsnc.cn/Article/details/gtudzbyfgq.html

[R56] 远程拷贝
来源：http://dali.sxryk.cn/Article/details/gtebgssasd.html

scp file user@host:/path/
来源：http://dali.shzxlz.cn/Article/details/gtewgfjaga.html

[R57] 远程执行命令
来源：http://dali.feifeiyinyue.top/Article/details/gtpajpnrqu.html

ssh user@host 'uptime'
来源：http://dali.yanxiufei.cn/Article/details/gttsiljyty.html

[R58] 下载文件
来源：http://dali.zdqjudy.top/Article/details/gtdjnnkcsa.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.xuetiantiany.cn/Article/details/gtzfgrylaq.html

[R59] 发 POST JSON
来源：http://dali.snrcjt.cn/Article/details/gttgacutus.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.0kj1m.cn/Article/details/gtzbioeoul.html

[R60] 只看 HTTP 状态码
来源：http://dali.yongpay.top/Article/details/gtrjkhdkkb.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.gotoacloud.top/Article/details/gtirzmylgx.html

[R61] 磁盘占用
来源：http://dali.redwolf501.top/Article/details/gtasmczjxg.html

df -h;  du -sh *
来源：http://dali.dianchejie.cn/Article/details/gtuptcquvj.html

[R62] 找最占空间的文件
来源：http://dali.gotoacloud.top/Article/details/gtmyxrhkuh.html

du -ah . | sort -rh | head -10
来源：http://dali.nwbrower.top/Article/details/gtipwaresp.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gtrndogcna.html

free -h;  ps aux | grep nginx
来源：http://dali.andypj.xyz/Article/details/gtqbbezdkw.html

[R64] 结束进程
来源：http://dali.yj20258888.top/Article/details/gtuwhjgaut.html

kill -9 $(pgrep -f app.py)
来源：http://dali.xuanzx.com/Article/details/gtxynbqzwi.html

[R65] 查看端口占用
来源：http://dali.wangshuangyany.cn/Article/details/gtcdetjqsn.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.vqdsnc.cn/Article/details/gtrtsnkcpg.html

[R66] 定时任务
来源：http://dali.jinqigufen.top/Article/details/gtahjaugqg.html

crontab -e;  crontab -l
来源：http://dali.guowangkeji.top/Article/details/gtbphfhlvn.html

[R67] 生成随机十六进制串
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuowgnqrn.html

openssl rand -hex 16
来源：http://dali.yongpay.top/Article/details/gtesdzkxzo.html

[R68] 计算文件校验值
来源：http://dali.kuanghao11.cn/Article/details/gttpsslipe.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.tian-w.cn/Article/details/gtablryxmh.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gtnimbmruh.html

head -c 16 /dev/urandom | base64
来源：http://dali.hnqzz.top/Article/details/gtukddabdq.html

[R70] 时间戳与互转
来源：http://dali.xylfe.cn/Article/details/gtbksbvjom.html

date +%s;  date -d @1700000000
来源：http://dali.gogol.net.cn/Article/details/gtalotpvzu.html

[R71] 日期格式化
来源：http://dali.meibo888.top/Article/details/gtckgpwwdy.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.jqgfzy.top/Article/details/gtrndvkwwk.html

[R72] 等待端口就绪
来源：http://dali.haohaochexian.top/Article/details/gtkedofrew.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.sysykeji.top/Article/details/gtqyogbqeu.html

[R73] 分割大日志
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwqerinyz.html

split -l 1000 big.log part_
来源：http://dali.shanyushiyangtech.top/Article/details/gtnuixufpx.html

[R74] 批量重命名
来源：http://dali.zhongyouzk.top/Article/details/gtvrgcvnme.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.jqgfzy.top/Article/details/gtnnvlyber.html

[R75] 导出环境变量
来源：http://dali.gaohongyu789.top/Article/details/gtzmxojpns.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.nanxuanxn.top/Article/details/gtbejbfsnm.html

[R76] 使用临时文件
来源：http://dali.nanxuanxn.top/Article/details/gtstwhehad.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.cqqwz.cn/Article/details/gtywcouzwv.html

[R77] 读取用户输入
来源：http://dali.hywenlv.cn/Article/details/gtxsjqfgru.html

read -rp "请输入: " ans
来源：http://dali.sufxvd.cn/Article/details/gtwwboloqp.html

[R78] 交互式菜单
来源：http://dali.hammf.cn/Article/details/gtiftqqqip.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.yj20258.top/Article/details/gtyvomfkbw.html

[R79] 解析命令行选项
来源：http://dali.havefunace.top/Article/details/gtvlrxxbga.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.aibaodan.cn/Article/details/gtnnwtpdlm.html

[R80] 查看脚本执行耗时
来源：http://dali.daria6918.cn/Article/details/gtyvfxeimq.html

time ./run.sh
来源：http://dali.jinyuanbaomall.cn/Article/details/gtafreyfmx.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtwmhtipmy.html

S. C / C++ 专题
来源：http://dali.sysykeji.top/Article/details/gtawpcgbms.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtbawjbolx.html

[S01] C：Hello World
来源：http://dali.cashguo.top/Article/details/gtrxemtgtj.html

#include <stdio.h>
来源：http://dali.birdmap.top/Article/details/gtkgffytuh.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.hnqzz.top/Article/details/gtdvueacnh.html

[S02] C：变量与格式化输出
来源：http://dali.cashguo.top/Article/details/gtbotsuuad.html

int a = 10; printf("%d\n", a);
来源：http://dali.sysykeji.top/Article/details/gtbahvpxhl.html

[S03] C：读入整数
来源：http://dali.cdnleiting.top/Article/details/gtfgknwwax.html

int x; scanf("%d", &x);
来源：http://dali.hnxiangtu.top/Article/details/gtvsxkkgfs.html

[S04] C：字符串复制
来源：http://dali.ybcxt.top/Article/details/gtxrlxailq.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.aibaodan.cn/Article/details/gtbcjddldp.html

[S05] C：字符串长度
来源：http://dali.yuanzhike.top/Article/details/gtnvhlilok.html

strlen(s)
来源：http://dali.gotoacloud.top/Article/details/gtgkvseibo.html

[S06] C：字符串比较
来源：http://dali.bjfxy.top/Article/details/gtqjolsqla.html

strcmp(a, b) == 0
来源：http://dali.dashuyun.cn/Article/details/gtbvwvfqqw.html

[S07] C：数组遍历求和
来源：http://dali.hnxiangtu.top/Article/details/gtukfwzawr.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhoulong.xyz/Article/details/gtvkccymbo.html

[S08] C：动态内存分配与释放
来源：http://dali.nanxuanxn.top/Article/details/gtnvampdlo.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.xuetiantiany.cn/Article/details/gtenefwnpv.html

[S09] C：结构体定义与初始化
来源：http://dali.aizwys.cn/Article/details/gtqjliamze.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.yj20258888.top/Article/details/gtmeanibhq.html

[S10] C：指针与解引用
来源：http://dali.smart0.xyz/Article/details/gtapirgnzp.html

int *p = &a;  *p = 5;
来源：http://dali.yvedp.cn/Article/details/gtpkbsjaem.html

[S11] C：逐行读文件
来源：http://dali.tianlin.xyz/Article/details/gtngglfsmi.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.xuetiantiany.cn/Article/details/gtlchtedmg.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.xuetiantiany.cn/Article/details/gtmkeqmlej.html

fclose(f);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwmbfitez.html

[S12] C：写文件
来源：http://dali.hongshengwenyu.top/Article/details/gtufguoyra.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyalgarpe.html

[S13] C：宏定义
来源：http://dali.snrcjt.cn/Article/details/gtyxqrbouf.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhoulong.xyz/Article/details/gtamlhinfp.html

[S14] C：枚举
来源：http://dali.tianlin.xyz/Article/details/gtoxgoajhr.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.iojbl.cn/Article/details/gtbxupnutm.html

[S15] C：类型转换
来源：http://dali.fzhhl.top/Article/details/gtuxbvalox.html

(double) a / b
来源：http://dali.sysykeji.top/Article/details/gtjtkbkooz.html

[S16] C：位操作置位
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtevvrftuo.html

x |= (1 << 3);
来源：http://dali.xuanzx.com/Article/details/gtpdxxbngq.html

[S17] C：安全拼接字符串
来源：http://dali.jinqigfzy.top/Article/details/gtfcssrxjo.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhixingplan.top/Article/details/gtnhbyqjwa.html

[S18] C：命令行参数
来源：http://dali.shangyingyoupin.top/Article/details/gtfssllnev.html

int main(int argc, char **argv)
来源：http://dali.jlsjyb.cn/Article/details/gtonxcxfiz.html

[S19] C：快速排序
来源：http://dali.daria6918.cn/Article/details/gtwftrqpry.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.yangfankeji.com/Article/details/gtkaoetdsk.html

[S20] C：二分查找
来源：http://dali.yvedp.cn/Article/details/gtrkaeqezr.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.gzhubu.top/Article/details/gtyjxjwkdn.html

[S21] C：字符类别判断
来源：http://dali.shanyushiyangkeji.top/Article/details/gthqanysip.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.gotoacloud.top/Article/details/gtkpdqdbcp.html

[S22] C：字符串转数字
来源：http://dali.hammf.cn/Article/details/gtsziwbcta.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.vqdsnc.cn/Article/details/gtmymrmnxz.html

[S23] C：随机数
来源：http://dali.nwbrower.top/Article/details/gtqprbyjtc.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhongyouzk.top/Article/details/gtglliexup.html

[S24] C：获取本地时间
来源：http://dali.daxiang520.top/Article/details/gtovzerarh.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.yvedp.cn/Article/details/gtiunynmyi.html

[S25] C：内存拷贝
来源：http://dali.cucudq.cn/Article/details/gtjvakbgmf.html

memcpy(dst, src, n);
来源：http://dali.zdqjudy.top/Article/details/gtkogggozp.html

[S26] C：内存清零
来源：http://dali.jlsjyb.cn/Article/details/gthbkyhzak.html

memset(a, 0, sizeof a);
来源：http://dali.snrcjt.cn/Article/details/gtuqokvdfu.html

[S27] C：定义常量
来源：http://dali.tianlin.xyz/Article/details/gtzhfndmsh.html

const double PI = 3.14159;
来源：http://dali.birdmap.top/Article/details/gtvhrqifwa.html

[S28] C：静态变量
来源：http://dali.hnqzz.top/Article/details/gtpeetbpmy.html

static int counter = 0;
来源：http://dali.hongshengwenyu.top/Article/details/gtbjvtcngj.html

[S29] C：变参函数
来源：http://dali.zhoulong.xyz/Article/details/gtrsunthcx.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.tanke756.top/Article/details/gtcqtpguvh.html

[S30] C：头文件保护
来源：http://dali.wangdashe.top/Article/details/gtiqyrztbb.html

#ifndef X_H
来源：http://dali.zhoulong.xyz/Article/details/gtytfzhadt.html

#define X_H
来源：http://dali.gzhubu.top/Article/details/gthdndjgbz.html

#endif
来源：http://dali.snrcjt.cn/Article/details/gtvfrtowvf.html

[S31] C++：Hello World
来源：http://dali.pengpengdd.cyou/Article/details/gtleablybd.html

#include <iostream>
来源：http://dali.ydzc1.top/Article/details/gtefqsveuj.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.chenlongwang.top/Article/details/gtvuiysaxa.html

[S32] C++：字符串
来源：http://dali.jqgufenzy.top/Article/details/gtvpbqcyag.html

std::string s = "hi";  s += "!";
来源：http://dali.pycfn.com/Article/details/gtcufnhqrl.html

[S33] C++：vector 增删
来源：http://dali.yonumen.top/Article/details/gtilvzmvca.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.iojbl.cn/Article/details/gtjiwrjsjv.html

[S34] C++：遍历 vector
来源：http://dali.ivvv.top/Article/details/gtchqwdrou.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhixingplan.top/Article/details/gtrdglqkuq.html

[S35] C++：map
来源：http://dali.guowangkeji.top/Article/details/gtvdomdhhl.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.mhx1999.top/Article/details/gtahodpqub.html

[S36] C++：unordered_map
来源：http://dali.0kj1m.cn/Article/details/gttdrmhnjk.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.chenzaomai.com/Article/details/gtcmfendqh.html

[S37] C++：set
来源：http://dali.zycfv.cn/Article/details/gtacsbxhfo.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.chenjidiqi.icu/Article/details/gtrcfpwddc.html

[S38] C++：排序
来源：http://dali.gotoacloud.top/Article/details/gtugagmsgd.html

std::sort(v.begin(), v.end());
来源：http://dali.shuidangran.top/Article/details/gtofhznuky.html

[S39] C++：自定义比较器排序
来源：http://dali.guowangkeji.top/Article/details/gtogovkijw.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.chenjidiqi.icu/Article/details/gttzwrupsi.html

[S40] C++：查找元素
来源：http://dali.xuanzx.com/Article/details/gtgarwmyjc.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.cdnleiting.top/Article/details/gtwmthcxqb.html

[S41] C++：类与构造函数
来源：http://dali.zhixingplan.top/Article/details/gtuwepbqov.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.hnqzz.top/Article/details/gtlwejloft.html

[S42] C++：继承与虚函数
来源：http://dali.dashuyun.cn/Article/details/gtbzfghqpl.html

class B : public Base { public: void f() override {} };
来源：http://dali.aibaodan.cn/Article/details/gtvczhsxvz.html

[S43] C++：智能指针
来源：http://dali.chenlongwang.top/Article/details/gtqkcqtexw.html

auto p = std::make_unique<int>(5);
来源：http://dali.kuanghao11.cn/Article/details/gtllydwaps.html

[S44] C++：引用传参
来源：http://dali.ivvv.top/Article/details/gtoitfyljp.html

void inc(int &x) { ++x; }
来源：http://dali.jianghu66.top/Article/details/gtqpmxfdsg.html

[S45] C++：lambda
来源：http://dali.ppjwa.cn/Article/details/gtkiawkrij.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.ywan-chungtsiang.top/Article/details/gtreqmfutq.html

[S46] C++：函数模板
来源：http://dali.shangyingyoupin.top/Article/details/gtqspanwap.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.shangyingyoupin.top/Article/details/gtkapjukyg.html

[S47] C++：结构化绑定遍历
来源：http://dali.tanke756.top/Article/details/gtwadcqbiu.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.hfpthk.cn/Article/details/gtjgzimbgj.html

[S48] C++：逐行读文件
来源：http://dali.cdnleiting.top/Article/details/gtivqliowa.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.wangshuangyany.cn/Article/details/gtgwlhttmw.html

while (std::getline(in, line)) { }
来源：http://dali.mhx1999.top/Article/details/gtlbycqyal.html

[S49] C++：写文件
来源：http://dali.jinghuilouyu.cn/Article/details/gthpsoyahx.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.jqgfzy.top/Article/details/gtemuuyozd.html

[S50] C++：格式化数字
来源：http://dali.jiagoushi.top/Article/details/gtenwwsqbk.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.havefunace.top/Article/details/gtsnlgjaut.html

[S51] C++：显式类型转换
来源：http://dali.yangfankeji.com/Article/details/gtbmxffiit.html

static_cast<double>(a) / b
来源：http://dali.meibo888.top/Article/details/gtfnibvanl.html

[S52] C++：const 与 noexcept
来源：http://dali.jinghuilouyu.cn/Article/details/gtjushavrg.html

int size() const noexcept { return n_; }
来源：http://dali.sweek.top/Article/details/gttrjswnfl.html

[S53] C++：移动语义
来源：http://dali.vqdsnc.cn/Article/details/gtoxfwfruu.html

std::vector<int> w = std::move(v);
来源：http://dali.c1oappe.top/Article/details/gtqvmzuyxk.html

[S54] C++：异常处理
来源：http://dali.dashuyun.cn/Article/details/gtufxwwrbh.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiummywju.html

[S55] C++：结构化绑定
来源：http://dali.daxiang520.top/Article/details/gtrpruxmko.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgxpjfbzc.html

[S56] C++：optional
来源：http://dali.gaohongyu789.top/Article/details/gtzgkgwisw.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhengqikj.top/Article/details/gtxlrimsxk.html

[S57] C++：编译期常量
来源：http://dali.zhengqikj.top/Article/details/gttyexfvws.html

constexpr int N = 10;
来源：http://dali.pycfn.com/Article/details/gtdpjpmbyq.html

[S58] C++：命名空间
来源：http://dali.xziqi.cn/Article/details/gtjgpprtzp.html

namespace ns { int f() { return 1; } }
来源：http://dali.pycfn.com/Article/details/gtqcohhrzb.html

[S59] C++：静态断言
来源：http://dali.jqgufenzy.top/Article/details/gtausvghkg.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.yongpay.top/Article/details/gtykvfcvrg.html

[S60] C++：遍历并删除元素
来源：http://dali.svipenyu.cn/Article/details/gtabejwgju.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.yj20258.top/Article/details/gtgzddqhas.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuxjgoyqn.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.tian-w.cn/Article/details/gtshnjvfzs.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtllwlsecw.html

[T01] Kotlin：Hello World
来源：http://dali.daxiang520.top/Article/details/gteroysqlg.html

println("Hello")
来源：http://dali.yj202588.top/Article/details/gtdeiuzxxu.html

[T02] Kotlin：变量
来源：http://dali.jianghu66.top/Article/details/gttaogihxx.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.yonumen.top/Article/details/gtzkfuwzjn.html

[T03] Kotlin：字符串模板
来源：http://dali.9152youxi.cn/Article/details/gttkjfustw.html

"值: $b"
来源：http://dali.shanyushiyangtech.top/Article/details/gtydmoubem.html

[T04] Kotlin：空安全
来源：http://dali.hywenlv.cn/Article/details/gtntbctglq.html

val n: String? = null;  n?.length
来源：http://dali.guannengcc.top/Article/details/gtgilpuwbw.html

[T05] Kotlin：when 表达式
来源：http://dali.shuidangran.top/Article/details/gtffatbntl.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.jinqigfzy.top/Article/details/gtxejwjjoz.html

[T06] Kotlin：集合映射
来源：http://dali.yuanzhike.top/Article/details/gtzcuzxjtx.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.jyoumei.cn/Article/details/gtxhuxuhzi.html

[T07] Kotlin：集合过滤
来源：http://dali.shzxlz.cn/Article/details/gtroaluzji.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.pengpengdd.cyou/Article/details/gtzascvgtc.html

[T08] Kotlin：数据类
来源：http://dali.birdmap.top/Article/details/gtdsvmiwgo.html

data class User(val name: String, val age: Int)
来源：http://dali.316326.xyz/Article/details/gtnxlgeiqp.html

[T09] Kotlin：扩展函数
来源：http://dali.birdmap.top/Article/details/gtmssiuvyf.html

fun String.exclaim() = this + "!"
来源：http://dali.tianlin.xyz/Article/details/gtyufgmdvn.html

[T10] Kotlin：默认参数
来源：http://dali.guannengcc.top/Article/details/gteatfcvig.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.shanyushiyangtech.top/Article/details/gttohtzbbj.html

[T11] Kotlin：协程
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthkdrfofp.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.sufxvd.cn/Article/details/gtbyfcdogc.html

[T12] Kotlin：解构声明
来源：http://dali.xuetiantiany.cn/Article/details/gtiidrmeso.html

val (a, b) = Pair(1, 2)
来源：http://dali.xuanzx.com/Article/details/gtgoylyhgr.html

[T13] Kotlin：只读 Map
来源：http://dali.mhx1999.top/Article/details/gttgebabsn.html

val m = mapOf("a" to 1)
来源：http://dali.gaohongyu789.top/Article/details/gtmmfiyavj.html

[T14] Kotlin：循环
来源：http://dali.pengpengdd.cyou/Article/details/gtievqltdg.html

for (i in 1..10) println(i)
来源：http://dali.xylfe.cn/Article/details/gtosflmkqb.html

[T15] Kotlin：接口
来源：http://dali.yangfankeji.com/Article/details/gtbkdgkarw.html

interface Shape { fun area(): Double }
来源：http://dali.nanxinkj.top/Article/details/gtlxlemmbn.html

[T16] Swift：Hello World
来源：http://dali.chenjidiqi.icu/Article/details/gtbifbvnpf.html

print("Hello")
来源：http://dali.hnxiangtu.top/Article/details/gtfjbvgiac.html

[T17] Swift：变量与常量
来源：http://dali.0kj1m.cn/Article/details/gtzsfxyvvp.html

var a = 1;  let b = 2
来源：http://dali.sweek.top/Article/details/gtiomouhrr.html

[T18] Swift：字符串插值
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkgmbjhld.html

"值: \(b)"
来源：http://dali.chenzaomai.com/Article/details/gtfprvzdrh.html

[T19] Swift：可选绑定
来源：http://dali.cdnleiting.top/Article/details/gtgctplmlz.html

if let n = opt { print(n) }
来源：http://dali.cashguo.top/Article/details/gtjqgffxev.html

[T20] Swift：数组操作
来源：http://dali.gaohongyu789.top/Article/details/gtktpigfrf.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.cashguo.top/Article/details/gthomlfsed.html

[T21] Swift：遍历
来源：http://dali.yj20258888.top/Article/details/gtnbmccfcc.html

for x in a { print(x) }
来源：http://dali.nanxinkj.top/Article/details/gtoujodmqe.html

[T22] Swift：字典
来源：http://dali.316326.xyz/Article/details/gtljabjaea.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.wangdashe.top/Article/details/gtsuqaiehm.html

[T23] Swift：函数
来源：http://dali.shzxlz.cn/Article/details/gtaiclqavb.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.jyoumei.cn/Article/details/gtgtabwfdv.html

[T24] Swift：闭包
来源：http://dali.nwbrower.top/Article/details/gtlxmwbdzo.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gtzohrrxrp.html

[T25] Swift：结构体
来源：http://dali.shuidangran.top/Article/details/gtugpezrvq.html

struct P { var x: Int }
来源：http://dali.kuanghao11.cn/Article/details/gtynhgpklv.html

[T26] Swift：类与重写
来源：http://dali.zhixingplan.top/Article/details/gtkgoyvgju.html

class A: Base { override func f() {} }
来源：http://dali.wangshuangyany.cn/Article/details/gtfzdzjbpp.html

[T27] Swift：错误处理
来源：http://dali.hfpthk.cn/Article/details/gtdgbwsgqx.html

do { try f() } catch { print(error) }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzdakrclb.html

[T28] Swift：枚举
来源：http://dali.birdmap.top/Article/details/gtjqrivlcy.html

enum Color { case red, green }
来源：http://dali.yvedp.cn/Article/details/gtpvtdxwvk.html

[T29] Swift：guard 提前返回
来源：http://dali.andypj.xyz/Article/details/gtcuuvkdhh.html

guard let x = opt else { return }
来源：http://dali.hammf.cn/Article/details/gthqgmvoza.html

[T30] Swift：协议
来源：http://dali.haohaochexian.top/Article/details/gtnxlhxuaf.html

protocol Shape { func area() -> Double }
来源：http://dali.dashuyun.cn/Article/details/gtqkdourti.html

[T31] Lua：Hello World
来源：http://dali.feifeiyinyue.top/Article/details/gtwplaonev.html

print("Hello")
来源：http://dali.jqgufenzy.top/Article/details/gtqvicfiey.html

[T32] Lua：局部变量
来源：http://dali.cheryme.top/Article/details/gtzsyavedq.html

local a = 1
来源：http://dali.c1oappe.top/Article/details/gtjlncsbmb.html

[T33] Lua：表（数组）
来源：http://dali.guowangkeji.top/Article/details/gtazmdjkkw.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.iojbl.cn/Article/details/gtauobqwxw.html

[T34] Lua：遍历表
来源：http://dali.316326.xyz/Article/details/gtuaadccve.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.smart0.xyz/Article/details/gtaqjktxmw.html

[T35] Lua：字典表
来源：http://dali.gotoacloud.top/Article/details/gtxwibcpva.html

local d = { a = 1 };  d.b = 2
来源：http://dali.gaohongyu789.top/Article/details/gteuuzwbks.html

[T36] Lua：函数
来源：http://dali.sweek.top/Article/details/gtwvaigwsg.html

function add(a, b) return a + b end
来源：http://dali.xinyue.icu/Article/details/gtyhshjpoq.html

[T37] Lua：字符串拼接
来源：http://dali.fzhhl.top/Article/details/gtsusfyfit.html

"a" .. "b"
来源：http://dali.jinghuilouyu.cn/Article/details/gtjpkihhvc.html

[T38] Lua：条件
来源：http://dali.fengsongda.top/Article/details/gtrijflums.html

if x > 0 then print("正") end
来源：http://dali.ydzc1.top/Article/details/gtgpuupfvj.html

[T39] Lua：模式匹配
来源：http://dali.zhongyouzk.top/Article/details/gteakhomjx.html

string.find(s, "%d+")
来源：http://dali.jqgfzy.top/Article/details/gtylikvkpo.html

[T40] Lua：元表
来源：http://dali.vqdsnc.cn/Article/details/gtednaoafx.html

setmetatable({}, { __index = base })
来源：http://dali.yuanzhike.top/Article/details/gtutqvolus.html

[T41] Perl：Hello World
来源：http://dali.sweek.top/Article/details/gtptuyhfkt.html

print "Hello\n";
来源：http://dali.hfpthk.cn/Article/details/gtnujpnyts.html

[T42] Perl：变量类型
来源：http://dali.pycfn.com/Article/details/gtnagsvoxf.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.cashguo.top/Article/details/gtsqckssup.html

[T43] Perl：字符串插值
来源：http://dali.zycfv.cn/Article/details/gtcbefamqv.html

"值: $a"
来源：http://dali.shangyingyoupin.top/Article/details/gtocvgjxva.html

[T44] Perl：条件
来源：http://dali.yj202588.top/Article/details/gtrxpjwgje.html

if ($a > 0) { print "正"; }
来源：http://dali.ybcxt.top/Article/details/gtzhseiixk.html

[T45] Perl：数组遍历
来源：http://dali.nwbrower.top/Article/details/gtdnjtmrip.html

for my $x (@arr) { print $x; }
来源：http://dali.ppjwa.cn/Article/details/gtyxoudgef.html

[T46] Perl：哈希操作
来源：http://dali.pycfn.com/Article/details/gtellgifxw.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zycfv.cn/Article/details/gtgrcizokk.html

[T47] Perl：正则捕获
来源：http://dali.cdnleiting.top/Article/details/gtlymgvmul.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.cashguo.top/Article/details/gtgoxwkvnu.html

[T48] Perl：正则替换
来源：http://dali.jqgfzy.top/Article/details/gtpognlcvs.html

$s =~ s/old/new/g;
来源：http://dali.sufxvd.cn/Article/details/gtzdaezdsi.html

[T49] Perl：函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxsqjfxxk.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.tian-w.cn/Article/details/gthewiufwh.html

[T50] Perl：逐行读文件
来源：http://dali.tianlin.xyz/Article/details/gtjhkmpuxy.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.xylfe.cn/Article/details/gtryeyghzj.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.yuxming.cn/Article/details/gtjmhokvbd.html

[T51] Scala：Hello World
来源：http://dali.gogol.net.cn/Article/details/gttxsfxhhg.html

println("Hello")
来源：http://dali.cucudq.cn/Article/details/gtdmqrwvif.html

[T52] Scala：变量
来源：http://dali.9152youxi.cn/Article/details/gtkipbdtzv.html

val a = 1;  var b = 2
来源：http://dali.xuetiantiany.cn/Article/details/gtbqczxqlx.html

[T53] Scala：字符串插值
来源：http://dali.mhx1999.top/Article/details/gtqdhlbbwn.html

s"值: $b"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrgtfangk.html

[T54] Scala：集合映射
来源：http://dali.yj202588.top/Article/details/gtaumerlec.html


<!-- 参考信息 -->