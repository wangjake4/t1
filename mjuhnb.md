代发 wailian999

case "$1" in
来源：http://dali.chenzaomai.com/Article/details/gtcwbpeews.html

start) echo "启动" ;;
来源：http://dali.jianghu66.top/Article/details/gttishjjqc.html

stop)  echo "停止" ;;
来源：http://dali.sufxvd.cn/Article/details/gtzthwepwl.html

*)     echo "未知命令" ;;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtacdacvce.html

esac
来源：http://dali.fzhhl.top/Article/details/gtungkjnwu.html

[R12] for 遍历文件
来源：http://dali.ydzc1.top/Article/details/gtxrwxmhdk.html

for f in *.txt; do echo "$f"; done
来源：http://dali.sxryk.cn/Article/details/gtvkretqxh.html

[R13] for 计数循环
来源：http://dali.jiagoushi.top/Article/details/gttveqsfoj.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.mhx1999.top/Article/details/gtzluzotcx.html

[R14] C 风格 for
来源：http://dali.tianlin.xyz/Article/details/gtwsbdawgq.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.mhx1999.top/Article/details/gtfhsxixeq.html

[R15] while 逐行读文件
来源：http://dali.xinyue.icu/Article/details/gtledrpnxq.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.ehwqpu.com/Article/details/gtxelksmjq.html

[R16] until 等待条件
来源：http://dali.zdqjudy.top/Article/details/gtupnnhaqo.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.gogol.net.cn/Article/details/gtgnuqhlxp.html

[R17] 数组定义与取值
来源：http://dali.guowangkeji.top/Article/details/gtwyuddqty.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.xziqi.cn/Article/details/gtzurppimk.html

[R18] 遍历数组
来源：http://dali.hfpthk.cn/Article/details/gtfieodgrf.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.chenjidiqi.icu/Article/details/gtsdybcrvt.html

[R19] 数组长度
来源：http://dali.daxiang520.top/Article/details/gtzfgnerso.html

echo "${#arr[@]}"
来源：http://dali.gotoacloud.top/Article/details/gtgqmlbakg.html

[R20] 关联数组（字典）
来源：http://dali.yuxming.cn/Article/details/gtglxuztkw.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.jinqigfzy.top/Article/details/gtscvgyqwf.html

[R21] 字符串长度
来源：http://dali.svipenyu.cn/Article/details/gtyjjqdgxa.html

echo "${#s}"
来源：http://dali.wangdashe.top/Article/details/gtwbevxqvb.html

[R22] 截取子串
来源：http://dali.yuanzhike.top/Article/details/gtrzdihogm.html

echo "${s:0:5}"
来源：http://dali.nwbrower.top/Article/details/gtvbhtfoml.html

[R23] 字符串替换
来源：http://dali.cdnleiting.top/Article/details/gtgmdzduoa.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.yanxiufei.cn/Article/details/gtddtaigkn.html

[R24] 大小写转换
来源：http://dali.jqgfzy.top/Article/details/gtloyaaumz.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.shzxlz.cn/Article/details/gtcwcujras.html

[R25] 去后缀 / 去前缀
来源：http://dali.nanxuanxn.top/Article/details/gtxwsfqjdj.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.jianghu66.top/Article/details/gtnjupnrms.html

[R26] 命令替换
来源：http://dali.hywenlv.cn/Article/details/gthkzlbbfd.html

now=$(date +%F); echo "$now"
来源：http://dali.chenlongwang.top/Article/details/gttmzmhezr.html

[R27] 算术展开
来源：http://dali.yj202588.top/Article/details/gtjcsrmxbm.html

echo $((1 + 2 * 3))
来源：http://dali.yvedp.cn/Article/details/gtrfxpqbgo.html

[R28] 浮点运算
来源：http://dali.yanxiufei.cn/Article/details/gtkqnznima.html

echo "scale=2; 10/3" | bc
来源：http://dali.xuetiantiany.cn/Article/details/gtcyyybkml.html

[R29] 定义函数
来源：http://dali.gogol.net.cn/Article/details/gtwpoizknb.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.jqgfzy.top/Article/details/gttapqeaqa.html

[R30] 函数返回状态码
来源：http://dali.0kj1m.cn/Article/details/gthxpvgwvv.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.jlsjyb.cn/Article/details/gthonsbhga.html

[R31] 局部变量
来源：http://dali.nwbrower.top/Article/details/gtpibkrlug.html

f() { local x=1; echo "$x"; }
来源：http://dali.zycfv.cn/Article/details/gtpqksanwh.html

[R32] 参数个数校验
来源：http://dali.yongpay.top/Article/details/gtzaktznsg.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.gotoacloud.top/Article/details/gtsthsuvgb.html

[R33] 捕获错误并提示行号
来源：http://dali.9152youxi.cn/Article/details/gtseujefuc.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.havefunace.top/Article/details/gtqwnsyltq.html

[R34] 退出时清理
来源：http://dali.xuanzx.com/Article/details/gtqzsqlomk.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhengqikj.top/Article/details/gtzmotdszq.html

[R35] 后台执行并等待
来源：http://dali.xuanzx.com/Article/details/gtgcdyvqsp.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhoulong.xyz/Article/details/gtymrgoica.html

[R36] 并发执行多个任务
来源：http://dali.tian-w.cn/Article/details/gtsuwaonec.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.nanxinkj.top/Article/details/gtbhempbrx.html

[R37] 把输出赋给变量
来源：http://dali.zhoulong.xyz/Article/details/gtxxhldxti.html

files=$(ls -1)
来源：http://dali.hongshengwenyu.top/Article/details/gttbawawen.html

[R38] 管道串联
来源：http://dali.gogol.net.cn/Article/details/gtmvbwfwsn.html

cat a.txt | grep -i error | wc -l
来源：http://dali.dashuyun.cn/Article/details/gtylhxxmyb.html

[R39] 重定向标准输出与错误
来源：http://dali.nanxuanxn.top/Article/details/gtojjgcmed.html

cmd > out.log 2>&1
来源：http://dali.wangshuangyany.cn/Article/details/gtqbuyxwml.html

[R40] 追加写日志
来源：http://dali.jyoumei.cn/Article/details/gtygssejqq.html

echo "log" >> out.log
来源：http://dali.yuxming.cn/Article/details/gtswudpofi.html

[R41] 丢弃输出
来源：http://dali.fengsongda.top/Article/details/gtbxlzatqd.html

cmd >/dev/null 2>&1
来源：http://dali.shuidangran.top/Article/details/gtffuqiodo.html

[R42] 输入重定向
来源：http://dali.chenzaomai.com/Article/details/gtjwsowgfr.html

wc -l < a.txt
来源：http://dali.jyoumei.cn/Article/details/gtpyuxadih.html

[R43] 按名字查找文件
来源：http://dali.yongpay.top/Article/details/gtzviwniyo.html

find . -name "*.log" -type f
来源：http://dali.xinyue.icu/Article/details/gturajjfda.html

[R44] 按修改时间查找
来源：http://dali.gaohongyu789.top/Article/details/gtmlntssrd.html

find . -mtime -7 -type f
来源：http://dali.yj202588.top/Article/details/gtbxsrhcpf.html

[R45] 批量删除
来源：http://dali.zhengqikj.top/Article/details/gtvyeocdet.html

find . -name "*.tmp" -delete
来源：http://dali.hysaishi.cn/Article/details/gtaoezevmz.html

[R46] 递归替换文件内容
来源：http://dali.jiagoushi.top/Article/details/gtrificdlf.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.redwolf501.top/Article/details/gtbbgxxwso.html

[R47] sed 单行替换
来源：http://dali.hammf.cn/Article/details/gtmnghyapz.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.hysaishi.cn/Article/details/gtswgtmpoe.html

[R48] awk 取指定列
来源：http://dali.pengpengdd.cyou/Article/details/gtsgnfiicr.html

awk '{print $1, $3}' a.txt
来源：http://dali.tanke756.top/Article/details/gtefqwyfba.html

[R49] awk 带条件
来源：http://dali.jqgufenzy.top/Article/details/gtqbvfnhyw.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.hfpthk.cn/Article/details/gtebuvhegs.html

[R50] awk 求和
来源：http://dali.guowangkeji.top/Article/details/gtjepynzlq.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.yj202588.top/Article/details/gtxtwefawp.html

[R51] 排序去重取前几
来源：http://dali.yanxiufei.cn/Article/details/gtmmnhthwm.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.c1oappe.top/Article/details/gtxjklfars.html

[R52] 统计行数
来源：http://dali.vqdsnc.cn/Article/details/gtzenlghrm.html

wc -l a.txt
来源：http://dali.hfpthk.cn/Article/details/gtjsqrhzvw.html

[R53] 查看文件头与实时尾
来源：http://dali.cqqwz.cn/Article/details/gtghalhqoz.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.yj20258.top/Article/details/gtdgmflnzv.html

[R54] 比较两个文件
来源：http://dali.ivvv.top/Article/details/gttsldwdnl.html

diff a.txt b.txt
来源：http://dali.bjfxy.top/Article/details/gtdkmplsju.html

[R55] 压缩与解压
来源：http://dali.snrcjt.cn/Article/details/gtvezhsvla.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.svipenyu.cn/Article/details/gtgigmbvch.html

[R56] 远程拷贝
来源：http://dali.tanke756.top/Article/details/gtenfrvbdv.html

scp file user@host:/path/
来源：http://dali.yonumen.top/Article/details/gtuivetnwv.html

[R57] 远程执行命令
来源：http://dali.zhoulong.xyz/Article/details/gthfksveuh.html

ssh user@host 'uptime'
来源：http://dali.zdqjudy.top/Article/details/gtzauozffs.html

[R58] 下载文件
来源：http://dali.ydzc1.top/Article/details/gtpiqxuddl.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.jqgfzy.top/Article/details/gtkhgkkzis.html

[R59] 发 POST JSON
来源：http://dali.9152youxi.cn/Article/details/gthbexztdd.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.xuanzx.com/Article/details/gtkpbbkekr.html

[R60] 只看 HTTP 状态码
来源：http://dali.ybcxt.top/Article/details/gtbefdrbyr.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.gaohongyu789.top/Article/details/gthggigzfk.html

[R61] 磁盘占用
来源：http://dali.yj20258888.top/Article/details/gtsurouqdg.html

df -h;  du -sh *
来源：http://dali.xuetiantiany.cn/Article/details/gtbuismgse.html

[R62] 找最占空间的文件
来源：http://dali.hysaishi.cn/Article/details/gtmiissqrv.html

du -ah . | sort -rh | head -10
来源：http://dali.cqqwz.cn/Article/details/gtkppmhyav.html

[R63] 内存与进程
来源：http://dali.ywan-chungtsiang.top/Article/details/gthqflptnb.html

free -h;  ps aux | grep nginx
来源：http://dali.hysaishi.cn/Article/details/gtnwdkczvt.html

[R64] 结束进程
来源：http://dali.zhoulong.xyz/Article/details/gtgyqwsqnp.html

kill -9 $(pgrep -f app.py)
来源：http://dali.0kj1m.cn/Article/details/gtipklurud.html

[R65] 查看端口占用
来源：http://dali.yongpay.top/Article/details/gtnrbnsofv.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.jinqigfzy.top/Article/details/gtfjaypgjg.html

[R66] 定时任务
来源：http://dali.xziqi.cn/Article/details/gtinrfkpsi.html

crontab -e;  crontab -l
来源：http://dali.hfpthk.cn/Article/details/gthxyixbjh.html

[R67] 生成随机十六进制串
来源：http://dali.9152youxi.cn/Article/details/gtyfbycyev.html

openssl rand -hex 16
来源：http://dali.smart0.xyz/Article/details/gtumfaiugi.html

[R68] 计算文件校验值
来源：http://dali.yangfankeji.com/Article/details/gtaxhlgbhq.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.jinyuanbaomall.cn/Article/details/gtamngqnif.html

[R69] 生成随机密码
来源：http://dali.gaohongyu789.top/Article/details/gtlplzfqoz.html

head -c 16 /dev/urandom | base64
来源：http://dali.nanxinkj.top/Article/details/gtbqpsynno.html

[R70] 时间戳与互转
来源：http://dali.zhengqikj.top/Article/details/gtxoojqkhz.html

date +%s;  date -d @1700000000
来源：http://dali.hammf.cn/Article/details/gtqjbzmykc.html

[R71] 日期格式化
来源：http://dali.tanke756.top/Article/details/gtvnhvwspf.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.jinyuanbaomall.cn/Article/details/gthycjrxqb.html

[R72] 等待端口就绪
来源：http://dali.chenjidiqi.icu/Article/details/gtmymupody.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.xuetiantiany.cn/Article/details/gtdkiipvst.html

[R73] 分割大日志
来源：http://dali.cashguo.top/Article/details/gtalhfzswe.html

split -l 1000 big.log part_
来源：http://dali.guannengcc.top/Article/details/gtdsdwswfr.html

[R74] 批量重命名
来源：http://dali.cqqwz.cn/Article/details/gtlyksqpnv.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.shangyingyoupin.top/Article/details/gtjopaoarp.html

[R75] 导出环境变量
来源：http://dali.feifeiyinyue.top/Article/details/gtudcjeolj.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.iojbl.cn/Article/details/gtutlefaji.html

[R76] 使用临时文件
来源：http://dali.xuetiantiany.cn/Article/details/gtyelrywyy.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.shuidangran.top/Article/details/gtxtafzpri.html

[R77] 读取用户输入
来源：http://dali.jinqigfzy.top/Article/details/gtseuowibp.html

read -rp "请输入: " ans
来源：http://dali.jinghuilouyu.cn/Article/details/gtjxvjfmot.html

[R78] 交互式菜单
来源：http://dali.tanke756.top/Article/details/gtaicmxkaf.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.meibo888.top/Article/details/gtuvglfryn.html

[R79] 解析命令行选项
来源：http://dali.birdmap.top/Article/details/gtsvvwgfwb.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.316326.xyz/Article/details/gtkskgoarf.html

[R80] 查看脚本执行耗时
来源：http://dali.hnxiangtu.top/Article/details/gtzyfbstez.html

time ./run.sh
来源：http://dali.yueranfly.top/Article/details/gtybhgqtve.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtfelvcvoi.html

S. C / C++ 专题
来源：http://dali.bjfxy.top/Article/details/gtdyrucemc.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gttiahsrhe.html

[S01] C：Hello World
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdjpehxof.html

#include <stdio.h>
来源：http://dali.jinghuilouyu.cn/Article/details/gtfhnrmhlx.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.redwolf501.top/Article/details/gthtmgheev.html

[S02] C：变量与格式化输出
来源：http://dali.0kj1m.cn/Article/details/gtbmdgaljb.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gtbvhojmge.html

[S03] C：读入整数
来源：http://dali.fzhhl.top/Article/details/gtuwvsvooe.html

int x; scanf("%d", &x);
来源：http://dali.daxiang520.top/Article/details/gteiazubuh.html

[S04] C：字符串复制
来源：http://dali.cqqwz.cn/Article/details/gtbvrctoar.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.jiagoushi.top/Article/details/gtwrbqytmu.html

[S05] C：字符串长度
来源：http://dali.havefunace.top/Article/details/gthfrniera.html

strlen(s)
来源：http://dali.cucudq.cn/Article/details/gtrudsjsvm.html

[S06] C：字符串比较
来源：http://dali.zhengqikj.top/Article/details/gteigxryhy.html

strcmp(a, b) == 0
来源：http://dali.ehwqpu.com/Article/details/gttsvfytbb.html

[S07] C：数组遍历求和
来源：http://dali.9152youxi.cn/Article/details/gtaikgidox.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhiwuduotai.top/Article/details/gtfyebsxqr.html

[S08] C：动态内存分配与释放
来源：http://dali.nanxuanxn.top/Article/details/gtkxdlqffe.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.cdnleiting.top/Article/details/gtdaodcmhn.html

[S09] C：结构体定义与初始化
来源：http://dali.shzxlz.cn/Article/details/gtsgohedei.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.guowangkeji.top/Article/details/gtmoayvkog.html

[S10] C：指针与解引用
来源：http://dali.smart0.xyz/Article/details/gtjljtpjrs.html

int *p = &a;  *p = 5;
来源：http://dali.yongpay.top/Article/details/gtwkqfcpkm.html

[S11] C：逐行读文件
来源：http://dali.zdqjudy.top/Article/details/gtjmlxllxm.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.pengpengdd.cyou/Article/details/gtrsfrpwwo.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.jlsjyb.cn/Article/details/gtdwnmwjdb.html

fclose(f);
来源：http://dali.0kj1m.cn/Article/details/gthxwqpxeg.html

[S12] C：写文件
来源：http://dali.yvedp.cn/Article/details/gtuutrxbns.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.birdmap.top/Article/details/gtmtqeekod.html

[S13] C：宏定义
来源：http://dali.gotoacloud.top/Article/details/gtfwoxjrey.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.yueranfly.top/Article/details/gtciegwosz.html

[S14] C：枚举
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvcgkdjgu.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zycfv.cn/Article/details/gtrxutjcpz.html

[S15] C：类型转换
来源：http://dali.yuxming.cn/Article/details/gtvdlxwmyo.html

(double) a / b
来源：http://dali.guannengcc.top/Article/details/gtjamwhzni.html

[S16] C：位操作置位
来源：http://dali.chenjidiqi.icu/Article/details/gtzamzexmu.html

x |= (1 << 3);
来源：http://dali.hammf.cn/Article/details/gtsiykssay.html

[S17] C：安全拼接字符串
来源：http://dali.kuanghao11.cn/Article/details/gtnzmtgejh.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.shuidangran.top/Article/details/gtsivsskeg.html

[S18] C：命令行参数
来源：http://dali.ehwqpu.com/Article/details/gtlnlpjlnl.html

int main(int argc, char **argv)
来源：http://dali.c1oappe.top/Article/details/gtvyojnrxe.html

[S19] C：快速排序
来源：http://dali.feifeiyinyue.top/Article/details/gtuytcvhuf.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.gogol.net.cn/Article/details/gtnyzpmtuf.html

[S20] C：二分查找
来源：http://dali.xuanzx.com/Article/details/gtsmcyqwcd.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.sweek.top/Article/details/gtkmivfivn.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gtvkqpqbrb.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.ydzc1.top/Article/details/gtbgvpnsau.html

[S22] C：字符串转数字
来源：http://dali.sufxvd.cn/Article/details/gtornshbdf.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.pycfn.com/Article/details/gttezkbgkn.html

[S23] C：随机数
来源：http://dali.gzhubu.top/Article/details/gtjycqtidn.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.shzxlz.cn/Article/details/gtnlgmjrps.html

[S24] C：获取本地时间
来源：http://dali.c1oappe.top/Article/details/gtujfqnulv.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.jinqigufen.top/Article/details/gtyqvyseml.html

[S25] C：内存拷贝
来源：http://dali.jqgufenzy.top/Article/details/gtuhughwsg.html

memcpy(dst, src, n);
来源：http://dali.fengsongda.top/Article/details/gtvdosuptg.html

[S26] C：内存清零
来源：http://dali.gotoacloud.top/Article/details/gtinxlebyn.html

memset(a, 0, sizeof a);
来源：http://dali.yangfankeji.com/Article/details/gtuywtuypr.html

[S27] C：定义常量
来源：http://dali.yongpay.top/Article/details/gtjpimgtal.html

const double PI = 3.14159;
来源：http://dali.hammf.cn/Article/details/gtescnnera.html

[S28] C：静态变量
来源：http://dali.yj202588.top/Article/details/gtxrtydlie.html

static int counter = 0;
来源：http://dali.yj202588.top/Article/details/gtsbhpobtb.html

[S29] C：变参函数
来源：http://dali.ydzc1.top/Article/details/gtrvrscnzp.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gtvtfrocvy.html

[S30] C：头文件保护
来源：http://dali.yuxming.cn/Article/details/gtkyjuoida.html

#ifndef X_H
来源：http://dali.yj20258888.top/Article/details/gtjpqlxnhc.html

#define X_H
来源：http://dali.yuxming.cn/Article/details/gtspydxbxr.html

#endif
来源：http://dali.shuidangran.top/Article/details/gttedpqxpt.html

[S31] C++：Hello World
来源：http://dali.yj202588.top/Article/details/gtmixcnuhx.html

#include <iostream>
来源：http://dali.ivvv.top/Article/details/gtorrqqjas.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.9152youxi.cn/Article/details/gtjhqphklw.html

[S32] C++：字符串
来源：http://dali.sweek.top/Article/details/gtvnvtmjcn.html

std::string s = "hi";  s += "!";
来源：http://dali.meibo888.top/Article/details/gtnuvetzhu.html

[S33] C++：vector 增删
来源：http://dali.yuanzhike.top/Article/details/gtvjwfomhp.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.nanxuanxn.top/Article/details/gtoxgkcrtv.html

[S34] C++：遍历 vector
来源：http://dali.smart0.xyz/Article/details/gtuumjpsvm.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.gaohongyu789.top/Article/details/gtzjqsuxhy.html

[S35] C++：map
来源：http://dali.feifeiyinyue.top/Article/details/gtmjrifbmn.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zycfv.cn/Article/details/gtlzitdizi.html

[S36] C++：unordered_map
来源：http://dali.yuxming.cn/Article/details/gtpocdyhtq.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.nanxinkj.top/Article/details/gtjfjpofou.html

[S37] C++：set
来源：http://dali.guannengcc.top/Article/details/gtmzehbakq.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.xuetiantiany.cn/Article/details/gtvzxmjubd.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gtxzcqzzic.html

std::sort(v.begin(), v.end());
来源：http://dali.redwolf501.top/Article/details/gthwagnmej.html

[S39] C++：自定义比较器排序
来源：http://dali.shanyushiyangtech.top/Article/details/gtgxutrnim.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.xuetiantiany.cn/Article/details/gtkmefnqnn.html

[S40] C++：查找元素
来源：http://dali.yj20258.top/Article/details/gtrnbhjtmo.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkpmdbpqv.html

[S41] C++：类与构造函数
来源：http://dali.zhengqikj.top/Article/details/gtpxythxlm.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.yanxiufei.cn/Article/details/gtzocrzsby.html

[S42] C++：继承与虚函数
来源：http://dali.xziqi.cn/Article/details/gtgyfzwkhn.html

class B : public Base { public: void f() override {} };
来源：http://dali.sufxvd.cn/Article/details/gtoswbjgxd.html

[S43] C++：智能指针
来源：http://dali.zycfv.cn/Article/details/gtygdzmczr.html

auto p = std::make_unique<int>(5);
来源：http://dali.nanxuanxn.top/Article/details/gtlxmeykqv.html

[S44] C++：引用传参
来源：http://dali.daxiang520.top/Article/details/gtdziefldo.html

void inc(int &x) { ++x; }
来源：http://dali.cheryme.top/Article/details/gtimtiuuwt.html

[S45] C++：lambda
来源：http://dali.jyoumei.cn/Article/details/gtassdyhar.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.jqgufenzy.top/Article/details/gtlznaewto.html

[S46] C++：函数模板
来源：http://dali.birdmap.top/Article/details/gtjkszoqcu.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.sysykeji.top/Article/details/gtohxfdsiz.html

[S47] C++：结构化绑定遍历
来源：http://dali.iojbl.cn/Article/details/gthmzhdlro.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.yuanzhike.top/Article/details/gtrokrbfpb.html

[S48] C++：逐行读文件
来源：http://dali.gogol.net.cn/Article/details/gthknjnpzi.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.meibo888.top/Article/details/gtvvynqhth.html

while (std::getline(in, line)) { }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtymuovtmc.html

[S49] C++：写文件
来源：http://dali.redwolf501.top/Article/details/gtzplupjlf.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.shuidangran.top/Article/details/gtzzaxetyr.html

[S50] C++：格式化数字
来源：http://dali.smart0.xyz/Article/details/gtlqygggnr.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.yj202588.top/Article/details/gtipyqduaw.html

[S51] C++：显式类型转换
来源：http://dali.quarkkingdee.top/Article/details/gtwxtmgayo.html

static_cast<double>(a) / b
来源：http://dali.jinghuilouyu.cn/Article/details/gtyolrcgol.html

[S52] C++：const 与 noexcept
来源：http://dali.cucudq.cn/Article/details/gtkhjnqqhl.html

int size() const noexcept { return n_; }
来源：http://dali.jinqigufen.top/Article/details/gthvbkmzys.html

[S53] C++：移动语义
来源：http://dali.shanyushiyangtech.top/Article/details/gtjvwxtqmq.html

std::vector<int> w = std::move(v);
来源：http://dali.shanyushiyangtech.top/Article/details/gtcoyqidmt.html

[S54] C++：异常处理
来源：http://dali.andypj.xyz/Article/details/gttfeodhyi.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaytcqcah.html

[S55] C++：结构化绑定
来源：http://dali.smart0.xyz/Article/details/gteoetexef.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.yanxiufei.cn/Article/details/gtfmtmijmn.html

[S56] C++：optional
来源：http://dali.tian-w.cn/Article/details/gtnhrdwkgx.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yj202588.top/Article/details/gtjvhxkaoe.html

[S57] C++：编译期常量
来源：http://dali.yj202588.top/Article/details/gtxspfpten.html

constexpr int N = 10;
来源：http://dali.zdqjudy.top/Article/details/gtpivyzlpy.html

[S58] C++：命名空间
来源：http://dali.daxiang520.top/Article/details/gtpqvdovms.html

namespace ns { int f() { return 1; } }
来源：http://dali.gzhubu.top/Article/details/gttyxzyqdv.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gthvvontro.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.yueranfly.top/Article/details/gtjcrnihtu.html

[S60] C++：遍历并删除元素
来源：http://dali.jinqigfzy.top/Article/details/gtbzkhopao.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.yangfankeji.com/Article/details/gtesbldwrm.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtgvboliqi.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.shuidangran.top/Article/details/gtbxqdurgi.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtjtqqghbb.html

[T01] Kotlin：Hello World
来源：http://dali.smart0.xyz/Article/details/gtqmtlyywl.html

println("Hello")
来源：http://dali.snrcjt.cn/Article/details/gtfbcjwpdo.html

[T02] Kotlin：变量
来源：http://dali.sysykeji.top/Article/details/gtrdszvlyr.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.9152youxi.cn/Article/details/gtmkkrdvfw.html

[T03] Kotlin：字符串模板
来源：http://dali.cashguo.top/Article/details/gtxscwrvyn.html

"值: $b"
来源：http://dali.ydzc1.top/Article/details/gtawmllrlj.html

[T04] Kotlin：空安全
来源：http://dali.pycfn.com/Article/details/gthiqssoev.html

val n: String? = null;  n?.length
来源：http://dali.shzxlz.cn/Article/details/gtypfjmmuj.html

[T05] Kotlin：when 表达式
来源：http://dali.cheryme.top/Article/details/gtpjdhhdut.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.hfpthk.cn/Article/details/gtszkuvzvj.html

[T06] Kotlin：集合映射
来源：http://dali.svipenyu.cn/Article/details/gtyseivvaf.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.chenlongwang.top/Article/details/gtpsflwnvl.html

[T07] Kotlin：集合过滤
来源：http://dali.hnxiangtu.top/Article/details/gtouvsltav.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.mhx1999.top/Article/details/gtamewhxzh.html

[T08] Kotlin：数据类
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqlxgbaqm.html

data class User(val name: String, val age: Int)
来源：http://dali.9152youxi.cn/Article/details/gtfnsezwhf.html

[T09] Kotlin：扩展函数
来源：http://dali.dashuyun.cn/Article/details/gtdjgjnret.html

fun String.exclaim() = this + "!"
来源：http://dali.xylfe.cn/Article/details/gtsgfikxdr.html

[T10] Kotlin：默认参数
来源：http://dali.andypj.xyz/Article/details/gtxafnsief.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.yj20258.top/Article/details/gtgrckmjvc.html

[T11] Kotlin：协程
来源：http://dali.chenlongwang.top/Article/details/gtuuqznndq.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.yueranfly.top/Article/details/gtcmsvkbbv.html

[T12] Kotlin：解构声明
来源：http://dali.guowangkeji.top/Article/details/gtaronhwgn.html

val (a, b) = Pair(1, 2)
来源：http://dali.dashuyun.cn/Article/details/gttlbvtioi.html


<!-- 参考信息 -->