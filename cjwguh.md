代发 wailian999

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.shangyingyoupin.top/Article/details/gtyidybher.html

[Q18] 模糊匹配
来源：http://dali.cheryme.top/Article/details/gtpzlakeas.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.sufxvd.cn/Article/details/gtpvhegilg.html

[Q19] 范围查询
来源：http://dali.wangdashe.top/Article/details/gtozxdqwol.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.shangyingyoupin.top/Article/details/gtopfemohm.html

[Q20] IN 列表
来源：http://dali.yanxiufei.cn/Article/details/gtewyscpmx.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.yuxming.cn/Article/details/gtseqstsvp.html

[Q21] 空值判断
来源：http://dali.jinghuilouyu.cn/Article/details/gtlurskrqf.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.guannengcc.top/Article/details/gtpgtnolwl.html

[Q22] 排序
来源：http://dali.meibo888.top/Article/details/gtjrpknenx.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.birdmap.top/Article/details/gtrfncevgl.html

[Q23] 分页
来源：http://dali.yj202588.top/Article/details/gthnfktqyh.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.sufxvd.cn/Article/details/gtvcykrqyq.html

[Q24] 去重
来源：http://dali.daxiang520.top/Article/details/gtspppwyua.html

SELECT DISTINCT city FROM users;
来源：http://dali.kuanghao11.cn/Article/details/gtxwnaelpc.html

[Q25] 只取前 N 条
来源：http://dali.hnqzz.top/Article/details/gtjgockbxg.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.xziqi.cn/Article/details/gttqmmoqdn.html

[Q26] 计数
来源：http://dali.316326.xyz/Article/details/gtcknaaqaq.html

SELECT COUNT(*) FROM users;
来源：http://dali.mhx1999.top/Article/details/gtqfagugdl.html

[Q27] 条件计数
来源：http://dali.cucudq.cn/Article/details/gtcogfxfyx.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gtrjqxzlir.html

[Q28] 求和与平均
来源：http://dali.yvedp.cn/Article/details/gtlqheysbf.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.wangdashe.top/Article/details/gtiwlybgra.html

[Q29] 最大最小值
来源：http://dali.cashguo.top/Article/details/gtwyesldau.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.sufxvd.cn/Article/details/gtnlfnnsfc.html

[Q30] 分组统计
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpwdrgbug.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhiwuduotai.top/Article/details/gtzwcpufqd.html

[Q31] 分组后过滤
来源：http://dali.yanxiufei.cn/Article/details/gthrubjftm.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.jinqigfzy.top/Article/details/gtotljvjeb.html

[Q32] 分组拼接字符串
来源：http://dali.zycfv.cn/Article/details/gtqjhjukii.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.jinqigufen.top/Article/details/gtivsqibio.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.316326.xyz/Article/details/gtxbndsbrk.html

[Q33] 多列分组
来源：http://dali.dianchejie.cn/Article/details/gttbmevlav.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.snrcjt.cn/Article/details/gthzzbpssp.html

[Q34] 每组取第一条
来源：http://dali.sxryk.cn/Article/details/gtsvplnhvm.html

SELECT * FROM (
来源：http://dali.vqdsnc.cn/Article/details/gtgvbxwxhq.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.daxiang520.top/Article/details/gtfgiipecx.html

) t WHERE rn = 1;
来源：http://dali.hfpthk.cn/Article/details/gteymtfsfi.html

[Q35] 内连接
来源：http://dali.zhoulong.xyz/Article/details/gtzuxndkfd.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.jqgufenzy.top/Article/details/gtkrxcsfze.html

[Q36] 左连接
来源：http://dali.kuanghao11.cn/Article/details/gtksdvhtmr.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.redwolf501.top/Article/details/gtlgvfzrws.html

[Q37] 右连接
来源：http://dali.zycfv.cn/Article/details/gtsnpihvjz.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.316326.xyz/Article/details/gteomhvmmr.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.0kj1m.cn/Article/details/gthdovttqi.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.jianghu66.top/Article/details/gtugrblrod.html

[Q39] 自连接（查上下级）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuhmvbiri.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.yangfankeji.com/Article/details/gttvrqwkuc.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.smart0.xyz/Article/details/gtvtviimsc.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.yonumen.top/Article/details/gtrycofkek.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.snrcjt.cn/Article/details/gtrzimcsqf.html

[Q41] 多表连接
来源：http://dali.shuidangran.top/Article/details/gtavrfcmth.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.jqgfzy.top/Article/details/gtmjfsyxfz.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gtiebslesp.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.yuxming.cn/Article/details/gtfnpljtmp.html

[Q42] 连接条件附加过滤
来源：http://dali.jqgufenzy.top/Article/details/gtiosrrysi.html

SELECT u.name, o.amount FROM users u
来源：http://dali.hnqzz.top/Article/details/gtcutqcxna.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.xuanzx.com/Article/details/gtjbwxgepp.html

[Q43] 标量子查询
来源：http://dali.zhixingplan.top/Article/details/gtosobdkul.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.jqgfzy.top/Article/details/gtjugzhhty.html

[Q44] IN 子查询
来源：http://dali.zhoulong.xyz/Article/details/gtagiooevp.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.cucudq.cn/Article/details/gtrrdlefik.html

[Q45] EXISTS 判断存在
来源：http://dali.jinqigufen.top/Article/details/gtsitusngj.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yongpay.top/Article/details/gtmcweczzb.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.haohaochexian.top/Article/details/gtbrjaixfv.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.xuetiantiany.cn/Article/details/gtexzvrtub.html

[Q47] 与平均值比较
来源：http://dali.nwbrower.top/Article/details/gtuegyfnwr.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.hammf.cn/Article/details/gtdborjrdf.html

[Q48] CTE 公用表表达式
来源：http://dali.yuxming.cn/Article/details/gtitrajzws.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.xylfe.cn/Article/details/gtcrocvttt.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.gaohongyu789.top/Article/details/gttlrekunm.html

[Q49] 更新单行
来源：http://dali.jinyuanbaomall.cn/Article/details/gtimjdonxa.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.haohaochexian.top/Article/details/gttovczlpf.html

[Q50] 批量更新
来源：http://dali.feifeiyinyue.top/Article/details/gtjbafaoea.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.dashuyun.cn/Article/details/gtkplclkiv.html

[Q51] 用子查询更新
来源：http://dali.fzhhl.top/Article/details/gtfvjukmxo.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.xinyue.icu/Article/details/gtmqmoqnnc.html

[Q52] 删除指定行
来源：http://dali.andypj.xyz/Article/details/gtbszphwid.html

DELETE FROM users WHERE id = 10;
来源：http://dali.vqdsnc.cn/Article/details/gtmkokgcrx.html

[Q53] 按条件删除
来源：http://dali.zhengqikj.top/Article/details/gtqtisomzy.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.feifeiyinyue.top/Article/details/gtlxycwzsi.html

[Q54] 清空表
来源：http://dali.tianlin.xyz/Article/details/gtrlovmujl.html

TRUNCATE TABLE logs;
来源：http://dali.bjfxy.top/Article/details/gtsempsdsa.html

[Q55] 排名（并列占位）
来源：http://dali.9152youxi.cn/Article/details/gtyvqqzhks.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.9152youxi.cn/Article/details/gtdcxqfhgp.html

[Q56] 密集排名（并列不占位）
来源：http://dali.cdnleiting.top/Article/details/gtnmfbxzos.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.9152youxi.cn/Article/details/gtieysonuz.html

[Q57] 行号
来源：http://dali.yj202588.top/Article/details/gtjhibktab.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrnnqyajk.html

[Q58] 累计求和
来源：http://dali.jinyuanbaomall.cn/Article/details/gteuaeoyva.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.sysykeji.top/Article/details/gtkrwxkviw.html

[Q59] 分组内累计
来源：http://dali.jianghu66.top/Article/details/gtxyjgpxpz.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.hfpthk.cn/Article/details/gtfcbyuzjr.html

[Q60] 取上一行 / 下一行
来源：http://dali.xinyue.icu/Article/details/gtwpvmowcg.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhixingplan.top/Article/details/gtafjhnaua.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.nwbrower.top/Article/details/gtaroyecbe.html

[Q61] 移动平均
来源：http://dali.hnqzz.top/Article/details/gtdvspcgpc.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.havefunace.top/Article/details/gttbifkxkk.html

[Q62] 分组占比
来源：http://dali.yvedp.cn/Article/details/gtyxdacfat.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.haohaochexian.top/Article/details/gtokzdelqo.html

[Q63] 开启事务
来源：http://dali.hnxiangtu.top/Article/details/gtwpwktrlo.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.cheryme.top/Article/details/gtcqjsbede.html

[Q64] 提交事务
来源：http://dali.yvedp.cn/Article/details/gtvbmcmdkp.html

COMMIT;
来源：http://dali.hongshengwenyu.top/Article/details/gtyxsogzsk.html

[Q65] 回滚事务
来源：http://dali.sufxvd.cn/Article/details/gtrphdgkbc.html

ROLLBACK;
来源：http://dali.shuidangran.top/Article/details/gtywimwlrj.html

[Q66] 行锁查询
来源：http://dali.zhixingplan.top/Article/details/gtokjxzggl.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.jinqigfzy.top/Article/details/gthsgnnurz.html

[Q67] 设置隔离级别
来源：http://dali.feifeiyinyue.top/Article/details/gtabksxoeu.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.0kj1m.cn/Article/details/gtbifqbhcg.html

[Q68] 保存点
来源：http://dali.yangfankeji.com/Article/details/gtousibnjl.html

SAVEPOINT sp1;
来源：http://dali.xuanzx.com/Article/details/gturfmunir.html

ROLLBACK TO sp1;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtblhwrklj.html

[Q69] 查看执行计划
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpanhnbmt.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.smart0.xyz/Article/details/gthumymrlc.html

[Q70] 更新统计信息
来源：http://dali.hywenlv.cn/Article/details/gtwfbqjraz.html

ANALYZE TABLE users;
来源：http://dali.ydzc1.top/Article/details/gttlkfgvnn.html

[Q71] 查看建表语句
来源：http://dali.iojbl.cn/Article/details/gtmkmdbzpw.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.cashguo.top/Article/details/gtlqvvvcbl.html

[Q72] 查看索引
来源：http://dali.zhiwuduotai.top/Article/details/gtktetcmhk.html

SHOW INDEX FROM users;
来源：http://dali.yvedp.cn/Article/details/gtfopumymf.html

[Q73] 查看表状态
来源：http://dali.chenlongwang.top/Article/details/gtdtdesoiz.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteezgzmgi.html

[Q74] 强制使用索引
来源：http://dali.daria6918.cn/Article/details/gtuhykzgqb.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.guannengcc.top/Article/details/gtqjphjpyz.html

[Q75] 日期格式化
来源：http://dali.nanxinkj.top/Article/details/gtogzncfkk.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.yuanzhike.top/Article/details/gtdlfpvfuj.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.cdnleiting.top/Article/details/gtrauswejf.html

[Q76] 按天统计
来源：http://dali.zycfv.cn/Article/details/gtmeulyqus.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.fengsongda.top/Article/details/gtucdhamjy.html

[Q77] 时间加减
来源：http://dali.yj202588.top/Article/details/gtmntlvrvb.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.sweek.top/Article/details/gtyehnoybi.html

[Q78] 当前时间
来源：http://dali.hfpthk.cn/Article/details/gtrxebbdms.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.yangfankeji.com/Article/details/gtnajeoklh.html

[Q79] 字符串拼接
来源：http://dali.ywan-chungtsiang.top/Article/details/gthnbbyilv.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.gotoacloud.top/Article/details/gtzhavbixs.html

[Q80] 字符串截取
来源：http://dali.fengsongda.top/Article/details/gtamwtjaqe.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gtackqqaqq.html

[Q81] 字符串替换
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzgzrsmsl.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.316326.xyz/Article/details/gtwznfhkpl.html

[Q82] 字符长度与字节长度
来源：http://dali.hongshengwenyu.top/Article/details/gtokgwovic.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.hysaishi.cn/Article/details/gtnxhrkxkk.html

[Q83] 大小写转换
来源：http://dali.gotoacloud.top/Article/details/gtcwuzqurf.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.yongpay.top/Article/details/gtcfwdhrcd.html

[Q84] 去除首尾空格
来源：http://dali.jqgufenzy.top/Article/details/gtkpngtqkp.html

SELECT TRIM(name) FROM users;
来源：http://dali.sufxvd.cn/Article/details/gtwknrridx.html

[Q85] 数值取整
来源：http://dali.ydzc1.top/Article/details/gtcchpkook.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.wangshuangyany.cn/Article/details/gtgltmihww.html

[Q86] 读取 JSON 字段
来源：http://dali.zdqjudy.top/Article/details/gtvtqlbglm.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.tian-w.cn/Article/details/gtefdxethl.html

[Q87] JSON 字段做条件
来源：http://dali.birdmap.top/Article/details/gttzuwuyqg.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.birdmap.top/Article/details/gtqrwzfitb.html

[Q88] 行转列（条件聚合）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkgamllmq.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.316326.xyz/Article/details/gtjisaqcdk.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.tian-w.cn/Article/details/gtxbasuvfj.html

[Q89] 判断表是否存在
来源：http://dali.cashguo.top/Article/details/gtzzzfjnao.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.hnxiangtu.top/Article/details/gtvxlifoov.html

[Q90] 生成序号列
来源：http://dali.cashguo.top/Article/details/gtdyakzqkf.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtipsaspur.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtsmhgcwhc.html

R. Bash 专题
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfkfvbepa.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtgpmhhicj.html

[R01] shebang 与严格模式
来源：http://dali.zhiwuduotai.top/Article/details/gtwvktntsx.html

#!/usr/bin/env bash
来源：http://dali.hnqzz.top/Article/details/gtmkxyftfh.html

set -euo pipefail
来源：http://dali.guowangkeji.top/Article/details/gtzxebohok.html

[R02] 变量赋值与使用
来源：http://dali.xuetiantiany.cn/Article/details/gtwbwemeuy.html

name="Tom"; echo "$name"
来源：http://dali.tanke756.top/Article/details/gtoomhmdbr.html

[R03] 只读变量
来源：http://dali.tanke756.top/Article/details/gtufjdjsng.html

readonly PI=3.14
来源：http://dali.mhx1999.top/Article/details/gtmbqdxalz.html

[R04] 位置参数
来源：http://dali.aibaodan.cn/Article/details/gtkyfmmwfd.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gtsqhilnte.html

[R05] 参数默认值
来源：http://dali.yj20258.top/Article/details/gtvhmggvru.html

name="${1:-default}"
来源：http://dali.hammf.cn/Article/details/gtckllgnmz.html

[R06] 判断命令是否存在
来源：http://dali.tanke756.top/Article/details/gthcfyktfl.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.hammf.cn/Article/details/gtfgaxdkqv.html

[R07] if 判断文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtivnwfjxm.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.dashuyun.cn/Article/details/gtugbmgffe.html

[R08] 数值比较
来源：http://dali.chenjidiqi.icu/Article/details/gtqeyabeiu.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhixingplan.top/Article/details/gtirfbwizq.html

[R09] 字符串比较
来源：http://dali.ydzc1.top/Article/details/gtxiwruzow.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.yongpay.top/Article/details/gtkwrvsflt.html

[R10] 正则匹配
来源：http://dali.yongpay.top/Article/details/gtdjtqvpbm.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.cdnleiting.top/Article/details/gtlaoxujdr.html

[R11] case 多分支
来源：http://dali.c1oappe.top/Article/details/gtrndrmqdl.html

case "$1" in
来源：http://dali.zhengqikj.top/Article/details/gthclmfdso.html

start) echo "启动" ;;
来源：http://dali.smart0.xyz/Article/details/gtmdxpbwla.html

stop)  echo "停止" ;;
来源：http://dali.ybcxt.top/Article/details/gtbowomfnf.html

*)     echo "未知命令" ;;
来源：http://dali.hnqzz.top/Article/details/gtqffgzliz.html

esac
来源：http://dali.jinghuilouyu.cn/Article/details/gtqqaunigy.html

[R12] for 遍历文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfvoyfgcf.html

for f in *.txt; do echo "$f"; done
来源：http://dali.0kj1m.cn/Article/details/gtjmjvmzlx.html

[R13] for 计数循环
来源：http://dali.haohaochexian.top/Article/details/gtdyqiwcqx.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zycfv.cn/Article/details/gtshktltdq.html

[R14] C 风格 for
来源：http://dali.yanxiufei.cn/Article/details/gtlfsqgvyt.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.jinghuilouyu.cn/Article/details/gtqjnsznhi.html

[R15] while 逐行读文件
来源：http://dali.sweek.top/Article/details/gtibziqlls.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.hammf.cn/Article/details/gtqpiswlwh.html

[R16] until 等待条件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsvcalglm.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhoulong.xyz/Article/details/gtdwmvllos.html

[R17] 数组定义与取值
来源：http://dali.kuanghao11.cn/Article/details/gttoekhynf.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.hfpthk.cn/Article/details/gtcommljag.html

[R18] 遍历数组
来源：http://dali.jqgufenzy.top/Article/details/gtobveagas.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.cdnleiting.top/Article/details/gtbgsyvxlj.html

[R19] 数组长度
来源：http://dali.sxryk.cn/Article/details/gtktohpkmq.html

echo "${#arr[@]}"
来源：http://dali.smart0.xyz/Article/details/gtqlszeduh.html

[R20] 关联数组（字典）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpdaeuoqi.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.hysaishi.cn/Article/details/gtbnesmnbb.html

[R21] 字符串长度
来源：http://dali.cucudq.cn/Article/details/gticrscxde.html

echo "${#s}"
来源：http://dali.yuanzhike.top/Article/details/gtcmedhfks.html

[R22] 截取子串
来源：http://dali.kuanghao11.cn/Article/details/gteuntkrvh.html

echo "${s:0:5}"
来源：http://dali.gzhubu.top/Article/details/gtvdhcaiwj.html

[R23] 字符串替换
来源：http://dali.kuanghao11.cn/Article/details/gtomfadmzz.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.birdmap.top/Article/details/gtcmvorxia.html

[R24] 大小写转换
来源：http://dali.zhengqikj.top/Article/details/gtngfpvdzo.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.tanke756.top/Article/details/gteglbllyx.html

[R25] 去后缀 / 去前缀
来源：http://dali.shangyingyoupin.top/Article/details/gtvvxcklsc.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.chenzaomai.com/Article/details/gtdsmbextp.html

[R26] 命令替换
来源：http://dali.shzxlz.cn/Article/details/gtiqverpji.html

now=$(date +%F); echo "$now"
来源：http://dali.birdmap.top/Article/details/gtfhhajqdq.html

[R27] 算术展开
来源：http://dali.316326.xyz/Article/details/gtrdhsmqkr.html

echo $((1 + 2 * 3))
来源：http://dali.yj20258.top/Article/details/gtqhgzvfby.html

[R28] 浮点运算
来源：http://dali.tianlin.xyz/Article/details/gtrxszrznp.html

echo "scale=2; 10/3" | bc
来源：http://dali.cheryme.top/Article/details/gtvrgifcum.html

[R29] 定义函数
来源：http://dali.cucudq.cn/Article/details/gtvgouqyzd.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.shzxlz.cn/Article/details/gtzzhbffwn.html

[R30] 函数返回状态码
来源：http://dali.sufxvd.cn/Article/details/gtajzuoqjf.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhiwuduotai.top/Article/details/gtbhtldesx.html

[R31] 局部变量
来源：http://dali.shanyushiyangtech.top/Article/details/gtgcngvgzw.html

f() { local x=1; echo "$x"; }
来源：http://dali.yuxming.cn/Article/details/gtkurfjbou.html

[R32] 参数个数校验
来源：http://dali.xuetiantiany.cn/Article/details/gtjawwhlif.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.snrcjt.cn/Article/details/gtrrkvhqrc.html

[R33] 捕获错误并提示行号
来源：http://dali.hfpthk.cn/Article/details/gtxdpzfnkr.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.fengsongda.top/Article/details/gtaxfbfnib.html

[R34] 退出时清理
来源：http://dali.tian-w.cn/Article/details/gtmrlkmeqi.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.haohaochexian.top/Article/details/gtxpfjopul.html

[R35] 后台执行并等待
来源：http://dali.feifeiyinyue.top/Article/details/gtqyxvcpte.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.fzhhl.top/Article/details/gthzuouqyz.html

[R36] 并发执行多个任务
来源：http://dali.snrcjt.cn/Article/details/gtxikcvozl.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.hnxiangtu.top/Article/details/gtmlxnfbut.html

[R37] 把输出赋给变量
来源：http://dali.fengsongda.top/Article/details/gtjmtoyjtf.html

files=$(ls -1)
来源：http://dali.chenlongwang.top/Article/details/gtmlmnrlaa.html

[R38] 管道串联
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpnkhqwfr.html

cat a.txt | grep -i error | wc -l
来源：http://dali.fengsongda.top/Article/details/gthtcjkhrb.html

[R39] 重定向标准输出与错误
来源：http://dali.gzhubu.top/Article/details/gtcawotfnb.html

cmd > out.log 2>&1
来源：http://dali.gogol.net.cn/Article/details/gtblqdndos.html

[R40] 追加写日志
来源：http://dali.chenlongwang.top/Article/details/gtxdoxonta.html

echo "log" >> out.log
来源：http://dali.hongshengwenyu.top/Article/details/gtqhgrpuzp.html

[R41] 丢弃输出
来源：http://dali.sweek.top/Article/details/gtmcacbogs.html

cmd >/dev/null 2>&1
来源：http://dali.zycfv.cn/Article/details/gtmtwmiqoh.html

[R42] 输入重定向
来源：http://dali.gogol.net.cn/Article/details/gtialwoffc.html

wc -l < a.txt
来源：http://dali.chenzaomai.com/Article/details/gtebmaeopq.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gtmcnpcksg.html

find . -name "*.log" -type f
来源：http://dali.hnqzz.top/Article/details/gtbywngsjd.html

[R44] 按修改时间查找
来源：http://dali.yj202588.top/Article/details/gtuzxditpy.html

find . -mtime -7 -type f
来源：http://dali.yangfankeji.com/Article/details/gtehfmzyob.html

[R45] 批量删除
来源：http://dali.quarkkingdee.top/Article/details/gtpspsyaxq.html

find . -name "*.tmp" -delete
来源：http://dali.cdnleiting.top/Article/details/gtanutxedl.html

[R46] 递归替换文件内容
来源：http://dali.tian-w.cn/Article/details/gthctziclf.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.meibo888.top/Article/details/gtuacazeid.html

[R47] sed 单行替换
来源：http://dali.cdnleiting.top/Article/details/gttcveofeo.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.chenlongwang.top/Article/details/gtifezlxju.html

[R48] awk 取指定列
来源：http://dali.guowangkeji.top/Article/details/gtxhdkhriu.html

awk '{print $1, $3}' a.txt
来源：http://dali.shangyingyoupin.top/Article/details/gtrjyezecq.html

[R49] awk 带条件
来源：http://dali.zhengqikj.top/Article/details/gtgxndnzqx.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.ybcxt.top/Article/details/gtvzfdejtr.html

[R50] awk 求和
来源：http://dali.birdmap.top/Article/details/gtgsohhqbk.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.chenjidiqi.icu/Article/details/gtmvqcgjgf.html

[R51] 排序去重取前几
来源：http://dali.yvedp.cn/Article/details/gthigjbtea.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.xinyue.icu/Article/details/gttzvtoozx.html

[R52] 统计行数
来源：http://dali.tianlin.xyz/Article/details/gtchknirjq.html

wc -l a.txt
来源：http://dali.andypj.xyz/Article/details/gtdcrtbzzq.html

[R53] 查看文件头与实时尾
来源：http://dali.andypj.xyz/Article/details/gtigspgzul.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.yj20258.top/Article/details/gtxzdheofu.html

[R54] 比较两个文件
来源：http://dali.zhongyouzk.top/Article/details/gtywzepkds.html

diff a.txt b.txt
来源：http://dali.zhoulong.xyz/Article/details/gtxppczher.html

[R55] 压缩与解压
来源：http://dali.redwolf501.top/Article/details/gtsmeqehpe.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.iojbl.cn/Article/details/gtfvcqepws.html

[R56] 远程拷贝
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlimmvsrf.html

scp file user@host:/path/
来源：http://dali.gogol.net.cn/Article/details/gtughqsrqm.html

[R57] 远程执行命令
来源：http://dali.yj20258888.top/Article/details/gtvktwuatb.html

ssh user@host 'uptime'
来源：http://dali.yj20258.top/Article/details/gtugzdfklf.html

[R58] 下载文件
来源：http://dali.zdqjudy.top/Article/details/gtibbslghg.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.yangfankeji.com/Article/details/gthbbeoliy.html

[R59] 发 POST JSON
来源：http://dali.sysykeji.top/Article/details/gtrhhgtujr.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.ivvv.top/Article/details/gtjmmgruci.html

[R60] 只看 HTTP 状态码
来源：http://dali.hfpthk.cn/Article/details/gtyuiuckbf.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhixingplan.top/Article/details/gtybwdsoxl.html

[R61] 磁盘占用
来源：http://dali.sufxvd.cn/Article/details/gtzuvzvfie.html

df -h;  du -sh *
来源：http://dali.haohaochexian.top/Article/details/gtsildckjz.html

[R62] 找最占空间的文件
来源：http://dali.hammf.cn/Article/details/gteqaadezv.html

du -ah . | sort -rh | head -10
来源：http://dali.tanke756.top/Article/details/gtzqpwwlyb.html

[R63] 内存与进程
来源：http://dali.9152youxi.cn/Article/details/gtvulcflii.html

free -h;  ps aux | grep nginx
来源：http://dali.ppjwa.cn/Article/details/gttftmvogm.html

[R64] 结束进程
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgzrieiix.html

kill -9 $(pgrep -f app.py)
来源：http://dali.nwbrower.top/Article/details/gtorxpwsxs.html

[R65] 查看端口占用
来源：http://dali.shanyushiyangtech.top/Article/details/gtvwgxkaxd.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.chenjidiqi.icu/Article/details/gtbxvrazsx.html

[R66] 定时任务
来源：http://dali.aibaodan.cn/Article/details/gtxjmymxlu.html

crontab -e;  crontab -l
来源：http://dali.yongpay.top/Article/details/gtfpstmxaa.html

[R67] 生成随机十六进制串
来源：http://dali.shangyingyoupin.top/Article/details/gtkdmmhvdb.html


<!-- 参考信息 -->