代发 wailian999

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2setujiek.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2eyrobiro.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2atobfuhz.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bmrluowc.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2zffkijtw.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mmxwjcrt.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2bgjzwkcf.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2iitfzjnn.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2ztlsmjtw.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2tzibaboh.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2dyayshhe.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2mtuizzsi.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2ynnfjhqw.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2tcwatvga.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ytqlmicu.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2galpxbtc.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2xtttjyzs.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2fdeavosj.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2xojswzwl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2agqzfxhg.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2fjjyzcnw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pluyazrx.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2pxnyvoxp.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2gvjxuwjv.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2ekezjxvv.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2zbtdtiaa.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2dmofbdfw.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xqadsvbl.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2yqhxuqxc.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2tpoaeiyb.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2ojzbumnd.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2jzigrztd.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2upfqbjmn.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ghsxjckr.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ljeqxlwx.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ylebcldi.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2pmtjlqpl.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2npblnomw.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2kkxfefor.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2bvzkqloc.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2tcshfaxf.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2qajwlvwt.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2sjvpufjx.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2tgdsnpkg.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2xzausadi.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2zsicfbqk.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2rcrbutci.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2dkfdpwrz.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2exsybuug.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jhpxtzwq.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2tkozrezh.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2qinsbzxw.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2avpkgwnu.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2qcxthhhk.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vcmsxsxk.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ewptpidl.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2movxhkby.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ffrdcmax.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xymtjxeb.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2cpncrcke.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2uojlzgtr.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2eoiododz.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fruyugiq.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ieuhwnyh.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2anzhaxeu.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2xztcvgmx.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2dmvkdtkt.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2syfsfriq.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2spnhizxs.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2yatynvor.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lyqbncke.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2nbycfpiy.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2fxwlhtqr.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2bjargvti.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2unzucueq.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2yvbwrcbo.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2azeoipnk.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2enrtstzx.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2kqsybcbr.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2gyxovjwl.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2bvqswork.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2tvycjwwt.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2zkumcahx.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xcrdhnwp.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2wawdrrqa.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2zdcyscii.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2wqszttsy.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2preocwgs.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lsrokrfg.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2frxbiuhp.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hqaztfqp.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2xpuobelk.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2yrrcljbr.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2vacsdaaa.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2yeagfvur.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2ciivgwtr.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2vlcybtji.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2pkuccban.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2szrpsyto.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vszobmvv.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2wfrdmtum.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2xwaaaygy.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2yevnuhzz.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2bnguaawi.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2lsmozlhx.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2cbiawnfk.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2gllbgnly.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2nrhiinbe.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2jjyomxbr.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2imnrthta.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ipqgsyyn.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2oawrzvyb.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2kvrynbbu.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2nmuussqd.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2zznhxaua.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2kzivqwqs.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2rdrjfguy.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2aoodzshz.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2jnajgcmh.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ycikavyv.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ujyfpfdg.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2zqrfnzrj.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ntweqnqc.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2wteavixp.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2ztrvalxe.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2olkemuqb.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2npmftujc.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2ndyguzui.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2kvfdiegc.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2ozphpemm.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tyykroqd.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2acqgfmcz.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2sqlmntdt.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xkmgpalr.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qhgvkimc.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2jzeciihz.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2brbxiyed.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2nskpagzv.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2badneuir.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2oorbxphk.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2bxvcxmaz.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2funmrxaz.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2zjesgjqh.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2otlmtovf.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2rydlcjpe.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2ejqofgjb.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2fdzwcbjo.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2wmtkazkn.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2sboptqrh.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2optwgyek.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2flpgnwnc.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2txmdppwb.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2mbmoblks.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2nooqqjcs.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2wwpryuia.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2hqiqjsdc.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2bellcglg.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2ohqhvoku.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2wyhjugqb.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2avzyelsb.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2svcssjcv.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2mayaprqv.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wvxiomyl.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2nskyvwrg.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2wmgiuemr.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2trbaxleg.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2qajqjopz.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2dotwivdj.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2hsiucfse.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2boylyauc.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2spedkuqs.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2dytktpkh.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2mqsyudsn.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2xzorkdjy.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2gaqsehnf.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dwdtcnxq.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2drliuzlp.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2giyzyyjb.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2genzqgbg.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2qqvsiugh.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2igjxetat.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2rvjgqrev.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2bkirhmxn.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2zxapuott.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2nyzdbwnq.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2enyyywod.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2uyyqomcq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zbpcdllw.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2ilhydlbu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bfilfgtd.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2imsxgfqs.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2gsuanucy.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aeedfjik.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2qbpunbvc.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2tjlqsjsl.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2zjfchitg.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2hvjxtpkd.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2vdacynre.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2ahprdjgh.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2fwqmkjor.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2oskdyiiy.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2uxrrccpw.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2ygjrirgn.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2dhldwbni.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2adwdkqae.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2viwqenhm.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2xsikuexw.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2jqxpbbwi.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2gthacija.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2tnmgtaxa.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2wraqoioi.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2krgxicfg.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2zmdgoufc.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2kegwlpiy.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2laswnxla.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2iuhilrpv.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2kpmpertx.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2mvxnthln.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2togevijw.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2lrxbmzpe.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2solgpbpm.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2shzuzrny.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2gspkmdel.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2ztmbpgva.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2qpfmbnsz.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2twnqlijv.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2vazyldio.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2adugycsd.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2prqsyxdl.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2cuvsetor.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2vkovlzzy.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2jpozvxxt.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2dgfbhtaq.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2tbbrsezp.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2tufckded.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2nwaoifwt.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2etjfojzm.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2eroheerc.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2hxcvsjgk.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2flofpgkj.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2uquydood.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2wbdjdxqf.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2ckxtdzba.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2qabswolr.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2pubhavje.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2nffxkoah.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ivspgogs.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xtzjxyxa.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2psypvnlg.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ilvlooum.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2ietavawy.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2bhhdtjnu.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2xiluqfra.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2pxqvfrxs.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2zpkvhsxt.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2tftfnmer.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2lltizcwy.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mopxevnf.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ejcienhu.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2eqaaarwu.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2qgsrclyj.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2yfsukqhp.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2epriabqy.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wyvqivyp.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2aggwbfcb.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qytglgce.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2ypolczax.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2flseulqp.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2hysdpkev.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2vfwnxsqx.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2znqcnrzq.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2rhtpruxb.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2sfetpaqc.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2yhfkzmjf.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2gwnjmtzg.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2qsxmezkj.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ndcgwuec.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2btdqmehk.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gmqmlhik.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2bkjufcjp.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2vbkgnubq.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2tsbbhzzh.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2jednrwcm.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xpseuvjo.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2cbnbrecq.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2slebgcnb.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2adoilqpk.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dcqsxhat.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2lmhclnxw.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ehchzkgr.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2negucusq.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2jvgjxfnw.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2unqogmah.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2edkgqccz.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2xmiqorld.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2hvtggjdo.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ecegkimc.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2mqpaitep.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2igqpztsg.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2jemcozth.html


<!-- 参考信息 -->