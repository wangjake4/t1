代发 wailian999

echo "${#s}"
来源：http://dali.tian-w.cn/Article/details/gt2wiogydyc.html

[R22] 截取子串
来源：http://dali.yonumen.top/Article/details/gt2lflgzydc.html

echo "${s:0:5}"
来源：http://dali.9152youxi.cn/Article/details/gt2sznbqpee.html

[R23] 字符串替换
来源：http://dali.hnxiangtu.top/Article/details/gt2dbxpyjuf.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.ivvv.top/Article/details/gt2cgnxjnxy.html

[R24] 大小写转换
来源：http://dali.iojbl.cn/Article/details/gt2wtldnqji.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.sufxvd.cn/Article/details/gt2kbgslyyu.html

[R25] 去后缀 / 去前缀
来源：http://dali.nwbrower.top/Article/details/gt2ktjsysob.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.yonumen.top/Article/details/gt2pyufoxlo.html

[R26] 命令替换
来源：http://dali.nanxinkj.top/Article/details/gt2nmkuoqrm.html

now=$(date +%F); echo "$now"
来源：http://dali.cdnleiting.top/Article/details/gt2jisosbdj.html

[R27] 算术展开
来源：http://dali.gotoacloud.top/Article/details/gt2zrhpzonh.html

echo $((1 + 2 * 3))
来源：http://dali.redwolf501.top/Article/details/gt2ipgfcwxq.html

[R28] 浮点运算
来源：http://dali.chenjidiqi.icu/Article/details/gt2daclsdql.html

echo "scale=2; 10/3" | bc
来源：http://dali.nanxinkj.top/Article/details/gt2kbnowjqj.html

[R29] 定义函数
来源：http://dali.chenjidiqi.icu/Article/details/gt2rzjdbuaa.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.aibaodan.cn/Article/details/gt2uiugkumi.html

[R30] 函数返回状态码
来源：http://dali.guowangkeji.top/Article/details/gt2bgvkklrg.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.xuetiantiany.cn/Article/details/gt2clskthqn.html

[R31] 局部变量
来源：http://dali.ydzc1.top/Article/details/gt2rdkdbvth.html

f() { local x=1; echo "$x"; }
来源：http://dali.haohaochexian.top/Article/details/gt2crlvwquw.html

[R32] 参数个数校验
来源：http://dali.shuidangran.top/Article/details/gt2hlrzanff.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.quarkkingdee.top/Article/details/gt2jqfszxji.html

[R33] 捕获错误并提示行号
来源：http://dali.hnxiangtu.top/Article/details/gt2hednozgt.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.aizwys.cn/Article/details/gt2hgddhgkp.html

[R34] 退出时清理
来源：http://dali.chenjidiqi.icu/Article/details/gt2hndfpqkz.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.wangdashe.top/Article/details/gt2zptzjgsc.html

[R35] 后台执行并等待
来源：http://dali.zdqjudy.top/Article/details/gt2sfgqwngr.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.shuidangran.top/Article/details/gt2kabqljlv.html

[R36] 并发执行多个任务
来源：http://dali.aizwys.cn/Article/details/gt2tmkdowxv.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.tianlin.xyz/Article/details/gt2cmgvlfer.html

[R37] 把输出赋给变量
来源：http://dali.jyoumei.cn/Article/details/gt2qcxqwqte.html

files=$(ls -1)
来源：http://dali.yuanzhike.top/Article/details/gt2xqamowue.html

[R38] 管道串联
来源：http://dali.cheryme.top/Article/details/gt2baiddpwa.html

cat a.txt | grep -i error | wc -l
来源：http://dali.aizwys.cn/Article/details/gt2rhvthena.html

[R39] 重定向标准输出与错误
来源：http://dali.chenzaomai.com/Article/details/gt2ppazndca.html

cmd > out.log 2>&1
来源：http://dali.yuxming.cn/Article/details/gt2drysjikg.html

[R40] 追加写日志
来源：http://dali.cdnleiting.top/Article/details/gt2cafeoukf.html

echo "log" >> out.log
来源：http://dali.hnxiangtu.top/Article/details/gt2xluoevbt.html

[R41] 丢弃输出
来源：http://dali.yanxiufei.cn/Article/details/gt2amxsetnw.html

cmd >/dev/null 2>&1
来源：http://dali.yuxming.cn/Article/details/gt2awwgbwco.html

[R42] 输入重定向
来源：http://dali.feifeiyinyue.top/Article/details/gt2myvlucro.html

wc -l < a.txt
来源：http://dali.jlsjyb.cn/Article/details/gt2tdmjohjv.html

[R43] 按名字查找文件
来源：http://dali.zhiwuduotai.top/Article/details/gt2abtixiqv.html

find . -name "*.log" -type f
来源：http://dali.feifeiyinyue.top/Article/details/gt2ddgzmdnw.html

[R44] 按修改时间查找
来源：http://dali.jinqigufen.top/Article/details/gt2rkedaapf.html

find . -mtime -7 -type f
来源：http://dali.sysykeji.top/Article/details/gt2qrphabte.html

[R45] 批量删除
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lcywkuhy.html

find . -name "*.tmp" -delete
来源：http://dali.redwolf501.top/Article/details/gt2gpbkxmyr.html

[R46] 递归替换文件内容
来源：http://dali.hammf.cn/Article/details/gt2imjcavjd.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2sjmurjkm.html

[R47] sed 单行替换
来源：http://dali.smart0.xyz/Article/details/gt2smrsacwz.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.snrcjt.cn/Article/details/gt2qculnkbn.html

[R48] awk 取指定列
来源：http://dali.hnxiangtu.top/Article/details/gt2cilmxivn.html

awk '{print $1, $3}' a.txt
来源：http://dali.gogol.net.cn/Article/details/gt2qpzgyrht.html

[R49] awk 带条件
来源：http://dali.jlsjyb.cn/Article/details/gt2buaepmve.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.9152youxi.cn/Article/details/gt2gufxugfi.html

[R50] awk 求和
来源：http://dali.zhongyouzk.top/Article/details/gt2llfdtymc.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.quarkkingdee.top/Article/details/gt2uoxrwibj.html

[R51] 排序去重取前几
来源：http://dali.wangshuangyany.cn/Article/details/gt2lirzuwre.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.hnqzz.top/Article/details/gt2grmhftny.html

[R52] 统计行数
来源：http://dali.xinyue.icu/Article/details/gt2ckqovhru.html

wc -l a.txt
来源：http://dali.zdqjudy.top/Article/details/gt2fikgvfwx.html

[R53] 查看文件头与实时尾
来源：http://dali.chenzaomai.com/Article/details/gt2mdpokric.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zycfv.cn/Article/details/gt2alfagsrd.html

[R54] 比较两个文件
来源：http://dali.meibo888.top/Article/details/gt2cvqjfopq.html

diff a.txt b.txt
来源：http://dali.aizwys.cn/Article/details/gt2jsmselhb.html

[R55] 压缩与解压
来源：http://dali.tanke756.top/Article/details/gt2siyldwqe.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.jiagoushi.top/Article/details/gt2zpylazuf.html

[R56] 远程拷贝
来源：http://dali.xziqi.cn/Article/details/gt2ghwohmjq.html

scp file user@host:/path/
来源：http://dali.cqqwz.cn/Article/details/gt2rxmkfcof.html

[R57] 远程执行命令
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qsyxqjuj.html

ssh user@host 'uptime'
来源：http://dali.chenzaomai.com/Article/details/gt2oyiwxsga.html

[R58] 下载文件
来源：http://dali.xuanzx.com/Article/details/gt2lsvofngl.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.dianchejie.cn/Article/details/gt2smjqiwlp.html

[R59] 发 POST JSON
来源：http://dali.wangdashe.top/Article/details/gt2bgvocmtz.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.jiagoushi.top/Article/details/gt2xroczfga.html

[R60] 只看 HTTP 状态码
来源：http://dali.dianchejie.cn/Article/details/gt2pdskoffo.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.quarkkingdee.top/Article/details/gt2yagndwkq.html

[R61] 磁盘占用
来源：http://dali.jianghu66.top/Article/details/gt2bzkatfyn.html

df -h;  du -sh *
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2msqhkgpz.html

[R62] 找最占空间的文件
来源：http://dali.gzhubu.top/Article/details/gt2skhtksps.html

du -ah . | sort -rh | head -10
来源：http://dali.xylfe.cn/Article/details/gt2bnucggrl.html

[R63] 内存与进程
来源：http://dali.daxiang520.top/Article/details/gt2eoaxdrho.html

free -h;  ps aux | grep nginx
来源：http://dali.zhoulong.xyz/Article/details/gt2wolflpwy.html

[R64] 结束进程
来源：http://dali.sweek.top/Article/details/gt2jviduerq.html

kill -9 $(pgrep -f app.py)
来源：http://dali.birdmap.top/Article/details/gt2nkeuxkig.html

[R65] 查看端口占用
来源：http://dali.yongpay.top/Article/details/gt2jrvkhddn.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.dianchejie.cn/Article/details/gt2twlnxpdo.html

[R66] 定时任务
来源：http://dali.jianghu66.top/Article/details/gt2xnsktihq.html

crontab -e;  crontab -l
来源：http://dali.cucudq.cn/Article/details/gt2ncdtqlka.html

[R67] 生成随机十六进制串
来源：http://dali.cashguo.top/Article/details/gt2zqiginrx.html

openssl rand -hex 16
来源：http://dali.yj20258888.top/Article/details/gt2jleysvry.html

[R68] 计算文件校验值
来源：http://dali.zhixingplan.top/Article/details/gt2jcdfsnfl.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.316326.xyz/Article/details/gt2povzoygm.html

[R69] 生成随机密码
来源：http://dali.ydzc1.top/Article/details/gt2yvrhvlbx.html

head -c 16 /dev/urandom | base64
来源：http://dali.jinqigfzy.top/Article/details/gt2aefacxau.html

[R70] 时间戳与互转
来源：http://dali.tianlin.xyz/Article/details/gt2eambczix.html

date +%s;  date -d @1700000000
来源：http://dali.sweek.top/Article/details/gt2hblxogyg.html

[R71] 日期格式化
来源：http://dali.zhiwuduotai.top/Article/details/gt2xfucnana.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.vqdsnc.cn/Article/details/gt2zteelqdp.html

[R72] 等待端口就绪
来源：http://dali.yuanzhike.top/Article/details/gt2lcggcidb.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.ybcxt.top/Article/details/gt2ytpaipkf.html

[R73] 分割大日志
来源：http://dali.zdqjudy.top/Article/details/gt2xwsxbbmr.html

split -l 1000 big.log part_
来源：http://dali.zhongyouzk.top/Article/details/gt2hcfqrwrh.html

[R74] 批量重命名
来源：http://dali.shuidangran.top/Article/details/gt2usbirrff.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.cqqwz.cn/Article/details/gt2plgcehcb.html

[R75] 导出环境变量
来源：http://dali.jianghu66.top/Article/details/gt2uqpauqfx.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.haohaochexian.top/Article/details/gt2srxykmho.html

[R76] 使用临时文件
来源：http://dali.0kj1m.cn/Article/details/gt2rrufwsub.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nthpatzr.html

[R77] 读取用户输入
来源：http://dali.cashguo.top/Article/details/gt2gvogaufu.html

read -rp "请输入: " ans
来源：http://dali.cqqwz.cn/Article/details/gt2cvmdeyjt.html

[R78] 交互式菜单
来源：http://dali.gotoacloud.top/Article/details/gt2suclrsml.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.ivvv.top/Article/details/gt2xyranhjx.html

[R79] 解析命令行选项
来源：http://dali.gaohongyu789.top/Article/details/gt2lzmzmdpk.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.ppjwa.cn/Article/details/gt2wudqaxfp.html

[R80] 查看脚本执行耗时
来源：http://dali.sweek.top/Article/details/gt2kjlrevxz.html

time ./run.sh
来源：http://dali.yonumen.top/Article/details/gt2jslaukfm.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2cxoehrug.html

S. C / C++ 专题
来源：http://dali.ybcxt.top/Article/details/gt2cerlpgmv.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gt2rlwgppem.html

[S01] C：Hello World
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wgpmsafa.html

#include <stdio.h>
来源：http://dali.pycfn.com/Article/details/gt2zxaukyqj.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.daria6918.cn/Article/details/gt2cthujsvf.html

[S02] C：变量与格式化输出
来源：http://dali.daria6918.cn/Article/details/gt2qofjdozv.html

int a = 10; printf("%d\n", a);
来源：http://dali.yonumen.top/Article/details/gt2wcrksqpb.html

[S03] C：读入整数
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2votxhniw.html

int x; scanf("%d", &x);
来源：http://dali.dianchejie.cn/Article/details/gt2mnnviwji.html

[S04] C：字符串复制
来源：http://dali.ybcxt.top/Article/details/gt2fgqjftml.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.bjfxy.top/Article/details/gt2wgwkbixf.html

[S05] C：字符串长度
来源：http://dali.gotoacloud.top/Article/details/gt2vjcsrvrm.html

strlen(s)
来源：http://dali.nanxuanxn.top/Article/details/gt2roevvfdv.html

[S06] C：字符串比较
来源：http://dali.zhixingplan.top/Article/details/gt2uulwzzzf.html

strcmp(a, b) == 0
来源：http://dali.sxryk.cn/Article/details/gt2pxncdnej.html

[S07] C：数组遍历求和
来源：http://dali.tian-w.cn/Article/details/gt2yjsipeld.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zdqjudy.top/Article/details/gt2lmhcogpz.html

[S08] C：动态内存分配与释放
来源：http://dali.mhx1999.top/Article/details/gt2cydajaxi.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.tanke756.top/Article/details/gt2llvsqdpj.html

[S09] C：结构体定义与初始化
来源：http://dali.ehwqpu.com/Article/details/gt2scfyyxgu.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.quarkkingdee.top/Article/details/gt2vivtccto.html

[S10] C：指针与解引用
来源：http://dali.xziqi.cn/Article/details/gt2gtzbgmrf.html

int *p = &a;  *p = 5;
来源：http://dali.yuanzhike.top/Article/details/gt2wcpovrne.html

[S11] C：逐行读文件
来源：http://dali.9152youxi.cn/Article/details/gt2rwjuzith.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.nwbrower.top/Article/details/gt2unsnsjhm.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.hnqzz.top/Article/details/gt2jpowfzhf.html

fclose(f);
来源：http://dali.fzhhl.top/Article/details/gt2nyptngnl.html

[S12] C：写文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ifxcaodo.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhoulong.xyz/Article/details/gt2tcbjqrsi.html

[S13] C：宏定义
来源：http://dali.ydzc1.top/Article/details/gt2mmkpjpti.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.tanke756.top/Article/details/gt2cfcikvur.html

[S14] C：枚举
来源：http://dali.hysaishi.cn/Article/details/gt2ndoxwvvh.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.guowangkeji.top/Article/details/gt2zcdwowtx.html

[S15] C：类型转换
来源：http://dali.ppjwa.cn/Article/details/gt2smpxgbsu.html

(double) a / b
来源：http://dali.yvedp.cn/Article/details/gt2guzlsxoy.html

[S16] C：位操作置位
来源：http://dali.tianlin.xyz/Article/details/gt2mgwtsqym.html

x |= (1 << 3);
来源：http://dali.jiagoushi.top/Article/details/gt2prnmktxc.html

[S17] C：安全拼接字符串
来源：http://dali.jqgfzy.top/Article/details/gt2jovwqnwc.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.pengpengdd.cyou/Article/details/gt2dlfbtnbc.html

[S18] C：命令行参数
来源：http://dali.gzhubu.top/Article/details/gt2dugpbmyj.html

int main(int argc, char **argv)
来源：http://dali.fzhhl.top/Article/details/gt2ygdbbisl.html

[S19] C：快速排序
来源：http://dali.yueranfly.top/Article/details/gt2qsjgtnvv.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.xylfe.cn/Article/details/gt2lcaxrfiq.html

[S20] C：二分查找
来源：http://dali.aizwys.cn/Article/details/gt2guaekbnw.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.fengsongda.top/Article/details/gt2kruszlul.html

[S21] C：字符类别判断
来源：http://dali.sweek.top/Article/details/gt2jppffbdl.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.hnxiangtu.top/Article/details/gt2yagwmydz.html

[S22] C：字符串转数字
来源：http://dali.yangfankeji.com/Article/details/gt2ostkezku.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.meibo888.top/Article/details/gt2wtjiampm.html

[S23] C：随机数
来源：http://dali.iojbl.cn/Article/details/gt2wbwiaacc.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhiwuduotai.top/Article/details/gt2wzjbprvi.html

[S24] C：获取本地时间
来源：http://dali.zycfv.cn/Article/details/gt2bigpupeu.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.xinyue.icu/Article/details/gt2iuvnzzxa.html

[S25] C：内存拷贝
来源：http://dali.yj202588.top/Article/details/gt2jzfrivih.html

memcpy(dst, src, n);
来源：http://dali.316326.xyz/Article/details/gt2lpavlnhw.html

[S26] C：内存清零
来源：http://dali.yuxming.cn/Article/details/gt2skgsalin.html

memset(a, 0, sizeof a);
来源：http://dali.jiagoushi.top/Article/details/gt2wygogkae.html

[S27] C：定义常量
来源：http://dali.cashguo.top/Article/details/gt2bmwpgvjh.html

const double PI = 3.14159;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tytozubm.html

[S28] C：静态变量
来源：http://dali.ivvv.top/Article/details/gt2tscwjsjo.html

static int counter = 0;
来源：http://dali.guowangkeji.top/Article/details/gt2jmvccskj.html

[S29] C：变参函数
来源：http://dali.tanke756.top/Article/details/gt2kfojnshf.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.guannengcc.top/Article/details/gt2giyhtcsl.html

[S30] C：头文件保护
来源：http://dali.cqqwz.cn/Article/details/gt2uchncybc.html

#ifndef X_H
来源：http://dali.feifeiyinyue.top/Article/details/gt2zvhktxjt.html

#define X_H
来源：http://dali.chenzaomai.com/Article/details/gt2llrhvsht.html

#endif
来源：http://dali.9152youxi.cn/Article/details/gt2nfgzuvjr.html

[S31] C++：Hello World
来源：http://dali.pengpengdd.cyou/Article/details/gt2gjqfuvay.html

#include <iostream>
来源：http://dali.xuanzx.com/Article/details/gt2giuxmxxg.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.tianlin.xyz/Article/details/gt2ppojfojd.html

[S32] C++：字符串
来源：http://dali.chenjidiqi.icu/Article/details/gt2yzolyluq.html

std::string s = "hi";  s += "!";
来源：http://dali.tianlin.xyz/Article/details/gt2pdfvcgqi.html

[S33] C++：vector 增删
来源：http://dali.cucudq.cn/Article/details/gt2jxvqyxrn.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.havefunace.top/Article/details/gt2ocdaogyp.html

[S34] C++：遍历 vector
来源：http://dali.andypj.xyz/Article/details/gt2bedyprfa.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zdqjudy.top/Article/details/gt2wjigjkha.html

[S35] C++：map
来源：http://dali.jlsjyb.cn/Article/details/gt2llkyraba.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.cucudq.cn/Article/details/gt2esqxyxyi.html

[S36] C++：unordered_map
来源：http://dali.0kj1m.cn/Article/details/gt2twgpwvnr.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.9152youxi.cn/Article/details/gt2zututjxi.html

[S37] C++：set
来源：http://dali.sufxvd.cn/Article/details/gt2irvttkwr.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.316326.xyz/Article/details/gt2uxjcotls.html

[S38] C++：排序
来源：http://dali.sysykeji.top/Article/details/gt2ziskahdi.html

std::sort(v.begin(), v.end());
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tfjkhqfr.html

[S39] C++：自定义比较器排序
来源：http://dali.cucudq.cn/Article/details/gt2vwtbmpge.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.pengpengdd.cyou/Article/details/gt2jedsvxbz.html

[S40] C++：查找元素
来源：http://dali.pycfn.com/Article/details/gt2wakepteb.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.shangyingyoupin.top/Article/details/gt2soixjlpo.html

[S41] C++：类与构造函数
来源：http://dali.shzxlz.cn/Article/details/gt2rnmfctna.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.ydzc1.top/Article/details/gt2ftihmwlu.html

[S42] C++：继承与虚函数
来源：http://dali.pengpengdd.cyou/Article/details/gt2rbtruiyg.html

class B : public Base { public: void f() override {} };
来源：http://dali.kuanghao11.cn/Article/details/gt2krvdexwj.html

[S43] C++：智能指针
来源：http://dali.shuidangran.top/Article/details/gt2avpkweyf.html

auto p = std::make_unique<int>(5);
来源：http://dali.gaohongyu789.top/Article/details/gt2vjfpaprr.html

[S44] C++：引用传参
来源：http://dali.haohaochexian.top/Article/details/gt2jerrcpqp.html

void inc(int &x) { ++x; }
来源：http://dali.yuxming.cn/Article/details/gt2ihnfqrdq.html

[S45] C++：lambda
来源：http://dali.sufxvd.cn/Article/details/gt2zakplovl.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.hywenlv.cn/Article/details/gt2ojvureki.html

[S46] C++：函数模板
来源：http://dali.tian-w.cn/Article/details/gt2almtnair.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yrxhmwqv.html

[S47] C++：结构化绑定遍历
来源：http://dali.shangyingyoupin.top/Article/details/gt2nzssdevy.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.xinyue.icu/Article/details/gt2ucnzzqtg.html

[S48] C++：逐行读文件
来源：http://dali.vqdsnc.cn/Article/details/gt2gqyrmfdi.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.yangfankeji.com/Article/details/gt2ltahpjaf.html

while (std::getline(in, line)) { }
来源：http://dali.yvedp.cn/Article/details/gt2hgjmesyq.html

[S49] C++：写文件
来源：http://dali.aizwys.cn/Article/details/gt2qdkfqnkf.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.shzxlz.cn/Article/details/gt2nxbamuhv.html

[S50] C++：格式化数字
来源：http://dali.chenjidiqi.icu/Article/details/gt2fkuxaceh.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhiwuduotai.top/Article/details/gt2twhuagji.html

[S51] C++：显式类型转换
来源：http://dali.chenjidiqi.icu/Article/details/gt2bneinwlb.html

static_cast<double>(a) / b
来源：http://dali.gotoacloud.top/Article/details/gt2brgveewm.html

[S52] C++：const 与 noexcept
来源：http://dali.dashuyun.cn/Article/details/gt2fumriltk.html

int size() const noexcept { return n_; }
来源：http://dali.aibaodan.cn/Article/details/gt2jishvkuj.html

[S53] C++：移动语义
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lheodfbq.html

std::vector<int> w = std::move(v);
来源：http://dali.gogol.net.cn/Article/details/gt2lssqtvcw.html

[S54] C++：异常处理
来源：http://dali.hammf.cn/Article/details/gt2xjgktlzv.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhengqikj.top/Article/details/gt2emsjaifs.html

[S55] C++：结构化绑定
来源：http://dali.mhx1999.top/Article/details/gt2txsbktyv.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.daxiang520.top/Article/details/gt2bqavnian.html

[S56] C++：optional
来源：http://dali.shuidangran.top/Article/details/gt2vjeyqsnn.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.andypj.xyz/Article/details/gt2yaqlhbjy.html

[S57] C++：编译期常量
来源：http://dali.c1oappe.top/Article/details/gt2iwfykgih.html

constexpr int N = 10;
来源：http://dali.snrcjt.cn/Article/details/gt2zjnzcups.html

[S58] C++：命名空间
来源：http://dali.shangyingyoupin.top/Article/details/gt2dnvhloky.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhoulong.xyz/Article/details/gt2snpbvedr.html

[S59] C++：静态断言
来源：http://dali.xylfe.cn/Article/details/gt2vfqidfkh.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.316326.xyz/Article/details/gt2nwejnldt.html

[S60] C++：遍历并删除元素
来源：http://dali.nanxinkj.top/Article/details/gt2ppwfruxd.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.ehwqpu.com/Article/details/gt2mvsvtazh.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2vzvfbpdm.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.hnxiangtu.top/Article/details/gt2wvjfxppw.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fgmliwfe.html

[T01] Kotlin：Hello World
来源：http://dali.zhongyouzk.top/Article/details/gt2mzuuozzj.html

println("Hello")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2srfohcdj.html

[T02] Kotlin：变量
来源：http://dali.svipenyu.cn/Article/details/gt2erumhnbx.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lbnzlfnu.html

[T03] Kotlin：字符串模板
来源：http://dali.snrcjt.cn/Article/details/gt2rocqomyq.html

"值: $b"
来源：http://dali.zycfv.cn/Article/details/gt2hawcozvn.html

[T04] Kotlin：空安全
来源：http://dali.snrcjt.cn/Article/details/gt2ervbxbqu.html

val n: String? = null;  n?.length
来源：http://dali.gogol.net.cn/Article/details/gt2atfdotft.html

[T05] Kotlin：when 表达式
来源：http://dali.haohaochexian.top/Article/details/gt2szpxinjo.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.jinqigfzy.top/Article/details/gt2sgzxkhaf.html

[T06] Kotlin：集合映射
来源：http://dali.cqqwz.cn/Article/details/gt2gufkbrss.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhongyouzk.top/Article/details/gt2agnqnizk.html

[T07] Kotlin：集合过滤
来源：http://dali.pengpengdd.cyou/Article/details/gt2oncqwgek.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.c1oappe.top/Article/details/gt2yiqflfny.html

[T08] Kotlin：数据类
来源：http://dali.xuetiantiany.cn/Article/details/gt2ezralreg.html

data class User(val name: String, val age: Int)
来源：http://dali.xziqi.cn/Article/details/gt2flyxiedl.html

[T09] Kotlin：扩展函数
来源：http://dali.dianchejie.cn/Article/details/gt2vjhlwkog.html

fun String.exclaim() = this + "!"
来源：http://dali.gogol.net.cn/Article/details/gt2dseiovld.html

[T10] Kotlin：默认参数
来源：http://dali.0kj1m.cn/Article/details/gt2lfbwwczl.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.haohaochexian.top/Article/details/gt2hqkkxmrx.html

[T11] Kotlin：协程
来源：http://dali.daria6918.cn/Article/details/gt2dntcdebu.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.cashguo.top/Article/details/gt2xhyubpxy.html

[T12] Kotlin：解构声明
来源：http://dali.hywenlv.cn/Article/details/gt2ydpalups.html

val (a, b) = Pair(1, 2)
来源：http://dali.smart0.xyz/Article/details/gt2ispxlazw.html

[T13] Kotlin：只读 Map
来源：http://dali.ehwqpu.com/Article/details/gt2jgzvdxam.html

val m = mapOf("a" to 1)
来源：http://dali.wangshuangyany.cn/Article/details/gt2wdlkhqdj.html

[T14] Kotlin：循环
来源：http://dali.cheryme.top/Article/details/gt2uufrdtcs.html

for (i in 1..10) println(i)
来源：http://dali.pengpengdd.cyou/Article/details/gt2lpanevxq.html

[T15] Kotlin：接口
来源：http://dali.yonumen.top/Article/details/gt2djqiewgz.html

interface Shape { fun area(): Double }
来源：http://dali.smart0.xyz/Article/details/gt2cehfehxu.html

[T16] Swift：Hello World
来源：http://dali.yvedp.cn/Article/details/gt2llgindky.html

print("Hello")
来源：http://dali.hongshengwenyu.top/Article/details/gt2fixkvjiw.html

[T17] Swift：变量与常量
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gxxhcgfh.html

var a = 1;  let b = 2
来源：http://dali.yj202588.top/Article/details/gt2rqvknagz.html

[T18] Swift：字符串插值
来源：http://dali.nanxuanxn.top/Article/details/gt2urwrdltr.html

"值: \(b)"
来源：http://dali.jinqigufen.top/Article/details/gt2wayuwjas.html

[T19] Swift：可选绑定
来源：http://dali.daria6918.cn/Article/details/gt2epbmosgb.html

if let n = opt { print(n) }
来源：http://dali.gogol.net.cn/Article/details/gt2ppnphozu.html

[T20] Swift：数组操作
来源：http://dali.xinyue.icu/Article/details/gt2hllgszjf.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.yvedp.cn/Article/details/gt2pmvuhquj.html

[T21] Swift：遍历
来源：http://dali.yanxiufei.cn/Article/details/gt2etrrsnol.html

for x in a { print(x) }
来源：http://dali.svipenyu.cn/Article/details/gt2ciopfsmy.html

[T22] Swift：字典
来源：http://dali.hongshengwenyu.top/Article/details/gt2ddsykgug.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.feifeiyinyue.top/Article/details/gt2umfeotem.html

[T23] Swift：函数
来源：http://dali.yuanzhike.top/Article/details/gt2guzpeizf.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.bjfxy.top/Article/details/gt2hejxgdtw.html

[T24] Swift：闭包
来源：http://dali.chenlongwang.top/Article/details/gt2omlewiyh.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zycfv.cn/Article/details/gt2vapdienw.html


<!-- 参考信息 -->