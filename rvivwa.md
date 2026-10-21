代发 wailian999

[Q82] 字符长度与字节长度
来源：http://dali.yuanzhike.top/Article/details/gtbkvsqwzj.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.tanke756.top/Article/details/gtgocttoxw.html

[Q83] 大小写转换
来源：http://dali.nanxuanxn.top/Article/details/gtysifegqz.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.tianlin.xyz/Article/details/gtllctkyww.html

[Q84] 去除首尾空格
来源：http://dali.andypj.xyz/Article/details/gtonbrczor.html

SELECT TRIM(name) FROM users;
来源：http://dali.jianghu66.top/Article/details/gtdxyqsoar.html

[Q85] 数值取整
来源：http://dali.jianghu66.top/Article/details/gthkonygtz.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhengqikj.top/Article/details/gtsajlkfkr.html

[Q86] 读取 JSON 字段
来源：http://dali.zdqjudy.top/Article/details/gtpmklddmt.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.sweek.top/Article/details/gtdlgfabvn.html

[Q87] JSON 字段做条件
来源：http://dali.jianghu66.top/Article/details/gtsuhwgjum.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.feifeiyinyue.top/Article/details/gtbgzzfygy.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhiwuduotai.top/Article/details/gttusrstcq.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.iojbl.cn/Article/details/gtofeeanjd.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.hammf.cn/Article/details/gtorczugne.html

[Q89] 判断表是否存在
来源：http://dali.xziqi.cn/Article/details/gtsknacohf.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.sufxvd.cn/Article/details/gttuhsblvn.html

[Q90] 生成序号列
来源：http://dali.guowangkeji.top/Article/details/gtfbvkqwlk.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqypqqxbn.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtcyfhngdo.html

R. Bash 专题
来源：http://dali.yanxiufei.cn/Article/details/gtplueavzk.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtzrchdtln.html

[R01] shebang 与严格模式
来源：http://dali.pycfn.com/Article/details/gtnfzmbdth.html

#!/usr/bin/env bash
来源：http://dali.quarkkingdee.top/Article/details/gtiwqziccv.html

set -euo pipefail
来源：http://dali.jinghuilouyu.cn/Article/details/gtnjcpmfhj.html

[R02] 变量赋值与使用
来源：http://dali.pengpengdd.cyou/Article/details/gtsgqkzlbu.html

name="Tom"; echo "$name"
来源：http://dali.yj20258.top/Article/details/gtzfivdqeo.html

[R03] 只读变量
来源：http://dali.yueranfly.top/Article/details/gtsrtftjqk.html

readonly PI=3.14
来源：http://dali.guannengcc.top/Article/details/gtextlfqtg.html

[R04] 位置参数
来源：http://dali.shuidangran.top/Article/details/gtwyscnekx.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.fengsongda.top/Article/details/gtivhduvaa.html

[R05] 参数默认值
来源：http://dali.dianchejie.cn/Article/details/gttzrbmxfm.html

name="${1:-default}"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvinueoun.html

[R06] 判断命令是否存在
来源：http://dali.9152youxi.cn/Article/details/gtdambbkvu.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.nanxuanxn.top/Article/details/gttixeewqa.html

[R07] if 判断文件
来源：http://dali.hongshengwenyu.top/Article/details/gtuiggpeqg.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.pengpengdd.cyou/Article/details/gtivwqxusx.html

[R08] 数值比较
来源：http://dali.guowangkeji.top/Article/details/gtkoxcfnte.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.yonumen.top/Article/details/gtimtzzljj.html

[R09] 字符串比较
来源：http://dali.hysaishi.cn/Article/details/gtosvjtjgq.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.xinyue.icu/Article/details/gtjxfscbxx.html

[R10] 正则匹配
来源：http://dali.hywenlv.cn/Article/details/gtlejztzgx.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.hnxiangtu.top/Article/details/gtwnaimlta.html

[R11] case 多分支
来源：http://dali.ydzc1.top/Article/details/gtknazhgti.html

case "$1" in
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwmgbkfls.html

start) echo "启动" ;;
来源：http://dali.guowangkeji.top/Article/details/gtazbowmpw.html

stop)  echo "停止" ;;
来源：http://dali.wangshuangyany.cn/Article/details/gtpwvdlkus.html

*)     echo "未知命令" ;;
来源：http://dali.jianghu66.top/Article/details/gtfnvjyoly.html

esac
来源：http://dali.guowangkeji.top/Article/details/gtzmtzloed.html

[R12] for 遍历文件
来源：http://dali.redwolf501.top/Article/details/gtwenjxete.html

for f in *.txt; do echo "$f"; done
来源：http://dali.fengsongda.top/Article/details/gtmyrdsyyg.html

[R13] for 计数循环
来源：http://dali.sysykeji.top/Article/details/gtnczqrgoe.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.yongpay.top/Article/details/gtvlwjmzik.html

[R14] C 风格 for
来源：http://dali.andypj.xyz/Article/details/gtqnttbsmp.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.havefunace.top/Article/details/gteuaxyxcc.html

[R15] while 逐行读文件
来源：http://dali.jiagoushi.top/Article/details/gtcyqrsdlp.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.yanxiufei.cn/Article/details/gtqlkyxujt.html

[R16] until 等待条件
来源：http://dali.xuetiantiany.cn/Article/details/gtdrqvbqmp.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.gogol.net.cn/Article/details/gtcpfcyout.html

[R17] 数组定义与取值
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrsvhuoyv.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.gogol.net.cn/Article/details/gtfuxexauf.html

[R18] 遍历数组
来源：http://dali.316326.xyz/Article/details/gtdiiuoaei.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.nanxuanxn.top/Article/details/gtvtpionco.html

[R19] 数组长度
来源：http://dali.gaohongyu789.top/Article/details/gtgqttbcsm.html

echo "${#arr[@]}"
来源：http://dali.haohaochexian.top/Article/details/gtbphovzvq.html

[R20] 关联数组（字典）
来源：http://dali.yvedp.cn/Article/details/gtsiprbpdk.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.hywenlv.cn/Article/details/gtyvcipgyc.html

[R21] 字符串长度
来源：http://dali.guowangkeji.top/Article/details/gthbvtkrhg.html

echo "${#s}"
来源：http://dali.gotoacloud.top/Article/details/gtrvegtgfp.html

[R22] 截取子串
来源：http://dali.guannengcc.top/Article/details/gtwdzrqavy.html

echo "${s:0:5}"
来源：http://dali.xuanzx.com/Article/details/gtfyxgsryu.html

[R23] 字符串替换
来源：http://dali.shanyushiyangtech.top/Article/details/gtxmqwpioe.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.ivvv.top/Article/details/gthzbyeydr.html

[R24] 大小写转换
来源：http://dali.jinqigufen.top/Article/details/gtobubnzma.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.jiagoushi.top/Article/details/gtpexwihmj.html

[R25] 去后缀 / 去前缀
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdinehjmv.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.yanxiufei.cn/Article/details/gtkcdkozun.html

[R26] 命令替换
来源：http://dali.hnqzz.top/Article/details/gtjfjrqbpy.html

now=$(date +%F); echo "$now"
来源：http://dali.c1oappe.top/Article/details/gtacebbiid.html

[R27] 算术展开
来源：http://dali.pengpengdd.cyou/Article/details/gtqdmtjcvz.html

echo $((1 + 2 * 3))
来源：http://dali.hammf.cn/Article/details/gtbbifqxaq.html

[R28] 浮点运算
来源：http://dali.hnqzz.top/Article/details/gthknupmfs.html

echo "scale=2; 10/3" | bc
来源：http://dali.tian-w.cn/Article/details/gthtwmogcz.html

[R29] 定义函数
来源：http://dali.jianghu66.top/Article/details/gtgbbiyfvo.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.hfpthk.cn/Article/details/gtucttshsa.html

[R30] 函数返回状态码
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuxqzobnp.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.nanxuanxn.top/Article/details/gtoikckmcp.html

[R31] 局部变量
来源：http://dali.svipenyu.cn/Article/details/gtxkgcdzkt.html

f() { local x=1; echo "$x"; }
来源：http://dali.guannengcc.top/Article/details/gtrwgtibyo.html

[R32] 参数个数校验
来源：http://dali.wangshuangyany.cn/Article/details/gtkyetkqat.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.fzhhl.top/Article/details/gtuirkuooq.html

[R33] 捕获错误并提示行号
来源：http://dali.yvedp.cn/Article/details/gtqulkiwcp.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.svipenyu.cn/Article/details/gtjjadvwja.html

[R34] 退出时清理
来源：http://dali.316326.xyz/Article/details/gtiynxvcpc.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.aizwys.cn/Article/details/gtvvpwvswn.html

[R35] 后台执行并等待
来源：http://dali.yj20258888.top/Article/details/gtvsdmhwnt.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.sxryk.cn/Article/details/gtyhwnigjt.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gtpepguqqm.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.9152youxi.cn/Article/details/gtqjixotrh.html

[R37] 把输出赋给变量
来源：http://dali.kuanghao11.cn/Article/details/gtzhwrqiwx.html

files=$(ls -1)
来源：http://dali.sweek.top/Article/details/gtzdcnkfcs.html

[R38] 管道串联
来源：http://dali.chenlongwang.top/Article/details/gtzwrxvoza.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhengqikj.top/Article/details/gtmqpdibxy.html

[R39] 重定向标准输出与错误
来源：http://dali.yongpay.top/Article/details/gtorihwugr.html

cmd > out.log 2>&1
来源：http://dali.daxiang520.top/Article/details/gtpwiqmaag.html

[R40] 追加写日志
来源：http://dali.jianghu66.top/Article/details/gtzacxmyeo.html

echo "log" >> out.log
来源：http://dali.hfpthk.cn/Article/details/gtbbbzmfjk.html

[R41] 丢弃输出
来源：http://dali.xuetiantiany.cn/Article/details/gternyhuqy.html

cmd >/dev/null 2>&1
来源：http://dali.316326.xyz/Article/details/gtcptgkzln.html

[R42] 输入重定向
来源：http://dali.hnxiangtu.top/Article/details/gtwxfohtib.html

wc -l < a.txt
来源：http://dali.jqgufenzy.top/Article/details/gtpfmholao.html

[R43] 按名字查找文件
来源：http://dali.hysaishi.cn/Article/details/gtaxokjiqk.html

find . -name "*.log" -type f
来源：http://dali.cdnleiting.top/Article/details/gtgwbwluxd.html

[R44] 按修改时间查找
来源：http://dali.jinqigfzy.top/Article/details/gtbklcfkrb.html

find . -mtime -7 -type f
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyamurfyx.html

[R45] 批量删除
来源：http://dali.sufxvd.cn/Article/details/gtgwbcaxon.html

find . -name "*.tmp" -delete
来源：http://dali.wangdashe.top/Article/details/gtmkczzuzi.html

[R46] 递归替换文件内容
来源：http://dali.jianghu66.top/Article/details/gtunhbcjpk.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.shuidangran.top/Article/details/gtghgpcbte.html

[R47] sed 单行替换
来源：http://dali.yuanzhike.top/Article/details/gtlkntlcvl.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.jinghuilouyu.cn/Article/details/gtyskpxtqb.html

[R48] awk 取指定列
来源：http://dali.9152youxi.cn/Article/details/gtfjwceizn.html

awk '{print $1, $3}' a.txt
来源：http://dali.vqdsnc.cn/Article/details/gtokfqtudk.html

[R49] awk 带条件
来源：http://dali.hongshengwenyu.top/Article/details/gtxmzxcvdu.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.gogol.net.cn/Article/details/gtpunazyxd.html

[R50] awk 求和
来源：http://dali.feifeiyinyue.top/Article/details/gtbhpwjsxx.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.sxryk.cn/Article/details/gtmjoodmqt.html

[R51] 排序去重取前几
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnaqgwhvm.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.fengsongda.top/Article/details/gtdceeamsg.html

[R52] 统计行数
来源：http://dali.ydzc1.top/Article/details/gtechbwaco.html

wc -l a.txt
来源：http://dali.yueranfly.top/Article/details/gtkoghpbrx.html

[R53] 查看文件头与实时尾
来源：http://dali.mhx1999.top/Article/details/gtvsooapob.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zdqjudy.top/Article/details/gtgltzrmva.html

[R54] 比较两个文件
来源：http://dali.jinqigufen.top/Article/details/gttbjkywwy.html

diff a.txt b.txt
来源：http://dali.chenlongwang.top/Article/details/gtsqoiiflr.html

[R55] 压缩与解压
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxwldtkkn.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.jyoumei.cn/Article/details/gtakupcbfk.html

[R56] 远程拷贝
来源：http://dali.jianghu66.top/Article/details/gtzkqnascs.html

scp file user@host:/path/
来源：http://dali.cdnleiting.top/Article/details/gtxwsevyko.html

[R57] 远程执行命令
来源：http://dali.quarkkingdee.top/Article/details/gtdwnppkkl.html

ssh user@host 'uptime'
来源：http://dali.yvedp.cn/Article/details/gtkqtouiwp.html

[R58] 下载文件
来源：http://dali.dianchejie.cn/Article/details/gtifdacfne.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.xylfe.cn/Article/details/gthhzmbezy.html

[R59] 发 POST JSON
来源：http://dali.sufxvd.cn/Article/details/gtyynlythh.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.vqdsnc.cn/Article/details/gtgtehvypz.html

[R60] 只看 HTTP 状态码
来源：http://dali.nanxinkj.top/Article/details/gtxdpovqxt.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.xuetiantiany.cn/Article/details/gtfdtmzlej.html

[R61] 磁盘占用
来源：http://dali.zhengqikj.top/Article/details/gtwagwvloe.html

df -h;  du -sh *
来源：http://dali.hfpthk.cn/Article/details/gtvxljxzmi.html

[R62] 找最占空间的文件
来源：http://dali.ydzc1.top/Article/details/gtrhpdyuax.html

du -ah . | sort -rh | head -10
来源：http://dali.pengpengdd.cyou/Article/details/gtjcqnddqg.html

[R63] 内存与进程
来源：http://dali.xylfe.cn/Article/details/gtsbhnbfit.html

free -h;  ps aux | grep nginx
来源：http://dali.wangdashe.top/Article/details/gtdwrevrke.html

[R64] 结束进程
来源：http://dali.gotoacloud.top/Article/details/gtmlbvvvjn.html

kill -9 $(pgrep -f app.py)
来源：http://dali.smart0.xyz/Article/details/gtcgwwsdsz.html

[R65] 查看端口占用
来源：http://dali.c1oappe.top/Article/details/gtylkhtbrq.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.hnqzz.top/Article/details/gtzmcczdsr.html

[R66] 定时任务
来源：http://dali.iojbl.cn/Article/details/gtphgelzic.html

crontab -e;  crontab -l
来源：http://dali.hywenlv.cn/Article/details/gtdrrjazhk.html

[R67] 生成随机十六进制串
来源：http://dali.c1oappe.top/Article/details/gtjxkjrsjz.html

openssl rand -hex 16
来源：http://dali.yonumen.top/Article/details/gtjcqsecyj.html

[R68] 计算文件校验值
来源：http://dali.jinghuilouyu.cn/Article/details/gtgvroxfjb.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.yangfankeji.com/Article/details/gtnpvwgadm.html

[R69] 生成随机密码
来源：http://dali.ydzc1.top/Article/details/gtauhpkgvt.html

head -c 16 /dev/urandom | base64
来源：http://dali.smart0.xyz/Article/details/gtbgtjbfqy.html

[R70] 时间戳与互转
来源：http://dali.yuxming.cn/Article/details/gtdgyxndbg.html

date +%s;  date -d @1700000000
来源：http://dali.cucudq.cn/Article/details/gtrwfhybxs.html

[R71] 日期格式化
来源：http://dali.sysykeji.top/Article/details/gtrowryopm.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.daxiang520.top/Article/details/gtjmtdvtvp.html

[R72] 等待端口就绪
来源：http://dali.vqdsnc.cn/Article/details/gtneexnpky.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.ppjwa.cn/Article/details/gtwbufeqmz.html

[R73] 分割大日志
来源：http://dali.jiagoushi.top/Article/details/gtsoditzbh.html

split -l 1000 big.log part_
来源：http://dali.gaohongyu789.top/Article/details/gtuynijgpc.html

[R74] 批量重命名
来源：http://dali.haohaochexian.top/Article/details/gtqijgafzw.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.aibaodan.cn/Article/details/gtwnclaani.html

[R75] 导出环境变量
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmbveuryf.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.wangshuangyany.cn/Article/details/gtbxwdnfxv.html

[R76] 使用临时文件
来源：http://dali.hysaishi.cn/Article/details/gtnfetevrc.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.0kj1m.cn/Article/details/gtwqdndafs.html

[R77] 读取用户输入
来源：http://dali.snrcjt.cn/Article/details/gtxujqrsls.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gtvcieyepm.html

[R78] 交互式菜单
来源：http://dali.jqgfzy.top/Article/details/gtmvilmjus.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.xinyue.icu/Article/details/gtmghrxhvr.html

[R79] 解析命令行选项
来源：http://dali.cheryme.top/Article/details/gtwvyakncy.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhoulong.xyz/Article/details/gtttloasmt.html

[R80] 查看脚本执行耗时
来源：http://dali.shangyingyoupin.top/Article/details/gtlycjqrnj.html

time ./run.sh
来源：http://dali.sufxvd.cn/Article/details/gtaqilwilo.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtqhramive.html

S. C / C++ 专题
来源：http://dali.yj202588.top/Article/details/gtphwipoch.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtqepaahkd.html

[S01] C：Hello World
来源：http://dali.yvedp.cn/Article/details/gtlcuvulcz.html

#include <stdio.h>
来源：http://dali.sweek.top/Article/details/gtmpqtluxm.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.snrcjt.cn/Article/details/gtilwxmped.html

[S02] C：变量与格式化输出
来源：http://dali.zhixingplan.top/Article/details/gtazprnoku.html

int a = 10; printf("%d\n", a);
来源：http://dali.yangfankeji.com/Article/details/gtyqgzbyya.html

[S03] C：读入整数
来源：http://dali.xylfe.cn/Article/details/gtrydjajrc.html

int x; scanf("%d", &x);
来源：http://dali.daria6918.cn/Article/details/gtpyovzsaj.html

[S04] C：字符串复制
来源：http://dali.yvedp.cn/Article/details/gtvtrnkdys.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.fengsongda.top/Article/details/gtbojclzqz.html

[S05] C：字符串长度
来源：http://dali.yuxming.cn/Article/details/gtsbzunjtu.html

strlen(s)
来源：http://dali.hfpthk.cn/Article/details/gtvvvehzlp.html

[S06] C：字符串比较
来源：http://dali.xuanzx.com/Article/details/gtrisoxnii.html

strcmp(a, b) == 0
来源：http://dali.haohaochexian.top/Article/details/gtiefztbrq.html

[S07] C：数组遍历求和
来源：http://dali.sufxvd.cn/Article/details/gtdsbblgoc.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.yj202588.top/Article/details/gtqxhtqmse.html

[S08] C：动态内存分配与释放
来源：http://dali.gaohongyu789.top/Article/details/gtmrzkjwha.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.kuanghao11.cn/Article/details/gtyumsnpsu.html

[S09] C：结构体定义与初始化
来源：http://dali.snrcjt.cn/Article/details/gtgejgvsdu.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.316326.xyz/Article/details/gtfytlrnie.html

[S10] C：指针与解引用
来源：http://dali.c1oappe.top/Article/details/gtkctdgvsj.html

int *p = &a;  *p = 5;
来源：http://dali.bjfxy.top/Article/details/gtijjykhbs.html

[S11] C：逐行读文件
来源：http://dali.guannengcc.top/Article/details/gtpmogoiwx.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.yuxming.cn/Article/details/gtegszszhs.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.yueranfly.top/Article/details/gtacripofs.html

fclose(f);
来源：http://dali.xziqi.cn/Article/details/gtvazrmwpo.html

[S12] C：写文件
来源：http://dali.feifeiyinyue.top/Article/details/gtpfgmghcn.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.vqdsnc.cn/Article/details/gtrtjnpmej.html

[S13] C：宏定义
来源：http://dali.meibo888.top/Article/details/gtziajaopx.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.aibaodan.cn/Article/details/gtlfncbrmr.html

[S14] C：枚举
来源：http://dali.gogol.net.cn/Article/details/gtzdcwrmzs.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.fengsongda.top/Article/details/gtmebhvygk.html

[S15] C：类型转换
来源：http://dali.zdqjudy.top/Article/details/gtzihwulqc.html

(double) a / b
来源：http://dali.jinqigufen.top/Article/details/gternpwcln.html

[S16] C：位操作置位
来源：http://dali.meibo888.top/Article/details/gtxfoqxfqj.html

x |= (1 << 3);
来源：http://dali.kuanghao11.cn/Article/details/gtimorzwof.html

[S17] C：安全拼接字符串
来源：http://dali.yuanzhike.top/Article/details/gtrwzecuns.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.andypj.xyz/Article/details/gtyfukzuhf.html

[S18] C：命令行参数
来源：http://dali.zhongyouzk.top/Article/details/gtsfjztfrr.html

int main(int argc, char **argv)
来源：http://dali.smart0.xyz/Article/details/gtrubefivt.html

[S19] C：快速排序
来源：http://dali.guannengcc.top/Article/details/gtzatnwctg.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.hysaishi.cn/Article/details/gtandnwlvg.html

[S20] C：二分查找
来源：http://dali.jinqigfzy.top/Article/details/gtfroqvixm.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.xylfe.cn/Article/details/gtrgoqkebl.html

[S21] C：字符类别判断
来源：http://dali.yj202588.top/Article/details/gthendutfl.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.haohaochexian.top/Article/details/gtudsvrogd.html

[S22] C：字符串转数字
来源：http://dali.gogol.net.cn/Article/details/gtyfjevzll.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.yj202588.top/Article/details/gtrjcezirv.html

[S23] C：随机数
来源：http://dali.xziqi.cn/Article/details/gtbvscxuxs.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtigjkztkj.html

[S24] C：获取本地时间
来源：http://dali.jinghuilouyu.cn/Article/details/gtwabzmbok.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhongyouzk.top/Article/details/gthrlzpkkb.html

[S25] C：内存拷贝
来源：http://dali.yuanzhike.top/Article/details/gtbmopluvq.html

memcpy(dst, src, n);
来源：http://dali.birdmap.top/Article/details/gthdjeavyn.html

[S26] C：内存清零
来源：http://dali.yuanzhike.top/Article/details/gtkpoeakvq.html

memset(a, 0, sizeof a);
来源：http://dali.yvedp.cn/Article/details/gtpjyotsjb.html

[S27] C：定义常量
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwrqdjymx.html

const double PI = 3.14159;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbafdvbjm.html

[S28] C：静态变量
来源：http://dali.zhiwuduotai.top/Article/details/gtpnazmhoc.html

static int counter = 0;
来源：http://dali.bjfxy.top/Article/details/gtyfrzsvvy.html

[S29] C：变参函数
来源：http://dali.vqdsnc.cn/Article/details/gtiwydjpho.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.yuanzhike.top/Article/details/gtycslvpgs.html

[S30] C：头文件保护
来源：http://dali.jinqigufen.top/Article/details/gttofbdcjy.html

#ifndef X_H
来源：http://dali.wangdashe.top/Article/details/gtcvpbcxxs.html

#define X_H
来源：http://dali.gotoacloud.top/Article/details/gtscspksky.html

#endif
来源：http://dali.shanyushiyangtech.top/Article/details/gtzswtnwem.html

[S31] C++：Hello World
来源：http://dali.cheryme.top/Article/details/gtqcmrfnlf.html

#include <iostream>
来源：http://dali.daxiang520.top/Article/details/gtbenxrond.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.smart0.xyz/Article/details/gtfipmtaij.html

[S32] C++：字符串
来源：http://dali.wangdashe.top/Article/details/gtszscmjtg.html

std::string s = "hi";  s += "!";
来源：http://dali.xziqi.cn/Article/details/gtuwzsbxsj.html

[S33] C++：vector 增删
来源：http://dali.nanxuanxn.top/Article/details/gtiofidfih.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.yuxming.cn/Article/details/gtwhsovcok.html

[S34] C++：遍历 vector
来源：http://dali.yj20258888.top/Article/details/gtriryimwp.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhengqikj.top/Article/details/gtfgmqkcwt.html

[S35] C++：map
来源：http://dali.9152youxi.cn/Article/details/gtqblxyfhz.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.bjfxy.top/Article/details/gtnrtrbldf.html

[S36] C++：unordered_map
来源：http://dali.mhx1999.top/Article/details/gtuvzacuuw.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hnxiangtu.top/Article/details/gtujjupbde.html

[S37] C++：set
来源：http://dali.iojbl.cn/Article/details/gtkfwktbyx.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.hywenlv.cn/Article/details/gtgxtozhod.html

[S38] C++：排序
来源：http://dali.fengsongda.top/Article/details/gtijxtific.html

std::sort(v.begin(), v.end());
来源：http://dali.zdqjudy.top/Article/details/gtwiqqjtqm.html

[S39] C++：自定义比较器排序
来源：http://dali.yongpay.top/Article/details/gtooocctfj.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.ybcxt.top/Article/details/gtflelxjtg.html

[S40] C++：查找元素
来源：http://dali.sweek.top/Article/details/gtroycpxfi.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.shzxlz.cn/Article/details/gtuckysknx.html

[S41] C++：类与构造函数
来源：http://dali.snrcjt.cn/Article/details/gtkkfpfbjo.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.haohaochexian.top/Article/details/gtmmwayhmr.html

[S42] C++：继承与虚函数
来源：http://dali.shzxlz.cn/Article/details/gtpbscnoxf.html

class B : public Base { public: void f() override {} };
来源：http://dali.shzxlz.cn/Article/details/gterwcjxrp.html

[S43] C++：智能指针
来源：http://dali.vqdsnc.cn/Article/details/gtnfdpmpqm.html

auto p = std::make_unique<int>(5);
来源：http://dali.yangfankeji.com/Article/details/gtlhdwcrof.html

[S44] C++：引用传参
来源：http://dali.ehwqpu.com/Article/details/gtvsjkibcr.html

void inc(int &x) { ++x; }
来源：http://dali.xylfe.cn/Article/details/gtlyydohlq.html

[S45] C++：lambda
来源：http://dali.meibo888.top/Article/details/gtrpvkiltu.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.chenzaomai.com/Article/details/gtrzhtfrjl.html

[S46] C++：函数模板
来源：http://dali.yj20258888.top/Article/details/gtqdszkzxq.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.havefunace.top/Article/details/gtgxohfngg.html

[S47] C++：结构化绑定遍历
来源：http://dali.jianghu66.top/Article/details/gtjirgzhtf.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhongyouzk.top/Article/details/gtcdxqjxpt.html

[S48] C++：逐行读文件
来源：http://dali.9152youxi.cn/Article/details/gttkyrdxad.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.xziqi.cn/Article/details/gtrmafjatb.html

while (std::getline(in, line)) { }
来源：http://dali.meibo888.top/Article/details/gtvgvhtzlf.html

[S49] C++：写文件
来源：http://dali.shzxlz.cn/Article/details/gtfmohdmyj.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhengqikj.top/Article/details/gtfemvcufy.html

[S50] C++：格式化数字
来源：http://dali.fzhhl.top/Article/details/gtpvfdpdij.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.cqqwz.cn/Article/details/gtilncvdcb.html

[S51] C++：显式类型转换
来源：http://dali.jianghu66.top/Article/details/gtqsemeizr.html

static_cast<double>(a) / b
来源：http://dali.snrcjt.cn/Article/details/gtzyzjehey.html

[S52] C++：const 与 noexcept
来源：http://dali.jinqigufen.top/Article/details/gtdaundvff.html


<!-- 参考信息 -->