代发 wailian999

find . -name "*.tmp" -delete
来源：http://dali.xuanzx.com/Article/details/gt2rhvklgzb.html

[R46] 递归替换文件内容
来源：http://dali.cqqwz.cn/Article/details/gt2wsmsoqtc.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.shuidangran.top/Article/details/gt2xgpopmat.html

[R47] sed 单行替换
来源：http://dali.jqgufenzy.top/Article/details/gt2yewwlvri.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.sweek.top/Article/details/gt2fefvslle.html

[R48] awk 取指定列
来源：http://dali.hnxiangtu.top/Article/details/gt2niihpzwr.html

awk '{print $1, $3}' a.txt
来源：http://dali.hongshengwenyu.top/Article/details/gt2zcyrenho.html

[R49] awk 带条件
来源：http://dali.zhixingplan.top/Article/details/gt2gjjnwdue.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.yj20258888.top/Article/details/gt2tlzlmaln.html

[R50] awk 求和
来源：http://dali.zhixingplan.top/Article/details/gt2urdxxwmh.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.birdmap.top/Article/details/gt2ldmlnlbr.html

[R51] 排序去重取前几
来源：http://dali.ehwqpu.com/Article/details/gt2idfvqzcq.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.hfpthk.cn/Article/details/gt2ldhbutdz.html

[R52] 统计行数
来源：http://dali.cucudq.cn/Article/details/gt2zctbmwud.html

wc -l a.txt
来源：http://dali.sxryk.cn/Article/details/gt2lfuhyral.html

[R53] 查看文件头与实时尾
来源：http://dali.zhongyouzk.top/Article/details/gt2ukwfemko.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.0kj1m.cn/Article/details/gt2euyjwqlo.html

[R54] 比较两个文件
来源：http://dali.jlsjyb.cn/Article/details/gt2hneptbbz.html

diff a.txt b.txt
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lrraahbr.html

[R55] 压缩与解压
来源：http://dali.c1oappe.top/Article/details/gt2ewaalwhe.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wksphedh.html

[R56] 远程拷贝
来源：http://dali.jinqigufen.top/Article/details/gt2nrhmacad.html

scp file user@host:/path/
来源：http://dali.aizwys.cn/Article/details/gt2uvbnsfup.html

[R57] 远程执行命令
来源：http://dali.jyoumei.cn/Article/details/gt2mwjhgnol.html

ssh user@host 'uptime'
来源：http://dali.aibaodan.cn/Article/details/gt2pnxvfztq.html

[R58] 下载文件
来源：http://dali.tian-w.cn/Article/details/gt2tybnlucs.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.chenlongwang.top/Article/details/gt2volyaacm.html

[R59] 发 POST JSON
来源：http://dali.birdmap.top/Article/details/gt2rmwgvjmz.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.gaohongyu789.top/Article/details/gt2qfvepmxq.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2vwjcsmop.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.sufxvd.cn/Article/details/gt2kthwmyny.html

[R61] 磁盘占用
来源：http://dali.tanke756.top/Article/details/gt2ixgnrvlg.html

df -h;  du -sh *
来源：http://dali.xziqi.cn/Article/details/gt2wqygusdb.html

[R62] 找最占空间的文件
来源：http://dali.pycfn.com/Article/details/gt2wuctbuuq.html

du -ah . | sort -rh | head -10
来源：http://dali.zhixingplan.top/Article/details/gt2lwbzkiff.html

[R63] 内存与进程
来源：http://dali.daxiang520.top/Article/details/gt2jrkqenlt.html

free -h;  ps aux | grep nginx
来源：http://dali.yonumen.top/Article/details/gt2oxihvmjl.html

[R64] 结束进程
来源：http://dali.yangfankeji.com/Article/details/gt2uxtrcrhf.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhoulong.xyz/Article/details/gt2alhbrapx.html

[R65] 查看端口占用
来源：http://dali.svipenyu.cn/Article/details/gt2ekjcszzx.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lwtlkcjj.html

[R66] 定时任务
来源：http://dali.yuxming.cn/Article/details/gt2hmjbzejz.html

crontab -e;  crontab -l
来源：http://dali.jyoumei.cn/Article/details/gt2aactnfox.html

[R67] 生成随机十六进制串
来源：http://dali.nanxinkj.top/Article/details/gt2zdblsrle.html

openssl rand -hex 16
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qckayahx.html

[R68] 计算文件校验值
来源：http://dali.cheryme.top/Article/details/gt2culiclcp.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.xuanzx.com/Article/details/gt2dnflcoqt.html

[R69] 生成随机密码
来源：http://dali.gotoacloud.top/Article/details/gt2azrpokii.html

head -c 16 /dev/urandom | base64
来源：http://dali.hammf.cn/Article/details/gt2uimxzvqo.html

[R70] 时间戳与互转
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2krhilxpd.html

date +%s;  date -d @1700000000
来源：http://dali.sysykeji.top/Article/details/gt2pfakbijg.html

[R71] 日期格式化
来源：http://dali.haohaochexian.top/Article/details/gt2jddxylgs.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.nwbrower.top/Article/details/gt2bluvzdde.html

[R72] 等待端口就绪
来源：http://dali.tian-w.cn/Article/details/gt2hripfqvl.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.yueranfly.top/Article/details/gt2oscqfqdx.html

[R73] 分割大日志
来源：http://dali.yueranfly.top/Article/details/gt2cjlypxht.html

split -l 1000 big.log part_
来源：http://dali.iojbl.cn/Article/details/gt2xadakarp.html

[R74] 批量重命名
来源：http://dali.hfpthk.cn/Article/details/gt2nfzpnexa.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.tian-w.cn/Article/details/gt2jojcuomw.html

[R75] 导出环境变量
来源：http://dali.birdmap.top/Article/details/gt2hcuyottf.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.hfpthk.cn/Article/details/gt2wvzruamj.html

[R76] 使用临时文件
来源：http://dali.tianlin.xyz/Article/details/gt2ifqlcjrl.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.yueranfly.top/Article/details/gt2uinokiag.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2nljozief.html

read -rp "请输入: " ans
来源：http://dali.guowangkeji.top/Article/details/gt2aaoiicgz.html

[R78] 交互式菜单
来源：http://dali.shuidangran.top/Article/details/gt2rcptfact.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.cheryme.top/Article/details/gt2sapuzkbg.html

[R79] 解析命令行选项
来源：http://dali.yj202588.top/Article/details/gt2cpqgtlou.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.tian-w.cn/Article/details/gt2hdgxxxzc.html

[R80] 查看脚本执行耗时
来源：http://dali.birdmap.top/Article/details/gt2zcmlcwtv.html

time ./run.sh
来源：http://dali.gzhubu.top/Article/details/gt2vaaruzlr.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gt2letctqak.html

S. C / C++ 专题
来源：http://dali.svipenyu.cn/Article/details/gt2vysansmy.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gt2dexvapwe.html

[S01] C：Hello World
来源：http://dali.bjfxy.top/Article/details/gt2iassoadk.html

#include <stdio.h>
来源：http://dali.snrcjt.cn/Article/details/gt2ucyiqobn.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhoulong.xyz/Article/details/gt2roemynzd.html

[S02] C：变量与格式化输出
来源：http://dali.hnxiangtu.top/Article/details/gt2ijuucbig.html

int a = 10; printf("%d\n", a);
来源：http://dali.sweek.top/Article/details/gt2lybiucsl.html

[S03] C：读入整数
来源：http://dali.shuidangran.top/Article/details/gt2vpdbifbe.html

int x; scanf("%d", &x);
来源：http://dali.316326.xyz/Article/details/gt2ouyqrolq.html

[S04] C：字符串复制
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2krzajoxg.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.yj20258888.top/Article/details/gt2glirvppg.html

[S05] C：字符串长度
来源：http://dali.sweek.top/Article/details/gt2utaoovjc.html

strlen(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2abkcxggu.html

[S06] C：字符串比较
来源：http://dali.yongpay.top/Article/details/gt2eanfzkpg.html

strcmp(a, b) == 0
来源：http://dali.shzxlz.cn/Article/details/gt2nyqslupv.html

[S07] C：数组遍历求和
来源：http://dali.hysaishi.cn/Article/details/gt2ayjgoxle.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.yanxiufei.cn/Article/details/gt2guyjoekk.html

[S08] C：动态内存分配与释放
来源：http://dali.zhoulong.xyz/Article/details/gt2gevhjcot.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.jinqigfzy.top/Article/details/gt2ssifkcob.html

[S09] C：结构体定义与初始化
来源：http://dali.ydzc1.top/Article/details/gt2myqwwnfz.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.andypj.xyz/Article/details/gt2yzlbaaqc.html

[S10] C：指针与解引用
来源：http://dali.zhengqikj.top/Article/details/gt2bwfjebwz.html

int *p = &a;  *p = 5;
来源：http://dali.gogol.net.cn/Article/details/gt2tiyrzdax.html

[S11] C：逐行读文件
来源：http://dali.cashguo.top/Article/details/gt2ckniivto.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhixingplan.top/Article/details/gt2olgjrkpk.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.jiagoushi.top/Article/details/gt2vifgmvjp.html

fclose(f);
来源：http://dali.bjfxy.top/Article/details/gt2mbtrxffm.html

[S12] C：写文件
来源：http://dali.yongpay.top/Article/details/gt2zyovavwh.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.svipenyu.cn/Article/details/gt2cfgoxqnd.html

[S13] C：宏定义
来源：http://dali.hywenlv.cn/Article/details/gt2akplrtpf.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.yueranfly.top/Article/details/gt2okqapjgl.html

[S14] C：枚举
来源：http://dali.c1oappe.top/Article/details/gt2ppsooonf.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.sysykeji.top/Article/details/gt2nafucesu.html

[S15] C：类型转换
来源：http://dali.316326.xyz/Article/details/gt2dxyndeyo.html

(double) a / b
来源：http://dali.haohaochexian.top/Article/details/gt2usvgxzed.html

[S16] C：位操作置位
来源：http://dali.zhiwuduotai.top/Article/details/gt2fkebfdxo.html

x |= (1 << 3);
来源：http://dali.yj202588.top/Article/details/gt2otkreflc.html

[S17] C：安全拼接字符串
来源：http://dali.gaohongyu789.top/Article/details/gt2jwuigakm.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.gotoacloud.top/Article/details/gt2zkyoepit.html

[S18] C：命令行参数
来源：http://dali.yj20258.top/Article/details/gt2svqczezr.html

int main(int argc, char **argv)
来源：http://dali.yvedp.cn/Article/details/gt2vfwibmss.html

[S19] C：快速排序
来源：http://dali.yj20258.top/Article/details/gt2kdjswwqx.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.yonumen.top/Article/details/gt2lghxyygv.html

[S20] C：二分查找
来源：http://dali.jlsjyb.cn/Article/details/gt2trguvhky.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.hnqzz.top/Article/details/gt2fekgmuvc.html

[S21] C：字符类别判断
来源：http://dali.dashuyun.cn/Article/details/gt2ogisksua.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.cashguo.top/Article/details/gt2norbyweo.html

[S22] C：字符串转数字
来源：http://dali.jinqigufen.top/Article/details/gt2lmbxooye.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2jsmqleum.html

[S23] C：随机数
来源：http://dali.svipenyu.cn/Article/details/gt2mspskykh.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.daxiang520.top/Article/details/gt2bxpxbsnb.html

[S24] C：获取本地时间
来源：http://dali.yonumen.top/Article/details/gt2wehayjee.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.andypj.xyz/Article/details/gt2tvdyqrtb.html

[S25] C：内存拷贝
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sgemwspf.html

memcpy(dst, src, n);
来源：http://dali.yangfankeji.com/Article/details/gt2pmnclrfs.html

[S26] C：内存清零
来源：http://dali.hysaishi.cn/Article/details/gt2ppedgtmq.html

memset(a, 0, sizeof a);
来源：http://dali.chenjidiqi.icu/Article/details/gt2xovvktzr.html

[S27] C：定义常量
来源：http://dali.cdnleiting.top/Article/details/gt2sdyqhxuh.html

const double PI = 3.14159;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ririjcoy.html

[S28] C：静态变量
来源：http://dali.jianghu66.top/Article/details/gt2ovocyjlk.html

static int counter = 0;
来源：http://dali.zhixingplan.top/Article/details/gt2rnkdllql.html

[S29] C：变参函数
来源：http://dali.zhoulong.xyz/Article/details/gt2ccfyngbl.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.pengpengdd.cyou/Article/details/gt2xjeoxrbo.html

[S30] C：头文件保护
来源：http://dali.hysaishi.cn/Article/details/gt2zarbffqd.html

#ifndef X_H
来源：http://dali.xziqi.cn/Article/details/gt2qbncycby.html

#define X_H
来源：http://dali.yj202588.top/Article/details/gt2rpiungzu.html

#endif
来源：http://dali.aizwys.cn/Article/details/gt2qhdryije.html

[S31] C++：Hello World
来源：http://dali.chenzaomai.com/Article/details/gt2iffkvxqa.html

#include <iostream>
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lyiqdaxg.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.fzhhl.top/Article/details/gt2stunsgoi.html

[S32] C++：字符串
来源：http://dali.cucudq.cn/Article/details/gt2wygwbhqh.html

std::string s = "hi";  s += "!";
来源：http://dali.birdmap.top/Article/details/gt2hphrxahv.html

[S33] C++：vector 增删
来源：http://dali.yueranfly.top/Article/details/gt2fbedmpbo.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.c1oappe.top/Article/details/gt2rcuxnjnw.html

[S34] C++：遍历 vector
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2iwztmjps.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kzhodmyc.html

[S35] C++：map
来源：http://dali.wangshuangyany.cn/Article/details/gt2tcefgjep.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.daxiang520.top/Article/details/gt2pfemryvx.html

[S36] C++：unordered_map
来源：http://dali.gotoacloud.top/Article/details/gt2yjgqyaxt.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.meibo888.top/Article/details/gt2xzvcsmji.html

[S37] C++：set
来源：http://dali.yvedp.cn/Article/details/gt2uwrowpfi.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.fzhhl.top/Article/details/gt2rskhfqwl.html

[S38] C++：排序
来源：http://dali.shzxlz.cn/Article/details/gt2bubpojxw.html

std::sort(v.begin(), v.end());
来源：http://dali.daxiang520.top/Article/details/gt2qxjeeimo.html

[S39] C++：自定义比较器排序
来源：http://dali.nanxinkj.top/Article/details/gt2ovzvcefx.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.bjfxy.top/Article/details/gt2takqpkdg.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2oyfyrdkg.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.c1oappe.top/Article/details/gt2cgttdfcw.html

[S41] C++：类与构造函数
来源：http://dali.pengpengdd.cyou/Article/details/gt2cnyhzonf.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.xuanzx.com/Article/details/gt2ooxdeinf.html

[S42] C++：继承与虚函数
来源：http://dali.nanxuanxn.top/Article/details/gt2ihtqxfkb.html

class B : public Base { public: void f() override {} };
来源：http://dali.pycfn.com/Article/details/gt2eglldnph.html

[S43] C++：智能指针
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ujkbjtcw.html

auto p = std::make_unique<int>(5);
来源：http://dali.smart0.xyz/Article/details/gt2bodzfbug.html

[S44] C++：引用传参
来源：http://dali.xuanzx.com/Article/details/gt2ghxedbqi.html

void inc(int &x) { ++x; }
来源：http://dali.vqdsnc.cn/Article/details/gt2qhsrsqri.html

[S45] C++：lambda
来源：http://dali.gotoacloud.top/Article/details/gt2ozhniaos.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhixingplan.top/Article/details/gt2sorfwlau.html

[S46] C++：函数模板
来源：http://dali.zycfv.cn/Article/details/gt2bqdzmaba.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.aizwys.cn/Article/details/gt2pktaqtke.html

[S47] C++：结构化绑定遍历
来源：http://dali.quarkkingdee.top/Article/details/gt2vwrhbypg.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.cqqwz.cn/Article/details/gt2ulvsksho.html

[S48] C++：逐行读文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kpugycsx.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.sxryk.cn/Article/details/gt2tllpqgqi.html

while (std::getline(in, line)) { }
来源：http://dali.hywenlv.cn/Article/details/gt2hqjxemrs.html

[S49] C++：写文件
来源：http://dali.xuetiantiany.cn/Article/details/gt2pldlfuwz.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.yuanzhike.top/Article/details/gt2tmfgfktl.html

[S50] C++：格式化数字
来源：http://dali.smart0.xyz/Article/details/gt2lsurcfim.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.cdnleiting.top/Article/details/gt2ekrvkadj.html

[S51] C++：显式类型转换
来源：http://dali.hfpthk.cn/Article/details/gt2ksvdqfki.html

static_cast<double>(a) / b
来源：http://dali.pycfn.com/Article/details/gt2eefixiqp.html

[S52] C++：const 与 noexcept
来源：http://dali.ivvv.top/Article/details/gt2pxkjzgca.html

int size() const noexcept { return n_; }
来源：http://dali.sweek.top/Article/details/gt2lxqbzmyk.html

[S53] C++：移动语义
来源：http://dali.xuanzx.com/Article/details/gt2okwuwoju.html

std::vector<int> w = std::move(v);
来源：http://dali.cdnleiting.top/Article/details/gt2mipzwrba.html

[S54] C++：异常处理
来源：http://dali.ppjwa.cn/Article/details/gt2ljilzyfl.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.yj20258888.top/Article/details/gt2juhbtsdm.html

[S55] C++：结构化绑定
来源：http://dali.aibaodan.cn/Article/details/gt2xwwfkjpt.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.xylfe.cn/Article/details/gt2vbfsyfxg.html

[S56] C++：optional
来源：http://dali.jqgfzy.top/Article/details/gt2cgyzimiw.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yuxming.cn/Article/details/gt2qoihsnxo.html

[S57] C++：编译期常量
来源：http://dali.chenzaomai.com/Article/details/gt2lejagohz.html

constexpr int N = 10;
来源：http://dali.chenjidiqi.icu/Article/details/gt2wruwwrkb.html

[S58] C++：命名空间
来源：http://dali.xylfe.cn/Article/details/gt2jlypfnpn.html

namespace ns { int f() { return 1; } }
来源：http://dali.nanxuanxn.top/Article/details/gt2ylttkhyp.html

[S59] C++：静态断言
来源：http://dali.sxryk.cn/Article/details/gt2htejinao.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.nwbrower.top/Article/details/gt2pvkeeflg.html

[S60] C++：遍历并删除元素
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ghrumvfe.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.xylfe.cn/Article/details/gt2chsjuylm.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2kljrbkzo.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ydclrong.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2bobqswom.html

[T01] Kotlin：Hello World
来源：http://dali.yuxming.cn/Article/details/gt2doqlbpmt.html

println("Hello")
来源：http://dali.jyoumei.cn/Article/details/gt2facmenhi.html

[T02] Kotlin：变量
来源：http://dali.yuxming.cn/Article/details/gt2nkpdjsxx.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.andypj.xyz/Article/details/gt2bswcxnwa.html

[T03] Kotlin：字符串模板
来源：http://dali.jyoumei.cn/Article/details/gt2uzpjmvtg.html

"值: $b"
来源：http://dali.nanxinkj.top/Article/details/gt2jqjklrqi.html

[T04] Kotlin：空安全
来源：http://dali.nanxinkj.top/Article/details/gt2tsrdxzqd.html

val n: String? = null;  n?.length
来源：http://dali.yongpay.top/Article/details/gt2ihwhvyse.html

[T05] Kotlin：when 表达式
来源：http://dali.nwbrower.top/Article/details/gt2icfpfrez.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.xylfe.cn/Article/details/gt2ildwtzli.html

[T06] Kotlin：集合映射
来源：http://dali.yj202588.top/Article/details/gt2gbpsmmnf.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.nwbrower.top/Article/details/gt2vlzwfumo.html

[T07] Kotlin：集合过滤
来源：http://dali.gogol.net.cn/Article/details/gt2mxhsucdk.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.sufxvd.cn/Article/details/gt2pakhebdv.html

[T08] Kotlin：数据类
来源：http://dali.guannengcc.top/Article/details/gt2ijokfdqr.html

data class User(val name: String, val age: Int)
来源：http://dali.zhongyouzk.top/Article/details/gt2wjuxfpkv.html

[T09] Kotlin：扩展函数
来源：http://dali.gotoacloud.top/Article/details/gt2nfejmvvo.html

fun String.exclaim() = this + "!"
来源：http://dali.cashguo.top/Article/details/gt2qqvhetfs.html

[T10] Kotlin：默认参数
来源：http://dali.xylfe.cn/Article/details/gt2aabwizqi.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.snrcjt.cn/Article/details/gt2oxwrqutz.html

[T11] Kotlin：协程
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rfzchxva.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.sysykeji.top/Article/details/gt2egpbsixm.html

[T12] Kotlin：解构声明
来源：http://dali.feifeiyinyue.top/Article/details/gt2fezfoxiw.html

val (a, b) = Pair(1, 2)
来源：http://dali.zdqjudy.top/Article/details/gt2ihyicwxx.html

[T13] Kotlin：只读 Map
来源：http://dali.jianghu66.top/Article/details/gt2urcjxgum.html

val m = mapOf("a" to 1)
来源：http://dali.jiagoushi.top/Article/details/gt2kukdntda.html

[T14] Kotlin：循环
来源：http://dali.jianghu66.top/Article/details/gt2dkouwwvc.html

for (i in 1..10) println(i)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zilbcwfd.html

[T15] Kotlin：接口
来源：http://dali.xinyue.icu/Article/details/gt2nanyuzgs.html

interface Shape { fun area(): Double }
来源：http://dali.yvedp.cn/Article/details/gt2smcxcdwj.html

[T16] Swift：Hello World
来源：http://dali.yangfankeji.com/Article/details/gt2yvqreqax.html

print("Hello")
来源：http://dali.jianghu66.top/Article/details/gt2eekygdpb.html

[T17] Swift：变量与常量
来源：http://dali.hysaishi.cn/Article/details/gt2jguclkfp.html

var a = 1;  let b = 2
来源：http://dali.zhengqikj.top/Article/details/gt2xgnpcumk.html

[T18] Swift：字符串插值
来源：http://dali.jqgfzy.top/Article/details/gt2evrmduls.html

"值: \(b)"
来源：http://dali.ydzc1.top/Article/details/gt2uzrjgesb.html

[T19] Swift：可选绑定
来源：http://dali.cqqwz.cn/Article/details/gt2qacrzope.html

if let n = opt { print(n) }
来源：http://dali.yanxiufei.cn/Article/details/gt2dykwiyws.html

[T20] Swift：数组操作
来源：http://dali.shuidangran.top/Article/details/gt2btiifrdt.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.yonumen.top/Article/details/gt2xozfcyla.html

[T21] Swift：遍历
来源：http://dali.bjfxy.top/Article/details/gt2pdwssqwt.html

for x in a { print(x) }
来源：http://dali.dianchejie.cn/Article/details/gt2oapqbzrm.html

[T22] Swift：字典
来源：http://dali.nanxuanxn.top/Article/details/gt2hwxqaeff.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.shuidangran.top/Article/details/gt2tzzznepa.html

[T23] Swift：函数
来源：http://dali.andypj.xyz/Article/details/gt2zjsynywh.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.guannengcc.top/Article/details/gt2mornchdq.html

[T24] Swift：闭包
来源：http://dali.yj202588.top/Article/details/gt2hdxoxlhg.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.jianghu66.top/Article/details/gt2oymbtkvb.html

[T25] Swift：结构体
来源：http://dali.yj202588.top/Article/details/gt2wurestmr.html

struct P { var x: Int }
来源：http://dali.xziqi.cn/Article/details/gt2uxwmklxc.html

[T26] Swift：类与重写
来源：http://dali.tianlin.xyz/Article/details/gt2ezgqxlpr.html

class A: Base { override func f() {} }
来源：http://dali.yueranfly.top/Article/details/gt2qezswnss.html

[T27] Swift：错误处理
来源：http://dali.0kj1m.cn/Article/details/gt2omxfqmag.html

do { try f() } catch { print(error) }
来源：http://dali.xinyue.icu/Article/details/gt2jlaqcjpk.html

[T28] Swift：枚举
来源：http://dali.meibo888.top/Article/details/gt2clbkrnmz.html

enum Color { case red, green }
来源：http://dali.zycfv.cn/Article/details/gt2kpuopaha.html

[T29] Swift：guard 提前返回
来源：http://dali.yueranfly.top/Article/details/gt2vhburbgt.html

guard let x = opt else { return }
来源：http://dali.daxiang520.top/Article/details/gt2vepbzaej.html

[T30] Swift：协议
来源：http://dali.gzhubu.top/Article/details/gt2oxoxzcpy.html

protocol Shape { func area() -> Double }
来源：http://dali.shzxlz.cn/Article/details/gt2gidpkpuo.html

[T31] Lua：Hello World
来源：http://dali.zhixingplan.top/Article/details/gt2luurjwcx.html

print("Hello")
来源：http://dali.pengpengdd.cyou/Article/details/gt2kwqdrzim.html

[T32] Lua：局部变量
来源：http://dali.cdnleiting.top/Article/details/gt2lvnoaaza.html

local a = 1
来源：http://dali.yuanzhike.top/Article/details/gt2lqnuqejs.html

[T33] Lua：表（数组）
来源：http://dali.vqdsnc.cn/Article/details/gt2cssuzcvn.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.guowangkeji.top/Article/details/gt2ayjnocus.html

[T34] Lua：遍历表
来源：http://dali.zdqjudy.top/Article/details/gt2syfvrpjo.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.jianghu66.top/Article/details/gt2vkcfhanj.html

[T35] Lua：字典表
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ysktonfk.html

local d = { a = 1 };  d.b = 2
来源：http://dali.tianlin.xyz/Article/details/gt2otcmccma.html

[T36] Lua：函数
来源：http://dali.zhoulong.xyz/Article/details/gt2ekgyqbni.html

function add(a, b) return a + b end
来源：http://dali.havefunace.top/Article/details/gt2cfenpsat.html

[T37] Lua：字符串拼接
来源：http://dali.yj20258888.top/Article/details/gt2lfcegtlb.html

"a" .. "b"
来源：http://dali.xziqi.cn/Article/details/gt2xwuxjohe.html

[T38] Lua：条件
来源：http://dali.sufxvd.cn/Article/details/gt2cmduoqpr.html

if x > 0 then print("正") end
来源：http://dali.iojbl.cn/Article/details/gt2sbvzysss.html

[T39] Lua：模式匹配
来源：http://dali.ivvv.top/Article/details/gt2ahnggajf.html

string.find(s, "%d+")
来源：http://dali.nwbrower.top/Article/details/gt2rqsmgjkr.html

[T40] Lua：元表
来源：http://dali.316326.xyz/Article/details/gt2wezcrdvd.html

setmetatable({}, { __index = base })
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gmfqptya.html

[T41] Perl：Hello World
来源：http://dali.xuetiantiany.cn/Article/details/gt2kjadxkrp.html

print "Hello\n";
来源：http://dali.vqdsnc.cn/Article/details/gt2qshyxhcl.html

[T42] Perl：变量类型
来源：http://dali.tanke756.top/Article/details/gt2jfdpsapq.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.yuxming.cn/Article/details/gt2okqinouq.html

[T43] Perl：字符串插值
来源：http://dali.yanxiufei.cn/Article/details/gt2lvrrmssu.html

"值: $a"
来源：http://dali.zhongyouzk.top/Article/details/gt2xolbqseh.html

[T44] Perl：条件
来源：http://dali.yonumen.top/Article/details/gt2yyyoqqpk.html

if ($a > 0) { print "正"; }
来源：http://dali.ybcxt.top/Article/details/gt2caxlwobj.html

[T45] Perl：数组遍历
来源：http://dali.tian-w.cn/Article/details/gt2jbpyddxh.html

for my $x (@arr) { print $x; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2nxrhnnuj.html

[T46] Perl：哈希操作
来源：http://dali.gaohongyu789.top/Article/details/gt2ezgrnawk.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.kuanghao11.cn/Article/details/gt2yychiqpk.html

[T47] Perl：正则捕获
来源：http://dali.wangshuangyany.cn/Article/details/gt2sotgtoyq.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhongyouzk.top/Article/details/gt2bpwlvtyj.html

[T48] Perl：正则替换
来源：http://dali.jlsjyb.cn/Article/details/gt2btnfxulr.html

$s =~ s/old/new/g;
来源：http://dali.gzhubu.top/Article/details/gt2cvyfysew.html


<!-- 参考信息 -->