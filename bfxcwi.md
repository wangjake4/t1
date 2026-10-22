代发 wailian999

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.jqgufenzy.top/Article/details/gtmrjrqtqk.html

[R52] 统计行数
来源：http://dali.jinqigfzy.top/Article/details/gtouwxulpz.html

wc -l a.txt
来源：http://dali.daria6918.cn/Article/details/gthdgfzlhz.html

[R53] 查看文件头与实时尾
来源：http://dali.c1oappe.top/Article/details/gtlibjnjkg.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.meibo888.top/Article/details/gtbrggohvc.html

[R54] 比较两个文件
来源：http://dali.redwolf501.top/Article/details/gtgiwbeqdv.html

diff a.txt b.txt
来源：http://dali.zhongyouzk.top/Article/details/gtmwwraxkq.html

[R55] 压缩与解压
来源：http://dali.zhixingplan.top/Article/details/gttbvozkpc.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.jianghu66.top/Article/details/gtlkngpotw.html

[R56] 远程拷贝
来源：http://dali.jqgufenzy.top/Article/details/gtewqgjcie.html

scp file user@host:/path/
来源：http://dali.hammf.cn/Article/details/gtxdefuaxm.html

[R57] 远程执行命令
来源：http://dali.smart0.xyz/Article/details/gtiskfmzmy.html

ssh user@host 'uptime'
来源：http://dali.yuxming.cn/Article/details/gtronwjwha.html

[R58] 下载文件
来源：http://dali.fengsongda.top/Article/details/gtvglaczdw.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.aibaodan.cn/Article/details/gtifehguht.html

[R59] 发 POST JSON
来源：http://dali.daria6918.cn/Article/details/gtwfdwelsy.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.pycfn.com/Article/details/gtiwppvtpi.html

[R60] 只看 HTTP 状态码
来源：http://dali.yueranfly.top/Article/details/gtvmtgpxpq.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.haohaochexian.top/Article/details/gtdokispep.html

[R61] 磁盘占用
来源：http://dali.zhongyouzk.top/Article/details/gthdrucque.html

df -h;  du -sh *
来源：http://dali.meibo888.top/Article/details/gtucjydbru.html

[R62] 找最占空间的文件
来源：http://dali.iojbl.cn/Article/details/gtqhcoksgr.html

du -ah . | sort -rh | head -10
来源：http://dali.sufxvd.cn/Article/details/gttliqhzit.html

[R63] 内存与进程
来源：http://dali.zhixingplan.top/Article/details/gtipknezsu.html

free -h;  ps aux | grep nginx
来源：http://dali.jinqigfzy.top/Article/details/gtuuxobulb.html

[R64] 结束进程
来源：http://dali.zhiwuduotai.top/Article/details/gtelixxqkk.html

kill -9 $(pgrep -f app.py)
来源：http://dali.bjfxy.top/Article/details/gtqtkahutu.html

[R65] 查看端口占用
来源：http://dali.jinqigfzy.top/Article/details/gtyrttqief.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.aibaodan.cn/Article/details/gtfwtgfrfs.html

[R66] 定时任务
来源：http://dali.316326.xyz/Article/details/gtjpualcha.html

crontab -e;  crontab -l
来源：http://dali.zhongyouzk.top/Article/details/gtbwqsyffe.html

[R67] 生成随机十六进制串
来源：http://dali.cucudq.cn/Article/details/gtrduqpsoq.html

openssl rand -hex 16
来源：http://dali.yanxiufei.cn/Article/details/gtarvbpfzc.html

[R68] 计算文件校验值
来源：http://dali.redwolf501.top/Article/details/gtmesbimci.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.yanxiufei.cn/Article/details/gtywrbgniq.html

[R69] 生成随机密码
来源：http://dali.hammf.cn/Article/details/gtoamkamhr.html

head -c 16 /dev/urandom | base64
来源：http://dali.ppjwa.cn/Article/details/gtzoakgxke.html

[R70] 时间戳与互转
来源：http://dali.jinqigfzy.top/Article/details/gtpqtlcovt.html

date +%s;  date -d @1700000000
来源：http://dali.zhengqikj.top/Article/details/gtezisngnt.html

[R71] 日期格式化
来源：http://dali.yuxming.cn/Article/details/gtfwxjvfjk.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.fzhhl.top/Article/details/gtzakkijix.html

[R72] 等待端口就绪
来源：http://dali.yuanzhike.top/Article/details/gtxrdmetql.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.yongpay.top/Article/details/gttpgqxona.html

[R73] 分割大日志
来源：http://dali.vqdsnc.cn/Article/details/gtjfkworoj.html

split -l 1000 big.log part_
来源：http://dali.ydzc1.top/Article/details/gtchzfpndt.html

[R74] 批量重命名
来源：http://dali.nwbrower.top/Article/details/gtoaaxddrh.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.cashguo.top/Article/details/gtreoshori.html

[R75] 导出环境变量
来源：http://dali.nanxuanxn.top/Article/details/gtjwbxexfl.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.yanxiufei.cn/Article/details/gtwqbtxdmb.html

[R76] 使用临时文件
来源：http://dali.xziqi.cn/Article/details/gtcpzyfeqb.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.hammf.cn/Article/details/gtdxomtlot.html

[R77] 读取用户输入
来源：http://dali.daxiang520.top/Article/details/gthcdgtyuu.html

read -rp "请输入: " ans
来源：http://dali.zhiwuduotai.top/Article/details/gtgpekybjg.html

[R78] 交互式菜单
来源：http://dali.guowangkeji.top/Article/details/gttorpvufu.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.daria6918.cn/Article/details/gtwrlqmgxl.html

[R79] 解析命令行选项
来源：http://dali.shzxlz.cn/Article/details/gtxkcximbt.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.feifeiyinyue.top/Article/details/gtfmsmjfhc.html

[R80] 查看脚本执行耗时
来源：http://dali.zdqjudy.top/Article/details/gtpdwxeftv.html

time ./run.sh
来源：http://dali.xuetiantiany.cn/Article/details/gtaeddvufh.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtqonbpcut.html

S. C / C++ 专题
来源：http://dali.zhoulong.xyz/Article/details/gtqjlfyans.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtqcjxwask.html

[S01] C：Hello World
来源：http://dali.zhongyouzk.top/Article/details/gtsdcjdiol.html

#include <stdio.h>
来源：http://dali.hnqzz.top/Article/details/gtuwkrglna.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.jiagoushi.top/Article/details/gtgmydhxoo.html

[S02] C：变量与格式化输出
来源：http://dali.aibaodan.cn/Article/details/gtppgygdjt.html

int a = 10; printf("%d\n", a);
来源：http://dali.yongpay.top/Article/details/gthmygljgy.html

[S03] C：读入整数
来源：http://dali.aizwys.cn/Article/details/gtqcqjzihl.html

int x; scanf("%d", &x);
来源：http://dali.jyoumei.cn/Article/details/gtckvrfteu.html

[S04] C：字符串复制
来源：http://dali.gotoacloud.top/Article/details/gtvfdrgkyp.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.feifeiyinyue.top/Article/details/gtcauxqkgo.html

[S05] C：字符串长度
来源：http://dali.andypj.xyz/Article/details/gtpuexclff.html

strlen(s)
来源：http://dali.jqgfzy.top/Article/details/gtmsqbrplu.html

[S06] C：字符串比较
来源：http://dali.jianghu66.top/Article/details/gtwctckbry.html

strcmp(a, b) == 0
来源：http://dali.hnxiangtu.top/Article/details/gtahlxbssj.html

[S07] C：数组遍历求和
来源：http://dali.fengsongda.top/Article/details/gtwglbqfry.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhengqikj.top/Article/details/gtnafpcmop.html

[S08] C：动态内存分配与释放
来源：http://dali.zhongyouzk.top/Article/details/gtbhqzrpig.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.sweek.top/Article/details/gtbgnoibuq.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gtmlxfishy.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhoulong.xyz/Article/details/gtxweidfgz.html

[S10] C：指针与解引用
来源：http://dali.yj20258.top/Article/details/gtkflheeki.html

int *p = &a;  *p = 5;
来源：http://dali.tianlin.xyz/Article/details/gtectjizmk.html

[S11] C：逐行读文件
来源：http://dali.ehwqpu.com/Article/details/gtxoebraid.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.c1oappe.top/Article/details/gtgzziqjkh.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.hnqzz.top/Article/details/gtlxpnwjea.html

fclose(f);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfjeksjgk.html

[S12] C：写文件
来源：http://dali.nanxinkj.top/Article/details/gtquuvpqjq.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.xuetiantiany.cn/Article/details/gtzlejrhhw.html

[S13] C：宏定义
来源：http://dali.yvedp.cn/Article/details/gtbbpfhhtt.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.havefunace.top/Article/details/gtdrjsdawn.html

[S14] C：枚举
来源：http://dali.tianlin.xyz/Article/details/gtlrwjkejs.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.hongshengwenyu.top/Article/details/gteuqrocaq.html

[S15] C：类型转换
来源：http://dali.hywenlv.cn/Article/details/gtiolunqug.html

(double) a / b
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqlrtnsdo.html

[S16] C：位操作置位
来源：http://dali.ivvv.top/Article/details/gtpbugeeee.html

x |= (1 << 3);
来源：http://dali.hnxiangtu.top/Article/details/gtwbllnhbg.html

[S17] C：安全拼接字符串
来源：http://dali.zhongyouzk.top/Article/details/gtjpibbazl.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.hnxiangtu.top/Article/details/gtdrtucflw.html

[S18] C：命令行参数
来源：http://dali.shanyushiyangtech.top/Article/details/gtoswizdci.html

int main(int argc, char **argv)
来源：http://dali.xylfe.cn/Article/details/gtdmlrygzb.html

[S19] C：快速排序
来源：http://dali.dashuyun.cn/Article/details/gtiogqtdav.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.iojbl.cn/Article/details/gtqnncfuwl.html

[S20] C：二分查找
来源：http://dali.hfpthk.cn/Article/details/gtlckkxrtx.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.cheryme.top/Article/details/gteugibvbz.html

[S21] C：字符类别判断
来源：http://dali.shanyushiyangtech.top/Article/details/gtauprkbkx.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.haohaochexian.top/Article/details/gtxuwqfyew.html

[S22] C：字符串转数字
来源：http://dali.dashuyun.cn/Article/details/gteippxkun.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.chenjidiqi.icu/Article/details/gtyhpymurs.html

[S23] C：随机数
来源：http://dali.zycfv.cn/Article/details/gtvxrwqfll.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.c1oappe.top/Article/details/gtwguobrgo.html

[S24] C：获取本地时间
来源：http://dali.vqdsnc.cn/Article/details/gtheduizqm.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.meibo888.top/Article/details/gtaoewimgd.html

[S25] C：内存拷贝
来源：http://dali.ywan-chungtsiang.top/Article/details/gtettntzun.html

memcpy(dst, src, n);
来源：http://dali.gogol.net.cn/Article/details/gtggqxmnet.html

[S26] C：内存清零
来源：http://dali.aibaodan.cn/Article/details/gtosdlfivx.html

memset(a, 0, sizeof a);
来源：http://dali.nanxuanxn.top/Article/details/gthjygrwoq.html

[S27] C：定义常量
来源：http://dali.cashguo.top/Article/details/gtljspdzkj.html

const double PI = 3.14159;
来源：http://dali.hongshengwenyu.top/Article/details/gtfotlmoev.html

[S28] C：静态变量
来源：http://dali.aizwys.cn/Article/details/gtflbmajsb.html

static int counter = 0;
来源：http://dali.smart0.xyz/Article/details/gtgpxwoqlr.html

[S29] C：变参函数
来源：http://dali.hongshengwenyu.top/Article/details/gtqevrkqgv.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gtdxihkxqy.html

[S30] C：头文件保护
来源：http://dali.yonumen.top/Article/details/gtcwqnkzns.html

#ifndef X_H
来源：http://dali.jinqigfzy.top/Article/details/gtxdqcujvj.html

#define X_H
来源：http://dali.shzxlz.cn/Article/details/gtnjuwkrbe.html

#endif
来源：http://dali.tanke756.top/Article/details/gtxsfihxvp.html

[S31] C++：Hello World
来源：http://dali.chenjidiqi.icu/Article/details/gtkkcmpgfz.html

#include <iostream>
来源：http://dali.cdnleiting.top/Article/details/gteipwfnkj.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.hfpthk.cn/Article/details/gtpnpzlfzg.html

[S32] C++：字符串
来源：http://dali.iojbl.cn/Article/details/gtvkejntwq.html

std::string s = "hi";  s += "!";
来源：http://dali.ywan-chungtsiang.top/Article/details/gtorgereet.html

[S33] C++：vector 增删
来源：http://dali.nanxuanxn.top/Article/details/gtlgatrfne.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.feifeiyinyue.top/Article/details/gtfijgspdu.html

[S34] C++：遍历 vector
来源：http://dali.aibaodan.cn/Article/details/gtfvtkwpxg.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.yj20258888.top/Article/details/gthtztalws.html

[S35] C++：map
来源：http://dali.jiagoushi.top/Article/details/gttmqyvvxt.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtycwdoara.html

[S36] C++：unordered_map
来源：http://dali.jyoumei.cn/Article/details/gthvbayonu.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.cashguo.top/Article/details/gtwvcyvzhk.html

[S37] C++：set
来源：http://dali.yuxming.cn/Article/details/gtpmrcgdiv.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.yongpay.top/Article/details/gtjmkbbvlw.html

[S38] C++：排序
来源：http://dali.xinyue.icu/Article/details/gtgmioypsq.html

std::sort(v.begin(), v.end());
来源：http://dali.hywenlv.cn/Article/details/gtoeegljlg.html

[S39] C++：自定义比较器排序
来源：http://dali.sxryk.cn/Article/details/gthurkoihx.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.iojbl.cn/Article/details/gtdxemoeok.html

[S40] C++：查找元素
来源：http://dali.fengsongda.top/Article/details/gtjkwfgxaj.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.dashuyun.cn/Article/details/gtloaqshjk.html

[S41] C++：类与构造函数
来源：http://dali.shuidangran.top/Article/details/gtszgfbjkq.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.guannengcc.top/Article/details/gtjxjewyxq.html

[S42] C++：继承与虚函数
来源：http://dali.guowangkeji.top/Article/details/gtujsnmokn.html

class B : public Base { public: void f() override {} };
来源：http://dali.hysaishi.cn/Article/details/gtikvsppow.html

[S43] C++：智能指针
来源：http://dali.redwolf501.top/Article/details/gtrjqaisfg.html

auto p = std::make_unique<int>(5);
来源：http://dali.svipenyu.cn/Article/details/gtwvlytvlu.html

[S44] C++：引用传参
来源：http://dali.fengsongda.top/Article/details/gtgcnpethp.html

void inc(int &x) { ++x; }
来源：http://dali.yanxiufei.cn/Article/details/gtxkdjwmho.html

[S45] C++：lambda
来源：http://dali.redwolf501.top/Article/details/gtmzfhzygm.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.redwolf501.top/Article/details/gtuclydaou.html

[S46] C++：函数模板
来源：http://dali.pycfn.com/Article/details/gtlftuhfkv.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.iojbl.cn/Article/details/gtostdjvsm.html

[S47] C++：结构化绑定遍历
来源：http://dali.havefunace.top/Article/details/gtmgezlihh.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.redwolf501.top/Article/details/gtsztigxew.html

[S48] C++：逐行读文件
来源：http://dali.shuidangran.top/Article/details/gtvbzwdvmi.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.ybcxt.top/Article/details/gtchewsuga.html

while (std::getline(in, line)) { }
来源：http://dali.yj20258.top/Article/details/gtkryxmpkc.html

[S49] C++：写文件
来源：http://dali.nwbrower.top/Article/details/gtqkwzkmag.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.nanxinkj.top/Article/details/gtdxgnestk.html

[S50] C++：格式化数字
来源：http://dali.sufxvd.cn/Article/details/gtxogppeyj.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.cqqwz.cn/Article/details/gtgiagvwys.html

[S51] C++：显式类型转换
来源：http://dali.wangshuangyany.cn/Article/details/gtalluffek.html

static_cast<double>(a) / b
来源：http://dali.jyoumei.cn/Article/details/gtfzjjhydl.html

[S52] C++：const 与 noexcept
来源：http://dali.cdnleiting.top/Article/details/gtbvsxmfzs.html

int size() const noexcept { return n_; }
来源：http://dali.ivvv.top/Article/details/gtnsozjmlr.html

[S53] C++：移动语义
来源：http://dali.jyoumei.cn/Article/details/gtpclpnlin.html

std::vector<int> w = std::move(v);
来源：http://dali.iojbl.cn/Article/details/gtllmocvii.html

[S54] C++：异常处理
来源：http://dali.gogol.net.cn/Article/details/gtfefhtjbe.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.chenzaomai.com/Article/details/gtimdvznep.html

[S55] C++：结构化绑定
来源：http://dali.wangdashe.top/Article/details/gtpsvbulil.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.jinqigfzy.top/Article/details/gtayywcuqn.html

[S56] C++：optional
来源：http://dali.meibo888.top/Article/details/gtdpzuwzfc.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.xziqi.cn/Article/details/gtniufznvg.html

[S57] C++：编译期常量
来源：http://dali.yonumen.top/Article/details/gtyirggkgq.html

constexpr int N = 10;
来源：http://dali.zdqjudy.top/Article/details/gtivfgvnta.html

[S58] C++：命名空间
来源：http://dali.jianghu66.top/Article/details/gtmbaegghx.html

namespace ns { int f() { return 1; } }
来源：http://dali.jinqigufen.top/Article/details/gtdkwblzpf.html

[S59] C++：静态断言
来源：http://dali.yongpay.top/Article/details/gtajoouccg.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.cucudq.cn/Article/details/gtojmulmph.html

[S60] C++：遍历并删除元素
来源：http://dali.zhengqikj.top/Article/details/gtmkmnkvrg.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.aizwys.cn/Article/details/gtaircfkqr.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gttzbjtnww.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbhrmufmd.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtszeyopoo.html

[T01] Kotlin：Hello World
来源：http://dali.shzxlz.cn/Article/details/gtnyftozzc.html

println("Hello")
来源：http://dali.xylfe.cn/Article/details/gtnxpgtcje.html

[T02] Kotlin：变量
来源：http://dali.cucudq.cn/Article/details/gtvirrguck.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhongyouzk.top/Article/details/gtbzsyyqrv.html

[T03] Kotlin：字符串模板
来源：http://dali.shzxlz.cn/Article/details/gtrcnkgskp.html

"值: $b"
来源：http://dali.yonumen.top/Article/details/gtabqnqdej.html

[T04] Kotlin：空安全
来源：http://dali.ybcxt.top/Article/details/gtvhbtzxck.html

val n: String? = null;  n?.length
来源：http://dali.zhengqikj.top/Article/details/gtswmmrcnf.html

[T05] Kotlin：when 表达式
来源：http://dali.fzhhl.top/Article/details/gtqpbhxrnq.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.cucudq.cn/Article/details/gtqnmflacm.html

[T06] Kotlin：集合映射
来源：http://dali.zdqjudy.top/Article/details/gtgneqfxmw.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.ehwqpu.com/Article/details/gtldxprrqm.html

[T07] Kotlin：集合过滤
来源：http://dali.yangfankeji.com/Article/details/gtaxkakihn.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.jinqigufen.top/Article/details/gtqsavxhto.html

[T08] Kotlin：数据类
来源：http://dali.cheryme.top/Article/details/gtqasgqpug.html

data class User(val name: String, val age: Int)
来源：http://dali.jinqigufen.top/Article/details/gtoqwupkiu.html

[T09] Kotlin：扩展函数
来源：http://dali.cucudq.cn/Article/details/gthkkgsvxj.html

fun String.exclaim() = this + "!"
来源：http://dali.jinghuilouyu.cn/Article/details/gtpjovmoxm.html

[T10] Kotlin：默认参数
来源：http://dali.vqdsnc.cn/Article/details/gthfcoevmy.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.fzhhl.top/Article/details/gtlphdnegt.html

[T11] Kotlin：协程
来源：http://dali.nwbrower.top/Article/details/gtufgymyjo.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.sysykeji.top/Article/details/gtkwoxmlaq.html

[T12] Kotlin：解构声明
来源：http://dali.havefunace.top/Article/details/gtoymwfete.html

val (a, b) = Pair(1, 2)
来源：http://dali.nanxuanxn.top/Article/details/gtasshudgj.html

[T13] Kotlin：只读 Map
来源：http://dali.yvedp.cn/Article/details/gtbfcwcsye.html

val m = mapOf("a" to 1)
来源：http://dali.tian-w.cn/Article/details/gtfpgeespc.html

[T14] Kotlin：循环
来源：http://dali.ppjwa.cn/Article/details/gtjokjsmfy.html

for (i in 1..10) println(i)
来源：http://dali.zhiwuduotai.top/Article/details/gteykgynlb.html

[T15] Kotlin：接口
来源：http://dali.gogol.net.cn/Article/details/gtuibewoqy.html

interface Shape { fun area(): Double }
来源：http://dali.pycfn.com/Article/details/gtnooorrzy.html

[T16] Swift：Hello World
来源：http://dali.ybcxt.top/Article/details/gtnbyizdww.html

print("Hello")
来源：http://dali.cqqwz.cn/Article/details/gtjxphcnpu.html

[T17] Swift：变量与常量
来源：http://dali.chenjidiqi.icu/Article/details/gtxpuzlwpe.html

var a = 1;  let b = 2
来源：http://dali.yj202588.top/Article/details/gtuipwjhdp.html

[T18] Swift：字符串插值
来源：http://dali.gotoacloud.top/Article/details/gtzplkpgia.html

"值: \(b)"
来源：http://dali.xinyue.icu/Article/details/gtccwmbzeu.html

[T19] Swift：可选绑定
来源：http://dali.yvedp.cn/Article/details/gtzhizysad.html

if let n = opt { print(n) }
来源：http://dali.ydzc1.top/Article/details/gtbqlqapce.html

[T20] Swift：数组操作
来源：http://dali.vqdsnc.cn/Article/details/gtkrldnrbi.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.jqgufenzy.top/Article/details/gtuhvywfsa.html

[T21] Swift：遍历
来源：http://dali.zhoulong.xyz/Article/details/gtxsrfdlcr.html

for x in a { print(x) }
来源：http://dali.vqdsnc.cn/Article/details/gtxbsfxbha.html

[T22] Swift：字典
来源：http://dali.sufxvd.cn/Article/details/gtegaaxohg.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zdqjudy.top/Article/details/gtkzuaotcw.html

[T23] Swift：函数
来源：http://dali.sysykeji.top/Article/details/gtqmvqizee.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.kuanghao11.cn/Article/details/gtqvytsmwz.html

[T24] Swift：闭包
来源：http://dali.shuidangran.top/Article/details/gtwyqlgrzd.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.tanke756.top/Article/details/gtciyjpbhx.html

[T25] Swift：结构体
来源：http://dali.jqgufenzy.top/Article/details/gthwnjsvvt.html

struct P { var x: Int }
来源：http://dali.gaohongyu789.top/Article/details/gtsewaxbyv.html

[T26] Swift：类与重写
来源：http://dali.jianghu66.top/Article/details/gtajxozhpl.html

class A: Base { override func f() {} }
来源：http://dali.ivvv.top/Article/details/gtnjwfguww.html

[T27] Swift：错误处理
来源：http://dali.xinyue.icu/Article/details/gtclkdquoj.html

do { try f() } catch { print(error) }
来源：http://dali.daria6918.cn/Article/details/gtoecqizzo.html

[T28] Swift：枚举
来源：http://dali.feifeiyinyue.top/Article/details/gtcfmfxrdr.html

enum Color { case red, green }
来源：http://dali.andypj.xyz/Article/details/gtsgbsyaab.html

[T29] Swift：guard 提前返回
来源：http://dali.jinqigfzy.top/Article/details/gtqhxclsrz.html

guard let x = opt else { return }
来源：http://dali.cheryme.top/Article/details/gtbcsmlrgr.html

[T30] Swift：协议
来源：http://dali.jyoumei.cn/Article/details/gtfwxekhqr.html

protocol Shape { func area() -> Double }
来源：http://dali.jianghu66.top/Article/details/gtfbrxhqhm.html

[T31] Lua：Hello World
来源：http://dali.yonumen.top/Article/details/gteqpoatry.html

print("Hello")
来源：http://dali.chenzaomai.com/Article/details/gtvygbhwtt.html

[T32] Lua：局部变量
来源：http://dali.kuanghao11.cn/Article/details/gtplylrskp.html

local a = 1
来源：http://dali.guowangkeji.top/Article/details/gtuyrnkjoo.html

[T33] Lua：表（数组）
来源：http://dali.fzhhl.top/Article/details/gtlofpqfqf.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.meibo888.top/Article/details/gtearcmbls.html

[T34] Lua：遍历表
来源：http://dali.tian-w.cn/Article/details/gttzpabwcu.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.c1oappe.top/Article/details/gtpfmfzkkw.html

[T35] Lua：字典表
来源：http://dali.snrcjt.cn/Article/details/gtvnxpbhjs.html

local d = { a = 1 };  d.b = 2
来源：http://dali.gzhubu.top/Article/details/gtwiqnqrzb.html

[T36] Lua：函数
来源：http://dali.bjfxy.top/Article/details/gtzapcjvio.html

function add(a, b) return a + b end
来源：http://dali.hammf.cn/Article/details/gtdmarpsdr.html

[T37] Lua：字符串拼接
来源：http://dali.daxiang520.top/Article/details/gtgsrxibgh.html

"a" .. "b"
来源：http://dali.iojbl.cn/Article/details/gtduazghyv.html

[T38] Lua：条件
来源：http://dali.pycfn.com/Article/details/gtmidavloa.html

if x > 0 then print("正") end
来源：http://dali.guannengcc.top/Article/details/gtrcvjebrr.html

[T39] Lua：模式匹配
来源：http://dali.xinyue.icu/Article/details/gtmnepyijy.html

string.find(s, "%d+")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkajozuio.html

[T40] Lua：元表
来源：http://dali.yueranfly.top/Article/details/gtytfpnehx.html

setmetatable({}, { __index = base })
来源：http://dali.chenjidiqi.icu/Article/details/gtensggnds.html

[T41] Perl：Hello World
来源：http://dali.zhixingplan.top/Article/details/gtpxrjgjaz.html

print "Hello\n";
来源：http://dali.yonumen.top/Article/details/gtcrepvptp.html

[T42] Perl：变量类型
来源：http://dali.hysaishi.cn/Article/details/gtipwcomps.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvlrwdhxs.html

[T43] Perl：字符串插值
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkdjdomjj.html

"值: $a"
来源：http://dali.9152youxi.cn/Article/details/gtzivqkesb.html

[T44] Perl：条件
来源：http://dali.sweek.top/Article/details/gtydfzedwn.html

if ($a > 0) { print "正"; }
来源：http://dali.hysaishi.cn/Article/details/gtjbgochod.html

[T45] Perl：数组遍历
来源：http://dali.xuetiantiany.cn/Article/details/gtsxeaqzqx.html

for my $x (@arr) { print $x; }
来源：http://dali.shzxlz.cn/Article/details/gtwtnbznvb.html

[T46] Perl：哈希操作
来源：http://dali.zhaomingkeji.xyz/Article/details/gtombwllhe.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.jiagoushi.top/Article/details/gttmlfegiv.html

[T47] Perl：正则捕获
来源：http://dali.daxiang520.top/Article/details/gthpvmnklp.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.ybcxt.top/Article/details/gtsuyiwlku.html

[T48] Perl：正则替换
来源：http://dali.svipenyu.cn/Article/details/gtwywapoci.html

$s =~ s/old/new/g;
来源：http://dali.wangshuangyany.cn/Article/details/gtvooggafk.html

[T49] Perl：函数
来源：http://dali.chenzaomai.com/Article/details/gtsjgikpkz.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.ehwqpu.com/Article/details/gtyykaxkst.html

[T50] Perl：逐行读文件
来源：http://dali.snrcjt.cn/Article/details/gtqaiwpfru.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.jqgfzy.top/Article/details/gtwgpkissb.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.xziqi.cn/Article/details/gtivkhbszf.html

[T51] Scala：Hello World
来源：http://dali.dashuyun.cn/Article/details/gtpkcngsyh.html

println("Hello")
来源：http://dali.chenlongwang.top/Article/details/gtzedzgovl.html

[T52] Scala：变量
来源：http://dali.yj202588.top/Article/details/gtcnsfqjgt.html

val a = 1;  var b = 2
来源：http://dali.wangshuangyany.cn/Article/details/gtynrszhbw.html

[T53] Scala：字符串插值
来源：http://dali.cdnleiting.top/Article/details/gtswbsxkpk.html

s"值: $b"
来源：http://dali.xylfe.cn/Article/details/gtnarvtejo.html

[T54] Scala：集合映射
来源：http://dali.yj20258888.top/Article/details/gtyonpunni.html


<!-- 参考信息 -->