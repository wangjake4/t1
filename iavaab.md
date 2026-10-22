代发 wailian999

find . -name "*.tmp" -delete
来源：http://dali.zhixingplan.top/Article/details/gt2coxjegbv.html

[R46] 递归替换文件内容
来源：http://dali.dianchejie.cn/Article/details/gt2cldhvlgh.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.chenlongwang.top/Article/details/gt2nmkpdbav.html

[R47] sed 单行替换
来源：http://dali.bjfxy.top/Article/details/gt2mhziupcs.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ajailolo.html

[R48] awk 取指定列
来源：http://dali.yj20258.top/Article/details/gt2cdsdzapa.html

awk '{print $1, $3}' a.txt
来源：http://dali.ybcxt.top/Article/details/gt2iwtxcezd.html

[R49] awk 带条件
来源：http://dali.jlsjyb.cn/Article/details/gt2kskzmhus.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.haohaochexian.top/Article/details/gt2kyipvpyx.html

[R50] awk 求和
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hdggrcig.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.yj20258888.top/Article/details/gt2aayzcryq.html

[R51] 排序去重取前几
来源：http://dali.yongpay.top/Article/details/gt2aehyhjqb.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.pengpengdd.cyou/Article/details/gt2agqnbozk.html

[R52] 统计行数
来源：http://dali.bjfxy.top/Article/details/gt2ueikwesf.html

wc -l a.txt
来源：http://dali.sxryk.cn/Article/details/gt2ffvhowwx.html

[R53] 查看文件头与实时尾
来源：http://dali.pycfn.com/Article/details/gt2xfmqrwul.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.aibaodan.cn/Article/details/gt2etjwgtyg.html

[R54] 比较两个文件
来源：http://dali.gogol.net.cn/Article/details/gt2ykubeqzt.html

diff a.txt b.txt
来源：http://dali.chenlongwang.top/Article/details/gt2mhuthhcu.html

[R55] 压缩与解压
来源：http://dali.yvedp.cn/Article/details/gt2jrwennpi.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.shuidangran.top/Article/details/gt2hulaoazp.html

[R56] 远程拷贝
来源：http://dali.hammf.cn/Article/details/gt2mthjlmfv.html

scp file user@host:/path/
来源：http://dali.bjfxy.top/Article/details/gt2gbeixutt.html

[R57] 远程执行命令
来源：http://dali.sxryk.cn/Article/details/gt2gimoyikq.html

ssh user@host 'uptime'
来源：http://dali.yj202588.top/Article/details/gt2bsfntjqw.html

[R58] 下载文件
来源：http://dali.nanxuanxn.top/Article/details/gt2nibtihfk.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.birdmap.top/Article/details/gt2ixjugvgh.html

[R59] 发 POST JSON
来源：http://dali.gzhubu.top/Article/details/gt2romqotxo.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.pengpengdd.cyou/Article/details/gt2opmaksvz.html

[R60] 只看 HTTP 状态码
来源：http://dali.ivvv.top/Article/details/gt2xxhgtnke.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.yueranfly.top/Article/details/gt2txjnjgdl.html

[R61] 磁盘占用
来源：http://dali.shangyingyoupin.top/Article/details/gt2udncyaud.html

df -h;  du -sh *
来源：http://dali.svipenyu.cn/Article/details/gt2xqshipeu.html

[R62] 找最占空间的文件
来源：http://dali.zdqjudy.top/Article/details/gt2gtbihhmg.html

du -ah . | sort -rh | head -10
来源：http://dali.chenjidiqi.icu/Article/details/gt2xowfnnrf.html

[R63] 内存与进程
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wtqgkmff.html

free -h;  ps aux | grep nginx
来源：http://dali.ydzc1.top/Article/details/gt2szmmoqdk.html

[R64] 结束进程
来源：http://dali.yj202588.top/Article/details/gt2ptehnfjt.html

kill -9 $(pgrep -f app.py)
来源：http://dali.xinyue.icu/Article/details/gt2lonrvmrk.html

[R65] 查看端口占用
来源：http://dali.jinqigufen.top/Article/details/gt2jtmiamns.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.chenzaomai.com/Article/details/gt2tenoucnc.html

[R66] 定时任务
来源：http://dali.cheryme.top/Article/details/gt2rblqwlpg.html

crontab -e;  crontab -l
来源：http://dali.nwbrower.top/Article/details/gt2jhpfavqw.html

[R67] 生成随机十六进制串
来源：http://dali.ydzc1.top/Article/details/gt2vycebwzi.html

openssl rand -hex 16
来源：http://dali.vqdsnc.cn/Article/details/gt2hcysxvyt.html

[R68] 计算文件校验值
来源：http://dali.yj202588.top/Article/details/gt2sgoflmoj.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gwwveiwa.html

[R69] 生成随机密码
来源：http://dali.hnqzz.top/Article/details/gt2drfofbqr.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2tbzcdgpu.html

[R70] 时间戳与互转
来源：http://dali.gzhubu.top/Article/details/gt2vliaqtgv.html

date +%s;  date -d @1700000000
来源：http://dali.zhoulong.xyz/Article/details/gt2mlbdpgun.html

[R71] 日期格式化
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lkkgchvi.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.jyoumei.cn/Article/details/gt2iswtktbo.html

[R72] 等待端口就绪
来源：http://dali.daria6918.cn/Article/details/gt2kgfwqopw.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.jlsjyb.cn/Article/details/gt2xwfjpvwc.html

[R73] 分割大日志
来源：http://dali.dianchejie.cn/Article/details/gt2vdhqxcuq.html

split -l 1000 big.log part_
来源：http://dali.jqgufenzy.top/Article/details/gt2iygrmgyv.html

[R74] 批量重命名
来源：http://dali.chenzaomai.com/Article/details/gt2ewlnlxdh.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.hammf.cn/Article/details/gt2wgiijtrj.html

[R75] 导出环境变量
来源：http://dali.daria6918.cn/Article/details/gt2ehmdkria.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.jqgufenzy.top/Article/details/gt2ysjetkss.html

[R76] 使用临时文件
来源：http://dali.guannengcc.top/Article/details/gt2dslkwkpj.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.gaohongyu789.top/Article/details/gt2mrdzdbbq.html

[R77] 读取用户输入
来源：http://dali.xuetiantiany.cn/Article/details/gt2ksgxhhkl.html

read -rp "请输入: " ans
来源：http://dali.cucudq.cn/Article/details/gt2kauwfccp.html

[R78] 交互式菜单
来源：http://dali.havefunace.top/Article/details/gt2upefckzw.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.hysaishi.cn/Article/details/gt2ooqbjrjp.html

[R79] 解析命令行选项
来源：http://dali.pengpengdd.cyou/Article/details/gt2ccsjlgwz.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.316326.xyz/Article/details/gt2weqtsina.html

[R80] 查看脚本执行耗时
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yxfhqkbo.html

time ./run.sh
来源：http://dali.jianghu66.top/Article/details/gt2wcmyaqba.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2nvemngvw.html

S. C / C++ 专题
来源：http://dali.zycfv.cn/Article/details/gt2nbnwnkih.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2ccoqwfna.html

[S01] C：Hello World
来源：http://dali.ppjwa.cn/Article/details/gt2fganewjt.html

#include <stdio.h>
来源：http://dali.yanxiufei.cn/Article/details/gt2skrmeusv.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.guowangkeji.top/Article/details/gt2euzvxsqp.html

[S02] C：变量与格式化输出
来源：http://dali.kuanghao11.cn/Article/details/gt2dtwgmtof.html

int a = 10; printf("%d\n", a);
来源：http://dali.jinqigufen.top/Article/details/gt2qwsebxtf.html

[S03] C：读入整数
来源：http://dali.zhiwuduotai.top/Article/details/gt2tezzhaqt.html

int x; scanf("%d", &x);
来源：http://dali.fengsongda.top/Article/details/gt2fxniricj.html

[S04] C：字符串复制
来源：http://dali.andypj.xyz/Article/details/gt2ddhztvpy.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zdqjudy.top/Article/details/gt2xwidgvld.html

[S05] C：字符串长度
来源：http://dali.pycfn.com/Article/details/gt2axoxiuks.html

strlen(s)
来源：http://dali.9152youxi.cn/Article/details/gt2tjudyjpn.html

[S06] C：字符串比较
来源：http://dali.xuetiantiany.cn/Article/details/gt2nfbquemg.html

strcmp(a, b) == 0
来源：http://dali.jianghu66.top/Article/details/gt2kvheufht.html

[S07] C：数组遍历求和
来源：http://dali.dashuyun.cn/Article/details/gt2kxulzteh.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhixingplan.top/Article/details/gt2owgfnygt.html

[S08] C：动态内存分配与释放
来源：http://dali.bjfxy.top/Article/details/gt2mrvrgrzw.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.nanxuanxn.top/Article/details/gt2hqxcdazp.html

[S09] C：结构体定义与初始化
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dhhkiaiy.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.smart0.xyz/Article/details/gt2vwhaxzis.html

[S10] C：指针与解引用
来源：http://dali.ivvv.top/Article/details/gt2wcvqymun.html

int *p = &a;  *p = 5;
来源：http://dali.hongshengwenyu.top/Article/details/gt2ohgofpdn.html

[S11] C：逐行读文件
来源：http://dali.hfpthk.cn/Article/details/gt2tyscjpje.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.nanxinkj.top/Article/details/gt2fxqixpac.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.feifeiyinyue.top/Article/details/gt2etqdcejo.html

fclose(f);
来源：http://dali.xinyue.icu/Article/details/gt2etgabimb.html

[S12] C：写文件
来源：http://dali.jinqigufen.top/Article/details/gt2uizhbvsk.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.tian-w.cn/Article/details/gt2zitmgdjf.html

[S13] C：宏定义
来源：http://dali.yanxiufei.cn/Article/details/gt2osvtxhhn.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fvvlsfhf.html

[S14] C：枚举
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uqazpevg.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.ybcxt.top/Article/details/gt2kfmiwqiu.html

[S15] C：类型转换
来源：http://dali.sxryk.cn/Article/details/gt2filtytxo.html

(double) a / b
来源：http://dali.xuetiantiany.cn/Article/details/gt2sezjmyrf.html

[S16] C：位操作置位
来源：http://dali.zhoulong.xyz/Article/details/gt2vbmnajju.html

x |= (1 << 3);
来源：http://dali.jqgfzy.top/Article/details/gt2qqhvnoil.html

[S17] C：安全拼接字符串
来源：http://dali.hongshengwenyu.top/Article/details/gt2jhybpkhm.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.dianchejie.cn/Article/details/gt2jfoojrtj.html

[S18] C：命令行参数
来源：http://dali.gzhubu.top/Article/details/gt2hilbjnlt.html

int main(int argc, char **argv)
来源：http://dali.wangdashe.top/Article/details/gt2pbkwsube.html

[S19] C：快速排序
来源：http://dali.fzhhl.top/Article/details/gt2rgunufsd.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.yj20258888.top/Article/details/gt2coxqzizq.html

[S20] C：二分查找
来源：http://dali.ppjwa.cn/Article/details/gt2jdrcrmtv.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.aibaodan.cn/Article/details/gt2dzxsmrwg.html

[S21] C：字符类别判断
来源：http://dali.yuxming.cn/Article/details/gt2wjtrpgpc.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.pengpengdd.cyou/Article/details/gt2grvkozzk.html

[S22] C：字符串转数字
来源：http://dali.svipenyu.cn/Article/details/gt2htzszmhg.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.guannengcc.top/Article/details/gt2jjoyfkzk.html

[S23] C：随机数
来源：http://dali.jqgufenzy.top/Article/details/gt2bvdczens.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.hywenlv.cn/Article/details/gt2vdebpnff.html

[S24] C：获取本地时间
来源：http://dali.bjfxy.top/Article/details/gt2yxzvjmwy.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.cheryme.top/Article/details/gt2jhltytba.html

[S25] C：内存拷贝
来源：http://dali.haohaochexian.top/Article/details/gt2elawiqez.html

memcpy(dst, src, n);
来源：http://dali.gzhubu.top/Article/details/gt2qnhjvqhc.html

[S26] C：内存清零
来源：http://dali.gotoacloud.top/Article/details/gt2fcbraodq.html

memset(a, 0, sizeof a);
来源：http://dali.xuetiantiany.cn/Article/details/gt2sbkcrsdg.html

[S27] C：定义常量
来源：http://dali.smart0.xyz/Article/details/gt2dfoyyuty.html

const double PI = 3.14159;
来源：http://dali.dianchejie.cn/Article/details/gt2jhhieout.html

[S28] C：静态变量
来源：http://dali.xylfe.cn/Article/details/gt2accdystx.html

static int counter = 0;
来源：http://dali.9152youxi.cn/Article/details/gt2szbreflj.html

[S29] C：变参函数
来源：http://dali.xylfe.cn/Article/details/gt2vqligzct.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.sysykeji.top/Article/details/gt2mzktungv.html

[S30] C：头文件保护
来源：http://dali.jlsjyb.cn/Article/details/gt2nrtiziul.html

#ifndef X_H
来源：http://dali.shangyingyoupin.top/Article/details/gt2lsavjvop.html

#define X_H
来源：http://dali.jqgufenzy.top/Article/details/gt2rjowmzee.html

#endif
来源：http://dali.daria6918.cn/Article/details/gt2ejqoaqrb.html

[S31] C++：Hello World
来源：http://dali.xuanzx.com/Article/details/gt2ylbbleud.html

#include <iostream>
来源：http://dali.shuidangran.top/Article/details/gt2qcwcoopi.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.jinqigufen.top/Article/details/gt2ydboncec.html

[S32] C++：字符串
来源：http://dali.xziqi.cn/Article/details/gt2fzwmzwkq.html

std::string s = "hi";  s += "!";
来源：http://dali.andypj.xyz/Article/details/gt2yxiazttr.html

[S33] C++：vector 增删
来源：http://dali.gotoacloud.top/Article/details/gt2fdrauwpc.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.cdnleiting.top/Article/details/gt2nppnatob.html

[S34] C++：遍历 vector
来源：http://dali.tanke756.top/Article/details/gt2cniewlzo.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.tianlin.xyz/Article/details/gt2clfxgrqh.html

[S35] C++：map
来源：http://dali.fengsongda.top/Article/details/gt2txjppksy.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wzsbqqxt.html

[S36] C++：unordered_map
来源：http://dali.cdnleiting.top/Article/details/gt2kddkdano.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.cucudq.cn/Article/details/gt2ygkwzwpz.html

[S37] C++：set
来源：http://dali.hongshengwenyu.top/Article/details/gt2pdfmpkuw.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.wangshuangyany.cn/Article/details/gt2jnftiars.html

[S38] C++：排序
来源：http://dali.cdnleiting.top/Article/details/gt2jjrdmygn.html

std::sort(v.begin(), v.end());
来源：http://dali.hammf.cn/Article/details/gt2tiwhsjzg.html

[S39] C++：自定义比较器排序
来源：http://dali.tanke756.top/Article/details/gt2xnzzwnfg.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hdnahcoy.html

[S40] C++：查找元素
来源：http://dali.guannengcc.top/Article/details/gt2nlfciyoq.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.0kj1m.cn/Article/details/gt2cpusehlh.html

[S41] C++：类与构造函数
来源：http://dali.9152youxi.cn/Article/details/gt2znnxycvn.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.hnxiangtu.top/Article/details/gt2ighzxnpa.html

[S42] C++：继承与虚函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fhakfyar.html

class B : public Base { public: void f() override {} };
来源：http://dali.ivvv.top/Article/details/gt2gobpgzcj.html

[S43] C++：智能指针
来源：http://dali.jqgufenzy.top/Article/details/gt2coevxfnb.html

auto p = std::make_unique<int>(5);
来源：http://dali.bjfxy.top/Article/details/gt2vmcsuyjr.html

[S44] C++：引用传参
来源：http://dali.gogol.net.cn/Article/details/gt2uzynzdeu.html

void inc(int &x) { ++x; }
来源：http://dali.sysykeji.top/Article/details/gt2cxsiaxya.html

[S45] C++：lambda
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yyscuage.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.nwbrower.top/Article/details/gt2msvtpkli.html

[S46] C++：函数模板
来源：http://dali.ppjwa.cn/Article/details/gt2jzooiyqo.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.gogol.net.cn/Article/details/gt2nxohdcjn.html

[S47] C++：结构化绑定遍历
来源：http://dali.bjfxy.top/Article/details/gt2dwvjtniy.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.tanke756.top/Article/details/gt2ypnbjvga.html

[S48] C++：逐行读文件
来源：http://dali.cheryme.top/Article/details/gt2disbexse.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.dianchejie.cn/Article/details/gt2sldtcaho.html

while (std::getline(in, line)) { }
来源：http://dali.xziqi.cn/Article/details/gt2fmyjqnid.html

[S49] C++：写文件
来源：http://dali.0kj1m.cn/Article/details/gt2noyemdtq.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.sysykeji.top/Article/details/gt2zcducdjb.html

[S50] C++：格式化数字
来源：http://dali.cashguo.top/Article/details/gt2feuvcnyy.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2irwlkpaw.html

[S51] C++：显式类型转换
来源：http://dali.cashguo.top/Article/details/gt2sylpqdju.html

static_cast<double>(a) / b
来源：http://dali.cqqwz.cn/Article/details/gt2vdkvircv.html

[S52] C++：const 与 noexcept
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bmywnfej.html

int size() const noexcept { return n_; }
来源：http://dali.ybcxt.top/Article/details/gt2cxyspqvc.html

[S53] C++：移动语义
来源：http://dali.yuanzhike.top/Article/details/gt2klrokrqf.html

std::vector<int> w = std::move(v);
来源：http://dali.nwbrower.top/Article/details/gt2szlepcwi.html

[S54] C++：异常处理
来源：http://dali.sxryk.cn/Article/details/gt2pfalckgl.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.meibo888.top/Article/details/gt2olhlxhox.html

[S55] C++：结构化绑定
来源：http://dali.tian-w.cn/Article/details/gt2tybvxzpg.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.yj202588.top/Article/details/gt2dvusmmzu.html

[S56] C++：optional
来源：http://dali.9152youxi.cn/Article/details/gt2zieeqrwc.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.xinyue.icu/Article/details/gt2rtgwgbfl.html

[S57] C++：编译期常量
来源：http://dali.jianghu66.top/Article/details/gt2zfhcqefh.html

constexpr int N = 10;
来源：http://dali.gogol.net.cn/Article/details/gt2cqgspclx.html

[S58] C++：命名空间
来源：http://dali.jqgfzy.top/Article/details/gt2pbjsazlu.html

namespace ns { int f() { return 1; } }
来源：http://dali.hnqzz.top/Article/details/gt2oqudfidn.html

[S59] C++：静态断言
来源：http://dali.smart0.xyz/Article/details/gt2ampmimuz.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.0kj1m.cn/Article/details/gt2afyuysju.html

[S60] C++：遍历并删除元素
来源：http://dali.wangshuangyany.cn/Article/details/gt2bozijnab.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.pycfn.com/Article/details/gt2gsolkyys.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2aqnmfyxk.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.ivvv.top/Article/details/gt2rwjzbyvg.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2vrxwahco.html

[T01] Kotlin：Hello World
来源：http://dali.hnqzz.top/Article/details/gt2dctbrwan.html

println("Hello")
来源：http://dali.guowangkeji.top/Article/details/gt2vqyxdqyg.html

[T02] Kotlin：变量
来源：http://dali.hysaishi.cn/Article/details/gt2rmoxiqvo.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.jqgfzy.top/Article/details/gt2mlpurpfm.html

[T03] Kotlin：字符串模板
来源：http://dali.zycfv.cn/Article/details/gt2xjkqxyoa.html

"值: $b"
来源：http://dali.haohaochexian.top/Article/details/gt2arnyfctg.html

[T04] Kotlin：空安全
来源：http://dali.cdnleiting.top/Article/details/gt2pemobrsp.html

val n: String? = null;  n?.length
来源：http://dali.hfpthk.cn/Article/details/gt2wuygungh.html

[T05] Kotlin：when 表达式
来源：http://dali.meibo888.top/Article/details/gt2ecbkhndq.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhiwuduotai.top/Article/details/gt2vvcbhqkc.html

[T06] Kotlin：集合映射
来源：http://dali.svipenyu.cn/Article/details/gt2oxtvurvr.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.yangfankeji.com/Article/details/gt2wkoonqjq.html

[T07] Kotlin：集合过滤
来源：http://dali.wangshuangyany.cn/Article/details/gt2ndpbrcai.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.jqgfzy.top/Article/details/gt2fntenczl.html

[T08] Kotlin：数据类
来源：http://dali.shzxlz.cn/Article/details/gt2xewwkakw.html

data class User(val name: String, val age: Int)
来源：http://dali.sysykeji.top/Article/details/gt2lucslude.html

[T09] Kotlin：扩展函数
来源：http://dali.hongshengwenyu.top/Article/details/gt2bmxublic.html

fun String.exclaim() = this + "!"
来源：http://dali.9152youxi.cn/Article/details/gt2mcyqpcaz.html

[T10] Kotlin：默认参数
来源：http://dali.chenlongwang.top/Article/details/gt2awxhtbzv.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.sysykeji.top/Article/details/gt2redenayh.html

[T11] Kotlin：协程
来源：http://dali.kuanghao11.cn/Article/details/gt2wfvrworc.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.tianlin.xyz/Article/details/gt2jnktmmnv.html

[T12] Kotlin：解构声明
来源：http://dali.bjfxy.top/Article/details/gt2qnqkfzxc.html

val (a, b) = Pair(1, 2)
来源：http://dali.yuxming.cn/Article/details/gt2zzkrwxzu.html

[T13] Kotlin：只读 Map
来源：http://dali.ppjwa.cn/Article/details/gt2xkfmuudv.html

val m = mapOf("a" to 1)
来源：http://dali.jianghu66.top/Article/details/gt2wmejrixq.html

[T14] Kotlin：循环
来源：http://dali.chenlongwang.top/Article/details/gt2eyyorcrr.html

for (i in 1..10) println(i)
来源：http://dali.xuanzx.com/Article/details/gt2lmtzejyb.html

[T15] Kotlin：接口
来源：http://dali.zhiwuduotai.top/Article/details/gt2sahkidlg.html

interface Shape { fun area(): Double }
来源：http://dali.svipenyu.cn/Article/details/gt2kvzdzone.html

[T16] Swift：Hello World
来源：http://dali.havefunace.top/Article/details/gt2pzmrvikv.html

print("Hello")
来源：http://dali.fengsongda.top/Article/details/gt2retwdojz.html

[T17] Swift：变量与常量
来源：http://dali.hnqzz.top/Article/details/gt2rgsnnoue.html

var a = 1;  let b = 2
来源：http://dali.yj202588.top/Article/details/gt2wpybrjrl.html

[T18] Swift：字符串插值
来源：http://dali.chenjidiqi.icu/Article/details/gt2cwlozvyu.html

"值: \(b)"
来源：http://dali.jinqigfzy.top/Article/details/gt2mzjhfmgz.html

[T19] Swift：可选绑定
来源：http://dali.9152youxi.cn/Article/details/gt2hnhqmphh.html

if let n = opt { print(n) }
来源：http://dali.cdnleiting.top/Article/details/gt2xzcpwuwb.html

[T20] Swift：数组操作
来源：http://dali.zhongyouzk.top/Article/details/gt2wzvvmdqu.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.meibo888.top/Article/details/gt2cuidlifj.html

[T21] Swift：遍历
来源：http://dali.birdmap.top/Article/details/gt2reofnery.html

for x in a { print(x) }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tvjhisfe.html

[T22] Swift：字典
来源：http://dali.yj202588.top/Article/details/gt2fvjbeais.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhoulong.xyz/Article/details/gt2lvxtzabb.html

[T23] Swift：函数
来源：http://dali.svipenyu.cn/Article/details/gt2wkvetjaf.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jjueeige.html

[T24] Swift：闭包
来源：http://dali.xuanzx.com/Article/details/gt2iqahhvcz.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.feifeiyinyue.top/Article/details/gt2qvejzqgv.html

[T25] Swift：结构体
来源：http://dali.yj20258888.top/Article/details/gt2xxnlluob.html

struct P { var x: Int }
来源：http://dali.xuanzx.com/Article/details/gt2foznefat.html

[T26] Swift：类与重写
来源：http://dali.nwbrower.top/Article/details/gt2vktkkujf.html

class A: Base { override func f() {} }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fuhsslpb.html

[T27] Swift：错误处理
来源：http://dali.daxiang520.top/Article/details/gt2ngekmejl.html

do { try f() } catch { print(error) }
来源：http://dali.tanke756.top/Article/details/gt2sprsvhqo.html

[T28] Swift：枚举
来源：http://dali.zhiwuduotai.top/Article/details/gt2uivfyzml.html

enum Color { case red, green }
来源：http://dali.hnqzz.top/Article/details/gt2khawgbnn.html

[T29] Swift：guard 提前返回
来源：http://dali.redwolf501.top/Article/details/gt2ixdaibqp.html

guard let x = opt else { return }
来源：http://dali.dashuyun.cn/Article/details/gt2dymmsaoe.html

[T30] Swift：协议
来源：http://dali.yj20258888.top/Article/details/gt2jibhsxrn.html

protocol Shape { func area() -> Double }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bpirbbgf.html

[T31] Lua：Hello World
来源：http://dali.ppjwa.cn/Article/details/gt2cuawsbvn.html

print("Hello")
来源：http://dali.sysykeji.top/Article/details/gt2riyuyrqw.html

[T32] Lua：局部变量
来源：http://dali.zhixingplan.top/Article/details/gt2pifknfqb.html

local a = 1
来源：http://dali.redwolf501.top/Article/details/gt2kkzgrkyt.html

[T33] Lua：表（数组）
来源：http://dali.hnqzz.top/Article/details/gt2xyfkcddl.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.316326.xyz/Article/details/gt2qbyvurhk.html

[T34] Lua：遍历表
来源：http://dali.svipenyu.cn/Article/details/gt2hrcgbema.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.yanxiufei.cn/Article/details/gt2crgaqsmg.html

[T35] Lua：字典表
来源：http://dali.pengpengdd.cyou/Article/details/gt2izwpfomv.html

local d = { a = 1 };  d.b = 2
来源：http://dali.ydzc1.top/Article/details/gt2amtqxhuv.html

[T36] Lua：函数
来源：http://dali.snrcjt.cn/Article/details/gt2fxyftbsx.html

function add(a, b) return a + b end
来源：http://dali.hammf.cn/Article/details/gt2nbmhogno.html

[T37] Lua：字符串拼接
来源：http://dali.9152youxi.cn/Article/details/gt2fdrictso.html

"a" .. "b"
来源：http://dali.chenlongwang.top/Article/details/gt2dkfehcmn.html

[T38] Lua：条件
来源：http://dali.zhengqikj.top/Article/details/gt2xchzcimp.html

if x > 0 then print("正") end
来源：http://dali.yj20258888.top/Article/details/gt2cqqqstie.html

[T39] Lua：模式匹配
来源：http://dali.chenzaomai.com/Article/details/gt2llgsprsr.html

string.find(s, "%d+")
来源：http://dali.yj20258.top/Article/details/gt2znikgqvb.html

[T40] Lua：元表
来源：http://dali.aizwys.cn/Article/details/gt2sfwernsv.html

setmetatable({}, { __index = base })
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dmoxeltv.html

[T41] Perl：Hello World
来源：http://dali.aizwys.cn/Article/details/gt2nppiktys.html

print "Hello\n";
来源：http://dali.jinqigufen.top/Article/details/gt2auwlsgxa.html

[T42] Perl：变量类型
来源：http://dali.shangyingyoupin.top/Article/details/gt2gohcqrwg.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2alcwqmkv.html

[T43] Perl：字符串插值
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xfvbkafy.html

"值: $a"
来源：http://dali.guowangkeji.top/Article/details/gt2ageisiyq.html

[T44] Perl：条件
来源：http://dali.snrcjt.cn/Article/details/gt2gztnbjtz.html

if ($a > 0) { print "正"; }
来源：http://dali.tian-w.cn/Article/details/gt2kleasfbm.html

[T45] Perl：数组遍历
来源：http://dali.nwbrower.top/Article/details/gt2oqobquwt.html

for my $x (@arr) { print $x; }
来源：http://dali.jqgufenzy.top/Article/details/gt2bfzokhhm.html

[T46] Perl：哈希操作
来源：http://dali.xuetiantiany.cn/Article/details/gt2pfjzsayz.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.xylfe.cn/Article/details/gt2bdwxzpwa.html

[T47] Perl：正则捕获
来源：http://dali.andypj.xyz/Article/details/gt2scacdkdd.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.hammf.cn/Article/details/gt2dpoxwxbf.html

[T48] Perl：正则替换
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tgebqvqu.html

$s =~ s/old/new/g;
来源：http://dali.guannengcc.top/Article/details/gt2ptcalodr.html


<!-- 参考信息 -->