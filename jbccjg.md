代发 wailian999

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bkjajuii.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2lqhwifoi.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2qqmlowte.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2bkpdeiyv.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2ofmdlpno.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2kgxyahdi.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2qzxvakul.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2lggbrtdu.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2scmdvdrb.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2agfxdryc.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2vokjrrja.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2hkkigsqh.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2otigcvfj.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2effcacrv.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2jdiwvpdp.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2lkowsyvz.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2oxjgsgtv.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jkugiwzw.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2vzooeyiq.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2stewqzbd.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2jmtbgcci.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pijtppnk.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2isfeshnb.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hkjfsxws.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2dsrygmwq.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qutpsccd.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2vftfmyuo.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2vkjyzoug.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2lpgysdmh.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2gcglwqig.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2lpfpkhyh.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2bwfqewtp.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2ytddhuiy.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2yimywrho.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wmdblvlt.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2mosbixsb.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2ibhtppct.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2fawtobay.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2swdclddg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qisqfyij.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2cfpcjfrz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2evudjafg.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2qunazvwh.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2mepjiccs.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2zjuzdyti.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2xlnljxhf.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2rdcnsqfd.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2pzjozvvz.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2aggxdnkn.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2zrqpuylr.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2enqlgqxc.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2klbunuwz.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ysjbrvac.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2prxczwua.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lokziwvv.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tamxrnds.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2lqsbetjv.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2vqryxhvo.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2mkefcvco.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2eibllxzk.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2qxvzdgqx.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2gqxambly.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ijzjjeum.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2woxhwdlo.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2pjghqhsn.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2omkyyghz.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2djgidbuh.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2pfdultxg.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2cqeqtykz.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kojzdhti.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2njfzaujk.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2dstbieat.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2kuiedeum.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2apuodhns.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2reecshvb.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zhssujja.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2yhkvbptk.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ltrmqzvu.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ulmyhxie.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2hlxorpup.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2buzwlinp.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2yfdhyhbg.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2kzpuuywa.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2wvrxnjvv.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2nnqvkosm.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2muzpvtla.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xpdvrzxf.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2muaqoiwc.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xmqlmkfa.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2kplrjznd.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2cdfvceto.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2trabphiv.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2gdupyiwd.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2tyivxapv.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2gpymcnop.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2entgrqzk.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2gywyhfww.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2swyzbyze.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2pdpmkmed.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2nffznbnw.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2zjnkydub.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2ltsjjagw.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2yfhazybd.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kcasfkar.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2epzflgwg.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2tjwvshfx.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2ckempjtz.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dokvudke.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gxrbvuih.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2stzvifuq.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kpmkcxbw.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2spnxeeke.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2rojoybgw.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2rcztozqp.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2llqlxkis.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2kimmcken.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2syxdhvds.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2mjdmlpzz.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2ltfwfvku.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2kmvstapm.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rjxbzeei.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2eksidmdy.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2xtliobag.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2cfzqrnsk.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2oiurkvbw.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2suvmossd.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2gjmtoziu.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2nqdtaljp.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2yaufqxcd.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2wnmzbuyv.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fvagyocf.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jeftcnob.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2wfswihsw.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2rdlyozfe.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2qlqnzfmx.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2ivcguppz.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2noeyuswp.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2qvgklggm.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2cczwsdwv.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2sratkmoj.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jnetfiys.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2fdgnxcdl.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tygvzftn.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2qjtopapz.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2sxtdonms.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2syipwnfu.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2rmpprekm.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2jmwhjktm.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2tfaadrae.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2tvuaecpz.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2amubdkeo.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2bqjgkcug.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2eahhybqf.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pwwjifay.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2acmgxpyq.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2lamjvxle.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2yplikvts.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2fvdznzbo.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2lxqwdvdz.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2lumnltkg.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2opbqxwxv.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2huqkyxsx.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2bkfxqdkn.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2inaqnoid.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2htliogrd.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2zvszfrog.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2qdgrbmpw.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2ekbnewds.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2navjvwar.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hedyrovn.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2eyalovkv.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2lvgoqyps.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2tqxdtxck.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2jbtyaety.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2cpgqwaob.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2vzluqomh.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2lhhxfmfu.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2hjdlbver.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2issccriw.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2dvrvqrke.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2codaesgi.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2giyrwjmo.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ubfhqzdy.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2qbllikoq.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2fntonsjx.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2dwfqeslk.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2mthndqus.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2jlujduxn.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2xfzecynw.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2uoejzvuv.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2tuzgoajs.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2zpavtmxc.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2czwmorin.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2ccfvlpyq.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ictcjbjm.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2kiukzflz.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2izvlqjff.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kagncicx.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2chsanyur.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2wxcwcjpq.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2bqgbbjct.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2cvuvajeo.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2flrsvmon.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2vwywswrn.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2rfazgerd.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2puzshdka.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2omtqjijw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2stifsyja.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2qwbkckiy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ldlvcrfh.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2coorjgpk.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2vcnvzmpr.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iebuypfm.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2litjoqiw.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2asvxrcmc.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2ifguxegn.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2zoujfwqr.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2obwtxixa.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2xhjkgoxb.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2rsebyghc.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2equovvwr.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2aboemcgp.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2vwzhfqux.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2xyextngk.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2tpkaavjs.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2llpdnpgd.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2jjhtffsj.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2quxlgaci.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2zbojkhnw.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2nkhudgoa.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2zpjofzpb.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2evxwhirg.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2iqbccefi.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ujgfkpht.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2vyxmotkw.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2onaiqjsy.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2pjqguapz.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2hiuuafnq.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2tkzwfmse.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2lvqqczpb.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2dfhkghwp.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2qeyfjzpl.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2paytkrxg.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2wvovcigh.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ryhoeoaq.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2qjgoeibk.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2cvbhkfpa.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2djvbmvus.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2kdnynnpi.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2iozeddzx.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2rhokadcj.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2mbmqwvpj.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2daoovitm.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2gmacqhiu.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2jqgvkqxi.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2dmuqwnmq.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2pvzsysea.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2bsosmumo.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2ytccspuw.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2hnwzzjnz.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2mbomotmz.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2ayrxkvoq.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2xjgnueoe.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2oxlpgmbe.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2kmmavtwb.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2shguvmny.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2nqnycgfg.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2cfijrnho.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2amrxhvze.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wljgydsf.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2czywaidn.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2wvggklts.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2cjxtuefj.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2dtxxobaq.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2qciuukjv.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2wvnokthy.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2biblzyau.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vgbhdcfu.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2kuouyoxj.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2avdcojzc.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2bygjhsfb.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ecruroby.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2puiwzdie.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xborgswv.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2odjftkfh.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2bbzvpvjz.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2zviwakyg.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2mvgzfrly.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2qrswjwpe.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2wvuqtnad.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ilmjrvwd.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2nipckxah.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2pxojauok.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2anshkhrs.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2nopxnwwn.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ajtkeany.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jfhzkzgd.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2pkgejxdh.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dkfcivps.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2pxidbvaw.html


<!-- 参考信息 -->