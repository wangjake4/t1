代发 wailian999

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2blmfijlu.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2xflrcgnx.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2cddzsocg.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2yromanjb.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2yddsxlpz.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2kdqrhhhe.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2ddzmagci.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2bpoyflmv.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2dmqnoyse.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2kskmvqit.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2evecwnyp.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2ynfqpkkz.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2duzqobqp.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2bjtvcvgs.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2oalimovp.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2eptljxmk.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2kcirgsvg.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2wdexgalo.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2fuvzapyi.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2inszuhfb.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2wnjkwlag.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ypkyuaoj.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2kecovqqb.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2mzwxsqik.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2otsbbzvk.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2hrlkatxw.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2xcagmkrs.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2nucfkdod.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2suysvwgw.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2zkhskmog.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2slszmulm.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2chhbsgwv.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2vasokfeq.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2nzdlrqep.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2lxwigpcw.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2rciewglq.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2kkfcowwt.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2trysxyvj.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2riohlzmu.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2rwgopmsa.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lgimsgpz.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2yomnnppq.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2abgznjmk.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2palpzcgk.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cyhmzjtv.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2bzbzllkj.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2mffyxmrv.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2rzraubnn.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2gfwnrsma.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2adbhergj.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ypbstuwd.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2vrnzuklb.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2yovywflb.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2ivwjfiwh.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2ievxhvua.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2cavutjxj.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2jwdtwuud.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2vlkfzfcm.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2slcxspak.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2zkoomjnl.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2cmsukjku.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nlbxjfgn.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2jiltifvh.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rhxmnmcn.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2lgetcfge.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xcmqewdc.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2nuzjpujd.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2opaahpqx.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2eexidsyy.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qydtsocd.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2jjqgeuvv.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2xbnofuxi.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2ysakplqq.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2tyurssgq.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2woxrihzr.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2ztwfmcfu.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2ihfjdavh.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2yksnfipf.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kuaajonc.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2tngepiix.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2ggtmodgy.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2atyecixs.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2prasxlje.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2banqujpf.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2xakxxojt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zsfjkpir.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2ouozetrm.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2fwvkxvnj.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2ponjefav.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2qcoepyzv.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2mncspvhb.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2fajndbuf.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2emclciso.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2asjkrbjt.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2zykpcldi.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2hhfalvru.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wvxvqcgw.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2lnvnktue.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kekqpesx.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fsnqdyrv.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2jcgxjssm.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2gtdjnatx.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2lkipewbq.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ifzzlvvq.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2evujehdp.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2dzdrvndj.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2jeeeskah.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2gdbszqrp.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2ehwqykgl.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2gkqhojtf.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2gyqixqrh.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2pwjfulll.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2siumdtka.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kavhfkty.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2turqmuat.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2usczvvwj.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2amivcbfq.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2swdkjloh.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2oaxczphi.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cjqlugxr.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2uixzaqam.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2zjpwffkf.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2obhlthro.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2ulshfzuy.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wxlzkwli.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2nvkazxat.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2bhixysle.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2rojpbioj.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qgsevwei.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2fkxlbpyc.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2cveqtnle.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2nzjecokz.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mikanzqm.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2xcnnhcto.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2svsblkth.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2fdjyrily.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2dujutikt.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2bwpyyqrz.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2saosiwum.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2avgzfcnb.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zovbijry.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2zfgyxfmu.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2qpsjcsxm.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2ekemmwye.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2rpafenlg.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2omsrhbqs.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2hkcuzgzz.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ofnumqfa.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2smqmbtno.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2efrovupi.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2wfpjdjkm.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wkfaumfw.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pwawcivo.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2cetjtlpl.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gleezpwj.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2udqhzcpw.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2tsyqkrbi.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2smvnsati.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2pegkdugo.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2dxlseuet.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2mflpqzdy.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2dywedxby.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2wqqgfsvx.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dfgotxlh.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fdwzxjoh.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2rcgtlhhp.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2azlxtnpx.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2afwfrwfv.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2dqxzcsrx.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2vtbfkity.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2hwfupxso.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2cervlyqs.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2yjefwnru.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2nfnrzzdy.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xbtspmcj.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ekgvdvct.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2fjczgzvh.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2lxdogimi.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2dryjqwez.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2nmpgckim.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2nhalqflm.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2qvjoddfu.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2syjlljry.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2bolbkdon.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2yndbhtbl.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2omtdtlue.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qolbzmzi.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2etoirhne.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2yuacuprh.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2gflutyek.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jrwioago.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2holthoqg.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2keathkqa.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2ynxogmmu.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tqjnjpur.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2gsgihdsx.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2sctqaouj.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vibzjuzw.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vqkubnhu.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2hkvblxfo.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2jngfetsf.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2dvmvssey.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2mtxovymh.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2exppdlmk.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2wwhjbauf.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jvovtrts.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2uihisyrh.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2skletary.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2qoguqswm.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2muicvwex.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2fvipiukg.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2njaqipcb.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2vxspvzhc.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2borgmvex.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2dwpohbkm.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2fvmeivyw.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2erdvebqo.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2uxleqqqp.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2lcwrdtfz.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2pxjvkdum.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2abylovnp.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2jwiwyvmy.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2nfhssrft.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2ilnblpys.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2tstuokqi.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2httgbxvg.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2bbdaepot.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2itxelvqx.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2wrouuinz.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2bqjcoxok.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2hdoomuxa.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2iikczrih.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2hvmnbymd.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2gzkrpowc.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2basbmyys.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2qudzarju.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2jilknxoq.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2ltejjbqr.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mkmqwxpe.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vmwwdvlz.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2zhswzslf.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2iykkmyte.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2xwzirvtn.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2bmtqthwr.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2rpjspopq.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2zwbcihjx.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vuremdnf.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2aztfibwh.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2sfhngvkb.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2jybmleuz.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2porxxpee.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xkapbdmd.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2simixsrj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tqzzagro.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2zwzoqnxx.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2csfwthvd.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vsykqypm.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2scaettgb.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2wpwjscox.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2zlborkbq.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2peupfrfn.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2fwsxqygl.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2hxgklrsz.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ltqotqpd.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2uplpnufh.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ygsixcpp.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2xqrulkav.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2neqcfjdi.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2ovkbqlqg.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2qmlpevsc.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2idxsjaki.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2nrwjpgsx.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2dtqvdyzc.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2fuicmyfz.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2nunxwmgq.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jlwkazdo.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2mcpkpvfi.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2shrewfay.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2lrlzmwga.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wwucxela.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2dgagcqyh.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2drnnnbpt.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2lbtdhzmy.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ldegjdza.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2sktlbdbn.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2agxxseyr.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2yyhekfhi.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2psaiphpy.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2uzqqzgsv.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2dfrlkdao.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2fopalqxb.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2kggthlwj.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2sbyzkigv.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2qhhuadad.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2aafcabhn.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2cekyiazm.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2niweovhp.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2xvnmzepa.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2hzreyxhl.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2oimsownr.html


<!-- 参考信息 -->