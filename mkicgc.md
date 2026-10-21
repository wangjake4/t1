代发 wailian999

[Q84] 去除首尾空格
来源：http://dali.xuetiantiany.cn/Article/details/gtbsokkmyb.html

SELECT TRIM(name) FROM users;
来源：http://dali.ppjwa.cn/Article/details/gtkldxqchy.html

[Q85] 数值取整
来源：http://dali.nanxinkj.top/Article/details/gtkiiszmnr.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqkaajjpd.html

[Q86] 读取 JSON 字段
来源：http://dali.gotoacloud.top/Article/details/gtfybxgohz.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuiehjvcz.html

[Q87] JSON 字段做条件
来源：http://dali.hywenlv.cn/Article/details/gtrxlkyphh.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.tanke756.top/Article/details/gtwfxqihzw.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhoulong.xyz/Article/details/gttazcycym.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.ydzc1.top/Article/details/gtzsthddhu.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gtqjpbcfxv.html

[Q89] 判断表是否存在
来源：http://dali.jyoumei.cn/Article/details/gtvlfjocay.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.jiagoushi.top/Article/details/gtftwdjrma.html

[Q90] 生成序号列
来源：http://dali.cashguo.top/Article/details/gtocopgdxd.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.hysaishi.cn/Article/details/gtrxegwmbn.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtqmgoplsj.html

R. Bash 专题
来源：http://dali.ppjwa.cn/Article/details/gtfeersxwl.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtrynoxukr.html

[R01] shebang 与严格模式
来源：http://dali.xylfe.cn/Article/details/gtctulvifm.html

#!/usr/bin/env bash
来源：http://dali.tian-w.cn/Article/details/gtojekeupm.html

set -euo pipefail
来源：http://dali.ehwqpu.com/Article/details/gtycsuwkix.html

[R02] 变量赋值与使用
来源：http://dali.smart0.xyz/Article/details/gtdvcsbwkq.html

name="Tom"; echo "$name"
来源：http://dali.jinqigufen.top/Article/details/gtlpiuafjy.html

[R03] 只读变量
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtptejmfft.html

readonly PI=3.14
来源：http://dali.ydzc1.top/Article/details/gtbiiapchm.html

[R04] 位置参数
来源：http://dali.shanyushiyangtech.top/Article/details/gtdtbdvluo.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.daxiang520.top/Article/details/gtjgbgwrru.html

[R05] 参数默认值
来源：http://dali.haohaochexian.top/Article/details/gtxcrsptel.html

name="${1:-default}"
来源：http://dali.yanxiufei.cn/Article/details/gttrtcqafj.html

[R06] 判断命令是否存在
来源：http://dali.hnxiangtu.top/Article/details/gtopftrwxr.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.aibaodan.cn/Article/details/gtbpaykveg.html

[R07] if 判断文件
来源：http://dali.birdmap.top/Article/details/gtgrfmcure.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.sxryk.cn/Article/details/gtlhqqpqkr.html

[R08] 数值比较
来源：http://dali.fzhhl.top/Article/details/gtflsnnsnu.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.daxiang520.top/Article/details/gtqyfpusyf.html

[R09] 字符串比较
来源：http://dali.shangyingyoupin.top/Article/details/gtdqfcrnqa.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.daxiang520.top/Article/details/gtrprmgpgj.html

[R10] 正则匹配
来源：http://dali.shzxlz.cn/Article/details/gtierrtkfn.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.aizwys.cn/Article/details/gtfkmnihvb.html

[R11] case 多分支
来源：http://dali.mhx1999.top/Article/details/gtzlkwmmpv.html

case "$1" in
来源：http://dali.jyoumei.cn/Article/details/gtjiyalchf.html

start) echo "启动" ;;
来源：http://dali.xuetiantiany.cn/Article/details/gtevtlasas.html

stop)  echo "停止" ;;
来源：http://dali.cqqwz.cn/Article/details/gtqjintgit.html

*)     echo "未知命令" ;;
来源：http://dali.mhx1999.top/Article/details/gtcvsxruey.html

esac
来源：http://dali.quarkkingdee.top/Article/details/gtqalgdozv.html

[R12] for 遍历文件
来源：http://dali.hnxiangtu.top/Article/details/gtshpkujad.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhoulong.xyz/Article/details/gtpdtttihn.html

[R13] for 计数循环
来源：http://dali.jinghuilouyu.cn/Article/details/gtodqchsve.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.hysaishi.cn/Article/details/gtrvewwkxp.html

[R14] C 风格 for
来源：http://dali.shzxlz.cn/Article/details/gtnwwvjhto.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.yvedp.cn/Article/details/gthvdztdwv.html

[R15] while 逐行读文件
来源：http://dali.cucudq.cn/Article/details/gtqfmmxxre.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.tanke756.top/Article/details/gtjbbetdik.html

[R16] until 等待条件
来源：http://dali.hfpthk.cn/Article/details/gtlfcrhyqk.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.guannengcc.top/Article/details/gtlzdqfmib.html

[R17] 数组定义与取值
来源：http://dali.yvedp.cn/Article/details/gtmiwycmcm.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.gotoacloud.top/Article/details/gtjcdolfai.html

[R18] 遍历数组
来源：http://dali.haohaochexian.top/Article/details/gtnakojwzs.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.meibo888.top/Article/details/gtyqgllzav.html

[R19] 数组长度
来源：http://dali.ppjwa.cn/Article/details/gtmqkhuxgi.html

echo "${#arr[@]}"
来源：http://dali.9152youxi.cn/Article/details/gtupqeagfx.html

[R20] 关联数组（字典）
来源：http://dali.mhx1999.top/Article/details/gtnbgdbpsa.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.cheryme.top/Article/details/gtoahbfpwb.html

[R21] 字符串长度
来源：http://dali.hnxiangtu.top/Article/details/gtjsdnbnsc.html

echo "${#s}"
来源：http://dali.guannengcc.top/Article/details/gtvhggjkeu.html

[R22] 截取子串
来源：http://dali.yuanzhike.top/Article/details/gtbkgxkrlt.html

echo "${s:0:5}"
来源：http://dali.gzhubu.top/Article/details/gtebgocjem.html

[R23] 字符串替换
来源：http://dali.yongpay.top/Article/details/gtymosapcf.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.shanyushiyangtech.top/Article/details/gtanbjiaqv.html

[R24] 大小写转换
来源：http://dali.ywan-chungtsiang.top/Article/details/gthtceuidp.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.sweek.top/Article/details/gtbgjtrshm.html

[R25] 去后缀 / 去前缀
来源：http://dali.daxiang520.top/Article/details/gteqmoydro.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.sufxvd.cn/Article/details/gtdheoqkrl.html

[R26] 命令替换
来源：http://dali.hfpthk.cn/Article/details/gtcufoshro.html

now=$(date +%F); echo "$now"
来源：http://dali.ehwqpu.com/Article/details/gtovrskxqk.html

[R27] 算术展开
来源：http://dali.daxiang520.top/Article/details/gtruxgnwzs.html

echo $((1 + 2 * 3))
来源：http://dali.ehwqpu.com/Article/details/gtgkygacbf.html

[R28] 浮点运算
来源：http://dali.aibaodan.cn/Article/details/gthchxrpjj.html

echo "scale=2; 10/3" | bc
来源：http://dali.haohaochexian.top/Article/details/gtouahqdya.html

[R29] 定义函数
来源：http://dali.meibo888.top/Article/details/gtnhkhspqq.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.316326.xyz/Article/details/gtbuhvfxnu.html

[R30] 函数返回状态码
来源：http://dali.ehwqpu.com/Article/details/gtayjoogup.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.chenzaomai.com/Article/details/gtcrajgave.html

[R31] 局部变量
来源：http://dali.zhixingplan.top/Article/details/gtprfoeymp.html

f() { local x=1; echo "$x"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtdlwmhjgp.html

[R32] 参数个数校验
来源：http://dali.meibo888.top/Article/details/gtskftgvog.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhoulong.xyz/Article/details/gtibzjquas.html

[R33] 捕获错误并提示行号
来源：http://dali.xinyue.icu/Article/details/gtzbsfevsg.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.9152youxi.cn/Article/details/gtaidrtrid.html

[R34] 退出时清理
来源：http://dali.jqgufenzy.top/Article/details/gtmnukjtql.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhongyouzk.top/Article/details/gtctlkmlts.html

[R35] 后台执行并等待
来源：http://dali.jinqigfzy.top/Article/details/gtsrbagdwi.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.birdmap.top/Article/details/gtfjysestu.html

[R36] 并发执行多个任务
来源：http://dali.wangshuangyany.cn/Article/details/gtyvglofca.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.gotoacloud.top/Article/details/gtjktxigsu.html

[R37] 把输出赋给变量
来源：http://dali.yueranfly.top/Article/details/gtpywndkwl.html

files=$(ls -1)
来源：http://dali.zhiwuduotai.top/Article/details/gtpilkrrcw.html

[R38] 管道串联
来源：http://dali.xinyue.icu/Article/details/gtjxkqxjlb.html

cat a.txt | grep -i error | wc -l
来源：http://dali.tian-w.cn/Article/details/gtydytwfrx.html

[R39] 重定向标准输出与错误
来源：http://dali.yuanzhike.top/Article/details/gtlnlcvhav.html

cmd > out.log 2>&1
来源：http://dali.wangshuangyany.cn/Article/details/gtiwdagvhi.html

[R40] 追加写日志
来源：http://dali.iojbl.cn/Article/details/gtkmoizpom.html

echo "log" >> out.log
来源：http://dali.xuetiantiany.cn/Article/details/gteezzizty.html

[R41] 丢弃输出
来源：http://dali.yj20258.top/Article/details/gthehflpjt.html

cmd >/dev/null 2>&1
来源：http://dali.guannengcc.top/Article/details/gtmhybourn.html

[R42] 输入重定向
来源：http://dali.yuanzhike.top/Article/details/gtmorkupgj.html

wc -l < a.txt
来源：http://dali.bjfxy.top/Article/details/gtragfldlr.html

[R43] 按名字查找文件
来源：http://dali.birdmap.top/Article/details/gtblqnrxig.html

find . -name "*.log" -type f
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqiyazalh.html

[R44] 按修改时间查找
来源：http://dali.yueranfly.top/Article/details/gtxzewcxol.html

find . -mtime -7 -type f
来源：http://dali.andypj.xyz/Article/details/gtureqpmfy.html

[R45] 批量删除
来源：http://dali.cucudq.cn/Article/details/gthjrajxjk.html

find . -name "*.tmp" -delete
来源：http://dali.svipenyu.cn/Article/details/gtcdygwyqa.html

[R46] 递归替换文件内容
来源：http://dali.zdqjudy.top/Article/details/gtdabyopsl.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.yj20258.top/Article/details/gtputdmddd.html

[R47] sed 单行替换
来源：http://dali.tian-w.cn/Article/details/gtebnrrspp.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.jinqigufen.top/Article/details/gtxknorhlm.html

[R48] awk 取指定列
来源：http://dali.cashguo.top/Article/details/gtefzsevpv.html

awk '{print $1, $3}' a.txt
来源：http://dali.aibaodan.cn/Article/details/gtoqfwhgox.html

[R49] awk 带条件
来源：http://dali.bjfxy.top/Article/details/gtxgxchvkx.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.tanke756.top/Article/details/gttkdocpmr.html

[R50] awk 求和
来源：http://dali.xylfe.cn/Article/details/gtbzmmamzc.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.316326.xyz/Article/details/gtybgeorwm.html

[R51] 排序去重取前几
来源：http://dali.haohaochexian.top/Article/details/gtvbrkydox.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.andypj.xyz/Article/details/gtmapykkvl.html

[R52] 统计行数
来源：http://dali.jyoumei.cn/Article/details/gthgjcjxqe.html

wc -l a.txt
来源：http://dali.chenjidiqi.icu/Article/details/gtggpfhhzn.html

[R53] 查看文件头与实时尾
来源：http://dali.jqgufenzy.top/Article/details/gtllbscuon.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyqavvvcz.html

[R54] 比较两个文件
来源：http://dali.zhixingplan.top/Article/details/gtlhmmbvwb.html

diff a.txt b.txt
来源：http://dali.wangshuangyany.cn/Article/details/gtucerxert.html

[R55] 压缩与解压
来源：http://dali.xylfe.cn/Article/details/gtkqqcnyqz.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.tian-w.cn/Article/details/gtkwbbcynr.html

[R56] 远程拷贝
来源：http://dali.xziqi.cn/Article/details/gtkkglbzsr.html

scp file user@host:/path/
来源：http://dali.jqgufenzy.top/Article/details/gtczyozrln.html

[R57] 远程执行命令
来源：http://dali.bjfxy.top/Article/details/gtmxortiwu.html

ssh user@host 'uptime'
来源：http://dali.sysykeji.top/Article/details/gtuttcyykw.html

[R58] 下载文件
来源：http://dali.hnqzz.top/Article/details/gtkphbugfg.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.guannengcc.top/Article/details/gtvtdyrohl.html

[R59] 发 POST JSON
来源：http://dali.aibaodan.cn/Article/details/gtjbxfsuyb.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.guowangkeji.top/Article/details/gtwbijctjh.html

[R60] 只看 HTTP 状态码
来源：http://dali.jqgufenzy.top/Article/details/gtfyrcvfaj.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.jinqigfzy.top/Article/details/gtegykjqhj.html

[R61] 磁盘占用
来源：http://dali.0kj1m.cn/Article/details/gtrprsvjbk.html

df -h;  du -sh *
来源：http://dali.ivvv.top/Article/details/gtmgdsqyjd.html

[R62] 找最占空间的文件
来源：http://dali.zhiwuduotai.top/Article/details/gtwwwejckk.html

du -ah . | sort -rh | head -10
来源：http://dali.yangfankeji.com/Article/details/gtkionuwud.html

[R63] 内存与进程
来源：http://dali.sysykeji.top/Article/details/gtfkogluwi.html

free -h;  ps aux | grep nginx
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsivndyuv.html

[R64] 结束进程
来源：http://dali.chenlongwang.top/Article/details/gtjgyojsrg.html

kill -9 $(pgrep -f app.py)
来源：http://dali.gotoacloud.top/Article/details/gthjbuspze.html

[R65] 查看端口占用
来源：http://dali.xuanzx.com/Article/details/gtdslizfly.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnrtixyhk.html

[R66] 定时任务
来源：http://dali.daxiang520.top/Article/details/gtqekoheuj.html

crontab -e;  crontab -l
来源：http://dali.shangyingyoupin.top/Article/details/gtlfcsvzrl.html

[R67] 生成随机十六进制串
来源：http://dali.birdmap.top/Article/details/gtblysldvx.html

openssl rand -hex 16
来源：http://dali.zhixingplan.top/Article/details/gtzueljbnh.html

[R68] 计算文件校验值
来源：http://dali.xylfe.cn/Article/details/gtouzqmyhm.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.pengpengdd.cyou/Article/details/gtpryadjus.html

[R69] 生成随机密码
来源：http://dali.ppjwa.cn/Article/details/gttndeltct.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gtpyvsqzwe.html

[R70] 时间戳与互转
来源：http://dali.zdqjudy.top/Article/details/gtoxobnrao.html

date +%s;  date -d @1700000000
来源：http://dali.chenlongwang.top/Article/details/gtvugbqqxp.html

[R71] 日期格式化
来源：http://dali.nanxuanxn.top/Article/details/gtzjdhqiln.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.xziqi.cn/Article/details/gtuomuhdyg.html

[R72] 等待端口就绪
来源：http://dali.quarkkingdee.top/Article/details/gttrolrled.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.ydzc1.top/Article/details/gtrgzrsycl.html

[R73] 分割大日志
来源：http://dali.ybcxt.top/Article/details/gtrdtclall.html

split -l 1000 big.log part_
来源：http://dali.hywenlv.cn/Article/details/gtireuxazl.html

[R74] 批量重命名
来源：http://dali.jinqigfzy.top/Article/details/gtpxackots.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.cqqwz.cn/Article/details/gthbpgrifz.html

[R75] 导出环境变量
来源：http://dali.yuanzhike.top/Article/details/gtntarverd.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.tanke756.top/Article/details/gtfbirwyok.html

[R76] 使用临时文件
来源：http://dali.yueranfly.top/Article/details/gttqbzipwq.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.ivvv.top/Article/details/gthafjxxfe.html

[R77] 读取用户输入
来源：http://dali.0kj1m.cn/Article/details/gtuzzxxwwq.html

read -rp "请输入: " ans
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbnbfeyhv.html

[R78] 交互式菜单
来源：http://dali.c1oappe.top/Article/details/gttjicgnbv.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.xuetiantiany.cn/Article/details/gtrcxpfzwb.html

[R79] 解析命令行选项
来源：http://dali.yvedp.cn/Article/details/gtdzrbpbov.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.shuidangran.top/Article/details/gtipimqfkw.html

[R80] 查看脚本执行耗时
来源：http://dali.shangyingyoupin.top/Article/details/gtbgwoiipf.html

time ./run.sh
来源：http://dali.gogol.net.cn/Article/details/gtmwlkotwi.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtxvjvqrqo.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gtubtquxef.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtmhyglxzh.html

[S01] C：Hello World
来源：http://dali.jinyuanbaomall.cn/Article/details/gtytliwltz.html

#include <stdio.h>
来源：http://dali.zycfv.cn/Article/details/gtxjmmaqvv.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.yuxming.cn/Article/details/gtamafqshx.html

[S02] C：变量与格式化输出
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdjydknnl.html

int a = 10; printf("%d\n", a);
来源：http://dali.fzhhl.top/Article/details/gtbwnezhlm.html

[S03] C：读入整数
来源：http://dali.hfpthk.cn/Article/details/gtjggkhhrj.html

int x; scanf("%d", &x);
来源：http://dali.svipenyu.cn/Article/details/gtaaewevjc.html

[S04] C：字符串复制
来源：http://dali.gaohongyu789.top/Article/details/gtsybeycap.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.tanke756.top/Article/details/gtolvnqnci.html

[S05] C：字符串长度
来源：http://dali.hysaishi.cn/Article/details/gtsnuhnehc.html

strlen(s)
来源：http://dali.cucudq.cn/Article/details/gtyvxrcwxa.html

[S06] C：字符串比较
来源：http://dali.dianchejie.cn/Article/details/gtfadbedqp.html

strcmp(a, b) == 0
来源：http://dali.bjfxy.top/Article/details/gthfnwdcxs.html

[S07] C：数组遍历求和
来源：http://dali.chenjidiqi.icu/Article/details/gtqfgwhieb.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.birdmap.top/Article/details/gtqejrohvn.html

[S08] C：动态内存分配与释放
来源：http://dali.nanxinkj.top/Article/details/gtlekynymc.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.yj202588.top/Article/details/gtrqnpgjeg.html

[S09] C：结构体定义与初始化
来源：http://dali.havefunace.top/Article/details/gtwixegtwm.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.dashuyun.cn/Article/details/gtejxhsjjq.html

[S10] C：指针与解引用
来源：http://dali.zhongyouzk.top/Article/details/gtlxecuvts.html

int *p = &a;  *p = 5;
来源：http://dali.shzxlz.cn/Article/details/gtchvfrsbp.html

[S11] C：逐行读文件
来源：http://dali.cheryme.top/Article/details/gtfudcofgf.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.9152youxi.cn/Article/details/gtqejqjoii.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.wangshuangyany.cn/Article/details/gtxqewahso.html

fclose(f);
来源：http://dali.yvedp.cn/Article/details/gtvmfjjrhm.html

[S12] C：写文件
来源：http://dali.gogol.net.cn/Article/details/gtrillknfr.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.chenzaomai.com/Article/details/gthpunoftx.html

[S13] C：宏定义
来源：http://dali.chenzaomai.com/Article/details/gtynigglvj.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.jlsjyb.cn/Article/details/gtaehtlarc.html

[S14] C：枚举
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzyfjvrjf.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhongyouzk.top/Article/details/gtaqutrfkv.html

[S15] C：类型转换
来源：http://dali.yj20258.top/Article/details/gtjsyzlcdp.html

(double) a / b
来源：http://dali.cucudq.cn/Article/details/gtwsbhaojw.html

[S16] C：位操作置位
来源：http://dali.yueranfly.top/Article/details/gtxzswheco.html

x |= (1 << 3);
来源：http://dali.pycfn.com/Article/details/gtogddbwmb.html

[S17] C：安全拼接字符串
来源：http://dali.shzxlz.cn/Article/details/gtvmjvswmb.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhengqikj.top/Article/details/gtjwsnhufb.html

[S18] C：命令行参数
来源：http://dali.daria6918.cn/Article/details/gtujxwijhp.html

int main(int argc, char **argv)
来源：http://dali.quarkkingdee.top/Article/details/gtvcznhfqh.html

[S19] C：快速排序
来源：http://dali.svipenyu.cn/Article/details/gtdvmhcdwc.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.shanyushiyangtech.top/Article/details/gtzfkxokbg.html

[S20] C：二分查找
来源：http://dali.yvedp.cn/Article/details/gtxnnevcdi.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.jyoumei.cn/Article/details/gtdlafdqri.html

[S21] C：字符类别判断
来源：http://dali.sysykeji.top/Article/details/gtxwlgofmd.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.gotoacloud.top/Article/details/gtvuawspzl.html

[S22] C：字符串转数字
来源：http://dali.ydzc1.top/Article/details/gtkcifxuku.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.svipenyu.cn/Article/details/gttuqjbile.html

[S23] C：随机数
来源：http://dali.ppjwa.cn/Article/details/gtapzmandk.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.yj20258.top/Article/details/gtlqdlzsio.html

[S24] C：获取本地时间
来源：http://dali.zdqjudy.top/Article/details/gtwvdvzobz.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.feifeiyinyue.top/Article/details/gtbqzqwqbn.html

[S25] C：内存拷贝
来源：http://dali.feifeiyinyue.top/Article/details/gtagchoiwr.html

memcpy(dst, src, n);
来源：http://dali.meibo888.top/Article/details/gtlfcvffpf.html

[S26] C：内存清零
来源：http://dali.mhx1999.top/Article/details/gtrtqkanor.html

memset(a, 0, sizeof a);
来源：http://dali.yuxming.cn/Article/details/gtkesjzptb.html

[S27] C：定义常量
来源：http://dali.aibaodan.cn/Article/details/gtfxjuyoxh.html

const double PI = 3.14159;
来源：http://dali.fengsongda.top/Article/details/gtfiyooixv.html

[S28] C：静态变量
来源：http://dali.nanxuanxn.top/Article/details/gtvaznpkok.html

static int counter = 0;
来源：http://dali.chenjidiqi.icu/Article/details/gtwltfnhmw.html

[S29] C：变参函数
来源：http://dali.fzhhl.top/Article/details/gtaleecvot.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.cucudq.cn/Article/details/gtcuwkddvd.html

[S30] C：头文件保护
来源：http://dali.nanxinkj.top/Article/details/gtzztpdsbm.html

#ifndef X_H
来源：http://dali.chenlongwang.top/Article/details/gtgwcaboim.html

#define X_H
来源：http://dali.hnxiangtu.top/Article/details/gtnjylmjgc.html

#endif
来源：http://dali.vqdsnc.cn/Article/details/gtpsuhhchg.html

[S31] C++：Hello World
来源：http://dali.gaohongyu789.top/Article/details/gtzkqaxvle.html

#include <iostream>
来源：http://dali.yangfankeji.com/Article/details/gtwpikqqtq.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.daria6918.cn/Article/details/gtfyufltah.html

[S32] C++：字符串
来源：http://dali.ydzc1.top/Article/details/gtybhapqrp.html

std::string s = "hi";  s += "!";
来源：http://dali.jianghu66.top/Article/details/gtuwjbwdag.html

[S33] C++：vector 增删
来源：http://dali.0kj1m.cn/Article/details/gtchpgspvf.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.nanxuanxn.top/Article/details/gtkmnaylsd.html

[S34] C++：遍历 vector
来源：http://dali.zhixingplan.top/Article/details/gtfpqkbllv.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.smart0.xyz/Article/details/gtrcgfdfmr.html

[S35] C++：map
来源：http://dali.nanxinkj.top/Article/details/gtlkixsgmx.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.snrcjt.cn/Article/details/gtipiesqdp.html

[S36] C++：unordered_map
来源：http://dali.bjfxy.top/Article/details/gtpkdpoqtv.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.chenlongwang.top/Article/details/gtppgujamx.html

[S37] C++：set
来源：http://dali.xuanzx.com/Article/details/gtlhqzrdii.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.hongshengwenyu.top/Article/details/gtqegguvdx.html

[S38] C++：排序
来源：http://dali.nwbrower.top/Article/details/gtsfsopmxt.html

std::sort(v.begin(), v.end());
来源：http://dali.chenlongwang.top/Article/details/gtjoxtoqri.html

[S39] C++：自定义比较器排序
来源：http://dali.cdnleiting.top/Article/details/gtroleypon.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.pycfn.com/Article/details/gtmsevjiqs.html

[S40] C++：查找元素
来源：http://dali.smart0.xyz/Article/details/gtqtqvucks.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.xuetiantiany.cn/Article/details/gthuttoopm.html

[S41] C++：类与构造函数
来源：http://dali.yuxming.cn/Article/details/gtzlwgmoah.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.yongpay.top/Article/details/gtnammkwgc.html

[S42] C++：继承与虚函数
来源：http://dali.yueranfly.top/Article/details/gtgsobahjv.html

class B : public Base { public: void f() override {} };
来源：http://dali.yangfankeji.com/Article/details/gtwjltcnok.html

[S43] C++：智能指针
来源：http://dali.daxiang520.top/Article/details/gtcaxumozj.html

auto p = std::make_unique<int>(5);
来源：http://dali.pengpengdd.cyou/Article/details/gtbxntmbee.html

[S44] C++：引用传参
来源：http://dali.zhongyouzk.top/Article/details/gtdkuhlrhf.html

void inc(int &x) { ++x; }
来源：http://dali.yj20258888.top/Article/details/gtvqpfsnxf.html

[S45] C++：lambda
来源：http://dali.jqgufenzy.top/Article/details/gtremtcuit.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.redwolf501.top/Article/details/gtasnswtsh.html

[S46] C++：函数模板
来源：http://dali.guowangkeji.top/Article/details/gthoixbcrz.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.ehwqpu.com/Article/details/gtcmzcaipp.html

[S47] C++：结构化绑定遍历
来源：http://dali.sufxvd.cn/Article/details/gtmwxfdbhq.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.c1oappe.top/Article/details/gtljnufvzm.html

[S48] C++：逐行读文件
来源：http://dali.ybcxt.top/Article/details/gticumrqso.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.pycfn.com/Article/details/gttwyykjej.html

while (std::getline(in, line)) { }
来源：http://dali.andypj.xyz/Article/details/gtkgxncuvo.html

[S49] C++：写文件
来源：http://dali.birdmap.top/Article/details/gtwxnuylwt.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.redwolf501.top/Article/details/gtftebkqfj.html

[S50] C++：格式化数字
来源：http://dali.sysykeji.top/Article/details/gtiflwmkzw.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlpmswrcy.html

[S51] C++：显式类型转换
来源：http://dali.zhiwuduotai.top/Article/details/gtqaeeydai.html

static_cast<double>(a) / b
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttfoekqcy.html

[S52] C++：const 与 noexcept
来源：http://dali.hnqzz.top/Article/details/gtpjcftofy.html

int size() const noexcept { return n_; }
来源：http://dali.kuanghao11.cn/Article/details/gtyfqohcee.html

[S53] C++：移动语义
来源：http://dali.tianlin.xyz/Article/details/gtdthijixe.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gtnwwzdmpd.html

[S54] C++：异常处理
来源：http://dali.chenjidiqi.icu/Article/details/gtoqroxbit.html


<!-- 参考信息 -->