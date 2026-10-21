代发 wailian999

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.jinqigfzy.top/Article/details/gtwwywonhn.html

[R50] awk 求和
来源：http://dali.yueranfly.top/Article/details/gthgzshdmu.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.haohaochexian.top/Article/details/gtjqurycph.html

[R51] 排序去重取前几
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtegugnuyk.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.nanxuanxn.top/Article/details/gtdptkcydq.html

[R52] 统计行数
来源：http://dali.yonumen.top/Article/details/gtmrmbgpmx.html

wc -l a.txt
来源：http://dali.jinghuilouyu.cn/Article/details/gtuinmshze.html

[R53] 查看文件头与实时尾
来源：http://dali.hysaishi.cn/Article/details/gtzwctmqpo.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.aizwys.cn/Article/details/gtxrxdbyvd.html

[R54] 比较两个文件
来源：http://dali.pengpengdd.cyou/Article/details/gtreaaxhrx.html

diff a.txt b.txt
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdngdsqoo.html

[R55] 压缩与解压
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlencufre.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhixingplan.top/Article/details/gtwwudwgyc.html

[R56] 远程拷贝
来源：http://dali.yj20258888.top/Article/details/gtiwjwvfjh.html

scp file user@host:/path/
来源：http://dali.zhengqikj.top/Article/details/gtyajdqwdm.html

[R57] 远程执行命令
来源：http://dali.tian-w.cn/Article/details/gtpmhpresm.html

ssh user@host 'uptime'
来源：http://dali.jiagoushi.top/Article/details/gtxxklamzr.html

[R58] 下载文件
来源：http://dali.shangyingyoupin.top/Article/details/gtcwtvwepd.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.sysykeji.top/Article/details/gtsikkaivr.html

[R59] 发 POST JSON
来源：http://dali.ybcxt.top/Article/details/gtfrawxofn.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.jinghuilouyu.cn/Article/details/gtstxdqnsc.html

[R60] 只看 HTTP 状态码
来源：http://dali.jqgufenzy.top/Article/details/gtkynptvlx.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaakbvjkb.html

[R61] 磁盘占用
来源：http://dali.yuanzhike.top/Article/details/gtlsvykktu.html

df -h;  du -sh *
来源：http://dali.shanyushiyangkeji.top/Article/details/gteowercww.html

[R62] 找最占空间的文件
来源：http://dali.yonumen.top/Article/details/gtqcxzsjsp.html

du -ah . | sort -rh | head -10
来源：http://dali.ybcxt.top/Article/details/gtyrxsbjvz.html

[R63] 内存与进程
来源：http://dali.birdmap.top/Article/details/gtzwmvivoh.html

free -h;  ps aux | grep nginx
来源：http://dali.gogol.net.cn/Article/details/gtlyyajysu.html

[R64] 结束进程
来源：http://dali.yanxiufei.cn/Article/details/gtmancvvxg.html

kill -9 $(pgrep -f app.py)
来源：http://dali.feifeiyinyue.top/Article/details/gtgmumalnk.html

[R65] 查看端口占用
来源：http://dali.meibo888.top/Article/details/gtpzuhkaxl.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.wangshuangyany.cn/Article/details/gtnpxmlgnh.html

[R66] 定时任务
来源：http://dali.ivvv.top/Article/details/gtssllobli.html

crontab -e;  crontab -l
来源：http://dali.meibo888.top/Article/details/gtoubnannm.html

[R67] 生成随机十六进制串
来源：http://dali.guowangkeji.top/Article/details/gtaqravkdo.html

openssl rand -hex 16
来源：http://dali.jianghu66.top/Article/details/gtofqeiksj.html

[R68] 计算文件校验值
来源：http://dali.hammf.cn/Article/details/gtbqqqawtg.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zdqjudy.top/Article/details/gtglpoqabp.html

[R69] 生成随机密码
来源：http://dali.ehwqpu.com/Article/details/gtsudflqql.html

head -c 16 /dev/urandom | base64
来源：http://dali.xziqi.cn/Article/details/gtegrarqrf.html

[R70] 时间戳与互转
来源：http://dali.fengsongda.top/Article/details/gtpdfafdxv.html

date +%s;  date -d @1700000000
来源：http://dali.yongpay.top/Article/details/gtkhtcakpu.html

[R71] 日期格式化
来源：http://dali.pycfn.com/Article/details/gtuazgtnxl.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.chenlongwang.top/Article/details/gtvcjwwvag.html

[R72] 等待端口就绪
来源：http://dali.aibaodan.cn/Article/details/gtwehuwjtt.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.mhx1999.top/Article/details/gtlecyexuq.html

[R73] 分割大日志
来源：http://dali.jianghu66.top/Article/details/gtxpjsbblt.html

split -l 1000 big.log part_
来源：http://dali.aizwys.cn/Article/details/gtzbmajdyr.html

[R74] 批量重命名
来源：http://dali.gaohongyu789.top/Article/details/gtjvqjnbpt.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gtuuzhlezf.html

[R75] 导出环境变量
来源：http://dali.ybcxt.top/Article/details/gtdwfdyphg.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.gogol.net.cn/Article/details/gtxxodlqav.html

[R76] 使用临时文件
来源：http://dali.hongshengwenyu.top/Article/details/gtrbofihjv.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.shzxlz.cn/Article/details/gtkhcvjnuj.html

[R77] 读取用户输入
来源：http://dali.mhx1999.top/Article/details/gtpokoobim.html

read -rp "请输入: " ans
来源：http://dali.zhongyouzk.top/Article/details/gtvuarxdow.html

[R78] 交互式菜单
来源：http://dali.yueranfly.top/Article/details/gtfyxlsbgx.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.hysaishi.cn/Article/details/gtrsdlwivf.html

[R79] 解析命令行选项
来源：http://dali.mhx1999.top/Article/details/gtmjfxffoy.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.meibo888.top/Article/details/gtlfmxchpk.html

[R80] 查看脚本执行耗时
来源：http://dali.jlsjyb.cn/Article/details/gtsteaocrj.html

time ./run.sh
来源：http://dali.ivvv.top/Article/details/gtnxzlnfcp.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzbvilzyv.html

S. C / C++ 专题
来源：http://dali.cashguo.top/Article/details/gtgaudbrdt.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtlannoind.html

[S01] C：Hello World
来源：http://dali.cqqwz.cn/Article/details/gtmnoithfc.html

#include <stdio.h>
来源：http://dali.shanyushiyangtech.top/Article/details/gtlxpzdgyy.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.hongshengwenyu.top/Article/details/gtzvkbybix.html

[S02] C：变量与格式化输出
来源：http://dali.yonumen.top/Article/details/gtoinemjsa.html

int a = 10; printf("%d\n", a);
来源：http://dali.shangyingyoupin.top/Article/details/gtynswqsqg.html

[S03] C：读入整数
来源：http://dali.yueranfly.top/Article/details/gtukexfswv.html

int x; scanf("%d", &x);
来源：http://dali.tian-w.cn/Article/details/gtlrniipds.html

[S04] C：字符串复制
来源：http://dali.yj20258888.top/Article/details/gtzrfzbcpk.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.hywenlv.cn/Article/details/gtmvfdjyec.html

[S05] C：字符串长度
来源：http://dali.zhiwuduotai.top/Article/details/gtopyhegcu.html

strlen(s)
来源：http://dali.cucudq.cn/Article/details/gtpkhpavxi.html

[S06] C：字符串比较
来源：http://dali.chenjidiqi.icu/Article/details/gtckmfuxyr.html

strcmp(a, b) == 0
来源：http://dali.dianchejie.cn/Article/details/gtizqxoloh.html

[S07] C：数组遍历求和
来源：http://dali.havefunace.top/Article/details/gtcvevbzqf.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.yuxming.cn/Article/details/gtepqtzeve.html

[S08] C：动态内存分配与释放
来源：http://dali.wangdashe.top/Article/details/gtjodsqhwp.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.tian-w.cn/Article/details/gtucugnxtr.html

[S09] C：结构体定义与初始化
来源：http://dali.tanke756.top/Article/details/gtmmfjtggr.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.jiagoushi.top/Article/details/gtcpkzvdnv.html

[S10] C：指针与解引用
来源：http://dali.aizwys.cn/Article/details/gtxprxonyo.html

int *p = &a;  *p = 5;
来源：http://dali.yanxiufei.cn/Article/details/gtkfcxidmi.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gtjbagqjkv.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.hammf.cn/Article/details/gtthjofobn.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.gzhubu.top/Article/details/gtaaxnxlvz.html

fclose(f);
来源：http://dali.ydzc1.top/Article/details/gtdnbfmfil.html

[S12] C：写文件
来源：http://dali.yuanzhike.top/Article/details/gtcgbtyunx.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.jqgufenzy.top/Article/details/gtzzlgwvzv.html

[S13] C：宏定义
来源：http://dali.cucudq.cn/Article/details/gtesnjbcrs.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.haohaochexian.top/Article/details/gtmeuwtuoj.html

[S14] C：枚举
来源：http://dali.birdmap.top/Article/details/gtgzmpamfc.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.tian-w.cn/Article/details/gtoehkqzxg.html

[S15] C：类型转换
来源：http://dali.daria6918.cn/Article/details/gtmpibqbph.html

(double) a / b
来源：http://dali.ivvv.top/Article/details/gtntelkmyy.html

[S16] C：位操作置位
来源：http://dali.nanxuanxn.top/Article/details/gtaqjdlafd.html

x |= (1 << 3);
来源：http://dali.shuidangran.top/Article/details/gtjshxppfh.html

[S17] C：安全拼接字符串
来源：http://dali.jinqigfzy.top/Article/details/gtyokvpxta.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.shzxlz.cn/Article/details/gtctzynlke.html

[S18] C：命令行参数
来源：http://dali.cheryme.top/Article/details/gtjzebjfux.html

int main(int argc, char **argv)
来源：http://dali.yanxiufei.cn/Article/details/gtvcoyomlu.html

[S19] C：快速排序
来源：http://dali.aizwys.cn/Article/details/gtchpnmavd.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.xinyue.icu/Article/details/gtlizmwruf.html

[S20] C：二分查找
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfaupxblj.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.hywenlv.cn/Article/details/gtsrrpcuea.html

[S21] C：字符类别判断
来源：http://dali.gaohongyu789.top/Article/details/gtzsrirxlq.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.bjfxy.top/Article/details/gtmhggujiu.html

[S22] C：字符串转数字
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgviihorn.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.chenlongwang.top/Article/details/gtttekcbgx.html

[S23] C：随机数
来源：http://dali.dianchejie.cn/Article/details/gtyklxfaiu.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.yonumen.top/Article/details/gtltiffdhn.html

[S24] C：获取本地时间
来源：http://dali.sysykeji.top/Article/details/gtsigowxxr.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.quarkkingdee.top/Article/details/gtwhfehxzx.html

[S25] C：内存拷贝
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxrecvkff.html

memcpy(dst, src, n);
来源：http://dali.haohaochexian.top/Article/details/gtjvpzjfhu.html

[S26] C：内存清零
来源：http://dali.gaohongyu789.top/Article/details/gtolmcfaxh.html

memset(a, 0, sizeof a);
来源：http://dali.quarkkingdee.top/Article/details/gtrbpllyeu.html

[S27] C：定义常量
来源：http://dali.aizwys.cn/Article/details/gtaomsdvpf.html

const double PI = 3.14159;
来源：http://dali.shanyushiyangtech.top/Article/details/gttrmztelt.html

[S28] C：静态变量
来源：http://dali.zdqjudy.top/Article/details/gtrauavutw.html

static int counter = 0;
来源：http://dali.sweek.top/Article/details/gtkbskltzq.html

[S29] C：变参函数
来源：http://dali.iojbl.cn/Article/details/gtsenfsdlk.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.hywenlv.cn/Article/details/gtjlgfflds.html

[S30] C：头文件保护
来源：http://dali.jiagoushi.top/Article/details/gtrcoiwodn.html

#ifndef X_H
来源：http://dali.jiagoushi.top/Article/details/gtodohpxmv.html

#define X_H
来源：http://dali.zdqjudy.top/Article/details/gtweeaqjna.html

#endif
来源：http://dali.tianlin.xyz/Article/details/gtpncqpgfg.html

[S31] C++：Hello World
来源：http://dali.gzhubu.top/Article/details/gtijdwdnuy.html

#include <iostream>
来源：http://dali.zhengqikj.top/Article/details/gtsmabiawg.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.yvedp.cn/Article/details/gtijufrqkw.html

[S32] C++：字符串
来源：http://dali.tianlin.xyz/Article/details/gtpfjlfymw.html

std::string s = "hi";  s += "!";
来源：http://dali.jqgfzy.top/Article/details/gtprgfytvc.html

[S33] C++：vector 增删
来源：http://dali.jlsjyb.cn/Article/details/gtekvoumuf.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.jqgfzy.top/Article/details/gtsuocioyp.html

[S34] C++：遍历 vector
来源：http://dali.xylfe.cn/Article/details/gtnmhwfgmd.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.pengpengdd.cyou/Article/details/gtsjxtezxl.html

[S35] C++：map
来源：http://dali.nwbrower.top/Article/details/gtsqsfqkls.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.cucudq.cn/Article/details/gtowjgsvsq.html

[S36] C++：unordered_map
来源：http://dali.dianchejie.cn/Article/details/gtjkyttqbv.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.svipenyu.cn/Article/details/gtlnpmircb.html

[S37] C++：set
来源：http://dali.xuetiantiany.cn/Article/details/gtntxeyave.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaoftjyvh.html

[S38] C++：排序
来源：http://dali.shanyushiyangkeji.top/Article/details/gtokkspckh.html

std::sort(v.begin(), v.end());
来源：http://dali.aibaodan.cn/Article/details/gtqqteiycx.html

[S39] C++：自定义比较器排序
来源：http://dali.pengpengdd.cyou/Article/details/gtgrxobjaf.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.jqgfzy.top/Article/details/gtgapdgbrx.html

[S40] C++：查找元素
来源：http://dali.xuanzx.com/Article/details/gthksaceep.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.ivvv.top/Article/details/gtrqaaiffj.html

[S41] C++：类与构造函数
来源：http://dali.cdnleiting.top/Article/details/gthfyjcxol.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwuzmklqf.html

[S42] C++：继承与虚函数
来源：http://dali.yanxiufei.cn/Article/details/gtciuvezxi.html

class B : public Base { public: void f() override {} };
来源：http://dali.guowangkeji.top/Article/details/gtdupdewaj.html

[S43] C++：智能指针
来源：http://dali.tian-w.cn/Article/details/gtnhqwdcpq.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhengqikj.top/Article/details/gtrummgepc.html

[S44] C++：引用传参
来源：http://dali.cashguo.top/Article/details/gtdpjgppvi.html

void inc(int &x) { ++x; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtidbczxro.html

[S45] C++：lambda
来源：http://dali.yangfankeji.com/Article/details/gtforsnoaw.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.guannengcc.top/Article/details/gtlprgbohw.html

[S46] C++：函数模板
来源：http://dali.xylfe.cn/Article/details/gtasfbhxom.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.hammf.cn/Article/details/gtdrxaxjys.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhixingplan.top/Article/details/gtqqujbtno.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.gotoacloud.top/Article/details/gtaljeomub.html

[S48] C++：逐行读文件
来源：http://dali.feifeiyinyue.top/Article/details/gtmbronyky.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.yangfankeji.com/Article/details/gtouqreejb.html

while (std::getline(in, line)) { }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcqwdxvir.html

[S49] C++：写文件
来源：http://dali.gaohongyu789.top/Article/details/gtwzstmoub.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.jinqigfzy.top/Article/details/gteeycftrf.html

[S50] C++：格式化数字
来源：http://dali.kuanghao11.cn/Article/details/gtlyyshuhs.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.gogol.net.cn/Article/details/gtjwssqzgr.html

[S51] C++：显式类型转换
来源：http://dali.zhaomingkeji.xyz/Article/details/gtphsjdcly.html

static_cast<double>(a) / b
来源：http://dali.jlsjyb.cn/Article/details/gtixtsgdik.html

[S52] C++：const 与 noexcept
来源：http://dali.chenjidiqi.icu/Article/details/gtcfucmzmf.html

int size() const noexcept { return n_; }
来源：http://dali.pycfn.com/Article/details/gtmcbmpaem.html

[S53] C++：移动语义
来源：http://dali.yj20258888.top/Article/details/gtdnsnsgmr.html

std::vector<int> w = std::move(v);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsuiavgmc.html

[S54] C++：异常处理
来源：http://dali.hnqzz.top/Article/details/gtbynniibh.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.xuetiantiany.cn/Article/details/gtywrpndgb.html

[S55] C++：结构化绑定
来源：http://dali.vqdsnc.cn/Article/details/gtmwqswjvc.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.wangshuangyany.cn/Article/details/gttugsbmpx.html

[S56] C++：optional
来源：http://dali.ybcxt.top/Article/details/gtfoofpykm.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.sysykeji.top/Article/details/gtjwynkpln.html

[S57] C++：编译期常量
来源：http://dali.sufxvd.cn/Article/details/gtxcmgvcly.html

constexpr int N = 10;
来源：http://dali.snrcjt.cn/Article/details/gtsqnxphbl.html

[S58] C++：命名空间
来源：http://dali.jiagoushi.top/Article/details/gtiageelhz.html

namespace ns { int f() { return 1; } }
来源：http://dali.gzhubu.top/Article/details/gtsndeasuz.html

[S59] C++：静态断言
来源：http://dali.9152youxi.cn/Article/details/gtmwdohtqw.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.shuidangran.top/Article/details/gtdhqiaapw.html

[S60] C++：遍历并删除元素
来源：http://dali.wangdashe.top/Article/details/gtblbpoodp.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.svipenyu.cn/Article/details/gtzmdxswnd.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtrzunfhxg.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.hnxiangtu.top/Article/details/gtinlkgjql.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtbuolnhvz.html

[T01] Kotlin：Hello World
来源：http://dali.jyoumei.cn/Article/details/gthxhkxxpq.html

println("Hello")
来源：http://dali.sysykeji.top/Article/details/gterkheiyg.html

[T02] Kotlin：变量
来源：http://dali.shuidangran.top/Article/details/gtalhfyrtk.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.ehwqpu.com/Article/details/gtspabovvu.html

[T03] Kotlin：字符串模板
来源：http://dali.birdmap.top/Article/details/gtyjrbfzqw.html

"值: $b"
来源：http://dali.snrcjt.cn/Article/details/gtdwybccpd.html

[T04] Kotlin：空安全
来源：http://dali.zhixingplan.top/Article/details/gtgbuymehp.html

val n: String? = null;  n?.length
来源：http://dali.sufxvd.cn/Article/details/gthgcjjkte.html

[T05] Kotlin：when 表达式
来源：http://dali.xylfe.cn/Article/details/gtxmmqpcsh.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.sysykeji.top/Article/details/gtzzojftae.html

[T06] Kotlin：集合映射
来源：http://dali.xinyue.icu/Article/details/gtlyzuftcv.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoneheqby.html

[T07] Kotlin：集合过滤
来源：http://dali.316326.xyz/Article/details/gtxlrlmiip.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.daria6918.cn/Article/details/gtpieauyve.html

[T08] Kotlin：数据类
来源：http://dali.ybcxt.top/Article/details/gtglzlfrtx.html

data class User(val name: String, val age: Int)
来源：http://dali.tianlin.xyz/Article/details/gtxszhyina.html

[T09] Kotlin：扩展函数
来源：http://dali.yuxming.cn/Article/details/gtpqsehrju.html

fun String.exclaim() = this + "!"
来源：http://dali.hywenlv.cn/Article/details/gtqrhuxnay.html

[T10] Kotlin：默认参数
来源：http://dali.xuanzx.com/Article/details/gtzqjgxpor.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.xuanzx.com/Article/details/gtbhllfqks.html

[T11] Kotlin：协程
来源：http://dali.jinqigfzy.top/Article/details/gtkgcgubzy.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.tianlin.xyz/Article/details/gtqghofamh.html

[T12] Kotlin：解构声明
来源：http://dali.svipenyu.cn/Article/details/gtmpoluaxm.html

val (a, b) = Pair(1, 2)
来源：http://dali.yuxming.cn/Article/details/gtihvzeqbe.html

[T13] Kotlin：只读 Map
来源：http://dali.yj20258888.top/Article/details/gtksbqtifr.html

val m = mapOf("a" to 1)
来源：http://dali.jinqigfzy.top/Article/details/gtqoejmhms.html

[T14] Kotlin：循环
来源：http://dali.tanke756.top/Article/details/gtkztfnuwv.html

for (i in 1..10) println(i)
来源：http://dali.jqgufenzy.top/Article/details/gtipbngoxc.html

[T15] Kotlin：接口
来源：http://dali.ehwqpu.com/Article/details/gtpjaokcxc.html

interface Shape { fun area(): Double }
来源：http://dali.jiagoushi.top/Article/details/gtjrtyvezz.html

[T16] Swift：Hello World
来源：http://dali.fengsongda.top/Article/details/gtwxbqdvrn.html

print("Hello")
来源：http://dali.yangfankeji.com/Article/details/gtxffrbska.html

[T17] Swift：变量与常量
来源：http://dali.xuetiantiany.cn/Article/details/gtakfyxyzu.html

var a = 1;  let b = 2
来源：http://dali.sysykeji.top/Article/details/gtlydqugqx.html

[T18] Swift：字符串插值
来源：http://dali.ppjwa.cn/Article/details/gtrlyofxqm.html

"值: \(b)"
来源：http://dali.ybcxt.top/Article/details/gtaasgitao.html

[T19] Swift：可选绑定
来源：http://dali.fengsongda.top/Article/details/gtggaxlnwh.html

if let n = opt { print(n) }
来源：http://dali.jqgfzy.top/Article/details/gtnkgdplwc.html

[T20] Swift：数组操作
来源：http://dali.hfpthk.cn/Article/details/gtdauvenaq.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.sufxvd.cn/Article/details/gttlpkempw.html

[T21] Swift：遍历
来源：http://dali.xuetiantiany.cn/Article/details/gtnsssnscu.html

for x in a { print(x) }
来源：http://dali.yanxiufei.cn/Article/details/gtmxldkqhg.html

[T22] Swift：字典
来源：http://dali.jiagoushi.top/Article/details/gtaunypsaf.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhixingplan.top/Article/details/gtgmdsuhlg.html

[T23] Swift：函数
来源：http://dali.tanke756.top/Article/details/gtvqesothx.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.pengpengdd.cyou/Article/details/gtrisiloas.html

[T24] Swift：闭包
来源：http://dali.smart0.xyz/Article/details/gtjjomvzta.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.gaohongyu789.top/Article/details/gtmehugtwe.html

[T25] Swift：结构体
来源：http://dali.jlsjyb.cn/Article/details/gtuuvvhsjt.html

struct P { var x: Int }
来源：http://dali.meibo888.top/Article/details/gtglrowxmt.html

[T26] Swift：类与重写
来源：http://dali.ybcxt.top/Article/details/gtekfkegtl.html

class A: Base { override func f() {} }
来源：http://dali.sxryk.cn/Article/details/gtyrndqrnr.html

[T27] Swift：错误处理
来源：http://dali.yongpay.top/Article/details/gththcocsn.html

do { try f() } catch { print(error) }
来源：http://dali.9152youxi.cn/Article/details/gtsqorghro.html

[T28] Swift：枚举
来源：http://dali.jianghu66.top/Article/details/gtctnehqlj.html

enum Color { case red, green }
来源：http://dali.cashguo.top/Article/details/gtgemfbyli.html

[T29] Swift：guard 提前返回
来源：http://dali.gaohongyu789.top/Article/details/gtqrniegfk.html

guard let x = opt else { return }
来源：http://dali.tianlin.xyz/Article/details/gthefiuwlj.html

[T30] Swift：协议
来源：http://dali.zhongyouzk.top/Article/details/gtkaltooum.html

protocol Shape { func area() -> Double }
来源：http://dali.vqdsnc.cn/Article/details/gtvevxrpgd.html

[T31] Lua：Hello World
来源：http://dali.redwolf501.top/Article/details/gtuncelcfc.html

print("Hello")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtitynzsgx.html

[T32] Lua：局部变量
来源：http://dali.zhiwuduotai.top/Article/details/gtdyjwnwol.html

local a = 1
来源：http://dali.shuidangran.top/Article/details/gtwsmytght.html

[T33] Lua：表（数组）
来源：http://dali.sxryk.cn/Article/details/gtdpjlcqlj.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.meibo888.top/Article/details/gtgbrtthbg.html

[T34] Lua：遍历表
来源：http://dali.fzhhl.top/Article/details/gtlikavkyx.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.sweek.top/Article/details/gtjlryedpu.html

[T35] Lua：字典表
来源：http://dali.ydzc1.top/Article/details/gtnrqbzvwt.html

local d = { a = 1 };  d.b = 2
来源：http://dali.yanxiufei.cn/Article/details/gtcgrkumbp.html

[T36] Lua：函数
来源：http://dali.0kj1m.cn/Article/details/gtfzijaonj.html

function add(a, b) return a + b end
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgzxpfqxg.html

[T37] Lua：字符串拼接
来源：http://dali.jqgfzy.top/Article/details/gtzijotpvm.html

"a" .. "b"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtycdraftt.html

[T38] Lua：条件
来源：http://dali.jianghu66.top/Article/details/gtsfqvmrea.html

if x > 0 then print("正") end
来源：http://dali.fengsongda.top/Article/details/gtfgddzioy.html

[T39] Lua：模式匹配
来源：http://dali.yuanzhike.top/Article/details/gtjlcfhrdd.html

string.find(s, "%d+")
来源：http://dali.meibo888.top/Article/details/gtyxkaxttb.html

[T40] Lua：元表
来源：http://dali.tianlin.xyz/Article/details/gtuoohspwp.html

setmetatable({}, { __index = base })
来源：http://dali.aibaodan.cn/Article/details/gtyjtpqlqq.html

[T41] Perl：Hello World
来源：http://dali.guannengcc.top/Article/details/gtgdxjlnoj.html

print "Hello\n";
来源：http://dali.tianlin.xyz/Article/details/gtozalekyi.html

[T42] Perl：变量类型
来源：http://dali.hnqzz.top/Article/details/gtrwvzhzcr.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.daria6918.cn/Article/details/gtrevpihiu.html

[T43] Perl：字符串插值
来源：http://dali.cashguo.top/Article/details/gtqmedecho.html

"值: $a"
来源：http://dali.yj202588.top/Article/details/gtsxhuaaas.html

[T44] Perl：条件
来源：http://dali.hysaishi.cn/Article/details/gtxoabumqf.html

if ($a > 0) { print "正"; }
来源：http://dali.kuanghao11.cn/Article/details/gtuyfnjxko.html

[T45] Perl：数组遍历
来源：http://dali.hnxiangtu.top/Article/details/gtaemxzrzf.html

for my $x (@arr) { print $x; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlyzxvzha.html

[T46] Perl：哈希操作
来源：http://dali.fengsongda.top/Article/details/gtqjbyrtmh.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.aizwys.cn/Article/details/gtwswkeotx.html

[T47] Perl：正则捕获
来源：http://dali.zhiwuduotai.top/Article/details/gtiqvpuhpu.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.yvedp.cn/Article/details/gtwfyjhtmv.html

[T48] Perl：正则替换
来源：http://dali.zhixingplan.top/Article/details/gtlniybqid.html

$s =~ s/old/new/g;
来源：http://dali.c1oappe.top/Article/details/gtaifrbndi.html

[T49] Perl：函数
来源：http://dali.hnxiangtu.top/Article/details/gtyxnwysle.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.yj202588.top/Article/details/gtummorosw.html

[T50] Perl：逐行读文件
来源：http://dali.hfpthk.cn/Article/details/gtuzndnpkl.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.cucudq.cn/Article/details/gtkqhahblj.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.yanxiufei.cn/Article/details/gtwyriyhvk.html

[T51] Scala：Hello World
来源：http://dali.jlsjyb.cn/Article/details/gtkiaagykb.html

println("Hello")
来源：http://dali.hnxiangtu.top/Article/details/gtqrhazpdr.html

[T52] Scala：变量
来源：http://dali.shzxlz.cn/Article/details/gtmuggwgxe.html


<!-- 参考信息 -->