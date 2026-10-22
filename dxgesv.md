代发 wailian999

SELECT * FROM users;
来源：http://dali.0kj1m.cn/Article/details/gt2hqmwrazj.html

[Q16] 查询指定列
来源：http://dali.sufxvd.cn/Article/details/gt2dmpeelbw.html

SELECT id, name FROM users;
来源：http://dali.tian-w.cn/Article/details/gt2xvscdmwu.html

[Q17] 条件查询
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uoqpxvno.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.gaohongyu789.top/Article/details/gt2qksxwhbm.html

[Q18] 模糊匹配
来源：http://dali.jyoumei.cn/Article/details/gt2habknmvr.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.hnxiangtu.top/Article/details/gt2avqwixql.html

[Q19] 范围查询
来源：http://dali.wangshuangyany.cn/Article/details/gt2zasexmiz.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.xinyue.icu/Article/details/gt2wqoocwzr.html

[Q20] IN 列表
来源：http://dali.0kj1m.cn/Article/details/gt2wlmblxsc.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.jyoumei.cn/Article/details/gt2mwcqeuyc.html

[Q21] 空值判断
来源：http://dali.jinqigufen.top/Article/details/gt2ctnfldrw.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.yanxiufei.cn/Article/details/gt2denhrvmj.html

[Q22] 排序
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kyhokpwt.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.hnqzz.top/Article/details/gt2kxoajueq.html

[Q23] 分页
来源：http://dali.mhx1999.top/Article/details/gt2vajlkaho.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.xylfe.cn/Article/details/gt2tptkufhk.html

[Q24] 去重
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gyylhasl.html

SELECT DISTINCT city FROM users;
来源：http://dali.ybcxt.top/Article/details/gt2fhgbkema.html

[Q25] 只取前 N 条
来源：http://dali.yuxming.cn/Article/details/gt2usrsgjtm.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.hysaishi.cn/Article/details/gt2zedizjcv.html

[Q26] 计数
来源：http://dali.wangshuangyany.cn/Article/details/gt2krboyuci.html

SELECT COUNT(*) FROM users;
来源：http://dali.cheryme.top/Article/details/gt2xubrdmyy.html

[Q27] 条件计数
来源：http://dali.xuanzx.com/Article/details/gt2efjbyfpo.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.ehwqpu.com/Article/details/gt2anqkngvo.html

[Q28] 求和与平均
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fqwiytju.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.ybcxt.top/Article/details/gt2feiyjkzv.html

[Q29] 最大最小值
来源：http://dali.jqgufenzy.top/Article/details/gt2mqkhmhxe.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.yueranfly.top/Article/details/gt2rhszufwb.html

[Q30] 分组统计
来源：http://dali.yongpay.top/Article/details/gt2qdaigczz.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.mhx1999.top/Article/details/gt2gnynmjok.html

[Q31] 分组后过滤
来源：http://dali.yuanzhike.top/Article/details/gt2mmdehomw.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.jinqigfzy.top/Article/details/gt2pzgkqudk.html

[Q32] 分组拼接字符串
来源：http://dali.xylfe.cn/Article/details/gt2slqxnjed.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.kuanghao11.cn/Article/details/gt2djcfxwtz.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.jqgufenzy.top/Article/details/gt2qxzvfnca.html

[Q33] 多列分组
来源：http://dali.xylfe.cn/Article/details/gt2lgffwcye.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.jinqigfzy.top/Article/details/gt2fcfptczt.html

[Q34] 每组取第一条
来源：http://dali.yanxiufei.cn/Article/details/gt2efnrxuzy.html

SELECT * FROM (
来源：http://dali.andypj.xyz/Article/details/gt2cnjxccqa.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fshkpwxo.html

) t WHERE rn = 1;
来源：http://dali.yj20258.top/Article/details/gt2zfvhupun.html

[Q35] 内连接
来源：http://dali.gaohongyu789.top/Article/details/gt2utyluffi.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.sweek.top/Article/details/gt2wretbyyc.html

[Q36] 左连接
来源：http://dali.hysaishi.cn/Article/details/gt2ufrsspbl.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.kuanghao11.cn/Article/details/gt2dsinvqil.html

[Q37] 右连接
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ggjafuvo.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.daria6918.cn/Article/details/gt2fbvcwbih.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.9152youxi.cn/Article/details/gt2zovouwtk.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zipwxtcg.html

[Q39] 自连接（查上下级）
来源：http://dali.xinyue.icu/Article/details/gt2ehvloxdv.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.jianghu66.top/Article/details/gt2nafvjhsa.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.yanxiufei.cn/Article/details/gt2xkwpaket.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.nwbrower.top/Article/details/gt2tkjrelxq.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.jyoumei.cn/Article/details/gt2onmraywq.html

[Q41] 多表连接
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ttkxnrxs.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.shuidangran.top/Article/details/gt2ykdknnrz.html

JOIN users u ON u.id = o.user_id
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pxtcgdeq.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hskbishx.html

[Q42] 连接条件附加过滤
来源：http://dali.nanxinkj.top/Article/details/gt2vlmphcss.html

SELECT u.name, o.amount FROM users u
来源：http://dali.xylfe.cn/Article/details/gt2piunprxv.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.meibo888.top/Article/details/gt2tdfipqpb.html

[Q43] 标量子查询
来源：http://dali.hnqzz.top/Article/details/gt2yooqkyal.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ragrdhia.html

[Q44] IN 子查询
来源：http://dali.shuidangran.top/Article/details/gt2hftdowma.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rhtfaoss.html

[Q45] EXISTS 判断存在
来源：http://dali.c1oappe.top/Article/details/gt2dgbgulns.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.bjfxy.top/Article/details/gt2bbzgnpdk.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tunnpote.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yuanzhike.top/Article/details/gt2kwjewsdd.html

[Q47] 与平均值比较
来源：http://dali.pengpengdd.cyou/Article/details/gt2drrdexau.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.nanxinkj.top/Article/details/gt2zgtrqafl.html

[Q48] CTE 公用表表达式
来源：http://dali.yj202588.top/Article/details/gt2cemstfqn.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.haohaochexian.top/Article/details/gt2ccehalym.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.haohaochexian.top/Article/details/gt2ssmthzjb.html

[Q49] 更新单行
来源：http://dali.andypj.xyz/Article/details/gt2ededxyli.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.ivvv.top/Article/details/gt2lmdzjnrl.html

[Q50] 批量更新
来源：http://dali.shzxlz.cn/Article/details/gt2vyflravd.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.tian-w.cn/Article/details/gt2ljvoufut.html

[Q51] 用子查询更新
来源：http://dali.jinqigfzy.top/Article/details/gt2ffttgkpc.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.hongshengwenyu.top/Article/details/gt2nzqmdbln.html

[Q52] 删除指定行
来源：http://dali.sysykeji.top/Article/details/gt2otnkesoc.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2myjwvudv.html

[Q53] 按条件删除
来源：http://dali.chenzaomai.com/Article/details/gt2oiokchzg.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xfynmaxv.html

[Q54] 清空表
来源：http://dali.hammf.cn/Article/details/gt2ztmnhzus.html

TRUNCATE TABLE logs;
来源：http://dali.redwolf501.top/Article/details/gt2gooiydfe.html

[Q55] 排名（并列占位）
来源：http://dali.yj20258.top/Article/details/gt2lpzkzpdd.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.fengsongda.top/Article/details/gt2mjhptpgz.html

[Q56] 密集排名（并列不占位）
来源：http://dali.c1oappe.top/Article/details/gt2slomjpwo.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.hfpthk.cn/Article/details/gt2ytfwzlij.html

[Q57] 行号
来源：http://dali.jiagoushi.top/Article/details/gt2ivqhedcn.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.0kj1m.cn/Article/details/gt2coijvjyo.html

[Q58] 累计求和
来源：http://dali.andypj.xyz/Article/details/gt2cbeowbab.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.shzxlz.cn/Article/details/gt2mcgmogki.html

[Q59] 分组内累计
来源：http://dali.yanxiufei.cn/Article/details/gt2twmokxdi.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.chenjidiqi.icu/Article/details/gt2sytqvywr.html

[Q60] 取上一行 / 下一行
来源：http://dali.xuanzx.com/Article/details/gt2atrjzkab.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.cucudq.cn/Article/details/gt2ahkrgdyh.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.chenzaomai.com/Article/details/gt2xeebcwbg.html

[Q61] 移动平均
来源：http://dali.ydzc1.top/Article/details/gt2zuqwfnxs.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.pycfn.com/Article/details/gt2aimikyzu.html

[Q62] 分组占比
来源：http://dali.tanke756.top/Article/details/gt2laypytmf.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.wangshuangyany.cn/Article/details/gt2srmwohdk.html

[Q63] 开启事务
来源：http://dali.jyoumei.cn/Article/details/gt2ztwppnqz.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.jqgfzy.top/Article/details/gt2winurlpz.html

[Q64] 提交事务
来源：http://dali.kuanghao11.cn/Article/details/gt2mfvsjgzd.html

COMMIT;
来源：http://dali.cqqwz.cn/Article/details/gt2bhptzfgn.html

[Q65] 回滚事务
来源：http://dali.birdmap.top/Article/details/gt2dlovybnm.html

ROLLBACK;
来源：http://dali.hnxiangtu.top/Article/details/gt2kqbolpfs.html

[Q66] 行锁查询
来源：http://dali.pengpengdd.cyou/Article/details/gt2wbxtdjvp.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.ivvv.top/Article/details/gt2bczpgqvq.html

[Q67] 设置隔离级别
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xgwrkteq.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.nwbrower.top/Article/details/gt2pcvpclnr.html

[Q68] 保存点
来源：http://dali.zhiwuduotai.top/Article/details/gt2zsnxlklh.html

SAVEPOINT sp1;
来源：http://dali.zhiwuduotai.top/Article/details/gt2pxsmubws.html

ROLLBACK TO sp1;
来源：http://dali.zhixingplan.top/Article/details/gt2nejnnenm.html

[Q69] 查看执行计划
来源：http://dali.xziqi.cn/Article/details/gt2kwdbzfvp.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.daria6918.cn/Article/details/gt2mdeusrex.html

[Q70] 更新统计信息
来源：http://dali.shuidangran.top/Article/details/gt2qvnwkgjd.html

ANALYZE TABLE users;
来源：http://dali.havefunace.top/Article/details/gt2ngaxalna.html

[Q71] 查看建表语句
来源：http://dali.ehwqpu.com/Article/details/gt2gpmcxzjm.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.chenjidiqi.icu/Article/details/gt2pafzcqvy.html

[Q72] 查看索引
来源：http://dali.dianchejie.cn/Article/details/gt2ysjfhgmm.html

SHOW INDEX FROM users;
来源：http://dali.redwolf501.top/Article/details/gt2kfjfzfyl.html

[Q73] 查看表状态
来源：http://dali.ehwqpu.com/Article/details/gt2urgwxask.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.sweek.top/Article/details/gt2ygkmbins.html

[Q74] 强制使用索引
来源：http://dali.haohaochexian.top/Article/details/gt2yesummdo.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2evofxcky.html

[Q75] 日期格式化
来源：http://dali.havefunace.top/Article/details/gt2ehbczjxn.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.ybcxt.top/Article/details/gt2idiltwju.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhengqikj.top/Article/details/gt2jntkiket.html

[Q76] 按天统计
来源：http://dali.hnxiangtu.top/Article/details/gt2hoqtehhx.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.gzhubu.top/Article/details/gt2elowhurw.html

[Q77] 时间加减
来源：http://dali.xylfe.cn/Article/details/gt2gzbixxnr.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.ybcxt.top/Article/details/gt2rslhfpql.html

[Q78] 当前时间
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pwqcngmf.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.xuetiantiany.cn/Article/details/gt2rdzxfbkj.html

[Q79] 字符串拼接
来源：http://dali.0kj1m.cn/Article/details/gt2upwgphyk.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.iojbl.cn/Article/details/gt2ttnnlhpm.html

[Q80] 字符串截取
来源：http://dali.guannengcc.top/Article/details/gt2qoqmhyws.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.ppjwa.cn/Article/details/gt2msvzqacs.html

[Q81] 字符串替换
来源：http://dali.hywenlv.cn/Article/details/gt2ipkpvihi.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.sweek.top/Article/details/gt2fqrwbwlr.html

[Q82] 字符长度与字节长度
来源：http://dali.nanxuanxn.top/Article/details/gt2myzawxrz.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zdqjudy.top/Article/details/gt2iltolbgm.html

[Q83] 大小写转换
来源：http://dali.snrcjt.cn/Article/details/gt2merymsnq.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.snrcjt.cn/Article/details/gt2ktkzwudt.html

[Q84] 去除首尾空格
来源：http://dali.tian-w.cn/Article/details/gt2qqcicdax.html

SELECT TRIM(name) FROM users;
来源：http://dali.hammf.cn/Article/details/gt2qhozfwec.html

[Q85] 数值取整
来源：http://dali.guannengcc.top/Article/details/gt2mdeujtjp.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.meibo888.top/Article/details/gt2ufegyatu.html

[Q86] 读取 JSON 字段
来源：http://dali.0kj1m.cn/Article/details/gt2ichjyzbp.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.ppjwa.cn/Article/details/gt2webwtnfv.html

[Q87] JSON 字段做条件
来源：http://dali.iojbl.cn/Article/details/gt2ybtvgqgd.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.cucudq.cn/Article/details/gt2ssjhigzq.html

[Q88] 行转列（条件聚合）
来源：http://dali.chenjidiqi.icu/Article/details/gt2njvavsoa.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.gogol.net.cn/Article/details/gt2yhaghjgi.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.shuidangran.top/Article/details/gt2wdahykdz.html

[Q89] 判断表是否存在
来源：http://dali.fengsongda.top/Article/details/gt2hsjksbpx.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dempglyi.html

[Q90] 生成序号列
来源：http://dali.yj20258888.top/Article/details/gt2uzybcutn.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.jinqigfzy.top/Article/details/gt2mtswtmcd.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2bgrnlzsl.html

R. Bash 专题
来源：http://dali.jinqigfzy.top/Article/details/gt2pvockfxs.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2uxrhcstp.html

[R01] shebang 与严格模式
来源：http://dali.jianghu66.top/Article/details/gt2nozuakbx.html

#!/usr/bin/env bash
来源：http://dali.snrcjt.cn/Article/details/gt2dchxffxk.html

set -euo pipefail
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xmwkzklx.html

[R02] 变量赋值与使用
来源：http://dali.nwbrower.top/Article/details/gt2plmitbtr.html

name="Tom"; echo "$name"
来源：http://dali.cdnleiting.top/Article/details/gt2irvfsefs.html

[R03] 只读变量
来源：http://dali.vqdsnc.cn/Article/details/gt2zurjivul.html

readonly PI=3.14
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2esikhbss.html

[R04] 位置参数
来源：http://dali.quarkkingdee.top/Article/details/gt2fiiobwie.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.ybcxt.top/Article/details/gt2seexbdqk.html

[R05] 参数默认值
来源：http://dali.sweek.top/Article/details/gt2kdryaazw.html

name="${1:-default}"
来源：http://dali.guowangkeji.top/Article/details/gt2xiyxrusx.html

[R06] 判断命令是否存在
来源：http://dali.guannengcc.top/Article/details/gt2mguxlsjo.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.sufxvd.cn/Article/details/gt2jbgfcszc.html

[R07] if 判断文件
来源：http://dali.sweek.top/Article/details/gt2vlainrau.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.sxryk.cn/Article/details/gt2hbxvmxvf.html

[R08] 数值比较
来源：http://dali.jinqigufen.top/Article/details/gt2uimfdpyr.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.cdnleiting.top/Article/details/gt2fxgpbyws.html

[R09] 字符串比较
来源：http://dali.gzhubu.top/Article/details/gt2lzfmqmaz.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.gzhubu.top/Article/details/gt2paritbew.html

[R10] 正则匹配
来源：http://dali.andypj.xyz/Article/details/gt2fflnsfto.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.dianchejie.cn/Article/details/gt2qjhynozn.html

[R11] case 多分支
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mypxbxxr.html

case "$1" in
来源：http://dali.cdnleiting.top/Article/details/gt2qviqtcej.html

start) echo "启动" ;;
来源：http://dali.pengpengdd.cyou/Article/details/gt2ineuquzr.html

stop)  echo "停止" ;;
来源：http://dali.pycfn.com/Article/details/gt2hjzkarmq.html

*)     echo "未知命令" ;;
来源：http://dali.yueranfly.top/Article/details/gt2fcufynyb.html

esac
来源：http://dali.jinqigufen.top/Article/details/gt2lexmyyai.html

[R12] for 遍历文件
来源：http://dali.gotoacloud.top/Article/details/gt2xcpuicnf.html

for f in *.txt; do echo "$f"; done
来源：http://dali.chenjidiqi.icu/Article/details/gt2ayxqynrz.html

[R13] for 计数循环
来源：http://dali.shzxlz.cn/Article/details/gt2riekdzux.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.hnxiangtu.top/Article/details/gt2axbvhhkt.html

[R14] C 风格 for
来源：http://dali.gaohongyu789.top/Article/details/gt2eqouuore.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.ppjwa.cn/Article/details/gt2mbygneco.html

[R15] while 逐行读文件
来源：http://dali.0kj1m.cn/Article/details/gt2wepgsezt.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.bjfxy.top/Article/details/gt2dtjlqtop.html

[R16] until 等待条件
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2aeaqmrfm.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.gotoacloud.top/Article/details/gt2yxyxqstv.html

[R17] 数组定义与取值
来源：http://dali.sufxvd.cn/Article/details/gt2uylnhtau.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.cheryme.top/Article/details/gt2zozvkphj.html

[R18] 遍历数组
来源：http://dali.hysaishi.cn/Article/details/gt2nwlikjti.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.xinyue.icu/Article/details/gt2lzexiqna.html

[R19] 数组长度
来源：http://dali.hfpthk.cn/Article/details/gt2geafsmti.html

echo "${#arr[@]}"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yqelokcd.html

[R20] 关联数组（字典）
来源：http://dali.nanxinkj.top/Article/details/gt2flgfjpkf.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.ppjwa.cn/Article/details/gt2acilndur.html

[R21] 字符串长度
来源：http://dali.gaohongyu789.top/Article/details/gt2sufoylqt.html

echo "${#s}"
来源：http://dali.cdnleiting.top/Article/details/gt2kwvcnhtv.html

[R22] 截取子串
来源：http://dali.nanxinkj.top/Article/details/gt2ysnfubme.html

echo "${s:0:5}"
来源：http://dali.yvedp.cn/Article/details/gt2vmtjqhgk.html

[R23] 字符串替换
来源：http://dali.gogol.net.cn/Article/details/gt2iislxuac.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.gotoacloud.top/Article/details/gt2ucvhgjji.html

[R24] 大小写转换
来源：http://dali.shangyingyoupin.top/Article/details/gt2bmwgilzl.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.chenlongwang.top/Article/details/gt2jaqokjqv.html

[R25] 去后缀 / 去前缀
来源：http://dali.jinqigufen.top/Article/details/gt2ycenqkxd.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.0kj1m.cn/Article/details/gt2nulnpgze.html

[R26] 命令替换
来源：http://dali.andypj.xyz/Article/details/gt2rxkpbosm.html

now=$(date +%F); echo "$now"
来源：http://dali.cqqwz.cn/Article/details/gt2tcgjlrzc.html

[R27] 算术展开
来源：http://dali.zhongyouzk.top/Article/details/gt2fnnhehed.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2nwflkwmp.html

[R28] 浮点运算
来源：http://dali.fengsongda.top/Article/details/gt2yijfvfvh.html

echo "scale=2; 10/3" | bc
来源：http://dali.jiagoushi.top/Article/details/gt2fxrtklth.html

[R29] 定义函数
来源：http://dali.sxryk.cn/Article/details/gt2yhvvvdzk.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.jlsjyb.cn/Article/details/gt2cosceiyv.html

[R30] 函数返回状态码
来源：http://dali.gotoacloud.top/Article/details/gt2bzjjdlqp.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.guowangkeji.top/Article/details/gt2oejmrriz.html

[R31] 局部变量
来源：http://dali.xuetiantiany.cn/Article/details/gt2ksammdwq.html

f() { local x=1; echo "$x"; }
来源：http://dali.nanxuanxn.top/Article/details/gt2virqceqv.html

[R32] 参数个数校验
来源：http://dali.sufxvd.cn/Article/details/gt2oahocbdl.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.xuanzx.com/Article/details/gt2dlsuchuk.html

[R33] 捕获错误并提示行号
来源：http://dali.redwolf501.top/Article/details/gt2eqnkpkei.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.nwbrower.top/Article/details/gt2gkepmjki.html

[R34] 退出时清理
来源：http://dali.jyoumei.cn/Article/details/gt2rrgltipp.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.gzhubu.top/Article/details/gt2mvcrsnin.html

[R35] 后台执行并等待
来源：http://dali.yuxming.cn/Article/details/gt2xqdmitxx.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhongyouzk.top/Article/details/gt2zjlznbdu.html

[R36] 并发执行多个任务
来源：http://dali.feifeiyinyue.top/Article/details/gt2nmwiegnu.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.birdmap.top/Article/details/gt2artnbgcl.html

[R37] 把输出赋给变量
来源：http://dali.cdnleiting.top/Article/details/gt2teubtikn.html

files=$(ls -1)
来源：http://dali.cucudq.cn/Article/details/gt2bmjbnggl.html

[R38] 管道串联
来源：http://dali.0kj1m.cn/Article/details/gt2aixgpshn.html

cat a.txt | grep -i error | wc -l
来源：http://dali.nanxinkj.top/Article/details/gt2ytgfnmvr.html

[R39] 重定向标准输出与错误
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wysovuvc.html

cmd > out.log 2>&1
来源：http://dali.tian-w.cn/Article/details/gt2sawxbwfw.html

[R40] 追加写日志
来源：http://dali.yuxming.cn/Article/details/gt2aovrehat.html

echo "log" >> out.log
来源：http://dali.havefunace.top/Article/details/gt2sxridqbe.html

[R41] 丢弃输出
来源：http://dali.shangyingyoupin.top/Article/details/gt2lizuuuna.html

cmd >/dev/null 2>&1
来源：http://dali.bjfxy.top/Article/details/gt2rpnpjicm.html

[R42] 输入重定向
来源：http://dali.zhixingplan.top/Article/details/gt2kgarmkis.html

wc -l < a.txt
来源：http://dali.sxryk.cn/Article/details/gt2xdyghgrq.html

[R43] 按名字查找文件
来源：http://dali.jlsjyb.cn/Article/details/gt2xqasdjor.html

find . -name "*.log" -type f
来源：http://dali.aizwys.cn/Article/details/gt2jcmsgbfg.html

[R44] 按修改时间查找
来源：http://dali.redwolf501.top/Article/details/gt2bdralhgp.html

find . -mtime -7 -type f
来源：http://dali.chenzaomai.com/Article/details/gt2qekypdkw.html

[R45] 批量删除
来源：http://dali.vqdsnc.cn/Article/details/gt2lcnwgwon.html

find . -name "*.tmp" -delete
来源：http://dali.tian-w.cn/Article/details/gt2upxmipjj.html

[R46] 递归替换文件内容
来源：http://dali.ppjwa.cn/Article/details/gt2pjuuwjki.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.chenjidiqi.icu/Article/details/gt2uyjkqhyr.html

[R47] sed 单行替换
来源：http://dali.ehwqpu.com/Article/details/gt2lmitceho.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.cdnleiting.top/Article/details/gt2jxbwojsn.html

[R48] awk 取指定列
来源：http://dali.iojbl.cn/Article/details/gt2elvdxqel.html

awk '{print $1, $3}' a.txt
来源：http://dali.nanxinkj.top/Article/details/gt2saohhhlv.html

[R49] awk 带条件
来源：http://dali.hywenlv.cn/Article/details/gt2toawjirn.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.ivvv.top/Article/details/gt2glqwmbgz.html

[R50] awk 求和
来源：http://dali.xuetiantiany.cn/Article/details/gt2qtaxodef.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.yuanzhike.top/Article/details/gt2ncadpvnj.html

[R51] 排序去重取前几
来源：http://dali.bjfxy.top/Article/details/gt2nlgspqbp.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.yonumen.top/Article/details/gt2jbgirgeu.html

[R52] 统计行数
来源：http://dali.sysykeji.top/Article/details/gt2jmashxwb.html

wc -l a.txt
来源：http://dali.sufxvd.cn/Article/details/gt2rqpliwmb.html

[R53] 查看文件头与实时尾
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fwkkbfbe.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.chenlongwang.top/Article/details/gt2ldqjmbru.html

[R54] 比较两个文件
来源：http://dali.sweek.top/Article/details/gt2gpcwozam.html

diff a.txt b.txt
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2miubdthf.html

[R55] 压缩与解压
来源：http://dali.tianlin.xyz/Article/details/gt2svoxiuvt.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhoulong.xyz/Article/details/gt2buwwfrvo.html

[R56] 远程拷贝
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pbmysedv.html

scp file user@host:/path/
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qvrpekjq.html

[R57] 远程执行命令
来源：http://dali.xuanzx.com/Article/details/gt2rbfnlwxa.html

ssh user@host 'uptime'
来源：http://dali.shzxlz.cn/Article/details/gt2vlixjglf.html

[R58] 下载文件
来源：http://dali.hysaishi.cn/Article/details/gt2mblrxuci.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.smart0.xyz/Article/details/gt2fahrrcbv.html

[R59] 发 POST JSON
来源：http://dali.hongshengwenyu.top/Article/details/gt2sfiocwwu.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.hysaishi.cn/Article/details/gt2ovljlatq.html

[R60] 只看 HTTP 状态码
来源：http://dali.haohaochexian.top/Article/details/gt2yubmuerg.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.svipenyu.cn/Article/details/gt2kkmfsdgf.html

[R61] 磁盘占用
来源：http://dali.yj20258888.top/Article/details/gt2qpxshnyi.html

df -h;  du -sh *
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wgchxvzz.html

[R62] 找最占空间的文件
来源：http://dali.mhx1999.top/Article/details/gt2vgzeerpq.html

du -ah . | sort -rh | head -10
来源：http://dali.redwolf501.top/Article/details/gt2xxndlbkd.html

[R63] 内存与进程
来源：http://dali.guowangkeji.top/Article/details/gt2qbsvmrfv.html

free -h;  ps aux | grep nginx
来源：http://dali.hysaishi.cn/Article/details/gt2djohvmcq.html

[R64] 结束进程
来源：http://dali.hongshengwenyu.top/Article/details/gt2eqsrgodg.html

kill -9 $(pgrep -f app.py)
来源：http://dali.316326.xyz/Article/details/gt2wxzczvyh.html

[R65] 查看端口占用
来源：http://dali.9152youxi.cn/Article/details/gt2owdqdcnt.html


<!-- 参考信息 -->