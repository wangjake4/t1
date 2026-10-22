代发 wailian999

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.yueranfly.top/Article/details/gt2oaufphkg.html

[Q26] 计数
来源：http://dali.smart0.xyz/Article/details/gt2setogpxz.html

SELECT COUNT(*) FROM users;
来源：http://dali.jianghu66.top/Article/details/gt2qmhmphvs.html

[Q27] 条件计数
来源：http://dali.0kj1m.cn/Article/details/gt2fdsygnpk.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zsaxvlvr.html

[Q28] 求和与平均
来源：http://dali.nwbrower.top/Article/details/gt2nlmmwrug.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.hammf.cn/Article/details/gt2zlybxujy.html

[Q29] 最大最小值
来源：http://dali.jinqigfzy.top/Article/details/gt2qgrsgzec.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.andypj.xyz/Article/details/gt2nbzxgznm.html

[Q30] 分组统计
来源：http://dali.jlsjyb.cn/Article/details/gt2ircupwyu.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2przncrvc.html

[Q31] 分组后过滤
来源：http://dali.jyoumei.cn/Article/details/gt2ebraxbpa.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.fzhhl.top/Article/details/gt2nwxjxyzt.html

[Q32] 分组拼接字符串
来源：http://dali.jinqigfzy.top/Article/details/gt2cmmrujkr.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.jlsjyb.cn/Article/details/gt2gsylkqtf.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.iojbl.cn/Article/details/gt2ctkcinuh.html

[Q33] 多列分组
来源：http://dali.hfpthk.cn/Article/details/gt2omcztvxp.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.daria6918.cn/Article/details/gt2kqhrokwh.html

[Q34] 每组取第一条
来源：http://dali.guowangkeji.top/Article/details/gt2ubizopbc.html

SELECT * FROM (
来源：http://dali.cashguo.top/Article/details/gt2qucihpdj.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.shzxlz.cn/Article/details/gt2dwrcqyqy.html

) t WHERE rn = 1;
来源：http://dali.yuxming.cn/Article/details/gt2qphvllen.html

[Q35] 内连接
来源：http://dali.havefunace.top/Article/details/gt2gzuiaori.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.jlsjyb.cn/Article/details/gt2lvwjtfmk.html

[Q36] 左连接
来源：http://dali.xuetiantiany.cn/Article/details/gt2awfkgkgr.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.hammf.cn/Article/details/gt2atfzliqt.html

[Q37] 右连接
来源：http://dali.svipenyu.cn/Article/details/gt2ycqoffxp.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.jinqigufen.top/Article/details/gt2uraaaztl.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhoulong.xyz/Article/details/gt2slbgtgnf.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.aizwys.cn/Article/details/gt2pesxjtqf.html

[Q39] 自连接（查上下级）
来源：http://dali.xylfe.cn/Article/details/gt2zteeyead.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.shuidangran.top/Article/details/gt2hhxqudjy.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.xuanzx.com/Article/details/gt2rwzcusma.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.yj20258.top/Article/details/gt2uyyzjvww.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.feifeiyinyue.top/Article/details/gt2jvjudiac.html

[Q41] 多表连接
来源：http://dali.shuidangran.top/Article/details/gt2rjyyvwko.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhongyouzk.top/Article/details/gt2ztpmdybl.html

JOIN users u ON u.id = o.user_id
来源：http://dali.shangyingyoupin.top/Article/details/gt2epzjhldp.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.chenjidiqi.icu/Article/details/gt2sqbkljbf.html

[Q42] 连接条件附加过滤
来源：http://dali.zhoulong.xyz/Article/details/gt2qsgeksfg.html

SELECT u.name, o.amount FROM users u
来源：http://dali.xuanzx.com/Article/details/gt2hxoyscdw.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.hysaishi.cn/Article/details/gt2cbrjrsmn.html

[Q43] 标量子查询
来源：http://dali.quarkkingdee.top/Article/details/gt2fhljehrj.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhoulong.xyz/Article/details/gt2aaxtannv.html

[Q44] IN 子查询
来源：http://dali.meibo888.top/Article/details/gt2lavbqeks.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.snrcjt.cn/Article/details/gt2hjksicoc.html

[Q45] EXISTS 判断存在
来源：http://dali.jinqigufen.top/Article/details/gt2lpwoadln.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhongyouzk.top/Article/details/gt2ujmhwsoj.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.feifeiyinyue.top/Article/details/gt2vkboxhpl.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhongyouzk.top/Article/details/gt2lyfvusad.html

[Q47] 与平均值比较
来源：http://dali.xuetiantiany.cn/Article/details/gt2gtkplipm.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.shangyingyoupin.top/Article/details/gt2jxigeatb.html

[Q48] CTE 公用表表达式
来源：http://dali.nwbrower.top/Article/details/gt2dxquwymh.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tnkatbul.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.pengpengdd.cyou/Article/details/gt2smwjgxda.html

[Q49] 更新单行
来源：http://dali.jinqigfzy.top/Article/details/gt2fhrhjrlz.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhongyouzk.top/Article/details/gt2krjrkdki.html

[Q50] 批量更新
来源：http://dali.zdqjudy.top/Article/details/gt2ukdumobs.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.andypj.xyz/Article/details/gt2csvmxjum.html

[Q51] 用子查询更新
来源：http://dali.ybcxt.top/Article/details/gt2akteyvks.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.guannengcc.top/Article/details/gt2synjqjry.html

[Q52] 删除指定行
来源：http://dali.shzxlz.cn/Article/details/gt2smqqgthd.html

DELETE FROM users WHERE id = 10;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kdhqharp.html

[Q53] 按条件删除
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bquhvgqs.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2trbesdvt.html

[Q54] 清空表
来源：http://dali.ppjwa.cn/Article/details/gt2talkbcvw.html

TRUNCATE TABLE logs;
来源：http://dali.c1oappe.top/Article/details/gt2nvjvsdcx.html

[Q55] 排名（并列占位）
来源：http://dali.yangfankeji.com/Article/details/gt2hukgabfx.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.gzhubu.top/Article/details/gt2lwkixvtw.html

[Q56] 密集排名（并列不占位）
来源：http://dali.mhx1999.top/Article/details/gt2ofpnwddq.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2mzarphlv.html

[Q57] 行号
来源：http://dali.yangfankeji.com/Article/details/gt2hptjkhap.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.quarkkingdee.top/Article/details/gt2vacrdibc.html

[Q58] 累计求和
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bdeikdpe.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.cqqwz.cn/Article/details/gt2djhenstn.html

[Q59] 分组内累计
来源：http://dali.jiagoushi.top/Article/details/gt2ecnccqmn.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.yonumen.top/Article/details/gt2glolmooj.html

[Q60] 取上一行 / 下一行
来源：http://dali.guowangkeji.top/Article/details/gt2scdprwjy.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.cucudq.cn/Article/details/gt2ezfsktls.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.ehwqpu.com/Article/details/gt2hiaeqpkm.html

[Q61] 移动平均
来源：http://dali.havefunace.top/Article/details/gt2yfxbwdyp.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.gaohongyu789.top/Article/details/gt2ftflczwg.html

[Q62] 分组占比
来源：http://dali.fzhhl.top/Article/details/gt2itwghgsi.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.birdmap.top/Article/details/gt2gtowakpf.html

[Q63] 开启事务
来源：http://dali.nwbrower.top/Article/details/gt2qyaglhwh.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.jinqigfzy.top/Article/details/gt2dihhycms.html

[Q64] 提交事务
来源：http://dali.zhoulong.xyz/Article/details/gt2ulkvjtjx.html

COMMIT;
来源：http://dali.zdqjudy.top/Article/details/gt2cdovxbia.html

[Q65] 回滚事务
来源：http://dali.9152youxi.cn/Article/details/gt2tmyxxezk.html

ROLLBACK;
来源：http://dali.daxiang520.top/Article/details/gt2rlvuuhqo.html

[Q66] 行锁查询
来源：http://dali.zycfv.cn/Article/details/gt2xlfvjfva.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.chenjidiqi.icu/Article/details/gt2yyddufqp.html

[Q67] 设置隔离级别
来源：http://dali.sysykeji.top/Article/details/gt2vyzisjoz.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.jianghu66.top/Article/details/gt2urfnaudg.html

[Q68] 保存点
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ushkaphw.html

SAVEPOINT sp1;
来源：http://dali.xuanzx.com/Article/details/gt2sbjgxhug.html

ROLLBACK TO sp1;
来源：http://dali.cqqwz.cn/Article/details/gt2cdhqtsin.html

[Q69] 查看执行计划
来源：http://dali.gaohongyu789.top/Article/details/gt2mzkpozdm.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.kuanghao11.cn/Article/details/gt2upsloogz.html

[Q70] 更新统计信息
来源：http://dali.316326.xyz/Article/details/gt2pzyuffjl.html

ANALYZE TABLE users;
来源：http://dali.havefunace.top/Article/details/gt2ofblzfsa.html

[Q71] 查看建表语句
来源：http://dali.ivvv.top/Article/details/gt2bwmddndc.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.yonumen.top/Article/details/gt2fvauaowo.html

[Q72] 查看索引
来源：http://dali.pengpengdd.cyou/Article/details/gt2otbrgxmh.html

SHOW INDEX FROM users;
来源：http://dali.wangdashe.top/Article/details/gt2eivkmpew.html

[Q73] 查看表状态
来源：http://dali.zhengqikj.top/Article/details/gt2jalsiqcg.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.yuxming.cn/Article/details/gt2oztvzlpb.html

[Q74] 强制使用索引
来源：http://dali.cheryme.top/Article/details/gt2dzfraxhk.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.guowangkeji.top/Article/details/gt2pnkfdvmt.html

[Q75] 日期格式化
来源：http://dali.c1oappe.top/Article/details/gt2tqyxxnyq.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.yuxming.cn/Article/details/gt2dqqqoahz.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zdqjudy.top/Article/details/gt2kpadkyvj.html

[Q76] 按天统计
来源：http://dali.yueranfly.top/Article/details/gt2gusysjio.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.dashuyun.cn/Article/details/gt2lszpiolc.html

[Q77] 时间加减
来源：http://dali.chenlongwang.top/Article/details/gt2jhmgfzep.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.aizwys.cn/Article/details/gt2waesqekk.html

[Q78] 当前时间
来源：http://dali.fengsongda.top/Article/details/gt2xyxlnqgs.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zatcoxxt.html

[Q79] 字符串拼接
来源：http://dali.zdqjudy.top/Article/details/gt2kysljkma.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.jinqigufen.top/Article/details/gt2iskzmgzv.html

[Q80] 字符串截取
来源：http://dali.yj20258.top/Article/details/gt2mwlhlnvl.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.nanxinkj.top/Article/details/gt2otknqfty.html

[Q81] 字符串替换
来源：http://dali.xziqi.cn/Article/details/gt2ggaxfpcw.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gt2klqvfyjk.html

[Q82] 字符长度与字节长度
来源：http://dali.haohaochexian.top/Article/details/gt2poujqfiq.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.yvedp.cn/Article/details/gt2cxhtyhnc.html

[Q83] 大小写转换
来源：http://dali.xuanzx.com/Article/details/gt2djddbyol.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.jlsjyb.cn/Article/details/gt2ljkhcjzg.html

[Q84] 去除首尾空格
来源：http://dali.shuidangran.top/Article/details/gt2imkphveu.html

SELECT TRIM(name) FROM users;
来源：http://dali.dianchejie.cn/Article/details/gt2sndnevnr.html

[Q85] 数值取整
来源：http://dali.yj202588.top/Article/details/gt2xqxhqqpn.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.redwolf501.top/Article/details/gt2eoibtytf.html

[Q86] 读取 JSON 字段
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bqtqfjku.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.sweek.top/Article/details/gt2stckdywz.html

[Q87] JSON 字段做条件
来源：http://dali.havefunace.top/Article/details/gt2ltvcxhvc.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.tian-w.cn/Article/details/gt2uojhnbvz.html

[Q88] 行转列（条件聚合）
来源：http://dali.fzhhl.top/Article/details/gt2zvyjsnln.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.aibaodan.cn/Article/details/gt2bacolely.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.nanxinkj.top/Article/details/gt2iolmbbof.html

[Q89] 判断表是否存在
来源：http://dali.ybcxt.top/Article/details/gt2ptomivaa.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.hfpthk.cn/Article/details/gt2ebgryvhk.html

[Q90] 生成序号列
来源：http://dali.fengsongda.top/Article/details/gt2pjjqczkt.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.yongpay.top/Article/details/gt2wwvsmgqs.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2dunaucyu.html

R. Bash 专题
来源：http://dali.daxiang520.top/Article/details/gt2jcxxiyhx.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2soneqmjy.html

[R01] shebang 与严格模式
来源：http://dali.yj20258888.top/Article/details/gt2noakfdjn.html

#!/usr/bin/env bash
来源：http://dali.ppjwa.cn/Article/details/gt2yzibquol.html

set -euo pipefail
来源：http://dali.cheryme.top/Article/details/gt2ilojeilg.html

[R02] 变量赋值与使用
来源：http://dali.0kj1m.cn/Article/details/gt2eabyqvdn.html

name="Tom"; echo "$name"
来源：http://dali.mhx1999.top/Article/details/gt2xyxkihge.html

[R03] 只读变量
来源：http://dali.xziqi.cn/Article/details/gt2pevmjhof.html

readonly PI=3.14
来源：http://dali.zhixingplan.top/Article/details/gt2bccdlron.html

[R04] 位置参数
来源：http://dali.jyoumei.cn/Article/details/gt2onauohpw.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2semygcyy.html

[R05] 参数默认值
来源：http://dali.zhongyouzk.top/Article/details/gt2lyjlfiou.html

name="${1:-default}"
来源：http://dali.daria6918.cn/Article/details/gt2zsvrgswg.html

[R06] 判断命令是否存在
来源：http://dali.shuidangran.top/Article/details/gt2cafcncxo.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.yonumen.top/Article/details/gt2fiyrkmek.html

[R07] if 判断文件
来源：http://dali.gaohongyu789.top/Article/details/gt2dhttriig.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.nwbrower.top/Article/details/gt2qnyfmmpa.html

[R08] 数值比较
来源：http://dali.hysaishi.cn/Article/details/gt2tbaxckdy.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.chenjidiqi.icu/Article/details/gt2xblfivvf.html

[R09] 字符串比较
来源：http://dali.daria6918.cn/Article/details/gt2pdxigsvk.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.fzhhl.top/Article/details/gt2czcrlrin.html

[R10] 正则匹配
来源：http://dali.hywenlv.cn/Article/details/gt2xkoxczxa.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.hnqzz.top/Article/details/gt2uhidxzua.html

[R11] case 多分支
来源：http://dali.vqdsnc.cn/Article/details/gt2tjeemkcv.html

case "$1" in
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cqtyjhmn.html

start) echo "启动" ;;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2coqoknaf.html

stop)  echo "停止" ;;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ndulktxz.html

*)     echo "未知命令" ;;
来源：http://dali.fzhhl.top/Article/details/gt2kempearn.html

esac
来源：http://dali.aibaodan.cn/Article/details/gt2pitmaemk.html

[R12] for 遍历文件
来源：http://dali.jyoumei.cn/Article/details/gt2ldzpebbh.html

for f in *.txt; do echo "$f"; done
来源：http://dali.hywenlv.cn/Article/details/gt2apshvgcz.html

[R13] for 计数循环
来源：http://dali.fzhhl.top/Article/details/gt2mbyrpfch.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.shuidangran.top/Article/details/gt2jjsarukq.html

[R14] C 风格 for
来源：http://dali.pycfn.com/Article/details/gt2tjfxerxk.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.sysykeji.top/Article/details/gt2fhkyqiti.html

[R15] while 逐行读文件
来源：http://dali.yanxiufei.cn/Article/details/gt2crykcozl.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.xuanzx.com/Article/details/gt2mudbplnh.html

[R16] until 等待条件
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wfjwzmmm.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.9152youxi.cn/Article/details/gt2fovbmpyr.html

[R17] 数组定义与取值
来源：http://dali.ivvv.top/Article/details/gt2wqtozpfe.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.birdmap.top/Article/details/gt2xnjnxirx.html

[R18] 遍历数组
来源：http://dali.fengsongda.top/Article/details/gt2lfsdzwnx.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.cdnleiting.top/Article/details/gt2kfhjqprd.html

[R19] 数组长度
来源：http://dali.gotoacloud.top/Article/details/gt2vnryhwwt.html

echo "${#arr[@]}"
来源：http://dali.feifeiyinyue.top/Article/details/gt2dtksgbym.html

[R20] 关联数组（字典）
来源：http://dali.nanxinkj.top/Article/details/gt2dnwcwvuv.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.xinyue.icu/Article/details/gt2dinnnvrs.html

[R21] 字符串长度
来源：http://dali.ydzc1.top/Article/details/gt2wpphxsat.html

echo "${#s}"
来源：http://dali.jqgufenzy.top/Article/details/gt2scrpjmxo.html

[R22] 截取子串
来源：http://dali.yanxiufei.cn/Article/details/gt2vhnnnyjl.html

echo "${s:0:5}"
来源：http://dali.guannengcc.top/Article/details/gt2ipgscdut.html

[R23] 字符串替换
来源：http://dali.kuanghao11.cn/Article/details/gt2zpqkagyb.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.nwbrower.top/Article/details/gt2pgjzjcpw.html

[R24] 大小写转换
来源：http://dali.hfpthk.cn/Article/details/gt2xhwtikun.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.cheryme.top/Article/details/gt2kluejnbr.html

[R25] 去后缀 / 去前缀
来源：http://dali.shuidangran.top/Article/details/gt2dkdugjqj.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.havefunace.top/Article/details/gt2omyjcoqa.html

[R26] 命令替换
来源：http://dali.zycfv.cn/Article/details/gt2kamgqmly.html

now=$(date +%F); echo "$now"
来源：http://dali.gaohongyu789.top/Article/details/gt2vxouxwap.html

[R27] 算术展开
来源：http://dali.yongpay.top/Article/details/gt2fyanuxib.html

echo $((1 + 2 * 3))
来源：http://dali.guannengcc.top/Article/details/gt2kelkjkxg.html

[R28] 浮点运算
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ujkdmtzh.html

echo "scale=2; 10/3" | bc
来源：http://dali.wangshuangyany.cn/Article/details/gt2badyclzy.html

[R29] 定义函数
来源：http://dali.andypj.xyz/Article/details/gt2waapjjfv.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.cqqwz.cn/Article/details/gt2lrztxdys.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2eetiltgd.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.wangdashe.top/Article/details/gt2azthhstd.html

[R31] 局部变量
来源：http://dali.redwolf501.top/Article/details/gt2owrlwubm.html

f() { local x=1; echo "$x"; }
来源：http://dali.hnqzz.top/Article/details/gt2enrlmsbx.html

[R32] 参数个数校验
来源：http://dali.sysykeji.top/Article/details/gt2evrhdyfb.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2jxndqfmq.html

[R33] 捕获错误并提示行号
来源：http://dali.jiagoushi.top/Article/details/gt2catqiklc.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.jianghu66.top/Article/details/gt2dmsvgtpm.html

[R34] 退出时清理
来源：http://dali.xylfe.cn/Article/details/gt2kcjpsjjv.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.feifeiyinyue.top/Article/details/gt2naohygpx.html

[R35] 后台执行并等待
来源：http://dali.yj20258.top/Article/details/gt2nbvodlpg.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2puinizlr.html

[R36] 并发执行多个任务
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pzopodeb.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zdqjudy.top/Article/details/gt2xprqvgep.html

[R37] 把输出赋给变量
来源：http://dali.zhengqikj.top/Article/details/gt2wryufzao.html

files=$(ls -1)
来源：http://dali.jinqigfzy.top/Article/details/gt2mcdoncyt.html

[R38] 管道串联
来源：http://dali.havefunace.top/Article/details/gt2konybotg.html

cat a.txt | grep -i error | wc -l
来源：http://dali.ydzc1.top/Article/details/gt2ixjepdxh.html

[R39] 重定向标准输出与错误
来源：http://dali.zhoulong.xyz/Article/details/gt2jlwhyrso.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2tluveqxg.html

[R40] 追加写日志
来源：http://dali.jqgufenzy.top/Article/details/gt2scvjyebt.html

echo "log" >> out.log
来源：http://dali.sweek.top/Article/details/gt2rifdarpk.html

[R41] 丢弃输出
来源：http://dali.jlsjyb.cn/Article/details/gt2ljensjfn.html

cmd >/dev/null 2>&1
来源：http://dali.aizwys.cn/Article/details/gt2nkgftbfg.html

[R42] 输入重定向
来源：http://dali.hnqzz.top/Article/details/gt2joxltkmt.html

wc -l < a.txt
来源：http://dali.sxryk.cn/Article/details/gt2mzrugkvw.html

[R43] 按名字查找文件
来源：http://dali.jlsjyb.cn/Article/details/gt2fuyararz.html

find . -name "*.log" -type f
来源：http://dali.xinyue.icu/Article/details/gt2eqziwyaq.html

[R44] 按修改时间查找
来源：http://dali.yvedp.cn/Article/details/gt2ibtfaetp.html

find . -mtime -7 -type f
来源：http://dali.hysaishi.cn/Article/details/gt2dfmgjipm.html

[R45] 批量删除
来源：http://dali.hywenlv.cn/Article/details/gt2bktiscfw.html

find . -name "*.tmp" -delete
来源：http://dali.nanxinkj.top/Article/details/gt2lstvrkdu.html

[R46] 递归替换文件内容
来源：http://dali.c1oappe.top/Article/details/gt2ehoqipis.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.ppjwa.cn/Article/details/gt2fvundssi.html

[R47] sed 单行替换
来源：http://dali.cdnleiting.top/Article/details/gt2fjpxockr.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.pengpengdd.cyou/Article/details/gt2fehpllkk.html

[R48] awk 取指定列
来源：http://dali.yonumen.top/Article/details/gt2pcqyizeg.html

awk '{print $1, $3}' a.txt
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2houwttvq.html

[R49] awk 带条件
来源：http://dali.cheryme.top/Article/details/gt2eynpqtfg.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.shuidangran.top/Article/details/gt2ozpuduwg.html

[R50] awk 求和
来源：http://dali.yj20258888.top/Article/details/gt2hjbmcxtd.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vuulmyps.html

[R51] 排序去重取前几
来源：http://dali.dianchejie.cn/Article/details/gt2blmwxkzb.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.jlsjyb.cn/Article/details/gt2vhleeacu.html

[R52] 统计行数
来源：http://dali.jqgufenzy.top/Article/details/gt2tqgdkyip.html

wc -l a.txt
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2eoxozont.html

[R53] 查看文件头与实时尾
来源：http://dali.hywenlv.cn/Article/details/gt2uygumtye.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.guowangkeji.top/Article/details/gt2udptmuwd.html

[R54] 比较两个文件
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fpcyfwzy.html

diff a.txt b.txt
来源：http://dali.hnqzz.top/Article/details/gt2zxdiuthm.html

[R55] 压缩与解压
来源：http://dali.kuanghao11.cn/Article/details/gt2zpnaurva.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.snrcjt.cn/Article/details/gt2zhughcax.html

[R56] 远程拷贝
来源：http://dali.yj20258.top/Article/details/gt2qqfbrske.html

scp file user@host:/path/
来源：http://dali.yj20258888.top/Article/details/gt2sgfrsoaa.html

[R57] 远程执行命令
来源：http://dali.9152youxi.cn/Article/details/gt2ciwcygfn.html

ssh user@host 'uptime'
来源：http://dali.daria6918.cn/Article/details/gt2kgwdeadx.html

[R58] 下载文件
来源：http://dali.cashguo.top/Article/details/gt2mhhwpbce.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.shangyingyoupin.top/Article/details/gt2fpoicxut.html

[R59] 发 POST JSON
来源：http://dali.gaohongyu789.top/Article/details/gt2fburqmrd.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.andypj.xyz/Article/details/gt2ywjwepfi.html

[R60] 只看 HTTP 状态码
来源：http://dali.cdnleiting.top/Article/details/gt2ulgfnyqg.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.havefunace.top/Article/details/gt2nfforert.html

[R61] 磁盘占用
来源：http://dali.iojbl.cn/Article/details/gt2djqsodin.html

df -h;  du -sh *
来源：http://dali.xuetiantiany.cn/Article/details/gt2xybiyjik.html

[R62] 找最占空间的文件
来源：http://dali.jinqigfzy.top/Article/details/gt2trvnfyty.html

du -ah . | sort -rh | head -10
来源：http://dali.ybcxt.top/Article/details/gt2fidyhhod.html

[R63] 内存与进程
来源：http://dali.xinyue.icu/Article/details/gt2wnhjkalq.html

free -h;  ps aux | grep nginx
来源：http://dali.iojbl.cn/Article/details/gt2fvzyqoak.html

[R64] 结束进程
来源：http://dali.yueranfly.top/Article/details/gt2zgmuxwrw.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhengqikj.top/Article/details/gt2nihtszst.html

[R65] 查看端口占用
来源：http://dali.9152youxi.cn/Article/details/gt2znurftsw.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.hongshengwenyu.top/Article/details/gt2davlppqn.html

[R66] 定时任务
来源：http://dali.hywenlv.cn/Article/details/gt2ldeqprvi.html

crontab -e;  crontab -l
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ybadedec.html

[R67] 生成随机十六进制串
来源：http://dali.316326.xyz/Article/details/gt2ogtgwvzg.html

openssl rand -hex 16
来源：http://dali.sxryk.cn/Article/details/gt2nelnwxjn.html

[R68] 计算文件校验值
来源：http://dali.yj202588.top/Article/details/gt2zylbmgqr.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.iojbl.cn/Article/details/gt2tvzelymt.html

[R69] 生成随机密码
来源：http://dali.c1oappe.top/Article/details/gt2hkxcxidt.html

head -c 16 /dev/urandom | base64
来源：http://dali.jqgfzy.top/Article/details/gt2iigulcmp.html

[R70] 时间戳与互转
来源：http://dali.ivvv.top/Article/details/gt2waiipypz.html

date +%s;  date -d @1700000000
来源：http://dali.zdqjudy.top/Article/details/gt2wwhozanz.html

[R71] 日期格式化
来源：http://dali.tianlin.xyz/Article/details/gt2rcxwsxqc.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.redwolf501.top/Article/details/gt2zvrroaun.html

[R72] 等待端口就绪
来源：http://dali.316326.xyz/Article/details/gt2sjebzuub.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.shuidangran.top/Article/details/gt2ukzlvgfd.html

[R73] 分割大日志
来源：http://dali.aizwys.cn/Article/details/gt2fspiomga.html

split -l 1000 big.log part_
来源：http://dali.shuidangran.top/Article/details/gt2wevmdcmk.html

[R74] 批量重命名
来源：http://dali.dashuyun.cn/Article/details/gt2frnxxlfs.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.guowangkeji.top/Article/details/gt2azvphxvk.html

[R75] 导出环境变量
来源：http://dali.vqdsnc.cn/Article/details/gt2oprwdatm.html


<!-- 参考信息 -->