代发 wailian999

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.hammf.cn/Article/details/gt2kxunxhqj.html

[Q26] 计数
来源：http://dali.tian-w.cn/Article/details/gt2jnmgudeh.html

SELECT COUNT(*) FROM users;
来源：http://dali.redwolf501.top/Article/details/gt2oprgrnpm.html

[Q27] 条件计数
来源：http://dali.ivvv.top/Article/details/gt2edilglgg.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.havefunace.top/Article/details/gt2rgkilvts.html

[Q28] 求和与平均
来源：http://dali.xinyue.icu/Article/details/gt2keuunmgx.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.sweek.top/Article/details/gt2rubbnsqq.html

[Q29] 最大最小值
来源：http://dali.cdnleiting.top/Article/details/gt2zfsngnbg.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2inbawsxr.html

[Q30] 分组统计
来源：http://dali.jyoumei.cn/Article/details/gt2unqnvaqp.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.feifeiyinyue.top/Article/details/gt2xhswmfir.html

[Q31] 分组后过滤
来源：http://dali.yangfankeji.com/Article/details/gt2qtqgamqn.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.yanxiufei.cn/Article/details/gt2vspyuzkz.html

[Q32] 分组拼接字符串
来源：http://dali.daria6918.cn/Article/details/gt2trqgyuza.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.aibaodan.cn/Article/details/gt2quaycbuu.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.cqqwz.cn/Article/details/gt2kbunipcd.html

[Q33] 多列分组
来源：http://dali.tianlin.xyz/Article/details/gt2wcqyhoan.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.cucudq.cn/Article/details/gt2oqjptwzt.html

[Q34] 每组取第一条
来源：http://dali.dianchejie.cn/Article/details/gt2dcmagcir.html

SELECT * FROM (
来源：http://dali.kuanghao11.cn/Article/details/gt2visqaqms.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.jianghu66.top/Article/details/gt2hdfczkln.html

) t WHERE rn = 1;
来源：http://dali.daxiang520.top/Article/details/gt2cxibpopu.html

[Q35] 内连接
来源：http://dali.shangyingyoupin.top/Article/details/gt2wzltelzk.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.tianlin.xyz/Article/details/gt2wherjade.html

[Q36] 左连接
来源：http://dali.xinyue.icu/Article/details/gt2zxfpggou.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.fengsongda.top/Article/details/gt2wgzurthb.html

[Q37] 右连接
来源：http://dali.jianghu66.top/Article/details/gt2xwnherdb.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhixingplan.top/Article/details/gt2msozlaqr.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.pycfn.com/Article/details/gt2pkykcykw.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.sxryk.cn/Article/details/gt2nkwqixeb.html

[Q39] 自连接（查上下级）
来源：http://dali.c1oappe.top/Article/details/gt2jtmzwwsv.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.xylfe.cn/Article/details/gt2ivqjejwj.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.ppjwa.cn/Article/details/gt2jgyfotfb.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.chenlongwang.top/Article/details/gt2dqakynyi.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.guowangkeji.top/Article/details/gt2ztksehvi.html

[Q41] 多表连接
来源：http://dali.cucudq.cn/Article/details/gt2cdelorum.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.vqdsnc.cn/Article/details/gt2onytvvpd.html

JOIN users u ON u.id = o.user_id
来源：http://dali.316326.xyz/Article/details/gt2ckqtknac.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.nwbrower.top/Article/details/gt2guccctpz.html

[Q42] 连接条件附加过滤
来源：http://dali.gotoacloud.top/Article/details/gt2evqogmxg.html

SELECT u.name, o.amount FROM users u
来源：http://dali.guowangkeji.top/Article/details/gt2yixhevir.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.vqdsnc.cn/Article/details/gt2adyglujm.html

[Q43] 标量子查询
来源：http://dali.xylfe.cn/Article/details/gt2xjbphgev.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.nanxinkj.top/Article/details/gt2dqpqvdye.html

[Q44] IN 子查询
来源：http://dali.tianlin.xyz/Article/details/gt2snirjbie.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhiwuduotai.top/Article/details/gt2hgljcjrk.html

[Q45] EXISTS 判断存在
来源：http://dali.dashuyun.cn/Article/details/gt2usaeygbl.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.ppjwa.cn/Article/details/gt2txfybqym.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhengqikj.top/Article/details/gt2vnmhiqaj.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.aibaodan.cn/Article/details/gt2slhitsav.html

[Q47] 与平均值比较
来源：http://dali.guowangkeji.top/Article/details/gt2aiytyfzg.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.redwolf501.top/Article/details/gt2zqkmieqm.html

[Q48] CTE 公用表表达式
来源：http://dali.zhixingplan.top/Article/details/gt2irctrwzm.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.chenjidiqi.icu/Article/details/gt2hiomhtjh.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zycfv.cn/Article/details/gt2yjteboev.html

[Q49] 更新单行
来源：http://dali.316326.xyz/Article/details/gt2bsbauipx.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhengqikj.top/Article/details/gt2tkawjgmq.html

[Q50] 批量更新
来源：http://dali.hfpthk.cn/Article/details/gt2oejovrut.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.yj20258888.top/Article/details/gt2ohbvztri.html

[Q51] 用子查询更新
来源：http://dali.vqdsnc.cn/Article/details/gt2eamsfwed.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.mhx1999.top/Article/details/gt2ixlbxkul.html

[Q52] 删除指定行
来源：http://dali.0kj1m.cn/Article/details/gt2ffoaxvsc.html

DELETE FROM users WHERE id = 10;
来源：http://dali.meibo888.top/Article/details/gt2mkwhrpnk.html

[Q53] 按条件删除
来源：http://dali.yongpay.top/Article/details/gt2bfvinahr.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.mhx1999.top/Article/details/gt2wqrcxjrr.html

[Q54] 清空表
来源：http://dali.mhx1999.top/Article/details/gt2jfyodxlu.html

TRUNCATE TABLE logs;
来源：http://dali.nanxuanxn.top/Article/details/gt2vsnbaado.html

[Q55] 排名（并列占位）
来源：http://dali.shuidangran.top/Article/details/gt2idmnlbac.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.yueranfly.top/Article/details/gt2cmlrkebk.html

[Q56] 密集排名（并列不占位）
来源：http://dali.snrcjt.cn/Article/details/gt2nkohtnac.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.jianghu66.top/Article/details/gt2rbxvrobn.html

[Q57] 行号
来源：http://dali.yanxiufei.cn/Article/details/gt2okiqznkn.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.ppjwa.cn/Article/details/gt2tylxtzqe.html

[Q58] 累计求和
来源：http://dali.redwolf501.top/Article/details/gt2uqbirusm.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhiwuduotai.top/Article/details/gt2oazuqsuc.html

[Q59] 分组内累计
来源：http://dali.gzhubu.top/Article/details/gt2obtncyln.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.wangdashe.top/Article/details/gt2gexzwvsi.html

[Q60] 取上一行 / 下一行
来源：http://dali.svipenyu.cn/Article/details/gt2olsnciue.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.dianchejie.cn/Article/details/gt2nvvybiqz.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.0kj1m.cn/Article/details/gt2uvycnfce.html

[Q61] 移动平均
来源：http://dali.redwolf501.top/Article/details/gt2hkobladu.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.gotoacloud.top/Article/details/gt2fveyamxn.html

[Q62] 分组占比
来源：http://dali.sxryk.cn/Article/details/gt2xiuqydte.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.cheryme.top/Article/details/gt2qvtkiiob.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2uceircsm.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.xinyue.icu/Article/details/gt2caglxypi.html

[Q64] 提交事务
来源：http://dali.xziqi.cn/Article/details/gt2hantuhih.html

COMMIT;
来源：http://dali.xuanzx.com/Article/details/gt2haqsqhat.html

[Q65] 回滚事务
来源：http://dali.dashuyun.cn/Article/details/gt2folrljya.html

ROLLBACK;
来源：http://dali.pycfn.com/Article/details/gt2gnqapzhv.html

[Q66] 行锁查询
来源：http://dali.iojbl.cn/Article/details/gt2ptcgxttz.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.bjfxy.top/Article/details/gt2vkqwmemq.html

[Q67] 设置隔离级别
来源：http://dali.tanke756.top/Article/details/gt2dbojslqf.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.smart0.xyz/Article/details/gt2dpxzxwvg.html

[Q68] 保存点
来源：http://dali.hfpthk.cn/Article/details/gt2pavqnkow.html

SAVEPOINT sp1;
来源：http://dali.tianlin.xyz/Article/details/gt2whmswmbq.html

ROLLBACK TO sp1;
来源：http://dali.quarkkingdee.top/Article/details/gt2hqruvenh.html

[Q69] 查看执行计划
来源：http://dali.zhongyouzk.top/Article/details/gt2itmiysun.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.snrcjt.cn/Article/details/gt2orsxxhdk.html

[Q70] 更新统计信息
来源：http://dali.0kj1m.cn/Article/details/gt2nbukhxqo.html

ANALYZE TABLE users;
来源：http://dali.yvedp.cn/Article/details/gt2mogmonvm.html

[Q71] 查看建表语句
来源：http://dali.hnxiangtu.top/Article/details/gt2qsiyscac.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.svipenyu.cn/Article/details/gt2jnssrcux.html

[Q72] 查看索引
来源：http://dali.shuidangran.top/Article/details/gt2ipjezidn.html

SHOW INDEX FROM users;
来源：http://dali.wangshuangyany.cn/Article/details/gt2tbymhozx.html

[Q73] 查看表状态
来源：http://dali.yuanzhike.top/Article/details/gt2eaakilvg.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.shzxlz.cn/Article/details/gt2vjcrxrmb.html

[Q74] 强制使用索引
来源：http://dali.mhx1999.top/Article/details/gt2qrasedjz.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.xuanzx.com/Article/details/gt2iewkibwj.html

[Q75] 日期格式化
来源：http://dali.andypj.xyz/Article/details/gt2sfcuvdwh.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.dashuyun.cn/Article/details/gt2ayfquzct.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.nanxuanxn.top/Article/details/gt2sybefbra.html

[Q76] 按天统计
来源：http://dali.yonumen.top/Article/details/gt2uooahskz.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.ydzc1.top/Article/details/gt2dqxzamgt.html

[Q77] 时间加减
来源：http://dali.fengsongda.top/Article/details/gt2ukcivesa.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.dianchejie.cn/Article/details/gt2nzkvcqvs.html

[Q78] 当前时间
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vnqdmkmw.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhixingplan.top/Article/details/gt2wowiloez.html

[Q79] 字符串拼接
来源：http://dali.sxryk.cn/Article/details/gt2puzaybap.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.yanxiufei.cn/Article/details/gt2yhprivzd.html

[Q80] 字符串截取
来源：http://dali.xziqi.cn/Article/details/gt2iuyvkmlb.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pwwtbitr.html

[Q81] 字符串替换
来源：http://dali.chenlongwang.top/Article/details/gt2tltmskss.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.jlsjyb.cn/Article/details/gt2updhrstu.html

[Q82] 字符长度与字节长度
来源：http://dali.sweek.top/Article/details/gt2tqkoaerd.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gt2seiysvwh.html

[Q83] 大小写转换
来源：http://dali.gotoacloud.top/Article/details/gt2aahwfulh.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.aibaodan.cn/Article/details/gt2ymiipxun.html

[Q84] 去除首尾空格
来源：http://dali.xuetiantiany.cn/Article/details/gt2eahhrokj.html

SELECT TRIM(name) FROM users;
来源：http://dali.cucudq.cn/Article/details/gt2iajgnmlp.html

[Q85] 数值取整
来源：http://dali.chenlongwang.top/Article/details/gt2ujqbndcx.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.yj20258888.top/Article/details/gt2pbxfwgdu.html

[Q86] 读取 JSON 字段
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wrsfsvdt.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.sweek.top/Article/details/gt2pwcrdnfg.html

[Q87] JSON 字段做条件
来源：http://dali.daria6918.cn/Article/details/gt2vivyebcu.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.ivvv.top/Article/details/gt2wbcrevpj.html

[Q88] 行转列（条件聚合）
来源：http://dali.yueranfly.top/Article/details/gt2gpkfbvdv.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.haohaochexian.top/Article/details/gt2mnqthaht.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gt2jvocmztr.html

[Q89] 判断表是否存在
来源：http://dali.kuanghao11.cn/Article/details/gt2gpitbpom.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.chenzaomai.com/Article/details/gt2adnyyuss.html

[Q90] 生成序号列
来源：http://dali.yonumen.top/Article/details/gt2dhjeuguv.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.ybcxt.top/Article/details/gt2acrdsyyc.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2eburrlii.html

R. Bash 专题
来源：http://dali.hongshengwenyu.top/Article/details/gt2zmbbfnxl.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ghkfdavv.html

[R01] shebang 与严格模式
来源：http://dali.jqgufenzy.top/Article/details/gt2zvshujgp.html

#!/usr/bin/env bash
来源：http://dali.birdmap.top/Article/details/gt2xvdyjoww.html

set -euo pipefail
来源：http://dali.yj202588.top/Article/details/gt2scsuezji.html

[R02] 变量赋值与使用
来源：http://dali.jqgufenzy.top/Article/details/gt2oarzzzsi.html

name="Tom"; echo "$name"
来源：http://dali.jianghu66.top/Article/details/gt2gybnqizn.html

[R03] 只读变量
来源：http://dali.wangshuangyany.cn/Article/details/gt2bjeynaeb.html

readonly PI=3.14
来源：http://dali.shzxlz.cn/Article/details/gt2gqflvkmo.html

[R04] 位置参数
来源：http://dali.gogol.net.cn/Article/details/gt2nfsiljpz.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.redwolf501.top/Article/details/gt2eabnjfbc.html

[R05] 参数默认值
来源：http://dali.yvedp.cn/Article/details/gt2ldgsfyyo.html

name="${1:-default}"
来源：http://dali.sufxvd.cn/Article/details/gt2cdasprrq.html

[R06] 判断命令是否存在
来源：http://dali.haohaochexian.top/Article/details/gt2njkbhwzu.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2nagjzjpk.html

[R07] if 判断文件
来源：http://dali.bjfxy.top/Article/details/gt2glykfada.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.gogol.net.cn/Article/details/gt2hmlgcmbd.html

[R08] 数值比较
来源：http://dali.birdmap.top/Article/details/gt2xtwmhbtl.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.xuanzx.com/Article/details/gt2rssnairw.html

[R09] 字符串比较
来源：http://dali.tianlin.xyz/Article/details/gt2ztounftz.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.jinqigufen.top/Article/details/gt2wkbytale.html

[R10] 正则匹配
来源：http://dali.316326.xyz/Article/details/gt2kznstkpk.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.tian-w.cn/Article/details/gt2nywnwelo.html

[R11] case 多分支
来源：http://dali.sysykeji.top/Article/details/gt2jwzzrrla.html

case "$1" in
来源：http://dali.ydzc1.top/Article/details/gt2fqksozcj.html

start) echo "启动" ;;
来源：http://dali.dianchejie.cn/Article/details/gt2jyfpdkxo.html

stop)  echo "停止" ;;
来源：http://dali.smart0.xyz/Article/details/gt2emdyzyds.html

*)     echo "未知命令" ;;
来源：http://dali.daria6918.cn/Article/details/gt2izdnxhnm.html

esac
来源：http://dali.sweek.top/Article/details/gt2cfalhckg.html

[R12] for 遍历文件
来源：http://dali.zhixingplan.top/Article/details/gt2vqatdyly.html

for f in *.txt; do echo "$f"; done
来源：http://dali.smart0.xyz/Article/details/gt2bymhvbfo.html

[R13] for 计数循环
来源：http://dali.sweek.top/Article/details/gt2vwvhwymx.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.nanxuanxn.top/Article/details/gt2yjkstkpz.html

[R14] C 风格 for
来源：http://dali.yuxming.cn/Article/details/gt2zmsddcwp.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.dashuyun.cn/Article/details/gt2dyanbqdu.html

[R15] while 逐行读文件
来源：http://dali.jianghu66.top/Article/details/gt2iejwdqth.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.gogol.net.cn/Article/details/gt2xxgofduc.html

[R16] until 等待条件
来源：http://dali.redwolf501.top/Article/details/gt2gcumxdqu.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.yueranfly.top/Article/details/gt2ikjenubr.html

[R17] 数组定义与取值
来源：http://dali.guannengcc.top/Article/details/gt2bnlwjwkv.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.tianlin.xyz/Article/details/gt2zprwlury.html

[R18] 遍历数组
来源：http://dali.hywenlv.cn/Article/details/gt2ffpqzdop.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.xuanzx.com/Article/details/gt2lyosmqwz.html

[R19] 数组长度
来源：http://dali.gzhubu.top/Article/details/gt2chvgwenr.html

echo "${#arr[@]}"
来源：http://dali.chenzaomai.com/Article/details/gt2miwnnnwr.html

[R20] 关联数组（字典）
来源：http://dali.aibaodan.cn/Article/details/gt2ffbsmbdq.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.yueranfly.top/Article/details/gt2knkdeuak.html

[R21] 字符串长度
来源：http://dali.dashuyun.cn/Article/details/gt2imvvscel.html

echo "${#s}"
来源：http://dali.guowangkeji.top/Article/details/gt2dllcfcrc.html

[R22] 截取子串
来源：http://dali.chenlongwang.top/Article/details/gt2nysokffs.html

echo "${s:0:5}"
来源：http://dali.jyoumei.cn/Article/details/gt2hukssarn.html

[R23] 字符串替换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dhjupwpt.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhoulong.xyz/Article/details/gt2rbpcoqbx.html

[R24] 大小写转换
来源：http://dali.birdmap.top/Article/details/gt2dgofmsod.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.chenjidiqi.icu/Article/details/gt2jgpmbxnu.html

[R25] 去后缀 / 去前缀
来源：http://dali.yueranfly.top/Article/details/gt2goocrdbk.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.sysykeji.top/Article/details/gt2cbkbeqrj.html

[R26] 命令替换
来源：http://dali.ivvv.top/Article/details/gt2hnehhkwc.html

now=$(date +%F); echo "$now"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kkawckqr.html

[R27] 算术展开
来源：http://dali.tanke756.top/Article/details/gt2aucujdwp.html

echo $((1 + 2 * 3))
来源：http://dali.tian-w.cn/Article/details/gt2chmiizel.html

[R28] 浮点运算
来源：http://dali.yuxming.cn/Article/details/gt2keqoxqms.html

echo "scale=2; 10/3" | bc
来源：http://dali.yuanzhike.top/Article/details/gt2hzwqgxqw.html

[R29] 定义函数
来源：http://dali.dashuyun.cn/Article/details/gt2vovsggup.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.ivvv.top/Article/details/gt2ssnfwdib.html

[R30] 函数返回状态码
来源：http://dali.vqdsnc.cn/Article/details/gt2wawlnoax.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zdqjudy.top/Article/details/gt2vunagqfr.html

[R31] 局部变量
来源：http://dali.gzhubu.top/Article/details/gt2mcqqexux.html

f() { local x=1; echo "$x"; }
来源：http://dali.9152youxi.cn/Article/details/gt2gkkrvmyt.html

[R32] 参数个数校验
来源：http://dali.fzhhl.top/Article/details/gt2rydnoyxe.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.0kj1m.cn/Article/details/gt2lsyapyvc.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2ayienhmj.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.wangshuangyany.cn/Article/details/gt2uzglextx.html

[R34] 退出时清理
来源：http://dali.316326.xyz/Article/details/gt2yrpxokwf.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.fzhhl.top/Article/details/gt2hkshgche.html

[R35] 后台执行并等待
来源：http://dali.9152youxi.cn/Article/details/gt2qemliotz.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhoulong.xyz/Article/details/gt2goxzxilf.html

[R36] 并发执行多个任务
来源：http://dali.guowangkeji.top/Article/details/gt2rzqxygfg.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.fzhhl.top/Article/details/gt2kinyshxn.html

[R37] 把输出赋给变量
来源：http://dali.xylfe.cn/Article/details/gt2fefwvelt.html

files=$(ls -1)
来源：http://dali.hnqzz.top/Article/details/gt2midkxars.html

[R38] 管道串联
来源：http://dali.tanke756.top/Article/details/gt2qqokrvnp.html

cat a.txt | grep -i error | wc -l
来源：http://dali.snrcjt.cn/Article/details/gt2lcaxvzzl.html

[R39] 重定向标准输出与错误
来源：http://dali.gaohongyu789.top/Article/details/gt2grdfgzch.html

cmd > out.log 2>&1
来源：http://dali.ybcxt.top/Article/details/gt2qtahbnln.html

[R40] 追加写日志
来源：http://dali.tanke756.top/Article/details/gt2twhcbcfq.html

echo "log" >> out.log
来源：http://dali.vqdsnc.cn/Article/details/gt2danyamad.html

[R41] 丢弃输出
来源：http://dali.daxiang520.top/Article/details/gt2hedppbge.html

cmd >/dev/null 2>&1
来源：http://dali.jiagoushi.top/Article/details/gt2rtuptzgu.html

[R42] 输入重定向
来源：http://dali.gogol.net.cn/Article/details/gt2zuuqgznj.html

wc -l < a.txt
来源：http://dali.ehwqpu.com/Article/details/gt2uykmiygf.html

[R43] 按名字查找文件
来源：http://dali.guowangkeji.top/Article/details/gt2mkkeylob.html

find . -name "*.log" -type f
来源：http://dali.gotoacloud.top/Article/details/gt2kbdxeruq.html

[R44] 按修改时间查找
来源：http://dali.nanxuanxn.top/Article/details/gt2ihxmyzau.html

find . -mtime -7 -type f
来源：http://dali.yueranfly.top/Article/details/gt2bzeileab.html

[R45] 批量删除
来源：http://dali.nanxuanxn.top/Article/details/gt2pyecvjrz.html

find . -name "*.tmp" -delete
来源：http://dali.zycfv.cn/Article/details/gt2yxcmvyxp.html

[R46] 递归替换文件内容
来源：http://dali.gotoacloud.top/Article/details/gt2fdmbxfku.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.hnxiangtu.top/Article/details/gt2owueckxx.html

[R47] sed 单行替换
来源：http://dali.zhoulong.xyz/Article/details/gt2xusrsztb.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zycfv.cn/Article/details/gt2jtskdubz.html

[R48] awk 取指定列
来源：http://dali.wangshuangyany.cn/Article/details/gt2egkfohms.html

awk '{print $1, $3}' a.txt
来源：http://dali.ybcxt.top/Article/details/gt2dzzshpro.html

[R49] awk 带条件
来源：http://dali.zhixingplan.top/Article/details/gt2jtashlch.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.meibo888.top/Article/details/gt2rlubvxfk.html

[R50] awk 求和
来源：http://dali.9152youxi.cn/Article/details/gt2ztlaofru.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.sweek.top/Article/details/gt2awfeewou.html

[R51] 排序去重取前几
来源：http://dali.gogol.net.cn/Article/details/gt2fvqwwglc.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.jinqigfzy.top/Article/details/gt2fyvidqol.html

[R52] 统计行数
来源：http://dali.ehwqpu.com/Article/details/gt2rebbsjqt.html

wc -l a.txt
来源：http://dali.feifeiyinyue.top/Article/details/gt2ncakuyqs.html

[R53] 查看文件头与实时尾
来源：http://dali.sysykeji.top/Article/details/gt2mampgeut.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.yuxming.cn/Article/details/gt2dntcubqo.html

[R54] 比较两个文件
来源：http://dali.0kj1m.cn/Article/details/gt2fxkbceuk.html

diff a.txt b.txt
来源：http://dali.ybcxt.top/Article/details/gt2unbohulx.html

[R55] 压缩与解压
来源：http://dali.nwbrower.top/Article/details/gt2yjuglbxw.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.c1oappe.top/Article/details/gt2zleaulcq.html

[R56] 远程拷贝
来源：http://dali.dashuyun.cn/Article/details/gt2hbkpougw.html

scp file user@host:/path/
来源：http://dali.tanke756.top/Article/details/gt2sqicjish.html

[R57] 远程执行命令
来源：http://dali.sysykeji.top/Article/details/gt2ycfxqois.html

ssh user@host 'uptime'
来源：http://dali.xuanzx.com/Article/details/gt2dhjnybpk.html

[R58] 下载文件
来源：http://dali.zhixingplan.top/Article/details/gt2apjoayyo.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.hongshengwenyu.top/Article/details/gt2majrujzs.html

[R59] 发 POST JSON
来源：http://dali.316326.xyz/Article/details/gt2btlvcepd.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.cdnleiting.top/Article/details/gt2mdeofrlb.html

[R60] 只看 HTTP 状态码
来源：http://dali.jyoumei.cn/Article/details/gt2jryhsuyw.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.xuetiantiany.cn/Article/details/gt2kgraoypa.html

[R61] 磁盘占用
来源：http://dali.jinqigufen.top/Article/details/gt2lpsedqsx.html

df -h;  du -sh *
来源：http://dali.wangdashe.top/Article/details/gt2fbnnwjiw.html

[R62] 找最占空间的文件
来源：http://dali.hnxiangtu.top/Article/details/gt2lqixbdig.html

du -ah . | sort -rh | head -10
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zxiehfwq.html

[R63] 内存与进程
来源：http://dali.chenjidiqi.icu/Article/details/gt2fsmqhxci.html

free -h;  ps aux | grep nginx
来源：http://dali.feifeiyinyue.top/Article/details/gt2khfshaxm.html

[R64] 结束进程
来源：http://dali.gotoacloud.top/Article/details/gt2eetuvbnz.html

kill -9 $(pgrep -f app.py)
来源：http://dali.xuetiantiany.cn/Article/details/gt2zfzpbmah.html

[R65] 查看端口占用
来源：http://dali.haohaochexian.top/Article/details/gt2svtvbxns.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.fzhhl.top/Article/details/gt2bqqfekaq.html

[R66] 定时任务
来源：http://dali.cashguo.top/Article/details/gt2lmnpaomw.html

crontab -e;  crontab -l
来源：http://dali.yonumen.top/Article/details/gt2dzaxmvpm.html

[R67] 生成随机十六进制串
来源：http://dali.9152youxi.cn/Article/details/gt2yuybpflu.html

openssl rand -hex 16
来源：http://dali.jqgufenzy.top/Article/details/gt2mumpvqwm.html

[R68] 计算文件校验值
来源：http://dali.jinqigfzy.top/Article/details/gt2hvzivbrk.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.xziqi.cn/Article/details/gt2dpzgdwfq.html

[R69] 生成随机密码
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cbmfsisy.html

head -c 16 /dev/urandom | base64
来源：http://dali.jiagoushi.top/Article/details/gt2dgzpfwbz.html

[R70] 时间戳与互转
来源：http://dali.jiagoushi.top/Article/details/gt2osxnocqi.html

date +%s;  date -d @1700000000
来源：http://dali.birdmap.top/Article/details/gt2hptiwtld.html

[R71] 日期格式化
来源：http://dali.ehwqpu.com/Article/details/gt2qinpvnvs.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.iojbl.cn/Article/details/gt2kfwukoop.html

[R72] 等待端口就绪
来源：http://dali.zhongyouzk.top/Article/details/gt2hbamaifk.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zdqjudy.top/Article/details/gt2mnpebtuv.html

[R73] 分割大日志
来源：http://dali.hnqzz.top/Article/details/gt2yrbtjtqx.html

split -l 1000 big.log part_
来源：http://dali.mhx1999.top/Article/details/gt2uqkeruiq.html

[R74] 批量重命名
来源：http://dali.chenzaomai.com/Article/details/gt2pfgmmhrx.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.hysaishi.cn/Article/details/gt2gmalpnou.html

[R75] 导出环境变量
来源：http://dali.havefunace.top/Article/details/gt2iwjwqesu.html


<!-- 参考信息 -->