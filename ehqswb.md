代发 wailian999

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.cucudq.cn/Article/details/gtcygyfkrt.html

[Q24] 去重
来源：http://dali.zhaomingkeji.xyz/Article/details/gtycvqwwck.html

SELECT DISTINCT city FROM users;
来源：http://dali.xziqi.cn/Article/details/gtlaztqikq.html

[Q25] 只取前 N 条
来源：http://dali.chenjidiqi.icu/Article/details/gtuyvjtfyb.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.9152youxi.cn/Article/details/gtocwsauit.html

[Q26] 计数
来源：http://dali.jyoumei.cn/Article/details/gtagwvdcjg.html

SELECT COUNT(*) FROM users;
来源：http://dali.c1oappe.top/Article/details/gtevybvgqz.html

[Q27] 条件计数
来源：http://dali.yonumen.top/Article/details/gtylhmvkpx.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.nanxinkj.top/Article/details/gtwzdkcoud.html

[Q28] 求和与平均
来源：http://dali.zhongyouzk.top/Article/details/gtxjsipwqt.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.jiagoushi.top/Article/details/gtgvqwhkos.html

[Q29] 最大最小值
来源：http://dali.sweek.top/Article/details/gtjumboxpt.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.jqgfzy.top/Article/details/gtsmiygzfr.html

[Q30] 分组统计
来源：http://dali.cheryme.top/Article/details/gtzactufbt.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.jianghu66.top/Article/details/gtguhdlxri.html

[Q31] 分组后过滤
来源：http://dali.nwbrower.top/Article/details/gtzchlbxnk.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsvhnywdz.html

[Q32] 分组拼接字符串
来源：http://dali.dashuyun.cn/Article/details/gtvkjhuide.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.vqdsnc.cn/Article/details/gtbelzcojp.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.yanxiufei.cn/Article/details/gtvqfoaies.html

[Q33] 多列分组
来源：http://dali.jinqigufen.top/Article/details/gtfznwganr.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.quarkkingdee.top/Article/details/gtinblalbi.html

[Q34] 每组取第一条
来源：http://dali.cheryme.top/Article/details/gtaxrdawlg.html

SELECT * FROM (
来源：http://dali.c1oappe.top/Article/details/gtqqcansme.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.aizwys.cn/Article/details/gthzmyntqx.html

) t WHERE rn = 1;
来源：http://dali.aizwys.cn/Article/details/gtupxieaax.html

[Q35] 内连接
来源：http://dali.ivvv.top/Article/details/gtrekfkxwf.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.ehwqpu.com/Article/details/gtulginuuu.html

[Q36] 左连接
来源：http://dali.xinyue.icu/Article/details/gtnilfibms.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.meibo888.top/Article/details/gttcqizazi.html

[Q37] 右连接
来源：http://dali.redwolf501.top/Article/details/gtxtxdtusg.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.shangyingyoupin.top/Article/details/gteicfuhut.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.shanyushiyangtech.top/Article/details/gtdvfbgptu.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhongyouzk.top/Article/details/gtehxpawvy.html

[Q39] 自连接（查上下级）
来源：http://dali.aizwys.cn/Article/details/gtgrgswbcz.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.shuidangran.top/Article/details/gtjrdyhfln.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.chenzaomai.com/Article/details/gtejuwbvkn.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.shanyushiyangtech.top/Article/details/gtloepisow.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.mhx1999.top/Article/details/gthrvidblp.html

[Q41] 多表连接
来源：http://dali.gogol.net.cn/Article/details/gtaxgdqjpp.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.hnqzz.top/Article/details/gtflnmxncu.html

JOIN users u ON u.id = o.user_id
来源：http://dali.tianlin.xyz/Article/details/gtkioxkadl.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhiwuduotai.top/Article/details/gtafvkgixd.html

[Q42] 连接条件附加过滤
来源：http://dali.ppjwa.cn/Article/details/gtbhtqjazl.html

SELECT u.name, o.amount FROM users u
来源：http://dali.aizwys.cn/Article/details/gtivjmhjel.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.fengsongda.top/Article/details/gtzqxcdpsj.html

[Q43] 标量子查询
来源：http://dali.fzhhl.top/Article/details/gtwjyelatj.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.yuanzhike.top/Article/details/gtedphgpow.html

[Q44] IN 子查询
来源：http://dali.wangdashe.top/Article/details/gtydlsulib.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.shuidangran.top/Article/details/gtiqqlnqbs.html

[Q45] EXISTS 判断存在
来源：http://dali.tian-w.cn/Article/details/gtfjxtukgm.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.xylfe.cn/Article/details/gttpkloaif.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.snrcjt.cn/Article/details/gtjjvjhrth.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.xuanzx.com/Article/details/gtcsaoluxg.html

[Q47] 与平均值比较
来源：http://dali.fzhhl.top/Article/details/gtsommfifm.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.hnxiangtu.top/Article/details/gttawixohx.html

[Q48] CTE 公用表表达式
来源：http://dali.jyoumei.cn/Article/details/gtglkktvao.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.jlsjyb.cn/Article/details/gtiyxezics.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.sufxvd.cn/Article/details/gtisybavfv.html

[Q49] 更新单行
来源：http://dali.ppjwa.cn/Article/details/gtmniyslnk.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gtaommbuqb.html

[Q50] 批量更新
来源：http://dali.zdqjudy.top/Article/details/gtlhwawfyj.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.cdnleiting.top/Article/details/gtjtvirldn.html

[Q51] 用子查询更新
来源：http://dali.dashuyun.cn/Article/details/gtgxzryocy.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtahozntzs.html

[Q52] 删除指定行
来源：http://dali.ydzc1.top/Article/details/gtgsrcryzu.html

DELETE FROM users WHERE id = 10;
来源：http://dali.chenjidiqi.icu/Article/details/gtcljhqwgn.html

[Q53] 按条件删除
来源：http://dali.gogol.net.cn/Article/details/gtryzhxdux.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.jinqigfzy.top/Article/details/gtmcjozjre.html

[Q54] 清空表
来源：http://dali.havefunace.top/Article/details/gtbzuiayct.html

TRUNCATE TABLE logs;
来源：http://dali.hammf.cn/Article/details/gtwjmrzigl.html

[Q55] 排名（并列占位）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkkoccizc.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.ivvv.top/Article/details/gtlquzhykz.html

[Q56] 密集排名（并列不占位）
来源：http://dali.wangdashe.top/Article/details/gtzgaawwra.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnfcnnkhp.html

[Q57] 行号
来源：http://dali.mhx1999.top/Article/details/gtajkymkkv.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.jyoumei.cn/Article/details/gtprtpayie.html

[Q58] 累计求和
来源：http://dali.jinqigufen.top/Article/details/gtoualeeea.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.ppjwa.cn/Article/details/gtncabubap.html

[Q59] 分组内累计
来源：http://dali.yangfankeji.com/Article/details/gtegxdakuv.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.jqgufenzy.top/Article/details/gtmpnutgpj.html

[Q60] 取上一行 / 下一行
来源：http://dali.hnxiangtu.top/Article/details/gtrnqlceit.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgdorgykj.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.hysaishi.cn/Article/details/gtabqycciw.html

[Q61] 移动平均
来源：http://dali.shanyushiyangtech.top/Article/details/gtozoiudkp.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.aibaodan.cn/Article/details/gtzaiuoqsu.html

[Q62] 分组占比
来源：http://dali.zycfv.cn/Article/details/gtngmvjxjl.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.sufxvd.cn/Article/details/gtdyncbpwb.html

[Q63] 开启事务
来源：http://dali.yvedp.cn/Article/details/gtmeayrecu.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.guannengcc.top/Article/details/gtozfraaof.html

[Q64] 提交事务
来源：http://dali.ehwqpu.com/Article/details/gtlmpbkbln.html

COMMIT;
来源：http://dali.snrcjt.cn/Article/details/gtmpxnclpf.html

[Q65] 回滚事务
来源：http://dali.kuanghao11.cn/Article/details/gtfauxsnzn.html

ROLLBACK;
来源：http://dali.yongpay.top/Article/details/gtwyfnkmrj.html

[Q66] 行锁查询
来源：http://dali.zhongyouzk.top/Article/details/gtkbifelid.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.guannengcc.top/Article/details/gtwtptfelq.html

[Q67] 设置隔离级别
来源：http://dali.birdmap.top/Article/details/gtndadqbaa.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.svipenyu.cn/Article/details/gtjifogbad.html

[Q68] 保存点
来源：http://dali.0kj1m.cn/Article/details/gtmmfsymda.html

SAVEPOINT sp1;
来源：http://dali.gzhubu.top/Article/details/gtrowsnsax.html

ROLLBACK TO sp1;
来源：http://dali.wangdashe.top/Article/details/gtmyephycn.html

[Q69] 查看执行计划
来源：http://dali.guowangkeji.top/Article/details/gtgvekglaj.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.haohaochexian.top/Article/details/gtdrfxafcl.html

[Q70] 更新统计信息
来源：http://dali.jlsjyb.cn/Article/details/gtcrwdglmk.html

ANALYZE TABLE users;
来源：http://dali.hnqzz.top/Article/details/gtybotuvta.html

[Q71] 查看建表语句
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrzecresg.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.birdmap.top/Article/details/gtyskzldfy.html

[Q72] 查看索引
来源：http://dali.9152youxi.cn/Article/details/gtynlbfvow.html

SHOW INDEX FROM users;
来源：http://dali.haohaochexian.top/Article/details/gtzgacxkmx.html

[Q73] 查看表状态
来源：http://dali.yongpay.top/Article/details/gthejkhrkx.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.dashuyun.cn/Article/details/gtpnhmxxjw.html

[Q74] 强制使用索引
来源：http://dali.kuanghao11.cn/Article/details/gtipyfmkjm.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.wangshuangyany.cn/Article/details/gtnwovncvr.html

[Q75] 日期格式化
来源：http://dali.yj20258888.top/Article/details/gtmlpfxdmc.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.ivvv.top/Article/details/gtdygxlauc.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.dianchejie.cn/Article/details/gtxfcyawwt.html

[Q76] 按天统计
来源：http://dali.bjfxy.top/Article/details/gtllmxpwwg.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.havefunace.top/Article/details/gtnyvskrfz.html

[Q77] 时间加减
来源：http://dali.yvedp.cn/Article/details/gtybpklkrl.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.jianghu66.top/Article/details/gtqepmenae.html

[Q78] 当前时间
来源：http://dali.quarkkingdee.top/Article/details/gtbdzmumav.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.jinqigufen.top/Article/details/gtzpkmeaqm.html

[Q79] 字符串拼接
来源：http://dali.shzxlz.cn/Article/details/gtsfbxyvox.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.c1oappe.top/Article/details/gtaiogpezb.html

[Q80] 字符串截取
来源：http://dali.9152youxi.cn/Article/details/gtvyrkjqpn.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.yonumen.top/Article/details/gtrzppgnrs.html

[Q81] 字符串替换
来源：http://dali.guowangkeji.top/Article/details/gtuopyivnu.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.mhx1999.top/Article/details/gtzwqwapom.html

[Q82] 字符长度与字节长度
来源：http://dali.9152youxi.cn/Article/details/gtigoyvmzd.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.xinyue.icu/Article/details/gtajtfgims.html

[Q83] 大小写转换
来源：http://dali.yj202588.top/Article/details/gtobzfcvpo.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.chenlongwang.top/Article/details/gttphxemrq.html

[Q84] 去除首尾空格
来源：http://dali.xylfe.cn/Article/details/gtvfzxihbd.html

SELECT TRIM(name) FROM users;
来源：http://dali.316326.xyz/Article/details/gtwbdonhmr.html

[Q85] 数值取整
来源：http://dali.ehwqpu.com/Article/details/gtcyvsvekb.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.yj20258888.top/Article/details/gttkxgywmb.html

[Q86] 读取 JSON 字段
来源：http://dali.hnqzz.top/Article/details/gtwjbiguzd.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.hysaishi.cn/Article/details/gtmkuoairg.html

[Q87] JSON 字段做条件
来源：http://dali.pycfn.com/Article/details/gtwapxhwkm.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.gaohongyu789.top/Article/details/gtnjvblqky.html

[Q88] 行转列（条件聚合）
来源：http://dali.feifeiyinyue.top/Article/details/gttxldggwj.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.dashuyun.cn/Article/details/gtnqqvedud.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.bjfxy.top/Article/details/gtexnzgmpm.html

[Q89] 判断表是否存在
来源：http://dali.fengsongda.top/Article/details/gtpesozptn.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.ivvv.top/Article/details/gtgsebspjj.html

[Q90] 生成序号列
来源：http://dali.dianchejie.cn/Article/details/gtlxjrequn.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcgqseuix.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtobwylfds.html

R. Bash 专题
来源：http://dali.hammf.cn/Article/details/gtjcfiwazx.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtntapsfmi.html

[R01] shebang 与严格模式
来源：http://dali.smart0.xyz/Article/details/gtdrpkvexz.html

#!/usr/bin/env bash
来源：http://dali.c1oappe.top/Article/details/gtudybqryr.html

set -euo pipefail
来源：http://dali.daria6918.cn/Article/details/gtqkahdxov.html

[R02] 变量赋值与使用
来源：http://dali.cashguo.top/Article/details/gtmbywgtbv.html

name="Tom"; echo "$name"
来源：http://dali.zhiwuduotai.top/Article/details/gtvhppnirb.html

[R03] 只读变量
来源：http://dali.cheryme.top/Article/details/gtcqaerdoo.html

readonly PI=3.14
来源：http://dali.meibo888.top/Article/details/gtsjcgjxze.html

[R04] 位置参数
来源：http://dali.tianlin.xyz/Article/details/gtnczujzyq.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.snrcjt.cn/Article/details/gtalcxclwr.html

[R05] 参数默认值
来源：http://dali.vqdsnc.cn/Article/details/gtmlpdqhyv.html

name="${1:-default}"
来源：http://dali.vqdsnc.cn/Article/details/gtyicxrflc.html

[R06] 判断命令是否存在
来源：http://dali.yanxiufei.cn/Article/details/gtvynvxkfi.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.sysykeji.top/Article/details/gturfmdoeh.html

[R07] if 判断文件
来源：http://dali.sweek.top/Article/details/gtnyvnbdxl.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.yj20258.top/Article/details/gtdnelhnki.html

[R08] 数值比较
来源：http://dali.hywenlv.cn/Article/details/gtnotvaazf.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.chenjidiqi.icu/Article/details/gtprxztyrk.html

[R09] 字符串比较
来源：http://dali.cucudq.cn/Article/details/gtfgpdazpa.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.nwbrower.top/Article/details/gtdmthwipp.html

[R10] 正则匹配
来源：http://dali.tianlin.xyz/Article/details/gtaoypomca.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.sufxvd.cn/Article/details/gtalixqbaf.html

[R11] case 多分支
来源：http://dali.yonumen.top/Article/details/gtentpaukq.html

case "$1" in
来源：http://dali.snrcjt.cn/Article/details/gthzsqisnw.html

start) echo "启动" ;;
来源：http://dali.aizwys.cn/Article/details/gtnsdrbzkm.html

stop)  echo "停止" ;;
来源：http://dali.birdmap.top/Article/details/gtbnbiexcs.html

*)     echo "未知命令" ;;
来源：http://dali.xuetiantiany.cn/Article/details/gtqwsxmwei.html

esac
来源：http://dali.shuidangran.top/Article/details/gtsvqacudn.html

[R12] for 遍历文件
来源：http://dali.nwbrower.top/Article/details/gtbvhgxvyw.html

for f in *.txt; do echo "$f"; done
来源：http://dali.dianchejie.cn/Article/details/gtbxspnnyr.html

[R13] for 计数循环
来源：http://dali.gotoacloud.top/Article/details/gtwglngpnq.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.aibaodan.cn/Article/details/gthekigmgh.html

[R14] C 风格 for
来源：http://dali.birdmap.top/Article/details/gtobisncsf.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.tanke756.top/Article/details/gtqosvrpob.html

[R15] while 逐行读文件
来源：http://dali.jyoumei.cn/Article/details/gtauvpbxhv.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.hongshengwenyu.top/Article/details/gtfudktcjg.html

[R16] until 等待条件
来源：http://dali.sysykeji.top/Article/details/gtzqckjnbq.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.hywenlv.cn/Article/details/gtyqposwfl.html

[R17] 数组定义与取值
来源：http://dali.hongshengwenyu.top/Article/details/gtoilnedop.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.pycfn.com/Article/details/gtlfapxiuo.html

[R18] 遍历数组
来源：http://dali.guowangkeji.top/Article/details/gtiykgsqta.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.shzxlz.cn/Article/details/gtdtsefyri.html

[R19] 数组长度
来源：http://dali.mhx1999.top/Article/details/gtfmopkuoz.html

echo "${#arr[@]}"
来源：http://dali.sysykeji.top/Article/details/gtjqwraxkl.html

[R20] 关联数组（字典）
来源：http://dali.snrcjt.cn/Article/details/gtqxdpcwos.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.yuxming.cn/Article/details/gtmkozhvwp.html

[R21] 字符串长度
来源：http://dali.yonumen.top/Article/details/gtpriwlcui.html

echo "${#s}"
来源：http://dali.jinghuilouyu.cn/Article/details/gtzpedfgme.html

[R22] 截取子串
来源：http://dali.jqgufenzy.top/Article/details/gtrrkbubag.html

echo "${s:0:5}"
来源：http://dali.hfpthk.cn/Article/details/gthdollgiw.html

[R23] 字符串替换
来源：http://dali.zhongyouzk.top/Article/details/gtckamvudg.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.cashguo.top/Article/details/gtqnxhijns.html

[R24] 大小写转换
来源：http://dali.9152youxi.cn/Article/details/gtiwgrjqtg.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.snrcjt.cn/Article/details/gtvpyjmpjk.html

[R25] 去后缀 / 去前缀
来源：http://dali.shangyingyoupin.top/Article/details/gtqfecoclx.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.daxiang520.top/Article/details/gtpzsxvidy.html

[R26] 命令替换
来源：http://dali.ydzc1.top/Article/details/gtipncekmn.html

now=$(date +%F); echo "$now"
来源：http://dali.yueranfly.top/Article/details/gtqprrvsoc.html

[R27] 算术展开
来源：http://dali.hammf.cn/Article/details/gtufepvtpi.html

echo $((1 + 2 * 3))
来源：http://dali.vqdsnc.cn/Article/details/gttfknlcjv.html

[R28] 浮点运算
来源：http://dali.wangdashe.top/Article/details/gtciunrigt.html

echo "scale=2; 10/3" | bc
来源：http://dali.tian-w.cn/Article/details/gtyvskgzef.html

[R29] 定义函数
来源：http://dali.gzhubu.top/Article/details/gtfombsxlo.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.yongpay.top/Article/details/gtzsxessqr.html

[R30] 函数返回状态码
来源：http://dali.sysykeji.top/Article/details/gtnwzlagxe.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.sweek.top/Article/details/gtjdxchlfl.html

[R31] 局部变量
来源：http://dali.gzhubu.top/Article/details/gtwoyivkaz.html

f() { local x=1; echo "$x"; }
来源：http://dali.fzhhl.top/Article/details/gtamtdikny.html

[R32] 参数个数校验
来源：http://dali.zhengqikj.top/Article/details/gtgdqmbdtj.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.yj202588.top/Article/details/gtjpebdfsv.html

[R33] 捕获错误并提示行号
来源：http://dali.meibo888.top/Article/details/gtwbrsbkrt.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.hongshengwenyu.top/Article/details/gtmziakqhv.html

[R34] 退出时清理
来源：http://dali.316326.xyz/Article/details/gtvzwodzjy.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.quarkkingdee.top/Article/details/gtnmscekxy.html

[R35] 后台执行并等待
来源：http://dali.aizwys.cn/Article/details/gtzhkxfxpe.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.sxryk.cn/Article/details/gtchbqohja.html

[R36] 并发执行多个任务
来源：http://dali.yj20258.top/Article/details/gtiadybfnj.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.cheryme.top/Article/details/gtcecfwkhb.html

[R37] 把输出赋给变量
来源：http://dali.tianlin.xyz/Article/details/gtispkwquy.html

files=$(ls -1)
来源：http://dali.cqqwz.cn/Article/details/gtzciznorw.html

[R38] 管道串联
来源：http://dali.yvedp.cn/Article/details/gtmddpsqqa.html

cat a.txt | grep -i error | wc -l
来源：http://dali.guannengcc.top/Article/details/gtszgxckzz.html

[R39] 重定向标准输出与错误
来源：http://dali.ehwqpu.com/Article/details/gttclmcjcw.html

cmd > out.log 2>&1
来源：http://dali.hnqzz.top/Article/details/gtbuqxaewh.html

[R40] 追加写日志
来源：http://dali.jiagoushi.top/Article/details/gtvpgdwtuz.html

echo "log" >> out.log
来源：http://dali.zhongyouzk.top/Article/details/gtplelmyjg.html

[R41] 丢弃输出
来源：http://dali.shzxlz.cn/Article/details/gtuhsqqqul.html

cmd >/dev/null 2>&1
来源：http://dali.sxryk.cn/Article/details/gtrqludcdw.html

[R42] 输入重定向
来源：http://dali.0kj1m.cn/Article/details/gtwsamcoig.html

wc -l < a.txt
来源：http://dali.c1oappe.top/Article/details/gtmxrngrtm.html

[R43] 按名字查找文件
来源：http://dali.yanxiufei.cn/Article/details/gtsdqfuteg.html

find . -name "*.log" -type f
来源：http://dali.yonumen.top/Article/details/gtgitqanth.html

[R44] 按修改时间查找
来源：http://dali.vqdsnc.cn/Article/details/gtejefiquk.html

find . -mtime -7 -type f
来源：http://dali.jqgufenzy.top/Article/details/gtqirhnknc.html

[R45] 批量删除
来源：http://dali.yongpay.top/Article/details/gtooyxbrly.html

find . -name "*.tmp" -delete
来源：http://dali.tian-w.cn/Article/details/gtnlhlnbbq.html

[R46] 递归替换文件内容
来源：http://dali.316326.xyz/Article/details/gtwnzkkinp.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.ybcxt.top/Article/details/gtjqyrqyhq.html

[R47] sed 单行替换
来源：http://dali.c1oappe.top/Article/details/gtipevyqpo.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.0kj1m.cn/Article/details/gthmuszaob.html

[R48] awk 取指定列
来源：http://dali.sweek.top/Article/details/gtlyulpudn.html

awk '{print $1, $3}' a.txt
来源：http://dali.gaohongyu789.top/Article/details/gtycmonena.html

[R49] awk 带条件
来源：http://dali.smart0.xyz/Article/details/gtslrxkizq.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.daxiang520.top/Article/details/gtixdzccpl.html

[R50] awk 求和
来源：http://dali.shanyushiyangtech.top/Article/details/gthrbktevg.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.andypj.xyz/Article/details/gtknernbph.html

[R51] 排序去重取前几
来源：http://dali.yj20258.top/Article/details/gtxmkwhajh.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.ehwqpu.com/Article/details/gtcgbrsipk.html

[R52] 统计行数
来源：http://dali.zdqjudy.top/Article/details/gtmxcclehv.html

wc -l a.txt
来源：http://dali.bjfxy.top/Article/details/gtkyvqpyyq.html

[R53] 查看文件头与实时尾
来源：http://dali.andypj.xyz/Article/details/gtfhzqnqoj.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.nwbrower.top/Article/details/gtykunjofw.html

[R54] 比较两个文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgcupupul.html

diff a.txt b.txt
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwllyvelq.html

[R55] 压缩与解压
来源：http://dali.zhengqikj.top/Article/details/gtjmtgzlyw.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.jyoumei.cn/Article/details/gtciehquie.html

[R56] 远程拷贝
来源：http://dali.andypj.xyz/Article/details/gtnzqygpuf.html

scp file user@host:/path/
来源：http://dali.zhongyouzk.top/Article/details/gtnyhxojpc.html

[R57] 远程执行命令
来源：http://dali.nanxinkj.top/Article/details/gtztnshknl.html

ssh user@host 'uptime'
来源：http://dali.aizwys.cn/Article/details/gtjnydsvzg.html

[R58] 下载文件
来源：http://dali.yvedp.cn/Article/details/gtgktfypbo.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.andypj.xyz/Article/details/gtucjrrqld.html

[R59] 发 POST JSON
来源：http://dali.chenlongwang.top/Article/details/gtpeudhnpw.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.jinyuanbaomall.cn/Article/details/gttlyhrucy.html

[R60] 只看 HTTP 状态码
来源：http://dali.gogol.net.cn/Article/details/gtkojwwtsz.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.haohaochexian.top/Article/details/gtrobnadnq.html

[R61] 磁盘占用
来源：http://dali.yanxiufei.cn/Article/details/gtjwcfqhaf.html

df -h;  du -sh *
来源：http://dali.redwolf501.top/Article/details/gtuyezkrov.html

[R62] 找最占空间的文件
来源：http://dali.yj202588.top/Article/details/gtaalswmhc.html

du -ah . | sort -rh | head -10
来源：http://dali.wangshuangyany.cn/Article/details/gtuozhfjli.html

[R63] 内存与进程
来源：http://dali.aizwys.cn/Article/details/gtfptbecuk.html

free -h;  ps aux | grep nginx
来源：http://dali.tian-w.cn/Article/details/gtmhfvhkrb.html

[R64] 结束进程
来源：http://dali.shzxlz.cn/Article/details/gtwvetujrl.html

kill -9 $(pgrep -f app.py)
来源：http://dali.birdmap.top/Article/details/gtfyneogge.html

[R65] 查看端口占用
来源：http://dali.chenjidiqi.icu/Article/details/gtdvhqcvnc.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.0kj1m.cn/Article/details/gtwjmchhho.html

[R66] 定时任务
来源：http://dali.birdmap.top/Article/details/gtykotundt.html

crontab -e;  crontab -l
来源：http://dali.yj20258.top/Article/details/gtkkutmoar.html

[R67] 生成随机十六进制串
来源：http://dali.cashguo.top/Article/details/gttmrcdvsf.html

openssl rand -hex 16
来源：http://dali.cdnleiting.top/Article/details/gtikzndsue.html

[R68] 计算文件校验值
来源：http://dali.yvedp.cn/Article/details/gtpbbbsvza.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.sufxvd.cn/Article/details/gtyhsaafpr.html

[R69] 生成随机密码
来源：http://dali.kuanghao11.cn/Article/details/gtbqnaenxx.html

head -c 16 /dev/urandom | base64
来源：http://dali.pycfn.com/Article/details/gttujklgcf.html

[R70] 时间戳与互转
来源：http://dali.bjfxy.top/Article/details/gtdozxbpkd.html

date +%s;  date -d @1700000000
来源：http://dali.aizwys.cn/Article/details/gtniwvabmu.html

[R71] 日期格式化
来源：http://dali.jyoumei.cn/Article/details/gtcbzhmwxz.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.cheryme.top/Article/details/gtclwxvrez.html

[R72] 等待端口就绪
来源：http://dali.zycfv.cn/Article/details/gtnuqbpmfj.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zycfv.cn/Article/details/gtqslrrpyr.html

[R73] 分割大日志
来源：http://dali.zhoulong.xyz/Article/details/gtqmvpzahc.html


<!-- 参考信息 -->