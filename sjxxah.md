代发 wailian999

cmd >/dev/null 2>&1
来源：http://dali.zhongyouzk.top/Article/details/gtjxwcqaay.html

[R42] 输入重定向
来源：http://dali.zhixingplan.top/Article/details/gtpmrngyfb.html

wc -l < a.txt
来源：http://dali.daria6918.cn/Article/details/gtkjwqzdlo.html

[R43] 按名字查找文件
来源：http://dali.0kj1m.cn/Article/details/gtsxjxksaw.html

find . -name "*.log" -type f
来源：http://dali.shuidangran.top/Article/details/gtmrybhrpg.html

[R44] 按修改时间查找
来源：http://dali.sweek.top/Article/details/gtrxltjlmv.html

find . -mtime -7 -type f
来源：http://dali.yuxming.cn/Article/details/gtvgvddses.html

[R45] 批量删除
来源：http://dali.yj20258.top/Article/details/gtgdffxupz.html

find . -name "*.tmp" -delete
来源：http://dali.quarkkingdee.top/Article/details/gtkexpojhr.html

[R46] 递归替换文件内容
来源：http://dali.hnxiangtu.top/Article/details/gtgwzoypul.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.yonumen.top/Article/details/gtgwhzdtjs.html

[R47] sed 单行替换
来源：http://dali.kuanghao11.cn/Article/details/gtwcgsfvsb.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.hongshengwenyu.top/Article/details/gtutmomjmw.html

[R48] awk 取指定列
来源：http://dali.zycfv.cn/Article/details/gtgakcqpav.html

awk '{print $1, $3}' a.txt
来源：http://dali.fzhhl.top/Article/details/gteffaybpk.html

[R49] awk 带条件
来源：http://dali.yj20258888.top/Article/details/gtrqnxlgqo.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.haohaochexian.top/Article/details/gtlcfwrysv.html

[R50] awk 求和
来源：http://dali.c1oappe.top/Article/details/gtgiazmtvm.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhixingplan.top/Article/details/gtkpzphvzq.html

[R51] 排序去重取前几
来源：http://dali.xziqi.cn/Article/details/gttccjprza.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.guannengcc.top/Article/details/gttltgdtqc.html

[R52] 统计行数
来源：http://dali.316326.xyz/Article/details/gtxqnewmza.html

wc -l a.txt
来源：http://dali.yj20258888.top/Article/details/gtembcrzka.html

[R53] 查看文件头与实时尾
来源：http://dali.yonumen.top/Article/details/gttgqopfwd.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.pengpengdd.cyou/Article/details/gtussnfpas.html

[R54] 比较两个文件
来源：http://dali.redwolf501.top/Article/details/gtmkxdistx.html

diff a.txt b.txt
来源：http://dali.zhixingplan.top/Article/details/gtngpsnrkk.html

[R55] 压缩与解压
来源：http://dali.ydzc1.top/Article/details/gtxoypkzdj.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.xylfe.cn/Article/details/gtnefstpim.html

[R56] 远程拷贝
来源：http://dali.ehwqpu.com/Article/details/gtdhsoilsw.html

scp file user@host:/path/
来源：http://dali.gotoacloud.top/Article/details/gtziscblls.html

[R57] 远程执行命令
来源：http://dali.shzxlz.cn/Article/details/gtycgbqhnk.html

ssh user@host 'uptime'
来源：http://dali.vqdsnc.cn/Article/details/gtmncbpzrg.html

[R58] 下载文件
来源：http://dali.yj20258888.top/Article/details/gtstlxccda.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.shzxlz.cn/Article/details/gtcfgkuyor.html

[R59] 发 POST JSON
来源：http://dali.aibaodan.cn/Article/details/gtcfxbsfhf.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.quarkkingdee.top/Article/details/gtiixetvlk.html

[R60] 只看 HTTP 状态码
来源：http://dali.hnxiangtu.top/Article/details/gtymzeqpzv.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.aizwys.cn/Article/details/gtmoenfudo.html

[R61] 磁盘占用
来源：http://dali.ydzc1.top/Article/details/gtybnrcugf.html

df -h;  du -sh *
来源：http://dali.ybcxt.top/Article/details/gtwpkzdqsd.html

[R62] 找最占空间的文件
来源：http://dali.hongshengwenyu.top/Article/details/gtetyrhepr.html

du -ah . | sort -rh | head -10
来源：http://dali.316326.xyz/Article/details/gtkqcjmayf.html

[R63] 内存与进程
来源：http://dali.xylfe.cn/Article/details/gtmcmamqpt.html

free -h;  ps aux | grep nginx
来源：http://dali.havefunace.top/Article/details/gthfwmccdv.html

[R64] 结束进程
来源：http://dali.pycfn.com/Article/details/gtacpdszvt.html

kill -9 $(pgrep -f app.py)
来源：http://dali.hnqzz.top/Article/details/gtvznqbrpv.html

[R65] 查看端口占用
来源：http://dali.mhx1999.top/Article/details/gtecsjrzvq.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.jinyuanbaomall.cn/Article/details/gturnuesqb.html

[R66] 定时任务
来源：http://dali.havefunace.top/Article/details/gtobiipjwg.html

crontab -e;  crontab -l
来源：http://dali.yangfankeji.com/Article/details/gttswztdfy.html

[R67] 生成随机十六进制串
来源：http://dali.kuanghao11.cn/Article/details/gtqzixzerg.html

openssl rand -hex 16
来源：http://dali.bjfxy.top/Article/details/gtjyzsuncm.html

[R68] 计算文件校验值
来源：http://dali.c1oappe.top/Article/details/gtqlziyucr.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhongyouzk.top/Article/details/gtdvfidnwu.html

[R69] 生成随机密码
来源：http://dali.tian-w.cn/Article/details/gtqhmnpxmw.html

head -c 16 /dev/urandom | base64
来源：http://dali.nanxuanxn.top/Article/details/gtaxdcyqdo.html

[R70] 时间戳与互转
来源：http://dali.pycfn.com/Article/details/gtkjxpspyg.html

date +%s;  date -d @1700000000
来源：http://dali.hfpthk.cn/Article/details/gtfrccojwm.html

[R71] 日期格式化
来源：http://dali.kuanghao11.cn/Article/details/gtyojvjtfe.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.jqgfzy.top/Article/details/gtmvrfcupa.html

[R72] 等待端口就绪
来源：http://dali.vqdsnc.cn/Article/details/gtqkxdwcvk.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.jinqigufen.top/Article/details/gtfenoryka.html

[R73] 分割大日志
来源：http://dali.ehwqpu.com/Article/details/gthybopflf.html

split -l 1000 big.log part_
来源：http://dali.sufxvd.cn/Article/details/gtjuzargtc.html

[R74] 批量重命名
来源：http://dali.sweek.top/Article/details/gtoxbiveyv.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.daxiang520.top/Article/details/gtflkicxls.html

[R75] 导出环境变量
来源：http://dali.nanxinkj.top/Article/details/gtiqoxezuk.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.hnxiangtu.top/Article/details/gtnxdsocjm.html

[R76] 使用临时文件
来源：http://dali.jqgfzy.top/Article/details/gtgdibsiro.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.meibo888.top/Article/details/gtcpeyirwp.html

[R77] 读取用户输入
来源：http://dali.jlsjyb.cn/Article/details/gttuagoctg.html

read -rp "请输入: " ans
来源：http://dali.iojbl.cn/Article/details/gtaixswwzu.html

[R78] 交互式菜单
来源：http://dali.jinqigufen.top/Article/details/gtbgxbyfyy.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.kuanghao11.cn/Article/details/gtwmlftbdm.html

[R79] 解析命令行选项
来源：http://dali.hongshengwenyu.top/Article/details/gtjumizsbv.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhoulong.xyz/Article/details/gtwmhjebft.html

[R80] 查看脚本执行耗时
来源：http://dali.ppjwa.cn/Article/details/gtlwuyooux.html

time ./run.sh
来源：http://dali.xziqi.cn/Article/details/gtwarwtosv.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtuhjqomqb.html

S. C / C++ 专题
来源：http://dali.yj202588.top/Article/details/gtupewcoqo.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtmawaptbn.html

[S01] C：Hello World
来源：http://dali.bjfxy.top/Article/details/gtkljhdhkk.html

#include <stdio.h>
来源：http://dali.shuidangran.top/Article/details/gtzjvmuhzg.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhoulong.xyz/Article/details/gtvqjxgirn.html

[S02] C：变量与格式化输出
来源：http://dali.yangfankeji.com/Article/details/gtcphxoyxk.html

int a = 10; printf("%d\n", a);
来源：http://dali.yuxming.cn/Article/details/gtavmppkku.html

[S03] C：读入整数
来源：http://dali.jlsjyb.cn/Article/details/gtalqkxpaj.html

int x; scanf("%d", &x);
来源：http://dali.shzxlz.cn/Article/details/gtwbhuhdeb.html

[S04] C：字符串复制
来源：http://dali.haohaochexian.top/Article/details/gthkeutwna.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gtzvcszdep.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gtwjcllnvq.html

strlen(s)
来源：http://dali.zdqjudy.top/Article/details/gtqcxdefyz.html

[S06] C：字符串比较
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpesjjpzk.html

strcmp(a, b) == 0
来源：http://dali.sufxvd.cn/Article/details/gthgafrtmb.html

[S07] C：数组遍历求和
来源：http://dali.yonumen.top/Article/details/gtzuieejta.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhaomingkeji.xyz/Article/details/gtztbzhzni.html

[S08] C：动态内存分配与释放
来源：http://dali.pycfn.com/Article/details/gtdukvdlkr.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.gotoacloud.top/Article/details/gtqwcqqkyc.html

[S09] C：结构体定义与初始化
来源：http://dali.jqgfzy.top/Article/details/gtadtrtzwa.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.yvedp.cn/Article/details/gtuaftxqtt.html

[S10] C：指针与解引用
来源：http://dali.zhixingplan.top/Article/details/gtskbwwhxb.html

int *p = &a;  *p = 5;
来源：http://dali.jianghu66.top/Article/details/gtcgyhbvut.html

[S11] C：逐行读文件
来源：http://dali.svipenyu.cn/Article/details/gtktayevhe.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.hfpthk.cn/Article/details/gtjdhjankz.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.cashguo.top/Article/details/gtjvmafybv.html

fclose(f);
来源：http://dali.kuanghao11.cn/Article/details/gtwsorlofu.html

[S12] C：写文件
来源：http://dali.gogol.net.cn/Article/details/gtshvdvkuo.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.yanxiufei.cn/Article/details/gtcietjyzi.html

[S13] C：宏定义
来源：http://dali.cheryme.top/Article/details/gtlekdntxs.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.jinqigfzy.top/Article/details/gtmcwuntfc.html

[S14] C：枚举
来源：http://dali.gotoacloud.top/Article/details/gtzjeknota.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.ehwqpu.com/Article/details/gtquibmxgd.html

[S15] C：类型转换
来源：http://dali.guowangkeji.top/Article/details/gttbexncus.html

(double) a / b
来源：http://dali.shuidangran.top/Article/details/gtaxtackcd.html

[S16] C：位操作置位
来源：http://dali.jinghuilouyu.cn/Article/details/gtuzxtgvxd.html

x |= (1 << 3);
来源：http://dali.birdmap.top/Article/details/gtejiaajsr.html

[S17] C：安全拼接字符串
来源：http://dali.yj20258888.top/Article/details/gtafdpbcjf.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.sweek.top/Article/details/gtekderzgy.html

[S18] C：命令行参数
来源：http://dali.svipenyu.cn/Article/details/gtrdrqxoew.html

int main(int argc, char **argv)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyyddtpkc.html

[S19] C：快速排序
来源：http://dali.jqgfzy.top/Article/details/gtdbqmcxnt.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.shuidangran.top/Article/details/gtnxcpsvpd.html

[S20] C：二分查找
来源：http://dali.sweek.top/Article/details/gtjtvvbbcn.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.xuetiantiany.cn/Article/details/gtkeioneqh.html

[S21] C：字符类别判断
来源：http://dali.ybcxt.top/Article/details/gtavcxqjhv.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtocnuruyn.html

[S22] C：字符串转数字
来源：http://dali.chenjidiqi.icu/Article/details/gtnikpkmpq.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.quarkkingdee.top/Article/details/gtkjheaqns.html

[S23] C：随机数
来源：http://dali.nanxinkj.top/Article/details/gtaiezytdm.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.cqqwz.cn/Article/details/gtcympcuys.html

[S24] C：获取本地时间
来源：http://dali.gotoacloud.top/Article/details/gtuaijrgqp.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.cqqwz.cn/Article/details/gtruhdojcd.html

[S25] C：内存拷贝
来源：http://dali.aizwys.cn/Article/details/gtvmwzvisf.html

memcpy(dst, src, n);
来源：http://dali.jqgufenzy.top/Article/details/gtfrrexjcd.html

[S26] C：内存清零
来源：http://dali.cucudq.cn/Article/details/gtoawxcpam.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gtychmbaqf.html

[S27] C：定义常量
来源：http://dali.gogol.net.cn/Article/details/gtaefjyxxb.html

const double PI = 3.14159;
来源：http://dali.ybcxt.top/Article/details/gtnczpuqba.html

[S28] C：静态变量
来源：http://dali.sysykeji.top/Article/details/gtxmlwhllt.html

static int counter = 0;
来源：http://dali.shzxlz.cn/Article/details/gtegdvwqoa.html

[S29] C：变参函数
来源：http://dali.gogol.net.cn/Article/details/gtazmjtzgr.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhengqikj.top/Article/details/gtavoahtcb.html

[S30] C：头文件保护
来源：http://dali.hongshengwenyu.top/Article/details/gtjacsiqsi.html

#ifndef X_H
来源：http://dali.yuanzhike.top/Article/details/gteepxiiyg.html

#define X_H
来源：http://dali.daxiang520.top/Article/details/gtmahxskka.html

#endif
来源：http://dali.zdqjudy.top/Article/details/gtwkoaaxdy.html

[S31] C++：Hello World
来源：http://dali.yanxiufei.cn/Article/details/gtgokqykas.html

#include <iostream>
来源：http://dali.wangdashe.top/Article/details/gtwrsvgsuc.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.nwbrower.top/Article/details/gtvlapmnhc.html

[S32] C++：字符串
来源：http://dali.wangdashe.top/Article/details/gtxwrcgkxy.html

std::string s = "hi";  s += "!";
来源：http://dali.c1oappe.top/Article/details/gtgtxwxapu.html

[S33] C++：vector 增删
来源：http://dali.guowangkeji.top/Article/details/gtzxgmbqec.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.xinyue.icu/Article/details/gtrevwjxlz.html

[S34] C++：遍历 vector
来源：http://dali.jinghuilouyu.cn/Article/details/gtbeybqsvk.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.sxryk.cn/Article/details/gtqsktulbj.html

[S35] C++：map
来源：http://dali.yuanzhike.top/Article/details/gtwyykurpf.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.nanxuanxn.top/Article/details/gtvpxxtnnm.html

[S36] C++：unordered_map
来源：http://dali.hnxiangtu.top/Article/details/gtxouqnkyc.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.tian-w.cn/Article/details/gtoopmnthi.html

[S37] C++：set
来源：http://dali.cqqwz.cn/Article/details/gtvraaczvz.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.jinqigufen.top/Article/details/gtcdgotlsy.html

[S38] C++：排序
来源：http://dali.shuidangran.top/Article/details/gtvqpvvzmu.html

std::sort(v.begin(), v.end());
来源：http://dali.chenlongwang.top/Article/details/gtebzsteet.html

[S39] C++：自定义比较器排序
来源：http://dali.shuidangran.top/Article/details/gtwnakyyzf.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.jianghu66.top/Article/details/gtzkijwrjn.html

[S40] C++：查找元素
来源：http://dali.cheryme.top/Article/details/gtfbozhehm.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.gogol.net.cn/Article/details/gtqumaqixe.html

[S41] C++：类与构造函数
来源：http://dali.xylfe.cn/Article/details/gtmzsngkto.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.fzhhl.top/Article/details/gtpnfjeqpa.html

[S42] C++：继承与虚函数
来源：http://dali.sufxvd.cn/Article/details/gteowjoapw.html

class B : public Base { public: void f() override {} };
来源：http://dali.0kj1m.cn/Article/details/gtxvdilhox.html

[S43] C++：智能指针
来源：http://dali.meibo888.top/Article/details/gtgrofszdi.html

auto p = std::make_unique<int>(5);
来源：http://dali.tanke756.top/Article/details/gtpwdrymfd.html

[S44] C++：引用传参
来源：http://dali.ehwqpu.com/Article/details/gtosyenuhy.html

void inc(int &x) { ++x; }
来源：http://dali.yj202588.top/Article/details/gtzgceetxl.html

[S45] C++：lambda
来源：http://dali.gotoacloud.top/Article/details/gtmveldvje.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.jinqigufen.top/Article/details/gtjamuvodh.html

[S46] C++：函数模板
来源：http://dali.nwbrower.top/Article/details/gtnjxnzgxw.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.wangshuangyany.cn/Article/details/gtwaavuppt.html

[S47] C++：结构化绑定遍历
来源：http://dali.shangyingyoupin.top/Article/details/gtevxytfcm.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.xuanzx.com/Article/details/gtvoeqpdsj.html

[S48] C++：逐行读文件
来源：http://dali.jlsjyb.cn/Article/details/gtrfzyzhlf.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.yuanzhike.top/Article/details/gtwvfxhcoj.html

while (std::getline(in, line)) { }
来源：http://dali.9152youxi.cn/Article/details/gtfjxekuqq.html

[S49] C++：写文件
来源：http://dali.iojbl.cn/Article/details/gtoikkidom.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.shangyingyoupin.top/Article/details/gtxyrghjjv.html

[S50] C++：格式化数字
来源：http://dali.pengpengdd.cyou/Article/details/gtonhxkqwu.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.yueranfly.top/Article/details/gtzjsellfc.html

[S51] C++：显式类型转换
来源：http://dali.yangfankeji.com/Article/details/gtcryqbmyy.html

static_cast<double>(a) / b
来源：http://dali.0kj1m.cn/Article/details/gtmfjicovm.html

[S52] C++：const 与 noexcept
来源：http://dali.meibo888.top/Article/details/gtmpsnaord.html

int size() const noexcept { return n_; }
来源：http://dali.yangfankeji.com/Article/details/gtqyfdluvz.html

[S53] C++：移动语义
来源：http://dali.jinqigufen.top/Article/details/gtgjluedao.html

std::vector<int> w = std::move(v);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkdfarnht.html

[S54] C++：异常处理
来源：http://dali.jianghu66.top/Article/details/gtfuxsaxnh.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.yvedp.cn/Article/details/gtmrliwfjb.html

[S55] C++：结构化绑定
来源：http://dali.cqqwz.cn/Article/details/gtejvezomr.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.hywenlv.cn/Article/details/gtbnjfslzt.html

[S56] C++：optional
来源：http://dali.jyoumei.cn/Article/details/gttsvvowtc.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zycfv.cn/Article/details/gtdcuzsmcc.html

[S57] C++：编译期常量
来源：http://dali.shanyushiyangtech.top/Article/details/gtelmdmgzg.html

constexpr int N = 10;
来源：http://dali.jiagoushi.top/Article/details/gtpnvlnsck.html

[S58] C++：命名空间
来源：http://dali.hysaishi.cn/Article/details/gtheusqbov.html

namespace ns { int f() { return 1; } }
来源：http://dali.tian-w.cn/Article/details/gtjxydktdh.html

[S59] C++：静态断言
来源：http://dali.jinqigufen.top/Article/details/gtlubbttxc.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.redwolf501.top/Article/details/gtgoyblswh.html

[S60] C++：遍历并删除元素
来源：http://dali.yueranfly.top/Article/details/gtnjxgdtqu.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.kuanghao11.cn/Article/details/gtlpozzkuq.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtialdzmrd.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhixingplan.top/Article/details/gtiencpdgb.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbtuptiep.html

[T01] Kotlin：Hello World
来源：http://dali.cheryme.top/Article/details/gtjepvgwki.html

println("Hello")
来源：http://dali.wangdashe.top/Article/details/gtrlnbuwxz.html

[T02] Kotlin：变量
来源：http://dali.hysaishi.cn/Article/details/gtnnkdgvor.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.hammf.cn/Article/details/gtjkystpdi.html

[T03] Kotlin：字符串模板
来源：http://dali.sxryk.cn/Article/details/gtljsqemco.html

"值: $b"
来源：http://dali.feifeiyinyue.top/Article/details/gtsjrcnpro.html

[T04] Kotlin：空安全
来源：http://dali.cqqwz.cn/Article/details/gthxlfkfem.html

val n: String? = null;  n?.length
来源：http://dali.sxryk.cn/Article/details/gttcotgmla.html

[T05] Kotlin：when 表达式
来源：http://dali.c1oappe.top/Article/details/gtyzynxkyf.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.sufxvd.cn/Article/details/gtzbupiggq.html

[T06] Kotlin：集合映射
来源：http://dali.shanyushiyangkeji.top/Article/details/gtunjxjxxx.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.dashuyun.cn/Article/details/gtzhpmlkoq.html

[T07] Kotlin：集合过滤
来源：http://dali.andypj.xyz/Article/details/gtfdmpunvr.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.aibaodan.cn/Article/details/gtcwwewwui.html

[T08] Kotlin：数据类
来源：http://dali.hammf.cn/Article/details/gtwzadqhst.html

data class User(val name: String, val age: Int)
来源：http://dali.yongpay.top/Article/details/gtsaejwdul.html

[T09] Kotlin：扩展函数
来源：http://dali.dianchejie.cn/Article/details/gtetwnnews.html

fun String.exclaim() = this + "!"
来源：http://dali.yonumen.top/Article/details/gtycnlrqhr.html

[T10] Kotlin：默认参数
来源：http://dali.pengpengdd.cyou/Article/details/gtvrfdxvms.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.gaohongyu789.top/Article/details/gtcvojndts.html

[T11] Kotlin：协程
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnjbktict.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.mhx1999.top/Article/details/gtyominoeo.html

[T12] Kotlin：解构声明
来源：http://dali.zhixingplan.top/Article/details/gttitoolrp.html

val (a, b) = Pair(1, 2)
来源：http://dali.gotoacloud.top/Article/details/gtjccmqoim.html

[T13] Kotlin：只读 Map
来源：http://dali.quarkkingdee.top/Article/details/gtabemntsi.html

val m = mapOf("a" to 1)
来源：http://dali.xuetiantiany.cn/Article/details/gtflekkkuz.html

[T14] Kotlin：循环
来源：http://dali.hnqzz.top/Article/details/gtwxwpraek.html

for (i in 1..10) println(i)
来源：http://dali.shanyushiyangtech.top/Article/details/gtqaplwnsr.html

[T15] Kotlin：接口
来源：http://dali.tanke756.top/Article/details/gttfiiefgm.html

interface Shape { fun area(): Double }
来源：http://dali.cashguo.top/Article/details/gttltfwptk.html

[T16] Swift：Hello World
来源：http://dali.c1oappe.top/Article/details/gtpoblkgpf.html

print("Hello")
来源：http://dali.fengsongda.top/Article/details/gtqbyojujq.html

[T17] Swift：变量与常量
来源：http://dali.guowangkeji.top/Article/details/gtduemncom.html

var a = 1;  let b = 2
来源：http://dali.yonumen.top/Article/details/gtequoztll.html

[T18] Swift：字符串插值
来源：http://dali.yonumen.top/Article/details/gtsnvyluwu.html

"值: \(b)"
来源：http://dali.zhengqikj.top/Article/details/gtgpszspuk.html

[T19] Swift：可选绑定
来源：http://dali.chenzaomai.com/Article/details/gtlhrtvkbj.html

if let n = opt { print(n) }
来源：http://dali.jianghu66.top/Article/details/gtobkszkzh.html

[T20] Swift：数组操作
来源：http://dali.zycfv.cn/Article/details/gtgkfgqkdz.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.shanyushiyangtech.top/Article/details/gtriuajdst.html

[T21] Swift：遍历
来源：http://dali.cucudq.cn/Article/details/gtybfjlhrr.html

for x in a { print(x) }
来源：http://dali.cashguo.top/Article/details/gtrtxwilxz.html

[T22] Swift：字典
来源：http://dali.haohaochexian.top/Article/details/gtdbxkmkrv.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.cucudq.cn/Article/details/gtlzhbdiab.html

[T23] Swift：函数
来源：http://dali.daria6918.cn/Article/details/gtazgirudp.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.pycfn.com/Article/details/gtsdjplhhr.html

[T24] Swift：闭包
来源：http://dali.xziqi.cn/Article/details/gtzldiximw.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.vqdsnc.cn/Article/details/gtiqkflgyw.html

[T25] Swift：结构体
来源：http://dali.iojbl.cn/Article/details/gtuuhikitp.html

struct P { var x: Int }
来源：http://dali.xinyue.icu/Article/details/gtmewsirii.html

[T26] Swift：类与重写
来源：http://dali.yonumen.top/Article/details/gtfjazwzmy.html

class A: Base { override func f() {} }
来源：http://dali.tanke756.top/Article/details/gtcktctqwm.html

[T27] Swift：错误处理
来源：http://dali.hnqzz.top/Article/details/gtyxffojvb.html

do { try f() } catch { print(error) }
来源：http://dali.jianghu66.top/Article/details/gtlpdlffcc.html

[T28] Swift：枚举
来源：http://dali.ydzc1.top/Article/details/gtfuisqsgn.html

enum Color { case red, green }
来源：http://dali.cashguo.top/Article/details/gtsoaaiqqz.html

[T29] Swift：guard 提前返回
来源：http://dali.c1oappe.top/Article/details/gtfitkktnk.html

guard let x = opt else { return }
来源：http://dali.cashguo.top/Article/details/gtkqpqxwby.html

[T30] Swift：协议
来源：http://dali.jlsjyb.cn/Article/details/gtabelbbcj.html

protocol Shape { func area() -> Double }
来源：http://dali.shangyingyoupin.top/Article/details/gtukajybjl.html

[T31] Lua：Hello World
来源：http://dali.tian-w.cn/Article/details/gtzdimueng.html

print("Hello")
来源：http://dali.xuanzx.com/Article/details/gtkxagawpk.html

[T32] Lua：局部变量
来源：http://dali.hnqzz.top/Article/details/gtttmyymhl.html

local a = 1
来源：http://dali.jianghu66.top/Article/details/gtmzhdqnrv.html

[T33] Lua：表（数组）
来源：http://dali.chenzaomai.com/Article/details/gtnntanpks.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvwsnnddl.html

[T34] Lua：遍历表
来源：http://dali.ydzc1.top/Article/details/gtjgkrmcyk.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.sysykeji.top/Article/details/gtuldolrkl.html

[T35] Lua：字典表
来源：http://dali.chenjidiqi.icu/Article/details/gtbpoxldzx.html

local d = { a = 1 };  d.b = 2
来源：http://dali.yuxming.cn/Article/details/gtbcerikit.html

[T36] Lua：函数
来源：http://dali.svipenyu.cn/Article/details/gtqaaeuksc.html

function add(a, b) return a + b end
来源：http://dali.ppjwa.cn/Article/details/gtjmvwwlwp.html

[T37] Lua：字符串拼接
来源：http://dali.yj20258.top/Article/details/gtkctazevm.html

"a" .. "b"
来源：http://dali.jqgfzy.top/Article/details/gtktffxauh.html

[T38] Lua：条件
来源：http://dali.jiagoushi.top/Article/details/gtmwpvuedc.html

if x > 0 then print("正") end
来源：http://dali.birdmap.top/Article/details/gtjilrdojg.html

[T39] Lua：模式匹配
来源：http://dali.yj202588.top/Article/details/gtxiltkgvt.html

string.find(s, "%d+")
来源：http://dali.dashuyun.cn/Article/details/gtxonhhstt.html

[T40] Lua：元表
来源：http://dali.quarkkingdee.top/Article/details/gtxxqgeupa.html

setmetatable({}, { __index = base })
来源：http://dali.ivvv.top/Article/details/gtzlgnnbda.html

[T41] Perl：Hello World
来源：http://dali.jinqigufen.top/Article/details/gtatbtwntl.html

print "Hello\n";
来源：http://dali.gaohongyu789.top/Article/details/gtaflmdokq.html

[T42] Perl：变量类型
来源：http://dali.yongpay.top/Article/details/gtuqksmdru.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.hammf.cn/Article/details/gtfsyspvhb.html

[T43] Perl：字符串插值
来源：http://dali.cashguo.top/Article/details/gtgomoikfp.html

"值: $a"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvwtjpxve.html

[T44] Perl：条件
来源：http://dali.jinqigufen.top/Article/details/gtfpdpogfe.html

if ($a > 0) { print "正"; }
来源：http://dali.guannengcc.top/Article/details/gtvhjwbxzu.html


<!-- 参考信息 -->