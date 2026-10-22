代发 wailian999

esac
来源：http://dali.gzhubu.top/Article/details/gtqlwquimu.html

[R12] for 遍历文件
来源：http://dali.yanxiufei.cn/Article/details/gtwwyvdlme.html

for f in *.txt; do echo "$f"; done
来源：http://dali.guowangkeji.top/Article/details/gtlkqqrrap.html

[R13] for 计数循环
来源：http://dali.zhixingplan.top/Article/details/gtqqofoqad.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.birdmap.top/Article/details/gtbyzseyyr.html

[R14] C 风格 for
来源：http://dali.0kj1m.cn/Article/details/gtgmlfxjvi.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.cucudq.cn/Article/details/gtrkamjzqd.html

[R15] while 逐行读文件
来源：http://dali.ivvv.top/Article/details/gtlkudvzgs.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.gotoacloud.top/Article/details/gtrlyjelsi.html

[R16] until 等待条件
来源：http://dali.hywenlv.cn/Article/details/gtnslotcxk.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.tanke756.top/Article/details/gtcakqrcom.html

[R17] 数组定义与取值
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjhqllquv.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.nanxuanxn.top/Article/details/gthvajrxzy.html

[R18] 遍历数组
来源：http://dali.tianlin.xyz/Article/details/gtwhwndzjz.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.iojbl.cn/Article/details/gtqgyjptrc.html

[R19] 数组长度
来源：http://dali.ivvv.top/Article/details/gtukyzbiut.html

echo "${#arr[@]}"
来源：http://dali.fzhhl.top/Article/details/gtjpvksgiv.html

[R20] 关联数组（字典）
来源：http://dali.andypj.xyz/Article/details/gttmvrcnjt.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.gzhubu.top/Article/details/gtxmhhxpfq.html

[R21] 字符串长度
来源：http://dali.ivvv.top/Article/details/gtmywtehsj.html

echo "${#s}"
来源：http://dali.jinqigfzy.top/Article/details/gtwzgucdxg.html

[R22] 截取子串
来源：http://dali.jinqigfzy.top/Article/details/gtftjvaczq.html

echo "${s:0:5}"
来源：http://dali.0kj1m.cn/Article/details/gtkganbvqa.html

[R23] 字符串替换
来源：http://dali.smart0.xyz/Article/details/gtlfsodmhm.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.ybcxt.top/Article/details/gtnlpkobtk.html

[R24] 大小写转换
来源：http://dali.cqqwz.cn/Article/details/gtlwltsrhh.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.316326.xyz/Article/details/gtyffdrura.html

[R25] 去后缀 / 去前缀
来源：http://dali.ppjwa.cn/Article/details/gtbtbttncc.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.xziqi.cn/Article/details/gtcawlbksf.html

[R26] 命令替换
来源：http://dali.hammf.cn/Article/details/gtpobaddkg.html

now=$(date +%F); echo "$now"
来源：http://dali.zhongyouzk.top/Article/details/gtcotvljkb.html

[R27] 算术展开
来源：http://dali.ehwqpu.com/Article/details/gtghgeapqg.html

echo $((1 + 2 * 3))
来源：http://dali.316326.xyz/Article/details/gtvfjpdohd.html

[R28] 浮点运算
来源：http://dali.9152youxi.cn/Article/details/gtzdwjbxas.html

echo "scale=2; 10/3" | bc
来源：http://dali.dianchejie.cn/Article/details/gtxnnbyrnl.html

[R29] 定义函数
来源：http://dali.svipenyu.cn/Article/details/gtwnmdhwwk.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.cucudq.cn/Article/details/gtqmocqttg.html

[R30] 函数返回状态码
来源：http://dali.jinqigufen.top/Article/details/gtbvucphba.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.nanxinkj.top/Article/details/gtlgwdogmk.html

[R31] 局部变量
来源：http://dali.fzhhl.top/Article/details/gtlqggvhcj.html

f() { local x=1; echo "$x"; }
来源：http://dali.hongshengwenyu.top/Article/details/gtuipeenwb.html

[R32] 参数个数校验
来源：http://dali.hammf.cn/Article/details/gtyebawqgq.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.guowangkeji.top/Article/details/gtrreqikxn.html

[R33] 捕获错误并提示行号
来源：http://dali.nanxuanxn.top/Article/details/gtotlmmpib.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.xziqi.cn/Article/details/gtsarnoowj.html

[R34] 退出时清理
来源：http://dali.zdqjudy.top/Article/details/gtxfpuavcb.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zycfv.cn/Article/details/gtjcyjemtp.html

[R35] 后台执行并等待
来源：http://dali.smart0.xyz/Article/details/gtjesmetdi.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.ehwqpu.com/Article/details/gtioyvsarw.html

[R36] 并发执行多个任务
来源：http://dali.zhiwuduotai.top/Article/details/gtsemlizrf.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.ivvv.top/Article/details/gtvdcaglrq.html

[R37] 把输出赋给变量
来源：http://dali.fzhhl.top/Article/details/gtgnoqiifv.html

files=$(ls -1)
来源：http://dali.cashguo.top/Article/details/gtdebxqnuc.html

[R38] 管道串联
来源：http://dali.sweek.top/Article/details/gtzgwapmwf.html

cat a.txt | grep -i error | wc -l
来源：http://dali.gogol.net.cn/Article/details/gtrprwfjax.html

[R39] 重定向标准输出与错误
来源：http://dali.jiagoushi.top/Article/details/gtgbaszupw.html

cmd > out.log 2>&1
来源：http://dali.daria6918.cn/Article/details/gtrbitscyb.html

[R40] 追加写日志
来源：http://dali.9152youxi.cn/Article/details/gttxyzhkox.html

echo "log" >> out.log
来源：http://dali.jqgfzy.top/Article/details/gtomnerwdk.html

[R41] 丢弃输出
来源：http://dali.xziqi.cn/Article/details/gtrnrupnxi.html

cmd >/dev/null 2>&1
来源：http://dali.nanxuanxn.top/Article/details/gtfyymovgt.html

[R42] 输入重定向
来源：http://dali.yvedp.cn/Article/details/gtwrscbwid.html

wc -l < a.txt
来源：http://dali.cashguo.top/Article/details/gtzvizaqzw.html

[R43] 按名字查找文件
来源：http://dali.jlsjyb.cn/Article/details/gtpxpuxfkd.html

find . -name "*.log" -type f
来源：http://dali.smart0.xyz/Article/details/gtqqlorayr.html

[R44] 按修改时间查找
来源：http://dali.smart0.xyz/Article/details/gtqchtopew.html

find . -mtime -7 -type f
来源：http://dali.gzhubu.top/Article/details/gtdrtmvoxq.html

[R45] 批量删除
来源：http://dali.feifeiyinyue.top/Article/details/gtwqxgwgwc.html

find . -name "*.tmp" -delete
来源：http://dali.shangyingyoupin.top/Article/details/gtfpkdviio.html

[R46] 递归替换文件内容
来源：http://dali.jqgufenzy.top/Article/details/gtgzzleebi.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.pycfn.com/Article/details/gtrvfogjnb.html

[R47] sed 单行替换
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlkixwfvk.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.gzhubu.top/Article/details/gtqxojuzqe.html

[R48] awk 取指定列
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvjgsebyt.html

awk '{print $1, $3}' a.txt
来源：http://dali.9152youxi.cn/Article/details/gtocbfcust.html

[R49] awk 带条件
来源：http://dali.hfpthk.cn/Article/details/gtrdzqvmnl.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.yangfankeji.com/Article/details/gtopuxyrsb.html

[R50] awk 求和
来源：http://dali.gogol.net.cn/Article/details/gtqgltyekn.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.pengpengdd.cyou/Article/details/gtufxcshme.html

[R51] 排序去重取前几
来源：http://dali.yj202588.top/Article/details/gtilnsymao.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.gotoacloud.top/Article/details/gteozvryot.html

[R52] 统计行数
来源：http://dali.mhx1999.top/Article/details/gtnexbjxaa.html

wc -l a.txt
来源：http://dali.yueranfly.top/Article/details/gtvweqgdsc.html

[R53] 查看文件头与实时尾
来源：http://dali.iojbl.cn/Article/details/gtapfxdqjr.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.yonumen.top/Article/details/gtobikqggo.html

[R54] 比较两个文件
来源：http://dali.tanke756.top/Article/details/gthqfdgluc.html

diff a.txt b.txt
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjrdmdqok.html

[R55] 压缩与解压
来源：http://dali.hammf.cn/Article/details/gtyvwvlgry.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhongyouzk.top/Article/details/gtmfsazqje.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gtdatcbxpz.html

scp file user@host:/path/
来源：http://dali.yj20258888.top/Article/details/gtmeinyuzw.html

[R57] 远程执行命令
来源：http://dali.yj202588.top/Article/details/gtpmwbltfc.html

ssh user@host 'uptime'
来源：http://dali.zhongyouzk.top/Article/details/gtrtmfcznp.html

[R58] 下载文件
来源：http://dali.xziqi.cn/Article/details/gtxxqrvgki.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.shanyushiyangtech.top/Article/details/gtjdinyzyh.html

[R59] 发 POST JSON
来源：http://dali.yanxiufei.cn/Article/details/gtycbbcwpw.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.pycfn.com/Article/details/gtminxvuxg.html

[R60] 只看 HTTP 状态码
来源：http://dali.zycfv.cn/Article/details/gtyghvaayh.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.dashuyun.cn/Article/details/gtbeufyuvz.html

[R61] 磁盘占用
来源：http://dali.yuanzhike.top/Article/details/gthchcropf.html

df -h;  du -sh *
来源：http://dali.xuanzx.com/Article/details/gtfezqnitn.html

[R62] 找最占空间的文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqzgryddw.html

du -ah . | sort -rh | head -10
来源：http://dali.zhoulong.xyz/Article/details/gtetvluzcb.html

[R63] 内存与进程
来源：http://dali.jinqigfzy.top/Article/details/gtelydxgib.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gtrohkzqfq.html

[R64] 结束进程
来源：http://dali.yonumen.top/Article/details/gtahhzublt.html

kill -9 $(pgrep -f app.py)
来源：http://dali.xinyue.icu/Article/details/gtpqnqiccz.html

[R65] 查看端口占用
来源：http://dali.hfpthk.cn/Article/details/gtjfrnpovr.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.yonumen.top/Article/details/gtlyvdplnl.html

[R66] 定时任务
来源：http://dali.316326.xyz/Article/details/gtldcwtqpg.html

crontab -e;  crontab -l
来源：http://dali.yongpay.top/Article/details/gtteqrhmae.html

[R67] 生成随机十六进制串
来源：http://dali.jinghuilouyu.cn/Article/details/gtpxisiepv.html

openssl rand -hex 16
来源：http://dali.yongpay.top/Article/details/gtrvrqzaad.html

[R68] 计算文件校验值
来源：http://dali.iojbl.cn/Article/details/gtzjpmejxv.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.chenjidiqi.icu/Article/details/gtjbyxihzj.html

[R69] 生成随机密码
来源：http://dali.gotoacloud.top/Article/details/gtetaqbiwu.html

head -c 16 /dev/urandom | base64
来源：http://dali.xinyue.icu/Article/details/gtqnnqtbnh.html

[R70] 时间戳与互转
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfrbrnjlm.html

date +%s;  date -d @1700000000
来源：http://dali.gzhubu.top/Article/details/gtfzawavxs.html

[R71] 日期格式化
来源：http://dali.gogol.net.cn/Article/details/gtabeoqumi.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhoulong.xyz/Article/details/gtzbparhks.html

[R72] 等待端口就绪
来源：http://dali.fzhhl.top/Article/details/gtmizkpysd.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.daxiang520.top/Article/details/gtiliaqvmx.html

[R73] 分割大日志
来源：http://dali.jianghu66.top/Article/details/gtcjzwwguq.html

split -l 1000 big.log part_
来源：http://dali.sysykeji.top/Article/details/gtmdwgymzv.html

[R74] 批量重命名
来源：http://dali.sweek.top/Article/details/gtpdzptjmp.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.chenzaomai.com/Article/details/gtgeqhxtsh.html

[R75] 导出环境变量
来源：http://dali.jianghu66.top/Article/details/gtpzyigipd.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhoulong.xyz/Article/details/gtgzahgsyo.html

[R76] 使用临时文件
来源：http://dali.svipenyu.cn/Article/details/gtvmczqtic.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.dashuyun.cn/Article/details/gtgdilxkbu.html

[R77] 读取用户输入
来源：http://dali.yuanzhike.top/Article/details/gtyniakgnu.html

read -rp "请输入: " ans
来源：http://dali.yongpay.top/Article/details/gttgvbwimo.html

[R78] 交互式菜单
来源：http://dali.kuanghao11.cn/Article/details/gthrnxqwbh.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.sxryk.cn/Article/details/gtvbikcfem.html

[R79] 解析命令行选项
来源：http://dali.sxryk.cn/Article/details/gtkofjmkfz.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.jinyuanbaomall.cn/Article/details/gtagyveiyi.html

[R80] 查看脚本执行耗时
来源：http://dali.jianghu66.top/Article/details/gtcvykwyda.html

time ./run.sh
来源：http://dali.redwolf501.top/Article/details/gtbfwbcbmh.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtdzvyogzb.html

S. C / C++ 专题
来源：http://dali.wangdashe.top/Article/details/gthixiokot.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtjnjlgibf.html

[S01] C：Hello World
来源：http://dali.vqdsnc.cn/Article/details/gtygsnfcjv.html

#include <stdio.h>
来源：http://dali.jianghu66.top/Article/details/gthybxjxwv.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.hnxiangtu.top/Article/details/gtfgclzamb.html

[S02] C：变量与格式化输出
来源：http://dali.shzxlz.cn/Article/details/gtqfsftdyd.html

int a = 10; printf("%d\n", a);
来源：http://dali.snrcjt.cn/Article/details/gtkkryvpsv.html

[S03] C：读入整数
来源：http://dali.bjfxy.top/Article/details/gtsqnfxglx.html

int x; scanf("%d", &x);
来源：http://dali.yanxiufei.cn/Article/details/gtfhwpstzi.html

[S04] C：字符串复制
来源：http://dali.bjfxy.top/Article/details/gtckxgyhvy.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.hysaishi.cn/Article/details/gtoawqvqhj.html

[S05] C：字符串长度
来源：http://dali.yueranfly.top/Article/details/gtqyjvlvno.html

strlen(s)
来源：http://dali.nanxuanxn.top/Article/details/gtynddixlz.html

[S06] C：字符串比较
来源：http://dali.cashguo.top/Article/details/gtnttvtjex.html

strcmp(a, b) == 0
来源：http://dali.yuanzhike.top/Article/details/gtfmrzpmyu.html

[S07] C：数组遍历求和
来源：http://dali.zhengqikj.top/Article/details/gtinvsjese.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.jqgufenzy.top/Article/details/gtwwgsdkzc.html

[S08] C：动态内存分配与释放
来源：http://dali.ehwqpu.com/Article/details/gtadbxzncx.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.sufxvd.cn/Article/details/gtjdpcnnqv.html

[S09] C：结构体定义与初始化
来源：http://dali.shuidangran.top/Article/details/gtalpocakd.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.chenjidiqi.icu/Article/details/gttuiplxkp.html

[S10] C：指针与解引用
来源：http://dali.ybcxt.top/Article/details/gtrikxdxlp.html

int *p = &a;  *p = 5;
来源：http://dali.sufxvd.cn/Article/details/gtnhulqqby.html

[S11] C：逐行读文件
来源：http://dali.nanxinkj.top/Article/details/gtovrhunvo.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.ivvv.top/Article/details/gtjzozzrvw.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.quarkkingdee.top/Article/details/gtzimbbkyr.html

fclose(f);
来源：http://dali.smart0.xyz/Article/details/gtcazyvbyz.html

[S12] C：写文件
来源：http://dali.gotoacloud.top/Article/details/gtjgydwntf.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.cqqwz.cn/Article/details/gtjvouxkvz.html

[S13] C：宏定义
来源：http://dali.feifeiyinyue.top/Article/details/gtqzqghyle.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.jianghu66.top/Article/details/gttkhhtkeq.html

[S14] C：枚举
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnbnepyxd.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.birdmap.top/Article/details/gtmfjfipln.html

[S15] C：类型转换
来源：http://dali.aibaodan.cn/Article/details/gtyxnoulnc.html

(double) a / b
来源：http://dali.redwolf501.top/Article/details/gtxrhzhznf.html

[S16] C：位操作置位
来源：http://dali.guannengcc.top/Article/details/gtvftovgqz.html

x |= (1 << 3);
来源：http://dali.cdnleiting.top/Article/details/gtwgfatwuo.html

[S17] C：安全拼接字符串
来源：http://dali.daria6918.cn/Article/details/gtphirxebp.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.mhx1999.top/Article/details/gtmacliipa.html

[S18] C：命令行参数
来源：http://dali.wangshuangyany.cn/Article/details/gthvsyahms.html

int main(int argc, char **argv)
来源：http://dali.daxiang520.top/Article/details/gtrsrihuyx.html

[S19] C：快速排序
来源：http://dali.tianlin.xyz/Article/details/gtegrqmoor.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhixingplan.top/Article/details/gtjyqzdpsg.html

[S20] C：二分查找
来源：http://dali.chenjidiqi.icu/Article/details/gtobcrqpgj.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.dashuyun.cn/Article/details/gtpvpxyeau.html

[S21] C：字符类别判断
来源：http://dali.chenzaomai.com/Article/details/gtqxgxxmee.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.c1oappe.top/Article/details/gtqtblznio.html

[S22] C：字符串转数字
来源：http://dali.cheryme.top/Article/details/gtfipsemit.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.sysykeji.top/Article/details/gtoxsvzydd.html

[S23] C：随机数
来源：http://dali.sweek.top/Article/details/gtkluwbowm.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.chenjidiqi.icu/Article/details/gtuaqduyas.html

[S24] C：获取本地时间
来源：http://dali.gotoacloud.top/Article/details/gtkxrnhpcv.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.feifeiyinyue.top/Article/details/gtdhocikjc.html

[S25] C：内存拷贝
来源：http://dali.havefunace.top/Article/details/gtmwmsdepn.html

memcpy(dst, src, n);
来源：http://dali.sysykeji.top/Article/details/gtvtgqqnuj.html

[S26] C：内存清零
来源：http://dali.c1oappe.top/Article/details/gtjuahxtdk.html

memset(a, 0, sizeof a);
来源：http://dali.jlsjyb.cn/Article/details/gtzywbjqqf.html

[S27] C：定义常量
来源：http://dali.pengpengdd.cyou/Article/details/gtymcnlrvk.html

const double PI = 3.14159;
来源：http://dali.meibo888.top/Article/details/gtxqkiinji.html

[S28] C：静态变量
来源：http://dali.bjfxy.top/Article/details/gtfmhqergh.html

static int counter = 0;
来源：http://dali.gotoacloud.top/Article/details/gtrmftsuhw.html

[S29] C：变参函数
来源：http://dali.zhengqikj.top/Article/details/gtytzmjwva.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.gotoacloud.top/Article/details/gtwtbdsrhm.html

[S30] C：头文件保护
来源：http://dali.hnxiangtu.top/Article/details/gtlxmattpx.html

#ifndef X_H
来源：http://dali.zhiwuduotai.top/Article/details/gtyamejuma.html

#define X_H
来源：http://dali.fzhhl.top/Article/details/gtrzwxumln.html

#endif
来源：http://dali.redwolf501.top/Article/details/gtnnardsxm.html

[S31] C++：Hello World
来源：http://dali.xuetiantiany.cn/Article/details/gtzhzvwgyg.html

#include <iostream>
来源：http://dali.hysaishi.cn/Article/details/gtnluychwb.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.yuanzhike.top/Article/details/gttlocghfm.html

[S32] C++：字符串
来源：http://dali.xuanzx.com/Article/details/gthyhlnbhd.html

std::string s = "hi";  s += "!";
来源：http://dali.gogol.net.cn/Article/details/gtbsberxlp.html

[S33] C++：vector 增删
来源：http://dali.yj20258.top/Article/details/gtmeadzube.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gtrixejgzu.html

[S34] C++：遍历 vector
来源：http://dali.xziqi.cn/Article/details/gtcdndtxjy.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.shzxlz.cn/Article/details/gtstjopxpw.html

[S35] C++：map
来源：http://dali.yangfankeji.com/Article/details/gtwuqvubys.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.tianlin.xyz/Article/details/gtfkpbxxyl.html

[S36] C++：unordered_map
来源：http://dali.yongpay.top/Article/details/gtzpxoxetq.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.iojbl.cn/Article/details/gttkwuxrjd.html

[S37] C++：set
来源：http://dali.yuanzhike.top/Article/details/gtqtjriytn.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.9152youxi.cn/Article/details/gtqvajgwwl.html

[S38] C++：排序
来源：http://dali.ydzc1.top/Article/details/gtcybpmgmc.html

std::sort(v.begin(), v.end());
来源：http://dali.dianchejie.cn/Article/details/gtfkglhiza.html

[S39] C++：自定义比较器排序
来源：http://dali.jqgufenzy.top/Article/details/gtcyctvqod.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.iojbl.cn/Article/details/gtngnpodqh.html

[S40] C++：查找元素
来源：http://dali.aizwys.cn/Article/details/gtwyzeqtwm.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.xuetiantiany.cn/Article/details/gttqalcjxe.html

[S41] C++：类与构造函数
来源：http://dali.andypj.xyz/Article/details/gtxuhhbhhv.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.haohaochexian.top/Article/details/gtknqpsfik.html

[S42] C++：继承与虚函数
来源：http://dali.jlsjyb.cn/Article/details/gtifrohlyc.html

class B : public Base { public: void f() override {} };
来源：http://dali.smart0.xyz/Article/details/gtukadipoq.html

[S43] C++：智能指针
来源：http://dali.vqdsnc.cn/Article/details/gtkqmthqzb.html

auto p = std::make_unique<int>(5);
来源：http://dali.wangshuangyany.cn/Article/details/gtdcybtvgz.html

[S44] C++：引用传参
来源：http://dali.yuanzhike.top/Article/details/gtgpapxctg.html

void inc(int &x) { ++x; }
来源：http://dali.cucudq.cn/Article/details/gtsnvfyckh.html

[S45] C++：lambda
来源：http://dali.haohaochexian.top/Article/details/gtaqivglpe.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.gzhubu.top/Article/details/gtbiodtyim.html

[S46] C++：函数模板
来源：http://dali.aibaodan.cn/Article/details/gtthkbjzhs.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.smart0.xyz/Article/details/gtbqdxfkuv.html

[S47] C++：结构化绑定遍历
来源：http://dali.chenlongwang.top/Article/details/gtwqkaecxr.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.smart0.xyz/Article/details/gtjfvtdatn.html

[S48] C++：逐行读文件
来源：http://dali.sxryk.cn/Article/details/gtlswoqlkf.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.aizwys.cn/Article/details/gtrnqwpzdc.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gtgzjjesne.html

[S49] C++：写文件
来源：http://dali.zhengqikj.top/Article/details/gtgrqocxtb.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.vqdsnc.cn/Article/details/gtwasmsdhh.html

[S50] C++：格式化数字
来源：http://dali.nanxuanxn.top/Article/details/gtrxqnetwr.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhoulong.xyz/Article/details/gtrhadvaza.html

[S51] C++：显式类型转换
来源：http://dali.jianghu66.top/Article/details/gtkajihhrc.html

static_cast<double>(a) / b
来源：http://dali.gzhubu.top/Article/details/gtekxilzzd.html

[S52] C++：const 与 noexcept
来源：http://dali.jianghu66.top/Article/details/gtdjckyuuf.html

int size() const noexcept { return n_; }
来源：http://dali.0kj1m.cn/Article/details/gtkheauizw.html

[S53] C++：移动语义
来源：http://dali.pengpengdd.cyou/Article/details/gtlbgniouu.html

std::vector<int> w = std::move(v);
来源：http://dali.yanxiufei.cn/Article/details/gtdtqoqxkt.html

[S54] C++：异常处理
来源：http://dali.ydzc1.top/Article/details/gthhrgenzc.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.jqgufenzy.top/Article/details/gtzhkgctbp.html

[S55] C++：结构化绑定
来源：http://dali.zhengqikj.top/Article/details/gtklyfduyy.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhoulong.xyz/Article/details/gtgtcsdhyi.html

[S56] C++：optional
来源：http://dali.xziqi.cn/Article/details/gtufkiczgn.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.quarkkingdee.top/Article/details/gtjraiiedi.html

[S57] C++：编译期常量
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcwpetpyj.html

constexpr int N = 10;
来源：http://dali.yonumen.top/Article/details/gtctdnmlar.html

[S58] C++：命名空间
来源：http://dali.yj20258888.top/Article/details/gtvkazjdjz.html

namespace ns { int f() { return 1; } }
来源：http://dali.xziqi.cn/Article/details/gtsidjhsjx.html

[S59] C++：静态断言
来源：http://dali.shanyushiyangtech.top/Article/details/gtjibfddgm.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.xinyue.icu/Article/details/gtbwaqpuuc.html

[S60] C++：遍历并删除元素
来源：http://dali.jianghu66.top/Article/details/gtdftijvyf.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.bjfxy.top/Article/details/gthppbblig.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtfjvfggta.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.jinqigfzy.top/Article/details/gtrysjgugb.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtynnbsuhf.html

[T01] Kotlin：Hello World
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrvveeqpl.html

println("Hello")
来源：http://dali.xuetiantiany.cn/Article/details/gtezvdsinn.html

[T02] Kotlin：变量
来源：http://dali.fengsongda.top/Article/details/gtadxruptk.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.xziqi.cn/Article/details/gtownqsukf.html

[T03] Kotlin：字符串模板
来源：http://dali.jiagoushi.top/Article/details/gteueqjtxx.html

"值: $b"
来源：http://dali.hysaishi.cn/Article/details/gtdkzzchwv.html

[T04] Kotlin：空安全
来源：http://dali.0kj1m.cn/Article/details/gtytahgals.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gtqeeuwduh.html

[T05] Kotlin：when 表达式
来源：http://dali.aibaodan.cn/Article/details/gtzkwogzjr.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.tianlin.xyz/Article/details/gthwzsigxt.html

[T06] Kotlin：集合映射
来源：http://dali.yanxiufei.cn/Article/details/gtxfbfwjdr.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.snrcjt.cn/Article/details/gtqxbcavxd.html

[T07] Kotlin：集合过滤
来源：http://dali.sxryk.cn/Article/details/gtnaceefrc.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.vqdsnc.cn/Article/details/gtizgyqwjr.html

[T08] Kotlin：数据类
来源：http://dali.redwolf501.top/Article/details/gtmtvypszw.html

data class User(val name: String, val age: Int)
来源：http://dali.yueranfly.top/Article/details/gtxrhtzpzj.html

[T09] Kotlin：扩展函数
来源：http://dali.pycfn.com/Article/details/gtxlvxlghr.html

fun String.exclaim() = this + "!"
来源：http://dali.316326.xyz/Article/details/gteciteole.html

[T10] Kotlin：默认参数
来源：http://dali.ehwqpu.com/Article/details/gtxrockhdo.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.jqgfzy.top/Article/details/gtxaiikkfy.html

[T11] Kotlin：协程
来源：http://dali.sufxvd.cn/Article/details/gtdtevfovm.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.yueranfly.top/Article/details/gtqjelhehu.html

[T12] Kotlin：解构声明
来源：http://dali.iojbl.cn/Article/details/gtsyipmnlx.html

val (a, b) = Pair(1, 2)
来源：http://dali.xziqi.cn/Article/details/gtnqyirwfn.html

[T13] Kotlin：只读 Map
来源：http://dali.jiagoushi.top/Article/details/gtlvbikzhf.html

val m = mapOf("a" to 1)
来源：http://dali.hysaishi.cn/Article/details/gtwacgpxwq.html

[T14] Kotlin：循环
来源：http://dali.9152youxi.cn/Article/details/gtvwlopxqb.html

for (i in 1..10) println(i)
来源：http://dali.jyoumei.cn/Article/details/gtvndycsuq.html


<!-- 参考信息 -->