代发 wailian999

files=$(ls -1)
来源：http://dali.kuanghao11.cn/Article/details/gt2ezbboeln.html

[R38] 管道串联
来源：http://dali.zdqjudy.top/Article/details/gt2spwexznz.html

cat a.txt | grep -i error | wc -l
来源：http://dali.vqdsnc.cn/Article/details/gt2hvmmgjxg.html

[R39] 重定向标准输出与错误
来源：http://dali.yvedp.cn/Article/details/gt2lkfiapjf.html

cmd > out.log 2>&1
来源：http://dali.daxiang520.top/Article/details/gt2nnyylneo.html

[R40] 追加写日志
来源：http://dali.hysaishi.cn/Article/details/gt2nyxygavb.html

echo "log" >> out.log
来源：http://dali.dashuyun.cn/Article/details/gt2czjzxwkz.html

[R41] 丢弃输出
来源：http://dali.gzhubu.top/Article/details/gt2cnlbtlpl.html

cmd >/dev/null 2>&1
来源：http://dali.hnxiangtu.top/Article/details/gt2kpprqgty.html

[R42] 输入重定向
来源：http://dali.ybcxt.top/Article/details/gt2zphauplv.html

wc -l < a.txt
来源：http://dali.snrcjt.cn/Article/details/gt2wszdntfg.html

[R43] 按名字查找文件
来源：http://dali.pengpengdd.cyou/Article/details/gt2axgmbqnl.html

find . -name "*.log" -type f
来源：http://dali.zhengqikj.top/Article/details/gt2wldtnvfq.html

[R44] 按修改时间查找
来源：http://dali.xziqi.cn/Article/details/gt2ctkzbuwz.html

find . -mtime -7 -type f
来源：http://dali.yj20258.top/Article/details/gt2mdsjdrcg.html

[R45] 批量删除
来源：http://dali.dianchejie.cn/Article/details/gt2rfwbweat.html

find . -name "*.tmp" -delete
来源：http://dali.gotoacloud.top/Article/details/gt2cclwfozt.html

[R46] 递归替换文件内容
来源：http://dali.cucudq.cn/Article/details/gt2jmblwkge.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.xziqi.cn/Article/details/gt2mhtjpvdv.html

[R47] sed 单行替换
来源：http://dali.chenjidiqi.icu/Article/details/gt2hyslacib.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zdqjudy.top/Article/details/gt2kxxlfpmt.html

[R48] awk 取指定列
来源：http://dali.gaohongyu789.top/Article/details/gt2xfvezohm.html

awk '{print $1, $3}' a.txt
来源：http://dali.jianghu66.top/Article/details/gt2nxfduesk.html

[R49] awk 带条件
来源：http://dali.c1oappe.top/Article/details/gt2dmlkdxqn.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.ppjwa.cn/Article/details/gt2tfviarna.html

[R50] awk 求和
来源：http://dali.smart0.xyz/Article/details/gt2zspngpbm.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.jyoumei.cn/Article/details/gt2xnxswusb.html

[R51] 排序去重取前几
来源：http://dali.cashguo.top/Article/details/gt2mwfxealj.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.xziqi.cn/Article/details/gt2prbjcvkx.html

[R52] 统计行数
来源：http://dali.pycfn.com/Article/details/gt2dshlakwi.html

wc -l a.txt
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ypxalnwd.html

[R53] 查看文件头与实时尾
来源：http://dali.zhoulong.xyz/Article/details/gt2eglxltwu.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.shzxlz.cn/Article/details/gt2ugfkeurp.html

[R54] 比较两个文件
来源：http://dali.guowangkeji.top/Article/details/gt2dnlrcacb.html

diff a.txt b.txt
来源：http://dali.9152youxi.cn/Article/details/gt2zbzutekq.html

[R55] 压缩与解压
来源：http://dali.xylfe.cn/Article/details/gt2jesbnply.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2axrnttnh.html

[R56] 远程拷贝
来源：http://dali.yueranfly.top/Article/details/gt2qqpnbnxk.html

scp file user@host:/path/
来源：http://dali.svipenyu.cn/Article/details/gt2rdblodtj.html

[R57] 远程执行命令
来源：http://dali.mhx1999.top/Article/details/gt2sasxfprk.html

ssh user@host 'uptime'
来源：http://dali.feifeiyinyue.top/Article/details/gt2kuhuukgz.html

[R58] 下载文件
来源：http://dali.zdqjudy.top/Article/details/gt2rxzyvefi.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bxefifms.html

[R59] 发 POST JSON
来源：http://dali.cdnleiting.top/Article/details/gt2jsqwmqzd.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.shuidangran.top/Article/details/gt2ywxwlyjv.html

[R60] 只看 HTTP 状态码
来源：http://dali.shzxlz.cn/Article/details/gt2dyxuwevo.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.hammf.cn/Article/details/gt2dpbggnrg.html

[R61] 磁盘占用
来源：http://dali.ppjwa.cn/Article/details/gt2blgiajhb.html

df -h;  du -sh *
来源：http://dali.zhiwuduotai.top/Article/details/gt2layngsqy.html

[R62] 找最占空间的文件
来源：http://dali.wangdashe.top/Article/details/gt2imrhsilz.html

du -ah . | sort -rh | head -10
来源：http://dali.dianchejie.cn/Article/details/gt2zykgbith.html

[R63] 内存与进程
来源：http://dali.zhixingplan.top/Article/details/gt2amiqlsdm.html

free -h;  ps aux | grep nginx
来源：http://dali.pycfn.com/Article/details/gt2itecsysl.html

[R64] 结束进程
来源：http://dali.yuxming.cn/Article/details/gt2euylfmhn.html

kill -9 $(pgrep -f app.py)
来源：http://dali.chenzaomai.com/Article/details/gt2qcmfkbyh.html

[R65] 查看端口占用
来源：http://dali.xinyue.icu/Article/details/gt2tbsayetz.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhengqikj.top/Article/details/gt2imilkleg.html

[R66] 定时任务
来源：http://dali.xinyue.icu/Article/details/gt2vweocqtd.html

crontab -e;  crontab -l
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qsajmjxh.html

[R67] 生成随机十六进制串
来源：http://dali.jyoumei.cn/Article/details/gt2fjbbzeqx.html

openssl rand -hex 16
来源：http://dali.iojbl.cn/Article/details/gt2heegswel.html

[R68] 计算文件校验值
来源：http://dali.c1oappe.top/Article/details/gt2tlqdxiua.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.meibo888.top/Article/details/gt2fwjrbopl.html

[R69] 生成随机密码
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xugphblb.html

head -c 16 /dev/urandom | base64
来源：http://dali.yj20258888.top/Article/details/gt2teuwttva.html

[R70] 时间戳与互转
来源：http://dali.andypj.xyz/Article/details/gt2eaezxxoc.html

date +%s;  date -d @1700000000
来源：http://dali.ydzc1.top/Article/details/gt2yayfvqij.html

[R71] 日期格式化
来源：http://dali.vqdsnc.cn/Article/details/gt2gmynjmzd.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.gotoacloud.top/Article/details/gt2yjcykbpo.html

[R72] 等待端口就绪
来源：http://dali.meibo888.top/Article/details/gt2tgnfjkkl.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.hysaishi.cn/Article/details/gt2vpwcxjao.html

[R73] 分割大日志
来源：http://dali.0kj1m.cn/Article/details/gt2tcgkvkod.html

split -l 1000 big.log part_
来源：http://dali.yongpay.top/Article/details/gt2wevwbinm.html

[R74] 批量重命名
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qjuacspd.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.sweek.top/Article/details/gt2cwqytbfd.html

[R75] 导出环境变量
来源：http://dali.snrcjt.cn/Article/details/gt2cixcxwbj.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhixingplan.top/Article/details/gt2zfeugijt.html

[R76] 使用临时文件
来源：http://dali.jinqigfzy.top/Article/details/gt2ckbuxuko.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.pengpengdd.cyou/Article/details/gt2rklumejz.html

[R77] 读取用户输入
来源：http://dali.chenlongwang.top/Article/details/gt2kkpspakj.html

read -rp "请输入: " ans
来源：http://dali.zhongyouzk.top/Article/details/gt2ljnfcglg.html

[R78] 交互式菜单
来源：http://dali.cucudq.cn/Article/details/gt2fthjseap.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.hfpthk.cn/Article/details/gt2lnnngncb.html

[R79] 解析命令行选项
来源：http://dali.shuidangran.top/Article/details/gt2dcaesmae.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.yj20258888.top/Article/details/gt2jvemlgtu.html

[R80] 查看脚本执行耗时
来源：http://dali.birdmap.top/Article/details/gt2jndkuibw.html

time ./run.sh
来源：http://dali.xinyue.icu/Article/details/gt2sdpxbvly.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2wkbuqyno.html

S. C / C++ 专题
来源：http://dali.xuetiantiany.cn/Article/details/gt2kdqudydx.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2appjzvvh.html

[S01] C：Hello World
来源：http://dali.haohaochexian.top/Article/details/gt2pvvwcuap.html

#include <stdio.h>
来源：http://dali.zycfv.cn/Article/details/gt2iskkwkan.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.gogol.net.cn/Article/details/gt2slcpkrai.html

[S02] C：变量与格式化输出
来源：http://dali.hnqzz.top/Article/details/gt2cngqwwvn.html

int a = 10; printf("%d\n", a);
来源：http://dali.ppjwa.cn/Article/details/gt2vliwhihy.html

[S03] C：读入整数
来源：http://dali.shangyingyoupin.top/Article/details/gt2kgpasqnp.html

int x; scanf("%d", &x);
来源：http://dali.9152youxi.cn/Article/details/gt2zsxiwnwh.html

[S04] C：字符串复制
来源：http://dali.xuetiantiany.cn/Article/details/gt2qyxsecyl.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.tianlin.xyz/Article/details/gt2nqicmxqq.html

[S05] C：字符串长度
来源：http://dali.jianghu66.top/Article/details/gt2mqsdhcej.html

strlen(s)
来源：http://dali.smart0.xyz/Article/details/gt2wzrfnujm.html

[S06] C：字符串比较
来源：http://dali.ydzc1.top/Article/details/gt2gwvdjnze.html

strcmp(a, b) == 0
来源：http://dali.jqgfzy.top/Article/details/gt2gfwgjocg.html

[S07] C：数组遍历求和
来源：http://dali.yangfankeji.com/Article/details/gt2gtsiyket.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.jlsjyb.cn/Article/details/gt2xyenqllf.html

[S08] C：动态内存分配与释放
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lwzolkkf.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.fzhhl.top/Article/details/gt2ubjnitds.html

[S09] C：结构体定义与初始化
来源：http://dali.yj202588.top/Article/details/gt2cxsogoud.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.quarkkingdee.top/Article/details/gt2ijpynpei.html

[S10] C：指针与解引用
来源：http://dali.andypj.xyz/Article/details/gt2jfnkbcxh.html

int *p = &a;  *p = 5;
来源：http://dali.shangyingyoupin.top/Article/details/gt2waeomeak.html

[S11] C：逐行读文件
来源：http://dali.xinyue.icu/Article/details/gt2zkcltrek.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.daxiang520.top/Article/details/gt2qgdnpxgh.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.sxryk.cn/Article/details/gt2hucanogh.html

fclose(f);
来源：http://dali.wangshuangyany.cn/Article/details/gt2sakbrthd.html

[S12] C：写文件
来源：http://dali.hywenlv.cn/Article/details/gt2fswjzgjk.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.ydzc1.top/Article/details/gt2cwvddhdu.html

[S13] C：宏定义
来源：http://dali.zhixingplan.top/Article/details/gt2rhyenvoq.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhixingplan.top/Article/details/gt2cekuolxr.html

[S14] C：枚举
来源：http://dali.sufxvd.cn/Article/details/gt2ixvjwfuz.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.yvedp.cn/Article/details/gt2scnysjsx.html

[S15] C：类型转换
来源：http://dali.dashuyun.cn/Article/details/gt2zbspzvqh.html

(double) a / b
来源：http://dali.zhoulong.xyz/Article/details/gt2cwcltzje.html

[S16] C：位操作置位
来源：http://dali.meibo888.top/Article/details/gt2hldtcqbm.html

x |= (1 << 3);
来源：http://dali.shangyingyoupin.top/Article/details/gt2ouvoomft.html

[S17] C：安全拼接字符串
来源：http://dali.gzhubu.top/Article/details/gt2qkrnrfyt.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.nwbrower.top/Article/details/gt2otwdstri.html

[S18] C：命令行参数
来源：http://dali.haohaochexian.top/Article/details/gt2daexdseu.html

int main(int argc, char **argv)
来源：http://dali.yueranfly.top/Article/details/gt2bdowtfje.html

[S19] C：快速排序
来源：http://dali.meibo888.top/Article/details/gt2eojxvvey.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.haohaochexian.top/Article/details/gt2yljgsrtz.html

[S20] C：二分查找
来源：http://dali.c1oappe.top/Article/details/gt2nbrczqrx.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.ybcxt.top/Article/details/gt2orangxus.html

[S21] C：字符类别判断
来源：http://dali.jqgufenzy.top/Article/details/gt2ohzdwphp.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.shangyingyoupin.top/Article/details/gt2canojbor.html

[S22] C：字符串转数字
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zqmfqsnx.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.cheryme.top/Article/details/gt2tpvktsfe.html

[S23] C：随机数
来源：http://dali.yueranfly.top/Article/details/gt2qkmfwpbe.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.xinyue.icu/Article/details/gt2pyxwiaaq.html

[S24] C：获取本地时间
来源：http://dali.wangdashe.top/Article/details/gt2ijuxuxjz.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jwbfpntz.html

[S25] C：内存拷贝
来源：http://dali.gotoacloud.top/Article/details/gt2lpkptyjx.html

memcpy(dst, src, n);
来源：http://dali.pycfn.com/Article/details/gt2pgpzfxni.html

[S26] C：内存清零
来源：http://dali.nwbrower.top/Article/details/gt2nvezdewz.html

memset(a, 0, sizeof a);
来源：http://dali.yangfankeji.com/Article/details/gt2mwaavxto.html

[S27] C：定义常量
来源：http://dali.sysykeji.top/Article/details/gt2pmggfcrj.html

const double PI = 3.14159;
来源：http://dali.iojbl.cn/Article/details/gt2ljggusln.html

[S28] C：静态变量
来源：http://dali.yuxming.cn/Article/details/gt2izzjglxu.html

static int counter = 0;
来源：http://dali.zdqjudy.top/Article/details/gt2asuzfblm.html

[S29] C：变参函数
来源：http://dali.jqgufenzy.top/Article/details/gt2mavusoin.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhixingplan.top/Article/details/gt2khdwfofr.html

[S30] C：头文件保护
来源：http://dali.daxiang520.top/Article/details/gt2ackphrsd.html

#ifndef X_H
来源：http://dali.hywenlv.cn/Article/details/gt2edvnhrke.html

#define X_H
来源：http://dali.tianlin.xyz/Article/details/gt2ogibiipb.html

#endif
来源：http://dali.c1oappe.top/Article/details/gt2jjmsfpfd.html

[S31] C++：Hello World
来源：http://dali.zhengqikj.top/Article/details/gt2yuevttep.html

#include <iostream>
来源：http://dali.nanxuanxn.top/Article/details/gt2xejyewjm.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.wangdashe.top/Article/details/gt2qrmicolv.html

[S32] C++：字符串
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2insiqilr.html

std::string s = "hi";  s += "!";
来源：http://dali.guannengcc.top/Article/details/gt2liwmiawr.html

[S33] C++：vector 增删
来源：http://dali.nwbrower.top/Article/details/gt2kuvpisan.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.haohaochexian.top/Article/details/gt2cmyebtdc.html

[S34] C++：遍历 vector
来源：http://dali.zycfv.cn/Article/details/gt2wkvnesqm.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.chenzaomai.com/Article/details/gt2bhvxohdd.html

[S35] C++：map
来源：http://dali.gogol.net.cn/Article/details/gt2myjlzxvl.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yvedp.cn/Article/details/gt2rooptunr.html

[S36] C++：unordered_map
来源：http://dali.9152youxi.cn/Article/details/gt2lqkeawdy.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.xuanzx.com/Article/details/gt2xlnmfcgw.html

[S37] C++：set
来源：http://dali.9152youxi.cn/Article/details/gt2mliieizt.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.ivvv.top/Article/details/gt2ylufsfle.html

[S38] C++：排序
来源：http://dali.9152youxi.cn/Article/details/gt2rodpgpfh.html

std::sort(v.begin(), v.end());
来源：http://dali.ehwqpu.com/Article/details/gt2zotbdcmv.html

[S39] C++：自定义比较器排序
来源：http://dali.sxryk.cn/Article/details/gt2hdkvwyht.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.shangyingyoupin.top/Article/details/gt2nzhfklzr.html

[S40] C++：查找元素
来源：http://dali.hysaishi.cn/Article/details/gt2wvvzssra.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.dashuyun.cn/Article/details/gt2zglolsty.html

[S41] C++：类与构造函数
来源：http://dali.yanxiufei.cn/Article/details/gt2ahhoqpmq.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.redwolf501.top/Article/details/gt2xvqbwxsq.html

[S42] C++：继承与虚函数
来源：http://dali.redwolf501.top/Article/details/gt2muvkkntj.html

class B : public Base { public: void f() override {} };
来源：http://dali.meibo888.top/Article/details/gt2hhrkpmoh.html

[S43] C++：智能指针
来源：http://dali.yj20258.top/Article/details/gt2msqeiabn.html

auto p = std::make_unique<int>(5);
来源：http://dali.svipenyu.cn/Article/details/gt2lkventab.html

[S44] C++：引用传参
来源：http://dali.yuxming.cn/Article/details/gt2xpnylyqv.html

void inc(int &x) { ++x; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bceygzmb.html

[S45] C++：lambda
来源：http://dali.xinyue.icu/Article/details/gt2mekvflnn.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.ehwqpu.com/Article/details/gt2dfaifraw.html

[S46] C++：函数模板
来源：http://dali.aibaodan.cn/Article/details/gt2pvfbmtoj.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.aizwys.cn/Article/details/gt2lbgzljdg.html

[S47] C++：结构化绑定遍历
来源：http://dali.ivvv.top/Article/details/gt2zebnwean.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.hnqzz.top/Article/details/gt2lqvstwnn.html

[S48] C++：逐行读文件
来源：http://dali.xylfe.cn/Article/details/gt2dajzvgez.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.wangshuangyany.cn/Article/details/gt2umziybay.html

while (std::getline(in, line)) { }
来源：http://dali.wangdashe.top/Article/details/gt2cinlxgnd.html

[S49] C++：写文件
来源：http://dali.snrcjt.cn/Article/details/gt2ruqtbtoy.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.gaohongyu789.top/Article/details/gt2mbzaelgt.html

[S50] C++：格式化数字
来源：http://dali.hnxiangtu.top/Article/details/gt2bcognczr.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.feifeiyinyue.top/Article/details/gt2mosuifrb.html

[S51] C++：显式类型转换
来源：http://dali.nwbrower.top/Article/details/gt2facbgelw.html

static_cast<double>(a) / b
来源：http://dali.shanyushiyangtech.top/Article/details/gt2swwwwqqn.html

[S52] C++：const 与 noexcept
来源：http://dali.haohaochexian.top/Article/details/gt2keagjiwz.html

int size() const noexcept { return n_; }
来源：http://dali.yuanzhike.top/Article/details/gt2ybjpixix.html

[S53] C++：移动语义
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ehkegtug.html

std::vector<int> w = std::move(v);
来源：http://dali.ydzc1.top/Article/details/gt2virwgxpy.html

[S54] C++：异常处理
来源：http://dali.shzxlz.cn/Article/details/gt2hgqggpis.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.yueranfly.top/Article/details/gt2tkyhocxj.html

[S55] C++：结构化绑定
来源：http://dali.wangdashe.top/Article/details/gt2rqgaovby.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gwjddgdk.html

[S56] C++：optional
来源：http://dali.jiagoushi.top/Article/details/gt2hbftekyd.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yj20258888.top/Article/details/gt2xaniesup.html

[S57] C++：编译期常量
来源：http://dali.svipenyu.cn/Article/details/gt2jkelklnb.html

constexpr int N = 10;
来源：http://dali.cheryme.top/Article/details/gt2cqclbdfq.html

[S58] C++：命名空间
来源：http://dali.nanxinkj.top/Article/details/gt2vchyeoem.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhiwuduotai.top/Article/details/gt2lbvlnkrj.html

[S59] C++：静态断言
来源：http://dali.xuanzx.com/Article/details/gt2ksyazzmm.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.guowangkeji.top/Article/details/gt2voyfbnwo.html

[S60] C++：遍历并删除元素
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2psjjcikq.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.yongpay.top/Article/details/gt2fwtgugkl.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2woeotobr.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.daria6918.cn/Article/details/gt2xakizoay.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2ftmhrkaw.html

[T01] Kotlin：Hello World
来源：http://dali.zhiwuduotai.top/Article/details/gt2syobzqtm.html

println("Hello")
来源：http://dali.yvedp.cn/Article/details/gt2zdtimwhc.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2exoxucxc.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.yj202588.top/Article/details/gt2dlagwqlj.html

[T03] Kotlin：字符串模板
来源：http://dali.cqqwz.cn/Article/details/gt2zzvyhkiz.html

"值: $b"
来源：http://dali.yj20258888.top/Article/details/gt2vigsnnnv.html

[T04] Kotlin：空安全
来源：http://dali.kuanghao11.cn/Article/details/gt2iekvpayl.html

val n: String? = null;  n?.length
来源：http://dali.dianchejie.cn/Article/details/gt2msfmlmjn.html

[T05] Kotlin：when 表达式
来源：http://dali.chenlongwang.top/Article/details/gt2hfqsrzcl.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.yanxiufei.cn/Article/details/gt2egnxwpwp.html

[T06] Kotlin：集合映射
来源：http://dali.daria6918.cn/Article/details/gt2hczcwvdc.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.feifeiyinyue.top/Article/details/gt2hsoigjbu.html

[T07] Kotlin：集合过滤
来源：http://dali.shuidangran.top/Article/details/gt2jqrtvhzt.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhixingplan.top/Article/details/gt2suentaka.html

[T08] Kotlin：数据类
来源：http://dali.316326.xyz/Article/details/gt2achvojsp.html

data class User(val name: String, val age: Int)
来源：http://dali.tanke756.top/Article/details/gt2vdhdqtrk.html

[T09] Kotlin：扩展函数
来源：http://dali.wangshuangyany.cn/Article/details/gt2clrxynac.html

fun String.exclaim() = this + "!"
来源：http://dali.smart0.xyz/Article/details/gt2wgcqpwwl.html

[T10] Kotlin：默认参数
来源：http://dali.hywenlv.cn/Article/details/gt2rhnctjmh.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.birdmap.top/Article/details/gt2acykzkki.html

[T11] Kotlin：协程
来源：http://dali.xuetiantiany.cn/Article/details/gt2fbykcerz.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zowqtngh.html

[T12] Kotlin：解构声明
来源：http://dali.xuetiantiany.cn/Article/details/gt2inwsayxz.html

val (a, b) = Pair(1, 2)
来源：http://dali.sysykeji.top/Article/details/gt2tyqoendm.html

[T13] Kotlin：只读 Map
来源：http://dali.yonumen.top/Article/details/gt2brjbswqv.html

val m = mapOf("a" to 1)
来源：http://dali.feifeiyinyue.top/Article/details/gt2kovnszfj.html

[T14] Kotlin：循环
来源：http://dali.sufxvd.cn/Article/details/gt2edxpyqkg.html

for (i in 1..10) println(i)
来源：http://dali.zhongyouzk.top/Article/details/gt2bwxsszqi.html

[T15] Kotlin：接口
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gagwjqrt.html

interface Shape { fun area(): Double }
来源：http://dali.yonumen.top/Article/details/gt2lbilbqdw.html

[T16] Swift：Hello World
来源：http://dali.cheryme.top/Article/details/gt2kcijkcmz.html

print("Hello")
来源：http://dali.jlsjyb.cn/Article/details/gt2nellbvvb.html

[T17] Swift：变量与常量
来源：http://dali.dashuyun.cn/Article/details/gt2lojileux.html

var a = 1;  let b = 2
来源：http://dali.c1oappe.top/Article/details/gt2ghrpsfpz.html

[T18] Swift：字符串插值
来源：http://dali.hammf.cn/Article/details/gt2ozbkbdxp.html

"值: \(b)"
来源：http://dali.zhengqikj.top/Article/details/gt2ulvmwdew.html

[T19] Swift：可选绑定
来源：http://dali.hammf.cn/Article/details/gt2mokmrhuu.html

if let n = opt { print(n) }
来源：http://dali.feifeiyinyue.top/Article/details/gt2xolkngxu.html

[T20] Swift：数组操作
来源：http://dali.yanxiufei.cn/Article/details/gt2ekfidgle.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.yj20258.top/Article/details/gt2fuvosudq.html

[T21] Swift：遍历
来源：http://dali.cqqwz.cn/Article/details/gt2xexbonya.html

for x in a { print(x) }
来源：http://dali.shangyingyoupin.top/Article/details/gt2fgzivezz.html

[T22] Swift：字典
来源：http://dali.shangyingyoupin.top/Article/details/gt2jcsmcjht.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sloxridc.html

[T23] Swift：函数
来源：http://dali.daxiang520.top/Article/details/gt2zfbyxtux.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.ppjwa.cn/Article/details/gt2lumoczrr.html

[T24] Swift：闭包
来源：http://dali.zhoulong.xyz/Article/details/gt2veoidsms.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.gotoacloud.top/Article/details/gt2ebyekhnj.html

[T25] Swift：结构体
来源：http://dali.andypj.xyz/Article/details/gt2ztqlakhi.html

struct P { var x: Int }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vthzqntb.html

[T26] Swift：类与重写
来源：http://dali.yj202588.top/Article/details/gt2mbhlynjk.html

class A: Base { override func f() {} }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ehectizf.html

[T27] Swift：错误处理
来源：http://dali.xylfe.cn/Article/details/gt2izidcxkx.html

do { try f() } catch { print(error) }
来源：http://dali.xinyue.icu/Article/details/gt2vudtqcwf.html

[T28] Swift：枚举
来源：http://dali.zdqjudy.top/Article/details/gt2plpkeiej.html

enum Color { case red, green }
来源：http://dali.jyoumei.cn/Article/details/gt2irnlmyoe.html

[T29] Swift：guard 提前返回
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wwvuknio.html

guard let x = opt else { return }
来源：http://dali.jyoumei.cn/Article/details/gt2juaiacak.html

[T30] Swift：协议
来源：http://dali.yj202588.top/Article/details/gt2awstkxtd.html

protocol Shape { func area() -> Double }
来源：http://dali.feifeiyinyue.top/Article/details/gt2temkmqmy.html

[T31] Lua：Hello World
来源：http://dali.svipenyu.cn/Article/details/gt2mygsimsv.html

print("Hello")
来源：http://dali.daxiang520.top/Article/details/gt2jblyczsb.html

[T32] Lua：局部变量
来源：http://dali.cqqwz.cn/Article/details/gt2ntitwwdo.html

local a = 1
来源：http://dali.gzhubu.top/Article/details/gt2ydnbxyrg.html

[T33] Lua：表（数组）
来源：http://dali.chenjidiqi.icu/Article/details/gt2mpksamsc.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.wangshuangyany.cn/Article/details/gt2qulpelqc.html

[T34] Lua：遍历表
来源：http://dali.ehwqpu.com/Article/details/gt2ufhdjiwf.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.gzhubu.top/Article/details/gt2pmwntmyn.html

[T35] Lua：字典表
来源：http://dali.birdmap.top/Article/details/gt2fgebsqvj.html

local d = { a = 1 };  d.b = 2
来源：http://dali.quarkkingdee.top/Article/details/gt2imqyohyh.html

[T36] Lua：函数
来源：http://dali.nanxinkj.top/Article/details/gt2kiohybuc.html

function add(a, b) return a + b end
来源：http://dali.xuetiantiany.cn/Article/details/gt2chqqnrnm.html

[T37] Lua：字符串拼接
来源：http://dali.guannengcc.top/Article/details/gt2dknzflno.html

"a" .. "b"
来源：http://dali.pengpengdd.cyou/Article/details/gt2zzdhgeep.html

[T38] Lua：条件
来源：http://dali.birdmap.top/Article/details/gt2vjryywrh.html

if x > 0 then print("正") end
来源：http://dali.xuetiantiany.cn/Article/details/gt2xrkhixsj.html

[T39] Lua：模式匹配
来源：http://dali.cucudq.cn/Article/details/gt2hgbnlfhc.html

string.find(s, "%d+")
来源：http://dali.tian-w.cn/Article/details/gt2yphpmgng.html

[T40] Lua：元表
来源：http://dali.jlsjyb.cn/Article/details/gt2jephmenb.html

setmetatable({}, { __index = base })
来源：http://dali.jqgfzy.top/Article/details/gt2yjolosiq.html


<!-- 参考信息 -->