代发 wailian999

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.jinqigufen.top/Article/details/gtrtmajzjk.html

[Q90] 生成序号列
来源：http://dali.tian-w.cn/Article/details/gtliiuidrs.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.guowangkeji.top/Article/details/gtdohwpgfc.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtkyrbodip.html

R. Bash 专题
来源：http://dali.snrcjt.cn/Article/details/gtkpmzrrwx.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtztfrewmp.html

[R01] shebang 与严格模式
来源：http://dali.yuxming.cn/Article/details/gtfamfifck.html

#!/usr/bin/env bash
来源：http://dali.xuanzx.com/Article/details/gtrihfcxvi.html

set -euo pipefail
来源：http://dali.9152youxi.cn/Article/details/gtxbohulvr.html

[R02] 变量赋值与使用
来源：http://dali.yuanzhike.top/Article/details/gtcfshwvoc.html

name="Tom"; echo "$name"
来源：http://dali.dashuyun.cn/Article/details/gtqvpyragi.html

[R03] 只读变量
来源：http://dali.shzxlz.cn/Article/details/gttxkbloow.html

readonly PI=3.14
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwruvzouc.html

[R04] 位置参数
来源：http://dali.zycfv.cn/Article/details/gtymveuysx.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.yvedp.cn/Article/details/gtoygpggrw.html

[R05] 参数默认值
来源：http://dali.smart0.xyz/Article/details/gtzhaxsblw.html

name="${1:-default}"
来源：http://dali.cashguo.top/Article/details/gtekzuwaas.html

[R06] 判断命令是否存在
来源：http://dali.tian-w.cn/Article/details/gtrmruclgq.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.yanxiufei.cn/Article/details/gtrsqkywqz.html

[R07] if 判断文件
来源：http://dali.xziqi.cn/Article/details/gtlsbhvnwy.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.jyoumei.cn/Article/details/gtzepllcof.html

[R08] 数值比较
来源：http://dali.zhoulong.xyz/Article/details/gtgdxpypqq.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.yj202588.top/Article/details/gtfeosluxw.html

[R09] 字符串比较
来源：http://dali.vqdsnc.cn/Article/details/gtrnmqwfoh.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.xuetiantiany.cn/Article/details/gtpnoesmvc.html

[R10] 正则匹配
来源：http://dali.shanyushiyangtech.top/Article/details/gtvorhfiny.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzdjdszhh.html

[R11] case 多分支
来源：http://dali.yuanzhike.top/Article/details/gtwgbbrwca.html

case "$1" in
来源：http://dali.ybcxt.top/Article/details/gttxgznumd.html

start) echo "启动" ;;
来源：http://dali.sweek.top/Article/details/gtqltfonel.html

stop)  echo "停止" ;;
来源：http://dali.nwbrower.top/Article/details/gtxhtvkrnr.html

*)     echo "未知命令" ;;
来源：http://dali.jinqigufen.top/Article/details/gtyfcjzhkw.html

esac
来源：http://dali.guowangkeji.top/Article/details/gttwehnmzw.html

[R12] for 遍历文件
来源：http://dali.cqqwz.cn/Article/details/gtxnedjnhf.html

for f in *.txt; do echo "$f"; done
来源：http://dali.quarkkingdee.top/Article/details/gtgovivwyh.html

[R13] for 计数循环
来源：http://dali.guannengcc.top/Article/details/gtjdapqipm.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.yanxiufei.cn/Article/details/gtozagjwak.html

[R14] C 风格 for
来源：http://dali.xuetiantiany.cn/Article/details/gtoeinskuf.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.haohaochexian.top/Article/details/gtyhuawipd.html

[R15] while 逐行读文件
来源：http://dali.jyoumei.cn/Article/details/gtcsnvolfe.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zdqjudy.top/Article/details/gtiqeecyae.html

[R16] until 等待条件
来源：http://dali.meibo888.top/Article/details/gtoqtgswte.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.ydzc1.top/Article/details/gtknvgexnq.html

[R17] 数组定义与取值
来源：http://dali.316326.xyz/Article/details/gtumqqblqw.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.tian-w.cn/Article/details/gtzadaqszp.html

[R18] 遍历数组
来源：http://dali.shanyushiyangkeji.top/Article/details/gthruxnkuv.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.mhx1999.top/Article/details/gttnaaaquq.html

[R19] 数组长度
来源：http://dali.mhx1999.top/Article/details/gtequkulaw.html

echo "${#arr[@]}"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnbpuphjl.html

[R20] 关联数组（字典）
来源：http://dali.yj202588.top/Article/details/gtphwtybmz.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.daxiang520.top/Article/details/gtcqqywyia.html

[R21] 字符串长度
来源：http://dali.dashuyun.cn/Article/details/gtpuslhxuf.html

echo "${#s}"
来源：http://dali.birdmap.top/Article/details/gtbromkqyv.html

[R22] 截取子串
来源：http://dali.sysykeji.top/Article/details/gtklbjcrig.html

echo "${s:0:5}"
来源：http://dali.yj20258.top/Article/details/gtcggmnyyg.html

[R23] 字符串替换
来源：http://dali.jqgufenzy.top/Article/details/gtuhagrijc.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.cqqwz.cn/Article/details/gterxhlqbd.html

[R24] 大小写转换
来源：http://dali.yonumen.top/Article/details/gtzekuftla.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.hywenlv.cn/Article/details/gtpiwaebfs.html

[R25] 去后缀 / 去前缀
来源：http://dali.sufxvd.cn/Article/details/gtcwaqomil.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.smart0.xyz/Article/details/gtegiqdoiu.html

[R26] 命令替换
来源：http://dali.yj20258.top/Article/details/gtxobkmylh.html

now=$(date +%F); echo "$now"
来源：http://dali.jianghu66.top/Article/details/gtmssofsce.html

[R27] 算术展开
来源：http://dali.guowangkeji.top/Article/details/gtwrebatas.html

echo $((1 + 2 * 3))
来源：http://dali.sweek.top/Article/details/gtywuwnhha.html

[R28] 浮点运算
来源：http://dali.hfpthk.cn/Article/details/gtghcelllz.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhiwuduotai.top/Article/details/gtjxzspvzz.html

[R29] 定义函数
来源：http://dali.cheryme.top/Article/details/gtazbualgj.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.aizwys.cn/Article/details/gtwepiiyds.html

[R30] 函数返回状态码
来源：http://dali.hysaishi.cn/Article/details/gtliwhtjkm.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.c1oappe.top/Article/details/gtvaeemgmz.html

[R31] 局部变量
来源：http://dali.jyoumei.cn/Article/details/gtrbdtmsgy.html

f() { local x=1; echo "$x"; }
来源：http://dali.wangshuangyany.cn/Article/details/gtracilinj.html

[R32] 参数个数校验
来源：http://dali.snrcjt.cn/Article/details/gtdfwensnu.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.ppjwa.cn/Article/details/gtwxbhymks.html

[R33] 捕获错误并提示行号
来源：http://dali.zhiwuduotai.top/Article/details/gthmobtpgg.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.mhx1999.top/Article/details/gtdgfkvsqe.html

[R34] 退出时清理
来源：http://dali.sxryk.cn/Article/details/gtsuwubopp.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.jqgufenzy.top/Article/details/gtmbntpjqs.html

[R35] 后台执行并等待
来源：http://dali.guannengcc.top/Article/details/gtmotdcfmb.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.snrcjt.cn/Article/details/gtaqrmjxaj.html

[R36] 并发执行多个任务
来源：http://dali.hnxiangtu.top/Article/details/gtixrffsah.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.yanxiufei.cn/Article/details/gthwbsyfem.html

[R37] 把输出赋给变量
来源：http://dali.jianghu66.top/Article/details/gtrslutufo.html

files=$(ls -1)
来源：http://dali.zhengqikj.top/Article/details/gtdschdlgj.html

[R38] 管道串联
来源：http://dali.gzhubu.top/Article/details/gtmtgowksy.html

cat a.txt | grep -i error | wc -l
来源：http://dali.gotoacloud.top/Article/details/gtzcatdkby.html

[R39] 重定向标准输出与错误
来源：http://dali.cqqwz.cn/Article/details/gtplenlodu.html

cmd > out.log 2>&1
来源：http://dali.chenzaomai.com/Article/details/gtscustuze.html

[R40] 追加写日志
来源：http://dali.hnxiangtu.top/Article/details/gtdoceuvsv.html

echo "log" >> out.log
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmexxcwxv.html

[R41] 丢弃输出
来源：http://dali.jinqigufen.top/Article/details/gteabcezwb.html

cmd >/dev/null 2>&1
来源：http://dali.xinyue.icu/Article/details/gtvtuszplh.html

[R42] 输入重定向
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvcdlngun.html

wc -l < a.txt
来源：http://dali.redwolf501.top/Article/details/gtkonjhtat.html

[R43] 按名字查找文件
来源：http://dali.guowangkeji.top/Article/details/gtifsaazcs.html

find . -name "*.log" -type f
来源：http://dali.fzhhl.top/Article/details/gtttjpcghl.html

[R44] 按修改时间查找
来源：http://dali.chenjidiqi.icu/Article/details/gtxslhnsti.html

find . -mtime -7 -type f
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxxgqqtuo.html

[R45] 批量删除
来源：http://dali.gzhubu.top/Article/details/gthizglodw.html

find . -name "*.tmp" -delete
来源：http://dali.ybcxt.top/Article/details/gttjbgqjoj.html

[R46] 递归替换文件内容
来源：http://dali.jlsjyb.cn/Article/details/gtstzolgrd.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.xziqi.cn/Article/details/gtwyxmhnws.html

[R47] sed 单行替换
来源：http://dali.hongshengwenyu.top/Article/details/gtuawopqpq.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdvxbsguz.html

[R48] awk 取指定列
来源：http://dali.shzxlz.cn/Article/details/gtzbpcjrxd.html

awk '{print $1, $3}' a.txt
来源：http://dali.jlsjyb.cn/Article/details/gtryqofiau.html

[R49] awk 带条件
来源：http://dali.ppjwa.cn/Article/details/gtwsfutdry.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.316326.xyz/Article/details/gtfrlrpokl.html

[R50] awk 求和
来源：http://dali.havefunace.top/Article/details/gtxultldxx.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.shuidangran.top/Article/details/gtwxzvbbyc.html

[R51] 排序去重取前几
来源：http://dali.shanyushiyangtech.top/Article/details/gtptzsiixx.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.wangshuangyany.cn/Article/details/gtmiexvugf.html

[R52] 统计行数
来源：http://dali.fengsongda.top/Article/details/gtiptehtkq.html

wc -l a.txt
来源：http://dali.pengpengdd.cyou/Article/details/gtjtqtkjgq.html

[R53] 查看文件头与实时尾
来源：http://dali.yuanzhike.top/Article/details/gtyjwmliby.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvmsfutsu.html

[R54] 比较两个文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkknejsjn.html

diff a.txt b.txt
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjsigpnht.html

[R55] 压缩与解压
来源：http://dali.zhiwuduotai.top/Article/details/gtducmpeza.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.gogol.net.cn/Article/details/gtojhaigom.html

[R56] 远程拷贝
来源：http://dali.zhiwuduotai.top/Article/details/gtkwwehwro.html

scp file user@host:/path/
来源：http://dali.zdqjudy.top/Article/details/gtazruivly.html

[R57] 远程执行命令
来源：http://dali.fzhhl.top/Article/details/gtuaxtcaer.html

ssh user@host 'uptime'
来源：http://dali.nwbrower.top/Article/details/gtdnxdbjlm.html

[R58] 下载文件
来源：http://dali.birdmap.top/Article/details/gtijqhlvrl.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.havefunace.top/Article/details/gtixqipwou.html

[R59] 发 POST JSON
来源：http://dali.ydzc1.top/Article/details/gtdcuozqls.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.shuidangran.top/Article/details/gtclnqlvan.html

[R60] 只看 HTTP 状态码
来源：http://dali.jianghu66.top/Article/details/gtmnjoxtwc.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.hammf.cn/Article/details/gtbxunsujq.html

[R61] 磁盘占用
来源：http://dali.9152youxi.cn/Article/details/gtdxmdkdmi.html

df -h;  du -sh *
来源：http://dali.jinqigfzy.top/Article/details/gtdezuchzd.html

[R62] 找最占空间的文件
来源：http://dali.guowangkeji.top/Article/details/gtabmxmqsj.html

du -ah . | sort -rh | head -10
来源：http://dali.xziqi.cn/Article/details/gthmljfaaj.html

[R63] 内存与进程
来源：http://dali.vqdsnc.cn/Article/details/gtjtgqbvlc.html

free -h;  ps aux | grep nginx
来源：http://dali.jqgufenzy.top/Article/details/gtgbpwonyh.html

[R64] 结束进程
来源：http://dali.yonumen.top/Article/details/gtxworfvbc.html

kill -9 $(pgrep -f app.py)
来源：http://dali.tanke756.top/Article/details/gtzokitsez.html

[R65] 查看端口占用
来源：http://dali.hfpthk.cn/Article/details/gtwashxrux.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.svipenyu.cn/Article/details/gtgghnogvp.html

[R66] 定时任务
来源：http://dali.hywenlv.cn/Article/details/gtosoaojdl.html

crontab -e;  crontab -l
来源：http://dali.hysaishi.cn/Article/details/gtqlnimrwy.html

[R67] 生成随机十六进制串
来源：http://dali.redwolf501.top/Article/details/gtinujuwio.html

openssl rand -hex 16
来源：http://dali.ivvv.top/Article/details/gtrbycuxvo.html

[R68] 计算文件校验值
来源：http://dali.feifeiyinyue.top/Article/details/gtnehnygwo.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.sufxvd.cn/Article/details/gtordbebxv.html

[R69] 生成随机密码
来源：http://dali.hnxiangtu.top/Article/details/gtljdzerba.html

head -c 16 /dev/urandom | base64
来源：http://dali.jlsjyb.cn/Article/details/gtylhpkexn.html

[R70] 时间戳与互转
来源：http://dali.shuidangran.top/Article/details/gtedojjjqb.html

date +%s;  date -d @1700000000
来源：http://dali.xylfe.cn/Article/details/gtvzbmigeu.html

[R71] 日期格式化
来源：http://dali.zdqjudy.top/Article/details/gtrropgdaz.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.hongshengwenyu.top/Article/details/gtonlsliki.html

[R72] 等待端口就绪
来源：http://dali.0kj1m.cn/Article/details/gtbzhdlygo.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.svipenyu.cn/Article/details/gtpqlknoer.html

[R73] 分割大日志
来源：http://dali.shzxlz.cn/Article/details/gtfmoehwkt.html

split -l 1000 big.log part_
来源：http://dali.ybcxt.top/Article/details/gtfswmkcgd.html

[R74] 批量重命名
来源：http://dali.xuetiantiany.cn/Article/details/gtqubvnaob.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.hongshengwenyu.top/Article/details/gtrkfmmfwi.html

[R75] 导出环境变量
来源：http://dali.yj202588.top/Article/details/gtqjpxuizg.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.xinyue.icu/Article/details/gtcdgcfmhg.html

[R76] 使用临时文件
来源：http://dali.nanxuanxn.top/Article/details/gtzrbjkghb.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.sxryk.cn/Article/details/gtxpxrxgij.html

[R77] 读取用户输入
来源：http://dali.haohaochexian.top/Article/details/gtlkixxkgh.html

read -rp "请输入: " ans
来源：http://dali.meibo888.top/Article/details/gtmgrxfehl.html

[R78] 交互式菜单
来源：http://dali.ivvv.top/Article/details/gtvdnimuon.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.ehwqpu.com/Article/details/gtrkkeavji.html

[R79] 解析命令行选项
来源：http://dali.shangyingyoupin.top/Article/details/gtmlbexkff.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.andypj.xyz/Article/details/gtoovgypxl.html

[R80] 查看脚本执行耗时
来源：http://dali.jianghu66.top/Article/details/gticozjwxa.html

time ./run.sh
来源：http://dali.gogol.net.cn/Article/details/gtytpflqtb.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtblwdztwz.html

S. C / C++ 专题
来源：http://dali.jyoumei.cn/Article/details/gtdnvsixbm.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtwapaionq.html

[S01] C：Hello World
来源：http://dali.hnxiangtu.top/Article/details/gtsbrliyma.html

#include <stdio.h>
来源：http://dali.guowangkeji.top/Article/details/gtuclxwqfe.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.yj20258.top/Article/details/gtnbehywcw.html

[S02] C：变量与格式化输出
来源：http://dali.jqgfzy.top/Article/details/gtwjyqmfbw.html

int a = 10; printf("%d\n", a);
来源：http://dali.sxryk.cn/Article/details/gtimvhosrn.html

[S03] C：读入整数
来源：http://dali.nanxinkj.top/Article/details/gtfdwyjdgq.html

int x; scanf("%d", &x);
来源：http://dali.meibo888.top/Article/details/gtnzkwtsop.html

[S04] C：字符串复制
来源：http://dali.gotoacloud.top/Article/details/gtsakwkiqf.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhengqikj.top/Article/details/gtjsotmxan.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gtvzdhirhl.html

strlen(s)
来源：http://dali.cashguo.top/Article/details/gtttogpsfk.html

[S06] C：字符串比较
来源：http://dali.fzhhl.top/Article/details/gtkhjxpoqs.html

strcmp(a, b) == 0
来源：http://dali.gzhubu.top/Article/details/gtbygkqnxd.html

[S07] C：数组遍历求和
来源：http://dali.zhoulong.xyz/Article/details/gtcjnlilsz.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.cdnleiting.top/Article/details/gtqqnwhfrj.html

[S08] C：动态内存分配与释放
来源：http://dali.yj20258888.top/Article/details/gtipqatyzi.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.iojbl.cn/Article/details/gtnmmneozt.html

[S09] C：结构体定义与初始化
来源：http://dali.redwolf501.top/Article/details/gtpkdpfgwc.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.pengpengdd.cyou/Article/details/gttlamfqqs.html

[S10] C：指针与解引用
来源：http://dali.ppjwa.cn/Article/details/gtgsmngepq.html

int *p = &a;  *p = 5;
来源：http://dali.pycfn.com/Article/details/gtvdjnvrcp.html

[S11] C：逐行读文件
来源：http://dali.jyoumei.cn/Article/details/gtootofrab.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.wangdashe.top/Article/details/gtmgqjjrfs.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.yj20258.top/Article/details/gtvsztfyrx.html

fclose(f);
来源：http://dali.yj20258.top/Article/details/gttemcilnx.html

[S12] C：写文件
来源：http://dali.aibaodan.cn/Article/details/gthfncqdhu.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.xuanzx.com/Article/details/gtraidvhoh.html

[S13] C：宏定义
来源：http://dali.cqqwz.cn/Article/details/gtvyuzksyo.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.fzhhl.top/Article/details/gtvyglggis.html

[S14] C：枚举
来源：http://dali.sweek.top/Article/details/gtaveexvhp.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.ppjwa.cn/Article/details/gtdnuusmbb.html

[S15] C：类型转换
来源：http://dali.nanxinkj.top/Article/details/gtnpcyscbd.html

(double) a / b
来源：http://dali.yj20258.top/Article/details/gtjlinpkig.html

[S16] C：位操作置位
来源：http://dali.daria6918.cn/Article/details/gtszrneqhe.html

x |= (1 << 3);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtalbdgwhf.html

[S17] C：安全拼接字符串
来源：http://dali.bjfxy.top/Article/details/gtftkyybux.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.redwolf501.top/Article/details/gtkiqjcluf.html

[S18] C：命令行参数
来源：http://dali.jqgufenzy.top/Article/details/gtpvritbpq.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gtgttortkb.html

[S19] C：快速排序
来源：http://dali.yj20258.top/Article/details/gtznlothlt.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.kuanghao11.cn/Article/details/gtnlbgvfzn.html

[S20] C：二分查找
来源：http://dali.yj202588.top/Article/details/gtxhuvilwt.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.fengsongda.top/Article/details/gtgucmnkuy.html

[S21] C：字符类别判断
来源：http://dali.feifeiyinyue.top/Article/details/gtpmxhwfjk.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.tian-w.cn/Article/details/gtdaskxksn.html

[S22] C：字符串转数字
来源：http://dali.hnqzz.top/Article/details/gtqrsbbaog.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.yvedp.cn/Article/details/gtgyjikzcj.html

[S23] C：随机数
来源：http://dali.zhiwuduotai.top/Article/details/gttuybdtfg.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.yangfankeji.com/Article/details/gtqkznyyex.html

[S24] C：获取本地时间
来源：http://dali.wangshuangyany.cn/Article/details/gtzqedtane.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.jinqigfzy.top/Article/details/gtakrvpkmg.html

[S25] C：内存拷贝
来源：http://dali.shanyushiyangtech.top/Article/details/gtlmlmqhlw.html

memcpy(dst, src, n);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmkdyirio.html

[S26] C：内存清零
来源：http://dali.feifeiyinyue.top/Article/details/gtyvflbkib.html

memset(a, 0, sizeof a);
来源：http://dali.birdmap.top/Article/details/gtpqqhemwg.html

[S27] C：定义常量
来源：http://dali.yuanzhike.top/Article/details/gtuvrzlwpn.html

const double PI = 3.14159;
来源：http://dali.wangdashe.top/Article/details/gtonxoaujb.html

[S28] C：静态变量
来源：http://dali.zhongyouzk.top/Article/details/gtaxyzytdk.html

static int counter = 0;
来源：http://dali.jiagoushi.top/Article/details/gttqnqczzl.html

[S29] C：变参函数
来源：http://dali.yj202588.top/Article/details/gtnbvnplyz.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.nwbrower.top/Article/details/gtwulqhjyj.html

[S30] C：头文件保护
来源：http://dali.yongpay.top/Article/details/gtgzqmaujh.html

#ifndef X_H
来源：http://dali.nanxinkj.top/Article/details/gtltycyspq.html

#define X_H
来源：http://dali.chenlongwang.top/Article/details/gtchywjaeq.html

#endif
来源：http://dali.jiagoushi.top/Article/details/gtrtbyveds.html

[S31] C++：Hello World
来源：http://dali.redwolf501.top/Article/details/gthsnvlndf.html

#include <iostream>
来源：http://dali.ehwqpu.com/Article/details/gtnfyqlubk.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.sweek.top/Article/details/gtmqhfgshu.html

[S32] C++：字符串
来源：http://dali.fzhhl.top/Article/details/gtzasmorke.html

std::string s = "hi";  s += "!";
来源：http://dali.jinqigufen.top/Article/details/gtyklnmpvh.html

[S33] C++：vector 增删
来源：http://dali.bjfxy.top/Article/details/gtnmrcemaj.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.fengsongda.top/Article/details/gtjzlxexqk.html

[S34] C++：遍历 vector
来源：http://dali.fzhhl.top/Article/details/gtbpteltcl.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.nanxinkj.top/Article/details/gttehxiuha.html

[S35] C++：map
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgcmzubcl.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhixingplan.top/Article/details/gtoqwqhxom.html

[S36] C++：unordered_map
来源：http://dali.hongshengwenyu.top/Article/details/gtwhelrxmw.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.gogol.net.cn/Article/details/gtmsohefpn.html

[S37] C++：set
来源：http://dali.zycfv.cn/Article/details/gtinvylrga.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.xziqi.cn/Article/details/gtdiugnkob.html

[S38] C++：排序
来源：http://dali.xuanzx.com/Article/details/gtapldogem.html

std::sort(v.begin(), v.end());
来源：http://dali.cucudq.cn/Article/details/gtnqxkxafd.html

[S39] C++：自定义比较器排序
来源：http://dali.snrcjt.cn/Article/details/gtzgadeyur.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.ydzc1.top/Article/details/gtdhsohcuj.html

[S40] C++：查找元素
来源：http://dali.ehwqpu.com/Article/details/gtsvavceqs.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.jinqigufen.top/Article/details/gtkzjamdld.html

[S41] C++：类与构造函数
来源：http://dali.zhiwuduotai.top/Article/details/gtklfojvoe.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.jinqigfzy.top/Article/details/gtebkqsxzr.html

[S42] C++：继承与虚函数
来源：http://dali.shangyingyoupin.top/Article/details/gtjnlwfxvx.html

class B : public Base { public: void f() override {} };
来源：http://dali.shuidangran.top/Article/details/gtefqqnjgl.html

[S43] C++：智能指针
来源：http://dali.redwolf501.top/Article/details/gtrhfipmod.html

auto p = std::make_unique<int>(5);
来源：http://dali.iojbl.cn/Article/details/gtpvohlukk.html

[S44] C++：引用传参
来源：http://dali.gzhubu.top/Article/details/gttugxdqon.html

void inc(int &x) { ++x; }
来源：http://dali.quarkkingdee.top/Article/details/gtzxfezvne.html

[S45] C++：lambda
来源：http://dali.ybcxt.top/Article/details/gtssxqhmue.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.cheryme.top/Article/details/gtwqtnrcfv.html

[S46] C++：函数模板
来源：http://dali.mhx1999.top/Article/details/gtrdcrerme.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhoulong.xyz/Article/details/gtkbiikkob.html

[S47] C++：结构化绑定遍历
来源：http://dali.shangyingyoupin.top/Article/details/gtlyneuvqq.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.nanxinkj.top/Article/details/gtoqubtkeo.html

[S48] C++：逐行读文件
来源：http://dali.xuetiantiany.cn/Article/details/gtitikfdhp.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.ppjwa.cn/Article/details/gtnctgajrt.html

while (std::getline(in, line)) { }
来源：http://dali.zhengqikj.top/Article/details/gtyjapakun.html

[S49] C++：写文件
来源：http://dali.yangfankeji.com/Article/details/gtqczqmjnr.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.snrcjt.cn/Article/details/gtqklsnxkr.html

[S50] C++：格式化数字
来源：http://dali.nwbrower.top/Article/details/gtulhgbyuq.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.feifeiyinyue.top/Article/details/gtaynswfxg.html

[S51] C++：显式类型转换
来源：http://dali.sxryk.cn/Article/details/gtvhzhgsyl.html

static_cast<double>(a) / b
来源：http://dali.xuanzx.com/Article/details/gtkqnmzirz.html

[S52] C++：const 与 noexcept
来源：http://dali.hammf.cn/Article/details/gtnwjzqvnf.html

int size() const noexcept { return n_; }
来源：http://dali.chenjidiqi.icu/Article/details/gtqjuquaef.html

[S53] C++：移动语义
来源：http://dali.pengpengdd.cyou/Article/details/gtdvbwhzpk.html

std::vector<int> w = std::move(v);
来源：http://dali.iojbl.cn/Article/details/gtakftudxm.html

[S54] C++：异常处理
来源：http://dali.sxryk.cn/Article/details/gtmaftezrj.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gtzbwctcri.html

[S55] C++：结构化绑定
来源：http://dali.aibaodan.cn/Article/details/gtikolztpb.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.svipenyu.cn/Article/details/gtplrypbxu.html

[S56] C++：optional
来源：http://dali.chenlongwang.top/Article/details/gtvvytaded.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.pengpengdd.cyou/Article/details/gtruucdaye.html

[S57] C++：编译期常量
来源：http://dali.pycfn.com/Article/details/gtkrejfuhl.html

constexpr int N = 10;
来源：http://dali.daxiang520.top/Article/details/gtfdepkqez.html

[S58] C++：命名空间
来源：http://dali.ppjwa.cn/Article/details/gtegbtsfrk.html

namespace ns { int f() { return 1; } }
来源：http://dali.yangfankeji.com/Article/details/gtowiajfwp.html

[S59] C++：静态断言
来源：http://dali.yvedp.cn/Article/details/gtmhargsfi.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.xuanzx.com/Article/details/gtfoffskyu.html

[S60] C++：遍历并删除元素
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrzxauxub.html


<!-- 参考信息 -->