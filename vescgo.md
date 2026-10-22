代发 wailian999

find . -name "*.tmp" -delete
来源：http://dali.yj202588.top/Article/details/gt2hwddlwvd.html

[R46] 递归替换文件内容
来源：http://dali.meibo888.top/Article/details/gt2uejmfrzc.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhongyouzk.top/Article/details/gt2abgeygcx.html

[R47] sed 单行替换
来源：http://dali.jinqigfzy.top/Article/details/gt2mzmwipsw.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.hongshengwenyu.top/Article/details/gt2hjztancw.html

[R48] awk 取指定列
来源：http://dali.yuanzhike.top/Article/details/gt2wqdqwuvu.html

awk '{print $1, $3}' a.txt
来源：http://dali.yvedp.cn/Article/details/gt2ovltvyqf.html

[R49] awk 带条件
来源：http://dali.hnqzz.top/Article/details/gt2elpvurjw.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.yangfankeji.com/Article/details/gt2fujrcwbk.html

[R50] awk 求和
来源：http://dali.sweek.top/Article/details/gt2kpjdgzja.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.jqgufenzy.top/Article/details/gt2kknqlhuv.html

[R51] 排序去重取前几
来源：http://dali.zhoulong.xyz/Article/details/gt2capabkoc.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.redwolf501.top/Article/details/gt2vdnsqkwz.html

[R52] 统计行数
来源：http://dali.jinghuilouyu.cn/Article/details/gt2iprrwcbm.html

wc -l a.txt
来源：http://dali.zhixingplan.top/Article/details/gt2vvsestre.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2yzgoczef.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.gotoacloud.top/Article/details/gt2xwbhcerj.html

[R54] 比较两个文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gztmprbh.html

diff a.txt b.txt
来源：http://dali.zdqjudy.top/Article/details/gt2etqlwmef.html

[R55] 压缩与解压
来源：http://dali.shzxlz.cn/Article/details/gt2hxliwewf.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.jqgufenzy.top/Article/details/gt2tqebdahz.html

[R56] 远程拷贝
来源：http://dali.ehwqpu.com/Article/details/gt2tgmeuwjw.html

scp file user@host:/path/
来源：http://dali.fzhhl.top/Article/details/gt2bhhkmlll.html

[R57] 远程执行命令
来源：http://dali.sysykeji.top/Article/details/gt2cbiljhfb.html

ssh user@host 'uptime'
来源：http://dali.xuetiantiany.cn/Article/details/gt2numnlsxy.html

[R58] 下载文件
来源：http://dali.xziqi.cn/Article/details/gt2waoaknqg.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.yueranfly.top/Article/details/gt2znlwsjiu.html

[R59] 发 POST JSON
来源：http://dali.yj202588.top/Article/details/gt2bulfmwyz.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.dashuyun.cn/Article/details/gt2ougpowpd.html

[R60] 只看 HTTP 状态码
来源：http://dali.cqqwz.cn/Article/details/gt2vyxkzfuh.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.hfpthk.cn/Article/details/gt2odonegek.html

[R61] 磁盘占用
来源：http://dali.fzhhl.top/Article/details/gt2nxjnvzel.html

df -h;  du -sh *
来源：http://dali.aizwys.cn/Article/details/gt2lniwxhne.html

[R62] 找最占空间的文件
来源：http://dali.andypj.xyz/Article/details/gt2drvaetgi.html

du -ah . | sort -rh | head -10
来源：http://dali.cheryme.top/Article/details/gt2ntxsemeb.html

[R63] 内存与进程
来源：http://dali.ehwqpu.com/Article/details/gt2seubkkdo.html

free -h;  ps aux | grep nginx
来源：http://dali.nanxinkj.top/Article/details/gt2nroumxve.html

[R64] 结束进程
来源：http://dali.xuanzx.com/Article/details/gt2nuxhdlzf.html

kill -9 $(pgrep -f app.py)
来源：http://dali.aibaodan.cn/Article/details/gt2iubdthdn.html

[R65] 查看端口占用
来源：http://dali.jqgufenzy.top/Article/details/gt2emdofbqj.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.sweek.top/Article/details/gt2iijrfdaq.html

[R66] 定时任务
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nrhtybkc.html

crontab -e;  crontab -l
来源：http://dali.shzxlz.cn/Article/details/gt2vixymjfa.html

[R67] 生成随机十六进制串
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lgaqxqcn.html

openssl rand -hex 16
来源：http://dali.xuetiantiany.cn/Article/details/gt2howjkyro.html

[R68] 计算文件校验值
来源：http://dali.xuanzx.com/Article/details/gt2belrepag.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.sxryk.cn/Article/details/gt2ilqgpxad.html

[R69] 生成随机密码
来源：http://dali.cucudq.cn/Article/details/gt2nyaxfhag.html

head -c 16 /dev/urandom | base64
来源：http://dali.yuanzhike.top/Article/details/gt2pfpifcib.html

[R70] 时间戳与互转
来源：http://dali.gaohongyu789.top/Article/details/gt2fejgntej.html

date +%s;  date -d @1700000000
来源：http://dali.hysaishi.cn/Article/details/gt2jcbhwqos.html

[R71] 日期格式化
来源：http://dali.pengpengdd.cyou/Article/details/gt2cwqskmpd.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zdqjudy.top/Article/details/gt2zbnulggi.html

[R72] 等待端口就绪
来源：http://dali.cucudq.cn/Article/details/gt2ynmvoffq.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.yonumen.top/Article/details/gt2dobkfqrb.html

[R73] 分割大日志
来源：http://dali.zhiwuduotai.top/Article/details/gt2qtondfui.html

split -l 1000 big.log part_
来源：http://dali.haohaochexian.top/Article/details/gt2fkwngjtd.html

[R74] 批量重命名
来源：http://dali.ydzc1.top/Article/details/gt2idofgqcw.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.jlsjyb.cn/Article/details/gt2fgpiivgk.html

[R75] 导出环境变量
来源：http://dali.cdnleiting.top/Article/details/gt2aybfdmrc.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.tanke756.top/Article/details/gt2zmkhaedg.html

[R76] 使用临时文件
来源：http://dali.tian-w.cn/Article/details/gt2vgxjkjli.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.jqgfzy.top/Article/details/gt2wrpgkyfw.html

[R77] 读取用户输入
来源：http://dali.jiagoushi.top/Article/details/gt2taaumspm.html

read -rp "请输入: " ans
来源：http://dali.mhx1999.top/Article/details/gt2phdmrlyh.html

[R78] 交互式菜单
来源：http://dali.hammf.cn/Article/details/gt2lkllonhq.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.havefunace.top/Article/details/gt2zwwsghbz.html

[R79] 解析命令行选项
来源：http://dali.tanke756.top/Article/details/gt2vbcbiqem.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.daria6918.cn/Article/details/gt2hrvgoheb.html

[R80] 查看脚本执行耗时
来源：http://dali.cqqwz.cn/Article/details/gt2ybesmkfr.html

time ./run.sh
来源：http://dali.yongpay.top/Article/details/gt2lrpujgbs.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gt2gtcnxjlu.html

S. C / C++ 专题
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lqivycud.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gt2usbelvib.html

[S01] C：Hello World
来源：http://dali.tanke756.top/Article/details/gt2zogbmdpq.html

#include <stdio.h>
来源：http://dali.nanxinkj.top/Article/details/gt2vvyelhbo.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.hnxiangtu.top/Article/details/gt2ktyvygvm.html

[S02] C：变量与格式化输出
来源：http://dali.cqqwz.cn/Article/details/gt2zhkmqzee.html

int a = 10; printf("%d\n", a);
来源：http://dali.dianchejie.cn/Article/details/gt2sogjtmcb.html

[S03] C：读入整数
来源：http://dali.ybcxt.top/Article/details/gt2ipyxhssk.html

int x; scanf("%d", &x);
来源：http://dali.sysykeji.top/Article/details/gt2wjdwyanq.html

[S04] C：字符串复制
来源：http://dali.snrcjt.cn/Article/details/gt2joigjkbb.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.ybcxt.top/Article/details/gt2dbtwcekf.html

[S05] C：字符串长度
来源：http://dali.yanxiufei.cn/Article/details/gt2gnchynvu.html

strlen(s)
来源：http://dali.fzhhl.top/Article/details/gt2xnzshbhx.html

[S06] C：字符串比较
来源：http://dali.meibo888.top/Article/details/gt2hwdtntwq.html

strcmp(a, b) == 0
来源：http://dali.zhixingplan.top/Article/details/gt2fdligzha.html

[S07] C：数组遍历求和
来源：http://dali.jyoumei.cn/Article/details/gt2zkeurmzi.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.yongpay.top/Article/details/gt2gykcvhcd.html

[S08] C：动态内存分配与释放
来源：http://dali.zhixingplan.top/Article/details/gt2bngkplvj.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.yj202588.top/Article/details/gt2zbtuqoxc.html

[S09] C：结构体定义与初始化
来源：http://dali.chenzaomai.com/Article/details/gt2uhafdgea.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rghhjaru.html

[S10] C：指针与解引用
来源：http://dali.hnxiangtu.top/Article/details/gt2ugrabznu.html

int *p = &a;  *p = 5;
来源：http://dali.haohaochexian.top/Article/details/gt2fvzauaaz.html

[S11] C：逐行读文件
来源：http://dali.birdmap.top/Article/details/gt2flxplplz.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.aizwys.cn/Article/details/gt2hnaazkhd.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.fzhhl.top/Article/details/gt2xjiffjoc.html

fclose(f);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dlelevek.html

[S12] C：写文件
来源：http://dali.zycfv.cn/Article/details/gt2izafxgxt.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.xuetiantiany.cn/Article/details/gt2vrpwbepl.html

[S13] C：宏定义
来源：http://dali.daxiang520.top/Article/details/gt2qafusqrw.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.chenlongwang.top/Article/details/gt2cwhprceo.html

[S14] C：枚举
来源：http://dali.smart0.xyz/Article/details/gt2rwctybvu.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.shangyingyoupin.top/Article/details/gt2fdwluuvp.html

[S15] C：类型转换
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kppvjhsm.html

(double) a / b
来源：http://dali.shuidangran.top/Article/details/gt2zxredawg.html

[S16] C：位操作置位
来源：http://dali.havefunace.top/Article/details/gt2giphdizl.html

x |= (1 << 3);
来源：http://dali.xinyue.icu/Article/details/gt2xsuyvbei.html

[S17] C：安全拼接字符串
来源：http://dali.hnxiangtu.top/Article/details/gt2ibzhwfal.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.hnqzz.top/Article/details/gt2wlvckhvl.html

[S18] C：命令行参数
来源：http://dali.gzhubu.top/Article/details/gt2zzdwnmfs.html

int main(int argc, char **argv)
来源：http://dali.ydzc1.top/Article/details/gt2beqhggob.html

[S19] C：快速排序
来源：http://dali.bjfxy.top/Article/details/gt2gintedsz.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2afnxatfg.html

[S20] C：二分查找
来源：http://dali.yonumen.top/Article/details/gt2myarsyzv.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.jinqigufen.top/Article/details/gt2dnbrxknd.html

[S21] C：字符类别判断
来源：http://dali.0kj1m.cn/Article/details/gt2gvyqsggo.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.tian-w.cn/Article/details/gt2etprbqbr.html

[S22] C：字符串转数字
来源：http://dali.hongshengwenyu.top/Article/details/gt2mziwdgsj.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.jiagoushi.top/Article/details/gt2qzapwmdv.html

[S23] C：随机数
来源：http://dali.bjfxy.top/Article/details/gt2rnxlznlq.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.kuanghao11.cn/Article/details/gt2alvsndlx.html

[S24] C：获取本地时间
来源：http://dali.zdqjudy.top/Article/details/gt2gwxrasis.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.ivvv.top/Article/details/gt2jfziirox.html

[S25] C：内存拷贝
来源：http://dali.hfpthk.cn/Article/details/gt2wmaouyus.html

memcpy(dst, src, n);
来源：http://dali.hongshengwenyu.top/Article/details/gt2xocqsasw.html

[S26] C：内存清零
来源：http://dali.zhixingplan.top/Article/details/gt2evediqor.html

memset(a, 0, sizeof a);
来源：http://dali.hywenlv.cn/Article/details/gt2dddnecle.html

[S27] C：定义常量
来源：http://dali.gzhubu.top/Article/details/gt2odyejmra.html

const double PI = 3.14159;
来源：http://dali.ivvv.top/Article/details/gt2cqarutrs.html

[S28] C：静态变量
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gybuldwc.html

static int counter = 0;
来源：http://dali.gogol.net.cn/Article/details/gt2bmisrdyt.html

[S29] C：变参函数
来源：http://dali.jqgufenzy.top/Article/details/gt2nctkqeol.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.fzhhl.top/Article/details/gt2kpldulsy.html

[S30] C：头文件保护
来源：http://dali.hysaishi.cn/Article/details/gt2hyufqech.html

#ifndef X_H
来源：http://dali.xylfe.cn/Article/details/gt2bssjdrfw.html

#define X_H
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jfnhbwoc.html

#endif
来源：http://dali.tianlin.xyz/Article/details/gt2etlnoojb.html

[S31] C++：Hello World
来源：http://dali.yuxming.cn/Article/details/gt2rizewelv.html

#include <iostream>
来源：http://dali.jiagoushi.top/Article/details/gt2mmukhazc.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.hnxiangtu.top/Article/details/gt2njrfjvvp.html

[S32] C++：字符串
来源：http://dali.daria6918.cn/Article/details/gt2vfxqlufq.html

std::string s = "hi";  s += "!";
来源：http://dali.fzhhl.top/Article/details/gt2ukhbtmdv.html

[S33] C++：vector 增删
来源：http://dali.yanxiufei.cn/Article/details/gt2xdyjbdqu.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.wangdashe.top/Article/details/gt2zbkhkfta.html

[S34] C++：遍历 vector
来源：http://dali.daria6918.cn/Article/details/gt2fieumstj.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.cucudq.cn/Article/details/gt2rcekhvol.html

[S35] C++：map
来源：http://dali.ivvv.top/Article/details/gt2iusaqitx.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yj202588.top/Article/details/gt2sjnsrgbz.html

[S36] C++：unordered_map
来源：http://dali.xylfe.cn/Article/details/gt2lqjuouik.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.ydzc1.top/Article/details/gt2mscgeqza.html

[S37] C++：set
来源：http://dali.hywenlv.cn/Article/details/gt2rncfzbyt.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.andypj.xyz/Article/details/gt2ekylotdy.html

[S38] C++：排序
来源：http://dali.gogol.net.cn/Article/details/gt2tunyxout.html

std::sort(v.begin(), v.end());
来源：http://dali.hnxiangtu.top/Article/details/gt2iwmhgftz.html

[S39] C++：自定义比较器排序
来源：http://dali.gogol.net.cn/Article/details/gt2chxqzjzg.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.nanxinkj.top/Article/details/gt2lioouqmz.html

[S40] C++：查找元素
来源：http://dali.smart0.xyz/Article/details/gt2yxihioqg.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.yuanzhike.top/Article/details/gt2ipyukzjx.html

[S41] C++：类与构造函数
来源：http://dali.jiagoushi.top/Article/details/gt2ozsacgjl.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.xylfe.cn/Article/details/gt2lwtejhse.html

[S42] C++：继承与虚函数
来源：http://dali.smart0.xyz/Article/details/gt2xckddsbw.html

class B : public Base { public: void f() override {} };
来源：http://dali.meibo888.top/Article/details/gt2wpatlkcs.html

[S43] C++：智能指针
来源：http://dali.zhengqikj.top/Article/details/gt2igbeofin.html

auto p = std::make_unique<int>(5);
来源：http://dali.9152youxi.cn/Article/details/gt2wtoeyklk.html

[S44] C++：引用传参
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vnxtatic.html

void inc(int &x) { ++x; }
来源：http://dali.yangfankeji.com/Article/details/gt2jnvmekhk.html

[S45] C++：lambda
来源：http://dali.fengsongda.top/Article/details/gt2effbnftu.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.yongpay.top/Article/details/gt2uyszlhbq.html

[S46] C++：函数模板
来源：http://dali.zhoulong.xyz/Article/details/gt2bbrofqwd.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.xylfe.cn/Article/details/gt2bbrvpzmh.html

[S47] C++：结构化绑定遍历
来源：http://dali.yvedp.cn/Article/details/gt2wcufddje.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.smart0.xyz/Article/details/gt2mjuimust.html

[S48] C++：逐行读文件
来源：http://dali.mhx1999.top/Article/details/gt2blbcubkz.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.hfpthk.cn/Article/details/gt2rxiuychu.html

while (std::getline(in, line)) { }
来源：http://dali.snrcjt.cn/Article/details/gt2axemszul.html

[S49] C++：写文件
来源：http://dali.jlsjyb.cn/Article/details/gt2ucuqlazt.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.cheryme.top/Article/details/gt2pzwbuxlz.html

[S50] C++：格式化数字
来源：http://dali.shuidangran.top/Article/details/gt2wakizqvu.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.yuanzhike.top/Article/details/gt2xufakrjt.html

[S51] C++：显式类型转换
来源：http://dali.andypj.xyz/Article/details/gt2mkjdrwyq.html

static_cast<double>(a) / b
来源：http://dali.jlsjyb.cn/Article/details/gt2izgespbj.html

[S52] C++：const 与 noexcept
来源：http://dali.ivvv.top/Article/details/gt2zfdmslqw.html

int size() const noexcept { return n_; }
来源：http://dali.fzhhl.top/Article/details/gt2ffimwznz.html

[S53] C++：移动语义
来源：http://dali.hnxiangtu.top/Article/details/gt2lrsthswv.html

std::vector<int> w = std::move(v);
来源：http://dali.smart0.xyz/Article/details/gt2aycfvxtd.html

[S54] C++：异常处理
来源：http://dali.nwbrower.top/Article/details/gt2vbyobztu.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kowxetjh.html

[S55] C++：结构化绑定
来源：http://dali.yuanzhike.top/Article/details/gt2iodkvoif.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.hysaishi.cn/Article/details/gt2pemphotx.html

[S56] C++：optional
来源：http://dali.yonumen.top/Article/details/gt2xoxolvva.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.hnxiangtu.top/Article/details/gt2yjkujebb.html

[S57] C++：编译期常量
来源：http://dali.chenzaomai.com/Article/details/gt2qnatjlgm.html

constexpr int N = 10;
来源：http://dali.chenlongwang.top/Article/details/gt2iqgtkqhd.html

[S58] C++：命名空间
来源：http://dali.snrcjt.cn/Article/details/gt2rtpobvtl.html

namespace ns { int f() { return 1; } }
来源：http://dali.cashguo.top/Article/details/gt2ftuttbzu.html

[S59] C++：静态断言
来源：http://dali.feifeiyinyue.top/Article/details/gt2nvgrtcqm.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.cdnleiting.top/Article/details/gt2rmfjyafk.html

[S60] C++：遍历并删除元素
来源：http://dali.zhengqikj.top/Article/details/gt2illvqfql.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.yuanzhike.top/Article/details/gt2auyoeupi.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2mhdowxkt.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.nwbrower.top/Article/details/gt2vnrjttqz.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gt2wqfkkrbk.html

[T01] Kotlin：Hello World
来源：http://dali.yj20258888.top/Article/details/gt2gbwztwzd.html

println("Hello")
来源：http://dali.yuanzhike.top/Article/details/gt2kttmjdkz.html

[T02] Kotlin：变量
来源：http://dali.hnqzz.top/Article/details/gt2tujemdmi.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.gaohongyu789.top/Article/details/gt2ajcewbyy.html

[T03] Kotlin：字符串模板
来源：http://dali.chenjidiqi.icu/Article/details/gt2lpddfxvo.html

"值: $b"
来源：http://dali.yj20258.top/Article/details/gt2rogjatnl.html

[T04] Kotlin：空安全
来源：http://dali.feifeiyinyue.top/Article/details/gt2txojwcuu.html

val n: String? = null;  n?.length
来源：http://dali.quarkkingdee.top/Article/details/gt2ittjhnox.html

[T05] Kotlin：when 表达式
来源：http://dali.0kj1m.cn/Article/details/gt2bskrvnyq.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.wangshuangyany.cn/Article/details/gt2ywxzpnmf.html

[T06] Kotlin：集合映射
来源：http://dali.shuidangran.top/Article/details/gt2xwcaksyc.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.c1oappe.top/Article/details/gt2gumldtmo.html

[T07] Kotlin：集合过滤
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2keomosts.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.yangfankeji.com/Article/details/gt2zofixuvw.html

[T08] Kotlin：数据类
来源：http://dali.feifeiyinyue.top/Article/details/gt2tzdaduqy.html

data class User(val name: String, val age: Int)
来源：http://dali.zhengqikj.top/Article/details/gt2xvpnnmof.html

[T09] Kotlin：扩展函数
来源：http://dali.cdnleiting.top/Article/details/gt2lsjvimci.html

fun String.exclaim() = this + "!"
来源：http://dali.ivvv.top/Article/details/gt2orwbswbw.html

[T10] Kotlin：默认参数
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zpduchgt.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.yj20258.top/Article/details/gt2ltdncqmn.html

[T11] Kotlin：协程
来源：http://dali.zdqjudy.top/Article/details/gt2halfuqed.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.nwbrower.top/Article/details/gt2wqrrnafp.html

[T12] Kotlin：解构声明
来源：http://dali.zhiwuduotai.top/Article/details/gt2ulsbrqev.html

val (a, b) = Pair(1, 2)
来源：http://dali.feifeiyinyue.top/Article/details/gt2eumyixxw.html

[T13] Kotlin：只读 Map
来源：http://dali.ivvv.top/Article/details/gt2crscgjgs.html

val m = mapOf("a" to 1)
来源：http://dali.zhoulong.xyz/Article/details/gt2ywunhaqo.html

[T14] Kotlin：循环
来源：http://dali.hnxiangtu.top/Article/details/gt2wwhchpho.html

for (i in 1..10) println(i)
来源：http://dali.xuetiantiany.cn/Article/details/gt2rjzoacqy.html

[T15] Kotlin：接口
来源：http://dali.fengsongda.top/Article/details/gt2laentngs.html

interface Shape { fun area(): Double }
来源：http://dali.xziqi.cn/Article/details/gt2ndqjaubs.html

[T16] Swift：Hello World
来源：http://dali.nanxuanxn.top/Article/details/gt2osmoducw.html

print("Hello")
来源：http://dali.hfpthk.cn/Article/details/gt2ejexzjwh.html

[T17] Swift：变量与常量
来源：http://dali.gotoacloud.top/Article/details/gt2zmznafqh.html

var a = 1;  let b = 2
来源：http://dali.xuetiantiany.cn/Article/details/gt2ndqbylyb.html

[T18] Swift：字符串插值
来源：http://dali.gzhubu.top/Article/details/gt2sueqavtl.html

"值: \(b)"
来源：http://dali.vqdsnc.cn/Article/details/gt2hiqqbnga.html

[T19] Swift：可选绑定
来源：http://dali.sysykeji.top/Article/details/gt2ketigyuy.html

if let n = opt { print(n) }
来源：http://dali.jqgufenzy.top/Article/details/gt2zijbjlfb.html

[T20] Swift：数组操作
来源：http://dali.sysykeji.top/Article/details/gt2xwaqenwj.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.xuanzx.com/Article/details/gt2hlhsqoyd.html

[T21] Swift：遍历
来源：http://dali.sxryk.cn/Article/details/gt2pofsdaom.html

for x in a { print(x) }
来源：http://dali.yueranfly.top/Article/details/gt2jskagttb.html

[T22] Swift：字典
来源：http://dali.nwbrower.top/Article/details/gt2vejeuefu.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.chenzaomai.com/Article/details/gt2ihfcpvbf.html

[T23] Swift：函数
来源：http://dali.cdnleiting.top/Article/details/gt2hnezdfvq.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.tanke756.top/Article/details/gt2riksoyml.html

[T24] Swift：闭包
来源：http://dali.shzxlz.cn/Article/details/gt2hbpgoryc.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.gaohongyu789.top/Article/details/gt2qyorgcxf.html

[T25] Swift：结构体
来源：http://dali.haohaochexian.top/Article/details/gt2toexhohx.html

struct P { var x: Int }
来源：http://dali.sweek.top/Article/details/gt2eynvpzrn.html

[T26] Swift：类与重写
来源：http://dali.meibo888.top/Article/details/gt2ifhesjuc.html

class A: Base { override func f() {} }
来源：http://dali.zhengqikj.top/Article/details/gt2gjtgmmib.html

[T27] Swift：错误处理
来源：http://dali.yanxiufei.cn/Article/details/gt2zavxcmxv.html

do { try f() } catch { print(error) }
来源：http://dali.9152youxi.cn/Article/details/gt2cngbcvtn.html

[T28] Swift：枚举
来源：http://dali.yvedp.cn/Article/details/gt2rzndorat.html

enum Color { case red, green }
来源：http://dali.fengsongda.top/Article/details/gt2wgqcgrqy.html

[T29] Swift：guard 提前返回
来源：http://dali.yuxming.cn/Article/details/gt2ywyyjssu.html

guard let x = opt else { return }
来源：http://dali.jqgfzy.top/Article/details/gt2mtdzwujp.html

[T30] Swift：协议
来源：http://dali.xuetiantiany.cn/Article/details/gt2qfozdsgm.html

protocol Shape { func area() -> Double }
来源：http://dali.sysykeji.top/Article/details/gt2nxjiwjab.html

[T31] Lua：Hello World
来源：http://dali.wangshuangyany.cn/Article/details/gt2wdyjsrqv.html

print("Hello")
来源：http://dali.nwbrower.top/Article/details/gt2njxwxtgy.html

[T32] Lua：局部变量
来源：http://dali.hywenlv.cn/Article/details/gt2mflrwwye.html

local a = 1
来源：http://dali.jqgufenzy.top/Article/details/gt2jchcshve.html

[T33] Lua：表（数组）
来源：http://dali.vqdsnc.cn/Article/details/gt2bdpcdczc.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.sufxvd.cn/Article/details/gt2rsfajzcy.html

[T34] Lua：遍历表
来源：http://dali.daxiang520.top/Article/details/gt2arazqgts.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhixingplan.top/Article/details/gt2kauljvfc.html

[T35] Lua：字典表
来源：http://dali.ivvv.top/Article/details/gt2sgojveot.html

local d = { a = 1 };  d.b = 2
来源：http://dali.kuanghao11.cn/Article/details/gt2skkaudhl.html

[T36] Lua：函数
来源：http://dali.fengsongda.top/Article/details/gt2donlsumf.html

function add(a, b) return a + b end
来源：http://dali.wangshuangyany.cn/Article/details/gt2xhzqhbjo.html

[T37] Lua：字符串拼接
来源：http://dali.jiagoushi.top/Article/details/gt2suhaufdj.html

"a" .. "b"
来源：http://dali.gotoacloud.top/Article/details/gt2gtjlyzjn.html

[T38] Lua：条件
来源：http://dali.xziqi.cn/Article/details/gt2dbtyvntt.html

if x > 0 then print("正") end
来源：http://dali.meibo888.top/Article/details/gt2ejaclrsx.html

[T39] Lua：模式匹配
来源：http://dali.zhengqikj.top/Article/details/gt2xakwbkxn.html

string.find(s, "%d+")
来源：http://dali.yangfankeji.com/Article/details/gt2hblxyvib.html

[T40] Lua：元表
来源：http://dali.andypj.xyz/Article/details/gt2vilcaaji.html

setmetatable({}, { __index = base })
来源：http://dali.sxryk.cn/Article/details/gt2zzekpfnt.html

[T41] Perl：Hello World
来源：http://dali.9152youxi.cn/Article/details/gt2awjlszgk.html

print "Hello\n";
来源：http://dali.xziqi.cn/Article/details/gt2kgupqbwd.html

[T42] Perl：变量类型
来源：http://dali.c1oappe.top/Article/details/gt2izxeiaen.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.jqgfzy.top/Article/details/gt2xajahbze.html

[T43] Perl：字符串插值
来源：http://dali.zhongyouzk.top/Article/details/gt2ctyqvqid.html

"值: $a"
来源：http://dali.pycfn.com/Article/details/gt2tzzdrmeo.html

[T44] Perl：条件
来源：http://dali.bjfxy.top/Article/details/gt2mapshdyp.html

if ($a > 0) { print "正"; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2fppflulh.html

[T45] Perl：数组遍历
来源：http://dali.tanke756.top/Article/details/gt2gvtlzwbh.html

for my $x (@arr) { print $x; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cjrlussd.html

[T46] Perl：哈希操作
来源：http://dali.gaohongyu789.top/Article/details/gt2xfvldslb.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gyrztcdw.html

[T47] Perl：正则捕获
来源：http://dali.yonumen.top/Article/details/gt2irxprfgj.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2njbnveam.html

[T48] Perl：正则替换
来源：http://dali.yangfankeji.com/Article/details/gt2iajzasoh.html

$s =~ s/old/new/g;
来源：http://dali.cucudq.cn/Article/details/gt2tcnlihqo.html


<!-- 参考信息 -->