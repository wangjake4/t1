代发 wailian999

[Q88] 行转列（条件聚合）
来源：http://dali.hfpthk.cn/Article/details/gtxuxidxvp.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.gogol.net.cn/Article/details/gtucbgcspx.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.iojbl.cn/Article/details/gtbcfjgibu.html

[Q89] 判断表是否存在
来源：http://dali.quarkkingdee.top/Article/details/gtzjulnlai.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.yanxiufei.cn/Article/details/gttzbeyhpg.html

[Q90] 生成序号列
来源：http://dali.ydzc1.top/Article/details/gtlthzofcp.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjtisiflt.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtquvinddj.html

R. Bash 专题
来源：http://dali.yueranfly.top/Article/details/gtfyydkygf.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtgzstdazj.html

[R01] shebang 与严格模式
来源：http://dali.yj202588.top/Article/details/gtzqvkmjrm.html

#!/usr/bin/env bash
来源：http://dali.andypj.xyz/Article/details/gtvxasbwor.html

set -euo pipefail
来源：http://dali.guannengcc.top/Article/details/gtnchdqrgd.html

[R02] 变量赋值与使用
来源：http://dali.hammf.cn/Article/details/gtgoqpsoeg.html

name="Tom"; echo "$name"
来源：http://dali.yuxming.cn/Article/details/gtrlnqaskm.html

[R03] 只读变量
来源：http://dali.redwolf501.top/Article/details/gtlwtounya.html

readonly PI=3.14
来源：http://dali.nanxuanxn.top/Article/details/gtbnbbdhjw.html

[R04] 位置参数
来源：http://dali.sysykeji.top/Article/details/gtpcylbufx.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.redwolf501.top/Article/details/gtimaczqxv.html

[R05] 参数默认值
来源：http://dali.jinqigufen.top/Article/details/gtvfnvvqva.html

name="${1:-default}"
来源：http://dali.vqdsnc.cn/Article/details/gtrxlenrnf.html

[R06] 判断命令是否存在
来源：http://dali.xinyue.icu/Article/details/gtpeczyngr.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.hywenlv.cn/Article/details/gtxatfqdjo.html

[R07] if 判断文件
来源：http://dali.yueranfly.top/Article/details/gtwjtnqnns.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.meibo888.top/Article/details/gtklvfwqyl.html

[R08] 数值比较
来源：http://dali.hammf.cn/Article/details/gtmzmgpsce.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttizpvegw.html

[R09] 字符串比较
来源：http://dali.hysaishi.cn/Article/details/gtxtgvybot.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.cqqwz.cn/Article/details/gtbjzqduoe.html

[R10] 正则匹配
来源：http://dali.ehwqpu.com/Article/details/gtybpvhbuh.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.tian-w.cn/Article/details/gthpbztajl.html

[R11] case 多分支
来源：http://dali.wangshuangyany.cn/Article/details/gtxkywcikn.html

case "$1" in
来源：http://dali.yongpay.top/Article/details/gtoemmbozl.html

start) echo "启动" ;;
来源：http://dali.wangshuangyany.cn/Article/details/gtggljcrsk.html

stop)  echo "停止" ;;
来源：http://dali.0kj1m.cn/Article/details/gtfbstkmlq.html

*)     echo "未知命令" ;;
来源：http://dali.chenzaomai.com/Article/details/gthrfovncs.html

esac
来源：http://dali.9152youxi.cn/Article/details/gtvdkremle.html

[R12] for 遍历文件
来源：http://dali.svipenyu.cn/Article/details/gtjqoernkr.html

for f in *.txt; do echo "$f"; done
来源：http://dali.birdmap.top/Article/details/gthhoxlrdm.html

[R13] for 计数循环
来源：http://dali.0kj1m.cn/Article/details/gtszyejiob.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhixingplan.top/Article/details/gttqatkopo.html

[R14] C 风格 for
来源：http://dali.hysaishi.cn/Article/details/gtxdwdtjsm.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.yongpay.top/Article/details/gtwldfprtg.html

[R15] while 逐行读文件
来源：http://dali.ydzc1.top/Article/details/gtcforvusc.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.nanxinkj.top/Article/details/gtktidvrzd.html

[R16] until 等待条件
来源：http://dali.yj20258888.top/Article/details/gtrenpcutt.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.yuxming.cn/Article/details/gtxmvsibpb.html

[R17] 数组定义与取值
来源：http://dali.aizwys.cn/Article/details/gtfvvpbjqq.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zdqjudy.top/Article/details/gtvfhcxjqf.html

[R18] 遍历数组
来源：http://dali.shuidangran.top/Article/details/gtufjwheci.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.wangdashe.top/Article/details/gtalqpiqof.html

[R19] 数组长度
来源：http://dali.c1oappe.top/Article/details/gtulqolybe.html

echo "${#arr[@]}"
来源：http://dali.chenzaomai.com/Article/details/gtfoiwetxi.html

[R20] 关联数组（字典）
来源：http://dali.gogol.net.cn/Article/details/gtpxgvfbke.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.xylfe.cn/Article/details/gtdzdyisnl.html

[R21] 字符串长度
来源：http://dali.zhiwuduotai.top/Article/details/gtbdhzusiv.html

echo "${#s}"
来源：http://dali.chenzaomai.com/Article/details/gtqdubetkf.html

[R22] 截取子串
来源：http://dali.sxryk.cn/Article/details/gtlrvqjuul.html

echo "${s:0:5}"
来源：http://dali.ppjwa.cn/Article/details/gttcmmwqkt.html

[R23] 字符串替换
来源：http://dali.yueranfly.top/Article/details/gtvnrdfuyv.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.yj20258888.top/Article/details/gtyvarxvxt.html

[R24] 大小写转换
来源：http://dali.gogol.net.cn/Article/details/gtdjtynmfn.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhixingplan.top/Article/details/gtvbpeeqwf.html

[R25] 去后缀 / 去前缀
来源：http://dali.pycfn.com/Article/details/gthsgzxqqk.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.hnqzz.top/Article/details/gtejctgwze.html

[R26] 命令替换
来源：http://dali.birdmap.top/Article/details/gtpdeqscxa.html

now=$(date +%F); echo "$now"
来源：http://dali.shzxlz.cn/Article/details/gtcxelynsx.html

[R27] 算术展开
来源：http://dali.ydzc1.top/Article/details/gtmmbenbpk.html

echo $((1 + 2 * 3))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpuzwovbs.html

[R28] 浮点运算
来源：http://dali.shanyushiyangtech.top/Article/details/gtczmwipmm.html

echo "scale=2; 10/3" | bc
来源：http://dali.ybcxt.top/Article/details/gtwsqctosw.html

[R29] 定义函数
来源：http://dali.cdnleiting.top/Article/details/gtbitvbhwt.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.guowangkeji.top/Article/details/gtomslyuje.html

[R30] 函数返回状态码
来源：http://dali.dianchejie.cn/Article/details/gtkmbncuum.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.yueranfly.top/Article/details/gtiqbpbzrk.html

[R31] 局部变量
来源：http://dali.cqqwz.cn/Article/details/gteltgnaky.html

f() { local x=1; echo "$x"; }
来源：http://dali.quarkkingdee.top/Article/details/gtigaeribc.html

[R32] 参数个数校验
来源：http://dali.feifeiyinyue.top/Article/details/gtpedtzeir.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.xylfe.cn/Article/details/gtijxxzbpu.html

[R33] 捕获错误并提示行号
来源：http://dali.xinyue.icu/Article/details/gtixybdqyl.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqoawitql.html

[R34] 退出时清理
来源：http://dali.chenlongwang.top/Article/details/gtllvuzndg.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.dashuyun.cn/Article/details/gtgyhnhrzz.html

[R35] 后台执行并等待
来源：http://dali.hongshengwenyu.top/Article/details/gtvltdmoto.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.jianghu66.top/Article/details/gtaonkchaf.html

[R36] 并发执行多个任务
来源：http://dali.zhiwuduotai.top/Article/details/gtskuspoxy.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.nanxinkj.top/Article/details/gttklhfwyy.html

[R37] 把输出赋给变量
来源：http://dali.hysaishi.cn/Article/details/gtgeozbzud.html

files=$(ls -1)
来源：http://dali.zhixingplan.top/Article/details/gtpwrnjuhl.html

[R38] 管道串联
来源：http://dali.yj20258.top/Article/details/gtxksallgu.html

cat a.txt | grep -i error | wc -l
来源：http://dali.yongpay.top/Article/details/gtyizjdnfo.html

[R39] 重定向标准输出与错误
来源：http://dali.shuidangran.top/Article/details/gtmmjgvrxu.html

cmd > out.log 2>&1
来源：http://dali.yonumen.top/Article/details/gtrvhrldiy.html

[R40] 追加写日志
来源：http://dali.0kj1m.cn/Article/details/gtxaywrahk.html

echo "log" >> out.log
来源：http://dali.mhx1999.top/Article/details/gtmpihynfm.html

[R41] 丢弃输出
来源：http://dali.chenjidiqi.icu/Article/details/gtwsfpiuze.html

cmd >/dev/null 2>&1
来源：http://dali.quarkkingdee.top/Article/details/gtdyohjvpw.html

[R42] 输入重定向
来源：http://dali.ydzc1.top/Article/details/gtuskqyzit.html

wc -l < a.txt
来源：http://dali.aizwys.cn/Article/details/gtzlrprsrp.html

[R43] 按名字查找文件
来源：http://dali.cqqwz.cn/Article/details/gtlfsllsgu.html

find . -name "*.log" -type f
来源：http://dali.chenzaomai.com/Article/details/gtfnollgds.html

[R44] 按修改时间查找
来源：http://dali.nwbrower.top/Article/details/gtcdbhrpho.html

find . -mtime -7 -type f
来源：http://dali.svipenyu.cn/Article/details/gtjnstdkyq.html

[R45] 批量删除
来源：http://dali.jlsjyb.cn/Article/details/gtclhffoki.html

find . -name "*.tmp" -delete
来源：http://dali.c1oappe.top/Article/details/gtufjfgivg.html

[R46] 递归替换文件内容
来源：http://dali.xylfe.cn/Article/details/gtozmmfcbp.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.wangshuangyany.cn/Article/details/gtqxhqqhge.html

[R47] sed 单行替换
来源：http://dali.ybcxt.top/Article/details/gtqmmyecha.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.yvedp.cn/Article/details/gtlxutaivi.html

[R48] awk 取指定列
来源：http://dali.zhaomingkeji.xyz/Article/details/gtynedfhix.html

awk '{print $1, $3}' a.txt
来源：http://dali.gogol.net.cn/Article/details/gtsrjfhvbq.html

[R49] awk 带条件
来源：http://dali.haohaochexian.top/Article/details/gtflrsyebk.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.sufxvd.cn/Article/details/gttppowuyv.html

[R50] awk 求和
来源：http://dali.jinqigufen.top/Article/details/gtjbvulicm.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.xinyue.icu/Article/details/gtwgvmcdfm.html

[R51] 排序去重取前几
来源：http://dali.jlsjyb.cn/Article/details/gtrzonzfqn.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.wangdashe.top/Article/details/gtnnrybero.html

[R52] 统计行数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtacnvcmad.html

wc -l a.txt
来源：http://dali.iojbl.cn/Article/details/gtvplxchds.html

[R53] 查看文件头与实时尾
来源：http://dali.bjfxy.top/Article/details/gtwxgpdbha.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.andypj.xyz/Article/details/gthtaotzdi.html

[R54] 比较两个文件
来源：http://dali.jinqigufen.top/Article/details/gticrnhjce.html

diff a.txt b.txt
来源：http://dali.guannengcc.top/Article/details/gttolyzjsc.html

[R55] 压缩与解压
来源：http://dali.redwolf501.top/Article/details/gtikmejbtw.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.redwolf501.top/Article/details/gtnvhozujb.html

[R56] 远程拷贝
来源：http://dali.sysykeji.top/Article/details/gtwvxskmna.html

scp file user@host:/path/
来源：http://dali.jinghuilouyu.cn/Article/details/gtniqzdbsi.html

[R57] 远程执行命令
来源：http://dali.yuxming.cn/Article/details/gtdolsczek.html

ssh user@host 'uptime'
来源：http://dali.shanyushiyangtech.top/Article/details/gtdpdlrfwq.html

[R58] 下载文件
来源：http://dali.hywenlv.cn/Article/details/gtbcipmmgc.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.cqqwz.cn/Article/details/gtuihxghek.html

[R59] 发 POST JSON
来源：http://dali.meibo888.top/Article/details/gtepticlni.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.sufxvd.cn/Article/details/gtzrhziktp.html

[R60] 只看 HTTP 状态码
来源：http://dali.cqqwz.cn/Article/details/gtaknlwsod.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.daxiang520.top/Article/details/gtywjwmfmm.html

[R61] 磁盘占用
来源：http://dali.birdmap.top/Article/details/gtvnxsssmb.html

df -h;  du -sh *
来源：http://dali.0kj1m.cn/Article/details/gtlzgdnzqs.html

[R62] 找最占空间的文件
来源：http://dali.jqgufenzy.top/Article/details/gtrkxscabp.html

du -ah . | sort -rh | head -10
来源：http://dali.gzhubu.top/Article/details/gtzlwktpsn.html

[R63] 内存与进程
来源：http://dali.nanxuanxn.top/Article/details/gtytlxikgc.html

free -h;  ps aux | grep nginx
来源：http://dali.yongpay.top/Article/details/gtkmcporpo.html

[R64] 结束进程
来源：http://dali.yuanzhike.top/Article/details/gtqpboppci.html

kill -9 $(pgrep -f app.py)
来源：http://dali.cheryme.top/Article/details/gtcdigpsno.html

[R65] 查看端口占用
来源：http://dali.sysykeji.top/Article/details/gttoybgfql.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.xuanzx.com/Article/details/gtfpsftjxs.html

[R66] 定时任务
来源：http://dali.9152youxi.cn/Article/details/gttizxevwb.html

crontab -e;  crontab -l
来源：http://dali.yuxming.cn/Article/details/gtfhnhzmgp.html

[R67] 生成随机十六进制串
来源：http://dali.cdnleiting.top/Article/details/gtaezmkvov.html

openssl rand -hex 16
来源：http://dali.sysykeji.top/Article/details/gttwentitm.html

[R68] 计算文件校验值
来源：http://dali.fzhhl.top/Article/details/gtartxcrzg.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.cqqwz.cn/Article/details/gtfoaufqpg.html

[R69] 生成随机密码
来源：http://dali.yj20258888.top/Article/details/gtwnruziph.html

head -c 16 /dev/urandom | base64
来源：http://dali.cashguo.top/Article/details/gtikcswidl.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gtnhtkrxlt.html

date +%s;  date -d @1700000000
来源：http://dali.yj202588.top/Article/details/gtwubszjuc.html

[R71] 日期格式化
来源：http://dali.cheryme.top/Article/details/gtftbzunxe.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsisaxgoe.html

[R72] 等待端口就绪
来源：http://dali.xinyue.icu/Article/details/gtkoadiwxf.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.cucudq.cn/Article/details/gtspdujloc.html

[R73] 分割大日志
来源：http://dali.sufxvd.cn/Article/details/gtgbqrlbrm.html

split -l 1000 big.log part_
来源：http://dali.jyoumei.cn/Article/details/gtjnuhmtqc.html

[R74] 批量重命名
来源：http://dali.ehwqpu.com/Article/details/gtutucrgsv.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.yuanzhike.top/Article/details/gtusdtjsmi.html

[R75] 导出环境变量
来源：http://dali.cqqwz.cn/Article/details/gtmfhxwxze.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.sxryk.cn/Article/details/gtliutvqea.html

[R76] 使用临时文件
来源：http://dali.smart0.xyz/Article/details/gtunudbwvf.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.yuanzhike.top/Article/details/gtkiniiiry.html

[R77] 读取用户输入
来源：http://dali.hysaishi.cn/Article/details/gttelgcijx.html

read -rp "请输入: " ans
来源：http://dali.hnqzz.top/Article/details/gtjhgldhsa.html

[R78] 交互式菜单
来源：http://dali.cucudq.cn/Article/details/gtrxpuqvdf.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.ydzc1.top/Article/details/gtgeahmaiy.html

[R79] 解析命令行选项
来源：http://dali.0kj1m.cn/Article/details/gtwjdoxelb.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.svipenyu.cn/Article/details/gtdkmchszd.html

[R80] 查看脚本执行耗时
来源：http://dali.snrcjt.cn/Article/details/gtyfmpevlj.html

time ./run.sh
来源：http://dali.wangdashe.top/Article/details/gtnhbqwqfs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtybkymszj.html

S. C / C++ 专题
来源：http://dali.pycfn.com/Article/details/gtdugbzlzn.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtvkygqjex.html

[S01] C：Hello World
来源：http://dali.zhiwuduotai.top/Article/details/gtrbokumen.html

#include <stdio.h>
来源：http://dali.yuxming.cn/Article/details/gtatbmccpr.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.cheryme.top/Article/details/gtghoeeysl.html

[S02] C：变量与格式化输出
来源：http://dali.gzhubu.top/Article/details/gtxemqjoqd.html

int a = 10; printf("%d\n", a);
来源：http://dali.dianchejie.cn/Article/details/gtwwfldtki.html

[S03] C：读入整数
来源：http://dali.hammf.cn/Article/details/gtjedrwebi.html

int x; scanf("%d", &x);
来源：http://dali.aibaodan.cn/Article/details/gtdrnxbprk.html

[S04] C：字符串复制
来源：http://dali.jiagoushi.top/Article/details/gtixdaxqgt.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.fzhhl.top/Article/details/gtuexiznam.html

[S05] C：字符串长度
来源：http://dali.shuidangran.top/Article/details/gttvdrbcsg.html

strlen(s)
来源：http://dali.shangyingyoupin.top/Article/details/gtopuntqwn.html

[S06] C：字符串比较
来源：http://dali.cucudq.cn/Article/details/gtnappzepf.html

strcmp(a, b) == 0
来源：http://dali.shuidangran.top/Article/details/gtsafvsdra.html

[S07] C：数组遍历求和
来源：http://dali.wangshuangyany.cn/Article/details/gtarqrebnc.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.cqqwz.cn/Article/details/gtqregyvge.html

[S08] C：动态内存分配与释放
来源：http://dali.gzhubu.top/Article/details/gtsiqodibl.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.yj20258888.top/Article/details/gtwdxkdzdl.html

[S09] C：结构体定义与初始化
来源：http://dali.hongshengwenyu.top/Article/details/gtjvlofdfo.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.pycfn.com/Article/details/gtvtjrxjkr.html

[S10] C：指针与解引用
来源：http://dali.hnxiangtu.top/Article/details/gtxnaeqgun.html

int *p = &a;  *p = 5;
来源：http://dali.jyoumei.cn/Article/details/gtuywdnwuk.html

[S11] C：逐行读文件
来源：http://dali.zhixingplan.top/Article/details/gtpsgrlqbw.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.gaohongyu789.top/Article/details/gtmuoeeukv.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.pycfn.com/Article/details/gtsdkypwix.html

fclose(f);
来源：http://dali.smart0.xyz/Article/details/gtkiaxbnlb.html

[S12] C：写文件
来源：http://dali.chenzaomai.com/Article/details/gtvdmhbasy.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.gaohongyu789.top/Article/details/gtpopagwiq.html

[S13] C：宏定义
来源：http://dali.sysykeji.top/Article/details/gtjmuwlmbm.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.daxiang520.top/Article/details/gtxcdwcjhx.html

[S14] C：枚举
来源：http://dali.zhoulong.xyz/Article/details/gtyvdavuox.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.shanyushiyangtech.top/Article/details/gtjzupxjwm.html

[S15] C：类型转换
来源：http://dali.xuetiantiany.cn/Article/details/gtlzcadzwp.html

(double) a / b
来源：http://dali.guannengcc.top/Article/details/gtszlcunlq.html

[S16] C：位操作置位
来源：http://dali.hnxiangtu.top/Article/details/gttihxqlzi.html

x |= (1 << 3);
来源：http://dali.yangfankeji.com/Article/details/gtzrjlwjwn.html

[S17] C：安全拼接字符串
来源：http://dali.hywenlv.cn/Article/details/gtmbkvuqxj.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.yuanzhike.top/Article/details/gtgojfsaze.html

[S18] C：命令行参数
来源：http://dali.jyoumei.cn/Article/details/gtjohmhehu.html

int main(int argc, char **argv)
来源：http://dali.dianchejie.cn/Article/details/gtjtgettpp.html

[S19] C：快速排序
来源：http://dali.cdnleiting.top/Article/details/gtstwdkkuf.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.chenlongwang.top/Article/details/gtqoxwtlpb.html

[S20] C：二分查找
来源：http://dali.yvedp.cn/Article/details/gtrezkqmjo.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.cheryme.top/Article/details/gtqrysjwbb.html

[S21] C：字符类别判断
来源：http://dali.sufxvd.cn/Article/details/gtrpvylrpv.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.jinyuanbaomall.cn/Article/details/gttafjzcbs.html

[S22] C：字符串转数字
来源：http://dali.chenzaomai.com/Article/details/gtftoqofkb.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.xuetiantiany.cn/Article/details/gtqficoazx.html

[S23] C：随机数
来源：http://dali.feifeiyinyue.top/Article/details/gtgimdkvfa.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.ybcxt.top/Article/details/gtgqhucnmg.html

[S24] C：获取本地时间
来源：http://dali.xuetiantiany.cn/Article/details/gtvjrcayag.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhixingplan.top/Article/details/gthykadwzt.html

[S25] C：内存拷贝
来源：http://dali.quarkkingdee.top/Article/details/gtdgbcqmml.html

memcpy(dst, src, n);
来源：http://dali.hnqzz.top/Article/details/gtoreyovnk.html

[S26] C：内存清零
来源：http://dali.fzhhl.top/Article/details/gtyryywidz.html

memset(a, 0, sizeof a);
来源：http://dali.yangfankeji.com/Article/details/gtlcprikxl.html

[S27] C：定义常量
来源：http://dali.zycfv.cn/Article/details/gtufveluwu.html

const double PI = 3.14159;
来源：http://dali.jyoumei.cn/Article/details/gtcoxyjxwk.html

[S28] C：静态变量
来源：http://dali.sxryk.cn/Article/details/gtjkacgenz.html

static int counter = 0;
来源：http://dali.dianchejie.cn/Article/details/gtadakysws.html

[S29] C：变参函数
来源：http://dali.birdmap.top/Article/details/gtbxjwlqym.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.316326.xyz/Article/details/gthdpyjvyk.html

[S30] C：头文件保护
来源：http://dali.zhengqikj.top/Article/details/gtlpsjhocz.html

#ifndef X_H
来源：http://dali.tanke756.top/Article/details/gtmqhuyxos.html

#define X_H
来源：http://dali.shanyushiyangtech.top/Article/details/gtundtvdso.html

#endif
来源：http://dali.tanke756.top/Article/details/gtunhofjtf.html

[S31] C++：Hello World
来源：http://dali.gotoacloud.top/Article/details/gtgutekybj.html

#include <iostream>
来源：http://dali.sufxvd.cn/Article/details/gtbqbxamvp.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zycfv.cn/Article/details/gtozjltpwn.html

[S32] C++：字符串
来源：http://dali.shuidangran.top/Article/details/gtlyervloe.html

std::string s = "hi";  s += "!";
来源：http://dali.redwolf501.top/Article/details/gtcftveioy.html

[S33] C++：vector 增删
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpalsakvy.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.haohaochexian.top/Article/details/gtelmbseop.html

[S34] C++：遍历 vector
来源：http://dali.guannengcc.top/Article/details/gtcgufvrru.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.jianghu66.top/Article/details/gtjyiwomjb.html

[S35] C++：map
来源：http://dali.hammf.cn/Article/details/gttrbrilst.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.shangyingyoupin.top/Article/details/gtbckwetkb.html

[S36] C++：unordered_map
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjooabeal.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfuzabbpz.html

[S37] C++：set
来源：http://dali.xinyue.icu/Article/details/gtlzwcnbog.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.yvedp.cn/Article/details/gtimqbvabu.html

[S38] C++：排序
来源：http://dali.ybcxt.top/Article/details/gtsqsjkqdr.html

std::sort(v.begin(), v.end());
来源：http://dali.hfpthk.cn/Article/details/gtzkttlkmg.html

[S39] C++：自定义比较器排序
来源：http://dali.haohaochexian.top/Article/details/gtfuwtcsbh.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zdqjudy.top/Article/details/gtvpggbhst.html

[S40] C++：查找元素
来源：http://dali.9152youxi.cn/Article/details/gttzgnnybn.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zycfv.cn/Article/details/gttaliqnrn.html

[S41] C++：类与构造函数
来源：http://dali.bjfxy.top/Article/details/gtqezqpyre.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.dashuyun.cn/Article/details/gtotaizalf.html

[S42] C++：继承与虚函数
来源：http://dali.kuanghao11.cn/Article/details/gthlkueeop.html

class B : public Base { public: void f() override {} };
来源：http://dali.pengpengdd.cyou/Article/details/gtxwrbktsu.html

[S43] C++：智能指针
来源：http://dali.daxiang520.top/Article/details/gtponfexsj.html

auto p = std::make_unique<int>(5);
来源：http://dali.snrcjt.cn/Article/details/gtsvdarfvc.html

[S44] C++：引用传参
来源：http://dali.chenzaomai.com/Article/details/gtwcszvfgf.html

void inc(int &x) { ++x; }
来源：http://dali.cashguo.top/Article/details/gtgpazanwu.html

[S45] C++：lambda
来源：http://dali.nwbrower.top/Article/details/gthikfgnps.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.nwbrower.top/Article/details/gtqtfnpydj.html

[S46] C++：函数模板
来源：http://dali.shuidangran.top/Article/details/gtsbflxkgy.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.havefunace.top/Article/details/gtlpdomqeg.html

[S47] C++：结构化绑定遍历
来源：http://dali.guannengcc.top/Article/details/gtfyzzngxq.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.yongpay.top/Article/details/gtlvqcdxui.html

[S48] C++：逐行读文件
来源：http://dali.xuetiantiany.cn/Article/details/gtoqggqcoo.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.hammf.cn/Article/details/gtlnazuafq.html

while (std::getline(in, line)) { }
来源：http://dali.cashguo.top/Article/details/gtcvfrohkh.html

[S49] C++：写文件
来源：http://dali.pycfn.com/Article/details/gtmejautwb.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.jiagoushi.top/Article/details/gtcbuysacq.html

[S50] C++：格式化数字
来源：http://dali.sufxvd.cn/Article/details/gtpdweejgs.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.birdmap.top/Article/details/gtprklbfcs.html

[S51] C++：显式类型转换
来源：http://dali.daria6918.cn/Article/details/gtuuqvupib.html

static_cast<double>(a) / b
来源：http://dali.quarkkingdee.top/Article/details/gtkbzrpwyq.html

[S52] C++：const 与 noexcept
来源：http://dali.ywan-chungtsiang.top/Article/details/gtujbnbpmu.html

int size() const noexcept { return n_; }
来源：http://dali.zhoulong.xyz/Article/details/gtptjfaszx.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gtquswfeyf.html

std::vector<int> w = std::move(v);
来源：http://dali.nanxinkj.top/Article/details/gtgxbpupie.html

[S54] C++：异常处理
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkytpgzpr.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.yj20258.top/Article/details/gtlrhsaxxh.html

[S55] C++：结构化绑定
来源：http://dali.jiagoushi.top/Article/details/gtnylikvad.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.quarkkingdee.top/Article/details/gtczypaful.html

[S56] C++：optional
来源：http://dali.cdnleiting.top/Article/details/gtsjeoobmk.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.hongshengwenyu.top/Article/details/gtruvxdwyo.html

[S57] C++：编译期常量
来源：http://dali.yueranfly.top/Article/details/gtzceozebo.html

constexpr int N = 10;
来源：http://dali.ehwqpu.com/Article/details/gtsqtinobs.html

[S58] C++：命名空间
来源：http://dali.jiagoushi.top/Article/details/gteeenvqav.html


<!-- 参考信息 -->