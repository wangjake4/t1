代发 wailian999

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.cdnleiting.top/Article/details/gtfcrdozim.html

[Q28] 求和与平均
来源：http://dali.c1oappe.top/Article/details/gtanrsbffi.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.meibo888.top/Article/details/gtogggglzf.html

[Q29] 最大最小值
来源：http://dali.yj202588.top/Article/details/gtrtuzbrmq.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.daxiang520.top/Article/details/gterfyylje.html

[Q30] 分组统计
来源：http://dali.sufxvd.cn/Article/details/gtoweyqnxt.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.guowangkeji.top/Article/details/gtzkoegakd.html

[Q31] 分组后过滤
来源：http://dali.tian-w.cn/Article/details/gtejfngwmq.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.svipenyu.cn/Article/details/gtcdmcxugy.html

[Q32] 分组拼接字符串
来源：http://dali.hnxiangtu.top/Article/details/gtflqybvsr.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.xylfe.cn/Article/details/gtawneszto.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.redwolf501.top/Article/details/gtffcavicw.html

[Q33] 多列分组
来源：http://dali.jqgufenzy.top/Article/details/gtcatnbxks.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.andypj.xyz/Article/details/gthyzksgcu.html

[Q34] 每组取第一条
来源：http://dali.smart0.xyz/Article/details/gtrzxqobod.html

SELECT * FROM (
来源：http://dali.nanxinkj.top/Article/details/gtllutsdql.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.shanyushiyangtech.top/Article/details/gttcbkiosp.html

) t WHERE rn = 1;
来源：http://dali.yj20258.top/Article/details/gtejxiutjy.html

[Q35] 内连接
来源：http://dali.pengpengdd.cyou/Article/details/gtzoflidok.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.fzhhl.top/Article/details/gtkfetflro.html

[Q36] 左连接
来源：http://dali.yj20258.top/Article/details/gtcmhkjocp.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.guowangkeji.top/Article/details/gtgyxekalr.html

[Q37] 右连接
来源：http://dali.feifeiyinyue.top/Article/details/gtreyyhckh.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.chenlongwang.top/Article/details/gtffvkkswa.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.yueranfly.top/Article/details/gtdvnzbhhr.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.jqgfzy.top/Article/details/gtqtjiwvyi.html

[Q39] 自连接（查上下级）
来源：http://dali.zhoulong.xyz/Article/details/gtnbdvldfc.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.nanxuanxn.top/Article/details/gtocfkgzby.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.mhx1999.top/Article/details/gtijqkybrz.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.hammf.cn/Article/details/gtsxvbnrzk.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.hfpthk.cn/Article/details/gtvgyedkqc.html

[Q41] 多表连接
来源：http://dali.jinqigufen.top/Article/details/gtkbinbzmd.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.yj20258888.top/Article/details/gtsklmovit.html

JOIN users u ON u.id = o.user_id
来源：http://dali.chenjidiqi.icu/Article/details/gtatxnjles.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.svipenyu.cn/Article/details/gtjnixtfqe.html

[Q42] 连接条件附加过滤
来源：http://dali.jyoumei.cn/Article/details/gtsyhopwwe.html

SELECT u.name, o.amount FROM users u
来源：http://dali.0kj1m.cn/Article/details/gtyerfkteo.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.cucudq.cn/Article/details/gtwpokhcbf.html

[Q43] 标量子查询
来源：http://dali.andypj.xyz/Article/details/gtfvlwdmwn.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gtlqdvihhl.html

[Q44] IN 子查询
来源：http://dali.yanxiufei.cn/Article/details/gtyfclzgvr.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.shanyushiyangtech.top/Article/details/gtniwpspvz.html

[Q45] EXISTS 判断存在
来源：http://dali.zycfv.cn/Article/details/gtodrwfpxy.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.svipenyu.cn/Article/details/gtgejelarc.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.fzhhl.top/Article/details/gtttjjvupv.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.redwolf501.top/Article/details/gtemcgjrcv.html

[Q47] 与平均值比较
来源：http://dali.gaohongyu789.top/Article/details/gtrrtsqrzf.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.birdmap.top/Article/details/gtaojavfqu.html

[Q48] CTE 公用表表达式
来源：http://dali.zhengqikj.top/Article/details/gtyawdhxvi.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.cqqwz.cn/Article/details/gtdlfvwvur.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.hongshengwenyu.top/Article/details/gtqopywfdq.html

[Q49] 更新单行
来源：http://dali.hnqzz.top/Article/details/gtgjjkbafu.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.birdmap.top/Article/details/gtegrxiodz.html

[Q50] 批量更新
来源：http://dali.9152youxi.cn/Article/details/gttlfnrvux.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.daria6918.cn/Article/details/gtdpdbrllj.html

[Q51] 用子查询更新
来源：http://dali.guannengcc.top/Article/details/gtakrzolnx.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.gotoacloud.top/Article/details/gtlpeeuitf.html

[Q52] 删除指定行
来源：http://dali.yuxming.cn/Article/details/gtbdnwokdq.html

DELETE FROM users WHERE id = 10;
来源：http://dali.nwbrower.top/Article/details/gtvvbtmdun.html

[Q53] 按条件删除
来源：http://dali.jqgufenzy.top/Article/details/gtrjbrbtoh.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.xziqi.cn/Article/details/gtawouwxss.html

[Q54] 清空表
来源：http://dali.cdnleiting.top/Article/details/gtqmkrhpgt.html

TRUNCATE TABLE logs;
来源：http://dali.zhongyouzk.top/Article/details/gtjfaewbbk.html

[Q55] 排名（并列占位）
来源：http://dali.hongshengwenyu.top/Article/details/gtzhyncsmh.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.chenjidiqi.icu/Article/details/gtjfvqtiii.html

[Q56] 密集排名（并列不占位）
来源：http://dali.jiagoushi.top/Article/details/gtbdcckhmj.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.ybcxt.top/Article/details/gtgstbkopa.html

[Q57] 行号
来源：http://dali.kuanghao11.cn/Article/details/gtngcasoec.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gtfvdrxmen.html

[Q58] 累计求和
来源：http://dali.sxryk.cn/Article/details/gtrgjpziqf.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.cheryme.top/Article/details/gtdcyqfbwa.html

[Q59] 分组内累计
来源：http://dali.snrcjt.cn/Article/details/gteoazhrhh.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.xziqi.cn/Article/details/gtafizsrkl.html

[Q60] 取上一行 / 下一行
来源：http://dali.nanxinkj.top/Article/details/gttorzdatn.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.hnqzz.top/Article/details/gtmpdjbpbw.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.gogol.net.cn/Article/details/gtpmrvhxhp.html

[Q61] 移动平均
来源：http://dali.jqgufenzy.top/Article/details/gtmxxcdcte.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.hammf.cn/Article/details/gticbakdhq.html

[Q62] 分组占比
来源：http://dali.sysykeji.top/Article/details/gtppvbqzcv.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.tanke756.top/Article/details/gtlrmiwobm.html

[Q63] 开启事务
来源：http://dali.yongpay.top/Article/details/gtjmhkgzcq.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.chenzaomai.com/Article/details/gtsaqgcvhv.html

[Q64] 提交事务
来源：http://dali.wangshuangyany.cn/Article/details/gtrpavpvmx.html

COMMIT;
来源：http://dali.wangshuangyany.cn/Article/details/gtcvdyhtis.html

[Q65] 回滚事务
来源：http://dali.daxiang520.top/Article/details/gtqdcwymqh.html

ROLLBACK;
来源：http://dali.tian-w.cn/Article/details/gtaxmixblx.html

[Q66] 行锁查询
来源：http://dali.zycfv.cn/Article/details/gtgieejxch.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.tanke756.top/Article/details/gttkghzwwd.html

[Q67] 设置隔离级别
来源：http://dali.ivvv.top/Article/details/gtotfdwtnv.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.sweek.top/Article/details/gtqclyrttp.html

[Q68] 保存点
来源：http://dali.smart0.xyz/Article/details/gtveznqsdm.html

SAVEPOINT sp1;
来源：http://dali.pycfn.com/Article/details/gtaexdgkad.html

ROLLBACK TO sp1;
来源：http://dali.chenjidiqi.icu/Article/details/gtkzmlprto.html

[Q69] 查看执行计划
来源：http://dali.xuetiantiany.cn/Article/details/gtiazkehwn.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.yuxming.cn/Article/details/gtsreyyvww.html

[Q70] 更新统计信息
来源：http://dali.c1oappe.top/Article/details/gtuzykvygf.html

ANALYZE TABLE users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtylzhusjq.html

[Q71] 查看建表语句
来源：http://dali.ehwqpu.com/Article/details/gtlnebcjjr.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.fzhhl.top/Article/details/gtqucpvkfy.html

[Q72] 查看索引
来源：http://dali.zhongyouzk.top/Article/details/gtngzrbsmk.html

SHOW INDEX FROM users;
来源：http://dali.sufxvd.cn/Article/details/gtewcjwnlo.html

[Q73] 查看表状态
来源：http://dali.yvedp.cn/Article/details/gtvfhhxdlp.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.chenjidiqi.icu/Article/details/gtkcspgxqd.html

[Q74] 强制使用索引
来源：http://dali.xuanzx.com/Article/details/gtwtvfrocx.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.gotoacloud.top/Article/details/gtvuxwpixs.html

[Q75] 日期格式化
来源：http://dali.feifeiyinyue.top/Article/details/gtocyiqqlj.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.hnxiangtu.top/Article/details/gtyjozeyec.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.wangdashe.top/Article/details/gthdxmbkmz.html

[Q76] 按天统计
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmkyyoneh.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.jqgfzy.top/Article/details/gtglmjgyqy.html

[Q77] 时间加减
来源：http://dali.cashguo.top/Article/details/gtprsqnkfq.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.andypj.xyz/Article/details/gtwsysaxhe.html

[Q78] 当前时间
来源：http://dali.shzxlz.cn/Article/details/gtufpeyjyy.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.yuanzhike.top/Article/details/gtogifkecz.html

[Q79] 字符串拼接
来源：http://dali.yuxming.cn/Article/details/gtfqrynrvt.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.hysaishi.cn/Article/details/gtobiyhtri.html

[Q80] 字符串截取
来源：http://dali.xuanzx.com/Article/details/gtpxpsimef.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.tanke756.top/Article/details/gtdqszrdez.html

[Q81] 字符串替换
来源：http://dali.cdnleiting.top/Article/details/gtsuuttbku.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.yongpay.top/Article/details/gtstrtxpku.html

[Q82] 字符长度与字节长度
来源：http://dali.fzhhl.top/Article/details/gtfqinurtm.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.daria6918.cn/Article/details/gtqsyedtkr.html

[Q83] 大小写转换
来源：http://dali.9152youxi.cn/Article/details/gtapwtoyne.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhongyouzk.top/Article/details/gtecwsopxu.html

[Q84] 去除首尾空格
来源：http://dali.yongpay.top/Article/details/gtvhkgetzn.html

SELECT TRIM(name) FROM users;
来源：http://dali.bjfxy.top/Article/details/gttuommpdd.html

[Q85] 数值取整
来源：http://dali.jinqigufen.top/Article/details/gtholyseam.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.vqdsnc.cn/Article/details/gtfiseqvlp.html

[Q86] 读取 JSON 字段
来源：http://dali.feifeiyinyue.top/Article/details/gtdlnaupkk.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.ehwqpu.com/Article/details/gtuaigxqwl.html

[Q87] JSON 字段做条件
来源：http://dali.xuetiantiany.cn/Article/details/gtvhsiwyrv.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.guowangkeji.top/Article/details/gtmtfsxkyp.html

[Q88] 行转列（条件聚合）
来源：http://dali.nanxinkj.top/Article/details/gtohujfdck.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.pengpengdd.cyou/Article/details/gtvegulfix.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpmmyfjiw.html

[Q89] 判断表是否存在
来源：http://dali.guowangkeji.top/Article/details/gttgdladjb.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.svipenyu.cn/Article/details/gtndyyfzsi.html

[Q90] 生成序号列
来源：http://dali.yongpay.top/Article/details/gtgioigine.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.dianchejie.cn/Article/details/gtlcgifqpg.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtnpnzpppr.html

R. Bash 专题
来源：http://dali.ywan-chungtsiang.top/Article/details/gtamztffmr.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtcfvmmjer.html

[R01] shebang 与严格模式
来源：http://dali.yangfankeji.com/Article/details/gtjktyuagf.html

#!/usr/bin/env bash
来源：http://dali.yonumen.top/Article/details/gtirugrspz.html

set -euo pipefail
来源：http://dali.tianlin.xyz/Article/details/gtvqzoxvrr.html

[R02] 变量赋值与使用
来源：http://dali.wangshuangyany.cn/Article/details/gtplewtbut.html

name="Tom"; echo "$name"
来源：http://dali.yongpay.top/Article/details/gtaetfkfzj.html

[R03] 只读变量
来源：http://dali.316326.xyz/Article/details/gttqhoqjtu.html

readonly PI=3.14
来源：http://dali.zdqjudy.top/Article/details/gtmaqxvjbs.html

[R04] 位置参数
来源：http://dali.hnqzz.top/Article/details/gtxjxaqywh.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.cashguo.top/Article/details/gtdlgjcebf.html

[R05] 参数默认值
来源：http://dali.kuanghao11.cn/Article/details/gtcbmbmaff.html

name="${1:-default}"
来源：http://dali.jianghu66.top/Article/details/gtfaedysya.html

[R06] 判断命令是否存在
来源：http://dali.hnxiangtu.top/Article/details/gthaacewtp.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.jqgufenzy.top/Article/details/gtkpmttzqt.html

[R07] if 判断文件
来源：http://dali.dianchejie.cn/Article/details/gtewdmdmxx.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.vqdsnc.cn/Article/details/gtkztjxrie.html

[R08] 数值比较
来源：http://dali.jinqigfzy.top/Article/details/gtvftaugry.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.shuidangran.top/Article/details/gtvktvszht.html

[R09] 字符串比较
来源：http://dali.daria6918.cn/Article/details/gtkswlqvpm.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.dashuyun.cn/Article/details/gthnitxdka.html

[R10] 正则匹配
来源：http://dali.quarkkingdee.top/Article/details/gtmctfzzbk.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhaomingkeji.xyz/Article/details/gtogjqelrr.html

[R11] case 多分支
来源：http://dali.c1oappe.top/Article/details/gtxkxzohbo.html

case "$1" in
来源：http://dali.yonumen.top/Article/details/gtbptvozun.html

start) echo "启动" ;;
来源：http://dali.fengsongda.top/Article/details/gtyqzqdsqy.html

stop)  echo "停止" ;;
来源：http://dali.xinyue.icu/Article/details/gtlypmsmgt.html

*)     echo "未知命令" ;;
来源：http://dali.snrcjt.cn/Article/details/gtqrtwjojy.html

esac
来源：http://dali.yj20258.top/Article/details/gtrfllqsgk.html

[R12] for 遍历文件
来源：http://dali.wangshuangyany.cn/Article/details/gtotznkjlm.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhiwuduotai.top/Article/details/gtzgzupoyx.html

[R13] for 计数循环
来源：http://dali.mhx1999.top/Article/details/gtkszziqcr.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.yj20258.top/Article/details/gtldditlml.html

[R14] C 风格 for
来源：http://dali.xinyue.icu/Article/details/gtvotopteh.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.sysykeji.top/Article/details/gtkoknmgui.html

[R15] while 逐行读文件
来源：http://dali.havefunace.top/Article/details/gtosvxzwcd.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zdqjudy.top/Article/details/gtmtucaxct.html

[R16] until 等待条件
来源：http://dali.yj20258.top/Article/details/gttzsffpmh.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.yueranfly.top/Article/details/gtpwrvtlsh.html

[R17] 数组定义与取值
来源：http://dali.nwbrower.top/Article/details/gtcgiffnxu.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gtpnvwarpu.html

[R18] 遍历数组
来源：http://dali.ppjwa.cn/Article/details/gtaefjmigr.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhixingplan.top/Article/details/gtqpddhnfz.html

[R19] 数组长度
来源：http://dali.zdqjudy.top/Article/details/gtafkqkkmh.html

echo "${#arr[@]}"
来源：http://dali.yonumen.top/Article/details/gtdqaabzzh.html

[R20] 关联数组（字典）
来源：http://dali.tanke756.top/Article/details/gtfrnedbvm.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.0kj1m.cn/Article/details/gtgujsdrrz.html

[R21] 字符串长度
来源：http://dali.yongpay.top/Article/details/gtewkcrogx.html

echo "${#s}"
来源：http://dali.zhixingplan.top/Article/details/gtmknexgvt.html

[R22] 截取子串
来源：http://dali.sxryk.cn/Article/details/gtmdudgpug.html

echo "${s:0:5}"
来源：http://dali.xinyue.icu/Article/details/gtijkzdrkm.html

[R23] 字符串替换
来源：http://dali.zhiwuduotai.top/Article/details/gtgskgwoxu.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.yj20258888.top/Article/details/gtzbqzmmym.html

[R24] 大小写转换
来源：http://dali.yonumen.top/Article/details/gtovtlyztj.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.9152youxi.cn/Article/details/gtkdretutu.html

[R25] 去后缀 / 去前缀
来源：http://dali.gogol.net.cn/Article/details/gtntpivjfm.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.ehwqpu.com/Article/details/gtwkjibbno.html

[R26] 命令替换
来源：http://dali.tianlin.xyz/Article/details/gtahiioxzn.html

now=$(date +%F); echo "$now"
来源：http://dali.daxiang520.top/Article/details/gtlxvnhaoo.html

[R27] 算术展开
来源：http://dali.jinghuilouyu.cn/Article/details/gtsqjndaii.html

echo $((1 + 2 * 3))
来源：http://dali.xuetiantiany.cn/Article/details/gtogniqjia.html

[R28] 浮点运算
来源：http://dali.iojbl.cn/Article/details/gtoucaqtsu.html

echo "scale=2; 10/3" | bc
来源：http://dali.pycfn.com/Article/details/gtvpuufsjw.html

[R29] 定义函数
来源：http://dali.zdqjudy.top/Article/details/gtmwufqayl.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhengqikj.top/Article/details/gtfxhswmjh.html

[R30] 函数返回状态码
来源：http://dali.hongshengwenyu.top/Article/details/gtcizaxnwt.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.wangshuangyany.cn/Article/details/gtrarsdwkm.html

[R31] 局部变量
来源：http://dali.vqdsnc.cn/Article/details/gtormvikxp.html

f() { local x=1; echo "$x"; }
来源：http://dali.pengpengdd.cyou/Article/details/gtlkoxuvcg.html

[R32] 参数个数校验
来源：http://dali.quarkkingdee.top/Article/details/gtxmtrhfyo.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zycfv.cn/Article/details/gtwnghemlo.html

[R33] 捕获错误并提示行号
来源：http://dali.gogol.net.cn/Article/details/gteqtlnknl.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhiwuduotai.top/Article/details/gtgvmjcowp.html

[R34] 退出时清理
来源：http://dali.jqgufenzy.top/Article/details/gthzsizyur.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.andypj.xyz/Article/details/gtsxiwhpqo.html

[R35] 后台执行并等待
来源：http://dali.hnqzz.top/Article/details/gtdzqdqczh.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.andypj.xyz/Article/details/gtrzdfabht.html

[R36] 并发执行多个任务
来源：http://dali.cucudq.cn/Article/details/gtkiwmtrai.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhoulong.xyz/Article/details/gtlojujztq.html

[R37] 把输出赋给变量
来源：http://dali.gotoacloud.top/Article/details/gtnfdfkzgx.html

files=$(ls -1)
来源：http://dali.c1oappe.top/Article/details/gtxaybjmeg.html

[R38] 管道串联
来源：http://dali.mhx1999.top/Article/details/gtejcjrufn.html

cat a.txt | grep -i error | wc -l
来源：http://dali.pengpengdd.cyou/Article/details/gtwftzxymn.html

[R39] 重定向标准输出与错误
来源：http://dali.xuetiantiany.cn/Article/details/gtsjdvfoxv.html

cmd > out.log 2>&1
来源：http://dali.jinqigfzy.top/Article/details/gtjjyrnzkn.html

[R40] 追加写日志
来源：http://dali.tanke756.top/Article/details/gtholetmfa.html

echo "log" >> out.log
来源：http://dali.hfpthk.cn/Article/details/gtqzubxsmq.html

[R41] 丢弃输出
来源：http://dali.chenjidiqi.icu/Article/details/gtgqklneqq.html

cmd >/dev/null 2>&1
来源：http://dali.jlsjyb.cn/Article/details/gthvvxdees.html

[R42] 输入重定向
来源：http://dali.ydzc1.top/Article/details/gtljcilzrk.html

wc -l < a.txt
来源：http://dali.sxryk.cn/Article/details/gtotbgevwe.html

[R43] 按名字查找文件
来源：http://dali.yj20258.top/Article/details/gtxdwfjaek.html

find . -name "*.log" -type f
来源：http://dali.ybcxt.top/Article/details/gtxcibpkmq.html

[R44] 按修改时间查找
来源：http://dali.sufxvd.cn/Article/details/gtltoenjpq.html

find . -mtime -7 -type f
来源：http://dali.jyoumei.cn/Article/details/gtyxgsmeaq.html

[R45] 批量删除
来源：http://dali.cqqwz.cn/Article/details/gtukzrzdkr.html

find . -name "*.tmp" -delete
来源：http://dali.wangdashe.top/Article/details/gtwrwnspng.html

[R46] 递归替换文件内容
来源：http://dali.gotoacloud.top/Article/details/gtgdanohwj.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhoulong.xyz/Article/details/gteptuscte.html

[R47] sed 单行替换
来源：http://dali.yonumen.top/Article/details/gtesnrgbit.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.cucudq.cn/Article/details/gtkrnqwrce.html

[R48] awk 取指定列
来源：http://dali.yueranfly.top/Article/details/gtpfvufsuq.html

awk '{print $1, $3}' a.txt
来源：http://dali.quarkkingdee.top/Article/details/gtpfdbzqke.html

[R49] awk 带条件
来源：http://dali.tian-w.cn/Article/details/gtlmdollar.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.hammf.cn/Article/details/gtmkipwxul.html

[R50] awk 求和
来源：http://dali.xziqi.cn/Article/details/gtbftexxna.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.xuanzx.com/Article/details/gtkfuivisd.html

[R51] 排序去重取前几
来源：http://dali.nwbrower.top/Article/details/gtszmmetql.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.gogol.net.cn/Article/details/gtaoplqiqp.html

[R52] 统计行数
来源：http://dali.fengsongda.top/Article/details/gtoergcofv.html

wc -l a.txt
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkspvbuzs.html

[R53] 查看文件头与实时尾
来源：http://dali.yvedp.cn/Article/details/gtddifzree.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.cheryme.top/Article/details/gtvvwyllcd.html

[R54] 比较两个文件
来源：http://dali.fengsongda.top/Article/details/gtstfyyixy.html

diff a.txt b.txt
来源：http://dali.jiagoushi.top/Article/details/gtyersphak.html

[R55] 压缩与解压
来源：http://dali.hammf.cn/Article/details/gtgwrdjkqf.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.gotoacloud.top/Article/details/gtblaggjiv.html

[R56] 远程拷贝
来源：http://dali.yangfankeji.com/Article/details/gttdhcpzfp.html

scp file user@host:/path/
来源：http://dali.yueranfly.top/Article/details/gtwpdhvkht.html

[R57] 远程执行命令
来源：http://dali.chenlongwang.top/Article/details/gtluqgytpi.html

ssh user@host 'uptime'
来源：http://dali.feifeiyinyue.top/Article/details/gtourimbie.html

[R58] 下载文件
来源：http://dali.jlsjyb.cn/Article/details/gtcdgtlpsj.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.hnqzz.top/Article/details/gtbtgcodtc.html

[R59] 发 POST JSON
来源：http://dali.jinqigfzy.top/Article/details/gtbzewvljw.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.chenlongwang.top/Article/details/gtyjlwyxuz.html

[R60] 只看 HTTP 状态码
来源：http://dali.daxiang520.top/Article/details/gtumaapqnq.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.daxiang520.top/Article/details/gtwvwicpjs.html

[R61] 磁盘占用
来源：http://dali.smart0.xyz/Article/details/gtayaxefpq.html

df -h;  du -sh *
来源：http://dali.gogol.net.cn/Article/details/gtekpxxyhf.html

[R62] 找最占空间的文件
来源：http://dali.tanke756.top/Article/details/gtjzlcxyqf.html

du -ah . | sort -rh | head -10
来源：http://dali.shzxlz.cn/Article/details/gtguaqcpym.html

[R63] 内存与进程
来源：http://dali.yuanzhike.top/Article/details/gtdkkpegvo.html

free -h;  ps aux | grep nginx
来源：http://dali.redwolf501.top/Article/details/gtiwoolwhx.html

[R64] 结束进程
来源：http://dali.chenjidiqi.icu/Article/details/gtpivthnrf.html

kill -9 $(pgrep -f app.py)
来源：http://dali.yj202588.top/Article/details/gtvrvpscdq.html

[R65] 查看端口占用
来源：http://dali.shangyingyoupin.top/Article/details/gtwdcbxxcs.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.sxryk.cn/Article/details/gtckxbzzzn.html

[R66] 定时任务
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkwsvskpt.html

crontab -e;  crontab -l
来源：http://dali.yj20258888.top/Article/details/gtbqlfnudp.html

[R67] 生成随机十六进制串
来源：http://dali.cheryme.top/Article/details/gtumztekra.html

openssl rand -hex 16
来源：http://dali.wangshuangyany.cn/Article/details/gtnnktwvms.html

[R68] 计算文件校验值
来源：http://dali.xziqi.cn/Article/details/gtmupijrru.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.meibo888.top/Article/details/gtuhetlvxd.html

[R69] 生成随机密码
来源：http://dali.gogol.net.cn/Article/details/gtgyoltzya.html

head -c 16 /dev/urandom | base64
来源：http://dali.yj20258888.top/Article/details/gtxwflmlvz.html

[R70] 时间戳与互转
来源：http://dali.shzxlz.cn/Article/details/gtexadjrpo.html

date +%s;  date -d @1700000000
来源：http://dali.chenlongwang.top/Article/details/gtvzjicyyy.html

[R71] 日期格式化
来源：http://dali.xuanzx.com/Article/details/gtvbccoddt.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.chenjidiqi.icu/Article/details/gtyreeuryp.html

[R72] 等待端口就绪
来源：http://dali.xylfe.cn/Article/details/gtpetjlofy.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.tanke756.top/Article/details/gtwjtwiydm.html

[R73] 分割大日志
来源：http://dali.chenzaomai.com/Article/details/gtfampqgtk.html

split -l 1000 big.log part_
来源：http://dali.jqgfzy.top/Article/details/gtzhzhscbo.html

[R74] 批量重命名
来源：http://dali.ehwqpu.com/Article/details/gtohzhbgbx.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.redwolf501.top/Article/details/gtjafaygui.html

[R75] 导出环境变量
来源：http://dali.jqgufenzy.top/Article/details/gtoyejyoij.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.haohaochexian.top/Article/details/gtzsevlugg.html

[R76] 使用临时文件
来源：http://dali.yuxming.cn/Article/details/gttthjjvgl.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.hfpthk.cn/Article/details/gtaspbcwrd.html

[R77] 读取用户输入
来源：http://dali.hnxiangtu.top/Article/details/gtixviwnxm.html


<!-- 参考信息 -->