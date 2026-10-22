代发 wailian999

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.chenzaomai.com/Article/details/gt2nuplhaiz.html

[Q18] 模糊匹配
来源：http://dali.quarkkingdee.top/Article/details/gt2kbsejdua.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.chenzaomai.com/Article/details/gt2vbpqezzy.html

[Q19] 范围查询
来源：http://dali.zdqjudy.top/Article/details/gt2wsyvyris.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.xuanzx.com/Article/details/gt2yqgqepxu.html

[Q20] IN 列表
来源：http://dali.9152youxi.cn/Article/details/gt2kxartlhq.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.cdnleiting.top/Article/details/gt2xeljuhgc.html

[Q21] 空值判断
来源：http://dali.haohaochexian.top/Article/details/gt2qkihlmxt.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.bjfxy.top/Article/details/gt2eoubhohv.html

[Q22] 排序
来源：http://dali.shanyushiyangtech.top/Article/details/gt2aivpkqsh.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.yj202588.top/Article/details/gt2xrzuopcd.html

[Q23] 分页
来源：http://dali.jianghu66.top/Article/details/gt2iwkjuxut.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.shzxlz.cn/Article/details/gt2hyilbtmu.html

[Q24] 去重
来源：http://dali.vqdsnc.cn/Article/details/gt2jytwumpn.html

SELECT DISTINCT city FROM users;
来源：http://dali.sufxvd.cn/Article/details/gt2suvcymrr.html

[Q25] 只取前 N 条
来源：http://dali.gzhubu.top/Article/details/gt2qzxnhwxl.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.yuxming.cn/Article/details/gt2dekbftyw.html

[Q26] 计数
来源：http://dali.zhoulong.xyz/Article/details/gt2bzxiypne.html

SELECT COUNT(*) FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hihpyybv.html

[Q27] 条件计数
来源：http://dali.jiagoushi.top/Article/details/gt2oamyjexf.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.guowangkeji.top/Article/details/gt2pzhsexmd.html

[Q28] 求和与平均
来源：http://dali.hongshengwenyu.top/Article/details/gt2wjmnkwiu.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.ivvv.top/Article/details/gt2dzsazxih.html

[Q29] 最大最小值
来源：http://dali.quarkkingdee.top/Article/details/gt2otcknlym.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.hongshengwenyu.top/Article/details/gt2whogseiq.html

[Q30] 分组统计
来源：http://dali.fengsongda.top/Article/details/gt2untytanf.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.sufxvd.cn/Article/details/gt2ilzputcp.html

[Q31] 分组后过滤
来源：http://dali.zdqjudy.top/Article/details/gt2onlmedsb.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.mhx1999.top/Article/details/gt2psabdafa.html

[Q32] 分组拼接字符串
来源：http://dali.meibo888.top/Article/details/gt2uwurystt.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.andypj.xyz/Article/details/gt2prkqpieb.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.vqdsnc.cn/Article/details/gt2kaexhjjs.html

[Q33] 多列分组
来源：http://dali.dashuyun.cn/Article/details/gt2gogyylgv.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.jyoumei.cn/Article/details/gt2dpximirl.html

[Q34] 每组取第一条
来源：http://dali.ivvv.top/Article/details/gt2ejnejdfv.html

SELECT * FROM (
来源：http://dali.jinqigufen.top/Article/details/gt2ogdvwiuf.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.jinqigufen.top/Article/details/gt2tflvtxas.html

) t WHERE rn = 1;
来源：http://dali.c1oappe.top/Article/details/gt2dgvpwijc.html

[Q35] 内连接
来源：http://dali.sufxvd.cn/Article/details/gt2nukwhnow.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.chenlongwang.top/Article/details/gt2veizclvs.html

[Q36] 左连接
来源：http://dali.yj20258888.top/Article/details/gt2stoevisy.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qxmlvcul.html

[Q37] 右连接
来源：http://dali.cashguo.top/Article/details/gt2lrovbqfu.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.cashguo.top/Article/details/gt2rfecavgj.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.ehwqpu.com/Article/details/gt2mrsqurfj.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.sufxvd.cn/Article/details/gt2eghckabh.html

[Q39] 自连接（查上下级）
来源：http://dali.yanxiufei.cn/Article/details/gt2wrtwxaps.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.ybcxt.top/Article/details/gt2egfkmsvm.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.nanxinkj.top/Article/details/gt2udzudeve.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.hnxiangtu.top/Article/details/gt2xgepugms.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.yj20258888.top/Article/details/gt2ighihsow.html

[Q41] 多表连接
来源：http://dali.wangdashe.top/Article/details/gt2blyjnavw.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.smart0.xyz/Article/details/gt2anjutdbd.html

JOIN users u ON u.id = o.user_id
来源：http://dali.gotoacloud.top/Article/details/gt2yzooxjai.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.jyoumei.cn/Article/details/gt2qgsmafzh.html

[Q42] 连接条件附加过滤
来源：http://dali.zhiwuduotai.top/Article/details/gt2vnezjeeq.html

SELECT u.name, o.amount FROM users u
来源：http://dali.hnxiangtu.top/Article/details/gt2owhebuwo.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ojrzzvcd.html

[Q43] 标量子查询
来源：http://dali.birdmap.top/Article/details/gt2svyolawc.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhongyouzk.top/Article/details/gt2ecqtxmxl.html

[Q44] IN 子查询
来源：http://dali.ybcxt.top/Article/details/gt2xkpvcwyt.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.andypj.xyz/Article/details/gt2ktksrmdu.html

[Q45] EXISTS 判断存在
来源：http://dali.hywenlv.cn/Article/details/gt2wnoederb.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.cdnleiting.top/Article/details/gt2bxbygqft.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.aizwys.cn/Article/details/gt2alcfrenf.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.mhx1999.top/Article/details/gt2lbrpgwjl.html

[Q47] 与平均值比较
来源：http://dali.jqgfzy.top/Article/details/gt2hacbtttd.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.yuanzhike.top/Article/details/gt2hlzhtuws.html

[Q48] CTE 公用表表达式
来源：http://dali.sysykeji.top/Article/details/gt2vxcmefqv.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.iojbl.cn/Article/details/gt2nerbwnyr.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.jianghu66.top/Article/details/gt2vfvgjdeg.html

[Q49] 更新单行
来源：http://dali.9152youxi.cn/Article/details/gt2hgmycomw.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.hnqzz.top/Article/details/gt2mpxqpzax.html

[Q50] 批量更新
来源：http://dali.gzhubu.top/Article/details/gt2vmkvllqt.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.jinghuilouyu.cn/Article/details/gt2phxcfjym.html

[Q51] 用子查询更新
来源：http://dali.pycfn.com/Article/details/gt2vooxkszq.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.smart0.xyz/Article/details/gt2nixkvpjo.html

[Q52] 删除指定行
来源：http://dali.iojbl.cn/Article/details/gt2xyrlpsuh.html

DELETE FROM users WHERE id = 10;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2piagxdkb.html

[Q53] 按条件删除
来源：http://dali.yj202588.top/Article/details/gt2exghpxjg.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2coghvgoq.html

[Q54] 清空表
来源：http://dali.aibaodan.cn/Article/details/gt2oqsjrwob.html

TRUNCATE TABLE logs;
来源：http://dali.xuetiantiany.cn/Article/details/gt2jkbbdjgn.html

[Q55] 排名（并列占位）
来源：http://dali.sxryk.cn/Article/details/gt2wvvldqvj.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhixingplan.top/Article/details/gt2wbtgeirj.html

[Q56] 密集排名（并列不占位）
来源：http://dali.ehwqpu.com/Article/details/gt2zvahdxcu.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.yongpay.top/Article/details/gt2whwynosv.html

[Q57] 行号
来源：http://dali.shzxlz.cn/Article/details/gt2znzwijzm.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.gzhubu.top/Article/details/gt2dxrngxsd.html

[Q58] 累计求和
来源：http://dali.hfpthk.cn/Article/details/gt2gbnfhkph.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qccinhgo.html

[Q59] 分组内累计
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ysmlfril.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.jqgfzy.top/Article/details/gt2teenkukz.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhiwuduotai.top/Article/details/gt2plygruwt.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.tian-w.cn/Article/details/gt2kljgpyau.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.vqdsnc.cn/Article/details/gt2lzfbvtuo.html

[Q61] 移动平均
来源：http://dali.aizwys.cn/Article/details/gt2kqromskd.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhoulong.xyz/Article/details/gt2hweiowjo.html

[Q62] 分组占比
来源：http://dali.jianghu66.top/Article/details/gt2migswyhk.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.haohaochexian.top/Article/details/gt2aopvogvv.html

[Q63] 开启事务
来源：http://dali.yuxming.cn/Article/details/gt2kolpiqbv.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.yueranfly.top/Article/details/gt2fcmnvcht.html

[Q64] 提交事务
来源：http://dali.sysykeji.top/Article/details/gt2jhjlbdru.html

COMMIT;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2obqtrewi.html

[Q65] 回滚事务
来源：http://dali.tianlin.xyz/Article/details/gt2eozjxmfk.html

ROLLBACK;
来源：http://dali.sufxvd.cn/Article/details/gt2kfmpsgwh.html

[Q66] 行锁查询
来源：http://dali.andypj.xyz/Article/details/gt2yauvcojx.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhixingplan.top/Article/details/gt2klhwhobz.html

[Q67] 设置隔离级别
来源：http://dali.ivvv.top/Article/details/gt2ioeazluk.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.guannengcc.top/Article/details/gt2mdcshnjj.html

[Q68] 保存点
来源：http://dali.dashuyun.cn/Article/details/gt2ijrlkomv.html

SAVEPOINT sp1;
来源：http://dali.birdmap.top/Article/details/gt2gevvkkdu.html

ROLLBACK TO sp1;
来源：http://dali.jianghu66.top/Article/details/gt2cfyscyst.html

[Q69] 查看执行计划
来源：http://dali.fengsongda.top/Article/details/gt2dvkxmqby.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.redwolf501.top/Article/details/gt2bavxurwx.html

[Q70] 更新统计信息
来源：http://dali.nanxuanxn.top/Article/details/gt2wzloqfvz.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fzypivbc.html

[Q71] 查看建表语句
来源：http://dali.tanke756.top/Article/details/gt2wkqlfzhm.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.chenzaomai.com/Article/details/gt2qyyogznl.html

[Q72] 查看索引
来源：http://dali.yanxiufei.cn/Article/details/gt2acgdvlts.html

SHOW INDEX FROM users;
来源：http://dali.cdnleiting.top/Article/details/gt2sdqcghhf.html

[Q73] 查看表状态
来源：http://dali.hnqzz.top/Article/details/gt2fjkdibng.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.hammf.cn/Article/details/gt2udaucrjl.html

[Q74] 强制使用索引
来源：http://dali.jiagoushi.top/Article/details/gt2qrxnlfqd.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zclpyxpn.html

[Q75] 日期格式化
来源：http://dali.nwbrower.top/Article/details/gt2iykctxxn.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.smart0.xyz/Article/details/gt2wropkkaz.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.gzhubu.top/Article/details/gt2xnuybibx.html

[Q76] 按天统计
来源：http://dali.mhx1999.top/Article/details/gt2dqglavpc.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.jlsjyb.cn/Article/details/gt2ftbbvdxf.html

[Q77] 时间加减
来源：http://dali.c1oappe.top/Article/details/gt2keiosvyb.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.nwbrower.top/Article/details/gt2npnjhjfr.html

[Q78] 当前时间
来源：http://dali.zhiwuduotai.top/Article/details/gt2arbtscsv.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.yanxiufei.cn/Article/details/gt2swlhkpcz.html

[Q79] 字符串拼接
来源：http://dali.iojbl.cn/Article/details/gt2osmxexlj.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.jiagoushi.top/Article/details/gt2jbtkolte.html

[Q80] 字符串截取
来源：http://dali.dianchejie.cn/Article/details/gt2xbpeyyxh.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.fzhhl.top/Article/details/gt2czbefhqj.html

[Q81] 字符串替换
来源：http://dali.hongshengwenyu.top/Article/details/gt2uyxoloru.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.bjfxy.top/Article/details/gt2diztulug.html

[Q82] 字符长度与字节长度
来源：http://dali.gotoacloud.top/Article/details/gt2snknfdfz.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.jqgfzy.top/Article/details/gt2qfkctpgx.html

[Q83] 大小写转换
来源：http://dali.svipenyu.cn/Article/details/gt2kkvsucvj.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.yongpay.top/Article/details/gt2kfvyxkpu.html

[Q84] 去除首尾空格
来源：http://dali.cucudq.cn/Article/details/gt2jedypnpb.html

SELECT TRIM(name) FROM users;
来源：http://dali.fzhhl.top/Article/details/gt2urpmatvo.html

[Q85] 数值取整
来源：http://dali.sweek.top/Article/details/gt2mifdrutt.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.ivvv.top/Article/details/gt2xrwbgtym.html

[Q86] 读取 JSON 字段
来源：http://dali.redwolf501.top/Article/details/gt2wvqspgsf.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.cashguo.top/Article/details/gt2xpansfxw.html

[Q87] JSON 字段做条件
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jyyldrgw.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.gogol.net.cn/Article/details/gt2qpebibnh.html

[Q88] 行转列（条件聚合）
来源：http://dali.fengsongda.top/Article/details/gt2vrjqohfg.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.meibo888.top/Article/details/gt2rvcgmhga.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tlnugzwh.html

[Q89] 判断表是否存在
来源：http://dali.0kj1m.cn/Article/details/gt2upmfkbmv.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.yj20258.top/Article/details/gt2ciukjdoa.html

[Q90] 生成序号列
来源：http://dali.zhengqikj.top/Article/details/gt2oakuxfpg.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.aibaodan.cn/Article/details/gt2brbmzmcv.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2dpvsovzi.html

R. Bash 专题
来源：http://dali.sweek.top/Article/details/gt2nhuznrns.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2lfrmhgpo.html

[R01] shebang 与严格模式
来源：http://dali.kuanghao11.cn/Article/details/gt2srycland.html

#!/usr/bin/env bash
来源：http://dali.aibaodan.cn/Article/details/gt2diaaxows.html

set -euo pipefail
来源：http://dali.hnqzz.top/Article/details/gt2deowzxkx.html

[R02] 变量赋值与使用
来源：http://dali.nanxuanxn.top/Article/details/gt2ojhjvkdu.html

name="Tom"; echo "$name"
来源：http://dali.zhengqikj.top/Article/details/gt2lfhzynqe.html

[R03] 只读变量
来源：http://dali.dianchejie.cn/Article/details/gt2bevdvizc.html

readonly PI=3.14
来源：http://dali.shuidangran.top/Article/details/gt2xqpbapsp.html

[R04] 位置参数
来源：http://dali.snrcjt.cn/Article/details/gt2hiwbfyjo.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.jqgufenzy.top/Article/details/gt2jcxixarp.html

[R05] 参数默认值
来源：http://dali.feifeiyinyue.top/Article/details/gt2llhdogmy.html

name="${1:-default}"
来源：http://dali.daxiang520.top/Article/details/gt2aryohksa.html

[R06] 判断命令是否存在
来源：http://dali.havefunace.top/Article/details/gt2zklvtnbz.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.guowangkeji.top/Article/details/gt2afrankcw.html

[R07] if 判断文件
来源：http://dali.tanke756.top/Article/details/gt2yovgzxcq.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.pycfn.com/Article/details/gt2fskmvjjq.html

[R08] 数值比较
来源：http://dali.iojbl.cn/Article/details/gt2dmbvpfrz.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.316326.xyz/Article/details/gt2ftnjjpsv.html

[R09] 字符串比较
来源：http://dali.gogol.net.cn/Article/details/gt2iufdsyun.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xhyliurv.html

[R10] 正则匹配
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vllxiftv.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.snrcjt.cn/Article/details/gt2igpowgkm.html

[R11] case 多分支
来源：http://dali.quarkkingdee.top/Article/details/gt2tacifoiw.html

case "$1" in
来源：http://dali.fzhhl.top/Article/details/gt2jbpvhbul.html

start) echo "启动" ;;
来源：http://dali.kuanghao11.cn/Article/details/gt2bzujfdfq.html

stop)  echo "停止" ;;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qpvlnfua.html

*)     echo "未知命令" ;;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2aqslnzwb.html

esac
来源：http://dali.xuanzx.com/Article/details/gt2ngguscsr.html

[R12] for 遍历文件
来源：http://dali.c1oappe.top/Article/details/gt2nzxklywd.html

for f in *.txt; do echo "$f"; done
来源：http://dali.jiagoushi.top/Article/details/gt2zaubkwag.html

[R13] for 计数循环
来源：http://dali.jinqigufen.top/Article/details/gt2ctimswwx.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.tian-w.cn/Article/details/gt2dibxjtlr.html

[R14] C 风格 for
来源：http://dali.aizwys.cn/Article/details/gt2urucogcx.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.gogol.net.cn/Article/details/gt2anxcrhnw.html

[R15] while 逐行读文件
来源：http://dali.zhongyouzk.top/Article/details/gt2ejjxbhpf.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2uxjtqmik.html

[R16] until 等待条件
来源：http://dali.tianlin.xyz/Article/details/gt2hkxlmfnd.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.nanxinkj.top/Article/details/gt2usfjecaw.html

[R17] 数组定义与取值
来源：http://dali.jinqigufen.top/Article/details/gt2htrbgwts.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wknzakjb.html

[R18] 遍历数组
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rmoxurpa.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.hongshengwenyu.top/Article/details/gt2xjtdyxer.html

[R19] 数组长度
来源：http://dali.xylfe.cn/Article/details/gt2qlpihtpd.html

echo "${#arr[@]}"
来源：http://dali.smart0.xyz/Article/details/gt2deoszsze.html

[R20] 关联数组（字典）
来源：http://dali.ydzc1.top/Article/details/gt2rfcgxlzx.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.jianghu66.top/Article/details/gt2owfcwczq.html

[R21] 字符串长度
来源：http://dali.havefunace.top/Article/details/gt2xjyrbanp.html

echo "${#s}"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kvsqyfov.html

[R22] 截取子串
来源：http://dali.cucudq.cn/Article/details/gt2bcyevlez.html

echo "${s:0:5}"
来源：http://dali.aibaodan.cn/Article/details/gt2xongzepk.html

[R23] 字符串替换
来源：http://dali.hysaishi.cn/Article/details/gt2ykkyrnye.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.birdmap.top/Article/details/gt2hdupxkpm.html

[R24] 大小写转换
来源：http://dali.hnqzz.top/Article/details/gt2jbepdogp.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2upqznyed.html

[R25] 去后缀 / 去前缀
来源：http://dali.nwbrower.top/Article/details/gt2awdakxtn.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.wangdashe.top/Article/details/gt2nyadttwm.html

[R26] 命令替换
来源：http://dali.cqqwz.cn/Article/details/gt2xjmzqhwm.html

now=$(date +%F); echo "$now"
来源：http://dali.gzhubu.top/Article/details/gt2txzruonc.html

[R27] 算术展开
来源：http://dali.tian-w.cn/Article/details/gt2bmvexapz.html

echo $((1 + 2 * 3))
来源：http://dali.dashuyun.cn/Article/details/gt2gpesnqpk.html

[R28] 浮点运算
来源：http://dali.zycfv.cn/Article/details/gt2xpgqygrl.html

echo "scale=2; 10/3" | bc
来源：http://dali.dashuyun.cn/Article/details/gt2ihawjztl.html

[R29] 定义函数
来源：http://dali.xuanzx.com/Article/details/gt2mpmyosqb.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.birdmap.top/Article/details/gt2zmqfummi.html

[R30] 函数返回状态码
来源：http://dali.bjfxy.top/Article/details/gt2vxdewofe.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.ppjwa.cn/Article/details/gt2bdydxbhu.html

[R31] 局部变量
来源：http://dali.chenlongwang.top/Article/details/gt2sraepfev.html

f() { local x=1; echo "$x"; }
来源：http://dali.hysaishi.cn/Article/details/gt2tgeacgvo.html

[R32] 参数个数校验
来源：http://dali.hywenlv.cn/Article/details/gt2wajmzwhw.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.xuanzx.com/Article/details/gt2tcqirogd.html

[R33] 捕获错误并提示行号
来源：http://dali.9152youxi.cn/Article/details/gt2uwksdgpe.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.redwolf501.top/Article/details/gt2kvdfvlzq.html

[R34] 退出时清理
来源：http://dali.havefunace.top/Article/details/gt2qagjcqvy.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.chenjidiqi.icu/Article/details/gt2uyqqsfrk.html

[R35] 后台执行并等待
来源：http://dali.jinqigufen.top/Article/details/gt2vmyjbgbp.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.havefunace.top/Article/details/gt2bhfokdpz.html

[R36] 并发执行多个任务
来源：http://dali.jianghu66.top/Article/details/gt2ucrdcmjr.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.nwbrower.top/Article/details/gt2oqjgktey.html

[R37] 把输出赋给变量
来源：http://dali.cucudq.cn/Article/details/gt2rrsbxjps.html

files=$(ls -1)
来源：http://dali.9152youxi.cn/Article/details/gt2lrpebjxy.html

[R38] 管道串联
来源：http://dali.tian-w.cn/Article/details/gt2xjtmgwel.html

cat a.txt | grep -i error | wc -l
来源：http://dali.yangfankeji.com/Article/details/gt2hokmoexb.html

[R39] 重定向标准输出与错误
来源：http://dali.gzhubu.top/Article/details/gt2uhtmvdpy.html

cmd > out.log 2>&1
来源：http://dali.svipenyu.cn/Article/details/gt2uqdctjbg.html

[R40] 追加写日志
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bcsgglsr.html

echo "log" >> out.log
来源：http://dali.yuanzhike.top/Article/details/gt2lbhnrfxz.html

[R41] 丢弃输出
来源：http://dali.jinqigfzy.top/Article/details/gt2wnxiwxrt.html

cmd >/dev/null 2>&1
来源：http://dali.zhiwuduotai.top/Article/details/gt2vrdnsvxp.html

[R42] 输入重定向
来源：http://dali.gzhubu.top/Article/details/gt2lzovwvau.html

wc -l < a.txt
来源：http://dali.pengpengdd.cyou/Article/details/gt2wvlrmdiu.html

[R43] 按名字查找文件
来源：http://dali.jqgufenzy.top/Article/details/gt2gbyocijq.html

find . -name "*.log" -type f
来源：http://dali.ppjwa.cn/Article/details/gt2qtmbtisg.html

[R44] 按修改时间查找
来源：http://dali.guowangkeji.top/Article/details/gt2eorvxyel.html

find . -mtime -7 -type f
来源：http://dali.snrcjt.cn/Article/details/gt2gqtntlhk.html

[R45] 批量删除
来源：http://dali.zhongyouzk.top/Article/details/gt2wjnbaugc.html

find . -name "*.tmp" -delete
来源：http://dali.yj202588.top/Article/details/gt2rsilrsan.html

[R46] 递归替换文件内容
来源：http://dali.zhixingplan.top/Article/details/gt2ucjxrkdq.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.dianchejie.cn/Article/details/gt2iszelndc.html

[R47] sed 单行替换
来源：http://dali.gotoacloud.top/Article/details/gt2zerlsngt.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.tianlin.xyz/Article/details/gt2hkkvnrte.html

[R48] awk 取指定列
来源：http://dali.ppjwa.cn/Article/details/gt2pkydcckv.html

awk '{print $1, $3}' a.txt
来源：http://dali.yvedp.cn/Article/details/gt2taiqjdhs.html

[R49] awk 带条件
来源：http://dali.smart0.xyz/Article/details/gt2csmdnbef.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.nanxuanxn.top/Article/details/gt2eoyarmfk.html

[R50] awk 求和
来源：http://dali.316326.xyz/Article/details/gt2ymzbtzie.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.xinyue.icu/Article/details/gt2ggecvorx.html

[R51] 排序去重取前几
来源：http://dali.gotoacloud.top/Article/details/gt2yceudbom.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.chenlongwang.top/Article/details/gt2upoijzzn.html

[R52] 统计行数
来源：http://dali.iojbl.cn/Article/details/gt2kedfadgn.html

wc -l a.txt
来源：http://dali.gogol.net.cn/Article/details/gt2cwrojvui.html

[R53] 查看文件头与实时尾
来源：http://dali.tanke756.top/Article/details/gt2jcamurvu.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zdqjudy.top/Article/details/gt2modkiwce.html

[R54] 比较两个文件
来源：http://dali.zhengqikj.top/Article/details/gt2phtkiiul.html

diff a.txt b.txt
来源：http://dali.cashguo.top/Article/details/gt2bkxsfaas.html

[R55] 压缩与解压
来源：http://dali.hysaishi.cn/Article/details/gt2gcipcgix.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.bjfxy.top/Article/details/gt2dmwdcfsp.html

[R56] 远程拷贝
来源：http://dali.hnxiangtu.top/Article/details/gt2nrrkxdmr.html

scp file user@host:/path/
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vxkqqbvp.html

[R57] 远程执行命令
来源：http://dali.fzhhl.top/Article/details/gt2ekpjpkdy.html

ssh user@host 'uptime'
来源：http://dali.zhoulong.xyz/Article/details/gt2psmagotx.html

[R58] 下载文件
来源：http://dali.sufxvd.cn/Article/details/gt2wqcacxxn.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.dianchejie.cn/Article/details/gt2dnhetalj.html

[R59] 发 POST JSON
来源：http://dali.gaohongyu789.top/Article/details/gt2ufdpqfrb.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.hysaishi.cn/Article/details/gt2pngkypjm.html

[R60] 只看 HTTP 状态码
来源：http://dali.hywenlv.cn/Article/details/gt2spmxtoat.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.feifeiyinyue.top/Article/details/gt2ebpznebv.html

[R61] 磁盘占用
来源：http://dali.jinqigfzy.top/Article/details/gt2ewtfeuth.html

df -h;  du -sh *
来源：http://dali.redwolf501.top/Article/details/gt2bqpsvpsg.html

[R62] 找最占空间的文件
来源：http://dali.yongpay.top/Article/details/gt2bglmgtol.html

du -ah . | sort -rh | head -10
来源：http://dali.zdqjudy.top/Article/details/gt2ewjawlgt.html

[R63] 内存与进程
来源：http://dali.sufxvd.cn/Article/details/gt2tplmfglz.html

free -h;  ps aux | grep nginx
来源：http://dali.hnxiangtu.top/Article/details/gt2ygdxeecn.html

[R64] 结束进程
来源：http://dali.chenlongwang.top/Article/details/gt2upqykeok.html

kill -9 $(pgrep -f app.py)
来源：http://dali.yongpay.top/Article/details/gt2igtxypsh.html

[R65] 查看端口占用
来源：http://dali.svipenyu.cn/Article/details/gt2lsxftyjf.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ywfmojjv.html

[R66] 定时任务
来源：http://dali.hnqzz.top/Article/details/gt2mytvysbl.html

crontab -e;  crontab -l
来源：http://dali.yongpay.top/Article/details/gt2rcjpxqrg.html

[R67] 生成随机十六进制串
来源：http://dali.ybcxt.top/Article/details/gt2yrrswvty.html


<!-- 参考信息 -->