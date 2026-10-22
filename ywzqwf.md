代发 wailian999

echo "${#arr[@]}"
来源：http://dali.nwbrower.top/Article/details/gt2nwkqgrqo.html

[R20] 关联数组（字典）
来源：http://dali.cucudq.cn/Article/details/gt2ncisqump.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhengqikj.top/Article/details/gt2zpsctpos.html

[R21] 字符串长度
来源：http://dali.yonumen.top/Article/details/gt2kfxeddpp.html

echo "${#s}"
来源：http://dali.yj202588.top/Article/details/gt2ckjmopkd.html

[R22] 截取子串
来源：http://dali.xylfe.cn/Article/details/gt2kfojgyfq.html

echo "${s:0:5}"
来源：http://dali.zhixingplan.top/Article/details/gt2okknzjiy.html

[R23] 字符串替换
来源：http://dali.xuanzx.com/Article/details/gt2rfnxbizi.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.xuanzx.com/Article/details/gt2zgowgsvh.html

[R24] 大小写转换
来源：http://dali.9152youxi.cn/Article/details/gt2eexmanbr.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.andypj.xyz/Article/details/gt2bjfwoecq.html

[R25] 去后缀 / 去前缀
来源：http://dali.mhx1999.top/Article/details/gt2fqszdtlu.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.yueranfly.top/Article/details/gt2bqgrpxzh.html

[R26] 命令替换
来源：http://dali.c1oappe.top/Article/details/gt2qkunuknj.html

now=$(date +%F); echo "$now"
来源：http://dali.daxiang520.top/Article/details/gt2zlfolklj.html

[R27] 算术展开
来源：http://dali.jyoumei.cn/Article/details/gt2zwaezdhi.html

echo $((1 + 2 * 3))
来源：http://dali.bjfxy.top/Article/details/gt2mzqnjupn.html

[R28] 浮点运算
来源：http://dali.chenlongwang.top/Article/details/gt2festyivv.html

echo "scale=2; 10/3" | bc
来源：http://dali.aizwys.cn/Article/details/gt2xnsmcpzb.html

[R29] 定义函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hpiegowb.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.wangdashe.top/Article/details/gt2cnioilpu.html

[R30] 函数返回状态码
来源：http://dali.sufxvd.cn/Article/details/gt2qwcpjyfg.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.meibo888.top/Article/details/gt2qktrpjnl.html

[R31] 局部变量
来源：http://dali.gogol.net.cn/Article/details/gt2viwdfkdw.html

f() { local x=1; echo "$x"; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2advhpjnk.html

[R32] 参数个数校验
来源：http://dali.jianghu66.top/Article/details/gt2jroxxast.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.jiagoushi.top/Article/details/gt2fazhfqkx.html

[R33] 捕获错误并提示行号
来源：http://dali.dashuyun.cn/Article/details/gt2icdtjiiq.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.shuidangran.top/Article/details/gt2xunkrctq.html

[R34] 退出时清理
来源：http://dali.sxryk.cn/Article/details/gt2xcnqcdyy.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.dianchejie.cn/Article/details/gt2herzxinj.html

[R35] 后台执行并等待
来源：http://dali.hongshengwenyu.top/Article/details/gt2elcqjlbf.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.pengpengdd.cyou/Article/details/gt2ucdzxhfv.html

[R36] 并发执行多个任务
来源：http://dali.zhiwuduotai.top/Article/details/gt2diwmympa.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.meibo888.top/Article/details/gt2onvzcbhj.html

[R37] 把输出赋给变量
来源：http://dali.shuidangran.top/Article/details/gt2gfwdgdqq.html

files=$(ls -1)
来源：http://dali.shuidangran.top/Article/details/gt2txkgjkdj.html

[R38] 管道串联
来源：http://dali.kuanghao11.cn/Article/details/gt2agomjswc.html

cat a.txt | grep -i error | wc -l
来源：http://dali.jyoumei.cn/Article/details/gt2yxczwhax.html

[R39] 重定向标准输出与错误
来源：http://dali.zhongyouzk.top/Article/details/gt2dxuoddvf.html

cmd > out.log 2>&1
来源：http://dali.fzhhl.top/Article/details/gt2qgjuuftm.html

[R40] 追加写日志
来源：http://dali.wangdashe.top/Article/details/gt2mzutgmrn.html

echo "log" >> out.log
来源：http://dali.xinyue.icu/Article/details/gt2jrpfnvor.html

[R41] 丢弃输出
来源：http://dali.iojbl.cn/Article/details/gt2aqqkpnme.html

cmd >/dev/null 2>&1
来源：http://dali.sysykeji.top/Article/details/gt2vpnyeski.html

[R42] 输入重定向
来源：http://dali.fengsongda.top/Article/details/gt2qrvktaes.html

wc -l < a.txt
来源：http://dali.dianchejie.cn/Article/details/gt2nmrnkhbe.html

[R43] 按名字查找文件
来源：http://dali.wangshuangyany.cn/Article/details/gt2fervqava.html

find . -name "*.log" -type f
来源：http://dali.snrcjt.cn/Article/details/gt2jfhtqthf.html

[R44] 按修改时间查找
来源：http://dali.pycfn.com/Article/details/gt2uwnpdafi.html

find . -mtime -7 -type f
来源：http://dali.hywenlv.cn/Article/details/gt2rnofaegy.html

[R45] 批量删除
来源：http://dali.yongpay.top/Article/details/gt2cphrzsqk.html

find . -name "*.tmp" -delete
来源：http://dali.havefunace.top/Article/details/gt2ekhuehas.html

[R46] 递归替换文件内容
来源：http://dali.hammf.cn/Article/details/gt2sdkiuyui.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.c1oappe.top/Article/details/gt2gzywpwzo.html

[R47] sed 单行替换
来源：http://dali.yuanzhike.top/Article/details/gt2lileojyn.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.wangdashe.top/Article/details/gt2rxpeegmt.html

[R48] awk 取指定列
来源：http://dali.ivvv.top/Article/details/gt2kxvvpkfj.html

awk '{print $1, $3}' a.txt
来源：http://dali.redwolf501.top/Article/details/gt2lleejvuj.html

[R49] awk 带条件
来源：http://dali.tian-w.cn/Article/details/gt2afyucyfs.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2quudwwlo.html

[R50] awk 求和
来源：http://dali.hfpthk.cn/Article/details/gt2wmptnxip.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.dashuyun.cn/Article/details/gt2btgsjmfu.html

[R51] 排序去重取前几
来源：http://dali.daxiang520.top/Article/details/gt2elbxqyba.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.jqgfzy.top/Article/details/gt2qfwpwxev.html

[R52] 统计行数
来源：http://dali.yvedp.cn/Article/details/gt2dxjoqout.html

wc -l a.txt
来源：http://dali.redwolf501.top/Article/details/gt2uagtmlfm.html

[R53] 查看文件头与实时尾
来源：http://dali.cashguo.top/Article/details/gt2tizyptyo.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.0kj1m.cn/Article/details/gt2tgnbhfdk.html

[R54] 比较两个文件
来源：http://dali.0kj1m.cn/Article/details/gt2fnvlbtkr.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wygqvsnr.html

[R55] 压缩与解压
来源：http://dali.yuxming.cn/Article/details/gt2bsioyvyn.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.hongshengwenyu.top/Article/details/gt2bcdwoixr.html

[R56] 远程拷贝
来源：http://dali.yuanzhike.top/Article/details/gt2wkihcjmg.html

scp file user@host:/path/
来源：http://dali.redwolf501.top/Article/details/gt2bzodifsd.html

[R57] 远程执行命令
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sfwjrnvu.html

ssh user@host 'uptime'
来源：http://dali.pengpengdd.cyou/Article/details/gt2suuxawuz.html

[R58] 下载文件
来源：http://dali.yuxming.cn/Article/details/gt2njzsapmh.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jekqqzfb.html

[R59] 发 POST JSON
来源：http://dali.cdnleiting.top/Article/details/gt2ijahgvbl.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.ehwqpu.com/Article/details/gt2eibfhxwi.html

[R60] 只看 HTTP 状态码
来源：http://dali.kuanghao11.cn/Article/details/gt2repdjled.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.jqgufenzy.top/Article/details/gt2pzfrcqao.html

[R61] 磁盘占用
来源：http://dali.9152youxi.cn/Article/details/gt2fvhwyvbm.html

df -h;  du -sh *
来源：http://dali.zdqjudy.top/Article/details/gt2xgnmtrnd.html

[R62] 找最占空间的文件
来源：http://dali.sufxvd.cn/Article/details/gt2twaemyii.html

du -ah . | sort -rh | head -10
来源：http://dali.0kj1m.cn/Article/details/gt2ihayutaw.html

[R63] 内存与进程
来源：http://dali.guowangkeji.top/Article/details/gt2drzsfnrl.html

free -h;  ps aux | grep nginx
来源：http://dali.jinqigufen.top/Article/details/gt2fkqrpyvt.html

[R64] 结束进程
来源：http://dali.daxiang520.top/Article/details/gt2oeoypwar.html

kill -9 $(pgrep -f app.py)
来源：http://dali.hnxiangtu.top/Article/details/gt2rvnmpuld.html

[R65] 查看端口占用
来源：http://dali.yangfankeji.com/Article/details/gt2pfveaygw.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.9152youxi.cn/Article/details/gt2jdmpgiuo.html

[R66] 定时任务
来源：http://dali.hnxiangtu.top/Article/details/gt2hruorjvo.html

crontab -e;  crontab -l
来源：http://dali.nwbrower.top/Article/details/gt2qcvpezqm.html

[R67] 生成随机十六进制串
来源：http://dali.xziqi.cn/Article/details/gt2vdvwwggg.html

openssl rand -hex 16
来源：http://dali.sweek.top/Article/details/gt2zqxxynkg.html

[R68] 计算文件校验值
来源：http://dali.yongpay.top/Article/details/gt2whsrkjtl.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ivdrnban.html

[R69] 生成随机密码
来源：http://dali.iojbl.cn/Article/details/gt2prqqleun.html

head -c 16 /dev/urandom | base64
来源：http://dali.0kj1m.cn/Article/details/gt2ekkzmkry.html

[R70] 时间戳与互转
来源：http://dali.jqgufenzy.top/Article/details/gt2xkmwwbrs.html

date +%s;  date -d @1700000000
来源：http://dali.sxryk.cn/Article/details/gt2jxlnjkso.html

[R71] 日期格式化
来源：http://dali.jinqigfzy.top/Article/details/gt2jhvjvjxz.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.xinyue.icu/Article/details/gt2lrlxrnju.html

[R72] 等待端口就绪
来源：http://dali.tianlin.xyz/Article/details/gt2gyhhbhdv.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.yangfankeji.com/Article/details/gt2pzyelbmo.html

[R73] 分割大日志
来源：http://dali.ppjwa.cn/Article/details/gt2kxrjhipr.html

split -l 1000 big.log part_
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mjsupbwg.html

[R74] 批量重命名
来源：http://dali.9152youxi.cn/Article/details/gt2niwgkauv.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.meibo888.top/Article/details/gt2rqpyuyee.html

[R75] 导出环境变量
来源：http://dali.sweek.top/Article/details/gt2gvaxmypp.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhixingplan.top/Article/details/gt2coajngeo.html

[R76] 使用临时文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hosmlcen.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.ivvv.top/Article/details/gt2ivzzvpkq.html

[R77] 读取用户输入
来源：http://dali.smart0.xyz/Article/details/gt2wnmznmjj.html

read -rp "请输入: " ans
来源：http://dali.cqqwz.cn/Article/details/gt2agjashcg.html

[R78] 交互式菜单
来源：http://dali.aibaodan.cn/Article/details/gt2flbieuru.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.svipenyu.cn/Article/details/gt2wkoauvla.html

[R79] 解析命令行选项
来源：http://dali.ydzc1.top/Article/details/gt2tkjknzct.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2afzvmfns.html

[R80] 查看脚本执行耗时
来源：http://dali.hfpthk.cn/Article/details/gt2zcmyhxum.html

time ./run.sh
来源：http://dali.wangshuangyany.cn/Article/details/gt2kkmqwuqx.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2oevndgaf.html

S. C / C++ 专题
来源：http://dali.yuxming.cn/Article/details/gt2dxgxecdx.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gt2tyzqkxhd.html

[S01] C：Hello World
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gvgnbbiy.html

#include <stdio.h>
来源：http://dali.yj20258.top/Article/details/gt2dtjycvik.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.sysykeji.top/Article/details/gt2ozrigpza.html

[S02] C：变量与格式化输出
来源：http://dali.xziqi.cn/Article/details/gt2lmisiyem.html

int a = 10; printf("%d\n", a);
来源：http://dali.xinyue.icu/Article/details/gt2qnwowyxu.html

[S03] C：读入整数
来源：http://dali.jianghu66.top/Article/details/gt2uxtekklr.html

int x; scanf("%d", &x);
来源：http://dali.cheryme.top/Article/details/gt2tbudrghx.html

[S04] C：字符串复制
来源：http://dali.havefunace.top/Article/details/gt2evwpkunl.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.daxiang520.top/Article/details/gt2dlwzjgoj.html

[S05] C：字符串长度
来源：http://dali.aizwys.cn/Article/details/gt2yrygeyvq.html

strlen(s)
来源：http://dali.hnqzz.top/Article/details/gt2jypklngd.html

[S06] C：字符串比较
来源：http://dali.ydzc1.top/Article/details/gt2dgkhxeow.html

strcmp(a, b) == 0
来源：http://dali.dianchejie.cn/Article/details/gt2ovfitiba.html

[S07] C：数组遍历求和
来源：http://dali.ivvv.top/Article/details/gt2krneqewo.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.yj20258888.top/Article/details/gt2avffbcom.html

[S08] C：动态内存分配与释放
来源：http://dali.havefunace.top/Article/details/gt2alhgfgdo.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.nwbrower.top/Article/details/gt2lyqrdojk.html

[S09] C：结构体定义与初始化
来源：http://dali.jinqigfzy.top/Article/details/gt2scpfrtvs.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.yuanzhike.top/Article/details/gt2zrzwooxf.html

[S10] C：指针与解引用
来源：http://dali.yangfankeji.com/Article/details/gt2skgrwwha.html

int *p = &a;  *p = 5;
来源：http://dali.hnxiangtu.top/Article/details/gt2xfvlifeq.html

[S11] C：逐行读文件
来源：http://dali.316326.xyz/Article/details/gt2hupdqxzl.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.tianlin.xyz/Article/details/gt2ojqcxsyt.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.snrcjt.cn/Article/details/gt2kaslfvnm.html

fclose(f);
来源：http://dali.jinqigufen.top/Article/details/gt2ubtoutkj.html

[S12] C：写文件
来源：http://dali.zhongyouzk.top/Article/details/gt2vsiehwul.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.yj20258.top/Article/details/gt2wbrjernz.html

[S13] C：宏定义
来源：http://dali.zhiwuduotai.top/Article/details/gt2wsxwkfrm.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.kuanghao11.cn/Article/details/gt2snfjvolr.html

[S14] C：枚举
来源：http://dali.hysaishi.cn/Article/details/gt2cqdemomw.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.yj20258.top/Article/details/gt2rwimpoct.html

[S15] C：类型转换
来源：http://dali.gogol.net.cn/Article/details/gt2zxknidux.html

(double) a / b
来源：http://dali.pengpengdd.cyou/Article/details/gt2cwpshhzo.html

[S16] C：位操作置位
来源：http://dali.haohaochexian.top/Article/details/gt2cjoodunv.html

x |= (1 << 3);
来源：http://dali.zhixingplan.top/Article/details/gt2hncwaqbq.html

[S17] C：安全拼接字符串
来源：http://dali.jqgfzy.top/Article/details/gt2jjqixmlq.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhongyouzk.top/Article/details/gt2mfozkupz.html

[S18] C：命令行参数
来源：http://dali.sweek.top/Article/details/gt2awyphysl.html

int main(int argc, char **argv)
来源：http://dali.aibaodan.cn/Article/details/gt2vdnnnqtm.html

[S19] C：快速排序
来源：http://dali.cheryme.top/Article/details/gt2qhaatjsi.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.hnqzz.top/Article/details/gt2oaxspnfp.html

[S20] C：二分查找
来源：http://dali.sysykeji.top/Article/details/gt2fbmmmafr.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.hfpthk.cn/Article/details/gt2ameseadu.html

[S21] C：字符类别判断
来源：http://dali.gaohongyu789.top/Article/details/gt2kaukutbs.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.ybcxt.top/Article/details/gt2sbqngfjb.html

[S22] C：字符串转数字
来源：http://dali.jinqigfzy.top/Article/details/gt2shdoqbnp.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ohyfdjbi.html

[S23] C：随机数
来源：http://dali.tianlin.xyz/Article/details/gt2bcklodpp.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.birdmap.top/Article/details/gt2dxpnlfio.html

[S24] C：获取本地时间
来源：http://dali.xuanzx.com/Article/details/gt2rvumbvmp.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.havefunace.top/Article/details/gt2evsubaoa.html

[S25] C：内存拷贝
来源：http://dali.sweek.top/Article/details/gt2fqvgorsj.html

memcpy(dst, src, n);
来源：http://dali.dianchejie.cn/Article/details/gt2rpkokpjd.html

[S26] C：内存清零
来源：http://dali.0kj1m.cn/Article/details/gt2vkvfsrvh.html

memset(a, 0, sizeof a);
来源：http://dali.hywenlv.cn/Article/details/gt2hdcaeiwe.html

[S27] C：定义常量
来源：http://dali.zhongyouzk.top/Article/details/gt2olxprhyb.html

const double PI = 3.14159;
来源：http://dali.zhiwuduotai.top/Article/details/gt2iexvwvpq.html

[S28] C：静态变量
来源：http://dali.ydzc1.top/Article/details/gt2kyzqtefs.html

static int counter = 0;
来源：http://dali.guowangkeji.top/Article/details/gt2fjzqpfjc.html

[S29] C：变参函数
来源：http://dali.shuidangran.top/Article/details/gt2zwddyrol.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.mhx1999.top/Article/details/gt2lyuljnur.html

[S30] C：头文件保护
来源：http://dali.aibaodan.cn/Article/details/gt2diacdsjf.html

#ifndef X_H
来源：http://dali.chenlongwang.top/Article/details/gt2lyuqgoiw.html

#define X_H
来源：http://dali.sufxvd.cn/Article/details/gt2lmgwioik.html

#endif
来源：http://dali.ehwqpu.com/Article/details/gt2urvxopjv.html

[S31] C++：Hello World
来源：http://dali.xuanzx.com/Article/details/gt2fdmqkpvn.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2luukjtah.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zdqjudy.top/Article/details/gt2bprqbtjk.html

[S32] C++：字符串
来源：http://dali.mhx1999.top/Article/details/gt2uzlmhsik.html

std::string s = "hi";  s += "!";
来源：http://dali.nanxuanxn.top/Article/details/gt2ghernqsm.html

[S33] C++：vector 增删
来源：http://dali.chenjidiqi.icu/Article/details/gt2qcdsvzrk.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.xuetiantiany.cn/Article/details/gt2okctndoq.html

[S34] C++：遍历 vector
来源：http://dali.pycfn.com/Article/details/gt2nqaxgpxv.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.vqdsnc.cn/Article/details/gt2bsinjege.html

[S35] C++：map
来源：http://dali.snrcjt.cn/Article/details/gt2eyxzmsjy.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.cqqwz.cn/Article/details/gt2wyuvratd.html

[S36] C++：unordered_map
来源：http://dali.yanxiufei.cn/Article/details/gt2lkxypwmm.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.xuanzx.com/Article/details/gt2jvszshld.html

[S37] C++：set
来源：http://dali.cheryme.top/Article/details/gt2fcykoryr.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.jlsjyb.cn/Article/details/gt2byvinsfg.html

[S38] C++：排序
来源：http://dali.wangdashe.top/Article/details/gt2smyjxlvh.html

std::sort(v.begin(), v.end());
来源：http://dali.yanxiufei.cn/Article/details/gt2atpfhxsy.html

[S39] C++：自定义比较器排序
来源：http://dali.yj202588.top/Article/details/gt2qlteboqn.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.smart0.xyz/Article/details/gt2oeknzxbg.html

[S40] C++：查找元素
来源：http://dali.shangyingyoupin.top/Article/details/gt2yzbmnzkd.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.yonumen.top/Article/details/gt2rkdojctu.html

[S41] C++：类与构造函数
来源：http://dali.redwolf501.top/Article/details/gt2xwphijvo.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.jinqigufen.top/Article/details/gt2cfsxhtqx.html

[S42] C++：继承与虚函数
来源：http://dali.smart0.xyz/Article/details/gt2qgtreudy.html

class B : public Base { public: void f() override {} };
来源：http://dali.shzxlz.cn/Article/details/gt2hfhzspga.html

[S43] C++：智能指针
来源：http://dali.hysaishi.cn/Article/details/gt2fpkmsmkx.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhoulong.xyz/Article/details/gt2olrbejao.html

[S44] C++：引用传参
来源：http://dali.yuanzhike.top/Article/details/gt2cfewagos.html

void inc(int &x) { ++x; }
来源：http://dali.ybcxt.top/Article/details/gt2kpzjdast.html

[S45] C++：lambda
来源：http://dali.zycfv.cn/Article/details/gt2ddgluvve.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.shzxlz.cn/Article/details/gt2wzrjheor.html

[S46] C++：函数模板
来源：http://dali.cheryme.top/Article/details/gt2fowmkjnc.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.guowangkeji.top/Article/details/gt2kkecfwnu.html

[S47] C++：结构化绑定遍历
来源：http://dali.hysaishi.cn/Article/details/gt2ytleaarp.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.quarkkingdee.top/Article/details/gt2izmnlofv.html

[S48] C++：逐行读文件
来源：http://dali.zycfv.cn/Article/details/gt2vfammzpy.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.shuidangran.top/Article/details/gt2mdbcbuse.html

while (std::getline(in, line)) { }
来源：http://dali.c1oappe.top/Article/details/gt2zkoazrsm.html

[S49] C++：写文件
来源：http://dali.pycfn.com/Article/details/gt2mjkcbdak.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.wangshuangyany.cn/Article/details/gt2jmrwnmyl.html

[S50] C++：格式化数字
来源：http://dali.sufxvd.cn/Article/details/gt2hztejghz.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.c1oappe.top/Article/details/gt2dzclrcac.html

[S51] C++：显式类型转换
来源：http://dali.jiagoushi.top/Article/details/gt2odtoiuuu.html

static_cast<double>(a) / b
来源：http://dali.yj202588.top/Article/details/gt2jkwtfgms.html

[S52] C++：const 与 noexcept
来源：http://dali.feifeiyinyue.top/Article/details/gt2moanmhiq.html

int size() const noexcept { return n_; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2frazcirz.html

[S53] C++：移动语义
来源：http://dali.daria6918.cn/Article/details/gt2khydanjg.html

std::vector<int> w = std::move(v);
来源：http://dali.hysaishi.cn/Article/details/gt2clfehhxr.html

[S54] C++：异常处理
来源：http://dali.yueranfly.top/Article/details/gt2jevjtrlk.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.dianchejie.cn/Article/details/gt2oeggbpwx.html

[S55] C++：结构化绑定
来源：http://dali.gogol.net.cn/Article/details/gt2vsdlfqoc.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.nanxuanxn.top/Article/details/gt2fnavgwmy.html

[S56] C++：optional
来源：http://dali.yj202588.top/Article/details/gt2eseqecps.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.tian-w.cn/Article/details/gt2ydomvlhc.html

[S57] C++：编译期常量
来源：http://dali.kuanghao11.cn/Article/details/gt2ncmvzzmt.html

constexpr int N = 10;
来源：http://dali.aibaodan.cn/Article/details/gt2isvfjqct.html

[S58] C++：命名空间
来源：http://dali.jiagoushi.top/Article/details/gt2fyygldxq.html

namespace ns { int f() { return 1; } }
来源：http://dali.tanke756.top/Article/details/gt2gahqgned.html

[S59] C++：静态断言
来源：http://dali.hnqzz.top/Article/details/gt2caereijo.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.pycfn.com/Article/details/gt2gldzswlh.html

[S60] C++：遍历并删除元素
来源：http://dali.guannengcc.top/Article/details/gt2aefjstdx.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.yangfankeji.com/Article/details/gt2kegejshf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2esokhnbo.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yueranfly.top/Article/details/gt2tdnygwpp.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gt2vemomucc.html

[T01] Kotlin：Hello World
来源：http://dali.smart0.xyz/Article/details/gt2oeoljaof.html

println("Hello")
来源：http://dali.jinqigufen.top/Article/details/gt2qvokirrx.html

[T02] Kotlin：变量
来源：http://dali.tianlin.xyz/Article/details/gt2kskpewhr.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.yonumen.top/Article/details/gt2dcusktjo.html

[T03] Kotlin：字符串模板
来源：http://dali.jqgufenzy.top/Article/details/gt2srymvfnp.html

"值: $b"
来源：http://dali.tanke756.top/Article/details/gt2oyqlcqlf.html

[T04] Kotlin：空安全
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2petirixc.html

val n: String? = null;  n?.length
来源：http://dali.chenjidiqi.icu/Article/details/gt2zxwwucvg.html

[T05] Kotlin：when 表达式
来源：http://dali.yj202588.top/Article/details/gt2ygbjioom.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.quarkkingdee.top/Article/details/gt2ceketdkh.html

[T06] Kotlin：集合映射
来源：http://dali.yj20258888.top/Article/details/gt2ggqevqnn.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.redwolf501.top/Article/details/gt2skwiyfqz.html

[T07] Kotlin：集合过滤
来源：http://dali.cucudq.cn/Article/details/gt2opdofdyz.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.jianghu66.top/Article/details/gt2ogkvqpkx.html

[T08] Kotlin：数据类
来源：http://dali.ydzc1.top/Article/details/gt2hdstynxs.html

data class User(val name: String, val age: Int)
来源：http://dali.tanke756.top/Article/details/gt2fkbgespb.html

[T09] Kotlin：扩展函数
来源：http://dali.316326.xyz/Article/details/gt2khjlxzly.html

fun String.exclaim() = this + "!"
来源：http://dali.jinqigufen.top/Article/details/gt2teywhmiu.html

[T10] Kotlin：默认参数
来源：http://dali.havefunace.top/Article/details/gt2hzrbzwkc.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.bjfxy.top/Article/details/gt2czolcbhw.html

[T11] Kotlin：协程
来源：http://dali.sxryk.cn/Article/details/gt2hajnakrq.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jwfisbhk.html

[T12] Kotlin：解构声明
来源：http://dali.xuanzx.com/Article/details/gt2sqwrokbu.html

val (a, b) = Pair(1, 2)
来源：http://dali.gaohongyu789.top/Article/details/gt2gbevqjpi.html

[T13] Kotlin：只读 Map
来源：http://dali.jinqigfzy.top/Article/details/gt2uthjuotv.html

val m = mapOf("a" to 1)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uzcypkkf.html

[T14] Kotlin：循环
来源：http://dali.shuidangran.top/Article/details/gt2xvputypf.html

for (i in 1..10) println(i)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jvbgugya.html

[T15] Kotlin：接口
来源：http://dali.hnxiangtu.top/Article/details/gt2odeujwej.html

interface Shape { fun area(): Double }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uadtpmth.html

[T16] Swift：Hello World
来源：http://dali.nwbrower.top/Article/details/gt2aqmykykd.html

print("Hello")
来源：http://dali.shangyingyoupin.top/Article/details/gt2haaepsli.html

[T17] Swift：变量与常量
来源：http://dali.zhongyouzk.top/Article/details/gt2mhjfpcbi.html

var a = 1;  let b = 2
来源：http://dali.hfpthk.cn/Article/details/gt2nzdtdcud.html

[T18] Swift：字符串插值
来源：http://dali.yvedp.cn/Article/details/gt2etdpozdn.html

"值: \(b)"
来源：http://dali.daria6918.cn/Article/details/gt2usditran.html

[T19] Swift：可选绑定
来源：http://dali.redwolf501.top/Article/details/gt2lawlgppv.html

if let n = opt { print(n) }
来源：http://dali.yvedp.cn/Article/details/gt2rjjtwehh.html

[T20] Swift：数组操作
来源：http://dali.hongshengwenyu.top/Article/details/gt2zcisdloh.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.yj20258888.top/Article/details/gt2hfivuvrb.html

[T21] Swift：遍历
来源：http://dali.cheryme.top/Article/details/gt2ppukstcd.html

for x in a { print(x) }
来源：http://dali.xuanzx.com/Article/details/gt2dqvhkvbr.html

[T22] Swift：字典
来源：http://dali.hnxiangtu.top/Article/details/gt2uixblctz.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.jinqigfzy.top/Article/details/gt2vxzteari.html


<!-- 参考信息 -->