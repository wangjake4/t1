代发 wailian999

[Q80] 字符串截取
来源：http://dali.pycfn.com/Article/details/gtatliswfn.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.birdmap.top/Article/details/gthlneozsp.html

[Q81] 字符串替换
来源：http://dali.pengpengdd.cyou/Article/details/gtuhzrikvh.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.hysaishi.cn/Article/details/gtnmqshqke.html

[Q82] 字符长度与字节长度
来源：http://dali.wangshuangyany.cn/Article/details/gteohyhmys.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.quarkkingdee.top/Article/details/gtfdpruvib.html

[Q83] 大小写转换
来源：http://dali.shangyingyoupin.top/Article/details/gtmbaqkuny.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gtkwxuvuyw.html

[Q84] 去除首尾空格
来源：http://dali.zhiwuduotai.top/Article/details/gtwtvnzldf.html

SELECT TRIM(name) FROM users;
来源：http://dali.nanxuanxn.top/Article/details/gtkfqwgkiq.html

[Q85] 数值取整
来源：http://dali.wangshuangyany.cn/Article/details/gtynlvhuvn.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.pengpengdd.cyou/Article/details/gtggtifbhz.html

[Q86] 读取 JSON 字段
来源：http://dali.ppjwa.cn/Article/details/gtgbxazuqn.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.mhx1999.top/Article/details/gtpvlucnud.html

[Q87] JSON 字段做条件
来源：http://dali.jlsjyb.cn/Article/details/gtyyrjfsbo.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.ybcxt.top/Article/details/gtnqwushpb.html

[Q88] 行转列（条件聚合）
来源：http://dali.yuanzhike.top/Article/details/gtwygubgta.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.chenzaomai.com/Article/details/gtwtmhgspa.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.yongpay.top/Article/details/gtjjqdlgjt.html

[Q89] 判断表是否存在
来源：http://dali.hnxiangtu.top/Article/details/gtybrxzqip.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.jyoumei.cn/Article/details/gthrocrztl.html

[Q90] 生成序号列
来源：http://dali.zhongyouzk.top/Article/details/gtafftvoby.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjtohwxlf.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtknhgcpuu.html

R. Bash 专题
来源：http://dali.316326.xyz/Article/details/gtmqlyenkz.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfwegqvid.html

[R01] shebang 与严格模式
来源：http://dali.yj20258888.top/Article/details/gtaksmnmnm.html

#!/usr/bin/env bash
来源：http://dali.ivvv.top/Article/details/gtvpqmcikn.html

set -euo pipefail
来源：http://dali.hywenlv.cn/Article/details/gtrwfyxhmj.html

[R02] 变量赋值与使用
来源：http://dali.ppjwa.cn/Article/details/gtzwjxmqfa.html

name="Tom"; echo "$name"
来源：http://dali.nanxinkj.top/Article/details/gtvefkejnk.html

[R03] 只读变量
来源：http://dali.chenzaomai.com/Article/details/gtjuhvipmc.html

readonly PI=3.14
来源：http://dali.gzhubu.top/Article/details/gtxjsbmwnl.html

[R04] 位置参数
来源：http://dali.ehwqpu.com/Article/details/gtqtxrayfe.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zycfv.cn/Article/details/gthjkcxmiz.html

[R05] 参数默认值
来源：http://dali.tianlin.xyz/Article/details/gtpbmgaejr.html

name="${1:-default}"
来源：http://dali.cheryme.top/Article/details/gtauegocvu.html

[R06] 判断命令是否存在
来源：http://dali.guowangkeji.top/Article/details/gtbzsuetro.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhongyouzk.top/Article/details/gtojorfpne.html

[R07] if 判断文件
来源：http://dali.ydzc1.top/Article/details/gtugczzbvi.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.redwolf501.top/Article/details/gtdgggszbw.html

[R08] 数值比较
来源：http://dali.yvedp.cn/Article/details/gtkwkgdtqz.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.jianghu66.top/Article/details/gtpaaahsus.html

[R09] 字符串比较
来源：http://dali.xziqi.cn/Article/details/gtvvwuhilb.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.cashguo.top/Article/details/gtxggitrex.html

[R10] 正则匹配
来源：http://dali.jinghuilouyu.cn/Article/details/gtzkxmroby.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.sufxvd.cn/Article/details/gtaacvqauc.html

[R11] case 多分支
来源：http://dali.gogol.net.cn/Article/details/gtgfzgqpgv.html

case "$1" in
来源：http://dali.havefunace.top/Article/details/gtokpcsgya.html

start) echo "启动" ;;
来源：http://dali.yj20258888.top/Article/details/gtvkkrdwde.html

stop)  echo "停止" ;;
来源：http://dali.hammf.cn/Article/details/gttqdsntqv.html

*)     echo "未知命令" ;;
来源：http://dali.tanke756.top/Article/details/gtppysdloq.html

esac
来源：http://dali.shzxlz.cn/Article/details/gtkavmskjd.html

[R12] for 遍历文件
来源：http://dali.chenlongwang.top/Article/details/gtiexicxhj.html

for f in *.txt; do echo "$f"; done
来源：http://dali.wangshuangyany.cn/Article/details/gtxosozofh.html

[R13] for 计数循环
来源：http://dali.shzxlz.cn/Article/details/gtcyhnyuyq.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.iojbl.cn/Article/details/gtzdutqgef.html

[R14] C 风格 for
来源：http://dali.tian-w.cn/Article/details/gtqwxelzfq.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwunxtlux.html

[R15] while 逐行读文件
来源：http://dali.9152youxi.cn/Article/details/gtyyswhase.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.wangshuangyany.cn/Article/details/gttgozbyik.html

[R16] until 等待条件
来源：http://dali.vqdsnc.cn/Article/details/gtkvmyeryr.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.ybcxt.top/Article/details/gtmhsmujcs.html

[R17] 数组定义与取值
来源：http://dali.hfpthk.cn/Article/details/gtoafuwldd.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.tianlin.xyz/Article/details/gtcqstnbvh.html

[R18] 遍历数组
来源：http://dali.shanyushiyangtech.top/Article/details/gtomxbsscl.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.hnqzz.top/Article/details/gtjteodogs.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gtfsdzfkns.html

echo "${#arr[@]}"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzkquaqqk.html

[R20] 关联数组（字典）
来源：http://dali.dianchejie.cn/Article/details/gtpmphsfmg.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.hnqzz.top/Article/details/gtexikqfky.html

[R21] 字符串长度
来源：http://dali.zycfv.cn/Article/details/gtnqmclvne.html

echo "${#s}"
来源：http://dali.yongpay.top/Article/details/gtiegbqtax.html

[R22] 截取子串
来源：http://dali.ydzc1.top/Article/details/gtylygighf.html

echo "${s:0:5}"
来源：http://dali.chenjidiqi.icu/Article/details/gtojvnxbcg.html

[R23] 字符串替换
来源：http://dali.pycfn.com/Article/details/gtobrjzxby.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.feifeiyinyue.top/Article/details/gtzeyopvaj.html

[R24] 大小写转换
来源：http://dali.feifeiyinyue.top/Article/details/gtomsezejv.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtewqctvxh.html

[R25] 去后缀 / 去前缀
来源：http://dali.sufxvd.cn/Article/details/gtqyhpnmcj.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjvkjcrwj.html

[R26] 命令替换
来源：http://dali.zhiwuduotai.top/Article/details/gtbfrnuymb.html

now=$(date +%F); echo "$now"
来源：http://dali.ivvv.top/Article/details/gtbptejpig.html

[R27] 算术展开
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttjqkjraj.html

echo $((1 + 2 * 3))
来源：http://dali.xylfe.cn/Article/details/gtsqznrocv.html

[R28] 浮点运算
来源：http://dali.cucudq.cn/Article/details/gtfxbineww.html

echo "scale=2; 10/3" | bc
来源：http://dali.yj20258.top/Article/details/gtccsppiws.html

[R29] 定义函数
来源：http://dali.cdnleiting.top/Article/details/gtnvfkqlrm.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.jinqigfzy.top/Article/details/gtoggzduvk.html

[R30] 函数返回状态码
来源：http://dali.shanyushiyangtech.top/Article/details/gtrvxxrxms.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.jinqigfzy.top/Article/details/gtnetmefck.html

[R31] 局部变量
来源：http://dali.9152youxi.cn/Article/details/gtgziwvmiu.html

f() { local x=1; echo "$x"; }
来源：http://dali.aibaodan.cn/Article/details/gtisqikcad.html

[R32] 参数个数校验
来源：http://dali.xinyue.icu/Article/details/gtertgphye.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.xuetiantiany.cn/Article/details/gthnkwjpev.html

[R33] 捕获错误并提示行号
来源：http://dali.smart0.xyz/Article/details/gtgxsdcxuc.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.9152youxi.cn/Article/details/gtqjdswhaj.html

[R34] 退出时清理
来源：http://dali.jinqigufen.top/Article/details/gtzljtxuay.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.9152youxi.cn/Article/details/gtraptpydd.html

[R35] 后台执行并等待
来源：http://dali.jqgufenzy.top/Article/details/gtfsazrfwv.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.xinyue.icu/Article/details/gtfdiclfrw.html

[R36] 并发执行多个任务
来源：http://dali.zhixingplan.top/Article/details/gtrkrvwoec.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.jinyuanbaomall.cn/Article/details/gtebbthgie.html

[R37] 把输出赋给变量
来源：http://dali.xylfe.cn/Article/details/gthnbvpyfc.html

files=$(ls -1)
来源：http://dali.yvedp.cn/Article/details/gtaaqkatwh.html

[R38] 管道串联
来源：http://dali.aizwys.cn/Article/details/gtewohudew.html

cat a.txt | grep -i error | wc -l
来源：http://dali.yvedp.cn/Article/details/gtqdmqicth.html

[R39] 重定向标准输出与错误
来源：http://dali.yj20258888.top/Article/details/gtuhvfhvjz.html

cmd > out.log 2>&1
来源：http://dali.jyoumei.cn/Article/details/gtpwurmgge.html

[R40] 追加写日志
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjrtdxabd.html

echo "log" >> out.log
来源：http://dali.fengsongda.top/Article/details/gtalthznya.html

[R41] 丢弃输出
来源：http://dali.jinqigufen.top/Article/details/gtenxfnmor.html

cmd >/dev/null 2>&1
来源：http://dali.316326.xyz/Article/details/gtnxbbdjcj.html

[R42] 输入重定向
来源：http://dali.tanke756.top/Article/details/gtlajokfrm.html

wc -l < a.txt
来源：http://dali.ehwqpu.com/Article/details/gtmxzhbepf.html

[R43] 按名字查找文件
来源：http://dali.nwbrower.top/Article/details/gtcdqsnhgk.html

find . -name "*.log" -type f
来源：http://dali.shangyingyoupin.top/Article/details/gtnffdljpa.html

[R44] 按修改时间查找
来源：http://dali.zycfv.cn/Article/details/gtrsacubre.html

find . -mtime -7 -type f
来源：http://dali.quarkkingdee.top/Article/details/gtnqltqnyz.html

[R45] 批量删除
来源：http://dali.feifeiyinyue.top/Article/details/gtdupwnawi.html

find . -name "*.tmp" -delete
来源：http://dali.mhx1999.top/Article/details/gtrhoaievx.html

[R46] 递归替换文件内容
来源：http://dali.hongshengwenyu.top/Article/details/gtgwgawyfq.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.jlsjyb.cn/Article/details/gttdfcyqgu.html

[R47] sed 单行替换
来源：http://dali.gogol.net.cn/Article/details/gtaghuphma.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.quarkkingdee.top/Article/details/gtftbxawhv.html

[R48] awk 取指定列
来源：http://dali.jqgufenzy.top/Article/details/gtgjxdaghm.html

awk '{print $1, $3}' a.txt
来源：http://dali.daxiang520.top/Article/details/gtllpgasko.html

[R49] awk 带条件
来源：http://dali.jianghu66.top/Article/details/gtecyrxfka.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.316326.xyz/Article/details/gtupmrzezl.html

[R50] awk 求和
来源：http://dali.feifeiyinyue.top/Article/details/gtfqwgtkim.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.shuidangran.top/Article/details/gtokgwhpiz.html

[R51] 排序去重取前几
来源：http://dali.nanxinkj.top/Article/details/gtbltaajmh.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.fengsongda.top/Article/details/gtsjdolwiz.html

[R52] 统计行数
来源：http://dali.zdqjudy.top/Article/details/gtrfqabszw.html

wc -l a.txt
来源：http://dali.wangdashe.top/Article/details/gtbtcbnvqt.html

[R53] 查看文件头与实时尾
来源：http://dali.shanyushiyangkeji.top/Article/details/gtypnjavds.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.cucudq.cn/Article/details/gtrsfyjqtc.html

[R54] 比较两个文件
来源：http://dali.chenjidiqi.icu/Article/details/gtlwowkepf.html

diff a.txt b.txt
来源：http://dali.zhaomingkeji.xyz/Article/details/gthjbrhnkd.html

[R55] 压缩与解压
来源：http://dali.jqgfzy.top/Article/details/gtmbghvtrc.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.ydzc1.top/Article/details/gtziwdglys.html

[R56] 远程拷贝
来源：http://dali.jinghuilouyu.cn/Article/details/gtmxuzmzyt.html

scp file user@host:/path/
来源：http://dali.cucudq.cn/Article/details/gtzprwzlxm.html

[R57] 远程执行命令
来源：http://dali.hywenlv.cn/Article/details/gtkobfzeuq.html

ssh user@host 'uptime'
来源：http://dali.snrcjt.cn/Article/details/gtijdsjjrn.html

[R58] 下载文件
来源：http://dali.nwbrower.top/Article/details/gtfbirtzmx.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.dianchejie.cn/Article/details/gtrvyhltvd.html

[R59] 发 POST JSON
来源：http://dali.jinghuilouyu.cn/Article/details/gtjxuhapvp.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.gotoacloud.top/Article/details/gtxlzlipal.html

[R60] 只看 HTTP 状态码
来源：http://dali.havefunace.top/Article/details/gtppngdnlm.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.ybcxt.top/Article/details/gtsuiwisex.html

[R61] 磁盘占用
来源：http://dali.zhixingplan.top/Article/details/gtdgovapdr.html

df -h;  du -sh *
来源：http://dali.gaohongyu789.top/Article/details/gtcdbndfzm.html

[R62] 找最占空间的文件
来源：http://dali.guowangkeji.top/Article/details/gtvdwdkqsp.html

du -ah . | sort -rh | head -10
来源：http://dali.cucudq.cn/Article/details/gtgzkekocl.html

[R63] 内存与进程
来源：http://dali.xuetiantiany.cn/Article/details/gteoiyiqag.html

free -h;  ps aux | grep nginx
来源：http://dali.shangyingyoupin.top/Article/details/gtbsapqxnd.html

[R64] 结束进程
来源：http://dali.snrcjt.cn/Article/details/gtqfdqdcuf.html

kill -9 $(pgrep -f app.py)
来源：http://dali.hfpthk.cn/Article/details/gtszrhztgx.html

[R65] 查看端口占用
来源：http://dali.ppjwa.cn/Article/details/gtuzqqsmmh.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.yj20258888.top/Article/details/gtwaxmbong.html

[R66] 定时任务
来源：http://dali.kuanghao11.cn/Article/details/gtuyqmprlc.html

crontab -e;  crontab -l
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnqmbfqrs.html

[R67] 生成随机十六进制串
来源：http://dali.fzhhl.top/Article/details/gtjrfuzauj.html

openssl rand -hex 16
来源：http://dali.gogol.net.cn/Article/details/gtjoplwzcg.html

[R68] 计算文件校验值
来源：http://dali.daxiang520.top/Article/details/gtfrtvkbiz.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.jinqigfzy.top/Article/details/gtpbgeplvp.html

[R69] 生成随机密码
来源：http://dali.zhiwuduotai.top/Article/details/gtrnyfhxyx.html

head -c 16 /dev/urandom | base64
来源：http://dali.jianghu66.top/Article/details/gtoqullrvf.html

[R70] 时间戳与互转
来源：http://dali.jinqigufen.top/Article/details/gtntizahsk.html

date +%s;  date -d @1700000000
来源：http://dali.ehwqpu.com/Article/details/gtrulxlogh.html

[R71] 日期格式化
来源：http://dali.yueranfly.top/Article/details/gtxjesfbzf.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.daria6918.cn/Article/details/gtskgbfkcv.html

[R72] 等待端口就绪
来源：http://dali.pycfn.com/Article/details/gtomsvsfna.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.yj20258888.top/Article/details/gtdlvgkyqp.html

[R73] 分割大日志
来源：http://dali.yj20258888.top/Article/details/gteaudaeuc.html

split -l 1000 big.log part_
来源：http://dali.316326.xyz/Article/details/gtpfbpcojy.html

[R74] 批量重命名
来源：http://dali.chenlongwang.top/Article/details/gtgtqgxngy.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.pycfn.com/Article/details/gtxoqlyjzq.html

[R75] 导出环境变量
来源：http://dali.tanke756.top/Article/details/gturlzjnpa.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.shangyingyoupin.top/Article/details/gttbsfworn.html

[R76] 使用临时文件
来源：http://dali.hammf.cn/Article/details/gtzwnntutl.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.xuetiantiany.cn/Article/details/gtsoedkivm.html

[R77] 读取用户输入
来源：http://dali.jqgufenzy.top/Article/details/gtbhkionsx.html

read -rp "请输入: " ans
来源：http://dali.hywenlv.cn/Article/details/gtsjkbshne.html

[R78] 交互式菜单
来源：http://dali.haohaochexian.top/Article/details/gthmfcrxuc.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.jlsjyb.cn/Article/details/gtkasbviik.html

[R79] 解析命令行选项
来源：http://dali.hnqzz.top/Article/details/gtsxpyxdzw.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.yanxiufei.cn/Article/details/gtkvqmqsxk.html

[R80] 查看脚本执行耗时
来源：http://dali.sxryk.cn/Article/details/gtttnrzjeo.html

time ./run.sh
来源：http://dali.chenzaomai.com/Article/details/gttsnrkyyk.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtueyeguqk.html

S. C / C++ 专题
来源：http://dali.yuanzhike.top/Article/details/gtgplrocyy.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtsmkcodmw.html

[S01] C：Hello World
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpxtjokpw.html

#include <stdio.h>
来源：http://dali.jinghuilouyu.cn/Article/details/gtkelhutpt.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.bjfxy.top/Article/details/gtckcjmito.html

[S02] C：变量与格式化输出
来源：http://dali.sxryk.cn/Article/details/gtxfjgijii.html

int a = 10; printf("%d\n", a);
来源：http://dali.wangdashe.top/Article/details/gtrhluvitu.html

[S03] C：读入整数
来源：http://dali.0kj1m.cn/Article/details/gtspobltxq.html

int x; scanf("%d", &x);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbcojkvet.html

[S04] C：字符串复制
来源：http://dali.yonumen.top/Article/details/gtruesvbwj.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.ehwqpu.com/Article/details/gtavzwtbgy.html

[S05] C：字符串长度
来源：http://dali.hongshengwenyu.top/Article/details/gtlngtmazo.html

strlen(s)
来源：http://dali.0kj1m.cn/Article/details/gtoupaojft.html

[S06] C：字符串比较
来源：http://dali.yj20258888.top/Article/details/gtymczrkgd.html

strcmp(a, b) == 0
来源：http://dali.hnxiangtu.top/Article/details/gtsxcfnrre.html

[S07] C：数组遍历求和
来源：http://dali.svipenyu.cn/Article/details/gtgwkshvua.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.chenzaomai.com/Article/details/gtbkqusqjs.html

[S08] C：动态内存分配与释放
来源：http://dali.shanyushiyangkeji.top/Article/details/gtliikmcbv.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.yanxiufei.cn/Article/details/gtrtvvvdhr.html

[S09] C：结构体定义与初始化
来源：http://dali.9152youxi.cn/Article/details/gtixkvaksw.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.yj202588.top/Article/details/gtyqffdsiy.html

[S10] C：指针与解引用
来源：http://dali.yuanzhike.top/Article/details/gtidnxdukv.html

int *p = &a;  *p = 5;
来源：http://dali.bjfxy.top/Article/details/gtlpfoshgy.html

[S11] C：逐行读文件
来源：http://dali.jiagoushi.top/Article/details/gtudqkpnlu.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zdqjudy.top/Article/details/gtfxqscdos.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtexejedyh.html

fclose(f);
来源：http://dali.jyoumei.cn/Article/details/gtqvsnbdor.html

[S12] C：写文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbykfblya.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhoulong.xyz/Article/details/gtrspgzzlq.html

[S13] C：宏定义
来源：http://dali.jqgfzy.top/Article/details/gtcuqkruux.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.wangshuangyany.cn/Article/details/gtqvfalpkm.html

[S14] C：枚举
来源：http://dali.haohaochexian.top/Article/details/gtenuartjh.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.hammf.cn/Article/details/gtaavqpzdg.html

[S15] C：类型转换
来源：http://dali.mhx1999.top/Article/details/gtlzooioyr.html

(double) a / b
来源：http://dali.fzhhl.top/Article/details/gtolxzmiws.html

[S16] C：位操作置位
来源：http://dali.xziqi.cn/Article/details/gtqwzwabat.html

x |= (1 << 3);
来源：http://dali.yangfankeji.com/Article/details/gtpgetffgi.html

[S17] C：安全拼接字符串
来源：http://dali.cucudq.cn/Article/details/gtksyuxcwb.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.hywenlv.cn/Article/details/gtyfdqhvdt.html

[S18] C：命令行参数
来源：http://dali.fengsongda.top/Article/details/gttocvxolf.html

int main(int argc, char **argv)
来源：http://dali.bjfxy.top/Article/details/gtrfdlpqrz.html

[S19] C：快速排序
来源：http://dali.jianghu66.top/Article/details/gtyfsrqmup.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtomqcmkbr.html

[S20] C：二分查找
来源：http://dali.svipenyu.cn/Article/details/gtiwgwovpd.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.wangdashe.top/Article/details/gtwqehgjxn.html

[S21] C：字符类别判断
来源：http://dali.tanke756.top/Article/details/gtqdxhssne.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.xziqi.cn/Article/details/gteiifbnpm.html

[S22] C：字符串转数字
来源：http://dali.kuanghao11.cn/Article/details/gtgyjyfkhp.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zdqjudy.top/Article/details/gtdwjygnrr.html

[S23] C：随机数
来源：http://dali.jiagoushi.top/Article/details/gtxapqsbhg.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.316326.xyz/Article/details/gtfnpfzsks.html

[S24] C：获取本地时间
来源：http://dali.aibaodan.cn/Article/details/gtstgjbelv.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.haohaochexian.top/Article/details/gtvdckygxj.html

[S25] C：内存拷贝
来源：http://dali.cashguo.top/Article/details/gtwschcbko.html

memcpy(dst, src, n);
来源：http://dali.jinqigfzy.top/Article/details/gtmxwnvsmg.html

[S26] C：内存清零
来源：http://dali.jinqigufen.top/Article/details/gtiqjvkefk.html

memset(a, 0, sizeof a);
来源：http://dali.sysykeji.top/Article/details/gtbuyxdwmo.html

[S27] C：定义常量
来源：http://dali.cucudq.cn/Article/details/gtcqfsdjma.html

const double PI = 3.14159;
来源：http://dali.tanke756.top/Article/details/gteycjtzvv.html

[S28] C：静态变量
来源：http://dali.9152youxi.cn/Article/details/gtudmnzouh.html

static int counter = 0;
来源：http://dali.ybcxt.top/Article/details/gtthrlavqi.html

[S29] C：变参函数
来源：http://dali.gaohongyu789.top/Article/details/gtojlgzppm.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.guowangkeji.top/Article/details/gtkfcbuywu.html

[S30] C：头文件保护
来源：http://dali.hongshengwenyu.top/Article/details/gtnaeillvq.html

#ifndef X_H
来源：http://dali.shanyushiyangkeji.top/Article/details/gtegruqoka.html

#define X_H
来源：http://dali.zhengqikj.top/Article/details/gtyqhuttnc.html

#endif
来源：http://dali.cheryme.top/Article/details/gtlpoqofer.html

[S31] C++：Hello World
来源：http://dali.tianlin.xyz/Article/details/gtbdchboxc.html

#include <iostream>
来源：http://dali.jqgfzy.top/Article/details/gtaduxshev.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.sufxvd.cn/Article/details/gtlydopcgi.html

[S32] C++：字符串
来源：http://dali.ybcxt.top/Article/details/gtzefzlruk.html

std::string s = "hi";  s += "!";
来源：http://dali.dianchejie.cn/Article/details/gtjtocwxqu.html

[S33] C++：vector 增删
来源：http://dali.havefunace.top/Article/details/gtozjifykk.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.aibaodan.cn/Article/details/gtrjlizcbo.html

[S34] C++：遍历 vector
来源：http://dali.aibaodan.cn/Article/details/gtkcqtrqhb.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.316326.xyz/Article/details/gthvjvamhv.html

[S35] C++：map
来源：http://dali.jianghu66.top/Article/details/gtxuopvgen.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hnxiangtu.top/Article/details/gtbqcqzvjm.html

[S36] C++：unordered_map
来源：http://dali.havefunace.top/Article/details/gtxvowhbby.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhixingplan.top/Article/details/gtmxmomeke.html

[S37] C++：set
来源：http://dali.pycfn.com/Article/details/gtguvyhcga.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.jiagoushi.top/Article/details/gtsxwhpkmz.html

[S38] C++：排序
来源：http://dali.yanxiufei.cn/Article/details/gthlvtpwko.html

std::sort(v.begin(), v.end());
来源：http://dali.cheryme.top/Article/details/gtvzytdnuc.html

[S39] C++：自定义比较器排序
来源：http://dali.jiagoushi.top/Article/details/gtxmvqccsw.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.shzxlz.cn/Article/details/gtgmyqmgsu.html

[S40] C++：查找元素
来源：http://dali.pengpengdd.cyou/Article/details/gtvuzeucnz.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.jinqigfzy.top/Article/details/gteprlxtnh.html

[S41] C++：类与构造函数
来源：http://dali.quarkkingdee.top/Article/details/gtmzjsjpus.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttxutlhqg.html

[S42] C++：继承与虚函数
来源：http://dali.cashguo.top/Article/details/gttvcpwipb.html

class B : public Base { public: void f() override {} };
来源：http://dali.wangdashe.top/Article/details/gtnclcdvwh.html

[S43] C++：智能指针
来源：http://dali.hywenlv.cn/Article/details/gtzrbnhwwk.html

auto p = std::make_unique<int>(5);
来源：http://dali.yvedp.cn/Article/details/gtxgxudtex.html

[S44] C++：引用传参
来源：http://dali.xuanzx.com/Article/details/gtfxxzihci.html

void inc(int &x) { ++x; }
来源：http://dali.smart0.xyz/Article/details/gtrbvuzaxf.html

[S45] C++：lambda
来源：http://dali.gzhubu.top/Article/details/gtntexcqqu.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.ivvv.top/Article/details/gtoognqdli.html

[S46] C++：函数模板
来源：http://dali.tianlin.xyz/Article/details/gtjppgmygn.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.cheryme.top/Article/details/gtpoatlwza.html

[S47] C++：结构化绑定遍历
来源：http://dali.nanxinkj.top/Article/details/gtcgjsppjh.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.yvedp.cn/Article/details/gtnvrlfcjm.html

[S48] C++：逐行读文件
来源：http://dali.xinyue.icu/Article/details/gtokcxdugi.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.316326.xyz/Article/details/gthelfozfj.html

while (std::getline(in, line)) { }
来源：http://dali.nanxuanxn.top/Article/details/gtwyifcvqh.html

[S49] C++：写文件
来源：http://dali.smart0.xyz/Article/details/gtezeynfja.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.shangyingyoupin.top/Article/details/gtyzidxksj.html

[S50] C++：格式化数字
来源：http://dali.yanxiufei.cn/Article/details/gtjtqztvut.html


<!-- 参考信息 -->