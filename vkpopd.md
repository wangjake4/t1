代发 wailian999

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.cucudq.cn/Article/details/gt2bduarmpf.html

[Q26] 计数
来源：http://dali.yanxiufei.cn/Article/details/gt2xfqbnquw.html

SELECT COUNT(*) FROM users;
来源：http://dali.hnqzz.top/Article/details/gt2ywknudyi.html

[Q27] 条件计数
来源：http://dali.bjfxy.top/Article/details/gt2pvgqnthj.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.fengsongda.top/Article/details/gt2srysrtui.html

[Q28] 求和与平均
来源：http://dali.jiagoushi.top/Article/details/gt2kfpwbkfl.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhongyouzk.top/Article/details/gt2kbzeukoy.html

[Q29] 最大最小值
来源：http://dali.vqdsnc.cn/Article/details/gt2fpelbqzc.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.wangdashe.top/Article/details/gt2kxvchjat.html

[Q30] 分组统计
来源：http://dali.kuanghao11.cn/Article/details/gt2cjkqjgve.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wuhrkbgs.html

[Q31] 分组后过滤
来源：http://dali.iojbl.cn/Article/details/gt2szglfftt.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.0kj1m.cn/Article/details/gt2dhtylcxr.html

[Q32] 分组拼接字符串
来源：http://dali.daria6918.cn/Article/details/gt2cbuhdzea.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.cqqwz.cn/Article/details/gt2pqfagbez.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.tianlin.xyz/Article/details/gt2iowayqqk.html

[Q33] 多列分组
来源：http://dali.smart0.xyz/Article/details/gt2gmxenarg.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.sxryk.cn/Article/details/gt2pwmzwmjv.html

[Q34] 每组取第一条
来源：http://dali.sxryk.cn/Article/details/gt2mdyjayff.html

SELECT * FROM (
来源：http://dali.9152youxi.cn/Article/details/gt2dnjzwdaz.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.sweek.top/Article/details/gt2cdexggvd.html

) t WHERE rn = 1;
来源：http://dali.hywenlv.cn/Article/details/gt2rddvijrv.html

[Q35] 内连接
来源：http://dali.wangshuangyany.cn/Article/details/gt2uellhafb.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.0kj1m.cn/Article/details/gt2vzffbuwy.html

[Q36] 左连接
来源：http://dali.yueranfly.top/Article/details/gt2hzrlfuua.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.yueranfly.top/Article/details/gt2zwamwmmk.html

[Q37] 右连接
来源：http://dali.zhengqikj.top/Article/details/gt2ejryygez.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.dashuyun.cn/Article/details/gt2hpmlbktw.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.tianlin.xyz/Article/details/gt2iyecvkpu.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.cashguo.top/Article/details/gt2vhacnlxt.html

[Q39] 自连接（查上下级）
来源：http://dali.yvedp.cn/Article/details/gt2khxlofmu.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.quarkkingdee.top/Article/details/gt2fjplnnev.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.cheryme.top/Article/details/gt2qckphfww.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.iojbl.cn/Article/details/gt2robqamcl.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2fczvwkbr.html

[Q41] 多表连接
来源：http://dali.hfpthk.cn/Article/details/gt2lafgrlwp.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.ydzc1.top/Article/details/gt2lmexdhqa.html

JOIN users u ON u.id = o.user_id
来源：http://dali.ppjwa.cn/Article/details/gt2ojtzofrk.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.shzxlz.cn/Article/details/gt2rlkdnypc.html

[Q42] 连接条件附加过滤
来源：http://dali.smart0.xyz/Article/details/gt2fxgsndqx.html

SELECT u.name, o.amount FROM users u
来源：http://dali.smart0.xyz/Article/details/gt2hopsjvsw.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhixingplan.top/Article/details/gt2xqgwnbpd.html

[Q43] 标量子查询
来源：http://dali.ehwqpu.com/Article/details/gt2oprkbbvf.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.dianchejie.cn/Article/details/gt2jxgxedzl.html

[Q44] IN 子查询
来源：http://dali.feifeiyinyue.top/Article/details/gt2mrcmfopo.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.nanxuanxn.top/Article/details/gt2grgvhtqx.html

[Q45] EXISTS 判断存在
来源：http://dali.chenlongwang.top/Article/details/gt2wxiowuem.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.cheryme.top/Article/details/gt2abubmdlj.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.shanyushiyangtech.top/Article/details/gt2riiwiiig.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.sufxvd.cn/Article/details/gt2lqbdrpgo.html

[Q47] 与平均值比较
来源：http://dali.316326.xyz/Article/details/gt2ygrwnybe.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.andypj.xyz/Article/details/gt2pfsagdhs.html

[Q48] CTE 公用表表达式
来源：http://dali.jqgfzy.top/Article/details/gt2adbuanwf.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.yuanzhike.top/Article/details/gt2ukasqpdb.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.jinqigfzy.top/Article/details/gt2pqthitcn.html

[Q49] 更新单行
来源：http://dali.gzhubu.top/Article/details/gt2mydmdyxy.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.ehwqpu.com/Article/details/gt2dnjagicz.html

[Q50] 批量更新
来源：http://dali.xuetiantiany.cn/Article/details/gt2ettwohcc.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.quarkkingdee.top/Article/details/gt2bhpsigpj.html

[Q51] 用子查询更新
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mjadrcae.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.cheryme.top/Article/details/gt2axgldcfb.html

[Q52] 删除指定行
来源：http://dali.chenjidiqi.icu/Article/details/gt2mmskgrrt.html

DELETE FROM users WHERE id = 10;
来源：http://dali.hammf.cn/Article/details/gt2lfvqhbqb.html

[Q53] 按条件删除
来源：http://dali.nanxuanxn.top/Article/details/gt2rhlqjqrk.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.pycfn.com/Article/details/gt2bspuipyx.html

[Q54] 清空表
来源：http://dali.gzhubu.top/Article/details/gt2ueilxybu.html

TRUNCATE TABLE logs;
来源：http://dali.jqgfzy.top/Article/details/gt2xcsyovjh.html

[Q55] 排名（并列占位）
来源：http://dali.xziqi.cn/Article/details/gt2zlvqtfqg.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.ivvv.top/Article/details/gt2utfplocs.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhongyouzk.top/Article/details/gt2gbyrawkj.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.havefunace.top/Article/details/gt2jzoukdel.html

[Q57] 行号
来源：http://dali.shzxlz.cn/Article/details/gt2lbnvswho.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dvxagshn.html

[Q58] 累计求和
来源：http://dali.dashuyun.cn/Article/details/gt2dbrpysth.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.316326.xyz/Article/details/gt2xgjhtinl.html

[Q59] 分组内累计
来源：http://dali.quarkkingdee.top/Article/details/gt2jqubpcbi.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.tanke756.top/Article/details/gt2ruofmgme.html

[Q60] 取上一行 / 下一行
来源：http://dali.xziqi.cn/Article/details/gt2cvdkowxc.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.havefunace.top/Article/details/gt2fxsjzkbw.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.sxryk.cn/Article/details/gt2piuxzhay.html

[Q61] 移动平均
来源：http://dali.wangshuangyany.cn/Article/details/gt2flelcqre.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.jqgfzy.top/Article/details/gt2ospwaajb.html

[Q62] 分组占比
来源：http://dali.iojbl.cn/Article/details/gt2rdgbsxkw.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.jiagoushi.top/Article/details/gt2cjdqlvje.html

[Q63] 开启事务
来源：http://dali.jinqigfzy.top/Article/details/gt2wthanqff.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.tianlin.xyz/Article/details/gt2fubfxxfx.html

[Q64] 提交事务
来源：http://dali.ybcxt.top/Article/details/gt2sqismcxe.html

COMMIT;
来源：http://dali.ybcxt.top/Article/details/gt2rmqxsati.html

[Q65] 回滚事务
来源：http://dali.jlsjyb.cn/Article/details/gt2bgvaiqxh.html

ROLLBACK;
来源：http://dali.wangdashe.top/Article/details/gt2gchtzbgl.html

[Q66] 行锁查询
来源：http://dali.smart0.xyz/Article/details/gt2iyefdfkg.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.xuanzx.com/Article/details/gt2sdqxnxmh.html

[Q67] 设置隔离级别
来源：http://dali.0kj1m.cn/Article/details/gt2xxzsffro.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.aibaodan.cn/Article/details/gt2civyweon.html

[Q68] 保存点
来源：http://dali.chenzaomai.com/Article/details/gt2otslaufx.html

SAVEPOINT sp1;
来源：http://dali.gogol.net.cn/Article/details/gt2snwrjvaa.html

ROLLBACK TO sp1;
来源：http://dali.vqdsnc.cn/Article/details/gt2tnsutfvh.html

[Q69] 查看执行计划
来源：http://dali.jinqigfzy.top/Article/details/gt2idrtfasp.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.yj20258888.top/Article/details/gt2rqfxypnf.html

[Q70] 更新统计信息
来源：http://dali.fzhhl.top/Article/details/gt2frwxfqiv.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2sgqbgtkf.html

[Q71] 查看建表语句
来源：http://dali.jyoumei.cn/Article/details/gt2leftxqxg.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.svipenyu.cn/Article/details/gt2sgidlhui.html

[Q72] 查看索引
来源：http://dali.hnxiangtu.top/Article/details/gt2grtsjxnn.html

SHOW INDEX FROM users;
来源：http://dali.hywenlv.cn/Article/details/gt2xcyfausb.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2pbnydaqq.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.yonumen.top/Article/details/gt2mnewzxyu.html

[Q74] 强制使用索引
来源：http://dali.gogol.net.cn/Article/details/gt2pwerildl.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.bjfxy.top/Article/details/gt2ahioktkx.html

[Q75] 日期格式化
来源：http://dali.nanxinkj.top/Article/details/gt2vgghprzb.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.dashuyun.cn/Article/details/gt2bsgualli.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.yuxming.cn/Article/details/gt2ejnnkowy.html

[Q76] 按天统计
来源：http://dali.zhoulong.xyz/Article/details/gt2lvjfxwgr.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.andypj.xyz/Article/details/gt2zqsjqsqo.html

[Q77] 时间加减
来源：http://dali.wangshuangyany.cn/Article/details/gt2ourikajt.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.jqgufenzy.top/Article/details/gt2qyzaqahy.html

[Q78] 当前时间
来源：http://dali.xuetiantiany.cn/Article/details/gt2ootgaqgf.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.guannengcc.top/Article/details/gt2cdipzjuz.html

[Q79] 字符串拼接
来源：http://dali.jqgufenzy.top/Article/details/gt2ovzihdsl.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.meibo888.top/Article/details/gt2jvjfsiqh.html

[Q80] 字符串截取
来源：http://dali.hnqzz.top/Article/details/gt2exioossf.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.chenlongwang.top/Article/details/gt2ytiwvpyz.html

[Q81] 字符串替换
来源：http://dali.jlsjyb.cn/Article/details/gt2bayuwsey.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.jinqigufen.top/Article/details/gt2kgrcorab.html

[Q82] 字符长度与字节长度
来源：http://dali.hnxiangtu.top/Article/details/gt2nxzencud.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.yvedp.cn/Article/details/gt2inlapbgr.html

[Q83] 大小写转换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wzvupynj.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.pycfn.com/Article/details/gt2gydosonm.html

[Q84] 去除首尾空格
来源：http://dali.tian-w.cn/Article/details/gt2oapuorfc.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhoulong.xyz/Article/details/gt2oglbcpmf.html

[Q85] 数值取整
来源：http://dali.aibaodan.cn/Article/details/gt2mxftmckz.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.redwolf501.top/Article/details/gt2lfogssfq.html

[Q86] 读取 JSON 字段
来源：http://dali.0kj1m.cn/Article/details/gt2ynolsifx.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.vqdsnc.cn/Article/details/gt2czecjref.html

[Q87] JSON 字段做条件
来源：http://dali.yueranfly.top/Article/details/gt2exhypzdg.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhixingplan.top/Article/details/gt2fhzybetm.html

[Q88] 行转列（条件聚合）
来源：http://dali.hnqzz.top/Article/details/gt2ruuglfka.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.nwbrower.top/Article/details/gt2zeoauwcp.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.smart0.xyz/Article/details/gt2lqykrkdr.html

[Q89] 判断表是否存在
来源：http://dali.meibo888.top/Article/details/gt2mkofeizl.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.havefunace.top/Article/details/gt2dqjyobtu.html

[Q90] 生成序号列
来源：http://dali.pycfn.com/Article/details/gt2crkiomsc.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.quarkkingdee.top/Article/details/gt2bjkkzjyz.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2rwdogbew.html

R. Bash 专题
来源：http://dali.jinqigufen.top/Article/details/gt2uecpusuc.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gt2dqpkptgb.html

[R01] shebang 与严格模式
来源：http://dali.sysykeji.top/Article/details/gt2qrhfquhh.html

#!/usr/bin/env bash
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2whosvemw.html

set -euo pipefail
来源：http://dali.yanxiufei.cn/Article/details/gt2ogrqfpzm.html

[R02] 变量赋值与使用
来源：http://dali.dashuyun.cn/Article/details/gt2ydauqakq.html

name="Tom"; echo "$name"
来源：http://dali.pycfn.com/Article/details/gt2cayopxfl.html

[R03] 只读变量
来源：http://dali.guannengcc.top/Article/details/gt2rjhxkyre.html

readonly PI=3.14
来源：http://dali.zhoulong.xyz/Article/details/gt2dntleifr.html

[R04] 位置参数
来源：http://dali.snrcjt.cn/Article/details/gt2uiktynut.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.smart0.xyz/Article/details/gt2vrxddbpx.html

[R05] 参数默认值
来源：http://dali.nanxinkj.top/Article/details/gt2ykqravpd.html

name="${1:-default}"
来源：http://dali.yanxiufei.cn/Article/details/gt2muntwpgh.html

[R06] 判断命令是否存在
来源：http://dali.zhengqikj.top/Article/details/gt2kczwfjex.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.yueranfly.top/Article/details/gt2fpirqpxv.html

[R07] if 判断文件
来源：http://dali.meibo888.top/Article/details/gt2kpyflxil.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.yonumen.top/Article/details/gt2cfrwmryc.html

[R08] 数值比较
来源：http://dali.yuanzhike.top/Article/details/gt2govetqxx.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.yongpay.top/Article/details/gt2odtikphm.html

[R09] 字符串比较
来源：http://dali.gogol.net.cn/Article/details/gt2dyychywo.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.pengpengdd.cyou/Article/details/gt2crrcpksu.html

[R10] 正则匹配
来源：http://dali.jiagoushi.top/Article/details/gt2qgquqvol.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.316326.xyz/Article/details/gt2iufhxymh.html

[R11] case 多分支
来源：http://dali.cheryme.top/Article/details/gt2uzvhatlp.html

case "$1" in
来源：http://dali.pycfn.com/Article/details/gt2mmkmoudx.html

start) echo "启动" ;;
来源：http://dali.ppjwa.cn/Article/details/gt2nokyjaje.html

stop)  echo "停止" ;;
来源：http://dali.shzxlz.cn/Article/details/gt2xsrwihyl.html

*)     echo "未知命令" ;;
来源：http://dali.aizwys.cn/Article/details/gt2efrywmvc.html

esac
来源：http://dali.hnqzz.top/Article/details/gt2kdsajtol.html

[R12] for 遍历文件
来源：http://dali.yuanzhike.top/Article/details/gt2saaiqine.html

for f in *.txt; do echo "$f"; done
来源：http://dali.hongshengwenyu.top/Article/details/gt2ihlmewxy.html

[R13] for 计数循环
来源：http://dali.sxryk.cn/Article/details/gt2znfdzjrx.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.316326.xyz/Article/details/gt2lcdjdiqv.html

[R14] C 风格 for
来源：http://dali.ybcxt.top/Article/details/gt2hfgpuvhh.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.aizwys.cn/Article/details/gt2awqkyuvs.html

[R15] while 逐行读文件
来源：http://dali.ybcxt.top/Article/details/gt2ogwseank.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.yj20258.top/Article/details/gt2ogxenzjr.html

[R16] until 等待条件
来源：http://dali.aizwys.cn/Article/details/gt2wvbmhqtd.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.yj20258888.top/Article/details/gt2zlpcasls.html

[R17] 数组定义与取值
来源：http://dali.hammf.cn/Article/details/gt2kxpmrkwf.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.hysaishi.cn/Article/details/gt2xjncgqwd.html

[R18] 遍历数组
来源：http://dali.birdmap.top/Article/details/gt2zvugxavi.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.jinqigfzy.top/Article/details/gt2viqdhagp.html

[R19] 数组长度
来源：http://dali.shuidangran.top/Article/details/gt2htnjklda.html

echo "${#arr[@]}"
来源：http://dali.jqgufenzy.top/Article/details/gt2plcrjplq.html

[R20] 关联数组（字典）
来源：http://dali.jqgufenzy.top/Article/details/gt2qdejcsim.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.316326.xyz/Article/details/gt2vlqgdfjb.html

[R21] 字符串长度
来源：http://dali.zhixingplan.top/Article/details/gt2dewbpioi.html

echo "${#s}"
来源：http://dali.snrcjt.cn/Article/details/gt2wevnvtin.html

[R22] 截取子串
来源：http://dali.jianghu66.top/Article/details/gt2ktghkjsx.html

echo "${s:0:5}"
来源：http://dali.gogol.net.cn/Article/details/gt2wxpdlbrr.html

[R23] 字符串替换
来源：http://dali.ehwqpu.com/Article/details/gt2jcawzmxp.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.guannengcc.top/Article/details/gt2ywpkttqm.html

[R24] 大小写转换
来源：http://dali.yuanzhike.top/Article/details/gt2nfchizci.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.yuanzhike.top/Article/details/gt2kwnsrjhm.html

[R25] 去后缀 / 去前缀
来源：http://dali.guowangkeji.top/Article/details/gt2snjjgzpv.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.smart0.xyz/Article/details/gt2svhesals.html

[R26] 命令替换
来源：http://dali.yongpay.top/Article/details/gt2jrsmzsni.html

now=$(date +%F); echo "$now"
来源：http://dali.hywenlv.cn/Article/details/gt2qmpmpbge.html

[R27] 算术展开
来源：http://dali.haohaochexian.top/Article/details/gt2hfseegey.html

echo $((1 + 2 * 3))
来源：http://dali.shuidangran.top/Article/details/gt2tbkixvvv.html

[R28] 浮点运算
来源：http://dali.xziqi.cn/Article/details/gt2xfnvohku.html

echo "scale=2; 10/3" | bc
来源：http://dali.snrcjt.cn/Article/details/gt2lgyddmhn.html

[R29] 定义函数
来源：http://dali.andypj.xyz/Article/details/gt2yhsefdmv.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.jqgufenzy.top/Article/details/gt2wshvpjzo.html

[R30] 函数返回状态码
来源：http://dali.aizwys.cn/Article/details/gt2mqudtvie.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.shuidangran.top/Article/details/gt2hodktjed.html

[R31] 局部变量
来源：http://dali.havefunace.top/Article/details/gt2pkronkjd.html

f() { local x=1; echo "$x"; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2msgyjpkr.html

[R32] 参数个数校验
来源：http://dali.yj202588.top/Article/details/gt2ysgpawdy.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.fengsongda.top/Article/details/gt2wfykprzs.html

[R33] 捕获错误并提示行号
来源：http://dali.vqdsnc.cn/Article/details/gt2uxkdnplk.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.wangshuangyany.cn/Article/details/gt2aenyjomj.html

[R34] 退出时清理
来源：http://dali.yj20258.top/Article/details/gt2jpnsmthd.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.xylfe.cn/Article/details/gt2dqdynhse.html

[R35] 后台执行并等待
来源：http://dali.tanke756.top/Article/details/gt2whzskzpt.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhoulong.xyz/Article/details/gt2nutkpacj.html

[R36] 并发执行多个任务
来源：http://dali.havefunace.top/Article/details/gt2gqhjfnri.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.vqdsnc.cn/Article/details/gt2krijpjsg.html

[R37] 把输出赋给变量
来源：http://dali.316326.xyz/Article/details/gt2tdjqsuac.html

files=$(ls -1)
来源：http://dali.c1oappe.top/Article/details/gt2ijrjvujb.html

[R38] 管道串联
来源：http://dali.aibaodan.cn/Article/details/gt2dswcbxpm.html

cat a.txt | grep -i error | wc -l
来源：http://dali.xylfe.cn/Article/details/gt2gcwyrxas.html

[R39] 重定向标准输出与错误
来源：http://dali.fengsongda.top/Article/details/gt2cqgvcesv.html

cmd > out.log 2>&1
来源：http://dali.jinqigufen.top/Article/details/gt2cezqwzkm.html

[R40] 追加写日志
来源：http://dali.hysaishi.cn/Article/details/gt2btpjzjow.html

echo "log" >> out.log
来源：http://dali.aizwys.cn/Article/details/gt2ryyyyldk.html

[R41] 丢弃输出
来源：http://dali.yvedp.cn/Article/details/gt2mrhuwnsa.html

cmd >/dev/null 2>&1
来源：http://dali.jyoumei.cn/Article/details/gt2dmfdtlqa.html

[R42] 输入重定向
来源：http://dali.yuxming.cn/Article/details/gt2ooeoujyc.html

wc -l < a.txt
来源：http://dali.yj202588.top/Article/details/gt2ubexepjt.html

[R43] 按名字查找文件
来源：http://dali.yongpay.top/Article/details/gt2nsaowuol.html

find . -name "*.log" -type f
来源：http://dali.jinqigfzy.top/Article/details/gt2yxzefkal.html

[R44] 按修改时间查找
来源：http://dali.jlsjyb.cn/Article/details/gt2iqnzuasg.html

find . -mtime -7 -type f
来源：http://dali.shzxlz.cn/Article/details/gt2nmwkcuwg.html

[R45] 批量删除
来源：http://dali.vqdsnc.cn/Article/details/gt2stgbyrpx.html

find . -name "*.tmp" -delete
来源：http://dali.gotoacloud.top/Article/details/gt2ygwveiea.html

[R46] 递归替换文件内容
来源：http://dali.zhiwuduotai.top/Article/details/gt2shtwcrbg.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.havefunace.top/Article/details/gt2iifmltbe.html

[R47] sed 单行替换
来源：http://dali.chenjidiqi.icu/Article/details/gt2olvjwfsh.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.birdmap.top/Article/details/gt2jbsoglwi.html

[R48] awk 取指定列
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tlefautu.html

awk '{print $1, $3}' a.txt
来源：http://dali.vqdsnc.cn/Article/details/gt2oazxplvz.html

[R49] awk 带条件
来源：http://dali.dianchejie.cn/Article/details/gt2ngxmiiek.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.yuanzhike.top/Article/details/gt2deecnvpn.html

[R50] awk 求和
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sorqhkox.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.svipenyu.cn/Article/details/gt2meeyffkh.html

[R51] 排序去重取前几
来源：http://dali.cdnleiting.top/Article/details/gt2pyguvsgi.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.jqgfzy.top/Article/details/gt2ymtfdknk.html

[R52] 统计行数
来源：http://dali.ppjwa.cn/Article/details/gt2zlabbkbp.html

wc -l a.txt
来源：http://dali.xylfe.cn/Article/details/gt2qglfvuho.html

[R53] 查看文件头与实时尾
来源：http://dali.zdqjudy.top/Article/details/gt2vynczmui.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.tianlin.xyz/Article/details/gt2ahnwwokz.html

[R54] 比较两个文件
来源：http://dali.pycfn.com/Article/details/gt2sfpiemsr.html

diff a.txt b.txt
来源：http://dali.9152youxi.cn/Article/details/gt2vnygykld.html

[R55] 压缩与解压
来源：http://dali.hfpthk.cn/Article/details/gt2eqlkxgtm.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhoulong.xyz/Article/details/gt2dhlsnpfk.html

[R56] 远程拷贝
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xtjurhqb.html

scp file user@host:/path/
来源：http://dali.yj20258.top/Article/details/gt2tysrtwhm.html

[R57] 远程执行命令
来源：http://dali.redwolf501.top/Article/details/gt2duwhtxcj.html

ssh user@host 'uptime'
来源：http://dali.sweek.top/Article/details/gt2wvghyhzq.html

[R58] 下载文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vjrqeusg.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhongyouzk.top/Article/details/gt2nwvkknwn.html

[R59] 发 POST JSON
来源：http://dali.dashuyun.cn/Article/details/gt2etxxazxp.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.daxiang520.top/Article/details/gt2kocdhgwm.html

[R60] 只看 HTTP 状态码
来源：http://dali.hongshengwenyu.top/Article/details/gt2etukznhq.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.feifeiyinyue.top/Article/details/gt2zkshdnqg.html

[R61] 磁盘占用
来源：http://dali.yuxming.cn/Article/details/gt2qgnvmqmq.html

df -h;  du -sh *
来源：http://dali.hammf.cn/Article/details/gt2tsruuqhn.html

[R62] 找最占空间的文件
来源：http://dali.0kj1m.cn/Article/details/gt2ntghjqlf.html

du -ah . | sort -rh | head -10
来源：http://dali.meibo888.top/Article/details/gt2fklvrjzu.html

[R63] 内存与进程
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wkwquboz.html

free -h;  ps aux | grep nginx
来源：http://dali.sweek.top/Article/details/gt2eubzrncc.html

[R64] 结束进程
来源：http://dali.bjfxy.top/Article/details/gt2cfdndboz.html

kill -9 $(pgrep -f app.py)
来源：http://dali.xinyue.icu/Article/details/gt2zfmbvsiv.html

[R65] 查看端口占用
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2blhnaozh.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.jinqigfzy.top/Article/details/gt2vpmfjeoc.html

[R66] 定时任务
来源：http://dali.jianghu66.top/Article/details/gt2wnreuzeq.html

crontab -e;  crontab -l
来源：http://dali.316326.xyz/Article/details/gt2qzuzktcl.html

[R67] 生成随机十六进制串
来源：http://dali.dianchejie.cn/Article/details/gt2thkxjtkl.html

openssl rand -hex 16
来源：http://dali.aibaodan.cn/Article/details/gt2hvurueib.html

[R68] 计算文件校验值
来源：http://dali.feifeiyinyue.top/Article/details/gt2ahhmfued.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pilybgml.html

[R69] 生成随机密码
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tmglynxv.html

head -c 16 /dev/urandom | base64
来源：http://dali.cqqwz.cn/Article/details/gt2jjscmajo.html

[R70] 时间戳与互转
来源：http://dali.aibaodan.cn/Article/details/gt2siuueqen.html

date +%s;  date -d @1700000000
来源：http://dali.jlsjyb.cn/Article/details/gt2lkhednsl.html

[R71] 日期格式化
来源：http://dali.xziqi.cn/Article/details/gt2qbzikumy.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhengqikj.top/Article/details/gt2tsuwrxor.html

[R72] 等待端口就绪
来源：http://dali.guowangkeji.top/Article/details/gt2yioavoqi.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.jinqigufen.top/Article/details/gt2viqaveft.html

[R73] 分割大日志
来源：http://dali.vqdsnc.cn/Article/details/gt2mzhobssi.html

split -l 1000 big.log part_
来源：http://dali.jqgfzy.top/Article/details/gt2ggafsknv.html

[R74] 批量重命名
来源：http://dali.shanyushiyangtech.top/Article/details/gt2edcsqgrm.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.sysykeji.top/Article/details/gt2dxqoelrb.html

[R75] 导出环境变量
来源：http://dali.yj20258888.top/Article/details/gt2zijooybs.html


<!-- 参考信息 -->