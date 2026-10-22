代发 wailian999

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.nanxuanxn.top/Article/details/gtnmeorrsi.html

[Q22] 排序
来源：http://dali.ivvv.top/Article/details/gtxjtgmixr.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.havefunace.top/Article/details/gtqpsalstb.html

[Q23] 分页
来源：http://dali.9152youxi.cn/Article/details/gtgryuwvug.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.xuanzx.com/Article/details/gtxrfgihjm.html

[Q24] 去重
来源：http://dali.fengsongda.top/Article/details/gtlroosopg.html

SELECT DISTINCT city FROM users;
来源：http://dali.nwbrower.top/Article/details/gtoqnyufiy.html

[Q25] 只取前 N 条
来源：http://dali.jinqigfzy.top/Article/details/gtqanqxhjo.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.jiagoushi.top/Article/details/gtvugxfxhi.html

[Q26] 计数
来源：http://dali.guowangkeji.top/Article/details/gtkdkjykci.html

SELECT COUNT(*) FROM users;
来源：http://dali.fengsongda.top/Article/details/gtttxafwla.html

[Q27] 条件计数
来源：http://dali.0kj1m.cn/Article/details/gtspmktqzx.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.ydzc1.top/Article/details/gtshnsohgt.html

[Q28] 求和与平均
来源：http://dali.xuanzx.com/Article/details/gtcpkralfx.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.nwbrower.top/Article/details/gtqujxzvcs.html

[Q29] 最大最小值
来源：http://dali.ppjwa.cn/Article/details/gtuufdwqhq.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zdqjudy.top/Article/details/gtttuuxjcw.html

[Q30] 分组统计
来源：http://dali.wangdashe.top/Article/details/gtlbsbztah.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhengqikj.top/Article/details/gtpkrtggda.html

[Q31] 分组后过滤
来源：http://dali.yvedp.cn/Article/details/gtfijrqmdk.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.yuxming.cn/Article/details/gtltljlkcb.html

[Q32] 分组拼接字符串
来源：http://dali.pengpengdd.cyou/Article/details/gtykzzbgmp.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.daria6918.cn/Article/details/gtjgmdnitq.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.nanxuanxn.top/Article/details/gtadknkyvh.html

[Q33] 多列分组
来源：http://dali.hnqzz.top/Article/details/gtheawmixh.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.jinqigfzy.top/Article/details/gtgoyhyzqe.html

[Q34] 每组取第一条
来源：http://dali.gogol.net.cn/Article/details/gtvnugcqps.html

SELECT * FROM (
来源：http://dali.yj20258.top/Article/details/gtombsdvgj.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.tian-w.cn/Article/details/gtgsqxjwxr.html

) t WHERE rn = 1;
来源：http://dali.jyoumei.cn/Article/details/gtaelnsyoe.html

[Q35] 内连接
来源：http://dali.jqgufenzy.top/Article/details/gtdwzbtzoc.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.yangfankeji.com/Article/details/gtupmiwvhp.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gthxawhqap.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.yuxming.cn/Article/details/gtdjuegswn.html

[Q37] 右连接
来源：http://dali.nanxinkj.top/Article/details/gttbntubfx.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.yuxming.cn/Article/details/gtpolupovf.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.xuanzx.com/Article/details/gtyrssyybu.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtksmjxeav.html

[Q39] 自连接（查上下级）
来源：http://dali.sweek.top/Article/details/gtqrsnzmgt.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.yangfankeji.com/Article/details/gtayhfjzyg.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.tian-w.cn/Article/details/gtvmduxrob.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.cucudq.cn/Article/details/gthbmutewa.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.shuidangran.top/Article/details/gtgqmannji.html

[Q41] 多表连接
来源：http://dali.jlsjyb.cn/Article/details/gtaegtvpye.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.shangyingyoupin.top/Article/details/gtavcywqzn.html

JOIN users u ON u.id = o.user_id
来源：http://dali.redwolf501.top/Article/details/gtpfdlsonm.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.c1oappe.top/Article/details/gteqqxoktm.html

[Q42] 连接条件附加过滤
来源：http://dali.ydzc1.top/Article/details/gtrrbppcsx.html

SELECT u.name, o.amount FROM users u
来源：http://dali.yj20258888.top/Article/details/gtwbghsqwj.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.nanxuanxn.top/Article/details/gtqbjygeok.html

[Q43] 标量子查询
来源：http://dali.shuidangran.top/Article/details/gtrauaooxp.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.yuanzhike.top/Article/details/gthijtscgc.html

[Q44] IN 子查询
来源：http://dali.dianchejie.cn/Article/details/gtghlwcpww.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zycfv.cn/Article/details/gtncrldiav.html

[Q45] EXISTS 判断存在
来源：http://dali.cdnleiting.top/Article/details/gthgvrkrth.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.ivvv.top/Article/details/gtizdaxikw.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.chenzaomai.com/Article/details/gtqkgwhgvz.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.cqqwz.cn/Article/details/gtpjjghwfr.html

[Q47] 与平均值比较
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuscvzmyh.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.haohaochexian.top/Article/details/gtrsegjvdn.html

[Q48] CTE 公用表表达式
来源：http://dali.316326.xyz/Article/details/gttdpllzzw.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.ivvv.top/Article/details/gtimahvics.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.gotoacloud.top/Article/details/gtsfmwzifa.html

[Q49] 更新单行
来源：http://dali.zhiwuduotai.top/Article/details/gtdlpxkfsb.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.iojbl.cn/Article/details/gtnjxgcper.html

[Q50] 批量更新
来源：http://dali.pycfn.com/Article/details/gtwxjqtilc.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.jiagoushi.top/Article/details/gtomgshnux.html

[Q51] 用子查询更新
来源：http://dali.yangfankeji.com/Article/details/gthdxsbpfp.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.guannengcc.top/Article/details/gtdnbecmpk.html

[Q52] 删除指定行
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxajwdaus.html

DELETE FROM users WHERE id = 10;
来源：http://dali.guannengcc.top/Article/details/gtxnlrzxoc.html

[Q53] 按条件删除
来源：http://dali.gogol.net.cn/Article/details/gtmdkmwabp.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.sweek.top/Article/details/gtktciuuif.html

[Q54] 清空表
来源：http://dali.0kj1m.cn/Article/details/gtquymxded.html

TRUNCATE TABLE logs;
来源：http://dali.hnqzz.top/Article/details/gtotebfkkz.html

[Q55] 排名（并列占位）
来源：http://dali.fzhhl.top/Article/details/gtpuzjqctw.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.cucudq.cn/Article/details/gtsxvvanqm.html

[Q56] 密集排名（并列不占位）
来源：http://dali.yongpay.top/Article/details/gtfgaaylnn.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqitkypgw.html

[Q57] 行号
来源：http://dali.jqgufenzy.top/Article/details/gtgazuysxu.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gtrsequftr.html

[Q58] 累计求和
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfpyxzrds.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.daria6918.cn/Article/details/gtjmwxtrny.html

[Q59] 分组内累计
来源：http://dali.bjfxy.top/Article/details/gtfxmxwgnd.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.tianlin.xyz/Article/details/gtytfefzar.html

[Q60] 取上一行 / 下一行
来源：http://dali.dashuyun.cn/Article/details/gtjoexzoit.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.shangyingyoupin.top/Article/details/gtssjmwurd.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.daria6918.cn/Article/details/gtcdcnnvbi.html

[Q61] 移动平均
来源：http://dali.ybcxt.top/Article/details/gtvdjptmdn.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.jqgfzy.top/Article/details/gtkpstfpzx.html

[Q62] 分组占比
来源：http://dali.yuanzhike.top/Article/details/gtquipwxlq.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.aizwys.cn/Article/details/gtxhatvezr.html

[Q63] 开启事务
来源：http://dali.guannengcc.top/Article/details/gthhmvdqnd.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.aibaodan.cn/Article/details/gtceobqmkk.html

[Q64] 提交事务
来源：http://dali.zhoulong.xyz/Article/details/gtyihvglhy.html

COMMIT;
来源：http://dali.pengpengdd.cyou/Article/details/gtmafycmqx.html

[Q65] 回滚事务
来源：http://dali.yongpay.top/Article/details/gtneqaqqaj.html

ROLLBACK;
来源：http://dali.cashguo.top/Article/details/gttksnasdo.html

[Q66] 行锁查询
来源：http://dali.shanyushiyangtech.top/Article/details/gtijasnpop.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.xinyue.icu/Article/details/gtcajrdhri.html

[Q67] 设置隔离级别
来源：http://dali.xinyue.icu/Article/details/gtqmjumhqm.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.aizwys.cn/Article/details/gtnbvktnkc.html

[Q68] 保存点
来源：http://dali.vqdsnc.cn/Article/details/gtrsegvgll.html

SAVEPOINT sp1;
来源：http://dali.yj20258.top/Article/details/gtvmqdqzkc.html

ROLLBACK TO sp1;
来源：http://dali.nanxuanxn.top/Article/details/gtdgdtjibb.html

[Q69] 查看执行计划
来源：http://dali.vqdsnc.cn/Article/details/gtaskwxdjl.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.xylfe.cn/Article/details/gtfbgjblcw.html

[Q70] 更新统计信息
来源：http://dali.xuanzx.com/Article/details/gtuaeixvdb.html

ANALYZE TABLE users;
来源：http://dali.cqqwz.cn/Article/details/gtmaypyxyf.html

[Q71] 查看建表语句
来源：http://dali.cheryme.top/Article/details/gtophpryjf.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.guowangkeji.top/Article/details/gtojumchju.html

[Q72] 查看索引
来源：http://dali.ybcxt.top/Article/details/gtjzvyqopi.html

SHOW INDEX FROM users;
来源：http://dali.hongshengwenyu.top/Article/details/gtiqblmzbj.html

[Q73] 查看表状态
来源：http://dali.hnxiangtu.top/Article/details/gtwqlvhycv.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.pycfn.com/Article/details/gtxmzcnyib.html

[Q74] 强制使用索引
来源：http://dali.gaohongyu789.top/Article/details/gtjgnecllw.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.wangdashe.top/Article/details/gtqbxsqasd.html

[Q75] 日期格式化
来源：http://dali.bjfxy.top/Article/details/gtyirvftvm.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhengqikj.top/Article/details/gtdomvyspc.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.chenlongwang.top/Article/details/gtogysdihw.html

[Q76] 按天统计
来源：http://dali.shangyingyoupin.top/Article/details/gtleuuptns.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.dashuyun.cn/Article/details/gtaaiwcarf.html

[Q77] 时间加减
来源：http://dali.daxiang520.top/Article/details/gtilukddeh.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.bjfxy.top/Article/details/gtymvuueil.html

[Q78] 当前时间
来源：http://dali.jqgfzy.top/Article/details/gtnkunxwlk.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.yuanzhike.top/Article/details/gtedmnddmg.html

[Q79] 字符串拼接
来源：http://dali.shanyushiyangtech.top/Article/details/gtcucnknsl.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.jqgfzy.top/Article/details/gtytdzxmjv.html

[Q80] 字符串截取
来源：http://dali.fzhhl.top/Article/details/gtwhaoealv.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.tian-w.cn/Article/details/gtxmoziqme.html

[Q81] 字符串替换
来源：http://dali.gogol.net.cn/Article/details/gtdhgqfmpf.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhongyouzk.top/Article/details/gtssgutpdh.html

[Q82] 字符长度与字节长度
来源：http://dali.zhiwuduotai.top/Article/details/gtxsmlqdil.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.havefunace.top/Article/details/gtirnchtzm.html

[Q83] 大小写转换
来源：http://dali.hongshengwenyu.top/Article/details/gtdgjsxbxn.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.yuxming.cn/Article/details/gtljzmgghb.html

[Q84] 去除首尾空格
来源：http://dali.jinqigfzy.top/Article/details/gtbukbxlij.html

SELECT TRIM(name) FROM users;
来源：http://dali.ybcxt.top/Article/details/gtkykwizyo.html

[Q85] 数值取整
来源：http://dali.cashguo.top/Article/details/gtdfhprool.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.tanke756.top/Article/details/gtstcyexfz.html

[Q86] 读取 JSON 字段
来源：http://dali.hongshengwenyu.top/Article/details/gtfvdmwwsk.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.aibaodan.cn/Article/details/gtzyesngjy.html

[Q87] JSON 字段做条件
来源：http://dali.chenlongwang.top/Article/details/gtpnqmgbwb.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.yj202588.top/Article/details/gtniinjbfr.html

[Q88] 行转列（条件聚合）
来源：http://dali.ppjwa.cn/Article/details/gtufslhsqp.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.yangfankeji.com/Article/details/gtptmzgcwb.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.xylfe.cn/Article/details/gtpwyifzhw.html

[Q89] 判断表是否存在
来源：http://dali.daxiang520.top/Article/details/gtzjphnahl.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.0kj1m.cn/Article/details/gtbvldaclg.html

[Q90] 生成序号列
来源：http://dali.jyoumei.cn/Article/details/gtwhhffjvz.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.daria6918.cn/Article/details/gtkzmrpcco.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtmsdyteow.html

R. Bash 专题
来源：http://dali.ybcxt.top/Article/details/gtstkzlvqo.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtdmgvybop.html

[R01] shebang 与严格模式
来源：http://dali.hywenlv.cn/Article/details/gtnksxqcyk.html

#!/usr/bin/env bash
来源：http://dali.9152youxi.cn/Article/details/gtmqgtdjkf.html

set -euo pipefail
来源：http://dali.jinqigufen.top/Article/details/gtmzhbbxmg.html

[R02] 变量赋值与使用
来源：http://dali.xuetiantiany.cn/Article/details/gtxueacyif.html

name="Tom"; echo "$name"
来源：http://dali.guannengcc.top/Article/details/gtibrgyyso.html

[R03] 只读变量
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdghsvhro.html

readonly PI=3.14
来源：http://dali.nwbrower.top/Article/details/gttgzkbdyj.html

[R04] 位置参数
来源：http://dali.jlsjyb.cn/Article/details/gtarfnzpcn.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.yj20258888.top/Article/details/gtfsksplbu.html

[R05] 参数默认值
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjpbiwkoh.html

name="${1:-default}"
来源：http://dali.hfpthk.cn/Article/details/gtflpffxxa.html

[R06] 判断命令是否存在
来源：http://dali.bjfxy.top/Article/details/gtoqwokmxq.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.jiagoushi.top/Article/details/gtzpppwoqh.html

[R07] if 判断文件
来源：http://dali.daxiang520.top/Article/details/gtyiercudr.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.9152youxi.cn/Article/details/gtbazvcnef.html

[R08] 数值比较
来源：http://dali.shangyingyoupin.top/Article/details/gtvottrygv.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.yonumen.top/Article/details/gtbccgziyd.html

[R09] 字符串比较
来源：http://dali.ybcxt.top/Article/details/gtiwdsotjx.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.ywan-chungtsiang.top/Article/details/gtelqurqzi.html

[R10] 正则匹配
来源：http://dali.gaohongyu789.top/Article/details/gtzbkddusy.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.ivvv.top/Article/details/gtkeipihvw.html

[R11] case 多分支
来源：http://dali.wangshuangyany.cn/Article/details/gtbvwjhoov.html

case "$1" in
来源：http://dali.mhx1999.top/Article/details/gtzeqoexkv.html

start) echo "启动" ;;
来源：http://dali.fengsongda.top/Article/details/gtxapvcghq.html

stop)  echo "停止" ;;
来源：http://dali.jyoumei.cn/Article/details/gtvesximik.html

*)     echo "未知命令" ;;
来源：http://dali.shangyingyoupin.top/Article/details/gtvdvlqhot.html

esac
来源：http://dali.tian-w.cn/Article/details/gtmqstcsrr.html

[R12] for 遍历文件
来源：http://dali.bjfxy.top/Article/details/gtceolfcyn.html

for f in *.txt; do echo "$f"; done
来源：http://dali.jqgfzy.top/Article/details/gtiqkgatwe.html

[R13] for 计数循环
来源：http://dali.jinqigfzy.top/Article/details/gtvuvldxqc.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.hongshengwenyu.top/Article/details/gtgkgmsrfp.html

[R14] C 风格 for
来源：http://dali.hfpthk.cn/Article/details/gtcqvhdmgf.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhiwuduotai.top/Article/details/gtfghozaih.html

[R15] while 逐行读文件
来源：http://dali.sweek.top/Article/details/gttfpbrbqt.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.tianlin.xyz/Article/details/gtwxsigsoa.html

[R16] until 等待条件
来源：http://dali.andypj.xyz/Article/details/gtiiidgwgl.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.cashguo.top/Article/details/gtaspgdugr.html

[R17] 数组定义与取值
来源：http://dali.snrcjt.cn/Article/details/gtdibugaft.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.cashguo.top/Article/details/gtimsvkepc.html

[R18] 遍历数组
来源：http://dali.gaohongyu789.top/Article/details/gtlnpjwuul.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.jiagoushi.top/Article/details/gtrhwirnkx.html

[R19] 数组长度
来源：http://dali.cucudq.cn/Article/details/gtwhkompep.html

echo "${#arr[@]}"
来源：http://dali.hnqzz.top/Article/details/gtgebbzyla.html

[R20] 关联数组（字典）
来源：http://dali.c1oappe.top/Article/details/gttdguotxr.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.cucudq.cn/Article/details/gtdgtxacfs.html

[R21] 字符串长度
来源：http://dali.zhengqikj.top/Article/details/gtmodwlbvi.html

echo "${#s}"
来源：http://dali.shuidangran.top/Article/details/gturgsqpru.html

[R22] 截取子串
来源：http://dali.dianchejie.cn/Article/details/gtsmapwhtm.html

echo "${s:0:5}"
来源：http://dali.wangdashe.top/Article/details/gtrvsoczor.html

[R23] 字符串替换
来源：http://dali.jinqigufen.top/Article/details/gttvswqfei.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.yvedp.cn/Article/details/gtdnfhihaj.html

[R24] 大小写转换
来源：http://dali.yangfankeji.com/Article/details/gtgvrbpmsq.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzgldveiu.html

[R25] 去后缀 / 去前缀
来源：http://dali.jyoumei.cn/Article/details/gtpwgfkmrt.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.daria6918.cn/Article/details/gtjzkqeser.html

[R26] 命令替换
来源：http://dali.chenlongwang.top/Article/details/gtllftvdcu.html

now=$(date +%F); echo "$now"
来源：http://dali.jyoumei.cn/Article/details/gtjuqciofn.html

[R27] 算术展开
来源：http://dali.jqgfzy.top/Article/details/gtwlxpvclv.html

echo $((1 + 2 * 3))
来源：http://dali.0kj1m.cn/Article/details/gtwiugeukp.html

[R28] 浮点运算
来源：http://dali.yvedp.cn/Article/details/gtmzzthsze.html

echo "scale=2; 10/3" | bc
来源：http://dali.gogol.net.cn/Article/details/gtdwlsyqew.html

[R29] 定义函数
来源：http://dali.tanke756.top/Article/details/gtqghdpzwr.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.aizwys.cn/Article/details/gtxglsjwsi.html

[R30] 函数返回状态码
来源：http://dali.tian-w.cn/Article/details/gtyfcxoiuv.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.ivvv.top/Article/details/gtcwzrdvzx.html

[R31] 局部变量
来源：http://dali.cucudq.cn/Article/details/gthznenexa.html

f() { local x=1; echo "$x"; }
来源：http://dali.tianlin.xyz/Article/details/gtozwkbupj.html

[R32] 参数个数校验
来源：http://dali.shanyushiyangkeji.top/Article/details/gthqwfaccv.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhoulong.xyz/Article/details/gthylwqsvx.html

[R33] 捕获错误并提示行号
来源：http://dali.dashuyun.cn/Article/details/gtzgcgjhxj.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.yuxming.cn/Article/details/gthbdpryvb.html

[R34] 退出时清理
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxsaawbwo.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.snrcjt.cn/Article/details/gtonwdrmrh.html

[R35] 后台执行并等待
来源：http://dali.316326.xyz/Article/details/gtwjooimqd.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.sufxvd.cn/Article/details/gtmbxuvkhj.html

[R36] 并发执行多个任务
来源：http://dali.tian-w.cn/Article/details/gtnaiqsixb.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.pycfn.com/Article/details/gtfgvfkipc.html

[R37] 把输出赋给变量
来源：http://dali.xinyue.icu/Article/details/gtlpahoqib.html

files=$(ls -1)
来源：http://dali.xinyue.icu/Article/details/gtccswksih.html

[R38] 管道串联
来源：http://dali.cdnleiting.top/Article/details/gttcoaiurf.html

cat a.txt | grep -i error | wc -l
来源：http://dali.fengsongda.top/Article/details/gtieplycfr.html

[R39] 重定向标准输出与错误
来源：http://dali.kuanghao11.cn/Article/details/gtnkljlfwp.html

cmd > out.log 2>&1
来源：http://dali.vqdsnc.cn/Article/details/gtdlitoivh.html

[R40] 追加写日志
来源：http://dali.gotoacloud.top/Article/details/gtnljfydtz.html

echo "log" >> out.log
来源：http://dali.havefunace.top/Article/details/gtuhbssubn.html

[R41] 丢弃输出
来源：http://dali.kuanghao11.cn/Article/details/gthfhxnmqx.html

cmd >/dev/null 2>&1
来源：http://dali.chenlongwang.top/Article/details/gtywkfhumt.html

[R42] 输入重定向
来源：http://dali.ppjwa.cn/Article/details/gtosfmdcvo.html

wc -l < a.txt
来源：http://dali.yuxming.cn/Article/details/gttpusgvgd.html

[R43] 按名字查找文件
来源：http://dali.jinqigufen.top/Article/details/gtsjgynzyi.html

find . -name "*.log" -type f
来源：http://dali.iojbl.cn/Article/details/gtqkzvbmfn.html

[R44] 按修改时间查找
来源：http://dali.nanxuanxn.top/Article/details/gtxeoyyxvo.html

find . -mtime -7 -type f
来源：http://dali.feifeiyinyue.top/Article/details/gtssttjojz.html

[R45] 批量删除
来源：http://dali.9152youxi.cn/Article/details/gtckxtioux.html

find . -name "*.tmp" -delete
来源：http://dali.iojbl.cn/Article/details/gtvxfmjryx.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gteuhykast.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.fengsongda.top/Article/details/gtbhrkktul.html

[R47] sed 单行替换
来源：http://dali.ppjwa.cn/Article/details/gtbjuxnkkq.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.wangdashe.top/Article/details/gtifcfkaci.html

[R48] awk 取指定列
来源：http://dali.hnxiangtu.top/Article/details/gtatcmlpyr.html

awk '{print $1, $3}' a.txt
来源：http://dali.yanxiufei.cn/Article/details/gtglyvivjh.html

[R49] awk 带条件
来源：http://dali.yanxiufei.cn/Article/details/gtpkmagtxb.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.nwbrower.top/Article/details/gtrbqrhizj.html

[R50] awk 求和
来源：http://dali.tian-w.cn/Article/details/gtefpcxgcu.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.sufxvd.cn/Article/details/gtcosukdjq.html

[R51] 排序去重取前几
来源：http://dali.c1oappe.top/Article/details/gtnwsgkeca.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.feifeiyinyue.top/Article/details/gtgcwkdrsl.html

[R52] 统计行数
来源：http://dali.cqqwz.cn/Article/details/gtlbahfboj.html

wc -l a.txt
来源：http://dali.mhx1999.top/Article/details/gtuaptmlft.html

[R53] 查看文件头与实时尾
来源：http://dali.cashguo.top/Article/details/gtvlboabpb.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.sufxvd.cn/Article/details/gthljucruf.html

[R54] 比较两个文件
来源：http://dali.shangyingyoupin.top/Article/details/gtdgfwbrzx.html

diff a.txt b.txt
来源：http://dali.zhiwuduotai.top/Article/details/gtyilynyoc.html

[R55] 压缩与解压
来源：http://dali.nwbrower.top/Article/details/gtvbcewnkn.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.wangshuangyany.cn/Article/details/gtsiubdlev.html

[R56] 远程拷贝
来源：http://dali.redwolf501.top/Article/details/gtywseekmv.html

scp file user@host:/path/
来源：http://dali.mhx1999.top/Article/details/gttskzdczu.html

[R57] 远程执行命令
来源：http://dali.jqgfzy.top/Article/details/gtmxybgvqi.html

ssh user@host 'uptime'
来源：http://dali.iojbl.cn/Article/details/gtxheviomv.html

[R58] 下载文件
来源：http://dali.pengpengdd.cyou/Article/details/gttzknzcqj.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.yuxming.cn/Article/details/gtgkejdcqs.html

[R59] 发 POST JSON
来源：http://dali.sxryk.cn/Article/details/gtwhnxzisg.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.ehwqpu.com/Article/details/gtlhtabspl.html

[R60] 只看 HTTP 状态码
来源：http://dali.dianchejie.cn/Article/details/gtvsrludcr.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.yvedp.cn/Article/details/gtuxsuvdxx.html

[R61] 磁盘占用
来源：http://dali.quarkkingdee.top/Article/details/gtrictshjf.html

df -h;  du -sh *
来源：http://dali.yj20258888.top/Article/details/gtfnpiavce.html

[R62] 找最占空间的文件
来源：http://dali.jinghuilouyu.cn/Article/details/gtvajnjkwf.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gtlyxsqfvn.html

[R63] 内存与进程
来源：http://dali.jinghuilouyu.cn/Article/details/gtoeiwlnms.html

free -h;  ps aux | grep nginx
来源：http://dali.dashuyun.cn/Article/details/gtqpexrlgk.html

[R64] 结束进程
来源：http://dali.shzxlz.cn/Article/details/gtehkzgqjx.html

kill -9 $(pgrep -f app.py)
来源：http://dali.hammf.cn/Article/details/gtqfulfswe.html

[R65] 查看端口占用
来源：http://dali.pycfn.com/Article/details/gtkiiqslca.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.quarkkingdee.top/Article/details/gtykqgwtzl.html

[R66] 定时任务
来源：http://dali.xuanzx.com/Article/details/gtxwbuapqs.html

crontab -e;  crontab -l
来源：http://dali.jinqigufen.top/Article/details/gttoemqabo.html

[R67] 生成随机十六进制串
来源：http://dali.gaohongyu789.top/Article/details/gtkqdtksru.html

openssl rand -hex 16
来源：http://dali.gogol.net.cn/Article/details/gtwvuoupcy.html

[R68] 计算文件校验值
来源：http://dali.wangdashe.top/Article/details/gtjanwuakw.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.fzhhl.top/Article/details/gttqbdpmnt.html

[R69] 生成随机密码
来源：http://dali.hnxiangtu.top/Article/details/gtnndwbirb.html

head -c 16 /dev/urandom | base64
来源：http://dali.cdnleiting.top/Article/details/gtbhpjraiy.html

[R70] 时间戳与互转
来源：http://dali.zhongyouzk.top/Article/details/gtczhkehlf.html

date +%s;  date -d @1700000000
来源：http://dali.jinghuilouyu.cn/Article/details/gtdhhmekau.html

[R71] 日期格式化
来源：http://dali.yj20258888.top/Article/details/gtttlihlbf.html


<!-- 参考信息 -->