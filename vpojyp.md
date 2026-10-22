代发 wailian999

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2mvvruiyt.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nwocicsh.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2mfyreila.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2uevbkrtk.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ydhetnbz.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dejwsuok.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2zqtgpgpw.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kuzjtbwy.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2harfpjtz.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jpaugric.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2kzrbsfjt.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2afcaaawf.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2mtacadsf.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2lkxmiljx.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ibdulkta.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2siyvajmv.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2gnxvdnyb.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2ojusiurn.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nsxhnbvu.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2owdshrtf.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2vqxnvxcg.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2ulbuqsgb.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2fapehwfi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xbhumuzo.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2otcnfjpa.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nfcfgabj.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2nydjlely.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2gmzlnlmb.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2fmgbbynz.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2pmrvokkt.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2ozmjngvj.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qxbugnex.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2cdcbzkjs.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2qzlzuoij.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2hopssude.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2mumrgrpm.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wyqfniea.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2tethlyck.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2arsfyahu.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2puglaezl.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2vkicnwii.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ujnsvdrt.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2jjaqvubp.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2pupvifrn.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2wilmxskl.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2fzhhmzog.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2aosilgol.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2qfofzuaq.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2nfxtalxk.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2mdprherq.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2cykhmhan.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2cqdzruve.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2kwijisvg.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qagpllwd.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2rsdgswfc.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2etijytnx.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2rksyggcx.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2ypxkwbtv.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xggdoaei.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ghhkzdvd.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2srqlbiiq.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2hjcvdyhs.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2iixjztfx.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2phvwdzgv.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ykfunald.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2zjtftrvg.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2owvekmaf.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2aubtgmgr.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2cthczarz.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2ayyqlchg.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rgvvqqsu.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2mmyslkpy.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2gqhusodl.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2qdnjdkuv.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2fjvtmwno.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2cevzpxir.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2cficfhjm.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2oubwrlnl.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qiainadx.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2cmvnwaeo.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2pwjsrtsn.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2tpjlagum.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2ojbzbmjr.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2wxsydrgd.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2ljtfnijf.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2xrzcidud.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2diindrmf.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2oigxjtyv.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2kzorlapd.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2wyjwsjli.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2yiowyhme.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zknljcwa.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2glxvpyaz.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2tlngrquo.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gdgyznsp.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2qczfsltc.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2dyfeqjbz.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2nghsvfhj.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2cnpdzsup.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2xemyvuto.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2waobdwkb.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2zzgoeame.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2ksoplvrw.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2gwfesvku.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2kbrlnewv.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2vmhhyiht.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2yyfmvlyq.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2rcqjqqwr.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2wgzppczi.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2wyzxeygb.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2arotvsrp.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2cojbuxwn.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2aiwdzdpn.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2bsgtsydo.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2yckzflts.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2eqjbtiup.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2hhnznyvo.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2rkngtuoe.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2yfzxbiax.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2zxnvzwgh.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2mmalatgd.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2jpuvmyus.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2zhttxgcx.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2jyafblht.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qrkjayqf.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2bwaxekjj.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ueluqunj.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2mjihusrm.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2ktdddtsq.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2zmcarmse.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2eautjcyx.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2wybwplft.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2hcgginbs.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2gffwgzva.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xokdeiwl.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2ehddorvu.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2rbxwpqpa.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cnfsurrd.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2whvnhekn.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2chsqyhab.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2nbfdldwg.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2ycqggcrp.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2jjrxygcd.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2pqzmtscl.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2ciugjqou.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mazxedbi.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2hhkzndcw.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2ejsuivil.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2emvbozmi.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2zxuafeqh.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2ocndlygv.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2uycaugtq.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2knznzcul.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vtotpnqk.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2bfcyjsaa.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2oxzxygmm.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2qtaooozy.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2hgrzoqrq.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2qqnqmzzx.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2zkfoayqe.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2uxoygwio.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2zcopbheh.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2klvlthxs.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2awguhdda.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2wzafbsfh.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2dzeijhvn.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2adnmfbdj.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2njgemxxu.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2zrtysjyy.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2kqjeeuvj.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2iwytbpia.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2duxhicvo.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2ltftopvm.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2ooplblmg.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2rqesrefm.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2xwkokxso.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2xlndrrzy.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2hcxhshna.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hxpjbuhw.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2kdqwmqyy.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2ezhuqvyc.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2iutyyjtf.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2qcolgmzb.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2eyfsfnlu.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2wnpdoezf.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2doergfwy.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2eycskzui.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2cvbzswky.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qxpihlth.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2bncipkqc.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2tinfwsey.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vpdoosli.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2beamljgl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bkdblqbd.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2aaixocuy.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2rwclokzp.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qibttjqi.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2zcqdieca.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2qmxghsmp.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2wttenivw.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2prevfcww.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2myklgwff.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2xyepzplb.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2mcocemrl.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2nsetwwts.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2gesprsey.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2phcynctx.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2brfviodj.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2ycclggxz.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2obpipsfz.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2jmbnwtcm.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2lxgrwtlo.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2pobzogvc.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2cgopudyy.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2wvbrvrdq.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mospuoko.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2cabxinkw.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2jigibsrk.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2vrrhaggx.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fnwpznli.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2pmirjolu.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2cfwxzlrp.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2fclswskb.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2xilrrolo.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2rwjrczhz.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2dgojgrbs.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2fqixxfev.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2solkmjaq.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2vifvgitg.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2jfsamuhw.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2gjyvoixb.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2hfadwmnc.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2txpmppgd.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ytuqiwiu.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2lsptxxxg.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2wypsrfnp.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2flvndmwr.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2zuocbjbv.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2cfnycyjv.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2bqgzrsgv.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2mqmloypa.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2mqcbzdoo.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2xgsorwff.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2hywjtote.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2llulhcgv.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2tymwefsl.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2cetjmjky.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2cfxsecgt.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2mcugaggr.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2favzlxdt.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2yafctbbh.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wgkyaclo.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2qoqsufpj.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vynpxlzl.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2zttsgeoi.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2yjafaimm.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2rrclylbb.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2tohuxeqd.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2ewejrtgi.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2nulzdqzy.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2cnjwmpro.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mtjnnyeq.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ooaxxzfd.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2tmcpjflz.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2sbiadlhb.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2awgwfrem.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2vbwaambs.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2luvntlbe.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2ddchfiue.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2kfjsvzmq.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2ggxutztv.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2sogvtayy.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2oplxbgoc.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2eloixxmx.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2kyzizugo.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2eergqlqp.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2jngptsjh.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2etzckzbn.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2kwmpdnlu.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2gbpqfqgs.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2alemskex.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2epradxyy.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2twmohuht.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2cgukjsvt.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2hcwvgmyn.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2aeuzanix.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2chsflpdh.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tnfoedzn.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2xfeohdnp.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2igfdaesu.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2awululpk.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ivjoyqjd.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2eretnhkd.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sgyfwvhh.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hwwlpxin.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2xyfgfzxz.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2bbttnzuw.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qjtcznjv.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2jdlanyxy.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2natiguda.html


<!-- 参考信息 -->