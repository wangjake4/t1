代发 wailian999

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ligandpj.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2tkdppthf.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2knvujnqg.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ihwifqap.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2xkmswjzy.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ohxbaccj.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2zhxssndf.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2rkrlihvj.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2pqpemrsv.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2fmwsegyg.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2wtrudeqb.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2okzhaech.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2oesoyoki.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2xegebxjf.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2innozjnp.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2wpzfkmee.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2gmznkxyl.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gwogdlcs.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2rvugigwv.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2sakqsapi.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2iitdbddq.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2refmecss.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2dqferugk.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mkvwxdts.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2ojjbapax.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2djpsplys.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2xhmmxvol.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2ojmryyff.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2miugqukc.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2fglwjabc.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2dkldkcrn.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2ddpisvfr.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2fcrfmzbv.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2bvgytbgg.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dvahyasd.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2jqvnyjdg.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2gamzhqww.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2sxlqomnw.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2nbmdqbsi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2meeligyt.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2ujbdnxon.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2itkuadrh.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2vbbnjpjn.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2vbohqepe.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2ysbbzkci.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2fzvhkqsa.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2hnueykuw.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2sytpqkyv.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2bwwfggfa.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2iwxkmrds.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2zndfoajj.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2miagtfdc.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jssiiqen.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2rkhllfpq.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mfwpzmgx.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fymchpws.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2bebnwmlk.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2kihdrnht.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2aamrzriw.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2gepvrbgx.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2zqcyayjc.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2dsqmioob.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2botcyqcg.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2wxatzghz.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2wlrgyuwx.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ulkjpttg.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2baevcnws.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2irzrkyxq.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2nlnuzfzy.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rvuqwqfy.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2oioitkys.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2cdiebryv.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2cgpgjnnd.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2eqkwqwjp.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2zsqabrlr.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ktitpvkz.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2gdbxggcn.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2nkowpove.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hfvzqkvz.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2pahkztvo.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ksrghuuf.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2tppkfkhq.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2tjgidntf.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2xfvkhhxp.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2eczjxozq.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2plixwuxb.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2krnwmtjv.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2dbxnqthd.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2haabhsli.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2vbrqrrip.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mqgjqghe.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2sxgaxadl.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2zbktxwcf.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2pehvrgdn.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2pqxwyepu.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2vnepmsvl.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hlzzzvnc.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2rrhbngnd.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2wepvqeub.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2dwugalta.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2otlontmw.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2gpilvblt.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2gvheitax.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fdfdzbjy.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2irlvycxf.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2xkvuwhva.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2xdxvddze.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xlkmruir.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2esvnqulj.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2qucvddmu.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yccgcrks.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2fqetgvlv.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2lpbixthf.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2ideyzdnz.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2sjrgvgeg.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2jesdaaql.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2gcajumkr.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2jcvjzmjv.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2aatugnwe.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2uxouswne.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vzllrbdp.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2yspnqrtn.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2bebxxzwk.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2fridnfjp.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2gqujeimi.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2yonnbvhx.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2bdkztbqj.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2pjfpejjb.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2ajsjclvx.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2zdgiatur.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2gwemgcur.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ppmgatmu.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2mdovjewm.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2ygwvfdgv.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2bvippgdg.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2sxzeykze.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2xqeywfzb.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2jnwygfys.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2cnhefhwz.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2khgkngzb.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qywkmizu.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2cyjirrbp.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wbcxivgc.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2izddoqhs.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2rxnbzlhe.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2yavoqxya.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2bsbgiiij.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2evvyqdzg.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2tllgixgz.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2fghqgguj.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2eoxaakrr.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2guxqpfrx.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2ufvbhmpr.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jhzylmsk.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xtjsdceq.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2gbqvgihw.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2rbzxslit.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2caolnpvs.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2peoxwtkq.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2bnbhlvjm.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2gcendgxf.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2oeknmmnr.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2rvbcsphv.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2umynmfmp.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2aczpzgzz.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2ebopcaop.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2fsbvirlk.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2kihmnaxs.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2pbzcwibz.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vxnqpzef.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2fjxwsctl.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2peykadal.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2pgkajrdk.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2ebngvdnr.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2iyyqbxhs.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2oeqpadbx.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2glctnxkq.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2mywmxzou.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2eltwurua.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2ozklfxwk.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2qwnhhagy.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2jkccnubl.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2czqvqapz.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2getdoypx.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2hvaxiqie.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2ecvcthjx.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2vycczths.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2tjoqqugz.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2ctswsshq.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2aeuffgcs.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2cahwkefm.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2qujenenx.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2xdhcumar.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2phxujomz.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2nvmoqnhe.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2lxzymcks.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2bmgeqrrc.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zgzamjfv.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2naodywws.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2uhmhlswg.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2rbbhnhyy.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2veoacyxj.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2sqnxafcv.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2sigrlkid.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2cwlnjqyn.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2lgjpicdb.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2addkpizk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2iijwhkas.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2jkooijyk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mgvebktk.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2xbskppky.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2wmwfgmqw.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oxhymceg.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2hdhxpfzq.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2jxfygeyh.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2pnnjeytf.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2ggobvoim.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2jiqhearn.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2rpssvaax.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2vtogjeng.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2okfrllps.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2xghalfca.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2fkdtdrud.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2cpfbrzrj.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2spydrcwl.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2jlyuqnjc.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2fyitzhsw.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2lyukkvoq.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2hlorojvx.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2nudcwidb.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2xtnxuxlf.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tksyqtwl.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2hzyjrxwv.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2omhqxicp.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2lrfijfze.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mbyhawdb.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2gfjiwnxf.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2lmdeprwa.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2fykkvudx.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2xtrcwrca.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2klvrazof.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2wdbpsohb.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2hsabxrma.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2ampxjqum.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ukingszx.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2lmnwmzfh.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2xjzqctnv.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2lagmunnh.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2veysgbyl.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2actbgzbx.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2xfwslwbp.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2dzzuvnqj.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2wpdjkiml.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2kcrdkbvj.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2koaqsmht.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2qoedtmdk.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2tsdhxoaw.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2pdasfddq.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2cblkujkz.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2qftbaoyb.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2gfuhkbsy.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2ceqmulbm.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2vmaewxis.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2iegwzjdp.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2ljfyhfcq.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2biwesgsw.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ufydsnjf.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2sniilhot.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2wupxsefx.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zveaezwi.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2puntrcmx.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2cgkxcquu.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2sjrvznyb.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2xiprevhj.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2gcevkigs.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2mvdebsml.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2bhpzdrmu.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ickuybze.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2vrhyggsu.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2znpodqvp.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2irzrihfo.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2vnthwshu.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2admayigu.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wzfsrkxn.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2kxjsvoym.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2lojiayfy.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2eyumdvff.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ubaqyjdw.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2qpiknbju.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2qsattyyt.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2qneusgaz.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2aqammote.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ummsabhy.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2guymxrrq.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2pbqrklhf.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2amdmigip.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ifbulray.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2mhvwuojx.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tuffmmnh.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2vwtgrevn.html


<!-- 参考信息 -->