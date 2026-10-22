代发 wailian999

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.fengsongda.top/Article/details/gt2bttozvio.html

[Q26] 计数
来源：http://dali.hnqzz.top/Article/details/gt2ukxpxzbm.html

SELECT COUNT(*) FROM users;
来源：http://dali.cqqwz.cn/Article/details/gt2gwqxghqf.html

[Q27] 条件计数
来源：http://dali.cheryme.top/Article/details/gt2zlzkglge.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.jiagoushi.top/Article/details/gt2fzknxiyt.html

[Q28] 求和与平均
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nnzewvrj.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.tianlin.xyz/Article/details/gt2hobegrrl.html

[Q29] 最大最小值
来源：http://dali.birdmap.top/Article/details/gt2poeclzxi.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.havefunace.top/Article/details/gt2queuivpn.html

[Q30] 分组统计
来源：http://dali.birdmap.top/Article/details/gt2ptnxspkr.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.0kj1m.cn/Article/details/gt2trfufbpf.html

[Q31] 分组后过滤
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2oyeaquan.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.iojbl.cn/Article/details/gt2cryxdhus.html

[Q32] 分组拼接字符串
来源：http://dali.yj20258888.top/Article/details/gt2njfiplcf.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.jqgufenzy.top/Article/details/gt2vvlvnmmf.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.sxryk.cn/Article/details/gt2uyeyoabu.html

[Q33] 多列分组
来源：http://dali.birdmap.top/Article/details/gt2eqyotrjo.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.dashuyun.cn/Article/details/gt2hkpixqhs.html

[Q34] 每组取第一条
来源：http://dali.c1oappe.top/Article/details/gt2fxnuxgjx.html

SELECT * FROM (
来源：http://dali.nwbrower.top/Article/details/gt2ohdyvkig.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.ppjwa.cn/Article/details/gt2rbzcpdfi.html

) t WHERE rn = 1;
来源：http://dali.birdmap.top/Article/details/gt2crnoruaj.html

[Q35] 内连接
来源：http://dali.ivvv.top/Article/details/gt2eqyxmsnx.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhengqikj.top/Article/details/gt2qzdjtqgv.html

[Q36] 左连接
来源：http://dali.jqgufenzy.top/Article/details/gt2fbssxvds.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhiwuduotai.top/Article/details/gt2pestiban.html

[Q37] 右连接
来源：http://dali.haohaochexian.top/Article/details/gt2itdobbfz.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.hnqzz.top/Article/details/gt2negcocfu.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.yueranfly.top/Article/details/gt2zgkibyec.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.316326.xyz/Article/details/gt2gabfajnc.html

[Q39] 自连接（查上下级）
来源：http://dali.yueranfly.top/Article/details/gt2fstsrcln.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhiwuduotai.top/Article/details/gt2pajjavgr.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.9152youxi.cn/Article/details/gt2nzyrtllf.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.birdmap.top/Article/details/gt2heqbhldy.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.sweek.top/Article/details/gt2ehmngbxs.html

[Q41] 多表连接
来源：http://dali.xuetiantiany.cn/Article/details/gt2vgorrfun.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.yuxming.cn/Article/details/gt2uxyagdyl.html

JOIN users u ON u.id = o.user_id
来源：http://dali.nanxuanxn.top/Article/details/gt2cipwmecd.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.yuxming.cn/Article/details/gt2blrslnez.html

[Q42] 连接条件附加过滤
来源：http://dali.aibaodan.cn/Article/details/gt2kohqmypr.html

SELECT u.name, o.amount FROM users u
来源：http://dali.xuetiantiany.cn/Article/details/gt2dbdzjgmq.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.gzhubu.top/Article/details/gt2ijqisoyy.html

[Q43] 标量子查询
来源：http://dali.xuanzx.com/Article/details/gt2msxzdzbv.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.sysykeji.top/Article/details/gt2vpybwzyd.html

[Q44] IN 子查询
来源：http://dali.haohaochexian.top/Article/details/gt2rjcwttts.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.yongpay.top/Article/details/gt2xmffgjhz.html

[Q45] EXISTS 判断存在
来源：http://dali.ybcxt.top/Article/details/gt2lzgzfbss.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yueranfly.top/Article/details/gt2bstvldal.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.redwolf501.top/Article/details/gt2ffwkwlza.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.fzhhl.top/Article/details/gt2yeibkxro.html

[Q47] 与平均值比较
来源：http://dali.meibo888.top/Article/details/gt2gwdohkue.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.wangdashe.top/Article/details/gt2lpcpftdj.html

[Q48] CTE 公用表表达式
来源：http://dali.zhoulong.xyz/Article/details/gt2ampjiehx.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.sufxvd.cn/Article/details/gt2vudmypel.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.quarkkingdee.top/Article/details/gt2sjxpilwf.html

[Q49] 更新单行
来源：http://dali.jyoumei.cn/Article/details/gt2jejvgchd.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.yuxming.cn/Article/details/gt2ugmuamnq.html

[Q50] 批量更新
来源：http://dali.aizwys.cn/Article/details/gt2swxupbqn.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.c1oappe.top/Article/details/gt2xudrpghr.html

[Q51] 用子查询更新
来源：http://dali.havefunace.top/Article/details/gt2tcersfkf.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.dianchejie.cn/Article/details/gt2arrwcins.html

[Q52] 删除指定行
来源：http://dali.nanxinkj.top/Article/details/gt2epvxapyv.html

DELETE FROM users WHERE id = 10;
来源：http://dali.guannengcc.top/Article/details/gt2kuqzyumg.html

[Q53] 按条件删除
来源：http://dali.bjfxy.top/Article/details/gt2ysizzqjj.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.chenzaomai.com/Article/details/gt2nmnixxml.html

[Q54] 清空表
来源：http://dali.zhiwuduotai.top/Article/details/gt2gakxqela.html

TRUNCATE TABLE logs;
来源：http://dali.dianchejie.cn/Article/details/gt2fpcsrflg.html

[Q55] 排名（并列占位）
来源：http://dali.316326.xyz/Article/details/gt2wkcaqqvm.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.yj20258888.top/Article/details/gt2gupckgyu.html

[Q56] 密集排名（并列不占位）
来源：http://dali.yangfankeji.com/Article/details/gt2tftaeech.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhiwuduotai.top/Article/details/gt2sfsiwspi.html

[Q57] 行号
来源：http://dali.hfpthk.cn/Article/details/gt2nhtiwadg.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.yueranfly.top/Article/details/gt2sykmgxlg.html

[Q58] 累计求和
来源：http://dali.yanxiufei.cn/Article/details/gt2dzqruhpa.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.cashguo.top/Article/details/gt2qjotpmni.html

[Q59] 分组内累计
来源：http://dali.yongpay.top/Article/details/gt2wfxyvvmj.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zdqjudy.top/Article/details/gt2vnyfljnf.html

[Q60] 取上一行 / 下一行
来源：http://dali.aibaodan.cn/Article/details/gt2kfhujotp.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.yvedp.cn/Article/details/gt2kpsavdpg.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.feifeiyinyue.top/Article/details/gt2msxofuwh.html

[Q61] 移动平均
来源：http://dali.9152youxi.cn/Article/details/gt2skgvxbao.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.snrcjt.cn/Article/details/gt2omlfrsgv.html

[Q62] 分组占比
来源：http://dali.havefunace.top/Article/details/gt2tbzkxyyx.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.yongpay.top/Article/details/gt2zwdsqvmi.html

[Q63] 开启事务
来源：http://dali.fzhhl.top/Article/details/gt2gzbwuurd.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.hnxiangtu.top/Article/details/gt2jflvjbkx.html

[Q64] 提交事务
来源：http://dali.bjfxy.top/Article/details/gt2szldnciz.html

COMMIT;
来源：http://dali.kuanghao11.cn/Article/details/gt2lqaagiot.html

[Q65] 回滚事务
来源：http://dali.vqdsnc.cn/Article/details/gt2axfzgqvf.html

ROLLBACK;
来源：http://dali.xuetiantiany.cn/Article/details/gt2rbmnmxsn.html

[Q66] 行锁查询
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xodckpxp.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.cucudq.cn/Article/details/gt2ffxjiopb.html

[Q67] 设置隔离级别
来源：http://dali.jlsjyb.cn/Article/details/gt2mllgkwzj.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.nwbrower.top/Article/details/gt2caotwwnl.html

[Q68] 保存点
来源：http://dali.xinyue.icu/Article/details/gt2cnmtwhla.html

SAVEPOINT sp1;
来源：http://dali.tian-w.cn/Article/details/gt2dbrkejjc.html

ROLLBACK TO sp1;
来源：http://dali.yuanzhike.top/Article/details/gt2obsbzdgj.html

[Q69] 查看执行计划
来源：http://dali.xinyue.icu/Article/details/gt2certplsl.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dvbfmvxh.html

[Q70] 更新统计信息
来源：http://dali.tanke756.top/Article/details/gt2aggjwvll.html

ANALYZE TABLE users;
来源：http://dali.iojbl.cn/Article/details/gt2mbwrcnzh.html

[Q71] 查看建表语句
来源：http://dali.yvedp.cn/Article/details/gt2cxfmyhfz.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jfnguxuq.html

[Q72] 查看索引
来源：http://dali.nanxuanxn.top/Article/details/gt2yualygzn.html

SHOW INDEX FROM users;
来源：http://dali.nanxinkj.top/Article/details/gt2qefpekns.html

[Q73] 查看表状态
来源：http://dali.svipenyu.cn/Article/details/gt2pioittoq.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.xziqi.cn/Article/details/gt2bpqnqwsp.html

[Q74] 强制使用索引
来源：http://dali.hywenlv.cn/Article/details/gt2vtpvtkob.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.tianlin.xyz/Article/details/gt2awgbcnno.html

[Q75] 日期格式化
来源：http://dali.svipenyu.cn/Article/details/gt2elpdqedo.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.quarkkingdee.top/Article/details/gt2hndhpdpl.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.mhx1999.top/Article/details/gt2xmkaokiv.html

[Q76] 按天统计
来源：http://dali.pycfn.com/Article/details/gt2mivybnny.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.aizwys.cn/Article/details/gt2hefoetyn.html

[Q77] 时间加减
来源：http://dali.yueranfly.top/Article/details/gt2sonbqrdk.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.cheryme.top/Article/details/gt2ahsllghi.html

[Q78] 当前时间
来源：http://dali.chenzaomai.com/Article/details/gt2rhtfbwsl.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.gzhubu.top/Article/details/gt2erozvkzs.html

[Q79] 字符串拼接
来源：http://dali.feifeiyinyue.top/Article/details/gt2hguigwzz.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhixingplan.top/Article/details/gt2yrcnszvr.html

[Q80] 字符串截取
来源：http://dali.yueranfly.top/Article/details/gt2zjgzthqk.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.shangyingyoupin.top/Article/details/gt2gzusprxd.html

[Q81] 字符串替换
来源：http://dali.chenzaomai.com/Article/details/gt2iumvplhu.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gt2ydjqgjwq.html

[Q82] 字符长度与字节长度
来源：http://dali.guowangkeji.top/Article/details/gt2dullgslu.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.shangyingyoupin.top/Article/details/gt2wyivwdtg.html

[Q83] 大小写转换
来源：http://dali.zhiwuduotai.top/Article/details/gt2rwxzpmgx.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.jqgfzy.top/Article/details/gt2oblpuidk.html

[Q84] 去除首尾空格
来源：http://dali.cheryme.top/Article/details/gt2umiczgop.html

SELECT TRIM(name) FROM users;
来源：http://dali.tanke756.top/Article/details/gt2rnsbvbiu.html

[Q85] 数值取整
来源：http://dali.pengpengdd.cyou/Article/details/gt2yiznccgr.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhoulong.xyz/Article/details/gt2vedsljcu.html

[Q86] 读取 JSON 字段
来源：http://dali.cheryme.top/Article/details/gt2swhscpfr.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.ydzc1.top/Article/details/gt2vqkglqbs.html

[Q87] JSON 字段做条件
来源：http://dali.shuidangran.top/Article/details/gt2misweelm.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.yj20258888.top/Article/details/gt2dxvwkshz.html

[Q88] 行转列（条件聚合）
来源：http://dali.shangyingyoupin.top/Article/details/gt2scvrsrtq.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhoulong.xyz/Article/details/gt2dfjgxcir.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.chenzaomai.com/Article/details/gt2lqtlmiat.html

[Q89] 判断表是否存在
来源：http://dali.kuanghao11.cn/Article/details/gt2zvmbibpk.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.hywenlv.cn/Article/details/gt2jzmzgnpe.html

[Q90] 生成序号列
来源：http://dali.yvedp.cn/Article/details/gt2pqtungja.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.havefunace.top/Article/details/gt2nfkeacrm.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gt2atyoqlax.html

R. Bash 专题
来源：http://dali.iojbl.cn/Article/details/gt2qusfeqeu.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2nxxyqijc.html

[R01] shebang 与严格模式
来源：http://dali.vqdsnc.cn/Article/details/gt2vaklbsby.html

#!/usr/bin/env bash
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hsruhlar.html

set -euo pipefail
来源：http://dali.xylfe.cn/Article/details/gt2hdltwyfm.html

[R02] 变量赋值与使用
来源：http://dali.mhx1999.top/Article/details/gt2ymdkhpcy.html

name="Tom"; echo "$name"
来源：http://dali.xylfe.cn/Article/details/gt2upkgwdcp.html

[R03] 只读变量
来源：http://dali.zdqjudy.top/Article/details/gt2qffwpssx.html

readonly PI=3.14
来源：http://dali.cqqwz.cn/Article/details/gt2chmojcaa.html

[R04] 位置参数
来源：http://dali.hongshengwenyu.top/Article/details/gt2sebmgwcj.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.chenzaomai.com/Article/details/gt2apaosedz.html

[R05] 参数默认值
来源：http://dali.haohaochexian.top/Article/details/gt2pwyoqhcl.html

name="${1:-default}"
来源：http://dali.sweek.top/Article/details/gt2voxujxzs.html

[R06] 判断命令是否存在
来源：http://dali.zhongyouzk.top/Article/details/gt2bedchxjc.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hpnqjtme.html

[R07] if 判断文件
来源：http://dali.pengpengdd.cyou/Article/details/gt2ksxjijev.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.gaohongyu789.top/Article/details/gt2gbdhsogy.html

[R08] 数值比较
来源：http://dali.xuetiantiany.cn/Article/details/gt2eesxsqrr.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zycfv.cn/Article/details/gt2yfuqvpvd.html

[R09] 字符串比较
来源：http://dali.nwbrower.top/Article/details/gt2wgopgfjm.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.pengpengdd.cyou/Article/details/gt2lsllyves.html

[R10] 正则匹配
来源：http://dali.hnxiangtu.top/Article/details/gt2hilcatpa.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dfdxblps.html

[R11] case 多分支
来源：http://dali.shuidangran.top/Article/details/gt2jkqwjthi.html

case "$1" in
来源：http://dali.hnqzz.top/Article/details/gt2betkbkkq.html

start) echo "启动" ;;
来源：http://dali.fengsongda.top/Article/details/gt2aovyyhys.html

stop)  echo "停止" ;;
来源：http://dali.jinqigfzy.top/Article/details/gt2dsugnlar.html

*)     echo "未知命令" ;;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xsimvcye.html

esac
来源：http://dali.shangyingyoupin.top/Article/details/gt2mahwkjqn.html

[R12] for 遍历文件
来源：http://dali.vqdsnc.cn/Article/details/gt2fegikgic.html

for f in *.txt; do echo "$f"; done
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vlwyiwld.html

[R13] for 计数循环
来源：http://dali.jiagoushi.top/Article/details/gt2prbjjfaw.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.hongshengwenyu.top/Article/details/gt2mwdfzfaj.html

[R14] C 风格 for
来源：http://dali.ehwqpu.com/Article/details/gt2pywngunw.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.gzhubu.top/Article/details/gt2yeqlnfed.html

[R15] while 逐行读文件
来源：http://dali.daria6918.cn/Article/details/gt2hbzilwqd.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.dianchejie.cn/Article/details/gt2qqfalucr.html

[R16] until 等待条件
来源：http://dali.yonumen.top/Article/details/gt2bodiasps.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.snrcjt.cn/Article/details/gt2fdsqifax.html

[R17] 数组定义与取值
来源：http://dali.svipenyu.cn/Article/details/gt2ekxwclfz.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.gzhubu.top/Article/details/gt2ewzllzgn.html

[R18] 遍历数组
来源：http://dali.yueranfly.top/Article/details/gt2mxdgysnh.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bfcbonzw.html

[R19] 数组长度
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uulqmtjj.html

echo "${#arr[@]}"
来源：http://dali.fengsongda.top/Article/details/gt2fqyebbxj.html

[R20] 关联数组（字典）
来源：http://dali.shangyingyoupin.top/Article/details/gt2cnkxfldg.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.jyoumei.cn/Article/details/gt2sqfvcqfh.html

[R21] 字符串长度
来源：http://dali.fengsongda.top/Article/details/gt2tnsfpfxr.html

echo "${#s}"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tzloxrkl.html

[R22] 截取子串
来源：http://dali.tianlin.xyz/Article/details/gt2gduuprpm.html

echo "${s:0:5}"
来源：http://dali.shzxlz.cn/Article/details/gt2ffrhwapf.html

[R23] 字符串替换
来源：http://dali.hongshengwenyu.top/Article/details/gt2iyjpwdxj.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.gzhubu.top/Article/details/gt2cbpgnxry.html

[R24] 大小写转换
来源：http://dali.pengpengdd.cyou/Article/details/gt2xlxaqtde.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.yj202588.top/Article/details/gt2lxeghily.html

[R25] 去后缀 / 去前缀
来源：http://dali.cqqwz.cn/Article/details/gt2xdnvblvk.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.tian-w.cn/Article/details/gt2ejjthwic.html

[R26] 命令替换
来源：http://dali.guannengcc.top/Article/details/gt2wznomlst.html

now=$(date +%F); echo "$now"
来源：http://dali.chenlongwang.top/Article/details/gt2fizaaztb.html

[R27] 算术展开
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nixaizww.html

echo $((1 + 2 * 3))
来源：http://dali.jqgufenzy.top/Article/details/gt2yedekado.html

[R28] 浮点运算
来源：http://dali.zhengqikj.top/Article/details/gt2aqmvpreo.html

echo "scale=2; 10/3" | bc
来源：http://dali.jianghu66.top/Article/details/gt2teiyavim.html

[R29] 定义函数
来源：http://dali.hongshengwenyu.top/Article/details/gt2jsjursgu.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.hammf.cn/Article/details/gt2eijudyod.html

[R30] 函数返回状态码
来源：http://dali.gaohongyu789.top/Article/details/gt2ggbpikxb.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.shuidangran.top/Article/details/gt2ovfrlupf.html

[R31] 局部变量
来源：http://dali.snrcjt.cn/Article/details/gt2prjnzemg.html

f() { local x=1; echo "$x"; }
来源：http://dali.havefunace.top/Article/details/gt2sohikxvh.html

[R32] 参数个数校验
来源：http://dali.aizwys.cn/Article/details/gt2onqvygmq.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhongyouzk.top/Article/details/gt2mdhhhdcy.html

[R33] 捕获错误并提示行号
来源：http://dali.ybcxt.top/Article/details/gt2gihadtaq.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.nanxinkj.top/Article/details/gt2ogcitpjs.html

[R34] 退出时清理
来源：http://dali.daxiang520.top/Article/details/gt2gyxlxkoi.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.pycfn.com/Article/details/gt2qfpgeiat.html

[R35] 后台执行并等待
来源：http://dali.aizwys.cn/Article/details/gt2enqkqvth.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.sxryk.cn/Article/details/gt2gmggsjpo.html

[R36] 并发执行多个任务
来源：http://dali.gogol.net.cn/Article/details/gt2tqmxofgn.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.mhx1999.top/Article/details/gt2apbzxyjx.html

[R37] 把输出赋给变量
来源：http://dali.guowangkeji.top/Article/details/gt2fylvnuna.html

files=$(ls -1)
来源：http://dali.havefunace.top/Article/details/gt2koklyqit.html

[R38] 管道串联
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pgcufhxm.html

cat a.txt | grep -i error | wc -l
来源：http://dali.guowangkeji.top/Article/details/gt2ptlazqjj.html

[R39] 重定向标准输出与错误
来源：http://dali.fengsongda.top/Article/details/gt2izinbeda.html

cmd > out.log 2>&1
来源：http://dali.fengsongda.top/Article/details/gt2xxqzzjlg.html

[R40] 追加写日志
来源：http://dali.0kj1m.cn/Article/details/gt2bctgsmlk.html

echo "log" >> out.log
来源：http://dali.zhiwuduotai.top/Article/details/gt2uwhuiogj.html

[R41] 丢弃输出
来源：http://dali.sysykeji.top/Article/details/gt2gufoowla.html

cmd >/dev/null 2>&1
来源：http://dali.xinyue.icu/Article/details/gt2nmsijvjd.html

[R42] 输入重定向
来源：http://dali.fengsongda.top/Article/details/gt2dvsyajuh.html

wc -l < a.txt
来源：http://dali.yuxming.cn/Article/details/gt2esjxaqrd.html

[R43] 按名字查找文件
来源：http://dali.yueranfly.top/Article/details/gt2bvbzjfqg.html

find . -name "*.log" -type f
来源：http://dali.jinghuilouyu.cn/Article/details/gt2otfbzwsg.html

[R44] 按修改时间查找
来源：http://dali.yj202588.top/Article/details/gt2rvesqqce.html

find . -mtime -7 -type f
来源：http://dali.xuanzx.com/Article/details/gt2jxlbdjru.html

[R45] 批量删除
来源：http://dali.yueranfly.top/Article/details/gt2gumlfshs.html

find . -name "*.tmp" -delete
来源：http://dali.jinqigufen.top/Article/details/gt2qkvzdmra.html

[R46] 递归替换文件内容
来源：http://dali.chenlongwang.top/Article/details/gt2ouyhkfkb.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.redwolf501.top/Article/details/gt2hlgyjndc.html

[R47] sed 单行替换
来源：http://dali.hysaishi.cn/Article/details/gt2dyjohihz.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.0kj1m.cn/Article/details/gt2zcifdytp.html

[R48] awk 取指定列
来源：http://dali.cqqwz.cn/Article/details/gt2eymjsosi.html

awk '{print $1, $3}' a.txt
来源：http://dali.hongshengwenyu.top/Article/details/gt2lazpgkfd.html

[R49] awk 带条件
来源：http://dali.xziqi.cn/Article/details/gt2dmgwmwbe.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.ydzc1.top/Article/details/gt2cbcphpio.html

[R50] awk 求和
来源：http://dali.xinyue.icu/Article/details/gt2uxvaixle.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ndkxpvsf.html

[R51] 排序去重取前几
来源：http://dali.0kj1m.cn/Article/details/gt2ukyxxpwj.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.yj202588.top/Article/details/gt2dvtgdbpd.html

[R52] 统计行数
来源：http://dali.gogol.net.cn/Article/details/gt2ujiijpro.html

wc -l a.txt
来源：http://dali.yj20258888.top/Article/details/gt2imhhrfev.html

[R53] 查看文件头与实时尾
来源：http://dali.havefunace.top/Article/details/gt2jjaiaggj.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.tian-w.cn/Article/details/gt2rnpezlyy.html

[R54] 比较两个文件
来源：http://dali.jqgufenzy.top/Article/details/gt2ngkoiknz.html

diff a.txt b.txt
来源：http://dali.zhoulong.xyz/Article/details/gt2dhoetvga.html

[R55] 压缩与解压
来源：http://dali.chenzaomai.com/Article/details/gt2bbolbfhj.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.0kj1m.cn/Article/details/gt2zmfvihmf.html

[R56] 远程拷贝
来源：http://dali.sweek.top/Article/details/gt2hwyboxxt.html

scp file user@host:/path/
来源：http://dali.gotoacloud.top/Article/details/gt2gkdjcgge.html

[R57] 远程执行命令
来源：http://dali.wangdashe.top/Article/details/gt2hofyqpvb.html

ssh user@host 'uptime'
来源：http://dali.sysykeji.top/Article/details/gt2ftneiwzn.html

[R58] 下载文件
来源：http://dali.ybcxt.top/Article/details/gt2plzjddyh.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.quarkkingdee.top/Article/details/gt2zxzfpaik.html

[R59] 发 POST JSON
来源：http://dali.xinyue.icu/Article/details/gt2ohegqunm.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.cqqwz.cn/Article/details/gt2swkxhtmq.html

[R60] 只看 HTTP 状态码
来源：http://dali.cdnleiting.top/Article/details/gt2qdahxvnv.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.xuetiantiany.cn/Article/details/gt2mwmhvsgl.html

[R61] 磁盘占用
来源：http://dali.shangyingyoupin.top/Article/details/gt2bolixyfj.html

df -h;  du -sh *
来源：http://dali.ybcxt.top/Article/details/gt2gdtshdrt.html

[R62] 找最占空间的文件
来源：http://dali.yongpay.top/Article/details/gt2motsblcd.html

du -ah . | sort -rh | head -10
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zbliqdif.html

[R63] 内存与进程
来源：http://dali.zhongyouzk.top/Article/details/gt2gzyugidg.html

free -h;  ps aux | grep nginx
来源：http://dali.andypj.xyz/Article/details/gt2rbdhiioy.html

[R64] 结束进程
来源：http://dali.dianchejie.cn/Article/details/gt2feekhoos.html

kill -9 $(pgrep -f app.py)
来源：http://dali.meibo888.top/Article/details/gt2fatnbrxz.html

[R65] 查看端口占用
来源：http://dali.0kj1m.cn/Article/details/gt2jwhfqxby.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.316326.xyz/Article/details/gt2myfkqylf.html

[R66] 定时任务
来源：http://dali.hfpthk.cn/Article/details/gt2jmxmmrab.html

crontab -e;  crontab -l
来源：http://dali.nwbrower.top/Article/details/gt2kmefbbdu.html

[R67] 生成随机十六进制串
来源：http://dali.daria6918.cn/Article/details/gt2cemkamsr.html

openssl rand -hex 16
来源：http://dali.iojbl.cn/Article/details/gt2lexuxitg.html

[R68] 计算文件校验值
来源：http://dali.jqgufenzy.top/Article/details/gt2inajqood.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.daria6918.cn/Article/details/gt2xlaalmxa.html

[R69] 生成随机密码
来源：http://dali.daxiang520.top/Article/details/gt2rztbcnpr.html

head -c 16 /dev/urandom | base64
来源：http://dali.sxryk.cn/Article/details/gt2vlftmxxp.html

[R70] 时间戳与互转
来源：http://dali.svipenyu.cn/Article/details/gt2xijrckzq.html

date +%s;  date -d @1700000000
来源：http://dali.andypj.xyz/Article/details/gt2qnetkorx.html

[R71] 日期格式化
来源：http://dali.cheryme.top/Article/details/gt2qtkjvxvu.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.hongshengwenyu.top/Article/details/gt2zwusvjgv.html

[R72] 等待端口就绪
来源：http://dali.chenlongwang.top/Article/details/gt2xnbibsus.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.xuanzx.com/Article/details/gt2fskiapiu.html

[R73] 分割大日志
来源：http://dali.cucudq.cn/Article/details/gt2bdgprccw.html

split -l 1000 big.log part_
来源：http://dali.aizwys.cn/Article/details/gt2mxcjnlhc.html

[R74] 批量重命名
来源：http://dali.cdnleiting.top/Article/details/gt2jwtyfhvv.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.9152youxi.cn/Article/details/gt2ygctmffi.html

[R75] 导出环境变量
来源：http://dali.jiagoushi.top/Article/details/gt2umfnjfws.html


<!-- 参考信息 -->