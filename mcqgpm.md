代发 wailian999

set -euo pipefail
来源：http://dali.vqdsnc.cn/Article/details/gtpctreykl.html

[R02] 变量赋值与使用
来源：http://dali.zhengqikj.top/Article/details/gtiqqlcike.html

name="Tom"; echo "$name"
来源：http://dali.yj20258.top/Article/details/gtemoqoycc.html

[R03] 只读变量
来源：http://dali.zdqjudy.top/Article/details/gtwuijjhex.html

readonly PI=3.14
来源：http://dali.gogol.net.cn/Article/details/gtoprmbaet.html

[R04] 位置参数
来源：http://dali.sysykeji.top/Article/details/gtptclhhmi.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.quarkkingdee.top/Article/details/gtcvbgmqjz.html

[R05] 参数默认值
来源：http://dali.kuanghao11.cn/Article/details/gteiomcyfv.html

name="${1:-default}"
来源：http://dali.zhoulong.xyz/Article/details/gtpuucukne.html

[R06] 判断命令是否存在
来源：http://dali.yonumen.top/Article/details/gtsmnpmvaf.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.xuanzx.com/Article/details/gtusftbqcd.html

[R07] if 判断文件
来源：http://dali.dashuyun.cn/Article/details/gtakftvhim.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zycfv.cn/Article/details/gtmrwqvsmf.html

[R08] 数值比较
来源：http://dali.hysaishi.cn/Article/details/gtdofurgox.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.kuanghao11.cn/Article/details/gthyasfdyi.html

[R09] 字符串比较
来源：http://dali.nwbrower.top/Article/details/gtbznwrhnl.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgpptifsq.html

[R10] 正则匹配
来源：http://dali.ydzc1.top/Article/details/gtvmpkuvzr.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.yangfankeji.com/Article/details/gthjzzyxwk.html

[R11] case 多分支
来源：http://dali.chenzaomai.com/Article/details/gtpjxdgxrg.html

case "$1" in
来源：http://dali.jqgufenzy.top/Article/details/gtktlqmdry.html

start) echo "启动" ;;
来源：http://dali.hnqzz.top/Article/details/gtwtqxysix.html

stop)  echo "停止" ;;
来源：http://dali.zhiwuduotai.top/Article/details/gtqvtfcivc.html

*)     echo "未知命令" ;;
来源：http://dali.quarkkingdee.top/Article/details/gtbyoeuvyh.html

esac
来源：http://dali.hysaishi.cn/Article/details/gtnaqnzqec.html

[R12] for 遍历文件
来源：http://dali.shzxlz.cn/Article/details/gtwysmqraq.html

for f in *.txt; do echo "$f"; done
来源：http://dali.yj20258888.top/Article/details/gtjhuuorat.html

[R13] for 计数循环
来源：http://dali.cqqwz.cn/Article/details/gtrwotkdyk.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.sxryk.cn/Article/details/gtmasrpeuy.html

[R14] C 风格 for
来源：http://dali.0kj1m.cn/Article/details/gtzxluvmbm.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.jqgfzy.top/Article/details/gtfxquybgd.html

[R15] while 逐行读文件
来源：http://dali.ybcxt.top/Article/details/gtscudrtjc.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.yonumen.top/Article/details/gteojcsvii.html

[R16] until 等待条件
来源：http://dali.ehwqpu.com/Article/details/gtwrkyoyfg.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.daxiang520.top/Article/details/gtmdidirmh.html

[R17] 数组定义与取值
来源：http://dali.yonumen.top/Article/details/gtuwgzbcjh.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.yonumen.top/Article/details/gtcgjfxaiq.html

[R18] 遍历数组
来源：http://dali.pycfn.com/Article/details/gtbghnkorm.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.quarkkingdee.top/Article/details/gtdyymzosm.html

[R19] 数组长度
来源：http://dali.zhiwuduotai.top/Article/details/gthrmxbrrd.html

echo "${#arr[@]}"
来源：http://dali.zhoulong.xyz/Article/details/gtcpsqtjdc.html

[R20] 关联数组（字典）
来源：http://dali.chenjidiqi.icu/Article/details/gtpgrpsykz.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtebytgvgs.html

[R21] 字符串长度
来源：http://dali.fengsongda.top/Article/details/gtymcmmtef.html

echo "${#s}"
来源：http://dali.sysykeji.top/Article/details/gtjtzavrwm.html

[R22] 截取子串
来源：http://dali.shzxlz.cn/Article/details/gtgqcyrhwh.html

echo "${s:0:5}"
来源：http://dali.c1oappe.top/Article/details/gtfwzclwtf.html

[R23] 字符串替换
来源：http://dali.guannengcc.top/Article/details/gteooxsuch.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.nanxuanxn.top/Article/details/gtiwdnhenb.html

[R24] 大小写转换
来源：http://dali.hywenlv.cn/Article/details/gtvsaojurv.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhongyouzk.top/Article/details/gttsplhakl.html

[R25] 去后缀 / 去前缀
来源：http://dali.jinqigfzy.top/Article/details/gtswswzzae.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.chenjidiqi.icu/Article/details/gtaicbtiwv.html

[R26] 命令替换
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoaqpzdjp.html

now=$(date +%F); echo "$now"
来源：http://dali.cqqwz.cn/Article/details/gtyfbkogka.html

[R27] 算术展开
来源：http://dali.yj20258888.top/Article/details/gtgxeyreag.html

echo $((1 + 2 * 3))
来源：http://dali.zhoulong.xyz/Article/details/gtckuuusyr.html

[R28] 浮点运算
来源：http://dali.yonumen.top/Article/details/gtcmjekaxf.html

echo "scale=2; 10/3" | bc
来源：http://dali.wangdashe.top/Article/details/gtiwmoecsx.html

[R29] 定义函数
来源：http://dali.jiagoushi.top/Article/details/gttreegsoe.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.gzhubu.top/Article/details/gtltdbnker.html

[R30] 函数返回状态码
来源：http://dali.jinqigufen.top/Article/details/gthmffagti.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.shuidangran.top/Article/details/gthqrfcacp.html

[R31] 局部变量
来源：http://dali.jyoumei.cn/Article/details/gtzareyehp.html

f() { local x=1; echo "$x"; }
来源：http://dali.guannengcc.top/Article/details/gtustyfiyr.html

[R32] 参数个数校验
来源：http://dali.zhoulong.xyz/Article/details/gttdrkysci.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.birdmap.top/Article/details/gtsoiqvsnh.html

[R33] 捕获错误并提示行号
来源：http://dali.aibaodan.cn/Article/details/gtwdjgpqab.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgvgnanta.html

[R34] 退出时清理
来源：http://dali.haohaochexian.top/Article/details/gtbvpztjbc.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.havefunace.top/Article/details/gtobhmpaxu.html

[R35] 后台执行并等待
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfzlukafo.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gttugabxjr.html

[R36] 并发执行多个任务
来源：http://dali.vqdsnc.cn/Article/details/gtqmtituxt.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.dashuyun.cn/Article/details/gtsbhmwzoc.html

[R37] 把输出赋给变量
来源：http://dali.tianlin.xyz/Article/details/gtsdtqrwsn.html

files=$(ls -1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gthfiglmxt.html

[R38] 管道串联
来源：http://dali.dashuyun.cn/Article/details/gtufjslkmm.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zycfv.cn/Article/details/gttnhgkjmu.html

[R39] 重定向标准输出与错误
来源：http://dali.jqgufenzy.top/Article/details/gtuhrudejd.html

cmd > out.log 2>&1
来源：http://dali.zycfv.cn/Article/details/gtrdllciqv.html

[R40] 追加写日志
来源：http://dali.cqqwz.cn/Article/details/gtbonmcmyy.html

echo "log" >> out.log
来源：http://dali.ppjwa.cn/Article/details/gtrhfyrtzx.html

[R41] 丢弃输出
来源：http://dali.feifeiyinyue.top/Article/details/gtuemycpui.html

cmd >/dev/null 2>&1
来源：http://dali.yvedp.cn/Article/details/gtbpkvbdzq.html

[R42] 输入重定向
来源：http://dali.nanxuanxn.top/Article/details/gtwqxgctzf.html

wc -l < a.txt
来源：http://dali.haohaochexian.top/Article/details/gtsipuqqtx.html

[R43] 按名字查找文件
来源：http://dali.cdnleiting.top/Article/details/gtxevbzshn.html

find . -name "*.log" -type f
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwjjdstwd.html

[R44] 按修改时间查找
来源：http://dali.xuetiantiany.cn/Article/details/gtfnpcvbuq.html

find . -mtime -7 -type f
来源：http://dali.xziqi.cn/Article/details/gtowaqvxjv.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gtlfigwibn.html

find . -name "*.tmp" -delete
来源：http://dali.zhoulong.xyz/Article/details/gtsgprkzab.html

[R46] 递归替换文件内容
来源：http://dali.shanyushiyangtech.top/Article/details/gthcmofsne.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.tanke756.top/Article/details/gtoppanyjq.html

[R47] sed 单行替换
来源：http://dali.birdmap.top/Article/details/gthbiahknu.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.gaohongyu789.top/Article/details/gtynrdkiho.html

[R48] awk 取指定列
来源：http://dali.dashuyun.cn/Article/details/gtrpxrarnr.html

awk '{print $1, $3}' a.txt
来源：http://dali.sweek.top/Article/details/gtwayenito.html

[R49] awk 带条件
来源：http://dali.nanxinkj.top/Article/details/gtvniawrfe.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.cucudq.cn/Article/details/gtigzrqxfl.html

[R50] awk 求和
来源：http://dali.svipenyu.cn/Article/details/gthggfjtwe.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.bjfxy.top/Article/details/gtavtiaeyp.html

[R51] 排序去重取前几
来源：http://dali.tanke756.top/Article/details/gtgahvwcgc.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.hywenlv.cn/Article/details/gtyvrqftyr.html

[R52] 统计行数
来源：http://dali.yj20258.top/Article/details/gtmmsqnmcm.html

wc -l a.txt
来源：http://dali.jinyuanbaomall.cn/Article/details/gtslqoebvt.html

[R53] 查看文件头与实时尾
来源：http://dali.yvedp.cn/Article/details/gtgpzgrfba.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.jqgfzy.top/Article/details/gtqsnblkkp.html

[R54] 比较两个文件
来源：http://dali.sxryk.cn/Article/details/gtwuztntou.html

diff a.txt b.txt
来源：http://dali.feifeiyinyue.top/Article/details/gtnbmnntiu.html

[R55] 压缩与解压
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcmwyyjcv.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.fengsongda.top/Article/details/gtpimhjcpr.html

[R56] 远程拷贝
来源：http://dali.jqgufenzy.top/Article/details/gtlxrmswfh.html

scp file user@host:/path/
来源：http://dali.hysaishi.cn/Article/details/gtqyzmbtlj.html

[R57] 远程执行命令
来源：http://dali.ppjwa.cn/Article/details/gttjhvvvaf.html

ssh user@host 'uptime'
来源：http://dali.cqqwz.cn/Article/details/gtyzwftzhe.html

[R58] 下载文件
来源：http://dali.jqgufenzy.top/Article/details/gtdpbtvmrm.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.cqqwz.cn/Article/details/gtfbpyqnco.html

[R59] 发 POST JSON
来源：http://dali.jinghuilouyu.cn/Article/details/gtwbefklgx.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gttployomv.html

[R60] 只看 HTTP 状态码
来源：http://dali.vqdsnc.cn/Article/details/gtxzxybidi.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.sweek.top/Article/details/gtjqkixrep.html

[R61] 磁盘占用
来源：http://dali.0kj1m.cn/Article/details/gtxsagycph.html

df -h;  du -sh *
来源：http://dali.snrcjt.cn/Article/details/gtdhsxdwik.html

[R62] 找最占空间的文件
来源：http://dali.guannengcc.top/Article/details/gtfppnisoi.html

du -ah . | sort -rh | head -10
来源：http://dali.jinqigufen.top/Article/details/gtqjztsylu.html

[R63] 内存与进程
来源：http://dali.jqgfzy.top/Article/details/gtxjmrevyc.html

free -h;  ps aux | grep nginx
来源：http://dali.cdnleiting.top/Article/details/gtwwtofozg.html

[R64] 结束进程
来源：http://dali.xziqi.cn/Article/details/gtajanruzs.html

kill -9 $(pgrep -f app.py)
来源：http://dali.gogol.net.cn/Article/details/gtpuxasgme.html

[R65] 查看端口占用
来源：http://dali.sxryk.cn/Article/details/gtqemocsvn.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.hysaishi.cn/Article/details/gtvfdfqktw.html

[R66] 定时任务
来源：http://dali.zhengqikj.top/Article/details/gtezsodedr.html

crontab -e;  crontab -l
来源：http://dali.cheryme.top/Article/details/gtuswzpyds.html

[R67] 生成随机十六进制串
来源：http://dali.jianghu66.top/Article/details/gttzwkilwd.html

openssl rand -hex 16
来源：http://dali.guannengcc.top/Article/details/gtviruwqrs.html

[R68] 计算文件校验值
来源：http://dali.ehwqpu.com/Article/details/gtxgmklnts.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.xuanzx.com/Article/details/gtfffkizmc.html

[R69] 生成随机密码
来源：http://dali.daxiang520.top/Article/details/gtcbjdfpnt.html

head -c 16 /dev/urandom | base64
来源：http://dali.xylfe.cn/Article/details/gtqdmlgfpv.html

[R70] 时间戳与互转
来源：http://dali.gotoacloud.top/Article/details/gtjlcqqtys.html

date +%s;  date -d @1700000000
来源：http://dali.yangfankeji.com/Article/details/gthxpafans.html

[R71] 日期格式化
来源：http://dali.yangfankeji.com/Article/details/gtztnfmiwm.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.dianchejie.cn/Article/details/gtwkulrlsl.html

[R72] 等待端口就绪
来源：http://dali.yangfankeji.com/Article/details/gtseuxmmfo.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.yvedp.cn/Article/details/gtxlhkpecj.html

[R73] 分割大日志
来源：http://dali.guowangkeji.top/Article/details/gtsogcdlcd.html

split -l 1000 big.log part_
来源：http://dali.sxryk.cn/Article/details/gtqxmrmbby.html

[R74] 批量重命名
来源：http://dali.9152youxi.cn/Article/details/gtrauyrelb.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.snrcjt.cn/Article/details/gtftoljctt.html

[R75] 导出环境变量
来源：http://dali.zhengqikj.top/Article/details/gtlmfnurat.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.sweek.top/Article/details/gtwpjditgf.html

[R76] 使用临时文件
来源：http://dali.yuxming.cn/Article/details/gtpgwqyqld.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.fzhhl.top/Article/details/gtgsjvyadt.html

[R77] 读取用户输入
来源：http://dali.andypj.xyz/Article/details/gtnymwwfwu.html

read -rp "请输入: " ans
来源：http://dali.zdqjudy.top/Article/details/gtkjerijeq.html

[R78] 交互式菜单
来源：http://dali.guowangkeji.top/Article/details/gtsxskwjnm.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.yj20258.top/Article/details/gtrrpwstaw.html

[R79] 解析命令行选项
来源：http://dali.shuidangran.top/Article/details/gtxaawccnt.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.yangfankeji.com/Article/details/gtwnqszczs.html

[R80] 查看脚本执行耗时
来源：http://dali.cucudq.cn/Article/details/gtwkrykhki.html

time ./run.sh
来源：http://dali.zycfv.cn/Article/details/gtbigbldin.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtqlfnxhbp.html

S. C / C++ 专题
来源：http://dali.xylfe.cn/Article/details/gteikvadvg.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtscllxvbe.html

[S01] C：Hello World
来源：http://dali.wangshuangyany.cn/Article/details/gtodqwympf.html

#include <stdio.h>
来源：http://dali.chenjidiqi.icu/Article/details/gtufmzoivz.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.xuetiantiany.cn/Article/details/gtbfpnhcih.html

[S02] C：变量与格式化输出
来源：http://dali.fengsongda.top/Article/details/gttnvdrhga.html

int a = 10; printf("%d\n", a);
来源：http://dali.chenjidiqi.icu/Article/details/gtjuejtnbq.html

[S03] C：读入整数
来源：http://dali.xuanzx.com/Article/details/gtzmnfnzrk.html

int x; scanf("%d", &x);
来源：http://dali.wangshuangyany.cn/Article/details/gtjnnpwlhz.html

[S04] C：字符串复制
来源：http://dali.jqgfzy.top/Article/details/gtodsjxijm.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.kuanghao11.cn/Article/details/gtafplybzh.html

[S05] C：字符串长度
来源：http://dali.xuanzx.com/Article/details/gtbhcnexwa.html

strlen(s)
来源：http://dali.sysykeji.top/Article/details/gtbejcitbs.html

[S06] C：字符串比较
来源：http://dali.mhx1999.top/Article/details/gtybmhfgnl.html

strcmp(a, b) == 0
来源：http://dali.gotoacloud.top/Article/details/gthhckraha.html

[S07] C：数组遍历求和
来源：http://dali.fzhhl.top/Article/details/gtrawoelna.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.guowangkeji.top/Article/details/gtdmjlqgfa.html

[S08] C：动态内存分配与释放
来源：http://dali.sufxvd.cn/Article/details/gtircanpae.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.jqgfzy.top/Article/details/gtirhdgevx.html

[S09] C：结构体定义与初始化
来源：http://dali.mhx1999.top/Article/details/gtxsloswsg.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.yj202588.top/Article/details/gtuhkqjhwt.html

[S10] C：指针与解引用
来源：http://dali.yongpay.top/Article/details/gtzkacudge.html

int *p = &a;  *p = 5;
来源：http://dali.fzhhl.top/Article/details/gtshoixsqz.html

[S11] C：逐行读文件
来源：http://dali.ppjwa.cn/Article/details/gtvdmxwndm.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.dianchejie.cn/Article/details/gtjrghzbhs.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.xuetiantiany.cn/Article/details/gtimckwgzp.html

fclose(f);
来源：http://dali.snrcjt.cn/Article/details/gtlmrcickg.html

[S12] C：写文件
来源：http://dali.nwbrower.top/Article/details/gtzuiyadjz.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.hfpthk.cn/Article/details/gtmkdxniwj.html

[S13] C：宏定义
来源：http://dali.jiagoushi.top/Article/details/gtdgzrrflk.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.chenlongwang.top/Article/details/gtjjnkadby.html

[S14] C：枚举
来源：http://dali.iojbl.cn/Article/details/gtilacjtms.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.snrcjt.cn/Article/details/gtbjjsptdb.html

[S15] C：类型转换
来源：http://dali.yj20258888.top/Article/details/gtvzrqhoqx.html

(double) a / b
来源：http://dali.yonumen.top/Article/details/gtcqmaicto.html

[S16] C：位操作置位
来源：http://dali.quarkkingdee.top/Article/details/gtjjwdwzmm.html

x |= (1 << 3);
来源：http://dali.sufxvd.cn/Article/details/gtjanuqrea.html

[S17] C：安全拼接字符串
来源：http://dali.jinqigfzy.top/Article/details/gtjbsvifwh.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.jqgfzy.top/Article/details/gtpjcezmps.html

[S18] C：命令行参数
来源：http://dali.yvedp.cn/Article/details/gtgsurmhjh.html

int main(int argc, char **argv)
来源：http://dali.aizwys.cn/Article/details/gtiztmgeuy.html

[S19] C：快速排序
来源：http://dali.yongpay.top/Article/details/gtsbvaxmno.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.bjfxy.top/Article/details/gtwsaagjux.html

[S20] C：二分查找
来源：http://dali.smart0.xyz/Article/details/gtrmsavsyb.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.nwbrower.top/Article/details/gtzeqprkpl.html

[S21] C：字符类别判断
来源：http://dali.yueranfly.top/Article/details/gtgoovidnl.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.cqqwz.cn/Article/details/gtnoorlqbv.html

[S22] C：字符串转数字
来源：http://dali.hysaishi.cn/Article/details/gtbkekykgg.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.sysykeji.top/Article/details/gtyfaurzpy.html

[S23] C：随机数
来源：http://dali.yuanzhike.top/Article/details/gtxszuyjec.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.cucudq.cn/Article/details/gtzwehvwja.html

[S24] C：获取本地时间
来源：http://dali.smart0.xyz/Article/details/gthokvfsqj.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.gogol.net.cn/Article/details/gttnkhsxcq.html

[S25] C：内存拷贝
来源：http://dali.hongshengwenyu.top/Article/details/gtozjlliee.html

memcpy(dst, src, n);
来源：http://dali.sysykeji.top/Article/details/gtlaxlafrr.html

[S26] C：内存清零
来源：http://dali.ivvv.top/Article/details/gtdvjkswul.html

memset(a, 0, sizeof a);
来源：http://dali.sxryk.cn/Article/details/gtoqdkenvq.html

[S27] C：定义常量
来源：http://dali.zhengqikj.top/Article/details/gtyhhgyzxs.html

const double PI = 3.14159;
来源：http://dali.shanyushiyangtech.top/Article/details/gthzmywzsd.html

[S28] C：静态变量
来源：http://dali.ybcxt.top/Article/details/gtmkyfvfvh.html

static int counter = 0;
来源：http://dali.zhoulong.xyz/Article/details/gtufmmdikw.html

[S29] C：变参函数
来源：http://dali.sxryk.cn/Article/details/gthiqtvoaq.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.vqdsnc.cn/Article/details/gtjmowcdqk.html

[S30] C：头文件保护
来源：http://dali.c1oappe.top/Article/details/gtjgaucjot.html

#ifndef X_H
来源：http://dali.wangdashe.top/Article/details/gtiugrosbu.html

#define X_H
来源：http://dali.cucudq.cn/Article/details/gtvjuwkdzg.html

#endif
来源：http://dali.yangfankeji.com/Article/details/gtokgigthe.html

[S31] C++：Hello World
来源：http://dali.zhengqikj.top/Article/details/gtfvbleixm.html

#include <iostream>
来源：http://dali.316326.xyz/Article/details/gtzhfugnwk.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhixingplan.top/Article/details/gtylztpqvk.html

[S32] C++：字符串
来源：http://dali.quarkkingdee.top/Article/details/gtoncuzvfm.html

std::string s = "hi";  s += "!";
来源：http://dali.zhixingplan.top/Article/details/gtuvcxywsi.html

[S33] C++：vector 增删
来源：http://dali.snrcjt.cn/Article/details/gtbzvvppxx.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.mhx1999.top/Article/details/gtbtijwhqr.html

[S34] C++：遍历 vector
来源：http://dali.yongpay.top/Article/details/gtqimjyzju.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtoqcnfzjs.html

[S35] C++：map
来源：http://dali.sufxvd.cn/Article/details/gtcvtaxmts.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hnqzz.top/Article/details/gtmkgiyppb.html

[S36] C++：unordered_map
来源：http://dali.316326.xyz/Article/details/gtskibhsmt.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.chenlongwang.top/Article/details/gtlngydplz.html

[S37] C++：set
来源：http://dali.yueranfly.top/Article/details/gtvqxzfqjt.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.yvedp.cn/Article/details/gtxmjhaztz.html

[S38] C++：排序
来源：http://dali.quarkkingdee.top/Article/details/gtgbjudbzc.html

std::sort(v.begin(), v.end());
来源：http://dali.sxryk.cn/Article/details/gtbacfbzsm.html

[S39] C++：自定义比较器排序
来源：http://dali.tian-w.cn/Article/details/gtkcjraxbz.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.guowangkeji.top/Article/details/gtqzfsshnv.html

[S40] C++：查找元素
来源：http://dali.yj20258.top/Article/details/gtsgtaacvr.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.daxiang520.top/Article/details/gtekdioshx.html

[S41] C++：类与构造函数
来源：http://dali.jinqigufen.top/Article/details/gtwfwebhqg.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.jqgufenzy.top/Article/details/gttdrgzagn.html

[S42] C++：继承与虚函数
来源：http://dali.zhiwuduotai.top/Article/details/gtaobfcpvi.html

class B : public Base { public: void f() override {} };
来源：http://dali.kuanghao11.cn/Article/details/gtfvgbczrh.html

[S43] C++：智能指针
来源：http://dali.aizwys.cn/Article/details/gtgrddgovp.html

auto p = std::make_unique<int>(5);
来源：http://dali.mhx1999.top/Article/details/gtgjhvecch.html

[S44] C++：引用传参
来源：http://dali.haohaochexian.top/Article/details/gtzscssldu.html

void inc(int &x) { ++x; }
来源：http://dali.zhiwuduotai.top/Article/details/gtziconpns.html

[S45] C++：lambda
来源：http://dali.feifeiyinyue.top/Article/details/gtxljozzek.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhengqikj.top/Article/details/gtkunnztqz.html

[S46] C++：函数模板
来源：http://dali.tian-w.cn/Article/details/gtcbxxgdpe.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.quarkkingdee.top/Article/details/gtexvmrioh.html

[S47] C++：结构化绑定遍历
来源：http://dali.daxiang520.top/Article/details/gtrvcdtziq.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhiwuduotai.top/Article/details/gtpdxomeyz.html

[S48] C++：逐行读文件
来源：http://dali.yvedp.cn/Article/details/gtonusmhgx.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.yvedp.cn/Article/details/gtkggnzatj.html

while (std::getline(in, line)) { }
来源：http://dali.sweek.top/Article/details/gtjwqqjcpz.html

[S49] C++：写文件
来源：http://dali.xinyue.icu/Article/details/gttqquzily.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.shzxlz.cn/Article/details/gtjbrmspxt.html

[S50] C++：格式化数字
来源：http://dali.hnqzz.top/Article/details/gtmrzcsecp.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.daxiang520.top/Article/details/gtqjsijzud.html

[S51] C++：显式类型转换
来源：http://dali.sweek.top/Article/details/gtdscalnsx.html

static_cast<double>(a) / b
来源：http://dali.hnxiangtu.top/Article/details/gtjvtsmrxm.html

[S52] C++：const 与 noexcept
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqbyxzoaj.html

int size() const noexcept { return n_; }
来源：http://dali.yonumen.top/Article/details/gtnbxmuhzz.html

[S53] C++：移动语义
来源：http://dali.bjfxy.top/Article/details/gtdgqqffhe.html

std::vector<int> w = std::move(v);
来源：http://dali.gotoacloud.top/Article/details/gtionatihd.html

[S54] C++：异常处理
来源：http://dali.guannengcc.top/Article/details/gtyniqlofr.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.tianlin.xyz/Article/details/gtdgmawqje.html

[S55] C++：结构化绑定
来源：http://dali.jinqigfzy.top/Article/details/gtxjluiaax.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.andypj.xyz/Article/details/gtwhrbcywq.html

[S56] C++：optional
来源：http://dali.nanxinkj.top/Article/details/gtxvmcqlma.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.quarkkingdee.top/Article/details/gtvmxolfbd.html

[S57] C++：编译期常量
来源：http://dali.cucudq.cn/Article/details/gtpfvtbcdw.html

constexpr int N = 10;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtysjrstkh.html

[S58] C++：命名空间
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmirnbixr.html

namespace ns { int f() { return 1; } }
来源：http://dali.ybcxt.top/Article/details/gthgocbjfr.html

[S59] C++：静态断言
来源：http://dali.9152youxi.cn/Article/details/gtezqnctom.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.chenzaomai.com/Article/details/gtkqkmgvxa.html

[S60] C++：遍历并删除元素
来源：http://dali.jqgufenzy.top/Article/details/gtaqpjpyyz.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.snrcjt.cn/Article/details/gtrvvscznc.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gthpjogcnk.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.haohaochexian.top/Article/details/gtjlzztnqi.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtqloyuiyn.html

[T01] Kotlin：Hello World
来源：http://dali.sweek.top/Article/details/gtpwoirabt.html

println("Hello")
来源：http://dali.cashguo.top/Article/details/gtmelnmacv.html

[T02] Kotlin：变量
来源：http://dali.tanke756.top/Article/details/gtchfnnbim.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.xylfe.cn/Article/details/gthcvltnqy.html


<!-- 参考信息 -->