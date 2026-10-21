代发 wailian999

[Q86] 读取 JSON 字段
来源：http://dali.jinqigufen.top/Article/details/gttuyznklm.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.cdnleiting.top/Article/details/gteltcqurk.html

[Q87] JSON 字段做条件
来源：http://dali.shzxlz.cn/Article/details/gtcrtgjhgw.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvadwrbly.html

[Q88] 行转列（条件聚合）
来源：http://dali.ivvv.top/Article/details/gtkuvhqhwg.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.xinyue.icu/Article/details/gtmajixobg.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkhfnchwk.html

[Q89] 判断表是否存在
来源：http://dali.jinqigfzy.top/Article/details/gthnqaeunm.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhiwuduotai.top/Article/details/gtyfmhnwyq.html

[Q90] 生成序号列
来源：http://dali.wangshuangyany.cn/Article/details/gtodfnpddy.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhiwuduotai.top/Article/details/gtqcluzkez.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtasudlqxr.html

R. Bash 专题
来源：http://dali.nwbrower.top/Article/details/gtfcphzkdi.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtmultqiud.html

[R01] shebang 与严格模式
来源：http://dali.hnxiangtu.top/Article/details/gtgpugbone.html

#!/usr/bin/env bash
来源：http://dali.guowangkeji.top/Article/details/gteoguzgzo.html

set -euo pipefail
来源：http://dali.havefunace.top/Article/details/gtlmzmanhh.html

[R02] 变量赋值与使用
来源：http://dali.9152youxi.cn/Article/details/gtsankwceq.html

name="Tom"; echo "$name"
来源：http://dali.xziqi.cn/Article/details/gtwhlbacze.html

[R03] 只读变量
来源：http://dali.redwolf501.top/Article/details/gtitkqkokh.html

readonly PI=3.14
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtakmwqelf.html

[R04] 位置参数
来源：http://dali.guannengcc.top/Article/details/gthkupvuxv.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.cucudq.cn/Article/details/gtdnaupsuc.html

[R05] 参数默认值
来源：http://dali.jqgfzy.top/Article/details/gthrronnno.html

name="${1:-default}"
来源：http://dali.yueranfly.top/Article/details/gtocqweszc.html

[R06] 判断命令是否存在
来源：http://dali.gogol.net.cn/Article/details/gtrcyochey.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.cashguo.top/Article/details/gtgsrlidbp.html

[R07] if 判断文件
来源：http://dali.yuanzhike.top/Article/details/gtqmavjkko.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiocdarpx.html

[R08] 数值比较
来源：http://dali.hammf.cn/Article/details/gtucimkshi.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.hywenlv.cn/Article/details/gthwgdolaf.html

[R09] 字符串比较
来源：http://dali.yangfankeji.com/Article/details/gtnzjkbtdb.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.hfpthk.cn/Article/details/gtmdcedygs.html

[R10] 正则匹配
来源：http://dali.yuanzhike.top/Article/details/gtlrqgzdtr.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.jinqigfzy.top/Article/details/gtegkuyzlp.html

[R11] case 多分支
来源：http://dali.sxryk.cn/Article/details/gtjtyskser.html

case "$1" in
来源：http://dali.jinghuilouyu.cn/Article/details/gtmfealoku.html

start) echo "启动" ;;
来源：http://dali.quarkkingdee.top/Article/details/gtgxkrvtmx.html

stop)  echo "停止" ;;
来源：http://dali.tianlin.xyz/Article/details/gtigdlgczy.html

*)     echo "未知命令" ;;
来源：http://dali.gotoacloud.top/Article/details/gtcycnpune.html

esac
来源：http://dali.sweek.top/Article/details/gtzzsutymy.html

[R12] for 遍历文件
来源：http://dali.hammf.cn/Article/details/gtwllalzva.html

for f in *.txt; do echo "$f"; done
来源：http://dali.jqgufenzy.top/Article/details/gttotgpvgu.html

[R13] for 计数循环
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzbkqgktr.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.daria6918.cn/Article/details/gtyrsynugk.html

[R14] C 风格 for
来源：http://dali.chenzaomai.com/Article/details/gtaydjtmpf.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.jinqigfzy.top/Article/details/gtpwcdprje.html

[R15] while 逐行读文件
来源：http://dali.sufxvd.cn/Article/details/gtwneevotl.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.sxryk.cn/Article/details/gtcjymaqnt.html

[R16] until 等待条件
来源：http://dali.chenjidiqi.icu/Article/details/gtcwnywbwa.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.gogol.net.cn/Article/details/gtrkuednei.html

[R17] 数组定义与取值
来源：http://dali.chenzaomai.com/Article/details/gtshamilap.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.yj20258.top/Article/details/gttalngknu.html

[R18] 遍历数组
来源：http://dali.feifeiyinyue.top/Article/details/gtlgbeffik.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.shangyingyoupin.top/Article/details/gtzygrzlvb.html

[R19] 数组长度
来源：http://dali.hnxiangtu.top/Article/details/gteerjcdll.html

echo "${#arr[@]}"
来源：http://dali.shzxlz.cn/Article/details/gtgnuswhgv.html

[R20] 关联数组（字典）
来源：http://dali.ppjwa.cn/Article/details/gtbpmzqdqk.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.chenzaomai.com/Article/details/gtzbixpqdl.html

[R21] 字符串长度
来源：http://dali.chenzaomai.com/Article/details/gtkyogqpky.html

echo "${#s}"
来源：http://dali.yangfankeji.com/Article/details/gtoyxvvdrw.html

[R22] 截取子串
来源：http://dali.pengpengdd.cyou/Article/details/gtxrdknnzc.html

echo "${s:0:5}"
来源：http://dali.cucudq.cn/Article/details/gtiosrnzmw.html

[R23] 字符串替换
来源：http://dali.xylfe.cn/Article/details/gtklgyzvzz.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.yj202588.top/Article/details/gtwpcrrbwl.html

[R24] 大小写转换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtehylazys.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.chenjidiqi.icu/Article/details/gtleihyyyy.html

[R25] 去后缀 / 去前缀
来源：http://dali.yj20258888.top/Article/details/gtyxfqppmh.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.ybcxt.top/Article/details/gtvohnblwa.html

[R26] 命令替换
来源：http://dali.tianlin.xyz/Article/details/gtvpvlyfvr.html

now=$(date +%F); echo "$now"
来源：http://dali.jinqigfzy.top/Article/details/gtvzgohxos.html

[R27] 算术展开
来源：http://dali.havefunace.top/Article/details/gtziwqjfzh.html

echo $((1 + 2 * 3))
来源：http://dali.shuidangran.top/Article/details/gtbqymshvp.html

[R28] 浮点运算
来源：http://dali.mhx1999.top/Article/details/gtovrfqatt.html

echo "scale=2; 10/3" | bc
来源：http://dali.ppjwa.cn/Article/details/gtylttxjcy.html

[R29] 定义函数
来源：http://dali.sufxvd.cn/Article/details/gtjhxujdxd.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.jianghu66.top/Article/details/gtkczspsjn.html

[R30] 函数返回状态码
来源：http://dali.xinyue.icu/Article/details/gtckhsptmp.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.jiagoushi.top/Article/details/gtxvsvcvmi.html

[R31] 局部变量
来源：http://dali.jinghuilouyu.cn/Article/details/gtqozggwfm.html

f() { local x=1; echo "$x"; }
来源：http://dali.hywenlv.cn/Article/details/gtmfnjkatm.html

[R32] 参数个数校验
来源：http://dali.vqdsnc.cn/Article/details/gtfherrdgm.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.pengpengdd.cyou/Article/details/gthtvzbkpl.html

[R33] 捕获错误并提示行号
来源：http://dali.shzxlz.cn/Article/details/gtmggxhyaj.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.hammf.cn/Article/details/gtqyovjgny.html

[R34] 退出时清理
来源：http://dali.sxryk.cn/Article/details/gtaamsjzsm.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.pengpengdd.cyou/Article/details/gtxtgidyvv.html

[R35] 后台执行并等待
来源：http://dali.daria6918.cn/Article/details/gtpqfcnqzk.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.yj20258.top/Article/details/gttuqdgiva.html

[R36] 并发执行多个任务
来源：http://dali.chenlongwang.top/Article/details/gtzsejavmt.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.snrcjt.cn/Article/details/gtmrzlhumv.html

[R37] 把输出赋给变量
来源：http://dali.yj20258888.top/Article/details/gtagzgbirq.html

files=$(ls -1)
来源：http://dali.xylfe.cn/Article/details/gtlmnppqno.html

[R38] 管道串联
来源：http://dali.fengsongda.top/Article/details/gtgtedmleg.html

cat a.txt | grep -i error | wc -l
来源：http://dali.yuanzhike.top/Article/details/gtieowamzf.html

[R39] 重定向标准输出与错误
来源：http://dali.yj20258.top/Article/details/gtmqqqllpw.html

cmd > out.log 2>&1
来源：http://dali.aizwys.cn/Article/details/gtwexestoa.html

[R40] 追加写日志
来源：http://dali.jinqigfzy.top/Article/details/gtvrijruof.html

echo "log" >> out.log
来源：http://dali.xylfe.cn/Article/details/gtbljcbhyf.html

[R41] 丢弃输出
来源：http://dali.dashuyun.cn/Article/details/gtqttlhcjb.html

cmd >/dev/null 2>&1
来源：http://dali.nwbrower.top/Article/details/gticesdepd.html

[R42] 输入重定向
来源：http://dali.jqgfzy.top/Article/details/gtwoudkgtv.html

wc -l < a.txt
来源：http://dali.yanxiufei.cn/Article/details/gtwdmhwfvo.html

[R43] 按名字查找文件
来源：http://dali.vqdsnc.cn/Article/details/gtqhiwrhgi.html

find . -name "*.log" -type f
来源：http://dali.dianchejie.cn/Article/details/gtwkxmvgtk.html

[R44] 按修改时间查找
来源：http://dali.aizwys.cn/Article/details/gtsfwasnce.html

find . -mtime -7 -type f
来源：http://dali.shzxlz.cn/Article/details/gtztetvbkp.html

[R45] 批量删除
来源：http://dali.guannengcc.top/Article/details/gtksutmuck.html

find . -name "*.tmp" -delete
来源：http://dali.shzxlz.cn/Article/details/gthfcmhjjf.html

[R46] 递归替换文件内容
来源：http://dali.jyoumei.cn/Article/details/gttstdudtu.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.shzxlz.cn/Article/details/gtxxzddffi.html

[R47] sed 单行替换
来源：http://dali.jlsjyb.cn/Article/details/gthhcvblgz.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.jinghuilouyu.cn/Article/details/gtllfpsdxo.html

[R48] awk 取指定列
来源：http://dali.chenlongwang.top/Article/details/gtdbalecus.html

awk '{print $1, $3}' a.txt
来源：http://dali.yj20258.top/Article/details/gtjgscundt.html

[R49] awk 带条件
来源：http://dali.gogol.net.cn/Article/details/gtcajrwsme.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.pycfn.com/Article/details/gtqvnhcjzt.html

[R50] awk 求和
来源：http://dali.hnqzz.top/Article/details/gtkllgykim.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.yonumen.top/Article/details/gtuokimcsq.html

[R51] 排序去重取前几
来源：http://dali.tian-w.cn/Article/details/gtyyqbwvhj.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.gotoacloud.top/Article/details/gthhaoweps.html

[R52] 统计行数
来源：http://dali.hnqzz.top/Article/details/gtigogwzzk.html

wc -l a.txt
来源：http://dali.jqgufenzy.top/Article/details/gtfysogqmk.html

[R53] 查看文件头与实时尾
来源：http://dali.shangyingyoupin.top/Article/details/gtcvyzkeay.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.yongpay.top/Article/details/gtnaefdlih.html

[R54] 比较两个文件
来源：http://dali.gaohongyu789.top/Article/details/gtqgixhmzb.html

diff a.txt b.txt
来源：http://dali.shanyushiyangtech.top/Article/details/gtbwtmuniw.html

[R55] 压缩与解压
来源：http://dali.cdnleiting.top/Article/details/gtfzgzityt.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gtfrxrsrrp.html

[R56] 远程拷贝
来源：http://dali.gaohongyu789.top/Article/details/gtmebuyqjs.html

scp file user@host:/path/
来源：http://dali.jyoumei.cn/Article/details/gtohimhyyr.html

[R57] 远程执行命令
来源：http://dali.316326.xyz/Article/details/gtonzgjgum.html

ssh user@host 'uptime'
来源：http://dali.birdmap.top/Article/details/gtqinxlogp.html

[R58] 下载文件
来源：http://dali.hnqzz.top/Article/details/gtlktgrygm.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.yonumen.top/Article/details/gtcyuoyzsj.html

[R59] 发 POST JSON
来源：http://dali.pycfn.com/Article/details/gtursvtukl.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.cashguo.top/Article/details/gtiwaibncr.html

[R60] 只看 HTTP 状态码
来源：http://dali.daria6918.cn/Article/details/gtuzjkoiyl.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhongyouzk.top/Article/details/gtktvrohxj.html

[R61] 磁盘占用
来源：http://dali.nwbrower.top/Article/details/gtmkwokzfe.html

df -h;  du -sh *
来源：http://dali.tian-w.cn/Article/details/gtcdquqerq.html

[R62] 找最占空间的文件
来源：http://dali.zhengqikj.top/Article/details/gtedswniqp.html

du -ah . | sort -rh | head -10
来源：http://dali.jianghu66.top/Article/details/gtcxwjibms.html

[R63] 内存与进程
来源：http://dali.nanxuanxn.top/Article/details/gtefttcrgr.html

free -h;  ps aux | grep nginx
来源：http://dali.daxiang520.top/Article/details/gteueqpurk.html

[R64] 结束进程
来源：http://dali.yj20258.top/Article/details/gtrgpsffjf.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zycfv.cn/Article/details/gtrvlqzdwq.html

[R65] 查看端口占用
来源：http://dali.sxryk.cn/Article/details/gtdsfypvje.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwttmrrty.html

[R66] 定时任务
来源：http://dali.hnqzz.top/Article/details/gtghkjwilg.html

crontab -e;  crontab -l
来源：http://dali.pycfn.com/Article/details/gtcapgebnh.html

[R67] 生成随机十六进制串
来源：http://dali.gaohongyu789.top/Article/details/gttwztayll.html

openssl rand -hex 16
来源：http://dali.yuxming.cn/Article/details/gtfxyqkgdd.html

[R68] 计算文件校验值
来源：http://dali.jianghu66.top/Article/details/gtfhxycqie.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhengqikj.top/Article/details/gtlazbzmfn.html

[R69] 生成随机密码
来源：http://dali.cqqwz.cn/Article/details/gtawrakpus.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhengqikj.top/Article/details/gtopnxkumf.html

[R70] 时间戳与互转
来源：http://dali.birdmap.top/Article/details/gtpbutvjvx.html

date +%s;  date -d @1700000000
来源：http://dali.sysykeji.top/Article/details/gtnfehwuga.html

[R71] 日期格式化
来源：http://dali.iojbl.cn/Article/details/gtqzzlghtb.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.andypj.xyz/Article/details/gtwpujbaig.html

[R72] 等待端口就绪
来源：http://dali.yongpay.top/Article/details/gtrhuirjbi.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.quarkkingdee.top/Article/details/gtsxksvife.html

[R73] 分割大日志
来源：http://dali.andypj.xyz/Article/details/gtqpvwusls.html

split -l 1000 big.log part_
来源：http://dali.fengsongda.top/Article/details/gttcljgzlo.html

[R74] 批量重命名
来源：http://dali.guowangkeji.top/Article/details/gtencfgjow.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.feifeiyinyue.top/Article/details/gtquzihody.html

[R75] 导出环境变量
来源：http://dali.yj20258.top/Article/details/gtgmuoeatb.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.hnqzz.top/Article/details/gtzwcnkoxs.html

[R76] 使用临时文件
来源：http://dali.xziqi.cn/Article/details/gtsnatighc.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.hysaishi.cn/Article/details/gtyivrschk.html

[R77] 读取用户输入
来源：http://dali.pycfn.com/Article/details/gtesuvfbtc.html

read -rp "请输入: " ans
来源：http://dali.andypj.xyz/Article/details/gtykxayhkd.html

[R78] 交互式菜单
来源：http://dali.cheryme.top/Article/details/gtymlphkez.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.shzxlz.cn/Article/details/gtifppjjpe.html

[R79] 解析命令行选项
来源：http://dali.yangfankeji.com/Article/details/gtfzfaemdt.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.jinqigfzy.top/Article/details/gtrwbdyqay.html

[R80] 查看脚本执行耗时
来源：http://dali.yuanzhike.top/Article/details/gtpczujcjn.html

time ./run.sh
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrynlxtog.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtbjsxkcxl.html

S. C / C++ 专题
来源：http://dali.pycfn.com/Article/details/gtdgeadcff.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtgqbnwbic.html

[S01] C：Hello World
来源：http://dali.aizwys.cn/Article/details/gtpyscbqiq.html

#include <stdio.h>
来源：http://dali.daria6918.cn/Article/details/gtshylpuqd.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.gotoacloud.top/Article/details/gtifgixtlz.html

[S02] C：变量与格式化输出
来源：http://dali.dashuyun.cn/Article/details/gtwrwnofzj.html

int a = 10; printf("%d\n", a);
来源：http://dali.ppjwa.cn/Article/details/gtfabbzzpg.html

[S03] C：读入整数
来源：http://dali.ppjwa.cn/Article/details/gtrmtguiuy.html

int x; scanf("%d", &x);
来源：http://dali.316326.xyz/Article/details/gtklekvije.html

[S04] C：字符串复制
来源：http://dali.jlsjyb.cn/Article/details/gtyrviwupb.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhengqikj.top/Article/details/gtrvarrrij.html

[S05] C：字符串长度
来源：http://dali.316326.xyz/Article/details/gtrjcefzkk.html

strlen(s)
来源：http://dali.fengsongda.top/Article/details/gtjpvazczm.html

[S06] C：字符串比较
来源：http://dali.yj202588.top/Article/details/gtdhkeovdp.html

strcmp(a, b) == 0
来源：http://dali.guannengcc.top/Article/details/gtfcsglpdg.html

[S07] C：数组遍历求和
来源：http://dali.gogol.net.cn/Article/details/gtthubogxi.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.hywenlv.cn/Article/details/gtjjjcznim.html

[S08] C：动态内存分配与释放
来源：http://dali.meibo888.top/Article/details/gtmzlybiqm.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqmydycjz.html

[S09] C：结构体定义与初始化
来源：http://dali.svipenyu.cn/Article/details/gtsshzwqoy.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.gzhubu.top/Article/details/gtcbsqaeuf.html

[S10] C：指针与解引用
来源：http://dali.xinyue.icu/Article/details/gtabomhcez.html

int *p = &a;  *p = 5;
来源：http://dali.hfpthk.cn/Article/details/gtalcjvipx.html

[S11] C：逐行读文件
来源：http://dali.gogol.net.cn/Article/details/gtmqeuhobh.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.andypj.xyz/Article/details/gtirnuvkah.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.xziqi.cn/Article/details/gtmdzhprqt.html

fclose(f);
来源：http://dali.dashuyun.cn/Article/details/gtlnrzirmd.html

[S12] C：写文件
来源：http://dali.yuxming.cn/Article/details/gtcmuttacz.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.guowangkeji.top/Article/details/gtqdaeyeip.html

[S13] C：宏定义
来源：http://dali.guannengcc.top/Article/details/gtqoamkqcb.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.sweek.top/Article/details/gtvxjadhue.html

[S14] C：枚举
来源：http://dali.hywenlv.cn/Article/details/gttiwnsemf.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.yvedp.cn/Article/details/gthxxqsrzu.html

[S15] C：类型转换
来源：http://dali.pengpengdd.cyou/Article/details/gtakixyoov.html

(double) a / b
来源：http://dali.jinqigfzy.top/Article/details/gtfzmpjiyw.html

[S16] C：位操作置位
来源：http://dali.c1oappe.top/Article/details/gtcpkxgpdb.html

x |= (1 << 3);
来源：http://dali.yj20258.top/Article/details/gtbppkyrpr.html

[S17] C：安全拼接字符串
来源：http://dali.jinqigfzy.top/Article/details/gtndpcqnyt.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.chenjidiqi.icu/Article/details/gtoekerqtg.html

[S18] C：命令行参数
来源：http://dali.xuanzx.com/Article/details/gtcaluqucl.html

int main(int argc, char **argv)
来源：http://dali.316326.xyz/Article/details/gtryoohfga.html

[S19] C：快速排序
来源：http://dali.havefunace.top/Article/details/gtalhghius.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.birdmap.top/Article/details/gtytcoxetc.html

[S20] C：二分查找
来源：http://dali.jinqigufen.top/Article/details/gthuruddqm.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.aizwys.cn/Article/details/gttdxgrjfg.html

[S21] C：字符类别判断
来源：http://dali.xuanzx.com/Article/details/gthxiwpffd.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.sweek.top/Article/details/gtjarmkepr.html

[S22] C：字符串转数字
来源：http://dali.gogol.net.cn/Article/details/gtaoubgdeg.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.cdnleiting.top/Article/details/gtghyyqtcl.html

[S23] C：随机数
来源：http://dali.tianlin.xyz/Article/details/gtahifcxgg.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtweuuyqij.html

[S24] C：获取本地时间
来源：http://dali.ydzc1.top/Article/details/gtsfpkninx.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.tanke756.top/Article/details/gtrkwgapwy.html

[S25] C：内存拷贝
来源：http://dali.meibo888.top/Article/details/gtsqdfmmza.html

memcpy(dst, src, n);
来源：http://dali.shanyushiyangtech.top/Article/details/gtpyaidnal.html

[S26] C：内存清零
来源：http://dali.iojbl.cn/Article/details/gtnwtaqevd.html

memset(a, 0, sizeof a);
来源：http://dali.zhixingplan.top/Article/details/gteubsgyms.html

[S27] C：定义常量
来源：http://dali.gzhubu.top/Article/details/gtudjbhdzq.html

const double PI = 3.14159;
来源：http://dali.tian-w.cn/Article/details/gtwklqqcgl.html

[S28] C：静态变量
来源：http://dali.cqqwz.cn/Article/details/gtjzcpwbja.html

static int counter = 0;
来源：http://dali.zhongyouzk.top/Article/details/gtamznfzyg.html

[S29] C：变参函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmsamdtch.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.shangyingyoupin.top/Article/details/gtaazenouj.html

[S30] C：头文件保护
来源：http://dali.fzhhl.top/Article/details/gtwwrgtbgp.html

#ifndef X_H
来源：http://dali.jianghu66.top/Article/details/gtyevarndy.html

#define X_H
来源：http://dali.hnxiangtu.top/Article/details/gttfxbapio.html

#endif
来源：http://dali.daria6918.cn/Article/details/gtosqbgrvp.html

[S31] C++：Hello World
来源：http://dali.daxiang520.top/Article/details/gtaiipqonp.html

#include <iostream>
来源：http://dali.xuetiantiany.cn/Article/details/gtkmaumfhj.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.tianlin.xyz/Article/details/gtosjbfsre.html

[S32] C++：字符串
来源：http://dali.ydzc1.top/Article/details/gtdrxcessa.html

std::string s = "hi";  s += "!";
来源：http://dali.jqgfzy.top/Article/details/gtkruiwayu.html

[S33] C++：vector 增删
来源：http://dali.jqgfzy.top/Article/details/gtoxzmdard.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.sufxvd.cn/Article/details/gtvtmcqdwf.html

[S34] C++：遍历 vector
来源：http://dali.wangdashe.top/Article/details/gttqgnrlnd.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.fzhhl.top/Article/details/gtakkfkrtx.html

[S35] C++：map
来源：http://dali.hongshengwenyu.top/Article/details/gtmrozjubm.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.feifeiyinyue.top/Article/details/gtszfpuyna.html

[S36] C++：unordered_map
来源：http://dali.yj20258888.top/Article/details/gtrwlcpchr.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.sxryk.cn/Article/details/gtbriqjkag.html

[S37] C++：set
来源：http://dali.cashguo.top/Article/details/gtsdpnliun.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.ivvv.top/Article/details/gtbcsmfoco.html

[S38] C++：排序
来源：http://dali.daxiang520.top/Article/details/gtynsgcamz.html

std::sort(v.begin(), v.end());
来源：http://dali.xziqi.cn/Article/details/gtyeyitraw.html

[S39] C++：自定义比较器排序
来源：http://dali.bjfxy.top/Article/details/gtprfruhjc.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.shzxlz.cn/Article/details/gtqyzgkysh.html

[S40] C++：查找元素
来源：http://dali.ivvv.top/Article/details/gtzzzqhsiz.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhixingplan.top/Article/details/gtgjstnjxj.html

[S41] C++：类与构造函数
来源：http://dali.hysaishi.cn/Article/details/gtvkyobbbb.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.yj20258.top/Article/details/gtaovkfkki.html

[S42] C++：继承与虚函数
来源：http://dali.zhiwuduotai.top/Article/details/gtearihzmv.html

class B : public Base { public: void f() override {} };
来源：http://dali.smart0.xyz/Article/details/gtgjlsaehj.html

[S43] C++：智能指针
来源：http://dali.andypj.xyz/Article/details/gtfmqxltgh.html

auto p = std::make_unique<int>(5);
来源：http://dali.yj20258888.top/Article/details/gtrmpetwuu.html

[S44] C++：引用传参
来源：http://dali.zhaomingkeji.xyz/Article/details/gthgnptofn.html

void inc(int &x) { ++x; }
来源：http://dali.xuetiantiany.cn/Article/details/gtiwvqhzjk.html

[S45] C++：lambda
来源：http://dali.jqgfzy.top/Article/details/gtcguwdxxb.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.shangyingyoupin.top/Article/details/gtkicydaap.html

[S46] C++：函数模板
来源：http://dali.zycfv.cn/Article/details/gtnimhstgj.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.pycfn.com/Article/details/gthovcwkfx.html

[S47] C++：结构化绑定遍历
来源：http://dali.guannengcc.top/Article/details/gtlcrvjwje.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.jinqigufen.top/Article/details/gtsjkzxbdw.html

[S48] C++：逐行读文件
来源：http://dali.daxiang520.top/Article/details/gtdjthoghx.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.cqqwz.cn/Article/details/gtprcagrsq.html

while (std::getline(in, line)) { }
来源：http://dali.yj20258.top/Article/details/gtyubowgeb.html

[S49] C++：写文件
来源：http://dali.yanxiufei.cn/Article/details/gtjqmbvgdj.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.cucudq.cn/Article/details/gttqbcvgjh.html

[S50] C++：格式化数字
来源：http://dali.hongshengwenyu.top/Article/details/gtijpnhpjt.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.ehwqpu.com/Article/details/gtpskkpimo.html

[S51] C++：显式类型转换
来源：http://dali.jianghu66.top/Article/details/gtrmwjuljz.html

static_cast<double>(a) / b
来源：http://dali.zhengqikj.top/Article/details/gtigmpocmo.html

[S52] C++：const 与 noexcept
来源：http://dali.nanxinkj.top/Article/details/gtecopznwc.html

int size() const noexcept { return n_; }
来源：http://dali.ydzc1.top/Article/details/gtuevabpsa.html

[S53] C++：移动语义
来源：http://dali.fzhhl.top/Article/details/gtymbfbbnu.html

std::vector<int> w = std::move(v);
来源：http://dali.dashuyun.cn/Article/details/gtmojpxfgd.html

[S54] C++：异常处理
来源：http://dali.gaohongyu789.top/Article/details/gtegbmpwic.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.hfpthk.cn/Article/details/gtcsafwqfe.html

[S55] C++：结构化绑定
来源：http://dali.cqqwz.cn/Article/details/gtpgblgbnc.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.jlsjyb.cn/Article/details/gtptwlgssq.html

[S56] C++：optional
来源：http://dali.yj20258.top/Article/details/gttxrmiomx.html


<!-- 参考信息 -->