代发 wailian999

[Q14] 存在则更新（upsert）
来源：http://dali.aibaodan.cn/Article/details/gthqsdhbbf.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhoulong.xyz/Article/details/gtqaekumbs.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjdssoazr.html

[Q15] 查询全部
来源：http://dali.hfpthk.cn/Article/details/gtiyhnmjap.html

SELECT * FROM users;
来源：http://dali.nwbrower.top/Article/details/gtdujsobto.html

[Q16] 查询指定列
来源：http://dali.yj20258.top/Article/details/gtibnlqiic.html

SELECT id, name FROM users;
来源：http://dali.ehwqpu.com/Article/details/gtzsjpqvzd.html

[Q17] 条件查询
来源：http://dali.yueranfly.top/Article/details/gtqrjfivaf.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhengqikj.top/Article/details/gtbvafmbkh.html

[Q18] 模糊匹配
来源：http://dali.ppjwa.cn/Article/details/gtvhmoozkf.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.cqqwz.cn/Article/details/gtplenfziu.html

[Q19] 范围查询
来源：http://dali.zdqjudy.top/Article/details/gtrhghbsdb.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.hnqzz.top/Article/details/gtamabdcuz.html

[Q20] IN 列表
来源：http://dali.xuanzx.com/Article/details/gtgkxkifdq.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.vqdsnc.cn/Article/details/gtjlezypxc.html

[Q21] 空值判断
来源：http://dali.nwbrower.top/Article/details/gtzxgvbxri.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.yuanzhike.top/Article/details/gttviueodj.html

[Q22] 排序
来源：http://dali.cashguo.top/Article/details/gtbmswczih.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhiwuduotai.top/Article/details/gtuxyksprv.html

[Q23] 分页
来源：http://dali.mhx1999.top/Article/details/gtpnyfoeea.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.chenlongwang.top/Article/details/gtvdylpyib.html

[Q24] 去重
来源：http://dali.jinghuilouyu.cn/Article/details/gtupmxhxpq.html

SELECT DISTINCT city FROM users;
来源：http://dali.jqgfzy.top/Article/details/gtbxcclbcn.html

[Q25] 只取前 N 条
来源：http://dali.haohaochexian.top/Article/details/gtabxxsdbd.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.jqgufenzy.top/Article/details/gtbrgyokpm.html

[Q26] 计数
来源：http://dali.hysaishi.cn/Article/details/gtmlvkrnvr.html

SELECT COUNT(*) FROM users;
来源：http://dali.xziqi.cn/Article/details/gtybqwhxzd.html

[Q27] 条件计数
来源：http://dali.guannengcc.top/Article/details/gteqxsfoqc.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.sysykeji.top/Article/details/gtgiqkhmtz.html

[Q28] 求和与平均
来源：http://dali.jinghuilouyu.cn/Article/details/gtvdaafyka.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhiwuduotai.top/Article/details/gtukxqrnye.html

[Q29] 最大最小值
来源：http://dali.sxryk.cn/Article/details/gtwprxsqlw.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.daria6918.cn/Article/details/gtzchrfoos.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gtlptotrxu.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.hfpthk.cn/Article/details/gtbmjbvgli.html

[Q31] 分组后过滤
来源：http://dali.zdqjudy.top/Article/details/gtdrudidtj.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.tanke756.top/Article/details/gtqjzayrqa.html

[Q32] 分组拼接字符串
来源：http://dali.guowangkeji.top/Article/details/gtvegbjvjo.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.pengpengdd.cyou/Article/details/gtwfctjzhb.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.pycfn.com/Article/details/gtkzrgahsa.html

[Q33] 多列分组
来源：http://dali.bjfxy.top/Article/details/gtryddiaao.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.shuidangran.top/Article/details/gtpskvzdmi.html

[Q34] 每组取第一条
来源：http://dali.sufxvd.cn/Article/details/gtutptwcsh.html

SELECT * FROM (
来源：http://dali.ehwqpu.com/Article/details/gtftpkvjhy.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuxtrqfyd.html

) t WHERE rn = 1;
来源：http://dali.jlsjyb.cn/Article/details/gtjdnruozs.html

[Q35] 内连接
来源：http://dali.nwbrower.top/Article/details/gtzmqltrub.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.kuanghao11.cn/Article/details/gtkhfbbhpm.html

[Q36] 左连接
来源：http://dali.yonumen.top/Article/details/gtdaohatot.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.nanxinkj.top/Article/details/gtrfxmtulm.html

[Q37] 右连接
来源：http://dali.hnqzz.top/Article/details/gtlzqdcswy.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.jinghuilouyu.cn/Article/details/gtwommjpqm.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.gzhubu.top/Article/details/gteyjqpkgf.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.ybcxt.top/Article/details/gtjzortttm.html

[Q39] 自连接（查上下级）
来源：http://dali.iojbl.cn/Article/details/gtzshvflfk.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhixingplan.top/Article/details/gtaclpyaqt.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.chenlongwang.top/Article/details/gtepchcqry.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.jiagoushi.top/Article/details/gtwiyapnxl.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.yongpay.top/Article/details/gtustskxeg.html

[Q41] 多表连接
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzthnbjvy.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.gaohongyu789.top/Article/details/gtccoeixet.html

JOIN users u ON u.id = o.user_id
来源：http://dali.9152youxi.cn/Article/details/gtprkyoqcp.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.daria6918.cn/Article/details/gtzcenfurq.html

[Q42] 连接条件附加过滤
来源：http://dali.ivvv.top/Article/details/gtunsgmyvb.html

SELECT u.name, o.amount FROM users u
来源：http://dali.yuxming.cn/Article/details/gtyxjmsdnk.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlkympsrk.html

[Q43] 标量子查询
来源：http://dali.aizwys.cn/Article/details/gtccnbzrwx.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.yj20258888.top/Article/details/gtsgvlsptr.html

[Q44] IN 子查询
来源：http://dali.yuxming.cn/Article/details/gtzbfkfmja.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.guowangkeji.top/Article/details/gtzfkieqcm.html

[Q45] EXISTS 判断存在
来源：http://dali.vqdsnc.cn/Article/details/gtdvfkotgc.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.birdmap.top/Article/details/gtztcghjmc.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.meibo888.top/Article/details/gtsasavyrd.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.nwbrower.top/Article/details/gtsgrbhwov.html

[Q47] 与平均值比较
来源：http://dali.shuidangran.top/Article/details/gtakndhqqx.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.meibo888.top/Article/details/gtviipwnxv.html

[Q48] CTE 公用表表达式
来源：http://dali.hnxiangtu.top/Article/details/gtusljwtbv.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.hnqzz.top/Article/details/gtrylzpful.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.birdmap.top/Article/details/gtheblcwpv.html

[Q49] 更新单行
来源：http://dali.redwolf501.top/Article/details/gtxwwmvkhd.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.xylfe.cn/Article/details/gtbnohxqxz.html

[Q50] 批量更新
来源：http://dali.wangdashe.top/Article/details/gtacxasdpt.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.fzhhl.top/Article/details/gtbjcahqzz.html

[Q51] 用子查询更新
来源：http://dali.bjfxy.top/Article/details/gtlhcbfrbj.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.aizwys.cn/Article/details/gtbigsoadj.html

[Q52] 删除指定行
来源：http://dali.fzhhl.top/Article/details/gtjdcgvhso.html

DELETE FROM users WHERE id = 10;
来源：http://dali.cashguo.top/Article/details/gteskejryp.html

[Q53] 按条件删除
来源：http://dali.hnqzz.top/Article/details/gtzmphegip.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.vqdsnc.cn/Article/details/gtbwqhrwww.html

[Q54] 清空表
来源：http://dali.yj20258.top/Article/details/gtuwyaidct.html

TRUNCATE TABLE logs;
来源：http://dali.xylfe.cn/Article/details/gtpgiyfugu.html

[Q55] 排名（并列占位）
来源：http://dali.wangshuangyany.cn/Article/details/gtupqyxahz.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.chenjidiqi.icu/Article/details/gtldyefitd.html

[Q56] 密集排名（并列不占位）
来源：http://dali.yuxming.cn/Article/details/gtzoqfaznb.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.chenzaomai.com/Article/details/gtqqycsdwq.html

[Q57] 行号
来源：http://dali.zhongyouzk.top/Article/details/gtfffxgzhh.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.daria6918.cn/Article/details/gtgstktoys.html

[Q58] 累计求和
来源：http://dali.andypj.xyz/Article/details/gtgfbkfoxy.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.yuanzhike.top/Article/details/gtkgsvdrhi.html

[Q59] 分组内累计
来源：http://dali.hnqzz.top/Article/details/gtytciaheg.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.snrcjt.cn/Article/details/gtghfehnba.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhixingplan.top/Article/details/gtkqkpbdjq.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.ydzc1.top/Article/details/gtlvxajlia.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.nanxinkj.top/Article/details/gtwzefizfa.html

[Q61] 移动平均
来源：http://dali.jyoumei.cn/Article/details/gtnorggmxh.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.meibo888.top/Article/details/gtmfptlntm.html

[Q62] 分组占比
来源：http://dali.gotoacloud.top/Article/details/gtgecnedom.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.yj20258.top/Article/details/gthfjpfnlv.html

[Q63] 开启事务
来源：http://dali.aizwys.cn/Article/details/gtkkdvgsgq.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.andypj.xyz/Article/details/gtvrqxmjax.html

[Q64] 提交事务
来源：http://dali.gotoacloud.top/Article/details/gtomghwwov.html

COMMIT;
来源：http://dali.xziqi.cn/Article/details/gtfxooqwxj.html

[Q65] 回滚事务
来源：http://dali.chenjidiqi.icu/Article/details/gtcesgursu.html

ROLLBACK;
来源：http://dali.jqgufenzy.top/Article/details/gtnnrhfcob.html

[Q66] 行锁查询
来源：http://dali.hywenlv.cn/Article/details/gtxdysacpg.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.nanxuanxn.top/Article/details/gtifrmwguo.html

[Q67] 设置隔离级别
来源：http://dali.shanyushiyangtech.top/Article/details/gtjtxghfad.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.yongpay.top/Article/details/gtylpfgslm.html

[Q68] 保存点
来源：http://dali.tian-w.cn/Article/details/gtoljchdrl.html

SAVEPOINT sp1;
来源：http://dali.jqgufenzy.top/Article/details/gtxstkcxhp.html

ROLLBACK TO sp1;
来源：http://dali.cashguo.top/Article/details/gtifesdvja.html

[Q69] 查看执行计划
来源：http://dali.andypj.xyz/Article/details/gtdxaulpwa.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.jiagoushi.top/Article/details/gtgahfwyth.html

[Q70] 更新统计信息
来源：http://dali.quarkkingdee.top/Article/details/gtobnbkfez.html

ANALYZE TABLE users;
来源：http://dali.jiagoushi.top/Article/details/gtpgtqxaob.html

[Q71] 查看建表语句
来源：http://dali.fzhhl.top/Article/details/gtwideshdb.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.dashuyun.cn/Article/details/gtnyaxralg.html

[Q72] 查看索引
来源：http://dali.yongpay.top/Article/details/gtsvjiwwqg.html

SHOW INDEX FROM users;
来源：http://dali.mhx1999.top/Article/details/gtrtwsuzpx.html

[Q73] 查看表状态
来源：http://dali.sysykeji.top/Article/details/gtwlrjyahj.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhixingplan.top/Article/details/gtgbkzbler.html

[Q74] 强制使用索引
来源：http://dali.feifeiyinyue.top/Article/details/gtxbrzbrgb.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.cashguo.top/Article/details/gtnwmrzdxc.html

[Q75] 日期格式化
来源：http://dali.cashguo.top/Article/details/gtvvpdkxrq.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.nwbrower.top/Article/details/gtmizwepzb.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.c1oappe.top/Article/details/gtbajsqqhr.html

[Q76] 按天统计
来源：http://dali.smart0.xyz/Article/details/gtqhblycya.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.yj20258888.top/Article/details/gtdyutthfc.html

[Q77] 时间加减
来源：http://dali.bjfxy.top/Article/details/gtyfotkmsh.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.tianlin.xyz/Article/details/gtelaxyufs.html

[Q78] 当前时间
来源：http://dali.iojbl.cn/Article/details/gtwzlzkktr.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.daxiang520.top/Article/details/gtpegrcddy.html

[Q79] 字符串拼接
来源：http://dali.tanke756.top/Article/details/gtwktjrirr.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.haohaochexian.top/Article/details/gthawwkfkd.html

[Q80] 字符串截取
来源：http://dali.feifeiyinyue.top/Article/details/gtebodylxu.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.guannengcc.top/Article/details/gthjoxmlgu.html

[Q81] 字符串替换
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzijuzijh.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjvrdwqlz.html

[Q82] 字符长度与字节长度
来源：http://dali.svipenyu.cn/Article/details/gtmfhezfjl.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.birdmap.top/Article/details/gtuhudexcv.html

[Q83] 大小写转换
来源：http://dali.hnxiangtu.top/Article/details/gttfbscqeq.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.aibaodan.cn/Article/details/gtyodlymbx.html

[Q84] 去除首尾空格
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxjmjsgih.html

SELECT TRIM(name) FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gtyuinuspk.html

[Q85] 数值取整
来源：http://dali.yvedp.cn/Article/details/gtaqiwccrp.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.ivvv.top/Article/details/gtqriqwlyz.html

[Q86] 读取 JSON 字段
来源：http://dali.c1oappe.top/Article/details/gtyedozbbh.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlyznaafp.html

[Q87] JSON 字段做条件
来源：http://dali.mhx1999.top/Article/details/gtawrhyzcp.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.tian-w.cn/Article/details/gtmwsclvtc.html

[Q88] 行转列（条件聚合）
来源：http://dali.hywenlv.cn/Article/details/gttanoxbll.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.xinyue.icu/Article/details/gtdjgfnbmh.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.yangfankeji.com/Article/details/gtdkodlxtj.html

[Q89] 判断表是否存在
来源：http://dali.zhiwuduotai.top/Article/details/gtwjvchsxw.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.ywan-chungtsiang.top/Article/details/gthvjoatgs.html

[Q90] 生成序号列
来源：http://dali.sweek.top/Article/details/gtbnnxjjpy.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.dashuyun.cn/Article/details/gtjfesvqcl.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtbxzwfeuq.html

R. Bash 专题
来源：http://dali.jinqigfzy.top/Article/details/gtxiegkmug.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gthpwhrpmw.html

[R01] shebang 与严格模式
来源：http://dali.dianchejie.cn/Article/details/gtuxhtwtcg.html

#!/usr/bin/env bash
来源：http://dali.shangyingyoupin.top/Article/details/gtzpjixdvy.html

set -euo pipefail
来源：http://dali.ppjwa.cn/Article/details/gtuhndpmly.html

[R02] 变量赋值与使用
来源：http://dali.xuetiantiany.cn/Article/details/gtsksdbvnn.html

name="Tom"; echo "$name"
来源：http://dali.feifeiyinyue.top/Article/details/gtegvaueiw.html

[R03] 只读变量
来源：http://dali.xylfe.cn/Article/details/gtlyavfevp.html

readonly PI=3.14
来源：http://dali.quarkkingdee.top/Article/details/gtttdagtjf.html

[R04] 位置参数
来源：http://dali.ppjwa.cn/Article/details/gtubegiuez.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhengqikj.top/Article/details/gtsmvfseqw.html

[R05] 参数默认值
来源：http://dali.ydzc1.top/Article/details/gttdnsfcgx.html

name="${1:-default}"
来源：http://dali.meibo888.top/Article/details/gtieaclzhj.html

[R06] 判断命令是否存在
来源：http://dali.zhengqikj.top/Article/details/gtyrrdrqav.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.jqgfzy.top/Article/details/gtogrsyrin.html

[R07] if 判断文件
来源：http://dali.gotoacloud.top/Article/details/gtehmrgdbr.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.daria6918.cn/Article/details/gtpogavijc.html

[R08] 数值比较
来源：http://dali.0kj1m.cn/Article/details/gtsppyezcz.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.gogol.net.cn/Article/details/gtejbgcdxb.html

[R09] 字符串比较
来源：http://dali.sweek.top/Article/details/gtpcdfxmpu.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.xziqi.cn/Article/details/gtxyrdpyap.html

[R10] 正则匹配
来源：http://dali.hywenlv.cn/Article/details/gtgbqbzkeh.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.xylfe.cn/Article/details/gtrhuwcxvy.html

[R11] case 多分支
来源：http://dali.yvedp.cn/Article/details/gtwhsdfqtz.html

case "$1" in
来源：http://dali.0kj1m.cn/Article/details/gtumpnqfne.html

start) echo "启动" ;;
来源：http://dali.zhongyouzk.top/Article/details/gthydjjrrx.html

stop)  echo "停止" ;;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtblgqvrjb.html

*)     echo "未知命令" ;;
来源：http://dali.tanke756.top/Article/details/gtlxtjnpmw.html

esac
来源：http://dali.andypj.xyz/Article/details/gtyfvernak.html

[R12] for 遍历文件
来源：http://dali.guannengcc.top/Article/details/gtruuwbjgc.html

for f in *.txt; do echo "$f"; done
来源：http://dali.redwolf501.top/Article/details/gtewpqntyl.html

[R13] for 计数循环
来源：http://dali.jinghuilouyu.cn/Article/details/gtxgdmoqjl.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.jyoumei.cn/Article/details/gtmylhlmlq.html

[R14] C 风格 for
来源：http://dali.daria6918.cn/Article/details/gtdqylnkrd.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.0kj1m.cn/Article/details/gtkrsbeoxz.html

[R15] while 逐行读文件
来源：http://dali.0kj1m.cn/Article/details/gtpwvsssnl.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.xuetiantiany.cn/Article/details/gtmwlbpkzw.html

[R16] until 等待条件
来源：http://dali.zhengqikj.top/Article/details/gtnvxgpsdt.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.havefunace.top/Article/details/gtylnxiyzj.html

[R17] 数组定义与取值
来源：http://dali.ivvv.top/Article/details/gtnnuyaawa.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.wangshuangyany.cn/Article/details/gtlyholvft.html

[R18] 遍历数组
来源：http://dali.aibaodan.cn/Article/details/gtcuddvcux.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.shangyingyoupin.top/Article/details/gtrfflfqck.html

[R19] 数组长度
来源：http://dali.jlsjyb.cn/Article/details/gtdcaxmyor.html

echo "${#arr[@]}"
来源：http://dali.xziqi.cn/Article/details/gtpbprosna.html

[R20] 关联数组（字典）
来源：http://dali.dashuyun.cn/Article/details/gtdyhmvltm.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhoulong.xyz/Article/details/gtdfhmknrp.html

[R21] 字符串长度
来源：http://dali.pycfn.com/Article/details/gtaqhrueho.html

echo "${#s}"
来源：http://dali.jianghu66.top/Article/details/gtaobbsotd.html

[R22] 截取子串
来源：http://dali.hfpthk.cn/Article/details/gtftdwcswu.html

echo "${s:0:5}"
来源：http://dali.cheryme.top/Article/details/gtmrirawar.html

[R23] 字符串替换
来源：http://dali.ehwqpu.com/Article/details/gtxncmzfno.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.hongshengwenyu.top/Article/details/gtgjvkiwqj.html

[R24] 大小写转换
来源：http://dali.quarkkingdee.top/Article/details/gtvqemnjom.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.c1oappe.top/Article/details/gtkbasapor.html

[R25] 去后缀 / 去前缀
来源：http://dali.yueranfly.top/Article/details/gtmeljispu.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.yuxming.cn/Article/details/gtlmrdvcxw.html

[R26] 命令替换
来源：http://dali.zycfv.cn/Article/details/gtijpmikvy.html

now=$(date +%F); echo "$now"
来源：http://dali.nwbrower.top/Article/details/gttxcwrkyf.html

[R27] 算术展开
来源：http://dali.cashguo.top/Article/details/gtmreszanp.html

echo $((1 + 2 * 3))
来源：http://dali.xinyue.icu/Article/details/gtatiqiynz.html

[R28] 浮点运算
来源：http://dali.zhiwuduotai.top/Article/details/gtnciucmwj.html

echo "scale=2; 10/3" | bc
来源：http://dali.gaohongyu789.top/Article/details/gtrolbbatc.html

[R29] 定义函数
来源：http://dali.tanke756.top/Article/details/gtmegnibqv.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.shangyingyoupin.top/Article/details/gtnqmceegc.html

[R30] 函数返回状态码
来源：http://dali.vqdsnc.cn/Article/details/gtqysszdnx.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.jlsjyb.cn/Article/details/gtlswyszmh.html

[R31] 局部变量
来源：http://dali.hnqzz.top/Article/details/gtuqzcngdj.html

f() { local x=1; echo "$x"; }
来源：http://dali.nanxinkj.top/Article/details/gtnxetatqi.html

[R32] 参数个数校验
来源：http://dali.jiagoushi.top/Article/details/gtsvaovuko.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.shuidangran.top/Article/details/gtdadnqxwx.html

[R33] 捕获错误并提示行号
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbfvlpkht.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.gzhubu.top/Article/details/gtjanglbgu.html

[R34] 退出时清理
来源：http://dali.316326.xyz/Article/details/gtfcfbagky.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.meibo888.top/Article/details/gtadzfbptz.html

[R35] 后台执行并等待
来源：http://dali.hfpthk.cn/Article/details/gtpqguuodg.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.nwbrower.top/Article/details/gttuvwsdze.html

[R36] 并发执行多个任务
来源：http://dali.nwbrower.top/Article/details/gtnalptfou.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zdqjudy.top/Article/details/gtmlcldmrz.html

[R37] 把输出赋给变量
来源：http://dali.jinqigfzy.top/Article/details/gteynrasff.html

files=$(ls -1)
来源：http://dali.zhixingplan.top/Article/details/gtfeeckuel.html

[R38] 管道串联
来源：http://dali.jianghu66.top/Article/details/gtipovgrnz.html

cat a.txt | grep -i error | wc -l
来源：http://dali.gogol.net.cn/Article/details/gtdbndizzv.html

[R39] 重定向标准输出与错误
来源：http://dali.gaohongyu789.top/Article/details/gtszrkcfqj.html

cmd > out.log 2>&1
来源：http://dali.chenlongwang.top/Article/details/gtklouissl.html

[R40] 追加写日志
来源：http://dali.fengsongda.top/Article/details/gtcdgoelmv.html

echo "log" >> out.log
来源：http://dali.redwolf501.top/Article/details/gtulrjajvx.html

[R41] 丢弃输出
来源：http://dali.316326.xyz/Article/details/gtfyrunbue.html

cmd >/dev/null 2>&1
来源：http://dali.sxryk.cn/Article/details/gtrjhwevmd.html

[R42] 输入重定向
来源：http://dali.316326.xyz/Article/details/gtpnetfxvn.html

wc -l < a.txt
来源：http://dali.iojbl.cn/Article/details/gtvycbhdpt.html

[R43] 按名字查找文件
来源：http://dali.chenjidiqi.icu/Article/details/gtkzvsvzfr.html

find . -name "*.log" -type f
来源：http://dali.jianghu66.top/Article/details/gtanljtalj.html

[R44] 按修改时间查找
来源：http://dali.dashuyun.cn/Article/details/gtronyqpxc.html

find . -mtime -7 -type f
来源：http://dali.yj20258.top/Article/details/gtilyehlvs.html

[R45] 批量删除
来源：http://dali.cqqwz.cn/Article/details/gtvpxfwjqe.html

find . -name "*.tmp" -delete
来源：http://dali.zhengqikj.top/Article/details/gtywsygpda.html

[R46] 递归替换文件内容
来源：http://dali.shzxlz.cn/Article/details/gtxdsrazxv.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zdqjudy.top/Article/details/gtfawmsonn.html

[R47] sed 单行替换
来源：http://dali.cqqwz.cn/Article/details/gtzcydlsxl.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgrqvjfzr.html

[R48] awk 取指定列
来源：http://dali.svipenyu.cn/Article/details/gtohgymvrw.html

awk '{print $1, $3}' a.txt
来源：http://dali.yanxiufei.cn/Article/details/gtvxxfmxto.html

[R49] awk 带条件
来源：http://dali.daxiang520.top/Article/details/gtxnkcbomf.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.yj20258888.top/Article/details/gtlxfvavyc.html

[R50] awk 求和
来源：http://dali.zhongyouzk.top/Article/details/gtgwkpkpcj.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.jinqigufen.top/Article/details/gthtwfzhlo.html

[R51] 排序去重取前几
来源：http://dali.tian-w.cn/Article/details/gtofovzday.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.mhx1999.top/Article/details/gtdbwjhair.html

[R52] 统计行数
来源：http://dali.jinqigfzy.top/Article/details/gtsitfeqio.html

wc -l a.txt
来源：http://dali.yangfankeji.com/Article/details/gtwlzuarif.html

[R53] 查看文件头与实时尾
来源：http://dali.jianghu66.top/Article/details/gtkwfxwvyt.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.kuanghao11.cn/Article/details/gtoxqlhsvp.html

[R54] 比较两个文件
来源：http://dali.yanxiufei.cn/Article/details/gtejinouqy.html

diff a.txt b.txt
来源：http://dali.yuanzhike.top/Article/details/gtfkncxcfo.html

[R55] 压缩与解压
来源：http://dali.316326.xyz/Article/details/gtodsfinfl.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.ivvv.top/Article/details/gtjlrccujt.html

[R56] 远程拷贝
来源：http://dali.xuetiantiany.cn/Article/details/gtzuapmuzm.html

scp file user@host:/path/
来源：http://dali.nwbrower.top/Article/details/gthnctbbcp.html

[R57] 远程执行命令
来源：http://dali.hongshengwenyu.top/Article/details/gtbjdjhcuh.html

ssh user@host 'uptime'
来源：http://dali.nwbrower.top/Article/details/gtguvumltc.html

[R58] 下载文件
来源：http://dali.cdnleiting.top/Article/details/gtecjrpwfy.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zycfv.cn/Article/details/gtnangseyr.html

[R59] 发 POST JSON
来源：http://dali.0kj1m.cn/Article/details/gtlbzublqn.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.svipenyu.cn/Article/details/gtqurvfgid.html

[R60] 只看 HTTP 状态码
来源：http://dali.haohaochexian.top/Article/details/gtogdrqspr.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.hysaishi.cn/Article/details/gtwpmtxpdy.html

[R61] 磁盘占用
来源：http://dali.birdmap.top/Article/details/gtagoajzkk.html

df -h;  du -sh *
来源：http://dali.feifeiyinyue.top/Article/details/gtwsoddvup.html

[R62] 找最占空间的文件
来源：http://dali.guowangkeji.top/Article/details/gtjwvcqrvu.html

du -ah . | sort -rh | head -10
来源：http://dali.jlsjyb.cn/Article/details/gtqpcxwpcy.html

[R63] 内存与进程
来源：http://dali.dashuyun.cn/Article/details/gtgoycobxd.html


<!-- 参考信息 -->