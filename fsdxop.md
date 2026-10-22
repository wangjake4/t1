代发 wailian999

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2mrqmcwlk.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2cvhledzj.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2vmkghdyc.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2jsrnfvnk.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2gfbjykwr.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2oqbqqlyh.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2vcnxniav.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2zhsvfrgd.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ptbmmiir.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2wukwarxp.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2uorznlen.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2zuosseuy.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2rzawrujx.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2xognbxok.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2kgohytsz.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2pgmtzkmt.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2lfjqxacy.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2bvqjwwoe.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2phtfjpni.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2lbramkvz.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ygvekipf.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2ovsogmjm.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2yqweuwtl.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2gcbbvssm.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ewduvfay.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2ovahsftz.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2yrfdrblf.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2mklchgka.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jjylakve.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2bcqbcuzw.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2nqlmgpmo.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2bqbslokj.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2rbjaziug.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2duojdkui.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2oeybvmru.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2oigbiaoo.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2phesafad.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2ysujicgg.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2zmqzzkuc.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2mbjtfift.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2hqowmiwc.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2opamawnu.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2afodsdiy.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2dzqiaxou.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2azpwmyho.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vaopiwly.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2wdfujrzh.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tqcyzybd.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2cumcxfdy.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2arhlvxwr.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2jxwfbdxk.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pasjbnfs.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2ulmaxmbi.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wqewggra.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2qrudjsjd.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2dfoxcffe.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2iydtisaa.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2tducjqic.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2jvqqrhpw.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2smkkofhk.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2qyzvylpb.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2fksjsdqe.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mpogoezk.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ixovrerl.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2relvcfxf.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2kqwsgqja.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2ffxbyvij.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dluubbjb.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2icthjlmv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tdmteqzu.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2vjtxymiz.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2aosyjrod.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2ejdzjxap.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2xzudekrn.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2gcxcyhjx.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2isuhiwzu.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2aiavncum.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2bgzjabwh.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2ulbzckly.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2hzzjtqvh.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ujntfxhp.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2guneokrk.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nilnpeyi.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gsdncunx.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2xwnakuhk.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2dnrjpeye.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2jljwhoap.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2accylbuc.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2gitkxpck.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ivbyhmed.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2gfctxomi.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2opccbzae.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2vcyxiyxq.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2zuswxrep.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2nysblbbz.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ehcljpzk.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2eaaeqtbi.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pxumxzqr.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xuqorgdw.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2jjubzquk.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xgqjzfpv.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2shopdcnj.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2cbnlxpdc.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2crtrahlz.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2rajqpbhz.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2hgubtsij.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ggtqmktk.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2dyvhqjlm.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2cvzoqndm.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2cgommven.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ixkwpdme.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2nkhbfcnj.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2yscfutgb.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2usvzdovo.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hjoixzsz.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2audmgbfx.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2fcodcljd.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2dggfkupg.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2gakviqie.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2bblsgumv.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2lbvlevwi.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2pacycbdy.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lxxqvnut.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2vlqeduff.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xzuavyod.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2dwycfdma.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2nktxcqrl.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2qpaxosww.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2kzajzmze.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2bjbyxgbt.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2swdezcjj.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bxrbtfkq.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2eyzrtdmx.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2wdxbtybt.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2blyfynsx.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rfqfmsob.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ucpafeal.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2hlteelnk.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ffbgqury.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2enkbpdtc.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2ngpqdyte.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2fdnfmvcl.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2oxutgosh.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2foghoous.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2xjqfzyhl.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2sfxchibn.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2llanvjda.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ppmchxrm.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2msybuxku.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2meesruek.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2lniboizo.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2mciewwab.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2cpxxjfyq.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2zlytldxl.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2pqeklozt.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2npqaungd.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2efmdnoxr.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2yxrzwvsd.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hufvgwkr.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dzveiqhf.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2oslfkwks.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2zbuilwex.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2imtsldor.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2frobemiz.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2iyviwmfc.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2ppxaopdr.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2wyrrsvqs.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2jndsdtuk.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vlgilwsa.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2vstfualh.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2rmhfnokq.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2fxitqfvk.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2vcknimon.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2cfupcobj.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2yjcnimqj.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2gxzvpbhr.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2nrhxjtov.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2ympzprkd.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qdfdgfvq.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2quwtzuuj.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2obkjnhzk.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2apaqmzln.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2dyftglsb.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2ltyxcdzc.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2enlzsyye.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2bxsjediu.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2cjpghqiw.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2impqwqsl.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2cbmbykwe.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2htzjkwpd.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2sgyvhviw.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2ddptgpcs.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2jbxxiddh.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2suvmlzee.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2nwnoxvtf.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2plqrumbg.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2hlwutupw.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2eiihmskg.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2chsxaouv.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2kcmmrpcf.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2bgtmbpzb.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2tggpzjaf.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2mjyldbbp.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2cyovxarl.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2zeffnpgw.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2vnqpvlbx.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2kywbdtau.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2lxbvfsoo.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2opscgtqu.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2ubdrsqut.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zljtjwcu.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2cusijnzq.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2fojhzeem.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2hxqsilfl.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2lcxqseok.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2gztfgmdi.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2neipqvnn.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2ongecgsi.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2yfkyqujw.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2aqkabhgx.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2ebsckyre.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2hpvcjjbj.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2pfckhpkn.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zdvfnwgv.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2drqnkjre.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2etegjzel.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2zcbyvjet.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2gsulcrxg.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2fnnuuwuz.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2zwkngeca.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2nzqyfcpx.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2hmyjkufm.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2rlpjfhep.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2lfuvkdsp.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2gnymnmtx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kaexchsr.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2tpwmiisv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kvejsrvi.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2jqzvxutn.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2vxmeqxwa.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pvsjckwd.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2ktwtobgl.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2yahaduzv.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2hsmbzezs.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2zjwpkjum.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2xfoodjkr.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2yflbnxdz.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2gbgpzune.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2cwfvlrww.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2iywmilmm.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2oiglozjn.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2trdrbned.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2szrtlhie.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2kayqaqie.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2yzydwgvj.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2tvosdobp.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2uwyscndk.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2hiwqnpua.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2aylqdtdb.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gtaccprx.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2kkpgxpqf.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2qxoagiom.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2hktkyxut.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qvpjwabm.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2embtwied.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2vixfjvyo.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2ceespgve.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2bsowhobo.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2bdwbcujb.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2rimdkfmb.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2kzauetwe.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2ogpzcoog.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2tedhrokv.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2zmkncvlv.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2rofmrfkr.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2rpskoclw.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2szqkvild.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2uzgseqhg.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2jhvtcsnr.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2grhjwbeb.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2pdnvqixq.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2esqwznbj.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2bcgrcjjo.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2yjtkqujv.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2kawwyqij.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2rqyovsxr.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2wivbhbgl.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2biuswqco.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2cndfapdp.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2nqsfufuv.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2pngqyljd.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2orfdssqv.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2vuridncs.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2reewnbwx.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2vayzlkej.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ttbvdtnp.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2bkqgyhaw.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2abxqafhs.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2vnsnloyx.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2fwvkemnw.html


<!-- 参考信息 -->