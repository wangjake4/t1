代发 wailian999

[Q82] 字符长度与字节长度
来源：http://dali.jinqigfzy.top/Article/details/gtlteqbuue.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.sufxvd.cn/Article/details/gtnhtdqmyn.html

[Q83] 大小写转换
来源：http://dali.jqgufenzy.top/Article/details/gtjlcaunvn.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.chenzaomai.com/Article/details/gtzofmevld.html

[Q84] 去除首尾空格
来源：http://dali.haohaochexian.top/Article/details/gtcztoxsyh.html

SELECT TRIM(name) FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gtqtkvnxxc.html

[Q85] 数值取整
来源：http://dali.daria6918.cn/Article/details/gtswumuvfl.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.svipenyu.cn/Article/details/gtccfbsqws.html

[Q86] 读取 JSON 字段
来源：http://dali.yuanzhike.top/Article/details/gtuaucrlqw.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.jinqigfzy.top/Article/details/gtwolrxayf.html

[Q87] JSON 字段做条件
来源：http://dali.pengpengdd.cyou/Article/details/gtgagirnfg.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.tanke756.top/Article/details/gtpwyohorp.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhiwuduotai.top/Article/details/gtahcmsctc.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.jinqigfzy.top/Article/details/gthrnykvni.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.yueranfly.top/Article/details/gtjomfegnm.html

[Q89] 判断表是否存在
来源：http://dali.ppjwa.cn/Article/details/gtlkfwyvgw.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.yonumen.top/Article/details/gtyniqxhvg.html

[Q90] 生成序号列
来源：http://dali.shangyingyoupin.top/Article/details/gtznqgzsfk.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.sufxvd.cn/Article/details/gtrkdoyalq.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtfrvxqnld.html

R. Bash 专题
来源：http://dali.zhoulong.xyz/Article/details/gtdysjyuwv.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtpmiucsdf.html

[R01] shebang 与严格模式
来源：http://dali.shuidangran.top/Article/details/gtisayejnz.html

#!/usr/bin/env bash
来源：http://dali.ivvv.top/Article/details/gtoucqqsyq.html

set -euo pipefail
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxjvaktes.html

[R02] 变量赋值与使用
来源：http://dali.shangyingyoupin.top/Article/details/gtfdmxykeu.html

name="Tom"; echo "$name"
来源：http://dali.gotoacloud.top/Article/details/gtdvdauhha.html

[R03] 只读变量
来源：http://dali.mhx1999.top/Article/details/gtxokxfqrj.html

readonly PI=3.14
来源：http://dali.9152youxi.cn/Article/details/gtekqroehk.html

[R04] 位置参数
来源：http://dali.cucudq.cn/Article/details/gtargstgfc.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.yangfankeji.com/Article/details/gtjzjusuof.html

[R05] 参数默认值
来源：http://dali.cqqwz.cn/Article/details/gtzrvqfmvn.html

name="${1:-default}"
来源：http://dali.jqgufenzy.top/Article/details/gtvupvukhn.html

[R06] 判断命令是否存在
来源：http://dali.316326.xyz/Article/details/gtrxdvtdxb.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.hnxiangtu.top/Article/details/gthkeikcif.html

[R07] if 判断文件
来源：http://dali.jinqigufen.top/Article/details/gtbgiqyqve.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.yueranfly.top/Article/details/gtxobalvan.html

[R08] 数值比较
来源：http://dali.haohaochexian.top/Article/details/gtwglznrli.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.shzxlz.cn/Article/details/gtsotezepb.html

[R09] 字符串比较
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfmqpnjqt.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.sxryk.cn/Article/details/gtrcxaszgi.html

[R10] 正则匹配
来源：http://dali.andypj.xyz/Article/details/gtwwfbdgyo.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.gotoacloud.top/Article/details/gtlxdohdhz.html

[R11] case 多分支
来源：http://dali.cucudq.cn/Article/details/gtcammkzex.html

case "$1" in
来源：http://dali.dashuyun.cn/Article/details/gtcjqituki.html

start) echo "启动" ;;
来源：http://dali.jinghuilouyu.cn/Article/details/gtjuglisya.html

stop)  echo "停止" ;;
来源：http://dali.0kj1m.cn/Article/details/gtxuccblkr.html

*)     echo "未知命令" ;;
来源：http://dali.pengpengdd.cyou/Article/details/gtfpcqgkip.html

esac
来源：http://dali.kuanghao11.cn/Article/details/gtittshwvg.html

[R12] for 遍历文件
来源：http://dali.kuanghao11.cn/Article/details/gtxgxtektt.html

for f in *.txt; do echo "$f"; done
来源：http://dali.yvedp.cn/Article/details/gtsjjfpjbg.html

[R13] for 计数循环
来源：http://dali.yj202588.top/Article/details/gtkrfkcbfs.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.shuidangran.top/Article/details/gtwojvaytq.html

[R14] C 风格 for
来源：http://dali.c1oappe.top/Article/details/gtzndugldu.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gtktnhodlc.html

[R15] while 逐行读文件
来源：http://dali.redwolf501.top/Article/details/gtjsisnzon.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.cdnleiting.top/Article/details/gtfzolzvns.html

[R16] until 等待条件
来源：http://dali.yongpay.top/Article/details/gtwegcgisn.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaeyofsid.html

[R17] 数组定义与取值
来源：http://dali.jianghu66.top/Article/details/gtknyofciw.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.iojbl.cn/Article/details/gtocrmkney.html

[R18] 遍历数组
来源：http://dali.pycfn.com/Article/details/gttwqmnjju.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.tianlin.xyz/Article/details/gtzwcaibha.html

[R19] 数组长度
来源：http://dali.hnxiangtu.top/Article/details/gtgfbtzipg.html

echo "${#arr[@]}"
来源：http://dali.andypj.xyz/Article/details/gtaqqpayec.html

[R20] 关联数组（字典）
来源：http://dali.fzhhl.top/Article/details/gtfssqklvf.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.yangfankeji.com/Article/details/gthyagyext.html

[R21] 字符串长度
来源：http://dali.yvedp.cn/Article/details/gtpplnygwe.html

echo "${#s}"
来源：http://dali.xinyue.icu/Article/details/gtrtosfooj.html

[R22] 截取子串
来源：http://dali.tianlin.xyz/Article/details/gtwccaampg.html

echo "${s:0:5}"
来源：http://dali.jlsjyb.cn/Article/details/gtufzpwczy.html

[R23] 字符串替换
来源：http://dali.nwbrower.top/Article/details/gtgrlfcgbu.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.iojbl.cn/Article/details/gtinmhrheq.html

[R24] 大小写转换
来源：http://dali.hammf.cn/Article/details/gtdnnmcrwv.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.ybcxt.top/Article/details/gthgefxrpy.html

[R25] 去后缀 / 去前缀
来源：http://dali.jqgfzy.top/Article/details/gtfwfmnsye.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhongyouzk.top/Article/details/gtdhoxodiw.html

[R26] 命令替换
来源：http://dali.xziqi.cn/Article/details/gtjdrdiiyf.html

now=$(date +%F); echo "$now"
来源：http://dali.jianghu66.top/Article/details/gtsjoomimt.html

[R27] 算术展开
来源：http://dali.wangshuangyany.cn/Article/details/gthtkqdams.html

echo $((1 + 2 * 3))
来源：http://dali.iojbl.cn/Article/details/gttedzzpxr.html

[R28] 浮点运算
来源：http://dali.fengsongda.top/Article/details/gtvvhsqcrp.html

echo "scale=2; 10/3" | bc
来源：http://dali.ivvv.top/Article/details/gtfjslztuo.html

[R29] 定义函数
来源：http://dali.wangshuangyany.cn/Article/details/gtqcgzcmwh.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.ehwqpu.com/Article/details/gtfwgsqzdh.html

[R30] 函数返回状态码
来源：http://dali.ywan-chungtsiang.top/Article/details/gttozocnpc.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.aibaodan.cn/Article/details/gtegskccoc.html

[R31] 局部变量
来源：http://dali.daxiang520.top/Article/details/gtvyjbtmab.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gthnfozisl.html

[R32] 参数个数校验
来源：http://dali.xuetiantiany.cn/Article/details/gtjrqsmtka.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.jinqigfzy.top/Article/details/gtzsfpvpyp.html

[R33] 捕获错误并提示行号
来源：http://dali.gogol.net.cn/Article/details/gtzzrhchsn.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.pycfn.com/Article/details/gtnucdvwjd.html

[R34] 退出时清理
来源：http://dali.yuanzhike.top/Article/details/gtbcxduaek.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.fzhhl.top/Article/details/gtsghnuibi.html

[R35] 后台执行并等待
来源：http://dali.yj20258888.top/Article/details/gtpyazgqtm.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhengqikj.top/Article/details/gtbzqfgaok.html

[R36] 并发执行多个任务
来源：http://dali.yangfankeji.com/Article/details/gtblnohdlt.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.yanxiufei.cn/Article/details/gtpvyamndy.html

[R37] 把输出赋给变量
来源：http://dali.bjfxy.top/Article/details/gtginakagp.html

files=$(ls -1)
来源：http://dali.svipenyu.cn/Article/details/gtboqqdnuq.html

[R38] 管道串联
来源：http://dali.smart0.xyz/Article/details/gtrxlpyfin.html

cat a.txt | grep -i error | wc -l
来源：http://dali.hnqzz.top/Article/details/gtzhabybka.html

[R39] 重定向标准输出与错误
来源：http://dali.yongpay.top/Article/details/gtctuxguqi.html

cmd > out.log 2>&1
来源：http://dali.wangshuangyany.cn/Article/details/gtdfrywshf.html

[R40] 追加写日志
来源：http://dali.xziqi.cn/Article/details/gtgzkixyko.html

echo "log" >> out.log
来源：http://dali.hywenlv.cn/Article/details/gtsvogpvln.html

[R41] 丢弃输出
来源：http://dali.chenjidiqi.icu/Article/details/gtovnkyiem.html

cmd >/dev/null 2>&1
来源：http://dali.ybcxt.top/Article/details/gtlvrixmld.html

[R42] 输入重定向
来源：http://dali.tian-w.cn/Article/details/gtxbqzskpt.html

wc -l < a.txt
来源：http://dali.jinqigufen.top/Article/details/gturfsdvkz.html

[R43] 按名字查找文件
来源：http://dali.chenlongwang.top/Article/details/gtsvlkrpbp.html

find . -name "*.log" -type f
来源：http://dali.aibaodan.cn/Article/details/gtbraunxym.html

[R44] 按修改时间查找
来源：http://dali.birdmap.top/Article/details/gtaysmnxdw.html

find . -mtime -7 -type f
来源：http://dali.quarkkingdee.top/Article/details/gtsezziaqo.html

[R45] 批量删除
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyobknxqz.html

find . -name "*.tmp" -delete
来源：http://dali.chenjidiqi.icu/Article/details/gtywpzkqso.html

[R46] 递归替换文件内容
来源：http://dali.sxryk.cn/Article/details/gtlewhoyto.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.9152youxi.cn/Article/details/gtvxhtbxir.html

[R47] sed 单行替换
来源：http://dali.dashuyun.cn/Article/details/gtlkgxxkqp.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzzvqrddo.html

[R48] awk 取指定列
来源：http://dali.jlsjyb.cn/Article/details/gtriytxrgn.html

awk '{print $1, $3}' a.txt
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbhkuqkdh.html

[R49] awk 带条件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrjumctbs.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.jinghuilouyu.cn/Article/details/gtkwyinhcq.html

[R50] awk 求和
来源：http://dali.gogol.net.cn/Article/details/gtftmrhhtt.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.jlsjyb.cn/Article/details/gtzffiynaq.html

[R51] 排序去重取前几
来源：http://dali.yvedp.cn/Article/details/gtcirhlonn.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.haohaochexian.top/Article/details/gtvakkgykh.html

[R52] 统计行数
来源：http://dali.zhiwuduotai.top/Article/details/gtzhyugeza.html

wc -l a.txt
来源：http://dali.svipenyu.cn/Article/details/gtjinwahub.html

[R53] 查看文件头与实时尾
来源：http://dali.c1oappe.top/Article/details/gtvzadixla.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.cucudq.cn/Article/details/gtnhkoswcr.html

[R54] 比较两个文件
来源：http://dali.yj202588.top/Article/details/gtizrysknq.html

diff a.txt b.txt
来源：http://dali.zhiwuduotai.top/Article/details/gtdjaaiyjs.html

[R55] 压缩与解压
来源：http://dali.hongshengwenyu.top/Article/details/gtzickquyl.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhengqikj.top/Article/details/gtgyrjhnsa.html

[R56] 远程拷贝
来源：http://dali.jyoumei.cn/Article/details/gtwjfrmpsq.html

scp file user@host:/path/
来源：http://dali.cheryme.top/Article/details/gtefmlfwlr.html

[R57] 远程执行命令
来源：http://dali.shuidangran.top/Article/details/gtkdvttpge.html

ssh user@host 'uptime'
来源：http://dali.kuanghao11.cn/Article/details/gtlbuhmwqj.html

[R58] 下载文件
来源：http://dali.jqgufenzy.top/Article/details/gtersieujd.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.shuidangran.top/Article/details/gtydmakbnw.html

[R59] 发 POST JSON
来源：http://dali.cdnleiting.top/Article/details/gtzpxjappr.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.svipenyu.cn/Article/details/gtbeiwfiip.html

[R60] 只看 HTTP 状态码
来源：http://dali.c1oappe.top/Article/details/gtvdyxapep.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.cheryme.top/Article/details/gthylmucfa.html

[R61] 磁盘占用
来源：http://dali.hnqzz.top/Article/details/gtdsszrgag.html

df -h;  du -sh *
来源：http://dali.redwolf501.top/Article/details/gtalkvxuln.html

[R62] 找最占空间的文件
来源：http://dali.xuetiantiany.cn/Article/details/gttsxmufaz.html

du -ah . | sort -rh | head -10
来源：http://dali.0kj1m.cn/Article/details/gtfprqjrzk.html

[R63] 内存与进程
来源：http://dali.xuetiantiany.cn/Article/details/gtsptxdraa.html

free -h;  ps aux | grep nginx
来源：http://dali.hywenlv.cn/Article/details/gtdpknmgtt.html

[R64] 结束进程
来源：http://dali.zdqjudy.top/Article/details/gtveobkook.html

kill -9 $(pgrep -f app.py)
来源：http://dali.sufxvd.cn/Article/details/gtsdxapasu.html

[R65] 查看端口占用
来源：http://dali.zycfv.cn/Article/details/gtwvsbivjx.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.sysykeji.top/Article/details/gtbrbrutii.html

[R66] 定时任务
来源：http://dali.hammf.cn/Article/details/gtpxmegjmh.html

crontab -e;  crontab -l
来源：http://dali.yangfankeji.com/Article/details/gtcyuhvvlb.html

[R67] 生成随机十六进制串
来源：http://dali.guannengcc.top/Article/details/gtfayoxmlx.html

openssl rand -hex 16
来源：http://dali.hfpthk.cn/Article/details/gtdlxxzpbe.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gtnidoymvb.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.tanke756.top/Article/details/gtyrakwtay.html

[R69] 生成随机密码
来源：http://dali.hammf.cn/Article/details/gtnripimps.html

head -c 16 /dev/urandom | base64
来源：http://dali.bjfxy.top/Article/details/gtokalzwzt.html

[R70] 时间戳与互转
来源：http://dali.jyoumei.cn/Article/details/gtgvdnkonx.html

date +%s;  date -d @1700000000
来源：http://dali.316326.xyz/Article/details/gtzgfrpknm.html

[R71] 日期格式化
来源：http://dali.hnxiangtu.top/Article/details/gtbadyiwpu.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zycfv.cn/Article/details/gtzyqxdbqz.html

[R72] 等待端口就绪
来源：http://dali.pycfn.com/Article/details/gtmhxhjlqf.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.jqgfzy.top/Article/details/gtvkcoqybm.html

[R73] 分割大日志
来源：http://dali.xylfe.cn/Article/details/gtrjcoofpf.html

split -l 1000 big.log part_
来源：http://dali.sxryk.cn/Article/details/gtheiapkox.html

[R74] 批量重命名
来源：http://dali.vqdsnc.cn/Article/details/gtdlxhtsqn.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.yanxiufei.cn/Article/details/gtmhlaswco.html

[R75] 导出环境变量
来源：http://dali.fzhhl.top/Article/details/gtphgkywqh.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.hongshengwenyu.top/Article/details/gtjhhruyyo.html

[R76] 使用临时文件
来源：http://dali.jinqigufen.top/Article/details/gtijszdceh.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.cheryme.top/Article/details/gtrmqlimzv.html

[R77] 读取用户输入
来源：http://dali.birdmap.top/Article/details/gtmctpxqwt.html

read -rp "请输入: " ans
来源：http://dali.yanxiufei.cn/Article/details/gtsdihovsx.html

[R78] 交互式菜单
来源：http://dali.xziqi.cn/Article/details/gtwsoyrkhe.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.yueranfly.top/Article/details/gtictbrhek.html

[R79] 解析命令行选项
来源：http://dali.gogol.net.cn/Article/details/gthzbbdxwi.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.jiagoushi.top/Article/details/gtlzlcbrrf.html

[R80] 查看脚本执行耗时
来源：http://dali.cheryme.top/Article/details/gtdbgcwval.html

time ./run.sh
来源：http://dali.jinghuilouyu.cn/Article/details/gtltfsskil.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtizcivuws.html

S. C / C++ 专题
来源：http://dali.ppjwa.cn/Article/details/gtoeapodyq.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtjdmbvraa.html

[S01] C：Hello World
来源：http://dali.cheryme.top/Article/details/gtpqldyyjk.html

#include <stdio.h>
来源：http://dali.sxryk.cn/Article/details/gtmuebjelp.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.0kj1m.cn/Article/details/gtgezgslub.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gtojuyszeb.html

int a = 10; printf("%d\n", a);
来源：http://dali.ybcxt.top/Article/details/gtugdmsenm.html

[S03] C：读入整数
来源：http://dali.yangfankeji.com/Article/details/gtnpnxlbvs.html

int x; scanf("%d", &x);
来源：http://dali.kuanghao11.cn/Article/details/gtngntoxso.html

[S04] C：字符串复制
来源：http://dali.gaohongyu789.top/Article/details/gtlkntqlop.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.hnxiangtu.top/Article/details/gtchcygcel.html

[S05] C：字符串长度
来源：http://dali.havefunace.top/Article/details/gtbxkbukrx.html

strlen(s)
来源：http://dali.mhx1999.top/Article/details/gtdihkyxnl.html

[S06] C：字符串比较
来源：http://dali.jianghu66.top/Article/details/gtmvxvpifp.html

strcmp(a, b) == 0
来源：http://dali.vqdsnc.cn/Article/details/gtiwadhvem.html

[S07] C：数组遍历求和
来源：http://dali.andypj.xyz/Article/details/gtbfuhxwsn.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.jinqigufen.top/Article/details/gtypehrbxz.html

[S08] C：动态内存分配与释放
来源：http://dali.pengpengdd.cyou/Article/details/gtkmsyetcu.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.cdnleiting.top/Article/details/gtwvexcqnz.html

[S09] C：结构体定义与初始化
来源：http://dali.chenjidiqi.icu/Article/details/gthmlhrbgk.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.hywenlv.cn/Article/details/gtsnbbsyrr.html

[S10] C：指针与解引用
来源：http://dali.shuidangran.top/Article/details/gtqarxfkkz.html

int *p = &a;  *p = 5;
来源：http://dali.hnqzz.top/Article/details/gtvzktrcwn.html

[S11] C：逐行读文件
来源：http://dali.fzhhl.top/Article/details/gtphvdebnu.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.yanxiufei.cn/Article/details/gtmzgoqhfr.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.yonumen.top/Article/details/gtitcxgjxq.html

fclose(f);
来源：http://dali.nwbrower.top/Article/details/gtblxqkrox.html

[S12] C：写文件
来源：http://dali.nanxinkj.top/Article/details/gtcitstmoi.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.jiagoushi.top/Article/details/gtncfmnhrx.html

[S13] C：宏定义
来源：http://dali.jqgfzy.top/Article/details/gtqgoxsnpl.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhixingplan.top/Article/details/gtwonnenqb.html

[S14] C：枚举
来源：http://dali.fzhhl.top/Article/details/gtvkqidiho.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.gzhubu.top/Article/details/gtaohhnkiy.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gtkfpwgvhm.html

(double) a / b
来源：http://dali.cdnleiting.top/Article/details/gtemsqgyjr.html

[S16] C：位操作置位
来源：http://dali.nwbrower.top/Article/details/gtxvljgjsk.html

x |= (1 << 3);
来源：http://dali.jyoumei.cn/Article/details/gtavaigtgq.html

[S17] C：安全拼接字符串
来源：http://dali.jiagoushi.top/Article/details/gtwcltiicf.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhengqikj.top/Article/details/gtejuavdio.html

[S18] C：命令行参数
来源：http://dali.kuanghao11.cn/Article/details/gttgaxvuhf.html

int main(int argc, char **argv)
来源：http://dali.sweek.top/Article/details/gtopvzgcsk.html

[S19] C：快速排序
来源：http://dali.yj20258888.top/Article/details/gtujvlbmck.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.kuanghao11.cn/Article/details/gtxhqtpcyr.html

[S20] C：二分查找
来源：http://dali.jiagoushi.top/Article/details/gtabkjzwnk.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.xuetiantiany.cn/Article/details/gtnvjsgghc.html

[S21] C：字符类别判断
来源：http://dali.jinqigufen.top/Article/details/gtfvbhcykx.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.9152youxi.cn/Article/details/gtsuhtjarl.html

[S22] C：字符串转数字
来源：http://dali.daria6918.cn/Article/details/gttlpncamk.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.wangdashe.top/Article/details/gtpjgyzxvy.html

[S23] C：随机数
来源：http://dali.aizwys.cn/Article/details/gtwsqkgzsm.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.316326.xyz/Article/details/gtelgejmtu.html

[S24] C：获取本地时间
来源：http://dali.yongpay.top/Article/details/gthxcgwzug.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.tian-w.cn/Article/details/gtnbtruxxk.html

[S25] C：内存拷贝
来源：http://dali.gotoacloud.top/Article/details/gtskjxxgeb.html

memcpy(dst, src, n);
来源：http://dali.havefunace.top/Article/details/gtvvojkbve.html

[S26] C：内存清零
来源：http://dali.guowangkeji.top/Article/details/gtcmqqswgu.html

memset(a, 0, sizeof a);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwfpexryz.html

[S27] C：定义常量
来源：http://dali.quarkkingdee.top/Article/details/gtqamxmbhn.html

const double PI = 3.14159;
来源：http://dali.jyoumei.cn/Article/details/gtsarcbnqw.html

[S28] C：静态变量
来源：http://dali.gzhubu.top/Article/details/gtniwqsdzj.html

static int counter = 0;
来源：http://dali.hongshengwenyu.top/Article/details/gthpomtqwd.html

[S29] C：变参函数
来源：http://dali.fengsongda.top/Article/details/gtlowxmhrq.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.ybcxt.top/Article/details/gtrklvemet.html

[S30] C：头文件保护
来源：http://dali.zhoulong.xyz/Article/details/gtlmqdkeon.html

#ifndef X_H
来源：http://dali.hongshengwenyu.top/Article/details/gtduaglila.html

#define X_H
来源：http://dali.sufxvd.cn/Article/details/gtirobhchk.html

#endif
来源：http://dali.hysaishi.cn/Article/details/gtjjuzyfxm.html

[S31] C++：Hello World
来源：http://dali.chenzaomai.com/Article/details/gtsrxyttrn.html

#include <iostream>
来源：http://dali.shanyushiyangtech.top/Article/details/gtbdybmlnw.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.sufxvd.cn/Article/details/gtomzwjmwh.html

[S32] C++：字符串
来源：http://dali.jqgufenzy.top/Article/details/gtgoofsgts.html

std::string s = "hi";  s += "!";
来源：http://dali.ehwqpu.com/Article/details/gtpvfnnkei.html

[S33] C++：vector 增删
来源：http://dali.wangshuangyany.cn/Article/details/gtznlkgycz.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.jqgfzy.top/Article/details/gtkkogwqml.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gtqfucgdhk.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.cqqwz.cn/Article/details/gtzgtkmfmi.html

[S35] C++：map
来源：http://dali.wangdashe.top/Article/details/gtwlgprbgz.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.9152youxi.cn/Article/details/gtbdumbolv.html

[S36] C++：unordered_map
来源：http://dali.wangdashe.top/Article/details/gtmovytdjz.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.vqdsnc.cn/Article/details/gtcximmneb.html

[S37] C++：set
来源：http://dali.tanke756.top/Article/details/gtdrmdtele.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.nanxuanxn.top/Article/details/gtwteodwac.html

[S38] C++：排序
来源：http://dali.gotoacloud.top/Article/details/gtecowukyv.html

std::sort(v.begin(), v.end());
来源：http://dali.gogol.net.cn/Article/details/gtcarjcywc.html

[S39] C++：自定义比较器排序
来源：http://dali.yj202588.top/Article/details/gtmcdnrzdr.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.jqgufenzy.top/Article/details/gtmpvdwmgq.html

[S40] C++：查找元素
来源：http://dali.xylfe.cn/Article/details/gttdjqybew.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhongyouzk.top/Article/details/gteayifspp.html

[S41] C++：类与构造函数
来源：http://dali.iojbl.cn/Article/details/gtffnmkmov.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.gogol.net.cn/Article/details/gtcjegzimt.html

[S42] C++：继承与虚函数
来源：http://dali.jqgufenzy.top/Article/details/gtqecyvlgl.html

class B : public Base { public: void f() override {} };
来源：http://dali.wangshuangyany.cn/Article/details/gtogflpgsj.html

[S43] C++：智能指针
来源：http://dali.feifeiyinyue.top/Article/details/gtdaaujyrc.html

auto p = std::make_unique<int>(5);
来源：http://dali.feifeiyinyue.top/Article/details/gtujjpaalp.html

[S44] C++：引用传参
来源：http://dali.iojbl.cn/Article/details/gtxbpsfhwo.html

void inc(int &x) { ++x; }
来源：http://dali.cucudq.cn/Article/details/gtjfkzqvwg.html

[S45] C++：lambda
来源：http://dali.ivvv.top/Article/details/gtbwlqepgg.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.yonumen.top/Article/details/gtgovxxpox.html

[S46] C++：函数模板
来源：http://dali.hfpthk.cn/Article/details/gtgzpmdekt.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.yangfankeji.com/Article/details/gtiylmtwyu.html

[S47] C++：结构化绑定遍历
来源：http://dali.redwolf501.top/Article/details/gtpsxzuzsm.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpldrrkvx.html

[S48] C++：逐行读文件
来源：http://dali.wangdashe.top/Article/details/gtgxsupamk.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.tanke756.top/Article/details/gtaxjfqoqe.html

while (std::getline(in, line)) { }
来源：http://dali.andypj.xyz/Article/details/gtyiypzfxt.html

[S49] C++：写文件
来源：http://dali.gzhubu.top/Article/details/gtobqruccj.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.yanxiufei.cn/Article/details/gtqyjayeko.html

[S50] C++：格式化数字
来源：http://dali.yuanzhike.top/Article/details/gtrboxqmbm.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.xuetiantiany.cn/Article/details/gtdwwesygl.html

[S51] C++：显式类型转换
来源：http://dali.yj20258.top/Article/details/gtyoxisasw.html

static_cast<double>(a) / b
来源：http://dali.hongshengwenyu.top/Article/details/gtvstjbzbj.html

[S52] C++：const 与 noexcept
来源：http://dali.xziqi.cn/Article/details/gtcoacezpb.html


<!-- 参考信息 -->