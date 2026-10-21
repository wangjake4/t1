代发 wailian999

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.jinyuanbaomall.cn/Article/details/gtounduaiy.html

[Q90] 生成序号列
来源：http://dali.xziqi.cn/Article/details/gtalkuzxcq.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.hfpthk.cn/Article/details/gtzonfiprb.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtmcgnfqsq.html

R. Bash 专题
来源：http://dali.cheryme.top/Article/details/gtsrwvnlio.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtwkigrutk.html

[R01] shebang 与严格模式
来源：http://dali.xuetiantiany.cn/Article/details/gtjaquwgnc.html

#!/usr/bin/env bash
来源：http://dali.ivvv.top/Article/details/gtoxogwuvq.html

set -euo pipefail
来源：http://dali.cheryme.top/Article/details/gteoutjnkx.html

[R02] 变量赋值与使用
来源：http://dali.9152youxi.cn/Article/details/gtkpmbtkvm.html

name="Tom"; echo "$name"
来源：http://dali.hfpthk.cn/Article/details/gttiumvhji.html

[R03] 只读变量
来源：http://dali.yangfankeji.com/Article/details/gtdefybprx.html

readonly PI=3.14
来源：http://dali.jinqigufen.top/Article/details/gtczygrfyw.html

[R04] 位置参数
来源：http://dali.pycfn.com/Article/details/gtaszunicu.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhoulong.xyz/Article/details/gtoejswqqg.html

[R05] 参数默认值
来源：http://dali.xziqi.cn/Article/details/gtsawogrqh.html

name="${1:-default}"
来源：http://dali.bjfxy.top/Article/details/gtytwzavkj.html

[R06] 判断命令是否存在
来源：http://dali.tanke756.top/Article/details/gtcvcsjhay.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.hongshengwenyu.top/Article/details/gtkfbvebor.html

[R07] if 判断文件
来源：http://dali.ppjwa.cn/Article/details/gtpsxfvncz.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.jinqigufen.top/Article/details/gtohqrgiax.html

[R08] 数值比较
来源：http://dali.kuanghao11.cn/Article/details/gtliklxffv.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.yongpay.top/Article/details/gtszkqmqye.html

[R09] 字符串比较
来源：http://dali.tianlin.xyz/Article/details/gtbhtuigjv.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.yueranfly.top/Article/details/gtjhtqsbdk.html

[R10] 正则匹配
来源：http://dali.xinyue.icu/Article/details/gtqorbqorp.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.yuxming.cn/Article/details/gtugvsbvdi.html

[R11] case 多分支
来源：http://dali.sxryk.cn/Article/details/gtawqkzwmf.html

case "$1" in
来源：http://dali.chenjidiqi.icu/Article/details/gtwojxpdmg.html

start) echo "启动" ;;
来源：http://dali.jlsjyb.cn/Article/details/gtcztmceup.html

stop)  echo "停止" ;;
来源：http://dali.fzhhl.top/Article/details/gttgnrnnzt.html

*)     echo "未知命令" ;;
来源：http://dali.zycfv.cn/Article/details/gtfwhuklrt.html

esac
来源：http://dali.9152youxi.cn/Article/details/gthrygtigb.html

[R12] for 遍历文件
来源：http://dali.guowangkeji.top/Article/details/gtanoigpll.html

for f in *.txt; do echo "$f"; done
来源：http://dali.shangyingyoupin.top/Article/details/gtkrwzkteo.html

[R13] for 计数循环
来源：http://dali.zdqjudy.top/Article/details/gtvfggphej.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.fengsongda.top/Article/details/gtazzliiqm.html

[R14] C 风格 for
来源：http://dali.zdqjudy.top/Article/details/gtzpjsqdlh.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.cashguo.top/Article/details/gtspzqliit.html

[R15] while 逐行读文件
来源：http://dali.mhx1999.top/Article/details/gtdouilduv.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcfbnblxu.html

[R16] until 等待条件
来源：http://dali.iojbl.cn/Article/details/gtvtjjqkcj.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.hywenlv.cn/Article/details/gtescsgzbz.html

[R17] 数组定义与取值
来源：http://dali.yj202588.top/Article/details/gteatdgxzv.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.fzhhl.top/Article/details/gtmipnkltk.html

[R18] 遍历数组
来源：http://dali.jiagoushi.top/Article/details/gttnsxjosi.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.bjfxy.top/Article/details/gtvgcrccmr.html

[R19] 数组长度
来源：http://dali.zhiwuduotai.top/Article/details/gtibsuckgo.html

echo "${#arr[@]}"
来源：http://dali.fzhhl.top/Article/details/gtvjixhcnf.html

[R20] 关联数组（字典）
来源：http://dali.0kj1m.cn/Article/details/gtflbfzksi.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfcuitmuz.html

[R21] 字符串长度
来源：http://dali.svipenyu.cn/Article/details/gtztouylvy.html

echo "${#s}"
来源：http://dali.iojbl.cn/Article/details/gthfpapecs.html

[R22] 截取子串
来源：http://dali.iojbl.cn/Article/details/gttvssqaic.html

echo "${s:0:5}"
来源：http://dali.andypj.xyz/Article/details/gtdwvqijrl.html

[R23] 字符串替换
来源：http://dali.cqqwz.cn/Article/details/gtqevrsrwr.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.sweek.top/Article/details/gtmqimyawy.html

[R24] 大小写转换
来源：http://dali.sweek.top/Article/details/gthqedgqjh.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.jinqigfzy.top/Article/details/gttcwdougo.html

[R25] 去后缀 / 去前缀
来源：http://dali.havefunace.top/Article/details/gtznhltojh.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.ppjwa.cn/Article/details/gtvjpcuhjl.html

[R26] 命令替换
来源：http://dali.gaohongyu789.top/Article/details/gtmnxthbro.html

now=$(date +%F); echo "$now"
来源：http://dali.pycfn.com/Article/details/gteveebbcf.html

[R27] 算术展开
来源：http://dali.yonumen.top/Article/details/gtarljzkwg.html

echo $((1 + 2 * 3))
来源：http://dali.gaohongyu789.top/Article/details/gtvdtmnlgj.html

[R28] 浮点运算
来源：http://dali.yueranfly.top/Article/details/gtbmdvtkwz.html

echo "scale=2; 10/3" | bc
来源：http://dali.jqgfzy.top/Article/details/gthgzxayuo.html

[R29] 定义函数
来源：http://dali.mhx1999.top/Article/details/gtbiwxents.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.andypj.xyz/Article/details/gtjwdqxcpu.html

[R30] 函数返回状态码
来源：http://dali.c1oappe.top/Article/details/gtymnzyhta.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.jyoumei.cn/Article/details/gtjyrtjmld.html

[R31] 局部变量
来源：http://dali.zhoulong.xyz/Article/details/gtunlundfg.html

f() { local x=1; echo "$x"; }
来源：http://dali.sweek.top/Article/details/gtsdplffbn.html

[R32] 参数个数校验
来源：http://dali.ydzc1.top/Article/details/gtxqipwbif.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zdqjudy.top/Article/details/gtrzrvnbic.html

[R33] 捕获错误并提示行号
来源：http://dali.yongpay.top/Article/details/gtklcnmtli.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.gaohongyu789.top/Article/details/gtqzjrgnnq.html

[R34] 退出时清理
来源：http://dali.hnqzz.top/Article/details/gthyzcbggz.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.vqdsnc.cn/Article/details/gtakebajyf.html

[R35] 后台执行并等待
来源：http://dali.xinyue.icu/Article/details/gtksoduwzq.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.cashguo.top/Article/details/gtpipsuujz.html

[R36] 并发执行多个任务
来源：http://dali.zhaomingkeji.xyz/Article/details/gtplvxlfvc.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.chenzaomai.com/Article/details/gtwiuvtxzc.html

[R37] 把输出赋给变量
来源：http://dali.tianlin.xyz/Article/details/gtgrwdmpnu.html

files=$(ls -1)
来源：http://dali.xylfe.cn/Article/details/gtrzvozcot.html

[R38] 管道串联
来源：http://dali.ivvv.top/Article/details/gtbgslmpei.html

cat a.txt | grep -i error | wc -l
来源：http://dali.pengpengdd.cyou/Article/details/gtbzgybcqa.html

[R39] 重定向标准输出与错误
来源：http://dali.chenzaomai.com/Article/details/gteyngpvuz.html

cmd > out.log 2>&1
来源：http://dali.dashuyun.cn/Article/details/gtnlcycgfz.html

[R40] 追加写日志
来源：http://dali.9152youxi.cn/Article/details/gtmdrsrcsc.html

echo "log" >> out.log
来源：http://dali.chenlongwang.top/Article/details/gtkydjhztw.html

[R41] 丢弃输出
来源：http://dali.9152youxi.cn/Article/details/gthfqfithc.html

cmd >/dev/null 2>&1
来源：http://dali.gogol.net.cn/Article/details/gtzptnoxuz.html

[R42] 输入重定向
来源：http://dali.jyoumei.cn/Article/details/gtzkqtdbre.html

wc -l < a.txt
来源：http://dali.cdnleiting.top/Article/details/gtxdbphdzh.html

[R43] 按名字查找文件
来源：http://dali.vqdsnc.cn/Article/details/gtdahpakxk.html

find . -name "*.log" -type f
来源：http://dali.hnxiangtu.top/Article/details/gtnhdptsic.html

[R44] 按修改时间查找
来源：http://dali.meibo888.top/Article/details/gtfubqfwra.html

find . -mtime -7 -type f
来源：http://dali.aibaodan.cn/Article/details/gtwvpzwzre.html

[R45] 批量删除
来源：http://dali.bjfxy.top/Article/details/gtyewshyxj.html

find . -name "*.tmp" -delete
来源：http://dali.jianghu66.top/Article/details/gtzppjxwuz.html

[R46] 递归替换文件内容
来源：http://dali.snrcjt.cn/Article/details/gtsimkrueh.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.ybcxt.top/Article/details/gtdetqyfqv.html

[R47] sed 单行替换
来源：http://dali.316326.xyz/Article/details/gtqzcqgymy.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.ivvv.top/Article/details/gtznfjyztf.html

[R48] awk 取指定列
来源：http://dali.iojbl.cn/Article/details/gtpulfhdtw.html

awk '{print $1, $3}' a.txt
来源：http://dali.fengsongda.top/Article/details/gtifzdqubg.html

[R49] awk 带条件
来源：http://dali.0kj1m.cn/Article/details/gtgvwecdat.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.xylfe.cn/Article/details/gtawfgptax.html

[R50] awk 求和
来源：http://dali.shzxlz.cn/Article/details/gtjswknhhi.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.sxryk.cn/Article/details/gtpobobsyt.html

[R51] 排序去重取前几
来源：http://dali.zycfv.cn/Article/details/gtipzmpxfr.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.jqgufenzy.top/Article/details/gtvtwmqdlf.html

[R52] 统计行数
来源：http://dali.feifeiyinyue.top/Article/details/gthhmyksky.html

wc -l a.txt
来源：http://dali.quarkkingdee.top/Article/details/gtumgpzssy.html

[R53] 查看文件头与实时尾
来源：http://dali.chenlongwang.top/Article/details/gtxovdgsys.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.ehwqpu.com/Article/details/gtxgtlvayh.html

[R54] 比较两个文件
来源：http://dali.birdmap.top/Article/details/gtzudehelh.html

diff a.txt b.txt
来源：http://dali.xziqi.cn/Article/details/gtwshbvfif.html

[R55] 压缩与解压
来源：http://dali.zhixingplan.top/Article/details/gtsadgxhnq.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.yanxiufei.cn/Article/details/gtvnwetgpj.html

[R56] 远程拷贝
来源：http://dali.zhixingplan.top/Article/details/gtohgrkyss.html

scp file user@host:/path/
来源：http://dali.zdqjudy.top/Article/details/gtuicjgiaw.html

[R57] 远程执行命令
来源：http://dali.ybcxt.top/Article/details/gtdjeyxnuj.html

ssh user@host 'uptime'
来源：http://dali.zhiwuduotai.top/Article/details/gticfeytnf.html

[R58] 下载文件
来源：http://dali.yj20258.top/Article/details/gtxsvehxgb.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.kuanghao11.cn/Article/details/gtokqepygf.html

[R59] 发 POST JSON
来源：http://dali.jinyuanbaomall.cn/Article/details/gttmizcwjd.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvrzuxery.html

[R60] 只看 HTTP 状态码
来源：http://dali.guannengcc.top/Article/details/gtbdxtwnrh.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.yonumen.top/Article/details/gtxdpowuny.html

[R61] 磁盘占用
来源：http://dali.xuetiantiany.cn/Article/details/gtybztoqiv.html

df -h;  du -sh *
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxwqwzoim.html

[R62] 找最占空间的文件
来源：http://dali.jiagoushi.top/Article/details/gtvgjpcupc.html

du -ah . | sort -rh | head -10
来源：http://dali.ydzc1.top/Article/details/gtldkncmzf.html

[R63] 内存与进程
来源：http://dali.cashguo.top/Article/details/gtwxhqyrsa.html

free -h;  ps aux | grep nginx
来源：http://dali.jinqigufen.top/Article/details/gteowwaspy.html

[R64] 结束进程
来源：http://dali.fzhhl.top/Article/details/gtsfixnfdr.html

kill -9 $(pgrep -f app.py)
来源：http://dali.jinqigfzy.top/Article/details/gtsuybbrvu.html

[R65] 查看端口占用
来源：http://dali.yongpay.top/Article/details/gtjqnoeysu.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.tianlin.xyz/Article/details/gtkbieuxwp.html

[R66] 定时任务
来源：http://dali.smart0.xyz/Article/details/gteaozgpmy.html

crontab -e;  crontab -l
来源：http://dali.wangdashe.top/Article/details/gtbcqwmgup.html

[R67] 生成随机十六进制串
来源：http://dali.pycfn.com/Article/details/gtovaobbkh.html

openssl rand -hex 16
来源：http://dali.jinqigfzy.top/Article/details/gtylpxjteo.html

[R68] 计算文件校验值
来源：http://dali.gotoacloud.top/Article/details/gtpmwisuzg.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.quarkkingdee.top/Article/details/gtzfyuuhic.html

[R69] 生成随机密码
来源：http://dali.hfpthk.cn/Article/details/gtydmtsnjy.html

head -c 16 /dev/urandom | base64
来源：http://dali.jlsjyb.cn/Article/details/gtfwcpxsej.html

[R70] 时间戳与互转
来源：http://dali.sufxvd.cn/Article/details/gtwbhmjatx.html

date +%s;  date -d @1700000000
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwzguiyda.html

[R71] 日期格式化
来源：http://dali.hammf.cn/Article/details/gtjwaxndcm.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhiwuduotai.top/Article/details/gtvwnvaeji.html

[R72] 等待端口就绪
来源：http://dali.vqdsnc.cn/Article/details/gtwhcqxhpc.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhiwuduotai.top/Article/details/gtkxzjssip.html

[R73] 分割大日志
来源：http://dali.daxiang520.top/Article/details/gtdzggrfsx.html

split -l 1000 big.log part_
来源：http://dali.xziqi.cn/Article/details/gtdnksufwz.html

[R74] 批量重命名
来源：http://dali.bjfxy.top/Article/details/gtjluyzeug.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.hysaishi.cn/Article/details/gtudteqpuw.html

[R75] 导出环境变量
来源：http://dali.hfpthk.cn/Article/details/gtvwpwgwfw.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.jinqigfzy.top/Article/details/gtjovwyljl.html

[R76] 使用临时文件
来源：http://dali.ivvv.top/Article/details/gttpswzoso.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.hnxiangtu.top/Article/details/gtknwrrhft.html

[R77] 读取用户输入
来源：http://dali.redwolf501.top/Article/details/gtcikzxuju.html

read -rp "请输入: " ans
来源：http://dali.dianchejie.cn/Article/details/gtrghizgho.html

[R78] 交互式菜单
来源：http://dali.fzhhl.top/Article/details/gtvpyznpvo.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.cqqwz.cn/Article/details/gtamgrfysh.html

[R79] 解析命令行选项
来源：http://dali.shanyushiyangtech.top/Article/details/gtfufxqtlr.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.wangdashe.top/Article/details/gtoeubweid.html

[R80] 查看脚本执行耗时
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxgtmwgez.html

time ./run.sh
来源：http://dali.hysaishi.cn/Article/details/gtstatmpyg.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtxotasmxz.html

S. C / C++ 专题
来源：http://dali.zhixingplan.top/Article/details/gtagjeaqmh.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtqqdwwpca.html

[S01] C：Hello World
来源：http://dali.aizwys.cn/Article/details/gtrrxmlhpk.html

#include <stdio.h>
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyrudelhu.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.dianchejie.cn/Article/details/gtoxcrgvqq.html

[S02] C：变量与格式化输出
来源：http://dali.pycfn.com/Article/details/gtnyuwmbuv.html

int a = 10; printf("%d\n", a);
来源：http://dali.sweek.top/Article/details/gtupnoljpo.html

[S03] C：读入整数
来源：http://dali.yj20258.top/Article/details/gtxirkogsu.html

int x; scanf("%d", &x);
来源：http://dali.0kj1m.cn/Article/details/gtjuwvihyu.html

[S04] C：字符串复制
来源：http://dali.jyoumei.cn/Article/details/gtwplvqdsr.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.chenlongwang.top/Article/details/gtgzxadfie.html

[S05] C：字符串长度
来源：http://dali.haohaochexian.top/Article/details/gtsvgalhto.html

strlen(s)
来源：http://dali.zycfv.cn/Article/details/gtobeprxka.html

[S06] C：字符串比较
来源：http://dali.chenjidiqi.icu/Article/details/gtwskutjix.html

strcmp(a, b) == 0
来源：http://dali.tianlin.xyz/Article/details/gtzzdekpxi.html

[S07] C：数组遍历求和
来源：http://dali.zycfv.cn/Article/details/gtnbwxlzit.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.andypj.xyz/Article/details/gtbipythgp.html

[S08] C：动态内存分配与释放
来源：http://dali.yj202588.top/Article/details/gthpxoypsl.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.ivvv.top/Article/details/gtatnhxhcz.html

[S09] C：结构体定义与初始化
来源：http://dali.xylfe.cn/Article/details/gtbxagngjm.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.haohaochexian.top/Article/details/gtpjmuwyzk.html

[S10] C：指针与解引用
来源：http://dali.zycfv.cn/Article/details/gtlyyxtmdf.html

int *p = &a;  *p = 5;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlxsyobkh.html

[S11] C：逐行读文件
来源：http://dali.nwbrower.top/Article/details/gteplasrtc.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.redwolf501.top/Article/details/gtjzigkbfq.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.ydzc1.top/Article/details/gthysgysfz.html

fclose(f);
来源：http://dali.yj202588.top/Article/details/gthvhfjjbl.html

[S12] C：写文件
来源：http://dali.9152youxi.cn/Article/details/gtorstvodi.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.jinghuilouyu.cn/Article/details/gtscvfwfxf.html

[S13] C：宏定义
来源：http://dali.xuanzx.com/Article/details/gtgyzqdeov.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.kuanghao11.cn/Article/details/gtharbfrfu.html

[S14] C：枚举
来源：http://dali.havefunace.top/Article/details/gtmdlwgyfv.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.kuanghao11.cn/Article/details/gttvfgqnti.html

[S15] C：类型转换
来源：http://dali.cqqwz.cn/Article/details/gtwsrrkiok.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gttrduoqtt.html

[S16] C：位操作置位
来源：http://dali.dianchejie.cn/Article/details/gtboxugtpo.html

x |= (1 << 3);
来源：http://dali.hysaishi.cn/Article/details/gtfejflcvn.html

[S17] C：安全拼接字符串
来源：http://dali.hfpthk.cn/Article/details/gtonvyxtzy.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.jyoumei.cn/Article/details/gtqcnjhrbk.html

[S18] C：命令行参数
来源：http://dali.wangdashe.top/Article/details/gtixikvqiy.html

int main(int argc, char **argv)
来源：http://dali.aibaodan.cn/Article/details/gtztsypvbw.html

[S19] C：快速排序
来源：http://dali.yongpay.top/Article/details/gtmgxpctdd.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhengqikj.top/Article/details/gtemdxmdzt.html

[S20] C：二分查找
来源：http://dali.hammf.cn/Article/details/gtktuhmslq.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.vqdsnc.cn/Article/details/gtyauhzckp.html

[S21] C：字符类别判断
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjywwrsge.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.tianlin.xyz/Article/details/gtyxtplpzw.html

[S22] C：字符串转数字
来源：http://dali.quarkkingdee.top/Article/details/gtozrfxsav.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.gotoacloud.top/Article/details/gtlcmdhikx.html

[S23] C：随机数
来源：http://dali.tian-w.cn/Article/details/gtfiblgeka.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.aizwys.cn/Article/details/gtgkvboflr.html

[S24] C：获取本地时间
来源：http://dali.zycfv.cn/Article/details/gthmzhabbc.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.pengpengdd.cyou/Article/details/gturputnce.html

[S25] C：内存拷贝
来源：http://dali.xuanzx.com/Article/details/gthmtrvfmp.html

memcpy(dst, src, n);
来源：http://dali.zhixingplan.top/Article/details/gtwzxdgimy.html

[S26] C：内存清零
来源：http://dali.fengsongda.top/Article/details/gtleotlcvp.html

memset(a, 0, sizeof a);
来源：http://dali.gaohongyu789.top/Article/details/gtfqwffbrg.html

[S27] C：定义常量
来源：http://dali.cheryme.top/Article/details/gtfznvnpge.html

const double PI = 3.14159;
来源：http://dali.meibo888.top/Article/details/gtborvzzor.html

[S28] C：静态变量
来源：http://dali.dianchejie.cn/Article/details/gtegvzyxkf.html

static int counter = 0;
来源：http://dali.guowangkeji.top/Article/details/gttbzumbvj.html

[S29] C：变参函数
来源：http://dali.yj20258888.top/Article/details/gtcptrkvgu.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.hfpthk.cn/Article/details/gtukbfukyz.html

[S30] C：头文件保护
来源：http://dali.316326.xyz/Article/details/gtkxbndkjv.html

#ifndef X_H
来源：http://dali.yuxming.cn/Article/details/gtnotirlct.html

#define X_H
来源：http://dali.0kj1m.cn/Article/details/gtqoxkotkz.html

#endif
来源：http://dali.dashuyun.cn/Article/details/gteabohsdt.html

[S31] C++：Hello World
来源：http://dali.vqdsnc.cn/Article/details/gtbvbpkoqz.html

#include <iostream>
来源：http://dali.0kj1m.cn/Article/details/gtngxftquk.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.xuetiantiany.cn/Article/details/gtcnwylgiu.html

[S32] C++：字符串
来源：http://dali.sweek.top/Article/details/gtdkznlwcb.html

std::string s = "hi";  s += "!";
来源：http://dali.pycfn.com/Article/details/gtitnqhpmg.html

[S33] C++：vector 增删
来源：http://dali.shangyingyoupin.top/Article/details/gtutdtisep.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.jyoumei.cn/Article/details/gtaltkfxil.html

[S34] C++：遍历 vector
来源：http://dali.tanke756.top/Article/details/gtsozxyypc.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.gogol.net.cn/Article/details/gtbmveqbux.html

[S35] C++：map
来源：http://dali.zhixingplan.top/Article/details/gtdgjwneks.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gtvctoarli.html

[S36] C++：unordered_map
来源：http://dali.hnxiangtu.top/Article/details/gtpipgelwm.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.chenzaomai.com/Article/details/gtgdvrrxno.html

[S37] C++：set
来源：http://dali.svipenyu.cn/Article/details/gtsqwtjxia.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.smart0.xyz/Article/details/gtrinwlynt.html

[S38] C++：排序
来源：http://dali.nanxinkj.top/Article/details/gtihihwvxr.html

std::sort(v.begin(), v.end());
来源：http://dali.hfpthk.cn/Article/details/gtowgiybbc.html

[S39] C++：自定义比较器排序
来源：http://dali.zhoulong.xyz/Article/details/gtdfuyyqvp.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.shuidangran.top/Article/details/gtqrfmkvrx.html

[S40] C++：查找元素
来源：http://dali.birdmap.top/Article/details/gtdeszfyhw.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.pycfn.com/Article/details/gttmbycnsx.html

[S41] C++：类与构造函数
来源：http://dali.fengsongda.top/Article/details/gtvipajccj.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.xuanzx.com/Article/details/gtcfeotfmq.html

[S42] C++：继承与虚函数
来源：http://dali.snrcjt.cn/Article/details/gtpcbiiqdq.html

class B : public Base { public: void f() override {} };
来源：http://dali.0kj1m.cn/Article/details/gthiwifmcq.html

[S43] C++：智能指针
来源：http://dali.xuetiantiany.cn/Article/details/gtoopkleiz.html

auto p = std::make_unique<int>(5);
来源：http://dali.hywenlv.cn/Article/details/gthqywqpbz.html

[S44] C++：引用传参
来源：http://dali.jqgufenzy.top/Article/details/gtfjnkvjra.html

void inc(int &x) { ++x; }
来源：http://dali.haohaochexian.top/Article/details/gtkcvrwchv.html

[S45] C++：lambda
来源：http://dali.zhengqikj.top/Article/details/gtadaqhstd.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.jinqigufen.top/Article/details/gtydwaylvm.html

[S46] C++：函数模板
来源：http://dali.yanxiufei.cn/Article/details/gtyhartqse.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.guowangkeji.top/Article/details/gtivuahzhn.html

[S47] C++：结构化绑定遍历
来源：http://dali.shanyushiyangtech.top/Article/details/gtekzjftrm.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.daxiang520.top/Article/details/gtihbrhxfd.html

[S48] C++：逐行读文件
来源：http://dali.hywenlv.cn/Article/details/gtgicwiaai.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.wangdashe.top/Article/details/gtfzkqptpe.html

while (std::getline(in, line)) { }
来源：http://dali.gaohongyu789.top/Article/details/gtsapqbwae.html

[S49] C++：写文件
来源：http://dali.yanxiufei.cn/Article/details/gtsveuowos.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.quarkkingdee.top/Article/details/gthilklpjs.html

[S50] C++：格式化数字
来源：http://dali.chenjidiqi.icu/Article/details/gtsxdpyoph.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.mhx1999.top/Article/details/gtlxorzcvo.html

[S51] C++：显式类型转换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttvpntbrt.html

static_cast<double>(a) / b
来源：http://dali.tianlin.xyz/Article/details/gtxhqjworz.html

[S52] C++：const 与 noexcept
来源：http://dali.hywenlv.cn/Article/details/gtxixiexzb.html

int size() const noexcept { return n_; }
来源：http://dali.xuanzx.com/Article/details/gtlkhrddnp.html

[S53] C++：移动语义
来源：http://dali.dianchejie.cn/Article/details/gtgzriiwoy.html

std::vector<int> w = std::move(v);
来源：http://dali.iojbl.cn/Article/details/gtpbmypbby.html

[S54] C++：异常处理
来源：http://dali.pycfn.com/Article/details/gtrgsbkdzc.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.xylfe.cn/Article/details/gtfvrpwlwa.html

[S55] C++：结构化绑定
来源：http://dali.ydzc1.top/Article/details/gtzwulrhvh.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.yongpay.top/Article/details/gtigrkxdtj.html

[S56] C++：optional
来源：http://dali.yj20258.top/Article/details/gtoxuletze.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.cqqwz.cn/Article/details/gthjnbiloy.html

[S57] C++：编译期常量
来源：http://dali.jqgufenzy.top/Article/details/gtmuxabpcn.html

constexpr int N = 10;
来源：http://dali.jlsjyb.cn/Article/details/gtaixpqeok.html

[S58] C++：命名空间
来源：http://dali.0kj1m.cn/Article/details/gtidgmvbud.html

namespace ns { int f() { return 1; } }
来源：http://dali.yangfankeji.com/Article/details/gtddodkijj.html

[S59] C++：静态断言
来源：http://dali.wangshuangyany.cn/Article/details/gttmntpzzi.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.pycfn.com/Article/details/gthzjiieqs.html

[S60] C++：遍历并删除元素
来源：http://dali.jiagoushi.top/Article/details/gtqcjjihvz.html


<!-- 参考信息 -->