代发 wailian999

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.aibaodan.cn/Article/details/gtkxavjwbb.html

[Q22] 排序
来源：http://dali.aibaodan.cn/Article/details/gtgihwldae.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gthgluzeoo.html

[Q23] 分页
来源：http://dali.gotoacloud.top/Article/details/gtnamjerca.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.yvedp.cn/Article/details/gtdzfwukum.html

[Q24] 去重
来源：http://dali.shzxlz.cn/Article/details/gthmobitah.html

SELECT DISTINCT city FROM users;
来源：http://dali.cqqwz.cn/Article/details/gtcpxmrwbr.html

[Q25] 只取前 N 条
来源：http://dali.daria6918.cn/Article/details/gtxzhhznzz.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgsrsdlmo.html

[Q26] 计数
来源：http://dali.dianchejie.cn/Article/details/gtssylvomx.html

SELECT COUNT(*) FROM users;
来源：http://dali.daxiang520.top/Article/details/gtnoxlbgfr.html

[Q27] 条件计数
来源：http://dali.9152youxi.cn/Article/details/gttstkpxgj.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.havefunace.top/Article/details/gtnbrynzgq.html

[Q28] 求和与平均
来源：http://dali.shanyushiyangtech.top/Article/details/gtmhyviogi.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.cqqwz.cn/Article/details/gtutjeajvr.html

[Q29] 最大最小值
来源：http://dali.zhengqikj.top/Article/details/gteylmscqb.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtacunehgb.html

[Q30] 分组统计
来源：http://dali.jqgfzy.top/Article/details/gtvegldscp.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.guowangkeji.top/Article/details/gtbiejgrga.html

[Q31] 分组后过滤
来源：http://dali.wangdashe.top/Article/details/gtpoqrxufp.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.ydzc1.top/Article/details/gtadyqhjwg.html

[Q32] 分组拼接字符串
来源：http://dali.cheryme.top/Article/details/gtuxplkzdv.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.ydzc1.top/Article/details/gtpttexazv.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gtnncwgivk.html

[Q33] 多列分组
来源：http://dali.yuanzhike.top/Article/details/gteisvntro.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.jinqigufen.top/Article/details/gtrljemdvb.html

[Q34] 每组取第一条
来源：http://dali.xziqi.cn/Article/details/gteizdbyib.html

SELECT * FROM (
来源：http://dali.snrcjt.cn/Article/details/gtqodtokng.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhengqikj.top/Article/details/gtpiatxnby.html

) t WHERE rn = 1;
来源：http://dali.jianghu66.top/Article/details/gtsoefmniu.html

[Q35] 内连接
来源：http://dali.yj20258.top/Article/details/gtnzmanvkh.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.chenjidiqi.icu/Article/details/gttednlcgw.html

[Q36] 左连接
来源：http://dali.hongshengwenyu.top/Article/details/gtrdrrevuf.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.cdnleiting.top/Article/details/gteuygcyth.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gtderwuuwq.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.hongshengwenyu.top/Article/details/gtwokzcebi.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zycfv.cn/Article/details/gtzvzijrmi.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfrhlzakd.html

[Q39] 自连接（查上下级）
来源：http://dali.chenzaomai.com/Article/details/gtqpzdcbpz.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.hnxiangtu.top/Article/details/gtzjawvkol.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.fzhhl.top/Article/details/gtybypjxyt.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.hysaishi.cn/Article/details/gtrdkhgfdi.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.pycfn.com/Article/details/gtkcklgxnb.html

[Q41] 多表连接
来源：http://dali.jiagoushi.top/Article/details/gtyqtymaxv.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.cucudq.cn/Article/details/gtwsdhbwcq.html

JOIN users u ON u.id = o.user_id
来源：http://dali.shangyingyoupin.top/Article/details/gtsddqjmuu.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.jiagoushi.top/Article/details/gtcnfzhodk.html

[Q42] 连接条件附加过滤
来源：http://dali.zhongyouzk.top/Article/details/gtfqrmqlkm.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhixingplan.top/Article/details/gtdhxheecd.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.cucudq.cn/Article/details/gtxitlhqge.html

[Q43] 标量子查询
来源：http://dali.pengpengdd.cyou/Article/details/gtpqaqvfwt.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.andypj.xyz/Article/details/gtrpcfufew.html

[Q44] IN 子查询
来源：http://dali.zhiwuduotai.top/Article/details/gtbxyehlhk.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.shangyingyoupin.top/Article/details/gtfsqfcqxa.html

[Q45] EXISTS 判断存在
来源：http://dali.dianchejie.cn/Article/details/gtznrfrjkl.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.hysaishi.cn/Article/details/gtwwilhada.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.sxryk.cn/Article/details/gtdjokjmzm.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zdqjudy.top/Article/details/gtuprirarg.html

[Q47] 与平均值比较
来源：http://dali.jiagoushi.top/Article/details/gtdsxbrnlt.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.9152youxi.cn/Article/details/gtnxotspxb.html

[Q48] CTE 公用表表达式
来源：http://dali.9152youxi.cn/Article/details/gtqqxidkfj.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zdqjudy.top/Article/details/gtognfcgwo.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.ybcxt.top/Article/details/gtpmryqdxk.html

[Q49] 更新单行
来源：http://dali.jinghuilouyu.cn/Article/details/gtwrnwcaio.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.cheryme.top/Article/details/gtbgqtnjfn.html

[Q50] 批量更新
来源：http://dali.hongshengwenyu.top/Article/details/gtqgomdrhp.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.shuidangran.top/Article/details/gtywhcrpjb.html

[Q51] 用子查询更新
来源：http://dali.dashuyun.cn/Article/details/gtwkgebbqg.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.feifeiyinyue.top/Article/details/gtgkppfxsk.html

[Q52] 删除指定行
来源：http://dali.yueranfly.top/Article/details/gtawpwqpxl.html

DELETE FROM users WHERE id = 10;
来源：http://dali.jqgfzy.top/Article/details/gtybprdngl.html

[Q53] 按条件删除
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrmonsmyj.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.shangyingyoupin.top/Article/details/gtqsimacqo.html

[Q54] 清空表
来源：http://dali.aizwys.cn/Article/details/gtsmifazky.html

TRUNCATE TABLE logs;
来源：http://dali.wangshuangyany.cn/Article/details/gtxgacxatp.html

[Q55] 排名（并列占位）
来源：http://dali.iojbl.cn/Article/details/gtcrkgfxqu.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.cdnleiting.top/Article/details/gtzinorjrk.html

[Q56] 密集排名（并列不占位）
来源：http://dali.ybcxt.top/Article/details/gtvvbupxxi.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.quarkkingdee.top/Article/details/gtmnmgvzuh.html

[Q57] 行号
来源：http://dali.ivvv.top/Article/details/gtcxgjwhfb.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.nanxinkj.top/Article/details/gtuhqfltti.html

[Q58] 累计求和
来源：http://dali.zhengqikj.top/Article/details/gtpulhhssk.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.cucudq.cn/Article/details/gtepdgnpux.html

[Q59] 分组内累计
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwjupyptt.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.jqgufenzy.top/Article/details/gtgptyqser.html

[Q60] 取上一行 / 下一行
来源：http://dali.jqgfzy.top/Article/details/gtjbpyqigx.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.shzxlz.cn/Article/details/gtjnfcmxtl.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.yueranfly.top/Article/details/gtyzqrbkcr.html

[Q61] 移动平均
来源：http://dali.jyoumei.cn/Article/details/gtbutxubks.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.smart0.xyz/Article/details/gtvmpjljkp.html

[Q62] 分组占比
来源：http://dali.9152youxi.cn/Article/details/gtufwpnzlp.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.316326.xyz/Article/details/gtgpbzgjxy.html

[Q63] 开启事务
来源：http://dali.yj202588.top/Article/details/gtmsyzsomu.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.fzhhl.top/Article/details/gtjoqxauze.html

[Q64] 提交事务
来源：http://dali.jyoumei.cn/Article/details/gtmakfoeqd.html

COMMIT;
来源：http://dali.zhixingplan.top/Article/details/gtvfkrvzgt.html

[Q65] 回滚事务
来源：http://dali.bjfxy.top/Article/details/gtvtsxvdcd.html

ROLLBACK;
来源：http://dali.snrcjt.cn/Article/details/gtpoylylmh.html

[Q66] 行锁查询
来源：http://dali.hysaishi.cn/Article/details/gteclvyrbg.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.daria6918.cn/Article/details/gtjyflylzu.html

[Q67] 设置隔离级别
来源：http://dali.ppjwa.cn/Article/details/gtvvvsmujl.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.xziqi.cn/Article/details/gtbydsjjxg.html

[Q68] 保存点
来源：http://dali.hammf.cn/Article/details/gtzgugqtdi.html

SAVEPOINT sp1;
来源：http://dali.chenlongwang.top/Article/details/gttpatlujs.html

ROLLBACK TO sp1;
来源：http://dali.hnxiangtu.top/Article/details/gtjlomanha.html

[Q69] 查看执行计划
来源：http://dali.chenlongwang.top/Article/details/gtkiqfgbwv.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.sufxvd.cn/Article/details/gtubukimtj.html

[Q70] 更新统计信息
来源：http://dali.sweek.top/Article/details/gtlchmpctk.html

ANALYZE TABLE users;
来源：http://dali.jinghuilouyu.cn/Article/details/gtcbvofbji.html

[Q71] 查看建表语句
来源：http://dali.sufxvd.cn/Article/details/gtctjlxyam.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.hysaishi.cn/Article/details/gtyurzkupl.html

[Q72] 查看索引
来源：http://dali.hywenlv.cn/Article/details/gtyzmqilna.html

SHOW INDEX FROM users;
来源：http://dali.yj202588.top/Article/details/gtxhypjwsm.html

[Q73] 查看表状态
来源：http://dali.quarkkingdee.top/Article/details/gtimmajuey.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.wangshuangyany.cn/Article/details/gtziubbapr.html

[Q74] 强制使用索引
来源：http://dali.andypj.xyz/Article/details/gtuwvddzee.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.xuetiantiany.cn/Article/details/gtivgwnfjy.html

[Q75] 日期格式化
来源：http://dali.jqgufenzy.top/Article/details/gtslofrzcm.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.wangdashe.top/Article/details/gtjiesgstu.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.quarkkingdee.top/Article/details/gtoshivvqj.html

[Q76] 按天统计
来源：http://dali.nanxinkj.top/Article/details/gtcorctpxg.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.jiagoushi.top/Article/details/gtmzvftyed.html

[Q77] 时间加减
来源：http://dali.guowangkeji.top/Article/details/gtsrqzsxcr.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.aizwys.cn/Article/details/gtaxnxkmsm.html

[Q78] 当前时间
来源：http://dali.wangshuangyany.cn/Article/details/gtldprrddc.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.9152youxi.cn/Article/details/gthjtjitqc.html

[Q79] 字符串拼接
来源：http://dali.haohaochexian.top/Article/details/gtpffzymhg.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.chenlongwang.top/Article/details/gtqnqxkuum.html

[Q80] 字符串截取
来源：http://dali.daxiang520.top/Article/details/gtalwarhkz.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.hywenlv.cn/Article/details/gtrmaimjru.html

[Q81] 字符串替换
来源：http://dali.kuanghao11.cn/Article/details/gtlfgevkrx.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gtczuwsyen.html

[Q82] 字符长度与字节长度
来源：http://dali.cqqwz.cn/Article/details/gtifyudats.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.pycfn.com/Article/details/gtdlhgywga.html

[Q83] 大小写转换
来源：http://dali.daria6918.cn/Article/details/gttwdtiaqh.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.jinqigufen.top/Article/details/gtrazakivv.html

[Q84] 去除首尾空格
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdsbszjwm.html

SELECT TRIM(name) FROM users;
来源：http://dali.tianlin.xyz/Article/details/gtkaqezora.html

[Q85] 数值取整
来源：http://dali.snrcjt.cn/Article/details/gtxdpbnzlg.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.yueranfly.top/Article/details/gtjaftxydi.html

[Q86] 读取 JSON 字段
来源：http://dali.sweek.top/Article/details/gtqyiicrft.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gtdbtjomgs.html

[Q87] JSON 字段做条件
来源：http://dali.chenzaomai.com/Article/details/gtcapcakph.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.kuanghao11.cn/Article/details/gtldbwuetq.html

[Q88] 行转列（条件聚合）
来源：http://dali.xuetiantiany.cn/Article/details/gtrptgfsjj.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.hnxiangtu.top/Article/details/gtxlpqqbcc.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.hfpthk.cn/Article/details/gtddgmyjbs.html

[Q89] 判断表是否存在
来源：http://dali.yvedp.cn/Article/details/gtizjtnhae.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.yongpay.top/Article/details/gtprrlhzqd.html

[Q90] 生成序号列
来源：http://dali.zdqjudy.top/Article/details/gtrlxvtzli.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.nanxinkj.top/Article/details/gtbnzjyceq.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtnrakxbtm.html

R. Bash 专题
来源：http://dali.cheryme.top/Article/details/gtwemnquiv.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtsozwzble.html

[R01] shebang 与严格模式
来源：http://dali.yueranfly.top/Article/details/gtqqxwnafs.html

#!/usr/bin/env bash
来源：http://dali.dianchejie.cn/Article/details/gtocwxjxvr.html

set -euo pipefail
来源：http://dali.dashuyun.cn/Article/details/gtqyjzvlwv.html

[R02] 变量赋值与使用
来源：http://dali.daria6918.cn/Article/details/gtfwnchrgd.html

name="Tom"; echo "$name"
来源：http://dali.gzhubu.top/Article/details/gtftbmbeej.html

[R03] 只读变量
来源：http://dali.iojbl.cn/Article/details/gtygjykgvm.html

readonly PI=3.14
来源：http://dali.gzhubu.top/Article/details/gtyxkpngkr.html

[R04] 位置参数
来源：http://dali.dashuyun.cn/Article/details/gtzbxscret.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.sxryk.cn/Article/details/gttgiqloal.html

[R05] 参数默认值
来源：http://dali.yuxming.cn/Article/details/gtovsagtze.html

name="${1:-default}"
来源：http://dali.pengpengdd.cyou/Article/details/gtdmcojlkm.html

[R06] 判断命令是否存在
来源：http://dali.zdqjudy.top/Article/details/gthsqcelsb.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.dianchejie.cn/Article/details/gtlbjknqno.html

[R07] if 判断文件
来源：http://dali.xuanzx.com/Article/details/gtuusiwgnu.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.gotoacloud.top/Article/details/gtbpwphpry.html

[R08] 数值比较
来源：http://dali.wangshuangyany.cn/Article/details/gthtdoeafw.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.cashguo.top/Article/details/gteqfitmok.html

[R09] 字符串比较
来源：http://dali.svipenyu.cn/Article/details/gtsmynyufe.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.svipenyu.cn/Article/details/gtyvregktm.html

[R10] 正则匹配
来源：http://dali.ywan-chungtsiang.top/Article/details/gttglcvqph.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.ybcxt.top/Article/details/gtbbaxhfxd.html

[R11] case 多分支
来源：http://dali.hysaishi.cn/Article/details/gtgrwtbifi.html

case "$1" in
来源：http://dali.xinyue.icu/Article/details/gtvjafzfiz.html

start) echo "启动" ;;
来源：http://dali.chenzaomai.com/Article/details/gtyhsqxwnt.html

stop)  echo "停止" ;;
来源：http://dali.chenzaomai.com/Article/details/gtfyrqdvvr.html

*)     echo "未知命令" ;;
来源：http://dali.hfpthk.cn/Article/details/gtuowfbkwk.html

esac
来源：http://dali.xuanzx.com/Article/details/gtfbakwbnl.html

[R12] for 遍历文件
来源：http://dali.shzxlz.cn/Article/details/gtctzpkebz.html

for f in *.txt; do echo "$f"; done
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxfzdexjl.html

[R13] for 计数循环
来源：http://dali.tianlin.xyz/Article/details/gtrcisfxxs.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.wangshuangyany.cn/Article/details/gtkrrrfaas.html

[R14] C 风格 for
来源：http://dali.ywan-chungtsiang.top/Article/details/gtopnapmhd.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.birdmap.top/Article/details/gthyvklbpz.html

[R15] while 逐行读文件
来源：http://dali.yuxming.cn/Article/details/gtyoqvhsuk.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.yongpay.top/Article/details/gthodobyaw.html

[R16] until 等待条件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjfynktfg.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.yj20258.top/Article/details/gtnnfnhgca.html

[R17] 数组定义与取值
来源：http://dali.kuanghao11.cn/Article/details/gtaqebrlpo.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrxcvrxwv.html

[R18] 遍历数组
来源：http://dali.nanxuanxn.top/Article/details/gtkwayqfmh.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.jianghu66.top/Article/details/gtevgpeqzv.html

[R19] 数组长度
来源：http://dali.c1oappe.top/Article/details/gtiifowydq.html

echo "${#arr[@]}"
来源：http://dali.jqgufenzy.top/Article/details/gtlwylpsjm.html

[R20] 关联数组（字典）
来源：http://dali.jlsjyb.cn/Article/details/gtvfmcnwob.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.gzhubu.top/Article/details/gtchnggnyz.html

[R21] 字符串长度
来源：http://dali.xuetiantiany.cn/Article/details/gtuureyvue.html

echo "${#s}"
来源：http://dali.yuanzhike.top/Article/details/gtyoctlxgm.html

[R22] 截取子串
来源：http://dali.yj202588.top/Article/details/gtnswkdvlc.html

echo "${s:0:5}"
来源：http://dali.chenjidiqi.icu/Article/details/gtviqvqvdi.html

[R23] 字符串替换
来源：http://dali.chenlongwang.top/Article/details/gtuvjdqtbe.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.yanxiufei.cn/Article/details/gtzkhpmypt.html

[R24] 大小写转换
来源：http://dali.tanke756.top/Article/details/gttgylfqhn.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.redwolf501.top/Article/details/gtsjeyqtje.html

[R25] 去后缀 / 去前缀
来源：http://dali.cashguo.top/Article/details/gtqvflrrip.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.cucudq.cn/Article/details/gtohhnzlpl.html

[R26] 命令替换
来源：http://dali.c1oappe.top/Article/details/gtyfcbbsep.html

now=$(date +%F); echo "$now"
来源：http://dali.yonumen.top/Article/details/gtbqlaksix.html

[R27] 算术展开
来源：http://dali.yvedp.cn/Article/details/gtwqirugcu.html

echo $((1 + 2 * 3))
来源：http://dali.gaohongyu789.top/Article/details/gttwwizkdq.html

[R28] 浮点运算
来源：http://dali.jinyuanbaomall.cn/Article/details/gtquzsfexp.html

echo "scale=2; 10/3" | bc
来源：http://dali.svipenyu.cn/Article/details/gthbkgeari.html

[R29] 定义函数
来源：http://dali.bjfxy.top/Article/details/gtxmrnvslt.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.jinqigufen.top/Article/details/gtbxnqoloj.html

[R30] 函数返回状态码
来源：http://dali.hfpthk.cn/Article/details/gtzbnttpfn.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.jqgfzy.top/Article/details/gtskhbpzhl.html

[R31] 局部变量
来源：http://dali.yangfankeji.com/Article/details/gtbhktgzow.html

f() { local x=1; echo "$x"; }
来源：http://dali.hnxiangtu.top/Article/details/gtlqfslhsh.html

[R32] 参数个数校验
来源：http://dali.svipenyu.cn/Article/details/gtlhnnjcyp.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.feifeiyinyue.top/Article/details/gtyixslrfu.html

[R33] 捕获错误并提示行号
来源：http://dali.yongpay.top/Article/details/gtzrdeejqe.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.shzxlz.cn/Article/details/gtzjiuxzsf.html

[R34] 退出时清理
来源：http://dali.shanyushiyangkeji.top/Article/details/gtydjafluw.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.xylfe.cn/Article/details/gtwdyyqpza.html

[R35] 后台执行并等待
来源：http://dali.jianghu66.top/Article/details/gtecebwlbo.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.guannengcc.top/Article/details/gtrvlwzoex.html

[R36] 并发执行多个任务
来源：http://dali.xziqi.cn/Article/details/gtnygsyciv.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.kuanghao11.cn/Article/details/gtsiybrozz.html

[R37] 把输出赋给变量
来源：http://dali.xinyue.icu/Article/details/gtdzgixeah.html

files=$(ls -1)
来源：http://dali.yuxming.cn/Article/details/gtxnciqllr.html

[R38] 管道串联
来源：http://dali.haohaochexian.top/Article/details/gthdcssggl.html

cat a.txt | grep -i error | wc -l
来源：http://dali.fengsongda.top/Article/details/gtwjftmmzy.html

[R39] 重定向标准输出与错误
来源：http://dali.hfpthk.cn/Article/details/gtzureahgp.html

cmd > out.log 2>&1
来源：http://dali.vqdsnc.cn/Article/details/gtnkklbpbq.html

[R40] 追加写日志
来源：http://dali.ybcxt.top/Article/details/gtfccsxsvg.html

echo "log" >> out.log
来源：http://dali.yanxiufei.cn/Article/details/gtmllmovie.html

[R41] 丢弃输出
来源：http://dali.gaohongyu789.top/Article/details/gtuytcgndm.html

cmd >/dev/null 2>&1
来源：http://dali.smart0.xyz/Article/details/gtsogjqgaw.html

[R42] 输入重定向
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwwtdqixc.html

wc -l < a.txt
来源：http://dali.jinqigfzy.top/Article/details/gtrxqxnfsl.html

[R43] 按名字查找文件
来源：http://dali.sxryk.cn/Article/details/gtqtcqlqai.html

find . -name "*.log" -type f
来源：http://dali.c1oappe.top/Article/details/gtlyqcuahl.html

[R44] 按修改时间查找
来源：http://dali.aizwys.cn/Article/details/gthzmnaxva.html

find . -mtime -7 -type f
来源：http://dali.jqgufenzy.top/Article/details/gtjyteecxl.html

[R45] 批量删除
来源：http://dali.chenlongwang.top/Article/details/gtlgofjflb.html

find . -name "*.tmp" -delete
来源：http://dali.yj20258.top/Article/details/gtzbzkjwrp.html

[R46] 递归替换文件内容
来源：http://dali.nanxinkj.top/Article/details/gthnxfaftu.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.yuanzhike.top/Article/details/gtiauyldnw.html

[R47] sed 单行替换
来源：http://dali.iojbl.cn/Article/details/gtqumlqvyi.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhixingplan.top/Article/details/gttjdoqdir.html

[R48] awk 取指定列
来源：http://dali.yangfankeji.com/Article/details/gtkxcrnjtx.html

awk '{print $1, $3}' a.txt
来源：http://dali.tanke756.top/Article/details/gtiewbzatd.html

[R49] awk 带条件
来源：http://dali.jiagoushi.top/Article/details/gtkvxypzim.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.wangdashe.top/Article/details/gtmfyaxori.html

[R50] awk 求和
来源：http://dali.hywenlv.cn/Article/details/gtygocujsh.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.hongshengwenyu.top/Article/details/gtbrgmoxhu.html

[R51] 排序去重取前几
来源：http://dali.zhengqikj.top/Article/details/gtonqtazef.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.sxryk.cn/Article/details/gtvaabywuq.html

[R52] 统计行数
来源：http://dali.fzhhl.top/Article/details/gtxmxcbvde.html

wc -l a.txt
来源：http://dali.ydzc1.top/Article/details/gtaxxjjksn.html

[R53] 查看文件头与实时尾
来源：http://dali.yangfankeji.com/Article/details/gthkpyieir.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.tanke756.top/Article/details/gtsasmcfbn.html

[R54] 比较两个文件
来源：http://dali.zycfv.cn/Article/details/gtfcfsgpal.html

diff a.txt b.txt
来源：http://dali.hysaishi.cn/Article/details/gtrkpcncyi.html

[R55] 压缩与解压
来源：http://dali.zhengqikj.top/Article/details/gtiaqincdr.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.aizwys.cn/Article/details/gtdfhatawv.html

[R56] 远程拷贝
来源：http://dali.yj202588.top/Article/details/gtzorwdekj.html

scp file user@host:/path/
来源：http://dali.wangshuangyany.cn/Article/details/gtpjiyunsl.html

[R57] 远程执行命令
来源：http://dali.quarkkingdee.top/Article/details/gtnmzqcyxx.html

ssh user@host 'uptime'
来源：http://dali.ehwqpu.com/Article/details/gtxfugvlvf.html

[R58] 下载文件
来源：http://dali.shangyingyoupin.top/Article/details/gtopextmhw.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpcpvefhf.html

[R59] 发 POST JSON
来源：http://dali.sxryk.cn/Article/details/gthmrixtla.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.ydzc1.top/Article/details/gtqyqogxkg.html

[R60] 只看 HTTP 状态码
来源：http://dali.shanyushiyangkeji.top/Article/details/gtffwmgmmh.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.yj202588.top/Article/details/gtwvirwbxs.html

[R61] 磁盘占用
来源：http://dali.yuxming.cn/Article/details/gthwmirbkd.html

df -h;  du -sh *
来源：http://dali.guowangkeji.top/Article/details/gthlegeqfe.html

[R62] 找最占空间的文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzipjvvhy.html

du -ah . | sort -rh | head -10
来源：http://dali.jqgufenzy.top/Article/details/gtxqlbpuez.html

[R63] 内存与进程
来源：http://dali.shangyingyoupin.top/Article/details/gtefrvubts.html

free -h;  ps aux | grep nginx
来源：http://dali.wangshuangyany.cn/Article/details/gtqaonkjcw.html

[R64] 结束进程
来源：http://dali.jinghuilouyu.cn/Article/details/gtkgtqynii.html

kill -9 $(pgrep -f app.py)
来源：http://dali.xinyue.icu/Article/details/gtuaycxftm.html

[R65] 查看端口占用
来源：http://dali.feifeiyinyue.top/Article/details/gtlbchxtrl.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.yj20258.top/Article/details/gttqgltdxe.html

[R66] 定时任务
来源：http://dali.yongpay.top/Article/details/gtnthxqnce.html

crontab -e;  crontab -l
来源：http://dali.guannengcc.top/Article/details/gtqtmzjnqy.html

[R67] 生成随机十六进制串
来源：http://dali.hywenlv.cn/Article/details/gtpjlywjnj.html

openssl rand -hex 16
来源：http://dali.pycfn.com/Article/details/gtftkwuanw.html

[R68] 计算文件校验值
来源：http://dali.cdnleiting.top/Article/details/gtrjdlxyax.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.pycfn.com/Article/details/gtdwhsidwj.html

[R69] 生成随机密码
来源：http://dali.hnxiangtu.top/Article/details/gtrqavsmqz.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhiwuduotai.top/Article/details/gtxrhumwgz.html

[R70] 时间戳与互转
来源：http://dali.jianghu66.top/Article/details/gtkykeprwr.html

date +%s;  date -d @1700000000
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzvzpurnd.html

[R71] 日期格式化
来源：http://dali.iojbl.cn/Article/details/gtxxydllpd.html


<!-- 参考信息 -->