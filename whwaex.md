代发 wailian999

set -euo pipefail
来源：http://dali.snrcjt.cn/Article/details/gtlrcacrad.html

[R02] 变量赋值与使用
来源：http://dali.dianchejie.cn/Article/details/gtfpccdsbd.html

name="Tom"; echo "$name"
来源：http://dali.xylfe.cn/Article/details/gtqnlevrks.html

[R03] 只读变量
来源：http://dali.gogol.net.cn/Article/details/gtujfqbyan.html

readonly PI=3.14
来源：http://dali.sxryk.cn/Article/details/gtarogadme.html

[R04] 位置参数
来源：http://dali.shangyingyoupin.top/Article/details/gtfszbjhcc.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.hywenlv.cn/Article/details/gtymdllaux.html

[R05] 参数默认值
来源：http://dali.chenlongwang.top/Article/details/gtqkjhpojg.html

name="${1:-default}"
来源：http://dali.gaohongyu789.top/Article/details/gtlkpeucbp.html

[R06] 判断命令是否存在
来源：http://dali.pycfn.com/Article/details/gtnapiwmjs.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.guannengcc.top/Article/details/gtvmcydcvj.html

[R07] if 判断文件
来源：http://dali.yj20258888.top/Article/details/gtyqihrxnc.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.xuanzx.com/Article/details/gtaunclobs.html

[R08] 数值比较
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsnapwjzj.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.hfpthk.cn/Article/details/gtnkppsclu.html

[R09] 字符串比较
来源：http://dali.aibaodan.cn/Article/details/gttsibqrox.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.ehwqpu.com/Article/details/gtpvvmrzyy.html

[R10] 正则匹配
来源：http://dali.ybcxt.top/Article/details/gtgcgdgoof.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.chenlongwang.top/Article/details/gtdoxkagcm.html

[R11] case 多分支
来源：http://dali.hywenlv.cn/Article/details/gtnmnzpyel.html

case "$1" in
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxyyzhitx.html

start) echo "启动" ;;
来源：http://dali.haohaochexian.top/Article/details/gtaewzzwtf.html

stop)  echo "停止" ;;
来源：http://dali.zycfv.cn/Article/details/gthmrhgpkr.html

*)     echo "未知命令" ;;
来源：http://dali.havefunace.top/Article/details/gtmmxbxryg.html

esac
来源：http://dali.316326.xyz/Article/details/gtohcuoxst.html

[R12] for 遍历文件
来源：http://dali.daxiang520.top/Article/details/gtdttobrpj.html

for f in *.txt; do echo "$f"; done
来源：http://dali.ehwqpu.com/Article/details/gtexlnjwst.html

[R13] for 计数循环
来源：http://dali.yj20258.top/Article/details/gtraesrfrq.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.chenjidiqi.icu/Article/details/gtutbyvrhr.html

[R14] C 风格 for
来源：http://dali.zycfv.cn/Article/details/gtrldezjcy.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.xinyue.icu/Article/details/gtqufbrjxq.html

[R15] while 逐行读文件
来源：http://dali.cqqwz.cn/Article/details/gtbqthlqib.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.daxiang520.top/Article/details/gtaoydnsak.html

[R16] until 等待条件
来源：http://dali.hnxiangtu.top/Article/details/gtxaimeehh.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.meibo888.top/Article/details/gtqsjpkorz.html

[R17] 数组定义与取值
来源：http://dali.0kj1m.cn/Article/details/gtdiufashi.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.yangfankeji.com/Article/details/gtepcwekwv.html

[R18] 遍历数组
来源：http://dali.zdqjudy.top/Article/details/gtugmifbnq.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.chenlongwang.top/Article/details/gtqtrjrolr.html

[R19] 数组长度
来源：http://dali.yj20258.top/Article/details/gtqnezcmih.html

echo "${#arr[@]}"
来源：http://dali.pycfn.com/Article/details/gtjuqsrtfh.html

[R20] 关联数组（字典）
来源：http://dali.chenlongwang.top/Article/details/gtldjytqyl.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.aibaodan.cn/Article/details/gtzldzwimm.html

[R21] 字符串长度
来源：http://dali.nanxuanxn.top/Article/details/gthrtaddah.html

echo "${#s}"
来源：http://dali.daxiang520.top/Article/details/gtpaiulsir.html

[R22] 截取子串
来源：http://dali.cashguo.top/Article/details/gtjhpzhfkt.html

echo "${s:0:5}"
来源：http://dali.cheryme.top/Article/details/gtauotvrjz.html

[R23] 字符串替换
来源：http://dali.cashguo.top/Article/details/gtrdwhxtzl.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpcrssojx.html

[R24] 大小写转换
来源：http://dali.shangyingyoupin.top/Article/details/gtogwhcaii.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.ydzc1.top/Article/details/gtlvblhjlj.html

[R25] 去后缀 / 去前缀
来源：http://dali.cucudq.cn/Article/details/gtkvojbvqn.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.nanxuanxn.top/Article/details/gtfxepnrha.html

[R26] 命令替换
来源：http://dali.nanxuanxn.top/Article/details/gtjhegctms.html

now=$(date +%F); echo "$now"
来源：http://dali.chenlongwang.top/Article/details/gtolhwqjdy.html

[R27] 算术展开
来源：http://dali.havefunace.top/Article/details/gthgfnjjxq.html

echo $((1 + 2 * 3))
来源：http://dali.tanke756.top/Article/details/gtsnqjcagl.html

[R28] 浮点运算
来源：http://dali.yj20258888.top/Article/details/gtoliqlhbb.html

echo "scale=2; 10/3" | bc
来源：http://dali.cucudq.cn/Article/details/gtmrxgjiyn.html

[R29] 定义函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqphitmmt.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.tian-w.cn/Article/details/gticuwnzrx.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gtsjopprjv.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.pycfn.com/Article/details/gtbrnsbqst.html

[R31] 局部变量
来源：http://dali.kuanghao11.cn/Article/details/gtfenvxaao.html

f() { local x=1; echo "$x"; }
来源：http://dali.xuetiantiany.cn/Article/details/gthcqaembx.html

[R32] 参数个数校验
来源：http://dali.aibaodan.cn/Article/details/gttkcdcojk.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.tanke756.top/Article/details/gtuhouezmu.html

[R33] 捕获错误并提示行号
来源：http://dali.0kj1m.cn/Article/details/gtznpeyxze.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.sxryk.cn/Article/details/gtlwanvmbw.html

[R34] 退出时清理
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwzggdyyl.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.xuanzx.com/Article/details/gtquxhqoun.html

[R35] 后台执行并等待
来源：http://dali.andypj.xyz/Article/details/gtqjgnepni.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtecpjdfpa.html

[R36] 并发执行多个任务
来源：http://dali.shuidangran.top/Article/details/gtglsjynry.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.tanke756.top/Article/details/gtjldhjjcd.html

[R37] 把输出赋给变量
来源：http://dali.316326.xyz/Article/details/gtplyhvtqu.html

files=$(ls -1)
来源：http://dali.svipenyu.cn/Article/details/gtkqoegwzi.html

[R38] 管道串联
来源：http://dali.mhx1999.top/Article/details/gtlyyfhrau.html

cat a.txt | grep -i error | wc -l
来源：http://dali.shuidangran.top/Article/details/gtlqqaoear.html

[R39] 重定向标准输出与错误
来源：http://dali.jqgufenzy.top/Article/details/gtymaietfr.html

cmd > out.log 2>&1
来源：http://dali.nwbrower.top/Article/details/gtafftogbl.html

[R40] 追加写日志
来源：http://dali.nwbrower.top/Article/details/gtydyvjnml.html

echo "log" >> out.log
来源：http://dali.hnxiangtu.top/Article/details/gtgpjcfccp.html

[R41] 丢弃输出
来源：http://dali.cashguo.top/Article/details/gtrdaeyqrc.html

cmd >/dev/null 2>&1
来源：http://dali.cqqwz.cn/Article/details/gtwewzvbnz.html

[R42] 输入重定向
来源：http://dali.hongshengwenyu.top/Article/details/gtqhhashlp.html

wc -l < a.txt
来源：http://dali.gogol.net.cn/Article/details/gtgevtassu.html

[R43] 按名字查找文件
来源：http://dali.vqdsnc.cn/Article/details/gteofxngsn.html

find . -name "*.log" -type f
来源：http://dali.xuetiantiany.cn/Article/details/gtwkcuzxkv.html

[R44] 按修改时间查找
来源：http://dali.zhengqikj.top/Article/details/gtgctlrfid.html

find . -mtime -7 -type f
来源：http://dali.iojbl.cn/Article/details/gtokyoufeh.html

[R45] 批量删除
来源：http://dali.fengsongda.top/Article/details/gtvtqwnfru.html

find . -name "*.tmp" -delete
来源：http://dali.yvedp.cn/Article/details/gtxovciwcv.html

[R46] 递归替换文件内容
来源：http://dali.bjfxy.top/Article/details/gtxyazhxpw.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.yonumen.top/Article/details/gtydosccqy.html

[R47] sed 单行替换
来源：http://dali.sweek.top/Article/details/gtzzknnplh.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.cashguo.top/Article/details/gtyostitpi.html

[R48] awk 取指定列
来源：http://dali.dianchejie.cn/Article/details/gtldsypxvk.html

awk '{print $1, $3}' a.txt
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthhldioqz.html

[R49] awk 带条件
来源：http://dali.guowangkeji.top/Article/details/gtzqwchajz.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.aibaodan.cn/Article/details/gtkegjdhkv.html

[R50] awk 求和
来源：http://dali.daxiang520.top/Article/details/gthkyuyutr.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.ppjwa.cn/Article/details/gtgakakdmr.html

[R51] 排序去重取前几
来源：http://dali.shangyingyoupin.top/Article/details/gtwrfvifcd.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.ppjwa.cn/Article/details/gtawuvvuvv.html

[R52] 统计行数
来源：http://dali.yangfankeji.com/Article/details/gtokfnkczl.html

wc -l a.txt
来源：http://dali.shzxlz.cn/Article/details/gtqcqtkqha.html

[R53] 查看文件头与实时尾
来源：http://dali.xinyue.icu/Article/details/gturfvhkrn.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzovhuhhq.html

[R54] 比较两个文件
来源：http://dali.xinyue.icu/Article/details/gtodvvyjig.html

diff a.txt b.txt
来源：http://dali.sysykeji.top/Article/details/gtefldimju.html

[R55] 压缩与解压
来源：http://dali.xuetiantiany.cn/Article/details/gtwqauedbx.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.hongshengwenyu.top/Article/details/gtoffujunk.html

[R56] 远程拷贝
来源：http://dali.guowangkeji.top/Article/details/gtwpluvysu.html

scp file user@host:/path/
来源：http://dali.wangdashe.top/Article/details/gtckkxoobd.html

[R57] 远程执行命令
来源：http://dali.0kj1m.cn/Article/details/gtyiltuqqy.html

ssh user@host 'uptime'
来源：http://dali.nanxinkj.top/Article/details/gtpmipyyyl.html

[R58] 下载文件
来源：http://dali.sweek.top/Article/details/gtyebsmzun.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnsreecxe.html

[R59] 发 POST JSON
来源：http://dali.sysykeji.top/Article/details/gtqyvbtevj.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.xuetiantiany.cn/Article/details/gtqqnvaijm.html

[R60] 只看 HTTP 状态码
来源：http://dali.chenlongwang.top/Article/details/gtihovtqcc.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.pengpengdd.cyou/Article/details/gtegpguzch.html

[R61] 磁盘占用
来源：http://dali.cheryme.top/Article/details/gtpxamcoav.html

df -h;  du -sh *
来源：http://dali.smart0.xyz/Article/details/gtczlwxevy.html

[R62] 找最占空间的文件
来源：http://dali.tian-w.cn/Article/details/gtoujajxbj.html

du -ah . | sort -rh | head -10
来源：http://dali.yj20258.top/Article/details/gtiyarnlrg.html

[R63] 内存与进程
来源：http://dali.tian-w.cn/Article/details/gtldbzarkq.html

free -h;  ps aux | grep nginx
来源：http://dali.wangshuangyany.cn/Article/details/gtzkxgapph.html

[R64] 结束进程
来源：http://dali.jqgufenzy.top/Article/details/gtqmdhwvoh.html

kill -9 $(pgrep -f app.py)
来源：http://dali.yongpay.top/Article/details/gtvyuiosgv.html

[R65] 查看端口占用
来源：http://dali.jinqigufen.top/Article/details/gtdvpfcmod.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhongyouzk.top/Article/details/gttbtkvatq.html

[R66] 定时任务
来源：http://dali.smart0.xyz/Article/details/gtngfiixeu.html

crontab -e;  crontab -l
来源：http://dali.gzhubu.top/Article/details/gtinilfjud.html

[R67] 生成随机十六进制串
来源：http://dali.kuanghao11.cn/Article/details/gtaunfllya.html

openssl rand -hex 16
来源：http://dali.shuidangran.top/Article/details/gtpmdonpmq.html

[R68] 计算文件校验值
来源：http://dali.meibo888.top/Article/details/gtmvbqycgf.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.haohaochexian.top/Article/details/gthbylmbmf.html

[R69] 生成随机密码
来源：http://dali.sweek.top/Article/details/gtscvfjtco.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhongyouzk.top/Article/details/gtavlqnkki.html

[R70] 时间戳与互转
来源：http://dali.pengpengdd.cyou/Article/details/gtbpklilkb.html

date +%s;  date -d @1700000000
来源：http://dali.sufxvd.cn/Article/details/gtyzstrmgw.html

[R71] 日期格式化
来源：http://dali.jinghuilouyu.cn/Article/details/gtpzpdgrzo.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.sufxvd.cn/Article/details/gtttdzwbrd.html

[R72] 等待端口就绪
来源：http://dali.dashuyun.cn/Article/details/gttrtacupv.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.c1oappe.top/Article/details/gtcipplljo.html

[R73] 分割大日志
来源：http://dali.jinqigfzy.top/Article/details/gtogqpyxhb.html

split -l 1000 big.log part_
来源：http://dali.pycfn.com/Article/details/gtpzhlzvgk.html

[R74] 批量重命名
来源：http://dali.yongpay.top/Article/details/gtzjjqdpas.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhengqikj.top/Article/details/gtckwloqwx.html

[R75] 导出环境变量
来源：http://dali.aibaodan.cn/Article/details/gtsmryrils.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.gaohongyu789.top/Article/details/gtsiwqnecm.html

[R76] 使用临时文件
来源：http://dali.cdnleiting.top/Article/details/gtbkvmyxfd.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.dianchejie.cn/Article/details/gttidhroon.html

[R77] 读取用户输入
来源：http://dali.ppjwa.cn/Article/details/gtfoezlxtr.html

read -rp "请输入: " ans
来源：http://dali.yj20258888.top/Article/details/gtskoihdqj.html

[R78] 交互式菜单
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuybcwlsw.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.haohaochexian.top/Article/details/gtjjlmfekn.html

[R79] 解析命令行选项
来源：http://dali.hysaishi.cn/Article/details/gtupsktqyx.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.9152youxi.cn/Article/details/gtqsunqsxr.html

[R80] 查看脚本执行耗时
来源：http://dali.yangfankeji.com/Article/details/gttuaxloaq.html

time ./run.sh
来源：http://dali.pycfn.com/Article/details/gtsfnpntuv.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtqwtizaxt.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gtqdzsinkf.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtbsucjjik.html

[S01] C：Hello World
来源：http://dali.9152youxi.cn/Article/details/gtojlhqglp.html

#include <stdio.h>
来源：http://dali.redwolf501.top/Article/details/gtcsftalgy.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.pengpengdd.cyou/Article/details/gthatepehh.html

[S02] C：变量与格式化输出
来源：http://dali.yuxming.cn/Article/details/gtoyfyjdaz.html

int a = 10; printf("%d\n", a);
来源：http://dali.kuanghao11.cn/Article/details/gtzwgpiyjh.html

[S03] C：读入整数
来源：http://dali.yvedp.cn/Article/details/gtspbxdjlv.html

int x; scanf("%d", &x);
来源：http://dali.jinqigfzy.top/Article/details/gthmgfzzrp.html

[S04] C：字符串复制
来源：http://dali.yongpay.top/Article/details/gtfvwvkexk.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhoulong.xyz/Article/details/gtlulwfame.html

[S05] C：字符串长度
来源：http://dali.jlsjyb.cn/Article/details/gtdidsatcl.html

strlen(s)
来源：http://dali.tian-w.cn/Article/details/gtpetopwyy.html

[S06] C：字符串比较
来源：http://dali.gogol.net.cn/Article/details/gtmpmijbli.html

strcmp(a, b) == 0
来源：http://dali.tianlin.xyz/Article/details/gtyruuirwr.html

[S07] C：数组遍历求和
来源：http://dali.snrcjt.cn/Article/details/gtyccbfxhc.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzvjvqlyd.html

[S08] C：动态内存分配与释放
来源：http://dali.dashuyun.cn/Article/details/gtjwexgaox.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.redwolf501.top/Article/details/gtudtcqjlw.html

[S09] C：结构体定义与初始化
来源：http://dali.mhx1999.top/Article/details/gtucjeaazm.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhengqikj.top/Article/details/gthobfzgvx.html

[S10] C：指针与解引用
来源：http://dali.shangyingyoupin.top/Article/details/gtiqguimnt.html

int *p = &a;  *p = 5;
来源：http://dali.shangyingyoupin.top/Article/details/gtkmqqiynb.html

[S11] C：逐行读文件
来源：http://dali.jiagoushi.top/Article/details/gtkzxbmwcf.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.svipenyu.cn/Article/details/gtdekdkiks.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.yuxming.cn/Article/details/gtozocbzet.html

fclose(f);
来源：http://dali.aizwys.cn/Article/details/gteyeoedgr.html

[S12] C：写文件
来源：http://dali.redwolf501.top/Article/details/gtdsavkgde.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.hywenlv.cn/Article/details/gtruqsybci.html

[S13] C：宏定义
来源：http://dali.9152youxi.cn/Article/details/gtglsumrtk.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.meibo888.top/Article/details/gtunqwjtly.html

[S14] C：枚举
来源：http://dali.316326.xyz/Article/details/gtvrdkiwlq.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.tanke756.top/Article/details/gtiabhwfhs.html

[S15] C：类型转换
来源：http://dali.zycfv.cn/Article/details/gtqhtntpaf.html

(double) a / b
来源：http://dali.andypj.xyz/Article/details/gthbxzcgkq.html

[S16] C：位操作置位
来源：http://dali.hongshengwenyu.top/Article/details/gtesqjkahl.html

x |= (1 << 3);
来源：http://dali.shanyushiyangtech.top/Article/details/gtajewkxfb.html

[S17] C：安全拼接字符串
来源：http://dali.ehwqpu.com/Article/details/gtqogtcsjm.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.gogol.net.cn/Article/details/gtnwmrlkra.html

[S18] C：命令行参数
来源：http://dali.daria6918.cn/Article/details/gtbnfsenbg.html

int main(int argc, char **argv)
来源：http://dali.ehwqpu.com/Article/details/gtqitxyghm.html

[S19] C：快速排序
来源：http://dali.chenjidiqi.icu/Article/details/gtsbvkbzkn.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.tianlin.xyz/Article/details/gtbyvijlxn.html

[S20] C：二分查找
来源：http://dali.cashguo.top/Article/details/gtbojyqyiv.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zdqjudy.top/Article/details/gtwfsyvjgo.html

[S21] C：字符类别判断
来源：http://dali.jinghuilouyu.cn/Article/details/gtultuvnlz.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.tanke756.top/Article/details/gtqsjwbrhi.html

[S22] C：字符串转数字
来源：http://dali.xziqi.cn/Article/details/gtkhobpcej.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.yonumen.top/Article/details/gtalhxtmvd.html

[S23] C：随机数
来源：http://dali.quarkkingdee.top/Article/details/gtcgfqrfmz.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.chenzaomai.com/Article/details/gtoqjrmghm.html

[S24] C：获取本地时间
来源：http://dali.fzhhl.top/Article/details/gtyklcwroa.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.xziqi.cn/Article/details/gtbewqesmf.html

[S25] C：内存拷贝
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkyrepsks.html

memcpy(dst, src, n);
来源：http://dali.yuxming.cn/Article/details/gtjqwvryar.html

[S26] C：内存清零
来源：http://dali.zycfv.cn/Article/details/gtfjrjmcsf.html

memset(a, 0, sizeof a);
来源：http://dali.nanxuanxn.top/Article/details/gtcxlxkyjx.html

[S27] C：定义常量
来源：http://dali.snrcjt.cn/Article/details/gtwddqhfwv.html

const double PI = 3.14159;
来源：http://dali.tian-w.cn/Article/details/gtcnktlunq.html

[S28] C：静态变量
来源：http://dali.aizwys.cn/Article/details/gtzhuqrusv.html

static int counter = 0;
来源：http://dali.jyoumei.cn/Article/details/gtphmxovzd.html

[S29] C：变参函数
来源：http://dali.9152youxi.cn/Article/details/gtptbriape.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.jqgfzy.top/Article/details/gteflaolgi.html

[S30] C：头文件保护
来源：http://dali.smart0.xyz/Article/details/gtsjntqnai.html

#ifndef X_H
来源：http://dali.zdqjudy.top/Article/details/gtrleotuoa.html

#define X_H
来源：http://dali.havefunace.top/Article/details/gtgnzpultp.html

#endif
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlqptabaz.html

[S31] C++：Hello World
来源：http://dali.havefunace.top/Article/details/gtglcpztox.html

#include <iostream>
来源：http://dali.xuetiantiany.cn/Article/details/gtbjjzbuho.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.wangshuangyany.cn/Article/details/gtafarptud.html

[S32] C++：字符串
来源：http://dali.yonumen.top/Article/details/gtxcpxugia.html

std::string s = "hi";  s += "!";
来源：http://dali.shuidangran.top/Article/details/gtihddemqg.html

[S33] C++：vector 增删
来源：http://dali.zhengqikj.top/Article/details/gtmchoeopa.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.hnxiangtu.top/Article/details/gtmgujjhln.html

[S34] C++：遍历 vector
来源：http://dali.meibo888.top/Article/details/gtnnfvlmwv.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.xinyue.icu/Article/details/gtgotuzqzv.html

[S35] C++：map
来源：http://dali.jlsjyb.cn/Article/details/gtwndmtjvq.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.wangshuangyany.cn/Article/details/gtixxnugka.html

[S36] C++：unordered_map
来源：http://dali.yanxiufei.cn/Article/details/gtbgabgcdp.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yj20258.top/Article/details/gtbfasckuo.html

[S37] C++：set
来源：http://dali.meibo888.top/Article/details/gttwypvfbz.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.hysaishi.cn/Article/details/gtjwfgafsf.html

[S38] C++：排序
来源：http://dali.redwolf501.top/Article/details/gttrkzollz.html

std::sort(v.begin(), v.end());
来源：http://dali.gotoacloud.top/Article/details/gtskcfpgmj.html

[S39] C++：自定义比较器排序
来源：http://dali.jqgufenzy.top/Article/details/gtxxdasmgt.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.ehwqpu.com/Article/details/gtlwdouxyx.html

[S40] C++：查找元素
来源：http://dali.yueranfly.top/Article/details/gthbykggvm.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.mhx1999.top/Article/details/gtqlptmvhk.html

[S41] C++：类与构造函数
来源：http://dali.ybcxt.top/Article/details/gtkcgbtrfq.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.yj20258888.top/Article/details/gtzmfjvair.html

[S42] C++：继承与虚函数
来源：http://dali.zhiwuduotai.top/Article/details/gtsywczkni.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhiwuduotai.top/Article/details/gtznvjiecq.html

[S43] C++：智能指针
来源：http://dali.aibaodan.cn/Article/details/gtkwsftmba.html

auto p = std::make_unique<int>(5);
来源：http://dali.cucudq.cn/Article/details/gtkfpaabhw.html

[S44] C++：引用传参
来源：http://dali.zycfv.cn/Article/details/gtshyrqsrc.html

void inc(int &x) { ++x; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtifwoovdb.html

[S45] C++：lambda
来源：http://dali.yj20258.top/Article/details/gtvovlrqax.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.pengpengdd.cyou/Article/details/gthnstjwdi.html

[S46] C++：函数模板
来源：http://dali.shanyushiyangkeji.top/Article/details/gtflbewshw.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.sweek.top/Article/details/gtxfhmjrxj.html

[S47] C++：结构化绑定遍历
来源：http://dali.guannengcc.top/Article/details/gtipajnvfr.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.shangyingyoupin.top/Article/details/gtukmdukbx.html

[S48] C++：逐行读文件
来源：http://dali.sysykeji.top/Article/details/gtdevmnhmv.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtudsteuff.html

while (std::getline(in, line)) { }
来源：http://dali.feifeiyinyue.top/Article/details/gtjphfkiow.html

[S49] C++：写文件
来源：http://dali.jqgufenzy.top/Article/details/gtpjhszrlp.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.fzhhl.top/Article/details/gtmjssszwv.html

[S50] C++：格式化数字
来源：http://dali.yueranfly.top/Article/details/gtytxquvbp.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.jiagoushi.top/Article/details/gtltarcxmh.html

[S51] C++：显式类型转换
来源：http://dali.nanxinkj.top/Article/details/gthkvhrilh.html

static_cast<double>(a) / b
来源：http://dali.shangyingyoupin.top/Article/details/gtvsljbfaz.html

[S52] C++：const 与 noexcept
来源：http://dali.smart0.xyz/Article/details/gttzwjeewz.html

int size() const noexcept { return n_; }
来源：http://dali.shangyingyoupin.top/Article/details/gtancxvuit.html

[S53] C++：移动语义
来源：http://dali.shangyingyoupin.top/Article/details/gttatplqmx.html

std::vector<int> w = std::move(v);
来源：http://dali.hongshengwenyu.top/Article/details/gtmqqgrgsm.html

[S54] C++：异常处理
来源：http://dali.jinqigufen.top/Article/details/gtpsxuxkul.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.nwbrower.top/Article/details/gthkcnqwhe.html

[S55] C++：结构化绑定
来源：http://dali.dianchejie.cn/Article/details/gtbgsjeqdq.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.gotoacloud.top/Article/details/gtaqjfukte.html

[S56] C++：optional
来源：http://dali.hysaishi.cn/Article/details/gthllvozyd.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yuxming.cn/Article/details/gtgrnbdubc.html

[S57] C++：编译期常量
来源：http://dali.redwolf501.top/Article/details/gthbeluhrj.html

constexpr int N = 10;
来源：http://dali.yonumen.top/Article/details/gtvlhtzama.html

[S58] C++：命名空间
来源：http://dali.shzxlz.cn/Article/details/gtcbuguxdk.html

namespace ns { int f() { return 1; } }
来源：http://dali.shuidangran.top/Article/details/gtcqkainez.html

[S59] C++：静态断言
来源：http://dali.zdqjudy.top/Article/details/gtucarbblm.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.yvedp.cn/Article/details/gtvokumpqp.html

[S60] C++：遍历并删除元素
来源：http://dali.yanxiufei.cn/Article/details/gtkimetmzt.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.sysykeji.top/Article/details/gtxalzokml.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtsyytbogw.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yuanzhike.top/Article/details/gtpyxpejec.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtetnqtqex.html

[T01] Kotlin：Hello World
来源：http://dali.birdmap.top/Article/details/gtafgislnj.html

println("Hello")
来源：http://dali.yangfankeji.com/Article/details/gtowyzkrnt.html

[T02] Kotlin：变量
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaelamtvd.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.0kj1m.cn/Article/details/gtoysgnicu.html


<!-- 参考信息 -->