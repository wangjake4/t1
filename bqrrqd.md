代发 wailian999

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.xinyue.icu/Article/details/gtcwxdttfg.html

[Q24] 去重
来源：http://dali.nanxinkj.top/Article/details/gtxwsafosd.html

SELECT DISTINCT city FROM users;
来源：http://dali.sysykeji.top/Article/details/gtxmotabvq.html

[Q25] 只取前 N 条
来源：http://dali.birdmap.top/Article/details/gtfizlkkvt.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.hfpthk.cn/Article/details/gtflckzqpn.html

[Q26] 计数
来源：http://dali.shuidangran.top/Article/details/gtfnuctvzt.html

SELECT COUNT(*) FROM users;
来源：http://dali.shzxlz.cn/Article/details/gtahscxieb.html

[Q27] 条件计数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsjdoevdl.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.xziqi.cn/Article/details/gtonvshiqy.html

[Q28] 求和与平均
来源：http://dali.zycfv.cn/Article/details/gtpkeoblnm.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.yuxming.cn/Article/details/gtlvqrewdx.html

[Q29] 最大最小值
来源：http://dali.yuxming.cn/Article/details/gtjxlqidmx.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.ydzc1.top/Article/details/gtvwlzgypt.html

[Q30] 分组统计
来源：http://dali.jinqigfzy.top/Article/details/gtwevcbbks.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.aibaodan.cn/Article/details/gtaapkdmeu.html

[Q31] 分组后过滤
来源：http://dali.dashuyun.cn/Article/details/gtfiquoczz.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.gogol.net.cn/Article/details/gtjsjzltmv.html

[Q32] 分组拼接字符串
来源：http://dali.yuanzhike.top/Article/details/gtfftzrvip.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.hnxiangtu.top/Article/details/gtnogehezx.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.meibo888.top/Article/details/gtygcwozaz.html

[Q33] 多列分组
来源：http://dali.gzhubu.top/Article/details/gtuopmnsqk.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.cqqwz.cn/Article/details/gtieyrpbdk.html

[Q34] 每组取第一条
来源：http://dali.gaohongyu789.top/Article/details/gtbjeoopmj.html

SELECT * FROM (
来源：http://dali.yuanzhike.top/Article/details/gtkoppzkbf.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.nanxinkj.top/Article/details/gtjintnydk.html

) t WHERE rn = 1;
来源：http://dali.mhx1999.top/Article/details/gtgvlituzm.html

[Q35] 内连接
来源：http://dali.birdmap.top/Article/details/gtyiryrfjs.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.pycfn.com/Article/details/gtqfquknwi.html

[Q36] 左连接
来源：http://dali.redwolf501.top/Article/details/gtidnfkotl.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.smart0.xyz/Article/details/gtusorkcic.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gtsuoobdnr.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.yongpay.top/Article/details/gtfltupwpl.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.daria6918.cn/Article/details/gtyrpdtemh.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.hywenlv.cn/Article/details/gtaldurujl.html

[Q39] 自连接（查上下级）
来源：http://dali.yuanzhike.top/Article/details/gtibvrfmqu.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.jyoumei.cn/Article/details/gtivvgdbsv.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.daria6918.cn/Article/details/gtcmyhguxq.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.ppjwa.cn/Article/details/gtedunyfzo.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.chenjidiqi.icu/Article/details/gtahwkybkf.html

[Q41] 多表连接
来源：http://dali.havefunace.top/Article/details/gtarwgutsm.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.birdmap.top/Article/details/gtsssibfts.html

JOIN users u ON u.id = o.user_id
来源：http://dali.yueranfly.top/Article/details/gtkfmxowio.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.jinghuilouyu.cn/Article/details/gtlunpsknk.html

[Q42] 连接条件附加过滤
来源：http://dali.aizwys.cn/Article/details/gtgxtzdyxi.html

SELECT u.name, o.amount FROM users u
来源：http://dali.chenjidiqi.icu/Article/details/gthtyhkuqm.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.jyoumei.cn/Article/details/gtbelythsz.html

[Q43] 标量子查询
来源：http://dali.nanxuanxn.top/Article/details/gtuchaesjd.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.hfpthk.cn/Article/details/gtffmmrdgb.html

[Q44] IN 子查询
来源：http://dali.tanke756.top/Article/details/gtzdcdnbol.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.bjfxy.top/Article/details/gtmptnulhf.html

[Q45] EXISTS 判断存在
来源：http://dali.svipenyu.cn/Article/details/gtvvhvcjal.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.cdnleiting.top/Article/details/gtrwhqsbkb.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.ppjwa.cn/Article/details/gtyvwaadft.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yanxiufei.cn/Article/details/gtdiuibbvo.html

[Q47] 与平均值比较
来源：http://dali.smart0.xyz/Article/details/gtwgvtusup.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.hnqzz.top/Article/details/gtoijcjtif.html

[Q48] CTE 公用表表达式
来源：http://dali.jinqigfzy.top/Article/details/gtblpxojxj.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.hongshengwenyu.top/Article/details/gtzqldknzi.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.fengsongda.top/Article/details/gtekejecqs.html

[Q49] 更新单行
来源：http://dali.c1oappe.top/Article/details/gtnltbivqi.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.jinghuilouyu.cn/Article/details/gtpdzsmfpn.html

[Q50] 批量更新
来源：http://dali.zycfv.cn/Article/details/gtwpgbmjdh.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.daxiang520.top/Article/details/gtghdcscwl.html

[Q51] 用子查询更新
来源：http://dali.mhx1999.top/Article/details/gtrgheulke.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.daria6918.cn/Article/details/gtyolordlf.html

[Q52] 删除指定行
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzsuqxbie.html

DELETE FROM users WHERE id = 10;
来源：http://dali.ppjwa.cn/Article/details/gtkgphwopn.html

[Q53] 按条件删除
来源：http://dali.zhoulong.xyz/Article/details/gthllvufuj.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.xinyue.icu/Article/details/gtcvvppxxc.html

[Q54] 清空表
来源：http://dali.daria6918.cn/Article/details/gtjyugkzim.html

TRUNCATE TABLE logs;
来源：http://dali.andypj.xyz/Article/details/gtvgycvqhc.html

[Q55] 排名（并列占位）
来源：http://dali.jqgufenzy.top/Article/details/gtidaxrnbd.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.cucudq.cn/Article/details/gtjtidvgyo.html

[Q56] 密集排名（并列不占位）
来源：http://dali.aizwys.cn/Article/details/gthtnxyizj.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.hnqzz.top/Article/details/gtgvgusynf.html

[Q57] 行号
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcuyzxkkp.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.wangshuangyany.cn/Article/details/gtmvmmvkkw.html

[Q58] 累计求和
来源：http://dali.jiagoushi.top/Article/details/gtlntbzfup.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.chenlongwang.top/Article/details/gthdbalgds.html

[Q59] 分组内累计
来源：http://dali.gzhubu.top/Article/details/gtiwhwumdu.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.mhx1999.top/Article/details/gtkratvdme.html

[Q60] 取上一行 / 下一行
来源：http://dali.zdqjudy.top/Article/details/gtlmiwzruu.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.yonumen.top/Article/details/gtjrwvqhev.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.yuanzhike.top/Article/details/gtwzcylrcd.html

[Q61] 移动平均
来源：http://dali.daxiang520.top/Article/details/gtytomxcbs.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.jyoumei.cn/Article/details/gtwukdwkjh.html

[Q62] 分组占比
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrhamnuym.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.jlsjyb.cn/Article/details/gtcnjffubw.html

[Q63] 开启事务
来源：http://dali.yueranfly.top/Article/details/gtqhlcjfoy.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.yuxming.cn/Article/details/gtmvcxnrob.html

[Q64] 提交事务
来源：http://dali.xuanzx.com/Article/details/gtetmpyzhn.html

COMMIT;
来源：http://dali.cdnleiting.top/Article/details/gtfrpiexbz.html

[Q65] 回滚事务
来源：http://dali.jinqigufen.top/Article/details/gtcdyqzemx.html

ROLLBACK;
来源：http://dali.chenjidiqi.icu/Article/details/gtevsobuot.html

[Q66] 行锁查询
来源：http://dali.sweek.top/Article/details/gtsaijphsa.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.jqgufenzy.top/Article/details/gtfvutqibn.html

[Q67] 设置隔离级别
来源：http://dali.smart0.xyz/Article/details/gtobhkswjf.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.yonumen.top/Article/details/gtfhlytijy.html

[Q68] 保存点
来源：http://dali.jqgfzy.top/Article/details/gtvpiizzqb.html

SAVEPOINT sp1;
来源：http://dali.pycfn.com/Article/details/gtbisusxad.html

ROLLBACK TO sp1;
来源：http://dali.hongshengwenyu.top/Article/details/gtqggzsucm.html

[Q69] 查看执行计划
来源：http://dali.ydzc1.top/Article/details/gtsfqeuuhq.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.jinqigfzy.top/Article/details/gtzmkssffp.html

[Q70] 更新统计信息
来源：http://dali.wangshuangyany.cn/Article/details/gtdfpprtbo.html

ANALYZE TABLE users;
来源：http://dali.wangdashe.top/Article/details/gtsitaltfe.html

[Q71] 查看建表语句
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrqavqvsr.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.ehwqpu.com/Article/details/gtqkyvqyir.html

[Q72] 查看索引
来源：http://dali.ppjwa.cn/Article/details/gtsjhzssgb.html

SHOW INDEX FROM users;
来源：http://dali.cashguo.top/Article/details/gthhrhvfcf.html

[Q73] 查看表状态
来源：http://dali.shanyushiyangtech.top/Article/details/gtkorsvjav.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.jiagoushi.top/Article/details/gtckbedmsf.html

[Q74] 强制使用索引
来源：http://dali.shzxlz.cn/Article/details/gthkspgmea.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.xuanzx.com/Article/details/gtxijbohsc.html

[Q75] 日期格式化
来源：http://dali.jinqigfzy.top/Article/details/gtfzwwnclk.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.cheryme.top/Article/details/gtsrzoxcqh.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.hfpthk.cn/Article/details/gtrsychveo.html

[Q76] 按天统计
来源：http://dali.sysykeji.top/Article/details/gtvzpkmzww.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.yuanzhike.top/Article/details/gtmdtedpuk.html

[Q77] 时间加减
来源：http://dali.yj20258888.top/Article/details/gtlxefwrpx.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.chenzaomai.com/Article/details/gtefmuvwvz.html

[Q78] 当前时间
来源：http://dali.cheryme.top/Article/details/gtigwurrjz.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjxzfhpku.html

[Q79] 字符串拼接
来源：http://dali.vqdsnc.cn/Article/details/gtbrvzgodf.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.ydzc1.top/Article/details/gtuqjmrxev.html

[Q80] 字符串截取
来源：http://dali.yanxiufei.cn/Article/details/gtcddpffxt.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.0kj1m.cn/Article/details/gtjjnecizw.html

[Q81] 字符串替换
来源：http://dali.svipenyu.cn/Article/details/gtuvosgtif.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.feifeiyinyue.top/Article/details/gtvyqjohar.html

[Q82] 字符长度与字节长度
来源：http://dali.vqdsnc.cn/Article/details/gtjtiwsabx.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.tianlin.xyz/Article/details/gtewvcdiqa.html

[Q83] 大小写转换
来源：http://dali.pycfn.com/Article/details/gtlgtvzdps.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.ehwqpu.com/Article/details/gtwwfrdelc.html

[Q84] 去除首尾空格
来源：http://dali.nwbrower.top/Article/details/gtgvjrvzin.html

SELECT TRIM(name) FROM users;
来源：http://dali.tian-w.cn/Article/details/gtvdwavmyf.html

[Q85] 数值取整
来源：http://dali.ivvv.top/Article/details/gtmzvkemfa.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.yueranfly.top/Article/details/gtbainqeye.html

[Q86] 读取 JSON 字段
来源：http://dali.cucudq.cn/Article/details/gtweibstme.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.jianghu66.top/Article/details/gtncsbbfbx.html

[Q87] JSON 字段做条件
来源：http://dali.xuanzx.com/Article/details/gtuvezwbpj.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.guowangkeji.top/Article/details/gtsmohlqeo.html

[Q88] 行转列（条件聚合）
来源：http://dali.cqqwz.cn/Article/details/gtjxignodf.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqjrzsnuy.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.yuxming.cn/Article/details/gtdgtteekn.html

[Q89] 判断表是否存在
来源：http://dali.fzhhl.top/Article/details/gtwkpicsqe.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.316326.xyz/Article/details/gthpkeoodk.html

[Q90] 生成序号列
来源：http://dali.nanxinkj.top/Article/details/gtrvkygrgr.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.pengpengdd.cyou/Article/details/gtiqcarirk.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtohbetuvk.html

R. Bash 专题
来源：http://dali.aizwys.cn/Article/details/gtkibjjpbp.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtwcsfxwfc.html

[R01] shebang 与严格模式
来源：http://dali.dianchejie.cn/Article/details/gttzsijrrb.html

#!/usr/bin/env bash
来源：http://dali.redwolf501.top/Article/details/gtifrshswn.html

set -euo pipefail
来源：http://dali.cheryme.top/Article/details/gtejcxylbh.html

[R02] 变量赋值与使用
来源：http://dali.aibaodan.cn/Article/details/gtwidaofje.html

name="Tom"; echo "$name"
来源：http://dali.nanxinkj.top/Article/details/gtwzsowiwz.html

[R03] 只读变量
来源：http://dali.yj202588.top/Article/details/gthhbcfqlr.html

readonly PI=3.14
来源：http://dali.gotoacloud.top/Article/details/gtfozglphs.html

[R04] 位置参数
来源：http://dali.xziqi.cn/Article/details/gtfymgkrwh.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.jinqigufen.top/Article/details/gtobgfcveu.html

[R05] 参数默认值
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbxlohkjl.html

name="${1:-default}"
来源：http://dali.vqdsnc.cn/Article/details/gtlyknwdem.html

[R06] 判断命令是否存在
来源：http://dali.xuanzx.com/Article/details/gtzxjtdcxq.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjjvnlnuj.html

[R07] if 判断文件
来源：http://dali.hnqzz.top/Article/details/gtipycqfoc.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.guannengcc.top/Article/details/gtlvmqnuqa.html

[R08] 数值比较
来源：http://dali.tanke756.top/Article/details/gtvxvrgxvd.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.daxiang520.top/Article/details/gtfmckxrhb.html

[R09] 字符串比较
来源：http://dali.cucudq.cn/Article/details/gtasilrrfk.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.guowangkeji.top/Article/details/gtepknbgok.html

[R10] 正则匹配
来源：http://dali.yangfankeji.com/Article/details/gtcrlygjdx.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.jqgufenzy.top/Article/details/gtjhvbbehl.html

[R11] case 多分支
来源：http://dali.ehwqpu.com/Article/details/gthuwpjxuj.html

case "$1" in
来源：http://dali.ybcxt.top/Article/details/gtkpkyfcds.html

start) echo "启动" ;;
来源：http://dali.kuanghao11.cn/Article/details/gtcyxukssc.html

stop)  echo "停止" ;;
来源：http://dali.chenlongwang.top/Article/details/gttaumdsde.html

*)     echo "未知命令" ;;
来源：http://dali.tian-w.cn/Article/details/gtmbsooqub.html

esac
来源：http://dali.ybcxt.top/Article/details/gtauneobgx.html

[R12] for 遍历文件
来源：http://dali.cashguo.top/Article/details/gtffesvkev.html

for f in *.txt; do echo "$f"; done
来源：http://dali.hfpthk.cn/Article/details/gtpnjvmyju.html

[R13] for 计数循环
来源：http://dali.0kj1m.cn/Article/details/gtwzzrtyjy.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.yvedp.cn/Article/details/gtiulabmeq.html

[R14] C 风格 for
来源：http://dali.zhongyouzk.top/Article/details/gtemkkvhyb.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.sxryk.cn/Article/details/gtsthklhir.html

[R15] while 逐行读文件
来源：http://dali.dianchejie.cn/Article/details/gtxthhjegr.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.smart0.xyz/Article/details/gthkgjeyrt.html

[R16] until 等待条件
来源：http://dali.aizwys.cn/Article/details/gtmgzmkjdq.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.havefunace.top/Article/details/gtfebxauwa.html

[R17] 数组定义与取值
来源：http://dali.ehwqpu.com/Article/details/gtnirljrkr.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.yj202588.top/Article/details/gtzqycurco.html

[R18] 遍历数组
来源：http://dali.sufxvd.cn/Article/details/gturxxjznp.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.ehwqpu.com/Article/details/gtlhtnjdsq.html

[R19] 数组长度
来源：http://dali.shuidangran.top/Article/details/gtwledmtii.html

echo "${#arr[@]}"
来源：http://dali.316326.xyz/Article/details/gtvmyfygrs.html

[R20] 关联数组（字典）
来源：http://dali.snrcjt.cn/Article/details/gtrjtydofj.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.yonumen.top/Article/details/gtiekvxdre.html

[R21] 字符串长度
来源：http://dali.aibaodan.cn/Article/details/gtabllijpp.html

echo "${#s}"
来源：http://dali.nanxinkj.top/Article/details/gtrdtrckss.html

[R22] 截取子串
来源：http://dali.zhoulong.xyz/Article/details/gtvipqahdz.html

echo "${s:0:5}"
来源：http://dali.sweek.top/Article/details/gtynqfaelg.html

[R23] 字符串替换
来源：http://dali.ydzc1.top/Article/details/gtetafjzzp.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.shanyushiyangtech.top/Article/details/gtiksccnnx.html

[R24] 大小写转换
来源：http://dali.cheryme.top/Article/details/gtboeeydsn.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.tian-w.cn/Article/details/gtqcmffron.html

[R25] 去后缀 / 去前缀
来源：http://dali.nwbrower.top/Article/details/gtzhgkvyuz.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.jinghuilouyu.cn/Article/details/gtpitisnwx.html

[R26] 命令替换
来源：http://dali.daria6918.cn/Article/details/gtzemepknq.html

now=$(date +%F); echo "$now"
来源：http://dali.quarkkingdee.top/Article/details/gtnnvzxoaq.html

[R27] 算术展开
来源：http://dali.wangshuangyany.cn/Article/details/gtwmzvnggv.html

echo $((1 + 2 * 3))
来源：http://dali.haohaochexian.top/Article/details/gtwatnqwlt.html

[R28] 浮点运算
来源：http://dali.cqqwz.cn/Article/details/gtbgaiquat.html

echo "scale=2; 10/3" | bc
来源：http://dali.cdnleiting.top/Article/details/gtuyvsihbh.html

[R29] 定义函数
来源：http://dali.daxiang520.top/Article/details/gtuggmriin.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.birdmap.top/Article/details/gtamovkbqw.html

[R30] 函数返回状态码
来源：http://dali.tanke756.top/Article/details/gthwbeyyir.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.yangfankeji.com/Article/details/gtzqxntxqk.html

[R31] 局部变量
来源：http://dali.ivvv.top/Article/details/gtdegojjqp.html

f() { local x=1; echo "$x"; }
来源：http://dali.zdqjudy.top/Article/details/gtnofrttbq.html

[R32] 参数个数校验
来源：http://dali.vqdsnc.cn/Article/details/gtfcwkpwmd.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.ppjwa.cn/Article/details/gtpujalppe.html

[R33] 捕获错误并提示行号
来源：http://dali.yangfankeji.com/Article/details/gtpdwouhet.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.wangdashe.top/Article/details/gtwvvyytjd.html

[R34] 退出时清理
来源：http://dali.xziqi.cn/Article/details/gtepfpbrqx.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.hnxiangtu.top/Article/details/gtexbdqxvy.html

[R35] 后台执行并等待
来源：http://dali.shuidangran.top/Article/details/gtrnbrzvgw.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.jlsjyb.cn/Article/details/gtdcpjllpu.html

[R36] 并发执行多个任务
来源：http://dali.chenzaomai.com/Article/details/gtuagtozvl.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.chenzaomai.com/Article/details/gtoljtkrjw.html

[R37] 把输出赋给变量
来源：http://dali.vqdsnc.cn/Article/details/gtiqmyweww.html

files=$(ls -1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtqnajolft.html

[R38] 管道串联
来源：http://dali.tianlin.xyz/Article/details/gtgbpskzsp.html

cat a.txt | grep -i error | wc -l
来源：http://dali.fengsongda.top/Article/details/gtlkgqkqsd.html

[R39] 重定向标准输出与错误
来源：http://dali.hnxiangtu.top/Article/details/gtgstnaqhx.html

cmd > out.log 2>&1
来源：http://dali.xinyue.icu/Article/details/gtogaapixi.html

[R40] 追加写日志
来源：http://dali.shuidangran.top/Article/details/gtitchswwh.html

echo "log" >> out.log
来源：http://dali.cdnleiting.top/Article/details/gtziehbnea.html

[R41] 丢弃输出
来源：http://dali.cdnleiting.top/Article/details/gtsmuxefzf.html

cmd >/dev/null 2>&1
来源：http://dali.ivvv.top/Article/details/gttigxowco.html

[R42] 输入重定向
来源：http://dali.snrcjt.cn/Article/details/gtyukqoups.html

wc -l < a.txt
来源：http://dali.nwbrower.top/Article/details/gtpyngnepj.html

[R43] 按名字查找文件
来源：http://dali.shangyingyoupin.top/Article/details/gtbopryayb.html

find . -name "*.log" -type f
来源：http://dali.yuxming.cn/Article/details/gtmdgoesjw.html

[R44] 按修改时间查找
来源：http://dali.wangdashe.top/Article/details/gtkquvxgst.html

find . -mtime -7 -type f
来源：http://dali.tian-w.cn/Article/details/gtgwebbjjw.html

[R45] 批量删除
来源：http://dali.pycfn.com/Article/details/gtndterlsu.html

find . -name "*.tmp" -delete
来源：http://dali.fengsongda.top/Article/details/gtrekspyzp.html

[R46] 递归替换文件内容
来源：http://dali.cheryme.top/Article/details/gttfgluvbf.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zycfv.cn/Article/details/gtawrnrgho.html

[R47] sed 单行替换
来源：http://dali.mhx1999.top/Article/details/gtttqwdwov.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.gaohongyu789.top/Article/details/gtxysuxtkq.html

[R48] awk 取指定列
来源：http://dali.sysykeji.top/Article/details/gtatdggsld.html

awk '{print $1, $3}' a.txt
来源：http://dali.kuanghao11.cn/Article/details/gtkmnidytq.html

[R49] awk 带条件
来源：http://dali.xziqi.cn/Article/details/gtjipeiuid.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gtwwakmlrr.html

[R50] awk 求和
来源：http://dali.gogol.net.cn/Article/details/gtgleiqzwn.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhoulong.xyz/Article/details/gtdrlnfegf.html

[R51] 排序去重取前几
来源：http://dali.zhoulong.xyz/Article/details/gtutowdxbp.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.gogol.net.cn/Article/details/gtnzpfxukc.html

[R52] 统计行数
来源：http://dali.jinqigufen.top/Article/details/gtpsscaghx.html

wc -l a.txt
来源：http://dali.bjfxy.top/Article/details/gtcysnfpoq.html

[R53] 查看文件头与实时尾
来源：http://dali.yj20258888.top/Article/details/gtxcnabzqu.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.sweek.top/Article/details/gtpypxrrlb.html

[R54] 比较两个文件
来源：http://dali.birdmap.top/Article/details/gtnnawuxmo.html

diff a.txt b.txt
来源：http://dali.daria6918.cn/Article/details/gtjspccjqh.html

[R55] 压缩与解压
来源：http://dali.fengsongda.top/Article/details/gtrzkiknsl.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.ivvv.top/Article/details/gtrhgdexnz.html

[R56] 远程拷贝
来源：http://dali.tanke756.top/Article/details/gticuximig.html

scp file user@host:/path/
来源：http://dali.hywenlv.cn/Article/details/gtykhhfugu.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gtilduzksp.html

ssh user@host 'uptime'
来源：http://dali.xuanzx.com/Article/details/gtagpgkklk.html

[R58] 下载文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvlaixjkh.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.xinyue.icu/Article/details/gtscibzpwp.html

[R59] 发 POST JSON
来源：http://dali.zycfv.cn/Article/details/gtengzfggd.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.gaohongyu789.top/Article/details/gtcaeyfeds.html

[R60] 只看 HTTP 状态码
来源：http://dali.snrcjt.cn/Article/details/gtfdmnskzq.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.ppjwa.cn/Article/details/gtgldzzewl.html

[R61] 磁盘占用
来源：http://dali.hammf.cn/Article/details/gtsikfjbqw.html

df -h;  du -sh *
来源：http://dali.guowangkeji.top/Article/details/gtojdgfclb.html

[R62] 找最占空间的文件
来源：http://dali.yangfankeji.com/Article/details/gtudatjzhp.html

du -ah . | sort -rh | head -10
来源：http://dali.chenlongwang.top/Article/details/gtrfzrivzh.html

[R63] 内存与进程
来源：http://dali.9152youxi.cn/Article/details/gtlxucoyxh.html

free -h;  ps aux | grep nginx
来源：http://dali.jinghuilouyu.cn/Article/details/gtbrctkxek.html

[R64] 结束进程
来源：http://dali.birdmap.top/Article/details/gtmxixkknv.html

kill -9 $(pgrep -f app.py)
来源：http://dali.andypj.xyz/Article/details/gtcocmnocj.html

[R65] 查看端口占用
来源：http://dali.chenzaomai.com/Article/details/gthvhyrxet.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.sweek.top/Article/details/gtlffqjbas.html

[R66] 定时任务
来源：http://dali.ydzc1.top/Article/details/gtmfzdxytz.html

crontab -e;  crontab -l
来源：http://dali.chenzaomai.com/Article/details/gtkkwzicdt.html

[R67] 生成随机十六进制串
来源：http://dali.smart0.xyz/Article/details/gtvctamars.html

openssl rand -hex 16
来源：http://dali.yj202588.top/Article/details/gtxkbmmltt.html

[R68] 计算文件校验值
来源：http://dali.shangyingyoupin.top/Article/details/gtsqdnlixx.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.jinghuilouyu.cn/Article/details/gtucvrebho.html

[R69] 生成随机密码
来源：http://dali.guowangkeji.top/Article/details/gttcjzxewq.html

head -c 16 /dev/urandom | base64
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmrkuqefh.html

[R70] 时间戳与互转
来源：http://dali.gzhubu.top/Article/details/gtirxodiyf.html

date +%s;  date -d @1700000000
来源：http://dali.tianlin.xyz/Article/details/gtsowbqtax.html

[R71] 日期格式化
来源：http://dali.ehwqpu.com/Article/details/gtxemmfjzn.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhixingplan.top/Article/details/gtqfmmslqe.html

[R72] 等待端口就绪
来源：http://dali.gotoacloud.top/Article/details/gtusiwcqjq.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.yj202588.top/Article/details/gthlifqjmr.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gtwfigmyul.html


<!-- 参考信息 -->