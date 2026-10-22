代发 wailian999

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.tian-w.cn/Article/details/gtwsneurlj.html

[Q28] 求和与平均
来源：http://dali.yanxiufei.cn/Article/details/gtypaixxtm.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.vqdsnc.cn/Article/details/gtyxuncyji.html

[Q29] 最大最小值
来源：http://dali.zhengqikj.top/Article/details/gtbhmnweqz.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.cashguo.top/Article/details/gtrxyvxsum.html

[Q30] 分组统计
来源：http://dali.zycfv.cn/Article/details/gtotiosjuk.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.wangshuangyany.cn/Article/details/gtqnzvzlev.html

[Q31] 分组后过滤
来源：http://dali.gotoacloud.top/Article/details/gtalyxwdrd.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.yanxiufei.cn/Article/details/gtulbbrhqu.html

[Q32] 分组拼接字符串
来源：http://dali.haohaochexian.top/Article/details/gtigserbgj.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.yvedp.cn/Article/details/gtvpfhsxqd.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.shzxlz.cn/Article/details/gtpgulzdbw.html

[Q33] 多列分组
来源：http://dali.tian-w.cn/Article/details/gtvopcbgqc.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlayjqshk.html

[Q34] 每组取第一条
来源：http://dali.zhongyouzk.top/Article/details/gtzjtxzsbg.html

SELECT * FROM (
来源：http://dali.hfpthk.cn/Article/details/gtnmrekdwk.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.snrcjt.cn/Article/details/gtotrbxbzz.html

) t WHERE rn = 1;
来源：http://dali.tanke756.top/Article/details/gtlpljehvx.html

[Q35] 内连接
来源：http://dali.cdnleiting.top/Article/details/gtxcdqubeh.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.smart0.xyz/Article/details/gtwimlxbmn.html

[Q36] 左连接
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlapyyaye.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.vqdsnc.cn/Article/details/gtirunztra.html

[Q37] 右连接
来源：http://dali.birdmap.top/Article/details/gtjbxyygmv.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.svipenyu.cn/Article/details/gtxpigjkqi.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.cashguo.top/Article/details/gthxxlybws.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.tianlin.xyz/Article/details/gtbjnrtidx.html

[Q39] 自连接（查上下级）
来源：http://dali.shangyingyoupin.top/Article/details/gtwfchfbuj.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.cqqwz.cn/Article/details/gtxizutwpf.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.andypj.xyz/Article/details/gtchbdlgtg.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.meibo888.top/Article/details/gtbyngibva.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.xziqi.cn/Article/details/gtiecswbei.html

[Q41] 多表连接
来源：http://dali.jqgfzy.top/Article/details/gthcfjyxyw.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.feifeiyinyue.top/Article/details/gtcgbscwyf.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhongyouzk.top/Article/details/gtvlqvjnbt.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.9152youxi.cn/Article/details/gtlarkxbnq.html

[Q42] 连接条件附加过滤
来源：http://dali.wangdashe.top/Article/details/gtjwylckpf.html

SELECT u.name, o.amount FROM users u
来源：http://dali.shzxlz.cn/Article/details/gtidulbyrv.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.xziqi.cn/Article/details/gtmaqeundm.html

[Q43] 标量子查询
来源：http://dali.zhiwuduotai.top/Article/details/gtzufxwmwg.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.hongshengwenyu.top/Article/details/gtglyydgjb.html

[Q44] IN 子查询
来源：http://dali.fzhhl.top/Article/details/gtfrwhboyv.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.guowangkeji.top/Article/details/gtwdatdghx.html

[Q45] EXISTS 判断存在
来源：http://dali.pycfn.com/Article/details/gtzlcrflsf.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.guannengcc.top/Article/details/gtgcxkxpnc.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.cashguo.top/Article/details/gtfmjpseaq.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.kuanghao11.cn/Article/details/gtokiqhwhh.html

[Q47] 与平均值比较
来源：http://dali.zhoulong.xyz/Article/details/gtghrqoplb.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.jinqigufen.top/Article/details/gtczhlepjd.html

[Q48] CTE 公用表表达式
来源：http://dali.daxiang520.top/Article/details/gtwwvhevqy.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.ppjwa.cn/Article/details/gtbisrfdtu.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.svipenyu.cn/Article/details/gtxkqsdjkg.html

[Q49] 更新单行
来源：http://dali.sufxvd.cn/Article/details/gtxnavyayh.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.feifeiyinyue.top/Article/details/gtfctelrjg.html

[Q50] 批量更新
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfdgcibto.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.fzhhl.top/Article/details/gtvzdoechb.html

[Q51] 用子查询更新
来源：http://dali.kuanghao11.cn/Article/details/gtlxcnklfc.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.feifeiyinyue.top/Article/details/gtuusbncgh.html

[Q52] 删除指定行
来源：http://dali.cqqwz.cn/Article/details/gtrcjbjscd.html

DELETE FROM users WHERE id = 10;
来源：http://dali.vqdsnc.cn/Article/details/gtgedqxtjc.html

[Q53] 按条件删除
来源：http://dali.ppjwa.cn/Article/details/gtackpaztd.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.jyoumei.cn/Article/details/gtffdwbnub.html

[Q54] 清空表
来源：http://dali.jqgfzy.top/Article/details/gtwmyxstfs.html

TRUNCATE TABLE logs;
来源：http://dali.daria6918.cn/Article/details/gttjkvxtlc.html

[Q55] 排名（并列占位）
来源：http://dali.nanxuanxn.top/Article/details/gtpqiamkja.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.hongshengwenyu.top/Article/details/gtrnphkngc.html

[Q56] 密集排名（并列不占位）
来源：http://dali.gzhubu.top/Article/details/gtssgdaibr.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.bjfxy.top/Article/details/gtcebatbth.html

[Q57] 行号
来源：http://dali.smart0.xyz/Article/details/gtctqutplk.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.yuanzhike.top/Article/details/gtukfwvihe.html

[Q58] 累计求和
来源：http://dali.yj20258888.top/Article/details/gtrxjftggp.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhoulong.xyz/Article/details/gtdrbqzdll.html

[Q59] 分组内累计
来源：http://dali.guannengcc.top/Article/details/gthfeifjwy.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.cheryme.top/Article/details/gtwtllbzvd.html

[Q60] 取上一行 / 下一行
来源：http://dali.yangfankeji.com/Article/details/gtexfpjown.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.kuanghao11.cn/Article/details/gtuqhmayvw.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.gotoacloud.top/Article/details/gtslwcnkrx.html

[Q61] 移动平均
来源：http://dali.sweek.top/Article/details/gtwfwddepp.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.daxiang520.top/Article/details/gttmqcjglx.html

[Q62] 分组占比
来源：http://dali.jqgfzy.top/Article/details/gtuplydauz.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.xinyue.icu/Article/details/gtoipdkcha.html

[Q63] 开启事务
来源：http://dali.sxryk.cn/Article/details/gtjhynlgfi.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.dashuyun.cn/Article/details/gtkhezskdn.html

[Q64] 提交事务
来源：http://dali.gaohongyu789.top/Article/details/gtxzxnzgdv.html

COMMIT;
来源：http://dali.ybcxt.top/Article/details/gtabhzylwy.html

[Q65] 回滚事务
来源：http://dali.jlsjyb.cn/Article/details/gtrjukewlk.html

ROLLBACK;
来源：http://dali.zdqjudy.top/Article/details/gtzmmwmqog.html

[Q66] 行锁查询
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmcxullpb.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.jianghu66.top/Article/details/gtlnxsamwr.html

[Q67] 设置隔离级别
来源：http://dali.hnqzz.top/Article/details/gtsqzfwapn.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.hnqzz.top/Article/details/gthowarmyd.html

[Q68] 保存点
来源：http://dali.xziqi.cn/Article/details/gtwrmuirgh.html

SAVEPOINT sp1;
来源：http://dali.sxryk.cn/Article/details/gtouqmffmj.html

ROLLBACK TO sp1;
来源：http://dali.xuanzx.com/Article/details/gtmlrkyqzj.html

[Q69] 查看执行计划
来源：http://dali.yongpay.top/Article/details/gtxgqkabwx.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.haohaochexian.top/Article/details/gtxodvqihm.html

[Q70] 更新统计信息
来源：http://dali.jlsjyb.cn/Article/details/gtrtuovwhn.html

ANALYZE TABLE users;
来源：http://dali.guannengcc.top/Article/details/gtwuwrptav.html

[Q71] 查看建表语句
来源：http://dali.dianchejie.cn/Article/details/gtuagsiqup.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.sysykeji.top/Article/details/gtbktummjp.html

[Q72] 查看索引
来源：http://dali.gogol.net.cn/Article/details/gtufrdovjo.html

SHOW INDEX FROM users;
来源：http://dali.quarkkingdee.top/Article/details/gtiksaclfw.html

[Q73] 查看表状态
来源：http://dali.jqgufenzy.top/Article/details/gtuhelnfwl.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.jyoumei.cn/Article/details/gtqlqbmjez.html

[Q74] 强制使用索引
来源：http://dali.redwolf501.top/Article/details/gtvawytdxh.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.shangyingyoupin.top/Article/details/gtcijwxihe.html

[Q75] 日期格式化
来源：http://dali.ybcxt.top/Article/details/gtsazxsexx.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.jqgfzy.top/Article/details/gtckpbuqlb.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.hongshengwenyu.top/Article/details/gtztakhlwn.html

[Q76] 按天统计
来源：http://dali.yuxming.cn/Article/details/gthalqgopm.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.fengsongda.top/Article/details/gtfsjvknfs.html

[Q77] 时间加减
来源：http://dali.yanxiufei.cn/Article/details/gtxwwmenet.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.wangdashe.top/Article/details/gtxxgfijxp.html

[Q78] 当前时间
来源：http://dali.jinghuilouyu.cn/Article/details/gtncgxhuss.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.kuanghao11.cn/Article/details/gtndflrpph.html

[Q79] 字符串拼接
来源：http://dali.shanyushiyangtech.top/Article/details/gtntqbyocg.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.xinyue.icu/Article/details/gtckihltof.html

[Q80] 字符串截取
来源：http://dali.iojbl.cn/Article/details/gtlpmurinv.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.ivvv.top/Article/details/gtcsstysbw.html

[Q81] 字符串替换
来源：http://dali.ivvv.top/Article/details/gtctdfrwyr.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.yonumen.top/Article/details/gturphwnzx.html

[Q82] 字符长度与字节长度
来源：http://dali.vqdsnc.cn/Article/details/gtaricituq.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.kuanghao11.cn/Article/details/gtdclypwtd.html

[Q83] 大小写转换
来源：http://dali.bjfxy.top/Article/details/gtxnnssxws.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhixingplan.top/Article/details/gtovnbseen.html

[Q84] 去除首尾空格
来源：http://dali.mhx1999.top/Article/details/gtxgjgxgax.html

SELECT TRIM(name) FROM users;
来源：http://dali.svipenyu.cn/Article/details/gtelnlztzn.html

[Q85] 数值取整
来源：http://dali.hammf.cn/Article/details/gthxkggadz.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.sxryk.cn/Article/details/gtjaabzqae.html

[Q86] 读取 JSON 字段
来源：http://dali.daxiang520.top/Article/details/gtfpuozsrs.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.haohaochexian.top/Article/details/gtxehzsbon.html

[Q87] JSON 字段做条件
来源：http://dali.hfpthk.cn/Article/details/gttlxambia.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.jinghuilouyu.cn/Article/details/gtnftoshoa.html

[Q88] 行转列（条件聚合）
来源：http://dali.cdnleiting.top/Article/details/gtvdckcclg.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.xuanzx.com/Article/details/gtelbauyie.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.hammf.cn/Article/details/gtzqnovgpu.html

[Q89] 判断表是否存在
来源：http://dali.zhoulong.xyz/Article/details/gtgwslzuca.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.gotoacloud.top/Article/details/gttqlczmlf.html

[Q90] 生成序号列
来源：http://dali.aizwys.cn/Article/details/gtrosnldwu.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.ywan-chungtsiang.top/Article/details/gttbnhhtxa.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtwjcxckif.html

R. Bash 专题
来源：http://dali.ivvv.top/Article/details/gthchjhvno.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttqwnlcnh.html

[R01] shebang 与严格模式
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcfwjbjji.html

#!/usr/bin/env bash
来源：http://dali.quarkkingdee.top/Article/details/gtnywploka.html

set -euo pipefail
来源：http://dali.kuanghao11.cn/Article/details/gtulxtfgrt.html

[R02] 变量赋值与使用
来源：http://dali.c1oappe.top/Article/details/gtvhyrkilx.html

name="Tom"; echo "$name"
来源：http://dali.hfpthk.cn/Article/details/gtwgadoulh.html

[R03] 只读变量
来源：http://dali.cashguo.top/Article/details/gtebeypwvw.html

readonly PI=3.14
来源：http://dali.0kj1m.cn/Article/details/gtxdupxjyu.html

[R04] 位置参数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtamhjordk.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.shangyingyoupin.top/Article/details/gtlhbnurty.html

[R05] 参数默认值
来源：http://dali.aibaodan.cn/Article/details/gthpgyxwgw.html

name="${1:-default}"
来源：http://dali.ehwqpu.com/Article/details/gtlwprjdhh.html

[R06] 判断命令是否存在
来源：http://dali.bjfxy.top/Article/details/gtzdcppzgr.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.yonumen.top/Article/details/gtfnplhshg.html

[R07] if 判断文件
来源：http://dali.hnqzz.top/Article/details/gtbpdngkkz.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.gogol.net.cn/Article/details/gtmbdsegjx.html

[R08] 数值比较
来源：http://dali.yj20258888.top/Article/details/gtbtiffnyr.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.guannengcc.top/Article/details/gtguddyqug.html

[R09] 字符串比较
来源：http://dali.yonumen.top/Article/details/gtvuiyxfai.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.yuanzhike.top/Article/details/gtbojtxhnr.html

[R10] 正则匹配
来源：http://dali.jqgfzy.top/Article/details/gtkuwzzbaw.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.ppjwa.cn/Article/details/gtzscqaiul.html

[R11] case 多分支
来源：http://dali.shzxlz.cn/Article/details/gtzpmkbiwl.html

case "$1" in
来源：http://dali.zhoulong.xyz/Article/details/gtpdehjmfa.html

start) echo "启动" ;;
来源：http://dali.zycfv.cn/Article/details/gtticiwyac.html

stop)  echo "停止" ;;
来源：http://dali.haohaochexian.top/Article/details/gthnyywyms.html

*)     echo "未知命令" ;;
来源：http://dali.andypj.xyz/Article/details/gtpujdoxrk.html

esac
来源：http://dali.nanxuanxn.top/Article/details/gtqgbfiaow.html

[R12] for 遍历文件
来源：http://dali.cheryme.top/Article/details/gtkdmuhile.html

for f in *.txt; do echo "$f"; done
来源：http://dali.xylfe.cn/Article/details/gtkhezxbht.html

[R13] for 计数循环
来源：http://dali.yanxiufei.cn/Article/details/gtqlhmffgd.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.cqqwz.cn/Article/details/gtphiovazc.html

[R14] C 风格 for
来源：http://dali.daxiang520.top/Article/details/gtogkpilbn.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.aibaodan.cn/Article/details/gtuwubeljr.html

[R15] while 逐行读文件
来源：http://dali.jyoumei.cn/Article/details/gtkhdgjjvm.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zycfv.cn/Article/details/gtpkrartop.html

[R16] until 等待条件
来源：http://dali.smart0.xyz/Article/details/gtazaeytld.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zycfv.cn/Article/details/gthbspiyoi.html

[R17] 数组定义与取值
来源：http://dali.iojbl.cn/Article/details/gtrhupufoq.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.316326.xyz/Article/details/gtzkzzkagu.html

[R18] 遍历数组
来源：http://dali.ydzc1.top/Article/details/gtgcgvoicx.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.xuetiantiany.cn/Article/details/gterpoyfnr.html

[R19] 数组长度
来源：http://dali.quarkkingdee.top/Article/details/gtwwwjwhjv.html

echo "${#arr[@]}"
来源：http://dali.xylfe.cn/Article/details/gtcpzyqgpt.html

[R20] 关联数组（字典）
来源：http://dali.sufxvd.cn/Article/details/gtozozssjk.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.hnxiangtu.top/Article/details/gtnvtfcmsq.html

[R21] 字符串长度
来源：http://dali.tanke756.top/Article/details/gtoaeaxacp.html

echo "${#s}"
来源：http://dali.guowangkeji.top/Article/details/gtwdvgwdru.html

[R22] 截取子串
来源：http://dali.yonumen.top/Article/details/gtpaudqvvd.html

echo "${s:0:5}"
来源：http://dali.birdmap.top/Article/details/gtvyzesrbs.html

[R23] 字符串替换
来源：http://dali.ybcxt.top/Article/details/gtsedavheb.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.tian-w.cn/Article/details/gtuvvfqliy.html

[R24] 大小写转换
来源：http://dali.birdmap.top/Article/details/gtsjbapnks.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.sxryk.cn/Article/details/gtyanspvxv.html

[R25] 去后缀 / 去前缀
来源：http://dali.cqqwz.cn/Article/details/gtfhsgzmzd.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.yvedp.cn/Article/details/gtrzkadqjp.html

[R26] 命令替换
来源：http://dali.c1oappe.top/Article/details/gtdupkwpfo.html

now=$(date +%F); echo "$now"
来源：http://dali.hnqzz.top/Article/details/gtrsbslege.html

[R27] 算术展开
来源：http://dali.wangshuangyany.cn/Article/details/gtidtoroxk.html

echo $((1 + 2 * 3))
来源：http://dali.yj202588.top/Article/details/gtewsoknbx.html

[R28] 浮点运算
来源：http://dali.dianchejie.cn/Article/details/gtinwfmfuz.html

echo "scale=2; 10/3" | bc
来源：http://dali.sweek.top/Article/details/gtmpiwxxaf.html

[R29] 定义函数
来源：http://dali.ydzc1.top/Article/details/gtyyiqabeb.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.sxryk.cn/Article/details/gtmjroujae.html

[R30] 函数返回状态码
来源：http://dali.yangfankeji.com/Article/details/gtwgyymglu.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.cucudq.cn/Article/details/gtudtjuboy.html

[R31] 局部变量
来源：http://dali.aizwys.cn/Article/details/gtqfgsofqe.html

f() { local x=1; echo "$x"; }
来源：http://dali.ydzc1.top/Article/details/gtjgzywovx.html

[R32] 参数个数校验
来源：http://dali.guowangkeji.top/Article/details/gtcdghtmfn.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.yuxming.cn/Article/details/gtygoeceww.html

[R33] 捕获错误并提示行号
来源：http://dali.ybcxt.top/Article/details/gthahzbvng.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttxaeodxh.html

[R34] 退出时清理
来源：http://dali.yonumen.top/Article/details/gtklklzgit.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.kuanghao11.cn/Article/details/gthjwfionf.html

[R35] 后台执行并等待
来源：http://dali.pengpengdd.cyou/Article/details/gtrhuggwrw.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.snrcjt.cn/Article/details/gtysxwgept.html

[R36] 并发执行多个任务
来源：http://dali.daria6918.cn/Article/details/gtastduxna.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhiwuduotai.top/Article/details/gtyxxsdmtf.html

[R37] 把输出赋给变量
来源：http://dali.tian-w.cn/Article/details/gthwsoxhuw.html

files=$(ls -1)
来源：http://dali.zhengqikj.top/Article/details/gtsrasnsqi.html

[R38] 管道串联
来源：http://dali.shzxlz.cn/Article/details/gtxwtutmiy.html

cat a.txt | grep -i error | wc -l
来源：http://dali.yanxiufei.cn/Article/details/gtlppifasy.html

[R39] 重定向标准输出与错误
来源：http://dali.c1oappe.top/Article/details/gtjnaazlcs.html

cmd > out.log 2>&1
来源：http://dali.yj20258.top/Article/details/gtxmcjxrrr.html

[R40] 追加写日志
来源：http://dali.wangdashe.top/Article/details/gtcodcsrna.html

echo "log" >> out.log
来源：http://dali.wangshuangyany.cn/Article/details/gtixywghgu.html

[R41] 丢弃输出
来源：http://dali.daria6918.cn/Article/details/gtyeengkhf.html

cmd >/dev/null 2>&1
来源：http://dali.yj20258888.top/Article/details/gtcglmzgzq.html

[R42] 输入重定向
来源：http://dali.xylfe.cn/Article/details/gtlfpdccnl.html

wc -l < a.txt
来源：http://dali.zhixingplan.top/Article/details/gtsrkxuybe.html

[R43] 按名字查找文件
来源：http://dali.pengpengdd.cyou/Article/details/gtrbsughwu.html

find . -name "*.log" -type f
来源：http://dali.wangdashe.top/Article/details/gtroaefftf.html

[R44] 按修改时间查找
来源：http://dali.gotoacloud.top/Article/details/gtwcnwsvnd.html

find . -mtime -7 -type f
来源：http://dali.sysykeji.top/Article/details/gtlsfgbeyq.html

[R45] 批量删除
来源：http://dali.cheryme.top/Article/details/gtxmoxvznj.html

find . -name "*.tmp" -delete
来源：http://dali.ehwqpu.com/Article/details/gtbvpxxyka.html

[R46] 递归替换文件内容
来源：http://dali.dashuyun.cn/Article/details/gtmnqfgmzo.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.gotoacloud.top/Article/details/gtydkrsuyo.html

[R47] sed 单行替换
来源：http://dali.dashuyun.cn/Article/details/gtzsmipdkt.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.316326.xyz/Article/details/gtkewgyyzd.html

[R48] awk 取指定列
来源：http://dali.quarkkingdee.top/Article/details/gtyyakjxaw.html

awk '{print $1, $3}' a.txt
来源：http://dali.wangdashe.top/Article/details/gtwrvnatnv.html

[R49] awk 带条件
来源：http://dali.zhiwuduotai.top/Article/details/gtnurpxuuy.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.hfpthk.cn/Article/details/gtcrnlygae.html

[R50] awk 求和
来源：http://dali.0kj1m.cn/Article/details/gthlgmcnzl.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.yongpay.top/Article/details/gtyiwhiljt.html

[R51] 排序去重取前几
来源：http://dali.iojbl.cn/Article/details/gtkbkmjrhx.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.hywenlv.cn/Article/details/gtuzztjomd.html

[R52] 统计行数
来源：http://dali.svipenyu.cn/Article/details/gtbnsgueim.html

wc -l a.txt
来源：http://dali.ivvv.top/Article/details/gtijsvtily.html

[R53] 查看文件头与实时尾
来源：http://dali.9152youxi.cn/Article/details/gtmxtyawvw.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.wangdashe.top/Article/details/gtskoipzlc.html

[R54] 比较两个文件
来源：http://dali.jinqigfzy.top/Article/details/gteojfjvue.html

diff a.txt b.txt
来源：http://dali.chenzaomai.com/Article/details/gtzwyfeqom.html

[R55] 压缩与解压
来源：http://dali.yongpay.top/Article/details/gtnqekukry.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.aizwys.cn/Article/details/gtqpgvbwur.html

[R56] 远程拷贝
来源：http://dali.ppjwa.cn/Article/details/gtaghjwssa.html

scp file user@host:/path/
来源：http://dali.zhiwuduotai.top/Article/details/gtmkmmjghs.html

[R57] 远程执行命令
来源：http://dali.aizwys.cn/Article/details/gtsfxxlkms.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gtzupiqipk.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gtvywhcgmx.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.sxryk.cn/Article/details/gtbxhvkkkc.html

[R59] 发 POST JSON
来源：http://dali.quarkkingdee.top/Article/details/gtrhilahnu.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjfzbelqy.html

[R60] 只看 HTTP 状态码
来源：http://dali.xuanzx.com/Article/details/gtjrsewfhi.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.aizwys.cn/Article/details/gtpvdtjmng.html

[R61] 磁盘占用
来源：http://dali.ppjwa.cn/Article/details/gtitefzjyo.html

df -h;  du -sh *
来源：http://dali.nwbrower.top/Article/details/gtasnmbnkb.html

[R62] 找最占空间的文件
来源：http://dali.feifeiyinyue.top/Article/details/gtnsjzzqcg.html

du -ah . | sort -rh | head -10
来源：http://dali.nwbrower.top/Article/details/gtoevkqjhn.html

[R63] 内存与进程
来源：http://dali.gogol.net.cn/Article/details/gtbvsvmxsl.html

free -h;  ps aux | grep nginx
来源：http://dali.yuxming.cn/Article/details/gtydkmjmlx.html

[R64] 结束进程
来源：http://dali.zhengqikj.top/Article/details/gtlblyfmpm.html

kill -9 $(pgrep -f app.py)
来源：http://dali.xziqi.cn/Article/details/gtepdqxrak.html

[R65] 查看端口占用
来源：http://dali.smart0.xyz/Article/details/gtgmieajla.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.jinqigfzy.top/Article/details/gtomsderie.html

[R66] 定时任务
来源：http://dali.sufxvd.cn/Article/details/gtajucjujr.html

crontab -e;  crontab -l
来源：http://dali.zycfv.cn/Article/details/gtygcifjpu.html

[R67] 生成随机十六进制串
来源：http://dali.jinghuilouyu.cn/Article/details/gtmngwysvh.html

openssl rand -hex 16
来源：http://dali.xziqi.cn/Article/details/gtcxaaqlmy.html

[R68] 计算文件校验值
来源：http://dali.zycfv.cn/Article/details/gtggbjfkwf.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.yj202588.top/Article/details/gtvjoujkyl.html

[R69] 生成随机密码
来源：http://dali.xylfe.cn/Article/details/gtxmjonepb.html

head -c 16 /dev/urandom | base64
来源：http://dali.dianchejie.cn/Article/details/gtlwxclxce.html

[R70] 时间戳与互转
来源：http://dali.cucudq.cn/Article/details/gtlywgskrd.html

date +%s;  date -d @1700000000
来源：http://dali.zhengqikj.top/Article/details/gtugkngiqc.html

[R71] 日期格式化
来源：http://dali.zhoulong.xyz/Article/details/gtowkysxlb.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.sweek.top/Article/details/gtlhzuuunf.html

[R72] 等待端口就绪
来源：http://dali.xuanzx.com/Article/details/gtbbdbfqyn.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.iojbl.cn/Article/details/gtfrlkpskn.html

[R73] 分割大日志
来源：http://dali.aizwys.cn/Article/details/gtuftvpgcl.html

split -l 1000 big.log part_
来源：http://dali.hywenlv.cn/Article/details/gtasdzlrwc.html

[R74] 批量重命名
来源：http://dali.fengsongda.top/Article/details/gtoqqxlazi.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.nwbrower.top/Article/details/gtjyytswql.html

[R75] 导出环境变量
来源：http://dali.jqgfzy.top/Article/details/gtkzpnoqoy.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.316326.xyz/Article/details/gtydgaubdj.html

[R76] 使用临时文件
来源：http://dali.sweek.top/Article/details/gtkrjtzidm.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.shzxlz.cn/Article/details/gtiiislhnh.html

[R77] 读取用户输入
来源：http://dali.mhx1999.top/Article/details/gtjexboosb.html


<!-- 参考信息 -->