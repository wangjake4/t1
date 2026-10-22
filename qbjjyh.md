代发 wailian999

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2awmczuqu.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2obrxouec.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2mfibjsvt.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2bglhkeic.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2eenccmxd.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2cakenqjw.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2ugalayud.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2uenezxvb.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2arlnyorj.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2kupvbtre.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2osrlpusn.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2woddoohk.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2wjeyapax.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2vwpawxji.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2xbmtdjoq.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2sxqvshfr.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2pwirwnyo.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2ideqasxh.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2zhudezwl.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2rmhtndhw.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2bosfvwge.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2ozvmgujo.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2vdtdoyzt.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2cksljmap.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2rznqbkyn.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2jvzsolgv.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2dmoxnrwq.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2fpapifoo.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jsgtppuk.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2iyetywiz.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2ohttvqfl.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2siomgjae.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2grteodmn.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2dcxlioub.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2czogdikj.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2kfhdtnmc.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2bafasshv.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2jxvknbqy.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2rllqtckv.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2citfoaaw.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2ewdlyxwt.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2fcqlnaws.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2fdtoggwg.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2xhzbpbiw.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2nrtjlyap.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2nghvpzxh.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2khsakgyl.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2ryvmhorf.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2etykbkbw.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hcpvegum.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ekmnjdrf.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vzhgsfyt.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2fbqplkdm.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2owffphny.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2lccgwyrv.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vtgqfrzj.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2iunknfta.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rdmdndhl.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2nnnzqile.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2tytukxyi.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2alfobnvv.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2imhqwyxf.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2svkeutyk.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2tybsffde.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2ybphfiii.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2cspfxqjz.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kgljvocc.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ruilqosp.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2lrakemul.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2rrvplynl.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2opbpruvo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uowgmole.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2olknfrhb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xrdndqzt.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2kamjkuwd.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2vkpppfhy.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2znzaxftu.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2wiwfnqzq.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2cludxmit.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2teznaslu.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2douzrdfq.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2jczllbhx.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2yqiitowp.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2uwzqyctw.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mspubfns.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2zziatyvy.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hqpinmuo.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2iutjkqsl.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2opgehjkz.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2urizlnhi.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2tkzvvupu.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2lwocucvl.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2jbohayds.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2zxjvdfzh.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2eipxlpqq.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2suyuarvj.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2runsynqa.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2zbvjstsu.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2szleqrrg.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2qldmnodc.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2womlyqxw.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jizqalko.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jtbfjmku.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ifwdgqem.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2uvkcclej.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2mtbpxkhv.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ecmirrna.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dtdfnfuv.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fclqllht.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2dewcyxfm.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jtwookbu.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2orqouwjg.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2spronpsg.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2nzlvveye.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2cjonhcal.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2pcaosajh.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2gjnkpvqs.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2adivkfvx.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2parghbdv.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2knpocvlg.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2gyixzihy.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2bvpjgdeb.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ivwinlfr.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2kqwhrnmr.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ueaxhyeh.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2bexhratp.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zfxcfmot.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2cgijpmlk.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2drsqldec.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2rafiuahx.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2evohsqqd.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2ddaqrhfd.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2rxazaboq.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2spsapzit.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2igziduqn.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ipfkvjeh.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2kgdvvkvd.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2nrweuwcc.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2eznctqul.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wjxsxgvk.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vnqldapd.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2ukiimupc.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vmlbpgws.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2yfsoljyb.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2rlygtbwe.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2bwhqlmhi.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2esumcjti.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2janjsvvw.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2tmmyghjs.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2rzedtaos.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2emtjxfzc.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2gqmqpdjc.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2cnlsbrdh.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2qpofmfai.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2bwaoceek.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2lokwmrjg.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2rilmzfrd.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2dbxqsord.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2cfxvnhvi.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2rzfconfx.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2geeniyfi.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2lqupglrh.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2lcgltcvg.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rzxqkcuv.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2fighuxem.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2lmaogbna.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2koonutjo.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2hmfcfuuo.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2hultellk.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2zvufytzg.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2blpohqvk.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2yunrtusc.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vkdhqpxn.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2ixuaceew.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2bsybkffr.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2slnpxhcw.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2vyqnmjzr.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2fuyaqguc.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ndkiiuch.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2llrdnazg.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2kymfcgxn.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2errkpjfw.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vxxkychc.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2dulaibao.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2fdvjaedu.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lgcqjfkp.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2bdmkyssk.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2xyuxajxf.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2zebzqepn.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2knpjvkiu.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2nzdjuxzh.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2obetymxc.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2fyrjotil.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ypjiapbl.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2uhssntbr.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2rbaypdhh.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2xuphjmns.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2wkcphhmk.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2xxkouqdf.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2rgxxviir.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2ssfzhyyh.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2andevzcc.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2raqckxww.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2izbchmlo.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2ikeeanpy.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2zztyddfe.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2paogrgpa.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2cyllfapj.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2jwiurgjr.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2sodzglnl.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2vxftpyql.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2vqcpzjfw.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2azwyczme.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2ccuczbkx.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zrnymjgm.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2nxumwtbe.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2hcuwhywf.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2ndbtszfl.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2arkjocqj.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2xaoshbzw.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2jtbgwvis.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2sbkivwwe.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2zbiinudz.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2mowxhjiy.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2qkqxwqry.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2vanuknjy.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wzhfmbxl.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jiykzdfc.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2jcdrbjks.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2enzfskza.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2lhtkpaqc.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2qqpbcxzh.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2kokoeszn.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2njoltmjn.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2zuoecqnu.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2bepjedrv.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2kcgztjjr.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2rcrtfmat.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2irmepgln.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kqslxtcj.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2caqjvchi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jwynksct.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2nrsbktew.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2ifpuuzqn.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2koevuxtt.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2drotzeqa.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2iddsfccg.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2eaqdsgzy.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2clatgrrv.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2nrjchfuf.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2txiguahp.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2govjkrgq.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2qnpzasuv.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2jeafdvak.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2idndaajs.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2pisofydx.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2dykdsqye.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2xhaqffjt.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2ikgfurhj.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2snxesuvv.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2slvptruu.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2pbxucdxw.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2wlkxuhdu.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xpolsruu.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2vvgojaql.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2jcdggunu.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2twpiiosx.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2borsnsre.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2pjgeefuo.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2qgiwatma.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2fegknapl.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ocfktaoq.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2lbhoybxi.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2lmwznneq.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2qyfxycln.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2ldleuwwr.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2khagyjxq.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2zqfpiriu.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2lugglpzd.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ywehnmgg.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2anfyisez.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2kjnndxzp.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2vzserdfy.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2wchqjmxo.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2jqxfpaov.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2sbnfwjio.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2xpjzyppc.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2qdqhluqd.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2ezhxwclg.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2byyzaohe.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2fmlkqqht.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2mhujxnsr.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2dekpszml.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2cuealwms.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2jcubyuqy.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2zwsscblp.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2edygzttp.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2omeisxys.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2rkapfimv.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hnptdisn.html


<!-- 参考信息 -->