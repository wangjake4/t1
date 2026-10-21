代发 wailian999

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.aibaodan.cn/Article/details/gtfcxicdmg.html

[Q28] 求和与平均
来源：http://dali.dashuyun.cn/Article/details/gtfktnljov.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.cashguo.top/Article/details/gtzbelsgfk.html

[Q29] 最大最小值
来源：http://dali.9152youxi.cn/Article/details/gtyoqkvnab.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.yj202588.top/Article/details/gtwkurpoix.html

[Q30] 分组统计
来源：http://dali.yonumen.top/Article/details/gtyggdutqf.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.jyoumei.cn/Article/details/gtesxahqxs.html

[Q31] 分组后过滤
来源：http://dali.gaohongyu789.top/Article/details/gtpkxwazpi.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhengqikj.top/Article/details/gtnolkqbms.html

[Q32] 分组拼接字符串
来源：http://dali.yj20258888.top/Article/details/gtridtcgol.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.svipenyu.cn/Article/details/gtlwlumpet.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.yvedp.cn/Article/details/gtaqicypck.html

[Q33] 多列分组
来源：http://dali.gaohongyu789.top/Article/details/gtsxoxjibv.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.meibo888.top/Article/details/gtzjslmzfc.html

[Q34] 每组取第一条
来源：http://dali.svipenyu.cn/Article/details/gtvkcsbkyc.html

SELECT * FROM (
来源：http://dali.zhiwuduotai.top/Article/details/gttdvmzzwt.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.redwolf501.top/Article/details/gtqbgfdjqz.html

) t WHERE rn = 1;
来源：http://dali.yj202588.top/Article/details/gtfctcnzia.html

[Q35] 内连接
来源：http://dali.gaohongyu789.top/Article/details/gttsiwdxab.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.mhx1999.top/Article/details/gtknpvoaly.html

[Q36] 左连接
来源：http://dali.fzhhl.top/Article/details/gtcihezcqz.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.yangfankeji.com/Article/details/gtxpphmuqv.html

[Q37] 右连接
来源：http://dali.jqgfzy.top/Article/details/gtljlosfcd.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.shzxlz.cn/Article/details/gtumghmnvl.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.wangdashe.top/Article/details/gtgypqwtzv.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvicculao.html

[Q39] 自连接（查上下级）
来源：http://dali.shanyushiyangtech.top/Article/details/gtjjxqzaps.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.gotoacloud.top/Article/details/gteaybaiqm.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.yuanzhike.top/Article/details/gtldyoidin.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.yonumen.top/Article/details/gtlreadxxp.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.hnxiangtu.top/Article/details/gttwbgzpal.html

[Q41] 多表连接
来源：http://dali.cqqwz.cn/Article/details/gtpkuqlblc.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.yuxming.cn/Article/details/gtrybxjgnd.html

JOIN users u ON u.id = o.user_id
来源：http://dali.cqqwz.cn/Article/details/gtlzjhdwmc.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.shuidangran.top/Article/details/gtqtyrcrly.html

[Q42] 连接条件附加过滤
来源：http://dali.0kj1m.cn/Article/details/gtpuqdfmqk.html

SELECT u.name, o.amount FROM users u
来源：http://dali.chenzaomai.com/Article/details/gtddyitykb.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.iojbl.cn/Article/details/gtbgsxiayq.html

[Q43] 标量子查询
来源：http://dali.gotoacloud.top/Article/details/gtyqaezpzv.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.fengsongda.top/Article/details/gtnlaslzud.html

[Q44] IN 子查询
来源：http://dali.hnxiangtu.top/Article/details/gtzhyrnwci.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.yvedp.cn/Article/details/gttvmfxsaj.html

[Q45] EXISTS 判断存在
来源：http://dali.haohaochexian.top/Article/details/gteupupgns.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.hongshengwenyu.top/Article/details/gtqyoqtagk.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.jlsjyb.cn/Article/details/gtpastyrzc.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.tianlin.xyz/Article/details/gtjuamipzk.html

[Q47] 与平均值比较
来源：http://dali.ehwqpu.com/Article/details/gtzhcsadnt.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.nanxuanxn.top/Article/details/gtdtzaqlba.html

[Q48] CTE 公用表表达式
来源：http://dali.hnqzz.top/Article/details/gtnsbtrgft.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.vqdsnc.cn/Article/details/gtxmsqmink.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.jinqigfzy.top/Article/details/gtwxeljkfn.html

[Q49] 更新单行
来源：http://dali.hywenlv.cn/Article/details/gtuqnfwnyi.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.hfpthk.cn/Article/details/gtjirzvxzu.html

[Q50] 批量更新
来源：http://dali.xuanzx.com/Article/details/gtmjmnrhkh.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhiwuduotai.top/Article/details/gtlxwndrld.html

[Q51] 用子查询更新
来源：http://dali.c1oappe.top/Article/details/gtafqsgnzf.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.cucudq.cn/Article/details/gtxvectjlf.html

[Q52] 删除指定行
来源：http://dali.guowangkeji.top/Article/details/gtxysalbyd.html

DELETE FROM users WHERE id = 10;
来源：http://dali.yj20258888.top/Article/details/gthibrkqiv.html

[Q53] 按条件删除
来源：http://dali.nanxinkj.top/Article/details/gtemkvnmgh.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.xziqi.cn/Article/details/gtxxcmnzzu.html

[Q54] 清空表
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcgmggxyd.html

TRUNCATE TABLE logs;
来源：http://dali.hongshengwenyu.top/Article/details/gtzkixdvon.html

[Q55] 排名（并列占位）
来源：http://dali.sweek.top/Article/details/gtzblawutl.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.c1oappe.top/Article/details/gtbqcwfkhg.html

[Q56] 密集排名（并列不占位）
来源：http://dali.yj20258888.top/Article/details/gtofissmvl.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.yj20258888.top/Article/details/gtirextnvm.html

[Q57] 行号
来源：http://dali.zhiwuduotai.top/Article/details/gtcspyexpm.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.tianlin.xyz/Article/details/gtrsskasfv.html

[Q58] 累计求和
来源：http://dali.fengsongda.top/Article/details/gtlnctabep.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.c1oappe.top/Article/details/gtimvmcbhw.html

[Q59] 分组内累计
来源：http://dali.yongpay.top/Article/details/gtlfyqmsyi.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.shzxlz.cn/Article/details/gtdeatdhhe.html

[Q60] 取上一行 / 下一行
来源：http://dali.yuxming.cn/Article/details/gtnqiwzdny.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.ehwqpu.com/Article/details/gtsapzooly.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.pengpengdd.cyou/Article/details/gtledkxhyi.html

[Q61] 移动平均
来源：http://dali.9152youxi.cn/Article/details/gtdfiyrten.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.ydzc1.top/Article/details/gtcvrrzogk.html

[Q62] 分组占比
来源：http://dali.quarkkingdee.top/Article/details/gtvmewkhrb.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.smart0.xyz/Article/details/gtborhuuzw.html

[Q63] 开启事务
来源：http://dali.gogol.net.cn/Article/details/gtmaoahksa.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zdqjudy.top/Article/details/gtkwxiodwg.html

[Q64] 提交事务
来源：http://dali.shuidangran.top/Article/details/gtmdfvuamq.html

COMMIT;
来源：http://dali.cucudq.cn/Article/details/gtzpwatfqj.html

[Q65] 回滚事务
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwkmzatbh.html

ROLLBACK;
来源：http://dali.jinghuilouyu.cn/Article/details/gtltdkhzyz.html

[Q66] 行锁查询
来源：http://dali.c1oappe.top/Article/details/gtsvltuumo.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.kuanghao11.cn/Article/details/gttatxelqx.html

[Q67] 设置隔离级别
来源：http://dali.cheryme.top/Article/details/gtttkxbaew.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.tian-w.cn/Article/details/gttnxkumpy.html

[Q68] 保存点
来源：http://dali.svipenyu.cn/Article/details/gtficgudeu.html

SAVEPOINT sp1;
来源：http://dali.vqdsnc.cn/Article/details/gtuqrieikg.html

ROLLBACK TO sp1;
来源：http://dali.hongshengwenyu.top/Article/details/gtvtwqvqwe.html

[Q69] 查看执行计划
来源：http://dali.haohaochexian.top/Article/details/gtqahjbfkv.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gtszixjjxz.html

[Q70] 更新统计信息
来源：http://dali.mhx1999.top/Article/details/gtyxtxszfd.html

ANALYZE TABLE users;
来源：http://dali.jiagoushi.top/Article/details/gtvdsxhsdr.html

[Q71] 查看建表语句
来源：http://dali.ehwqpu.com/Article/details/gtuthpqoig.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.smart0.xyz/Article/details/gtjvrqqnrm.html

[Q72] 查看索引
来源：http://dali.xinyue.icu/Article/details/gtfxnxhbob.html

SHOW INDEX FROM users;
来源：http://dali.ybcxt.top/Article/details/gtlftyzjez.html

[Q73] 查看表状态
来源：http://dali.gaohongyu789.top/Article/details/gtmtnzfwiv.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.fzhhl.top/Article/details/gtjsdvdrje.html

[Q74] 强制使用索引
来源：http://dali.meibo888.top/Article/details/gtvvwbygof.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.haohaochexian.top/Article/details/gtpuisklkn.html

[Q75] 日期格式化
来源：http://dali.yvedp.cn/Article/details/gtselaniih.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.hnxiangtu.top/Article/details/gtruwiynul.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.nanxinkj.top/Article/details/gthuwomccg.html

[Q76] 按天统计
来源：http://dali.shanyushiyangtech.top/Article/details/gtwsskdhep.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.yongpay.top/Article/details/gtvbtievsh.html

[Q77] 时间加减
来源：http://dali.yangfankeji.com/Article/details/gthkagolvb.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.jianghu66.top/Article/details/gtigcvebbz.html

[Q78] 当前时间
来源：http://dali.bjfxy.top/Article/details/gtjahehatj.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.cdnleiting.top/Article/details/gtjmdsbvzo.html

[Q79] 字符串拼接
来源：http://dali.cqqwz.cn/Article/details/gtpdympyni.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.gogol.net.cn/Article/details/gtjknnjxwe.html

[Q80] 字符串截取
来源：http://dali.dashuyun.cn/Article/details/gtmxxudqnb.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.daxiang520.top/Article/details/gtviirwfmo.html

[Q81] 字符串替换
来源：http://dali.nanxuanxn.top/Article/details/gtydxnwcdn.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gtdxtfilth.html

[Q82] 字符长度与字节长度
来源：http://dali.quarkkingdee.top/Article/details/gtrpfujldl.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.meibo888.top/Article/details/gtifiqckja.html

[Q83] 大小写转换
来源：http://dali.quarkkingdee.top/Article/details/gtqcxfgwug.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.yj20258.top/Article/details/gtrujbcflj.html

[Q84] 去除首尾空格
来源：http://dali.shuidangran.top/Article/details/gtedvczyjp.html

SELECT TRIM(name) FROM users;
来源：http://dali.hnqzz.top/Article/details/gtvwhizyhq.html

[Q85] 数值取整
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcczcpneh.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.xziqi.cn/Article/details/gtoxmlxsgf.html

[Q86] 读取 JSON 字段
来源：http://dali.shuidangran.top/Article/details/gtedtmgvng.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.birdmap.top/Article/details/gtaqdswvse.html

[Q87] JSON 字段做条件
来源：http://dali.sysykeji.top/Article/details/gtesrallwj.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.sufxvd.cn/Article/details/gtbtxfqzoo.html

[Q88] 行转列（条件聚合）
来源：http://dali.hnxiangtu.top/Article/details/gtfdgylscb.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.jiagoushi.top/Article/details/gtqzxtucze.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.feifeiyinyue.top/Article/details/gtgyztbmrs.html

[Q89] 判断表是否存在
来源：http://dali.tianlin.xyz/Article/details/gtinvzzhwm.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.fzhhl.top/Article/details/gtkloetplp.html

[Q90] 生成序号列
来源：http://dali.hnxiangtu.top/Article/details/gtxojsexky.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.cucudq.cn/Article/details/gttxcrzkwx.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtkpklpifa.html

R. Bash 专题
来源：http://dali.yangfankeji.com/Article/details/gtvgkcqgvg.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtdlltiyor.html

[R01] shebang 与严格模式
来源：http://dali.yueranfly.top/Article/details/gtrtuwhsjk.html

#!/usr/bin/env bash
来源：http://dali.ywan-chungtsiang.top/Article/details/gtelcosrad.html

set -euo pipefail
来源：http://dali.jiagoushi.top/Article/details/gtwahpokxp.html

[R02] 变量赋值与使用
来源：http://dali.cashguo.top/Article/details/gtduzpbfsi.html

name="Tom"; echo "$name"
来源：http://dali.ehwqpu.com/Article/details/gtcggrdeej.html

[R03] 只读变量
来源：http://dali.chenjidiqi.icu/Article/details/gtdxsvjpey.html

readonly PI=3.14
来源：http://dali.yanxiufei.cn/Article/details/gtiychekbd.html

[R04] 位置参数
来源：http://dali.redwolf501.top/Article/details/gtwzqewcze.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.feifeiyinyue.top/Article/details/gtlsbhftju.html

[R05] 参数默认值
来源：http://dali.hnxiangtu.top/Article/details/gtjskomuhz.html

name="${1:-default}"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwqowccvh.html

[R06] 判断命令是否存在
来源：http://dali.zhoulong.xyz/Article/details/gtdjiylpwq.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.mhx1999.top/Article/details/gtsbcwvyra.html

[R07] if 判断文件
来源：http://dali.zhiwuduotai.top/Article/details/gtqstrcocd.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqpoztbee.html

[R08] 数值比较
来源：http://dali.xuanzx.com/Article/details/gtbgjpyfve.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.dianchejie.cn/Article/details/gtomravllz.html

[R09] 字符串比较
来源：http://dali.mhx1999.top/Article/details/gtjrwgknpx.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.ivvv.top/Article/details/gtxhpdwfud.html

[R10] 正则匹配
来源：http://dali.xziqi.cn/Article/details/gtralccusx.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.hongshengwenyu.top/Article/details/gtlaqddcgq.html

[R11] case 多分支
来源：http://dali.ppjwa.cn/Article/details/gtrpjffyka.html

case "$1" in
来源：http://dali.daria6918.cn/Article/details/gtujiyneym.html

start) echo "启动" ;;
来源：http://dali.zdqjudy.top/Article/details/gtcugyzjrs.html

stop)  echo "停止" ;;
来源：http://dali.0kj1m.cn/Article/details/gthwbhnzob.html

*)     echo "未知命令" ;;
来源：http://dali.zhiwuduotai.top/Article/details/gtxegtkxde.html

esac
来源：http://dali.hysaishi.cn/Article/details/gtpjuxives.html

[R12] for 遍历文件
来源：http://dali.9152youxi.cn/Article/details/gtyucesmyx.html

for f in *.txt; do echo "$f"; done
来源：http://dali.dashuyun.cn/Article/details/gtiaqmjcph.html

[R13] for 计数循环
来源：http://dali.quarkkingdee.top/Article/details/gtnxcqelab.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.jinqigfzy.top/Article/details/gtdfukazkj.html

[R14] C 风格 for
来源：http://dali.fzhhl.top/Article/details/gtplgbxwfc.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.sufxvd.cn/Article/details/gtdaonymxv.html

[R15] while 逐行读文件
来源：http://dali.jinqigfzy.top/Article/details/gtjkjczuuc.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.yanxiufei.cn/Article/details/gtkhfpsbax.html

[R16] until 等待条件
来源：http://dali.zhixingplan.top/Article/details/gtcyhcjunm.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.jlsjyb.cn/Article/details/gtgjizzrat.html

[R17] 数组定义与取值
来源：http://dali.mhx1999.top/Article/details/gtfyrlamav.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.sweek.top/Article/details/gtfjdlpejq.html

[R18] 遍历数组
来源：http://dali.chenzaomai.com/Article/details/gtyusqclhl.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.daria6918.cn/Article/details/gtyjyffypa.html

[R19] 数组长度
来源：http://dali.xziqi.cn/Article/details/gtekjxrzoy.html

echo "${#arr[@]}"
来源：http://dali.jinqigfzy.top/Article/details/gtgvnkqcea.html

[R20] 关联数组（字典）
来源：http://dali.iojbl.cn/Article/details/gtshrssvsz.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.yongpay.top/Article/details/gtiwtxguhq.html

[R21] 字符串长度
来源：http://dali.yj202588.top/Article/details/gtzcwfgiwl.html

echo "${#s}"
来源：http://dali.9152youxi.cn/Article/details/gteswjsvxg.html

[R22] 截取子串
来源：http://dali.meibo888.top/Article/details/gtmlzlkuef.html

echo "${s:0:5}"
来源：http://dali.yj20258.top/Article/details/gtlyywuukp.html

[R23] 字符串替换
来源：http://dali.redwolf501.top/Article/details/gtiakvgspp.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.svipenyu.cn/Article/details/gtpvuiumjl.html

[R24] 大小写转换
来源：http://dali.sysykeji.top/Article/details/gtnijqbfzi.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gtrsoindzw.html

[R25] 去后缀 / 去前缀
来源：http://dali.dashuyun.cn/Article/details/gtxuvwpqwj.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.jinqigfzy.top/Article/details/gtsuwvhxhp.html

[R26] 命令替换
来源：http://dali.jinqigufen.top/Article/details/gtngpkiutu.html

now=$(date +%F); echo "$now"
来源：http://dali.nwbrower.top/Article/details/gtzrbmtsou.html

[R27] 算术展开
来源：http://dali.xuanzx.com/Article/details/gtedranzhy.html

echo $((1 + 2 * 3))
来源：http://dali.dianchejie.cn/Article/details/gtrsodwfou.html

[R28] 浮点运算
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqnwigrfv.html

echo "scale=2; 10/3" | bc
来源：http://dali.jianghu66.top/Article/details/gtimxidrtw.html

[R29] 定义函数
来源：http://dali.birdmap.top/Article/details/gtaghuxdcd.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.hongshengwenyu.top/Article/details/gtbhoinqvz.html

[R30] 函数返回状态码
来源：http://dali.cheryme.top/Article/details/gtmoncpher.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.daxiang520.top/Article/details/gthwelxgqv.html

[R31] 局部变量
来源：http://dali.hongshengwenyu.top/Article/details/gtorischjq.html

f() { local x=1; echo "$x"; }
来源：http://dali.fzhhl.top/Article/details/gtmlonfbco.html

[R32] 参数个数校验
来源：http://dali.sxryk.cn/Article/details/gtgbmraprz.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.yonumen.top/Article/details/gtxtbusbru.html

[R33] 捕获错误并提示行号
来源：http://dali.wangshuangyany.cn/Article/details/gtfqnauevi.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.xylfe.cn/Article/details/gtcwgsqjge.html

[R34] 退出时清理
来源：http://dali.yueranfly.top/Article/details/gtvybkefru.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhengqikj.top/Article/details/gtoybyxcuc.html

[R35] 后台执行并等待
来源：http://dali.nanxuanxn.top/Article/details/gtrthnlzgg.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.birdmap.top/Article/details/gtwwexyytn.html

[R36] 并发执行多个任务
来源：http://dali.guannengcc.top/Article/details/gtahbsmaud.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.316326.xyz/Article/details/gtcaubnwoa.html

[R37] 把输出赋给变量
来源：http://dali.zhiwuduotai.top/Article/details/gtoqwdxdra.html

files=$(ls -1)
来源：http://dali.nwbrower.top/Article/details/gtclsdidql.html

[R38] 管道串联
来源：http://dali.mhx1999.top/Article/details/gtluqcicki.html

cat a.txt | grep -i error | wc -l
来源：http://dali.cdnleiting.top/Article/details/gtrhcvjjrr.html

[R39] 重定向标准输出与错误
来源：http://dali.jlsjyb.cn/Article/details/gtcmjfmkua.html

cmd > out.log 2>&1
来源：http://dali.hnqzz.top/Article/details/gtjnsmtppx.html

[R40] 追加写日志
来源：http://dali.hysaishi.cn/Article/details/gtttrnyqdz.html

echo "log" >> out.log
来源：http://dali.yongpay.top/Article/details/gtnskbygxb.html

[R41] 丢弃输出
来源：http://dali.jqgufenzy.top/Article/details/gtwhcbsgzb.html

cmd >/dev/null 2>&1
来源：http://dali.cucudq.cn/Article/details/gtpwrvhkid.html

[R42] 输入重定向
来源：http://dali.kuanghao11.cn/Article/details/gtwmofkqrn.html

wc -l < a.txt
来源：http://dali.wangshuangyany.cn/Article/details/gtuepyilnq.html

[R43] 按名字查找文件
来源：http://dali.chenlongwang.top/Article/details/gttxmebxkn.html

find . -name "*.log" -type f
来源：http://dali.gzhubu.top/Article/details/gtmtnfersz.html

[R44] 按修改时间查找
来源：http://dali.zhengqikj.top/Article/details/gtedbtwvvn.html

find . -mtime -7 -type f
来源：http://dali.gaohongyu789.top/Article/details/gtqkhutber.html

[R45] 批量删除
来源：http://dali.yj202588.top/Article/details/gtuhelcdwj.html

find . -name "*.tmp" -delete
来源：http://dali.yangfankeji.com/Article/details/gtknsfmxvp.html

[R46] 递归替换文件内容
来源：http://dali.cqqwz.cn/Article/details/gtcznqeifa.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.jqgfzy.top/Article/details/gtqepgjfnw.html

[R47] sed 单行替换
来源：http://dali.hnqzz.top/Article/details/gtkaebkvxz.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhiwuduotai.top/Article/details/gtgiikltsf.html

[R48] awk 取指定列
来源：http://dali.svipenyu.cn/Article/details/gtdepgmncg.html

awk '{print $1, $3}' a.txt
来源：http://dali.yuanzhike.top/Article/details/gtcujqsicf.html

[R49] awk 带条件
来源：http://dali.ybcxt.top/Article/details/gtzzhmxzdz.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zdqjudy.top/Article/details/gtmxviedls.html

[R50] awk 求和
来源：http://dali.gotoacloud.top/Article/details/gtkspdcctp.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.jianghu66.top/Article/details/gtsdyyfkqz.html

[R51] 排序去重取前几
来源：http://dali.tanke756.top/Article/details/gtolhroujr.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.hnxiangtu.top/Article/details/gtikkuntzo.html

[R52] 统计行数
来源：http://dali.hongshengwenyu.top/Article/details/gtkwalymmc.html

wc -l a.txt
来源：http://dali.xinyue.icu/Article/details/gtjaveuzme.html

[R53] 查看文件头与实时尾
来源：http://dali.chenzaomai.com/Article/details/gtgmrhgkdl.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.xinyue.icu/Article/details/gtewnlcdzn.html

[R54] 比较两个文件
来源：http://dali.shangyingyoupin.top/Article/details/gtmwunhfbk.html

diff a.txt b.txt
来源：http://dali.xziqi.cn/Article/details/gtrvfeefgo.html

[R55] 压缩与解压
来源：http://dali.xuanzx.com/Article/details/gtcbdmvhjx.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.cqqwz.cn/Article/details/gtnsqnzboz.html

[R56] 远程拷贝
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmrwqhsey.html

scp file user@host:/path/
来源：http://dali.guannengcc.top/Article/details/gtpfyaghgb.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gtcxjpbsgb.html

ssh user@host 'uptime'
来源：http://dali.tian-w.cn/Article/details/gtobehehdx.html

[R58] 下载文件
来源：http://dali.cdnleiting.top/Article/details/gtwejxrgdj.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.dashuyun.cn/Article/details/gtygffkzdp.html

[R59] 发 POST JSON
来源：http://dali.yongpay.top/Article/details/gtcltywkpp.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhengqikj.top/Article/details/gttdroqvhe.html

[R60] 只看 HTTP 状态码
来源：http://dali.hnxiangtu.top/Article/details/gtvyitrnwb.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.nwbrower.top/Article/details/gtgwjlskdh.html

[R61] 磁盘占用
来源：http://dali.dianchejie.cn/Article/details/gtmjshgsjz.html

df -h;  du -sh *
来源：http://dali.tian-w.cn/Article/details/gtmhchmtnn.html

[R62] 找最占空间的文件
来源：http://dali.haohaochexian.top/Article/details/gtwgbsqpqg.html

du -ah . | sort -rh | head -10
来源：http://dali.chenjidiqi.icu/Article/details/gtliephnux.html

[R63] 内存与进程
来源：http://dali.nwbrower.top/Article/details/gtwtnddjjn.html

free -h;  ps aux | grep nginx
来源：http://dali.guannengcc.top/Article/details/gtersdeeea.html

[R64] 结束进程
来源：http://dali.zhiwuduotai.top/Article/details/gtsmkynnxz.html

kill -9 $(pgrep -f app.py)
来源：http://dali.hongshengwenyu.top/Article/details/gtwxorzvgr.html

[R65] 查看端口占用
来源：http://dali.shanyushiyangtech.top/Article/details/gtkmwviold.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhixingplan.top/Article/details/gtendjiqvr.html

[R66] 定时任务
来源：http://dali.daxiang520.top/Article/details/gtrzcddnmk.html

crontab -e;  crontab -l
来源：http://dali.fengsongda.top/Article/details/gtwepbmpgm.html

[R67] 生成随机十六进制串
来源：http://dali.bjfxy.top/Article/details/gtkwjzocyd.html

openssl rand -hex 16
来源：http://dali.daxiang520.top/Article/details/gteizmvugh.html

[R68] 计算文件校验值
来源：http://dali.ybcxt.top/Article/details/gtfpmsyknb.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkfakunrf.html

[R69] 生成随机密码
来源：http://dali.birdmap.top/Article/details/gthcdtrcqp.html

head -c 16 /dev/urandom | base64
来源：http://dali.aizwys.cn/Article/details/gtxapwrweo.html

[R70] 时间戳与互转
来源：http://dali.haohaochexian.top/Article/details/gtpmwtxxaz.html

date +%s;  date -d @1700000000
来源：http://dali.ybcxt.top/Article/details/gtksdkhaig.html

[R71] 日期格式化
来源：http://dali.wangshuangyany.cn/Article/details/gtkaiqadab.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.yueranfly.top/Article/details/gtqpoolsrc.html

[R72] 等待端口就绪
来源：http://dali.yueranfly.top/Article/details/gteoncdtwa.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.daria6918.cn/Article/details/gtlinjqfxf.html

[R73] 分割大日志
来源：http://dali.jinqigufen.top/Article/details/gtwrfufobp.html

split -l 1000 big.log part_
来源：http://dali.andypj.xyz/Article/details/gtqvimctpx.html

[R74] 批量重命名
来源：http://dali.hammf.cn/Article/details/gtyabcalhx.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.shangyingyoupin.top/Article/details/gtcixmquxt.html

[R75] 导出环境变量
来源：http://dali.zdqjudy.top/Article/details/gtlutmrpvr.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.hongshengwenyu.top/Article/details/gtiihfbcgh.html

[R76] 使用临时文件
来源：http://dali.dashuyun.cn/Article/details/gthjtfpask.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.yuanzhike.top/Article/details/gtjojyffmz.html

[R77] 读取用户输入
来源：http://dali.ehwqpu.com/Article/details/gtooqzrijq.html


<!-- 参考信息 -->