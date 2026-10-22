代发 wailian999

[Q86] 读取 JSON 字段
来源：http://dali.yuxming.cn/Article/details/gtnkrwuiko.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.shanyushiyangtech.top/Article/details/gtkrphilcj.html

[Q87] JSON 字段做条件
来源：http://dali.hfpthk.cn/Article/details/gtqjgsohqr.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.hammf.cn/Article/details/gtjybypphz.html

[Q88] 行转列（条件聚合）
来源：http://dali.xuanzx.com/Article/details/gtozjdeqam.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.jiagoushi.top/Article/details/gtcevkysik.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.yongpay.top/Article/details/gtcijxkkou.html

[Q89] 判断表是否存在
来源：http://dali.hywenlv.cn/Article/details/gtzabgheac.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.xziqi.cn/Article/details/gtjdmrluxh.html

[Q90] 生成序号列
来源：http://dali.nwbrower.top/Article/details/gtpqyjsnid.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.c1oappe.top/Article/details/gtlxttpygh.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtpzppbwwm.html

R. Bash 专题
来源：http://dali.yj202588.top/Article/details/gtggdlgrzq.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtchfnhdgs.html

[R01] shebang 与严格模式
来源：http://dali.nanxinkj.top/Article/details/gtjlwvkyvu.html

#!/usr/bin/env bash
来源：http://dali.shangyingyoupin.top/Article/details/gtspyqdmpq.html

set -euo pipefail
来源：http://dali.yj20258.top/Article/details/gttgueaqgo.html

[R02] 变量赋值与使用
来源：http://dali.hysaishi.cn/Article/details/gtgfxlzwsb.html

name="Tom"; echo "$name"
来源：http://dali.wangdashe.top/Article/details/gtucmjauwp.html

[R03] 只读变量
来源：http://dali.pycfn.com/Article/details/gthcserwqf.html

readonly PI=3.14
来源：http://dali.aibaodan.cn/Article/details/gtvubfywxe.html

[R04] 位置参数
来源：http://dali.yongpay.top/Article/details/gtusyssoxq.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.aibaodan.cn/Article/details/gtcndxseeg.html

[R05] 参数默认值
来源：http://dali.zycfv.cn/Article/details/gtxtgdkbmt.html

name="${1:-default}"
来源：http://dali.yj20258.top/Article/details/gtehdgjtib.html

[R06] 判断命令是否存在
来源：http://dali.jyoumei.cn/Article/details/gtiqknpbsh.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.xziqi.cn/Article/details/gtzqntgkvv.html

[R07] if 判断文件
来源：http://dali.tanke756.top/Article/details/gtwkvqmvwx.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.dianchejie.cn/Article/details/gtlfckuixk.html

[R08] 数值比较
来源：http://dali.nanxuanxn.top/Article/details/gttnawqzxa.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.birdmap.top/Article/details/gtczxehdlo.html

[R09] 字符串比较
来源：http://dali.sxryk.cn/Article/details/gtkalofkgo.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.aibaodan.cn/Article/details/gtjyuhplnb.html

[R10] 正则匹配
来源：http://dali.daria6918.cn/Article/details/gtbqtvndmh.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.gaohongyu789.top/Article/details/gtfcyuzfag.html

[R11] case 多分支
来源：http://dali.316326.xyz/Article/details/gtajzlsqok.html

case "$1" in
来源：http://dali.shuidangran.top/Article/details/gtbidrlaof.html

start) echo "启动" ;;
来源：http://dali.cashguo.top/Article/details/gtiilcdbzy.html

stop)  echo "停止" ;;
来源：http://dali.pengpengdd.cyou/Article/details/gtllianmle.html

*)     echo "未知命令" ;;
来源：http://dali.aizwys.cn/Article/details/gtvlvnebuw.html

esac
来源：http://dali.dashuyun.cn/Article/details/gttikciesj.html

[R12] for 遍历文件
来源：http://dali.ivvv.top/Article/details/gtjfdbcnph.html

for f in *.txt; do echo "$f"; done
来源：http://dali.jqgufenzy.top/Article/details/gtaiyvftoq.html

[R13] for 计数循环
来源：http://dali.aibaodan.cn/Article/details/gthpuqjrgg.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.yonumen.top/Article/details/gtydusrsnq.html

[R14] C 风格 for
来源：http://dali.chenzaomai.com/Article/details/gteghkhbrb.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.hammf.cn/Article/details/gtowbhwqlo.html

[R15] while 逐行读文件
来源：http://dali.dashuyun.cn/Article/details/gtgylclykj.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.pycfn.com/Article/details/gtntlecoum.html

[R16] until 等待条件
来源：http://dali.sysykeji.top/Article/details/gtsxddvytk.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhongyouzk.top/Article/details/gtmbcilajd.html

[R17] 数组定义与取值
来源：http://dali.shangyingyoupin.top/Article/details/gttqsqhlqu.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.chenjidiqi.icu/Article/details/gtaehgarkb.html

[R18] 遍历数组
来源：http://dali.wangdashe.top/Article/details/gtlsewvjvd.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.birdmap.top/Article/details/gtwsynoumt.html

[R19] 数组长度
来源：http://dali.9152youxi.cn/Article/details/gtataesasy.html

echo "${#arr[@]}"
来源：http://dali.wangshuangyany.cn/Article/details/gtnnoxydyf.html

[R20] 关联数组（字典）
来源：http://dali.gzhubu.top/Article/details/gtyncwmlzx.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.pengpengdd.cyou/Article/details/gtposjldte.html

[R21] 字符串长度
来源：http://dali.sysykeji.top/Article/details/gtfjtqykdb.html

echo "${#s}"
来源：http://dali.xuanzx.com/Article/details/gtllmfibgf.html

[R22] 截取子串
来源：http://dali.birdmap.top/Article/details/gtamtiqjds.html

echo "${s:0:5}"
来源：http://dali.316326.xyz/Article/details/gtsaeznnhi.html

[R23] 字符串替换
来源：http://dali.xziqi.cn/Article/details/gtlsgpttzb.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.yuanzhike.top/Article/details/gtcdeaqzra.html

[R24] 大小写转换
来源：http://dali.cashguo.top/Article/details/gtlncbsitd.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.hongshengwenyu.top/Article/details/gtvhbvtler.html

[R25] 去后缀 / 去前缀
来源：http://dali.jqgufenzy.top/Article/details/gtcfwycfgk.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.xylfe.cn/Article/details/gtqkqhvjzr.html

[R26] 命令替换
来源：http://dali.zhongyouzk.top/Article/details/gtrirgjlqe.html

now=$(date +%F); echo "$now"
来源：http://dali.shangyingyoupin.top/Article/details/gtdrjuutpi.html

[R27] 算术展开
来源：http://dali.pengpengdd.cyou/Article/details/gtbfpwgywq.html

echo $((1 + 2 * 3))
来源：http://dali.cashguo.top/Article/details/gtjbemaclm.html

[R28] 浮点运算
来源：http://dali.0kj1m.cn/Article/details/gtrkboaoaa.html

echo "scale=2; 10/3" | bc
来源：http://dali.chenlongwang.top/Article/details/gtddlgsogy.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gtvbnrzwum.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.ybcxt.top/Article/details/gttrlciobu.html

[R30] 函数返回状态码
来源：http://dali.fzhhl.top/Article/details/gtgyiqslsr.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.redwolf501.top/Article/details/gtcrgdgeeg.html

[R31] 局部变量
来源：http://dali.bjfxy.top/Article/details/gtspytwsux.html

f() { local x=1; echo "$x"; }
来源：http://dali.jinqigufen.top/Article/details/gtgeibcogp.html

[R32] 参数个数校验
来源：http://dali.gogol.net.cn/Article/details/gtcvrtkyaa.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.xuanzx.com/Article/details/gtrnwhpujc.html

[R33] 捕获错误并提示行号
来源：http://dali.daxiang520.top/Article/details/gtcxnafyhj.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.shzxlz.cn/Article/details/gtccddjekd.html

[R34] 退出时清理
来源：http://dali.zhengqikj.top/Article/details/gtkoavbngi.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.feifeiyinyue.top/Article/details/gtlmkvlzqe.html

[R35] 后台执行并等待
来源：http://dali.snrcjt.cn/Article/details/gtslijgcqq.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.dashuyun.cn/Article/details/gtfjbfoopl.html

[R36] 并发执行多个任务
来源：http://dali.jinqigufen.top/Article/details/gtdriqtnio.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.jinghuilouyu.cn/Article/details/gtooynhdtn.html

[R37] 把输出赋给变量
来源：http://dali.gogol.net.cn/Article/details/gtxzwzzzdo.html

files=$(ls -1)
来源：http://dali.snrcjt.cn/Article/details/gttnnjvtei.html

[R38] 管道串联
来源：http://dali.sysykeji.top/Article/details/gtbnokanmw.html

cat a.txt | grep -i error | wc -l
来源：http://dali.aizwys.cn/Article/details/gtdpfzaaeq.html

[R39] 重定向标准输出与错误
来源：http://dali.hnxiangtu.top/Article/details/gtqhnoknac.html

cmd > out.log 2>&1
来源：http://dali.bjfxy.top/Article/details/gtsnrharnp.html

[R40] 追加写日志
来源：http://dali.gzhubu.top/Article/details/gtxlokleqs.html

echo "log" >> out.log
来源：http://dali.pycfn.com/Article/details/gtbxgicrtf.html

[R41] 丢弃输出
来源：http://dali.316326.xyz/Article/details/gtxsfsmcvy.html

cmd >/dev/null 2>&1
来源：http://dali.dianchejie.cn/Article/details/gtyiksrall.html

[R42] 输入重定向
来源：http://dali.svipenyu.cn/Article/details/gtzfbgyxif.html

wc -l < a.txt
来源：http://dali.zdqjudy.top/Article/details/gttzmtabsm.html

[R43] 按名字查找文件
来源：http://dali.jyoumei.cn/Article/details/gtcmjgnjnz.html

find . -name "*.log" -type f
来源：http://dali.chenjidiqi.icu/Article/details/gtwahvlvhb.html

[R44] 按修改时间查找
来源：http://dali.sysykeji.top/Article/details/gtqbsjglmv.html

find . -mtime -7 -type f
来源：http://dali.ydzc1.top/Article/details/gtrinbvbij.html

[R45] 批量删除
来源：http://dali.zdqjudy.top/Article/details/gthwoijywn.html

find . -name "*.tmp" -delete
来源：http://dali.cashguo.top/Article/details/gtxrsnugud.html

[R46] 递归替换文件内容
来源：http://dali.tian-w.cn/Article/details/gtuuaplvsr.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.ppjwa.cn/Article/details/gtwplrjiix.html

[R47] sed 单行替换
来源：http://dali.smart0.xyz/Article/details/gthgzkyuzb.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.hnqzz.top/Article/details/gtizmsfuti.html

[R48] awk 取指定列
来源：http://dali.cucudq.cn/Article/details/gtecrdiapw.html

awk '{print $1, $3}' a.txt
来源：http://dali.yangfankeji.com/Article/details/gtplmmjbus.html

[R49] awk 带条件
来源：http://dali.tanke756.top/Article/details/gtkliebvbi.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.gotoacloud.top/Article/details/gttlzlcegi.html

[R50] awk 求和
来源：http://dali.smart0.xyz/Article/details/gtkrprtnho.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.birdmap.top/Article/details/gtglvqqzqt.html

[R51] 排序去重取前几
来源：http://dali.zhixingplan.top/Article/details/gttzrqjysn.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.yvedp.cn/Article/details/gtoxlvqoaz.html

[R52] 统计行数
来源：http://dali.birdmap.top/Article/details/gtlvjsonrl.html

wc -l a.txt
来源：http://dali.zhaomingkeji.xyz/Article/details/gtigvrsbgi.html

[R53] 查看文件头与实时尾
来源：http://dali.yuanzhike.top/Article/details/gtczqgkmsl.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.9152youxi.cn/Article/details/gtdtyiowxc.html

[R54] 比较两个文件
来源：http://dali.dianchejie.cn/Article/details/gtaaygxsjz.html

diff a.txt b.txt
来源：http://dali.shzxlz.cn/Article/details/gtnyqdoddv.html

[R55] 压缩与解压
来源：http://dali.aizwys.cn/Article/details/gtqcsjgeqf.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.snrcjt.cn/Article/details/gthoqcxbxy.html

[R56] 远程拷贝
来源：http://dali.yvedp.cn/Article/details/gtaxbigugl.html

scp file user@host:/path/
来源：http://dali.svipenyu.cn/Article/details/gtzchyhxje.html

[R57] 远程执行命令
来源：http://dali.daria6918.cn/Article/details/gtrjlrwvkp.html

ssh user@host 'uptime'
来源：http://dali.gzhubu.top/Article/details/gtchrmvtdz.html

[R58] 下载文件
来源：http://dali.pycfn.com/Article/details/gtybxfrshp.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.sweek.top/Article/details/gtpmluiwyu.html

[R59] 发 POST JSON
来源：http://dali.yongpay.top/Article/details/gtknzgqivd.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.dianchejie.cn/Article/details/gtsiljltrq.html

[R60] 只看 HTTP 状态码
来源：http://dali.guowangkeji.top/Article/details/gtprxafrpu.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.guowangkeji.top/Article/details/gtjukwkanx.html

[R61] 磁盘占用
来源：http://dali.guannengcc.top/Article/details/gtynfymkmx.html

df -h;  du -sh *
来源：http://dali.yvedp.cn/Article/details/gtcrkbzths.html

[R62] 找最占空间的文件
来源：http://dali.yangfankeji.com/Article/details/gtngvkxefe.html

du -ah . | sort -rh | head -10
来源：http://dali.zhiwuduotai.top/Article/details/gtwfxvahzh.html

[R63] 内存与进程
来源：http://dali.pycfn.com/Article/details/gtcadjissz.html

free -h;  ps aux | grep nginx
来源：http://dali.jqgfzy.top/Article/details/gtcembecbt.html

[R64] 结束进程
来源：http://dali.shanyushiyangkeji.top/Article/details/gtivcwanrl.html

kill -9 $(pgrep -f app.py)
来源：http://dali.jinghuilouyu.cn/Article/details/gtmmweauct.html

[R65] 查看端口占用
来源：http://dali.guannengcc.top/Article/details/gtiazosdzq.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.guannengcc.top/Article/details/gtnjswyxaq.html

[R66] 定时任务
来源：http://dali.jinqigfzy.top/Article/details/gtuzrupfxi.html

crontab -e;  crontab -l
来源：http://dali.gotoacloud.top/Article/details/gthdyqguva.html

[R67] 生成随机十六进制串
来源：http://dali.ybcxt.top/Article/details/gtvfrtkrbb.html

openssl rand -hex 16
来源：http://dali.fzhhl.top/Article/details/gtlrxtkdcf.html

[R68] 计算文件校验值
来源：http://dali.pengpengdd.cyou/Article/details/gtjgdkeqau.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.jqgufenzy.top/Article/details/gtinfkddjl.html

[R69] 生成随机密码
来源：http://dali.yuxming.cn/Article/details/gtruwkxoil.html

head -c 16 /dev/urandom | base64
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdohgrsty.html

[R70] 时间戳与互转
来源：http://dali.aibaodan.cn/Article/details/gtlnzzkmsd.html

date +%s;  date -d @1700000000
来源：http://dali.sufxvd.cn/Article/details/gtbaxufdfg.html

[R71] 日期格式化
来源：http://dali.pycfn.com/Article/details/gtbvyvilyx.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhiwuduotai.top/Article/details/gtgsgywfgd.html

[R72] 等待端口就绪
来源：http://dali.zhengqikj.top/Article/details/gtnlgvqlkf.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.meibo888.top/Article/details/gtfzuelsxc.html

[R73] 分割大日志
来源：http://dali.cdnleiting.top/Article/details/gtbciljtwq.html

split -l 1000 big.log part_
来源：http://dali.c1oappe.top/Article/details/gtbdpvkcrh.html

[R74] 批量重命名
来源：http://dali.jiagoushi.top/Article/details/gtaskbpcur.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.jiagoushi.top/Article/details/gtafptacay.html

[R75] 导出环境变量
来源：http://dali.yonumen.top/Article/details/gtnnvqjkks.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.sysykeji.top/Article/details/gtfimszxax.html

[R76] 使用临时文件
来源：http://dali.guannengcc.top/Article/details/gtzsgdttgy.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.havefunace.top/Article/details/gtxdyxeoqn.html

[R77] 读取用户输入
来源：http://dali.yueranfly.top/Article/details/gtughuhpsx.html

read -rp "请输入: " ans
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfmnakwfp.html

[R78] 交互式菜单
来源：http://dali.snrcjt.cn/Article/details/gthqrvjbzl.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.jqgufenzy.top/Article/details/gtgsmdsyth.html

[R79] 解析命令行选项
来源：http://dali.316326.xyz/Article/details/gtdycruntl.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.yj20258888.top/Article/details/gttiblgkyv.html

[R80] 查看脚本执行耗时
来源：http://dali.havefunace.top/Article/details/gtuweuofjg.html

time ./run.sh
来源：http://dali.zhongyouzk.top/Article/details/gtkhvdcpkf.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtjsrnprrl.html

S. C / C++ 专题
来源：http://dali.zycfv.cn/Article/details/gtltofjrvu.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdpbwfctf.html

[S01] C：Hello World
来源：http://dali.sufxvd.cn/Article/details/gtlgyqqlqq.html

#include <stdio.h>
来源：http://dali.sufxvd.cn/Article/details/gtjzlsmzcq.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.kuanghao11.cn/Article/details/gtubvrqrox.html

[S02] C：变量与格式化输出
来源：http://dali.cheryme.top/Article/details/gtppvkcojx.html

int a = 10; printf("%d\n", a);
来源：http://dali.pycfn.com/Article/details/gtipfhkbhf.html

[S03] C：读入整数
来源：http://dali.sysykeji.top/Article/details/gtskqtcfuq.html

int x; scanf("%d", &x);
来源：http://dali.quarkkingdee.top/Article/details/gtdzgcqhci.html

[S04] C：字符串复制
来源：http://dali.sxryk.cn/Article/details/gtnvtmumsf.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.redwolf501.top/Article/details/gtyqfrnyqc.html

[S05] C：字符串长度
来源：http://dali.chenzaomai.com/Article/details/gtgsomtzox.html

strlen(s)
来源：http://dali.zdqjudy.top/Article/details/gtbrusyqhq.html

[S06] C：字符串比较
来源：http://dali.fzhhl.top/Article/details/gtxrlnwzoe.html

strcmp(a, b) == 0
来源：http://dali.dianchejie.cn/Article/details/gttujlivjq.html

[S07] C：数组遍历求和
来源：http://dali.shzxlz.cn/Article/details/gtlujopnzr.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.yuanzhike.top/Article/details/gttahqvvdy.html

[S08] C：动态内存分配与释放
来源：http://dali.xuanzx.com/Article/details/gtyjkcgvlh.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.quarkkingdee.top/Article/details/gtiibjuezn.html

[S09] C：结构体定义与初始化
来源：http://dali.yangfankeji.com/Article/details/gtrbyygmct.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.sysykeji.top/Article/details/gtasrjuvqf.html

[S10] C：指针与解引用
来源：http://dali.havefunace.top/Article/details/gtnbnohoel.html

int *p = &a;  *p = 5;
来源：http://dali.hywenlv.cn/Article/details/gtjvstyhra.html

[S11] C：逐行读文件
来源：http://dali.guannengcc.top/Article/details/gttahpwamv.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.chenzaomai.com/Article/details/gtpfzjdwev.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.gotoacloud.top/Article/details/gtagvhnsqz.html

fclose(f);
来源：http://dali.jianghu66.top/Article/details/gtfthdpfab.html

[S12] C：写文件
来源：http://dali.hywenlv.cn/Article/details/gtwkkzuinv.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.jinyuanbaomall.cn/Article/details/gthlwrhrdw.html

[S13] C：宏定义
来源：http://dali.yonumen.top/Article/details/gtmdzksopx.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.yj20258888.top/Article/details/gtyboqhlbw.html

[S14] C：枚举
来源：http://dali.svipenyu.cn/Article/details/gtujqavyyx.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.havefunace.top/Article/details/gtorkcvzbg.html

[S15] C：类型转换
来源：http://dali.sxryk.cn/Article/details/gtrgfdijcg.html

(double) a / b
来源：http://dali.chenjidiqi.icu/Article/details/gtnnbidbea.html

[S16] C：位操作置位
来源：http://dali.tianlin.xyz/Article/details/gtwdvmaxok.html

x |= (1 << 3);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlxkqbqqz.html

[S17] C：安全拼接字符串
来源：http://dali.c1oappe.top/Article/details/gtujamfhmi.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.birdmap.top/Article/details/gttkmpysoc.html

[S18] C：命令行参数
来源：http://dali.quarkkingdee.top/Article/details/gtkzqpmaid.html

int main(int argc, char **argv)
来源：http://dali.jinqigufen.top/Article/details/gtmajlaasr.html

[S19] C：快速排序
来源：http://dali.hnxiangtu.top/Article/details/gtsygbasfb.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zycfv.cn/Article/details/gtzpzabazo.html

[S20] C：二分查找
来源：http://dali.smart0.xyz/Article/details/gttctvekyp.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.tian-w.cn/Article/details/gtoxjbkwip.html

[S21] C：字符类别判断
来源：http://dali.gotoacloud.top/Article/details/gtmhvxxmtz.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.quarkkingdee.top/Article/details/gtvlgyozkb.html

[S22] C：字符串转数字
来源：http://dali.jinqigufen.top/Article/details/gtojlwaand.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.bjfxy.top/Article/details/gtctoaopnd.html

[S23] C：随机数
来源：http://dali.xuanzx.com/Article/details/gtevovyhsg.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.guannengcc.top/Article/details/gtooexmnyx.html

[S24] C：获取本地时间
来源：http://dali.sweek.top/Article/details/gtyjlzibml.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.shuidangran.top/Article/details/gtkwoavyiu.html

[S25] C：内存拷贝
来源：http://dali.guowangkeji.top/Article/details/gtlreevbls.html

memcpy(dst, src, n);
来源：http://dali.smart0.xyz/Article/details/gtrlpglnvd.html

[S26] C：内存清零
来源：http://dali.shanyushiyangkeji.top/Article/details/gthybfihwk.html

memset(a, 0, sizeof a);
来源：http://dali.c1oappe.top/Article/details/gtjdetjwco.html

[S27] C：定义常量
来源：http://dali.gzhubu.top/Article/details/gtznsigzwq.html

const double PI = 3.14159;
来源：http://dali.wangshuangyany.cn/Article/details/gtzumitekl.html

[S28] C：静态变量
来源：http://dali.ivvv.top/Article/details/gtkgdplhlg.html

static int counter = 0;
来源：http://dali.jiagoushi.top/Article/details/gtnemhjuad.html

[S29] C：变参函数
来源：http://dali.xuanzx.com/Article/details/gtrqwohuqu.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.mhx1999.top/Article/details/gthiiehgew.html

[S30] C：头文件保护
来源：http://dali.xinyue.icu/Article/details/gtufsblfyx.html

#ifndef X_H
来源：http://dali.ivvv.top/Article/details/gtngrigcch.html

#define X_H
来源：http://dali.jqgfzy.top/Article/details/gtwszpgnsr.html

#endif
来源：http://dali.xinyue.icu/Article/details/gtqcmnqfqw.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gtiydenaok.html

#include <iostream>
来源：http://dali.xuetiantiany.cn/Article/details/gtxabfiqjj.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.jqgufenzy.top/Article/details/gtbovdvdjm.html

[S32] C++：字符串
来源：http://dali.zhaomingkeji.xyz/Article/details/gtagnwikbp.html

std::string s = "hi";  s += "!";
来源：http://dali.hfpthk.cn/Article/details/gtsqfztdjm.html

[S33] C++：vector 增删
来源：http://dali.dashuyun.cn/Article/details/gttwatnomn.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.sufxvd.cn/Article/details/gtruchfuib.html

[S34] C++：遍历 vector
来源：http://dali.svipenyu.cn/Article/details/gtfmtnzllo.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.quarkkingdee.top/Article/details/gtwrtcwzor.html

[S35] C++：map
来源：http://dali.yj20258.top/Article/details/gtcwnpzmza.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jinqigfzy.top/Article/details/gtnzcmztxo.html

[S36] C++：unordered_map
来源：http://dali.jlsjyb.cn/Article/details/gtqzcgxsgv.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.dianchejie.cn/Article/details/gthjzsfumw.html

[S37] C++：set
来源：http://dali.zhiwuduotai.top/Article/details/gtbamncmzf.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.ywan-chungtsiang.top/Article/details/gthwbkksdp.html

[S38] C++：排序
来源：http://dali.feifeiyinyue.top/Article/details/gtdzvxzroq.html

std::sort(v.begin(), v.end());
来源：http://dali.nanxinkj.top/Article/details/gttmibnjwr.html

[S39] C++：自定义比较器排序
来源：http://dali.ydzc1.top/Article/details/gtdglmbvvf.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.xziqi.cn/Article/details/gtiouzrlwm.html

[S40] C++：查找元素
来源：http://dali.tianlin.xyz/Article/details/gtswkrsttd.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.xziqi.cn/Article/details/gtatnanypk.html

[S41] C++：类与构造函数
来源：http://dali.snrcjt.cn/Article/details/gtazwdrsog.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zycfv.cn/Article/details/gtragdljxs.html

[S42] C++：继承与虚函数
来源：http://dali.tanke756.top/Article/details/gtgfbtlwig.html

class B : public Base { public: void f() override {} };
来源：http://dali.hongshengwenyu.top/Article/details/gtajvqwydj.html

[S43] C++：智能指针
来源：http://dali.fengsongda.top/Article/details/gtbaludnma.html

auto p = std::make_unique<int>(5);
来源：http://dali.sweek.top/Article/details/gtfoqafoqf.html

[S44] C++：引用传参
来源：http://dali.gotoacloud.top/Article/details/gtwmkuitln.html

void inc(int &x) { ++x; }
来源：http://dali.cdnleiting.top/Article/details/gtephrwbqc.html

[S45] C++：lambda
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgqfjnrxq.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.redwolf501.top/Article/details/gtvzwwpzrg.html

[S46] C++：函数模板
来源：http://dali.316326.xyz/Article/details/gtzrexiwuv.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.pycfn.com/Article/details/gtfrvtkhcv.html

[S47] C++：结构化绑定遍历
来源：http://dali.ywan-chungtsiang.top/Article/details/gtautqpchy.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhoulong.xyz/Article/details/gtizzhkgqo.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gtyehoyahc.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.gotoacloud.top/Article/details/gtexcztbzw.html

while (std::getline(in, line)) { }
来源：http://dali.tanke756.top/Article/details/gtkchifgai.html

[S49] C++：写文件
来源：http://dali.aizwys.cn/Article/details/gtgqsduqwx.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.hywenlv.cn/Article/details/gtpdsrjpsm.html

[S50] C++：格式化数字
来源：http://dali.aizwys.cn/Article/details/gtaguoaubt.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.quarkkingdee.top/Article/details/gtnajqnzdc.html

[S51] C++：显式类型转换
来源：http://dali.guannengcc.top/Article/details/gtmmfslkqs.html

static_cast<double>(a) / b
来源：http://dali.yueranfly.top/Article/details/gtviidvbvk.html

[S52] C++：const 与 noexcept
来源：http://dali.gotoacloud.top/Article/details/gtsrmxyeno.html

int size() const noexcept { return n_; }
来源：http://dali.hysaishi.cn/Article/details/gtsoqphqoi.html

[S53] C++：移动语义
来源：http://dali.yuxming.cn/Article/details/gtjjqbrqab.html

std::vector<int> w = std::move(v);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtplluizre.html

[S54] C++：异常处理
来源：http://dali.yanxiufei.cn/Article/details/gtjhsabqkl.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.guowangkeji.top/Article/details/gtctwddsbg.html

[S55] C++：结构化绑定
来源：http://dali.xziqi.cn/Article/details/gtkyfkhqcp.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhongyouzk.top/Article/details/gtlvayhwvz.html

[S56] C++：optional
来源：http://dali.wangshuangyany.cn/Article/details/gtawkizdfs.html


<!-- 参考信息 -->