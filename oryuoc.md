代发 wailian999

cmd >/dev/null 2>&1
来源：http://dali.zhixingplan.top/Article/details/gt2vqbvhnrg.html

[R42] 输入重定向
来源：http://dali.jianghu66.top/Article/details/gt2zzknefpj.html

wc -l < a.txt
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dxbnfyva.html

[R43] 按名字查找文件
来源：http://dali.xinyue.icu/Article/details/gt2paowvtyo.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2rwcaovfx.html

[R44] 按修改时间查找
来源：http://dali.nanxuanxn.top/Article/details/gt2ujsbmpeq.html

find . -mtime -7 -type f
来源：http://dali.jianghu66.top/Article/details/gt2humdbzmv.html

[R45] 批量删除
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zdkhlatp.html

find . -name "*.tmp" -delete
来源：http://dali.aibaodan.cn/Article/details/gt2qsuncddy.html

[R46] 递归替换文件内容
来源：http://dali.hnqzz.top/Article/details/gt2whdfdlxc.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.xuetiantiany.cn/Article/details/gt2hlejgayu.html

[R47] sed 单行替换
来源：http://dali.cashguo.top/Article/details/gt2hglbybfx.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.bjfxy.top/Article/details/gt2rxyiojjx.html

[R48] awk 取指定列
来源：http://dali.cucudq.cn/Article/details/gt2wlfytlrq.html

awk '{print $1, $3}' a.txt
来源：http://dali.hfpthk.cn/Article/details/gt2mmaesfwb.html

[R49] awk 带条件
来源：http://dali.fzhhl.top/Article/details/gt2lqdgrsar.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.shuidangran.top/Article/details/gt2stmnxabn.html

[R50] awk 求和
来源：http://dali.zdqjudy.top/Article/details/gt2kmfgedde.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.yuxming.cn/Article/details/gt2vwcyohwx.html

[R51] 排序去重取前几
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jfufiutt.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.iojbl.cn/Article/details/gt2vfdfnzxs.html

[R52] 统计行数
来源：http://dali.aibaodan.cn/Article/details/gt2dsuacrxy.html

wc -l a.txt
来源：http://dali.316326.xyz/Article/details/gt2ohvyqyvh.html

[R53] 查看文件头与实时尾
来源：http://dali.sxryk.cn/Article/details/gt2cofwkrcw.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhengqikj.top/Article/details/gt2rtojdjhf.html

[R54] 比较两个文件
来源：http://dali.yueranfly.top/Article/details/gt2bponscub.html

diff a.txt b.txt
来源：http://dali.ydzc1.top/Article/details/gt2cimdtxpc.html

[R55] 压缩与解压
来源：http://dali.nwbrower.top/Article/details/gt2veyefbuq.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.nwbrower.top/Article/details/gt2frmxxnmc.html

[R56] 远程拷贝
来源：http://dali.yj20258888.top/Article/details/gt2dgclpwkm.html

scp file user@host:/path/
来源：http://dali.hywenlv.cn/Article/details/gt2lehrxmtn.html

[R57] 远程执行命令
来源：http://dali.tanke756.top/Article/details/gt2zrqbkwkn.html

ssh user@host 'uptime'
来源：http://dali.xuetiantiany.cn/Article/details/gt2kzwexugd.html

[R58] 下载文件
来源：http://dali.ehwqpu.com/Article/details/gt2azxbwffy.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.hywenlv.cn/Article/details/gt2xpxqdqve.html

[R59] 发 POST JSON
来源：http://dali.ppjwa.cn/Article/details/gt2cbzxmdmb.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.yueranfly.top/Article/details/gt2tdrsaugb.html

[R60] 只看 HTTP 状态码
来源：http://dali.yvedp.cn/Article/details/gt2rbuyqtlt.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.shuidangran.top/Article/details/gt2xbmepdzq.html

[R61] 磁盘占用
来源：http://dali.svipenyu.cn/Article/details/gt2vruwduyp.html

df -h;  du -sh *
来源：http://dali.snrcjt.cn/Article/details/gt2hjxzaqas.html

[R62] 找最占空间的文件
来源：http://dali.yangfankeji.com/Article/details/gt2rrkfiiym.html

du -ah . | sort -rh | head -10
来源：http://dali.shangyingyoupin.top/Article/details/gt2rizvdmuu.html

[R63] 内存与进程
来源：http://dali.sxryk.cn/Article/details/gt2kwwtwvqx.html

free -h;  ps aux | grep nginx
来源：http://dali.sufxvd.cn/Article/details/gt2bwpopkll.html

[R64] 结束进程
来源：http://dali.yongpay.top/Article/details/gt2knomqctd.html

kill -9 $(pgrep -f app.py)
来源：http://dali.sxryk.cn/Article/details/gt2lbbfrphe.html

[R65] 查看端口占用
来源：http://dali.ppjwa.cn/Article/details/gt2xkihmovq.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.shangyingyoupin.top/Article/details/gt2edvfwdah.html

[R66] 定时任务
来源：http://dali.snrcjt.cn/Article/details/gt2itjcdzbu.html

crontab -e;  crontab -l
来源：http://dali.dianchejie.cn/Article/details/gt2epdppawu.html

[R67] 生成随机十六进制串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lxkzdnhm.html

openssl rand -hex 16
来源：http://dali.andypj.xyz/Article/details/gt2hxnjtroi.html

[R68] 计算文件校验值
来源：http://dali.svipenyu.cn/Article/details/gt2qcmfxltv.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.yj202588.top/Article/details/gt2cdzsqivn.html

[R69] 生成随机密码
来源：http://dali.fzhhl.top/Article/details/gt2riobqsjl.html

head -c 16 /dev/urandom | base64
来源：http://dali.jqgufenzy.top/Article/details/gt2imeqbvjk.html

[R70] 时间戳与互转
来源：http://dali.mhx1999.top/Article/details/gt2lyrunehm.html

date +%s;  date -d @1700000000
来源：http://dali.nanxinkj.top/Article/details/gt2ifbhwluw.html

[R71] 日期格式化
来源：http://dali.havefunace.top/Article/details/gt2agsgcgiw.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.hnxiangtu.top/Article/details/gt2dgbvvlkl.html

[R72] 等待端口就绪
来源：http://dali.jqgufenzy.top/Article/details/gt2cyeeutrv.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.jiagoushi.top/Article/details/gt2xgorlgcz.html

[R73] 分割大日志
来源：http://dali.nwbrower.top/Article/details/gt2ekzeftxl.html

split -l 1000 big.log part_
来源：http://dali.gogol.net.cn/Article/details/gt2vewedxsx.html

[R74] 批量重命名
来源：http://dali.cdnleiting.top/Article/details/gt2rhrtvany.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.0kj1m.cn/Article/details/gt2dahytyml.html

[R75] 导出环境变量
来源：http://dali.nanxuanxn.top/Article/details/gt2jjpyvqth.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.smart0.xyz/Article/details/gt2otzwqvks.html

[R76] 使用临时文件
来源：http://dali.yj20258888.top/Article/details/gt2gmlezkdw.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.cdnleiting.top/Article/details/gt2rumrkbzi.html

[R77] 读取用户输入
来源：http://dali.dianchejie.cn/Article/details/gt2prisgddr.html

read -rp "请输入: " ans
来源：http://dali.guannengcc.top/Article/details/gt2yhwpnyyl.html

[R78] 交互式菜单
来源：http://dali.gogol.net.cn/Article/details/gt2gaamefqp.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.xuetiantiany.cn/Article/details/gt2cswgwhbo.html

[R79] 解析命令行选项
来源：http://dali.shuidangran.top/Article/details/gt2heuszmzs.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tnrfjypf.html

[R80] 查看脚本执行耗时
来源：http://dali.yonumen.top/Article/details/gt2hpigpfxk.html

time ./run.sh
来源：http://dali.wangshuangyany.cn/Article/details/gt2bmyqwfcb.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gt2jhyktvvr.html

S. C / C++ 专题
来源：http://dali.xinyue.icu/Article/details/gt2zyuwuguz.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2kwqeldow.html

[S01] C：Hello World
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zglxifvg.html

#include <stdio.h>
来源：http://dali.jqgufenzy.top/Article/details/gt2bhkqpldh.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.cucudq.cn/Article/details/gt2tkxwrqtq.html

[S02] C：变量与格式化输出
来源：http://dali.ppjwa.cn/Article/details/gt2fkgleawa.html

int a = 10; printf("%d\n", a);
来源：http://dali.havefunace.top/Article/details/gt2orlwcstx.html

[S03] C：读入整数
来源：http://dali.hammf.cn/Article/details/gt2dsudnxny.html

int x; scanf("%d", &x);
来源：http://dali.9152youxi.cn/Article/details/gt2zpsxftcw.html

[S04] C：字符串复制
来源：http://dali.smart0.xyz/Article/details/gt2iwtrqhdp.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.yj202588.top/Article/details/gt2mcezcwkv.html

[S05] C：字符串长度
来源：http://dali.ivvv.top/Article/details/gt2slmgofjf.html

strlen(s)
来源：http://dali.xylfe.cn/Article/details/gt2ogztwfdg.html

[S06] C：字符串比较
来源：http://dali.snrcjt.cn/Article/details/gt2igkjuprf.html

strcmp(a, b) == 0
来源：http://dali.ppjwa.cn/Article/details/gt2tprgawod.html

[S07] C：数组遍历求和
来源：http://dali.jianghu66.top/Article/details/gt2gssngytc.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.ybcxt.top/Article/details/gt2obuomgen.html

[S08] C：动态内存分配与释放
来源：http://dali.wangdashe.top/Article/details/gt2rhkcisln.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.guannengcc.top/Article/details/gt2jnmfmysq.html

[S09] C：结构体定义与初始化
来源：http://dali.yj20258888.top/Article/details/gt2afxlfphc.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.tian-w.cn/Article/details/gt2bcwpcyiq.html

[S10] C：指针与解引用
来源：http://dali.tanke756.top/Article/details/gt2rjayrkzs.html

int *p = &a;  *p = 5;
来源：http://dali.xuetiantiany.cn/Article/details/gt2sfacgjir.html

[S11] C：逐行读文件
来源：http://dali.yongpay.top/Article/details/gt2zynotvyo.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.cucudq.cn/Article/details/gt2jzlgtxxs.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.ehwqpu.com/Article/details/gt2exjbnxic.html

fclose(f);
来源：http://dali.meibo888.top/Article/details/gt2yzbfmcif.html

[S12] C：写文件
来源：http://dali.shuidangran.top/Article/details/gt2xjcfblhw.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.havefunace.top/Article/details/gt2gmvgfffi.html

[S13] C：宏定义
来源：http://dali.mhx1999.top/Article/details/gt2swrypgmh.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.fzhhl.top/Article/details/gt2thbtxorm.html

[S14] C：枚举
来源：http://dali.nanxinkj.top/Article/details/gt2isietsdo.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.cashguo.top/Article/details/gt2byasijye.html

[S15] C：类型转换
来源：http://dali.iojbl.cn/Article/details/gt2lyiruvgi.html

(double) a / b
来源：http://dali.fzhhl.top/Article/details/gt2vvpggkyb.html

[S16] C：位操作置位
来源：http://dali.pengpengdd.cyou/Article/details/gt2lmarffje.html

x |= (1 << 3);
来源：http://dali.xinyue.icu/Article/details/gt2hvyeyaud.html

[S17] C：安全拼接字符串
来源：http://dali.gotoacloud.top/Article/details/gt2thguigkp.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.yangfankeji.com/Article/details/gt2esumarwf.html

[S18] C：命令行参数
来源：http://dali.fengsongda.top/Article/details/gt2lfxsshyi.html

int main(int argc, char **argv)
来源：http://dali.jinqigufen.top/Article/details/gt2viwhyulz.html

[S19] C：快速排序
来源：http://dali.hammf.cn/Article/details/gt2ymxncuwr.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.0kj1m.cn/Article/details/gt2mulnoews.html

[S20] C：二分查找
来源：http://dali.jianghu66.top/Article/details/gt2mnnbguag.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.sysykeji.top/Article/details/gt2nuseokuf.html

[S21] C：字符类别判断
来源：http://dali.haohaochexian.top/Article/details/gt2zhegjuxq.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.aibaodan.cn/Article/details/gt2envwtvcg.html

[S22] C：字符串转数字
来源：http://dali.gaohongyu789.top/Article/details/gt2xingxzsq.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.shangyingyoupin.top/Article/details/gt2ntnzmzhy.html

[S23] C：随机数
来源：http://dali.9152youxi.cn/Article/details/gt2iejhkijk.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zdqjudy.top/Article/details/gt2oubrgwrz.html

[S24] C：获取本地时间
来源：http://dali.ivvv.top/Article/details/gt2lfszmjpv.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.wangshuangyany.cn/Article/details/gt2ifpekqwv.html

[S25] C：内存拷贝
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lyxqepjk.html

memcpy(dst, src, n);
来源：http://dali.snrcjt.cn/Article/details/gt2avfhsypr.html

[S26] C：内存清零
来源：http://dali.snrcjt.cn/Article/details/gt2bklvkzyn.html

memset(a, 0, sizeof a);
来源：http://dali.daxiang520.top/Article/details/gt2cpvmxrhu.html

[S27] C：定义常量
来源：http://dali.zhoulong.xyz/Article/details/gt2ainhjcpr.html

const double PI = 3.14159;
来源：http://dali.0kj1m.cn/Article/details/gt2jhjbxorv.html

[S28] C：静态变量
来源：http://dali.ydzc1.top/Article/details/gt2pgekgnuq.html

static int counter = 0;
来源：http://dali.zhiwuduotai.top/Article/details/gt2jlorfzrx.html

[S29] C：变参函数
来源：http://dali.yj20258.top/Article/details/gt2xpqqeyqy.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.nanxuanxn.top/Article/details/gt2xwhfeluy.html

[S30] C：头文件保护
来源：http://dali.guowangkeji.top/Article/details/gt2yeayghog.html

#ifndef X_H
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uzecvjji.html

#define X_H
来源：http://dali.pycfn.com/Article/details/gt2mxcxnvea.html

#endif
来源：http://dali.fzhhl.top/Article/details/gt2bauygqqf.html

[S31] C++：Hello World
来源：http://dali.nanxuanxn.top/Article/details/gt2xdriooak.html

#include <iostream>
来源：http://dali.316326.xyz/Article/details/gt2cogxplvz.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.daria6918.cn/Article/details/gt2sgokrvto.html

[S32] C++：字符串
来源：http://dali.wangshuangyany.cn/Article/details/gt2tlkizthe.html

std::string s = "hi";  s += "!";
来源：http://dali.yj20258.top/Article/details/gt2aandxqbf.html

[S33] C++：vector 增删
来源：http://dali.yanxiufei.cn/Article/details/gt2dgdylnvc.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.svipenyu.cn/Article/details/gt2svcgnayp.html

[S34] C++：遍历 vector
来源：http://dali.xuetiantiany.cn/Article/details/gt2lfdlqqyn.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2imgzqbuu.html

[S35] C++：map
来源：http://dali.ppjwa.cn/Article/details/gt2lwnklltd.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jyoumei.cn/Article/details/gt2fpkjeush.html

[S36] C++：unordered_map
来源：http://dali.aizwys.cn/Article/details/gt2duouvqfd.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.guannengcc.top/Article/details/gt2urspvktj.html

[S37] C++：set
来源：http://dali.tian-w.cn/Article/details/gt2wmmlpezj.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.xuetiantiany.cn/Article/details/gt2jeefdhdw.html

[S38] C++：排序
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ixbastns.html

std::sort(v.begin(), v.end());
来源：http://dali.havefunace.top/Article/details/gt2vogsopir.html

[S39] C++：自定义比较器排序
来源：http://dali.kuanghao11.cn/Article/details/gt2tczqjrgk.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.wangdashe.top/Article/details/gt2ijttvaqk.html

[S40] C++：查找元素
来源：http://dali.quarkkingdee.top/Article/details/gt2oydlvmbm.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.dianchejie.cn/Article/details/gt2hiikhqgv.html

[S41] C++：类与构造函数
来源：http://dali.cqqwz.cn/Article/details/gt2emjmwiut.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.xylfe.cn/Article/details/gt2cscdcisv.html

[S42] C++：继承与虚函数
来源：http://dali.c1oappe.top/Article/details/gt2qlzvrvxg.html

class B : public Base { public: void f() override {} };
来源：http://dali.snrcjt.cn/Article/details/gt2zhfwnjvv.html

[S43] C++：智能指针
来源：http://dali.ydzc1.top/Article/details/gt2qmbxtjel.html

auto p = std::make_unique<int>(5);
来源：http://dali.feifeiyinyue.top/Article/details/gt2xhsahqgn.html

[S44] C++：引用传参
来源：http://dali.andypj.xyz/Article/details/gt2hahxsnkr.html

void inc(int &x) { ++x; }
来源：http://dali.shzxlz.cn/Article/details/gt2ymyshrzc.html

[S45] C++：lambda
来源：http://dali.shangyingyoupin.top/Article/details/gt2znkzofgn.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nzmrlaro.html

[S46] C++：函数模板
来源：http://dali.hnqzz.top/Article/details/gt2wllhkavj.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.tianlin.xyz/Article/details/gt2byaxskdd.html

[S47] C++：结构化绑定遍历
来源：http://dali.316326.xyz/Article/details/gt2xccqeuqp.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.jlsjyb.cn/Article/details/gt2cwirhpsf.html

[S48] C++：逐行读文件
来源：http://dali.dianchejie.cn/Article/details/gt2ulavmydb.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.chenlongwang.top/Article/details/gt2logdpura.html

while (std::getline(in, line)) { }
来源：http://dali.xziqi.cn/Article/details/gt2ojbmrkzs.html

[S49] C++：写文件
来源：http://dali.sweek.top/Article/details/gt2cvvvssve.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fqqubazi.html

[S50] C++：格式化数字
来源：http://dali.yuxming.cn/Article/details/gt2accswyeo.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.aizwys.cn/Article/details/gt2sygccrat.html

[S51] C++：显式类型转换
来源：http://dali.chenjidiqi.icu/Article/details/gt2wnwhqkjw.html

static_cast<double>(a) / b
来源：http://dali.ehwqpu.com/Article/details/gt2pkoouyht.html

[S52] C++：const 与 noexcept
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ooizwikx.html

int size() const noexcept { return n_; }
来源：http://dali.cucudq.cn/Article/details/gt2qbegbmyh.html

[S53] C++：移动语义
来源：http://dali.cashguo.top/Article/details/gt2lfshbhou.html

std::vector<int> w = std::move(v);
来源：http://dali.yuxming.cn/Article/details/gt2tknbkadb.html

[S54] C++：异常处理
来源：http://dali.guowangkeji.top/Article/details/gt2ohmilxqx.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.chenzaomai.com/Article/details/gt2ivgrzanm.html

[S55] C++：结构化绑定
来源：http://dali.jqgufenzy.top/Article/details/gt2qchsohuo.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.wangshuangyany.cn/Article/details/gt2kbxpygwg.html

[S56] C++：optional
来源：http://dali.jqgfzy.top/Article/details/gt2eqwfuocn.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yvedp.cn/Article/details/gt2hpagmgsw.html

[S57] C++：编译期常量
来源：http://dali.yuanzhike.top/Article/details/gt2mzxwdoze.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2otyrbhvn.html

[S58] C++：命名空间
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tzcemurl.html

namespace ns { int f() { return 1; } }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2awrnljqj.html

[S59] C++：静态断言
来源：http://dali.jlsjyb.cn/Article/details/gt2ibvxchkn.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.sysykeji.top/Article/details/gt2ubgdnewq.html

[S60] C++：遍历并删除元素
来源：http://dali.fzhhl.top/Article/details/gt2psvkckbo.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.bjfxy.top/Article/details/gt2xrhmuwvx.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gt2ozlrtjyg.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.xylfe.cn/Article/details/gt2kkasmnuw.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gt2jhccgyyq.html

[T01] Kotlin：Hello World
来源：http://dali.gzhubu.top/Article/details/gt2hzavztar.html

println("Hello")
来源：http://dali.cheryme.top/Article/details/gt2yaofoydg.html

[T02] Kotlin：变量
来源：http://dali.kuanghao11.cn/Article/details/gt2oaditjuk.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.jinghuilouyu.cn/Article/details/gt2axqalfwc.html

[T03] Kotlin：字符串模板
来源：http://dali.havefunace.top/Article/details/gt2wjuijvyi.html

"值: $b"
来源：http://dali.nanxinkj.top/Article/details/gt2rbiuckzq.html

[T04] Kotlin：空安全
来源：http://dali.tanke756.top/Article/details/gt2eamebfmf.html

val n: String? = null;  n?.length
来源：http://dali.jyoumei.cn/Article/details/gt2bjwfcsgw.html

[T05] Kotlin：when 表达式
来源：http://dali.jinqigfzy.top/Article/details/gt2hzajkfjv.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2itohqajf.html

[T06] Kotlin：集合映射
来源：http://dali.zycfv.cn/Article/details/gt2wvbcjfzz.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.nanxuanxn.top/Article/details/gt2gdyxutzb.html

[T07] Kotlin：集合过滤
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ahcpkoal.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.havefunace.top/Article/details/gt2txmttzqu.html

[T08] Kotlin：数据类
来源：http://dali.cashguo.top/Article/details/gt2dclnghoz.html

data class User(val name: String, val age: Int)
来源：http://dali.xinyue.icu/Article/details/gt2jcudozkr.html

[T09] Kotlin：扩展函数
来源：http://dali.xylfe.cn/Article/details/gt2skgdyidl.html

fun String.exclaim() = this + "!"
来源：http://dali.hnqzz.top/Article/details/gt2yanchngf.html

[T10] Kotlin：默认参数
来源：http://dali.cqqwz.cn/Article/details/gt2dmejptcq.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.sysykeji.top/Article/details/gt2mxfkcbgy.html

[T11] Kotlin：协程
来源：http://dali.aibaodan.cn/Article/details/gt2jgsasdxs.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.snrcjt.cn/Article/details/gt2ydqxrpex.html

[T12] Kotlin：解构声明
来源：http://dali.sufxvd.cn/Article/details/gt2nqiuaglt.html

val (a, b) = Pair(1, 2)
来源：http://dali.meibo888.top/Article/details/gt2zxkeiewx.html

[T13] Kotlin：只读 Map
来源：http://dali.vqdsnc.cn/Article/details/gt2jmpdhfjm.html

val m = mapOf("a" to 1)
来源：http://dali.jyoumei.cn/Article/details/gt2lxnsatwo.html

[T14] Kotlin：循环
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2aomxxsjj.html

for (i in 1..10) println(i)
来源：http://dali.xuetiantiany.cn/Article/details/gt2hdphqliw.html

[T15] Kotlin：接口
来源：http://dali.zhoulong.xyz/Article/details/gt2gzrghjrq.html

interface Shape { fun area(): Double }
来源：http://dali.yueranfly.top/Article/details/gt2fqqisjyc.html

[T16] Swift：Hello World
来源：http://dali.sysykeji.top/Article/details/gt2honfqwls.html

print("Hello")
来源：http://dali.quarkkingdee.top/Article/details/gt2qvlekdje.html

[T17] Swift：变量与常量
来源：http://dali.chenzaomai.com/Article/details/gt2vdzuvtxb.html

var a = 1;  let b = 2
来源：http://dali.cucudq.cn/Article/details/gt2ecsfhmal.html

[T18] Swift：字符串插值
来源：http://dali.aibaodan.cn/Article/details/gt2hkgstkxu.html

"值: \(b)"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zhpaygki.html

[T19] Swift：可选绑定
来源：http://dali.wangdashe.top/Article/details/gt2mzhszxxe.html

if let n = opt { print(n) }
来源：http://dali.redwolf501.top/Article/details/gt2rjgqxntg.html

[T20] Swift：数组操作
来源：http://dali.hnqzz.top/Article/details/gt2wlyrwkge.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.jlsjyb.cn/Article/details/gt2ktrziyvd.html

[T21] Swift：遍历
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nnnrxtmk.html

for x in a { print(x) }
来源：http://dali.jinqigfzy.top/Article/details/gt2gebciduq.html

[T22] Swift：字典
来源：http://dali.gotoacloud.top/Article/details/gt2ngsmrkmh.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.smart0.xyz/Article/details/gt2pzuspwgz.html

[T23] Swift：函数
来源：http://dali.haohaochexian.top/Article/details/gt2vjwvrzej.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.tianlin.xyz/Article/details/gt2qihcpnkz.html

[T24] Swift：闭包
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pqkhlgri.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhoulong.xyz/Article/details/gt2ujwwmzzr.html

[T25] Swift：结构体
来源：http://dali.tanke756.top/Article/details/gt2rietdnou.html

struct P { var x: Int }
来源：http://dali.yj20258.top/Article/details/gt2jetfayuc.html

[T26] Swift：类与重写
来源：http://dali.shzxlz.cn/Article/details/gt2ohykemzu.html

class A: Base { override func f() {} }
来源：http://dali.sufxvd.cn/Article/details/gt2spprzvna.html

[T27] Swift：错误处理
来源：http://dali.wangdashe.top/Article/details/gt2tydlesth.html

do { try f() } catch { print(error) }
来源：http://dali.chenjidiqi.icu/Article/details/gt2mpiramsf.html

[T28] Swift：枚举
来源：http://dali.zdqjudy.top/Article/details/gt2ccxqnwon.html

enum Color { case red, green }
来源：http://dali.fzhhl.top/Article/details/gt2ingqxvyr.html

[T29] Swift：guard 提前返回
来源：http://dali.yuxming.cn/Article/details/gt2ewigxjms.html

guard let x = opt else { return }
来源：http://dali.xuanzx.com/Article/details/gt2pubfxpvd.html

[T30] Swift：协议
来源：http://dali.svipenyu.cn/Article/details/gt2mgoxackb.html

protocol Shape { func area() -> Double }
来源：http://dali.shzxlz.cn/Article/details/gt2rxkljeao.html

[T31] Lua：Hello World
来源：http://dali.pengpengdd.cyou/Article/details/gt2lnqebbfb.html

print("Hello")
来源：http://dali.hysaishi.cn/Article/details/gt2kbdbsgua.html

[T32] Lua：局部变量
来源：http://dali.jinqigufen.top/Article/details/gt2zfxpzwqx.html

local a = 1
来源：http://dali.hammf.cn/Article/details/gt2lkjbbvqv.html

[T33] Lua：表（数组）
来源：http://dali.xylfe.cn/Article/details/gt2qoggyxhe.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2oeegpwyl.html

[T34] Lua：遍历表
来源：http://dali.jinqigufen.top/Article/details/gt2mzqgdlxl.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.xinyue.icu/Article/details/gt2tgpppddx.html

[T35] Lua：字典表
来源：http://dali.cucudq.cn/Article/details/gt2pgbhlyej.html

local d = { a = 1 };  d.b = 2
来源：http://dali.vqdsnc.cn/Article/details/gt2ieatsjfn.html

[T36] Lua：函数
来源：http://dali.feifeiyinyue.top/Article/details/gt2jtmaygdc.html

function add(a, b) return a + b end
来源：http://dali.gogol.net.cn/Article/details/gt2iwjwikwk.html

[T37] Lua：字符串拼接
来源：http://dali.zhoulong.xyz/Article/details/gt2zcvseoka.html

"a" .. "b"
来源：http://dali.vqdsnc.cn/Article/details/gt2woiycqxu.html

[T38] Lua：条件
来源：http://dali.birdmap.top/Article/details/gt2tebfseab.html

if x > 0 then print("正") end
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bkujfroz.html

[T39] Lua：模式匹配
来源：http://dali.jqgufenzy.top/Article/details/gt2fgdelhgm.html

string.find(s, "%d+")
来源：http://dali.hnxiangtu.top/Article/details/gt2pamqxugy.html

[T40] Lua：元表
来源：http://dali.zhoulong.xyz/Article/details/gt2dkqydsbf.html

setmetatable({}, { __index = base })
来源：http://dali.cqqwz.cn/Article/details/gt2hgkbqojz.html

[T41] Perl：Hello World
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zeepibtr.html

print "Hello\n";
来源：http://dali.yangfankeji.com/Article/details/gt2kbaabgrf.html

[T42] Perl：变量类型
来源：http://dali.xziqi.cn/Article/details/gt2ovewbcqd.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.fzhhl.top/Article/details/gt2pnhmpscl.html

[T43] Perl：字符串插值
来源：http://dali.zhiwuduotai.top/Article/details/gt2vsyrptqq.html

"值: $a"
来源：http://dali.zycfv.cn/Article/details/gt2crnnhcsu.html

[T44] Perl：条件
来源：http://dali.chenzaomai.com/Article/details/gt2lzbtkqni.html

if ($a > 0) { print "正"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vmpsgnfz.html


<!-- 参考信息 -->