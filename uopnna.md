代发 wailian999

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.cdnleiting.top/Article/details/gt2pbgfvtsz.html

[R30] 函数返回状态码
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2adwxzzvm.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.feifeiyinyue.top/Article/details/gt2hhkiymqp.html

[R31] 局部变量
来源：http://dali.nanxinkj.top/Article/details/gt2lqpkzffr.html

f() { local x=1; echo "$x"; }
来源：http://dali.jiagoushi.top/Article/details/gt2mrnjbsgg.html

[R32] 参数个数校验
来源：http://dali.0kj1m.cn/Article/details/gt2vnadqsid.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.svipenyu.cn/Article/details/gt2tlezjewn.html

[R33] 捕获错误并提示行号
来源：http://dali.fzhhl.top/Article/details/gt2mzomdbij.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.hysaishi.cn/Article/details/gt2dpojfhhc.html

[R34] 退出时清理
来源：http://dali.zhixingplan.top/Article/details/gt2vauwtujz.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.shzxlz.cn/Article/details/gt2zzmodoji.html

[R35] 后台执行并等待
来源：http://dali.xuanzx.com/Article/details/gt2cyvsckio.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.hnxiangtu.top/Article/details/gt2zshomepe.html

[R36] 并发执行多个任务
来源：http://dali.cheryme.top/Article/details/gt2wjwguywj.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.daxiang520.top/Article/details/gt2iehdjnxc.html

[R37] 把输出赋给变量
来源：http://dali.meibo888.top/Article/details/gt2zkzzjcos.html

files=$(ls -1)
来源：http://dali.cqqwz.cn/Article/details/gt2nwdmqzbw.html

[R38] 管道串联
来源：http://dali.gzhubu.top/Article/details/gt2fqhfzblj.html

cat a.txt | grep -i error | wc -l
来源：http://dali.pycfn.com/Article/details/gt2acdhpuvd.html

[R39] 重定向标准输出与错误
来源：http://dali.hywenlv.cn/Article/details/gt2ifzelizi.html

cmd > out.log 2>&1
来源：http://dali.zycfv.cn/Article/details/gt2tcyuofrx.html

[R40] 追加写日志
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tyyqfkro.html

echo "log" >> out.log
来源：http://dali.feifeiyinyue.top/Article/details/gt2vweszpra.html

[R41] 丢弃输出
来源：http://dali.yongpay.top/Article/details/gt2urftlafm.html

cmd >/dev/null 2>&1
来源：http://dali.jinqigfzy.top/Article/details/gt2ocnjmxzq.html

[R42] 输入重定向
来源：http://dali.sxryk.cn/Article/details/gt2eevgdqcc.html

wc -l < a.txt
来源：http://dali.gogol.net.cn/Article/details/gt2wigumcui.html

[R43] 按名字查找文件
来源：http://dali.tian-w.cn/Article/details/gt2tdwjvlar.html

find . -name "*.log" -type f
来源：http://dali.yuanzhike.top/Article/details/gt2vudrgter.html

[R44] 按修改时间查找
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lmvpasqy.html

find . -mtime -7 -type f
来源：http://dali.dianchejie.cn/Article/details/gt2uvhmyyog.html

[R45] 批量删除
来源：http://dali.xziqi.cn/Article/details/gt2gwucjuwv.html

find . -name "*.tmp" -delete
来源：http://dali.ybcxt.top/Article/details/gt2eodcnkqe.html

[R46] 递归替换文件内容
来源：http://dali.tianlin.xyz/Article/details/gt2jngqyzhe.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.hywenlv.cn/Article/details/gt2zqalweuq.html

[R47] sed 单行替换
来源：http://dali.ybcxt.top/Article/details/gt2xjjfzlaa.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.hfpthk.cn/Article/details/gt2ctcivcwf.html

[R48] awk 取指定列
来源：http://dali.zhoulong.xyz/Article/details/gt2efvobjtf.html

awk '{print $1, $3}' a.txt
来源：http://dali.yangfankeji.com/Article/details/gt2cackrqog.html

[R49] awk 带条件
来源：http://dali.sufxvd.cn/Article/details/gt2zwjlyvvv.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.gzhubu.top/Article/details/gt2ujynxvru.html

[R50] awk 求和
来源：http://dali.xylfe.cn/Article/details/gt2krxntyqs.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2teflswxi.html

[R51] 排序去重取前几
来源：http://dali.hongshengwenyu.top/Article/details/gt2ajkuucnj.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.yangfankeji.com/Article/details/gt2wwsfmltd.html

[R52] 统计行数
来源：http://dali.hnxiangtu.top/Article/details/gt2doabhjak.html

wc -l a.txt
来源：http://dali.yj20258.top/Article/details/gt2mzkmlhmm.html

[R53] 查看文件头与实时尾
来源：http://dali.daria6918.cn/Article/details/gt2kthkuepd.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.jianghu66.top/Article/details/gt2ftxaensx.html

[R54] 比较两个文件
来源：http://dali.chenjidiqi.icu/Article/details/gt2lxnznuav.html

diff a.txt b.txt
来源：http://dali.shzxlz.cn/Article/details/gt2wkfpxbxm.html

[R55] 压缩与解压
来源：http://dali.hnqzz.top/Article/details/gt2tpaobtdh.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.fengsongda.top/Article/details/gt2pomenwpl.html

[R56] 远程拷贝
来源：http://dali.cdnleiting.top/Article/details/gt2gllhuopy.html

scp file user@host:/path/
来源：http://dali.andypj.xyz/Article/details/gt2culqdumh.html

[R57] 远程执行命令
来源：http://dali.zhixingplan.top/Article/details/gt2cfggpnai.html

ssh user@host 'uptime'
来源：http://dali.xuetiantiany.cn/Article/details/gt2ayvyuzce.html

[R58] 下载文件
来源：http://dali.haohaochexian.top/Article/details/gt2gdaqmhlj.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.svipenyu.cn/Article/details/gt2enexdxzr.html

[R59] 发 POST JSON
来源：http://dali.ybcxt.top/Article/details/gt2dnzyluhr.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.svipenyu.cn/Article/details/gt2weqbavqr.html

[R60] 只看 HTTP 状态码
来源：http://dali.haohaochexian.top/Article/details/gt2xzgtofbf.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.shzxlz.cn/Article/details/gt2dxvmeqot.html

[R61] 磁盘占用
来源：http://dali.0kj1m.cn/Article/details/gt2iuwonbxl.html

df -h;  du -sh *
来源：http://dali.yanxiufei.cn/Article/details/gt2kmsatqlv.html

[R62] 找最占空间的文件
来源：http://dali.ybcxt.top/Article/details/gt2lcodsicg.html

du -ah . | sort -rh | head -10
来源：http://dali.pycfn.com/Article/details/gt2ybhjyxtz.html

[R63] 内存与进程
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ilezebji.html

free -h;  ps aux | grep nginx
来源：http://dali.9152youxi.cn/Article/details/gt2uacvrsyb.html

[R64] 结束进程
来源：http://dali.chenlongwang.top/Article/details/gt2cmbxzpnd.html

kill -9 $(pgrep -f app.py)
来源：http://dali.yuxming.cn/Article/details/gt2mcczecco.html

[R65] 查看端口占用
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vxmsvpng.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.aizwys.cn/Article/details/gt2qprfleeb.html

[R66] 定时任务
来源：http://dali.birdmap.top/Article/details/gt2hhqmkjfl.html

crontab -e;  crontab -l
来源：http://dali.zhiwuduotai.top/Article/details/gt2lhudzuba.html

[R67] 生成随机十六进制串
来源：http://dali.yuanzhike.top/Article/details/gt2smojyuve.html

openssl rand -hex 16
来源：http://dali.gotoacloud.top/Article/details/gt2mwcpxivg.html

[R68] 计算文件校验值
来源：http://dali.yongpay.top/Article/details/gt2quuqfbyw.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ytuufcit.html

[R69] 生成随机密码
来源：http://dali.ivvv.top/Article/details/gt2hzsuojpq.html

head -c 16 /dev/urandom | base64
来源：http://dali.pengpengdd.cyou/Article/details/gt2lpnsplwz.html

[R70] 时间戳与互转
来源：http://dali.meibo888.top/Article/details/gt2amyjqvcq.html

date +%s;  date -d @1700000000
来源：http://dali.jqgfzy.top/Article/details/gt2enemhacg.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2rhnpozrl.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhongyouzk.top/Article/details/gt2qjzvmjjn.html

[R72] 等待端口就绪
来源：http://dali.yj20258888.top/Article/details/gt2wctrajgg.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.jinqigufen.top/Article/details/gt2exxviasq.html

[R73] 分割大日志
来源：http://dali.xinyue.icu/Article/details/gt2hjfyueld.html

split -l 1000 big.log part_
来源：http://dali.feifeiyinyue.top/Article/details/gt2rlqutuuj.html

[R74] 批量重命名
来源：http://dali.pengpengdd.cyou/Article/details/gt2gqpwctsi.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.cdnleiting.top/Article/details/gt2zmxwacni.html

[R75] 导出环境变量
来源：http://dali.xziqi.cn/Article/details/gt2njbythlh.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.0kj1m.cn/Article/details/gt2zhbooxhp.html

[R76] 使用临时文件
来源：http://dali.mhx1999.top/Article/details/gt2inkozkzr.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.gaohongyu789.top/Article/details/gt2dsuzjfuk.html

[R77] 读取用户输入
来源：http://dali.ehwqpu.com/Article/details/gt2mlpuxlrc.html

read -rp "请输入: " ans
来源：http://dali.cdnleiting.top/Article/details/gt2sktyyuwf.html

[R78] 交互式菜单
来源：http://dali.mhx1999.top/Article/details/gt2prxhjpic.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.iojbl.cn/Article/details/gt2rwysndst.html

[R79] 解析命令行选项
来源：http://dali.snrcjt.cn/Article/details/gt2wmorbyxc.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.ybcxt.top/Article/details/gt2cdkihunq.html

[R80] 查看脚本执行耗时
来源：http://dali.yvedp.cn/Article/details/gt2dyssjfrh.html

time ./run.sh
来源：http://dali.cheryme.top/Article/details/gt2cyvrqjug.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gt2mbmeqkvp.html

S. C / C++ 专题
来源：http://dali.andypj.xyz/Article/details/gt2yjboyiga.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2aqyxyzsd.html

[S01] C：Hello World
来源：http://dali.iojbl.cn/Article/details/gt2nxnxinmz.html

#include <stdio.h>
来源：http://dali.hysaishi.cn/Article/details/gt2zjlahyvz.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.ydzc1.top/Article/details/gt2pqjwfvlm.html

[S02] C：变量与格式化输出
来源：http://dali.pycfn.com/Article/details/gt2acxnpymv.html

int a = 10; printf("%d\n", a);
来源：http://dali.pycfn.com/Article/details/gt2bzfymsxc.html

[S03] C：读入整数
来源：http://dali.aibaodan.cn/Article/details/gt2yghfpfvc.html

int x; scanf("%d", &x);
来源：http://dali.haohaochexian.top/Article/details/gt2ccvyojgo.html

[S04] C：字符串复制
来源：http://dali.quarkkingdee.top/Article/details/gt2glbpbdba.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.nanxinkj.top/Article/details/gt2lyrwkguf.html

[S05] C：字符串长度
来源：http://dali.tanke756.top/Article/details/gt2ifaukidv.html

strlen(s)
来源：http://dali.yj20258.top/Article/details/gt2jmuubcha.html

[S06] C：字符串比较
来源：http://dali.meibo888.top/Article/details/gt2wbllutpj.html

strcmp(a, b) == 0
来源：http://dali.tianlin.xyz/Article/details/gt2sqlrzojo.html

[S07] C：数组遍历求和
来源：http://dali.vqdsnc.cn/Article/details/gt2knpmpgdn.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mrohsogc.html

[S08] C：动态内存分配与释放
来源：http://dali.sweek.top/Article/details/gt2aqjuklpq.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.daria6918.cn/Article/details/gt2dtogbzmw.html

[S09] C：结构体定义与初始化
来源：http://dali.shzxlz.cn/Article/details/gt2rsgmlcce.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.chenzaomai.com/Article/details/gt2azgnzyca.html

[S10] C：指针与解引用
来源：http://dali.hnxiangtu.top/Article/details/gt2urjmzvfz.html

int *p = &a;  *p = 5;
来源：http://dali.snrcjt.cn/Article/details/gt2swgbtrsu.html

[S11] C：逐行读文件
来源：http://dali.jyoumei.cn/Article/details/gt2svykhtxb.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.guowangkeji.top/Article/details/gt2gdygwfon.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.ppjwa.cn/Article/details/gt2ifojxkvp.html

fclose(f);
来源：http://dali.meibo888.top/Article/details/gt2flykuecg.html

[S12] C：写文件
来源：http://dali.pycfn.com/Article/details/gt2vamyhnbs.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.ivvv.top/Article/details/gt2exmmgwhl.html

[S13] C：宏定义
来源：http://dali.xuanzx.com/Article/details/gt2yixirssm.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.xuanzx.com/Article/details/gt2oorwxyga.html

[S14] C：枚举
来源：http://dali.yangfankeji.com/Article/details/gt2xpwtgngl.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.yj20258888.top/Article/details/gt2wohyflxc.html

[S15] C：类型转换
来源：http://dali.sxryk.cn/Article/details/gt2ryxkqmjm.html

(double) a / b
来源：http://dali.sysykeji.top/Article/details/gt2ikkovsgw.html

[S16] C：位操作置位
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2haqlncyj.html

x |= (1 << 3);
来源：http://dali.wangshuangyany.cn/Article/details/gt2kcnygifv.html

[S17] C：安全拼接字符串
来源：http://dali.jqgufenzy.top/Article/details/gt2mcpvetbm.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.sxryk.cn/Article/details/gt2ghejdmqy.html

[S18] C：命令行参数
来源：http://dali.feifeiyinyue.top/Article/details/gt2exhqfbxt.html

int main(int argc, char **argv)
来源：http://dali.ivvv.top/Article/details/gt2vdhjwavm.html

[S19] C：快速排序
来源：http://dali.smart0.xyz/Article/details/gt2obbchpte.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.wangshuangyany.cn/Article/details/gt2fhjtghis.html

[S20] C：二分查找
来源：http://dali.fzhhl.top/Article/details/gt2saaneptn.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.mhx1999.top/Article/details/gt2gclvykcx.html

[S21] C：字符类别判断
来源：http://dali.tanke756.top/Article/details/gt2xzurqrir.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.iojbl.cn/Article/details/gt2oydfsvvj.html

[S22] C：字符串转数字
来源：http://dali.tianlin.xyz/Article/details/gt2spssyvbj.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.yueranfly.top/Article/details/gt2phftwxww.html

[S23] C：随机数
来源：http://dali.yvedp.cn/Article/details/gt2jfkpcwjx.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhixingplan.top/Article/details/gt2rgfygcut.html

[S24] C：获取本地时间
来源：http://dali.ybcxt.top/Article/details/gt2uxnkwely.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.nanxinkj.top/Article/details/gt2hwtjefod.html

[S25] C：内存拷贝
来源：http://dali.0kj1m.cn/Article/details/gt2rbawgrny.html

memcpy(dst, src, n);
来源：http://dali.c1oappe.top/Article/details/gt2jllgjhzz.html

[S26] C：内存清零
来源：http://dali.ehwqpu.com/Article/details/gt2tdmipdba.html

memset(a, 0, sizeof a);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jastbsmo.html

[S27] C：定义常量
来源：http://dali.jlsjyb.cn/Article/details/gt2ovohdbgv.html

const double PI = 3.14159;
来源：http://dali.yj20258.top/Article/details/gt2plguhucq.html

[S28] C：静态变量
来源：http://dali.cdnleiting.top/Article/details/gt2ghatfqor.html

static int counter = 0;
来源：http://dali.jlsjyb.cn/Article/details/gt2usbmilho.html

[S29] C：变参函数
来源：http://dali.hongshengwenyu.top/Article/details/gt2odrylkcr.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.nanxinkj.top/Article/details/gt2vlsmeaeb.html

[S30] C：头文件保护
来源：http://dali.cashguo.top/Article/details/gt2yrnqevyo.html

#ifndef X_H
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ciliywjo.html

#define X_H
来源：http://dali.snrcjt.cn/Article/details/gt2tmjlldjj.html

#endif
来源：http://dali.xuetiantiany.cn/Article/details/gt2cebhfgph.html

[S31] C++：Hello World
来源：http://dali.ehwqpu.com/Article/details/gt2fmnmlwup.html

#include <iostream>
来源：http://dali.sxryk.cn/Article/details/gt2oncaxabt.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2snhtwyhw.html

[S32] C++：字符串
来源：http://dali.dashuyun.cn/Article/details/gt2ytvlwgkm.html

std::string s = "hi";  s += "!";
来源：http://dali.feifeiyinyue.top/Article/details/gt2akiyxxfe.html

[S33] C++：vector 增删
来源：http://dali.shuidangran.top/Article/details/gt2xblzukpl.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.yonumen.top/Article/details/gt2awzncqsw.html

[S34] C++：遍历 vector
来源：http://dali.haohaochexian.top/Article/details/gt2axhlhaix.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2exfuowgw.html

[S35] C++：map
来源：http://dali.guannengcc.top/Article/details/gt2ivfqfomi.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.ivvv.top/Article/details/gt2sznhorap.html

[S36] C++：unordered_map
来源：http://dali.yuanzhike.top/Article/details/gt2xkqdrmnv.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.sysykeji.top/Article/details/gt2qonkglgt.html

[S37] C++：set
来源：http://dali.pengpengdd.cyou/Article/details/gt2fqmbbihb.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.yj20258.top/Article/details/gt2iymvgczl.html

[S38] C++：排序
来源：http://dali.jqgufenzy.top/Article/details/gt2bvdgtwot.html

std::sort(v.begin(), v.end());
来源：http://dali.ehwqpu.com/Article/details/gt2mpxrhtpu.html

[S39] C++：自定义比较器排序
来源：http://dali.xuetiantiany.cn/Article/details/gt2wwhlcymm.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.sysykeji.top/Article/details/gt2vwoehzdh.html

[S40] C++：查找元素
来源：http://dali.zhengqikj.top/Article/details/gt2qhluscro.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.yongpay.top/Article/details/gt2qtmzxmqk.html

[S41] C++：类与构造函数
来源：http://dali.hammf.cn/Article/details/gt2thoemcvl.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.dianchejie.cn/Article/details/gt2knlyutur.html

[S42] C++：继承与虚函数
来源：http://dali.jinqigufen.top/Article/details/gt2kixffatd.html

class B : public Base { public: void f() override {} };
来源：http://dali.xuetiantiany.cn/Article/details/gt2fqsytmrh.html

[S43] C++：智能指针
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2inkweqjv.html

auto p = std::make_unique<int>(5);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nogxynjr.html

[S44] C++：引用传参
来源：http://dali.shangyingyoupin.top/Article/details/gt2odpjouyd.html

void inc(int &x) { ++x; }
来源：http://dali.zycfv.cn/Article/details/gt2zjhyiyje.html

[S45] C++：lambda
来源：http://dali.pycfn.com/Article/details/gt2ipiqitkv.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.kuanghao11.cn/Article/details/gt2xidsfbiy.html

[S46] C++：函数模板
来源：http://dali.nwbrower.top/Article/details/gt2hppkghdx.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.hfpthk.cn/Article/details/gt2hvdzxtyx.html

[S47] C++：结构化绑定遍历
来源：http://dali.aizwys.cn/Article/details/gt2gkkvlelg.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.sufxvd.cn/Article/details/gt2jmemkrjf.html

[S48] C++：逐行读文件
来源：http://dali.guannengcc.top/Article/details/gt2ugypnupj.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.nanxuanxn.top/Article/details/gt2btcexfpj.html

while (std::getline(in, line)) { }
来源：http://dali.zycfv.cn/Article/details/gt2oomvxwfg.html

[S49] C++：写文件
来源：http://dali.gogol.net.cn/Article/details/gt2hteghwrz.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.hnxiangtu.top/Article/details/gt2rzkrzvos.html

[S50] C++：格式化数字
来源：http://dali.cheryme.top/Article/details/gt2ecpldxlw.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.yangfankeji.com/Article/details/gt2xlthfwac.html

[S51] C++：显式类型转换
来源：http://dali.daria6918.cn/Article/details/gt2rdelusii.html

static_cast<double>(a) / b
来源：http://dali.sysykeji.top/Article/details/gt2jeiathje.html

[S52] C++：const 与 noexcept
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ywmdsmcz.html

int size() const noexcept { return n_; }
来源：http://dali.snrcjt.cn/Article/details/gt2grlhfruj.html

[S53] C++：移动语义
来源：http://dali.havefunace.top/Article/details/gt2uhufvoog.html

std::vector<int> w = std::move(v);
来源：http://dali.zhixingplan.top/Article/details/gt2ryimrvtf.html

[S54] C++：异常处理
来源：http://dali.gaohongyu789.top/Article/details/gt2wlpmtdsr.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.cdnleiting.top/Article/details/gt2pmhxdnkz.html

[S55] C++：结构化绑定
来源：http://dali.fzhhl.top/Article/details/gt2jocxkhwq.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.ybcxt.top/Article/details/gt2sgpfqzfu.html

[S56] C++：optional
来源：http://dali.wangdashe.top/Article/details/gt2ufpderoa.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.iojbl.cn/Article/details/gt2oytchmhw.html

[S57] C++：编译期常量
来源：http://dali.andypj.xyz/Article/details/gt2oelddfdw.html

constexpr int N = 10;
来源：http://dali.fzhhl.top/Article/details/gt2pnwdekjg.html

[S58] C++：命名空间
来源：http://dali.mhx1999.top/Article/details/gt2ilcgykiu.html

namespace ns { int f() { return 1; } }
来源：http://dali.xuanzx.com/Article/details/gt2yyrdpxjb.html

[S59] C++：静态断言
来源：http://dali.chenzaomai.com/Article/details/gt2oziryqxd.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.xuanzx.com/Article/details/gt2gvtjiwgc.html

[S60] C++：遍历并删除元素
来源：http://dali.jyoumei.cn/Article/details/gt2yxcuslrp.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.xuanzx.com/Article/details/gt2yjgzysxl.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2xfreuhpx.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qkiczaqk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2blthtgwm.html

[T01] Kotlin：Hello World
来源：http://dali.zhiwuduotai.top/Article/details/gt2pymzaosv.html

println("Hello")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ppwfokaw.html

[T02] Kotlin：变量
来源：http://dali.andypj.xyz/Article/details/gt2trfltpeg.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.chenzaomai.com/Article/details/gt2kuxnubdn.html

[T03] Kotlin：字符串模板
来源：http://dali.zhoulong.xyz/Article/details/gt2fqsijsvi.html

"值: $b"
来源：http://dali.haohaochexian.top/Article/details/gt2hwwxtoyw.html

[T04] Kotlin：空安全
来源：http://dali.yj20258.top/Article/details/gt2gnvdbxhk.html

val n: String? = null;  n?.length
来源：http://dali.cucudq.cn/Article/details/gt2wkozlwqh.html

[T05] Kotlin：when 表达式
来源：http://dali.svipenyu.cn/Article/details/gt2udwvqdkj.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.havefunace.top/Article/details/gt2ugpcrgwi.html

[T06] Kotlin：集合映射
来源：http://dali.dianchejie.cn/Article/details/gt2whxiyzfp.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.hywenlv.cn/Article/details/gt2uxjmgbuh.html

[T07] Kotlin：集合过滤
来源：http://dali.zhongyouzk.top/Article/details/gt2odgezjub.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zycfv.cn/Article/details/gt2xqtyryhr.html

[T08] Kotlin：数据类
来源：http://dali.snrcjt.cn/Article/details/gt2tvfanjbw.html

data class User(val name: String, val age: Int)
来源：http://dali.mhx1999.top/Article/details/gt2hexciqmw.html

[T09] Kotlin：扩展函数
来源：http://dali.havefunace.top/Article/details/gt2lcydpgjy.html

fun String.exclaim() = this + "!"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pddsebax.html

[T10] Kotlin：默认参数
来源：http://dali.yuxming.cn/Article/details/gt2vhloysnu.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhoulong.xyz/Article/details/gt2ixihbkbx.html

[T11] Kotlin：协程
来源：http://dali.jqgufenzy.top/Article/details/gt2ujcyxcde.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.meibo888.top/Article/details/gt2tovnmyfp.html

[T12] Kotlin：解构声明
来源：http://dali.xziqi.cn/Article/details/gt2akaxhiei.html

val (a, b) = Pair(1, 2)
来源：http://dali.hywenlv.cn/Article/details/gt2olrqewki.html

[T13] Kotlin：只读 Map
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pbwvbqoc.html

val m = mapOf("a" to 1)
来源：http://dali.xziqi.cn/Article/details/gt2gxcrbdoc.html

[T14] Kotlin：循环
来源：http://dali.yueranfly.top/Article/details/gt2gwezbbgk.html

for (i in 1..10) println(i)
来源：http://dali.haohaochexian.top/Article/details/gt2xvchzxyc.html

[T15] Kotlin：接口
来源：http://dali.hywenlv.cn/Article/details/gt2kbpbscsw.html

interface Shape { fun area(): Double }
来源：http://dali.cucudq.cn/Article/details/gt2fexiaqki.html

[T16] Swift：Hello World
来源：http://dali.wangdashe.top/Article/details/gt2bgbpfdtr.html

print("Hello")
来源：http://dali.yonumen.top/Article/details/gt2cvryxwsz.html

[T17] Swift：变量与常量
来源：http://dali.iojbl.cn/Article/details/gt2hwoiwtbc.html

var a = 1;  let b = 2
来源：http://dali.jyoumei.cn/Article/details/gt2ctqfhrsp.html

[T18] Swift：字符串插值
来源：http://dali.fzhhl.top/Article/details/gt2qmewuaod.html

"值: \(b)"
来源：http://dali.aizwys.cn/Article/details/gt2wwrgcsab.html

[T19] Swift：可选绑定
来源：http://dali.zdqjudy.top/Article/details/gt2cpksibbu.html

if let n = opt { print(n) }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jjtkegpl.html

[T20] Swift：数组操作
来源：http://dali.ppjwa.cn/Article/details/gt2hasppnar.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.yj20258.top/Article/details/gt2tdkfxxsr.html

[T21] Swift：遍历
来源：http://dali.gzhubu.top/Article/details/gt2qkeksqug.html

for x in a { print(x) }
来源：http://dali.gotoacloud.top/Article/details/gt2httdfekw.html

[T22] Swift：字典
来源：http://dali.hywenlv.cn/Article/details/gt2bwtawcix.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.sweek.top/Article/details/gt2kgugnnlc.html

[T23] Swift：函数
来源：http://dali.yj202588.top/Article/details/gt2swkxjhfk.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.daria6918.cn/Article/details/gt2ahyputqz.html

[T24] Swift：闭包
来源：http://dali.pengpengdd.cyou/Article/details/gt2vytrwkfu.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.aizwys.cn/Article/details/gt2lxmfihqt.html

[T25] Swift：结构体
来源：http://dali.aibaodan.cn/Article/details/gt2odwoxrac.html

struct P { var x: Int }
来源：http://dali.hfpthk.cn/Article/details/gt2hvmglxxl.html

[T26] Swift：类与重写
来源：http://dali.ydzc1.top/Article/details/gt2fzstxwsz.html

class A: Base { override func f() {} }
来源：http://dali.cheryme.top/Article/details/gt2wzbafwao.html

[T27] Swift：错误处理
来源：http://dali.jqgfzy.top/Article/details/gt2jwlkfusu.html

do { try f() } catch { print(error) }
来源：http://dali.jlsjyb.cn/Article/details/gt2ewxiuitj.html

[T28] Swift：枚举
来源：http://dali.aibaodan.cn/Article/details/gt2cgtbkswg.html

enum Color { case red, green }
来源：http://dali.svipenyu.cn/Article/details/gt2mnkfwvay.html

[T29] Swift：guard 提前返回
来源：http://dali.ppjwa.cn/Article/details/gt2sekfqcbc.html

guard let x = opt else { return }
来源：http://dali.yongpay.top/Article/details/gt2czqbhqij.html

[T30] Swift：协议
来源：http://dali.yj202588.top/Article/details/gt2ktnnbuoj.html

protocol Shape { func area() -> Double }
来源：http://dali.fengsongda.top/Article/details/gt2cgyetkbc.html

[T31] Lua：Hello World
来源：http://dali.cashguo.top/Article/details/gt2reujxfha.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2hmpegtfa.html

[T32] Lua：局部变量
来源：http://dali.aibaodan.cn/Article/details/gt2qvlteqlc.html

local a = 1
来源：http://dali.snrcjt.cn/Article/details/gt2hihcdhkf.html


<!-- 参考信息 -->