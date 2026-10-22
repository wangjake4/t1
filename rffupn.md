代发 wailian999

sed -i 's/foo/bar/g' a.txt
来源：http://dali.yangfankeji.com/Article/details/gt2ewhubojn.html

[R48] awk 取指定列
来源：http://dali.aizwys.cn/Article/details/gt2keftbckh.html

awk '{print $1, $3}' a.txt
来源：http://dali.hnqzz.top/Article/details/gt2dpzhcmbu.html

[R49] awk 带条件
来源：http://dali.0kj1m.cn/Article/details/gt2foidsfog.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.jqgfzy.top/Article/details/gt2ylfqpvsq.html

[R50] awk 求和
来源：http://dali.smart0.xyz/Article/details/gt2oaynqtel.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zdqjudy.top/Article/details/gt2qhwijdev.html

[R51] 排序去重取前几
来源：http://dali.xinyue.icu/Article/details/gt2dnxnxjbj.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bpozjdol.html

[R52] 统计行数
来源：http://dali.ppjwa.cn/Article/details/gt2nxxnamjl.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zmtdbxxb.html

[R53] 查看文件头与实时尾
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rqfftyoi.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.yongpay.top/Article/details/gt2smoidqlw.html

[R54] 比较两个文件
来源：http://dali.feifeiyinyue.top/Article/details/gt2edchrwez.html

diff a.txt b.txt
来源：http://dali.pengpengdd.cyou/Article/details/gt2pjbqygxd.html

[R55] 压缩与解压
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qxaudwny.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.hammf.cn/Article/details/gt2ejdagyjq.html

[R56] 远程拷贝
来源：http://dali.cdnleiting.top/Article/details/gt2hdujshuc.html

scp file user@host:/path/
来源：http://dali.andypj.xyz/Article/details/gt2pqvrmpek.html

[R57] 远程执行命令
来源：http://dali.yongpay.top/Article/details/gt2gglcyona.html

ssh user@host 'uptime'
来源：http://dali.cheryme.top/Article/details/gt2ohtwqbae.html

[R58] 下载文件
来源：http://dali.sxryk.cn/Article/details/gt2cdtflfjj.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.nanxuanxn.top/Article/details/gt2iydyvzah.html

[R59] 发 POST JSON
来源：http://dali.cqqwz.cn/Article/details/gt2necnqcpq.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.sxryk.cn/Article/details/gt2tebovcjc.html

[R60] 只看 HTTP 状态码
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dnzokxyo.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.dianchejie.cn/Article/details/gt2edrvwqlg.html

[R61] 磁盘占用
来源：http://dali.ppjwa.cn/Article/details/gt2ybugbzrd.html

df -h;  du -sh *
来源：http://dali.hysaishi.cn/Article/details/gt2tczqpkxf.html

[R62] 找最占空间的文件
来源：http://dali.dianchejie.cn/Article/details/gt2sfzqdcbt.html

du -ah . | sort -rh | head -10
来源：http://dali.fengsongda.top/Article/details/gt2sphdmzba.html

[R63] 内存与进程
来源：http://dali.sweek.top/Article/details/gt2glsfnryj.html

free -h;  ps aux | grep nginx
来源：http://dali.guannengcc.top/Article/details/gt2kypsronk.html

[R64] 结束进程
来源：http://dali.xziqi.cn/Article/details/gt2krehtznn.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhixingplan.top/Article/details/gt2jjjecpim.html

[R65] 查看端口占用
来源：http://dali.jqgfzy.top/Article/details/gt2qcqcnylb.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.fzhhl.top/Article/details/gt2gffqdwbr.html

[R66] 定时任务
来源：http://dali.nwbrower.top/Article/details/gt2unnrihon.html

crontab -e;  crontab -l
来源：http://dali.jlsjyb.cn/Article/details/gt2hxehnjce.html

[R67] 生成随机十六进制串
来源：http://dali.gogol.net.cn/Article/details/gt2tnawztbk.html

openssl rand -hex 16
来源：http://dali.yanxiufei.cn/Article/details/gt2itkgacxk.html

[R68] 计算文件校验值
来源：http://dali.ydzc1.top/Article/details/gt2bjxwpssj.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.chenjidiqi.icu/Article/details/gt2udkkqgdd.html

[R69] 生成随机密码
来源：http://dali.svipenyu.cn/Article/details/gt2zekqqurh.html

head -c 16 /dev/urandom | base64
来源：http://dali.svipenyu.cn/Article/details/gt2uuyvwtcw.html

[R70] 时间戳与互转
来源：http://dali.jyoumei.cn/Article/details/gt2eqosfkqz.html

date +%s;  date -d @1700000000
来源：http://dali.0kj1m.cn/Article/details/gt2zvrhovid.html

[R71] 日期格式化
来源：http://dali.shuidangran.top/Article/details/gt2cgrlympx.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.9152youxi.cn/Article/details/gt2kumqktdq.html

[R72] 等待端口就绪
来源：http://dali.cucudq.cn/Article/details/gt2jgyauden.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.jiagoushi.top/Article/details/gt2vhunirgs.html

[R73] 分割大日志
来源：http://dali.fzhhl.top/Article/details/gt2ifntsasc.html

split -l 1000 big.log part_
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bhdxdhea.html

[R74] 批量重命名
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tkhgleri.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.birdmap.top/Article/details/gt2sahshskk.html

[R75] 导出环境变量
来源：http://dali.yj202588.top/Article/details/gt2clvrpnyc.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.jianghu66.top/Article/details/gt2iwmkladt.html

[R76] 使用临时文件
来源：http://dali.zycfv.cn/Article/details/gt2uwwmpsvi.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.gotoacloud.top/Article/details/gt2truqahcv.html

[R77] 读取用户输入
来源：http://dali.0kj1m.cn/Article/details/gt2bhhpqggq.html

read -rp "请输入: " ans
来源：http://dali.xuanzx.com/Article/details/gt2josauqmj.html

[R78] 交互式菜单
来源：http://dali.jqgfzy.top/Article/details/gt2ivpzfrfx.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.aibaodan.cn/Article/details/gt2egczaxhp.html

[R79] 解析命令行选项
来源：http://dali.cdnleiting.top/Article/details/gt2nkzecuvf.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhengqikj.top/Article/details/gt2hawjkfgh.html

[R80] 查看脚本执行耗时
来源：http://dali.hnqzz.top/Article/details/gt2gwkixviq.html

time ./run.sh
来源：http://dali.hysaishi.cn/Article/details/gt2fnzhzzfk.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gt2vxbqinnm.html

S. C / C++ 专题
来源：http://dali.yuanzhike.top/Article/details/gt2vhinnolg.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2oqacfsqs.html

[S01] C：Hello World
来源：http://dali.shangyingyoupin.top/Article/details/gt2aiotwsby.html

#include <stdio.h>
来源：http://dali.zycfv.cn/Article/details/gt2vkrpkpuw.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhoulong.xyz/Article/details/gt2fzcpqrbq.html

[S02] C：变量与格式化输出
来源：http://dali.gaohongyu789.top/Article/details/gt2fmppotnr.html

int a = 10; printf("%d\n", a);
来源：http://dali.quarkkingdee.top/Article/details/gt2knwaruyk.html

[S03] C：读入整数
来源：http://dali.tian-w.cn/Article/details/gt2qaaskkyu.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2ehdbnqlv.html

[S04] C：字符串复制
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ymefstml.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gyfgsjev.html

[S05] C：字符串长度
来源：http://dali.wangshuangyany.cn/Article/details/gt2obozyqum.html

strlen(s)
来源：http://dali.fengsongda.top/Article/details/gt2pmatizlh.html

[S06] C：字符串比较
来源：http://dali.sxryk.cn/Article/details/gt2xgwfuqni.html

strcmp(a, b) == 0
来源：http://dali.haohaochexian.top/Article/details/gt2umnqvyra.html

[S07] C：数组遍历求和
来源：http://dali.ppjwa.cn/Article/details/gt2ljhbbfiu.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.meibo888.top/Article/details/gt2wddvecyh.html

[S08] C：动态内存分配与释放
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hphbwqmx.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.tian-w.cn/Article/details/gt2axhrnarf.html

[S09] C：结构体定义与初始化
来源：http://dali.yj202588.top/Article/details/gt2umrxgllp.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sgryumlu.html

[S10] C：指针与解引用
来源：http://dali.tian-w.cn/Article/details/gt2zgojicnz.html

int *p = &a;  *p = 5;
来源：http://dali.daria6918.cn/Article/details/gt2bfsfpgrd.html

[S11] C：逐行读文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zdozkwbb.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.chenzaomai.com/Article/details/gt2mnqpmufc.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zdqjudy.top/Article/details/gt2oxzutrpa.html

fclose(f);
来源：http://dali.redwolf501.top/Article/details/gt2huavotcj.html

[S12] C：写文件
来源：http://dali.chenlongwang.top/Article/details/gt2kpppvfiv.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.ehwqpu.com/Article/details/gt2hwidwrts.html

[S13] C：宏定义
来源：http://dali.kuanghao11.cn/Article/details/gt2jpcflqjo.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.wangshuangyany.cn/Article/details/gt2egcbanoo.html

[S14] C：枚举
来源：http://dali.316326.xyz/Article/details/gt2rqmwdzwg.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.cqqwz.cn/Article/details/gt2odpgfmps.html

[S15] C：类型转换
来源：http://dali.cucudq.cn/Article/details/gt2ewhzufrv.html

(double) a / b
来源：http://dali.nwbrower.top/Article/details/gt2kkpojemw.html

[S16] C：位操作置位
来源：http://dali.snrcjt.cn/Article/details/gt2epwpyrsj.html

x |= (1 << 3);
来源：http://dali.quarkkingdee.top/Article/details/gt2qlbsiazp.html

[S17] C：安全拼接字符串
来源：http://dali.hammf.cn/Article/details/gt2vhadzjkt.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.sysykeji.top/Article/details/gt2fuzszkmt.html

[S18] C：命令行参数
来源：http://dali.tian-w.cn/Article/details/gt2asfrymfp.html

int main(int argc, char **argv)
来源：http://dali.hammf.cn/Article/details/gt2lpuwbxax.html

[S19] C：快速排序
来源：http://dali.ppjwa.cn/Article/details/gt2ztbrazos.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.feifeiyinyue.top/Article/details/gt2rcdnjmuo.html

[S20] C：二分查找
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lgdovyfv.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.svipenyu.cn/Article/details/gt2hdlzbien.html

[S21] C：字符类别判断
来源：http://dali.yonumen.top/Article/details/gt2zxutpsor.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.yj20258888.top/Article/details/gt2qotzycyl.html

[S22] C：字符串转数字
来源：http://dali.yuanzhike.top/Article/details/gt2zwkvjlsy.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.chenjidiqi.icu/Article/details/gt2goorchdb.html

[S23] C：随机数
来源：http://dali.0kj1m.cn/Article/details/gt2lqznyngw.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.cashguo.top/Article/details/gt2xikyitmj.html

[S24] C：获取本地时间
来源：http://dali.ydzc1.top/Article/details/gt2ajycucni.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.nwbrower.top/Article/details/gt2tfrmmncy.html

[S25] C：内存拷贝
来源：http://dali.hammf.cn/Article/details/gt2rlmwopyt.html

memcpy(dst, src, n);
来源：http://dali.tian-w.cn/Article/details/gt2xwvxsujw.html

[S26] C：内存清零
来源：http://dali.hammf.cn/Article/details/gt2xfyidckw.html

memset(a, 0, sizeof a);
来源：http://dali.snrcjt.cn/Article/details/gt2uhhtqvoy.html

[S27] C：定义常量
来源：http://dali.pycfn.com/Article/details/gt2tujrsddr.html

const double PI = 3.14159;
来源：http://dali.zhixingplan.top/Article/details/gt2ihyeqptm.html

[S28] C：静态变量
来源：http://dali.svipenyu.cn/Article/details/gt2ccnakefr.html

static int counter = 0;
来源：http://dali.cashguo.top/Article/details/gt2pjhrnhfl.html

[S29] C：变参函数
来源：http://dali.havefunace.top/Article/details/gt2uxqdygzh.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.pengpengdd.cyou/Article/details/gt2duwbkwhc.html

[S30] C：头文件保护
来源：http://dali.nanxuanxn.top/Article/details/gt2anftlofp.html

#ifndef X_H
来源：http://dali.jinqigfzy.top/Article/details/gt2iivmuzeg.html

#define X_H
来源：http://dali.wangdashe.top/Article/details/gt2qjhbiqwb.html

#endif
来源：http://dali.zhengqikj.top/Article/details/gt2yimsbasr.html

[S31] C++：Hello World
来源：http://dali.gaohongyu789.top/Article/details/gt2cealptow.html

#include <iostream>
来源：http://dali.ydzc1.top/Article/details/gt2vxggvzok.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.sysykeji.top/Article/details/gt2raidnywf.html

[S32] C++：字符串
来源：http://dali.ivvv.top/Article/details/gt2neamdekg.html

std::string s = "hi";  s += "!";
来源：http://dali.nwbrower.top/Article/details/gt2usxmdgoq.html

[S33] C++：vector 增删
来源：http://dali.9152youxi.cn/Article/details/gt2upelqnhs.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.gotoacloud.top/Article/details/gt2rvgdkhyo.html

[S34] C++：遍历 vector
来源：http://dali.bjfxy.top/Article/details/gt2vnisrlth.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.hywenlv.cn/Article/details/gt2zjdbkdqb.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2pfagmwgc.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.0kj1m.cn/Article/details/gt2bapyjsah.html

[S36] C++：unordered_map
来源：http://dali.kuanghao11.cn/Article/details/gt2oljvbjua.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.nanxuanxn.top/Article/details/gt2xpvxevuc.html

[S37] C++：set
来源：http://dali.shuidangran.top/Article/details/gt2yzerkbgf.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.hnxiangtu.top/Article/details/gt2jyaiwmuo.html

[S38] C++：排序
来源：http://dali.jinqigfzy.top/Article/details/gt2ifbiogxc.html

std::sort(v.begin(), v.end());
来源：http://dali.hnqzz.top/Article/details/gt2iapsjoep.html

[S39] C++：自定义比较器排序
来源：http://dali.nwbrower.top/Article/details/gt2bgiirzna.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.yongpay.top/Article/details/gt2caqhpozf.html

[S40] C++：查找元素
来源：http://dali.sufxvd.cn/Article/details/gt2okflappi.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.cqqwz.cn/Article/details/gt2vablgcxh.html

[S41] C++：类与构造函数
来源：http://dali.ivvv.top/Article/details/gt2nasexaol.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.xuanzx.com/Article/details/gt2afzzgcki.html

[S42] C++：继承与虚函数
来源：http://dali.mhx1999.top/Article/details/gt2rwhomjum.html

class B : public Base { public: void f() override {} };
来源：http://dali.fengsongda.top/Article/details/gt2kqkqstbw.html

[S43] C++：智能指针
来源：http://dali.dianchejie.cn/Article/details/gt2itxxvggh.html

auto p = std::make_unique<int>(5);
来源：http://dali.hfpthk.cn/Article/details/gt2csffrtdj.html

[S44] C++：引用传参
来源：http://dali.hysaishi.cn/Article/details/gt2fnguzbly.html

void inc(int &x) { ++x; }
来源：http://dali.cqqwz.cn/Article/details/gt2axqnudky.html

[S45] C++：lambda
来源：http://dali.nwbrower.top/Article/details/gt2tnobmvys.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.yj20258.top/Article/details/gt2fsmaamtk.html

[S46] C++：函数模板
来源：http://dali.jqgufenzy.top/Article/details/gt2cuqnoisl.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.yj20258.top/Article/details/gt2csxdmrpg.html

[S47] C++：结构化绑定遍历
来源：http://dali.ehwqpu.com/Article/details/gt2qcmilajs.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.pycfn.com/Article/details/gt2jsfnxfob.html

[S48] C++：逐行读文件
来源：http://dali.ivvv.top/Article/details/gt2mzkmudjc.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.sysykeji.top/Article/details/gt2ektcyyqj.html

while (std::getline(in, line)) { }
来源：http://dali.jinqigfzy.top/Article/details/gt2djuncqdp.html

[S49] C++：写文件
来源：http://dali.kuanghao11.cn/Article/details/gt2apxvvhkk.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.jqgufenzy.top/Article/details/gt2vdifvysg.html

[S50] C++：格式化数字
来源：http://dali.smart0.xyz/Article/details/gt2txhniihm.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mkfndayd.html

[S51] C++：显式类型转换
来源：http://dali.sweek.top/Article/details/gt2qtepypgy.html

static_cast<double>(a) / b
来源：http://dali.zhengqikj.top/Article/details/gt2wfqxdlji.html

[S52] C++：const 与 noexcept
来源：http://dali.cashguo.top/Article/details/gt2nbdflmll.html

int size() const noexcept { return n_; }
来源：http://dali.cashguo.top/Article/details/gt2vtjmaxoo.html

[S53] C++：移动语义
来源：http://dali.zdqjudy.top/Article/details/gt2ddbltven.html

std::vector<int> w = std::move(v);
来源：http://dali.quarkkingdee.top/Article/details/gt2yewyxiqh.html

[S54] C++：异常处理
来源：http://dali.sweek.top/Article/details/gt2tgmtjyoq.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.ehwqpu.com/Article/details/gt2zfxyyfvf.html

[S55] C++：结构化绑定
来源：http://dali.cdnleiting.top/Article/details/gt2jmtuhuuf.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.yueranfly.top/Article/details/gt2olwspwtk.html

[S56] C++：optional
来源：http://dali.birdmap.top/Article/details/gt2rhknxdqr.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.andypj.xyz/Article/details/gt2jupitjta.html

[S57] C++：编译期常量
来源：http://dali.yuanzhike.top/Article/details/gt2asajebjl.html

constexpr int N = 10;
来源：http://dali.zhiwuduotai.top/Article/details/gt2vbcgpahz.html

[S58] C++：命名空间
来源：http://dali.zhongyouzk.top/Article/details/gt2xbtldcrq.html

namespace ns { int f() { return 1; } }
来源：http://dali.cheryme.top/Article/details/gt2iyhlnbge.html

[S59] C++：静态断言
来源：http://dali.zdqjudy.top/Article/details/gt2yplnqivc.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.yj20258888.top/Article/details/gt2eucbvqjl.html

[S60] C++：遍历并删除元素
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nttfnooe.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.yuanzhike.top/Article/details/gt2fnewdzpz.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2sawtfnaa.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.ybcxt.top/Article/details/gt2prbeqhnc.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gt2bxrmmkam.html

[T01] Kotlin：Hello World
来源：http://dali.jiagoushi.top/Article/details/gt2zavicdrq.html

println("Hello")
来源：http://dali.hywenlv.cn/Article/details/gt2mcuxjfxd.html

[T02] Kotlin：变量
来源：http://dali.mhx1999.top/Article/details/gt2zmqhwjxz.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.xuanzx.com/Article/details/gt2aobwmbzv.html

[T03] Kotlin：字符串模板
来源：http://dali.daxiang520.top/Article/details/gt2yxtqumiz.html

"值: $b"
来源：http://dali.haohaochexian.top/Article/details/gt2gnkfjewq.html

[T04] Kotlin：空安全
来源：http://dali.aizwys.cn/Article/details/gt2xcfumoxo.html

val n: String? = null;  n?.length
来源：http://dali.cheryme.top/Article/details/gt2xgsjnmdv.html

[T05] Kotlin：when 表达式
来源：http://dali.yvedp.cn/Article/details/gt2rloysaue.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.xziqi.cn/Article/details/gt2jloctsym.html

[T06] Kotlin：集合映射
来源：http://dali.birdmap.top/Article/details/gt2smpxadmd.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.havefunace.top/Article/details/gt2ymahnuhp.html

[T07] Kotlin：集合过滤
来源：http://dali.quarkkingdee.top/Article/details/gt2xbtkense.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.ppjwa.cn/Article/details/gt2jmcxfstj.html

[T08] Kotlin：数据类
来源：http://dali.andypj.xyz/Article/details/gt2ztevsvtg.html

data class User(val name: String, val age: Int)
来源：http://dali.hnqzz.top/Article/details/gt2lrtjnatj.html

[T09] Kotlin：扩展函数
来源：http://dali.sysykeji.top/Article/details/gt2asrvbbwl.html

fun String.exclaim() = this + "!"
来源：http://dali.jianghu66.top/Article/details/gt2xsedejfe.html

[T10] Kotlin：默认参数
来源：http://dali.jqgufenzy.top/Article/details/gt2vmynalnd.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.smart0.xyz/Article/details/gt2oblytkjd.html

[T11] Kotlin：协程
来源：http://dali.havefunace.top/Article/details/gt2kbqplgyh.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.shuidangran.top/Article/details/gt2sjkryrqn.html

[T12] Kotlin：解构声明
来源：http://dali.jqgfzy.top/Article/details/gt2qsghwytw.html

val (a, b) = Pair(1, 2)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ntowiicv.html

[T13] Kotlin：只读 Map
来源：http://dali.ppjwa.cn/Article/details/gt2sxjnjjil.html

val m = mapOf("a" to 1)
来源：http://dali.yonumen.top/Article/details/gt2ecjrztdr.html

[T14] Kotlin：循环
来源：http://dali.zhoulong.xyz/Article/details/gt2dccbgfwm.html

for (i in 1..10) println(i)
来源：http://dali.haohaochexian.top/Article/details/gt2yjhpozha.html

[T15] Kotlin：接口
来源：http://dali.svipenyu.cn/Article/details/gt2uodyepju.html

interface Shape { fun area(): Double }
来源：http://dali.feifeiyinyue.top/Article/details/gt2ytxnocft.html

[T16] Swift：Hello World
来源：http://dali.sufxvd.cn/Article/details/gt2pzgaffro.html

print("Hello")
来源：http://dali.hysaishi.cn/Article/details/gt2zvytfmbs.html

[T17] Swift：变量与常量
来源：http://dali.guowangkeji.top/Article/details/gt2madjftnm.html

var a = 1;  let b = 2
来源：http://dali.smart0.xyz/Article/details/gt2vemzegjx.html

[T18] Swift：字符串插值
来源：http://dali.316326.xyz/Article/details/gt2mmhdgsik.html

"值: \(b)"
来源：http://dali.hnxiangtu.top/Article/details/gt2djjwbsmc.html

[T19] Swift：可选绑定
来源：http://dali.hysaishi.cn/Article/details/gt2myofwdmd.html

if let n = opt { print(n) }
来源：http://dali.hnxiangtu.top/Article/details/gt2cpxzbuzb.html

[T20] Swift：数组操作
来源：http://dali.pengpengdd.cyou/Article/details/gt2ojbzcfdu.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.yj20258.top/Article/details/gt2uhafuqct.html

[T21] Swift：遍历
来源：http://dali.jiagoushi.top/Article/details/gt2uwhmpbdh.html

for x in a { print(x) }
来源：http://dali.jinqigfzy.top/Article/details/gt2xpyofuoq.html

[T22] Swift：字典
来源：http://dali.tanke756.top/Article/details/gt2fkbrrpaw.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.xylfe.cn/Article/details/gt2nvnxwoai.html

[T23] Swift：函数
来源：http://dali.nanxinkj.top/Article/details/gt2paeqioxo.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.hammf.cn/Article/details/gt2zizwoqvz.html

[T24] Swift：闭包
来源：http://dali.xuetiantiany.cn/Article/details/gt2gmlnluxk.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.fengsongda.top/Article/details/gt2phoagzbe.html

[T25] Swift：结构体
来源：http://dali.c1oappe.top/Article/details/gt2bunncojg.html

struct P { var x: Int }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qpizmnmc.html

[T26] Swift：类与重写
来源：http://dali.jqgfzy.top/Article/details/gt2admyzpqx.html

class A: Base { override func f() {} }
来源：http://dali.nwbrower.top/Article/details/gt2pmjlottc.html

[T27] Swift：错误处理
来源：http://dali.birdmap.top/Article/details/gt2wzvcmpbl.html

do { try f() } catch { print(error) }
来源：http://dali.nanxinkj.top/Article/details/gt2xvqrencf.html

[T28] Swift：枚举
来源：http://dali.pengpengdd.cyou/Article/details/gt2yanxspsb.html

enum Color { case red, green }
来源：http://dali.nanxinkj.top/Article/details/gt2ziaqdaed.html

[T29] Swift：guard 提前返回
来源：http://dali.shangyingyoupin.top/Article/details/gt2kcscwuca.html

guard let x = opt else { return }
来源：http://dali.tianlin.xyz/Article/details/gt2vndwcwmy.html

[T30] Swift：协议
来源：http://dali.316326.xyz/Article/details/gt2taoyxcej.html

protocol Shape { func area() -> Double }
来源：http://dali.chenzaomai.com/Article/details/gt2pgjtkfuf.html

[T31] Lua：Hello World
来源：http://dali.cucudq.cn/Article/details/gt2uwgnbsog.html

print("Hello")
来源：http://dali.kuanghao11.cn/Article/details/gt2sfwqfyda.html

[T32] Lua：局部变量
来源：http://dali.daxiang520.top/Article/details/gt2styinbrz.html

local a = 1
来源：http://dali.gotoacloud.top/Article/details/gt2jhlatlam.html

[T33] Lua：表（数组）
来源：http://dali.havefunace.top/Article/details/gt2irbztxxs.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.hongshengwenyu.top/Article/details/gt2dwtqzdwh.html

[T34] Lua：遍历表
来源：http://dali.jiagoushi.top/Article/details/gt2yfgwddiz.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.haohaochexian.top/Article/details/gt2tzrldtuk.html

[T35] Lua：字典表
来源：http://dali.tianlin.xyz/Article/details/gt2barzrsyf.html

local d = { a = 1 };  d.b = 2
来源：http://dali.xuetiantiany.cn/Article/details/gt2nvwattye.html

[T36] Lua：函数
来源：http://dali.chenzaomai.com/Article/details/gt2hoqyjvam.html

function add(a, b) return a + b end
来源：http://dali.hfpthk.cn/Article/details/gt2ufkogiyx.html

[T37] Lua：字符串拼接
来源：http://dali.havefunace.top/Article/details/gt2aetvyrjf.html

"a" .. "b"
来源：http://dali.dianchejie.cn/Article/details/gt2ljhvfxst.html

[T38] Lua：条件
来源：http://dali.guowangkeji.top/Article/details/gt2vbkjwsqu.html

if x > 0 then print("正") end
来源：http://dali.pengpengdd.cyou/Article/details/gt2eabybgpv.html

[T39] Lua：模式匹配
来源：http://dali.birdmap.top/Article/details/gt2tyvdfbim.html

string.find(s, "%d+")
来源：http://dali.ydzc1.top/Article/details/gt2eikzmphq.html

[T40] Lua：元表
来源：http://dali.feifeiyinyue.top/Article/details/gt2esqimqar.html

setmetatable({}, { __index = base })
来源：http://dali.snrcjt.cn/Article/details/gt2wnasbyyz.html

[T41] Perl：Hello World
来源：http://dali.smart0.xyz/Article/details/gt2cqbpzddc.html

print "Hello\n";
来源：http://dali.jinqigfzy.top/Article/details/gt2ahcjyrxd.html

[T42] Perl：变量类型
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vrkhdovl.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.hongshengwenyu.top/Article/details/gt2expzpdrk.html

[T43] Perl：字符串插值
来源：http://dali.bjfxy.top/Article/details/gt2lgnmdzud.html

"值: $a"
来源：http://dali.ehwqpu.com/Article/details/gt2edrrujyy.html

[T44] Perl：条件
来源：http://dali.jinqigufen.top/Article/details/gt2nfmyihsv.html

if ($a > 0) { print "正"; }
来源：http://dali.haohaochexian.top/Article/details/gt2wcekbeie.html

[T45] Perl：数组遍历
来源：http://dali.jiagoushi.top/Article/details/gt2lcbkhwyj.html

for my $x (@arr) { print $x; }
来源：http://dali.ppjwa.cn/Article/details/gt2oqxlcaui.html

[T46] Perl：哈希操作
来源：http://dali.0kj1m.cn/Article/details/gt2xrkezwpg.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.ppjwa.cn/Article/details/gt2adbktktt.html

[T47] Perl：正则捕获
来源：http://dali.xuanzx.com/Article/details/gt2dguyxxsa.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.shuidangran.top/Article/details/gt2kqdyqsek.html

[T48] Perl：正则替换
来源：http://dali.yj20258.top/Article/details/gt2elljykqt.html

$s =~ s/old/new/g;
来源：http://dali.tian-w.cn/Article/details/gt2kguthhpy.html

[T49] Perl：函数
来源：http://dali.tian-w.cn/Article/details/gt2jyliixvg.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.gzhubu.top/Article/details/gt2oomgybwr.html

[T50] Perl：逐行读文件
来源：http://dali.guowangkeji.top/Article/details/gt2smyoblns.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.vqdsnc.cn/Article/details/gt2zobpcvjk.html


<!-- 参考信息 -->