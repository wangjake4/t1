代发 wailian999

set -euo pipefail
来源：http://dali.pengpengdd.cyou/Article/details/gtzmqnfgdd.html

[R02] 变量赋值与使用
来源：http://dali.xuanzx.com/Article/details/gtuctpryaf.html

name="Tom"; echo "$name"
来源：http://dali.hnxiangtu.top/Article/details/gtoqyttzwv.html

[R03] 只读变量
来源：http://dali.fengsongda.top/Article/details/gtwzkmxerk.html

readonly PI=3.14
来源：http://dali.fzhhl.top/Article/details/gtmanalipn.html

[R04] 位置参数
来源：http://dali.haohaochexian.top/Article/details/gtgnxfmelo.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.yvedp.cn/Article/details/gtmvmpssti.html

[R05] 参数默认值
来源：http://dali.mhx1999.top/Article/details/gtklpecyey.html

name="${1:-default}"
来源：http://dali.zhengqikj.top/Article/details/gtkmemvmoo.html

[R06] 判断命令是否存在
来源：http://dali.haohaochexian.top/Article/details/gthmbecfzj.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.yj20258888.top/Article/details/gtwfzimpjw.html

[R07] if 判断文件
来源：http://dali.sxryk.cn/Article/details/gtiiyffgmf.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.shanyushiyangkeji.top/Article/details/gthhzwkehb.html

[R08] 数值比较
来源：http://dali.cucudq.cn/Article/details/gtniynmzar.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrmmteuez.html

[R09] 字符串比较
来源：http://dali.xinyue.icu/Article/details/gtdweedseu.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.ppjwa.cn/Article/details/gtzaqzqtdb.html

[R10] 正则匹配
来源：http://dali.hfpthk.cn/Article/details/gtounmxtjx.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.jiagoushi.top/Article/details/gttkmxvdqp.html

[R11] case 多分支
来源：http://dali.chenjidiqi.icu/Article/details/gtyjtpahro.html

case "$1" in
来源：http://dali.redwolf501.top/Article/details/gtycbzrdrx.html

start) echo "启动" ;;
来源：http://dali.smart0.xyz/Article/details/gtsoyrmxqq.html

stop)  echo "停止" ;;
来源：http://dali.shanyushiyangtech.top/Article/details/gtbyazzhgg.html

*)     echo "未知命令" ;;
来源：http://dali.iojbl.cn/Article/details/gtldkqgyvn.html

esac
来源：http://dali.svipenyu.cn/Article/details/gtugnbmqkl.html

[R12] for 遍历文件
来源：http://dali.bjfxy.top/Article/details/gtgfagwwdx.html

for f in *.txt; do echo "$f"; done
来源：http://dali.haohaochexian.top/Article/details/gttarhqgnp.html

[R13] for 计数循环
来源：http://dali.yongpay.top/Article/details/gtawfakdcc.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.yongpay.top/Article/details/gtebsyjuza.html

[R14] C 风格 for
来源：http://dali.xylfe.cn/Article/details/gtstwbcfuk.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.tianlin.xyz/Article/details/gthanbgbrf.html

[R15] while 逐行读文件
来源：http://dali.yvedp.cn/Article/details/gtfzhwhahf.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.hywenlv.cn/Article/details/gtwxkarkdd.html

[R16] until 等待条件
来源：http://dali.mhx1999.top/Article/details/gtmmzdhcnz.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.yj20258.top/Article/details/gtumipyuyl.html

[R17] 数组定义与取值
来源：http://dali.guowangkeji.top/Article/details/gterjhryza.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.xylfe.cn/Article/details/gtsrfeapen.html

[R18] 遍历数组
来源：http://dali.hywenlv.cn/Article/details/gtgiomclpw.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.sysykeji.top/Article/details/gtuzzyvzxp.html

[R19] 数组长度
来源：http://dali.dashuyun.cn/Article/details/gtanrsxddr.html

echo "${#arr[@]}"
来源：http://dali.jqgufenzy.top/Article/details/gtyhmmhuef.html

[R20] 关联数组（字典）
来源：http://dali.meibo888.top/Article/details/gtzxaikzgg.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.hnqzz.top/Article/details/gtkpgldcem.html

[R21] 字符串长度
来源：http://dali.hnqzz.top/Article/details/gtsgygxpkx.html

echo "${#s}"
来源：http://dali.ehwqpu.com/Article/details/gtpgpxutop.html

[R22] 截取子串
来源：http://dali.zhaomingkeji.xyz/Article/details/gttuizsffd.html

echo "${s:0:5}"
来源：http://dali.guannengcc.top/Article/details/gtipwoqqhw.html

[R23] 字符串替换
来源：http://dali.hongshengwenyu.top/Article/details/gtjjrahjpc.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.hywenlv.cn/Article/details/gtpyimlztp.html

[R24] 大小写转换
来源：http://dali.jlsjyb.cn/Article/details/gtnugfsmim.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.jlsjyb.cn/Article/details/gtbcqukpof.html

[R25] 去后缀 / 去前缀
来源：http://dali.nanxuanxn.top/Article/details/gtjwvseoqm.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.hysaishi.cn/Article/details/gthdnnvcgb.html

[R26] 命令替换
来源：http://dali.zhixingplan.top/Article/details/gtvngklfir.html

now=$(date +%F); echo "$now"
来源：http://dali.tianlin.xyz/Article/details/gtyncxsmuq.html

[R27] 算术展开
来源：http://dali.cqqwz.cn/Article/details/gtqfiqtagh.html

echo $((1 + 2 * 3))
来源：http://dali.yangfankeji.com/Article/details/gtleorbpgp.html

[R28] 浮点运算
来源：http://dali.yangfankeji.com/Article/details/gtprscbrdu.html

echo "scale=2; 10/3" | bc
来源：http://dali.dianchejie.cn/Article/details/gtteuthfhv.html

[R29] 定义函数
来源：http://dali.shzxlz.cn/Article/details/gtqhxvhxcy.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.jqgfzy.top/Article/details/gtbaihxnfs.html

[R30] 函数返回状态码
来源：http://dali.ehwqpu.com/Article/details/gtmwpalumg.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.yvedp.cn/Article/details/gthwsaddcp.html

[R31] 局部变量
来源：http://dali.jinghuilouyu.cn/Article/details/gtshivjazk.html

f() { local x=1; echo "$x"; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtydlcanru.html

[R32] 参数个数校验
来源：http://dali.chenjidiqi.icu/Article/details/gttbhfvygb.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.hysaishi.cn/Article/details/gttoepotdo.html

[R33] 捕获错误并提示行号
来源：http://dali.ywan-chungtsiang.top/Article/details/gtskvxnjka.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.xuanzx.com/Article/details/gtcynejpvc.html

[R34] 退出时清理
来源：http://dali.xziqi.cn/Article/details/gtushwxlvp.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.yangfankeji.com/Article/details/gtixouixoc.html

[R35] 后台执行并等待
来源：http://dali.yj20258888.top/Article/details/gtznrzutnt.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.daria6918.cn/Article/details/gtqybdilkh.html

[R36] 并发执行多个任务
来源：http://dali.sufxvd.cn/Article/details/gtdchoqggn.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.fengsongda.top/Article/details/gtvkjktbkq.html

[R37] 把输出赋给变量
来源：http://dali.nanxuanxn.top/Article/details/gtzuensxpw.html

files=$(ls -1)
来源：http://dali.snrcjt.cn/Article/details/gtgnwgatvn.html

[R38] 管道串联
来源：http://dali.jqgfzy.top/Article/details/gtbhtmhwha.html

cat a.txt | grep -i error | wc -l
来源：http://dali.ehwqpu.com/Article/details/gtjlgjxuos.html

[R39] 重定向标准输出与错误
来源：http://dali.svipenyu.cn/Article/details/gtzreahgms.html

cmd > out.log 2>&1
来源：http://dali.chenzaomai.com/Article/details/gtkjsvrhjr.html

[R40] 追加写日志
来源：http://dali.cheryme.top/Article/details/gticudjnuj.html

echo "log" >> out.log
来源：http://dali.kuanghao11.cn/Article/details/gteqegdyvm.html

[R41] 丢弃输出
来源：http://dali.redwolf501.top/Article/details/gtbytcteox.html

cmd >/dev/null 2>&1
来源：http://dali.fzhhl.top/Article/details/gtqhtgykoc.html

[R42] 输入重定向
来源：http://dali.feifeiyinyue.top/Article/details/gteoxwuruc.html

wc -l < a.txt
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjoiivxnq.html

[R43] 按名字查找文件
来源：http://dali.yvedp.cn/Article/details/gtivlvzekt.html

find . -name "*.log" -type f
来源：http://dali.c1oappe.top/Article/details/gtavixabjf.html

[R44] 按修改时间查找
来源：http://dali.hfpthk.cn/Article/details/gttjdqmkqq.html

find . -mtime -7 -type f
来源：http://dali.daxiang520.top/Article/details/gtqedhgbih.html

[R45] 批量删除
来源：http://dali.aizwys.cn/Article/details/gtipypyefw.html

find . -name "*.tmp" -delete
来源：http://dali.ybcxt.top/Article/details/gtnsabihun.html

[R46] 递归替换文件内容
来源：http://dali.xuanzx.com/Article/details/gtlblctvis.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.shanyushiyangtech.top/Article/details/gtnyhcyhkr.html

[R47] sed 单行替换
来源：http://dali.jqgfzy.top/Article/details/gtoynwumkc.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.mhx1999.top/Article/details/gtkqmemdvk.html

[R48] awk 取指定列
来源：http://dali.hnxiangtu.top/Article/details/gtesvqatdz.html

awk '{print $1, $3}' a.txt
来源：http://dali.guowangkeji.top/Article/details/gtowguoxqo.html

[R49] awk 带条件
来源：http://dali.ppjwa.cn/Article/details/gtumgmyevj.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.cqqwz.cn/Article/details/gtkymsepzu.html

[R50] awk 求和
来源：http://dali.hammf.cn/Article/details/gtwicytqzx.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.tianlin.xyz/Article/details/gtgnoqqyfr.html

[R51] 排序去重取前几
来源：http://dali.kuanghao11.cn/Article/details/gtvqjvpiiv.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.wangshuangyany.cn/Article/details/gtcboqznxn.html

[R52] 统计行数
来源：http://dali.yvedp.cn/Article/details/gtgtpvgilb.html

wc -l a.txt
来源：http://dali.gotoacloud.top/Article/details/gtyoicsonb.html

[R53] 查看文件头与实时尾
来源：http://dali.xuetiantiany.cn/Article/details/gtyixbgqhl.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.jqgfzy.top/Article/details/gtdapkbkog.html

[R54] 比较两个文件
来源：http://dali.ppjwa.cn/Article/details/gthppggbcb.html

diff a.txt b.txt
来源：http://dali.shzxlz.cn/Article/details/gtvgyoxdqi.html

[R55] 压缩与解压
来源：http://dali.zhixingplan.top/Article/details/gtysazmpvm.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.fzhhl.top/Article/details/gtcgpeqjyp.html

[R56] 远程拷贝
来源：http://dali.andypj.xyz/Article/details/gtnmysqbcs.html

scp file user@host:/path/
来源：http://dali.chenjidiqi.icu/Article/details/gtxlvldavu.html

[R57] 远程执行命令
来源：http://dali.chenzaomai.com/Article/details/gtiavjtlwk.html

ssh user@host 'uptime'
来源：http://dali.xuetiantiany.cn/Article/details/gtuwjkpcna.html

[R58] 下载文件
来源：http://dali.ydzc1.top/Article/details/gtpdjrnrgk.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.cqqwz.cn/Article/details/gtdadsqpns.html

[R59] 发 POST JSON
来源：http://dali.9152youxi.cn/Article/details/gtgowsdagc.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gtdiprhbpt.html

[R60] 只看 HTTP 状态码
来源：http://dali.yonumen.top/Article/details/gtnjedlijb.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.ydzc1.top/Article/details/gttpjhdglv.html

[R61] 磁盘占用
来源：http://dali.jqgfzy.top/Article/details/gttqfdnjif.html

df -h;  du -sh *
来源：http://dali.ydzc1.top/Article/details/gtyzxjldaq.html

[R62] 找最占空间的文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsfhfixnp.html

du -ah . | sort -rh | head -10
来源：http://dali.sxryk.cn/Article/details/gtrqrqmafv.html

[R63] 内存与进程
来源：http://dali.jyoumei.cn/Article/details/gtadizwoph.html

free -h;  ps aux | grep nginx
来源：http://dali.tian-w.cn/Article/details/gtvobhryhk.html

[R64] 结束进程
来源：http://dali.ybcxt.top/Article/details/gtbpypurpp.html

kill -9 $(pgrep -f app.py)
来源：http://dali.hammf.cn/Article/details/gtslxxaggs.html

[R65] 查看端口占用
来源：http://dali.jinqigfzy.top/Article/details/gtvpkblfpl.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.dashuyun.cn/Article/details/gtysieqmlz.html

[R66] 定时任务
来源：http://dali.zhongyouzk.top/Article/details/gtrlyhneqb.html

crontab -e;  crontab -l
来源：http://dali.vqdsnc.cn/Article/details/gtnggswcyb.html

[R67] 生成随机十六进制串
来源：http://dali.snrcjt.cn/Article/details/gtclaprzgc.html

openssl rand -hex 16
来源：http://dali.xuanzx.com/Article/details/gtnpwfrsmf.html

[R68] 计算文件校验值
来源：http://dali.nwbrower.top/Article/details/gtldqkzwkj.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.svipenyu.cn/Article/details/gtrwonpaqz.html

[R69] 生成随机密码
来源：http://dali.zdqjudy.top/Article/details/gtakzogyhj.html

head -c 16 /dev/urandom | base64
来源：http://dali.yueranfly.top/Article/details/gtvpzskmey.html

[R70] 时间戳与互转
来源：http://dali.meibo888.top/Article/details/gtzvyukmws.html

date +%s;  date -d @1700000000
来源：http://dali.ehwqpu.com/Article/details/gtxrgmfqig.html

[R71] 日期格式化
来源：http://dali.cucudq.cn/Article/details/gttjvcsunc.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.cdnleiting.top/Article/details/gtyposzyeg.html

[R72] 等待端口就绪
来源：http://dali.tianlin.xyz/Article/details/gtddajfcwd.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.xuetiantiany.cn/Article/details/gtrtdsrfmo.html

[R73] 分割大日志
来源：http://dali.daxiang520.top/Article/details/gtmyalbwwg.html

split -l 1000 big.log part_
来源：http://dali.jinqigfzy.top/Article/details/gtdvofijws.html

[R74] 批量重命名
来源：http://dali.zhoulong.xyz/Article/details/gtlzjwyqny.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.316326.xyz/Article/details/gtkyslfgwl.html

[R75] 导出环境变量
来源：http://dali.yvedp.cn/Article/details/gtaoawhphf.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.ehwqpu.com/Article/details/gtucgqwouf.html

[R76] 使用临时文件
来源：http://dali.pengpengdd.cyou/Article/details/gtxinxpkow.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.jianghu66.top/Article/details/gtqypvaaxo.html

[R77] 读取用户输入
来源：http://dali.yangfankeji.com/Article/details/gtvnaxiofi.html

read -rp "请输入: " ans
来源：http://dali.xziqi.cn/Article/details/gtjjtxrywq.html

[R78] 交互式菜单
来源：http://dali.xziqi.cn/Article/details/gtstbcavxe.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.guannengcc.top/Article/details/gtybftwucv.html

[R79] 解析命令行选项
来源：http://dali.zdqjudy.top/Article/details/gtvvhfcirx.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.gzhubu.top/Article/details/gtfkmsgnlf.html

[R80] 查看脚本执行耗时
来源：http://dali.yueranfly.top/Article/details/gtwxmxdaop.html

time ./run.sh
来源：http://dali.shangyingyoupin.top/Article/details/gtxdzhutiu.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtmuixzvhx.html

S. C / C++ 专题
来源：http://dali.andypj.xyz/Article/details/gtggaowuvj.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtkfpreqyq.html

[S01] C：Hello World
来源：http://dali.hysaishi.cn/Article/details/gtwnnadvfn.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gtmrregbqi.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.xuanzx.com/Article/details/gtrxgvltfz.html

[S02] C：变量与格式化输出
来源：http://dali.sxryk.cn/Article/details/gtceahztit.html

int a = 10; printf("%d\n", a);
来源：http://dali.iojbl.cn/Article/details/gtthkhvcjw.html

[S03] C：读入整数
来源：http://dali.feifeiyinyue.top/Article/details/gtumujlbub.html

int x; scanf("%d", &x);
来源：http://dali.fzhhl.top/Article/details/gtwceiqmkw.html

[S04] C：字符串复制
来源：http://dali.zhixingplan.top/Article/details/gtqdiwnzpa.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.ppjwa.cn/Article/details/gtrpuqekdv.html

[S05] C：字符串长度
来源：http://dali.jinyuanbaomall.cn/Article/details/gtngsthmox.html

strlen(s)
来源：http://dali.shzxlz.cn/Article/details/gtxgnkbirh.html

[S06] C：字符串比较
来源：http://dali.shzxlz.cn/Article/details/gtxkvhblal.html

strcmp(a, b) == 0
来源：http://dali.xuanzx.com/Article/details/gtwqixnwjn.html

[S07] C：数组遍历求和
来源：http://dali.guowangkeji.top/Article/details/gtwyzpbcax.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.jinghuilouyu.cn/Article/details/gtuwapxyag.html

[S08] C：动态内存分配与释放
来源：http://dali.zhaomingkeji.xyz/Article/details/gteqylcyvp.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.cqqwz.cn/Article/details/gteuiswkvt.html

[S09] C：结构体定义与初始化
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyhhitcqo.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.ydzc1.top/Article/details/gtibjfdhum.html

[S10] C：指针与解引用
来源：http://dali.fzhhl.top/Article/details/gtnwtwtjbm.html

int *p = &a;  *p = 5;
来源：http://dali.yj20258.top/Article/details/gtxfilhwid.html

[S11] C：逐行读文件
来源：http://dali.ydzc1.top/Article/details/gtkkthgltj.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.yangfankeji.com/Article/details/gttstbgsqv.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.redwolf501.top/Article/details/gtogmabfgl.html

fclose(f);
来源：http://dali.yuanzhike.top/Article/details/gtqksnbbft.html

[S12] C：写文件
来源：http://dali.bjfxy.top/Article/details/gtghofnymo.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.jinghuilouyu.cn/Article/details/gtkrjbuxiy.html

[S13] C：宏定义
来源：http://dali.gaohongyu789.top/Article/details/gtbtcpstdh.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhoulong.xyz/Article/details/gtqeqcbred.html

[S14] C：枚举
来源：http://dali.cheryme.top/Article/details/gtcvmbiglm.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.bjfxy.top/Article/details/gtyqndfdvh.html

[S15] C：类型转换
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcdvisgci.html

(double) a / b
来源：http://dali.bjfxy.top/Article/details/gtpwzgoudy.html

[S16] C：位操作置位
来源：http://dali.gzhubu.top/Article/details/gtzwthrpid.html

x |= (1 << 3);
来源：http://dali.gogol.net.cn/Article/details/gtatyrhutv.html

[S17] C：安全拼接字符串
来源：http://dali.hnqzz.top/Article/details/gtzsvcrsar.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.cdnleiting.top/Article/details/gtyzdytccz.html

[S18] C：命令行参数
来源：http://dali.zycfv.cn/Article/details/gtulbqklih.html

int main(int argc, char **argv)
来源：http://dali.9152youxi.cn/Article/details/gtqpgdxktq.html

[S19] C：快速排序
来源：http://dali.shzxlz.cn/Article/details/gteuhevygp.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.mhx1999.top/Article/details/gtnsokflom.html

[S20] C：二分查找
来源：http://dali.aibaodan.cn/Article/details/gttcfdbrvf.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.jinqigufen.top/Article/details/gthzqwxcbi.html

[S21] C：字符类别判断
来源：http://dali.daria6918.cn/Article/details/gtrzkwsgot.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpuuomsap.html

[S22] C：字符串转数字
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvpphfjxj.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.yuanzhike.top/Article/details/gtcvwsvvlu.html

[S23] C：随机数
来源：http://dali.dashuyun.cn/Article/details/gtraodegxv.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.daxiang520.top/Article/details/gtkymakqlh.html

[S24] C：获取本地时间
来源：http://dali.shuidangran.top/Article/details/gthkupbgzz.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.xziqi.cn/Article/details/gttkwljamn.html

[S25] C：内存拷贝
来源：http://dali.bjfxy.top/Article/details/gtpkikjbes.html

memcpy(dst, src, n);
来源：http://dali.hywenlv.cn/Article/details/gtckysdvxn.html

[S26] C：内存清零
来源：http://dali.feifeiyinyue.top/Article/details/gtbebmbwdb.html

memset(a, 0, sizeof a);
来源：http://dali.xuetiantiany.cn/Article/details/gtqhzwynsv.html

[S27] C：定义常量
来源：http://dali.ydzc1.top/Article/details/gtxsophlwg.html

const double PI = 3.14159;
来源：http://dali.hammf.cn/Article/details/gthgywllpt.html

[S28] C：静态变量
来源：http://dali.vqdsnc.cn/Article/details/gtdywefmvm.html

static int counter = 0;
来源：http://dali.c1oappe.top/Article/details/gtehfucujf.html

[S29] C：变参函数
来源：http://dali.gogol.net.cn/Article/details/gtkecbrgsa.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.9152youxi.cn/Article/details/gthyhxfhes.html

[S30] C：头文件保护
来源：http://dali.yj202588.top/Article/details/gtsmmlttvf.html

#ifndef X_H
来源：http://dali.xuanzx.com/Article/details/gthggohgpr.html

#define X_H
来源：http://dali.c1oappe.top/Article/details/gtbugxenja.html

#endif
来源：http://dali.sxryk.cn/Article/details/gtdhuqhtpj.html

[S31] C++：Hello World
来源：http://dali.redwolf501.top/Article/details/gtlxdboqzn.html

#include <iostream>
来源：http://dali.pengpengdd.cyou/Article/details/gtpelyphge.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.chenlongwang.top/Article/details/gtnrbjndym.html

[S32] C++：字符串
来源：http://dali.yonumen.top/Article/details/gtmblxphhj.html

std::string s = "hi";  s += "!";
来源：http://dali.gzhubu.top/Article/details/gtpaarajev.html

[S33] C++：vector 增删
来源：http://dali.cucudq.cn/Article/details/gtssnjweup.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zdqjudy.top/Article/details/gtajovfeaj.html

[S34] C++：遍历 vector
来源：http://dali.yuanzhike.top/Article/details/gtnwpxyehp.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.sufxvd.cn/Article/details/gtnxedtepc.html

[S35] C++：map
来源：http://dali.xylfe.cn/Article/details/gthorztxrn.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hysaishi.cn/Article/details/gtypngkfeb.html

[S36] C++：unordered_map
来源：http://dali.nanxinkj.top/Article/details/gteguktbpx.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zycfv.cn/Article/details/gtnvqgrbuh.html

[S37] C++：set
来源：http://dali.hysaishi.cn/Article/details/gtpiofeclt.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.hnqzz.top/Article/details/gtvvnjlhbk.html

[S38] C++：排序
来源：http://dali.nwbrower.top/Article/details/gtvnctohgh.html

std::sort(v.begin(), v.end());
来源：http://dali.mhx1999.top/Article/details/gtshguoeat.html

[S39] C++：自定义比较器排序
来源：http://dali.jinghuilouyu.cn/Article/details/gtonyclajl.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.jqgufenzy.top/Article/details/gtmroaulge.html

[S40] C++：查找元素
来源：http://dali.redwolf501.top/Article/details/gtrnuznjpr.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtssgataok.html

[S41] C++：类与构造函数
来源：http://dali.zhiwuduotai.top/Article/details/gtpvcnitxh.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhixingplan.top/Article/details/gtfnjsysvm.html

[S42] C++：继承与虚函数
来源：http://dali.hnxiangtu.top/Article/details/gtretgvekc.html

class B : public Base { public: void f() override {} };
来源：http://dali.yueranfly.top/Article/details/gtskqzemmi.html

[S43] C++：智能指针
来源：http://dali.wangshuangyany.cn/Article/details/gtjyqsahxz.html

auto p = std::make_unique<int>(5);
来源：http://dali.jiagoushi.top/Article/details/gtkxgjcyht.html

[S44] C++：引用传参
来源：http://dali.nanxuanxn.top/Article/details/gtedesieqt.html

void inc(int &x) { ++x; }
来源：http://dali.gotoacloud.top/Article/details/gtgkdnhexk.html

[S45] C++：lambda
来源：http://dali.0kj1m.cn/Article/details/gtswvdkxdn.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.tianlin.xyz/Article/details/gtboxeeyco.html

[S46] C++：函数模板
来源：http://dali.meibo888.top/Article/details/gtqthlcwuo.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.birdmap.top/Article/details/gtlctdyigr.html

[S47] C++：结构化绑定遍历
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtodsqnmew.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.chenlongwang.top/Article/details/gtudokblql.html

[S48] C++：逐行读文件
来源：http://dali.chenzaomai.com/Article/details/gtregcofsz.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.chenjidiqi.icu/Article/details/gtwygcyfwt.html

while (std::getline(in, line)) { }
来源：http://dali.hnqzz.top/Article/details/gtiejqoize.html

[S49] C++：写文件
来源：http://dali.gaohongyu789.top/Article/details/gtawlcwyzc.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.hongshengwenyu.top/Article/details/gtjkucqnet.html

[S50] C++：格式化数字
来源：http://dali.zhoulong.xyz/Article/details/gtzhqywynn.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.pycfn.com/Article/details/gtkowqfeiq.html

[S51] C++：显式类型转换
来源：http://dali.smart0.xyz/Article/details/gtkodoaydg.html

static_cast<double>(a) / b
来源：http://dali.yongpay.top/Article/details/gtjevtnjrv.html

[S52] C++：const 与 noexcept
来源：http://dali.gzhubu.top/Article/details/gtncrdebir.html

int size() const noexcept { return n_; }
来源：http://dali.sysykeji.top/Article/details/gtkyrsqhmi.html

[S53] C++：移动语义
来源：http://dali.xylfe.cn/Article/details/gtcxxliwpw.html

std::vector<int> w = std::move(v);
来源：http://dali.andypj.xyz/Article/details/gtcmfssqse.html

[S54] C++：异常处理
来源：http://dali.wangshuangyany.cn/Article/details/gtdcntzrhp.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.xziqi.cn/Article/details/gtkyttfnar.html

[S55] C++：结构化绑定
来源：http://dali.wangdashe.top/Article/details/gtegjjahrf.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.mhx1999.top/Article/details/gtcotpisld.html

[S56] C++：optional
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmfdnywnj.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yanxiufei.cn/Article/details/gtlglkgsit.html

[S57] C++：编译期常量
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlsahvtbq.html

constexpr int N = 10;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwduvistk.html

[S58] C++：命名空间
来源：http://dali.nwbrower.top/Article/details/gtkwtqegqx.html

namespace ns { int f() { return 1; } }
来源：http://dali.aibaodan.cn/Article/details/gtlqttohnh.html

[S59] C++：静态断言
来源：http://dali.iojbl.cn/Article/details/gtgineuflx.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpdbgyzkv.html

[S60] C++：遍历并删除元素
来源：http://dali.hysaishi.cn/Article/details/gtyhydfrqt.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.jinqigufen.top/Article/details/gtzgowomut.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtskgvszlv.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.jiagoushi.top/Article/details/gtyvukxube.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtfsxtzodv.html

[T01] Kotlin：Hello World
来源：http://dali.iojbl.cn/Article/details/gtcabjmebw.html

println("Hello")
来源：http://dali.sysykeji.top/Article/details/gtirrjqntz.html

[T02] Kotlin：变量
来源：http://dali.jianghu66.top/Article/details/gthovwpraw.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.wangshuangyany.cn/Article/details/gthmhhvpfe.html


<!-- 参考信息 -->