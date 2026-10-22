代发 wailian999

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.guowangkeji.top/Article/details/gtdumgiuzv.html

[Q90] 生成序号列
来源：http://dali.daxiang520.top/Article/details/gtfphqttoy.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.ydzc1.top/Article/details/gtatodebrf.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtinhxpvgw.html

R. Bash 专题
来源：http://dali.fengsongda.top/Article/details/gttzfxkdxp.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtsiulabmp.html

[R01] shebang 与严格模式
来源：http://dali.shangyingyoupin.top/Article/details/gtxibnxvbr.html

#!/usr/bin/env bash
来源：http://dali.zhoulong.xyz/Article/details/gtgaeaeork.html

set -euo pipefail
来源：http://dali.cheryme.top/Article/details/gtdnrykilr.html

[R02] 变量赋值与使用
来源：http://dali.zdqjudy.top/Article/details/gtqzlfzbdq.html

name="Tom"; echo "$name"
来源：http://dali.cqqwz.cn/Article/details/gtqewlqbtq.html

[R03] 只读变量
来源：http://dali.sysykeji.top/Article/details/gttrnpexra.html

readonly PI=3.14
来源：http://dali.9152youxi.cn/Article/details/gtdcdljlmf.html

[R04] 位置参数
来源：http://dali.xuetiantiany.cn/Article/details/gtruncfatp.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.cdnleiting.top/Article/details/gtnkfmxras.html

[R05] 参数默认值
来源：http://dali.cashguo.top/Article/details/gtutkquvwr.html

name="${1:-default}"
来源：http://dali.aizwys.cn/Article/details/gtyfevdkam.html

[R06] 判断命令是否存在
来源：http://dali.chenjidiqi.icu/Article/details/gtunkkbdtn.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.shangyingyoupin.top/Article/details/gtolnklioi.html

[R07] if 判断文件
来源：http://dali.hfpthk.cn/Article/details/gtmagmytyn.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.yanxiufei.cn/Article/details/gttvwdvpqx.html

[R08] 数值比较
来源：http://dali.yonumen.top/Article/details/gtkjdgeisl.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.wangshuangyany.cn/Article/details/gthiooxzgp.html

[R09] 字符串比较
来源：http://dali.cheryme.top/Article/details/gtmfvptnli.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.yangfankeji.com/Article/details/gtpktbhsoz.html

[R10] 正则匹配
来源：http://dali.svipenyu.cn/Article/details/gttkcgsbrk.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.yongpay.top/Article/details/gttsgatnha.html

[R11] case 多分支
来源：http://dali.haohaochexian.top/Article/details/gtrqwuxkha.html

case "$1" in
来源：http://dali.wangdashe.top/Article/details/gtrgtlfjbu.html

start) echo "启动" ;;
来源：http://dali.316326.xyz/Article/details/gtlwiqdjrt.html

stop)  echo "停止" ;;
来源：http://dali.zhengqikj.top/Article/details/gtiurqyuxs.html

*)     echo "未知命令" ;;
来源：http://dali.guannengcc.top/Article/details/gtnthsmliq.html

esac
来源：http://dali.cucudq.cn/Article/details/gtbnpwelpm.html

[R12] for 遍历文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttlyrzwck.html

for f in *.txt; do echo "$f"; done
来源：http://dali.chenlongwang.top/Article/details/gtzpwjxwbr.html

[R13] for 计数循环
来源：http://dali.mhx1999.top/Article/details/gtoyqlorxg.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.yj20258888.top/Article/details/gtvfzmtwpu.html

[R14] C 风格 for
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxpokhptu.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.jqgfzy.top/Article/details/gtafflxjzh.html

[R15] while 逐行读文件
来源：http://dali.yvedp.cn/Article/details/gtihyadomy.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.fzhhl.top/Article/details/gtnyonmqlz.html

[R16] until 等待条件
来源：http://dali.chenjidiqi.icu/Article/details/gtzjbhsjzy.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.bjfxy.top/Article/details/gtwgalgxyn.html

[R17] 数组定义与取值
来源：http://dali.vqdsnc.cn/Article/details/gtbbxkrrmu.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.sufxvd.cn/Article/details/gtjqgubifb.html

[R18] 遍历数组
来源：http://dali.dashuyun.cn/Article/details/gtjrysikyc.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.feifeiyinyue.top/Article/details/gtznlagtzu.html

[R19] 数组长度
来源：http://dali.zhiwuduotai.top/Article/details/gtwqwyvfuq.html

echo "${#arr[@]}"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaakulaoq.html

[R20] 关联数组（字典）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgxasopsc.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.yj20258.top/Article/details/gtvfsxvpvd.html

[R21] 字符串长度
来源：http://dali.andypj.xyz/Article/details/gtiqwezyeh.html

echo "${#s}"
来源：http://dali.dashuyun.cn/Article/details/gtysfrdylz.html

[R22] 截取子串
来源：http://dali.shanyushiyangtech.top/Article/details/gtrxiimdmk.html

echo "${s:0:5}"
来源：http://dali.iojbl.cn/Article/details/gtbdkpuypd.html

[R23] 字符串替换
来源：http://dali.tanke756.top/Article/details/gtgrocadjj.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.tianlin.xyz/Article/details/gtkzbyluut.html

[R24] 大小写转换
来源：http://dali.hywenlv.cn/Article/details/gtuvsmpmuc.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.xinyue.icu/Article/details/gtyqgmwvia.html

[R25] 去后缀 / 去前缀
来源：http://dali.tianlin.xyz/Article/details/gtrwxyvbwn.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.aizwys.cn/Article/details/gtzhxplllj.html

[R26] 命令替换
来源：http://dali.zhaomingkeji.xyz/Article/details/gtinumwpfw.html

now=$(date +%F); echo "$now"
来源：http://dali.tian-w.cn/Article/details/gtmgmzgemn.html

[R27] 算术展开
来源：http://dali.jlsjyb.cn/Article/details/gtngufdhyy.html

echo $((1 + 2 * 3))
来源：http://dali.ehwqpu.com/Article/details/gtgutavtrk.html

[R28] 浮点运算
来源：http://dali.zdqjudy.top/Article/details/gtlpishkyv.html

echo "scale=2; 10/3" | bc
来源：http://dali.snrcjt.cn/Article/details/gtlgtuurpm.html

[R29] 定义函数
来源：http://dali.zhixingplan.top/Article/details/gtmwgcokcu.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.gaohongyu789.top/Article/details/gtlqhgqsxj.html

[R30] 函数返回状态码
来源：http://dali.sysykeji.top/Article/details/gtyfawniac.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhengqikj.top/Article/details/gtcmiioiom.html

[R31] 局部变量
来源：http://dali.jqgfzy.top/Article/details/gtftymxsnx.html

f() { local x=1; echo "$x"; }
来源：http://dali.wangshuangyany.cn/Article/details/gtvqhagoyz.html

[R32] 参数个数校验
来源：http://dali.yj20258.top/Article/details/gtxlwjyjso.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.ydzc1.top/Article/details/gtrdkirpjh.html

[R33] 捕获错误并提示行号
来源：http://dali.hfpthk.cn/Article/details/gtijyknleu.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.yanxiufei.cn/Article/details/gtzrvehwir.html

[R34] 退出时清理
来源：http://dali.cucudq.cn/Article/details/gtfxtuylum.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.jqgfzy.top/Article/details/gtkzncixyk.html

[R35] 后台执行并等待
来源：http://dali.guannengcc.top/Article/details/gtazmyizpm.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.shzxlz.cn/Article/details/gtkazzqyzx.html

[R36] 并发执行多个任务
来源：http://dali.fengsongda.top/Article/details/gthikdknhz.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.aizwys.cn/Article/details/gtmrdywhmq.html

[R37] 把输出赋给变量
来源：http://dali.ybcxt.top/Article/details/gtrnnfjeyf.html

files=$(ls -1)
来源：http://dali.zhixingplan.top/Article/details/gtbrfeoswy.html

[R38] 管道串联
来源：http://dali.yangfankeji.com/Article/details/gtmgjklkpt.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkzythtfw.html

[R39] 重定向标准输出与错误
来源：http://dali.quarkkingdee.top/Article/details/gtpqrtoltu.html

cmd > out.log 2>&1
来源：http://dali.mhx1999.top/Article/details/gtqzghgmdm.html

[R40] 追加写日志
来源：http://dali.sufxvd.cn/Article/details/gtpybxdwjq.html

echo "log" >> out.log
来源：http://dali.shanyushiyangtech.top/Article/details/gtmhsipgwp.html

[R41] 丢弃输出
来源：http://dali.haohaochexian.top/Article/details/gtuabkqkju.html

cmd >/dev/null 2>&1
来源：http://dali.cheryme.top/Article/details/gtkezaocbm.html

[R42] 输入重定向
来源：http://dali.tianlin.xyz/Article/details/gtaawvcagi.html

wc -l < a.txt
来源：http://dali.pengpengdd.cyou/Article/details/gtaftpwjvi.html

[R43] 按名字查找文件
来源：http://dali.yanxiufei.cn/Article/details/gtcxdxbgko.html

find . -name "*.log" -type f
来源：http://dali.nwbrower.top/Article/details/gthhqzwaed.html

[R44] 按修改时间查找
来源：http://dali.guowangkeji.top/Article/details/gtwwwqvryn.html

find . -mtime -7 -type f
来源：http://dali.sxryk.cn/Article/details/gtpxeukoqz.html

[R45] 批量删除
来源：http://dali.chenlongwang.top/Article/details/gtiznllwss.html

find . -name "*.tmp" -delete
来源：http://dali.zhoulong.xyz/Article/details/gtoezoetlu.html

[R46] 递归替换文件内容
来源：http://dali.shanyushiyangtech.top/Article/details/gtdxyrlyno.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.jlsjyb.cn/Article/details/gtoawsmelj.html

[R47] sed 单行替换
来源：http://dali.jiagoushi.top/Article/details/gtlxmjylml.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.shanyushiyangtech.top/Article/details/gtiklxsnbf.html

[R48] awk 取指定列
来源：http://dali.9152youxi.cn/Article/details/gtrsqvhwxz.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhoulong.xyz/Article/details/gtniexttkw.html

[R49] awk 带条件
来源：http://dali.birdmap.top/Article/details/gtjlyrxgln.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.xinyue.icu/Article/details/gtxsbailex.html

[R50] awk 求和
来源：http://dali.tianlin.xyz/Article/details/gtvocmlgmc.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.dashuyun.cn/Article/details/gtvwbgmnba.html

[R51] 排序去重取前几
来源：http://dali.yuxming.cn/Article/details/gtsfsyxnvx.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.yueranfly.top/Article/details/gtjegjtrcl.html

[R52] 统计行数
来源：http://dali.yonumen.top/Article/details/gtrwdsmvgg.html

wc -l a.txt
来源：http://dali.guowangkeji.top/Article/details/gthcixdksd.html

[R53] 查看文件头与实时尾
来源：http://dali.smart0.xyz/Article/details/gtxosurvhc.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.cucudq.cn/Article/details/gtfkatfzdu.html

[R54] 比较两个文件
来源：http://dali.cqqwz.cn/Article/details/gtozvoqkja.html

diff a.txt b.txt
来源：http://dali.jqgufenzy.top/Article/details/gtukkjmvaa.html

[R55] 压缩与解压
来源：http://dali.feifeiyinyue.top/Article/details/gtdjgfdrnc.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.nanxuanxn.top/Article/details/gtdkqrekby.html

[R56] 远程拷贝
来源：http://dali.yanxiufei.cn/Article/details/gtmknofvjl.html

scp file user@host:/path/
来源：http://dali.cucudq.cn/Article/details/gtngeyzerw.html

[R57] 远程执行命令
来源：http://dali.tianlin.xyz/Article/details/gtpvggdmct.html

ssh user@host 'uptime'
来源：http://dali.quarkkingdee.top/Article/details/gtnfdzfixd.html

[R58] 下载文件
来源：http://dali.c1oappe.top/Article/details/gtzuoxlnlt.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.yonumen.top/Article/details/gtdntfbumg.html

[R59] 发 POST JSON
来源：http://dali.hnxiangtu.top/Article/details/gtfjrgaowb.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhengqikj.top/Article/details/gtxoapidnd.html

[R60] 只看 HTTP 状态码
来源：http://dali.hongshengwenyu.top/Article/details/gtiuniofnc.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.vqdsnc.cn/Article/details/gtnpjxfoab.html

[R61] 磁盘占用
来源：http://dali.nwbrower.top/Article/details/gtxtkabmkj.html

df -h;  du -sh *
来源：http://dali.jqgfzy.top/Article/details/gtomgjhfgc.html

[R62] 找最占空间的文件
来源：http://dali.hnqzz.top/Article/details/gtvturjkjx.html

du -ah . | sort -rh | head -10
来源：http://dali.dianchejie.cn/Article/details/gtbjbjkkcw.html

[R63] 内存与进程
来源：http://dali.tian-w.cn/Article/details/gtgskygbnn.html

free -h;  ps aux | grep nginx
来源：http://dali.ybcxt.top/Article/details/gthivwhdnd.html

[R64] 结束进程
来源：http://dali.sxryk.cn/Article/details/gtzfaltkpr.html

kill -9 $(pgrep -f app.py)
来源：http://dali.aibaodan.cn/Article/details/gtvxoclmjx.html

[R65] 查看端口占用
来源：http://dali.gzhubu.top/Article/details/gtreohdvpk.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.yuxming.cn/Article/details/gtyoeghvyl.html

[R66] 定时任务
来源：http://dali.yj202588.top/Article/details/gtxkazuckt.html

crontab -e;  crontab -l
来源：http://dali.hywenlv.cn/Article/details/gtilzqkohl.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gtqehfcybf.html

openssl rand -hex 16
来源：http://dali.birdmap.top/Article/details/gtudsdxvuy.html

[R68] 计算文件校验值
来源：http://dali.yanxiufei.cn/Article/details/gtflrcqsmu.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.ybcxt.top/Article/details/gtchxeljei.html

[R69] 生成随机密码
来源：http://dali.pengpengdd.cyou/Article/details/gtmpsibvvz.html

head -c 16 /dev/urandom | base64
来源：http://dali.zycfv.cn/Article/details/gtdmenkvit.html

[R70] 时间戳与互转
来源：http://dali.dianchejie.cn/Article/details/gtkzjioctl.html

date +%s;  date -d @1700000000
来源：http://dali.svipenyu.cn/Article/details/gtowgwikkx.html

[R71] 日期格式化
来源：http://dali.sweek.top/Article/details/gtrsajckmn.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.hysaishi.cn/Article/details/gtccohytma.html

[R72] 等待端口就绪
来源：http://dali.jiagoushi.top/Article/details/gtedqpdfko.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhoulong.xyz/Article/details/gtqqqokiwl.html

[R73] 分割大日志
来源：http://dali.vqdsnc.cn/Article/details/gtlvzbcqqv.html

split -l 1000 big.log part_
来源：http://dali.redwolf501.top/Article/details/gtpmpymbbe.html

[R74] 批量重命名
来源：http://dali.quarkkingdee.top/Article/details/gtsmeuwtox.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.guowangkeji.top/Article/details/gtwsslsvgp.html

[R75] 导出环境变量
来源：http://dali.haohaochexian.top/Article/details/gtjsvbbwol.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.gzhubu.top/Article/details/gtifefcthm.html

[R76] 使用临时文件
来源：http://dali.jlsjyb.cn/Article/details/gtuafgkcvp.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.birdmap.top/Article/details/gtqijjkdlv.html

[R77] 读取用户输入
来源：http://dali.yvedp.cn/Article/details/gtwrbdaywg.html

read -rp "请输入: " ans
来源：http://dali.shzxlz.cn/Article/details/gtowkhuant.html

[R78] 交互式菜单
来源：http://dali.guowangkeji.top/Article/details/gtagmyepjb.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.9152youxi.cn/Article/details/gtzaymtqeg.html

[R79] 解析命令行选项
来源：http://dali.shzxlz.cn/Article/details/gtlyyhdjxy.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.jlsjyb.cn/Article/details/gtucerjros.html

[R80] 查看脚本执行耗时
来源：http://dali.yuxming.cn/Article/details/gtrdxipjsi.html

time ./run.sh
来源：http://dali.sufxvd.cn/Article/details/gtbvzmubeu.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtfnfydkug.html

S. C / C++ 专题
来源：http://dali.jyoumei.cn/Article/details/gttzpoqhgu.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtxxvcemmk.html

[S01] C：Hello World
来源：http://dali.nanxinkj.top/Article/details/gtqugfkdtm.html

#include <stdio.h>
来源：http://dali.gzhubu.top/Article/details/gtojdpnhhx.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zycfv.cn/Article/details/gtrzyxhoaf.html

[S02] C：变量与格式化输出
来源：http://dali.hysaishi.cn/Article/details/gtwoycmxtr.html

int a = 10; printf("%d\n", a);
来源：http://dali.cdnleiting.top/Article/details/gtdmhpgxmd.html

[S03] C：读入整数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsafwnqyb.html

int x; scanf("%d", &x);
来源：http://dali.zhixingplan.top/Article/details/gtwbzmxjwt.html

[S04] C：字符串复制
来源：http://dali.meibo888.top/Article/details/gtzegyziis.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.yuanzhike.top/Article/details/gtgavftrvh.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gtpnjcrtuz.html

strlen(s)
来源：http://dali.316326.xyz/Article/details/gtwznzvsgo.html

[S06] C：字符串比较
来源：http://dali.9152youxi.cn/Article/details/gtpejqqygq.html

strcmp(a, b) == 0
来源：http://dali.316326.xyz/Article/details/gtuvlwpwxr.html

[S07] C：数组遍历求和
来源：http://dali.chenjidiqi.icu/Article/details/gtujueoeqb.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.smart0.xyz/Article/details/gtdpzknpzd.html

[S08] C：动态内存分配与释放
来源：http://dali.iojbl.cn/Article/details/gtrcrpleqs.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.aibaodan.cn/Article/details/gtqdzpomvk.html

[S09] C：结构体定义与初始化
来源：http://dali.jyoumei.cn/Article/details/gtjrlomsxi.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwhuyolwh.html

[S10] C：指针与解引用
来源：http://dali.hnxiangtu.top/Article/details/gtuixfopur.html

int *p = &a;  *p = 5;
来源：http://dali.svipenyu.cn/Article/details/gtwsnrhniu.html

[S11] C：逐行读文件
来源：http://dali.snrcjt.cn/Article/details/gtmsmwzday.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrkmielpd.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.cqqwz.cn/Article/details/gtrxsaimjn.html

fclose(f);
来源：http://dali.tian-w.cn/Article/details/gtkgyabfkn.html

[S12] C：写文件
来源：http://dali.yonumen.top/Article/details/gtdsinpbdp.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.0kj1m.cn/Article/details/gtbkmzkwss.html

[S13] C：宏定义
来源：http://dali.xuanzx.com/Article/details/gtgcflqlwo.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.316326.xyz/Article/details/gtzcvewyjq.html

[S14] C：枚举
来源：http://dali.zycfv.cn/Article/details/gtxacgbfvw.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhoulong.xyz/Article/details/gtqqwniock.html

[S15] C：类型转换
来源：http://dali.jiagoushi.top/Article/details/gttucvbify.html

(double) a / b
来源：http://dali.cucudq.cn/Article/details/gtdakdrfcc.html

[S16] C：位操作置位
来源：http://dali.jinghuilouyu.cn/Article/details/gthgrowmce.html

x |= (1 << 3);
来源：http://dali.zhengqikj.top/Article/details/gtjwcxqevs.html

[S17] C：安全拼接字符串
来源：http://dali.haohaochexian.top/Article/details/gtqspjvsuh.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.vqdsnc.cn/Article/details/gtioalkpya.html

[S18] C：命令行参数
来源：http://dali.jinqigufen.top/Article/details/gtxbenfzji.html

int main(int argc, char **argv)
来源：http://dali.zhiwuduotai.top/Article/details/gtxxykwkkm.html

[S19] C：快速排序
来源：http://dali.gogol.net.cn/Article/details/gtghumrbpb.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gtfqgetfvr.html

[S20] C：二分查找
来源：http://dali.zhixingplan.top/Article/details/gtmltqmktb.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.cdnleiting.top/Article/details/gtgrccycef.html

[S21] C：字符类别判断
来源：http://dali.snrcjt.cn/Article/details/gtghcxoiif.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.hammf.cn/Article/details/gtlewvcait.html

[S22] C：字符串转数字
来源：http://dali.cqqwz.cn/Article/details/gtrciendxl.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.vqdsnc.cn/Article/details/gtwpwgpuyw.html

[S23] C：随机数
来源：http://dali.jinqigfzy.top/Article/details/gteavgnpev.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhiwuduotai.top/Article/details/gtqalrzmiw.html

[S24] C：获取本地时间
来源：http://dali.pycfn.com/Article/details/gtmxevelzf.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.xuanzx.com/Article/details/gtggtgbgbq.html

[S25] C：内存拷贝
来源：http://dali.ybcxt.top/Article/details/gtmnkavybq.html

memcpy(dst, src, n);
来源：http://dali.gzhubu.top/Article/details/gtbubnjekj.html

[S26] C：内存清零
来源：http://dali.haohaochexian.top/Article/details/gtwmgtqkay.html

memset(a, 0, sizeof a);
来源：http://dali.zhengqikj.top/Article/details/gtenltxdqo.html

[S27] C：定义常量
来源：http://dali.sufxvd.cn/Article/details/gttbxbkuyw.html

const double PI = 3.14159;
来源：http://dali.daxiang520.top/Article/details/gteoslobpa.html

[S28] C：静态变量
来源：http://dali.guowangkeji.top/Article/details/gtsxbdygef.html

static int counter = 0;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxyqqzybz.html

[S29] C：变参函数
来源：http://dali.zhongyouzk.top/Article/details/gtwkzekcyt.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.gaohongyu789.top/Article/details/gtaierewor.html

[S30] C：头文件保护
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuaxngtdu.html

#ifndef X_H
来源：http://dali.shzxlz.cn/Article/details/gtmxfgixwv.html

#define X_H
来源：http://dali.jinqigufen.top/Article/details/gtxughsssu.html

#endif
来源：http://dali.cucudq.cn/Article/details/gturdwbpaa.html

[S31] C++：Hello World
来源：http://dali.xziqi.cn/Article/details/gtznufdtmf.html

#include <iostream>
来源：http://dali.redwolf501.top/Article/details/gtlmebscpo.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.guannengcc.top/Article/details/gtnulojnxk.html

[S32] C++：字符串
来源：http://dali.hnxiangtu.top/Article/details/gtsyxtxywx.html

std::string s = "hi";  s += "!";
来源：http://dali.chenjidiqi.icu/Article/details/gtkqlaqqqz.html

[S33] C++：vector 增删
来源：http://dali.316326.xyz/Article/details/gtpxdkhywm.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.hnqzz.top/Article/details/gtelfkbrtx.html

[S34] C++：遍历 vector
来源：http://dali.aizwys.cn/Article/details/gtpecthpcl.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.hysaishi.cn/Article/details/gtnpvvtujx.html

[S35] C++：map
来源：http://dali.pengpengdd.cyou/Article/details/gtvtshcpdv.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.0kj1m.cn/Article/details/gtbfbgtotc.html

[S36] C++：unordered_map
来源：http://dali.chenzaomai.com/Article/details/gtxcfgvagr.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.shzxlz.cn/Article/details/gtuxufyeey.html

[S37] C++：set
来源：http://dali.yj20258888.top/Article/details/gtdsditfbb.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.kuanghao11.cn/Article/details/gtnovewnuf.html

[S38] C++：排序
来源：http://dali.pengpengdd.cyou/Article/details/gtsnleibfj.html

std::sort(v.begin(), v.end());
来源：http://dali.hysaishi.cn/Article/details/gtuwycqlbh.html

[S39] C++：自定义比较器排序
来源：http://dali.snrcjt.cn/Article/details/gtcqlfrhlh.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.shuidangran.top/Article/details/gtwodcsgwi.html

[S40] C++：查找元素
来源：http://dali.shzxlz.cn/Article/details/gtniugcgno.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.iojbl.cn/Article/details/gtqbjfrobg.html

[S41] C++：类与构造函数
来源：http://dali.yuanzhike.top/Article/details/gtpbclinng.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.hfpthk.cn/Article/details/gtociisieb.html

[S42] C++：继承与虚函数
来源：http://dali.hongshengwenyu.top/Article/details/gtnajdcvhj.html

class B : public Base { public: void f() override {} };
来源：http://dali.ehwqpu.com/Article/details/gtehnyjero.html

[S43] C++：智能指针
来源：http://dali.zhongyouzk.top/Article/details/gtzlpxmmdo.html

auto p = std::make_unique<int>(5);
来源：http://dali.bjfxy.top/Article/details/gtoinoaojr.html

[S44] C++：引用传参
来源：http://dali.ivvv.top/Article/details/gtrybjqule.html

void inc(int &x) { ++x; }
来源：http://dali.svipenyu.cn/Article/details/gtiptcvmct.html

[S45] C++：lambda
来源：http://dali.aizwys.cn/Article/details/gtkybssojj.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.yuxming.cn/Article/details/gtlgblaojr.html

[S46] C++：函数模板
来源：http://dali.redwolf501.top/Article/details/gtdyzogjqq.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.haohaochexian.top/Article/details/gtbwkjjivi.html

[S47] C++：结构化绑定遍历
来源：http://dali.gzhubu.top/Article/details/gtpyzgysyb.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.wangshuangyany.cn/Article/details/gtdxwblunf.html

[S48] C++：逐行读文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgmfiekaq.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhoulong.xyz/Article/details/gtkedfkqkp.html

while (std::getline(in, line)) { }
来源：http://dali.zycfv.cn/Article/details/gtapnbvvmz.html

[S49] C++：写文件
来源：http://dali.hnqzz.top/Article/details/gtmrzzbeck.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.birdmap.top/Article/details/gtgaerybzw.html

[S50] C++：格式化数字
来源：http://dali.aizwys.cn/Article/details/gtzeaxyvfd.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.yuxming.cn/Article/details/gtpbjumius.html

[S51] C++：显式类型转换
来源：http://dali.cucudq.cn/Article/details/gtrolxonxh.html

static_cast<double>(a) / b
来源：http://dali.cashguo.top/Article/details/gteydhidjf.html

[S52] C++：const 与 noexcept
来源：http://dali.yj20258.top/Article/details/gtzcexhflt.html

int size() const noexcept { return n_; }
来源：http://dali.yj202588.top/Article/details/gtfvninvub.html

[S53] C++：移动语义
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrzsgkpxk.html

std::vector<int> w = std::move(v);
来源：http://dali.yanxiufei.cn/Article/details/gthalxijdw.html

[S54] C++：异常处理
来源：http://dali.jlsjyb.cn/Article/details/gtvukhixzl.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.316326.xyz/Article/details/gtdnbcgluz.html

[S55] C++：结构化绑定
来源：http://dali.zhiwuduotai.top/Article/details/gtzmtgbpxf.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.jiagoushi.top/Article/details/gtzzhmobhn.html

[S56] C++：optional
来源：http://dali.xuetiantiany.cn/Article/details/gtaqmkstow.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.aibaodan.cn/Article/details/gtwkdxwtwn.html

[S57] C++：编译期常量
来源：http://dali.zycfv.cn/Article/details/gtfaqwidvj.html

constexpr int N = 10;
来源：http://dali.cheryme.top/Article/details/gtiiuuzlhx.html

[S58] C++：命名空间
来源：http://dali.cucudq.cn/Article/details/gtbzkfspav.html

namespace ns { int f() { return 1; } }
来源：http://dali.xuanzx.com/Article/details/gtfusuyysv.html

[S59] C++：静态断言
来源：http://dali.snrcjt.cn/Article/details/gtwbmxizsj.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.ybcxt.top/Article/details/gtvzrjfbnv.html

[S60] C++：遍历并删除元素
来源：http://dali.quarkkingdee.top/Article/details/gtvxxsjqwy.html


<!-- 参考信息 -->