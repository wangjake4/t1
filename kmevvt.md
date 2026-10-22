代发 wailian999

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.nwbrower.top/Article/details/gt2urgdmuen.html

[Q20] IN 列表
来源：http://dali.hysaishi.cn/Article/details/gt2gdyrvlun.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.pycfn.com/Article/details/gt2jcckkwoj.html

[Q21] 空值判断
来源：http://dali.sysykeji.top/Article/details/gt2snltqtqj.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.xziqi.cn/Article/details/gt2wzjqoddo.html

[Q22] 排序
来源：http://dali.svipenyu.cn/Article/details/gt2pcynothf.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.quarkkingdee.top/Article/details/gt2yxogjyhb.html

[Q23] 分页
来源：http://dali.jiagoushi.top/Article/details/gt2kgemrslm.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.xuetiantiany.cn/Article/details/gt2svwntnhs.html

[Q24] 去重
来源：http://dali.hnqzz.top/Article/details/gt2thdjliky.html

SELECT DISTINCT city FROM users;
来源：http://dali.xuanzx.com/Article/details/gt2mnjcbxqk.html

[Q25] 只取前 N 条
来源：http://dali.yangfankeji.com/Article/details/gt2rsiunqgu.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhixingplan.top/Article/details/gt2xbxkqhgz.html

[Q26] 计数
来源：http://dali.wangshuangyany.cn/Article/details/gt2anbcpotg.html

SELECT COUNT(*) FROM users;
来源：http://dali.chenjidiqi.icu/Article/details/gt2nsudctta.html

[Q27] 条件计数
来源：http://dali.pycfn.com/Article/details/gt2afwdnfac.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.yueranfly.top/Article/details/gt2cjzyacab.html

[Q28] 求和与平均
来源：http://dali.jinqigfzy.top/Article/details/gt2dlwfkcpb.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.wangdashe.top/Article/details/gt2ihmttelv.html

[Q29] 最大最小值
来源：http://dali.yanxiufei.cn/Article/details/gt2azovvwlh.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.cheryme.top/Article/details/gt2hbpdupob.html

[Q30] 分组统计
来源：http://dali.feifeiyinyue.top/Article/details/gt2lklkmzrj.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhengqikj.top/Article/details/gt2xglmyted.html

[Q31] 分组后过滤
来源：http://dali.daxiang520.top/Article/details/gt2nosladtu.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.ivvv.top/Article/details/gt2ziynxxra.html

[Q32] 分组拼接字符串
来源：http://dali.yueranfly.top/Article/details/gt2xdjoeudp.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.pengpengdd.cyou/Article/details/gt2yuyzlrvv.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.jqgufenzy.top/Article/details/gt2fogudany.html

[Q33] 多列分组
来源：http://dali.zdqjudy.top/Article/details/gt2censjifv.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.sufxvd.cn/Article/details/gt2dxgujabb.html

[Q34] 每组取第一条
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kdqeaqfa.html

SELECT * FROM (
来源：http://dali.xziqi.cn/Article/details/gt2bjwubkwp.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.gogol.net.cn/Article/details/gt2nbtjtdmx.html

) t WHERE rn = 1;
来源：http://dali.daria6918.cn/Article/details/gt2ncivaode.html

[Q35] 内连接
来源：http://dali.yuanzhike.top/Article/details/gt2sxtqefqn.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.hnxiangtu.top/Article/details/gt2daywdyxh.html

[Q36] 左连接
来源：http://dali.haohaochexian.top/Article/details/gt2woenhqga.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhoulong.xyz/Article/details/gt2jvxolbjw.html

[Q37] 右连接
来源：http://dali.shangyingyoupin.top/Article/details/gt2qybvuepn.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.hfpthk.cn/Article/details/gt2xhcjltbs.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rblukoth.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.xuetiantiany.cn/Article/details/gt2kmgnpzwg.html

[Q39] 自连接（查上下级）
来源：http://dali.daxiang520.top/Article/details/gt2dlfgpfnd.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.svipenyu.cn/Article/details/gt2dfeswqwe.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.wangshuangyany.cn/Article/details/gt2rlwlvdjs.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.aibaodan.cn/Article/details/gt2jswyshvf.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.aizwys.cn/Article/details/gt2xasekeex.html

[Q41] 多表连接
来源：http://dali.daxiang520.top/Article/details/gt2dzxznpiw.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sitqojbs.html

JOIN users u ON u.id = o.user_id
来源：http://dali.pengpengdd.cyou/Article/details/gt2yjueeheg.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.cqqwz.cn/Article/details/gt2wivhatgl.html

[Q42] 连接条件附加过滤
来源：http://dali.vqdsnc.cn/Article/details/gt2nqluhorz.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zdqjudy.top/Article/details/gt2knsqlxyd.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.jianghu66.top/Article/details/gt2eaxcsjoy.html

[Q43] 标量子查询
来源：http://dali.cheryme.top/Article/details/gt2fwxvsops.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.gogol.net.cn/Article/details/gt2mynqmdgp.html

[Q44] IN 子查询
来源：http://dali.vqdsnc.cn/Article/details/gt2onvuigkh.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.shzxlz.cn/Article/details/gt2tenljpmg.html

[Q45] EXISTS 判断存在
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hvppfznp.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.gzhubu.top/Article/details/gt2mguctwap.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.tian-w.cn/Article/details/gt2iwebtqoe.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jqgfzy.top/Article/details/gt2zyrhttjw.html

[Q47] 与平均值比较
来源：http://dali.cdnleiting.top/Article/details/gt2sgzywymv.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.fzhhl.top/Article/details/gt2cjbzhzpp.html

[Q48] CTE 公用表表达式
来源：http://dali.cheryme.top/Article/details/gt2mtdxgikk.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.haohaochexian.top/Article/details/gt2thbrzgeh.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zycfv.cn/Article/details/gt2gnryfygm.html

[Q49] 更新单行
来源：http://dali.zycfv.cn/Article/details/gt2thghgrgb.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.cheryme.top/Article/details/gt2lgozvgwv.html

[Q50] 批量更新
来源：http://dali.tanke756.top/Article/details/gt2rkokjfzi.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.dianchejie.cn/Article/details/gt2grlbpecf.html

[Q51] 用子查询更新
来源：http://dali.daxiang520.top/Article/details/gt2njdereri.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.cqqwz.cn/Article/details/gt2fslnhjlu.html

[Q52] 删除指定行
来源：http://dali.xuanzx.com/Article/details/gt2vjrigkyi.html

DELETE FROM users WHERE id = 10;
来源：http://dali.shuidangran.top/Article/details/gt2txekxogk.html

[Q53] 按条件删除
来源：http://dali.zhongyouzk.top/Article/details/gt2slkapdkd.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wpxitavv.html

[Q54] 清空表
来源：http://dali.zdqjudy.top/Article/details/gt2sijbqqww.html

TRUNCATE TABLE logs;
来源：http://dali.yuxming.cn/Article/details/gt2hyenxtyd.html

[Q55] 排名（并列占位）
来源：http://dali.zhiwuduotai.top/Article/details/gt2ipfvacvh.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.jianghu66.top/Article/details/gt2whguozwk.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2pqqxrxon.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.shzxlz.cn/Article/details/gt2dohpownk.html

[Q57] 行号
来源：http://dali.ydzc1.top/Article/details/gt2wwsmonqa.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.sufxvd.cn/Article/details/gt2cgosugre.html

[Q58] 累计求和
来源：http://dali.jinqigufen.top/Article/details/gt2fmmoykqt.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhixingplan.top/Article/details/gt2baltgjxg.html

[Q59] 分组内累计
来源：http://dali.hnqzz.top/Article/details/gt2bxverfxc.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.jyoumei.cn/Article/details/gt2leoopsnm.html

[Q60] 取上一行 / 下一行
来源：http://dali.yj20258.top/Article/details/gt2shbyeeeb.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.havefunace.top/Article/details/gt2ddkqmnxx.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.tianlin.xyz/Article/details/gt2tkcnublb.html

[Q61] 移动平均
来源：http://dali.kuanghao11.cn/Article/details/gt2kuboqeei.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xdjavpcv.html

[Q62] 分组占比
来源：http://dali.yj20258888.top/Article/details/gt2jlkegwxt.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.gaohongyu789.top/Article/details/gt2hqotbnuq.html

[Q63] 开启事务
来源：http://dali.vqdsnc.cn/Article/details/gt2lxxbrrle.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.guowangkeji.top/Article/details/gt2qxsvjnyz.html

[Q64] 提交事务
来源：http://dali.jqgfzy.top/Article/details/gt2werwionp.html

COMMIT;
来源：http://dali.zhongyouzk.top/Article/details/gt2hztlmgmh.html

[Q65] 回滚事务
来源：http://dali.haohaochexian.top/Article/details/gt2rzegfctg.html

ROLLBACK;
来源：http://dali.tianlin.xyz/Article/details/gt2ebavoobn.html

[Q66] 行锁查询
来源：http://dali.sweek.top/Article/details/gt2ucczzbfi.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.dashuyun.cn/Article/details/gt2xgzwzprz.html

[Q67] 设置隔离级别
来源：http://dali.9152youxi.cn/Article/details/gt2nbuqartz.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.jqgufenzy.top/Article/details/gt2nmffuckg.html

[Q68] 保存点
来源：http://dali.andypj.xyz/Article/details/gt2nvdaxrak.html

SAVEPOINT sp1;
来源：http://dali.zycfv.cn/Article/details/gt2tvyghuxy.html

ROLLBACK TO sp1;
来源：http://dali.gogol.net.cn/Article/details/gt2zodgsgjy.html

[Q69] 查看执行计划
来源：http://dali.xylfe.cn/Article/details/gt2maqfxagk.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.quarkkingdee.top/Article/details/gt2cdfoyjmu.html

[Q70] 更新统计信息
来源：http://dali.aizwys.cn/Article/details/gt2fqhplsji.html

ANALYZE TABLE users;
来源：http://dali.ivvv.top/Article/details/gt2oswgtiaa.html

[Q71] 查看建表语句
来源：http://dali.cheryme.top/Article/details/gt2ydyyivti.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.birdmap.top/Article/details/gt2brbhxadi.html

[Q72] 查看索引
来源：http://dali.haohaochexian.top/Article/details/gt2hkntqfhv.html

SHOW INDEX FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gt2vobcenjw.html

[Q73] 查看表状态
来源：http://dali.wangdashe.top/Article/details/gt2osohvais.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.hongshengwenyu.top/Article/details/gt2yfzjqksy.html

[Q74] 强制使用索引
来源：http://dali.yj20258.top/Article/details/gt2teaxcavc.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.sxryk.cn/Article/details/gt2iujlgham.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2vzzsmhcc.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.redwolf501.top/Article/details/gt2bkaglcvs.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.cucudq.cn/Article/details/gt2mivkfqdi.html

[Q76] 按天统计
来源：http://dali.sxryk.cn/Article/details/gt2czufrwww.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhengqikj.top/Article/details/gt2mzvzcauq.html

[Q77] 时间加减
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2stsamhgs.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.nwbrower.top/Article/details/gt2ohcxzvgy.html

[Q78] 当前时间
来源：http://dali.aizwys.cn/Article/details/gt2kqzzibua.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.fzhhl.top/Article/details/gt2hrklbqvj.html

[Q79] 字符串拼接
来源：http://dali.birdmap.top/Article/details/gt2ywydintn.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wfjblocc.html

[Q80] 字符串截取
来源：http://dali.jinqigufen.top/Article/details/gt2hohhdpdc.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.316326.xyz/Article/details/gt2ztkxlpdx.html

[Q81] 字符串替换
来源：http://dali.9152youxi.cn/Article/details/gt2oezjlvkl.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2shnhcvom.html

[Q82] 字符长度与字节长度
来源：http://dali.zhixingplan.top/Article/details/gt2zsruspab.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nbbatbke.html

[Q83] 大小写转换
来源：http://dali.shangyingyoupin.top/Article/details/gt2lxewgcwl.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.sweek.top/Article/details/gt2zwaqbxhb.html

[Q84] 去除首尾空格
来源：http://dali.svipenyu.cn/Article/details/gt2swmbitzq.html

SELECT TRIM(name) FROM users;
来源：http://dali.ydzc1.top/Article/details/gt2otefiplu.html

[Q85] 数值取整
来源：http://dali.zhiwuduotai.top/Article/details/gt2uaovfqws.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.shuidangran.top/Article/details/gt2ysnutmwm.html

[Q86] 读取 JSON 字段
来源：http://dali.wangdashe.top/Article/details/gt2nvwjlfpj.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.quarkkingdee.top/Article/details/gt2zhevfcmi.html

[Q87] JSON 字段做条件
来源：http://dali.yj202588.top/Article/details/gt2xcxpkhaz.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.ydzc1.top/Article/details/gt2rcykonqt.html

[Q88] 行转列（条件聚合）
来源：http://dali.meibo888.top/Article/details/gt2akqpukvh.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.smart0.xyz/Article/details/gt2rvozvqky.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.birdmap.top/Article/details/gt2eahkjfny.html

[Q89] 判断表是否存在
来源：http://dali.0kj1m.cn/Article/details/gt2cxytpodk.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.yj20258.top/Article/details/gt2vowycyaq.html

[Q90] 生成序号列
来源：http://dali.ivvv.top/Article/details/gt2gwfmlzmd.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.mhx1999.top/Article/details/gt2xtevvmba.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2ptocukom.html

R. Bash 专题
来源：http://dali.wangshuangyany.cn/Article/details/gt2orrlewkm.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2phcehuwg.html

[R01] shebang 与严格模式
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mwnwguok.html

#!/usr/bin/env bash
来源：http://dali.meibo888.top/Article/details/gt2umfbszjf.html

set -euo pipefail
来源：http://dali.snrcjt.cn/Article/details/gt2ibibqkyb.html

[R02] 变量赋值与使用
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ktupdjpu.html

name="Tom"; echo "$name"
来源：http://dali.smart0.xyz/Article/details/gt2udvduady.html

[R03] 只读变量
来源：http://dali.jlsjyb.cn/Article/details/gt2tsqyegyd.html

readonly PI=3.14
来源：http://dali.tanke756.top/Article/details/gt2wfmrwtcy.html

[R04] 位置参数
来源：http://dali.daria6918.cn/Article/details/gt2jnooozqr.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.havefunace.top/Article/details/gt2iuqmtxis.html

[R05] 参数默认值
来源：http://dali.hongshengwenyu.top/Article/details/gt2heqjlrol.html

name="${1:-default}"
来源：http://dali.daria6918.cn/Article/details/gt2ocmsoxeq.html

[R06] 判断命令是否存在
来源：http://dali.redwolf501.top/Article/details/gt2gtznvgeh.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vrrnrvzk.html

[R07] if 判断文件
来源：http://dali.jqgfzy.top/Article/details/gt2wbckcdor.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.tian-w.cn/Article/details/gt2pwgkfcfy.html

[R08] 数值比较
来源：http://dali.ybcxt.top/Article/details/gt2xfpmqbxy.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.xuanzx.com/Article/details/gt2irakottm.html

[R09] 字符串比较
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zebfnwvu.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.quarkkingdee.top/Article/details/gt2zpllgkit.html

[R10] 正则匹配
来源：http://dali.aizwys.cn/Article/details/gt2gfunfkkc.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.shzxlz.cn/Article/details/gt2vrrsudcx.html

[R11] case 多分支
来源：http://dali.jinqigfzy.top/Article/details/gt2wdzgjqoo.html

case "$1" in
来源：http://dali.zhongyouzk.top/Article/details/gt2iudhskpt.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2cuuvjtxi.html

stop)  echo "停止" ;;
来源：http://dali.hnqzz.top/Article/details/gt2raekfhzo.html

*)     echo "未知命令" ;;
来源：http://dali.yj20258.top/Article/details/gt2idtuzxad.html

esac
来源：http://dali.316326.xyz/Article/details/gt2wzqhytdn.html

[R12] for 遍历文件
来源：http://dali.gotoacloud.top/Article/details/gt2qzsdasca.html

for f in *.txt; do echo "$f"; done
来源：http://dali.tian-w.cn/Article/details/gt2ojfmvpxu.html

[R13] for 计数循环
来源：http://dali.jiagoushi.top/Article/details/gt2lhmbpioc.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.ydzc1.top/Article/details/gt2zmpsihqc.html

[R14] C 风格 for
来源：http://dali.nanxuanxn.top/Article/details/gt2liancvoq.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.wangdashe.top/Article/details/gt2uesaoxwg.html

[R15] while 逐行读文件
来源：http://dali.snrcjt.cn/Article/details/gt2rfcfksht.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wcitwvnz.html

[R16] until 等待条件
来源：http://dali.yuanzhike.top/Article/details/gt2toefibaq.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.chenjidiqi.icu/Article/details/gt2efdagtlo.html

[R17] 数组定义与取值
来源：http://dali.hysaishi.cn/Article/details/gt2uhjhcfwq.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.andypj.xyz/Article/details/gt2izzkwlot.html

[R18] 遍历数组
来源：http://dali.ehwqpu.com/Article/details/gt2axuqwrzn.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.jiagoushi.top/Article/details/gt2fivayuum.html

[R19] 数组长度
来源：http://dali.c1oappe.top/Article/details/gt2cflbzwcv.html

echo "${#arr[@]}"
来源：http://dali.316326.xyz/Article/details/gt2gumhqrtn.html

[R20] 关联数组（字典）
来源：http://dali.jyoumei.cn/Article/details/gt2tesrolmo.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.hysaishi.cn/Article/details/gt2cviqakng.html

[R21] 字符串长度
来源：http://dali.dashuyun.cn/Article/details/gt2jidcmafs.html

echo "${#s}"
来源：http://dali.jyoumei.cn/Article/details/gt2kpxhdady.html

[R22] 截取子串
来源：http://dali.ybcxt.top/Article/details/gt2ljktvdnt.html

echo "${s:0:5}"
来源：http://dali.9152youxi.cn/Article/details/gt2dtsnglpi.html

[R23] 字符串替换
来源：http://dali.zhixingplan.top/Article/details/gt2yqfnxxud.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.meibo888.top/Article/details/gt2dpbrzlnk.html

[R24] 大小写转换
来源：http://dali.zhengqikj.top/Article/details/gt2npoxmzrs.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.daria6918.cn/Article/details/gt2qenqmtoy.html

[R25] 去后缀 / 去前缀
来源：http://dali.snrcjt.cn/Article/details/gt2hksahcsh.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.tian-w.cn/Article/details/gt2ropnfdrv.html

[R26] 命令替换
来源：http://dali.zhongyouzk.top/Article/details/gt2euxsujrw.html

now=$(date +%F); echo "$now"
来源：http://dali.guowangkeji.top/Article/details/gt2xqdbpulw.html

[R27] 算术展开
来源：http://dali.cqqwz.cn/Article/details/gt2hygvbhpw.html

echo $((1 + 2 * 3))
来源：http://dali.sufxvd.cn/Article/details/gt2hqfigmfc.html

[R28] 浮点运算
来源：http://dali.cqqwz.cn/Article/details/gt2idknsjwn.html

echo "scale=2; 10/3" | bc
来源：http://dali.chenjidiqi.icu/Article/details/gt2wjhhvnsi.html

[R29] 定义函数
来源：http://dali.tian-w.cn/Article/details/gt2ixkvzdit.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.9152youxi.cn/Article/details/gt2vnkuxaxz.html

[R30] 函数返回状态码
来源：http://dali.fengsongda.top/Article/details/gt2jqgxbzsu.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.sweek.top/Article/details/gt2aunjumhj.html

[R31] 局部变量
来源：http://dali.havefunace.top/Article/details/gt2wrkpdygp.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yjohjqtd.html

[R32] 参数个数校验
来源：http://dali.shanyushiyangtech.top/Article/details/gt2taumzpku.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.svipenyu.cn/Article/details/gt2ezpjfeju.html

[R33] 捕获错误并提示行号
来源：http://dali.redwolf501.top/Article/details/gt2ziqianni.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhengqikj.top/Article/details/gt2mhgdapjw.html

[R34] 退出时清理
来源：http://dali.zycfv.cn/Article/details/gt2othpcwnf.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhiwuduotai.top/Article/details/gt2bdzbjgge.html

[R35] 后台执行并等待
来源：http://dali.yuanzhike.top/Article/details/gt2gjvwitdi.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.smart0.xyz/Article/details/gt2okohdvot.html

[R36] 并发执行多个任务
来源：http://dali.cucudq.cn/Article/details/gt2jefkmclf.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhongyouzk.top/Article/details/gt2dtotrytz.html

[R37] 把输出赋给变量
来源：http://dali.gogol.net.cn/Article/details/gt2sefhdjga.html

files=$(ls -1)
来源：http://dali.ehwqpu.com/Article/details/gt2lkkspfwz.html

[R38] 管道串联
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dnkzglup.html

cat a.txt | grep -i error | wc -l
来源：http://dali.shuidangran.top/Article/details/gt2yqwfjzti.html

[R39] 重定向标准输出与错误
来源：http://dali.hfpthk.cn/Article/details/gt2znlkubbt.html

cmd > out.log 2>&1
来源：http://dali.xuetiantiany.cn/Article/details/gt2dttookfw.html

[R40] 追加写日志
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2srneqnby.html

echo "log" >> out.log
来源：http://dali.aibaodan.cn/Article/details/gt2yakkvsat.html

[R41] 丢弃输出
来源：http://dali.fengsongda.top/Article/details/gt2bilyacpm.html

cmd >/dev/null 2>&1
来源：http://dali.chenlongwang.top/Article/details/gt2jtxxdrke.html

[R42] 输入重定向
来源：http://dali.xuetiantiany.cn/Article/details/gt2nvasngyg.html

wc -l < a.txt
来源：http://dali.sufxvd.cn/Article/details/gt2vdabmbli.html

[R43] 按名字查找文件
来源：http://dali.snrcjt.cn/Article/details/gt2aeaicsnm.html

find . -name "*.log" -type f
来源：http://dali.nanxinkj.top/Article/details/gt2tdvjttkc.html

[R44] 按修改时间查找
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kskmcqtq.html

find . -mtime -7 -type f
来源：http://dali.hongshengwenyu.top/Article/details/gt2lzpyexsk.html

[R45] 批量删除
来源：http://dali.fzhhl.top/Article/details/gt2ixcbzeab.html

find . -name "*.tmp" -delete
来源：http://dali.9152youxi.cn/Article/details/gt2jvlcppkz.html

[R46] 递归替换文件内容
来源：http://dali.meibo888.top/Article/details/gt2uorfxtnm.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.birdmap.top/Article/details/gt2lustswyz.html

[R47] sed 单行替换
来源：http://dali.cqqwz.cn/Article/details/gt2uxvimsfs.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.yangfankeji.com/Article/details/gt2bxcetmjv.html

[R48] awk 取指定列
来源：http://dali.fengsongda.top/Article/details/gt2xnlfymtc.html

awk '{print $1, $3}' a.txt
来源：http://dali.birdmap.top/Article/details/gt2nydghmfn.html

[R49] awk 带条件
来源：http://dali.guowangkeji.top/Article/details/gt2ihfgkwjn.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.xuanzx.com/Article/details/gt2ejrleegp.html

[R50] awk 求和
来源：http://dali.aibaodan.cn/Article/details/gt2nzvkjkqr.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.jqgufenzy.top/Article/details/gt2bpgcuqix.html

[R51] 排序去重取前几
来源：http://dali.daxiang520.top/Article/details/gt2waxpvudq.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.jianghu66.top/Article/details/gt2vdskcwxz.html

[R52] 统计行数
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2adghweye.html

wc -l a.txt
来源：http://dali.shangyingyoupin.top/Article/details/gt2uokgemgi.html

[R53] 查看文件头与实时尾
来源：http://dali.redwolf501.top/Article/details/gt2ibfztbsh.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.cashguo.top/Article/details/gt2xtxcvown.html

[R54] 比较两个文件
来源：http://dali.daria6918.cn/Article/details/gt2itqpsesd.html

diff a.txt b.txt
来源：http://dali.yuanzhike.top/Article/details/gt2jvgglaox.html

[R55] 压缩与解压
来源：http://dali.gaohongyu789.top/Article/details/gt2aujsnnln.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sajxusbz.html

[R56] 远程拷贝
来源：http://dali.dashuyun.cn/Article/details/gt2hjgbiyil.html

scp file user@host:/path/
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zzudybou.html

[R57] 远程执行命令
来源：http://dali.gotoacloud.top/Article/details/gt2ekcbwnor.html

ssh user@host 'uptime'
来源：http://dali.redwolf501.top/Article/details/gt2clzhkgtk.html

[R58] 下载文件
来源：http://dali.xziqi.cn/Article/details/gt2hloyeiuy.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.xziqi.cn/Article/details/gt2gdrbjzkx.html

[R59] 发 POST JSON
来源：http://dali.jinghuilouyu.cn/Article/details/gt2znmmlmib.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zycfv.cn/Article/details/gt2ymnpewdu.html

[R60] 只看 HTTP 状态码
来源：http://dali.svipenyu.cn/Article/details/gt2pjlxwtjs.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.daxiang520.top/Article/details/gt2hrtmfdkz.html

[R61] 磁盘占用
来源：http://dali.0kj1m.cn/Article/details/gt2wwpjiveu.html

df -h;  du -sh *
来源：http://dali.tian-w.cn/Article/details/gt2qpvuxoeo.html

[R62] 找最占空间的文件
来源：http://dali.dianchejie.cn/Article/details/gt2ldajwrlg.html

du -ah . | sort -rh | head -10
来源：http://dali.ybcxt.top/Article/details/gt2jwzonozv.html

[R63] 内存与进程
来源：http://dali.hnqzz.top/Article/details/gt2aiuypaxn.html

free -h;  ps aux | grep nginx
来源：http://dali.yuanzhike.top/Article/details/gt2zaotvpuu.html

[R64] 结束进程
来源：http://dali.iojbl.cn/Article/details/gt2ktwzfsin.html

kill -9 $(pgrep -f app.py)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lkewerue.html

[R65] 查看端口占用
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jdxjajss.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.iojbl.cn/Article/details/gt2ncgqxztl.html

[R66] 定时任务
来源：http://dali.chenjidiqi.icu/Article/details/gt2vuavjbgc.html

crontab -e;  crontab -l
来源：http://dali.andypj.xyz/Article/details/gt2itjlziuq.html

[R67] 生成随机十六进制串
来源：http://dali.sysykeji.top/Article/details/gt2ewrcayud.html

openssl rand -hex 16
来源：http://dali.meibo888.top/Article/details/gt2rkmikevi.html

[R68] 计算文件校验值
来源：http://dali.hywenlv.cn/Article/details/gt2bhzfzvmb.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.hnxiangtu.top/Article/details/gt2qgydipbs.html

[R69] 生成随机密码
来源：http://dali.zycfv.cn/Article/details/gt2vdawfzwm.html


<!-- 参考信息 -->