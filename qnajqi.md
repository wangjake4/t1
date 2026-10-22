代发 wailian999

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2lbdccndw.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2fomwqizm.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2ifqzsnla.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2wtvulbib.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2qdadhpzi.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2ktzhjyfl.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2oxyirrgp.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2smgotrlx.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2gwqgewtw.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2vcqwodbi.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2wmsjerqo.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2dffkkbre.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2pzsoycmi.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2kuffiqxx.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2cduyxfcm.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2zcfopveh.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2smkupmci.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2mqpnpqoz.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2lumayrcc.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2homwotqr.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2feomajzq.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2rdjoikxf.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2pnagxbpm.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2wksfdduk.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2nantitsx.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2wspyotuz.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2hrligife.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2tzsdfiwf.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2xeafmksx.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2rpynuzvg.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2rjnfqvux.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2bqiyjkjo.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2vooowvfy.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2vugdrtjo.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2jpxstqjo.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2integxfd.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2emmpeilo.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2xsnvxsfu.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2gdnentzl.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2qqcqghuf.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2muhwoxyf.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2pmdnaqvu.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2mzrwmcag.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2fycfccif.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ayvrlpui.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2rfvevhvr.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2nzfirbmo.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2whnekqbe.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jdjfieuv.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2duthvxno.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2mmaehxza.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2sgtjmxxh.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wlfimucc.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2ildylwnj.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2chrvchfu.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2kxwdkozh.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2ncpzenrk.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2mrplvdqo.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2zajlnsaf.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2iexujopn.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2zinutdfa.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2hebdiirs.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2mtbpmeru.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2wdlrkqou.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2bmefuvvf.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2gudxrubw.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2fqmhpclk.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2dogehwhm.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2xdjuzfpo.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2miefkbyd.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2pfxpydno.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ggexqldp.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2acawmudu.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rgiqjapa.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2vqptglnj.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2klhhrerq.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2pxlmizra.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gstobavd.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2ngzbnmnr.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2szkvvqie.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2fsupaiam.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2prahyvsp.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2lluizqju.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2lmshhryb.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2tulpcppc.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2yevbfqgs.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ewefhwqa.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2bgzevqcw.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2njipsxyk.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2rptxgkgh.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2slqdajqg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zrscusca.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2pdkawkvk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2whifkpkt.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2vseuyttz.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2xmanwpxp.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2inwzynlu.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2shcsnwgl.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2wmtcduuk.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ekykhtuu.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2pgzqmocd.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2edjcrnlv.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2ovvccxro.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2meblfxoj.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zmtpacyi.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2gulvlgnf.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ojkaddes.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2piesmczk.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2mdkonhwk.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ageedoqp.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2bamckwae.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2xuwjizyj.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2kybmvgcj.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2jwtwsaxh.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2nndxvewg.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2rzgydkib.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2usmtxpko.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2sjxjqabr.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2jaulqpji.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2pfvnfxgf.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2jusedppk.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ssidllll.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2pqutapia.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2xqbqehtf.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2eweixdsu.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2zsfjakfy.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wvsnoylj.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lkghgsta.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fbiugtca.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ejfpgjke.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2npwywxsy.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2yuztzjvk.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2skhweoer.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2fhjgvuko.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qibynenw.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2moylcyjt.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xwobctid.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2vapckbdb.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rpnfofwh.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ondyzxyk.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2eojknqem.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2lxerelfx.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2acrvnbye.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ixcabmnk.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2rzfsgxxf.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2lwqfclxj.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2nhldnuzt.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2zenvfjko.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2eveszqtr.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2hxuklopw.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2fmhgcjko.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2xodgprhp.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2ihcvzdle.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2oyrzrvvi.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2mrkolvrr.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zuvhlxcv.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2iejbxsaf.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2dnsavjrf.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2xhbaxypa.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vtftugyi.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2geahayrp.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2hmakxqyx.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rsybcrdv.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2gtxorsgl.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2wrhskimo.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2zatyigyz.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2dhjpujhj.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2ivhkvhfa.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2qtdasoys.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2szygdnvm.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2tedspmcz.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ochvhnds.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2yodrwdug.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2dquafzqj.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2qcukkxht.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2tywstfoh.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2gzbbjgir.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2wtpagsra.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2mwadjwii.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2nifnmoja.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2houqsmvg.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2hqykynaj.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ikqwavgw.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gffaaxhs.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2qcmbfcqd.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2xqtjsihu.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2uhnhthlw.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2aixkwgkv.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2ywagcoeb.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2enkockri.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2zvmoigfy.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ttdhaspt.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2kbkztnoo.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2vvmyjebb.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2rqjraehr.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ewnpycep.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2dqbacmzt.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2nnqrqsvu.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xvvlbqoa.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2tgtqrqop.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2cuunmfhb.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2vwaselgw.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2bnwwgwzy.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2vfvzdhii.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2ugohulvu.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fnewjowz.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xzfoehoy.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2lvlxqvyx.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2fsyyhjob.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2xflonogf.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2qvfcykam.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2qsjlkynq.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2lpwtpbuf.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2djjakfpj.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2dtfvizlb.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2xmadnmcb.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2rrexxoen.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2srvimtwd.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2wihvexmh.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2aueznvpi.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2fgyxclck.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yxxtwquo.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2jgjxlyei.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2gygfwfaw.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2idiryjyx.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2ppllfurc.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2psnmnrbb.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2utjfafgh.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2yqhvelxr.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2odtqxnxk.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2xgyehykv.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2vrtptuqe.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2vmhzjgrp.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2fwujagwu.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2emaslkec.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2fpadhnrl.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2lawbzhuv.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2iagmsqyl.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2olluenha.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2xxboqakp.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2agfvvmdv.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2myektavj.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2njcdatec.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2rzyrzgof.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2vyibubnr.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2oowkammw.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wcbfoosv.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2txhfaozd.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2nmxwspnc.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2effyxdvi.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2vstrbvpy.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2mnvlyoia.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2bylkokjn.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2cmuoenvf.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2glltzxif.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2dksnagcu.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2lxvshqhj.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2jfimfsxa.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2tqlyypka.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gxksufpg.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2fzisrizf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2umbsbgvw.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2cspkpcfe.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2kacvywjc.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qlayhbkp.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2msubeykz.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2juhzugtr.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2nexkjhdq.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2vglnjwpf.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2ncdrmyww.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2kjsefurv.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2xfenbhqj.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2htrsuvrv.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2qwcgljsw.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2lvrxdcdq.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ywaxgige.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2oofoqbtr.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2nzkyamsw.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2hyubiwez.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2drzgqyvs.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2iveawknt.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2bwmugvep.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2crvqjmvw.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2awbsunjj.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2mfduaybb.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2rqialryw.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2aowgwbgl.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jsprwund.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2rjcnvqlc.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2ssvikwsh.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2rxcdtpql.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2bxpoonsi.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2lcceoosj.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2dxvpcqvx.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2poaqkewn.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2ipclplfk.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2wuisndzu.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2qugkzsyr.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2mjsauxoz.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ggqpkgmo.html


<!-- 参考信息 -->