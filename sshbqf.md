代发 wailian999

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tvewakmb.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2yhncgfua.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2faigkine.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2iwlgwdhb.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2wiyydmgr.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2mfbliifc.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2ubkkpxfi.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2aqvgluva.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2ufxrcbrz.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2lcrdukqw.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2ynridpfe.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2rtcdriyi.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2llrkgvfk.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2oukogfwl.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2doarrppt.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2nndrjauq.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2toxnbxci.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2muvenhly.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ypcudiqx.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2pmaqlqnw.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2kkjtmfgy.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2ygzsnmkp.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2ncdgexyj.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2catjoynp.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2vmmloelk.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2zdfvsnsq.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2escswdfg.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2uzoxacpq.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hholnqgr.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2slfrpwhc.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2ivttewlb.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2yrtlkzua.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yigsqndn.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2lfhrqqgr.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2tsnxfcwg.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2vgfpzcpa.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2mxirlnow.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2zdnnrzck.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2zutiobgd.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2namekbmb.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2yvadadzt.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2rdkrhqyr.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2xkntscbc.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2ynpxvevg.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2qdozmrvd.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2vnadrmub.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2dshjbeee.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2qchfxqtd.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2izeuinxg.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2udbgnuqn.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2clxdspnn.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yjdjjpjx.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2pcpmtlyt.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vbphfewo.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2qeepfznv.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nzlesuqf.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2xktiwnac.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lighrqpd.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2ibipintu.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2rvfbdgma.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2fyyrnise.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2aqmujwlf.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2drlptrbv.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2qmmlrgll.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2irtabwds.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2vzykyxlf.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hyabifqn.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2xhrojaci.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2enlnvanm.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2duvcalah.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2eyxjpgsw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bmtpcnhu.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2gcaqkzql.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ebdoegjg.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2hukiwdhy.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2dxbkrztk.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2uzuaniro.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2ftnokbhf.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2whdwtylw.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dkxspggc.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2bbrgvclm.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2sahyyqwv.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2yjlqczvv.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2ibbzydpf.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2bzzvwowt.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2mxekmlkx.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qtwuevfy.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yxgyfhjz.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2nmpcidvl.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2qsvvkiqx.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2rbqrjcjn.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2srfcecuk.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2lgffpfra.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2aaorcnbg.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2rmmbwbci.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2pvjuzkmp.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2uyxnkpzi.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2yfhqwrcs.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2wxduxzfq.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2avfawkrp.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2eliqgumr.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gpzwryfh.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2tjcpdtjb.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2yhufuhwt.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2kbwcirkc.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2uxfhmwde.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2yexqcrsh.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2efpnvxbb.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vaxazluv.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2czkvjddk.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vrpvfvaq.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2icbfuzin.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2kdmhxwwx.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2pobuiqpi.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qbbwcktx.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2tibqesag.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ocxqqfnp.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2qlpzuwbc.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zwmbgqdg.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2rocfsbmu.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2blsfshmk.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2lccgagmf.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2fcjtxbdz.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2uuhknloj.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ychpvuhz.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2vpcsfyxf.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2dknifwfn.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2zjvteryd.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2alesuult.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2htjxppph.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2pxkesleb.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2pjjhilfr.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2pyhkgzni.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2oibgylfo.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2psnusmki.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2poixyddf.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2giobwaio.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2itdfgjiu.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2jnpuhphr.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mwyddsoz.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gsbxdjoq.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2anrzyyxl.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sxmzgygo.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2hnogfkhh.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2njgxekom.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2amzedwcq.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2ohhsykof.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2faxpiokt.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2tgqjjatw.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2kulknlul.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2gzwzljmv.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ahysmxlw.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ievdnxmd.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2zeasfdod.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2eupnrgut.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2xvwerbaa.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2vhrcdkug.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2bmydqini.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2iocwanxg.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2esjvemod.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2lrrupgmm.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2ndabjmgz.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2onrydmjp.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2naktqkjc.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2cpmjwrly.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2eqommubo.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2zoqpduit.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2ijhbxqvt.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2ustcrytm.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2iyuxrihc.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2pbybrhpj.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ebqigbdc.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xhslnyjq.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2viauzael.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2adfdjqaw.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2oozltxlz.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2bpapxfmy.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2udfxtfxl.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2rstufkkx.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2fwnhnbkp.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2idimtfjf.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2relzjskq.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ttrcqvrh.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2twcopthj.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2xwlujprz.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2azmddmgf.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2yfekivhy.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2afnrhqgc.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2iuubcjrk.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2cycpljva.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2gzwdlcgr.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2rcoinjys.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2ixxypxcx.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2arqkcoet.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2fmowmfvh.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2itvpetlc.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2zlxjrcfh.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2rpyfwzpk.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2bztwxrxr.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2zxksvrry.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2mpmwjegu.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cxcspqhv.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2axyjvlbo.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2eydbelvh.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2zuxvaggy.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2cozmsqct.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2xvbwpvmp.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2tqmtdnyl.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2vqxvuyum.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2tbzmgrif.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2logpldtj.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2sgfdwfvi.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2cmbusylm.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2kvhdvqzy.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2yekfnpbr.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2egilkcuw.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2aekrwrqk.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2nctcfxkh.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2nzkotysv.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2bycozrwk.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2edmdmkqn.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2jppldtwt.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2aibebxau.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ssexades.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2mrbmaudp.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2efxqoerq.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jvponaqh.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hpspjfet.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2zrimwhth.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uzcrzgan.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2jpihoflo.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2pbfwwucz.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2tuqmhsgq.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2ivahficx.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ctjzblqv.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2vddgwuon.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ojscioff.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2fkvnupcf.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2sjyvnnhj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ecrihdgi.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2jxgxbjtz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2iezirdyb.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2dagpkuva.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2zgjfxvxd.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jtuepbdt.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2kvnhzbyr.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2mkvmgniy.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2orenzngz.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2llwmvwhz.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2lntpihbb.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2zifrfmzo.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2kvbdhcmi.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2dcncpdyt.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2srcbwjcc.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2xoghzyju.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2xdylcgsu.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2vbjxpzrd.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2gbtkoojv.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2vslhtqzh.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2rmigsvkf.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2phqpkjid.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2dnbstvzx.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2obwbjvkk.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tztwkqrl.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2fmuhbfax.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2qxzqfozz.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2qqhktcga.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kmngxajk.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2bmwpmlly.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2flpckpoi.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2ugcukeda.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2lqweoayo.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2kizejubo.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2vnqvotit.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2fhxaigcr.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2rrfedqwl.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2asggtwxb.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2gfucohdc.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2arolasaa.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2fdmtqony.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2hiuijvsu.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2bcwgcqhq.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2noogztmx.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2ygqoywea.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2mbmwcqah.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2syqnofzp.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2kvnxwwqn.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2wnktttnb.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2jyecoefc.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2mkucszpc.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2swffmcen.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2pepdcdaw.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2xwmgzadr.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2wwvqnnzc.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2rdpajkyf.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2ltrpuoqb.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2afehaozx.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2xqudxalx.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2hdrusswv.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2oumowapu.html


<!-- 参考信息 -->