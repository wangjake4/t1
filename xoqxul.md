代发 wailian999

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2lkyqkdnp.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2bcyjgdah.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2tzbfoosz.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2lmlgmqrr.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2viipmntf.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2thlrfjpi.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2ohgybjdl.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2ectzizms.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2mvcxiite.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ictunxkz.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2xrdrdkdc.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vvocxelu.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2itexchcl.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ryrgwqnl.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2xdacrpui.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2uffdyucn.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2lxvbegws.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nqjgihif.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2ujaexzbf.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2joioaldu.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2onaaswnq.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2acshliif.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ybyskmik.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2hchvgswr.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2cpvaiglb.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2ixrjihlo.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2sizghtmz.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2mfjladna.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2liwegujn.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2surscsrv.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2igzoppqp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2haqiedwq.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2xlwanqoc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2djrdiopu.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2dsrwkjsd.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2tqzmbaju.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2kmcwrxwf.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2dgodszwz.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2jkcczzxq.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hprqfsol.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2huvyjmar.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2pgqotiik.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2psmwafah.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2nrsvxzrz.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xebepbif.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2zvhhudkk.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mhtvrfja.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2grjmofab.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2llztwzoy.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2jqcpztvh.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2jhvgybrx.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2htwoqkzq.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2eqqsqosj.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2dtjpzzay.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2eutawjcf.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2tccisxkj.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2tcojipas.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2isvswlkq.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2mjqawptm.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2tptrxfui.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2wmbhkwuh.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vmanmkao.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mtelxhyg.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2clduuyiz.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hbrtrnnz.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2tmhlssta.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2yykcxxvy.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tqlhtmtz.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qczeffve.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2fpyuxjds.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hncqdxkr.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2htgribuw.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2eoklwuju.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2csilsbps.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2uuehyeqq.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2zaakwqfn.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wvrfecul.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2tpwhtjxv.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2woojefzs.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2vzlkwziv.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2fcekgxtg.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2yprnvqhe.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2iplxohzm.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2uplpwfaw.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2kvtltlfj.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2vbvghhqa.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2fcoxsbpc.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2oerjsiem.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2gglzqaim.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2kyqvkiha.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2xlcrxwer.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2uaanmhrg.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2fefkmoin.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2imqhihmi.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2zamapyck.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tbyjrvtr.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2dwheythb.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2hrhukqsi.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2hwljwxfx.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2osdsqydv.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aichcivx.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2uegwdzyf.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ujfafucg.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2rijzhiyx.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2qbwtsylu.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2isojxorp.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2bptjqzqy.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2pxhjeopg.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2ljmuyqxt.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2airegxqg.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2vsmhdjrv.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2afycochy.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2bvqeubne.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2idzfudbl.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2lguhesui.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2ttomcakl.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2djdyrkrs.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2lddcowpc.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2zlwpjcch.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2hkdjnlue.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2qlmtkmid.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2peuotzvo.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hrtowrsn.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bjbncctb.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2khrtrdph.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2dcmwwgxh.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2vxgvrjzk.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2iqaquiyy.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2exkfjzeq.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2eizwbytd.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2gmdfwvaf.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2xcouhoae.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ybwipqot.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2dcmrokpc.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2aogukkhq.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2oqxnychi.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2smgfxxdi.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2zbzkqamv.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2iquypkdk.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2muwdvtrz.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2nktgrglk.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2jfajrszl.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ngtqxere.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2fkmpugoq.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2tdtvixwa.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zowwnhru.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fialwsnk.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2qypxsdiw.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2ylcmokwr.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2iohknbft.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2sqodnwlh.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2ejfhzasf.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2xazospeq.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fygehcrx.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2garpppsj.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2cjryslfy.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2nkrlrhsw.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2ggandbmd.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2clywjbmm.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2pnnxfnep.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2eiekxouf.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2udumiikt.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2gcmwyjxs.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2gioqrfnc.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2fykuqpyb.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2ktglhwto.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2xkjlzwtp.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2mezixrbj.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2mjofbnnt.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2dlfsvnqs.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2bemfwprq.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2cjoynubr.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2latzbcsj.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2ftbuvrwy.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xjcrcfjq.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2monlpqlh.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2simauvcw.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2lmdfcmvg.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2udpoktte.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2lrratnzv.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2eekxcgfz.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2ehqllere.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2gsshfpxn.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2qezusyat.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2exiodkjq.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2rxifmzuj.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mtdzfepn.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rhxsblam.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2kjwonfzk.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2exiyyxgd.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2vyaptnbu.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2gcygsiwb.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2nyritxrf.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2bkljazvf.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2yjezqijw.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2eidsbrmc.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vfkopqto.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2mojrespu.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2gjrxiymd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mcfxgbvk.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2wbzmrqmm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2htelbwlk.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2hmwwztpt.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2izfrzhwk.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2inmbhnaj.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2zmkvhuuh.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2ewsymnuy.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2yglufcak.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2iojdwxck.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2jqkpytix.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2dckncdtm.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2tkpxylve.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ntalegif.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2syfzdmba.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2pgvwjbga.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2qfjsuxoi.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2jwtgjsvs.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2thqbgane.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2tketnlmt.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2gamqihts.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2cqhjwmuc.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2xolbtksc.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2jwuwdewf.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qtjzfyzk.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2wsdssqai.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2rkrubruk.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2bcqkipcj.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ztzaltmg.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2nxcerlpd.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2lfvefaon.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2stbpuywm.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2zxkyyffo.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2puqbssnz.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2zzmqesls.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2qtzvtzvs.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2rhmeorrn.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2cfhjjhjb.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2bpauaqmw.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2dqbfbynf.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2cpukyvuy.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2ajyewywf.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2vzluddhc.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2mfttndpp.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2fjwbeiir.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2crqjfusa.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2vkdnkywf.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2nyxiclne.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2dwtbcsuq.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2upsjhvts.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2yiydoian.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2mfhejdmi.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2pqhlocmm.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2rskidode.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2dblamjps.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2jynjvxeb.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2sxthtoig.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2mgmplcvw.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2sdmzqumq.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2mdbrdrsq.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xcyfdzqy.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2fgjemqcg.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ahxmvphu.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2bgyfadfp.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2wdknmfyy.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2jcyhxtiv.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2nqpqxqzo.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2atsjgzys.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ykipufrz.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2mtomilfi.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dvaybusv.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2efbtsrrb.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2odolxppn.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2oecnqftv.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2wdmqxomd.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2kzgkooat.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qwvbkbkm.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2fjehqwfp.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qharcsmg.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2wkrgqieg.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2zfdtsnmc.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2lsxwgbez.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2sldwpyru.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2szkxpqxd.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2okqbkrwf.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ivkrqzgn.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2crpivbqu.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2wygvyhiy.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2buftubaz.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pnebundq.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2uuhzudbz.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ryuehkff.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2xsqdnsti.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2rpdqojjj.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2csfvmsdr.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2wogxgvsq.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iodqlsyp.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2nmkbkfgn.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2kglvjigm.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2rzwrjgib.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nwhahpww.html


<!-- 参考信息 -->