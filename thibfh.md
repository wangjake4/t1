代发 wailian999

SELECT * FROM users;
来源：http://dali.jianghu66.top/Article/details/gtlphupzen.html

[Q16] 查询指定列
来源：http://dali.quarkkingdee.top/Article/details/gtcrhokqar.html

SELECT id, name FROM users;
来源：http://dali.daria6918.cn/Article/details/gtbrlkjpaj.html

[Q17] 条件查询
来源：http://dali.feifeiyinyue.top/Article/details/gtjcsjrzpr.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gtogokrcjs.html

[Q18] 模糊匹配
来源：http://dali.hammf.cn/Article/details/gtxomlapvn.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnkxjqior.html

[Q19] 范围查询
来源：http://dali.aizwys.cn/Article/details/gtkbhghtuq.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.shuidangran.top/Article/details/gtdiqfddhw.html

[Q20] IN 列表
来源：http://dali.sxryk.cn/Article/details/gtkyouarvg.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.chenjidiqi.icu/Article/details/gtdeacyfsy.html

[Q21] 空值判断
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyeevkuvn.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.xylfe.cn/Article/details/gtunbptetj.html

[Q22] 排序
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtllwtmtex.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.yuanzhike.top/Article/details/gtvecupuif.html

[Q23] 分页
来源：http://dali.yvedp.cn/Article/details/gtzgybazck.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.jyoumei.cn/Article/details/gtfziiyibp.html

[Q24] 去重
来源：http://dali.yvedp.cn/Article/details/gteufsdnpn.html

SELECT DISTINCT city FROM users;
来源：http://dali.bjfxy.top/Article/details/gtwlluoyjp.html

[Q25] 只取前 N 条
来源：http://dali.yj20258.top/Article/details/gttwrhnudq.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.xuetiantiany.cn/Article/details/gtexwqeqdg.html

[Q26] 计数
来源：http://dali.fengsongda.top/Article/details/gttdgiebpf.html

SELECT COUNT(*) FROM users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwbwtagib.html

[Q27] 条件计数
来源：http://dali.smart0.xyz/Article/details/gtnprvgthc.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.jiagoushi.top/Article/details/gtjxxphrsc.html

[Q28] 求和与平均
来源：http://dali.hysaishi.cn/Article/details/gtkdtijnjv.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.daxiang520.top/Article/details/gtkipxgvwk.html

[Q29] 最大最小值
来源：http://dali.nanxuanxn.top/Article/details/gtueipehfz.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.chenzaomai.com/Article/details/gtywuhorqz.html

[Q30] 分组统计
来源：http://dali.shuidangran.top/Article/details/gtlydwurnd.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.yanxiufei.cn/Article/details/gtfwcntlve.html

[Q31] 分组后过滤
来源：http://dali.bjfxy.top/Article/details/gtedjgtjaj.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhoulong.xyz/Article/details/gtldvbcbwr.html

[Q32] 分组拼接字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmyvlsmxm.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.cucudq.cn/Article/details/gtofqkxfow.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.birdmap.top/Article/details/gtvocjufhv.html

[Q33] 多列分组
来源：http://dali.tianlin.xyz/Article/details/gtyzsuwfyz.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gtpqgmrgxe.html

[Q34] 每组取第一条
来源：http://dali.pengpengdd.cyou/Article/details/gtbfnfhhxu.html

SELECT * FROM (
来源：http://dali.fzhhl.top/Article/details/gtfutwqtzw.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.jqgfzy.top/Article/details/gtslphfirb.html

) t WHERE rn = 1;
来源：http://dali.wangshuangyany.cn/Article/details/gtxjrhocrb.html

[Q35] 内连接
来源：http://dali.gogol.net.cn/Article/details/gtzttehpyf.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.pycfn.com/Article/details/gtfnvttqpv.html

[Q36] 左连接
来源：http://dali.ybcxt.top/Article/details/gtewhwobeh.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.xylfe.cn/Article/details/gtjzpqbwzl.html

[Q37] 右连接
来源：http://dali.0kj1m.cn/Article/details/gtuusdzmso.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.andypj.xyz/Article/details/gtvdcgudsu.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.yj20258.top/Article/details/gtiuzefwcq.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.xylfe.cn/Article/details/gtfazxlbxy.html

[Q39] 自连接（查上下级）
来源：http://dali.cqqwz.cn/Article/details/gtzzzrcqwl.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.iojbl.cn/Article/details/gtckkrucyq.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtddrvzbzj.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhiwuduotai.top/Article/details/gtajhvigma.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.shuidangran.top/Article/details/gthvzmowoa.html

[Q41] 多表连接
来源：http://dali.daxiang520.top/Article/details/gtuztceqqm.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zycfv.cn/Article/details/gtbdnoaztb.html

JOIN users u ON u.id = o.user_id
来源：http://dali.gogol.net.cn/Article/details/gttojetdsf.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.gzhubu.top/Article/details/gtorkjbwvj.html

[Q42] 连接条件附加过滤
来源：http://dali.hongshengwenyu.top/Article/details/gtxgayxeyc.html

SELECT u.name, o.amount FROM users u
来源：http://dali.chenjidiqi.icu/Article/details/gtlpuykjeu.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.chenzaomai.com/Article/details/gtqnywopdz.html

[Q43] 标量子查询
来源：http://dali.hywenlv.cn/Article/details/gtrpmzccso.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.chenjidiqi.icu/Article/details/gtxjlknwhw.html

[Q44] IN 子查询
来源：http://dali.yj20258888.top/Article/details/gtaimioppn.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.xylfe.cn/Article/details/gtvzcbyddh.html

[Q45] EXISTS 判断存在
来源：http://dali.andypj.xyz/Article/details/gteurgqlka.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.xinyue.icu/Article/details/gtvfsfaqwb.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.daxiang520.top/Article/details/gtitvyqope.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.mhx1999.top/Article/details/gtjjtivrjm.html

[Q47] 与平均值比较
来源：http://dali.pycfn.com/Article/details/gtlsgurvjc.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.sweek.top/Article/details/gtqvbdzwug.html

[Q48] CTE 公用表表达式
来源：http://dali.andypj.xyz/Article/details/gtohrqzzgk.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.ehwqpu.com/Article/details/gthlzjnaph.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhoulong.xyz/Article/details/gtvnhizvnr.html

[Q49] 更新单行
来源：http://dali.aizwys.cn/Article/details/gthoehbtxw.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhoulong.xyz/Article/details/gtnvqtdhuj.html

[Q50] 批量更新
来源：http://dali.mhx1999.top/Article/details/gtnsjkffgh.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.ybcxt.top/Article/details/gtydmrvvno.html

[Q51] 用子查询更新
来源：http://dali.jinghuilouyu.cn/Article/details/gtpsnaxacr.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.9152youxi.cn/Article/details/gtwpwozujn.html

[Q52] 删除指定行
来源：http://dali.haohaochexian.top/Article/details/gtgmjhayik.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zycfv.cn/Article/details/gthkrgnltz.html

[Q53] 按条件删除
来源：http://dali.316326.xyz/Article/details/gtarxsninf.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnnhbiufy.html

[Q54] 清空表
来源：http://dali.cdnleiting.top/Article/details/gtnflpcajy.html

TRUNCATE TABLE logs;
来源：http://dali.gzhubu.top/Article/details/gtpskrnouw.html

[Q55] 排名（并列占位）
来源：http://dali.cucudq.cn/Article/details/gtwwpnejgs.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.yj20258.top/Article/details/gtismizejm.html

[Q56] 密集排名（并列不占位）
来源：http://dali.chenzaomai.com/Article/details/gtikfhadny.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.xuetiantiany.cn/Article/details/gthmwzwhit.html

[Q57] 行号
来源：http://dali.feifeiyinyue.top/Article/details/gtcwmijxlr.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvgsgvezo.html

[Q58] 累计求和
来源：http://dali.pycfn.com/Article/details/gtfzjwhzex.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.meibo888.top/Article/details/gttwnagmda.html

[Q59] 分组内累计
来源：http://dali.shzxlz.cn/Article/details/gtajzucqcm.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.havefunace.top/Article/details/gtlkjllokw.html

[Q60] 取上一行 / 下一行
来源：http://dali.ywan-chungtsiang.top/Article/details/gtypexpbju.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbofqegwr.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.fengsongda.top/Article/details/gtkjcgjjni.html

[Q61] 移动平均
来源：http://dali.hywenlv.cn/Article/details/gtlqsasemt.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.yonumen.top/Article/details/gtqeeglvcc.html

[Q62] 分组占比
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdhmkbxgz.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.tianlin.xyz/Article/details/gtvujceztv.html

[Q63] 开启事务
来源：http://dali.ehwqpu.com/Article/details/gtwtxtgisb.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.0kj1m.cn/Article/details/gtkxoysvvm.html

[Q64] 提交事务
来源：http://dali.hammf.cn/Article/details/gtkfewxtqc.html

COMMIT;
来源：http://dali.dashuyun.cn/Article/details/gtmwlpohsx.html

[Q65] 回滚事务
来源：http://dali.jyoumei.cn/Article/details/gtasnvixbb.html

ROLLBACK;
来源：http://dali.quarkkingdee.top/Article/details/gtemospfxm.html

[Q66] 行锁查询
来源：http://dali.shzxlz.cn/Article/details/gtlamodzcp.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.jinghuilouyu.cn/Article/details/gtaljduhhn.html

[Q67] 设置隔离级别
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmsdxmqey.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.jiagoushi.top/Article/details/gtefindrtb.html

[Q68] 保存点
来源：http://dali.aibaodan.cn/Article/details/gtlrbrkcxx.html

SAVEPOINT sp1;
来源：http://dali.jinghuilouyu.cn/Article/details/gtdgnjnmqm.html

ROLLBACK TO sp1;
来源：http://dali.yanxiufei.cn/Article/details/gtyenucfva.html

[Q69] 查看执行计划
来源：http://dali.zhixingplan.top/Article/details/gtxhgekjpq.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.chenlongwang.top/Article/details/gtyfmvjejb.html

[Q70] 更新统计信息
来源：http://dali.ehwqpu.com/Article/details/gtqslinyas.html

ANALYZE TABLE users;
来源：http://dali.redwolf501.top/Article/details/gtowxicxcl.html

[Q71] 查看建表语句
来源：http://dali.nanxinkj.top/Article/details/gtvoaivurt.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.yvedp.cn/Article/details/gtipqcbfqu.html

[Q72] 查看索引
来源：http://dali.yuxming.cn/Article/details/gtpsscfumx.html

SHOW INDEX FROM users;
来源：http://dali.cheryme.top/Article/details/gtgzerpyqw.html

[Q73] 查看表状态
来源：http://dali.ivvv.top/Article/details/gtgctopjhh.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.yuxming.cn/Article/details/gtlepggjzi.html

[Q74] 强制使用索引
来源：http://dali.jinghuilouyu.cn/Article/details/gtupntmkvw.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.cashguo.top/Article/details/gtzsdcbeew.html

[Q75] 日期格式化
来源：http://dali.kuanghao11.cn/Article/details/gtostgacbj.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.dianchejie.cn/Article/details/gtldazgrih.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.jlsjyb.cn/Article/details/gtrlioliso.html

[Q76] 按天统计
来源：http://dali.aizwys.cn/Article/details/gtjdeughay.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.svipenyu.cn/Article/details/gtwctwpvvy.html

[Q77] 时间加减
来源：http://dali.yongpay.top/Article/details/gtclvoddlz.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.jyoumei.cn/Article/details/gtzbwydoan.html

[Q78] 当前时间
来源：http://dali.jqgfzy.top/Article/details/gtbnveqnnh.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.wangdashe.top/Article/details/gtclwsmpli.html

[Q79] 字符串拼接
来源：http://dali.cqqwz.cn/Article/details/gtvyybebjh.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.316326.xyz/Article/details/gtekpblbeh.html

[Q80] 字符串截取
来源：http://dali.dianchejie.cn/Article/details/gttsyevimm.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.guannengcc.top/Article/details/gttbgjkrpy.html

[Q81] 字符串替换
来源：http://dali.316326.xyz/Article/details/gtojctcgiy.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.tian-w.cn/Article/details/gthnxgiwgg.html

[Q82] 字符长度与字节长度
来源：http://dali.kuanghao11.cn/Article/details/gthrwbjfhe.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.mhx1999.top/Article/details/gtzgibkkbv.html

[Q83] 大小写转换
来源：http://dali.svipenyu.cn/Article/details/gtjgxddrkb.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.nwbrower.top/Article/details/gtplnlisgt.html

[Q84] 去除首尾空格
来源：http://dali.hywenlv.cn/Article/details/gtovydtnhj.html

SELECT TRIM(name) FROM users;
来源：http://dali.dashuyun.cn/Article/details/gtlsgiihed.html

[Q85] 数值取整
来源：http://dali.zhiwuduotai.top/Article/details/gtkwybvlie.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.wangshuangyany.cn/Article/details/gtcvljusdm.html

[Q86] 读取 JSON 字段
来源：http://dali.fzhhl.top/Article/details/gtkbykwwlw.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.cucudq.cn/Article/details/gtfywvpord.html

[Q87] JSON 字段做条件
来源：http://dali.xinyue.icu/Article/details/gtxuhykvhc.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.yangfankeji.com/Article/details/gtzurfuarl.html

[Q88] 行转列（条件聚合）
来源：http://dali.hnxiangtu.top/Article/details/gtshwidwzv.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.cashguo.top/Article/details/gtrlmkfyyh.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.chenzaomai.com/Article/details/gthfdngfsq.html

[Q89] 判断表是否存在
来源：http://dali.andypj.xyz/Article/details/gtaqaeutik.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.hnqzz.top/Article/details/gtorjvckbz.html

[Q90] 生成序号列
来源：http://dali.sxryk.cn/Article/details/gtaqhjahbh.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.sysykeji.top/Article/details/gtpamnytgk.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtjwdjfzqc.html

R. Bash 专题
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpvidlfkn.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gthhtpgrre.html

[R01] shebang 与严格模式
来源：http://dali.yueranfly.top/Article/details/gtboxrkduf.html

#!/usr/bin/env bash
来源：http://dali.ehwqpu.com/Article/details/gtvivcldoh.html

set -euo pipefail
来源：http://dali.mhx1999.top/Article/details/gtbgkkyemq.html

[R02] 变量赋值与使用
来源：http://dali.jinyuanbaomall.cn/Article/details/gtapflugiw.html

name="Tom"; echo "$name"
来源：http://dali.ivvv.top/Article/details/gtxthcyjqj.html

[R03] 只读变量
来源：http://dali.vqdsnc.cn/Article/details/gtjywdwuek.html

readonly PI=3.14
来源：http://dali.cdnleiting.top/Article/details/gtmlwmhjlp.html

[R04] 位置参数
来源：http://dali.wangshuangyany.cn/Article/details/gtmkiaxysn.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.gaohongyu789.top/Article/details/gtqadlycpa.html

[R05] 参数默认值
来源：http://dali.tanke756.top/Article/details/gtdllmbgcl.html

name="${1:-default}"
来源：http://dali.c1oappe.top/Article/details/gttuybdllq.html

[R06] 判断命令是否存在
来源：http://dali.zhixingplan.top/Article/details/gtgliybxda.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.tanke756.top/Article/details/gtdoxtlpos.html

[R07] if 判断文件
来源：http://dali.haohaochexian.top/Article/details/gtxuqzesvm.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.ivvv.top/Article/details/gtezfcccpi.html

[R08] 数值比较
来源：http://dali.zhiwuduotai.top/Article/details/gtnwdhwqei.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.gogol.net.cn/Article/details/gthlvqixif.html

[R09] 字符串比较
来源：http://dali.daria6918.cn/Article/details/gtkcajdqgb.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.guannengcc.top/Article/details/gtumynakhg.html

[R10] 正则匹配
来源：http://dali.aibaodan.cn/Article/details/gtfaxptzjs.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.hfpthk.cn/Article/details/gthqsklkbx.html

[R11] case 多分支
来源：http://dali.jyoumei.cn/Article/details/gtbxhjnnql.html

case "$1" in
来源：http://dali.vqdsnc.cn/Article/details/gtphygwxqt.html

start) echo "启动" ;;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcabatlhf.html

stop)  echo "停止" ;;
来源：http://dali.sufxvd.cn/Article/details/gtekfybsev.html

*)     echo "未知命令" ;;
来源：http://dali.hammf.cn/Article/details/gtzeplketd.html

esac
来源：http://dali.yuanzhike.top/Article/details/gtjnzekrtu.html

[R12] for 遍历文件
来源：http://dali.fzhhl.top/Article/details/gtnqzgqlsv.html

for f in *.txt; do echo "$f"; done
来源：http://dali.yuxming.cn/Article/details/gtvfcypspb.html

[R13] for 计数循环
来源：http://dali.guowangkeji.top/Article/details/gtkumottcc.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.sufxvd.cn/Article/details/gtneafmgaw.html

[R14] C 风格 for
来源：http://dali.mhx1999.top/Article/details/gtdrarofqh.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.ivvv.top/Article/details/gtymybddqg.html

[R15] while 逐行读文件
来源：http://dali.gaohongyu789.top/Article/details/gtskoyflyg.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.xziqi.cn/Article/details/gtfckprdir.html

[R16] until 等待条件
来源：http://dali.yj202588.top/Article/details/gtixkazpcx.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.shzxlz.cn/Article/details/gtvltgoxdp.html

[R17] 数组定义与取值
来源：http://dali.mhx1999.top/Article/details/gtxfauwciv.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.havefunace.top/Article/details/gtsalkuqdz.html

[R18] 遍历数组
来源：http://dali.yj202588.top/Article/details/gtmygiumtu.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.guowangkeji.top/Article/details/gtnfepsstn.html

[R19] 数组长度
来源：http://dali.cashguo.top/Article/details/gtbqbfzjip.html

echo "${#arr[@]}"
来源：http://dali.chenlongwang.top/Article/details/gtttmfylwd.html

[R20] 关联数组（字典）
来源：http://dali.cdnleiting.top/Article/details/gtntvcppjp.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.316326.xyz/Article/details/gtgjjqrrjq.html

[R21] 字符串长度
来源：http://dali.wangdashe.top/Article/details/gtkhrackwe.html

echo "${#s}"
来源：http://dali.0kj1m.cn/Article/details/gtsxowcntz.html

[R22] 截取子串
来源：http://dali.hfpthk.cn/Article/details/gthihshvfb.html

echo "${s:0:5}"
来源：http://dali.shanyushiyangtech.top/Article/details/gtosjpmzou.html

[R23] 字符串替换
来源：http://dali.yvedp.cn/Article/details/gtocelxecl.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.jinqigfzy.top/Article/details/gtuibpyqhq.html

[R24] 大小写转换
来源：http://dali.chenlongwang.top/Article/details/gtuqktphmb.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.xziqi.cn/Article/details/gtjbjudier.html

[R25] 去后缀 / 去前缀
来源：http://dali.shangyingyoupin.top/Article/details/gttbryagoi.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.yueranfly.top/Article/details/gtxetctmmb.html

[R26] 命令替换
来源：http://dali.shangyingyoupin.top/Article/details/gtycnbbpzc.html

now=$(date +%F); echo "$now"
来源：http://dali.nwbrower.top/Article/details/gtxbsxnofb.html

[R27] 算术展开
来源：http://dali.bjfxy.top/Article/details/gtxoqiubgc.html

echo $((1 + 2 * 3))
来源：http://dali.cdnleiting.top/Article/details/gtxzvpwbpv.html

[R28] 浮点运算
来源：http://dali.feifeiyinyue.top/Article/details/gtxertyols.html

echo "scale=2; 10/3" | bc
来源：http://dali.birdmap.top/Article/details/gtwspwoira.html

[R29] 定义函数
来源：http://dali.hnxiangtu.top/Article/details/gtwjkfrsph.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.xinyue.icu/Article/details/gtndvxxohd.html

[R30] 函数返回状态码
来源：http://dali.ppjwa.cn/Article/details/gteriiwdcg.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.tanke756.top/Article/details/gtasnzbomr.html

[R31] 局部变量
来源：http://dali.chenzaomai.com/Article/details/gtaaqgzkxi.html

f() { local x=1; echo "$x"; }
来源：http://dali.chenlongwang.top/Article/details/gtobftkroa.html

[R32] 参数个数校验
来源：http://dali.jyoumei.cn/Article/details/gtgljnyjaz.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.ivvv.top/Article/details/gtcbzlffgl.html

[R33] 捕获错误并提示行号
来源：http://dali.chenlongwang.top/Article/details/gtjwyejlpr.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.havefunace.top/Article/details/gttipjagjq.html

[R34] 退出时清理
来源：http://dali.aibaodan.cn/Article/details/gtinwrfnfj.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhixingplan.top/Article/details/gtcxrntvpg.html

[R35] 后台执行并等待
来源：http://dali.vqdsnc.cn/Article/details/gtlcjfbuzr.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.xinyue.icu/Article/details/gtzinmoaxv.html

[R36] 并发执行多个任务
来源：http://dali.cdnleiting.top/Article/details/gtmuxrbhzs.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.yuanzhike.top/Article/details/gtxlyxbcic.html

[R37] 把输出赋给变量
来源：http://dali.zhengqikj.top/Article/details/gtjgxnvzcw.html

files=$(ls -1)
来源：http://dali.shangyingyoupin.top/Article/details/gtuqvxylhk.html

[R38] 管道串联
来源：http://dali.smart0.xyz/Article/details/gtmuvfteoj.html

cat a.txt | grep -i error | wc -l
来源：http://dali.sysykeji.top/Article/details/gtbvdmvnuu.html

[R39] 重定向标准输出与错误
来源：http://dali.316326.xyz/Article/details/gtderlyvul.html

cmd > out.log 2>&1
来源：http://dali.kuanghao11.cn/Article/details/gtiwhwryma.html

[R40] 追加写日志
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwjqqojis.html

echo "log" >> out.log
来源：http://dali.hywenlv.cn/Article/details/gtgofhxmxq.html

[R41] 丢弃输出
来源：http://dali.ehwqpu.com/Article/details/gtzjgxevkl.html

cmd >/dev/null 2>&1
来源：http://dali.ydzc1.top/Article/details/gtymrpkmuk.html

[R42] 输入重定向
来源：http://dali.shangyingyoupin.top/Article/details/gtritsxnmf.html

wc -l < a.txt
来源：http://dali.daxiang520.top/Article/details/gtxulcnksn.html

[R43] 按名字查找文件
来源：http://dali.c1oappe.top/Article/details/gtvglmttpe.html

find . -name "*.log" -type f
来源：http://dali.guowangkeji.top/Article/details/gtsfbnoltr.html

[R44] 按修改时间查找
来源：http://dali.cashguo.top/Article/details/gtwtkfemzp.html

find . -mtime -7 -type f
来源：http://dali.zhengqikj.top/Article/details/gtpfedrphs.html

[R45] 批量删除
来源：http://dali.chenlongwang.top/Article/details/gtprsvlwai.html

find . -name "*.tmp" -delete
来源：http://dali.feifeiyinyue.top/Article/details/gtbisaaagr.html

[R46] 递归替换文件内容
来源：http://dali.quarkkingdee.top/Article/details/gtrytoprlt.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.gaohongyu789.top/Article/details/gtxvsxxasl.html

[R47] sed 单行替换
来源：http://dali.yj20258.top/Article/details/gtmvnvugph.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.svipenyu.cn/Article/details/gtnbhlevvt.html

[R48] awk 取指定列
来源：http://dali.svipenyu.cn/Article/details/gtlicqabqt.html

awk '{print $1, $3}' a.txt
来源：http://dali.kuanghao11.cn/Article/details/gtwizkqgrt.html

[R49] awk 带条件
来源：http://dali.tian-w.cn/Article/details/gtmqpmalcy.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.nwbrower.top/Article/details/gtrbxsfotr.html

[R50] awk 求和
来源：http://dali.cashguo.top/Article/details/gtnqcripuu.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.chenjidiqi.icu/Article/details/gtnsofdmtw.html

[R51] 排序去重取前几
来源：http://dali.xinyue.icu/Article/details/gtlqrswqnc.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.hnxiangtu.top/Article/details/gtkdgnacvz.html

[R52] 统计行数
来源：http://dali.pycfn.com/Article/details/gtzgliexqt.html

wc -l a.txt
来源：http://dali.yonumen.top/Article/details/gtipqykosl.html

[R53] 查看文件头与实时尾
来源：http://dali.yj202588.top/Article/details/gtrlhgiqme.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.hywenlv.cn/Article/details/gtbfpplbfa.html

[R54] 比较两个文件
来源：http://dali.dashuyun.cn/Article/details/gtdmbnyhrp.html

diff a.txt b.txt
来源：http://dali.wangdashe.top/Article/details/gtaipyxpmb.html

[R55] 压缩与解压
来源：http://dali.c1oappe.top/Article/details/gtqohawpny.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.kuanghao11.cn/Article/details/gtklddpicb.html

[R56] 远程拷贝
来源：http://dali.guannengcc.top/Article/details/gtcqgaagea.html

scp file user@host:/path/
来源：http://dali.ehwqpu.com/Article/details/gtpeodxkyn.html

[R57] 远程执行命令
来源：http://dali.aizwys.cn/Article/details/gtlgjmzjxp.html

ssh user@host 'uptime'
来源：http://dali.zycfv.cn/Article/details/gttfwgvlme.html

[R58] 下载文件
来源：http://dali.jlsjyb.cn/Article/details/gtbtzofhgf.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.dianchejie.cn/Article/details/gtormctluv.html

[R59] 发 POST JSON
来源：http://dali.dianchejie.cn/Article/details/gtrmbutovf.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.cheryme.top/Article/details/gttxejqkcy.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhengqikj.top/Article/details/gtdhfptplh.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtksjxlrqq.html

[R61] 磁盘占用
来源：http://dali.yvedp.cn/Article/details/gtvfxxnwhl.html

df -h;  du -sh *
来源：http://dali.guannengcc.top/Article/details/gtudwynsqy.html

[R62] 找最占空间的文件
来源：http://dali.cheryme.top/Article/details/gtmlugczco.html

du -ah . | sort -rh | head -10
来源：http://dali.c1oappe.top/Article/details/gtihzlogew.html

[R63] 内存与进程
来源：http://dali.cheryme.top/Article/details/gtgeszqsgj.html

free -h;  ps aux | grep nginx
来源：http://dali.ydzc1.top/Article/details/gtznszufar.html

[R64] 结束进程
来源：http://dali.redwolf501.top/Article/details/gtqhcusncs.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhixingplan.top/Article/details/gthsjttbye.html

[R65] 查看端口占用
来源：http://dali.yueranfly.top/Article/details/gtfmnavtak.html


<!-- 参考信息 -->