代发 wailian999

arr=(a b c); echo "${arr[0]}"
来源：http://dali.sufxvd.cn/Article/details/gt2wvbbhnch.html

[R18] 遍历数组
来源：http://dali.snrcjt.cn/Article/details/gt2twfhawhx.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.chenzaomai.com/Article/details/gt2rzjmidhb.html

[R19] 数组长度
来源：http://dali.iojbl.cn/Article/details/gt2upflwtew.html

echo "${#arr[@]}"
来源：http://dali.bjfxy.top/Article/details/gt2kwbencmp.html

[R20] 关联数组（字典）
来源：http://dali.tanke756.top/Article/details/gt2fbyalldq.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.yvedp.cn/Article/details/gt2xoqyjyae.html

[R21] 字符串长度
来源：http://dali.yj20258888.top/Article/details/gt2aeympgwb.html

echo "${#s}"
来源：http://dali.ehwqpu.com/Article/details/gt2uhlcqosb.html

[R22] 截取子串
来源：http://dali.smart0.xyz/Article/details/gt2upmozyts.html

echo "${s:0:5}"
来源：http://dali.9152youxi.cn/Article/details/gt2nypkecda.html

[R23] 字符串替换
来源：http://dali.nwbrower.top/Article/details/gt2geuycqpl.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.chenjidiqi.icu/Article/details/gt2xqpcptdc.html

[R24] 大小写转换
来源：http://dali.jinqigfzy.top/Article/details/gt2cwvtgxnj.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.daxiang520.top/Article/details/gt2qcixfypk.html

[R25] 去后缀 / 去前缀
来源：http://dali.hnqzz.top/Article/details/gt2itbjnxgb.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.yvedp.cn/Article/details/gt2wnfodjch.html

[R26] 命令替换
来源：http://dali.sysykeji.top/Article/details/gt2uasergmb.html

now=$(date +%F); echo "$now"
来源：http://dali.ppjwa.cn/Article/details/gt2ataddgpm.html

[R27] 算术展开
来源：http://dali.redwolf501.top/Article/details/gt2detckequ.html

echo $((1 + 2 * 3))
来源：http://dali.yanxiufei.cn/Article/details/gt2pwlizrrg.html

[R28] 浮点运算
来源：http://dali.ybcxt.top/Article/details/gt2qpczmzta.html

echo "scale=2; 10/3" | bc
来源：http://dali.hywenlv.cn/Article/details/gt2ychjwqwd.html

[R29] 定义函数
来源：http://dali.jqgufenzy.top/Article/details/gt2dpscoogv.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.0kj1m.cn/Article/details/gt2scycmcfn.html

[R30] 函数返回状态码
来源：http://dali.zhengqikj.top/Article/details/gt2vajdctzn.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.dianchejie.cn/Article/details/gt2mxqugoya.html

[R31] 局部变量
来源：http://dali.dashuyun.cn/Article/details/gt2ghorolyl.html

f() { local x=1; echo "$x"; }
来源：http://dali.9152youxi.cn/Article/details/gt2qgfrztwl.html

[R32] 参数个数校验
来源：http://dali.zhongyouzk.top/Article/details/gt2iqfjpmai.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.gzhubu.top/Article/details/gt2aixktzdu.html

[R33] 捕获错误并提示行号
来源：http://dali.jqgufenzy.top/Article/details/gt2diqsqatz.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.sysykeji.top/Article/details/gt2hmnabnfx.html

[R34] 退出时清理
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kcsvtehy.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.dianchejie.cn/Article/details/gt2eeucpbbt.html

[R35] 后台执行并等待
来源：http://dali.wangshuangyany.cn/Article/details/gt2ovreevbu.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.yangfankeji.com/Article/details/gt2gkslzcjk.html

[R36] 并发执行多个任务
来源：http://dali.daria6918.cn/Article/details/gt2iosdlbql.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.hnqzz.top/Article/details/gt2amulbfzo.html

[R37] 把输出赋给变量
来源：http://dali.cashguo.top/Article/details/gt2ovjxrags.html

files=$(ls -1)
来源：http://dali.9152youxi.cn/Article/details/gt2ymidmthu.html

[R38] 管道串联
来源：http://dali.hfpthk.cn/Article/details/gt2otpfpmvp.html

cat a.txt | grep -i error | wc -l
来源：http://dali.yuanzhike.top/Article/details/gt2ypertwei.html

[R39] 重定向标准输出与错误
来源：http://dali.yonumen.top/Article/details/gt2iiobreos.html

cmd > out.log 2>&1
来源：http://dali.yj20258.top/Article/details/gt2zhojlpqx.html

[R40] 追加写日志
来源：http://dali.svipenyu.cn/Article/details/gt2aymrwetc.html

echo "log" >> out.log
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qudoonhw.html

[R41] 丢弃输出
来源：http://dali.yuxming.cn/Article/details/gt2alfldqca.html

cmd >/dev/null 2>&1
来源：http://dali.shuidangran.top/Article/details/gt2zkogtdmc.html

[R42] 输入重定向
来源：http://dali.ydzc1.top/Article/details/gt2prrbqpap.html

wc -l < a.txt
来源：http://dali.zhoulong.xyz/Article/details/gt2zlqorsji.html

[R43] 按名字查找文件
来源：http://dali.hfpthk.cn/Article/details/gt2uxusuwxm.html

find . -name "*.log" -type f
来源：http://dali.xinyue.icu/Article/details/gt2smvmukbl.html

[R44] 按修改时间查找
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tnvzdzyx.html

find . -mtime -7 -type f
来源：http://dali.sufxvd.cn/Article/details/gt2sfkqvpoh.html

[R45] 批量删除
来源：http://dali.snrcjt.cn/Article/details/gt2xbxayejm.html

find . -name "*.tmp" -delete
来源：http://dali.fengsongda.top/Article/details/gt2lekchzwv.html

[R46] 递归替换文件内容
来源：http://dali.svipenyu.cn/Article/details/gt2ijwdxgzg.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.jlsjyb.cn/Article/details/gt2ksngicwb.html

[R47] sed 单行替换
来源：http://dali.ydzc1.top/Article/details/gt2yffkhull.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.aibaodan.cn/Article/details/gt2lmprqrpw.html

[R48] awk 取指定列
来源：http://dali.sufxvd.cn/Article/details/gt2rgurvumd.html

awk '{print $1, $3}' a.txt
来源：http://dali.cqqwz.cn/Article/details/gt2ziijqvul.html

[R49] awk 带条件
来源：http://dali.0kj1m.cn/Article/details/gt2ybnbkxrt.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2atchqfmb.html

[R50] awk 求和
来源：http://dali.gotoacloud.top/Article/details/gt2owdyhbnq.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.guannengcc.top/Article/details/gt2zelgcoqb.html

[R51] 排序去重取前几
来源：http://dali.yuanzhike.top/Article/details/gt2khjzxywb.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.xylfe.cn/Article/details/gt2xlujloro.html

[R52] 统计行数
来源：http://dali.ppjwa.cn/Article/details/gt2nzuarlkl.html

wc -l a.txt
来源：http://dali.aizwys.cn/Article/details/gt2tawbyubj.html

[R53] 查看文件头与实时尾
来源：http://dali.gogol.net.cn/Article/details/gt2kzljjriz.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.fengsongda.top/Article/details/gt2nstioeqc.html

[R54] 比较两个文件
来源：http://dali.9152youxi.cn/Article/details/gt2sekomoyn.html

diff a.txt b.txt
来源：http://dali.nwbrower.top/Article/details/gt2makbqpui.html

[R55] 压缩与解压
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lqgfbrjt.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.yj202588.top/Article/details/gt2ryymqfop.html

[R56] 远程拷贝
来源：http://dali.aizwys.cn/Article/details/gt2pjuzfxmw.html

scp file user@host:/path/
来源：http://dali.smart0.xyz/Article/details/gt2ghfpabpy.html

[R57] 远程执行命令
来源：http://dali.cashguo.top/Article/details/gt2jifebgfg.html

ssh user@host 'uptime'
来源：http://dali.yuanzhike.top/Article/details/gt2xbofhalu.html

[R58] 下载文件
来源：http://dali.hnxiangtu.top/Article/details/gt2oaqxqfdg.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.aibaodan.cn/Article/details/gt2cabjufcx.html

[R59] 发 POST JSON
来源：http://dali.gogol.net.cn/Article/details/gt2hyazcmmd.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.yuxming.cn/Article/details/gt2mbsfbxbi.html

[R60] 只看 HTTP 状态码
来源：http://dali.jqgfzy.top/Article/details/gt2tmbczolf.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.yonumen.top/Article/details/gt2xtkjryeu.html

[R61] 磁盘占用
来源：http://dali.zhiwuduotai.top/Article/details/gt2pewzwees.html

df -h;  du -sh *
来源：http://dali.zhengqikj.top/Article/details/gt2jxckpepv.html

[R62] 找最占空间的文件
来源：http://dali.cheryme.top/Article/details/gt2mnjfktdk.html

du -ah . | sort -rh | head -10
来源：http://dali.c1oappe.top/Article/details/gt2zijyzusv.html

[R63] 内存与进程
来源：http://dali.hywenlv.cn/Article/details/gt2vryeadua.html

free -h;  ps aux | grep nginx
来源：http://dali.yj20258888.top/Article/details/gt2fjjdtkqb.html

[R64] 结束进程
来源：http://dali.xylfe.cn/Article/details/gt2uptdnwyh.html

kill -9 $(pgrep -f app.py)
来源：http://dali.cqqwz.cn/Article/details/gt2vgczjeke.html

[R65] 查看端口占用
来源：http://dali.cucudq.cn/Article/details/gt2sxxhpwzl.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhengqikj.top/Article/details/gt2rjtgafxv.html

[R66] 定时任务
来源：http://dali.0kj1m.cn/Article/details/gt2rvsxzutn.html

crontab -e;  crontab -l
来源：http://dali.wangdashe.top/Article/details/gt2ytgdksoy.html

[R67] 生成随机十六进制串
来源：http://dali.hfpthk.cn/Article/details/gt2kkwxttew.html

openssl rand -hex 16
来源：http://dali.316326.xyz/Article/details/gt2ruhrungx.html

[R68] 计算文件校验值
来源：http://dali.nwbrower.top/Article/details/gt2prztoqlw.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhoulong.xyz/Article/details/gt2vziabarm.html

[R69] 生成随机密码
来源：http://dali.gzhubu.top/Article/details/gt2oapwhmkr.html

head -c 16 /dev/urandom | base64
来源：http://dali.hongshengwenyu.top/Article/details/gt2pdnhthrd.html

[R70] 时间戳与互转
来源：http://dali.andypj.xyz/Article/details/gt2zxqmyufi.html

date +%s;  date -d @1700000000
来源：http://dali.gaohongyu789.top/Article/details/gt2eypqrdpd.html

[R71] 日期格式化
来源：http://dali.andypj.xyz/Article/details/gt2zxialepa.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.xinyue.icu/Article/details/gt2cvjehaqu.html

[R72] 等待端口就绪
来源：http://dali.yvedp.cn/Article/details/gt2xrmilsnq.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2idmhzwph.html

[R73] 分割大日志
来源：http://dali.hysaishi.cn/Article/details/gt2wnchbfkd.html

split -l 1000 big.log part_
来源：http://dali.bjfxy.top/Article/details/gt2omrbqgre.html

[R74] 批量重命名
来源：http://dali.xinyue.icu/Article/details/gt2texaefqc.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.tanke756.top/Article/details/gt2dkyxoldo.html

[R75] 导出环境变量
来源：http://dali.svipenyu.cn/Article/details/gt2yilqpsbw.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.wangshuangyany.cn/Article/details/gt2tkehezfz.html

[R76] 使用临时文件
来源：http://dali.ppjwa.cn/Article/details/gt2reaklwej.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.hammf.cn/Article/details/gt2ntmengqp.html

[R77] 读取用户输入
来源：http://dali.yj20258.top/Article/details/gt2aduwrrom.html

read -rp "请输入: " ans
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xgitnxex.html

[R78] 交互式菜单
来源：http://dali.nanxinkj.top/Article/details/gt2lwfrnevr.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.bjfxy.top/Article/details/gt2hbetvyow.html

[R79] 解析命令行选项
来源：http://dali.hysaishi.cn/Article/details/gt2xdtskwfa.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.yueranfly.top/Article/details/gt2ymhebiut.html

[R80] 查看脚本执行耗时
来源：http://dali.sxryk.cn/Article/details/gt2vkmduvml.html

time ./run.sh
来源：http://dali.yueranfly.top/Article/details/gt2bzgivlty.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2xnbylpxs.html

S. C / C++ 专题
来源：http://dali.c1oappe.top/Article/details/gt2srmjhqwi.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gt2ogjjvhme.html

[S01] C：Hello World
来源：http://dali.gotoacloud.top/Article/details/gt2qhyfuehr.html

#include <stdio.h>
来源：http://dali.zhixingplan.top/Article/details/gt2ccnvgfum.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qoshdugi.html

[S02] C：变量与格式化输出
来源：http://dali.ybcxt.top/Article/details/gt2kkxqrwyy.html

int a = 10; printf("%d\n", a);
来源：http://dali.ybcxt.top/Article/details/gt2dzlcfbgx.html

[S03] C：读入整数
来源：http://dali.jinqigufen.top/Article/details/gt2xsizogvf.html

int x; scanf("%d", &x);
来源：http://dali.sufxvd.cn/Article/details/gt2rcrcmbfy.html

[S04] C：字符串复制
来源：http://dali.shangyingyoupin.top/Article/details/gt2sdmllztl.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.sweek.top/Article/details/gt2gannktgg.html

[S05] C：字符串长度
来源：http://dali.jianghu66.top/Article/details/gt2jrafbbdj.html

strlen(s)
来源：http://dali.pengpengdd.cyou/Article/details/gt2hyrfcmty.html

[S06] C：字符串比较
来源：http://dali.svipenyu.cn/Article/details/gt2eiwczffa.html

strcmp(a, b) == 0
来源：http://dali.nanxuanxn.top/Article/details/gt2mvtbkfoe.html

[S07] C：数组遍历求和
来源：http://dali.smart0.xyz/Article/details/gt2qoydbexb.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.c1oappe.top/Article/details/gt2ojoqrydc.html

[S08] C：动态内存分配与释放
来源：http://dali.shuidangran.top/Article/details/gt2uuvpunls.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.yuxming.cn/Article/details/gt2fypbvesh.html

[S09] C：结构体定义与初始化
来源：http://dali.tanke756.top/Article/details/gt2uzlylrex.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.feifeiyinyue.top/Article/details/gt2bofjwdbc.html

[S10] C：指针与解引用
来源：http://dali.sxryk.cn/Article/details/gt2webnfqwz.html

int *p = &a;  *p = 5;
来源：http://dali.cucudq.cn/Article/details/gt2ofcwsdal.html

[S11] C：逐行读文件
来源：http://dali.daria6918.cn/Article/details/gt2ohyvrpmb.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gjodnmkh.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.sxryk.cn/Article/details/gt2gpendbfv.html

fclose(f);
来源：http://dali.tian-w.cn/Article/details/gt2crsyweer.html

[S12] C：写文件
来源：http://dali.zdqjudy.top/Article/details/gt2wovwsmqj.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.chenlongwang.top/Article/details/gt2cvhywidp.html

[S13] C：宏定义
来源：http://dali.nanxinkj.top/Article/details/gt2sneovpul.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.xylfe.cn/Article/details/gt2csuxqiuk.html

[S14] C：枚举
来源：http://dali.gzhubu.top/Article/details/gt2gnjlnzke.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.pycfn.com/Article/details/gt2jfsrsxkt.html

[S15] C：类型转换
来源：http://dali.zhoulong.xyz/Article/details/gt2orsvtmfp.html

(double) a / b
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rfekahgr.html

[S16] C：位操作置位
来源：http://dali.pengpengdd.cyou/Article/details/gt2uvswlauw.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ffyxevvh.html

[S17] C：安全拼接字符串
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hhalkiyt.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.cdnleiting.top/Article/details/gt2aiknhdpu.html

[S18] C：命令行参数
来源：http://dali.tian-w.cn/Article/details/gt2bynfrwwq.html

int main(int argc, char **argv)
来源：http://dali.gaohongyu789.top/Article/details/gt2kglzrigr.html

[S19] C：快速排序
来源：http://dali.yj202588.top/Article/details/gt2olnekjpx.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2byjfeqfk.html

[S20] C：二分查找
来源：http://dali.xuetiantiany.cn/Article/details/gt2apfikncs.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.sweek.top/Article/details/gt2bkhoaqro.html

[S21] C：字符类别判断
来源：http://dali.meibo888.top/Article/details/gt2btfzbahf.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.jinqigfzy.top/Article/details/gt2nuxhtetu.html

[S22] C：字符串转数字
来源：http://dali.vqdsnc.cn/Article/details/gt2wdovzmgk.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.quarkkingdee.top/Article/details/gt2hicnpbfd.html

[S23] C：随机数
来源：http://dali.chenlongwang.top/Article/details/gt2gfgluezf.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.cucudq.cn/Article/details/gt2cikscfkn.html

[S24] C：获取本地时间
来源：http://dali.nanxinkj.top/Article/details/gt2qbgvdkki.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.nanxuanxn.top/Article/details/gt2qebuuuvv.html

[S25] C：内存拷贝
来源：http://dali.andypj.xyz/Article/details/gt2yleehxja.html

memcpy(dst, src, n);
来源：http://dali.shangyingyoupin.top/Article/details/gt2lykamgxv.html

[S26] C：内存清零
来源：http://dali.jinqigfzy.top/Article/details/gt2jwexsucp.html

memset(a, 0, sizeof a);
来源：http://dali.zhongyouzk.top/Article/details/gt2vilffltj.html

[S27] C：定义常量
来源：http://dali.shuidangran.top/Article/details/gt2cypnlzgo.html

const double PI = 3.14159;
来源：http://dali.dashuyun.cn/Article/details/gt2xzgtkmlh.html

[S28] C：静态变量
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2asubikql.html

static int counter = 0;
来源：http://dali.wangdashe.top/Article/details/gt2bithxywk.html

[S29] C：变参函数
来源：http://dali.cqqwz.cn/Article/details/gt2uwnmslzh.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.ppjwa.cn/Article/details/gt2cuuawpwn.html

[S30] C：头文件保护
来源：http://dali.redwolf501.top/Article/details/gt2oferakph.html

#ifndef X_H
来源：http://dali.9152youxi.cn/Article/details/gt2agsnfykt.html

#define X_H
来源：http://dali.pengpengdd.cyou/Article/details/gt2tftptesx.html

#endif
来源：http://dali.yongpay.top/Article/details/gt2wveglzea.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2pkpxnqga.html

#include <iostream>
来源：http://dali.havefunace.top/Article/details/gt2yvgnbqsz.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.cucudq.cn/Article/details/gt2evoafbhv.html

[S32] C++：字符串
来源：http://dali.snrcjt.cn/Article/details/gt2xhghgdwh.html

std::string s = "hi";  s += "!";
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xbpzapuv.html

[S33] C++：vector 增删
来源：http://dali.zhoulong.xyz/Article/details/gt2imvhrlis.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.yueranfly.top/Article/details/gt2pptatekw.html

[S34] C++：遍历 vector
来源：http://dali.gaohongyu789.top/Article/details/gt2poizmkpw.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.gzhubu.top/Article/details/gt2knqjbkdg.html

[S35] C++：map
来源：http://dali.kuanghao11.cn/Article/details/gt2loirsznb.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jqgufenzy.top/Article/details/gt2inetqxli.html

[S36] C++：unordered_map
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kgdotaex.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jinqigufen.top/Article/details/gt2bcrzggnx.html

[S37] C++：set
来源：http://dali.ppjwa.cn/Article/details/gt2psomvqoh.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.hammf.cn/Article/details/gt2kqievcmy.html

[S38] C++：排序
来源：http://dali.birdmap.top/Article/details/gt2tltbroqo.html

std::sort(v.begin(), v.end());
来源：http://dali.redwolf501.top/Article/details/gt2eeztkhqb.html

[S39] C++：自定义比较器排序
来源：http://dali.aizwys.cn/Article/details/gt2lmhottkp.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.0kj1m.cn/Article/details/gt2wdanvhev.html

[S40] C++：查找元素
来源：http://dali.yj202588.top/Article/details/gt2kyfwydim.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.jinqigufen.top/Article/details/gt2xtykdkzj.html

[S41] C++：类与构造函数
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cfpsvvaj.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.andypj.xyz/Article/details/gt2ytjckzqs.html

[S42] C++：继承与虚函数
来源：http://dali.sysykeji.top/Article/details/gt2lgqdnpso.html

class B : public Base { public: void f() override {} };
来源：http://dali.cheryme.top/Article/details/gt2drmzlrhc.html

[S43] C++：智能指针
来源：http://dali.ydzc1.top/Article/details/gt2qwyvipna.html

auto p = std::make_unique<int>(5);
来源：http://dali.nanxinkj.top/Article/details/gt2khwlmvyf.html

[S44] C++：引用传参
来源：http://dali.gaohongyu789.top/Article/details/gt2yqwjtwpg.html

void inc(int &x) { ++x; }
来源：http://dali.hysaishi.cn/Article/details/gt2gkalatop.html

[S45] C++：lambda
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ctmgpppy.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nhibvbxb.html

[S46] C++：函数模板
来源：http://dali.9152youxi.cn/Article/details/gt2rpgkmaei.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.cheryme.top/Article/details/gt2aafmasbx.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhiwuduotai.top/Article/details/gt2xnpmvabf.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.yangfankeji.com/Article/details/gt2wdxxhanx.html

[S48] C++：逐行读文件
来源：http://dali.xinyue.icu/Article/details/gt2foymqbtx.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.jinqigufen.top/Article/details/gt2xxphkrev.html

while (std::getline(in, line)) { }
来源：http://dali.yuanzhike.top/Article/details/gt2bwtimtnx.html

[S49] C++：写文件
来源：http://dali.hysaishi.cn/Article/details/gt2pzhvngua.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.ppjwa.cn/Article/details/gt2iepkfipn.html

[S50] C++：格式化数字
来源：http://dali.hfpthk.cn/Article/details/gt2gmkcerrx.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.dianchejie.cn/Article/details/gt2buaruxoa.html

[S51] C++：显式类型转换
来源：http://dali.birdmap.top/Article/details/gt2yijewwkh.html

static_cast<double>(a) / b
来源：http://dali.cucudq.cn/Article/details/gt2ymlofpoi.html

[S52] C++：const 与 noexcept
来源：http://dali.shangyingyoupin.top/Article/details/gt2imqgoxhn.html

int size() const noexcept { return n_; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lwoszjtl.html

[S53] C++：移动语义
来源：http://dali.jinqigfzy.top/Article/details/gt2kdkyoeeh.html

std::vector<int> w = std::move(v);
来源：http://dali.zhoulong.xyz/Article/details/gt2mhrijxtt.html

[S54] C++：异常处理
来源：http://dali.snrcjt.cn/Article/details/gt2wovmoetv.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jjwjkgms.html

[S55] C++：结构化绑定
来源：http://dali.guowangkeji.top/Article/details/gt2jjpaxggn.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.yvedp.cn/Article/details/gt2dxpxkruy.html

[S56] C++：optional
来源：http://dali.hongshengwenyu.top/Article/details/gt2yzimrsaw.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yueranfly.top/Article/details/gt2jciwnrsu.html

[S57] C++：编译期常量
来源：http://dali.nanxinkj.top/Article/details/gt2idptawpj.html

constexpr int N = 10;
来源：http://dali.aizwys.cn/Article/details/gt2oscpjtpr.html

[S58] C++：命名空间
来源：http://dali.shangyingyoupin.top/Article/details/gt2feubkgug.html

namespace ns { int f() { return 1; } }
来源：http://dali.jinqigfzy.top/Article/details/gt2zjvcbgmz.html

[S59] C++：静态断言
来源：http://dali.jlsjyb.cn/Article/details/gt2dadhtnts.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.shangyingyoupin.top/Article/details/gt2fqgsmgdr.html

[S60] C++：遍历并删除元素
来源：http://dali.pycfn.com/Article/details/gt2jclkvkjf.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.wangdashe.top/Article/details/gt2uzkarkte.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vxpqsquz.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.gotoacloud.top/Article/details/gt2lvsmtucg.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mgjzgifk.html

[T01] Kotlin：Hello World
来源：http://dali.tanke756.top/Article/details/gt2qcufomwk.html

println("Hello")
来源：http://dali.yj20258888.top/Article/details/gt2beuvlxov.html

[T02] Kotlin：变量
来源：http://dali.zhiwuduotai.top/Article/details/gt2lifilonk.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.hysaishi.cn/Article/details/gt2pawjsuoj.html

[T03] Kotlin：字符串模板
来源：http://dali.dianchejie.cn/Article/details/gt2qfgxdkqk.html

"值: $b"
来源：http://dali.snrcjt.cn/Article/details/gt2ocredutg.html

[T04] Kotlin：空安全
来源：http://dali.hysaishi.cn/Article/details/gt2mrybifqw.html

val n: String? = null;  n?.length
来源：http://dali.fzhhl.top/Article/details/gt2ynzqfvuz.html

[T05] Kotlin：when 表达式
来源：http://dali.pycfn.com/Article/details/gt2fbmlbxzo.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.yuxming.cn/Article/details/gt2trpcauzr.html

[T06] Kotlin：集合映射
来源：http://dali.sxryk.cn/Article/details/gt2jaopnjna.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.shangyingyoupin.top/Article/details/gt2olfpvlvh.html

[T07] Kotlin：集合过滤
来源：http://dali.xziqi.cn/Article/details/gt2jboqrzdy.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zdqjudy.top/Article/details/gt2amcbhavk.html

[T08] Kotlin：数据类
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xupplntm.html

data class User(val name: String, val age: Int)
来源：http://dali.hammf.cn/Article/details/gt2lgceqtnd.html

[T09] Kotlin：扩展函数
来源：http://dali.cucudq.cn/Article/details/gt2biwruzrt.html

fun String.exclaim() = this + "!"
来源：http://dali.guowangkeji.top/Article/details/gt2hnyctgdo.html

[T10] Kotlin：默认参数
来源：http://dali.jlsjyb.cn/Article/details/gt2mszsoaek.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.fengsongda.top/Article/details/gt2zteynagi.html

[T11] Kotlin：协程
来源：http://dali.jianghu66.top/Article/details/gt2xnhrikly.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.hysaishi.cn/Article/details/gt2xtravraa.html

[T12] Kotlin：解构声明
来源：http://dali.snrcjt.cn/Article/details/gt2kuyzspqv.html

val (a, b) = Pair(1, 2)
来源：http://dali.chenjidiqi.icu/Article/details/gt2hjiowait.html

[T13] Kotlin：只读 Map
来源：http://dali.yuxming.cn/Article/details/gt2esdwaqbx.html

val m = mapOf("a" to 1)
来源：http://dali.aibaodan.cn/Article/details/gt2eszdnwzc.html

[T14] Kotlin：循环
来源：http://dali.daria6918.cn/Article/details/gt2hgkrosmp.html

for (i in 1..10) println(i)
来源：http://dali.cqqwz.cn/Article/details/gt2letrodmj.html

[T15] Kotlin：接口
来源：http://dali.aibaodan.cn/Article/details/gt2xvcykplx.html

interface Shape { fun area(): Double }
来源：http://dali.guannengcc.top/Article/details/gt2ixzvfgtq.html

[T16] Swift：Hello World
来源：http://dali.meibo888.top/Article/details/gt2ztqzchtt.html

print("Hello")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hroxdxji.html

[T17] Swift：变量与常量
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fieaorif.html

var a = 1;  let b = 2
来源：http://dali.yanxiufei.cn/Article/details/gt2lnbdbcrn.html

[T18] Swift：字符串插值
来源：http://dali.tanke756.top/Article/details/gt2nvrrxyxu.html

"值: \(b)"
来源：http://dali.shuidangran.top/Article/details/gt2ydzvykqz.html

[T19] Swift：可选绑定
来源：http://dali.fzhhl.top/Article/details/gt2bzkdeawh.html

if let n = opt { print(n) }
来源：http://dali.ybcxt.top/Article/details/gt2zfpzjhau.html

[T20] Swift：数组操作
来源：http://dali.redwolf501.top/Article/details/gt2cjujfrtm.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.yueranfly.top/Article/details/gt2jcykmlvi.html


<!-- 参考信息 -->