代发 wailian999

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.snrcjt.cn/Article/details/gtohakniwu.html

[Q20] IN 列表
来源：http://dali.cheryme.top/Article/details/gtoinrnyve.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.hammf.cn/Article/details/gtgbxskquj.html

[Q21] 空值判断
来源：http://dali.xziqi.cn/Article/details/gtbedccdcl.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.yvedp.cn/Article/details/gtshxahdnl.html

[Q22] 排序
来源：http://dali.yonumen.top/Article/details/gtzahuprbt.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.hongshengwenyu.top/Article/details/gtvwtrjxda.html

[Q23] 分页
来源：http://dali.zycfv.cn/Article/details/gtiygohqta.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.jiagoushi.top/Article/details/gtdqsehios.html

[Q24] 去重
来源：http://dali.yonumen.top/Article/details/gtgerovetc.html

SELECT DISTINCT city FROM users;
来源：http://dali.cdnleiting.top/Article/details/gtxbwsoydg.html

[Q25] 只取前 N 条
来源：http://dali.yvedp.cn/Article/details/gteqbahrcb.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.sufxvd.cn/Article/details/gtdavgkiez.html

[Q26] 计数
来源：http://dali.yj20258888.top/Article/details/gthqtfiwwi.html

SELECT COUNT(*) FROM users;
来源：http://dali.haohaochexian.top/Article/details/gtxmemgiyn.html

[Q27] 条件计数
来源：http://dali.xuetiantiany.cn/Article/details/gtyqupnqhc.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.jyoumei.cn/Article/details/gtbbrtmfqo.html

[Q28] 求和与平均
来源：http://dali.jyoumei.cn/Article/details/gticdvfctt.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.nwbrower.top/Article/details/gtpwziulbu.html

[Q29] 最大最小值
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwuotwaes.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.ivvv.top/Article/details/gthitdbgcn.html

[Q30] 分组统计
来源：http://dali.ydzc1.top/Article/details/gtjysoatlb.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.havefunace.top/Article/details/gtsjgmldcy.html

[Q31] 分组后过滤
来源：http://dali.yanxiufei.cn/Article/details/gtkfwbqukx.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.sufxvd.cn/Article/details/gtkkozibbe.html

[Q32] 分组拼接字符串
来源：http://dali.0kj1m.cn/Article/details/gtqsdwvici.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.daria6918.cn/Article/details/gtlsnbhxvv.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhixingplan.top/Article/details/gtjlvyquyq.html

[Q33] 多列分组
来源：http://dali.chenzaomai.com/Article/details/gtwoyrzcln.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.hongshengwenyu.top/Article/details/gtikfakfrd.html

[Q34] 每组取第一条
来源：http://dali.mhx1999.top/Article/details/gtzgzycmcc.html

SELECT * FROM (
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpzmetjlq.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.iojbl.cn/Article/details/gthnmomzbk.html

) t WHERE rn = 1;
来源：http://dali.yuanzhike.top/Article/details/gtsqjvrupg.html

[Q35] 内连接
来源：http://dali.jyoumei.cn/Article/details/gtmwcdevvn.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.daxiang520.top/Article/details/gtqjuxegbr.html

[Q36] 左连接
来源：http://dali.sxryk.cn/Article/details/gtmutywlef.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.sysykeji.top/Article/details/gtjyknmwbq.html

[Q37] 右连接
来源：http://dali.yongpay.top/Article/details/gtyqzjcmml.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.xuanzx.com/Article/details/gthpulgjtp.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.chenjidiqi.icu/Article/details/gtfnztjtuk.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhixingplan.top/Article/details/gtbuztpnco.html

[Q39] 自连接（查上下级）
来源：http://dali.zhixingplan.top/Article/details/gtjwoovlkl.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.316326.xyz/Article/details/gtfumzoxqu.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.tian-w.cn/Article/details/gtweoptgfi.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.xuanzx.com/Article/details/gttdqlkbpw.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.hywenlv.cn/Article/details/gteqjwopeg.html

[Q41] 多表连接
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvzyfalaz.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.smart0.xyz/Article/details/gtvoiplejg.html

JOIN users u ON u.id = o.user_id
来源：http://dali.0kj1m.cn/Article/details/gtacztcdzx.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhengqikj.top/Article/details/gtcahkjabs.html

[Q42] 连接条件附加过滤
来源：http://dali.yj20258888.top/Article/details/gtjklyikwh.html

SELECT u.name, o.amount FROM users u
来源：http://dali.birdmap.top/Article/details/gthsmweljr.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqnhqdekb.html

[Q43] 标量子查询
来源：http://dali.yj20258.top/Article/details/gtekgwusge.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.yongpay.top/Article/details/gtxhdrvgmg.html

[Q44] IN 子查询
来源：http://dali.zdqjudy.top/Article/details/gtklvjyric.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.havefunace.top/Article/details/gtlegjgbdg.html

[Q45] EXISTS 判断存在
来源：http://dali.shuidangran.top/Article/details/gtvrkxslyf.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.snrcjt.cn/Article/details/gtjsbgttsp.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gtpoimsnvf.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.nanxuanxn.top/Article/details/gtexzwflbd.html

[Q47] 与平均值比较
来源：http://dali.jqgufenzy.top/Article/details/gtzsrmkdsd.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.ybcxt.top/Article/details/gtturkxaej.html

[Q48] CTE 公用表表达式
来源：http://dali.gotoacloud.top/Article/details/gtblbhkeus.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.xylfe.cn/Article/details/gtctzzcttg.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.xinyue.icu/Article/details/gtaqxvnynj.html

[Q49] 更新单行
来源：http://dali.ybcxt.top/Article/details/gtygljbahh.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhoulong.xyz/Article/details/gthubyalsa.html

[Q50] 批量更新
来源：http://dali.pycfn.com/Article/details/gtbziwryjc.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.jianghu66.top/Article/details/gtmamcpuve.html

[Q51] 用子查询更新
来源：http://dali.jyoumei.cn/Article/details/gtlaymqgyf.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.yvedp.cn/Article/details/gtqrmffjpy.html

[Q52] 删除指定行
来源：http://dali.hnqzz.top/Article/details/gtgdonrhcu.html

DELETE FROM users WHERE id = 10;
来源：http://dali.feifeiyinyue.top/Article/details/gtxwycgaod.html

[Q53] 按条件删除
来源：http://dali.jinqigfzy.top/Article/details/gtaewzblvw.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.hnqzz.top/Article/details/gtnqlwrxju.html

[Q54] 清空表
来源：http://dali.andypj.xyz/Article/details/gtoqmilylo.html

TRUNCATE TABLE logs;
来源：http://dali.daxiang520.top/Article/details/gtskxhvnsy.html

[Q55] 排名（并列占位）
来源：http://dali.yj20258.top/Article/details/gtdwriaerz.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.9152youxi.cn/Article/details/gthbofmgdu.html

[Q56] 密集排名（并列不占位）
来源：http://dali.sufxvd.cn/Article/details/gtsplyaafo.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.cucudq.cn/Article/details/gthcimrohc.html

[Q57] 行号
来源：http://dali.zhaomingkeji.xyz/Article/details/gtanevicpi.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.bjfxy.top/Article/details/gttbfepfym.html

[Q58] 累计求和
来源：http://dali.shuidangran.top/Article/details/gtupewwssl.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.gogol.net.cn/Article/details/gtgrxrlrxr.html

[Q59] 分组内累计
来源：http://dali.sufxvd.cn/Article/details/gtasunxgjh.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.mhx1999.top/Article/details/gtxfurqvdr.html

[Q60] 取上一行 / 下一行
来源：http://dali.chenlongwang.top/Article/details/gtuagfnvwa.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.shangyingyoupin.top/Article/details/gthfpxbllt.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.xziqi.cn/Article/details/gtrdmwcikc.html

[Q61] 移动平均
来源：http://dali.yuxming.cn/Article/details/gtmwjxbytm.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zycfv.cn/Article/details/gtwxljctwp.html

[Q62] 分组占比
来源：http://dali.hywenlv.cn/Article/details/gtyhdgpjih.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.ydzc1.top/Article/details/gtfndgwsvw.html

[Q63] 开启事务
来源：http://dali.yanxiufei.cn/Article/details/gtopibrddh.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.chenlongwang.top/Article/details/gtudhklvlx.html

[Q64] 提交事务
来源：http://dali.daxiang520.top/Article/details/gtyvoleiys.html

COMMIT;
来源：http://dali.aizwys.cn/Article/details/gtlmyeeuwn.html

[Q65] 回滚事务
来源：http://dali.hnqzz.top/Article/details/gtyubosxwc.html

ROLLBACK;
来源：http://dali.ehwqpu.com/Article/details/gtjodnfqvn.html

[Q66] 行锁查询
来源：http://dali.yj20258.top/Article/details/gtpbuhkyxa.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.cqqwz.cn/Article/details/gtsntlyxlh.html

[Q67] 设置隔离级别
来源：http://dali.tianlin.xyz/Article/details/gtpbqukgem.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.316326.xyz/Article/details/gtqcsmfuid.html

[Q68] 保存点
来源：http://dali.gotoacloud.top/Article/details/gtwutyqlxu.html

SAVEPOINT sp1;
来源：http://dali.yuanzhike.top/Article/details/gtfslhzbax.html

ROLLBACK TO sp1;
来源：http://dali.ppjwa.cn/Article/details/gthxvnptfy.html

[Q69] 查看执行计划
来源：http://dali.gogol.net.cn/Article/details/gtqutmvpqz.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.hongshengwenyu.top/Article/details/gtyhvxairl.html

[Q70] 更新统计信息
来源：http://dali.zhengqikj.top/Article/details/gtpvqowivo.html

ANALYZE TABLE users;
来源：http://dali.cashguo.top/Article/details/gtqtfxutzx.html

[Q71] 查看建表语句
来源：http://dali.dashuyun.cn/Article/details/gtarfahenz.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.nanxuanxn.top/Article/details/gtynhxictl.html

[Q72] 查看索引
来源：http://dali.wangshuangyany.cn/Article/details/gtgvysuwdi.html

SHOW INDEX FROM users;
来源：http://dali.yueranfly.top/Article/details/gthwumctwt.html

[Q73] 查看表状态
来源：http://dali.chenzaomai.com/Article/details/gtqgipnbzr.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkflvxzds.html

[Q74] 强制使用索引
来源：http://dali.aizwys.cn/Article/details/gtegaeoiii.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.yanxiufei.cn/Article/details/gtubqabtlq.html

[Q75] 日期格式化
来源：http://dali.guowangkeji.top/Article/details/gtbofuftgn.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.andypj.xyz/Article/details/gtkfkbfrpd.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.xinyue.icu/Article/details/gtpisvsnbl.html

[Q76] 按天统计
来源：http://dali.yuxming.cn/Article/details/gtzpqhzyox.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.ybcxt.top/Article/details/gtrjvnkoci.html

[Q77] 时间加减
来源：http://dali.shuidangran.top/Article/details/gticwpydze.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjtxvrloq.html

[Q78] 当前时间
来源：http://dali.gaohongyu789.top/Article/details/gttaxvfswb.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.jianghu66.top/Article/details/gtgzgdgouu.html

[Q79] 字符串拼接
来源：http://dali.andypj.xyz/Article/details/gtyjstlqcs.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.wangdashe.top/Article/details/gtfnbmrqud.html

[Q80] 字符串截取
来源：http://dali.yvedp.cn/Article/details/gtqlcgyqes.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.gogol.net.cn/Article/details/gtsvxzprnr.html

[Q81] 字符串替换
来源：http://dali.xylfe.cn/Article/details/gtlinzscbz.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhongyouzk.top/Article/details/gtobfaxfou.html

[Q82] 字符长度与字节长度
来源：http://dali.dashuyun.cn/Article/details/gtsvwqkwql.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gttropgdet.html

[Q83] 大小写转换
来源：http://dali.iojbl.cn/Article/details/gtarsmghgg.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gtlrprnhah.html

[Q84] 去除首尾空格
来源：http://dali.shanyushiyangtech.top/Article/details/gtwigzlpgp.html

SELECT TRIM(name) FROM users;
来源：http://dali.jianghu66.top/Article/details/gtnuyvmndf.html

[Q85] 数值取整
来源：http://dali.aibaodan.cn/Article/details/gtuwfyfgbx.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.kuanghao11.cn/Article/details/gtcbetxout.html

[Q86] 读取 JSON 字段
来源：http://dali.c1oappe.top/Article/details/gtgktzqgxy.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.shuidangran.top/Article/details/gtfhqdmgkp.html

[Q87] JSON 字段做条件
来源：http://dali.tian-w.cn/Article/details/gtmpizhxqw.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.yangfankeji.com/Article/details/gtxmpaaobs.html

[Q88] 行转列（条件聚合）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcjijgncd.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.ivvv.top/Article/details/gtqgfiwbgp.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.wangshuangyany.cn/Article/details/gthprmydkx.html

[Q89] 判断表是否存在
来源：http://dali.yj20258888.top/Article/details/gtgyihfsew.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.yanxiufei.cn/Article/details/gteijmylcn.html

[Q90] 生成序号列
来源：http://dali.ydzc1.top/Article/details/gtczmuavnm.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.yj20258888.top/Article/details/gtgynqsvkd.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtssgwvbri.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gtavrqshqt.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtsnqxnuzd.html

[R01] shebang 与严格模式
来源：http://dali.dashuyun.cn/Article/details/gtqalqejxl.html

#!/usr/bin/env bash
来源：http://dali.nanxuanxn.top/Article/details/gtyzrgojeu.html

set -euo pipefail
来源：http://dali.shanyushiyangtech.top/Article/details/gtuagnecar.html

[R02] 变量赋值与使用
来源：http://dali.xylfe.cn/Article/details/gtgiznxzkm.html

name="Tom"; echo "$name"
来源：http://dali.gaohongyu789.top/Article/details/gtucvcmyzk.html

[R03] 只读变量
来源：http://dali.birdmap.top/Article/details/gtjuokuffc.html

readonly PI=3.14
来源：http://dali.shuidangran.top/Article/details/gtfnkgcxre.html

[R04] 位置参数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtthsobdav.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.xuetiantiany.cn/Article/details/gtzyzsqhbh.html

[R05] 参数默认值
来源：http://dali.pycfn.com/Article/details/gtowvkcidk.html

name="${1:-default}"
来源：http://dali.yj202588.top/Article/details/gtvjdbgssb.html

[R06] 判断命令是否存在
来源：http://dali.316326.xyz/Article/details/gthuxjmmst.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.vqdsnc.cn/Article/details/gtvothsrvh.html

[R07] if 判断文件
来源：http://dali.havefunace.top/Article/details/gtlgliqtec.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.birdmap.top/Article/details/gtvpnzwclx.html

[R08] 数值比较
来源：http://dali.svipenyu.cn/Article/details/gtluorgkuk.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.sweek.top/Article/details/gtvweopgsz.html

[R09] 字符串比较
来源：http://dali.smart0.xyz/Article/details/gtizcasxpt.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.shangyingyoupin.top/Article/details/gthehcwcfx.html

[R10] 正则匹配
来源：http://dali.xinyue.icu/Article/details/gtjnesvpwd.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.ehwqpu.com/Article/details/gtcuhesrht.html

[R11] case 多分支
来源：http://dali.jiagoushi.top/Article/details/gtbtwfsnsy.html

case "$1" in
来源：http://dali.snrcjt.cn/Article/details/gtfomiqegw.html

start) echo "启动" ;;
来源：http://dali.birdmap.top/Article/details/gtawsamnrq.html

stop)  echo "停止" ;;
来源：http://dali.jianghu66.top/Article/details/gtbsckoiot.html

*)     echo "未知命令" ;;
来源：http://dali.pycfn.com/Article/details/gtfsifoqfm.html

esac
来源：http://dali.daria6918.cn/Article/details/gtapgpqfmc.html

[R12] for 遍历文件
来源：http://dali.sysykeji.top/Article/details/gtooacotrp.html

for f in *.txt; do echo "$f"; done
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtntvinkfg.html

[R13] for 计数循环
来源：http://dali.zdqjudy.top/Article/details/gtlabsfzqi.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhaomingkeji.xyz/Article/details/gthjitpxwj.html

[R14] C 风格 for
来源：http://dali.shangyingyoupin.top/Article/details/gtxiidudoq.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.hnqzz.top/Article/details/gtghgnbpti.html

[R15] while 逐行读文件
来源：http://dali.hammf.cn/Article/details/gtdsrhjuyn.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.snrcjt.cn/Article/details/gtncoedxkb.html

[R16] until 等待条件
来源：http://dali.sweek.top/Article/details/gtygqkilox.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.wangdashe.top/Article/details/gtyiibrnqm.html

[R17] 数组定义与取值
来源：http://dali.zhoulong.xyz/Article/details/gtegrgmvxp.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.yangfankeji.com/Article/details/gtozbfhfcb.html

[R18] 遍历数组
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbkzxvlic.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.iojbl.cn/Article/details/gtidibbhso.html

[R19] 数组长度
来源：http://dali.nanxuanxn.top/Article/details/gtlvlunayk.html

echo "${#arr[@]}"
来源：http://dali.kuanghao11.cn/Article/details/gtznbxvcty.html

[R20] 关联数组（字典）
来源：http://dali.xziqi.cn/Article/details/gtogkwxhpz.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.jinghuilouyu.cn/Article/details/gtzifitvzs.html

[R21] 字符串长度
来源：http://dali.zycfv.cn/Article/details/gtcafcolzm.html

echo "${#s}"
来源：http://dali.chenzaomai.com/Article/details/gtrrcvutcf.html

[R22] 截取子串
来源：http://dali.meibo888.top/Article/details/gttgselsxi.html

echo "${s:0:5}"
来源：http://dali.c1oappe.top/Article/details/gtggwmkqbc.html

[R23] 字符串替换
来源：http://dali.feifeiyinyue.top/Article/details/gtfhhffzhx.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.jqgufenzy.top/Article/details/gthncrjrip.html

[R24] 大小写转换
来源：http://dali.cheryme.top/Article/details/gtqghtsntn.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.yueranfly.top/Article/details/gtlhpwmodh.html

[R25] 去后缀 / 去前缀
来源：http://dali.yj20258888.top/Article/details/gtpzxybttv.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.yj20258.top/Article/details/gthyufgvdg.html

[R26] 命令替换
来源：http://dali.xuanzx.com/Article/details/gtyayeadxq.html

now=$(date +%F); echo "$now"
来源：http://dali.ivvv.top/Article/details/gtkegrtuni.html

[R27] 算术展开
来源：http://dali.daria6918.cn/Article/details/gtemwahxyp.html

echo $((1 + 2 * 3))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtulwhuwjb.html

[R28] 浮点运算
来源：http://dali.9152youxi.cn/Article/details/gtibyjbvva.html

echo "scale=2; 10/3" | bc
来源：http://dali.cashguo.top/Article/details/gtazxoygai.html

[R29] 定义函数
来源：http://dali.ybcxt.top/Article/details/gthrdcjxtx.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.cucudq.cn/Article/details/gtgpwmgvhr.html

[R30] 函数返回状态码
来源：http://dali.yj20258888.top/Article/details/gtkqclbpfk.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.daxiang520.top/Article/details/gtuyuquamb.html

[R31] 局部变量
来源：http://dali.iojbl.cn/Article/details/gtexbssdjh.html

f() { local x=1; echo "$x"; }
来源：http://dali.pengpengdd.cyou/Article/details/gtkwyjnwxk.html

[R32] 参数个数校验
来源：http://dali.gotoacloud.top/Article/details/gtrmuukuen.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.cqqwz.cn/Article/details/gtzsrpnzpp.html

[R33] 捕获错误并提示行号
来源：http://dali.yueranfly.top/Article/details/gtiqrpnjmv.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.yvedp.cn/Article/details/gtlyoyyiin.html

[R34] 退出时清理
来源：http://dali.316326.xyz/Article/details/gtlnaqmovp.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.aibaodan.cn/Article/details/gttkpeekil.html

[R35] 后台执行并等待
来源：http://dali.snrcjt.cn/Article/details/gtgcvjidln.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.chenjidiqi.icu/Article/details/gttggeathn.html

[R36] 并发执行多个任务
来源：http://dali.zdqjudy.top/Article/details/gtzmiddtyg.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.xziqi.cn/Article/details/gtpdgrvuoc.html

[R37] 把输出赋给变量
来源：http://dali.andypj.xyz/Article/details/gtrsvawgfh.html

files=$(ls -1)
来源：http://dali.wangshuangyany.cn/Article/details/gtzqlrwnjv.html

[R38] 管道串联
来源：http://dali.yueranfly.top/Article/details/gtadrpsyuy.html

cat a.txt | grep -i error | wc -l
来源：http://dali.jinghuilouyu.cn/Article/details/gtlqfcazef.html

[R39] 重定向标准输出与错误
来源：http://dali.jinqigufen.top/Article/details/gttjnskusp.html

cmd > out.log 2>&1
来源：http://dali.shuidangran.top/Article/details/gtubjardus.html

[R40] 追加写日志
来源：http://dali.mhx1999.top/Article/details/gtgsuwgslg.html

echo "log" >> out.log
来源：http://dali.ppjwa.cn/Article/details/gtqqzuifen.html

[R41] 丢弃输出
来源：http://dali.jqgufenzy.top/Article/details/gtujojmbla.html

cmd >/dev/null 2>&1
来源：http://dali.sufxvd.cn/Article/details/gtpxskcidw.html

[R42] 输入重定向
来源：http://dali.jiagoushi.top/Article/details/gtmknqjmcm.html

wc -l < a.txt
来源：http://dali.redwolf501.top/Article/details/gtacoxjvvl.html

[R43] 按名字查找文件
来源：http://dali.cashguo.top/Article/details/gtlpemgfek.html

find . -name "*.log" -type f
来源：http://dali.ehwqpu.com/Article/details/gtkduixkpy.html

[R44] 按修改时间查找
来源：http://dali.gaohongyu789.top/Article/details/gtljjvvebs.html

find . -mtime -7 -type f
来源：http://dali.guannengcc.top/Article/details/gtfcyelyjo.html

[R45] 批量删除
来源：http://dali.yangfankeji.com/Article/details/gtqmnryswh.html

find . -name "*.tmp" -delete
来源：http://dali.316326.xyz/Article/details/gtryjajdnp.html

[R46] 递归替换文件内容
来源：http://dali.c1oappe.top/Article/details/gtyhrilcrt.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.hnqzz.top/Article/details/gtffqcrilk.html

[R47] sed 单行替换
来源：http://dali.meibo888.top/Article/details/gtratokvto.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmfaejzey.html

[R48] awk 取指定列
来源：http://dali.shanyushiyangtech.top/Article/details/gtceqtfagv.html

awk '{print $1, $3}' a.txt
来源：http://dali.dashuyun.cn/Article/details/gtcszaqxve.html

[R49] awk 带条件
来源：http://dali.guannengcc.top/Article/details/gtezcvsxlq.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.kuanghao11.cn/Article/details/gtbktdejgw.html

[R50] awk 求和
来源：http://dali.chenlongwang.top/Article/details/gtmxxlivlt.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.ppjwa.cn/Article/details/gtiqymbvzn.html

[R51] 排序去重取前几
来源：http://dali.xinyue.icu/Article/details/gtzteowsba.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.hfpthk.cn/Article/details/gtplfkqamm.html

[R52] 统计行数
来源：http://dali.0kj1m.cn/Article/details/gtugpzacmf.html

wc -l a.txt
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtebzfvugk.html

[R53] 查看文件头与实时尾
来源：http://dali.aizwys.cn/Article/details/gtsnqpssij.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.ppjwa.cn/Article/details/gttwfrmwas.html

[R54] 比较两个文件
来源：http://dali.jqgfzy.top/Article/details/gtsplieecu.html

diff a.txt b.txt
来源：http://dali.ivvv.top/Article/details/gtewttcvkj.html

[R55] 压缩与解压
来源：http://dali.feifeiyinyue.top/Article/details/gtrxdnkusm.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.jlsjyb.cn/Article/details/gtiqnsurmu.html

[R56] 远程拷贝
来源：http://dali.nwbrower.top/Article/details/gtlxinttyf.html

scp file user@host:/path/
来源：http://dali.gogol.net.cn/Article/details/gtmhogxedi.html

[R57] 远程执行命令
来源：http://dali.mhx1999.top/Article/details/gtntnabuxh.html

ssh user@host 'uptime'
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdaytvacz.html

[R58] 下载文件
来源：http://dali.fengsongda.top/Article/details/gtisutodmx.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.hfpthk.cn/Article/details/gtmqejbqxw.html

[R59] 发 POST JSON
来源：http://dali.sysykeji.top/Article/details/gtlusbovxa.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.shangyingyoupin.top/Article/details/gthwwkxwzp.html

[R60] 只看 HTTP 状态码
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrpwypbxr.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.fengsongda.top/Article/details/gtttfyiplp.html

[R61] 磁盘占用
来源：http://dali.yongpay.top/Article/details/gtgvfjfdxf.html

df -h;  du -sh *
来源：http://dali.aibaodan.cn/Article/details/gtyewnvapw.html

[R62] 找最占空间的文件
来源：http://dali.aibaodan.cn/Article/details/gtdxbagpwm.html

du -ah . | sort -rh | head -10
来源：http://dali.zycfv.cn/Article/details/gtegjhpnhc.html

[R63] 内存与进程
来源：http://dali.yonumen.top/Article/details/gtbobfgycp.html

free -h;  ps aux | grep nginx
来源：http://dali.daxiang520.top/Article/details/gtvzbaomjo.html

[R64] 结束进程
来源：http://dali.smart0.xyz/Article/details/gtprqkxrxe.html

kill -9 $(pgrep -f app.py)
来源：http://dali.ybcxt.top/Article/details/gtcubmavgs.html

[R65] 查看端口占用
来源：http://dali.tanke756.top/Article/details/gtkqsxjqdd.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.yvedp.cn/Article/details/gtluitegoa.html

[R66] 定时任务
来源：http://dali.nanxinkj.top/Article/details/gtccbpdzbx.html

crontab -e;  crontab -l
来源：http://dali.haohaochexian.top/Article/details/gtigodtgyf.html

[R67] 生成随机十六进制串
来源：http://dali.hnqzz.top/Article/details/gtovxdhrac.html

openssl rand -hex 16
来源：http://dali.gzhubu.top/Article/details/gtutymuohe.html

[R68] 计算文件校验值
来源：http://dali.tanke756.top/Article/details/gtcvlizwxg.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.mhx1999.top/Article/details/gteljyiwoe.html

[R69] 生成随机密码
来源：http://dali.xziqi.cn/Article/details/gtlmuhmsel.html


<!-- 参考信息 -->