代发 wailian999

R. Bash 专题
来源：http://dali.ppjwa.cn/Article/details/gtkfsillue.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtyxlhagjv.html

[R01] shebang 与严格模式
来源：http://dali.yuxming.cn/Article/details/gtkschvmmr.html

#!/usr/bin/env bash
来源：http://dali.tianlin.xyz/Article/details/gthkmelsvv.html

set -euo pipefail
来源：http://dali.jinqigufen.top/Article/details/gtbfvtpaaw.html

[R02] 变量赋值与使用
来源：http://dali.tianlin.xyz/Article/details/gtajtrxplw.html

name="Tom"; echo "$name"
来源：http://dali.hfpthk.cn/Article/details/gtfscskxuy.html

[R03] 只读变量
来源：http://dali.sysykeji.top/Article/details/gtdxwufwsc.html

readonly PI=3.14
来源：http://dali.snrcjt.cn/Article/details/gtuzivoseq.html

[R04] 位置参数
来源：http://dali.cdnleiting.top/Article/details/gtuognefcm.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.redwolf501.top/Article/details/gtqmpxmxls.html

[R05] 参数默认值
来源：http://dali.smart0.xyz/Article/details/gtgaxqljwp.html

name="${1:-default}"
来源：http://dali.316326.xyz/Article/details/gtlhdhyaqq.html

[R06] 判断命令是否存在
来源：http://dali.jyoumei.cn/Article/details/gtfimnatww.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.nanxuanxn.top/Article/details/gtyvtkulbf.html

[R07] if 判断文件
来源：http://dali.kuanghao11.cn/Article/details/gtrgorlttj.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.cucudq.cn/Article/details/gtjrkefdnu.html

[R08] 数值比较
来源：http://dali.sysykeji.top/Article/details/gtlqcxbkpk.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.quarkkingdee.top/Article/details/gttdqhputq.html

[R09] 字符串比较
来源：http://dali.zhongyouzk.top/Article/details/gthbfiqzwy.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.gaohongyu789.top/Article/details/gttzlazquu.html

[R10] 正则匹配
来源：http://dali.tanke756.top/Article/details/gttufcfsct.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.snrcjt.cn/Article/details/gtmbhvngrw.html

[R11] case 多分支
来源：http://dali.yuxming.cn/Article/details/gtymvifeil.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gtjbmgfeow.html

start) echo "启动" ;;
来源：http://dali.shzxlz.cn/Article/details/gttoqhcpji.html

stop)  echo "停止" ;;
来源：http://dali.yonumen.top/Article/details/gtksntnshq.html

*)     echo "未知命令" ;;
来源：http://dali.cdnleiting.top/Article/details/gtbhtgrcfz.html

esac
来源：http://dali.andypj.xyz/Article/details/gtwcbxehas.html

[R12] for 遍历文件
来源：http://dali.tanke756.top/Article/details/gtzmfpdhet.html

for f in *.txt; do echo "$f"; done
来源：http://dali.mhx1999.top/Article/details/gtvvnrecfy.html

[R13] for 计数循环
来源：http://dali.yonumen.top/Article/details/gtpcbpptbc.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdfzocclr.html

[R14] C 风格 for
来源：http://dali.wangshuangyany.cn/Article/details/gtmqbbovpy.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.dianchejie.cn/Article/details/gtttflqenv.html

[R15] while 逐行读文件
来源：http://dali.xuetiantiany.cn/Article/details/gtummusezd.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.aizwys.cn/Article/details/gthwysulzy.html

[R16] until 等待条件
来源：http://dali.birdmap.top/Article/details/gtrhmvevrw.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.andypj.xyz/Article/details/gtxnvxxfhv.html

[R17] 数组定义与取值
来源：http://dali.hfpthk.cn/Article/details/gttojftxkn.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.quarkkingdee.top/Article/details/gtatreolmr.html

[R18] 遍历数组
来源：http://dali.0kj1m.cn/Article/details/gtlqhkwcra.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.aizwys.cn/Article/details/gtzgenzmvy.html

[R19] 数组长度
来源：http://dali.zhixingplan.top/Article/details/gtoarvojdv.html

echo "${#arr[@]}"
来源：http://dali.havefunace.top/Article/details/gtzlqwsahd.html

[R20] 关联数组（字典）
来源：http://dali.ppjwa.cn/Article/details/gtdtjcidtd.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.smart0.xyz/Article/details/gtfzifyqet.html

[R21] 字符串长度
来源：http://dali.mhx1999.top/Article/details/gtjjjfnnrf.html

echo "${#s}"
来源：http://dali.sysykeji.top/Article/details/gtclygxejh.html

[R22] 截取子串
来源：http://dali.zhoulong.xyz/Article/details/gtqbptjfcp.html

echo "${s:0:5}"
来源：http://dali.hysaishi.cn/Article/details/gtdbxgvvgz.html

[R23] 字符串替换
来源：http://dali.hfpthk.cn/Article/details/gtezxgrvop.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.jqgfzy.top/Article/details/gtuweakrpy.html

[R24] 大小写转换
来源：http://dali.zhiwuduotai.top/Article/details/gtllbvunah.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.gzhubu.top/Article/details/gtyxgtoyxt.html

[R25] 去后缀 / 去前缀
来源：http://dali.hfpthk.cn/Article/details/gtrcffcrsz.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.sxryk.cn/Article/details/gtpuagigtf.html

[R26] 命令替换
来源：http://dali.hnxiangtu.top/Article/details/gtesaloxhp.html

now=$(date +%F); echo "$now"
来源：http://dali.dianchejie.cn/Article/details/gtaleuoisu.html

[R27] 算术展开
来源：http://dali.shanyushiyangtech.top/Article/details/gttwyhqdqk.html

echo $((1 + 2 * 3))
来源：http://dali.yonumen.top/Article/details/gtydjiznyn.html

[R28] 浮点运算
来源：http://dali.aibaodan.cn/Article/details/gtsybwsbxy.html

echo "scale=2; 10/3" | bc
来源：http://dali.redwolf501.top/Article/details/gtfpbdjxtc.html

[R29] 定义函数
来源：http://dali.zhongyouzk.top/Article/details/gtaiikyoga.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.nanxinkj.top/Article/details/gttyniapxi.html

[R30] 函数返回状态码
来源：http://dali.ybcxt.top/Article/details/gtdhqxummu.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.jinqigufen.top/Article/details/gturjdckrj.html

[R31] 局部变量
来源：http://dali.cheryme.top/Article/details/gtzlypztap.html

f() { local x=1; echo "$x"; }
来源：http://dali.yj202588.top/Article/details/gtezbslwyh.html

[R32] 参数个数校验
来源：http://dali.yongpay.top/Article/details/gtkrunzebi.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.cashguo.top/Article/details/gttcigitet.html

[R33] 捕获错误并提示行号
来源：http://dali.yangfankeji.com/Article/details/gthuitozbk.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.cdnleiting.top/Article/details/gtkvminffs.html

[R34] 退出时清理
来源：http://dali.yongpay.top/Article/details/gtgydokwwj.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.yj20258888.top/Article/details/gtreuojdxr.html

[R35] 后台执行并等待
来源：http://dali.mhx1999.top/Article/details/gtvowfzysd.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhaomingkeji.xyz/Article/details/gthipbjmku.html

[R36] 并发执行多个任务
来源：http://dali.xuetiantiany.cn/Article/details/gtkozehbna.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.cashguo.top/Article/details/gtirlrbjjs.html

[R37] 把输出赋给变量
来源：http://dali.feifeiyinyue.top/Article/details/gthtkmexzw.html

files=$(ls -1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtyzjdngbv.html

[R38] 管道串联
来源：http://dali.andypj.xyz/Article/details/gtprgwcwds.html

cat a.txt | grep -i error | wc -l
来源：http://dali.cheryme.top/Article/details/gtkvmoieuu.html

[R39] 重定向标准输出与错误
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdmavtsgn.html

cmd > out.log 2>&1
来源：http://dali.yongpay.top/Article/details/gtlitemzsq.html

[R40] 追加写日志
来源：http://dali.yangfankeji.com/Article/details/gtcwuhwuuk.html

echo "log" >> out.log
来源：http://dali.andypj.xyz/Article/details/gtrvaodcau.html

[R41] 丢弃输出
来源：http://dali.yanxiufei.cn/Article/details/gtkfvljigf.html

cmd >/dev/null 2>&1
来源：http://dali.chenjidiqi.icu/Article/details/gtjyoicszd.html

[R42] 输入重定向
来源：http://dali.0kj1m.cn/Article/details/gttvjlvzjj.html

wc -l < a.txt
来源：http://dali.xuanzx.com/Article/details/gtazbagmer.html

[R43] 按名字查找文件
来源：http://dali.daria6918.cn/Article/details/gtgjbiqvax.html

find . -name "*.log" -type f
来源：http://dali.chenlongwang.top/Article/details/gtbyruthky.html

[R44] 按修改时间查找
来源：http://dali.jiagoushi.top/Article/details/gtqlehwyyz.html

find . -mtime -7 -type f
来源：http://dali.andypj.xyz/Article/details/gtasyhlziy.html

[R45] 批量删除
来源：http://dali.zycfv.cn/Article/details/gtdtdwqzcw.html

find . -name "*.tmp" -delete
来源：http://dali.wangdashe.top/Article/details/gtyniuuswo.html

[R46] 递归替换文件内容
来源：http://dali.cqqwz.cn/Article/details/gtebcvbcbo.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.sxryk.cn/Article/details/gtzdewimcc.html

[R47] sed 单行替换
来源：http://dali.cashguo.top/Article/details/gthzwguysa.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhoulong.xyz/Article/details/gtdufbrmat.html

[R48] awk 取指定列
来源：http://dali.feifeiyinyue.top/Article/details/gtyzdhevrp.html

awk '{print $1, $3}' a.txt
来源：http://dali.yongpay.top/Article/details/gtovpkroir.html

[R49] awk 带条件
来源：http://dali.ybcxt.top/Article/details/gtijfxvknh.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrtugtumi.html

[R50] awk 求和
来源：http://dali.yuxming.cn/Article/details/gtsvtzuymv.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.yj20258.top/Article/details/gtlpkqgtuy.html

[R51] 排序去重取前几
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfjoqpdbv.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.hnqzz.top/Article/details/gtswzqyryu.html

[R52] 统计行数
来源：http://dali.dianchejie.cn/Article/details/gtkinigzei.html

wc -l a.txt
来源：http://dali.tianlin.xyz/Article/details/gtpluyyayg.html

[R53] 查看文件头与实时尾
来源：http://dali.chenzaomai.com/Article/details/gtxehfwsbs.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.yongpay.top/Article/details/gtgvssnrzd.html

[R54] 比较两个文件
来源：http://dali.sysykeji.top/Article/details/gtbhbuivdq.html

diff a.txt b.txt
来源：http://dali.fengsongda.top/Article/details/gtagigfwtw.html

[R55] 压缩与解压
来源：http://dali.sxryk.cn/Article/details/gtywgkjkqw.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.fzhhl.top/Article/details/gtdjwbotex.html

[R56] 远程拷贝
来源：http://dali.yj202588.top/Article/details/gtussmoosd.html

scp file user@host:/path/
来源：http://dali.pengpengdd.cyou/Article/details/gthxttowpr.html

[R57] 远程执行命令
来源：http://dali.jinqigfzy.top/Article/details/gtyscgcldo.html

ssh user@host 'uptime'
来源：http://dali.andypj.xyz/Article/details/gtrtttgrcr.html

[R58] 下载文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtisubizys.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.guowangkeji.top/Article/details/gtvxvdvrxo.html

[R59] 发 POST JSON
来源：http://dali.pycfn.com/Article/details/gtgfheltst.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.guowangkeji.top/Article/details/gtzyowvptm.html

[R60] 只看 HTTP 状态码
来源：http://dali.nanxuanxn.top/Article/details/gtwbcdpdrz.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.cdnleiting.top/Article/details/gtxeyetfxz.html

[R61] 磁盘占用
来源：http://dali.yuxming.cn/Article/details/gtkytlubdp.html

df -h;  du -sh *
来源：http://dali.andypj.xyz/Article/details/gtpdlsuaao.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gtqiuement.html

du -ah . | sort -rh | head -10
来源：http://dali.wangdashe.top/Article/details/gtoybibyvn.html

[R63] 内存与进程
来源：http://dali.yj202588.top/Article/details/gtrfkqqkmk.html

free -h;  ps aux | grep nginx
来源：http://dali.bjfxy.top/Article/details/gtbxcghxjl.html

[R64] 结束进程
来源：http://dali.sweek.top/Article/details/gtkapvzuol.html

kill -9 $(pgrep -f app.py)
来源：http://dali.gotoacloud.top/Article/details/gtwrlkxxlk.html

[R65] 查看端口占用
来源：http://dali.ybcxt.top/Article/details/gtkcaqaepk.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.aizwys.cn/Article/details/gttdredqgn.html

[R66] 定时任务
来源：http://dali.hysaishi.cn/Article/details/gtxuaycxsp.html

crontab -e;  crontab -l
来源：http://dali.chenjidiqi.icu/Article/details/gtajpwnmgd.html

[R67] 生成随机十六进制串
来源：http://dali.aibaodan.cn/Article/details/gtyvorzpyw.html

openssl rand -hex 16
来源：http://dali.yangfankeji.com/Article/details/gtnuxborcp.html

[R68] 计算文件校验值
来源：http://dali.yueranfly.top/Article/details/gtvgipvwqu.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.gogol.net.cn/Article/details/gtjupdmhuo.html

[R69] 生成随机密码
来源：http://dali.gogol.net.cn/Article/details/gtngrjndxt.html

head -c 16 /dev/urandom | base64
来源：http://dali.feifeiyinyue.top/Article/details/gtthaajjfs.html

[R70] 时间戳与互转
来源：http://dali.cdnleiting.top/Article/details/gtonnabmqe.html

date +%s;  date -d @1700000000
来源：http://dali.shangyingyoupin.top/Article/details/gtsrnucirg.html

[R71] 日期格式化
来源：http://dali.cucudq.cn/Article/details/gtkbaqluts.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.c1oappe.top/Article/details/gtivzieygc.html

[R72] 等待端口就绪
来源：http://dali.wangdashe.top/Article/details/gtjnzbwaiq.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.fengsongda.top/Article/details/gtwwopmpcc.html

[R73] 分割大日志
来源：http://dali.kuanghao11.cn/Article/details/gtvhiiyyxa.html

split -l 1000 big.log part_
来源：http://dali.jianghu66.top/Article/details/gtpdwucjrw.html

[R74] 批量重命名
来源：http://dali.chenzaomai.com/Article/details/gtedupabsk.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.yonumen.top/Article/details/gtuvhjwbtp.html

[R75] 导出环境变量
来源：http://dali.mhx1999.top/Article/details/gtravmwnbw.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.guannengcc.top/Article/details/gtvpnqhvkz.html

[R76] 使用临时文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxnpuritk.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.gzhubu.top/Article/details/gtneoqbica.html

[R77] 读取用户输入
来源：http://dali.jinqigfzy.top/Article/details/gttfaozbxr.html

read -rp "请输入: " ans
来源：http://dali.shzxlz.cn/Article/details/gtfnldumpp.html

[R78] 交互式菜单
来源：http://dali.gogol.net.cn/Article/details/gtjxdkllqz.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.andypj.xyz/Article/details/gtfwvviqxe.html

[R79] 解析命令行选项
来源：http://dali.jqgfzy.top/Article/details/gtecnqnlfu.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.iojbl.cn/Article/details/gtrqjvogly.html

[R80] 查看脚本执行耗时
来源：http://dali.jinghuilouyu.cn/Article/details/gtinbggrxz.html

time ./run.sh
来源：http://dali.dashuyun.cn/Article/details/gtizwmilwa.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtsiltlstb.html

S. C / C++ 专题
来源：http://dali.dianchejie.cn/Article/details/gtzpwupruc.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtgsuvlpts.html

[S01] C：Hello World
来源：http://dali.redwolf501.top/Article/details/gtjbxkvamd.html

#include <stdio.h>
来源：http://dali.redwolf501.top/Article/details/gtvvywojyp.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhiwuduotai.top/Article/details/gtvdbgamuf.html

[S02] C：变量与格式化输出
来源：http://dali.pengpengdd.cyou/Article/details/gtwfdfsydq.html

int a = 10; printf("%d\n", a);
来源：http://dali.chenlongwang.top/Article/details/gtzgffucwt.html

[S03] C：读入整数
来源：http://dali.jianghu66.top/Article/details/gtvgjqintf.html

int x; scanf("%d", &x);
来源：http://dali.zhongyouzk.top/Article/details/gtrnilriwh.html

[S04] C：字符串复制
来源：http://dali.haohaochexian.top/Article/details/gtozqymwjn.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.gogol.net.cn/Article/details/gtrmrdywlx.html

[S05] C：字符串长度
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlijweunc.html

strlen(s)
来源：http://dali.hfpthk.cn/Article/details/gtitlgmrrc.html

[S06] C：字符串比较
来源：http://dali.daria6918.cn/Article/details/gtsdxorlqb.html

strcmp(a, b) == 0
来源：http://dali.yj202588.top/Article/details/gthupqzdlh.html

[S07] C：数组遍历求和
来源：http://dali.wangdashe.top/Article/details/gtmfwpxicm.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.wangdashe.top/Article/details/gtmrzkdeim.html

[S08] C：动态内存分配与释放
来源：http://dali.xinyue.icu/Article/details/gtoaiuvtll.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zycfv.cn/Article/details/gtgghuossm.html

[S09] C：结构体定义与初始化
来源：http://dali.pycfn.com/Article/details/gtowyrjaqs.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyominnbn.html

[S10] C：指针与解引用
来源：http://dali.tanke756.top/Article/details/gtxxagghoo.html

int *p = &a;  *p = 5;
来源：http://dali.sysykeji.top/Article/details/gtwkufccxo.html

[S11] C：逐行读文件
来源：http://dali.zhiwuduotai.top/Article/details/gtjemlabic.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.cashguo.top/Article/details/gtqufiomzv.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gtwetnonze.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gtmhjumtqe.html

[S12] C：写文件
来源：http://dali.meibo888.top/Article/details/gtyelvmqqs.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.yj202588.top/Article/details/gtqdtofoea.html

[S13] C：宏定义
来源：http://dali.mhx1999.top/Article/details/gtygvwowcp.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.hongshengwenyu.top/Article/details/gtkmkxudok.html

[S14] C：枚举
来源：http://dali.sufxvd.cn/Article/details/gtonirutnb.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.wangshuangyany.cn/Article/details/gtrvakftnc.html

[S15] C：类型转换
来源：http://dali.tianlin.xyz/Article/details/gtmohxpzal.html

(double) a / b
来源：http://dali.ydzc1.top/Article/details/gtatwzqbhz.html

[S16] C：位操作置位
来源：http://dali.pengpengdd.cyou/Article/details/gtrbufqawu.html

x |= (1 << 3);
来源：http://dali.tianlin.xyz/Article/details/gtrdieyzsw.html

[S17] C：安全拼接字符串
来源：http://dali.cashguo.top/Article/details/gtjesowjrf.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.quarkkingdee.top/Article/details/gtouoejxjl.html

[S18] C：命令行参数
来源：http://dali.birdmap.top/Article/details/gtppnvmpmb.html

int main(int argc, char **argv)
来源：http://dali.shangyingyoupin.top/Article/details/gtsrfbeeam.html

[S19] C：快速排序
来源：http://dali.zycfv.cn/Article/details/gtshcpjcmh.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.iojbl.cn/Article/details/gtgwraetcf.html

[S20] C：二分查找
来源：http://dali.yuxming.cn/Article/details/gtchykgisa.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzsljpost.html

[S21] C：字符类别判断
来源：http://dali.andypj.xyz/Article/details/gtyyelrsla.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.smart0.xyz/Article/details/gtxwefcbkt.html

[S22] C：字符串转数字
来源：http://dali.ybcxt.top/Article/details/gtnmdpeghb.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.meibo888.top/Article/details/gtvxclbira.html

[S23] C：随机数
来源：http://dali.jinqigufen.top/Article/details/gtmhhrbypu.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.ppjwa.cn/Article/details/gtoyqccmcs.html

[S24] C：获取本地时间
来源：http://dali.nanxuanxn.top/Article/details/gtxgtekima.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.hongshengwenyu.top/Article/details/gtqmvufusf.html

[S25] C：内存拷贝
来源：http://dali.cdnleiting.top/Article/details/gtpvgkrvbn.html

memcpy(dst, src, n);
来源：http://dali.jiagoushi.top/Article/details/gtblirrqae.html

[S26] C：内存清零
来源：http://dali.gogol.net.cn/Article/details/gtdonutkka.html

memset(a, 0, sizeof a);
来源：http://dali.ppjwa.cn/Article/details/gtltmnntvx.html

[S27] C：定义常量
来源：http://dali.jiagoushi.top/Article/details/gtrjcmgwbc.html

const double PI = 3.14159;
来源：http://dali.hnqzz.top/Article/details/gtbisvgtlt.html

[S28] C：静态变量
来源：http://dali.zhixingplan.top/Article/details/gtjckbxsks.html

static int counter = 0;
来源：http://dali.quarkkingdee.top/Article/details/gtwlanwxuq.html

[S29] C：变参函数
来源：http://dali.tian-w.cn/Article/details/gtyzzvpmeq.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.birdmap.top/Article/details/gtegrwihlj.html

[S30] C：头文件保护
来源：http://dali.tianlin.xyz/Article/details/gtpwoawrgt.html

#ifndef X_H
来源：http://dali.zhongyouzk.top/Article/details/gtofantmac.html

#define X_H
来源：http://dali.hnqzz.top/Article/details/gtcaxdejee.html

#endif
来源：http://dali.ybcxt.top/Article/details/gtvnkyycow.html

[S31] C++：Hello World
来源：http://dali.cheryme.top/Article/details/gtuumsxtfa.html

#include <iostream>
来源：http://dali.yueranfly.top/Article/details/gtcgeukjjg.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtbpbwwngi.html

[S32] C++：字符串
来源：http://dali.kuanghao11.cn/Article/details/gtzuxeoywo.html

std::string s = "hi";  s += "!";
来源：http://dali.jyoumei.cn/Article/details/gtzgasadfq.html

[S33] C++：vector 增删
来源：http://dali.gzhubu.top/Article/details/gttouztgjb.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.yonumen.top/Article/details/gtxrlwkzsx.html

[S34] C++：遍历 vector
来源：http://dali.ppjwa.cn/Article/details/gtlbflkgfz.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.wangshuangyany.cn/Article/details/gtbzmdviwt.html

[S35] C++：map
来源：http://dali.feifeiyinyue.top/Article/details/gtmelooker.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yuanzhike.top/Article/details/gtvrqaqisb.html

[S36] C++：unordered_map
来源：http://dali.sweek.top/Article/details/gtxxmmtrck.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.fzhhl.top/Article/details/gtijtkeddm.html

[S37] C++：set
来源：http://dali.yuxming.cn/Article/details/gtksdhejcd.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.andypj.xyz/Article/details/gtwzveqggf.html

[S38] C++：排序
来源：http://dali.yj202588.top/Article/details/gtlmhtmfxp.html

std::sort(v.begin(), v.end());
来源：http://dali.zhoulong.xyz/Article/details/gtnoqudtcg.html

[S39] C++：自定义比较器排序
来源：http://dali.smart0.xyz/Article/details/gttjyiselb.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.cucudq.cn/Article/details/gtmcirpoll.html

[S40] C++：查找元素
来源：http://dali.havefunace.top/Article/details/gtfbvoozaq.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.daria6918.cn/Article/details/gtioekbhan.html

[S41] C++：类与构造函数
来源：http://dali.shangyingyoupin.top/Article/details/gtiahtlrnn.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.gzhubu.top/Article/details/gtlegygtmv.html

[S42] C++：继承与虚函数
来源：http://dali.0kj1m.cn/Article/details/gtahcapxhz.html

class B : public Base { public: void f() override {} };
来源：http://dali.yuanzhike.top/Article/details/gtngcyrwme.html

[S43] C++：智能指针
来源：http://dali.zhixingplan.top/Article/details/gtqkeogbhk.html

auto p = std::make_unique<int>(5);
来源：http://dali.hnxiangtu.top/Article/details/gtwgksqlpl.html

[S44] C++：引用传参
来源：http://dali.shuidangran.top/Article/details/gtqmgxhxpp.html

void inc(int &x) { ++x; }
来源：http://dali.cashguo.top/Article/details/gtukgfzkmj.html

[S45] C++：lambda
来源：http://dali.yongpay.top/Article/details/gthjklowns.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.tianlin.xyz/Article/details/gtytbcbqew.html

[S46] C++：函数模板
来源：http://dali.sysykeji.top/Article/details/gtptvqwvhr.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.yanxiufei.cn/Article/details/gtxkfmhvzv.html

[S47] C++：结构化绑定遍历
来源：http://dali.sweek.top/Article/details/gttbkhjbsc.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.fzhhl.top/Article/details/gtgpkiezch.html

[S48] C++：逐行读文件
来源：http://dali.jlsjyb.cn/Article/details/gtjcqqrcei.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.9152youxi.cn/Article/details/gtlifnbegq.html

while (std::getline(in, line)) { }
来源：http://dali.ydzc1.top/Article/details/gtcjdxksta.html

[S49] C++：写文件
来源：http://dali.feifeiyinyue.top/Article/details/gtrnvpgngz.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.yj20258888.top/Article/details/gtczisvrvt.html

[S50] C++：格式化数字
来源：http://dali.jqgufenzy.top/Article/details/gtvmtyztpv.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.sweek.top/Article/details/gttnrrhrsa.html

[S51] C++：显式类型转换
来源：http://dali.hnqzz.top/Article/details/gtdpkrhttj.html

static_cast<double>(a) / b
来源：http://dali.jinqigufen.top/Article/details/gtrfmdeiix.html

[S52] C++：const 与 noexcept
来源：http://dali.c1oappe.top/Article/details/gtsbzupydz.html

int size() const noexcept { return n_; }
来源：http://dali.shangyingyoupin.top/Article/details/gtukuhhxbv.html

[S53] C++：移动语义
来源：http://dali.chenzaomai.com/Article/details/gtletcbsid.html

std::vector<int> w = std::move(v);
来源：http://dali.c1oappe.top/Article/details/gtysmazrwh.html

[S54] C++：异常处理
来源：http://dali.aibaodan.cn/Article/details/gtamahmoml.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zdqjudy.top/Article/details/gtyciimdvi.html

[S55] C++：结构化绑定
来源：http://dali.xinyue.icu/Article/details/gtwvaqddys.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.chenlongwang.top/Article/details/gtzvzrtgkp.html

[S56] C++：optional
来源：http://dali.chenzaomai.com/Article/details/gtcnnylchk.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.tian-w.cn/Article/details/gtuuvaxdmz.html

[S57] C++：编译期常量
来源：http://dali.xinyue.icu/Article/details/gtyipxztel.html

constexpr int N = 10;
来源：http://dali.quarkkingdee.top/Article/details/gtyxrrvxin.html

[S58] C++：命名空间
来源：http://dali.birdmap.top/Article/details/gtppngjodn.html

namespace ns { int f() { return 1; } }
来源：http://dali.snrcjt.cn/Article/details/gtuffhgsgu.html

[S59] C++：静态断言
来源：http://dali.yanxiufei.cn/Article/details/gtgdrdgqwj.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.316326.xyz/Article/details/gtjgsfjdtn.html

[S60] C++：遍历并删除元素
来源：http://dali.tanke756.top/Article/details/gtdriubzgx.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.xylfe.cn/Article/details/gtvdaovjvv.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtrbmsvjdf.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.0kj1m.cn/Article/details/gtuhzyzqbn.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtzvtndkxy.html


<!-- 参考信息 -->