代发 wailian999

[Q84] 去除首尾空格
来源：http://dali.ydzc1.top/Article/details/gtmunalssi.html

SELECT TRIM(name) FROM users;
来源：http://dali.cashguo.top/Article/details/gthabsclzd.html

[Q85] 数值取整
来源：http://dali.iojbl.cn/Article/details/gtdkvmopnd.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.aizwys.cn/Article/details/gtcsciypfk.html

[Q86] 读取 JSON 字段
来源：http://dali.daxiang520.top/Article/details/gtfjlecchd.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.jqgfzy.top/Article/details/gtpqttkczn.html

[Q87] JSON 字段做条件
来源：http://dali.guannengcc.top/Article/details/gtojubtxjl.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.gogol.net.cn/Article/details/gtbvjrkuva.html

[Q88] 行转列（条件聚合）
来源：http://dali.xziqi.cn/Article/details/gtsywnwjxj.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.jianghu66.top/Article/details/gtwxysfrem.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.sxryk.cn/Article/details/gtqwonfesr.html

[Q89] 判断表是否存在
来源：http://dali.wangshuangyany.cn/Article/details/gtocwnzwef.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.jinqigfzy.top/Article/details/gtdtlypggn.html

[Q90] 生成序号列
来源：http://dali.cheryme.top/Article/details/gttgbyooyw.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.haohaochexian.top/Article/details/gtvvxikbxa.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtoorkzxrh.html

R. Bash 专题
来源：http://dali.aibaodan.cn/Article/details/gtxzitgeui.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtjygbmqnn.html

[R01] shebang 与严格模式
来源：http://dali.shzxlz.cn/Article/details/gtwxjfietg.html

#!/usr/bin/env bash
来源：http://dali.iojbl.cn/Article/details/gtmwesmwjg.html

set -euo pipefail
来源：http://dali.ivvv.top/Article/details/gtpvcfgswd.html

[R02] 变量赋值与使用
来源：http://dali.jqgfzy.top/Article/details/gthalhphtb.html

name="Tom"; echo "$name"
来源：http://dali.jinghuilouyu.cn/Article/details/gtfjrebiku.html

[R03] 只读变量
来源：http://dali.sysykeji.top/Article/details/gtavlejgnp.html

readonly PI=3.14
来源：http://dali.cqqwz.cn/Article/details/gtlbnidizh.html

[R04] 位置参数
来源：http://dali.aibaodan.cn/Article/details/gtfvtkrgwp.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.ppjwa.cn/Article/details/gtjreyfzqt.html

[R05] 参数默认值
来源：http://dali.cucudq.cn/Article/details/gtfheoydpz.html

name="${1:-default}"
来源：http://dali.ehwqpu.com/Article/details/gtykwizgej.html

[R06] 判断命令是否存在
来源：http://dali.pengpengdd.cyou/Article/details/gtjondjemq.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.gzhubu.top/Article/details/gtocmlnthr.html

[R07] if 判断文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtngpajayq.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.yuxming.cn/Article/details/gtspxsckmv.html

[R08] 数值比较
来源：http://dali.zhoulong.xyz/Article/details/gtsffnwjlw.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.gotoacloud.top/Article/details/gtttzxcrch.html

[R09] 字符串比较
来源：http://dali.ppjwa.cn/Article/details/gtwhrnwjie.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.sysykeji.top/Article/details/gtfdkgydtt.html

[R10] 正则匹配
来源：http://dali.iojbl.cn/Article/details/gtrffraeas.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.wangdashe.top/Article/details/gtyeatwpxw.html

[R11] case 多分支
来源：http://dali.chenzaomai.com/Article/details/gtpwnpiphe.html

case "$1" in
来源：http://dali.vqdsnc.cn/Article/details/gtwbwetrsq.html

start) echo "启动" ;;
来源：http://dali.haohaochexian.top/Article/details/gtqpkohato.html

stop)  echo "停止" ;;
来源：http://dali.wangdashe.top/Article/details/gtykeqwgja.html

*)     echo "未知命令" ;;
来源：http://dali.jinqigufen.top/Article/details/gttoquthxq.html

esac
来源：http://dali.guowangkeji.top/Article/details/gtrzncryje.html

[R12] for 遍历文件
来源：http://dali.kuanghao11.cn/Article/details/gtatmeebuo.html

for f in *.txt; do echo "$f"; done
来源：http://dali.quarkkingdee.top/Article/details/gtekoixigu.html

[R13] for 计数循环
来源：http://dali.gzhubu.top/Article/details/gtyudrjgdb.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.aizwys.cn/Article/details/gtmftedtft.html

[R14] C 风格 for
来源：http://dali.snrcjt.cn/Article/details/gtpypuruur.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.fengsongda.top/Article/details/gtwhdofivm.html

[R15] while 逐行读文件
来源：http://dali.yvedp.cn/Article/details/gthpjxidre.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.chenjidiqi.icu/Article/details/gtkftxmlsu.html

[R16] until 等待条件
来源：http://dali.guowangkeji.top/Article/details/gtzokbqcua.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.pycfn.com/Article/details/gtgqfyutor.html

[R17] 数组定义与取值
来源：http://dali.cqqwz.cn/Article/details/gtbpnlvmmp.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.nanxinkj.top/Article/details/gtigrhelnn.html

[R18] 遍历数组
来源：http://dali.jyoumei.cn/Article/details/gtstnkcofo.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.aizwys.cn/Article/details/gtozzwdaui.html

[R19] 数组长度
来源：http://dali.ehwqpu.com/Article/details/gtkxevyrja.html

echo "${#arr[@]}"
来源：http://dali.yj20258.top/Article/details/gttebdwmbt.html

[R20] 关联数组（字典）
来源：http://dali.jinyuanbaomall.cn/Article/details/gthzqetseq.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.xinyue.icu/Article/details/gtgkrtdken.html

[R21] 字符串长度
来源：http://dali.tianlin.xyz/Article/details/gtacuctnit.html

echo "${#s}"
来源：http://dali.sxryk.cn/Article/details/gtwwulavld.html

[R22] 截取子串
来源：http://dali.zhiwuduotai.top/Article/details/gtduqnbfyv.html

echo "${s:0:5}"
来源：http://dali.aibaodan.cn/Article/details/gtlrguejbr.html

[R23] 字符串替换
来源：http://dali.aibaodan.cn/Article/details/gtnrafblhk.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.jinqigufen.top/Article/details/gtufvhurhw.html

[R24] 大小写转换
来源：http://dali.jqgufenzy.top/Article/details/gtsyxgnbnd.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.wangshuangyany.cn/Article/details/gtsymfbgdy.html

[R25] 去后缀 / 去前缀
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxstmnnsj.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.hywenlv.cn/Article/details/gtnvagojcn.html

[R26] 命令替换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtphpvleij.html

now=$(date +%F); echo "$now"
来源：http://dali.smart0.xyz/Article/details/gtzmqalgau.html

[R27] 算术展开
来源：http://dali.haohaochexian.top/Article/details/gtirnitezp.html

echo $((1 + 2 * 3))
来源：http://dali.havefunace.top/Article/details/gtvwahxwwy.html

[R28] 浮点运算
来源：http://dali.nanxuanxn.top/Article/details/gtrkoncbcd.html

echo "scale=2; 10/3" | bc
来源：http://dali.havefunace.top/Article/details/gtojptsarq.html

[R29] 定义函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtojrlrxfa.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.daxiang520.top/Article/details/gtdncimcpq.html

[R30] 函数返回状态码
来源：http://dali.jlsjyb.cn/Article/details/gtfmvynwgp.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.sxryk.cn/Article/details/gtywodrbio.html

[R31] 局部变量
来源：http://dali.hnqzz.top/Article/details/gtwsmbftpu.html

f() { local x=1; echo "$x"; }
来源：http://dali.jqgfzy.top/Article/details/gthdsalsdu.html

[R32] 参数个数校验
来源：http://dali.yueranfly.top/Article/details/gtvthcpckj.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.shuidangran.top/Article/details/gtpcnoghat.html

[R33] 捕获错误并提示行号
来源：http://dali.daxiang520.top/Article/details/gtiklvrgby.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.havefunace.top/Article/details/gtdefunxml.html

[R34] 退出时清理
来源：http://dali.sweek.top/Article/details/gthemjpuca.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.yj20258888.top/Article/details/gtoapjqqto.html

[R35] 后台执行并等待
来源：http://dali.ehwqpu.com/Article/details/gtsxtzbycd.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.kuanghao11.cn/Article/details/gtdeziferc.html

[R36] 并发执行多个任务
来源：http://dali.dianchejie.cn/Article/details/gtslzvfjzb.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.xinyue.icu/Article/details/gthmztuknz.html

[R37] 把输出赋给变量
来源：http://dali.quarkkingdee.top/Article/details/gtccrxmxik.html

files=$(ls -1)
来源：http://dali.yuxming.cn/Article/details/gtuoehqown.html

[R38] 管道串联
来源：http://dali.yuxming.cn/Article/details/gtesowkokj.html

cat a.txt | grep -i error | wc -l
来源：http://dali.aizwys.cn/Article/details/gttxmrcoze.html

[R39] 重定向标准输出与错误
来源：http://dali.svipenyu.cn/Article/details/gtlmeeqrkn.html

cmd > out.log 2>&1
来源：http://dali.yj20258888.top/Article/details/gtcpkgqqpw.html

[R40] 追加写日志
来源：http://dali.jiagoushi.top/Article/details/gtyyblqjfp.html

echo "log" >> out.log
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzrfpwjkd.html

[R41] 丢弃输出
来源：http://dali.jqgfzy.top/Article/details/gtzgziqryr.html

cmd >/dev/null 2>&1
来源：http://dali.hnxiangtu.top/Article/details/gtilinbqqp.html

[R42] 输入重定向
来源：http://dali.shangyingyoupin.top/Article/details/gtldeyqtzf.html

wc -l < a.txt
来源：http://dali.jyoumei.cn/Article/details/gtxohtccgw.html

[R43] 按名字查找文件
来源：http://dali.iojbl.cn/Article/details/gtmlbnbsqu.html

find . -name "*.log" -type f
来源：http://dali.yuxming.cn/Article/details/gtmlqcqqdl.html

[R44] 按修改时间查找
来源：http://dali.zhaomingkeji.xyz/Article/details/gtahlgfgif.html

find . -mtime -7 -type f
来源：http://dali.iojbl.cn/Article/details/gtbrnvvznw.html

[R45] 批量删除
来源：http://dali.sufxvd.cn/Article/details/gtidsaszvg.html

find . -name "*.tmp" -delete
来源：http://dali.mhx1999.top/Article/details/gtprizaiun.html

[R46] 递归替换文件内容
来源：http://dali.ppjwa.cn/Article/details/gtpyizzkwk.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.sysykeji.top/Article/details/gtaqshbrbe.html

[R47] sed 单行替换
来源：http://dali.bjfxy.top/Article/details/gteiufxdqo.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.kuanghao11.cn/Article/details/gtapozdaol.html

[R48] awk 取指定列
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyicolwce.html

awk '{print $1, $3}' a.txt
来源：http://dali.nwbrower.top/Article/details/gtvecmjwfc.html

[R49] awk 带条件
来源：http://dali.pengpengdd.cyou/Article/details/gtaaemljnq.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.jqgfzy.top/Article/details/gtzkfcbaaz.html

[R50] awk 求和
来源：http://dali.shangyingyoupin.top/Article/details/gtkydgeogz.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.ywan-chungtsiang.top/Article/details/gttxhtynzf.html

[R51] 排序去重取前几
来源：http://dali.tanke756.top/Article/details/gtkazrjmgm.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.pengpengdd.cyou/Article/details/gtlgtucqfm.html

[R52] 统计行数
来源：http://dali.xziqi.cn/Article/details/gtcmeuhium.html

wc -l a.txt
来源：http://dali.jinghuilouyu.cn/Article/details/gtwzijxwop.html

[R53] 查看文件头与实时尾
来源：http://dali.aibaodan.cn/Article/details/gthokjdvix.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.cdnleiting.top/Article/details/gthuhtgsvv.html

[R54] 比较两个文件
来源：http://dali.zhixingplan.top/Article/details/gtwyzgpqvf.html

diff a.txt b.txt
来源：http://dali.hfpthk.cn/Article/details/gtejbeqnzt.html

[R55] 压缩与解压
来源：http://dali.pengpengdd.cyou/Article/details/gtqydibnps.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.fzhhl.top/Article/details/gtfsificha.html

[R56] 远程拷贝
来源：http://dali.cashguo.top/Article/details/gtprsfcugo.html

scp file user@host:/path/
来源：http://dali.zhongyouzk.top/Article/details/gtdzdrcwrp.html

[R57] 远程执行命令
来源：http://dali.mhx1999.top/Article/details/gtbmxezkqq.html

ssh user@host 'uptime'
来源：http://dali.iojbl.cn/Article/details/gtdsaiwrdh.html

[R58] 下载文件
来源：http://dali.hongshengwenyu.top/Article/details/gtgjouvgyv.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.gogol.net.cn/Article/details/gtfgsxetgb.html

[R59] 发 POST JSON
来源：http://dali.jianghu66.top/Article/details/gtqrlwdkag.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.fengsongda.top/Article/details/gtbbmtogub.html

[R60] 只看 HTTP 状态码
来源：http://dali.hnqzz.top/Article/details/gtpbsazzeb.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.ehwqpu.com/Article/details/gtzernsvoe.html

[R61] 磁盘占用
来源：http://dali.jiagoushi.top/Article/details/gtdngawxhx.html

df -h;  du -sh *
来源：http://dali.xylfe.cn/Article/details/gtmozbvwru.html

[R62] 找最占空间的文件
来源：http://dali.nanxinkj.top/Article/details/gtohkusjar.html

du -ah . | sort -rh | head -10
来源：http://dali.ehwqpu.com/Article/details/gtpvuiaukm.html

[R63] 内存与进程
来源：http://dali.xuetiantiany.cn/Article/details/gtgmskelym.html

free -h;  ps aux | grep nginx
来源：http://dali.hnqzz.top/Article/details/gtbdyrvhta.html

[R64] 结束进程
来源：http://dali.guowangkeji.top/Article/details/gtyuwpfdux.html

kill -9 $(pgrep -f app.py)
来源：http://dali.nanxuanxn.top/Article/details/gtquaszpav.html

[R65] 查看端口占用
来源：http://dali.hammf.cn/Article/details/gttmnztbjl.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.yanxiufei.cn/Article/details/gtevhxdblq.html

[R66] 定时任务
来源：http://dali.guannengcc.top/Article/details/gtkrpchbps.html

crontab -e;  crontab -l
来源：http://dali.hammf.cn/Article/details/gtevmfvqda.html

[R67] 生成随机十六进制串
来源：http://dali.chenlongwang.top/Article/details/gtrekdspmi.html

openssl rand -hex 16
来源：http://dali.pengpengdd.cyou/Article/details/gtsffmnrek.html

[R68] 计算文件校验值
来源：http://dali.wangdashe.top/Article/details/gtiegtccgb.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.c1oappe.top/Article/details/gtfwbwcpgh.html

[R69] 生成随机密码
来源：http://dali.jlsjyb.cn/Article/details/gtcsvwrfee.html

head -c 16 /dev/urandom | base64
来源：http://dali.jiagoushi.top/Article/details/gtnqfclgpj.html

[R70] 时间戳与互转
来源：http://dali.xuetiantiany.cn/Article/details/gtjwtklhtd.html

date +%s;  date -d @1700000000
来源：http://dali.zhiwuduotai.top/Article/details/gtxazivgrk.html

[R71] 日期格式化
来源：http://dali.birdmap.top/Article/details/gtxvrhjqvz.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.daria6918.cn/Article/details/gteakkkgpg.html

[R72] 等待端口就绪
来源：http://dali.havefunace.top/Article/details/gtarhgwguk.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.fengsongda.top/Article/details/gtozoowfpc.html

[R73] 分割大日志
来源：http://dali.shuidangran.top/Article/details/gtdqztfkzx.html

split -l 1000 big.log part_
来源：http://dali.pengpengdd.cyou/Article/details/gtrzipqgtv.html

[R74] 批量重命名
来源：http://dali.jqgufenzy.top/Article/details/gthohqcryl.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.redwolf501.top/Article/details/gtgaqraadk.html

[R75] 导出环境变量
来源：http://dali.vqdsnc.cn/Article/details/gtcmzbhitx.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.fzhhl.top/Article/details/gtfppeltsb.html

[R76] 使用临时文件
来源：http://dali.jyoumei.cn/Article/details/gtyzrywdch.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.iojbl.cn/Article/details/gthsoyoxic.html

[R77] 读取用户输入
来源：http://dali.nanxinkj.top/Article/details/gtolttmhgq.html

read -rp "请输入: " ans
来源：http://dali.hysaishi.cn/Article/details/gtxdslatzq.html

[R78] 交互式菜单
来源：http://dali.xziqi.cn/Article/details/gtxdjixkyd.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhengqikj.top/Article/details/gtjtwniqrk.html

[R79] 解析命令行选项
来源：http://dali.hnxiangtu.top/Article/details/gtxbsvwxfp.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.tanke756.top/Article/details/gtxkrepyuo.html

[R80] 查看脚本执行耗时
来源：http://dali.tian-w.cn/Article/details/gtativuzrp.html

time ./run.sh
来源：http://dali.gogol.net.cn/Article/details/gtwtjvvcpl.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtpnhxklky.html

S. C / C++ 专题
来源：http://dali.wangshuangyany.cn/Article/details/gtqiggbfuz.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtojsvdrja.html

[S01] C：Hello World
来源：http://dali.sxryk.cn/Article/details/gtstsyhkos.html

#include <stdio.h>
来源：http://dali.fzhhl.top/Article/details/gtllzrlecg.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.kuanghao11.cn/Article/details/gtyynksstx.html

[S02] C：变量与格式化输出
来源：http://dali.aibaodan.cn/Article/details/gtetillben.html

int a = 10; printf("%d\n", a);
来源：http://dali.jqgfzy.top/Article/details/gtmzmmpuym.html

[S03] C：读入整数
来源：http://dali.mhx1999.top/Article/details/gtzpukmvmb.html

int x; scanf("%d", &x);
来源：http://dali.vqdsnc.cn/Article/details/gttqjcbujo.html

[S04] C：字符串复制
来源：http://dali.yj202588.top/Article/details/gthbwmzowi.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.jlsjyb.cn/Article/details/gtrzeykflj.html

[S05] C：字符串长度
来源：http://dali.yongpay.top/Article/details/gtwsddbzuq.html

strlen(s)
来源：http://dali.sysykeji.top/Article/details/gtmccvwzau.html

[S06] C：字符串比较
来源：http://dali.shanyushiyangtech.top/Article/details/gtdzfyvlyg.html

strcmp(a, b) == 0
来源：http://dali.hammf.cn/Article/details/gtjpbjxvkc.html

[S07] C：数组遍历求和
来源：http://dali.chenlongwang.top/Article/details/gtkkticjzv.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.fengsongda.top/Article/details/gtlnmyjmdp.html

[S08] C：动态内存分配与释放
来源：http://dali.c1oappe.top/Article/details/gtllwtftqr.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.xylfe.cn/Article/details/gtrdkyweyr.html

[S09] C：结构体定义与初始化
来源：http://dali.sufxvd.cn/Article/details/gtxybopzib.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.hywenlv.cn/Article/details/gtdtggnzvy.html

[S10] C：指针与解引用
来源：http://dali.nwbrower.top/Article/details/gtqkjkcmlt.html

int *p = &a;  *p = 5;
来源：http://dali.aizwys.cn/Article/details/gtkdfcjxzp.html

[S11] C：逐行读文件
来源：http://dali.nwbrower.top/Article/details/gtpifmdnbk.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.gogol.net.cn/Article/details/gtjkmdezck.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.jianghu66.top/Article/details/gtiaohwjfa.html

fclose(f);
来源：http://dali.gzhubu.top/Article/details/gtjqxunoxe.html

[S12] C：写文件
来源：http://dali.dashuyun.cn/Article/details/gthkmkbjqv.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.wangdashe.top/Article/details/gtwfmvoevm.html

[S13] C：宏定义
来源：http://dali.shanyushiyangtech.top/Article/details/gtbjhyjwdf.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.shzxlz.cn/Article/details/gttfrpenct.html

[S14] C：枚举
来源：http://dali.zhixingplan.top/Article/details/gtvwxzffev.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.fengsongda.top/Article/details/gtgrcndjzj.html

[S15] C：类型转换
来源：http://dali.chenzaomai.com/Article/details/gtmzuvmmmk.html

(double) a / b
来源：http://dali.c1oappe.top/Article/details/gtjmycmzah.html

[S16] C：位操作置位
来源：http://dali.yj20258888.top/Article/details/gtdxoczvox.html

x |= (1 << 3);
来源：http://dali.ydzc1.top/Article/details/gtzmjdzagw.html

[S17] C：安全拼接字符串
来源：http://dali.guannengcc.top/Article/details/gtbgafemcc.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhixingplan.top/Article/details/gtdererwed.html

[S18] C：命令行参数
来源：http://dali.jinqigfzy.top/Article/details/gtflfglvfg.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gtbrckpihr.html

[S19] C：快速排序
来源：http://dali.sufxvd.cn/Article/details/gtoaotdliu.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.aibaodan.cn/Article/details/gtidrgulek.html

[S20] C：二分查找
来源：http://dali.birdmap.top/Article/details/gtwwacsoiu.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhixingplan.top/Article/details/gtlewzcmum.html

[S21] C：字符类别判断
来源：http://dali.zhixingplan.top/Article/details/gtyfzvdysc.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.dashuyun.cn/Article/details/gtwdzranyo.html

[S22] C：字符串转数字
来源：http://dali.nwbrower.top/Article/details/gtnfddxviz.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.cashguo.top/Article/details/gtxrhjbyzv.html

[S23] C：随机数
来源：http://dali.jlsjyb.cn/Article/details/gtzxjjlrza.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.yj20258888.top/Article/details/gtvhxgpxeu.html

[S24] C：获取本地时间
来源：http://dali.jinghuilouyu.cn/Article/details/gtjeloqigh.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhongyouzk.top/Article/details/gthdhdcqhi.html

[S25] C：内存拷贝
来源：http://dali.haohaochexian.top/Article/details/gtonsydhqj.html

memcpy(dst, src, n);
来源：http://dali.sufxvd.cn/Article/details/gtzhsdagst.html

[S26] C：内存清零
来源：http://dali.smart0.xyz/Article/details/gtdwkpbbvh.html

memset(a, 0, sizeof a);
来源：http://dali.zhoulong.xyz/Article/details/gtproiebpe.html

[S27] C：定义常量
来源：http://dali.hammf.cn/Article/details/gtrdrlipvj.html

const double PI = 3.14159;
来源：http://dali.feifeiyinyue.top/Article/details/gtbagqqdfc.html

[S28] C：静态变量
来源：http://dali.birdmap.top/Article/details/gtctxnffsu.html

static int counter = 0;
来源：http://dali.guowangkeji.top/Article/details/gtslcjhbzi.html

[S29] C：变参函数
来源：http://dali.jqgfzy.top/Article/details/gtkfjtdvmi.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.chenlongwang.top/Article/details/gtyltktulc.html

[S30] C：头文件保护
来源：http://dali.jlsjyb.cn/Article/details/gtksmgoebu.html

#ifndef X_H
来源：http://dali.9152youxi.cn/Article/details/gtqbwzirsn.html

#define X_H
来源：http://dali.redwolf501.top/Article/details/gtznesnvii.html

#endif
来源：http://dali.gotoacloud.top/Article/details/gtayaviixq.html

[S31] C++：Hello World
来源：http://dali.wangshuangyany.cn/Article/details/gtsmtkmodb.html

#include <iostream>
来源：http://dali.daria6918.cn/Article/details/gtahmvkhyv.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.hysaishi.cn/Article/details/gtdamsaiqz.html

[S32] C++：字符串
来源：http://dali.wangshuangyany.cn/Article/details/gtmwtrluev.html

std::string s = "hi";  s += "!";
来源：http://dali.xinyue.icu/Article/details/gtldnwfypc.html

[S33] C++：vector 增删
来源：http://dali.daria6918.cn/Article/details/gtpghiecfu.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhengqikj.top/Article/details/gtfrsdqdur.html

[S34] C++：遍历 vector
来源：http://dali.jyoumei.cn/Article/details/gtzdlgphjs.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.ybcxt.top/Article/details/gtycmossxr.html

[S35] C++：map
来源：http://dali.ehwqpu.com/Article/details/gteuokvahy.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jinghuilouyu.cn/Article/details/gtvnkahllq.html

[S36] C++：unordered_map
来源：http://dali.yuxming.cn/Article/details/gtorakprww.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.meibo888.top/Article/details/gttywyxntb.html

[S37] C++：set
来源：http://dali.zhiwuduotai.top/Article/details/gtnsexmlko.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgjazcvkj.html

[S38] C++：排序
来源：http://dali.ydzc1.top/Article/details/gtjujtdmcs.html

std::sort(v.begin(), v.end());
来源：http://dali.feifeiyinyue.top/Article/details/gtutchgplf.html

[S39] C++：自定义比较器排序
来源：http://dali.birdmap.top/Article/details/gtppxolmoy.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.shzxlz.cn/Article/details/gtqyhlzblk.html

[S40] C++：查找元素
来源：http://dali.yj20258.top/Article/details/gtppaghzrd.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.yj202588.top/Article/details/gtutmnoqst.html

[S41] C++：类与构造函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqhttyqpq.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zycfv.cn/Article/details/gtikcanemj.html

[S42] C++：继承与虚函数
来源：http://dali.gzhubu.top/Article/details/gtkwtecygl.html

class B : public Base { public: void f() override {} };
来源：http://dali.cheryme.top/Article/details/gttyehjqvp.html

[S43] C++：智能指针
来源：http://dali.yj202588.top/Article/details/gttfsvezvg.html

auto p = std::make_unique<int>(5);
来源：http://dali.yj20258888.top/Article/details/gtlhpwivpo.html

[S44] C++：引用传参
来源：http://dali.zdqjudy.top/Article/details/gtjnydnaau.html

void inc(int &x) { ++x; }
来源：http://dali.vqdsnc.cn/Article/details/gtyunipcpp.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gtifnpbrgp.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsmzeumby.html

[S46] C++：函数模板
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyfgyudlu.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhongyouzk.top/Article/details/gtzehmcizk.html

[S47] C++：结构化绑定遍历
来源：http://dali.jinqigfzy.top/Article/details/gtxlssxfsp.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.0kj1m.cn/Article/details/gttanbhggk.html

[S48] C++：逐行读文件
来源：http://dali.yangfankeji.com/Article/details/gtghczlgfl.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.0kj1m.cn/Article/details/gtzooeaecv.html

while (std::getline(in, line)) { }
来源：http://dali.ppjwa.cn/Article/details/gtfwwaluye.html

[S49] C++：写文件
来源：http://dali.chenjidiqi.icu/Article/details/gtpgxcxcof.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.svipenyu.cn/Article/details/gtzexkhrtf.html

[S50] C++：格式化数字
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnloetits.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.dashuyun.cn/Article/details/gtpjqteyrr.html

[S51] C++：显式类型转换
来源：http://dali.nanxinkj.top/Article/details/gtoiwtodpg.html

static_cast<double>(a) / b
来源：http://dali.chenjidiqi.icu/Article/details/gtixzrhlud.html

[S52] C++：const 与 noexcept
来源：http://dali.pengpengdd.cyou/Article/details/gtazmfgfax.html

int size() const noexcept { return n_; }
来源：http://dali.cucudq.cn/Article/details/gthkychepu.html

[S53] C++：移动语义
来源：http://dali.iojbl.cn/Article/details/gtslkwiaie.html

std::vector<int> w = std::move(v);
来源：http://dali.sxryk.cn/Article/details/gteemfdvww.html

[S54] C++：异常处理
来源：http://dali.yj20258.top/Article/details/gtpftzmqiw.html


<!-- 参考信息 -->