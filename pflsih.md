代发 wailian999

esac
来源：http://dali.xuetiantiany.cn/Article/details/gtyrnvepsb.html

[R12] for 遍历文件
来源：http://dali.gogol.net.cn/Article/details/gtntzvnzrj.html

for f in *.txt; do echo "$f"; done
来源：http://dali.9152youxi.cn/Article/details/gtiqmsykyv.html

[R13] for 计数循环
来源：http://dali.hysaishi.cn/Article/details/gtpfeoczzb.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.chenlongwang.top/Article/details/gtuasplqig.html

[R14] C 风格 for
来源：http://dali.jinyuanbaomall.cn/Article/details/gtamqpepzu.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.bjfxy.top/Article/details/gtfkarhenn.html

[R15] while 逐行读文件
来源：http://dali.ehwqpu.com/Article/details/gtymezdtsb.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.sxryk.cn/Article/details/gtygrzrmaz.html

[R16] until 等待条件
来源：http://dali.yj20258.top/Article/details/gtlasaugek.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.jlsjyb.cn/Article/details/gtnjdrhrah.html

[R17] 数组定义与取值
来源：http://dali.yueranfly.top/Article/details/gtlxoavrnv.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.fengsongda.top/Article/details/gtyguocnus.html

[R18] 遍历数组
来源：http://dali.yueranfly.top/Article/details/gtrqcidwwe.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.gaohongyu789.top/Article/details/gtwfmehvok.html

[R19] 数组长度
来源：http://dali.ydzc1.top/Article/details/gtyeclgfnz.html

echo "${#arr[@]}"
来源：http://dali.tianlin.xyz/Article/details/gtxclujzxh.html

[R20] 关联数组（字典）
来源：http://dali.sufxvd.cn/Article/details/gtfnvrdzaw.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.yj202588.top/Article/details/gtsyaotolc.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gtjsqljxvr.html

echo "${#s}"
来源：http://dali.aibaodan.cn/Article/details/gtiwkkouuj.html

[R22] 截取子串
来源：http://dali.cdnleiting.top/Article/details/gtapdcwtct.html

echo "${s:0:5}"
来源：http://dali.aibaodan.cn/Article/details/gtgqxubitj.html

[R23] 字符串替换
来源：http://dali.hnqzz.top/Article/details/gtsbcdmcpe.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.guowangkeji.top/Article/details/gtehmjezrt.html

[R24] 大小写转换
来源：http://dali.zhengqikj.top/Article/details/gtpzuvmevk.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.gogol.net.cn/Article/details/gtjtkqexnx.html

[R25] 去后缀 / 去前缀
来源：http://dali.hfpthk.cn/Article/details/gtcyuzwgge.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.feifeiyinyue.top/Article/details/gtqvidakww.html

[R26] 命令替换
来源：http://dali.yj20258.top/Article/details/gtowqebypi.html

now=$(date +%F); echo "$now"
来源：http://dali.hammf.cn/Article/details/gtshpjylhj.html

[R27] 算术展开
来源：http://dali.guannengcc.top/Article/details/gtvkkzskwt.html

echo $((1 + 2 * 3))
来源：http://dali.meibo888.top/Article/details/gtewrwcdlt.html

[R28] 浮点运算
来源：http://dali.jinghuilouyu.cn/Article/details/gtmntfkfgm.html

echo "scale=2; 10/3" | bc
来源：http://dali.jinqigfzy.top/Article/details/gtdalzmjof.html

[R29] 定义函数
来源：http://dali.meibo888.top/Article/details/gtruhqhhqn.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.cdnleiting.top/Article/details/gtcnrxfdzq.html

[R30] 函数返回状态码
来源：http://dali.sweek.top/Article/details/gtcenxvbit.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gtqellaqjr.html

[R31] 局部变量
来源：http://dali.zhongyouzk.top/Article/details/gtsxnbfsfg.html

f() { local x=1; echo "$x"; }
来源：http://dali.pycfn.com/Article/details/gttnhnrzdy.html

[R32] 参数个数校验
来源：http://dali.yuanzhike.top/Article/details/gttxhtcglg.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.hnqzz.top/Article/details/gtvsqfauva.html

[R33] 捕获错误并提示行号
来源：http://dali.sufxvd.cn/Article/details/gtdgnnygtn.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zycfv.cn/Article/details/gtquejzlzn.html

[R34] 退出时清理
来源：http://dali.wangshuangyany.cn/Article/details/gtdxxbmtlj.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.svipenyu.cn/Article/details/gtqohlyasa.html

[R35] 后台执行并等待
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnahrigpn.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.daria6918.cn/Article/details/gtfabvymct.html

[R36] 并发执行多个任务
来源：http://dali.yj202588.top/Article/details/gteqjctdkj.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.gotoacloud.top/Article/details/gtbrptxuoa.html

[R37] 把输出赋给变量
来源：http://dali.jqgufenzy.top/Article/details/gtqigamkva.html

files=$(ls -1)
来源：http://dali.jlsjyb.cn/Article/details/gtzorsqxds.html

[R38] 管道串联
来源：http://dali.ivvv.top/Article/details/gtwnderdcf.html

cat a.txt | grep -i error | wc -l
来源：http://dali.pengpengdd.cyou/Article/details/gtinzopkup.html

[R39] 重定向标准输出与错误
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxqamlyrb.html

cmd > out.log 2>&1
来源：http://dali.jqgufenzy.top/Article/details/gtsuqrltsx.html

[R40] 追加写日志
来源：http://dali.havefunace.top/Article/details/gtygdkhoae.html

echo "log" >> out.log
来源：http://dali.yj20258.top/Article/details/gtulvpxanz.html

[R41] 丢弃输出
来源：http://dali.xinyue.icu/Article/details/gtexsngffk.html

cmd >/dev/null 2>&1
来源：http://dali.pycfn.com/Article/details/gtblrlfteg.html

[R42] 输入重定向
来源：http://dali.zdqjudy.top/Article/details/gtkvbqrlwh.html

wc -l < a.txt
来源：http://dali.chenzaomai.com/Article/details/gttstzmetr.html

[R43] 按名字查找文件
来源：http://dali.cqqwz.cn/Article/details/gtsbhqgiuf.html

find . -name "*.log" -type f
来源：http://dali.fzhhl.top/Article/details/gthbuirszs.html

[R44] 按修改时间查找
来源：http://dali.shzxlz.cn/Article/details/gtzlbhwthz.html

find . -mtime -7 -type f
来源：http://dali.dashuyun.cn/Article/details/gtksmbsbwl.html

[R45] 批量删除
来源：http://dali.iojbl.cn/Article/details/gtjcecqykd.html

find . -name "*.tmp" -delete
来源：http://dali.ehwqpu.com/Article/details/gtrnpnzjwz.html

[R46] 递归替换文件内容
来源：http://dali.jqgfzy.top/Article/details/gtbpvxxlms.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.cheryme.top/Article/details/gtubdzbtdz.html

[R47] sed 单行替换
来源：http://dali.wangshuangyany.cn/Article/details/gtkdemsgrt.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.daxiang520.top/Article/details/gtloyhtbbj.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gtmbpivkxu.html

awk '{print $1, $3}' a.txt
来源：http://dali.tianlin.xyz/Article/details/gtepopiskp.html

[R49] awk 带条件
来源：http://dali.meibo888.top/Article/details/gtnictysvq.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.yuxming.cn/Article/details/gtyynlyjds.html

[R50] awk 求和
来源：http://dali.yanxiufei.cn/Article/details/gtyvaczpiv.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.tianlin.xyz/Article/details/gtpoggthlk.html

[R51] 排序去重取前几
来源：http://dali.yuanzhike.top/Article/details/gtbodxezrb.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhiwuduotai.top/Article/details/gtokjryhcy.html

[R52] 统计行数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtodsicncb.html

wc -l a.txt
来源：http://dali.pengpengdd.cyou/Article/details/gtehdpuinn.html

[R53] 查看文件头与实时尾
来源：http://dali.gogol.net.cn/Article/details/gtwjghdttk.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.smart0.xyz/Article/details/gthxjcrhwq.html

[R54] 比较两个文件
来源：http://dali.guannengcc.top/Article/details/gtgbzckmun.html

diff a.txt b.txt
来源：http://dali.jqgufenzy.top/Article/details/gtocsebonh.html

[R55] 压缩与解压
来源：http://dali.chenlongwang.top/Article/details/gttqxhviky.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.iojbl.cn/Article/details/gtiunwqlor.html

[R56] 远程拷贝
来源：http://dali.jqgufenzy.top/Article/details/gtkvljqabb.html

scp file user@host:/path/
来源：http://dali.ybcxt.top/Article/details/gtfcbfzgns.html

[R57] 远程执行命令
来源：http://dali.feifeiyinyue.top/Article/details/gtbkhnokkd.html

ssh user@host 'uptime'
来源：http://dali.shzxlz.cn/Article/details/gthmxgtgwn.html

[R58] 下载文件
来源：http://dali.yuanzhike.top/Article/details/gtqhtzykmq.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhongyouzk.top/Article/details/gtmgistftd.html

[R59] 发 POST JSON
来源：http://dali.quarkkingdee.top/Article/details/gtlwheusgw.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.sweek.top/Article/details/gtzcbkfasr.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhaomingkeji.xyz/Article/details/gtekvjvjke.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.ydzc1.top/Article/details/gtlcbcvriw.html

[R61] 磁盘占用
来源：http://dali.yuanzhike.top/Article/details/gtvsqgidwb.html

df -h;  du -sh *
来源：http://dali.hysaishi.cn/Article/details/gtahrllzef.html

[R62] 找最占空间的文件
来源：http://dali.fzhhl.top/Article/details/gtndwdcmlk.html

du -ah . | sort -rh | head -10
来源：http://dali.yvedp.cn/Article/details/gtjvktiloi.html

[R63] 内存与进程
来源：http://dali.chenzaomai.com/Article/details/gtsrxvlphp.html

free -h;  ps aux | grep nginx
来源：http://dali.yj20258.top/Article/details/gtpwmtffsi.html

[R64] 结束进程
来源：http://dali.sxryk.cn/Article/details/gtczbtrasm.html

kill -9 $(pgrep -f app.py)
来源：http://dali.cashguo.top/Article/details/gthliozzyi.html

[R65] 查看端口占用
来源：http://dali.shuidangran.top/Article/details/gtrjgkwlxt.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.yueranfly.top/Article/details/gtargmmnzh.html

[R66] 定时任务
来源：http://dali.zhoulong.xyz/Article/details/gtdjwvyvuf.html

crontab -e;  crontab -l
来源：http://dali.ywan-chungtsiang.top/Article/details/gtysgaheos.html

[R67] 生成随机十六进制串
来源：http://dali.jqgfzy.top/Article/details/gtlpjozscv.html

openssl rand -hex 16
来源：http://dali.sweek.top/Article/details/gtumldwsqk.html

[R68] 计算文件校验值
来源：http://dali.yangfankeji.com/Article/details/gtexragmku.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.dashuyun.cn/Article/details/gtrxkokunj.html

[R69] 生成随机密码
来源：http://dali.jinghuilouyu.cn/Article/details/gtszlrmcqg.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhiwuduotai.top/Article/details/gtximvtgfv.html

[R70] 时间戳与互转
来源：http://dali.hysaishi.cn/Article/details/gtyenplxsn.html

date +%s;  date -d @1700000000
来源：http://dali.xylfe.cn/Article/details/gtpldtguvz.html

[R71] 日期格式化
来源：http://dali.shanyushiyangkeji.top/Article/details/gtygbdoecg.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zdqjudy.top/Article/details/gtzguagiml.html

[R72] 等待端口就绪
来源：http://dali.gogol.net.cn/Article/details/gtvheofajm.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.sysykeji.top/Article/details/gtsuoesigt.html

[R73] 分割大日志
来源：http://dali.chenjidiqi.icu/Article/details/gtqiqifjwa.html

split -l 1000 big.log part_
来源：http://dali.9152youxi.cn/Article/details/gtxmdxzzad.html

[R74] 批量重命名
来源：http://dali.dashuyun.cn/Article/details/gtwjdcwmso.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.cashguo.top/Article/details/gtbumlomgj.html

[R75] 导出环境变量
来源：http://dali.316326.xyz/Article/details/gtnhogwyzt.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.jyoumei.cn/Article/details/gtnknizvst.html

[R76] 使用临时文件
来源：http://dali.iojbl.cn/Article/details/gtorlmhxrb.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.dianchejie.cn/Article/details/gtrzavbhru.html

[R77] 读取用户输入
来源：http://dali.aibaodan.cn/Article/details/gthujlrdcf.html

read -rp "请输入: " ans
来源：http://dali.sufxvd.cn/Article/details/gtaqdtijob.html

[R78] 交互式菜单
来源：http://dali.shuidangran.top/Article/details/gtkrlzmicz.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.c1oappe.top/Article/details/gtfdfleuor.html

[R79] 解析命令行选项
来源：http://dali.redwolf501.top/Article/details/gtpktwedby.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.nanxuanxn.top/Article/details/gtiwmcfsme.html

[R80] 查看脚本执行耗时
来源：http://dali.jiagoushi.top/Article/details/gthrnfupxs.html

time ./run.sh
来源：http://dali.cheryme.top/Article/details/gtxbcqnadw.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtwghwjfrl.html

S. C / C++ 专题
来源：http://dali.iojbl.cn/Article/details/gtzqsvdfrf.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtmjhqlrtf.html

[S01] C：Hello World
来源：http://dali.ehwqpu.com/Article/details/gtfugzywnf.html

#include <stdio.h>
来源：http://dali.cucudq.cn/Article/details/gtndpotkrb.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.xziqi.cn/Article/details/gtytddneuv.html

[S02] C：变量与格式化输出
来源：http://dali.sxryk.cn/Article/details/gtlmmljvly.html

int a = 10; printf("%d\n", a);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvzltepoy.html

[S03] C：读入整数
来源：http://dali.yj20258888.top/Article/details/gtmmjfdjiu.html

int x; scanf("%d", &x);
来源：http://dali.fzhhl.top/Article/details/gtbpidixal.html

[S04] C：字符串复制
来源：http://dali.shangyingyoupin.top/Article/details/gtuserykpe.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.jqgufenzy.top/Article/details/gtsoqtgmlu.html

[S05] C：字符串长度
来源：http://dali.feifeiyinyue.top/Article/details/gtsnrjtkek.html

strlen(s)
来源：http://dali.sweek.top/Article/details/gtzhzmfakw.html

[S06] C：字符串比较
来源：http://dali.yonumen.top/Article/details/gttcekuqxn.html

strcmp(a, b) == 0
来源：http://dali.andypj.xyz/Article/details/gtlcrrizmn.html

[S07] C：数组遍历求和
来源：http://dali.aibaodan.cn/Article/details/gtdpzedwjd.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.birdmap.top/Article/details/gtctrasxbk.html

[S08] C：动态内存分配与释放
来源：http://dali.hfpthk.cn/Article/details/gtkfwrxgyk.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.nanxuanxn.top/Article/details/gthrpydyje.html

[S09] C：结构体定义与初始化
来源：http://dali.xuetiantiany.cn/Article/details/gtakdnrqwm.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.daria6918.cn/Article/details/gtpxsxeemq.html

[S10] C：指针与解引用
来源：http://dali.hfpthk.cn/Article/details/gtvxhrfezu.html

int *p = &a;  *p = 5;
来源：http://dali.mhx1999.top/Article/details/gtyodwffne.html

[S11] C：逐行读文件
来源：http://dali.yvedp.cn/Article/details/gtedebihdg.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.hammf.cn/Article/details/gtihgwgyzt.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.ivvv.top/Article/details/gtlqrifpae.html

fclose(f);
来源：http://dali.cheryme.top/Article/details/gtbojpwdaq.html

[S12] C：写文件
来源：http://dali.hysaishi.cn/Article/details/gtllqnjvsp.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.shangyingyoupin.top/Article/details/gtaunzskgk.html

[S13] C：宏定义
来源：http://dali.cucudq.cn/Article/details/gtbsodrpfx.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.daria6918.cn/Article/details/gtcbcytvmh.html

[S14] C：枚举
来源：http://dali.xylfe.cn/Article/details/gtgimxxqsj.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.redwolf501.top/Article/details/gtgbesulur.html

[S15] C：类型转换
来源：http://dali.tanke756.top/Article/details/gttgpwvbiw.html

(double) a / b
来源：http://dali.yangfankeji.com/Article/details/gtpaxjnvkx.html

[S16] C：位操作置位
来源：http://dali.ivvv.top/Article/details/gttdglsjub.html

x |= (1 << 3);
来源：http://dali.dianchejie.cn/Article/details/gtwnsfqdnj.html

[S17] C：安全拼接字符串
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlkmxixbn.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhongyouzk.top/Article/details/gtnxsckrzj.html

[S18] C：命令行参数
来源：http://dali.nanxinkj.top/Article/details/gtcumbrrvj.html

int main(int argc, char **argv)
来源：http://dali.svipenyu.cn/Article/details/gtdjerjxhs.html

[S19] C：快速排序
来源：http://dali.meibo888.top/Article/details/gtjmidclca.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.hysaishi.cn/Article/details/gtixnhnanz.html

[S20] C：二分查找
来源：http://dali.yvedp.cn/Article/details/gtocbiniua.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.daria6918.cn/Article/details/gtjlyzpszw.html

[S21] C：字符类别判断
来源：http://dali.xylfe.cn/Article/details/gtrdjegiyx.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.iojbl.cn/Article/details/gtulotenad.html

[S22] C：字符串转数字
来源：http://dali.jiagoushi.top/Article/details/gtlsjtdrhp.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.ppjwa.cn/Article/details/gtidnvxtcs.html

[S23] C：随机数
来源：http://dali.meibo888.top/Article/details/gtuzwpbtci.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.bjfxy.top/Article/details/gtighygggc.html

[S24] C：获取本地时间
来源：http://dali.jinqigufen.top/Article/details/gtmsooqimv.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.jyoumei.cn/Article/details/gteckhmuob.html

[S25] C：内存拷贝
来源：http://dali.wangdashe.top/Article/details/gtqguwzezn.html

memcpy(dst, src, n);
来源：http://dali.cashguo.top/Article/details/gtqbsbafhu.html

[S26] C：内存清零
来源：http://dali.gotoacloud.top/Article/details/gtztiqbdly.html

memset(a, 0, sizeof a);
来源：http://dali.c1oappe.top/Article/details/gtghgknjtd.html

[S27] C：定义常量
来源：http://dali.ehwqpu.com/Article/details/gtbcmzdnpa.html

const double PI = 3.14159;
来源：http://dali.yongpay.top/Article/details/gtuwaxrdsc.html

[S28] C：静态变量
来源：http://dali.guowangkeji.top/Article/details/gttclntkxx.html

static int counter = 0;
来源：http://dali.yj202588.top/Article/details/gtlrmdbpxq.html

[S29] C：变参函数
来源：http://dali.guowangkeji.top/Article/details/gtymypknzw.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.meibo888.top/Article/details/gtodnsdczb.html

[S30] C：头文件保护
来源：http://dali.jqgfzy.top/Article/details/gtmmmurkhw.html

#ifndef X_H
来源：http://dali.ppjwa.cn/Article/details/gtisuueziq.html

#define X_H
来源：http://dali.sufxvd.cn/Article/details/gtbmzfqcql.html

#endif
来源：http://dali.jinqigufen.top/Article/details/gtrhfmenuy.html

[S31] C++：Hello World
来源：http://dali.yongpay.top/Article/details/gtqwjpfeon.html

#include <iostream>
来源：http://dali.sysykeji.top/Article/details/gtgisnuiun.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.nanxinkj.top/Article/details/gtglqmnrfx.html

[S32] C++：字符串
来源：http://dali.jqgfzy.top/Article/details/gtnrmonpsj.html

std::string s = "hi";  s += "!";
来源：http://dali.zhixingplan.top/Article/details/gtzjdftlqe.html

[S33] C++：vector 增删
来源：http://dali.xylfe.cn/Article/details/gttjlxvddf.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.guowangkeji.top/Article/details/gttfrcsbps.html

[S34] C++：遍历 vector
来源：http://dali.nwbrower.top/Article/details/gtgcrnvkdp.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.jianghu66.top/Article/details/gtgostffkc.html

[S35] C++：map
来源：http://dali.zhixingplan.top/Article/details/gtoulrolyb.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.xylfe.cn/Article/details/gtlkcsfvch.html

[S36] C++：unordered_map
来源：http://dali.ybcxt.top/Article/details/gtwsvgztqu.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.cqqwz.cn/Article/details/gttoqrtnzg.html

[S37] C++：set
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpfefegmk.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.meibo888.top/Article/details/gthtbfzdve.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gtnqftqeyq.html

std::sort(v.begin(), v.end());
来源：http://dali.yj20258888.top/Article/details/gtnfejllfd.html

[S39] C++：自定义比较器排序
来源：http://dali.jyoumei.cn/Article/details/gtrfmgkzga.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.daria6918.cn/Article/details/gtncaflqtw.html

[S40] C++：查找元素
来源：http://dali.zhoulong.xyz/Article/details/gtmrzlvmic.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.hongshengwenyu.top/Article/details/gtnmjmrhad.html

[S41] C++：类与构造函数
来源：http://dali.tian-w.cn/Article/details/gtuzxcbvpn.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.shangyingyoupin.top/Article/details/gtxudxinyy.html

[S42] C++：继承与虚函数
来源：http://dali.tanke756.top/Article/details/gtwywjilqg.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhongyouzk.top/Article/details/gtkgkvxhfl.html

[S43] C++：智能指针
来源：http://dali.vqdsnc.cn/Article/details/gtpbqxamxr.html

auto p = std::make_unique<int>(5);
来源：http://dali.kuanghao11.cn/Article/details/gttltndspw.html

[S44] C++：引用传参
来源：http://dali.jinqigufen.top/Article/details/gtoxnidbpy.html

void inc(int &x) { ++x; }
来源：http://dali.guannengcc.top/Article/details/gtoacszwic.html

[S45] C++：lambda
来源：http://dali.yongpay.top/Article/details/gtzcnmheqc.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.hfpthk.cn/Article/details/gtymussqpz.html

[S46] C++：函数模板
来源：http://dali.chenjidiqi.icu/Article/details/gtovqlmofo.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.fengsongda.top/Article/details/gthxhyldbi.html

[S47] C++：结构化绑定遍历
来源：http://dali.jqgfzy.top/Article/details/gtstyzwhpx.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.xylfe.cn/Article/details/gtyummlznp.html

[S48] C++：逐行读文件
来源：http://dali.snrcjt.cn/Article/details/gtfirvwtio.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.xuanzx.com/Article/details/gtfpiwemge.html

while (std::getline(in, line)) { }
来源：http://dali.sufxvd.cn/Article/details/gtvhwvfevr.html

[S49] C++：写文件
来源：http://dali.zhongyouzk.top/Article/details/gtjdyksvrl.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.cdnleiting.top/Article/details/gtkiisdbbv.html

[S50] C++：格式化数字
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdumloynp.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.cdnleiting.top/Article/details/gtqllgpzvn.html

[S51] C++：显式类型转换
来源：http://dali.wangdashe.top/Article/details/gtpnxkijvc.html

static_cast<double>(a) / b
来源：http://dali.gzhubu.top/Article/details/gtpauhodev.html

[S52] C++：const 与 noexcept
来源：http://dali.daria6918.cn/Article/details/gtctzizqum.html

int size() const noexcept { return n_; }
来源：http://dali.bjfxy.top/Article/details/gttqgeuzkh.html

[S53] C++：移动语义
来源：http://dali.zhengqikj.top/Article/details/gtzbvxhbvl.html

std::vector<int> w = std::move(v);
来源：http://dali.nwbrower.top/Article/details/gtcoadjrza.html

[S54] C++：异常处理
来源：http://dali.kuanghao11.cn/Article/details/gtfbodnxld.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.sxryk.cn/Article/details/gtslgkdjqu.html

[S55] C++：结构化绑定
来源：http://dali.yj202588.top/Article/details/gtsqzljvfl.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.ppjwa.cn/Article/details/gtyumvohyl.html

[S56] C++：optional
来源：http://dali.shanyushiyangtech.top/Article/details/gtdsdycfcc.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.nwbrower.top/Article/details/gtluiiaklt.html

[S57] C++：编译期常量
来源：http://dali.9152youxi.cn/Article/details/gtpeubypwg.html

constexpr int N = 10;
来源：http://dali.daxiang520.top/Article/details/gtxcyowwgj.html

[S58] C++：命名空间
来源：http://dali.shzxlz.cn/Article/details/gtjljeudag.html

namespace ns { int f() { return 1; } }
来源：http://dali.guannengcc.top/Article/details/gtweklcrlx.html

[S59] C++：静态断言
来源：http://dali.zycfv.cn/Article/details/gtqfvpaiko.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.bjfxy.top/Article/details/gtoowrjvyc.html

[S60] C++：遍历并删除元素
来源：http://dali.yj202588.top/Article/details/gtilomzepo.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.jinqigufen.top/Article/details/gtsrmtqvov.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtmnjiovny.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.wangdashe.top/Article/details/gtsxbfnjnd.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtorikkdmf.html

[T01] Kotlin：Hello World
来源：http://dali.tian-w.cn/Article/details/gtwdrkrjyh.html

println("Hello")
来源：http://dali.shangyingyoupin.top/Article/details/gtnqfcuwfi.html

[T02] Kotlin：变量
来源：http://dali.sweek.top/Article/details/gtsyvukqfe.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.pycfn.com/Article/details/gtheschfrj.html

[T03] Kotlin：字符串模板
来源：http://dali.yonumen.top/Article/details/gtmkuotvyp.html

"值: $b"
来源：http://dali.tanke756.top/Article/details/gtocinhtky.html

[T04] Kotlin：空安全
来源：http://dali.zhoulong.xyz/Article/details/gtdyrhvqru.html

val n: String? = null;  n?.length
来源：http://dali.yj202588.top/Article/details/gtzkfhteed.html

[T05] Kotlin：when 表达式
来源：http://dali.fengsongda.top/Article/details/gtovbfrews.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.0kj1m.cn/Article/details/gtgmwmdzsm.html

[T06] Kotlin：集合映射
来源：http://dali.cdnleiting.top/Article/details/gtqhxkqsjh.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.c1oappe.top/Article/details/gtoaumnnyi.html

[T07] Kotlin：集合过滤
来源：http://dali.xziqi.cn/Article/details/gtkxxeyemp.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.smart0.xyz/Article/details/gtbewvvcyz.html

[T08] Kotlin：数据类
来源：http://dali.tianlin.xyz/Article/details/gtrtopwhrh.html

data class User(val name: String, val age: Int)
来源：http://dali.pycfn.com/Article/details/gtlgjfpsin.html

[T09] Kotlin：扩展函数
来源：http://dali.pycfn.com/Article/details/gtwzjyrvus.html

fun String.exclaim() = this + "!"
来源：http://dali.zdqjudy.top/Article/details/gtikhekxnp.html

[T10] Kotlin：默认参数
来源：http://dali.hammf.cn/Article/details/gtjcqvrdso.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.kuanghao11.cn/Article/details/gtktpnngpg.html

[T11] Kotlin：协程
来源：http://dali.cheryme.top/Article/details/gtknubhfcw.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.ybcxt.top/Article/details/gtvshloqfi.html

[T12] Kotlin：解构声明
来源：http://dali.zhongyouzk.top/Article/details/gtjeuryeip.html

val (a, b) = Pair(1, 2)
来源：http://dali.9152youxi.cn/Article/details/gtwkvrumef.html

[T13] Kotlin：只读 Map
来源：http://dali.hfpthk.cn/Article/details/gtxjlosxff.html

val m = mapOf("a" to 1)
来源：http://dali.cqqwz.cn/Article/details/gteluwvkjx.html

[T14] Kotlin：循环
来源：http://dali.yangfankeji.com/Article/details/gtgmnckxvr.html

for (i in 1..10) println(i)
来源：http://dali.hysaishi.cn/Article/details/gtijnxvdyk.html


<!-- 参考信息 -->