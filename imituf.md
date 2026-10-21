代发 wailian999

cmd > out.log 2>&1
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtomcujbwo.html

[R40] 追加写日志
来源：http://dali.yonumen.top/Article/details/gtiqrdxfpe.html

echo "log" >> out.log
来源：http://dali.zdqjudy.top/Article/details/gtqjxwoypt.html

[R41] 丢弃输出
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoxxrghbg.html

cmd >/dev/null 2>&1
来源：http://dali.xinyue.icu/Article/details/gtwyzzzfqj.html

[R42] 输入重定向
来源：http://dali.aibaodan.cn/Article/details/gtjjiyubbr.html

wc -l < a.txt
来源：http://dali.iojbl.cn/Article/details/gtxeqnpdbg.html

[R43] 按名字查找文件
来源：http://dali.mhx1999.top/Article/details/gtqcpeatmj.html

find . -name "*.log" -type f
来源：http://dali.zdqjudy.top/Article/details/gtigvonqst.html

[R44] 按修改时间查找
来源：http://dali.hammf.cn/Article/details/gtpubmnssr.html

find . -mtime -7 -type f
来源：http://dali.daxiang520.top/Article/details/gtmyoictby.html

[R45] 批量删除
来源：http://dali.smart0.xyz/Article/details/gtpgikppqt.html

find . -name "*.tmp" -delete
来源：http://dali.ppjwa.cn/Article/details/gtjsqihrbd.html

[R46] 递归替换文件内容
来源：http://dali.shanyushiyangtech.top/Article/details/gtciuyjrct.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.smart0.xyz/Article/details/gthvnmwjtv.html

[R47] sed 单行替换
来源：http://dali.fzhhl.top/Article/details/gtxwzydjjy.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.xuanzx.com/Article/details/gtoybtmikw.html

[R48] awk 取指定列
来源：http://dali.aizwys.cn/Article/details/gtmajwvyhy.html

awk '{print $1, $3}' a.txt
来源：http://dali.yj20258.top/Article/details/gtglvunfzk.html

[R49] awk 带条件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmiubfpvq.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.nanxuanxn.top/Article/details/gtvitahpzj.html

[R50] awk 求和
来源：http://dali.wangdashe.top/Article/details/gtanmruvwm.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.yongpay.top/Article/details/gtazscvxwy.html

[R51] 排序去重取前几
来源：http://dali.zhoulong.xyz/Article/details/gtzlqvqzsb.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.sxryk.cn/Article/details/gtgptjowmx.html

[R52] 统计行数
来源：http://dali.snrcjt.cn/Article/details/gtduyiqlmx.html

wc -l a.txt
来源：http://dali.wangdashe.top/Article/details/gtsxqphkji.html

[R53] 查看文件头与实时尾
来源：http://dali.gzhubu.top/Article/details/gtxvfknaeo.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.yuxming.cn/Article/details/gtkwpgvafu.html

[R54] 比较两个文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtizvnllrn.html

diff a.txt b.txt
来源：http://dali.guannengcc.top/Article/details/gtfjxeiyyu.html

[R55] 压缩与解压
来源：http://dali.yanxiufei.cn/Article/details/gtyxmorqfe.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.316326.xyz/Article/details/gtjrgvtbyp.html

[R56] 远程拷贝
来源：http://dali.jqgfzy.top/Article/details/gtlguzhvuc.html

scp file user@host:/path/
来源：http://dali.chenzaomai.com/Article/details/gtckdirtlt.html

[R57] 远程执行命令
来源：http://dali.tianlin.xyz/Article/details/gtacwbgosu.html

ssh user@host 'uptime'
来源：http://dali.shzxlz.cn/Article/details/gtdmrbhjan.html

[R58] 下载文件
来源：http://dali.shuidangran.top/Article/details/gtpgrzrgwf.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.yongpay.top/Article/details/gtdmkpqvnp.html

[R59] 发 POST JSON
来源：http://dali.jqgfzy.top/Article/details/gtzkmkkojf.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.xylfe.cn/Article/details/gtzwnamvms.html

[R60] 只看 HTTP 状态码
来源：http://dali.chenzaomai.com/Article/details/gtaiqaowzt.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.sweek.top/Article/details/gtazyqfylo.html

[R61] 磁盘占用
来源：http://dali.hammf.cn/Article/details/gtcwxodlch.html

df -h;  du -sh *
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaxbdphuk.html

[R62] 找最占空间的文件
来源：http://dali.cdnleiting.top/Article/details/gtrdgtilfp.html

du -ah . | sort -rh | head -10
来源：http://dali.feifeiyinyue.top/Article/details/gtsscawlvy.html

[R63] 内存与进程
来源：http://dali.smart0.xyz/Article/details/gtymlrvuor.html

free -h;  ps aux | grep nginx
来源：http://dali.316326.xyz/Article/details/gtvjkjrmiw.html

[R64] 结束进程
来源：http://dali.nwbrower.top/Article/details/gtshetfbpv.html

kill -9 $(pgrep -f app.py)
来源：http://dali.chenjidiqi.icu/Article/details/gtqpexvtbr.html

[R65] 查看端口占用
来源：http://dali.xinyue.icu/Article/details/gtpksbzgop.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.yuanzhike.top/Article/details/gtlthuksel.html

[R66] 定时任务
来源：http://dali.gotoacloud.top/Article/details/gtedlxbruy.html

crontab -e;  crontab -l
来源：http://dali.xylfe.cn/Article/details/gtqtrzllnl.html

[R67] 生成随机十六进制串
来源：http://dali.dashuyun.cn/Article/details/gtuchrzuid.html

openssl rand -hex 16
来源：http://dali.wangshuangyany.cn/Article/details/gtmseopbcy.html

[R68] 计算文件校验值
来源：http://dali.aibaodan.cn/Article/details/gtossnoeul.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.jinqigfzy.top/Article/details/gtsxnhsjgl.html

[R69] 生成随机密码
来源：http://dali.0kj1m.cn/Article/details/gtlmwtounu.html

head -c 16 /dev/urandom | base64
来源：http://dali.xuetiantiany.cn/Article/details/gtxvavgmxv.html

[R70] 时间戳与互转
来源：http://dali.hfpthk.cn/Article/details/gtteeqjejs.html

date +%s;  date -d @1700000000
来源：http://dali.xziqi.cn/Article/details/gtfcjfhgwc.html

[R71] 日期格式化
来源：http://dali.9152youxi.cn/Article/details/gtolgynsdm.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.316326.xyz/Article/details/gtlcyieqjs.html

[R72] 等待端口就绪
来源：http://dali.quarkkingdee.top/Article/details/gtfwusmwdm.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.tian-w.cn/Article/details/gtcazohkhg.html

[R73] 分割大日志
来源：http://dali.guowangkeji.top/Article/details/gtekcdhikl.html

split -l 1000 big.log part_
来源：http://dali.tianlin.xyz/Article/details/gtlgpfffpl.html

[R74] 批量重命名
来源：http://dali.guowangkeji.top/Article/details/gtsaniusnm.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.wangdashe.top/Article/details/gtcdgrvdda.html

[R75] 导出环境变量
来源：http://dali.shanyushiyangtech.top/Article/details/gtmboszctw.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.jqgfzy.top/Article/details/gtbdoppqdq.html

[R76] 使用临时文件
来源：http://dali.wangdashe.top/Article/details/gtzfxklcby.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.gzhubu.top/Article/details/gtttjulsds.html

[R77] 读取用户输入
来源：http://dali.cucudq.cn/Article/details/gtsnvqkioi.html

read -rp "请输入: " ans
来源：http://dali.chenzaomai.com/Article/details/gtoqbopuga.html

[R78] 交互式菜单
来源：http://dali.hywenlv.cn/Article/details/gtvvyekmqs.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.andypj.xyz/Article/details/gtwifllmjf.html

[R79] 解析命令行选项
来源：http://dali.ybcxt.top/Article/details/gtmricclgh.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.cucudq.cn/Article/details/gtzixmavax.html

[R80] 查看脚本执行耗时
来源：http://dali.0kj1m.cn/Article/details/gtiqkjpfhf.html

time ./run.sh
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuyiefhim.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtxabapzlb.html

S. C / C++ 专题
来源：http://dali.hnqzz.top/Article/details/gtguqysyxn.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtsvbsgwfh.html

[S01] C：Hello World
来源：http://dali.havefunace.top/Article/details/gtylqjyftu.html

#include <stdio.h>
来源：http://dali.hnqzz.top/Article/details/gtgxakkevj.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.jianghu66.top/Article/details/gthlprjuew.html

[S02] C：变量与格式化输出
来源：http://dali.shuidangran.top/Article/details/gtlcosdtmr.html

int a = 10; printf("%d\n", a);
来源：http://dali.hongshengwenyu.top/Article/details/gtlbtlpvzb.html

[S03] C：读入整数
来源：http://dali.bjfxy.top/Article/details/gtypyzopnv.html

int x; scanf("%d", &x);
来源：http://dali.hysaishi.cn/Article/details/gtlkbvixta.html

[S04] C：字符串复制
来源：http://dali.guowangkeji.top/Article/details/gtogiqkvcq.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.hysaishi.cn/Article/details/gtzjiwkrjz.html

[S05] C：字符串长度
来源：http://dali.xinyue.icu/Article/details/gtxvgjatsm.html

strlen(s)
来源：http://dali.jqgufenzy.top/Article/details/gtgfvoypme.html

[S06] C：字符串比较
来源：http://dali.316326.xyz/Article/details/gtwotkkneu.html

strcmp(a, b) == 0
来源：http://dali.zhixingplan.top/Article/details/gtnckdsysy.html

[S07] C：数组遍历求和
来源：http://dali.shanyushiyangtech.top/Article/details/gtxzlqjtdk.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.dashuyun.cn/Article/details/gtvnloawii.html

[S08] C：动态内存分配与释放
来源：http://dali.hnxiangtu.top/Article/details/gtnqmimuma.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.fzhhl.top/Article/details/gthhpqplng.html

[S09] C：结构体定义与初始化
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmbwtwvbx.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.xinyue.icu/Article/details/gtnubhejuw.html

[S10] C：指针与解引用
来源：http://dali.ybcxt.top/Article/details/gtlziativt.html

int *p = &a;  *p = 5;
来源：http://dali.quarkkingdee.top/Article/details/gtofsxegpy.html

[S11] C：逐行读文件
来源：http://dali.gotoacloud.top/Article/details/gtxeyqmewk.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.0kj1m.cn/Article/details/gtpdxcnqyp.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.jianghu66.top/Article/details/gtweqlexzj.html

fclose(f);
来源：http://dali.daxiang520.top/Article/details/gtztikvrdj.html

[S12] C：写文件
来源：http://dali.hongshengwenyu.top/Article/details/gtcayrbdxc.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.yangfankeji.com/Article/details/gtupcnklnx.html

[S13] C：宏定义
来源：http://dali.xuetiantiany.cn/Article/details/gtqgjaigou.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.hongshengwenyu.top/Article/details/gtrvzqebhh.html

[S14] C：枚举
来源：http://dali.chenzaomai.com/Article/details/gttfqnyerb.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhongyouzk.top/Article/details/gtmdvxjgte.html

[S15] C：类型转换
来源：http://dali.0kj1m.cn/Article/details/gtnrsdnktu.html

(double) a / b
来源：http://dali.cheryme.top/Article/details/gtcyyazfte.html

[S16] C：位操作置位
来源：http://dali.ppjwa.cn/Article/details/gtmylhfeod.html

x |= (1 << 3);
来源：http://dali.hywenlv.cn/Article/details/gttomoitty.html

[S17] C：安全拼接字符串
来源：http://dali.shanyushiyangkeji.top/Article/details/gtibfrsldt.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.316326.xyz/Article/details/gtrfifihny.html

[S18] C：命令行参数
来源：http://dali.quarkkingdee.top/Article/details/gtrxezxmiq.html

int main(int argc, char **argv)
来源：http://dali.xziqi.cn/Article/details/gtqhqjxoir.html

[S19] C：快速排序
来源：http://dali.vqdsnc.cn/Article/details/gtbybiipcf.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.redwolf501.top/Article/details/gtitvvdlmm.html

[S20] C：二分查找
来源：http://dali.yj202588.top/Article/details/gtxtownrmw.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.xuetiantiany.cn/Article/details/gtbpzbulvl.html

[S21] C：字符类别判断
来源：http://dali.guowangkeji.top/Article/details/gtmgrbzqvr.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.gogol.net.cn/Article/details/gtbzyrbnlo.html

[S22] C：字符串转数字
来源：http://dali.ivvv.top/Article/details/gtpwgxwouk.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttbhusczs.html

[S23] C：随机数
来源：http://dali.nwbrower.top/Article/details/gtuldpcdcl.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhiwuduotai.top/Article/details/gtjlnlefod.html

[S24] C：获取本地时间
来源：http://dali.cqqwz.cn/Article/details/gtkrbaobtt.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.bjfxy.top/Article/details/gtuepgipor.html

[S25] C：内存拷贝
来源：http://dali.jinqigufen.top/Article/details/gtpgyiomno.html

memcpy(dst, src, n);
来源：http://dali.316326.xyz/Article/details/gtyqmtjrnz.html

[S26] C：内存清零
来源：http://dali.yj202588.top/Article/details/gtsisyxxbk.html

memset(a, 0, sizeof a);
来源：http://dali.xuetiantiany.cn/Article/details/gtqxurdzii.html

[S27] C：定义常量
来源：http://dali.yongpay.top/Article/details/gtdpzudnsf.html

const double PI = 3.14159;
来源：http://dali.svipenyu.cn/Article/details/gtwvyofhhb.html

[S28] C：静态变量
来源：http://dali.shangyingyoupin.top/Article/details/gtywwpfeff.html

static int counter = 0;
来源：http://dali.jiagoushi.top/Article/details/gtrkiqldjs.html

[S29] C：变参函数
来源：http://dali.andypj.xyz/Article/details/gtcdljhdri.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.ehwqpu.com/Article/details/gtumciuvls.html

[S30] C：头文件保护
来源：http://dali.xuanzx.com/Article/details/gtgidygums.html

#ifndef X_H
来源：http://dali.aibaodan.cn/Article/details/gtkjrfxuzo.html

#define X_H
来源：http://dali.shangyingyoupin.top/Article/details/gtejmenkec.html

#endif
来源：http://dali.dianchejie.cn/Article/details/gtapaixyjl.html

[S31] C++：Hello World
来源：http://dali.yj20258888.top/Article/details/gtczbjkiib.html

#include <iostream>
来源：http://dali.zycfv.cn/Article/details/gtfunzpyoa.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.nwbrower.top/Article/details/gtzagcxbrt.html

[S32] C++：字符串
来源：http://dali.yanxiufei.cn/Article/details/gtxuhnkgus.html

std::string s = "hi";  s += "!";
来源：http://dali.jqgufenzy.top/Article/details/gtxptpzenh.html

[S33] C++：vector 增删
来源：http://dali.yj20258888.top/Article/details/gtkgdopgzx.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.chenjidiqi.icu/Article/details/gtecygwbgm.html

[S34] C++：遍历 vector
来源：http://dali.gogol.net.cn/Article/details/gtyvneokom.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyyjiqbds.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gtegdnkaym.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.meibo888.top/Article/details/gtnnsioigh.html

[S36] C++：unordered_map
来源：http://dali.tanke756.top/Article/details/gtelgabkfj.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.316326.xyz/Article/details/gtkbncrjxy.html

[S37] C++：set
来源：http://dali.birdmap.top/Article/details/gtnhwctzid.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.kuanghao11.cn/Article/details/gtspxotoby.html

[S38] C++：排序
来源：http://dali.shanyushiyangtech.top/Article/details/gtzqfadhdh.html

std::sort(v.begin(), v.end());
来源：http://dali.jinqigufen.top/Article/details/gthybyvzeg.html

[S39] C++：自定义比较器排序
来源：http://dali.9152youxi.cn/Article/details/gtpbavgjhs.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrzgkvswk.html

[S40] C++：查找元素
来源：http://dali.daria6918.cn/Article/details/gtwoiistoy.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.shangyingyoupin.top/Article/details/gtolecczhl.html

[S41] C++：类与构造函数
来源：http://dali.daria6918.cn/Article/details/gtmkqorfpk.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.shzxlz.cn/Article/details/gtjvyytyxv.html

[S42] C++：继承与虚函数
来源：http://dali.mhx1999.top/Article/details/gtozgbrkhz.html

class B : public Base { public: void f() override {} };
来源：http://dali.ppjwa.cn/Article/details/gtwwuciezw.html

[S43] C++：智能指针
来源：http://dali.chenlongwang.top/Article/details/gtyaqaszjt.html

auto p = std::make_unique<int>(5);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvpvfdbze.html

[S44] C++：引用传参
来源：http://dali.yvedp.cn/Article/details/gtjshuuyla.html

void inc(int &x) { ++x; }
来源：http://dali.yuanzhike.top/Article/details/gtoztmmeid.html

[S45] C++：lambda
来源：http://dali.quarkkingdee.top/Article/details/gtumkkwwpx.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.nanxuanxn.top/Article/details/gtfjxmvyyi.html

[S46] C++：函数模板
来源：http://dali.wangdashe.top/Article/details/gtpuknhfym.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.wangshuangyany.cn/Article/details/gtjglvnwew.html

[S47] C++：结构化绑定遍历
来源：http://dali.hywenlv.cn/Article/details/gtpfihadgw.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.jqgfzy.top/Article/details/gthqeidavd.html

[S48] C++：逐行读文件
来源：http://dali.hammf.cn/Article/details/gtkssnezzj.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.tian-w.cn/Article/details/gtyingejbv.html

while (std::getline(in, line)) { }
来源：http://dali.nwbrower.top/Article/details/gtgvmvzcqd.html

[S49] C++：写文件
来源：http://dali.vqdsnc.cn/Article/details/gtikyyhhxv.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcgjrhjqr.html

[S50] C++：格式化数字
来源：http://dali.nanxinkj.top/Article/details/gtmmvunkop.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.yangfankeji.com/Article/details/gtcomajere.html

[S51] C++：显式类型转换
来源：http://dali.hfpthk.cn/Article/details/gttxvrdbic.html

static_cast<double>(a) / b
来源：http://dali.yangfankeji.com/Article/details/gtuncjjgoj.html

[S52] C++：const 与 noexcept
来源：http://dali.gaohongyu789.top/Article/details/gtpzmiqojv.html

int size() const noexcept { return n_; }
来源：http://dali.andypj.xyz/Article/details/gtmfaraari.html

[S53] C++：移动语义
来源：http://dali.chenzaomai.com/Article/details/gtknmolwxd.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gtdoeaqsts.html

[S54] C++：异常处理
来源：http://dali.jyoumei.cn/Article/details/gtctpvtaus.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.shanyushiyangtech.top/Article/details/gtfmlngtaf.html

[S55] C++：结构化绑定
来源：http://dali.shzxlz.cn/Article/details/gthnwcqcmj.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhoulong.xyz/Article/details/gtrizafvqg.html

[S56] C++：optional
来源：http://dali.chenjidiqi.icu/Article/details/gtcuwdqdic.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.jinqigfzy.top/Article/details/gtenuqlavc.html

[S57] C++：编译期常量
来源：http://dali.9152youxi.cn/Article/details/gtxbzxqbxv.html

constexpr int N = 10;
来源：http://dali.gzhubu.top/Article/details/gtplwkdsth.html

[S58] C++：命名空间
来源：http://dali.c1oappe.top/Article/details/gtkyfnelgi.html

namespace ns { int f() { return 1; } }
来源：http://dali.smart0.xyz/Article/details/gtjnwdrvrk.html

[S59] C++：静态断言
来源：http://dali.shzxlz.cn/Article/details/gtedvwnjxw.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.svipenyu.cn/Article/details/gtlutdtyqh.html

[S60] C++：遍历并删除元素
来源：http://dali.ybcxt.top/Article/details/gtyfmlkxer.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.yuanzhike.top/Article/details/gtwfaxwrnr.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtjaufosbz.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yvedp.cn/Article/details/gteqwlcnnl.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtwutczdjd.html

[T01] Kotlin：Hello World
来源：http://dali.zhixingplan.top/Article/details/gtwsltwpfj.html

println("Hello")
来源：http://dali.mhx1999.top/Article/details/gttqgdkjxr.html

[T02] Kotlin：变量
来源：http://dali.aizwys.cn/Article/details/gtarzrjhef.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zycfv.cn/Article/details/gtvyjupbfp.html

[T03] Kotlin：字符串模板
来源：http://dali.birdmap.top/Article/details/gtacajswez.html

"值: $b"
来源：http://dali.xziqi.cn/Article/details/gtvvejvdja.html

[T04] Kotlin：空安全
来源：http://dali.gogol.net.cn/Article/details/gtlwqezkyw.html

val n: String? = null;  n?.length
来源：http://dali.tianlin.xyz/Article/details/gtataonzwv.html

[T05] Kotlin：when 表达式
来源：http://dali.ywan-chungtsiang.top/Article/details/gtouopymvs.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.tian-w.cn/Article/details/gtlsfuqupx.html

[T06] Kotlin：集合映射
来源：http://dali.fzhhl.top/Article/details/gttlynarld.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.pengpengdd.cyou/Article/details/gtaikinrhi.html

[T07] Kotlin：集合过滤
来源：http://dali.zhongyouzk.top/Article/details/gtmhrjkpdr.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.yueranfly.top/Article/details/gtyspphchl.html

[T08] Kotlin：数据类
来源：http://dali.zdqjudy.top/Article/details/gtwtebyeiv.html

data class User(val name: String, val age: Int)
来源：http://dali.yj20258888.top/Article/details/gtoaqxxgcw.html

[T09] Kotlin：扩展函数
来源：http://dali.hfpthk.cn/Article/details/gttqsocqyx.html

fun String.exclaim() = this + "!"
来源：http://dali.zhongyouzk.top/Article/details/gtsmvuwsnx.html

[T10] Kotlin：默认参数
来源：http://dali.ivvv.top/Article/details/gtbgykulng.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.nanxuanxn.top/Article/details/gtvgyzcygc.html

[T11] Kotlin：协程
来源：http://dali.ivvv.top/Article/details/gtkupczdov.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.dashuyun.cn/Article/details/gtxizuomgo.html

[T12] Kotlin：解构声明
来源：http://dali.tanke756.top/Article/details/gtyzznskqe.html

val (a, b) = Pair(1, 2)
来源：http://dali.9152youxi.cn/Article/details/gtqxleqzeu.html

[T13] Kotlin：只读 Map
来源：http://dali.chenlongwang.top/Article/details/gtmaarzhrz.html

val m = mapOf("a" to 1)
来源：http://dali.ehwqpu.com/Article/details/gtneocrqim.html

[T14] Kotlin：循环
来源：http://dali.zhongyouzk.top/Article/details/gtoonubqfh.html

for (i in 1..10) println(i)
来源：http://dali.yueranfly.top/Article/details/gtzeemsjsv.html

[T15] Kotlin：接口
来源：http://dali.svipenyu.cn/Article/details/gtstfhwvuq.html

interface Shape { fun area(): Double }
来源：http://dali.shanyushiyangtech.top/Article/details/gtgkysnrue.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gtlxfajugk.html

print("Hello")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmajyeuea.html

[T17] Swift：变量与常量
来源：http://dali.zhongyouzk.top/Article/details/gtyjfmfemz.html

var a = 1;  let b = 2
来源：http://dali.bjfxy.top/Article/details/gtaawxyfem.html

[T18] Swift：字符串插值
来源：http://dali.jianghu66.top/Article/details/gtuxnnlmix.html

"值: \(b)"
来源：http://dali.zhoulong.xyz/Article/details/gtwqicafgc.html

[T19] Swift：可选绑定
来源：http://dali.zhengqikj.top/Article/details/gtlpcvwhax.html

if let n = opt { print(n) }
来源：http://dali.yuanzhike.top/Article/details/gtmsjqhqbp.html

[T20] Swift：数组操作
来源：http://dali.yj202588.top/Article/details/gtkfhbiwmd.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.sxryk.cn/Article/details/gtuubkehcf.html

[T21] Swift：遍历
来源：http://dali.chenjidiqi.icu/Article/details/gtcpvljfvz.html

for x in a { print(x) }
来源：http://dali.chenjidiqi.icu/Article/details/gtdxxajopv.html

[T22] Swift：字典
来源：http://dali.daxiang520.top/Article/details/gttwoocifu.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.cucudq.cn/Article/details/gthhirebig.html

[T23] Swift：函数
来源：http://dali.nanxuanxn.top/Article/details/gtwhhdcosw.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.redwolf501.top/Article/details/gtkxmmdjnt.html

[T24] Swift：闭包
来源：http://dali.yuxming.cn/Article/details/gtxyvqknxt.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.dianchejie.cn/Article/details/gtmonduryq.html

[T25] Swift：结构体
来源：http://dali.haohaochexian.top/Article/details/gtwixkdivy.html

struct P { var x: Int }
来源：http://dali.pengpengdd.cyou/Article/details/gthyrpeagy.html

[T26] Swift：类与重写
来源：http://dali.ppjwa.cn/Article/details/gtjkcrtqve.html

class A: Base { override func f() {} }
来源：http://dali.dianchejie.cn/Article/details/gtpyjxuqiy.html

[T27] Swift：错误处理
来源：http://dali.tian-w.cn/Article/details/gtqnryrmjg.html

do { try f() } catch { print(error) }
来源：http://dali.bjfxy.top/Article/details/gtbkrdglzn.html

[T28] Swift：枚举
来源：http://dali.redwolf501.top/Article/details/gtphfsgzdw.html

enum Color { case red, green }
来源：http://dali.nwbrower.top/Article/details/gtxuvvdbav.html

[T29] Swift：guard 提前返回
来源：http://dali.hfpthk.cn/Article/details/gtuustqwxv.html

guard let x = opt else { return }
来源：http://dali.ehwqpu.com/Article/details/gtzogbfsyx.html

[T30] Swift：协议
来源：http://dali.9152youxi.cn/Article/details/gtvxvhqtpr.html

protocol Shape { func area() -> Double }
来源：http://dali.jqgufenzy.top/Article/details/gtogoefcrt.html

[T31] Lua：Hello World
来源：http://dali.sysykeji.top/Article/details/gtokbihxds.html

print("Hello")
来源：http://dali.zhongyouzk.top/Article/details/gtqdejoohe.html

[T32] Lua：局部变量
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnrqrhacd.html

local a = 1
来源：http://dali.jinqigfzy.top/Article/details/gtsacrxjjv.html

[T33] Lua：表（数组）
来源：http://dali.yonumen.top/Article/details/gtqsofirvc.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.jinqigufen.top/Article/details/gtbcjgnoce.html

[T34] Lua：遍历表
来源：http://dali.gaohongyu789.top/Article/details/gtokvnbvyr.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zdqjudy.top/Article/details/gtnmfhibbv.html

[T35] Lua：字典表
来源：http://dali.nanxinkj.top/Article/details/gtkgyllnfg.html

local d = { a = 1 };  d.b = 2
来源：http://dali.fengsongda.top/Article/details/gtjftfifxd.html

[T36] Lua：函数
来源：http://dali.sysykeji.top/Article/details/gtztzjoldc.html

function add(a, b) return a + b end
来源：http://dali.xziqi.cn/Article/details/gtkiwiqqip.html

[T37] Lua：字符串拼接
来源：http://dali.wangdashe.top/Article/details/gtjhigckjo.html

"a" .. "b"
来源：http://dali.svipenyu.cn/Article/details/gtekyratnz.html

[T38] Lua：条件
来源：http://dali.daxiang520.top/Article/details/gtfloezcax.html

if x > 0 then print("正") end
来源：http://dali.sweek.top/Article/details/gthoczmysc.html

[T39] Lua：模式匹配
来源：http://dali.sweek.top/Article/details/gtdgwzypcz.html

string.find(s, "%d+")
来源：http://dali.wangshuangyany.cn/Article/details/gtfqwpkboe.html

[T40] Lua：元表
来源：http://dali.pycfn.com/Article/details/gtcwgjunnc.html

setmetatable({}, { __index = base })
来源：http://dali.havefunace.top/Article/details/gtakwurcnq.html

[T41] Perl：Hello World
来源：http://dali.zhengqikj.top/Article/details/gtnhcbtjcd.html

print "Hello\n";
来源：http://dali.hammf.cn/Article/details/gtuzvebsde.html

[T42] Perl：变量类型
来源：http://dali.svipenyu.cn/Article/details/gtuqzruwxe.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.cashguo.top/Article/details/gtvwtedsqy.html


<!-- 参考信息 -->