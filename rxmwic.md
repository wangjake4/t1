代发 wailian999

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.smart0.xyz/Article/details/gttvgdpbvu.html

[Q32] 分组拼接字符串
来源：http://dali.jyoumei.cn/Article/details/gtctrzianm.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhoulong.xyz/Article/details/gtsqnartaj.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhengqikj.top/Article/details/gtxkfjinta.html

[Q33] 多列分组
来源：http://dali.quarkkingdee.top/Article/details/gtpzsmimca.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.gogol.net.cn/Article/details/gtpterlnfp.html

[Q34] 每组取第一条
来源：http://dali.zycfv.cn/Article/details/gtrlxxihsr.html

SELECT * FROM (
来源：http://dali.ppjwa.cn/Article/details/gtphjakxlq.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.smart0.xyz/Article/details/gtzsyhlpph.html

) t WHERE rn = 1;
来源：http://dali.xylfe.cn/Article/details/gtrlahlbkd.html

[Q35] 内连接
来源：http://dali.jqgufenzy.top/Article/details/gtujfuiwbk.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.fengsongda.top/Article/details/gthsqidofj.html

[Q36] 左连接
来源：http://dali.xuetiantiany.cn/Article/details/gttdpkdpgj.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.nwbrower.top/Article/details/gtomnrulax.html

[Q37] 右连接
来源：http://dali.xuanzx.com/Article/details/gtlrgjygki.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.cdnleiting.top/Article/details/gtguymkusv.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.cashguo.top/Article/details/gtoegycxds.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhongyouzk.top/Article/details/gtkdsgclme.html

[Q39] 自连接（查上下级）
来源：http://dali.mhx1999.top/Article/details/gthvffhdht.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.yuanzhike.top/Article/details/gtijznvjik.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.hongshengwenyu.top/Article/details/gtrdfibbdt.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.aibaodan.cn/Article/details/gtejarqpfo.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.havefunace.top/Article/details/gtsfkbzvqs.html

[Q41] 多表连接
来源：http://dali.smart0.xyz/Article/details/gtxizcnxpl.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.gzhubu.top/Article/details/gtgexwgsyy.html

JOIN users u ON u.id = o.user_id
来源：http://dali.andypj.xyz/Article/details/gtxqttlafo.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.yj202588.top/Article/details/gtasavqije.html

[Q42] 连接条件附加过滤
来源：http://dali.xylfe.cn/Article/details/gtmkfkuaow.html

SELECT u.name, o.amount FROM users u
来源：http://dali.jinqigufen.top/Article/details/gtbitqovvo.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.haohaochexian.top/Article/details/gtjghstghv.html

[Q43] 标量子查询
来源：http://dali.dashuyun.cn/Article/details/gtppvytupt.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.jinqigfzy.top/Article/details/gtfxkgjpnx.html

[Q44] IN 子查询
来源：http://dali.gaohongyu789.top/Article/details/gtwnhqbhjr.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.shzxlz.cn/Article/details/gtviagqgll.html

[Q45] EXISTS 判断存在
来源：http://dali.xuetiantiany.cn/Article/details/gtbbjbmbqn.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.nwbrower.top/Article/details/gtueipzetx.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhongyouzk.top/Article/details/gtssfrckvv.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.nanxinkj.top/Article/details/gthlgplerp.html

[Q47] 与平均值比较
来源：http://dali.iojbl.cn/Article/details/gtqchdjcgj.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.shangyingyoupin.top/Article/details/gtmxsodfoj.html

[Q48] CTE 公用表表达式
来源：http://dali.daxiang520.top/Article/details/gttjaurout.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.haohaochexian.top/Article/details/gtflovaeed.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.mhx1999.top/Article/details/gtqlhbkctt.html

[Q49] 更新单行
来源：http://dali.ehwqpu.com/Article/details/gtgufzjzwk.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.xinyue.icu/Article/details/gtiwjfwylw.html

[Q50] 批量更新
来源：http://dali.feifeiyinyue.top/Article/details/gtvnkwwshs.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.pengpengdd.cyou/Article/details/gtpypfttuo.html

[Q51] 用子查询更新
来源：http://dali.zhixingplan.top/Article/details/gtjtuxevly.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.xinyue.icu/Article/details/gthdrurtnq.html

[Q52] 删除指定行
来源：http://dali.bjfxy.top/Article/details/gtlsrkiqkv.html

DELETE FROM users WHERE id = 10;
来源：http://dali.yvedp.cn/Article/details/gtdrfudxft.html

[Q53] 按条件删除
来源：http://dali.yanxiufei.cn/Article/details/gtjvquvmjn.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.cucudq.cn/Article/details/gtlfgknuyd.html

[Q54] 清空表
来源：http://dali.birdmap.top/Article/details/gtgelhnfuo.html

TRUNCATE TABLE logs;
来源：http://dali.jlsjyb.cn/Article/details/gtsfmzeqkg.html

[Q55] 排名（并列占位）
来源：http://dali.yongpay.top/Article/details/gtjklhnanp.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.mhx1999.top/Article/details/gtodduqmtd.html

[Q56] 密集排名（并列不占位）
来源：http://dali.shangyingyoupin.top/Article/details/gtveieqvkj.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.nwbrower.top/Article/details/gtuwkzpgyf.html

[Q57] 行号
来源：http://dali.jinqigfzy.top/Article/details/gtclsqqiud.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.tianlin.xyz/Article/details/gthgnfqrta.html

[Q58] 累计求和
来源：http://dali.ybcxt.top/Article/details/gtapbpjtmj.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.hammf.cn/Article/details/gtynlrxfkz.html

[Q59] 分组内累计
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxsatlqdm.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.fengsongda.top/Article/details/gtsjiirykn.html

[Q60] 取上一行 / 下一行
来源：http://dali.9152youxi.cn/Article/details/gtygqymawj.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.fengsongda.top/Article/details/gttkddcwig.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.cdnleiting.top/Article/details/gtatrpgslu.html

[Q61] 移动平均
来源：http://dali.yj20258.top/Article/details/gtluxcskkz.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.yj202588.top/Article/details/gtzvuwvyzq.html

[Q62] 分组占比
来源：http://dali.shangyingyoupin.top/Article/details/gtbtliadgd.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.9152youxi.cn/Article/details/gtxiyzongz.html

[Q63] 开启事务
来源：http://dali.kuanghao11.cn/Article/details/gthkihiqpl.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gtnsweipci.html

[Q64] 提交事务
来源：http://dali.mhx1999.top/Article/details/gtnihavrqu.html

COMMIT;
来源：http://dali.yvedp.cn/Article/details/gtvgusyhcs.html

[Q65] 回滚事务
来源：http://dali.yj202588.top/Article/details/gtotmhhulm.html

ROLLBACK;
来源：http://dali.zycfv.cn/Article/details/gtzjphyyrx.html

[Q66] 行锁查询
来源：http://dali.aizwys.cn/Article/details/gtplbqdgiw.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.guannengcc.top/Article/details/gtynklfutg.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gtwsnhrlel.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.xziqi.cn/Article/details/gtirrwpngj.html

[Q68] 保存点
来源：http://dali.aibaodan.cn/Article/details/gtwxixjdul.html

SAVEPOINT sp1;
来源：http://dali.9152youxi.cn/Article/details/gtgrsifihp.html

ROLLBACK TO sp1;
来源：http://dali.meibo888.top/Article/details/gtyrrxuaob.html

[Q69] 查看执行计划
来源：http://dali.hfpthk.cn/Article/details/gtbwiuvhxl.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.xuanzx.com/Article/details/gtcvwiorff.html

[Q70] 更新统计信息
来源：http://dali.hnxiangtu.top/Article/details/gtpnhzrpii.html

ANALYZE TABLE users;
来源：http://dali.gotoacloud.top/Article/details/gtxcxxtxls.html

[Q71] 查看建表语句
来源：http://dali.yangfankeji.com/Article/details/gtuhcrkqsj.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.feifeiyinyue.top/Article/details/gtctzubrpo.html

[Q72] 查看索引
来源：http://dali.9152youxi.cn/Article/details/gtzuatesuz.html

SHOW INDEX FROM users;
来源：http://dali.chenlongwang.top/Article/details/gtbjqkjfse.html

[Q73] 查看表状态
来源：http://dali.gaohongyu789.top/Article/details/gttfbbwaza.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhongyouzk.top/Article/details/gtakeehqbj.html

[Q74] 强制使用索引
来源：http://dali.havefunace.top/Article/details/gtiwnvyclc.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.cheryme.top/Article/details/gtpzywzsgm.html

[Q75] 日期格式化
来源：http://dali.zhaomingkeji.xyz/Article/details/gthrleyuhr.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhixingplan.top/Article/details/gtpkcudamc.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.redwolf501.top/Article/details/gtjmrlxfax.html

[Q76] 按天统计
来源：http://dali.hysaishi.cn/Article/details/gtcvbxfnux.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.guowangkeji.top/Article/details/gtqflumgtq.html

[Q77] 时间加减
来源：http://dali.kuanghao11.cn/Article/details/gtoilpmwdr.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.vqdsnc.cn/Article/details/gtsfstvook.html

[Q78] 当前时间
来源：http://dali.zhiwuduotai.top/Article/details/gtzxhiqicj.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.cqqwz.cn/Article/details/gtxymshpys.html

[Q79] 字符串拼接
来源：http://dali.zhengqikj.top/Article/details/gtovvntrmv.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.daria6918.cn/Article/details/gtblxjlohb.html

[Q80] 字符串截取
来源：http://dali.zycfv.cn/Article/details/gtvirsiyyk.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.ehwqpu.com/Article/details/gtetfopnru.html

[Q81] 字符串替换
来源：http://dali.smart0.xyz/Article/details/gtdwgcovet.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.yuanzhike.top/Article/details/gttqpnpxkp.html

[Q82] 字符长度与字节长度
来源：http://dali.yvedp.cn/Article/details/gtsfsvpszi.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gtjrgsehnl.html

[Q83] 大小写转换
来源：http://dali.xylfe.cn/Article/details/gtewjdjgyw.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhixingplan.top/Article/details/gtpnmkjhnw.html

[Q84] 去除首尾空格
来源：http://dali.svipenyu.cn/Article/details/gtltjcwbfc.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhixingplan.top/Article/details/gtdfouzxde.html

[Q85] 数值取整
来源：http://dali.sufxvd.cn/Article/details/gtvykdezlx.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhongyouzk.top/Article/details/gtqtwfjgki.html

[Q86] 读取 JSON 字段
来源：http://dali.jqgfzy.top/Article/details/gtjexglpjs.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.quarkkingdee.top/Article/details/gtzdmbsedf.html

[Q87] JSON 字段做条件
来源：http://dali.hnxiangtu.top/Article/details/gtuslofzkg.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.wangshuangyany.cn/Article/details/gtqnuexohz.html

[Q88] 行转列（条件聚合）
来源：http://dali.xuanzx.com/Article/details/gtyhalggom.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.cashguo.top/Article/details/gtbqsurgln.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.wangdashe.top/Article/details/gtdvrvveth.html

[Q89] 判断表是否存在
来源：http://dali.xylfe.cn/Article/details/gtjintjzla.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.jianghu66.top/Article/details/gtmnycxqdy.html

[Q90] 生成序号列
来源：http://dali.zhoulong.xyz/Article/details/gtduxzyqhe.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.0kj1m.cn/Article/details/gtyganpvsb.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtthzuznbo.html

R. Bash 专题
来源：http://dali.gaohongyu789.top/Article/details/gtcxraqltp.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtdddanirx.html

[R01] shebang 与严格模式
来源：http://dali.sweek.top/Article/details/gtcctpdpdu.html

#!/usr/bin/env bash
来源：http://dali.yonumen.top/Article/details/gtfnfyyirq.html

set -euo pipefail
来源：http://dali.daria6918.cn/Article/details/gthjstksea.html

[R02] 变量赋值与使用
来源：http://dali.jianghu66.top/Article/details/gtvygmigts.html

name="Tom"; echo "$name"
来源：http://dali.jiagoushi.top/Article/details/gtoypqognn.html

[R03] 只读变量
来源：http://dali.iojbl.cn/Article/details/gtettuaehf.html

readonly PI=3.14
来源：http://dali.jqgfzy.top/Article/details/gtilxvrvhy.html

[R04] 位置参数
来源：http://dali.zhixingplan.top/Article/details/gtbxuxfrqv.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.tanke756.top/Article/details/gtpqiktfyt.html

[R05] 参数默认值
来源：http://dali.zycfv.cn/Article/details/gtjwlqfjhh.html

name="${1:-default}"
来源：http://dali.svipenyu.cn/Article/details/gtjygfwsui.html

[R06] 判断命令是否存在
来源：http://dali.yuxming.cn/Article/details/gtlxjwiksi.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.xylfe.cn/Article/details/gtqzqbbmnb.html

[R07] if 判断文件
来源：http://dali.vqdsnc.cn/Article/details/gttkatagji.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.guannengcc.top/Article/details/gtmlournii.html

[R08] 数值比较
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkpkgciuk.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.haohaochexian.top/Article/details/gtdnkchzzj.html

[R09] 字符串比较
来源：http://dali.yj20258888.top/Article/details/gtwaztdhrk.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.jinqigufen.top/Article/details/gtmmngpisp.html

[R10] 正则匹配
来源：http://dali.gzhubu.top/Article/details/gtngvltjdx.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.gogol.net.cn/Article/details/gtvuefpgsq.html

[R11] case 多分支
来源：http://dali.mhx1999.top/Article/details/gtjuqjzadg.html

case "$1" in
来源：http://dali.svipenyu.cn/Article/details/gtnpaoxrrd.html

start) echo "启动" ;;
来源：http://dali.chenzaomai.com/Article/details/gtsuaolfbb.html

stop)  echo "停止" ;;
来源：http://dali.hysaishi.cn/Article/details/gtuxakrojf.html

*)     echo "未知命令" ;;
来源：http://dali.yj20258.top/Article/details/gtxeuzjzlj.html

esac
来源：http://dali.sxryk.cn/Article/details/gtugzmijva.html

[R12] for 遍历文件
来源：http://dali.hysaishi.cn/Article/details/gtyqryosle.html

for f in *.txt; do echo "$f"; done
来源：http://dali.tian-w.cn/Article/details/gtauxvtgfu.html

[R13] for 计数循环
来源：http://dali.9152youxi.cn/Article/details/gtopqywsci.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.hammf.cn/Article/details/gtlnuucjpd.html

[R14] C 风格 for
来源：http://dali.9152youxi.cn/Article/details/gtaamdgoyt.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.pycfn.com/Article/details/gtlqevunhj.html

[R15] while 逐行读文件
来源：http://dali.hfpthk.cn/Article/details/gtikujumbn.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.yangfankeji.com/Article/details/gtcksosmcf.html

[R16] until 等待条件
来源：http://dali.havefunace.top/Article/details/gtsdcpucju.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.sxryk.cn/Article/details/gtoyhtlaxp.html

[R17] 数组定义与取值
来源：http://dali.tian-w.cn/Article/details/gtssibncgs.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.nanxinkj.top/Article/details/gtcqvyoket.html

[R18] 遍历数组
来源：http://dali.tian-w.cn/Article/details/gtovpfwqxv.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.xuetiantiany.cn/Article/details/gtaxipptrv.html

[R19] 数组长度
来源：http://dali.smart0.xyz/Article/details/gtrmhqzgmu.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gterttvxgo.html

[R20] 关联数组（字典）
来源：http://dali.dashuyun.cn/Article/details/gtjuapsqur.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.xuetiantiany.cn/Article/details/gtodtrivlk.html

[R21] 字符串长度
来源：http://dali.fzhhl.top/Article/details/gtcvvlczok.html

echo "${#s}"
来源：http://dali.zhixingplan.top/Article/details/gteyndbduq.html

[R22] 截取子串
来源：http://dali.xziqi.cn/Article/details/gtneubhash.html

echo "${s:0:5}"
来源：http://dali.svipenyu.cn/Article/details/gtjkwmvkjv.html

[R23] 字符串替换
来源：http://dali.yvedp.cn/Article/details/gtkixpzvzu.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.316326.xyz/Article/details/gtohhqazyc.html

[R24] 大小写转换
来源：http://dali.yanxiufei.cn/Article/details/gtdnbxelio.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.smart0.xyz/Article/details/gtxbulfqcy.html

[R25] 去后缀 / 去前缀
来源：http://dali.xziqi.cn/Article/details/gtnopaubpw.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.hfpthk.cn/Article/details/gtpjmpqlef.html

[R26] 命令替换
来源：http://dali.yonumen.top/Article/details/gtexriqdbr.html

now=$(date +%F); echo "$now"
来源：http://dali.fzhhl.top/Article/details/gtfacstmao.html

[R27] 算术展开
来源：http://dali.wangshuangyany.cn/Article/details/gtuxcspdbs.html

echo $((1 + 2 * 3))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnhobomcp.html

[R28] 浮点运算
来源：http://dali.hongshengwenyu.top/Article/details/gtpcpvsqwl.html

echo "scale=2; 10/3" | bc
来源：http://dali.gotoacloud.top/Article/details/gtxpkzvfun.html

[R29] 定义函数
来源：http://dali.yongpay.top/Article/details/gtjnyxlpsf.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.tianlin.xyz/Article/details/gthhsimghr.html

[R30] 函数返回状态码
来源：http://dali.0kj1m.cn/Article/details/gthucchslq.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.ivvv.top/Article/details/gtkofmswkw.html

[R31] 局部变量
来源：http://dali.guannengcc.top/Article/details/gtczjtgafc.html

f() { local x=1; echo "$x"; }
来源：http://dali.yuanzhike.top/Article/details/gtymvmhemx.html

[R32] 参数个数校验
来源：http://dali.wangdashe.top/Article/details/gtzdhidrja.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.jiagoushi.top/Article/details/gttofmrfdl.html

[R33] 捕获错误并提示行号
来源：http://dali.chenlongwang.top/Article/details/gteoiktaqd.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.chenlongwang.top/Article/details/gtjizqdhcc.html

[R34] 退出时清理
来源：http://dali.havefunace.top/Article/details/gtkpgwrpvb.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.shzxlz.cn/Article/details/gtmbmbrmqr.html

[R35] 后台执行并等待
来源：http://dali.hongshengwenyu.top/Article/details/gtmffndnff.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.cheryme.top/Article/details/gtntqabfmb.html

[R36] 并发执行多个任务
来源：http://dali.chenzaomai.com/Article/details/gtbwndexhl.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.chenjidiqi.icu/Article/details/gtltfzatpo.html

[R37] 把输出赋给变量
来源：http://dali.zhongyouzk.top/Article/details/gtjkowlxau.html

files=$(ls -1)
来源：http://dali.hongshengwenyu.top/Article/details/gtzffqchui.html

[R38] 管道串联
来源：http://dali.kuanghao11.cn/Article/details/gtjjkqitan.html

cat a.txt | grep -i error | wc -l
来源：http://dali.birdmap.top/Article/details/gtundlsgem.html

[R39] 重定向标准输出与错误
来源：http://dali.guowangkeji.top/Article/details/gtayaceium.html

cmd > out.log 2>&1
来源：http://dali.sweek.top/Article/details/gtnovevjmg.html

[R40] 追加写日志
来源：http://dali.snrcjt.cn/Article/details/gtatmyzdte.html

echo "log" >> out.log
来源：http://dali.hnxiangtu.top/Article/details/gtfkciztyy.html

[R41] 丢弃输出
来源：http://dali.xylfe.cn/Article/details/gthezkegad.html

cmd >/dev/null 2>&1
来源：http://dali.pengpengdd.cyou/Article/details/gthnrncgng.html

[R42] 输入重定向
来源：http://dali.yuxming.cn/Article/details/gthtincdim.html

wc -l < a.txt
来源：http://dali.jinqigufen.top/Article/details/gtnigpwaqc.html

[R43] 按名字查找文件
来源：http://dali.c1oappe.top/Article/details/gthgvmglxv.html

find . -name "*.log" -type f
来源：http://dali.nanxuanxn.top/Article/details/gttarfwaih.html

[R44] 按修改时间查找
来源：http://dali.nwbrower.top/Article/details/gtlhajhghv.html

find . -mtime -7 -type f
来源：http://dali.chenjidiqi.icu/Article/details/gtbosluxty.html

[R45] 批量删除
来源：http://dali.hfpthk.cn/Article/details/gtyfwycwje.html

find . -name "*.tmp" -delete
来源：http://dali.andypj.xyz/Article/details/gtlduwzcvp.html

[R46] 递归替换文件内容
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtarduusop.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.meibo888.top/Article/details/gtsqgndcab.html

[R47] sed 单行替换
来源：http://dali.tian-w.cn/Article/details/gthymedjls.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.tanke756.top/Article/details/gtneneevkz.html

[R48] awk 取指定列
来源：http://dali.tianlin.xyz/Article/details/gtmpvqqqvc.html

awk '{print $1, $3}' a.txt
来源：http://dali.kuanghao11.cn/Article/details/gtapkcjvtt.html

[R49] awk 带条件
来源：http://dali.zhoulong.xyz/Article/details/gtxugujnni.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.xuetiantiany.cn/Article/details/gtirqfaqly.html

[R50] awk 求和
来源：http://dali.ppjwa.cn/Article/details/gthwmkkywy.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.pengpengdd.cyou/Article/details/gtpsbxmalx.html

[R51] 排序去重取前几
来源：http://dali.nanxinkj.top/Article/details/gtgrymjhap.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.pengpengdd.cyou/Article/details/gtmytuknzj.html

[R52] 统计行数
来源：http://dali.zhixingplan.top/Article/details/gtffqbboxn.html

wc -l a.txt
来源：http://dali.yangfankeji.com/Article/details/gtpjvtcsxr.html

[R53] 查看文件头与实时尾
来源：http://dali.yj20258.top/Article/details/gtvlmpwujm.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.gotoacloud.top/Article/details/gtmoechveh.html

[R54] 比较两个文件
来源：http://dali.c1oappe.top/Article/details/gtqranrgnb.html

diff a.txt b.txt
来源：http://dali.gogol.net.cn/Article/details/gtyoobicbd.html

[R55] 压缩与解压
来源：http://dali.kuanghao11.cn/Article/details/gtuoyjgeja.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.ppjwa.cn/Article/details/gtullenojb.html

[R56] 远程拷贝
来源：http://dali.quarkkingdee.top/Article/details/gtsgsxznpl.html

scp file user@host:/path/
来源：http://dali.shzxlz.cn/Article/details/gtxtjcwtmv.html

[R57] 远程执行命令
来源：http://dali.jinqigufen.top/Article/details/gtctdvyymo.html

ssh user@host 'uptime'
来源：http://dali.fengsongda.top/Article/details/gtxlbluqdj.html

[R58] 下载文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjziooshk.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.wangdashe.top/Article/details/gtmkambmaj.html

[R59] 发 POST JSON
来源：http://dali.cucudq.cn/Article/details/gtdxznwwdw.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.mhx1999.top/Article/details/gttqprhfgr.html

[R60] 只看 HTTP 状态码
来源：http://dali.vqdsnc.cn/Article/details/gtgwcczcdi.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.feifeiyinyue.top/Article/details/gtyjiuiacy.html

[R61] 磁盘占用
来源：http://dali.pengpengdd.cyou/Article/details/gtelpnmrck.html

df -h;  du -sh *
来源：http://dali.aizwys.cn/Article/details/gtnibavxuo.html

[R62] 找最占空间的文件
来源：http://dali.smart0.xyz/Article/details/gttmkzmpjo.html

du -ah . | sort -rh | head -10
来源：http://dali.redwolf501.top/Article/details/gtzceoezed.html

[R63] 内存与进程
来源：http://dali.wangshuangyany.cn/Article/details/gtspwetjta.html

free -h;  ps aux | grep nginx
来源：http://dali.hysaishi.cn/Article/details/gttaxyummh.html

[R64] 结束进程
来源：http://dali.daxiang520.top/Article/details/gtudtlryxz.html

kill -9 $(pgrep -f app.py)
来源：http://dali.shuidangran.top/Article/details/gtofwpbmbv.html

[R65] 查看端口占用
来源：http://dali.wangdashe.top/Article/details/gtrsvelfzk.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.guowangkeji.top/Article/details/gtyszzlbdf.html

[R66] 定时任务
来源：http://dali.aizwys.cn/Article/details/gtqrvpthcw.html

crontab -e;  crontab -l
来源：http://dali.jyoumei.cn/Article/details/gtrqpvhhqf.html

[R67] 生成随机十六进制串
来源：http://dali.cashguo.top/Article/details/gtxintnfsz.html

openssl rand -hex 16
来源：http://dali.fengsongda.top/Article/details/gtbrngzkrt.html

[R68] 计算文件校验值
来源：http://dali.sxryk.cn/Article/details/gthurhgsct.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.pengpengdd.cyou/Article/details/gtchwfinri.html

[R69] 生成随机密码
来源：http://dali.jqgufenzy.top/Article/details/gtgocagady.html

head -c 16 /dev/urandom | base64
来源：http://dali.ybcxt.top/Article/details/gtbaxufgiy.html

[R70] 时间戳与互转
来源：http://dali.daria6918.cn/Article/details/gtiuyscrbg.html

date +%s;  date -d @1700000000
来源：http://dali.hongshengwenyu.top/Article/details/gtpeqdwezv.html

[R71] 日期格式化
来源：http://dali.xylfe.cn/Article/details/gtjnybgzqm.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.feifeiyinyue.top/Article/details/gtoiegacdz.html

[R72] 等待端口就绪
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqxmoezuv.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.jqgufenzy.top/Article/details/gthtrwnngh.html

[R73] 分割大日志
来源：http://dali.iojbl.cn/Article/details/gtlqxhaflb.html

split -l 1000 big.log part_
来源：http://dali.shanyushiyangkeji.top/Article/details/gtinolyxcr.html

[R74] 批量重命名
来源：http://dali.shuidangran.top/Article/details/gtjcwfxqne.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.andypj.xyz/Article/details/gtinygkrcp.html

[R75] 导出环境变量
来源：http://dali.xuanzx.com/Article/details/gtckixdobm.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.ppjwa.cn/Article/details/gtdpzyaxtw.html

[R76] 使用临时文件
来源：http://dali.nanxuanxn.top/Article/details/gtxtdfaxiy.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.tian-w.cn/Article/details/gtyxymsztf.html

[R77] 读取用户输入
来源：http://dali.yuanzhike.top/Article/details/gthbmnzsbc.html

read -rp "请输入: " ans
来源：http://dali.ehwqpu.com/Article/details/gtcehkmexf.html

[R78] 交互式菜单
来源：http://dali.snrcjt.cn/Article/details/gtrjkfjhkr.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.quarkkingdee.top/Article/details/gtaqibzxzs.html

[R79] 解析命令行选项
来源：http://dali.pengpengdd.cyou/Article/details/gtqjwiunjz.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.hfpthk.cn/Article/details/gtskddrmpn.html

[R80] 查看脚本执行耗时
来源：http://dali.cucudq.cn/Article/details/gtyomsrpqw.html

time ./run.sh
来源：http://dali.hfpthk.cn/Article/details/gtxvapkyio.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtrfdzkmdk.html


<!-- 参考信息 -->