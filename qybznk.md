代发 wailian999

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.nanxinkj.top/Article/details/gt2hoptgbwd.html

[Q32] 分组拼接字符串
来源：http://dali.0kj1m.cn/Article/details/gt2lxjqesof.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.yj20258.top/Article/details/gt2lnlqbraf.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.redwolf501.top/Article/details/gt2uyjlsxcl.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2wmjqsreo.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.ydzc1.top/Article/details/gt2ngmgfvav.html

[Q34] 每组取第一条
来源：http://dali.yvedp.cn/Article/details/gt2kmbmsqvg.html

SELECT * FROM (
来源：http://dali.smart0.xyz/Article/details/gt2kfuxzhdt.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.haohaochexian.top/Article/details/gt2ndgmkjlx.html

) t WHERE rn = 1;
来源：http://dali.jianghu66.top/Article/details/gt2tfoirbjd.html

[Q35] 内连接
来源：http://dali.yj20258888.top/Article/details/gt2lkhjpcds.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhengqikj.top/Article/details/gt2uquoeqbc.html

[Q36] 左连接
来源：http://dali.ppjwa.cn/Article/details/gt2qwnmdkst.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.yonumen.top/Article/details/gt2tbdmcxhd.html

[Q37] 右连接
来源：http://dali.cheryme.top/Article/details/gt2cnxesghr.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.hywenlv.cn/Article/details/gt2mejykyvp.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.quarkkingdee.top/Article/details/gt2lasryznp.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.jinqigufen.top/Article/details/gt2pvxxcuwt.html

[Q39] 自连接（查上下级）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gzrtgktd.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jgzkbkxr.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.yj20258888.top/Article/details/gt2rrmusznx.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.xziqi.cn/Article/details/gt2zvazzzda.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.yongpay.top/Article/details/gt2sgvkvwye.html

[Q41] 多表连接
来源：http://dali.zhixingplan.top/Article/details/gt2mlgvuicr.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.yj20258.top/Article/details/gt2kngtwiuz.html

JOIN users u ON u.id = o.user_id
来源：http://dali.316326.xyz/Article/details/gt2dzmpalvt.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.chenlongwang.top/Article/details/gt2zhwroyya.html

[Q42] 连接条件附加过滤
来源：http://dali.dianchejie.cn/Article/details/gt2iqnztzfa.html

SELECT u.name, o.amount FROM users u
来源：http://dali.jiagoushi.top/Article/details/gt2xhywbpod.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhongyouzk.top/Article/details/gt2rtondgwf.html

[Q43] 标量子查询
来源：http://dali.jinqigufen.top/Article/details/gt2akmpqixy.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.pengpengdd.cyou/Article/details/gt2kviysnrr.html

[Q44] IN 子查询
来源：http://dali.0kj1m.cn/Article/details/gt2ykoeuwvo.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.fengsongda.top/Article/details/gt2wucmnanc.html

[Q45] EXISTS 判断存在
来源：http://dali.wangdashe.top/Article/details/gt2wveehzil.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.ehwqpu.com/Article/details/gt2odewrlqy.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.wangdashe.top/Article/details/gt2shshminr.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.kuanghao11.cn/Article/details/gt2ipkfyvje.html

[Q47] 与平均值比较
来源：http://dali.kuanghao11.cn/Article/details/gt2jhgblsgx.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.gaohongyu789.top/Article/details/gt2nlqfhqzm.html

[Q48] CTE 公用表表达式
来源：http://dali.ehwqpu.com/Article/details/gt2aexxasdo.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.tanke756.top/Article/details/gt2lscjbsxm.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.mhx1999.top/Article/details/gt2cedbbnmo.html

[Q49] 更新单行
来源：http://dali.jianghu66.top/Article/details/gt2abxgifvp.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.yongpay.top/Article/details/gt2uqtywswl.html

[Q50] 批量更新
来源：http://dali.yj202588.top/Article/details/gt2vcmrcpux.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.yj20258.top/Article/details/gt2kjqqrmpy.html

[Q51] 用子查询更新
来源：http://dali.dianchejie.cn/Article/details/gt2ljhxnjou.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhixingplan.top/Article/details/gt2enawkbyu.html

[Q52] 删除指定行
来源：http://dali.zhiwuduotai.top/Article/details/gt2nxzicnzt.html

DELETE FROM users WHERE id = 10;
来源：http://dali.cqqwz.cn/Article/details/gt2lmccrrub.html

[Q53] 按条件删除
来源：http://dali.shzxlz.cn/Article/details/gt2npqxetcm.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.chenjidiqi.icu/Article/details/gt2plyojlxg.html

[Q54] 清空表
来源：http://dali.ydzc1.top/Article/details/gt2lxskccbc.html

TRUNCATE TABLE logs;
来源：http://dali.ivvv.top/Article/details/gt2lgsuvyly.html

[Q55] 排名（并列占位）
来源：http://dali.svipenyu.cn/Article/details/gt2ezlcrrrg.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.hnxiangtu.top/Article/details/gt2jymtyvku.html

[Q56] 密集排名（并列不占位）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fteexeoq.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.sysykeji.top/Article/details/gt2xspqawla.html

[Q57] 行号
来源：http://dali.tianlin.xyz/Article/details/gt2wkqjwnzp.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.nwbrower.top/Article/details/gt2nnbkmlid.html

[Q58] 累计求和
来源：http://dali.sysykeji.top/Article/details/gt2soebpufv.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zdqjudy.top/Article/details/gt2ldnwmqeh.html

[Q59] 分组内累计
来源：http://dali.yonumen.top/Article/details/gt2jhhzbnuo.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.yvedp.cn/Article/details/gt2fzqgjjjt.html

[Q60] 取上一行 / 下一行
来源：http://dali.zdqjudy.top/Article/details/gt2wzctygjd.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.yuanzhike.top/Article/details/gt2rthmgahw.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.316326.xyz/Article/details/gt2gvpuldlc.html

[Q61] 移动平均
来源：http://dali.yj20258888.top/Article/details/gt2zxwavcgc.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.gogol.net.cn/Article/details/gt2ihevpfso.html

[Q62] 分组占比
来源：http://dali.gzhubu.top/Article/details/gt2arheeizr.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.cqqwz.cn/Article/details/gt2hdfwmqte.html

[Q63] 开启事务
来源：http://dali.tanke756.top/Article/details/gt2rgmpcroq.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.mhx1999.top/Article/details/gt2mtimcozd.html

[Q64] 提交事务
来源：http://dali.snrcjt.cn/Article/details/gt2urjhuwsd.html

COMMIT;
来源：http://dali.tianlin.xyz/Article/details/gt2fjpjwypg.html

[Q65] 回滚事务
来源：http://dali.jqgfzy.top/Article/details/gt2levxullr.html

ROLLBACK;
来源：http://dali.zhoulong.xyz/Article/details/gt2hhixwzjg.html

[Q66] 行锁查询
来源：http://dali.jlsjyb.cn/Article/details/gt2vytchvoy.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.sweek.top/Article/details/gt2qvhruqxi.html

[Q67] 设置隔离级别
来源：http://dali.zhengqikj.top/Article/details/gt2ohsepizo.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.tian-w.cn/Article/details/gt2agizoqxd.html

[Q68] 保存点
来源：http://dali.tianlin.xyz/Article/details/gt2kwggyixe.html

SAVEPOINT sp1;
来源：http://dali.sufxvd.cn/Article/details/gt2fjennfiq.html

ROLLBACK TO sp1;
来源：http://dali.guannengcc.top/Article/details/gt2bmibyshc.html

[Q69] 查看执行计划
来源：http://dali.cucudq.cn/Article/details/gt2niofhhtw.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.jqgufenzy.top/Article/details/gt2gbikziay.html

[Q70] 更新统计信息
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2isadunbv.html

ANALYZE TABLE users;
来源：http://dali.jiagoushi.top/Article/details/gt2eiferwqn.html

[Q71] 查看建表语句
来源：http://dali.316326.xyz/Article/details/gt2vwaivecp.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.fzhhl.top/Article/details/gt2sawzrner.html

[Q72] 查看索引
来源：http://dali.nanxinkj.top/Article/details/gt2tayltygy.html

SHOW INDEX FROM users;
来源：http://dali.gotoacloud.top/Article/details/gt2qikloupi.html

[Q73] 查看表状态
来源：http://dali.0kj1m.cn/Article/details/gt2vyhuubem.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.jyoumei.cn/Article/details/gt2otjrmfgz.html

[Q74] 强制使用索引
来源：http://dali.xinyue.icu/Article/details/gt2hslbdusz.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.nwbrower.top/Article/details/gt2viyhyery.html

[Q75] 日期格式化
来源：http://dali.gaohongyu789.top/Article/details/gt2qiopgcug.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhixingplan.top/Article/details/gt2mraurqtw.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.cashguo.top/Article/details/gt2dkfengfr.html

[Q76] 按天统计
来源：http://dali.gogol.net.cn/Article/details/gt2rliwixvw.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.fengsongda.top/Article/details/gt2vjsoekca.html

[Q77] 时间加减
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vcknytzt.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.gzhubu.top/Article/details/gt2esqnlkre.html

[Q78] 当前时间
来源：http://dali.zhoulong.xyz/Article/details/gt2udhyfdja.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.fengsongda.top/Article/details/gt2awobphlx.html

[Q79] 字符串拼接
来源：http://dali.ivvv.top/Article/details/gt2iggcaukx.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.dianchejie.cn/Article/details/gt2ldheyphr.html

[Q80] 字符串截取
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wmpihpmy.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.birdmap.top/Article/details/gt2chbuetjl.html

[Q81] 字符串替换
来源：http://dali.daria6918.cn/Article/details/gt2enbncimc.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.jianghu66.top/Article/details/gt2xzkrrdzg.html

[Q82] 字符长度与字节长度
来源：http://dali.jianghu66.top/Article/details/gt2pbneoqre.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.9152youxi.cn/Article/details/gt2mqxizpmq.html

[Q83] 大小写转换
来源：http://dali.meibo888.top/Article/details/gt2qopdqibd.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.wangshuangyany.cn/Article/details/gt2eekyuash.html

[Q84] 去除首尾空格
来源：http://dali.yvedp.cn/Article/details/gt2zeqnugav.html

SELECT TRIM(name) FROM users;
来源：http://dali.9152youxi.cn/Article/details/gt2tvywdtdd.html

[Q85] 数值取整
来源：http://dali.yuanzhike.top/Article/details/gt2lvsgqnim.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhengqikj.top/Article/details/gt2mpruxwwh.html

[Q86] 读取 JSON 字段
来源：http://dali.chenjidiqi.icu/Article/details/gt2ysedvmxh.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.xinyue.icu/Article/details/gt2utkknmvt.html

[Q87] JSON 字段做条件
来源：http://dali.jinqigufen.top/Article/details/gt2zanjmrgq.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.hfpthk.cn/Article/details/gt2uduicohc.html

[Q88] 行转列（条件聚合）
来源：http://dali.hongshengwenyu.top/Article/details/gt2tlflaegi.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.pengpengdd.cyou/Article/details/gt2hvnxdrwi.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.shangyingyoupin.top/Article/details/gt2kuahmwhc.html

[Q89] 判断表是否存在
来源：http://dali.ivvv.top/Article/details/gt2pnexzzyn.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.haohaochexian.top/Article/details/gt2eozrlaew.html

[Q90] 生成序号列
来源：http://dali.yvedp.cn/Article/details/gt2neebclez.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.9152youxi.cn/Article/details/gt2aeqpgawq.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2rdonwtcp.html

R. Bash 专题
来源：http://dali.vqdsnc.cn/Article/details/gt2lwvmjksm.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2mpsjnbyy.html

[R01] shebang 与严格模式
来源：http://dali.316326.xyz/Article/details/gt2qozlewfw.html

#!/usr/bin/env bash
来源：http://dali.ivvv.top/Article/details/gt2uvhcygkc.html

set -euo pipefail
来源：http://dali.jinqigufen.top/Article/details/gt2iwurmhwu.html

[R02] 变量赋值与使用
来源：http://dali.aibaodan.cn/Article/details/gt2nzhvlslc.html

name="Tom"; echo "$name"
来源：http://dali.gotoacloud.top/Article/details/gt2sxiegdjx.html

[R03] 只读变量
来源：http://dali.gaohongyu789.top/Article/details/gt2tkclfatm.html

readonly PI=3.14
来源：http://dali.jianghu66.top/Article/details/gt2vtqhpslj.html

[R04] 位置参数
来源：http://dali.ivvv.top/Article/details/gt2qppvhzti.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.nwbrower.top/Article/details/gt2blabqfuh.html

[R05] 参数默认值
来源：http://dali.feifeiyinyue.top/Article/details/gt2jgookzhd.html

name="${1:-default}"
来源：http://dali.shzxlz.cn/Article/details/gt2biazwtkk.html

[R06] 判断命令是否存在
来源：http://dali.hnqzz.top/Article/details/gt2zjrzqjid.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.jiagoushi.top/Article/details/gt2xaxrjoye.html

[R07] if 判断文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2whqwzwom.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.tianlin.xyz/Article/details/gt2clbamvdw.html

[R08] 数值比较
来源：http://dali.ehwqpu.com/Article/details/gt2fhjdwiac.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.cheryme.top/Article/details/gt2lavpqffq.html

[R09] 字符串比较
来源：http://dali.daria6918.cn/Article/details/gt2qwnkidlv.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.0kj1m.cn/Article/details/gt2oywloejl.html

[R10] 正则匹配
来源：http://dali.wangdashe.top/Article/details/gt2bdqcftgj.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.gzhubu.top/Article/details/gt2vqupozmw.html

[R11] case 多分支
来源：http://dali.0kj1m.cn/Article/details/gt2kowgznug.html

case "$1" in
来源：http://dali.bjfxy.top/Article/details/gt2czdesswk.html

start) echo "启动" ;;
来源：http://dali.jqgfzy.top/Article/details/gt2spdchgev.html

stop)  echo "停止" ;;
来源：http://dali.tianlin.xyz/Article/details/gt2vmmwpicy.html

*)     echo "未知命令" ;;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jzyeeimx.html

esac
来源：http://dali.daxiang520.top/Article/details/gt2erooofue.html

[R12] for 遍历文件
来源：http://dali.yj20258888.top/Article/details/gt2tuqfbhfs.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vycaesqi.html

[R13] for 计数循环
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mbhynunz.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.nwbrower.top/Article/details/gt2abistblu.html

[R14] C 风格 for
来源：http://dali.tianlin.xyz/Article/details/gt2kzkjhgqr.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.ydzc1.top/Article/details/gt2gvddprnu.html

[R15] while 逐行读文件
来源：http://dali.hysaishi.cn/Article/details/gt2avixktoq.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.tanke756.top/Article/details/gt2boxoygxm.html

[R16] until 等待条件
来源：http://dali.jinqigfzy.top/Article/details/gt2abzklvkd.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.haohaochexian.top/Article/details/gt2cmenofzq.html

[R17] 数组定义与取值
来源：http://dali.cqqwz.cn/Article/details/gt2fgxmhcuv.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zdqjudy.top/Article/details/gt2bpblmouf.html

[R18] 遍历数组
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nixekwjk.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.hammf.cn/Article/details/gt2pscczlkd.html

[R19] 数组长度
来源：http://dali.gotoacloud.top/Article/details/gt2kmgojqxg.html

echo "${#arr[@]}"
来源：http://dali.guowangkeji.top/Article/details/gt2jjanoqjf.html

[R20] 关联数组（字典）
来源：http://dali.wangdashe.top/Article/details/gt2ythpmugx.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.wangdashe.top/Article/details/gt2sjjvkqce.html

[R21] 字符串长度
来源：http://dali.ydzc1.top/Article/details/gt2zbfpbhci.html

echo "${#s}"
来源：http://dali.zhengqikj.top/Article/details/gt2nhbncpum.html

[R22] 截取子串
来源：http://dali.cucudq.cn/Article/details/gt2qljhnugh.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2nzfzgqii.html

[R23] 字符串替换
来源：http://dali.xylfe.cn/Article/details/gt2enjrhemt.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.jqgfzy.top/Article/details/gt2tbmnynvk.html

[R24] 大小写转换
来源：http://dali.yangfankeji.com/Article/details/gt2xgipulvf.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jcdgrmyj.html

[R25] 去后缀 / 去前缀
来源：http://dali.redwolf501.top/Article/details/gt2fjzgfygj.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cpmaampw.html

[R26] 命令替换
来源：http://dali.jqgfzy.top/Article/details/gt2mtalzkiv.html

now=$(date +%F); echo "$now"
来源：http://dali.yvedp.cn/Article/details/gt2warpujap.html

[R27] 算术展开
来源：http://dali.jinqigufen.top/Article/details/gt2vorbkedq.html

echo $((1 + 2 * 3))
来源：http://dali.zhengqikj.top/Article/details/gt2zrfsnavk.html

[R28] 浮点运算
来源：http://dali.yuanzhike.top/Article/details/gt2pepmazoc.html

echo "scale=2; 10/3" | bc
来源：http://dali.cheryme.top/Article/details/gt2altezwjm.html

[R29] 定义函数
来源：http://dali.daxiang520.top/Article/details/gt2estzowhg.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zdqjudy.top/Article/details/gt2xmqyjqvo.html

[R30] 函数返回状态码
来源：http://dali.jqgufenzy.top/Article/details/gt2zgnuuttt.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.chenlongwang.top/Article/details/gt2xfptvsgf.html

[R31] 局部变量
来源：http://dali.yuanzhike.top/Article/details/gt2iorgwdmu.html

f() { local x=1; echo "$x"; }
来源：http://dali.shzxlz.cn/Article/details/gt2gahgkkdb.html

[R32] 参数个数校验
来源：http://dali.hywenlv.cn/Article/details/gt2pzmekqpo.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.yvedp.cn/Article/details/gt2llubwnga.html

[R33] 捕获错误并提示行号
来源：http://dali.redwolf501.top/Article/details/gt2nxtthxdw.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sfjmkojw.html

[R34] 退出时清理
来源：http://dali.fzhhl.top/Article/details/gt2dzdzxpxo.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.sysykeji.top/Article/details/gt2uejvprih.html

[R35] 后台执行并等待
来源：http://dali.shzxlz.cn/Article/details/gt2qygqrymv.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.haohaochexian.top/Article/details/gt2tuvefwgo.html

[R36] 并发执行多个任务
来源：http://dali.wangdashe.top/Article/details/gt2rsknqmdp.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.wangdashe.top/Article/details/gt2jifundlq.html

[R37] 把输出赋给变量
来源：http://dali.meibo888.top/Article/details/gt2ulxitioh.html

files=$(ls -1)
来源：http://dali.yangfankeji.com/Article/details/gt2xwdcexzd.html

[R38] 管道串联
来源：http://dali.feifeiyinyue.top/Article/details/gt2smjmzsjl.html

cat a.txt | grep -i error | wc -l
来源：http://dali.jyoumei.cn/Article/details/gt2pzprzsoe.html

[R39] 重定向标准输出与错误
来源：http://dali.zdqjudy.top/Article/details/gt2rhsqkfhb.html

cmd > out.log 2>&1
来源：http://dali.yuxming.cn/Article/details/gt2tzbogvkl.html

[R40] 追加写日志
来源：http://dali.xinyue.icu/Article/details/gt2fpytlrzq.html

echo "log" >> out.log
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2akpyjchc.html

[R41] 丢弃输出
来源：http://dali.birdmap.top/Article/details/gt2mfdepuwr.html

cmd >/dev/null 2>&1
来源：http://dali.chenlongwang.top/Article/details/gt2onbfwlzv.html

[R42] 输入重定向
来源：http://dali.mhx1999.top/Article/details/gt2wqjupmms.html

wc -l < a.txt
来源：http://dali.snrcjt.cn/Article/details/gt2bpnsomwi.html

[R43] 按名字查找文件
来源：http://dali.yuxming.cn/Article/details/gt2ixwqraiy.html

find . -name "*.log" -type f
来源：http://dali.daxiang520.top/Article/details/gt2ircoiqnp.html

[R44] 按修改时间查找
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vkqxdgcd.html

find . -mtime -7 -type f
来源：http://dali.cdnleiting.top/Article/details/gt2jopgydox.html

[R45] 批量删除
来源：http://dali.meibo888.top/Article/details/gt2jvyapcwi.html

find . -name "*.tmp" -delete
来源：http://dali.jinqigufen.top/Article/details/gt2blordyax.html

[R46] 递归替换文件内容
来源：http://dali.dashuyun.cn/Article/details/gt2rsivslud.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.aibaodan.cn/Article/details/gt2vewuuydu.html

[R47] sed 单行替换
来源：http://dali.chenjidiqi.icu/Article/details/gt2mftkwgpn.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.aibaodan.cn/Article/details/gt2sulzljws.html

[R48] awk 取指定列
来源：http://dali.jiagoushi.top/Article/details/gt2qpvixywn.html

awk '{print $1, $3}' a.txt
来源：http://dali.cheryme.top/Article/details/gt2noxymwmq.html

[R49] awk 带条件
来源：http://dali.xinyue.icu/Article/details/gt2rbunivsg.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.chenzaomai.com/Article/details/gt2vmlkpufl.html

[R50] awk 求和
来源：http://dali.yangfankeji.com/Article/details/gt2vtaaazym.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lggczrks.html

[R51] 排序去重取前几
来源：http://dali.yj202588.top/Article/details/gt2xifrzupe.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.jyoumei.cn/Article/details/gt2zoikriha.html

[R52] 统计行数
来源：http://dali.vqdsnc.cn/Article/details/gt2dvavnxtt.html

wc -l a.txt
来源：http://dali.guannengcc.top/Article/details/gt2ngpmbszd.html

[R53] 查看文件头与实时尾
来源：http://dali.yj202588.top/Article/details/gt2ijcmldiw.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.redwolf501.top/Article/details/gt2okcklhkj.html

[R54] 比较两个文件
来源：http://dali.gzhubu.top/Article/details/gt2ieunevuo.html

diff a.txt b.txt
来源：http://dali.zhixingplan.top/Article/details/gt2lrnjewqq.html

[R55] 压缩与解压
来源：http://dali.gogol.net.cn/Article/details/gt2zsoyiqua.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.ybcxt.top/Article/details/gt2uulfadxp.html

[R56] 远程拷贝
来源：http://dali.yanxiufei.cn/Article/details/gt2irimmfip.html

scp file user@host:/path/
来源：http://dali.xinyue.icu/Article/details/gt2gitwiohv.html

[R57] 远程执行命令
来源：http://dali.fzhhl.top/Article/details/gt2drzjogmc.html

ssh user@host 'uptime'
来源：http://dali.nanxuanxn.top/Article/details/gt2buccktcr.html

[R58] 下载文件
来源：http://dali.shuidangran.top/Article/details/gt2pwkdaitx.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.svipenyu.cn/Article/details/gt2fxgnccjg.html

[R59] 发 POST JSON
来源：http://dali.daria6918.cn/Article/details/gt2jljcchsf.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.chenzaomai.com/Article/details/gt2tlabyssw.html

[R60] 只看 HTTP 状态码
来源：http://dali.dianchejie.cn/Article/details/gt2bolvmjlg.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.nwbrower.top/Article/details/gt2zpdpwbeh.html

[R61] 磁盘占用
来源：http://dali.jyoumei.cn/Article/details/gt2kgxbxamr.html

df -h;  du -sh *
来源：http://dali.cheryme.top/Article/details/gt2vfvwlian.html

[R62] 找最占空间的文件
来源：http://dali.chenlongwang.top/Article/details/gt2lbmeyelu.html

du -ah . | sort -rh | head -10
来源：http://dali.xinyue.icu/Article/details/gt2qmoghbmf.html

[R63] 内存与进程
来源：http://dali.ehwqpu.com/Article/details/gt2jtbtwtbv.html

free -h;  ps aux | grep nginx
来源：http://dali.jinqigufen.top/Article/details/gt2vrfztmbh.html

[R64] 结束进程
来源：http://dali.ehwqpu.com/Article/details/gt2oaqiiary.html

kill -9 $(pgrep -f app.py)
来源：http://dali.guannengcc.top/Article/details/gt2bympayfp.html

[R65] 查看端口占用
来源：http://dali.pengpengdd.cyou/Article/details/gt2jnoaaaty.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zycfv.cn/Article/details/gt2ajidfnwu.html

[R66] 定时任务
来源：http://dali.cqqwz.cn/Article/details/gt2miwmnbad.html

crontab -e;  crontab -l
来源：http://dali.jyoumei.cn/Article/details/gt2nobawfhm.html

[R67] 生成随机十六进制串
来源：http://dali.daria6918.cn/Article/details/gt2kvtmopcv.html

openssl rand -hex 16
来源：http://dali.tanke756.top/Article/details/gt2ojxrgrqy.html

[R68] 计算文件校验值
来源：http://dali.nwbrower.top/Article/details/gt2hawsduzi.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.jinqigufen.top/Article/details/gt2lujzuwkc.html

[R69] 生成随机密码
来源：http://dali.pengpengdd.cyou/Article/details/gt2tlzaksln.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhiwuduotai.top/Article/details/gt2tchorrsx.html

[R70] 时间戳与互转
来源：http://dali.gaohongyu789.top/Article/details/gt2lsofmmpb.html

date +%s;  date -d @1700000000
来源：http://dali.316326.xyz/Article/details/gt2sohmrrkc.html

[R71] 日期格式化
来源：http://dali.svipenyu.cn/Article/details/gt2umhzjokb.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.havefunace.top/Article/details/gt2osqhwsua.html

[R72] 等待端口就绪
来源：http://dali.zdqjudy.top/Article/details/gt2xzaxjeho.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.shangyingyoupin.top/Article/details/gt2xfokbmwr.html

[R73] 分割大日志
来源：http://dali.gaohongyu789.top/Article/details/gt2bzrjsdri.html

split -l 1000 big.log part_
来源：http://dali.cheryme.top/Article/details/gt2jsgdcsdc.html

[R74] 批量重命名
来源：http://dali.gotoacloud.top/Article/details/gt2ovmfuzbd.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.jqgufenzy.top/Article/details/gt2feijmzkn.html

[R75] 导出环境变量
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2llznkndg.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.ehwqpu.com/Article/details/gt2kpzmukvf.html

[R76] 使用临时文件
来源：http://dali.bjfxy.top/Article/details/gt2fpmwqeyq.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.ivvv.top/Article/details/gt2xxfdfahp.html

[R77] 读取用户输入
来源：http://dali.zhongyouzk.top/Article/details/gt2sxctpatk.html

read -rp "请输入: " ans
来源：http://dali.smart0.xyz/Article/details/gt2kbhurnjy.html

[R78] 交互式菜单
来源：http://dali.fengsongda.top/Article/details/gt2dmqlcfei.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.redwolf501.top/Article/details/gt2tqargxtk.html

[R79] 解析命令行选项
来源：http://dali.aizwys.cn/Article/details/gt2lbvbrxup.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.tanke756.top/Article/details/gt2fgaltdlw.html

[R80] 查看脚本执行耗时
来源：http://dali.aibaodan.cn/Article/details/gt2uxtabfdm.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2whnjoeax.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2fnqxmwmt.html


<!-- 参考信息 -->