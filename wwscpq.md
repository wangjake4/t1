代发 wailian999

[Q88] 行转列（条件聚合）
来源：http://dali.hfpthk.cn/Article/details/gtiihxtsdv.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.cqqwz.cn/Article/details/gtbxkrswkc.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gtguzjyckt.html

[Q89] 判断表是否存在
来源：http://dali.jianghu66.top/Article/details/gtyonehgup.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.gogol.net.cn/Article/details/gtelwdccvr.html

[Q90] 生成序号列
来源：http://dali.svipenyu.cn/Article/details/gttkdckzsv.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.kuanghao11.cn/Article/details/gtddypagrs.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gttoztnqmr.html

R. Bash 专题
来源：http://dali.yj20258.top/Article/details/gtnlbfnfrt.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gthkmwdpmh.html

[R01] shebang 与严格模式
来源：http://dali.aibaodan.cn/Article/details/gtdcdaoido.html

#!/usr/bin/env bash
来源：http://dali.c1oappe.top/Article/details/gtgvpzrhql.html

set -euo pipefail
来源：http://dali.yanxiufei.cn/Article/details/gtyykugpre.html

[R02] 变量赋值与使用
来源：http://dali.zhongyouzk.top/Article/details/gtupmkrtwv.html

name="Tom"; echo "$name"
来源：http://dali.fengsongda.top/Article/details/gteoeghftb.html

[R03] 只读变量
来源：http://dali.cashguo.top/Article/details/gtlooerihi.html

readonly PI=3.14
来源：http://dali.yuanzhike.top/Article/details/gtrcwgicsr.html

[R04] 位置参数
来源：http://dali.chenjidiqi.icu/Article/details/gtufloyynq.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.daxiang520.top/Article/details/gtilgjhflq.html

[R05] 参数默认值
来源：http://dali.jqgufenzy.top/Article/details/gtikqvzbji.html

name="${1:-default}"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdssanpvn.html

[R06] 判断命令是否存在
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqfaxiuku.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhengqikj.top/Article/details/gtqctkyadj.html

[R07] if 判断文件
来源：http://dali.chenjidiqi.icu/Article/details/gtlswqvglr.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.cheryme.top/Article/details/gtaexmwlku.html

[R08] 数值比较
来源：http://dali.cqqwz.cn/Article/details/gtyedfihfd.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.haohaochexian.top/Article/details/gtkkkwowve.html

[R09] 字符串比较
来源：http://dali.yj20258888.top/Article/details/gtdmiwfqjq.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjqkrupgd.html

[R10] 正则匹配
来源：http://dali.gotoacloud.top/Article/details/gtnphulteg.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.nanxuanxn.top/Article/details/gtmprvlxvp.html

[R11] case 多分支
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdooridoy.html

case "$1" in
来源：http://dali.nanxuanxn.top/Article/details/gtfkjoozaz.html

start) echo "启动" ;;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyvbzccle.html

stop)  echo "停止" ;;
来源：http://dali.yongpay.top/Article/details/gtlbcwnihb.html

*)     echo "未知命令" ;;
来源：http://dali.haohaochexian.top/Article/details/gtqdcjradb.html

esac
来源：http://dali.c1oappe.top/Article/details/gtqjtzkjmf.html

[R12] for 遍历文件
来源：http://dali.sysykeji.top/Article/details/gtenrjqdym.html

for f in *.txt; do echo "$f"; done
来源：http://dali.yonumen.top/Article/details/gtngdejhvi.html

[R13] for 计数循环
来源：http://dali.birdmap.top/Article/details/gtfnoigtgi.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.fengsongda.top/Article/details/gtkssgarge.html

[R14] C 风格 for
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtssmgxxwr.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhoulong.xyz/Article/details/gtrmvjvtyc.html

[R15] while 逐行读文件
来源：http://dali.yanxiufei.cn/Article/details/gtnflxzqxl.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.cucudq.cn/Article/details/gtqutspeat.html

[R16] until 等待条件
来源：http://dali.cucudq.cn/Article/details/gtsizthdyy.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.hnxiangtu.top/Article/details/gtcpqpboox.html

[R17] 数组定义与取值
来源：http://dali.feifeiyinyue.top/Article/details/gtctlaemgp.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.ehwqpu.com/Article/details/gtnunckroa.html

[R18] 遍历数组
来源：http://dali.xinyue.icu/Article/details/gtarbqbozq.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.316326.xyz/Article/details/gtpcsbvknu.html

[R19] 数组长度
来源：http://dali.wangshuangyany.cn/Article/details/gtgdmzsdqg.html

echo "${#arr[@]}"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnropaznv.html

[R20] 关联数组（字典）
来源：http://dali.jinghuilouyu.cn/Article/details/gtqjwrhcqu.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.sxryk.cn/Article/details/gtryaifhqx.html

[R21] 字符串长度
来源：http://dali.wangshuangyany.cn/Article/details/gtkjhjighn.html

echo "${#s}"
来源：http://dali.zhixingplan.top/Article/details/gtcureclsd.html

[R22] 截取子串
来源：http://dali.wangshuangyany.cn/Article/details/gtzogrgctu.html

echo "${s:0:5}"
来源：http://dali.nanxinkj.top/Article/details/gtugzolbom.html

[R23] 字符串替换
来源：http://dali.xylfe.cn/Article/details/gtzyfaupfn.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.iojbl.cn/Article/details/gterzumgzu.html

[R24] 大小写转换
来源：http://dali.gogol.net.cn/Article/details/gttbicplzi.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.chenzaomai.com/Article/details/gtbljdprzu.html

[R25] 去后缀 / 去前缀
来源：http://dali.jianghu66.top/Article/details/gtrqkgqezf.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.hnqzz.top/Article/details/gtzhcjhmao.html

[R26] 命令替换
来源：http://dali.haohaochexian.top/Article/details/gtusfbryeg.html

now=$(date +%F); echo "$now"
来源：http://dali.tanke756.top/Article/details/gterxtgrkq.html

[R27] 算术展开
来源：http://dali.ivvv.top/Article/details/gtnsinujzf.html

echo $((1 + 2 * 3))
来源：http://dali.nanxinkj.top/Article/details/gtjgpwpejm.html

[R28] 浮点运算
来源：http://dali.jqgufenzy.top/Article/details/gtqmmymhcm.html

echo "scale=2; 10/3" | bc
来源：http://dali.cucudq.cn/Article/details/gtrmqzbsmk.html

[R29] 定义函数
来源：http://dali.cashguo.top/Article/details/gtenknldln.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.jlsjyb.cn/Article/details/gtjodyramc.html

[R30] 函数返回状态码
来源：http://dali.yueranfly.top/Article/details/gtplzbdrqv.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.shangyingyoupin.top/Article/details/gtunkbuutz.html

[R31] 局部变量
来源：http://dali.ehwqpu.com/Article/details/gtwqczcchq.html

f() { local x=1; echo "$x"; }
来源：http://dali.zdqjudy.top/Article/details/gtfmbcxtsm.html

[R32] 参数个数校验
来源：http://dali.havefunace.top/Article/details/gtwqmnwltv.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.redwolf501.top/Article/details/gtphepwdpq.html

[R33] 捕获错误并提示行号
来源：http://dali.cheryme.top/Article/details/gtddhpmmkw.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.9152youxi.cn/Article/details/gtesrptizw.html

[R34] 退出时清理
来源：http://dali.jinyuanbaomall.cn/Article/details/gtojkksumt.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.redwolf501.top/Article/details/gtbldpjgis.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gtobjrahjr.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.yueranfly.top/Article/details/gtvctbngxo.html

[R36] 并发执行多个任务
来源：http://dali.chenjidiqi.icu/Article/details/gtgmudugpe.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhongyouzk.top/Article/details/gtrzbqkonc.html

[R37] 把输出赋给变量
来源：http://dali.jinqigufen.top/Article/details/gtositmjqj.html

files=$(ls -1)
来源：http://dali.jianghu66.top/Article/details/gtushiandq.html

[R38] 管道串联
来源：http://dali.daxiang520.top/Article/details/gtwqypyquo.html

cat a.txt | grep -i error | wc -l
来源：http://dali.yanxiufei.cn/Article/details/gtuztafyfl.html

[R39] 重定向标准输出与错误
来源：http://dali.cqqwz.cn/Article/details/gtonkvglmq.html

cmd > out.log 2>&1
来源：http://dali.yj202588.top/Article/details/gtvjrqbnvs.html

[R40] 追加写日志
来源：http://dali.0kj1m.cn/Article/details/gtnbbaqybu.html

echo "log" >> out.log
来源：http://dali.xylfe.cn/Article/details/gtymlrdfif.html

[R41] 丢弃输出
来源：http://dali.hnxiangtu.top/Article/details/gtqulfqwcv.html

cmd >/dev/null 2>&1
来源：http://dali.shanyushiyangtech.top/Article/details/gttljiaicr.html

[R42] 输入重定向
来源：http://dali.fengsongda.top/Article/details/gturmabvyp.html

wc -l < a.txt
来源：http://dali.shanyushiyangtech.top/Article/details/gtbasyjnbc.html

[R43] 按名字查找文件
来源：http://dali.fzhhl.top/Article/details/gthciineyq.html

find . -name "*.log" -type f
来源：http://dali.nanxinkj.top/Article/details/gtgiahvxvq.html

[R44] 按修改时间查找
来源：http://dali.xylfe.cn/Article/details/gtybdrmooq.html

find . -mtime -7 -type f
来源：http://dali.havefunace.top/Article/details/gtgxblilav.html

[R45] 批量删除
来源：http://dali.chenlongwang.top/Article/details/gtsxejhmnj.html

find . -name "*.tmp" -delete
来源：http://dali.svipenyu.cn/Article/details/gtiebgmnfq.html

[R46] 递归替换文件内容
来源：http://dali.sxryk.cn/Article/details/gtxcwkvaxo.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.c1oappe.top/Article/details/gtgmtdctjh.html

[R47] sed 单行替换
来源：http://dali.shangyingyoupin.top/Article/details/gtrhfwicqn.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.jlsjyb.cn/Article/details/gtgrqzguxi.html

[R48] awk 取指定列
来源：http://dali.hywenlv.cn/Article/details/gtninmopbg.html

awk '{print $1, $3}' a.txt
来源：http://dali.cashguo.top/Article/details/gtnckzqflx.html

[R49] awk 带条件
来源：http://dali.ppjwa.cn/Article/details/gtscbljeqb.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.hysaishi.cn/Article/details/gtfrwmnjom.html

[R50] awk 求和
来源：http://dali.zhoulong.xyz/Article/details/gtaabgymmd.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.haohaochexian.top/Article/details/gtuzzkpgte.html

[R51] 排序去重取前几
来源：http://dali.sweek.top/Article/details/gtvojbsfwn.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.sxryk.cn/Article/details/gtxutyqtvr.html

[R52] 统计行数
来源：http://dali.jinghuilouyu.cn/Article/details/gtgxuaktux.html

wc -l a.txt
来源：http://dali.hongshengwenyu.top/Article/details/gtoluoibvm.html

[R53] 查看文件头与实时尾
来源：http://dali.sufxvd.cn/Article/details/gtaynwvdvu.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.yongpay.top/Article/details/gtxnwiglmb.html

[R54] 比较两个文件
来源：http://dali.guannengcc.top/Article/details/gtdspyczgn.html

diff a.txt b.txt
来源：http://dali.jinghuilouyu.cn/Article/details/gthjbrcujr.html

[R55] 压缩与解压
来源：http://dali.nanxuanxn.top/Article/details/gtgofsmjfu.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.haohaochexian.top/Article/details/gtmzaoekhf.html

[R56] 远程拷贝
来源：http://dali.tanke756.top/Article/details/gtmvosigyu.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gtxjeyfhgl.html

[R57] 远程执行命令
来源：http://dali.jqgufenzy.top/Article/details/gtzwmpnkzp.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gtrkfoedhh.html

[R58] 下载文件
来源：http://dali.bjfxy.top/Article/details/gtfumxrzjr.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.sxryk.cn/Article/details/gtanywmegx.html

[R59] 发 POST JSON
来源：http://dali.zhoulong.xyz/Article/details/gterhhpeuz.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.redwolf501.top/Article/details/gtonazafkq.html

[R60] 只看 HTTP 状态码
来源：http://dali.gotoacloud.top/Article/details/gtzmybgekj.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.feifeiyinyue.top/Article/details/gtivhmilcx.html

[R61] 磁盘占用
来源：http://dali.redwolf501.top/Article/details/gtutrujtyn.html

df -h;  du -sh *
来源：http://dali.jinqigfzy.top/Article/details/gttocqukin.html

[R62] 找最占空间的文件
来源：http://dali.fengsongda.top/Article/details/gtsmgqqreh.html

du -ah . | sort -rh | head -10
来源：http://dali.nanxinkj.top/Article/details/gtacrlglyc.html

[R63] 内存与进程
来源：http://dali.yvedp.cn/Article/details/gtsaidibwd.html

free -h;  ps aux | grep nginx
来源：http://dali.dianchejie.cn/Article/details/gtdlffukix.html

[R64] 结束进程
来源：http://dali.yj20258.top/Article/details/gtgoseceed.html

kill -9 $(pgrep -f app.py)
来源：http://dali.aibaodan.cn/Article/details/gtiazusqcm.html

[R65] 查看端口占用
来源：http://dali.birdmap.top/Article/details/gtestxtjqe.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.gogol.net.cn/Article/details/gtqjxnzymn.html

[R66] 定时任务
来源：http://dali.dianchejie.cn/Article/details/gtequonsiq.html

crontab -e;  crontab -l
来源：http://dali.daxiang520.top/Article/details/gtrpkwwvss.html

[R67] 生成随机十六进制串
来源：http://dali.sxryk.cn/Article/details/gtciwcstvl.html

openssl rand -hex 16
来源：http://dali.feifeiyinyue.top/Article/details/gtupkdtnev.html

[R68] 计算文件校验值
来源：http://dali.jiagoushi.top/Article/details/gtemzoxoyo.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.jiagoushi.top/Article/details/gthsdpdylk.html

[R69] 生成随机密码
来源：http://dali.zhongyouzk.top/Article/details/gtrtbcmyeg.html

head -c 16 /dev/urandom | base64
来源：http://dali.gzhubu.top/Article/details/gtsctfympc.html

[R70] 时间戳与互转
来源：http://dali.andypj.xyz/Article/details/gtdgzuexnl.html

date +%s;  date -d @1700000000
来源：http://dali.yongpay.top/Article/details/gtqehqzvik.html

[R71] 日期格式化
来源：http://dali.nanxinkj.top/Article/details/gtmwjegwth.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.feifeiyinyue.top/Article/details/gtujhnlbhb.html

[R72] 等待端口就绪
来源：http://dali.vqdsnc.cn/Article/details/gtjuwdiqgf.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.yanxiufei.cn/Article/details/gtxjmbyhqh.html

[R73] 分割大日志
来源：http://dali.cashguo.top/Article/details/gtipfkurbo.html

split -l 1000 big.log part_
来源：http://dali.snrcjt.cn/Article/details/gtrybbwcbp.html

[R74] 批量重命名
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfffkiyxw.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.ydzc1.top/Article/details/gtjsbqoqsg.html

[R75] 导出环境变量
来源：http://dali.yueranfly.top/Article/details/gtxbcqadop.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.andypj.xyz/Article/details/gtfnykkcxc.html

[R76] 使用临时文件
来源：http://dali.zdqjudy.top/Article/details/gtitodfiwv.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.aizwys.cn/Article/details/gtfyhofoug.html

[R77] 读取用户输入
来源：http://dali.chenlongwang.top/Article/details/gtmrfmxuay.html

read -rp "请输入: " ans
来源：http://dali.hongshengwenyu.top/Article/details/gtotiadzer.html

[R78] 交互式菜单
来源：http://dali.xziqi.cn/Article/details/gtmnpvztsw.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.ybcxt.top/Article/details/gtaxbspmbt.html

[R79] 解析命令行选项
来源：http://dali.zhongyouzk.top/Article/details/gtpdycqisi.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhoulong.xyz/Article/details/gtatcofglx.html

[R80] 查看脚本执行耗时
来源：http://dali.ywan-chungtsiang.top/Article/details/gthbhxdhur.html

time ./run.sh
来源：http://dali.tianlin.xyz/Article/details/gturcmcemd.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtdtcxknvy.html

S. C / C++ 专题
来源：http://dali.shangyingyoupin.top/Article/details/gtunmgxgfz.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtjbnarzyi.html

[S01] C：Hello World
来源：http://dali.kuanghao11.cn/Article/details/gtwlikwygx.html

#include <stdio.h>
来源：http://dali.kuanghao11.cn/Article/details/gtibohxiny.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.redwolf501.top/Article/details/gtaqfnjsqt.html

[S02] C：变量与格式化输出
来源：http://dali.tianlin.xyz/Article/details/gtmjmyajil.html

int a = 10; printf("%d\n", a);
来源：http://dali.0kj1m.cn/Article/details/gtqkwctlcz.html

[S03] C：读入整数
来源：http://dali.jinqigufen.top/Article/details/gtoehtrvhw.html

int x; scanf("%d", &x);
来源：http://dali.bjfxy.top/Article/details/gtmnglqfnm.html

[S04] C：字符串复制
来源：http://dali.zhiwuduotai.top/Article/details/gtrjnzlsly.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.kuanghao11.cn/Article/details/gtqcruvzjk.html

[S05] C：字符串长度
来源：http://dali.xuanzx.com/Article/details/gtdbpvcndn.html

strlen(s)
来源：http://dali.ivvv.top/Article/details/gtrtxwbqpw.html

[S06] C：字符串比较
来源：http://dali.shuidangran.top/Article/details/gtqslicqpo.html

strcmp(a, b) == 0
来源：http://dali.chenjidiqi.icu/Article/details/gtlvmwlfre.html

[S07] C：数组遍历求和
来源：http://dali.redwolf501.top/Article/details/gtvehxvfgs.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.hfpthk.cn/Article/details/gtlabtojir.html

[S08] C：动态内存分配与释放
来源：http://dali.ppjwa.cn/Article/details/gtoleljhxv.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.cqqwz.cn/Article/details/gtkbrdbber.html

[S09] C：结构体定义与初始化
来源：http://dali.aizwys.cn/Article/details/gtzcqzdont.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.daria6918.cn/Article/details/gtlbzcdeev.html

[S10] C：指针与解引用
来源：http://dali.kuanghao11.cn/Article/details/gthdgmtskn.html

int *p = &a;  *p = 5;
来源：http://dali.316326.xyz/Article/details/gtpoqmsknf.html

[S11] C：逐行读文件
来源：http://dali.birdmap.top/Article/details/gthzlagcbj.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.meibo888.top/Article/details/gtqwompnfg.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.guannengcc.top/Article/details/gtekribgcb.html

fclose(f);
来源：http://dali.gotoacloud.top/Article/details/gtzgrdmadl.html

[S12] C：写文件
来源：http://dali.fzhhl.top/Article/details/gttakxgeip.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.nwbrower.top/Article/details/gtwxabregy.html

[S13] C：宏定义
来源：http://dali.chenzaomai.com/Article/details/gtnaokxxjm.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.haohaochexian.top/Article/details/gthsjtowda.html

[S14] C：枚举
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsxbholxw.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.sufxvd.cn/Article/details/gtceuknnxx.html

[S15] C：类型转换
来源：http://dali.yueranfly.top/Article/details/gtfzudyciz.html

(double) a / b
来源：http://dali.aibaodan.cn/Article/details/gtetibsbwz.html

[S16] C：位操作置位
来源：http://dali.chenlongwang.top/Article/details/gtzcjcnkrf.html

x |= (1 << 3);
来源：http://dali.jlsjyb.cn/Article/details/gtuncajswj.html

[S17] C：安全拼接字符串
来源：http://dali.nanxuanxn.top/Article/details/gtqxmodilv.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.sweek.top/Article/details/gtfmudojdk.html

[S18] C：命令行参数
来源：http://dali.ehwqpu.com/Article/details/gtbmjdvjtg.html

int main(int argc, char **argv)
来源：http://dali.daria6918.cn/Article/details/gtdybmbhso.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gtzawsovib.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.haohaochexian.top/Article/details/gttnvjothc.html

[S20] C：二分查找
来源：http://dali.chenzaomai.com/Article/details/gtrdkkbtty.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.nwbrower.top/Article/details/gtpliazulc.html

[S21] C：字符类别判断
来源：http://dali.ydzc1.top/Article/details/gturomcgzh.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.aibaodan.cn/Article/details/gthrslxivu.html

[S22] C：字符串转数字
来源：http://dali.gaohongyu789.top/Article/details/gtegfgdcjf.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.yonumen.top/Article/details/gtxacnlqpz.html

[S23] C：随机数
来源：http://dali.cashguo.top/Article/details/gtiehjmehb.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.yj20258888.top/Article/details/gtxheswnih.html

[S24] C：获取本地时间
来源：http://dali.svipenyu.cn/Article/details/gtkxzqtphz.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.redwolf501.top/Article/details/gtotfmfuhb.html

[S25] C：内存拷贝
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnngwrsbs.html

memcpy(dst, src, n);
来源：http://dali.chenzaomai.com/Article/details/gthmdqovpa.html

[S26] C：内存清零
来源：http://dali.0kj1m.cn/Article/details/gtlgguecmg.html

memset(a, 0, sizeof a);
来源：http://dali.yj202588.top/Article/details/gtpthjxnvr.html

[S27] C：定义常量
来源：http://dali.ydzc1.top/Article/details/gtvqrmrzzb.html

const double PI = 3.14159;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzvvjqath.html

[S28] C：静态变量
来源：http://dali.zdqjudy.top/Article/details/gtqzkadezp.html

static int counter = 0;
来源：http://dali.hfpthk.cn/Article/details/gtlgbsgkkw.html

[S29] C：变参函数
来源：http://dali.dianchejie.cn/Article/details/gtfsieqkyw.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.shanyushiyangtech.top/Article/details/gtkgvstufh.html

[S30] C：头文件保护
来源：http://dali.bjfxy.top/Article/details/gtttsyrbwv.html

#ifndef X_H
来源：http://dali.jyoumei.cn/Article/details/gtwegfoyki.html

#define X_H
来源：http://dali.zdqjudy.top/Article/details/gttffhzxxr.html

#endif
来源：http://dali.mhx1999.top/Article/details/gtiwjcahtf.html

[S31] C++：Hello World
来源：http://dali.shzxlz.cn/Article/details/gtqgqhkcxw.html

#include <iostream>
来源：http://dali.shanyushiyangtech.top/Article/details/gtsxgltubd.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.aizwys.cn/Article/details/gthhgwicpn.html

[S32] C++：字符串
来源：http://dali.sysykeji.top/Article/details/gtsgfcxlqj.html

std::string s = "hi";  s += "!";
来源：http://dali.shangyingyoupin.top/Article/details/gtfllugfjj.html

[S33] C++：vector 增删
来源：http://dali.mhx1999.top/Article/details/gtzkswpdqn.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.9152youxi.cn/Article/details/gtsnbmrriq.html

[S34] C++：遍历 vector
来源：http://dali.ydzc1.top/Article/details/gtikzfgowc.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.cqqwz.cn/Article/details/gtbdgbtuqk.html

[S35] C++：map
来源：http://dali.yongpay.top/Article/details/gtodjggtwr.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.gogol.net.cn/Article/details/gtbksqjezv.html

[S36] C++：unordered_map
来源：http://dali.quarkkingdee.top/Article/details/gtyopgvsuw.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yvedp.cn/Article/details/gtvoivqqxq.html

[S37] C++：set
来源：http://dali.shuidangran.top/Article/details/gtsirvrumc.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.nanxuanxn.top/Article/details/gtjaebpsrs.html

[S38] C++：排序
来源：http://dali.shanyushiyangtech.top/Article/details/gtfaiptjbt.html

std::sort(v.begin(), v.end());
来源：http://dali.hongshengwenyu.top/Article/details/gtmccktuuf.html

[S39] C++：自定义比较器排序
来源：http://dali.ivvv.top/Article/details/gttstylafz.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.yueranfly.top/Article/details/gttndayxbh.html

[S40] C++：查找元素
来源：http://dali.daxiang520.top/Article/details/gtanqhsenq.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.ivvv.top/Article/details/gtjmnvaiid.html

[S41] C++：类与构造函数
来源：http://dali.yj202588.top/Article/details/gtumgjnphm.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.aibaodan.cn/Article/details/gtjawjndfl.html

[S42] C++：继承与虚函数
来源：http://dali.jianghu66.top/Article/details/gtsjuuesvj.html

class B : public Base { public: void f() override {} };
来源：http://dali.zdqjudy.top/Article/details/gtnyytoyhh.html

[S43] C++：智能指针
来源：http://dali.meibo888.top/Article/details/gtptafgpzi.html

auto p = std::make_unique<int>(5);
来源：http://dali.yangfankeji.com/Article/details/gtblvpxbcn.html

[S44] C++：引用传参
来源：http://dali.xingfuxueyuan.xyz/Article/details/gturswucvw.html

void inc(int &x) { ++x; }
来源：http://dali.ehwqpu.com/Article/details/gtzxxzevoc.html

[S45] C++：lambda
来源：http://dali.cucudq.cn/Article/details/gtijybenma.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.guowangkeji.top/Article/details/gtgdwticxo.html

[S46] C++：函数模板
来源：http://dali.xylfe.cn/Article/details/gtlcjqqjdh.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.hnqzz.top/Article/details/gtrjgypyfc.html

[S47] C++：结构化绑定遍历
来源：http://dali.haohaochexian.top/Article/details/gtggnxmxud.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.hammf.cn/Article/details/gtomdedezb.html

[S48] C++：逐行读文件
来源：http://dali.yanxiufei.cn/Article/details/gtctdpecuk.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.snrcjt.cn/Article/details/gtkxyjzwni.html

while (std::getline(in, line)) { }
来源：http://dali.nwbrower.top/Article/details/gtdsbbtqnh.html

[S49] C++：写文件
来源：http://dali.sweek.top/Article/details/gtnflewlxu.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.hnxiangtu.top/Article/details/gtxxnhbipa.html

[S50] C++：格式化数字
来源：http://dali.daxiang520.top/Article/details/gtduiaomiz.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.cucudq.cn/Article/details/gtrpwtftxx.html

[S51] C++：显式类型转换
来源：http://dali.haohaochexian.top/Article/details/gtlipxkbiy.html

static_cast<double>(a) / b
来源：http://dali.jiagoushi.top/Article/details/gtbzhcsjeu.html

[S52] C++：const 与 noexcept
来源：http://dali.ehwqpu.com/Article/details/gtnkdunsxa.html

int size() const noexcept { return n_; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlobiaorn.html

[S53] C++：移动语义
来源：http://dali.xylfe.cn/Article/details/gtlghsqyww.html

std::vector<int> w = std::move(v);
来源：http://dali.zdqjudy.top/Article/details/gtmessqwmf.html

[S54] C++：异常处理
来源：http://dali.feifeiyinyue.top/Article/details/gtznippbuv.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.bjfxy.top/Article/details/gtfdyatclz.html

[S55] C++：结构化绑定
来源：http://dali.yvedp.cn/Article/details/gtnbfgdcpm.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhengqikj.top/Article/details/gtbjkxzhgu.html

[S56] C++：optional
来源：http://dali.yanxiufei.cn/Article/details/gtpvcudopr.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.kuanghao11.cn/Article/details/gtqvmntphk.html

[S57] C++：编译期常量
来源：http://dali.yonumen.top/Article/details/gtjfiihpvh.html

constexpr int N = 10;
来源：http://dali.xziqi.cn/Article/details/gtqartdmqy.html

[S58] C++：命名空间
来源：http://dali.zhengqikj.top/Article/details/gtdxnvyynb.html


<!-- 参考信息 -->