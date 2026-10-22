代发 wailian999

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.shanyushiyangtech.top/Article/details/gt2erhlavsk.html

[R52] 统计行数
来源：http://dali.feifeiyinyue.top/Article/details/gt2gdindywc.html

wc -l a.txt
来源：http://dali.dashuyun.cn/Article/details/gt2lcrlkbbi.html

[R53] 查看文件头与实时尾
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2losbkbhv.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.xinyue.icu/Article/details/gt2qnylxvel.html

[R54] 比较两个文件
来源：http://dali.9152youxi.cn/Article/details/gt2uhuhnzul.html

diff a.txt b.txt
来源：http://dali.redwolf501.top/Article/details/gt2jscbwwdq.html

[R55] 压缩与解压
来源：http://dali.sysykeji.top/Article/details/gt2fljpegee.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.pengpengdd.cyou/Article/details/gt2kwjomjnu.html

[R56] 远程拷贝
来源：http://dali.cashguo.top/Article/details/gt2msmdjbfm.html

scp file user@host:/path/
来源：http://dali.gotoacloud.top/Article/details/gt2bbcmuhsx.html

[R57] 远程执行命令
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tfrgtprl.html

ssh user@host 'uptime'
来源：http://dali.jinqigfzy.top/Article/details/gt2jbugculs.html

[R58] 下载文件
来源：http://dali.cdnleiting.top/Article/details/gt2ewraltec.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.jinqigufen.top/Article/details/gt2mdyfbovs.html

[R59] 发 POST JSON
来源：http://dali.sufxvd.cn/Article/details/gt2foxkgoji.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.pycfn.com/Article/details/gt2jkmixxfy.html

[R60] 只看 HTTP 状态码
来源：http://dali.dashuyun.cn/Article/details/gt2bplnqnsy.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pljdoost.html

[R61] 磁盘占用
来源：http://dali.pengpengdd.cyou/Article/details/gt2tuwgaicg.html

df -h;  du -sh *
来源：http://dali.redwolf501.top/Article/details/gt2wbvwyfcd.html

[R62] 找最占空间的文件
来源：http://dali.zhixingplan.top/Article/details/gt2wqsohupn.html

du -ah . | sort -rh | head -10
来源：http://dali.jinqigfzy.top/Article/details/gt2cpuevzxn.html

[R63] 内存与进程
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2aabimpet.html

free -h;  ps aux | grep nginx
来源：http://dali.sysykeji.top/Article/details/gt2updidcnv.html

[R64] 结束进程
来源：http://dali.hongshengwenyu.top/Article/details/gt2qibskwss.html

kill -9 $(pgrep -f app.py)
来源：http://dali.dashuyun.cn/Article/details/gt2kuehbhuq.html

[R65] 查看端口占用
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ebkoqxic.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.yj20258888.top/Article/details/gt2xbemrdbv.html

[R66] 定时任务
来源：http://dali.cheryme.top/Article/details/gt2zgxakjkw.html

crontab -e;  crontab -l
来源：http://dali.pycfn.com/Article/details/gt2ynwwzytp.html

[R67] 生成随机十六进制串
来源：http://dali.ivvv.top/Article/details/gt2dkksnxqo.html

openssl rand -hex 16
来源：http://dali.yj20258.top/Article/details/gt2slyxbnag.html

[R68] 计算文件校验值
来源：http://dali.gotoacloud.top/Article/details/gt2qpykptaq.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.xuetiantiany.cn/Article/details/gt2ztskzvmc.html

[R69] 生成随机密码
来源：http://dali.redwolf501.top/Article/details/gt2uisuryub.html

head -c 16 /dev/urandom | base64
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zsbkmdmp.html

[R70] 时间戳与互转
来源：http://dali.nanxuanxn.top/Article/details/gt2avikkbhw.html

date +%s;  date -d @1700000000
来源：http://dali.ydzc1.top/Article/details/gt2abmhikbq.html

[R71] 日期格式化
来源：http://dali.yonumen.top/Article/details/gt2otlampuk.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhixingplan.top/Article/details/gt2cvrztvja.html

[R72] 等待端口就绪
来源：http://dali.hnxiangtu.top/Article/details/gt2mumhwrmq.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.pycfn.com/Article/details/gt2spexnfpp.html

[R73] 分割大日志
来源：http://dali.shangyingyoupin.top/Article/details/gt2bicuygyf.html

split -l 1000 big.log part_
来源：http://dali.xylfe.cn/Article/details/gt2uadxizkz.html

[R74] 批量重命名
来源：http://dali.pycfn.com/Article/details/gt2fvigdhif.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.sysykeji.top/Article/details/gt2eeaycyme.html

[R75] 导出环境变量
来源：http://dali.hnxiangtu.top/Article/details/gt2klbftgrb.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zswpadrt.html

[R76] 使用临时文件
来源：http://dali.daxiang520.top/Article/details/gt2vgegscub.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.andypj.xyz/Article/details/gt2yxvarqvv.html

[R77] 读取用户输入
来源：http://dali.sweek.top/Article/details/gt2rigdmbpn.html

read -rp "请输入: " ans
来源：http://dali.jiagoushi.top/Article/details/gt2phnuqwjr.html

[R78] 交互式菜单
来源：http://dali.dashuyun.cn/Article/details/gt2fvfycabj.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.tianlin.xyz/Article/details/gt2ksvaongd.html

[R79] 解析命令行选项
来源：http://dali.yj202588.top/Article/details/gt2riuxqswa.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhengqikj.top/Article/details/gt2nvhydwpo.html

[R80] 查看脚本执行耗时
来源：http://dali.jyoumei.cn/Article/details/gt2txwpiawn.html

time ./run.sh
来源：http://dali.quarkkingdee.top/Article/details/gt2aghjhcgt.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tqjlpify.html

S. C / C++ 专题
来源：http://dali.feifeiyinyue.top/Article/details/gt2yaocabop.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gt2jvfbiwsp.html

[S01] C：Hello World
来源：http://dali.zhengqikj.top/Article/details/gt2uvrcacha.html

#include <stdio.h>
来源：http://dali.daxiang520.top/Article/details/gt2fzduetuk.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.pycfn.com/Article/details/gt2sdxfcgap.html

[S02] C：变量与格式化输出
来源：http://dali.redwolf501.top/Article/details/gt2vypuikjr.html

int a = 10; printf("%d\n", a);
来源：http://dali.chenzaomai.com/Article/details/gt2ikykguzy.html

[S03] C：读入整数
来源：http://dali.snrcjt.cn/Article/details/gt2bqshcayh.html

int x; scanf("%d", &x);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lgapwlzw.html

[S04] C：字符串复制
来源：http://dali.yonumen.top/Article/details/gt2gcuvxqke.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.hfpthk.cn/Article/details/gt2wwvccqqp.html

[S05] C：字符串长度
来源：http://dali.nanxinkj.top/Article/details/gt2jocndgnl.html

strlen(s)
来源：http://dali.bjfxy.top/Article/details/gt2frxiihcy.html

[S06] C：字符串比较
来源：http://dali.fengsongda.top/Article/details/gt2dgtkvepe.html

strcmp(a, b) == 0
来源：http://dali.c1oappe.top/Article/details/gt2fvpnxkfj.html

[S07] C：数组遍历求和
来源：http://dali.feifeiyinyue.top/Article/details/gt2wfcsftrg.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hdtcluxm.html

[S08] C：动态内存分配与释放
来源：http://dali.dashuyun.cn/Article/details/gt2icugdruh.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.kuanghao11.cn/Article/details/gt2yscnmsow.html

[S09] C：结构体定义与初始化
来源：http://dali.gzhubu.top/Article/details/gt2myonnhpd.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.shangyingyoupin.top/Article/details/gt2iolbpqtz.html

[S10] C：指针与解引用
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2crfbwgud.html

int *p = &a;  *p = 5;
来源：http://dali.hammf.cn/Article/details/gt2fsrhbadx.html

[S11] C：逐行读文件
来源：http://dali.mhx1999.top/Article/details/gt2xdwrxnjm.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.haohaochexian.top/Article/details/gt2sbqcqmqy.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.ehwqpu.com/Article/details/gt2ximkdckn.html

fclose(f);
来源：http://dali.hongshengwenyu.top/Article/details/gt2sptefiwf.html

[S12] C：写文件
来源：http://dali.nanxuanxn.top/Article/details/gt2tzoujjya.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zycfv.cn/Article/details/gt2okekdhgy.html

[S13] C：宏定义
来源：http://dali.haohaochexian.top/Article/details/gt2wtreeiui.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.svipenyu.cn/Article/details/gt2ussxpxvl.html

[S14] C：枚举
来源：http://dali.svipenyu.cn/Article/details/gt2wbzwkrmg.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.tian-w.cn/Article/details/gt2ncvfxnui.html

[S15] C：类型转换
来源：http://dali.zhiwuduotai.top/Article/details/gt2vmwoypdk.html

(double) a / b
来源：http://dali.cashguo.top/Article/details/gt2khtsiqfn.html

[S16] C：位操作置位
来源：http://dali.cashguo.top/Article/details/gt2bagpskeg.html

x |= (1 << 3);
来源：http://dali.feifeiyinyue.top/Article/details/gt2niklydfi.html

[S17] C：安全拼接字符串
来源：http://dali.jlsjyb.cn/Article/details/gt2rmxxmjkb.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.0kj1m.cn/Article/details/gt2rjsbmgxr.html

[S18] C：命令行参数
来源：http://dali.tianlin.xyz/Article/details/gt2zgysuuve.html

int main(int argc, char **argv)
来源：http://dali.nwbrower.top/Article/details/gt2avsnmowv.html

[S19] C：快速排序
来源：http://dali.yuxming.cn/Article/details/gt2tlvgvojd.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.c1oappe.top/Article/details/gt2menuxkrz.html

[S20] C：二分查找
来源：http://dali.9152youxi.cn/Article/details/gt2evuysvjo.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.bjfxy.top/Article/details/gt2lcectunz.html

[S21] C：字符类别判断
来源：http://dali.xziqi.cn/Article/details/gt2beijyvof.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.yuanzhike.top/Article/details/gt2vwggcvhm.html

[S22] C：字符串转数字
来源：http://dali.fzhhl.top/Article/details/gt2dfzahtxc.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.daria6918.cn/Article/details/gt2hboxitoz.html

[S23] C：随机数
来源：http://dali.tianlin.xyz/Article/details/gt2gigmlfxi.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.316326.xyz/Article/details/gt2jxtnohdd.html

[S24] C：获取本地时间
来源：http://dali.cashguo.top/Article/details/gt2vqwerkey.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.svipenyu.cn/Article/details/gt2ogeqxklg.html

[S25] C：内存拷贝
来源：http://dali.sufxvd.cn/Article/details/gt2hqdldxla.html

memcpy(dst, src, n);
来源：http://dali.hongshengwenyu.top/Article/details/gt2lgbbflnb.html

[S26] C：内存清零
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hufzbfog.html

memset(a, 0, sizeof a);
来源：http://dali.zhongyouzk.top/Article/details/gt2qafxksow.html

[S27] C：定义常量
来源：http://dali.dashuyun.cn/Article/details/gt2prnhowsg.html

const double PI = 3.14159;
来源：http://dali.feifeiyinyue.top/Article/details/gt2pwarbapa.html

[S28] C：静态变量
来源：http://dali.guannengcc.top/Article/details/gt2xsyjfbai.html

static int counter = 0;
来源：http://dali.yueranfly.top/Article/details/gt2rsypciuu.html

[S29] C：变参函数
来源：http://dali.xziqi.cn/Article/details/gt2aatbsiyt.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.jinqigfzy.top/Article/details/gt2fvekfmdc.html

[S30] C：头文件保护
来源：http://dali.gogol.net.cn/Article/details/gt2gtpaiujz.html

#ifndef X_H
来源：http://dali.jianghu66.top/Article/details/gt2qxgyhorg.html

#define X_H
来源：http://dali.iojbl.cn/Article/details/gt2ryprhjkh.html

#endif
来源：http://dali.shzxlz.cn/Article/details/gt2zcnvsoqd.html

[S31] C++：Hello World
来源：http://dali.haohaochexian.top/Article/details/gt2vmkfgqyb.html

#include <iostream>
来源：http://dali.xinyue.icu/Article/details/gt2hbdrdeov.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.jiagoushi.top/Article/details/gt2ruchaowq.html

[S32] C++：字符串
来源：http://dali.zhengqikj.top/Article/details/gt2xirvwrax.html

std::string s = "hi";  s += "!";
来源：http://dali.yangfankeji.com/Article/details/gt2gcjhddwp.html

[S33] C++：vector 增删
来源：http://dali.daria6918.cn/Article/details/gt2hjihfzwt.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.dashuyun.cn/Article/details/gt2bdkxufuv.html

[S34] C++：遍历 vector
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uyujxbtv.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.meibo888.top/Article/details/gt2aqbhxznn.html

[S35] C++：map
来源：http://dali.kuanghao11.cn/Article/details/gt2ssvqqucv.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yhbxoftc.html

[S36] C++：unordered_map
来源：http://dali.pycfn.com/Article/details/gt2nlzkzlqk.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2acwfoppy.html

[S37] C++：set
来源：http://dali.tanke756.top/Article/details/gt2vfghowjr.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.jlsjyb.cn/Article/details/gt2qxczvhao.html

[S38] C++：排序
来源：http://dali.sufxvd.cn/Article/details/gt2ahlnpeff.html

std::sort(v.begin(), v.end());
来源：http://dali.jqgfzy.top/Article/details/gt2tayrgxsx.html

[S39] C++：自定义比较器排序
来源：http://dali.vqdsnc.cn/Article/details/gt2dzyxttcg.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.xuetiantiany.cn/Article/details/gt2rbovejrr.html

[S40] C++：查找元素
来源：http://dali.feifeiyinyue.top/Article/details/gt2dzpbibfw.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.ppjwa.cn/Article/details/gt2sbnsyiwd.html

[S41] C++：类与构造函数
来源：http://dali.ivvv.top/Article/details/gt2umxczkcc.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.chenzaomai.com/Article/details/gt2ncoreecg.html

[S42] C++：继承与虚函数
来源：http://dali.chenlongwang.top/Article/details/gt2vywwaybm.html

class B : public Base { public: void f() override {} };
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2aznzxeqe.html

[S43] C++：智能指针
来源：http://dali.iojbl.cn/Article/details/gt2thlhgzuy.html

auto p = std::make_unique<int>(5);
来源：http://dali.cdnleiting.top/Article/details/gt2nbfrcpzx.html

[S44] C++：引用传参
来源：http://dali.gaohongyu789.top/Article/details/gt2rdrhgvcj.html

void inc(int &x) { ++x; }
来源：http://dali.hfpthk.cn/Article/details/gt2xavmibet.html

[S45] C++：lambda
来源：http://dali.hammf.cn/Article/details/gt2gxsvpbjt.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.pycfn.com/Article/details/gt2keyceuuf.html

[S46] C++：函数模板
来源：http://dali.sysykeji.top/Article/details/gt2gdqmlryz.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.c1oappe.top/Article/details/gt2noaebcpq.html

[S47] C++：结构化绑定遍历
来源：http://dali.cashguo.top/Article/details/gt2expreaud.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.redwolf501.top/Article/details/gt2ttcjyupw.html

[S48] C++：逐行读文件
来源：http://dali.316326.xyz/Article/details/gt2rxzhekir.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.yj20258.top/Article/details/gt2dgvmjdga.html

while (std::getline(in, line)) { }
来源：http://dali.nanxuanxn.top/Article/details/gt2cznjoiuu.html

[S49] C++：写文件
来源：http://dali.yueranfly.top/Article/details/gt2yjtdxqmd.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.jinqigufen.top/Article/details/gt2jijmnsny.html

[S50] C++：格式化数字
来源：http://dali.hongshengwenyu.top/Article/details/gt2uleieynw.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.jyoumei.cn/Article/details/gt2exshmdee.html

[S51] C++：显式类型转换
来源：http://dali.sufxvd.cn/Article/details/gt2fnxxtbgm.html

static_cast<double>(a) / b
来源：http://dali.yongpay.top/Article/details/gt2yrrkzcyx.html

[S52] C++：const 与 noexcept
来源：http://dali.cqqwz.cn/Article/details/gt2nigtvtng.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cpqaltcs.html

[S53] C++：移动语义
来源：http://dali.tanke756.top/Article/details/gt2nriawqsw.html

std::vector<int> w = std::move(v);
来源：http://dali.cashguo.top/Article/details/gt2vnvgvefq.html

[S54] C++：异常处理
来源：http://dali.jinqigfzy.top/Article/details/gt2pazabcet.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.jqgufenzy.top/Article/details/gt2owyvyojc.html

[S55] C++：结构化绑定
来源：http://dali.c1oappe.top/Article/details/gt2mhczxatr.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.fengsongda.top/Article/details/gt2rclefkju.html

[S56] C++：optional
来源：http://dali.cqqwz.cn/Article/details/gt2yfmmmviz.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.shzxlz.cn/Article/details/gt2xzsonoht.html

[S57] C++：编译期常量
来源：http://dali.zhixingplan.top/Article/details/gt2knltpvma.html

constexpr int N = 10;
来源：http://dali.yj202588.top/Article/details/gt2mrpdkwvf.html

[S58] C++：命名空间
来源：http://dali.wangshuangyany.cn/Article/details/gt2rkycexic.html

namespace ns { int f() { return 1; } }
来源：http://dali.xuanzx.com/Article/details/gt2zlokgqph.html

[S59] C++：静态断言
来源：http://dali.tianlin.xyz/Article/details/gt2crhbcabl.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mmdwxxui.html

[S60] C++：遍历并删除元素
来源：http://dali.yuxming.cn/Article/details/gt2eakffpft.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.quarkkingdee.top/Article/details/gt2vyeolxnf.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dmoqvwpz.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.svipenyu.cn/Article/details/gt2imkefzna.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2ypubudwz.html

[T01] Kotlin：Hello World
来源：http://dali.jianghu66.top/Article/details/gt2pkrrsatx.html

println("Hello")
来源：http://dali.havefunace.top/Article/details/gt2znnorbsk.html

[T02] Kotlin：变量
来源：http://dali.zhixingplan.top/Article/details/gt2jiyfxnat.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.guannengcc.top/Article/details/gt2oapqjtyi.html

[T03] Kotlin：字符串模板
来源：http://dali.jqgufenzy.top/Article/details/gt2tvkjsczx.html

"值: $b"
来源：http://dali.jinqigufen.top/Article/details/gt2tnlcxumt.html

[T04] Kotlin：空安全
来源：http://dali.tianlin.xyz/Article/details/gt2jfpksnnh.html

val n: String? = null;  n?.length
来源：http://dali.fzhhl.top/Article/details/gt2pozffdfi.html

[T05] Kotlin：when 表达式
来源：http://dali.daxiang520.top/Article/details/gt2pllnwlxw.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.redwolf501.top/Article/details/gt2gwubsfaw.html

[T06] Kotlin：集合映射
来源：http://dali.jinqigufen.top/Article/details/gt2vzusrpxz.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.iojbl.cn/Article/details/gt2iswtvxjm.html

[T07] Kotlin：集合过滤
来源：http://dali.ppjwa.cn/Article/details/gt2immimuco.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qxcexkpd.html

[T08] Kotlin：数据类
来源：http://dali.jinqigufen.top/Article/details/gt2yytdztdt.html

data class User(val name: String, val age: Int)
来源：http://dali.aizwys.cn/Article/details/gt2ehraystq.html

[T09] Kotlin：扩展函数
来源：http://dali.zdqjudy.top/Article/details/gt2jpwwwuvl.html

fun String.exclaim() = this + "!"
来源：http://dali.jianghu66.top/Article/details/gt2knlibwaq.html

[T10] Kotlin：默认参数
来源：http://dali.xuanzx.com/Article/details/gt2ofxxluzo.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.pycfn.com/Article/details/gt2nbiluyfh.html

[T11] Kotlin：协程
来源：http://dali.shangyingyoupin.top/Article/details/gt2qbtgasxj.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2axmxblgx.html

[T12] Kotlin：解构声明
来源：http://dali.zhoulong.xyz/Article/details/gt2xtyrcjbq.html

val (a, b) = Pair(1, 2)
来源：http://dali.shangyingyoupin.top/Article/details/gt2fpfjalwd.html

[T13] Kotlin：只读 Map
来源：http://dali.hammf.cn/Article/details/gt2egrickhr.html

val m = mapOf("a" to 1)
来源：http://dali.zdqjudy.top/Article/details/gt2ezyxhejz.html

[T14] Kotlin：循环
来源：http://dali.chenzaomai.com/Article/details/gt2jymhawsm.html

for (i in 1..10) println(i)
来源：http://dali.xylfe.cn/Article/details/gt2lbjhmyzc.html

[T15] Kotlin：接口
来源：http://dali.0kj1m.cn/Article/details/gt2thlqbony.html

interface Shape { fun area(): Double }
来源：http://dali.yuxming.cn/Article/details/gt2jnpbtlkb.html

[T16] Swift：Hello World
来源：http://dali.ehwqpu.com/Article/details/gt2kwaqjbpc.html

print("Hello")
来源：http://dali.snrcjt.cn/Article/details/gt2sqvrtbal.html

[T17] Swift：变量与常量
来源：http://dali.fengsongda.top/Article/details/gt2elljpveq.html

var a = 1;  let b = 2
来源：http://dali.pengpengdd.cyou/Article/details/gt2nblpfzni.html

[T18] Swift：字符串插值
来源：http://dali.andypj.xyz/Article/details/gt2ndifjwvw.html

"值: \(b)"
来源：http://dali.tanke756.top/Article/details/gt2vltnqkfj.html

[T19] Swift：可选绑定
来源：http://dali.meibo888.top/Article/details/gt2zpblvalx.html

if let n = opt { print(n) }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lsrnheod.html

[T20] Swift：数组操作
来源：http://dali.hnqzz.top/Article/details/gt2ostdxrin.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nhwcevat.html

[T21] Swift：遍历
来源：http://dali.c1oappe.top/Article/details/gt2resovdwu.html

for x in a { print(x) }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zutihzcv.html

[T22] Swift：字典
来源：http://dali.yuxming.cn/Article/details/gt2dahgqbvi.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.cqqwz.cn/Article/details/gt2ppvtwzsp.html

[T23] Swift：函数
来源：http://dali.cheryme.top/Article/details/gt2mvcgmmzx.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.pycfn.com/Article/details/gt2yctxtbtj.html

[T24] Swift：闭包
来源：http://dali.yj202588.top/Article/details/gt2izitnput.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.nanxinkj.top/Article/details/gt2vusoxnxr.html

[T25] Swift：结构体
来源：http://dali.yuanzhike.top/Article/details/gt2dzjonoke.html

struct P { var x: Int }
来源：http://dali.yonumen.top/Article/details/gt2uzarvyan.html

[T26] Swift：类与重写
来源：http://dali.nwbrower.top/Article/details/gt2oqmaejxk.html

class A: Base { override func f() {} }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kanfntrq.html

[T27] Swift：错误处理
来源：http://dali.ppjwa.cn/Article/details/gt2erkpphwh.html

do { try f() } catch { print(error) }
来源：http://dali.aibaodan.cn/Article/details/gt2alyyvwes.html

[T28] Swift：枚举
来源：http://dali.tianlin.xyz/Article/details/gt2hhsqrnny.html

enum Color { case red, green }
来源：http://dali.xuetiantiany.cn/Article/details/gt2kmcgbdfb.html

[T29] Swift：guard 提前返回
来源：http://dali.xuetiantiany.cn/Article/details/gt2duhkqwvx.html

guard let x = opt else { return }
来源：http://dali.yonumen.top/Article/details/gt2dtauzein.html

[T30] Swift：协议
来源：http://dali.nwbrower.top/Article/details/gt2texozrio.html

protocol Shape { func area() -> Double }
来源：http://dali.aizwys.cn/Article/details/gt2eowymeid.html

[T31] Lua：Hello World
来源：http://dali.redwolf501.top/Article/details/gt2jtsupght.html

print("Hello")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ntfezuqf.html

[T32] Lua：局部变量
来源：http://dali.daxiang520.top/Article/details/gt2oxnjmgwg.html

local a = 1
来源：http://dali.hnxiangtu.top/Article/details/gt2ayaobyjn.html

[T33] Lua：表（数组）
来源：http://dali.0kj1m.cn/Article/details/gt2seoqgzqb.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.chenzaomai.com/Article/details/gt2qfjztopp.html

[T34] Lua：遍历表
来源：http://dali.jqgfzy.top/Article/details/gt2jqtsrtoi.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.haohaochexian.top/Article/details/gt2ztamnaxm.html

[T35] Lua：字典表
来源：http://dali.yj202588.top/Article/details/gt2ejqvkdpm.html

local d = { a = 1 };  d.b = 2
来源：http://dali.nanxuanxn.top/Article/details/gt2ezmdihhk.html

[T36] Lua：函数
来源：http://dali.yj202588.top/Article/details/gt2tpvimlmk.html

function add(a, b) return a + b end
来源：http://dali.feifeiyinyue.top/Article/details/gt2gqxenyzn.html

[T37] Lua：字符串拼接
来源：http://dali.shzxlz.cn/Article/details/gt2rdcffsrn.html

"a" .. "b"
来源：http://dali.yj20258.top/Article/details/gt2yombaxdu.html

[T38] Lua：条件
来源：http://dali.mhx1999.top/Article/details/gt2crgugjhl.html

if x > 0 then print("正") end
来源：http://dali.gzhubu.top/Article/details/gt2zyilcxjy.html

[T39] Lua：模式匹配
来源：http://dali.dianchejie.cn/Article/details/gt2phdtbeyh.html

string.find(s, "%d+")
来源：http://dali.gzhubu.top/Article/details/gt2hyprlfwg.html

[T40] Lua：元表
来源：http://dali.ppjwa.cn/Article/details/gt2hjndxlom.html

setmetatable({}, { __index = base })
来源：http://dali.havefunace.top/Article/details/gt2zuenchos.html

[T41] Perl：Hello World
来源：http://dali.sysykeji.top/Article/details/gt2ndulqhcy.html

print "Hello\n";
来源：http://dali.ydzc1.top/Article/details/gt2dwjjiwoh.html

[T42] Perl：变量类型
来源：http://dali.jqgfzy.top/Article/details/gt2qfjxjxrm.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.wangshuangyany.cn/Article/details/gt2pscjyjcq.html

[T43] Perl：字符串插值
来源：http://dali.dashuyun.cn/Article/details/gt2qoquzwsa.html

"值: $a"
来源：http://dali.yangfankeji.com/Article/details/gt2yciqxwgc.html

[T44] Perl：条件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wedoeoyl.html

if ($a > 0) { print "正"; }
来源：http://dali.zdqjudy.top/Article/details/gt2qgyoscaf.html

[T45] Perl：数组遍历
来源：http://dali.hfpthk.cn/Article/details/gt2fvjqesxv.html

for my $x (@arr) { print $x; }
来源：http://dali.yangfankeji.com/Article/details/gt2xcsqnzvs.html

[T46] Perl：哈希操作
来源：http://dali.jqgufenzy.top/Article/details/gt2xwwokapi.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.sxryk.cn/Article/details/gt2zughfxop.html

[T47] Perl：正则捕获
来源：http://dali.zhiwuduotai.top/Article/details/gt2mfoucmdt.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.sweek.top/Article/details/gt2shswrgvp.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2itxmvdwm.html

$s =~ s/old/new/g;
来源：http://dali.meibo888.top/Article/details/gt2pwnjsovh.html

[T49] Perl：函数
来源：http://dali.tanke756.top/Article/details/gt2ikawmxzl.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.tian-w.cn/Article/details/gt2frkbpuyx.html

[T50] Perl：逐行读文件
来源：http://dali.iojbl.cn/Article/details/gt2pzzsucsf.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.c1oappe.top/Article/details/gt2ebltmers.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.guowangkeji.top/Article/details/gt2sqqdnqkr.html

[T51] Scala：Hello World
来源：http://dali.fzhhl.top/Article/details/gt2ojhfizee.html

println("Hello")
来源：http://dali.jlsjyb.cn/Article/details/gt2rmmxvfvs.html

[T52] Scala：变量
来源：http://dali.yangfankeji.com/Article/details/gt2qpgekelp.html

val a = 1;  var b = 2
来源：http://dali.ybcxt.top/Article/details/gt2uiailidu.html

[T53] Scala：字符串插值
来源：http://dali.yj202588.top/Article/details/gt2wfsgvqqf.html

s"值: $b"
来源：http://dali.zhongyouzk.top/Article/details/gt2knnhzuou.html

[T54] Scala：集合映射
来源：http://dali.hywenlv.cn/Article/details/gt2qjmblyxf.html


<!-- 参考信息 -->