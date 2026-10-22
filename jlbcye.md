代发 wailian999

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2kgseazjs.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ajmvwska.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2mscyqdlt.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2jiugloup.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2faxnwadw.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2eydtshdl.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2kteqxgxj.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2wuoytxmb.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2mauypdwe.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2kyjjxuld.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2kiridnlu.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2nmczehjx.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2krpcomug.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2gwmpqabw.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2uqtpfiyz.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ickvycex.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qzdzulli.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2xnyhgbsp.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2kahhkzvu.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2rkfljydm.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2msapfoyh.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2mrrnnawi.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2fspaoeqq.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2nqzcmizk.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fybycwmo.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2bachqogp.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2ynyoatxl.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2vzyfytgn.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2wyfjktud.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2dfflhktm.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2jzjgpthh.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2cvclbpqo.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2xkjifmqr.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2qrslmkqf.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2ogaxyujx.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2qiwojnas.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2skutsupm.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2yowomtup.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2msrqnrho.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2ewroecup.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2axodvrxd.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2sydpffnl.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2jsitdllv.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qcmnsqpu.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ndbdukuj.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rbnbzvjc.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2fjlpimoh.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gqwtxfns.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2byfljmba.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2euzunybi.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2mfctytbj.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2iikpyvdv.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2ipukchbq.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2hlnrtqwb.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2rmsrtmpu.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2ukllmsgh.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2jkhwedtw.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2wssrhslh.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bbjmsxhf.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2jfdnlanm.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2zuvbvocq.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2yfjsfcqs.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2gceumqib.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qxxshjns.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2tpbslejq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jkrfwden.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2kpgzrlxp.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2vvtkdptj.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2zuhvwmbm.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2zlvjlmqd.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2tgcgbvgl.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ficdqywv.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2tnjsbfff.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2sxczibkc.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2mztemcrz.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2hpyravkw.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vklkcjfq.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2pqmyvfza.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2seioymov.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pjdukmok.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2egwarepz.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2bbuhkjsq.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2qxzrupza.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2bahlbbpu.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ycwvqcyo.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2vrrvzoih.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2lylfombj.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2mddptwjw.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2qbacdies.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2pcibucsn.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2wtgcfgym.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2cfvghyww.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2ehtdbdwh.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tythinaa.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2nqxsokbi.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2jwbbagzy.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2odskbghd.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2atnqslxj.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2eizehgeh.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tbdhvnlp.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vlzbtqrd.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2boddqtgc.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ceamdvjw.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2hgwcjqvx.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hxlpvduy.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2pmmhaule.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2nyonqexj.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2kzftbpmk.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2uouqnden.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2llvfqsbf.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2avfgvgsb.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2unksxbxo.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ngmsgohf.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2yvalyupl.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2gnbabwji.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2iieyhkxr.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2euvpetoj.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2oxoxoaza.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ngwvmsdj.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2icgpprtv.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2bnzfqfyz.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2mukbjbpj.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2taipawfg.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2maiuiott.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2dbqtwtyh.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2pvdidvoz.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2gsauwjrh.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rjviyuei.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xqxfmxnx.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2jjpklrby.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2bajqlmyl.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2cnkbetjz.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2babwrwee.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2wnddvcbj.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2spualyjf.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2ypspaesz.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2ypacazyg.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2xdkmkati.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2zfcpmikg.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2ewggkhwa.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2jpmosvbq.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2zztiucot.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2cghxbwxc.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hwgaatrx.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fqwrzwvv.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2qmbmogec.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2rrdvczlw.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2uwsbvnqi.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2gpbimhoh.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2jorstifj.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2fpjlhonw.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2luyjunmk.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2dcrqkyta.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2jrmjbrll.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2pvmryfcn.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ywoywxvj.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2zvsnlelb.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2rwsivuqz.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2lmomugaf.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2xgyskplb.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2sawrfuta.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2obkwqthu.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2flfbnrnq.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2rpxaimwy.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fxxbjiop.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2jkuztmkm.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2pcaqqryx.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2kmaceiuf.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2ixxchysq.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2fwshimci.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2frtggxcr.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2xiuglkiy.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2tgssctne.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2evwuhqli.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2feiuobmj.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2hqmywsse.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2hnmcuavn.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lkadtrro.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vsubrpbv.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2zlrmmgvt.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2xyjjlbgg.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2jgkfixwj.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2zqgbtarw.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2hysbfijg.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2bzwophnf.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vpcwjjsh.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2uazglgwv.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2uxrowtyi.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2apqkalig.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2gpdnlepb.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2axntikga.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2mqelgybi.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2wiysxzuj.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qgmclscb.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2jwmlycip.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2mnhzyzpp.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2pvjymjyn.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2pytenryn.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2vuoinseh.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2pionipes.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2sswhkyku.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2vaybpizb.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2siqhttyz.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2oiduvkjz.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2clsdzsxh.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2xlvsiqsg.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fwlvxbbk.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2xkizaxsh.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2jmsrites.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2qlezjixg.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2gtyckgxq.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2jvastoci.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2sekhakij.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2oyugabox.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2gmewkwvu.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2uaxvmwid.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2mhmjsdsl.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2nphpdwie.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vgyejggn.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ekhzqqet.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2libhvqng.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rkgewkgd.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2pxoxpjpv.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2yhpkfpzv.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2tijvwywk.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2nsrbhgad.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2nhtkssrw.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2rhshhylc.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qsgyzfqw.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2sifxalhc.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2maopwext.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jkcaejme.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2cwvpxtfo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nmhmefgp.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2gabszzmv.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2nhhjyoif.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qchhptye.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2mwevnrzy.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2bbwuyuli.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2tphbtssy.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2toalahkj.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2ostikbxz.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2uhrhoiws.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ntjapoxw.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2sigzvxxa.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2frfoymch.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2jygabqmn.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2glpvltqa.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2irwjpqgy.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2agryjxqn.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2nwqcltir.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2ennukmjl.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2fqxbfvep.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2lpsodaxc.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2ukbnlrjb.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dplspily.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2pnqciypk.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2huzaygbu.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2poyzoucv.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2etzkzfzj.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2qnkuxjwu.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2mfkuylea.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2alerusvj.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2surrpgtt.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2sqkcapcs.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2kjfpwvmq.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2sgbyzjpx.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2vmnfzxee.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2abwzgoju.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2kkfismqw.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2polwxsbq.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2aslharyl.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2aemvujzy.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2napaarur.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2thfhczeq.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2pyfuxxho.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2jpilvcbp.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2dcbvoajb.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2boihxxac.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2yduwtisq.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2ftqbmgox.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2zvgqlrky.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2uwojglvq.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2nlvygrbv.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2xrvukmnq.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2minlgwnv.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2ukwxxylr.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2foqejglq.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2bwmegwps.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2jmwqsiox.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2rlbtfjwb.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rxqaemen.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2czamoxzm.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ojmnqbkv.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2nmulezqp.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2bugfwuwa.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2rhqunkpt.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2zlffvnfj.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2bufgzcrf.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2zsvvyfbp.html


<!-- 参考信息 -->