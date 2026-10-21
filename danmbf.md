代发 wailian999

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.gotoacloud.top/Article/details/gtkyauahvd.html

[R54] 比较两个文件
来源：http://dali.zdqjudy.top/Article/details/gtkvabmqwb.html

diff a.txt b.txt
来源：http://dali.guowangkeji.top/Article/details/gtzekqtenn.html

[R55] 压缩与解压
来源：http://dali.tian-w.cn/Article/details/gtlwcwayvh.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.cdnleiting.top/Article/details/gtitpxtips.html

[R56] 远程拷贝
来源：http://dali.xinyue.icu/Article/details/gtyqcgasfi.html

scp file user@host:/path/
来源：http://dali.jiagoushi.top/Article/details/gtytacucvi.html

[R57] 远程执行命令
来源：http://dali.yuanzhike.top/Article/details/gtydtffydl.html

ssh user@host 'uptime'
来源：http://dali.shzxlz.cn/Article/details/gtygubctge.html

[R58] 下载文件
来源：http://dali.quarkkingdee.top/Article/details/gtlleubomr.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zdqjudy.top/Article/details/gtqqgcfegk.html

[R59] 发 POST JSON
来源：http://dali.zdqjudy.top/Article/details/gtnjfsscvg.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.shanyushiyangtech.top/Article/details/gthrlqwhhq.html

[R60] 只看 HTTP 状态码
来源：http://dali.snrcjt.cn/Article/details/gterkapfpo.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhiwuduotai.top/Article/details/gtesetpden.html

[R61] 磁盘占用
来源：http://dali.zhengqikj.top/Article/details/gtjnnzcnyh.html

df -h;  du -sh *
来源：http://dali.iojbl.cn/Article/details/gtmxkpifzz.html

[R62] 找最占空间的文件
来源：http://dali.xuetiantiany.cn/Article/details/gthhdhivoj.html

du -ah . | sort -rh | head -10
来源：http://dali.ybcxt.top/Article/details/gtqigkgkmp.html

[R63] 内存与进程
来源：http://dali.snrcjt.cn/Article/details/gtnmehlfty.html

free -h;  ps aux | grep nginx
来源：http://dali.fzhhl.top/Article/details/gtjdkcwzdv.html

[R64] 结束进程
来源：http://dali.meibo888.top/Article/details/gtrgbigihq.html

kill -9 $(pgrep -f app.py)
来源：http://dali.yueranfly.top/Article/details/gtonacewrz.html

[R65] 查看端口占用
来源：http://dali.ywan-chungtsiang.top/Article/details/gtafwiuuzu.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.yanxiufei.cn/Article/details/gtmyfkijho.html

[R66] 定时任务
来源：http://dali.jinqigfzy.top/Article/details/gtdhvksudc.html

crontab -e;  crontab -l
来源：http://dali.zycfv.cn/Article/details/gtswnhyjoo.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gtkobekbvm.html

openssl rand -hex 16
来源：http://dali.shanyushiyangtech.top/Article/details/gtwdnhjjog.html

[R68] 计算文件校验值
来源：http://dali.yanxiufei.cn/Article/details/gtuvrmebep.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zycfv.cn/Article/details/gtdngvkaku.html

[R69] 生成随机密码
来源：http://dali.kuanghao11.cn/Article/details/gtqzkvmgta.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhiwuduotai.top/Article/details/gtesnfdflc.html

[R70] 时间戳与互转
来源：http://dali.zycfv.cn/Article/details/gteesvpqnq.html

date +%s;  date -d @1700000000
来源：http://dali.dianchejie.cn/Article/details/gtoqvtvzjp.html

[R71] 日期格式化
来源：http://dali.cheryme.top/Article/details/gtvfkzeuxl.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.aibaodan.cn/Article/details/gthttlzkkq.html

[R72] 等待端口就绪
来源：http://dali.nanxuanxn.top/Article/details/gtjhrrzkls.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhixingplan.top/Article/details/gtbooewhpe.html

[R73] 分割大日志
来源：http://dali.yj202588.top/Article/details/gtsxdzpcoa.html

split -l 1000 big.log part_
来源：http://dali.tian-w.cn/Article/details/gtnmhzjqkc.html

[R74] 批量重命名
来源：http://dali.daria6918.cn/Article/details/gtlfkutonc.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.jyoumei.cn/Article/details/gtucqdwoxw.html

[R75] 导出环境变量
来源：http://dali.zhixingplan.top/Article/details/gtprhudyro.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.redwolf501.top/Article/details/gtbeunuxgj.html

[R76] 使用临时文件
来源：http://dali.birdmap.top/Article/details/gtqzutsafa.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.quarkkingdee.top/Article/details/gtelhkepdp.html

[R77] 读取用户输入
来源：http://dali.hnqzz.top/Article/details/gtsgsdahdi.html

read -rp "请输入: " ans
来源：http://dali.daxiang520.top/Article/details/gthopfnmbk.html

[R78] 交互式菜单
来源：http://dali.guannengcc.top/Article/details/gttonptetj.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhongyouzk.top/Article/details/gtojciskpv.html

[R79] 解析命令行选项
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaqvbkvjp.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.pycfn.com/Article/details/gtubpsunyb.html

[R80] 查看脚本执行耗时
来源：http://dali.jlsjyb.cn/Article/details/gtgnyftnch.html

time ./run.sh
来源：http://dali.zhoulong.xyz/Article/details/gtlhrqwvyv.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtgazadnnh.html

S. C / C++ 专题
来源：http://dali.9152youxi.cn/Article/details/gtwrcjtppd.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtpwwsyfcg.html

[S01] C：Hello World
来源：http://dali.jianghu66.top/Article/details/gtinqcamtd.html

#include <stdio.h>
来源：http://dali.shangyingyoupin.top/Article/details/gtcyfjtjty.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.sweek.top/Article/details/gthlrxdaig.html

[S02] C：变量与格式化输出
来源：http://dali.zdqjudy.top/Article/details/gtlprqtsqv.html

int a = 10; printf("%d\n", a);
来源：http://dali.9152youxi.cn/Article/details/gtxapgmook.html

[S03] C：读入整数
来源：http://dali.nwbrower.top/Article/details/gtiiyntlqt.html

int x; scanf("%d", &x);
来源：http://dali.yongpay.top/Article/details/gtdtvzrxgb.html

[S04] C：字符串复制
来源：http://dali.ehwqpu.com/Article/details/gtstrujdfw.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.c1oappe.top/Article/details/gtzfebvfad.html

[S05] C：字符串长度
来源：http://dali.shuidangran.top/Article/details/gtkturkquz.html

strlen(s)
来源：http://dali.jyoumei.cn/Article/details/gtpsnveazz.html

[S06] C：字符串比较
来源：http://dali.fzhhl.top/Article/details/gtitullvqv.html

strcmp(a, b) == 0
来源：http://dali.hnxiangtu.top/Article/details/gteheugklt.html

[S07] C：数组遍历求和
来源：http://dali.c1oappe.top/Article/details/gtbdfwhujz.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.chenjidiqi.icu/Article/details/gtkhrqontv.html

[S08] C：动态内存分配与释放
来源：http://dali.dianchejie.cn/Article/details/gtgmbdvlke.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.c1oappe.top/Article/details/gtnvllswok.html

[S09] C：结构体定义与初始化
来源：http://dali.sysykeji.top/Article/details/gtzvbpuzeu.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.ppjwa.cn/Article/details/gtnxajpsvb.html

[S10] C：指针与解引用
来源：http://dali.nanxuanxn.top/Article/details/gtucuauvro.html

int *p = &a;  *p = 5;
来源：http://dali.fengsongda.top/Article/details/gtwtvjaznr.html

[S11] C：逐行读文件
来源：http://dali.wangdashe.top/Article/details/gtvrrnrsru.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.havefunace.top/Article/details/gtohzxurot.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.hongshengwenyu.top/Article/details/gtrldcakjj.html

fclose(f);
来源：http://dali.smart0.xyz/Article/details/gtlwxdsctp.html

[S12] C：写文件
来源：http://dali.0kj1m.cn/Article/details/gtehtomczh.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.hongshengwenyu.top/Article/details/gtuayfyjmn.html

[S13] C：宏定义
来源：http://dali.sysykeji.top/Article/details/gtwzibavcg.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.gaohongyu789.top/Article/details/gtatszjypr.html

[S14] C：枚举
来源：http://dali.yuxming.cn/Article/details/gtwxkououh.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.svipenyu.cn/Article/details/gtzlmzxfoq.html

[S15] C：类型转换
来源：http://dali.xziqi.cn/Article/details/gtkwyetrvh.html

(double) a / b
来源：http://dali.yonumen.top/Article/details/gtxhecsqvz.html

[S16] C：位操作置位
来源：http://dali.c1oappe.top/Article/details/gtrzwpbvuq.html

x |= (1 << 3);
来源：http://dali.nwbrower.top/Article/details/gtywrbxuzh.html

[S17] C：安全拼接字符串
来源：http://dali.cdnleiting.top/Article/details/gtmmcpjnbd.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.redwolf501.top/Article/details/gtrwbsdmxm.html

[S18] C：命令行参数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbmuobirg.html

int main(int argc, char **argv)
来源：http://dali.0kj1m.cn/Article/details/gtcrdribza.html

[S19] C：快速排序
来源：http://dali.hammf.cn/Article/details/gtxfpgvrqf.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.xinyue.icu/Article/details/gtnwhyejgt.html

[S20] C：二分查找
来源：http://dali.iojbl.cn/Article/details/gtvjenysvm.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.xuanzx.com/Article/details/gtgwlbawgs.html

[S21] C：字符类别判断
来源：http://dali.smart0.xyz/Article/details/gtrbewhdkj.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.mhx1999.top/Article/details/gtqovyszfy.html

[S22] C：字符串转数字
来源：http://dali.sweek.top/Article/details/gtiwzzgdkc.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.fengsongda.top/Article/details/gtwlyxcppi.html

[S23] C：随机数
来源：http://dali.hongshengwenyu.top/Article/details/gtiiclsqqp.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.wangdashe.top/Article/details/gtqiyonqrm.html

[S24] C：获取本地时间
来源：http://dali.chenzaomai.com/Article/details/gtvblxfaee.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.hysaishi.cn/Article/details/gtjaxxqkyg.html

[S25] C：内存拷贝
来源：http://dali.hywenlv.cn/Article/details/gtqjhoxaxc.html

memcpy(dst, src, n);
来源：http://dali.jinqigfzy.top/Article/details/gtgasrutuz.html

[S26] C：内存清零
来源：http://dali.smart0.xyz/Article/details/gtvjlhbhrx.html

memset(a, 0, sizeof a);
来源：http://dali.jlsjyb.cn/Article/details/gtlpsqosii.html

[S27] C：定义常量
来源：http://dali.ehwqpu.com/Article/details/gtqkftfset.html

const double PI = 3.14159;
来源：http://dali.ydzc1.top/Article/details/gthgyooknt.html

[S28] C：静态变量
来源：http://dali.smart0.xyz/Article/details/gtkrwbuuye.html

static int counter = 0;
来源：http://dali.vqdsnc.cn/Article/details/gtlbhzfiwc.html

[S29] C：变参函数
来源：http://dali.jianghu66.top/Article/details/gtdhslkwks.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.hywenlv.cn/Article/details/gtoqlqhndl.html

[S30] C：头文件保护
来源：http://dali.shzxlz.cn/Article/details/gtranszngz.html

#ifndef X_H
来源：http://dali.dianchejie.cn/Article/details/gtauxwxhqd.html

#define X_H
来源：http://dali.yueranfly.top/Article/details/gtpbnfvfav.html

#endif
来源：http://dali.fengsongda.top/Article/details/gtpylpqbal.html

[S31] C++：Hello World
来源：http://dali.jqgfzy.top/Article/details/gtnmuykrpg.html

#include <iostream>
来源：http://dali.guannengcc.top/Article/details/gtzjitzffi.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.gotoacloud.top/Article/details/gtljihvdxj.html

[S32] C++：字符串
来源：http://dali.hfpthk.cn/Article/details/gtnicrepaz.html

std::string s = "hi";  s += "!";
来源：http://dali.iojbl.cn/Article/details/gttkrpowpu.html

[S33] C++：vector 增删
来源：http://dali.pycfn.com/Article/details/gtjbtqvzty.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.pengpengdd.cyou/Article/details/gtgnotlwoj.html

[S34] C++：遍历 vector
来源：http://dali.dashuyun.cn/Article/details/gtwsyvwqih.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.jinqigufen.top/Article/details/gtixauhgvi.html

[S35] C++：map
来源：http://dali.zhengqikj.top/Article/details/gtmcvwptbx.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zycfv.cn/Article/details/gtsrczcuvw.html

[S36] C++：unordered_map
来源：http://dali.fzhhl.top/Article/details/gtphaovmyk.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhongyouzk.top/Article/details/gtrprbpjhk.html

[S37] C++：set
来源：http://dali.jyoumei.cn/Article/details/gtucjxpchy.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.chenlongwang.top/Article/details/gtyjvsxgee.html

[S38] C++：排序
来源：http://dali.andypj.xyz/Article/details/gtffddidwq.html

std::sort(v.begin(), v.end());
来源：http://dali.gogol.net.cn/Article/details/gtxbzbhhet.html

[S39] C++：自定义比较器排序
来源：http://dali.gaohongyu789.top/Article/details/gtlsashdbd.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.gaohongyu789.top/Article/details/gtqohztmat.html

[S40] C++：查找元素
来源：http://dali.jinqigfzy.top/Article/details/gtmaxwxtbs.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhengqikj.top/Article/details/gtuegcznah.html

[S41] C++：类与构造函数
来源：http://dali.chenlongwang.top/Article/details/gtzskbbhez.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhiwuduotai.top/Article/details/gtlhhojmwk.html

[S42] C++：继承与虚函数
来源：http://dali.cdnleiting.top/Article/details/gtwwuedyzl.html

class B : public Base { public: void f() override {} };
来源：http://dali.snrcjt.cn/Article/details/gtbkkdjing.html

[S43] C++：智能指针
来源：http://dali.jinghuilouyu.cn/Article/details/gtnblchncj.html

auto p = std::make_unique<int>(5);
来源：http://dali.aizwys.cn/Article/details/gtxmigeyqa.html

[S44] C++：引用传参
来源：http://dali.ybcxt.top/Article/details/gtqgvpyypk.html

void inc(int &x) { ++x; }
来源：http://dali.sweek.top/Article/details/gtuclfhsvr.html

[S45] C++：lambda
来源：http://dali.shangyingyoupin.top/Article/details/gtdzchwxez.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.shanyushiyangtech.top/Article/details/gtpazsltnl.html

[S46] C++：函数模板
来源：http://dali.jlsjyb.cn/Article/details/gtlrkexghy.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.smart0.xyz/Article/details/gtzwvubrso.html

[S47] C++：结构化绑定遍历
来源：http://dali.wangshuangyany.cn/Article/details/gtcgpntngg.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.yonumen.top/Article/details/gtzznefqdj.html

[S48] C++：逐行读文件
来源：http://dali.xuetiantiany.cn/Article/details/gtnuaedslq.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.kuanghao11.cn/Article/details/gtqcxbcwqs.html

while (std::getline(in, line)) { }
来源：http://dali.iojbl.cn/Article/details/gtcmfckyrp.html

[S49] C++：写文件
来源：http://dali.cqqwz.cn/Article/details/gtdeuyxrby.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.shanyushiyangtech.top/Article/details/gtcmmnryok.html

[S50] C++：格式化数字
来源：http://dali.yvedp.cn/Article/details/gtzkeaauxk.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.gzhubu.top/Article/details/gtfeituaok.html

[S51] C++：显式类型转换
来源：http://dali.xziqi.cn/Article/details/gtoyblssus.html

static_cast<double>(a) / b
来源：http://dali.hnqzz.top/Article/details/gtqxapcrfn.html

[S52] C++：const 与 noexcept
来源：http://dali.jyoumei.cn/Article/details/gteuzxlhgj.html

int size() const noexcept { return n_; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtljgpysio.html

[S53] C++：移动语义
来源：http://dali.redwolf501.top/Article/details/gtvpshalaa.html

std::vector<int> w = std::move(v);
来源：http://dali.snrcjt.cn/Article/details/gtyshuoljn.html

[S54] C++：异常处理
来源：http://dali.tianlin.xyz/Article/details/gtsxelyfxo.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.yueranfly.top/Article/details/gtucpvrlku.html

[S55] C++：结构化绑定
来源：http://dali.dashuyun.cn/Article/details/gtslqmcutp.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.chenlongwang.top/Article/details/gtlijyeuuy.html

[S56] C++：optional
来源：http://dali.sysykeji.top/Article/details/gtdmbcsmkm.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.dashuyun.cn/Article/details/gtcpfonkyz.html

[S57] C++：编译期常量
来源：http://dali.cqqwz.cn/Article/details/gtwjzojsgy.html

constexpr int N = 10;
来源：http://dali.yj20258.top/Article/details/gtryzknatb.html

[S58] C++：命名空间
来源：http://dali.sufxvd.cn/Article/details/gtietbfdco.html

namespace ns { int f() { return 1; } }
来源：http://dali.pengpengdd.cyou/Article/details/gtcdywxdmz.html

[S59] C++：静态断言
来源：http://dali.birdmap.top/Article/details/gtoojfmiyn.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.316326.xyz/Article/details/gtkgfoxqbj.html

[S60] C++：遍历并删除元素
来源：http://dali.quarkkingdee.top/Article/details/gtcgsjcyew.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.daxiang520.top/Article/details/gtxjmztbvr.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtrlnydazj.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.hfpthk.cn/Article/details/gtaxszondy.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gthodukdmi.html

[T01] Kotlin：Hello World
来源：http://dali.yj20258888.top/Article/details/gtodjgnrjl.html

println("Hello")
来源：http://dali.yuanzhike.top/Article/details/gtquohfxmu.html

[T02] Kotlin：变量
来源：http://dali.ppjwa.cn/Article/details/gtckgretxm.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.gotoacloud.top/Article/details/gtcekqaxtj.html

[T03] Kotlin：字符串模板
来源：http://dali.xinyue.icu/Article/details/gtovbrycwg.html

"值: $b"
来源：http://dali.316326.xyz/Article/details/gtvsuneeiw.html

[T04] Kotlin：空安全
来源：http://dali.jinqigufen.top/Article/details/gtbspvxtnm.html

val n: String? = null;  n?.length
来源：http://dali.ppjwa.cn/Article/details/gtqcynycoz.html

[T05] Kotlin：when 表达式
来源：http://dali.ivvv.top/Article/details/gtboauuakr.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtojahkjot.html

[T06] Kotlin：集合映射
来源：http://dali.jianghu66.top/Article/details/gtxqwsgvuf.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.dianchejie.cn/Article/details/gtwovtotef.html

[T07] Kotlin：集合过滤
来源：http://dali.xinyue.icu/Article/details/gtkzruiuqs.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.nwbrower.top/Article/details/gttugfosuf.html

[T08] Kotlin：数据类
来源：http://dali.jinqigfzy.top/Article/details/gtptokdxpd.html

data class User(val name: String, val age: Int)
来源：http://dali.daxiang520.top/Article/details/gtlazboidb.html

[T09] Kotlin：扩展函数
来源：http://dali.jianghu66.top/Article/details/gtvvnxkajx.html

fun String.exclaim() = this + "!"
来源：http://dali.andypj.xyz/Article/details/gtwhhoyogr.html

[T10] Kotlin：默认参数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtskzhgmdi.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.yvedp.cn/Article/details/gtluvyjrgp.html

[T11] Kotlin：协程
来源：http://dali.jlsjyb.cn/Article/details/gtgfymkqfr.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.9152youxi.cn/Article/details/gtzddigcnt.html

[T12] Kotlin：解构声明
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtabvioyos.html

val (a, b) = Pair(1, 2)
来源：http://dali.cucudq.cn/Article/details/gtgghwfhzt.html

[T13] Kotlin：只读 Map
来源：http://dali.kuanghao11.cn/Article/details/gtdzzejapm.html

val m = mapOf("a" to 1)
来源：http://dali.fzhhl.top/Article/details/gtjvrhtwha.html

[T14] Kotlin：循环
来源：http://dali.yonumen.top/Article/details/gticoyjeyt.html

for (i in 1..10) println(i)
来源：http://dali.gotoacloud.top/Article/details/gtridxrqwk.html

[T15] Kotlin：接口
来源：http://dali.zhoulong.xyz/Article/details/gtofcjzvcg.html

interface Shape { fun area(): Double }
来源：http://dali.cashguo.top/Article/details/gtpdmxwqxk.html

[T16] Swift：Hello World
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvenoigxt.html

print("Hello")
来源：http://dali.bjfxy.top/Article/details/gtlnzrajzo.html

[T17] Swift：变量与常量
来源：http://dali.yueranfly.top/Article/details/gthkpzevom.html

var a = 1;  let b = 2
来源：http://dali.zdqjudy.top/Article/details/gtrgekqcvs.html

[T18] Swift：字符串插值
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcxnggmsr.html

"值: \(b)"
来源：http://dali.vqdsnc.cn/Article/details/gtvjovtzrs.html

[T19] Swift：可选绑定
来源：http://dali.hnqzz.top/Article/details/gtpjnpaven.html

if let n = opt { print(n) }
来源：http://dali.shzxlz.cn/Article/details/gtottycecr.html

[T20] Swift：数组操作
来源：http://dali.zdqjudy.top/Article/details/gttcsflmvv.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.hammf.cn/Article/details/gtmqnxxqvi.html

[T21] Swift：遍历
来源：http://dali.hongshengwenyu.top/Article/details/gtyhhrsvld.html

for x in a { print(x) }
来源：http://dali.hfpthk.cn/Article/details/gtvqzcexka.html

[T22] Swift：字典
来源：http://dali.ehwqpu.com/Article/details/gtrktypekn.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.jqgfzy.top/Article/details/gtwtldkkvi.html

[T23] Swift：函数
来源：http://dali.guannengcc.top/Article/details/gtxkoafnlp.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.ppjwa.cn/Article/details/gtjylqeamm.html

[T24] Swift：闭包
来源：http://dali.svipenyu.cn/Article/details/gticbakbvw.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.jinqigfzy.top/Article/details/gtwyubowlk.html

[T25] Swift：结构体
来源：http://dali.yvedp.cn/Article/details/gtzhqmwmpu.html

struct P { var x: Int }
来源：http://dali.zhongyouzk.top/Article/details/gtkloqqzhr.html

[T26] Swift：类与重写
来源：http://dali.hysaishi.cn/Article/details/gthxbdzfay.html

class A: Base { override func f() {} }
来源：http://dali.meibo888.top/Article/details/gtobepvlgq.html

[T27] Swift：错误处理
来源：http://dali.yongpay.top/Article/details/gtdqaqoqzr.html

do { try f() } catch { print(error) }
来源：http://dali.guannengcc.top/Article/details/gtmpqbaoky.html

[T28] Swift：枚举
来源：http://dali.jiagoushi.top/Article/details/gtynixzcmz.html

enum Color { case red, green }
来源：http://dali.iojbl.cn/Article/details/gtwftbwgpo.html

[T29] Swift：guard 提前返回
来源：http://dali.gaohongyu789.top/Article/details/gtltouthvu.html

guard let x = opt else { return }
来源：http://dali.pengpengdd.cyou/Article/details/gtiqxzryqe.html

[T30] Swift：协议
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaaihetir.html

protocol Shape { func area() -> Double }
来源：http://dali.ivvv.top/Article/details/gtbroehcgb.html

[T31] Lua：Hello World
来源：http://dali.smart0.xyz/Article/details/gthzjzinyr.html

print("Hello")
来源：http://dali.0kj1m.cn/Article/details/gtbirqkflt.html

[T32] Lua：局部变量
来源：http://dali.sweek.top/Article/details/gtrqnmpidu.html

local a = 1
来源：http://dali.chenlongwang.top/Article/details/gtpyneqrja.html

[T33] Lua：表（数组）
来源：http://dali.daxiang520.top/Article/details/gtxapqlwnj.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.dianchejie.cn/Article/details/gtagxcmeqz.html

[T34] Lua：遍历表
来源：http://dali.sysykeji.top/Article/details/gtrmfqrife.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.cheryme.top/Article/details/gtvkpkzjka.html

[T35] Lua：字典表
来源：http://dali.zhoulong.xyz/Article/details/gttlzrgcxh.html

local d = { a = 1 };  d.b = 2
来源：http://dali.jqgufenzy.top/Article/details/gtbqqsbptv.html

[T36] Lua：函数
来源：http://dali.nanxinkj.top/Article/details/gtyiknujyw.html

function add(a, b) return a + b end
来源：http://dali.yueranfly.top/Article/details/gtojmloyio.html

[T37] Lua：字符串拼接
来源：http://dali.aizwys.cn/Article/details/gtkvidhbxj.html

"a" .. "b"
来源：http://dali.cqqwz.cn/Article/details/gtjytcgpas.html

[T38] Lua：条件
来源：http://dali.birdmap.top/Article/details/gtvyvedrsl.html

if x > 0 then print("正") end
来源：http://dali.hongshengwenyu.top/Article/details/gtvikzqpel.html

[T39] Lua：模式匹配
来源：http://dali.zhoulong.xyz/Article/details/gtainwuceo.html

string.find(s, "%d+")
来源：http://dali.tianlin.xyz/Article/details/gtfvwpjabi.html

[T40] Lua：元表
来源：http://dali.ydzc1.top/Article/details/gtguselwws.html

setmetatable({}, { __index = base })
来源：http://dali.yj202588.top/Article/details/gtqbpteacr.html

[T41] Perl：Hello World
来源：http://dali.fengsongda.top/Article/details/gtkxwuahxf.html

print "Hello\n";
来源：http://dali.c1oappe.top/Article/details/gtnvsgejab.html

[T42] Perl：变量类型
来源：http://dali.zhengqikj.top/Article/details/gtloxnspml.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.tianlin.xyz/Article/details/gtcxzjiibx.html

[T43] Perl：字符串插值
来源：http://dali.hongshengwenyu.top/Article/details/gtjhxtzhgg.html

"值: $a"
来源：http://dali.bjfxy.top/Article/details/gtxkelikof.html

[T44] Perl：条件
来源：http://dali.jlsjyb.cn/Article/details/gtmabnykzb.html

if ($a > 0) { print "正"; }
来源：http://dali.dashuyun.cn/Article/details/gtcmwtqbxe.html

[T45] Perl：数组遍历
来源：http://dali.chenzaomai.com/Article/details/gtthgbpauj.html

for my $x (@arr) { print $x; }
来源：http://dali.zdqjudy.top/Article/details/gtzxgqsbye.html

[T46] Perl：哈希操作
来源：http://dali.aibaodan.cn/Article/details/gtymzbwyns.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.cucudq.cn/Article/details/gtsoblpcik.html

[T47] Perl：正则捕获
来源：http://dali.dashuyun.cn/Article/details/gtiglcewzh.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.tanke756.top/Article/details/gtaqeorlag.html

[T48] Perl：正则替换
来源：http://dali.chenlongwang.top/Article/details/gtmsopcaeo.html

$s =~ s/old/new/g;
来源：http://dali.shzxlz.cn/Article/details/gtlalcjtrz.html

[T49] Perl：函数
来源：http://dali.cucudq.cn/Article/details/gteelkpwol.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.daria6918.cn/Article/details/gttptubgyt.html

[T50] Perl：逐行读文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxtgrwacu.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.gogol.net.cn/Article/details/gtqeqhxdmi.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhoulong.xyz/Article/details/gtweyvxinr.html

[T51] Scala：Hello World
来源：http://dali.cqqwz.cn/Article/details/gtkpfkjdyi.html

println("Hello")
来源：http://dali.smart0.xyz/Article/details/gtfpmgipyf.html

[T52] Scala：变量
来源：http://dali.hongshengwenyu.top/Article/details/gtmcofshfr.html

val a = 1;  var b = 2
来源：http://dali.yj202588.top/Article/details/gtbmklcrgz.html

[T53] Scala：字符串插值
来源：http://dali.zycfv.cn/Article/details/gtlsfvfcbr.html

s"值: $b"
来源：http://dali.aibaodan.cn/Article/details/gtcqppgmuo.html

[T54] Scala：集合映射
来源：http://dali.andypj.xyz/Article/details/gtodanilsx.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.quarkkingdee.top/Article/details/gtjcwilqdp.html

[T55] Scala：集合过滤
来源：http://dali.gzhubu.top/Article/details/gtaapzlzms.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.gaohongyu789.top/Article/details/gtjjfbiqnc.html

[T56] Scala：样例类
来源：http://dali.sxryk.cn/Article/details/gtvoxvvujq.html


<!-- 参考信息 -->