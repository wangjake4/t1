代发 wailian999

cmd >/dev/null 2>&1
来源：http://dali.yuxming.cn/Article/details/gt2qiflclvn.html

[R42] 输入重定向
来源：http://dali.ehwqpu.com/Article/details/gt2cbidjkqb.html

wc -l < a.txt
来源：http://dali.ybcxt.top/Article/details/gt2frokpiac.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pavixyoa.html

find . -name "*.log" -type f
来源：http://dali.316326.xyz/Article/details/gt2ehpkmbfa.html

[R44] 按修改时间查找
来源：http://dali.cqqwz.cn/Article/details/gt2luigdpkr.html

find . -mtime -7 -type f
来源：http://dali.bjfxy.top/Article/details/gt2kthrgovk.html

[R45] 批量删除
来源：http://dali.c1oappe.top/Article/details/gt2mgikuclj.html

find . -name "*.tmp" -delete
来源：http://dali.chenzaomai.com/Article/details/gt2hginhekx.html

[R46] 递归替换文件内容
来源：http://dali.tianlin.xyz/Article/details/gt2npunrxgj.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhoulong.xyz/Article/details/gt2gsfwpvzj.html

[R47] sed 单行替换
来源：http://dali.shzxlz.cn/Article/details/gt2zdmohuwa.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.shuidangran.top/Article/details/gt2otkvtsbf.html

[R48] awk 取指定列
来源：http://dali.xylfe.cn/Article/details/gt2fzqsdwgk.html

awk '{print $1, $3}' a.txt
来源：http://dali.havefunace.top/Article/details/gt2kzhqfsrj.html

[R49] awk 带条件
来源：http://dali.ppjwa.cn/Article/details/gt2lpegqlnk.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.ybcxt.top/Article/details/gt2zgnmuhva.html

[R50] awk 求和
来源：http://dali.9152youxi.cn/Article/details/gt2annvmpug.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.tanke756.top/Article/details/gt2tjxnoewo.html

[R51] 排序去重取前几
来源：http://dali.9152youxi.cn/Article/details/gt2cilualzh.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.9152youxi.cn/Article/details/gt2gylupour.html

[R52] 统计行数
来源：http://dali.smart0.xyz/Article/details/gt2zkhgdukj.html

wc -l a.txt
来源：http://dali.0kj1m.cn/Article/details/gt2jxdrahls.html

[R53] 查看文件头与实时尾
来源：http://dali.cashguo.top/Article/details/gt2tlostord.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.sweek.top/Article/details/gt2lklehwjg.html

[R54] 比较两个文件
来源：http://dali.yj20258888.top/Article/details/gt2sehtyfwl.html

diff a.txt b.txt
来源：http://dali.cdnleiting.top/Article/details/gt2qumqbcba.html

[R55] 压缩与解压
来源：http://dali.tian-w.cn/Article/details/gt2zhwgsznb.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.ydzc1.top/Article/details/gt2fxlqzwac.html

[R56] 远程拷贝
来源：http://dali.wangshuangyany.cn/Article/details/gt2ievyvgjj.html

scp file user@host:/path/
来源：http://dali.9152youxi.cn/Article/details/gt2wqrdjbpm.html

[R57] 远程执行命令
来源：http://dali.shangyingyoupin.top/Article/details/gt2bljwpcdc.html

ssh user@host 'uptime'
来源：http://dali.nanxuanxn.top/Article/details/gt2tayobcgk.html

[R58] 下载文件
来源：http://dali.gogol.net.cn/Article/details/gt2lrcupyiv.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.birdmap.top/Article/details/gt2qjzgdjps.html

[R59] 发 POST JSON
来源：http://dali.zdqjudy.top/Article/details/gt2xpjdrbey.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2shbfzmyq.html

[R60] 只看 HTTP 状态码
来源：http://dali.feifeiyinyue.top/Article/details/gt2ywizqvjn.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.c1oappe.top/Article/details/gt2fkgxhxob.html

[R61] 磁盘占用
来源：http://dali.wangdashe.top/Article/details/gt2aqhqcmvy.html

df -h;  du -sh *
来源：http://dali.zdqjudy.top/Article/details/gt2ynzpfmpd.html

[R62] 找最占空间的文件
来源：http://dali.sxryk.cn/Article/details/gt2prylugnr.html

du -ah . | sort -rh | head -10
来源：http://dali.gotoacloud.top/Article/details/gt2dikxtyne.html

[R63] 内存与进程
来源：http://dali.chenjidiqi.icu/Article/details/gt2hyzhzazr.html

free -h;  ps aux | grep nginx
来源：http://dali.cashguo.top/Article/details/gt2qpiptwqp.html

[R64] 结束进程
来源：http://dali.zycfv.cn/Article/details/gt2uqlztfhl.html

kill -9 $(pgrep -f app.py)
来源：http://dali.yonumen.top/Article/details/gt2dcbawtym.html

[R65] 查看端口占用
来源：http://dali.nwbrower.top/Article/details/gt2uhbiayqc.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.0kj1m.cn/Article/details/gt2jfszaqnr.html

[R66] 定时任务
来源：http://dali.pycfn.com/Article/details/gt2vnyhoajh.html

crontab -e;  crontab -l
来源：http://dali.hongshengwenyu.top/Article/details/gt2gguanykc.html

[R67] 生成随机十六进制串
来源：http://dali.wangdashe.top/Article/details/gt2yxtkgene.html

openssl rand -hex 16
来源：http://dali.zdqjudy.top/Article/details/gt2dadleaqp.html

[R68] 计算文件校验值
来源：http://dali.cheryme.top/Article/details/gt2ozgvvfov.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.ydzc1.top/Article/details/gt2reikjjrr.html

[R69] 生成随机密码
来源：http://dali.daxiang520.top/Article/details/gt2furfqzwn.html

head -c 16 /dev/urandom | base64
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lngqfaza.html

[R70] 时间戳与互转
来源：http://dali.jinghuilouyu.cn/Article/details/gt2evtboion.html

date +%s;  date -d @1700000000
来源：http://dali.yj20258888.top/Article/details/gt2vjkxewkk.html

[R71] 日期格式化
来源：http://dali.zhiwuduotai.top/Article/details/gt2kimmpzqa.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.iojbl.cn/Article/details/gt2jdbsmmrn.html

[R72] 等待端口就绪
来源：http://dali.smart0.xyz/Article/details/gt2dkpvrtbr.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.jqgufenzy.top/Article/details/gt2zykktiep.html

[R73] 分割大日志
来源：http://dali.xuetiantiany.cn/Article/details/gt2vjjvatky.html

split -l 1000 big.log part_
来源：http://dali.jqgufenzy.top/Article/details/gt2xyihgfex.html

[R74] 批量重命名
来源：http://dali.redwolf501.top/Article/details/gt2eubcbeyy.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.feifeiyinyue.top/Article/details/gt2hnywxqmw.html

[R75] 导出环境变量
来源：http://dali.svipenyu.cn/Article/details/gt2lhgyopkq.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.snrcjt.cn/Article/details/gt2nbayhzyg.html

[R76] 使用临时文件
来源：http://dali.jinqigfzy.top/Article/details/gt2brkshkqm.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.vqdsnc.cn/Article/details/gt2fubwtzdp.html

[R77] 读取用户输入
来源：http://dali.yj20258888.top/Article/details/gt2lkbmgqie.html

read -rp "请输入: " ans
来源：http://dali.zhiwuduotai.top/Article/details/gt2dvzywktq.html

[R78] 交互式菜单
来源：http://dali.feifeiyinyue.top/Article/details/gt2thgxvadj.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.yuxming.cn/Article/details/gt2qgejarcf.html

[R79] 解析命令行选项
来源：http://dali.gogol.net.cn/Article/details/gt2vispbjgk.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.havefunace.top/Article/details/gt2qknkwsws.html

[R80] 查看脚本执行耗时
来源：http://dali.9152youxi.cn/Article/details/gt2jzbjdlku.html

time ./run.sh
来源：http://dali.xylfe.cn/Article/details/gt2rwicohwv.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gt2frlsnndn.html

S. C / C++ 专题
来源：http://dali.cqqwz.cn/Article/details/gt2wblsgwru.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2maqixzod.html

[S01] C：Hello World
来源：http://dali.xuanzx.com/Article/details/gt2etfdumty.html

#include <stdio.h>
来源：http://dali.chenzaomai.com/Article/details/gt2rgvbvnhg.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.yuanzhike.top/Article/details/gt2fzrifhjo.html

[S02] C：变量与格式化输出
来源：http://dali.gaohongyu789.top/Article/details/gt2htnveiji.html

int a = 10; printf("%d\n", a);
来源：http://dali.hnxiangtu.top/Article/details/gt2lcyvkwym.html

[S03] C：读入整数
来源：http://dali.ydzc1.top/Article/details/gt2svypsfhi.html

int x; scanf("%d", &x);
来源：http://dali.cucudq.cn/Article/details/gt2uxfzywwt.html

[S04] C：字符串复制
来源：http://dali.chenjidiqi.icu/Article/details/gt2fwkivpgc.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhongyouzk.top/Article/details/gt2sdoiqeyn.html

[S05] C：字符串长度
来源：http://dali.xuanzx.com/Article/details/gt2wetazevs.html

strlen(s)
来源：http://dali.zhengqikj.top/Article/details/gt2xsqgcvey.html

[S06] C：字符串比较
来源：http://dali.ivvv.top/Article/details/gt2pactxjsg.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2dvevaxtx.html

[S07] C：数组遍历求和
来源：http://dali.feifeiyinyue.top/Article/details/gt2murxymrw.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.nanxinkj.top/Article/details/gt2septbkhd.html

[S08] C：动态内存分配与释放
来源：http://dali.guannengcc.top/Article/details/gt2znburqpc.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.svipenyu.cn/Article/details/gt2slvsbrac.html

[S09] C：结构体定义与初始化
来源：http://dali.tanke756.top/Article/details/gt2wqhvqlpg.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.yj202588.top/Article/details/gt2pjqdmlws.html

[S10] C：指针与解引用
来源：http://dali.chenlongwang.top/Article/details/gt2vvzflrrb.html

int *p = &a;  *p = 5;
来源：http://dali.hnxiangtu.top/Article/details/gt2fbopvvzj.html

[S11] C：逐行读文件
来源：http://dali.guannengcc.top/Article/details/gt2ffgrkbfr.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.quarkkingdee.top/Article/details/gt2yxhsduyh.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.gotoacloud.top/Article/details/gt2kmmzzcnk.html

fclose(f);
来源：http://dali.pengpengdd.cyou/Article/details/gt2nfbsitzz.html

[S12] C：写文件
来源：http://dali.hnqzz.top/Article/details/gt2ygxkvmit.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.yj20258.top/Article/details/gt2pbhqguft.html

[S13] C：宏定义
来源：http://dali.9152youxi.cn/Article/details/gt2zszykzzh.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.snrcjt.cn/Article/details/gt2nrcmlrih.html

[S14] C：枚举
来源：http://dali.yongpay.top/Article/details/gt2lopbrsxn.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.yj20258.top/Article/details/gt2zkgljunt.html

[S15] C：类型转换
来源：http://dali.quarkkingdee.top/Article/details/gt2vevtjpjw.html

(double) a / b
来源：http://dali.nwbrower.top/Article/details/gt2zyihtlyj.html

[S16] C：位操作置位
来源：http://dali.vqdsnc.cn/Article/details/gt2sdagpzto.html

x |= (1 << 3);
来源：http://dali.chenlongwang.top/Article/details/gt2zeenhyaf.html

[S17] C：安全拼接字符串
来源：http://dali.tanke756.top/Article/details/gt2tbysasbi.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.snrcjt.cn/Article/details/gt2dchegrxa.html

[S18] C：命令行参数
来源：http://dali.wangshuangyany.cn/Article/details/gt2frxkbcdg.html

int main(int argc, char **argv)
来源：http://dali.fzhhl.top/Article/details/gt2ctudiyhb.html

[S19] C：快速排序
来源：http://dali.dashuyun.cn/Article/details/gt2lpafyhfq.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.sysykeji.top/Article/details/gt2trqsrkak.html

[S20] C：二分查找
来源：http://dali.zdqjudy.top/Article/details/gt2sclavndw.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.fzhhl.top/Article/details/gt2dajquydo.html

[S21] C：字符类别判断
来源：http://dali.sufxvd.cn/Article/details/gt2zfwwjpfa.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.quarkkingdee.top/Article/details/gt2eynehmsy.html

[S22] C：字符串转数字
来源：http://dali.cashguo.top/Article/details/gt2byprehye.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.nanxuanxn.top/Article/details/gt2adrenovj.html

[S23] C：随机数
来源：http://dali.pengpengdd.cyou/Article/details/gt2mrpgtsjc.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hbhnxsrl.html

[S24] C：获取本地时间
来源：http://dali.ivvv.top/Article/details/gt2cyxyabcj.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.tianlin.xyz/Article/details/gt2sgbvcmoo.html

[S25] C：内存拷贝
来源：http://dali.jinqigufen.top/Article/details/gt2kukmercj.html

memcpy(dst, src, n);
来源：http://dali.yj20258.top/Article/details/gt2qzkpnzjq.html

[S26] C：内存清零
来源：http://dali.haohaochexian.top/Article/details/gt2mqakiarz.html

memset(a, 0, sizeof a);
来源：http://dali.daxiang520.top/Article/details/gt2dkklftlm.html

[S27] C：定义常量
来源：http://dali.hysaishi.cn/Article/details/gt2uvfloofg.html

const double PI = 3.14159;
来源：http://dali.feifeiyinyue.top/Article/details/gt2hwbpghmc.html

[S28] C：静态变量
来源：http://dali.jqgfzy.top/Article/details/gt2xhtzkrfj.html

static int counter = 0;
来源：http://dali.nanxinkj.top/Article/details/gt2xjfimbyh.html

[S29] C：变参函数
来源：http://dali.havefunace.top/Article/details/gt2jlgnflvt.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.aizwys.cn/Article/details/gt2gtczkgyq.html

[S30] C：头文件保护
来源：http://dali.gzhubu.top/Article/details/gt2xpoehkdw.html

#ifndef X_H
来源：http://dali.fengsongda.top/Article/details/gt2lawzckwb.html

#define X_H
来源：http://dali.guowangkeji.top/Article/details/gt2xdtuvipg.html

#endif
来源：http://dali.jiagoushi.top/Article/details/gt2agwttpjc.html

[S31] C++：Hello World
来源：http://dali.316326.xyz/Article/details/gt2niewuiim.html

#include <iostream>
来源：http://dali.9152youxi.cn/Article/details/gt2eevthxfq.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.shuidangran.top/Article/details/gt2dsknoucg.html

[S32] C++：字符串
来源：http://dali.ivvv.top/Article/details/gt2kbgoendz.html

std::string s = "hi";  s += "!";
来源：http://dali.jlsjyb.cn/Article/details/gt2klqotmeq.html

[S33] C++：vector 增删
来源：http://dali.cheryme.top/Article/details/gt2wbsbwncs.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.snrcjt.cn/Article/details/gt2uifvpaul.html

[S34] C++：遍历 vector
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ufnwdpij.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.xinyue.icu/Article/details/gt2pykvqrcj.html

[S35] C++：map
来源：http://dali.cqqwz.cn/Article/details/gt2ycgoztay.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.sweek.top/Article/details/gt2poccdrdb.html

[S36] C++：unordered_map
来源：http://dali.yangfankeji.com/Article/details/gt2mxszyroh.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.svipenyu.cn/Article/details/gt2lcslvxjl.html

[S37] C++：set
来源：http://dali.mhx1999.top/Article/details/gt2sfoxjlwx.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.daria6918.cn/Article/details/gt2bahszzlv.html

[S38] C++：排序
来源：http://dali.c1oappe.top/Article/details/gt2ysyjyfwt.html

std::sort(v.begin(), v.end());
来源：http://dali.cqqwz.cn/Article/details/gt2otswsmec.html

[S39] C++：自定义比较器排序
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kuijzgxf.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.sysykeji.top/Article/details/gt2ixrtqqdf.html

[S40] C++：查找元素
来源：http://dali.zhongyouzk.top/Article/details/gt2sgouitpx.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.yangfankeji.com/Article/details/gt2cgcxicsu.html

[S41] C++：类与构造函数
来源：http://dali.meibo888.top/Article/details/gt2jvfqxoju.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhoulong.xyz/Article/details/gt2pqhhwrgu.html

[S42] C++：继承与虚函数
来源：http://dali.9152youxi.cn/Article/details/gt2dlditgqw.html

class B : public Base { public: void f() override {} };
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ryuoywjs.html

[S43] C++：智能指针
来源：http://dali.haohaochexian.top/Article/details/gt2eegfszkg.html

auto p = std::make_unique<int>(5);
来源：http://dali.meibo888.top/Article/details/gt2zfbjfttk.html

[S44] C++：引用传参
来源：http://dali.snrcjt.cn/Article/details/gt2qixjyavv.html

void inc(int &x) { ++x; }
来源：http://dali.hnxiangtu.top/Article/details/gt2odfowaee.html

[S45] C++：lambda
来源：http://dali.cdnleiting.top/Article/details/gt2oqebobay.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.iojbl.cn/Article/details/gt2oslfqsrd.html

[S46] C++：函数模板
来源：http://dali.guowangkeji.top/Article/details/gt2qenjrhhp.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2atctldvr.html

[S47] C++：结构化绑定遍历
来源：http://dali.jiagoushi.top/Article/details/gt2koynvgni.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.guowangkeji.top/Article/details/gt2hjnqqwsq.html

[S48] C++：逐行读文件
来源：http://dali.vqdsnc.cn/Article/details/gt2kfauhvit.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.pycfn.com/Article/details/gt2txvpudhn.html

while (std::getline(in, line)) { }
来源：http://dali.sweek.top/Article/details/gt2ahfygxnz.html

[S49] C++：写文件
来源：http://dali.nanxuanxn.top/Article/details/gt2mcdhputp.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.snrcjt.cn/Article/details/gt2atpzjtnl.html

[S50] C++：格式化数字
来源：http://dali.cqqwz.cn/Article/details/gt2ianxdpxq.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.chenzaomai.com/Article/details/gt2kzqfhymf.html

[S51] C++：显式类型转换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fumqppcq.html

static_cast<double>(a) / b
来源：http://dali.smart0.xyz/Article/details/gt2yalxybqq.html

[S52] C++：const 与 noexcept
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mgemxpkg.html

int size() const noexcept { return n_; }
来源：http://dali.sufxvd.cn/Article/details/gt2zlzixfvx.html

[S53] C++：移动语义
来源：http://dali.gzhubu.top/Article/details/gt2qiqsqdbx.html

std::vector<int> w = std::move(v);
来源：http://dali.iojbl.cn/Article/details/gt2jdlcyqkh.html

[S54] C++：异常处理
来源：http://dali.snrcjt.cn/Article/details/gt2rtbckang.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.yuxming.cn/Article/details/gt2qbwupqev.html

[S55] C++：结构化绑定
来源：http://dali.ivvv.top/Article/details/gt2ovwkopie.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.c1oappe.top/Article/details/gt2sgjblpvu.html

[S56] C++：optional
来源：http://dali.yonumen.top/Article/details/gt2ybvggytn.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2wsqugaml.html

[S57] C++：编译期常量
来源：http://dali.tianlin.xyz/Article/details/gt2weyqwcft.html

constexpr int N = 10;
来源：http://dali.jqgufenzy.top/Article/details/gt2pvavxwzr.html

[S58] C++：命名空间
来源：http://dali.gotoacloud.top/Article/details/gt2qevzsfqa.html

namespace ns { int f() { return 1; } }
来源：http://dali.hysaishi.cn/Article/details/gt2ytdizoji.html

[S59] C++：静态断言
来源：http://dali.yangfankeji.com/Article/details/gt2mdntkwtm.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.shuidangran.top/Article/details/gt2lrampscc.html

[S60] C++：遍历并删除元素
来源：http://dali.sufxvd.cn/Article/details/gt2sprtdcpp.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.jyoumei.cn/Article/details/gt2wotquuts.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2mbzccwmp.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2ylxaxaof.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gt2chduuxzk.html

[T01] Kotlin：Hello World
来源：http://dali.cheryme.top/Article/details/gt2epnfsggr.html

println("Hello")
来源：http://dali.xziqi.cn/Article/details/gt2yycwlemj.html

[T02] Kotlin：变量
来源：http://dali.hnqzz.top/Article/details/gt2dqqbfbfo.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.yj20258888.top/Article/details/gt2xhxwrapo.html

[T03] Kotlin：字符串模板
来源：http://dali.fzhhl.top/Article/details/gt2omelmekm.html

"值: $b"
来源：http://dali.sweek.top/Article/details/gt2hksspgvi.html

[T04] Kotlin：空安全
来源：http://dali.gzhubu.top/Article/details/gt2hckhnlvz.html

val n: String? = null;  n?.length
来源：http://dali.chenjidiqi.icu/Article/details/gt2vopsjklj.html

[T05] Kotlin：when 表达式
来源：http://dali.ybcxt.top/Article/details/gt2ikcqhuif.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.ivvv.top/Article/details/gt2dphegvbk.html

[T06] Kotlin：集合映射
来源：http://dali.hfpthk.cn/Article/details/gt2hbwslozu.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.jinqigfzy.top/Article/details/gt2byspduac.html

[T07] Kotlin：集合过滤
来源：http://dali.hnxiangtu.top/Article/details/gt2okqyjwsf.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.hnqzz.top/Article/details/gt2spduqusn.html

[T08] Kotlin：数据类
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jkmckhaq.html

data class User(val name: String, val age: Int)
来源：http://dali.ybcxt.top/Article/details/gt2koqbdhvy.html

[T09] Kotlin：扩展函数
来源：http://dali.0kj1m.cn/Article/details/gt2uwptiakp.html

fun String.exclaim() = this + "!"
来源：http://dali.yueranfly.top/Article/details/gt2dptljgfv.html

[T10] Kotlin：默认参数
来源：http://dali.redwolf501.top/Article/details/gt2nehvdkjs.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.chenlongwang.top/Article/details/gt2gnmkssbj.html

[T11] Kotlin：协程
来源：http://dali.xziqi.cn/Article/details/gt2cshcymtv.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.xziqi.cn/Article/details/gt2ruhlbdsy.html

[T12] Kotlin：解构声明
来源：http://dali.guannengcc.top/Article/details/gt2fxmvuckj.html

val (a, b) = Pair(1, 2)
来源：http://dali.0kj1m.cn/Article/details/gt2fzybsrnp.html

[T13] Kotlin：只读 Map
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ussybptx.html

val m = mapOf("a" to 1)
来源：http://dali.zhixingplan.top/Article/details/gt2qhokmbxu.html

[T14] Kotlin：循环
来源：http://dali.gogol.net.cn/Article/details/gt2uragmtgf.html

for (i in 1..10) println(i)
来源：http://dali.guowangkeji.top/Article/details/gt2riokypud.html

[T15] Kotlin：接口
来源：http://dali.gaohongyu789.top/Article/details/gt2dxkfenqr.html

interface Shape { fun area(): Double }
来源：http://dali.smart0.xyz/Article/details/gt2wlholftd.html

[T16] Swift：Hello World
来源：http://dali.gotoacloud.top/Article/details/gt2wimcxsfs.html

print("Hello")
来源：http://dali.gzhubu.top/Article/details/gt2ppbfxycr.html

[T17] Swift：变量与常量
来源：http://dali.hnxiangtu.top/Article/details/gt2wyshpndk.html

var a = 1;  let b = 2
来源：http://dali.zhixingplan.top/Article/details/gt2fgeryauj.html

[T18] Swift：字符串插值
来源：http://dali.chenlongwang.top/Article/details/gt2rhcrdwqf.html

"值: \(b)"
来源：http://dali.aizwys.cn/Article/details/gt2qvndqnul.html

[T19] Swift：可选绑定
来源：http://dali.iojbl.cn/Article/details/gt2byxbxigj.html

if let n = opt { print(n) }
来源：http://dali.zhiwuduotai.top/Article/details/gt2ofihyogn.html

[T20] Swift：数组操作
来源：http://dali.hnqzz.top/Article/details/gt2icxbdnkr.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.wangshuangyany.cn/Article/details/gt2exfkbfii.html

[T21] Swift：遍历
来源：http://dali.yj20258.top/Article/details/gt2ejucvchh.html

for x in a { print(x) }
来源：http://dali.jqgufenzy.top/Article/details/gt2uaaqljix.html

[T22] Swift：字典
来源：http://dali.quarkkingdee.top/Article/details/gt2ziooltyd.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.bjfxy.top/Article/details/gt2nsvbdvpg.html

[T23] Swift：函数
来源：http://dali.tanke756.top/Article/details/gt2iigkyuzi.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.ybcxt.top/Article/details/gt2vxbiyude.html

[T24] Swift：闭包
来源：http://dali.sxryk.cn/Article/details/gt2jdgvsmme.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.pycfn.com/Article/details/gt2fszpqrne.html

[T25] Swift：结构体
来源：http://dali.hnqzz.top/Article/details/gt2ijoqxsez.html

struct P { var x: Int }
来源：http://dali.shuidangran.top/Article/details/gt2gaghgegt.html

[T26] Swift：类与重写
来源：http://dali.hammf.cn/Article/details/gt2lgqfrqbd.html

class A: Base { override func f() {} }
来源：http://dali.yj20258.top/Article/details/gt2uucrfnhr.html

[T27] Swift：错误处理
来源：http://dali.hywenlv.cn/Article/details/gt2hptowatm.html

do { try f() } catch { print(error) }
来源：http://dali.yj202588.top/Article/details/gt2khbgpgxb.html

[T28] Swift：枚举
来源：http://dali.xuanzx.com/Article/details/gt2eyladiou.html

enum Color { case red, green }
来源：http://dali.snrcjt.cn/Article/details/gt2vqzzovpd.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2etlxjzcu.html

guard let x = opt else { return }
来源：http://dali.jianghu66.top/Article/details/gt2edabeoop.html

[T30] Swift：协议
来源：http://dali.cucudq.cn/Article/details/gt2fmngxltd.html

protocol Shape { func area() -> Double }
来源：http://dali.zhixingplan.top/Article/details/gt2txbpxzzb.html

[T31] Lua：Hello World
来源：http://dali.svipenyu.cn/Article/details/gt2raywzsug.html

print("Hello")
来源：http://dali.havefunace.top/Article/details/gt2udpgkuwp.html

[T32] Lua：局部变量
来源：http://dali.yangfankeji.com/Article/details/gt2bsxaitra.html

local a = 1
来源：http://dali.yonumen.top/Article/details/gt2lctbfjmd.html

[T33] Lua：表（数组）
来源：http://dali.bjfxy.top/Article/details/gt2nqkehvjw.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.chenlongwang.top/Article/details/gt2dzcoiwqe.html

[T34] Lua：遍历表
来源：http://dali.yj202588.top/Article/details/gt2ccnoxdlc.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.c1oappe.top/Article/details/gt2vhrltzhv.html

[T35] Lua：字典表
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wcsjfrpb.html

local d = { a = 1 };  d.b = 2
来源：http://dali.birdmap.top/Article/details/gt2wuvehwxn.html

[T36] Lua：函数
来源：http://dali.jinqigufen.top/Article/details/gt2fwlbskgw.html

function add(a, b) return a + b end
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vltzynpl.html

[T37] Lua：字符串拼接
来源：http://dali.sysykeji.top/Article/details/gt2ningruuo.html

"a" .. "b"
来源：http://dali.ppjwa.cn/Article/details/gt2thygekfj.html

[T38] Lua：条件
来源：http://dali.ppjwa.cn/Article/details/gt2vjkkotgz.html

if x > 0 then print("正") end
来源：http://dali.havefunace.top/Article/details/gt2msqncmrn.html

[T39] Lua：模式匹配
来源：http://dali.gzhubu.top/Article/details/gt2wsbxcrfk.html

string.find(s, "%d+")
来源：http://dali.zhiwuduotai.top/Article/details/gt2zfblevrv.html

[T40] Lua：元表
来源：http://dali.ybcxt.top/Article/details/gt2llqmtakq.html

setmetatable({}, { __index = base })
来源：http://dali.zhengqikj.top/Article/details/gt2rvrpkpii.html

[T41] Perl：Hello World
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rilueycq.html

print "Hello\n";
来源：http://dali.guannengcc.top/Article/details/gt2vffiiqlm.html

[T42] Perl：变量类型
来源：http://dali.guannengcc.top/Article/details/gt2ahxxacau.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.jianghu66.top/Article/details/gt2prjjutdd.html

[T43] Perl：字符串插值
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cvnqknth.html

"值: $a"
来源：http://dali.meibo888.top/Article/details/gt2kpbzlwzn.html

[T44] Perl：条件
来源：http://dali.hongshengwenyu.top/Article/details/gt2ylkwerpd.html

if ($a > 0) { print "正"; }
来源：http://dali.sysykeji.top/Article/details/gt2yrkfzrfy.html


<!-- 参考信息 -->