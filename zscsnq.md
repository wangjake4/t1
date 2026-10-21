代发 wailian999

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.chenjidiqi.icu/Article/details/gtjnydrzxo.html

[Q24] 去重
来源：http://dali.yuanzhike.top/Article/details/gtiikltcpy.html

SELECT DISTINCT city FROM users;
来源：http://dali.sxryk.cn/Article/details/gtzkqiytqi.html

[Q25] 只取前 N 条
来源：http://dali.dianchejie.cn/Article/details/gtttysyjdx.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.c1oappe.top/Article/details/gtwdqulkjq.html

[Q26] 计数
来源：http://dali.hnqzz.top/Article/details/gtneljsusr.html

SELECT COUNT(*) FROM users;
来源：http://dali.hnqzz.top/Article/details/gtgqfmsbgw.html

[Q27] 条件计数
来源：http://dali.tianlin.xyz/Article/details/gtozgrwmrp.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.svipenyu.cn/Article/details/gtymvrawwy.html

[Q28] 求和与平均
来源：http://dali.shangyingyoupin.top/Article/details/gtiuywqfmv.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.shangyingyoupin.top/Article/details/gtnpbzlalb.html

[Q29] 最大最小值
来源：http://dali.xuetiantiany.cn/Article/details/gtxysgkxvg.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gtmzvqagdd.html

[Q30] 分组统计
来源：http://dali.yanxiufei.cn/Article/details/gtiduleejz.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.tianlin.xyz/Article/details/gtfyrxjwdq.html

[Q31] 分组后过滤
来源：http://dali.pengpengdd.cyou/Article/details/gtltlhddzs.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.xylfe.cn/Article/details/gtozmslwvw.html

[Q32] 分组拼接字符串
来源：http://dali.c1oappe.top/Article/details/gtnmftlhje.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhoulong.xyz/Article/details/gtlmjjivkn.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhiwuduotai.top/Article/details/gtlhdkmxkf.html

[Q33] 多列分组
来源：http://dali.mhx1999.top/Article/details/gthrdksuyi.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.nanxinkj.top/Article/details/gtrsgswirs.html

[Q34] 每组取第一条
来源：http://dali.nanxuanxn.top/Article/details/gtgkcwpcsv.html

SELECT * FROM (
来源：http://dali.yvedp.cn/Article/details/gtgobydfku.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.tianlin.xyz/Article/details/gtyagtbjng.html

) t WHERE rn = 1;
来源：http://dali.birdmap.top/Article/details/gtltecicap.html

[Q35] 内连接
来源：http://dali.tian-w.cn/Article/details/gtyaqlvofd.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.jiagoushi.top/Article/details/gtdwtjjobw.html

[Q36] 左连接
来源：http://dali.shangyingyoupin.top/Article/details/gtegbitkxn.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.yueranfly.top/Article/details/gtoywfeklu.html

[Q37] 右连接
来源：http://dali.gotoacloud.top/Article/details/gtntqavkyo.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmkpezibx.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhoulong.xyz/Article/details/gtwgxxhwbe.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.hysaishi.cn/Article/details/gtzwatbhmg.html

[Q39] 自连接（查上下级）
来源：http://dali.bjfxy.top/Article/details/gtpgfjnbom.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.shanyushiyangtech.top/Article/details/gtfknrgetw.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.cashguo.top/Article/details/gtxzaewwxx.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.316326.xyz/Article/details/gtomjqoppe.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.xziqi.cn/Article/details/gthoferxcc.html

[Q41] 多表连接
来源：http://dali.zhoulong.xyz/Article/details/gtfhqpprsq.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.wangshuangyany.cn/Article/details/gtzvdslxsw.html

JOIN users u ON u.id = o.user_id
来源：http://dali.316326.xyz/Article/details/gtatkicyso.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.yj20258888.top/Article/details/gtaqrinjin.html

[Q42] 连接条件附加过滤
来源：http://dali.gzhubu.top/Article/details/gtwbqjuuzv.html

SELECT u.name, o.amount FROM users u
来源：http://dali.316326.xyz/Article/details/gtvuxlgmlu.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.xziqi.cn/Article/details/gtkubazynv.html

[Q43] 标量子查询
来源：http://dali.gotoacloud.top/Article/details/gtdsrheqcq.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtesiijdrm.html

[Q44] IN 子查询
来源：http://dali.zhengqikj.top/Article/details/gttaynexuu.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnkwdikcr.html

[Q45] EXISTS 判断存在
来源：http://dali.tanke756.top/Article/details/gteqrvkyga.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.gzhubu.top/Article/details/gtnlumefkn.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.chenlongwang.top/Article/details/gtqupwptrb.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.smart0.xyz/Article/details/gtkzuxflij.html

[Q47] 与平均值比较
来源：http://dali.iojbl.cn/Article/details/gtfglrlioe.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.nanxinkj.top/Article/details/gtjlehycbm.html

[Q48] CTE 公用表表达式
来源：http://dali.sysykeji.top/Article/details/gtegunpeej.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.xuetiantiany.cn/Article/details/gtppiayged.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.guowangkeji.top/Article/details/gtkohielnd.html

[Q49] 更新单行
来源：http://dali.shzxlz.cn/Article/details/gtqfhajgyt.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.nanxuanxn.top/Article/details/gtlevikbwb.html

[Q50] 批量更新
来源：http://dali.mhx1999.top/Article/details/gtvwmmybzb.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.kuanghao11.cn/Article/details/gtjdxnakgm.html

[Q51] 用子查询更新
来源：http://dali.cashguo.top/Article/details/gteditgbrj.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.pycfn.com/Article/details/gtnquxtriy.html

[Q52] 删除指定行
来源：http://dali.jlsjyb.cn/Article/details/gtkphejpnp.html

DELETE FROM users WHERE id = 10;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlpunzmlp.html

[Q53] 按条件删除
来源：http://dali.316326.xyz/Article/details/gtaotmmcdf.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.guowangkeji.top/Article/details/gtaqebxakm.html

[Q54] 清空表
来源：http://dali.redwolf501.top/Article/details/gtrvldedaq.html

TRUNCATE TABLE logs;
来源：http://dali.zdqjudy.top/Article/details/gtbhszvoik.html

[Q55] 排名（并列占位）
来源：http://dali.hfpthk.cn/Article/details/gtigedsfgo.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.shzxlz.cn/Article/details/gthmkdnwsr.html

[Q56] 密集排名（并列不占位）
来源：http://dali.gaohongyu789.top/Article/details/gtjqnlraml.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.yuxming.cn/Article/details/gtfdoeymps.html

[Q57] 行号
来源：http://dali.yvedp.cn/Article/details/gtwpxsfgos.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.guowangkeji.top/Article/details/gtylwkitbq.html

[Q58] 累计求和
来源：http://dali.yvedp.cn/Article/details/gtzkwhfdyz.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.shangyingyoupin.top/Article/details/gtlwouzzdd.html

[Q59] 分组内累计
来源：http://dali.cashguo.top/Article/details/gtmlekdylc.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.nwbrower.top/Article/details/gtdkaxiayb.html

[Q60] 取上一行 / 下一行
来源：http://dali.aibaodan.cn/Article/details/gttfjxjsuj.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.ppjwa.cn/Article/details/gttkztsfrc.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.ybcxt.top/Article/details/gtsmvzbkma.html

[Q61] 移动平均
来源：http://dali.fzhhl.top/Article/details/gtrybolngm.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zdqjudy.top/Article/details/gtdrpowbrd.html

[Q62] 分组占比
来源：http://dali.tanke756.top/Article/details/gtvajybdnn.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbssjtwov.html

[Q63] 开启事务
来源：http://dali.gotoacloud.top/Article/details/gtkphwpbcw.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.gogol.net.cn/Article/details/gtklexklrx.html

[Q64] 提交事务
来源：http://dali.zhoulong.xyz/Article/details/gtjcnxtlif.html

COMMIT;
来源：http://dali.cdnleiting.top/Article/details/gtwzrkkpnm.html

[Q65] 回滚事务
来源：http://dali.9152youxi.cn/Article/details/gtyboctfta.html

ROLLBACK;
来源：http://dali.guowangkeji.top/Article/details/gtwfxswxpo.html

[Q66] 行锁查询
来源：http://dali.gzhubu.top/Article/details/gtfpxnbfsb.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.c1oappe.top/Article/details/gtjouizzyk.html

[Q67] 设置隔离级别
来源：http://dali.cucudq.cn/Article/details/gtfzhxskst.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaejdotql.html

[Q68] 保存点
来源：http://dali.zhengqikj.top/Article/details/gtvnmrpaux.html

SAVEPOINT sp1;
来源：http://dali.shuidangran.top/Article/details/gtispixvsm.html

ROLLBACK TO sp1;
来源：http://dali.kuanghao11.cn/Article/details/gtlayjjlkx.html

[Q69] 查看执行计划
来源：http://dali.cheryme.top/Article/details/gtvsuumgfa.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gtlfkzxpko.html

[Q70] 更新统计信息
来源：http://dali.aibaodan.cn/Article/details/gtlyphvlhb.html

ANALYZE TABLE users;
来源：http://dali.zhixingplan.top/Article/details/gtrixysbak.html

[Q71] 查看建表语句
来源：http://dali.wangdashe.top/Article/details/gtrzltpzdt.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.hnxiangtu.top/Article/details/gtejmdjlps.html

[Q72] 查看索引
来源：http://dali.pengpengdd.cyou/Article/details/gtibiatitw.html

SHOW INDEX FROM users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjrqmfexa.html

[Q73] 查看表状态
来源：http://dali.jlsjyb.cn/Article/details/gtrsvxwpbg.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.cqqwz.cn/Article/details/gtuohainep.html

[Q74] 强制使用索引
来源：http://dali.zhongyouzk.top/Article/details/gtklyxppnf.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.xuanzx.com/Article/details/gtvxuyktio.html

[Q75] 日期格式化
来源：http://dali.chenjidiqi.icu/Article/details/gtngbdwkri.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.chenjidiqi.icu/Article/details/gtmjhoiltb.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.wangshuangyany.cn/Article/details/gtihllqkyq.html

[Q76] 按天统计
来源：http://dali.jqgfzy.top/Article/details/gtyjlharcn.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.yangfankeji.com/Article/details/gtylmcfnhj.html

[Q77] 时间加减
来源：http://dali.chenzaomai.com/Article/details/gtvigmegqd.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.bjfxy.top/Article/details/gtqazjpdzq.html

[Q78] 当前时间
来源：http://dali.jinghuilouyu.cn/Article/details/gtuporsrdd.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.c1oappe.top/Article/details/gtftwjbsmh.html

[Q79] 字符串拼接
来源：http://dali.havefunace.top/Article/details/gtmdxjrjwo.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.yueranfly.top/Article/details/gtkrnecaub.html

[Q80] 字符串截取
来源：http://dali.zycfv.cn/Article/details/gtkkpizaiw.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.xuanzx.com/Article/details/gtzsonakbt.html

[Q81] 字符串替换
来源：http://dali.chenlongwang.top/Article/details/gtjfcoqmww.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.yonumen.top/Article/details/gtnvokvdmq.html

[Q82] 字符长度与字节长度
来源：http://dali.daria6918.cn/Article/details/gtpevngipd.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.yj202588.top/Article/details/gtolwixexk.html

[Q83] 大小写转换
来源：http://dali.nanxuanxn.top/Article/details/gtzwiayedp.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gtdcszyfse.html

[Q84] 去除首尾空格
来源：http://dali.zycfv.cn/Article/details/gtbqffwcpt.html

SELECT TRIM(name) FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gtigaydlts.html

[Q85] 数值取整
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtukjgaabl.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.gogol.net.cn/Article/details/gtwlhtkrfs.html

[Q86] 读取 JSON 字段
来源：http://dali.yuanzhike.top/Article/details/gthkgpieae.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.hysaishi.cn/Article/details/gtuovheydr.html

[Q87] JSON 字段做条件
来源：http://dali.sweek.top/Article/details/gtwkjnpvza.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.smart0.xyz/Article/details/gtbdawryic.html

[Q88] 行转列（条件聚合）
来源：http://dali.hnqzz.top/Article/details/gtngoicoyk.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.cheryme.top/Article/details/gtlahikhsr.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.jianghu66.top/Article/details/gthgrztcgl.html

[Q89] 判断表是否存在
来源：http://dali.ppjwa.cn/Article/details/gtevceznvc.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.daria6918.cn/Article/details/gtqcvgsapv.html

[Q90] 生成序号列
来源：http://dali.jqgufenzy.top/Article/details/gthspmkkec.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.aibaodan.cn/Article/details/gtlgdnqutj.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtqqxzqirp.html

R. Bash 专题
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtntseheld.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtudgnoiwc.html

[R01] shebang 与严格模式
来源：http://dali.nwbrower.top/Article/details/gtisohinwu.html

#!/usr/bin/env bash
来源：http://dali.chenlongwang.top/Article/details/gtibpprvts.html

set -euo pipefail
来源：http://dali.ydzc1.top/Article/details/gtrnxytrpy.html

[R02] 变量赋值与使用
来源：http://dali.haohaochexian.top/Article/details/gtolhqchke.html

name="Tom"; echo "$name"
来源：http://dali.xuanzx.com/Article/details/gtrylmfmqy.html

[R03] 只读变量
来源：http://dali.havefunace.top/Article/details/gtyiptpzdr.html

readonly PI=3.14
来源：http://dali.ivvv.top/Article/details/gtxhdofasg.html

[R04] 位置参数
来源：http://dali.shanyushiyangtech.top/Article/details/gthkmpdxap.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.yonumen.top/Article/details/gtslhzxgkz.html

[R05] 参数默认值
来源：http://dali.zhongyouzk.top/Article/details/gtkxzwfvnj.html

name="${1:-default}"
来源：http://dali.hnxiangtu.top/Article/details/gtgiildmsw.html

[R06] 判断命令是否存在
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsalqjkuj.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.vqdsnc.cn/Article/details/gtgbaacypr.html

[R07] if 判断文件
来源：http://dali.zhoulong.xyz/Article/details/gtacbmxdor.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.xuanzx.com/Article/details/gtcakjdqjb.html

[R08] 数值比较
来源：http://dali.yj202588.top/Article/details/gtsdvgxoqw.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.yj20258.top/Article/details/gtqvufotle.html

[R09] 字符串比较
来源：http://dali.yongpay.top/Article/details/gtpcdasssy.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.c1oappe.top/Article/details/gttgtzdnjo.html

[R10] 正则匹配
来源：http://dali.sysykeji.top/Article/details/gtmglfkuwg.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.jyoumei.cn/Article/details/gtluqnxqvv.html

[R11] case 多分支
来源：http://dali.quarkkingdee.top/Article/details/gthyusrnkp.html

case "$1" in
来源：http://dali.sufxvd.cn/Article/details/gtxhvtdryt.html

start) echo "启动" ;;
来源：http://dali.nanxuanxn.top/Article/details/gtvarktmvn.html

stop)  echo "停止" ;;
来源：http://dali.guannengcc.top/Article/details/gtdaijfqvn.html

*)     echo "未知命令" ;;
来源：http://dali.shangyingyoupin.top/Article/details/gtkoctwszd.html

esac
来源：http://dali.yanxiufei.cn/Article/details/gtaykxcily.html

[R12] for 遍历文件
来源：http://dali.meibo888.top/Article/details/gtojtxzosj.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zdqjudy.top/Article/details/gtnicsjwup.html

[R13] for 计数循环
来源：http://dali.xinyue.icu/Article/details/gtwvudkuji.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.hongshengwenyu.top/Article/details/gtahshgjtj.html

[R14] C 风格 for
来源：http://dali.shangyingyoupin.top/Article/details/gtwjunuzns.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.nanxinkj.top/Article/details/gtfyhujbwp.html

[R15] while 逐行读文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjuyymbph.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.mhx1999.top/Article/details/gtwtievipi.html

[R16] until 等待条件
来源：http://dali.mhx1999.top/Article/details/gtjzeavgqr.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.gzhubu.top/Article/details/gtmlmynkye.html

[R17] 数组定义与取值
来源：http://dali.nwbrower.top/Article/details/gtggnnkijh.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.gaohongyu789.top/Article/details/gtakkqjxaj.html

[R18] 遍历数组
来源：http://dali.jinqigufen.top/Article/details/gtduotpfks.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.yanxiufei.cn/Article/details/gtsszessqw.html

[R19] 数组长度
来源：http://dali.aizwys.cn/Article/details/gtadydeiwd.html

echo "${#arr[@]}"
来源：http://dali.hywenlv.cn/Article/details/gtdsuvwixt.html

[R20] 关联数组（字典）
来源：http://dali.shzxlz.cn/Article/details/gtanmmapis.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.yuanzhike.top/Article/details/gtpooqlapl.html

[R21] 字符串长度
来源：http://dali.hammf.cn/Article/details/gtlqqnquks.html

echo "${#s}"
来源：http://dali.quarkkingdee.top/Article/details/gtpdlgvnxy.html

[R22] 截取子串
来源：http://dali.yuanzhike.top/Article/details/gtyrvrdogc.html

echo "${s:0:5}"
来源：http://dali.gaohongyu789.top/Article/details/gtfbatrtex.html

[R23] 字符串替换
来源：http://dali.xuetiantiany.cn/Article/details/gtllwfkybp.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.jinghuilouyu.cn/Article/details/gtxusgrjpb.html

[R24] 大小写转换
来源：http://dali.ppjwa.cn/Article/details/gtvuqbdkfu.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.yuxming.cn/Article/details/gtscnxrpnm.html

[R25] 去后缀 / 去前缀
来源：http://dali.jyoumei.cn/Article/details/gtkcffoapl.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.cdnleiting.top/Article/details/gtxnactrmz.html

[R26] 命令替换
来源：http://dali.zhixingplan.top/Article/details/gtmxnjtper.html

now=$(date +%F); echo "$now"
来源：http://dali.wangshuangyany.cn/Article/details/gteziglfib.html

[R27] 算术展开
来源：http://dali.c1oappe.top/Article/details/gtizdylicg.html

echo $((1 + 2 * 3))
来源：http://dali.yj202588.top/Article/details/gtfnnmbngo.html

[R28] 浮点运算
来源：http://dali.hongshengwenyu.top/Article/details/gtebquebym.html

echo "scale=2; 10/3" | bc
来源：http://dali.ivvv.top/Article/details/gtubczuclw.html

[R29] 定义函数
来源：http://dali.fzhhl.top/Article/details/gtznpvxzog.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.smart0.xyz/Article/details/gtizxtnopd.html

[R30] 函数返回状态码
来源：http://dali.snrcjt.cn/Article/details/gtzzpcujlt.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.svipenyu.cn/Article/details/gtoyhyheeq.html

[R31] 局部变量
来源：http://dali.c1oappe.top/Article/details/gtuffrfxvs.html

f() { local x=1; echo "$x"; }
来源：http://dali.svipenyu.cn/Article/details/gtutcmhyqf.html

[R32] 参数个数校验
来源：http://dali.chenzaomai.com/Article/details/gtikxjzpjf.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.sufxvd.cn/Article/details/gtycacdhqz.html

[R33] 捕获错误并提示行号
来源：http://dali.wangshuangyany.cn/Article/details/gtbjhggcuj.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.yj20258.top/Article/details/gtyjsnuwvw.html

[R34] 退出时清理
来源：http://dali.shuidangran.top/Article/details/gtjpljrgdx.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.redwolf501.top/Article/details/gtalmkoucw.html

[R35] 后台执行并等待
来源：http://dali.9152youxi.cn/Article/details/gtauyzhdma.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.daxiang520.top/Article/details/gtqgrttfsy.html

[R36] 并发执行多个任务
来源：http://dali.yueranfly.top/Article/details/gtyoqjlfxm.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.chenlongwang.top/Article/details/gtdfkfchuu.html

[R37] 把输出赋给变量
来源：http://dali.mhx1999.top/Article/details/gtvxezqkdf.html

files=$(ls -1)
来源：http://dali.snrcjt.cn/Article/details/gtgvrjizxp.html

[R38] 管道串联
来源：http://dali.hywenlv.cn/Article/details/gtghsvzuje.html

cat a.txt | grep -i error | wc -l
来源：http://dali.nanxuanxn.top/Article/details/gtsqepgjwn.html

[R39] 重定向标准输出与错误
来源：http://dali.jinghuilouyu.cn/Article/details/gtvtehiclp.html

cmd > out.log 2>&1
来源：http://dali.0kj1m.cn/Article/details/gtfslqhidn.html

[R40] 追加写日志
来源：http://dali.zhaomingkeji.xyz/Article/details/gtewplbigj.html

echo "log" >> out.log
来源：http://dali.meibo888.top/Article/details/gtnpyolfqo.html

[R41] 丢弃输出
来源：http://dali.yangfankeji.com/Article/details/gtdhajqeaq.html

cmd >/dev/null 2>&1
来源：http://dali.hnxiangtu.top/Article/details/gtapigssjx.html

[R42] 输入重定向
来源：http://dali.yongpay.top/Article/details/gtrucyarjj.html

wc -l < a.txt
来源：http://dali.pengpengdd.cyou/Article/details/gtlflhdnmf.html

[R43] 按名字查找文件
来源：http://dali.wangshuangyany.cn/Article/details/gtrnadbsaq.html

find . -name "*.log" -type f
来源：http://dali.hnxiangtu.top/Article/details/gttaghsjuk.html

[R44] 按修改时间查找
来源：http://dali.xuetiantiany.cn/Article/details/gtzhyhmofd.html

find . -mtime -7 -type f
来源：http://dali.hfpthk.cn/Article/details/gthahnsuln.html

[R45] 批量删除
来源：http://dali.cheryme.top/Article/details/gtpxlbvtza.html

find . -name "*.tmp" -delete
来源：http://dali.pengpengdd.cyou/Article/details/gtembxmtaq.html

[R46] 递归替换文件内容
来源：http://dali.xuetiantiany.cn/Article/details/gtzacwwpkn.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.ehwqpu.com/Article/details/gtztfnapgy.html

[R47] sed 单行替换
来源：http://dali.svipenyu.cn/Article/details/gtkoangxqu.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.ppjwa.cn/Article/details/gtfwpdakss.html

[R48] awk 取指定列
来源：http://dali.yangfankeji.com/Article/details/gtwnsywwxi.html

awk '{print $1, $3}' a.txt
来源：http://dali.dashuyun.cn/Article/details/gtyqfvrlqg.html

[R49] awk 带条件
来源：http://dali.guannengcc.top/Article/details/gtutffrihc.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.yvedp.cn/Article/details/gtqmoytcuc.html

[R50] awk 求和
来源：http://dali.gaohongyu789.top/Article/details/gtexlqvlih.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.andypj.xyz/Article/details/gtafplwgwv.html

[R51] 排序去重取前几
来源：http://dali.hammf.cn/Article/details/gtmpszfebo.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhixingplan.top/Article/details/gttodnphue.html

[R52] 统计行数
来源：http://dali.yuxming.cn/Article/details/gtxgdgfwmh.html

wc -l a.txt
来源：http://dali.jinqigfzy.top/Article/details/gtblckekpv.html

[R53] 查看文件头与实时尾
来源：http://dali.iojbl.cn/Article/details/gtkvbjpass.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.jqgufenzy.top/Article/details/gtzotqpirp.html

[R54] 比较两个文件
来源：http://dali.nwbrower.top/Article/details/gtubmjsauq.html

diff a.txt b.txt
来源：http://dali.sxryk.cn/Article/details/gtwakbykae.html

[R55] 压缩与解压
来源：http://dali.hywenlv.cn/Article/details/gtrkgvlxfy.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.jqgfzy.top/Article/details/gtnqpjbjcf.html

[R56] 远程拷贝
来源：http://dali.feifeiyinyue.top/Article/details/gtpcunjnfd.html

scp file user@host:/path/
来源：http://dali.guannengcc.top/Article/details/gtbdanpvly.html

[R57] 远程执行命令
来源：http://dali.iojbl.cn/Article/details/gtpquuhtzh.html

ssh user@host 'uptime'
来源：http://dali.xuanzx.com/Article/details/gtuwqqcjgs.html

[R58] 下载文件
来源：http://dali.meibo888.top/Article/details/gtaxjalukm.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.jlsjyb.cn/Article/details/gtmntkulza.html

[R59] 发 POST JSON
来源：http://dali.andypj.xyz/Article/details/gteumhwgcx.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.shanyushiyangtech.top/Article/details/gtyqxgttnl.html

[R60] 只看 HTTP 状态码
来源：http://dali.feifeiyinyue.top/Article/details/gtmwtzeova.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.cucudq.cn/Article/details/gtnxzwjrhy.html

[R61] 磁盘占用
来源：http://dali.tianlin.xyz/Article/details/gtmqawrqng.html

df -h;  du -sh *
来源：http://dali.9152youxi.cn/Article/details/gtknjxqrpt.html

[R62] 找最占空间的文件
来源：http://dali.hywenlv.cn/Article/details/gtukcdmwqr.html

du -ah . | sort -rh | head -10
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbvcuflpx.html

[R63] 内存与进程
来源：http://dali.ppjwa.cn/Article/details/gtvbvhgzzl.html

free -h;  ps aux | grep nginx
来源：http://dali.wangdashe.top/Article/details/gtnsqwnjha.html

[R64] 结束进程
来源：http://dali.tianlin.xyz/Article/details/gtutsabxnb.html

kill -9 $(pgrep -f app.py)
来源：http://dali.yongpay.top/Article/details/gtymyjkcff.html

[R65] 查看端口占用
来源：http://dali.ppjwa.cn/Article/details/gtrfftwbbb.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.sweek.top/Article/details/gtiftcecsg.html

[R66] 定时任务
来源：http://dali.ydzc1.top/Article/details/gtfmetuicx.html

crontab -e;  crontab -l
来源：http://dali.hongshengwenyu.top/Article/details/gtatahbmkf.html

[R67] 生成随机十六进制串
来源：http://dali.wangshuangyany.cn/Article/details/gtmmkqpiaz.html

openssl rand -hex 16
来源：http://dali.cucudq.cn/Article/details/gtvywhzije.html

[R68] 计算文件校验值
来源：http://dali.tanke756.top/Article/details/gtobvznhai.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.havefunace.top/Article/details/gtvqktnpyx.html

[R69] 生成随机密码
来源：http://dali.jinghuilouyu.cn/Article/details/gttzbkczub.html

head -c 16 /dev/urandom | base64
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvcbcwzfg.html

[R70] 时间戳与互转
来源：http://dali.fzhhl.top/Article/details/gtraspelvc.html

date +%s;  date -d @1700000000
来源：http://dali.shzxlz.cn/Article/details/gtggclyiqd.html

[R71] 日期格式化
来源：http://dali.zhengqikj.top/Article/details/gtrhochvlu.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.jiagoushi.top/Article/details/gtxdpulxtx.html

[R72] 等待端口就绪
来源：http://dali.316326.xyz/Article/details/gtkgljmrmf.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.hnxiangtu.top/Article/details/gtjfrgsrzw.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gtsghyixol.html


<!-- 参考信息 -->