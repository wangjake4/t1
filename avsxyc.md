代发 wailian999

files=$(ls -1)
来源：http://dali.ydzc1.top/Article/details/gt2ljgpyjqi.html

[R38] 管道串联
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2exmthopw.html

cat a.txt | grep -i error | wc -l
来源：http://dali.xuetiantiany.cn/Article/details/gt2itbcxcnh.html

[R39] 重定向标准输出与错误
来源：http://dali.dianchejie.cn/Article/details/gt2bzlghjtm.html

cmd > out.log 2>&1
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jfjrjxrb.html

[R40] 追加写日志
来源：http://dali.tian-w.cn/Article/details/gt2dfiazrim.html

echo "log" >> out.log
来源：http://dali.quarkkingdee.top/Article/details/gt2oiylsbap.html

[R41] 丢弃输出
来源：http://dali.ehwqpu.com/Article/details/gt2ilyiwpfm.html

cmd >/dev/null 2>&1
来源：http://dali.guowangkeji.top/Article/details/gt2rftptcxv.html

[R42] 输入重定向
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tboabbdt.html

wc -l < a.txt
来源：http://dali.tanke756.top/Article/details/gt2ajxuiziw.html

[R43] 按名字查找文件
来源：http://dali.xuetiantiany.cn/Article/details/gt2pfnpsust.html

find . -name "*.log" -type f
来源：http://dali.316326.xyz/Article/details/gt2vyokrkes.html

[R44] 按修改时间查找
来源：http://dali.wangdashe.top/Article/details/gt2ajrrxahk.html

find . -mtime -7 -type f
来源：http://dali.cheryme.top/Article/details/gt2aazqvnqq.html

[R45] 批量删除
来源：http://dali.wangdashe.top/Article/details/gt2jybulbxn.html

find . -name "*.tmp" -delete
来源：http://dali.c1oappe.top/Article/details/gt2xpsboqub.html

[R46] 递归替换文件内容
来源：http://dali.guannengcc.top/Article/details/gt2xhfkefbt.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhiwuduotai.top/Article/details/gt2ezlwyedk.html

[R47] sed 单行替换
来源：http://dali.meibo888.top/Article/details/gt2uglbdrkd.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.meibo888.top/Article/details/gt2shwmexqw.html

[R48] awk 取指定列
来源：http://dali.zhixingplan.top/Article/details/gt2rsvbkobe.html

awk '{print $1, $3}' a.txt
来源：http://dali.shzxlz.cn/Article/details/gt2gbmbhuss.html

[R49] awk 带条件
来源：http://dali.chenjidiqi.icu/Article/details/gt2cxoxpxqv.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.nanxuanxn.top/Article/details/gt2ezfaukjf.html

[R50] awk 求和
来源：http://dali.cdnleiting.top/Article/details/gt2baqnfsej.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.haohaochexian.top/Article/details/gt2iabwihik.html

[R51] 排序去重取前几
来源：http://dali.jqgufenzy.top/Article/details/gt2ouhlsobg.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.daria6918.cn/Article/details/gt2inkmxnzf.html

[R52] 统计行数
来源：http://dali.jyoumei.cn/Article/details/gt2hoxawgef.html

wc -l a.txt
来源：http://dali.hfpthk.cn/Article/details/gt2odxcxxyv.html

[R53] 查看文件头与实时尾
来源：http://dali.jinqigufen.top/Article/details/gt2zavqtwnv.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.wangdashe.top/Article/details/gt2ogwfapfk.html

[R54] 比较两个文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vckqlzub.html

diff a.txt b.txt
来源：http://dali.feifeiyinyue.top/Article/details/gt2mmzgssxj.html

[R55] 压缩与解压
来源：http://dali.gotoacloud.top/Article/details/gt2tzxepbwu.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.ehwqpu.com/Article/details/gt2yqywkawx.html

[R56] 远程拷贝
来源：http://dali.yuxming.cn/Article/details/gt2febexsxz.html

scp file user@host:/path/
来源：http://dali.zycfv.cn/Article/details/gt2iaubwrrq.html

[R57] 远程执行命令
来源：http://dali.yongpay.top/Article/details/gt2fiysjyna.html

ssh user@host 'uptime'
来源：http://dali.hysaishi.cn/Article/details/gt2gaeuwsqy.html

[R58] 下载文件
来源：http://dali.fengsongda.top/Article/details/gt2aobcnjnt.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.aizwys.cn/Article/details/gt2khklybpv.html

[R59] 发 POST JSON
来源：http://dali.316326.xyz/Article/details/gt2setkehje.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.tanke756.top/Article/details/gt2eofiwekf.html

[R60] 只看 HTTP 状态码
来源：http://dali.gogol.net.cn/Article/details/gt2vfhkykyf.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.hysaishi.cn/Article/details/gt2yydvwcay.html

[R61] 磁盘占用
来源：http://dali.guowangkeji.top/Article/details/gt2xkhmtrgw.html

df -h;  du -sh *
来源：http://dali.gogol.net.cn/Article/details/gt2mkwvadzn.html

[R62] 找最占空间的文件
来源：http://dali.vqdsnc.cn/Article/details/gt2elstlpml.html

du -ah . | sort -rh | head -10
来源：http://dali.cheryme.top/Article/details/gt2kxqbetzr.html

[R63] 内存与进程
来源：http://dali.andypj.xyz/Article/details/gt2dzvrgolr.html

free -h;  ps aux | grep nginx
来源：http://dali.0kj1m.cn/Article/details/gt2kthftabq.html

[R64] 结束进程
来源：http://dali.zhoulong.xyz/Article/details/gt2ozhfbfub.html

kill -9 $(pgrep -f app.py)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2enxdgeon.html

[R65] 查看端口占用
来源：http://dali.yuanzhike.top/Article/details/gt2qctnjope.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.jiagoushi.top/Article/details/gt2tcpgjskl.html

[R66] 定时任务
来源：http://dali.feifeiyinyue.top/Article/details/gt2tewbugap.html

crontab -e;  crontab -l
来源：http://dali.ppjwa.cn/Article/details/gt2wziwtfvv.html

[R67] 生成随机十六进制串
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rcbwcevt.html

openssl rand -hex 16
来源：http://dali.0kj1m.cn/Article/details/gt2yohxuiii.html

[R68] 计算文件校验值
来源：http://dali.pycfn.com/Article/details/gt2mqzpwmbn.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.ehwqpu.com/Article/details/gt2dqtnrwft.html

[R69] 生成随机密码
来源：http://dali.ppjwa.cn/Article/details/gt2ncjdbyzu.html

head -c 16 /dev/urandom | base64
来源：http://dali.fengsongda.top/Article/details/gt2pztsaynt.html

[R70] 时间戳与互转
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vqovzlmh.html

date +%s;  date -d @1700000000
来源：http://dali.snrcjt.cn/Article/details/gt2apgtrtwy.html

[R71] 日期格式化
来源：http://dali.9152youxi.cn/Article/details/gt2dtqpkrqa.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.wangshuangyany.cn/Article/details/gt2rlavuiwj.html

[R72] 等待端口就绪
来源：http://dali.yj202588.top/Article/details/gt2cqlofodv.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.9152youxi.cn/Article/details/gt2uqweoffl.html

[R73] 分割大日志
来源：http://dali.iojbl.cn/Article/details/gt2khabqodb.html

split -l 1000 big.log part_
来源：http://dali.yueranfly.top/Article/details/gt2oztqrxqe.html

[R74] 批量重命名
来源：http://dali.chenjidiqi.icu/Article/details/gt2wlscnlyx.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.yj202588.top/Article/details/gt2ntosyzxo.html

[R75] 导出环境变量
来源：http://dali.yj202588.top/Article/details/gt2ysuflklj.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.snrcjt.cn/Article/details/gt2ucujhemg.html

[R76] 使用临时文件
来源：http://dali.ppjwa.cn/Article/details/gt2isetubda.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.iojbl.cn/Article/details/gt2jzdxotqd.html

[R77] 读取用户输入
来源：http://dali.xuanzx.com/Article/details/gt2kalxcdqa.html

read -rp "请输入: " ans
来源：http://dali.ivvv.top/Article/details/gt2cacnkgux.html

[R78] 交互式菜单
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lscnucfk.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.chenzaomai.com/Article/details/gt2cbdsjjmi.html

[R79] 解析命令行选项
来源：http://dali.zhoulong.xyz/Article/details/gt2lxzmpbhn.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.dashuyun.cn/Article/details/gt2nykxbtud.html

[R80] 查看脚本执行耗时
来源：http://dali.fengsongda.top/Article/details/gt2fjnufupw.html

time ./run.sh
来源：http://dali.fzhhl.top/Article/details/gt2ovhfnvwx.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gt2xzukwahl.html

S. C / C++ 专题
来源：http://dali.xuanzx.com/Article/details/gt2uzilhvqi.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2jtmxgsap.html

[S01] C：Hello World
来源：http://dali.redwolf501.top/Article/details/gt2tjlvfclp.html

#include <stdio.h>
来源：http://dali.xuetiantiany.cn/Article/details/gt2mzmffiow.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.yueranfly.top/Article/details/gt2pzaovylq.html

[S02] C：变量与格式化输出
来源：http://dali.jinqigufen.top/Article/details/gt2ebyyrfox.html

int a = 10; printf("%d\n", a);
来源：http://dali.guannengcc.top/Article/details/gt2jnxflkpa.html

[S03] C：读入整数
来源：http://dali.daxiang520.top/Article/details/gt2pqdsunbb.html

int x; scanf("%d", &x);
来源：http://dali.shuidangran.top/Article/details/gt2msxtapdm.html

[S04] C：字符串复制
来源：http://dali.guowangkeji.top/Article/details/gt2mztasvst.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.sufxvd.cn/Article/details/gt2ijuyvlsp.html

[S05] C：字符串长度
来源：http://dali.jiagoushi.top/Article/details/gt2bjknzkqc.html

strlen(s)
来源：http://dali.cheryme.top/Article/details/gt2agiqergj.html

[S06] C：字符串比较
来源：http://dali.zhixingplan.top/Article/details/gt2iamzucqd.html

strcmp(a, b) == 0
来源：http://dali.sxryk.cn/Article/details/gt2wjithsri.html

[S07] C：数组遍历求和
来源：http://dali.jianghu66.top/Article/details/gt2fdybktyr.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.smart0.xyz/Article/details/gt2tewxhugh.html

[S08] C：动态内存分配与释放
来源：http://dali.havefunace.top/Article/details/gt2ytcazwaa.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.gaohongyu789.top/Article/details/gt2wosikctj.html

[S09] C：结构体定义与初始化
来源：http://dali.ehwqpu.com/Article/details/gt2mzhjhukp.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.tianlin.xyz/Article/details/gt2bvwebwtb.html

[S10] C：指针与解引用
来源：http://dali.cqqwz.cn/Article/details/gt2scnszabv.html

int *p = &a;  *p = 5;
来源：http://dali.jqgfzy.top/Article/details/gt2dqqjznym.html

[S11] C：逐行读文件
来源：http://dali.xuetiantiany.cn/Article/details/gt2wxupinvy.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.wangdashe.top/Article/details/gt2ylqajzdb.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.jqgfzy.top/Article/details/gt2piumwsyj.html

fclose(f);
来源：http://dali.hnxiangtu.top/Article/details/gt2uxybwdlr.html

[S12] C：写文件
来源：http://dali.smart0.xyz/Article/details/gt2trgbfbjv.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.aibaodan.cn/Article/details/gt2jdaqjtcf.html

[S13] C：宏定义
来源：http://dali.tanke756.top/Article/details/gt2itvggjpr.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.c1oappe.top/Article/details/gt2obtckeyd.html

[S14] C：枚举
来源：http://dali.xuetiantiany.cn/Article/details/gt2tttjvhlk.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.jinqigufen.top/Article/details/gt2yfepukha.html

[S15] C：类型转换
来源：http://dali.xuetiantiany.cn/Article/details/gt2zhtosunm.html

(double) a / b
来源：http://dali.jyoumei.cn/Article/details/gt2qlfufmus.html

[S16] C：位操作置位
来源：http://dali.ydzc1.top/Article/details/gt2fdlivwky.html

x |= (1 << 3);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xukjdcqv.html

[S17] C：安全拼接字符串
来源：http://dali.yangfankeji.com/Article/details/gt2uaybymto.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.hongshengwenyu.top/Article/details/gt2kggbklqn.html

[S18] C：命令行参数
来源：http://dali.chenjidiqi.icu/Article/details/gt2lwhjyxxx.html

int main(int argc, char **argv)
来源：http://dali.gotoacloud.top/Article/details/gt2cusogiap.html

[S19] C：快速排序
来源：http://dali.yangfankeji.com/Article/details/gt2lnyhdwgf.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.chenlongwang.top/Article/details/gt2yizxjtaa.html

[S20] C：二分查找
来源：http://dali.quarkkingdee.top/Article/details/gt2mwhokwyf.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.tianlin.xyz/Article/details/gt2srefnqqx.html

[S21] C：字符类别判断
来源：http://dali.jiagoushi.top/Article/details/gt2eprwsnks.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.hysaishi.cn/Article/details/gt2poxkooax.html

[S22] C：字符串转数字
来源：http://dali.cucudq.cn/Article/details/gt2irbbhyde.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.tanke756.top/Article/details/gt2ffsyaipq.html

[S23] C：随机数
来源：http://dali.ivvv.top/Article/details/gt2ygdcwsek.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.yj20258888.top/Article/details/gt2uhqkgdhx.html

[S24] C：获取本地时间
来源：http://dali.cheryme.top/Article/details/gt2fijxmzye.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.xziqi.cn/Article/details/gt2jtitorxj.html

[S25] C：内存拷贝
来源：http://dali.c1oappe.top/Article/details/gt2hahuuxov.html

memcpy(dst, src, n);
来源：http://dali.guowangkeji.top/Article/details/gt2neafihbj.html

[S26] C：内存清零
来源：http://dali.aibaodan.cn/Article/details/gt2eydncylh.html

memset(a, 0, sizeof a);
来源：http://dali.cucudq.cn/Article/details/gt2pouvuoom.html

[S27] C：定义常量
来源：http://dali.hammf.cn/Article/details/gt2zqejfncp.html

const double PI = 3.14159;
来源：http://dali.birdmap.top/Article/details/gt2vokuxwhd.html

[S28] C：静态变量
来源：http://dali.jyoumei.cn/Article/details/gt2kvpqsbcr.html

static int counter = 0;
来源：http://dali.jiagoushi.top/Article/details/gt2bggqfrvh.html

[S29] C：变参函数
来源：http://dali.zhongyouzk.top/Article/details/gt2mpwpypfz.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.hongshengwenyu.top/Article/details/gt2lmehducw.html

[S30] C：头文件保护
来源：http://dali.ivvv.top/Article/details/gt2rvsulenm.html

#ifndef X_H
来源：http://dali.jianghu66.top/Article/details/gt2wnsomdqt.html

#define X_H
来源：http://dali.jianghu66.top/Article/details/gt2yeeprhdq.html

#endif
来源：http://dali.gzhubu.top/Article/details/gt2tdzcldha.html

[S31] C++：Hello World
来源：http://dali.shuidangran.top/Article/details/gt2yxturwgp.html

#include <iostream>
来源：http://dali.316326.xyz/Article/details/gt2crwmdgkw.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vrtjsysf.html

[S32] C++：字符串
来源：http://dali.aibaodan.cn/Article/details/gt2lupkwlgh.html

std::string s = "hi";  s += "!";
来源：http://dali.xziqi.cn/Article/details/gt2lbisjbec.html

[S33] C++：vector 增删
来源：http://dali.316326.xyz/Article/details/gt2hfhoqqns.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhixingplan.top/Article/details/gt2smbjikcs.html

[S34] C++：遍历 vector
来源：http://dali.jyoumei.cn/Article/details/gt2xsulguqc.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.shuidangran.top/Article/details/gt2yttcepxy.html

[S35] C++：map
来源：http://dali.smart0.xyz/Article/details/gt2ypustmjd.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yueranfly.top/Article/details/gt2mxxfnctr.html

[S36] C++：unordered_map
来源：http://dali.xinyue.icu/Article/details/gt2nxxbahms.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.fzhhl.top/Article/details/gt2onlmcqmf.html

[S37] C++：set
来源：http://dali.jinqigfzy.top/Article/details/gt2qkbezpnb.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.nanxinkj.top/Article/details/gt2fepazval.html

[S38] C++：排序
来源：http://dali.gzhubu.top/Article/details/gt2lblegayd.html

std::sort(v.begin(), v.end());
来源：http://dali.jinghuilouyu.cn/Article/details/gt2icklwwvc.html

[S39] C++：自定义比较器排序
来源：http://dali.9152youxi.cn/Article/details/gt2dqfahvqj.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.9152youxi.cn/Article/details/gt2vagwkgjd.html

[S40] C++：查找元素
来源：http://dali.shzxlz.cn/Article/details/gt2lmcwokti.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhoulong.xyz/Article/details/gt2hzdlcmzx.html

[S41] C++：类与构造函数
来源：http://dali.zycfv.cn/Article/details/gt2npyhbssv.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.birdmap.top/Article/details/gt2ravspwqe.html

[S42] C++：继承与虚函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rxbatlfa.html

class B : public Base { public: void f() override {} };
来源：http://dali.haohaochexian.top/Article/details/gt2islivsio.html

[S43] C++：智能指针
来源：http://dali.xziqi.cn/Article/details/gt2daqskmjl.html

auto p = std::make_unique<int>(5);
来源：http://dali.daria6918.cn/Article/details/gt2hdajlhog.html

[S44] C++：引用传参
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bnhipqbd.html

void inc(int &x) { ++x; }
来源：http://dali.ybcxt.top/Article/details/gt2ynkoawze.html

[S45] C++：lambda
来源：http://dali.meibo888.top/Article/details/gt2yrbyawad.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2svyueitf.html

[S46] C++：函数模板
来源：http://dali.sxryk.cn/Article/details/gt2bawtrjvr.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.ehwqpu.com/Article/details/gt2bwopsouk.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhiwuduotai.top/Article/details/gt2ifimuuig.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.yj202588.top/Article/details/gt2lqtxlohk.html

[S48] C++：逐行读文件
来源：http://dali.haohaochexian.top/Article/details/gt2invrzech.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ubyxltiw.html

while (std::getline(in, line)) { }
来源：http://dali.smart0.xyz/Article/details/gt2odeizfqy.html

[S49] C++：写文件
来源：http://dali.jqgfzy.top/Article/details/gt2pzcxparc.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.havefunace.top/Article/details/gt2kijvvhqc.html

[S50] C++：格式化数字
来源：http://dali.guowangkeji.top/Article/details/gt2sjjkcuit.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.gogol.net.cn/Article/details/gt2dilagzfx.html

[S51] C++：显式类型转换
来源：http://dali.hywenlv.cn/Article/details/gt2rjodklvp.html

static_cast<double>(a) / b
来源：http://dali.andypj.xyz/Article/details/gt2kcdchljg.html

[S52] C++：const 与 noexcept
来源：http://dali.aizwys.cn/Article/details/gt2wjtahopb.html

int size() const noexcept { return n_; }
来源：http://dali.sufxvd.cn/Article/details/gt2vijplboy.html

[S53] C++：移动语义
来源：http://dali.jiagoushi.top/Article/details/gt2dqxhvwei.html

std::vector<int> w = std::move(v);
来源：http://dali.gaohongyu789.top/Article/details/gt2drhqgqnx.html

[S54] C++：异常处理
来源：http://dali.cashguo.top/Article/details/gt2pnobiehs.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.chenjidiqi.icu/Article/details/gt2tfamcunj.html

[S55] C++：结构化绑定
来源：http://dali.hammf.cn/Article/details/gt2uwlgpmgn.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.chenzaomai.com/Article/details/gt2mpcpskwr.html

[S56] C++：optional
来源：http://dali.xinyue.icu/Article/details/gt2qscdrvti.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yangfankeji.com/Article/details/gt2gjyiekwo.html

[S57] C++：编译期常量
来源：http://dali.fengsongda.top/Article/details/gt2ecohzjpt.html

constexpr int N = 10;
来源：http://dali.wangdashe.top/Article/details/gt2jxoxqjuh.html

[S58] C++：命名空间
来源：http://dali.sweek.top/Article/details/gt2etbkwfqo.html

namespace ns { int f() { return 1; } }
来源：http://dali.sysykeji.top/Article/details/gt2hrsyyrtg.html

[S59] C++：静态断言
来源：http://dali.sweek.top/Article/details/gt2ipfecxja.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.jianghu66.top/Article/details/gt2qjsnengb.html

[S60] C++：遍历并删除元素
来源：http://dali.jyoumei.cn/Article/details/gt2zfjztdty.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.ybcxt.top/Article/details/gt2phqlrjkn.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2fqotsern.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yongpay.top/Article/details/gt2aeaifoqh.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2rumggick.html

[T01] Kotlin：Hello World
来源：http://dali.pengpengdd.cyou/Article/details/gt2hxjpuoyx.html

println("Hello")
来源：http://dali.hnqzz.top/Article/details/gt2ycdurttm.html

[T02] Kotlin：变量
来源：http://dali.shangyingyoupin.top/Article/details/gt2exnbglny.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.gotoacloud.top/Article/details/gt2cyepobzh.html

[T03] Kotlin：字符串模板
来源：http://dali.tanke756.top/Article/details/gt2owwlfnbj.html

"值: $b"
来源：http://dali.meibo888.top/Article/details/gt2gfyxkdyo.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2oofcbybk.html

val n: String? = null;  n?.length
来源：http://dali.shangyingyoupin.top/Article/details/gt2xitjvjar.html

[T05] Kotlin：when 表达式
来源：http://dali.aibaodan.cn/Article/details/gt2fpzlkdxr.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.fengsongda.top/Article/details/gt2gzynbxhc.html

[T06] Kotlin：集合映射
来源：http://dali.yanxiufei.cn/Article/details/gt2dumzcyrj.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.aibaodan.cn/Article/details/gt2yctuvdtr.html

[T07] Kotlin：集合过滤
来源：http://dali.gogol.net.cn/Article/details/gt2amzighby.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.xuanzx.com/Article/details/gt2tzxavixy.html

[T08] Kotlin：数据类
来源：http://dali.yuxming.cn/Article/details/gt2adsoayoj.html

data class User(val name: String, val age: Int)
来源：http://dali.vqdsnc.cn/Article/details/gt2lhsxmils.html

[T09] Kotlin：扩展函数
来源：http://dali.yj202588.top/Article/details/gt2vjbhoxgu.html

fun String.exclaim() = this + "!"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rjxqhgmp.html

[T10] Kotlin：默认参数
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tazjmhhw.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.birdmap.top/Article/details/gt2hviozruk.html

[T11] Kotlin：协程
来源：http://dali.9152youxi.cn/Article/details/gt2kvboqzwp.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.yueranfly.top/Article/details/gt2gpqujjal.html

[T12] Kotlin：解构声明
来源：http://dali.zhengqikj.top/Article/details/gt2auwokyns.html

val (a, b) = Pair(1, 2)
来源：http://dali.sxryk.cn/Article/details/gt2mjustwnm.html

[T13] Kotlin：只读 Map
来源：http://dali.chenzaomai.com/Article/details/gt2jfhhkyhz.html

val m = mapOf("a" to 1)
来源：http://dali.iojbl.cn/Article/details/gt2skqkjgeu.html

[T14] Kotlin：循环
来源：http://dali.gogol.net.cn/Article/details/gt2rkexiyxx.html

for (i in 1..10) println(i)
来源：http://dali.cqqwz.cn/Article/details/gt2jxalfwsm.html

[T15] Kotlin：接口
来源：http://dali.zycfv.cn/Article/details/gt2aegfazsn.html

interface Shape { fun area(): Double }
来源：http://dali.yj20258.top/Article/details/gt2inupfffy.html

[T16] Swift：Hello World
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gpluqwot.html

print("Hello")
来源：http://dali.yangfankeji.com/Article/details/gt2ckvviqub.html

[T17] Swift：变量与常量
来源：http://dali.hongshengwenyu.top/Article/details/gt2epsossjr.html

var a = 1;  let b = 2
来源：http://dali.nanxuanxn.top/Article/details/gt2aqruacul.html

[T18] Swift：字符串插值
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vefmidpa.html

"值: \(b)"
来源：http://dali.nanxuanxn.top/Article/details/gt2zmlpnvay.html

[T19] Swift：可选绑定
来源：http://dali.guowangkeji.top/Article/details/gt2wqnyruer.html

if let n = opt { print(n) }
来源：http://dali.ydzc1.top/Article/details/gt2islsjbbv.html

[T20] Swift：数组操作
来源：http://dali.vqdsnc.cn/Article/details/gt2buprdily.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.birdmap.top/Article/details/gt2cvwfkcdw.html

[T21] Swift：遍历
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2thoafyfy.html

for x in a { print(x) }
来源：http://dali.xinyue.icu/Article/details/gt2kjowngzs.html

[T22] Swift：字典
来源：http://dali.yonumen.top/Article/details/gt2yfjmngga.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.gzhubu.top/Article/details/gt2yjelzakj.html

[T23] Swift：函数
来源：http://dali.ivvv.top/Article/details/gt2rtdbnidk.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2canxkvkn.html

[T24] Swift：闭包
来源：http://dali.aizwys.cn/Article/details/gt2kfxlquuv.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.gzhubu.top/Article/details/gt2hxsfacqr.html

[T25] Swift：结构体
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lnwailgq.html

struct P { var x: Int }
来源：http://dali.cqqwz.cn/Article/details/gt2kshksyki.html

[T26] Swift：类与重写
来源：http://dali.andypj.xyz/Article/details/gt2qcqrydyc.html

class A: Base { override func f() {} }
来源：http://dali.jinqigufen.top/Article/details/gt2mvurjdub.html

[T27] Swift：错误处理
来源：http://dali.fzhhl.top/Article/details/gt2hlymdrwx.html

do { try f() } catch { print(error) }
来源：http://dali.yvedp.cn/Article/details/gt2kwllinqg.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ggqxasnm.html

enum Color { case red, green }
来源：http://dali.jlsjyb.cn/Article/details/gt2kwftmnol.html

[T29] Swift：guard 提前返回
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2flsmguoo.html

guard let x = opt else { return }
来源：http://dali.xinyue.icu/Article/details/gt2rmyffiol.html

[T30] Swift：协议
来源：http://dali.jlsjyb.cn/Article/details/gt2idcuvzya.html

protocol Shape { func area() -> Double }
来源：http://dali.yuanzhike.top/Article/details/gt2bseucdai.html

[T31] Lua：Hello World
来源：http://dali.hongshengwenyu.top/Article/details/gt2qfedfgtc.html

print("Hello")
来源：http://dali.0kj1m.cn/Article/details/gt2gbwjzmnm.html

[T32] Lua：局部变量
来源：http://dali.feifeiyinyue.top/Article/details/gt2suzamzus.html

local a = 1
来源：http://dali.xziqi.cn/Article/details/gt2kbxuvqdy.html

[T33] Lua：表（数组）
来源：http://dali.fzhhl.top/Article/details/gt2ieuwkzhh.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.bjfxy.top/Article/details/gt2bdwvlmuq.html

[T34] Lua：遍历表
来源：http://dali.shzxlz.cn/Article/details/gt2varjoypq.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.nanxinkj.top/Article/details/gt2itkpaxuh.html

[T35] Lua：字典表
来源：http://dali.birdmap.top/Article/details/gt2buymbylx.html

local d = { a = 1 };  d.b = 2
来源：http://dali.chenlongwang.top/Article/details/gt2dtjahwcm.html

[T36] Lua：函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2smibhxzh.html

function add(a, b) return a + b end
来源：http://dali.chenjidiqi.icu/Article/details/gt2fpjlvefn.html

[T37] Lua：字符串拼接
来源：http://dali.xziqi.cn/Article/details/gt2trmzugec.html

"a" .. "b"
来源：http://dali.fzhhl.top/Article/details/gt2kxhhbvdq.html

[T38] Lua：条件
来源：http://dali.zhengqikj.top/Article/details/gt2rxznufbp.html

if x > 0 then print("正") end
来源：http://dali.mhx1999.top/Article/details/gt2nqxelldc.html

[T39] Lua：模式匹配
来源：http://dali.316326.xyz/Article/details/gt2saqpovbh.html

string.find(s, "%d+")
来源：http://dali.zhoulong.xyz/Article/details/gt2otycfshk.html

[T40] Lua：元表
来源：http://dali.ybcxt.top/Article/details/gt2dolbhcsn.html

setmetatable({}, { __index = base })
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jngikzhc.html


<!-- 参考信息 -->