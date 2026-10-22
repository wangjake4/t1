代发 wailian999

readonly PI=3.14
来源：http://dali.daria6918.cn/Article/details/gtjibbyrlf.html

[R04] 位置参数
来源：http://dali.ppjwa.cn/Article/details/gtqnzkyyvj.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.yvedp.cn/Article/details/gtclaeitwl.html

[R05] 参数默认值
来源：http://dali.cucudq.cn/Article/details/gtkxehxjmc.html

name="${1:-default}"
来源：http://dali.jinghuilouyu.cn/Article/details/gtqsnbocti.html

[R06] 判断命令是否存在
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgsiwshsc.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.smart0.xyz/Article/details/gtaalfvohe.html

[R07] if 判断文件
来源：http://dali.zhiwuduotai.top/Article/details/gtgazqpycx.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.snrcjt.cn/Article/details/gturxfxgvs.html

[R08] 数值比较
来源：http://dali.yongpay.top/Article/details/gtfovmksfx.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.316326.xyz/Article/details/gtnmfbxbro.html

[R09] 字符串比较
来源：http://dali.snrcjt.cn/Article/details/gtyacatbsf.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtadjsqujv.html

[R10] 正则匹配
来源：http://dali.zdqjudy.top/Article/details/gtgwgvefyy.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.9152youxi.cn/Article/details/gtsdagttqc.html

[R11] case 多分支
来源：http://dali.gogol.net.cn/Article/details/gtmitzoyoy.html

case "$1" in
来源：http://dali.aizwys.cn/Article/details/gtnkqgcjyf.html

start) echo "启动" ;;
来源：http://dali.jinqigfzy.top/Article/details/gtuichfjiu.html

stop)  echo "停止" ;;
来源：http://dali.wangshuangyany.cn/Article/details/gteuqsvezq.html

*)     echo "未知命令" ;;
来源：http://dali.vqdsnc.cn/Article/details/gtemqkxxvg.html

esac
来源：http://dali.sysykeji.top/Article/details/gtddcegsvv.html

[R12] for 遍历文件
来源：http://dali.haohaochexian.top/Article/details/gtdbhctohg.html

for f in *.txt; do echo "$f"; done
来源：http://dali.bjfxy.top/Article/details/gteiaulvsa.html

[R13] for 计数循环
来源：http://dali.svipenyu.cn/Article/details/gttaxojrlf.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.sysykeji.top/Article/details/gtfeewjfqa.html

[R14] C 风格 for
来源：http://dali.yj20258888.top/Article/details/gtzyyejjcx.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.xylfe.cn/Article/details/gtwjjywnpz.html

[R15] while 逐行读文件
来源：http://dali.sxryk.cn/Article/details/gtjaqdouti.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.shzxlz.cn/Article/details/gtecsaksit.html

[R16] until 等待条件
来源：http://dali.zhengqikj.top/Article/details/gtpdrfwzkn.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.xuetiantiany.cn/Article/details/gtmkibfqbb.html

[R17] 数组定义与取值
来源：http://dali.pycfn.com/Article/details/gtwlakromn.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.dashuyun.cn/Article/details/gthazmntri.html

[R18] 遍历数组
来源：http://dali.yvedp.cn/Article/details/gtgyynpsme.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.gaohongyu789.top/Article/details/gtjmkranjc.html

[R19] 数组长度
来源：http://dali.xylfe.cn/Article/details/gtksuuorga.html

echo "${#arr[@]}"
来源：http://dali.shzxlz.cn/Article/details/gtzofdlrzr.html

[R20] 关联数组（字典）
来源：http://dali.quarkkingdee.top/Article/details/gtbpkfxsde.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.meibo888.top/Article/details/gtcqypkkep.html

[R21] 字符串长度
来源：http://dali.xuanzx.com/Article/details/gtkkwrxkdr.html

echo "${#s}"
来源：http://dali.gogol.net.cn/Article/details/gtshuwuntf.html

[R22] 截取子串
来源：http://dali.havefunace.top/Article/details/gtqmctjcle.html

echo "${s:0:5}"
来源：http://dali.feifeiyinyue.top/Article/details/gtiwccsuyr.html

[R23] 字符串替换
来源：http://dali.cucudq.cn/Article/details/gtdfwvrjuv.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.aizwys.cn/Article/details/gtorlqingr.html

[R24] 大小写转换
来源：http://dali.shuidangran.top/Article/details/gtdpeeazhm.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.jqgfzy.top/Article/details/gttdmwdyxh.html

[R25] 去后缀 / 去前缀
来源：http://dali.hnxiangtu.top/Article/details/gtebkrogfd.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.jianghu66.top/Article/details/gtycrvnzih.html

[R26] 命令替换
来源：http://dali.jinghuilouyu.cn/Article/details/gtjnnbxedk.html

now=$(date +%F); echo "$now"
来源：http://dali.jlsjyb.cn/Article/details/gtvexdfjbg.html

[R27] 算术展开
来源：http://dali.daria6918.cn/Article/details/gtkcblrgpn.html

echo $((1 + 2 * 3))
来源：http://dali.ybcxt.top/Article/details/gtkmjqlsko.html

[R28] 浮点运算
来源：http://dali.snrcjt.cn/Article/details/gtoimrrltu.html

echo "scale=2; 10/3" | bc
来源：http://dali.ydzc1.top/Article/details/gtvtlyfprj.html

[R29] 定义函数
来源：http://dali.hongshengwenyu.top/Article/details/gtinaszwnk.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.gogol.net.cn/Article/details/gtgdyqxgtw.html

[R30] 函数返回状态码
来源：http://dali.fengsongda.top/Article/details/gtvcdzaiuo.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.bjfxy.top/Article/details/gtdngkxgso.html

[R31] 局部变量
来源：http://dali.zhengqikj.top/Article/details/gtpoagbnou.html

f() { local x=1; echo "$x"; }
来源：http://dali.cdnleiting.top/Article/details/gtyhihqeuz.html

[R32] 参数个数校验
来源：http://dali.sysykeji.top/Article/details/gtoazfffqq.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtquyrtpxn.html

[R33] 捕获错误并提示行号
来源：http://dali.hnxiangtu.top/Article/details/gtktylxbbn.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.ybcxt.top/Article/details/gtmulahace.html

[R34] 退出时清理
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsnoifsie.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.kuanghao11.cn/Article/details/gtkejtctxl.html

[R35] 后台执行并等待
来源：http://dali.yueranfly.top/Article/details/gtkujooaag.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zdqjudy.top/Article/details/gttqbqmtkj.html

[R36] 并发执行多个任务
来源：http://dali.fzhhl.top/Article/details/gtttwyenhe.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.gaohongyu789.top/Article/details/gtzmkeynpb.html

[R37] 把输出赋给变量
来源：http://dali.hammf.cn/Article/details/gtbhapxccw.html

files=$(ls -1)
来源：http://dali.daxiang520.top/Article/details/gtkdirzxiw.html

[R38] 管道串联
来源：http://dali.hnqzz.top/Article/details/gtikzcvppz.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhixingplan.top/Article/details/gtoptkhltj.html

[R39] 重定向标准输出与错误
来源：http://dali.sufxvd.cn/Article/details/gthkhbelza.html

cmd > out.log 2>&1
来源：http://dali.chenlongwang.top/Article/details/gtanvpvniw.html

[R40] 追加写日志
来源：http://dali.haohaochexian.top/Article/details/gtxeeykcza.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gtkhxellbn.html

[R41] 丢弃输出
来源：http://dali.zhengqikj.top/Article/details/gtrjnxnvpm.html

cmd >/dev/null 2>&1
来源：http://dali.sysykeji.top/Article/details/gtextytnwy.html

[R42] 输入重定向
来源：http://dali.jinqigufen.top/Article/details/gtcijsxngh.html

wc -l < a.txt
来源：http://dali.yj20258.top/Article/details/gtzmodoyxa.html

[R43] 按名字查找文件
来源：http://dali.wangdashe.top/Article/details/gtrmwzjjtj.html

find . -name "*.log" -type f
来源：http://dali.zycfv.cn/Article/details/gtqihkrpmy.html

[R44] 按修改时间查找
来源：http://dali.dashuyun.cn/Article/details/gtyjinhujp.html

find . -mtime -7 -type f
来源：http://dali.jinyuanbaomall.cn/Article/details/gtamolmiyl.html

[R45] 批量删除
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwvlheiux.html

find . -name "*.tmp" -delete
来源：http://dali.yj20258888.top/Article/details/gtyhxuagwf.html

[R46] 递归替换文件内容
来源：http://dali.9152youxi.cn/Article/details/gtxxlbcavr.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.hfpthk.cn/Article/details/gtltglgapq.html

[R47] sed 单行替换
来源：http://dali.cqqwz.cn/Article/details/gtcyohddjp.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.feifeiyinyue.top/Article/details/gtdgpqmkyx.html

[R48] awk 取指定列
来源：http://dali.mhx1999.top/Article/details/gtxxuoalci.html

awk '{print $1, $3}' a.txt
来源：http://dali.gzhubu.top/Article/details/gtpzqltjpb.html

[R49] awk 带条件
来源：http://dali.cucudq.cn/Article/details/gtvzjilhzd.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.jianghu66.top/Article/details/gtjebwonro.html

[R50] awk 求和
来源：http://dali.xziqi.cn/Article/details/gtdiylrmew.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.mhx1999.top/Article/details/gtuordgkgg.html

[R51] 排序去重取前几
来源：http://dali.cheryme.top/Article/details/gtklmwiayk.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.shuidangran.top/Article/details/gtfgydqgnm.html

[R52] 统计行数
来源：http://dali.fengsongda.top/Article/details/gtpseiqzis.html

wc -l a.txt
来源：http://dali.daxiang520.top/Article/details/gtigqtkblm.html

[R53] 查看文件头与实时尾
来源：http://dali.yueranfly.top/Article/details/gtbbjmyuqr.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zycfv.cn/Article/details/gtpuyokanm.html

[R54] 比较两个文件
来源：http://dali.dashuyun.cn/Article/details/gtgrtwkgzo.html

diff a.txt b.txt
来源：http://dali.hongshengwenyu.top/Article/details/gtclfcxjza.html

[R55] 压缩与解压
来源：http://dali.yanxiufei.cn/Article/details/gttzztsohi.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.wangdashe.top/Article/details/gtpaeaviak.html

[R56] 远程拷贝
来源：http://dali.yvedp.cn/Article/details/gtpwumfuuj.html

scp file user@host:/path/
来源：http://dali.9152youxi.cn/Article/details/gtoswrrxok.html

[R57] 远程执行命令
来源：http://dali.nanxinkj.top/Article/details/gtrdsozizg.html

ssh user@host 'uptime'
来源：http://dali.nwbrower.top/Article/details/gtguhdtndd.html

[R58] 下载文件
来源：http://dali.yanxiufei.cn/Article/details/gtkryitlrt.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.guannengcc.top/Article/details/gtxaevlkmi.html

[R59] 发 POST JSON
来源：http://dali.hysaishi.cn/Article/details/gtanyapeyf.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.pycfn.com/Article/details/gthkayiezc.html

[R60] 只看 HTTP 状态码
来源：http://dali.hammf.cn/Article/details/gtugcgmade.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.havefunace.top/Article/details/gteyxplyzl.html

[R61] 磁盘占用
来源：http://dali.svipenyu.cn/Article/details/gthzrxbkyp.html

df -h;  du -sh *
来源：http://dali.jinghuilouyu.cn/Article/details/gtuomcxyqp.html

[R62] 找最占空间的文件
来源：http://dali.ehwqpu.com/Article/details/gtimkgkgmj.html

du -ah . | sort -rh | head -10
来源：http://dali.aizwys.cn/Article/details/gtiolxaqcc.html

[R63] 内存与进程
来源：http://dali.cheryme.top/Article/details/gtjwjdbzow.html

free -h;  ps aux | grep nginx
来源：http://dali.hfpthk.cn/Article/details/gtaighpwbw.html

[R64] 结束进程
来源：http://dali.sysykeji.top/Article/details/gtyycjpsop.html

kill -9 $(pgrep -f app.py)
来源：http://dali.jianghu66.top/Article/details/gtqzzwmsuy.html

[R65] 查看端口占用
来源：http://dali.gzhubu.top/Article/details/gtfreqivab.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.jianghu66.top/Article/details/gtmnlvlyyt.html

[R66] 定时任务
来源：http://dali.yvedp.cn/Article/details/gtfmepwgju.html

crontab -e;  crontab -l
来源：http://dali.aibaodan.cn/Article/details/gtkdfwewcr.html

[R67] 生成随机十六进制串
来源：http://dali.zhongyouzk.top/Article/details/gttujfikme.html

openssl rand -hex 16
来源：http://dali.dianchejie.cn/Article/details/gtyfnojifp.html

[R68] 计算文件校验值
来源：http://dali.wangdashe.top/Article/details/gtufxzytws.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.pengpengdd.cyou/Article/details/gtdswolmpk.html

[R69] 生成随机密码
来源：http://dali.nwbrower.top/Article/details/gtiwgilaxk.html

head -c 16 /dev/urandom | base64
来源：http://dali.dianchejie.cn/Article/details/gtxzhkvlsf.html

[R70] 时间戳与互转
来源：http://dali.yuxming.cn/Article/details/gtseofhavv.html

date +%s;  date -d @1700000000
来源：http://dali.wangdashe.top/Article/details/gtakllsdis.html

[R71] 日期格式化
来源：http://dali.dashuyun.cn/Article/details/gtkhqhmljo.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.sxryk.cn/Article/details/gtjoapyfkt.html

[R72] 等待端口就绪
来源：http://dali.tianlin.xyz/Article/details/gtnzzzdidd.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.yongpay.top/Article/details/gtsshgmtbp.html

[R73] 分割大日志
来源：http://dali.snrcjt.cn/Article/details/gtrcimypap.html

split -l 1000 big.log part_
来源：http://dali.yvedp.cn/Article/details/gtkfrjjtkj.html

[R74] 批量重命名
来源：http://dali.daxiang520.top/Article/details/gtwxynovun.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.tian-w.cn/Article/details/gtcxcznhcx.html

[R75] 导出环境变量
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjxbwfcld.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.andypj.xyz/Article/details/gtfwmtwhlg.html

[R76] 使用临时文件
来源：http://dali.vqdsnc.cn/Article/details/gtsfahhdhy.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.chenjidiqi.icu/Article/details/gtsxmqdfxs.html

[R77] 读取用户输入
来源：http://dali.tianlin.xyz/Article/details/gtswzdklsw.html

read -rp "请输入: " ans
来源：http://dali.kuanghao11.cn/Article/details/gtfjxruvly.html

[R78] 交互式菜单
来源：http://dali.fzhhl.top/Article/details/gtdfxexeeq.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.chenlongwang.top/Article/details/gtellrhmwg.html

[R79] 解析命令行选项
来源：http://dali.smart0.xyz/Article/details/gtpluyxhxr.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gtturwmhdy.html

[R80] 查看脚本执行耗时
来源：http://dali.yuanzhike.top/Article/details/gtpducupmw.html

time ./run.sh
来源：http://dali.havefunace.top/Article/details/gtkwgesbqd.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtosveeeed.html

S. C / C++ 专题
来源：http://dali.svipenyu.cn/Article/details/gttavvrxtr.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gteaeirqqh.html

[S01] C：Hello World
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjjpvpvtg.html

#include <stdio.h>
来源：http://dali.jqgfzy.top/Article/details/gtbufoslwy.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.shuidangran.top/Article/details/gtpnzxzlpo.html

[S02] C：变量与格式化输出
来源：http://dali.zhaomingkeji.xyz/Article/details/gthvzmqcyi.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhengqikj.top/Article/details/gtsnosppuf.html

[S03] C：读入整数
来源：http://dali.jinqigufen.top/Article/details/gthzpqkylc.html

int x; scanf("%d", &x);
来源：http://dali.xuanzx.com/Article/details/gtbjdgnhkd.html

[S04] C：字符串复制
来源：http://dali.cashguo.top/Article/details/gtzwgomkog.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.yj202588.top/Article/details/gtatlgcvlj.html

[S05] C：字符串长度
来源：http://dali.xinyue.icu/Article/details/gtnhvtmkad.html

strlen(s)
来源：http://dali.zhengqikj.top/Article/details/gtbgcodwup.html

[S06] C：字符串比较
来源：http://dali.aibaodan.cn/Article/details/gtpxnwkrrz.html

strcmp(a, b) == 0
来源：http://dali.nanxinkj.top/Article/details/gtolmdezed.html

[S07] C：数组遍历求和
来源：http://dali.hnqzz.top/Article/details/gtxjluwcha.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.0kj1m.cn/Article/details/gteqitxirc.html

[S08] C：动态内存分配与释放
来源：http://dali.ivvv.top/Article/details/gtnfytzenr.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.smart0.xyz/Article/details/gtejljxxfr.html

[S09] C：结构体定义与初始化
来源：http://dali.zhixingplan.top/Article/details/gthlxwjsnc.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.snrcjt.cn/Article/details/gtxcgjhjun.html

[S10] C：指针与解引用
来源：http://dali.nanxinkj.top/Article/details/gtesoyrgdh.html

int *p = &a;  *p = 5;
来源：http://dali.feifeiyinyue.top/Article/details/gtobjvzqop.html

[S11] C：逐行读文件
来源：http://dali.hysaishi.cn/Article/details/gtquodbeon.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.nanxuanxn.top/Article/details/gtppntxixo.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.xylfe.cn/Article/details/gtyrmzqutn.html

fclose(f);
来源：http://dali.zhixingplan.top/Article/details/gtgwrtvtla.html

[S12] C：写文件
来源：http://dali.hysaishi.cn/Article/details/gtssrycmfa.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.hysaishi.cn/Article/details/gtxryedlup.html

[S13] C：宏定义
来源：http://dali.tianlin.xyz/Article/details/gtzmlqxryq.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.aibaodan.cn/Article/details/gtitovkrph.html

[S14] C：枚举
来源：http://dali.smart0.xyz/Article/details/gtetmogazg.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.sweek.top/Article/details/gtyndipyhj.html

[S15] C：类型转换
来源：http://dali.sysykeji.top/Article/details/gtbghvovlh.html

(double) a / b
来源：http://dali.gzhubu.top/Article/details/gtspxifxvr.html

[S16] C：位操作置位
来源：http://dali.cqqwz.cn/Article/details/gtkeodplvl.html

x |= (1 << 3);
来源：http://dali.chenjidiqi.icu/Article/details/gtlmgmlafu.html

[S17] C：安全拼接字符串
来源：http://dali.9152youxi.cn/Article/details/gtndopdaxq.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.tian-w.cn/Article/details/gtyjbitotf.html

[S18] C：命令行参数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfgfdtpcv.html

int main(int argc, char **argv)
来源：http://dali.chenlongwang.top/Article/details/gtocfjvkkp.html

[S19] C：快速排序
来源：http://dali.yuanzhike.top/Article/details/gtofltsdfc.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdxouyiov.html

[S20] C：二分查找
来源：http://dali.aibaodan.cn/Article/details/gtuvnyaxaq.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.fzhhl.top/Article/details/gtawcnqpih.html

[S21] C：字符类别判断
来源：http://dali.hnqzz.top/Article/details/gtgzxbxsqz.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.snrcjt.cn/Article/details/gtyedzvkvz.html

[S22] C：字符串转数字
来源：http://dali.ydzc1.top/Article/details/gtidvkwbqd.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.pycfn.com/Article/details/gtrnbxfbva.html

[S23] C：随机数
来源：http://dali.cqqwz.cn/Article/details/gtqxlcpzei.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.shanyushiyangtech.top/Article/details/gtjtzkcrtx.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gtmlnknghl.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.0kj1m.cn/Article/details/gtflooocpz.html

[S25] C：内存拷贝
来源：http://dali.shzxlz.cn/Article/details/gtaxhluhfq.html

memcpy(dst, src, n);
来源：http://dali.zhoulong.xyz/Article/details/gtlzyaxjcg.html

[S26] C：内存清零
来源：http://dali.jyoumei.cn/Article/details/gtbiancvvs.html

memset(a, 0, sizeof a);
来源：http://dali.zhixingplan.top/Article/details/gtyyachwfe.html

[S27] C：定义常量
来源：http://dali.shzxlz.cn/Article/details/gtnulxqypy.html

const double PI = 3.14159;
来源：http://dali.hysaishi.cn/Article/details/gtcdnkppxa.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gtawuivvum.html

static int counter = 0;
来源：http://dali.gaohongyu789.top/Article/details/gtqkxatizd.html

[S29] C：变参函数
来源：http://dali.hywenlv.cn/Article/details/gtiafbgmnp.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zycfv.cn/Article/details/gtslraxmvk.html

[S30] C：头文件保护
来源：http://dali.dianchejie.cn/Article/details/gtjvrduomp.html

#ifndef X_H
来源：http://dali.zycfv.cn/Article/details/gtgqregyln.html

#define X_H
来源：http://dali.zhiwuduotai.top/Article/details/gtcbdwvdqc.html

#endif
来源：http://dali.jiagoushi.top/Article/details/gtmlgxftng.html

[S31] C++：Hello World
来源：http://dali.0kj1m.cn/Article/details/gtbkddmshb.html

#include <iostream>
来源：http://dali.jqgufenzy.top/Article/details/gtnsmitebt.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.svipenyu.cn/Article/details/gtvumtimfa.html

[S32] C++：字符串
来源：http://dali.wangshuangyany.cn/Article/details/gtrdksiobg.html

std::string s = "hi";  s += "!";
来源：http://dali.yueranfly.top/Article/details/gtftwufnvw.html

[S33] C++：vector 增删
来源：http://dali.ybcxt.top/Article/details/gthptstfbc.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhengqikj.top/Article/details/gtrozdmzib.html

[S34] C++：遍历 vector
来源：http://dali.zhaomingkeji.xyz/Article/details/gtifllijdm.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.guannengcc.top/Article/details/gtclzuunod.html

[S35] C++：map
来源：http://dali.hammf.cn/Article/details/gtankowviw.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.gzhubu.top/Article/details/gtuaspkxfh.html

[S36] C++：unordered_map
来源：http://dali.pycfn.com/Article/details/gtkxutkggt.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.smart0.xyz/Article/details/gtcnmvmgdr.html

[S37] C++：set
来源：http://dali.jianghu66.top/Article/details/gtreshiqse.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.yj202588.top/Article/details/gtnnzenncu.html

[S38] C++：排序
来源：http://dali.tanke756.top/Article/details/gtbwtepdki.html

std::sort(v.begin(), v.end());
来源：http://dali.feifeiyinyue.top/Article/details/gtytrobsil.html

[S39] C++：自定义比较器排序
来源：http://dali.zhiwuduotai.top/Article/details/gticofggyv.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.xinyue.icu/Article/details/gtpdqfzfuc.html

[S40] C++：查找元素
来源：http://dali.hammf.cn/Article/details/gtihwlqkpj.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.wangdashe.top/Article/details/gtcdujhycg.html

[S41] C++：类与构造函数
来源：http://dali.xinyue.icu/Article/details/gtmpglhlaf.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.pengpengdd.cyou/Article/details/gtwcabbxlz.html

[S42] C++：继承与虚函数
来源：http://dali.jinghuilouyu.cn/Article/details/gtjjeaksoy.html

class B : public Base { public: void f() override {} };
来源：http://dali.sufxvd.cn/Article/details/gtcurrydcw.html

[S43] C++：智能指针
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnbgkcdih.html

auto p = std::make_unique<int>(5);
来源：http://dali.ybcxt.top/Article/details/gtmmnsmoox.html

[S44] C++：引用传参
来源：http://dali.birdmap.top/Article/details/gtttmzncml.html

void inc(int &x) { ++x; }
来源：http://dali.sysykeji.top/Article/details/gtadvmzlzc.html

[S45] C++：lambda
来源：http://dali.wangdashe.top/Article/details/gtgrbwwqyj.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.meibo888.top/Article/details/gttersabhs.html

[S46] C++：函数模板
来源：http://dali.shzxlz.cn/Article/details/gtrewrkocf.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.kuanghao11.cn/Article/details/gthykurxzy.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhengqikj.top/Article/details/gtrjiizzns.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.bjfxy.top/Article/details/gtamgnawng.html

[S48] C++：逐行读文件
来源：http://dali.jlsjyb.cn/Article/details/gtbixwvxzd.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.tianlin.xyz/Article/details/gtbegugoxh.html

while (std::getline(in, line)) { }
来源：http://dali.daxiang520.top/Article/details/gtjhatwkgw.html

[S49] C++：写文件
来源：http://dali.gzhubu.top/Article/details/gtagrnjkgj.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.yueranfly.top/Article/details/gtnsptekcy.html

[S50] C++：格式化数字
来源：http://dali.wangdashe.top/Article/details/gtbykxvbay.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrjtagsll.html

[S51] C++：显式类型转换
来源：http://dali.birdmap.top/Article/details/gtmjflwcup.html

static_cast<double>(a) / b
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcetylmkj.html

[S52] C++：const 与 noexcept
来源：http://dali.haohaochexian.top/Article/details/gtbjtopotv.html

int size() const noexcept { return n_; }
来源：http://dali.cqqwz.cn/Article/details/gtyabusejg.html

[S53] C++：移动语义
来源：http://dali.yangfankeji.com/Article/details/gtvwflrteq.html

std::vector<int> w = std::move(v);
来源：http://dali.iojbl.cn/Article/details/gtfsyiamli.html

[S54] C++：异常处理
来源：http://dali.birdmap.top/Article/details/gtjrsuvbbc.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhengqikj.top/Article/details/gtjwdgxjnw.html

[S55] C++：结构化绑定
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrmenjsed.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.yuxming.cn/Article/details/gtfvkawool.html

[S56] C++：optional
来源：http://dali.jinghuilouyu.cn/Article/details/gtzrrnavri.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.sweek.top/Article/details/gtkmemribm.html

[S57] C++：编译期常量
来源：http://dali.shanyushiyangtech.top/Article/details/gtjffbzxus.html

constexpr int N = 10;
来源：http://dali.nanxinkj.top/Article/details/gtvdigddss.html

[S58] C++：命名空间
来源：http://dali.yanxiufei.cn/Article/details/gtgnrzurox.html

namespace ns { int f() { return 1; } }
来源：http://dali.ydzc1.top/Article/details/gtithbnbvg.html

[S59] C++：静态断言
来源：http://dali.daxiang520.top/Article/details/gtxilqefqo.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.andypj.xyz/Article/details/gtkfskylpc.html

[S60] C++：遍历并删除元素
来源：http://dali.yj20258.top/Article/details/gtohatsgbr.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.xinyue.icu/Article/details/gtlebgodri.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtybpwcihe.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.jinqigfzy.top/Article/details/gtmaeebuth.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtemsfgclt.html

[T01] Kotlin：Hello World
来源：http://dali.xinyue.icu/Article/details/gtytyekokr.html

println("Hello")
来源：http://dali.wangdashe.top/Article/details/gtmiolpwfl.html

[T02] Kotlin：变量
来源：http://dali.yongpay.top/Article/details/gtihmhmgpv.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmhdairxl.html

[T03] Kotlin：字符串模板
来源：http://dali.yuanzhike.top/Article/details/gtdozepmkn.html

"值: $b"
来源：http://dali.jqgufenzy.top/Article/details/gtplobjxja.html

[T04] Kotlin：空安全
来源：http://dali.vqdsnc.cn/Article/details/gtfadtcdua.html

val n: String? = null;  n?.length
来源：http://dali.gotoacloud.top/Article/details/gtzmkfcifb.html


<!-- 参考信息 -->