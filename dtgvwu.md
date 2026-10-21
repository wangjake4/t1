代发 wailian999

readonly PI=3.14
来源：http://dali.jinghuilouyu.cn/Article/details/gtcwtllxhj.html

[R04] 位置参数
来源：http://dali.quarkkingdee.top/Article/details/gtpsmrsdjy.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.pycfn.com/Article/details/gtnqanplav.html

[R05] 参数默认值
来源：http://dali.zdqjudy.top/Article/details/gtypcopcgx.html

name="${1:-default}"
来源：http://dali.gogol.net.cn/Article/details/gtgqhidncc.html

[R06] 判断命令是否存在
来源：http://dali.quarkkingdee.top/Article/details/gtmzggbloj.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.fengsongda.top/Article/details/gtxyznlani.html

[R07] if 判断文件
来源：http://dali.hammf.cn/Article/details/gtcnbasdzx.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.pengpengdd.cyou/Article/details/gtnofsabny.html

[R08] 数值比较
来源：http://dali.jqgufenzy.top/Article/details/gtjpilvixk.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.tanke756.top/Article/details/gttzwiwmsq.html

[R09] 字符串比较
来源：http://dali.shuidangran.top/Article/details/gtnfomnnqf.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.316326.xyz/Article/details/gtfssddihi.html

[R10] 正则匹配
来源：http://dali.pengpengdd.cyou/Article/details/gtdlycxhhq.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.haohaochexian.top/Article/details/gttslblayx.html

[R11] case 多分支
来源：http://dali.0kj1m.cn/Article/details/gtnryiebpz.html

case "$1" in
来源：http://dali.smart0.xyz/Article/details/gtdujrgoai.html

start) echo "启动" ;;
来源：http://dali.yj20258.top/Article/details/gtkwizanwa.html

stop)  echo "停止" ;;
来源：http://dali.meibo888.top/Article/details/gtjlvqifkg.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gtaefqronm.html

esac
来源：http://dali.cashguo.top/Article/details/gtzlsxxqpq.html

[R12] for 遍历文件
来源：http://dali.0kj1m.cn/Article/details/gtpmbfvgxf.html

for f in *.txt; do echo "$f"; done
来源：http://dali.hnxiangtu.top/Article/details/gtszvwnsjz.html

[R13] for 计数循环
来源：http://dali.jianghu66.top/Article/details/gtqlqsaxgf.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.nanxuanxn.top/Article/details/gtnlzfoock.html

[R14] C 风格 for
来源：http://dali.xuanzx.com/Article/details/gtuajubmog.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.yvedp.cn/Article/details/gtpfulefhy.html

[R15] while 逐行读文件
来源：http://dali.sufxvd.cn/Article/details/gtiyvkjzki.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.fengsongda.top/Article/details/gthzxvhzqo.html

[R16] until 等待条件
来源：http://dali.c1oappe.top/Article/details/gtwytdupsv.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.shzxlz.cn/Article/details/gtivxogfax.html

[R17] 数组定义与取值
来源：http://dali.9152youxi.cn/Article/details/gtqubxpkid.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.nanxinkj.top/Article/details/gtmpgeuzva.html

[R18] 遍历数组
来源：http://dali.sweek.top/Article/details/gtiwnxwpps.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.9152youxi.cn/Article/details/gtvuskdjir.html

[R19] 数组长度
来源：http://dali.zycfv.cn/Article/details/gtsezmfxxw.html

echo "${#arr[@]}"
来源：http://dali.chenlongwang.top/Article/details/gtydsvmbxb.html

[R20] 关联数组（字典）
来源：http://dali.yuanzhike.top/Article/details/gtvdwinfat.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.hywenlv.cn/Article/details/gtiybsdsrp.html

[R21] 字符串长度
来源：http://dali.snrcjt.cn/Article/details/gteonwxkxm.html

echo "${#s}"
来源：http://dali.shzxlz.cn/Article/details/gtyiuksuwu.html

[R22] 截取子串
来源：http://dali.smart0.xyz/Article/details/gtlhnlzqbi.html

echo "${s:0:5}"
来源：http://dali.zhongyouzk.top/Article/details/gtietnmakc.html

[R23] 字符串替换
来源：http://dali.hongshengwenyu.top/Article/details/gtckioanoj.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.wangshuangyany.cn/Article/details/gtdwtxsbuh.html

[R24] 大小写转换
来源：http://dali.xuanzx.com/Article/details/gtofaxitns.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.chenlongwang.top/Article/details/gtidnrddze.html

[R25] 去后缀 / 去前缀
来源：http://dali.nanxuanxn.top/Article/details/gtwwwfmntx.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.yongpay.top/Article/details/gtpbufhvtt.html

[R26] 命令替换
来源：http://dali.pengpengdd.cyou/Article/details/gtvgotbika.html

now=$(date +%F); echo "$now"
来源：http://dali.shzxlz.cn/Article/details/gtrvftdhhn.html

[R27] 算术展开
来源：http://dali.zhixingplan.top/Article/details/gtvsoviqbt.html

echo $((1 + 2 * 3))
来源：http://dali.cucudq.cn/Article/details/gtzpqnoeuu.html

[R28] 浮点运算
来源：http://dali.feifeiyinyue.top/Article/details/gtlwiqilnl.html

echo "scale=2; 10/3" | bc
来源：http://dali.ywan-chungtsiang.top/Article/details/gtljwpvrwo.html

[R29] 定义函数
来源：http://dali.meibo888.top/Article/details/gtamkhtpmq.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.shanyushiyangtech.top/Article/details/gtqvdcuiri.html

[R30] 函数返回状态码
来源：http://dali.jinqigufen.top/Article/details/gtndpjtasq.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.nwbrower.top/Article/details/gthoahnhpj.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gtuyqxkfhc.html

f() { local x=1; echo "$x"; }
来源：http://dali.fzhhl.top/Article/details/gteyynjzuu.html

[R32] 参数个数校验
来源：http://dali.cdnleiting.top/Article/details/gtbbrpwavk.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhengqikj.top/Article/details/gtsdecuigw.html

[R33] 捕获错误并提示行号
来源：http://dali.pengpengdd.cyou/Article/details/gtgznpcapf.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.9152youxi.cn/Article/details/gtepvrdiho.html

[R34] 退出时清理
来源：http://dali.gaohongyu789.top/Article/details/gtuuksetbq.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhongyouzk.top/Article/details/gtyszbfexn.html

[R35] 后台执行并等待
来源：http://dali.hnxiangtu.top/Article/details/gtejftbbyw.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.jinqigfzy.top/Article/details/gtclymulua.html

[R36] 并发执行多个任务
来源：http://dali.nwbrower.top/Article/details/gtjapbsqft.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.yanxiufei.cn/Article/details/gtqzfldfwj.html

[R37] 把输出赋给变量
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkgobdthh.html

files=$(ls -1)
来源：http://dali.smart0.xyz/Article/details/gtatjzjoii.html

[R38] 管道串联
来源：http://dali.tianlin.xyz/Article/details/gtxaeplklh.html

cat a.txt | grep -i error | wc -l
来源：http://dali.birdmap.top/Article/details/gtvibkqoiq.html

[R39] 重定向标准输出与错误
来源：http://dali.guowangkeji.top/Article/details/gthbebkxem.html

cmd > out.log 2>&1
来源：http://dali.0kj1m.cn/Article/details/gtywgkpkvd.html

[R40] 追加写日志
来源：http://dali.yuxming.cn/Article/details/gtrilhxlto.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gtencqfeny.html

[R41] 丢弃输出
来源：http://dali.havefunace.top/Article/details/gtyzurgnan.html

cmd >/dev/null 2>&1
来源：http://dali.zhixingplan.top/Article/details/gtggeoditg.html

[R42] 输入重定向
来源：http://dali.zhoulong.xyz/Article/details/gtyfdcwsco.html

wc -l < a.txt
来源：http://dali.cashguo.top/Article/details/gtfbyxzbin.html

[R43] 按名字查找文件
来源：http://dali.ppjwa.cn/Article/details/gtjedinnmd.html

find . -name "*.log" -type f
来源：http://dali.ybcxt.top/Article/details/gturdztggv.html

[R44] 按修改时间查找
来源：http://dali.316326.xyz/Article/details/gtjgfebeyo.html

find . -mtime -7 -type f
来源：http://dali.0kj1m.cn/Article/details/gtpqxdhnyy.html

[R45] 批量删除
来源：http://dali.jyoumei.cn/Article/details/gtepjewcix.html

find . -name "*.tmp" -delete
来源：http://dali.hywenlv.cn/Article/details/gtrpoqugpr.html

[R46] 递归替换文件内容
来源：http://dali.yj20258888.top/Article/details/gtjqdsjxsx.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.dianchejie.cn/Article/details/gtrytklbza.html

[R47] sed 单行替换
来源：http://dali.jlsjyb.cn/Article/details/gtjqwcutek.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.cqqwz.cn/Article/details/gtqjzktzvs.html

[R48] awk 取指定列
来源：http://dali.zhengqikj.top/Article/details/gtfabdahpr.html

awk '{print $1, $3}' a.txt
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuadspnuw.html

[R49] awk 带条件
来源：http://dali.tian-w.cn/Article/details/gtqfxhldgs.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.jiagoushi.top/Article/details/gttdmbumbl.html

[R50] awk 求和
来源：http://dali.hammf.cn/Article/details/gtbmabjqat.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhoulong.xyz/Article/details/gtixzwjotq.html

[R51] 排序去重取前几
来源：http://dali.yangfankeji.com/Article/details/gtivutyxri.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhoulong.xyz/Article/details/gtoaxfoykw.html

[R52] 统计行数
来源：http://dali.hywenlv.cn/Article/details/gtakdzkrgh.html

wc -l a.txt
来源：http://dali.gogol.net.cn/Article/details/gtaouztirx.html

[R53] 查看文件头与实时尾
来源：http://dali.jinqigfzy.top/Article/details/gtwgoulwiy.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.pengpengdd.cyou/Article/details/gtxcgvtirw.html

[R54] 比较两个文件
来源：http://dali.andypj.xyz/Article/details/gtlesvbqhz.html

diff a.txt b.txt
来源：http://dali.daria6918.cn/Article/details/gtliijhvig.html

[R55] 压缩与解压
来源：http://dali.sweek.top/Article/details/gtuxhlaqjh.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.hnxiangtu.top/Article/details/gtwegfugpu.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gtnbnznqid.html

scp file user@host:/path/
来源：http://dali.yuanzhike.top/Article/details/gtqctutore.html

[R57] 远程执行命令
来源：http://dali.shangyingyoupin.top/Article/details/gtimrcpwzo.html

ssh user@host 'uptime'
来源：http://dali.dianchejie.cn/Article/details/gtuyxjbrwl.html

[R58] 下载文件
来源：http://dali.feifeiyinyue.top/Article/details/gtxkzejsrf.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.bjfxy.top/Article/details/gtaxelvjny.html

[R59] 发 POST JSON
来源：http://dali.guannengcc.top/Article/details/gtgeqhmztg.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.ybcxt.top/Article/details/gtiysdxvxr.html

[R60] 只看 HTTP 状态码
来源：http://dali.xziqi.cn/Article/details/gtcvmqdqnc.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.ehwqpu.com/Article/details/gtolvlxfvx.html

[R61] 磁盘占用
来源：http://dali.daria6918.cn/Article/details/gtpmmgyaps.html

df -h;  du -sh *
来源：http://dali.snrcjt.cn/Article/details/gtultonmrd.html

[R62] 找最占空间的文件
来源：http://dali.daxiang520.top/Article/details/gtslxbueda.html

du -ah . | sort -rh | head -10
来源：http://dali.yonumen.top/Article/details/gtngcsqtpq.html

[R63] 内存与进程
来源：http://dali.gaohongyu789.top/Article/details/gtjfxawekb.html

free -h;  ps aux | grep nginx
来源：http://dali.316326.xyz/Article/details/gtmnjwyubv.html

[R64] 结束进程
来源：http://dali.fzhhl.top/Article/details/gthiuczmsh.html

kill -9 $(pgrep -f app.py)
来源：http://dali.yongpay.top/Article/details/gtqrownsxr.html

[R65] 查看端口占用
来源：http://dali.xylfe.cn/Article/details/gteacckrel.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.nanxuanxn.top/Article/details/gthhthwwqa.html

[R66] 定时任务
来源：http://dali.fzhhl.top/Article/details/gtutznkndl.html

crontab -e;  crontab -l
来源：http://dali.sysykeji.top/Article/details/gtvhcnqxvf.html

[R67] 生成随机十六进制串
来源：http://dali.nanxuanxn.top/Article/details/gtqlrqovnw.html

openssl rand -hex 16
来源：http://dali.jinqigfzy.top/Article/details/gtgxmkgoss.html

[R68] 计算文件校验值
来源：http://dali.cqqwz.cn/Article/details/gtxfifwhvr.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zdqjudy.top/Article/details/gthrbuwxcf.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gtjgibsvkv.html

head -c 16 /dev/urandom | base64
来源：http://dali.xuetiantiany.cn/Article/details/gtiahutsnv.html

[R70] 时间戳与互转
来源：http://dali.dianchejie.cn/Article/details/gtujvngxsm.html

date +%s;  date -d @1700000000
来源：http://dali.snrcjt.cn/Article/details/gtmgiapzap.html

[R71] 日期格式化
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpyhkeakb.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.cdnleiting.top/Article/details/gtldjvvjzb.html

[R72] 等待端口就绪
来源：http://dali.hnqzz.top/Article/details/gtbtogydyy.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.vqdsnc.cn/Article/details/gtwdzgtvqv.html

[R73] 分割大日志
来源：http://dali.nanxuanxn.top/Article/details/gtchjrnpcx.html

split -l 1000 big.log part_
来源：http://dali.jlsjyb.cn/Article/details/gtfpjlkhxv.html

[R74] 批量重命名
来源：http://dali.chenzaomai.com/Article/details/gtvnkvxakk.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.c1oappe.top/Article/details/gtipybfnwg.html

[R75] 导出环境变量
来源：http://dali.yj20258888.top/Article/details/gtfxjovvsh.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyvsadsqn.html

[R76] 使用临时文件
来源：http://dali.cheryme.top/Article/details/gtuatyfvdv.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.redwolf501.top/Article/details/gtgizqeese.html

[R77] 读取用户输入
来源：http://dali.mhx1999.top/Article/details/gtczqmpkok.html

read -rp "请输入: " ans
来源：http://dali.hysaishi.cn/Article/details/gternucepp.html

[R78] 交互式菜单
来源：http://dali.yueranfly.top/Article/details/gtsdkwovum.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.cdnleiting.top/Article/details/gtghzrudob.html

[R79] 解析命令行选项
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpztsmmmq.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.nanxinkj.top/Article/details/gtasvginvr.html

[R80] 查看脚本执行耗时
来源：http://dali.0kj1m.cn/Article/details/gtutcixxpn.html

time ./run.sh
来源：http://dali.jinqigfzy.top/Article/details/gtmmswrnmg.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtkshsvldp.html

S. C / C++ 专题
来源：http://dali.aibaodan.cn/Article/details/gtvpxmgmqi.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtbawnbcwr.html

[S01] C：Hello World
来源：http://dali.jinghuilouyu.cn/Article/details/gtglxyumcv.html

#include <stdio.h>
来源：http://dali.meibo888.top/Article/details/gtonjvntvd.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.xziqi.cn/Article/details/gtdbbgxrpe.html

[S02] C：变量与格式化输出
来源：http://dali.hongshengwenyu.top/Article/details/gtozvbxomo.html

int a = 10; printf("%d\n", a);
来源：http://dali.jqgufenzy.top/Article/details/gtpshtjdix.html

[S03] C：读入整数
来源：http://dali.zhiwuduotai.top/Article/details/gtwupkjjkx.html

int x; scanf("%d", &x);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvjfmqcyl.html

[S04] C：字符串复制
来源：http://dali.jqgfzy.top/Article/details/gtlzutlabi.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.mhx1999.top/Article/details/gtuubgklrc.html

[S05] C：字符串长度
来源：http://dali.yvedp.cn/Article/details/gtuwvnivuv.html

strlen(s)
来源：http://dali.hywenlv.cn/Article/details/gttwgodxdz.html

[S06] C：字符串比较
来源：http://dali.redwolf501.top/Article/details/gtlptyesyd.html

strcmp(a, b) == 0
来源：http://dali.daria6918.cn/Article/details/gtohplhidz.html

[S07] C：数组遍历求和
来源：http://dali.guowangkeji.top/Article/details/gtefqlxalr.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.chenjidiqi.icu/Article/details/gtzotihvye.html

[S08] C：动态内存分配与释放
来源：http://dali.yonumen.top/Article/details/gtqlxonqio.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.shzxlz.cn/Article/details/gtfuwjrawi.html

[S09] C：结构体定义与初始化
来源：http://dali.gogol.net.cn/Article/details/gtatspyzvd.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.jinqigfzy.top/Article/details/gtkkprhwdh.html

[S10] C：指针与解引用
来源：http://dali.svipenyu.cn/Article/details/gtmonaujmr.html

int *p = &a;  *p = 5;
来源：http://dali.mhx1999.top/Article/details/gtpcwadtyz.html

[S11] C：逐行读文件
来源：http://dali.hysaishi.cn/Article/details/gttfzahzhf.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.dashuyun.cn/Article/details/gtwmmuzxgz.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.316326.xyz/Article/details/gtqsyyrqhq.html

fclose(f);
来源：http://dali.shangyingyoupin.top/Article/details/gtaiknjqgg.html

[S12] C：写文件
来源：http://dali.wangdashe.top/Article/details/gtxyvksvnp.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.xuanzx.com/Article/details/gtqdgtfmps.html

[S13] C：宏定义
来源：http://dali.316326.xyz/Article/details/gtzhpidsgx.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zycfv.cn/Article/details/gtyfckrnfm.html

[S14] C：枚举
来源：http://dali.cashguo.top/Article/details/gtytsyomxt.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhongyouzk.top/Article/details/gtwnvrldmy.html

[S15] C：类型转换
来源：http://dali.redwolf501.top/Article/details/gtfizxbvty.html

(double) a / b
来源：http://dali.9152youxi.cn/Article/details/gtztzmrnbs.html

[S16] C：位操作置位
来源：http://dali.pycfn.com/Article/details/gtxjyrednn.html

x |= (1 << 3);
来源：http://dali.hnqzz.top/Article/details/gtqxrakcym.html

[S17] C：安全拼接字符串
来源：http://dali.cheryme.top/Article/details/gtuykniiph.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.shanyushiyangtech.top/Article/details/gtoidohlnc.html

[S18] C：命令行参数
来源：http://dali.tanke756.top/Article/details/gtzovdwcpb.html

int main(int argc, char **argv)
来源：http://dali.fzhhl.top/Article/details/gtwuiafkre.html

[S19] C：快速排序
来源：http://dali.yuanzhike.top/Article/details/gtowifwaqs.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.sxryk.cn/Article/details/gttceyvawf.html

[S20] C：二分查找
来源：http://dali.fzhhl.top/Article/details/gtkahfbevr.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.feifeiyinyue.top/Article/details/gtwzckyfzz.html

[S21] C：字符类别判断
来源：http://dali.birdmap.top/Article/details/gtvdcfnpsh.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnjxpnnai.html

[S22] C：字符串转数字
来源：http://dali.316326.xyz/Article/details/gtznkwckcz.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.tianlin.xyz/Article/details/gtsganyfqc.html

[S23] C：随机数
来源：http://dali.hywenlv.cn/Article/details/gtxnjwouev.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.daria6918.cn/Article/details/gtmfbxeuxy.html

[S24] C：获取本地时间
来源：http://dali.jianghu66.top/Article/details/gtvywzphel.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.hammf.cn/Article/details/gtmwyphhhh.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gtedtyjkdh.html

memcpy(dst, src, n);
来源：http://dali.hammf.cn/Article/details/gtmjygbwpt.html

[S26] C：内存清零
来源：http://dali.wangdashe.top/Article/details/gtyujxbssr.html

memset(a, 0, sizeof a);
来源：http://dali.yangfankeji.com/Article/details/gtlyeryssm.html

[S27] C：定义常量
来源：http://dali.nanxinkj.top/Article/details/gtwcltokab.html

const double PI = 3.14159;
来源：http://dali.xylfe.cn/Article/details/gtvwdyhbct.html

[S28] C：静态变量
来源：http://dali.cucudq.cn/Article/details/gtnjsiponn.html

static int counter = 0;
来源：http://dali.jinghuilouyu.cn/Article/details/gtkeodnwep.html

[S29] C：变参函数
来源：http://dali.xziqi.cn/Article/details/gtjflpirng.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.yueranfly.top/Article/details/gtvrsihgwx.html

[S30] C：头文件保护
来源：http://dali.hfpthk.cn/Article/details/gtnhuwdtyk.html

#ifndef X_H
来源：http://dali.jinqigufen.top/Article/details/gtsibcovcc.html

#define X_H
来源：http://dali.guowangkeji.top/Article/details/gtffalhtoi.html

#endif
来源：http://dali.ydzc1.top/Article/details/gtmuzqcstu.html

[S31] C++：Hello World
来源：http://dali.daria6918.cn/Article/details/gthhoainow.html

#include <iostream>
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthsndwxdq.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.dianchejie.cn/Article/details/gtkclgyevo.html

[S32] C++：字符串
来源：http://dali.gzhubu.top/Article/details/gtfvwoqond.html

std::string s = "hi";  s += "!";
来源：http://dali.ivvv.top/Article/details/gtrcnabpyh.html

[S33] C++：vector 增删
来源：http://dali.cheryme.top/Article/details/gtcnnepbrk.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.shzxlz.cn/Article/details/gthwguxupo.html

[S34] C++：遍历 vector
来源：http://dali.xinyue.icu/Article/details/gtwpuyjwes.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.redwolf501.top/Article/details/gtomtsbiqa.html

[S35] C++：map
来源：http://dali.jinqigufen.top/Article/details/gtjxybulvj.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jqgfzy.top/Article/details/gtlclgogeo.html

[S36] C++：unordered_map
来源：http://dali.yuxming.cn/Article/details/gtangrtntf.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.ivvv.top/Article/details/gtzeycseua.html

[S37] C++：set
来源：http://dali.zhaomingkeji.xyz/Article/details/gttmobkvqa.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.hnqzz.top/Article/details/gtnsptckge.html

[S38] C++：排序
来源：http://dali.chenlongwang.top/Article/details/gtktueczbx.html

std::sort(v.begin(), v.end());
来源：http://dali.zhengqikj.top/Article/details/gtdnnjnwiw.html

[S39] C++：自定义比较器排序
来源：http://dali.zhoulong.xyz/Article/details/gtdwdgcjwu.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.xuanzx.com/Article/details/gtqdyomcvp.html

[S40] C++：查找元素
来源：http://dali.yueranfly.top/Article/details/gtpkpogwlc.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.daria6918.cn/Article/details/gtzxgqbbfr.html

[S41] C++：类与构造函数
来源：http://dali.yueranfly.top/Article/details/gtwkiexnnb.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.yj20258888.top/Article/details/gtbbwddakc.html

[S42] C++：继承与虚函数
来源：http://dali.mhx1999.top/Article/details/gtpmzanknq.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gtovqiylwv.html

[S43] C++：智能指针
来源：http://dali.meibo888.top/Article/details/gtxidtklxr.html

auto p = std::make_unique<int>(5);
来源：http://dali.jinyuanbaomall.cn/Article/details/gttekxwrih.html

[S44] C++：引用传参
来源：http://dali.snrcjt.cn/Article/details/gtpopvxarl.html

void inc(int &x) { ++x; }
来源：http://dali.iojbl.cn/Article/details/gtvmqpxuka.html

[S45] C++：lambda
来源：http://dali.meibo888.top/Article/details/gtadnlqxrk.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.316326.xyz/Article/details/gtyieexssg.html

[S46] C++：函数模板
来源：http://dali.zdqjudy.top/Article/details/gtysmzvmjy.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.yueranfly.top/Article/details/gtsinvhyti.html

[S47] C++：结构化绑定遍历
来源：http://dali.jinghuilouyu.cn/Article/details/gtgfgkntze.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.hammf.cn/Article/details/gthmgchabr.html

[S48] C++：逐行读文件
来源：http://dali.birdmap.top/Article/details/gtxzvydank.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.xinyue.icu/Article/details/gtfzvenpyl.html

while (std::getline(in, line)) { }
来源：http://dali.zhoulong.xyz/Article/details/gtteezogtr.html

[S49] C++：写文件
来源：http://dali.yj20258.top/Article/details/gtfroycjcs.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.birdmap.top/Article/details/gtlpgujysh.html

[S50] C++：格式化数字
来源：http://dali.jinghuilouyu.cn/Article/details/gtobnregdi.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.ppjwa.cn/Article/details/gtiruftamz.html

[S51] C++：显式类型转换
来源：http://dali.nwbrower.top/Article/details/gtolsviicq.html

static_cast<double>(a) / b
来源：http://dali.zhixingplan.top/Article/details/gtzjjwxkcn.html

[S52] C++：const 与 noexcept
来源：http://dali.mhx1999.top/Article/details/gtcycimiwb.html

int size() const noexcept { return n_; }
来源：http://dali.cqqwz.cn/Article/details/gtqicejcdv.html

[S53] C++：移动语义
来源：http://dali.feifeiyinyue.top/Article/details/gtlhympbyu.html

std::vector<int> w = std::move(v);
来源：http://dali.hnqzz.top/Article/details/gtszmdylew.html

[S54] C++：异常处理
来源：http://dali.xinyue.icu/Article/details/gtnipkfmos.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.fengsongda.top/Article/details/gtjxfdbpwx.html

[S55] C++：结构化绑定
来源：http://dali.9152youxi.cn/Article/details/gtjwansnhg.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.yuxming.cn/Article/details/gteeolqjye.html

[S56] C++：optional
来源：http://dali.gotoacloud.top/Article/details/gtjvpcmjmd.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.hfpthk.cn/Article/details/gtyaxwhwse.html

[S57] C++：编译期常量
来源：http://dali.mhx1999.top/Article/details/gtbjezykmf.html

constexpr int N = 10;
来源：http://dali.jianghu66.top/Article/details/gtyqipnqri.html

[S58] C++：命名空间
来源：http://dali.snrcjt.cn/Article/details/gtprzxedft.html

namespace ns { int f() { return 1; } }
来源：http://dali.zdqjudy.top/Article/details/gtbeornzjy.html

[S59] C++：静态断言
来源：http://dali.hysaishi.cn/Article/details/gtcjgporao.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.pycfn.com/Article/details/gtanshltyk.html

[S60] C++：遍历并删除元素
来源：http://dali.sxryk.cn/Article/details/gtcxxgnhqa.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.yuxming.cn/Article/details/gtdmetikdt.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzzegjoic.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxqmzhhcy.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtyuapvjwa.html

[T01] Kotlin：Hello World
来源：http://dali.zdqjudy.top/Article/details/gtmaiomoxx.html

println("Hello")
来源：http://dali.hywenlv.cn/Article/details/gtzrrjntbq.html

[T02] Kotlin：变量
来源：http://dali.zdqjudy.top/Article/details/gtgjqwwfhz.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.smart0.xyz/Article/details/gtyiqvnzpi.html

[T03] Kotlin：字符串模板
来源：http://dali.316326.xyz/Article/details/gtdcalbptl.html

"值: $b"
来源：http://dali.chenjidiqi.icu/Article/details/gtrnqidwvk.html

[T04] Kotlin：空安全
来源：http://dali.yvedp.cn/Article/details/gtpwhuwzug.html

val n: String? = null;  n?.length
来源：http://dali.sysykeji.top/Article/details/gtxjgeukam.html


<!-- 参考信息 -->