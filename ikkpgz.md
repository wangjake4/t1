代发 wailian999

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2hxnnqmrv.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nmzvphco.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2cycrezrs.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dfsqjuzc.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2iednflei.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lwaoiexx.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2iqmazjpf.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xwetodrh.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2ynsgdjzd.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mualwrto.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2njpintgb.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2zmjhdtrm.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2yvopwdig.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2hgvshttf.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ihkvnqny.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2qczawcrx.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2mqxeqtvf.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2muxvodab.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ouqqgpwd.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2reeqelvc.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2iwjixhxb.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2swjnhakv.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2cocrmatr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rjxlnhfz.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2hhxnyjxn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rnjcrukj.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2bgdqthac.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2tfbpietd.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2knvdsbna.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2lihlairp.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2udnsadnl.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rspsnvua.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2jegvcvld.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2kagedhhj.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2cyfrtwsa.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2sliaumcu.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2riezmndt.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2qtmvwiqn.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tbrhefpm.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lpajhqtr.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2psebxfmn.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2pgwokpji.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2kqvvdyti.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2hwejlxpm.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2smzchlzn.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2bjzelqaq.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2hldahvmq.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2rqmpztus.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2pcjdohpx.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2tgmjuvqf.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2zbdmbjfa.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2zaxzwepw.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2ghrxgjhh.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nedywsop.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hlwlzgxb.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2hvrvaygx.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ozwmfaim.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2xmhnllxy.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2lezibwnc.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gktpbatn.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vowqtdts.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2hbquexzv.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2lrscokec.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2aklzhbzo.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hizuicpy.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2emppsusu.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hnrqjusr.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2lonkixzg.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hdotahdt.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2zytuhjmb.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vsinazek.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2rbsrgikt.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2tnvnvtda.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2wcdqtocu.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ckbyizgo.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2irqngsft.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2exhxlnth.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ewsellfp.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ifhzsosg.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2pnmryucp.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wdxzofgi.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ihguxayg.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2hpjfvimq.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2vbkkkloc.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2gzwjtrug.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2tpwmufhl.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2npxvyyec.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2honrqrsr.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2kaehddoh.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2nvpvhtvs.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2xoyemvjz.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wfqkpxeo.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rwtxutkw.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2iuzswkhz.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2txefvsxq.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2ualqlgsu.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2siyxppfn.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2acidjtei.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2xovwznri.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2ukbcelpp.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2zbyrdmpn.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2ntwyyjln.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2bkwlsyrg.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2anljhgfv.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2kuuwmrym.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2mydbpmvn.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2gumqjovl.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2cfmpqzkm.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2fllficff.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2tzfahnqz.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2ksrpbewh.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2kefxjurd.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2anpzkfac.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2yhhvvprv.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zawzeyha.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qpnntpkd.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2aelrkklj.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2dpczkhcc.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2rnwrejyw.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2dweqnewm.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2jhvezpvs.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2nekbycso.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2ezqqgxej.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2kuprzwjg.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2uyfumrwq.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2tsfoslml.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2nfenknao.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2zqkzmzvr.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2swkxjagx.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2knjvmfic.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mxksxeix.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2dcsezcup.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2amqalrbk.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2ahbdsjnw.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2aopbklgj.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2dqomijkv.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2tabrjyuu.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kzfsvjlv.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ztelnrld.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2mtrbvnuf.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2pzqwdmjn.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2smtkcemr.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2joodtigz.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2qcgrdkph.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2acunpxek.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hcaemokr.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2mrahlifg.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2txgyztxz.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2tlcimewl.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2mvoeohke.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2qtyubopa.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2bagpdnbr.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2axjdxvob.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xbzvnhpd.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2bnkhtrvb.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2xdhcyztk.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2gkakesdt.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2veggsnlp.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2ritmkgmv.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2asmstfln.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2bpqjcnwn.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2blcahxqv.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2bfcksixi.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2pejpaovw.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2ywbvzbmb.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2pwdelfyn.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2cclluujq.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2ojxttovo.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2kvynahrf.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2hizfjjlw.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2fwtaytrf.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2kdauinaq.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2ucrnooiq.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2fyewwxsg.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wqoqzhnj.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2pqacupbg.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2axavcnjz.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2ayndcavt.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qtwwcpno.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2pucohkci.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2qfvmqxrk.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wenlvxys.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2zuvoxqpk.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2lftjbefi.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2wzkipnis.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2pjggvqnz.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2yelogrsz.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2fycsfzwa.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2kghpykab.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2dwqcwkpf.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2hgszpvve.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tbofbegz.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2ayzeqkbf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dxtmhhel.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2hewmehru.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2ppmsbvjt.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2duywvrcm.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2jiztjztc.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2oncfijrr.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2qovtvjyf.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2tfiahsjm.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2hsomwbal.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2fmikxrxz.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2jjvrrrdu.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2sldkdepc.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2upcpfoqo.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2ndqgfbqg.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2pxlypwem.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2mvlbmuqw.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2uqilysqt.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2elkzewdl.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2yagoocaz.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2jbwzmyzu.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2lktnjpgy.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2wgatedcq.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2shgqqfhl.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2qfrvsjax.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2tsuhzgml.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2gpyxajzg.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bsftnbgq.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2rizebwyi.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2ymlighdi.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2fqwyuqfz.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2obeejehn.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2dlywvvyg.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2cbuducug.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2nrieopxx.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2vrsswrta.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2wfagefyl.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2npggkohl.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2xqtwcfws.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2rxvpqojh.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2lbkwcrde.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2bvydifbp.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2xppqdfbd.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2izvapwaz.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2eydzfaak.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2hlbteekk.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2spspfdae.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2vvmlfugn.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2tsnhzdig.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2xagmtsbz.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2rmkjywde.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2adkfslbs.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2heatgvdr.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2kmxwnljb.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2pdtaaqsd.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2slkclkfl.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2wmefsxgo.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2aiqxcpii.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ylrbwgem.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xeolltvm.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2chhakzvu.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pxfodswn.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2gobdnxyy.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2dpsrptpy.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2qssgufvm.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2ahmlswxo.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2xpxudjzt.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2qijikese.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2ecmmcfgm.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qocdszyp.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2tjxuqyxr.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2rodcnnnq.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2bbpstskz.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2nixglpqj.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2nhpafjuo.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ewzrhwsr.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2iclknrnb.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2xuauynvx.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2xrxwfsqb.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2dckevrnr.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2oghidxrf.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2fjvmpsrd.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2mgljzyhp.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2dadntjsl.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2svudlifv.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2ymzwcikh.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2evmzbimx.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2zszydlmz.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2skdwmrvj.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2anhzwenu.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hzooqdjh.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2yttcabqb.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2kndfzvmi.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2nipooklk.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2wnjsymcp.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2njbwensc.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2uesnxizf.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2lcfffych.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2dvjkgaov.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zrhwviua.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2vfsaexuy.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wgyakfey.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lbwvvdeg.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2tntigcmx.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2pectubif.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bzdqpphq.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2ynlxeeei.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2vlfucgay.html


<!-- 参考信息 -->