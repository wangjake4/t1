代发 wailian999

name="${1:-default}"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtauvteotw.html

[R06] 判断命令是否存在
来源：http://dali.cheryme.top/Article/details/gtkearvabt.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtczlitxzv.html

[R07] if 判断文件
来源：http://dali.andypj.xyz/Article/details/gtatmyidut.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.daria6918.cn/Article/details/gtyqobitrf.html

[R08] 数值比较
来源：http://dali.hnqzz.top/Article/details/gtjizlgxft.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.snrcjt.cn/Article/details/gtxzsjquxi.html

[R09] 字符串比较
来源：http://dali.svipenyu.cn/Article/details/gtwtpkelel.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhixingplan.top/Article/details/gtnygnketm.html

[R10] 正则匹配
来源：http://dali.shuidangran.top/Article/details/gttdnmqxjf.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.vqdsnc.cn/Article/details/gtksabzaaw.html

[R11] case 多分支
来源：http://dali.jlsjyb.cn/Article/details/gtwrwbvrgr.html

case "$1" in
来源：http://dali.quarkkingdee.top/Article/details/gtrjtvubqd.html

start) echo "启动" ;;
来源：http://dali.chenlongwang.top/Article/details/gtawvgqzly.html

stop)  echo "停止" ;;
来源：http://dali.xuetiantiany.cn/Article/details/gtmujorfqw.html

*)     echo "未知命令" ;;
来源：http://dali.kuanghao11.cn/Article/details/gtucdvgqod.html

esac
来源：http://dali.haohaochexian.top/Article/details/gtqqyieose.html

[R12] for 遍历文件
来源：http://dali.cashguo.top/Article/details/gtuuyymekr.html

for f in *.txt; do echo "$f"; done
来源：http://dali.pengpengdd.cyou/Article/details/gtitnjigkz.html

[R13] for 计数循环
来源：http://dali.birdmap.top/Article/details/gtanzfyqxi.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.gzhubu.top/Article/details/gtsdcicaow.html

[R14] C 风格 for
来源：http://dali.hfpthk.cn/Article/details/gtnjxeuaai.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.ppjwa.cn/Article/details/gtlejzuhfs.html

[R15] while 逐行读文件
来源：http://dali.gotoacloud.top/Article/details/gtgskindou.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.sxryk.cn/Article/details/gtlshpaykk.html

[R16] until 等待条件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqqtzjwgx.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.yonumen.top/Article/details/gtdgqlljfq.html

[R17] 数组定义与取值
来源：http://dali.gaohongyu789.top/Article/details/gtkcwvxbqj.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.yj20258888.top/Article/details/gtybfpsevx.html

[R18] 遍历数组
来源：http://dali.yongpay.top/Article/details/gteacaatkn.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.sysykeji.top/Article/details/gtczypngnf.html

[R19] 数组长度
来源：http://dali.tanke756.top/Article/details/gtbpqgjhzb.html

echo "${#arr[@]}"
来源：http://dali.ivvv.top/Article/details/gtdcwacwqs.html

[R20] 关联数组（字典）
来源：http://dali.hywenlv.cn/Article/details/gtmtgrvift.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.ybcxt.top/Article/details/gtitscyzex.html

[R21] 字符串长度
来源：http://dali.hnqzz.top/Article/details/gtcurkpcqy.html

echo "${#s}"
来源：http://dali.meibo888.top/Article/details/gtniqbdvfk.html

[R22] 截取子串
来源：http://dali.hywenlv.cn/Article/details/gtnewipysx.html

echo "${s:0:5}"
来源：http://dali.yanxiufei.cn/Article/details/gtswickorm.html

[R23] 字符串替换
来源：http://dali.zdqjudy.top/Article/details/gtixrexdip.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.hnqzz.top/Article/details/gtkohuessa.html

[R24] 大小写转换
来源：http://dali.tian-w.cn/Article/details/gtfumhxyyl.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.nanxinkj.top/Article/details/gtdvgebnqm.html

[R25] 去后缀 / 去前缀
来源：http://dali.dianchejie.cn/Article/details/gtzhmlrqqk.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.jiagoushi.top/Article/details/gtcwjzdzqv.html

[R26] 命令替换
来源：http://dali.gotoacloud.top/Article/details/gtxklqdzlh.html

now=$(date +%F); echo "$now"
来源：http://dali.wangshuangyany.cn/Article/details/gthplwjcqt.html

[R27] 算术展开
来源：http://dali.jinyuanbaomall.cn/Article/details/gtspaqkaop.html

echo $((1 + 2 * 3))
来源：http://dali.daxiang520.top/Article/details/gtegtxdtqh.html

[R28] 浮点运算
来源：http://dali.tianlin.xyz/Article/details/gtgczyokeu.html

echo "scale=2; 10/3" | bc
来源：http://dali.jiagoushi.top/Article/details/gtixmacymv.html

[R29] 定义函数
来源：http://dali.cdnleiting.top/Article/details/gtimqpdnym.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.havefunace.top/Article/details/gtzirghygn.html

[R30] 函数返回状态码
来源：http://dali.daxiang520.top/Article/details/gtlgaxjtyh.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.jianghu66.top/Article/details/gtpyuaagnt.html

[R31] 局部变量
来源：http://dali.chenlongwang.top/Article/details/gtzefxirjg.html

f() { local x=1; echo "$x"; }
来源：http://dali.jiagoushi.top/Article/details/gtmsdavapw.html

[R32] 参数个数校验
来源：http://dali.dashuyun.cn/Article/details/gttczuhjjp.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.sxryk.cn/Article/details/gtjaaqlglz.html

[R33] 捕获错误并提示行号
来源：http://dali.shanyushiyangtech.top/Article/details/gtiwxbntwo.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhengqikj.top/Article/details/gtyhrqtbbk.html

[R34] 退出时清理
来源：http://dali.redwolf501.top/Article/details/gtmyhdyxoo.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.feifeiyinyue.top/Article/details/gtfbfkomco.html

[R35] 后台执行并等待
来源：http://dali.yueranfly.top/Article/details/gtltjrbcrl.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.gotoacloud.top/Article/details/gtldmrlhwd.html

[R36] 并发执行多个任务
来源：http://dali.jinghuilouyu.cn/Article/details/gthgqxdcvv.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.svipenyu.cn/Article/details/gtebpdbevd.html

[R37] 把输出赋给变量
来源：http://dali.yj202588.top/Article/details/gtjtvwjcsi.html

files=$(ls -1)
来源：http://dali.yj202588.top/Article/details/gtjaiazlfd.html

[R38] 管道串联
来源：http://dali.c1oappe.top/Article/details/gtbgygnvxn.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhoulong.xyz/Article/details/gthcvofjkx.html

[R39] 重定向标准输出与错误
来源：http://dali.zhiwuduotai.top/Article/details/gtkgjkryix.html

cmd > out.log 2>&1
来源：http://dali.yvedp.cn/Article/details/gthyvoxfvj.html

[R40] 追加写日志
来源：http://dali.jqgfzy.top/Article/details/gtpdqrhvdn.html

echo "log" >> out.log
来源：http://dali.sysykeji.top/Article/details/gtfucctymd.html

[R41] 丢弃输出
来源：http://dali.c1oappe.top/Article/details/gthtcvxecm.html

cmd >/dev/null 2>&1
来源：http://dali.tian-w.cn/Article/details/gtvdfxrcgp.html

[R42] 输入重定向
来源：http://dali.zhiwuduotai.top/Article/details/gthkremqnw.html

wc -l < a.txt
来源：http://dali.wangshuangyany.cn/Article/details/gtepfzfhfa.html

[R43] 按名字查找文件
来源：http://dali.jqgfzy.top/Article/details/gtqczevgrc.html

find . -name "*.log" -type f
来源：http://dali.zhoulong.xyz/Article/details/gtvhrhejmr.html

[R44] 按修改时间查找
来源：http://dali.cdnleiting.top/Article/details/gtmragcntr.html

find . -mtime -7 -type f
来源：http://dali.dianchejie.cn/Article/details/gtrlbfxbsi.html

[R45] 批量删除
来源：http://dali.jinqigfzy.top/Article/details/gteflhoreq.html

find . -name "*.tmp" -delete
来源：http://dali.zhongyouzk.top/Article/details/gtkvkiqnuj.html

[R46] 递归替换文件内容
来源：http://dali.tian-w.cn/Article/details/gtzjqpqeah.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.shangyingyoupin.top/Article/details/gtdxlhqkto.html

[R47] sed 单行替换
来源：http://dali.hnqzz.top/Article/details/gtqkqzrioj.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.andypj.xyz/Article/details/gtngmsvtjw.html

[R48] awk 取指定列
来源：http://dali.chenzaomai.com/Article/details/gtwsgofxrt.html

awk '{print $1, $3}' a.txt
来源：http://dali.ehwqpu.com/Article/details/gtrelvfado.html

[R49] awk 带条件
来源：http://dali.hongshengwenyu.top/Article/details/gttkeqcgej.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.birdmap.top/Article/details/gtkcxgtzru.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gtelehvqrh.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.xinyue.icu/Article/details/gtkdracghn.html

[R51] 排序去重取前几
来源：http://dali.vqdsnc.cn/Article/details/gthlovcmee.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.yanxiufei.cn/Article/details/gtviakrgiw.html

[R52] 统计行数
来源：http://dali.chenjidiqi.icu/Article/details/gthfeewxkv.html

wc -l a.txt
来源：http://dali.zycfv.cn/Article/details/gtwphlmvzc.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gtyxaatyvf.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gtfuphbzvc.html

[R54] 比较两个文件
来源：http://dali.andypj.xyz/Article/details/gtiqtkdprz.html

diff a.txt b.txt
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmfgfqsof.html

[R55] 压缩与解压
来源：http://dali.sweek.top/Article/details/gtaauxudyg.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.guowangkeji.top/Article/details/gtxirdyexi.html

[R56] 远程拷贝
来源：http://dali.sufxvd.cn/Article/details/gtwwayvkfb.html

scp file user@host:/path/
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjqboxphs.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gtufskcuab.html

ssh user@host 'uptime'
来源：http://dali.cheryme.top/Article/details/gtdwkptgam.html

[R58] 下载文件
来源：http://dali.cashguo.top/Article/details/gtihizpsud.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.quarkkingdee.top/Article/details/gtsodoousm.html

[R59] 发 POST JSON
来源：http://dali.chenjidiqi.icu/Article/details/gtzqtdyimo.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.xziqi.cn/Article/details/gtbfeqoaol.html

[R60] 只看 HTTP 状态码
来源：http://dali.yangfankeji.com/Article/details/gtdbbfrtuf.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.yongpay.top/Article/details/gtcdldzanb.html

[R61] 磁盘占用
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsbuqyisa.html

df -h;  du -sh *
来源：http://dali.jinghuilouyu.cn/Article/details/gtlxkunmdp.html

[R62] 找最占空间的文件
来源：http://dali.chenjidiqi.icu/Article/details/gthihvvuiq.html

du -ah . | sort -rh | head -10
来源：http://dali.ivvv.top/Article/details/gtbsvdxzcr.html

[R63] 内存与进程
来源：http://dali.zhiwuduotai.top/Article/details/gtbzjsujnt.html

free -h;  ps aux | grep nginx
来源：http://dali.nanxinkj.top/Article/details/gteiprvqis.html

[R64] 结束进程
来源：http://dali.shangyingyoupin.top/Article/details/gttzhbfryi.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhongyouzk.top/Article/details/gtabbxstoe.html

[R65] 查看端口占用
来源：http://dali.snrcjt.cn/Article/details/gtvlglxagw.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.c1oappe.top/Article/details/gtmbzmvobr.html

[R66] 定时任务
来源：http://dali.daria6918.cn/Article/details/gthpzwkczo.html

crontab -e;  crontab -l
来源：http://dali.shanyushiyangtech.top/Article/details/gtvtubzdws.html

[R67] 生成随机十六进制串
来源：http://dali.andypj.xyz/Article/details/gtsiivzhti.html

openssl rand -hex 16
来源：http://dali.yueranfly.top/Article/details/gtvcpmiaxy.html

[R68] 计算文件校验值
来源：http://dali.guannengcc.top/Article/details/gtpxzsqusz.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zdqjudy.top/Article/details/gtwugvtvic.html

[R69] 生成随机密码
来源：http://dali.fengsongda.top/Article/details/gtjdmcxdqr.html

head -c 16 /dev/urandom | base64
来源：http://dali.ybcxt.top/Article/details/gtqwaejmlh.html

[R70] 时间戳与互转
来源：http://dali.hammf.cn/Article/details/gtquleybzh.html

date +%s;  date -d @1700000000
来源：http://dali.tanke756.top/Article/details/gtslqghrav.html

[R71] 日期格式化
来源：http://dali.dianchejie.cn/Article/details/gtqhwtonau.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.jianghu66.top/Article/details/gtxhpngcee.html

[R72] 等待端口就绪
来源：http://dali.jqgufenzy.top/Article/details/gtjdnjlibr.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhongyouzk.top/Article/details/gtuykhjtaj.html

[R73] 分割大日志
来源：http://dali.ybcxt.top/Article/details/gtiyubeibg.html

split -l 1000 big.log part_
来源：http://dali.meibo888.top/Article/details/gtkacmsfyl.html

[R74] 批量重命名
来源：http://dali.kuanghao11.cn/Article/details/gtitxhzify.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.bjfxy.top/Article/details/gthhpcliqg.html

[R75] 导出环境变量
来源：http://dali.wangdashe.top/Article/details/gtcsmqprdg.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.tianlin.xyz/Article/details/gtocnuzhci.html

[R76] 使用临时文件
来源：http://dali.sysykeji.top/Article/details/gtzfhukjmq.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhengqikj.top/Article/details/gtppntgkrw.html

[R77] 读取用户输入
来源：http://dali.chenjidiqi.icu/Article/details/gtviluthsi.html

read -rp "请输入: " ans
来源：http://dali.zhixingplan.top/Article/details/gtaozecmet.html

[R78] 交互式菜单
来源：http://dali.yueranfly.top/Article/details/gtqrcpenos.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvzptlmaa.html

[R79] 解析命令行选项
来源：http://dali.pengpengdd.cyou/Article/details/gtnqwykmsr.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.cdnleiting.top/Article/details/gtxuervqai.html

[R80] 查看脚本执行耗时
来源：http://dali.gzhubu.top/Article/details/gtpwpdocyy.html

time ./run.sh
来源：http://dali.shanyushiyangtech.top/Article/details/gttapvvjiq.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtxugvlavt.html

S. C / C++ 专题
来源：http://dali.hnxiangtu.top/Article/details/gtwgrevpxr.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtxosvgatl.html

[S01] C：Hello World
来源：http://dali.pengpengdd.cyou/Article/details/gtwuytoutm.html

#include <stdio.h>
来源：http://dali.jiagoushi.top/Article/details/gttsrjpihv.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.svipenyu.cn/Article/details/gtvsukwtmi.html

[S02] C：变量与格式化输出
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgigqmsiz.html

int a = 10; printf("%d\n", a);
来源：http://dali.svipenyu.cn/Article/details/gtkgluxkuu.html

[S03] C：读入整数
来源：http://dali.zdqjudy.top/Article/details/gtfhufbnio.html

int x; scanf("%d", &x);
来源：http://dali.redwolf501.top/Article/details/gtjluurhkd.html

[S04] C：字符串复制
来源：http://dali.daxiang520.top/Article/details/gtymianqpb.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.cqqwz.cn/Article/details/gtfmgjqnfj.html

[S05] C：字符串长度
来源：http://dali.yanxiufei.cn/Article/details/gtazwatwod.html

strlen(s)
来源：http://dali.birdmap.top/Article/details/gtsvezlwxb.html

[S06] C：字符串比较
来源：http://dali.jyoumei.cn/Article/details/gtcfkznkcq.html

strcmp(a, b) == 0
来源：http://dali.pengpengdd.cyou/Article/details/gtxykwlwhm.html

[S07] C：数组遍历求和
来源：http://dali.yuxming.cn/Article/details/gtxvrsgqqz.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.sufxvd.cn/Article/details/gtrevigsjr.html

[S08] C：动态内存分配与释放
来源：http://dali.guannengcc.top/Article/details/gtgtszrcab.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zycfv.cn/Article/details/gtemxxefeu.html

[S09] C：结构体定义与初始化
来源：http://dali.0kj1m.cn/Article/details/gtzhwfhatk.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxvitugxd.html

[S10] C：指针与解引用
来源：http://dali.jinqigufen.top/Article/details/gtdedoaguy.html

int *p = &a;  *p = 5;
来源：http://dali.aizwys.cn/Article/details/gtdmrqyvhz.html

[S11] C：逐行读文件
来源：http://dali.bjfxy.top/Article/details/gtsxeugbrh.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.xylfe.cn/Article/details/gtswnjqmod.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.jinqigufen.top/Article/details/gtirevhbwk.html

fclose(f);
来源：http://dali.redwolf501.top/Article/details/gtmsecqgqa.html

[S12] C：写文件
来源：http://dali.gaohongyu789.top/Article/details/gtdhpqqyex.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.aibaodan.cn/Article/details/gtwcatqrqo.html

[S13] C：宏定义
来源：http://dali.hnxiangtu.top/Article/details/gtsbvbeisq.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.tianlin.xyz/Article/details/gtsnkcooef.html

[S14] C：枚举
来源：http://dali.ybcxt.top/Article/details/gtiaqpmspo.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.bjfxy.top/Article/details/gtydzkendj.html

[S15] C：类型转换
来源：http://dali.cheryme.top/Article/details/gtfloznakf.html

(double) a / b
来源：http://dali.feifeiyinyue.top/Article/details/gtlpnmfphg.html

[S16] C：位操作置位
来源：http://dali.jinqigfzy.top/Article/details/gtxnqlpzip.html

x |= (1 << 3);
来源：http://dali.hnxiangtu.top/Article/details/gtbesesylm.html

[S17] C：安全拼接字符串
来源：http://dali.fzhhl.top/Article/details/gtrerdkulw.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbkmwuiul.html

[S18] C：命令行参数
来源：http://dali.svipenyu.cn/Article/details/gtstjdyvvq.html

int main(int argc, char **argv)
来源：http://dali.shuidangran.top/Article/details/gtijwnydxh.html

[S19] C：快速排序
来源：http://dali.daxiang520.top/Article/details/gtddtfdhhe.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.dashuyun.cn/Article/details/gtqibapjgf.html

[S20] C：二分查找
来源：http://dali.yj20258888.top/Article/details/gtfwgojuhm.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.wangshuangyany.cn/Article/details/gtqkporehi.html

[S21] C：字符类别判断
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfxwidwqb.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.ppjwa.cn/Article/details/gtthjbcqds.html

[S22] C：字符串转数字
来源：http://dali.cheryme.top/Article/details/gtucxzgfyb.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.cheryme.top/Article/details/gthfrwgecu.html

[S23] C：随机数
来源：http://dali.jyoumei.cn/Article/details/gtwfljpyml.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.tian-w.cn/Article/details/gtdmqndsfl.html

[S24] C：获取本地时间
来源：http://dali.fengsongda.top/Article/details/gttivoiuzp.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.sweek.top/Article/details/gtpzxckjoe.html

[S25] C：内存拷贝
来源：http://dali.nanxinkj.top/Article/details/gtvkjgjxcf.html

memcpy(dst, src, n);
来源：http://dali.fzhhl.top/Article/details/gtpxbohezf.html

[S26] C：内存清零
来源：http://dali.zhengqikj.top/Article/details/gtdjcfdsmm.html

memset(a, 0, sizeof a);
来源：http://dali.cucudq.cn/Article/details/gtaurfufad.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gttjrxohuv.html

const double PI = 3.14159;
来源：http://dali.yueranfly.top/Article/details/gtdldgbrhs.html

[S28] C：静态变量
来源：http://dali.sxryk.cn/Article/details/gtzdmnxnib.html

static int counter = 0;
来源：http://dali.shangyingyoupin.top/Article/details/gtnbmrrfnx.html

[S29] C：变参函数
来源：http://dali.hnqzz.top/Article/details/gthrabsntx.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.hnqzz.top/Article/details/gtkybukhyn.html

[S30] C：头文件保护
来源：http://dali.hongshengwenyu.top/Article/details/gtgvzbatju.html

#ifndef X_H
来源：http://dali.wangshuangyany.cn/Article/details/gtkhihxdvd.html

#define X_H
来源：http://dali.daria6918.cn/Article/details/gtndmvktdx.html

#endif
来源：http://dali.fzhhl.top/Article/details/gtyygnxuzk.html

[S31] C++：Hello World
来源：http://dali.dashuyun.cn/Article/details/gtxijgyfaq.html

#include <iostream>
来源：http://dali.nanxuanxn.top/Article/details/gtrnyhkmuk.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.9152youxi.cn/Article/details/gtmopehdvl.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gturipczdu.html

std::string s = "hi";  s += "!";
来源：http://dali.pycfn.com/Article/details/gtiksvhclx.html

[S33] C++：vector 增删
来源：http://dali.mhx1999.top/Article/details/gtcehssrxj.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.ybcxt.top/Article/details/gtztdxswrl.html

[S34] C++：遍历 vector
来源：http://dali.yongpay.top/Article/details/gtxogqyzdh.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhengqikj.top/Article/details/gtpezygvcn.html

[S35] C++：map
来源：http://dali.yangfankeji.com/Article/details/gtguzttbxf.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.sweek.top/Article/details/gtdvpslffh.html

[S36] C++：unordered_map
来源：http://dali.ppjwa.cn/Article/details/gtwbxhljng.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtieihopfl.html

[S37] C++：set
来源：http://dali.dashuyun.cn/Article/details/gtpmkocmsb.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.gotoacloud.top/Article/details/gtfqtjwxtj.html

[S38] C++：排序
来源：http://dali.yongpay.top/Article/details/gttdmbxick.html

std::sort(v.begin(), v.end());
来源：http://dali.redwolf501.top/Article/details/gtjwsznium.html

[S39] C++：自定义比较器排序
来源：http://dali.snrcjt.cn/Article/details/gtdkrzxghp.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhengqikj.top/Article/details/gthkndtkdx.html

[S40] C++：查找元素
来源：http://dali.meibo888.top/Article/details/gtbmjgpbir.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhiwuduotai.top/Article/details/gtungkmcwo.html

[S41] C++：类与构造函数
来源：http://dali.cdnleiting.top/Article/details/gtkezgbeaj.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.sweek.top/Article/details/gtjnxojlhx.html

[S42] C++：继承与虚函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfttwlypj.html

class B : public Base { public: void f() override {} };
来源：http://dali.xziqi.cn/Article/details/gtewtskbie.html

[S43] C++：智能指针
来源：http://dali.hywenlv.cn/Article/details/gtudnmcuhp.html

auto p = std::make_unique<int>(5);
来源：http://dali.bjfxy.top/Article/details/gtidnrokax.html

[S44] C++：引用传参
来源：http://dali.xinyue.icu/Article/details/gtloaphtmt.html

void inc(int &x) { ++x; }
来源：http://dali.316326.xyz/Article/details/gtdjsrmncx.html

[S45] C++：lambda
来源：http://dali.gogol.net.cn/Article/details/gtkkofqmsc.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.svipenyu.cn/Article/details/gtevhnpuug.html

[S46] C++：函数模板
来源：http://dali.chenjidiqi.icu/Article/details/gtoxncbtyb.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.yj202588.top/Article/details/gtkcekjwtf.html

[S47] C++：结构化绑定遍历
来源：http://dali.cdnleiting.top/Article/details/gtjslwaivw.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.nanxinkj.top/Article/details/gtsgwzodhn.html

[S48] C++：逐行读文件
来源：http://dali.c1oappe.top/Article/details/gthkowivdd.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.kuanghao11.cn/Article/details/gtmgkvvoju.html

while (std::getline(in, line)) { }
来源：http://dali.redwolf501.top/Article/details/gtamuzlgph.html

[S49] C++：写文件
来源：http://dali.zdqjudy.top/Article/details/gtsvzxjjcj.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.ehwqpu.com/Article/details/gtjttizome.html

[S50] C++：格式化数字
来源：http://dali.jianghu66.top/Article/details/gtjvjepzzt.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.ppjwa.cn/Article/details/gtwmgnbnlk.html

[S51] C++：显式类型转换
来源：http://dali.0kj1m.cn/Article/details/gtsmkrqmln.html

static_cast<double>(a) / b
来源：http://dali.0kj1m.cn/Article/details/gtisiimzen.html

[S52] C++：const 与 noexcept
来源：http://dali.gzhubu.top/Article/details/gthzvmqpep.html

int size() const noexcept { return n_; }
来源：http://dali.sufxvd.cn/Article/details/gttdqnvxmp.html

[S53] C++：移动语义
来源：http://dali.zhaomingkeji.xyz/Article/details/gtydrtijsc.html

std::vector<int> w = std::move(v);
来源：http://dali.fzhhl.top/Article/details/gtelvosfpb.html

[S54] C++：异常处理
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbtdcthjg.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.shuidangran.top/Article/details/gtpycasosl.html

[S55] C++：结构化绑定
来源：http://dali.gzhubu.top/Article/details/gtbfzvztwh.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.mhx1999.top/Article/details/gtdqciavld.html

[S56] C++：optional
来源：http://dali.guowangkeji.top/Article/details/gtbwyoxgsc.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.tianlin.xyz/Article/details/gtaajamnfs.html

[S57] C++：编译期常量
来源：http://dali.yanxiufei.cn/Article/details/gtetnadfer.html

constexpr int N = 10;
来源：http://dali.redwolf501.top/Article/details/gtxfamgzxx.html

[S58] C++：命名空间
来源：http://dali.birdmap.top/Article/details/gtqzizwwmr.html

namespace ns { int f() { return 1; } }
来源：http://dali.yongpay.top/Article/details/gtmgcdjyla.html

[S59] C++：静态断言
来源：http://dali.aibaodan.cn/Article/details/gtvafofyjg.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.cashguo.top/Article/details/gtnbiozrqq.html

[S60] C++：遍历并删除元素
来源：http://dali.shangyingyoupin.top/Article/details/gtwuwcuzxw.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.jyoumei.cn/Article/details/gtogbcxnxe.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gthtuuqffj.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.wangshuangyany.cn/Article/details/gtgrpxpseg.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtkasdcmzl.html

[T01] Kotlin：Hello World
来源：http://dali.jyoumei.cn/Article/details/gttdgchofy.html

println("Hello")
来源：http://dali.chenlongwang.top/Article/details/gtapoadxwq.html

[T02] Kotlin：变量
来源：http://dali.316326.xyz/Article/details/gtlzfynwnz.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gtwlxlphzw.html

[T03] Kotlin：字符串模板
来源：http://dali.dashuyun.cn/Article/details/gtochqkamd.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gtkkiyeoba.html

[T04] Kotlin：空安全
来源：http://dali.tianlin.xyz/Article/details/gtidwxjmsj.html

val n: String? = null;  n?.length
来源：http://dali.gzhubu.top/Article/details/gtljiyxtgn.html

[T05] Kotlin：when 表达式
来源：http://dali.yvedp.cn/Article/details/gttovhqizr.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.guowangkeji.top/Article/details/gtiqvviqih.html

[T06] Kotlin：集合映射
来源：http://dali.hnxiangtu.top/Article/details/gtqfcwyvmk.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.jqgufenzy.top/Article/details/gtvoqtkkpv.html


<!-- 参考信息 -->