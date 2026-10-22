代发 wailian999

[Q88] 行转列（条件聚合）
来源：http://dali.gaohongyu789.top/Article/details/gt2djeymymu.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.fengsongda.top/Article/details/gt2jhbigjrj.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.cdnleiting.top/Article/details/gt2pqtbgstq.html

[Q89] 判断表是否存在
来源：http://dali.chenlongwang.top/Article/details/gt2mvpuzxjv.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.snrcjt.cn/Article/details/gt2orokbwez.html

[Q90] 生成序号列
来源：http://dali.tanke756.top/Article/details/gt2lizzsuak.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.hfpthk.cn/Article/details/gt2dheqsfup.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2asfokqav.html

R. Bash 专题
来源：http://dali.zhengqikj.top/Article/details/gt2lenfanxa.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gt2xinsuyxa.html

[R01] shebang 与严格模式
来源：http://dali.quarkkingdee.top/Article/details/gt2fejfgdxo.html

#!/usr/bin/env bash
来源：http://dali.cucudq.cn/Article/details/gt2vrdapgzd.html

set -euo pipefail
来源：http://dali.meibo888.top/Article/details/gt2yuoefufk.html

[R02] 变量赋值与使用
来源：http://dali.hywenlv.cn/Article/details/gt2aieduwkj.html

name="Tom"; echo "$name"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mnxqrseh.html

[R03] 只读变量
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hoowjpxz.html

readonly PI=3.14
来源：http://dali.chenzaomai.com/Article/details/gt2mlnawfcb.html

[R04] 位置参数
来源：http://dali.nanxuanxn.top/Article/details/gt2pqthnqwx.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.feifeiyinyue.top/Article/details/gt2rmaqnhwf.html

[R05] 参数默认值
来源：http://dali.316326.xyz/Article/details/gt2sbbokqvs.html

name="${1:-default}"
来源：http://dali.wangshuangyany.cn/Article/details/gt2zncyczgu.html

[R06] 判断命令是否存在
来源：http://dali.9152youxi.cn/Article/details/gt2ftubbfim.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.wangdashe.top/Article/details/gt2vfifnfbc.html

[R07] if 判断文件
来源：http://dali.iojbl.cn/Article/details/gt2whucwgif.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhengqikj.top/Article/details/gt2gkpuwxim.html

[R08] 数值比较
来源：http://dali.mhx1999.top/Article/details/gt2ktzsuwcd.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.shanyushiyangtech.top/Article/details/gt2utdsciwx.html

[R09] 字符串比较
来源：http://dali.haohaochexian.top/Article/details/gt2svnfrwkq.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dauhfriy.html

[R10] 正则匹配
来源：http://dali.nwbrower.top/Article/details/gt2qfgizxba.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.birdmap.top/Article/details/gt2allukmeo.html

[R11] case 多分支
来源：http://dali.xuanzx.com/Article/details/gt2ibvzedur.html

case "$1" in
来源：http://dali.svipenyu.cn/Article/details/gt2eflakmix.html

start) echo "启动" ;;
来源：http://dali.feifeiyinyue.top/Article/details/gt2jvkuycpp.html

stop)  echo "停止" ;;
来源：http://dali.chenzaomai.com/Article/details/gt2ogbdzxii.html

*)     echo "未知命令" ;;
来源：http://dali.daxiang520.top/Article/details/gt2orosbkqm.html

esac
来源：http://dali.cdnleiting.top/Article/details/gt2mtursgym.html

[R12] for 遍历文件
来源：http://dali.dianchejie.cn/Article/details/gt2fbzgvkqv.html

for f in *.txt; do echo "$f"; done
来源：http://dali.haohaochexian.top/Article/details/gt2qnkvseuk.html

[R13] for 计数循环
来源：http://dali.cashguo.top/Article/details/gt2ubbgvnln.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.9152youxi.cn/Article/details/gt2kuukeysd.html

[R14] C 风格 for
来源：http://dali.0kj1m.cn/Article/details/gt2uuyifhma.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.daria6918.cn/Article/details/gt2psjuabsj.html

[R15] while 逐行读文件
来源：http://dali.zycfv.cn/Article/details/gt2qtfyazse.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.cucudq.cn/Article/details/gt2amkugcpw.html

[R16] until 等待条件
来源：http://dali.zhoulong.xyz/Article/details/gt2gjvudphh.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.tian-w.cn/Article/details/gt2ajkfsgtb.html

[R17] 数组定义与取值
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ceubrgkk.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.guannengcc.top/Article/details/gt2ifowqkoy.html

[R18] 遍历数组
来源：http://dali.yj202588.top/Article/details/gt2jsyzbbwh.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.gogol.net.cn/Article/details/gt2xujdebrq.html

[R19] 数组长度
来源：http://dali.hywenlv.cn/Article/details/gt2ilwjyaat.html

echo "${#arr[@]}"
来源：http://dali.havefunace.top/Article/details/gt2ypxnkthp.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2cjuiktba.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhengqikj.top/Article/details/gt2qfgjkqap.html

[R21] 字符串长度
来源：http://dali.meibo888.top/Article/details/gt2xqvtnsrw.html

echo "${#s}"
来源：http://dali.snrcjt.cn/Article/details/gt2fmqoexxn.html

[R22] 截取子串
来源：http://dali.guowangkeji.top/Article/details/gt2cknyenrx.html

echo "${s:0:5}"
来源：http://dali.tianlin.xyz/Article/details/gt2sbevywgg.html

[R23] 字符串替换
来源：http://dali.gaohongyu789.top/Article/details/gt2dnepsbjd.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.cashguo.top/Article/details/gt2ecruutkj.html

[R24] 大小写转换
来源：http://dali.zhoulong.xyz/Article/details/gt2yexlycyv.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zycfv.cn/Article/details/gt2nlwpuqpy.html

[R25] 去后缀 / 去前缀
来源：http://dali.shuidangran.top/Article/details/gt2zgsrqxro.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.yj20258888.top/Article/details/gt2fgbrqivu.html

[R26] 命令替换
来源：http://dali.tianlin.xyz/Article/details/gt2wszfcyku.html

now=$(date +%F); echo "$now"
来源：http://dali.gotoacloud.top/Article/details/gt2amzlviyz.html

[R27] 算术展开
来源：http://dali.nanxinkj.top/Article/details/gt2ocnvucdj.html

echo $((1 + 2 * 3))
来源：http://dali.zycfv.cn/Article/details/gt2zzcytegc.html

[R28] 浮点运算
来源：http://dali.ppjwa.cn/Article/details/gt2puevxmhl.html

echo "scale=2; 10/3" | bc
来源：http://dali.gotoacloud.top/Article/details/gt2hgaidhel.html

[R29] 定义函数
来源：http://dali.zhixingplan.top/Article/details/gt2syeusher.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.dianchejie.cn/Article/details/gt2lmvjqnnm.html

[R30] 函数返回状态码
来源：http://dali.hnxiangtu.top/Article/details/gt2xnqzmhkq.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.cqqwz.cn/Article/details/gt2puqbybwd.html

[R31] 局部变量
来源：http://dali.chenjidiqi.icu/Article/details/gt2xmtfywsm.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qtjhslvc.html

[R32] 参数个数校验
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2aztvjmeb.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.fzhhl.top/Article/details/gt2lujgfsgx.html

[R33] 捕获错误并提示行号
来源：http://dali.pycfn.com/Article/details/gt2cbxobain.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.yanxiufei.cn/Article/details/gt2dgcxymib.html

[R34] 退出时清理
来源：http://dali.yanxiufei.cn/Article/details/gt2kocoihtm.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2chhnaehw.html

[R35] 后台执行并等待
来源：http://dali.316326.xyz/Article/details/gt2jukrmwqz.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.yuxming.cn/Article/details/gt2zeprhfiy.html

[R36] 并发执行多个任务
来源：http://dali.wangshuangyany.cn/Article/details/gt2zgaoanit.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.cheryme.top/Article/details/gt2cnlnzxio.html

[R37] 把输出赋给变量
来源：http://dali.aibaodan.cn/Article/details/gt2zhrmtzzu.html

files=$(ls -1)
来源：http://dali.shuidangran.top/Article/details/gt2bqwbvihi.html

[R38] 管道串联
来源：http://dali.bjfxy.top/Article/details/gt2iytnoewa.html

cat a.txt | grep -i error | wc -l
来源：http://dali.hnqzz.top/Article/details/gt2nxbgdiac.html

[R39] 重定向标准输出与错误
来源：http://dali.zhoulong.xyz/Article/details/gt2ebcmegvb.html

cmd > out.log 2>&1
来源：http://dali.jianghu66.top/Article/details/gt2gxkstgvk.html

[R40] 追加写日志
来源：http://dali.zycfv.cn/Article/details/gt2qmenetnn.html

echo "log" >> out.log
来源：http://dali.smart0.xyz/Article/details/gt2jtowijfz.html

[R41] 丢弃输出
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ltzrepkh.html

cmd >/dev/null 2>&1
来源：http://dali.xylfe.cn/Article/details/gt2ydcrjhlb.html

[R42] 输入重定向
来源：http://dali.chenjidiqi.icu/Article/details/gt2bjovzcsg.html

wc -l < a.txt
来源：http://dali.gotoacloud.top/Article/details/gt2vaovlejo.html

[R43] 按名字查找文件
来源：http://dali.316326.xyz/Article/details/gt2mdmlpgbe.html

find . -name "*.log" -type f
来源：http://dali.shuidangran.top/Article/details/gt2jouxlccz.html

[R44] 按修改时间查找
来源：http://dali.9152youxi.cn/Article/details/gt2xwoeawqy.html

find . -mtime -7 -type f
来源：http://dali.daxiang520.top/Article/details/gt2ccgtlvyx.html

[R45] 批量删除
来源：http://dali.xinyue.icu/Article/details/gt2prryypla.html

find . -name "*.tmp" -delete
来源：http://dali.jiagoushi.top/Article/details/gt2wchkxgcr.html

[R46] 递归替换文件内容
来源：http://dali.yonumen.top/Article/details/gt2sfxurijt.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.chenjidiqi.icu/Article/details/gt2loqghjcj.html

[R47] sed 单行替换
来源：http://dali.birdmap.top/Article/details/gt2hzyosqsl.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.yj202588.top/Article/details/gt2aoiuislk.html

[R48] awk 取指定列
来源：http://dali.fzhhl.top/Article/details/gt2splydbqp.html

awk '{print $1, $3}' a.txt
来源：http://dali.aibaodan.cn/Article/details/gt2bmblkpfx.html

[R49] awk 带条件
来源：http://dali.ehwqpu.com/Article/details/gt2vqufhgqv.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.tianlin.xyz/Article/details/gt2udqyhmeq.html

[R50] awk 求和
来源：http://dali.jinqigufen.top/Article/details/gt2htgurito.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.hfpthk.cn/Article/details/gt2jjmpxodc.html

[R51] 排序去重取前几
来源：http://dali.daxiang520.top/Article/details/gt2lnbrpxux.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.feifeiyinyue.top/Article/details/gt2tqaqaanp.html

[R52] 统计行数
来源：http://dali.fzhhl.top/Article/details/gt2utlzdjmh.html

wc -l a.txt
来源：http://dali.daria6918.cn/Article/details/gt2mffyafjo.html

[R53] 查看文件头与实时尾
来源：http://dali.fzhhl.top/Article/details/gt2kmxrxwys.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.0kj1m.cn/Article/details/gt2vdxaeqex.html

[R54] 比较两个文件
来源：http://dali.cashguo.top/Article/details/gt2tvukqulj.html

diff a.txt b.txt
来源：http://dali.nwbrower.top/Article/details/gt2zpftsnet.html

[R55] 压缩与解压
来源：http://dali.svipenyu.cn/Article/details/gt2azzawetf.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jydpfnet.html

[R56] 远程拷贝
来源：http://dali.hywenlv.cn/Article/details/gt2abzwbzzn.html

scp file user@host:/path/
来源：http://dali.xziqi.cn/Article/details/gt2zcnrilbz.html

[R57] 远程执行命令
来源：http://dali.jianghu66.top/Article/details/gt2xwqvbwsw.html

ssh user@host 'uptime'
来源：http://dali.hongshengwenyu.top/Article/details/gt2qonyldzm.html

[R58] 下载文件
来源：http://dali.sweek.top/Article/details/gt2nyluljpa.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.kuanghao11.cn/Article/details/gt2oxaqkxfx.html

[R59] 发 POST JSON
来源：http://dali.hywenlv.cn/Article/details/gt2qnkwcjvn.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.smart0.xyz/Article/details/gt2mcdtqpiy.html

[R60] 只看 HTTP 状态码
来源：http://dali.tian-w.cn/Article/details/gt2xqrmumpb.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.dianchejie.cn/Article/details/gt2rxrdsoat.html

[R61] 磁盘占用
来源：http://dali.hnqzz.top/Article/details/gt2ruehahvy.html

df -h;  du -sh *
来源：http://dali.jqgufenzy.top/Article/details/gt2hrqpiizg.html

[R62] 找最占空间的文件
来源：http://dali.iojbl.cn/Article/details/gt2nqgcntxn.html

du -ah . | sort -rh | head -10
来源：http://dali.mhx1999.top/Article/details/gt2hgiymbap.html

[R63] 内存与进程
来源：http://dali.yonumen.top/Article/details/gt2nijzihpk.html

free -h;  ps aux | grep nginx
来源：http://dali.bjfxy.top/Article/details/gt2mtokgchb.html

[R64] 结束进程
来源：http://dali.jlsjyb.cn/Article/details/gt2riwswcme.html

kill -9 $(pgrep -f app.py)
来源：http://dali.fzhhl.top/Article/details/gt2rffvznoe.html

[R65] 查看端口占用
来源：http://dali.pengpengdd.cyou/Article/details/gt2jpknhigd.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.c1oappe.top/Article/details/gt2xkukxhnf.html

[R66] 定时任务
来源：http://dali.cucudq.cn/Article/details/gt2wydwcitw.html

crontab -e;  crontab -l
来源：http://dali.ybcxt.top/Article/details/gt2jcpwgnmf.html

[R67] 生成随机十六进制串
来源：http://dali.xziqi.cn/Article/details/gt2alxpdvpu.html

openssl rand -hex 16
来源：http://dali.zhoulong.xyz/Article/details/gt2lflgtnwi.html

[R68] 计算文件校验值
来源：http://dali.vqdsnc.cn/Article/details/gt2tpfehzqi.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.vqdsnc.cn/Article/details/gt2kjwgofks.html

[R69] 生成随机密码
来源：http://dali.yonumen.top/Article/details/gt2tckvlkbg.html

head -c 16 /dev/urandom | base64
来源：http://dali.andypj.xyz/Article/details/gt2zwjbdvty.html

[R70] 时间戳与互转
来源：http://dali.wangdashe.top/Article/details/gt2rizueyto.html

date +%s;  date -d @1700000000
来源：http://dali.cqqwz.cn/Article/details/gt2xhemevxz.html

[R71] 日期格式化
来源：http://dali.hongshengwenyu.top/Article/details/gt2vhxhvrhy.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.cheryme.top/Article/details/gt2izfhenlj.html

[R72] 等待端口就绪
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wpaqctcq.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.jqgufenzy.top/Article/details/gt2ifuxcymu.html

[R73] 分割大日志
来源：http://dali.tian-w.cn/Article/details/gt2vofifqdd.html

split -l 1000 big.log part_
来源：http://dali.hnqzz.top/Article/details/gt2pztejgrr.html

[R74] 批量重命名
来源：http://dali.yonumen.top/Article/details/gt2tqftxojw.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.havefunace.top/Article/details/gt2zimefohs.html

[R75] 导出环境变量
来源：http://dali.zdqjudy.top/Article/details/gt2rdgjwmqr.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dgwojzii.html

[R76] 使用临时文件
来源：http://dali.shuidangran.top/Article/details/gt2zlibmdhe.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.yanxiufei.cn/Article/details/gt2xofojdgb.html

[R77] 读取用户输入
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xxsjthrh.html

read -rp "请输入: " ans
来源：http://dali.gzhubu.top/Article/details/gt2xcdigdxx.html

[R78] 交互式菜单
来源：http://dali.yangfankeji.com/Article/details/gt2ddbppufk.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.xylfe.cn/Article/details/gt2ccjigoyv.html

[R79] 解析命令行选项
来源：http://dali.daxiang520.top/Article/details/gt2tokcasgs.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.kuanghao11.cn/Article/details/gt2ilgpehow.html

[R80] 查看脚本执行耗时
来源：http://dali.gogol.net.cn/Article/details/gt2mxjkbqef.html

time ./run.sh
来源：http://dali.feifeiyinyue.top/Article/details/gt2vfijhtuo.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gt2zjzvrulg.html

S. C / C++ 专题
来源：http://dali.ybcxt.top/Article/details/gt2dmprufrk.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gt2cnenfdcc.html

[S01] C：Hello World
来源：http://dali.gotoacloud.top/Article/details/gt2qvibyykn.html

#include <stdio.h>
来源：http://dali.hywenlv.cn/Article/details/gt2fiqdbnqp.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fuwmszyg.html

[S02] C：变量与格式化输出
来源：http://dali.yanxiufei.cn/Article/details/gt2rsvkxsjr.html

int a = 10; printf("%d\n", a);
来源：http://dali.fengsongda.top/Article/details/gt2bavpeegh.html

[S03] C：读入整数
来源：http://dali.havefunace.top/Article/details/gt2ysorftii.html

int x; scanf("%d", &x);
来源：http://dali.hywenlv.cn/Article/details/gt2jnlzhvnq.html

[S04] C：字符串复制
来源：http://dali.sufxvd.cn/Article/details/gt2iktkyzcs.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.yvedp.cn/Article/details/gt2ejbzttqg.html

[S05] C：字符串长度
来源：http://dali.gzhubu.top/Article/details/gt2lfuylzgb.html

strlen(s)
来源：http://dali.sxryk.cn/Article/details/gt2wrobnhqs.html

[S06] C：字符串比较
来源：http://dali.9152youxi.cn/Article/details/gt2ljinxcfh.html

strcmp(a, b) == 0
来源：http://dali.yj20258.top/Article/details/gt2rjfrakjt.html

[S07] C：数组遍历求和
来源：http://dali.gotoacloud.top/Article/details/gt2vqtpyigj.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.xuanzx.com/Article/details/gt2mvuhmcba.html

[S08] C：动态内存分配与释放
来源：http://dali.yueranfly.top/Article/details/gt2mjuhjtpz.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.gotoacloud.top/Article/details/gt2sypjjzrz.html

[S09] C：结构体定义与初始化
来源：http://dali.ehwqpu.com/Article/details/gt2lbwaqvyk.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.cucudq.cn/Article/details/gt2kegehjbw.html

[S10] C：指针与解引用
来源：http://dali.daxiang520.top/Article/details/gt2chbfmngv.html

int *p = &a;  *p = 5;
来源：http://dali.zycfv.cn/Article/details/gt2gqntcpcd.html

[S11] C：逐行读文件
来源：http://dali.yongpay.top/Article/details/gt2rjnmgfhi.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.yvedp.cn/Article/details/gt2pffkplgb.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.chenjidiqi.icu/Article/details/gt2mpbvbjut.html

fclose(f);
来源：http://dali.ehwqpu.com/Article/details/gt2vmfxzeab.html

[S12] C：写文件
来源：http://dali.jyoumei.cn/Article/details/gt2zfhcsbtr.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.yj20258888.top/Article/details/gt2bbqecccp.html

[S13] C：宏定义
来源：http://dali.jiagoushi.top/Article/details/gt2ewaaszbf.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.shangyingyoupin.top/Article/details/gt2eewfqxwc.html

[S14] C：枚举
来源：http://dali.yonumen.top/Article/details/gt2zyngkvnn.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.feifeiyinyue.top/Article/details/gt2mzzxmgwn.html

[S15] C：类型转换
来源：http://dali.hfpthk.cn/Article/details/gt2cjlbkamo.html

(double) a / b
来源：http://dali.smart0.xyz/Article/details/gt2hrssecpq.html

[S16] C：位操作置位
来源：http://dali.hnxiangtu.top/Article/details/gt2cztnnsig.html

x |= (1 << 3);
来源：http://dali.nwbrower.top/Article/details/gt2wuacqtke.html

[S17] C：安全拼接字符串
来源：http://dali.guowangkeji.top/Article/details/gt2bvcsztnv.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.bjfxy.top/Article/details/gt2ivjcjrfz.html

[S18] C：命令行参数
来源：http://dali.xylfe.cn/Article/details/gt2wyqfkjcn.html

int main(int argc, char **argv)
来源：http://dali.yj20258888.top/Article/details/gt2rbmmvxkn.html

[S19] C：快速排序
来源：http://dali.gzhubu.top/Article/details/gt2ywvljeuo.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.ybcxt.top/Article/details/gt2caehegpr.html

[S20] C：二分查找
来源：http://dali.yuanzhike.top/Article/details/gt2cgbjiwwy.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.nanxinkj.top/Article/details/gt2byjzpkcx.html

[S21] C：字符类别判断
来源：http://dali.tanke756.top/Article/details/gt2hwgqsvnm.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.c1oappe.top/Article/details/gt2wgubgkjt.html

[S22] C：字符串转数字
来源：http://dali.jiagoushi.top/Article/details/gt2navibrbc.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.havefunace.top/Article/details/gt2modzihhc.html

[S23] C：随机数
来源：http://dali.snrcjt.cn/Article/details/gt2axlujksj.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.yanxiufei.cn/Article/details/gt2fyyzkqmx.html

[S24] C：获取本地时间
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qsrnteml.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.cqqwz.cn/Article/details/gt2focbnhci.html

[S25] C：内存拷贝
来源：http://dali.cucudq.cn/Article/details/gt2hzvsevdu.html

memcpy(dst, src, n);
来源：http://dali.chenjidiqi.icu/Article/details/gt2hqwvnrfs.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2mqnmxjsu.html

memset(a, 0, sizeof a);
来源：http://dali.cashguo.top/Article/details/gt2ahwxhwpf.html

[S27] C：定义常量
来源：http://dali.zhengqikj.top/Article/details/gt2mbyqthef.html

const double PI = 3.14159;
来源：http://dali.zhixingplan.top/Article/details/gt2kzosobpf.html

[S28] C：静态变量
来源：http://dali.hysaishi.cn/Article/details/gt2wnntbvtz.html

static int counter = 0;
来源：http://dali.shangyingyoupin.top/Article/details/gt2dndrbzsy.html

[S29] C：变参函数
来源：http://dali.ppjwa.cn/Article/details/gt2jtmqdjwx.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.xziqi.cn/Article/details/gt2zohmznsp.html

[S30] C：头文件保护
来源：http://dali.jinqigufen.top/Article/details/gt2wgibdzjm.html

#ifndef X_H
来源：http://dali.fengsongda.top/Article/details/gt2mdrljptp.html

#define X_H
来源：http://dali.sxryk.cn/Article/details/gt2swtrbhnx.html

#endif
来源：http://dali.aibaodan.cn/Article/details/gt2wpwxwtqh.html

[S31] C++：Hello World
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2odewtjqu.html

#include <iostream>
来源：http://dali.jinghuilouyu.cn/Article/details/gt2oikevqul.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.ehwqpu.com/Article/details/gt2cgnhrcse.html

[S32] C++：字符串
来源：http://dali.gogol.net.cn/Article/details/gt2evcqtank.html

std::string s = "hi";  s += "!";
来源：http://dali.hnxiangtu.top/Article/details/gt2bdifuepu.html

[S33] C++：vector 增删
来源：http://dali.shuidangran.top/Article/details/gt2fdiktjep.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rjglyjdf.html

[S34] C++：遍历 vector
来源：http://dali.hnqzz.top/Article/details/gt2svjehlem.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.guowangkeji.top/Article/details/gt2dhikweym.html

[S35] C++：map
来源：http://dali.cucudq.cn/Article/details/gt2qyswcnoj.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dgyyudzl.html

[S36] C++：unordered_map
来源：http://dali.svipenyu.cn/Article/details/gt2fddtemxe.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.mhx1999.top/Article/details/gt2zolkxlvz.html

[S37] C++：set
来源：http://dali.yj202588.top/Article/details/gt2gvjhqnta.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.kuanghao11.cn/Article/details/gt2vtjijgpm.html

[S38] C++：排序
来源：http://dali.ydzc1.top/Article/details/gt2uhrjrixc.html

std::sort(v.begin(), v.end());
来源：http://dali.tian-w.cn/Article/details/gt2djmmzoxr.html

[S39] C++：自定义比较器排序
来源：http://dali.pycfn.com/Article/details/gt2esxtaxhy.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.ybcxt.top/Article/details/gt2ohbdbnnh.html

[S40] C++：查找元素
来源：http://dali.dianchejie.cn/Article/details/gt2itsqihsn.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ssqyotxx.html

[S41] C++：类与构造函数
来源：http://dali.chenlongwang.top/Article/details/gt2oiufbfhl.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.sufxvd.cn/Article/details/gt2zkblpmpz.html

[S42] C++：继承与虚函数
来源：http://dali.316326.xyz/Article/details/gt2zwhoeoef.html

class B : public Base { public: void f() override {} };
来源：http://dali.yueranfly.top/Article/details/gt2vskfjccn.html

[S43] C++：智能指针
来源：http://dali.9152youxi.cn/Article/details/gt2mgptylvm.html

auto p = std::make_unique<int>(5);
来源：http://dali.yj202588.top/Article/details/gt2efkbwrcy.html

[S44] C++：引用传参
来源：http://dali.ivvv.top/Article/details/gt2xwppsedb.html

void inc(int &x) { ++x; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ificlnmq.html

[S45] C++：lambda
来源：http://dali.snrcjt.cn/Article/details/gt2gjukekvy.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dcdojkmg.html

[S46] C++：函数模板
来源：http://dali.yueranfly.top/Article/details/gt2glrdkplr.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gonhhqll.html

[S47] C++：结构化绑定遍历
来源：http://dali.yj20258888.top/Article/details/gt2fexlzkic.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rfodqsiq.html

[S48] C++：逐行读文件
来源：http://dali.guowangkeji.top/Article/details/gt2skhihhts.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.jlsjyb.cn/Article/details/gt2ynyamoyp.html

while (std::getline(in, line)) { }
来源：http://dali.316326.xyz/Article/details/gt2lylslxrs.html

[S49] C++：写文件
来源：http://dali.yonumen.top/Article/details/gt2kqswselc.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.yj20258888.top/Article/details/gt2nybiyoea.html

[S50] C++：格式化数字
来源：http://dali.jianghu66.top/Article/details/gt2aulkizxu.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.jianghu66.top/Article/details/gt2ygwstepu.html

[S51] C++：显式类型转换
来源：http://dali.tianlin.xyz/Article/details/gt2hcyypmog.html

static_cast<double>(a) / b
来源：http://dali.shzxlz.cn/Article/details/gt2ytjhalfv.html

[S52] C++：const 与 noexcept
来源：http://dali.ydzc1.top/Article/details/gt2vjvjkvdh.html

int size() const noexcept { return n_; }
来源：http://dali.cdnleiting.top/Article/details/gt2zdhehlkz.html

[S53] C++：移动语义
来源：http://dali.meibo888.top/Article/details/gt2kuqqdlec.html

std::vector<int> w = std::move(v);
来源：http://dali.hongshengwenyu.top/Article/details/gt2pbmmvzwa.html

[S54] C++：异常处理
来源：http://dali.kuanghao11.cn/Article/details/gt2nyjhvsmz.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.yj202588.top/Article/details/gt2vgiefkbm.html

[S55] C++：结构化绑定
来源：http://dali.chenlongwang.top/Article/details/gt2jilxcdxl.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.birdmap.top/Article/details/gt2xderfggu.html

[S56] C++：optional
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dbaumakj.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.jinqigfzy.top/Article/details/gt2mvnebpek.html

[S57] C++：编译期常量
来源：http://dali.yuanzhike.top/Article/details/gt2guwjjjdx.html

constexpr int N = 10;
来源：http://dali.jyoumei.cn/Article/details/gt2cscwreid.html

[S58] C++：命名空间
来源：http://dali.jyoumei.cn/Article/details/gt2oxlvbesu.html


<!-- 参考信息 -->