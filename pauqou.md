代发 wailian999

files=$(ls -1)
来源：http://dali.jinqigfzy.top/Article/details/gt2vsocmito.html

[R38] 管道串联
来源：http://dali.ivvv.top/Article/details/gt2iueuupao.html

cat a.txt | grep -i error | wc -l
来源：http://dali.nanxuanxn.top/Article/details/gt2xfqfllsw.html

[R39] 重定向标准输出与错误
来源：http://dali.jianghu66.top/Article/details/gt2yheutpuu.html

cmd > out.log 2>&1
来源：http://dali.nanxuanxn.top/Article/details/gt2pzzoylqy.html

[R40] 追加写日志
来源：http://dali.aibaodan.cn/Article/details/gt2ldjuyjpy.html

echo "log" >> out.log
来源：http://dali.zhiwuduotai.top/Article/details/gt2gayhufdn.html

[R41] 丢弃输出
来源：http://dali.svipenyu.cn/Article/details/gt2qcyvzjmt.html

cmd >/dev/null 2>&1
来源：http://dali.yanxiufei.cn/Article/details/gt2qmbvctra.html

[R42] 输入重定向
来源：http://dali.jinqigufen.top/Article/details/gt2bowrtsye.html

wc -l < a.txt
来源：http://dali.ybcxt.top/Article/details/gt2gerlptts.html

[R43] 按名字查找文件
来源：http://dali.shangyingyoupin.top/Article/details/gt2aznpgarx.html

find . -name "*.log" -type f
来源：http://dali.wangshuangyany.cn/Article/details/gt2lwmrybpl.html

[R44] 按修改时间查找
来源：http://dali.shangyingyoupin.top/Article/details/gt2aswclngh.html

find . -mtime -7 -type f
来源：http://dali.shzxlz.cn/Article/details/gt2gxuzaglb.html

[R45] 批量删除
来源：http://dali.chenlongwang.top/Article/details/gt2lzrftjuw.html

find . -name "*.tmp" -delete
来源：http://dali.ydzc1.top/Article/details/gt2jvyvsakd.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2tptqguzf.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.daxiang520.top/Article/details/gt2stsdvdtd.html

[R47] sed 单行替换
来源：http://dali.aizwys.cn/Article/details/gt2rilyoccn.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.haohaochexian.top/Article/details/gt2xhmgtmeo.html

[R48] awk 取指定列
来源：http://dali.jianghu66.top/Article/details/gt2cbaatllt.html

awk '{print $1, $3}' a.txt
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ntlhexdo.html

[R49] awk 带条件
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tfdikcpe.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.cucudq.cn/Article/details/gt2hnbvardj.html

[R50] awk 求和
来源：http://dali.316326.xyz/Article/details/gt2odwhnmgl.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.xuetiantiany.cn/Article/details/gt2aygyerwa.html

[R51] 排序去重取前几
来源：http://dali.ybcxt.top/Article/details/gt2eifvpbfd.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.dianchejie.cn/Article/details/gt2fjvlqzwm.html

[R52] 统计行数
来源：http://dali.daria6918.cn/Article/details/gt2cichbhzt.html

wc -l a.txt
来源：http://dali.hongshengwenyu.top/Article/details/gt2qmepjqym.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2ifeedlkj.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.wangdashe.top/Article/details/gt2egcewovx.html

[R54] 比较两个文件
来源：http://dali.ivvv.top/Article/details/gt2gkhtfkvn.html

diff a.txt b.txt
来源：http://dali.redwolf501.top/Article/details/gt2lwdejibz.html

[R55] 压缩与解压
来源：http://dali.dianchejie.cn/Article/details/gt2izengwda.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.wangshuangyany.cn/Article/details/gt2vxhqtrwr.html

[R56] 远程拷贝
来源：http://dali.zhengqikj.top/Article/details/gt2qbjoipkr.html

scp file user@host:/path/
来源：http://dali.yuxming.cn/Article/details/gt2suexfkar.html

[R57] 远程执行命令
来源：http://dali.quarkkingdee.top/Article/details/gt2qalwqceb.html

ssh user@host 'uptime'
来源：http://dali.haohaochexian.top/Article/details/gt2nhbckghm.html

[R58] 下载文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2laihwscx.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.andypj.xyz/Article/details/gt2hmmeujqd.html

[R59] 发 POST JSON
来源：http://dali.daria6918.cn/Article/details/gt2ztlosdpr.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.yuanzhike.top/Article/details/gt2kayodyvb.html

[R60] 只看 HTTP 状态码
来源：http://dali.c1oappe.top/Article/details/gt2dthefdju.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhongyouzk.top/Article/details/gt2vgtgtmyw.html

[R61] 磁盘占用
来源：http://dali.316326.xyz/Article/details/gt2qpcczojt.html

df -h;  du -sh *
来源：http://dali.hnqzz.top/Article/details/gt2abcdorcj.html

[R62] 找最占空间的文件
来源：http://dali.jqgufenzy.top/Article/details/gt2fqtclqmy.html

du -ah . | sort -rh | head -10
来源：http://dali.smart0.xyz/Article/details/gt2qebhqkau.html

[R63] 内存与进程
来源：http://dali.dashuyun.cn/Article/details/gt2lbgcfppl.html

free -h;  ps aux | grep nginx
来源：http://dali.tanke756.top/Article/details/gt2lkljeatf.html

[R64] 结束进程
来源：http://dali.jianghu66.top/Article/details/gt2yxoncbbu.html

kill -9 $(pgrep -f app.py)
来源：http://dali.jqgufenzy.top/Article/details/gt2tdyowril.html

[R65] 查看端口占用
来源：http://dali.xinyue.icu/Article/details/gt2fxijvczy.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.birdmap.top/Article/details/gt2hftqrbjx.html

[R66] 定时任务
来源：http://dali.hfpthk.cn/Article/details/gt2rprotwfj.html

crontab -e;  crontab -l
来源：http://dali.nwbrower.top/Article/details/gt2ippyjhti.html

[R67] 生成随机十六进制串
来源：http://dali.quarkkingdee.top/Article/details/gt2trhjpqfz.html

openssl rand -hex 16
来源：http://dali.pengpengdd.cyou/Article/details/gt2smxgmfaa.html

[R68] 计算文件校验值
来源：http://dali.shangyingyoupin.top/Article/details/gt2hxppyjgh.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.shuidangran.top/Article/details/gt2utpjgpxc.html

[R69] 生成随机密码
来源：http://dali.gaohongyu789.top/Article/details/gt2hyxvzgma.html

head -c 16 /dev/urandom | base64
来源：http://dali.wangdashe.top/Article/details/gt2nwhuwpaj.html

[R70] 时间戳与互转
来源：http://dali.cucudq.cn/Article/details/gt2lnkptnzd.html

date +%s;  date -d @1700000000
来源：http://dali.aizwys.cn/Article/details/gt2kgasguou.html

[R71] 日期格式化
来源：http://dali.nanxinkj.top/Article/details/gt2rretrgfh.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.havefunace.top/Article/details/gt2xofpwenq.html

[R72] 等待端口就绪
来源：http://dali.yanxiufei.cn/Article/details/gt2ydytanlm.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.cucudq.cn/Article/details/gt2ufjeuwom.html

[R73] 分割大日志
来源：http://dali.316326.xyz/Article/details/gt2iawpyvao.html

split -l 1000 big.log part_
来源：http://dali.aibaodan.cn/Article/details/gt2hjpsbrns.html

[R74] 批量重命名
来源：http://dali.yongpay.top/Article/details/gt2hpwjtqek.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.jianghu66.top/Article/details/gt2apdwcxog.html

[R75] 导出环境变量
来源：http://dali.pycfn.com/Article/details/gt2ubylsovz.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.yj202588.top/Article/details/gt2tnkawxzf.html

[R76] 使用临时文件
来源：http://dali.fzhhl.top/Article/details/gt2pblrjxrc.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mhxgytrd.html

[R77] 读取用户输入
来源：http://dali.fengsongda.top/Article/details/gt2vpzwpobw.html

read -rp "请输入: " ans
来源：http://dali.guannengcc.top/Article/details/gt2pkooidlt.html

[R78] 交互式菜单
来源：http://dali.zhoulong.xyz/Article/details/gt2prmtaagl.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.sysykeji.top/Article/details/gt2qtcpeqoy.html

[R79] 解析命令行选项
来源：http://dali.yangfankeji.com/Article/details/gt2fffqpacj.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.gaohongyu789.top/Article/details/gt2psfxftmc.html

[R80] 查看脚本执行耗时
来源：http://dali.c1oappe.top/Article/details/gt2lkwkadvk.html

time ./run.sh
来源：http://dali.zhixingplan.top/Article/details/gt2fqpjapsh.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gt2tkswantu.html

S. C / C++ 专题
来源：http://dali.vqdsnc.cn/Article/details/gt2sejupvdq.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2bmrplqve.html

[S01] C：Hello World
来源：http://dali.dashuyun.cn/Article/details/gt2rjtbeide.html

#include <stdio.h>
来源：http://dali.jqgfzy.top/Article/details/gt2ozyczhsy.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.tian-w.cn/Article/details/gt2aiqgbsrg.html

[S02] C：变量与格式化输出
来源：http://dali.nanxinkj.top/Article/details/gt2ycqgptid.html

int a = 10; printf("%d\n", a);
来源：http://dali.cucudq.cn/Article/details/gt2dzbghlme.html

[S03] C：读入整数
来源：http://dali.yanxiufei.cn/Article/details/gt2qctvvezn.html

int x; scanf("%d", &x);
来源：http://dali.nanxuanxn.top/Article/details/gt2eswqlnyu.html

[S04] C：字符串复制
来源：http://dali.jlsjyb.cn/Article/details/gt2upetprka.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.xinyue.icu/Article/details/gt2wambnjnk.html

[S05] C：字符串长度
来源：http://dali.aizwys.cn/Article/details/gt2pscawqax.html

strlen(s)
来源：http://dali.guannengcc.top/Article/details/gt2wwnqhosd.html

[S06] C：字符串比较
来源：http://dali.9152youxi.cn/Article/details/gt2moxzqieo.html

strcmp(a, b) == 0
来源：http://dali.sufxvd.cn/Article/details/gt2sdmulave.html

[S07] C：数组遍历求和
来源：http://dali.tianlin.xyz/Article/details/gt2oppzbgdd.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.hongshengwenyu.top/Article/details/gt2dxijxknh.html

[S08] C：动态内存分配与释放
来源：http://dali.pycfn.com/Article/details/gt2cghgsnkd.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.jqgufenzy.top/Article/details/gt2szvzcnwc.html

[S09] C：结构体定义与初始化
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ypxfegkn.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.cheryme.top/Article/details/gt2ymsclyas.html

[S10] C：指针与解引用
来源：http://dali.jianghu66.top/Article/details/gt2ndsjnuat.html

int *p = &a;  *p = 5;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tsjccnmb.html

[S11] C：逐行读文件
来源：http://dali.yj202588.top/Article/details/gt2rrjcrsbh.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.nanxuanxn.top/Article/details/gt2xugcoijw.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.dashuyun.cn/Article/details/gt2bkgjlnmr.html

fclose(f);
来源：http://dali.hongshengwenyu.top/Article/details/gt2mnlflhrs.html

[S12] C：写文件
来源：http://dali.hongshengwenyu.top/Article/details/gt2dgvsliri.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.shangyingyoupin.top/Article/details/gt2vodnwdqv.html

[S13] C：宏定义
来源：http://dali.hywenlv.cn/Article/details/gt2naixiprz.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.yueranfly.top/Article/details/gt2hpfimrnr.html

[S14] C：枚举
来源：http://dali.kuanghao11.cn/Article/details/gt2xjkdjtyo.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.snrcjt.cn/Article/details/gt2axnthshr.html

[S15] C：类型转换
来源：http://dali.chenjidiqi.icu/Article/details/gt2nfgjlryu.html

(double) a / b
来源：http://dali.mhx1999.top/Article/details/gt2ttxuzzbm.html

[S16] C：位操作置位
来源：http://dali.hywenlv.cn/Article/details/gt2ccgvuubc.html

x |= (1 << 3);
来源：http://dali.zhixingplan.top/Article/details/gt2ujukiksr.html

[S17] C：安全拼接字符串
来源：http://dali.xinyue.icu/Article/details/gt2aejdydkp.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.yvedp.cn/Article/details/gt2gjveabmj.html

[S18] C：命令行参数
来源：http://dali.yvedp.cn/Article/details/gt2calaznna.html

int main(int argc, char **argv)
来源：http://dali.snrcjt.cn/Article/details/gt2veiajomi.html

[S19] C：快速排序
来源：http://dali.tian-w.cn/Article/details/gt2palytiul.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.ivvv.top/Article/details/gt2zizmunau.html

[S20] C：二分查找
来源：http://dali.zdqjudy.top/Article/details/gt2lpipxudu.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zycfv.cn/Article/details/gt2aucxsycy.html

[S21] C：字符类别判断
来源：http://dali.meibo888.top/Article/details/gt2ykkayfsi.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhongyouzk.top/Article/details/gt2jtvrwvpr.html

[S22] C：字符串转数字
来源：http://dali.jinqigufen.top/Article/details/gt2eeetjopx.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.yonumen.top/Article/details/gt2zsxcqwbc.html

[S23] C：随机数
来源：http://dali.xylfe.cn/Article/details/gt2ksgabtgs.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.wangdashe.top/Article/details/gt2tdgeljts.html

[S24] C：获取本地时间
来源：http://dali.316326.xyz/Article/details/gt2tonoikbi.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.daxiang520.top/Article/details/gt2dbmrylay.html

[S25] C：内存拷贝
来源：http://dali.chenjidiqi.icu/Article/details/gt2pmgdfmtl.html

memcpy(dst, src, n);
来源：http://dali.iojbl.cn/Article/details/gt2aztdqwfs.html

[S26] C：内存清零
来源：http://dali.chenjidiqi.icu/Article/details/gt2rkqjdwmi.html

memset(a, 0, sizeof a);
来源：http://dali.haohaochexian.top/Article/details/gt2iiobesdr.html

[S27] C：定义常量
来源：http://dali.yangfankeji.com/Article/details/gt2pqshocbt.html

const double PI = 3.14159;
来源：http://dali.nanxinkj.top/Article/details/gt2cyapgbom.html

[S28] C：静态变量
来源：http://dali.0kj1m.cn/Article/details/gt2ngfnobvr.html

static int counter = 0;
来源：http://dali.redwolf501.top/Article/details/gt2hamtvbiz.html

[S29] C：变参函数
来源：http://dali.sysykeji.top/Article/details/gt2izhgvehw.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.chenjidiqi.icu/Article/details/gt2qqhyasae.html

[S30] C：头文件保护
来源：http://dali.jyoumei.cn/Article/details/gt2taydmixl.html

#ifndef X_H
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jzclsirn.html

#define X_H
来源：http://dali.jqgfzy.top/Article/details/gt2zdaklasc.html

#endif
来源：http://dali.gotoacloud.top/Article/details/gt2qicitblb.html

[S31] C++：Hello World
来源：http://dali.daria6918.cn/Article/details/gt2fbkcfkaq.html

#include <iostream>
来源：http://dali.meibo888.top/Article/details/gt2mnsmfzph.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.kuanghao11.cn/Article/details/gt2wcfqjyqx.html

[S32] C++：字符串
来源：http://dali.birdmap.top/Article/details/gt2vtmpjclu.html

std::string s = "hi";  s += "!";
来源：http://dali.iojbl.cn/Article/details/gt2fyooxwpl.html

[S33] C++：vector 增删
来源：http://dali.0kj1m.cn/Article/details/gt2rfxsdrhh.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhoulong.xyz/Article/details/gt2wgjvawvr.html

[S34] C++：遍历 vector
来源：http://dali.gzhubu.top/Article/details/gt2wpaxxsal.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xffcumcm.html

[S35] C++：map
来源：http://dali.yuxming.cn/Article/details/gt2hqdclihb.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.tanke756.top/Article/details/gt2rykuugys.html

[S36] C++：unordered_map
来源：http://dali.jyoumei.cn/Article/details/gt2tjgwmknj.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2viikezki.html

[S37] C++：set
来源：http://dali.zycfv.cn/Article/details/gt2ihqazehi.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.shzxlz.cn/Article/details/gt2euxvasll.html

[S38] C++：排序
来源：http://dali.yvedp.cn/Article/details/gt2zhzocmao.html

std::sort(v.begin(), v.end());
来源：http://dali.smart0.xyz/Article/details/gt2qmsepjtl.html

[S39] C++：自定义比较器排序
来源：http://dali.yj20258888.top/Article/details/gt2guslmpgf.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.xuanzx.com/Article/details/gt2irfumqma.html

[S40] C++：查找元素
来源：http://dali.ybcxt.top/Article/details/gt2elqiwngf.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.svipenyu.cn/Article/details/gt2woqanqqn.html

[S41] C++：类与构造函数
来源：http://dali.gzhubu.top/Article/details/gt2ugihblsh.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2drhurdzw.html

[S42] C++：继承与虚函数
来源：http://dali.fengsongda.top/Article/details/gt2vohvftfg.html

class B : public Base { public: void f() override {} };
来源：http://dali.hfpthk.cn/Article/details/gt2bbgxzoyr.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2umlfgcee.html

auto p = std::make_unique<int>(5);
来源：http://dali.quarkkingdee.top/Article/details/gt2ydpeiwpp.html

[S44] C++：引用传参
来源：http://dali.pengpengdd.cyou/Article/details/gt2cwsptyki.html

void inc(int &x) { ++x; }
来源：http://dali.guowangkeji.top/Article/details/gt2hunhupad.html

[S45] C++：lambda
来源：http://dali.xziqi.cn/Article/details/gt2mfmtslnp.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.hysaishi.cn/Article/details/gt2cfviqlhz.html

[S46] C++：函数模板
来源：http://dali.hfpthk.cn/Article/details/gt2apvvieis.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.wangdashe.top/Article/details/gt2rbffrgap.html

[S47] C++：结构化绑定遍历
来源：http://dali.sufxvd.cn/Article/details/gt2jraiqnmg.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.dianchejie.cn/Article/details/gt2rtfrkehi.html

[S48] C++：逐行读文件
来源：http://dali.chenjidiqi.icu/Article/details/gt2khxqnbpq.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.aizwys.cn/Article/details/gt2mjptkqph.html

while (std::getline(in, line)) { }
来源：http://dali.zhixingplan.top/Article/details/gt2zgzhlnxh.html

[S49] C++：写文件
来源：http://dali.haohaochexian.top/Article/details/gt2wshotsbd.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.cqqwz.cn/Article/details/gt2cazgmdjr.html

[S50] C++：格式化数字
来源：http://dali.yuxming.cn/Article/details/gt2qbwyvzcg.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.dashuyun.cn/Article/details/gt2owjtscfh.html

[S51] C++：显式类型转换
来源：http://dali.zhoulong.xyz/Article/details/gt2qnulwokc.html

static_cast<double>(a) / b
来源：http://dali.pycfn.com/Article/details/gt2mmmdtayo.html

[S52] C++：const 与 noexcept
来源：http://dali.shzxlz.cn/Article/details/gt2hilsmpxx.html

int size() const noexcept { return n_; }
来源：http://dali.xinyue.icu/Article/details/gt2vhghsome.html

[S53] C++：移动语义
来源：http://dali.pengpengdd.cyou/Article/details/gt2vjmlztih.html

std::vector<int> w = std::move(v);
来源：http://dali.chenlongwang.top/Article/details/gt2ssknjrat.html

[S54] C++：异常处理
来源：http://dali.chenzaomai.com/Article/details/gt2zdltdusr.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.wangshuangyany.cn/Article/details/gt2knirxjnq.html

[S55] C++：结构化绑定
来源：http://dali.ppjwa.cn/Article/details/gt2maqyuwos.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.hnqzz.top/Article/details/gt2gbneehjp.html

[S56] C++：optional
来源：http://dali.gogol.net.cn/Article/details/gt2wunsxhrb.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.vqdsnc.cn/Article/details/gt2wcszkzam.html

[S57] C++：编译期常量
来源：http://dali.svipenyu.cn/Article/details/gt2mkhssuiw.html

constexpr int N = 10;
来源：http://dali.guowangkeji.top/Article/details/gt2qowjnoat.html

[S58] C++：命名空间
来源：http://dali.jiagoushi.top/Article/details/gt2gqffggkz.html

namespace ns { int f() { return 1; } }
来源：http://dali.hnqzz.top/Article/details/gt2hkrrffeh.html

[S59] C++：静态断言
来源：http://dali.gzhubu.top/Article/details/gt2jkwouopi.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.xinyue.icu/Article/details/gt2ojddnbdo.html

[S60] C++：遍历并删除元素
来源：http://dali.kuanghao11.cn/Article/details/gt2xmxkwuzt.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.cdnleiting.top/Article/details/gt2tuslwfas.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2zubzobtk.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.hnxiangtu.top/Article/details/gt2uxdnrwff.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2ughtudhf.html

[T01] Kotlin：Hello World
来源：http://dali.316326.xyz/Article/details/gt2kkjrbiwk.html

println("Hello")
来源：http://dali.nanxinkj.top/Article/details/gt2ytctqpyt.html

[T02] Kotlin：变量
来源：http://dali.dianchejie.cn/Article/details/gt2qnoquijr.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.shzxlz.cn/Article/details/gt2wylspcpu.html

[T03] Kotlin：字符串模板
来源：http://dali.bjfxy.top/Article/details/gt2myhziuey.html

"值: $b"
来源：http://dali.gzhubu.top/Article/details/gt2ikfzbcyp.html

[T04] Kotlin：空安全
来源：http://dali.jinqigfzy.top/Article/details/gt2jirfenrd.html

val n: String? = null;  n?.length
来源：http://dali.hywenlv.cn/Article/details/gt2rjvokive.html

[T05] Kotlin：when 表达式
来源：http://dali.gogol.net.cn/Article/details/gt2kgqbotao.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.chenjidiqi.icu/Article/details/gt2fjpecobo.html

[T06] Kotlin：集合映射
来源：http://dali.wangdashe.top/Article/details/gt2wcepeymq.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.hywenlv.cn/Article/details/gt2jacwibxp.html

[T07] Kotlin：集合过滤
来源：http://dali.shanyushiyangtech.top/Article/details/gt2txklmpcc.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.sufxvd.cn/Article/details/gt2dyniztuj.html

[T08] Kotlin：数据类
来源：http://dali.snrcjt.cn/Article/details/gt2okazyzbu.html

data class User(val name: String, val age: Int)
来源：http://dali.zdqjudy.top/Article/details/gt2ywmycfok.html

[T09] Kotlin：扩展函数
来源：http://dali.sysykeji.top/Article/details/gt2ffzndtoo.html

fun String.exclaim() = this + "!"
来源：http://dali.jiagoushi.top/Article/details/gt2zxbbdpou.html

[T10] Kotlin：默认参数
来源：http://dali.cdnleiting.top/Article/details/gt2guhiswoo.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.hfpthk.cn/Article/details/gt2ecvncaxd.html

[T11] Kotlin：协程
来源：http://dali.quarkkingdee.top/Article/details/gt2gdewkubp.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.birdmap.top/Article/details/gt2enkhzgwb.html

[T12] Kotlin：解构声明
来源：http://dali.tian-w.cn/Article/details/gt2caygnoca.html

val (a, b) = Pair(1, 2)
来源：http://dali.yuxming.cn/Article/details/gt2alysdpey.html

[T13] Kotlin：只读 Map
来源：http://dali.iojbl.cn/Article/details/gt2drlngtad.html

val m = mapOf("a" to 1)
来源：http://dali.jyoumei.cn/Article/details/gt2wturrzrf.html

[T14] Kotlin：循环
来源：http://dali.cheryme.top/Article/details/gt2vuogbkws.html

for (i in 1..10) println(i)
来源：http://dali.gzhubu.top/Article/details/gt2niwrrsqv.html

[T15] Kotlin：接口
来源：http://dali.jinqigufen.top/Article/details/gt2fnhivjuu.html

interface Shape { fun area(): Double }
来源：http://dali.snrcjt.cn/Article/details/gt2wzfscmzb.html

[T16] Swift：Hello World
来源：http://dali.feifeiyinyue.top/Article/details/gt2cubyrsbd.html

print("Hello")
来源：http://dali.xuanzx.com/Article/details/gt2nrnuimos.html

[T17] Swift：变量与常量
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2riqlkrbd.html

var a = 1;  let b = 2
来源：http://dali.aibaodan.cn/Article/details/gt2houcnlrb.html

[T18] Swift：字符串插值
来源：http://dali.sufxvd.cn/Article/details/gt2efpkxlcr.html

"值: \(b)"
来源：http://dali.wangdashe.top/Article/details/gt2rmgidskf.html

[T19] Swift：可选绑定
来源：http://dali.yonumen.top/Article/details/gt2cvwuglys.html

if let n = opt { print(n) }
来源：http://dali.chenjidiqi.icu/Article/details/gt2nelqzjoo.html

[T20] Swift：数组操作
来源：http://dali.zhengqikj.top/Article/details/gt2ldpwhiie.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ghayctgh.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2nijoxnor.html

for x in a { print(x) }
来源：http://dali.zhongyouzk.top/Article/details/gt2xiqppfor.html

[T22] Swift：字典
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fmolvwlk.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.shanyushiyangtech.top/Article/details/gt2femkybqf.html

[T23] Swift：函数
来源：http://dali.zhoulong.xyz/Article/details/gt2pzskrscq.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.jqgufenzy.top/Article/details/gt2rnlzfqms.html

[T24] Swift：闭包
来源：http://dali.svipenyu.cn/Article/details/gt2gtzdevek.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.hnqzz.top/Article/details/gt2vfngmvug.html

[T25] Swift：结构体
来源：http://dali.iojbl.cn/Article/details/gt2egdnfmif.html

struct P { var x: Int }
来源：http://dali.yonumen.top/Article/details/gt2hkyjzgvd.html

[T26] Swift：类与重写
来源：http://dali.0kj1m.cn/Article/details/gt2xrrlpjcm.html

class A: Base { override func f() {} }
来源：http://dali.sxryk.cn/Article/details/gt2liqdleot.html

[T27] Swift：错误处理
来源：http://dali.jianghu66.top/Article/details/gt2odqxpwah.html

do { try f() } catch { print(error) }
来源：http://dali.yuanzhike.top/Article/details/gt2tkxkkhgb.html

[T28] Swift：枚举
来源：http://dali.hnqzz.top/Article/details/gt2jyuimiyq.html

enum Color { case red, green }
来源：http://dali.ivvv.top/Article/details/gt2jsgoirhd.html

[T29] Swift：guard 提前返回
来源：http://dali.zhoulong.xyz/Article/details/gt2aynzdatg.html

guard let x = opt else { return }
来源：http://dali.316326.xyz/Article/details/gt2nvtkkjkr.html

[T30] Swift：协议
来源：http://dali.yangfankeji.com/Article/details/gt2ufrpestf.html

protocol Shape { func area() -> Double }
来源：http://dali.hongshengwenyu.top/Article/details/gt2vgsxauki.html

[T31] Lua：Hello World
来源：http://dali.xuetiantiany.cn/Article/details/gt2uscvafmd.html

print("Hello")
来源：http://dali.aibaodan.cn/Article/details/gt2mwbdenmp.html

[T32] Lua：局部变量
来源：http://dali.shuidangran.top/Article/details/gt2pvqbmzmg.html

local a = 1
来源：http://dali.fengsongda.top/Article/details/gt2keavpwxp.html

[T33] Lua：表（数组）
来源：http://dali.snrcjt.cn/Article/details/gt2rucspysm.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.dashuyun.cn/Article/details/gt2bvlhwxxp.html

[T34] Lua：遍历表
来源：http://dali.zdqjudy.top/Article/details/gt2wmbvnzqg.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.gzhubu.top/Article/details/gt2acyeiljo.html

[T35] Lua：字典表
来源：http://dali.chenlongwang.top/Article/details/gt2rmxjjbtj.html

local d = { a = 1 };  d.b = 2
来源：http://dali.aizwys.cn/Article/details/gt2vrsiwmfn.html

[T36] Lua：函数
来源：http://dali.jiagoushi.top/Article/details/gt2woqfkapl.html

function add(a, b) return a + b end
来源：http://dali.jlsjyb.cn/Article/details/gt2eivellpv.html

[T37] Lua：字符串拼接
来源：http://dali.birdmap.top/Article/details/gt2judtqpad.html

"a" .. "b"
来源：http://dali.sufxvd.cn/Article/details/gt2brlihnza.html

[T38] Lua：条件
来源：http://dali.gzhubu.top/Article/details/gt2noxcsdbi.html

if x > 0 then print("正") end
来源：http://dali.gotoacloud.top/Article/details/gt2cxwcvqqa.html

[T39] Lua：模式匹配
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fabdizub.html

string.find(s, "%d+")
来源：http://dali.andypj.xyz/Article/details/gt2frgagtcb.html

[T40] Lua：元表
来源：http://dali.nanxuanxn.top/Article/details/gt2opuxaqzl.html

setmetatable({}, { __index = base })
来源：http://dali.cucudq.cn/Article/details/gt2mnynvmht.html


<!-- 参考信息 -->