代发 wailian999

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zdqjudy.top/Article/details/gtrmwwucqc.html

[R52] 统计行数
来源：http://dali.zhengqikj.top/Article/details/gtsqiltkbq.html

wc -l a.txt
来源：http://dali.redwolf501.top/Article/details/gtyajuberw.html

[R53] 查看文件头与实时尾
来源：http://dali.jinqigufen.top/Article/details/gthtwphijv.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.tianlin.xyz/Article/details/gtiwgvwtip.html

[R54] 比较两个文件
来源：http://dali.xinyue.icu/Article/details/gtuptrehzy.html

diff a.txt b.txt
来源：http://dali.guannengcc.top/Article/details/gtcbjcaguw.html

[R55] 压缩与解压
来源：http://dali.9152youxi.cn/Article/details/gtaiktfgtc.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.iojbl.cn/Article/details/gtsbajazmo.html

[R56] 远程拷贝
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpqzdqfdq.html

scp file user@host:/path/
来源：http://dali.yj202588.top/Article/details/gtcrzsdnla.html

[R57] 远程执行命令
来源：http://dali.ydzc1.top/Article/details/gtgzbqxjpt.html

ssh user@host 'uptime'
来源：http://dali.zhengqikj.top/Article/details/gtrjomkahz.html

[R58] 下载文件
来源：http://dali.9152youxi.cn/Article/details/gtjfuascqu.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.yj20258888.top/Article/details/gtaumrxbfd.html

[R59] 发 POST JSON
来源：http://dali.wangdashe.top/Article/details/gtalxgzreh.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.nanxuanxn.top/Article/details/gtthlafdgj.html

[R60] 只看 HTTP 状态码
来源：http://dali.redwolf501.top/Article/details/gtzerlyidi.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.9152youxi.cn/Article/details/gttrqcyqxo.html

[R61] 磁盘占用
来源：http://dali.snrcjt.cn/Article/details/gtyynpaiab.html

df -h;  du -sh *
来源：http://dali.xuetiantiany.cn/Article/details/gtqdaauqbm.html

[R62] 找最占空间的文件
来源：http://dali.nanxinkj.top/Article/details/gtfwofekjq.html

du -ah . | sort -rh | head -10
来源：http://dali.gaohongyu789.top/Article/details/gtuqllfukj.html

[R63] 内存与进程
来源：http://dali.jqgfzy.top/Article/details/gtrejeactn.html

free -h;  ps aux | grep nginx
来源：http://dali.shanyushiyangtech.top/Article/details/gtjgmwlnbj.html

[R64] 结束进程
来源：http://dali.0kj1m.cn/Article/details/gtustfpyml.html

kill -9 $(pgrep -f app.py)
来源：http://dali.gotoacloud.top/Article/details/gtstynkxoz.html

[R65] 查看端口占用
来源：http://dali.tanke756.top/Article/details/gtfeiyimnn.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.ybcxt.top/Article/details/gtvqkmenwj.html

[R66] 定时任务
来源：http://dali.xziqi.cn/Article/details/gtvpycltzk.html

crontab -e;  crontab -l
来源：http://dali.9152youxi.cn/Article/details/gteyoetfdl.html

[R67] 生成随机十六进制串
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyavfncix.html

openssl rand -hex 16
来源：http://dali.zdqjudy.top/Article/details/gttvldkuup.html

[R68] 计算文件校验值
来源：http://dali.zhiwuduotai.top/Article/details/gtznurdnzt.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.chenlongwang.top/Article/details/gtjdewfrxr.html

[R69] 生成随机密码
来源：http://dali.zhoulong.xyz/Article/details/gtleuomgpy.html

head -c 16 /dev/urandom | base64
来源：http://dali.hammf.cn/Article/details/gttdbrmxqb.html

[R70] 时间戳与互转
来源：http://dali.gogol.net.cn/Article/details/gtgrxoyevt.html

date +%s;  date -d @1700000000
来源：http://dali.shanyushiyangkeji.top/Article/details/gttksqjnkb.html

[R71] 日期格式化
来源：http://dali.sysykeji.top/Article/details/gtsrtqnpcs.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtinqikiqn.html

[R72] 等待端口就绪
来源：http://dali.havefunace.top/Article/details/gtttldpcsu.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.xuanzx.com/Article/details/gteqfaimjl.html

[R73] 分割大日志
来源：http://dali.cqqwz.cn/Article/details/gtdoniqqxx.html

split -l 1000 big.log part_
来源：http://dali.tanke756.top/Article/details/gtifqtucum.html

[R74] 批量重命名
来源：http://dali.shuidangran.top/Article/details/gtxrvpsgkc.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gtbcjlfbpn.html

[R75] 导出环境变量
来源：http://dali.zhengqikj.top/Article/details/gtkktoonmk.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.daria6918.cn/Article/details/gtnfhnwlbf.html

[R76] 使用临时文件
来源：http://dali.xylfe.cn/Article/details/gtgjakyvwh.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.hammf.cn/Article/details/gtcuxwsgsc.html

[R77] 读取用户输入
来源：http://dali.fengsongda.top/Article/details/gtyalcjucg.html

read -rp "请输入: " ans
来源：http://dali.mhx1999.top/Article/details/gtzncdoghy.html

[R78] 交互式菜单
来源：http://dali.zdqjudy.top/Article/details/gtpsbjdpzh.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.yonumen.top/Article/details/gtgfihakyr.html

[R79] 解析命令行选项
来源：http://dali.hammf.cn/Article/details/gtzgviagrk.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.birdmap.top/Article/details/gtzsdbernj.html

[R80] 查看脚本执行耗时
来源：http://dali.sufxvd.cn/Article/details/gtmhwmemsp.html

time ./run.sh
来源：http://dali.svipenyu.cn/Article/details/gtvpofnpro.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gttgttfzph.html

S. C / C++ 专题
来源：http://dali.redwolf501.top/Article/details/gtnpnljjhz.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gteggnegrb.html

[S01] C：Hello World
来源：http://dali.zycfv.cn/Article/details/gteizvubgt.html

#include <stdio.h>
来源：http://dali.zhixingplan.top/Article/details/gtcsgrpyns.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.yuxming.cn/Article/details/gtjezpieth.html

[S02] C：变量与格式化输出
来源：http://dali.0kj1m.cn/Article/details/gtourbukgx.html

int a = 10; printf("%d\n", a);
来源：http://dali.havefunace.top/Article/details/gtabplzhsq.html

[S03] C：读入整数
来源：http://dali.tian-w.cn/Article/details/gtcewagtxq.html

int x; scanf("%d", &x);
来源：http://dali.sxryk.cn/Article/details/gtvkfcsjev.html

[S04] C：字符串复制
来源：http://dali.aizwys.cn/Article/details/gtzjogykdf.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhiwuduotai.top/Article/details/gtectjspoe.html

[S05] C：字符串长度
来源：http://dali.birdmap.top/Article/details/gtsualagyb.html

strlen(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfmllzbjt.html

[S06] C：字符串比较
来源：http://dali.svipenyu.cn/Article/details/gtbvlebsbg.html

strcmp(a, b) == 0
来源：http://dali.gogol.net.cn/Article/details/gtpaktdcoq.html

[S07] C：数组遍历求和
来源：http://dali.ybcxt.top/Article/details/gtxiarfaqc.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.yangfankeji.com/Article/details/gtspcbccii.html

[S08] C：动态内存分配与释放
来源：http://dali.jqgfzy.top/Article/details/gthzfevegm.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.xuetiantiany.cn/Article/details/gtyiywjdhw.html

[S09] C：结构体定义与初始化
来源：http://dali.xziqi.cn/Article/details/gtnwabompr.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.ydzc1.top/Article/details/gtfiaedvqk.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gtexuiqtjq.html

int *p = &a;  *p = 5;
来源：http://dali.daxiang520.top/Article/details/gterfuorlt.html

[S11] C：逐行读文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gttfhpzsoe.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.cqqwz.cn/Article/details/gthtabtzfs.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.xylfe.cn/Article/details/gtfelxfdjl.html

fclose(f);
来源：http://dali.pycfn.com/Article/details/gtoolhklrw.html

[S12] C：写文件
来源：http://dali.dianchejie.cn/Article/details/gtkbixixrf.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.tianlin.xyz/Article/details/gtudowitjy.html

[S13] C：宏定义
来源：http://dali.yueranfly.top/Article/details/gtehfgawrp.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.birdmap.top/Article/details/gtntllzqay.html

[S14] C：枚举
来源：http://dali.guowangkeji.top/Article/details/gtfsakmgmq.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.chenjidiqi.icu/Article/details/gtuhmgymft.html

[S15] C：类型转换
来源：http://dali.yuanzhike.top/Article/details/gtyuacbtth.html

(double) a / b
来源：http://dali.cheryme.top/Article/details/gtajyyrftn.html

[S16] C：位操作置位
来源：http://dali.xuanzx.com/Article/details/gtbqlmewrr.html

x |= (1 << 3);
来源：http://dali.xuanzx.com/Article/details/gtzbdkaeth.html

[S17] C：安全拼接字符串
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsnfdfixm.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.jqgfzy.top/Article/details/gtnlfxctoz.html

[S18] C：命令行参数
来源：http://dali.kuanghao11.cn/Article/details/gtxzcqbutp.html

int main(int argc, char **argv)
来源：http://dali.tian-w.cn/Article/details/gtxeknuzbr.html

[S19] C：快速排序
来源：http://dali.jyoumei.cn/Article/details/gtxpypfmye.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.jlsjyb.cn/Article/details/gtnwwsptcl.html

[S20] C：二分查找
来源：http://dali.kuanghao11.cn/Article/details/gtoyhdpjsk.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.jinqigufen.top/Article/details/gtujqhglyy.html

[S21] C：字符类别判断
来源：http://dali.shzxlz.cn/Article/details/gtpvvewdly.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.aizwys.cn/Article/details/gtcsiqhfzj.html

[S22] C：字符串转数字
来源：http://dali.zhixingplan.top/Article/details/gtogcbadua.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.jiagoushi.top/Article/details/gtxitdhedo.html

[S23] C：随机数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtohwcybvj.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhixingplan.top/Article/details/gthdtmcbvz.html

[S24] C：获取本地时间
来源：http://dali.yj20258888.top/Article/details/gtqvmzvqxa.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.daria6918.cn/Article/details/gtgiejjwws.html

[S25] C：内存拷贝
来源：http://dali.jyoumei.cn/Article/details/gtezrucvue.html

memcpy(dst, src, n);
来源：http://dali.shangyingyoupin.top/Article/details/gtxyjyvhlr.html

[S26] C：内存清零
来源：http://dali.shuidangran.top/Article/details/gtfpawyyhw.html

memset(a, 0, sizeof a);
来源：http://dali.yj202588.top/Article/details/gtcisztgwh.html

[S27] C：定义常量
来源：http://dali.feifeiyinyue.top/Article/details/gtjxrlknhq.html

const double PI = 3.14159;
来源：http://dali.guowangkeji.top/Article/details/gteergfkvu.html

[S28] C：静态变量
来源：http://dali.ppjwa.cn/Article/details/gtvsdjsswp.html

static int counter = 0;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbccgramu.html

[S29] C：变参函数
来源：http://dali.jinqigufen.top/Article/details/gtwspulgzr.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhixingplan.top/Article/details/gtzfpsrtjf.html

[S30] C：头文件保护
来源：http://dali.cucudq.cn/Article/details/gtmitpoijk.html

#ifndef X_H
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkejtogvn.html

#define X_H
来源：http://dali.daria6918.cn/Article/details/gtgryycwec.html

#endif
来源：http://dali.ehwqpu.com/Article/details/gtqmjnqcwm.html

[S31] C++：Hello World
来源：http://dali.ehwqpu.com/Article/details/gtoocuqvds.html

#include <iostream>
来源：http://dali.316326.xyz/Article/details/gtjrhwomxr.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.chenjidiqi.icu/Article/details/gteswusxul.html

[S32] C++：字符串
来源：http://dali.zhoulong.xyz/Article/details/gtctrorabt.html

std::string s = "hi";  s += "!";
来源：http://dali.pengpengdd.cyou/Article/details/gtjpyznule.html

[S33] C++：vector 增删
来源：http://dali.mhx1999.top/Article/details/gtbdyszehj.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.mhx1999.top/Article/details/gtpmtdtlfq.html

[S34] C++：遍历 vector
来源：http://dali.chenjidiqi.icu/Article/details/gtuqmftrwp.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.yongpay.top/Article/details/gtyttchdjz.html

[S35] C++：map
来源：http://dali.pycfn.com/Article/details/gtrbteinjn.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.svipenyu.cn/Article/details/gthfvvozyc.html

[S36] C++：unordered_map
来源：http://dali.zhiwuduotai.top/Article/details/gtdvinbvpa.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.wangshuangyany.cn/Article/details/gttsqcdkmh.html

[S37] C++：set
来源：http://dali.316326.xyz/Article/details/gtmgbjacox.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.havefunace.top/Article/details/gtxccdnlxo.html

[S38] C++：排序
来源：http://dali.iojbl.cn/Article/details/gtokvqwhnu.html

std::sort(v.begin(), v.end());
来源：http://dali.jinghuilouyu.cn/Article/details/gtxxzehxld.html

[S39] C++：自定义比较器排序
来源：http://dali.mhx1999.top/Article/details/gtauijfysk.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.yueranfly.top/Article/details/gtmjczydlj.html

[S40] C++：查找元素
来源：http://dali.ydzc1.top/Article/details/gtymxpcane.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.snrcjt.cn/Article/details/gtyqhokrsg.html

[S41] C++：类与构造函数
来源：http://dali.zycfv.cn/Article/details/gtrmnlpbti.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.snrcjt.cn/Article/details/gtiekabhkj.html

[S42] C++：继承与虚函数
来源：http://dali.fengsongda.top/Article/details/gtxsgzdfil.html

class B : public Base { public: void f() override {} };
来源：http://dali.yueranfly.top/Article/details/gtegkktyeq.html

[S43] C++：智能指针
来源：http://dali.yj202588.top/Article/details/gtqradtyzo.html

auto p = std::make_unique<int>(5);
来源：http://dali.0kj1m.cn/Article/details/gtzugjjduy.html

[S44] C++：引用传参
来源：http://dali.yanxiufei.cn/Article/details/gtsvextgte.html

void inc(int &x) { ++x; }
来源：http://dali.yj20258888.top/Article/details/gtdscanxny.html

[S45] C++：lambda
来源：http://dali.cashguo.top/Article/details/gtakipzvwj.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhoulong.xyz/Article/details/gtlumsabhd.html

[S46] C++：函数模板
来源：http://dali.daria6918.cn/Article/details/gthvcttnxk.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.shangyingyoupin.top/Article/details/gtvouuggku.html

[S47] C++：结构化绑定遍历
来源：http://dali.shuidangran.top/Article/details/gtaeefqkel.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.sysykeji.top/Article/details/gthflwzndc.html

[S48] C++：逐行读文件
来源：http://dali.chenjidiqi.icu/Article/details/gtbydilonb.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.redwolf501.top/Article/details/gtyiwqhkwh.html

while (std::getline(in, line)) { }
来源：http://dali.jinghuilouyu.cn/Article/details/gturrnsake.html

[S49] C++：写文件
来源：http://dali.jinqigufen.top/Article/details/gttzpzetvq.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.jinghuilouyu.cn/Article/details/gtatwujryu.html

[S50] C++：格式化数字
来源：http://dali.daria6918.cn/Article/details/gtwnrgxagf.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.shanyushiyangtech.top/Article/details/gtwsnzykyt.html

[S51] C++：显式类型转换
来源：http://dali.aizwys.cn/Article/details/gtitkbnvod.html

static_cast<double>(a) / b
来源：http://dali.zhoulong.xyz/Article/details/gtvpdwnnqo.html

[S52] C++：const 与 noexcept
来源：http://dali.jinqigufen.top/Article/details/gtgstlozcd.html

int size() const noexcept { return n_; }
来源：http://dali.andypj.xyz/Article/details/gtrgdaojjn.html

[S53] C++：移动语义
来源：http://dali.havefunace.top/Article/details/gtltzsribz.html

std::vector<int> w = std::move(v);
来源：http://dali.dashuyun.cn/Article/details/gtkkvwgglx.html

[S54] C++：异常处理
来源：http://dali.zhongyouzk.top/Article/details/gtfdgwhyyg.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.cqqwz.cn/Article/details/gtjsfafwkt.html

[S55] C++：结构化绑定
来源：http://dali.ybcxt.top/Article/details/gtezlfbrhw.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gtyflegwbq.html

[S56] C++：optional
来源：http://dali.guowangkeji.top/Article/details/gtyzxcrozq.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhoulong.xyz/Article/details/gthljkigoy.html

[S57] C++：编译期常量
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrwqndlsm.html

constexpr int N = 10;
来源：http://dali.sysykeji.top/Article/details/gtplofmsiv.html

[S58] C++：命名空间
来源：http://dali.zhiwuduotai.top/Article/details/gttzrcnfbb.html

namespace ns { int f() { return 1; } }
来源：http://dali.hongshengwenyu.top/Article/details/gtockyyyos.html

[S59] C++：静态断言
来源：http://dali.cheryme.top/Article/details/gtzdfcbxqa.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.jqgfzy.top/Article/details/gtsuvuowyo.html

[S60] C++：遍历并删除元素
来源：http://dali.dianchejie.cn/Article/details/gtnjqijgvw.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.havefunace.top/Article/details/gtefgxkeex.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gticmxqnhv.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.hammf.cn/Article/details/gtpijdlknc.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzzsyxhrw.html

[T01] Kotlin：Hello World
来源：http://dali.gogol.net.cn/Article/details/gtudcphqir.html

println("Hello")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfflephpy.html

[T02] Kotlin：变量
来源：http://dali.yongpay.top/Article/details/gtfcgdkyea.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.vqdsnc.cn/Article/details/gtwtneheup.html

[T03] Kotlin：字符串模板
来源：http://dali.haohaochexian.top/Article/details/gtkxthwpti.html

"值: $b"
来源：http://dali.jiagoushi.top/Article/details/gtrfsseiep.html

[T04] Kotlin：空安全
来源：http://dali.gogol.net.cn/Article/details/gtmiewkmnw.html

val n: String? = null;  n?.length
来源：http://dali.zycfv.cn/Article/details/gtsuomdzuc.html

[T05] Kotlin：when 表达式
来源：http://dali.birdmap.top/Article/details/gtbzykbngf.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.hnxiangtu.top/Article/details/gtgrdatbms.html

[T06] Kotlin：集合映射
来源：http://dali.guannengcc.top/Article/details/gtqmevvvlw.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.yanxiufei.cn/Article/details/gtqahkyoez.html

[T07] Kotlin：集合过滤
来源：http://dali.snrcjt.cn/Article/details/gtfygjetoy.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.cqqwz.cn/Article/details/gtltardlrj.html

[T08] Kotlin：数据类
来源：http://dali.svipenyu.cn/Article/details/gtqotlvirt.html

data class User(val name: String, val age: Int)
来源：http://dali.shanyushiyangtech.top/Article/details/gttcxwuxtg.html

[T09] Kotlin：扩展函数
来源：http://dali.zhengqikj.top/Article/details/gthmlqtrek.html

fun String.exclaim() = this + "!"
来源：http://dali.dashuyun.cn/Article/details/gtrgwcuygf.html

[T10] Kotlin：默认参数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuwynzijb.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.iojbl.cn/Article/details/gtyjerjdzg.html

[T11] Kotlin：协程
来源：http://dali.shangyingyoupin.top/Article/details/gtdgsqgzkm.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdfmtmavy.html

[T12] Kotlin：解构声明
来源：http://dali.daria6918.cn/Article/details/gtuubckjjs.html

val (a, b) = Pair(1, 2)
来源：http://dali.hnxiangtu.top/Article/details/gtxgrrgwrq.html

[T13] Kotlin：只读 Map
来源：http://dali.ehwqpu.com/Article/details/gtrhxmagyb.html

val m = mapOf("a" to 1)
来源：http://dali.havefunace.top/Article/details/gtyzlejspk.html

[T14] Kotlin：循环
来源：http://dali.snrcjt.cn/Article/details/gtkkseayom.html

for (i in 1..10) println(i)
来源：http://dali.dashuyun.cn/Article/details/gtvkxqbybh.html

[T15] Kotlin：接口
来源：http://dali.jlsjyb.cn/Article/details/gtkkvfyxop.html

interface Shape { fun area(): Double }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwjmynimu.html

[T16] Swift：Hello World
来源：http://dali.cdnleiting.top/Article/details/gtglcelios.html

print("Hello")
来源：http://dali.zhiwuduotai.top/Article/details/gtodgstzga.html

[T17] Swift：变量与常量
来源：http://dali.dianchejie.cn/Article/details/gtyiadpsnt.html

var a = 1;  let b = 2
来源：http://dali.vqdsnc.cn/Article/details/gtrnnjywgx.html

[T18] Swift：字符串插值
来源：http://dali.yuxming.cn/Article/details/gtmmbuvbms.html

"值: \(b)"
来源：http://dali.birdmap.top/Article/details/gtalnbricl.html

[T19] Swift：可选绑定
来源：http://dali.guowangkeji.top/Article/details/gtqihlhbwi.html

if let n = opt { print(n) }
来源：http://dali.yueranfly.top/Article/details/gthgpgcrmb.html

[T20] Swift：数组操作
来源：http://dali.hongshengwenyu.top/Article/details/gtcidkvlvn.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.pycfn.com/Article/details/gtrudmqgbr.html

[T21] Swift：遍历
来源：http://dali.hfpthk.cn/Article/details/gtmxqpytmx.html

for x in a { print(x) }
来源：http://dali.quarkkingdee.top/Article/details/gtlvkuktng.html

[T22] Swift：字典
来源：http://dali.ivvv.top/Article/details/gtccknmuis.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhoulong.xyz/Article/details/gtfqmltmdo.html

[T23] Swift：函数
来源：http://dali.sweek.top/Article/details/gtgxajjstn.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.kuanghao11.cn/Article/details/gtvtmtyeyf.html

[T24] Swift：闭包
来源：http://dali.yj20258888.top/Article/details/gtftlsaidw.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.yuanzhike.top/Article/details/gtunpocbzv.html

[T25] Swift：结构体
来源：http://dali.jqgufenzy.top/Article/details/gtoxmtdctj.html

struct P { var x: Int }
来源：http://dali.birdmap.top/Article/details/gtkqskzljo.html

[T26] Swift：类与重写
来源：http://dali.zhongyouzk.top/Article/details/gtcpimiaeu.html

class A: Base { override func f() {} }
来源：http://dali.daxiang520.top/Article/details/gtjdturprs.html

[T27] Swift：错误处理
来源：http://dali.jqgfzy.top/Article/details/gtnkijuljq.html

do { try f() } catch { print(error) }
来源：http://dali.fzhhl.top/Article/details/gttxvzczxx.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gtfzptqiqg.html

enum Color { case red, green }
来源：http://dali.dianchejie.cn/Article/details/gtvnjtkhqh.html

[T29] Swift：guard 提前返回
来源：http://dali.jqgufenzy.top/Article/details/gtrbofqsed.html

guard let x = opt else { return }
来源：http://dali.wangshuangyany.cn/Article/details/gtsilzmhnk.html

[T30] Swift：协议
来源：http://dali.kuanghao11.cn/Article/details/gtrohsmkgu.html

protocol Shape { func area() -> Double }
来源：http://dali.chenzaomai.com/Article/details/gtkbyugpdq.html

[T31] Lua：Hello World
来源：http://dali.hammf.cn/Article/details/gtsyycldkq.html

print("Hello")
来源：http://dali.jianghu66.top/Article/details/gtzrqrjgsl.html

[T32] Lua：局部变量
来源：http://dali.daxiang520.top/Article/details/gtlfsxbtgt.html

local a = 1
来源：http://dali.daria6918.cn/Article/details/gtqpxcwyhf.html

[T33] Lua：表（数组）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmalcgckh.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.0kj1m.cn/Article/details/gtmvlxcrdk.html

[T34] Lua：遍历表
来源：http://dali.chenzaomai.com/Article/details/gtpvnqnsjs.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.chenjidiqi.icu/Article/details/gtydefxdhq.html

[T35] Lua：字典表
来源：http://dali.0kj1m.cn/Article/details/gtxnufucsn.html

local d = { a = 1 };  d.b = 2
来源：http://dali.shangyingyoupin.top/Article/details/gtxgcnwswk.html

[T36] Lua：函数
来源：http://dali.nanxuanxn.top/Article/details/gtzgywaega.html

function add(a, b) return a + b end
来源：http://dali.hnxiangtu.top/Article/details/gtaopwygjt.html

[T37] Lua：字符串拼接
来源：http://dali.yj20258.top/Article/details/gtmaewwrfw.html

"a" .. "b"
来源：http://dali.jiagoushi.top/Article/details/gtoaterprc.html

[T38] Lua：条件
来源：http://dali.birdmap.top/Article/details/gtvphpkjjy.html

if x > 0 then print("正") end
来源：http://dali.snrcjt.cn/Article/details/gtnqjdfizp.html

[T39] Lua：模式匹配
来源：http://dali.gogol.net.cn/Article/details/gtfsbydqtw.html

string.find(s, "%d+")
来源：http://dali.yvedp.cn/Article/details/gthjfmltnw.html

[T40] Lua：元表
来源：http://dali.haohaochexian.top/Article/details/gtbqhcpjmc.html

setmetatable({}, { __index = base })
来源：http://dali.jinghuilouyu.cn/Article/details/gtftbjrpro.html

[T41] Perl：Hello World
来源：http://dali.zycfv.cn/Article/details/gtwhndfnlg.html

print "Hello\n";
来源：http://dali.tanke756.top/Article/details/gtsldeuvbg.html

[T42] Perl：变量类型
来源：http://dali.andypj.xyz/Article/details/gtqomukmom.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.ybcxt.top/Article/details/gtuqjyriex.html

[T43] Perl：字符串插值
来源：http://dali.pycfn.com/Article/details/gtwryjbdhk.html

"值: $a"
来源：http://dali.shuidangran.top/Article/details/gtniisncql.html

[T44] Perl：条件
来源：http://dali.xziqi.cn/Article/details/gtfxwfktwp.html

if ($a > 0) { print "正"; }
来源：http://dali.chenlongwang.top/Article/details/gtcihptkdb.html

[T45] Perl：数组遍历
来源：http://dali.snrcjt.cn/Article/details/gtpfcvtkbd.html

for my $x (@arr) { print $x; }
来源：http://dali.xylfe.cn/Article/details/gtfskrnadw.html

[T46] Perl：哈希操作
来源：http://dali.jiagoushi.top/Article/details/gtsuwiezxy.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.tanke756.top/Article/details/gtjhiduufx.html

[T47] Perl：正则捕获
来源：http://dali.nanxinkj.top/Article/details/gtfsyaryan.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zdqjudy.top/Article/details/gtguzmathw.html

[T48] Perl：正则替换
来源：http://dali.xziqi.cn/Article/details/gtqyrodean.html

$s =~ s/old/new/g;
来源：http://dali.ybcxt.top/Article/details/gtfgxhssgh.html

[T49] Perl：函数
来源：http://dali.quarkkingdee.top/Article/details/gtoscicses.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.andypj.xyz/Article/details/gtiuupzzlf.html

[T50] Perl：逐行读文件
来源：http://dali.xinyue.icu/Article/details/gtdrykibae.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.birdmap.top/Article/details/gtoaafncgo.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.gotoacloud.top/Article/details/gtnkoiphin.html

[T51] Scala：Hello World
来源：http://dali.jlsjyb.cn/Article/details/gtifknteso.html

println("Hello")
来源：http://dali.316326.xyz/Article/details/gteneircrv.html

[T52] Scala：变量
来源：http://dali.jinqigfzy.top/Article/details/gtfgwjkmad.html

val a = 1;  var b = 2
来源：http://dali.jinqigfzy.top/Article/details/gtgdegsacd.html

[T53] Scala：字符串插值
来源：http://dali.hongshengwenyu.top/Article/details/gtiudyggcv.html

s"值: $b"
来源：http://dali.fengsongda.top/Article/details/gttncqrubx.html

[T54] Scala：集合映射
来源：http://dali.hywenlv.cn/Article/details/gtuujdifsf.html


<!-- 参考信息 -->