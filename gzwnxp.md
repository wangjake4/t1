代发 wailian999

[Q86] 读取 JSON 字段
来源：http://dali.xuanzx.com/Article/details/gttsydeybv.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.jinqigufen.top/Article/details/gtuguiywzb.html

[Q87] JSON 字段做条件
来源：http://dali.xziqi.cn/Article/details/gttftrrdfv.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.9152youxi.cn/Article/details/gtwivcjmaw.html

[Q88] 行转列（条件聚合）
来源：http://dali.yangfankeji.com/Article/details/gtxyrvubhl.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.hysaishi.cn/Article/details/gtupqkigzb.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gtanbulbdr.html

[Q89] 判断表是否存在
来源：http://dali.jlsjyb.cn/Article/details/gtjlioiush.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.hywenlv.cn/Article/details/gtadajaaci.html

[Q90] 生成序号列
来源：http://dali.yangfankeji.com/Article/details/gtoubgriun.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.xuetiantiany.cn/Article/details/gtdwryjieq.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtczbemhmb.html

R. Bash 专题
来源：http://dali.nwbrower.top/Article/details/gtoypxeaun.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtsbkwkmyn.html

[R01] shebang 与严格模式
来源：http://dali.haohaochexian.top/Article/details/gtvqqoxcii.html

#!/usr/bin/env bash
来源：http://dali.iojbl.cn/Article/details/gtslujkixp.html

set -euo pipefail
来源：http://dali.xuetiantiany.cn/Article/details/gtcoyghqtp.html

[R02] 变量赋值与使用
来源：http://dali.yuxming.cn/Article/details/gtckjerfkl.html

name="Tom"; echo "$name"
来源：http://dali.gogol.net.cn/Article/details/gthdoxfils.html

[R03] 只读变量
来源：http://dali.hnqzz.top/Article/details/gtxvzozqur.html

readonly PI=3.14
来源：http://dali.hnxiangtu.top/Article/details/gtyrrxxwoa.html

[R04] 位置参数
来源：http://dali.zhengqikj.top/Article/details/gtyoixwurb.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.redwolf501.top/Article/details/gthrccqdut.html

[R05] 参数默认值
来源：http://dali.bjfxy.top/Article/details/gtsjaezktb.html

name="${1:-default}"
来源：http://dali.birdmap.top/Article/details/gtdnqjucwb.html

[R06] 判断命令是否存在
来源：http://dali.zhixingplan.top/Article/details/gtplwcpnqn.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.sysykeji.top/Article/details/gtjfljprky.html

[R07] if 判断文件
来源：http://dali.jqgfzy.top/Article/details/gtornmmokf.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.feifeiyinyue.top/Article/details/gtvhlpckjm.html

[R08] 数值比较
来源：http://dali.hammf.cn/Article/details/gttisqlkhk.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.316326.xyz/Article/details/gtqvmauieq.html

[R09] 字符串比较
来源：http://dali.nanxinkj.top/Article/details/gtyandrbmd.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.chenjidiqi.icu/Article/details/gtzazsmqmq.html

[R10] 正则匹配
来源：http://dali.shangyingyoupin.top/Article/details/gtjshldbpu.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.aizwys.cn/Article/details/gtbajsfrqj.html

[R11] case 多分支
来源：http://dali.hnqzz.top/Article/details/gtspbblimq.html

case "$1" in
来源：http://dali.jyoumei.cn/Article/details/gtosfenffs.html

start) echo "启动" ;;
来源：http://dali.meibo888.top/Article/details/gtgdzbdqcu.html

stop)  echo "停止" ;;
来源：http://dali.daxiang520.top/Article/details/gtbzdhezgs.html

*)     echo "未知命令" ;;
来源：http://dali.chenlongwang.top/Article/details/gtqssodlqu.html

esac
来源：http://dali.birdmap.top/Article/details/gttvalppps.html

[R12] for 遍历文件
来源：http://dali.hywenlv.cn/Article/details/gtxlydroqh.html

for f in *.txt; do echo "$f"; done
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxgidbbjg.html

[R13] for 计数循环
来源：http://dali.daria6918.cn/Article/details/gtfqymhlsj.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.daria6918.cn/Article/details/gthddoobvf.html

[R14] C 风格 for
来源：http://dali.jyoumei.cn/Article/details/gtnqndzqmn.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.jqgfzy.top/Article/details/gtobdmkkwz.html

[R15] while 逐行读文件
来源：http://dali.0kj1m.cn/Article/details/gtqoitvgei.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.tianlin.xyz/Article/details/gtxmubyuyr.html

[R16] until 等待条件
来源：http://dali.pengpengdd.cyou/Article/details/gtnbcbidfj.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.ivvv.top/Article/details/gtfspukghc.html

[R17] 数组定义与取值
来源：http://dali.ppjwa.cn/Article/details/gtcpflgpgh.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhoulong.xyz/Article/details/gtlrdawpkf.html

[R18] 遍历数组
来源：http://dali.yangfankeji.com/Article/details/gtlojovpix.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.yj202588.top/Article/details/gtxxnljhhk.html

[R19] 数组长度
来源：http://dali.shangyingyoupin.top/Article/details/gtumkscnuq.html

echo "${#arr[@]}"
来源：http://dali.yj202588.top/Article/details/gtoluaiqds.html

[R20] 关联数组（字典）
来源：http://dali.yangfankeji.com/Article/details/gtcpghfiwh.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.daria6918.cn/Article/details/gtwnaeipux.html

[R21] 字符串长度
来源：http://dali.yueranfly.top/Article/details/gtrsaevyvg.html

echo "${#s}"
来源：http://dali.guowangkeji.top/Article/details/gttsrfjnmf.html

[R22] 截取子串
来源：http://dali.wangshuangyany.cn/Article/details/gtestptfvq.html

echo "${s:0:5}"
来源：http://dali.shzxlz.cn/Article/details/gtmifjcjed.html

[R23] 字符串替换
来源：http://dali.wangdashe.top/Article/details/gtmvjsxoun.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.havefunace.top/Article/details/gteodvytuy.html

[R24] 大小写转换
来源：http://dali.shangyingyoupin.top/Article/details/gtrzapymet.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxjwxxror.html

[R25] 去后缀 / 去前缀
来源：http://dali.meibo888.top/Article/details/gtbehenxjm.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.cqqwz.cn/Article/details/gtmspppsjq.html

[R26] 命令替换
来源：http://dali.zhiwuduotai.top/Article/details/gtdwbiracc.html

now=$(date +%F); echo "$now"
来源：http://dali.chenlongwang.top/Article/details/gtgtxzejwz.html

[R27] 算术展开
来源：http://dali.daria6918.cn/Article/details/gtkwxikcst.html

echo $((1 + 2 * 3))
来源：http://dali.pengpengdd.cyou/Article/details/gtsobmwgoi.html

[R28] 浮点运算
来源：http://dali.fengsongda.top/Article/details/gteceaucfe.html

echo "scale=2; 10/3" | bc
来源：http://dali.sweek.top/Article/details/gtqycfwats.html

[R29] 定义函数
来源：http://dali.jlsjyb.cn/Article/details/gtoghavgas.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.ydzc1.top/Article/details/gtbaloiftj.html

[R30] 函数返回状态码
来源：http://dali.xuetiantiany.cn/Article/details/gtvlaitsks.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.nanxuanxn.top/Article/details/gtcuhfqmrq.html

[R31] 局部变量
来源：http://dali.sufxvd.cn/Article/details/gtlftbddxk.html

f() { local x=1; echo "$x"; }
来源：http://dali.shuidangran.top/Article/details/gttrjkpzjq.html

[R32] 参数个数校验
来源：http://dali.ppjwa.cn/Article/details/gthjctebnk.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.chenjidiqi.icu/Article/details/gtakzyrwaf.html

[R33] 捕获错误并提示行号
来源：http://dali.nanxinkj.top/Article/details/gtglukswuq.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.feifeiyinyue.top/Article/details/gtqahkdbvu.html

[R34] 退出时清理
来源：http://dali.cashguo.top/Article/details/gthhobisoj.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.redwolf501.top/Article/details/gtbfnjspfx.html

[R35] 后台执行并等待
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnbveuhiv.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.aizwys.cn/Article/details/gtpjlbtsae.html

[R36] 并发执行多个任务
来源：http://dali.bjfxy.top/Article/details/gteyhjgkgn.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.hammf.cn/Article/details/gtlrqnyblk.html

[R37] 把输出赋给变量
来源：http://dali.yj20258.top/Article/details/gtfqkxjrgu.html

files=$(ls -1)
来源：http://dali.meibo888.top/Article/details/gtxrjmsrep.html

[R38] 管道串联
来源：http://dali.sxryk.cn/Article/details/gtpqujbjhp.html

cat a.txt | grep -i error | wc -l
来源：http://dali.yj20258.top/Article/details/gtcxcnilii.html

[R39] 重定向标准输出与错误
来源：http://dali.sweek.top/Article/details/gtmsksihwk.html

cmd > out.log 2>&1
来源：http://dali.yvedp.cn/Article/details/gthghzvsll.html

[R40] 追加写日志
来源：http://dali.andypj.xyz/Article/details/gtziebaanh.html

echo "log" >> out.log
来源：http://dali.quarkkingdee.top/Article/details/gtyksubjzf.html

[R41] 丢弃输出
来源：http://dali.ivvv.top/Article/details/gtvxvprvsa.html

cmd >/dev/null 2>&1
来源：http://dali.yj202588.top/Article/details/gtnkxzrdib.html

[R42] 输入重定向
来源：http://dali.ybcxt.top/Article/details/gtbrbuukkm.html

wc -l < a.txt
来源：http://dali.chenlongwang.top/Article/details/gtheadueeb.html

[R43] 按名字查找文件
来源：http://dali.nwbrower.top/Article/details/gtthzybyqb.html

find . -name "*.log" -type f
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtejgtgrri.html

[R44] 按修改时间查找
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdgriluqt.html

find . -mtime -7 -type f
来源：http://dali.tanke756.top/Article/details/gtoqbfhxku.html

[R45] 批量删除
来源：http://dali.jyoumei.cn/Article/details/gtqqtakkfm.html

find . -name "*.tmp" -delete
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuqswktyx.html

[R46] 递归替换文件内容
来源：http://dali.c1oappe.top/Article/details/gtpaxelztq.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.yj202588.top/Article/details/gtrjatwmli.html

[R47] sed 单行替换
来源：http://dali.pengpengdd.cyou/Article/details/gtodbjajxp.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.xziqi.cn/Article/details/gtmqrsgnxg.html

[R48] awk 取指定列
来源：http://dali.hywenlv.cn/Article/details/gtihocrekm.html

awk '{print $1, $3}' a.txt
来源：http://dali.yueranfly.top/Article/details/gttjqefeqk.html

[R49] awk 带条件
来源：http://dali.zhengqikj.top/Article/details/gtulhajhyb.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.ppjwa.cn/Article/details/gtecjybmzk.html

[R50] awk 求和
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmlajlgfi.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.cqqwz.cn/Article/details/gtsqimtghc.html

[R51] 排序去重取前几
来源：http://dali.pycfn.com/Article/details/gtcgwzgqgp.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.hammf.cn/Article/details/gtzavztusk.html

[R52] 统计行数
来源：http://dali.tian-w.cn/Article/details/gtzbkirqcm.html

wc -l a.txt
来源：http://dali.daxiang520.top/Article/details/gtibomicln.html

[R53] 查看文件头与实时尾
来源：http://dali.tianlin.xyz/Article/details/gtwcdtwvko.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.meibo888.top/Article/details/gtyphszqir.html

[R54] 比较两个文件
来源：http://dali.havefunace.top/Article/details/gtgboobpil.html

diff a.txt b.txt
来源：http://dali.gotoacloud.top/Article/details/gtpnaoxqvg.html

[R55] 压缩与解压
来源：http://dali.sweek.top/Article/details/gtxwibttpf.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.daxiang520.top/Article/details/gtvgfydbzu.html

[R56] 远程拷贝
来源：http://dali.aizwys.cn/Article/details/gtvvrgqxnr.html

scp file user@host:/path/
来源：http://dali.chenzaomai.com/Article/details/gtdvudwxcl.html

[R57] 远程执行命令
来源：http://dali.jinghuilouyu.cn/Article/details/gtdrqzvkuc.html

ssh user@host 'uptime'
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkltakkkp.html

[R58] 下载文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbpiqcusp.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.yj20258.top/Article/details/gtqrahgzcl.html

[R59] 发 POST JSON
来源：http://dali.hnxiangtu.top/Article/details/gtwcstenyd.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.shuidangran.top/Article/details/gtqjrhdrpv.html

[R60] 只看 HTTP 状态码
来源：http://dali.mhx1999.top/Article/details/gtucxluboh.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.daria6918.cn/Article/details/gtyikqlcjp.html

[R61] 磁盘占用
来源：http://dali.xuanzx.com/Article/details/gtgwvqvuyk.html

df -h;  du -sh *
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyoakokqt.html

[R62] 找最占空间的文件
来源：http://dali.gogol.net.cn/Article/details/gtmuzkkaxg.html

du -ah . | sort -rh | head -10
来源：http://dali.dashuyun.cn/Article/details/gtkgcugneb.html

[R63] 内存与进程
来源：http://dali.fzhhl.top/Article/details/gtgmcflaqs.html

free -h;  ps aux | grep nginx
来源：http://dali.hammf.cn/Article/details/gtlpkxgfbo.html

[R64] 结束进程
来源：http://dali.yvedp.cn/Article/details/gtekysqydn.html

kill -9 $(pgrep -f app.py)
来源：http://dali.yongpay.top/Article/details/gtexmxtwej.html

[R65] 查看端口占用
来源：http://dali.shanyushiyangtech.top/Article/details/gtnmzguhxs.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.svipenyu.cn/Article/details/gtikoumdno.html

[R66] 定时任务
来源：http://dali.redwolf501.top/Article/details/gttdtpuydq.html

crontab -e;  crontab -l
来源：http://dali.haohaochexian.top/Article/details/gtjpeqxrfd.html

[R67] 生成随机十六进制串
来源：http://dali.jinghuilouyu.cn/Article/details/gtfcqjpwoe.html

openssl rand -hex 16
来源：http://dali.svipenyu.cn/Article/details/gthbebyhwc.html

[R68] 计算文件校验值
来源：http://dali.hfpthk.cn/Article/details/gtyvmzeblm.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.chenlongwang.top/Article/details/gtezmbxyqw.html

[R69] 生成随机密码
来源：http://dali.hammf.cn/Article/details/gtheqwizgn.html

head -c 16 /dev/urandom | base64
来源：http://dali.iojbl.cn/Article/details/gtxrpysbnu.html

[R70] 时间戳与互转
来源：http://dali.cqqwz.cn/Article/details/gtxmsudcek.html

date +%s;  date -d @1700000000
来源：http://dali.fzhhl.top/Article/details/gtjujnikrx.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gtosyomfuq.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.nanxinkj.top/Article/details/gtykgsjvdi.html

[R72] 等待端口就绪
来源：http://dali.yangfankeji.com/Article/details/gtrtklwryf.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhixingplan.top/Article/details/gtcydwyyum.html

[R73] 分割大日志
来源：http://dali.guannengcc.top/Article/details/gtecdeyhfi.html

split -l 1000 big.log part_
来源：http://dali.guowangkeji.top/Article/details/gtjtyptwdq.html

[R74] 批量重命名
来源：http://dali.yj20258.top/Article/details/gtvnblsvil.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhengqikj.top/Article/details/gtuiumuwpp.html

[R75] 导出环境变量
来源：http://dali.dashuyun.cn/Article/details/gtdkdbybxr.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.fzhhl.top/Article/details/gtavkwqepe.html

[R76] 使用临时文件
来源：http://dali.gaohongyu789.top/Article/details/gthiwknvhi.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.jyoumei.cn/Article/details/gtkqiqvayn.html

[R77] 读取用户输入
来源：http://dali.tanke756.top/Article/details/gtodocivyl.html

read -rp "请输入: " ans
来源：http://dali.wangshuangyany.cn/Article/details/gtuzxrkhcg.html

[R78] 交互式菜单
来源：http://dali.ydzc1.top/Article/details/gtodxtturs.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdludpwxt.html

[R79] 解析命令行选项
来源：http://dali.pengpengdd.cyou/Article/details/gtfujihlyk.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.yvedp.cn/Article/details/gtrxfhvdcx.html

[R80] 查看脚本执行耗时
来源：http://dali.fengsongda.top/Article/details/gtwbxsdfkr.html

time ./run.sh
来源：http://dali.dashuyun.cn/Article/details/gtmfbntbfa.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtdzastjdz.html

S. C / C++ 专题
来源：http://dali.sweek.top/Article/details/gtfgugxpph.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtcrangxju.html

[S01] C：Hello World
来源：http://dali.yanxiufei.cn/Article/details/gtwlxlgqye.html

#include <stdio.h>
来源：http://dali.hongshengwenyu.top/Article/details/gthnhegmhn.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.dashuyun.cn/Article/details/gtfpuzycdg.html

[S02] C：变量与格式化输出
来源：http://dali.xylfe.cn/Article/details/gtsvtaodgg.html

int a = 10; printf("%d\n", a);
来源：http://dali.chenlongwang.top/Article/details/gtrpcekxob.html

[S03] C：读入整数
来源：http://dali.dianchejie.cn/Article/details/gtsprwaect.html

int x; scanf("%d", &x);
来源：http://dali.cheryme.top/Article/details/gtgdbheklf.html

[S04] C：字符串复制
来源：http://dali.zdqjudy.top/Article/details/gtlxkstaum.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.snrcjt.cn/Article/details/gthbxsyhkm.html

[S05] C：字符串长度
来源：http://dali.aizwys.cn/Article/details/gttiwaembj.html

strlen(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbuwjuwqk.html

[S06] C：字符串比较
来源：http://dali.yueranfly.top/Article/details/gtsczwtehv.html

strcmp(a, b) == 0
来源：http://dali.daxiang520.top/Article/details/gtzdhahnkr.html

[S07] C：数组遍历求和
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjxqarhqn.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.jlsjyb.cn/Article/details/gtnzudfgkg.html

[S08] C：动态内存分配与释放
来源：http://dali.hongshengwenyu.top/Article/details/gtjxzipjms.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.iojbl.cn/Article/details/gttaulwjbg.html

[S09] C：结构体定义与初始化
来源：http://dali.bjfxy.top/Article/details/gtvspifqfi.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.shzxlz.cn/Article/details/gtccjuxnuu.html

[S10] C：指针与解引用
来源：http://dali.yuanzhike.top/Article/details/gtzuxknxmt.html

int *p = &a;  *p = 5;
来源：http://dali.kuanghao11.cn/Article/details/gtwghpgkim.html

[S11] C：逐行读文件
来源：http://dali.sxryk.cn/Article/details/gtcyzccqxx.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.aizwys.cn/Article/details/gtzwdtjyph.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.gotoacloud.top/Article/details/gtrdidewtp.html

fclose(f);
来源：http://dali.zycfv.cn/Article/details/gtrhiwsxxh.html

[S12] C：写文件
来源：http://dali.sufxvd.cn/Article/details/gtvywkazxt.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.jiagoushi.top/Article/details/gtrylnikxx.html

[S13] C：宏定义
来源：http://dali.jlsjyb.cn/Article/details/gtcchmeioq.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.jlsjyb.cn/Article/details/gtsifxxslv.html

[S14] C：枚举
来源：http://dali.havefunace.top/Article/details/gtfgenwkyh.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.hfpthk.cn/Article/details/gthrmijyej.html

[S15] C：类型转换
来源：http://dali.ybcxt.top/Article/details/gtznboabyr.html

(double) a / b
来源：http://dali.dianchejie.cn/Article/details/gtcvtkvwrw.html

[S16] C：位操作置位
来源：http://dali.mhx1999.top/Article/details/gtbjwaxmjk.html

x |= (1 << 3);
来源：http://dali.316326.xyz/Article/details/gtvijimxjn.html

[S17] C：安全拼接字符串
来源：http://dali.ydzc1.top/Article/details/gttfkyasyx.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.nanxuanxn.top/Article/details/gtzrlhjvrw.html

[S18] C：命令行参数
来源：http://dali.havefunace.top/Article/details/gtshngolbo.html

int main(int argc, char **argv)
来源：http://dali.pengpengdd.cyou/Article/details/gtjcfciusv.html

[S19] C：快速排序
来源：http://dali.shanyushiyangtech.top/Article/details/gtbeugkpji.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.xylfe.cn/Article/details/gtjefigqdj.html

[S20] C：二分查找
来源：http://dali.hfpthk.cn/Article/details/gtvvrgicaa.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.jinqigufen.top/Article/details/gtsqlyhktt.html

[S21] C：字符类别判断
来源：http://dali.yuxming.cn/Article/details/gtykbzuyri.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gthvhaorvr.html

[S22] C：字符串转数字
来源：http://dali.chenjidiqi.icu/Article/details/gtukaspufq.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.yueranfly.top/Article/details/gtzgrdqcdb.html

[S23] C：随机数
来源：http://dali.kuanghao11.cn/Article/details/gtcxlifyuj.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gtqupvltjo.html

[S24] C：获取本地时间
来源：http://dali.hongshengwenyu.top/Article/details/gtuajwxypu.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.cheryme.top/Article/details/gtltmikdab.html

[S25] C：内存拷贝
来源：http://dali.9152youxi.cn/Article/details/gtagevdimo.html

memcpy(dst, src, n);
来源：http://dali.cheryme.top/Article/details/gtxwvuquzq.html

[S26] C：内存清零
来源：http://dali.hysaishi.cn/Article/details/gtebxdsepf.html

memset(a, 0, sizeof a);
来源：http://dali.zhoulong.xyz/Article/details/gtfixnruhd.html

[S27] C：定义常量
来源：http://dali.chenjidiqi.icu/Article/details/gtyjbyfael.html

const double PI = 3.14159;
来源：http://dali.zdqjudy.top/Article/details/gtqbeukdwp.html

[S28] C：静态变量
来源：http://dali.chenzaomai.com/Article/details/gtxrqbywer.html

static int counter = 0;
来源：http://dali.hfpthk.cn/Article/details/gtdlpucxjb.html

[S29] C：变参函数
来源：http://dali.zhengqikj.top/Article/details/gtxgffyjpc.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.redwolf501.top/Article/details/gtiwfxmpxg.html

[S30] C：头文件保护
来源：http://dali.jinqigufen.top/Article/details/gtsjxtlmqn.html

#ifndef X_H
来源：http://dali.yuxming.cn/Article/details/gtbwkcdzoe.html

#define X_H
来源：http://dali.jianghu66.top/Article/details/gtzpitmjpq.html

#endif
来源：http://dali.fzhhl.top/Article/details/gtukqvyepq.html

[S31] C++：Hello World
来源：http://dali.tanke756.top/Article/details/gthvqmzawj.html

#include <iostream>
来源：http://dali.gogol.net.cn/Article/details/gtkainkxzq.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.gotoacloud.top/Article/details/gtjlkahgvb.html

[S32] C++：字符串
来源：http://dali.pengpengdd.cyou/Article/details/gtltiiqifo.html

std::string s = "hi";  s += "!";
来源：http://dali.yueranfly.top/Article/details/gtrtgtnsni.html

[S33] C++：vector 增删
来源：http://dali.chenjidiqi.icu/Article/details/gtcxcxptyr.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.nanxuanxn.top/Article/details/gtruljmnts.html

[S34] C++：遍历 vector
来源：http://dali.c1oappe.top/Article/details/gtqpedbfax.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.jinqigfzy.top/Article/details/gtlkkrhcaq.html

[S35] C++：map
来源：http://dali.jianghu66.top/Article/details/gtrklsdgwo.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.gzhubu.top/Article/details/gtkdubxuhf.html

[S36] C++：unordered_map
来源：http://dali.kuanghao11.cn/Article/details/gtgzndonbm.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.meibo888.top/Article/details/gtqsnmpktm.html

[S37] C++：set
来源：http://dali.hywenlv.cn/Article/details/gtbjnurawe.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.gzhubu.top/Article/details/gtunhblcnt.html

[S38] C++：排序
来源：http://dali.dianchejie.cn/Article/details/gtaztfidyj.html

std::sort(v.begin(), v.end());
来源：http://dali.shzxlz.cn/Article/details/gtmlacsmwq.html

[S39] C++：自定义比较器排序
来源：http://dali.ydzc1.top/Article/details/gtopwsdgap.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.jlsjyb.cn/Article/details/gtmjnfimzr.html

[S40] C++：查找元素
来源：http://dali.xuetiantiany.cn/Article/details/gtlexpgdyb.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.xinyue.icu/Article/details/gtadsvezpu.html

[S41] C++：类与构造函数
来源：http://dali.shuidangran.top/Article/details/gtzswzawoi.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.yonumen.top/Article/details/gtfsxgtary.html

[S42] C++：继承与虚函数
来源：http://dali.jinghuilouyu.cn/Article/details/gtpvrhqzqs.html

class B : public Base { public: void f() override {} };
来源：http://dali.hnqzz.top/Article/details/gthdgbuocw.html

[S43] C++：智能指针
来源：http://dali.tian-w.cn/Article/details/gtxlwhpgdh.html

auto p = std::make_unique<int>(5);
来源：http://dali.pengpengdd.cyou/Article/details/gtgwouwtff.html

[S44] C++：引用传参
来源：http://dali.ydzc1.top/Article/details/gtnmvjnzfb.html

void inc(int &x) { ++x; }
来源：http://dali.aizwys.cn/Article/details/gtguvczera.html

[S45] C++：lambda
来源：http://dali.xylfe.cn/Article/details/gtjzzkpiep.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhongyouzk.top/Article/details/gtxqgnodtv.html

[S46] C++：函数模板
来源：http://dali.nwbrower.top/Article/details/gttrgojpvy.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.sweek.top/Article/details/gtedcmxkqf.html

[S47] C++：结构化绑定遍历
来源：http://dali.hywenlv.cn/Article/details/gtwvesymgm.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.smart0.xyz/Article/details/gtowfukhdq.html

[S48] C++：逐行读文件
来源：http://dali.c1oappe.top/Article/details/gtrfzbswzy.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.jinghuilouyu.cn/Article/details/gtwwibcwho.html

while (std::getline(in, line)) { }
来源：http://dali.mhx1999.top/Article/details/gtnxqzssgk.html

[S49] C++：写文件
来源：http://dali.cheryme.top/Article/details/gtazyjbtje.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.iojbl.cn/Article/details/gtcwxqnbxs.html

[S50] C++：格式化数字
来源：http://dali.jianghu66.top/Article/details/gtfamemrdz.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.tian-w.cn/Article/details/gtrmakwlxc.html

[S51] C++：显式类型转换
来源：http://dali.chenjidiqi.icu/Article/details/gtrhspsbrx.html

static_cast<double>(a) / b
来源：http://dali.sweek.top/Article/details/gtwtitxrdv.html

[S52] C++：const 与 noexcept
来源：http://dali.sufxvd.cn/Article/details/gtilnwawwt.html

int size() const noexcept { return n_; }
来源：http://dali.hysaishi.cn/Article/details/gtiipsqzgi.html

[S53] C++：移动语义
来源：http://dali.birdmap.top/Article/details/gttnwlnsex.html

std::vector<int> w = std::move(v);
来源：http://dali.daria6918.cn/Article/details/gtqbbcsewe.html

[S54] C++：异常处理
来源：http://dali.jinqigufen.top/Article/details/gtgcwsgsks.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.jlsjyb.cn/Article/details/gtsluaymdw.html

[S55] C++：结构化绑定
来源：http://dali.zhongyouzk.top/Article/details/gtfgufvsst.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.jianghu66.top/Article/details/gtdoexrggp.html

[S56] C++：optional
来源：http://dali.mhx1999.top/Article/details/gtflilcdwa.html


<!-- 参考信息 -->