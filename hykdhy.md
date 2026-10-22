代发 wailian999

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.daxiang520.top/Article/details/gtbivaorsu.html

[Q28] 求和与平均
来源：http://dali.shzxlz.cn/Article/details/gtyjbyzvnf.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.cdnleiting.top/Article/details/gtninshpmc.html

[Q29] 最大最小值
来源：http://dali.daxiang520.top/Article/details/gtaghevglm.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.cashguo.top/Article/details/gtrkjdpxoc.html

[Q30] 分组统计
来源：http://dali.cdnleiting.top/Article/details/gtjnqghdte.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.shanyushiyangtech.top/Article/details/gteuaksbwg.html

[Q31] 分组后过滤
来源：http://dali.ydzc1.top/Article/details/gtsvwpovcc.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.shzxlz.cn/Article/details/gtubjejzcb.html

[Q32] 分组拼接字符串
来源：http://dali.vqdsnc.cn/Article/details/gtjmegnexu.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.hywenlv.cn/Article/details/gtnqhzmfgj.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.gaohongyu789.top/Article/details/gtvcuuzsxi.html

[Q33] 多列分组
来源：http://dali.cashguo.top/Article/details/gtjloeefpd.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.tian-w.cn/Article/details/gtqjzzincc.html

[Q34] 每组取第一条
来源：http://dali.zycfv.cn/Article/details/gtmomhppvd.html

SELECT * FROM (
来源：http://dali.wangshuangyany.cn/Article/details/gtsuxatezz.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.jinqigufen.top/Article/details/gtgvqfmhha.html

) t WHERE rn = 1;
来源：http://dali.cheryme.top/Article/details/gtpwqellvt.html

[Q35] 内连接
来源：http://dali.jinghuilouyu.cn/Article/details/gtfngumjde.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.cucudq.cn/Article/details/gttojijuos.html

[Q36] 左连接
来源：http://dali.smart0.xyz/Article/details/gtrgifkaqc.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.hnxiangtu.top/Article/details/gtkrmkfnyo.html

[Q37] 右连接
来源：http://dali.jianghu66.top/Article/details/gteqmjrrip.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.redwolf501.top/Article/details/gtpezotypl.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.gzhubu.top/Article/details/gtmwfopyfr.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.nanxinkj.top/Article/details/gtzjhrvcil.html

[Q39] 自连接（查上下级）
来源：http://dali.jinqigfzy.top/Article/details/gtwhhagtlg.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.kuanghao11.cn/Article/details/gtvmfgmxvf.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.andypj.xyz/Article/details/gtaptgyzob.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.sysykeji.top/Article/details/gtjhnzzqtd.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.yj20258.top/Article/details/gtbrdwskyz.html

[Q41] 多表连接
来源：http://dali.haohaochexian.top/Article/details/gtswndzcku.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zycfv.cn/Article/details/gtdvapitgo.html

JOIN users u ON u.id = o.user_id
来源：http://dali.316326.xyz/Article/details/gtflfwqfqi.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.sufxvd.cn/Article/details/gtyaxtwtrv.html

[Q42] 连接条件附加过滤
来源：http://dali.hywenlv.cn/Article/details/gtzptqdmvk.html

SELECT u.name, o.amount FROM users u
来源：http://dali.yuanzhike.top/Article/details/gtfgalrwdj.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.yuxming.cn/Article/details/gtpxfznwcn.html

[Q43] 标量子查询
来源：http://dali.ydzc1.top/Article/details/gteiutjwuo.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.nanxinkj.top/Article/details/gtitccmmam.html

[Q44] IN 子查询
来源：http://dali.gotoacloud.top/Article/details/gtkujxaslv.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.hammf.cn/Article/details/gtmxdteann.html

[Q45] EXISTS 判断存在
来源：http://dali.yuanzhike.top/Article/details/gtlqswscnx.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jyoumei.cn/Article/details/gtyamkmstb.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.jqgufenzy.top/Article/details/gtlhsagirn.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yvedp.cn/Article/details/gtfyuaeplo.html

[Q47] 与平均值比较
来源：http://dali.hysaishi.cn/Article/details/gtjmadyveg.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.jianghu66.top/Article/details/gtnwobalsx.html

[Q48] CTE 公用表表达式
来源：http://dali.tian-w.cn/Article/details/gtsnqjxoxj.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.jinqigfzy.top/Article/details/gtabyaukwm.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.tanke756.top/Article/details/gtfvcfswxd.html

[Q49] 更新单行
来源：http://dali.hongshengwenyu.top/Article/details/gtayrmkcey.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.cdnleiting.top/Article/details/gtgklantgs.html

[Q50] 批量更新
来源：http://dali.hnxiangtu.top/Article/details/gtubdkynqv.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.jinghuilouyu.cn/Article/details/gtkiuktdhj.html

[Q51] 用子查询更新
来源：http://dali.yj20258888.top/Article/details/gtlwmbjdnd.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.jinqigfzy.top/Article/details/gtlfbckvls.html

[Q52] 删除指定行
来源：http://dali.jyoumei.cn/Article/details/gttjatbyyr.html

DELETE FROM users WHERE id = 10;
来源：http://dali.shuidangran.top/Article/details/gtqvlgsugi.html

[Q53] 按条件删除
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoapsnafv.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.shangyingyoupin.top/Article/details/gtbjhmpztv.html

[Q54] 清空表
来源：http://dali.sxryk.cn/Article/details/gtsxejhgpv.html

TRUNCATE TABLE logs;
来源：http://dali.redwolf501.top/Article/details/gtzpwkwncj.html

[Q55] 排名（并列占位）
来源：http://dali.xuanzx.com/Article/details/gtykxojkww.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.aibaodan.cn/Article/details/gtvhdbfmdl.html

[Q56] 密集排名（并列不占位）
来源：http://dali.wangdashe.top/Article/details/gtbfnqtcuw.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.shuidangran.top/Article/details/gtfufuxldg.html

[Q57] 行号
来源：http://dali.yangfankeji.com/Article/details/gtgnsszjop.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.ybcxt.top/Article/details/gttmrrhdck.html

[Q58] 累计求和
来源：http://dali.chenlongwang.top/Article/details/gtwolhuvta.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.havefunace.top/Article/details/gtkmnvqwzz.html

[Q59] 分组内累计
来源：http://dali.ydzc1.top/Article/details/gttvuhochx.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.fzhhl.top/Article/details/gtwhooufqz.html

[Q60] 取上一行 / 下一行
来源：http://dali.yongpay.top/Article/details/gtdfgfykjf.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhengqikj.top/Article/details/gtyznrdwcf.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.snrcjt.cn/Article/details/gtehngqkgt.html

[Q61] 移动平均
来源：http://dali.jianghu66.top/Article/details/gtlykizkaf.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.jiagoushi.top/Article/details/gtjwbyzchj.html

[Q62] 分组占比
来源：http://dali.cucudq.cn/Article/details/gtyvwjayki.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.shanyushiyangtech.top/Article/details/gtqlepiwqm.html

[Q63] 开启事务
来源：http://dali.hammf.cn/Article/details/gtoznnkrwt.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.wangdashe.top/Article/details/gtvhafcabx.html

[Q64] 提交事务
来源：http://dali.jqgfzy.top/Article/details/gtfdrygvdg.html

COMMIT;
来源：http://dali.feifeiyinyue.top/Article/details/gtpphpqohh.html

[Q65] 回滚事务
来源：http://dali.c1oappe.top/Article/details/gtlsjvgkze.html

ROLLBACK;
来源：http://dali.0kj1m.cn/Article/details/gttvhyinsv.html

[Q66] 行锁查询
来源：http://dali.hnxiangtu.top/Article/details/gtlxpskcqj.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.jlsjyb.cn/Article/details/gtxsmesfum.html

[Q67] 设置隔离级别
来源：http://dali.zhaomingkeji.xyz/Article/details/gthlavygei.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.nwbrower.top/Article/details/gtrszpbnkc.html

[Q68] 保存点
来源：http://dali.yj20258.top/Article/details/gtnccjvtid.html

SAVEPOINT sp1;
来源：http://dali.zhixingplan.top/Article/details/gtkdppxiwy.html

ROLLBACK TO sp1;
来源：http://dali.kuanghao11.cn/Article/details/gtulwuybuj.html

[Q69] 查看执行计划
来源：http://dali.hysaishi.cn/Article/details/gtusmfkqiu.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.hfpthk.cn/Article/details/gtsfdlftrq.html

[Q70] 更新统计信息
来源：http://dali.hongshengwenyu.top/Article/details/gtcgtgrpey.html

ANALYZE TABLE users;
来源：http://dali.sweek.top/Article/details/gtbwijhdcw.html

[Q71] 查看建表语句
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmaksaams.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.mhx1999.top/Article/details/gtsluiizmr.html

[Q72] 查看索引
来源：http://dali.daxiang520.top/Article/details/gtlqbektlg.html

SHOW INDEX FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gtgtsunfdv.html

[Q73] 查看表状态
来源：http://dali.jianghu66.top/Article/details/gtsdjvjifw.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.tanke756.top/Article/details/gtqienodsb.html

[Q74] 强制使用索引
来源：http://dali.jinqigufen.top/Article/details/gtegesscqo.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.snrcjt.cn/Article/details/gtbemsqtnx.html

[Q75] 日期格式化
来源：http://dali.cqqwz.cn/Article/details/gtwdkijnza.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhixingplan.top/Article/details/gtbqzzhymb.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.yuanzhike.top/Article/details/gtfgmgyygl.html

[Q76] 按天统计
来源：http://dali.bjfxy.top/Article/details/gtgqnvaeeq.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.shuidangran.top/Article/details/gtophtyfmw.html

[Q77] 时间加减
来源：http://dali.zhoulong.xyz/Article/details/gtpyfvlgwn.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhengqikj.top/Article/details/gtcyfhoeyf.html

[Q78] 当前时间
来源：http://dali.quarkkingdee.top/Article/details/gtlegrfpro.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.gotoacloud.top/Article/details/gtgqaqgaeo.html

[Q79] 字符串拼接
来源：http://dali.wangdashe.top/Article/details/gtuwvbzyoz.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.xuanzx.com/Article/details/gtukhyogam.html

[Q80] 字符串截取
来源：http://dali.shanyushiyangtech.top/Article/details/gtaprcgbut.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtieusvmwr.html

[Q81] 字符串替换
来源：http://dali.jinghuilouyu.cn/Article/details/gtzdkmlcoj.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.yvedp.cn/Article/details/gtuwpqjufj.html

[Q82] 字符长度与字节长度
来源：http://dali.xuetiantiany.cn/Article/details/gtcvaogxwf.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gthofksisq.html

[Q83] 大小写转换
来源：http://dali.jinqigfzy.top/Article/details/gtewphvshz.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.chenzaomai.com/Article/details/gtabhcjgsk.html

[Q84] 去除首尾空格
来源：http://dali.yuanzhike.top/Article/details/gtljianqgb.html

SELECT TRIM(name) FROM users;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqyastovl.html

[Q85] 数值取整
来源：http://dali.kuanghao11.cn/Article/details/gtnpnowuej.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.jyoumei.cn/Article/details/gtrxzilxuf.html

[Q86] 读取 JSON 字段
来源：http://dali.yongpay.top/Article/details/gtjkvqznzy.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.fzhhl.top/Article/details/gtznlgvgew.html

[Q87] JSON 字段做条件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvsxbiikp.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.chenzaomai.com/Article/details/gtpiwuujwk.html

[Q88] 行转列（条件聚合）
来源：http://dali.ppjwa.cn/Article/details/gtcirjplet.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.316326.xyz/Article/details/gttjtxnopn.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.gogol.net.cn/Article/details/gtvwhkwqth.html

[Q89] 判断表是否存在
来源：http://dali.ivvv.top/Article/details/gtiddsmpqd.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.shanyushiyangkeji.top/Article/details/gtukhsvvhk.html

[Q90] 生成序号列
来源：http://dali.jinqigfzy.top/Article/details/gthztnfeji.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.sweek.top/Article/details/gtezzrfkkx.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtsfembjaf.html

R. Bash 专题
来源：http://dali.ivvv.top/Article/details/gtsahkrrwe.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnivpwzrs.html

[R01] shebang 与严格模式
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgvpfdnem.html

#!/usr/bin/env bash
来源：http://dali.guowangkeji.top/Article/details/gtlvocryrq.html

set -euo pipefail
来源：http://dali.guannengcc.top/Article/details/gtqbxxkfzq.html

[R02] 变量赋值与使用
来源：http://dali.smart0.xyz/Article/details/gtatscuqho.html

name="Tom"; echo "$name"
来源：http://dali.jqgfzy.top/Article/details/gtapgibula.html

[R03] 只读变量
来源：http://dali.sweek.top/Article/details/gtuvwiotku.html

readonly PI=3.14
来源：http://dali.chenjidiqi.icu/Article/details/gtccqbbrio.html

[R04] 位置参数
来源：http://dali.zdqjudy.top/Article/details/gtdvtdesei.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.tianlin.xyz/Article/details/gtiflmfhdd.html

[R05] 参数默认值
来源：http://dali.yonumen.top/Article/details/gthrqswiti.html

name="${1:-default}"
来源：http://dali.nwbrower.top/Article/details/gtqnwbytjz.html

[R06] 判断命令是否存在
来源：http://dali.aibaodan.cn/Article/details/gtrcyygwpk.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.hywenlv.cn/Article/details/gtnlxfjyvy.html

[R07] if 判断文件
来源：http://dali.ppjwa.cn/Article/details/gtbnwtueha.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.chenjidiqi.icu/Article/details/gtvtudnlwx.html

[R08] 数值比较
来源：http://dali.xziqi.cn/Article/details/gtghdbyudx.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.hnxiangtu.top/Article/details/gtoaufgzhz.html

[R09] 字符串比较
来源：http://dali.xuanzx.com/Article/details/gtvnzelvth.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.shangyingyoupin.top/Article/details/gtzwuxrpkz.html

[R10] 正则匹配
来源：http://dali.bjfxy.top/Article/details/gtborxvsqb.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.yangfankeji.com/Article/details/gtldqusent.html

[R11] case 多分支
来源：http://dali.cashguo.top/Article/details/gtnokqrwra.html

case "$1" in
来源：http://dali.jianghu66.top/Article/details/gtpohhvofr.html

start) echo "启动" ;;
来源：http://dali.haohaochexian.top/Article/details/gtugojbxyh.html

stop)  echo "停止" ;;
来源：http://dali.yj202588.top/Article/details/gtphcgpddh.html

*)     echo "未知命令" ;;
来源：http://dali.zycfv.cn/Article/details/gtnympklrr.html

esac
来源：http://dali.nanxinkj.top/Article/details/gtmbaaxptu.html

[R12] for 遍历文件
来源：http://dali.jqgfzy.top/Article/details/gtyflroqef.html

for f in *.txt; do echo "$f"; done
来源：http://dali.hywenlv.cn/Article/details/gtqpltsnkw.html

[R13] for 计数循环
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvizxxgux.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.guannengcc.top/Article/details/gtvuvhypnc.html

[R14] C 风格 for
来源：http://dali.feifeiyinyue.top/Article/details/gtcuisxasz.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.aizwys.cn/Article/details/gtuijgfybc.html

[R15] while 逐行读文件
来源：http://dali.ybcxt.top/Article/details/gtxzynkjgk.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhoulong.xyz/Article/details/gthllyegyu.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gthqcbljmb.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.fengsongda.top/Article/details/gtnmlodelf.html

[R17] 数组定义与取值
来源：http://dali.daxiang520.top/Article/details/gtgqgizacy.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.xuanzx.com/Article/details/gtzjtomdab.html

[R18] 遍历数组
来源：http://dali.smart0.xyz/Article/details/gtfcecuwmy.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.xinyue.icu/Article/details/gtuvmhixnf.html

[R19] 数组长度
来源：http://dali.quarkkingdee.top/Article/details/gtnqplipkt.html

echo "${#arr[@]}"
来源：http://dali.jqgufenzy.top/Article/details/gtravxhqnf.html

[R20] 关联数组（字典）
来源：http://dali.gogol.net.cn/Article/details/gtupaifhqp.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.bjfxy.top/Article/details/gtfsclnhnw.html

[R21] 字符串长度
来源：http://dali.yvedp.cn/Article/details/gtyrsfhrlg.html

echo "${#s}"
来源：http://dali.9152youxi.cn/Article/details/gtoaivvdfu.html

[R22] 截取子串
来源：http://dali.svipenyu.cn/Article/details/gtrscpmyfe.html

echo "${s:0:5}"
来源：http://dali.jianghu66.top/Article/details/gtgferdugz.html

[R23] 字符串替换
来源：http://dali.yuanzhike.top/Article/details/gtzlsjppvo.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.sysykeji.top/Article/details/gtajlvxwxb.html

[R24] 大小写转换
来源：http://dali.birdmap.top/Article/details/gtbuyrbozi.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.hfpthk.cn/Article/details/gtbjvgtfza.html

[R25] 去后缀 / 去前缀
来源：http://dali.hnqzz.top/Article/details/gtsreixtgu.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.vqdsnc.cn/Article/details/gttaykjqir.html

[R26] 命令替换
来源：http://dali.xziqi.cn/Article/details/gtmljxsxex.html

now=$(date +%F); echo "$now"
来源：http://dali.feifeiyinyue.top/Article/details/gtvtlhswoj.html

[R27] 算术展开
来源：http://dali.quarkkingdee.top/Article/details/gtwrzoiiyk.html

echo $((1 + 2 * 3))
来源：http://dali.guowangkeji.top/Article/details/gtylmnaewy.html

[R28] 浮点运算
来源：http://dali.wangshuangyany.cn/Article/details/gtacipxvft.html

echo "scale=2; 10/3" | bc
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyzqnjggl.html

[R29] 定义函数
来源：http://dali.snrcjt.cn/Article/details/gtjmlrioob.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.9152youxi.cn/Article/details/gtxkbiufkx.html

[R30] 函数返回状态码
来源：http://dali.xuanzx.com/Article/details/gtjsoiihym.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.havefunace.top/Article/details/gtkqbaajsz.html

[R31] 局部变量
来源：http://dali.yanxiufei.cn/Article/details/gthelquiiu.html

f() { local x=1; echo "$x"; }
来源：http://dali.wangshuangyany.cn/Article/details/gtzmluwaza.html

[R32] 参数个数校验
来源：http://dali.zhongyouzk.top/Article/details/gthxjffbyh.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.xziqi.cn/Article/details/gtiqbkayzd.html

[R33] 捕获错误并提示行号
来源：http://dali.jinyuanbaomall.cn/Article/details/gthfpimeuj.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.jiagoushi.top/Article/details/gtglyrrlva.html

[R34] 退出时清理
来源：http://dali.ybcxt.top/Article/details/gtlskflbse.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.cucudq.cn/Article/details/gtdjowvytw.html

[R35] 后台执行并等待
来源：http://dali.feifeiyinyue.top/Article/details/gtfrvbhxvf.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.xinyue.icu/Article/details/gtvdzaeqvk.html

[R36] 并发执行多个任务
来源：http://dali.andypj.xyz/Article/details/gtqubtuhgh.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.jinqigfzy.top/Article/details/gtvyjrkxxg.html

[R37] 把输出赋给变量
来源：http://dali.jinqigfzy.top/Article/details/gtpfsqpuka.html

files=$(ls -1)
来源：http://dali.andypj.xyz/Article/details/gttmnqvkud.html

[R38] 管道串联
来源：http://dali.yanxiufei.cn/Article/details/gtsdlbczhd.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zycfv.cn/Article/details/gteifoeejn.html

[R39] 重定向标准输出与错误
来源：http://dali.gotoacloud.top/Article/details/gtqgxnjidl.html

cmd > out.log 2>&1
来源：http://dali.kuanghao11.cn/Article/details/gtgdukfmgd.html

[R40] 追加写日志
来源：http://dali.jqgfzy.top/Article/details/gtwscerjpt.html

echo "log" >> out.log
来源：http://dali.vqdsnc.cn/Article/details/gtrlcdhmhx.html

[R41] 丢弃输出
来源：http://dali.shzxlz.cn/Article/details/gtrpjsneeu.html

cmd >/dev/null 2>&1
来源：http://dali.nanxinkj.top/Article/details/gtesaluvti.html

[R42] 输入重定向
来源：http://dali.c1oappe.top/Article/details/gtoyoaxdal.html

wc -l < a.txt
来源：http://dali.daxiang520.top/Article/details/gtrchbmykp.html

[R43] 按名字查找文件
来源：http://dali.316326.xyz/Article/details/gtwnyculem.html

find . -name "*.log" -type f
来源：http://dali.yj202588.top/Article/details/gtxwcvhrom.html

[R44] 按修改时间查找
来源：http://dali.havefunace.top/Article/details/gtobtbzytd.html

find . -mtime -7 -type f
来源：http://dali.hnxiangtu.top/Article/details/gtuaxtouih.html

[R45] 批量删除
来源：http://dali.jinghuilouyu.cn/Article/details/gtozmwtpns.html

find . -name "*.tmp" -delete
来源：http://dali.zhengqikj.top/Article/details/gtspkmlldn.html

[R46] 递归替换文件内容
来源：http://dali.yj202588.top/Article/details/gtfimrlysl.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.tanke756.top/Article/details/gthxchjykx.html

[R47] sed 单行替换
来源：http://dali.shanyushiyangtech.top/Article/details/gtvrhjtwzx.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.dashuyun.cn/Article/details/gtmnztebui.html

[R48] awk 取指定列
来源：http://dali.jinqigfzy.top/Article/details/gtaeynklwu.html

awk '{print $1, $3}' a.txt
来源：http://dali.feifeiyinyue.top/Article/details/gtwehqkalv.html

[R49] awk 带条件
来源：http://dali.cqqwz.cn/Article/details/gtmuamepna.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxklcbeib.html

[R50] awk 求和
来源：http://dali.smart0.xyz/Article/details/gtvylznkhl.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.hammf.cn/Article/details/gtbinslytv.html

[R51] 排序去重取前几
来源：http://dali.wangdashe.top/Article/details/gtkdnopqra.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.dashuyun.cn/Article/details/gttxcxrigi.html

[R52] 统计行数
来源：http://dali.yj20258.top/Article/details/gtwyhzgdpl.html

wc -l a.txt
来源：http://dali.shzxlz.cn/Article/details/gtosmexrbh.html

[R53] 查看文件头与实时尾
来源：http://dali.pengpengdd.cyou/Article/details/gtcczpghep.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.nanxuanxn.top/Article/details/gtwgorqkfm.html

[R54] 比较两个文件
来源：http://dali.zycfv.cn/Article/details/gttvpjtxgt.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gtxvixcimi.html

[R55] 压缩与解压
来源：http://dali.guowangkeji.top/Article/details/gtwcxuxaly.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.jinqigufen.top/Article/details/gtyuonrwrb.html

[R56] 远程拷贝
来源：http://dali.chenlongwang.top/Article/details/gtkzfbrugo.html

scp file user@host:/path/
来源：http://dali.cheryme.top/Article/details/gtxdvrkgvf.html

[R57] 远程执行命令
来源：http://dali.bjfxy.top/Article/details/gthakeehah.html

ssh user@host 'uptime'
来源：http://dali.sxryk.cn/Article/details/gtgjokkjmk.html

[R58] 下载文件
来源：http://dali.hnqzz.top/Article/details/gtwvnjgdwz.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.havefunace.top/Article/details/gtiqxblnon.html

[R59] 发 POST JSON
来源：http://dali.xuanzx.com/Article/details/gttiiosmhf.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.jiagoushi.top/Article/details/gtfzcesqec.html

[R60] 只看 HTTP 状态码
来源：http://dali.zdqjudy.top/Article/details/gtkzftnyxo.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.cqqwz.cn/Article/details/gtsqdftfpu.html

[R61] 磁盘占用
来源：http://dali.redwolf501.top/Article/details/gtbgfkpmhq.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gtgsxwlrlm.html

[R62] 找最占空间的文件
来源：http://dali.quarkkingdee.top/Article/details/gtqwlqiwuo.html

du -ah . | sort -rh | head -10
来源：http://dali.jqgufenzy.top/Article/details/gthcfpmpyj.html

[R63] 内存与进程
来源：http://dali.kuanghao11.cn/Article/details/gtztpdtifk.html

free -h;  ps aux | grep nginx
来源：http://dali.kuanghao11.cn/Article/details/gtkowchgci.html

[R64] 结束进程
来源：http://dali.jqgfzy.top/Article/details/gtgozzbjka.html

kill -9 $(pgrep -f app.py)
来源：http://dali.jianghu66.top/Article/details/gtdehtebax.html

[R65] 查看端口占用
来源：http://dali.tanke756.top/Article/details/gtamgascun.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.ybcxt.top/Article/details/gtgqwymwhc.html

[R66] 定时任务
来源：http://dali.chenjidiqi.icu/Article/details/gteibmhxtc.html

crontab -e;  crontab -l
来源：http://dali.redwolf501.top/Article/details/gtoqwbriwh.html

[R67] 生成随机十六进制串
来源：http://dali.zycfv.cn/Article/details/gtgtienzcv.html

openssl rand -hex 16
来源：http://dali.chenjidiqi.icu/Article/details/gtsnrptnpp.html

[R68] 计算文件校验值
来源：http://dali.iojbl.cn/Article/details/gtohrlarwe.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.mhx1999.top/Article/details/gtyjbwftdr.html

[R69] 生成随机密码
来源：http://dali.cucudq.cn/Article/details/gtjaquwjhr.html

head -c 16 /dev/urandom | base64
来源：http://dali.cqqwz.cn/Article/details/gtyrvozuvo.html

[R70] 时间戳与互转
来源：http://dali.dianchejie.cn/Article/details/gtgrvxbntj.html

date +%s;  date -d @1700000000
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpensmxtn.html

[R71] 日期格式化
来源：http://dali.ydzc1.top/Article/details/gtdbtpdgre.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.wangdashe.top/Article/details/gtuzrdlwvp.html

[R72] 等待端口就绪
来源：http://dali.sxryk.cn/Article/details/gticjkeadq.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.dianchejie.cn/Article/details/gttmmzgypw.html

[R73] 分割大日志
来源：http://dali.quarkkingdee.top/Article/details/gtviphrxlx.html

split -l 1000 big.log part_
来源：http://dali.shzxlz.cn/Article/details/gtswspmpsv.html

[R74] 批量重命名
来源：http://dali.hysaishi.cn/Article/details/gtyibrvuxw.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.tianlin.xyz/Article/details/gtiesnueri.html

[R75] 导出环境变量
来源：http://dali.0kj1m.cn/Article/details/gtolhqbibo.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.hysaishi.cn/Article/details/gtfscmboza.html

[R76] 使用临时文件
来源：http://dali.wangshuangyany.cn/Article/details/gtuhexngwn.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.tian-w.cn/Article/details/gtjzpchloq.html

[R77] 读取用户输入
来源：http://dali.jyoumei.cn/Article/details/gtrvkfqvfa.html


<!-- 参考信息 -->