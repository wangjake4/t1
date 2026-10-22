代发 wailian999

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2rautqfej.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2hskwfcuw.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2brsivdci.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2irlvdjgh.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2pedrvvrg.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2cvzribkx.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2wvoethas.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2pnvupihk.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2aektwwhz.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2qohnindp.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2fowcnwuw.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2ooqrpmgr.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2fqaygzub.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2cyvxroxr.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2urfiyygw.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2qctriqsw.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2eouinvtd.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2drhohlpb.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2hzezxngr.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2aqvrjalc.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2pbmbojmb.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2ppstakei.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2zuictnnf.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2yxpzotdt.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ebknztkz.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2bffnahaq.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2mgvrntvf.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2fatmwnjj.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2wknwjdvu.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2ahihbcgx.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2utsfjiuk.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2neailyyx.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2saniryiy.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2bcadueyg.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2ikronhxk.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2hnrxzbky.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ukgifjjj.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2mlpkhnlc.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2tjiuaave.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2owtmzbfw.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fefddecz.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2pmljskae.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2xnvdqbey.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2tacmljpx.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2seqgunta.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2nyadwzjq.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2eqlulnko.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2enzokwyt.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2stfbbved.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2fmvyipgw.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2kvjjupqb.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2mijbmrnb.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2gcwqsrec.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2nubkuqqv.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2kmsysdgd.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2dxafxqjs.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2aamhkvrs.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zkwoaadq.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ufxysumo.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2extcpicr.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2cccahzdv.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2sjvkkfxq.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2txdlorjf.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2esqclhmv.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2icbkqobu.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zzrcuouw.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2qjkbxxvv.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2impsotzh.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2owopopiw.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2uksjiogn.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2yilktedc.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2uvmcfhet.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2acmbntkr.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2nypfhjyp.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ljqfjfjo.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2xjskgjwi.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2lkdesmyd.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2baqwtpsf.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2jiwxbzlr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2suvllmgq.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2vxusnfcx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qlsczkzq.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2rtlwzhax.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2nbyapzym.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2sjyfkmas.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2cvxovoqr.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2qwjcwuig.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qdwdwyud.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2fddjkrnn.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2iyosychd.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2rubzuuco.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2jmikrrnx.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qxbblsof.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2gncmccgp.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ebbklwuc.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uammxkos.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2hmrcdcms.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2dcsfwulu.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2bfdzklyr.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2akxkwpft.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2xhblqkfr.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2nsyrsdaw.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2frnxqvjf.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2asymfrxp.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2drdrrapo.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2humztcnl.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2viejlyvv.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2nwfhczmh.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2rqctyosw.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ykwckbcp.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2sfgyrhep.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2gponrtvj.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2yvijlvdj.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2vmqyatid.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ssctjqip.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2urnwmuim.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tilknupv.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ouygyuqo.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2evrlkxbz.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2emkfqmkh.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hruqtouw.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2tzgtxrxq.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qtjuegto.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2olvleqen.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2cibvvknc.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2njarsbpn.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2divenoeh.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2zsmdtqwq.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2tsjdyfij.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2ofnwsxtd.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2emlgtefi.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ltudefis.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ismkvxcb.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2poayvnnk.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mwhhfipx.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2izmgpman.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2bbziqszy.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2yqxhqilb.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2wjksflxc.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2vofvisby.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2ivjahtzd.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2pbslhfkl.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2gptoomve.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qqixfklk.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2nczokqqx.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2paaqdevv.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2wolsvxod.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2birztptg.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rmoozmqc.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2egcnyggh.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jpjnxjkc.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2wdvkhqju.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2nsoopzck.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2peovyovl.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2vhsofgbe.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2oehvqlvj.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2uyimamvo.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2gxwzsfij.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2zvxnfzzs.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2pyivvhco.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qwyphvjc.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2hhxbwiir.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2sbntbkgb.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2mpbftudj.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2rqusicng.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2bqtvlmfg.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2jyzvwoca.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2kadjbqcj.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2yklvpfqj.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2mfzggdlb.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zyihxqye.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bdhskjzq.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2apjahojy.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2aojwqfve.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2rpjqlhci.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2kgfjzcbr.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2oawfziod.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2almulmlt.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2qoryhiqz.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2evftyews.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2dzhkommw.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2oulzrxui.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2gwwemdus.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2lmdsltbv.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2ayayscpu.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2kknhcach.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2gyvscdcn.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2ceqracxl.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2slglkmkf.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2qhgxbsii.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ketuoxlv.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2lqlhqohr.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2htfdudcg.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nchonamj.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xcqwgqjc.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2jjmgnbht.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2tgiypxbb.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2kwjglwvd.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2ocgnzagx.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2cbqbdpbo.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2qlbonwhh.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fzupnaml.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2smypcylw.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2vemngfvj.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2pjzlhvxv.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2gqhvfejk.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2ylqdqutb.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2qnixzqzg.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2jygoqpux.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ojelgqjx.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2ncyedhcj.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2lirvhqxi.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2niyxmxiv.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2iqzponwe.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2agdawsva.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2ghwidsxo.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2bvmehevl.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2kfujlpli.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2kochvkif.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2jpgxujvh.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2dhqezlas.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2ofeauyus.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2kglfxkqe.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2gjnethzr.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2cvaxvqkn.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2cibstijq.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2utvacsvj.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2poslgboj.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2rivopqhr.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2skmcicty.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ozdcjbyq.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ypnghwem.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2vvlvhlng.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2rcsqotua.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2obcaiwxo.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rkxrbnmx.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2lmjikims.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jpeulpvj.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2ywkpyegh.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2rqccgjgq.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2ypqkdfxf.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2czoaxakj.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2uvamogix.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2ezlapqom.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2puxdnuwq.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2juyrwwnp.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2wqpjizhf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qraolyps.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2umylzgka.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rbvnoyrb.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ueuskvwg.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2bknqjqfq.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yddpasww.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2lzmxkzvm.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2aeczvftc.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2nzzqppbu.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2gitkvlsg.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2ccoddvrj.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2arezteno.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ikkcztdx.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ubeuhhoi.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2aavxswrv.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2agvwvxfn.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2aaoegmvz.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2twffpgzz.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2dkcclsoi.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2jwngulzu.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2ltbasves.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2uzaimwwv.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2igmkcddr.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2odjqfwpr.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2udymgwkk.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2loppawhn.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2vvzigkph.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2nblsrvgx.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ybxasatp.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2ryydvrdn.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2pswkaksv.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2zzbnleih.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ebglvhkv.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2hikdoloq.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2zlnqcgnk.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2yakqzwdx.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2pwntcdev.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2lhdzklfm.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2reholsea.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2yevfbuak.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ngqrhljp.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2zepytgwh.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2hzdtptka.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2yglthdwy.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2mhtzrlxw.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2nknqrnhk.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2cqplcdlr.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2bvlqnfvs.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2cohbyuet.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2lrgficcw.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2rieqikir.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2dznjsaur.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2grecmscr.html


<!-- 参考信息 -->