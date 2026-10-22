代发 wailian999

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2bdqdmaon.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2jjhecvja.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ousoamwp.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2clpwedxo.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2kufzffse.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2ffuppzeo.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2psuzbvmr.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2jjksikiy.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2eejikzxc.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2yyqvlczq.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2yxgxmymk.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2legnjdxd.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2thorgvta.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2cdlaaouj.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2xaaotkut.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2szcuzivl.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gzlqovdd.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2ksqsffui.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2bkfvpzso.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2hocifpct.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2zicmpnaf.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2wqadjnrq.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2cghinjfa.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2wdemnrgi.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2gqohfcvq.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2pkfzepsb.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2olirhhnu.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2yrfglvoa.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2rkjfqfbk.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2pwzygvwz.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2doezkmzx.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2dqqtjzcd.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2rvohlhnc.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jveulxcm.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2bpwmzksf.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2uzoogbtc.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2shmlpshu.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xcqqksrq.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2vymfhisv.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2okkxqazr.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2gotnsjfe.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2luvsbncg.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2nrukzrad.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2nnswmqcc.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2nssftgzj.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2pbbozspf.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2feirfbvb.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2mifalmlu.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2ewlfxcvo.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2kagnymdf.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ibtcfjiu.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2wjuconck.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2rvoummtb.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2rgcudxtb.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2pjhjejax.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sydprhha.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2ftqktjvn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ovtwelzo.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2aibgsijw.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2jmeenkfu.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2kawjryau.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2boyaxynm.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2yxwldwmz.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2kyffuvje.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2oafuqblk.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2iqulnxxn.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2ygkadhoc.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2jxezrvov.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xlhaultc.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2yrgdhguh.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rismstkr.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mvovvada.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2zkcbdkxh.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2jpgovcfd.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ebdjabiy.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2jygpxeit.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2gnqdlpnb.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2hfiaqgld.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2bdckuudf.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2syjkvajz.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2orqtauns.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2zbklksic.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2psbgynph.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2hxnxohua.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2vrxdsxgd.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2viijgpnz.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xznemgyl.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2vfnhgkac.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mjqvkdfn.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2vhiccvhk.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hmycrgud.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hslpxvey.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wozfhfni.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2iiqhlvuz.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2cldtbxpd.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2dkcmqmol.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ndkkihsy.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2vajvdljc.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2rrlkyjyg.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ukgulhva.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rpfvxugu.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2kriduptk.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qttodwhb.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2rkndksje.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2bwhxuoru.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2jnnpawmk.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vdsahdzc.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2frgrovaf.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ekbplsze.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2haaljzzl.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2uzeagrih.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2hbbahpkq.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2umtrytnh.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2glpqqtdv.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2sabfzaeg.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2fmfwvezf.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2wzlzzaum.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2whmwmaxt.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2fbokxnql.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ogikwxcs.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2yxmtjluf.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2tzzgdswu.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2qssyphyy.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2buflecoh.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vxiqrdsv.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2uvnrqmog.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ksrnnqds.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2xagrpsce.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2lunzraml.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2mwusmsfb.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2mkbqpcym.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2usqurxng.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2eanapggs.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2jzyfsoye.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2elazphgn.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ojnbknnw.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2cubfajmi.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2bfjpmmkz.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2gxyzptox.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2wqhjmkiy.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2cwhfwlim.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2vpflohnp.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2kheixflp.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2hrynqpgr.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2qptckxqk.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2dpshuxly.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tbftedsd.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hwvernqk.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2swkgpckr.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2huodojgn.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2gsalmdjo.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2ygvhqfdo.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2dngekzec.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2guhrridt.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2ewdxlacy.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2yqfwhwiy.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2gqokckzx.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2adopoeci.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xeyxfpqe.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2chuldrut.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2qbtbrzox.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ftifiiox.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2abhgqjkr.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2gqrrsfhd.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2bptccsgp.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2mkkzezbi.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mxgdgyuk.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2cjmwcpsz.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2zgmxvnwa.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lxeoamov.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2feftybtl.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2oyoxkifb.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2svscowjm.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2ynknghnn.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2ohukqoaq.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2kbiwpdga.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2euyhvjnw.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jpdswfpj.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2jdebtwzl.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2nvvmzoiw.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2tqdmjjji.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2wawqvzek.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2hgnpcwuy.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2zspgdsox.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2ikleattr.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zwqynkfw.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2akbstjpd.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2astuonqe.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2atqcgxip.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2gujwshma.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2ndrksztd.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2kjppzvwd.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2wmgruwue.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2afywclie.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2mctkrktt.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2dezdpnmq.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2zjehqwby.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2fnrmgngm.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hpvpfqmj.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2fcunzwwz.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2wsqbugtk.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2lpdzwmpe.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2luiwuwff.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2dodhvmkt.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2nccmkjev.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2efugexfa.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ohqgdbao.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2tzijpdap.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2omifthtv.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2bpymbavn.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ineqyiay.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2puslgwie.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2lgievwxx.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xlzdhges.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2jxtfzrnk.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2wzcvvdai.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2hkcaumhn.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2reixibqc.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2eldyhbqg.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2gorzakke.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qncdpwph.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2fkvwwvfc.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2autzhxpp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ezhnorqj.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2matbisrv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uwodewfa.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ayqrmsbu.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2msfbtdpr.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xoqgultq.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2busimtep.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2naaqnkfe.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2udrwuthj.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2totueime.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2zotefhum.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2xzancsbn.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2mwjmvjos.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2odgqvnpk.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2vxnlqzkv.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2sqjaxccz.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2wkbaghgq.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2rzfixsai.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2ctgyfwmk.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2lermfkvf.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2fjdoppsx.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2wgwzsons.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2njfrbjkl.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2gxgfbeht.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2llaovbdl.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2rtgjcchl.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2hqriobin.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2iqednnpd.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ojgzjhbs.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2cbsldhgw.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2gyfznisd.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2ylmbgnut.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2mbyebotm.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2gmehnfyd.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2mbzqaqbg.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2bcrdfhox.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2dndgafpy.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2kwtieqkj.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2upuinain.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2dxuusqme.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2hootzemi.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2vgmdstxb.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2oydawant.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2lrikinva.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2gfuuuegw.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2mwcfralz.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2dojdzutp.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2wdpbrtbb.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2hhueucsr.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2bhuzbmaf.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2xhfjltac.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2mdeypiiv.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2ecngapnp.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2lfakmuos.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2daevzpyt.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2uuhqabiv.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2qqqmjpee.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2clzdmchf.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2gggcalmu.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2vdeqguld.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jtfpiqhr.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2zpwhptuw.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gdbbvcpa.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2rgqmczya.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2zesmqayw.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2hrbvagjs.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2qfwdkxeu.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2oqhltkuq.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2twgssojz.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2ngqxnzqr.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vffblerf.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2jkampkki.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2pzxytfzs.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2zegswgum.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2dwlfprnm.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2bdjcmiim.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2caqrrqip.html


<!-- 参考信息 -->