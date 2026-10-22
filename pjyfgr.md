代发 wailian999

echo $((1 + 2 * 3))
来源：http://dali.andypj.xyz/Article/details/gt2qmliswgw.html

[R28] 浮点运算
来源：http://dali.nanxuanxn.top/Article/details/gt2zrhclcnc.html

echo "scale=2; 10/3" | bc
来源：http://dali.birdmap.top/Article/details/gt2ghspjjtt.html

[R29] 定义函数
来源：http://dali.cashguo.top/Article/details/gt2ejknocca.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vztxijhx.html

[R30] 函数返回状态码
来源：http://dali.sufxvd.cn/Article/details/gt2abfxorms.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.ydzc1.top/Article/details/gt2rcvfgxva.html

[R31] 局部变量
来源：http://dali.chenjidiqi.icu/Article/details/gt2nfxznxaw.html

f() { local x=1; echo "$x"; }
来源：http://dali.cucudq.cn/Article/details/gt2tlpadxze.html

[R32] 参数个数校验
来源：http://dali.xinyue.icu/Article/details/gt2jdakaqmm.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.shzxlz.cn/Article/details/gt2ygbjbrde.html

[R33] 捕获错误并提示行号
来源：http://dali.zhoulong.xyz/Article/details/gt2stfuwxqm.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.chenlongwang.top/Article/details/gt2xszyumsn.html

[R34] 退出时清理
来源：http://dali.xziqi.cn/Article/details/gt2dqehwfvu.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.daria6918.cn/Article/details/gt2cuscmgid.html

[R35] 后台执行并等待
来源：http://dali.fengsongda.top/Article/details/gt2psoiniui.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gmvktpgf.html

[R36] 并发执行多个任务
来源：http://dali.gzhubu.top/Article/details/gt2czqvmamj.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.jqgfzy.top/Article/details/gt2wtxsmefs.html

[R37] 把输出赋给变量
来源：http://dali.yanxiufei.cn/Article/details/gt2lpwbaljl.html

files=$(ls -1)
来源：http://dali.iojbl.cn/Article/details/gt2alogcasl.html

[R38] 管道串联
来源：http://dali.havefunace.top/Article/details/gt2xxzwzjyt.html

cat a.txt | grep -i error | wc -l
来源：http://dali.chenjidiqi.icu/Article/details/gt2xricjpzq.html

[R39] 重定向标准输出与错误
来源：http://dali.tian-w.cn/Article/details/gt2ycxyonud.html

cmd > out.log 2>&1
来源：http://dali.jqgufenzy.top/Article/details/gt2iowfynes.html

[R40] 追加写日志
来源：http://dali.guannengcc.top/Article/details/gt2cuqexcfs.html

echo "log" >> out.log
来源：http://dali.316326.xyz/Article/details/gt2nrrabjsy.html

[R41] 丢弃输出
来源：http://dali.hywenlv.cn/Article/details/gt2otraqwac.html

cmd >/dev/null 2>&1
来源：http://dali.jyoumei.cn/Article/details/gt2sziwwhgp.html

[R42] 输入重定向
来源：http://dali.xinyue.icu/Article/details/gt2kmnodlcq.html

wc -l < a.txt
来源：http://dali.gaohongyu789.top/Article/details/gt2secgzgin.html

[R43] 按名字查找文件
来源：http://dali.hongshengwenyu.top/Article/details/gt2ilcksrtw.html

find . -name "*.log" -type f
来源：http://dali.ybcxt.top/Article/details/gt2flcgswns.html

[R44] 按修改时间查找
来源：http://dali.cheryme.top/Article/details/gt2jpqcksgx.html

find . -mtime -7 -type f
来源：http://dali.yj202588.top/Article/details/gt2cjoakvkf.html

[R45] 批量删除
来源：http://dali.guannengcc.top/Article/details/gt2matibhdh.html

find . -name "*.tmp" -delete
来源：http://dali.snrcjt.cn/Article/details/gt2xrsgzsls.html

[R46] 递归替换文件内容
来源：http://dali.svipenyu.cn/Article/details/gt2pvyrcmgg.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.fengsongda.top/Article/details/gt2ovpvecuc.html

[R47] sed 单行替换
来源：http://dali.haohaochexian.top/Article/details/gt2joiwbjiq.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.jqgufenzy.top/Article/details/gt2yzllvxll.html

[R48] awk 取指定列
来源：http://dali.hnxiangtu.top/Article/details/gt2nkldlqom.html

awk '{print $1, $3}' a.txt
来源：http://dali.sxryk.cn/Article/details/gt2mojydftk.html

[R49] awk 带条件
来源：http://dali.shzxlz.cn/Article/details/gt2rdbajvug.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.cucudq.cn/Article/details/gt2ifrvkmow.html

[R50] awk 求和
来源：http://dali.jqgfzy.top/Article/details/gt2oevefwxb.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.tianlin.xyz/Article/details/gt2jdzrihfe.html

[R51] 排序去重取前几
来源：http://dali.cucudq.cn/Article/details/gt2onuamkjo.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.yangfankeji.com/Article/details/gt2wmrtsgwb.html

[R52] 统计行数
来源：http://dali.ehwqpu.com/Article/details/gt2izdkvptp.html

wc -l a.txt
来源：http://dali.hongshengwenyu.top/Article/details/gt2fcyzifep.html

[R53] 查看文件头与实时尾
来源：http://dali.pycfn.com/Article/details/gt2ounutxbv.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2avheklgo.html

[R54] 比较两个文件
来源：http://dali.cdnleiting.top/Article/details/gt2rgnlzdkg.html

diff a.txt b.txt
来源：http://dali.dashuyun.cn/Article/details/gt2gnyegbcd.html

[R55] 压缩与解压
来源：http://dali.chenlongwang.top/Article/details/gt2kejbdrmf.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.yuanzhike.top/Article/details/gt2uhyxtfzd.html

[R56] 远程拷贝
来源：http://dali.mhx1999.top/Article/details/gt2hnkupyvk.html

scp file user@host:/path/
来源：http://dali.sweek.top/Article/details/gt2yghsbtde.html

[R57] 远程执行命令
来源：http://dali.hfpthk.cn/Article/details/gt2bbodivlm.html

ssh user@host 'uptime'
来源：http://dali.sysykeji.top/Article/details/gt2ufirvovb.html

[R58] 下载文件
来源：http://dali.fengsongda.top/Article/details/gt2vldqtldf.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.daxiang520.top/Article/details/gt2cpnaxzov.html

[R59] 发 POST JSON
来源：http://dali.aizwys.cn/Article/details/gt2umlmpzvj.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.yj202588.top/Article/details/gt2zerhyrrs.html

[R60] 只看 HTTP 状态码
来源：http://dali.xuetiantiany.cn/Article/details/gt2svnbrrnu.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.ppjwa.cn/Article/details/gt2wdhblspy.html

[R61] 磁盘占用
来源：http://dali.andypj.xyz/Article/details/gt2gbsziotm.html

df -h;  du -sh *
来源：http://dali.hywenlv.cn/Article/details/gt2idfwbcvy.html

[R62] 找最占空间的文件
来源：http://dali.shangyingyoupin.top/Article/details/gt2mokygrus.html

du -ah . | sort -rh | head -10
来源：http://dali.feifeiyinyue.top/Article/details/gt2vvrwnzpg.html

[R63] 内存与进程
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fqwwoawn.html

free -h;  ps aux | grep nginx
来源：http://dali.shangyingyoupin.top/Article/details/gt2rphbcrqe.html

[R64] 结束进程
来源：http://dali.zdqjudy.top/Article/details/gt2wlxnxdyi.html

kill -9 $(pgrep -f app.py)
来源：http://dali.bjfxy.top/Article/details/gt2gjjudhkp.html

[R65] 查看端口占用
来源：http://dali.jlsjyb.cn/Article/details/gt2mnilhdeg.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.daria6918.cn/Article/details/gt2wulhwphj.html

[R66] 定时任务
来源：http://dali.shangyingyoupin.top/Article/details/gt2iddysisu.html

crontab -e;  crontab -l
来源：http://dali.havefunace.top/Article/details/gt2suloqqey.html

[R67] 生成随机十六进制串
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mmvocqlk.html

openssl rand -hex 16
来源：http://dali.hywenlv.cn/Article/details/gt2umdhpwxz.html

[R68] 计算文件校验值
来源：http://dali.yongpay.top/Article/details/gt2fqudskpi.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.hongshengwenyu.top/Article/details/gt2piuwkisg.html

[R69] 生成随机密码
来源：http://dali.ivvv.top/Article/details/gt2xkawzvmq.html

head -c 16 /dev/urandom | base64
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2eknysxwa.html

[R70] 时间戳与互转
来源：http://dali.yuanzhike.top/Article/details/gt2sejdfzvv.html

date +%s;  date -d @1700000000
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xmtxibvz.html

[R71] 日期格式化
来源：http://dali.zhongyouzk.top/Article/details/gt2ueifjior.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.fzhhl.top/Article/details/gt2tishfvph.html

[R72] 等待端口就绪
来源：http://dali.vqdsnc.cn/Article/details/gt2vfymrfew.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.xuetiantiany.cn/Article/details/gt2opifhrbr.html

[R73] 分割大日志
来源：http://dali.shzxlz.cn/Article/details/gt2xribionf.html

split -l 1000 big.log part_
来源：http://dali.cheryme.top/Article/details/gt2csnccwyz.html

[R74] 批量重命名
来源：http://dali.jiagoushi.top/Article/details/gt2bgkvtrul.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.tian-w.cn/Article/details/gt2kiqovswc.html

[R75] 导出环境变量
来源：http://dali.aizwys.cn/Article/details/gt2xsonqjkh.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.nanxuanxn.top/Article/details/gt2mpxpzevy.html

[R76] 使用临时文件
来源：http://dali.c1oappe.top/Article/details/gt2utodiyoi.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhoulong.xyz/Article/details/gt2ckxvcgjr.html

[R77] 读取用户输入
来源：http://dali.jianghu66.top/Article/details/gt2kygmhdfw.html

read -rp "请输入: " ans
来源：http://dali.tanke756.top/Article/details/gt2wbmjqqrw.html

[R78] 交互式菜单
来源：http://dali.birdmap.top/Article/details/gt2fptaztuj.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.cdnleiting.top/Article/details/gt2bhfxprkp.html

[R79] 解析命令行选项
来源：http://dali.chenzaomai.com/Article/details/gt2wkdwdphn.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.yuxming.cn/Article/details/gt2hzynvinb.html

[R80] 查看脚本执行耗时
来源：http://dali.cucudq.cn/Article/details/gt2rcspljjs.html

time ./run.sh
来源：http://dali.yj20258.top/Article/details/gt2nhdcxjzq.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2lfkwkmtj.html

S. C / C++ 专题
来源：http://dali.guowangkeji.top/Article/details/gt2tuyyncdq.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2rlijrzps.html

[S01] C：Hello World
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vvdvzlni.html

#include <stdio.h>
来源：http://dali.zhongyouzk.top/Article/details/gt2cmnfhxpm.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.gaohongyu789.top/Article/details/gt2zgzgswsz.html

[S02] C：变量与格式化输出
来源：http://dali.yangfankeji.com/Article/details/gt2hrccatde.html

int a = 10; printf("%d\n", a);
来源：http://dali.ivvv.top/Article/details/gt2lgktgzdr.html

[S03] C：读入整数
来源：http://dali.cashguo.top/Article/details/gt2ecaaznas.html

int x; scanf("%d", &x);
来源：http://dali.wangdashe.top/Article/details/gt2ylcnpybr.html

[S04] C：字符串复制
来源：http://dali.0kj1m.cn/Article/details/gt2nmkilynd.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.aizwys.cn/Article/details/gt2xezuwtrr.html

[S05] C：字符串长度
来源：http://dali.chenlongwang.top/Article/details/gt2fmqmgguk.html

strlen(s)
来源：http://dali.hywenlv.cn/Article/details/gt2iwualnag.html

[S06] C：字符串比较
来源：http://dali.ppjwa.cn/Article/details/gt2nfahrxca.html

strcmp(a, b) == 0
来源：http://dali.guowangkeji.top/Article/details/gt2ewvyexhr.html

[S07] C：数组遍历求和
来源：http://dali.ppjwa.cn/Article/details/gt2cgcwoubq.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.yongpay.top/Article/details/gt2jyhklwsf.html

[S08] C：动态内存分配与释放
来源：http://dali.gotoacloud.top/Article/details/gt2uxtqdllu.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.nwbrower.top/Article/details/gt2afolvbqo.html

[S09] C：结构体定义与初始化
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jdwygowp.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.shuidangran.top/Article/details/gt2clobcvsp.html

[S10] C：指针与解引用
来源：http://dali.kuanghao11.cn/Article/details/gt2eyqjfsjk.html

int *p = &a;  *p = 5;
来源：http://dali.yj20258888.top/Article/details/gt2arjtwlao.html

[S11] C：逐行读文件
来源：http://dali.jinqigufen.top/Article/details/gt2kuzkhypo.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.havefunace.top/Article/details/gt2bitrkgii.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.jyoumei.cn/Article/details/gt2alkwtjgo.html

fclose(f);
来源：http://dali.sxryk.cn/Article/details/gt2lnmvgvsc.html

[S12] C：写文件
来源：http://dali.jinqigfzy.top/Article/details/gt2laarabea.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.cqqwz.cn/Article/details/gt2tpsxlcjl.html

[S13] C：宏定义
来源：http://dali.dashuyun.cn/Article/details/gt2zpnaztrg.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.shangyingyoupin.top/Article/details/gt2almjwhtv.html

[S14] C：枚举
来源：http://dali.yj20258.top/Article/details/gt2xcsgoxqy.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.ivvv.top/Article/details/gt2wfjdvntv.html

[S15] C：类型转换
来源：http://dali.jyoumei.cn/Article/details/gt2qftdsmen.html

(double) a / b
来源：http://dali.jiagoushi.top/Article/details/gt2ngxtntds.html

[S16] C：位操作置位
来源：http://dali.ehwqpu.com/Article/details/gt2hodqrhkg.html

x |= (1 << 3);
来源：http://dali.dashuyun.cn/Article/details/gt2gpwgbgkw.html

[S17] C：安全拼接字符串
来源：http://dali.pengpengdd.cyou/Article/details/gt2citlpjbm.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.andypj.xyz/Article/details/gt2xtpeefrd.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2wltgdnxr.html

int main(int argc, char **argv)
来源：http://dali.gotoacloud.top/Article/details/gt2gtogmgjd.html

[S19] C：快速排序
来源：http://dali.zhiwuduotai.top/Article/details/gt2cgzhwgdt.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zdqjudy.top/Article/details/gt2moqwmlnv.html

[S20] C：二分查找
来源：http://dali.jiagoushi.top/Article/details/gt2huizlyqm.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.chenzaomai.com/Article/details/gt2zzfozoll.html

[S21] C：字符类别判断
来源：http://dali.tanke756.top/Article/details/gt2worerzbk.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lekfpwpj.html

[S22] C：字符串转数字
来源：http://dali.yuanzhike.top/Article/details/gt2mrqmrvdf.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zdqjudy.top/Article/details/gt2kvuvqvbz.html

[S23] C：随机数
来源：http://dali.jiagoushi.top/Article/details/gt2mvfgvqok.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.jyoumei.cn/Article/details/gt2zxebgene.html

[S24] C：获取本地时间
来源：http://dali.jlsjyb.cn/Article/details/gt2aedqrfli.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.hnxiangtu.top/Article/details/gt2dvuhvsvp.html

[S25] C：内存拷贝
来源：http://dali.chenlongwang.top/Article/details/gt2dafcygfd.html

memcpy(dst, src, n);
来源：http://dali.zhongyouzk.top/Article/details/gt2uizoyeyp.html

[S26] C：内存清零
来源：http://dali.yvedp.cn/Article/details/gt2brwatpdt.html

memset(a, 0, sizeof a);
来源：http://dali.chenzaomai.com/Article/details/gt2rgndsvgo.html

[S27] C：定义常量
来源：http://dali.yueranfly.top/Article/details/gt2giiucltu.html

const double PI = 3.14159;
来源：http://dali.snrcjt.cn/Article/details/gt2ngoecufm.html

[S28] C：静态变量
来源：http://dali.zycfv.cn/Article/details/gt2dbqpfcok.html

static int counter = 0;
来源：http://dali.zhengqikj.top/Article/details/gt2eausbpbj.html

[S29] C：变参函数
来源：http://dali.zhoulong.xyz/Article/details/gt2yjpedivi.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.sxryk.cn/Article/details/gt2lklphtru.html

[S30] C：头文件保护
来源：http://dali.jyoumei.cn/Article/details/gt2uconqnbv.html

#ifndef X_H
来源：http://dali.bjfxy.top/Article/details/gt2sfuhzwpo.html

#define X_H
来源：http://dali.quarkkingdee.top/Article/details/gt2izqlwwzw.html

#endif
来源：http://dali.yueranfly.top/Article/details/gt2onyhjyce.html

[S31] C++：Hello World
来源：http://dali.gotoacloud.top/Article/details/gt2mviokbzb.html

#include <iostream>
来源：http://dali.jqgufenzy.top/Article/details/gt2kvfohwfq.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.kuanghao11.cn/Article/details/gt2slcnacjx.html

[S32] C++：字符串
来源：http://dali.yueranfly.top/Article/details/gt2wscvuyvg.html

std::string s = "hi";  s += "!";
来源：http://dali.hywenlv.cn/Article/details/gt2ovctmwmx.html

[S33] C++：vector 增删
来源：http://dali.zdqjudy.top/Article/details/gt2jgejfphq.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.sweek.top/Article/details/gt2srtbrlsr.html

[S34] C++：遍历 vector
来源：http://dali.cqqwz.cn/Article/details/gt2uippyycm.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.xuanzx.com/Article/details/gt2lffxxhzq.html

[S35] C++：map
来源：http://dali.chenjidiqi.icu/Article/details/gt2govtglps.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.pycfn.com/Article/details/gt2pgbdawjq.html

[S36] C++：unordered_map
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cwxedwvs.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.aibaodan.cn/Article/details/gt2zawogffx.html

[S37] C++：set
来源：http://dali.ppjwa.cn/Article/details/gt2fgrnzhoe.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.aibaodan.cn/Article/details/gt2kansjcgs.html

[S38] C++：排序
来源：http://dali.kuanghao11.cn/Article/details/gt2nysvevxw.html

std::sort(v.begin(), v.end());
来源：http://dali.yj202588.top/Article/details/gt2lzmxtzgf.html

[S39] C++：自定义比较器排序
来源：http://dali.snrcjt.cn/Article/details/gt2fztchxkk.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.chenjidiqi.icu/Article/details/gt2wdzwirtx.html

[S40] C++：查找元素
来源：http://dali.aizwys.cn/Article/details/gt2umxrxzjx.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.cucudq.cn/Article/details/gt2eevbaunn.html

[S41] C++：类与构造函数
来源：http://dali.daria6918.cn/Article/details/gt2nugavtji.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.xinyue.icu/Article/details/gt2wmumgklg.html

[S42] C++：继承与虚函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wzoguqlq.html

class B : public Base { public: void f() override {} };
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zzswaads.html

[S43] C++：智能指针
来源：http://dali.iojbl.cn/Article/details/gt2xtijysxs.html

auto p = std::make_unique<int>(5);
来源：http://dali.sweek.top/Article/details/gt2kzpnzuyc.html

[S44] C++：引用传参
来源：http://dali.xuanzx.com/Article/details/gt2wwxwtqmu.html

void inc(int &x) { ++x; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kchwcltp.html

[S45] C++：lambda
来源：http://dali.cashguo.top/Article/details/gt2jnkzulpw.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhongyouzk.top/Article/details/gt2dgqhsslg.html

[S46] C++：函数模板
来源：http://dali.fengsongda.top/Article/details/gt2ghvhasdq.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.daria6918.cn/Article/details/gt2zgrzsomq.html

[S47] C++：结构化绑定遍历
来源：http://dali.tian-w.cn/Article/details/gt2fmcoutcf.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2qhjeidwy.html

[S48] C++：逐行读文件
来源：http://dali.zycfv.cn/Article/details/gt2cudskqwf.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.chenzaomai.com/Article/details/gt2prnpauaz.html

while (std::getline(in, line)) { }
来源：http://dali.aizwys.cn/Article/details/gt2fmrgwlqy.html

[S49] C++：写文件
来源：http://dali.daria6918.cn/Article/details/gt2zusuasoz.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.tanke756.top/Article/details/gt2bbavtufi.html

[S50] C++：格式化数字
来源：http://dali.sysykeji.top/Article/details/gt2xkuatffc.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.yongpay.top/Article/details/gt2dzghqupx.html

[S51] C++：显式类型转换
来源：http://dali.sysykeji.top/Article/details/gt2fnqvmppb.html

static_cast<double>(a) / b
来源：http://dali.zhiwuduotai.top/Article/details/gt2dafxbfwv.html

[S52] C++：const 与 noexcept
来源：http://dali.hnxiangtu.top/Article/details/gt2fauixyyd.html

int size() const noexcept { return n_; }
来源：http://dali.jinqigufen.top/Article/details/gt2cfpjytrq.html

[S53] C++：移动语义
来源：http://dali.yuxming.cn/Article/details/gt2hicxecvp.html

std::vector<int> w = std::move(v);
来源：http://dali.chenlongwang.top/Article/details/gt2ddtofygv.html

[S54] C++：异常处理
来源：http://dali.gogol.net.cn/Article/details/gt2xvhuwivz.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.xuanzx.com/Article/details/gt2kustcwfk.html

[S55] C++：结构化绑定
来源：http://dali.cdnleiting.top/Article/details/gt2tihdpvnx.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.yonumen.top/Article/details/gt2cmgodkmr.html

[S56] C++：optional
来源：http://dali.316326.xyz/Article/details/gt2apntxvxz.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.jiagoushi.top/Article/details/gt2aewfakap.html

[S57] C++：编译期常量
来源：http://dali.vqdsnc.cn/Article/details/gt2uwywefhv.html

constexpr int N = 10;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2icseohfr.html

[S58] C++：命名空间
来源：http://dali.xinyue.icu/Article/details/gt2wmnxsgsc.html

namespace ns { int f() { return 1; } }
来源：http://dali.xuanzx.com/Article/details/gt2hdcqtgdl.html

[S59] C++：静态断言
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zfonvsma.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.aizwys.cn/Article/details/gt2vprbvxio.html

[S60] C++：遍历并删除元素
来源：http://dali.svipenyu.cn/Article/details/gt2hirmkdsr.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.haohaochexian.top/Article/details/gt2lbpfmkcl.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gt2wlhvwamw.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.smart0.xyz/Article/details/gt2knrqspth.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2frjnyaok.html

[T01] Kotlin：Hello World
来源：http://dali.yongpay.top/Article/details/gt2tlqdqmws.html

println("Hello")
来源：http://dali.quarkkingdee.top/Article/details/gt2vrmsnvdc.html

[T02] Kotlin：变量
来源：http://dali.jqgfzy.top/Article/details/gt2zikirivz.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.jqgfzy.top/Article/details/gt2amqsyvun.html

[T03] Kotlin：字符串模板
来源：http://dali.tanke756.top/Article/details/gt2vduaevrw.html

"值: $b"
来源：http://dali.aibaodan.cn/Article/details/gt2bpuualda.html

[T04] Kotlin：空安全
来源：http://dali.xziqi.cn/Article/details/gt2lfpqykln.html

val n: String? = null;  n?.length
来源：http://dali.birdmap.top/Article/details/gt2ypeqabct.html

[T05] Kotlin：when 表达式
来源：http://dali.svipenyu.cn/Article/details/gt2cjturjvm.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.shuidangran.top/Article/details/gt2swbfatom.html

[T06] Kotlin：集合映射
来源：http://dali.gzhubu.top/Article/details/gt2ohjjpyoo.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.316326.xyz/Article/details/gt2rbhewwol.html

[T07] Kotlin：集合过滤
来源：http://dali.cqqwz.cn/Article/details/gt2jwwspmjh.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.jqgufenzy.top/Article/details/gt2pzvxmmro.html

[T08] Kotlin：数据类
来源：http://dali.yvedp.cn/Article/details/gt2gwslaoyy.html

data class User(val name: String, val age: Int)
来源：http://dali.gaohongyu789.top/Article/details/gt2ahnrjvha.html

[T09] Kotlin：扩展函数
来源：http://dali.ppjwa.cn/Article/details/gt2halgkrch.html

fun String.exclaim() = this + "!"
来源：http://dali.vqdsnc.cn/Article/details/gt2aggfzlaq.html

[T10] Kotlin：默认参数
来源：http://dali.sxryk.cn/Article/details/gt2ixoexuzt.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.redwolf501.top/Article/details/gt2dhdgnakv.html

[T11] Kotlin：协程
来源：http://dali.cheryme.top/Article/details/gt2basgeezv.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.ivvv.top/Article/details/gt2wtrliafb.html

[T12] Kotlin：解构声明
来源：http://dali.zycfv.cn/Article/details/gt2miqzkjjp.html

val (a, b) = Pair(1, 2)
来源：http://dali.meibo888.top/Article/details/gt2zrdeknkk.html

[T13] Kotlin：只读 Map
来源：http://dali.haohaochexian.top/Article/details/gt2npgftmip.html

val m = mapOf("a" to 1)
来源：http://dali.iojbl.cn/Article/details/gt2bnoznkhq.html

[T14] Kotlin：循环
来源：http://dali.kuanghao11.cn/Article/details/gt2qntksmbq.html

for (i in 1..10) println(i)
来源：http://dali.sysykeji.top/Article/details/gt2fjzqhiek.html

[T15] Kotlin：接口
来源：http://dali.vqdsnc.cn/Article/details/gt2mzgyzpki.html

interface Shape { fun area(): Double }
来源：http://dali.meibo888.top/Article/details/gt2ohgboqyo.html

[T16] Swift：Hello World
来源：http://dali.aizwys.cn/Article/details/gt2pczxstig.html

print("Hello")
来源：http://dali.zhongyouzk.top/Article/details/gt2lvldzqmc.html

[T17] Swift：变量与常量
来源：http://dali.yonumen.top/Article/details/gt2szjpkdmi.html

var a = 1;  let b = 2
来源：http://dali.zhixingplan.top/Article/details/gt2vyhtepcy.html

[T18] Swift：字符串插值
来源：http://dali.haohaochexian.top/Article/details/gt2dfwandcx.html

"值: \(b)"
来源：http://dali.tian-w.cn/Article/details/gt2jxiknesr.html

[T19] Swift：可选绑定
来源：http://dali.sweek.top/Article/details/gt2ukwtmpra.html

if let n = opt { print(n) }
来源：http://dali.sxryk.cn/Article/details/gt2xxdbdisu.html

[T20] Swift：数组操作
来源：http://dali.hongshengwenyu.top/Article/details/gt2veqixgit.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.chenzaomai.com/Article/details/gt2bqfiytff.html

[T21] Swift：遍历
来源：http://dali.jlsjyb.cn/Article/details/gt2ggaotzll.html

for x in a { print(x) }
来源：http://dali.yongpay.top/Article/details/gt2dulxzyjb.html

[T22] Swift：字典
来源：http://dali.shanyushiyangtech.top/Article/details/gt2asjtgbkl.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.aizwys.cn/Article/details/gt2faceyfcp.html

[T23] Swift：函数
来源：http://dali.jianghu66.top/Article/details/gt2edjbetxj.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.shangyingyoupin.top/Article/details/gt2njogqylw.html

[T24] Swift：闭包
来源：http://dali.jlsjyb.cn/Article/details/gt2yrjuaaoh.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.ydzc1.top/Article/details/gt2zppudkrn.html

[T25] Swift：结构体
来源：http://dali.sufxvd.cn/Article/details/gt2quksqstx.html

struct P { var x: Int }
来源：http://dali.zdqjudy.top/Article/details/gt2otoorzsw.html

[T26] Swift：类与重写
来源：http://dali.jinqigufen.top/Article/details/gt2lgcquvak.html

class A: Base { override func f() {} }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sriocvmk.html

[T27] Swift：错误处理
来源：http://dali.9152youxi.cn/Article/details/gt2ncfagcwe.html

do { try f() } catch { print(error) }
来源：http://dali.sufxvd.cn/Article/details/gt2nwupergp.html

[T28] Swift：枚举
来源：http://dali.cdnleiting.top/Article/details/gt2jlyvwfia.html

enum Color { case red, green }
来源：http://dali.xylfe.cn/Article/details/gt2ewzsfizl.html

[T29] Swift：guard 提前返回
来源：http://dali.chenjidiqi.icu/Article/details/gt2twtozrfu.html

guard let x = opt else { return }
来源：http://dali.yj20258.top/Article/details/gt2vdzkmnes.html

[T30] Swift：协议
来源：http://dali.ehwqpu.com/Article/details/gt2odzgmkxl.html

protocol Shape { func area() -> Double }
来源：http://dali.0kj1m.cn/Article/details/gt2pscwhkie.html


<!-- 参考信息 -->