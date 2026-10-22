代发 wailian999

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.tianlin.xyz/Article/details/gtegewbpvr.html

[Q18] 模糊匹配
来源：http://dali.yanxiufei.cn/Article/details/gtdhuzqcto.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.nwbrower.top/Article/details/gtqiclmpag.html

[Q19] 范围查询
来源：http://dali.dianchejie.cn/Article/details/gteelxcjaw.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.dashuyun.cn/Article/details/gthxnaaohb.html

[Q20] IN 列表
来源：http://dali.daxiang520.top/Article/details/gtpkkwpavg.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.9152youxi.cn/Article/details/gttdcqszvf.html

[Q21] 空值判断
来源：http://dali.yj20258888.top/Article/details/gtpimikqkl.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zdqjudy.top/Article/details/gtjclxpznl.html

[Q22] 排序
来源：http://dali.zhoulong.xyz/Article/details/gtybclqkvf.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.jqgufenzy.top/Article/details/gtvumbqbdx.html

[Q23] 分页
来源：http://dali.birdmap.top/Article/details/gtwefkmrwx.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.yuanzhike.top/Article/details/gtlusqonhr.html

[Q24] 去重
来源：http://dali.jqgfzy.top/Article/details/gtponjkgdf.html

SELECT DISTINCT city FROM users;
来源：http://dali.iojbl.cn/Article/details/gtippjnpyi.html

[Q25] 只取前 N 条
来源：http://dali.snrcjt.cn/Article/details/gtuuwaxcmq.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.sweek.top/Article/details/gtiyedpiis.html

[Q26] 计数
来源：http://dali.vqdsnc.cn/Article/details/gtppsonjuj.html

SELECT COUNT(*) FROM users;
来源：http://dali.aibaodan.cn/Article/details/gtjwofbykq.html

[Q27] 条件计数
来源：http://dali.snrcjt.cn/Article/details/gtfawhlhth.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.yj20258.top/Article/details/gtoqwdoopf.html

[Q28] 求和与平均
来源：http://dali.hnqzz.top/Article/details/gtppjdlxiy.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.aibaodan.cn/Article/details/gthialvpnu.html

[Q29] 最大最小值
来源：http://dali.jianghu66.top/Article/details/gtdhnlysmz.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtppgvbbjf.html

[Q30] 分组统计
来源：http://dali.yuanzhike.top/Article/details/gtjcgxuaix.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.iojbl.cn/Article/details/gtwulrqdum.html

[Q31] 分组后过滤
来源：http://dali.zhengqikj.top/Article/details/gtrzghsvbc.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.sweek.top/Article/details/gtlsfcnnix.html

[Q32] 分组拼接字符串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgnwyfunl.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.c1oappe.top/Article/details/gtduggxiyf.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.birdmap.top/Article/details/gtnzgnwpbu.html

[Q33] 多列分组
来源：http://dali.chenzaomai.com/Article/details/gtignggovv.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.xuanzx.com/Article/details/gttluuabdd.html

[Q34] 每组取第一条
来源：http://dali.fengsongda.top/Article/details/gttehywyko.html

SELECT * FROM (
来源：http://dali.chenjidiqi.icu/Article/details/gtkmegwwus.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.pengpengdd.cyou/Article/details/gtuizyshvg.html

) t WHERE rn = 1;
来源：http://dali.yuanzhike.top/Article/details/gtbiewfajl.html

[Q35] 内连接
来源：http://dali.zhengqikj.top/Article/details/gtrfmpdtmh.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.jlsjyb.cn/Article/details/gtftynejee.html

[Q36] 左连接
来源：http://dali.aizwys.cn/Article/details/gtmmcakfxm.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.jinghuilouyu.cn/Article/details/gtgkbyohyi.html

[Q37] 右连接
来源：http://dali.gaohongyu789.top/Article/details/gtireazlku.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.jqgfzy.top/Article/details/gtjoywwvmw.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.yuxming.cn/Article/details/gtqixptlsn.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.yvedp.cn/Article/details/gtcoftrzzt.html

[Q39] 自连接（查上下级）
来源：http://dali.yuanzhike.top/Article/details/gtmqyolyig.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.cqqwz.cn/Article/details/gtoxwsdwdi.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.dianchejie.cn/Article/details/gtdujbwrmt.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gtuywawagb.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.hnxiangtu.top/Article/details/gtepzwpgxg.html

[Q41] 多表连接
来源：http://dali.nwbrower.top/Article/details/gtfrwiicye.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.cucudq.cn/Article/details/gtjcmuoncc.html

JOIN users u ON u.id = o.user_id
来源：http://dali.yuxming.cn/Article/details/gttnfxhrfn.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhiwuduotai.top/Article/details/gtaeqnfpwl.html

[Q42] 连接条件附加过滤
来源：http://dali.jinghuilouyu.cn/Article/details/gthwpetxvg.html

SELECT u.name, o.amount FROM users u
来源：http://dali.mhx1999.top/Article/details/gtfmpaxvhy.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.fzhhl.top/Article/details/gtzfjseaqw.html

[Q43] 标量子查询
来源：http://dali.jqgfzy.top/Article/details/gtzarjsfuv.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.snrcjt.cn/Article/details/gthurpjlhr.html

[Q44] IN 子查询
来源：http://dali.hywenlv.cn/Article/details/gtlhypvfzi.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtticnephw.html

[Q45] EXISTS 判断存在
来源：http://dali.shuidangran.top/Article/details/gtzohllvgu.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.sufxvd.cn/Article/details/gtzjxmgabl.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.meibo888.top/Article/details/gtowpuatgk.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.xuetiantiany.cn/Article/details/gtlvkovkor.html

[Q47] 与平均值比较
来源：http://dali.shuidangran.top/Article/details/gtbzihithl.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.jinghuilouyu.cn/Article/details/gtlmberfmw.html

[Q48] CTE 公用表表达式
来源：http://dali.feifeiyinyue.top/Article/details/gteuqkbeii.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.hfpthk.cn/Article/details/gtvrytrbhv.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.aizwys.cn/Article/details/gtayernyfx.html

[Q49] 更新单行
来源：http://dali.hysaishi.cn/Article/details/gtrirheuah.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhiwuduotai.top/Article/details/gtbgzcrhmt.html

[Q50] 批量更新
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqwhnpqhp.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhengqikj.top/Article/details/gtmuyugjcq.html

[Q51] 用子查询更新
来源：http://dali.redwolf501.top/Article/details/gtdckxlbyn.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.yonumen.top/Article/details/gtvfjhquzm.html

[Q52] 删除指定行
来源：http://dali.iojbl.cn/Article/details/gtnpvvzvzv.html

DELETE FROM users WHERE id = 10;
来源：http://dali.andypj.xyz/Article/details/gtcpssmkbw.html

[Q53] 按条件删除
来源：http://dali.yuxming.cn/Article/details/gtsjtjzbts.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.nwbrower.top/Article/details/gthzsiqkcg.html

[Q54] 清空表
来源：http://dali.9152youxi.cn/Article/details/gtidlsyqfs.html

TRUNCATE TABLE logs;
来源：http://dali.xylfe.cn/Article/details/gthxegroqg.html

[Q55] 排名（并列占位）
来源：http://dali.cucudq.cn/Article/details/gtearcbnby.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.chenzaomai.com/Article/details/gtxblnpeiq.html

[Q56] 密集排名（并列不占位）
来源：http://dali.ydzc1.top/Article/details/gtkamorupr.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.aizwys.cn/Article/details/gtxlrfrgpw.html

[Q57] 行号
来源：http://dali.ivvv.top/Article/details/gtbdyuftbh.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.chenjidiqi.icu/Article/details/gtygrjigvd.html

[Q58] 累计求和
来源：http://dali.kuanghao11.cn/Article/details/gtbygrunqn.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhixingplan.top/Article/details/gtbcdjxfza.html

[Q59] 分组内累计
来源：http://dali.andypj.xyz/Article/details/gtjtpyoeiz.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.pengpengdd.cyou/Article/details/gtaipuvgtk.html

[Q60] 取上一行 / 下一行
来源：http://dali.hongshengwenyu.top/Article/details/gtddavxjrk.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.yangfankeji.com/Article/details/gtfsgdhpab.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.hfpthk.cn/Article/details/gtdbrpyfza.html

[Q61] 移动平均
来源：http://dali.tian-w.cn/Article/details/gtfbyorrsf.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.hfpthk.cn/Article/details/gtkvbuewri.html

[Q62] 分组占比
来源：http://dali.haohaochexian.top/Article/details/gtelofqsuq.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.gzhubu.top/Article/details/gtsegdlqdk.html

[Q63] 开启事务
来源：http://dali.sxryk.cn/Article/details/gtypnlvjym.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.birdmap.top/Article/details/gthfnbafrw.html

[Q64] 提交事务
来源：http://dali.gogol.net.cn/Article/details/gttnuyzjyn.html

COMMIT;
来源：http://dali.haohaochexian.top/Article/details/gtruqehqjx.html

[Q65] 回滚事务
来源：http://dali.yj20258.top/Article/details/gtpfbokxon.html

ROLLBACK;
来源：http://dali.cdnleiting.top/Article/details/gtqbznkthq.html

[Q66] 行锁查询
来源：http://dali.hnqzz.top/Article/details/gtqkrxyxql.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.haohaochexian.top/Article/details/gtcwufrvat.html

[Q67] 设置隔离级别
来源：http://dali.yj20258.top/Article/details/gtizuqjatg.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.nanxinkj.top/Article/details/gtjugegwst.html

[Q68] 保存点
来源：http://dali.yanxiufei.cn/Article/details/gttlngnzfc.html

SAVEPOINT sp1;
来源：http://dali.kuanghao11.cn/Article/details/gtpdffftaq.html

ROLLBACK TO sp1;
来源：http://dali.zhengqikj.top/Article/details/gtxmltecxr.html

[Q69] 查看执行计划
来源：http://dali.chenjidiqi.icu/Article/details/gtiduhpfcf.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.aibaodan.cn/Article/details/gtevcdazfq.html

[Q70] 更新统计信息
来源：http://dali.cdnleiting.top/Article/details/gtjxdnewgg.html

ANALYZE TABLE users;
来源：http://dali.ivvv.top/Article/details/gtzsmoexlw.html

[Q71] 查看建表语句
来源：http://dali.chenlongwang.top/Article/details/gtlncueaor.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.quarkkingdee.top/Article/details/gtdryduicn.html

[Q72] 查看索引
来源：http://dali.daxiang520.top/Article/details/gtqmoalwpc.html

SHOW INDEX FROM users;
来源：http://dali.sxryk.cn/Article/details/gtqribbmrm.html

[Q73] 查看表状态
来源：http://dali.hnqzz.top/Article/details/gtpswvetud.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhoulong.xyz/Article/details/gtqftzdfrk.html

[Q74] 强制使用索引
来源：http://dali.yuxming.cn/Article/details/gtlqxkhtzu.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.andypj.xyz/Article/details/gtawpmpknt.html

[Q75] 日期格式化
来源：http://dali.cdnleiting.top/Article/details/gtahctidgh.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.chenjidiqi.icu/Article/details/gtzgcjhpgf.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.jinqigufen.top/Article/details/gtovzmdpjg.html

[Q76] 按天统计
来源：http://dali.feifeiyinyue.top/Article/details/gtnigvbrwx.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.9152youxi.cn/Article/details/gtkwxfsqkw.html

[Q77] 时间加减
来源：http://dali.9152youxi.cn/Article/details/gtdednbnrw.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.wangshuangyany.cn/Article/details/gtwbnjqouh.html

[Q78] 当前时间
来源：http://dali.redwolf501.top/Article/details/gtppyzglcb.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.yj20258888.top/Article/details/gttscfhowg.html

[Q79] 字符串拼接
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlfwmcphs.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.cqqwz.cn/Article/details/gtfnpsdupd.html

[Q80] 字符串截取
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcgmybvsz.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gtbypewbtv.html

[Q81] 字符串替换
来源：http://dali.ydzc1.top/Article/details/gtrsbpegju.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.dianchejie.cn/Article/details/gttgwedixv.html

[Q82] 字符长度与字节长度
来源：http://dali.kuanghao11.cn/Article/details/gtkhitdqkh.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.yonumen.top/Article/details/gtidqahywz.html

[Q83] 大小写转换
来源：http://dali.andypj.xyz/Article/details/gtvxrntfud.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgmiymwtw.html

[Q84] 去除首尾空格
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgqbrepmz.html

SELECT TRIM(name) FROM users;
来源：http://dali.ybcxt.top/Article/details/gtyxodftxk.html

[Q85] 数值取整
来源：http://dali.jinqigufen.top/Article/details/gtzzcbtvbp.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.ppjwa.cn/Article/details/gtebgokxaq.html

[Q86] 读取 JSON 字段
来源：http://dali.gaohongyu789.top/Article/details/gtiafxvtkv.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.jyoumei.cn/Article/details/gtfscyrnzv.html

[Q87] JSON 字段做条件
来源：http://dali.hfpthk.cn/Article/details/gtdbsojbkv.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.gzhubu.top/Article/details/gtiqngbyce.html

[Q88] 行转列（条件聚合）
来源：http://dali.yuxming.cn/Article/details/gtapicuxhl.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.feifeiyinyue.top/Article/details/gtqcwdxmel.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.nanxuanxn.top/Article/details/gttcvsusar.html

[Q89] 判断表是否存在
来源：http://dali.jinqigufen.top/Article/details/gtuwnmtuwz.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.jlsjyb.cn/Article/details/gtzpslvnbj.html

[Q90] 生成序号列
来源：http://dali.vqdsnc.cn/Article/details/gtjasmjdcc.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.cashguo.top/Article/details/gtduwmtljw.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtavjnvnuk.html

R. Bash 专题
来源：http://dali.yueranfly.top/Article/details/gtsrrdiugf.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtxwfuhjxb.html

[R01] shebang 与严格模式
来源：http://dali.shanyushiyangtech.top/Article/details/gtsxurdryq.html

#!/usr/bin/env bash
来源：http://dali.ivvv.top/Article/details/gtdkpekafd.html

set -euo pipefail
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlxzppvxn.html

[R02] 变量赋值与使用
来源：http://dali.nanxuanxn.top/Article/details/gtgjrixxtd.html

name="Tom"; echo "$name"
来源：http://dali.jqgfzy.top/Article/details/gthvbuqbds.html

[R03] 只读变量
来源：http://dali.zhoulong.xyz/Article/details/gtgkphnmaj.html

readonly PI=3.14
来源：http://dali.zdqjudy.top/Article/details/gtkrdroufb.html

[R04] 位置参数
来源：http://dali.chenjidiqi.icu/Article/details/gtiksgubby.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.pengpengdd.cyou/Article/details/gtkyadgkid.html

[R05] 参数默认值
来源：http://dali.mhx1999.top/Article/details/gtmkmnuvxa.html

name="${1:-default}"
来源：http://dali.daria6918.cn/Article/details/gtuksjkojv.html

[R06] 判断命令是否存在
来源：http://dali.xuetiantiany.cn/Article/details/gtlyddvnut.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.yangfankeji.com/Article/details/gtpzzieegk.html

[R07] if 判断文件
来源：http://dali.xinyue.icu/Article/details/gteftrmhww.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.jinyuanbaomall.cn/Article/details/gttmrnvajy.html

[R08] 数值比较
来源：http://dali.xylfe.cn/Article/details/gtxbcxfeuf.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.gzhubu.top/Article/details/gtfwhwqrfh.html

[R09] 字符串比较
来源：http://dali.haohaochexian.top/Article/details/gtpwdbwnyw.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.316326.xyz/Article/details/gtalembwyq.html

[R10] 正则匹配
来源：http://dali.ehwqpu.com/Article/details/gtdyufloag.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.hongshengwenyu.top/Article/details/gtihxjjwso.html

[R11] case 多分支
来源：http://dali.ydzc1.top/Article/details/gtfvxdomsz.html

case "$1" in
来源：http://dali.pengpengdd.cyou/Article/details/gtxdchlutq.html

start) echo "启动" ;;
来源：http://dali.zdqjudy.top/Article/details/gtispuvbcg.html

stop)  echo "停止" ;;
来源：http://dali.smart0.xyz/Article/details/gtmacwjfpz.html

*)     echo "未知命令" ;;
来源：http://dali.yanxiufei.cn/Article/details/gtqlqihepe.html

esac
来源：http://dali.pengpengdd.cyou/Article/details/gtklmswbub.html

[R12] for 遍历文件
来源：http://dali.jiagoushi.top/Article/details/gtolbhupjo.html

for f in *.txt; do echo "$f"; done
来源：http://dali.nanxinkj.top/Article/details/gtrzsjlwer.html

[R13] for 计数循环
来源：http://dali.sufxvd.cn/Article/details/gtegdsfbmo.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.pengpengdd.cyou/Article/details/gtdruxhdkx.html

[R14] C 风格 for
来源：http://dali.nanxinkj.top/Article/details/gtpkalnofg.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.0kj1m.cn/Article/details/gtjsfotoix.html

[R15] while 逐行读文件
来源：http://dali.snrcjt.cn/Article/details/gtuyqafogl.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.shzxlz.cn/Article/details/gtnuhgjpxa.html

[R16] until 等待条件
来源：http://dali.nanxuanxn.top/Article/details/gtwecisknt.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.guannengcc.top/Article/details/gthuwoppan.html

[R17] 数组定义与取值
来源：http://dali.cqqwz.cn/Article/details/gtmsbtbztv.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhiwuduotai.top/Article/details/gtyaipsomt.html

[R18] 遍历数组
来源：http://dali.yonumen.top/Article/details/gtpkovivbw.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.havefunace.top/Article/details/gtwjsosvkb.html

[R19] 数组长度
来源：http://dali.meibo888.top/Article/details/gtztfnjjkp.html

echo "${#arr[@]}"
来源：http://dali.zhoulong.xyz/Article/details/gtfuccgxlc.html

[R20] 关联数组（字典）
来源：http://dali.gaohongyu789.top/Article/details/gtesxibkwt.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.xuanzx.com/Article/details/gtmnismrwz.html

[R21] 字符串长度
来源：http://dali.pycfn.com/Article/details/gtfrsgugve.html

echo "${#s}"
来源：http://dali.birdmap.top/Article/details/gtpojqwzda.html

[R22] 截取子串
来源：http://dali.tanke756.top/Article/details/gtzqitcttg.html

echo "${s:0:5}"
来源：http://dali.yanxiufei.cn/Article/details/gtugetwyed.html

[R23] 字符串替换
来源：http://dali.yueranfly.top/Article/details/gtgpnvhwdu.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.haohaochexian.top/Article/details/gtkfrtpccw.html

[R24] 大小写转换
来源：http://dali.yj202588.top/Article/details/gtbwrjxczd.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.316326.xyz/Article/details/gttvyzikpw.html

[R25] 去后缀 / 去前缀
来源：http://dali.yanxiufei.cn/Article/details/gttdcnnnzl.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.xuanzx.com/Article/details/gtkzchescg.html

[R26] 命令替换
来源：http://dali.vqdsnc.cn/Article/details/gtlklvwwrb.html

now=$(date +%F); echo "$now"
来源：http://dali.svipenyu.cn/Article/details/gtfkirwghz.html

[R27] 算术展开
来源：http://dali.yj20258888.top/Article/details/gtqxfaujec.html

echo $((1 + 2 * 3))
来源：http://dali.nanxuanxn.top/Article/details/gtrbyyuzti.html

[R28] 浮点运算
来源：http://dali.shangyingyoupin.top/Article/details/gtkmdzadbo.html

echo "scale=2; 10/3" | bc
来源：http://dali.jlsjyb.cn/Article/details/gtbmfelisy.html

[R29] 定义函数
来源：http://dali.xylfe.cn/Article/details/gtnkzsmozl.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.snrcjt.cn/Article/details/gtbkwumucg.html

[R30] 函数返回状态码
来源：http://dali.nanxinkj.top/Article/details/gtgjklvyia.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.dianchejie.cn/Article/details/gtlufwquva.html

[R31] 局部变量
来源：http://dali.zhongyouzk.top/Article/details/gthefxmbpj.html

f() { local x=1; echo "$x"; }
来源：http://dali.dashuyun.cn/Article/details/gtqhvtfgmh.html

[R32] 参数个数校验
来源：http://dali.kuanghao11.cn/Article/details/gtsaufmewa.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.cqqwz.cn/Article/details/gtojtskpzr.html

[R33] 捕获错误并提示行号
来源：http://dali.zhoulong.xyz/Article/details/gtypdzmzwg.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.yonumen.top/Article/details/gtotryhduo.html

[R34] 退出时清理
来源：http://dali.wangdashe.top/Article/details/gtoijzolgd.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.hnxiangtu.top/Article/details/gtzxnwilbc.html

[R35] 后台执行并等待
来源：http://dali.havefunace.top/Article/details/gtmbrinfqq.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.tanke756.top/Article/details/gtdnpufyii.html

[R36] 并发执行多个任务
来源：http://dali.xuanzx.com/Article/details/gtwropfvsy.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.sufxvd.cn/Article/details/gtlyuzqanb.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gtmjinbqeg.html

files=$(ls -1)
来源：http://dali.daxiang520.top/Article/details/gtavxgteoh.html

[R38] 管道串联
来源：http://dali.mhx1999.top/Article/details/gtzrxonyxi.html

cat a.txt | grep -i error | wc -l
来源：http://dali.havefunace.top/Article/details/gtkyqxvaib.html

[R39] 重定向标准输出与错误
来源：http://dali.sweek.top/Article/details/gtqrvicqwx.html

cmd > out.log 2>&1
来源：http://dali.yj202588.top/Article/details/gttjqzjhkv.html

[R40] 追加写日志
来源：http://dali.nwbrower.top/Article/details/gtrpvjfllw.html

echo "log" >> out.log
来源：http://dali.shangyingyoupin.top/Article/details/gtzptxzcnk.html

[R41] 丢弃输出
来源：http://dali.kuanghao11.cn/Article/details/gtweratwjg.html

cmd >/dev/null 2>&1
来源：http://dali.meibo888.top/Article/details/gtspgovocu.html

[R42] 输入重定向
来源：http://dali.nanxinkj.top/Article/details/gtffptxiol.html

wc -l < a.txt
来源：http://dali.yj20258888.top/Article/details/gtoeniozle.html

[R43] 按名字查找文件
来源：http://dali.sweek.top/Article/details/gtprjowkqv.html

find . -name "*.log" -type f
来源：http://dali.redwolf501.top/Article/details/gtrcyteept.html

[R44] 按修改时间查找
来源：http://dali.aizwys.cn/Article/details/gtikirtimn.html

find . -mtime -7 -type f
来源：http://dali.yanxiufei.cn/Article/details/gtvzwvqftw.html

[R45] 批量删除
来源：http://dali.yueranfly.top/Article/details/gtgivpoyur.html

find . -name "*.tmp" -delete
来源：http://dali.redwolf501.top/Article/details/gtgyaatfbv.html

[R46] 递归替换文件内容
来源：http://dali.sxryk.cn/Article/details/gtxjovemrq.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.shanyushiyangtech.top/Article/details/gtpexrgeva.html

[R47] sed 单行替换
来源：http://dali.xinyue.icu/Article/details/gtqlpzgdev.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.cdnleiting.top/Article/details/gtpxubwtzb.html

[R48] awk 取指定列
来源：http://dali.jiagoushi.top/Article/details/gtyrsmjgui.html

awk '{print $1, $3}' a.txt
来源：http://dali.daria6918.cn/Article/details/gtthwwrjrf.html

[R49] awk 带条件
来源：http://dali.hammf.cn/Article/details/gtakzxjdpk.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.jianghu66.top/Article/details/gtpgizutqr.html

[R50] awk 求和
来源：http://dali.yj20258.top/Article/details/gtqdqplfcg.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.havefunace.top/Article/details/gtzrcxvehq.html

[R51] 排序去重取前几
来源：http://dali.ehwqpu.com/Article/details/gtigfdwxvh.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.shangyingyoupin.top/Article/details/gtvohhqowd.html

[R52] 统计行数
来源：http://dali.zhongyouzk.top/Article/details/gtjmbrmqhd.html

wc -l a.txt
来源：http://dali.cashguo.top/Article/details/gtoudvzdew.html

[R53] 查看文件头与实时尾
来源：http://dali.feifeiyinyue.top/Article/details/gtjwgibjtj.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.yongpay.top/Article/details/gtkbeaubhx.html

[R54] 比较两个文件
来源：http://dali.yuanzhike.top/Article/details/gtarzbrfem.html

diff a.txt b.txt
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdgpcpjjt.html

[R55] 压缩与解压
来源：http://dali.shuidangran.top/Article/details/gtoyiyvraj.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.hysaishi.cn/Article/details/gtuxxgbuxc.html

[R56] 远程拷贝
来源：http://dali.zdqjudy.top/Article/details/gtthqyqaud.html

scp file user@host:/path/
来源：http://dali.jinghuilouyu.cn/Article/details/gtlqeqomuv.html

[R57] 远程执行命令
来源：http://dali.jinghuilouyu.cn/Article/details/gticgbycvv.html

ssh user@host 'uptime'
来源：http://dali.havefunace.top/Article/details/gtnebuwntj.html

[R58] 下载文件
来源：http://dali.yj20258.top/Article/details/gtgbckglro.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.ydzc1.top/Article/details/gtzjyprlkj.html

[R59] 发 POST JSON
来源：http://dali.hysaishi.cn/Article/details/gtqdddhuyn.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.jianghu66.top/Article/details/gttnneyplg.html

[R60] 只看 HTTP 状态码
来源：http://dali.gogol.net.cn/Article/details/gtbdafjexf.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.hnxiangtu.top/Article/details/gtssybyrfp.html

[R61] 磁盘占用
来源：http://dali.havefunace.top/Article/details/gtvvsyigrn.html

df -h;  du -sh *
来源：http://dali.yuanzhike.top/Article/details/gtbbhicrll.html

[R62] 找最占空间的文件
来源：http://dali.fengsongda.top/Article/details/gtcssbkrrp.html

du -ah . | sort -rh | head -10
来源：http://dali.sxryk.cn/Article/details/gtmyjpdcal.html

[R63] 内存与进程
来源：http://dali.tian-w.cn/Article/details/gtklwxyfde.html

free -h;  ps aux | grep nginx
来源：http://dali.jqgfzy.top/Article/details/gtolvzpjdw.html

[R64] 结束进程
来源：http://dali.0kj1m.cn/Article/details/gtfiuduwsu.html

kill -9 $(pgrep -f app.py)
来源：http://dali.sufxvd.cn/Article/details/gtzjqgxasa.html

[R65] 查看端口占用
来源：http://dali.shzxlz.cn/Article/details/gtuypfnntb.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.daria6918.cn/Article/details/gttbycrauo.html

[R66] 定时任务
来源：http://dali.yangfankeji.com/Article/details/gtzydspuaa.html

crontab -e;  crontab -l
来源：http://dali.c1oappe.top/Article/details/gtnbjxokdk.html

[R67] 生成随机十六进制串
来源：http://dali.sxryk.cn/Article/details/gtcvhwxgiz.html


<!-- 参考信息 -->