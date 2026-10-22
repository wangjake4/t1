代发 wailian999

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2soyfhrca.html

[Q28] 求和与平均
来源：http://dali.wangdashe.top/Article/details/gt2gygzqwjl.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.9152youxi.cn/Article/details/gt2nrauhwdo.html

[Q29] 最大最小值
来源：http://dali.hongshengwenyu.top/Article/details/gt2ckmsgute.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.feifeiyinyue.top/Article/details/gt2enlyfrvk.html

[Q30] 分组统计
来源：http://dali.yueranfly.top/Article/details/gt2axlqvhqn.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.hongshengwenyu.top/Article/details/gt2ihhscski.html

[Q31] 分组后过滤
来源：http://dali.hnxiangtu.top/Article/details/gt2ibhwjqge.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.cashguo.top/Article/details/gt2piiqxuon.html

[Q32] 分组拼接字符串
来源：http://dali.fzhhl.top/Article/details/gt2guskprps.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.jlsjyb.cn/Article/details/gt2uaeibomr.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.jinqigfzy.top/Article/details/gt2oksfuciw.html

[Q33] 多列分组
来源：http://dali.shangyingyoupin.top/Article/details/gt2thmgyrqz.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.sweek.top/Article/details/gt2fuuwvxiu.html

[Q34] 每组取第一条
来源：http://dali.cucudq.cn/Article/details/gt2azvfhxmy.html

SELECT * FROM (
来源：http://dali.yuanzhike.top/Article/details/gt2zhahswqs.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.nanxinkj.top/Article/details/gt2sxsabefy.html

) t WHERE rn = 1;
来源：http://dali.yanxiufei.cn/Article/details/gt2pgurpplq.html

[Q35] 内连接
来源：http://dali.daria6918.cn/Article/details/gt2nvenwwpy.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.cqqwz.cn/Article/details/gt2ywgpbmhr.html

[Q36] 左连接
来源：http://dali.jyoumei.cn/Article/details/gt2pauzodxo.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.redwolf501.top/Article/details/gt2wgiomoko.html

[Q37] 右连接
来源：http://dali.aizwys.cn/Article/details/gt2dkyinkxj.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.svipenyu.cn/Article/details/gt2lbvbdohn.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.vqdsnc.cn/Article/details/gt2pogctdzt.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.yuxming.cn/Article/details/gt2nwgxqhku.html

[Q39] 自连接（查上下级）
来源：http://dali.316326.xyz/Article/details/gt2copcynlh.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.aibaodan.cn/Article/details/gt2zzytnbjs.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.sysykeji.top/Article/details/gt2gfduqkoq.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.chenjidiqi.icu/Article/details/gt2wihwcsrz.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.yongpay.top/Article/details/gt2efvtyzur.html

[Q41] 多表连接
来源：http://dali.hongshengwenyu.top/Article/details/gt2quvfpayr.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.smart0.xyz/Article/details/gt2bdioysny.html

JOIN users u ON u.id = o.user_id
来源：http://dali.ppjwa.cn/Article/details/gt2dwlcsiht.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhixingplan.top/Article/details/gt2jzegvhza.html

[Q42] 连接条件附加过滤
来源：http://dali.ppjwa.cn/Article/details/gt2qzmvjdso.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhixingplan.top/Article/details/gt2csjiifxf.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.hfpthk.cn/Article/details/gt2lauzslbe.html

[Q43] 标量子查询
来源：http://dali.yongpay.top/Article/details/gt2xkshrxkr.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhixingplan.top/Article/details/gt2ykxqwfwr.html

[Q44] IN 子查询
来源：http://dali.ivvv.top/Article/details/gt2vmmwktwn.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.ybcxt.top/Article/details/gt2elpftsxb.html

[Q45] EXISTS 判断存在
来源：http://dali.cucudq.cn/Article/details/gt2oukgikaa.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.daxiang520.top/Article/details/gt2tkpweqvl.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.shangyingyoupin.top/Article/details/gt2ghyqjitb.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yuanzhike.top/Article/details/gt2rrsinyap.html

[Q47] 与平均值比较
来源：http://dali.xylfe.cn/Article/details/gt2oncycfkq.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.tian-w.cn/Article/details/gt2iacpzwys.html

[Q48] CTE 公用表表达式
来源：http://dali.yuanzhike.top/Article/details/gt2hxsyeefu.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.wangshuangyany.cn/Article/details/gt2pwdlbryf.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.nwbrower.top/Article/details/gt2iqmfiebi.html

[Q49] 更新单行
来源：http://dali.vqdsnc.cn/Article/details/gt2ssswhjno.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.hongshengwenyu.top/Article/details/gt2nfkzjgyz.html

[Q50] 批量更新
来源：http://dali.0kj1m.cn/Article/details/gt2fjzpdpam.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.cheryme.top/Article/details/gt2fwoehgbu.html

[Q51] 用子查询更新
来源：http://dali.wangshuangyany.cn/Article/details/gt2irwfbpiw.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.gaohongyu789.top/Article/details/gt2dfqopigb.html

[Q52] 删除指定行
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zyviylgb.html

DELETE FROM users WHERE id = 10;
来源：http://dali.xuetiantiany.cn/Article/details/gt2sqdbxgdn.html

[Q53] 按条件删除
来源：http://dali.shangyingyoupin.top/Article/details/gt2vldruetl.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.wangshuangyany.cn/Article/details/gt2plzrsbvw.html

[Q54] 清空表
来源：http://dali.0kj1m.cn/Article/details/gt2lkvlxboz.html

TRUNCATE TABLE logs;
来源：http://dali.andypj.xyz/Article/details/gt2jmthieqj.html

[Q55] 排名（并列占位）
来源：http://dali.yj20258888.top/Article/details/gt2uevzpjkq.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.mhx1999.top/Article/details/gt2lujkboan.html

[Q56] 密集排名（并列不占位）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2twaujitn.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.nanxuanxn.top/Article/details/gt2jmskbtko.html

[Q57] 行号
来源：http://dali.redwolf501.top/Article/details/gt2useyopme.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.gotoacloud.top/Article/details/gt2csfgpkoq.html

[Q58] 累计求和
来源：http://dali.9152youxi.cn/Article/details/gt2petbjeja.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.cheryme.top/Article/details/gt2xivzcack.html

[Q59] 分组内累计
来源：http://dali.nanxuanxn.top/Article/details/gt2wgdrmmfp.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.ehwqpu.com/Article/details/gt2mbeggwnm.html

[Q60] 取上一行 / 下一行
来源：http://dali.havefunace.top/Article/details/gt2yorphsog.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hjrzgpkf.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.gaohongyu789.top/Article/details/gt2sycrslel.html

[Q61] 移动平均
来源：http://dali.gaohongyu789.top/Article/details/gt2basdkfoc.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.chenzaomai.com/Article/details/gt2xpzqsaum.html

[Q62] 分组占比
来源：http://dali.zhiwuduotai.top/Article/details/gt2cadnytfs.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.cheryme.top/Article/details/gt2luijrsvq.html

[Q63] 开启事务
来源：http://dali.zhongyouzk.top/Article/details/gt2kjorcbzw.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.xziqi.cn/Article/details/gt2latcmfyi.html

[Q64] 提交事务
来源：http://dali.wangshuangyany.cn/Article/details/gt2taujevsi.html

COMMIT;
来源：http://dali.gotoacloud.top/Article/details/gt2pmyguqax.html

[Q65] 回滚事务
来源：http://dali.cashguo.top/Article/details/gt2ejholdnm.html

ROLLBACK;
来源：http://dali.jiagoushi.top/Article/details/gt2lyqljecw.html

[Q66] 行锁查询
来源：http://dali.chenjidiqi.icu/Article/details/gt2xvskaush.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhengqikj.top/Article/details/gt2kijuheis.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2bgltgeij.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.pengpengdd.cyou/Article/details/gt2hljiflfz.html

[Q68] 保存点
来源：http://dali.yuxming.cn/Article/details/gt2ubgmwnns.html

SAVEPOINT sp1;
来源：http://dali.cheryme.top/Article/details/gt2ydiiylee.html

ROLLBACK TO sp1;
来源：http://dali.dashuyun.cn/Article/details/gt2csmloxgu.html

[Q69] 查看执行计划
来源：http://dali.cqqwz.cn/Article/details/gt2gfpidhvy.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.jyoumei.cn/Article/details/gt2ysbndvlo.html

[Q70] 更新统计信息
来源：http://dali.daxiang520.top/Article/details/gt2oftcsssq.html

ANALYZE TABLE users;
来源：http://dali.jinqigfzy.top/Article/details/gt2benchxul.html

[Q71] 查看建表语句
来源：http://dali.guannengcc.top/Article/details/gt2tndkeqcj.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.jqgfzy.top/Article/details/gt2pnzeurxm.html

[Q72] 查看索引
来源：http://dali.hongshengwenyu.top/Article/details/gt2srbxeiop.html

SHOW INDEX FROM users;
来源：http://dali.birdmap.top/Article/details/gt2mogjqkyx.html

[Q73] 查看表状态
来源：http://dali.jlsjyb.cn/Article/details/gt2nzrfxgah.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.nwbrower.top/Article/details/gt2cgnljvge.html

[Q74] 强制使用索引
来源：http://dali.zdqjudy.top/Article/details/gt2dvcotvuu.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.jyoumei.cn/Article/details/gt2wpwsjeis.html

[Q75] 日期格式化
来源：http://dali.yongpay.top/Article/details/gt2bmmtfztn.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.ybcxt.top/Article/details/gt2vboytyji.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.haohaochexian.top/Article/details/gt2yynsdxlz.html

[Q76] 按天统计
来源：http://dali.zhoulong.xyz/Article/details/gt2rjmkywhh.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.xylfe.cn/Article/details/gt2xejbgrxu.html

[Q77] 时间加减
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dcryxykj.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.dashuyun.cn/Article/details/gt2kwzpqbwn.html

[Q78] 当前时间
来源：http://dali.hnqzz.top/Article/details/gt2wflvysla.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.chenjidiqi.icu/Article/details/gt2jnzpbdho.html

[Q79] 字符串拼接
来源：http://dali.9152youxi.cn/Article/details/gt2lbqqcrnm.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.pycfn.com/Article/details/gt2lwdvvhgg.html

[Q80] 字符串截取
来源：http://dali.sufxvd.cn/Article/details/gt2bobfqehk.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.sweek.top/Article/details/gt2vyescxnw.html

[Q81] 字符串替换
来源：http://dali.yvedp.cn/Article/details/gt2aapyqzun.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.jinqigufen.top/Article/details/gt2jozrkclr.html

[Q82] 字符长度与字节长度
来源：http://dali.dianchejie.cn/Article/details/gt2etrazrol.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.tianlin.xyz/Article/details/gt2vrcsbzjr.html

[Q83] 大小写转换
来源：http://dali.pengpengdd.cyou/Article/details/gt2sdjaccmm.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.yangfankeji.com/Article/details/gt2houstphp.html

[Q84] 去除首尾空格
来源：http://dali.redwolf501.top/Article/details/gt2cmipaing.html

SELECT TRIM(name) FROM users;
来源：http://dali.yj202588.top/Article/details/gt2ykbuarwr.html

[Q85] 数值取整
来源：http://dali.hysaishi.cn/Article/details/gt2npdzocuy.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.cheryme.top/Article/details/gt2dgxrqkxe.html

[Q86] 读取 JSON 字段
来源：http://dali.zhengqikj.top/Article/details/gt2mhngsqvj.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.chenlongwang.top/Article/details/gt2bdunmvim.html

[Q87] JSON 字段做条件
来源：http://dali.yuanzhike.top/Article/details/gt2wvzijxfl.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.nanxinkj.top/Article/details/gt2ckbccxay.html

[Q88] 行转列（条件聚合）
来源：http://dali.daria6918.cn/Article/details/gt2vmimkgyq.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.daxiang520.top/Article/details/gt2rwrrnoll.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.c1oappe.top/Article/details/gt2rfgatmwk.html

[Q89] 判断表是否存在
来源：http://dali.sysykeji.top/Article/details/gt2oizjzoqn.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.aibaodan.cn/Article/details/gt2pljhzgea.html

[Q90] 生成序号列
来源：http://dali.cheryme.top/Article/details/gt2fcmltdup.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.jianghu66.top/Article/details/gt2qfaaocgc.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fmjasymh.html

R. Bash 专题
来源：http://dali.fzhhl.top/Article/details/gt2nkhhkvob.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2ceewbbgi.html

[R01] shebang 与严格模式
来源：http://dali.chenzaomai.com/Article/details/gt2ekisigcv.html

#!/usr/bin/env bash
来源：http://dali.dashuyun.cn/Article/details/gt2zhwqemhm.html

set -euo pipefail
来源：http://dali.cdnleiting.top/Article/details/gt2wejqynec.html

[R02] 变量赋值与使用
来源：http://dali.iojbl.cn/Article/details/gt2zsmztxem.html

name="Tom"; echo "$name"
来源：http://dali.fzhhl.top/Article/details/gt2puuaybzo.html

[R03] 只读变量
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2syehwlck.html

readonly PI=3.14
来源：http://dali.yvedp.cn/Article/details/gt2pbhtapmz.html

[R04] 位置参数
来源：http://dali.ybcxt.top/Article/details/gt2jhwrlagc.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.sufxvd.cn/Article/details/gt2qhacjvbo.html

[R05] 参数默认值
来源：http://dali.yuanzhike.top/Article/details/gt2grqzuyxj.html

name="${1:-default}"
来源：http://dali.nanxuanxn.top/Article/details/gt2syetiuvw.html

[R06] 判断命令是否存在
来源：http://dali.zdqjudy.top/Article/details/gt2uevtmrvf.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.jiagoushi.top/Article/details/gt2thkvkwmi.html

[R07] if 判断文件
来源：http://dali.cucudq.cn/Article/details/gt2jokjtbpb.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.gogol.net.cn/Article/details/gt2ryzwaugm.html

[R08] 数值比较
来源：http://dali.yuanzhike.top/Article/details/gt2mcmeeant.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.dashuyun.cn/Article/details/gt2qfwaafap.html

[R09] 字符串比较
来源：http://dali.xziqi.cn/Article/details/gt2kfmuregl.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.yanxiufei.cn/Article/details/gt2hmlizcbi.html

[R10] 正则匹配
来源：http://dali.gzhubu.top/Article/details/gt2rasezzxn.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cvfplmvv.html

[R11] case 多分支
来源：http://dali.mhx1999.top/Article/details/gt2ymlvthps.html

case "$1" in
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pwlpkerg.html

start) echo "启动" ;;
来源：http://dali.ybcxt.top/Article/details/gt2cqdaeidg.html

stop)  echo "停止" ;;
来源：http://dali.nanxinkj.top/Article/details/gt2ugkloaxp.html

*)     echo "未知命令" ;;
来源：http://dali.yangfankeji.com/Article/details/gt2mtblppvz.html

esac
来源：http://dali.yvedp.cn/Article/details/gt2xcykiuau.html

[R12] for 遍历文件
来源：http://dali.kuanghao11.cn/Article/details/gt2vacgreyj.html

for f in *.txt; do echo "$f"; done
来源：http://dali.yueranfly.top/Article/details/gt2eiaverqw.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2dqpzzcbz.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.mhx1999.top/Article/details/gt2ujqbcrwk.html

[R14] C 风格 for
来源：http://dali.yonumen.top/Article/details/gt2uumfnjuv.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.yanxiufei.cn/Article/details/gt2uzhhpqla.html

[R15] while 逐行读文件
来源：http://dali.fzhhl.top/Article/details/gt2ahypxkhj.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2svmgimfk.html

[R16] until 等待条件
来源：http://dali.mhx1999.top/Article/details/gt2yhxvxcoo.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.cucudq.cn/Article/details/gt2kdhnsxob.html

[R17] 数组定义与取值
来源：http://dali.jiagoushi.top/Article/details/gt2qkkhonnr.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhixingplan.top/Article/details/gt2udhuxqnj.html

[R18] 遍历数组
来源：http://dali.shangyingyoupin.top/Article/details/gt2khowfalp.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bigiqicc.html

[R19] 数组长度
来源：http://dali.zdqjudy.top/Article/details/gt2ivwqdrsu.html

echo "${#arr[@]}"
来源：http://dali.redwolf501.top/Article/details/gt2rbrfdsov.html

[R20] 关联数组（字典）
来源：http://dali.hysaishi.cn/Article/details/gt2iqcutzml.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.haohaochexian.top/Article/details/gt2xdgjkksy.html

[R21] 字符串长度
来源：http://dali.zhoulong.xyz/Article/details/gt2qlhvtxfm.html

echo "${#s}"
来源：http://dali.feifeiyinyue.top/Article/details/gt2jmlhibpc.html

[R22] 截取子串
来源：http://dali.yuanzhike.top/Article/details/gt2wccsdcfs.html

echo "${s:0:5}"
来源：http://dali.wangdashe.top/Article/details/gt2eiteunli.html

[R23] 字符串替换
来源：http://dali.wangdashe.top/Article/details/gt2ekpcjjtg.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.nwbrower.top/Article/details/gt2rnbkqpnm.html

[R24] 大小写转换
来源：http://dali.jinqigfzy.top/Article/details/gt2ydxjpqch.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.ydzc1.top/Article/details/gt2fkbobdoi.html

[R25] 去后缀 / 去前缀
来源：http://dali.hywenlv.cn/Article/details/gt2iiygnjbv.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhixingplan.top/Article/details/gt2kznytebv.html

[R26] 命令替换
来源：http://dali.yuanzhike.top/Article/details/gt2qhrrmclz.html

now=$(date +%F); echo "$now"
来源：http://dali.chenzaomai.com/Article/details/gt2qkmmijab.html

[R27] 算术展开
来源：http://dali.yvedp.cn/Article/details/gt2tguekuce.html

echo $((1 + 2 * 3))
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fgqbpsql.html

[R28] 浮点运算
来源：http://dali.hnqzz.top/Article/details/gt2qigohqey.html

echo "scale=2; 10/3" | bc
来源：http://dali.cucudq.cn/Article/details/gt2qijkantn.html

[R29] 定义函数
来源：http://dali.ivvv.top/Article/details/gt2knzgdkcl.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.sweek.top/Article/details/gt2bvdiioap.html

[R30] 函数返回状态码
来源：http://dali.zhengqikj.top/Article/details/gt2xssampeq.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.fzhhl.top/Article/details/gt2ebnrbzac.html

[R31] 局部变量
来源：http://dali.yuxming.cn/Article/details/gt2anyytbmg.html

f() { local x=1; echo "$x"; }
来源：http://dali.jiagoushi.top/Article/details/gt2vjsnddww.html

[R32] 参数个数校验
来源：http://dali.gotoacloud.top/Article/details/gt2dqrlvdfa.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhixingplan.top/Article/details/gt2zdwlegwe.html

[R33] 捕获错误并提示行号
来源：http://dali.tanke756.top/Article/details/gt2orhyodpo.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.ehwqpu.com/Article/details/gt2aiawrdus.html

[R34] 退出时清理
来源：http://dali.aibaodan.cn/Article/details/gt2bajamsyf.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.sxryk.cn/Article/details/gt2kxcbornu.html

[R35] 后台执行并等待
来源：http://dali.zhongyouzk.top/Article/details/gt2ojnusdbf.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.ybcxt.top/Article/details/gt2ktzieurh.html

[R36] 并发执行多个任务
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sugeecut.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.hywenlv.cn/Article/details/gt2wlmklwfw.html

[R37] 把输出赋给变量
来源：http://dali.yj20258888.top/Article/details/gt2usfamcwm.html

files=$(ls -1)
来源：http://dali.nwbrower.top/Article/details/gt2yeqmjfwf.html

[R38] 管道串联
来源：http://dali.redwolf501.top/Article/details/gt2ulicizat.html

cat a.txt | grep -i error | wc -l
来源：http://dali.yongpay.top/Article/details/gt2kgrpyrlt.html

[R39] 重定向标准输出与错误
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gkiborsz.html

cmd > out.log 2>&1
来源：http://dali.guowangkeji.top/Article/details/gt2ljwboonb.html

[R40] 追加写日志
来源：http://dali.9152youxi.cn/Article/details/gt2zpunougd.html

echo "log" >> out.log
来源：http://dali.quarkkingdee.top/Article/details/gt2urpkoqwf.html

[R41] 丢弃输出
来源：http://dali.sxryk.cn/Article/details/gt2ismpfpfw.html

cmd >/dev/null 2>&1
来源：http://dali.ivvv.top/Article/details/gt2dxvqzoso.html

[R42] 输入重定向
来源：http://dali.guannengcc.top/Article/details/gt2xhmscehp.html

wc -l < a.txt
来源：http://dali.jiagoushi.top/Article/details/gt2yvwmtzwk.html

[R43] 按名字查找文件
来源：http://dali.xziqi.cn/Article/details/gt2ydmgdsvo.html

find . -name "*.log" -type f
来源：http://dali.316326.xyz/Article/details/gt2sgbazgmp.html

[R44] 按修改时间查找
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wmvyrjoc.html

find . -mtime -7 -type f
来源：http://dali.nwbrower.top/Article/details/gt2tyrvjoji.html

[R45] 批量删除
来源：http://dali.jlsjyb.cn/Article/details/gt2adsdodjb.html

find . -name "*.tmp" -delete
来源：http://dali.zdqjudy.top/Article/details/gt2udiepmio.html

[R46] 递归替换文件内容
来源：http://dali.nanxuanxn.top/Article/details/gt2yqdbkzcb.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.andypj.xyz/Article/details/gt2goaxidyb.html

[R47] sed 单行替换
来源：http://dali.xinyue.icu/Article/details/gt2dlbwcfok.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.sxryk.cn/Article/details/gt2ctroewfr.html

[R48] awk 取指定列
来源：http://dali.jianghu66.top/Article/details/gt2koiqyhdy.html

awk '{print $1, $3}' a.txt
来源：http://dali.hnqzz.top/Article/details/gt2godrwcss.html

[R49] awk 带条件
来源：http://dali.fzhhl.top/Article/details/gt2wvgkwync.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.ybcxt.top/Article/details/gt2kvgjsozb.html

[R50] awk 求和
来源：http://dali.yangfankeji.com/Article/details/gt2exbkmhpc.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.cheryme.top/Article/details/gt2vfevkrbr.html

[R51] 排序去重取前几
来源：http://dali.tianlin.xyz/Article/details/gt2hxliltaj.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.sysykeji.top/Article/details/gt2jqeuafrz.html

[R52] 统计行数
来源：http://dali.yvedp.cn/Article/details/gt2hwbeplbw.html

wc -l a.txt
来源：http://dali.tian-w.cn/Article/details/gt2aslopbkq.html

[R53] 查看文件头与实时尾
来源：http://dali.pycfn.com/Article/details/gt2ynphtrud.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.dianchejie.cn/Article/details/gt2zenarbok.html

[R54] 比较两个文件
来源：http://dali.0kj1m.cn/Article/details/gt2kqipovzk.html

diff a.txt b.txt
来源：http://dali.tanke756.top/Article/details/gt2ootmlkkw.html

[R55] 压缩与解压
来源：http://dali.jqgufenzy.top/Article/details/gt2ksdkqgju.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zdqjudy.top/Article/details/gt2udzsyfen.html

[R56] 远程拷贝
来源：http://dali.zhiwuduotai.top/Article/details/gt2gqxrwurw.html

scp file user@host:/path/
来源：http://dali.daria6918.cn/Article/details/gt2litepwgg.html

[R57] 远程执行命令
来源：http://dali.shuidangran.top/Article/details/gt2wbxdlwwi.html

ssh user@host 'uptime'
来源：http://dali.0kj1m.cn/Article/details/gt2cgxhxjsb.html

[R58] 下载文件
来源：http://dali.vqdsnc.cn/Article/details/gt2rzerizus.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.yj20258.top/Article/details/gt2exzqessa.html

[R59] 发 POST JSON
来源：http://dali.jinqigfzy.top/Article/details/gt2egcorufd.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhongyouzk.top/Article/details/gt2bextfeav.html

[R60] 只看 HTTP 状态码
来源：http://dali.birdmap.top/Article/details/gt2bipjxhtt.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.ybcxt.top/Article/details/gt2awjtsltp.html

[R61] 磁盘占用
来源：http://dali.gzhubu.top/Article/details/gt2mnodwtyl.html

df -h;  du -sh *
来源：http://dali.chenjidiqi.icu/Article/details/gt2adrbvqxm.html

[R62] 找最占空间的文件
来源：http://dali.hfpthk.cn/Article/details/gt2gqeujbow.html

du -ah . | sort -rh | head -10
来源：http://dali.gzhubu.top/Article/details/gt2kmufhfrk.html

[R63] 内存与进程
来源：http://dali.aizwys.cn/Article/details/gt2iqgpwekb.html

free -h;  ps aux | grep nginx
来源：http://dali.ppjwa.cn/Article/details/gt2kgdxqgqx.html

[R64] 结束进程
来源：http://dali.wangdashe.top/Article/details/gt2itjytdwy.html

kill -9 $(pgrep -f app.py)
来源：http://dali.dashuyun.cn/Article/details/gt2pngqyint.html

[R65] 查看端口占用
来源：http://dali.0kj1m.cn/Article/details/gt2upgpkxdn.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.nanxuanxn.top/Article/details/gt2ijagzmyc.html

[R66] 定时任务
来源：http://dali.cashguo.top/Article/details/gt2ykqzmegs.html

crontab -e;  crontab -l
来源：http://dali.nanxuanxn.top/Article/details/gt2vullpzcm.html

[R67] 生成随机十六进制串
来源：http://dali.shanyushiyangtech.top/Article/details/gt2iscedzbx.html

openssl rand -hex 16
来源：http://dali.yj202588.top/Article/details/gt2giiipvzs.html

[R68] 计算文件校验值
来源：http://dali.xinyue.icu/Article/details/gt2rkicgtsw.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.chenlongwang.top/Article/details/gt2rhzcpofb.html

[R69] 生成随机密码
来源：http://dali.dianchejie.cn/Article/details/gt2ztojqhst.html

head -c 16 /dev/urandom | base64
来源：http://dali.jiagoushi.top/Article/details/gt2mlifnoxh.html

[R70] 时间戳与互转
来源：http://dali.pycfn.com/Article/details/gt2bcieftqp.html

date +%s;  date -d @1700000000
来源：http://dali.sweek.top/Article/details/gt2ewxzcakn.html

[R71] 日期格式化
来源：http://dali.sysykeji.top/Article/details/gt2mruhgbvx.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.shuidangran.top/Article/details/gt2kuenfqho.html

[R72] 等待端口就绪
来源：http://dali.gaohongyu789.top/Article/details/gt2gbwqgxgl.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.hammf.cn/Article/details/gt2opfizegu.html

[R73] 分割大日志
来源：http://dali.daria6918.cn/Article/details/gt2wbpcgleh.html

split -l 1000 big.log part_
来源：http://dali.9152youxi.cn/Article/details/gt2lzcgekss.html

[R74] 批量重命名
来源：http://dali.yonumen.top/Article/details/gt2imonmsye.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.yuxming.cn/Article/details/gt2bnywghbi.html

[R75] 导出环境变量
来源：http://dali.zhixingplan.top/Article/details/gt2tkmplcgb.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.hfpthk.cn/Article/details/gt2kdufhbhj.html

[R76] 使用临时文件
来源：http://dali.iojbl.cn/Article/details/gt2riscxohw.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.ybcxt.top/Article/details/gt2sotpajco.html

[R77] 读取用户输入
来源：http://dali.svipenyu.cn/Article/details/gt2sbqruapc.html


<!-- 参考信息 -->