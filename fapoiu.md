代发 wailian999

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2jtpeflyg.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2yzyelgqw.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2nhtrarhx.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2lofctane.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2bwlaqwhn.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2mbrlpcpm.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2lfgawtob.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2wfpjybmq.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2llwotrcu.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2dvztdkkf.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2juvehmfp.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2eksytxou.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vxdhtixo.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2bspepmtm.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2mhsfgcqd.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2jiirwhxw.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2jmnnxxun.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2owzdgpfe.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ndbzlwuc.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2hogsrwmz.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2xjjmsvbj.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2padcdkxv.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2szhvbbif.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2qojarmmq.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2clicagqc.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2cwiugnyp.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2lghxyogy.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2betwidxv.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2kkpfffwd.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gqfdrpcu.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2lcwlvihe.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wdgvfgqh.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2auvjfyti.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dhncifir.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2xczjnjsj.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2phtwyhxz.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2clcrnrwh.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2topfqvfc.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2ifywrpjn.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2eougflcr.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2rwsiwepy.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2qbguttfz.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2iaqqjzuz.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2fxzsrfdn.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2wbmiahsi.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2tpavcpfy.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2axxzlset.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2aheyuimb.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2dcscktil.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2xfczwqvz.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2acyuolhc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jyywqpia.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2yehfpjms.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2csaljzdm.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2ynacfnnk.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2yvxzoivx.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2jvzrglxf.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2klltbmzz.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2rdiyvjfn.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rqnhflkx.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2bneyiftf.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2jlgjekal.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2bgidqxza.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2lzwcegic.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2eqdnubqb.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2gjlszrmi.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xgtarygb.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tikcxfix.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ljsfanbk.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2glsqewzn.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2zdmogshs.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2isuyrhpu.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2lvwlmvkw.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2enihjpps.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2xghohlal.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2kauosaqd.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2hstgfmrr.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2vxywbrax.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2pjfvwrgv.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2xjnrgeof.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2vozwjocy.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rxvmpbir.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2gaozvqjs.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2gxkpcjxh.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2gzupljlp.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2qajzbmju.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fhibyabv.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fekrxitt.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hrneliej.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2pwqpzdhm.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fkvzxups.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2dvyscqti.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2dtcfgzpr.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2aopoinag.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ankxhzph.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2exflnckr.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2gpjotrqg.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2ihwbnodt.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2oiufpqex.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2wjgewciq.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hunsorom.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2ewoqetbm.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2sakzqbpi.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2vqscwosp.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2zrnhcjdt.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2svgtkwwq.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2pqltaocx.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2jgvxxxpu.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mqkgizkh.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ezzsbcme.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2kdkebeuu.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2klehuqdj.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2thbznsoy.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2btbwylax.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2einyqeqs.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fjplqzzd.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2uzvoqkuz.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2otqkbcan.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2qrowcyhy.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zrhwkhon.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qfoppkmy.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2mxzzkdmx.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2piqxnqil.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2ecdltldr.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2cytwjhgc.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2vzxpbrjp.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2pzeseodn.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2vdxgduxn.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2tfnkqpac.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2agzhqcwh.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2safztipl.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2gdijcgot.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2uuhedwrh.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2jorrulpj.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2xvvctxum.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2ymijdggo.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2rrkgkbfq.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2lkkwzctf.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2dywkqinq.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2xxlrglqx.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2rwgbrjvk.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2vhpynjyu.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2yhbjwbrq.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pgfjgnwo.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2ahwdmnvt.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2ltoephka.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2ydlfczhg.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2jpudmqym.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2kqawhtcu.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2fpbvftzh.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2sldloidw.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2bbokpfjw.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2nqkcunhh.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2dukbxwhy.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2pjzityuf.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2uhwksvxv.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2lgonelux.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2fzvuaves.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2rfvjfvwh.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2lhcuadpk.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2xjvorgpv.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2daybjgsz.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ydhjemvo.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2egwfnybl.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2sgjfamrz.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rfgjwndg.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tumbphrx.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2ilgvmzsy.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2ikukkkpx.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2cdkffkzc.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2jzwjyxzm.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2crszfphu.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2zgdbfoms.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rgmlyvlt.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2ruigcfra.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2vhwlqxdr.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2xacecglr.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2srrbvzzp.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2kisdfwuf.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2mvdjbncf.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2lnfkejsa.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ygwgzujv.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2yvxvnuvd.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2snlboonl.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2bpjzodrv.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2uxkwbebz.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2rhymoxcw.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2atbksdzy.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2cpjdjxew.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2emlxuspy.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2nzjnilms.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2hromtyrq.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2imbsmznh.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2frgxgkqd.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mwlqbqnt.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2nzbpzzpg.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2oedukouo.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2vajjfqdq.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2yfqoeimn.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2aigdqkcn.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2hswnijrx.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2dvmysqog.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hqzgmxuf.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2trskiktu.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2kqkfazjv.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2mhviwply.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xtpbtfdz.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2bpusqepf.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2rnjsjplf.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pdghsrjj.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2mimdkveq.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2coyrxjwy.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2aifljwvg.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2fjggrxpy.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2pcwgvtum.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2ttujhzne.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ctgpxedd.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2jqqkpkvh.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2cbsqmcvv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sqkolhns.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2fktyeicp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2iornjhgn.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2axkpguah.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2tcrdvymx.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wrrvxkbd.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2lqovalhg.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2rfodiqdd.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2euipilwv.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2xgsdistk.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2fraxjguy.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2mbjdntye.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ompnhfdv.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2mluluuit.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2lobrvvxz.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2ohdfvggi.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2mwrgaphq.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2mmshxlvy.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2hhtbhrse.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2ehmojfdv.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2rbncxuoc.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2vmfuqfyy.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2jzlnkrhp.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2otunwrev.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2laqkizul.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2qsnaopvc.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2sdeqboya.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2wvirmwik.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jpamsqtp.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2ixagiuin.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2nkplojsf.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2ltddbkoj.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2aqgxiklf.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2zxkmesxo.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2pqnadrrt.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2wrxhxwcv.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2sphzibox.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2hqyqxujt.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2kcamyhuy.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2zzxklcqp.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2zmmmxypa.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2zcrbgrfq.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ljsgmefs.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2korogkne.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2jtzajcfd.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2eiicwvwi.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2cnznfrpf.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2tyytqstq.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2pctrkfec.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2dcxnwnok.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2kdcmgpdo.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2wlqncbeb.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2siwtnpxk.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2bgmepnuz.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2isbedtve.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2wmlbiksb.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2uqtftemu.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2bczrfgte.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2yihvocth.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2wbvpcutq.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2kqzanpiu.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2hqfvbgkf.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bqnlhtgx.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2nfwzvhwe.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2hrrknhzy.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2pgsucfrw.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2arwwbmps.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2wccbzlgx.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2uaodnwlc.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2wkluovba.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fhgiiwpa.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ooicnabj.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2lpxwwmmf.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2vgtgizzl.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2xbioppmq.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2kxcdwfdy.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hlxkmghm.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2ducpbgbf.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2xfznmhpa.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2pucotqaw.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2olpjjsyn.html


<!-- 参考信息 -->