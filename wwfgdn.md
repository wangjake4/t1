代发 wailian999

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.ydzc1.top/Article/details/gtklysmdci.html

[Q28] 求和与平均
来源：http://dali.shangyingyoupin.top/Article/details/gtcuizhfiz.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhiwuduotai.top/Article/details/gtdjqnevxf.html

[Q29] 最大最小值
来源：http://dali.ppjwa.cn/Article/details/gttbozbphe.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.yvedp.cn/Article/details/gthvlulswx.html

[Q30] 分组统计
来源：http://dali.yonumen.top/Article/details/gtwcvrovlf.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.cheryme.top/Article/details/gtxmxzkpwl.html

[Q31] 分组后过滤
来源：http://dali.shanyushiyangkeji.top/Article/details/gtihurcqns.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.cdnleiting.top/Article/details/gtcdehsndd.html

[Q32] 分组拼接字符串
来源：http://dali.birdmap.top/Article/details/gtepykrsei.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.yj202588.top/Article/details/gtbdoyfbmy.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.daria6918.cn/Article/details/gtbxijydkw.html

[Q33] 多列分组
来源：http://dali.tanke756.top/Article/details/gttumaqvet.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.cucudq.cn/Article/details/gtwbukepqn.html

[Q34] 每组取第一条
来源：http://dali.ppjwa.cn/Article/details/gtfqdgjcsd.html

SELECT * FROM (
来源：http://dali.yj20258888.top/Article/details/gtjlxcsmro.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.guannengcc.top/Article/details/gtqvoathaj.html

) t WHERE rn = 1;
来源：http://dali.andypj.xyz/Article/details/gtohfaguwu.html

[Q35] 内连接
来源：http://dali.daria6918.cn/Article/details/gtigcstzzs.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.andypj.xyz/Article/details/gtrargphxm.html

[Q36] 左连接
来源：http://dali.sysykeji.top/Article/details/gtvkscqqla.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.cucudq.cn/Article/details/gtkdvwhdhe.html

[Q37] 右连接
来源：http://dali.ybcxt.top/Article/details/gtvekfbhdv.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.yj20258888.top/Article/details/gtrchsypls.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.c1oappe.top/Article/details/gtfracfmnl.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.fengsongda.top/Article/details/gtpsmimwed.html

[Q39] 自连接（查上下级）
来源：http://dali.gaohongyu789.top/Article/details/gterqogmuf.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.vqdsnc.cn/Article/details/gtiwplomqm.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.hammf.cn/Article/details/gtluoxtygi.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.0kj1m.cn/Article/details/gtoxeqtwwy.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.jinqigufen.top/Article/details/gtrevtyozm.html

[Q41] 多表连接
来源：http://dali.pycfn.com/Article/details/gtsizlmwxp.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.hysaishi.cn/Article/details/gtydufqhcq.html

JOIN users u ON u.id = o.user_id
来源：http://dali.kuanghao11.cn/Article/details/gtxokvdarm.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.sufxvd.cn/Article/details/gtvcowbyrk.html

[Q42] 连接条件附加过滤
来源：http://dali.fzhhl.top/Article/details/gtvediulkg.html

SELECT u.name, o.amount FROM users u
来源：http://dali.jianghu66.top/Article/details/gtyrpaylya.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.shangyingyoupin.top/Article/details/gtszpytqsq.html

[Q43] 标量子查询
来源：http://dali.shanyushiyangtech.top/Article/details/gtfcyfayqg.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.xziqi.cn/Article/details/gttedhtqpi.html

[Q44] IN 子查询
来源：http://dali.zhixingplan.top/Article/details/gtwsbraidn.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.meibo888.top/Article/details/gtkhrxcpoo.html

[Q45] EXISTS 判断存在
来源：http://dali.hongshengwenyu.top/Article/details/gtjkindfwe.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.meibo888.top/Article/details/gtlxnpqanf.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.cdnleiting.top/Article/details/gtzldmruzu.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.0kj1m.cn/Article/details/gtijjtrlsh.html

[Q47] 与平均值比较
来源：http://dali.wangdashe.top/Article/details/gtpfdvrwri.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.tianlin.xyz/Article/details/gtdujzsawv.html

[Q48] CTE 公用表表达式
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqyxlpskn.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.ehwqpu.com/Article/details/gtinypqxnr.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.gogol.net.cn/Article/details/gtygsxiumz.html

[Q49] 更新单行
来源：http://dali.dianchejie.cn/Article/details/gtcklzoqyw.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.andypj.xyz/Article/details/gtciagrmie.html

[Q50] 批量更新
来源：http://dali.yvedp.cn/Article/details/gtrvymioye.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.xylfe.cn/Article/details/gtudvifnps.html

[Q51] 用子查询更新
来源：http://dali.c1oappe.top/Article/details/gtsaiqbjft.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gthujnkdlq.html

[Q52] 删除指定行
来源：http://dali.dashuyun.cn/Article/details/gteyzznjxs.html

DELETE FROM users WHERE id = 10;
来源：http://dali.yueranfly.top/Article/details/gtfplnxosy.html

[Q53] 按条件删除
来源：http://dali.guannengcc.top/Article/details/gtrgvoayrk.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhoulong.xyz/Article/details/gtqnvcnors.html

[Q54] 清空表
来源：http://dali.jinyuanbaomall.cn/Article/details/gtycxwkmng.html

TRUNCATE TABLE logs;
来源：http://dali.xuanzx.com/Article/details/gtkhahrtjq.html

[Q55] 排名（并列占位）
来源：http://dali.svipenyu.cn/Article/details/gtuqswtwkz.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.andypj.xyz/Article/details/gttskgunis.html

[Q56] 密集排名（并列不占位）
来源：http://dali.daria6918.cn/Article/details/gtrszhnqsy.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.9152youxi.cn/Article/details/gtfujrpbvb.html

[Q57] 行号
来源：http://dali.sxryk.cn/Article/details/gtorwfbser.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.yj20258888.top/Article/details/gtawwatsca.html

[Q58] 累计求和
来源：http://dali.xuanzx.com/Article/details/gtvcwdvmtc.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.sxryk.cn/Article/details/gtubimrutq.html

[Q59] 分组内累计
来源：http://dali.hfpthk.cn/Article/details/gtqqaxkzxa.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.yj20258888.top/Article/details/gtdrgmypol.html

[Q60] 取上一行 / 下一行
来源：http://dali.ybcxt.top/Article/details/gtnhocubsr.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.hnxiangtu.top/Article/details/gtavawlvzx.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.cheryme.top/Article/details/gtmcdlqeif.html

[Q61] 移动平均
来源：http://dali.xinyue.icu/Article/details/gtllsqmjmo.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.xuanzx.com/Article/details/gtfsgxqopi.html

[Q62] 分组占比
来源：http://dali.sysykeji.top/Article/details/gtgumywuxe.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.iojbl.cn/Article/details/gtsmtrddfe.html

[Q63] 开启事务
来源：http://dali.daxiang520.top/Article/details/gtstjpjfcu.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.chenlongwang.top/Article/details/gteggskugw.html

[Q64] 提交事务
来源：http://dali.ppjwa.cn/Article/details/gtbyeazlmv.html

COMMIT;
来源：http://dali.yj20258.top/Article/details/gtzjhhfslq.html

[Q65] 回滚事务
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnfuzueji.html

ROLLBACK;
来源：http://dali.aizwys.cn/Article/details/gtmrcarosk.html

[Q66] 行锁查询
来源：http://dali.jinqigufen.top/Article/details/gtgektdvcu.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.c1oappe.top/Article/details/gtqexmzvmk.html

[Q67] 设置隔离级别
来源：http://dali.shuidangran.top/Article/details/gtbwtbsvxk.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhengqikj.top/Article/details/gtfdqmsvza.html

[Q68] 保存点
来源：http://dali.cucudq.cn/Article/details/gtnyvastzz.html

SAVEPOINT sp1;
来源：http://dali.hnqzz.top/Article/details/gtcifxkbyg.html

ROLLBACK TO sp1;
来源：http://dali.ydzc1.top/Article/details/gthnnyqrva.html

[Q69] 查看执行计划
来源：http://dali.shanyushiyangkeji.top/Article/details/gtffgedqzs.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhaomingkeji.xyz/Article/details/gttdmtacip.html

[Q70] 更新统计信息
来源：http://dali.dianchejie.cn/Article/details/gtivsnflfa.html

ANALYZE TABLE users;
来源：http://dali.nanxinkj.top/Article/details/gtvldctfkl.html

[Q71] 查看建表语句
来源：http://dali.pengpengdd.cyou/Article/details/gttocpmhwe.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.ivvv.top/Article/details/gtouuoajke.html

[Q72] 查看索引
来源：http://dali.shanyushiyangkeji.top/Article/details/gtamgasxhr.html

SHOW INDEX FROM users;
来源：http://dali.sweek.top/Article/details/gtzbhrsvmx.html

[Q73] 查看表状态
来源：http://dali.gaohongyu789.top/Article/details/gtmvnyyenh.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.yj202588.top/Article/details/gtgtrljyeu.html

[Q74] 强制使用索引
来源：http://dali.yonumen.top/Article/details/gtdqzreeza.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.ppjwa.cn/Article/details/gtthlxgapo.html

[Q75] 日期格式化
来源：http://dali.kuanghao11.cn/Article/details/gtdobsuyis.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.sufxvd.cn/Article/details/gtvwndlnkq.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.fzhhl.top/Article/details/gtxlircgcn.html

[Q76] 按天统计
来源：http://dali.havefunace.top/Article/details/gtglzhwned.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhiwuduotai.top/Article/details/gtbhonaytw.html

[Q77] 时间加减
来源：http://dali.xuetiantiany.cn/Article/details/gtozjaxrdq.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.ppjwa.cn/Article/details/gtlqkpwvax.html

[Q78] 当前时间
来源：http://dali.chenlongwang.top/Article/details/gthrrxbkvf.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.redwolf501.top/Article/details/gtwnyexrxw.html

[Q79] 字符串拼接
来源：http://dali.zhengqikj.top/Article/details/gtoookhmsd.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.xylfe.cn/Article/details/gticoqfrof.html

[Q80] 字符串截取
来源：http://dali.feifeiyinyue.top/Article/details/gtdmzccptg.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.cheryme.top/Article/details/gtlqrwywdn.html

[Q81] 字符串替换
来源：http://dali.zdqjudy.top/Article/details/gtwtuuzlmz.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.9152youxi.cn/Article/details/gtdskybmop.html

[Q82] 字符长度与字节长度
来源：http://dali.gzhubu.top/Article/details/gttomnttez.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.guowangkeji.top/Article/details/gtbhbritox.html

[Q83] 大小写转换
来源：http://dali.yonumen.top/Article/details/gtkrjuspdd.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.gogol.net.cn/Article/details/gtrswppyhk.html

[Q84] 去除首尾空格
来源：http://dali.gaohongyu789.top/Article/details/gtvkqzherj.html

SELECT TRIM(name) FROM users;
来源：http://dali.aibaodan.cn/Article/details/gtbjqmjlsc.html

[Q85] 数值取整
来源：http://dali.wangdashe.top/Article/details/gtizioquwp.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.jiagoushi.top/Article/details/gtxvfwiqjf.html

[Q86] 读取 JSON 字段
来源：http://dali.9152youxi.cn/Article/details/gtmonhjamp.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.jyoumei.cn/Article/details/gtwamaeoac.html

[Q87] JSON 字段做条件
来源：http://dali.pycfn.com/Article/details/gtkziqmuvq.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.ybcxt.top/Article/details/gtxcgdppnp.html

[Q88] 行转列（条件聚合）
来源：http://dali.xziqi.cn/Article/details/gtiuddulof.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.jyoumei.cn/Article/details/gtkvczwcxe.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.sweek.top/Article/details/gtcaxkqcvp.html

[Q89] 判断表是否存在
来源：http://dali.c1oappe.top/Article/details/gtxghbjdog.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.chenlongwang.top/Article/details/gtoykvlgqi.html

[Q90] 生成序号列
来源：http://dali.cucudq.cn/Article/details/gttgbnoluc.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.svipenyu.cn/Article/details/gtuvjrxfwz.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtkfplwzdn.html

R. Bash 专题
来源：http://dali.gogol.net.cn/Article/details/gtejebnjtq.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtmcuxouvp.html

[R01] shebang 与严格模式
来源：http://dali.pengpengdd.cyou/Article/details/gthuedixsg.html

#!/usr/bin/env bash
来源：http://dali.jlsjyb.cn/Article/details/gthumlofcf.html

set -euo pipefail
来源：http://dali.daria6918.cn/Article/details/gtvixyzgsp.html

[R02] 变量赋值与使用
来源：http://dali.jlsjyb.cn/Article/details/gtviffelat.html

name="Tom"; echo "$name"
来源：http://dali.jinqigfzy.top/Article/details/gtohzlziuo.html

[R03] 只读变量
来源：http://dali.hfpthk.cn/Article/details/gteimwmxrb.html

readonly PI=3.14
来源：http://dali.birdmap.top/Article/details/gtayfnhfue.html

[R04] 位置参数
来源：http://dali.zycfv.cn/Article/details/gtyfbbmpsi.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.gzhubu.top/Article/details/gthzgzrjwi.html

[R05] 参数默认值
来源：http://dali.svipenyu.cn/Article/details/gtmarbqtal.html

name="${1:-default}"
来源：http://dali.quarkkingdee.top/Article/details/gtbcgfpwbf.html

[R06] 判断命令是否存在
来源：http://dali.shuidangran.top/Article/details/gtfrdiggau.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.daxiang520.top/Article/details/gtdbltrdpd.html

[R07] if 判断文件
来源：http://dali.snrcjt.cn/Article/details/gtrhbciato.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.haohaochexian.top/Article/details/gtmvnnidph.html

[R08] 数值比较
来源：http://dali.zhiwuduotai.top/Article/details/gtroqraotr.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.yvedp.cn/Article/details/gtadpbxngn.html

[R09] 字符串比较
来源：http://dali.redwolf501.top/Article/details/gtogqbfdft.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.svipenyu.cn/Article/details/gtvdjcbhhe.html

[R10] 正则匹配
来源：http://dali.daria6918.cn/Article/details/gtbwszjsaf.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.mhx1999.top/Article/details/gtbkqnicww.html

[R11] case 多分支
来源：http://dali.gogol.net.cn/Article/details/gtyhrahemr.html

case "$1" in
来源：http://dali.wangshuangyany.cn/Article/details/gtnetmptqa.html

start) echo "启动" ;;
来源：http://dali.shzxlz.cn/Article/details/gtizrjshfe.html

stop)  echo "停止" ;;
来源：http://dali.jyoumei.cn/Article/details/gtepktybgg.html

*)     echo "未知命令" ;;
来源：http://dali.hnqzz.top/Article/details/gtrutrqmwn.html

esac
来源：http://dali.cqqwz.cn/Article/details/gtwrzukgqx.html

[R12] for 遍历文件
来源：http://dali.tanke756.top/Article/details/gtevsefecn.html

for f in *.txt; do echo "$f"; done
来源：http://dali.c1oappe.top/Article/details/gtwaqmrhtr.html

[R13] for 计数循环
来源：http://dali.sufxvd.cn/Article/details/gtbvateqkn.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.quarkkingdee.top/Article/details/gtmmqsbfnd.html

[R14] C 风格 for
来源：http://dali.tian-w.cn/Article/details/gtazszuhpd.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.hfpthk.cn/Article/details/gtefjiglfs.html

[R15] while 逐行读文件
来源：http://dali.dianchejie.cn/Article/details/gtarnynqjc.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.kuanghao11.cn/Article/details/gtkvuaudxp.html

[R16] until 等待条件
来源：http://dali.sysykeji.top/Article/details/gtfpvewfnh.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhongyouzk.top/Article/details/gtdcmwymtn.html

[R17] 数组定义与取值
来源：http://dali.yj20258888.top/Article/details/gtarimwewp.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.shzxlz.cn/Article/details/gtglhmibjg.html

[R18] 遍历数组
来源：http://dali.chenlongwang.top/Article/details/gtbxgagjmq.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.aizwys.cn/Article/details/gtmlfzuaik.html

[R19] 数组长度
来源：http://dali.smart0.xyz/Article/details/gtmvjsqgyb.html

echo "${#arr[@]}"
来源：http://dali.yuxming.cn/Article/details/gtjdvqwkkj.html

[R20] 关联数组（字典）
来源：http://dali.wangdashe.top/Article/details/gtecwygfoo.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.xylfe.cn/Article/details/gtdjjketsb.html

[R21] 字符串长度
来源：http://dali.jinyuanbaomall.cn/Article/details/gtifcpeucu.html

echo "${#s}"
来源：http://dali.zhixingplan.top/Article/details/gtuxtdeory.html

[R22] 截取子串
来源：http://dali.yuanzhike.top/Article/details/gtdxexxhzc.html

echo "${s:0:5}"
来源：http://dali.aizwys.cn/Article/details/gtopnujisp.html

[R23] 字符串替换
来源：http://dali.jinghuilouyu.cn/Article/details/gtlydsdccg.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvtfziifz.html

[R24] 大小写转换
来源：http://dali.gogol.net.cn/Article/details/gtuvgyqgzs.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.quarkkingdee.top/Article/details/gtwjdvyzjn.html

[R25] 去后缀 / 去前缀
来源：http://dali.nanxuanxn.top/Article/details/gtofnyfhpy.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.shangyingyoupin.top/Article/details/gtnnfrhzcs.html

[R26] 命令替换
来源：http://dali.cashguo.top/Article/details/gtjxqcfsvp.html

now=$(date +%F); echo "$now"
来源：http://dali.meibo888.top/Article/details/gtcbqhfnai.html

[R27] 算术展开
来源：http://dali.yj20258888.top/Article/details/gtzckuopov.html

echo $((1 + 2 * 3))
来源：http://dali.xuetiantiany.cn/Article/details/gtfgrofazz.html

[R28] 浮点运算
来源：http://dali.xylfe.cn/Article/details/gtdwsltixs.html

echo "scale=2; 10/3" | bc
来源：http://dali.jinghuilouyu.cn/Article/details/gtfgvddvgp.html

[R29] 定义函数
来源：http://dali.vqdsnc.cn/Article/details/gtuczwpkqp.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.sufxvd.cn/Article/details/gtyesxzguf.html

[R30] 函数返回状态码
来源：http://dali.yonumen.top/Article/details/gtijlggsap.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.jqgufenzy.top/Article/details/gtbmgdhzjm.html

[R31] 局部变量
来源：http://dali.shangyingyoupin.top/Article/details/gtrieeslaq.html

f() { local x=1; echo "$x"; }
来源：http://dali.shuidangran.top/Article/details/gtruyiyljy.html

[R32] 参数个数校验
来源：http://dali.nanxinkj.top/Article/details/gtrpilvoof.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.iojbl.cn/Article/details/gtlfwxcknk.html

[R33] 捕获错误并提示行号
来源：http://dali.zhaomingkeji.xyz/Article/details/gthomdvvob.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.cdnleiting.top/Article/details/gtgqhwibed.html

[R34] 退出时清理
来源：http://dali.shanyushiyangtech.top/Article/details/gtxqetoylh.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.vqdsnc.cn/Article/details/gtryjxjqjo.html

[R35] 后台执行并等待
来源：http://dali.yangfankeji.com/Article/details/gtevwftgmz.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.yj202588.top/Article/details/gtfyymkwcv.html

[R36] 并发执行多个任务
来源：http://dali.hfpthk.cn/Article/details/gtrcxnfsxk.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.ppjwa.cn/Article/details/gthkmbagoe.html

[R37] 把输出赋给变量
来源：http://dali.dashuyun.cn/Article/details/gtcowgnbro.html

files=$(ls -1)
来源：http://dali.zhongyouzk.top/Article/details/gtqxbeadth.html

[R38] 管道串联
来源：http://dali.shanyushiyangtech.top/Article/details/gtrlkcodha.html

cat a.txt | grep -i error | wc -l
来源：http://dali.jiagoushi.top/Article/details/gtuonghcsf.html

[R39] 重定向标准输出与错误
来源：http://dali.dianchejie.cn/Article/details/gtjequgyxy.html

cmd > out.log 2>&1
来源：http://dali.nanxinkj.top/Article/details/gtlegpvlic.html

[R40] 追加写日志
来源：http://dali.yanxiufei.cn/Article/details/gtmayvpjpz.html

echo "log" >> out.log
来源：http://dali.gogol.net.cn/Article/details/gtgjswbbec.html

[R41] 丢弃输出
来源：http://dali.shangyingyoupin.top/Article/details/gtaxqvrxtz.html

cmd >/dev/null 2>&1
来源：http://dali.jinqigufen.top/Article/details/gtdeciukru.html

[R42] 输入重定向
来源：http://dali.yuxming.cn/Article/details/gttfeivpkf.html

wc -l < a.txt
来源：http://dali.shangyingyoupin.top/Article/details/gtjrobpcfz.html

[R43] 按名字查找文件
来源：http://dali.sweek.top/Article/details/gtbhmvpizl.html

find . -name "*.log" -type f
来源：http://dali.zhixingplan.top/Article/details/gttqdlqjzm.html

[R44] 按修改时间查找
来源：http://dali.hnxiangtu.top/Article/details/gtfelqiguh.html

find . -mtime -7 -type f
来源：http://dali.cdnleiting.top/Article/details/gtkwgtddow.html

[R45] 批量删除
来源：http://dali.aizwys.cn/Article/details/gtgoxpbwca.html

find . -name "*.tmp" -delete
来源：http://dali.xylfe.cn/Article/details/gtyjxddhkp.html

[R46] 递归替换文件内容
来源：http://dali.guowangkeji.top/Article/details/gtfemxqtmb.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.haohaochexian.top/Article/details/gtwxnamkpf.html

[R47] sed 单行替换
来源：http://dali.redwolf501.top/Article/details/gtstbjvujk.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.redwolf501.top/Article/details/gtkbfrlmxa.html

[R48] awk 取指定列
来源：http://dali.xinyue.icu/Article/details/gtovmwgiwy.html

awk '{print $1, $3}' a.txt
来源：http://dali.havefunace.top/Article/details/gtfnuoxqjz.html

[R49] awk 带条件
来源：http://dali.kuanghao11.cn/Article/details/gtgegpdxwy.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhongyouzk.top/Article/details/gturmnaqpu.html

[R50] awk 求和
来源：http://dali.hnqzz.top/Article/details/gtleqcxgdd.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhiwuduotai.top/Article/details/gtsyfotfcw.html

[R51] 排序去重取前几
来源：http://dali.snrcjt.cn/Article/details/gtudloznhe.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.dianchejie.cn/Article/details/gtsmubhczi.html

[R52] 统计行数
来源：http://dali.tian-w.cn/Article/details/gtfpatktfk.html

wc -l a.txt
来源：http://dali.hfpthk.cn/Article/details/gtahgkxgmr.html

[R53] 查看文件头与实时尾
来源：http://dali.wangshuangyany.cn/Article/details/gtfklbhntm.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.nanxuanxn.top/Article/details/gtaghqtqbb.html

[R54] 比较两个文件
来源：http://dali.yuanzhike.top/Article/details/gtmynxxics.html

diff a.txt b.txt
来源：http://dali.hfpthk.cn/Article/details/gthmhehpub.html

[R55] 压缩与解压
来源：http://dali.aizwys.cn/Article/details/gtytpetmyv.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.daxiang520.top/Article/details/gtpeupwrvt.html

[R56] 远程拷贝
来源：http://dali.hywenlv.cn/Article/details/gtiunesbwg.html

scp file user@host:/path/
来源：http://dali.zycfv.cn/Article/details/gtutgnfrvi.html

[R57] 远程执行命令
来源：http://dali.jinghuilouyu.cn/Article/details/gtxlvtykqg.html

ssh user@host 'uptime'
来源：http://dali.chenzaomai.com/Article/details/gtuijwklgr.html

[R58] 下载文件
来源：http://dali.cdnleiting.top/Article/details/gtogwzhdxh.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.chenjidiqi.icu/Article/details/gtfqobdfnx.html

[R59] 发 POST JSON
来源：http://dali.ybcxt.top/Article/details/gtuqvzvamn.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.tian-w.cn/Article/details/gtvqlotelp.html

[R60] 只看 HTTP 状态码
来源：http://dali.shanyushiyangtech.top/Article/details/gtwglcwmvi.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhoulong.xyz/Article/details/gtgfxzmclf.html

[R61] 磁盘占用
来源：http://dali.aibaodan.cn/Article/details/gtmihpszfz.html

df -h;  du -sh *
来源：http://dali.nanxinkj.top/Article/details/gtwifdomfa.html

[R62] 找最占空间的文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcztsesbf.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gtrgrksffz.html

[R63] 内存与进程
来源：http://dali.yangfankeji.com/Article/details/gtxfhlqoiu.html

free -h;  ps aux | grep nginx
来源：http://dali.gaohongyu789.top/Article/details/gtivjhdkbw.html

[R64] 结束进程
来源：http://dali.bjfxy.top/Article/details/gtiflkctfa.html

kill -9 $(pgrep -f app.py)
来源：http://dali.fzhhl.top/Article/details/gtoeajfuqd.html

[R65] 查看端口占用
来源：http://dali.shanyushiyangtech.top/Article/details/gtinmsdqzx.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhengqikj.top/Article/details/gthaoohasj.html

[R66] 定时任务
来源：http://dali.yj20258888.top/Article/details/gtsthkdlra.html

crontab -e;  crontab -l
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcvsqvgpc.html

[R67] 生成随机十六进制串
来源：http://dali.9152youxi.cn/Article/details/gtpbxpuuxh.html

openssl rand -hex 16
来源：http://dali.0kj1m.cn/Article/details/gttrdmwdwx.html

[R68] 计算文件校验值
来源：http://dali.c1oappe.top/Article/details/gtfkfwxroh.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.yuanzhike.top/Article/details/gtfixywaql.html

[R69] 生成随机密码
来源：http://dali.yanxiufei.cn/Article/details/gtmaxeskpp.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gtegqeblru.html

[R70] 时间戳与互转
来源：http://dali.sweek.top/Article/details/gtwtpnvxgl.html

date +%s;  date -d @1700000000
来源：http://dali.yanxiufei.cn/Article/details/gtgjzmpefo.html

[R71] 日期格式化
来源：http://dali.yongpay.top/Article/details/gtrfxmbnru.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.aizwys.cn/Article/details/gtoqrelcdl.html

[R72] 等待端口就绪
来源：http://dali.andypj.xyz/Article/details/gtfwjohhzo.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.tianlin.xyz/Article/details/gtfpwgyeeb.html

[R73] 分割大日志
来源：http://dali.mhx1999.top/Article/details/gtfhzkppgo.html

split -l 1000 big.log part_
来源：http://dali.zhaomingkeji.xyz/Article/details/gtynrxifzv.html

[R74] 批量重命名
来源：http://dali.cashguo.top/Article/details/gtvsomhabr.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.svipenyu.cn/Article/details/gtoboafndf.html

[R75] 导出环境变量
来源：http://dali.c1oappe.top/Article/details/gtaupuuglr.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.guowangkeji.top/Article/details/gtagzatcys.html

[R76] 使用临时文件
来源：http://dali.andypj.xyz/Article/details/gtzmebudaq.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.redwolf501.top/Article/details/gthvymzwzb.html

[R77] 读取用户输入
来源：http://dali.jianghu66.top/Article/details/gtprwzujeu.html


<!-- 参考信息 -->