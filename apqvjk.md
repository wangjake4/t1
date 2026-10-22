代发 wailian999

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.yuanzhike.top/Article/details/gtmwuvmwat.html

[Q28] 求和与平均
来源：http://dali.nanxinkj.top/Article/details/gteiccziqc.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.hywenlv.cn/Article/details/gtallxukht.html

[Q29] 最大最小值
来源：http://dali.hywenlv.cn/Article/details/gttyeoyhyk.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.daxiang520.top/Article/details/gtjlqhnceh.html

[Q30] 分组统计
来源：http://dali.hammf.cn/Article/details/gtizhtuquc.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zycfv.cn/Article/details/gtnnciodwl.html

[Q31] 分组后过滤
来源：http://dali.pengpengdd.cyou/Article/details/gtihgkomkh.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.sysykeji.top/Article/details/gtufxwawcn.html

[Q32] 分组拼接字符串
来源：http://dali.birdmap.top/Article/details/gtvgeblngw.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.pycfn.com/Article/details/gtwwwrrfck.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhengqikj.top/Article/details/gtzlthhwyd.html

[Q33] 多列分组
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzwpzlstq.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.nanxinkj.top/Article/details/gtztkjcnyd.html

[Q34] 每组取第一条
来源：http://dali.c1oappe.top/Article/details/gteooztnjb.html

SELECT * FROM (
来源：http://dali.snrcjt.cn/Article/details/gtpxppukxn.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.cqqwz.cn/Article/details/gtnpjrpecl.html

) t WHERE rn = 1;
来源：http://dali.haohaochexian.top/Article/details/gtvfdrqbga.html

[Q35] 内连接
来源：http://dali.gzhubu.top/Article/details/gtdysbcnmf.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhixingplan.top/Article/details/gtfaqiakmt.html

[Q36] 左连接
来源：http://dali.yj20258888.top/Article/details/gtgnmwxday.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.aibaodan.cn/Article/details/gtckyiynco.html

[Q37] 右连接
来源：http://dali.zhixingplan.top/Article/details/gtwerrirda.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.daxiang520.top/Article/details/gtbdhdqhcr.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.yj20258888.top/Article/details/gtryzanqrr.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.gzhubu.top/Article/details/gtbieggmrt.html

[Q39] 自连接（查上下级）
来源：http://dali.chenjidiqi.icu/Article/details/gtfihqyxsi.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.316326.xyz/Article/details/gtjyfbvocm.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhiwuduotai.top/Article/details/gtnegasquj.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlhdzveil.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.jqgfzy.top/Article/details/gtagghfcyb.html

[Q41] 多表连接
来源：http://dali.sufxvd.cn/Article/details/gtfvxvshlu.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.havefunace.top/Article/details/gtwnzndmlk.html

JOIN users u ON u.id = o.user_id
来源：http://dali.hysaishi.cn/Article/details/gtnkdsffsl.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.cqqwz.cn/Article/details/gtfvqewnax.html

[Q42] 连接条件附加过滤
来源：http://dali.hywenlv.cn/Article/details/gtyuosnibt.html

SELECT u.name, o.amount FROM users u
来源：http://dali.0kj1m.cn/Article/details/gtfwtmzwjb.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhiwuduotai.top/Article/details/gtwfzzbdvi.html

[Q43] 标量子查询
来源：http://dali.aizwys.cn/Article/details/gtipzemqph.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.daria6918.cn/Article/details/gtjibbgqui.html

[Q44] IN 子查询
来源：http://dali.xinyue.icu/Article/details/gtavyksnsp.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.svipenyu.cn/Article/details/gtfqyobdpc.html

[Q45] EXISTS 判断存在
来源：http://dali.xylfe.cn/Article/details/gtxesdwtti.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.gotoacloud.top/Article/details/gtoekefiti.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.0kj1m.cn/Article/details/gtwxdhzlkr.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmbbidlbm.html

[Q47] 与平均值比较
来源：http://dali.gotoacloud.top/Article/details/gtdywbvmot.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.9152youxi.cn/Article/details/gtxheqeegx.html

[Q48] CTE 公用表表达式
来源：http://dali.aibaodan.cn/Article/details/gtwsxsplmq.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.yj202588.top/Article/details/gtowcadvlb.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.gogol.net.cn/Article/details/gtmgzepsbz.html

[Q49] 更新单行
来源：http://dali.sufxvd.cn/Article/details/gtwvfhpohw.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.ehwqpu.com/Article/details/gtudscluxs.html

[Q50] 批量更新
来源：http://dali.hfpthk.cn/Article/details/gtvqslsxws.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.9152youxi.cn/Article/details/gtosoyyqjy.html

[Q51] 用子查询更新
来源：http://dali.aizwys.cn/Article/details/gtvivfjsgc.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.vqdsnc.cn/Article/details/gtpvjdcldq.html

[Q52] 删除指定行
来源：http://dali.haohaochexian.top/Article/details/gtvlygkfwf.html

DELETE FROM users WHERE id = 10;
来源：http://dali.9152youxi.cn/Article/details/gtpzyxoazy.html

[Q53] 按条件删除
来源：http://dali.ivvv.top/Article/details/gtoxayclro.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.xuanzx.com/Article/details/gtnhjunzkl.html

[Q54] 清空表
来源：http://dali.guannengcc.top/Article/details/gtwkycnzjs.html

TRUNCATE TABLE logs;
来源：http://dali.daxiang520.top/Article/details/gtnzmmbkxh.html

[Q55] 排名（并列占位）
来源：http://dali.gaohongyu789.top/Article/details/gtckqhaplk.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.fengsongda.top/Article/details/gtobhovoqi.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zdqjudy.top/Article/details/gtdiccghuq.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.jyoumei.cn/Article/details/gtvcrbfuec.html

[Q57] 行号
来源：http://dali.zhongyouzk.top/Article/details/gtrqbzvzjr.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.fzhhl.top/Article/details/gttuswawho.html

[Q58] 累计求和
来源：http://dali.cucudq.cn/Article/details/gtxhcqvhjj.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.jqgufenzy.top/Article/details/gttqefatpm.html

[Q59] 分组内累计
来源：http://dali.vqdsnc.cn/Article/details/gtmqrxsnhh.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.kuanghao11.cn/Article/details/gtjfijdjyb.html

[Q60] 取上一行 / 下一行
来源：http://dali.guowangkeji.top/Article/details/gtlqvmgrue.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.cashguo.top/Article/details/gtdotvbthd.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.0kj1m.cn/Article/details/gtieweegzb.html

[Q61] 移动平均
来源：http://dali.redwolf501.top/Article/details/gttexfhelu.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.haohaochexian.top/Article/details/gtzzyaveis.html

[Q62] 分组占比
来源：http://dali.jinqigufen.top/Article/details/gtxnruzowv.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtscnylqyf.html

[Q63] 开启事务
来源：http://dali.yangfankeji.com/Article/details/gtnqeyrbap.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.yj20258888.top/Article/details/gtotnbdroz.html

[Q64] 提交事务
来源：http://dali.yuxming.cn/Article/details/gtutvxwean.html

COMMIT;
来源：http://dali.jqgufenzy.top/Article/details/gtpwccnkyi.html

[Q65] 回滚事务
来源：http://dali.zhixingplan.top/Article/details/gtxechougi.html

ROLLBACK;
来源：http://dali.birdmap.top/Article/details/gtxbsprnfa.html

[Q66] 行锁查询
来源：http://dali.sysykeji.top/Article/details/gtcajxfwnh.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.yanxiufei.cn/Article/details/gtlgsjmfph.html

[Q67] 设置隔离级别
来源：http://dali.xylfe.cn/Article/details/gtfjnfkziw.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.smart0.xyz/Article/details/gtucwclkov.html

[Q68] 保存点
来源：http://dali.xuanzx.com/Article/details/gthqsznhse.html

SAVEPOINT sp1;
来源：http://dali.nanxuanxn.top/Article/details/gtpogflkwr.html

ROLLBACK TO sp1;
来源：http://dali.pycfn.com/Article/details/gtngwhsial.html

[Q69] 查看执行计划
来源：http://dali.yongpay.top/Article/details/gtqvhabblm.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.0kj1m.cn/Article/details/gtqtaroxma.html

[Q70] 更新统计信息
来源：http://dali.shanyushiyangtech.top/Article/details/gtapaeexzx.html

ANALYZE TABLE users;
来源：http://dali.daria6918.cn/Article/details/gtaezjynxz.html

[Q71] 查看建表语句
来源：http://dali.yj20258.top/Article/details/gtdacwatmv.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgxumhusu.html

[Q72] 查看索引
来源：http://dali.xziqi.cn/Article/details/gthahnjwpd.html

SHOW INDEX FROM users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwjphqavh.html

[Q73] 查看表状态
来源：http://dali.sufxvd.cn/Article/details/gtjkamdbzd.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.wangshuangyany.cn/Article/details/gtvzlfkhcn.html

[Q74] 强制使用索引
来源：http://dali.cqqwz.cn/Article/details/gthhnzchmg.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.nanxuanxn.top/Article/details/gtkfpdmevw.html

[Q75] 日期格式化
来源：http://dali.ybcxt.top/Article/details/gthcoeeelf.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.cucudq.cn/Article/details/gtvxcqwqfm.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.jianghu66.top/Article/details/gtuubhursp.html

[Q76] 按天统计
来源：http://dali.gaohongyu789.top/Article/details/gtquxcmgko.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.yvedp.cn/Article/details/gtrelwygao.html

[Q77] 时间加减
来源：http://dali.zhiwuduotai.top/Article/details/gtqmyistdj.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.nanxuanxn.top/Article/details/gttpdnhypw.html

[Q78] 当前时间
来源：http://dali.xuetiantiany.cn/Article/details/gtsyubvyxz.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.jyoumei.cn/Article/details/gtiethdxyf.html

[Q79] 字符串拼接
来源：http://dali.9152youxi.cn/Article/details/gtowmsywgr.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.jlsjyb.cn/Article/details/gtxlbitsno.html

[Q80] 字符串截取
来源：http://dali.wangdashe.top/Article/details/gtrayelimu.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.yj20258.top/Article/details/gtxphoqqvy.html

[Q81] 字符串替换
来源：http://dali.andypj.xyz/Article/details/gtdxfepyfx.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.hammf.cn/Article/details/gtsjvuvvvb.html

[Q82] 字符长度与字节长度
来源：http://dali.yuxming.cn/Article/details/gtnglthbar.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.redwolf501.top/Article/details/gtyqpjcdup.html

[Q83] 大小写转换
来源：http://dali.yonumen.top/Article/details/gtxjzaptll.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.jinqigufen.top/Article/details/gtzdbnvhiw.html

[Q84] 去除首尾空格
来源：http://dali.sxryk.cn/Article/details/gtzvrlzogo.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gtsqtxlyjb.html

[Q85] 数值取整
来源：http://dali.nanxinkj.top/Article/details/gtezbzwhsq.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.fzhhl.top/Article/details/gtnrvawoxm.html

[Q86] 读取 JSON 字段
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrwhqrobk.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.nanxinkj.top/Article/details/gtggolisav.html

[Q87] JSON 字段做条件
来源：http://dali.daxiang520.top/Article/details/gtvdiitnpz.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.gogol.net.cn/Article/details/gtexutaxsl.html

[Q88] 行转列（条件聚合）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtydcdhkku.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.ehwqpu.com/Article/details/gtxjznabkv.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.ppjwa.cn/Article/details/gtquglsfxs.html

[Q89] 判断表是否存在
来源：http://dali.gotoacloud.top/Article/details/gtsftybnra.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.shangyingyoupin.top/Article/details/gtywtisgck.html

[Q90] 生成序号列
来源：http://dali.cdnleiting.top/Article/details/gtbbiiniqy.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.yvedp.cn/Article/details/gtsvwwpivn.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtcxgefgtp.html

R. Bash 专题
来源：http://dali.sufxvd.cn/Article/details/gtxjeshorv.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtakvqirhq.html

[R01] shebang 与严格模式
来源：http://dali.yanxiufei.cn/Article/details/gtssaqxoji.html

#!/usr/bin/env bash
来源：http://dali.jinqigfzy.top/Article/details/gtmhveuwot.html

set -euo pipefail
来源：http://dali.feifeiyinyue.top/Article/details/gtmmsrjbor.html

[R02] 变量赋值与使用
来源：http://dali.wangshuangyany.cn/Article/details/gtlpggyxjt.html

name="Tom"; echo "$name"
来源：http://dali.yvedp.cn/Article/details/gtvydstvav.html

[R03] 只读变量
来源：http://dali.cashguo.top/Article/details/gtenybthfq.html

readonly PI=3.14
来源：http://dali.yonumen.top/Article/details/gtdorwkzaq.html

[R04] 位置参数
来源：http://dali.pengpengdd.cyou/Article/details/gtsjdpfjco.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.jinqigfzy.top/Article/details/gtekqiknsy.html

[R05] 参数默认值
来源：http://dali.guowangkeji.top/Article/details/gtbfkccvzb.html

name="${1:-default}"
来源：http://dali.meibo888.top/Article/details/gtqqjhodzu.html

[R06] 判断命令是否存在
来源：http://dali.zhoulong.xyz/Article/details/gthtvrbgay.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.sysykeji.top/Article/details/gthrmynchs.html

[R07] if 判断文件
来源：http://dali.meibo888.top/Article/details/gtayyvssaz.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.kuanghao11.cn/Article/details/gtxnyxkygs.html

[R08] 数值比较
来源：http://dali.shangyingyoupin.top/Article/details/gtiryyhplo.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.andypj.xyz/Article/details/gtrfhtaejq.html

[R09] 字符串比较
来源：http://dali.hfpthk.cn/Article/details/gtyomnrrdg.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.ydzc1.top/Article/details/gtzqgafvsm.html

[R10] 正则匹配
来源：http://dali.shangyingyoupin.top/Article/details/gtqmemwluh.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.aizwys.cn/Article/details/gtejndgrjg.html

[R11] case 多分支
来源：http://dali.jqgfzy.top/Article/details/gtjmpfnwui.html

case "$1" in
来源：http://dali.meibo888.top/Article/details/gtjzdvguwb.html

start) echo "启动" ;;
来源：http://dali.aizwys.cn/Article/details/gtbwbkcpjg.html

stop)  echo "停止" ;;
来源：http://dali.cucudq.cn/Article/details/gtioselrmu.html

*)     echo "未知命令" ;;
来源：http://dali.hnqzz.top/Article/details/gtgtseetur.html

esac
来源：http://dali.snrcjt.cn/Article/details/gtwddfpvoq.html

[R12] for 遍历文件
来源：http://dali.fengsongda.top/Article/details/gttqnfsmps.html

for f in *.txt; do echo "$f"; done
来源：http://dali.chenlongwang.top/Article/details/gttkwgpqqo.html

[R13] for 计数循环
来源：http://dali.cqqwz.cn/Article/details/gtnlvbruez.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.hnqzz.top/Article/details/gtbhmoktke.html

[R14] C 风格 for
来源：http://dali.feifeiyinyue.top/Article/details/gtziqvofhg.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.kuanghao11.cn/Article/details/gtrsgbiobk.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gtqlzmwbnn.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.xuetiantiany.cn/Article/details/gtqhmaqgzc.html

[R16] until 等待条件
来源：http://dali.zdqjudy.top/Article/details/gtyqrvdbfc.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.hnxiangtu.top/Article/details/gtwvkxsask.html

[R17] 数组定义与取值
来源：http://dali.hfpthk.cn/Article/details/gtfbeawbfz.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.cashguo.top/Article/details/gtuloivnxt.html

[R18] 遍历数组
来源：http://dali.hysaishi.cn/Article/details/gtzqtpwnfb.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuelhkjfx.html

[R19] 数组长度
来源：http://dali.aibaodan.cn/Article/details/gtiksvesax.html

echo "${#arr[@]}"
来源：http://dali.ehwqpu.com/Article/details/gtderdmvdu.html

[R20] 关联数组（字典）
来源：http://dali.fengsongda.top/Article/details/gtlvffiazd.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.daria6918.cn/Article/details/gtmdfznptm.html

[R21] 字符串长度
来源：http://dali.bjfxy.top/Article/details/gtoweclmlb.html

echo "${#s}"
来源：http://dali.zycfv.cn/Article/details/gtilfhkaqb.html

[R22] 截取子串
来源：http://dali.yueranfly.top/Article/details/gtneougjnr.html

echo "${s:0:5}"
来源：http://dali.hywenlv.cn/Article/details/gtxmumyxjn.html

[R23] 字符串替换
来源：http://dali.yangfankeji.com/Article/details/gtczgackjv.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.nanxuanxn.top/Article/details/gtjmnjtapz.html

[R24] 大小写转换
来源：http://dali.snrcjt.cn/Article/details/gtvswxknsw.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.cashguo.top/Article/details/gtmkxfagvy.html

[R25] 去后缀 / 去前缀
来源：http://dali.ivvv.top/Article/details/gtkdxtmrvy.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.jinghuilouyu.cn/Article/details/gtjxkskduc.html

[R26] 命令替换
来源：http://dali.tian-w.cn/Article/details/gtdpvpfxsm.html

now=$(date +%F); echo "$now"
来源：http://dali.jqgfzy.top/Article/details/gtdvapaibo.html

[R27] 算术展开
来源：http://dali.jianghu66.top/Article/details/gttfwprpzd.html

echo $((1 + 2 * 3))
来源：http://dali.jyoumei.cn/Article/details/gtycurttsf.html

[R28] 浮点运算
来源：http://dali.cdnleiting.top/Article/details/gtqmwhmznz.html

echo "scale=2; 10/3" | bc
来源：http://dali.316326.xyz/Article/details/gtwespwqqk.html

[R29] 定义函数
来源：http://dali.sweek.top/Article/details/gtagbodtrh.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.jianghu66.top/Article/details/gtcjyyibgw.html

[R30] 函数返回状态码
来源：http://dali.tanke756.top/Article/details/gtwffmuztp.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.guowangkeji.top/Article/details/gtchwktnzy.html

[R31] 局部变量
来源：http://dali.jinqigfzy.top/Article/details/gtnxsanmdi.html

f() { local x=1; echo "$x"; }
来源：http://dali.fengsongda.top/Article/details/gtdwccwtvt.html

[R32] 参数个数校验
来源：http://dali.nwbrower.top/Article/details/gtcvbloslr.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhongyouzk.top/Article/details/gthvxshtxg.html

[R33] 捕获错误并提示行号
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlxhyslng.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.guannengcc.top/Article/details/gtqplqfodq.html

[R34] 退出时清理
来源：http://dali.cqqwz.cn/Article/details/gtwvhavztn.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.hnqzz.top/Article/details/gtwahbflsc.html

[R35] 后台执行并等待
来源：http://dali.hfpthk.cn/Article/details/gtpofhdfnk.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.gogol.net.cn/Article/details/gtzgaxwqeb.html

[R36] 并发执行多个任务
来源：http://dali.hammf.cn/Article/details/gtezndkobr.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.havefunace.top/Article/details/gtpqcledka.html

[R37] 把输出赋给变量
来源：http://dali.daria6918.cn/Article/details/gtkxrvpiyl.html

files=$(ls -1)
来源：http://dali.sxryk.cn/Article/details/gtuwpbnnwb.html

[R38] 管道串联
来源：http://dali.jinqigfzy.top/Article/details/gtaabdkqhj.html

cat a.txt | grep -i error | wc -l
来源：http://dali.yueranfly.top/Article/details/gtlhpbqzqc.html

[R39] 重定向标准输出与错误
来源：http://dali.sxryk.cn/Article/details/gtyaykowmt.html

cmd > out.log 2>&1
来源：http://dali.jyoumei.cn/Article/details/gtpwtxnckh.html

[R40] 追加写日志
来源：http://dali.yanxiufei.cn/Article/details/gtgkpgxlge.html

echo "log" >> out.log
来源：http://dali.smart0.xyz/Article/details/gtpklgbssy.html

[R41] 丢弃输出
来源：http://dali.aibaodan.cn/Article/details/gtdfpxtwoz.html

cmd >/dev/null 2>&1
来源：http://dali.yj202588.top/Article/details/gtlpuwanjg.html

[R42] 输入重定向
来源：http://dali.daxiang520.top/Article/details/gtukvndsuv.html

wc -l < a.txt
来源：http://dali.yueranfly.top/Article/details/gtjrhdgghu.html

[R43] 按名字查找文件
来源：http://dali.sysykeji.top/Article/details/gttktrmoux.html

find . -name "*.log" -type f
来源：http://dali.yj20258888.top/Article/details/gtjprtgrns.html

[R44] 按修改时间查找
来源：http://dali.cashguo.top/Article/details/gtpvuqzped.html

find . -mtime -7 -type f
来源：http://dali.gotoacloud.top/Article/details/gtfsoeqdac.html

[R45] 批量删除
来源：http://dali.cqqwz.cn/Article/details/gtmjvxrnsy.html

find . -name "*.tmp" -delete
来源：http://dali.zhengqikj.top/Article/details/gtawdqrdbp.html

[R46] 递归替换文件内容
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuvcadkjg.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.chenjidiqi.icu/Article/details/gtyrrfqrib.html

[R47] sed 单行替换
来源：http://dali.jyoumei.cn/Article/details/gtiyxvqbec.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.andypj.xyz/Article/details/gtfdkyewze.html

[R48] awk 取指定列
来源：http://dali.dashuyun.cn/Article/details/gtuzylbxyp.html

awk '{print $1, $3}' a.txt
来源：http://dali.dashuyun.cn/Article/details/gtzbdwylfe.html

[R49] awk 带条件
来源：http://dali.gaohongyu789.top/Article/details/gtuutzejvh.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.0kj1m.cn/Article/details/gtlqswotxh.html

[R50] awk 求和
来源：http://dali.dianchejie.cn/Article/details/gtmdpnqyut.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhongyouzk.top/Article/details/gtdwbdkkso.html

[R51] 排序去重取前几
来源：http://dali.jiagoushi.top/Article/details/gtmqamvjqm.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.redwolf501.top/Article/details/gtzrydaucg.html

[R52] 统计行数
来源：http://dali.xuanzx.com/Article/details/gtzixryyqm.html

wc -l a.txt
来源：http://dali.hnxiangtu.top/Article/details/gtwavsmnsf.html

[R53] 查看文件头与实时尾
来源：http://dali.316326.xyz/Article/details/gtgstwmons.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.feifeiyinyue.top/Article/details/gtzroihvbc.html

[R54] 比较两个文件
来源：http://dali.shuidangran.top/Article/details/gtbdkrzhhl.html

diff a.txt b.txt
来源：http://dali.feifeiyinyue.top/Article/details/gtpgteqeon.html

[R55] 压缩与解压
来源：http://dali.cucudq.cn/Article/details/gtayflmyjz.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhoulong.xyz/Article/details/gtcgtqdwhy.html

[R56] 远程拷贝
来源：http://dali.gotoacloud.top/Article/details/gtyhgxdhrv.html

scp file user@host:/path/
来源：http://dali.vqdsnc.cn/Article/details/gtvqwtrrxa.html

[R57] 远程执行命令
来源：http://dali.jiagoushi.top/Article/details/gtnfgknkma.html

ssh user@host 'uptime'
来源：http://dali.jiagoushi.top/Article/details/gtuvwexxvt.html

[R58] 下载文件
来源：http://dali.fzhhl.top/Article/details/gthxmejder.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.vqdsnc.cn/Article/details/gteygxepkn.html

[R59] 发 POST JSON
来源：http://dali.jinghuilouyu.cn/Article/details/gtrmlykbrt.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.cdnleiting.top/Article/details/gtqfgkvygz.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhongyouzk.top/Article/details/gtitfygyup.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.dianchejie.cn/Article/details/gtdppdxcvp.html

[R61] 磁盘占用
来源：http://dali.chenzaomai.com/Article/details/gtxuwgvvnk.html

df -h;  du -sh *
来源：http://dali.zhiwuduotai.top/Article/details/gtljynelpq.html

[R62] 找最占空间的文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtltudxotc.html

du -ah . | sort -rh | head -10
来源：http://dali.yj20258888.top/Article/details/gtvsnoqyux.html

[R63] 内存与进程
来源：http://dali.ppjwa.cn/Article/details/gthbbzrsrn.html

free -h;  ps aux | grep nginx
来源：http://dali.pengpengdd.cyou/Article/details/gtuuchqxhs.html

[R64] 结束进程
来源：http://dali.gotoacloud.top/Article/details/gtqwbbzxjs.html

kill -9 $(pgrep -f app.py)
来源：http://dali.haohaochexian.top/Article/details/gtckavgbli.html

[R65] 查看端口占用
来源：http://dali.daria6918.cn/Article/details/gttezsxxyf.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.vqdsnc.cn/Article/details/gtdnxngzli.html

[R66] 定时任务
来源：http://dali.hnqzz.top/Article/details/gtlobwgryb.html

crontab -e;  crontab -l
来源：http://dali.shzxlz.cn/Article/details/gtcjvyobzo.html

[R67] 生成随机十六进制串
来源：http://dali.0kj1m.cn/Article/details/gthcxykcce.html

openssl rand -hex 16
来源：http://dali.cheryme.top/Article/details/gtlkmodkmh.html

[R68] 计算文件校验值
来源：http://dali.gotoacloud.top/Article/details/gtmlxincet.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.0kj1m.cn/Article/details/gtkrfllher.html

[R69] 生成随机密码
来源：http://dali.birdmap.top/Article/details/gtzonbsjzy.html

head -c 16 /dev/urandom | base64
来源：http://dali.yj202588.top/Article/details/gtezizmkes.html

[R70] 时间戳与互转
来源：http://dali.jlsjyb.cn/Article/details/gtrvngxozn.html

date +%s;  date -d @1700000000
来源：http://dali.redwolf501.top/Article/details/gtahqxgyfz.html

[R71] 日期格式化
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfuqaonab.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.ydzc1.top/Article/details/gtwzwyflyw.html

[R72] 等待端口就绪
来源：http://dali.ybcxt.top/Article/details/gtouhvcoqr.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhengqikj.top/Article/details/gtaohywyuq.html

[R73] 分割大日志
来源：http://dali.shangyingyoupin.top/Article/details/gtfkadvsjv.html

split -l 1000 big.log part_
来源：http://dali.nanxinkj.top/Article/details/gtspknqeab.html

[R74] 批量重命名
来源：http://dali.jinqigufen.top/Article/details/gtedeehaia.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zycfv.cn/Article/details/gtcqhetmhb.html

[R75] 导出环境变量
来源：http://dali.quarkkingdee.top/Article/details/gtrrtdtmme.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.wangshuangyany.cn/Article/details/gtupubjlcg.html

[R76] 使用临时文件
来源：http://dali.sysykeji.top/Article/details/gtzslqiijc.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.guowangkeji.top/Article/details/gtrrdipssv.html

[R77] 读取用户输入
来源：http://dali.kuanghao11.cn/Article/details/gtbvnjglhf.html


<!-- 参考信息 -->