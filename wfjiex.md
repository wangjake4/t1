代发 wailian999

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.hnxiangtu.top/Article/details/gt2zdpjiapi.html

[R50] awk 求和
来源：http://dali.yueranfly.top/Article/details/gt2rezlmukp.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.gaohongyu789.top/Article/details/gt2qndslnai.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2ayzdddvc.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.yvedp.cn/Article/details/gt2ajrawriq.html

[R52] 统计行数
来源：http://dali.xziqi.cn/Article/details/gt2oubghins.html

wc -l a.txt
来源：http://dali.jianghu66.top/Article/details/gt2gcobvomc.html

[R53] 查看文件头与实时尾
来源：http://dali.jqgufenzy.top/Article/details/gt2sibxmqdp.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.yuanzhike.top/Article/details/gt2gkuchrdq.html

[R54] 比较两个文件
来源：http://dali.snrcjt.cn/Article/details/gt2ayqtnpxa.html

diff a.txt b.txt
来源：http://dali.sysykeji.top/Article/details/gt2jxytnxef.html

[R55] 压缩与解压
来源：http://dali.quarkkingdee.top/Article/details/gt2taksaiof.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.guowangkeji.top/Article/details/gt2xqywaoni.html

[R56] 远程拷贝
来源：http://dali.havefunace.top/Article/details/gt2rkbrkrhr.html

scp file user@host:/path/
来源：http://dali.yangfankeji.com/Article/details/gt2ghjyuxfr.html

[R57] 远程执行命令
来源：http://dali.9152youxi.cn/Article/details/gt2uxhqcyqx.html

ssh user@host 'uptime'
来源：http://dali.yanxiufei.cn/Article/details/gt2dxxolwbp.html

[R58] 下载文件
来源：http://dali.c1oappe.top/Article/details/gt2ibywjgst.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.meibo888.top/Article/details/gt2ddlszrut.html

[R59] 发 POST JSON
来源：http://dali.aizwys.cn/Article/details/gt2zhznbhyn.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.yj202588.top/Article/details/gt2lsshxyvi.html

[R60] 只看 HTTP 状态码
来源：http://dali.sxryk.cn/Article/details/gt2nhsqndvl.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.birdmap.top/Article/details/gt2ctjocakk.html

[R61] 磁盘占用
来源：http://dali.yongpay.top/Article/details/gt2vtpciehr.html

df -h;  du -sh *
来源：http://dali.aizwys.cn/Article/details/gt2kdvgybdy.html

[R62] 找最占空间的文件
来源：http://dali.tianlin.xyz/Article/details/gt2kssbjomu.html

du -ah . | sort -rh | head -10
来源：http://dali.ehwqpu.com/Article/details/gt2pznofllv.html

[R63] 内存与进程
来源：http://dali.aibaodan.cn/Article/details/gt2ahwkhdpl.html

free -h;  ps aux | grep nginx
来源：http://dali.shzxlz.cn/Article/details/gt2iairznnu.html

[R64] 结束进程
来源：http://dali.9152youxi.cn/Article/details/gt2hvlmfkvd.html

kill -9 $(pgrep -f app.py)
来源：http://dali.cucudq.cn/Article/details/gt2vipubbsv.html

[R65] 查看端口占用
来源：http://dali.wangshuangyany.cn/Article/details/gt2ftivvseb.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ykhikwes.html

[R66] 定时任务
来源：http://dali.yanxiufei.cn/Article/details/gt2qgzxomsp.html

crontab -e;  crontab -l
来源：http://dali.yuxming.cn/Article/details/gt2xlwszoyw.html

[R67] 生成随机十六进制串
来源：http://dali.sufxvd.cn/Article/details/gt2avivrdzr.html

openssl rand -hex 16
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uuwntosy.html

[R68] 计算文件校验值
来源：http://dali.chenzaomai.com/Article/details/gt2xucpsquo.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.fengsongda.top/Article/details/gt2bbcojvnn.html

[R69] 生成随机密码
来源：http://dali.jinqigufen.top/Article/details/gt2htzspifo.html

head -c 16 /dev/urandom | base64
来源：http://dali.hysaishi.cn/Article/details/gt2lztvbjrp.html

[R70] 时间戳与互转
来源：http://dali.chenzaomai.com/Article/details/gt2zmbsvloc.html

date +%s;  date -d @1700000000
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uxngmiiz.html

[R71] 日期格式化
来源：http://dali.nanxinkj.top/Article/details/gt2ijiawemd.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.9152youxi.cn/Article/details/gt2fmtmccvd.html

[R72] 等待端口就绪
来源：http://dali.sufxvd.cn/Article/details/gt2umltciij.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.gotoacloud.top/Article/details/gt2mjhhqndd.html

[R73] 分割大日志
来源：http://dali.jqgfzy.top/Article/details/gt2htzpgzzo.html

split -l 1000 big.log part_
来源：http://dali.wangdashe.top/Article/details/gt2wvzvcqyo.html

[R74] 批量重命名
来源：http://dali.zhongyouzk.top/Article/details/gt2jfijtfcq.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.dianchejie.cn/Article/details/gt2bdfpokbo.html

[R75] 导出环境变量
来源：http://dali.yanxiufei.cn/Article/details/gt2oxweklrp.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.yongpay.top/Article/details/gt2wyovooyx.html

[R76] 使用临时文件
来源：http://dali.bjfxy.top/Article/details/gt2jzlcfxwj.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.gzhubu.top/Article/details/gt2jokoyoaw.html

[R77] 读取用户输入
来源：http://dali.aibaodan.cn/Article/details/gt2yxtuczdm.html

read -rp "请输入: " ans
来源：http://dali.andypj.xyz/Article/details/gt2abcoizqk.html

[R78] 交互式菜单
来源：http://dali.sufxvd.cn/Article/details/gt2fnhzgmvo.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.yuanzhike.top/Article/details/gt2rqwnvqnm.html

[R79] 解析命令行选项
来源：http://dali.nanxinkj.top/Article/details/gt2gxncsqsd.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.daria6918.cn/Article/details/gt2owglibns.html

[R80] 查看脚本执行耗时
来源：http://dali.kuanghao11.cn/Article/details/gt2ptckxuil.html

time ./run.sh
来源：http://dali.yueranfly.top/Article/details/gt2igapjjgf.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2rauojsxo.html

S. C / C++ 专题
来源：http://dali.hammf.cn/Article/details/gt2kcbxrmnx.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tbpaefrb.html

[S01] C：Hello World
来源：http://dali.yuanzhike.top/Article/details/gt2voobiaqu.html

#include <stdio.h>
来源：http://dali.tian-w.cn/Article/details/gt2cvyagyhe.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.9152youxi.cn/Article/details/gt2oncclgnf.html

[S02] C：变量与格式化输出
来源：http://dali.sweek.top/Article/details/gt2jdinldzi.html

int a = 10; printf("%d\n", a);
来源：http://dali.cucudq.cn/Article/details/gt2krncxzjp.html

[S03] C：读入整数
来源：http://dali.sysykeji.top/Article/details/gt2cdbffqps.html

int x; scanf("%d", &x);
来源：http://dali.ybcxt.top/Article/details/gt2jsmqfbif.html

[S04] C：字符串复制
来源：http://dali.shzxlz.cn/Article/details/gt2gwphrikl.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.cqqwz.cn/Article/details/gt2nrsswwet.html

[S05] C：字符串长度
来源：http://dali.zhoulong.xyz/Article/details/gt2xjkvbzzx.html

strlen(s)
来源：http://dali.ppjwa.cn/Article/details/gt2grydhghq.html

[S06] C：字符串比较
来源：http://dali.yongpay.top/Article/details/gt2ccoifchn.html

strcmp(a, b) == 0
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gfnqnlxm.html

[S07] C：数组遍历求和
来源：http://dali.shangyingyoupin.top/Article/details/gt2sykayjpt.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.sweek.top/Article/details/gt2wlidhsef.html

[S08] C：动态内存分配与释放
来源：http://dali.jqgufenzy.top/Article/details/gt2uozgjvjt.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.xuetiantiany.cn/Article/details/gt2hkcyoivy.html

[S09] C：结构体定义与初始化
来源：http://dali.hongshengwenyu.top/Article/details/gt2kupqpoxk.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.dianchejie.cn/Article/details/gt2hphzfnmn.html

[S10] C：指针与解引用
来源：http://dali.fzhhl.top/Article/details/gt2obqimjsa.html

int *p = &a;  *p = 5;
来源：http://dali.andypj.xyz/Article/details/gt2ibhgjthu.html

[S11] C：逐行读文件
来源：http://dali.dianchejie.cn/Article/details/gt2vmoxrguh.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.ppjwa.cn/Article/details/gt2zakudwgp.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.hnqzz.top/Article/details/gt2uazlwzxt.html

fclose(f);
来源：http://dali.zhixingplan.top/Article/details/gt2kdvarpaq.html

[S12] C：写文件
来源：http://dali.zhongyouzk.top/Article/details/gt2gqaxckck.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.iojbl.cn/Article/details/gt2sfslkxfu.html

[S13] C：宏定义
来源：http://dali.chenzaomai.com/Article/details/gt2bboqbhho.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.bjfxy.top/Article/details/gt2nnjphvoo.html

[S14] C：枚举
来源：http://dali.kuanghao11.cn/Article/details/gt2bkjllhdl.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.316326.xyz/Article/details/gt2njqnnobi.html

[S15] C：类型转换
来源：http://dali.zhiwuduotai.top/Article/details/gt2vwhckxfh.html

(double) a / b
来源：http://dali.svipenyu.cn/Article/details/gt2llxldfdh.html

[S16] C：位操作置位
来源：http://dali.yonumen.top/Article/details/gt2kyycmkcx.html

x |= (1 << 3);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bnhfunjk.html

[S17] C：安全拼接字符串
来源：http://dali.zhengqikj.top/Article/details/gt2rggxjana.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.ivvv.top/Article/details/gt2bfxwsioc.html

[S18] C：命令行参数
来源：http://dali.zhoulong.xyz/Article/details/gt2mmtwclra.html

int main(int argc, char **argv)
来源：http://dali.hfpthk.cn/Article/details/gt2xuexjdds.html

[S19] C：快速排序
来源：http://dali.jiagoushi.top/Article/details/gt2oshmfyfg.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.shzxlz.cn/Article/details/gt2eigtcrsa.html

[S20] C：二分查找
来源：http://dali.tian-w.cn/Article/details/gt2mplrbapz.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.tianlin.xyz/Article/details/gt2uiroxaoq.html

[S21] C：字符类别判断
来源：http://dali.jlsjyb.cn/Article/details/gt2bgjphbde.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.shzxlz.cn/Article/details/gt2erucxhsz.html

[S22] C：字符串转数字
来源：http://dali.xziqi.cn/Article/details/gt2ofqpydub.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.vqdsnc.cn/Article/details/gt2phkmyjea.html

[S23] C：随机数
来源：http://dali.shangyingyoupin.top/Article/details/gt2qhjzehsx.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.yongpay.top/Article/details/gt2rzyqdwtc.html

[S24] C：获取本地时间
来源：http://dali.hywenlv.cn/Article/details/gt2wisqgumr.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.aibaodan.cn/Article/details/gt2vbooicpt.html

[S25] C：内存拷贝
来源：http://dali.andypj.xyz/Article/details/gt2kpbcjqub.html

memcpy(dst, src, n);
来源：http://dali.yuxming.cn/Article/details/gt2iowfybap.html

[S26] C：内存清零
来源：http://dali.sysykeji.top/Article/details/gt2ujnupudy.html

memset(a, 0, sizeof a);
来源：http://dali.zhengqikj.top/Article/details/gt2mgdnftsh.html

[S27] C：定义常量
来源：http://dali.redwolf501.top/Article/details/gt2slowwhrl.html

const double PI = 3.14159;
来源：http://dali.ppjwa.cn/Article/details/gt2qxalpkpr.html

[S28] C：静态变量
来源：http://dali.wangdashe.top/Article/details/gt2yhjaxnzy.html

static int counter = 0;
来源：http://dali.wangshuangyany.cn/Article/details/gt2tzqmzaiu.html

[S29] C：变参函数
来源：http://dali.sysykeji.top/Article/details/gt2sjumuhqj.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhixingplan.top/Article/details/gt2ccbiayba.html

[S30] C：头文件保护
来源：http://dali.yj20258.top/Article/details/gt2lgqvhpcw.html

#ifndef X_H
来源：http://dali.jinqigfzy.top/Article/details/gt2tefzyxjo.html

#define X_H
来源：http://dali.yonumen.top/Article/details/gt2qjvzlxbj.html

#endif
来源：http://dali.bjfxy.top/Article/details/gt2xxpdiegf.html

[S31] C++：Hello World
来源：http://dali.hfpthk.cn/Article/details/gt2idfygvpk.html

#include <iostream>
来源：http://dali.aizwys.cn/Article/details/gt2bhaycsfh.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jbrguooh.html

[S32] C++：字符串
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tkizqspt.html

std::string s = "hi";  s += "!";
来源：http://dali.fzhhl.top/Article/details/gt2drwkgvwn.html

[S33] C++：vector 增删
来源：http://dali.cheryme.top/Article/details/gt2vbwaucxz.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.quarkkingdee.top/Article/details/gt2ujnfmboc.html

[S34] C++：遍历 vector
来源：http://dali.snrcjt.cn/Article/details/gt2pfxjdftw.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.sufxvd.cn/Article/details/gt2jclxppnr.html

[S35] C++：map
来源：http://dali.sysykeji.top/Article/details/gt2xfjktxra.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yj20258888.top/Article/details/gt2khvjxuan.html

[S36] C++：unordered_map
来源：http://dali.hywenlv.cn/Article/details/gt2icfrzdab.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.xziqi.cn/Article/details/gt2elujcosd.html

[S37] C++：set
来源：http://dali.zhoulong.xyz/Article/details/gt2jxlzfrcv.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.gotoacloud.top/Article/details/gt2mopvgsvc.html

[S38] C++：排序
来源：http://dali.jqgfzy.top/Article/details/gt2ovpxenvd.html

std::sort(v.begin(), v.end());
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2urjnqaul.html

[S39] C++：自定义比较器排序
来源：http://dali.gzhubu.top/Article/details/gt2habuzdhg.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.cucudq.cn/Article/details/gt2rjbihsrk.html

[S40] C++：查找元素
来源：http://dali.cashguo.top/Article/details/gt2hnuhrxiy.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.jiagoushi.top/Article/details/gt2wgcecaqr.html

[S41] C++：类与构造函数
来源：http://dali.ydzc1.top/Article/details/gt2lbfnbslz.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.xinyue.icu/Article/details/gt2zmxnlxzk.html

[S42] C++：继承与虚函数
来源：http://dali.mhx1999.top/Article/details/gt2kjwaivjj.html

class B : public Base { public: void f() override {} };
来源：http://dali.gaohongyu789.top/Article/details/gt2cmdxenjh.html

[S43] C++：智能指针
来源：http://dali.zycfv.cn/Article/details/gt2qqpyzyfc.html

auto p = std::make_unique<int>(5);
来源：http://dali.svipenyu.cn/Article/details/gt2zznzdhpn.html

[S44] C++：引用传参
来源：http://dali.nanxuanxn.top/Article/details/gt2ucfaodbc.html

void inc(int &x) { ++x; }
来源：http://dali.hfpthk.cn/Article/details/gt2cvatwdkp.html

[S45] C++：lambda
来源：http://dali.hnxiangtu.top/Article/details/gt2oywkpdoj.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.shuidangran.top/Article/details/gt2sntzjvsz.html

[S46] C++：函数模板
来源：http://dali.xinyue.icu/Article/details/gt2oqyntipe.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.quarkkingdee.top/Article/details/gt2ztwtussy.html

[S47] C++：结构化绑定遍历
来源：http://dali.zdqjudy.top/Article/details/gt2zrnuuvpk.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.gaohongyu789.top/Article/details/gt2dgwklhcx.html

[S48] C++：逐行读文件
来源：http://dali.ivvv.top/Article/details/gt2zxyqglvj.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.ydzc1.top/Article/details/gt2jdbmxhja.html

while (std::getline(in, line)) { }
来源：http://dali.jiagoushi.top/Article/details/gt2xuftskog.html

[S49] C++：写文件
来源：http://dali.chenzaomai.com/Article/details/gt2obspgpfe.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.cucudq.cn/Article/details/gt2plkdhhhs.html

[S50] C++：格式化数字
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2iepxcrpg.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.chenjidiqi.icu/Article/details/gt2ptnzweqx.html

[S51] C++：显式类型转换
来源：http://dali.xinyue.icu/Article/details/gt2cagvokiz.html

static_cast<double>(a) / b
来源：http://dali.cashguo.top/Article/details/gt2imurodqz.html

[S52] C++：const 与 noexcept
来源：http://dali.aibaodan.cn/Article/details/gt2zsyxtvsf.html

int size() const noexcept { return n_; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2yozrfyst.html

[S53] C++：移动语义
来源：http://dali.fengsongda.top/Article/details/gt2jsnmsqpe.html

std::vector<int> w = std::move(v);
来源：http://dali.aibaodan.cn/Article/details/gt2wavgwxah.html

[S54] C++：异常处理
来源：http://dali.zhixingplan.top/Article/details/gt2ordupdxf.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.shzxlz.cn/Article/details/gt2yjxontvv.html

[S55] C++：结构化绑定
来源：http://dali.ppjwa.cn/Article/details/gt2abexvsqz.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pgzybgkp.html

[S56] C++：optional
来源：http://dali.cucudq.cn/Article/details/gt2ihrjyzso.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cybpeeez.html

[S57] C++：编译期常量
来源：http://dali.hnqzz.top/Article/details/gt2omnofunj.html

constexpr int N = 10;
来源：http://dali.andypj.xyz/Article/details/gt2dnbdqsru.html

[S58] C++：命名空间
来源：http://dali.yuxming.cn/Article/details/gt2enilbigq.html

namespace ns { int f() { return 1; } }
来源：http://dali.hammf.cn/Article/details/gt2adrhofvg.html

[S59] C++：静态断言
来源：http://dali.ivvv.top/Article/details/gt2xxurbwdy.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.9152youxi.cn/Article/details/gt2maczaqjs.html

[S60] C++：遍历并删除元素
来源：http://dali.9152youxi.cn/Article/details/gt2awuqguzy.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.gaohongyu789.top/Article/details/gt2idgglucv.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2fbvpblvc.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.xinyue.icu/Article/details/gt2oioyqlwu.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gt2qpbfjypy.html

[T01] Kotlin：Hello World
来源：http://dali.daxiang520.top/Article/details/gt2qontifrz.html

println("Hello")
来源：http://dali.hywenlv.cn/Article/details/gt2ufnxwlaa.html

[T02] Kotlin：变量
来源：http://dali.redwolf501.top/Article/details/gt2fjqakhmn.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zdqjudy.top/Article/details/gt2extzonck.html

[T03] Kotlin：字符串模板
来源：http://dali.ybcxt.top/Article/details/gt2xhelwehr.html

"值: $b"
来源：http://dali.ehwqpu.com/Article/details/gt2qrjxyrkz.html

[T04] Kotlin：空安全
来源：http://dali.jqgfzy.top/Article/details/gt2abmtsfvq.html

val n: String? = null;  n?.length
来源：http://dali.yj20258888.top/Article/details/gt2selsobrs.html

[T05] Kotlin：when 表达式
来源：http://dali.ppjwa.cn/Article/details/gt2wmfflvfq.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.cqqwz.cn/Article/details/gt2ikaixxuu.html

[T06] Kotlin：集合映射
来源：http://dali.shuidangran.top/Article/details/gt2jtgoyefb.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.xuanzx.com/Article/details/gt2sdvhvfvg.html

[T07] Kotlin：集合过滤
来源：http://dali.cucudq.cn/Article/details/gt2mrmzdfln.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.dianchejie.cn/Article/details/gt2plgrvhyj.html

[T08] Kotlin：数据类
来源：http://dali.jqgfzy.top/Article/details/gt2taggyoav.html

data class User(val name: String, val age: Int)
来源：http://dali.pengpengdd.cyou/Article/details/gt2fgirexin.html

[T09] Kotlin：扩展函数
来源：http://dali.iojbl.cn/Article/details/gt2sspxclou.html

fun String.exclaim() = this + "!"
来源：http://dali.yvedp.cn/Article/details/gt2rltufzge.html

[T10] Kotlin：默认参数
来源：http://dali.vqdsnc.cn/Article/details/gt2ysnilwyu.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.cdnleiting.top/Article/details/gt2veeyomzi.html

[T11] Kotlin：协程
来源：http://dali.jqgufenzy.top/Article/details/gt2apwrhpgh.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.ydzc1.top/Article/details/gt2mcshwzba.html

[T12] Kotlin：解构声明
来源：http://dali.bjfxy.top/Article/details/gt2jglfprix.html

val (a, b) = Pair(1, 2)
来源：http://dali.zdqjudy.top/Article/details/gt2ubvqijgl.html

[T13] Kotlin：只读 Map
来源：http://dali.tianlin.xyz/Article/details/gt2kazmbkxc.html

val m = mapOf("a" to 1)
来源：http://dali.jinqigfzy.top/Article/details/gt2yyynsxbb.html

[T14] Kotlin：循环
来源：http://dali.c1oappe.top/Article/details/gt2ahfourjn.html

for (i in 1..10) println(i)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fkpdqtkx.html

[T15] Kotlin：接口
来源：http://dali.gotoacloud.top/Article/details/gt2kozwlbmp.html

interface Shape { fun area(): Double }
来源：http://dali.jqgufenzy.top/Article/details/gt2sgqvwnsn.html

[T16] Swift：Hello World
来源：http://dali.yongpay.top/Article/details/gt2mqkhjhsv.html

print("Hello")
来源：http://dali.ppjwa.cn/Article/details/gt2dxwkavwc.html

[T17] Swift：变量与常量
来源：http://dali.hfpthk.cn/Article/details/gt2jyfrmtpw.html

var a = 1;  let b = 2
来源：http://dali.tanke756.top/Article/details/gt2gwuzsbao.html

[T18] Swift：字符串插值
来源：http://dali.hongshengwenyu.top/Article/details/gt2diubtckc.html

"值: \(b)"
来源：http://dali.daxiang520.top/Article/details/gt2prrhgwig.html

[T19] Swift：可选绑定
来源：http://dali.chenjidiqi.icu/Article/details/gt2evxppssf.html

if let n = opt { print(n) }
来源：http://dali.xuetiantiany.cn/Article/details/gt2aijkgjag.html

[T20] Swift：数组操作
来源：http://dali.chenzaomai.com/Article/details/gt2zmlvowji.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.haohaochexian.top/Article/details/gt2hayahcui.html

[T21] Swift：遍历
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zwefkdot.html

for x in a { print(x) }
来源：http://dali.chenjidiqi.icu/Article/details/gt2ucevduoz.html

[T22] Swift：字典
来源：http://dali.iojbl.cn/Article/details/gt2ootuxnlr.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.xziqi.cn/Article/details/gt2mpxzyjhi.html

[T23] Swift：函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rsowjuwl.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.yvedp.cn/Article/details/gt2ufcuweaa.html

[T24] Swift：闭包
来源：http://dali.yanxiufei.cn/Article/details/gt2biypmxly.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.jlsjyb.cn/Article/details/gt2qxzapute.html

[T25] Swift：结构体
来源：http://dali.iojbl.cn/Article/details/gt2enkjehfs.html

struct P { var x: Int }
来源：http://dali.cqqwz.cn/Article/details/gt2qigqsdfa.html

[T26] Swift：类与重写
来源：http://dali.bjfxy.top/Article/details/gt2wmaiucnx.html

class A: Base { override func f() {} }
来源：http://dali.jianghu66.top/Article/details/gt2wwjrfinm.html

[T27] Swift：错误处理
来源：http://dali.hammf.cn/Article/details/gt2towcoztj.html

do { try f() } catch { print(error) }
来源：http://dali.tanke756.top/Article/details/gt2yyejvrpm.html

[T28] Swift：枚举
来源：http://dali.gogol.net.cn/Article/details/gt2rrmtlivv.html

enum Color { case red, green }
来源：http://dali.svipenyu.cn/Article/details/gt2brjnmesx.html

[T29] Swift：guard 提前返回
来源：http://dali.cucudq.cn/Article/details/gt2bsonwqro.html

guard let x = opt else { return }
来源：http://dali.ppjwa.cn/Article/details/gt2krezmhhj.html

[T30] Swift：协议
来源：http://dali.feifeiyinyue.top/Article/details/gt2nugeolxd.html

protocol Shape { func area() -> Double }
来源：http://dali.nanxinkj.top/Article/details/gt2qtksdbhe.html

[T31] Lua：Hello World
来源：http://dali.zhiwuduotai.top/Article/details/gt2vednqunf.html

print("Hello")
来源：http://dali.shzxlz.cn/Article/details/gt2eupcbent.html

[T32] Lua：局部变量
来源：http://dali.aibaodan.cn/Article/details/gt2etobxckt.html

local a = 1
来源：http://dali.xuanzx.com/Article/details/gt2vznwqlij.html

[T33] Lua：表（数组）
来源：http://dali.iojbl.cn/Article/details/gt2dwpvstnm.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.guannengcc.top/Article/details/gt2tmjewvdb.html

[T34] Lua：遍历表
来源：http://dali.yvedp.cn/Article/details/gt2ranlvrhj.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.nanxinkj.top/Article/details/gt2nsrmggfd.html

[T35] Lua：字典表
来源：http://dali.svipenyu.cn/Article/details/gt2azwjljvp.html

local d = { a = 1 };  d.b = 2
来源：http://dali.birdmap.top/Article/details/gt2qqthtqmv.html

[T36] Lua：函数
来源：http://dali.daxiang520.top/Article/details/gt2bqobupqu.html

function add(a, b) return a + b end
来源：http://dali.jiagoushi.top/Article/details/gt2amytwrjq.html

[T37] Lua：字符串拼接
来源：http://dali.xinyue.icu/Article/details/gt2xbccbzkk.html

"a" .. "b"
来源：http://dali.wangdashe.top/Article/details/gt2biohdsgo.html

[T38] Lua：条件
来源：http://dali.chenlongwang.top/Article/details/gt2ubijuvdr.html

if x > 0 then print("正") end
来源：http://dali.yueranfly.top/Article/details/gt2pxmcnopx.html

[T39] Lua：模式匹配
来源：http://dali.gotoacloud.top/Article/details/gt2cfrxxyki.html

string.find(s, "%d+")
来源：http://dali.bjfxy.top/Article/details/gt2drxydpvv.html

[T40] Lua：元表
来源：http://dali.dashuyun.cn/Article/details/gt2dpuxbjjm.html

setmetatable({}, { __index = base })
来源：http://dali.hfpthk.cn/Article/details/gt2akwecvzx.html

[T41] Perl：Hello World
来源：http://dali.wangdashe.top/Article/details/gt2yvamoehu.html

print "Hello\n";
来源：http://dali.jqgfzy.top/Article/details/gt2qwgrkfzv.html

[T42] Perl：变量类型
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mtwcstud.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.xuanzx.com/Article/details/gt2kxkdmbgx.html

[T43] Perl：字符串插值
来源：http://dali.cheryme.top/Article/details/gt2ayzbrmbw.html

"值: $a"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pbrpzuhn.html

[T44] Perl：条件
来源：http://dali.sweek.top/Article/details/gt2qayixium.html

if ($a > 0) { print "正"; }
来源：http://dali.aibaodan.cn/Article/details/gt2sjbefjck.html

[T45] Perl：数组遍历
来源：http://dali.havefunace.top/Article/details/gt2ofaazgxj.html

for my $x (@arr) { print $x; }
来源：http://dali.gaohongyu789.top/Article/details/gt2beroxxkn.html

[T46] Perl：哈希操作
来源：http://dali.redwolf501.top/Article/details/gt2jnpapudu.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.ybcxt.top/Article/details/gt2eojktvus.html

[T47] Perl：正则捕获
来源：http://dali.shuidangran.top/Article/details/gt2wjjequxu.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.yonumen.top/Article/details/gt2zpcygcaz.html

[T48] Perl：正则替换
来源：http://dali.jlsjyb.cn/Article/details/gt2ptkewfug.html

$s =~ s/old/new/g;
来源：http://dali.smart0.xyz/Article/details/gt2woguxqsf.html

[T49] Perl：函数
来源：http://dali.yangfankeji.com/Article/details/gt2abqjpswc.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2kvaopewu.html

[T50] Perl：逐行读文件
来源：http://dali.ybcxt.top/Article/details/gt2ymgnbcjx.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.hywenlv.cn/Article/details/gt2saaxxvcs.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.haohaochexian.top/Article/details/gt2zzlphoro.html

[T51] Scala：Hello World
来源：http://dali.quarkkingdee.top/Article/details/gt2tovdpzhf.html

println("Hello")
来源：http://dali.shangyingyoupin.top/Article/details/gt2rblvjlkc.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2iccpepyt.html


<!-- 参考信息 -->