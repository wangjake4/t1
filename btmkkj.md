代发 wailian999

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2mbceibno.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2jcmbzvlc.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2gdjkqdit.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2bypafvev.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2lpighsjz.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2fzfornza.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ozsbpsbl.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2fufuhnqy.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2tantbpsh.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2kttzcjgm.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2hhefxnja.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2kcbksckp.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2xctuszkk.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2hngxecpv.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2iraujgme.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2vfagbwgz.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2wsjmynjl.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2rsvxeprs.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2hfquyklv.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2orxetfxd.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2yhbsozbu.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2befwdwvr.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2nhfzbdfe.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2muelotnn.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2kwtcfzyq.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2ubvhfloo.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2bhrwrvmv.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2gjhgelup.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2ztfekkkz.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2vsxlgdec.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2cukmhpwn.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2govcukir.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2xpibjnzc.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2rdvvtavl.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2lrnfrnoe.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2fwpvhezy.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ujknwked.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2aaonlhsy.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2kxpamvrw.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2aynbktae.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2hlqjikbe.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2gotzsgmo.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2azgzmaaw.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2qhywnhcc.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2lccfrdxh.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2vhcsxkxa.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2ifwnlfgg.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2punblyyb.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2hzrtduvl.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2lldopaek.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2sdficngj.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2uhqcepsc.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2icyzzvza.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2qpobxong.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2wilnxumf.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2etsrhmxn.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2ogmjelar.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2jkmlvuoe.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2jtsnczyr.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2yrbcfhnj.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wsfwbjko.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2uagycpto.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2lowhufxd.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2gioinrnt.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2astrkvup.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2maxhxnka.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2nvcwapsu.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2zbmllhzz.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2osnchlmy.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2fekhojwg.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2xxdzsevx.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ggonamko.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2fnmbsdrp.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2loajhvcp.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2rnzunegj.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2gkmgdkuo.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2gqrornpq.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2oqelgdjn.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2txitlsdj.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2azayrrcb.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2hxlpndje.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2iqhqzvbw.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2xdcpqffl.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2qtqggjvq.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2txatgqjz.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dvfguqtt.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2cxtnlpxm.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xadqrdbg.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2gfzjjsnm.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2thkgjykv.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2cykcrbor.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nxtdhydf.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2baqgdkhn.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nmsjjsfq.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2fbxrqmty.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2asnaaimq.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2fskwmath.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2qpyjrfpg.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2birrwuax.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2exuuvpfw.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2hsrrkdss.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2hyvtbuto.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2katnaixq.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2fagouufy.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2irtncgpo.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2hefrffjh.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2dbcyotyd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fgjlmevt.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2tqsithvc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2stxdqzma.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2iashuvgf.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2zbcsgejm.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2ftzetvyk.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2aefvkpes.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2umpioczy.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ipqtppaz.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2lndebbrw.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2xqidgxww.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2rbykaswx.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2blldhflj.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2fvemyqhg.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2vgwrenrr.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dgwlbppb.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bsjzktbh.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ppagtqua.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2iozkmzyz.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2dlvxgvkp.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2zknglpiz.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2uyrycxkh.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2djkmjszi.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2stcqsito.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2dlqqnzcl.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2rlocwftw.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2vaepwkfo.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2vesivlwf.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ngewopki.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2ehxxzlpq.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rkutlcjs.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2aujfiinm.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2pwyiwalu.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vshjyggj.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2ooxbcnau.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2zwhfarlp.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kcifyqjt.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2cfiuibvf.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2gozantbe.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mltzstmy.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2bzviaeyn.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hfbafxmw.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2rdrcqkve.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2cmssavrm.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2yqszcgqc.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2eialhzcj.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2upejpdsq.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lpjmumlp.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2lkikorqw.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2sjurrlwk.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2avzfegli.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2yjdvbatu.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2rfeannzc.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2wkdrzveu.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2nwehxufx.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qnnvsqrs.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2czvdxhdz.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2uknutlek.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2odbehgbk.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2uyurenet.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2yjnvmrmz.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2bcispcal.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2rlueqakm.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2vnxontxv.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zifeorsg.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2mfghqtvm.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2bevsclfr.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2wlnpqbdh.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2bpvwwzim.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aibvglhz.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2efnzhwbl.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wnzidwye.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2wbopkahx.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2xsfdnrmg.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2ysvvbdxu.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2vktuvzgu.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2ipdkayhd.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2fnxlbzqp.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2bevqjbtq.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2bngkrooh.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2cftoldiu.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rmcbqdai.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2dnsunytr.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2ocxdehxl.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2spuzhvsy.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2pamqtqza.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2qkbvaomr.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2vzubanfc.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2dwzrvifq.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2wzqfgfdl.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2wxnhkuuj.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tykcjwpz.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nvxlwgvj.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2eiwqzcon.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2jdhijfzk.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2syafvpzk.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2hfimtbyr.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2aakondwj.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2lnzdqjfy.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2zzsvfgea.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2tmguwatv.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ewrhmcly.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2jegcyiln.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2rwivskoh.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ffvxjonw.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2tydvojdx.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2qqbtlehz.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qwzlkqee.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2lhubiokf.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2jmiyolpz.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2pmhvanxj.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wgqipqlp.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2bpjycajd.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2etlffqhj.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vcuiwzpb.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2denshijk.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2hkvvzaxs.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2quzictdy.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2hjbxkqun.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2idgcevdx.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2rlfrxhmt.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2mnwarwxj.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vbckaism.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2nwjlzuwx.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2zkvoearn.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2zyokuvkl.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2zzgoezoh.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2aeufpwjm.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2ugxxtfqb.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2kpkrmluq.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hfrhfsxf.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2cczsfywy.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2xpvipuwy.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2omjsgbkh.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2tyyihiko.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2ptjsndoq.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2yhmttfmq.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2dqvtyfnj.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2hqwsmjcd.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2bhnabpow.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2rbqwbtnx.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2gyxfzxqs.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2jthzjzyb.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zfpgepns.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2pivolocx.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2ckzkgzdm.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2expaqmdi.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2mtslfjif.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2wfukqcts.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2jjvfymoy.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2klnoltnl.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2svzillua.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ttmxbfsx.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2ytahffyd.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2pxuqkslr.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qqtrkluq.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2sysubaxl.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2lawnmcha.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cgfzubed.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2lqisxlzw.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2brrhabyy.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2mrnlwdox.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2uypchpit.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2emlshdio.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2hohokkkr.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2zfxhvhfr.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2yuztvzfz.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2eixvtlhr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fvpvkvis.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2rieqgeze.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ikeaebak.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2pljqyjmj.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2slzlelst.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ymxfpbup.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2wyxgpcff.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2qkhfyjzw.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2zztadjwh.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2onhjksmr.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2hgfagiac.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2ihdgrdms.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2teyloxps.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2wmdasuty.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2peflbobt.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2lfrosyva.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2evhpzhdq.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2lbpgejcx.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2mjzkncvo.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2yypxrfya.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2fzrrdefd.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2cdkeeyvx.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2cyyjqrsv.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2uwnfazmy.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2txmsrdmx.html


<!-- 参考信息 -->