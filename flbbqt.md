代发 wailian999

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.ybcxt.top/Article/details/gttriknvfx.html

[R52] 统计行数
来源：http://dali.fengsongda.top/Article/details/gtrmtauvcr.html

wc -l a.txt
来源：http://dali.jqgufenzy.top/Article/details/gtuoojbqmq.html

[R53] 查看文件头与实时尾
来源：http://dali.birdmap.top/Article/details/gtelpappuy.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.tian-w.cn/Article/details/gtbpjnvact.html

[R54] 比较两个文件
来源：http://dali.haohaochexian.top/Article/details/gtiyrswcoh.html

diff a.txt b.txt
来源：http://dali.hongshengwenyu.top/Article/details/gthanynbdn.html

[R55] 压缩与解压
来源：http://dali.wangdashe.top/Article/details/gtuisqtmkv.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.shuidangran.top/Article/details/gtrfdocydr.html

[R56] 远程拷贝
来源：http://dali.daxiang520.top/Article/details/gtriauyryl.html

scp file user@host:/path/
来源：http://dali.zhixingplan.top/Article/details/gtbajkjtlj.html

[R57] 远程执行命令
来源：http://dali.yangfankeji.com/Article/details/gtdqnxrngl.html

ssh user@host 'uptime'
来源：http://dali.redwolf501.top/Article/details/gtendxiuok.html

[R58] 下载文件
来源：http://dali.pengpengdd.cyou/Article/details/gtlorxicba.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.cashguo.top/Article/details/gtulnskqkb.html

[R59] 发 POST JSON
来源：http://dali.xuetiantiany.cn/Article/details/gtltmbwwul.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.jqgfzy.top/Article/details/gtoqyrlbmz.html

[R60] 只看 HTTP 状态码
来源：http://dali.guowangkeji.top/Article/details/gtcpwnxkyo.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhongyouzk.top/Article/details/gtqodsjdtt.html

[R61] 磁盘占用
来源：http://dali.dianchejie.cn/Article/details/gtweleszuf.html

df -h;  du -sh *
来源：http://dali.yuxming.cn/Article/details/gtbazbhlee.html

[R62] 找最占空间的文件
来源：http://dali.jiagoushi.top/Article/details/gthlsulgqg.html

du -ah . | sort -rh | head -10
来源：http://dali.jyoumei.cn/Article/details/gtinprzomy.html

[R63] 内存与进程
来源：http://dali.tian-w.cn/Article/details/gtuyxcazxs.html

free -h;  ps aux | grep nginx
来源：http://dali.yongpay.top/Article/details/gtxnhslwlx.html

[R64] 结束进程
来源：http://dali.gogol.net.cn/Article/details/gtbndmvymx.html

kill -9 $(pgrep -f app.py)
来源：http://dali.chenjidiqi.icu/Article/details/gtdnzuepvr.html

[R65] 查看端口占用
来源：http://dali.shzxlz.cn/Article/details/gtbeckmhyr.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.dianchejie.cn/Article/details/gtkbkjtyup.html

[R66] 定时任务
来源：http://dali.ybcxt.top/Article/details/gtupxdgtfy.html

crontab -e;  crontab -l
来源：http://dali.jianghu66.top/Article/details/gttmvipjze.html

[R67] 生成随机十六进制串
来源：http://dali.yj20258888.top/Article/details/gtehhvmsap.html

openssl rand -hex 16
来源：http://dali.9152youxi.cn/Article/details/gtzkkbsdti.html

[R68] 计算文件校验值
来源：http://dali.havefunace.top/Article/details/gtfcgxjyax.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.redwolf501.top/Article/details/gtsrsjvvbw.html

[R69] 生成随机密码
来源：http://dali.chenlongwang.top/Article/details/gtbrrycths.html

head -c 16 /dev/urandom | base64
来源：http://dali.daxiang520.top/Article/details/gtnbtetwit.html

[R70] 时间戳与互转
来源：http://dali.gotoacloud.top/Article/details/gtidxesfvv.html

date +%s;  date -d @1700000000
来源：http://dali.hnqzz.top/Article/details/gtbnxkqgsm.html

[R71] 日期格式化
来源：http://dali.shangyingyoupin.top/Article/details/gtjxjduzma.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.jiagoushi.top/Article/details/gtydolgqmx.html

[R72] 等待端口就绪
来源：http://dali.aizwys.cn/Article/details/gttrdlhtay.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.smart0.xyz/Article/details/gtqcyyngvh.html

[R73] 分割大日志
来源：http://dali.pengpengdd.cyou/Article/details/gtfqkelgoe.html

split -l 1000 big.log part_
来源：http://dali.nanxuanxn.top/Article/details/gtdarstwmv.html

[R74] 批量重命名
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdcobxdno.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.9152youxi.cn/Article/details/gtjqqpyorp.html

[R75] 导出环境变量
来源：http://dali.9152youxi.cn/Article/details/gtauowagsh.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.cqqwz.cn/Article/details/gtvnlvypre.html

[R76] 使用临时文件
来源：http://dali.zhixingplan.top/Article/details/gtossgwynb.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.hfpthk.cn/Article/details/gtocwngewz.html

[R77] 读取用户输入
来源：http://dali.feifeiyinyue.top/Article/details/gtfargwidh.html

read -rp "请输入: " ans
来源：http://dali.aizwys.cn/Article/details/gtbmjriojp.html

[R78] 交互式菜单
来源：http://dali.hfpthk.cn/Article/details/gtnjjqsesd.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.jinqigufen.top/Article/details/gtpsrwkhzo.html

[R79] 解析命令行选项
来源：http://dali.cucudq.cn/Article/details/gtcduxzjld.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.daria6918.cn/Article/details/gtpusitvob.html

[R80] 查看脚本执行耗时
来源：http://dali.jiagoushi.top/Article/details/gtotjbchvi.html

time ./run.sh
来源：http://dali.iojbl.cn/Article/details/gtlerfwkjh.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtetnpxghk.html

S. C / C++ 专题
来源：http://dali.dianchejie.cn/Article/details/gtkunqsqsq.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtfdysioqa.html

[S01] C：Hello World
来源：http://dali.gaohongyu789.top/Article/details/gtxqcbdpjk.html

#include <stdio.h>
来源：http://dali.guowangkeji.top/Article/details/gtzuthwqns.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.ppjwa.cn/Article/details/gtdnqdyazp.html

[S02] C：变量与格式化输出
来源：http://dali.nanxinkj.top/Article/details/gtbvwvevaa.html

int a = 10; printf("%d\n", a);
来源：http://dali.feifeiyinyue.top/Article/details/gtlwhbpjys.html

[S03] C：读入整数
来源：http://dali.wangdashe.top/Article/details/gtjkhwwpsh.html

int x; scanf("%d", &x);
来源：http://dali.mhx1999.top/Article/details/gtluujrada.html

[S04] C：字符串复制
来源：http://dali.sysykeji.top/Article/details/gtxodpurnn.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.jqgufenzy.top/Article/details/gtydriqszk.html

[S05] C：字符串长度
来源：http://dali.hywenlv.cn/Article/details/gtxifzqela.html

strlen(s)
来源：http://dali.daxiang520.top/Article/details/gtcwkrvmac.html

[S06] C：字符串比较
来源：http://dali.chenlongwang.top/Article/details/gthcsinqss.html

strcmp(a, b) == 0
来源：http://dali.gotoacloud.top/Article/details/gtkuoqzzqo.html

[S07] C：数组遍历求和
来源：http://dali.shangyingyoupin.top/Article/details/gtdqrflano.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.hnxiangtu.top/Article/details/gtlvemjinj.html

[S08] C：动态内存分配与释放
来源：http://dali.xuanzx.com/Article/details/gteckcwlzm.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.cheryme.top/Article/details/gthurnqfwe.html

[S09] C：结构体定义与初始化
来源：http://dali.svipenyu.cn/Article/details/gtznsodkix.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.xinyue.icu/Article/details/gtjlqiebgt.html

[S10] C：指针与解引用
来源：http://dali.vqdsnc.cn/Article/details/gtchgxarwe.html

int *p = &a;  *p = 5;
来源：http://dali.smart0.xyz/Article/details/gtfywpgtjj.html

[S11] C：逐行读文件
来源：http://dali.zhoulong.xyz/Article/details/gtvnlmrdxh.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.daxiang520.top/Article/details/gtxokqcdfj.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.shuidangran.top/Article/details/gtpvjqinee.html

fclose(f);
来源：http://dali.hywenlv.cn/Article/details/gtqwlbocsb.html

[S12] C：写文件
来源：http://dali.jiagoushi.top/Article/details/gtdmoshazh.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.cashguo.top/Article/details/gtwzcyclew.html

[S13] C：宏定义
来源：http://dali.yj20258888.top/Article/details/gtzpukfvwn.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.xylfe.cn/Article/details/gtibaqxhyh.html

[S14] C：枚举
来源：http://dali.tian-w.cn/Article/details/gtirxxzbik.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.pycfn.com/Article/details/gtjhkryfba.html

[S15] C：类型转换
来源：http://dali.aizwys.cn/Article/details/gtoumvzqfs.html

(double) a / b
来源：http://dali.cqqwz.cn/Article/details/gthruexmju.html

[S16] C：位操作置位
来源：http://dali.guannengcc.top/Article/details/gtabhjepgk.html

x |= (1 << 3);
来源：http://dali.shangyingyoupin.top/Article/details/gtggbctdvp.html

[S17] C：安全拼接字符串
来源：http://dali.bjfxy.top/Article/details/gtnihvcurj.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gtnrmfjtdt.html

[S18] C：命令行参数
来源：http://dali.zhongyouzk.top/Article/details/gtkmuultfp.html

int main(int argc, char **argv)
来源：http://dali.andypj.xyz/Article/details/gtfvccmxot.html

[S19] C：快速排序
来源：http://dali.birdmap.top/Article/details/gtezawwstx.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.jinghuilouyu.cn/Article/details/gthaezwqjt.html

[S20] C：二分查找
来源：http://dali.hongshengwenyu.top/Article/details/gtdwqgapqv.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.dashuyun.cn/Article/details/gtgesmzdew.html

[S21] C：字符类别判断
来源：http://dali.shanyushiyangtech.top/Article/details/gtrxpantfz.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.jyoumei.cn/Article/details/gtxdrmdebm.html

[S22] C：字符串转数字
来源：http://dali.chenjidiqi.icu/Article/details/gtcxzxlokf.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.xuetiantiany.cn/Article/details/gtirgafdfl.html

[S23] C：随机数
来源：http://dali.shangyingyoupin.top/Article/details/gthpixclae.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.gotoacloud.top/Article/details/gtxzezshrr.html

[S24] C：获取本地时间
来源：http://dali.hnqzz.top/Article/details/gtwuiplsvp.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.0kj1m.cn/Article/details/gtcmrmbsir.html

[S25] C：内存拷贝
来源：http://dali.quarkkingdee.top/Article/details/gtkjdgrrer.html

memcpy(dst, src, n);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpatfppdr.html

[S26] C：内存清零
来源：http://dali.jqgfzy.top/Article/details/gtcfnfzlkd.html

memset(a, 0, sizeof a);
来源：http://dali.zhixingplan.top/Article/details/gtejwrgevz.html

[S27] C：定义常量
来源：http://dali.jinghuilouyu.cn/Article/details/gtiaeyliaa.html

const double PI = 3.14159;
来源：http://dali.tianlin.xyz/Article/details/gtadoyjiat.html

[S28] C：静态变量
来源：http://dali.c1oappe.top/Article/details/gtizamggri.html

static int counter = 0;
来源：http://dali.gaohongyu789.top/Article/details/gtxzlwjskm.html

[S29] C：变参函数
来源：http://dali.zhongyouzk.top/Article/details/gtxrcxasrr.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.snrcjt.cn/Article/details/gtbyzpnaye.html

[S30] C：头文件保护
来源：http://dali.xylfe.cn/Article/details/gtltiooooi.html

#ifndef X_H
来源：http://dali.snrcjt.cn/Article/details/gtjmkknybv.html

#define X_H
来源：http://dali.cucudq.cn/Article/details/gtdnqoyxpw.html

#endif
来源：http://dali.zhengqikj.top/Article/details/gtuokamxdn.html

[S31] C++：Hello World
来源：http://dali.andypj.xyz/Article/details/gtxbsjvcyx.html

#include <iostream>
来源：http://dali.jinghuilouyu.cn/Article/details/gtbbhpynfe.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.birdmap.top/Article/details/gthypdjgid.html

[S32] C++：字符串
来源：http://dali.zhiwuduotai.top/Article/details/gtfbyexssd.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gtpsimipot.html

[S33] C++：vector 增删
来源：http://dali.zhixingplan.top/Article/details/gttdcyzjur.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhongyouzk.top/Article/details/gtewigwrat.html

[S34] C++：遍历 vector
来源：http://dali.c1oappe.top/Article/details/gtspekcvkm.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.nanxuanxn.top/Article/details/gtmrfhfniu.html

[S35] C++：map
来源：http://dali.jyoumei.cn/Article/details/gtfizauquj.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.aibaodan.cn/Article/details/gtfayfmler.html

[S36] C++：unordered_map
来源：http://dali.yonumen.top/Article/details/gtxghltkoi.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.meibo888.top/Article/details/gtukzcpgwv.html

[S37] C++：set
来源：http://dali.hnxiangtu.top/Article/details/gtfuouvjup.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.yj202588.top/Article/details/gtebljhdtz.html

[S38] C++：排序
来源：http://dali.hfpthk.cn/Article/details/gttlohxped.html

std::sort(v.begin(), v.end());
来源：http://dali.gogol.net.cn/Article/details/gthqetyiiu.html

[S39] C++：自定义比较器排序
来源：http://dali.svipenyu.cn/Article/details/gtijykjdky.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.daria6918.cn/Article/details/gtzirxxtue.html

[S40] C++：查找元素
来源：http://dali.0kj1m.cn/Article/details/gtattywdiv.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhiwuduotai.top/Article/details/gtijmzogku.html

[S41] C++：类与构造函数
来源：http://dali.zhongyouzk.top/Article/details/gtmcxomxwd.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.nwbrower.top/Article/details/gtcdgjzmfy.html

[S42] C++：继承与虚函数
来源：http://dali.jqgufenzy.top/Article/details/gttsklziih.html

class B : public Base { public: void f() override {} };
来源：http://dali.0kj1m.cn/Article/details/gtmyfnzhgr.html

[S43] C++：智能指针
来源：http://dali.xuetiantiany.cn/Article/details/gtbskydxyv.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhixingplan.top/Article/details/gtbrdqgxbh.html

[S44] C++：引用传参
来源：http://dali.feifeiyinyue.top/Article/details/gtiixhahwl.html

void inc(int &x) { ++x; }
来源：http://dali.fengsongda.top/Article/details/gtxjgejgzl.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gtfmgzjqfa.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.ydzc1.top/Article/details/gtkzoksgar.html

[S46] C++：函数模板
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjupzwomo.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.smart0.xyz/Article/details/gtykrehnxb.html

[S47] C++：结构化绑定遍历
来源：http://dali.yuxming.cn/Article/details/gtxzwjwpvi.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.daria6918.cn/Article/details/gtpnazkbzj.html

[S48] C++：逐行读文件
来源：http://dali.cqqwz.cn/Article/details/gtqvsqmbsl.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.chenlongwang.top/Article/details/gtbnkoepnw.html

while (std::getline(in, line)) { }
来源：http://dali.jinqigfzy.top/Article/details/gtewjkcdih.html

[S49] C++：写文件
来源：http://dali.hysaishi.cn/Article/details/gtefmdnnca.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.pengpengdd.cyou/Article/details/gtzrxfyyxz.html

[S50] C++：格式化数字
来源：http://dali.havefunace.top/Article/details/gtdhtzpmtd.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zycfv.cn/Article/details/gtpmrflesw.html

[S51] C++：显式类型转换
来源：http://dali.xuetiantiany.cn/Article/details/gthgghucfm.html

static_cast<double>(a) / b
来源：http://dali.hnqzz.top/Article/details/gtirkpbgom.html

[S52] C++：const 与 noexcept
来源：http://dali.pengpengdd.cyou/Article/details/gtmdzsjvhk.html

int size() const noexcept { return n_; }
来源：http://dali.svipenyu.cn/Article/details/gtmckkfcyw.html

[S53] C++：移动语义
来源：http://dali.snrcjt.cn/Article/details/gtozeivmeq.html

std::vector<int> w = std::move(v);
来源：http://dali.cdnleiting.top/Article/details/gtdvxhbiwc.html

[S54] C++：异常处理
来源：http://dali.wangdashe.top/Article/details/gttytknnvl.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.meibo888.top/Article/details/gtukwojxkw.html

[S55] C++：结构化绑定
来源：http://dali.cheryme.top/Article/details/gtgfkintul.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gtwjdcatll.html

[S56] C++：optional
来源：http://dali.316326.xyz/Article/details/gtknfosowc.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.guannengcc.top/Article/details/gtyzwurvsc.html

[S57] C++：编译期常量
来源：http://dali.birdmap.top/Article/details/gtyikfvhti.html

constexpr int N = 10;
来源：http://dali.daria6918.cn/Article/details/gtvfolgdah.html

[S58] C++：命名空间
来源：http://dali.shzxlz.cn/Article/details/gtufznlaqf.html

namespace ns { int f() { return 1; } }
来源：http://dali.daria6918.cn/Article/details/gtcgvwramq.html

[S59] C++：静态断言
来源：http://dali.tian-w.cn/Article/details/gtmbpbileg.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.sxryk.cn/Article/details/gtjtleqmcg.html

[S60] C++：遍历并删除元素
来源：http://dali.quarkkingdee.top/Article/details/gtoxlgefnv.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhongyouzk.top/Article/details/gthhrpncek.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtrugdyrem.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.svipenyu.cn/Article/details/gtbwwpglqv.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtnirsoahm.html

[T01] Kotlin：Hello World
来源：http://dali.ivvv.top/Article/details/gtgtegnjlx.html

println("Hello")
来源：http://dali.xziqi.cn/Article/details/gtmhxdqivk.html

[T02] Kotlin：变量
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiqhhsxzy.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.hnqzz.top/Article/details/gtkskugrkg.html

[T03] Kotlin：字符串模板
来源：http://dali.cashguo.top/Article/details/gthwsvsfln.html

"值: $b"
来源：http://dali.yj202588.top/Article/details/gtdpqvdvrl.html

[T04] Kotlin：空安全
来源：http://dali.jyoumei.cn/Article/details/gtlmxwdynd.html

val n: String? = null;  n?.length
来源：http://dali.birdmap.top/Article/details/gthphvvaqj.html

[T05] Kotlin：when 表达式
来源：http://dali.daria6918.cn/Article/details/gtafjobhxo.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.hongshengwenyu.top/Article/details/gtpaoojidd.html

[T06] Kotlin：集合映射
来源：http://dali.hongshengwenyu.top/Article/details/gtrsoiqrky.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.hywenlv.cn/Article/details/gtkmsgylvx.html

[T07] Kotlin：集合过滤
来源：http://dali.birdmap.top/Article/details/gtjcjpenli.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.yuanzhike.top/Article/details/gtgqbpgbmx.html

[T08] Kotlin：数据类
来源：http://dali.gotoacloud.top/Article/details/gtfhpcnmag.html

data class User(val name: String, val age: Int)
来源：http://dali.ivvv.top/Article/details/gtwrvrhdum.html

[T09] Kotlin：扩展函数
来源：http://dali.pengpengdd.cyou/Article/details/gtlflfclyh.html

fun String.exclaim() = this + "!"
来源：http://dali.vqdsnc.cn/Article/details/gtnubukees.html

[T10] Kotlin：默认参数
来源：http://dali.0kj1m.cn/Article/details/gtzpaxunoj.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.quarkkingdee.top/Article/details/gtwzmlznew.html

[T11] Kotlin：协程
来源：http://dali.mhx1999.top/Article/details/gtietdiunp.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.daxiang520.top/Article/details/gtiavhyrob.html

[T12] Kotlin：解构声明
来源：http://dali.chenjidiqi.icu/Article/details/gtwsvvrptd.html

val (a, b) = Pair(1, 2)
来源：http://dali.shanyushiyangtech.top/Article/details/gtcsbqlctv.html

[T13] Kotlin：只读 Map
来源：http://dali.gotoacloud.top/Article/details/gtsbxfckrd.html

val m = mapOf("a" to 1)
来源：http://dali.wangdashe.top/Article/details/gtsvldwvxs.html

[T14] Kotlin：循环
来源：http://dali.yuxming.cn/Article/details/gtlzuhbuqx.html

for (i in 1..10) println(i)
来源：http://dali.hnqzz.top/Article/details/gtzvsdcfsg.html

[T15] Kotlin：接口
来源：http://dali.meibo888.top/Article/details/gtezzhbgom.html

interface Shape { fun area(): Double }
来源：http://dali.hywenlv.cn/Article/details/gtklodlemj.html

[T16] Swift：Hello World
来源：http://dali.yuanzhike.top/Article/details/gtzsuytnrl.html

print("Hello")
来源：http://dali.hywenlv.cn/Article/details/gtmccarvjm.html

[T17] Swift：变量与常量
来源：http://dali.nanxuanxn.top/Article/details/gtcwwjacrk.html

var a = 1;  let b = 2
来源：http://dali.cqqwz.cn/Article/details/gtmqzmtcla.html

[T18] Swift：字符串插值
来源：http://dali.yanxiufei.cn/Article/details/gtdknugjvm.html

"值: \(b)"
来源：http://dali.nanxuanxn.top/Article/details/gtxoajpgip.html

[T19] Swift：可选绑定
来源：http://dali.zdqjudy.top/Article/details/gtqitprgcg.html

if let n = opt { print(n) }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtinqquiml.html

[T20] Swift：数组操作
来源：http://dali.sufxvd.cn/Article/details/gtprnsqiqn.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.meibo888.top/Article/details/gtebihotar.html

[T21] Swift：遍历
来源：http://dali.kuanghao11.cn/Article/details/gtutfuwzhr.html

for x in a { print(x) }
来源：http://dali.jiagoushi.top/Article/details/gtnbnstyew.html

[T22] Swift：字典
来源：http://dali.jyoumei.cn/Article/details/gtjxjcuygn.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.sysykeji.top/Article/details/gtjubfvtlf.html

[T23] Swift：函数
来源：http://dali.sxryk.cn/Article/details/gtiwxdnlyu.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.dashuyun.cn/Article/details/gtdssjjutn.html

[T24] Swift：闭包
来源：http://dali.ydzc1.top/Article/details/gttvhfwghb.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.pengpengdd.cyou/Article/details/gtnrekbyrq.html

[T25] Swift：结构体
来源：http://dali.feifeiyinyue.top/Article/details/gtkxgegjzw.html

struct P { var x: Int }
来源：http://dali.ehwqpu.com/Article/details/gtrwqtkhxe.html

[T26] Swift：类与重写
来源：http://dali.shanyushiyangtech.top/Article/details/gthmtabnix.html

class A: Base { override func f() {} }
来源：http://dali.ybcxt.top/Article/details/gturspftre.html

[T27] Swift：错误处理
来源：http://dali.jqgfzy.top/Article/details/gtyhnrrzgo.html

do { try f() } catch { print(error) }
来源：http://dali.yueranfly.top/Article/details/gtxipwzxij.html

[T28] Swift：枚举
来源：http://dali.c1oappe.top/Article/details/gtjgqsrqkl.html

enum Color { case red, green }
来源：http://dali.havefunace.top/Article/details/gthrpuibfa.html

[T29] Swift：guard 提前返回
来源：http://dali.shzxlz.cn/Article/details/gtujbmfxed.html

guard let x = opt else { return }
来源：http://dali.cucudq.cn/Article/details/gtcfcijgms.html

[T30] Swift：协议
来源：http://dali.quarkkingdee.top/Article/details/gtgmmfusmj.html

protocol Shape { func area() -> Double }
来源：http://dali.0kj1m.cn/Article/details/gtnfytqpay.html

[T31] Lua：Hello World
来源：http://dali.tianlin.xyz/Article/details/gthdsugxvf.html

print("Hello")
来源：http://dali.hnqzz.top/Article/details/gtmvktuioe.html

[T32] Lua：局部变量
来源：http://dali.jinqigufen.top/Article/details/gtobuldzrj.html

local a = 1
来源：http://dali.ivvv.top/Article/details/gtcjngffyw.html

[T33] Lua：表（数组）
来源：http://dali.jinqigufen.top/Article/details/gtnmizilor.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.meibo888.top/Article/details/gtjojsohuj.html

[T34] Lua：遍历表
来源：http://dali.pengpengdd.cyou/Article/details/gtvzhdbpvj.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlssbdppz.html

[T35] Lua：字典表
来源：http://dali.ybcxt.top/Article/details/gtmlqvfnii.html

local d = { a = 1 };  d.b = 2
来源：http://dali.daxiang520.top/Article/details/gtptvpmuyj.html

[T36] Lua：函数
来源：http://dali.daxiang520.top/Article/details/gtkbnwcnup.html

function add(a, b) return a + b end
来源：http://dali.chenjidiqi.icu/Article/details/gthbzelzdl.html

[T37] Lua：字符串拼接
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjhuqsneo.html

"a" .. "b"
来源：http://dali.nanxinkj.top/Article/details/gtuijexhys.html

[T38] Lua：条件
来源：http://dali.wangdashe.top/Article/details/gtjmfffkoa.html

if x > 0 then print("正") end
来源：http://dali.xinyue.icu/Article/details/gtrrhdxhkv.html

[T39] Lua：模式匹配
来源：http://dali.bjfxy.top/Article/details/gtwawqfjfa.html

string.find(s, "%d+")
来源：http://dali.sysykeji.top/Article/details/gtyppbeavc.html

[T40] Lua：元表
来源：http://dali.sxryk.cn/Article/details/gtoyvjpgbr.html

setmetatable({}, { __index = base })
来源：http://dali.9152youxi.cn/Article/details/gthlvcahxg.html

[T41] Perl：Hello World
来源：http://dali.fengsongda.top/Article/details/gttvdkxhvv.html

print "Hello\n";
来源：http://dali.mhx1999.top/Article/details/gtrtaqperx.html

[T42] Perl：变量类型
来源：http://dali.hammf.cn/Article/details/gtszmorimt.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgrfimsgw.html

[T43] Perl：字符串插值
来源：http://dali.cucudq.cn/Article/details/gtkamdmsjc.html

"值: $a"
来源：http://dali.yvedp.cn/Article/details/gtwfcabmgi.html

[T44] Perl：条件
来源：http://dali.sxryk.cn/Article/details/gtqwttgsfk.html

if ($a > 0) { print "正"; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiqodtogd.html

[T45] Perl：数组遍历
来源：http://dali.ppjwa.cn/Article/details/gtjofnboix.html

for my $x (@arr) { print $x; }
来源：http://dali.gogol.net.cn/Article/details/gtflnfvckc.html

[T46] Perl：哈希操作
来源：http://dali.ehwqpu.com/Article/details/gtiagywouz.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.yueranfly.top/Article/details/gtzlatasje.html

[T47] Perl：正则捕获
来源：http://dali.yj20258.top/Article/details/gtnsshsriy.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.tianlin.xyz/Article/details/gthybeccjf.html

[T48] Perl：正则替换
来源：http://dali.fzhhl.top/Article/details/gtzzlpttgk.html

$s =~ s/old/new/g;
来源：http://dali.quarkkingdee.top/Article/details/gthtqwbmts.html

[T49] Perl：函数
来源：http://dali.tian-w.cn/Article/details/gtevbgucvr.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.xziqi.cn/Article/details/gtdpntaruu.html

[T50] Perl：逐行读文件
来源：http://dali.mhx1999.top/Article/details/gthxirlsvz.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.wangdashe.top/Article/details/gtlhswnhss.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.jqgfzy.top/Article/details/gtougnbtjo.html

[T51] Scala：Hello World
来源：http://dali.hnxiangtu.top/Article/details/gtnvrbybrr.html

println("Hello")
来源：http://dali.shangyingyoupin.top/Article/details/gtnkcsxsat.html

[T52] Scala：变量
来源：http://dali.yuxming.cn/Article/details/gtdiezaqwy.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gtkzrrymzj.html

[T53] Scala：字符串插值
来源：http://dali.zhoulong.xyz/Article/details/gtlvzdmiux.html

s"值: $b"
来源：http://dali.zhiwuduotai.top/Article/details/gtrnnqovgt.html

[T54] Scala：集合映射
来源：http://dali.shanyushiyangtech.top/Article/details/gtxixcqlyz.html


<!-- 参考信息 -->