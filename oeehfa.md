代发 wailian999

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2hwyzprjx.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2yfwqkwzm.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ibdeykik.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2lekduuiq.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2xkjjbguy.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2ipqvgiel.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2rqipnwqg.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2gnmqglmh.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2lwovchhc.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2junagyrj.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2eyvicysa.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2jkatwook.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rqbwlgod.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2wjudogsg.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2gijqaxhw.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2xunhrkxk.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2zcycvxad.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2teeukfes.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2zhnnxbgu.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2zcfoekbp.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2llupwqev.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2moczwuyk.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2xgexzjok.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2gbqyacgt.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2dxsehuom.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2idygwsez.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2wtsamztn.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2mioscghq.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2etqeysop.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2yefafwdj.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2xennseow.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2wsrqukgi.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2kwwaxnzs.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2lvjrtjzf.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2nqfjjtdn.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2yzgqjmhc.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2aesbywgo.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2qiwlbgdm.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2wkdtudei.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2rztqebwt.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hqulkgoj.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2dmuffydx.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2vxbraspj.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2bwfniiov.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wbdkxfxg.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2mkmwdmyi.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2gkrssvbd.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ctappfba.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2roldewgc.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2duuzvhjc.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2koauyiei.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2rtodvrxw.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2demysxvf.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2xsikzlsp.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2vcqrrghq.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2lmvtuqvf.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2ratbzorg.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2mwpgwtul.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2uqrapuks.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2plntarrr.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2rcteyesj.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lvoirtxm.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2rwjmvnoa.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2joeijpos.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2xtoxdqjf.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2iqgdsqre.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2icpibvcn.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jvcyikqg.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2nfzcrapu.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2duedccau.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2iimmqztx.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2pqpgoamu.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2zdaomdsa.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2dhrpkfok.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2xykdhfor.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2wbkyuhbz.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2vdkaypar.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2fmablero.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mfxkhzst.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2zdifouzl.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2vhpydhho.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2winatfev.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2rpbcaeak.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sxztdsjm.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2jhsjafmf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2upefiqcv.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2ckdwviky.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2yypqrcot.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2jnjsqynn.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2jdnxihsw.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2mowtciya.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vqpmcyag.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2dooqhiuw.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2vvcxxbph.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2ebtulecr.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2cohdeyma.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2pmznmhzp.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2bdujiizf.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sxvkrmaw.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vndgscgw.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2npqjfgdc.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2dpokjdfs.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ktskjcoz.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2leuaedoc.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2avwdfkjk.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2srqcwxeq.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2cobxhhhq.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2urfobfjx.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2tzzeprjb.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2cwmejsgt.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2qeteqipw.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2expqsyuw.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2hhexbfxd.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qjvncylf.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qfmqeihm.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2iunzlphx.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mxdlrtcq.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2xveensrz.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xtsgidai.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xwuatktt.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mrkhuukv.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2bkykaqjx.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hjmslxga.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2lpfutips.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hdrtnlsc.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2rqyxklcl.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2nprewpww.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2oofktegb.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2dwiycqbu.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2zgyccdbo.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jkeqkwfj.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2xjnzvekz.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ruuucfyn.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2esmhdnbn.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vrsuqema.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ayvwkxpv.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2wyytcinl.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2fpuxrmbz.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2uhcparmd.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2rzssgwoa.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2prypwjpi.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2prgblfaw.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2lslgzrfd.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2ddljdwxq.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2xkwmezzq.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2ucsroksb.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2ljvvosjm.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tranoinx.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2dxezmruv.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2uuciqher.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2fxashyau.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ucwijruy.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2izcecqom.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2zesbposl.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2azvaerpo.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2lqrmszxo.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2uwmljcoy.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2xindieuh.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2awgsnkzj.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2itskexmd.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2qjrbqljq.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2shozswio.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2ewhshchy.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2cvihohto.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2sszevyic.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2uavtkgtr.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2yaknzjzv.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2cbcnzcqd.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2hbnndvur.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2xkaflzig.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2fgtjqjii.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2lfseytwi.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2yehtlxgt.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2amgkntth.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2uejpmxmz.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rozjnawk.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2oqpkestu.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2xqrvzifh.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2znmcywkn.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2xyfixevx.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2khjujfdw.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2jhmvraru.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2fypuqxht.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2aunlyybe.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2bbyjbasn.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2polkucpj.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2obzqnxml.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ytsbyhio.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2ycnalivu.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2mkesmuqb.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hinkupub.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2dgawrjgm.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2pshbhoxy.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2kqhvguzo.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ycffafqs.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2mhvzjjzv.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2gejcsvfe.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nmnyxsix.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tgojtkdo.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2zrqkwkib.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2hhqnsqqt.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2qcpbhhlk.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2xidrgcoe.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2uwaqpryj.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2mwcnnyfh.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2iptwyikh.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2fmutvawt.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2jusaplrv.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2wbqpubqo.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2eygignjj.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2uxefkepl.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2iskfwpkj.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2rstngheh.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2medbksok.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2vmtwcbij.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2bdgrkzpn.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2gohmmnnj.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2eovznfrg.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2whbjgvgi.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2bhubplcy.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2tsrkyupa.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2ymlnpfog.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2zdxjoegr.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2ucvrynuo.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2jtyuibvg.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2jceqebel.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2dytzqrix.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2chcnvomj.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2ourtxkjs.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2junbbuxe.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2eqaijyrn.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2huwdgdsm.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2hcrfarwx.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2fxtpmnmg.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2rqrmbtaf.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2qprzhlwi.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2tzhbtshi.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2fjbguecp.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2uavkvsvi.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2fiomkqka.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2yrpwtnax.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2clrxgukf.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2cfpagbbb.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2cqpkblac.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2kaecekzc.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2ntpvzwco.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2bwklfjfs.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2fphdlqsx.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ilkokhsa.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2ctcmjsfz.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2dikdzqzz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pyxevmfj.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2tohaakdm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ddkopvet.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2teuhkcrm.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2wapvlwdr.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jvmzakgp.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2gfqjvnev.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2rsrnvebr.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2ndupfffd.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2utrlpkaz.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2ftusdgwb.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2mqxlwsvz.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2cndiucjm.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2cxsgawuu.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2zymkfheu.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2kbvwqnrk.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2vpsquqop.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2kpzxskid.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2yyscukxp.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2srxbhrrs.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2boiysbud.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2vugwvcri.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2hglkjvvv.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2moztszwd.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ciogiwwk.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2abhfewbx.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2keqrharg.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2fajiclhn.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vkfbuwfg.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2pjilezuv.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2zxbzfqci.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2tejkdbxv.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2qquuhusn.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2hvrqzegu.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2rscwkkdp.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2wkmypzyd.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2fjefeskd.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2xcmhmoxs.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2udgqurgc.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2zfvsmiru.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2zfnamcbl.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2lrjjrkca.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2gebbpyof.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2hquimrwx.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2vkpmlppi.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2gutnhqfe.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2jicjtfec.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2mrknmwgd.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2riqujmml.html


<!-- 参考信息 -->