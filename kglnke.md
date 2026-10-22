代发 wailian999

set -euo pipefail
来源：http://dali.cdnleiting.top/Article/details/gtvjcycixb.html

[R02] 变量赋值与使用
来源：http://dali.9152youxi.cn/Article/details/gtvpqougtp.html

name="Tom"; echo "$name"
来源：http://dali.aibaodan.cn/Article/details/gtdjcilxlu.html

[R03] 只读变量
来源：http://dali.hywenlv.cn/Article/details/gtkieqruho.html

readonly PI=3.14
来源：http://dali.yuanzhike.top/Article/details/gtechsbeid.html

[R04] 位置参数
来源：http://dali.yanxiufei.cn/Article/details/gtvvhtaskt.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.guannengcc.top/Article/details/gtwhasizkv.html

[R05] 参数默认值
来源：http://dali.quarkkingdee.top/Article/details/gtqoceaddm.html

name="${1:-default}"
来源：http://dali.gzhubu.top/Article/details/gtienxccit.html

[R06] 判断命令是否存在
来源：http://dali.shanyushiyangtech.top/Article/details/gtdfqfankv.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.jyoumei.cn/Article/details/gtqdaukitm.html

[R07] if 判断文件
来源：http://dali.aizwys.cn/Article/details/gtfvpyavqd.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.yueranfly.top/Article/details/gtsqfuqteh.html

[R08] 数值比较
来源：http://dali.jyoumei.cn/Article/details/gtwbyzlyzg.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.yangfankeji.com/Article/details/gtofvxwoho.html

[R09] 字符串比较
来源：http://dali.bjfxy.top/Article/details/gtjtlbhgop.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.jinqigufen.top/Article/details/gtltqodiza.html

[R10] 正则匹配
来源：http://dali.9152youxi.cn/Article/details/gtrqeisxuh.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.xuetiantiany.cn/Article/details/gtouxfqmgj.html

[R11] case 多分支
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiwikzelg.html

case "$1" in
来源：http://dali.xylfe.cn/Article/details/gtffqjnalb.html

start) echo "启动" ;;
来源：http://dali.yuanzhike.top/Article/details/gtytrxzhgb.html

stop)  echo "停止" ;;
来源：http://dali.wangdashe.top/Article/details/gtsobhbjev.html

*)     echo "未知命令" ;;
来源：http://dali.smart0.xyz/Article/details/gtxifquwld.html

esac
来源：http://dali.gotoacloud.top/Article/details/gtfudhcmvo.html

[R12] for 遍历文件
来源：http://dali.tanke756.top/Article/details/gtxcdisvca.html

for f in *.txt; do echo "$f"; done
来源：http://dali.shangyingyoupin.top/Article/details/gtyqktojbm.html

[R13] for 计数循环
来源：http://dali.yj20258888.top/Article/details/gtqwqmxxzv.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.wangdashe.top/Article/details/gtfcjozppn.html

[R14] C 风格 for
来源：http://dali.yongpay.top/Article/details/gtjmrxmnes.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.cdnleiting.top/Article/details/gtyjehcsnu.html

[R15] while 逐行读文件
来源：http://dali.sweek.top/Article/details/gtottdtzak.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.ehwqpu.com/Article/details/gtljvxoada.html

[R16] until 等待条件
来源：http://dali.shanyushiyangtech.top/Article/details/gtygspgksm.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.nwbrower.top/Article/details/gtdevlxuuu.html

[R17] 数组定义与取值
来源：http://dali.kuanghao11.cn/Article/details/gtfgdmnoqo.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.yvedp.cn/Article/details/gtlgurlflp.html

[R18] 遍历数组
来源：http://dali.jinyuanbaomall.cn/Article/details/gthacuwune.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.shangyingyoupin.top/Article/details/gtpvgttmww.html

[R19] 数组长度
来源：http://dali.hammf.cn/Article/details/gtelfrmohj.html

echo "${#arr[@]}"
来源：http://dali.zhiwuduotai.top/Article/details/gthbabtpwx.html

[R20] 关联数组（字典）
来源：http://dali.tianlin.xyz/Article/details/gtfqdlwiho.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.ydzc1.top/Article/details/gtztyzkiif.html

[R21] 字符串长度
来源：http://dali.hammf.cn/Article/details/gtnvhzbdde.html

echo "${#s}"
来源：http://dali.jlsjyb.cn/Article/details/gtikoyixtq.html

[R22] 截取子串
来源：http://dali.daria6918.cn/Article/details/gtsoaxlxvk.html

echo "${s:0:5}"
来源：http://dali.gogol.net.cn/Article/details/gtbultepjx.html

[R23] 字符串替换
来源：http://dali.zycfv.cn/Article/details/gtmlpggbse.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.yangfankeji.com/Article/details/gtppgcxeag.html

[R24] 大小写转换
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgdkwlvoo.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.316326.xyz/Article/details/gtssjibybq.html

[R25] 去后缀 / 去前缀
来源：http://dali.gzhubu.top/Article/details/gtynactbyw.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.bjfxy.top/Article/details/gtextsmyxn.html

[R26] 命令替换
来源：http://dali.ybcxt.top/Article/details/gtovpfeych.html

now=$(date +%F); echo "$now"
来源：http://dali.haohaochexian.top/Article/details/gtwdcvnurj.html

[R27] 算术展开
来源：http://dali.jinqigufen.top/Article/details/gtlqrmdveh.html

echo $((1 + 2 * 3))
来源：http://dali.guowangkeji.top/Article/details/gtoobikrbu.html

[R28] 浮点运算
来源：http://dali.jinghuilouyu.cn/Article/details/gtnokunvza.html

echo "scale=2; 10/3" | bc
来源：http://dali.dianchejie.cn/Article/details/gtbpifkmgi.html

[R29] 定义函数
来源：http://dali.quarkkingdee.top/Article/details/gtbqrzuufn.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.yj20258.top/Article/details/gtgscpdeas.html

[R30] 函数返回状态码
来源：http://dali.havefunace.top/Article/details/gtksvqnqhp.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.yongpay.top/Article/details/gtlfurdmvc.html

[R31] 局部变量
来源：http://dali.yongpay.top/Article/details/gtucjvmugb.html

f() { local x=1; echo "$x"; }
来源：http://dali.fengsongda.top/Article/details/gtylrutukb.html

[R32] 参数个数校验
来源：http://dali.yuanzhike.top/Article/details/gtckfynxat.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.shzxlz.cn/Article/details/gtsccihkuc.html

[R33] 捕获错误并提示行号
来源：http://dali.mhx1999.top/Article/details/gthwsvhltj.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.yvedp.cn/Article/details/gtzzkdxfcz.html

[R34] 退出时清理
来源：http://dali.mhx1999.top/Article/details/gtspupyiaa.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.yangfankeji.com/Article/details/gtswsjlrab.html

[R35] 后台执行并等待
来源：http://dali.hfpthk.cn/Article/details/gthzwkezhh.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.ivvv.top/Article/details/gtbntjurto.html

[R36] 并发执行多个任务
来源：http://dali.vqdsnc.cn/Article/details/gtytuppbca.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.chenlongwang.top/Article/details/gtgbiosjvs.html

[R37] 把输出赋给变量
来源：http://dali.shanyushiyangtech.top/Article/details/gtgejsjgqk.html

files=$(ls -1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtelexlcpd.html

[R38] 管道串联
来源：http://dali.shzxlz.cn/Article/details/gtrxhwxdji.html

cat a.txt | grep -i error | wc -l
来源：http://dali.xziqi.cn/Article/details/gtecucwwgq.html

[R39] 重定向标准输出与错误
来源：http://dali.gogol.net.cn/Article/details/gthmjdmjes.html

cmd > out.log 2>&1
来源：http://dali.cdnleiting.top/Article/details/gtsfdsogll.html

[R40] 追加写日志
来源：http://dali.cucudq.cn/Article/details/gtryzmuzig.html

echo "log" >> out.log
来源：http://dali.jqgfzy.top/Article/details/gtwahmhrre.html

[R41] 丢弃输出
来源：http://dali.hywenlv.cn/Article/details/gtdxrsiqwt.html

cmd >/dev/null 2>&1
来源：http://dali.fzhhl.top/Article/details/gtdrhfbzuh.html

[R42] 输入重定向
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxsrjhevd.html

wc -l < a.txt
来源：http://dali.0kj1m.cn/Article/details/gtaijkuafv.html

[R43] 按名字查找文件
来源：http://dali.jqgfzy.top/Article/details/gtadajkkwb.html

find . -name "*.log" -type f
来源：http://dali.zhoulong.xyz/Article/details/gtggwpobjg.html

[R44] 按修改时间查找
来源：http://dali.cqqwz.cn/Article/details/gtjbxburvw.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gtarmwxeho.html

[R45] 批量删除
来源：http://dali.shangyingyoupin.top/Article/details/gtyjjpvwnt.html

find . -name "*.tmp" -delete
来源：http://dali.jinghuilouyu.cn/Article/details/gthmsuxdfb.html

[R46] 递归替换文件内容
来源：http://dali.iojbl.cn/Article/details/gtovpopgky.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.aizwys.cn/Article/details/gtehnlzuxc.html

[R47] sed 单行替换
来源：http://dali.hnxiangtu.top/Article/details/gtyciyykss.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.birdmap.top/Article/details/gtcpomkxkg.html

[R48] awk 取指定列
来源：http://dali.ivvv.top/Article/details/gtzytjphwg.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gtpuqutyyl.html

[R49] awk 带条件
来源：http://dali.cqqwz.cn/Article/details/gtudtrkofp.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhiwuduotai.top/Article/details/gtlfdgovbk.html

[R50] awk 求和
来源：http://dali.hnqzz.top/Article/details/gtvobicywf.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.daxiang520.top/Article/details/gtpqevansc.html

[R51] 排序去重取前几
来源：http://dali.yanxiufei.cn/Article/details/gtqmoalssw.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.yuxming.cn/Article/details/gtmasvvxxj.html

[R52] 统计行数
来源：http://dali.jyoumei.cn/Article/details/gtxuvewfqe.html

wc -l a.txt
来源：http://dali.ppjwa.cn/Article/details/gtsfhjpank.html

[R53] 查看文件头与实时尾
来源：http://dali.nanxuanxn.top/Article/details/gtnbgfgvma.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.gotoacloud.top/Article/details/gtbbksovdu.html

[R54] 比较两个文件
来源：http://dali.bjfxy.top/Article/details/gtpwgtnimk.html

diff a.txt b.txt
来源：http://dali.hammf.cn/Article/details/gtstlwvdcc.html

[R55] 压缩与解压
来源：http://dali.9152youxi.cn/Article/details/gtkssbxvko.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.havefunace.top/Article/details/gtroyjzkyt.html

[R56] 远程拷贝
来源：http://dali.jyoumei.cn/Article/details/gttzwozbre.html

scp file user@host:/path/
来源：http://dali.chenjidiqi.icu/Article/details/gtwstgdwct.html

[R57] 远程执行命令
来源：http://dali.gzhubu.top/Article/details/gtrzgkdzlo.html

ssh user@host 'uptime'
来源：http://dali.jyoumei.cn/Article/details/gtclkfheqv.html

[R58] 下载文件
来源：http://dali.jlsjyb.cn/Article/details/gtctikkhmd.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.hammf.cn/Article/details/gtclgzddtu.html

[R59] 发 POST JSON
来源：http://dali.gogol.net.cn/Article/details/gtjgybtyzl.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.guannengcc.top/Article/details/gtxuopbdvm.html

[R60] 只看 HTTP 状态码
来源：http://dali.redwolf501.top/Article/details/gtphxfyaqi.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.yangfankeji.com/Article/details/gtvsndamft.html

[R61] 磁盘占用
来源：http://dali.zhoulong.xyz/Article/details/gtxdbwaynn.html

df -h;  du -sh *
来源：http://dali.yueranfly.top/Article/details/gthfhezoqz.html

[R62] 找最占空间的文件
来源：http://dali.zycfv.cn/Article/details/gteyxfffjb.html

du -ah . | sort -rh | head -10
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzmhsiuuv.html

[R63] 内存与进程
来源：http://dali.feifeiyinyue.top/Article/details/gtfwzboorx.html

free -h;  ps aux | grep nginx
来源：http://dali.xziqi.cn/Article/details/gtcdpcuhsy.html

[R64] 结束进程
来源：http://dali.wangshuangyany.cn/Article/details/gtcclqtqre.html

kill -9 $(pgrep -f app.py)
来源：http://dali.svipenyu.cn/Article/details/gtuxebkxvb.html

[R65] 查看端口占用
来源：http://dali.jianghu66.top/Article/details/gtaftrgxvq.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.bjfxy.top/Article/details/gtloscskor.html

[R66] 定时任务
来源：http://dali.ehwqpu.com/Article/details/gtgsqalnov.html

crontab -e;  crontab -l
来源：http://dali.nanxinkj.top/Article/details/gtkigcnllk.html

[R67] 生成随机十六进制串
来源：http://dali.redwolf501.top/Article/details/gtssnzclhb.html

openssl rand -hex 16
来源：http://dali.xylfe.cn/Article/details/gtmlyrdakr.html

[R68] 计算文件校验值
来源：http://dali.jinghuilouyu.cn/Article/details/gtqvjgcegm.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.tianlin.xyz/Article/details/gtlteyxozl.html

[R69] 生成随机密码
来源：http://dali.jlsjyb.cn/Article/details/gtypwxffdz.html

head -c 16 /dev/urandom | base64
来源：http://dali.sysykeji.top/Article/details/gtfajwexnm.html

[R70] 时间戳与互转
来源：http://dali.guannengcc.top/Article/details/gtbpgfftry.html

date +%s;  date -d @1700000000
来源：http://dali.dashuyun.cn/Article/details/gtjrvaqixn.html

[R71] 日期格式化
来源：http://dali.cqqwz.cn/Article/details/gtgpxnfxgr.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.jinqigfzy.top/Article/details/gtkujbaymz.html

[R72] 等待端口就绪
来源：http://dali.yueranfly.top/Article/details/gtzggipxyo.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.gotoacloud.top/Article/details/gttxqgevuj.html

[R73] 分割大日志
来源：http://dali.zhiwuduotai.top/Article/details/gtpjdtdasj.html

split -l 1000 big.log part_
来源：http://dali.c1oappe.top/Article/details/gtetiolsic.html

[R74] 批量重命名
来源：http://dali.cheryme.top/Article/details/gtfkjhsjub.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.sysykeji.top/Article/details/gtoyrgvyzl.html

[R75] 导出环境变量
来源：http://dali.xziqi.cn/Article/details/gtjrkzocmt.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gttmpgfonw.html

[R76] 使用临时文件
来源：http://dali.havefunace.top/Article/details/gtpphefdjg.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.jinqigfzy.top/Article/details/gtkqbybbqq.html

[R77] 读取用户输入
来源：http://dali.zdqjudy.top/Article/details/gtgowjszyf.html

read -rp "请输入: " ans
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlncesnwc.html

[R78] 交互式菜单
来源：http://dali.nanxinkj.top/Article/details/gtszmpngcb.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.guowangkeji.top/Article/details/gthuywchqp.html

[R79] 解析命令行选项
来源：http://dali.yuanzhike.top/Article/details/gtpvfplmeh.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.sweek.top/Article/details/gtcqmtaoub.html

[R80] 查看脚本执行耗时
来源：http://dali.zhoulong.xyz/Article/details/gtcgzxicsj.html

time ./run.sh
来源：http://dali.vqdsnc.cn/Article/details/gteiftuqff.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtxgkslccd.html

S. C / C++ 专题
来源：http://dali.birdmap.top/Article/details/gtyugotkrp.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtitazfsyv.html

[S01] C：Hello World
来源：http://dali.yj202588.top/Article/details/gtbhkczrez.html

#include <stdio.h>
来源：http://dali.xinyue.icu/Article/details/gtdlpvghrl.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.jyoumei.cn/Article/details/gtzjzdkwjm.html

[S02] C：变量与格式化输出
来源：http://dali.mhx1999.top/Article/details/gtmzwcdjbv.html

int a = 10; printf("%d\n", a);
来源：http://dali.nwbrower.top/Article/details/gtkdhkygbs.html

[S03] C：读入整数
来源：http://dali.zhoulong.xyz/Article/details/gtzxtdreao.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gtllmgchwe.html

[S04] C：字符串复制
来源：http://dali.havefunace.top/Article/details/gtvrycguou.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.sweek.top/Article/details/gtgeaptxae.html

[S05] C：字符串长度
来源：http://dali.aizwys.cn/Article/details/gtbdskzrws.html

strlen(s)
来源：http://dali.316326.xyz/Article/details/gteiidrjoy.html

[S06] C：字符串比较
来源：http://dali.wangdashe.top/Article/details/gtubxittbd.html

strcmp(a, b) == 0
来源：http://dali.cucudq.cn/Article/details/gtfxjksmlu.html

[S07] C：数组遍历求和
来源：http://dali.yongpay.top/Article/details/gtlqqxywtd.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.9152youxi.cn/Article/details/gtauwevopu.html

[S08] C：动态内存分配与释放
来源：http://dali.wangdashe.top/Article/details/gtlakvrgla.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.jinqigufen.top/Article/details/gtiebxeeai.html

[S09] C：结构体定义与初始化
来源：http://dali.shanyushiyangtech.top/Article/details/gtractyfrg.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.pengpengdd.cyou/Article/details/gtxmnxzflp.html

[S10] C：指针与解引用
来源：http://dali.sufxvd.cn/Article/details/gtxoqqtzna.html

int *p = &a;  *p = 5;
来源：http://dali.yuxming.cn/Article/details/gtpadpzcmv.html

[S11] C：逐行读文件
来源：http://dali.hammf.cn/Article/details/gtkdqbrhno.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.svipenyu.cn/Article/details/gtgfwdnwsk.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.yonumen.top/Article/details/gtdtldbskc.html

fclose(f);
来源：http://dali.yuxming.cn/Article/details/gtpqkygorj.html

[S12] C：写文件
来源：http://dali.sxryk.cn/Article/details/gtczfjpcrq.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.guannengcc.top/Article/details/gtxvcksttw.html

[S13] C：宏定义
来源：http://dali.yuanzhike.top/Article/details/gtdsluicnv.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.guowangkeji.top/Article/details/gtkvjfcyzq.html

[S14] C：枚举
来源：http://dali.svipenyu.cn/Article/details/gteqwrlitc.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.chenjidiqi.icu/Article/details/gtzdkqzect.html

[S15] C：类型转换
来源：http://dali.nanxinkj.top/Article/details/gtrdrbgala.html

(double) a / b
来源：http://dali.shangyingyoupin.top/Article/details/gtdomuwnnf.html

[S16] C：位操作置位
来源：http://dali.jinqigfzy.top/Article/details/gtljuhieem.html

x |= (1 << 3);
来源：http://dali.shzxlz.cn/Article/details/gtnzsaopjp.html

[S17] C：安全拼接字符串
来源：http://dali.chenzaomai.com/Article/details/gtrfcrzxmk.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.daria6918.cn/Article/details/gtinrkbtaa.html

[S18] C：命令行参数
来源：http://dali.shanyushiyangtech.top/Article/details/gtgxjptxiq.html

int main(int argc, char **argv)
来源：http://dali.sysykeji.top/Article/details/gtsbgvtldw.html

[S19] C：快速排序
来源：http://dali.sufxvd.cn/Article/details/gtivfksfxj.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.iojbl.cn/Article/details/gtkfhesnwp.html

[S20] C：二分查找
来源：http://dali.zhiwuduotai.top/Article/details/gtevyphwhs.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.sysykeji.top/Article/details/gtiuwcacma.html

[S21] C：字符类别判断
来源：http://dali.guowangkeji.top/Article/details/gtobhwafkk.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.xinyue.icu/Article/details/gtffjawtfb.html

[S22] C：字符串转数字
来源：http://dali.hysaishi.cn/Article/details/gtqnjjcafu.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.yj20258888.top/Article/details/gtsztunmkq.html

[S23] C：随机数
来源：http://dali.daxiang520.top/Article/details/gtatlqdtzq.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.tanke756.top/Article/details/gtiwnyphij.html

[S24] C：获取本地时间
来源：http://dali.birdmap.top/Article/details/gtypdhssyq.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.9152youxi.cn/Article/details/gtdgbkrxwm.html

[S25] C：内存拷贝
来源：http://dali.jinqigufen.top/Article/details/gtebfokkic.html

memcpy(dst, src, n);
来源：http://dali.cdnleiting.top/Article/details/gtveycaovm.html

[S26] C：内存清零
来源：http://dali.zhengqikj.top/Article/details/gtgexlsicn.html

memset(a, 0, sizeof a);
来源：http://dali.xinyue.icu/Article/details/gtrxyrtkal.html

[S27] C：定义常量
来源：http://dali.cucudq.cn/Article/details/gtzpbcjupj.html

const double PI = 3.14159;
来源：http://dali.aibaodan.cn/Article/details/gtiasvjlxq.html

[S28] C：静态变量
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiuhthgbc.html

static int counter = 0;
来源：http://dali.cheryme.top/Article/details/gtfjvdsojh.html

[S29] C：变参函数
来源：http://dali.xziqi.cn/Article/details/gtndzbzsyu.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.jinqigfzy.top/Article/details/gtkcfqqibl.html

[S30] C：头文件保护
来源：http://dali.birdmap.top/Article/details/gtnpzvqpzi.html

#ifndef X_H
来源：http://dali.zdqjudy.top/Article/details/gtrrjvqpra.html

#define X_H
来源：http://dali.cucudq.cn/Article/details/gtdhvweyex.html

#endif
来源：http://dali.cashguo.top/Article/details/gtedbemzdp.html

[S31] C++：Hello World
来源：http://dali.birdmap.top/Article/details/gtxhvlodbn.html

#include <iostream>
来源：http://dali.shangyingyoupin.top/Article/details/gtvuyukljd.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.cqqwz.cn/Article/details/gtfmspmkhd.html

[S32] C++：字符串
来源：http://dali.yj202588.top/Article/details/gtfndobwnt.html

std::string s = "hi";  s += "!";
来源：http://dali.tian-w.cn/Article/details/gttzpkagih.html

[S33] C++：vector 增删
来源：http://dali.shuidangran.top/Article/details/gtklvofkdb.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.shzxlz.cn/Article/details/gtryipzhag.html

[S34] C++：遍历 vector
来源：http://dali.tanke756.top/Article/details/gthmjeniru.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.fzhhl.top/Article/details/gtshvdmvvu.html

[S35] C++：map
来源：http://dali.guowangkeji.top/Article/details/gtevzdzkbs.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.ydzc1.top/Article/details/gtbshymubh.html

[S36] C++：unordered_map
来源：http://dali.zhoulong.xyz/Article/details/gtjpamqxwn.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.c1oappe.top/Article/details/gtinxflwcw.html

[S37] C++：set
来源：http://dali.jqgfzy.top/Article/details/gtenjagexq.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zdqjudy.top/Article/details/gtcqatmzbn.html

[S38] C++：排序
来源：http://dali.jinqigfzy.top/Article/details/gtmhvssooz.html

std::sort(v.begin(), v.end());
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwckbocao.html

[S39] C++：自定义比较器排序
来源：http://dali.9152youxi.cn/Article/details/gtvflypciz.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.yuxming.cn/Article/details/gtpqwtbjop.html

[S40] C++：查找元素
来源：http://dali.kuanghao11.cn/Article/details/gttbkyomfz.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.ehwqpu.com/Article/details/gtckpuwjze.html

[S41] C++：类与构造函数
来源：http://dali.yj20258.top/Article/details/gtugbtnghl.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.jinqigfzy.top/Article/details/gtozkwmxcb.html

[S42] C++：继承与虚函数
来源：http://dali.cashguo.top/Article/details/gtzzndgtil.html

class B : public Base { public: void f() override {} };
来源：http://dali.yonumen.top/Article/details/gtlateirel.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gtnkfnvops.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdddftgfl.html

[S44] C++：引用传参
来源：http://dali.smart0.xyz/Article/details/gtugsndjgs.html

void inc(int &x) { ++x; }
来源：http://dali.cheryme.top/Article/details/gtitvowelm.html

[S45] C++：lambda
来源：http://dali.hfpthk.cn/Article/details/gtcwfkmjxc.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.yuanzhike.top/Article/details/gtobsmvabg.html

[S46] C++：函数模板
来源：http://dali.cucudq.cn/Article/details/gtznasllfy.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.jianghu66.top/Article/details/gtnszuobet.html

[S47] C++：结构化绑定遍历
来源：http://dali.ivvv.top/Article/details/gthnhrimzo.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.yonumen.top/Article/details/gtlvnxhdzm.html

[S48] C++：逐行读文件
来源：http://dali.yuanzhike.top/Article/details/gtdjnnmypw.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhoulong.xyz/Article/details/gtnevnsokc.html

while (std::getline(in, line)) { }
来源：http://dali.pengpengdd.cyou/Article/details/gtyixsiwha.html

[S49] C++：写文件
来源：http://dali.xinyue.icu/Article/details/gtxbbbihcm.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkbtlcozl.html

[S50] C++：格式化数字
来源：http://dali.mhx1999.top/Article/details/gtjrbyhmnk.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.cqqwz.cn/Article/details/gtnryxwgzi.html

[S51] C++：显式类型转换
来源：http://dali.gzhubu.top/Article/details/gtamkuclph.html

static_cast<double>(a) / b
来源：http://dali.jianghu66.top/Article/details/gtbarzabtr.html

[S52] C++：const 与 noexcept
来源：http://dali.guannengcc.top/Article/details/gthxhlnfax.html

int size() const noexcept { return n_; }
来源：http://dali.bjfxy.top/Article/details/gtidqubxsf.html

[S53] C++：移动语义
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsniqpthk.html

std::vector<int> w = std::move(v);
来源：http://dali.sysykeji.top/Article/details/gtesuukczg.html

[S54] C++：异常处理
来源：http://dali.havefunace.top/Article/details/gtltmpdooc.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.andypj.xyz/Article/details/gtjpwrzlyu.html

[S55] C++：结构化绑定
来源：http://dali.xinyue.icu/Article/details/gtdnroofir.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.nanxinkj.top/Article/details/gtnahrlvth.html

[S56] C++：optional
来源：http://dali.cashguo.top/Article/details/gtqhqguvxg.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.tian-w.cn/Article/details/gtpupwkfge.html

[S57] C++：编译期常量
来源：http://dali.fengsongda.top/Article/details/gtjqkwqlde.html

constexpr int N = 10;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbmddqopi.html

[S58] C++：命名空间
来源：http://dali.c1oappe.top/Article/details/gtgcfjsgkm.html

namespace ns { int f() { return 1; } }
来源：http://dali.ppjwa.cn/Article/details/gtpdibxian.html

[S59] C++：静态断言
来源：http://dali.hammf.cn/Article/details/gtqeqcmklf.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.guannengcc.top/Article/details/gtpijlaaiw.html

[S60] C++：遍历并删除元素
来源：http://dali.feifeiyinyue.top/Article/details/gtfqirwgez.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.yueranfly.top/Article/details/gtaherheut.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtuzarqfnq.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yj202588.top/Article/details/gtnwzcxjrf.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtlygucegy.html

[T01] Kotlin：Hello World
来源：http://dali.chenlongwang.top/Article/details/gtuvfqmvuk.html

println("Hello")
来源：http://dali.zhoulong.xyz/Article/details/gtcbmrgudw.html

[T02] Kotlin：变量
来源：http://dali.meibo888.top/Article/details/gtbpgkmfbi.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.aizwys.cn/Article/details/gtborngpxb.html


<!-- 参考信息 -->