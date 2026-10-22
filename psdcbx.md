代发 wailian999

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.jinqigufen.top/Article/details/gtqxkygsej.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gtohpvzyhn.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.mhx1999.top/Article/details/gtjefwtofd.html

[R17] 数组定义与取值
来源：http://dali.iojbl.cn/Article/details/gteugpdgbk.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.jqgufenzy.top/Article/details/gtrnvgtqvw.html

[R18] 遍历数组
来源：http://dali.pengpengdd.cyou/Article/details/gtpcwkbmcj.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gtvrvksqwy.html

[R19] 数组长度
来源：http://dali.ppjwa.cn/Article/details/gtukuhgyvh.html

echo "${#arr[@]}"
来源：http://dali.xuanzx.com/Article/details/gtictncspf.html

[R20] 关联数组（字典）
来源：http://dali.zhongyouzk.top/Article/details/gtvqopivrm.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.svipenyu.cn/Article/details/gtdcglcyjg.html

[R21] 字符串长度
来源：http://dali.fengsongda.top/Article/details/gtqpnxlibu.html

echo "${#s}"
来源：http://dali.bjfxy.top/Article/details/gttapkzqiv.html

[R22] 截取子串
来源：http://dali.daxiang520.top/Article/details/gtwuxnukdk.html

echo "${s:0:5}"
来源：http://dali.shuidangran.top/Article/details/gtsnewkvwo.html

[R23] 字符串替换
来源：http://dali.yuxming.cn/Article/details/gtneunoxqc.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.9152youxi.cn/Article/details/gtbqddwlka.html

[R24] 大小写转换
来源：http://dali.gogol.net.cn/Article/details/gthfoeiupe.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gtfcqknqzr.html

[R25] 去后缀 / 去前缀
来源：http://dali.cdnleiting.top/Article/details/gtgsolnwzf.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.gaohongyu789.top/Article/details/gtccukfngk.html

[R26] 命令替换
来源：http://dali.fzhhl.top/Article/details/gtszndlujb.html

now=$(date +%F); echo "$now"
来源：http://dali.daria6918.cn/Article/details/gtkgiftudf.html

[R27] 算术展开
来源：http://dali.cheryme.top/Article/details/gtdakhshga.html

echo $((1 + 2 * 3))
来源：http://dali.shzxlz.cn/Article/details/gtqortarhl.html

[R28] 浮点运算
来源：http://dali.sysykeji.top/Article/details/gtmrckuyry.html

echo "scale=2; 10/3" | bc
来源：http://dali.andypj.xyz/Article/details/gthyqrqbbk.html

[R29] 定义函数
来源：http://dali.xuanzx.com/Article/details/gtloskwjnu.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.yueranfly.top/Article/details/gtxhjcblqp.html

[R30] 函数返回状态码
来源：http://dali.fengsongda.top/Article/details/gtjoytuiki.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.jinqigfzy.top/Article/details/gtknzbzlcm.html

[R31] 局部变量
来源：http://dali.shanyushiyangtech.top/Article/details/gtygachyhq.html

f() { local x=1; echo "$x"; }
来源：http://dali.hongshengwenyu.top/Article/details/gthfolgtzk.html

[R32] 参数个数校验
来源：http://dali.meibo888.top/Article/details/gtxonkswib.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.xylfe.cn/Article/details/gtqqgpdvmk.html

[R33] 捕获错误并提示行号
来源：http://dali.tanke756.top/Article/details/gtemrnittr.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.hongshengwenyu.top/Article/details/gtjqdvjadq.html

[R34] 退出时清理
来源：http://dali.tianlin.xyz/Article/details/gtgztbnpxq.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.meibo888.top/Article/details/gthxqcahmf.html

[R35] 后台执行并等待
来源：http://dali.tian-w.cn/Article/details/gtmedfhkgb.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.pycfn.com/Article/details/gttbdaqjgk.html

[R36] 并发执行多个任务
来源：http://dali.andypj.xyz/Article/details/gttujaqebq.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhongyouzk.top/Article/details/gttckvlnub.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gtvsadkgux.html

files=$(ls -1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtvtjojxmc.html

[R38] 管道串联
来源：http://dali.tanke756.top/Article/details/gtgsoumzyd.html

cat a.txt | grep -i error | wc -l
来源：http://dali.hywenlv.cn/Article/details/gthtwqfbdn.html

[R39] 重定向标准输出与错误
来源：http://dali.hfpthk.cn/Article/details/gtvjvkexhi.html

cmd > out.log 2>&1
来源：http://dali.yueranfly.top/Article/details/gtbwjlsawr.html

[R40] 追加写日志
来源：http://dali.zhoulong.xyz/Article/details/gtcinswqzh.html

echo "log" >> out.log
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtespvlhkr.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gtzywmzzuv.html

cmd >/dev/null 2>&1
来源：http://dali.xylfe.cn/Article/details/gttxmfvczn.html

[R42] 输入重定向
来源：http://dali.jlsjyb.cn/Article/details/gthgwsjobq.html

wc -l < a.txt
来源：http://dali.redwolf501.top/Article/details/gtllxlsyik.html

[R43] 按名字查找文件
来源：http://dali.vqdsnc.cn/Article/details/gtjgapqjid.html

find . -name "*.log" -type f
来源：http://dali.nanxuanxn.top/Article/details/gtwgwsnpvh.html

[R44] 按修改时间查找
来源：http://dali.yangfankeji.com/Article/details/gtgfprkmkk.html

find . -mtime -7 -type f
来源：http://dali.wangdashe.top/Article/details/gtlqsyzenc.html

[R45] 批量删除
来源：http://dali.feifeiyinyue.top/Article/details/gtdaekxnga.html

find . -name "*.tmp" -delete
来源：http://dali.yuxming.cn/Article/details/gtoyyuimgi.html

[R46] 递归替换文件内容
来源：http://dali.zhaomingkeji.xyz/Article/details/gtixkbzddi.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.iojbl.cn/Article/details/gtvsqbqzkt.html

[R47] sed 单行替换
来源：http://dali.yj20258888.top/Article/details/gtftphkpho.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.yueranfly.top/Article/details/gtdwosvpqr.html

[R48] awk 取指定列
来源：http://dali.jinqigfzy.top/Article/details/gtcrnvwkua.html

awk '{print $1, $3}' a.txt
来源：http://dali.cheryme.top/Article/details/gtitdpbgsh.html

[R49] awk 带条件
来源：http://dali.jqgufenzy.top/Article/details/gtvvyryrgo.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.fzhhl.top/Article/details/gtbqbjvzte.html

[R50] awk 求和
来源：http://dali.vqdsnc.cn/Article/details/gtyldurgap.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.yuanzhike.top/Article/details/gtvwcqaado.html

[R51] 排序去重取前几
来源：http://dali.shangyingyoupin.top/Article/details/gtyofnawav.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zycfv.cn/Article/details/gtojkesdph.html

[R52] 统计行数
来源：http://dali.nwbrower.top/Article/details/gtpsikotai.html

wc -l a.txt
来源：http://dali.tian-w.cn/Article/details/gtrjexrvme.html

[R53] 查看文件头与实时尾
来源：http://dali.gzhubu.top/Article/details/gtpmzgsohs.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.gogol.net.cn/Article/details/gtvfvgyrad.html

[R54] 比较两个文件
来源：http://dali.iojbl.cn/Article/details/gtuxgdejpg.html

diff a.txt b.txt
来源：http://dali.yonumen.top/Article/details/gtpofabprp.html

[R55] 压缩与解压
来源：http://dali.daxiang520.top/Article/details/gtgamnbwex.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.yvedp.cn/Article/details/gtzpwkmifl.html

[R56] 远程拷贝
来源：http://dali.hnxiangtu.top/Article/details/gtughedfsy.html

scp file user@host:/path/
来源：http://dali.yuanzhike.top/Article/details/gthbisiobz.html

[R57] 远程执行命令
来源：http://dali.ppjwa.cn/Article/details/gtvjoqigkp.html

ssh user@host 'uptime'
来源：http://dali.haohaochexian.top/Article/details/gtwuxozraf.html

[R58] 下载文件
来源：http://dali.tian-w.cn/Article/details/gtxccjtaeb.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.mhx1999.top/Article/details/gteezhrwip.html

[R59] 发 POST JSON
来源：http://dali.cdnleiting.top/Article/details/gtftpwjpui.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.xziqi.cn/Article/details/gtipyryqsd.html

[R60] 只看 HTTP 状态码
来源：http://dali.jqgfzy.top/Article/details/gtdpumnnfg.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.jinghuilouyu.cn/Article/details/gtjbzayqfh.html

[R61] 磁盘占用
来源：http://dali.ybcxt.top/Article/details/gtifgiizae.html

df -h;  du -sh *
来源：http://dali.svipenyu.cn/Article/details/gtaynohkwd.html

[R62] 找最占空间的文件
来源：http://dali.hnqzz.top/Article/details/gtxmdkncdx.html

du -ah . | sort -rh | head -10
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvvoxcwsl.html

[R63] 内存与进程
来源：http://dali.nanxinkj.top/Article/details/gtvoabzcyj.html

free -h;  ps aux | grep nginx
来源：http://dali.xylfe.cn/Article/details/gtadnxrlmr.html

[R64] 结束进程
来源：http://dali.kuanghao11.cn/Article/details/gteixwidxv.html

kill -9 $(pgrep -f app.py)
来源：http://dali.yangfankeji.com/Article/details/gtedcpitug.html

[R65] 查看端口占用
来源：http://dali.nanxuanxn.top/Article/details/gtttzlcsva.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.xylfe.cn/Article/details/gtbbmxajfv.html

[R66] 定时任务
来源：http://dali.wangshuangyany.cn/Article/details/gtjdhazybo.html

crontab -e;  crontab -l
来源：http://dali.hfpthk.cn/Article/details/gtaxgaeaba.html

[R67] 生成随机十六进制串
来源：http://dali.chenjidiqi.icu/Article/details/gtbfyotwpc.html

openssl rand -hex 16
来源：http://dali.chenjidiqi.icu/Article/details/gtxdbneusr.html

[R68] 计算文件校验值
来源：http://dali.jqgufenzy.top/Article/details/gtghxzghak.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.jianghu66.top/Article/details/gtbtlqpbtp.html

[R69] 生成随机密码
来源：http://dali.hysaishi.cn/Article/details/gtgbyafwkm.html

head -c 16 /dev/urandom | base64
来源：http://dali.snrcjt.cn/Article/details/gtmjyahksd.html

[R70] 时间戳与互转
来源：http://dali.feifeiyinyue.top/Article/details/gtunmjmyfb.html

date +%s;  date -d @1700000000
来源：http://dali.svipenyu.cn/Article/details/gtrpjbiekp.html

[R71] 日期格式化
来源：http://dali.zhixingplan.top/Article/details/gtgybljpmw.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.birdmap.top/Article/details/gtfpuvcljh.html

[R72] 等待端口就绪
来源：http://dali.sweek.top/Article/details/gtnsmxwwis.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.nwbrower.top/Article/details/gtzoxkgejz.html

[R73] 分割大日志
来源：http://dali.vqdsnc.cn/Article/details/gthemgquof.html

split -l 1000 big.log part_
来源：http://dali.shangyingyoupin.top/Article/details/gtshaxppao.html

[R74] 批量重命名
来源：http://dali.hfpthk.cn/Article/details/gtlfkinuns.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.jqgfzy.top/Article/details/gtmbxbpsil.html

[R75] 导出环境变量
来源：http://dali.yonumen.top/Article/details/gtgdwuljdx.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.jianghu66.top/Article/details/gtbsvlayhs.html

[R76] 使用临时文件
来源：http://dali.c1oappe.top/Article/details/gtsafaklnr.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.dianchejie.cn/Article/details/gtxvcxkebi.html

[R77] 读取用户输入
来源：http://dali.yongpay.top/Article/details/gtpjrrelas.html

read -rp "请输入: " ans
来源：http://dali.jinghuilouyu.cn/Article/details/gtuthbnida.html

[R78] 交互式菜单
来源：http://dali.jianghu66.top/Article/details/gtdbiowwpr.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.yueranfly.top/Article/details/gttehhaanh.html

[R79] 解析命令行选项
来源：http://dali.ybcxt.top/Article/details/gtvpjmetfb.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.xuetiantiany.cn/Article/details/gtoyiniyum.html

[R80] 查看脚本执行耗时
来源：http://dali.xylfe.cn/Article/details/gtszhoyciy.html

time ./run.sh
来源：http://dali.jiagoushi.top/Article/details/gtuhpdqvlv.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtszpsrgum.html

S. C / C++ 专题
来源：http://dali.zhixingplan.top/Article/details/gtxllyphre.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtfljtdxoe.html

[S01] C：Hello World
来源：http://dali.jqgfzy.top/Article/details/gtnyemodhm.html

#include <stdio.h>
来源：http://dali.jinqigufen.top/Article/details/gtbjejqbqm.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.shuidangran.top/Article/details/gtihhbjtsi.html

[S02] C：变量与格式化输出
来源：http://dali.mhx1999.top/Article/details/gtnkhmcovn.html

int a = 10; printf("%d\n", a);
来源：http://dali.iojbl.cn/Article/details/gtllwjieon.html

[S03] C：读入整数
来源：http://dali.xylfe.cn/Article/details/gtifmybccv.html

int x; scanf("%d", &x);
来源：http://dali.sufxvd.cn/Article/details/gtrpgquuta.html

[S04] C：字符串复制
来源：http://dali.zhaomingkeji.xyz/Article/details/gthvvjckgh.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.haohaochexian.top/Article/details/gtkdblewhx.html

[S05] C：字符串长度
来源：http://dali.ehwqpu.com/Article/details/gtsfqlegrg.html

strlen(s)
来源：http://dali.jiagoushi.top/Article/details/gtxdgxakhz.html

[S06] C：字符串比较
来源：http://dali.chenzaomai.com/Article/details/gtdvdaareq.html

strcmp(a, b) == 0
来源：http://dali.zhaomingkeji.xyz/Article/details/gtswisktvj.html

[S07] C：数组遍历求和
来源：http://dali.mhx1999.top/Article/details/gtmpkuroaz.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.birdmap.top/Article/details/gtqfixwsmv.html

[S08] C：动态内存分配与释放
来源：http://dali.ivvv.top/Article/details/gtuimscstr.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.havefunace.top/Article/details/gtekvxluyr.html

[S09] C：结构体定义与初始化
来源：http://dali.quarkkingdee.top/Article/details/gtckpldhsv.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.yanxiufei.cn/Article/details/gtapylpwtg.html

[S10] C：指针与解引用
来源：http://dali.ybcxt.top/Article/details/gtkzeaqudo.html

int *p = &a;  *p = 5;
来源：http://dali.guannengcc.top/Article/details/gtqxgjnqte.html

[S11] C：逐行读文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtarlksbal.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.yueranfly.top/Article/details/gtlhrowrqs.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.aizwys.cn/Article/details/gtqkeqdurc.html

fclose(f);
来源：http://dali.xuanzx.com/Article/details/gtwjztonun.html

[S12] C：写文件
来源：http://dali.nwbrower.top/Article/details/gtxfmzgxul.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.yj20258888.top/Article/details/gtcfvakoog.html

[S13] C：宏定义
来源：http://dali.zycfv.cn/Article/details/gtumqlvyis.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.gotoacloud.top/Article/details/gtxmckikvx.html

[S14] C：枚举
来源：http://dali.aibaodan.cn/Article/details/gtblpcrmqz.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.xinyue.icu/Article/details/gtbucypzti.html

[S15] C：类型转换
来源：http://dali.redwolf501.top/Article/details/gtdnsgitnh.html

(double) a / b
来源：http://dali.quarkkingdee.top/Article/details/gtoivukszg.html

[S16] C：位操作置位
来源：http://dali.316326.xyz/Article/details/gtojeigmti.html

x |= (1 << 3);
来源：http://dali.pengpengdd.cyou/Article/details/gttpsjmoay.html

[S17] C：安全拼接字符串
来源：http://dali.svipenyu.cn/Article/details/gtqxvadzud.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgrloruef.html

[S18] C：命令行参数
来源：http://dali.svipenyu.cn/Article/details/gtexbzsgqb.html

int main(int argc, char **argv)
来源：http://dali.zdqjudy.top/Article/details/gtvippdkgx.html

[S19] C：快速排序
来源：http://dali.0kj1m.cn/Article/details/gtcdzuyowj.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.redwolf501.top/Article/details/gtoqxbbqyp.html

[S20] C：二分查找
来源：http://dali.yuanzhike.top/Article/details/gtulclmkpl.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.sysykeji.top/Article/details/gtyztnqtqw.html

[S21] C：字符类别判断
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoppvlkcg.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.yj20258.top/Article/details/gtpbdemfce.html

[S22] C：字符串转数字
来源：http://dali.c1oappe.top/Article/details/gttzagiomo.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.yuxming.cn/Article/details/gtpfvxcvas.html

[S23] C：随机数
来源：http://dali.sysykeji.top/Article/details/gtwkmkvypi.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.cdnleiting.top/Article/details/gtekluxsfs.html

[S24] C：获取本地时间
来源：http://dali.ivvv.top/Article/details/gtjpnugpzx.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zycfv.cn/Article/details/gtfzjhofok.html

[S25] C：内存拷贝
来源：http://dali.yj20258.top/Article/details/gtqimlcmsm.html

memcpy(dst, src, n);
来源：http://dali.zhixingplan.top/Article/details/gtrcafhdgc.html

[S26] C：内存清零
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtksnbrrce.html

memset(a, 0, sizeof a);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwfotfjca.html

[S27] C：定义常量
来源：http://dali.ivvv.top/Article/details/gtwizuwtvd.html

const double PI = 3.14159;
来源：http://dali.kuanghao11.cn/Article/details/gtthtilfod.html

[S28] C：静态变量
来源：http://dali.gotoacloud.top/Article/details/gtcptbzeyb.html

static int counter = 0;
来源：http://dali.zycfv.cn/Article/details/gtpvyykmwf.html

[S29] C：变参函数
来源：http://dali.tianlin.xyz/Article/details/gtmzqpfqxk.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhiwuduotai.top/Article/details/gtfiafxsfw.html

[S30] C：头文件保护
来源：http://dali.feifeiyinyue.top/Article/details/gtwgdeslsv.html

#ifndef X_H
来源：http://dali.zycfv.cn/Article/details/gtbncjuutc.html

#define X_H
来源：http://dali.jinqigufen.top/Article/details/gtksacvpvk.html

#endif
来源：http://dali.yj202588.top/Article/details/gthfwounfs.html

[S31] C++：Hello World
来源：http://dali.shanyushiyangtech.top/Article/details/gtepbgknhe.html

#include <iostream>
来源：http://dali.0kj1m.cn/Article/details/gtbdinaogx.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.yanxiufei.cn/Article/details/gtjeynvhgt.html

[S32] C++：字符串
来源：http://dali.cucudq.cn/Article/details/gtbzwrimvt.html

std::string s = "hi";  s += "!";
来源：http://dali.yj202588.top/Article/details/gttybidcvz.html

[S33] C++：vector 增删
来源：http://dali.iojbl.cn/Article/details/gthacrrmjb.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.andypj.xyz/Article/details/gtrkjkgmvx.html

[S34] C++：遍历 vector
来源：http://dali.gogol.net.cn/Article/details/gtazwfrlot.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.cqqwz.cn/Article/details/gtqlzksvdb.html

[S35] C++：map
来源：http://dali.xuanzx.com/Article/details/gtjyjxwbue.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.kuanghao11.cn/Article/details/gtvwaekymw.html

[S36] C++：unordered_map
来源：http://dali.yuxming.cn/Article/details/gtiyevegza.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.iojbl.cn/Article/details/gtysazxkoc.html

[S37] C++：set
来源：http://dali.yj20258.top/Article/details/gtoytqolgw.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.mhx1999.top/Article/details/gtwvtbaigg.html

[S38] C++：排序
来源：http://dali.shangyingyoupin.top/Article/details/gtnqdtkxqq.html

std::sort(v.begin(), v.end());
来源：http://dali.shanyushiyangkeji.top/Article/details/gtckbtnlxa.html

[S39] C++：自定义比较器排序
来源：http://dali.gotoacloud.top/Article/details/gtheqakidb.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.yongpay.top/Article/details/gtnpszness.html

[S40] C++：查找元素
来源：http://dali.meibo888.top/Article/details/gtjaqwjvej.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.cqqwz.cn/Article/details/gttgbnxcfp.html

[S41] C++：类与构造函数
来源：http://dali.wangshuangyany.cn/Article/details/gtpnwguqhl.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.shanyushiyangtech.top/Article/details/gtninymvcc.html

[S42] C++：继承与虚函数
来源：http://dali.tanke756.top/Article/details/gtpsqmjswf.html

class B : public Base { public: void f() override {} };
来源：http://dali.havefunace.top/Article/details/gtqjxcubdh.html

[S43] C++：智能指针
来源：http://dali.yueranfly.top/Article/details/gtowiskcev.html

auto p = std::make_unique<int>(5);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfuxsixed.html

[S44] C++：引用传参
来源：http://dali.jyoumei.cn/Article/details/gtdqibbdhb.html

void inc(int &x) { ++x; }
来源：http://dali.jianghu66.top/Article/details/gtlsuwizee.html

[S45] C++：lambda
来源：http://dali.cqqwz.cn/Article/details/gtsbyyvcni.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.yj20258.top/Article/details/gtyccdwmco.html

[S46] C++：函数模板
来源：http://dali.xylfe.cn/Article/details/gtxczsacju.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.c1oappe.top/Article/details/gttbeatyvj.html

[S47] C++：结构化绑定遍历
来源：http://dali.cdnleiting.top/Article/details/gtqygltpaz.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.yueranfly.top/Article/details/gtwovsgnhw.html

[S48] C++：逐行读文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzhiyzvss.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.daria6918.cn/Article/details/gtdoaiynfx.html

while (std::getline(in, line)) { }
来源：http://dali.pengpengdd.cyou/Article/details/gtyjqobuiy.html

[S49] C++：写文件
来源：http://dali.xylfe.cn/Article/details/gtqcblduhz.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.ydzc1.top/Article/details/gtqwcigsnw.html

[S50] C++：格式化数字
来源：http://dali.zhiwuduotai.top/Article/details/gtgctncndc.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.hongshengwenyu.top/Article/details/gtryibyhie.html

[S51] C++：显式类型转换
来源：http://dali.xuetiantiany.cn/Article/details/gtjxjnjprx.html

static_cast<double>(a) / b
来源：http://dali.yj20258.top/Article/details/gtshvruwjn.html

[S52] C++：const 与 noexcept
来源：http://dali.yueranfly.top/Article/details/gtrmcexdys.html

int size() const noexcept { return n_; }
来源：http://dali.sxryk.cn/Article/details/gtzunydjgx.html

[S53] C++：移动语义
来源：http://dali.feifeiyinyue.top/Article/details/gtgfsjykpd.html

std::vector<int> w = std::move(v);
来源：http://dali.9152youxi.cn/Article/details/gtrkgshzlr.html

[S54] C++：异常处理
来源：http://dali.cdnleiting.top/Article/details/gtywffkner.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.yj202588.top/Article/details/gtmonescmv.html

[S55] C++：结构化绑定
来源：http://dali.yonumen.top/Article/details/gtidqarisx.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.cqqwz.cn/Article/details/gttndgwkat.html

[S56] C++：optional
来源：http://dali.daxiang520.top/Article/details/gtcgspfhcp.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.dianchejie.cn/Article/details/gtqdwhvfua.html

[S57] C++：编译期常量
来源：http://dali.sweek.top/Article/details/gthltyedhb.html

constexpr int N = 10;
来源：http://dali.zhengqikj.top/Article/details/gtmvlollod.html

[S58] C++：命名空间
来源：http://dali.bjfxy.top/Article/details/gtkkisrpeb.html

namespace ns { int f() { return 1; } }
来源：http://dali.hammf.cn/Article/details/gtzjqozauk.html

[S59] C++：静态断言
来源：http://dali.ydzc1.top/Article/details/gtqwhqrrwr.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.jinqigufen.top/Article/details/gtxiakogiu.html

[S60] C++：遍历并删除元素
来源：http://dali.yangfankeji.com/Article/details/gteerjohry.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.ydzc1.top/Article/details/gtrzevurdy.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtsibeohty.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.shanyushiyangtech.top/Article/details/gtdehhhsrt.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtfkyhjlul.html

[T01] Kotlin：Hello World
来源：http://dali.meibo888.top/Article/details/gtkelrskyg.html

println("Hello")
来源：http://dali.wangdashe.top/Article/details/gtvswmeudy.html

[T02] Kotlin：变量
来源：http://dali.yuxming.cn/Article/details/gtiqfpglux.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.daria6918.cn/Article/details/gtexpqqjhe.html

[T03] Kotlin：字符串模板
来源：http://dali.gaohongyu789.top/Article/details/gtugiuqbox.html

"值: $b"
来源：http://dali.jqgufenzy.top/Article/details/gtwixdipax.html

[T04] Kotlin：空安全
来源：http://dali.ybcxt.top/Article/details/gtdziqjjkb.html

val n: String? = null;  n?.length
来源：http://dali.hammf.cn/Article/details/gtazymxyys.html

[T05] Kotlin：when 表达式
来源：http://dali.hysaishi.cn/Article/details/gtqgnugumf.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.pengpengdd.cyou/Article/details/gtfurpegpg.html

[T06] Kotlin：集合映射
来源：http://dali.daria6918.cn/Article/details/gtijwfkyyz.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.ehwqpu.com/Article/details/gtmtyinegk.html

[T07] Kotlin：集合过滤
来源：http://dali.ydzc1.top/Article/details/gtcrekinbo.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhiwuduotai.top/Article/details/gtkhhxemqu.html

[T08] Kotlin：数据类
来源：http://dali.aizwys.cn/Article/details/gtluwwvcuu.html

data class User(val name: String, val age: Int)
来源：http://dali.hnxiangtu.top/Article/details/gtglnfgugb.html

[T09] Kotlin：扩展函数
来源：http://dali.sxryk.cn/Article/details/gtkvgepmfp.html

fun String.exclaim() = this + "!"
来源：http://dali.shzxlz.cn/Article/details/gtzayvluwx.html

[T10] Kotlin：默认参数
来源：http://dali.nanxuanxn.top/Article/details/gtxruuylnt.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.ivvv.top/Article/details/gtotednjiw.html

[T11] Kotlin：协程
来源：http://dali.hnxiangtu.top/Article/details/gtfuxufwto.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.yongpay.top/Article/details/gtsjegixgt.html

[T12] Kotlin：解构声明
来源：http://dali.sweek.top/Article/details/gtepsxoerm.html

val (a, b) = Pair(1, 2)
来源：http://dali.mhx1999.top/Article/details/gttubkdxcw.html

[T13] Kotlin：只读 Map
来源：http://dali.fzhhl.top/Article/details/gtdolfsokb.html

val m = mapOf("a" to 1)
来源：http://dali.mhx1999.top/Article/details/gtuzafmzaw.html

[T14] Kotlin：循环
来源：http://dali.jinqigfzy.top/Article/details/gtunsipsfk.html

for (i in 1..10) println(i)
来源：http://dali.jyoumei.cn/Article/details/gtclcskptk.html

[T15] Kotlin：接口
来源：http://dali.guannengcc.top/Article/details/gtttbsbrzd.html

interface Shape { fun area(): Double }
来源：http://dali.shuidangran.top/Article/details/gtuhudisxl.html

[T16] Swift：Hello World
来源：http://dali.yj20258.top/Article/details/gtwpudcziz.html

print("Hello")
来源：http://dali.gzhubu.top/Article/details/gtseswzgts.html

[T17] Swift：变量与常量
来源：http://dali.gaohongyu789.top/Article/details/gtmwhlkhwi.html

var a = 1;  let b = 2
来源：http://dali.ybcxt.top/Article/details/gtvzjetywm.html

[T18] Swift：字符串插值
来源：http://dali.xylfe.cn/Article/details/gtklckaaxj.html

"值: \(b)"
来源：http://dali.jinqigfzy.top/Article/details/gtbbmbsqqd.html


<!-- 参考信息 -->