代发 wailian999

name="${1:-default}"
来源：http://dali.yueranfly.top/Article/details/gtnoxtbjdj.html

[R06] 判断命令是否存在
来源：http://dali.9152youxi.cn/Article/details/gtcnlpnngq.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.hysaishi.cn/Article/details/gteehwndgx.html

[R07] if 判断文件
来源：http://dali.yuxming.cn/Article/details/gthxtvvqfa.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.hywenlv.cn/Article/details/gtftnmoudx.html

[R08] 数值比较
来源：http://dali.yj20258888.top/Article/details/gtypecqgoi.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.tianlin.xyz/Article/details/gtrdqbnwsk.html

[R09] 字符串比较
来源：http://dali.haohaochexian.top/Article/details/gtphqzjibb.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.jlsjyb.cn/Article/details/gthgxlamxz.html

[R10] 正则匹配
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjosqyiqo.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.quarkkingdee.top/Article/details/gtddoacjkv.html

[R11] case 多分支
来源：http://dali.0kj1m.cn/Article/details/gtevosugwq.html

case "$1" in
来源：http://dali.zhongyouzk.top/Article/details/gtswwmdwtt.html

start) echo "启动" ;;
来源：http://dali.hfpthk.cn/Article/details/gtskhxoqtq.html

stop)  echo "停止" ;;
来源：http://dali.xinyue.icu/Article/details/gtjufcjnyf.html

*)     echo "未知命令" ;;
来源：http://dali.zdqjudy.top/Article/details/gtmzulwmxj.html

esac
来源：http://dali.nanxuanxn.top/Article/details/gtfwaqabqi.html

[R12] for 遍历文件
来源：http://dali.zhiwuduotai.top/Article/details/gtlrevloqv.html

for f in *.txt; do echo "$f"; done
来源：http://dali.sxryk.cn/Article/details/gtkoqsjsrm.html

[R13] for 计数循环
来源：http://dali.birdmap.top/Article/details/gtutixohyt.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.wangdashe.top/Article/details/gtvrcdhgxu.html

[R14] C 风格 for
来源：http://dali.cdnleiting.top/Article/details/gtyjlmmnxs.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.sysykeji.top/Article/details/gthnzzfevy.html

[R15] while 逐行读文件
来源：http://dali.jlsjyb.cn/Article/details/gtvxjltone.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.guowangkeji.top/Article/details/gtpzucsjhs.html

[R16] until 等待条件
来源：http://dali.tian-w.cn/Article/details/gtmhjeftuc.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.xuanzx.com/Article/details/gtfslslmnr.html

[R17] 数组定义与取值
来源：http://dali.hnqzz.top/Article/details/gttmmominl.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.hnqzz.top/Article/details/gtaosnkgrd.html

[R18] 遍历数组
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpmqmqlra.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.wangdashe.top/Article/details/gtfjgeirtt.html

[R19] 数组长度
来源：http://dali.xylfe.cn/Article/details/gtrmjeijqh.html

echo "${#arr[@]}"
来源：http://dali.jinqigfzy.top/Article/details/gtxbodfkvw.html

[R20] 关联数组（字典）
来源：http://dali.cheryme.top/Article/details/gtezxmshcv.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.svipenyu.cn/Article/details/gthofcndlx.html

[R21] 字符串长度
来源：http://dali.svipenyu.cn/Article/details/gtonxvdunl.html

echo "${#s}"
来源：http://dali.wangdashe.top/Article/details/gtiavjepbq.html

[R22] 截取子串
来源：http://dali.chenjidiqi.icu/Article/details/gtjaypcmez.html

echo "${s:0:5}"
来源：http://dali.ppjwa.cn/Article/details/gtofehmhda.html

[R23] 字符串替换
来源：http://dali.hywenlv.cn/Article/details/gtkudeubtr.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.jiagoushi.top/Article/details/gtjwswfitn.html

[R24] 大小写转换
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaptfywnh.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.havefunace.top/Article/details/gtjectktyp.html

[R25] 去后缀 / 去前缀
来源：http://dali.xylfe.cn/Article/details/gtlkosbqhh.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.cashguo.top/Article/details/gtcrqlmxni.html

[R26] 命令替换
来源：http://dali.sysykeji.top/Article/details/gtcfzyjbsg.html

now=$(date +%F); echo "$now"
来源：http://dali.jiagoushi.top/Article/details/gtkyxpblbm.html

[R27] 算术展开
来源：http://dali.dashuyun.cn/Article/details/gtgvxlsvdw.html

echo $((1 + 2 * 3))
来源：http://dali.zdqjudy.top/Article/details/gteqdgtnhc.html

[R28] 浮点运算
来源：http://dali.xuanzx.com/Article/details/gtmdsuwafs.html

echo "scale=2; 10/3" | bc
来源：http://dali.hywenlv.cn/Article/details/gttotozhxh.html

[R29] 定义函数
来源：http://dali.hammf.cn/Article/details/gtfneboina.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.shuidangran.top/Article/details/gtomcdhqfe.html

[R30] 函数返回状态码
来源：http://dali.svipenyu.cn/Article/details/gtlpvovifn.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.ehwqpu.com/Article/details/gtiicuxqsc.html

[R31] 局部变量
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjtugokci.html

f() { local x=1; echo "$x"; }
来源：http://dali.hysaishi.cn/Article/details/gtmpgqfpus.html

[R32] 参数个数校验
来源：http://dali.hnqzz.top/Article/details/gtezmyltkc.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.tanke756.top/Article/details/gtvhqajawn.html

[R33] 捕获错误并提示行号
来源：http://dali.zhiwuduotai.top/Article/details/gtegqzjuvr.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.daxiang520.top/Article/details/gtxwymsdeo.html

[R34] 退出时清理
来源：http://dali.zycfv.cn/Article/details/gtvmmvxqkl.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.snrcjt.cn/Article/details/gtmiphwzds.html

[R35] 后台执行并等待
来源：http://dali.sysykeji.top/Article/details/gtfqggfjsv.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.daxiang520.top/Article/details/gtittczapc.html

[R36] 并发执行多个任务
来源：http://dali.tanke756.top/Article/details/gtfqzssfmo.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.vqdsnc.cn/Article/details/gtmojnmzjc.html

[R37] 把输出赋给变量
来源：http://dali.cucudq.cn/Article/details/gtjrbisbus.html

files=$(ls -1)
来源：http://dali.xinyue.icu/Article/details/gtrafgbiak.html

[R38] 管道串联
来源：http://dali.smart0.xyz/Article/details/gtckucjxvn.html

cat a.txt | grep -i error | wc -l
来源：http://dali.hnxiangtu.top/Article/details/gtjkpgpjve.html

[R39] 重定向标准输出与错误
来源：http://dali.chenlongwang.top/Article/details/gtppaglndk.html

cmd > out.log 2>&1
来源：http://dali.hnxiangtu.top/Article/details/gtwemxnxup.html

[R40] 追加写日志
来源：http://dali.shangyingyoupin.top/Article/details/gthyqlmlaz.html

echo "log" >> out.log
来源：http://dali.nanxinkj.top/Article/details/gtrjmgwpij.html

[R41] 丢弃输出
来源：http://dali.guowangkeji.top/Article/details/gtlrwnrjwj.html

cmd >/dev/null 2>&1
来源：http://dali.ivvv.top/Article/details/gtjvvygxnz.html

[R42] 输入重定向
来源：http://dali.yj20258888.top/Article/details/gtpdpnzbtv.html

wc -l < a.txt
来源：http://dali.aibaodan.cn/Article/details/gtpxoiughj.html

[R43] 按名字查找文件
来源：http://dali.feifeiyinyue.top/Article/details/gtbhemjdos.html

find . -name "*.log" -type f
来源：http://dali.jiagoushi.top/Article/details/gtseipkwyu.html

[R44] 按修改时间查找
来源：http://dali.gzhubu.top/Article/details/gtogizadbn.html

find . -mtime -7 -type f
来源：http://dali.xuanzx.com/Article/details/gtpwmhfocs.html

[R45] 批量删除
来源：http://dali.wangshuangyany.cn/Article/details/gthjvukkjk.html

find . -name "*.tmp" -delete
来源：http://dali.zycfv.cn/Article/details/gtooabrbgb.html

[R46] 递归替换文件内容
来源：http://dali.tianlin.xyz/Article/details/gtgryttxrl.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.fzhhl.top/Article/details/gtbmqnedmu.html

[R47] sed 单行替换
来源：http://dali.smart0.xyz/Article/details/gtxudbssxn.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.havefunace.top/Article/details/gtsgwqpjmc.html

[R48] awk 取指定列
来源：http://dali.ppjwa.cn/Article/details/gtjgicncjt.html

awk '{print $1, $3}' a.txt
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttgcinsmj.html

[R49] awk 带条件
来源：http://dali.havefunace.top/Article/details/gtarcttytb.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.xinyue.icu/Article/details/gtxxkqcarc.html

[R50] awk 求和
来源：http://dali.zhaomingkeji.xyz/Article/details/gttfkxckid.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhongyouzk.top/Article/details/gtiuxjfokn.html

[R51] 排序去重取前几
来源：http://dali.sxryk.cn/Article/details/gtailpylja.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.yuanzhike.top/Article/details/gtoemsdwbt.html

[R52] 统计行数
来源：http://dali.pengpengdd.cyou/Article/details/gtcmgxrzeb.html

wc -l a.txt
来源：http://dali.mhx1999.top/Article/details/gtaqonupnk.html

[R53] 查看文件头与实时尾
来源：http://dali.zhengqikj.top/Article/details/gtvctrrylt.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.svipenyu.cn/Article/details/gtgulrkulc.html

[R54] 比较两个文件
来源：http://dali.tanke756.top/Article/details/gtdjpngbpk.html

diff a.txt b.txt
来源：http://dali.fzhhl.top/Article/details/gtwshikljc.html

[R55] 压缩与解压
来源：http://dali.yangfankeji.com/Article/details/gtnpmdsxjo.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.tian-w.cn/Article/details/gtlcfodben.html

[R56] 远程拷贝
来源：http://dali.mhx1999.top/Article/details/gtdheccplo.html

scp file user@host:/path/
来源：http://dali.jinqigufen.top/Article/details/gtbsekivee.html

[R57] 远程执行命令
来源：http://dali.yangfankeji.com/Article/details/gtgcmcknyu.html

ssh user@host 'uptime'
来源：http://dali.birdmap.top/Article/details/gticmhwoav.html

[R58] 下载文件
来源：http://dali.yuxming.cn/Article/details/gtbnitkvum.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.yj202588.top/Article/details/gtzmhumpue.html

[R59] 发 POST JSON
来源：http://dali.cdnleiting.top/Article/details/gtbxiaxuzs.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.pycfn.com/Article/details/gtyjvaogkb.html

[R60] 只看 HTTP 状态码
来源：http://dali.yj202588.top/Article/details/gtfacbluux.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.dianchejie.cn/Article/details/gtehlynssr.html

[R61] 磁盘占用
来源：http://dali.ydzc1.top/Article/details/gtjyuwplwo.html

df -h;  du -sh *
来源：http://dali.wangdashe.top/Article/details/gtlhxbdqgz.html

[R62] 找最占空间的文件
来源：http://dali.cdnleiting.top/Article/details/gthqwlsqep.html

du -ah . | sort -rh | head -10
来源：http://dali.dashuyun.cn/Article/details/gtilfwebcw.html

[R63] 内存与进程
来源：http://dali.xinyue.icu/Article/details/gtuifdduzl.html

free -h;  ps aux | grep nginx
来源：http://dali.zhixingplan.top/Article/details/gtpkcaslzj.html

[R64] 结束进程
来源：http://dali.havefunace.top/Article/details/gtagmbhmmg.html

kill -9 $(pgrep -f app.py)
来源：http://dali.cdnleiting.top/Article/details/gtunmibwnx.html

[R65] 查看端口占用
来源：http://dali.jlsjyb.cn/Article/details/gtwqayvsqg.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhixingplan.top/Article/details/gtohzezkxb.html

[R66] 定时任务
来源：http://dali.aibaodan.cn/Article/details/gtupmsruke.html

crontab -e;  crontab -l
来源：http://dali.fzhhl.top/Article/details/gthewkmtvu.html

[R67] 生成随机十六进制串
来源：http://dali.snrcjt.cn/Article/details/gtsdrlcnbr.html

openssl rand -hex 16
来源：http://dali.xziqi.cn/Article/details/gtgdkypfkr.html

[R68] 计算文件校验值
来源：http://dali.cucudq.cn/Article/details/gtmddvdkul.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.shangyingyoupin.top/Article/details/gtglhjxmcf.html

[R69] 生成随机密码
来源：http://dali.yj20258888.top/Article/details/gtbcplvsyk.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhixingplan.top/Article/details/gtotknlrbw.html

[R70] 时间戳与互转
来源：http://dali.zycfv.cn/Article/details/gtsbkmvgex.html

date +%s;  date -d @1700000000
来源：http://dali.shanyushiyangtech.top/Article/details/gtyuqszdst.html

[R71] 日期格式化
来源：http://dali.hongshengwenyu.top/Article/details/gtopzbxmbp.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.sweek.top/Article/details/gtyqfjtssi.html

[R72] 等待端口就绪
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdfvguntj.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.dianchejie.cn/Article/details/gthetrrfcg.html

[R73] 分割大日志
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmmqjoepk.html

split -l 1000 big.log part_
来源：http://dali.jinqigfzy.top/Article/details/gtvgbcsekr.html

[R74] 批量重命名
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfwkmjcta.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.c1oappe.top/Article/details/gtracgpupn.html

[R75] 导出环境变量
来源：http://dali.chenzaomai.com/Article/details/gtulagzlbv.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiletzxny.html

[R76] 使用临时文件
来源：http://dali.xuetiantiany.cn/Article/details/gtdxlnqbsn.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.hammf.cn/Article/details/gtrpdmhwgd.html

[R77] 读取用户输入
来源：http://dali.hysaishi.cn/Article/details/gtblarsgsd.html

read -rp "请输入: " ans
来源：http://dali.yanxiufei.cn/Article/details/gtpnsulqck.html

[R78] 交互式菜单
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkrsakpzx.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.hysaishi.cn/Article/details/gtkumdhhhi.html

[R79] 解析命令行选项
来源：http://dali.wangdashe.top/Article/details/gtxxkdopmo.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.vqdsnc.cn/Article/details/gtxujeoiey.html

[R80] 查看脚本执行耗时
来源：http://dali.hnxiangtu.top/Article/details/gtnstfuzre.html

time ./run.sh
来源：http://dali.hfpthk.cn/Article/details/gtmwikxcyl.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtqsenawwd.html

S. C / C++ 专题
来源：http://dali.shanyushiyangtech.top/Article/details/gtcrdxpbcq.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtxmlnkqww.html

[S01] C：Hello World
来源：http://dali.wangshuangyany.cn/Article/details/gtnnpgcbdh.html

#include <stdio.h>
来源：http://dali.yvedp.cn/Article/details/gtqrrfcgvm.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.redwolf501.top/Article/details/gtiqokamvp.html

[S02] C：变量与格式化输出
来源：http://dali.zycfv.cn/Article/details/gtnweffclx.html

int a = 10; printf("%d\n", a);
来源：http://dali.chenjidiqi.icu/Article/details/gtbdzbfrgg.html

[S03] C：读入整数
来源：http://dali.guannengcc.top/Article/details/gttqjwwdkd.html

int x; scanf("%d", &x);
来源：http://dali.fzhhl.top/Article/details/gtrrvekysj.html

[S04] C：字符串复制
来源：http://dali.havefunace.top/Article/details/gtvqzgbqrc.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.wangshuangyany.cn/Article/details/gtcfdibsxz.html

[S05] C：字符串长度
来源：http://dali.zhixingplan.top/Article/details/gtrgtpyytr.html

strlen(s)
来源：http://dali.pycfn.com/Article/details/gtiovuezqf.html

[S06] C：字符串比较
来源：http://dali.ivvv.top/Article/details/gtcrcdmzfi.html

strcmp(a, b) == 0
来源：http://dali.xziqi.cn/Article/details/gtiiakvqve.html

[S07] C：数组遍历求和
来源：http://dali.hnqzz.top/Article/details/gtuwdrcscf.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.ybcxt.top/Article/details/gthvhborhg.html

[S08] C：动态内存分配与释放
来源：http://dali.hnxiangtu.top/Article/details/gtxiyfdcdn.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.yj20258.top/Article/details/gttqqfhswr.html

[S09] C：结构体定义与初始化
来源：http://dali.daria6918.cn/Article/details/gtqszxmwdu.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.hammf.cn/Article/details/gtajxdwryf.html

[S10] C：指针与解引用
来源：http://dali.hysaishi.cn/Article/details/gthcvjuwwi.html

int *p = &a;  *p = 5;
来源：http://dali.zhoulong.xyz/Article/details/gtkgvwtvvs.html

[S11] C：逐行读文件
来源：http://dali.yanxiufei.cn/Article/details/gtygwnksym.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.guannengcc.top/Article/details/gtcdfgqzzd.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.feifeiyinyue.top/Article/details/gtceobttwa.html

fclose(f);
来源：http://dali.hnqzz.top/Article/details/gttjjpjsgw.html

[S12] C：写文件
来源：http://dali.yuxming.cn/Article/details/gtizkclkly.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.yj202588.top/Article/details/gtirbptljm.html

[S13] C：宏定义
来源：http://dali.haohaochexian.top/Article/details/gtlzhuqbqh.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.jinqigufen.top/Article/details/gtogmznsoz.html

[S14] C：枚举
来源：http://dali.dashuyun.cn/Article/details/gtyljfhnkq.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.jqgfzy.top/Article/details/gtpumgqhqn.html

[S15] C：类型转换
来源：http://dali.dianchejie.cn/Article/details/gtsvmuvyuo.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gtoqyvvkxn.html

[S16] C：位操作置位
来源：http://dali.jinqigfzy.top/Article/details/gtenyhhzxh.html

x |= (1 << 3);
来源：http://dali.xuanzx.com/Article/details/gtvgltqdxd.html

[S17] C：安全拼接字符串
来源：http://dali.gzhubu.top/Article/details/gtmgdclgno.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcavzqzcj.html

[S18] C：命令行参数
来源：http://dali.hnxiangtu.top/Article/details/gtsfuindik.html

int main(int argc, char **argv)
来源：http://dali.hnxiangtu.top/Article/details/gtzjutxnra.html

[S19] C：快速排序
来源：http://dali.wangshuangyany.cn/Article/details/gtqhydovtj.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.c1oappe.top/Article/details/gtcbfrbrze.html

[S20] C：二分查找
来源：http://dali.zycfv.cn/Article/details/gtdvwednjy.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.jiagoushi.top/Article/details/gtnloafvgb.html

[S21] C：字符类别判断
来源：http://dali.dianchejie.cn/Article/details/gtrxeaueyz.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.sysykeji.top/Article/details/gtjlfzmumk.html

[S22] C：字符串转数字
来源：http://dali.chenjidiqi.icu/Article/details/gtvjcflkhk.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.9152youxi.cn/Article/details/gtaybgkqnk.html

[S23] C：随机数
来源：http://dali.cucudq.cn/Article/details/gtkeprjerx.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.cheryme.top/Article/details/gtxemhuasr.html

[S24] C：获取本地时间
来源：http://dali.xylfe.cn/Article/details/gtaxkjftux.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.yueranfly.top/Article/details/gtrlmsxwop.html

[S25] C：内存拷贝
来源：http://dali.guannengcc.top/Article/details/gtfzjcxzfx.html

memcpy(dst, src, n);
来源：http://dali.birdmap.top/Article/details/gtvnydnenx.html

[S26] C：内存清零
来源：http://dali.jqgufenzy.top/Article/details/gtczxmcvcd.html

memset(a, 0, sizeof a);
来源：http://dali.cdnleiting.top/Article/details/gtlpnvtakl.html

[S27] C：定义常量
来源：http://dali.mhx1999.top/Article/details/gtnxhxoerx.html

const double PI = 3.14159;
来源：http://dali.jinyuanbaomall.cn/Article/details/gttrijakyh.html

[S28] C：静态变量
来源：http://dali.c1oappe.top/Article/details/gtopufxgti.html

static int counter = 0;
来源：http://dali.hongshengwenyu.top/Article/details/gtlydpdpts.html

[S29] C：变参函数
来源：http://dali.dashuyun.cn/Article/details/gtdflonwad.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.wangdashe.top/Article/details/gtcuenhdpk.html

[S30] C：头文件保护
来源：http://dali.wangshuangyany.cn/Article/details/gthzrjeppn.html

#ifndef X_H
来源：http://dali.chenzaomai.com/Article/details/gtwezjtwzb.html

#define X_H
来源：http://dali.cucudq.cn/Article/details/gtcizjpmrv.html

#endif
来源：http://dali.jianghu66.top/Article/details/gtguqgrwcp.html

[S31] C++：Hello World
来源：http://dali.guannengcc.top/Article/details/gtmouetrdf.html

#include <iostream>
来源：http://dali.hfpthk.cn/Article/details/gtcxtwnyst.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gtyvhefdjm.html

[S32] C++：字符串
来源：http://dali.cashguo.top/Article/details/gtoretlicm.html

std::string s = "hi";  s += "!";
来源：http://dali.redwolf501.top/Article/details/gtneseymel.html

[S33] C++：vector 增删
来源：http://dali.hfpthk.cn/Article/details/gtsliqgtgt.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.quarkkingdee.top/Article/details/gtbfhdpede.html

[S34] C++：遍历 vector
来源：http://dali.hongshengwenyu.top/Article/details/gtkngkdizl.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.jinqigufen.top/Article/details/gtdlglvzpm.html

[S35] C++：map
来源：http://dali.pengpengdd.cyou/Article/details/gtofxuqqxn.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.haohaochexian.top/Article/details/gtyuevyzuf.html

[S36] C++：unordered_map
来源：http://dali.haohaochexian.top/Article/details/gtzbergcqz.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.snrcjt.cn/Article/details/gtprcompcg.html

[S37] C++：set
来源：http://dali.hfpthk.cn/Article/details/gtwrbjsiod.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.yj202588.top/Article/details/gtgunkfxbt.html

[S38] C++：排序
来源：http://dali.shzxlz.cn/Article/details/gtubqbuwpe.html

std::sort(v.begin(), v.end());
来源：http://dali.bjfxy.top/Article/details/gtaiidgfjm.html

[S39] C++：自定义比较器排序
来源：http://dali.cashguo.top/Article/details/gtmpjhaxej.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.xylfe.cn/Article/details/gtqwnsrjbi.html

[S40] C++：查找元素
来源：http://dali.redwolf501.top/Article/details/gtcmkmdckm.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.yangfankeji.com/Article/details/gtcdxnyyyk.html

[S41] C++：类与构造函数
来源：http://dali.cdnleiting.top/Article/details/gtfxwqcupo.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.tianlin.xyz/Article/details/gteomlqnro.html

[S42] C++：继承与虚函数
来源：http://dali.tanke756.top/Article/details/gtxvajzeey.html

class B : public Base { public: void f() override {} };
来源：http://dali.pycfn.com/Article/details/gtnmwkxcxz.html

[S43] C++：智能指针
来源：http://dali.sweek.top/Article/details/gtsojkkamo.html

auto p = std::make_unique<int>(5);
来源：http://dali.daria6918.cn/Article/details/gtsvzfjnjq.html

[S44] C++：引用传参
来源：http://dali.havefunace.top/Article/details/gtifmqgpet.html

void inc(int &x) { ++x; }
来源：http://dali.9152youxi.cn/Article/details/gtdwatzxzp.html

[S45] C++：lambda
来源：http://dali.pycfn.com/Article/details/gtbiipwkpz.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.jiagoushi.top/Article/details/gtqtffwvas.html

[S46] C++：函数模板
来源：http://dali.0kj1m.cn/Article/details/gtthehvlac.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.quarkkingdee.top/Article/details/gtlkmkopnf.html

[S47] C++：结构化绑定遍历
来源：http://dali.fzhhl.top/Article/details/gtdkklefdo.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.nwbrower.top/Article/details/gthqdjuebp.html

[S48] C++：逐行读文件
来源：http://dali.nanxuanxn.top/Article/details/gttdczhdhk.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.ppjwa.cn/Article/details/gtojdxenuq.html

while (std::getline(in, line)) { }
来源：http://dali.yj20258888.top/Article/details/gtmttjqydx.html

[S49] C++：写文件
来源：http://dali.jqgufenzy.top/Article/details/gtzztbzftx.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhixingplan.top/Article/details/gtkiqrfliy.html

[S50] C++：格式化数字
来源：http://dali.xylfe.cn/Article/details/gtnzxkewdt.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.vqdsnc.cn/Article/details/gttslkvvwq.html

[S51] C++：显式类型转换
来源：http://dali.jqgufenzy.top/Article/details/gtbsalyxvj.html

static_cast<double>(a) / b
来源：http://dali.316326.xyz/Article/details/gtktgehswf.html

[S52] C++：const 与 noexcept
来源：http://dali.gogol.net.cn/Article/details/gtpgzywbee.html

int size() const noexcept { return n_; }
来源：http://dali.tanke756.top/Article/details/gtglybipcr.html

[S53] C++：移动语义
来源：http://dali.kuanghao11.cn/Article/details/gtouvmpuis.html

std::vector<int> w = std::move(v);
来源：http://dali.shzxlz.cn/Article/details/gtqcwychhc.html

[S54] C++：异常处理
来源：http://dali.shangyingyoupin.top/Article/details/gtpsnovfll.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.cashguo.top/Article/details/gtghgrmrpz.html

[S55] C++：结构化绑定
来源：http://dali.vqdsnc.cn/Article/details/gtmfmapogb.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.gzhubu.top/Article/details/gtydwgzepg.html

[S56] C++：optional
来源：http://dali.cashguo.top/Article/details/gtfxvrlypc.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.hywenlv.cn/Article/details/gtabddrdkb.html

[S57] C++：编译期常量
来源：http://dali.cqqwz.cn/Article/details/gtuhghjjjb.html

constexpr int N = 10;
来源：http://dali.jinqigfzy.top/Article/details/gthcewguku.html

[S58] C++：命名空间
来源：http://dali.yangfankeji.com/Article/details/gtxsgztuuw.html

namespace ns { int f() { return 1; } }
来源：http://dali.hammf.cn/Article/details/gtngttokgp.html

[S59] C++：静态断言
来源：http://dali.yvedp.cn/Article/details/gtrzvirvef.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.ydzc1.top/Article/details/gtqpkvlrut.html

[S60] C++：遍历并删除元素
来源：http://dali.wangshuangyany.cn/Article/details/gtvqdigyzy.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.dashuyun.cn/Article/details/gttuqqmwjo.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtxlekmecz.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.xinyue.icu/Article/details/gtwjoxiszg.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtuveihzco.html

[T01] Kotlin：Hello World
来源：http://dali.havefunace.top/Article/details/gtkxhoybha.html

println("Hello")
来源：http://dali.xylfe.cn/Article/details/gtpiwqqlnr.html

[T02] Kotlin：变量
来源：http://dali.nanxinkj.top/Article/details/gtapboznpt.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhixingplan.top/Article/details/gtfoslmrjl.html

[T03] Kotlin：字符串模板
来源：http://dali.bjfxy.top/Article/details/gtkoftljnu.html

"值: $b"
来源：http://dali.cashguo.top/Article/details/gtgdiajjtt.html

[T04] Kotlin：空安全
来源：http://dali.shzxlz.cn/Article/details/gtxflkjekv.html

val n: String? = null;  n?.length
来源：http://dali.cdnleiting.top/Article/details/gtjqlhdxsr.html

[T05] Kotlin：when 表达式
来源：http://dali.xylfe.cn/Article/details/gtgzlulxxc.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.sweek.top/Article/details/gtcexmqmqh.html

[T06] Kotlin：集合映射
来源：http://dali.meibo888.top/Article/details/gtyjxavqye.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.sweek.top/Article/details/gtppgxvxyv.html


<!-- 参考信息 -->