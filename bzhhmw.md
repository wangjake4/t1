代发 wailian999

esac
来源：http://dali.redwolf501.top/Article/details/gtkkbzwism.html

[R12] for 遍历文件
来源：http://dali.shuidangran.top/Article/details/gtdsmmmvrk.html

for f in *.txt; do echo "$f"; done
来源：http://dali.chenjidiqi.icu/Article/details/gtjyeusuwb.html

[R13] for 计数循环
来源：http://dali.zhongyouzk.top/Article/details/gtiqwxvfmt.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.andypj.xyz/Article/details/gtqelytrea.html

[R14] C 风格 for
来源：http://dali.jianghu66.top/Article/details/gtvwrotogr.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzeejloeu.html

[R15] while 逐行读文件
来源：http://dali.nanxinkj.top/Article/details/gtfsvgwhlz.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.kuanghao11.cn/Article/details/gtyhtmwbpr.html

[R16] until 等待条件
来源：http://dali.fzhhl.top/Article/details/gtdxcnhizf.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.hywenlv.cn/Article/details/gttahvwrtb.html

[R17] 数组定义与取值
来源：http://dali.xziqi.cn/Article/details/gtodvqcyhu.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.dianchejie.cn/Article/details/gtsrxjmbie.html

[R18] 遍历数组
来源：http://dali.ppjwa.cn/Article/details/gtvrnmujrg.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.xylfe.cn/Article/details/gtpytgosoq.html

[R19] 数组长度
来源：http://dali.c1oappe.top/Article/details/gtzclophnc.html

echo "${#arr[@]}"
来源：http://dali.ydzc1.top/Article/details/gtvzwovvsk.html

[R20] 关联数组（字典）
来源：http://dali.xziqi.cn/Article/details/gtblwjkulk.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.yanxiufei.cn/Article/details/gttnmqwuul.html

[R21] 字符串长度
来源：http://dali.yanxiufei.cn/Article/details/gtzoghjpuw.html

echo "${#s}"
来源：http://dali.hammf.cn/Article/details/gtakryrhiq.html

[R22] 截取子串
来源：http://dali.yj20258.top/Article/details/gtrlebyail.html

echo "${s:0:5}"
来源：http://dali.daria6918.cn/Article/details/gtrfgawnsz.html

[R23] 字符串替换
来源：http://dali.zhixingplan.top/Article/details/gteqsfurmo.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.tanke756.top/Article/details/gtmahjhcdm.html

[R24] 大小写转换
来源：http://dali.yueranfly.top/Article/details/gtealuykco.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.jlsjyb.cn/Article/details/gtdwqhkwch.html

[R25] 去后缀 / 去前缀
来源：http://dali.fengsongda.top/Article/details/gtyayrtkjf.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.shzxlz.cn/Article/details/gtrzewfoew.html

[R26] 命令替换
来源：http://dali.zycfv.cn/Article/details/gtcgwhllme.html

now=$(date +%F); echo "$now"
来源：http://dali.gogol.net.cn/Article/details/gtwenjnerr.html

[R27] 算术展开
来源：http://dali.ehwqpu.com/Article/details/gtsthbpzol.html

echo $((1 + 2 * 3))
来源：http://dali.vqdsnc.cn/Article/details/gtxturlhjg.html

[R28] 浮点运算
来源：http://dali.zhongyouzk.top/Article/details/gthgpwjpne.html

echo "scale=2; 10/3" | bc
来源：http://dali.birdmap.top/Article/details/gttpsqbbaf.html

[R29] 定义函数
来源：http://dali.sufxvd.cn/Article/details/gtyehgaame.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.jinghuilouyu.cn/Article/details/gtblocvkjd.html

[R30] 函数返回状态码
来源：http://dali.ehwqpu.com/Article/details/gtvkaofqsl.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zycfv.cn/Article/details/gtcxsfjsru.html

[R31] 局部变量
来源：http://dali.nwbrower.top/Article/details/gtjvtegbfk.html

f() { local x=1; echo "$x"; }
来源：http://dali.iojbl.cn/Article/details/gtatiyrhyf.html

[R32] 参数个数校验
来源：http://dali.aibaodan.cn/Article/details/gtgiyombyy.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhixingplan.top/Article/details/gtcsqnlumh.html

[R33] 捕获错误并提示行号
来源：http://dali.jqgufenzy.top/Article/details/gtbfqmsbtt.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.kuanghao11.cn/Article/details/gtbvpjnfga.html

[R34] 退出时清理
来源：http://dali.gzhubu.top/Article/details/gtcydgyjeo.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.svipenyu.cn/Article/details/gtirxzibmr.html

[R35] 后台执行并等待
来源：http://dali.chenzaomai.com/Article/details/gtmyiopbon.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.kuanghao11.cn/Article/details/gtatirroui.html

[R36] 并发执行多个任务
来源：http://dali.feifeiyinyue.top/Article/details/gtynptslln.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhixingplan.top/Article/details/gtrldegbjz.html

[R37] 把输出赋给变量
来源：http://dali.guannengcc.top/Article/details/gtutengoxm.html

files=$(ls -1)
来源：http://dali.yangfankeji.com/Article/details/gtdmizypdw.html

[R38] 管道串联
来源：http://dali.jyoumei.cn/Article/details/gtrfmizkdh.html

cat a.txt | grep -i error | wc -l
来源：http://dali.yueranfly.top/Article/details/gtwvumdjzn.html

[R39] 重定向标准输出与错误
来源：http://dali.gogol.net.cn/Article/details/gtrbcmjoxh.html

cmd > out.log 2>&1
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzanffzbc.html

[R40] 追加写日志
来源：http://dali.yj20258888.top/Article/details/gtxjmccjcs.html

echo "log" >> out.log
来源：http://dali.ivvv.top/Article/details/gtkoqeuvdv.html

[R41] 丢弃输出
来源：http://dali.yueranfly.top/Article/details/gtlyggmmup.html

cmd >/dev/null 2>&1
来源：http://dali.hongshengwenyu.top/Article/details/gtiehjebfq.html

[R42] 输入重定向
来源：http://dali.daxiang520.top/Article/details/gtwnvkayna.html

wc -l < a.txt
来源：http://dali.smart0.xyz/Article/details/gtolgyttvw.html

[R43] 按名字查找文件
来源：http://dali.shanyushiyangtech.top/Article/details/gtyaodrkka.html

find . -name "*.log" -type f
来源：http://dali.tanke756.top/Article/details/gtuzinbcej.html

[R44] 按修改时间查找
来源：http://dali.jinqigufen.top/Article/details/gtpkgweipg.html

find . -mtime -7 -type f
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkquymwrp.html

[R45] 批量删除
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdndhrlwh.html

find . -name "*.tmp" -delete
来源：http://dali.xylfe.cn/Article/details/gttwiliskx.html

[R46] 递归替换文件内容
来源：http://dali.bjfxy.top/Article/details/gtemknlfxx.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.snrcjt.cn/Article/details/gtxkugnxyd.html

[R47] sed 单行替换
来源：http://dali.svipenyu.cn/Article/details/gtygkjyraa.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.jinqigufen.top/Article/details/gtiikumkmh.html

[R48] awk 取指定列
来源：http://dali.sysykeji.top/Article/details/gtekshlrxq.html

awk '{print $1, $3}' a.txt
来源：http://dali.jianghu66.top/Article/details/gtixfzkfzv.html

[R49] awk 带条件
来源：http://dali.0kj1m.cn/Article/details/gtaboshxnq.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.snrcjt.cn/Article/details/gtnhghkimu.html

[R50] awk 求和
来源：http://dali.yanxiufei.cn/Article/details/gtolpjhgsw.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.birdmap.top/Article/details/gtyvrznlxu.html

[R51] 排序去重取前几
来源：http://dali.guowangkeji.top/Article/details/gthscxnvdz.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.cdnleiting.top/Article/details/gtevwollgy.html

[R52] 统计行数
来源：http://dali.meibo888.top/Article/details/gtzctzccxu.html

wc -l a.txt
来源：http://dali.jlsjyb.cn/Article/details/gtltcdqquh.html

[R53] 查看文件头与实时尾
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwlppqyrl.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.yueranfly.top/Article/details/gtimxaipjo.html

[R54] 比较两个文件
来源：http://dali.hysaishi.cn/Article/details/gtypvdjdir.html

diff a.txt b.txt
来源：http://dali.cucudq.cn/Article/details/gtrvzfwxxv.html

[R55] 压缩与解压
来源：http://dali.hywenlv.cn/Article/details/gtwxqjoxgn.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.xinyue.icu/Article/details/gtvaelqzzf.html

[R56] 远程拷贝
来源：http://dali.xylfe.cn/Article/details/gtsqeredtf.html

scp file user@host:/path/
来源：http://dali.0kj1m.cn/Article/details/gttanbmxsa.html

[R57] 远程执行命令
来源：http://dali.hnxiangtu.top/Article/details/gtwjkgsojx.html

ssh user@host 'uptime'
来源：http://dali.cqqwz.cn/Article/details/gtipynohmg.html

[R58] 下载文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdjzwpwvc.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.yuxming.cn/Article/details/gtpozzfgun.html

[R59] 发 POST JSON
来源：http://dali.tianlin.xyz/Article/details/gtzflmbmni.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.ivvv.top/Article/details/gtdfrrwdcm.html

[R60] 只看 HTTP 状态码
来源：http://dali.wangshuangyany.cn/Article/details/gthddkgaeg.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.mhx1999.top/Article/details/gtnnvnplph.html

[R61] 磁盘占用
来源：http://dali.aizwys.cn/Article/details/gtcpyztylu.html

df -h;  du -sh *
来源：http://dali.cheryme.top/Article/details/gthqxdxbym.html

[R62] 找最占空间的文件
来源：http://dali.snrcjt.cn/Article/details/gtgcyziejt.html

du -ah . | sort -rh | head -10
来源：http://dali.yangfankeji.com/Article/details/gtehdkhqfu.html

[R63] 内存与进程
来源：http://dali.sysykeji.top/Article/details/gtvumqomuy.html

free -h;  ps aux | grep nginx
来源：http://dali.yanxiufei.cn/Article/details/gthxcurdna.html

[R64] 结束进程
来源：http://dali.dashuyun.cn/Article/details/gtnqrbfplx.html

kill -9 $(pgrep -f app.py)
来源：http://dali.chenzaomai.com/Article/details/gttfobmsga.html

[R65] 查看端口占用
来源：http://dali.vqdsnc.cn/Article/details/gtricyhgxm.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.guowangkeji.top/Article/details/gtxowbmlzz.html

[R66] 定时任务
来源：http://dali.jqgufenzy.top/Article/details/gtguxkimmr.html

crontab -e;  crontab -l
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwhbvkohz.html

[R67] 生成随机十六进制串
来源：http://dali.gogol.net.cn/Article/details/gtdyzjrzst.html

openssl rand -hex 16
来源：http://dali.tian-w.cn/Article/details/gtvvksyxda.html

[R68] 计算文件校验值
来源：http://dali.zdqjudy.top/Article/details/gtaikrchrd.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.jinghuilouyu.cn/Article/details/gtgyhfdiyh.html

[R69] 生成随机密码
来源：http://dali.zhoulong.xyz/Article/details/gtazkzdldm.html

head -c 16 /dev/urandom | base64
来源：http://dali.sysykeji.top/Article/details/gttecpvigd.html

[R70] 时间戳与互转
来源：http://dali.yj20258.top/Article/details/gtyigrront.html

date +%s;  date -d @1700000000
来源：http://dali.zhiwuduotai.top/Article/details/gtimkaahhj.html

[R71] 日期格式化
来源：http://dali.aizwys.cn/Article/details/gtzlvybuot.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.jqgfzy.top/Article/details/gtsqnlkdzz.html

[R72] 等待端口就绪
来源：http://dali.jinqigufen.top/Article/details/gtaaqqutao.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.quarkkingdee.top/Article/details/gtkrmsakqt.html

[R73] 分割大日志
来源：http://dali.hywenlv.cn/Article/details/gtlzbuwnpj.html

split -l 1000 big.log part_
来源：http://dali.pengpengdd.cyou/Article/details/gtgvduwdch.html

[R74] 批量重命名
来源：http://dali.shanyushiyangtech.top/Article/details/gtwjboylue.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.yvedp.cn/Article/details/gtcqzaahvr.html

[R75] 导出环境变量
来源：http://dali.yj20258888.top/Article/details/gtdkalnzyi.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.guowangkeji.top/Article/details/gtszynazcw.html

[R76] 使用临时文件
来源：http://dali.jinqigufen.top/Article/details/gtphbphnxa.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.nanxinkj.top/Article/details/gtafcabrsp.html

[R77] 读取用户输入
来源：http://dali.yangfankeji.com/Article/details/gtpbksnyzo.html

read -rp "请输入: " ans
来源：http://dali.ybcxt.top/Article/details/gteybevjdy.html

[R78] 交互式菜单
来源：http://dali.c1oappe.top/Article/details/gtcyzjyxhb.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.ppjwa.cn/Article/details/gtzwqvjkpl.html

[R79] 解析命令行选项
来源：http://dali.zhiwuduotai.top/Article/details/gtnnnvphqx.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.havefunace.top/Article/details/gtfptsfjco.html

[R80] 查看脚本执行耗时
来源：http://dali.yangfankeji.com/Article/details/gthcipabja.html

time ./run.sh
来源：http://dali.yanxiufei.cn/Article/details/gtmjtbvtat.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtoiklhqkz.html

S. C / C++ 专题
来源：http://dali.yj20258888.top/Article/details/gtiezfzpkj.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtpezgydul.html

[S01] C：Hello World
来源：http://dali.shanyushiyangkeji.top/Article/details/gttpmyfote.html

#include <stdio.h>
来源：http://dali.chenzaomai.com/Article/details/gtmtlagsjt.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.tian-w.cn/Article/details/gtujxitfrr.html

[S02] C：变量与格式化输出
来源：http://dali.shuidangran.top/Article/details/gtjtnetbdk.html

int a = 10; printf("%d\n", a);
来源：http://dali.yanxiufei.cn/Article/details/gtyjgfpfho.html

[S03] C：读入整数
来源：http://dali.hysaishi.cn/Article/details/gtthmmrhtb.html

int x; scanf("%d", &x);
来源：http://dali.yangfankeji.com/Article/details/gtezrghxbv.html

[S04] C：字符串复制
来源：http://dali.hongshengwenyu.top/Article/details/gtgaofnupq.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.shzxlz.cn/Article/details/gtjawergxf.html

[S05] C：字符串长度
来源：http://dali.wangshuangyany.cn/Article/details/gtfqbyimub.html

strlen(s)
来源：http://dali.jlsjyb.cn/Article/details/gtcawkwwpf.html

[S06] C：字符串比较
来源：http://dali.gogol.net.cn/Article/details/gtvgjiajgc.html

strcmp(a, b) == 0
来源：http://dali.sysykeji.top/Article/details/gtrsrswyev.html

[S07] C：数组遍历求和
来源：http://dali.gotoacloud.top/Article/details/gtzhbdjzgc.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.yuxming.cn/Article/details/gtzteeqgne.html

[S08] C：动态内存分配与释放
来源：http://dali.snrcjt.cn/Article/details/gtexbzuvif.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.yvedp.cn/Article/details/gtzbtqaowu.html

[S09] C：结构体定义与初始化
来源：http://dali.hysaishi.cn/Article/details/gtarlnapmf.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.gaohongyu789.top/Article/details/gtnjgrsouv.html

[S10] C：指针与解引用
来源：http://dali.pengpengdd.cyou/Article/details/gtrdawyszf.html

int *p = &a;  *p = 5;
来源：http://dali.jinqigfzy.top/Article/details/gtxevmkysf.html

[S11] C：逐行读文件
来源：http://dali.haohaochexian.top/Article/details/gtsnmpgbmc.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.nanxinkj.top/Article/details/gtkrjrybwv.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.hfpthk.cn/Article/details/gtwvrlcnfm.html

fclose(f);
来源：http://dali.316326.xyz/Article/details/gtwpuhrczo.html

[S12] C：写文件
来源：http://dali.jinqigufen.top/Article/details/gtwugvlhrw.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.yueranfly.top/Article/details/gtcadrhnon.html

[S13] C：宏定义
来源：http://dali.gotoacloud.top/Article/details/gthsopdsls.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.tianlin.xyz/Article/details/gttebmwuzc.html

[S14] C：枚举
来源：http://dali.tian-w.cn/Article/details/gtekkregls.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.shuidangran.top/Article/details/gtrqanvawh.html

[S15] C：类型转换
来源：http://dali.jinqigufen.top/Article/details/gtazjbpqlc.html

(double) a / b
来源：http://dali.yongpay.top/Article/details/gtyayhyfwu.html

[S16] C：位操作置位
来源：http://dali.snrcjt.cn/Article/details/gthvgxjhgt.html

x |= (1 << 3);
来源：http://dali.yuanzhike.top/Article/details/gtrghbntnb.html

[S17] C：安全拼接字符串
来源：http://dali.yangfankeji.com/Article/details/gtlnyjxpai.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhengqikj.top/Article/details/gtuuidtggf.html

[S18] C：命令行参数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfebxahoh.html

int main(int argc, char **argv)
来源：http://dali.redwolf501.top/Article/details/gtmoytzqsd.html

[S19] C：快速排序
来源：http://dali.c1oappe.top/Article/details/gtbdyrzoqw.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.0kj1m.cn/Article/details/gtrhpliotc.html

[S20] C：二分查找
来源：http://dali.haohaochexian.top/Article/details/gthyhrxhiy.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.0kj1m.cn/Article/details/gtevyewrwz.html

[S21] C：字符类别判断
来源：http://dali.yvedp.cn/Article/details/gtttafiatp.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.chenzaomai.com/Article/details/gtikmvuzww.html

[S22] C：字符串转数字
来源：http://dali.ivvv.top/Article/details/gtvvyxoxgj.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.tianlin.xyz/Article/details/gtcyegsvvw.html

[S23] C：随机数
来源：http://dali.yuxming.cn/Article/details/gtxtjjlehd.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.daria6918.cn/Article/details/gtbmrhtuof.html

[S24] C：获取本地时间
来源：http://dali.svipenyu.cn/Article/details/gtayjlidbw.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.yongpay.top/Article/details/gtmavnhyje.html

[S25] C：内存拷贝
来源：http://dali.fzhhl.top/Article/details/gtctwcctui.html

memcpy(dst, src, n);
来源：http://dali.sufxvd.cn/Article/details/gtgwrjcseh.html

[S26] C：内存清零
来源：http://dali.sysykeji.top/Article/details/gthirbrwda.html

memset(a, 0, sizeof a);
来源：http://dali.yueranfly.top/Article/details/gtczxfydux.html

[S27] C：定义常量
来源：http://dali.xylfe.cn/Article/details/gtkrzbzhen.html

const double PI = 3.14159;
来源：http://dali.daria6918.cn/Article/details/gtyhvormng.html

[S28] C：静态变量
来源：http://dali.ydzc1.top/Article/details/gtagbhlrsb.html

static int counter = 0;
来源：http://dali.yj20258888.top/Article/details/gtymamdsgx.html

[S29] C：变参函数
来源：http://dali.yuanzhike.top/Article/details/gtkuwfyskv.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.yuxming.cn/Article/details/gtywvqezdd.html

[S30] C：头文件保护
来源：http://dali.pycfn.com/Article/details/gtdiwinitq.html

#ifndef X_H
来源：http://dali.bjfxy.top/Article/details/gtkmsmvsjr.html

#define X_H
来源：http://dali.cqqwz.cn/Article/details/gtswekzkdk.html

#endif
来源：http://dali.cashguo.top/Article/details/gtkwyjfzvm.html

[S31] C++：Hello World
来源：http://dali.guannengcc.top/Article/details/gtoddfpnya.html

#include <iostream>
来源：http://dali.gaohongyu789.top/Article/details/gtprallcta.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtibcdadik.html

[S32] C++：字符串
来源：http://dali.tian-w.cn/Article/details/gtvvjtivqr.html

std::string s = "hi";  s += "!";
来源：http://dali.yvedp.cn/Article/details/gtehammfec.html

[S33] C++：vector 增删
来源：http://dali.c1oappe.top/Article/details/gtctyyookm.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.yvedp.cn/Article/details/gtbivnndla.html

[S34] C++：遍历 vector
来源：http://dali.dianchejie.cn/Article/details/gtjmerofkh.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.kuanghao11.cn/Article/details/gtkcryecny.html

[S35] C++：map
来源：http://dali.tian-w.cn/Article/details/gtlqiopfzi.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.snrcjt.cn/Article/details/gtuaeefesi.html

[S36] C++：unordered_map
来源：http://dali.yongpay.top/Article/details/gthedttvdo.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.snrcjt.cn/Article/details/gtdelxxanb.html

[S37] C++：set
来源：http://dali.xuetiantiany.cn/Article/details/gtdsotjzca.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.birdmap.top/Article/details/gtitsvcfuv.html

[S38] C++：排序
来源：http://dali.birdmap.top/Article/details/gttufpoxyn.html

std::sort(v.begin(), v.end());
来源：http://dali.sweek.top/Article/details/gttuobrtdn.html

[S39] C++：自定义比较器排序
来源：http://dali.zhongyouzk.top/Article/details/gtnuzdpybf.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.yueranfly.top/Article/details/gtcrpqumss.html

[S40] C++：查找元素
来源：http://dali.jinqigfzy.top/Article/details/gttpeiwbts.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.jlsjyb.cn/Article/details/gtttxhwffp.html

[S41] C++：类与构造函数
来源：http://dali.meibo888.top/Article/details/gtzcdayjfw.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.ivvv.top/Article/details/gtxwmyynbi.html

[S42] C++：继承与虚函数
来源：http://dali.svipenyu.cn/Article/details/gtptqyuhcb.html

class B : public Base { public: void f() override {} };
来源：http://dali.ppjwa.cn/Article/details/gticbjsyuk.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gtyhnzrhdo.html

auto p = std::make_unique<int>(5);
来源：http://dali.zycfv.cn/Article/details/gtzdeydlkr.html

[S44] C++：引用传参
来源：http://dali.jinqigfzy.top/Article/details/gtkpnnmxlk.html

void inc(int &x) { ++x; }
来源：http://dali.hywenlv.cn/Article/details/gtpevwcbwb.html

[S45] C++：lambda
来源：http://dali.ywan-chungtsiang.top/Article/details/gttbvmtvqg.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.aizwys.cn/Article/details/gtpwihowcn.html

[S46] C++：函数模板
来源：http://dali.havefunace.top/Article/details/gtshgbnlzu.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.chenjidiqi.icu/Article/details/gtwpwmrssf.html

[S47] C++：结构化绑定遍历
来源：http://dali.yueranfly.top/Article/details/gtoaclavsj.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.yvedp.cn/Article/details/gtdqpeqmxt.html

[S48] C++：逐行读文件
来源：http://dali.zhixingplan.top/Article/details/gtfoikyseo.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.xziqi.cn/Article/details/gtktcxihpo.html

while (std::getline(in, line)) { }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtipylqewp.html

[S49] C++：写文件
来源：http://dali.jqgfzy.top/Article/details/gtzqxkwawl.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvowggiqq.html

[S50] C++：格式化数字
来源：http://dali.tian-w.cn/Article/details/gtanzetqtr.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.yonumen.top/Article/details/gtpwqbapwc.html

[S51] C++：显式类型转换
来源：http://dali.jinqigfzy.top/Article/details/gtlmncpebh.html

static_cast<double>(a) / b
来源：http://dali.xuanzx.com/Article/details/gtbzkcqudl.html

[S52] C++：const 与 noexcept
来源：http://dali.pycfn.com/Article/details/gtpngdnhja.html

int size() const noexcept { return n_; }
来源：http://dali.xuetiantiany.cn/Article/details/gtflhuqojy.html

[S53] C++：移动语义
来源：http://dali.nanxuanxn.top/Article/details/gthecgxmsd.html

std::vector<int> w = std::move(v);
来源：http://dali.quarkkingdee.top/Article/details/gtrjrzkcqv.html

[S54] C++：异常处理
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvpmzwxrl.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.chenjidiqi.icu/Article/details/gtaevhmlww.html

[S55] C++：结构化绑定
来源：http://dali.hongshengwenyu.top/Article/details/gtbbzumckt.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.yonumen.top/Article/details/gtrhnnwkrw.html

[S56] C++：optional
来源：http://dali.jiagoushi.top/Article/details/gtnplbsqow.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.xuanzx.com/Article/details/gtwzhswhmn.html

[S57] C++：编译期常量
来源：http://dali.nanxinkj.top/Article/details/gttjbqcbtx.html

constexpr int N = 10;
来源：http://dali.tian-w.cn/Article/details/gttkgcjosm.html

[S58] C++：命名空间
来源：http://dali.xuetiantiany.cn/Article/details/gtdujemwrf.html

namespace ns { int f() { return 1; } }
来源：http://dali.yuanzhike.top/Article/details/gtopfmitsw.html

[S59] C++：静态断言
来源：http://dali.ppjwa.cn/Article/details/gtpuzzmlfl.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.gaohongyu789.top/Article/details/gtqqcqstbr.html

[S60] C++：遍历并删除元素
来源：http://dali.hywenlv.cn/Article/details/gtvdblesqf.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.sysykeji.top/Article/details/gtwingtszt.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtabahdlof.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.sysykeji.top/Article/details/gtqsylgqnx.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtbexnzwbe.html

[T01] Kotlin：Hello World
来源：http://dali.xuanzx.com/Article/details/gtpmbhcgrz.html

println("Hello")
来源：http://dali.mhx1999.top/Article/details/gtzbbutnvq.html

[T02] Kotlin：变量
来源：http://dali.hnqzz.top/Article/details/gtkfrcimud.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzzdfrdxo.html

[T03] Kotlin：字符串模板
来源：http://dali.mhx1999.top/Article/details/gthjxovkqo.html

"值: $b"
来源：http://dali.yueranfly.top/Article/details/gtspnbcvnh.html

[T04] Kotlin：空安全
来源：http://dali.hongshengwenyu.top/Article/details/gtpzibrspz.html

val n: String? = null;  n?.length
来源：http://dali.tianlin.xyz/Article/details/gtnjmwvaqg.html

[T05] Kotlin：when 表达式
来源：http://dali.xziqi.cn/Article/details/gtfsermbto.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcjteqhju.html

[T06] Kotlin：集合映射
来源：http://dali.xziqi.cn/Article/details/gtyplskwii.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.gzhubu.top/Article/details/gtbgzsxmve.html

[T07] Kotlin：集合过滤
来源：http://dali.gaohongyu789.top/Article/details/gtzdqkyteo.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.chenlongwang.top/Article/details/gtaypdihog.html

[T08] Kotlin：数据类
来源：http://dali.hnxiangtu.top/Article/details/gtimjmguto.html

data class User(val name: String, val age: Int)
来源：http://dali.yuanzhike.top/Article/details/gtphzfagry.html

[T09] Kotlin：扩展函数
来源：http://dali.xylfe.cn/Article/details/gthylkpmig.html

fun String.exclaim() = this + "!"
来源：http://dali.gogol.net.cn/Article/details/gtpnwqnopi.html

[T10] Kotlin：默认参数
来源：http://dali.hnqzz.top/Article/details/gtypnyqayn.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.yj20258.top/Article/details/gtdhrxelwp.html

[T11] Kotlin：协程
来源：http://dali.zhixingplan.top/Article/details/gtwhvrmxmh.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zdqjudy.top/Article/details/gtpzozbhqq.html

[T12] Kotlin：解构声明
来源：http://dali.yj202588.top/Article/details/gthsstppgy.html

val (a, b) = Pair(1, 2)
来源：http://dali.iojbl.cn/Article/details/gtjpcepivi.html

[T13] Kotlin：只读 Map
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwbwxjbpn.html

val m = mapOf("a" to 1)
来源：http://dali.sweek.top/Article/details/gtscmqvfjx.html

[T14] Kotlin：循环
来源：http://dali.tian-w.cn/Article/details/gtyhhqvkpv.html

for (i in 1..10) println(i)
来源：http://dali.jinqigfzy.top/Article/details/gtqgxxeelq.html


<!-- 参考信息 -->