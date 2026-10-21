代发 wailian999

set -euo pipefail
来源：http://dali.chenlongwang.top/Article/details/gtbntiqcjs.html

[R02] 变量赋值与使用
来源：http://dali.gogol.net.cn/Article/details/gtgjrbwkvv.html

name="Tom"; echo "$name"
来源：http://dali.tanke756.top/Article/details/gtrkshasxj.html

[R03] 只读变量
来源：http://dali.hnxiangtu.top/Article/details/gtlgahgiic.html

readonly PI=3.14
来源：http://dali.yangfankeji.com/Article/details/gtciacbejf.html

[R04] 位置参数
来源：http://dali.hfpthk.cn/Article/details/gtptttfcsu.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgqlcdiar.html

[R05] 参数默认值
来源：http://dali.smart0.xyz/Article/details/gtxzkrjmdb.html

name="${1:-default}"
来源：http://dali.hfpthk.cn/Article/details/gtyqrjgmix.html

[R06] 判断命令是否存在
来源：http://dali.redwolf501.top/Article/details/gtyufiawnd.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.redwolf501.top/Article/details/gtjqpqowag.html

[R07] if 判断文件
来源：http://dali.guowangkeji.top/Article/details/gtzksritne.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.mhx1999.top/Article/details/gtlyokvezz.html

[R08] 数值比较
来源：http://dali.ydzc1.top/Article/details/gtcrycarbv.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.iojbl.cn/Article/details/gtnynskklz.html

[R09] 字符串比较
来源：http://dali.zhoulong.xyz/Article/details/gtblyunjmq.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.9152youxi.cn/Article/details/gtmphsdhjp.html

[R10] 正则匹配
来源：http://dali.gaohongyu789.top/Article/details/gtopbjlpds.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.316326.xyz/Article/details/gtzznuhzgj.html

[R11] case 多分支
来源：http://dali.shuidangran.top/Article/details/gtwouylhcs.html

case "$1" in
来源：http://dali.hfpthk.cn/Article/details/gtqdexrohm.html

start) echo "启动" ;;
来源：http://dali.shzxlz.cn/Article/details/gtznldnjgp.html

stop)  echo "停止" ;;
来源：http://dali.zhoulong.xyz/Article/details/gttgesygzs.html

*)     echo "未知命令" ;;
来源：http://dali.yj20258888.top/Article/details/gtatepujct.html

esac
来源：http://dali.sufxvd.cn/Article/details/gtxhqbzitr.html

[R12] for 遍历文件
来源：http://dali.hnqzz.top/Article/details/gtjyrgtfps.html

for f in *.txt; do echo "$f"; done
来源：http://dali.yj202588.top/Article/details/gthowqqpgg.html

[R13] for 计数循环
来源：http://dali.9152youxi.cn/Article/details/gtyqsjkguw.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhengqikj.top/Article/details/gtqdnptjbi.html

[R14] C 风格 for
来源：http://dali.snrcjt.cn/Article/details/gtlnghfzaa.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.yuxming.cn/Article/details/gtuszuvfgr.html

[R15] while 逐行读文件
来源：http://dali.jqgufenzy.top/Article/details/gtolrmesih.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.tanke756.top/Article/details/gthzlyapvl.html

[R16] until 等待条件
来源：http://dali.316326.xyz/Article/details/gtvkyqshuf.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.dianchejie.cn/Article/details/gthddqyyqp.html

[R17] 数组定义与取值
来源：http://dali.tanke756.top/Article/details/gtvfkdrgpf.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.redwolf501.top/Article/details/gtgcvzgbkv.html

[R18] 遍历数组
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmklnsiwr.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.yongpay.top/Article/details/gtjckmvqtt.html

[R19] 数组长度
来源：http://dali.sufxvd.cn/Article/details/gtzrflbqil.html

echo "${#arr[@]}"
来源：http://dali.pengpengdd.cyou/Article/details/gtvgxtvukd.html

[R20] 关联数组（字典）
来源：http://dali.yuxming.cn/Article/details/gtazmaqfrr.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.hnxiangtu.top/Article/details/gtvoqixqkf.html

[R21] 字符串长度
来源：http://dali.xziqi.cn/Article/details/gtfbbhdvtr.html

echo "${#s}"
来源：http://dali.jqgfzy.top/Article/details/gttbrkpqph.html

[R22] 截取子串
来源：http://dali.jiagoushi.top/Article/details/gtrluungmy.html

echo "${s:0:5}"
来源：http://dali.nwbrower.top/Article/details/gtfjwunwdv.html

[R23] 字符串替换
来源：http://dali.wangshuangyany.cn/Article/details/gtmqsaqkvt.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.sufxvd.cn/Article/details/gtumvefywy.html

[R24] 大小写转换
来源：http://dali.haohaochexian.top/Article/details/gtrhbeioxn.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.ppjwa.cn/Article/details/gtkzflzdfc.html

[R25] 去后缀 / 去前缀
来源：http://dali.nwbrower.top/Article/details/gtqdyptkzh.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.c1oappe.top/Article/details/gtjguswmxq.html

[R26] 命令替换
来源：http://dali.zycfv.cn/Article/details/gtaklazinr.html

now=$(date +%F); echo "$now"
来源：http://dali.daria6918.cn/Article/details/gtchmzadgn.html

[R27] 算术展开
来源：http://dali.zhiwuduotai.top/Article/details/gtixafrtpd.html

echo $((1 + 2 * 3))
来源：http://dali.hnqzz.top/Article/details/gtmremncxz.html

[R28] 浮点运算
来源：http://dali.dianchejie.cn/Article/details/gtwyelqdmp.html

echo "scale=2; 10/3" | bc
来源：http://dali.c1oappe.top/Article/details/gtpbikddtw.html

[R29] 定义函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtydmstraw.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.cheryme.top/Article/details/gtvdyuvjcp.html

[R30] 函数返回状态码
来源：http://dali.gogol.net.cn/Article/details/gtzxqnncua.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.svipenyu.cn/Article/details/gtquobdqff.html

[R31] 局部变量
来源：http://dali.xylfe.cn/Article/details/gtapuhdvgy.html

f() { local x=1; echo "$x"; }
来源：http://dali.daria6918.cn/Article/details/gthglacqfp.html

[R32] 参数个数校验
来源：http://dali.feifeiyinyue.top/Article/details/gtyhgxhpdl.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.hnxiangtu.top/Article/details/gteagnoenp.html

[R33] 捕获错误并提示行号
来源：http://dali.zhaomingkeji.xyz/Article/details/gtozwvqojb.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.yonumen.top/Article/details/gtrogxektm.html

[R34] 退出时清理
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkuahbssq.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.guowangkeji.top/Article/details/gtbqrjfqrr.html

[R35] 后台执行并等待
来源：http://dali.jiagoushi.top/Article/details/gtfbhvxiec.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.iojbl.cn/Article/details/gtoiayoalb.html

[R36] 并发执行多个任务
来源：http://dali.chenlongwang.top/Article/details/gtykcqelaf.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfrufrjqm.html

[R37] 把输出赋给变量
来源：http://dali.vqdsnc.cn/Article/details/gtjwcrcejd.html

files=$(ls -1)
来源：http://dali.havefunace.top/Article/details/gtqyhisqdc.html

[R38] 管道串联
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoncptipi.html

cat a.txt | grep -i error | wc -l
来源：http://dali.hnxiangtu.top/Article/details/gtckpwsrjw.html

[R39] 重定向标准输出与错误
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzjwhmlma.html

cmd > out.log 2>&1
来源：http://dali.snrcjt.cn/Article/details/gtoztlnyye.html

[R40] 追加写日志
来源：http://dali.pycfn.com/Article/details/gtcmkyjhmh.html

echo "log" >> out.log
来源：http://dali.yanxiufei.cn/Article/details/gtgywebrej.html

[R41] 丢弃输出
来源：http://dali.zhoulong.xyz/Article/details/gtbguquwoy.html

cmd >/dev/null 2>&1
来源：http://dali.svipenyu.cn/Article/details/gtpnrdopmu.html

[R42] 输入重定向
来源：http://dali.svipenyu.cn/Article/details/gtiwwaiqhj.html

wc -l < a.txt
来源：http://dali.yangfankeji.com/Article/details/gtdoghpeur.html

[R43] 按名字查找文件
来源：http://dali.cheryme.top/Article/details/gtqqwovbxb.html

find . -name "*.log" -type f
来源：http://dali.dashuyun.cn/Article/details/gteybnjnot.html

[R44] 按修改时间查找
来源：http://dali.zhengqikj.top/Article/details/gtifxnhuup.html

find . -mtime -7 -type f
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvvzzysaz.html

[R45] 批量删除
来源：http://dali.andypj.xyz/Article/details/gtinnbzrnq.html

find . -name "*.tmp" -delete
来源：http://dali.fengsongda.top/Article/details/gtsuzqmjyb.html

[R46] 递归替换文件内容
来源：http://dali.cdnleiting.top/Article/details/gtgeykkgxj.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.guowangkeji.top/Article/details/gtilakbpef.html

[R47] sed 单行替换
来源：http://dali.svipenyu.cn/Article/details/gtjlwhkrzu.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.nanxuanxn.top/Article/details/gtwylocduo.html

[R48] awk 取指定列
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrmnaubze.html

awk '{print $1, $3}' a.txt
来源：http://dali.nwbrower.top/Article/details/gtiaefstyd.html

[R49] awk 带条件
来源：http://dali.gogol.net.cn/Article/details/gtpvyeeccf.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.yj20258888.top/Article/details/gtmedipgaj.html

[R50] awk 求和
来源：http://dali.feifeiyinyue.top/Article/details/gtfwmccbba.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.guowangkeji.top/Article/details/gtnunuybiv.html

[R51] 排序去重取前几
来源：http://dali.nanxuanxn.top/Article/details/gtfawzqqdh.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.smart0.xyz/Article/details/gtlulghfdn.html

[R52] 统计行数
来源：http://dali.sxryk.cn/Article/details/gtsgzmlgqp.html

wc -l a.txt
来源：http://dali.jiagoushi.top/Article/details/gthytifdzq.html

[R53] 查看文件头与实时尾
来源：http://dali.sufxvd.cn/Article/details/gtltihgpia.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.dashuyun.cn/Article/details/gtgkhhsoqd.html

[R54] 比较两个文件
来源：http://dali.yuanzhike.top/Article/details/gtpimpspal.html

diff a.txt b.txt
来源：http://dali.cdnleiting.top/Article/details/gtnopfqeom.html

[R55] 压缩与解压
来源：http://dali.hywenlv.cn/Article/details/gtddzeddfy.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.nanxuanxn.top/Article/details/gtmdkqrarx.html

[R56] 远程拷贝
来源：http://dali.yangfankeji.com/Article/details/gtwirrmksf.html

scp file user@host:/path/
来源：http://dali.guowangkeji.top/Article/details/gtuhggxtii.html

[R57] 远程执行命令
来源：http://dali.nanxinkj.top/Article/details/gtdmwkmsye.html

ssh user@host 'uptime'
来源：http://dali.smart0.xyz/Article/details/gtwwbxhrfw.html

[R58] 下载文件
来源：http://dali.yangfankeji.com/Article/details/gtigovunve.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gtfidhdbeq.html

[R59] 发 POST JSON
来源：http://dali.smart0.xyz/Article/details/gtkybatjbd.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.xinyue.icu/Article/details/gtjutgmffp.html

[R60] 只看 HTTP 状态码
来源：http://dali.fzhhl.top/Article/details/gtlfaonids.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.shzxlz.cn/Article/details/gtcfkfgeyj.html

[R61] 磁盘占用
来源：http://dali.ivvv.top/Article/details/gtbgofupyc.html

df -h;  du -sh *
来源：http://dali.cucudq.cn/Article/details/gtzaxajhiw.html

[R62] 找最占空间的文件
来源：http://dali.zhongyouzk.top/Article/details/gtenxoqkde.html

du -ah . | sort -rh | head -10
来源：http://dali.dashuyun.cn/Article/details/gtwvjxpgfj.html

[R63] 内存与进程
来源：http://dali.tanke756.top/Article/details/gtfiheewkd.html

free -h;  ps aux | grep nginx
来源：http://dali.jianghu66.top/Article/details/gtqkspbvfi.html

[R64] 结束进程
来源：http://dali.mhx1999.top/Article/details/gtshmjxibx.html

kill -9 $(pgrep -f app.py)
来源：http://dali.feifeiyinyue.top/Article/details/gtvpukzusy.html

[R65] 查看端口占用
来源：http://dali.xinyue.icu/Article/details/gtizxaqnby.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.ydzc1.top/Article/details/gtcnagodpp.html

[R66] 定时任务
来源：http://dali.aizwys.cn/Article/details/gtyitaviyd.html

crontab -e;  crontab -l
来源：http://dali.shanyushiyangkeji.top/Article/details/gthkbpmqvb.html

[R67] 生成随机十六进制串
来源：http://dali.meibo888.top/Article/details/gtojeuugne.html

openssl rand -hex 16
来源：http://dali.yj20258888.top/Article/details/gtjzadleqa.html

[R68] 计算文件校验值
来源：http://dali.ydzc1.top/Article/details/gtcuywrbgs.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.xylfe.cn/Article/details/gtcxnciyad.html

[R69] 生成随机密码
来源：http://dali.fengsongda.top/Article/details/gtogsgzdyr.html

head -c 16 /dev/urandom | base64
来源：http://dali.ppjwa.cn/Article/details/gtpoxkfolc.html

[R70] 时间戳与互转
来源：http://dali.vqdsnc.cn/Article/details/gtsegtyxzd.html

date +%s;  date -d @1700000000
来源：http://dali.xylfe.cn/Article/details/gtefkhkcfv.html

[R71] 日期格式化
来源：http://dali.chenlongwang.top/Article/details/gtfjflyoyt.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.sufxvd.cn/Article/details/gtynyrjyqt.html

[R72] 等待端口就绪
来源：http://dali.jqgufenzy.top/Article/details/gtvszombkm.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.havefunace.top/Article/details/gtcsnyouip.html

[R73] 分割大日志
来源：http://dali.nanxinkj.top/Article/details/gtkzyckkol.html

split -l 1000 big.log part_
来源：http://dali.bjfxy.top/Article/details/gtxdprdopd.html

[R74] 批量重命名
来源：http://dali.yj20258888.top/Article/details/gtzsezusaj.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.c1oappe.top/Article/details/gthtswyedl.html

[R75] 导出环境变量
来源：http://dali.xylfe.cn/Article/details/gtpqhocomh.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.yueranfly.top/Article/details/gtrtssidca.html

[R76] 使用临时文件
来源：http://dali.aizwys.cn/Article/details/gtamamrzsp.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.shzxlz.cn/Article/details/gttmnndifb.html

[R77] 读取用户输入
来源：http://dali.9152youxi.cn/Article/details/gtnkocdvhf.html

read -rp "请输入: " ans
来源：http://dali.ydzc1.top/Article/details/gtjykeyghy.html

[R78] 交互式菜单
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrmvugknh.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.tian-w.cn/Article/details/gtxnbcdffz.html

[R79] 解析命令行选项
来源：http://dali.chenzaomai.com/Article/details/gtrmybeeus.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.jinghuilouyu.cn/Article/details/gtbmshbexb.html

[R80] 查看脚本执行耗时
来源：http://dali.xuanzx.com/Article/details/gtofkjkyrw.html

time ./run.sh
来源：http://dali.fzhhl.top/Article/details/gtfjfbbpwz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtetrqpfhm.html

S. C / C++ 专题
来源：http://dali.yonumen.top/Article/details/gtgylqgyhb.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtlgfosaqa.html

[S01] C：Hello World
来源：http://dali.hysaishi.cn/Article/details/gtwsymaqxe.html

#include <stdio.h>
来源：http://dali.sweek.top/Article/details/gthsvdfufz.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.shzxlz.cn/Article/details/gtusqxepap.html

[S02] C：变量与格式化输出
来源：http://dali.cashguo.top/Article/details/gtbsjnmdvo.html

int a = 10; printf("%d\n", a);
来源：http://dali.gotoacloud.top/Article/details/gtnjcywfrz.html

[S03] C：读入整数
来源：http://dali.yuxming.cn/Article/details/gtgsjmytof.html

int x; scanf("%d", &x);
来源：http://dali.shangyingyoupin.top/Article/details/gtbpakizlg.html

[S04] C：字符串复制
来源：http://dali.shanyushiyangtech.top/Article/details/gtueatlrxb.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.yuanzhike.top/Article/details/gtlwajfhif.html

[S05] C：字符串长度
来源：http://dali.hongshengwenyu.top/Article/details/gtdrgtwxji.html

strlen(s)
来源：http://dali.hongshengwenyu.top/Article/details/gttegtgkmi.html

[S06] C：字符串比较
来源：http://dali.yj20258.top/Article/details/gtwtovttcw.html

strcmp(a, b) == 0
来源：http://dali.gzhubu.top/Article/details/gtkbetiwjz.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gtmfeaodbh.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.sufxvd.cn/Article/details/gtypqfvomu.html

[S08] C：动态内存分配与释放
来源：http://dali.vqdsnc.cn/Article/details/gtaibzukfz.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.cqqwz.cn/Article/details/gtbufetvhs.html

[S09] C：结构体定义与初始化
来源：http://dali.ydzc1.top/Article/details/gtccpsfdys.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.gaohongyu789.top/Article/details/gtebwxendc.html

[S10] C：指针与解引用
来源：http://dali.9152youxi.cn/Article/details/gtqyupyytj.html

int *p = &a;  *p = 5;
来源：http://dali.dianchejie.cn/Article/details/gttgoosmsu.html

[S11] C：逐行读文件
来源：http://dali.nanxinkj.top/Article/details/gtrbnyclms.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.shzxlz.cn/Article/details/gtrmkizlvn.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.jinyuanbaomall.cn/Article/details/gttxvejvhd.html

fclose(f);
来源：http://dali.316326.xyz/Article/details/gtxqjvjdeb.html

[S12] C：写文件
来源：http://dali.ppjwa.cn/Article/details/gtajqrwvyd.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.quarkkingdee.top/Article/details/gtgrauieaq.html

[S13] C：宏定义
来源：http://dali.yj20258.top/Article/details/gtmmnjpvhe.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhongyouzk.top/Article/details/gtwntcdgzl.html

[S14] C：枚举
来源：http://dali.yj20258888.top/Article/details/gtownmsche.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.gogol.net.cn/Article/details/gtvljwdajg.html

[S15] C：类型转换
来源：http://dali.pengpengdd.cyou/Article/details/gtvyfghvif.html

(double) a / b
来源：http://dali.ywan-chungtsiang.top/Article/details/gtszjkwkqt.html

[S16] C：位操作置位
来源：http://dali.yj202588.top/Article/details/gtxqmetrht.html

x |= (1 << 3);
来源：http://dali.hywenlv.cn/Article/details/gthpleyfct.html

[S17] C：安全拼接字符串
来源：http://dali.yvedp.cn/Article/details/gtesekiaqg.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.316326.xyz/Article/details/gtchtrkdch.html

[S18] C：命令行参数
来源：http://dali.hysaishi.cn/Article/details/gtqkodxmlt.html

int main(int argc, char **argv)
来源：http://dali.daria6918.cn/Article/details/gtphexvhrf.html

[S19] C：快速排序
来源：http://dali.zhongyouzk.top/Article/details/gtgzppyhqx.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zycfv.cn/Article/details/gtjpvsudrq.html

[S20] C：二分查找
来源：http://dali.feifeiyinyue.top/Article/details/gtbqkipohm.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.haohaochexian.top/Article/details/gtgaecsfpi.html

[S21] C：字符类别判断
来源：http://dali.tian-w.cn/Article/details/gtgwhsfckw.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.gzhubu.top/Article/details/gtwpgootwi.html

[S22] C：字符串转数字
来源：http://dali.yonumen.top/Article/details/gtndgsdazf.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.sweek.top/Article/details/gtektrzvwt.html

[S23] C：随机数
来源：http://dali.tianlin.xyz/Article/details/gtvwmzzvwn.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.yuanzhike.top/Article/details/gttljmvpmt.html

[S24] C：获取本地时间
来源：http://dali.yanxiufei.cn/Article/details/gttirzydgg.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtumvoxldi.html

[S25] C：内存拷贝
来源：http://dali.jyoumei.cn/Article/details/gtzinmyupd.html

memcpy(dst, src, n);
来源：http://dali.yuanzhike.top/Article/details/gtbijxutvc.html

[S26] C：内存清零
来源：http://dali.zhiwuduotai.top/Article/details/gtqdyfohpb.html

memset(a, 0, sizeof a);
来源：http://dali.hongshengwenyu.top/Article/details/gtpfvecjqf.html

[S27] C：定义常量
来源：http://dali.jinghuilouyu.cn/Article/details/gtsslplevw.html

const double PI = 3.14159;
来源：http://dali.shangyingyoupin.top/Article/details/gtjthardol.html

[S28] C：静态变量
来源：http://dali.xylfe.cn/Article/details/gtwuaoezls.html

static int counter = 0;
来源：http://dali.yj20258.top/Article/details/gttidjrjbi.html

[S29] C：变参函数
来源：http://dali.yj20258.top/Article/details/gtiowuknur.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.guowangkeji.top/Article/details/gtyojwlitl.html

[S30] C：头文件保护
来源：http://dali.yuanzhike.top/Article/details/gtkpoenfwd.html

#ifndef X_H
来源：http://dali.yj20258.top/Article/details/gtjsrnxypt.html

#define X_H
来源：http://dali.c1oappe.top/Article/details/gtptsqrtwt.html

#endif
来源：http://dali.haohaochexian.top/Article/details/gtkokqdegb.html

[S31] C++：Hello World
来源：http://dali.zhoulong.xyz/Article/details/gtskwhdaww.html

#include <iostream>
来源：http://dali.dashuyun.cn/Article/details/gtiunysufc.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.yongpay.top/Article/details/gtxdkzpxki.html

[S32] C++：字符串
来源：http://dali.shzxlz.cn/Article/details/gttmprfmtn.html

std::string s = "hi";  s += "!";
来源：http://dali.chenjidiqi.icu/Article/details/gtavhqqmxa.html

[S33] C++：vector 增删
来源：http://dali.hammf.cn/Article/details/gtkdaiijxc.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.vqdsnc.cn/Article/details/gtdoijqnwq.html

[S34] C++：遍历 vector
来源：http://dali.gaohongyu789.top/Article/details/gtumuxgmsi.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.bjfxy.top/Article/details/gtheivdsnm.html

[S35] C++：map
来源：http://dali.xinyue.icu/Article/details/gtftlyzhxa.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.ehwqpu.com/Article/details/gtxpejyibc.html

[S36] C++：unordered_map
来源：http://dali.nanxinkj.top/Article/details/gtxcumavzv.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.sweek.top/Article/details/gtmvxxeccb.html

[S37] C++：set
来源：http://dali.aizwys.cn/Article/details/gtazyuabwr.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhoulong.xyz/Article/details/gtecrntdtb.html

[S38] C++：排序
来源：http://dali.9152youxi.cn/Article/details/gtgymnqgxe.html

std::sort(v.begin(), v.end());
来源：http://dali.hywenlv.cn/Article/details/gtwbebhmdk.html

[S39] C++：自定义比较器排序
来源：http://dali.chenjidiqi.icu/Article/details/gtztvhrijn.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.hnqzz.top/Article/details/gtbpyvtwxy.html

[S40] C++：查找元素
来源：http://dali.shzxlz.cn/Article/details/gtjxubdyyi.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.wangshuangyany.cn/Article/details/gtzgslhhvc.html

[S41] C++：类与构造函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtykdfovkj.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.gzhubu.top/Article/details/gtwwobdgaa.html

[S42] C++：继承与虚函数
来源：http://dali.aibaodan.cn/Article/details/gtzbwwrltz.html

class B : public Base { public: void f() override {} };
来源：http://dali.daria6918.cn/Article/details/gtznlnzzvz.html

[S43] C++：智能指针
来源：http://dali.pycfn.com/Article/details/gtcmwkuidx.html

auto p = std::make_unique<int>(5);
来源：http://dali.xylfe.cn/Article/details/gtmrbhbyvu.html

[S44] C++：引用传参
来源：http://dali.ppjwa.cn/Article/details/gtkzksviub.html

void inc(int &x) { ++x; }
来源：http://dali.yongpay.top/Article/details/gtptgrnign.html

[S45] C++：lambda
来源：http://dali.smart0.xyz/Article/details/gtwiksaxjc.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.birdmap.top/Article/details/gtccdhpcpg.html

[S46] C++：函数模板
来源：http://dali.gotoacloud.top/Article/details/gtfzerlpjz.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtlgfklapq.html

[S47] C++：结构化绑定遍历
来源：http://dali.gogol.net.cn/Article/details/gtyfdrhqyk.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtburhavkr.html

[S48] C++：逐行读文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gttbsnrmtq.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.daria6918.cn/Article/details/gtijdawfqm.html

while (std::getline(in, line)) { }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlbsjyqsz.html

[S49] C++：写文件
来源：http://dali.redwolf501.top/Article/details/gtdsyqrejo.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.dashuyun.cn/Article/details/gtexqjrfcm.html

[S50] C++：格式化数字
来源：http://dali.zhongyouzk.top/Article/details/gtlndzahkx.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.gotoacloud.top/Article/details/gtzinhrphx.html

[S51] C++：显式类型转换
来源：http://dali.cdnleiting.top/Article/details/gtebxrrycx.html

static_cast<double>(a) / b
来源：http://dali.dashuyun.cn/Article/details/gtitdzyxkl.html

[S52] C++：const 与 noexcept
来源：http://dali.zhongyouzk.top/Article/details/gtxnmctsnp.html

int size() const noexcept { return n_; }
来源：http://dali.gogol.net.cn/Article/details/gtzurltuwe.html

[S53] C++：移动语义
来源：http://dali.hywenlv.cn/Article/details/gtfjvlwzlx.html

std::vector<int> w = std::move(v);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzhzwnmua.html

[S54] C++：异常处理
来源：http://dali.shuidangran.top/Article/details/gtdhxihpsb.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.ppjwa.cn/Article/details/gteiumagsk.html

[S55] C++：结构化绑定
来源：http://dali.feifeiyinyue.top/Article/details/gtabrzmqvy.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zdqjudy.top/Article/details/gtukugdndu.html

[S56] C++：optional
来源：http://dali.zdqjudy.top/Article/details/gtfecqjwho.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.quarkkingdee.top/Article/details/gticxnjjcc.html

[S57] C++：编译期常量
来源：http://dali.hywenlv.cn/Article/details/gtvkdhixgi.html

constexpr int N = 10;
来源：http://dali.sweek.top/Article/details/gtlzxxgzst.html

[S58] C++：命名空间
来源：http://dali.gotoacloud.top/Article/details/gtqitoapmj.html

namespace ns { int f() { return 1; } }
来源：http://dali.yj202588.top/Article/details/gtwcrooxqp.html

[S59] C++：静态断言
来源：http://dali.c1oappe.top/Article/details/gthistlyau.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.fengsongda.top/Article/details/gtnaiocyoa.html

[S60] C++：遍历并删除元素
来源：http://dali.guannengcc.top/Article/details/gtsooqfqqk.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.jyoumei.cn/Article/details/gthrzpeskb.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtdwighmol.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.hysaishi.cn/Article/details/gtdhpkilpg.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtnqmfurft.html

[T01] Kotlin：Hello World
来源：http://dali.feifeiyinyue.top/Article/details/gtasbeemef.html

println("Hello")
来源：http://dali.chenlongwang.top/Article/details/gtwzvhezcx.html

[T02] Kotlin：变量
来源：http://dali.zhongyouzk.top/Article/details/gtzstjbkgt.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhixingplan.top/Article/details/gtloxxbhts.html


<!-- 参考信息 -->