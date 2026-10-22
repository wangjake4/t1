代发 wailian999

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.guannengcc.top/Article/details/gt2xmfaivwn.html

[R54] 比较两个文件
来源：http://dali.shuidangran.top/Article/details/gt2srmliyit.html

diff a.txt b.txt
来源：http://dali.iojbl.cn/Article/details/gt2gkpovddx.html

[R55] 压缩与解压
来源：http://dali.yonumen.top/Article/details/gt2wnqwfyan.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.hywenlv.cn/Article/details/gt2pjdzpzrr.html

[R56] 远程拷贝
来源：http://dali.fzhhl.top/Article/details/gt2tfirutag.html

scp file user@host:/path/
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rzszwnkk.html

[R57] 远程执行命令
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mrphwitr.html

ssh user@host 'uptime'
来源：http://dali.ivvv.top/Article/details/gt2zyvijjhb.html

[R58] 下载文件
来源：http://dali.yanxiufei.cn/Article/details/gt2gvskcrbz.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.tanke756.top/Article/details/gt2aimpqjwa.html

[R59] 发 POST JSON
来源：http://dali.hnxiangtu.top/Article/details/gt2lptfporb.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.ydzc1.top/Article/details/gt2qsbdbkhm.html

[R60] 只看 HTTP 状态码
来源：http://dali.zdqjudy.top/Article/details/gt2ttapapxw.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.cashguo.top/Article/details/gt2tggvdkbg.html

[R61] 磁盘占用
来源：http://dali.xziqi.cn/Article/details/gt2jhrqkagd.html

df -h;  du -sh *
来源：http://dali.9152youxi.cn/Article/details/gt2vzbvkidx.html

[R62] 找最占空间的文件
来源：http://dali.wangdashe.top/Article/details/gt2bvswmpmc.html

du -ah . | sort -rh | head -10
来源：http://dali.guannengcc.top/Article/details/gt2hllknfje.html

[R63] 内存与进程
来源：http://dali.xinyue.icu/Article/details/gt2wlvcabfz.html

free -h;  ps aux | grep nginx
来源：http://dali.chenlongwang.top/Article/details/gt2nolwtycm.html

[R64] 结束进程
来源：http://dali.nanxuanxn.top/Article/details/gt2nlnzkgmq.html

kill -9 $(pgrep -f app.py)
来源：http://dali.jqgfzy.top/Article/details/gt2sdtagrll.html

[R65] 查看端口占用
来源：http://dali.kuanghao11.cn/Article/details/gt2aanbvoqy.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.gogol.net.cn/Article/details/gt2pwrvuyjm.html

[R66] 定时任务
来源：http://dali.hnqzz.top/Article/details/gt2rfwwnaxa.html

crontab -e;  crontab -l
来源：http://dali.chenjidiqi.icu/Article/details/gt2tticxkac.html

[R67] 生成随机十六进制串
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hkiparwd.html

openssl rand -hex 16
来源：http://dali.cqqwz.cn/Article/details/gt2dzgdpvbh.html

[R68] 计算文件校验值
来源：http://dali.guowangkeji.top/Article/details/gt2ketsafom.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.sxryk.cn/Article/details/gt2axvctlyx.html

[R69] 生成随机密码
来源：http://dali.yj20258888.top/Article/details/gt2wjleakxs.html

head -c 16 /dev/urandom | base64
来源：http://dali.aibaodan.cn/Article/details/gt2lwbjvxft.html

[R70] 时间戳与互转
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2erezugzk.html

date +%s;  date -d @1700000000
来源：http://dali.zhengqikj.top/Article/details/gt2qfqaksxr.html

[R71] 日期格式化
来源：http://dali.yongpay.top/Article/details/gt2btjugxub.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.yj20258.top/Article/details/gt2zoyezwoj.html

[R72] 等待端口就绪
来源：http://dali.dianchejie.cn/Article/details/gt2sqwdbfpj.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.ydzc1.top/Article/details/gt2aeodnman.html

[R73] 分割大日志
来源：http://dali.mhx1999.top/Article/details/gt2dmznlxyg.html

split -l 1000 big.log part_
来源：http://dali.xziqi.cn/Article/details/gt2insbbxmd.html

[R74] 批量重命名
来源：http://dali.vqdsnc.cn/Article/details/gt2lklifxux.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.shuidangran.top/Article/details/gt2yryoncnd.html

[R75] 导出环境变量
来源：http://dali.shuidangran.top/Article/details/gt2wpgyokwu.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.gotoacloud.top/Article/details/gt2ascklzfz.html

[R76] 使用临时文件
来源：http://dali.feifeiyinyue.top/Article/details/gt2pwuvwipq.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.pengpengdd.cyou/Article/details/gt2ltxoxanm.html

[R77] 读取用户输入
来源：http://dali.yongpay.top/Article/details/gt2qgjggkrg.html

read -rp "请输入: " ans
来源：http://dali.yangfankeji.com/Article/details/gt2cuwabcsw.html

[R78] 交互式菜单
来源：http://dali.xuanzx.com/Article/details/gt2rlltaktj.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zsjlhbet.html

[R79] 解析命令行选项
来源：http://dali.vqdsnc.cn/Article/details/gt2pzjxsjmw.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.yj202588.top/Article/details/gt2izhxoxxq.html

[R80] 查看脚本执行耗时
来源：http://dali.xuetiantiany.cn/Article/details/gt2ptqasbfw.html

time ./run.sh
来源：http://dali.svipenyu.cn/Article/details/gt2upduwawc.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2syfrgcvz.html

S. C / C++ 专题
来源：http://dali.haohaochexian.top/Article/details/gt2bbmtkgzq.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2xobvrfrq.html

[S01] C：Hello World
来源：http://dali.meibo888.top/Article/details/gt2omxremgz.html

#include <stdio.h>
来源：http://dali.sweek.top/Article/details/gt2izortkrw.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.hywenlv.cn/Article/details/gt2vovtklmd.html

[S02] C：变量与格式化输出
来源：http://dali.zhengqikj.top/Article/details/gt2sbikpypc.html

int a = 10; printf("%d\n", a);
来源：http://dali.hammf.cn/Article/details/gt2dwiqgioz.html

[S03] C：读入整数
来源：http://dali.cucudq.cn/Article/details/gt2hmmbgwls.html

int x; scanf("%d", &x);
来源：http://dali.tian-w.cn/Article/details/gt2ljvymvpq.html

[S04] C：字符串复制
来源：http://dali.yangfankeji.com/Article/details/gt2qkuguvdr.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.cqqwz.cn/Article/details/gt2jrnrccyw.html

[S05] C：字符串长度
来源：http://dali.yvedp.cn/Article/details/gt2febdtvyf.html

strlen(s)
来源：http://dali.xziqi.cn/Article/details/gt2wrqjklzu.html

[S06] C：字符串比较
来源：http://dali.sweek.top/Article/details/gt2hffvxfqe.html

strcmp(a, b) == 0
来源：http://dali.yj20258888.top/Article/details/gt2qwyrfunj.html

[S07] C：数组遍历求和
来源：http://dali.birdmap.top/Article/details/gt2ocwvjykg.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.hongshengwenyu.top/Article/details/gt2toekauuh.html

[S08] C：动态内存分配与释放
来源：http://dali.yj20258888.top/Article/details/gt2esqkkvrc.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wtdhawxm.html

[S09] C：结构体定义与初始化
来源：http://dali.haohaochexian.top/Article/details/gt2lbnmavcs.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.vqdsnc.cn/Article/details/gt2vivdgiha.html

[S10] C：指针与解引用
来源：http://dali.aibaodan.cn/Article/details/gt2vvgunnvx.html

int *p = &a;  *p = 5;
来源：http://dali.316326.xyz/Article/details/gt2gajtqdrv.html

[S11] C：逐行读文件
来源：http://dali.sysykeji.top/Article/details/gt2djmusygr.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2olqcclbl.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.andypj.xyz/Article/details/gt2ozjkisnp.html

fclose(f);
来源：http://dali.gzhubu.top/Article/details/gt2tsjcafrp.html

[S12] C：写文件
来源：http://dali.jianghu66.top/Article/details/gt2qqvmmnch.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.gotoacloud.top/Article/details/gt2dmkfupom.html

[S13] C：宏定义
来源：http://dali.sxryk.cn/Article/details/gt2fcfiuzxy.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhoulong.xyz/Article/details/gt2vheeptul.html

[S14] C：枚举
来源：http://dali.shangyingyoupin.top/Article/details/gt2hggglhvt.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.daria6918.cn/Article/details/gt2vtayukfe.html

[S15] C：类型转换
来源：http://dali.yongpay.top/Article/details/gt2ribedssq.html

(double) a / b
来源：http://dali.birdmap.top/Article/details/gt2cvjgbpym.html

[S16] C：位操作置位
来源：http://dali.cashguo.top/Article/details/gt2djwauwvw.html

x |= (1 << 3);
来源：http://dali.haohaochexian.top/Article/details/gt2urndvfuo.html

[S17] C：安全拼接字符串
来源：http://dali.pengpengdd.cyou/Article/details/gt2jcawfjwb.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.yongpay.top/Article/details/gt2wviqxuam.html

[S18] C：命令行参数
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ljqxjrwy.html

int main(int argc, char **argv)
来源：http://dali.nwbrower.top/Article/details/gt2ttgaevbx.html

[S19] C：快速排序
来源：http://dali.pycfn.com/Article/details/gt2tqppwgtm.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.9152youxi.cn/Article/details/gt2jgisjyav.html

[S20] C：二分查找
来源：http://dali.jiagoushi.top/Article/details/gt2ghekgifk.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.bjfxy.top/Article/details/gt2lblaznkb.html

[S21] C：字符类别判断
来源：http://dali.xylfe.cn/Article/details/gt2qnywihns.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.snrcjt.cn/Article/details/gt2fvatvznu.html

[S22] C：字符串转数字
来源：http://dali.cdnleiting.top/Article/details/gt2pfrtwukj.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.316326.xyz/Article/details/gt2edotwajm.html

[S23] C：随机数
来源：http://dali.yanxiufei.cn/Article/details/gt2urwjpcpz.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.xinyue.icu/Article/details/gt2hfopmrtq.html

[S24] C：获取本地时间
来源：http://dali.fengsongda.top/Article/details/gt2udyiaqnn.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.ehwqpu.com/Article/details/gt2kndlwwwh.html

[S25] C：内存拷贝
来源：http://dali.fzhhl.top/Article/details/gt2lkqokaqm.html

memcpy(dst, src, n);
来源：http://dali.smart0.xyz/Article/details/gt2welobppm.html

[S26] C：内存清零
来源：http://dali.meibo888.top/Article/details/gt2qjfbnhds.html

memset(a, 0, sizeof a);
来源：http://dali.zhengqikj.top/Article/details/gt2ybqsfcsq.html

[S27] C：定义常量
来源：http://dali.sxryk.cn/Article/details/gt2nlihmbuh.html

const double PI = 3.14159;
来源：http://dali.yangfankeji.com/Article/details/gt2wazmakqm.html

[S28] C：静态变量
来源：http://dali.nanxuanxn.top/Article/details/gt2mzycovae.html

static int counter = 0;
来源：http://dali.hnxiangtu.top/Article/details/gt2mrgdnhgw.html

[S29] C：变参函数
来源：http://dali.xziqi.cn/Article/details/gt2nmnpyhej.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dhjqlqao.html

[S30] C：头文件保护
来源：http://dali.feifeiyinyue.top/Article/details/gt2lbstozys.html

#ifndef X_H
来源：http://dali.chenzaomai.com/Article/details/gt2sewnztxq.html

#define X_H
来源：http://dali.hywenlv.cn/Article/details/gt2pmqnkwge.html

#endif
来源：http://dali.chenlongwang.top/Article/details/gt2ogafkxoc.html

[S31] C++：Hello World
来源：http://dali.cucudq.cn/Article/details/gt2tuxearpd.html

#include <iostream>
来源：http://dali.nanxinkj.top/Article/details/gt2zeaudexn.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.jianghu66.top/Article/details/gt2eqpuhbnu.html

[S32] C++：字符串
来源：http://dali.andypj.xyz/Article/details/gt2cqrcxqnj.html

std::string s = "hi";  s += "!";
来源：http://dali.snrcjt.cn/Article/details/gt2hbpyagqz.html

[S33] C++：vector 增删
来源：http://dali.xylfe.cn/Article/details/gt2jufeqhdw.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.cucudq.cn/Article/details/gt2qlwjwjzq.html

[S34] C++：遍历 vector
来源：http://dali.yuxming.cn/Article/details/gt2jndiccsd.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lastmjdc.html

[S35] C++：map
来源：http://dali.0kj1m.cn/Article/details/gt2ewbszyvh.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.316326.xyz/Article/details/gt2zkrgesyf.html

[S36] C++：unordered_map
来源：http://dali.jqgfzy.top/Article/details/gt2hhloltth.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.feifeiyinyue.top/Article/details/gt2bxulmdnd.html

[S37] C++：set
来源：http://dali.birdmap.top/Article/details/gt2xeqfguxe.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.xuanzx.com/Article/details/gt2swkrpuhe.html

[S38] C++：排序
来源：http://dali.cdnleiting.top/Article/details/gt2ulsyvemu.html

std::sort(v.begin(), v.end());
来源：http://dali.mhx1999.top/Article/details/gt2vfpwkbpt.html

[S39] C++：自定义比较器排序
来源：http://dali.vqdsnc.cn/Article/details/gt2wwnlbdlc.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhixingplan.top/Article/details/gt2xrnnvpka.html

[S40] C++：查找元素
来源：http://dali.fzhhl.top/Article/details/gt2dgqikzxs.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.nwbrower.top/Article/details/gt2mnkuvkwt.html

[S41] C++：类与构造函数
来源：http://dali.xinyue.icu/Article/details/gt2xydnggyc.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lhovrqek.html

[S42] C++：继承与虚函数
来源：http://dali.jianghu66.top/Article/details/gt2vowdcrtb.html

class B : public Base { public: void f() override {} };
来源：http://dali.0kj1m.cn/Article/details/gt2yvmrgsrk.html

[S43] C++：智能指针
来源：http://dali.sxryk.cn/Article/details/gt2oauuaima.html

auto p = std::make_unique<int>(5);
来源：http://dali.jianghu66.top/Article/details/gt2pptkijxb.html

[S44] C++：引用传参
来源：http://dali.ybcxt.top/Article/details/gt2botbvyvi.html

void inc(int &x) { ++x; }
来源：http://dali.xylfe.cn/Article/details/gt2iedhsznv.html

[S45] C++：lambda
来源：http://dali.jinqigufen.top/Article/details/gt2wqohyahc.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.chenzaomai.com/Article/details/gt2eziqyhim.html

[S46] C++：函数模板
来源：http://dali.birdmap.top/Article/details/gt2ywckruuq.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.haohaochexian.top/Article/details/gt2ljivxvab.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhoulong.xyz/Article/details/gt2dhrhjocu.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.quarkkingdee.top/Article/details/gt2ilqodopg.html

[S48] C++：逐行读文件
来源：http://dali.zhongyouzk.top/Article/details/gt2gbacojjh.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.sufxvd.cn/Article/details/gt2pftvbdkd.html

while (std::getline(in, line)) { }
来源：http://dali.yangfankeji.com/Article/details/gt2mupyfofe.html

[S49] C++：写文件
来源：http://dali.bjfxy.top/Article/details/gt2zmjvotcj.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.havefunace.top/Article/details/gt2aljiheqq.html

[S50] C++：格式化数字
来源：http://dali.c1oappe.top/Article/details/gt2tzwgkgpf.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.jinqigfzy.top/Article/details/gt2yxqemhjd.html

[S51] C++：显式类型转换
来源：http://dali.birdmap.top/Article/details/gt2fqzxoned.html

static_cast<double>(a) / b
来源：http://dali.jiagoushi.top/Article/details/gt2fqxkxzjc.html

[S52] C++：const 与 noexcept
来源：http://dali.snrcjt.cn/Article/details/gt2tntmtmzv.html

int size() const noexcept { return n_; }
来源：http://dali.redwolf501.top/Article/details/gt2ahiciyeq.html

[S53] C++：移动语义
来源：http://dali.jiagoushi.top/Article/details/gt2cvowhhis.html

std::vector<int> w = std::move(v);
来源：http://dali.tianlin.xyz/Article/details/gt2ayxgiaqb.html

[S54] C++：异常处理
来源：http://dali.yj20258888.top/Article/details/gt2hocfkacg.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.fengsongda.top/Article/details/gt2yukkfnka.html

[S55] C++：结构化绑定
来源：http://dali.yuxming.cn/Article/details/gt2ermvvcek.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.yj202588.top/Article/details/gt2nabvhxyy.html

[S56] C++：optional
来源：http://dali.chenlongwang.top/Article/details/gt2yduenrfq.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.shuidangran.top/Article/details/gt2jynhabym.html

[S57] C++：编译期常量
来源：http://dali.gotoacloud.top/Article/details/gt2ylqwocxy.html

constexpr int N = 10;
来源：http://dali.cdnleiting.top/Article/details/gt2faffhefk.html

[S58] C++：命名空间
来源：http://dali.yvedp.cn/Article/details/gt2nyrvobth.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rcpfcsss.html

[S59] C++：静态断言
来源：http://dali.birdmap.top/Article/details/gt2gdhlgdcu.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.dianchejie.cn/Article/details/gt2oohokzws.html

[S60] C++：遍历并删除元素
来源：http://dali.hammf.cn/Article/details/gt2xdflzmwd.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.wangshuangyany.cn/Article/details/gt2miryxkza.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2shnetpex.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.jqgfzy.top/Article/details/gt2pkhoulbd.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2avsthtsh.html

[T01] Kotlin：Hello World
来源：http://dali.hysaishi.cn/Article/details/gt2iaemgsco.html

println("Hello")
来源：http://dali.sufxvd.cn/Article/details/gt2xuopggxk.html

[T02] Kotlin：变量
来源：http://dali.jyoumei.cn/Article/details/gt2uhhzuccs.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.yonumen.top/Article/details/gt2dhhpmbof.html

[T03] Kotlin：字符串模板
来源：http://dali.jianghu66.top/Article/details/gt2xvluwohv.html

"值: $b"
来源：http://dali.yj20258.top/Article/details/gt2jicahvsl.html

[T04] Kotlin：空安全
来源：http://dali.guannengcc.top/Article/details/gt2hfaxledo.html

val n: String? = null;  n?.length
来源：http://dali.fzhhl.top/Article/details/gt2dyeqenag.html

[T05] Kotlin：when 表达式
来源：http://dali.zycfv.cn/Article/details/gt2jvvhvgzv.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.sysykeji.top/Article/details/gt2rjumzjpw.html

[T06] Kotlin：集合映射
来源：http://dali.tianlin.xyz/Article/details/gt2fngxwugm.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.ybcxt.top/Article/details/gt2fwvelnpl.html

[T07] Kotlin：集合过滤
来源：http://dali.meibo888.top/Article/details/gt2wukmxkrl.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.dashuyun.cn/Article/details/gt2kxugqpvi.html

[T08] Kotlin：数据类
来源：http://dali.gzhubu.top/Article/details/gt2vmptfkjs.html

data class User(val name: String, val age: Int)
来源：http://dali.kuanghao11.cn/Article/details/gt2qvjsecjy.html

[T09] Kotlin：扩展函数
来源：http://dali.gogol.net.cn/Article/details/gt2agfuimri.html

fun String.exclaim() = this + "!"
来源：http://dali.xziqi.cn/Article/details/gt2frbqguzs.html

[T10] Kotlin：默认参数
来源：http://dali.zhoulong.xyz/Article/details/gt2jvtclfkr.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nrgmkzwm.html

[T11] Kotlin：协程
来源：http://dali.daria6918.cn/Article/details/gt2jocdrcdw.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.yanxiufei.cn/Article/details/gt2ytldeuwd.html

[T12] Kotlin：解构声明
来源：http://dali.yangfankeji.com/Article/details/gt2jkpmjubu.html

val (a, b) = Pair(1, 2)
来源：http://dali.xuetiantiany.cn/Article/details/gt2tfgelydq.html

[T13] Kotlin：只读 Map
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jtrbcdka.html

val m = mapOf("a" to 1)
来源：http://dali.tianlin.xyz/Article/details/gt2odejsyrq.html

[T14] Kotlin：循环
来源：http://dali.bjfxy.top/Article/details/gt2hvpuwrje.html

for (i in 1..10) println(i)
来源：http://dali.0kj1m.cn/Article/details/gt2ehahajxe.html

[T15] Kotlin：接口
来源：http://dali.cdnleiting.top/Article/details/gt2rxsrfsfo.html

interface Shape { fun area(): Double }
来源：http://dali.iojbl.cn/Article/details/gt2hkmaarpa.html

[T16] Swift：Hello World
来源：http://dali.wangdashe.top/Article/details/gt2kdhpmhcy.html

print("Hello")
来源：http://dali.yvedp.cn/Article/details/gt2jcafqmek.html

[T17] Swift：变量与常量
来源：http://dali.tian-w.cn/Article/details/gt2srwykqjm.html

var a = 1;  let b = 2
来源：http://dali.zycfv.cn/Article/details/gt2ciurhocp.html

[T18] Swift：字符串插值
来源：http://dali.smart0.xyz/Article/details/gt2mpxxrxtx.html

"值: \(b)"
来源：http://dali.nwbrower.top/Article/details/gt2slukwttj.html

[T19] Swift：可选绑定
来源：http://dali.birdmap.top/Article/details/gt2uzyfglef.html

if let n = opt { print(n) }
来源：http://dali.tanke756.top/Article/details/gt2qhuhlvtl.html

[T20] Swift：数组操作
来源：http://dali.c1oappe.top/Article/details/gt2apzrhtit.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.c1oappe.top/Article/details/gt2iyonfgcq.html

[T21] Swift：遍历
来源：http://dali.svipenyu.cn/Article/details/gt2sicywtvn.html

for x in a { print(x) }
来源：http://dali.tianlin.xyz/Article/details/gt2zeghsrdf.html

[T22] Swift：字典
来源：http://dali.cqqwz.cn/Article/details/gt2ufenmfln.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gpkvxjzo.html

[T23] Swift：函数
来源：http://dali.gogol.net.cn/Article/details/gt2jkngudxs.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.yj20258.top/Article/details/gt2efmdcwxv.html

[T24] Swift：闭包
来源：http://dali.zhoulong.xyz/Article/details/gt2bztomukk.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.daxiang520.top/Article/details/gt2izuwawod.html

[T25] Swift：结构体
来源：http://dali.daria6918.cn/Article/details/gt2uxixqdrq.html

struct P { var x: Int }
来源：http://dali.hongshengwenyu.top/Article/details/gt2tfproeyk.html

[T26] Swift：类与重写
来源：http://dali.yvedp.cn/Article/details/gt2wznmqcyn.html

class A: Base { override func f() {} }
来源：http://dali.quarkkingdee.top/Article/details/gt2rkprqfro.html

[T27] Swift：错误处理
来源：http://dali.jqgfzy.top/Article/details/gt2zivhkpfo.html

do { try f() } catch { print(error) }
来源：http://dali.sufxvd.cn/Article/details/gt2iygcjrhg.html

[T28] Swift：枚举
来源：http://dali.hywenlv.cn/Article/details/gt2yexqhzky.html

enum Color { case red, green }
来源：http://dali.sweek.top/Article/details/gt2ahdzmnel.html

[T29] Swift：guard 提前返回
来源：http://dali.yj20258888.top/Article/details/gt2milokpyc.html

guard let x = opt else { return }
来源：http://dali.cqqwz.cn/Article/details/gt2eohwhyby.html

[T30] Swift：协议
来源：http://dali.yuanzhike.top/Article/details/gt2ncngrzeu.html

protocol Shape { func area() -> Double }
来源：http://dali.gaohongyu789.top/Article/details/gt2sgnixjgc.html

[T31] Lua：Hello World
来源：http://dali.cashguo.top/Article/details/gt2toubbmka.html

print("Hello")
来源：http://dali.chenlongwang.top/Article/details/gt2whrjcjmi.html

[T32] Lua：局部变量
来源：http://dali.gogol.net.cn/Article/details/gt2whhymuqg.html

local a = 1
来源：http://dali.ydzc1.top/Article/details/gt2gffkuspa.html

[T33] Lua：表（数组）
来源：http://dali.guannengcc.top/Article/details/gt2nkciyiqo.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhoulong.xyz/Article/details/gt2gygsxlaq.html

[T34] Lua：遍历表
来源：http://dali.ehwqpu.com/Article/details/gt2tvqyhudi.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.aibaodan.cn/Article/details/gt2jmottwbk.html

[T35] Lua：字典表
来源：http://dali.xuetiantiany.cn/Article/details/gt2nisddabc.html

local d = { a = 1 };  d.b = 2
来源：http://dali.jianghu66.top/Article/details/gt2iwwiwskw.html

[T36] Lua：函数
来源：http://dali.yj20258.top/Article/details/gt2czdcgihj.html

function add(a, b) return a + b end
来源：http://dali.xinyue.icu/Article/details/gt2ixeyhvta.html

[T37] Lua：字符串拼接
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tovsvqsi.html

"a" .. "b"
来源：http://dali.redwolf501.top/Article/details/gt2lwlcyqoh.html

[T38] Lua：条件
来源：http://dali.yvedp.cn/Article/details/gt2sitottit.html

if x > 0 then print("正") end
来源：http://dali.yvedp.cn/Article/details/gt2lugryyai.html

[T39] Lua：模式匹配
来源：http://dali.cdnleiting.top/Article/details/gt2vooywcsq.html

string.find(s, "%d+")
来源：http://dali.jqgfzy.top/Article/details/gt2kxdynigu.html

[T40] Lua：元表
来源：http://dali.iojbl.cn/Article/details/gt2jtaseezc.html

setmetatable({}, { __index = base })
来源：http://dali.zhiwuduotai.top/Article/details/gt2ccovulml.html

[T41] Perl：Hello World
来源：http://dali.fengsongda.top/Article/details/gt2xflgoczb.html

print "Hello\n";
来源：http://dali.haohaochexian.top/Article/details/gt2dzymuaaa.html

[T42] Perl：变量类型
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nobmshax.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhengqikj.top/Article/details/gt2kmhqfnpr.html

[T43] Perl：字符串插值
来源：http://dali.chenjidiqi.icu/Article/details/gt2rmfrsfxx.html

"值: $a"
来源：http://dali.shangyingyoupin.top/Article/details/gt2tiadvhvb.html

[T44] Perl：条件
来源：http://dali.hnxiangtu.top/Article/details/gt2cqyosysf.html

if ($a > 0) { print "正"; }
来源：http://dali.smart0.xyz/Article/details/gt2ectreywp.html

[T45] Perl：数组遍历
来源：http://dali.shuidangran.top/Article/details/gt2vkbghitb.html

for my $x (@arr) { print $x; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vwkksgps.html

[T46] Perl：哈希操作
来源：http://dali.9152youxi.cn/Article/details/gt2fgprpeks.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.fengsongda.top/Article/details/gt2fjkrtwtr.html

[T47] Perl：正则捕获
来源：http://dali.sxryk.cn/Article/details/gt2cnytlfpz.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.hnxiangtu.top/Article/details/gt2fgtipzon.html

[T48] Perl：正则替换
来源：http://dali.jianghu66.top/Article/details/gt2dpffzyby.html

$s =~ s/old/new/g;
来源：http://dali.yj20258888.top/Article/details/gt2akhwsblm.html

[T49] Perl：函数
来源：http://dali.sufxvd.cn/Article/details/gt2wpvhaivf.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.hywenlv.cn/Article/details/gt2mjaktkfr.html

[T50] Perl：逐行读文件
来源：http://dali.quarkkingdee.top/Article/details/gt2powwwvzn.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhixingplan.top/Article/details/gt2iboxqrhs.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.mhx1999.top/Article/details/gt2mvukxega.html

[T51] Scala：Hello World
来源：http://dali.dianchejie.cn/Article/details/gt2yraofmty.html

println("Hello")
来源：http://dali.zhixingplan.top/Article/details/gt2pfwmbtjp.html

[T52] Scala：变量
来源：http://dali.mhx1999.top/Article/details/gt2tooyncvn.html

val a = 1;  var b = 2
来源：http://dali.yongpay.top/Article/details/gt2icelnfhk.html

[T53] Scala：字符串插值
来源：http://dali.aibaodan.cn/Article/details/gt2rlnvtwrb.html

s"值: $b"
来源：http://dali.hnqzz.top/Article/details/gt2owcwjyvl.html

[T54] Scala：集合映射
来源：http://dali.sweek.top/Article/details/gt2lsudtjhk.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.chenjidiqi.icu/Article/details/gt2kvrpqksf.html

[T55] Scala：集合过滤
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hpfhfnus.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.shzxlz.cn/Article/details/gt2msnnaznd.html

[T56] Scala：样例类
来源：http://dali.yj20258888.top/Article/details/gt2qrkdgicm.html


<!-- 参考信息 -->