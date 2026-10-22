代发 wailian999

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2vhyctbdi.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2qwoakhsf.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2fbzdtsxv.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2tudjjgsj.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2vyypchsw.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2zcuwlosa.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2jzjyhuki.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2jsscpexb.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2mqflzosz.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2sssdnexa.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2bsqozkzm.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2nefcwqpv.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2crtlefrv.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ufmicrtk.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2jxmqmdbu.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2cuppiunr.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2saeuvmcu.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2wjjyusgd.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2carpsgen.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2xhlpzcgb.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2qqqzkkmg.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2yhemjtqt.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2svfkwotz.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2ijlnojpk.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2chwcpzlk.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2iibrwduj.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2jocusnzj.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2csfkxqce.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2anqbsonc.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2bmodxhvj.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2avwtsjor.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2bzsmjfxk.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2hediihpd.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2thleidjz.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2dafdxraa.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2igckjrgl.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2tgzzqkhe.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2mezcpccg.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2clwzeqhi.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2ijplsjia.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2denqfchn.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2utbzewfw.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2wrdczqrd.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2vbezkbte.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fyxlzodv.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2kzgeprxy.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2cwxfwgio.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2khknmghq.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2ecbahwdg.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2wkgaupvu.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ksfiefga.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2pfaxizcw.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2kwtbvlia.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2hpuqcsce.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2pxodycqq.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2qpqmgioq.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2vwjqwbvb.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2mpztojia.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2imtagwvu.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2cckhcmfc.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2ptsozebt.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ilswywxs.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2bhuygoft.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lplholxg.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2munabfmh.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zbxbovtj.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2cqzglsub.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qxnrfijw.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2idqtxydr.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2eqlklnka.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2bdljxhuk.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2mgfanoxh.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2bifvyzki.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2eqdzzsgg.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2qqkothsk.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2jcfgugqf.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2ymghuenz.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2bivokzjl.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2phhpmqvx.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ewcnwqkg.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2ycaxchti.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2rngwtmwh.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2imohuwue.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pzxmgmgp.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2nekjhpkk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2quunroll.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2ukorpptx.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2fwsuptku.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2tspyuwui.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2plxrthfp.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2jluiknbk.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2arwqvnvx.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2yezdxaod.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2lefwdywp.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2bmcnuydp.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2odrtlolb.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2btygebaq.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2tdjtrisd.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ckikqhcp.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xwzznqho.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2yzkscduv.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2iulyzejs.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2uxpsgpcl.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2hovgczuc.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2nykfmvbm.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ikpzybez.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2oarfskst.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2rfzcdnfk.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2ztqvjvjk.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2qefoazxl.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2dbeqosvn.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2maxhacbo.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2ofgbgkyp.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vafojiix.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2pybpzkje.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2spqpkzuj.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ucrybzye.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2byhoqfqp.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ecprxkkf.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2subxgkzj.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zvmffuee.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2znxuzcgw.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2dsbpzuoi.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2fspndxdo.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ohzdnqey.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2ttmjmajt.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2rssetvbg.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2mefmcegf.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2sdvprfqn.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2kaqnywjd.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rigzsuaz.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2dngwtzsr.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2gjisthvo.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2ttbjmwgq.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2bhpeeqdj.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2bnwhrzhr.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2uezzplll.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2zqqwfsse.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ffceppqq.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2piwkxxti.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2llgzztot.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ybtsnigf.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2ofgwwoct.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2qhhxjgbe.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2vcgdexaf.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2khuweoju.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2nttrkmxn.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vlqqccpu.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2lkeosbsz.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2doslngtq.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2alngqaju.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ulgemsih.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ugoryrtg.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2atyoiuda.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2flsofpsd.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2oojuspzq.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2vywgurst.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2azeoieli.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2fqmwfhhn.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2vrjqejgu.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2xghdmkvh.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2sxxoomos.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2jxbaspxe.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zxfydrcj.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2juhromba.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2cmijtzmg.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2qwyavskd.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2hpplnbee.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2fhqxjokr.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2bhcjynwk.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2mzvgyloh.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2ftyhtuzu.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2nzodadcr.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2idfltqfv.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hdncjkmg.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kmlizoan.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2xsxnadnf.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2jmqmzrdz.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2sxpbybcd.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2uoazulpw.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2sdrvoyni.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2svwkzydn.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2ltqcoroj.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ebwaymbi.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2pzzpuvik.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2mwilukps.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2kriuhcvb.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2aidypipw.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2kskthyxa.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ndayxiaa.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mslvygnf.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2lcmyuiac.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2qswepmwq.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2mjcjifbv.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jezkqloo.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2vuytdzey.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2gyievhyn.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mrefstqm.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ihvhsiow.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2pwuiitop.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2emfjrghk.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2hfletdio.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2ghgvxxoh.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2lbimomjl.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2biiybyyc.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yixznbjq.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2ifiqkmas.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2bbxsjswn.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2jwiadihk.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2dfyvlwna.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2ioaajcev.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2zqkulnqs.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2snlxscmn.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mfnulywo.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2imgaorki.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2jitrogms.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2nncpdiue.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2yupcrlwc.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2zmtvcrgo.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2rtslubar.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2amafppep.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2yhyexvsn.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2ffaypkmf.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2awnxnnid.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2ajjczaig.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2bohbzmyz.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2dcexejtf.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2ejvcehaw.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2sswbxnah.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2dddndiqw.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2jzqsouxm.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2jtovhsih.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2rkxdnlhw.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2rspoodci.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jzfmskvv.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2cwzailgq.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2jtzbvxzd.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2uxmiivfj.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2lkwatbgt.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ucbjfldf.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2yvdiaczo.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wwbzlund.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2drnantaf.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2jvvoyafs.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2akofyoxi.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2cbgxnpqr.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2aetbkdfd.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2qnggcogr.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xgqmenja.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2agrjlzhk.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2mjvgupvy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2stgjpakr.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2pnvkvdfy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ouljfxid.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2uhahlbok.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2yvmafqus.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ictwkoac.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2ktqrhdvx.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2carxpogd.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2ttabpbsd.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2xskvfkcz.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2vgftodwv.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2irzfrsml.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2knuqjwda.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2almicwja.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2bkdrpadi.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2rkueuejh.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2kayzznaz.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2ozgirfkv.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2nrayhpiz.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2sfznwsuk.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2crrrmqbq.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2anhzgauv.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2bvtgtidq.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2mzlqwwmy.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2izatqfru.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2bcvxwrrr.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2jdtuglop.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2zwchhxws.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ojojhgup.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2qmbwjvqu.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2musqfroq.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2alaicrzo.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2atcnqwql.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2hhmmekzk.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2vlcjpvzo.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2nhgyzrel.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2syxmskby.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2txcwzltu.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ieyaeexl.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2ybkzwzdk.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2hufonoee.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2ydcfsgvj.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2fwthgyjy.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2dfqropgk.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2hkkvtcfe.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2vutvrrty.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2vibzeihm.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2ghreegki.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2qjwnawbx.html


<!-- 参考信息 -->