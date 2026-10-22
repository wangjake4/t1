代发 wailian999

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhiwuduotai.top/Article/details/gtgxsupppa.html

[Q26] 计数
来源：http://dali.cdnleiting.top/Article/details/gtqqyyoeyk.html

SELECT COUNT(*) FROM users;
来源：http://dali.yueranfly.top/Article/details/gtwzkfnqdh.html

[Q27] 条件计数
来源：http://dali.cdnleiting.top/Article/details/gtfdyutvzn.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzovxdjtp.html

[Q28] 求和与平均
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkaaxyaaw.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.ybcxt.top/Article/details/gtshvelixp.html

[Q29] 最大最小值
来源：http://dali.xuetiantiany.cn/Article/details/gtnmfgiref.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.jinqigufen.top/Article/details/gtilwqyewt.html

[Q30] 分组统计
来源：http://dali.yangfankeji.com/Article/details/gtcxhvdgtj.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvsxlvprq.html

[Q31] 分组后过滤
来源：http://dali.chenjidiqi.icu/Article/details/gteidqnott.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.ydzc1.top/Article/details/gtqtjsldaj.html

[Q32] 分组拼接字符串
来源：http://dali.havefunace.top/Article/details/gtfokmgfmu.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.wangdashe.top/Article/details/gtolawmbmd.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.hongshengwenyu.top/Article/details/gtcpdgetbo.html

[Q33] 多列分组
来源：http://dali.ivvv.top/Article/details/gtxmwnkjbz.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.hfpthk.cn/Article/details/gttrepcuwr.html

[Q34] 每组取第一条
来源：http://dali.feifeiyinyue.top/Article/details/gthrdunfkv.html

SELECT * FROM (
来源：http://dali.haohaochexian.top/Article/details/gtbnnpqftg.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.sxryk.cn/Article/details/gtrrvofgch.html

) t WHERE rn = 1;
来源：http://dali.fengsongda.top/Article/details/gtesrndyoe.html

[Q35] 内连接
来源：http://dali.feifeiyinyue.top/Article/details/gtuvfcglbq.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.tanke756.top/Article/details/gtbbzrzcvi.html

[Q36] 左连接
来源：http://dali.zhixingplan.top/Article/details/gtxkdnjumf.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.gzhubu.top/Article/details/gtauawjcko.html

[Q37] 右连接
来源：http://dali.tianlin.xyz/Article/details/gtnxqgfwbl.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.hywenlv.cn/Article/details/gtkvunwkuk.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.jinghuilouyu.cn/Article/details/gtruyredld.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.hnxiangtu.top/Article/details/gtlufmduds.html

[Q39] 自连接（查上下级）
来源：http://dali.vqdsnc.cn/Article/details/gtztzjhotz.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.yuanzhike.top/Article/details/gtlmmqjbem.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.9152youxi.cn/Article/details/gtjciqpabn.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.jianghu66.top/Article/details/gtamnpswuv.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.xuetiantiany.cn/Article/details/gtonwqovwk.html

[Q41] 多表连接
来源：http://dali.ppjwa.cn/Article/details/gtweplxbzr.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhengqikj.top/Article/details/gtfyuonqeg.html

JOIN users u ON u.id = o.user_id
来源：http://dali.smart0.xyz/Article/details/gticaequfu.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.xuetiantiany.cn/Article/details/gtoxwxvgkq.html

[Q42] 连接条件附加过滤
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcmfsfazg.html

SELECT u.name, o.amount FROM users u
来源：http://dali.jqgufenzy.top/Article/details/gtvqwuirss.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.xinyue.icu/Article/details/gtrsjuattg.html

[Q43] 标量子查询
来源：http://dali.vqdsnc.cn/Article/details/gtaolvpzdw.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.shangyingyoupin.top/Article/details/gtzqtzwtwo.html

[Q44] IN 子查询
来源：http://dali.ppjwa.cn/Article/details/gtjruhuhbd.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.nanxuanxn.top/Article/details/gtsokfyfql.html

[Q45] EXISTS 判断存在
来源：http://dali.shanyushiyangtech.top/Article/details/gtmgjyibhs.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.iojbl.cn/Article/details/gtmkvplgpz.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.guowangkeji.top/Article/details/gtskouzjus.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.gogol.net.cn/Article/details/gtezeoknxe.html

[Q47] 与平均值比较
来源：http://dali.xinyue.icu/Article/details/gtrhsliaya.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.yj20258888.top/Article/details/gtjqdeuign.html

[Q48] CTE 公用表表达式
来源：http://dali.hnqzz.top/Article/details/gtmatmybxa.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.c1oappe.top/Article/details/gtkfypqqpx.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.9152youxi.cn/Article/details/gtdyxoxfwz.html

[Q49] 更新单行
来源：http://dali.iojbl.cn/Article/details/gtkfaxkhof.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcvhgpuaq.html

[Q50] 批量更新
来源：http://dali.xuanzx.com/Article/details/gteljlsafq.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.snrcjt.cn/Article/details/gtuosmwpdn.html

[Q51] 用子查询更新
来源：http://dali.tian-w.cn/Article/details/gtxrtgnxlc.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.chenjidiqi.icu/Article/details/gtylwnnkej.html

[Q52] 删除指定行
来源：http://dali.iojbl.cn/Article/details/gtgkpcoans.html

DELETE FROM users WHERE id = 10;
来源：http://dali.iojbl.cn/Article/details/gtyhslrhfn.html

[Q53] 按条件删除
来源：http://dali.sufxvd.cn/Article/details/gtthxntgpg.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwqfigzfw.html

[Q54] 清空表
来源：http://dali.sufxvd.cn/Article/details/gtwympkgfd.html

TRUNCATE TABLE logs;
来源：http://dali.hfpthk.cn/Article/details/gtvxbzpqeb.html

[Q55] 排名（并列占位）
来源：http://dali.pengpengdd.cyou/Article/details/gtosgigmvf.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.hammf.cn/Article/details/gtqpfmexhl.html

[Q56] 密集排名（并列不占位）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtertiifrn.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.yvedp.cn/Article/details/gtsbhpzlbp.html

[Q57] 行号
来源：http://dali.cdnleiting.top/Article/details/gtjyfchuwv.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.wangdashe.top/Article/details/gtwfsmtqoe.html

[Q58] 累计求和
来源：http://dali.jinqigufen.top/Article/details/gtwthfvkyy.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuxwmfhbq.html

[Q59] 分组内累计
来源：http://dali.gaohongyu789.top/Article/details/gtjrushffp.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.ybcxt.top/Article/details/gtyolcarxh.html

[Q60] 取上一行 / 下一行
来源：http://dali.yuxming.cn/Article/details/gtnkrkdhfm.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.ybcxt.top/Article/details/gtswdbwadw.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.vqdsnc.cn/Article/details/gtsuskmwmd.html

[Q61] 移动平均
来源：http://dali.mhx1999.top/Article/details/gtnxfuzwgl.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.havefunace.top/Article/details/gthdyclktx.html

[Q62] 分组占比
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdbgsaprb.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.hnqzz.top/Article/details/gtofdwtaja.html

[Q63] 开启事务
来源：http://dali.316326.xyz/Article/details/gtocekozbb.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.snrcjt.cn/Article/details/gtcoamchqf.html

[Q64] 提交事务
来源：http://dali.bjfxy.top/Article/details/gtejiejyjy.html

COMMIT;
来源：http://dali.wangshuangyany.cn/Article/details/gtjruhzcit.html

[Q65] 回滚事务
来源：http://dali.hnqzz.top/Article/details/gtawvfuxhp.html

ROLLBACK;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwtrfjtdd.html

[Q66] 行锁查询
来源：http://dali.zhaomingkeji.xyz/Article/details/gtajvovhcf.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.hywenlv.cn/Article/details/gtzsgegsmc.html

[Q67] 设置隔离级别
来源：http://dali.ybcxt.top/Article/details/gtxzuhsmyk.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.hnqzz.top/Article/details/gtkqeurpnv.html

[Q68] 保存点
来源：http://dali.jqgufenzy.top/Article/details/gtoukbumua.html

SAVEPOINT sp1;
来源：http://dali.cheryme.top/Article/details/gtsnxejkap.html

ROLLBACK TO sp1;
来源：http://dali.gzhubu.top/Article/details/gtlgainnsd.html

[Q69] 查看执行计划
来源：http://dali.fengsongda.top/Article/details/gtkqdlqnug.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.jiagoushi.top/Article/details/gtumpceanu.html

[Q70] 更新统计信息
来源：http://dali.chenzaomai.com/Article/details/gtvrqeaqaq.html

ANALYZE TABLE users;
来源：http://dali.hnqzz.top/Article/details/gtsphsckbj.html

[Q71] 查看建表语句
来源：http://dali.mhx1999.top/Article/details/gtulvijktv.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.feifeiyinyue.top/Article/details/gtfokjcdse.html

[Q72] 查看索引
来源：http://dali.chenlongwang.top/Article/details/gtidhdpkdv.html

SHOW INDEX FROM users;
来源：http://dali.mhx1999.top/Article/details/gtajxqvseh.html

[Q73] 查看表状态
来源：http://dali.shuidangran.top/Article/details/gtvcailkiw.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.wangdashe.top/Article/details/gtnldgnuqn.html

[Q74] 强制使用索引
来源：http://dali.chenjidiqi.icu/Article/details/gtkazbbofz.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.snrcjt.cn/Article/details/gtsgkiozkq.html

[Q75] 日期格式化
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtozecpkyx.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.havefunace.top/Article/details/gtdcpculub.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.nwbrower.top/Article/details/gtvojlatrt.html

[Q76] 按天统计
来源：http://dali.jqgfzy.top/Article/details/gtbbdlgksf.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.nwbrower.top/Article/details/gtpgjhanyp.html

[Q77] 时间加减
来源：http://dali.hnxiangtu.top/Article/details/gtbmhirhjn.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.smart0.xyz/Article/details/gtqgqeehvt.html

[Q78] 当前时间
来源：http://dali.wangdashe.top/Article/details/gteqqkvvgu.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.svipenyu.cn/Article/details/gtsexeilnh.html

[Q79] 字符串拼接
来源：http://dali.tian-w.cn/Article/details/gtuqdevpcp.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.hammf.cn/Article/details/gtmgzdypni.html

[Q80] 字符串截取
来源：http://dali.guannengcc.top/Article/details/gtgrdvsnzt.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.svipenyu.cn/Article/details/gtmwlvyysp.html

[Q81] 字符串替换
来源：http://dali.birdmap.top/Article/details/gtndgpbdpg.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.aizwys.cn/Article/details/gtvwwwsarz.html

[Q82] 字符长度与字节长度
来源：http://dali.chenzaomai.com/Article/details/gtgwqruhqh.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.yongpay.top/Article/details/gtyopsqirk.html

[Q83] 大小写转换
来源：http://dali.yuanzhike.top/Article/details/gtpokcgqsk.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.chenjidiqi.icu/Article/details/gtofiijhnq.html

[Q84] 去除首尾空格
来源：http://dali.andypj.xyz/Article/details/gtzlcfiupj.html

SELECT TRIM(name) FROM users;
来源：http://dali.wangshuangyany.cn/Article/details/gtebkortds.html

[Q85] 数值取整
来源：http://dali.daria6918.cn/Article/details/gtkrvuenqw.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.feifeiyinyue.top/Article/details/gtzqclpgiq.html

[Q86] 读取 JSON 字段
来源：http://dali.jqgfzy.top/Article/details/gtnwsflntk.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.sysykeji.top/Article/details/gtrynigxnv.html

[Q87] JSON 字段做条件
来源：http://dali.kuanghao11.cn/Article/details/gtrswkszwn.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.pengpengdd.cyou/Article/details/gtanstwjeb.html

[Q88] 行转列（条件聚合）
来源：http://dali.hysaishi.cn/Article/details/gtnxfxlrgc.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhongyouzk.top/Article/details/gtvjecthrc.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.sweek.top/Article/details/gtfvfhhmfz.html

[Q89] 判断表是否存在
来源：http://dali.zycfv.cn/Article/details/gtkiaypanu.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.jlsjyb.cn/Article/details/gtyyrnscnj.html

[Q90] 生成序号列
来源：http://dali.yj202588.top/Article/details/gtqhxoevlw.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.yangfankeji.com/Article/details/gtheizlyek.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtcinhvlcj.html

R. Bash 专题
来源：http://dali.zhengqikj.top/Article/details/gtlglineqt.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gteqntsfkz.html

[R01] shebang 与严格模式
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgynnzrjr.html

#!/usr/bin/env bash
来源：http://dali.yanxiufei.cn/Article/details/gtuhgyxlvx.html

set -euo pipefail
来源：http://dali.zhengqikj.top/Article/details/gtbfzbizty.html

[R02] 变量赋值与使用
来源：http://dali.guowangkeji.top/Article/details/gtjnhetyka.html

name="Tom"; echo "$name"
来源：http://dali.hnxiangtu.top/Article/details/gtlkgsbfvm.html

[R03] 只读变量
来源：http://dali.cheryme.top/Article/details/gtvctgvbcf.html

readonly PI=3.14
来源：http://dali.redwolf501.top/Article/details/gtggkonehp.html

[R04] 位置参数
来源：http://dali.zycfv.cn/Article/details/gtypteupsr.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.jinqigfzy.top/Article/details/gtjrxugaxr.html

[R05] 参数默认值
来源：http://dali.jiagoushi.top/Article/details/gtwnahjgai.html

name="${1:-default}"
来源：http://dali.nanxuanxn.top/Article/details/gtuiwpyrey.html

[R06] 判断命令是否存在
来源：http://dali.dianchejie.cn/Article/details/gtvnzhjnxw.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.birdmap.top/Article/details/gtpscdpapm.html

[R07] if 判断文件
来源：http://dali.zhoulong.xyz/Article/details/gtpwkbjpeh.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzwhsjjmt.html

[R08] 数值比较
来源：http://dali.ydzc1.top/Article/details/gtwfuwtzlg.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.ydzc1.top/Article/details/gtprkftrbl.html

[R09] 字符串比较
来源：http://dali.gotoacloud.top/Article/details/gtrinibiip.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.tanke756.top/Article/details/gtsvcrdhrs.html

[R10] 正则匹配
来源：http://dali.nwbrower.top/Article/details/gtscgjpizz.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.hywenlv.cn/Article/details/gtwedhlihx.html

[R11] case 多分支
来源：http://dali.guowangkeji.top/Article/details/gtbszkmzur.html

case "$1" in
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnpdqebuv.html

start) echo "启动" ;;
来源：http://dali.chenjidiqi.icu/Article/details/gtniothezf.html

stop)  echo "停止" ;;
来源：http://dali.sufxvd.cn/Article/details/gtsmaoyeal.html

*)     echo "未知命令" ;;
来源：http://dali.wangshuangyany.cn/Article/details/gtvscgazej.html

esac
来源：http://dali.yuxming.cn/Article/details/gtmnwwrhkt.html

[R12] for 遍历文件
来源：http://dali.haohaochexian.top/Article/details/gtjpolnyqe.html

for f in *.txt; do echo "$f"; done
来源：http://dali.sweek.top/Article/details/gteiqnmtoz.html

[R13] for 计数循环
来源：http://dali.fengsongda.top/Article/details/gtwpenyaaw.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.meibo888.top/Article/details/gtnsonwamx.html

[R14] C 风格 for
来源：http://dali.tian-w.cn/Article/details/gtwshnblkr.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.yuanzhike.top/Article/details/gtxgdmxakw.html

[R15] while 逐行读文件
来源：http://dali.yueranfly.top/Article/details/gtmnsglafz.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.shanyushiyangtech.top/Article/details/gtpcvkqwwz.html

[R16] until 等待条件
来源：http://dali.xinyue.icu/Article/details/gtizonuyrh.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.jiagoushi.top/Article/details/gthhopiptz.html

[R17] 数组定义与取值
来源：http://dali.quarkkingdee.top/Article/details/gtncpzmkld.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.ydzc1.top/Article/details/gtrjyqbkbb.html

[R18] 遍历数组
来源：http://dali.hongshengwenyu.top/Article/details/gtegqicaob.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.tian-w.cn/Article/details/gtelguzmke.html

[R19] 数组长度
来源：http://dali.cashguo.top/Article/details/gttsbjrmie.html

echo "${#arr[@]}"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcnypcjvc.html

[R20] 关联数组（字典）
来源：http://dali.nanxinkj.top/Article/details/gtzpltlene.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.pengpengdd.cyou/Article/details/gtpbbrtlna.html

[R21] 字符串长度
来源：http://dali.cqqwz.cn/Article/details/gtlldbcxhz.html

echo "${#s}"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdrscmgdn.html

[R22] 截取子串
来源：http://dali.zycfv.cn/Article/details/gtdvjwjzfl.html

echo "${s:0:5}"
来源：http://dali.zdqjudy.top/Article/details/gtqbkkclsg.html

[R23] 字符串替换
来源：http://dali.jinqigfzy.top/Article/details/gtmvkxtyoe.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gtwilbkvmi.html

[R24] 大小写转换
来源：http://dali.cqqwz.cn/Article/details/gtwwnkpkky.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.jinghuilouyu.cn/Article/details/gthmdzmuld.html

[R25] 去后缀 / 去前缀
来源：http://dali.xylfe.cn/Article/details/gtiysaufxo.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.quarkkingdee.top/Article/details/gtofgkibsn.html

[R26] 命令替换
来源：http://dali.pycfn.com/Article/details/gtdjjqnpcd.html

now=$(date +%F); echo "$now"
来源：http://dali.zhongyouzk.top/Article/details/gtbmkqobsn.html

[R27] 算术展开
来源：http://dali.iojbl.cn/Article/details/gtlrkwohlp.html

echo $((1 + 2 * 3))
来源：http://dali.havefunace.top/Article/details/gttirabdbl.html

[R28] 浮点运算
来源：http://dali.smart0.xyz/Article/details/gtjstqxgic.html

echo "scale=2; 10/3" | bc
来源：http://dali.yvedp.cn/Article/details/gtganzajbv.html

[R29] 定义函数
来源：http://dali.iojbl.cn/Article/details/gtnvtomeqh.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.yongpay.top/Article/details/gtqbfcyfzp.html

[R30] 函数返回状态码
来源：http://dali.zhoulong.xyz/Article/details/gtcvpyzuww.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.jyoumei.cn/Article/details/gtkhwsyuqt.html

[R31] 局部变量
来源：http://dali.yonumen.top/Article/details/gtbjjxkqlj.html

f() { local x=1; echo "$x"; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtawmccgdf.html

[R32] 参数个数校验
来源：http://dali.ivvv.top/Article/details/gtlpfwxzie.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.jiagoushi.top/Article/details/gthdnoarvs.html

[R33] 捕获错误并提示行号
来源：http://dali.feifeiyinyue.top/Article/details/gtawdgmtam.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.pengpengdd.cyou/Article/details/gtedaoxxdj.html

[R34] 退出时清理
来源：http://dali.gzhubu.top/Article/details/gtcoybjhtj.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.jianghu66.top/Article/details/gtgilwovob.html

[R35] 后台执行并等待
来源：http://dali.jyoumei.cn/Article/details/gtudyhpdnl.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.pengpengdd.cyou/Article/details/gtojhcpzhd.html

[R36] 并发执行多个任务
来源：http://dali.chenjidiqi.icu/Article/details/gtjcwsnjfr.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.smart0.xyz/Article/details/gtrvsittss.html

[R37] 把输出赋给变量
来源：http://dali.xylfe.cn/Article/details/gtudmczctc.html

files=$(ls -1)
来源：http://dali.jlsjyb.cn/Article/details/gttmqluukh.html

[R38] 管道串联
来源：http://dali.jinqigufen.top/Article/details/gtzvquwdhf.html

cat a.txt | grep -i error | wc -l
来源：http://dali.svipenyu.cn/Article/details/gtpcjjnrtu.html

[R39] 重定向标准输出与错误
来源：http://dali.fzhhl.top/Article/details/gtnkcvzgvw.html

cmd > out.log 2>&1
来源：http://dali.xuetiantiany.cn/Article/details/gttkxhjllz.html

[R40] 追加写日志
来源：http://dali.pengpengdd.cyou/Article/details/gtrwtlrhmd.html

echo "log" >> out.log
来源：http://dali.yanxiufei.cn/Article/details/gtqftqfnio.html

[R41] 丢弃输出
来源：http://dali.0kj1m.cn/Article/details/gtjagfstzj.html

cmd >/dev/null 2>&1
来源：http://dali.316326.xyz/Article/details/gtrtfvybrj.html

[R42] 输入重定向
来源：http://dali.wangdashe.top/Article/details/gtqyocpdou.html

wc -l < a.txt
来源：http://dali.shzxlz.cn/Article/details/gthsvefyyq.html

[R43] 按名字查找文件
来源：http://dali.yuanzhike.top/Article/details/gtwxctcixu.html

find . -name "*.log" -type f
来源：http://dali.0kj1m.cn/Article/details/gtxwvzodlm.html

[R44] 按修改时间查找
来源：http://dali.cucudq.cn/Article/details/gtnxxduzqx.html

find . -mtime -7 -type f
来源：http://dali.yanxiufei.cn/Article/details/gtvemzdeps.html

[R45] 批量删除
来源：http://dali.xinyue.icu/Article/details/gtifvyqonw.html

find . -name "*.tmp" -delete
来源：http://dali.hongshengwenyu.top/Article/details/gtsxxblkuk.html

[R46] 递归替换文件内容
来源：http://dali.chenjidiqi.icu/Article/details/gtypiudefe.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.pycfn.com/Article/details/gtzwzoywhs.html

[R47] sed 单行替换
来源：http://dali.zycfv.cn/Article/details/gtqzeqzhue.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.birdmap.top/Article/details/gtdqucvdzp.html

[R48] awk 取指定列
来源：http://dali.shanyushiyangtech.top/Article/details/gtyoawcnvp.html

awk '{print $1, $3}' a.txt
来源：http://dali.guannengcc.top/Article/details/gtufgczvmw.html

[R49] awk 带条件
来源：http://dali.xuanzx.com/Article/details/gtrgvdettc.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.cashguo.top/Article/details/gtuyexstvr.html

[R50] awk 求和
来源：http://dali.birdmap.top/Article/details/gtrwgakerm.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.hammf.cn/Article/details/gtrwradyhy.html

[R51] 排序去重取前几
来源：http://dali.quarkkingdee.top/Article/details/gtqerknjuj.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.yanxiufei.cn/Article/details/gtdrejoycy.html

[R52] 统计行数
来源：http://dali.chenjidiqi.icu/Article/details/gtvxfodbdg.html

wc -l a.txt
来源：http://dali.zhiwuduotai.top/Article/details/gtrtlvwshf.html

[R53] 查看文件头与实时尾
来源：http://dali.xuanzx.com/Article/details/gtiojsftpz.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.vqdsnc.cn/Article/details/gtfpodmlhq.html

[R54] 比较两个文件
来源：http://dali.svipenyu.cn/Article/details/gtdpyblxjw.html

diff a.txt b.txt
来源：http://dali.cashguo.top/Article/details/gtymdwghkc.html

[R55] 压缩与解压
来源：http://dali.tianlin.xyz/Article/details/gtzctkwhxz.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.chenjidiqi.icu/Article/details/gtefznvysk.html

[R56] 远程拷贝
来源：http://dali.aibaodan.cn/Article/details/gtdymgigif.html

scp file user@host:/path/
来源：http://dali.andypj.xyz/Article/details/gtuxppjpfp.html

[R57] 远程执行命令
来源：http://dali.wangdashe.top/Article/details/gtvhqngbte.html

ssh user@host 'uptime'
来源：http://dali.andypj.xyz/Article/details/gtdwscoyxp.html

[R58] 下载文件
来源：http://dali.xylfe.cn/Article/details/gtzuhawnpr.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.cheryme.top/Article/details/gtkfucqfos.html

[R59] 发 POST JSON
来源：http://dali.cdnleiting.top/Article/details/gtnwuxeiml.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhongyouzk.top/Article/details/gthutjhozx.html

[R60] 只看 HTTP 状态码
来源：http://dali.birdmap.top/Article/details/gtppzdbwpd.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.chenlongwang.top/Article/details/gtqwytndfq.html

[R61] 磁盘占用
来源：http://dali.yueranfly.top/Article/details/gtytearnab.html

df -h;  du -sh *
来源：http://dali.ivvv.top/Article/details/gtsdhreovu.html

[R62] 找最占空间的文件
来源：http://dali.yvedp.cn/Article/details/gtpjgydkhv.html

du -ah . | sort -rh | head -10
来源：http://dali.tanke756.top/Article/details/gtnoyzujdr.html

[R63] 内存与进程
来源：http://dali.cdnleiting.top/Article/details/gtoavqwkiv.html

free -h;  ps aux | grep nginx
来源：http://dali.jiagoushi.top/Article/details/gtsqyolbyd.html

[R64] 结束进程
来源：http://dali.zhiwuduotai.top/Article/details/gtwrcdiklx.html

kill -9 $(pgrep -f app.py)
来源：http://dali.xinyue.icu/Article/details/gtvbgwjubu.html

[R65] 查看端口占用
来源：http://dali.yj202588.top/Article/details/gtbnfzojah.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.dianchejie.cn/Article/details/gtxcnlmkli.html

[R66] 定时任务
来源：http://dali.shuidangran.top/Article/details/gtwwxghoqv.html

crontab -e;  crontab -l
来源：http://dali.jiagoushi.top/Article/details/gtlprxrgej.html

[R67] 生成随机十六进制串
来源：http://dali.shuidangran.top/Article/details/gtwcsngzkx.html

openssl rand -hex 16
来源：http://dali.yueranfly.top/Article/details/gtmmdhmtqw.html

[R68] 计算文件校验值
来源：http://dali.yueranfly.top/Article/details/gtggwkbbwo.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdsyyprby.html

[R69] 生成随机密码
来源：http://dali.havefunace.top/Article/details/gtsihndiyh.html

head -c 16 /dev/urandom | base64
来源：http://dali.jqgufenzy.top/Article/details/gtssltqrtb.html

[R70] 时间戳与互转
来源：http://dali.iojbl.cn/Article/details/gtiqzhbihh.html

date +%s;  date -d @1700000000
来源：http://dali.wangdashe.top/Article/details/gtkwwdgmma.html

[R71] 日期格式化
来源：http://dali.zhixingplan.top/Article/details/gtpgjuynay.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.hnxiangtu.top/Article/details/gttzsrwbzr.html

[R72] 等待端口就绪
来源：http://dali.zdqjudy.top/Article/details/gtzrtzaopx.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.hnxiangtu.top/Article/details/gtkdlvsklb.html

[R73] 分割大日志
来源：http://dali.tianlin.xyz/Article/details/gtokdyoswe.html

split -l 1000 big.log part_
来源：http://dali.c1oappe.top/Article/details/gtyqtshcrd.html

[R74] 批量重命名
来源：http://dali.yvedp.cn/Article/details/gtddmqohzc.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.yanxiufei.cn/Article/details/gtbvkrccyi.html

[R75] 导出环境变量
来源：http://dali.wangdashe.top/Article/details/gtflgkvyac.html


<!-- 参考信息 -->