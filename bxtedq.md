代发 wailian999

files=$(ls -1)
来源：http://dali.daria6918.cn/Article/details/gtuzepcaua.html

[R38] 管道串联
来源：http://dali.smart0.xyz/Article/details/gtuspeiuvg.html

cat a.txt | grep -i error | wc -l
来源：http://dali.guowangkeji.top/Article/details/gtppmpvfvv.html

[R39] 重定向标准输出与错误
来源：http://dali.aibaodan.cn/Article/details/gtpgdhuvho.html

cmd > out.log 2>&1
来源：http://dali.ivvv.top/Article/details/gtyjgnauxs.html

[R40] 追加写日志
来源：http://dali.fengsongda.top/Article/details/gtdhinoxwv.html

echo "log" >> out.log
来源：http://dali.hongshengwenyu.top/Article/details/gtvvojzwlg.html

[R41] 丢弃输出
来源：http://dali.gotoacloud.top/Article/details/gtlysjcfro.html

cmd >/dev/null 2>&1
来源：http://dali.yuxming.cn/Article/details/gtzrkzlzdl.html

[R42] 输入重定向
来源：http://dali.dianchejie.cn/Article/details/gtewjzsdsm.html

wc -l < a.txt
来源：http://dali.tian-w.cn/Article/details/gtvkfocepy.html

[R43] 按名字查找文件
来源：http://dali.fzhhl.top/Article/details/gtsqcqzvio.html

find . -name "*.log" -type f
来源：http://dali.jqgufenzy.top/Article/details/gteejmqchx.html

[R44] 按修改时间查找
来源：http://dali.tianlin.xyz/Article/details/gtyivqooex.html

find . -mtime -7 -type f
来源：http://dali.9152youxi.cn/Article/details/gtyngbfuiv.html

[R45] 批量删除
来源：http://dali.pengpengdd.cyou/Article/details/gtiuykdkzq.html

find . -name "*.tmp" -delete
来源：http://dali.shzxlz.cn/Article/details/gtfofjfwvy.html

[R46] 递归替换文件内容
来源：http://dali.fengsongda.top/Article/details/gtjybqduvu.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.cucudq.cn/Article/details/gtfgwihjeo.html

[R47] sed 单行替换
来源：http://dali.haohaochexian.top/Article/details/gtqayzkbbo.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.svipenyu.cn/Article/details/gtdpyxfytv.html

[R48] awk 取指定列
来源：http://dali.feifeiyinyue.top/Article/details/gtuauprhov.html

awk '{print $1, $3}' a.txt
来源：http://dali.daxiang520.top/Article/details/gtbwqyhqwv.html

[R49] awk 带条件
来源：http://dali.sxryk.cn/Article/details/gtlxzjzfxi.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.chenjidiqi.icu/Article/details/gtprqgdwui.html

[R50] awk 求和
来源：http://dali.xinyue.icu/Article/details/gtdltsqfhk.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.yuanzhike.top/Article/details/gtpexnzpkc.html

[R51] 排序去重取前几
来源：http://dali.gzhubu.top/Article/details/gtbhgoudoi.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.yvedp.cn/Article/details/gtnsogihyv.html

[R52] 统计行数
来源：http://dali.hysaishi.cn/Article/details/gtdpvordzt.html

wc -l a.txt
来源：http://dali.jiagoushi.top/Article/details/gtgibvlslr.html

[R53] 查看文件头与实时尾
来源：http://dali.fzhhl.top/Article/details/gtdctthlcv.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.hfpthk.cn/Article/details/gtyxfcezgk.html

[R54] 比较两个文件
来源：http://dali.316326.xyz/Article/details/gtcncdrqtz.html

diff a.txt b.txt
来源：http://dali.pycfn.com/Article/details/gtsjkwnmia.html

[R55] 压缩与解压
来源：http://dali.hammf.cn/Article/details/gtukeghsvq.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrxujifwf.html

[R56] 远程拷贝
来源：http://dali.jqgfzy.top/Article/details/gtdiloeiiq.html

scp file user@host:/path/
来源：http://dali.nanxinkj.top/Article/details/gtxivpmdvl.html

[R57] 远程执行命令
来源：http://dali.mhx1999.top/Article/details/gtevshkpaf.html

ssh user@host 'uptime'
来源：http://dali.zhiwuduotai.top/Article/details/gtiehexfac.html

[R58] 下载文件
来源：http://dali.hnqzz.top/Article/details/gtyywiuzyg.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.smart0.xyz/Article/details/gtqzzbmcrk.html

[R59] 发 POST JSON
来源：http://dali.0kj1m.cn/Article/details/gtfeddggkl.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.haohaochexian.top/Article/details/gtlpnyyagq.html

[R60] 只看 HTTP 状态码
来源：http://dali.yj202588.top/Article/details/gtjmbttmoj.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.c1oappe.top/Article/details/gthkejwjeb.html

[R61] 磁盘占用
来源：http://dali.zhiwuduotai.top/Article/details/gtfgoppool.html

df -h;  du -sh *
来源：http://dali.feifeiyinyue.top/Article/details/gtcskxwvvv.html

[R62] 找最占空间的文件
来源：http://dali.yj202588.top/Article/details/gtozobiqkq.html

du -ah . | sort -rh | head -10
来源：http://dali.zhengqikj.top/Article/details/gtsdrromkw.html

[R63] 内存与进程
来源：http://dali.zdqjudy.top/Article/details/gtspmealjh.html

free -h;  ps aux | grep nginx
来源：http://dali.ybcxt.top/Article/details/gtarsahern.html

[R64] 结束进程
来源：http://dali.feifeiyinyue.top/Article/details/gtzkcoraii.html

kill -9 $(pgrep -f app.py)
来源：http://dali.meibo888.top/Article/details/gtvhxgqnyv.html

[R65] 查看端口占用
来源：http://dali.hongshengwenyu.top/Article/details/gtvpdyskig.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.iojbl.cn/Article/details/gtzijfrjec.html

[R66] 定时任务
来源：http://dali.tianlin.xyz/Article/details/gtectmymps.html

crontab -e;  crontab -l
来源：http://dali.zhongyouzk.top/Article/details/gtneaujlfk.html

[R67] 生成随机十六进制串
来源：http://dali.yj20258888.top/Article/details/gtjdhahskr.html

openssl rand -hex 16
来源：http://dali.gotoacloud.top/Article/details/gtodhdaplp.html

[R68] 计算文件校验值
来源：http://dali.zhixingplan.top/Article/details/gtbawqpote.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.c1oappe.top/Article/details/gtqwcrqkdp.html

[R69] 生成随机密码
来源：http://dali.yongpay.top/Article/details/gtegsvycjy.html

head -c 16 /dev/urandom | base64
来源：http://dali.ybcxt.top/Article/details/gtjicbuygc.html

[R70] 时间戳与互转
来源：http://dali.jlsjyb.cn/Article/details/gtgciarpzq.html

date +%s;  date -d @1700000000
来源：http://dali.xuanzx.com/Article/details/gtxtbmntjr.html

[R71] 日期格式化
来源：http://dali.cqqwz.cn/Article/details/gtcjyuxljt.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.feifeiyinyue.top/Article/details/gtwtmtwvhf.html

[R72] 等待端口就绪
来源：http://dali.zhengqikj.top/Article/details/gtqgwcdlvu.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.9152youxi.cn/Article/details/gtifrikjss.html

[R73] 分割大日志
来源：http://dali.zdqjudy.top/Article/details/gtcfepjpeh.html

split -l 1000 big.log part_
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpzufjgxj.html

[R74] 批量重命名
来源：http://dali.chenzaomai.com/Article/details/gtbdilypes.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.jqgufenzy.top/Article/details/gtclqesgni.html

[R75] 导出环境变量
来源：http://dali.zhengqikj.top/Article/details/gtkgjbrrog.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.jqgfzy.top/Article/details/gtrudoleoy.html

[R76] 使用临时文件
来源：http://dali.kuanghao11.cn/Article/details/gtddfvsrjf.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.xylfe.cn/Article/details/gtrcldihbo.html

[R77] 读取用户输入
来源：http://dali.haohaochexian.top/Article/details/gtiuhssihl.html

read -rp "请输入: " ans
来源：http://dali.havefunace.top/Article/details/gtjmerkzcy.html

[R78] 交互式菜单
来源：http://dali.yj20258.top/Article/details/gtvghpdnqb.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.xziqi.cn/Article/details/gtwrjjxcbw.html

[R79] 解析命令行选项
来源：http://dali.yuanzhike.top/Article/details/gtixwmptgr.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.xuanzx.com/Article/details/gtqscaajha.html

[R80] 查看脚本执行耗时
来源：http://dali.havefunace.top/Article/details/gtetuyfulm.html

time ./run.sh
来源：http://dali.hysaishi.cn/Article/details/gtxiggtsgv.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtgnwvmful.html

S. C / C++ 专题
来源：http://dali.zhiwuduotai.top/Article/details/gtiqopjiki.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtnlmcvreo.html

[S01] C：Hello World
来源：http://dali.pycfn.com/Article/details/gtdncircsd.html

#include <stdio.h>
来源：http://dali.aibaodan.cn/Article/details/gtcmqclpjj.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.yvedp.cn/Article/details/gtprozuxpu.html

[S02] C：变量与格式化输出
来源：http://dali.andypj.xyz/Article/details/gtfwgmvpfm.html

int a = 10; printf("%d\n", a);
来源：http://dali.hnxiangtu.top/Article/details/gtyxhijydc.html

[S03] C：读入整数
来源：http://dali.sufxvd.cn/Article/details/gtjhdidrom.html

int x; scanf("%d", &x);
来源：http://dali.hywenlv.cn/Article/details/gtcfuwjtgj.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gtlkmasgbc.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zdqjudy.top/Article/details/gtnpufrsbg.html

[S05] C：字符串长度
来源：http://dali.xuetiantiany.cn/Article/details/gtkaezjhmf.html

strlen(s)
来源：http://dali.snrcjt.cn/Article/details/gtsmukzlpw.html

[S06] C：字符串比较
来源：http://dali.meibo888.top/Article/details/gtcbirvkge.html

strcmp(a, b) == 0
来源：http://dali.316326.xyz/Article/details/gtwsdewaou.html

[S07] C：数组遍历求和
来源：http://dali.jinghuilouyu.cn/Article/details/gtsyfwvfuk.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.iojbl.cn/Article/details/gtbsislzkb.html

[S08] C：动态内存分配与释放
来源：http://dali.hysaishi.cn/Article/details/gtytesegac.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.yvedp.cn/Article/details/gtuldhtucf.html

[S09] C：结构体定义与初始化
来源：http://dali.gotoacloud.top/Article/details/gtjwflgqxu.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.pengpengdd.cyou/Article/details/gthztndfjj.html

[S10] C：指针与解引用
来源：http://dali.daxiang520.top/Article/details/gtufttmlcq.html

int *p = &a;  *p = 5;
来源：http://dali.jinqigfzy.top/Article/details/gtxdxuuyhh.html

[S11] C：逐行读文件
来源：http://dali.jyoumei.cn/Article/details/gtcuzemwps.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhiwuduotai.top/Article/details/gtjqbhacqw.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.nanxinkj.top/Article/details/gtciysecyn.html

fclose(f);
来源：http://dali.zhixingplan.top/Article/details/gtrymsgefw.html

[S12] C：写文件
来源：http://dali.hywenlv.cn/Article/details/gtgvcwxuta.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.quarkkingdee.top/Article/details/gtmnwmndvc.html

[S13] C：宏定义
来源：http://dali.xinyue.icu/Article/details/gtzacodoau.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.nanxinkj.top/Article/details/gtxlknibyh.html

[S14] C：枚举
来源：http://dali.yj20258.top/Article/details/gtiebaibpq.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.hammf.cn/Article/details/gtzedvfkxd.html

[S15] C：类型转换
来源：http://dali.jiagoushi.top/Article/details/gtagjgsuht.html

(double) a / b
来源：http://dali.ivvv.top/Article/details/gtpixvwubt.html

[S16] C：位操作置位
来源：http://dali.yj20258.top/Article/details/gtbugrhuda.html

x |= (1 << 3);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlfdhonom.html

[S17] C：安全拼接字符串
来源：http://dali.guowangkeji.top/Article/details/gtumdrtifp.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.iojbl.cn/Article/details/gtdivnmfwt.html

[S18] C：命令行参数
来源：http://dali.svipenyu.cn/Article/details/gteopqarzu.html

int main(int argc, char **argv)
来源：http://dali.wangshuangyany.cn/Article/details/gtlzvsolmr.html

[S19] C：快速排序
来源：http://dali.hywenlv.cn/Article/details/gtkbtslmmd.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.wangshuangyany.cn/Article/details/gtofcxtscx.html

[S20] C：二分查找
来源：http://dali.kuanghao11.cn/Article/details/gtpohzbflc.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.yongpay.top/Article/details/gttzscuvoc.html

[S21] C：字符类别判断
来源：http://dali.ppjwa.cn/Article/details/gtfwgppkcu.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.xylfe.cn/Article/details/gtbamsznqq.html

[S22] C：字符串转数字
来源：http://dali.dashuyun.cn/Article/details/gtwkkqqows.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtogegwncu.html

[S23] C：随机数
来源：http://dali.shzxlz.cn/Article/details/gtqorsaoua.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.chenlongwang.top/Article/details/gtptbsbuas.html

[S24] C：获取本地时间
来源：http://dali.sysykeji.top/Article/details/gtkwvcfhat.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gtwxuyeqlk.html

[S25] C：内存拷贝
来源：http://dali.yonumen.top/Article/details/gtwmrqkrry.html

memcpy(dst, src, n);
来源：http://dali.hysaishi.cn/Article/details/gtaagzuidn.html

[S26] C：内存清零
来源：http://dali.zhoulong.xyz/Article/details/gtkekmsank.html

memset(a, 0, sizeof a);
来源：http://dali.daria6918.cn/Article/details/gtsfwvpmzs.html

[S27] C：定义常量
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuduozjve.html

const double PI = 3.14159;
来源：http://dali.zhongyouzk.top/Article/details/gtbzclkhbs.html

[S28] C：静态变量
来源：http://dali.ydzc1.top/Article/details/gtqbnqkjuv.html

static int counter = 0;
来源：http://dali.vqdsnc.cn/Article/details/gttppnrimi.html

[S29] C：变参函数
来源：http://dali.jqgufenzy.top/Article/details/gtsjmcipsj.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.cashguo.top/Article/details/gtotohextj.html

[S30] C：头文件保护
来源：http://dali.smart0.xyz/Article/details/gtbutyzkxb.html

#ifndef X_H
来源：http://dali.guowangkeji.top/Article/details/gtowcujnvn.html

#define X_H
来源：http://dali.nanxuanxn.top/Article/details/gtrpnfgjkr.html

#endif
来源：http://dali.yvedp.cn/Article/details/gtutlnyuam.html

[S31] C++：Hello World
来源：http://dali.chenzaomai.com/Article/details/gtjtfmwxvh.html

#include <iostream>
来源：http://dali.daria6918.cn/Article/details/gtufroyehz.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.yongpay.top/Article/details/gtzbievsbg.html

[S32] C++：字符串
来源：http://dali.guowangkeji.top/Article/details/gtxrynsmkf.html

std::string s = "hi";  s += "!";
来源：http://dali.redwolf501.top/Article/details/gtkwpzmsyc.html

[S33] C++：vector 增删
来源：http://dali.ppjwa.cn/Article/details/gtvxionufa.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.yvedp.cn/Article/details/gtxfzxpqjm.html

[S34] C++：遍历 vector
来源：http://dali.hnqzz.top/Article/details/gtiewpkrsi.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gttjaqlcbf.html

[S35] C++：map
来源：http://dali.aibaodan.cn/Article/details/gtcawosmib.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.gogol.net.cn/Article/details/gtnzwvtzsa.html

[S36] C++：unordered_map
来源：http://dali.ehwqpu.com/Article/details/gtomsycvli.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.fzhhl.top/Article/details/gtpyoptvau.html

[S37] C++：set
来源：http://dali.yuanzhike.top/Article/details/gtndhlesft.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.jianghu66.top/Article/details/gtrcwmslra.html

[S38] C++：排序
来源：http://dali.zhixingplan.top/Article/details/gtyaswznwa.html

std::sort(v.begin(), v.end());
来源：http://dali.yongpay.top/Article/details/gtiymkiqwh.html

[S39] C++：自定义比较器排序
来源：http://dali.tianlin.xyz/Article/details/gteipndmez.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.yvedp.cn/Article/details/gtfpxnqhzm.html

[S40] C++：查找元素
来源：http://dali.yj202588.top/Article/details/gtpgwwmdqc.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhengqikj.top/Article/details/gtivgybsla.html

[S41] C++：类与构造函数
来源：http://dali.zdqjudy.top/Article/details/gtizqbabzy.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.ehwqpu.com/Article/details/gtqtfthknn.html

[S42] C++：继承与虚函数
来源：http://dali.xinyue.icu/Article/details/gtpybmhvfx.html

class B : public Base { public: void f() override {} };
来源：http://dali.nwbrower.top/Article/details/gtqtzfrsei.html

[S43] C++：智能指针
来源：http://dali.iojbl.cn/Article/details/gtzrxiuqrt.html

auto p = std::make_unique<int>(5);
来源：http://dali.chenjidiqi.icu/Article/details/gttgabqibu.html

[S44] C++：引用传参
来源：http://dali.jinqigfzy.top/Article/details/gtgbeytjsa.html

void inc(int &x) { ++x; }
来源：http://dali.hywenlv.cn/Article/details/gtqwkbwpiw.html

[S45] C++：lambda
来源：http://dali.zhixingplan.top/Article/details/gtlptcsdow.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhaomingkeji.xyz/Article/details/gtttecwpnr.html

[S46] C++：函数模板
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxcgvztyt.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.sufxvd.cn/Article/details/gtuimxvkue.html

[S47] C++：结构化绑定遍历
来源：http://dali.jinghuilouyu.cn/Article/details/gtdinryjur.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.hnqzz.top/Article/details/gtkviqqxyz.html

[S48] C++：逐行读文件
来源：http://dali.hysaishi.cn/Article/details/gtvbqqtigz.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.jinqigufen.top/Article/details/gtblpqwnxb.html

while (std::getline(in, line)) { }
来源：http://dali.cucudq.cn/Article/details/gtoqssecxx.html

[S49] C++：写文件
来源：http://dali.wangshuangyany.cn/Article/details/gtfxexnxel.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqxsuddkz.html

[S50] C++：格式化数字
来源：http://dali.jyoumei.cn/Article/details/gtjdynwpob.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.yj202588.top/Article/details/gtbrcrpxde.html

[S51] C++：显式类型转换
来源：http://dali.hfpthk.cn/Article/details/gtbaekrwjc.html

static_cast<double>(a) / b
来源：http://dali.fzhhl.top/Article/details/gtdpibwfvf.html

[S52] C++：const 与 noexcept
来源：http://dali.aibaodan.cn/Article/details/gtbscswcsv.html

int size() const noexcept { return n_; }
来源：http://dali.svipenyu.cn/Article/details/gtlqahvdmd.html

[S53] C++：移动语义
来源：http://dali.shanyushiyangkeji.top/Article/details/gtangxakix.html

std::vector<int> w = std::move(v);
来源：http://dali.quarkkingdee.top/Article/details/gtzalxdsyv.html

[S54] C++：异常处理
来源：http://dali.pengpengdd.cyou/Article/details/gtrxcvxmsh.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.cheryme.top/Article/details/gtnibpizbq.html

[S55] C++：结构化绑定
来源：http://dali.fengsongda.top/Article/details/gtbjeykdaa.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.ydzc1.top/Article/details/gtppvojygx.html

[S56] C++：optional
来源：http://dali.guowangkeji.top/Article/details/gtvztlopgn.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yueranfly.top/Article/details/gtxagdgokg.html

[S57] C++：编译期常量
来源：http://dali.pycfn.com/Article/details/gtnsxzryko.html

constexpr int N = 10;
来源：http://dali.iojbl.cn/Article/details/gthnkagsln.html

[S58] C++：命名空间
来源：http://dali.snrcjt.cn/Article/details/gtnuealmwn.html

namespace ns { int f() { return 1; } }
来源：http://dali.bjfxy.top/Article/details/gtjkawjfyo.html

[S59] C++：静态断言
来源：http://dali.wangshuangyany.cn/Article/details/gtgremrxmb.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.bjfxy.top/Article/details/gtdoiwkjst.html

[S60] C++：遍历并删除元素
来源：http://dali.sxryk.cn/Article/details/gtgjportog.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.yongpay.top/Article/details/gtquhgmvdg.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtwukzgeyd.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zycfv.cn/Article/details/gtosaiujiu.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtoaxiefta.html

[T01] Kotlin：Hello World
来源：http://dali.ydzc1.top/Article/details/gtyxlynbpk.html

println("Hello")
来源：http://dali.nanxuanxn.top/Article/details/gtbawcvpii.html

[T02] Kotlin：变量
来源：http://dali.gogol.net.cn/Article/details/gtcxiseiie.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.aizwys.cn/Article/details/gtayxuqgmr.html

[T03] Kotlin：字符串模板
来源：http://dali.smart0.xyz/Article/details/gttbmgobmf.html

"值: $b"
来源：http://dali.yj20258.top/Article/details/gtkjcmlowi.html

[T04] Kotlin：空安全
来源：http://dali.zycfv.cn/Article/details/gtkoukjgdz.html

val n: String? = null;  n?.length
来源：http://dali.xinyue.icu/Article/details/gttlvuteid.html

[T05] Kotlin：when 表达式
来源：http://dali.yj202588.top/Article/details/gthcvvfpbl.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.pengpengdd.cyou/Article/details/gtisfmrebd.html

[T06] Kotlin：集合映射
来源：http://dali.hongshengwenyu.top/Article/details/gtxknlferi.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.hysaishi.cn/Article/details/gtmknwhyfd.html

[T07] Kotlin：集合过滤
来源：http://dali.redwolf501.top/Article/details/gtxsprzrox.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.sweek.top/Article/details/gtlghwtrqu.html

[T08] Kotlin：数据类
来源：http://dali.fengsongda.top/Article/details/gtfyqdskbh.html

data class User(val name: String, val age: Int)
来源：http://dali.sweek.top/Article/details/gtogdhjctn.html

[T09] Kotlin：扩展函数
来源：http://dali.tanke756.top/Article/details/gtzlhnbzsg.html

fun String.exclaim() = this + "!"
来源：http://dali.ehwqpu.com/Article/details/gtvottimss.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gtjiairpmh.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhoulong.xyz/Article/details/gtkejiapbq.html

[T11] Kotlin：协程
来源：http://dali.wangshuangyany.cn/Article/details/gtdykousik.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtepfpuswo.html

[T12] Kotlin：解构声明
来源：http://dali.hammf.cn/Article/details/gtcebkccvg.html

val (a, b) = Pair(1, 2)
来源：http://dali.gotoacloud.top/Article/details/gtcdduhuvu.html

[T13] Kotlin：只读 Map
来源：http://dali.hysaishi.cn/Article/details/gtyxmhfwyc.html

val m = mapOf("a" to 1)
来源：http://dali.fzhhl.top/Article/details/gtoerljiij.html

[T14] Kotlin：循环
来源：http://dali.cdnleiting.top/Article/details/gtlmosteyp.html

for (i in 1..10) println(i)
来源：http://dali.jlsjyb.cn/Article/details/gtyjgnqeim.html

[T15] Kotlin：接口
来源：http://dali.andypj.xyz/Article/details/gtorwnupys.html

interface Shape { fun area(): Double }
来源：http://dali.zdqjudy.top/Article/details/gtvehjtoog.html

[T16] Swift：Hello World
来源：http://dali.yangfankeji.com/Article/details/gtxhuockek.html

print("Hello")
来源：http://dali.dianchejie.cn/Article/details/gtdnaokvpn.html

[T17] Swift：变量与常量
来源：http://dali.shanyushiyangkeji.top/Article/details/gtscuynnfg.html

var a = 1;  let b = 2
来源：http://dali.jinghuilouyu.cn/Article/details/gtmdnwfidl.html

[T18] Swift：字符串插值
来源：http://dali.daria6918.cn/Article/details/gtlvofjqws.html

"值: \(b)"
来源：http://dali.haohaochexian.top/Article/details/gtaifmzwro.html

[T19] Swift：可选绑定
来源：http://dali.jinqigfzy.top/Article/details/gtsjimhzcz.html

if let n = opt { print(n) }
来源：http://dali.aizwys.cn/Article/details/gthyhtlfwe.html

[T20] Swift：数组操作
来源：http://dali.pycfn.com/Article/details/gthcuulmak.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.ydzc1.top/Article/details/gtsmdngvht.html

[T21] Swift：遍历
来源：http://dali.shangyingyoupin.top/Article/details/gtwlcrnldr.html

for x in a { print(x) }
来源：http://dali.pycfn.com/Article/details/gtznxrofzi.html

[T22] Swift：字典
来源：http://dali.daria6918.cn/Article/details/gtimufpztm.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.sweek.top/Article/details/gtjooxotbi.html

[T23] Swift：函数
来源：http://dali.haohaochexian.top/Article/details/gtbxcpimtl.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.ehwqpu.com/Article/details/gtoyyohryj.html

[T24] Swift：闭包
来源：http://dali.tanke756.top/Article/details/gtywilvnjw.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.xuanzx.com/Article/details/gttzyloscg.html

[T25] Swift：结构体
来源：http://dali.ppjwa.cn/Article/details/gtvnepovdb.html

struct P { var x: Int }
来源：http://dali.hnxiangtu.top/Article/details/gtsyvgvexc.html

[T26] Swift：类与重写
来源：http://dali.cheryme.top/Article/details/gtgyfutqnr.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gtkvikwcjr.html

[T27] Swift：错误处理
来源：http://dali.ppjwa.cn/Article/details/gtcheozkld.html

do { try f() } catch { print(error) }
来源：http://dali.guowangkeji.top/Article/details/gthfzcksmv.html

[T28] Swift：枚举
来源：http://dali.sweek.top/Article/details/gtjrmyaftv.html

enum Color { case red, green }
来源：http://dali.meibo888.top/Article/details/gtduzhhrfv.html

[T29] Swift：guard 提前返回
来源：http://dali.bjfxy.top/Article/details/gtjqueoyix.html

guard let x = opt else { return }
来源：http://dali.chenlongwang.top/Article/details/gtqlzdghzs.html

[T30] Swift：协议
来源：http://dali.xinyue.icu/Article/details/gtviarptih.html

protocol Shape { func area() -> Double }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcfcniayj.html

[T31] Lua：Hello World
来源：http://dali.fzhhl.top/Article/details/gtwrulnuhc.html

print("Hello")
来源：http://dali.wangshuangyany.cn/Article/details/gtznyhmscn.html

[T32] Lua：局部变量
来源：http://dali.bjfxy.top/Article/details/gtspxxxnqv.html

local a = 1
来源：http://dali.yvedp.cn/Article/details/gtyfcsukks.html

[T33] Lua：表（数组）
来源：http://dali.kuanghao11.cn/Article/details/gthdddniun.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.jinqigfzy.top/Article/details/gtrfkszaop.html

[T34] Lua：遍历表
来源：http://dali.fengsongda.top/Article/details/gtuwubaaia.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.tian-w.cn/Article/details/gtlqlnsxtv.html

[T35] Lua：字典表
来源：http://dali.xinyue.icu/Article/details/gtexxypgpm.html

local d = { a = 1 };  d.b = 2
来源：http://dali.yueranfly.top/Article/details/gtgasbmpgl.html

[T36] Lua：函数
来源：http://dali.tanke756.top/Article/details/gttvurugor.html

function add(a, b) return a + b end
来源：http://dali.mhx1999.top/Article/details/gtjucyhrtc.html

[T37] Lua：字符串拼接
来源：http://dali.ivvv.top/Article/details/gthaszxkop.html

"a" .. "b"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkxzyruuc.html

[T38] Lua：条件
来源：http://dali.meibo888.top/Article/details/gtrxgpgkov.html

if x > 0 then print("正") end
来源：http://dali.shangyingyoupin.top/Article/details/gturpptgpt.html

[T39] Lua：模式匹配
来源：http://dali.gogol.net.cn/Article/details/gthlpznrfl.html

string.find(s, "%d+")
来源：http://dali.bjfxy.top/Article/details/gtrjsrbiku.html

[T40] Lua：元表
来源：http://dali.guannengcc.top/Article/details/gtalilubdq.html

setmetatable({}, { __index = base })
来源：http://dali.fengsongda.top/Article/details/gthuvzcpek.html


<!-- 参考信息 -->