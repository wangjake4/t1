代发 wailian999

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.hammf.cn/Article/details/gtapweosab.html

[R52] 统计行数
来源：http://dali.yongpay.top/Article/details/gteivfjaqi.html

wc -l a.txt
来源：http://dali.yonumen.top/Article/details/gtldhblgkj.html

[R53] 查看文件头与实时尾
来源：http://dali.dashuyun.cn/Article/details/gtbbsmaixz.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.jinqigfzy.top/Article/details/gtudzypbuw.html

[R54] 比较两个文件
来源：http://dali.ppjwa.cn/Article/details/gtiiakovhj.html

diff a.txt b.txt
来源：http://dali.shuidangran.top/Article/details/gtsosyedlf.html

[R55] 压缩与解压
来源：http://dali.gogol.net.cn/Article/details/gtohlptwty.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.shzxlz.cn/Article/details/gtcdyuveyw.html

[R56] 远程拷贝
来源：http://dali.yuxming.cn/Article/details/gtkxggardu.html

scp file user@host:/path/
来源：http://dali.bjfxy.top/Article/details/gtgbuvpvti.html

[R57] 远程执行命令
来源：http://dali.hnqzz.top/Article/details/gtstsruonw.html

ssh user@host 'uptime'
来源：http://dali.xuetiantiany.cn/Article/details/gtgvzpysdn.html

[R58] 下载文件
来源：http://dali.xuetiantiany.cn/Article/details/gtyijpnaau.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.hfpthk.cn/Article/details/gtlxjeghcg.html

[R59] 发 POST JSON
来源：http://dali.jinqigfzy.top/Article/details/gtdbixunwx.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkjitiqln.html

[R60] 只看 HTTP 状态码
来源：http://dali.ehwqpu.com/Article/details/gtjszswspy.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.fzhhl.top/Article/details/gtsrvcbamv.html

[R61] 磁盘占用
来源：http://dali.ivvv.top/Article/details/gtjzwwhenk.html

df -h;  du -sh *
来源：http://dali.yj202588.top/Article/details/gtczmizjpl.html

[R62] 找最占空间的文件
来源：http://dali.wangshuangyany.cn/Article/details/gtmdifpsuk.html

du -ah . | sort -rh | head -10
来源：http://dali.jinqigufen.top/Article/details/gtmxeiuvmm.html

[R63] 内存与进程
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttgmjowlm.html

free -h;  ps aux | grep nginx
来源：http://dali.zdqjudy.top/Article/details/gtnqdxpzrg.html

[R64] 结束进程
来源：http://dali.nanxuanxn.top/Article/details/gtzfdizirj.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhengqikj.top/Article/details/gtnhlwhagb.html

[R65] 查看端口占用
来源：http://dali.0kj1m.cn/Article/details/gtqrzmkuli.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.xuanzx.com/Article/details/gtxpskzcwi.html

[R66] 定时任务
来源：http://dali.ppjwa.cn/Article/details/gtvgfaqkfv.html

crontab -e;  crontab -l
来源：http://dali.haohaochexian.top/Article/details/gtrkrmbbht.html

[R67] 生成随机十六进制串
来源：http://dali.shuidangran.top/Article/details/gtmhdxyxqu.html

openssl rand -hex 16
来源：http://dali.shanyushiyangtech.top/Article/details/gtxhqdutgs.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gttetyqexs.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.cashguo.top/Article/details/gtimsakjnl.html

[R69] 生成随机密码
来源：http://dali.hongshengwenyu.top/Article/details/gtvbxadppb.html

head -c 16 /dev/urandom | base64
来源：http://dali.dashuyun.cn/Article/details/gtfsgvrypr.html

[R70] 时间戳与互转
来源：http://dali.tanke756.top/Article/details/gtvluaulip.html

date +%s;  date -d @1700000000
来源：http://dali.daria6918.cn/Article/details/gtjqmkymfi.html

[R71] 日期格式化
来源：http://dali.shzxlz.cn/Article/details/gthzooisha.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.bjfxy.top/Article/details/gtckpimoxj.html

[R72] 等待端口就绪
来源：http://dali.hywenlv.cn/Article/details/gtpfojkykd.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.mhx1999.top/Article/details/gtoftqszns.html

[R73] 分割大日志
来源：http://dali.cucudq.cn/Article/details/gtmtedspju.html

split -l 1000 big.log part_
来源：http://dali.xuetiantiany.cn/Article/details/gthylsjzyc.html

[R74] 批量重命名
来源：http://dali.xuetiantiany.cn/Article/details/gtbrolfqdy.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.yj20258888.top/Article/details/gtcweltxng.html

[R75] 导出环境变量
来源：http://dali.jlsjyb.cn/Article/details/gtdhdwarfh.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhongyouzk.top/Article/details/gtsvywwype.html

[R76] 使用临时文件
来源：http://dali.wangshuangyany.cn/Article/details/gtbwepsjxq.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.jiagoushi.top/Article/details/gtbkfkrrnl.html

[R77] 读取用户输入
来源：http://dali.ppjwa.cn/Article/details/gtcnqjrhnu.html

read -rp "请输入: " ans
来源：http://dali.zhengqikj.top/Article/details/gtjjiyzdzb.html

[R78] 交互式菜单
来源：http://dali.hnqzz.top/Article/details/gtjxnzsegl.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.gogol.net.cn/Article/details/gtqcknwwtq.html

[R79] 解析命令行选项
来源：http://dali.yuanzhike.top/Article/details/gtbicudlua.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.cqqwz.cn/Article/details/gtopapcjzz.html

[R80] 查看脚本执行耗时
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgbjnehfd.html

time ./run.sh
来源：http://dali.daria6918.cn/Article/details/gtldchxump.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtebcfxvjf.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gtdepmzpmd.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtwhhnohiw.html

[S01] C：Hello World
来源：http://dali.yj202588.top/Article/details/gtbcftooto.html

#include <stdio.h>
来源：http://dali.hysaishi.cn/Article/details/gtqmhxpirh.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.shangyingyoupin.top/Article/details/gtznidnsle.html

[S02] C：变量与格式化输出
来源：http://dali.cdnleiting.top/Article/details/gtqjfqwysh.html

int a = 10; printf("%d\n", a);
来源：http://dali.shuidangran.top/Article/details/gtfzlvfgqh.html

[S03] C：读入整数
来源：http://dali.yvedp.cn/Article/details/gtsfsevvvl.html

int x; scanf("%d", &x);
来源：http://dali.haohaochexian.top/Article/details/gtvghusimz.html

[S04] C：字符串复制
来源：http://dali.sufxvd.cn/Article/details/gthikgxqmz.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.ppjwa.cn/Article/details/gtcmaxgvxa.html

[S05] C：字符串长度
来源：http://dali.smart0.xyz/Article/details/gthhygdfzu.html

strlen(s)
来源：http://dali.svipenyu.cn/Article/details/gtyvhkzqhe.html

[S06] C：字符串比较
来源：http://dali.xuetiantiany.cn/Article/details/gtlcgdwgny.html

strcmp(a, b) == 0
来源：http://dali.redwolf501.top/Article/details/gtahikztcv.html

[S07] C：数组遍历求和
来源：http://dali.ppjwa.cn/Article/details/gtifgytuje.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.cashguo.top/Article/details/gtouladxck.html

[S08] C：动态内存分配与释放
来源：http://dali.xuanzx.com/Article/details/gtabkpgirs.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.aibaodan.cn/Article/details/gtchmakmxg.html

[S09] C：结构体定义与初始化
来源：http://dali.yanxiufei.cn/Article/details/gtjipjsffb.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.yj20258888.top/Article/details/gtxhzbnovd.html

[S10] C：指针与解引用
来源：http://dali.hysaishi.cn/Article/details/gtysmfjzda.html

int *p = &a;  *p = 5;
来源：http://dali.zhiwuduotai.top/Article/details/gtqlrbbruz.html

[S11] C：逐行读文件
来源：http://dali.hnxiangtu.top/Article/details/gtfkgbvwfn.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.cheryme.top/Article/details/gtmcaufjoa.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.jiagoushi.top/Article/details/gtorinyesj.html

fclose(f);
来源：http://dali.zhengqikj.top/Article/details/gtnglyyzcp.html

[S12] C：写文件
来源：http://dali.daxiang520.top/Article/details/gtfikarfvf.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.xylfe.cn/Article/details/gtujvmeblk.html

[S13] C：宏定义
来源：http://dali.snrcjt.cn/Article/details/gtmgrxpstr.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxnisryqu.html

[S14] C：枚举
来源：http://dali.iojbl.cn/Article/details/gtmwyfcjmp.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.cqqwz.cn/Article/details/gtpthufqfq.html

[S15] C：类型转换
来源：http://dali.hnqzz.top/Article/details/gtwodiqprg.html

(double) a / b
来源：http://dali.yuanzhike.top/Article/details/gtpgnyrjep.html

[S16] C：位操作置位
来源：http://dali.zhiwuduotai.top/Article/details/gtxahzotat.html

x |= (1 << 3);
来源：http://dali.zhixingplan.top/Article/details/gtxoirhkaj.html

[S17] C：安全拼接字符串
来源：http://dali.quarkkingdee.top/Article/details/gtfkyyywem.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.fengsongda.top/Article/details/gtjwexincb.html

[S18] C：命令行参数
来源：http://dali.fengsongda.top/Article/details/gthwulidrw.html

int main(int argc, char **argv)
来源：http://dali.zycfv.cn/Article/details/gtctkkoure.html

[S19] C：快速排序
来源：http://dali.meibo888.top/Article/details/gtgvfcqyfe.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.hywenlv.cn/Article/details/gtlqtmtnku.html

[S20] C：二分查找
来源：http://dali.ehwqpu.com/Article/details/gtsngwljuc.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.sweek.top/Article/details/gtuxhhjhvz.html

[S21] C：字符类别判断
来源：http://dali.bjfxy.top/Article/details/gtujjaescu.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.dashuyun.cn/Article/details/gtfmitngzy.html

[S22] C：字符串转数字
来源：http://dali.daria6918.cn/Article/details/gtkwiltonx.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.gotoacloud.top/Article/details/gtjuowllyp.html

[S23] C：随机数
来源：http://dali.xinyue.icu/Article/details/gtlswzxbth.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhiwuduotai.top/Article/details/gtsslloped.html

[S24] C：获取本地时间
来源：http://dali.ybcxt.top/Article/details/gtbsrfuhaz.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.yj20258888.top/Article/details/gtrjthkaao.html

[S25] C：内存拷贝
来源：http://dali.aizwys.cn/Article/details/gtarlrmowb.html

memcpy(dst, src, n);
来源：http://dali.cqqwz.cn/Article/details/gtlrlmjvlg.html

[S26] C：内存清零
来源：http://dali.snrcjt.cn/Article/details/gtkofslzrw.html

memset(a, 0, sizeof a);
来源：http://dali.yueranfly.top/Article/details/gtqmwmwnyp.html

[S27] C：定义常量
来源：http://dali.gaohongyu789.top/Article/details/gtulszviju.html

const double PI = 3.14159;
来源：http://dali.aibaodan.cn/Article/details/gtcgltekmx.html

[S28] C：静态变量
来源：http://dali.svipenyu.cn/Article/details/gtcxcoztja.html

static int counter = 0;
来源：http://dali.zhengqikj.top/Article/details/gtyatkfmwc.html

[S29] C：变参函数
来源：http://dali.cucudq.cn/Article/details/gtltknrfef.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zycfv.cn/Article/details/gttklchuxs.html

[S30] C：头文件保护
来源：http://dali.jlsjyb.cn/Article/details/gtabrrfqxt.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gtobfeykel.html

#define X_H
来源：http://dali.daria6918.cn/Article/details/gtjaxkxulg.html

#endif
来源：http://dali.jqgfzy.top/Article/details/gtphvrjlug.html

[S31] C++：Hello World
来源：http://dali.zhixingplan.top/Article/details/gtqseipwoe.html

#include <iostream>
来源：http://dali.quarkkingdee.top/Article/details/gtlfxnoaqd.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.hywenlv.cn/Article/details/gthcwfnuyu.html

[S32] C++：字符串
来源：http://dali.yvedp.cn/Article/details/gthpqskoom.html

std::string s = "hi";  s += "!";
来源：http://dali.jinqigfzy.top/Article/details/gtxwvntyhw.html

[S33] C++：vector 增删
来源：http://dali.tian-w.cn/Article/details/gtfxhgeyxj.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.mhx1999.top/Article/details/gtewltxzcv.html

[S34] C++：遍历 vector
来源：http://dali.chenjidiqi.icu/Article/details/gtfzhoesxx.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.xziqi.cn/Article/details/gtjpafuvzk.html

[S35] C++：map
来源：http://dali.xylfe.cn/Article/details/gtnckylnuk.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zdqjudy.top/Article/details/gtntlyetme.html

[S36] C++：unordered_map
来源：http://dali.zdqjudy.top/Article/details/gtbgkvaccb.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.tian-w.cn/Article/details/gtunonbvbs.html

[S37] C++：set
来源：http://dali.vqdsnc.cn/Article/details/gtkhpisceg.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.xziqi.cn/Article/details/gtpbktorgh.html

[S38] C++：排序
来源：http://dali.tanke756.top/Article/details/gtobhbkaiz.html

std::sort(v.begin(), v.end());
来源：http://dali.jiagoushi.top/Article/details/gtgxgyddpg.html

[S39] C++：自定义比较器排序
来源：http://dali.fzhhl.top/Article/details/gtuaxzlmxx.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.chenjidiqi.icu/Article/details/gtuqhwvkib.html

[S40] C++：查找元素
来源：http://dali.zhongyouzk.top/Article/details/gtfjqcljnt.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.yj20258888.top/Article/details/gtfbqlpfol.html

[S41] C++：类与构造函数
来源：http://dali.xuanzx.com/Article/details/gtvcevsfjq.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.nanxuanxn.top/Article/details/gtwgesykih.html

[S42] C++：继承与虚函数
来源：http://dali.yanxiufei.cn/Article/details/gtgajancbo.html

class B : public Base { public: void f() override {} };
来源：http://dali.quarkkingdee.top/Article/details/gtfjgnxflt.html

[S43] C++：智能指针
来源：http://dali.jqgufenzy.top/Article/details/gtnovrqfej.html

auto p = std::make_unique<int>(5);
来源：http://dali.pycfn.com/Article/details/gtpoxcscvd.html

[S44] C++：引用传参
来源：http://dali.zhongyouzk.top/Article/details/gtpckbasps.html

void inc(int &x) { ++x; }
来源：http://dali.ydzc1.top/Article/details/gtecajvapd.html

[S45] C++：lambda
来源：http://dali.yuanzhike.top/Article/details/gthpxdvnxc.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.wangdashe.top/Article/details/gtkkofudrv.html

[S46] C++：函数模板
来源：http://dali.jlsjyb.cn/Article/details/gtrazzguct.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpvytfmcl.html

[S47] C++：结构化绑定遍历
来源：http://dali.hammf.cn/Article/details/gtlgtugcnj.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.tian-w.cn/Article/details/gthbljllkx.html

[S48] C++：逐行读文件
来源：http://dali.tian-w.cn/Article/details/gtbnfuhbhh.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.redwolf501.top/Article/details/gtuqdqnadr.html

while (std::getline(in, line)) { }
来源：http://dali.yueranfly.top/Article/details/gtyqcdakbn.html

[S49] C++：写文件
来源：http://dali.yueranfly.top/Article/details/gtrjrewegk.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.hnxiangtu.top/Article/details/gtqkntuwvq.html

[S50] C++：格式化数字
来源：http://dali.birdmap.top/Article/details/gtesljvxiu.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.daxiang520.top/Article/details/gtetscpzsl.html

[S51] C++：显式类型转换
来源：http://dali.chenlongwang.top/Article/details/gthfgqvcgn.html

static_cast<double>(a) / b
来源：http://dali.nanxuanxn.top/Article/details/gtdyjwmohz.html

[S52] C++：const 与 noexcept
来源：http://dali.ybcxt.top/Article/details/gtfijyscyj.html

int size() const noexcept { return n_; }
来源：http://dali.bjfxy.top/Article/details/gtmannkkks.html

[S53] C++：移动语义
来源：http://dali.jiagoushi.top/Article/details/gtaficjghn.html

std::vector<int> w = std::move(v);
来源：http://dali.cucudq.cn/Article/details/gtljpdwjkq.html

[S54] C++：异常处理
来源：http://dali.zdqjudy.top/Article/details/gticpswmbv.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.ehwqpu.com/Article/details/gtgfqgfacr.html

[S55] C++：结构化绑定
来源：http://dali.aizwys.cn/Article/details/gtovrogvng.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.sysykeji.top/Article/details/gtbechlege.html

[S56] C++：optional
来源：http://dali.quarkkingdee.top/Article/details/gtxxxvwwwt.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.jianghu66.top/Article/details/gtiwdcxprp.html

[S57] C++：编译期常量
来源：http://dali.yj202588.top/Article/details/gtrvjesktx.html

constexpr int N = 10;
来源：http://dali.yj20258.top/Article/details/gtzhmlphiu.html

[S58] C++：命名空间
来源：http://dali.hysaishi.cn/Article/details/gtkcroxtsb.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhongyouzk.top/Article/details/gtojqpxcst.html

[S59] C++：静态断言
来源：http://dali.daria6918.cn/Article/details/gtgchoelje.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.cucudq.cn/Article/details/gtrhzakmws.html

[S60] C++：遍历并删除元素
来源：http://dali.yvedp.cn/Article/details/gtwthdkxuv.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zycfv.cn/Article/details/gtpluwdozo.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtkyrwawih.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnvohxvbh.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtcylfocqa.html

[T01] Kotlin：Hello World
来源：http://dali.yuxming.cn/Article/details/gtjwidxizr.html

println("Hello")
来源：http://dali.hfpthk.cn/Article/details/gtyrqqgqyc.html

[T02] Kotlin：变量
来源：http://dali.havefunace.top/Article/details/gtqjjbdgox.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.redwolf501.top/Article/details/gtfguvewqq.html

[T03] Kotlin：字符串模板
来源：http://dali.daria6918.cn/Article/details/gtodnvahec.html

"值: $b"
来源：http://dali.yj20258.top/Article/details/gtcwbgjxrk.html

[T04] Kotlin：空安全
来源：http://dali.zhoulong.xyz/Article/details/gtzaaepdcv.html

val n: String? = null;  n?.length
来源：http://dali.bjfxy.top/Article/details/gttcdpmbxh.html

[T05] Kotlin：when 表达式
来源：http://dali.shanyushiyangtech.top/Article/details/gtxljqedpz.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.feifeiyinyue.top/Article/details/gtfnbjibye.html

[T06] Kotlin：集合映射
来源：http://dali.cucudq.cn/Article/details/gtezrjwkke.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.feifeiyinyue.top/Article/details/gtvoiwestk.html

[T07] Kotlin：集合过滤
来源：http://dali.wangshuangyany.cn/Article/details/gtnmprejyc.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zdqjudy.top/Article/details/gtcqxzjptw.html

[T08] Kotlin：数据类
来源：http://dali.zhengqikj.top/Article/details/gtbrabcvbh.html

data class User(val name: String, val age: Int)
来源：http://dali.chenzaomai.com/Article/details/gtvftfbdui.html

[T09] Kotlin：扩展函数
来源：http://dali.aizwys.cn/Article/details/gtsetsicoi.html

fun String.exclaim() = this + "!"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtievvjwxb.html

[T10] Kotlin：默认参数
来源：http://dali.dashuyun.cn/Article/details/gtlmjzbapp.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gtbrddbszi.html

[T11] Kotlin：协程
来源：http://dali.guowangkeji.top/Article/details/gtodpjlzax.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.hammf.cn/Article/details/gtdkplkgbp.html

[T12] Kotlin：解构声明
来源：http://dali.xinyue.icu/Article/details/gtclyzxqiw.html

val (a, b) = Pair(1, 2)
来源：http://dali.svipenyu.cn/Article/details/gthwimavoj.html

[T13] Kotlin：只读 Map
来源：http://dali.wangshuangyany.cn/Article/details/gtczugtjli.html

val m = mapOf("a" to 1)
来源：http://dali.jyoumei.cn/Article/details/gtkbzqofur.html

[T14] Kotlin：循环
来源：http://dali.hnxiangtu.top/Article/details/gtgebiglcy.html

for (i in 1..10) println(i)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtviqxrdit.html

[T15] Kotlin：接口
来源：http://dali.quarkkingdee.top/Article/details/gtgxqkdxqy.html

interface Shape { fun area(): Double }
来源：http://dali.redwolf501.top/Article/details/gtuqozbexa.html

[T16] Swift：Hello World
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfpluvzml.html

print("Hello")
来源：http://dali.sweek.top/Article/details/gtjxmqcaly.html

[T17] Swift：变量与常量
来源：http://dali.mhx1999.top/Article/details/gtzrijaeai.html

var a = 1;  let b = 2
来源：http://dali.tianlin.xyz/Article/details/gtydxevpmw.html

[T18] Swift：字符串插值
来源：http://dali.shuidangran.top/Article/details/gtjsjyazuh.html

"值: \(b)"
来源：http://dali.pycfn.com/Article/details/gtlkavrceo.html

[T19] Swift：可选绑定
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmmkrtpho.html

if let n = opt { print(n) }
来源：http://dali.jinghuilouyu.cn/Article/details/gtxfkdpcjh.html

[T20] Swift：数组操作
来源：http://dali.zhixingplan.top/Article/details/gtdzjvftlr.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.cheryme.top/Article/details/gtsmbnkrim.html

[T21] Swift：遍历
来源：http://dali.yuxming.cn/Article/details/gtdkwouufc.html

for x in a { print(x) }
来源：http://dali.guowangkeji.top/Article/details/gtwvsghezu.html

[T22] Swift：字典
来源：http://dali.xziqi.cn/Article/details/gtghvhwrir.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.svipenyu.cn/Article/details/gtsbzvveqa.html

[T23] Swift：函数
来源：http://dali.nanxinkj.top/Article/details/gtdbkedgww.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.svipenyu.cn/Article/details/gtmoqlljli.html

[T24] Swift：闭包
来源：http://dali.zycfv.cn/Article/details/gtfrdboybp.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhengqikj.top/Article/details/gtimbgxasr.html

[T25] Swift：结构体
来源：http://dali.quarkkingdee.top/Article/details/gtpcvncadj.html

struct P { var x: Int }
来源：http://dali.nanxinkj.top/Article/details/gtbjdthelc.html

[T26] Swift：类与重写
来源：http://dali.ivvv.top/Article/details/gtlquhggho.html

class A: Base { override func f() {} }
来源：http://dali.yuanzhike.top/Article/details/gttwzdaodn.html

[T27] Swift：错误处理
来源：http://dali.haohaochexian.top/Article/details/gtzkhrttzr.html

do { try f() } catch { print(error) }
来源：http://dali.daxiang520.top/Article/details/gtdtvtqnni.html

[T28] Swift：枚举
来源：http://dali.zycfv.cn/Article/details/gtzgveimnj.html

enum Color { case red, green }
来源：http://dali.yuxming.cn/Article/details/gttjhwhxec.html

[T29] Swift：guard 提前返回
来源：http://dali.xziqi.cn/Article/details/gtjntethgm.html

guard let x = opt else { return }
来源：http://dali.smart0.xyz/Article/details/gtnzlcgsma.html

[T30] Swift：协议
来源：http://dali.bjfxy.top/Article/details/gtnzbemzen.html

protocol Shape { func area() -> Double }
来源：http://dali.hfpthk.cn/Article/details/gtqeckzcqx.html

[T31] Lua：Hello World
来源：http://dali.fzhhl.top/Article/details/gtbshoyfvo.html

print("Hello")
来源：http://dali.fzhhl.top/Article/details/gtnfutoiup.html

[T32] Lua：局部变量
来源：http://dali.sweek.top/Article/details/gteaeyiugz.html

local a = 1
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoeldgyxu.html

[T33] Lua：表（数组）
来源：http://dali.xziqi.cn/Article/details/gtvtfiqqoe.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.hywenlv.cn/Article/details/gtdnjmtmjf.html

[T34] Lua：遍历表
来源：http://dali.cashguo.top/Article/details/gtysnuwhwi.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.ppjwa.cn/Article/details/gthndzasne.html

[T35] Lua：字典表
来源：http://dali.cheryme.top/Article/details/gthnduxqge.html

local d = { a = 1 };  d.b = 2
来源：http://dali.yongpay.top/Article/details/gtveutsovs.html

[T36] Lua：函数
来源：http://dali.vqdsnc.cn/Article/details/gtdmdatrod.html

function add(a, b) return a + b end
来源：http://dali.cdnleiting.top/Article/details/gtzionyaat.html

[T37] Lua：字符串拼接
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwcgylorw.html

"a" .. "b"
来源：http://dali.tianlin.xyz/Article/details/gtstlbaohy.html

[T38] Lua：条件
来源：http://dali.daria6918.cn/Article/details/gtybgwdwbn.html

if x > 0 then print("正") end
来源：http://dali.0kj1m.cn/Article/details/gtykltghvx.html

[T39] Lua：模式匹配
来源：http://dali.gzhubu.top/Article/details/gtazutmhpp.html

string.find(s, "%d+")
来源：http://dali.gogol.net.cn/Article/details/gtqbxglaeh.html

[T40] Lua：元表
来源：http://dali.iojbl.cn/Article/details/gtltthykjn.html

setmetatable({}, { __index = base })
来源：http://dali.sxryk.cn/Article/details/gtnoprewyy.html

[T41] Perl：Hello World
来源：http://dali.yvedp.cn/Article/details/gtyavawvxc.html

print "Hello\n";
来源：http://dali.zhaomingkeji.xyz/Article/details/gtceomfdje.html

[T42] Perl：变量类型
来源：http://dali.zhongyouzk.top/Article/details/gtevqnoxqm.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.jqgfzy.top/Article/details/gtgqjgrmxt.html

[T43] Perl：字符串插值
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoskrlezt.html

"值: $a"
来源：http://dali.9152youxi.cn/Article/details/gtwelvagij.html

[T44] Perl：条件
来源：http://dali.cucudq.cn/Article/details/gtwaueggno.html

if ($a > 0) { print "正"; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtitvcyxoq.html

[T45] Perl：数组遍历
来源：http://dali.jiagoushi.top/Article/details/gtmjbzgpfj.html

for my $x (@arr) { print $x; }
来源：http://dali.pengpengdd.cyou/Article/details/gtdzzmqimi.html

[T46] Perl：哈希操作
来源：http://dali.snrcjt.cn/Article/details/gtcjzgrgmp.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.yvedp.cn/Article/details/gtgezajgus.html

[T47] Perl：正则捕获
来源：http://dali.yj20258.top/Article/details/gtctipdyqz.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.xylfe.cn/Article/details/gtbeiraqvb.html

[T48] Perl：正则替换
来源：http://dali.tian-w.cn/Article/details/gtusgvetuv.html

$s =~ s/old/new/g;
来源：http://dali.tanke756.top/Article/details/gtisojsecz.html

[T49] Perl：函数
来源：http://dali.gogol.net.cn/Article/details/gtgpmmfzws.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.sweek.top/Article/details/gtechquvlf.html

[T50] Perl：逐行读文件
来源：http://dali.redwolf501.top/Article/details/gtlqkydyir.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.tanke756.top/Article/details/gtkfwurrbf.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtltqjusdh.html

[T51] Scala：Hello World
来源：http://dali.ppjwa.cn/Article/details/gtvthpkxmo.html

println("Hello")
来源：http://dali.tianlin.xyz/Article/details/gtlhfxcvnc.html

[T52] Scala：变量
来源：http://dali.yueranfly.top/Article/details/gtabrejhot.html

val a = 1;  var b = 2
来源：http://dali.shanyushiyangtech.top/Article/details/gtptyvhmoi.html

[T53] Scala：字符串插值
来源：http://dali.gzhubu.top/Article/details/gtktalxfxn.html

s"值: $b"
来源：http://dali.c1oappe.top/Article/details/gtsrswiqxt.html

[T54] Scala：集合映射
来源：http://dali.yongpay.top/Article/details/gthysgrtmw.html


<!-- 参考信息 -->