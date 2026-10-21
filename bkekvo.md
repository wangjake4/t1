代发 wailian999

[Q82] 字符长度与字节长度
来源：http://dali.xuetiantiany.cn/Article/details/gtxsilwqmz.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gtzeaighly.html

[Q83] 大小写转换
来源：http://dali.yonumen.top/Article/details/gtiioydfsh.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.ppjwa.cn/Article/details/gtjcoycvwe.html

[Q84] 去除首尾空格
来源：http://dali.yangfankeji.com/Article/details/gtbgyoxbtj.html

SELECT TRIM(name) FROM users;
来源：http://dali.ehwqpu.com/Article/details/gtuyqunmen.html

[Q85] 数值取整
来源：http://dali.dashuyun.cn/Article/details/gtxazztcng.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.cheryme.top/Article/details/gtjrdrfvvb.html

[Q86] 读取 JSON 字段
来源：http://dali.smart0.xyz/Article/details/gtwvlbguxb.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.mhx1999.top/Article/details/gtypwmhohj.html

[Q87] JSON 字段做条件
来源：http://dali.9152youxi.cn/Article/details/gtbncekxhf.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.smart0.xyz/Article/details/gtxjkilhuk.html

[Q88] 行转列（条件聚合）
来源：http://dali.yangfankeji.com/Article/details/gtftqaxvln.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.ivvv.top/Article/details/gtogfkyiqm.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhongyouzk.top/Article/details/gtuvrbngmq.html

[Q89] 判断表是否存在
来源：http://dali.zhongyouzk.top/Article/details/gtwhyyykue.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.yvedp.cn/Article/details/gtbcnuusqp.html

[Q90] 生成序号列
来源：http://dali.hywenlv.cn/Article/details/gtnnvfgveg.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.daria6918.cn/Article/details/gttqjdgmnv.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtzbyswlhy.html

R. Bash 专题
来源：http://dali.dianchejie.cn/Article/details/gtmdpdgvym.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtjlronfef.html

[R01] shebang 与严格模式
来源：http://dali.zhaomingkeji.xyz/Article/details/gteeogdstg.html

#!/usr/bin/env bash
来源：http://dali.iojbl.cn/Article/details/gteevafktv.html

set -euo pipefail
来源：http://dali.nanxuanxn.top/Article/details/gtfbudhzty.html

[R02] 变量赋值与使用
来源：http://dali.jinqigfzy.top/Article/details/gtjpxapaal.html

name="Tom"; echo "$name"
来源：http://dali.mhx1999.top/Article/details/gtmqejqygu.html

[R03] 只读变量
来源：http://dali.yj202588.top/Article/details/gtfxqnmeze.html

readonly PI=3.14
来源：http://dali.ivvv.top/Article/details/gtjtkxxahc.html

[R04] 位置参数
来源：http://dali.svipenyu.cn/Article/details/gtavabiwjw.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.ywan-chungtsiang.top/Article/details/gthohjcusw.html

[R05] 参数默认值
来源：http://dali.vqdsnc.cn/Article/details/gtbxavzbja.html

name="${1:-default}"
来源：http://dali.birdmap.top/Article/details/gtgbkacier.html

[R06] 判断命令是否存在
来源：http://dali.fzhhl.top/Article/details/gtqyhioyod.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.nanxinkj.top/Article/details/gtwkrzykkg.html

[R07] if 判断文件
来源：http://dali.jyoumei.cn/Article/details/gtzjwqbgje.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.ehwqpu.com/Article/details/gtwfjbmugd.html

[R08] 数值比较
来源：http://dali.cqqwz.cn/Article/details/gthcqvuazz.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.jinqigfzy.top/Article/details/gtvdrkvhkd.html

[R09] 字符串比较
来源：http://dali.ydzc1.top/Article/details/gtrxqawfhn.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.jyoumei.cn/Article/details/gtrnqlhdkk.html

[R10] 正则匹配
来源：http://dali.gotoacloud.top/Article/details/gtdbvrwzdx.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zycfv.cn/Article/details/gtmoeeectb.html

[R11] case 多分支
来源：http://dali.chenjidiqi.icu/Article/details/gtxtcvulsh.html

case "$1" in
来源：http://dali.nanxuanxn.top/Article/details/gtjjqhbqcd.html

start) echo "启动" ;;
来源：http://dali.jianghu66.top/Article/details/gtdcikoujt.html

stop)  echo "停止" ;;
来源：http://dali.jianghu66.top/Article/details/gtrphwdezy.html

*)     echo "未知命令" ;;
来源：http://dali.wangdashe.top/Article/details/gtttshklro.html

esac
来源：http://dali.iojbl.cn/Article/details/gtanumaqmh.html

[R12] for 遍历文件
来源：http://dali.kuanghao11.cn/Article/details/gtqwkgmvkt.html

for f in *.txt; do echo "$f"; done
来源：http://dali.nanxinkj.top/Article/details/gtzjdqehhg.html

[R13] for 计数循环
来源：http://dali.shangyingyoupin.top/Article/details/gtfnxzrifd.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.xinyue.icu/Article/details/gtoqhijnfo.html

[R14] C 风格 for
来源：http://dali.jlsjyb.cn/Article/details/gtxxelspwh.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.nwbrower.top/Article/details/gtlmugmngb.html

[R15] while 逐行读文件
来源：http://dali.redwolf501.top/Article/details/gtslkxskjn.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.sxryk.cn/Article/details/gtwwekllja.html

[R16] until 等待条件
来源：http://dali.shzxlz.cn/Article/details/gtuqxmgqxg.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.daria6918.cn/Article/details/gtthjcbgtb.html

[R17] 数组定义与取值
来源：http://dali.dianchejie.cn/Article/details/gtitmbfnnz.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.jiagoushi.top/Article/details/gthcbtiooa.html

[R18] 遍历数组
来源：http://dali.zhixingplan.top/Article/details/gtgbveagfj.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.jlsjyb.cn/Article/details/gtofxfrhqc.html

[R19] 数组长度
来源：http://dali.sufxvd.cn/Article/details/gthhullthp.html

echo "${#arr[@]}"
来源：http://dali.jinghuilouyu.cn/Article/details/gtqmctgqnv.html

[R20] 关联数组（字典）
来源：http://dali.tanke756.top/Article/details/gtjzqrgykt.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.hfpthk.cn/Article/details/gtqcciyrks.html

[R21] 字符串长度
来源：http://dali.feifeiyinyue.top/Article/details/gtgmnuitcc.html

echo "${#s}"
来源：http://dali.yonumen.top/Article/details/gttfbbxnhp.html

[R22] 截取子串
来源：http://dali.zycfv.cn/Article/details/gtuvjlvybp.html

echo "${s:0:5}"
来源：http://dali.zhengqikj.top/Article/details/gtxgysuwmc.html

[R23] 字符串替换
来源：http://dali.aizwys.cn/Article/details/gtpxwdnxyy.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhiwuduotai.top/Article/details/gtdvgtupxn.html

[R24] 大小写转换
来源：http://dali.gzhubu.top/Article/details/gtzmuqrnue.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.xylfe.cn/Article/details/gthodpbisn.html

[R25] 去后缀 / 去前缀
来源：http://dali.yj202588.top/Article/details/gtbxskvxib.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.yj20258.top/Article/details/gtczzijlew.html

[R26] 命令替换
来源：http://dali.sweek.top/Article/details/gtdvgduhsu.html

now=$(date +%F); echo "$now"
来源：http://dali.tian-w.cn/Article/details/gtoaitmpjg.html

[R27] 算术展开
来源：http://dali.zhongyouzk.top/Article/details/gtbnzhyshc.html

echo $((1 + 2 * 3))
来源：http://dali.tanke756.top/Article/details/gthxcifhwd.html

[R28] 浮点运算
来源：http://dali.fzhhl.top/Article/details/gtkciqyulq.html

echo "scale=2; 10/3" | bc
来源：http://dali.xziqi.cn/Article/details/gtwgplyygp.html

[R29] 定义函数
来源：http://dali.ydzc1.top/Article/details/gttrjlyffz.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.redwolf501.top/Article/details/gtudtwjvre.html

[R30] 函数返回状态码
来源：http://dali.jqgufenzy.top/Article/details/gtaayvgdfi.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.9152youxi.cn/Article/details/gtpweytlxs.html

[R31] 局部变量
来源：http://dali.wangshuangyany.cn/Article/details/gtzwtcysif.html

f() { local x=1; echo "$x"; }
来源：http://dali.chenjidiqi.icu/Article/details/gtrvpwyxgr.html

[R32] 参数个数校验
来源：http://dali.tian-w.cn/Article/details/gtdbchpkvn.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.sxryk.cn/Article/details/gtftoumccm.html

[R33] 捕获错误并提示行号
来源：http://dali.316326.xyz/Article/details/gtprezyxle.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.hywenlv.cn/Article/details/gthbkitggk.html

[R34] 退出时清理
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiffxamvz.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.aizwys.cn/Article/details/gtxdmcopik.html

[R35] 后台执行并等待
来源：http://dali.snrcjt.cn/Article/details/gtkrtdxdiv.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.bjfxy.top/Article/details/gtpvlmdnkn.html

[R36] 并发执行多个任务
来源：http://dali.tanke756.top/Article/details/gtcjmesahv.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhiwuduotai.top/Article/details/gtzhlalfoi.html

[R37] 把输出赋给变量
来源：http://dali.haohaochexian.top/Article/details/gtelugsrxs.html

files=$(ls -1)
来源：http://dali.gogol.net.cn/Article/details/gtpllwmwbg.html

[R38] 管道串联
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkhqjoxew.html

cat a.txt | grep -i error | wc -l
来源：http://dali.chenzaomai.com/Article/details/gtxthpcwwp.html

[R39] 重定向标准输出与错误
来源：http://dali.hfpthk.cn/Article/details/gtopzdaqtm.html

cmd > out.log 2>&1
来源：http://dali.hongshengwenyu.top/Article/details/gtlfqlppgy.html

[R40] 追加写日志
来源：http://dali.guannengcc.top/Article/details/gtgzuegwmt.html

echo "log" >> out.log
来源：http://dali.sufxvd.cn/Article/details/gtnhwyfmkz.html

[R41] 丢弃输出
来源：http://dali.yuxming.cn/Article/details/gtzodssvie.html

cmd >/dev/null 2>&1
来源：http://dali.xinyue.icu/Article/details/gtqarakipn.html

[R42] 输入重定向
来源：http://dali.cqqwz.cn/Article/details/gtfqtyuzqh.html

wc -l < a.txt
来源：http://dali.dashuyun.cn/Article/details/gtizzpjxwp.html

[R43] 按名字查找文件
来源：http://dali.yuanzhike.top/Article/details/gtwmeyneqa.html

find . -name "*.log" -type f
来源：http://dali.yj20258.top/Article/details/gtxihkktmp.html

[R44] 按修改时间查找
来源：http://dali.hongshengwenyu.top/Article/details/gtxzsfthyj.html

find . -mtime -7 -type f
来源：http://dali.xziqi.cn/Article/details/gtajmhwwkz.html

[R45] 批量删除
来源：http://dali.jianghu66.top/Article/details/gtekozwwzs.html

find . -name "*.tmp" -delete
来源：http://dali.tanke756.top/Article/details/gtshpbhmyt.html

[R46] 递归替换文件内容
来源：http://dali.jianghu66.top/Article/details/gtpumrytgx.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.tian-w.cn/Article/details/gtibubauxq.html

[R47] sed 单行替换
来源：http://dali.fengsongda.top/Article/details/gtrnskyhny.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.ydzc1.top/Article/details/gtrsrboreh.html

[R48] awk 取指定列
来源：http://dali.shanyushiyangkeji.top/Article/details/gtylhhzhst.html

awk '{print $1, $3}' a.txt
来源：http://dali.shangyingyoupin.top/Article/details/gtsypxyxty.html

[R49] awk 带条件
来源：http://dali.ydzc1.top/Article/details/gtpodkovln.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.tianlin.xyz/Article/details/gtgibafjfj.html

[R50] awk 求和
来源：http://dali.zycfv.cn/Article/details/gtzhwzyzeb.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.ivvv.top/Article/details/gtilcakkrp.html

[R51] 排序去重取前几
来源：http://dali.jiagoushi.top/Article/details/gtksvwrjtv.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.ivvv.top/Article/details/gtfvsjbpwb.html

[R52] 统计行数
来源：http://dali.nanxinkj.top/Article/details/gthxsjpamo.html

wc -l a.txt
来源：http://dali.ivvv.top/Article/details/gtsqawtxsn.html

[R53] 查看文件头与实时尾
来源：http://dali.ywan-chungtsiang.top/Article/details/gtowqzrktv.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.gaohongyu789.top/Article/details/gtfjrxbryn.html

[R54] 比较两个文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvchwsvqn.html

diff a.txt b.txt
来源：http://dali.guannengcc.top/Article/details/gtdoxtzczg.html

[R55] 压缩与解压
来源：http://dali.sufxvd.cn/Article/details/gtaiyuywxh.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkxfegzwt.html

[R56] 远程拷贝
来源：http://dali.0kj1m.cn/Article/details/gtfnnwuhyr.html

scp file user@host:/path/
来源：http://dali.daxiang520.top/Article/details/gtskdknesa.html

[R57] 远程执行命令
来源：http://dali.jqgfzy.top/Article/details/gtmtkpikpb.html

ssh user@host 'uptime'
来源：http://dali.yongpay.top/Article/details/gtvzwzzzhk.html

[R58] 下载文件
来源：http://dali.yj202588.top/Article/details/gtoteneulu.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.dashuyun.cn/Article/details/gtgkqurjrs.html

[R59] 发 POST JSON
来源：http://dali.hfpthk.cn/Article/details/gtsacxeeib.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.birdmap.top/Article/details/gtxwbxhnps.html

[R60] 只看 HTTP 状态码
来源：http://dali.xinyue.icu/Article/details/gtdezayndo.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.c1oappe.top/Article/details/gtqnoxllvb.html

[R61] 磁盘占用
来源：http://dali.jianghu66.top/Article/details/gtwydzzauv.html

df -h;  du -sh *
来源：http://dali.daxiang520.top/Article/details/gtuxdtbxcg.html

[R62] 找最占空间的文件
来源：http://dali.0kj1m.cn/Article/details/gtovwtuntg.html

du -ah . | sort -rh | head -10
来源：http://dali.zycfv.cn/Article/details/gttqqoczyj.html

[R63] 内存与进程
来源：http://dali.jiagoushi.top/Article/details/gtoshvmczt.html

free -h;  ps aux | grep nginx
来源：http://dali.ywan-chungtsiang.top/Article/details/gtszxmxpde.html

[R64] 结束进程
来源：http://dali.gaohongyu789.top/Article/details/gtsvzlvklj.html

kill -9 $(pgrep -f app.py)
来源：http://dali.redwolf501.top/Article/details/gtcwjqzxpw.html

[R65] 查看端口占用
来源：http://dali.pycfn.com/Article/details/gtxbmocmwa.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhongyouzk.top/Article/details/gtpzmyskfb.html

[R66] 定时任务
来源：http://dali.chenzaomai.com/Article/details/gtjpkifnuh.html

crontab -e;  crontab -l
来源：http://dali.yanxiufei.cn/Article/details/gtevrtudua.html

[R67] 生成随机十六进制串
来源：http://dali.c1oappe.top/Article/details/gthjljsynw.html

openssl rand -hex 16
来源：http://dali.fengsongda.top/Article/details/gtwjppvlqw.html

[R68] 计算文件校验值
来源：http://dali.jianghu66.top/Article/details/gtnihmvlex.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.xinyue.icu/Article/details/gtwcauzniu.html

[R69] 生成随机密码
来源：http://dali.xylfe.cn/Article/details/gtfkrbwxlt.html

head -c 16 /dev/urandom | base64
来源：http://dali.chenlongwang.top/Article/details/gtpsnrhhxa.html

[R70] 时间戳与互转
来源：http://dali.pycfn.com/Article/details/gtreplogsw.html

date +%s;  date -d @1700000000
来源：http://dali.andypj.xyz/Article/details/gtmtdkyqps.html

[R71] 日期格式化
来源：http://dali.daxiang520.top/Article/details/gtebynwkep.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.hywenlv.cn/Article/details/gtibhcimab.html

[R72] 等待端口就绪
来源：http://dali.sysykeji.top/Article/details/gtlemqcoph.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.yj20258.top/Article/details/gtfnkihoeh.html

[R73] 分割大日志
来源：http://dali.aibaodan.cn/Article/details/gtgtbzopti.html

split -l 1000 big.log part_
来源：http://dali.jqgfzy.top/Article/details/gthfkzbobx.html

[R74] 批量重命名
来源：http://dali.9152youxi.cn/Article/details/gtzzkzcdjm.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.tanke756.top/Article/details/gtbmszazjb.html

[R75] 导出环境变量
来源：http://dali.chenzaomai.com/Article/details/gtggejbiul.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhongyouzk.top/Article/details/gtvdbwewkg.html

[R76] 使用临时文件
来源：http://dali.yuanzhike.top/Article/details/gtjjcslzfq.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.9152youxi.cn/Article/details/gtbostbgza.html

[R77] 读取用户输入
来源：http://dali.jianghu66.top/Article/details/gtwigjkbjb.html

read -rp "请输入: " ans
来源：http://dali.zycfv.cn/Article/details/gtcsxkyipj.html

[R78] 交互式菜单
来源：http://dali.snrcjt.cn/Article/details/gtdakrekrw.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.sysykeji.top/Article/details/gtxacuxvww.html

[R79] 解析命令行选项
来源：http://dali.mhx1999.top/Article/details/gtfoatwmez.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.haohaochexian.top/Article/details/gttnxzicmq.html

[R80] 查看脚本执行耗时
来源：http://dali.xinyue.icu/Article/details/gtpslruhjn.html

time ./run.sh
来源：http://dali.xuetiantiany.cn/Article/details/gtvcfeotqb.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtmciptamv.html

S. C / C++ 专题
来源：http://dali.yj20258.top/Article/details/gtlbkaqkix.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtajsbovfd.html

[S01] C：Hello World
来源：http://dali.tanke756.top/Article/details/gtuyhgcsko.html

#include <stdio.h>
来源：http://dali.tian-w.cn/Article/details/gtlquwwtno.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.shangyingyoupin.top/Article/details/gtpijivqwt.html

[S02] C：变量与格式化输出
来源：http://dali.andypj.xyz/Article/details/gtihbiguaj.html

int a = 10; printf("%d\n", a);
来源：http://dali.mhx1999.top/Article/details/gtcxbrvrqu.html

[S03] C：读入整数
来源：http://dali.jiagoushi.top/Article/details/gtnazhbwrf.html

int x; scanf("%d", &x);
来源：http://dali.gzhubu.top/Article/details/gtwypjvujl.html

[S04] C：字符串复制
来源：http://dali.feifeiyinyue.top/Article/details/gtdmlwbqqq.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.tianlin.xyz/Article/details/gtyleeumwu.html

[S05] C：字符串长度
来源：http://dali.yj20258.top/Article/details/gtvuyfvxdm.html

strlen(s)
来源：http://dali.feifeiyinyue.top/Article/details/gtnusrczbn.html

[S06] C：字符串比较
来源：http://dali.jinqigfzy.top/Article/details/gtxsucnwpa.html

strcmp(a, b) == 0
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxuwqpnuq.html

[S07] C：数组遍历求和
来源：http://dali.zhixingplan.top/Article/details/gtksmavrse.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.dianchejie.cn/Article/details/gtkpjshmud.html

[S08] C：动态内存分配与释放
来源：http://dali.jinqigfzy.top/Article/details/gtgqgfogbt.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.jqgufenzy.top/Article/details/gtnkjsadvd.html

[S09] C：结构体定义与初始化
来源：http://dali.gzhubu.top/Article/details/gtalxisklu.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkifmksyo.html

[S10] C：指针与解引用
来源：http://dali.zhixingplan.top/Article/details/gtwxcxdbgu.html

int *p = &a;  *p = 5;
来源：http://dali.9152youxi.cn/Article/details/gtzujbqufc.html

[S11] C：逐行读文件
来源：http://dali.haohaochexian.top/Article/details/gtjnsvpmyn.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.hfpthk.cn/Article/details/gttoplmdbm.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.havefunace.top/Article/details/gtdekspsbr.html

fclose(f);
来源：http://dali.jqgfzy.top/Article/details/gtybiyebuw.html

[S12] C：写文件
来源：http://dali.sweek.top/Article/details/gtqogdqogs.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.shangyingyoupin.top/Article/details/gtwpqxsqiu.html

[S13] C：宏定义
来源：http://dali.hfpthk.cn/Article/details/gtaeihsiad.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.quarkkingdee.top/Article/details/gtdeiofixd.html

[S14] C：枚举
来源：http://dali.hnxiangtu.top/Article/details/gthxxzgbst.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.cucudq.cn/Article/details/gtioodzotv.html

[S15] C：类型转换
来源：http://dali.zhixingplan.top/Article/details/gtxbqqtcgh.html

(double) a / b
来源：http://dali.zhongyouzk.top/Article/details/gtxdfejsyb.html

[S16] C：位操作置位
来源：http://dali.jinqigufen.top/Article/details/gttqlszvis.html

x |= (1 << 3);
来源：http://dali.chenjidiqi.icu/Article/details/gtxuguifke.html

[S17] C：安全拼接字符串
来源：http://dali.jlsjyb.cn/Article/details/gtmqijhlmb.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.feifeiyinyue.top/Article/details/gtiluyyreq.html

[S18] C：命令行参数
来源：http://dali.jyoumei.cn/Article/details/gtuxjayjsp.html

int main(int argc, char **argv)
来源：http://dali.hongshengwenyu.top/Article/details/gtjzbtdtxw.html

[S19] C：快速排序
来源：http://dali.smart0.xyz/Article/details/gtahdlvkix.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.yuanzhike.top/Article/details/gtkufruaxj.html

[S20] C：二分查找
来源：http://dali.iojbl.cn/Article/details/gtpbcfrbks.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.meibo888.top/Article/details/gtovlzoujy.html

[S21] C：字符类别判断
来源：http://dali.nanxinkj.top/Article/details/gtyfiuqppy.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.sufxvd.cn/Article/details/gtxmppyvix.html

[S22] C：字符串转数字
来源：http://dali.cheryme.top/Article/details/gtvpzdevfw.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.hammf.cn/Article/details/gtxjiizrrw.html

[S23] C：随机数
来源：http://dali.ybcxt.top/Article/details/gtznjpmjcb.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.jinghuilouyu.cn/Article/details/gtutqkxwip.html

[S24] C：获取本地时间
来源：http://dali.haohaochexian.top/Article/details/gttyxijqsm.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.bjfxy.top/Article/details/gtgzxegzei.html

[S25] C：内存拷贝
来源：http://dali.nanxinkj.top/Article/details/gtqktjpfxk.html

memcpy(dst, src, n);
来源：http://dali.aibaodan.cn/Article/details/gtiffevmqz.html

[S26] C：内存清零
来源：http://dali.xinyue.icu/Article/details/gtqelonkyc.html

memset(a, 0, sizeof a);
来源：http://dali.dianchejie.cn/Article/details/gtcnzhlpvf.html

[S27] C：定义常量
来源：http://dali.xuetiantiany.cn/Article/details/gtupgqtkkp.html

const double PI = 3.14159;
来源：http://dali.316326.xyz/Article/details/gtmclqwoed.html

[S28] C：静态变量
来源：http://dali.jqgufenzy.top/Article/details/gtnfubwrwy.html

static int counter = 0;
来源：http://dali.ybcxt.top/Article/details/gtdxdqlnix.html

[S29] C：变参函数
来源：http://dali.shzxlz.cn/Article/details/gtyhkyklkr.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.redwolf501.top/Article/details/gtvftlkwvo.html

[S30] C：头文件保护
来源：http://dali.shuidangran.top/Article/details/gtmwzaberv.html

#ifndef X_H
来源：http://dali.yj20258888.top/Article/details/gtmdbwgeeb.html

#define X_H
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvtygifaf.html

#endif
来源：http://dali.cucudq.cn/Article/details/gtzxihlgva.html

[S31] C++：Hello World
来源：http://dali.wangdashe.top/Article/details/gtzgiecprh.html

#include <iostream>
来源：http://dali.0kj1m.cn/Article/details/gtarclomhg.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.daxiang520.top/Article/details/gtstkaepcu.html

[S32] C++：字符串
来源：http://dali.zdqjudy.top/Article/details/gtjhqktzjq.html

std::string s = "hi";  s += "!";
来源：http://dali.yonumen.top/Article/details/gtcznlcfkm.html

[S33] C++：vector 增删
来源：http://dali.jiagoushi.top/Article/details/gtntumfulh.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.sysykeji.top/Article/details/gttdpihygz.html

[S34] C++：遍历 vector
来源：http://dali.ehwqpu.com/Article/details/gtiqeiatrm.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.pengpengdd.cyou/Article/details/gtaxenpxcd.html

[S35] C++：map
来源：http://dali.gaohongyu789.top/Article/details/gtotpavbjt.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jqgfzy.top/Article/details/gtpwnhvoaf.html

[S36] C++：unordered_map
来源：http://dali.gaohongyu789.top/Article/details/gtludkdpxt.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhiwuduotai.top/Article/details/gttzzmwqvw.html

[S37] C++：set
来源：http://dali.shanyushiyangtech.top/Article/details/gtyizvdtxj.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.redwolf501.top/Article/details/gtcqcuzwar.html

[S38] C++：排序
来源：http://dali.andypj.xyz/Article/details/gttpegkyfn.html

std::sort(v.begin(), v.end());
来源：http://dali.xylfe.cn/Article/details/gtvtzwutbp.html

[S39] C++：自定义比较器排序
来源：http://dali.jqgufenzy.top/Article/details/gtsdylujcp.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.gzhubu.top/Article/details/gtgverdxpo.html

[S40] C++：查找元素
来源：http://dali.chenzaomai.com/Article/details/gtmjhafjcc.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.cashguo.top/Article/details/gtorrujbon.html

[S41] C++：类与构造函数
来源：http://dali.0kj1m.cn/Article/details/gtzjmuvopf.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.yvedp.cn/Article/details/gtabsyogax.html

[S42] C++：继承与虚函数
来源：http://dali.9152youxi.cn/Article/details/gtwpzkpanx.html

class B : public Base { public: void f() override {} };
来源：http://dali.svipenyu.cn/Article/details/gtsawkfeys.html

[S43] C++：智能指针
来源：http://dali.ehwqpu.com/Article/details/gtutmsowzm.html

auto p = std::make_unique<int>(5);
来源：http://dali.jlsjyb.cn/Article/details/gtrdnmjvas.html

[S44] C++：引用传参
来源：http://dali.wangshuangyany.cn/Article/details/gtpujogdec.html

void inc(int &x) { ++x; }
来源：http://dali.chenjidiqi.icu/Article/details/gtlguipqbq.html

[S45] C++：lambda
来源：http://dali.c1oappe.top/Article/details/gtoqpydndd.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.gotoacloud.top/Article/details/gtivexobig.html

[S46] C++：函数模板
来源：http://dali.ehwqpu.com/Article/details/gtzqoahzdv.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.guannengcc.top/Article/details/gtlhyqzuel.html

[S47] C++：结构化绑定遍历
来源：http://dali.mhx1999.top/Article/details/gthvqkfrqi.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.kuanghao11.cn/Article/details/gtfwkwaree.html

[S48] C++：逐行读文件
来源：http://dali.yj20258.top/Article/details/gtbrpdyrlk.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gtrpxznoko.html

while (std::getline(in, line)) { }
来源：http://dali.zycfv.cn/Article/details/gtqdpmiqnn.html

[S49] C++：写文件
来源：http://dali.tanke756.top/Article/details/gtnlrwzbth.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.jianghu66.top/Article/details/gtkqjjsqwf.html

[S50] C++：格式化数字
来源：http://dali.hammf.cn/Article/details/gtgwzvnqdi.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.tian-w.cn/Article/details/gtwsbrkkfy.html

[S51] C++：显式类型转换
来源：http://dali.birdmap.top/Article/details/gtxosbrzce.html

static_cast<double>(a) / b
来源：http://dali.yangfankeji.com/Article/details/gtoaejatjv.html

[S52] C++：const 与 noexcept
来源：http://dali.ybcxt.top/Article/details/gtpqwkknqd.html


<!-- 参考信息 -->