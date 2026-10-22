代发 wailian999

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nprrbncv.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2lxtejhvi.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2swjpszie.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2gammktms.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2wufpovpd.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2amfuykqu.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2fvhqcwvy.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2zxewpuvn.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2mwadmpdi.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2gqyfrdjt.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2szpzkqpz.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2xhihskpa.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2idvltrgs.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2rhpoxqbn.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2pdtrunzn.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2ddcibxcn.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2rnsumhpu.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kkgvfmuh.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2hlxmvuqj.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yghhjckc.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ukrbnfcq.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2eildwkfo.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2naikfrkl.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rfztthyc.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2fgpswoyt.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zhvhoypm.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2ahnsgocr.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2bifwhlib.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2pnfcdqfu.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2dimqjllf.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2owtfklbb.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2vbeceluk.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2rwrbsxar.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2reochaok.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vzutiaaa.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2hufidwco.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2kvetjkeh.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2fqfsxavv.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2omcfspyn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rgcadijj.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2dkpragit.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2diktvczu.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2oxeoguav.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2mptyglyv.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2xgomnorp.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2teduvdqy.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2sbmboybt.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2tvmbrxfv.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2kzcialnq.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2zlysvuhn.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2pmfbnjjv.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2slsgqqxw.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zsvxpshr.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2nzwypboc.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vkhowxcu.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2otkivmuk.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2zbwskkfa.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2yjvztdgs.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2rfnssirm.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2syhbvbkd.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2aytznuwo.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2rglcxkzl.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2mbfmpuav.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2mylykwlm.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2lrovakww.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2bkaaqrfp.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2onycozrl.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2zjbmjnuk.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2qkravqfr.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qyyhctmf.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2rnjakheb.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2maibjtlh.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xtnognlv.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2oenzikxo.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2lruhsaoz.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zfvpkeqq.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2bnuddwlh.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2wbjzpcul.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2czpplvrr.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2fcycaixm.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wjwgvtse.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2jymievkx.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2lrttancj.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2mavoycjh.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2kpsbxtos.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2rxvqgbkz.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2gjhamfmn.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2dvrmagbr.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2uerfukks.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2tuhuflpl.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2gylgnzwh.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2oefzmlvo.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ljwrrdws.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ispqjbth.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2gignwhjj.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2nxsbiaxi.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2liejljyp.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ptdiriyk.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2zuplqlpl.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2ipqcxnxv.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2abjbsdjg.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2zavwcgoe.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2wqadfseu.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dxxlwbda.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2sooqtcjf.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2nuraunax.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2hmxdztgc.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2gdbytypp.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mragmqht.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2lacdestx.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bwwcediv.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2wvofcwsp.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2twebzsej.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2pfzxsbee.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2tngvrstr.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2hgkxypdb.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2yflwytor.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2fjkpkfkb.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2ykeaqwjy.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hmmjzsqe.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2nfhxrktb.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2pymygqvb.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2ufwuloxm.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2spzmrjqc.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2oyezlnuo.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2nqpzmvdx.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2ovehkukr.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2xtlvimny.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2szhbtmjy.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2upatghqj.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2rwydsphf.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2reduunml.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2bidownnn.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2ftcyuzuy.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2mzxwmshu.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2gxwqgpto.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2pnmugplf.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2ffhtroqg.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2ssxpdwwv.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2lxondkpn.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zkqlrwwh.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2upelhgqk.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2byqvfsnw.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2etxdpjox.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2nogkgiqq.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2pbghguqk.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2dgjoeedf.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2maqcjmwe.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2eqyympob.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2sqgvzpks.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zphgodqz.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2wndkehlx.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2pceaexxf.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2eqctbmib.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fvuujavs.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2bprvnjoh.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2blveujni.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2hhbjovrc.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2jyaryapq.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2cxjxaflp.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2rswsiddo.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2riptbbhh.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2xjzdexoy.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2pgquixkt.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2rodbqpmh.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2bzshyoxm.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2yrtlyoqy.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2awamuqdh.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2ahtwnrlt.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lmmqkvwh.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2eobphmzk.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2hwowdlav.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2tryjynep.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2vpaflraa.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2hcbndtfx.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2moxjjfob.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2qhjxryal.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2rpxrxnln.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2xlelxvzf.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2vnvcsbkf.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2sjgisghr.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2uioywcky.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2rkchckno.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2lafkawvb.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2qydmnpxw.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2cfyrgxqy.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2yqvkppvd.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2gwfkrmxb.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2lpowkxke.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2hznqjcxe.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mlbpabmr.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ucrydzwa.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2hmdifytd.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2wmndtnss.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2pvjlxghx.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xeftwdgv.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2bimegyuv.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nvbovlsi.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2umtjrtxw.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2cdivehbd.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2fqeyziyo.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2gtpfhbvm.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2swurjqbn.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2golszxro.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2avhqjqeo.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2cocvffey.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2mffonyme.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xushtzkx.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2rklbhcky.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zllacoqq.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2npqbuuuv.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2ohprlesb.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eqpszhkq.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2nlarvjgy.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2xfbdjruk.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2gwijmyvl.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2elmdanfs.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2gwwqgnst.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2slniunvd.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2bgkjrqiq.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2qozqkvxd.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2dowensqb.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2edezknhu.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2bopabtpd.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2ppopaxth.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2esqjfhsc.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2ddwxtyhj.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2baqoield.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2jrrvabri.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2qstvrvgj.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2swfnjomj.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2owtkeaar.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2yyrzgyfn.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2eytyvbrp.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2cwwdemcq.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nfbpojhv.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2pnpyuwsx.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2szaphnes.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2pocmonfk.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2qsjkrsmq.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2ftyegxam.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2yoqbacnl.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2rwhmrfcm.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2twgmbitf.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2idxlyivm.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2gbsxcfzi.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2eawgsxyx.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2vsqirlnu.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2mheludtx.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2zmzzugit.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2iusvoeyf.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2qtvlyaph.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2utanadry.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2cyladshv.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2gemrjrhh.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2tsihgtkp.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2xlalfwhd.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2zueijmfu.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2kzqbhaxg.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2liediyxw.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2eevaehuf.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2tzxwpziu.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2mcuaeyqz.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2pemtqklt.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2mzsseunj.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2eicrewnc.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2maxcclxr.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2bswubocg.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2cllcckxl.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2irwbootk.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2oklrpcix.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2kxusktid.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2xuhjinrv.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2xyevbmdf.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2vxtafelt.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2fscwgmnq.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2aqheocid.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ahtgfxmb.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ogfgnmcs.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2tzuekwhg.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2lqpckunj.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2tbybavcn.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2bzmouljc.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jzrblrvt.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2lezmvpgg.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2gxsgvazw.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2bijxbfow.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2bzfnjtdb.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2eypedrij.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2bpubnylu.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2zdapbcuh.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2axavwoue.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2rouehbjz.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2ostvcxun.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2loxwlvkh.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2afjfbuyz.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pkxrxibg.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2dbhniqfj.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rajgecch.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2bftxoopw.html


<!-- 参考信息 -->